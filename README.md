## Cloud-Native System Monitoring App
System monitoring app written in Python which retrieves system utilization info using `psutil` & visualizes the output using `plotly` graphing library.

![127 0 0 1_5000_(iPad Pro)](https://github.com/pkdeva/cloud-system-monitoring/assets/83779939/a3bab832-5893-4b7a-84ee-b66af62b3d6a)


> this also includes:
- have written the Dockerfile to build DockerImage and run Docker Container.
- added ``ECR`` module using `boto3` (the AWS SDK for Python) to push the DockerImage to AWS - Elastic Container Registry.
- have also written `EKS` module for to deploy Kubernetes pods and cluster on AWS - Elastic Kubernetes Service.
  
