#keep-score

##Development
To bring up dev environment run: 
```
docker-compose up db web
```
Changes made directly on the filesystem should be reflected immediatly in the container.

Then to run db migrations after the above are running (the containers should be left running) run:
```
docker-compose up dbmigrate
```

To run the test suite run:
```
docker-compose up webtest
```