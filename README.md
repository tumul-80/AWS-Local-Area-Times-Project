# AWS Solutions Architect Project: Local Area Times

## Project Overview
This project implements a secure, scalable web application infrastructure for Local Area Times newspaper, featuring:
- VPC with security groups and NACLs for network isolation
- IAM users, groups, roles, and policies for access control
- SQS queue and Lambda function integration for news processing
- Site-to-Site VPN connection for hybrid cloud connectivity

## Architecture
<img width="642" height="443" alt="image" src="https://github.com/user-attachments/assets/0404be72-017a-42e4-9833-e4fb28a358e1" />


## Implementation Details
1. Apply appropriate firewall controls to the Amazon VPC that includes the Local Area Times webserver to permit inbound web traffic only, and outbound responses to that traffic only.

2. Create an Identity and Access Management implementation that provides appropriate levels of control for the staff at Local Area Times, including the IT team, and Managers.

3. Configure policy settings on the serverless components of the Community News solution, including SQS and Lambda resources, granting the minimum necessary permissions to allow the solution to function.

4. Verify that the solution continues to function after hardening security settings.

5. Enable Virtual Private Network connectivity to the headquarters router from the AWS solution, to allow private administration of web servers in the future.
