# Hey There 👋

---

<div align="center">

### ⭐ 🎭 Dokan E2E & API Automation Suite — Highlights ⭐

</div>

**Highlights of my work:**

- 🧱 **Black-box, folder-isolated architecture** — each feature owns its spec, page object, and test data, with no cross-folder imports.
- 🌱 **Deterministic seeding** — vendors, customers, products, and modules are provisioned by setup projects before the test phase runs.
- 🏷️ **Tag-driven Lite/Pro gating** (`@lite`, `@liteOnly`, `@pro`) so the suite runs cleanly on fork PRs without the Pro repository.
- ⚡ **CI sharding & reporting** — 6-way parallelization plus storage-state authentication to eliminate per-test login cost.
- 🐛 **Flake hunting at the source** — auto-dismiss handlers for the Pro 5.0 announcement modal and robust REST-auth patterns.

🔗 **[Dokan Automation Suite Github Actions CI/CD →](https://github.com/getdokan/dokan/tree/develop/tests/pw)**

---

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shohanur-rahman-shohan/)

I am **SHOHAN**, a Software Quality Assurance Engineer and automation tester from Bangladesh. I work at [**weDevs**](https://wedevs.com) on the **Dokan multi-vendor marketplace** ecosystem, the **StorePulse** product suite, and **WP ERP** — tools powering thousands of WooCommerce and WordPress sites. I focus on end-to-end automation, CI test infrastructure, and performance testing. Day-to-day I write Playwright suites, harden GitHub Actions pipelines, and track down test flakiness at the source.

Want to know more about me? [**Connect with me on LinkedIn.**](https://www.linkedin.com/in/shohanur-rahman-shohan/)

- 🏢 Currently working as an **SQA Engineer & Automation Tester at weDevs**
- 🧪 Focusing on **Playwright (TypeScript), REST API testing, and CI sharding & reporting**
- 🤖 Exploring **AI-assisted QA workflows and performance testing**
- 📍 Based in **Bangladesh**
- 🧩 **Products I work on:**
- 🛒 **Dokan** — Multivendor plugin, Umbrella plugins & Mobile App
- 💼 **WP ERP**
- 📈 **StorePulse** — StoreGrowth, CartPulse, Conversion Tracking for WC & Texty

## Find me on Social Platforms

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shohanur-rahman-shohan/)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shohan0120)

## What I Work On

| Area | Recent work |
| --- | --- |
| **E2E Automation** | Refactoring Dokan's Playwright suite for stability and reliable CI reporting |
| **CI Hardening** | Improving GitHub Actions pipelines — caching, sharding, and quality reports |
| **Performance** | Load and performance testing for marketplace flows |
| **Internal Tooling** | Tooling to streamline QA workflows and debugging |

**Active contributor in [getdokan](https://github.com/getdokan) and [wp-erp](https://github.com/wp-erp)** — opening and merging pull requests and filing detailed, reproducible issues, mostly around E2E stability, CI infrastructure, and regression coverage. Recently had my end-to-end test suite merged into **wp-erp**.

## 🎭 Dokan E2E & API Automation Suite

A flagship project I work on: the official QA gate for **Dokan Lite & Pro**, built on **Playwright + TypeScript**. It drives a real WordPress + WooCommerce + Dokan stack inside Docker (`@wordpress/env`) — no local PHP, MySQL, or WordPress install required.

| Metric | Detail |
| --- | --- |
| **~2,000+** | end-to-end tests |
| **~400** | REST API tests (`/dokan/v1`, `/v2`, `/v3`) |
| **Surfaces** | Vendor dashboard (React 5.0+), Admin React shell, Pro modules, Lite storefront |
| **CI** | 6 parallel shards with merged HTML reporting via GitHub Actions |

## 🎟️ EventHub — Playwright E2E + API Automation Suite

A personal showcase project: a production-style automation suite for the **EventHub** application, covering both the **browser (E2E)** and the **REST API** layers with **Playwright + TypeScript**. **GitHub Actions CI/CD integrated** — UI and API suites run in parallel and publish the HTML report as an artifact.

- 🧩 **Two layers, one suite** — UI journeys and API contract/validation tests share types, data, and config.
- 🏗️ **Page Object Model** — every page is a class; specs read like English, with zero raw selectors.
- 🔌 **Typed API client** — a fully-typed wrapper over Playwright's `APIRequestContext` with Bearer-token handling.
- 🔐 **Authenticate once** — a setup project logs in and saves `storageState`; all UI specs reuse it.
- 🎭 **Playwright best practices** — web-first auto-retrying assertions, role/`data-testid` locators, no hard waits, traces on failure.
- 🌱 **Realistic, parallel-safe data** — `@faker-js/faker` generators produce unique data per test.
- 🐞 **Bugs documented** — defects found during exploration are filed as GitHub-issue-style reports in `/bugs`.

🔗 **[EventHub Automation Suite Github Actions CI/CD →](https://github.com/shohan0120/event-hub-test-suite)**

## 🏆 Achievements

- ✅ Merged pull requests into the **getdokan/dokan**, **wp-erp** codebase, including CI reliability fixes
- 🧪 Built and maintained automated end-to-end test coverage for a production WooCommerce plugin
- 🐛 Filed detailed, reproducible bug reports and test-case checklists used by the team
- 🔧 Improved CI pipeline stability and reporting for a multi-vendor e-commerce platform

## 🚧 In Progress

- **CartPilot** — a project I'm currently building (details coming soon)

## ✅ Merged Pull Requests

**[👉 View all my merged pull requests](https://github.com/search?q=type%3Apr+author%3Ashohan0120+is%3Amerged&type=pullrequests)**

## Tech Stack

**Languages**
