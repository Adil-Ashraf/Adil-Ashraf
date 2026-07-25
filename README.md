# Adil Ashraf

**Full-stack engineer. Six years shipping production software — deepest in Ruby on Rails,
but that's where I started, not where I stopped.**

I've built products from an empty directory and joined codebases that were already years old
and full of decisions somebody made for reasons nobody wrote down. The second one is harder,
and I've come to prefer it. You learn a system properly when you have to change it without
breaking it.

These days a typical piece of work for me spans a Rails or FastAPI backend, a React or
Next.js frontend, an LLM somewhere in the middle, and whichever cloud the team is already
paying for. I'd rather own a feature end to end than hand over a JSON payload and hope.

## Working with

- **Backend** — Ruby on Rails, Node.js, FastAPI, Python
- **Frontend** — React, React Native, Next.js, JavaScript
- **Data & caching** — PostgreSQL, Redis, vector databases
- **AI** — multiple LLM APIs, retrieval-augmented generation, LangChain
- **Infra** — AWS, Heroku, DigitalOcean, Docker, GitHub Actions

## What the work has actually looked like

**Caching, and the invalidation problem underneath it.** Read-heavy apps where the query is
cheap right up until it isn't. Working out what's allowed to go stale, what absolutely isn't,
and what has to expire the moment a related record changes.

**Third-party APIs.** Pulling data from external services and making it behave — rate limits,
partial failures, responses that change shape without warning, and retries that back off
instead of hammering someone's endpoint at 3am.

**LLMs in real products.** Integrating several different model APIs into working systems,
including React frontends, rather than building demos. Retrieval over a customer's own data
so the answers are grounded in their documents instead of the model's imagination.

**Custom integrations.** Features that talk to the tools teams already live in — Slack among
them — so the workflow happens where people already are, not in another dashboard nobody opens.

**Tests that earn their keep.** I've worked test-first on production codebases and I'm
comfortable being the person who says the suite has to pass before it ships.

## Selected projects

**Racing TV** — Horse racing broadcaster and subscription streaming platform for the UK and
Ireland. Backend development, plus frontend work across React and React Native.

**Nearcut** — Booking platform used by barbershops to run their scheduling and their business.
Full-stack Rails, front and back, built with test-driven development.

**UWCM** — Platform for a charity distributing financial assistance to people who had lost
their income through circumstances outside their control.

**Devbox AI** — AI system that answers questions against a user's own custom data, with a
React frontend over a retrieval-backed API.

**Codexa** — [one line: what it does and what you built]

## Open source

**[vector_vault_ai](https://github.com/Adil-Ashraf/vector_vault_ai)**
Rails API for retrieval-augmented Q&A. OpenAI embeddings, Postgres with pgvector,
nearest-neighbour retrieval before the model answers. Dockerised, with CI that runs the suite
and ships an image to GHCR when it's green.

**[rails_multitenant_starter](https://github.com/Adil-Ashraf/rails_multitenant_starter)**
Rails 8 baseline for multi-tenant SaaS. Tenant scoping fails closed, so a forgotten `where`
raises instead of quietly serving one customer's data to another. Roles, security scanning,
written security policy.

## Get in touch

Open to full-stack, backend, and frontend work. I don't have a religious attachment to any
particular stack — if a team is using something I haven't touched yet, I'd rather learn it
properly than argue for the thing I already know.

- LinkedIn — [linkedin.com/in/your-handle](https://www.linkedin.com/in/adil-ashraf-5b5b581a9/)
- Email — your.adilashraf4959@gmail.com

<!--
**Adil-Ashraf/Adil-Ashraf** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
