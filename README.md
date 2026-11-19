# Hi, I'm Evan Kennedy 😁👋

**Data scientist and machine learning engineer focused on agriculture and food systems.**

I'm a Computer Science graduate and Applied Machine Learning master's student at the **University of Maryland, College Park**. I build practical, data-driven tools that help the people who grow and move food, from small-farm yield planning to pest-risk prediction. Outside of code, I lead and organize **food recovery efforts on campus**, since the problems I work on are ones I care about beyond the classroom too.

I'm looking for **data science / ML roles in agriculture, food systems, and sustainability**, and I'm also open to general data science and ML positions.

## 🔬 Featured Projects

### 🌽 [Building a Management Aid for Small Farms](https://github.com/evankennedy-52/Portfolio/tree/main/[2025]%20Farm%20Yield%20Prediction%20Tool%20Tutorial)
*Python · pandas · scikit-learn · matplotlib / seaborn · Jupyter*

Large farms can afford precision-agriculture consultants, and small ones usually can't. I built an end-to-end tutorial that lets a small-farm manager turn spreadsheet records into a **corn yield estimator** on an ordinary laptop.
- Cleaned and merged multi-sheet field-trial data (~1,400 plots, University of Nebraska-Lincoln)
- Built a regularized regression model, choosing complexity by cross-validation
- **Result:** test RMSE ≈ 19 bu/acre and R² ≈ 0.74 using only information available before planting
- Used model coefficients to confirm that nitrogen and irrigation are the clearest controllable yield drivers

### 🌱 [Corn Yields and Sustainable Growing Methods](https://github.com/evankennedy-52/Portfolio/tree/main/[2024]%20Corn%20Yields%20with%20Growing%20Methods)
*R · tidyverse · ggplot2 · linear regression · leave-one-year-out validation*

Farmers often hesitate to adopt no-till, cover crops, and crop rotation because they fear yield losses. I analyzed 13 years of controlled Iowa State field data to test that worry.
- Compared yields across tillage, cropping systems, and rotations, with rainfall and temperature as controls
- Validated with leave-one-year-out cross-validation so models never saw the season they were predicting
- **Finding:** the practices had little predictive power over yield, and no strong yield penalty showed up for sustainable methods. Weather and other conditions mattered far more
- Wrote a plain-language memo for farmers, policymakers, and the public alongside the technical notebook

### 🐝 [Pipeline for a Regionally Curated Varroa Infestation Predictor](https://github.com/evankennedy-52/Varroa-Infestation-Prediction)
*Python · XGBoost · Optuna · Docker · ClearML*

Varroa mites are among the biggest threats to honey bee colonies. I built a **containerized, configurable ML pipeline** that lets a beekeeper supply their own apiary data and get a model and infestation-risk predictions tailored to their region.
- Three-stage pipeline (data processing → model fitting → prediction), run with a single Docker Compose command
- Hyperparameter tuning with Optuna, with experiment tracking in ClearML
- Designed so models train on geographically similar apiaries, improving computational efficiency and convergence
- Reached ~95% prediction accuracy on the included Austrian example data
- Written for non-technical users, with documented data formats and config files

## 🥬 Beyond the Code

I lead and organize **food recovery efforts at UMD**, work that keeps me connected to how food moves through a system and where it gets lost. Details are on my [resume](https://github.com/evankennedy-52/evankennedy-52.github.io/blob/main/assets/Resume%20-%20evankennedy52.pdf).

## 🎓 Education

**University of Maryland, College Park**
- M.S. in Applied Machine Learning (2025–2027)
- B.S. in Computer Science (2022–2025)

## 💻 Technical Skills

**Languages:** 

*Proficient:* Python, R, C, C#, Java

*Familiar:* Rust, HTML, VBA

**ML & Data Science:** regression, gradient-boosted trees (XGBoost), cross-validation, hyperparameter tuning (Optuna), exploratory analysis, data cleaning & feature engineering

**Libraries:** pandas, NumPy, scikit-learn, PyTorch, tidyverse, ggplot2

**Tools:** Git, Docker, Linux, SQL, Jupyter Notebooks, AWS, ClearML

## 📫 Connect With Me

- [LinkedIn](https://www.linkedin.com/in/evankennedy52)
- [Email](mailto:evankennedy5237@gmail.com)
- [Resume (PDF)](https://github.com/evankennedy-52/evankennedy-52.github.io/blob/main/assets/Resume%20-%20evankennedy52.pdf)
