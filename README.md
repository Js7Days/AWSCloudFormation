# AWS CloudFormation Deployment
## Description: 
This package contains a CloudFormation template (cf_00_Secrets_TT.yml, cf_01_VPC_TT.yml, cf_02_SG_TT.yml, cf_03_RDS_TT and cf_04_EC2_TT ) to deploy IAM, VPC, Security Group, Database and EC2 on AWS Cloud Platform.
## How to Run the Containerized Application
### Prerequisites
* AWS CLI installed and configured with appropriate IAM permissions.
* Docker installed (optional, for running locally).

### Steps to Download the YML script.
#### For Linux.
1. Clone this repository to your local machine:
wget or git clone https://github.com/Js7Days/AWSCloudFormation_AT2_Part3.git
2. Navigate to the repository directory:
cd AWSCloudFormation_AT2_Part3
3. There are 5 YAML Sript:
   - cf_00_Secrets
   - cf_01_VPC_TT
   - cf_02_SG_TT
   - cf_03_RDS_TT
   - cf_04_EC2_TT
#### For Microsoft Windows
Copy and paste this link to the browser: https://github.com/Js7Days/AWSCloudFormation_AT2_Part3/archive/refs/heads/main.zip

### Steps to Deploy the CloudFormation YML script
1. Deploy the CloudFormtion stack using the CloudFormation console:
   https://console.aws.amazon.com/cloudformation/ 
2. Click on "Create Stack" -> Choose "Upload a template file" and select the template file.
3. Specify your stack name and parameters.
4. Configure stack options tags, permissions stack 
5. Review and Create -> Next -> Click Submit

## Important Noted:
Please note that you must change the scripts before deploying on the CloudFormation console.
1. in cf_00_Secrets
   Default: Hello@123 | You must change your password
2. cf_01_VPC_TT
   You can deploy directly to this file, but please note that after deployment is completed, vpcid, security group and subnets.
3. cf_02_SG_TT
   VpcId: vpc-0072f1135f3693c5d | You must change your vpc id as mentioned in step 2, there are 3 vpc-id in this script.
4. cf_03_RDS_TT
   There are 2 SubnetIds in this script, you must change to your SubnetIds as mentioned in step 2. 
5. cf_04_EC2_TT
   There 2 SecurityGroupIds in this script, you must change to your SecurityGroupIds as mentioned in step 2.
   
## About me
Name: Thong Thao <br>
Student ID:  <br>
TAFE Student
