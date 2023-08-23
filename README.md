# Random-stuff

docker run --name seq -d --restart unless-stopped -e ACCEPT_EULA=Y -p 5341:80 datalust/seq:latest

docker run -d -p 6379:6379 redis

docker run --name mysql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=testing -e MYSQL_ALLOW_EMPTY_PASSWORD=true mysql:8

Limit WSL  memory usage
https://itnext.io/wsl2-tips-limit-cpu-memory-when-using-docker-c022535faf6f


terraform fmt -recursive


docker pull grafana/k6
Pipes test into docker and runs it:

cat script.js | docker run --rm -i grafana/k6 run -
https://k6.io/docs/get-started/installation/
