# Simple Load Balancer Using Nginx on Linux Arch with Docker Containers

## Step 1: Install docker and docker-compose
```shell
  sudo pacman -Syu
  sudo pacman -S docker docker-compose
  sudo pacman -S git
```
## Step 2: Creating Docker Containers
```shell
  git clone https://github.com/tomas6446/load-balancer
  cd load-balancer
  sudo docker compose up -d
```
## Step 3: Verify the Load Balancer
Run the following command in your terminal to check how load balancer works by making multiple requests to the Nginx server. 
```shell
  while true; do curl localhost; sleep 1; done
```
