# AWS-Project-1
This project is to deploy a web-application in AWS cloud infrastructure using GoDaddy Domain, AWS-EC2 instances for (Ngnix, MySQL, Memcached, RabbitMQ), Route53 Private DNS, ACM, S3, ELB, Autoscaling Group and CloudWatch

### Project Architecture
![1](https://user-images.githubusercontent.com/106590073/180606295-22edc260-270b-4c4c-872a-060d591a6f07.jpg)

### Procedure : 
- Login to AWS Account
- Create Key Pairs to login to the ec2 instances
- Create Security groups for ELB, tomcat and backend services
- Launch Instances with Bash scripts
- Update IP to name mapping in route53 private DNS
- Build Application from source code, in local machine
- Then upload the artifact to S3 bucket
- Download artifact from S3 to Tomcat EC2 Instance 
- Setup ELB with HTTPS (generate SSL certificate from Amazon Certificate Manager)
- Map ELB endpoint to website name in GoDaddy DNS
- Verify the entire setup
- Build Autoscaling Group for Tomcat Instances



