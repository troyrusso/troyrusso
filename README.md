# Troy Russo

Senior at the University of Washington, double majoring in Statistics (Data Science) and Mathematics (B.S. expected June 2027).

My research so far is on adaptive data selection. I'm most interested in stochastic optimization and online learning: when a procedure that adapts to the data it has seen provably matches or beats a fixed one, and how to make it work at scale.

---

## Research

### Weighted improved Greedy Sampling (WiGS)
Co-author · Under review, AAAI 2027 · [arXiv:2603.10435](https://arxiv.org/abs/2603.10435) · [Code](https://github.com/thatswhatsimonsaid/WeightedGreedySampling)

* **Problem:** Active learning for regression picks which points to label next. Improved Greedy Sampling (iGS) scores points by multiplying feature-space diversity and output-space uncertainty. The paper proves that in dense feature regions this product cannot prioritize high-uncertainty points.
* **Method:** WiGS replaces the product with a weighted sum and chooses the weight online with a multi-armed bandit. We benchmarked the bandit against a Soft Actor-Critic agent and chose the bandit for sample efficiency.
* **Result:** WiGS outperformed iGS across 20 benchmark and synthetic regression datasets.
* **My role:** Ran the benchmark suite on the lab's SLURM cluster, and led the full revision and resubmission of the paper (UAI to AAAI).

### Gap-filling satellite chlorophyll with deep learning (NOAA Fisheries)
Varanasi Summer Fellow, June to Sep 2026 · Continuing as a UW research assistant through June 2027 · Mentor: Eli Holmes · [Project page](https://github.com/troyrusso/noaa-chlorophyll-gap-filling)

* Scaled a U-Net gap-filling model for satellite chlorophyll-a from toy examples to real global datasets, leaving compute, not the model, as the remaining bottleneck.
* Diagnosed and removed tiling artifacts in large-region inference by deriving memory-safe tile specifications; the fix is now built into the model ahead of its planned public release.
* Trained on cloud GPUs (AWS via SkyPilot) with xarray/zarr data pipelines, working with UW eScience data scientists on GPU scaling.

### Pacific Northwest National Laboratory
* **Machine Learning Intern (2025):** Tuned and scaled UNet and ResNet models for spectroscopic data; improved and extended distributed training and inference pipelines on SLURM-managed HPC clusters.
* **Chemistry Laboratory Intern (2024):** Developed a hydrothermal titration method for rare earth separation, studying how inorganic ligands, pH, and temperature govern selective crystallization.

---

## Projects

### [Intersectional Bias in LLM Narrative Generation](https://github.com/troyrusso/LLM-Bias-Audit)
Statistics capstone (STAT 496), Winter 2026 · Lead developer
* Two-stage "LLM-as-a-judge" audit of a locally hosted, quantized Meta-Llama-3-8B-Instruct model across 2,160 generation trials, with ANOVA and chi-square tests for demographic differences.

### [Eurostat Shiny Dashboard](https://github.com/troyrusso/Eurostat-Shiny-Dashboard)
Data visualization course project (STAT 451)
* Interactive R Shiny app for European urban transport data, designed with colorblind-safe palettes.

### [Salary Predictive Modeling](https://github.com/troyrusso/Salary-Predictive-Modeling)
* Regression modeling and inference for salary outcomes in R.

---

## Skills
* **Languages:** Python, R, SQL, Java, Bash
* **ML and scientific computing:** PyTorch, JAX, TensorFlow, scikit-learn, SciPy, NumPy, pandas, Ray, xarray, zarr
* **Infrastructure:** Linux, Git, SLURM and HPC clusters, AWS (SkyPilot), Jupyter
* **Methods:** GLMs, regularization, cross-validation and model evaluation, hypothesis testing, active learning, multi-armed bandits

---

## Contact
* **LinkedIn:** [linkedin.com/in/troyrusso](https://www.linkedin.com/in/troyrusso/)
* **Email:** [trusso96@uw.edu](mailto:trusso96@uw.edu)
