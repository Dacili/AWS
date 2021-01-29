# AWS - Amazon Web Services

Expanding my knowledge in cloud computing.
Currently learning the most commonly used AWS services, such as EC2, Elastic Beanstalk, S3, IAM, RDS, Lamda, Route53, DynamoDB, Cloudwatch, etc...

Because of the costs of aws services, these instances are not running always. So that's the reason why I will upload images without links to created resources.

**Elastic beanstalk** - for hosting your web apps (you don't manage separately services, elastic beanstalk does it for you :D)
![alt text](https://github.com/Dacili/AWS/blob/master/elastic%20beanstalk.PNG)

**EC2 (Elastic Compute Cloud)** instance  - similar to a virtual machine (VM)
![alt text](https://github.com/Dacili/AWS/blob/master/ec2.PNG)

**S3 (Simple storage service)**  - storage that contains buckets (think of it as folders), in buckets you are putting the files. 
![alt text](https://github.com/Dacili/AWS/blob/master/s3.PNG)

**Lamda**  - serverless functions (trigger them on the events that you choose, very cheap, auto-scalable..)
I was triggering my lambda execution on the event: uploading files in S3.
![alt text](https://github.com/Dacili/AWS/blob/master/lambda1.PNG)
All logs are managed with the **Cloud watch** :
![alt text](https://github.com/Dacili/AWS/blob/master/lamda%20cloud%20watch%20logs.PNG)

**IAM - Identity and Access Management** - use of IAM is for the security and identity. You can create groups, roles, users. You can assign different permissions to them. <br />
![alt text](https://github.com/Dacili/AWS/blob/master/IAM.PNG)

Databases: <br />
* **DynamoDB** - NoSql database <br />
* **RDS** - SQL database <br />
* There are also many others options for dbs (like Aurora, Elasticache)...


