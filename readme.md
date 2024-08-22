```markdown
# Stock News Sentiment Analysis Using HuggingFace Models

This project performs sentiment analysis on financial news articles using three different Hugging Face models. The analysis predicts whether the sentiment of each news article is positive, negative, or neutral.

## Installation

To get started, clone the repository and install the required packages:

```bash
git clone https://github.com/SyedAffan10/Stock_News_Sentiment_Analysis_Using_HuggingFace_Models.git
cd Stock_News_Sentiment_Analysis_Using_HuggingFace_Models
```

### Installing Requirements

Make sure you have Python 3.7 or later installed. Install the necessary packages using pip:

```bash
pip install -r requirements.txt
```

## Usage

1. **Load the dataset**: Place your stock news dataset in the appropriate folder as defined in the project structure.
2. **Run the notebook**: Open the Jupyter notebook `code.ipynb` and run all cells to perform sentiment analysis on the news data.
3. **View the results**: The sentiment analysis results will be displayed in the notebook, including any visualizations generated.

## Model Accuracy

Based on the sample data used, the accuracy of each model is as follows:

- **[mrm8488/distilroberta-finetuned-financial-news-sentiment-analysis](https://huggingface.co/mrm8488/distilroberta-finetuned-financial-news-sentiment-analysis)**: 52%
- **[yiyanghkust/finbert-tone](https://huggingface.co/yiyanghkust/finbert-tone)**: 37%
- **[cardiffnlp/twitter-xlm-roberta-base-sentiment](https://huggingface.co/cardiffnlp/twitter-xlm-roberta-base-sentiment)**: 32%
```