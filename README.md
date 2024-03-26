# Chatbot Project

This project is a simple chatbot implemented using Python, Flask, Keras, NLTK, and JSON. The chatbot is capable of understanding and responding to predefined intents based on user input.

## Project Structure

- **App.py**: Contains the Flask application setup along with the chatbot logic.
- **data.json**: Contains the intents for the chatbot, including tags, patterns, and responses.
- **labels.pkl and texts.pkl**: Store the preprocessed data (words and classes) using pickle.
- **model.h5**: Stores the trained neural network model using Keras.
- **training.ipynb**: Jupyter Notebook used for data preprocessing, model training, and saving the trained model.
- **static/style.css**: Contains the CSS styles for the chatbot interface.
- **templates/index.html**: Contains the HTML structure for the chatbot interface.

## Technologies Used

- **Python**: Programming language used for the backend logic.
- **Flask**: Web framework used for building the web application.
- **Keras**: Deep learning library used for building and training the neural network model.
- **NLTK**: Natural language processing library used for text preprocessing.
- **JSON**: Data format used for storing intents and responses.
- **HTML/CSS**: Used for the frontend interface of the chatbot.

## Usage

1. Install the required libraries using `pip install -r requirements.txt`.
2. Run the Flask application using `python app.py`.
3. Open your web browser and navigate to `http://localhost:5000` to access the chatbot interface.
