# AWS CloudFormation Deployment
## Description: 
This package contains a CloudFormation template (cf_00_Secrets_TT.yml, cf_01_VPC_TT.yml and cf_02_SG_TT.yml ) to deploy IAM, VPC and Security Group on AWS. The template provisions an EC2 instance with Apache web server pre-installed, configured, and serving a basic webpage.

## How to Run the Containerized Application
### Prerequisites
* AWS CLI installed and configured with appropriate IAM permissions.
* Docker installed (optional, for running locally).

### Steps to Deploy the Web Server EC2 Instance
1. Clone this repository to your local machine:
git clone https://github.com/Js7Days/AWSCloudFormation_AT2_Part3.git
2. Navigate to the repository directory:
cd AWSCloudFormation_AT2_Part3
3. Open YAML Sript:
   - cf_00_Secrets_TT.yml
   - cf_01_VPC_TT.yml
   - cf_02_SG_TT.yml
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
