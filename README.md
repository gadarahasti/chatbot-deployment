# Chatbot Deployment with Flask and JavaScript

   This project is a simple AI chatbot deployed using Flask for the backend and JavaScript for the frontend. The chatbot interacts with users via a web interface and processes messages using a pre-trained AI model or custom logic.


## Features:

▪ Backend: Flask (Python) API for chatbot responses.

▪ Frontend: JavaScript & HTML for user interaction.

▪ REST API for communication between client and server.

▪ Simple and lightweight chatbot framework.

## Initial Setup:
This repo currently contains the starter files.

Clone repo and create a virtual environment
```
$ https://github.com/gadarahasti/chatbot-deployment.git
$ cd chatbot-deployment
$ python3 -m venv venv
$ . venv/bin/activate
```
Install dependencies
```
$ (venv) pip install Flask torch torchvision nltk
```
Install nltk package
```
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
```
Modify `intents.json` with different intents and responses for Chatbot

Run
```
$ (venv) python train.py
```
This will dump data.pth file. And then run
the following command to test it in the console.
```
$ (venv) python chat.py
```

## Project Structure:
```
/chatbot-flask-js
│── static/
│   ├── css/        # Stylesheets
│   ├── js/         # JavaScript files
│   ├── images/     # Assets
│── templates/
│   ├── index.html  # Frontend UI
│── app.py          # Flask backend
│── requirements.txt # Dependencies
│── README.md       # Project documentation
```

## License:

This project is licensed under the MIT License.







