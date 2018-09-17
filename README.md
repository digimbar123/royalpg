# royalpg
royalpg
Q1) Amazon Glacier is designed for: (Choose 2 answers)

A. active database storage.
B. infrequently accessed data.
C. data archives.
D. frequently accessed data.
E. cached session data.
Ans) B. infrequently accessed data.
C. data archives.
Q2) Your web application front end consists of multiple EC2 instances behind an Elastic Load Balancer. You configured ELB to perform health checks on these EC2 instances. If an instance fails to pass health checks, which statement will be true?

A. The instance is replaced automatically by the ELB.
B. The instance gets terminated automatically by the ELB.
C. The ELB stops sending traffic to the instance that failed its health check.
D. The instance gets quarantined by the ELB for root cause analysis.
Ans) C. The ELB stops sending traffic to the instance that failed its health check.
Q3) You are building a system to distribute confidential training videos to employees. Using CloudFront, what method could be used to serve content that is stored in S3, but not publicly accessible from S3 directly?

A. Create an Origin Access Identity (OAI) for CloudFront and grant access to the objects in your S3 bucket to that OAI.
B. Add the CloudFront account security group "amazon-cf/amazon-cf-sg" to the appropriate S3 bucket
policy.
C. Create an Identity and Access Management (IAM) User for CloudFront and grant access to the
objects in your S3 bucket to that IAM User.
D. Create a S3 bucket policy that lists the CloudFront distribution ID as the Principal and the target
bucket as the Amazon Resource Name (ARN).
Ans) A. Create an Origin Access Identity (OAI) for CloudFront and grant access to the objects in your S3 bucket to that OAI.
Q4) Which of the following will occur when an EC2 instance in a VPC with an associated Elastic IP is stopped and started? (Choose 2 answers)

A. The Elastic IP will be dissociated from the instance
B. All data on instance-store devices will be lost
C. All data on EBS (Elastic Block Store) devices will be lost
D. The ENI (Elastic Network Interface) is detached
E. The underlying host for the instance is changed
Ans) B. All data on instance-store devices will be lost
E. The underlying host for the instance is changed
Q5) In the basic monitoring package for EC2, Amazon CloudWatch provides the following metrics:

A. web server visible metrics such as number failed transaction requests
B. operating system visible metrics such as memory utilization
C. database visible metrics such as number of connections
D. hypervisor visible metrics such as CPU utilization
Ans) D. hypervisor visible metrics such as CPU utilization, disk I/O, network I/O

Q6) Which is an operational process performed by AWS for data security?

A. AES-256 encryption of data stored on any shared storage device
B. Decommissioning of storage devices using industry-standard practices
C. Background virus scans of EBS volumes and EBS snapshots
D. Replication of data across multiple AWS Regions
E. Secure wiping of EBS data when an EBS volume is unmounted
Ans) B. Decommissioning of storage devices using industry-standard practices
Q7) You have been tasked with creating a VPC network topology for your company. The VPC network must support both Internet-facing applications and internally-facing applications accessed only over VPN. Both Internet-facing and internally-facing applications must be able to leverage at least three AZs for high availability. At a minimum, how many subnets must you create within your VPC to accommodate these requirements?

A. 2
B. 3
C. 4
D. 6
Ans) D. 6
Q8) You receive a Spot Instance at a bid of $0.05/hr. After 30 minutes, the Spot Price increases to $0.06/hr and your Spot Instance is terminated by AWS. What was the total EC2 compute cost of running your Spot Instance?

A. $0.00
B. $0.02
C. $0.03
D. $0.05
E. $0.06
Ans) A. $0.00
Q9) You are developing a highly available web application using stateless web servers. Which services are suitable for storing session state data?
Choose 3 answers

A. Amazon CloudWatch
B. Amazon Relational Database Service (RDS)
C. Elastic Load Balancing
D. Amazon ElastiCache
E. AWS Storage Gateway
F. Amazon DynamoDB 
Ans) B. Amazon Relational Database Service (RDS)
D. Amazon ElastiCache
F. Amazon DynamoDB
Q10) You have a business-critical two-tier web app currently deployed in two AZs in a single region, using Elastic Load Balancing and Auto Scaling. The app depends on synchronous replication (very low latency connectivity) at the database layer. The application needs to remain fully available even if one application AZ goes off-line, and Auto Scaling cannot launch new instances in the remaining Availability Zones. How can the current architecture be enhanced to ensure this?

A. Deploy in two regions using Weighted Round Robin (WRR), with Auto Scaling minimums set for 50 percent peak load per Region.
B. Deploy in two regions using Weighted Round Robin (WRR), with Auto Scaling minimums set for 100 percent peak load per region.
C. Deploy in three Availability Zones, with Auto Scaling minimum set to handle 50 percent peak load per zone.
D. Deploy in three Availability Zones, with Auto Scaling minimum set to handle 33 percent peak load per zone. 
Ans) C. Deploy in three Availability Zones, with Auto Scaling minimum set to handle 50 percent peak load per zone.
Q11) You are deploying an application on EC2 that must call AWS APIs. What method of securely passing credentials to the application should you use?

A. Use AWS Identity and Access Management roles for EC2 instances.
B. Pass API credentials to the instance using instance userdata.
C. Embed the API credentials into your JAR files.
D. Store API credentials as an object in Amazon Simple Storage Service. 
Ans) A. Use AWS Identity and Access Management roles for EC2 instances.
Q12) Which route must be added to your routing table in order to allow connections to the Internet from your subnet?

A. Destination: 0.0.0.0/0 --> Target: your Internet gateway
B. Destination: 192.168.1.257/0 --> Target: your Internet gateway
C. Destination: 0.0.0.0/33 --> Target: your virtual private gateway
D. Destination: 0.0.0.0/0 --> Target: 0.0.0.0/24
E. Destination: 10.0.0.0/32 --> Target: your virtual private gateway 
Ans) A. Destination: 0.0.0.0/0 --> Target: your Internet gateway
Q13) A customer's nightly EMR job processes a single 2-TB data file stored on Amazon Simple Storage Service (S3). The EMR job runs on two On-Demand core nodes and three On-Demand task nodes. Which of the following may help reduce the EMR job completion time?
Choose 2 answers

A. Use three Spot Instances rather than three On-Demand instances for the task nodes.
B. Change the input split size in the MapReduce job configuration.
C. Use a bootstrap action to present the S3 bucket as a local filesystem.
D. Launch the core nodes and task nodes within an Amazon Virtual Cloud.
E. Adjust the number of simultaneous mapper tasks.
F. Enable termination protection for the job flow. 
Ans) B. Change the input split size in the MapReduce job configuration.
E. Adjust the number of simultaneous mapper tasks.
Q14) You have an VPC with a public subnet. Three EC2 instances currently running inside the subnet can successfully communicate with other hosts on the internet. You launch a fourth instance in the same subnet, using the same AMI and security group configuration you used for the others, but find that this instance cannot be accessed from the Internet. What should you do to enable Internet access?

A. Deploy a NAT instance into the public subnet.
B. Modify the routing table for the public subnet.
C. Assign an elastic IP address to the fourth instance.
D. Configure a publicly routable IP address in the host OS of the fourth instance. 
Ans) C. Assign an elastic IP address to the fourth instance.
Q15) Which of the following requires a custom CloudWatch metric to monitor?

A. Memory use (Memory Utilization of an EC2 instance)
B. CPU use (CPU Utilization of an EC2 instance)
C. Disk read operations (Disk usage activity of an EC2 instance)
D. Network in (Data transfer You are tasked with setting up a Linux bastion host for access to Amazon EC2of an EC2 instance)
E. Estimated charges 
Ans) A. Memory use

However, there's one big missing feature in CloudWatch: it doesn't monitor your instance memory utilization
http://arr.gr/blog/2013/08/monitoring-ec2-instance-memory-usage-with-cloudwatch/

Q16) Which of the following is a durable key-value store?

A. Amazon Simple Storage Service
B. Amazon Simple Workflow Service
C. Amazon Simple Queue Service
D. Amazon Simple Notification Service
Ans) A. Amazon Simple Storage Service
Q17) After creating a new AWS account, you use the API to request 40 on-demand EC2 instances in a single AZ. After 20 successful requests, subsequent requests failed. What could be a reason for this issue, and how would you resolve it?

A. You encountered a soft limit of 20 instances per region. Submit the limit increase form and retry the failed requests once approved.
B. AWS allows you to provision no more than 20 instances per Availability Zone. Select a different Availability Zone and retry the failed request.
C. You need to use Amazon Virtual Private Cloud (VPC) in order to provision more than 20 instances in a single Availability Zone. Simply terminate the resources already provisioned and re-launch them all in a VPC.
D. You encountered an API throttling situation and should try the failed requests using an exponential decay retry algorithm.
Ans) A. You encountered a soft limit of 20 instances per region. Submit the limit increase form and retry the failed requests once approved.
Q18) Amazon Glacier is designed for:
Choose 2 answers

A. Frequently accessed data
B. Active database storage
C. Data archives
D. Infrequently accessed data
E. Cached session data 
Ans) C. Data archives
D. Infrequently accessed data
Q19) You have an application running in us-west-2 that requires six EC2 instances running at all times. With three AZs available in that region (us-west-2a, us-west-2b, and us-west-2c), which of the following deployments provides 100 percent fault tolerance if any single AZ in us-west-2 becomes unavailable?
Choose 2 answers

A. Us-west-2a with two EC2 instances, us-west-2b with two EC2 instances, and us-west-2c with two EC2 instances
B. Us-west-2a with three EC2 instances, us-west-2b with three EC2 instances, and us-west-2c 
