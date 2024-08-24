

# Sentiment Analysis with SimpleTransformers on the IMDB Reviews Dataset

This project demonstrates how to perform sentiment analysis using the `SimpleTransformers` library, which is built on top of Hugging Face's `Transformers`. The goal is to classify movie reviews as positive or negative.

## Libraries Used

- **SimpleTransformers**: A high-level library that simplifies training and using transformer models.
- **Pandas**: Used for data manipulation and analysis.
- **Scikit-learn**: Utilized for splitting the dataset into training and evaluation sets.
- **Logging**: For tracking the training and evaluation process.

## Dataset

The dataset used for this project is the IMDB movie reviews dataset. It contains 50,000 reviews labeled as either positive or negative.

## Model

The model used in this project is based on the `RoBERTa` architecture, a robustly optimized version of BERT (Bidirectional Encoder Representations from Transformers). The model is fine-tuned on the IMDB dataset to classify movie reviews as positive or negative.

### Key Parameters

- **Model Type**: `roberta`
- **Pre-trained Model**: `roberta-base`
- **Number of Labels**: 2 (Positive, Negative)
- **Training Epochs**: 1

## Fine-Tuning

The fine-tuning process involves training the `RoBERTa` model on the IMDB dataset with a custom configuration. The dataset is split into training and evaluation sets, and the model is fine-tuned for one epoch to adapt it to the specific task of sentiment analysis.

## Evaluation

After fine-tuning, the model is evaluated on the test set to assess its performance in predicting the sentiment of movie reviews.

---

This template summarizes the key aspects of your project without including the code itself. You can expand on each section as needed.
