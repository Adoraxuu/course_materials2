# F2E02 前端應用開發工程師實戰養成班
## 專題指導補充 推薦開發工具 2025/03/06

#### Wappalyzer
- 查看網站的技術
- [Wappalyzer 官網](https://www.wappalyzer.com/)
- [chrome 擴充](https://chromewebstore.google.com/detail/wappalyzer-technology-pro/gppongmhjkpfnbhagpmjfkannfbllamg?hl=zh-TW)
- 範例：
    [VuePress](https://vuepress.vuejs.org/)
    ![截圖 2025-03-06 上午10.32.34](https://hackmd.io/_uploads/rkKUKKUske.png)
    
    [BeHance](https://www.behance.net/)
    
    ![截圖 2025-03-06 上午10.34.49](https://hackmd.io/_uploads/rJnucFLoyl.png)


    
### 開發者工具
- [Chrome 開發人員工具](https://developer.chrome.com/docs/devtools/open?hl=zh-tw)
- 元素 elements 
- 樣式 styles
- Computed 計算樣式
- [範例網站](https://www.lccnet.com.tw/lccnet)
![截圖 2025-03-06 上午11.10.34](https://hackmd.io/_uploads/H1cvz9Uj1l.png)

    
 
### 網站設計

#### 配色：
- [coolors](https://coolors.co/)

![截圖 2025-03-06 上午11.25.06](https://hackmd.io/_uploads/S1EsBqLiyg.png)


##### 找靈感
- [Pinterest](https://www.pinterest.com/search/pins/?q=web&rs=typed)

![截圖 2025-03-06 上午11.33.58](https://hackmd.io/_uploads/Syabu98sJl.png)

#### 設計：
- [Figma](https://www.figma.com/)

![截圖 2025-03-06 上午11.29.28](https://hackmd.io/_uploads/S1ciIcLoyx.png)


#### 流程圖
- [Miro](https://miro.com/)
- [Xmind](https://xmind.app/)
- [mindmeister](https://www.mindmeister.com/)

##### 製作簡易圖片
- [Canva](https://www.canva.com/)

### 套件
![截圖 2025-03-06 下午1.29.00](https://hackmd.io/_uploads/r1anfhUsyg.png)


## vscode 內安裝 code .

![截圖 2025-03-06 下午2.20.21](https://hackmd.io/_uploads/SJ230nIo1e.png)

- 在 vscode 按 `Command Shift + P`(mac) or `Ctrl Shift + P`(windows)

- 出現如上述圖片的工具列後，輸入：
```
Shell Command: Install 'code' command in PATH
```
- 按 Enter or 點擊 `殼層命令:
在 PATH 中安裝'{0}' 命令`

- 完成後開啟終端機， 輸入 `code .`，即可在所在資料夾開啟 VScode

- `code .` 指令含義：
    - `code` 是 VS Code 的命令列工具
    - `.` 代表目前所在的資料夾


輸入以上指令會執行以下的事：
- 把 code 命令安裝到系統的 PATH 中
- 讓你可以在 終端機 直接執行 code 指令來開啟 VS Code
    

#### 出現問題
以下指令皆是在 **終端機** 執行
##### 強制讓 code 可以被執行

```
$ sudo chmod +x /usr/local/bin/code
```
指令說明：
1. `sudo`（Super User DO）：用「管理員（root）」權限來執行該指令。因為 /usr/local/bin/ 目錄通常需要管理員權限來修改。
2. `chmod`（Change Mode）：修改檔案的權限。
3. `+x`（加上可執行權限）：讓 code 這個檔案可以被執行（執行程式）。
4. `/usr/local/bin/code`：這是 VS Code 的命令行執行檔案，它的作用是讓你可以在終端機使用 code . 來打開 VS Code。
    

##### 刪除 code 指令
- 如果還是有錯誤，可以刪除 code 指令再重新從第一步開始
```
$ sudo rm -f /usr/local/bin/code
```

##### 確認 code 有無安裝
- 可以使用指令，看看目前的 code 有無安裝
```
$ code --version
```

### VScode 指令
- [mac](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf)
- [windows](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)
- 來源 [VScode Docs](https://code.visualstudio.com/docs/editor/keybindings)