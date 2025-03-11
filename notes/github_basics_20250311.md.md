
# F2E02 前端應用開發工程師實戰養成班（專題指導補充）
## 目錄
- [F2E02 前端應用開發工程師實戰養成班（專題指導補充）](#f2e02-前端應用開發工程師實戰養成班專題指導補充)
  - [目錄](#目錄)
  - [HTML 表格秘訣](#html-表格秘訣)
  - [GitHub 基礎介紹](#github-基礎介紹)
  - [GitHub 特色](#github-特色)
  - [經營自己的 LeetCode 介面](#經營自己的-leetcode-介面)
    - [在 GitHub 建立 README](#在-github-建立-readme)
    - [Pinned Repositories，放上完整的作品](#pinned-repositories放上完整的作品)
  - [GitHub 基本操作](#github-基本操作)
    - [建立 SSH 連線](#建立-ssh-連線)
- [GitHub SSH 連線設定](#github-ssh-連線設定)
    - [透過 GitHub 網頁介面建立倉庫](#透過-github-網頁介面建立倉庫)
  - [create repository](#create-repository)
  - [create a new respository](#create-a-new-respository)
  - [本地端初始化 git 指令](#本地端初始化-git-指令)
  - [提交 (Commit) 與推送 (Push)](#提交-commit-與推送-push)
  - [Git clone](#git-clone)
  - [版本控制與分支 (Branch)](#版本控制與分支-branch)
  - [GitHub 團隊協作](#github-團隊協作)
  - [GitHub Actions 自動化（進階）](#github-actions-自動化進階)
  - [可以試著做看看](#可以試著做看看)

## HTML 表格秘訣
- 先畫大輪廓再處理細節
- 大輪廓：`<table>` > `<thead>`> `<tfoot>`> `<tbody>` 
- `<tr>`（垂直列） 包 `<td>` or `<th>`
- 由上往下數，直的有幾行，就有幾個 `<tr>`
- 水平合併 `colspan`
- 垂直合併 `rowspan`


## GitHub 基礎介紹

- [GitHub](https://github.com/) 是一個線上軟體程式代管服務平台，用於公開程式或軟體的代碼，使用Git作為版本控制軟體，允許開發者和團隊一同管理和開發軟體專案。

## GitHub 特色
- 類似軟體界的 Instagram + LinkedIn
- 為開源專案貢獻、促進團隊合作
- 展示你的專案或能力
- 查找新技術、文件

## 經營自己的 LeetCode 介面

### 在 GitHub 建立 README
1. 在 GitHub 上創建一個與你的用戶名完全相同的Repo。
2. Repo必須公開。
3. 在Repo中創建一個 README.md 文件。
4. 編輯 README.md 文件，加入你想展示的內容。
5. 提交並推送變更。

### Pinned Repositories，放上完整的作品


## GitHub 基本操作
- 請先註冊 GitHub 帳號
### 建立 SSH 連線

# GitHub SSH 連線設定
- SSH or HTTPS




### 透過 GitHub 網頁介面建立倉庫
## create repository

## create a new respository
- Public vs. Private


## 本地端初始化 git 指令

```
$ git init
$ git remote add origin <repo-url>
```

## 提交 (Commit) 與推送 (Push)
```
$ git add .（將變更加入暫存區）
$ git commit -m "描述這次變更"
$ git push origin main（推送到遠端）
```

## Git clone
```
$ Clone 倉庫到本地端
$ git clone <repo-url>
```

## 版本控制與分支 (Branch)
- 為什麼要使用分支？
- git branch feature-new
- git checkout feature-new / git switch feature-new
- git merge feature-new
- git pull 更新遠端內容

## GitHub 團隊協作
- Issues & Project Board
- 修改後發送 Pull Request (PR)
- Code Review
- 如何審查程式碼、留言、建議修改


## GitHub Actions 自動化（進階）
- 設定 CI/CD（持續整合/部署）
- 自動測試與部署

## 可以試著做看看
- 申請 GitHub帳戶、更新簡介
- 建立倉庫、本機連線、提交變更、Push
- 模擬團隊開發流程：
  - 建立分支、新增功能、提交 PR、合併