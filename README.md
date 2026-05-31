# 🏭 Manufacturing AI Copilot

> An AI-powered copilot that helps manufacturing companies automate workflows using intelligent agents.

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-green?logo=fastapi)](https://fastapi.tiangolo.com)
[![React](https://img.shields.io/badge/React-18+-61DAFB?logo=react)](https://react.dev)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15+-336791?logo=postgresql)](https://postgresql.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 🚀 Overview

Manufacturing AI Copilot is an intelligent platform designed to streamline and automate critical manufacturing workflows — from RFQ analysis and cost estimation to vendor selection and production planning — powered by state-of-the-art AI models.

---

## ✨ Features

| Feature | Description |
|---|---|
| 📋 **RFQ Analysis** | Automatically parse and analyze Request for Quotation documents |
| 💰 **Casting Cost Estimation** | AI-driven cost estimation for casting and manufacturing processes |
| 🛒 **Procurement Intelligence** | Smart procurement insights and spend analysis |
| 🗓️ **Production Planning** | Optimize production schedules with AI recommendations |
| 🏢 **Vendor Recommendation** | Intelligent vendor matching and scoring |
| 📊 **Quality Analytics** | Track and analyze quality metrics across production |
| 📄 **AI Document Processing** | Extract structured data from unstructured manufacturing documents |

---

## 🛠️ Technology Stack

### Backend
- **Python** — Core application logic
- **FastAPI** — High-performance REST API framework
- **PostgreSQL** — Relational database for structured data

### AI / ML
- **OpenAI** — LLM-powered reasoning and NLP
- **Claude API (Anthropic)** — Advanced document understanding and analysis

### Frontend
- **React** — Modern, responsive user interface

---

## 📁 Project Structure

```
manufacturing-ai-copilot/
├── backend/
│   ├── api/                  # FastAPI routes and endpoints
│   ├── agents/               # AI agent definitions
│   ├── services/             # Business logic
│   ├── models/               # Database models
│   └── main.py               # App entry point
├── frontend/
│   ├── src/
│   │   ├── components/       # Reusable UI components
│   │   ├── pages/            # Application pages
│   │   └── App.jsx
│   └── package.json
├── docs/                     # Documentation
├── .env.example              # Environment variable template
├── requirements.txt          # Python dependencies
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites

- Python 3.10+
- Node.js 18+
- PostgreSQL 15+
- OpenAI API Key
- Anthropic (Claude) API Key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/manufacturing-ai-copilot.git
   cd manufacturing-ai-copilot
   ```

2. **Set up the backend**
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate        # Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Configure environment variables**
   ```bash
   cp .env.example .env
   # Edit .env and add your API keys and DB credentials
   ```

4. **Run database migrations**
   ```bash
   alembic upgrade head
   ```

5. **Start the backend server**
   ```bash
   uvicorn main:app --reload
   ```

6. **Set up the frontend**
   ```bash
   cd ../frontend
   npm install
   npm run dev
   ```

7. **Open the app**
   Navigate to `http://localhost:5173`

---

## 🔑 Environment Variables

```env
# Database
DATABASE_URL=postgresql://user:password@localhost:5432/manufacturing_db

# AI Keys
OPENAI_API_KEY=your_openai_api_key
ANTHROPIC_API_KEY=your_anthropic_api_key

# App
SECRET_KEY=your_secret_key
DEBUG=True
```

---

## 🗺️ Roadmap

- [ ] Multi-tenant support
- [ ] ERP integrations (SAP, Oracle)
- [ ] Real-time production monitoring dashboard
- [ ] Mobile application
- [ ] Predictive maintenance module
- [ ] Supplier portal

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Arul Pandiyan Kamaraj**  
Founder — [TechMesh AI](https://techmesh.ai)

Arul is a technology entrepreneur building AI-powered solutions for the manufacturing industry. With a vision to modernize traditional manufacturing workflows through intelligent automation, he founded TechMesh AI to bridge the gap between industrial operations and cutting-edge AI.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Arul%20Pandiyan%20Kamaraj-blue?logo=linkedin)](https://www.linkedin.com/in/arul-pandiyan-kamaraj-16b1a340)
[![Email](https://img.shields.io/badge/Email-project%40techmesh.ai-red?logo=gmail)](mailto:project@techmesh.ai)
[![Phone](https://img.shields.io/badge/Mobile-%2B91%209742415432-green?logo=whatsapp)](https://wa.me/919742415432)

---

<p align="center">Built with ❤️ by TechMesh AI</p>
