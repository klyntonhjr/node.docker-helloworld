![build version](https://img.shields.io/badge/build-v1.0.0-green.svg)

# Node JS Hello-World
### Run Project Locally
    npm start
This will start a server on http://localhost:3000.

### Running Project Inside Docker container
Build docker image


    docker build -t node-helloworld .

Then run image in a container  

    docker run -p 8080:3000 -d node-helloworld

This will expose the application on http://localhost:8080.
