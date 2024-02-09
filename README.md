# Weather Forecast
Two innovative optimized quantum hybrid ensemble networks, BO-QEnsemble and GenHybQLSTM, tailored for weather forecasting tasks.

## GenHybQLSTM:
Hybrid Quantum Genetic Algorithm - Particle Swarm Optimization (QGA-PSO) approach coupled with adaptive weight ensemble technique to boost the performance of QLSTM models. 

### Forecast graph from GA hybrid QLSTM Ensemble model:
![Genhyb_pred_graph](https://github.com/AnanyaSDhar/weather_pred/assets/90474789/1472b9f3-fb44-4100-8d89-b1efed8639a3)

## BO-QEnsemble
Ensemble model combining Quantum Long Short-Term Memory (QLSTM) base models with Bayesian optimization for hyperparameter tuning to enhance 24-hour temperature predictions. Each QLSTM base model is paired with a dedicated Bayesian optimizer, generating a set of K-best hyperparameter configurations to form the hyperparameter space. The ensemble is trained iteratively, considering past errors and a forgetting factor, resulting in significantly improved performance compared to previous models.

### Forecast graph from BO-hybrid QLSTM Ensemble model:
![BO_pred_graph](https://github.com/AnanyaSDhar/weather_pred/assets/90474789/32290053-fd2e-4dfd-8502-59ff1d789d48)
