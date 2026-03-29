<div align="center">

```
██████╗  █████╗ ██╗      █████╗ ██╗   ██╗ █████╗ ███╗   ██╗████████╗██╗  ██╗
██╔══██╗██╔══██╗██║     ██╔══██╗██║   ██║██╔══██╗████╗  ██║╚══██╔══╝██║  ██║
██████╔╝███████║██║     ███████║██║   ██║███████║██╔██╗ ██║   ██║   ███████║
██╔══██╗██╔══██║██║     ██╔══██║╚██╗ ██╔╝██╔══██║██║╚██╗██║   ██║   ██╔══██║
██████╔╝██║  ██║███████╗██║  ██║ ╚████╔╝ ██║  ██║██║ ╚████║   ██║   ██║  ██║
╚═════╝ ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝  ╚═══╝  ╚═╝  ╚═╝╚═╝  ╚═══╝   ╚═╝  ╚═╝  ╚═╝
```

### AI Engineer · Full Stack Developer · Builder
**Bengaluru, India** · [balavanthko@gmail.com](mailto:balavanthko@gmail.com) · [LinkedIn](https://www.linkedin.com/in/balavanth/)

---

*I build AI-powered products from zero — RAG pipelines, voice agents, automation tools.*
*Currently at TCS. Available for AI Engineer / Full Stack roles.*

</div>

---

## ⚡ What I Actually Build

I don't do tutorial projects. Everything below is a real product with a real problem statement, real architecture decisions, and a deployed URL.

---

## 🚀 Featured Projects

### [VAULTIQ](https://github.com/balavanth/vaultiq) — AI Knowledge Base for Teams
> *"Stop answering the same questions. Let your docs answer them."*

Multi-tenant RAG system. Upload company docs (HR policies, SOPs, product specs). Employees ask in plain English, get answers with source citations in under 2 seconds. Built as a live product for a 52-person fictional SaaS company (Nexora Technologies) with full onboarding data, policies, and product docs ingested.

**What makes it non-trivial:**
- FAISS indexes per document → merged at query time for cross-doc retrieval
- MMR (Maximum Marginal Relevance) retrieval → zero duplicate chunks
- Multi-tenancy via Supabase Auth + org-level index isolation
- Custom prompt engineering → model cites sources, never hallucinates beyond context
- Role-based access: Admin (upload/manage) vs Employee (query only)

```
FastAPI · LangChain · FAISS · HuggingFace Embeddings · Groq (Llama 3) · Supabase · React · Docker
```

---

### [WAYWARD](https://github.com/balavanth/wayward-v1) — AI Quest Generator App
> *"Break your routine. The AI gives you a real-world mission."*

React Native + Expo mobile app that generates AI-powered real-world quests based on your location, mood, and time available. Built to solve decision fatigue for people stuck in routines. Groq (Llama 3) generates the quest logic. FastAPI backend. Supabase for user data and quest history.

```
React Native · Expo · FastAPI · Supabase · Groq · Python
```

---

### [KOBRA](https://github.com/balavanth) — Voice-Activated Personal AI Assistant
> *"Always listening. Always ready."*

Local voice agent running on Windows. Wake word detection via Porcupine, speech-to-text via faster-whisper (runs offline), LLM via Groq/Llama, text-to-speech via edge-tts. Zero cloud dependency for the core loop — under 800ms response latency end to end.

**Architecture that matters:**
- Porcupine wake word → no continuous cloud streaming
- faster-whisper local STT → privacy-first, no API costs
- Groq inference → sub-500ms LLM response
- edge-tts → natural voice output, offline capable

```
Python · Porcupine · faster-whisper · Groq · edge-tts · Windows
```

---

### [MARKETCREW](https://github.com/balavanth/MarketCrewe-v1) — AI Content & Ad Automation
> *"Brief in. Campaign out."*

Multi-agent AI system using CrewAI that takes a product brief and outputs ready-to-publish ad copy, social content, and marketing assets. Agents: Strategist, Copywriter, Ad Designer prompt generator. Outputs to Notion/Google Docs. SambaNova API (Llama 4 Maverick) as the LLM backbone. Supabase for auth and gating.

```
Python · CrewAI · SambaNova API · Supabase · TypeScript · Notion API
```

---

### [MYKATTU](https://github.com/balavanth/mykattu-v1) — Cinematic Gym Website
> *"A gym website that hits like a pre-workout."*

High-performance marketing site for a gym brand. Black and yellow palette, cinematic scroll animations, GSAP-powered transitions. Built to convert — not just look good.

```
React · TypeScript · Vite · Tailwind · Framer Motion · GSAP · ShadCN
```

---

## 🧠 Tech Stack

```python
ai_ml = [
    "LangChain", "FAISS", "ChromaDB", "RAG pipelines",
    "HuggingFace Transformers", "faster-whisper", "Groq API",
    "SambaNova API", "CrewAI", "Prompt Engineering",
    "LangGraph", "Ollama (local LLMs)"
]

backend = [
    "Python", "FastAPI", "Django", "Django REST Framework",
    "PostgreSQL", "Supabase", "REST APIs", "WebSockets"
]

frontend = [
    "React", "React Native", "Expo", "TypeScript",
    "Tailwind CSS", "Framer Motion", "GSAP", "Vite"
]

infrastructure = [
    "Docker", "Git", "Vercel", "Render", "Railway",
    "Supabase Storage", "Linux"
]
```

---

## 📊 GitHub Stats

<div align="center">

![Balavanth's GitHub Stats](https://github-readme-stats.vercel.app/api?username=balavanth&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6C63FF&icon_color=6C63FF&text_color=c9d1d9)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=balavanth&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6C63FF&text_color=c9d1d9&langs_count=8)

</div>

---

## 🗓️ Currently

```
├── Role       → Analyst @ TCS, Bengaluru
├── Building   → VAULTIQ (RAG SaaS) · WAYWARD (React Native AI app)
├── Learning   → LangGraph · Azure Cloud · Docker advanced patterns
├── Target     → AI Engineer / Full Stack roles — Bangalore or Remote
└── Open to    → Contract, full-time, and freelance AI builds
```

---

## 📬 Reach Me

If you're hiring for AI Engineer, Full Stack, or Generative AI roles — or building something and need a developer who ships:

**[balavanthko@gmail.com](mailto:balavanthko@gmail.com)** · **[LinkedIn](https://www.linkedin.com/in/balavanth/)**

---

<div align="center">

*Every repo here started with a problem worth solving.*

</div>
