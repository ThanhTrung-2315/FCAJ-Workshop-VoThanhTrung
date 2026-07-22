---
title: "Week 8 Worklog"
date: 2024-01-01
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Week 8 Objectives:

* Understand the principles of Continuous Integration and Continuous Delivery (CI/CD).
* Build a deployment pipeline to automate the application build and deployment process.
* Integrate AWS services to support an automated software delivery workflow.

### Tasks to Be Carried Out This Week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Study the CI/CD workflow, including the Build, Test, and Deploy stages.<br>- Learn the roles of AWS CodeCommit, AWS CodeBuild, AWS CodeDeploy, and AWS CodePipeline.<br>- Design a deployment workflow that matches the project architecture. | 06/08/2026 | 06/08/2026 | https://docs.aws.amazon.com/codepipeline/ <br> https://000010.awsstudygroup.com/ |
| 3 | - Create a source code repository in AWS CodeCommit or connect an existing GitHub repository.<br>- Configure repository access and synchronize the source code.<br>- Verify the source code update process from the development environment. | 06/09/2026 | 06/09/2026 | https://docs.aws.amazon.com/codecommit/ |
| 4 | - Configure AWS CodeBuild to automatically build the application.<br>- Create a **buildspec.yml** file and define the build stages.<br>- Verify the build results and resolve any build issues. | 06/10/2026 | 06/10/2026 | https://docs.aws.amazon.com/codebuild/ |
| 5 | - Configure AWS CodePipeline to connect the Source, Build, and Deploy stages.<br>- Set up automatic deployment to Amazon ECS after a successful build.<br>- Update the source code and observe the pipeline execution process. | 06/11/2026 | 06/11/2026 | https://docs.aws.amazon.com/codepipeline/ |
| 6 | - Validate the complete CI/CD workflow from source code changes to application deployment on Amazon ECS.<br>- Evaluate the pipeline performance and optimize the deployment process.<br>- Finalize the implementation documentation and remove temporary AWS resources. | 06/12/2026 | 06/12/2026 | https://docs.aws.amazon.com/devops-guru/latest/userguide/welcome.html |

### Week 8 Achievements:

* Understood the principles and workflow of Continuous Integration and Continuous Delivery (CI/CD).
* Successfully configured a source code repository for the deployment pipeline.
* Implemented AWS CodeBuild to automatically build the application after source code updates.
* Built an automated deployment pipeline using AWS CodePipeline with Source, Build, and Deploy stages.
* Successfully deployed updated application versions to Amazon ECS through the CI/CD pipeline.
* Gained practical experience in applying CI/CD practices to automate software delivery, reduce manual deployment tasks, and improve development efficiency.