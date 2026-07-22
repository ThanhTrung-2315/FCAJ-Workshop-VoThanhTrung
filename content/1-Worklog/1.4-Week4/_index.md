---
title: "Week 4 Worklog"
date: 2024-01-01
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Week 4 Objectives:

* Understand the operating principles of Elastic Load Balancing (ELB).
* Deploy Amazon EC2 Auto Scaling to automatically scale application resources.
* Evaluate load balancing performance and application availability on AWS.

### Tasks to Be Carried Out This Week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Study the architecture of Elastic Load Balancing (ELB).<br>- Compare the different types of AWS Load Balancers.<br>- Learn how incoming traffic is distributed across multiple Amazon EC2 instances. | 05/11/2026 | 05/11/2026 | https://docs.aws.amazon.com/elasticloadbalancing/ <br> https://000006.awsstudygroup.com/ |
| 3 | - Prepare the deployment environment, including the VPC, Subnets, and Amazon EC2 instances.<br>- Create a Target Group and register EC2 instances.<br>- Configure an Application Load Balancer (ALB) to distribute application traffic. | 05/12/2026 | 05/12/2026 | https://docs.aws.amazon.com/elasticloadbalancing/ |
| 4 | - Study Amazon EC2 Auto Scaling.<br>- Create a Launch Template and an Auto Scaling Group.<br>- Configure the minimum, maximum, and desired instance capacity. | 05/13/2026 | 05/13/2026 | https://docs.aws.amazon.com/autoscaling/ |
| 5 | - Configure a Scaling Policy based on CPU utilization.<br>- Generate application workload to simulate traffic.<br>- Observe the automatic scaling process of Amazon EC2 instances. | 05/14/2026 | 05/14/2026 | https://docs.aws.amazon.com/autoscaling/ |
| 6 | - Evaluate the performance of the Load Balancer and Auto Scaling configuration.<br>- Verify the Target Group health checks.<br>- Remove the deployed AWS resources and update the implementation notes. | 05/15/2026 | 05/15/2026 | https://docs.aws.amazon.com/ |

### Week 4 Achievements:

* Understood how Elastic Load Balancing distributes incoming traffic across multiple Amazon EC2 instances.
* Successfully deployed an Application Load Balancer integrated with multiple EC2 instances.
* Created an Auto Scaling Group based on a Launch Template.
* Configured Auto Scaling policies according to system resource utilization.
* Verified the automatic scale-out and scale-in process under different workload conditions.
* Gained practical experience in combining Elastic Load Balancing and Auto Scaling to improve application availability and scalability on AWS.