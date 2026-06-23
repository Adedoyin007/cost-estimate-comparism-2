# AWS Cost Breakdown

## Amazon EC2

| Resource     | Configuration                        | Estimated Monthly Cost |
| ------------ | ------------------------------------ | ---------------------- |
| EC2 Instance | t3.micro, Dedicated Usage, 730 Hours | $8.03                  |

## Amazon RDS (Database Services)

| Resource              | Configuration                              | Estimated Monthly Cost |
| --------------------- | ------------------------------------------ | ---------------------- |
| RDS Database Instance | db.c6gd.medium Multi-AZ Cluster, 730 Hours | $174.11                |
| RDS GP3 Storage       | 1,025 GB                                   | $353.63                |
| RDS Provisioned IOPS  | 3,000 IOPS                                 | $900.00                |

### Total Amazon RDS Cost

**$1,427.73/month**

## Amazon S3

| Resource            | Configuration  | Estimated Monthly Cost |
| ------------------- | -------------- | ---------------------- |
| S3 Standard Storage | 100 GB Storage | $2.30                  |
| S3 Requests         | 1,000 Requests | $0.00                  |

### Total Amazon S3 Cost

**$2.30/month**

## Amazon EBS

| Resource           | Configuration | Estimated Monthly Cost |
| ------------------ | ------------- | ---------------------- |
| GP3 Storage Volume | 8 GB          | $0.64                  |

## Total AWS Monthly Cost

**Estimated Total: $1,438.70/month**

## Total AWS Annual Cost

**Estimated Total: $17,264.40/year**

## AWS Cost Analysis

This AWS estimate represents a production-grade architecture deployed in the US East (Ohio) region. The environment consists of a dedicated Amazon EC2 t3.micro instance for application hosting, Amazon S3 for object storage, Amazon EBS GP3 volumes for block storage, and a highly available Amazon RDS Multi-AZ database cluster.

The largest portion of the cost comes from Amazon RDS, accounting for approximately 99% of the total monthly expenditure. This is due to the use of a Multi-AZ database deployment with 1,025 GB of GP3 storage and 3,000 provisioned IOPS, providing high availability, fault tolerance, and enhanced database performance for enterprise workloads.

Amazon EC2 contributes a relatively small cost for compute resources, while Amazon S3 and EBS provide cost-effective storage services. Overall, this architecture is suitable for business-critical applications that require database redundancy, consistent performance, and high availability, but organizations should carefully evaluate database storage and IOPS requirements because they significantly impact total cloud spending.
