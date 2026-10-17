# Sheryians Backend Engineering Notes Hub

An interactive, beautifully styled, comprehensive curriculum hub and collection of backend engineering handbook documents from **Sheryians Coding School**.

The root `index.html` acts as a master entry point and file handler leading into 13 chronological topic modules, complete with deep-linked section anchors, interactive playgrounds, dark/light themes, and full navigation chains.

---

## 📚 Chronological Curriculum Sequence

| # | Topic | Document | Highlights |
|---|---|---|---|
| **01** | **Git & GitHub** | [`git-github-notes.html`](git-github-notes.html) | Workflows, branching, merging, pull requests, rebase, merge conflicts, reflog & interactive dark theme |
| **02** | **HTTP, Servers, Ports & Express.js** | [`http-express-notes.html`](http-express-notes.html) | Client-server model, HTTP/HTTPS, ports, `listen()`, raw `http` vs Express, CRUD APIs, middleware, interactive request simulator |
| **03** | **REST API Architecture** | [`rest-api-notes.html`](rest-api-notes.html) | REST architectural style, HTTP methods, idempotence & safety, 1xx–5xx status codes filter table, 10 core interview Q&As |
| **04** | **Validation in Express** | [`express-validator-notes.html`](express-validator-notes.html) | Never trust `req.body`, validation vs verification, plain JS validation, `express-validator`, Zod 4 & Joi 18 |
| **05** | **Authentication 101** | [`authentication-notes.html`](authentication-notes.html) | Who sent this request? Authn vs Authz, JWT payload & signing, password hashing with bcrypt, register/login routes & auth middleware |
| **06** | **Access & Refresh Tokens** | [`access-refresh-tokens.html`](access-refresh-tokens.html) | Token storage attacks, XSS vs CSRF, token rotation & reuse detection, httpOnly cookies & closing security loopholes |
| **07** | **MongoDB Introduction** | [`mongodb-intro-notes.html`](mongodb-intro-notes.html) | Database fundamentals, MongoDB Atlas on AWS, Compass GUI, Mongoose ODM schemas/models & proper application flow |
| **08** | **MongoDB Indexing** | [`mongodb-indexing-notes.html`](mongodb-indexing-notes.html) | How databases find one row in a crore, B+ trees, 11 MongoDB index types with live animations, `explain()` & ESR rule |
| **09** | **MongoDB Aggregation Pipeline** | [`07-mongodb-aggregation-notes.html`](07-mongodb-aggregation-notes.html) | Complete multi-stage pipelines: `$match`, `$group`, `$project`, `$lookup`, `$unwind`, `$facet`, `$bucket`, accumulators & operators |
| **10** | **URL Shortener (SRS)** | [`url-shortener-srs.html`](url-shortener-srs.html) | Production Software Requirements Specification: 8 Functional Requirements, 6 NFRs, data models, API contracts & build order |
| **11** | **Real-Time with Socket.IO** | [`socket-io-notes.html`](socket-io-notes.html) | Why HTTP alone cannot build chat apps, WebSockets, custom events, rooms, broadcasting, middleware & multi-server Redis scaling |
| **12** | **Payment Gateway** | [`payment-gateway-notes.html`](payment-gateway-notes.html) | Who paid for what? Order creation, Razorpay checkout, HMAC-SHA256 signature verification, webhooks & error handling |
| **13** | **100 MERN Interview Questions** | [`mern-interview-questions.html`](mern-interview-questions.html) | 100 essential interview questions across MongoDB, Express, React, Node & System Design with expandable model answers & progress tracking |

---

## ✨ Features

- **Master File Handler (`index.html`)**: Interactive hub with search, phase filtering, chronological step bar, and 170+ curated direct-jump section chips.
- **Dark & Light Mode**: Built-in support for system theme preference (`prefers-color-scheme`), manual toggle persistence via `localStorage`, and FOUC prevention.
- **Interactive Widgets**: Live Express CRUD request tracer, status code category filters, and 100 expandable dropdown interview answers.
- **Bi-directional Navigation**: Every topic file includes a "← Back to Hub" pill in the sidebar, top breadcrumb bar with next/previous module links, and bottom module pager cards.
- **Zero External Server Dependencies**: Pure HTML5/CSS3/JavaScript — open `index.html` locally in any browser or host directly on GitHub Pages.

---

## 🚀 Getting Started

Simply open `index.html` in your favorite web browser:

```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Or deploy to **GitHub Pages** by setting the branch to `main` and root directory to `/` in your repository settings!
