Bronze bucket name - youtube-data-pipeline-bronze-dev-76
Silver bucket name - youtube-data-pipeline-silver-dev-76
Gold bucket name - youtube-data-pipeline-gold-dev-76

Script bucket name - youtube-data-pipeline-script-dev-76

Data is transfer from local to S3 using aws cli.

steps:
1. Download & install aws cli.
2. Create IAM user with Administrative access
3. connect our aws account to cli through Access Keys
4. Transfer data from local to S3 using cli/bash commands.

Note: 
All bash/cli commands are written in aws_copy.sh file in order.

1. upload all CSV into bronze bucket
2. upload JSON into bronze bucket

Create roles and attach policies in aws.