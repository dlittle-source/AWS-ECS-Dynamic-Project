**Project: Hosting Dynamic Website on AWS Fargate**

**Overview:** This project aims to demonstrate the deployment of a dynamic website on AWS ECS Fargate, utilizing various AWS services for scalability, reliability, and security.

**Deployment Steps:**

1. **Virtual Private Cloud (VPC):**
   - Configured a VPC with 2 public and 4 private subnets spread across two availability zones for fault tolerance.

2. **Internet Gateway:**
   - Deployed an Internet Gateway to enable connectivity between the VPC and the wider Internet.

3. **Security Groups:**
   - Established Security Groups as a network firewall mechanism to control traffic to and from various resources.

4. **High Availability:**
   - Utilized two Availability Zones to enhance system reliability and fault tolerance.

5. **Public Subnets:**
   - Public subnets were employed for infrastructure components like NAT Gateway and Application Load Balancer.

6. **ECS Fargate:**
   - Implemented ECS Fargate for secure containerized deployments within both public and private subnets.

7. **SSH Key Management:**
   - Created a public SSH key and added it to the GitHub account for secure repository access.

8. **Docker Image Management:**
   - Dockerized the application with a Dockerfile and pushed it to a Docker repository.

9. **ECR (Elastic Container Registry):**
   - Created an ECR on AWS and pushed the Docker image to ECR for versioned image management.

10. **IAM User:**
    - Created an IAM user with programmatic access for secure API interactions.

11. **Version Control:**
    - Stored the Dockerfile on GitHub for version control and collaborative development.

12. **Secure Communication:**
    - Secured application communication using a Certificate Manager.

13. **Domain Registration and DNS Setup:**
    - Registered a domain name and set up DNS records using Route 53 for easy access.

14. **Database Migration:**
    - Utilized Flyway to migrate data into RDS database seamlessly.

15. **Sensitive Information Protection:**
    - Created a GitIgnore file to protect sensitive information from being exposed.

16. **Bastion Host:**
    - Created a Bastion Host to securely access private EC2 instances for software installations and maintenance.

**Repository:** The reference diagram and Dockerfile used for this project is available in the GitHub repository. Please refer to the repository for detailed instructions on deploying the Docker image on AWS infrastructure.

**Conclusion:** By leveraging AWS services, this project demonstrates a scalable, reliable, and secure approach to hosting dynamic websites on ECS Fargate, suitable for various production environments.
