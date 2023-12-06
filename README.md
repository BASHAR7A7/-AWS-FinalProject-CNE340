# AWS-Final-Project-CNE340

## Media Conversion and Management  
### Steps to create an AWS setup for S3, IAM and Media Convert:
  #### Step 1: Sign in to your AWS Management Console

First, you need an AWS account. If you don't have one, you'll need to create it. Once you have an account, sign in to the AWS Management Console.

#### Step 2: Create an Amazon S3 Bucket

S3 (Simple Storage Service) is an object storage service that offers scalability, data availability, security, and performance. Here's how to create a bucket:

1. Navigate to the S3 service.
2. Click on "Create bucket".
3. Give your bucket a name, and select a region.
4. Set the properties for the bucket, such as versioning, logging, etc., as per your requirements.
5. Set the permissions for your bucket. By default, all the permissions are denied to everyone.
6. Review your settings and click 'Create bucket'.

#### Step 3: Create an IAM User and Assign Permissions

IAM (Identity and Access Management) enables you to manage access to AWS services and resources securely. Here's how to create a user:
1. Navigate to the IAM service.
2. In the navigation pane, choose "Users", and then choose "Add user".
3. Give your user a name.
4. Select the "Programmatic access" access type.
5. In the "Set permissions" section, assign appropriate permissions to your user.
6. Review the user, and if everything is fine, click 'Create user'.

#### Step 4: Set Up AWS Media Convert
Media Convert is a file-based video transcoding service with broadcast-grade features:
1. Go to your AWS Management Console and open the MediaConvert console.
2. Choose your region.
3. In the navigation pane, under "Job management", choose "Jobs".
4. Choose "Create job".
From here, you can choose the appropriate settings for your job based on your source media and how you want to convert it.