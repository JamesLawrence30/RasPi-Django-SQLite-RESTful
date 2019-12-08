Try to run everything, as listed below.  Your Pi will likely have a lot of dependencies that need to be installed. You must install them all or the application will not run.  Follow the Google Slides linked below in case you have any confusion!

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



Project from Design 6 course offered at Stevens Institute of Technology by Professor Kevin Lu.
For more info, visit https://docs.google.com/presentation/d/1PyelFDHtyRSXq5k_YyBTPZNVICtgtOE0cE8dF-SWwNI/edit#slide=id.geef9298d0_0_63
