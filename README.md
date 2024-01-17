# docker-compose-project


#### To start the application

Step 1: start mongodb and mongo-express

    docker-compose -f docker-compose.yaml up
    
_You can access the mongo-express under localhost:8080 from your browser_
    
Step 2: open mongo-express from browser

    http://localhost:8081

Step 3: create `my-db` _db_ and `my-collection` _collection_ and _document_ with `{myid: 1, data: "some dynamic data loaded from db"}` in mongo-express
    

Step 4: Access you nodejs application UI from browser

    http://localhost:3000
  