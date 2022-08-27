https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world

Commands
-----------------------------------
python3 -m venv venv
-----------------------------------
. venv/Scripts/activate
-----------------------------------
pip install -r requirements.txt
-----------------------------------

Requirements File
To create a requirement file using pipreqs run the following command:
pip install pipreqs
pipreqs /path/to/project (or . for root directory)
pipreqs . --force (rewrite exisiting)

### Chapter 1: Hello World
---
### Chapter 2: Templates
---
### Chapter 3: Web Forms
---
### Chapter 4: Database
  - flask db init
  - flask db migrate -m "message"
  - flask db upgrade !important
  - flask db downgrade command, which undoes the last migration

 upgrade command will detect that a database does not exist and will create it (you will notice a file named app.db is added after this command finishes, that is the SQLite database). When working with database servers such as MySQL and PostgreSQL, you have to create the database in the database server before running upgrade.

  - flask shell
  - exit()

---
### Chatper 5: User Logins