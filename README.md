<div align="center">

# Rohan Joglekar

**Financial Technology @ NJIT — Albert Dorman Honors College, full-ride merit scholar**

I design, build, and operate production trading systems end to end — quantitative
research, broker execution, full-stack products, and the Linux infrastructure
beneath them. Built and run by one person.

[![Forge — live dashboard](https://img.shields.io/badge/Forge-live_dashboard-b45309?style=flat-square&logo=bitcoin&logoColor=white)](https://forge-view.5.78.193.177.sslip.io)
[![Concordia — live demo](https://img.shields.io/badge/Concordia-live_demo-0f766e?style=flat-square&logo=nextdotjs&logoColor=white)](https://demo.voteconcordia.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rohan-joglekar-16339132b/)
[![Email](https://img.shields.io/badge/Email-rohannj29@gmail.com-334155?style=flat-square&logo=gmail&logoColor=white)](mailto:rohannj29@gmail.com)

</div>

---

## Flagship systems

<table>
<tr>
<td width="50%" valign="top">

### ⚒ Forge
**Quantitative research & algorithmic trading infrastructure.**

An automated strategy lab built around the hard question — *did this actually
work, or did it just look good?* It generates strategy variants and backtests
them against **measured** costs (real exchange fees, observed bid–ask spreads),
then survives them through a chronological 60/20/20 train–validation–holdout
split, multiple-testing–corrected significance gates, and live shadow evaluation
before any human-approved promotion. Alongside it: a 600-company equity screen
with a gated two-stage DCF and three autonomous paper books.

`Python` · `FastAPI` · `Next.js` · `scikit-learn` · `Alpaca` · `Kalshi`

**[Technical case study →](https://github.com/rohanjoglekar/forge-demo)**
· [Live read-only dashboard](https://forge-view.5.78.193.177.sslip.io)

</td>
<td width="50%" valign="top">

### 🗳 Concordia
**Vote-governed real-money investing.**

A club portfolio decided by vote and executed inside **each member's own
brokerage account** — capital is never pooled and the club never takes custody.
Members vote each cycle to form one auditable basket; a safety-gated executor
rebalances every account independently over encrypted OAuth, respecting T+1
settlement, deterministic order identity, and per-account reconciliation against
broker records. Backed by 200+ backend tests across voting, execution,
authentication, and market data.

`Python` · `FastAPI` · `SQLite (WAL)` · `Next.js` · `OAuth` · `systemd`

**[Technical case study →](https://github.com/rohanjoglekar/voteconcordia)**
· [Live demo](https://demo.voteconcordia.com) · invite code `demo`

</td>
</tr>
</table>

---

## How I build

| Evidence before promotion | Explicit execution authority | Production ownership |
|:---|:---|:---|
| Measured costs, chronological holdouts, multiple-testing controls, live shadow evidence, and benchmark-relative evaluation — nothing ships on a backtest alone. | Human arming, broker review, deterministic order identity, reconciliation, kill switches, and read-only public surfaces that cannot place an order. | Typed APIs, service supervision, resource limits, monitoring, serialized deploys, backups, and tests written from real incidents. |

---

## Toolbox

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-E76F00?style=for-the-badge&logo=openjdk&logoColor=white)
![Pine Script](https://img.shields.io/badge/Pine_Script-131722?style=for-the-badge&logo=tradingview&logoColor=white)

**Backend & data**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

**Frontend & infra**
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

**Finance & quant** — DCF valuation · options pricing & Greeks · portfolio construction · risk management · backtesting with honest friction

---

## Education

**New Jersey Institute of Technology** — B.S. Financial Technology · *Expected May 2028*
Albert Dorman Honors College · Dean's Scholar · Full-Ride Merit Scholarship · GPA 3.8

---

## Public work, private systems

The repositories above are employer-oriented **technical case studies** backed by
private production implementations. They publish architecture, methodology, safety
controls, failure analysis, and selected code — without exposing credentials,
member data, proprietary strategy source, or executable control paths.

📫 **[rohannj29@gmail.com](mailto:rohannj29@gmail.com)**
