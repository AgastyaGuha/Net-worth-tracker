# Net-worth-tracker
![Terminal Preview](https://img.shields.io/badge/UI-Dark_Mode-0B0F19?style=flat-square)
![React](https://img.shields.io/badge/React-18.2.0-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-3.0-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-2.1-FF69B4?style=flat-square)

A high-performance, purely client-side quantitative wealth tracking terminal. Designed with the aesthetics and functional density of an institutional trading dashboard, this tool aggregates assets and liabilities to provide real-time analytics on Net Asset Value (NAV), leverage ratios, and capital allocation.

 Motivation

As an Artificial Intelligence engineering student with a strong focus on algorithmic trading and financial analysis, I wanted a personal finance tool that moved beyond basic budgeting. I built this terminal to apply quantitative risk metrics (like Gross Exposure and Leverage Ratios) to personal wealth management. 

The architecture is deliberately designed as a **State-Driven Single-Page Application (SPA)** that runs entirely in the browser. By sandboxing the data in local memory rather than routing it through a backend database, it guarantees absolute zero-latency updates and 100% data privacy.

Core Features

* **Real-Time NAV Calculation:** Instantly computes Net Asset Value and Gross Exposure as new ledger items are executed.
* **Global Currency Engine:** Native `Intl.NumberFormat` integration allows seamless switching between USD, EUR, GBP, INR, JPY, and more, instantly recalculating all metrics and chart axes.
* **Risk Management Radar:** Live monitoring of Debt-to-Asset leverage ratios to flag elevated liquidity risks.
* **Interactive Data Visualization:**
  * **NAV Trajectory:** 12-month historical area chart tracking portfolio momentum.
  * **Asset Allocation:** Dynamic pie chart reflecting Modern Portfolio Theory (MPT) class distribution.
  * **Cash Flow Velocity:** Inflow vs. Outflow bar charts to track capital burn rates.
* **Bulletproof Architecture:** Utilizes Cloudflare's Enterprise CDN (`cdnjs`) for guaranteed script stability and cross-origin compliance.

Technology Stack

This project was engineered to be entirely dependency-free at the local level. It requires no `npm install`, no build steps, and no backend server.

* **Core Logic:** React (v18) & ReactDOM
* **Styling:** Tailwind CSS (via CDN configuration)
* **Visualization:** Recharts (D3.js wrapper)
* **Compilation:** Babel Standalone (In-browser JSX transformation)
* **Icons:** Hardcoded SVGs (Zero external script reliance for assets)


Agastya Tushar Guha

B.Tech in Artificial Intelligence

[LinkedIn]https://www.linkedin.com/in/agastya-guha-2376803a4?utm_source=share_via&utm_content=profile&utm_medium=member_android
