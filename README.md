# flask-app-cicd
A Flask application with python unit tests linked to a CI/CD pipeline on AWS

To build the architecture described in the solution overview, you will need the following ECS components:
  1. ECR Repository: store versioned application container images
  2. ECS Cluster: provides compute power to run application container instances
  3. ECS Task Definition: specifies application container image version and environment considerations
  4. ECS Service: specifies how task definition will be deployed onto underlying compute resources
