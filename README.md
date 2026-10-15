<h1 align="center"
style="background\:rgb(255, 190, 92);
color:rgb(35, 47, 62);
padding:24px;
border-radius:12px;">
☁️ AWS Cloud Learning & Teaching Hub
</h1>

<p align="center">
&#x20; <img src="[https://img.shields.io/badge/AWS-Cloud%20Computing-FF9900?style=for-the-badge&logo=amazonaws&logoColor=232F3E](https://img.shields.io/badge/AWS-Cloud%20Computing-FF9900?style=for-the-badge\&logo=amazonaws\&logoColor=232F3E)" alt="AWS Cloud Computing"/>
&#x20; <img src="[https://img.shields.io/badge/Learning-From%20Zero%20to%20Practical-2E8B57?style=for-the-badge](https://img.shields.io/badge/Learning-From%20Zero%20to%20Practical-2E8B57?style=for-the-badge)" alt="Learning roadmap"/>
&#x20; <img src="[https://img.shields.io/badge/Focus-Hands--On%20Labs-0078D4?style=for-the-badge](https://img.shields.io/badge/Focus-Hands--On%20Labs-0078D4?style=for-the-badge)" alt="Hands-on labs"/>
&#x20; <img src="[https://img.shields.io/badge/Documentation-Open%20Learning-7B61FF?style=for-the-badge](https://img.shields.io/badge/Documentation-Open%20Learning-7B61FF?style=for-the-badge)" alt="Open learning"/>
</p>

<table align="center">
<tr>
<td width="200" align="center" valign="middle">

<img src="[https://media.giphy.com/media/f3iwJFOVOwuy7K6FFw/giphy.gif](https://media.giphy.com/media/f3iwJFOVOwuy7K6FFw/giphy.gif)" width="180" alt="Animated technology illustration"/>

</td>
<td align="center" valign="middle">

<img src="[https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=2800&pause=900&color=FF9900&center=true&vCenter=true&width=650&lines=AWS+Cloud+Fundamentals;Compute%2C+Storage+%26+Networking;IAM+%26+Cloud+Security;Serverless+%26+Cloud+Architecture;Data+Engineering+on+AWS;Learning+by+Building](https://readme-typing-svg.demolab.com?font=Fira+Code\&size=24\&duration=2800\&pause=900\&color=FF9900\&center=true\&vCenter=true\&width=650\&lines=AWS+Cloud+Fundamentals;Compute%2C+Storage+%26+Networking;IAM+%26+Cloud+Security;Serverless+%26+Cloud+Architecture;Data+Engineering+on+AWS;Learning+by+Building)" alt="AWS learning topics"/>

</td>
</tr>
</table>

<p align="center">
&#x20; \<b>Understand the cloud. Build real solutions. Learn how the pieces fit together.\</b>
</p>

<p align="center">
AWS can feel overwhelming when you first encounter hundreds of services, unfamiliar terminology, and complicated architecture diagrams. This repository breaks the cloud into manageable concepts, explains the services in simple language, and connects theory with practical examples you can build yourself.
</p>

---

## 🚀 Welcome to the AWS Cloud Learning Hub

Cloud engineering is not about memorising service names.

It is about understanding a problem, selecting the right building blocks, connecting them securely, controlling costs, and designing systems that work reliably.

This repository is my structured learning and teaching space for **Amazon Web Services (AWS)**. It is designed for beginners who want to understand cloud computing properly, as well as learners preparing for cloud engineering, data engineering, DevOps, and AI-related roles.

Instead of simply describing what a service does, the goal is to understand:

- **What problem does this service solve?**
- **Why would an organisation choose it?**
- **How does it connect with other AWS services?**
- **How can we implement it through the AWS Console, CLI, or code?**
- **What are its security, availability, and cost implications?**

The focus is simple: learn the concepts, practise them, and gradually build systems that resemble real-world cloud solutions.

## 🎯 What Will You Learn?

| Learning Area            | What You Will Explore                                                                  |
| ------------------------ | -------------------------------------------------------------------------------------- |
| ☁️ Cloud Fundamentals    | Cloud computing, deployment models, elasticity, scalability, and pay-as-you-go pricing |
| 🕰️ AWS Background       | The history of AWS and how cloud infrastructure evolved                                |
| 🌍 Global Infrastructure | Regions, Availability Zones, edge locations, and high availability                     |
| 🖥️ Compute              | EC2, Lambda, Auto Scaling, Elastic Load Balancing, and containers                      |
| 🗄️ Storage              | S3, EBS, EFS, backup, lifecycle policies, and storage classes                          |
| 🌐 Networking            | VPC, subnets, route tables, Internet Gateway, NAT Gateway, DNS, and security groups    |
| 🔐 Security & Identity   | IAM users, roles, policies, least privilege, KMS, and secure access                    |
| 🛢️ Databases            | RDS, DynamoDB, database selection, backups, and replication                            |
| ⚙️ Serverless            | Lambda, API Gateway, EventBridge, SQS, and SNS                                         |
| 📊 Monitoring            | CloudWatch, CloudTrail, logs, metrics, alarms, and troubleshooting                     |
| 🐍 Cloud Automation      | AWS CLI, Python, Boto3, SDKs, and infrastructure automation                            |
| 🏗️ Architecture         | Designing systems for security, reliability, performance, and cost                     |
| 🧱 Data Engineering      | S3 data lakes, Glue, Athena, Redshift, ingestion, and ETL/ELT workflows                |
| 🤖 AI & Machine Learning | Amazon Bedrock, SageMaker, and cloud-based AI architectures                            |
| 💰 Cost Management       | Budgets, billing, pricing models, resource cleanup, and cost optimisation              |

---

## 📚 Table of Contents

1. [Introduction to Cloud Computing](#-1-introduction-to-cloud-computing)
2. [A Short History of AWS](#-2-a-short-history-of-aws)
3. [How the AWS Cloud Works](#-3-how-the-aws-cloud-works)
4. [AWS Service Map](#-4-aws-service-map)
5. [Learning Roadmap](#-5-learning-roadmap)
6. [Architecture Diagrams](#-6-architecture-diagrams)
7. [Hands-On Labs](#-7-hands-on-labs)
8. [Real-World Projects](#-8-real-world-projects)
9. [AWS CLI and Python Automation](#-9-aws-cli-and-python-automation)
10. [Security and Cost Best Practices](#-10-security-and-cost-best-practices)
11. [Repository Structure](#-11-repository-structure)
12. [Useful Learning Resources](#-12-useful-learning-resources)
13. [How to Use This Repository](#-13-how-to-use-this-repository)
14. [Learning Progress](#-14-learning-progress)
15. [About the Author](#-15-about-the-author)

---

## ☁️ 1. Introduction to Cloud Computing

Before learning AWS services, it is important to understand the problem cloud computing solves.

Imagine a company wants to launch a website. Traditionally, it might purchase physical servers, arrange networking, configure storage, maintain hardware, and plan capacity for future traffic.

This approach can require significant upfront investment and ongoing maintenance.

Cloud computing provides another option: access computing resources over the internet and pay according to the services and capacity you use.

### Traditional Infrastructure vs Cloud Computing

| Traditional Infrastructure                      | Cloud Computing                                   |
| ----------------------------------------------- | ------------------------------------------------- |
| Purchase physical hardware                      | Provision resources on demand                     |
| Large upfront investment                        | Usage-based pricing options                       |
| Hardware capacity can take time to expand       | Capacity can often be increased much faster       |
| Organisation maintains physical infrastructure  | Cloud provider operates the underlying facilities |
| Capacity planning is tied to purchased hardware | Resources can be scaled according to requirements |

Cloud computing does not automatically make every system cheaper, more secure, or more reliable. Good architecture, correct configuration, monitoring, and cost management still matter.

### Essential Cloud Concepts

| Concept               | Human-Friendly Explanation                                                          |
| --------------------- | ----------------------------------------------------------------------------------- |
| Scalability           | Increasing or decreasing capacity as requirements change                            |
| Elasticity            | Automatically or quickly adjusting resources to changing demand                     |
| High Availability     | Designing a system to remain available despite certain component failures           |
| Fault Tolerance       | Continuing operation when specified failures occur                                  |
| On-Demand Resources   | Provisioning services when they are needed                                          |
| Pay-as-You-Go         | Paying for measured usage where the pricing model supports it                       |
| Shared Responsibility | Understanding which security tasks AWS handles and which remain your responsibility |

---


<p align="center">
&#x20; \<a href="[https://aws.amazon.com/about-aws/our-origins/](https://aws.amazon.com/about-aws/our-origins/)">
&#x20;   \<img src="[https://img.shields.io/badge/Explore-Official%20AWS%20History-FF9900?style=for-the-badge&logo=amazonaws&logoColor=232F3E](https://img.shields.io/badge/Explore-Official%20AWS%20History-FF9900?style=for-the-badge\&logo=amazonaws\&logoColor=232F3E)" alt="Read the official AWS history"/>
&#x20; \</a>
</p>

**The key takeaway:** AWS is not one product. It is a collection of services that work together to provide the building blocks for cloud-based systems.



-----------------
## 🧩 4. AWS Service Map

AWS offers many services, and its service portfolio changes over time. This section focuses on the important service families you should understand first rather than treating every service as something to memorise.

### 🖥️ Compute

| Service                | What It Does                                      | Example Use Case                                   |
| ---------------------- | ------------------------------------------------- | -------------------------------------------------- |
| Amazon EC2             | Provides virtual servers                          | Hosting an application on a virtual machine        |
| AWS Lambda             | Runs code without requiring you to manage servers | Processing an uploaded file                        |
| Amazon ECS             | Runs containerised applications                   | Deploying a container-based backend                |
| Amazon EKS             | Managed Kubernetes control plane                  | Running Kubernetes workloads                       |
| AWS Auto Scaling       | Adjusts supported resource capacity               | Scaling application capacity with demand           |
| Elastic Load Balancing | Distributes supported incoming traffic            | Distributing requests across application instances |

### 🗄️ Storage

| Service                    | What It Does                            | Example Use Case                                      |
| -------------------------- | --------------------------------------- | ----------------------------------------------------- |
| Amazon S3                  | Object storage                          | Data lakes, files, logs, and backups                  |
| Amazon EBS                 | Block storage for EC2                   | Attaching persistent disks to virtual servers         |
| Amazon EFS                 | Managed shared file storage             | Shared file access across supported compute resources |
| AWS Backup                 | Centralises supported backup operations | Managing backup policies across resources             |
| S3 Glacier storage classes | Lower-cost archival storage options     | Retaining infrequently accessed historical data       |

### 🌐 Networking and Content Delivery

| Service            | What It Does                                                                  | Example Use Case                                              |
| ------------------ | ----------------------------------------------------------------------------- | ------------------------------------------------------------- |
| Amazon VPC         | Creates isolated virtual networks                                             | Controlling network layout and boundaries                     |
| Amazon Route 53    | DNS and domain-routing services                                               | Connecting a domain to an application                         |
| Amazon CloudFront  | Content delivery network                                                      | Delivering website content closer to users                    |
| Internet Gateway   | Enables supported connectivity between a VPC and the internet                 | Public subnet connectivity when routes and controls permit it |
| NAT Gateway        | Enables outbound internet access from private subnets in common architectures | Allowing private workloads to download updates                |
| AWS Direct Connect | Dedicated network connectivity to AWS                                         | Connecting on-premises networks to AWS                        |

### 🔐 Identity and Security

| Service             | What It Does                                           | Example Use Case                                            |
| ------------------- | ------------------------------------------------------ | ----------------------------------------------------------- |
| AWS IAM             | Manages identities and permissions                     | Controlling which users and services can access resources   |
| AWS KMS             | Manages cryptographic keys                             | Encrypting supported data and integrating with AWS services |
| AWS Secrets Manager | Stores and manages secrets                             | Managing database credentials                               |
| AWS CloudTrail      | Records supported account and API activity             | Investigating changes and supporting auditing               |
| Amazon GuardDuty    | Detects potential threats using supported data sources | Identifying suspicious activity                             |

### 🛢️ Databases

| Service            | What It Does                                                    | Example Use Case                                       |
| ------------------ | --------------------------------------------------------------- | ------------------------------------------------------ |
| Amazon RDS         | Managed relational databases                                    | Applications using SQL databases                       |
| Amazon Aurora      | Relational database engine compatible with MySQL and PostgreSQL | Managed relational database workloads                  |
| Amazon DynamoDB    | Managed NoSQL database                                          | Applications needing key-value or document data access |
| Amazon ElastiCache | Managed in-memory caching                                       | Reducing repeated database reads                       |
| Amazon Redshift    | Cloud data warehouse                                            | Analytics and business intelligence workloads          |

### ⚙️ Integration and Serverless

| Service            | What It Does                                              | Example Use Case                              |
| ------------------ | --------------------------------------------------------- | --------------------------------------------- |
| Amazon API Gateway | Creates and manages APIs                                  | Exposing application endpoints                |
| Amazon EventBridge | Routes events between supported services and applications | Triggering workflows from events              |
| Amazon SQS         | Message queuing                                           | Separating application components             |
| Amazon SNS         | Pub/sub messaging and notifications                       | Sending notifications to subscribers          |
| AWS Step Functions | Coordinates workflow steps                                | Orchestrating multi-step processing pipelines |

### 📊 Monitoring and Operations

| Service             | What It Does                                         | Example Use Case                                |
| ------------------- | ---------------------------------------------------- | ----------------------------------------------- |
| Amazon CloudWatch   | Collects metrics, logs, and alarms                   | Monitoring an application's health              |
| AWS CloudTrail      | Provides account activity history                    | Auditing AWS API activity                       |
| AWS Systems Manager | Supports operational management of resources         | Automating maintenance and administrative tasks |
| AWS Config          | Tracks supported resource configurations and changes | Evaluating configuration compliance             |

### 🧱 Data Engineering and Analytics

| Service            | What It Does                                           | Example Use Case                         |
| ------------------ | ------------------------------------------------------ | ---------------------------------------- |
| AWS Glue           | Managed data integration and ETL capabilities          | Transforming datasets for analytics      |
| Amazon Athena      | Queries data in supported sources such as S3 using SQL | Analysing files stored in a data lake    |
| AWS Lake Formation | Helps manage data lake access and governance           | Controlling access to data lake datasets |
| Amazon Kinesis     | Services for working with streaming data               | Ingesting and processing event streams   |
| Amazon EMR         | Managed big-data processing environments               | Distributed data processing              |
| Amazon Redshift    | Data warehousing and analytics                         | Running analytical SQL workloads         |

### 🤖 AI and Machine Learning

| Service             | What It Does                                                        | Example Use Case                       |
| ------------------- | ------------------------------------------------------------------- | -------------------------------------- |
| Amazon Bedrock      | Provides access to foundation models and generative AI capabilities | Building generative AI applications    |
| Amazon SageMaker AI | Provides tools and infrastructure for machine learning workflows    | Developing and deploying ML models     |
| Amazon Textract     | Extracts information from documents                                 | Processing forms and scanned documents |
| Amazon Rekognition  | Provides image and video analysis capabilities                      | Detecting objects in images            |

**How to study each service:** learn the problem it solves, the core components, when to use it, alternatives, pricing model, security considerations, limitations, and a small hands-on implementation.

Official reference: [AWS Documentation](https://docs.aws.amazon.com/)

---

## 🗺️ 5. Learning Roadmap

Follow the roadmap in order where possible. Each stage builds the foundation required for the next one.

| Stage | Focus                   | Suggested Outcome                                           |
| ----- | ----------------------- | ----------------------------------------------------------- |
| 01    | Cloud Fundamentals      | Explain cloud computing and its main benefits               |
| 02    | AWS Account and Console | Navigate the AWS Management Console safely                  |
| 03    | IAM and Security Basics | Understand users, roles, policies, and least privilege      |
| 04    | S3 Storage              | Upload, organise, protect, and retrieve objects             |
| 05    | EC2 and Compute         | Launch and connect to a virtual server securely             |
| 06    | Networking              | Understand VPCs, subnets, routes, and security groups       |
| 07    | Databases               | Compare relational and NoSQL databases                      |
| 08    | Serverless              | Build a basic event-driven application                      |
| 09    | Monitoring              | Use logs, metrics, alarms, and audit trails                 |
| 10    | Automation              | Use AWS CLI and Python with Boto3                           |
| 11    | Architecture            | Combine services to solve an end-to-end problem             |
| 12    | Specialisation          | Explore data engineering, DevOps, cloud architecture, or AI |

The roadmap is a learning sequence, not a requirement that every AWS professional master every service. Choose a specialisation after developing a solid foundation.

---

## 🧪 7. Hands-On Labs

Reading about a service is useful. Actually configuring it, testing it, and troubleshooting it makes the concept stick.

The following labs are designed to move from beginner exercises to small integrated solutions.

| Lab    | What You Will Build                             | Main Concepts                           |
| ------ | ----------------------------------------------- | --------------------------------------- |
| Lab 01 | Explore the AWS Console                         | Regions, service search, account basics |
| Lab 02 | Create a private S3 bucket and upload files     | Buckets, objects, permissions           |
| Lab 03 | Create an IAM role and inspect permissions      | IAM, roles, least privilege             |
| Lab 04 | Launch and connect to an EC2 instance           | Compute, networking, secure access      |
| Lab 05 | Configure a VPC with public and private subnets | Routing and network isolation           |
| Lab 06 | Host static website content in S3               | Static assets and storage configuration |
| Lab 07 | Create a Lambda function                        | Serverless computing                    |
| Lab 08 | Trigger processing from an S3 event             | Event-driven architecture               |
| Lab 09 | Create a CloudWatch alarm                       | Metrics and operational monitoring      |
| Lab 10 | Query S3 data using Athena                      | SQL analytics and data formats          |
| Lab 11 | Ingest a dataset into an S3 data lake           | Python, APIs, and cloud storage         |
| Lab 12 | Build an end-to-end cloud pipeline              | Service integration and data flow       |

Every lab should eventually include the objective, prerequisites, required permissions, console or CLI steps, code where applicable, expected output, common errors, validation steps, cleanup instructions, and estimated cost considerations.

---


Useful references:

- [AWS Pricing](https://aws.amazon.com/pricing/)
- [AWS Pricing Calculator](https://calculator.aws/)
- [AWS Budgets](https://aws.amazon.com/aws-cost-management/aws-budgets/)
- [AWS Security Documentation](https://docs.aws.amazon.com/security/)

---



This is a suggested structure, not a requirement to create every folder immediately. Start with the fundamentals and add folders as their lessons are written.

---

## 🔗 12. Useful Learning Resources

Official documentation should be the reference point for service features, configuration, quotas, pricing, and security guidance.

| Resource                                                                                  | Why It Is Useful                                                  |
| ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| [AWS Documentation](https://docs.aws.amazon.com/)                                         | Official technical documentation for AWS services                 |
| [AWS Getting Started](https://aws.amazon.com/getting-started/)                            | Guidance for people starting with AWS                             |
| [AWS Skill Builder](https://skillbuilder.aws/)                                            | Digital learning resources and training                           |
| [AWS Architecture Center](https://aws.amazon.com/architecture/)                           | Architecture patterns and design guidance                         |
| [AWS Well-Architected](https://aws.amazon.com/architecture/well-architected/)             | Guidance on secure, reliable, efficient, and cost-aware workloads |
| [AWS Workshops](https://workshops.aws/)                                                   | Hands-on workshops for selected services and solutions            |
| [AWS CLI User Guide](https://docs.aws.amazon.com/cli/latest/userguide/)                   | Installing and using the AWS command-line interface               |
| [Boto3 Documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html) | Reference for AWS automation using Python                         |

Always verify current details in the documentation, especially when a service feature, command, pricing rule, or best practice may have changed.

---


## 🙋‍♂️ 15. About the Author

**Muhammad Usman**

Computer Science Student | Cloud & Data Engineering Learner | Practical Technology Projects

I created this repository to organise my AWS learning journey and make cloud concepts easier for others to understand. My goal is to explain the fundamentals clearly, practise services through hands-on work, and document the reasoning behind the architecture and configuration choices.

This is a continuously evolving learning resource. As new topics and projects are completed, the repository will grow with them.

## 🔗 Connect With Me

<p align="left">
&#x20; <a href="[https://www.linkedin.com/in/mohammad-usman736/](https://www.linkedin.com/in/mohammad-usman736/)">
&#x20;   <img src="[https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)" alt="LinkedIn"/>
&#x20; </a>
&#x20; <a href="mailto\:usman.rizz6769@gmail.com">
&#x20;   <img src="[https://img.shields.io/badge/Gmail-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white](https://img.shields.io/badge/Gmail-Contact-D14836?style=for-the-badge\&logo=gmail\&logoColor=white)" alt="Gmail"/>
&#x20; </a>
&#x20; <a href="[https://github.com/usman-rizz](https://github.com/usman-rizz)">
&#x20;   <img src="[https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge\&logo=github\&logoColor=white)" alt="GitHub"/>
&#x20; </a>
</p>

---

<p align="center">
&#x20; <b>☁️ Learn the concepts. Build the architecture. Understand the trade-offs.</b>
</p>

<p align="center">
&#x20; <i>From cloud fundamentals to practical AWS solutions — one concept and one project at a time.</i>
</p>
