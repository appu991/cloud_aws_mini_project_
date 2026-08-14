# Cloud Computing and AWS Fundamentals

## 1. Introduction to Cloud Computing

Cloud computing is the delivery of computing resources such as servers, storage, networking, databases, and applications over the internet on demand.

Instead of purchasing and maintaining physical hardware, organizations can use cloud services provided by companies such as Amazon Web Services (AWS), Microsoft Azure, and Google Cloud.

### Key Benefits of Cloud Computing

* **Scalability:** Resources can be increased or decreased according to requirements.
* **Cost Efficiency:** Organizations can reduce the need for large upfront hardware investments.
* **Flexibility:** Cloud resources can be accessed through the internet.
* **Availability:** Cloud providers offer infrastructure across multiple locations.
* **Pay-as-you-go:** Many cloud services charge based on resource usage.

---

## 2. Cloud Deployment Models

Cloud deployment models describe how cloud infrastructure is deployed and used.

### 2.1 Public Cloud

A public cloud is a cloud environment where infrastructure and services are provided by a cloud service provider and shared among multiple customers.

**Examples:** Amazon Web Services (AWS), Microsoft Azure, and Google Cloud.

**Advantages:**

* Lower initial infrastructure cost
* High scalability
* No need to maintain physical hardware

### 2.2 Private Cloud

A private cloud is a cloud environment dedicated to a single organization. It provides greater control over infrastructure and configuration.

**Advantages:**

* Greater control
* Suitable for specific security and compliance requirements
* Customizable infrastructure

**Limitation:**

* Can require higher setup and maintenance costs

### 2.3 Hybrid Cloud

A hybrid cloud combines public and private cloud environments. Organizations can use private infrastructure for sensitive workloads and public cloud resources for scalable applications.

**Advantages:**

* Flexibility
* Better workload management
* Ability to combine security and scalability requirements

---

## 3. Cloud Service Models

Cloud service models define the level of infrastructure and services managed by the cloud provider.

### 3.1 Infrastructure as a Service (IaaS)

IaaS provides fundamental computing infrastructure such as virtual machines, storage, and networking.

The customer has greater control over the operating system, applications, and configurations.

**Example:** Amazon EC2.

### 3.2 Platform as a Service (PaaS)

PaaS provides a platform that allows developers to build, deploy, and manage applications without managing much of the underlying infrastructure.

It allows developers to focus mainly on application development.

**Example:** AWS Elastic Beanstalk.

### 3.3 Software as a Service (SaaS)

SaaS provides ready-to-use software applications over the internet. Users generally do not need to manage the underlying infrastructure.

**Examples:** Gmail, Google Docs, and Microsoft 365.

### Comparison of Service Models

| Feature                   | IaaS            | PaaS                  | SaaS                  |
| ------------------------- | --------------- | --------------------- | --------------------- |
| Main focus                | Infrastructure  | Application platform  | Ready-to-use software |
| User control              | High            | Medium                | Low                   |
| Infrastructure management | Mostly customer | Mostly provider       | Provider              |
| Example                   | Amazon EC2      | AWS Elastic Beanstalk | Gmail                 |

---

## 4. Introduction to AWS

Amazon Web Services (AWS) is a cloud computing platform provided by Amazon. AWS offers a wide range of services for computing, storage, networking, databases, security, monitoring, and application deployment.

AWS enables organizations and developers to build and operate applications without maintaining all physical infrastructure themselves.

---

## 5. Core AWS Services

### 5.1 Amazon EC2

Amazon EC2 stands for **Elastic Compute Cloud**.

EC2 provides resizable virtual servers in the AWS cloud. These virtual servers can be used to host applications, websites, and other workloads.

**Common uses:**

* Hosting websites
* Running applications
* Running Linux or Windows servers
* Development and testing environments

**Key concept:**

> EC2 provides virtual computing capacity in the cloud.

---

### 5.2 Amazon S3

Amazon S3 stands for **Simple Storage Service**.

S3 is an object storage service used to store and retrieve data such as documents, images, videos, backups, and application files.

S3 stores objects inside containers called **buckets**.

**Common uses:**

* Backup and recovery
* Application data storage
* Static website files
* Media storage

**Key concept:**

> S3 provides scalable object storage in the cloud.

---

### 5.3 Amazon VPC

Amazon VPC stands for **Virtual Private Cloud**.

VPC allows users to create a logically isolated virtual network within AWS. It provides networking components required to control communication between AWS resources.

Important VPC components include:

* Subnets
* Route tables
* Internet gateways
* Network security controls

**Common uses:**

* Creating private and public network environments
* Connecting AWS resources
* Controlling network traffic

**Key concept:**

> VPC provides a virtual networking environment for AWS resources.

---

### 5.4 Amazon RDS

Amazon RDS stands for **Relational Database Service**.

RDS is a managed database service that makes it easier to set up, operate, and scale relational databases in AWS.

It supports database engines such as:

* MySQL
* PostgreSQL
* MariaDB
* Microsoft SQL Server

**Common uses:**

* Application databases
* Web application backends
* Structured data storage

**Key concept:**

> RDS provides managed relational database services in AWS.

---

## 6. Summary

Cloud computing provides on-demand access to computing resources through the internet.

The major deployment models are:

* Public Cloud
* Private Cloud
* Hybrid Cloud

The major service models are:

* IaaS
* PaaS
* SaaS

AWS provides many cloud services, including:

* **EC2:** Virtual computing
* **S3:** Object storage
* **VPC:** Virtual networking
* **RDS:** Managed relational databases

These concepts provide a foundation for understanding AWS infrastructure and performing practical cloud computing tasks.

## 7. Learning Outcome

Through this task, I developed a basic understanding of cloud computing concepts, deployment models, service models, and fundamental AWS services. These concepts will be used as a foundation for subsequent AWS and cloud infrastructure hands-on activities.
