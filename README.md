## Vivek Kumar

I.MSc Quantitative Economics & Data Science at BIT Mesra, graduating 2027. I build memory and retrieval systems for LLMs and measure them, and I gravitate to problems where the statistics have to be right as well as the engineering.

**Paper:** *Conformalized Residual Option Pricing with Asymmetric Uncertainty Intervals*, presented at CIMA 2026 (NIT Puducherry); to appear in Springer Lecture Notes in Networks and Systems (Scopus-indexed).

### Worth opening

**[Long-Term Memory for LLM Assistants](https://github.com/KalWardin-Dronzer/Neurohack)**
An LLM extracts typed, dated memories that cite their source turns, and dense + BM25 retrieval fused by Reciprocal Rank Fusion brings them back. Benchmarked end to end on LoCoMo: memories alone answer temporal questions far better than raw-turn RAG (76% vs 52%), because dates are resolved when a memory is written, but they lose single-hop details. Pairing them with raw turns fixed that: on 200 held-out questions, under a criterion declared before the run, the hybrid beat raw-turn RAG 68.5% to 55.0% (+13.5 points, 95% CI 6.5 to 20.5). Its Gemini extractor is distilled into a LoRA-tuned Qwen3.5-0.8B that runs locally through Ollama. Rebuilt from a 26th-place Neurohack (IIT Guwahati) entry.

**[Hybrid CNN–BiLSTM–Transformer for Predictive Maintenance](https://github.com/KalWardin-Dronzer/NASA-C_MAPSS_transformers)**
Remaining-useful-life prediction for turbofan engines on all four NASA C-MAPSS subsets, rebuilt from a course project after finding that it spliced engines together and leaked its validation split. With engines held out whole and three seeds, it beats a linear baseline on the three harder subsets (FD004: 16.5 vs 19.5 cycles RMSE, truth capped at 125) and ties it on the simplest; its Monte Carlo dropout intervals are too narrow, and the README says so. Python, TensorFlow, Keras, pytest, GitHub Actions.

**[Electoral bonds and stock returns](https://github.com/KalWardin-Dronzer/Political_Alpha_Tracker)**
Matched all 18,871 bonds in India's March 2024 electoral bond disclosure to 1,589 listed companies, then re-tested a published political lead-lag with a size-matched placebo, period-clustered errors, trading costs and a deflated Sharpe ratio. It does not hold: the lead-lag that exists is size and liquidity, and costs erase it. Checking the refactor against the old outputs turned up four measurement bugs, now fixed. Python, pandas, statsmodels, RapidFuzz, NetworkX, GitHub Actions.

### Also here

Bayesian inference on COVID-19 transmission with adaptive Metropolis–Hastings MCMC · a regime-aware genetic algorithm for multi-asset portfolio optimisation · SARIMA forecasting of India's electricity generation.

---

[LinkedIn](https://linkedin.com/in/vivek-kumar-6414a2384) · vivek.kumar240043@gmail.com
