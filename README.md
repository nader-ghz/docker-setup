# docker-setup
Clone the project into ekipik directory make sure all files are in the root of ekipik 
docker-compose up -d 
docker run --rm artisan migrate 
docker run --rm artisan central:migrate 
docker run --rm artisan tenants:migrate 


docker run --rm composer ===> to run composer command 
docker run --rm artisan  ===> to run artisan command 
docker run --rm npm  ===> to run npm command
