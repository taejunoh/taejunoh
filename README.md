# Hi, I'm Taejun Oh 👋

Software engineer in New York. I build things I actually want to exist.

I build apps for iOS, Android, macOS, and the web, and write about what I learn from shipping and maintaining them.

<br/>

## 🚀 Released

**[GoLightWeight](https://golightweight.app)** · *Offline-first workout tracker*
> My alarm goes off at 4:20 a.m. and I am at the gym by 5:00. I tried a lot of fitness apps and none of them felt like mine, so I built one for intermediate to advanced lifters: 449 exercises, every one illustrated and 445 animated, 23 programs, PR detection, analytics, an Apple Watch companion, Apple Health, and cloud sync that works offline first. Recent releases added a community feed, heart rate on the wrist, and editing a saved workout without breaking records. English and Korean. iOS is on the [App Store](https://apps.apple.com/app/id6781628893); Android is on [Google Play](https://play.google.com/store/apps/details?id=com.golightweight.app).

`React Native` `Expo` `TypeScript` `WatermelonDB` `Supabase` `RevenueCat` `SwiftUI` `Next.js`

---

**[SpotTrove](https://spottrove.com)** · *Street parking + garage map, NYC*
> I don't drive, but every friend who does complains about reading parking signs. SpotTrove puts the rule on the map instead of the pole: legality by time of day, posted meter rates with what a stay costs, a tap-to-copy ParkNYC code, garage pricing, and a camera sign scanner. Built on 79,650 sign-parsed block faces and 561,642 legality rules across all five boroughs. Works without an account. iOS 1.7 is on the [App Store](https://apps.apple.com/app/spottrove/id6764669814).

`FastAPI` `PostgreSQL` `PostGIS` `Supabase` `React Native` `Expo` `Mapbox` `Next.js` `Claude API`

---

**[DoEveryday](https://doeveryday.app)** · *Habit tracker: web, iOS, Android, browser extension*
> I like having a routine and wanted a calm place to log it. One tap a day, a year heatmap, a habit-strength score that survives a missed day, rest days, a monthly report, and home-screen widgets on both phones. A "don't miss twice" push nudges you before a streak breaks. iOS on the [App Store](https://apps.apple.com/app/id6762887548), Android on [Google Play](https://play.google.com/store/apps/details?id=app.doeveryday), and a new-tab extension on [Chrome](https://chromewebstore.google.com/detail/doeveryday-%E2%80%94-build-habits/lfnjhojafagecmadibalpecnfhlobkkp), [Edge](https://microsoftedge.microsoft.com/addons/detail/doeveryday-%E2%80%94-build-habits/gfanlklnofdjgkmgjbjjmhoclekiachh), [Firefox](https://addons.mozilla.org/firefox/addon/doeveryday-habit-tracker/), and Safari. English and Korean.

Web: `React 18` `Vite` `Supabase` `Stripe` `Vercel` · Mobile: `React Native` `Expo` `Zustand` `RevenueCat` `WidgetKit`

---

**[Great Whiskey Narrative](https://greatwhiskeynarrative.com)** · *Whisky label scanner + library*
> A shelf of unfamiliar labels tells you nothing about taste, origin, or whether the price is fair. Point the camera at a label and get the distillery, region, tasting notes, and typical price, then keep a record of what you have poured. The library is live on the web at 1,078 bottles, every one illustrated, with food pairings and a Whisky 101 guide; bottles the scanner does not know yet go into a request queue. The iOS app is on TestFlight with Sign in with Apple, collection backup, a Journey tab of badges and ranks, an App Attest-gated API, and a catalogue that updates over the air.

`Astro` `React` `TypeScript` `Expo` `React Native` `Express` `Railway`

---

**[Seoul Rising](https://apps.apple.com/us/app/seoul-rising/id6822836898)** · *K-pop trends widget for iOS*
> K-pop news reaches US fans after Korea has already moved on. Seoul Rising watches YouTube channels, Wikipedia pageviews, and Korean entertainment headlines, scores artist momentum, and flags when Korea moves before English-language coverage. A keyless Python pipeline writes one static file every 30 minutes; the iOS app and widget read it, with no server, accounts, or API keys. The app is live on the [App Store](https://apps.apple.com/us/app/seoul-rising/id6822836898). [Code](https://github.com/taejunoh/seoulpulse) is public.

`Python` `GitHub Actions` `SwiftUI` `WidgetKit` `iOS 18`

---

**[Needlbar](https://github.com/taejunoh/needlbar)** · *AI coding usage monitor for macOS*
> A menu-bar monitor for Claude Code, Codex, and Cursor: locally aggregated tokens and estimated cost next to each provider's quota and reset window, a system monitor for CPU, memory, disk, network, and battery in the same popover, and a home widget. Local-first, with no account, backend, or telemetry. Rust does the session parsing behind a Swift UI. v0.3.9 is signed and notarized for macOS 14+ on Apple Silicon; install with `brew install --cask taejunoh/tap/needlbar` or download the zip. Code is public.

`Swift` `SwiftUI` `Rust` `macOS 14+`

---

**[JobTracker](https://github.com/taejunoh/easy-job-application-tracker)** · *Self-hosted job application tracker + Chrome extension*
> Save a posting from LinkedIn, Indeed, Glassdoor, Lever, Greenhouse, or Workday in one click, compare it against your resume for matched and missing keywords, and fill your profile links into application forms. AI extraction is optional and bring-your-own-key. Code is public.

`Next.js 16` `React 19` `Prisma 7` `PostgreSQL` `Tailwind CSS`

---

**[sam6pk-mac](https://github.com/taejunoh/sam6pk-mac)** · *Romance of the Three Kingdoms VI PK on macOS*
> Runs the Korean release on modern Macs through Wine, with fixed Hangul rendering and no mid-battle freeze. Ships the environment only; bring your own game files.

`Wine` `Shell` `macOS`

<br/>

## 🔨 In Development

**[CrewOn](https://getcrewon.com)** · *Club management platform*
> Running a club means events in one app, members in a spreadsheet, and dues in a chat. CrewOn puts them in one place: events with instant, approval, and lottery RSVP plus QR check-in, dues and online payments through Stripe Connect with automatic reminders, a club feed with polls and chat, a sponsorship marketplace, and a public "find a club" page. The web app for organizers is built; the Expo member app is in TestFlight; public launch is coming soon.

`Turborepo` `Next.js 15` `tRPC` `Prisma` `PostgreSQL` `Expo` `Stripe Connect` `Vercel` `Neon`

---

**[AllinSimple Pulse](https://pulse.allinsimple.com)** · *Uptime and heartbeat monitoring*
> Checks websites, APIs, cron jobs, and workers, confirms an outage with retries before opening one incident, and sends Down and recovery alerts to Email, Telegram, Discord, and Slack. In a private pilot. Its sibling, [AllinSimple Desk](https://desk.allinsimple.com/?lang=en), is a ledger for the links, recurring costs, and renewal dates of many projects, with a public demo.

`Next.js 16` `React 19` `Drizzle` `PostgreSQL` `Tailwind CSS`

---

**[AllinSimple Check](https://taejunoh.com/projects/allinsimple-check.html)** · *Local browser flow prototype*
> Manually checks a fixed flow against its bundled demo site by signing in, submitting a sample, and checking the result text. Includes success, mismatch, and delay modes, with local run history.

---

**[AllinSimple Desk](https://desk.allinsimple.com/?lang=en)** · *Personal operations ledger*
> Keeps project links, recurring costs, renewal dates, and maintenance tasks together. The local MVP stores its ledger in SQLite and supports JSON backup and restore. The public read-only demo uses fictional data.

`React 19` `Vite` `SQLite`

---

**[Security Scan Hub](https://github.com/taejunoh/security-scan-hub)** · *Seven security tools, one scan*
> Running Google OSV Scanner, NVIDIA SkillSpector, OpenAI Codex Security, Alibaba Open Code Review, OpenAI's PHP2Shell checker, Cloudflare's audit skill, and Anthropic's vuln-scan harness means seven setups and seven report formats. Security Scan Hub runs the ones you pick in a single scan and merges the findings into one Security Inbox, showing which tools completed, were skipped, or failed, with HTML, JSON, and SARIF output. AI tools run only with explicit opt-in. The desktop app is a 0.2.2 prerelease, signed and notarized for Apple silicon Macs, with a Windows x64 build. Code is public.

`Node.js` `Electron` `SARIF` `CLI`

---

**[TypeLeague](https://typeleague.gg)** · *Competitive typing leaderboards*
> A typing test usually answers one question: how fast am I? I wanted it to also answer how fast my school, my company, my city, and my country are. One test feeds every board at once, with affiliations verified by email OTP, weekly seasons that start at launch (it is in preseason now), server-side anti-cheat, a per-key heatmap with weak-key drills, and share cards. Guests see the rank they would hold before signing in. Korean typing is IME-aware.

`Next.js 14` `TypeScript` `Tailwind CSS` `FastAPI` `PostgreSQL` `Redis` `Clerk`

---

**[Mise](https://taejunoh.com/projects/mise.html)** · *Restaurant back-office automation*
> Back-office automation for independent restaurants, covering daily P&L, invoices and payments, recipes and menu cost, inventory, purchasing, and tax prep. Active pilot using live POS and invoice data.

`Python` `FastAPI` `PostgreSQL` `Next.js`

<br/>

## 🤫 Under Wraps

**Name under wraps** · *iOS day-out planner*
> Plan a day out with a tab for each stop, compare routes on one map, and follow live subway guidance.

`iOS`

---

**Name under wraps** · *Offline prayer companion*
> A quiet, offline prayer companion. Content and naming are still in review.

`iOS`

<br/>

## 🪦 Retired

**[ClaudeBeat](https://taejunoh.com/projects/claudebeat.html)** · *Retired macOS menu-bar app*
> Retired in November 2026 and no longer maintained. ClaudeBeat was the starting point for [Needlbar](https://github.com/taejunoh/needlbar). [Read the essay](https://taejunoh.com/writing/what-claudebeat-taught-me.html).

`Swift` `SwiftUI` `AppKit` `macOS 14+`

---

**[MLB Walk-Forward Lab](https://taejunoh.com/projects/mlb-walkforward-lab.html)** · *Retired MLB forecasting experiment*
> A traceable pregame forecast record with settlement rules and data-quality checks kept separate from the headline accuracy figure.

`Python` `Forecasting` `Data quality`

---

**[Fieldnote](https://taejunoh.com/projects/fieldnote.html)** · *Retired sports research desk*
> A personal sports research desk with persistent threads, background analysis, and a separate ledger for confirmed bets.

`Next.js` `Research tooling`

---

**[kalshi-arb](https://github.com/taejunoh/kalshi-arb)** · *Automated prediction-market trading, Mar–Sep 2026*
> 24 strategies, 1,983 real-money trades, 1,278 commits, one EC2 box. Final result −$2,004, of which fees were $1,035. Measured edge against the closing line: +0.30%, confidence interval −0.45% to +1.04%, against a 1.25% break-even. I shut it down because the measurement finally got good enough to say no. The README is about the part worth keeping: how to find out whether a strategy is real.

`Python` `SQLite` `FastAPI` `systemd` `AWS EC2`

<br/>

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

<br/>

## 🌱 Interests

- 🛠️ Building side projects
- 🤖 AI / LLM tooling
- 📈 Financial markets — space tech, AI-driven biotech, semiconductors
- 🤖 Machine learning fundamentals
- 🏋️ Fitness & strength training
- 🏙️ New York City food & restaurant culture

<br/>

## 📬 Get in Touch

[![Website](https://img.shields.io/badge/Website-000000?style=flat-square&logo=safari&logoColor=white)](https://taejunoh.com)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:itstaejun@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/taejunoh)

<br/>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=taejunoh&style=flat-square&color=2D6A4F&label=profile+views" />
</div>
