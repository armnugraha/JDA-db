# Setup db using mysql

Open Terminal
- docker build -t jda-db .

Config terminal
- docker run --name jda-mysql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=root -d jda-db > to run container
- open terminal in docker desktop or run docker exec -it jda-db bash

# References
https://hub.docker.com/_/mysql
https://www.datacamp.com/tutorial/set-up-and-configure-mysql-in-docker
https://medium.com/@edu18ds/running-mysql-in-container-docker-and-setting-dbeaver-5f9e5781649d
https://stackoverflow.com/questions/55931321/docker-mysql-connection-dbeaver