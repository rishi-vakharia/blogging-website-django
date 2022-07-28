# Instructions

## 1) For installing virtual environment

python3 -m pip install --user virtualenv

## 2) For creating virtual environment

python3 -m venv env

## 3) For activating the virtual environment


source env/bin/activate

## 4) Install requirements
pip3 install -r requirements.txt

## 5) Make migrations
python3 manage.py makemigrations
python3 manage.py migrate 

## 6) Run the server
python3 manage.py runserver
