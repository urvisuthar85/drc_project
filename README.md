# drc_project

#create viretual envirement

virtualenv -p python3 venv

#go to directry

source venv/bin/activate

#install requirement files

pip install -r requirement.txt

#go to project foldar

cd project

#Runserve

python manage.py runserver
