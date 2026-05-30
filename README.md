# Week 4 — Advanced Analysis & Reporting of Language Trends using NLP

## Overview
Longitudinal analysis of how AI-related language evolved on Twitter and Reddit from 2018 to 2024. Uses LDA topic modeling, TF-IDF with rolling averages, and K-Means clustering to track four distinct discourse phases — from General AI awareness through to the Generative AI explosion.

## Dataset
- **Source:** Twitter / Reddit AI discussions, 2018–2024
- **Scope:** 7 years of social media discussions about AI topics

## Results & Key Findings

### 4 LDA Topics Discovered

| Topic | Period | Theme | Key Terms |
|-------|--------|-------|-----------|
| Topic 1 | 2018–19 | General AI awareness | artificial intelligence, machine, future, robot, technology |
| Topic 2 | 2020–21 | ML tools & automation | model, training, deep learning, neural network, automation |
| Topic 3 | 2022 | Ethics & job displacement | bias, ethics, jobs, regulation, risk, privacy, fairness |
| Topic 4 | 2023–24 | Generative AI & LLMs | ChatGPT, GPT-4, prompt, LLM, generative, Gemini, Anthropic |

### Topic Share Shift (2018 → 2024)
- **General AI** discourse declined from ~60% → 8%
- **Generative AI** surged from ~2% → 44% share by 2024
- **AI Ethics** grew steadily, peaking at ~35% share in 2022

## Methods Used
1. **LDA Topic Modeling** — uncovered 4 dominant discourse themes across 7 years
2. **TF-IDF + rolling average** — tracked rise and fall of specific AI terms over time
3. **K-Means clustering** — grouped documents by thematic similarity

## Future Work
- Transformer-based topic models (BERTopic)
- Cross-lingual trend analysis
- Sentiment-aware topic modeling

## Project Structure
```
week4/
├── NLP_Language_Trends.ipynb    # Main notebook
├── requirements.txt
└── README.md
```

## Setup & Run
```bash
pip install -r requirements.txt
jupyter notebook NLP_Language_Trends.ipynb
```

## Skills Demonstrated
`LDA` · `Gensim` · `K-Means` · `TF-IDF` · `topic modeling` · `time-series NLP` · `BERTopic` · `wordcloud`
