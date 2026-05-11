# News Sentiment Analysis

This repository supports the Nova Financial Solutions challenge: linking financial news sentiment with stock price behavior.

## Branch

Work for Task 1 is on branch `task-1`.

## Project Structure

- `.github/workflows/unittests.yml`: CI pipeline
- `notebooks/task1_eda.ipynb`: Task 1 EDA notebook
- `Data/`: historical stock price CSV files
- `newsData/raw_analyst_ratings.csv`: financial headline data

## Quick Start

1. Create and activate a virtual environment.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Launch Jupyter:

```bash
jupyter notebook
```

4. Open `notebooks/task1_eda.ipynb` and run all cells.

## Task 1 Coverage

The notebook includes:
- Text descriptive statistics (headline length distribution)
- Publisher activity analysis (top publishers and domain extraction)
- Publication date/time trends and spike detection
- Keyword and topic exploration via CountVectorizer, TF-IDF, and simple LDA
- At least three visualizations to support insights

## Notes

The notebook reads data from `../newsData/raw_analyst_ratings.csv` relative to the notebook directory.
