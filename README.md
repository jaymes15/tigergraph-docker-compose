# TigerGraph using Docker-compose

Run a TigerGraph instance locally using Docker-compose

## Requirements to run this project using Docker

- docker (20.10.5+): To install docker visit https://docs.docker.com/get-docker/
- docker-compose (1.25.5+): To install docker-compose visit https://docs.docker.com/compose/install/


## Getting started

**To start project with Docker:**
 - install docker
 - install docker-compose
 - Clone the project  
 - Change directory to the project directory 
 - Run:
    ```bash
        docker-compose up
    ```
  - ssh -p 14022 tigergraph@localhost from your terminal, you would be asked for a password which is `tigergraph`
  - Run gadmin start all
  - Gstudio would be available at http://localhost:14240/ . password and username is `tigergraph`
  - Run `gsql` to use graph query from the terminal


