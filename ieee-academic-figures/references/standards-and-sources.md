# 圖稿規範與參考來源

查核日期：2026-10-25。投稿前查閱指定期刊或會議的最新指南。

## 教師指定設定

- 雙欄的一欄圖：8 cm。
- 雙欄的跨欄圖：14 cm。
- 單欄版面圖：14 cm。
- 最終尺寸的所有文字至少 8 pt，預設採 9–10 pt。
- 灰階印刷清楚可辨。
- 可編輯 PPTX 優先，可編輯 SVG 亦可。

這些尺寸與下限來自本任務的教師要求。保留論文版；投稿格式不同時另產生投稿版。

## IEEE 官方指南

### 尺寸與解析度

來源：[Resolution and Size](https://journals.ieeeauthorcenter.ieee.org/create-your-ieee-journal-article/create-graphics-for-your-article/resolution-and-size/)。

官方通用指南列出一欄寬 88.9 mm、兩欄寬約 182 mm，與本論文的 80／140 mm 不同。指南建議向量輸出；點陣彩色或灰階圖大於 300 dpi，黑白線稿大於 600 dpi，且事後增加解析度不能提高原始品質。

本 skill 的 400／800 dpi 是製作設定。有效解析度仍依原始像素與最終放置尺寸核對。

### 格式、字型與字級

來源：[File Formatting](https://journals.ieeeauthorcenter.ieee.org/create-your-ieee-journal-article/create-graphics-for-your-article/file-formatting/)。

指南列出 PS、EPS、PDF、PNG、TIFF，並說明原生於 Office 的圖可使用 Office 文件。投稿系統對 PPTX 的實際接受情況需另核對；本 skill 將 PPTX 作為編輯主檔，另備 PDF。SVG 為編輯來源，轉成接受的格式提交。

指南列出 Helvetica、Times New Roman、Arial、Cambria、Symbol，並要求 PDF 等輸出嵌入字型或轉外框。最終呈現字級建議約 9–10 pt。本 skill 以此為預設，另遵守教師要求的 8 pt 下限。編輯主檔保留文字，外框版本另存。

### 灰階辨識

來源：[Create Graphics for Your Article](https://journals.ieeeauthorcenter.ieee.org/create-your-ieee-journal-article/create-graphics-for-your-article/)。

官方建議以灰階列印檢查圖形，結合線型、填紋、資料點符號與標籤傳達差異。本 skill 將此納入必要檢查，並要求保留灰階校樣。

## GitHub 社群 Skills

以下來源以查核當日的 `main` 分支為準。本 skill 以自行撰寫的指令整合工作方法，未匯入第三方程式或素材。

| 來源 | 採用內容 | 本 skill 的調整 |
|---|---|---|
| [K-Dense-AI / scientific-visualization](https://github.com/K-Dense-AI/scientific-agent-skills/blob/main/skills/scientific-visualization/SKILL.md) | 依最終尺寸設計、使用重複辨識線索、檢查匯出檔及自動裁切對尺寸的影響。 | 依教師指定的 8／14 cm 設計，加入 PPTX 原生物件與可編輯 SVG 要求。 |
| [SciDER / scientific-visualization](https://github.com/leonardodalinky/SciDER/blob/main/.scider/skills/scientific-visualization/SKILL.md) | 依圖形元素設定字級，分別檢查刻度、圖例、註記與子圖，並保留向量輸出。 | 所有文字至少 8 pt，預設 9–10 pt；以實際灰階校樣驗證配色。 |

社群內容作為流程參考。出版規範以官方指南確認。若後續直接採用原文、程式或素材，記錄版本並保留其授權要求的聲明。
