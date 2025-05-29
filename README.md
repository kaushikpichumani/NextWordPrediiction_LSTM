<!DOCTYPE html>
<html>
<head>
  <title>Next Word Predictor</title>
</head>
<body>
  <h1>🔮 Next Word Predictor</h1>
  <p>
    This repository hosts a <strong>Streamlit web application</strong> that predicts the <strong>next word</strong> of a given sentence using deep learning models built with <strong>LSTM</strong> and <strong>GRU</strong>.
  </p>

  <h2>📌 Features</h2>
  <ul>
    <li>Interactive Streamlit interface</li>
    <li>Choose between LSTM or GRU models</li>
    <li>Auto-suggests the next word in a sentence</li>
    <li>Lightweight and easy to deploy</li>
  </ul>

  <h2>🧠 Models Used</h2>
  <ul>
    <li><strong>LSTM</strong> - Long Short-Term Memory network</li>
    <li><strong>GRU</strong> - Gated Recurrent Unit</li>
  </ul>
  <p>
    The models are saved in <code>.h5</code> format and loaded at runtime.
  </p>

  <h2>📁 File Structure</h2>
  <pre>
├── app.py               # Streamlit app
├── lstm_model.h5        # LSTM model
├── gru_model.h5         # GRU model
├── tokenizer.pickle     # Tokenizer used during training
  </pre>

  <h2>🚀 How to Run</h2>
  <pre>
# Clone the repo
git clone https://github.com/your-username/next-word-predictor.git
cd next-word-predictor

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
  </pre>

  <h2>🖼️ Demo</h2>
  <p>
    Type a sentence and select a model. The app will suggest the most probable next word.
  </p>

  <h2>🛠 Requirements</h2>
  <ul>
    <li>Python 3.7+</li>
    <li>TensorFlow</li>
    <li>Streamlit</li>
    <li>Keras</li>
  </ul>

  <h2>📬 Contact</h2>
  <p>
    Created by <strong>Your Name</strong> – feel free to reach out!
  </p>

  <h2>⭐ Show Your Support</h2>
  <p>
    If you found this project helpful, please consider giving it a ⭐ on GitHub!
  </p>
</body>
</html>
