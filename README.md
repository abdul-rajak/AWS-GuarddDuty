# AWS-GuarddDuty
Enable AWS GuardDuty to secure AWS account.

GuardDuty :
- Amazon GuardDuty is a threat detection service that continuously monitors for malicious activity and unauthorized behavior to protect AWS accounts, workloads, and data stored in Amazon S3. 
- GuardDuty analyzes  AWS CloudTrail event logs, Amazon VPC Flow Logs, and DNS logs across the AWS Region.
- The finding which can be detected by GuardDuty is for these resources in AWS :

Instance, AccessKey, S3Bucket, Kubernetes cluster, ECS cluster, Container, RDS, DBInstance, Lambda.

# AWS GuardDuty Findings contains the following information :

- Account ID 
- Count
- Created at
- Finding ID
- Finding type
- Region
- Resource ID 
- Scan ID 
- Severity 
- Updated at 

# Activating AWS GuardDuty :

1. Go to AWS GuardDuty Service and Click on Get Started.
2. AWS offers 30 days free trail for new users , now click on enable GuardDuty to start the service
3. Now, You have Successfully enabled AWS GuardDuty.
4. If your AWS account has any finding or malicious activity, it  will be available on Finding Console.
5. AWS GuardDuty Findings has three types of findings, they are :
- Low Severity Findings.
- Medium Severity Findings.
- high Severity Findings.
6. To read logs of findings, click on the finding.
  
# Protection From Malware

- To Secure account from Threats and Malware, use Malware scan to check Malware in your AWS account region.

# AWS GuardDuty useage :

we can use GuardDuty to monitor logs and detect the Findings from different AWS services.

# Pricing :

- AWS GuardDuy is free for first 30 days.
- AWS GuardDuty Billing changes from region to region.
- AWS GuardDuty is billed based on amount of data it detects and analysis.
