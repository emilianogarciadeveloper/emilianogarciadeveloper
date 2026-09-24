<!--
  Profile README — Emiliano Garcia
  Maintenance rules:
  - Name is always "Emiliano Garcia" (no accent). No personal aliases or brand names.
  - Only list repositories under "Selected engineering work" once they are public and documented.
  - No stats cards, typing animations or decorative badges.
-->

![](./banner.svg)

# Emiliano Garcia

Senior Full Stack Developer working on production web systems: building new ones, and improving the ones teams already depend on.

I work mainly with PHP, Laravel, React and WordPress/WooCommerce, with a particular focus on accessibility and web performance. For more than 8 years I've worked with clients and agencies in the US, Spain, Canada and Australia, remotely from Argentina.

[LinkedIn](https://www.linkedin.com/in/emilianogarciadeveloper/)

## What I work on

- **Full stack applications.** Laravel back ends (REST APIs, authentication, roles and permissions, jobs and queues, integrations) with React front ends built on Vite.
- **WordPress and WooCommerce engineering.** Custom themes and plugins in PHP, custom blocks, admin functionality, payment integrations, migrations and long-term maintenance. No page builders.
- **Accessibility.** WCAG 2.1 and 2.2 AA audits and remediation in existing codebases: keyboard and screen-reader testing, focus management, semantic markup, accessible forms, dialogs and navigation.
- **Web performance.** Core Web Vitals (LCP, INP, CLS) diagnosed across the whole request, from front-end assets and third-party scripts to PHP, MySQL, caching, Nginx/PHP-FPM and the CDN.
- **APIs and integrations.** REST APIs, webhooks, third-party services and data moving reliably between systems.
- **AI and automation.** Retrieval-augmented generation, tool calling, structured outputs and workflow automation, treated as engineering work: retrieval quality, guardrails, logging and evaluation.

## How I work

Production-minded engineering, where performance, accessibility, reliability and maintainability are considered together from the start instead of being added at the end. In practice:

- I read an existing system before changing it, and work within its conventions.
- Changes ship in small, reviewable increments through Git, staging and QA.
- Tests go where they protect behaviour that matters.
- Decisions and trade-offs are documented so the next developer can pick up the work.
- I watch what happens after a release, not only at merge time.

## Accessibility and performance

Since 2021 I've audited or remediated more than 500 sites for accessibility, first against WCAG 2.1 AA and, since its publication, WCAG 2.2 AA.

The work is done against live code. Automated scans with axe and Pa11y surface candidate issues; manual testing confirms what actually fails: keyboard-only navigation, focus order and visibility, screen readers, zoom and reflow, forms and error messages, landmarks, tables and dialogs. Each issue reaches developers with the affected element, the success criterion and a concrete fix, and is retested after the change. Fixes go into the markup and components, not into overlay widgets.

Performance work follows the same loop: measure with field and lab data, find the real bottleneck, fix it at the source, and measure again.

## Public and private work

Most of my client and agency work lives in private GitHub and Bitbucket repositories. The public repositories here show the same engineering practices in reusable or sanitized form.

<!--
  Uncomment each entry only when the repository is public, documented and tested.

## Selected engineering work

**[WCAG Remediation Toolkit](https://github.com/emilianogarciadeveloper/wcag-remediation-toolkit)**
Manual accessibility QA workflows, WCAG 2.2 AA checklists and accessible component patterns, including WordPress and WooCommerce notes.
Markdown · HTML · JavaScript · axe

**[Laravel + React reference](https://github.com/emilianogarciadeveloper/REPO_NAME)**
Production-oriented API and front-end architecture with auth, validation, service layer, tests and CI.
PHP · Laravel · React · Vite · Pest · GitHub Actions

**[Web Performance Playbook](https://github.com/emilianogarciadeveloper/web-performance-playbook)**
Measurement-driven Core Web Vitals diagnostics and remediation workflows for PHP and WordPress stacks.

**[WP Production Starter](https://github.com/emilianogarciadeveloper/wp-production-starter)**
Custom WordPress theme architecture with a modern build pipeline, CPTs, ACF, accessibility and performance defaults.

**[LUMEN GENESIS](https://github.com/emilianogarciadeveloper/REPO_NAME)**
Simulation platform with retrieval over pgvector, multi-world state and an observability dashboard.
Python · FastAPI · PostgreSQL · pgvector · Redis · Godot
-->

## Stack

**Core:** PHP, Laravel, JavaScript, React, Vite, Node.js, WordPress, WooCommerce

**Front end:** HTML, CSS/SCSS, Bootstrap, responsive layouts, jQuery in legacy systems

**Data and APIs:** MySQL, REST APIs, webhooks, third-party integrations

**Infrastructure:** Linux, Nginx, PHP-FPM, VPS, Cloudflare, DNS and SSL, cPanel/WHM, Git

**Accessibility and performance:** WCAG 2.1/2.2, axe, Pa11y, screen readers, Lighthouse, Core Web Vitals

**AI and automation:** RAG, embeddings and vector search, tool calling, structured outputs, OpenAI and Anthropic APIs, Python/FastAPI for AI services

## Working with agencies and teams

A large part of my work is white-label, inside an agency's own process: their tickets, repositories, staging environments and release schedule. Client confidentiality is the default. I'm comfortable taking over existing codebases, working on retainers, and leaving documentation and a clean handoff behind.

## Contact

Available for senior development contracts, agency collaboration, accessibility remediation, full stack projects and technical consulting.

- LinkedIn: [linkedin.com/in/emilianogarciadeveloper](https://www.linkedin.com/in/emilianogarciadeveloper/)
