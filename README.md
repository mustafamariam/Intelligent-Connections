**To run this project locally:**

1. Download game-github locally to your computer.

**Then, set up the virtual env in your terminal. Below are the sequential commands:**
1. python -m venv venv
2. venv\scripts\activate (on VSCode, you may just need to open a new terminal since the old one has been killed).
3. pip install Flask
4. pip install flask-sqlalchemy
5. python
6. from app import app, db
7. app.app_context().push()
8. db.create_all()
9. pip install Flask-Migrate
10. flask db init
11. flask db migrate -m "Initial migration"
12. flask db upgrade

Now, you can run the project locally:
1. In your terminal, type **flask run**
2. Then, using the URL presented in terminal, play the game

You can view your results by appending **/view** to your URL.
