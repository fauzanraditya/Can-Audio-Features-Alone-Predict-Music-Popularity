# 🎵 Can Audio Features Alone Predict Music Popularity?

A data-driven machine learning case study analyzing whether
Spotify audio features can reliably predict track popularity.

## 🔍 Problem Statement
Can musical attributes such as danceability, energy, and valence
predict whether a song becomes popular — without contextual metadata?

## 📊 Dataset
Spotify tracks across 125+ genres with audio features only.
No artist reputation, playlist exposure, or marketing signals included.

## 🧠 Approach
- Binary classification (top 25% popularity)
- Logistic Regression (baseline)
- Random Forest (main model)
- XGBoost (challenger model)
- ROC-AUC focused evaluation

## 📈 Key Results
| Model | ROC-AUC |
|------|--------|
| Logistic Regression | ~0.61 |
| Random Forest | ~0.72 |
| XGBoost | ~0.73 |

## 💡 Key Insights
- Audio features provide limited but non-zero predictive signal
- Model performance plateaus despite increased complexity
- Popularity is driven more by exposure than acoustic properties

## 🎯 Why This Matters
This project demonstrates how to:
- Diagnose performance ceilings
- Avoid misleading accuracy metrics
- Make data-driven decisions when models stop improving

## 📂 Notebook
👉 [View full analysis notebook](./notebook/spotify_popularity_analysis.ipynb)
