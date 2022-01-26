## Sample User Profile Application fetched from MongoDB based on Docker 

This demo app shows a simple user profile app set up using 
- index.html with pure js and css styles
- nodejs backend with express module
- mongodb for data storage

All components are docker-based

### With Docker Compose

#### To start the application

Use the following command to start mongodb, mongo-express UI and my-app

    docker compose -f docker-compose.yaml up
    

Mongo-express can be accessed from browser using the following

    http://localhost:8081

And access your nodejs application UI from browser

    http://localhost:3000

#### To manually build a docker image from the application

    docker build -t my-app .       
    
The dot "." at the end of the command denotes location of the Dockerfile.
