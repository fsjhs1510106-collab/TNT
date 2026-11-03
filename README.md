# TNT🍄 超級瑪利歐技能特訓學院 (Super Mario Practice & Learning Academy)
<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Canvas_API-000000?style=for-the-badge&logo=html5&logoColor=white" alt="Canvas API" />
  <img src="https://img.shields.io/badge/License-MIT-green.style=for-the-badge" alt="License" />
</p>
> 專為平台動作遊戲（Platformer）愛好者與新手打造的**一頁式遊戲化學習與練習平台**。結合視覺化跳躍軌跡、無敵練習模式、頂磚與變身機制，帶你從零克服挫折，直達酷霸王城堡通關！
---
📖 專案目錄 (Table of Contents)
💡 創作緣由與動機
🎮 遊戲平台介紹
✨ 核心特色與創新亮點
🗺️ 10 大主題特訓關卡
🛠️ 開發歷程 (Development Journey)
🕹️ 操作指南 (Controls)
🚀 快速開始 (Quick Start)
📄 開源授權 (License)
---
💡 創作緣由與動機
在許多經典的 2D 橫向捲軸遊戲（如《超級瑪利歐》系列）中，新手玩家常因為以下問題而感到挫折：
即死懲罰過重：一次判定失誤就要重新從頭開始，無法針對特定操作（如遠距疾跑躍下、高空頂磚）進行重複練習。
動作反饋不明顯：難以預判拋物線落點、跳躍加速度與頂磚 Hitbox 的精準時機。
設計動機：
本專案旨在建構一個低挫折、高回饋、可即時調控的「遊戲化特訓沙盒平台」。透過將複雜的動作拆解為 10 個漸進式關卡，搭配沙盒輔助工具（慢動作、軌跡線、無敵切換），幫助玩家建立肌肉記憶，達成「從破不了關到完美通關」的目標！
---
🎮 遊戲平台介紹
「超級瑪利歐技能特訓學院」是一個整合了一頁式展示網站（Landing Page）與實時 Canvas 2D 物理遊戲引擎的全功能平台。
實時物理引擎：採用自研 Canvas API 繪製，支援自訂重力、摩擦力、Collision 碰撞盒判定。
經典元素還原：包含問號磚塊（?）、超級蘑菇、火之花變身、無敵星星、Goomba 踩踏、烏龜殼踢飛與 Boss 酷霸王對決。
熟練度追蹤：內建 3 星通關評級、時間/金幣分數統計與成就徽章系統，讓進度一目了然。
---
✨ 核心特色與創新亮點
1. 🛠️ 沙盒特訓視覺輔助工具 (Sandbox Tools)
📐 跳躍拋物線實時軌跡：即時預測並繪製玩家起跳後的拋物線，提示降落點。
⏱️ 動作調速器 (0.5x ~ 1.5x)：可開啟慢動作模式，仔細觀察踩踏敵人與頂磚的微操細節。
🛡️ 鎖血無敵與低重力模式：提供無壓力練習環境，專注於路線記憶與操作熟悉。
2. 🍄 頂磚物理與道具變身系統
問號磚塊 (`?`)：從正下方撞擊可頂出金幣、超級蘑菇（身體變大增加血量）、火之花與無敵星星。
🔥 火焰瑪利歐 (Fire Mario)：吃下火之花後變身，按 `F` 鍵即可發射彈跳火球遠程消滅敵人。
Combo 踩踏翻倍加成：雙腳不落地的情況下連續踩踏敵人，可觸發 `2x, 4x, 8x` 分數倍數加成與音效！
3. 🎨 一頁式高質感網站與儀表板
採用 Tailwind CSS 與 Glassmorphism 微光澤暗色系視覺設計。
整合 Web Audio API 聲音合成器，無需外掛音效檔即可產生高品質 8-bit 復古遊戲音效。
---
🗺️ 10 大主題特訓關卡
關卡編號	關卡名稱	核心練習主題	3 星考核指標
01	基礎跳躍與問號方塊觸碰	頂撞問號磚 (`?`) 取得蘑菇補給	時間 < 25s / 金幣 ≥ 8
02	精準跳躍與浮動移動方塊	移動平台上預判起跳與頂磚	時間 < 30s / 金幣 ≥ 10
03	踩踏 Goomba 與踏高	Hitbox 踩踏與二段彈跳	時間 < 30s / 金幣 ≥ 12
04	踢飛烏龜殼與清道夫連擊	縮殼與踢飛烏龜 shell 連擊	時間 < 25s / 金幣 ≥ 10
05	Shift 疾跑衝刺與遠距飛躍	按住 Shift 累積慣性越過巨崖	時間 < 20s / 金幣 ≥ 10
06	超級蘑菇強化與容錯承受	變大狀態撞碎硬磚與承傷試驗	時間 < 30s / 金幣 ≥ 15
07	隱藏問號磚與高台探索	透明隱藏磚塊尋寶與躍台	時間 < 35s / 金幣 ≥ 15
08	致命岩漿海與地獄跳板	極限窄台落地與慢動作微操	時間 < 35s / 金幣 ≥ 10
09	無敵星星無雙衝刺	吃下無敵星星進行狂暴橫掃	時間 < 20s / 金幣 ≥ 20
10	終極城堡 Boss 酷霸王決戰	火球遠程攻擊與 Boss 三連踩踏	時間 < 45s / 金幣 ≥ 20
---
🛠️ 開發歷程 (Development Journey)
```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│  Phase 1: 原型  │ ──►│  Phase 2: 物理  │ ──►│  Phase 3: 道具  │ ──►│  Phase 4: 整合  │
│  基礎 Canvas 繪圖 │    │  碰撞與移動平台  │    │  問號磚/火球/Combo│    │ 一頁式展示/儀表板│
└─────────────────┘    └─────────────────┘    └─────────────────┘    └─────────────────┘
```
第一階段（原型建構）：建立 Canvas 繪圖架構，實作瑪利歐基礎重力、水平加速度與左右移動。
第二階段（物理優化）：加入多重平台判定、移動 platform 機制、地形危害（岩漿）與滾動鏡頭跟隨（Camera System）。
第三階段（機制擴充）：設計問號磚頂擊物理、掉落物彈出動畫、變身系統與遠程火球彈跳軌跡。
第四階段（網站整合）：運用 Tailwind CSS 打造一頁式 Landing Page，整合 Web Audio API 復古音效與 LocalStorage 進度儲存。
---
🕹️ 操作指南 (Controls)
動作	鍵盤按鍵 (Keyboard)	手機觸控按鈕
向左移動	<kbd>A</kbd> 或 <kbd>←</kbd>	◄ 按鈕
向右移動	<kbd>D</kbd> 或 <kbd>→</kbd>	► 按鈕
跳躍 (Jump)	<kbd>Space</kbd> / <kbd>W</kbd> / <kbd>↑</kbd>	JUMP 按鈕
疾跑衝刺 (Run)	按住 <kbd>Shift</kbd> 或 <kbd>Z</kbd>	RUN 按鈕
發射火球 (Fire)	<kbd>F</kbd> 鍵	FIRE 按鈕
快速重置關卡	<kbd>R</kbd> 鍵	⚡ 重置按鈕
---
🚀 快速開始 (Quick Start)
本專案完全基於前端技術打造，無需安裝任何複雜的後端環境或套件：
複製本儲存庫：
```bash
   git clone https://github.com/your-username/mario-learning-academy.git
   ```
開啟遊戲：
進入專案資料夾後，直接雙擊 `index.html` 檔案即可在任何瀏覽器（Chrome, Edge, Firefox, Safari）中開啟體驗！
---
📄 開源授權 (License)
本專案採用 MIT License 授權條款，歡迎自由修改、擴充與分享。
---
<p align="center">
  <b>🍄 祝您在超級瑪利歐特訓學院中順利破關！ 🍄</b>
</p>
