<h1 align="center">AmirHossein Honardoust</h1>

<p align="center">
  <b>Data Scientist & Machine Learning Engineer</b><br/>
  I design data-centric, explainable, and interactive AI systems.
</p>
 
<p align="center">
  <a href="https://github.com/AmirhosseinHonardoust?tab=repositories">All Repositories</a> •
  <a href="https://www.linkedin.com/in/honardoust">LinkedIn</a> •
  <a href="mailto:amirhosseinhonardoost80@gmail.com">Email</a>
</p>

<p align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="463" alt="coding gif">
</p>
<p align="center">
  <img alt="github stats" height="210px" src="https://github-readme-stats-ruby-mu.vercel.app/api?username=AmirhosseinHonardoust&show_icons=true&theme=tokyonight" />
</p>
<p align="center">
  <img alt="Top Langs" height="150px" src="https://github-readme-stats-ruby-mu.vercel.app/api/top-langs/?username=AmirhosseinHonardoust&layout=compact&show_icons=tru&theme=tokyonight" />
</p>

---
  
## About Me

- Data Scientist & ML Engineer with a **Physics** background and hands-on experience across:
  - Time series & forecasting
  - NLP and text classification
  - Computer vision & recommendation systems
  - Algorithmic trading & risk modeling
- Comfortable with the **full ML lifecycle**:
  - Problem framing → data generation/collection → feature engineering → modeling → evaluation → deployment (Streamlit/FastAPI dashboards).
- Strong focus on:
  - **Synthetic data & robustness**
  - **Interactive dashboards & decision-support tools**
  - **LLMs, RAG & hybrid AI architectures**
  - **Explainability & human-centered AI**
- I enjoy writing **deep, structured explanations**, many repos are part code, part essay.

---
  
## Tech Snapshot
 
**Languages & Tools**
 
- **Languages**: Python, SQL, MQL5, a bit of Solidity
- **ML / DL**: PyTorch, TensorFlow/Keras, scikit-learn, XGBoost, LightGBM
- **Time Series & Forecasting**: ARIMA/SARIMA, Prophet, LSTMs, rolling windows
- **NLP**: BERT, TF-IDF, classic ML (LogReg, Naive Bayes, SVM)
- **Apps & Services**: Streamlit, FastAPI, Plotly, SQLite/SQLAlchemy
- **MLOps-ish / Analysis**: SHAP, feature importance, evaluation frameworks, synthetic data benchmarks
 
**Domains & Topics**
 
- Synthetic & tabular data quality
- Forecasting & scenario simulation
- Recommender systems
- Smart contract risk analytics
- Interactive data storytelling
- LLMs & Retrieval-Augmented Generation (RAG)
- Algorithmic trading & financial modeling

---
 
## How to Navigate My Work

I organize my projects into a few **clusters** so you can jump directly to what interests you:

1. Synthetic Data, Data Realism & Anomaly Detection  
2. Forecasting, Dashboards & Interactive ML  
3. LLMs, RAG & Hybrid AI Systems  
4. Core ML, Deep Learning & Portfolio Projects  
5. Explainability, Thinking Like a Data Scientist & AI Philosophy  
6. Smart Contracts, Security & Risk Analytics  

---

## Synthetic Data, Data Realism & Anomaly Detection

> Generating realistic tables, probing data “authenticity”, and stress-testing models.

These projects focus on **fidelity, coverage, privacy, and utility** of synthetic data, plus anomaly detection in tabular domains.

- **[Autocurator-Synthetic-Data-Benchmark](https://github.com/AmirhosseinHonardoust/Autocurator-Synthetic-Data-Benchmark)**  
  A benchmarking toolkit for synthetic tabular data generators:
  - Compares different models (GANs, VAEs, copulas, etc.)
  - Evaluates **distribution fidelity**, **feature coverage**, **privacy leakage**, and **downstream ML utility**
  - Produces **visual reports** (PCA, correlations, histograms) to understand where generators succeed or fail  
  _Goal: make it easier to choose the right synthetic data approach for a business use case._

- **[Synthetic-Data-Artist](https://github.com/AmirhosseinHonardoust/Synthetic-Data-Artist)**  
  Deep dive into **Gaussian Copula vs VAE** for tabular data:
  - Side-by-side comparison of marginal and joint distributions
  - PCA visualizations of real vs synthetic embeddings
  - Correlation matrix similarity, pair plots, and coverage analysis  
  _Think of it as a “microscope” for synthetic tabular data._

- **[Anomaly-Detection](https://github.com/AmirhosseinHonardoust/Anomaly-Detection)**  
  End-to-end anomaly detection on synthetic transactions/sales:
  - Data generation with realistic “weird” patterns injected
  - Uses Isolation Forest, Local Outlier Factor, and classic statistical methods
  - Visual diagnostics and confusion-matrix-style evaluations  
  _Useful for building intuition about anomalies in finance/ops data._

- **[Market-Basket-Analysis](https://github.com/AmirhosseinHonardoust/Market-Basket-Analysis)**  
  Retail-style synthetic purchase data:
  - Apriori & FP-Growth frequent itemset mining
  - Association rules with support, confidence, and lift
  - Exportable rules + quick visual summaries  
  _Foundation for recommendation, cross-sell, and promo design._

- **[Sales-Data-Analysis](https://github.com/AmirhosseinHonardoust/Sales-Data-Analysis)**  
  Lightweight but complete:
  - Synthetic sales dataset generation
  - Cleaning, aggregation, KPI dashboards
  - Time-based trend analysis and segmentation  
  _Great for explaining analytics pipelines to non-technical stakeholders._

- **[Missing-Data-Doctor](https://github.com/AmirhosseinHonardoust/Missing-Data-Doctor)**  
  Toolkit for **missingness profiling & imputation**:
  - Visual missingness maps and patterns (by column, row, time)
  - Simple and advanced imputation strategies
  - Before/after comparisons for ML performance  
  _Focus: understanding how missing data distorts models._

- **[Noise-Injection-Techniques](https://github.com/AmirhosseinHonardoust/Noise-Injection-Techniques)**  
  Experiments on **robustness via controlled noise**:
  - Add noise to tabular features/labels during training
  - Explore how different noise types affect generalization
  - PyTorch-based training loops and results visualization  
  _Bridge between data augmentation and robustness in non-vision domains._

---

## Forecasting, Dashboards & Interactive ML

> Treat forecasting and analytics as **interactive tools**, not static reports.

These projects focus on **Streamlit dashboards**, **scenario analysis**, and **business-friendly UIs**.

- **[Forecast-Factory](https://github.com/AmirhosseinHonardoust/Forecast-Factory)**  
  Forecasting & simulation app:
  - Streamlit UI to upload time series (sales, traffic, revenue)
  - Uses Prophet (and/or other models) for forecasting with confidence intervals
  - Lets users run “what if we change X?” simulations on key drivers  
  _Designed for business teams to explore future scenarios without touching code._

- **[Market-IQ](https://github.com/AmirhosseinHonardoust/Market-IQ)**  
  BI-style web app:
  - Ingests transactional/sales-like data
  - Computes core KPIs (revenue, retention, AOV, etc.)
  - Time-series charts, comparisons, and exportable reports  
  _Acts like a focused analytics tool for small/medium businesses._

- **[Data-Storytelling-Dashboard](https://github.com/AmirhosseinHonardoust/Data-Storytelling-Dashboard)**  
  End-to-end narrative dashboard:
  - E-commerce style dataset with customers, orders, and products
  - KPIs, cohort analysis, and retention curves
  - Visuals + narrative “takeaways” to interpret the charts  
  _Focuses on **storytelling**, not just plotting._

- **[Beyond-Charts-Interactive-Storytelling](https://github.com/AmirhosseinHonardoust/Beyond-Charts-Interactive-Storytelling)**  
  Code + essay:
  - RFM segmentation, cohort tracking, user lifecycle
  - Interactive views that adapt to user selections
  - Conceptual guide on how to build **narrative dashboards**  
  _For people who want to turn dashboards into decision tools._

- **[AI-Report-Factory](https://github.com/AmirhosseinHonardoust/AI-Report-Factory)**  
  Automated reporting:
  - Input: structured data + configuration
  - Output: KPIs, visualizations, and narrative sections in Markdown/HTML
  - Uses templating to make the reporting repeatable  
  _Ideal for recurring reports that still need a “human-readable” style._

- **[AI-Personal-Study-Tracker](https://github.com/AmirhosseinHonardoust/AI-Personal-Study-Tracker)**  
  Productivity & study analytics:
  - Streamlit interface for logging study sessions
  - SQLite backend for persistence
  - ML model (RandomForestRegressor) to predict productivity and surface patterns  
  _Example of sending ML back to the user as personal feedback._

- **[Demand-Forecasting](https://github.com/AmirhosseinHonardoust/Demand-Forecasting)**  
  Classic time-series pipeline:
  - Synthetic demand & seasonality
  - ARIMA/SARIMA modeling workflow
  - Forecast evaluation and plots  
  _Template for demand planning and inventory decisions._

- **[ML-Playground-Autodetect](https://github.com/AmirhosseinHonardoust/ML-Playground-Autodetect)**  
  Auto ML playground:
  - Streamlit UI where you upload a dataset
  - Automatically detects **classification vs regression**
  - Builds sensible ML pipelines + evaluation  
  _Useful for teaching and quick sanity checks._

---

## LLMs, RAG & Hybrid AI Systems

> Building **explainable**, data-grounded LLM systems with retrieval & graphs.

- **[Graph-RAG-Engine](https://github.com/AmirhosseinHonardoust/Graph-RAG-Engine)**  
  A more structured take on RAG:
  - Vector search (FAISS) for semantic retrieval
  - Knowledge graph to add structure and relationships
  - FastAPI backend and optional Streamlit front-end
  - Emphasis on **traceability** and explaining why an answer was given  
  _Great for recommendation, research assistants, or domain-specific QA._

- **[Designing-Hybrid-AI-Systems](https://github.com/AmirhosseinHonardoust/Designing-Hybrid-AI-Systems)**  
  Conceptual + practical:
  - How to combine vector search, knowledge graphs, and LLMs
  - Design patterns for hybrid intelligence
  - Notes on failure modes and interpretability  
  _A “systems thinking” view for building LLM-powered apps._

- **[RAG-vs-Fine-Tuning](https://github.com/AmirhosseinHonardoust/RAG-vs-Fine-Tuning)**  
  Decision framework:
  - When to use RAG, when to fine-tune, when to do both
  - Cost, latency, maintenance, and data constraints
  - Includes examples and architectural diagrams (where applicable)  
  _Helpful for teams deciding how to productionize LLMs._

---

## Core ML, Deep Learning & Portfolio Projects

> Classic ML projects done with **clean structure** and **clear evaluation**.

- **[Stock-LSTM-Forecasting](https://github.com/AmirhosseinHonardoust/Stock-LSTM-Forecasting)**  
  Time-series forecasting with LSTMs:
  - Data preparation with sliding windows
  - PyTorch LSTM architecture
  - Loss curves + forecast vs actual plots  
  _Use case: financial time series, sensor data, or demand._

- **[Image-Captioning-CNN-LSTM](https://github.com/AmirhosseinHonardoust/Image-Captioning-CNN-LSTM)**  
  Computer vision + language:
  - Pretrained ResNet as image encoder
  - LSTM decoder generating captions word by word
  - BLEU score and qualitative examples  
  _Classic example of multimodal ML._

- **[Sentiment-Analysis-BERT](https://github.com/AmirhosseinHonardoust/Sentiment-Analysis-BERT)**  
  Transformer-based text classification:
  - Fine-tuning BERT on sentiment data (tweets)
  - Training/evaluation pipeline
  - Confusion matrix, ROC curves, and example predictions  
  _Template for other classification tasks with BERT-style models._

- **[Sentiment-Analysis-NLP](https://github.com/AmirhosseinHonardoust/Sentiment-Analysis-NLP)**  
  Classical ML for text:
  - Tokenization, stopword removal, lemmatization
  - TF-IDF vectorization
  - Models: Logistic Regression, Naive Bayes, Random Forest  
  _Shows how far you can go with “non-deep” NLP._

- **[Movie-Recommendation-System](https://github.com/AmirhosseinHonardoust/Movie-Recommendation-System)**  
  Hybrid recommender:
  - Content-based filtering (TF-IDF + cosine similarity)
  - Collaborative filtering via matrix factorization
  - Evaluation with ranking metrics and examples  
  _Useful base for product/content recommendations._

- **[LSTM-Time-Series-Forecasting](https://github.com/AmirhosseinHonardoust/LSTM-Time-Series-Forecasting)**  
  Generic LSTM-forecast template:
  - Works on many univariate series
  - Clear code structure and visualizations  
  _Good starting point for experimenting with sequence models._

- **[Handwritten-Digit-GAN](https://github.com/AmirhosseinHonardoust/Handwritten-Digit-GAN)**  
  Generative modeling:
  - DCGAN on MNIST
  - Training loop, generated samples, and latent space interpolation  
  _Intro to generative models in vision._

---

## Explainability, Thinking Like a Data Scientist & AI Philosophy

> Code + essays about how we **think about** and **interpret** AI systems.

- **[Shap-Mini](https://github.com/AmirhosseinHonardoust/Shap-Mini)**  
  Minimal SHAP explainability demo:
  - Tabular ML model (tree-based)
  - Global and local SHAP plots
  - Good for teaching “why did the model decide this?”  
  _Brings explainability down to a small, digestible example._

- **[Think-Like-a-Data-Scientist](https://github.com/AmirhosseinHonardoust/Think-Like-a-Data-Scientist)**  
  Long-form essay:
  - Framing questions, hypotheses, and experiments
  - How to move from raw data → insight → action
  - Balancing rigor with storytelling  
  _More about mindset than code._

- **[Forecasting-The-Future-of-Forecasting](https://github.com/AmirhosseinHonardoust/Forecasting-The-Future-of-Forecasting)**  
  Strategic perspective:
  - How forecasting tools shape decisions
  - Interactive foresight vs static point estimates
  - Reflections on feedback loops and reflexive systems  

- **[The-Future-of-Interactive-ML](https://github.com/AmirhosseinHonardoust/The-Future-of-Interactive-ML)**  
  Why interactivity matters:
  - Benefits of human-in-the-loop ML
  - Examples with Streamlit-style interfaces
  - How UI/UX changes modeling choices  

- **[Algorithmic-Empath-Human-Fallibility](https://github.com/AmirhosseinHonardoust/Algorithmic-Empath-Human-Fallibility)**  
  Ethics & “algorithmic empathy”:
  - Modeling human mistakes, uncertainty, and disagreement
  - Thinking beyond accuracy: fairness, robustness, trust  
  _Explores what it means for algorithms to “understand” humans._

- **[Measuring-The-Soul-of-Data](https://github.com/AmirhosseinHonardoust/Measuring-The-Soul-of-Data)**  
  Philosophy of data realism:
  - What makes data feel “alive” or “authentic”
  - Exploring relationships, diversity, and subtle patterns
  - Especially in the context of synthetic vs organic data  

- **[Quiet-Machines-Minimalist-AI](https://github.com/AmirhosseinHonardoust/Quiet-Machines-Minimalist-AI)**  
  Minimalist AI:
  - Preference for quiet, non-intrusive, human-respecting AI systems
  - Thoughts on attention, overload, and calm technology  

---

## Smart Contracts, Security & Risk Analytics

> Applying ML & static analysis ideas to **smart contracts and risk**.

- **[Python-Solidity-Feature-Engineering](https://github.com/AmirhosseinHonardoust/Python-Solidity-Feature-Engineering)**  
  Feature extraction for Solidity contracts:
  - Parse Solidity code using Python tooling
  - Extract structural & semantic features (complexity, patterns)
  - Basis for risk models, security classification, or audit support  

- **[Smart-Contract-Risk-Analyzer](https://github.com/AmirhosseinHonardoust/Smart-Contract-Risk-Analyzer)**  
  Static analysis plus heuristics:
  - Identify risky patterns in smart contracts
  - Compute risk scores or categories
  - Designed as a step toward automated security triage  

---

## Suggested Flagship Repositories

If you’re just browsing and want a **quick sense** of my work, start here:

- [Graph-RAG-Engine](https://github.com/AmirhosseinHonardoust/Graph-RAG-Engine)  
- [Forecast-Factory](https://github.com/AmirhosseinHonardoust/Forecast-Factory)  
- [Synthetic-Data-Artist](https://github.com/AmirhosseinHonardoust/Synthetic-Data-Artist)  
- [Data-Storytelling-Dashboard](https://github.com/AmirhosseinHonardoust/Data-Storytelling-Dashboard)  
- [Sentiment-Analysis-BERT](https://github.com/AmirhosseinHonardoust/Sentiment-Analysis-BERT)  
- [Think-Like-a-Data-Scientist](https://github.com/AmirhosseinHonardoust/Think-Like-a-Data-Scientist)  

---

> _“AI is not just about models; it’s about systems that solve real problems for real people.”_
