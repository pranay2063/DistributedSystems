
**AWS Components**

    Compute
        EC2 instances, Data Centres (DC), Availability Zones (AZ), Regions, Edge locations
        IAM - users, groups, roles
        EC2 - VM
        Containers, ECS
        Docker, Kubernetes, EKS
        Serverless, AWS Lambda

    Networking
        VPC
        Subnet
        Route table
        Gateway
        Network ACL, Security Groups (SGs)
            Network ACL is stateless while SG is stateful 
        https://www.coursera.org/learn/aws-cloud-technical-essentials/supplement/Zq1Wb/reading-2-5-networking-on-aws
        Elastic Load Balancer (ELB)
            ALB
            NLB
    
    Storage
        https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/Storage.html 
        EC2 instance store - ephemereal
        Elastic block store (EBS)
        File storage
        Object storage - S3
        S3 storage classes/tiers
            Buckets
            https://aws.amazon.com/s3/storage-classes/
     
    Databases
        https://aws.amazon.com/products/databases/
        Relational - RDS (Relational Database Service)
        Amazon AuroraDB via RDS
        NoSQL - DynamoDB

    Monitoring
        CloudWatch - metrics, alarms, logs (via log agent), dashboards
        https://www.coursera.org/learn/aws-cloud-technical-essentials/supplement/emkn9/reading-4-2-introduction-to-amazon-cloudwatch

    EC2 auto-scaling
           Launch template, scaling policies, target groups (of instances)
           Based on cloudwatch metrics/alarms
           Done via ELB
           Uses VPC, Subnets, security groups
        
        
        
        
    
    


