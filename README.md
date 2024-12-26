 ReelFeel: Sentiment Analysis of Movie Reviews with RNN

Welcome to ReelFeel, a deep learning project designed to analyze sentiments in movie reviews using Recurrent Neural Networks (RNN). This project leverages natural language processing techniques to interpret and classify emotions expressed in movie reviews, helping in understanding public perception and sentiment trends towards films.

## Project Overview

ReelFeel utilizes RNNs, specifically designed to work with sequence data, to predict the sentiment (positive or negative) expressed in textual movie reviews. This approach can be particularly useful for filmmakers, critics, and marketers to gauge audience reactions and tailor their strategies accordingly.

## Project Structure

- embedding.ipynb: Explores word embeddings and their preparation for RNN models.
- simplernn.ipynb: Notebook detailing the development and training of a simple RNN model for sentiment analysis.
- prediction.ipynb: Demonstrates how to use the trained RNN model to make predictions on new data.
- main.py: Main script for executing the model training and prediction pipeline.
- simple_rnn_imdb.h5: Saved model file containing the trained RNN.
- requirements.txt: Specifies all dependencies required to run the project.

## Installation

Clone this repository and navigate into the project directory:

```bash
git clone <repository-url>
cd raghuramg666-Sentiment-Analysis---Movie-Review-analysis-using-RNN-main
```

Install the necessary dependencies:

```bash
pip install -r requirements.txt
```

## Running the Project

To train the model and make predictions, run the following command:

```bash
python main.py
```

Alternatively, you can explore the Jupyter notebooks to understand the model training process and experiment with the predictions:

```bash
jupyter notebook simplernn.ipynb
```

