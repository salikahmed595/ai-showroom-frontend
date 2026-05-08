<!-- SEO Keywords: AI Showroom Frontend | AI Product Marketplace | AI Tools Catalog | HTML CSS JavaScript Frontend | Vercel Deployment | AI Web App | Salik Ahmed | AI Engineer | Artificial Intelligence Products | Browse AI Tools | Open Source AI Frontend -->

<div align="center">

# 🖥️ AI Showroom — Frontend

### A Premium AI Product Marketplace & Discovery Platform

<p>
  <strong>Browse, discover and interact with cutting-edge AI tools & products — all in one beautifully designed platform.</strong>
</p>

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Visit_Site-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://ai-showroom-frontend.vercel.app)
[![GitHub Stars](https://img.shields.io/github/stars/salikahmed595/ai-showroom-frontend?style=for-the-badge&logo=github&color=6C47FF)](https://github.com/salikahmed595/ai-showroom-frontend)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

</div>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Live Demo](#-live-demo)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Deployment](#-deployment)
- [Related Projects](#-related-projects)
- [Author](#-author)

---

## 🌟 Overview

The **AI Showroom Frontend** is a sleek, production-ready web interface that serves as the public-facing portal for the AI Showroom platform. It connects to the [AI Showroom Backend](https://github.com/salikahmed595/ai-showroom-backend) API to deliver a real-time, interactive catalog of AI products, automation tools, and AI agents.

**Who is this for?**
- 🏢 Businesses looking to discover and integrate AI tools
- 👩‍💻 Developers exploring AI product ecosystems
- 🚀 Startups building on top of existing AI platforms
- 💼 Investors researching the AI product landscape

> Built by **Salik Ahmed** — AI Engineer & Automation Architect. See more at [github.com/salikahmed595](https://github.com/salikahmed595)

---

## 🔗 Live Demo

> **🌐 [https://ai-showroom-frontend.vercel.app](https://ai-showroom-frontend.vercel.app)**

Deployed on **Vercel** with automatic CI/CD — every push to `main` triggers a production deployment.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎨 **Premium UI/UX** | Clean, modern design with smooth animations and micro-interactions |
| 📱 **Fully Responsive** | Pixel-perfect across mobile, tablet, and desktop |
| ⚡ **Lightning Fast** | Vanilla HTML/CSS/JS — zero framework overhead, max performance |
| 🔌 **API-Connected** | Real-time data from the AI Showroom Backend REST API |
| 🛍️ **AI Product Catalog** | Browse and filter AI tools by category, stack, and use case |
| 🎭 **Interactive Demos** | Embedded live demos for featured AI products |
| 🔍 **Search & Filter** | Powerful search across all AI products and categories |
| 🌐 **Global CDN** | Delivered via Vercel's edge network for sub-50ms load times |
| 🔒 **Secure** | HTTPS enforced, no sensitive data on client side |

---

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|------------|---------|---------|
| **HTML5** | Latest | Semantic structure & accessibility |
| **CSS3** | Latest | Styling, animations, responsive grid |
| **JavaScript** | ES6+ | Dynamic behavior, async API calls |
| **Vercel** | Latest | Hosting, CDN, CI/CD |
| **REST API** | — | Backend data communication |
| **Fetch API** | — | HTTP requests to backend |

---

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- [VS Code](https://code.visualstudio.com/) + [Live Server Extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) (recommended)
- Backend running: [ai-showroom-backend](https://github.com/salikahmed595/ai-showroom-backend)

### 1. Clone the Repository

```bash
git clone https://github.com/salikahmed595/ai-showroom-frontend.git
cd ai-showroom-frontend
```

### 2. Configure the API

Open your main JavaScript file and set the backend URL:

```javascript
// config.js
const CONFIG = {
  API_BASE_URL: 'https://your-backend-url.com/api',
  // or for local development:
  // API_BASE_URL: 'http://localhost:8000/api'
};
```

### 3. Run Locally

**Option A — VS Code Live Server:**
1. Open the project in VS Code
2. Right-click `index.html` → "Open with Live Server"
3. App opens at `http://localhost:5500`

**Option B — Python Simple Server:**
```bash
python -m http.server 8080
# Open: http://localhost:8080
```

**Option C — Node.js http-server:**
```bash
npx http-server . -p 8080
# Open: http://localhost:8080
```

---

## 📁 Project Structure

```
ai-showroom-frontend/
│
├── 📄 index.html              # Main entry point — home page
│
├── 📁 assets/
│   ├── 📁 css/
│   │   ├── style.css          # Main stylesheet
│   │   ├── animations.css     # CSS animations & transitions
│   │   └── responsive.css     # Mobile-first responsive styles
│   │
│   ├── 📁 js/
│   │   ├── main.js            # Core application logic
│   │   ├── api.js             # API communication layer
│   │   ├── products.js        # Product catalog logic
│   │   └── config.js          # Environment configuration
│   │
│   └── 📁 images/
│       ├── icons/             # UI icons & SVGs
│       └── products/          # AI product images
│
└── 📄 README.md               # This file
```

---

## 🚢 Deployment

### Deploy to Vercel (Recommended)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/salikahmed595/ai-showroom-frontend)

**Manual Vercel Deploy:**
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel --prod
```

### CI/CD Pipeline
Every push to `main` branch automatically:
1. ✅ Triggers Vercel build
2. ✅ Runs build checks
3. ✅ Deploys to production CDN
4. ✅ Generates shareable preview URL for PRs

---

## 🔗 Related Projects

| Repository | Description | Stack |
|------------|-------------|-------|
| ⚙️ [ai-showroom-backend](https://github.com/salikahmed595/ai-showroom-backend) | FastAPI backend powering this frontend | Python · FastAPI · Docker |
| 📞 [ai-calling-agent](https://github.com/salikahmed595/ai-calling-agent) | AI voice calling & lead qualification | Node.js · Vapi · Supabase |
| 🏠 [real-estate-leads-n8n](https://github.com/salikahmed595/real-estate-leads-n8n) | Automated real estate lead pipeline | n8n · Google Sheets · Vapi |
| 🎓 [AI-Basics](https://github.com/salikahmed595/AI-Basics) | Beginner AI/ML learning projects | Python · Machine Learning |

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. **Fork** the repository
2. **Clone** your fork: `git clone https://github.com/YOUR_USERNAME/ai-showroom-frontend.git`
3. **Create** a feature branch: `git checkout -b feature/amazing-feature`
4. **Commit** changes: `git commit -m 'feat: add amazing feature'`
5. **Push** to branch: `git push origin feature/amazing-feature`
6. **Open** a Pull Request

**Commit Convention:** We use [Conventional Commits](https://www.conventionalcommits.org/)
- `feat:` New features
- `fix:` Bug fixes
- `docs:` Documentation updates
- `style:` UI/styling changes

---

## 👤 Author & Contact

<div align="center">

**Salik Ahmed** — AI Engineer · Automation Architect · AI Product Builder

[![LinkedIn](https://img.shields.io/badge/LinkedIn-salikahmed110-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/salikahmed110)
[![Instagram](https://img.shields.io/badge/Instagram-@salikbuilds-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/salikbuilds/)
[![YouTube](https://img.shields.io/badge/YouTube-@salikahmed686-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@salikahmed686)
[![GitHub](https://img.shields.io/badge/GitHub-salikahmed595-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/salikahmed595)

</div>

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**⭐ Star this repo if you find it useful!**

*Part of the [AI Showroom](https://github.com/salikahmed595/ai-showroom-frontend) ecosystem by [Salik Ahmed](https://github.com/salikahmed595)*

*Keywords: AI frontend, AI marketplace, AI product catalog, Vercel deployment, HTML CSS JavaScript, open source AI, AI tools discovery, artificial intelligence products*

</div>
