# AWS-Project-1
This project is to deploy a web-application in AWS cloud infrastructure using GoDaddy Domain, AWS-EC2 instances for (Ngnix, MySQL, Memcached, RabbitMQ), Route53 Private DNS, ACM, S3, ELB, Autoscaling Group and CloudWatch

### Project Architecture
![1](https://user-images.githubusercontent.com/106590073/180604999-231889df-c734-4052-be52-13d70ac9c272.jpg)

### Procedure : 
1. Login to AWS Account
2. Create Key Pairs
3. Create Security groups
4. Launch Instances with Bash scripts
5. Update IP to name mapping in route53
6. Build Application from source code
7. Upload to S3 bucket
8. Download artifact to Tomcat EC2 Instance 
9. Setup ELB with HTTPS (SSL certificate from Amazon Certificate Manager)
10. Map ELB endpoint to website name in GoDaddy DNS
11. Verify 
12. Build Autoscaling Group for Tomcat Instances



