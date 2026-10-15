# About me

Hi, I'm a web developer and automation engineer from Hamburg. I like building clean UIs, automating everything that's annoying to do twice, and in my spare time I do GTA game modding.

# Stuff I did (projects)

## Legacy (closed source)

**German open.mp server · 2024–2026 · 600 registered user accounts**

Legacy was a German multiplayer server for GTA San Andreas, running on open.mp. Around the game server I built the tools players used every day: a desktop launcher, a community website with a control panel, interactive setup guides, a login theme and the forum design.

| Area | What it is | Stack |
| --- | --- | --- |
| [Launcher](#launcher) | Desktop app to start the game and manage mods | ![Tauri](https://img.shields.io/badge/Tauri-24C8D8?logo=tauri&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white) |
| [Control Panel](#control-panel) | Community website connected to the game database | ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white) |
| [Keycloak Theme](#keycloak-theme) | Custom login and registration pages | ![Keycloakify](https://img.shields.io/badge/Keycloakify-4D4D4D?logo=keycloak&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) |
| [open.mp Install & Connection Guide](#openmp-install--connection-guide) | Animated setup guide, built entirely for the web | ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?logo=framer&logoColor=white) |
| [Windows Security Settings Animations](#windows-security-settings-animations) | Animated troubleshooting for common Windows issues | ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?logo=framer&logoColor=white) |
| [Forum](#forum) | Custom forum design | ![WoltLab Suite](https://img.shields.io/badge/WoltLab_Suite-1A5A96) |

---

### Launcher
![Legacy](https://img.shields.io/badge/Legacy-7C3AED?style=for-the-badge)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=for-the-badge&logo=tauri&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)

Desktop launcher for a SA:MP / open.mp server.

- Server and player status, TeamSpeak indicator
- News feed from the forum
- GTA SA path management and one-click game start
- Player list with search and filters for factions, gangs and civilians
- Mod manager: install/remove, categories, search, sharing, import and backups, ASI loader detection

![Launcher](launcher.png)

<p align="center">
  <img src="playerlist.png" alt="Player list" width="49%">
  <img src="modloader.png" alt="Mods" width="49%">
</p>

`300–400 downloads`

---

### Control Panel
![Legacy](https://img.shields.io/badge/Legacy-7C3AED?style=for-the-badge)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![HeroUI](https://img.shields.io/badge/HeroUI-000000?style=for-the-badge&logo=heroui&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

Community website and control panel for the server, connected to the game database.

- Landing page with background video, a faction showcase and feature sections
- Factions overview: legal vs. criminal with live player counts and faction profiles
- Server contests: live, scheduled and finished contests with progress, rewards and top players
- Event calendar: monthly view of all server events
- Player profiles, stats, achievements, leaderboards and an interactive map
- Admin panel for moderation, logs and content

<p align="center">
  <img src="cp-profile.png" alt="Player profile" width="49%">
  <img src="cp-home-factions.png" alt="Choose your side" width="49%">
</p>

![Factions](cp-factions.png)

<p align="center">
  <img src="cp-contest.png" alt="Contests" width="49%">
  <img src="cp-calendar.png" alt="Event calendar" width="49%">
</p>

---

### Keycloak Theme
![Legacy](https://img.shields.io/badge/Legacy-7C3AED?style=for-the-badge)
![Keycloakify](https://img.shields.io/badge/Keycloakify-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

Custom theme for the Keycloak login and registration pages.

- Login with username or email, password reset
- Registration with in-game name, terms acceptance and reCAPTCHA
- Carousel showcasing game content next to the form

<p align="center">
  <img src="keycloak-theme-login.png" alt="Login" width="49%">
  <img src="keycloak-theme-register.png" alt="Registration" width="49%">
</p>

---

### open.mp Install & Connection Guide
![Legacy](https://img.shields.io/badge/Legacy-7C3AED?style=for-the-badge)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![Lucide](https://img.shields.io/badge/Lucide-F56565?style=for-the-badge&logo=lucide&logoColor=white)

Interactive guide from download to the first server connection. It's built entirely for the web: no screen recordings and no video files, just code that runs in the browser.

- Browser, installer and open.mp launcher rebuilt as React components with Tailwind CSS
- A TypeScript timeline scripts cursor movement, clicks and every UI state
- Transitions with Framer Motion, icons with Lucide
- Starts when scrolled into view (IntersectionObserver), then loops
- `No video assets to maintain: sharp at any size, and text changes are a code edit`

<p align="center">
  <img src="01-download.gif" alt="Download" width="49%">
  <img src="02-install.gif" alt="Configure" width="49%">
</p>
<p align="center">
  <img src="03-connect.gif" alt="Connect" width="49%">
</p>

---

### Windows Security Settings Animations
![Legacy](https://img.shields.io/badge/Legacy-7C3AED?style=for-the-badge)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)

Troubleshooting help for the most common Windows problems when starting the game. Windows dialogs are recreated in React and walk the player through each fix.

- Run as administrator: fixes open.mp starting singleplayer instead of multiplayer
- Windows Security: adds an antivirus exclusion when open.mp is flagged as a virus
- File Explorer: unpacks the texture pack into `samp\cache` when custom textures don't load

<p align="center">
  <img src="04-admin.gif" alt="Run as administrator" width="49%">
  <img src="05-antivirus.gif" alt="Antivirus exclusion" width="49%">
</p>
<p align="center">
  <img src="06-textures.gif" alt="Textures" width="49%">
</p>

---

### Forum
![Legacy](https://img.shields.io/badge/Legacy-7C3AED?style=for-the-badge)
![WoltLab Suite](https://img.shields.io/badge/WoltLab_Suite-1A5A96?style=for-the-badge)

Custom design for the community forum, built on WoltLab Suite.

- Sections for announcements, events, changelogs and suggestions
- Shared navigation with website, dashboard, rules and roadmap
- News also shows up in the launcher

![Forum](wotlab.png)
