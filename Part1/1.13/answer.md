## MANDATORY EXERCISE 1.13: HELLO, BACKEND!
1. Create a Dockerfile for the project
2. Build an image from the dockerfile
    `docker build . -t backend-app`
4. Run the created image
    `docker run -p 8080:8080 backend-app`
6. Navigate to http://localhost:8080/ping 


Output:
you should get a "pong" as respons

