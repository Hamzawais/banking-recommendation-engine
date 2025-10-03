# Recommendation Engine (Banking)

This project builds a recommendation engine to suggest banking products to customers based on interaction history and profile features.  
It includes a Jupyter Notebook for experiments and a Python script for application logic.

## Project Contents
- **recommendation_ml.ipynb** — Main notebook: data exploration, candidate generation, model training and evaluation.  
- **recommend_app.py** — Python script for recommendation app/config logic.  
- **requirements.txt** — Dependencies required to run the notebook.  
- **SPLIT_GUIDE.md** — Notes for mapping files from the original bundle into this repo.

## Features
- Baseline methods: Popularity and association rules  
- Content‑based or collaborative filtering approaches  
- Feature engineering for customer/product profiles  
- Evaluation metrics: Precision@K, Recall@K, MAP  

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
```
Open and run `recommendation_ml.ipynb`. Update any input paths as needed.

## Notes
- Include only anonymized sample data (or link to external data).  
- For quick demo, prepare a small sample interactions dataset (`user_id,item_id,timestamp`).  
