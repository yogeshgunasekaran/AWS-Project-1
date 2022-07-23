# AWS-Project-1
This project is to deploy a web-application in AWS cloud infrastructure using GoDaddy Domain, AWS-EC2 instances for (Ngnix, MySQL, Memcached, RabbitMQ), Route53 Private DNS, ACM, S3, ELB, Autoscaling Group and CloudWatch

### Project Architecture
![1](https://user-images.githubusercontent.com/106590073/180604999-231889df-c734-4052-be52-13d70ac9c272.jpg)

### Procedure : 
-  Login to AWS Account
-  Create Key Pairs
- Create Security groups
- Launch Instances with Bash scripts
- Update IP to name mapping in route53
- Build Application from source code
- Upload to S3 bucket
- Download artifact to Tomcat EC2 Instance 
- Setup ELB with HTTPS (SSL certificate from Amazon Certificate Manager)
- Map ELB endpoint to website name in GoDaddy DNS
- Verify 
- Build Autoscaling Group for Tomcat Instances



