## Hello there 👋

I’m currently working on polishing my projects and diving deep into MLOps

### Languages and Tools

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#)

<!-- Machine Learning & Data Science -->
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikit-learn&logoColor=white)](#)
[![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?logo=pytorch&logoColor=white)](#)
[![Optuna](https://img.shields.io/badge/Optuna-002C76?logo=optuna&logoColor=white)](#)

<!-- Infrastructure -->
[![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=fff)](#)
[![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff)](#)
[![uv](https://img.shields.io/badge/uv-Lightning_Fast-261230?logo=python&logoColor=white)](#)

### My projects:

1. [Ultrasonic welding optimization (R&D thesis project for the "Polymer composite materials" lab)](https://github.com/KnightKotOR/UW_SM):

   * Implemented a multi-fidelity optimization system based on CatBoost + Optuna.
   * Reduced the number of search steps to find the optimum by 1.4–3x compared with classic Bayesian optimization.
   * The repository is currently plrivate due to undergoing cosmetic refactoring.

2. [Audio classification (group project, responsible for ML)](https://github.com/yrmint/ml-app-arch):

   * Designed and trained a 2 MB CNN for audio classification, achieving F1 = 0.82 without data leakage; performance is comparable to fine-tuned 380 MB transformers.
   * Adapted the model for inference in a container using Docker and RabbitMQ.
   * Team collaboration: reviewed other team members’ PRs; my PRs were reviewed by the teamlead. We used conventional commits and a feature-branch flow. All changes were merged into main through PRs with CI checks.

3. [Topological Data Analysis research (group project)](https://github.com/KnightKotOR/topology-mnist3d):

   * Developed a TDA pipeline for extracting robust geometric features from 3D MNIST using gudhi and giotto-tda.
   * Trained XGBoost with an F1-score of 0.81, which is about 10% higher than the baseline CNN (F1 = 0.73).

4. [Support ticket prioritization system](https://github.com/KnightKotOR/SupportTickets-Prioritization):

   * Developed a ticket priority classifier on a synthetic, highly imbalanced dataset (50,000 records).
   * Built a pipeline with cross-validation and stratified splitting. Trained XGBoost (hyperparameter tuning with Optuna) and achieved F1-macro = 0.98.
   * Business impact: eliminated critical errors (no High incident is predicted as Low).
   * Using SHAP, demonstrated that the model was not overfitting and relied on real business factors (downtime, number of affected users).
