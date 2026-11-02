# Unity 6 遊戲教學與 AI 協作範本

適用 Editor：**Unity 6000.3.17f1**。文件使用繁體中文，輸入統一使用 **Input System Package (New)**。

這是資料夾與協作文件骨架，尚不是能直接執行的完整 Unity 專案，未包含遊戲程式、場景與 Unity 產生的設定。請先依 [初始化指南](docs/02_初始化與InputSystem.md) 建立真正的專案，再合併本骨架。

## 閱讀順序

1. [資料夾與文件說明](docs/01_資料夾與文件說明.md)
2. [初始化與 Input System](docs/02_初始化與InputSystem.md)
3. [AI 協作流程](docs/03_AI協作流程.md)
4. [教學路線與發布檢查](docs/04_教學與發布檢查.md)

AI 開始工作前須讀取根目錄 `AGENTS.md`；不會自動讀取的工具，請使用 `docs/05_AI啟動提示詞.md`。

建議 Repo 名稱：`Unity6-AI-Teaching-Template`。建立 GitHub 公開 Repository 後，在 Settings 勾選 Template repository，讓同學以 Use this template 建立各自專案。正式開放前，先完成 Unity 初始化與 Editor 驗證。

## 授權

尚未選定授權。建議自有程式與文件採 MIT；公開前由維護者加入正式 LICENSE。第三方素材須各自確認可否再散布，不能直接套用專案授權。

5. [Agent 相容性與解壓縮指南](docs/06_Agent相容性與解壓縮指南.md)

已提供 Codex、Kiro、Antigravity 與 Claude Code 入口，以及 .gitignore。請完整解壓縮，包含以點開頭的檔案與資料夾。

## 課程資產架構 v0.2

3D 資產以 `Assets/_Project/Art/Models/<模型名稱>/` 為單位，FBX、專屬貼圖／材質直接同層存放；可共用的 Material 放在 `Art/Materials/`。2D Sprite 與逐格動畫依角色放在 `Art/Sprites/<角色名稱>/`。詳見 `docs/01_資料夾與文件說明.md`。本 ZIP 不包含實際 Cat 模型或 Roll a Ball 程式碼。

1. 專案資訊

專案名稱

Unity 版本：6000.3.17f1

使用的 Git 工具:GitHub

2. Step-by-step 操作紀錄

簡單說明自己如何：

先使用 Unity Hub 建立一個新的空白 Unity 專案，並確認使用的版本為 6000.3.17f1。建立完成後，確認專案裡有 Assets、Packages、ProjectSettings 和 .gitignore 等必要檔案。

開啟 GitHub Desktop 並登入自己的 GitHub 帳號，接著將建立好的 Unity 專案加入 GitHub Desktop，開始進行版本控制。

確認專案檔案沒有問題後，在 GitHub Desktop 輸入 Commit 訊息，並點擊 Commit to main，完成第一次版本紀錄。

完成 Commit 後，點擊 Publish Repository，將 Unity 專案上傳到自己的 GitHub Repository，並設定為公開（Public）。

進入 GitHub 網站查看自己的 Repository，確認 Assets、Packages、ProjectSettings、.gitignore 等檔案都有成功上傳。


3. 學習心得

Commit：Commit就像是幫專案做一次存檔，可以記錄目前的檔案內容和修改狀況。如果之後修改錯誤，也可以查看之前儲存的版本。

Push：Push是將自己電腦裡已經 Commit 的內容上傳到 GitHub，讓專案可以保存在網路上，也方便之後分享給別人查看。

Pull：Pull 是將 GitHub 上最新的檔案下載並同步到自己的電腦。如果在其他電腦修改過專案，就可以透過 Pull 取得最新的內容。
