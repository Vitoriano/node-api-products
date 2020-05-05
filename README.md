
## Simple API with Express and MongoDb

Install all dependencies from package.json file.

- yarn add package.json

Run the project with the following command

- yarn dev

Open http://localhost:30001 in your Browser


## How to set up your database with docker 

 -- On Linx install docker.io

 Creating your container with MongoDB:

 -  docker pull mongo

 Configuring routes and ports:

 - sudo docker run --name mongodb -p 27017:27017 -d NAMECONTAINER

 List all your containers with the following command: 

 - docker ps 
 - docker ps -a 

 Start your container:

 - docker start mongodb