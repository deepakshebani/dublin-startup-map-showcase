<p align="center">
  <img src="./banner.svg" alt="Dublin Startup Map" width="100%">
</p>

<h1 align="center">Dublin Startup Map</h1>

<p align="center">
  <b>Every startup, scale-up and tech company hiring in Dublin — on one live, interactive map.</b>
</p>

<p align="center">
  <a href="https://dublinstartupmap.ie"><img src="https://img.shields.io/badge/Live-dublinstartupmap.ie-2f6fd8?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live site"></a>
  <img src="https://img.shields.io/badge/Updated-daily-4f93ff?style=for-the-badge" alt="Updated daily">
  <img src="https://img.shields.io/badge/PWA-installable-132a52?style=for-the-badge" alt="Installable">
  <img src="https://img.shields.io/badge/Cloudflare-Pages-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare Pages">
</p>

<p align="center">
  <a href="https://dublinstartupmap.ie"><b>▶ Open the live map</b></a>
</p>

<p align="center">
  <a href="https://dublinstartupmap.ie"><img src="./screenshots/map-desktop.png" alt="Dublin Startup Map — companies across Dublin on one map" width="100%"></a>
  <br><sub><i>Zoomed into the city — every company's logo sits where its office is. Click to open the live map →</i></sub>
</p>

---

## What it is

A free, fast map that turns a job hunt in Dublin into a map you can read at a glance. Open roles, commute times and hiring history for every company, in one place — no sign-up, no ads.

## What it does

- 🗺️ **Companies on a map** — startups, scale-ups and global tech hubs across Dublin, by exact building or district.
- 💼 **Live open roles** — read from each company's own careers board and refreshed daily, searchable by title, team and category inside each company.
- 🚇 **Commute at a glance** — walking time to the nearest Luas and DART stop, and distance from your home.
- 🛂 **Work-permit history** — which companies were issued employment permits this year.
- ⭐ **Shortlist & tracker** — save companies, set a status and notes, export to CSV. Kept in your browser only.
- 🌗 **Dark / light** with an animated theme reveal, and **installable** as an app on your phone.

## See it in action

Open any company for its live roles, commute times and work-permit history — then search that company's jobs by title, team or category.

<p align="center">
  <a href="https://dublinstartupmap.ie"><img src="./screenshots/mobile.png" alt="Dublin Startup Map on mobile — installable" width="340"></a>
  <br><sub>On your phone: swipeable cards, a drag-up list, and <b>Add to Home Screen</b></sub>
</p>

<p align="center">
  <a href="https://dublinstartupmap.ie"><b>↳ Try the real thing at dublinstartupmap.ie</b></a>
</p>

## How it is built

| Layer | Tech |
| --- | --- |
| Map & UI | Leaflet + MarkerCluster, hand-written HTML / CSS / vanilla JS — no framework |
| Data pipeline | Python — company careers boards, public employment-permit records, transit stops |
| Hosting | Cloudflare Pages, deploys on push |
| Extras | PWA manifest, View Transitions, design-token theming |

## Privacy

Everything you save (shortlist, home point, settings) stays in **your browser**. No tracking, no third-party cookies, no accounts.

---

<p align="center">
  <sub>The application source code and its datasets are kept in a private repository. This page is a project overview only — no code or data is published here.</sub>
</p>

<p align="center">
  <sub>© 2026 Deepak Shebani · <a href="https://dublinstartupmap.ie">dublinstartupmap.ie</a> · <a href="https://www.linkedin.com/in/deepak-shebani">LinkedIn</a></sub>
</p>
