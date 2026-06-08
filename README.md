insightoh_web
The official web platform for InsightOh — a company that delivers modern web applications and digital products.

This is a pre-release version. Intended for internal development and not the final production release.

Project Overview
insightoh_web is the primary web platform of InsightOh, built as a fullstack application using Vanilla HTML/CSS/JS on the frontend and Node.js / FastAPI on the backend.
Core principles:

Clear separation of concerns between frontend and backend
Predictable file locations for all team members
Frontend and backend are fully decoupled — communication happens only via HTTP APIs
No backend logic, secrets, or business rules live in the frontend
Scalable structure that can migrate to React or other frameworks later without rewrites


Tech Stack
LayerTechnologyFrontendVanilla HTML, CSS, JavaScriptBackendNode.js / FastAPI (Python)StylingCustom CSS + BootstrapDatabase(update as needed)Auth(update as needed)HostingCDN / Static Hosting / Backend Static Server

Project Structure
insightoh_web/
├── frontend/
│   ├── index.html
│   ├── pages/
│   │   ├── login.html
│   │   ├── dashboard.html
│   │   └── profile.html
│   ├── assets/
│   │   ├── css/
│   │   │   ├── bootstrap.min.css
│   │   │   ├── base.css
│   │   │   ├── layout.css
│   │   │   ├── components.css
│   │   │   ├── utilities.css
│   │   │   └── pages/
│   │   │       ├── login.css
│   │   │       └── dashboard.css
│   │   ├── js/
│   │   │   ├── core/
│   │   │   │   ├── api.js
│   │   │   │   ├── auth.js
│   │   │   │   └── router.js
│   │   │   ├── pages/
│   │   │   │   ├── login.js
│   │   │   │   ├── dashboard.js
│   │   │   │   └── profile.js
│   │   │   └── utils/
│   │   │       ├── dom.js
│   │   │       └── storage.js
│   │   ├── img/
│   │   └── fonts/
│   └── vendor/
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   └── middleware/
├── .env.example
├── .gitignore
└── README.md
