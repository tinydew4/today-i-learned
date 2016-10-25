# AWS 공인 솔루션스 아키텍트 - 어소시에이트

## 소개

AWS 공인 솔루션스 아키텍트 - 어소시에이트 레벨 시험은 솔루션스 아키텍트의 역할을
수행하는 개인을 위한 것입니다. 이 시험은 수험자의 다음 능력을 검증합니다:

* 아키텍처 모범 사례를 통하여 만들어질 솔루션을 정의하기 위한 요구사항을
  확인하고 수집합니다.
* 프로젝트의 라이프 사이클 전반에 걸쳐 개발자와 시스템 관리자에게 아키텍처 모범
  사례에 대한 지침을 제공할 수 있어야 합니다.

이 레벨에서 요구되는 지식과 기술은 다음 영역과 세부목표를 모두 포함합니다. 지식
레벨은 다음 대부분을 가지고 있는 것으로 정의 될 수 있습니다:

### AWS 지식

* Hands-on experience using compute, networking, storage, and database AWS services
* Professional experience architecting large scale distributed systems
* Understanding of Elasticity and Scalability concepts
* Understanding of network technologies as they relate to AWS
* A good understanding of all security features and tools that AWS provides and how they relate to traditional services
* A strong understanding on how to interact with AWS (AWS SDK, AWS API, Command Line Interface, AWS CloudFormation)
* Hands-on experience with AWS deployment and management services

### 일반 IT 지식

* Excellent understanding of typical multi-tier architectures: web servers (Apache, nginx, IIS), caching, application servers, and load balancers
* RDBMS (MySQL, Oracle, SQL Server), NoSQL
* Knowledge of message queuing and Enterprise Service Bus (ESB)
* Familiarity with loose coupling and stateless systems
* Understanding of different consistency models in distributed systems
* Experience with CDN, and performance concepts
* Network experience with route tables, access control lists, firewalls, NAT, HTTP, DNS, IP and OSI Network
* Knowledge of RESTful Web Services, XML, JSON
* Familiarity with the software development lifecycle
* Work experience with information and application security including public key encryption, SSH, access credentials, and X.509 certificates

These training courses or other equivalent methodologies will assist in exam preparation:

* Architecting on AWS (aws.amazon.com/training/architect)
* In-depth knowledge or training in at least one high-level programming language
* AWS Cloud Computing Whitepapers (aws.amazon.com/whitepapers)
  * Overview of Amazon Web Services
  * Overview of Security Processes
  * AWS Risk & Compliance Whitepaper
  * Storage Options in the Cloud
  * Architecting for the AWS Cloud: Best Practices
* Experience deploying hybrid systems with on-premise and AWS components
* Utilization of the AWS Architecture Center website (aws.amazon.com/architecture)

**참고:** This examination blueprint includes weighting, test objectives, and example content. Example topics and
concepts are included to clarify the test objectives; they should not be construed as a comprehensive listing of all
of the content of this examination. 

The table below lists the domains measured by this examination and the extent to which they are represented.

| Domain | % of Examination |
|---|---|
| 1.0 Designing highly available, cost efficient, fault tolerant, scalable systems | 60% |
| 2.0 Implementation/Deployment | 10% |
| 3.0 Data Security | 20% |
| 4.0 Troubleshooting | 10% |
| TOTAL | 100% |

## Response Limits

The examinee selects from four (4) or more response options the option(s) that best completes the statement or
answers the question. Distracters or wrong answers are response options that examinees with incomplete
knowledge or skill would likely choose, but are generally plausible responses fitting into the content area defined
by the test objective.

Test item formats used in this examination are:

* Multiple-choice: examinee selects one option that best answers the question or completes a statement.
The option can be embedded in a graphic where the examinee “points and clicks” on their selection
choice to complete the test item.
* Multiple-response: examinee selects more than one option that best answers the question or completes
a statement.
* Sample Directions: Read the statement or question and from the response options, select only the
option(s) that represent the most correct or best answer(s) given the information.

## Content Limits
1. Domain 1.0: Designing highly available, cost efficient, fault tolerant, scalable systems
  1.1. Identify and recognize cloud architecture considerations, such as fundamental components and effective designs.
  Content may include the following:
  * How to design cloud services
  * Planning and design
  * Monitoring
  * Familiarity with:
  * Best practices
  * Developing to Client Specifications including pricing/cost (e.g., on Demand vs. Reserved vs. Spot, RTO and RPO DR Design)
  * Architectural trade-off decisions (high availability vs. cost, Amazon Relational Database Service (RDS) vs. installing your own database on Amazon Elastic Compute Cloud (EC2))
  * Integrating with existing development environments and building scalable architecture
  * Elasticity and scalability
1. Domain 2.0: Implementation/Deployment
  1.1. Identify the appropriate techniques and methods using Amazon EC2, Amazon S3, Elastic Beanstalk,
  CloudFormation, Amazon Virtual Private Cloud (VPC), and AWS Identity and Access Management (IAM)
  to code and implement a cloud solution.
  Content may include the following:
  * Configure an Amazon Machine Image (AMI)
  * Operate and extend service management in the private cloud
  * Configure compliance in the private and public cloud
  * Launching instances in a variety of geographical regions
1. Domain 3.0: Data Security
  1.1. Recognize and implement secure procedures for optimum cloud deployment and maintenance.
  Content may include the following:
  * Cloud Security Best Practices
    * How to build and use a threat model
    * How to build and use a data flow diagram for risk management
      * Use cases
      * Abuse Cases (Negative use cases)
  * Security Architecture with AWS
    * Shared Security Responsibility Model
    * AWS Platform Compliance
    * AWS security attributes (customer workloads down to physical layer)
    * Security Services
    * AWS Identity and Access Management (IAM)
    * Amazon Virtual Private Cloud (VPC)
    * CIA and AAA models, ingress vs. egress filtering, and which AWS services and features fit
    * “Core” Amazon EC2 and S3 security feature sets
    * Incorporating common conventional security products (Firewall, IDS:HIDS/NIDS, SIEM, VPN)
    * Design Patterns
    * DDOS mitigation
    * Encryption solutions
    * Complex access controls (building sophisticated security groups, ACLs, etc.)
    * Amazon CloudWatch for the security architect
  1.1. Recognize critical disaster recovery techniques and their implementation.
  Content may include the following:
  * Disaster Recovery
    * Recovery time objective
    * Recovery point objective
    * Amazon Elastic Block Store
  * AWS Import/Export
  * AWS Storage Gateway
  * Amazon Route53
  * Testing the recovered data
1. Domain 4.0: Troubleshooting
  Content may include the following:
* General troubleshooting information and questions
