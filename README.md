# Udacity Data Review
For the Data Scientist course on Udacity, this is the 'Write a data science blog post' project. I'm using Car Fuel & Emissions data: https://www.kaggle.com/mrmorj/car-fuel-emissions.

## About the data
I was interested in the data, because of the ongoing discussion regarding global warming and the emission of greenhouse gasses. And after taking a closer look at the data, there were a few interesting topics that could be addressed using the data.

- There's tax band labels assigned to the different cars. I'm wondering if it's possible to model these tax band labels using the data.
- Since the years are specified, it would be interesting to see how the environmental impact of cars have evolved during those years.
- It would be interesting to see which companies are ahead of behind in regard on their emissions.


# Project breakdown

- Notebooks
- Flash app
- Data: showing the first look at the raw data and then processing the data to enable modelling.

# Development

## Requirements:
- Python3, pip
- Kaggle account: https://www.kaggle.com

## Getting started
1. Clone project from GitHub: `git clone https://github.com/Schayik/u-data-science-blog-post.git`
2. Download data from Kaggle: https://www.kaggle.com/mrmorj/car-fuel-emissions
3. Unzip file and add **data.csv** to the data folder
4. Create virtual environment: `python -m venv .venv`
5. Activate virtual environment: `.venv/Scripts/activate`
6. Install dependencies: `pip install notebook pandas sqlalchemy matplotlib sklearn`
7. Open Jupyter Notebook: `jupyter notebook`
8. A page in your browser will open: http://localhost:8888/tree
9. Open **data-review.ipynb**

**Note**: I had some troubles with the notebook kernel showing this error: *FileNotFoundError: [WinError 2] The system cannot find the file specified*. I managed to fix it using `python -m ipykernel install --user` from this issue post answer: https://github.com/jupyter/notebook/issues/4079#issuecomment-429651480

## Next time setup
1. Activate virtual environment: `.venv/Scripts/activate`
2. Open Jupyter Notebook: `jupyter notebook`