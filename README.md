## Hi, I'm Jheremyt Salazar

**Business Systems & AI Automation Specialist** · Lima, Peru (UTC-5) · open to remote work

I turn manual work into systems that run on their own: data pipelines, integrations and LLM agents, with the guardrails that make them safe to leave running (schema checks, approvals, retries and logs). 6+ years in data and operations (real-time analytics for ByteDance and Remitly operations, a PMO, a business I founded), now building AI automations at my own studio, Slead Studio.

### Selected projects

| Project | What it does | Numbers |
|---|---|---|
| **[Job-search operator](https://github.com/Jheremyt96/job-search-operator)** | Node.js + SQLite in Docker. Collectors run every 6 hours, an LLM scores each post, every model output is validated against a schema (retries, caching, monthly budget cap, dead-letter queue), deterministic guards block unsupported claims in generated CVs, and an IMAP checker classifies employer replies. Nothing is sent without approval. | Runs unattended |
| **[Automated short-video factory](https://github.com/Jheremyt96/podcast-shorts-factory)** | Full podcast episodes → vertical clips: Whisper transcription, LLM segment selection with fixed rules on top, captions that never cover faces, branding and scheduling. | 122 shorts produced, 48 published, ~US$0.04 of AI cost per short |
| **Video podcast editing workflow** | Redesigned a one-editor process into AI first pass → editor → quality control. | ~5 days → ~5 hours per episode |
| **Multi-tenant WhatsApp AI assistant** | Evolution API → intent classification → DeepSeek → reply, with PostgreSQL as the source of truth and a human handoff. A new business is added by configuration only. | Several small businesses on one service |
| **[Multi-machine automation platform](https://github.com/Jheremyt96/multi-machine-ai-workshop)** | Three always-on machines (Ubuntu mini PC, Mac M4, 10 TB server) on Tailscale. A job router sends each heavy task to the best machine by type and load; systemd services, memory and disk guards, nightly backups and a live dashboard of every AI session and long job. | 3 machines, 24/7 |
| **[Live-concert audio restoration](https://github.com/Jheremyt96/live-concert-audio-restoration)** (Áncora Tenores) | Batch pipeline: source separation (Mel-Band and BS-RoFormer), noise reduction, natural pitch correction and loudness, iterated through A/B reviews until approved. | 21 songs |
| **Social publishing pipeline** | Self-hosted Postiz + PostgreSQL: posts are generated, approved on a web page and published to Facebook and Instagram automatically. | — |

Each linked project has an overview with an architecture diagram and results. The code runs on my own private infrastructure; I am happy to walk through it on a call.

### Tools

Claude Code · LLM APIs (Claude, OpenAI, DeepSeek, GLM via OpenRouter) · Python · Node.js · PostgreSQL · SQLite · Supabase · Docker · Linux / systemd · Tailscale · ffmpeg · Whisper · Power BI · Tableau

### Contact

[LinkedIn](https://www.linkedin.com/in/alexander-jheremyt-salazar-requena-b55b10124/) · alexanderjheremyt@gmail.com
