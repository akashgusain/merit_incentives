Build the images and run the containers:

######################### Docker based instalation ########################################

Install Docker Desktop in system

Docker Desktop (https://www.docker.com/products/docker-desktop)

After installing the software, open terminal and verify the docker installation by using below command.

---->>>>>> docker run hello-world

Clone the repository:

$ git clone https://github.com/akashgusain/merit_incentives.git


Go inside merit_incentives directory where docker-compose file present

docker-compose up --build

Test the below endpoints

1. http://127.0.0.1:8000/notes/
2. http://127.0.0.1:8000/docs


For Testing

docker-compose exec web pytest .