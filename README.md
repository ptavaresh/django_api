#Django API 
##Recipe App

###Commands
docker-compose -f docker-compose-deploy.yml up  

docker-compose -f docker-compose-deploy.yml down

docker-compose run --rm app sh -c "python manage.py test"