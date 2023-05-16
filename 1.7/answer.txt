EXERCISE 1.7: IMAGE FOR SCRIPT

1.create a Dockerfile

2.create script file as given

3.build image from the dockerfile
  $ docker build . -t helloscript

4.run the image
  $ docker run -it helloscript
  
5.The following should now work:

$ docker run -it curler

  Input website:
  helsinki.fi
  Searching..
  <!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
  <html><head>
  <title>301 Moved Permanently</title>
  </head><body>
  <h1>Moved Permanently</h1>
  <p>The document has moved <a href="https://www.helsinki.fi/">here</a>.</p>
  </body></html>

