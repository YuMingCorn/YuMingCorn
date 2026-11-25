<p align="center">
  <b>繁體中文</b> | <a href="https://github.com/YuMingCorn/YuMingCorn/blob/main/README.en.md">English</a>
</p>

<h1 align="center">Hi 👋, I'm Alan</h1>
<h3 align="center">A Software Engineer from Taiwan</h3>

## 關於我

我是來自台灣的軟體工程師，熱衷於深度學習與 AI，也喜歡從底層弄懂技術背後的原理。目前主要關注以下幾個方向：

- **電腦視覺與影像處理**：用 C 語言從零實作基本影像演算法，讓它們能在樹莓派這類資源有限的邊緣裝置上執行。目標是整理成一套好用的函式庫，讓開發者能直接編譯進自己的專案。
- **深度學習**：用 PyTorch 訓練並壓縮小型模型，也有用 TensorRT、ONNX、NCNN 將模型部署到邊緣裝置的經驗。
- **AI Agent**：實作工具呼叫、權限控制等功能，並串接本地端或雲端的大型語言模型。這個領域我仍在持續學習與精進。
- **個人工具與作品集**：開發自己日常真正會用到的小型網頁應用程式。

## AI Agent 使用經驗

| 工具 | 使用經驗 |
| :--- | :--- |
| <img src="assets/claude.svg" height="20" align="center" alt="Claude Code logo"> **Claude Code** | 日常開發的主力工具。我自己撰寫並維護 subagents 與 skills（見 [agent_setting](https://github.com/YuMingCorn/agent_setting)），依工作性質把任務分派給 Haiku、Sonnet、Opus 等不同模型；[llm-wiki](https://github.com/YuMingCorn/llm-wiki) 知識庫也是以它為核心運作。 |
| <img src="assets/antigravity.png" height="20" align="center" alt="Google Antigravity logo"> **Google Antigravity CLI** | 作為審閱與程式碼審查的輔助工具，也透過它運用 Google Colab 的 GPU 資源。 |

## 最近專案

| 專案 | 說明 | 技術 | 最後更新 |
| :--- | :--- | :--- | :---: |
| [agent_setting](https://github.com/YuMingCorn/agent_setting) | 我的 Claude Code 自訂 subagents 與 skills。同一份設定會自動產生 Codex 與 Gemini CLI 的版本，一行指令即可部署。 | PowerShell、Claude Code、Codex、Gemini CLI | 2026-11-25 |
| [llm-wiki](https://github.com/YuMingCorn/llm-wiki) | 由 LLM 維護的個人知識庫模板。放入論文與文章後，Claude Code 會將內容整理成互相連結、標註頁碼出處的 Markdown 頁面。 | Python、uv、Claude Code | 2026-11-22 |
| [corn_agent](https://github.com/YuMingCorn/corn_agent) | 循序漸進的 AI Agent 教學，從連接模型、工具呼叫，一路實作到權限控制。 | Python、uv、OpenAI 相容 API | 2026-11-22 |
| [torchnetaug](https://github.com/YuMingCorn/torchnetaug) | 以純 PyTorch 實作 Network Augmentation（NetAug），提升小型模型的準確率。訓練完成後只匯出小模型，推論成本完全不變。 | PyTorch、torch.fx | 2026-11-21 |
| [OpenCV_For_Edge_Device](https://github.com/YuMingCorn/OpenCV_For_Edge_Device) | 以 C11 從零實作基本影像處理演算法。全部採用整數定點運算，各平台的輸出逐 byte 一致，可編譯到樹莓派、Cortex-M 與 AVR。 | C11、CMake | 2026-11-14 |

## 技術筆記

我在 HackMD 上記錄並整理各類技術筆記，歡迎參考：[hackmd.io/@YuMingCorn](https://hackmd.io/@YuMingCorn)

## 聯絡方式

- GitHub：[YuMingCorn](https://github.com/YuMingCorn)
- Email：[yumingchang9527@gmail.com](mailto:yumingchang9527@gmail.com)

<!---
YuMingCorn/YuMingCorn is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
