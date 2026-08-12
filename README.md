<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=200&section=header&text=Vivaldi&fontSize=70&fontColor=FFFFFF&animation=fadeIn&fontAlignY=35&desc=Solutions%20Architect&descAlignY=55&descSize=20" width="100%" />

<a href="https://github.com/VivaldiCode">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=36BCF7&center=true&vCenter=true&width=650&lines=Designing+systems+end+to+end;Distributed+AI%2C+data+pipelines+and+infrastructure;From+architecture+to+production" alt="Typing SVG" />
</a>

<br />

<img src="https://komarev.com/ghpvc/?username=VivaldiCode&label=Profile%20views&color=0e75b6&style=flat-square" alt="Profile views" />
<img src="https://img.shields.io/github/followers/VivaldiCode?label=Followers&style=flat-square&color=0e75b6" alt="Followers" />
<img src="https://img.shields.io/github/stars/VivaldiCode?label=Total%20stars&style=flat-square&color=0e75b6" alt="Stars" />

</div>

---

## 👋 About me

I'm **Vivaldi**, a **Solutions Architect** based in Portugal.

I design systems end to end — the architecture, the services that implement it, and the infrastructure that keeps it running. Most of my work sits where several concerns meet at once: distributed AI inference, real-time data ingestion, self-hosted platforms, and making all of it observable and reproducible.

I care about solutions that people can actually run. That means open source by default, sensible defaults, documented deployment paths, and software that doesn't assume unlimited hardware.

- 🧠 Building **distributed AI infrastructure** — orchestration, routing, multi-provider gateways
- 📊 Designing **data-driven platforms** on top of time-series and streaming systems
- 🐳 Shipping everything as **containerised, self-hostable** software
- 🍓 Making heavy infrastructure run on **constrained hardware**, down to ARM boards
- 🤝 Contributing to **Portuguese civic tech** and open-source tooling
- 🌍 I work in **🇵🇹 Portuguese**, **🇬🇧 English**, **🇫🇷 French**, **🇪🇸 Spanish** and **🇮🇹 Italian**

---

## 🛠️ Tech stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=ts,js,python,cs,bash,html,css&theme=dark" alt="Languages" />

**Frameworks & Runtimes**

<img src="https://skillicons.dev/icons?i=nodejs,react,nextjs,vue,electron,vite,tailwind,dotnet&theme=dark" alt="Frameworks" />

**Infrastructure & DevOps**

<img src="https://skillicons.dev/icons?i=docker,kubernetes,linux,nginx,githubactions,cloudflare,git&theme=dark" alt="Infrastructure" />

**Data & Messaging**

<img src="https://skillicons.dev/icons?i=postgres,sqlite,mongodb,redis,kafka&theme=dark" alt="Data" />

</div>

---

## 🚀 Featured projects

<div align="center">
<table>
<tr>
<td width="50%" valign="top">

### 🧠 AI-Orchestrator

A self-hosted gateway that pools AI inference across multiple Macs running Ollama, with optional fallback to Anthropic, OpenAI and Bedrock.

Drop-in replacement for the Ollama REST API, with round-robin and least-latency routing, health checks, automatic failover, and TimescaleDB-backed analytics.

`TypeScript` · `Fastify` · `React` · `PostgreSQL/TimescaleDB` · `Docker`

[**→ Repository**](https://github.com/VivaldiCode/AI-Orchestrator)

</td>
<td width="50%" valign="top">

### 🎙️ voice-gateway

A local-first desktop app for talking to a Hermes agent by voice, with push-to-talk and wake-word modes.

Runs speech-to-text and text-to-speech entirely on-device via whisper.cpp and Piper — no API keys required — with optional cloud upgrades for higher quality.

`Electron` · `React` · `Python` · `WebSocket` · `openWakeWord`

[**→ Repository**](https://github.com/VivaldiCode/voice-gateway)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌍 world-war-3-indicator

A modular geopolitical risk index (0–100) composed from 18+ live public data feeds — commodities, VIX, defense equities, ACLED conflict events, GDELT news tone and military signals.

Each source publishes a normalised score and the composite redistributes weights when a feed fails, so the index stays interpretable. Situational awareness, explicitly not a forecast.

`Next.js` · `TypeScript` · `PostgreSQL` · `SQLite` · `Docker`

[**→ Repository**](https://github.com/VivaldiCode/world-war-3-indicator)

</td>
<td width="50%" valign="top">

### 🐳 kafka-armv7

Apache Kafka packaged for **ARMv7** — the architecture official images don't publish for.

Brings event streaming to Raspberry Pi and IoT-class hardware. Available straight from Docker Hub as `guiters/kafka-armv7`.

`Docker` · `Kafka` · `ARM` · `Shell`

[**→ Repository**](https://github.com/VivaldiCode/kafka-armv7)

</td>
</tr>
</table>
</div>

---

## 🤝 Helping the community

Open source I contribute to and help maintain — civic tech that serves Portugal, and infrastructure tooling the self-hosting community depends on.

<div align="center">
<table>
<tr>
<td width="50%" valign="top">

### 🔥 fogospt

[Fogos.pt](https://fogos.pt) — the public platform that tracks active wildfires across Portugal in real time, used by citizens and emergency services during fire season.

`PHP` · `Laravel` · `Node.js` · `Docker`

[**→ Repository**](https://github.com/VivaldiCode/fogospt) · [Upstream](https://github.com/FogosPT/fogospt)

</td>
<td width="50%" valign="top">

### 🌦️ daily_weather_report

The automation behind **VOST Portugal**'s daily weather bulletins — pulls IPMA data each morning and renders report graphics for the mainland, Azores and Madeira, ready for publication.

`Python` · `IPMA API` · `GitHub Actions`

[**→ Repository**](https://github.com/VivaldiCode/daily_weather_report) · [Upstream](https://github.com/vostpt/daily_weather_report)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ FlareSolverr

A proxy server that solves Cloudflare and DDoS-GUARD challenges through a headless browser, returning cookies and HTML so downstream tools can keep working.

Multi-architecture, including ARM32 and ARM64.

`Python` · `Selenium` · `Docker`

[**→ Repository**](https://github.com/VivaldiCode/FlareSolverr) · [Upstream](https://github.com/FlareSolverr/FlareSolverr)

</td>
<td width="50%" valign="top">

### 📡 TP-Link-Archer-C6U

A Python library for programmatic access to 100+ TP-Link and Mercusys routers — status, connected clients, WiFi bands, DHCP reservations, VPN and reboot.

Widely used to bring consumer routers into Home Assistant.

`Python` · `Requests` · `PyCryptodome`

[**→ Repository**](https://github.com/VivaldiCode/TP-Link-Archer-C6U) · [Upstream](https://github.com/AlexandrErohin/TP-Link-Archer-C6U)

</td>
</tr>
</table>
</div>

---

## 📊 GitHub stats

<div align="center">

<img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=VivaldiCode&theme=tokyonight" alt="Profile details" />

<br />

<img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=VivaldiCode&theme=tokyonight" alt="Repos per language" />
<img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=VivaldiCode&theme=tokyonight" alt="Most commit language" />

<br />

<img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=VivaldiCode&theme=tokyonight" alt="Stats" />
<img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=VivaldiCode&theme=tokyonight&utcOffset=1" alt="Productive time" />

<br /><br />

<img src="https://streak-stats.demolab.com?user=VivaldiCode&theme=tokyonight&hide_border=true&background=0D1117&ring=36BCF7&fire=36BCF7&currStreakLabel=36BCF7" width="60%" alt="Streak stats" />

<br /><br />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=VivaldiCode&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=36BCF7&line=36BCF7&point=FFFFFF&area=true" width="95%" alt="Activity graph" />

</div>

---

## 🏆 Achievements

<div align="center">

<table>
<tr>
<td align="center" width="25%">
<img src="https://github.githubassets.com/images/modules/profile/achievements/pull-shark-default.png" width="72" alt="Pull Shark" /><br />
<b>Pull Shark ×3</b><br />
<sub>128+ merged pull requests</sub>
</td>
<td align="center" width="25%">
<img src="https://github.githubassets.com/images/modules/profile/achievements/pair-extraordinaire-default.png" width="72" alt="Pair Extraordinaire" /><br />
<b>Pair Extraordinaire ×4</b><br />
<sub>48 co-authored commits — max tier</sub>
</td>
<td align="center" width="25%">
<img src="https://github.githubassets.com/images/modules/profile/achievements/quickdraw-default.png" width="72" alt="Quickdraw" /><br />
<b>Quickdraw</b><br />
<sub>Closed in under 5 minutes</sub>
</td>
<td align="center" width="25%">
<img src="https://github.githubassets.com/images/modules/profile/achievements/yolo-default.png" width="72" alt="YOLO" /><br />
<b>YOLO</b><br />
<sub>Merged without code review</sub>
</td>
</tr>
</table>

</div>

---

## 🐍 Contribution graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/VivaldiCode/VivaldiCode/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/VivaldiCode/VivaldiCode/output/github-contribution-grid-snake.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/VivaldiCode/VivaldiCode/output/github-contribution-grid-snake.svg" width="95%" />
</picture>

</div>

---

<div align="center">

### 💭 Currently

Building distributed **AI inference infrastructure** that runs on hardware you own, and designing **data platforms** that stay honest about their own uncertainty.

<br />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=120&section=footer" width="100%" />

</div>
