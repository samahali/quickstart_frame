first you need to create virtualenv you can write this command
----------------------------

python3 -m venv env

## to activate it

source env/bin/activate

## to install packages run the command bellow
pip install -r requirements.txt

## then run the code 
python manage.py grpcrunserver --dev
