# 🎬 Movie Review API

A Django RESTful API that allows users to register, log in, and post reviews for movies. Built with Django, Django REST Framework, and JWT authentication. This project is part of my backend engineering journey through ALX.

## 🚀 Features

- User registration and login with JWT token authentication
- Custom user model with profile support
- Create, read, update, and delete movie reviews
- Filter reviews by user, rating, or movie
- Pagination and ordering support
- Ready for deployment on Heroku

## 🛠️ Tech Stack

- Python 3.11+
- Django 5.2.4
- Django REST Framework
- Simple JWT
- SQLite (development) / PostgreSQL (production)
- Heroku (deployment)

## 📦 Installation

```bash
git clone https://github.com/Shonisani98/movie_review_api.git
cd movie_review_api
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
