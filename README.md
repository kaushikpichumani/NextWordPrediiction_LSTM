<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Next Word Prediction App</title>
</head>
<body>

    <h1>Next Word Prediction App</h1>

    <section>
        <h2>Description</h2>
        <p>
            This application uses a TensorFlow-based deep learning model to predict the next word in a given sentence. 
            It provides implementations using both LSTM and GRU architectures. 
            Users can input a sentence via a Streamlit interface, and the app will return the predicted next word.
        </p>
    </section>

    <section>
        <h2>Technologies Used</h2>
        <ul>
            <li>Python</li>
            <li>TensorFlow</li>
            <li>Streamlit</li>
            <li>LSTM (Long Short-Term Memory)</li>
            <li>GRU (Gated Recurrent Unit)</li>
        </ul>
    </section>

    <section>
        <h2>Setup Instructions</h2>
        <p>
            To run this application, please follow these steps:
        </p>
        <ol>
            <li>Clone the repository to your local machine.</li>
            <li>Ensure you have Python installed.</li>
            <li>Install the required Python packages. You can typically do this by running:
                <pre><code>pip install streamlit tensorflow</code></pre>
                (You might need to install other dependencies as well, check the requirements.txt if present)
            </li>
        </ol>
    </section>

    <section>
        <h2>Usage</h2>
        <p>
            To start the application, navigate to the repository directory in your terminal and run:
        </p>
        <pre><code>streamlit run app.py</code></pre>
        <p>
            The Streamlit app will open in your web browser. You can then enter a sentence in the input field to get the next word prediction.
        </p>
    </section>

    <section>
        <h2>Model Information</h2>
        <p>
            This repository contains the trained model files and word embeddings for both LSTM and GRU implementations. 
            The models were trained using TensorFlow.
        </p>
    </section>

    <section>
        <h2>Repository Contents</h2>
        <ul>
            <li><code>app.py</code>: The Streamlit application file.</li>
            <li><code>models/</code>: Directory containing the trained model files.</li>
            <li><code>embeddings/</code>: Directory containing the word embedding files.</li>
            <li>(Other relevant files/directories)</li>
        </ul>
    </section>

    </body>
</html>