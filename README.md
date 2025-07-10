🏠 House Price Prediction App
This project is an end-to-end machine learning web app that predicts house prices based on user input. Built with Python, Flask, and Bootstrap, it includes a trained model, a stylish UI, and an optional cloud deployment setup (Render or Hugging Face).

📌 Features
Predicts house price based on:

Overall quality

Living area

Garage capacity and size

Basement area

Bathrooms

Year built

Fully responsive Bootstrap-based web form

Trained using Random Forest model

Local API with /predict endpoint

Option to deploy to Render or Hugging Face Spaces

📁 Project Structure
bash
Copy
Edit
house-price-predictor/
├── app.py                  # Flask app with HTML frontend
├── train_model.py          # Script to train and save the model
├── housing.csv             # Training dataset
├── house_model.pkl         # Trained model file
├── columns.pkl             # Feature columns file
├── requirements.txt        # Python dependencies
├── templates/
│   └── index.html          # Frontend Bootstrap form
├── render.yaml             # (Optional) For Render deployment

📦 Requirements
nginx
Copy
Edit
Flask
pandas
scikit-learn
joblib
gunicorn

👨‍💻 Author
Ritesh Biliangadi
