# AWSDEApreparation
--\
<a href="https://www.paypal.com/donate/?business=C5ZXDE6A7M28E&no_recurring=0&item_name=Donation+for+Owner+of+this+PayPal+Account&currency_code=BRL" target="_blank">
  <img src="https://www.paypalobjects.com/paypal-ui/logos/svg/paypal-color.svg" alt="PayPal Donation" width="100" height="50">
</a>


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
<h1>
# 2025-01-10</h1><br>
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
<h1>Video 02 - Content Review Session</h1><br>
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
.........Velocity: Speed of data flowing throught to be processed, analogy: Fast flowing river versus a slow moving stream, like process in real time ou batch jobs.<br>
.........Veracity: Degree to which data is accurate, precise and trusted, analogy: you have clean water and dirty water, in data coming in can be missing values<br>
.........Value: Ability to extract meaningful information from the data stored, analogy: there is more value in clean water, same with data dirty data,<br>
.........missing data, impurity data provides little value to a good clean dataset <br>
.........All analogies is to relate the 5 V´s with thinking about WATER being ingested in a lake or a reservoir. 
.........on exam you most focus in VOLUME, VARIETY and VELOCITY.<br>
...... <h2>DATA Source Types</h2><br> 
.........Structured DATA: Relational databases, data is organized in rows, columns, tables, <br>
.........Unstructured DATA: PDF, Jpeg, videos, a bunch of random data<br>
.........Semi-Structured DATA: JSON documents (Amazon REDSHIFT)
.........How i can handle these different DATA Types.<br>
......Amazon Simple Storage (related to VOLUME on 5 V´s)<br> 
......AWS Lake Formation (related to VOLUME on 5 V´s)<br>
......Amazon RedShift (related to VOLUME on 5 V´s)<br>
......Amazon Relational Database Service (related to VARIETY on 5 V´s)<br>
........Set up, operate and scale a Relational SQL database in the cloud.<br>
........Aurora, PostgreSQL, MySQL, MariaDB, OracleDB and SQL Server.<br>
......Amazon DynamoDB (related to VARIETY on 5 V´s)<br>
........Fast and flexible NoSQL database service for any scale.<br>
........Serverless KEY-VALUE and document database that delivers single-digit millisecond performance.<br>
........Maximize read throughput, atomicity consitency.<br>
......Amazon OpenSearch Service (related to VARIETY on 5 V´s)<br>
........Analyze logs, crm, social media.<br>
........can be used as a RAG data store and using LLM model can get information from OpenSearch.<br>
......Amazon EMR (related to VELOCITY on 5 V´s)<br>
........Elastic Map Reduce, run and scale Apache Spark, Hive, Presto and other Big Data Worloads.<br>
........for petabyte scale data processing, interactive analytics and Machine Learning using open-source frameworks.<br>
........HADOOP Clusters<br>
......Amazon MSK (related to VELOCITY on 5 V´s)<br>
.........Amazon MSK ingest and process streaming data in REAL TIME with a fully managed APACHE KAFKA<br>
......Amazon Kinesis Data Streams (related to VELOCITY on 5 V´s)<br>
........Cost-effectively process and analyzes streaming data as a managed service<br>
........ingest data from clickstream, iot, etc in real time.<br>
........Streaming data can be fan-out out multiple consumers like EC2, lambda, Spark or Amazon EMR and Amazon Managed Service for Apache Flink.<br>
........Amazon Kinesis is one of the focus services you have to study to be prepared for the exam.<br>
........Amazon Kinesis is about to how i ingest data, in real-time or near real-time and how i process streaming data.<br>
........i can store, i can process it, i can do a few different thing with that ingested data<br>
......Amazon Lambda (related to VELOCITY on 5 V´s)<br>
........Run Code without managing servers.<br>
........Remember the 15 min limitation from Lambda, when you in exam to discard or to choose lambda answers<br> 
........<br>
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






---////<br><br>
This Redme.md is in development<br>
