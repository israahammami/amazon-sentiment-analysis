Amazon Reviews Sentiment Analysis Pipeline
An end-to-end Natural Language Processing (NLP) pipeline designed to extract actionable business intelligence from unstructured Amazon customer reviews. This project benchmarks five supervised machine learning classifiers to determine the most effective approach for sentiment prediction.

🚀 Project Overview
In the competitive landscape of e-commerce, consumer sentiment is a key driver of brand strategy. This project moves beyond simple star ratings, utilizing R to transform thousands of raw text reviews into a diagnostic tool that highlights specific operational pain points and product strengths.

🛠 Tech Stack
Language: R

Data Mining: tm, tidytext

Machine Learning: caret, e1071, ranger, rpart

Visualization: ggplot2, wordcloud

📊 Methodology
Data Cleaning: Standardized unstructured text data (regex-based noise reduction, stop-word removal, and sparsity management).

Lexicon Labeling: Implemented an unsupervised lexicon-based approach (Bing Dictionary) to generate ground-truth labels for 21,000+ reviews.

Feature Engineering: Constructed a Document-Term Matrix (DTM) optimized for model performance.

Modeling & Benchmarking: Evaluated five classifiers:

Naive Bayes

Logistic Regression

Decision Trees

Random Forest

K-Nearest Neighbors (KNN)

📈 Key Results
Top Performance: Random Forest achieved an accuracy of 80%+ (AUC ~0.95), establishing it as the most reliable model for sentiment classification in this domain.

Business Insights: Bigram analysis successfully identified specific friction points (e.g., "missing pieces", "customer support" delays) versus key selling points (e.g., "easy assembly").

📂 Repository Structure
/code: The primary R analysis script.

/visuals: Exported performance charts and sentiment distribution plots.
