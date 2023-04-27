<!-- How to run the project -->

pip install virtualenv  
virtualenv env  
source env/Scripts/Activate  
pip install -r requirements.txt 

create .env file from .env.example file  
python manage.py makemigrations  
python manage.py migrate  
python manage.py createsuperuser  
python manage.py runserver  
