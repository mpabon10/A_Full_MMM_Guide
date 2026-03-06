# Marketing Measurement: A Complete Guide

Three self-contained Jupyter notebooks covering the full marketing measurement stack — MMM, MTA, and Triangulation — from theory to implementation, designed for data scientists.

## Notebooks

### 1. [MMM_Complete_Guide.ipynb](MMM_Complete_Guide.ipynb) — Marketing Mix Modeling *(4–6 hrs)*
1. **Foundational Theory** — History, key concepts, and the science behind MMM
2. **Mathematical Framework** — Adstock, saturation curves, and the complete MMM equation
3. **Implementation** — Frequentist and Bayesian MMM built from scratch
4. **Advanced Topics** — Time-varying effects, hierarchical models, and two-sided marketplace considerations
5. **Business Applications** — ROI calculation, budget optimization, and scenario planning

### 2. [MTA_Complete_Guide.ipynb](MTA_Complete_Guide.ipynb) — Multi-Touch Attribution *(4–6 hrs)*
1. **Rule-Based Models** — Last-click, first-click, linear, time-decay, and position-based attribution
2. **Algorithmic Models** — Markov chains, Shapley values, and logistic regression-based attribution
3. **Survival Analysis** — Time-to-conversion modeling and hazard-based attribution
4. **Incrementality & Causal Inference** — PSM, geo-lift, ghost ads, and conversion lift studies
5. **Privacy & Production** — Cookie deprecation, iOS 14.5+, cross-device tracking, building pipelines

### 3. [Triangulation_Guide.ipynb](Triangulation_Guide.ipynb) — Measurement Triangulation *(3–4 hrs)*
1. **Why Triangulation** — The limits of any single measurement method
2. **MMM vs. MTA** — Mapping their complementary strengths and blind spots
3. **Unified Measurement Framework** — Combining all three methodologies
4. **Calibrating MMM with Experiments** — Using incrementality results to set Bayesian priors
5. **Reconciliation Playbook** — Diagnosing and resolving model vs. platform disagreements

*Recommended order: MMM → MTA → Triangulation.*

## Prerequisites

- Python 3.10+
- Basic statistics (regression, probability distributions)
- Familiarity with marketing concepts (helpful but not required)

## Getting Started

```bash
# 1. Clone the repo
git clone https://github.com/mpabon10/A_Full_MMM_Guide.git
cd A_Full_MMM_Guide

# 2. Create and activate a virtual environment
python3 -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch a notebook
jupyter notebook MMM_Complete_Guide.ipynb
```

## Dependencies

| Package | Purpose |
|---|---|
| numpy / pandas | Data manipulation |
| scipy / statsmodels | Statistical modeling |
| scikit-learn | Machine learning utilities |
| matplotlib / seaborn | Visualization |
| networkx | Graph-based attribution (Markov chains) |
| tqdm | Progress bars |
| pymc / arviz *(optional)* | Bayesian modeling |

See [requirements.txt](requirements.txt) for pinned versions.


