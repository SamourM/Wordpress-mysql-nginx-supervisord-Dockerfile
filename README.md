# Wordpress-mysql-nginx-supervisord-Dockerfile

docker build -t imagename .  #build the image


docker run -d --name cotainername -p 3000:80 imagename # Fire up the container


http://localhost:3000 # wordpress page should appear
