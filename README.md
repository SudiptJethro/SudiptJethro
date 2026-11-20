### Hi, I'm Yithro👋

I run the finance function at a last-mile delivery company in Muscat, Oman, and I'm moving into quantitative finance. This page collects the research and tools I've built along the way: factor models, portfolio construction, and the data systems behind a real business.

---

#### 📈 Quant research

- **GCC equity factor research.** Fama-MacBeth regressions across 202 stocks on five Gulf exchanges. Quality was the strongest factor (Sharpe 1.03), and an investable multi-factor portfolio kept a net Sharpe of about 0.49 after transaction costs.
- **Family Office Lab** *(in progress)*. A systematic multi-asset absolute-return fund I'm designing. The investment policy statement is written, and the GCC factor model will drive the equity sleeve.
- **[Portfolio Risk & Multi-Asset Allocation Dashboard](https://github.com/SudiptJethro/Multi-Asset-Portfolio-Optimizer-and-Risk-Dashboard).** Portfolio metrics, VaR/CVaR, alpha/beta against the S&P 500, and correlation analysis in Streamlit. [Live demo](https://multi-asset-portfolio-optimizer-and-risk-dashboard-ihbd.streamlit.app)

#### ⚙️ Systems in production

- **Onyx Rider Ops** *(private repo)*. Two Google Apps Script systems that operations staff at a last-mile delivery company use every day. One takes riders from sign-up to their first live login, with a 10-stage pipeline, OCR checks on Omani ID cards and vehicle registrations, an event log and a funnel dashboard. The other imports the delivery partner's rider performance reports every hour. 250+ riders tracked and 140+ taken live across five cities, with unit tests running in CI.
- **[Oman SME intelligence](https://github.com/SudiptJethro/oman-sme-intelligence)** *([live demo](https://sudiptjethro.github.io/oman-sme-intelligence/))*. Sourced and scored private Omani SMEs for a private investment client looking for ICV-aligned targets. These companies publish no accounts, so it estimates turnover from Tender Board procurement records, and it narrowed about 20,000 suppliers to a shortlist of about 130. Built in Python with Cloudflare D1 and Workers AI; ran from April to October 2026.
- **[VC deal-flow pipeline](https://github.com/SudiptJethro/vc-deal-flow-pipeline)** *([live demo](https://sudiptjethro.github.io/vc-deal-flow-pipeline/dashboard/))*. A free, Tracxn-style tool I built to find early-stage Indian startups and their founders. It pulls from Hacker News, Product Hunt, news sites, accelerator portfolios and public search results, sorts companies by sector and ranks founders into tiers. Built in Python with Cloudflare Workers and D1.

<sub>Both live demos run on synthetic data.</sub>

#### 🚀 Ventures

- **FortuneFlo** *(private repo)*. An AI-native personal finance app for salaried professionals in India, co-founded with my brother, that predicted users' financial behaviour instead of just tracking it. I built the MVP end to end in Flutter, Supabase and Python, connected to India's Account Aggregator framework. We closed it in July 2026 after it didn't find enough demand.

#### 🧰 Toolkit

Python · JavaScript / Google Apps Script · SQL · Streamlit · Flutter · Excel & financial modelling

#### 🎓 Background

First-Class Honours in Accounting & Finance (Cardiff Metropolitan University) · buy-side internship at Salim International · earlier coursework in computer science and maths

---

[LinkedIn](https://www.linkedin.com/in/sudiptjethro)
