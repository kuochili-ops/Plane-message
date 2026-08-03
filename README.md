# 𓃥 白六廣宣飛機 (SkyBanner 3D)

這是一項基於 **Three.js** 開發的 3D 互動網頁應用程式。畫面呈現一架雙翼飛機拖曳著自訂文字與動態波浪特效的廣宣布條，並在背景中配有緩慢漂移的雲朵系統。

## 🌟 主要功能特色

* **即時 3D 渲染**：採用高效能的 WebGL (Three.js) 環境，流暢呈現 3D 模型與光影。
* **動態拖曳布條**：支援透過介面即時修改布條文字、字型、文字顏色與背景顏色，布條並具備擬真的 procedural wave（波浪飄動）特效。
* **自訂 Google 字型**：提供多種 Google 線上字型（如思源黑體等）供自由切換。
* **全機完美入鏡與視角控制**：預設視野完整涵蓋飛機與拖曳組合，並支援單指旋轉視角、雙指縮放與平移。
* **大氣雲朵背景**：場景中隨機生成偶爾經過的半透明雲朵，增添飛行臨場感。

## 🛠️ 技術架構

* **核心技術**：HTML5, CSS3, JavaScript (ES Modules)
* **3D 圖形庫**：Three.js (r160)
* **載入與控制**：GLTFLoader, OrbitControls
* **字型資源**：Google Fonts (Noto Sans TC, Roboto, Orbitron, Pacifico)

## 📜 3D 模型來源與版權 (Attribution)

* **Stylized WW1 Plane** (https://skfb.ly/6ZFnM) by AntijnvanderGun is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).

## 🚀 快速開始

1. 確保專案資料夾中包含 `index.html` 以及 3D 模型檔案 `stylized_ww1_plane.glb`。
2. 使用任何本地伺服器工具（例如 VS Code 的 Live Server 擴充功能）啟動專案，或部署至 Netlify 等雲端靜態託管平台。
3. 開啟網頁即可直接體驗互動與即時修改廣宣內容。
