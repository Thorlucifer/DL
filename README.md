# Facial Expression Recognition

This repository contains the code for a machine learning project that can identify and classify facial expressions from images.

## Project Overview

The project uses a convolutional neural network (CNN) model trained on a dataset of facial expressions to predict the emotion conveyed by the facial expressions in new images.

## Features

- Utilizes EfficientNet/VGG as the base for the transfer learning model.
- Implements a custom CNN model.
- Includes a Flask application for serving predictions over HTTP.
- Provides a simple web interface created with Streamlit for easy interaction with the model.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.8 or higher
- pip (Python package installer)

### Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/facial-expression-recognition.git

Navigate to the project directory:
cd facial-expression-recognition
Install the necessary Python packages:
pip install -r requirements.txt
Running the Model
Start the Flask server to serve the model:
python app.py
To use the Streamlit interface:
streamlit run streamlit_app.py

Usage
The Flask server will be available at http://127.0.0.1:5000, ready to accept POST requests with images for emotion prediction.

Alternatively, you can access the Streamlit interface at http://localhost:8501 for an interactive experience.

Contributing
Contributions to enhance this project are welcome! Please fork the repository and create a pull request with your suggested changes.

License
Distributed under the MIT License. See LICENSE for more information.

Contact
Name: Srinivasateja gandla
usernmae: Thorlucifer
Project Link: https://github.com/your-username/facial-expression-recognition
