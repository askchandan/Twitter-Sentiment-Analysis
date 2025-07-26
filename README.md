# Twitter-Sentiment-Analysis

This repository contains a project for performing sentiment analysis on Twitter data. It includes a Jupyter Notebook for model development, a trained model for sentiment prediction, and a Flask application for deployment.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)
- [License](#license)
- [Contributing](#contributing)

## Introduction

This project aims to analyze the sentiment of tweets related to specific topics or keywords. By leveraging machine learning techniques, it can classify tweets as positive, negative, or neutral, providing valuable insights into public opinion and trends.

## Features

- **Sentiment Analysis**: Predicts the sentiment of tweets.
- **Trained Model**: Includes a pre-trained model for immediate use.
- **Flask App**: Provides a simple web interface for sentiment analysis.

## Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/askchandan/Twitter-Sentiment-Analysis.git
    cd Twitter-Sentiment-Analysis
    ```

2.  **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  **Run the Flask app:**

    ```bash
    python app.py
    ```

2.  **Access the app in your browser**

    Open your web browser and go to `http://127.0.0.1:5000/` to use the sentiment analysis tool.

## Files

-   `app.py`: Flask application for running sentiment analysis.
-   `twitter_sentiment_analysis.ipynb`: Jupyter Notebook containing the model development and analysis.
-   `trained_model.sav`: Serialized trained machine learning model.
-   `vectorizer.sav`: Serialized vectorizer for text processing.
-   `requirements.txt`: List of Python dependencies.
-   `LICENSE`: License information.
-   `kaggle.json`: API key for Kaggle.
-   `.gitignore`: Specifies intentionally untracked files that Git should ignore.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please read the [contributing guidelines](docs/CONTRIBUTING.md) to get started.
