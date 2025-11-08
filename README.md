# 🎣 HookBuster

> *HookBuster is a machine-learning phishing detector that analyzes URLs to spot malicious bait before it bites.*

---

### 🧠 Overview
HookBuster uses machine learning to classify URLs as **legitimate** or **phishing** based on their structure, keywords, and domain patterns.  
It extracts smart URL features — like length, special characters, and subdomain count — and feeds them into a trained model that flags sketchy links before you click.

---

### ⚙️ Features
- 🧩 Extracts key URL features (HTTPS usage, IPs, subdomains, etc.)
- 🤖 ML-based phishing prediction (Random Forest / Logistic Regression)
- 💻 Simple CLI interface and optional Flask web app
- 🧠 Easy to train on custom datasets
- ⚔️ Catch phish before they catch you!

---

### 🚀 Quick Start
```bash
git clone https://github.com/<your-username>/HookBuster.git
cd HookBuster
pip install -r requirements.txt
python src/train_model.py
python src/predict_url.py
