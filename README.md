# Email Spam Detection 📧

A machine learning web application built with **Python, Django, and Scikit-learn** that classifies text messages as Spam or Ham (not spam).

## About the Project

Spam messages can contain unwanted advertisements, misleading offers, or potentially harmful links. This project uses Natural Language Processing (NLP) techniques and a machine learning model to identify whether a message is spam.

Users can enter a message through a web interface and receive a prediction.

## Technologies Used

- **Python** — Core programming language
- **Django** — Web application framework
- **Pandas** — Dataset handling
- **Scikit-learn** — Machine learning
- **CountVectorizer** — Converts text into numerical features
- **Multinomial Naive Bayes** — Spam classification algorithm
- **HTML/CSS** — Web interface

## How It Works

1. Load and process the labelled email dataset.
2. Convert text messages into numerical features using CountVectorizer.
3. Split the data into training and testing sets.
4. Train a Multinomial Naive Bayes classifier.
5. Accept a message from the user through the Django interface.
6. Predict whether the message is Spam or Ham.

## Project Structure

```text
email-spam-detection/
├── detector/
│   ├── templates/
│   ├── forms.py
│   ├── views.py
│   ├── models.py
│   └── urls.py
├── spamDetection/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── manage.py
└── requirements.txt
```

## Learning Outcomes

- Applying machine learning to a text classification problem
- Understanding text vectorization and Naive Bayes
- Integrating a machine learning model into a Django web application
- Connecting a user interface with a prediction function

## Future Improvements

- Evaluate model performance using precision, recall, and F1-score
- Improve text preprocessing and model performance
- Add more test cases and handle unexpected inputs
- Improve the user interface and prediction feedback

## Author

**Shloka Sonawane**

GitHub: [Shloka369](https://github.com/Shloka369)

---

*This project was developed for learning and demonstrating machine learning and web development concepts.*
