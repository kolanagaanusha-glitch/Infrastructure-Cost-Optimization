# Day 6 - Cost Analysis Report
## Existing Infrastructure Cost

| Resource | Monthly Cost |
|-----------|-------------|
| EC2-1 | $100 |
| EC2-2 | $100 |
| RDS | $150 |
| S3 | $80 |
| Load Balancer | $50 |
| Total | $480 |
## Optimization Applied

1. Right-sized EC2-1
2. Removed idle EC2-2
3. Reduced database size
4. Archived old S3 files
5. Scaled down Load Balancer
## Optimized Infrastructure Cost

| Resource | Monthly Cost |
|-----------|-------------|
| EC2-1 | $60 |
| EC2-2 | $0 |
| RDS | $100 |
| S3 | $40 |
| Load Balancer | $30 |
| Total | $230 |
## Cost Savings

Before Optimization = $480

After Optimization = $230

Savings = $250 per month
## Cost Comparison

| Category | Before | After |
|-----------|---------|--------|
| Compute | $200 | $60 |
| Database | $150 | $100 |
| Storage | $80 | $40 |
| Load Balancer | $50 | $30 |
| Total | $480 | $230 |
## Findings

- Infrastructure costs reduced significantly.
- Idle resources were identified and removed.
- Storage costs decreased after archiving old files.
- Database resources were optimized.
- Overall efficiency improved.
## Conclusion

By applying cost optimization techniques such as right-sizing, removing idle resources, and optimizing storage, the monthly infrastructure cost was reduced from $480 to $230, resulting in a savings of $250 per month.