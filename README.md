# TRIGGA.AI — Complete Website

## 📁 File Structure

```
trigga-ai/
├── index.html          ← Home Page
├── ai-agent.html       ← AI Agent Page
├── lead-generation.html ← Lead Generation Page
├── ai-automation.html  ← AI Automation Page
├── free-demo.html      ← Free Demo Booking Page
├── pricing.html        ← Pricing Page
├── contact.html        ← Contact Page
├── styles.css          ← Shared CSS (all pages use this)
├── server.js           ← Node.js Backend (Express)
├── package.json        ← Backend dependencies
└── data/               ← Auto-created by server
    ├── demos.json
    ├── contacts.json
    └── leads.json
```

## 🚀 Setup Instructions

### 1. Install Node.js
Download from: https://nodejs.org (LTS version)

### 2. Install Dependencies
```bash
npm install
```

### 3. Start the Server
```bash
npm start
```
OR for development (auto-restart):
```bash
npm run dev
```

### 4. Open in Browser
Go to: **http://localhost:3001**

---

## 🌐 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/health | Server health check |
| POST | /api/demo | Book a demo |
| POST | /api/contact | Contact form |
| POST | /api/lead | Capture a lead |
| GET | /api/admin/stats | Dashboard stats |
| GET | /api/admin/demos | All demo bookings |
| GET | /api/admin/contacts | All contact messages |
| GET | /api/admin/leads | All captured leads |

---

## 🎨 Theme Details

- **Background**: #06060e (very dark navy)
- **Accent**: #00aaff / #00e5ff (blue/cyan gradient)
- **Font**: Plus Jakarta Sans + Sora (Google Fonts)
- **Mobile Responsive**: Yes (768px breakpoint)

---

## 📄 Pages

| Page | File | Description |
|------|------|-------------|
| Home | index.html | Hero, Features, Pricing, FAQ, CTA |
| AI Agent | ai-agent.html | Live chat demo, use cases |
| Lead Generation | lead-generation.html | Funnel, channels, results |
| AI Automation | ai-automation.html | Workflow builder, integrations |
| Free Demo | free-demo.html | Demo booking form |
| Pricing | pricing.html | Plans, comparison table |
| Contact | contact.html | Contact form + info |

---

Made with ❤️ by NEXGEN · TRIGGA.AI © 2025
