<h1>
# AWSDEApreparation
</h1>
Donation:<br> <link>https://www.paypal.com/donate/?business=C5ZXDE6A7M28E&no_recurring=0&item_name=Donation+for+Owner+of+this+PayPal+Account&currency_code=BRL</link><br>
Doações:<br> Pix: altaperformancenubank@gmail.com<br>
--
<br>
<br>
<h4>
My personal path in preparation to take the AWS Certified Data Engineer Associate exam<br>
</h4>
<hr>
Trilha de estudos seguida para me preparar para o exame AWS Certified Data Engineer Associate<br>
////----<br>
2025-01-10<br>
. Re-Watch the videos about the AWS Partner Certification Readiness - AWS Partner Network Lectures gived by Kevin Zook, Brady Smith and Andy Kroll<br>
. Assistir novamente os videos do curso AWS Partner Certification Readiness, ministrados por Kevin Zoook, Brady Smith e Andy Kroll.<br>
<h2>Video 01 - Kick OFF</h2><br>
...Video is about the preparation for exame, accommodations and general tips to take the exam.<br>
   and a overall content of the 4 Domains that exam cover.<br>
...Video com dicas genéricas sobre o exame, acomodações para solicitar 30 minutos a mais, etc e um <br>
   review dos 4 domínios que o exame cobre.<br>
////----<br>
<h2>...... Domain 1 : Data Ingestion and Transformation ( 34% of the exam )</h2> <br>
...... 1. Perform data ingestion <br>
...... 2. Transform and process data <br>
...... 3. Orchestrate data pipelines <br>
...... 4. Apply programming concepts <br>
........ Data ingestion, is about stream data, database migration and how do i get data into Redshift ? <br>
........ Focus in ECS, EKS, Fargate, Lambda and Glue ( Glue is one of the most important topics of the exam) <br>
........ Step functions, Pipelines process, SNS, SQS, some questions in exam may touch and ask about your SQL skills <br>
........ as a part of applying programming concepts, you may be asked about AWS CDK and Cloud formation. <br>
........ you need to know aspects of CSVs, file types relationed to data structures.<br>
////----<br>
<h2>...... Domain 2 : Data Store Management ( 26% of the exam )</h2> <br>
...... 1. Choose a data store <br>
...... 2. Understand data cataloging systems <br>
...... 3. Manage the lifecycle of data <br>
...... 4. Design data models and schema evolution <br>
........ Choose a data store like: S3, lake formation; ...and you may store data in a database like Redshift or <br>
........ in relational data service (RDS). <br>
........ After you ingest data and after you store the data, you have to catalog it. <br>
........ You have to look at GLUE DATA CATALOG, APACHE HIVE, METASTORES.<br>
........ How do you get the SCHEMA of the data with GLUE CRAWLER.<br>
........ You will use the S3 Life cycle policies, example: if you have data that´s 60 days old, how i should handle it ?<br>
........ How you ensure the ACCURACY of DATA ? How to track the lineage of data ingested, his transformations and life cycle ? <br>
........ You see structured data, semi-structured data and unstructured data. <br>
........ You have to kwnow what tools/services you use to convert schemas and how schemas evolve.<br>
////----<br>
<h2>...... Domain 3 : Data Operations and Support ( 22% of the exam )</h2> <br>
...... 1. Automate data processing by using AWS services <br>
...... 2. Analyze data by using AWS Services <br>
...... 3. Maintain and monitor data pipelines <br>
...... 4. Ensure data quality <br>
........ At this point you ingested and stored data, now is the time to process, and extract insights from the data <br>
........ How do i automate data processing using AWS services ? <br>
........ Focus on STEP FUNCTIONS, AWS GLUE, AWS SAGE MAKER, this exam do not focus on Machine Learning but SAGE MAKER can process data <br>
........ You should be familiar with SAGE MAKER DATA WRANGLER and some components around it.<br>
........ You may see LAMBDA, EVENT BRIDGE and different ways to automate and process data.<br>
........ The exam is more focused in DATA than the analytics, but you have to look at ATHENA, QUICKSIGHT <br>
........ AWS GLUE and CLOUDWATCH come up in the Maintain and monitor data pipelines.<br>
........ To ensure data quality you have to use AWS GLUE, AWS GLUE DATA BREW, example: empty fields, missing data in a data set, etc. <br>
////----<br>
<h2>...... Domain 4 : Data Security and Governance ( 18% of the exam )</h2> <br>
...... 1. Apply authentication mechanisms <br>
...... 2. Apply authorization mechanisms <br>
...... 3. Ensure data encryption ans masking <br>
...... 4. Prepare logs for audity <br>
...... 5. Understand data privacy and governance <br>
........ At this point you knows about ingestion, storage, the operation aspect and how to process data.<br>
........ The Domain 4 is about security and governance aspect of the data environment.<br>
........ Aspects of VPC, IAM: example: How to process data in S3 tha it´s outside your VPC. <br>
........ How to access data in REDSHIFT, his tables, rows and columns.<br>
........ KMS Service to encrypt data. <br>
........ CLOUDWATCH and CLOUDTRAIL services to audity the data environment.<br>
........ Example of governance: PII identified by AWS MACIE and how to integrate it with LAKE FORMATION. <br>
........ At governance aspect of DATA Environment we will look at how to use AWS CONFIG <br>
........<br>
<h2>The resume of this 4 Domains is a high level concise content, use exam guide to deep dive in it´s aspects.</h2>
........<br>
useful resource:<br>
Data Engineer- Associate ProgramGuide<br>
. <link>https://partners.awscloud.com/rs/302-CJJ-746/images/Program%20Guide_APCR_DEA_NAMER.pdf</link>
<hr>
Video 02 - Content Review Session<br>
..............You have to firmly understand the foundational concepts of AWS Cloud, a lot of this content will help you fix and<br>
remember concepts will help you deep dive in more advanceds topics.<br>
WEEK 01 - AWS Tech & DATA Fundamentals<br>
...Video will cover: AWS Compute, AWS Networking, AWS Storage, AWS Databases, The Three V´s of DATA and AWS Services per "V"<br>
...b <br>
...... <h2>AWS Global Infrastructure review</h2> <br>
......... AWS Regions, AWS Availability Zones, A AWS Region is collection of AZs <br>
......... Example: AWS ap-southeast-1 (Singapore Region), has ap-southeast-1a, ap-southeast-1b and ap-southeast-1c <br>
......... Edge Locations is smaller endpoints for hosting cached data.<br>
......... POP (point of presence) enables delivering content like data, videos, apps and APIs globally with low latency and higher speed.<br> 
...... <h2>AWS Compute - Amazon EC2, ECS, EKS and AWS Fargate</h2> <br>
.........EC2 is a fancy way to say a virtual machine.<br>
.........Remember the price models for EC2 : On-Demand, Saving Plans, Dedicated Hosts, Spot Instances and Reserved Instances.<br>
.........AMI is a blueprint for you use to launch (intantiate) a EC2. <br>
.........an AMI is kinda off a "container image" not equal but similar in some way, it´s related, but not equal.<br>
.........<br>
.........CONTAINERS: Contain all the code, runtime, system libraries, dependencies and configuration requirede for the app to run.<br>
.........Multiple containers can run on same OS, sharing it´s resources. Containers engines runs the images.<br>
.........A abstraction we can use is "a container" is like a zip file, with a lot of type of files within.<br>
.........Container orchestration automates scheduling, development, networking, scaling, health monitoring and management of your container.<br>
.........Orchestration maintain your SLAs agreements.<br>
.........Orchestraion is Scheduling and Deployment: ECS Elastic Container Service and EKS Elastic Kubernetes Service they both do the exact same thing that is "orchestration".<br>
.........At HOSTS you can choose EC2 or Fargate, whith EC2 i have to manage the VM and otherwise with Fargate the VM´s is managed by the AWS (serverless).<br>
.........Fargate scales to 16 vCPU and 120GB memory per task to run DATA processing workloads, the serverless solution from AWS to containers.<br>
.........Good to use with AI and ML development environment.<br>
...... <h2>Scaling and Balancing</h2> <br>
.........Amazon EC2 Auto Scaling: <br>
.........Fleet Management: health, availability of EC2 fleet. Can replace impaired instances and balance capacity across AZs.<br>
.........Scheduled auto scaling allow you to up or down the fleet ahead of known load changes, besides the dynamic scheduling automates the process<br>
.........to up or down the fleet knowing some parameters, like cpu utilization.<br>
.........Amazon EC2 Auto Scaling Groups, is like a "thermostat" to feel how to scales up or down your EC2 fleet.<br>
.........ELB (Elastic Load Balancer) receives incoming traffic and distributes the requests across EC2 and AZs.<br>
.........SERVERS as the single point of contact for clients.<br>
...... <h2>Networking and Security</h2> <br>
.........Review of AWS Shared Responsibility Model.<br>
.........Review of AMAZON Virtual Private Cloud (VPC).<br>
.........How a lambda or a EC2 can process information inside a S3 bucket and how you set up that access.<br>
.........like routing, subnets, endpoints and the security around that, how could you integrate this and allow computation to access the storage.<br>
.........You need to urdestang security groups and network access control lists NACL.<br>
.........Review of Identity and Access Management (IAM)<br>
...... <h2>Storage and Databases</h2> <br>
.........Review of AWS Storage: EFS, FSx, EBS, S3, S3 Glacier<Br>
.........NFS (network file system) for EFS, SMB and Luster for FSx.<br>
.........EBS will be attached to a EC2 instance.<br>
.........You have to understand S3 concepts, like: how to protect data, how to integrate a lambda function, how data gets into a S3, how S3 lifecycle works.<br>
.........For databases you will focus on RDS, DynamoDB, Elastic Cache. <br>
.........MemoryDB for Redis: ULTRA FAST performance with microsecond reads, millisecond writes, scalability and enterprise security.<br>
.........USAGE of MemoryDB >> Simplifying architecture with a database with cache, Workload with ultra-fast performance, redis data structures.<br>
.........differences between MemoryDB and ElasticCache: <br>
.........MemoryDB is your main Databases, resides in memory.<br>
.........ElasticCache is a cache in front of a RDS for example.<br>
.........Amazon NEPTUNE, related with connections in social media.<br>
.........Amazon KEYSPACES for Apache Cassandra compatible with Cassandra Query Language fully managed by AWS.<br>
.........Amazon DocumentDB is MongoDB compatible database, Stores, query and indexes JSON data natively using fully managed document database service.<br>
.........For databases focus more on RDS and DynamoDB.<br>
...... <h2>The 5 V´s of Big Data</h2><br>
.........Volume: Total amount of data coming in to the solution, analogy: a lot of water being ingested or just a few...<br>
.........Variety: Count and type of data sources in the solution, analogy: types of water source, lakes, rain, rivers...like PDFS, images, JSON docs, videos.<br>
.........Velocity: Speed of data flowing throught to be processed<br>
.........Veracity: Degree to which data is accurate, precise and trusted<br>
.........Value: Ability to extract meaningful information from the data stored<br>
.........A analogy to think about the 5 V´s is think about WATER being ingested in a lake or a reservoir. 












........ 




/














--<br>

---////<br>
This Redme.md is in development
