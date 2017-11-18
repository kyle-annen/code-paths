# AWS (Amazon Web Services)

Cloud computing provider.


## Level 1

* Read [The NIST Definition of Cloud Computing](http://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf)
* Read [Overview of Amazon Web Services](https://d0.awsstatic.com/whitepapers/aws-overview.pdf)
* Complete the [IAM user walkthrough](http://docs.aws.amazon.com/IAM/latest/UserGuide/id_users_create.html)
* Complete the [AWS single public subnet VPC walkthrough](http://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/VPC_Scenario1.html).
* Complete the [AWS & Terraform Workshop](https://github.com/trptcolin/cloud-native-aws-terraform-workshop), part 1.

### You should be able to

* Describe what many AWS services are for.
* Create an IAM user with (multi-factor authentication).
* Create an EC2 host and SSH into it.
* Deploy a simple application to EC2.
* Use IAM Roles on EC2 hosts to access AWS APIs while avoiding saving AWS credentials on EC2 hosts.
* Set up a simple VPC
* Understand the detailed charges on the AWS billing console.


## Level 2

* Complete the [AWS & Terraform Workshop](https://github.com/trptcolin/cloud-native-aws-terraform-workshop), parts 2-4.
* Read [Architecting for the Cloud: AWS Best Practices](https://d0.awsstatic.com/whitepapers/AWS_Cloud_Best_Practices.pdf).
* Complete the [AWS public/private subnets VPC walkthrough](http://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/VPC_Scenario2.html).

### You should be able to

* Understand and describe the AWS networking primitives: VPCs, subnets, security groups, internet gateways, NAT, routing tables, network ACLs.
* Build a VPC from scratch, from memory, through the AWS Management Console, including a public subnets with a bastion host, a private subnet with another EC2 host, and security groups, network ACLs, and a NAT instance/gateway that allow the expected network communications to happen.
* Build a highly-available, resilient system in AWS, including Auto Scaling Groups and Load Balancers.


## Level 3

* Use the [AWS Total Cost of Ownership (TCO) Calculator](https://awstcocalculator.com/) to compare and estimate total cost of ownership of on-premises/colocated environments with AWS, and take the time to understand the given cost breakdowns and assumptions (not just the top-line comparison).
* Read [AWS Security Best Practices](https://d0.awsstatic.com/whitepapers/Security/AWS_Security_Best_Practices.pdf).
* Complete the [acloud.guru Solutions Architect - Associate training course](https://acloud.guru/learn/aws-certified-solutions-architect-associate)

### You should be able to

* "Lift and shift" a company's existing infrastructure to AWS.
* Use CloudFormation or Terraform to build AWS infrastructure in an automated way.
* Advise customers on the AWS pricing model.
* Understand the AWS Shared Responsibility Model, and what security is handled by AWS vs. needs to be handled by us.
* Pass the [AWS Certified Solutions Architect - Associate](https://aws.amazon.com/certification/certified-solutions-architect-associate/) exam. Recommended study resources after the acloud.guru course: [whizlabs practice exams](https://www.whizlabs.com/aws-solutions-architect-associate/).


## Level 4

* Read [AWS Well-Architected Framework](https://d0.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf).
* Complete the [acloud.guru Sysops Administrator - Associate training course](https://acloud.guru/learn/aws-certified-sysops-administrator-associate).

### You should be able to

* Pass the [AWS Certified Sysops Administrator - Associate](https://aws.amazon.com/certification/certified-sysops-admin-associate/) exam.

