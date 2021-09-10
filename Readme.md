 # Load balancing Sample

 #### How to use :
 - To launch the APP, just open a terminal, go inside the unzipped folder, at the same level with docker-compose.yml, and execute : docker-compose up
 - This will spin up the dockerised architecture. After that, you need to open a browser and tape : http://localhost:8080
 - It will redirect 70% traffic to lab-app-go and 30% traffic to lab-app-java.
 - To quit, you can just CTRL + C in the terminal and it will stop the application and destroy the created containers.
