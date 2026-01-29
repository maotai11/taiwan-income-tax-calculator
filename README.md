# 台灣綜合所得稅計算器 2025 - 離線版

## 使用方式

1. 解壓縮此 ZIP 檔案
2. 直接開啟 `index.html` 即可使用（不需要網路連線）

## 功能特色

✅ **完全離線運作** - 所有 JS/CSS 函式庫已內建
✅ **表格編輯** - Tabulator 動態新增扶養親屬、所得項目
✅ **圖表視覺化** - Chart.js 稅額構成圓餅圖 + 級距位置橫條圖
✅ **PDF 匯出** - html2canvas + jsPDF
✅ **資料備份** - JSON 匯出/匯入（含 CryptoJS 簽章驗證）
✅ **Excel 匯入/匯出** - XLSX.js 支援
✅ **股利二擇一** - 自動比較分離課稅 vs 合併計稅
✅ **最低稅負 (AMT)** - 自動檢查並計算

## 資料夾結構

```
taiwan-tax-calculator/
├── index.html           # 主程式（開啟此檔案）
├── libs/                # 所有函式庫（離線可用）
│   ├── tailwindcss-3.4.1.js
│   ├── tabulator_bootstrap5.min.css
│   ├── decimal.min.js
│   ├── dayjs.min.js
│   ├── tabulator.min.js
│   ├── chart.umd.js
│   ├── html2canvas.min.js
│   ├── jspdf.umd.min.js
│   ├── crypto-js.js
│   ├── purify.min.js
│   └── xlsx.full.min.js
└── README.md            # 本說明檔
```

## 系統需求

- 任何現代瀏覽器（Chrome、Firefox、Safari、Edge）
- 無需網路連線
- 無需安裝任何軟體

## 技術細節

- **計算引擎**: Decimal.js（高精度運算）
- **UI 框架**: Tailwind CSS
- **表格元件**: Tabulator 6.2.1
- **圖表引擎**: Chart.js 4.4.1
- **PDF 匯出**: html2canvas + jsPDF
- **Excel**: XLSX.js
- **加密**: CryptoJS

---

© 2025 台灣綜合所得稅計算器 | MIT License
