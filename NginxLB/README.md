# Quick steps to setting Nginx Load Balancer using default Round Robin

## Step 1 : Build the Image (run the command inside the folder NginxLB)
docker build -t nginxlb .

## Step 2 : Create a container based on the docker images created
docker run -d -p 80:80 nginxlb 
