<div align="center">

# Cem Ali Akgül

**Computer Engineering @ Mersin University** · AI systems, security tooling and full-stack apps

<a href="https://www.linkedin.com/in/cem-ali-akgül-9a1581399/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:cemali0220@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

I build projects end to end and ship them with tests, CI and documentation. Recent work covers a reinforcement learning agent trained on a live Minecraft server, a network intrusion detection system, an AI study platform in production and an offline Android app.

- Third-year Computer Engineering student (2024 – 2028), English C1
- Interested in **AI/ML**, **cybersecurity** and **developer tools**
- Now building **[RepoLens AI](https://github.com/LocalinTheEngineer/RepoLensAI)**: ask questions about a GitHub repo and get answers that cite the exact files and lines
- Open to internships, including international roles

## Featured work

### [MinecrAI](https://github.com/LocalinTheEngineer/MinecrAI) · reinforcement learning
A Minecraft bot that joins a Java server as a player and takes commands (chop trees, craft tools, mine ore), plus a Gymnasium environment for training it with behaviour cloning and PPO over a WebSocket bridge. In evaluation, the shared mining policy collected **2.75 more ore per episode than a random baseline (95% CI [0.53, 4.97])**. Supports optional natural-language commands through an LLM.
<br/>`Python` `Gymnasium` `PPO` `Node.js` `Mineflayer` `WebSocket`

### [SmartStudy AI](https://github.com/LocalinTheEngineer/SmartStudyAI) · full-stack AI app · [live demo](https://smartstudy-ai-delta.vercel.app)
Upload course material and get AI summaries, generated quizzes and an adaptive study plan that gives more time to the topics you score poorly on. Includes spaced-repetition reminders, JWT auth, and a Jest/Vitest test suite running in GitHub Actions.
<br/>`React` `Node.js` `Express` `MongoDB` `Gemini API` `GitHub Actions`

### [NetworkIds](https://github.com/LocalinTheEngineer/NetworkIds) · cybersecurity
Real-time intrusion detection system with four sliding-window detectors (port scan, brute force, traffic spike, SYN flood). Alerts are stored in SQLite and streamed to a live Flask dashboard. Runs on live traffic via Scapy, or in a simulation mode that works without root.
<br/>`Python` `Scapy` `Flask` `SQLite` `pytest`

### [LogLynx](https://github.com/LocalinTheEngineer/loglynx) · developer tool
Zero-dependency CLI for log analysis. Scores log health, clusters recurring errors, flags time windows that break from the file's own baseline and compares runs to catch regressions after a deploy. Also offers live watch, HTML/JSON reports and a dashboard.
<br/>`Python` `CLI` `Anomaly Detection` `CI`

<details>
<summary><b>More projects</b></summary>
<br/>

| Project | What it is | Stack |
|---|---|---|
| [Pillgement](https://github.com/LocalinTheEngineer/pillgement) | Offline Android medication reminder with exact-time alarms that survive reboots, refill tracking and TR/EN support. No accounts, servers or network permission | JavaScript · Capacitor · Android |
| [Game Library](https://github.com/LocalinTheEngineer/GameLibrary) | Personal game tracker with RAWG auto-fill, play-time stats and public profiles you can follow · [live](https://localintheengineer.github.io/GameLibrary/) | React · Express · PostgreSQL |
| [IconRave](https://github.com/LocalinTheEngineer/IconRave) | Makes real Windows desktop icons fall, bounce and jump to the beat, using Win32 cross-process calls and WASAPI + FFT audio analysis | C# · WinForms · Win32 |
| [DevTracker](https://github.com/LocalinTheEngineer/devtracker) | Learning-progress tracker with streaks, categories and weekly charts | React · Vite |

</details>

## Tech

**Languages:** Python · JavaScript · TypeScript · C# · SQL<br/>
**Backend:** Node.js · Express · FastAPI · Flask<br/>
**Frontend & mobile:** React · Vite · Capacitor<br/>
**Data & AI:** PostgreSQL · MongoDB · SQLite · Gymnasium · PPO · Gemini API · embeddings / vector search<br/>
**Tooling:** Git · GitHub Actions · Jest · Vitest · pytest · Linux
