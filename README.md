# Task mangemant system

Basically the project is based on given assignment. In this project I tried to fullfill the requirement of assigment.

Node.JS and it's framework express is used for developing all api's and mongodb is used as database. 

In this project basically three component user,task and task stages.In which admin user can create the task and assign to other
user .User can see details of his task and change the task of their task.

# Installation Steps

Install node.js in system
https://www.metachris.com/2017/01/how-to-install-nodejs-7-on-ubuntu-and-centos/

Install mongo db in syatem
https://docs.mongodb.com/v3.4/tutorial/install-mongodb-on-ubuntu/

Install pm2 globally npm install pm2 -g

Clone the repo git clone https://github.com/ankitm27/new.git

Move into project backend folder where paskage.json is available and run npm install

Move into project frontend folder where paskage.json is available and run npm install

for running frontend move into frontend folder and run pm2 start frontend

for running backend folder move into backend folder and run pm2 start www

access the app at http://127.0.0.1:8080

nginx proxy is set for deployed app

server link - http://52.221.212.105/#!/signup


