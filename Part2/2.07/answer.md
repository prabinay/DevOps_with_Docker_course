## EXERCISE 2.7 VOLUME

1. Add following in `docker-compose.yml`
   `volumes:
      - ./database:/var/lib/postgresql/data`
2. Run the following command to start the container:
   `docker-compose -d up`
3. Save a few messages through the frontend
4. Run `docker-compose down`
5. Run `docker-compose up` and see that the messages are available after refreshing browser
6. Run `docker-compose down` and delete the volume folder manually
7. Run `docker-compose up` and the data should be gone
