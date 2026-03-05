# Our Application

To operate this app, you must begin by building the container image. To do this, you can use this command:
  
  `docker build -t getting-started .`

Next, you must run the container. To do this, you can use this command:

  `docker run -dp 3000:3000 getting-started`

 After a few seconds, open your web browser to http://localhost:3000. You should see the app! 

 To stop the container, you can first check to see which containers are running. To do this, you can use this command:

   `docker ps`

Once you see the container ID, you can stop the container. To do this, you can use this command:

  `docker stop [CONTAINER_ID_OR_NAME]`
