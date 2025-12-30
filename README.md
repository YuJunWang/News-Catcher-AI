# 🌾 Catcher in NEWS 



> **"I keep standing on the edge of some crazy cliff... I have to catch everybody."**



### 🤖 AI-Driven Business Intelligence Automation System

*(AI 驅動商業情報自動化系統)*




[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://www.python.org/)

[![Gemini API](https://img.shields.io/badge/AI-Google%20Gemini-orange)](https://ai.google.dev/)

[![Status](https://img.shields.io/badge/Status-Complete-success)]()




## 📖 專案背景 (Project Overview)

在資訊爆炸的時代，決策者每天被無關的新聞淹沒。**Catcher in NEWS** 旨在解決此痛點。本專案利用 **Google Gemini 2.5** (現已可以更新至3.0)的語意理解能力，構建自動化新聞抓取與分析管線 (Data Pipeline)，協助使用者從繁瑣的資料篩選中解放。



## 🚀 核心成效 (Key Impact)

* **雜訊過濾率**：從 1,377 則原始資料中過濾掉 **86%** 的雜訊，僅保留 192 則高價值情報。

* **時間成本**：原本需耗時 **4 小時** 的人工閱讀，縮短至 **15 分鐘** 內完成。

* **語意辨識**：有效辨識語意歧義（例如：精準區分「蘋果公司」與「水果蘋果」的報導背景）。



## 🛠️ 技術亮點 (Technical Features)

* **多源爬蟲 (Robust Scraping)**：使用 Selenium 與 RSS Proxy 技術，克服動態加載與存取限制。

* **數據清洗 (Data Cleaning)**：自動將「2天前」等相對時間轉換為標準 ISO 日期格式。

* **LLM 整合 (Gemini API)**：設計高效 Prompt 指令集，進行多維度評分與自動摘要。



## 📂 專案結構 (Project Structure)
```text
News-Catcher-AI/
├── data/               # 數據樣本 (Sample Data)
├── docs/               # 技術報告與簡報 (PDF Presentation)
├── notebooks/          # 核心程式碼 (Main Pipeline)
├── .gitignore          # 忽略敏感設定 (Security)
└── README.md           # 專案說明文件
```


## 🛠️ 使用技術 (Tech Stack)

* **Programming**: Python 3.10+

* **AI/LLM**: Google Gemini API

* **Data Processing**: Pandas, Openpyxl

* **Crawling**: Selenium, BeautifulSoup4



## 👤 作者 (Author)

**王譽鈞 (YuJunWang)**

* Data Engineer / Data Scientist / AI-Augmented Developer 

* [GitHub Profile](https://github.com/YuJunWang)

