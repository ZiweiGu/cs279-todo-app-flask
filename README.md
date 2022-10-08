# cs279-todo-app-flask

A Todo app built from scratch with Flask. The app uses SQLAlchemy, the Python SQL toolkit, to store todo items in a database. To run it locally, first clone the repo and navigate to the root directory: 
```
git clone https://github.com/ZiweiGu/cs279-todo-app-flask.git
cd cs279-todo-app-flask
```
Then, set up the virtual environment (called venv) using virtualenv (installation [here](https://virtualenv.pypa.io/en/latest/installation.html)):
```
virtualenv -p python3 venv 
```
Activate the virtual environment:
```
source venv/bin/activate
```
Install necessary packages:
```
pip install -r requirements.txt
```
Run the app:
```
python3 app.py
```

Significant software concepts:
Flask is a micro web framework that is simple but highly extensible. Notably, it depends on the Jinja2 template engine that passes data from back-end to front-end. It allows developers to write complex logic code in Python and then pass the results to templates. 
