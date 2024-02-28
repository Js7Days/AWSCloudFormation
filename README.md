# AWS CloudFormation Deployment
## Description: 
This package contains a CloudFormation template (cf_00_Secrets_TT.yml, cf_01_VPC_TT.yml, cf_02_SG_TT.yml, cf_03_RDS_TT and cf_04_EC2_TT ) to deploy IAM, VPC, Security Group, Database and EC2 on AWS Cloud Platform.
## How to Run the Containerized Application
### Prerequisites
* AWS CLI installed and configured with appropriate IAM permissions.
* Docker installed (optional, for running locally).

### Steps to Deploy the Web Server EC2 Instance
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
4. Deploy the CloudFormtion stack using the CloudFormation console:
   https://console.aws.amazon.com/cloudformation/ 
5. Click on "Create Stack" -> Choose "Upload a template file" and select the template file.
6. Specify your stack name and parameters.
7. Configure stack options tags, permissions stack 
8. Review and Create -> Next -> Click Submit

## About me
Name: Thong Thao <br>
Student ID:  <br>
TAFE Student
