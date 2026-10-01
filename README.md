# Matheus Pacífico

Full-stack software engineer building production systems for Brazil's public sector, and founder of an early-stage B2B SaaS.
Most of my work lives in private repositories. The contribution graph below counts it, and this page describes it.

- 🏛️ Building a strategic-management platform for Brazil's **Ministry of Health** at **PACTO**
- 🚀 Founder of a **B2B legal-tech SaaS** in stealth, launching soon
- 🎓 Systems Analysis and Development at **IFSP** (Federal Institute of São Paulo)
- 📈 4,000+ commits in 2026 across work, freelance, open source and my own product

---

## 🔨 What I'm building

### Federal platform, Ministry of Health · PACTO · `private`
A strategic-management platform used across the ministry to plan and monitor its strategic items.
I led its architecture redesign and the migration from a NoSQL backend to a relational PostgreSQL model,
and built the new Next.js + TypeScript frontend. LGPD-compliant, with versioned migrations and end-to-end tests.

`TypeScript` `Next.js` `PostgreSQL`

### White-label public-sector SaaS · PACTO · `private`
A generic version of the same platform model for other Brazilian public agencies, with its own design system (tokens + React component library).

`TypeScript` `Next.js` `PostgreSQL` `React`

### Legal-tech B2B SaaS · Founder · `stealth`
A product for Brazilian law firms that I'm building from zero with a lawyer co-founder: **Go** API, **SvelteKit** frontend, and **PostgreSQL** with tenant isolation enforced by RLS, plus background jobs and a self-hosted deploy.

`Go` `SvelteKit` `PostgreSQL` `Redis` `Docker`

### Viva · Freelance · `private`
Backend for a mobile app for discovering cultural events and tourist attractions in Brazilian cities. I own the full backend architecture: JWT with refresh-token rotation, Google/Facebook OAuth2, RBAC, rate limiting (Bucket4j), S3 storage, and Flyway migrations.

`Java 25` `Spring Boot 3` `Spring Security` `PostgreSQL` `AWS S3`

---

## 🌱 Open source

### [rlsspec](https://github.com/matheusspacifico/rlsspec) [![release](https://img.shields.io/github/v/release/matheusspacifico/rlsspec?style=flat-square&label=)](https://github.com/matheusspacifico/rlsspec/releases/latest)
A Rust CLI that tests Postgres Row Level Security against a declared spec of who should see what.
It reports leaked and hidden rows, builds a coverage matrix, lints for common RLS mistakes, and fails CI on regressions.
Ships as a single binary via Homebrew, crates.io, Docker and a GitHub Action.

```sh
brew install matheusspacifico/tap/rlsspec   # or: cargo install rlsspec --locked
```

`Rust` `PostgreSQL`

### Contributions

| Project | What | My part |
|---|---|---|
| [**pet-ads/systematic**](https://github.com/pet-ads/systematic) | Backend for **StArt**, an academic tool for systematic literature reviews (UFSCar / IFSP) | **3rd-largest contributor, ~375 commits**. Kotlin + Spring Boot, DDD and Clean Architecture, JUnit 5 |
| [**ax-comp-scl/Group-Website**](https://github.com/ax-comp-scl/Group-Website) | Web platform for an **Embrapa** research group | Django + React |

## 🧪 Selected side projects

- [**gmail-audit**](https://github.com/matheusspacifico/gmail-audit): scans a whole Gmail mailbox over IMAP, groups mail by sender, and bulk-unsubscribes from newsletters · `Python`
- [**coop-crossword**](https://github.com/matheusspacifico/coop-crossword): real-time co-op crossword for two players · `Svelte`
- [**aura-movies-tdd**](https://github.com/GuilhermeAMendes/aura-movies-tdd): movie ratings and recommendations built with DDD, TDD and BDD · `Java`
- [**software-testing-studies**](https://github.com/matheusspacifico/software-testing-studies): modern Java testing practices · `Java`
- [**pvz-replanted-ahk-script**](https://github.com/matheusspacifico/pvz-replanted-ahk-script): keyboard hotkeys for *Plants vs. Zombies: Replanted*, **later added to the official game** 🌻 · `AutoHotkey`

---

## 🛠️ Stack

![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Svelte](https://img.shields.io/badge/svelte-%23f1413d.svg?style=for-the-badge&logo=svelte&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

## 📫 Find me

<a href="https://linkedin.com/in/matheusspacifico" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="matheusspacifico" height="30" width="40" /></a>
