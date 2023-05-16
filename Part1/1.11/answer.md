EXERCISE 1.11: SPRING

1. Create a Dockerfile for an old Java Spring project that can be found from the course repository.
2. Build an image
  $ docker build . -t java-spring
3. run the image
  $ docker run -p 8080:8080 java-spring
4. Open a browser and navigating to http://localhost:8080/. 
5. You've completed the exercise when you see a 'Success' message in your browser.
