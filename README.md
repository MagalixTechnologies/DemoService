# DemoService
This container is using express to host some js on port 5000.

## To build the container locally
`docker build -t airwavetechio/demoservice .`

## To Run the container
* `docker run -d -p 5000:5000 --name demoservice airwavetechio/demoservice`
* `http://localhost:5000`


## To stop a container
* `docker kill demoservice`
* `docker rm demoservice`


## To run docker-compose tests
`docker-compose -f docker-compose.test.yml up  --build --force-recreate`