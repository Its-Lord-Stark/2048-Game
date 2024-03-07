# 2048 Game

2048 is a single-player sliding block puzzle game where the objective is to slide numbered tiles on a grid to combine them and create a tile with the number 2048. The game is won when a tile with the number 2048 appears on the grid, but players can continue to play to reach higher scores.

** This project is a simple implementation of the 2048 game, created to understand the flow of Dockerization and deployment on AWS Elastic Beanstalk. **

![Screenshot (674)](https://github.com/Its-Lord-Stark/2048-Game/assets/126385754/fcbec6fd-e119-49b6-b05f-7f093b5be025)


## Dockerization

This project has been Dockerized for easier deployment and management. Docker allows you to package your application and its dependencies into a container, ensuring consistency across different environments.

To Dockerize the project, I created a Dockerfile that specifies the environment and dependencies needed to run the application. This Dockerfile includes instructions for installing Node.js and copying the application code into the container.

Once the Dockerfile was created, I built the Docker image using the `docker build` command. This command creates a Docker image based on the instructions in the Dockerfile.

After building the Docker image, I tested it locally to ensure that the application runs correctly within the container. I used the `docker run` command to start a container from the image and accessed the application via localhost.

![Screenshot (680)](https://github.com/Its-Lord-Stark/2048-Game/assets/126385754/9b4bd72d-bd66-4f62-acf4-ca3c275b3ff7)


![Screenshot (679)](https://github.com/Its-Lord-Stark/2048-Game/assets/126385754/f418c84e-080d-440f-ac96-e6aa59e58667)


## Deployment on AWS Elastic Beanstalk

After Dockerizing the project, I deployed it on AWS Elastic Beanstalk for easy scalability and management. AWS Elastic Beanstalk is a Platform as a Service (PaaS) offering that allows you to deploy and manage applications without worrying about the underlying infrastructure.

To deploy the Dockerized application on Elastic Beanstalk, I created an Elastic Beanstalk application and environment using the AWS Management Console. I configured the environment to use a Docker platform and provided the URL of the Docker image stored in a container registry Docker Hub.

Once the environment was configured, Elastic Beanstalk automatically deployed the Dockerized application, managed the underlying infrastructure.

Overall, Dockerizing the project and deploying it on AWS Elastic Beanstalk allowed for easy deployment, scalability, and management of the application. This approach ensures consistency across different environments and simplifies the deployment process.

![Screenshot (672)](https://github.com/Its-Lord-Stark/2048-Game/assets/126385754/a5b4f4ec-e312-4b16-b83e-8cde1218173b)




