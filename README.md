# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-

### NAME: SURIYA PRAKASH S
### REG NO: 212223100055

# Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.

# Procedure
### a) Steps to Create a first S3 Bucket:

Step 1: Sign in to the AWS Management Console Go to https://console.aws.amazon.com/s3. 

Step 2: Open the S3 Service In the console, type S3 in the search bar and select S3 to open the service dashboard. 

Step 3: Create Bucket Click the Create bucket button. 

Step 4: Configure Bucket Settings

• Bucket name: Choose a globally unique name. • AWS Region: Select the region where you want to store your data.

Step 5: Object Ownership Choose between: ▪ ACLs disabled (recommended) – Bucket owner has full control. ▪ ACLs enabled – Control access via access control lists.

Step 6: Block Public Access Settings By default, all public access is blocked. Leave it as-is unless you need public access. 

Step 7: Bucket Versioning (optional) Choose whether to enable versioning for objects in the bucket.

Step 8: Encryption (optional) Select encryption options (SSE-S3, SSE-KMS, or none). 

Step 9: Advanced Settings (optional) Add tags, configure logging, etc. 

Step 10: Create the Bucket Click Create bucket at the bottom of the page.

### b) Steps to launch an EC2 Instance

Go to the EC2 Dashboard in AWS Console.

Click on “Launch Instance”.

Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).

Select an instance type (e.g., t2.micro for Free Tier).

Create or choose a key pair for SSH access.

Configure network settings (use default VPC/subnet).

Configure storage (default root volume is fine).

Review the settings and click “Launch Instance”.

Wait for the instance to enter the running state.

### c) Step 3: Connect to Your Instance

• Linux: Use SSH command with your .pem key. • Windows: Use RDP with decrypted admin password.

### d) Steps to Clean Up (Terminate the Instance)

Go to EC2 Instances.
Select your instance → Instance State → Terminate.

# Output:

## Creating S3 Bucket:
<img width="1919" height="876" alt="3" src="https://github.com/user-attachments/assets/74edaa73-5aee-4487-b051-7857f975ef67" />


## Uploading Files in Bucket:
<img width="1919" height="873" alt="4" src="https://github.com/user-attachments/assets/8c8abadd-ba1d-4978-97ed-9adbc5003195" />


## Launching EC2 Instance:
<img width="1919" height="866" alt="7" src="https://github.com/user-attachments/assets/7d1f7cd7-5d23-45c6-816f-dbdfe0669d8f" />


## Connecting Instance:
<img width="1919" height="867" alt="6" src="https://github.com/user-attachments/assets/5f560e5e-8b4f-415c-9525-32576c5d5290" />


## Stopping the Instance:

<img width="1919" height="872" alt="8" src="https://github.com/user-attachments/assets/3a9d93f8-cfe4-4deb-b0f4-6937b8eeff76" />


# Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
