A machine learning project to detect Indonesian-language YouTube comments related to online gambling using a IndoBERT model.

## How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/HAJAR-Enterprise/ML-Repo.git
cd ML-Repo
```

### 2. Install Requirements
```bash 
pip install -r requirements.txt
```

### 3. Run the Notebooks
Open and run the notebooks in the following order:
- youtube_comment_scraper.ipynb → to scrape YouTube comments
- data_preprocessing.ipynb → to clean and preprocess data
- modelling.ipynb → to train and evaluate the model

## Evaluation Summary
- Model Accuracy: 99%
- F1-Score: 0.99
- Dataset Size: ~15,000 Indonesian comments
- Can detect disguised or symbol-altered gambling terms automatically

### Note
youtube_comment_scraper.ipynb once accidentally included API credentials (now removed).
Always use .env files and add them to .gitignore to protect sensitive data.
