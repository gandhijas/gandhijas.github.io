---
layout: page
title: Background
permalink: /background/
---


## Background

### Context
Financial markets are noisy, high-dimensional, and often non-stationary. Classical machine learning models (logistic regression, SVMs, neural networks) are widely used for **regime detection**, **risk modeling**, and **alpha discovery**, but can struggle with scalability or generalization in certain settings. **Quantum Machine Learning (QML)** proposes leveraging **superposition, entanglement, and high-dimensional Hilbert spaces** to create expressive models that might one day learn complex patterns more efficiently.

Here, we conceptually build a **quantum variational classifier** that ingests a tiny feature vector (e.g., short-term vs. long-term moving average crossover, realized volatility, momentum) and outputs a predicted regime label (bull/bear). While current NISQ-era devices won’t beat strong classical baselines, this project helps map the **pipeline from finance data → quantum feature encoding → variational training → measurement-based prediction**.

### Motivation
I’m interested in **quantitative finance** and **AI**. This project lets me connect those interests to the fast-growing world of **quantum computing**, asking: *If/when scalable quantum devices arrive, which ML problems in finance might benefit first?* Regime detection is a natural entry point because it’s central to **portfolio allocation, risk management (VaR/CVaR), and strategy switching**.

### Complementary Video (reference)
- **“Quantum Computing for Finance – Stefan Woerner (IBM)”** – a clear, high-level talk on how quantum algorithms map to finance problems (risk, portfolio optimization, Monte Carlo).  
  *(You can substitute any IBM/Qiskit Finance or Xanadu talk you liked during the program.)*

### References
1. **Schuld, M., Sinayskiy, I., & Petruccione, F. (2015).** *An Introduction to Quantum Machine Learning*. Contemporary Physics, 56(2), 172–185. https://arxiv.org/abs/1409.3097  
2. **Biamonte, J., Wittek, P., Pancotti, N., Rebentrost, P., Wiebe, N., & Lloyd, S. (2017).** *Quantum Machine Learning*. Nature, 549, 195–202. https://arxiv.org/abs/1611.09347  
3. **Orús, R., Mugel, S., & Lizaso, E. (2019).** *Quantum computing for finance: overview and prospects*. Rev. in Phys., 4, 100028. https://arxiv.org/abs/1807.03890  
4. **Woerner, S., & Egger, D. J. (2019).** *Quantum risk analysis*. npj Quantum Information, 5, 15. https://arxiv.org/abs/1806.06893

---
