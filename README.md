# 🎮 獻祭之環｜Twine 劇情互動遊戲

一款以「命運」、「愛情」與「克蘇魯」為主題的分歧式互動小說遊戲，由 Twine 撰寫劇本架構，透過 GitHub Actions 全自動轉檔並部署於 GitHub Pages。

👉 **線上體驗網址**：  
https://min1917.github.io/sacrifice-ring-twine/

---

## ✨ 專案亮點

- 📘 使用 [Twine](https://twinery.org/) 撰寫 `.twee` 劇情腳本
- ⚙️ 透過 GitHub Actions 自動執行 [Tweego](https://www.motoslave.net/tweego/) 編譯
- 🚀 成功部署至 GitHub Pages，打造可公開瀏覽的互動遊戲網站
- 🧪 含 passage 測試、分支邏輯與結局條件設計

---

## 🛠 使用技術

| 類別       | 工具與格式           |
|------------|----------------------|
| 劇本格式   | `.twee`（Twine）     |
| 編譯工具   | Tweego 2.1.1         |
| 自動化     | GitHub Actions       |
| 部署       | GitHub Pages         |
| 分支       | `main` / `gh-pages` |

---

## 📂 專案目錄結構簡介
├── index.twee                 ← 主劇本（Twine 原始腳本）
├── docs/
│   └── index.html             ← 自動產出的 HTML 遊戲檔
├── .github/
│   └── workflows/
│       └── build.yml          ← GitHub Actions 自動轉檔設定
└── README.md                  ← 專案說明文件（本檔）


---

## 📌 延伸方向

- 未定


---

## 🧑‍💻 作者

MIN1917｜[GitHub 頁面](https://github.com/MIN1917)  
《獻祭之環》由個人劇本創作與自學自動化技術實作而成
