# vprofile-aws-refractor
Refractoring vproifle aws project from lift and shift to native cloud.
It will be using the PAAS [Platform As A Service] and SAAS [Software As A Service] strategy on AWS.
This will help with:
* Automation
* IAAC [Infrastucture As A Code]
* Flexibility
* PayAsUgo

## AWS Services 
Frontend:
* AWS BEANSTALK
  * Tomcat (app server)
  * Autoscaling
  * Nginx : Load Balancer Replacement
  * S3/EFS: Storage

Backend:
* RDS Instance: Databases
* Elastic Cache
* Active MQ
* Route53
* CloudFront: Content Delivery
