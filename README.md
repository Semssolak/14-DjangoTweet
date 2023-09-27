# Tweet App
Tweet App is a social media application built using the Django web framework. With this application, users can create, view, and delete their own tweets.

![Logo](screenshots/logo.png)

## Features
- **List Tweets:** The home page features an interface that lists all tweets. It displays the title, content, and creation date of tweets.

![Tweet List](screenshots/tweetlist.png)

- **Add Tweet:** Users can add new tweets by clicking on the "Add Tweet" link.

![Tweet Add Page](screenshots/addtweet.png)

- **Register:** Users can create new accounts.

![Register Page](screenshots/signup.png)
 
- **Login:** Users can log into the application.

![Login Page](screenshots/login.png)

- **Logout:** Authenticated users can log out by clicking the "Logout" link.

## Getting Started
To run this application in your local development environment, follow these steps:

1.Clone the project files:
    git clone https://github.com/your-username/tweet-app.git
    cd tweet-app

2.Create a virtual environment and install dependencies:
    python -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt

3.Create the database:
    python manage.py migrate

4.Start the application:
    python manage.py runserver
    
5.Open http://localhost:8000 in your browser and start using the application.

## Contributing
If you'd like to contribute to this project, please don't hesitate to submit a pull request.
