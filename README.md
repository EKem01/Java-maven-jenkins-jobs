
# Build Automation & CI/DI with jenkins

## Overview
This project provides a comprehensive guide for setting up and managing Jenkins jobs, including Freestyle jobs, Pipeline jobs, and Multi-branch Pipeline jobs.

![jenkins job](https://github.com/user-attachments/assets/4ca7f072-b709-4b49-9329-8319c91a8315)

### Table of Content

- Jenkins Installation: Check documentation for the Jenkins installation.
- Freestyle Jobs
- Pipeline Jobs
- Multi-branch Pipeline Jobs

Jenkins Jobs

- Freestyle jobs : Executing a single task. Build, test and deploy a single freestyle jobs.

- Pipeline : Executing a CI/CD pipeline jobs. Build, test and deploy a pipeline jobs with samples of declarative and scripted jobs.

- Multi-branch pipeline. A multibranch job is simply a folder of pipeline jobs. The Multibranch implements different Jenkinsfiles for different branches of the same project. In a Multibranch Pipeline project, Jenkins automatically discovers, manages and executes Pipelines for branches which contain a Jenkinsfile in source control.


### Freestyle Job

Create a New Freestyle Job:
- Click New Item on the Jenkins dashboard.
- Enter a name for your job, select Freestyle project, and click OK.


Configure Job:

- In the job configuration page, add a description if desired.
- Source Code Management: Specify your repository if your project requires it.
- Build Triggers: Set triggers for automated builds (e.g., Poll SCM, Build periodically).
- Build Steps: Add build steps (e.g., Execute shell, Invoke Ant).
Save and Build:
- Click Save to save your configuration.
- Trigger a build manually using the Build Now button.


### Pipeline Job

Create a New Pipeline Job:
- Click New Item on the Jenkins dashboard.
- Enter a name for your job, select Pipeline, and click OK.
Configure Job:
- In the job configuration page, add a description if desired.
- Pipeline Definition: Choose Pipeline script from SCM.
- Click Save to save your configuration.
- Trigger a build manually using the Build Now button.


### Multi-branch Pipeline Job

Create a New Multi-branch Pipeline Job:
- Click New Item on the Jenkins dashboard.
- Enter a name for your job, select Multi-branch Pipeline, and click OK.
- In the job configuration page, add a description if desired.
- Branch Sources: Add your SCM source (e.g., Git) and configure repository URL and credentials.
- Build Configuration: Specify the script path (default is Jenkinsfile).
Save and Scan Repository:
- Click Save to save your configuration.
J- enkins will automatically scan the repository and create jobs for each branch containing a Jenkinsfile.

Using the Jobs

- Trigger Builds: Manually trigger builds using the Build Now button or set up automated triggers.
- Monitor Builds: Use the Jenkins dashboard to monitor build status, view logs, and track pipeline progress.
- Manage Jobs: Update job configurations, manage build history, and handle job-specific settings via the job configuration pages.


This README provides the foundational steps to set up and manage Freestyle, Pipeline, and Multi-branch Pipeline jobs in Jenkins. Adjustments can be made based on specific project requirements and environments.



