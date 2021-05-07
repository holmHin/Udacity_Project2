*** Project2 Holm Hinrichs *** 

Please find folowing files: 
- Project Diagram.pdf --> Diagram of Infrastructure
- infra.yml --> CloudFormation Script for the infrastructure
- infra_params,json --> Infrastructure Parameters
- servers.yml --> CloudFormation Script for Server and LoadBalancing
- server_param.json --> ServerParameters

** The S3 integration using an IAM Role worked on any host but unfortunately on the deployed one the outbound connection via https was not possible to any host. Resolving this by a wget wget udacity-demo-1.s3.amazonaws.com/udacity.zip


