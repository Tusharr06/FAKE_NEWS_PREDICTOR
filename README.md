
# Fake News Predictor

This project is a machine learning model that predicts whether a given news article is fake or real. The model is built using Python and various machine learning libraries.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Tusharr06/FAKE_NEWS_PREDICTOR.git
    cd FAKE_NEWS_PREDICTOR
    ```
## Usage

1. Download the dataset and place it in the project directory.

2. Run the Jupyter Notebook to preprocess the data, train the model, and evaluate it:
    ```bash
    jupyter notebook
    ```

3. Open the notebook `fake_news_predictor.ipynb` and run the cells sequentially.
   
## Dataset

The dataset used in this project is a collection of news articles labeled as fake or real. The dataset should be in CSV format with the following columns:
- `author`: The author of the news article.
- `title`: The title of the news article.
- `text`: The content of the news article.
- `label`: The label indicating whether the news is fake (1) or real (0).

## Model

The model used in this project is a Logistic Regression classifier. The text data is preprocessed using techniques such as stemming and stopword removal, and then transformed into TF-IDF features.

## Results

The performance of the model is evaluated using accuracy score. The results are displayed in the notebook.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
