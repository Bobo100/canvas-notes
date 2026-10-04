# Canvas-Dictionary

用 Next.js 寫的 HTML Canvas 教學筆記站，每個主題都附可互動的範例與可複製的程式碼。

## 狀態

2023 年的練習作品，已不再更新。原本部署在 Vercel 的版本已移除，目前沒有線上 demo,要看內容請在本機執行。

## 內容

| 章節 | 主題 |
|---|---|
| 01 基本繪圖功能 | 線、矩形、三角形、圓、弧線與填色 |
| 02 文字繪製 | `fillText` |
| 03 圖片繪製 | `drawImage` |
| 04 圖片繪製(進階) | 裁切、旋轉、縮放(以中心 / 滑鼠位置)、像素放大、把圖片拖進 Canvas |
| 05 動畫繪製 | `requestAnimationFrame` |
| 06 注意事項 | 常見陷阱(例如沒設定 Canvas 寬高會看不到畫面) |

相關的線上作品:

- [小小畫家](https://bobo100.github.io/canvas-paint/)
- [仿圖片增強](https://bobo100.github.io/canvas-image-enhance/)

## 本機執行

需要 Node.js 20.19 以上(Next.js 16 與 sass 的要求)。

```bash
npm install
npm run dev   # http://localhost:3000
npm run lint
```

技術:Next.js 16(Pages Router)、React 19、TypeScript、SCSS。
