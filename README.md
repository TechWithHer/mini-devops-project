# Mini DevOps Project 

## Description
Basic Flask application to start the DevOps project journey.

## How to run
pip install -r requirements.txt
python app.py

## Output
Hello from DevOps Project 🚀

----------------------------------

## Version 2 - Dockerized App

### Build Image
docker build -t devops-project .

### Run Container
docker run -p 5000:5000 devops-project

----------------------------------

## Version 3 - Deployed on Linux Server

- Application deployed on Ubuntu EC2 instance
- Docker used for containerization
- Access via: http://<public-ip>:5000

----------------------------------

## Version 4 - Infrastructure with Terraform

- EC2 instance created using Terraform
- Security group configured (SSH + App port)
- Infrastructure is now reproducible

------------------------------------
