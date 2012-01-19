Installation for development

1. Create a virtualenv
    A. virutalenv --distribute Mysite_ve
    B. cd Mysite_ve
    C. source bin/activate
2. Install this project
    A. git clone git@github.com:brousch/dpaste_de
3. Install dependencies
    A. pip install - r dpaste_de/requirements.txt
    B. git clone git@github.com:brousch/django-dpaste
    C. cd django-dpaste
    D. python setup.py install
4. Modify settings.py
    A. cd ../dpaste_de
    B. Modify PROJECT_ROOT and database settings in dpaste_de/settings.py
5. Syncdb and runserver
    A. ./manage.py syncdb
    B. ./manage.py runserver
