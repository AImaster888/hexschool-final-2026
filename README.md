# 個人品牌網站 — Nelson

六角學院 2026 軟體工程師體驗營・最終任務作業。

## 作業資訊

- **挑戰等級**：LV2（完成設計稿兩頁的 RWD 響應式網頁）
- **製作頁面**：Index 首頁、Blog 部落格頁
- **技術**：HTML + CSS，搭配原生 JavaScript（手機版漢堡選單）與 [AOS.js](https://github.com/michalsnik/aos)（捲動進場動畫）
- **設計需求**：響應式（桌機 / 平板 / 手機），畫面無 x 軸（左右捲動）

## 頁面區塊（由上到下）

Header 導覽列 → Hero 主視覺 → Services 服務區（深色）→ Projects 專案區 → Blogs 部落格區 → Subscription 訂閱區 → Footer / Contact 頁尾

## RWD 斷點

| 裝置 | 寬度 | 主要調整 |
| --- | --- | --- |
| 手機 | `max-width: 767px` | 全區單欄、漢堡選單、圖片滿版 |
| 平板 | `768px ~ 1023px` | Services 2 欄、Hero 圖文比例調整 |
| 桌機 | `1024px 以上` | 完整多欄版面 |

## 檔案結構

```
.
├── index.html        # 首頁（Hero / Services / Projects / Blogs 預覽 / Subscription / Footer）
├── blog.html         # 部落格頁（橫幅 / 分類選單 / 文章列表 / 分頁）
├── css/
│   ├── reset.css     # 清除瀏覽器預設樣式
│   └── style.css     # 設計變數、版面、RWD
├── js/
│   └── main.js       # 漢堡選單開合
└── README.md
```

## 圖片來源

所有圖片皆使用六角學院提供的線上圖片空間：
`https://github.com/hexschool/2022-web-layout-training/tree/main/2026-web-camp`

## 參考來源

- **設計稿（Figma）**：六角學院 2026 軟體工程師體驗營設計稿（版面、尺寸、配色依此還原）
- **切版流程**：參考六角學院課程與公開的 Flex / RWD 切版教學示範
- **動畫**：[AOS.js](https://github.com/michalsnik/aos) 2.3.1（透過 CDN 引入，用於圖片與卡片的捲動進場效果）

## GitHub Pages

🔗 線上 Demo：<https://aimaster888.github.io/hexschool-final-2026/>
