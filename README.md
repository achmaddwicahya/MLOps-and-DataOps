### Project 7 - MLOps and DataOps
### Build API service using Flask for implement ML model

 #### Execution
 
  1. Build the image (only first-time, or when there's any change in the `Dockerfile`):
     ```shell
     docker-compose build
     ```
   
     or (for legacy versions)
   
     ```shell
     docker build .
     ```
 2. Kick up the all the services from the container:
    ```shell
    docker-compose up -d
    ```

 3. Login to API web UI on `localhost:5000` 

 4. Run your DAG on the Web Console.

 5. On finishing your run or to shut down the container/s:
    ```shell
    docker-compose down
    ```

    To stop and delete containers, delete volumes with database data, and download images, run:
    ```
    docker-compose down --volumes --rmi all
    ```

    or
    ```
    docker-compose down --volumes --remove-orphans
    ```
       

