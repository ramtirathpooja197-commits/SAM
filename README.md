# SAM - Smart Academic Manager
**Team Parvaah | iQOO 15 Hackathon | Phone-First Offline AI**

> One whiteboard photo → Working SQLite + FastAPI APIs + Docs & Sheets in 20 seconds - 100% OFFLINE on iQOO 15 NPU

![iQOO15](https://img.shields.io/badge/Device-iQOO%2015-blue)
![Offline](https://img.shields.io/badge/Mode-100%25%20Offline-green)
![NPU](https://img.shields.io/badge/NPU-Llama%203.2%203B%20Q4_K_M-orange)
![OCR](https://img.shields.io/badge/OCR-PaddleOCR-red)

### 🎯 Problem
Bharat ke labs, colleges, aur rural schools me teacher whiteboard pe table likhta hai. Usse manual SQL banana, API banana, Docs banana me 3-4 ghanta lagta hai. Internet weak hai, cloud pe data leak ka risk hai.

### 💡 Solution - SAM
SAM iQOO 15 ke NPU pe hi pura kaam kar deta hai - bina internet ke!
- **Zero Cloud Leak:** Data phone se bahar hi nahi jata
- **20s me Ready:** 3-4 ghante ka kaam 20 second me
- **Bharat ke liye:** Jahan internet nahi, wahan bhi chalta hai

### ⚙️ How It Works (3 Steps)
1.  **Photo Lo:** Whiteboard ki photo lo
2.  **PaddleOCR:** Handwritten tables ko text me convert
3.  **Llama 3.2 3B (Q4_K_M) on iQOO 15 NPU:** SQL Schema + FastAPI Code + Docs auto-generate

**Input:** Whiteboard Photo (.jpg)
**Output:** `database.db` (SQLite) + `main.py` (FastAPI) + `docs.md` + `sheet.csv`

### ✨ Features
- 100% Offline - No internet needed
- Handwritten Table Detection
- Auto SQLite + FastAPI + Docs Generation
- Runs on iQOO 15 NPU - Super Fast & Private

### 🛠️ Tech Stack
- **OCR:** PaddleOCR
- **LLM:** Llama 3.2 3B Q4_K_M (Quantized for NPU)
- **Backend:** FastAPI, SQLite, Python
- **Device:** iQOO 15 (NPU Optimized)

### 🚀 How to Run Prototype on iQOO 15
```bash
git clone https://github.com/ramtirathpooja197-commits/SAM.git
cd SAM
pip install -r requirements.txt
python main.py --image demo/input_whiteboard.jpg
