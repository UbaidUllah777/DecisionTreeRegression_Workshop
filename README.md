# 🧠 Decision Tree Workshop — From Data Analysis to Machine Learning Pipelines

## 🎯 Learning Objective

The **Decision Tree Workshop** is designed to provide students with an applied understanding of **Decision Tree algorithms** as *non-parametric* and *non-linear models* in Machine Learning. Through this hands-on project, students learn not only the mathematical and conceptual foundations of Decision Trees but also their practical application in both **regression** and **classification** tasks using real-world data. The workshop integrates data analysis, model development, visualization, and modular code architecture based on the **Machine Learning Pipeline Pattern**, while introducing the fundamentals of **MLOps** for model tracking and reproducibility.

By engaging in **active learning and peer programming**, students gain experience in designing, coding, evaluating, and reflecting upon machine learning workflows that are both interpretable and operationally robust.

---

## 🧩 Workshop Summary

This workshop serves as an interactive bridge between theoretical learning and practical implementation. It encourages collaborative exploration of the **California Housing** dataset for regression and the **Iris** dataset for classification. Students build Decision Tree models, analyze their performance, and discuss interpretability, trade-offs, and use cases.

The structure of the workshop is divided into three main phases:

### **Before the Workshop**
1. Review the lecture on **non-parametric and non-linear models** to understand where Decision Trees fit in the Machine Learning landscape.  
2. Read scikit-learn documentation for `DecisionTreeRegressor` and `DecisionTreeClassifier`.  
3. Form groups of two or three students to work in a **peer programming** format.  
4. Clone or fork the workshop repository and prepare the environment by installing required dependencies.  

### **During the Workshop**
1. **Data Loading and Exploration** — Load and explore the datasets using pandas and scikit-learn. Analyze data structure, inspect feature distributions, and identify potential issues (e.g., missing values).  
2. **Data Preprocessing** — Split datasets into training and testing sets, and optionally standardize features. This phase introduces concepts of data integrity and reproducibility.  
3. **Model Training** — Train two Decision Tree models:
   - A **DecisionTreeRegressor** for predicting California housing prices.  
   - A **DecisionTreeClassifier** for classifying Iris species.  
   Students explore hyperparameters such as `max_depth` and `criterion` to understand overfitting and model complexity.
4. **Model Evaluation** — Evaluate models using regression metrics (MSE, R²) and classification metrics (accuracy, confusion matrix).  
5. **Visualization** — Visualize decision structures and feature importances to interpret model decisions. Students also learn how to export and document tree structures.  
6. **MLOps Extension** — Introduce the concept of **model tracking** using placeholders for MLflow integration. Students simulate logging of model parameters, metrics, and experiment metadata to prepare for real-world machine learning operations.  
7. **Reflection and Discussion** — Summarize findings, interpret results, and discuss the advantages, limitations, and ideal scenarios for applying Decision Trees.

### **After the Workshop**
- Consolidate code and reflections in the repository.  
- Submit via GitHub and conduct peer code reviews.  
- Prepare a short presentation highlighting findings, insights, and reflections on Decision Tree interpretability and performance.

---

## 🧠 Expected Outcomes

By completing this workshop, students will be able to:
- Understand the **conceptual foundation** of Decision Trees and their algorithmic mechanisms.  
- Build and evaluate both regression and classification models using scikit-learn.  
- Architect modular ML code following the **Pipeline Pattern** for maintainability and scalability.  
- Visualize and interpret model decision boundaries and feature importance.  
- Appreciate the **trade-offs between interpretability and complexity** in non-linear models.  
- Understand the **role of MLOps** in experiment tracking, reproducibility, and model lifecycle management.  
- Collaborate effectively through peer programming and code review, reinforcing shared learning and communication skills.

This workshop blends algorithmic insight with software engineering practices — guiding students toward becoming not only proficient Machine Learning practitioners but also thoughtful engineers of data-driven systems.
