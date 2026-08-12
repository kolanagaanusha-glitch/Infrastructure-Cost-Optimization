# Sample Company Infrastructure

Company: ABC Online Shopping

Resources:
1. EC2 Server 1 - Web Application
2. EC2 Server 2 - Backup Server
3. RDS Database
4. S3 Storage
5. Load Balancer
Users
  |
  v
Load Balancer
  |
  v
----------------
|              |
v              v
EC2-1      EC2-2
  |
  v
RDS Database
  |
  v
S3 Storage
          ## Resource Usage Analysis
          | Resource | Usage | Observation |
|----------|-------|-------------|
| EC2-1 | 25% CPU | Underutilized |
| EC2-2 | 10% CPU | Mostly Idle |
| RDS | Low Traffic | Over-sized |
| S3 | Old Files | Unused Data |
| Load Balancer | Low Requests | Underused | 
                        ## Cost Problems Identified
                        1. EC2-1 is running at only 25% utilization.
2. EC2-2 is mostly idle.
3. Database size is larger than required.
4. Old files are consuming storage.
5. Load Balancer is underutilized.
                     ## Cost Optimization Opportunities
                     | Problem | Solution |
|----------|----------|
| Large EC2 Instance | Right-size Instance |
| Idle Server | Stop or Remove |
| Large Database | Reduce Database Size |
| Old S3 Data | Archive Data |
| Low Traffic Resources | Scale Down |