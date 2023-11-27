# flask_tutorial
install dependencies (use a virtual env):
pip install Flask

start the app
flask --app flaskr run --debug

init the db with
flask --app flaskr init-db

cool flask html note:
{% block title %} will change the title displayed in the browser’s tab and window title.
{% block header %} is similar to title but will change the title displayed on the page.
{% block content %} is where the content of each page goes, such as the login form or a blog post.