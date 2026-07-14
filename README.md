# 👨‍💻 Jorch — Full-Stack Automation & DeFi Engineer

> *"Automatizo negocios, ejecuto en mercados financieros y construyo agentes de IA que trabajan 24/7."*

🌐 **[jorch-lab.top](https://jorch-lab.top)**

---

## 🎯 Perfil Profesional

Ingeniero de automatización y sistemas multi-agente. Construyo pipelines end-to-end: desde el scraping y enriquecimiento de datos hasta la ejecución financiera on-chain y la conversión comercial. Mis sistemas corren 24/7 en VPS con monitoreo en tiempo real.

**Abierto a:**
- 🏢 Posiciones **Full-Stack / Backend / Automation Engineer** en empresas remotas (NoDesk, Remotive, RemoteOK)
- 💼 **Bounties y micro-trabajo** (Gitcoin, Superteam, Layer3, Bountycaster, Upwork)
- 🤝 **Colaboraciones** en DeFi, trading algorítmico, SaaS B2B y automatización con IA

---

## 🧰 Stack Técnico

| Capa | Tecnologías |
|------|-------------|
| **Lenguajes** | Python · TypeScript · Rust · MQL5 · Bash · JavaScript |
| **Backend** | Node.js/Express · FastAPI · Next.js 14/16 · PostgreSQL · SQLite · Redis |
| **Blockchain** | Solana · Rust/Anchor · Jito · Helius · Kamino · Web3.js · SPL Token |
| **IA / Agentes** | Claude API · DeepSeek · Groq · CrewAI · ChromaDB · AgentDB · n8n |
| **Scraping** | Playwright · Scrapling · Apify · Telethon · Google Maps API |
| **Trading** | MetaTrader 5 · MQL5 · Python backtesting · ONNX ML · Pine Script |
| **Infra** | Docker · VPS (DigitalOcean/Hyonix) · Tailscale Mesh VPN · systemd |
| **Mensajería** | WhatsApp (Baileys) · Telegram Bot API · Twilio · SendGrid · Resend |

---

## 📂 Proyectos por Vertical

### ⛓️ Solana / Web3 / DeFi

| Proyecto | Descripción | Stack | |
|----------|-------------|-------|---|
| **[🛡️ Flash Crash Mitigator](https://github.com/Jorchspace/flash-crash-mitigator)** | Bot de protección DeFi: monitorea posición Kamino Finance 24/7, auto-repago cuando Health Factor < 1.2. Eventos a PostgreSQL. Docker + VPS. | Rust · Solana · PostgreSQL · Docker | 🔓 Público |
| Flash Crash Predator | Escáner proactivo de liquidaciones Kamino. Procesamiento paralelo con `rayon` sobre miles de cuentas on-chain. Offsets verificados empíricamente. | Rust · Solana · Kamino · Rayon | 🔒 Privado |
| Solana Bots Arsenal | Plan maestro 8 fases MEV: Barrendero OpenBook, Arqueología de Contratos Abandonados, Liquidaciones Flash Loan, Predator MEV, Salvamento Rug Pulls, Peg Arbitrage, Fat Finger Sniping, Oracle Arbitrage | Python · Rust · Solana · Jito | 🔒 Privado |
| Solana Hybrid Engine | Bot HFT dual: Hunter (token sniping <60s, filtros RugCheck, estrategia 80/20) + Guardian (liquidaciones DeFi con flash loans). Capital inicial $150 USD | Rust · Anchor · Jito · Helius | 🔒 Privado |
| **[GoldHunter](https://github.com/Jorchspace/goldhunter-medo)** | Plataforma gamificada "Explore-to-Learn & Earn" con cNFTs en Solana. Conecta marcas con audiencia física usando IA generativa. Hackathon Build With MeDo | React Native · Solana · Claude AI | 🔒 Privado |

### 🤖 SaaS & Automatización B2B

| Proyecto | Descripción | Stack | |
|----------|-------------|-------|---|
| **[🧠 Jarvis Command Center](https://github.com/Jorchspace/jarvis-command-center)** | Dashboard ejecutivo multi-proyecto unificado. WhatsApp Inbox multi-agente, SMM Pipeline, Google Maps Scraper, CRM leads, Skills Engine, pagos LemonSqueezy. Corre en Docker 24/7. | Next.js 14 · Express · PostgreSQL · Baileys · Docker | 🔓 Público |
| Bridge AI Engine | Pipeline B2B 9 fases 100% automatizado: scraping Google Maps → enriquecimiento IA → landing automática → outreach email → facturación → firma contratos. | Python · Apify · DeepSeek · Resend · Docuseal | 🔒 Privado |
| AI Business Activation Engine | Ecosistema SaaS 6 agentes IA que convierten búsquedas Google Maps en clientes para negocios locales. Blueprint Gemini XPRIZE Edition. Nichos: clínicas estéticas, dentales, hoteles boutique. $79-99/mes. | Python · Claude AI · n8n · Next.js · PostgreSQL | 📋 Blueprint |
| Landing Factory | Fábrica automatizada de landing pages: pipeline batch, CMS multi-tenant, generación por IA, analytics dashboard. Blueprint técnico completo. | Next.js · Supabase · LemonSqueezy · n8n | 📋 Blueprint |

### 🏦 Trading Algorítmico & Mercados

| Proyecto | Descripción | Stack | |
|----------|-------------|-------|---|
| GoldTraderEA | Sistema multi-estrategia XAUUSD. 14 estrategias institucionales ponderadas con motor de fusión. Confirmación 7+ requerida. Backtest: 287% return, 14.2% DD, 2.8 profit factor. | MQL5 · MetaTrader 5 | 🔒 Privado |
| Profitable EA Repository | Colección de EAs con ML: scalping XAUUSD/BTC/stocks, ONNX LSTM para predicción, backtesting Python, Pine Script TradingView. | MQL5 · Python · ONNX · TensorFlow | 🔒 Privado |
| Telegram → MT5 Bridge | Copy-trading automatizado: monitorea canales Telegram 24/7, parsea señales XAUUSD, ejecuta en MT5 con split de órdenes + trailing escalonado. Protección drawdown diario 3%. | Python · Telethon · MQL5 | 🔒 Privado |
| Bots Trading Arsenal | 35+ Expert Advisors catalogados y optimizados: GoldenHook, Monarca Fx, FullScalper, ProfitMachine. Plan maestro para canal VIP de señales con pasarela de pago. | MQL5 · MetaTrader 5 | 🔒 Privado |
| **[AItradingFX](https://jorch-lab.top)** | Landing + RAG Chatbot + Market Dashboard para trading. KB local ChromaDB con análisis técnico/fundamental. Bot Telegram VIP + EA exclusivo para afiliados Exness. | FastAPI · ChromaDB · Next.js 16 · Docker | 🔒 Privado |

### 🏠 Real Estate Tech

| Proyecto | Descripción | Stack | |
|----------|-------------|-------|---|
| WholeSmartEngine | Pipeline wholesale inmobiliario USA: scraping Zillow/Facebook FSBO → scoring IA de urgencia del vendedor → skip tracing → outreach SMS/email → contratos Docuseal → pagos ACH/Wire (UglyCash). Regla del 70%. | Python · Node.js · PostgreSQL · Apify · Docuseal | 🔒 Privado |
| Automatic Wholesaling | Motor autónomo de wholesaling Houston, TX. 6-stage pipeline: Scout→Normalize→Score→Trace→Outreach→Blast. HCAD integration, skip tracing, secuencias SMS + email. | Python · Celery · Playwright · Claude API · Twilio | 📋 Blueprint |

### 📱 Bots, Mensajería & Aplicaciones

| Proyecto | Descripción | Stack | |
|----------|-------------|-------|---|
| **[SMM + Blink Bot](https://github.com/Jorchspace/smm-blink-bot)** | Panel SMM vía Telegram con Auto-Match Engine: filtra 1,100+ servicios SMMWiz y asigna el más barato con margen ≥3x. Precios fijos. Pagos crypto (TRC20/BEP20/SOL) + LemonSqueezy. | Node.js · TypeScript · grammy · Drizzle ORM | 🔓 Público |
| AsistenteLeña | Bot Telegram para negocio real de venta de leña: pedidos paso a paso, optimización de rutas GPS (TSP Nearest Neighbor), geocodificación, panel admin, informes de ventas. | Python · Groq AI · SQLite · Nominatim | 🔒 Privado |
| SMM Dashboard | Panel de control web "Potencia tus Redes": métricas de órdenes, ingresos, profit, márgenes. WhatsApp Inbox multi-agente en vivo + mapa de clientes. | Next.js 14 · Express · Baileys · Leaflet | 🔒 Privado |
| Leads RAGChat | Dashboard de prospección: scraping Google Maps → clasificación IA (DeepSeek) → RAG chat → pipeline de campañas. 3 tabs: Scrapling, Campaña, Inbox WhatsApp. | Next.js 14 · Playwright · Scrapling · DeepSeek | 🔒 Privado |

### ⚖️ LegalTech & Proyectos Especiales

| Proyecto | Descripción | Stack | |
|----------|-------------|-------|---|
| LegalPagare | Plataforma web para Estudio Jurídico (Quito, Ecuador): registro inteligente de títulos valores, validación de viabilidad, generación automática de demandas .docx. Portal clientes + dashboard abogados. | Next.js 16 · Prisma · PostgreSQL · Anthropic SDK · Groq | 🔒 Privado |
| SkyStitcher | Motor de "Hacker Fares" aéreos: interlineado virtual con algoritmo de optimización precio+tiempo+geo. Monetización affiliate-first (Travelpayouts/Kiwi, CPA 1.2-2%). | Python · Scrapling · Next.js · PostgreSQL | 📋 Blueprint |
| Zona Oculta | Canal faceless de TikTok automatizado: pipeline con IA (guion → voz → video → subtítulos → publicación). Orquestador personalizado con aprobación vía Telegram. | Python · Streamlit · MoviePy · Edge TTS · Docker | 🔒 Privado |

---

## 🔥 Proyectos Destacados (Código Abierto)

### 🧠 [Jarvis Command Center](https://github.com/Jorchspace/jarvis-command-center)
Dashboard ejecutivo que unifica 4 proyectos bajo un solo panel. WhatsApp Inbox multi-agente con Baileys manejando conversaciones reales de clientes. Pipeline SMM con auto-match inteligente. Google Maps scraper para prospección de leads locales. PostgreSQL + Redis + Docker Compose. **Código público.**

### 🛡️ [Flash Crash Mitigator](https://github.com/Jorchspace/flash-crash-mitigator)
Bot DeFi en Rust puro que monitorea posiciones en Kamino Finance (Solana). Extrae health factor directamente de bytes on-chain y ejecuta auto-repago cuando HF < 1.2 para evitar liquidación. Eventos a PostgreSQL con tracing estructurado. **Código público.**

---

## 📊 El Ecosistema en Números

| Métrica | Valor |
|---------|-------|
| **Proyectos totales** | 22+ |
| **En producción activa** | 8 |
| **Código público** | 4 repos |
| **Verticales técnicas** | 5 (Web3 · SaaS · Trading · Real Estate · LegalTech) |
| **APIs externas integradas** | 15+ |
| **Lenguajes en uso activo** | Python, TypeScript, Rust, MQL5, Bash |

---

## 🔒 Sobre el Código Privado

La mayoría de mis proyectos son **privados por estrategia comercial** — sistemas de trading con alpha financiero, bots MEV en Solana, y pipelines B2B con ventaja competitiva. El código está disponible para discusión técnica en entrevistas y procesos de selección. Lo que es público (Jarvis CC, Flash Crash Mitigator, SMM+Blink) representa mi estándar de calidad.

---

## 📫 Contacto

- 🐙 **GitHub**: [github.com/Jorchspace](https://github.com/Jorchspace)
- 🌐 **Web / Portfolio**: **[jorch-lab.top](https://jorch-lab.top)**
- 📧 **Email**: Disponible para recruiters, colaboraciones y bounties

---

> *"No busco trabajo — busco problemas interesantes que resolver. Si necesitás alguien que entienda el stack completo, desde el scraper hasta el dashboard, desde el smart contract hasta el bot de Telegram, hablemos."*
