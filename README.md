Start the RabbitMQ docker container

To access the RabbitMQ page, make sure the docker container is started on the correct VM.

Run this command to see all the containers and find the id of the RabbitMQ container



docker ps -a
Start the docker container



docker start [container_id]
 

Open the RabbitMQ page

You can access the page in a browser window at the IP address of the VM on port 15672

PORT: 15672

For example, to access rabbitMQ on the test server go to:
http://10.2.160.51:15672/

 

Credentials

Username: user

Password: password
