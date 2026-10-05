# AI Weather Assistant｜AI 氣象助理

AI 氣象助理是一個整合即時氣象資料與生成式 AI 的互動式 Web 應用程式。

系統透過中央氣象署（CWA）Open Data API 取得全台各縣市天氣資料，
經 Python 進行資料整理後，以 Streamlit 建立互動式查詢介面，
並串接 Gemini LLM，將結構化的氣象資訊轉換為自然、易讀的天氣摘要。

## Project Motivation｜專案目的

一般氣象 API 回傳的資料多以 JSON 等結構化格式呈現，
雖然適合系統進行資料交換，卻不一定能直接提供使用者友善的閱讀體驗。

因此，本專案以 API-first 的概念為核心，
嘗試整合「即時資料取得」與「生成式 AI 自然語言生成」，
建立從資料來源、資料處理到資訊呈現的完整應用流程。

透過中央氣象署 API 取得即時氣象資訊，
再將指定城市的最高溫、最低溫與天氣狀況提供給 Gemini LLM，
自動生成較自然且容易理解的氣象摘要，
讓原始氣象資料轉化為更貼近使用者閱讀習慣的資訊。

## Core Features｜核心功能

- 🌤️ 串接中央氣象署 Open Data API
- 🏙️ 查詢全台各縣市天氣資訊
- 🌡️ 顯示最高溫、最低溫與天氣狀況
- 🤖 Gemini LLM 自動生成氣象摘要
- 🔄 JSON 氣象資料解析與整理
- 🖥️ Streamlit 互動式 Web 介面
- ☁️ Streamlit Cloud 雲端部署

## System Flow｜系統流程

CWA Weather API
        ↓
Python Data Processing
        ↓
Weather Information
        ↓
Gemini LLM
        ↓
Natural Language Summary
        ↓
Streamlit Web App

## Tech Stack｜使用技術

**Programming**
- Python
- Pandas

**API & AI**
- CWA Open Data API
- Gemini API / LLM
- REST API
- JSON

**Web Application**
- Streamlit

**Deployment**
- GitHub
- Streamlit Cloud

## Project Goal｜專案目標

本專案希望透過 API 與生成式 AI 的整合，
將即時氣象資料從「資料取得」進一步延伸至「資訊理解」。

藉由 Python 處理 API 回傳的結構化資料，
再結合 Gemini LLM 的自然語言生成能力，
建立一個具備即時資料查詢、AI 摘要與互動式介面的氣象應用，
實作完整的 API-first 應用流程。
