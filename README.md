# parade_metabase

## Running the Application with Docker Compose

To run the application using Docker Compose, follow these steps:

1. Make sure you have Docker and Docker Compose installed on your system.
2. Navigate to the project directory:
   ```bash
   cd /location/to/directory/parade_metabase
   ```
3. Start the application
    ```bash
    docker-compose up
    ```
4. To run the application in detached mode (in the background), use:
    ```bash
    docker-compose up -d
    ```
5. Stop the application:
    ```bash
    docker-compose down
    ```
6. If you want to remove volumes as well, use:
    ```bash
    docker-compose down -v
    ```