Goal
====

- Deploy a two-tier web application to AWS, using best practices
- Provision multiple environments, including `dev` (for development) and `live` (for production). Each environment may be scaled independently.  
- Use continuous deployment for rapid evolution of application environments 

Later,

- [ ] Enable content acceleration for the web application using CloudFront (to be managed by a different team)
-	Uses Infrastructure and Code
-	Git Link - https://github.com/krishnan-mani/the-cf-workshop
-	Goal of the Workshop –
o	Data is on S3
o	EMR Cluster
o	Getting the software installed and configured
o	Getting Data and Code from wherever it sits today
-	We will process the data using an EMR Cluster. This Data resides at S3.
-	We need EMR to have the desired software installed and configured 
-	Also need to scale the cluster

Cloud formation cannot manage Configuration management. It can only provision resources.
Configuration Management – Chef, Puppet, CodeDeploy
Imperative (API vs SDK) vs Declarative (Cloud Formation) ?
 
