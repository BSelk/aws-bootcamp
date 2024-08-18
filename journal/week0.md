# Week 0 — Billing and Architecture

## Pre-requisites for the AWS project 
⦁	Setting up a Gitpod account 
⦁	Syncing GitHub Account with the GitPod account
⦁	Using the template on GitHub to get the same Repository structure
⦁	Creating a Lucidchart account for the architecture design
![Napkin Diagram](../_docs/assets/conceptual-Design.jpeg)
## GitHub Account journal week 0
Completed tasks for WEEK 0:
Conceptual Design is created
AWS CLI installation
Architecure DIagram for the CI/CD Pipeline is done
Install AWS CLI

⦁	We are going to install the AWS CLI when our Gitpod enviroment lanuches.
⦁	We are  going to set AWS CLI to use partial autoprompt mode to make it easier to debug CLI commands
⦁	Getting Familiar with the drectory structure
⦁	Updating the .gitpod.yml with incuding the following tasks
 
⦁	The commands ran manually to perform the installation
⦁	The bash commands we are using can be reviewed on the AWS Documentation page: https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

### Create a new User and Generate AWS Credentials
⦁	Go to the IAM Users Console for creating a  new User
⦁	Enable console access
⦁	Creating a new Admin group and apply Administrator Access (Not a best practice but okay for our use case)
⦁	Create  an Access Key for the AWS CLI
⦁	Save the credentials 

### Enable Billing
⦁	Billing Alerts are recommended for a better Overview on the monthly payment
⦁	The Root Account is required to for setting up Billing Alerts


### Create a Billing Alarm 
⦁	Required to create a SNS Topic for the Billing Alarm
⦁	SNS is used for getting Notifications in different ways like Mail, SMS etc.
Create an AWS Budget 
Go through the Instructions on the following page: https://docs.aws.amazon.com/cli/latest/reference/budgets/create-budget.html


