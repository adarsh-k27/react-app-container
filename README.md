# VOLUME

1. docker run -v $(pwd)/src:/app/src -d -p 4000:4000 react-app-sample

2. -d: its run in terminal and we can use the terminal for our other use cases 

3. Cahces Are very Big problem while building so we need to check the cache when your building at first time.

4. docker-compose up -d --build will build a new image and run container with new code changes other wise it will run previous cache .

5. for run prod=> docker-compose  -f docker-compose-prod.yml up -d 

6. for run dev=> docker-compose  -f docker-compose-dev.yml up -d 

7. doen docker container => docker-compose -f docker-compose-dev.yml down