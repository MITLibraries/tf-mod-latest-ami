This module simply grabs the latest Amazon Linux 2 AMI image. It is currently only used for our EC2 instance bastion host, but may be used for other resources or modified to get the latest AMI for different Operating Systems.

There are currently no inputs or variables needed for this module (this may change if we add more and/or different filtering for other AMI). 

## Outputs

| Name             | Description                  |
| ---------------- | ---------------------------- |
| ec2_linux_ami_id | Latest Amazon Linux 2 AMI ID |
