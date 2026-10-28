### Hey, I'm seren-wib

[![Blog](https://img.shields.io/badge/Blog-kibotos.dev-000000?style=flat)](https://kibotos.dev/en/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-seren--wib-000000?style=flat)](https://www.linkedin.com/in/seren-wib/) [![Facebook](https://img.shields.io/badge/Facebook-seren--wib-000000?style=flat&logo=facebook&logoColor=white)](https://www.facebook.com/profile.php?id=61595087366681) [![Email](https://img.shields.io/badge/Email-smeteor0213%40gmail.com-000000?style=flat&logo=gmail&logoColor=white)](mailto:smeteor0213@gmail.com)

I'm a third-year Software major at Chungbuk National University in Korea. I like taking the repetitive parts of people's work and handing them to code and AI agents.

My main project is [Stairno Account](https://github.com/seren-wib/account.stairno.com), the account center and payments API behind every Stairno site. I built it solo, from planning documents to production: an OIDC provider, Toss Payments and PayPal checkout with card-on-file subscriptions, 115 requirements written before the code, 775 tests, and a 10-scenario payment rehearsal on production.

On team projects I usually end up as team lead. I write the API spec, DB schema and collaboration rules before anyone starts coding, and set up CI so nothing merges until the tests pass.

I post course notes and project write-ups at [kibotos.dev](https://kibotos.dev/en/), in Korean and English.

I'm a student ambassador for my university until September 2027. From October 2027 I'm open to backend and AI internships, and to new-grad roles after I graduate in February 2028.

I also take remote part-time work: AI agent setup, automation scripts, CI and dev environments. Reach me on LinkedIn or by email.

**Building**

- **[Atlas Odyssey](https://github.com/seren-wib/atlas-odyssey)** <a href="https://github.com/seren-wib/atlas-odyssey/stargazers"><img src="https://img.shields.io/github/stars/seren-wib/atlas-odyssey?style=flat&label=stars&color=000000" alt="stars" align="absmiddle"></a> - Personal learning atlas: map what to learn, record what's done, see what's left. Solo entry for the CBNU CUVIC Vibe Coding Contest 2026.
- **[kibotos.dev](https://github.com/seren-wib/vercel-blog)** <a href="https://github.com/seren-wib/vercel-blog/stargazers"><img src="https://img.shields.io/github/stars/seren-wib/vercel-blog?style=flat&label=stars&color=000000" alt="stars" align="absmiddle"></a> - Korean/English blog on Next.js 15, with a documented pipeline that turns lecture notes into posts.
- **[Coffee Shop](https://github.com/seren-wib/coffee-shop)** <a href="https://github.com/seren-wib/coffee-shop/stargazers"><img src="https://img.shields.io/github/stars/seren-wib/coffee-shop?style=flat&label=stars&color=000000" alt="stars" align="absmiddle"></a> - Coffee bean shop for a Software Engineering term project. Team lead, React + Vite front-end on Django.
- **[AI Woowangthon Team 18](https://github.com/woowangthon/WOOWANGTHON_TEAM_18)** <a href="https://github.com/woowangthon/WOOWANGTHON_TEAM_18/stargazers"><img src="https://img.shields.io/github/stars/woowangthon/WOOWANGTHON_TEAM_18?style=flat&label=stars&color=000000" alt="stars" align="absmiddle"></a> - Runs student projects on idle school lab PCs with Docker and k3s. Team entry for the CBNU 2026 AI Woowangthon.
- **Vane** - 2D top-down story adventure in Unity. Prototype.

**Shipped**

- **[Stairno Account](https://github.com/seren-wib/account.stairno.com)** <a href="https://github.com/seren-wib/account.stairno.com/stargazers"><img src="https://img.shields.io/github/stars/seren-wib/account.stairno.com?style=flat&label=stars&color=000000" alt="stars" align="absmiddle"></a> - One Stairno account and one saved card for every Stairno site, built solo from planning docs to production. An OIDC provider (PKCE, JWT/JWKS, refresh and site tokens) with sign-up, email verification, password reset, device sessions and account deletion; Toss Payments and PayPal behind one adapter, card-on-file subscriptions with retries and expiry, refunds, signed downloads, idempotent signed webhooks; Korean/English mail on SPF/DKIM/DMARC; CSP, rate limits and a privacy policy written to Korean law. 115 requirements written before the code, 775 tests (unit, PGlite integration, Astro component, workerd e2e), Lighthouse accessibility 100, Git Flow with rulesets, and a deploy that runs tests → DB migration → API → account center on Cloudflare Workers. Accepted with a 10-scenario payment rehearsal on production in test mode. Hono · Astro · Better Auth · Drizzle · Neon Postgres.
- **[my-status](https://github.com/seren-wib/my-status-public)** <a href="https://github.com/seren-wib/my-status-public/stargazers"><img src="https://img.shields.io/github/stars/seren-wib/my-status-public?style=flat&label=stars&color=000000" alt="stars" align="absmiddle"></a> - RPG-style status board: 348 roadmaps across 9 domains, learning logs regenerate stats. Python stdlib tooling + vanilla JS front-end.
- **[Stairno](https://stairno.com)** <a href="https://github.com/seren-wib/stairno.com/stargazers"><img src="https://img.shields.io/github/stars/seren-wib/stairno.com?style=flat&label=stars&color=000000" alt="stars" align="absmiddle"></a> - Brand hub at stairno.com: a halftone-dot canvas hero with a globe intro, full-page scrolling, Korean/English and dark mode. Astro on Cloudflare Pages, 123 tests gating every deploy.
- **[agent-commonplace](https://github.com/seren-wib/agent-commonplace)** <a href="https://github.com/seren-wib/agent-commonplace/stargazers"><img src="https://img.shields.io/github/stars/seren-wib/agent-commonplace?style=flat&label=stars&color=000000" alt="stars" align="absmiddle"></a> - One memory and one set of instructions for Claude Code, Codex and Antigravity on every machine, synced through agent hooks and a private git repo. Zero dependencies, CI on Linux/macOS/Windows.
- **[SCPC 2026 AI Agent Harness](https://github.com/seren-wib/scpc-2026-agent-harness)** <a href="https://github.com/seren-wib/scpc-2026-agent-harness/stargazers"><img src="https://img.shields.io/github/stars/seren-wib/scpc-2026-agent-harness?style=flat&label=stars&color=000000" alt="stars" align="absmiddle"></a> - Rule-based harness for an on-device agent benchmark, no LLM allowed. 0.8408 public score (baseline 0.5206), one 984-line deterministic file.
- **[Online Code Editor](https://github.com/seren-wib/opensource-web-azas)** <a href="https://github.com/seren-wib/opensource-web-azas/stargazers"><img src="https://img.shields.io/github/stars/seren-wib/opensource-web-azas?style=flat&label=stars&color=000000" alt="stars" align="absmiddle"></a> - Write, run and save code in the browser. Led a team of 4; I wrote the README, CONTRIBUTING and nine spec docs (API, DB schema, architecture, components) the team built from, plus most of the React/Monaco front-end, JWT auth and the CI.
- **usb-kit** - One command on a school Ubuntu PC logs into GitHub + Claude Code from a USB stick; `exit` wipes every trace.
- **[Amazon Price Scraper](https://github.com/seren-wib/amazon-price-scraper)** <a href="https://github.com/seren-wib/amazon-price-scraper/stargazers"><img src="https://img.shields.io/github/stars/seren-wib/amazon-price-scraper?style=flat&label=stars&color=000000" alt="stars" align="absmiddle"></a> - ScraperAPI + BeautifulSoup into SQLite/CSV, with a Streamlit price dashboard.
- **[Uncapped Construction](https://github.com/seren-wib/vic3-mod-construction-cap)** <a href="https://github.com/seren-wib/vic3-mod-construction-cap/stargazers"><img src="https://img.shields.io/github/stars/seren-wib/vic3-mod-construction-cap?style=flat&label=stars&color=000000" alt="stars" align="absmiddle"></a> - Victoria 3 mod that removes the per-building weekly construction cap.

**Contributing to**

<!-- Merged upstream PRs only, grouped by repo:
- [![owner/repo](https://img.shields.io/github/stars/owner/repo?style=flat&logo=github&logoColor=white&label=owner%2Frepo&color=000000)](https://github.com/owner/repo)
  - [#123](https://github.com/owner/repo/pull/123) - what it changed
-->

- [![nestjs/nest](https://img.shields.io/github/stars/nestjs/nest?style=flat&logo=github&logoColor=white&label=nestjs%2Fnest&color=000000)](https://github.com/nestjs/nest)
  - [#18264](https://github.com/nestjs/nest/pull/18264) - Map non form-data multipart requests to 415 in the multer interceptors
- [![nilbuild/developer-roadmap](https://img.shields.io/github/stars/nilbuild/developer-roadmap?style=flat&logo=github&logoColor=white&label=nilbuild%2Fdeveloper-roadmap&color=000000)](https://github.com/nilbuild/developer-roadmap)
  - [#10486](https://github.com/nilbuild/developer-roadmap/pull/10486) - Fix moved resource links and remove dead ones across six roadmap pages
- [![EbookFoundation/free-programming-books](https://img.shields.io/github/stars/EbookFoundation/free-programming-books?style=flat&logo=github&logoColor=white&label=EbookFoundation%2Ffree-programming-books&color=000000)](https://github.com/EbookFoundation/free-programming-books)
  - [#13566](https://github.com/EbookFoundation/free-programming-books/pull/13566) - Remove a hijacked TypeScript handbook link from the Russian list

**Stack**

Python · JavaScript · TypeScript · Node.js · React · Next.js · Astro · Hono · PostgreSQL · Drizzle · Tailwind CSS · GitHub Actions · Vercel · Cloudflare Workers · Cloudflare Pages · Claude Code
