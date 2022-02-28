

BEFORE ANYTHING:

pip3 install Flask-SQLAlchemy psycopg2
touch env.py

BEFORE DEPLOYMENT:

pip3 freeze --local > requirements.txt
echo web: python run.py > Procfile
