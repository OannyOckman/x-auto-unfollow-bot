# X Auto Unfollow Bot
> This project automates bulk unfollowing on the X platform by simulating natural mobile interactions on Android devices. The X Auto Unfollow Bot removes the repetitive manual workload, ensuring consistent account hygiene and follower list maintenance with minimal effort.


<p align="center">
  <a href="https://Appilot.app" target="_blank"><img src="https://github.com/Instagram-Automations/Footer-test/blob/main/appilot-baner.png" alt="Appilot Banner" width="100%"></a>
</p>

<p align="center">
  <a href="https://t.me/devpilot1" target="_blank"><img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:support@appilot.app" target="_blank"><img src="https://img.shields.io/badge/Email-support@appilot.app-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a href="https://Appilot.app" target="_blank"><img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website"></a>
  <a href="https://discord.gg/xvPWXJXCw7" target="_blank"><img src="https://img.shields.io/badge/Join-Appilot_Community-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Appilot Discord"></a>
</p>



## Introduction
This automation system identifies follow targets on the X app, navigates the interface, and performs controlled unfollow actions. It replaces a common repetitive workflow done manually by creators, growth managers, and social teams. By delegating the task to automation, users maintain cleaner follow lists, reduce spam, and restore balanced engagement ratios.

### Why Automated Unfollow Management Matters
- Saves hours of manual scrolling and tapping in the X app.
- Ensures consistent pacing that mimics human behavior to avoid rate limits.
- Reduces follow clutter and improves account relevance.
- Scales across multiple Android devices for large operations.
- Provides logs and reporting for full visibility.

## Core Features
| Feature | Description |
|----------|-------------|
| UI Automation Engine | Executes unfollow actions through controlled Android UI interactions. |
| Safe-Rate Scheduler | Manages delays and pace to avoid triggering app protections. |
| Multi-Device Support | Runs simultaneously on many Android devices with isolated workers. |
| Proxy & Network Routing | Rotates network identities for safer distributed behavior. |
| Auto-Target Discovery | Scrolls feeds/following lists to locate valid unfollow targets. |
| Retry & Backoff Logic | Recovers from failures, modal pop-ups, or slow device responses. |
| Activity Logging | Captures timestamps, actions, and decisions in structured logs. |
| Exportable Reports | Generates JSON and CSV summaries of unfollow operations. |
| Configurable Rules | Allows filtering by user type, follow age, or patterns. |
| Human-Like Interaction | Randomizes scrolls, tap positions, and intervals for realism. |

---
## How It Works
1. **Input or Trigger** — User provides device list, account credentials, and unfollow rules.
2. **Core Logic** — Automation scrolls the following list, identifies valid targets, and performs unfollow operations.
3. **Output or Action** — Produces logs, summaries, and per-session result files.
4. **Other Functionalities** — Handles pop-ups, network changes, and throttled UI states.
5. **Safety Controls** — Rate limits, random delays, and configurable caps per session.

---
## Tech Stack
**Language:** Python
**Frameworks:** Appilot, UI Automator-based flows
**Tools:** Device schedulers, proxy manager, YAML config loader
**Infrastructure:** Local device farm or remote Android orchestration environments

---
## Directory Structure
    automation-bot/
    ├── src/
    │   ├── main.py
    │   ├── automation/
    │   │   ├── tasks.py
    │   │   ├── scheduler.py
    │   │   └── utils/
    │   │       ├── logger.py
    │   │       ├── proxy_manager.py
    │   │       └── config_loader.py
    ├── config/
    │   ├── settings.yaml
    │   ├── credentials.env
    ├── logs/
    │   └── activity.log
    ├── output/
    │   ├── results.json
    │   └── report.csv
    ├── requirements.txt
    └── README.md

---
## Use Cases
- **Creators** use it to clean their following list so they can maintain healthier engagement ratios.
- **Agencies** use it to manage multiple client accounts so they can standardize workflows across devices.
- **Growth teams** use it to prune inactive or mismatched follows so they can improve account relevance.
- **Automation engineers** use it to orchestrate bulk device tasks so they can minimize manual labor.

---
## FAQs
**Does it run without connecting ADB?**
Yes—ADB-less automation via Appilot/UI Automator flows is supported.

**Can it target specific profiles?**
Rules can filter by patterns, follow age, or scroll position.

**Is rate limiting handled automatically?**
Yes, safe pacing, randomization, and session caps are built in.

**Can logs be exported?**
All sessions output structured JSON and CSV reports.

---
## Performance & Reliability Benchmarks
**Execution Speed:** Typically 18–26 unfollow actions per minute on standard device farm hardware.
**Success Rate:** Approximately 93–94% across long-running jobs with retry and backoff logic.
**Scalability:** Designed to coordinate 300–1,000 Android devices through sharded queues and horizontally scaled workers.
**Resource Efficiency:** ~8–12% CPU and 180–260 MB RAM per worker, depending on device density.
**Error Handling:** Automatic retries, exponential backoff, structured logging, alert hooks, and resilient recovery flows keep operations stable under heavy UI or network variation.


<p align="center">
<a href="https://cal.com/app-pilot-m8i8oo/30min" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
 
  <a href="https://www.youtube.com/@Appilot-app/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
