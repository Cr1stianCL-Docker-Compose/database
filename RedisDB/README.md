1.-First read the root README.md.
2.-Need to run the docker compose recipe to create the container, then connect with prefered client or using terminal, using the following command:

- docker exec -it redis-db redis-cli #to enter inside the redis container terminal
- AUTH my-password #to log with configured password
- SET welcome "Hello, Redis!" #set a value inside welcome key
- GET welcome #retreave a value getting welcome key , returning the string "Hello, Redis!"
