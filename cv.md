---
layout: cv
title: CV
---

<div style="display: flex; align-items: center; gap: 10px;">
  <h1 style="margin: 0;"><a href="{{ site.baseurl }}/assets/files/Gorshkov_Denis_Fullstack_Developer_CV.pdf" style="color: #74c0fc; text-decoration: none; border-bottom: 2px solid #74c0fc; padding-bottom: 2px;">Curriculum Vitæ (download)</a></h1>
  <a href="{{ site.baseurl }}/assets/files/Gorshkov_Denis_Fullstack_Developer_CV.pdf" download><span class="li-icon">{% include svg/download-square-outline.svg %}</span></a>
</div>

{% include contact.html %}

## Profile

Full-stack engineer with **6+ years** building and scaling production web applications with **Ruby on Rails**, **React** and **Elixir**, currently on a messaging platform handling **~10M messages a month**. Delivers measurable performance and reliability wins (a 257 ms → 0.3 ms query on a 56M-row table, CI twice as fast), **LLM (OpenAI API)** features and security hardening, owning work end to end.

Open to relocation (visa sponsorship required) or remote.

## Skills

* **Backend:** Ruby, Ruby on Rails, Elixir, Phoenix, PostgreSQL, Redis, Sidekiq, RabbitMQ, REST APIs, ActionPolicy
* **Frontend:** React, Redux Toolkit, JavaScript, HTML, CSS, Vite
* **Testing & DevOps:** RSpec, Jest, RuboCop, bundler-audit, Docker, Docker Compose, DroneCI, Git
* **AI:** LLM features with the OpenAI API, prompt and model management, AI-assisted development (Claude Code)

## Employment History

### Full-Stack Engineer, PushSMS
##### _July 2023 - Present_

_Product: [ChatPush](https://chatpush.ru/), a B2B platform connecting WhatsApp, Telegram and SMS messaging to CRMs (YCLIENTS, Bitrix24, amoCRM); ~10M messages a month._

* **Cut a hot query from 257 ms to 0.3 ms** on a **56M+ row PostgreSQL table** by diagnosing it with **EXPLAIN ANALYZE** and adding the right index.
* **Built an AI assistant** on the **OpenAI API** that answers from product data and powers other AI features, e.g. smart notifications that evaluate users' replies; added prompt and model management to the back office.
* **Rebuilt the user account dashboard** as a cached page backed by **Redis** and **Sidekiq** background jobs.
* **Designed and optimised an Elixir backend service** serving **~25,000 users**.
* **Built messaging and CRM integrations**: **WhatsApp Business API**, **Telegram (TDLib)**, YCLIENTS, Avito.
* **Halved CI time (2× faster)** in **DroneCI** with **parallel_tests**, shortening the feedback loop.
* **Remediated a high-severity SSRF vulnerability** in **HTTParty** (CVE-2025-68696) that could leak API keys, detected with **bundler-audit**.
* **Found and fixed a business-critical flaw in SMS rate limiting**, stopping excessive SMS sends and the operational costs they caused.

***

### Professional Development, Self-directed
##### _October 2022 - June 2023_

* Study and open source: [hexlet-cv](https://github.com/hexlet-volunteers/hexlet-cv) (Ruby on Rails, 3 merged PRs), [rusrails](https://github.com/rusrails/rusrails) (Rails Guides in Russian).

***

### Ruby on Rails Developer, Basistech (formerly TIONIX)
##### _January 2021 - October 2022_

* **Integrated the product with virtualisation platforms**, automating management of virtual resources.
* **Improved a third-party platform integration** with pagination and refactoring, making it faster and more reliable.
* **Kept credentials out of logs** by overriding logging in **Sidekiq**, Rails and **HTTParty**.

***

### Ruby Developer, At Consulting
##### _January 2020 - December 2020 (intern until March 2020)_

* **Improved performance** by moving signal processing to asynchronous jobs.
* **Created the project's onboarding documentation and process**, shortening ramp-up for new developers.

***

## Education

### Joint Programme (in progress), SPbPU → WelTec (Wellington, NZ)
##### _2026 - 2028_

* Team project: [Megatron-mk1](https://github.com/Leenday/support_megatron_mk1), an LLM-based support-ticket router (Qwen3 via Ollama, Django).

### Specialist Degree (Master's equivalent), MSUPE
##### _2010 - 2017_

## Certifications

* Meta Front-End Developer Certificate (2026)
* AWS Cloud Technical Essentials (2026)
* LeetCode 500-day streak
