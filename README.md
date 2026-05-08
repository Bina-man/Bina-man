<p align="left">
  <a href="https://www.linkedin.com/in/bina-man/"><img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=flat&logo=Linkedin&logoColor=white"/></a>
  <a href="mailto:binasisayet8790@gmail.com"><img src="https://img.shields.io/badge/-Gmail-D14836?style=flat&logo=Gmail&logoColor=white"/></a>
  <a href="https://medium.com/@binasisayet8790"><img src="https://img.shields.io/badge/-Medium-00AB6C?style=flat&logo=Medium&logoColor=white"/></a>
  <a href="https://sites.google.com/view/binyam"><img src="https://img.shields.io/badge/-Portfolio-4285F4?style=flat&logo=Google&logoColor=white"/></a>
  <a href="https://t.me/incherB"><img src="https://img.shields.io/badge/-Telegram-26A5E4?style=flat&logo=Telegram&logoColor=white"/></a>
  <a href="https://leetcode.com/u/binasisayet/"><img src="https://img.shields.io/badge/-LeetCode-F9C44D?style=flat&logo=LeetCode&logoColor=white"/></a>
  <a href="https://www.kaggle.com/bina3csis"><img src="https://img.shields.io/badge/-Kaggle-20BEFF?style=flat&logo=Kaggle&logoColor=white"/></a>
</p>

```
 ██████╗ ██╗███╗   ██╗██╗   ██╗ █████╗ ███╗   ███╗
 ██╔══██╗██║████╗  ██║╚██╗ ██╔╝██╔══██╗████╗ ████║
 ██████╔╝██║██╔██╗ ██║ ╚████╔╝ ███████║██╔████╔██║
 ██╔══██╗██║██║╚██╗██║  ╚██╔╝  ██╔══██║██║╚██╔╝██║
 ██████╔╝██║██║ ╚████║   ██║   ██║  ██║██║ ╚═╝ ██║
 ╚═════╝ ╚═╝╚═╝  ╚═══╝   ╚═╝   ╚═╝  ╚═╝╚═╝     ╚═╝
 Sr. Data Scientist · ML Systems · LLM Engineering · AdTech
```

---

Senior Data Scientist specializing in **end-to-end ML system design** — spanning quantile regression, temporal clustering, causal inference, anomaly detection, and **LLM-powered agent pipelines**. Building production systems where statistical rigor and engineering precision drive measurable outcomes at scale in latency-sensitive AdTech environments.

---

## ⚡ ML Architecture · Pipeline as Neural Net

```
   EDA              EMBED             MODEL             SERVE           FEEDBACK
   ───              ─────             ─────             ─────           ────────

  Polars ●─────────● Word2Vec ───────● LightGBM ───────● Lambda ───────● Thompson
         ╲         ╱╲        ╲      ╱╲          ╲     ╱╲        ╲     ╱
          ╲       ╱  ╲        ╲    ╱  ╲           ╲   ╱  ╲        ╲   ╱
   Kafka  ●─────────● BERT    ─────── ● DCN    ───────── ● O(1)   ───● Elasticity
          ╱       ╲  ╱        ╱    ╲  ╱           ╱   ╲  ╱        ╱   ╲
         ╱         ╲╱        ╱      ╲╱            ╱    ╲╱         ╱     ╲
     DSP ●─────────● HMM     ───────● Iso.Forest ───────● RT infer──────● AutoLoop

          └─────────────────────────────────────────────────────────────────┘
                         hourly recalibration feedback arc
```

---

## 🤖 LLM Engineering · Agents · Retrieval

### Agentic Pipeline Architecture

```
┌─────────────┐    ┌──────────────┐    ┌─────────────┐    ┌──────────────┐    ┌──────────────┐
│  User Query │───▶│   Planner    │───▶│  Tool Use   │───▶│  Reflection  │───▶│   Response   │
│             │    │  LangGraph   │    │  MCP · RAG  │    │ self-critique│    │   grounded   │
└─────────────┘    └──────────────┘    └─────────────┘    └──────────────┘    └──────────────┘
                          │                   │
                          ▼                   ▼
                   ┌────────────┐     ┌──────────────┐
                   │  Memory    │     │  Vector DB   │
                   │  store     │     │  FAISS·pgvec │
                   └────────────┘     └──────────────┘
```

### Retrieval Stack

| Layer | Method | Detail |
|---|---|---|
| **Embedding** | Dense + sparse hybrid | BERT, Word2Vec, BM25 fusion |
| **Indexing** | HNSW approximate NN | 200M+ document scale |
| **Re-ranking** | Cross-encoder | Precision boost post-retrieval |
| **Entity linking** | Custom taxonomy mapper | Publisher content → audience graph |
| **Storage** | FAISS · pgvector | On-prem and cloud portable |

### LLM Routing Strategy

```
Query complexity assessment
        │
        ├──▶ Simple retrieval   ──▶  Haiku  (fast · cheap)
        ├──▶ Structured output  ──▶  Sonnet (balanced)
        └──▶ Complex generation ──▶  Opus   (frontier)
```

**Tools & Frameworks:** `LangGraph` · `LangSmith` · `PydanticAI` · `MCP` · `FAISS` · `pgvector` · `RAG`

---

## 🏭 Production ML Pipeline

```
01 INGEST        02 FEATURES      03 MODEL         04 SERVE         05 FEEDBACK
─────────        ───────────      ─────────        ────────         ───────────
Polars · Kafka   Word2Vec         LightGBM QR      Lambda           Thompson MAB
Bidstream EDA    HMM states       DCN features     O(1) lookup      Auto-calibrate
DSP signals      GloVe embeds     Anomaly detect   Real-time        Price elasticity
     │                │                │                │                │
     └────────────────┴────────────────┴────────────────┴────────────────┘
                              Feedback loop (hourly recalibration)
```

---

## 📊 Impact at a Glance

<div align="center">

| Metric | Result |
|:---:|:---:|
| Bid request reduction | **50%+** |
| GCPM gain | **2×+** |
| Pipeline speedup | **10×** |
| Directional decision accuracy | **76%** |
| Daily revenue lift | **$44–$500** |
| ID5 integration revenue | **$10K+/day** |
| Infra cost reduction | **61%** ($7.63 → $3/hr) |

</div>

---

## 🧠 ML Competencies

```
Bid floor optimization    ████████████████████  95%
Quantile regression       ███████████████████   92%
LLM agents · LangGraph    ██████████████████    88%
Anomaly detection · IVT   ██████████████████    88%
Embedding · HNSW · RAG    █████████████████     87%
NLP · BERT · Word2Vec     █████████████████     86%
Thompson Sampling · MAB   ████████████████      83%
Hidden Markov Models      ████████████████      82%
Causal inference          ███████████████       80%
```

---

## 🔧 Tech Stack

**Core ML**

![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python)
![LightGBM](https://img.shields.io/badge/-LightGBM-05122A?style=flat)
![XGBoost](https://img.shields.io/badge/-XGBoost-05122A?style=flat)
![scikit--learn](https://img.shields.io/badge/-scikit--learn-05122A?style=flat&logo=scikit-learn)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-05122A?style=flat&logo=TensorFlow)

**LLM & Agents**

![LangGraph](https://img.shields.io/badge/-LangGraph-05122A?style=flat)
![LangSmith](https://img.shields.io/badge/-LangSmith-05122A?style=flat)
![PydanticAI](https://img.shields.io/badge/-PydanticAI-05122A?style=flat)
![MCP](https://img.shields.io/badge/-MCP-05122A?style=flat)
![FAISS](https://img.shields.io/badge/-FAISS-05122A?style=flat)
![pgvector](https://img.shields.io/badge/-pgvector-05122A?style=flat)
![RAG](https://img.shields.io/badge/-RAG-05122A?style=flat)

**Data & Infrastructure**

![Polars](https://img.shields.io/badge/-Polars-05122A?style=flat)
![Apache Spark](https://img.shields.io/badge/-Apache%20Spark-05122A?style=flat&logo=Apache%20Spark)
![Apache Kafka](https://img.shields.io/badge/-Kafka-05122A?style=flat&logo=Apache%20Kafka)
![Airflow](https://img.shields.io/badge/-Airflow-05122A?style=flat&logo=Apache%20Airflow)
![Docker](https://img.shields.io/badge/-Docker-05122A?style=flat&logo=Docker)
![MLflow](https://img.shields.io/badge/-MLflow-05122A?style=flat&logo=MLflow)
![DBT](https://img.shields.io/badge/-DBT-05122A?style=flat)
![Terraform](https://img.shields.io/badge/-Terraform-05122A?style=flat&logo=Terraform)

**Cloud**

![AWS](https://img.shields.io/badge/-AWS-05122A?style=flat&logo=amazonaws)
![Amazon Kinesis](https://img.shields.io/badge/-Kinesis-05122A?style=flat)
![Amazon SageMaker](https://img.shields.io/badge/-SageMaker-05122A?style=flat)
![AWS Lambda](https://img.shields.io/badge/-Lambda-05122A?style=flat&logo=AWSLambda)
![Amazon Redshift](https://img.shields.io/badge/-Redshift-05122A?style=flat)

---

## 🗂 Open Source Projects

<p align="center">
  <a href="https://github.com/Bina-man/Sensor_data_ETL">
    <img width="282" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=Bina-man&repo=Sensor_data_ETL&theme=react&bg_color=060B0D&icon_color=F8D866&hide_border=true&show_icons=false"/>
  </a>
  <a href="https://github.com/Bina-man/Pharmaceutical-Sales-Prediction">
    <img width="282" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=Bina-man&repo=Pharmaceutical-Sales-Prediction&theme=react&bg_color=060B0D&icon_color=F8D866&hide_border=true&show_icons=false"/>
  </a>
  <a href="https://github.com/Bina-man/AgriTech_USGS-LIDAR-Challenge">
    <img width="282" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=Bina-man&repo=AgriTech_USGS-LIDAR-Challenge&theme=react&bg_color=060B0D&icon_color=F8D866&hide_border=true&show_icons=false"/>
  </a>
  <a href="https://github.com/Bina-man/abtest-mlops">
    <img width="282" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=Bina-man&repo=abtest-mlops&theme=react&bg_color=060B0D&icon_color=F8D866&hide_border=true&show_icons=false"/>
  </a>
  <a href="https://github.com/Bina-man/Smart-Advertisement">
    <img width="282" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=Bina-man&repo=Smart-Advertisement&theme=react&bg_color=060B0D&icon_color=F8D866&hide_border=true&show_icons=false"/>
  </a>
</p>

<p align="left">
  <a href="https://github.com/Bina-man?tab=repositories&sort=stargazers">
    <img alt="All Repositories" src="https://custom-icon-badges.herokuapp.com/badge/-All%20Repos-2962FF?style=for-the-badge&logoColor=white&logo=repo"/>
  </a>
</p>

---

## 📈 GitHub Analytics

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Bina-man&color=378ADD&style=flat" alt="Profile views"/>
</p>

---

<p align="center">
  <sub>Addis Ababa, ET · Open to remote · AdTech · ML Systems · LLM Engineering</sub>
</p>
