# flaskbase

Web framework based on flask


# setup git

git config user.name $GIT_USER_NAME
git config user.email $GIT_USER_EMAIL

git config credential.helper 'cache --timeout=3600'
git config credential.helper store

git config --list


# setup database

flask db upgrade


# start web server

export FLASK_APP=flasky.py
export FLASK_DEBUG=1
flask run

or 

./start


