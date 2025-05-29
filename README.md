<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Next Word Prediction App</title>
</head>
<body>
    <h1>Next Word Prediction App</h1>

    <p>This repository contains a Streamlit web application that predicts the next word in a given sentence. The application utilizes two different deep learning models for prediction: Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU).</p>

    <h2>Overview</h2>
    <p>The application allows users to input a sentence and select either the LSTM or GRU model to predict the subsequent word. The models have been pre-trained and their weights are saved in <code>.h5</code> files.</p>

    <h2>Key Features</h2>
    <ul>
        <li>Interactive Streamlit interface.</li>
        <li>Option to choose between LSTM and GRU models.</li>
        <li>Loads pre-trained models from <code>.h5</code> files.</li>
        <li>Predicts the next word based on the input sentence.</li>
    </ul>

    <h2>Repository Contents</h2>
    <ul>
        <li><code>app.py</code>: The main Streamlit application script.</li>
        <li><code>lstm_model.h5</code>: Pre-trained weights for the LSTM model.</li>
        <li><code>gru_model.h5</code>: Pre-trained weights for the GRU model.</li>
        <li><code>README.html</code>: This file, providing information about the application.</li>
        </ul>

    <h2>Setup and Installation</h2>
    <p>To run this application locally, ensure you have Python and pip installed. Follow these steps:</p>

    <ol>
        <li>Clone this repository:
            <pre><code>git clone &lt;repository_url&gt;</code></pre>
        </li>
        <li>Navigate to the repository directory:
            <pre><code>cd next-word-prediction-app</code></pre>
        </li>
        <li>Install the required Python libraries:
            <pre><code>pip install -r requirements.txt</code></pre>
            <p>*(Note: You might need to create a <code>requirements.txt</code> file listing dependencies like <code>streamlit</code>, <code>tensorflow</code> or <code>keras</code>, <code>numpy</code>, etc.)*</p>
        </li>
    </ol>

    <h2>Running the Application</h2>
    <p>Once the dependencies are installed, you can run the Streamlit application using the following command:</p>
    <pre><code>streamlit run app.py</code></pre>
    <p>This command will open the application in your web browser.</p>

    <h2>Usage</h2>
    <ol>
        <li>Enter a sentence in the text input field.</li>
        <li>Select either "LSTM" or "GRU" from the model selection dropdown.</li>
        <li>Click the "Predict" button.</li>
        <li>The predicted next word will be displayed below the button.</li>
    </ol>

    <h2>Model Details</h2>
    <ul>
        <li><b>LSTM Model:</b> A Long Short-Term Memory network trained for next word prediction. The model weights are stored in <code>lstm_model.h5</code>.</li>
        <li><b>GRU Model:</b> A Gated Recurrent Unit network, another type of recurrent neural network, also trained for next word prediction. The model weights are stored in <code>gru_model.h5</code>.</li>
        <li>*(Optional: You can add more details about the model architecture, training data, etc., if you wish.)*</li>
    </ul>

    <h2>Contributing</h2>
    <p>Contributions to this project are welcome. Please feel free to submit pull requests or open issues for any bugs or enhancements.</p>

    <h2>License</h2>
    <p>*(Add your license information here if applicable)*</p>

    <h2>Contact</h2>
    <p>*(Add your contact information here if you wish)*</p>

</body>
</html>