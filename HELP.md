## Deploy with Docker
You need run the following commands
1. To create the Docker Image
    ```batch
    docker build -t <your-user>/sapper-docker .
    ```
2. To run the Docker Container
    ```batch
    docker run -p 8080:3000 -d <your-user>/sapper-docker
    ```
¡Ready!

At now, go to: [http://localhost:8080](http://localhost:8080)
