# 總校長的 AI 教育寶典 · 課程摘要網頁

KIAO 出品「總校長的 AI 教育寶典」線上課程的精華摘要網頁集。

20 個學習法 + 3 個綜合主題,共 23 個獨立 HTML 頁面,完全離線可用。

## 結構

```
.
├── index.html                      # 首頁(課程總覽)
├── ch1-focus/                      # CH1 專注力 — 修好你的杯子
│   ├── index.html                  # 章節索引
│   ├── 01-focus-diagnosis.html
│   ├── 02-box-breathing.html
│   ├── 03-boredom-practice.html
│   ├── 04-exercise-prescription.html
│   └── environment-design.html
├── ch2-brain-care/                 # CH2 護腦 — 學會正確的倒水方式
│   ├── index.html
│   ├── 05-human-first.html
│   ├── 06-socratic-coach.html
│   └── 07-pme-coach.html
├── ch3-fast-learning/              # CH3 速學 — 鍛鍊你的肌肉
│   ├── index.html
│   ├── 08-disss-deconstruction.html
│   ├── 09-dual-coding.html
│   ├── 10-spaced-retrieval.html
│   ├── 11-deliberate-practice.html
│   ├── 12-feynman-technique.html
│   ├── 13-metacognition.html
│   └── 14-sleep-time-design.html
├── ch4-empowerment/                # CH4 賦能 — AI 煉金術 5 步
│   ├── index.html
│   ├── 15-ai-spectrum.html
│   ├── 16-learner-profile.html
│   ├── 17-anchor-knowledge.html
│   ├── 18-knowledge-base.html
│   ├── 19-practice-plan.html
│   └── 20-ai-toolmaking.html
└── ch5-beyond/                     # CH5 超越 — 打造 AI 無法取代的核心競爭力
    ├── index.html
    ├── epoch-framework.html
    ├── enduring-skills.html
    └── six-layer-pyramid.html
```

## 部署到 GitHub Pages

1. 在 GitHub 建一個新的 repo(例:`kiao-ai-learning-handbook`)
2. 把這個資料夾的內容全部 push 到 repo 的 `main` 分支
3. 進入 repo 的 **Settings → Pages**
4. **Source** 選 `Deploy from a branch`
5. **Branch** 選 `main`,Folder 選 `/ (root)`,然後 Save
6. 等 1–2 分鐘,網站就會出現在 `https://<你的帳號>.github.io/kiao-ai-learning-handbook/`

如果想用 `username.github.io` 這種更短的網址,把 repo 命名為 `<你的帳號>.github.io` 就行。

## 技術規格

- 純靜態 HTML/CSS,無 JavaScript 依賴(除少數內頁有原生互動)
- 字型:Google Fonts 的 Noto Sans TC + 系統字型 fallback
- 設計:紫藍漸層風格,響應式(手機/平板/桌面)
- 編碼:UTF-8,檔名全部使用英文以避免 URL 編碼問題

## 版權

© KIAO · 總校長的 AI 教育寶典
