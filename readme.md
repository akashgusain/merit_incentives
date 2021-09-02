Build the images and run the containers:


Go inside merit_incentives directory where docker-compose file present

docker-compose up --build

Test the below endpoints

1. http://127.0.0.1:8000/notes/
2. http://127.0.0.1:8000/docs


For Testing

docker-compose exec web pytest .