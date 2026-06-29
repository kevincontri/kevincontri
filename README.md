<div align="center">

# Hey there! I'm Kevin Contri 👋

### Fullstack Engineer in Training · Python · FastAPI · React · TypeScript

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kevin-contri)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kevincontri)
![Profile Views](https://komarev.com/ghpvc/?username=kevincontri&style=for-the-badge&color=58a6ff&label=PROFILE+VIEWS)

![Kevin's Github Stats Graph](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=kevincontri&theme=dark&hide_border=true)

</div>

---

## About Me

I'm a Brazilian fullstack developer focused on building clean, well-structured applications — FastAPI REST APIs on the backend, React + TypeScript on the frontend. I'm currently completing my degree in **Systems Analysis and Development (ADS)** and actively working toward my first developer role.

My work follows layered architectures (MVC/repository pattern), and I care a lot about writing readable, testable code with real-world tooling — Docker, PostgreSQL, Redis, JWT auth, and more.

I'm also exploring **AI integration** in real applications — semantic search, embeddings, and LLM answers grounded in user content via LangChain.

---

## Tech Stack

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-%236DB33F.svg?style=flat-square&logo=spring&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

**Frontend & Styling**

![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433E38?style=flat-square&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white)
![Radix UI](https://img.shields.io/badge/Radix%20UI-161618?style=flat-square&logo=radixui&logoColor=white)

**Databases & ORM**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-6BA539?style=flat-square&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Infrastructure & Tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Render](https://img.shields.io/badge/Render-000000?style=flat-square&logo=render&logoColor=white)
![Neon](https://img.shields.io/badge/Neon-00E599?style=flat-square&logo=postgresql&logoColor=white)

**Testing**

![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Testing Library](https://img.shields.io/badge/Testing%20Library-E33332?style=flat-square&logo=testinglibrary&logoColor=white)
![MSW](https://img.shields.io/badge/MSW-FF6A33?style=flat-square&logo=mockserviceworker&logoColor=white)

**Auth & Security**

![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![bcrypt](https://img.shields.io/badge/bcrypt-525252?style=flat-square&logoColor=white)

**AI / ML**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Embeddings](https://img.shields.io/badge/Embeddings-8B5CF6?style=flat-square&logoColor=white)

---

## Featured Projects

### 🗂️ [TaskFlow](https://github.com/kevincontri/task-flow) · [Live Demo ↗](https://task-flow-1-vuz1.onrender.com/login)

> A full-stack Kanban project management app — FastAPI backend, React + TypeScript frontend — with a fully optimistic UI over a distributed deployment.

- **Optimistic updates on every mutation** — creating, editing, moving, and deleting tasks, projects, and comments all update instantly and reconcile (or roll back) once the server responds, keeping the app snappy despite cross-provider latency
- **TanStack Query (React Query v5)** for all server state — typed `useQuery` / `useMutation`, stable query keys, cache invalidation, and smart temporary-card management (negative-id `_optimistic` placeholders swapped for real records)
- **Fully typed in TypeScript** — shared domain models (`TaskStatus`, `TaskPriority`, derived `Create`/`Update` types) catch mismatches at edit time
- **Redis caching layer** with async integration (`redis.asyncio`), custom `RedisRepository`, and `fakeredis` for isolated pytest fixtures
- **UI on shadcn/ui + Radix + Tailwind CSS v4**; drag-and-drop via `@dnd-kit`; EN/PT language toggle with locale auto-detection
- **Tested end-to-end** — pytest (async fixtures) on the backend; Vitest + Testing Library + MSW on the frontend
- **Distributed deployment** — frontend & backend on Render, managed PostgreSQL on Neon

`Python` `FastAPI` `SQLAlchemy (async)` `PostgreSQL` `Redis` `React 19` `TypeScript` `TanStack Query` `@dnd-kit` `Tailwind v4` `shadcn/ui` `Vitest` `Docker`

---

### 🧠 [Summari](https://github.com/kevincontri/AI-Knowledge-Base-API) · [Live Demo ↗](https://summari-ai-nzmf.onrender.com/login)

> A personal AI knowledge base — store, search, and query your notes, augmented with AI answers grounded in your own content. *(formerly AI Knowledge Base API)*

- **LangChain AI layer** — Groq `llama-3.1-8b-instant` for grounded QA (answers only from the user's notes) + Google Gemini embeddings + **FAISS** vector search, returning the most relevant related notes alongside each answer
- **Full React + TypeScript web app** — auth flow with protected routes, notes CRUD with a card grid and modal editor, instant client-side search, and an AI panel
- **React Query** for server state (cache cleared on logout to prevent cross-account leaks) + **Zustand** for client state (auth + theme)
- **Dark mode** with a persisted global theme; UI on Tailwind CSS v4 + shadcn/ui
- **Production-grade Docker** — multi-stage build, non-root container (`appuser`), health checks, and a persistent PostgreSQL volume
- Layered architecture (controllers / services / repositories), JWT auth, pytest coverage across all layers

`Python` `FastAPI` `SQLAlchemy (async)` `PostgreSQL` `LangChain` `Groq` `Gemini` `FAISS` `React 19` `TypeScript` `Zustand` `Docker`

---

### 📝 [Blog REST API](https://github.com/kevincontri/blog-rest-api)

> A full-featured blogging backend with users, posts, comments, and role-based access control.

- **JWT authentication** with bearer tokens and bcrypt password hashing
- **Role-based ownership** — only authors can edit or delete their own content
- Layered MVC architecture with dependency injection and SQLAlchemy ORM
- Dockerized with Docker Compose

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `Docker` `JWT`

---

### ✅ [React Todo List](https://github.com/kevincontri/react-todo-list)

> A practical task manager built with React 19 and Vite.

- Add, edit, complete, and remove tasks with a clean UI
- **localStorage persistence** — tasks survive page reloads
- Completion counter and congratulations message when all tasks are done
- Built with React hooks, CSS, and ESLint

`React` `Vite` `JavaScript` `CSS`

---

### 🏪 [Gerenciador de Lojas](https://github.com/kevincontri/gerenciador-de-lojas)

> Academic OOP project in Java — a shopping center store management system.

- **5 specialized store types**: Alimentação, Bijuteria, Cosméticos, Informática, Vestuário — each with unique attributes
- Product management with automatic expiry date validation
- Demonstrates inheritance, polymorphism, and class hierarchies in Java

`Java` `OOP`

---

### 💰 [Ledger REST API](https://github.com/kevincontri/ledger-rest-api)

> A financial transactions backend service built with FastAPI.

`Python` `FastAPI`

---

## Currently

- Finishing my **ADS degree** and building my portfolio
- Deepening knowledge in **DSA**, **System Design**, and **ML fundamentals**
- Improving my front-end skills

---

<div align="center">

*Let's connect — I'm open to opportunities and collaboration.*

[![LinkedIn](https://img.shields.io/badge/Reach%20me%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kevin-contri)

</div>
