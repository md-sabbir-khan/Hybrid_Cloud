# Hybride_Cloud
Complete AWS Auto Deploy  Web-Server infrastructure using Terraform

Task 1
1. Create the key and security group which allow the port 80.
2. Launch EC2 instance.
3. In this Ec2 instance use the key and security group which we have created in step 1.
4. Launch one Volume (EBS) and mount that volume into /var/www/html and take snapshot, and deploy code from git-hub.
7. Create S3 bucket, and copy/deploy the images from git-hub into the s3 bucket and change the permission to public readable.
8. Create a Cloud-front using s3 bucket(which contains images) and use the Cloud-front URL to update in code in /var/www/html
