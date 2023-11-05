# express-sqlite
Step 1: Project Configuration on GitLab (or GitHub)
I created GitHu project titled "express-sqlite" and cloned the project to my local machine. Optionally, I can configure a GitFlow workflow for the project using my preferred tool.

Step 2: Creating the Express.js Application with SQLite
I navigated to the project directory using cd express-sqlite and initialize a Node.js project with npm init. Then, I installed the necessary dependencies (Express.js and SQLite) using npm install express sqlite3. After that, I created an app.js file and added the provided Express.js code. To ensure the application functions correctly, I tested it using tools like Postman.

Step 3: Creating the Docker Image
I created a Dockerfile in the project's root directory and build the Docker image using the command: docker build -t oumaimabensoussia/express-sqlite-app .. To test the Docker image locally, I will run it in a container with the command: docker run -p 3000:3000 oumaimabensoussia/express-sqlite-app. I confirmed the application's functionality by accessing http://localhost:3000. Finally, I published the Docker image to DockerHub using the command: docker push <username>/express-sqlite-app.

Step 4: Docker Compose Configuration
I will create a docker-compose.yml file to define the Docker Compose configuration. I used the provided example and modify it as needed. To run the application using Docker Compose, I executed the command: docker-compose up.

Step 5: Creating the Jenkinsfile (CI)
I created a new jenkins project and I added the credentials that I created lately in the configuration of my new jenkins project.
