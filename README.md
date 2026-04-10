
🎬 IMDB Sentiment Analysis: From Word2Vec to RNN
A Complete NLP Pipeline ()
This repository features a comprehensive Python notebook that demonstrates the full lifecycle of a Sentiment Analysis project. By using Word2Vec for semantic embeddings and a Recurrent Neural Network (RNN) for sequence modeling, this project predicts whether movie reviews are positive or negative.

🚀 What's Inside?
The included Sentiment_Analysis.ipynb file is a self-contained environment that covers:

Data Acquisition: Loading the IMDB movie review dataset.

Text Preprocessing: Tokenization, cleaning, and sequence padding.

Feature Engineering: Training a custom Word2Vec model to capture the relationship between words.

Deep Learning Architecture: Building an RNN with a custom embedding layer.

Inference: A live prediction function to test real-world sentences.

🛠️ Technical Stack
Language: Python 3.10+

Deep Learning: TensorFlow / Keras

Natural Language Processing: Gensim (Word2Vec)

Analysis: NumPy, Pandas, Matplotlib

🧠 Model Logic
Instead of relying on simple word counts, this model understands context.

The Word2Vec model converts words into 100-dimensional vectors.

These vectors are passed into a SimpleRNN layer that reads the review word-by-word, maintaining a hidden state to understand the sequence.

A final Sigmoid layer outputs a probability score (0 to 1).

📊 Sample Performance
The notebook includes live tests where the model successfully identified:

Positive Sentiment: "The cinematography was sublime and the acting was superb."

Negative Sentiment: "It was a complete waste of time and very boring."

⚙️ How to Run
Since this repository focuses on the code, you can run the entire project in minutes:

Open the Sentiment_Analysis.ipynb file in Google Colab or Jupyter Notebook.

Run the cells in order. The notebook will automatically download the necessary datasets and train the model locally in your session.

No external model files are required—the code generates everything!

📈 Future Roadmap
LSTM Upgrade: Transitioning from SimpleRNN to Long Short-Term Memory units to improve memory for longer reviews.

Bidirectional Processing: Updating the architecture to read text in both directions for better context.
