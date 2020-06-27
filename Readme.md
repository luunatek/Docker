Docker is an open platform for developing, shipping, and running applications. 

docker images --format "table {{.Repository}}:{{.Tag}}"
docker rmi `docker images --format "table {{.Repository}}:{{.Tag}}"`
