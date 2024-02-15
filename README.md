### Модель рекомендаций товаров для пользователей
Целевая метрика: precision@5 > 25%
### Результаты
| Алгоритм | precision@5 | money_precision@5 | recall@5 | money_recall@5 |
|-------|-------|-------|-------|-------|
| als_recommendations |	**0.146** |	0.143 |	0.0146 |	0.0207 |
| own_recommendations |	0.1621 |	0.1569 |	0.0147 |	0.0216 |
| similar_items_recommendation |	0.0813 |	0.0934 |	0.0073 |	0.0104 |
| similar_users_recommendation |	0.0043 |	0.0035 |	0.0004 |	0.0003 |
| i2i_recommendation |	0.0069 |	0.0064 |	0.0023 |	0.0028 |
| cosine_recommendation |	0.0071 |	0.0072 |	0.0008 |	0.0014 |
| als_recommendations_cand50 |	**0.2019** |	0.1988 |	0.0137 |	0.0197 |
| own_recommendations_cand50 |	0.2194 |	0.2119 |	0.0131 |	0.0196 |
| similar_items_recommendation_cand50 |	0.1143 |	0.1339 |	0.0076 |	0.0105 |
| similar_users_recommendation_cand50 |	0.0056 |	0.0051 |	0.0002 |	0.0004 |
| i2i_recommendation_cand50 |	0.0087 |	0.0091 |	0.0016 |	0.0022 |
| cosine_recommendation_cand50 |	0.0083 |	0.0077 |	0.0004 |	0.0006 |
| als_recommendations_cand50 + LightGBM |	**0.2222** |	- |	- |	- |
| als_recommendations_cand50 + FeatureEng + LightGBM |	**0.267** |	- |	- |	- |
