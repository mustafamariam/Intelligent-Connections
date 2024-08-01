**To run this project locally:**

1. Download game-github locally to your computer (you can ```git clone https://github.com/mustafamariam/Intelligent-Connections.git```)

**Then, set up the virtual env in your terminal. Below are the sequential commands:**
1. python -m venv venv
2. venv\scripts\activate (on VSCode, you may just need to open a new terminal since the old one has been killed)
3. pip install Flask
4. pip install flask-sqlalchemy

**Now, let's set up the DB:**
1. python
2. from app import app, db
3. app.app_context().push()
4. db.create_all()

**At this point, exit out of the python shell and run these commands in your IDE terminal normally:**
1. pip install Flask-Migrate
2. flask db init
3. flask db migrate -m "Initial migration"
4. flask db upgrade

**Now, you can run the project locally:**
1. In your terminal, type **flask run**
2. Then, using the URL presented in terminal, play the game

You can view your results by appending **/view** to your URL.
