# divio
A django website(https://vsc.us.aldryn.io)  deployed on cloud based server 'www.divio.com' <br> <br>
step for running this Dockerized web work <br>
step1 - Create a virtual environment
> python3 -m venv env    
> source env/bin/activate

step2 - install Docker from web

step3 -Dockerizing the app
> docker-compose build   
> docker-compose run web python manage.py collectstatic (optional) <br>
> docker-compose run web python manage.py makemigrations <br>
> docker-compose run web python manage.py migrate <br>
> docker-compose up
