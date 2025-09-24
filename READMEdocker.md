# WordPress on Docker

This folder contains the necessary files to run wordpress and phpmyadmin using docker on your local computer

To run it, you need to install docker on your local machine

Then follow these steps:
1. Edit the port for wordpress in the docker-compose.yml file in line 44
    - Take note of the port for phpmyadmin and wordpress
2. Open your terminal and navigate to the directory you copied this folder on
3. Enter this command -> docker compose up
    - This will create the containers for phpmyadmin and wordpress
    - You can see the containers in your docker desktop or by entering this in terminal -> docker containers
4. Navigate to the phpmyadmin page by opening http://localhost:{phpmyadmin-port} in your browser
    - You can find the password of the root user in the .env file
5. In phpmyadmin, create a new database for your wordpress instance
    - You can use root or create a new user and assign it to the new database
6. Open a new tab and open http://localhost:{wordpress-port} in your browser
7. Follow and finish the wordpess setup
8. BUILD BUILD BUILD!

