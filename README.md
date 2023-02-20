# quick books api
### run the project using docker

1. clone the project 
2. go to the project by using the command line `cd`
3. build the docker image with the command `docker build -f maven.Dockerfile -t book-api .`
4. Run the docker container `docker run docker run -it --rm -p 8091:8080 book-api` <br/>

you can right test the api  with `http://localhost:8091/books` to retrieve all books otherwise you can check all the mainController under src/main/java/com/pluralsight/books/controller/ folder to view all the available endpoints.

