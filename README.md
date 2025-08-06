# Cloud-Storage-Setup

COMPANY : CODTECH IT SOLUTIONS

NAME : SANJANA MARIA P.S

INTERN ID : CT04DH2447

DOMAIN : CLOUD COMPUTING

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH

# DESCRIPTION :
In this project, I have implemented and configured cloud storage using Amazon Simple Storage Service (Amazon S3), a scalable and secure object storage service provided by Amazon Web Services (AWS). The goal of this setup was to create a reliable and cost-effective storage solution for storing and accessing files (such as images, documents, and backups) used by my application.

1.Logging into AWS Console I began by logging into the AWS Management Console using my AWS account credentials. AWS provides a highly intuitive and user-friendly interface for managing its services.

2.Navigating to S3 Service From the Services menu, I selected “S3” under the Storage section. This redirected me to the Amazon S3 dashboard where I could manage existing buckets or create a new one.

3.Creating a New S3 Bucket To create a new storage bucket, I clicked on the “Create bucket” button and followed the wizard:

Bucket Name: I provided a unique name like myapp-storage-bucket (bucket names must be globally unique).

AWS Region: I selected a region closest to my user base for better latency (e.g., Asia Pacific (Mumbai) ap-south-1).

Block Public Access Settings: By default, all public access settings were blocked. However, for specific use-cases like hosting static websites, I later modified these settings accordingly.

Versioning: I enabled versioning for the bucket to keep track of file changes and maintain historical versions.

Encryption: To ensure data security, I enabled S3-managed encryption (SSE-S3), which automatically encrypts data at rest.

Once all configurations were set, I clicked on “Create bucket”, and the bucket was successfully created.

4.Uploading Files to the Bucket After creating the bucket, I uploaded files directly from my local system using the “Upload” button. AWS S3 also supports CLI and SDKs for programmatic uploads, which I used for automation later in the project.

5.Setting Object Permissions By default, files uploaded to S3 are private. I configured object-level permissions to control who can access which files:

For public access (e.g., images for a website), I granted public-read access to specific objects.

I also defined Bucket Policies using JSON to allow or restrict access to users or roles.

# OUTPUT 

<img width="1366" height="636" alt="Image" src="https://github.com/user-attachments/assets/ea6d0625-df98-4497-a6b1-45ebc76041ea" />
<img width="1366" height="635" alt="Image" src="https://github.com/user-attachments/assets/db391418-b7bd-45d6-b7f1-64b965f36d75" />
