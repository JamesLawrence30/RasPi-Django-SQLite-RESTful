*First Run only*:
~/sensing $ manage.py makemigrations myapp
~/sensing $ manage.py migrate
~/sensing $ manage.py createsuperuser


Run Django server:
~/sensing $ python3 manage.py runserver


*First Run only*:
Post "no" to http://127.0.0.1:8000/room & Post "closed" to http://127.0.0.1:8000/door


Run native controller service on *Seperate terminal window*:
~/sensing $ sudo python3 controller.py

View running application at http://127.0.0.1:8000/home
