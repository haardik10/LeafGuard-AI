# LeafGuard-AI
This project is a deep learning-powered web application that helps identify plant leaf diseases from images. Using a Convolutional Neural Network (CNN) model built with TensorFlow/Keras, the system classifies leaves into multiple categories (healthy or diseased) and provides information about the cause and suggested cure.

The app is built with Flask for the backend and provides a simple web interface for users to upload leaf images. Once uploaded, the model predicts the disease and displays:

📸 The uploaded image

🏷️ Predicted disease name

🧪 Cause (e.g., fungal infection)

💊 Suggested cure/remedy

🚀 Features

Upload a plant leaf image and get instant disease predictions.

Pre-trained deep learning model for accurate classification.

JSON-powered disease database with causes & treatments.

Clean Flask-based backend with Bootstrap-styled frontend.

🛠️ Tech Stack

Python (Flask, TensorFlow, NumPy)

HTML/CSS/Bootstrap (frontend UI)

TensorFlow/Keras (deep learning model)

📂 Project Structure
├── app.py                # Flask backend
├── models/               # Trained model (.keras file)
├── static/               # CSS, JS, images
├── templates/            # HTML templates
├── uploadimages/         # Uploaded images (runtime)
├── plant_disease.json    # Disease info (cause + cure)
└── README.md             # Project documentation

⚡ How to Run
# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py


Then open: http://127.0.0.1:5000/
