# Recommender System for Coursera Courses

Recommender System for Coursera Courses as part of the IBM Machine Learning Professional Certificate. In this project, several supervised and unsupervised machine learning algorithms like KNN, Logistic Regression, SVM, RandomForest, KMeans are employed to get new course recommendations for users.

The streamlit library is used as frontend.

## How to use
Simply clone this repo, setup a virtual environment and install the requirements:

```bash
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

Then, just start the streamlit app:

```bash
streamlit run PATH_TO_APP/recommender_app.py
```

in your CLI of choice to start the frontend in your default browser.
