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

- Engineered the platform on a Linux server with a Python and FastAPI backend, a Next.js dashboard, and systemd timers that run every job automatically. AI agents (Claude, Gemini, and local Ollama models) handle research, valuation, and trade management; rule-based code makes every decision to open a position.
- Built an agentic DCF engine: Claude drafts bear, base, and bull assumptions from SEC XBRL filings, and Python builds a 10-year Excel model with 5×5 sensitivity grids. LibreOffice recalculates every workbook against integrity checks before it is published. Nearly 170 models are live, and moving to the Batch API cut cost about 10× to roughly $0.03 per model under a hard monthly budget.
- Operated a $1M paper equity portfolio that grades about 600 companies daily on seven weighted factors, including a weekly Claude read of every business, with a DCF cross-check. It holds 15 to 22 names against the S&P 500 under 8% position and 30% sector caps. An incumbency band plus a 5-day minimum hold halved modeled turnover and friction.
- Ran a cash-secured put and covered-call wheel on a $100K paper account three times a day, rating contracts A to D with weights fit on 2,150 past picks. An AI agent decides whether to hold, close, or roll losing trades within hard limits. A replay over 375K real 2024–26 option contracts showed the live universe beating a wider 300-stock universe in all 200 robustness trials.

## Concordia — Vote-Governed Real-Money Investment Club

`Python` · `FastAPI` · `SQLite` · `Next.js` · `Claude API` — [GitHub](https://github.com/rohanjoglekar/voteconcordia) · [Live demo](https://demo.voteconcordia.com)

- Founded an investment club where members vote weekly to build a roughly 20-stock S&P 500 portfolio. Each member's voting power is scaled 0.5× to 2× by their vote-weighted excess return over the S&P 500. The club's paper decisions index is up 5.6% against the S&P 500's −6.9% across 52 sessions since June 2026.
- Executed the shared portfolio inside each member's own Robinhood account through encrypted OAuth, so capital is never pooled and the club never takes custody. Orders follow T+1 settlement, are built so they cannot duplicate, and every account is reconciled against broker records.
- Added 100 Claude-powered AI voting members, each a distinct investment strategy that votes on every S&P 500 stock weekly with a written thesis but holds no account and places no orders, for about $6 a month in API cost.
- Rebuilt the member app around a research hub with stock pages, sector moves, and SEC and Federal Reserve news, read through each member's own brokerage connection. The public demo runs on the club's Alpaca paper reference account, and more than 900 backend tests cover the system.

---

## Skills

**Technical:** Python (pandas, NumPy, scikit-learn), Java, Pine Script, Excel · Machine Learning · AI Agents · DCF Modeling · Equity & Options Pricing · Options Greeks · Portfolio Construction · Risk Management · Backtesting

**Tools:** Linux · systemd · Git · GitHub Actions · FastAPI · Next.js · SQLite · Ollama · Claude API · Claude Code

## Education

**New Jersey Institute of Technology** — B.S. Financial Technology · *Expected May 2028*
Albert Dorman Honors College · Dean's Scholar · Full-Ride Merit Scholarship · GPA 3.8

---

**Contact:** [rohannj29@gmail.com](mailto:rohannj29@gmail.com)
