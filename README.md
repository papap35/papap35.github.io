# papap35.github.io

Shane Chen 的個人主頁，透過 [GitHub Pages](https://pages.github.com/) 部署於 [papap35.github.io](https://papap35.github.io)。

單頁自我介紹 + 專案入口，收錄近期用 AI 協作打造的小工具，方便大家直接連到各專案的原始碼。

## Projects

Stack 欄位分三類標示：**Framework**（框架）、**Lang**（語言）、**AI**（是否有 AI 功能）。判斷依據是直接讀每個 repo 的 README「技術架構 / Tech Stack」段落與 About 欄位的 Website 連結，不是憑 repo 列表顯示的 GitHub 偵測語言去猜的。

| Project | Description | Framework | Lang | AI | Demo |
| --- | --- | --- | --- | --- | --- |
| [ilovechiikawa](https://github.com/papap35/ilovechiikawa) | Chiikawa 絨毛玩偶收藏管理工具，拍照即可用 AI 辨識角色、通路、尺寸與新舊狀況，標示可能仿品疑點並估算參考市值 | Next.js | TypeScript | ✅ | [Demo](https://ilovechiikawa.vercel.app) |
| [愛棒球](https://github.com/papap35/ilovebaseball) | CPBL 數據站，提供戰績戰況、進階數據視覺化、AI 賽前分析與個人化追蹤 | Next.js | TypeScript | ✅ | [Demo](https://ilovebaseball.vercel.app) |
| [台灣事件風險地圖](https://github.com/papap35/taiwan-rip) | 視覺化台灣意外與社會事件的風險地圖，支援時間軸回放、K-means 風險分級與周邊宮廟查詢 | Next.js | TypeScript | – | [Demo](https://taiwan-rip.vercel.app) |
| [ilovehouse](https://github.com/papap35/ilovehouse) | 實價登錄查詢 + AI 選屋規劃網站，整合內政部實價登錄資料，依預算、通勤與生活圈比較區域 | Next.js | TypeScript | ✅ | [Demo](https://ilovehouse.vercel.app) |
| [Paddock 64](https://github.com/papap35/diecast-platform) | 1:64 模型車限量預購與收藏平台作品集專案，含商城前台、後台管理與 REST API | Next.js, NestJS | TypeScript | – | 尚未部署 |
| [ilovetomica](https://github.com/papap35/ilovetomica) | 1/64 合金車收藏管理工具，AI 拍照鑑定、行情估值與跨品牌比較，支援 16 個品牌 | Next.js | TypeScript | ✅ | [Demo](https://ilovetomica.vercel.app) |
| [Taiwan Pulse](https://github.com/papap35/taiwan-pulse) | 整合台灣多項政府開放資料的即時監控儀表板，涵蓋地震、天氣、空品、路況、淹水、火災等九大類警示，並附電力供需看板 | Next.js | TypeScript | – | [Demo](https://taiwan-pulse-xi.vercel.app) |
| [PDOS](https://github.com/papap35/pdos) | 個人決策作業系統，整合目標管理、事件記憶與決策分析的私人儀表板，純瀏覽器端運作，資料只存在 localStorage | – (Vanilla) | JavaScript | ✅（選配） | 尚未部署 |
| [Aetheria](https://github.com/papap35/aetheria) | 原創奇幻世界觀的互動百科網站，收錄五大生態域、種族、人物譜系與歷史事件，支援搜尋與跨頁連結導覽 | – | HTML | – | [Demo](https://papap35.github.io/aetheria/) |
| [Image Search Tool](https://github.com/papap35/image-search-tool) | 用 Playwright 打造的圖庫網站爬蟲，可依關鍵字／標籤篩選相簿並批次下載圖片，支援分頁與去重 | – | Python | – | 本機工具 |
| [Many Money](https://github.com/papap35/many-money) | AI 輔助記帳軟體，結合完整記帳功能與 AI 財務分析，幫助使用者開源節流 | Next.js | TypeScript | ✅ | [Demo](https://many-money.vercel.app) |
| [Taiwan Stock Monitor](https://github.com/papap35/taiwan-stock-monitor) | 台股個人投資儀表板，提供即時監控、技術分析、籌碼追蹤與 AI 盤勢簡報 | React | JavaScript | ✅ | [Demo](https://taiwan-stock-monitor-murex.vercel.app) |
| [Image Magic](https://github.com/papap35/image-magic) | 透過提示詞與動態表單產生 AI 圖片，支援標籤、AI 辨識與語意搜尋的圖庫管理 | Next.js | TypeScript | ✅ | [Demo](https://image-magic-rosy.vercel.app) |
| [Paper Sudoku Helper](https://github.com/papap35/paper-sudoku-helper) | 拍照辨識紙本數獨盤面，自動計算候選數字、檢查錯誤並提供分級提示 | React | TypeScript | ✅ | [Demo](https://paper-sudoku-helper.vercel.app) |
| [Daily Planner](https://github.com/papap35/daily-planner) | 每天自動整理 Slack 與 Jira 資訊，透過 Claude AI 產生可執行的每日工作計畫 | – | TypeScript | ✅ | CLI 工具 |
| [LINE AI Summary](https://github.com/papap35/line-ai-summary) | 整合 LINE 訊息平台與摘要功能的後端服務 | – | JavaScript | 未確認 | 無公開 Demo |
| [Car Configurator](https://github.com/papap35/car-configurator) | 互動式選配車型的前端小工具 | React (Vite) | – | – | 尚未部署 |

更多專案請見 [github.com/papap35](https://github.com/papap35?tab=repositories)。

## Development

純靜態網站，沒有建置流程。

```bash
open index.html
```

## Deployment

推送到 `main` 後由 GitHub Pages 自動 build 並部署。

## Archive

這個 repo 原本是拿來測試公司（17.live）App Links deeplink 的頁面，舊內容保留在 [`archive/company-deeplink-test`](https://github.com/papap35/papap35.github.io/tree/archive/company-deeplink-test) 分支。
