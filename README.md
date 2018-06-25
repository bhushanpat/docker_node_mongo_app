# docker_node_mongo_app
Dockerised Node and MongoDB App

Steps to run this project on Local.

1. git clone
2. cd docker_node_mongo_app/
3. sudo docker-compose up --build -d

Everything working? Awesome! Open a browser and head for http://localhost:3000 where you will see a welcome to Express page.
- To check mongo entries: http://localhost:3000/userlist
- To add entries to mongo: http://localhost:3000/newuser
