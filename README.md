# CloudResume-Frontend

AWS CLOUD RESUME CHALLENGE

The Cloud Resume Challenge is a multiple-step resume project which helps build and demonstrate skills fundamental to pursuing a career as an AWS Cloud Engineer

These are the steps that are part of the challenge:

1.  Certification
2.  HTML
3.  CSS
4.  Static Website
5.  HTTPS
6.  DNS
7.  Javascript
8.  Database
9.  API
10. Python
11. Infrastructure as Code
12. Source Control
13. CI/CD (Back end)
14. CI/CD (Front end)

How I achieved the goal:

-To upload Webiste HTML files to S3 bucket, I created another repository on GitHub   
-Wrote a CICD pipeline in GitHub Actions to install AWS CLI and use COPY to add files into S3       
  
In the end:  
You can either manually invalidate cloudfront or use local-exec provisioner to let Cloudfront re-cache after updating HTML files into S3

_For Frontend please review the CloudResume-Frontend repository
