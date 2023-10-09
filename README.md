# aws-storage
AWS-Storage-Learning
# AWS Storage Labs 🚀

Welcome to the AWS Storage Labs repository! This collection of labs will guide you through various AWS storage services and concepts. Each lab comes with detailed step-by-step instructions, making it easy to learn and experiment with AWS storage solutions.

## Lab 1: Creating an S3 Bucket 📦

🔹 **Objective**: Learn how to create an Amazon S3 bucket using the AWS Management Console.

**Steps**:
1. Log in to the AWS Management Console.
2. Navigate to the S3 service.
3. Click the "Create bucket" button.
4. Enter a unique bucket name and choose a region.
5. Configure optional settings such as versioning, logging, and tags.
6. Review and create the bucket.

## Lab 2: Creating an S3 Bucket Using CLI 💻

🔹 **Objective**: Create an Amazon S3 bucket using the AWS Command Line Interface (CLI).

**Steps**:
1. Open your command line interface.
2. Use the `aws s3api create-bucket` command to create a new S3 bucket.
3. Specify the bucket name and region.
4. Verify the bucket creation.

## Lab 3: S3 Versioning 🔄

🔹 **Objective**: Understand and enable versioning for an S3 bucket.

**Steps**:
1. Navigate to the S3 bucket you created in Lab 1.
2. Access the bucket properties.
3. Enable versioning for the bucket.

## Lab 4: S3 Cross-Region Replication 🌐

🔹 **Objective**: Configure cross-region replication for an S3 bucket.

**Steps**:
1. Navigate to the S3 bucket you created in Lab 1.
2. Configure cross-region replication by selecting source and destination buckets.
3. Review and confirm the replication setup.

## Lab 5: AWS S3 Object Lifecycle 🕒

🔹 **Objective**: Set up object lifecycle policies for automatic data management in S3.

**Steps**:
1. Navigate to the S3 bucket you created in Lab 1.
2. Configure an object lifecycle policy to transition objects to Glacier storage.

## Lab 6: AWS EFS Demo 📂

🔹 **Objective**: Explore Amazon Elastic File System (EFS) by creating and using a shared file system.

**Steps**:
1. Log in to the AWS Management Console.
2. Navigate to the EFS service.
3. Create a new file system.
4. Configure security group settings.
5. Mount the EFS file system on an EC2 instance.
6. Test the shared file system.

## Lab 7: Hosting a Static Website 🌐

🔹 **Objective**: Host a static website on Amazon S3.

**Steps**:
1. Create an S3 bucket to store your website files.
2. Upload your website files to the S3 bucket.
3. Configure the S3 bucket for static website hosting.
4. Access and test your static website.

