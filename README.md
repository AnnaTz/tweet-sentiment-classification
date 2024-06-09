
This project aims to perform sentiment analysis on tweets about Dell's products and services. Utilizing the advanced features of XLNet, we aim to accurately classify sentiments as positive, negative, or neutral. This kind of analysis is a crucial aspect of understanding customer feedback and adjusting business strategies accordingly. 

## Key Features

- **Data Preprocessing**: Includes cleaning of tweets to remove noise like emojis, URLs, mentions, and non-ASCII characters.
- **Exploratory Data Analysis (EDA)**: Visualizes the dataset's characteristics, such as sentiment distribution, word and sentence lengths, common stopwords, named entity recognition, and part-of-speech tagging.
- **Deep Learning Model**: Utilizes the pre-trained XLNet model for sentiment classification, with fine-tuning to adapt to our specific dataset.
- **Hyperparameter Tuning**: Employs Ray Tune for optimizing model parameters, ensuring the best possible performance.
- **Evaluation**: Assesses model accuracy, F1 scores, and provides a confusion matrix to understand prediction quality.

## Getting Started

### Prerequisites

To run this project, ensure you have the following installed:
- Python 3.8 or newer
- Relevant Python packages as listed in `requirements.txt`

### Installation

To set up the project environment:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/AnnaTz/tweet-sentiment-classification
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
### Running the Project

Navigate to the project directory and launch the Jupyter notebook:
```
jupyter notebook sentiment_classification.ipynb
```

## References

- The XLNet model was proposed in [XLNet: Generalized Autoregressive Pretraining for Language Understanding](https://arxiv.org/abs/1906.08237) by Yang, Z., Dai, Z., Yang, Y., Carbonell, J., Salakhutdinov, R., & Le, Q. V.
- The dataset used for this project is sourced from Kaggle: [Sentiment and Emotions of Tweets](https://www.kaggle.com/datasets/ankitkumar2635/sentiment-and-emotions-of-tweets).
