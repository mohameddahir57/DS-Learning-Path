# DS Learning Path

## About This Course
This repository documents the Data Science learning journey of **Me** and **Halimo Nur Ibrahim**, two graduates with a background in Computer Applications, Software Engineering, and Full-Stack Development. Having already built a solid foundation in Excel, Power BI, Tableau, SQL, and Python through prior academic and professional work, we set out to extend that foundation into data science with the goal of building machine learning and AI models and integrating them into real, deployable products such as websites, mobile applications, and chatbots. The course follows a structured Lesson Day → Off Day rhythm, progressing from core fundamentals through to a fully deployed capstone project.

## Full Toolkit (Beginner → Advanced)

### Beginner Foundations
- Python
- Jupyter Notebook / Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Excel (already known)
- SQL MySQL (already known)
- Git & GitHub

### Intermediate Statistics & ML
- SciPy
- Statsmodels
- Scikit-learn
- Plotly
- Power BI / Tableau (already known)
- XGBoost / LightGBM
- Kaggle (practice platform)

### Advanced Deep Learning, NLP, Deployment
- PyTorch (primary deep learning framework) / TensorFlow (alternative)
- Keras (if using TensorFlow)
- Hugging Face Transformers
- OpenCV (only if specializing in Computer Vision)
- NLTK / spaCy
- FastAPI (primary) / Flask (alternative)
- Docker
- AWS (primary cloud target) / GCP / Azure
- Render / Railway / Vercel (lightweight deployment for practice)
- MLflow
- Streamlit / Gradio (quick demo UIs)

### Supporting Tools (used throughout)
- VS Code
- Anaconda
- Postman
- Notion / Google Docs (for your own personal notes)
- Claude/ChatGPT (for debugging help used to learn, not just copy)


## PHASE 1 Python for Data Science + Statistics (Weeks 1–4)

### Week 1 Python & NumPy Refresh
**Lesson Day 1:** Python refresh for Data Science data types recap (lists, dicts, tuples, sets), list comprehensions, lambda functions, working with Jupyter/Colab notebooks
- Exercise: Write 5 list comprehensions (e.g., filter even numbers, square a list) + 3 lambda functions used with `map()`/`filter()`

**Lesson Day 2:** NumPy basics what NumPy is and why it's faster than plain Python lists, creating arrays (1D, 2D, 3D), indexing & slicing, reshaping arrays
- Exercise: Create a 2D array (matrix), practice slicing rows/columns, reshape a 1D array of 12 numbers into a 3x4 matrix

**Lesson Day 3:** NumPy operations vectorized operations (why loops are inefficient in NumPy), broadcasting, aggregate functions (`sum()`, `mean()`, `std()`, `min()`, `max()`), boolean masking/filtering
- Exercise: Given a sales array, calculate mean and std, then filter values above average using boolean masking — no loops allowed

**Lesson Day 4:** NumPy applied random number generation (`np.random`), combining/stacking arrays (`concatenate`, `vstack`, `hstack`), linear algebra basics (dot product, matrix multiplication), review of Days 1–3
- Exercise (Mini Challenge): Simulate 100 random "test scores" using `np.random`, calculate mean and std, filter students who "passed" (score > 60) vectorized only, no loops


### Week 2 Pandas Mastery
**Lesson Day 1:** Pandas basics Series vs DataFrame, reading CSV/Excel, `.head()`, `.info()`, `.describe()`
- Exercise: Load a Kaggle dataset and explore its structure

**Lesson Day 2:** Data selection & filtering `.loc`, `.iloc`, conditional filtering, sorting
- Exercise: Filter rows based on 2–3 conditions on a real dataset

**Lesson Day 3:** Data cleaning handling missing values (`fillna`, `dropna`), duplicates, data type conversion
- Exercise: Take a "dirty" dataset and fully clean it

**Lesson Day 4:** GroupBy & merging `.groupby()`, aggregations, `merge()`, `concat()`, pivot tables
- Exercise (Mini Challenge): Group a sales dataset by category and calculate total/average sales, then merge with a second dataset (e.g., product info)


### Week 3 Visualization + Descriptive Statistics
**Lesson Day 1:** Matplotlib basics line, bar, histogram, scatter plots
- Exercise: Plot 4 different chart types from a dataset

**Lesson Day 2:** Seaborn & Plotly prettier statistical plots, heatmaps, pairplots, interactive charts
- Exercise: Create a heatmap of correlations + an interactive Plotly chart

**Lesson Day 3:** Descriptive statistics — mean, median, mode, variance, standard deviation, distributions
- Exercise: Calculate all descriptive stats manually, then verify with `.describe()`

**Lesson Day 4:** Full EDA (Exploratory Data Analysis) combining visualization + statistics into one analysis
- Exercise (Mini Challenge): Full EDA report on a dataset visuals + stats + written observations


### Week 4  Probability & Hypothesis Testing
**Lesson Day 1:** Probability basics probability rules, conditional probability, distributions (normal, binomial)
- Exercise: Solve 5 probability problems + plot a normal distribution

**Lesson Day 2:** Hypothesis testing null/alternative hypothesis, p-values, t-tests
- Exercise: Run a t-test comparing two groups in a dataset

**Lesson Day 3:** Confidence intervals & significance what "95% confidence" actually means, Type I/II errors
- Exercise: Calculate a confidence interval and interpret it

**Lesson Day 4:** A/B testing fundamentals + Phase 1 wrap-up
- Exercise (🔹 **Mini Project 1**): Design a mock A/B test AND complete a full EDA report on a dataset of your choice — combining everything from Weeks 1–4


## PHASE 2 Machine Learning Core (Weeks 5–9)

### Week 5 ML Foundations
**Lesson Day 1:** Scikit-learn setup, train/test split, intro to supervised learning
- Exercise: Split a dataset into train/test and explore Scikit-learn's API

**Lesson Day 2:** Linear Regression theory + implementation
- Exercise: Predict house prices using linear regression

**Lesson Day 3:** Logistic Regression theory + implementation
- Exercise: Classify a binary outcome dataset (e.g., pass/fail, churn/no churn)

**Lesson Day 4:** Comparing regression models, review of Week 5
- Exercise (Mini Challenge): Compare linear vs logistic regression results on two different datasets


### Week 6  Tree-Based Models
**Lesson Day 1:** Decision Trees how they split data, visualizing a tree
- Exercise: Build and visualize a decision tree on a dataset

**Lesson Day 2:** Random Forests ensemble learning concept
- Exercise: Compare Random Forest accuracy vs a single Decision Tree

**Lesson Day 3:** Model evaluation metrics accuracy, precision, recall, F1-score, ROC-AUC
- Exercise: Evaluate 3 different models on the same dataset using all metrics

**Lesson Day 4:** Review + mini challenge
- Exercise (Mini Challenge): Compare tree-based model vs logistic regression on a classification dataset, report which performs better and why


### Week 7 Model Optimization
**Lesson Day 1:** Cross-validation k-fold CV, why train/test split alone isn't enough
- Exercise: Apply k-fold cross-validation to a model

**Lesson Day 2:** Hyperparameter tuning GridSearchCV, RandomizedSearchCV
- Exercise: Tune a Random Forest's hyperparameters

**Lesson Day 3:** Overfitting/underfitting, regularization Ridge, Lasso
- Exercise: Take an overfit model and fix it using regularization

**Lesson Day 4:** Review + mini challenge
- Exercise (Mini Challenge): Take a poorly performing model, diagnose whether it's overfitting or underfitting, and fix it


### Week 8 Feature Engineering & Unsupervised Learning
**Lesson Day 1:** Feature engineering creating new features, encoding categorical variables (one-hot, label encoding)
- Exercise: Engineer 3 new features from a raw dataset

**Lesson Day 2:** K-Means Clustering theory + implementation
- Exercise: Segment customer data into clusters

**Lesson Day 3:** PCA (Principal Component Analysis) basics dimensionality reduction
- Exercise: Reduce a high-dimensional dataset to 2D and visualize it

**Lesson Day 4:** Review + mini project
- Exercise (Mini Challenge): Full customer segmentation project clean data, engineer features, cluster, and visualize results


### Week 9 Boosting & AutoML
**Lesson Day 1:** XGBoost gradient boosting theory + implementation
- Exercise: Train an XGBoost model and compare to Random Forest

**Lesson Day 2:** LightGBM faster boosting alternative
- Exercise: Train a LightGBM model, compare speed/accuracy to XGBoost

**Lesson Day 3:** AutoML tools overview how automated model selection works
- Exercise: Run an AutoML tool on a dataset and compare results to your manual models

**Lesson Day 4:** Phase 2 wrap-up
- Exercise (🔹 **Mini Project 2**): Build a full ML pipeline raw data → cleaned → feature engineered → model trained → evaluated → best model selected


## PHASE 3 Specialization Intro (Weeks 10–12)

### Week 10 Time Series
**Lesson Day 1:** Time series concepts trend, seasonality, stationarity
- Exercise: Plot and identify trend/seasonality in a real time series dataset

**Lesson Day 2:** Moving averages & smoothing techniques
- Exercise: Apply moving average smoothing to noisy data

**Lesson Day 3:** ARIMA basics forecasting model fundamentals
- Exercise: Fit a basic ARIMA model

**Lesson Day 4:** Review + mini challenge
- Exercise (Mini Challenge): Forecast sales or demand data for the next period using what you've learned


### Week 11 NLP Basics
**Lesson Day 1:** Text preprocessing tokenization, stemming, lemmatization (NLTK/spaCy)
- Exercise: Preprocess a batch of raw text data

**Lesson Day 2:** Bag of Words & TF-IDF turning text into numbers
- Exercise: Convert a text dataset into TF-IDF features

**Lesson Day 3:** Sentiment analysis basics
- Exercise: Build a basic sentiment classifier on product/movie reviews

**Lesson Day 4:** Review + mini challenge
- Exercise (Mini Challenge): Full sentiment analysis pipeline — raw text → preprocessed → classified → evaluated


### Week 12 — Intro to Deep Learning
**Lesson Day 1:** Neural network fundamentals — neurons, layers, activation functions, forward pass
- Exercise: Manually calculate a forward pass through a tiny neural network

**Lesson Day 2:** PyTorch basics tensors, autograd
- Exercise: Create and manipulate tensors in PyTorch

**Lesson Day 3:** Building & training a simple neural network
- Exercise: Train a small neural net on a simple dataset

**Lesson Day 4:** Review + mini challenge
- Exercise (Mini Challenge): Build a simple neural network from scratch and train it end-to-end


## PHASE 4  Building Real AI Products (Weeks 13–15)

### Week 13 Chatbots & Hugging Face
**Lesson Day 1:** Hugging Face Transformers intro pre-trained models overview
- Exercise: Load and run a pre-trained model from Hugging Face

**Lesson Day 2:** Building a basic chatbot/Q&A model
- Exercise: Build a simple Q&A bot using a pre-trained model

**Lesson Day 3:** Model explainability — SHAP/LIME
- Exercise: Explain a model's predictions using SHAP

**Lesson Day 4:** Review + mini challenge
- Exercise (Mini Challenge): Build and explain a chatbot response model end-to-end


### Week 14 APIs & Connecting Your Model
**Lesson Day 1:** FastAPI basics turning a trained model into an API endpoint
- Exercise: Wrap a simple model in a FastAPI endpoint

**Lesson Day 2:** Postman testing your API requests/responses
- Exercise: Test your FastAPI endpoint with Postman

**Lesson Day 3:** Connecting model API to a simple frontend
- Exercise: Build a basic web form that sends data to your API and displays the result

**Lesson Day 4:** Review + mini challenge
- Exercise (Mini Challenge): Full working demo model → API → web form, all connected


### Week 15 Deployment
**Lesson Day 1:** Docker basics containerizing your application
- Exercise: Write a Dockerfile for your model API

**Lesson Day 2:** Deploying to Render/Railway (practice deployment)
- Exercise: Deploy your API to Render or Railway

**Lesson Day 3:** Deploying to AWS (real-world deployment)
- Exercise: Deploy the same API to AWS

**Lesson Day 4:** Streamlit/Gradio for quick demos + review
- Exercise (Mini Challenge): Build a Streamlit/Gradio demo of your model and deploy it live with a public link


## PHASE 5 Capstone Project (Weeks 16–17)

### Week 16 Capstone Build
**Lesson Day 1:** Choose your capstone project (chatbot app / prediction dashboard with Power BI + ML / recommendation system), plan the architecture
- Exercise: Write out the full architecture plan (data → model → API → frontend)

**Lesson Day 2:** Build & train the core model
- Exercise: Complete model training and evaluation for the capstone

**Lesson Day 3:** Build the API layer
- Exercise: Wrap the capstone model in a FastAPI endpoint

**Lesson Day 4:** Build the frontend and connect all pieces
- Exercise: Connect frontend → API → model, test end-to-end


### Week 17 Capstone Finish & Portfolio
**Lesson Day 1:** Deploy the full application
- Exercise: Get the capstone live with a public link

**Lesson Day 2:** Testing & debugging
- Exercise: Stress-test the app, fix bugs, polish edge cases

**Lesson Day 3:** GitHub repository + README polish
- Exercise: Push the full project to GitHub with a professional README

**Lesson Day 4:** Final review + next-step planning
- Exercise: Reflect on the full journey, identify which specialization (ML Engineering, NLP, Computer Vision, Time Series, Analytics Engineering) to go deeper into next



