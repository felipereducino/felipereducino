<h1 align="center">
  Hi there, I'm Felipe Reducino
  <img src="https://em-content.zobj.net/thumbs/160/twitter/322/waving-hand_1f44b.png" width="40" />
</h1>

<p align="center">
  <em>Principal Front-End Software Engineer • React / Next.js • Design Systems • SDK • Microfrontends</em>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/felipe-reducino/" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:faugustoreducino@gmail.com" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://media.giphy.com/media/Ll22OhMLAlVDb8UQWe/giphy.gif" width="220" alt="Coding GIF"/>
</p>

---

## ✦ About Me

I build **high-performance frontend platforms** and product experiences with an eye for:
**architecture, UI consistency, DX, and scalable delivery**.

- ⚙️ **What I do:** React/Next.js applications, Design Systems, Microfrontends, and Auth flows
- 🧠 **I care about:** clean boundaries, predictable state, testing, accessibility, and maintainability
- 🧩 **I enjoy:** turning complex flows into simple UI + reliable abstractions
- 🚀 **Currently working on:** Multi-Zone navigation, shared layouts, session/auth orchestration, and platform UI components

---

## 🔥 Current Focus (deep work)

### 🧱 Design Systems & Platform UI
- Component libraries with **Radix UI**, **shadcn/ui**, **Tailwind**
- Tokens-first approach (themes, typography, spacing, colors)
- Storybook-driven development + reusable patterns across apps

### 🧠 Platform SDK (typed integration layer)
- Building a **TypeScript SDK** that standardizes how apps talk to services (client + server entrypoints)
- **Auth/session helpers** (token lifecycle, cookie strategy, refresh flows) shared across microfrontends
- **React Query hooks** and thin adapters to keep data fetching consistent (queries, mutations, optimistic updates)
- Centralized **error model** (typed errors, HTTP errors, safe serialization) for predictable UI handling
- Environment-aware configuration (local/dev/prod, Edge vs Node constraints when needed)

### 🌍 Microfrontends with Next.js
- **Next.js Multi-Zones** (rewrites + shared navigation strategies)
- Cross-app routing and “host vs remote” UX consistency
- Shared UI shell patterns (AppShell layout) and permission-driven navigation

### 🔐 Authentication (OAuth 2.0 + PKCE)
- OAuth 2.0 authorization code flow using **PKCE**
- Secure session + cookie strategies (domain scope, SameSite, HttpOnly)
- Handling callback flows, refresh, and protected navigation at scale

---

## 🧰 Tech Stack & Tools

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=000)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next-dot-js&logoColor=fff)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=fff)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=fff)
![Radix UI](https://img.shields.io/badge/Radix%20UI-161618?style=flat-square&logo=radix-ui&logoColor=fff)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=fff)

### State & Data
![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square&logo=reactquery&logoColor=fff)
![Zustand](https://img.shields.io/badge/Zustand-2D2D2D?style=flat-square&logo=react&logoColor=fff)

### Build, Monorepo & Tooling
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=fff)
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=flat-square&logo=pnpm&logoColor=fff)
![Storybook](https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=storybook&logoColor=fff)
![Biome](https://img.shields.io/badge/Biome-60A5FA?style=flat-square&logo=biome&logoColor=fff)

### Testing
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=fff)
![Testing Library](https://img.shields.io/badge/Testing%20Library-E33332?style=flat-square&logo=testinglibrary&logoColor=fff)
![Cypress](https://img.shields.io/badge/Cypress-17202C?style=flat-square&logo=cypress&logoColor=fff)

### DevOps / Cloud
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=fff)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=fff)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=fff)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=fff)

---

## 🧭 Architecture Notes (what I build a lot)

### Multi-Zones in practice
When multiple Next.js apps live under the same domain, I focus on:
- shared navigation behavior (even when each zone renders its own HTML)
- consistent app shell UX patterns (layout, sidebar, topbar)
- safe redirects + canonical sign-in/out paths across zones

### Microfrontend mindset
I like architectures where:
- each domain feature is independently deployable
- UI consistency is enforced by the Design System
- platform abstractions enable teams to ship without breaking other teams

### Auth flows with PKCE (mental model)
- generate verifier + challenge
- redirect to authorization endpoint
- exchange code → tokens securely
- persist session safely and gate navigation
- server side tokens

---

## 🧪 Engineering Principles

- ✅ **Clean Code**: names that explain intent, small units, minimal surprises  
- 🧩 **SOLID mindset**: modules with clear responsibilities and testable behavior  
- ⚡ **Performance first**: fast routes, cache-aware fetching, minimal hydration  
- ♿ **Accessibility**: keyboard-first UX, semantics, contrast, focus states  
- 🧯 **Operational maturity**: reliable logs, error boundaries, predictable failures

---

## 🤝 Let’s talk

If you’re building:
- a Design System that needs to scale,
- a microfrontend platform,
- or a Next.js architecture with real-world auth complexity…

I’ll love to exchange ideas.

<p align="center">
  <a href="https://www.linkedin.com/in/felipe-reducino/" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Message%20me%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

<p align="center">
  <sub>✨ Thanks for stopping by — keep building things that scale and feel great to use.</sub>
</p>
