# FASEROH_Tests
Evaluation Tasks for ML4SCI 2025 FASEROH 

# Common Task 1. Dataset preprocessing 

Description: Use Sympy or Mathematica to generate datasets of functions with their Taylor expansions up the fourth order. Tokenize the dataset.

For details: [notebook](Data_Generation_Task_1.ipynb)

Dataset Generated: [Link](final_data_4999.csv)

I have used algorithm provided in [Lample et. al, 2019](https://arxiv.org/abs/1912.01412) to generate expressions and calculated taylor expansion of the generated expressions.

I have generated around 5000 samples.

# Common Task 2. Use LSTM model

Descprition: Train an LSTM model to learn the Taylor expansion of each function.
You can use a deep learning algorithm of your choice (in Keras/TF or Pytorch).

I have used LSTM in Encoder-Decoder fashion.

For details: [notebook](./LSTM.ipynb)

Model weights: [link](./model_weights/LSTM_checkpoint.pth)

Token Accuracy: `89.3705%` 

# Specific Task 3: Use Transformer model
Description: Please train a Transformer  model to learn the Taylor expansion of each function.

I have used a seq2seq transformer with 2 Encoder blocks and 6 decoder blocks.

For details: [notebook](Transformer.ipynb)

Model weights: [link](./model_weights/Transformer_checkpoint.pth)

Token Accuracy: `95.01%`

Final Sequence Accuracy: `63.33%`

# Contact

For any questions or issues regarding this repository, please contact `prasanthnaidu31k at gmail.com`

