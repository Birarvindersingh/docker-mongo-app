<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
</head>
<body>

  <h1>🧱 Dockerize and Run a Node.js + MongoDB App</h1>

  <p>This project demonstrates how to create a simple Node.js REST API, connect it to MongoDB, containerize it with Docker, run it using Docker Compose, and push the image to DockerHub for portability and reuse.</p>

  <h2>🚀 Project Overview</h2>
  <ul>
    <li>Create a simple Node.js backend using Express</li>
    <li>Connect to a MongoDB database</li>
    <li>Write a Dockerfile to containerize the backend</li>
    <li>Define a multi-container setup using Docker Compose</li>
    <li>Push the Docker image to DockerHub</li>
  </ul>

  <h2>🛠️ Technologies Used</h2>
  <ul>
    <li>Node.js (with Express)</li>
    <li>MongoDB</li>
    <li>Docker</li>
    <li>Docker Compose</li>
    <li>DockerHub</li>
  </ul>

  <h2>📦 Docker Commands Summary</h2>
  <ul>
    <li><code>docker-compose up --build</code> – Build and run multi-container app</li>
    <li><code>docker-compose down</code> – Stop and remove containers</li>
    <li><code>docker tag docker-node-mongo-backend bir23/node-mongo-app</code> – Tag image for DockerHub</li>
    <li><code>docker push bir23/node-mongo-app</code> – Push to DockerHub</li>
  </ul>

  <h2>📸 Project Screenshots</h2>
  <img src="https://github.com/Birarvindersingh/docker-mongo-app/blob/main/1.PNG" alt="Screenshot 1" width="500" />
  <img src="https://github.com/Birarvindersingh/docker-mongo-app/blob/main/2.PNG" alt="Screenshot 2" width="500" />
  <img src="https://github.com/Birarvindersingh/docker-mongo-app/blob/main/3.PNG" alt="Screenshot 3" width="500" />
  <img src="https://github.com/Birarvindersingh/docker-mongo-app/blob/main/4.PNG" alt="Screenshot 4" width="500" />
  <img src="https://github.com/Birarvindersingh/docker-mongo-app/blob/main/5.PNG" alt="Screenshot 5" width="500" />
  <img src="https://github.com/Birarvindersingh/docker-mongo-app/blob/main/6.PNG" alt="Screenshot 6" width="500" />
  <img src="https://github.com/Birarvindersingh/docker-mongo-app/blob/main/7.PNG" alt="Screenshot 7" width="500" />
  <img src="https://github.com/Birarvindersingh/docker-mongo-app/blob/main/8.PNG" alt="Screenshot 8" width="500" />
  <img src="https://github.com/Birarvindersingh/docker-mongo-app/blob/main/9.PNG" alt="Screenshot 9" width="500" />


  <h2>🐳 DockerHub Link</h2>
  <p>View the pushed Docker image here:</p>
  <p>🔗 <a href="https://hub.docker.com/r/bir23/node-mongo-app" target="_blank">DockerHub Repository: bir23/node-mongo-app</a></p>

</body>
</html>
