# Aws-VPC-Repo
I developed a project named "Secure and Scalable Static Website Hosting: A Guide to AWS Route 53 and VPC Integration".

In our AWS project, we've established a robust infrastructure for hosting a website, leveraging key services for optimal performance and scalability. Our Virtual Private Cloud (VPC) is configured with two subnets: a public subnet for hosting the web application and an isolated private subnet housing our database. This setup enhances security by segregating public-facing components from sensitive data.

To ensure high availability and efficient resource management, we've incorporated an Application Load Balancer (ALB) into the architecture. The ALB intelligently distributes incoming traffic across multiple instances within an Auto Scaling Group (ASG). The ASG dynamically adjusts the number of instances based on traffic patterns, scaling in during low demand and scaling out when there's increased traffic. This approach not only enhances responsiveness but also optimizes costs by aligning resources with actual demand.

Our website's domain is managed through Amazon Route 53, which serves as the DNS web service. The Route 53 hosted zone is seamlessly integrated with the ASG, allowing for automatic scaling in and out of instances based on demand. This end-to-end setup ensures a resilient, scalable, and cost-effective solution for hosting our website, with a secure database residing in a private subnet within the VPC.
<br>
![new](https://github.com/ruchtr/Aws-VPC-Repo/assets/88919214/ea7d2c8c-99aa-4747-a531-5028b28e16b8)

