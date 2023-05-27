# Simple Load Balancer Using Nginx on Linux Arch with Docker Containers

## Step 1: Creating Docker Containers
```shell
  cd load-balancer
  sudo docker compose up -d
```
## Step 2: Verify the Load Balancer
Run the following command in your terminal to check how load balancer works by making multiple requests to the Nginx server. 
```shell
  while true; do curl localhost; sleep 1; done
```
