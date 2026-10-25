# NCU ME IoT Lab Thesis Skills

國立中央大學機械工程學系物聯網製造實驗室的碩士論文輔助 skills，適用於軟體系統研究與時間有限的在職班學生。

**目前版本：v1.0.0（版本 1，2026-10-25）**。主入口為 [main_skill.md](main_skill.md)，版本號見 [VERSION](VERSION)。

## 開始使用

1. 下載或複製完整儲存庫，保留子資料夾與相對路徑。
2. 準備學生自己的論文工作資料夾，放入已有稿件、圖表、資料或筆記；尚無稿件也可開始。
3. 將下列指令提供給能讀取檔案的 AI 助手，將方括號替換為實際路徑。

```text
請讀取 [本套件路徑]/main_skill.md，依其規則協助完成碩士論文。
學生工作資料夾是 [論文資料夾路徑]，今天可用 60 分鐘。
請先讀取已有檔案與紀錄，提供適合目前進度的工作選項。
```

啟動時會依工作資料夾、任務看板、待修 checklist 與修改紀錄提供少量選項，固定保留「我目前想先做別的」，讓學生自由輸入本次需求。AI 會選擇所需子 skill，學生不必逐一閱讀全部模組。

若使用環境無法讀取本機資料夾，先提供 `main_skill.md` 與 `shared_rules.md` 的內容，再按當前工作提供需要的子 skill 和研究素材。各子 skill 位於自己的 `SKILL.md`，主入口採用本套件指定的 `main_skill.md` 檔名。

## v1 功能

- 新手先看研究全貌；已有部分內容時先盤點完整度，再補強或接續。
- 一次推進一項 60–90 分鐘內的任務，計入確認與收尾；短時間也可完成同一任務的一小步。
- AI 整理資料、起草與維護紀錄，學生核對研究事實、證據與必要決策。
- 明確研究問題與假說；Related Work 比較研究差距與本文範疇；Discussion 引導形成有證據的 findings。
- 先準備並確認圖表，再撰寫對應內文。正式圖稿優先可編輯 PPTX，也可交付 SVG。
- 圖寬採 8 cm 或 14 cm；最終文字至少 8 pt，並檢查灰階辨識度。
- 採清楚表達原則，論文避免第一人稱、優先主動語態，維持完整學術段落。
- 預設以 Markdown 交付，超過 5,000 字時可依章節拆分並維持全篇連接。
- 待修清單另存，項目多時與學生討論優先次序；修改摘要經學生確認後提供教師。
- 保留致謝原文，另整理學生提供的簡短自傳與正式作者照片。

論文採適用的 IEEE 技術編輯與引用方式，封面、頁面與前後置內容依校方及系所範本設定。具體規則與來源見套件內文件。

## 套件導覽

| 位置 | 用途 |
|---|---|
| [main_skill.md](main_skill.md) | 啟動入口與子 skill 路由 |
| [shared_rules.md](shared_rules.md) | 寫作、互動、資料與交付共同規則 |
| [subskills/](subskills/) | 研究規劃、文獻、方法、實驗、寫作、檢查、修訂、組稿與口試 |
| [任務規劃](subskills/thesis-task-planning/SKILL.md) | 時間容量、既有成果盤點、任務看板與接續工作 |
| [修訂管理](subskills/revision-management/SKILL.md) | 教師意見、checklist、優先次序與修改摘要 |
| [學術圖製作](ieee-academic-figures/SKILL.md) | 可編輯圖稿、尺寸、字級及灰階檢查 |
| [來源紀錄](references/thesis-sources.md) | 官方規範與參考方法 |
| [在職班情境走查](references/part-time-student-walkthrough.md) | 維護者用情境推演與實際試用觀察方式 |

學生的任務看板、待修 checklist 與修改摘要由 AI 建立於學生工作資料夾，後續沿用原檔與編號。套件內的範本保留供重複使用。研究資料與學生稿件保存在各自的工作資料夾。

## 授權

沿用本儲存庫的 [MIT License](LICENSE)。官方規範與第三方參考來源的權利依各自來源說明。

## 原始專案介紹

簡介說明（中文）

本 repository 收錄一套結構化的論文寫作提示詞（prompts），用於協助研究生在進行學位論文或學術論文撰寫時，釐清研究方向、整理研究邏輯，並改善學術寫作表達。

本套提示詞由國立中央大學機械工程學系（臺灣）物聯網製造實驗室於研究與教學實務中發展與使用，主要作為研究生在進行論文撰寫時的輔助工具。

本 repository 的目的**並非取代研究思考、技術嚴謹性或學術貢獻本身**。
提示詞的角色在於協助學生：

* 更清楚地表達自己正在做的研究
* 釐清研究問題、現況限制與研究目標
* 以較有結構的方式進行學術寫作

特別是對理工科學生而言，即使研究內容本身具備技術深度，學術寫作往往仍是一項需要額外訓練的能力；本提示詞旨在於此處提供支持。

本 repository 特別強調以下原則：

* 研究的學術貢獻、正確性與技術合理性，必須由學生自行負責與確認
* 使用提示詞並不保證畢業、投稿成功或論文通過審查
* 學術價值最終仍取決於研究成果本身，而非提示詞的使用

在架構上，本 repository 依照研究與寫作的不同階段，提供對應的提示詞模組，包括：

* 研究初期的研究構想釐清與研究計畫書撰寫
* 論文初稿形成階段的引導與檢核
* 定稿前的大方向與研究核心門檻檢定
* 各論文章節（如 Introduction、Related Work、Methodology 等）的重點檢核提示

透過將寫作引導拆分為不同階段，本套提示詞的設計目標是在不犧牲學術誠信與研究自主性的前提下，加速寫作流程，並協助學生建立更清楚、可審視的研究論述。

---

This repository provides a collection of structured writing prompts designed to support graduate students in academic thesis and paper writing.

These prompts are developed and used within the Department of Mechanical Engineering, National Central University (Taiwan), specifically in the IoT Manufacturing Laboratory, as a writing support framework for students conducting research and preparing academic manuscripts.

The primary purpose of this repository is not to replace research thinking, technical rigor, or scholarly contribution. Instead, it serves as a guidance tool to help students clarify their research direction, articulate their ideas more clearly, and structure their writing more effectively—especially for engineering and STEM students who may struggle with academic writing despite having solid technical work.

The prompts emphasize that:

* Research contribution, correctness, and technical validity must always be verified and owned by the student.
* Writing prompts do not guarantee graduation, publication, or acceptance.
* Academic contribution ultimately depends on research outcomes, not on the use of prompts.

This repository is organized into multiple stages corresponding to different phases of research and writing, including:

* Early-stage research idea clarification and proposal development
* Thesis or paper draft development
* High-level structure and logic checks before detailed writing
* Final-stage direction validation before manuscript completion
* Chapter-specific guidance for common academic sections

By separating writing guidance into stages, the prompts aim to accelerate the writing process while preserving academic integrity, independent thinking, and responsibility for research quality.
