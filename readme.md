*** Project2 Holm Hinrichs *** 

Please find folowing files: 
- Project Diagram.pdf --> Diagram of Infrastructure
- infra.yml --> CloudFormation Script for the infrastructure
- infra_params,json --> Infrastructure Parameters
- servers.yml --> CloudFormation Script for Server and LoadBalancing
- server_param.json --> ServerParameters
- Screenshots of instance.pdf --> Showing all steps on AWS-Consol


URL to Project: http://proje-loadb-16j50yzs35esz-1575255447.us-west-2.elb.amazonaws.com



** The S3 integration using an IAM Role worked on any instance in private and oublic subnet. But unfortunately on the deployed one the outbound connection via https was not possibleto any host  (timed out, tried also wget https://google.de) . Resolving this by a wget wget udacity-demo-1.s3.amazonaws.com/udacity.zip


