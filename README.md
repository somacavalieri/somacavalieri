## Hi, I'm Soma

Twenty years building digital products. In the last few years, AI-assisted development dropped the cost of getting an idea out of my head far enough that I stopped living with problems no app on the market solved and started solving them myself. There have been dozens, nearly all of them for an audience of one. What's on this page is the subset where the problem turned out not to be mine alone.

**[LinkedIn](https://www.linkedin.com/in/flaviosoma/)** · **[somacavalieri.com](https://somacavalieri.com)** · contato@somacavalieri.com

### Projects

| Project | What it is | Stack | |
|---|---|---|---|
| **[somaplay](https://github.com/somacavalieri/somaplay)** | Offline PWA for reading chord charts, playing along with multitrack audio and singing karaoke — built for a tablet on a music stand. No account, no server. | Vanilla JS · Web Audio · IndexedDB · Service Worker | **[Live demo](https://somacavalieri.github.io/somaplay/)** |
| **[track-viewer](https://github.com/somacavalieri/track-viewer)** | A focused GPX viewer for planning bike trips: bulk-import hundreds of tracks onto satellite imagery, organise them, mark points of interest. | React · TypeScript · MapLibre GL · Postgres | **[Live demo](https://somacavalieri.github.io/track-viewer/)** |
| **[soma_trails](https://github.com/somacavalieri/soma_trails)** | Offline satellite maps for mountain biking — download tiles by area from the phone, overlay dozens of GPX tracks, record a breadcrumb with no cell signal. In weekly use on my own phone. | Flutter · Dart · Android | Sideloaded APK |
| **[flow-metrics-skill](https://github.com/somacavalieri/flow-metrics-skill)** | An agent skill that turns a board of issues into a self-contained flow-metrics dashboard — WIP, throughput, lead and cycle time, aging, blocked. | Claude Code skill · HTML | — |

`track-viewer` and `soma_trails` are one problem in two contexts: planning at the desk, riding in the woods. Each spec declares what the other one is for — the boundary was drawn before either was built.

Both ship with the spec attached. [Track Viewer's PRD](https://github.com/somacavalieri/track-viewer/blob/main/docs/PRD.md) carries the numbered requirements, the risk table and a decision log that keeps the losing option's merits instead of deleting them. That document is the more interesting half of the repository.

### How I build

Model-agnostic by habit — the assistants and the editors turn over every few months, and the workflow is what stays. Agents wired through MCP into the tools the work already lives in: Notion, Supabase, Linear, Slack, GitHub. n8n for the automation around it. Specs, research synthesis and prototypes move through that stack. The judgement calls don't.

### Background

- **Head of Product, then Head of PLG at Sólides** — through the largest funding round in Latin American HR tech. Product teams of 10 to 23 people, a freemium tier built from zero, product diligence on the M&A team.
- **Head of Product & UX at VIK** — led the pivot from B2C to B2B: burning cash to ten-plus enterprise clients in under a year, including iFood, Localiza and Grupo Dasa. Covered technical direction as well when the company lost its CTO.
- **Group Product Manager at EstrelaBet**; growth advisor at **Ticket/Edenred** and **ALLIA**.
- Twenty years in digital products, starting as a graphic designer and learning JavaScript on the job as a frontend developer in Melbourne. Design → UX → interaction design → frontend → product → growth — which is why I read the code and argue with engineering as a peer.
- Now running **[Soma Consultoria](https://somacavalieri.com)**, an independent product-led growth practice — and open to product leadership roles.
