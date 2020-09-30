# Frontend
Example of Docker usage

- ```docker build -f Dockerfile.dev . ```
- ```docker run --rm -it -p 3000:3000 -v ${pwd}:/app CONTAINER_ID``` - should be react-scripts: not found
- ```docker run --rm -it -p 3000:3000 -v /app/node_modules -v ${pwd}:/app CONTAINER_ID ``` - power shell
- ```docker run --rm -it -p 3000:3000 -v ./app/node_modules -v "/$(PWD)":/app CONTAINER_ID``` - bash
- ```docker run --rm -it CONTAINER_ID npm run test```
- ```docker exec -it CONTAINER_ID npm run test```
- ```docker-compose up```
- ```docker-compose up --build```

## Issues
- [ ] Jest re-run after changes doesn't work in Windows