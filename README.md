# AWSDEApreparation
--\
<a href="https://www.paypal.com/donate/?business=C5ZXDE6A7M28E&no_recurring=0&item_name=Donation+for+Owner+of+this+PayPal+Account&currency_code=BRL" target="_blank">
  <img src="https://www.paypalobjects.com/paypal-ui/logos/svg/paypal-color.svg" alt="PayPal Donation" width="100" height="50">
</a><br>
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Acheroniano)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/f%C3%A1bio-samuel-dos-santos-canedo-2708b533/)
###### Doações:<br>Pix: altaperformancenubank@gmail.com<br>
--
#### My personal path in preparation to take the AWS Certified Data Engineer Associate exam<br>
###### Trilha de estudos seguida para me preparar para o exame AWS Certified Data Engineer Associate
# 2025-01-10
###### .Re-Watch the videos about the AWS Partner Certification Readiness - AWS Partner Network Lectures gived by Kevin Zook, Brady Smith and Andy Kroll.
###### .Assistir novamente os videos do curso AWS Partner Certification Readiness, ministrados por Kevin Zoook, Brady Smith e Andy Kroll.
# Video 01 - Kick OFF
###### ...Video is about the preparation for exame, accommodations and general tips to take the exam
######   and a overall content of the 4 Domains that exam cover.
###### Video com dicas genéricas sobre o exame, acomodações para solicitar 30 minutos a mais, etc e um
###### review dos 4 domínios que o exame cobre
## ...... Domain 1 : Data Ingestion and Transformation ( 34% of the exam )
###### ...... 1. Perform data ingestion
###### ...... 2. Transform and process data
###### ...... 3. Orchestrate data pipelines
###### ...... 4. Apply programming concepts
###### ........ Data ingestion, is about stream data, database migration and how do i get data into Redshift ?
###### ........ Focus in ECS, EKS, Fargate, Lambda and Glue ( Glue is one of the most important topics of the exam)
###### ........ Step functions, Pipelines process, SNS, SQS, some questions in exam may touch and ask about your SQL skills
###### ........ as a part of applying programming concepts, you may be asked about AWS CDK and Cloud formation.
###### ........ you need to know aspects of CSVs, file types relationed to data structures.
## ...... Domain 2 : Data Store Management ( 26% of the exam )
###### ...... 1. Choose a data store
###### ...... 2. Understand data cataloging systems
###### ...... 3. Manage the lifecycle of data
###### ...... 4. Design data models and schema evolution
###### ........ Choose a data store like: S3, lake formation; ...and you may store data in a database like Redshift or 
###### ........ in relational data service (RDS).
###### ........ After you ingest data and after you store the data, you have to catalog it.
###### ........ You have to look at GLUE DATA CATALOG, APACHE HIVE, METASTORES.
###### ........ How do you get the SCHEMA of the data with GLUE CRAWLER.
###### ........ You will use the S3 Life cycle policies, example: if you have data that´s 60 days old, how i should handle it ?
###### ........ How you ensure the ACCURACY of DATA ? How to track the lineage of data ingested, his transformations and life cycle ?
###### ........ You see structured data, semi-structured data and unstructured data.
###### ........ You have to kwnow what tools/services you use to convert schemas and how schemas evolve.
## ...... Domain 3 : Data Operations and Support ( 22% of the exam )
###### ...... 1. Automate data processing by using AWS services
###### ...... 2. Analyze data by using AWS Services
###### ...... 3. Maintain and monitor data pipelines 
###### ...... 4. Ensure data quality 
###### ........ At this point you ingested and stored data, now is the time to process, and extract insights from the data 
###### ........ How do i automate data processing using AWS services ? 
###### ........ Focus on STEP FUNCTIONS, AWS GLUE, AWS SAGE MAKER, this exam do not focus on Machine Learning but SAGE MAKER can process data 
###### ........ You should be familiar with SAGE MAKER DATA WRANGLER and some components around it.
###### ........ You may see LAMBDA, EVENT BRIDGE and different ways to automate and process data.
###### ........ The exam is more focused in DATA than the analytics, but you have to look at ATHENA, QUICKSIGHT 
###### ........ AWS GLUE and CLOUDWATCH come up in the Maintain and monitor data pipelines.
###### ........ To ensure data quality you have to use AWS GLUE, AWS GLUE DATA BREW, example: empty fields, missing data in a data set, etc. 
## ...... Domain 4 : Data Security and Governance ( 18% of the exam )
###### ...... 1. Apply authentication mechanisms 
###### ...... 2. Apply authorization mechanisms 
###### ...... 3. Ensure data encryption ans masking 
###### ...... 4. Prepare logs for audity 
###### ...... 5. Understand data privacy and governance
###### ........ At this point you knows about ingestion, storage, the operation aspect and how to process data.
###### ........ The Domain 4 is about security and governance aspect of the data environment.
###### ........ Aspects of VPC, IAM: example: How to process data in S3 tha it´s outside your VPC. 
###### ........ How to access data in REDSHIFT, his tables, rows and columns.
###### ........ KMS Service to encrypt data. 
###### ........ CLOUDWATCH and CLOUDTRAIL services to audity the data environment.
###### ........ Example of governance: PII identified by AWS MACIE and how to integrate it with LAKE FORMATION. 
###### ........ At governance aspect of DATA Environment we will look at how to use AWS CONFIG.
###### ........
## The resume of this 4 Domains is a high level concise content, use exam guide to deep dive in it´s aspects.
###### ........
###### useful resource:
###### Data Engineer- Associate ProgramGuide
###### Saiba mais ==> <link>https://partners.awscloud.com/rs/302-CJJ-746/images/Program%20Guide_APCR_DEA_NAMER.pdf</link>
###### 
# Video 02 - Content Review Session
###### ........ You have to firmly understand the foundational concepts of AWS Cloud, a lot of this content will help you fix and
###### remember concepts will help you deep dive in more advanceds topics.
### WEEK 01 - AWS Tech & DATA Fundamentals
###### ...Video will cover: AWS Compute, AWS Networking, AWS Storage, AWS Databases, The Three V´s of DATA and AWS Services per "V"
## AWS Global Infrastructure review 
###### ......... AWS Regions, AWS Availability Zones, A AWS Region is collection of AZs
###### ......... Example: AWS ap-southeast-1 (Singapore Region), has ap-southeast-1a, ap-southeast-1b and ap-southeast-1c
###### ......... Edge Locations is smaller endpoints for hosting cached data.
###### ......... POP (point of presence) enables delivering content like data, videos, apps and APIs globally with low latency and higher speed.
## ...... AWS Compute - Amazon EC2, ECS, EKS and AWS Fargate
###### ......... EC2 is a fancy way to say a virtual machine.
###### ......... Remember the price models for EC2 : On-Demand, Saving Plans, Dedicated Hosts, Spot Instances and Reserved Instances.
###### ......... AMI is a blueprint for you use to launch (intantiate) a EC2.
###### ......... an AMI is kinda off a "container image" not equal but similar in some way, it´s related, but not equal.
###### .........
###### ......... CONTAINERS: Contain all the code, runtime, system libraries, dependencies and configuration requirede for the app to run.
###### ......... Multiple containers can run on same OS, sharing it´s resources. Containers engines runs the images.
###### ......... A abstraction we can use is "a container" is like a zip file, with a lot of type of files within.
###### ......... Container orchestration automates scheduling, development, networking, scaling, health monitoring and management of your container.
###### ......... Orchestration maintain your SLAs agreements.
###### ......... Orchestraion is Scheduling and Deployment: ECS Elastic Container Service and EKS Elastic Kubernetes Service they both do the exact same thing that is "orchestration".
###### ......... At HOSTS you can choose EC2 or Fargate, whith EC2 i have to manage the VM and otherwise with Fargate the VM´s is managed by the AWS (serverless).
###### ......... Fargate scales to 16 vCPU and 120GB memory per task to run DATA processing workloads, the serverless solution from AWS to containers.
###### ......... Good to use with AI and ML development environment.
## ...... Scaling and Balancing
###### ......... Amazon EC2 Auto Scaling: <br>
###### ......... Fleet Management: health, availability of EC2 fleet. Can replace impaired instances and balance capacity across AZs.
###### ......... Scheduled auto scaling allow you to up or down the fleet ahead of known load changes, besides the dynamic scheduling automates the process
###### ......... to up or down the fleet knowing some parameters, like cpu utilization.
###### ......... Amazon EC2 Auto Scaling Groups, is like a "thermostat" to feel how to scales up or down your EC2 fleet.
###### ......... ELB (Elastic Load Balancer) receives incoming traffic and distributes the requests across EC2 and AZs.
###### ......... SERVERS as the single point of contact for clients.
## ...... Networking and Security
###### ......... Review of AWS Shared Responsibility Model.
###### ......... Review of AMAZON Virtual Private Cloud (VPC).
###### ......... How a lambda or a EC2 can process information inside a S3 bucket and how you set up that access
###### ......... like routing, subnets, endpoints and the security around that, how could you integrate this and allow computation to access the storage.
###### ......... You need to urdestang security groups and network access control lists NACL.
###### ......... Review of Identity and Access Management (IAM)
## ...... Storage and Databases
###### ......... Review of AWS Storage: EFS, FSx, EBS, S3, S3 Glacier
###### ......... NFS (network file system) for EFS, SMB and Luster for FSx.
###### ......... EBS will be attached to a EC2 instance.
###### ......... You have to understand S3 concepts, like: how to protect data, how to integrate a lambda function, how data gets into a S3, how S3 lifecycle works.
###### ......... For databases you will focus on RDS, DynamoDB, Elastic Cache.
###### ......... MemoryDB for Redis: ULTRA FAST performance with microsecond reads, millisecond writes, scalability and enterprise security.
###### ......... USAGE of MemoryDB >> Simplifying architecture with a database with cache, Workload with ultra-fast performance, redis data structures.
###### ......... differences between MemoryDB and ElasticCache: 
###### ......... MemoryDB is your main Databases, resides in memory.
###### ......... ElasticCache is a cache in front of a RDS for example.
###### ......... Amazon NEPTUNE, related with connections in social media.
###### ......... Amazon KEYSPACES for Apache Cassandra compatible with Cassandra Query Language fully managed by AWS.
###### ......... Amazon DocumentDB is MongoDB compatible database, Stores, query and indexes JSON data natively using fully managed document database service.
###### ......... For databases focus more on RDS and DynamoDB.
## ...... The 5 V´s of Big Data
###### ......... Volume: Total amount of data coming in to the solution, analogy: a lot of water being ingested or just a few...
###### ......... Variety: Count and type of data sources in the solution, analogy: types of water source, lakes, rain, rivers...like PDFS, images, JSON docs, videos.
###### ......... Velocity: Speed of data flowing throught to be processed, analogy: Fast flowing river versus a slow moving stream, like process in real time ou batch jobs.
###### ......... Veracity: Degree to which data is accurate, precise and trusted, analogy: you have clean water and dirty water, in data coming in can be missing values.
###### ......... Value: Ability to extract meaningful information from the data stored, analogy: there is more value in clean water, same with data dirty data,
###### ......... missing data, impurity data provides little value to a good clean dataset.
###### ......... All analogies is to relate the 5 V´s with thinking about WATER being ingested in a lake or a reservoir. 
###### ......... on exam you most focus in VOLUME, VARIETY and VELOCITY.
## ...... DATA Source Types
###### ......... Structured DATA: Relational databases, data is organized in rows, columns, tables, 
###### ......... Unstructured DATA: PDF, Jpeg, videos, a bunch of random data
###### ......... Semi-Structured DATA: JSON documents (Amazon REDSHIFT)
###### ......... How i can handle these different DATA Types.
###  ...... Amazon Simple Storage (related to VOLUME on 5 V´s)
###  ...... AWS Lake Formation (related to VOLUME on 5 V´s)
###  ...... Amazon RedShift (related to VOLUME on 5 V´s)
###  ...... Amazon Relational Database Service (related to VARIETY on 5 V´s)
###### ........ Set up, operate and scale a Relational SQL database in the cloud.
###### ........ Aurora, PostgreSQL, MySQL, MariaDB, OracleDB and SQL Server.
###  ...... Amazon DynamoDB (related to VARIETY on 5 V´s)
###### ........ Fast and flexible NoSQL database service for any scale.
###### ........ Serverless KEY-VALUE and document database that delivers single-digit millisecond performance.
###### ........ Maximize read throughput, atomicity consitency.
###  ...... Amazon OpenSearch Service (related to VARIETY on 5 V´s)
###### ........ Analyze logs, crm, social media.
###### ........ can be used as a RAG data store and using LLM model can get information from OpenSearch.
###  ...... Amazon EMR (related to VELOCITY on 5 V´s)
###### ........ Elastic Map Reduce, run and scale Apache Spark, Hive, Presto and other Big Data Worloads.
###### ........ for petabyte scale data processing, interactive analytics and Machine Learning using open-source frameworks.
###### ........ HADOOP Clusters
###  ...... Amazon MSK (related to VELOCITY on 5 V´s)
###### ......... Amazon MSK ingest and process streaming data in REAL TIME with a fully managed APACHE KAFKA
###  ...... Amazon Kinesis Data Streams (related to VELOCITY on 5 V´s)
###### ........ Cost-effectively process and analyzes streaming data as a managed service
###### ........ ingest data from clickstream, iot, etc in real time.
###### ........ Streaming data can be fan-out out multiple consumers like EC2, lambda, Spark or Amazon EMR and Amazon Managed Service for Apache Flink.
###### ........ Amazon Kinesis is one of the focus services you have to study to be prepared for the exam.
###### ........ Amazon Kinesis is about to how i ingest data, in real-time or near real-time and how i process streaming data.
###### ........ i can store, i can process it, i can do a few different thing with that ingested data
###  ...... Amazon Lambda (related to VELOCITY on 5 V´s)
###### ........ Run Code without managing servers.
###### ........ Remember the 15 min limitation from Lambda, when you in exam to discard or to choose lambda answers<br> 
###### ........


........Question 1:<br>
...........An Amazon Kinesis application is trying to read data from a Kinesis data stream. However, the read data call is rejected.<br>
...........The following error message is displayed: ProvisionedThroughputException.<br>
...........<br>
...........Which combination of steps will resolve the error ? (select TWO)<br>
...........<br>
...........A. Configure ehanced fan-out on the stream<br>
...........B. Enable enhanced monitoring on the stream<br>
...........C. Increase the size of the GetRecords requests.<br>
...........D. Increase the number of shards within the stream to provide enough capacity for the read data calls.<br>
...........E. Make the application retry to read data from the stream.<br>
...........Answer: "D" and "E" <br>
...........<br>
...........<br>
........Question 2:<br>
...........A company is collecting data that is generated by its users for analysis by using an Amazon S3 data lake.<br>
...........Some of the data being collected and stored in Amazon S3 includes personally identifiable information (PII).<br>
...........<br>
...........The company wants a data engineer to design an automated solution to identify new and existing data that needs PII to be masked<br>
...........before analysis is performed. Additionally, the data engineer must provide an overview of the data identified.<br>
...........The task of masking the data will be handled by an application already created in the AWS account.<br>
...........The data engineer needs to design a solution that can invoke this application in real time when PII ins found.<br>
...........<br>
...........Which solution will meet these requirements with the LEAST operational overhead?<br>
...........<br>
...........A. Create an AWS Lambda function to analyze data for PII. Configure notification settings on the S3 bucket to invoke the lambda function<br>
...........   when a new object is uploaded.<br>
...........B. Configure notification settings on the S3 bucket. Configure an Amazon EventBridge rule for the default events bus for new object uploads.<br>
...........   Set the masking application as the target for the rule.<br>
...........C. Enable Amazon Macie in the AWS account. Create an Amazon EventBridge rule for the default event bus for Macie findings. Set the masking<br>
...........   application as the target for the rule.<br>
...........D. Enalbe Amazon Macie in the AWS account. Create an AWS Lambda function to run on a schedule to poll Macie findings and invoke the masking application.<br>
...........Answer: "C"<br>
...........<br>
...........<br>
........Question 3:<br>
...........A company has data in an on-premises NFS file share. The company plans to migrate to AWS. The company uses the data for data analysis.<br>
...........The company has written AWS Lambda functions to analyze the data.<br>
...........The company wants to continue to use NFS for the file system that Lambda Accesses. The data must be shared across all concurrently running Lambda functions.<br>
...........<br>
...........Which solution should the company use for this data migration ?<br>
...........<br>
...........A. Migrate the data into the local storage for each Lambda function. Use the local storage for data access.<br>
...........B. Migrate the data to Amazon Elastic Block Store (Amazon EBS) volumes. Access the EBS volumes from the Lambda functions.<br>
...........C. Migrate the data to Amazon DynamoDB. Ensure the lambda functions have permissions to access the table.<br>
...........D. Migrate the data to Amazon Elastic File System (Amazon EFS). Configure the Lambda Functions to mount the file system.<br>
...........Answer: "D"<br>
...........<br>
...........<br>
...........<br>
<h1># 2025-01-11</h1><br>
<h1>Video 03 - Content Review Week 2</h1><br>
......Domain 1: Data Ingestion and Transformation<br>
......Batch and Stream Processing Architectures<br>
........Batch processing is the method computers use to periodically complete high-volume, repetitive data jobs.<br>
........Stream processing requires ingesting a sequence of data, and incrementally updating metrics, reports and summary statistics in response to each arriving data record.<br>
........Better for real-time monitoring and response. <br>
........<br>
......AWS Services for Stream Processing<br>
........Amazon Kinesis Data Analytics and KDA Studio (both MSK and Kinesis Data Streams)<br>
........Amazon MSK Connect for sink from to Amazon MSK<br>
........Kinesis Data Firehose from Kinesis Data Streams, Amazon CloudWatch, etc<br>
........AWS Lambda<br>
........Amazon EMR<br>
........AWS Glue<br>
........Custom consumers<br>
........Streaming data options on AWS: Amazon Kinesis Data Streams, Amazon Data Firehose, Amazon Managed Service for Apache Flink and Amazon Managed Streaming for Apache Kafka <br>
........To exam focus more on Amazon Kinesis Data Streams<br>
<hr>
........Flow of Data: a bunch of PRODUCERS send DATA to Amazon Kinesis Data Streams, data ingested is temporally stored, when a consumer comes and pulls it down to processing,<br>
........after that DATA can be stored somewhere or generate some visualization.<br>
<hr>
........<h3>Kinesis Data Streams x Kinesis Firehose</h3>
........Kinesis Data Streams is about ingesting and processing that data.<br>
........Kinesis Data FireHose is about to store the data.<br>
........So if you are to process the data use Kinesis Data Streams otherwise you´re intending to store the data go with Kinesis Firehose
........If you need something as real time as possible use Amazon Kinesis Data Streams, the ingested data in the stream stay in for 24 hours and up to 365 days.<br>
........In Kinesis Firehose, producers send data to Kinesis Firehose, the DATA is added to a "buffer" with max size of 128 mb.<br>
........The deliver of that DATA to conusumer, example a S3, occurs when the buffer is filled with 128 mbr or after 900 seconds.
........You can call Kinesis Firehose a "near real-time".<br>
........With Kinesis Data Streams you can´t do Transformation and conversion with Data.<br>
........With Kinesis Firehose you can do Transformation and conversion using AWS GLUE or AWS Lambda.<br>
........As Data compression you can´t compress data in stream with Amazon Kinesis Data Stream, but you can compress with gzip, Snappy, zip with Kinesis Firehose.<br>
<hr>
........ETL - Extract, transform and load: the process of combining data from multiple sources ina a large repository called data warehouse.<br>
........ETL uses a set of buiness rules to clean, organize and prepare raw data for storage, data analytics and Machine Learning (ML).<br>
........AWS Glue is the main service you use to do ETL.<br>
........AWS Glue can use JDBC or ODBC to connect to data sources outside AWS.<br>
<hr>
........Orchestrate data Pipelines on AWS<br>
........Use AWS Step Functions and AMAZON Managed Workflows for Apache Airflow (MWAA) to simplify ETL Workflow management.<br>
........AWS Step Functions workflow types.<br>
........Standard workflows can run for up one year, and have exactly-once workflow transformation.<br>
........Express workflows can run for up five minutes, and have at-least-once workflow transformation.<br>
........Express is more suitable for high-event-rate and streaming data processing.<br>
........For long-running, auditable, debugging and show execution history use Standard workflows.<br>
........<br>
........CI/CD - Continuos integration and continuous delivery<br>
........AWS CodePipeline: AWS CodeCommit, AWS CodeBuild, AWS CodeDeploy<br>
........<br>
........AWS Lambda<br>
........To scale up Lambda Functions you need to add more memory.<br>
........Lambda execution models : Synchronous (push), Asynchronous (event based) and Stream (Poll-based).<br>
........Lambda maximum invocation timeout limit is 15 minutes.<br>
........<br>
........You you not have get-in-depth question on exam about CDK and Cloudformation but you got to know.<br>
........CloudFormation is a foundation of Infrastructure as a code.
........AWS CDK you can write code in programming languages, example: Python.<br>
........and CDK will call CloudFormation to deploy your code.<br>
........AWS SAM Serverless Application Model (AWS SAM).<br>
........<br>
........Apache Parquet and Apache ORC File formats.<br>
........is more compressible and more fast to be queried.<br>
........
........
<h1>Video 04 - Exam Strategy Session</h1> <br>
........Domain 1 - Exam Questions!<br>
........<br>
........Question 1 - Data Lake Automation <br>
........
........A legal firm manages various on-premises servers containing documents in text, PDF and CSV files. These contain confidential information related to contracts, lawsuits and customer data.<br>
........The firm aims to migrate and centralize data into a data lake.<br>
........The company wants to implement automated processes for sensitive data verification and segregation, including long-term storage of findings for auditing purposes.<br>
........Which tasks would achieve this goal with minimum effort ? (Select 2 options) <br>
........<br>
........A. Utilize Amazon EFS for data extraction, transformation and loading into the Data Lake.<br>
........B. Configure Amazon S3 bucket policies to segregate sensitive and non-sensitive data.<br>
........C. Deplou Amazon Macie to automatically discover, classify and protect sensitive data. <br>
........D. Use AWS Glue DataBrew to automatically discover, classify and protect sensitive data. <br>
........Answer: "B" and "C" <br>
........<br>
........<br>Tip: Glue DataBrew is more like a visualization tool. <br>
........<br>
........<br>
........Question 2 - Data Warehouse ingestion<br>
........<br>
........A company is collecting data from sensors located around the world.<br>
........The data is collected and stored in an S3 bucket as JSON files. A data engineer needs to load this data into their data warehouse running in an Amazon Redshift cluster.<br>
........Once the data is loaded, it will be queried and used to create visualizations.<br>
........Which solution would meet the requirements with the least operational overhead ?<br>
........<br>
........A. Create a glue workflow to convert the data to ORC format. Then use the Redshift COPY command to load the data directly in the cluster using the VARCHAR data type. <br>
........B. Create a glue workflow to convert the data to PARQUET format. The use the Redshift COPY command to load the data directly in the cluster using the SUPER data type. <br>
........C. Use the Redshift COPY command to load the data directly in the cluster using the VARCHAR data type. <br>
........D. Use the Redshift COPY command to load the data directly in the cluster using the SUPERE data type. <br>
........Answer: "D", With the introduction of the SUPER data type, AMAZON REDSHIFT provides a rapid and flexible way to ingest JSON data and query it without the need to impose a schema.<br>
........You can now load it directly into AMAZON Redshift without ETL. <br>
........<br>
........<br>
........Question 3 - Hive Metastore Configuration<br>
........<br>
........A company is using a persistent Amazon EMR cluster to process vast amounts of data and store them as external  <br>
........tables in an S3 bucket. The Data Analyst must launch several transient EMR clusters to access the same tables  <br>
........simultaneously. However, the metadata about the Amazon S3 external tables are stored and defined on the persistent cluster.  <br>
........Which of the following is the most efficient way to expose the Hive mestastore with minimal effort? <br>
........<br>
........A. Configure Hive to use an Amazon DynamoDB as its metastore.  <br>
........B. Configure Hive to use an External MySQL Database as its metastore. <br>
........C. Configure Hive to use the AWS Glue Data Catalog as its metastore. <br>
........D. Configure Hive to use Amazon Aurora as its metastore. <br>
........Answer: "C" -  What is a Metastore ? is "data" about the data, like what is the schema, what is the data types for the data ? <br>
........AWS Glue Data Catalog is a metastore, it's purpose built for that.<br>
........Using Amazon EMR you can configure Hive to use the AWS Glue Data Catalog as its metastore, this is recommended configuration when you<br>
........require a persistent metastore or a metastore shared by different clusters, services, applications or AWS accounts.<br>
........<br>
........<br>
........Question 4 - Infrastructure as Code<br>
........<br>
........A data engineer is using the AWS Cloud Development Kit (CDK) to create a repeatable deployment for their data platform.<br>
........The data engineer has written the code and is ready to provision the resources into their AWS environment.<br>
........Which command will turn the CDK code into a CloudFormation template?<br>
........<br>
........A. cdk diff<br>
........B. cdk deploy<br>
........C. cdk bootstrap<br>
........D. cdk synth<br>
........Answer: "D" - the sequence using CDK is: init, bootstrap, synth and deploy.<br>
........<br>
........<br>
........Question 5 - SQL<br>
........<br>
........<br>A data engineer is working with an Amazon RDS database instance in an AWS environment.<br>
........The database contains a table named "employees" with the following columns:<br>
........<br>
........- employee_id (INT, Primary Key)<br>
........- first_name (VARCHAR(50))<br>
........- last_name (VARCHAR(50))<br>
........- department (VARCHAR(50))<br>
........<br>
........They need to retrieve a list of all employee´s first names and last names from the "employees" table.<br>
........Which of the following SQL queries would correctly accomplish this task?<br>
........<br>
........A. SELECT first_name, last_name FROM employees;<br>
........B. GET first_name, last_name FROM employees;<br>
........C. RETRIEVE first_name, last_name FROM employees;<br>
........D. SELECT employees FROM first_name, last_name;<br>
........Answer: "A" <br>
........<br>
https://www.linkedin.com/posts/f%C3%A1bio-samuel-dos-santos-canedo-2708b533_aws-dea-dataengineerassociate-activity-7197287819017367553-ja8D?utm_source=share&utm_medium=member_desktop
<br>
........On AWS Data Engineer Associate, you need to focus on AWS Redshift, AWS GLUE, AWS S3, AWS Lake Formation, AWS Kinesis Data Streams, AWS Kinesis Firehose, set data pipelines.<br>
<h1># 2025-01-12 - 1st Simulated Session of a exam</h1><br>
........13% of a overall of 200 questions answered right. As a expected low rate. Keep studying.<br>
<hr>
# 2025-01-13 - Video 05 - Content Review: Development with AWS Services
<br>
### Amazon Athena, Amazon QuickSight, Serverless Analytics and AWS Hadoop Fundamentals.
<br>
###### Choosing a data store, Understand data cataloging systems, Manage the lifecycle of data anda Design data models and schema evolution.<br>
###### Review Amazon S3 Storage Types: S3 Intelligent-Tiering, S3 Standard, S3 Standard-IA, S3 Glacier, S3 Glacier Deep Archive, S3 One Zone-IA.<br>
###### Review Amazon EFS Elastic File System => Using NFS Protocol, is just a file system designed for multiple lambda functions or EC2 instances<br>
connect to one central file share, it´s grow and shrink as data is added or deleted.<br>
###### Review EBS Amazon Elastioc Block Storage: it´s your storage directly attached to your EC2 instance.<br>
<hr>
### AWS Transfer Family: SFTP, FTPS, FTP and AS2 Protocols.
<br>
### Amaozon RedShift: is a DATA WAREHOUSE<br>
###### DC2 = Dense Compute Node, we have a cluster made of a Leader Node (the Brain, realizes queries and computing) and Compute nodes. All inteligence stays in leader node.
###### Data is really stored in Compute nodes and it has the muscles, in further computer nodes have slices; slices is just a allocation of Ram and Storage and is where the computation actually happens.
###### You have to know for these cluster is with DC2 nodes you have to scale compute and storage together.
<br>
###### Amazon Redshift cluster architecture - RA3.
###### In RA3 you have leader node, compute nodes but the difference is you can scale compute and storage separately because RMS (Redshift Managed Storage) manages all for you.
###### RA3 is recommended becaus it has lot of benefits compared to DC2.
###### Redshift Spectrum can run queries on S3, Redshift Federated Query can run queries on RDS.
<br>
###### Columnar Data Storage.<br>
###### RDS ->> OLTP ->> CSV ........ or ........ REDSHIFT ->> OLAP ->> Parquet<br>
###### 
<hr>
### Data Cataloging Services : AWS GLUE
####### DATA Catalog is basic a index of where the data is located and what the schema of the data.
####### data catalog is a metadata, the data about the data.
####### AWS Glue crawlers: Connects to a data store, extract the schema of your data then populates the Data Catalog.
####### AWS Glu Triggers: Scheduled, Conditional and On-Demand. 
<hr>
####### How i load data from S3 into Redshift? You do that with the Redshift COPY command; and for a bunch files use manifest file.
####### Amazon S3 Lifecycle: Review how data noves between S3 Storage types.
####### Amazon S3 Versioning, once you turn versioning on, a change to an object occurr an another copy of the object is created and stored.
<hr>
####### Amazon DynamoDB - Time to Live TTL
####### Amazon Redshift Distribution styles
####### AUTO, EVEN, KEY and ALL
####### in AUTO assigns a optimal distribution style based on the size of the table data, when the tables grows larger, Amazon REDSHIFT might change the distribution style, let´s say to KEY.
####### in EVEN is appropriate when a table doesn´t participate in joins or when there isn´t a clear choice between KEY and ALL distribution.
####### in KEY the rows are distributed according to the values in one column.
####### in ALL a entire COPY of the Table is on every node, because of this is not great for large datasets but for small data sets.
####### Look at documentation of REDSHIFT for AMAZON REDSHIFT SCHEMA DESIGN
<br>
#### AWS Database Migration Service
####### Trusted way to migrate 1M+ databases with minimal downtime
####### AWS DMS and AWS Schema Conversion Tool (SCT) will use AWS SCT.
####### 
<h1># 2025-01-14 - Four Live Sessions </h1><br>
EdN - Live Escola da Nuvem
Bootcamp IA para Startups
ONE Brasil - Hello, Oracle ONE!
Proz - Arquitetos na Nuvem
<br>
2025-01-15
Soft Skills Oracle ONE!
2025-01-16
Soft Skills Oracle ONE!
2025-01-17
Video aula Sebrae AWS
2025-01-18
Finalizado o Curso SEBRAE / AWS

2025-03-11
Iniciando o Curso: Complete AWS Certified Data Engineer Associate - DEA-C01 by Nikolai Schuler ( Udemy )
Projetando a prova de exame do DEA para 24-03-2025.

---////<br><br>
This Redme.md is in development<br>
