# 🧠 MediScan AI

AI-powered medical image analysis for early disease detection.

## 🚀 Features
- Upload medical images (X-rays, MRIs)
- AI predicts disease probabilities
- Explainable AI (Grad-CAM heatmaps)
- REST API (FastAPI) + web dashboard

## ⚙️ Setup

```bash
git clone https://github.com/yourusername/MediScan-AI.git
cd MediScan-AI
pip install -r requirements.txt
uvicorn app.main:app --reload
