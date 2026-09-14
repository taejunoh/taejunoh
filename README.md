# Hi, I'm Taejun Oh 👋

Software engineer in New York. I build things I actually want to exist.

Three iOS apps on the App Store, two of them also on Google Play, a browser extension in four stores, two notarized macOS menu-bar apps on Homebrew, and one trading system I shut down on purpose and wrote up.

<br/>

## 🚀 Shipped

**[GoLightWeight](https://golightweight.app)** · *Offline-first workout tracker*
> My alarm goes off at 4:20 a.m. and I am at the gym by 5:00. I tried a lot of fitness apps and none of them felt like mine, so I built one for intermediate to advanced lifters: 449 exercises, every one illustrated and 445 animated, 23 programs, PR detection, analytics, an Apple Watch companion, Apple Health, and cloud sync that works offline first. Version 1.6 added a community feed with posts and in-app notifications. English and Korean. iOS is on the [App Store](https://apps.apple.com/app/id6781628893); Android is on [Google Play](https://play.google.com/store/apps/details?id=com.golightweight.app).

`React Native` `Expo` `TypeScript` `WatermelonDB` `Supabase` `RevenueCat` `SwiftUI` `Next.js`

---

**[SpotTrove](https://spottrove.com)** · *Street parking + garage map, NYC*
> I don't drive, but every friend who does complains about reading parking signs. SpotTrove puts the rule on the map instead of the pole: legality by time of day, posted meter rates with what a stay costs, a tap-to-copy ParkNYC code, garage pricing, and a camera sign scanner. Built on 79,650 sign-parsed block faces and 561,642 legality rules across all five boroughs. Works without an account. iOS 1.6 is on the [App Store](https://apps.apple.com/app/spottrove/id6764669814).

`FastAPI` `PostgreSQL` `PostGIS` `Supabase` `React Native` `Expo` `Mapbox` `Next.js` `Claude API`

---

**[DoEveryday](https://doeveryday.app)** · *Habit tracker: web, iOS, Android, browser extension*
> I like having a routine and wanted a calm place to log it. One tap a day, a year heatmap, a habit-strength score that survives a missed day, rest days, a monthly report, and home-screen widgets on both phones. iOS on the [App Store](https://apps.apple.com/app/id6762887548), Android on [Google Play](https://play.google.com/store/apps/details?id=app.doeveryday), and a new-tab extension on [Chrome](https://chromewebstore.google.com/detail/doeveryday-%E2%80%94-build-habits/lfnjhojafagecmadibalpecnfhlobkkp), [Edge](https://microsoftedge.microsoft.com/addons/detail/doeveryday-%E2%80%94-build-habits/gfanlklnofdjgkmgjbjjmhoclekiachh), [Firefox](https://addons.mozilla.org/firefox/addon/doeveryday-habit-tracker/), and Safari. English and Korean.

Web: `React 18` `Vite` `Supabase` `Stripe` `Vercel` · Mobile: `React Native` `Expo` `Zustand` `RevenueCat` `WidgetKit`

---

**[TypeLeague](https://typeleague.gg)** · *Competitive typing leaderboards*
> A typing test usually answers one question: how fast am I? I wanted it to also answer how fast my school, my company, my city, and my country are. One test feeds every board at once, with affiliations verified by email OTP, weekly seasons, server-side anti-cheat, a per-key heatmap with weak-key drills, and share cards. Guests see the rank they would hold before signing in. Korean typing is IME-aware.

`Next.js 14` `TypeScript` `Tailwind CSS` `FastAPI` `PostgreSQL` `Redis` `Clerk`

---

**[Needlbar](https://github.com/taejunoh/needlbar)** · *AI coding usage monitor for macOS*
> A menu-bar monitor for Claude Code, Codex, and Cursor: locally aggregated tokens and estimated cost next to each provider's quota and reset window, a system monitor for CPU, memory, disk, network, and battery in the same popover, and a home widget. Local-first, with no account, backend, or telemetry. Rust does the session parsing behind a Swift UI. v0.3.2 is signed and notarized for macOS 14+ on Apple Silicon; install with `brew install --cask taejunoh/tap/needlbar` or download the zip. Code is public.

`Swift` `SwiftUI` `Rust` `macOS 14+`

---

**[ClaudeBeat](https://claudebeat.com)** · *Claude usage in the menu bar*
> Session, weekly, and per-model gauges for Claude AI usage, threshold alerts, and reset notifications, with the session kept in the macOS Keychain. v1.1.2, notarized. Install with `brew install --cask taejunoh/tap/claudebeat` or unzip and run. Code is public.

`Swift` `SwiftUI` `AppKit` `macOS 14+`

---

**[easy-job-application-tracker](https://github.com/taejunoh/easy-job-application-tracker)** · *Self-hosted job tracker + Chrome extension*
> Save a posting from LinkedIn, Indeed, Glassdoor, Lever, Greenhouse, or Workday in one click, compare it against your resume for matched and missing keywords, and fill your profile links into application forms. AI extraction is optional and bring-your-own-key. Code is public.

`Next.js 16` `React 19` `Prisma 7` `PostgreSQL` `Tailwind CSS`

<br/>

## 🔨 In progress

**[Great Whiskey Narrative](https://greatwhiskeynarrative.com)** · *Whisky label scanner + library*
> A shelf of unfamiliar labels tells you nothing about taste, origin, or whether the price is fair. Point the camera at a label and get the distillery, region, tasting notes, and typical price, then keep a record of what you have poured. The library is live on the web at 688 bottles with food pairings and a Whisky 101 guide, growing through a batch pipeline toward 1,500; bottles the scanner does not know yet go into a request queue. The iOS app is on TestFlight with an App Attest-gated API and a catalogue that updates over the air. Your collection never leaves the device.

`Astro` `React` `TypeScript` `Expo` `React Native` `Express` `Railway`

---

**[CrewOn](https://getcrewon.com)** · *Club management platform*
> Running a club means events in one app, members in a spreadsheet, and dues in a chat. CrewOn puts them in one place: events with instant, approval, and lottery RSVP plus QR check-in, dues and online payments through Stripe Connect with automatic reminders, a club feed with polls and chat, a sponsorship marketplace, and a public "find a club" page. The web app for organizers is built; the Expo member app is in TestFlight; public launch is coming soon.

`Turborepo` `Next.js 15` `tRPC` `Prisma` `PostgreSQL` `Expo` `Stripe Connect` `Vercel` `Neon`

<br/>

## 🤫 Under wraps

**Mise** (pseudonym) · *Restaurant back-office automation*
> A friend with ten years in hospitality had a problem he had been sitting with for a long time, so we built it together: back-office automation for independent restaurants. Daily P&L, invoices and vendor payments, recipes and menu cost, inventory counts, purchasing, and tax prep, all from live Toast POS data and native invoice ingestion. In a live pilot with a high-volume NYC restaurant.

`Python` `FastAPI` `PostgreSQL` `Next.js 16` `Railway` `Vercel`

<br/>

## 🪦 Retired

**[kalshi-arb](https://github.com/taejunoh/kalshi-arb)** · *Automated prediction-market trading, Mar–Sep 2026*
> 24 strategies, 1,983 real-money trades, 1,278 commits, one EC2 box. Final result −$2,004, of which fees were $1,035. Measured edge against the closing line: +0.30%, confidence interval −0.45% to +1.04%, against a 1.25% break-even. I shut it down because the measurement finally got good enough to say no. The README is about the part worth keeping: how to find out whether a strategy is real.

`Python` `SQLite` `FastAPI` `systemd` `AWS EC2`

<br/>

## 🎮 Also

**[sam6pk-mac](https://github.com/taejunoh/sam6pk-mac)** · *Romance of the Three Kingdoms VI PK on macOS*
> Runs the Korean release on modern Macs through Wine, with fixed Hangul rendering and no mid-battle freeze. Ships the environment only; bring your own game files.

`Wine` `Shell` `macOS`

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
