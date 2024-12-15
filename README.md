Ecco il README e una descrizione per il progetto del tuo secondo script in un Jupyter Notebook.

---

## README

### Sentiment Analysis on IMDB Reviews Using LSTM

#### Project Overview

This project builds a sentiment analysis model to classify IMDB reviews as positive or negative. Using TensorFlow/Keras and NLP preprocessing techniques, the pipeline converts raw text into padded sequences and trains an LSTM-based neural network for accurate sentiment classification.

#### Features

- 📄 **Data Preprocessing**: 
  - Cleans raw text data by removing HTML tags and punctuation.
  - Tokenizes and pads sequences to prepare input for the neural network.
  
- 🧠 **LSTM Model**: 
  - Implements an LSTM-based architecture with embedding, pooling, and dropout layers for robust text feature extraction and sentiment prediction.

- 📊 **Performance Evaluation**: 
  - Splits the test set into validation and evaluation datasets for detailed performance metrics.

- 📝 **Manual Sentiment Testing**:
  - Includes sample reviews to test the model’s predictions interactively.

#### Requirements

##### Libraries

Install the required Python libraries with:

```bash
pip install tensorflow pandas
```

##### Data

The project uses the **IMDB Dataset of 50K Movie Reviews**, which must be saved locally as `IMDB Dataset.csv`. Ensure the dataset is placed under the appropriate path: `../Data/archive/IMDB Dataset.csv`.

#### Usage

1. 📂 Clone the repository and navigate to the project directory:

   ```bash
   git clone https://github.com/username/sentiment-analysis-lstm.git
   cd sentiment-analysis-lstm
   ```

2. 📁 Place the `IMDB Dataset.csv` file in the directory `../Data/archive/`.

3. ▶️ Open the `sentiment_analysis.ipynb` notebook in Jupyter and execute the cells step by step.

4. 🔍 Evaluate the model on test data and test it with manual reviews for predictions.

---

## Example

### Input

Sample review:  
*`"This movie is fantastic! I really enjoyed it and I would recommend it to everyone!"`*

### Output

Predicted sentiment: **Positive**

---

### Limitations

- ⚠️ Model performance depends on the quality and diversity of the training data.
- ⚠️ Manual tuning may be required for non-English reviews or different text formats.

---

#### Short Description (for GitHub)

This project uses TensorFlow and Keras to build an LSTM-based sentiment analysis model for classifying IMDB reviews. It includes data preprocessing, model training, evaluation, and interactive testing with sample reviews.
