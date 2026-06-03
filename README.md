<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Hi+%F0%9F%91%8B+I'm+Manoj+Kumar+Bag;M.Tech+CSDP+%40+IIT+Kharagpur;NLP+%7C+RAG+%7C+Deep+Learning+Researcher;Graph+ML+%7C+Convex+Optimization+%7C+Financial+AI;GATE+Mathematics+%E2%80%94+Top+2.18%25+Nationally" alt="Typing SVG" />

<br/>

[![Gmail](https://img.shields.io/badge/manojbag2014%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:manojbag2014@gmail.com)
[![GitHub](https://img.shields.io/badge/ManojkumarTheAnalyst-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ManojkumarTheAnalyst)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manojkumar-bag-b104aa211)
[![Profile Views](https://komarev.com/ghpvc/?username=ManojkumarTheAnalyst&color=58A6FF&style=flat-square&label=Profile+Views)](https://github.com/ManojkumarTheAnalyst)

</div>

---

## 🧑‍🔬 About Me

```yaml
Name        : Manoj Kumar Bag            Roll No : 24MA60R31
Program     : M.Tech — Computer Science & Data Processing
Institute   : IIT Kharagpur  (CGPA: 7.73 / 10)
Background  : M.Sc Applied Mathematics (Visva Bharati) + B.Sc Mathematics
Focus Areas : NLP · RAG Systems · Deep Learning · Graph ML · Convex Optimization · Financial AI
GATE        : Qualified 2023 & 2024 — Top 2.18% Nationally (Mathematics)
Role        : Teaching Assistant — Optimization Techniques & Simulation Labs, IIT KGP
```

I bridge **mathematical rigor** with **production-grade ML systems** — designing hybrid RAG pipelines with 99% recall, transformer summarizers with SOTA ROUGE scores, graph classifiers on 5.3M-node social networks, and deep learning models for financial forecasting.

---

## 🔬 Research Projects  *(IIT Kharagpur)*

### 🏦 Mitigating Hallucinations in Financial Document QA using RAG &nbsp;&nbsp;`Jan–Apr 2026`
> *Advisor: Prof. Somesh Kumar, Dept. of Mathematics, IIT Kharagpur*

- Architected a **HybridRetriever** achieving **99% retrieval recall** across 100+ benchmark questions on real financial documents
- Three-phase retrieval engine: **dense vector search + keyword scanning + TF-IDF re-ranking** for precision financial QA
- **91% overall accuracy** and **98% adversarial robustness** evaluated on TCS, Infosys & Reliance Industries FY2024-25 annual reports

`Python` `FAISS` `HuggingFace Transformers` `TF-IDF` `LangChain` `RAG`

---

### 📰 [Multidocument Summarization using Transformer Models](https://github.com/ManojkumarTheAnalyst/Multi_documentSummarization) &nbsp;&nbsp;`Jul–Nov 2025`
> *Advisor: Prof. Somesh Kumar, Dept. of Mathematics, IIT Kharagpur*

- Engineered a preprocessing pipeline for **3M+ news articles** using text normalization & NER, reducing noise by **40%**
- Fine-tuned **Pegasus** with a custom Hallucination Removal Framework for high-fidelity abstractive summarization
- Achieved **ROUGE-1: 47.65** on 11,490 test examples — **outperforms BART** models on the same benchmark

`Python` `Pegasus` `HuggingFace` `NLTK` `NumPy` `Pandas`

---

### 📈 Bitcoin Price Prediction using Hybrid Deep Learning &nbsp;&nbsp;`Jan–Apr 2025`
> *Advisors: Prof. Bodhayan Roy & Prof. Buddhananda Banerjee, IIT Kharagpur*

- Designed **LSTM + CNN hybrid** model achieving **97.87% prediction accuracy** on a 10K+ Bitcoin sample test set
- Built automated data pipeline: raw → cleaning → imputation → MinMax scaling → ReLU-optimized LSTM with Adam optimizer
- Evaluated rigorously with RMSE & MAPE; generated comprehensive visualizations for trend pattern interpretation

`Python` `TensorFlow` `Keras` `LSTM` `CNN` `NumPy` `Pandas` `Matplotlib`

---

### 🛡️ Opinion Mining Based Fake Product Review Detection &nbsp;&nbsp;`Sep–Oct 2024`
> *Advisor: Prof. Rupanwita Gayen, IIT Kharagpur · Semester 1 Seminar*

- Processed **40,431 Amazon reviews** using tokenization, stopword removal, stemming & TF-IDF vectorization (5000 features)
- Developed multi-model NLP pipeline: TF-IDF + n-grams + linguistic features → **84% fraud pattern precision**
- Trained, tuned (GridSearchCV), and benchmarked two classifiers:

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Naïve Bayes (Multinomial) | 85.38% | 85.69% | 85.38% | 85.36% |
| **Random Forest** | **86.14%** | **86.48%** | **86.14%** | **86.10%** |

`Python` `Scikit-Learn` `NLTK` `TF-IDF` `Random Forest` `Naïve Bayes` `GridSearchCV`

---

## 📊 Course & Academic Projects  *(IIT Kharagpur)*

### 🌐 Social Network Graph Analysis using Dimensionality Reduction &nbsp;&nbsp;`Apr 2025`
> *Course: Big Data Analysis · Instructor: Prof. Arindam Banerjee, Dept. of Mathematics, IIT Kharagpur*

A large-scale graph ML project on **5.3M-node Twitter social network** data — combining BFS-based graph traversal, PCA-based feature compression, and logistic regression for community structure detection.

**Methodology:**
- Constructed undirected friendship graph from 30M+ edges; extracted **5,309,746 unique users**
- Sampled **1000 center nodes**, expanded to **4-hop BFS neighborhoods** (~1.6M nodes/center)
- Built **500-dimensional feature vectors** using top-degree node connectivity profiles per subgraph
- Binary classification target: presence of a **k≥11 clique** (dense community detection)

**Results:**

| PCA Components | Variance Retained | Test Accuracy |
|---------------|-------------------|---------------|
| 7 | ~80% | 95.29% |
| 30 | ~90% | **97.38%** (best) |
| 264 | ~99% | 96.8% |

- **Final model (7 PCA):** Precision **95.41%** · Recall **96.30%** · F1-Score **95.85%**
- 3D PCA visualizations confirmed strong class separability; decision boundaries generalized well on test set

`Python` `NetworkX` `Scikit-Learn (PCA, Logistic Regression)` `NumPy` `Pandas` `Matplotlib` `Seaborn` `Plotly`

---

### ⚖️ Disciplined Saddle Programming (DSP) — Convex Optimization Seminar
> *M.Tech Semester 2 Seminar · Dept. of Mathematics, IIT Kharagpur · Co-authored with Sougata Rana (24MA60R07)*

A rigorous mathematical seminar on **Disciplined Saddle Programming (DSP)** — a domain-specific language (DSL) that automates the dualization of convex-concave min-max problems, analogous to how DCP handles convex programming.

**Core Theory covered:**
- Formalized **saddle functions** (convex in x, concave in y), saddle point problems, and saddle extremum functions (saddle-max is convex, saddle-min is concave)
- Studied **dual reduction**: converting min-max → min-min (or max-max) by expressing suprema/infima through their LP duals — automated by DSP's syntax rules
- Analyzed classical example: reducing a **matrix game** (Nash equilibrium) to a linear program via duality

**Application: Robust Bond Portfolio Construction**
- Modelled a portfolio of **n=20 bonds over T=60 half-year periods** with a $100 budget constraint
- Defined a **yield curve uncertainty set Y** (bounded element-wise, in absolute sum, and in smoothness via δmax=0.02, κ=0.9, ω=10⁻⁶)
- Formulated and solved the robust min-max portfolio problem using `saddle_inner` and `saddle_min` atoms in **CVXPY**, ensuring worst-case portfolio value ≥ $90 for any yield curve shock

`Python` `CVXPY` `Convex Optimization` `Duality Theory` `Lagrangian Relaxation` `Min-Max Optimization` `Robust Optimization`

---

## 💼 Internship Experience

### 🏢 Feynn Labs Services — ML & Data Science Intern &nbsp;&nbsp;`Jun–Aug 2025` &nbsp;`(2 months)`
> *Supervisor: Mr. Sanjay Basumatary · Certificate ID: B122562006*

Completed a structured industry internship across **three end-to-end ML & business projects**:

**① AI Product/Service Prototyping**
- Designed and prototyped AI-driven product/service concepts, applying ML feasibility analysis and rapid model iteration

**② Market Segmentation using ML & Data Analysis** *(flagship project)*
- Analyzed **50K+ vehicle sales records** across 28 Indian states using K-Means, Hierarchical Clustering & GMM → **5 distinct market segments**
- Identified **3 high-growth regional markets** via feature engineering, time-series analysis & PCA visualization
- Delivered a strategic EV market entry roadmap with **₹18 Crore investment plan** projecting **8–12% market share** through segment-specific positioning

**③ AI Product/Service Business & Financial Modelling**
- Developed financial models for AI product deployment: cost-benefit analysis, revenue projections, and market viability assessments

`Python` `Scikit-Learn` `K-Means` `GMM` `Hierarchical Clustering` `PCA` `Time-Series` `Matplotlib` `Seaborn`

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)

**Deep Learning & ML**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge&logoColor=white)

**NLP & LLMs**

![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logoColor=white)

`Pegasus` &nbsp; `BART` &nbsp; `BERT` &nbsp; `FAISS` &nbsp; `Word2Vec` &nbsp; `GloVe` &nbsp; `NLTK` &nbsp; `SpaCy`

**Graph & Network Analysis**

`NetworkX` &nbsp; `BFS/DFS Traversal` &nbsp; `Clique Detection` &nbsp; `PCA on Graphs` &nbsp; `Plotly`

**Optimization**

`CVXPY` &nbsp; `Convex & Saddle Optimization` &nbsp; `Lagrangian Duality` &nbsp; `Robust Optimization` &nbsp; `Min-Max Programming`

**Data Science**

![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logoColor=white)

**Tools & Environment**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)

**Core CS**

`Data Structures & Algorithms` &nbsp; `OOP` &nbsp; `DBMS` &nbsp; `Graph Theory` &nbsp; `Linear Algebra` &nbsp; `Probability & Statistics`

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ManojkumarTheAnalyst&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&cache_seconds=86400" height="165"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ManojkumarTheAnalyst&layout=compact&theme=tokyonight&hide_border=true&cache_seconds=86400" height="165"/>

<br/><br/>

<img src="https://streak-stats.demolab.com/?user=ManojkumarTheAnalyst&theme=tokyonight&hide_border=true&cache_seconds=86400" />

</div>

---

## 🏆 Achievements & Positions of Responsibility

| | Achievement | Details |
|--|------------|---------|
| 🥇 | **GATE 2023 & 2024** | Qualified GATE Mathematics **twice** — **Top 2.18% nationally** (2023) |
| 👨‍🏫 | **Teaching Assistant** | Optimization Techniques Lab (MA39207) & Model & Simulation Lab (MA39206), IIT Kharagpur · Mentored **80+ students** |
| 📚 | **Chegg Q&A Expert** | Solved **1000+ unique mathematics problems** for Chegg India as a freelance expert |
| 🎓 | **COVID-19 Social Impact** | Guided **100+ underprivileged students** (Classes 10–12) for 2 years during the pandemic |
| 🏅 | **Sports** | Silver medal — Intra-Departmental Football Tournament, Visva Bharati University |
| 🚀 | **ISRO Certification** | *Scientific Observation from Space* — ISRO START Programme (19.5 hrs) · ISRO HQ & IIRS Dehradun · Mar–Apr 2026 |
| 📜 | **NSQF Certification** | Domestic Data Entry Operator, NSQF Level 4 — WBEIDC (Jun–Aug 2019) |

---

## 🎓 Education

| Degree | Institution | Year | Score |
|--------|------------|------|-------|
| **M.Tech CSDP** | IIT Kharagpur | 2024 – Present | **7.73 / 10 CGPA** |
| B.Ed Mathematics | WBUTTEPA | 2022 | 92.15% |
| M.Sc Applied Mathematics | Visva Bharati University | 2020 | 66.9% |
| B.Sc Mathematics | University of Burdwan | 2017 | 55% |
| Higher Secondary | WBCHSE | 2014 | 50% |
| Secondary | WBBSE | 2012 | 67.71% |

---

## 📚 Relevant Coursework

**Computer Science:** OOP · Data Structures & Algorithms · DBMS · Artificial Intelligence & Machine Learning

**Mathematics:** Linear Algebra · Probability & Statistics · Big Data Analysis · Graph Theory & Algorithms · Differential Equations · Optimization Techniques · Convex Optimization

---

<div align="center">

*"Turning mathematical intuition into measurable ML impact — from 5 million node graphs to financial RAG systems."*

<br/>

📬 **manojbag2014@gmail.com**

</div>
