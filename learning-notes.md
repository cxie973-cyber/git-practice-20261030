# Git 教學影片演練筆記

日期：2026-10-30（Asia/Taipei）。

## 教材與對應操作

以下內容參照電腦課程資料夾中三支同名影片的教學畫面；影片本身沒有上傳至公開 repository。

| 影片 | 教學位置（約） | 本次演練對應 |
| --- | --- | --- |
| Git概念介紹.mp4 | 00:00–06:00 | 版本控制目的、分散式版本庫、文字檔適合比較差異 |
| Git概念介紹.mp4 | 07:00–14:00 | 工作目錄、暫存區、本機與遠端 repository；add / commit / clone / pull / push |
| Git概念介紹.mp4 | 15:00–18:20 | 一次提交聚焦一個目的，撰寫能解釋變更原因的提交訊息 |
| gitLocalRepo演練.mp4 | 00:00–09:00 | 安裝 Git、設定 `lg` 別名，認識 init / add / commit / checkout / log / diff |
| gitLocalRepo演練.mp4 | 10:00–24:00 | 建立本機 repository、準備專案檔案與 `.gitignore`、加入暫存區 |
| gitLocalRepo演練.mp4 | 25:00–34:44 | 提交、修改後再次提交、檢視歷史與差異、切換歷史版本 |
| gitRemote演練.mp4 | 00:00–11:00 | 建立全新 public GitHub repository、HTTPS 連線與登入 |
| gitRemote演練.mp4 | 12:00–17:00 | clone、add / commit、pull、push |
| gitRemote演練.mp4 | 18:00–26:32 | 用第二份本機副本模擬另一工作端，修改後 push，原副本 pull，檢查同步結果 |

## 概念整理

- `git add` 把指定檔案目前的內容放入暫存區；`git commit` 將暫存內容建立成本機版本。
- `git diff` 比較工作目錄與暫存區；`git diff <舊版> <新版>` 比較兩個已提交版本。
- `git checkout <commit>` 可檢視歷史版本，此時可能處於 detached HEAD；完成檢視後回到 `main`。
- `git clone` 建立含歷史紀錄的本機副本；`git pull` 取得並整合遠端更新；`git push` 將本機提交送到遠端。
- `.gitignore` 排除虛擬環境、快取與環境設定。本作業需上傳截圖，因此沒有照抄影片中排除所有 PNG 的規則。
- 教材中的示範專案用來說明 Git。本次另建可執行的簡單 Python 專案，實際練習相同 Git 指令與版本變化。
- 兩份副本均由同一位使用者帳號操作，用來模擬多個工作目錄；沒有宣稱有另一位協作者參與。
