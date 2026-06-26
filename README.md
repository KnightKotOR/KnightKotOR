## Hello there 👋

I focus on the intersection of **applied ML** and **ML Engineering** — from experiments to deployment.

Currently: polishing projects, diving deep into **MLOps**, and open to **Data Scientist / ML Engineer / ML Researcher** positions.

### Languages and Tools

**ML / DL:**
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#)
[![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?logo=pytorch&logoColor=white)](#)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikit-learn&logoColor=white)](#)
[![XGBoost](https://img.shields.io/badge/XGBoost-EB5424?logo=xgboost&logoColor=white)](#)
[![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?logo=catboost&logoColor=black)](#)
[![Optuna](https://img.shields.io/badge/Optuna-002C76?logo=optuna&logoColor=white)](#)
[![SHAP](https://img.shields.io/badge/SHAP-1D4ED8?logo=shap&logoColor=white)](#)

**Data:**
[![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)](#)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)](#)
[![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)](#)
[![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?logo=scipy&logoColor=white)](#)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?logo=matplotlib&logoColor=white)](#)

**Engineering:**
[![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=fff)](#)
[![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff)](#)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=github-actions&logoColor=white)](#)
[![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white)](#)
[![uv](https://img.shields.io/badge/uv-261230?logo=python&logoColor=white)](#)

### 📂 My projects 📂:

1. [Ultrasonic welding optimization](https://github.com/KnightKotOR/UW_SM):
    > **R&D thesis project** for the "Polymer Composite Materials" lab, SPbPU  
    > *Bachelor's thesis — defended with excellence 25 June 2025*
    > 🔒 *private — refactoring in progress* 🔒

   * Implemented a surrogate assisted bayesian optimization system based on CatBoost + Optuna
   * Achieved **1.4–3× reduction** in the number of experiments needed to find the global optimum compared to classical Bayesian optimization
   * Validated on benchmark functions (Branin, Rosenbrock, harmonic) with systematic methodology
   * Compared:
     * CV configurations (4-,6-,8-fold and LOO)
     * ML models for a surrogate (CatBoost, XGBoost, RandomForest, MLP with Nadaraya-Watson kernel)
     * Optimization methods (CMA-ES, TPE, GP, QMC)

2. [Music Genre Classifier](https://github.com/yrmint/ml-app-arch):
   > **Group project** — ML lead contributor

   * Designed and trained a **2 MB CNN**, achieving **F1 macro = 0.82 without data leakage**; accuracy is comparable to a **380 MB fine-tuned transformers**
   * Adapted the model for inference in a container using Docker and RabbitMQ (The container was configured by the other member)
   * Team practices: **PR reviews**, **conventional commits**, **feature-branch flow**, **CI checks** on all merges

3. [Support ticket prioritization](https://github.com/KnightKotOR/SupportTickets-Prioritization):
   > **End-to-end ML project** — classification on imbalanced data with business constraints

   * Built a priority classifier (Low / Medium / High) on a **50K synthetic dataset** with severe class imbalance
   * **Eliminated critical errors**: zero cases of High→Low misclassification
   * Used **TreeSHAP** to verify model relies on real business factors (downtime, affected users)

4. [Topological Data Analysis research](https://github.com/KnightKotOR/topology-mnist3d):
   > **Research group project**: assisted with TDA pipeline; responsible for the classifier

   * Built a TDA pipeline extracting robust geometric features from 3D point clouds using **gudhi** and **giotto-tda**
   * Improved **F1-macro from 0.73 to 0.81** (+10%) over the baseline CNN, demonstrating effectiveness of topological features
