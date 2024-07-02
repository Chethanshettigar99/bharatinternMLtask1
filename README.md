#HOUSE PRICE PREDICTION

size, and zip code. It loads a dataset and a pre-trained Ridge regression model. The main page (index.html) displays dropdown menus populated with unique values from the dataset. When the user submits the form, the app processes the input data, handles any unknown categories, and predicts the price using the model. The app runs on localhost at port 5000 in debug mode.
Flask Framework: Utilizes Flask to create a web application for predicting real estate prices.

key points
Data Handling: Loads a CSV dataset (final_dataset.csv) and a pre-trained Ridge regression model (RidgeModel.pkl) using Pandas and Pickle, respectively.

Dynamic Form Population: Extracts unique values from the dataset to populate dropdown menus in the HTML form for bedrooms, bathrooms, sizes, and zip codes.

Input Processing: Processes form inputs, converts data types as needed, and handles unknown categories by replacing them with the most frequent value from the dataset.

Prediction: Uses the pre-trained Ridge regression model to predict and return the price based on the processed input data.

Debug Mode: Runs the Flask app in debug mode on localhost at port 5000 for easy development and testing.
