<h1 align="center">
  Jorch Lab — Autonomous DeFi Engineering
</h1>

<h4 align="center">Jorge Darío Aranda · San Juan Bautista, Paraguay</h4>

<p align="center">
  <img src="https://img.shields.io/badge/Solana-Mainnet-9945FF?style=flat&logo=solana&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-Production-orange?style=flat&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude_Code-MCP-black?style=flat&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/CrewAI-Agent_Orchestrator-6C5CE7?style=flat&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-Automation-EA4B71?style=flat&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/Apify-Web_Scraping-FF6B35?style=flat&logo=apache&logoColor=white" />
  <img src="https://img.shields.io/badge/VPS-24%2F7-green?style=flat&logo=digitalocean&logoColor=white" />
</p>

---

> *"No construyo demos. Construyo bots que operan solos."*

Ingeniero de sistemas autónomos. Diseño, programo y despliego agentes que corren 24/7 en Solana — liquidaciones, fees permissionless, arbitraje y MEV. Todo KISS. Todo Rust/Python. Todo con memoria.

---

## 🤖 IA & Agentes Autónomos

**No solo uso IA — construyo sistemas donde la IA trabaja para mí.**

| Capacidad | Stack | Qué hace |
|-----------|-------|----------|
| **Orquestación Multi-Agente** | CrewAI + DeepSeek | Mesa Directiva de agentes que genera blueprints técnicos |
| **Sub-Agentes Especializados** | Bash + Python | Coder, Reviewer, Researcher, Reverser, Error Memory |
| **Claude Code CLI** | Anthropic API + MCP | Desarrollo acelerado con herramientas y skills personalizadas |
| **MCP Servers** | n8n, Apify, PostgreSQL | Tools de scraping, DB queries, y automatización directa desde el CLI |
| **Skills System** | Bash hooks + settings.json | Skills verificables: code-review, verify, graphify, deep-research |
| **Web Scraping Inteligente** | Apify Actors + Crawlee | Extracción de leads, protocolos DeFi, documentación on-chain |
| **Pipeline Autocorrector** | Aider + Error Memory | 6 fases: consulta → código → detección → autocorrección → deploy |
| **Memoria de Errores** | JSON + Python | Previene reintentos de enfoques fallidos. Ahorra tokens. |
| **Notificaciones Telegram** | Bot API + Bash | Alertas en tiempo real de cada hito del pipeline |

> *"El agente tira la idea, Claude Code construye el blueprint, el Coder genera los archivos, el Reviewer audita, y Telegram te avisa cuando terminó. Ese es el sueño."*

---

## 🧠 Proyectos Activos

<table>
<tr>
<td width="50%">

### 🦅 Flash-Crash-Predator
**Liquidador Atómico Kamino V2**

- Flash Loan + liquidate + redeem en 1 tx atómica
- Jito Bundles para subasta MEV
- Tip dinámico en 2 rondas (conservador → agresivo)
- WebSocket listener + Reserve Cache pre-load
- Stack: `Rust` `Solana` `Jito` `Jupiter API`

</td>
<td width="50%">

### 🪵 Tríada Barrendero OpenBook
**3 bots permissionless · Capital $0**

- **v1:** consumeEvents Serum V3 (monitor)
- **Settle:** settleFunds masivo — fondos abandonados
- **v2:** sweepFees + consumeEvents OpenBook V2
- 750k+ mercados escaneables
- Stack: `Python` `solana-py` `solders`

</td>
</tr>
<tr>
<td>

### 🧠 Jorch Lab Agent System
**Orquestador autónomo de código**

- Mesa Directiva: CrewAI + DeepSeek
- 5 sub-agentes especializados
- Pipeline 6 fases con autocorrección
- Memoria de errores anti-loop
- Stack: `Bash` `CrewAI` `DeepSeek` `Aider`

</td>
<td>

### 🛡️ Flash-Crash-Mitigator
**Monitor DeFi + Auto-Repago**

- Health Factor Kamino Finance
- Auto-repay cuando HF < 1.2
- Docker + PostgreSQL + Tailscale
- Stack: `Rust` `Docker` `Solana`

</td>
</tr>
</table>

---

## ⚡ Stack Técnico

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" />
  <img src="https://img.shields.io/badge/Solana-9945FF?style=for-the-badge&logo=solana&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Claude_Code-CLI-9775FF?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-Tools-FF6B35?style=for-the-badge&logo=apache&logoColor=white" />
  <img src="https://img.shields.io/badge/CrewAI-Agents-6C5CE7?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Apify-Scraping-FF8C00?style=for-the-badge&logo=apache&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-Automation-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/Aider-AI_Coding-10A37F?style=for-the-badge&logo=openai&logoColor=white" />
</p>

**Lo que hago todos los días:**
- CPI (Cross-Program Invocation) en Solana — instrucciones permissionless
- Flash Loans atómicos con Jito Bundles y tips dinámicos
- Parsing de cuentas on-chain (offsets binarios, discriminators, PDAs)
- WebSocket listeners + polling para detección en tiempo real
- Sistemas autónomos con autocorrección y memoria de errores
- Orquestación de agentes LLM (CrewAI + DeepSeek + Claude Code)
- MCP Servers personalizados (n8n, Apify, PostgreSQL) para desarrollo asistido
- Web scraping masivo con Apify Actors + Crawlee para inteligencia de mercado

---

## 🔬 Próximos Proyectos (Plan Maestro 8 Fases)

| # | Proyecto | Estrategia | Stack |
|---|----------|------------|-------|
| 4 | Predator Pro Max | Arbitraje atómico cross-DEX con Jito | Rust |
| 5 | Rug Pull Salvage | Extraer liquidez de pools abandonadas | Python |
| 6 | Peg Arbitrage | wSOL↔SOL spread en congestión | Rust |
| 7 | Fat Finger Sniping | Capturar errores humanos en libros de órdenes | Rust |
| 8 | Oracle Arbitrage | Ventana de milisegundos Pyth vs CEX | Rust |

---

<p align="center">
  <img height="150em" src="https://github-readme-stats.vercel.app/api?username=Jorchspace&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" />
  <img height="150em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jorchspace&layout=compact&theme=tokyonight&hide=html,css&langs_count=6" />
</p>

---

<p align="center">
  <i>Construyendo en WSL2 · Deployando en DigitalOcean VPS · Conectado por Tailscale</i>
</p>
