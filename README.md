# Random-stuff

docker run --name seq -d --restart unless-stopped -e ACCEPT_EULA=Y -p 5341:80 datalust/seq:latest

docker run -d -p 6379:6379 redis

docker run --name mysql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=testing -e MYSQL_ALLOW_EMPTY_PASSWORD=true mysql:8

terraform fmt -recursive
