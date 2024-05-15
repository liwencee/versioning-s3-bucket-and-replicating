# versioning-s3-bucket-and-replicating
log in to my AWS CONSOLE
then search S3 bucket, i create a bucket, follow the prompt and bucket was created
i navigated to properties on the bucket and enable versioning
configure cross replication amongst each region

in the S3 bucket properties navigate to the management tab
click on thr replication and configure cross-region replication
1. source region: your bucket's region
2. Destination Region: Another region of your choice
3.IAM Role: Create or select an IAM role replications
