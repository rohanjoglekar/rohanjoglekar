<div align="center">

# Rohan Joglekar

**Financial Technology at NJIT · Albert Dorman Honors College · Full-Ride Merit Scholar**

[![Résumé (PDF)](https://img.shields.io/badge/Résumé-download_PDF-b91c1c?style=flat-square&logo=adobeacrobatreader&logoColor=white)](https://github.com/rohanjoglekar/rohanjoglekar/blob/main/Rohan_Joglekar_Resume.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rohan-joglekar-16339132b/)
[![Email](https://img.shields.io/badge/Email-rohannj29@gmail.com-334155?style=flat-square&logo=gmail&logoColor=white)](mailto:rohannj29@gmail.com)

</div>

I build and operate quantitative trading and research systems end to end — the research, the execution, and the infrastructure that runs them.

---

## Forge — Autonomous Systematic Trading & Research Platform

`Python` · `FastAPI` · `Next.js` — [GitHub](https://github.com/rohanjoglekar/forge-demo) · [Live dashboard](https://forge-view.5.78.193.177.sslip.io)

- Engineered the platform on a Linux server with a Python and FastAPI backend, a Next.js dashboard, and systemd services and timers that run every job automatically; agentic workflows use local models served through Ollama and frontier models for more complex tasks.
- Operated a $1M paper equity portfolio that ranks 600 companies on value, quality, growth, momentum, sentiment, and news factors plus a two-stage DCF valuation, building a long-only portfolio benchmarked against the S&P 500 with conviction-based position sizing, position and sector caps, and minimum cash/bond buffers.
- Ran an automated options trader using a cash-secured put and covered-call wheel strategy that evaluates contracts on probability of profit, downside buffer, premium yield, liquidity, and IV rank, opening and managing positions three times each trading day.
- Developed an automated quantitative research pipeline that generates strategy variants, backtests them against measured costs — live exchange fees and observed bid-ask spreads — on a 60/20/20 train/validation/holdout split, gates promotion on statistical hypothesis tests, and validates survivors live on Kalshi 15-minute Bitcoin contracts before human-approved promotion.

## Concordia — Vote-Governed Real-Money Investment Club

`Python` · `FastAPI` · `SQLite` · `Next.js` — [GitHub](https://github.com/rohanjoglekar/voteconcordia) · [Live demo](https://demo.voteconcordia.com)

- Founded an investment club where members vote each cycle to build a portfolio of roughly 20 S&P 500 stocks; members gain or lose voting power based on the alpha their vote generates against the S&P 500 index.
- Executed the group portfolio inside each member's own Robinhood account through encrypted OAuth, so capital is never pooled and the club never takes custody; sells and buys run on separate days to respect T+1 settlement, orders are built so they cannot duplicate, and every account is reconciled against broker records.
- Ran an always-on public demo against an isolated brokerage simulator built from the same codebase, covered by more than 200 backend tests across voting, execution, authentication, market data, and reconciliation.

---

## Skills

**Technical:** Python (pandas, NumPy, scikit-learn), Java, Pine Script, Excel · Machine Learning · DCF Modeling · Equity & Options Pricing · Options Greeks · Portfolio Construction · Risk Management · Backtesting

**Tools:** Linux · systemd · Git · GitHub Actions · FastAPI · Next.js · SQLite · Ollama

## Education

**New Jersey Institute of Technology** — B.S. Financial Technology · *Expected May 2028*
Albert Dorman Honors College · Dean's Scholar · Full-Ride Merit Scholarship · GPA 3.8

---

**Contact:** [rohannj29@gmail.com](mailto:rohannj29@gmail.com)
