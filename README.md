# Fake News Detection Using Machine Learning

This project aims to build a machine learning model to detect fake news. The model is trained on a dataset of news articles, labeled as either "real" or "fake". The goal is to accurately classify new, unseen articles as either real or fake.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this project, you need to have Python and Jupyter Notebook installed. You can install the required libraries using pip:

```bash
pip install numpy pandas sklearn
```

## Usage

1. Clone this repository to your local machine.
2. Open the `fake_news_detection.ipynb` file in Jupyter Notebook.
3. Run the cells in the notebook to train the model and see the results.

## Dataset

The dataset used in this project is `news.csv`. It contains a collection of news articles, with each article labeled as either "REAL" or "FAKE". The dataset has the following columns:

- `Unnamed: 0`: An unnecessary index column.
- `title`: The title of the news article.
- `text`: The content of the news article.
- `label`: The label indicating whether the news is "REAL" or "FAKE".

## Model

The model used in this project is a simple machine learning model, likely a TfidfVectorizer and a PassiveAggressiveClassifier. The model is trained on the `news.csv` dataset and evaluated on its accuracy in classifying fake news.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
