# Hi, I'm Shohan

Senior SQA Engineer in Dhaka, Bangladesh. I test web, SaaS and AI products, and I build the automation that keeps them stable: Playwright + TypeScript end-to-end suites, API and performance tests, and the CI pipelines that run them.

[![Portfolio](https://img.shields.io/badge/Portfolio-shohan--qa.vercel.app-D4F542?style=for-the-badge&labelColor=121410)](https://shohan-qa.vercel.app)
[![CV](https://img.shields.io/badge/CV-Download_PDF-D4F542?style=for-the-badge&labelColor=121410)](https://shohan-qa.vercel.app/Shohanur_Rahman_Shohan_CV.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shohanur-rahman-shohan/)

## What I test

At [weDevs](https://wedevs.com) I test eight products and lead the test automation for Dokan.

| Product | What it is |
| --- | --- |
| [Dokan](https://dokan.co/) | Multi-vendor marketplace platform, with an Android app |
| [CartPilot](https://cartpilot.ai/) | AI shopping assistant (chat and voice) with a SaaS dashboard |
| [TryAura](https://storepulse.co/plugins/tryaura/docs/) | AI virtual try-on for online stores |
| [StoreGrowth](https://storepulse.co/plugins/storegrowth/) | Sales booster: upsells, BOGO offers, countdown timers |
| [FlyCRM](https://flycrm.co/) | CRM with contacts, deal pipelines, quotes and invoices |
| [FlyHR](https://flyhr.co/) | HR management: employee records, leave, attendance and payroll |
| [weDocs](https://wedocs.co/) | Documentation and knowledge base with an AI chatbot |
| [WP ERP](https://wperp.com/) | HR, CRM and accounting suite |

## Dokan end-to-end and API suite

The QA gate for Dokan Lite and Pro, built with Playwright + TypeScript. It runs a real WordPress, WooCommerce and Dokan stack in Docker (`@wordpress/env`), so nobody needs PHP, MySQL or WordPress installed locally.

- About **2,000 end-to-end tests** and **400 REST API tests** (`/dokan/v1`, `/v2`, `/v3`)
- Covers the vendor dashboard (React, 5.0+), the admin React shell, Pro modules and the Lite storefront
- Black-box, folder-isolated design: each feature owns its spec, page object and test data
- Deterministic seeding: setup projects create vendors, customers, products and modules before any test runs
- Tag-based Lite/Pro gating (`@lite`, `@liteOnly`, `@pro`), so fork PRs run cleanly without the Pro repo
- 12 parallel CI shards with one Playwright worker each, which removed the "passes on rerun" flakes
- Login state saved once and reused, and one merged HTML report per run

[Suite source and CI](https://github.com/getdokan/dokan/tree/develop/tests/pw)

## Side projects

Built outside work to show how I structure a suite. Both run their UI and API tests in parallel on GitHub Actions and publish an HTML report.

**[EventHub test suite](https://github.com/shohan0120/event-hub-test-suite)** covers the EventHub app's UI and REST API with page objects, a typed API client with Bearer-token auth, one login reused through `storageState`, Faker test data, and bug reports in `/bugs`.

**[Client Dashboard test suite](https://github.com/shohan0120/client-dashboard-test-suite)** has 65 tests (1 setup, 31 UI, 33 API) for the "Let's Shop" practice app, covering happy, negative and edge cases. Each test traces back to a written case in `TEST-CASES.md`.

## Open source

45 merged pull requests, mostly on Dokan's end-to-end suite and CI. Some highlights:

- [dokan#3387](https://github.com/getdokan/dokan/pull/3387): Tier 1 E2E suite for the Stripe Connect revamp
- [dokan#3294](https://github.com/getdokan/dokan/pull/3294): Stripe Express payment E2E suite
- [dokan#3251](https://github.com/getdokan/dokan/pull/3251): Playwright suite for the redesigned admin dashboard
- [dokan#3225](https://github.com/getdokan/dokan/pull/3225): E2E sharded across 12 CI workers
- [dokan#3451](https://github.com/getdokan/dokan/pull/3451): CI guard that cancels superseded Pro runs
- [wp-erp#1585](https://github.com/wp-erp/wp-erp/pull/1585): Playwright E2E and REST suite that replaced Codeception

[See all merged PRs](https://github.com/search?q=type%3Apr+author%3Ashohan0120+is%3Amerged&type=pullrequests)

## Tools

Playwright · TypeScript · JavaScript · REST APIs · Postman · k6 · JMeter · GitHub Actions · Docker · Appium · Claude Code · Playwright MCP
