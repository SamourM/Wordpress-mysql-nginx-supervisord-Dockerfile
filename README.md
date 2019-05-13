# Wordpress-mysql-nginx-supervisord-Dockerfile

docker build -t imagename .  #build the image
docker run -d --name cotainername -p 3000:80 imagename # Fire up the container
docker exec -it ContainerID /bin/bash # login to the container
service mysql start #run mysql daemon
http://localhost:3000 # wordpress page should appear
