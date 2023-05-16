EXERCISE 1.8: TWO LINE DOCKERFILE

1. Create a dockerfile use FROM and CMD to create a brand new image that automatically runs server.
2. Build image from the dockerfile
   $ docker build . -t web-server
3. Run he image
   $ docker run web-server
  
4. Running the built "web-server" image should look like this:

$ docker run web-server
[GIN-debug] [WARNING] Creating an Engine instance with the Logger and Recovery middleware already attached.

[GIN-debug] [WARNING] Running in "debug" mode. Switch to "release" mode in production.
- using env:   export GIN_MODE=release
- using code:  gin.SetMode(gin.ReleaseMode)

[GIN-debug] GET    /*path                    --> server.Start.func1 (3 handlers)
[GIN-debug] Listening and serving HTTP on :8080

