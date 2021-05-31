# divio
A django website that deployed on divio cloud

step1 - Create a vertual environment
> python3 -m venv env    
> source env/bin/activate

step2 - install Docker from web

step3 -Dockerizing the app
> docker-compose build   
> docker-compose run web python manage.py collectstatic (optional) <br>
> docker-compose run web python manage.py makemigrations <br>
> docker-compose run web python manage.py migrate <br>
> docker-compose up
