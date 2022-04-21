# MongoDB QuickBook

   ##  Using Homebrew
      You can install mongodb using below brew command
        
```sh 
      brew install mongo 

```
   ##  Using Docker
   
      1. Create a directory for e.g.  "MongoSampleDB"
      3. Copy docker-compose.yml file in your "MongoSampleDB" directory.
      5. Now go to terminal and execute below command 
     
```sh 
      docker-compose up -d

```
If  you are using visual code editor. You can install docker extension using below 
 - [visual code docker extension](https://code.visualstudio.com/docs/containers/overview)
Once docker extension is install then open docker-compose.yml file in visual code editor and open then right click  on file content and select "compose up". This will start docker container.
      5. Once docker compose command is successful and you will able be create docker container then go to terminal and execute below command to go inside docker container.
      
```sh 
      docker exec -it mongo_demo bash 

```
# Mongo Compass 

- [Install Compass for Query API](https://www.mongodb.com/docs/compass/current/install/)

# Mongo Upload Sample DB
   
   - [mongodb-sample-dataset](https://github.com/neelabalan/mongodb-sample-dataset)
     
#  MQL Cheat-sheet
 
  - [MQL Cheat-Sheet](https://www.mongodb.com/developer/quickstart/cheat-sheet/#connect-mongodb-shell)
     

