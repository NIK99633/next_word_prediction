**Next Word Prediction using LSTM
**


Overview
This project builds a next word prediction model using TensorFlow and Keras. It reads a text file and predicts the next word in a given sentence.

Idea
The model learns patterns from text data and tries to complete a sentence based on previous words.

Example
Input: I will leave if they
Output: I will leave if they are coming

Steps in Code

1. Read Data
   Load text from sample_data.txt

2. Tokenization
   Convert words into numerical form

3. Create Sequences
   Generate sequences of words

4. Padding
   Make all sequences equal length

5. Prepare Data
   X contains input words
   y contains the next word

6. Build Model
   Embedding layer
   LSTM layer
   Dense layer with softmax

7. Train Model
   Model learns patterns from data

8. Prediction
   Model predicts next words for a given sentence

File Needed
sample_data.txt

How to Run
Install required libraries using pip install tensorflow numpy matplotlib
Run the program using python your_file.py

Output
Shows model summary
Generates predicted sentence

Note
Training part is commented in the code, so enable it before prediction
Better dataset gives better results

Conclusion
This project demonstrates how LSTM can be used for next word prediction in natural language processing

**use python version 3.10
**
