<div align="center">

# Rohan Joglekar

**Financial Technology at NJIT · Albert Dorman Honors College · Full-Ride Merit Scholar**

[![Résumé (PDF)](https://img.shields.io/badge/Résumé-download_PDF-b91c1c?style=flat-square&logo=adobeacrobatreader&logoColor=white)](https://github.com/rohanjoglekar/rohanjoglekar/blob/main/Rohan_Joglekar_Resume.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rohan-joglekar)
[![Email](https://img.shields.io/badge/Email-rohannj29@gmail.com-334155?style=flat-square&logo=gmail&logoColor=white)](mailto:rohannj29@gmail.com)

</div>

I build and operate AI-driven research and trading systems end to end: the research, the valuation models, the execution, and the infrastructure that runs them.

---

## Agentic Research & Trading Platform

`Python` · `FastAPI` · `Next.js` · `Claude API` — [GitHub](https://github.com/rohanjoglekar/agentic-research-trading-platform) · [Live demo](https://agentic-research-trading.vercel.app/demo)

- **Architecture.** Engineered the platform on a Linux server with a FastAPI backend, a Next.js dashboard, and systemd timers that run every job. AI agents (Claude, Gemini, and local Ollama models) handle research, valuation, and trade management.
- **Research and DCF.** Built a research engine that grades about 600 companies daily, including a weekly Claude read of each business. Alongside it, an agentic DCF pipeline has Claude create bear, base, and bull cases from SEC filings into full Excel valuation models that are automatically checked before publishing.
- **Equity trader.** Ran a $1M paper stock portfolio that trades automatically from that research. An AI agent reviews performance against the S&P 500 each month and adjusts the strategy's settings within fixed limits.
- **Options trader.** Ran an automated options strategy that sells cash-secured puts on a $100K paper account three times a day and rates every trade. An AI agent researches positions that turn against it and decides whether to hold, close, or roll them, with about a 75% win rate.

## Concordia — Investment Club

`Python` · `FastAPI` · `SQLite` · `Next.js` · `Claude API` — [GitHub](https://github.com/rohanjoglekar/voteconcordia) · [Live demo](https://demo.voteconcordia.com)

- **Architecture.** Built the platform on FastAPI, SQLite, and Next.js to execute one vote-chosen portfolio inside each member's own Robinhood account through encrypted OAuth, so capital is never pooled or held by the club. Scheduled jobs run voting, settlement-aware trading, and reconciliation against broker records, covered by more than 900 backend tests.
- **Idea.** Founded the club on the wisdom of crowds. Members split their votes across S&P 500 stocks each week, the top 20 form the basket, and voting power scales 0.5× to 2× with each member's excess return over the S&P 500. The club's paper decisions index is up 5.6% against the S&P 500's −6.9% across 52 sessions since June 2026.
- **New voting rule, running in shadow.** Designed a rule that scores each ballot against the crowd and moves a member's power only once their record clears a two-standard-error luck dead zone. In a 2007–26 simulation of 100 strategy-driven members, it cost nothing when no one had skill, yet gave a planted star member 28% of the power (vs. 1.5% under the live rule).
- **100 Claude bots.** Added 100 Claude-powered AI voting members, each a distinct strategy that votes on every S&P 500 stock weekly with a written thesis but holds no account and places no orders. Their ballots average a 0.03 correlation, so they act as about 24 independent voters.

---

## Skills

**Technical:** Python (pandas, NumPy, scikit-learn), Java, Pine Script, Excel · Machine Learning · AI Agents · DCF Modeling · Equity & Options Pricing · Options Greeks · Portfolio Construction · Risk Management · Backtesting

**Tools:** Linux · systemd · Git · GitHub Actions · FastAPI · Next.js · SQLite · Ollama · Claude API · Claude Code

## Education

**New Jersey Institute of Technology** — B.S. Financial Technology · *Expected May 2028*
Albert Dorman Honors College · Dean's Scholar · Full-Ride Merit Scholarship · GPA 3.8

---

**Contact:** [rohannj29@gmail.com](mailto:rohannj29@gmail.com)
