# ⚡ VoltSaver AI

### AI-Powered Energy Saving Advisor for Indian Households

[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)](https://streamlit.io/)
[![Groq](https://img.shields.io/badge/Groq-FF6B00?style=for-the-badge&logo=groq&logoColor=white)](https://groq.com/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org/)

---

## 🎯 About

**VoltSaver AI** is an **Agentic AI** solution that helps Indian households save electricity and money. Built for **SDG 7: Affordable & Clean Energy**, it uses Groq's Llama 3 model to provide personalized energy-saving advice.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📊 **Energy Calculation** | Calculates monthly electricity consumption (kWh) |
| 💰 **Bill Estimation** | Shows monthly cost at ₹8/unit |
| 💡 **Smart Tips** | Gives 3 personalized energy-saving tips |
| 🌍 **Carbon Reduction** | Shows potential CO2 savings |
| 🎨 **Beautiful UI** | Professional, responsive Streamlit interface |

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| **Frontend** | Streamlit |
| **AI Model** | Groq (Llama 3.1-8B) |
| **Backend** | Python |
| **API** | Groq API |
| **Security** | python-dotenv |

---

## 🚀 Quick Start

### Prerequisites

- Python 3.8+
- Groq API Key (Free)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/VoltSaver_AI.git
cd VoltSaver_AI

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Set up environment variables
cp .env.example .env
# Edit .env and add your Groq API key

# 5. Run the application
streamlit run app.py