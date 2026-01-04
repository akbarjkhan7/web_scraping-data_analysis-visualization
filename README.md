# Programming for Data Science: Web Scraping, Text Analytics & Probabilistic Modelling

This repository contains my **Programming for Data Science** coursework, which demonstrates the use of Python for end-to-end data acquisition, processing, analysis, and modelling across multiple real-world datasets.

The assignment focuses on building **robust, reusable data pipelines**, applying analytical reasoning, and producing interpretable outputs rather than one-off scripts.

---

## Assignment Overview

The coursework is structured into three main parts:

1. **Web scraping and exploratory analysis**
2. **Text analytics and sentiment analysis**
3. **Probabilistic and predictive modelling**

Each part addresses a different stage of the data science workflow while emphasising programming best practices.

---

## Part 1 — Web Scraping & Publication Analysis

### Objective
To programmatically extract publication metadata from a live website and analyse trends in academic output.

### Key Tasks
- Locate and navigate publication pages dynamically
- Scrape structured data using `requests` and `BeautifulSoup`
- Extract:
  - Publication title
  - Year
  - Journal
  - Authors and author count
  - Impact factor and citation counts
- Clean, de-duplicate, and structure the data into a Pandas DataFrame

### Analysis & Visualisation
- Publications per year
- Impact factor vs number of authors
- Distribution of impact factors

This section demonstrates:
- Robust HTML parsing
- Defensive programming (error handling, fallbacks)
- Reproducible data extraction pipelines

---

## Part 2 — Text Analytics & Sentiment Analysis

### Objective
To analyse policy documents using readability metrics and sentiment analysis, and explore how these measures evolve over time.

### Key Tasks
- Load and process large collections of policy text files
- Compute readability scores using `textstat`:
  - Flesch Reading Ease
  - SMOG Index
  - Coleman–Liau Index
  - Flesch–Kincaid Grade
  - Dale–Chall Score
- Perform sentiment analysis using `TextBlob`
- Cache intermediate results to avoid unnecessary recomputation

### Analysis & Visualisation
- Distribution of readability and sentiment metrics
- Temporal trends in median readability and sentiment
- Correlation analysis between readability and sentiment measures

This section highlights:
- Efficient file handling
- Text preprocessing
- Analytical validation through correlation and trend analysis

---

## Part 3 — Probabilistic & Predictive Modelling

### Objective
To explore relationships between system variables using probabilistic modelling and evaluate predictive performance using supervised learning.

### Bayesian Network Modelling
- Feature selection via correlation analysis
- Discretisation of continuous variables
- Structure learning using Hill Climb Search (K2 score)
- Parameter estimation with Bayesian Estimation
- Model evaluation using:
  - Accuracy
  - F1 score
  - Precision and recall
  - Log-likelihood and structure scores

### Predictive Modelling
- Random Forest classifier for warning prediction
- Train–test split with feature scaling
- Model evaluation using:
  - Accuracy
  - Confusion matrix
  - Classification report

This section demonstrates:
- Probabilistic reasoning
- Model interpretability
- Comparison between explanatory and predictive approaches

---

## Tools & Libraries
- **Language:** Python
- **Core libraries:**
  - pandas, numpy
  - requests, BeautifulSoup
  - matplotlib, seaborn, bokeh
  - textblob, textstat
  - scikit-learn
  - pgmpy, networkx

---

## Repository Structure


---

## Key Takeaways
- Programming choices directly impact reproducibility and scalability
- Defensive coding is essential when working with real-world data sources
- Different modelling paradigms serve different analytical goals
- Clear structure and documentation are as important as model performance

---

## Author
**Akbar Jamal Khan**  
MSc Data Science (Distinction), Durham University
