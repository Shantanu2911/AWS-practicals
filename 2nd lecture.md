# 2nd Lecture

## Cloud Computing
- On-demand delievery
- Pay-as-you-go model
- Provision only the size you need (exactly right type and size)
- Access resources instantly

## S3
- Object Storage with durability of 99.999999% , 11 9's
    - (If 1 million objects stored loss of 1 object every 10k years)
- Infinitely Scaling Storage
- Can keep files in buckets
- S3 is a global service but buckets are created in specific regions
- Globally unique bucket names

- Security
    - User based IAM policies
    - Resource based
        - Bucket Policies
        - Bucket ACLs
        - Object ACLs
- Public vs Private accessible Buckets
- Object versioning
- State-of-the-art in-transit and at-rest encryption

- Storage Classes
     - Amazon S3 Standard - general purpose
     - Amazon S3 Standard-Infrequent Access (IA)
     - Etc...
## EC2
- Most Popular AWS offering
- Infrastructure as a code service
- Provide rented VIrtual Machines
- EC2 uses EBS and instance store to store data
- EC2 uses autoscaling for scaling purpose
- Bootstrapping can be done using userdata scripts
