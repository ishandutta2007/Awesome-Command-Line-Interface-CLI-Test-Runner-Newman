# Awesome-Command-Line-Interface-CLI-Test-Runner-Newman

## Top Command Line Interface (CLI) Test Runner (Newman) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Automated API Testing, Load Testing & CI/CD Pipeline Execution*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Command Line Interface (CLI) Test Runners**. These tools execute automated tests directly from the terminal—enabling developers and CI/CD pipelines to run API collections, load tests, and end-to-end scenarios without a graphical interface. Covering everything from Postman collection runners to modern HTTP testing DSLs.

**Examples** include Postman CLI, Newman, k6, Artillery, Cypress CLI, Playwright CLI, Tavern, Dredd, Hurl, and HTTPie (the category leaders).

**Open-source emphasis**: This section highlights every major active project for open-source CLI test runners, API testing frameworks, and load testing tools—ideal for developers, QA engineers, and DevOps teams seeking transparent, scriptable testing without per-seat SaaS subscriptions.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting Tier) | Free Tier / Trial Limits |
|---|---|---|---|
| **[Postman CLI](https://www.postman.com/)** | Official CLI for Postman to run collections, monitors, and governance checks directly from CI/CD pipelines. | **$0** (Included with Postman account; paid plans start at **$9/month** Solo or **$19/user/month** Team) | **Free forever plan**: Single user only, unlimited collection runs, 1,000 monitoring requests/month, 50 AI credits/month. No team workspaces on free tier. |
| **[k6 (Grafana Cloud)](https://k6.io/)** | Cloud-managed load testing platform powered by the k6 engine, offering distributed load generation and web dashboards. | Grafana Cloud k6 Pro starts at **$19/month** (includes 500 VU-hours; $0.15/VU-hour overage) | **Free forever plan**: 500 virtual user hours (VUH)/month, max 50 concurrent virtual users (VUs), 1 concurrent test, and 30-day data retention. |
| **[Artillery (Cloud)](https://www.artillery.io/)** | Cloud platform and dashboard for Artillery load testing and Playwright-based end-to-end performance tests. | Team plan starts at **$199/month** (annual discount available; Business at $499/month) | **Free forever plan**: 30 test reports/month, max 2 team members, 5 distributed workers per test, 25 E2E cases per report, 1-month retention. |
| **[Cypress Cloud](https://www.cypress.io/)** | Cloud test orchestration, parallelization, flake detection, and analytics service for Cypress CLI test suites. | Team plan starts at **$67/month** (Business plan starts at **$267/month**) | **Free forever plan (Starter)**: 500 test results/month, max 10 user seats, and 30-day data retention. (14-day free trial available for Smart Orchestration). |
| **[Postman (CLI + Platform)](https://www.postman.com/)** | Full API development and testing platform encompassing CLI runs, API monitors, mock servers, and workspaces. | Solo plan starts at **$9/month** billed annually ($12 billed monthly); Team plan starts at **$19/user/month** | **Free forever plan**: Single user only, unlimited collection runs, 1,000 monitoring requests/month, unlimited mock server calls up to 120k requests/year, 50 AI credits/month. |

## Open-Source GitHub Projects

| Project | Stars_Badge | Description |
|---------|------------|-------------|
| **[Newman](https://github.com/postmanlabs/newman)** | [![Stars](https://img.shields.io/github/stars/postmanlabs/newman?style=social&color=white)](https://github.com/postmanlabs/newman/stargazers) | Command-line collection runner for Postman (Apache-2.0, ~7k stars). Runs Postman collections from the CLI for automated API testing in CI/CD pipelines. The reference implementation for Postman-based CLI testing [citation:2][citation:12]. |
| **[Hurl](https://github.com/Orange-OpenSource/hurl)** | [![Stars](https://img.shields.io/github/stars/Orange-OpenSource/hurl?style=social&color=white)](https://github.com/Orange-OpenSource/hurl/stargazers) | Run and test HTTP requests with plain text (Apache-2.0, ~10.7k stars). Lightweight Rust binary powered by curl. Supports JSONPath, XPath, response assertions, performance testing, and CI integration. Single binary with no runtime required [citation:9][citation:23]. |
| **[Tavern](https://github.com/taverntesting/tavern)** | [![Stars](https://img.shields.io/github/stars/taverntesting/tavern?style=social&color=white)](https://github.com/taverntesting/tavern/stargazers) | Pytest plugin and CLI for automated API testing with YAML syntax (MIT, ~1.1k stars). Supports REST, MQTT, and gRPC. Integrates with pytest ecosystem for fixtures, hooks, and HTML reports [citation:18][citation:27]. |
| **[Dredd](https://github.com/apiaryio/dredd)** | [![Stars](https://img.shields.io/github/stars/apiaryio/dredd?style=social&color=white)](https://github.com/apiaryio/dredd/stargazers) | Language-agnostic HTTP API testing tool (MIT). Validates API implementations against OpenAPI 3.0/3.1/3.2 documents. Maintained fork available via Docker Hub [citation:8][citation:22]. |
| **[HTTPie CLI](https://github.com/httpie/cli)** | [![Stars](https://img.shields.io/github/stars/httpie/cli?style=social&color=white)](https://github.com/httpie/cli/stargazers) | Modern, user-friendly command-line HTTP client. Designed for testing, debugging, and interacting with APIs. Expressive syntax, JSON support, colors, sessions, downloads, and plugins [citation:19][citation:28]. |

### Additional Strong Open-Source Options

| Project | Stars_Badge | Description |
|---------|------------|-------------|
| **[Cypress](https://github.com/cypress-io/cypress)** | [![Stars](https://img.shields.io/github/stars/cypress-io/cypress?style=social&color=white)](https://github.com/cypress-io/cypress/stargazers) | Open-source (MIT) E2E testing framework with CLI. Time-travel debugging, automatic waiting, and network stubbing. Cypress Cloud adds parallelization as a paid service. |
| **[Playwright](https://github.com/microsoft/playwright)** | [![Stars](https://img.shields.io/github/stars/microsoft/playwright?style=social&color=white)](https://github.com/microsoft/playwright/stargazers) | Microsoft's cross-browser automation framework (Apache-2.0) with built-in test runner. CLI supports parallel execution, sharding, retries, and trace viewer. |
| **[Artillery (OSS)](https://github.com/artilleryio/artillery)** | [![Stars](https://img.shields.io/github/stars/artilleryio/artillery?style=social&color=white)](https://github.com/artilleryio/artillery/stargazers) | Open-source load testing CLI (MPL-2.0, ~9k stars). Supports HTTP, WebSocket, Socket.io, gRPC, and Playwright E2E testing. Distributed execution on AWS Lambda/Fargate and Azure ACI [citation:17][citation:26]. |

**Frameworks for building custom systems**: Combine **Newman** for Postman collection execution, **Hurl** for plain-text HTTP testing, **Tavern** for YAML-driven API tests with pytest, and **Dredd** for OpenAPI contract validation—creating a fully open-source CLI testing stack for CI/CD pipelines.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- CLI test runners execute HTTP requests and can potentially affect production systems if misconfigured; use environment-specific base URLs, secrets management, and test data isolation.
- Postman's free tier changes (March 2026) removed team collaboration entirely—existing teams on the free plan may need to migrate to Newman (open-source) or alternative platforms [citation:1]. k6 and Artillery pricing varies significantly between self-hosted CLI and managed cloud execution; model total cost against actual test volume before committing.

---

**Made for QA engineers, developers, DevOps teams, and organizations building automated testing pipelines.**  
Let's make CLI test runners more open, scriptable, and CI-friendly.
