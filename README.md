# Hi, I'm Konstantinos Kolta 👋

Junior software engineer and Computer Science student (University of East London) building web, desktop and mobile applications with **TypeScript**, **React/React Native**, **Node.js** and **Python/FastAPI**, alongside client business sites in **Astro** and **Tailwind CSS**.

I learn by shipping. Everything below is something I built end to end — data model and API through to interface, build config and deployment.

---

### Selected work

**[AgonCup](https://github.com/Shasuani/AgonCup)** — tournament platform (team project) · [live public beta](https://lol.gameras.gr)
A multi-tenant League of Legends tournament platform, used by 5 Greek Discord communities. A Discord bot handles sign-up and tournament commands, and an Electron desktop client creates and starts custom lobbies through the local League client API, with automatic host failover. Results are accepted only when at least 6 of the 10 players' reports agree. The FastAPI backend isolates each Discord server's data with Postgres row-level security, and admins manage everything from a React console.
`Python` `FastAPI` `PostgreSQL` `Redis` `WebSockets` `Electron` `React` `TypeScript` `Docker`

**[Agency OS](https://github.com/Shasuani/agency-os)** — operations platform
A Next.js and Supabase monorepo with a background worker: it watches an inbox over the Gmail API, classifies what arrives, drafts replies and follow-ups, and puts them in an approval queue rather than sending blind. Edited drafts are fed back as style examples.
`TypeScript` `Next.js` `Supabase` `Postgres` `pnpm workspaces`

**[Ranked Study App](https://github.com/Shasuani/ranked-study-app-backend)** — API + mobile client
A study timer built as a ranked ladder: finish a focus session, earn XP and LP, climb tiers. The [backend](https://github.com/Shasuani/ranked-study-app-backend) is Express and Prisma with JWT auth, request validation, rate limiting and a layered controller/service split; the [mobile client](https://github.com/Shasuani/ranked-study-app-mobile) is React Native.
`Node.js` `Express` `Prisma` `JWT` `React Native` `Expo`

**[Fedari](https://github.com/Shasuani/fedari-web)** — client business site · [live demo](https://shasuani.github.io/fedari-web/)
A marketing site built for a Dubai home-maintenance company. Component-driven pages, lead capture, SEO metadata, generated sitemap, and continuous deployment to GitHub Pages.
`Astro` `Tailwind CSS` `TypeScript` `GitHub Actions`

**[Ascend](https://github.com/Shasuani/ascend-mobile-app)** — mobile app
A React Native app that turns long-term goals into a concrete daily plan.
`React Native` `Expo`

**[Tokyo Night CV](https://github.com/Shasuani/tokyo-night-cv)** and **[Identity Hub](https://github.com/Shasuani/identity-hub-website)** — interactive front-end
An explorable CV rendered as a walkable neon city, and a cinematic scroll-driven site about personal data. Both built on Three.js without a framework.
`Three.js` `WebGL` `Chart.js`

---

### Tools I work with

| Area | Tools |
| --- | --- |
| Languages | TypeScript, JavaScript, Python, SQL, HTML, CSS |
| Front-end | React, React Native, Electron, Astro, Three.js, Tailwind CSS |
| Back-end | Node.js, Express, Prisma, Python, FastAPI, Postgres, Redis, Supabase |
| Tooling | Git, GitHub Actions, GitLab CI, Docker, pnpm, uv, Expo, Vite, VS Code |

---

### Currently learning

- Testing at the level that lets me refactor without fear
- Web performance and accessibility fundamentals
- Getting deeper into type-level TypeScript
