# 課表與行事曆 App

現代化的 Android 課表與行事曆應用程式，專為學生打造的智慧排程工具。

## 功能

- **課表管理** - 週視圖課表，支援時間衝突檢測、子任務管理
- **記帳功能** - 月曆式收支記錄，追蹤每日收入與支出
- **圖表資產** - 資產總覽、30天餘額走勢、支出/收入分類分析

## 技術棧

- React 19 + TypeScript
- Tailwind CSS 4
- Capacitor (Android)
- Framer Motion (動畫)
- IndexedDB (本地儲存)

## 本地開發

```bash
# 使用 SPA 伺服器啟動
npx serve -s web -l 3000
```

然後在瀏覽器開啟 `http://localhost:3000`

## 專案結構

```
web/                    # Web 前端資源
├── index.html          # 主頁面
├── assets/             # JS/CSS 資源
│   ├── index-*.js      # 主要應用程式邏輯
│   ├── index-*.css     # 樣式表
│   ├── Landing-*.js    # 著陸頁元件
│   └── enhancements.css # UI 增強樣式
├── cordova.js          # Cordova 橋接
└── cordova_plugins.js  # Cordova 插件
```
