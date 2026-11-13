<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1d2a,45:143d59,100:1f8a9e&height=210&section=header&text=Jack%20Wang&fontSize=64&fontColor=f4f7fa&fontAlignY=38&desc=Data%20Science%20%C3%97%20Economics-Accounting%20%C2%B7%20Claremont%20McKenna%20College%20'27&descSize=18&descAlignY=58&descColor=cfe6ee&animation=fadeIn" width="100%" alt="Jack Wang. Data Science and Economics-Accounting, Claremont McKenna College, class of 2027" />

<a href="https://github.com/jack-zhengyangwang"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&duration=3400&pause=1000&color=1F8A9E&center=true&vCenter=true&width=640&lines=I+build+research+systems+for+markets.;I+test+the+idea+before+I+trust+it.;Negative+results+get+written+up+too.;Graduating+May+2027+%C2%B7+open+to+full-time+analyst+and+quant+roles" alt="I build research systems for markets. I test the idea before I trust it. Negative results get written up too. Graduating May 2027, open to full-time analyst and quant roles." /></a>

<br/>

<a href="mailto:jackzhengyangwang0424@gmail.com"><img src="https://img.shields.io/badge/Email-jackzhengyangwang0424%40gmail.com-1f8a9e?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://www.linkedin.com/in/zhengyangwang0424/"><img src="https://img.shields.io/badge/LinkedIn-zhengyangwang0424-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn: zhengyangwang0424" /></a>
<a href="https://github.com/jack-zhengyangwang?tab=followers"><img src="https://img.shields.io/github/followers/jack-zhengyangwang?style=for-the-badge&logo=github&color=0b1d2a&labelColor=0b1d2a" alt="GitHub followers" /></a>

</div>

<br/>

I'm a senior at Claremont McKenna College with a dual major in Data Science and Economics-Accounting. Most of what I build sits where statistics meets a live market: pricing models, position sizing, and the testing harness that decides whether any of it deserves real money. I write up the results either way. Two of my larger projects ended with a clear "no edge here," and I think those reports are the most useful things in this profile.

<br/>

## Projects

### [kalshi-trading](https://github.com/jack-zhengyangwang/kalshi-trading) &nbsp;<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/v2.0.0-research%20report-1f8a9e?style=flat-square" alt="v2.0.0 research report" />

An autonomous research and trading system for soccer markets on Kalshi, a CFTC-regulated prediction market. It discovers every open market live, prices each contract with Poisson and negative-binomial models plus an optional LLM layer, sizes bets with capped Kelly, and evolves a population of strategy agents in a reproducible paper-trading arena. Over 3,500 settled paper bets and two written reports.

<div align="center">
<a href="https://github.com/jack-zhengyangwang/kalshi-trading/blob/main/docs/REPORT_v1.0.md"><img src="https://raw.githubusercontent.com/jack-zhengyangwang/kalshi-trading/main/docs/findings/img/01_calibration.png" width="640" alt="Calibration chart: Kalshi prices track realized win rates almost exactly" /></a>
<br/><sub>Kalshi's prices are the probabilities. Realized win rate vs. contract price across 3,582 settled bets.</sub>
</div>

<details>
<summary><b>What the two reports found</b></summary>
<br/>

| Report | Question | Answer |
|---|---|---|
| [v1.0](https://github.com/jack-zhengyangwang/kalshi-trading/blob/main/docs/REPORT_v1.0.md) | Can trading mechanics beat Kalshi? | No. Every desk lost money, AI-managed and rule-based alike. Prices move about 1.5¢ before kickoff and a taker round trip costs about 5.5¢. 0 of 4 pre-registered rule tests passed. |
| [v2.0](https://github.com/jack-zhengyangwang/kalshi-trading/blob/main/docs/REPORT_v2.0.md) | Can a public-data model beat the price? | No. 0 of 4 models beat Pinnacle or Kalshi on Brier score, 0 of 12 league-tier × entry-time groups passed. Public data is already in the price. |

Left open: profit on selected bets, non-public information, other market types.

</details>

<br/>

### [soccer-quant](https://github.com/jack-zhengyangwang/soccer-quant) &nbsp;<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="scikit-learn" /> <img src="https://img.shields.io/badge/LLM-Claude-d97757?style=flat-square" alt="Claude" />

Dual-model match prediction for the Premier League and Champions League. A machine-learning model trained on match history, xG, form, and squad rotation produces outcome and totals probabilities. A separate LLM pass reads injury news, lineups, and manager changes for context the numbers miss. The two are combined into one prediction with the evidence shown next to it.

### [CSCI146Project](https://github.com/jack-zhengyangwang/CSCI146Project) &nbsp;<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/Data%20Mining-final%20project-1f8a9e?style=flat-square" alt="Data mining final project" />

Machine-learning model predicting Valorant round outcomes from in-game state, built as the final project for a data mining course.

### Private, happy to talk about

- An AI stock research advisor on Alpaca paper trading, with a 600-test suite and a sector-momentum baseline.
- A personal life dashboard pulling calendar, messages, and trading accounts into one page.
- A Chrome extension for Kanban task management with Claude built in.

<br/>

## Research and teaching

| Where | What |
|---|---|
| **Senior thesis** | Covariance shrinkage for portfolio construction: SURE-tuned Ledoit-Wolf style estimators, compared on out-of-sample risk. |
| **Research Assistant, Prof. Evan Rosenman (CMC)** | Derived joint moment generating functions and ran simulation studies in R comparing expected against empirical risk. |
| **Nordic Seafarm** | Project data analyst on a semester-long client engagement through a CMC course. |
| **Robert Day School of Economics and Finance** | Student teaching assistant for Game Theory, Statistics, Accounting, and Economics. |

<br/>

## Toolbox

<div align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" alt="R" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
<img src="https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white" alt="LaTeX" />
<img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash" />

<img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas" />
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="scikit-learn" />
<img src="https://img.shields.io/badge/statsmodels-1f8a9e?style=for-the-badge" alt="statsmodels" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />

<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
<img src="https://img.shields.io/badge/DigitalOcean-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white" alt="DigitalOcean" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
<img src="https://img.shields.io/badge/Claude%20API-d97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude API" />

<sub>Also: Kelly sizing · Poisson / negative-binomial pricing · genetic algorithms · walk-forward backtests · cron-driven pipelines · Telegram bots</sub>

</div>

<br/>

## Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jack-zhengyangwang/jack-zhengyangwang/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jack-zhengyangwang/jack-zhengyangwang/output/github-snake.svg" />
  <img src="https://raw.githubusercontent.com/jack-zhengyangwang/jack-zhengyangwang/output/github-snake.svg" width="100%" alt="Snake animation eating my contribution graph" />
</picture>

<br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=jack-zhengyangwang&theme=tokyonight&animation=load" height="165" alt="GitHub stats" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=jack-zhengyangwang&theme=tokyonight&animation=load" height="165" alt="Most committed languages" />
<img src="https://streak-stats.demolab.com?user=jack-zhengyangwang&theme=tokyonight&hide_border=true&background=0b1d2a&ring=1f8a9e&fire=1f8a9e&currStreakLabel=1f8a9e" height="165" alt="Contribution streak" />

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f8a9e,55:143d59,100:0b1d2a&height=110&section=footer" width="100%" alt="" />
