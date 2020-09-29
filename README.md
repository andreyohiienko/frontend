# Frontend
Example of Docker usage

- ```docker build -f Dockerfile.dev . ```
- ```docker run -it -p 3000:3000 -v $(pwd):/app CONTAINER_ID```
- ```docker run -it -p 3000:3000 -v /app/node_modules -v pwd:/app CONTAINER_ID ```