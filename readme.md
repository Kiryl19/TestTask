Run `pip install -r requirements.txt`

Then run `python manage.py makemigrations` > `python manage.py migrate`

Also run `python manage.py loaddata app/fixtures/tariffs.json` to load initial data to db

Then run `python manage.py createsuperuser` and enter data for your superuser

And finally run `python manage.py runserver`


Swagger schema will be available at {your_host}:{your_port}/swagger

Admin site will be available at Swagger schema will be available at {your_host}:{your_port}/admin
