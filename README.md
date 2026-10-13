# Hi, I'm Trenton

I'm a student at Cornell focused on backend and fintech software engineering. I like systems where correctness is the whole point: money should never be created or lost by a bug, a retried request should never charge someone twice, and every number should be explainable after the fact.

The projects below are built from first principles, each with tests, CI, and a walkthrough explaining the design decisions and trade-offs.

## What I'm building

- **Payments and ledgers:** double-entry accounting, idempotent APIs, exact money arithmetic
- **Trading systems:** order books, price-time priority matching, low-latency data structures
- **Risk and security:** fraud scoring, authentication, rate limiting
- **Search and data:** indexing, ranking, and APIs over financial data

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

## Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/TrentonBankstheCoder12/ledger-service">ledger-service</a></h3>
      <p>Double-entry ledger REST API with idempotency keys, integer money math and overdraft protection.</p>
      <sub>Python · FastAPI · PostgreSQL · Docker</sub>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/TrentonBankstheCoder12/matching-engine">matching-engine</a></h3>
      <p>Limit order book and matching engine with price-time priority, partial fills and cancels.</p>
      <sub>TypeScript · Node.js</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/TrentonBankstheCoder12/fraud-detector">fraud-detector</a></h3>
      <p>Explainable transaction risk scoring: velocity, amount-spike and impossible-travel rules plus a streaming statistical anomaly score, with an evaluation harness.</p>
      <sub>Python · FastAPI</sub>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/TrentonBankstheCoder12/auth-service">auth-service</a></h3>
      <p>Authentication API with Argon2 password hashing, JWT access tokens, refresh token rotation, TOTP 2FA and rate limiting.</p>
      <sub>TypeScript · Node.js · Express</sub>
    </td>
  </tr>
</table>

## Also built

- **[portfolio-tracker-cli](https://github.com/TrentonBankstheCoder12/portfolio-tracker-cli)**: CLI for holdings, FIFO cost basis, and realized/unrealized P&L from a trade log
- **[budget-dashboard](https://github.com/TrentonBankstheCoder12/budget-dashboard)**: React + TypeScript personal finance dashboard with CSV import, auto-categorization and budget tracking
- **[url-shortener](https://github.com/TrentonBankstheCoder12/url-shortener)**: FastAPI shortener with base62 codes, expiry, click analytics, LRU caching and rate limiting
- **[realtime-chat](https://github.com/TrentonBankstheCoder12/realtime-chat)**: WebSocket chat server with rooms, presence, typing indicators and per-connection rate limiting
- **[search-engine](https://github.com/TrentonBankstheCoder12/search-engine)**: full-text search from scratch with BM25 ranking, boolean and phrase queries
- **[task-board](https://github.com/TrentonBankstheCoder12/task-board)**: React Kanban board with accessible drag-and-drop, filters and undo/redo

## GitHub stats

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=TrentonBankstheCoder12&show_icons=true&hide_border=true&bg_color=00000000&title_color=2f80ed&icon_color=2f80ed&text_color=7d8590" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TrentonBankstheCoder12&layout=compact&hide_border=true&bg_color=00000000&title_color=2f80ed&text_color=7d8590" alt="Top languages" />
</p>

## Get in touch

The best way to reach me is through [GitHub](https://github.com/TrentonBankstheCoder12). Issues and pull requests on any of these projects are welcome.
