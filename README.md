## Vinh Van

**Fullstack developer in Hanoi** — NestJS and React, both in TypeScript, on a product team.
I work on **two live product-feed apps**, one on the Shopify App Store and one on SHOPLINE.

What I care about is the unglamorous half of shipping — knowing what a change breaks *before* you
make it, and being able to prove it works afterwards. That is also why I put real effort into
working with AI agents: I write the guardrails first, then let them move fast inside those.

📄 **[vinhvan.netlify.app](https://vinhvan.netlify.app)** — CV, projects, and how I work.

---

### What I work on

| | |
| --- | --- |
| 🛒 **[Omega Google & Facebook Feed](https://apps.shopify.com/google-shopping-feed-pro)**<br>*Shopify App Store* | **Day job — the product, not a side project.** Live since 2020, **4.9★ from 110 reviews**. Creates and syncs product feeds to Google Shopping, Meta Catalog, TikTok, Bing, Pinterest and custom XML from one dashboard. I've worked on it since my internship, across the NestJS API, its queue workers and the React admin. Closed source; the link goes to the listing. |
| 🛒 **[FeedNexa — Multiple Feed](https://apps.shopline.com/detail/feednexa_multiple_feed)**<br>*SHOPLINE App Store* | **Day job, second platform.** Generates a separate XML product feed per marketing channel, location or collection, each structured to the receiving catalog's requirements. The same domain on a second commerce platform — which is why I can say the domain knowledge transfers, not just the codebase. Closed source. |
| **[visic](https://github.com/acevinh/visic)** | Chat with your own documents, answered only from your own content, with citations you can click back to. NestJS 11 · React/TS · PostgreSQL + pgvector · JWT · SSE streaming. |
| **[claude-skills](https://github.com/acevinh/claude-skills)** | Four Claude Code skills for disciplined AI-assisted development: scope control, conventions read at runtime instead of remembered, evidence before "done", and a QA ledger that outlives the session. |
| **[vinh-cv](https://github.com/acevinh/vinh-cv)** | The CV site above. React + TypeScript + Vite, liquid-glass UI built to a written design contract — no UI framework, no animation library, no PDF library, no analytics. |

### Selected work on the feed apps

- Built the app's bulk disapproval workflow, its most-worked-on area — turning raw Google and Meta
  rejection codes into a triaged issue list merchants can act on.
- Cut false "not approved" verdicts by replacing a one-shot catalog check with a retry chain and a
  merchant-visible ETA.
- Raised Shopify → Google product-category coverage to 99.5%, measured against both published
  taxonomies rather than estimated.
- Ended silent API-contract breakage by generating the React admin's client from the backend's
  OpenAPI document.
- Work to a written process I maintain: a 314-case QA ledger that makes regressions re-runnable,
  and the agent rules published as claude-skills.

### Stack

**Backend** — `NestJS` `TypeScript` `Node.js` `TypeORM` `PHP` `Laravel`
**Frontend** — `React 18` `TypeScript` `Redux Toolkit` `Vite` `Shopify Polaris`
**Data** — `MySQL` `MongoDB` `PostgreSQL + pgvector` `Redis` `BullMQ`
**Platform** — `Docker` `Shopify Admin GraphQL` `SHOPLINE` `Google Merchant Center` `Meta Catalog` `TikTok Catalog`

### Certified

- [Claude Code in Action](https://verify.skilljar.com/c/quhis252443d) — Anthropic Education
- [Introduction to Agent Skills](https://verify.skilljar.com/c/ytamcsc3sxu6) — Anthropic Education
- Developing Apps for Shopify — Shopify Academy

---

**Open to Fullstack Developer roles** · [work.vinh.vn@gmail.com](mailto:work.vinh.vn@gmail.com)
