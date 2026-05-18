Python Monitoring Application

Project overview
The project is pythong based infrastructure Monitoring
tool.

The application monitors the below metrics:
- use CI/CD Pipelines
- Automatically deploy from GitHub
- Runs on AWS EC2
- Monitor Server Health
- Simulate real devops infrastructure monitoring 

The application is built using python and Flask and 
will later be containerized using Docker.

Deplpoyed the monitoring applications in production 
using:
Python, Docker, Github Actions, AWS EC2, C/CD 
Automation.

Project workflow 
Developer -> GitHub Repository -> GitHub Actions CI/CD
-> Build Iamge (Docker) -> DockerHub Registry -> AWS
EC2 Deployment -> Monitoring application running in 
container 


CI/CD workflow
- Developer pushes cod to GitHub
- GitHub actions pipeline triggers automatically
- Docker image is built
- Docker image is pushed to DockerHub
- AWS EC2 server pulls latest image
- Container redeploys automatically
