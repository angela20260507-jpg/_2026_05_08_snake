<div align="center">
<img width="1200" height="475" alt="Neon Snake 3D Banner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />

# 🐍 NEON.SNAKE 3D

**NEON.SNAKE 3D** 是一款基於現代 Web 技術開發的極簡霓虹風格、實時多人聯機貪吃蛇遊戲。  
玩家在一個無限延伸的 3D 空間中競爭，收集能量球（Orbs）以增長體型，並在排行榜上留下自己的名字。

[查看 AI Studio 應用](https://ai.studio/apps/523b3459-8057-494b-9a4b-110f9212cf00)

</div>

---

## ✨ 核心特性

- 🎮 **沉浸式 3D 視覺**：
    - 使用 **React Three Fiber (Three.js)** 構建。
    - 具備 **Bloom (霓虹發光)** 與動態陰影效果。
    - 優化的 **Instanced Mesh** 技術，支持大量物體流暢渲染。
- 🌐 **實時多人同步**：
    - 基於 **Socket.io** 實現穩定的伺服器權威架構。
    - 具備客戶端預測（Client-side Prediction）與平滑插值，確保流暢的移動體驗。
- 🏆 **動態排行榜**：
    - 即時更新的 Top 10 排行榜。
    - 多樣化的玩家顏色，易於辨識。
- 🎨 **現代化 UI**：
    - 使用 **Tailwind CSS** 與 **Framer Motion** 打造的懸浮式透明介面。
    - 響應式設計，適配不同螢幕尺寸。

## 🛠️ 技術棧

- **前端**: React 19, Three.js, React Three Fiber, Zustand, Framer Motion, Tailwind CSS
- **後端**: Node.js, Express, Socket.io
- **資料庫**: SQLite (用於持久化儲存，可選)
- **開發**: Vite, TypeScript, tsx

## 🚀 快速開始

### 環境需求
- **Node.js**: v18.0.0 以上

### 安裝步驟

1. **安裝依賴**
   ```bash
   npm install
   ```

2. **設置環境變量**
   複製 `.env.example` 並更名為 `.env`，填入必要參數：
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```

3. **啟動開發伺服器**
   ```bash
   npm run dev
   ```
   默認訪問地址：`http://localhost:3000`

## 🕹️ 遊戲控制

| 按鍵 | 動作 |
| :--- | :--- |
| **A / D** 或 **← / →** | 控制轉向 |
| **Space** / **W** / **↑** | 消耗能量加速 |
| **New Tab** | 在新窗口打開以測試多人聯機 |

## 🌟 未來規劃 (Roadmap)

- [ ] **AI 智慧對手**：集成 Google Gemini API 實現具有策略性的 AI 蛇。
- [ ] **多樣化地圖**：引入不同的 3D 場景與障礙物。
- [ ] **皮膚系統**：允許玩家自定義蛇的發光顏色與紋理。

---

<div align="center">
Made with ❤️ by Antigravity AI
</div>
