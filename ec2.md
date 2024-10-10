# AWS EC2

1. **Elasticity and Scalability**

   - EC2 allows dynamic scaling of compute capacity, both up and down, based on traffic needs or predefined rules using Auto Scaling Groups.
   - Can handle sudden spikes in traffic and scale back when not needed, optimizing cost and performance.

2. **Instance Types**

   - EC2 provides various instance types optimized for different workloads (e.g., compute, memory, or storage-optimized).
   - Examples include general-purpose (t2.micro), compute-optimized (c5.large), and GPU instances (p3.2xlarge).

3. **Pricing Models**

   - Multiple pricing models are available:
     - **On-Demand**: Pay for compute capacity by the hour with no long-term commitment.
     - **Reserved Instances**: Offers discounts for committing to one or three years.
     - **Spot Instances**: Access spare compute capacity at a discount, ideal for flexible workloads.

4. **Security**

   - EC2 uses **Security Groups** to control inbound and outbound traffic at the instance level.
   - It integrates with **IAM** for controlling user access to resources and supports encryption for EBS volumes and instance storage.

5. **Networking**
   - EC2 instances can be launched in a Virtual Private Cloud (VPC) for isolation and security.
