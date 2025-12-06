# A Simple Hello World Node Demo 
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fneriia19911991%2Ftest-tools.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fneriia19911991%2Ftest-tools?ref=badge_shield)


Example used to demonstrate ```docker init``` CLI for a simple Hello World Node Program


## Run the application





You can simply use `node app.js` command.


This script creates a simple HTTP server that listens on port 8080 and returns a response with the message "Hello from Docker!" when accessed. You can save this script as app.js in your project directory and then run it using the command node app.js from the terminal.


Those commands will start a http server listening on port `8080` 
and if your request `http://localhost:8080` you'll see the following output: 
```shell
❯ curl http://localhost:8080

          ##         .
    ## ## ##        ==
 ## ## ## ## ##    ===
/"""""""""""""""""\___/ ===
{                       /  ===-
\______ O           __/
 \    \         __/
  \____\_______/


Hello from Docker!

```


## Using Docker init

### Run the following command:

```bash
 docker init
```

This utility will walk you through creating the following files with sensible defaults for your project:
  - .dockerignore
  - Dockerfile
  - docker-compose.yaml


## Install the Dependencies

```
 npm install
```
 
 ## Running the container service
 
 ```
  docker compose up -d --build
 ```
 
 ## Accessing the Node app
 
 ```
 curl localhost:8080

          ##         .
    ## ## ##        ==
 ## ## ## ## ##    ===
/"""""""""""""""""\___/ ===
{                       /  ===-
\______ O           __/
 \    \         __/
  \____\_______/


Hello from Docker!
```



## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fneriia19911991%2Ftest-tools.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fneriia19911991%2Ftest-tools?ref=badge_large)