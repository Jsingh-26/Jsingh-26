## Hi, I'm Jaspreet 👋

I build the tools customers and teams actually use: custom apps, integrations and automation, built with AI, shipped with tests, CI and a rollback.

- **Portfolio:** [jaspreet-builds.vercel.app](https://jaspreet-builds.vercel.app) — what is in use, what I built, and the public apps, in one scrolling page.
- **Now:** Customer Experience Manager II at GreyOrange. I designed, built and solely own nine internal systems for the Customer Success org, including a customer-health platform live across 50+ global sites: ~26,000 automated checks, CI on every push, one-command deploy with rollback, and runbooks for handover. Those repos are private employer work; everything below is personal and public.
- **10+ years** across enterprise CX and technical support (Enphase, NTT Data, Accenture, Dell), always the person who turns a recurring pain into a tool.
- **How I work:** AI writes most of the code under my direction. I design the system, review everything, maintain the test suites, and own deploy and operations.
- **Looking for:** Forward Deployed / AI Deployment / Implementation / Solutions Engineering roles where building is the job. Remote worldwide (I work evening-IST overlap with US and EU teams), Delhi NCR, or remote India.

### Featured projects

| Project | What it is | Stack |
|---|---|---|
| [**Cleverbot**](https://github.com/Jsingh-26/Cleverbot) | AI chat assistant for web and Android. Streams free LLMs through serverless functions so the API key never reaches the browser, with sign-in, saved chat history, server-side web search and 57 tests. A release workflow for a signed Android APK (keyless Google Cloud sign-in) is written; its first run waits on the cloud setup. | React · TypeScript · Netlify Functions · Convex · Capacitor · GitHub Actions |
| [**Wordwright**](https://github.com/Jsingh-26/Wordwright) [![CI](https://github.com/Jsingh-26/Wordwright/actions/workflows/ci.yml/badge.svg)](https://github.com/Jsingh-26/Wordwright/actions/workflows/ci.yml) | Open-source text expander for Windows: type a shortcut and your snippet appears in any app, with date, clipboard and cursor variables. v0.2.0 ships as an installer with no account and no network access. I also built an on-device AI rewriter and shipped it in three releases (v0.1.3–v0.1.5), then parked it on its own branch with a full write-up, because I couldn't test it on enough hardware to support it properly. 140 tests, CI. | C# · .NET 10 · WPF |
| [**YouTube Playlist Inbox**](https://github.com/Jsingh-26/youtube-playlist-inbox) [![CI](https://github.com/Jsingh-26/youtube-playlist-inbox/actions/workflows/ci.yml/badge.svg)](https://github.com/Jsingh-26/youtube-playlist-inbox/actions/workflows/ci.yml) | YouTube lets you subscribe to channels, not playlists. This adds that: new videos from the playlists you follow land hourly in one private inbox playlist, managed from a small web app. Quota-aware sync, a storage format that scales past the 9 KB property limit with automatic migration, and an undo for bad batches. | Google Apps Script · YouTube Data API · clasp · Node tests · GitHub Actions |
| [**Star Switch**](https://github.com/Jsingh-26/star-switch) | Two-player browser platformer: collect the stars, hit the switch, open the exit. Two players share one keyboard, or one plays by touch on phone or iPad; an offline Android edition is built from the same code. Fixed-timestep physics so speed is identical on 60 Hz and 120 Hz screens. [Play it](https://star-switch.vercel.app/). | TypeScript · Vite · HTML Canvas · Web Audio |
| [**Roll & Learn**](https://github.com/Jsingh-26/roll-and-learn) [![CI](https://github.com/Jsingh-26/roll-and-learn/actions/workflows/ci.yml/badge.svg)](https://github.com/Jsingh-26/roll-and-learn/actions/workflows/ci.yml) | Kids' counting game for Android: count, match the number word, name the color. Synthesized, license-free sound effects, an installable APK via EAS, and a typecheck in CI. | Expo · React Native · TypeScript |

### At work (private code)

The code belongs to my employer, so it isn't public. Here is what I built and how. Everything runs on **Google Apps Script** by design: customer data never leaves the company's Google Workspace, nothing needs third-party hosting, and every tool uses the company's own sign-in and access controls.

- **Customer Happiness Index platform:** one shared engine serving 50+ global sites, replacing six separate codebases. Every feature ships to all sites in one push, with no per-site changes. Pulls from Salesforce, Grafana, ClickUp and Jira into per-site scorecards, a leadership dashboard and monthly review decks. ~7,700 automated checks, CI on every push, versioned rollback.
- **Customer Success Portal (built, rolling out):** a Weekly Business Review builder with .pptx export, incident readers and a KPI editor (~17,000 automated checks). Gets live Grafana numbers past a CORS wall using a browser extension and a local bridge, with no infrastructure change. One-command deploy that verifies itself and rolls back to any numbered version.
- **Grafana → Slack Connect kit (built, rolling out):** built in one week for another team. A zero-dependency Node.js tool packaged as a single .exe with a one-double-click setup for non-technical staff, and 394 tests, including an end-to-end run against a fake Grafana and a fake Slack.
- **AI that drafts, a person approves (built, rolling out):** a customer upgrade-impact document where the model only fills data into a fixed template and a person approves every row before any PDF is produced. Plus a root-cause analysis method for Claude: 18 playbooks, with every finding confirmed in a second system.

### Toolbox (AI writes the code under my direction; I design, review, test and run it)

TypeScript · React · React Native / Expo · Node.js · C# / .NET · Google Apps Script · Vite · Convex · Netlify Functions · GitHub Actions · OpenRouter model API · Claude · Salesforce · Jira · Grafana

### Get in touch

[linkedin.com/in/js26](https://linkedin.com/in/js26)
