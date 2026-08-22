# Day 5 - Architecture Diagram and Documentation

## Objective

Create a visual representation of the cloud infrastructure and document its components.

## Architecture Components

1. Users
2. Load Balancer
3. EC2 Instance 1
4. EC2 Instance 2
5. RDS Database
6. S3 Storage

## Architecture Diagram

Users
  |
  v
Load Balancer
  |
  v
----------------
|              |
v              v
EC2-1        EC2-2
  |
  v
RDS Database
  |
  v
S3 Storage

## Component Description

### Load Balancer
Distributes incoming traffic across multiple servers.

### EC2 Instances
Run application workloads.

### RDS Database
Stores application data.

### S3 Storage
Stores files, images, backups, and logs.

## Benefits

- High Availability
- Scalability
- Better Performance
- Cost Optimization Opportunities

## Summary

The architecture diagram helps visualize cloud resources and identify optimization opportunities.