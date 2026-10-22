<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,35:0f172a,70:1e1b4b,100:312e81&height=250&section=header&text=Ojash%20Shrestha&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=34&desc=Applied%20ML%20%E2%80%A2%20Pattern%20Mining%20%E2%80%A2%20Research%20Engineering&descAlignY=56&descSize=19" />

### `build → evaluate → understand → improve`

<br>

<img src="https://img.shields.io/badge/Applied%20ML-6366F1?style=for-the-badge&logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/Pattern%20Mining-0891B2?style=for-the-badge" />
<img src="https://img.shields.io/badge/Research%20Engineering-7C3AED?style=for-the-badge" />
<img src="https://img.shields.io/badge/Robotics-334155?style=for-the-badge&logo=probot&logoColor=white" />

</div>

---

<table>
<tr>
<td width="60%" valign="top">

## 👋 About Me

I'm **Ojash Shrestha**, a Computer Science student at the **University of Aizu, Japan**.

My main interests are **machine learning, pattern mining, research engineering, and intelligent systems**.

I enjoy projects where implementing the algorithm is only the beginning — the interesting part is deciding how to evaluate it, understanding where it fails, and improving the methodology.

</td>

<td width="40%" valign="top">

```text
CURRENT FOCUS
─────────────
Applied ML
Pattern Mining
Data Streams
Research Engineering
Robotics
```

</td>
</tr>
</table>

---

# 🔬 Open-Source Work

<div align="center">

## PAMI — PAttern MIning

**Contributor to the upstream `UdayLab/PAMI` project**

<img src="https://img.shields.io/badge/Open%20Source-Contributor-22C55E?style=for-the-badge&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/Language-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Domain-Pattern%20Mining-8B5CF6?style=for-the-badge" />

</div>

[PAMI](https://github.com/UdayLab/PAMI) is an open-source Python library for discovering useful patterns across transactional, temporal, spatial, streaming, fuzzy, uncertain, and other forms of data.

My upstream contributions include work across **algorithm implementation, optimization, correctness fixes, GPU-oriented mining, and visualization**.

<table>
<tr>
<td width="50%" valign="top">

### 🧩 Algorithms

- [**BinaryApriori**](https://github.com/UdayLab/PAMI/commit/03608ea198452741de229c7ab86cb4d0ebebf36b)
- [**CorrelatedECLAT**](https://github.com/UdayLab/PAMI/commit/35f8ac9df462d6dabf77701831251d4e71eda08a)
- [**FTECLAT**](https://github.com/UdayLab/PAMI/commit/83589e358274d1e618d0acd5c1ca4db4b916a809)
- [**GenMax + MaxMiner**](https://github.com/UdayLab/PAMI/commit/7b63b0f0b536124d121864d374711ea32b34e0c3)

</td>

<td width="50%" valign="top">

### ⚡ Optimization

- [cuEclat / cuEclatBit optimization](https://github.com/UdayLab/PAMI/commit/5bdf973ca324d0940f796b48c19eb9479f9c8b5d)
- [Batched cuApriori GPU kernels](https://github.com/UdayLab/PAMI/commit/8dffb36640e64a59ba9d0f2d8989520937f35335)
- [ECLAT memory optimization](https://github.com/UdayLab/PAMI/commit/5b642a3d2d04ec7ea1b08a029b112832271a5ef9)
- [FPGrowth optimization](https://github.com/UdayLab/PAMI/commit/7f0c25b4894d68f8e80b878c830e558b32f17b0c)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🐛 Correctness

Fixed the lattice traversal in **SpatialECLAT** so that itemsets larger than size two could be mined correctly.

[View upstream commit →](https://github.com/UdayLab/PAMI/commit/c12a3df5ce245203a8f245e28761bcfd3bf6149d)

</td>

<td width="50%" valign="top">

### 📊 Visualization

Added:

- item co-occurrence heatmap
- association-rule scatter plot

[View upstream commit →](https://github.com/UdayLab/PAMI/commit/6dd723733e5376bc6f3630cf8e06aeb85f6f0365)

</td>
</tr>
</table>

<div align="center">

### → [Explore PAMI upstream](https://github.com/UdayLab/PAMI)

</div>

---

# 🧠 Research Direction

<div align="center">

<img src="https://img.shields.io/badge/Streaming%20Data-0EA5E9?style=flat-square" />
<img src="https://img.shields.io/badge/Spatiotemporal%20Mining-8B5CF6?style=flat-square" />
<img src="https://img.shields.io/badge/Incremental%20Algorithms-14B8A6?style=flat-square" />
<img src="https://img.shields.io/badge/Approximate%20Mining-F59E0B?style=flat-square" />

</div>

<br>

```text
                         DATA STREAM
                             │
                             ▼
                 ┌─────────────────────┐
                 │  Pattern Discovery  │
                 └──────────┬──────────┘
                            │
             ┌──────────────┼──────────────┐
             ▼              ▼              ▼
        Temporal        Spatial       Incremental
        structure       context        updates
             │              │              │
             └──────────────┼──────────────┘
                            ▼
                  Approximate summaries
                            │
                            ▼
                    Evolving patterns
```

I'm particularly interested in **frequent-pattern mining for evolving and spatiotemporal data**.

Current research questions include:

- How should frequent patterns be maintained incrementally?
- How should older information be summarized?
- How should spatial relationships constrain pattern generation?
- What happens when the item vocabulary itself grows over time?
- How should approximation error be measured?
- What baselines make a streaming algorithm comparison convincing?

> Ongoing research stays labeled as ongoing. I will add public repositories here when the implementations are ready to represent the work properly.

---

# 💳 Applied Machine Learning

<table>
<tr>
<td width="62%" valign="top">

## Credit Card Fraud Detection

A learning project exploring **extreme class imbalance** in fraud classification.

The dataset contains:

**284,807 transactions**  
**492 fraud transactions**  
**≈ 0.17% positive class**

The project explores:

- Random Forest classification
- class weighting
- precision / recall trade-offs
- confusion matrices
- feature importance
- threshold experiments

### Repository

[**Ojash-Shrestha/credit-card-fraud-detection →**](https://github.com/Ojash-Shrestha/credit-card-fraud-detection)

</td>

<td width="38%" valign="top">

### Experimental result

```text
Threshold    0.27
Recall       0.83
F1           0.88

Fraud found  81 / 98
False +      6
```

⚠️ **Evaluation caveat**

The threshold was selected using the same test split used to report these numbers.

Therefore these are **exploratory results**, not an unbiased estimate of final generalization performance.

</td>
</tr>
</table>

### What I would change

A stronger experimental design would use:

```text
TRAIN
  │
  ├── model fitting
  │
  ▼
VALIDATION
  │
  ├── threshold selection
  │
  ▼
TEST
  │
  └── final evaluation exactly once
```

I keep this limitation visible because identifying weaknesses in an experiment is part of doing applied ML properly.

---

# 🛠️ Technical Toolkit

<div align="center">

### Core

<img src="https://skillicons.dev/icons?i=python,git,github&theme=dark" />

<br><br>

### Machine Learning & Data

<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge" />

<br><br>

### Workflow

<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />

</div>

<br>

> This list intentionally contains technologies I have used in projects rather than every technology I have briefly encountered.

---

# 🧪 How I Think About Experiments

<div align="center">

```text
┌───────────────┐
│    Question   │
└───────┬───────┘
        ▼
┌───────────────┐
│     Data      │
└───────┬───────┘
        ▼
┌───────────────┐
│   Baseline    │
└───────┬───────┘
        ▼
┌───────────────┐
│     Model     │
└───────┬───────┘
        ▼
┌───────────────┐
│  Evaluation   │
└───────┬───────┘
        ▼
┌───────────────┐
│ Error Analysis│
└───────┬───────┘
        │
        └──────────► iterate
```

</div>

The questions I try to ask are:

**What exactly are we measuring?**

**Is the comparison fair?**

**Could information have leaked across the evaluation boundary?**

**Does the metric match the actual problem?**

**What examples does the model still fail on?**

**What claim does the evidence actually support?**

---

# 🤖 Beyond ML

Machine learning is my main technical direction, but I also experiment with **robotics and interactive systems**.

These projects help me explore areas that pure offline ML does not:

```text
Perception
   +
Control
   +
Real-time interaction
   +
Software systems
```

I prefer not to feature experimental or fork-only repositories as portfolio projects until my own contribution is substantial enough to stand on its own.

---

# 🎯 Current Direction

<table>
<tr>
<td align="center" width="25%">

### Learn

ML fundamentals  
Research methods

</td>

<td align="center" width="25%">

### Build

Algorithms  
Experiments

</td>

<td align="center" width="25%">

### Evaluate

Baselines  
Failure modes

</td>

<td align="center" width="25%">

### Improve

Methods  
Systems

</td>
</tr>
</table>

<div align="center">

<br>

## `Applied ML × Data Mining × Research Engineering`

<br>

[![Repositories](https://img.shields.io/badge/Explore%20My%20Repositories-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ojash-Shrestha)

<br><br>

### Build something testable. Measure it correctly. Understand why it works.

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:312e81,45:1e1b4b,100:020617&height=120&section=footer" />

</div>
