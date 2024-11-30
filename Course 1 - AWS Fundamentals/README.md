# AWS Infrastructure Overview

## Key Components of AWS Infrastructure

1. **Regions**  
   - Geographic locations such as US East, US West, etc.  
   - Each region consists of multiple Availability Zones (at least 2).  

2. **Availability Zones (AZs)**  
   - Isolated locations or physical data centers within a region.  
   - Designed to be failure-independent with multiple data centers.  

3. **Edge Locations**  
   - Mini data centers that serve multiple AZs.  
   - Used for caching large files and enhancing performance with AWS CDN (Content Delivery Network).  

Learn more about AWS Global Infrastructure:  
[AWS Global Infrastructure Overview](https://aws.amazon.com/about-aws/global-infrastructure/)  
[AWS Regions and Availability Zones](https://aws.amazon.com/about-aws/global-infrastructure/regions_az/)

---

## Why Learn About AWS Infrastructure?

- Understanding AWS infrastructure enables you to build **highly available** applications with **minimum latency**.  
- Example: If your application primarily serves users in India, hosting resources in Indian regions ensures **low latency** and **better performance**.

---

## Points to Remember

1. Resources do not replicate across multiple regions unless explicitly configured.  
   Example: A resource created in `us-east-1` will not automatically appear in `us-east-2`.  

