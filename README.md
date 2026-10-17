<div align="center">

# Nihar Ranjan Mishra

**AI agents + applied ML engineer** I build agents that do real work in the real world, and ML systems with honest, reproducible numbers.

Research Intern @ **IIT Jodhpur** (School of AI & Data Science) · Co-Lead, **Cloud** @ SIT ACM Student Chapter · B.Tech AI/ML, Symbiosis Institute of Technology, Pune ('28)

[![Open to work](https://img.shields.io/badge/Open_to_work-SDE_%2F_AI_internships-brightgreen)](https://github.com/DeltaN04)

</div>

## Featured projects

### 🛰️ [Turbofan RUL & Maintenance Alerting](https://github.com/DeltaN04/rul-turbofan-Jet-Engine)
**Problem:** fixed-interval engine maintenance wastes healthy life and still misses early failures.
**Built:** end-to-end pipeline on NASA C-MAPSS (FD001–FD004) condition-aware normalisation, causal rolling features, six model families under grouped 5-fold CV; alert thresholds tuned on out-of-fold predictions and frozen before test; Mondrian conformal intervals; Streamlit demo.
**Result:** capped test RMSE **12.3–13.2 cycles on all four subsets**; **100% of fails-within-30 engines detected** with **≈50 cycles median warning lead** (cost-aware policy). The project caught and quantified its own preprocessing bug — the fix moved FD004 from 23.9 → 13.2 RMSE.
**Stack:** Python · scikit-learn · PyTorch · Streamlit

### 🧠 [Pipeline-Corrosion-Guard](https://github.com/DeltaN04/Pipeline-Corrosion-Guard)
**Problem:** manual review of pipeline corrosion inspections misses critical defects and burns engineer hours.
**Built:** LangGraph multi-agent triage (planner → research → executor → critic with loop-back), human-approval gate, work-order generation — fully offline with a deterministic mock LLM; 23-test suite.
**Result:** missed-critical recall **0.85 → 0.98** on the synthetic validation benchmark.
**Stack:** Python · LangGraph · Streamlit · Plotly

### 🍛 [food-ordering-agent](https://github.com/DeltaN04/food-ordering-agent)
**Problem:** ordering across delivery platforms is manual and UI-bound.
**Built:** chat-first ordering API + React UI + Playwright agent that drives Swiggy end-to-end — dish matching, cart via the app's own Redux handlers, address → payments page; `PlatformAdapter` pattern; **never charges**, hands over for manual pay.
**Result:** proven on a live order through to the payments page (₹264), with honest fallbacks when a variant or payment method doesn't exist.
**Stack:** TypeScript · React · Express · Playwright · Python

## Stack

| Area | Tools |
|---|---|
| Languages | Python, TypeScript |
| ML / DL | PyTorch, scikit-learn, pandas, NumPy |
| Agents | LangGraph, multi-agent orchestration, Playwright browser automation, RAG patterns |
| Backend / UI | Node.js, Express, React, Vite, Streamlit |
| Tooling | pytest, Docker, Git |

## Research

- **Undergraduate research intern** School of AI & Data Science, IIT Jodhpur: agentic AI & multi-agent systems.
<!-- TODO: add paper details here when public, e.g. "Paper: Title — under review at <venue>" -->

## Reach me

- GitHub — [@DeltaN04](https://github.com/DeltaN04)
<!-- TODO: LinkedIn URL · public email (currently hidden on your profile) -->
