# Kaggle Competitions


## Predict Podcast Listening Time
./podcasts_time
> Your task it to predict listening time of a podcast episode.

Rank: ~400/1300 - Top 31%

Main approach:
- Embeddings cosine similarities on title to measure catchiness score
- Use MICE + LGBM to fill non negligeable missing values
- Use XG-Boost + LGBM + CatBoost ensemble with optuna finetuning



