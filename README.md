## AI-Powered Virtual Try-On & Outfit Recommendation System
## Project Overview
## Objective
To develop an AI-driven platform that allows users to virtually try on clothing items and receive personalized outfit recommendations. The system aims to bridge the gap between online shopping and physical retail experiences, reducing return rates and enhancing customer satisfaction.
## Key Features
Virtual Try-On: Users can upload photos or use live video to see how outfits look on them.Personalized Recommendations: AI suggests clothing based on user preferences, body shape, and fashion trends.Integration with E-commerce Platforms: Connect with online stores for real-time inventory updates.Social Media Integration: Users can share their try-on experiences online.

## More description about project and which technology we will use in our project are discribe in above outfitrecommedation.pdf and word file.

## currently we have Done AI chatbot which we will use in our system for communication between our help team and customer.
by using following step you can download AI chatbot and review it.

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

## UI
![chatbot1](https://github.com/user-attachments/assets/5dcda3f0-1a54-4ca8-b617-0e870ad5fce0)

