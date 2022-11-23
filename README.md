# Interview Preparation

## What is DevOps?
- **Dev Ops** is a set of practice that combines software development and IT operation. Its main aim is to shorten the time taken to develop a software or a piece of functionality for that software and provide continuous delivery of high quality software. With the implementation of devops different teams can work together improving the speed of delivery of products.

## What are the benefits of DevOps?
- Faster & better product delivery
- Faster issue resolution
- Better resource utilization
- Greater automation
- Stable working environment
- Greater innovation

## What is a VPC?
VPC is a service that enables us to create our own private network in the public cloud. We can then launch our resources inside the VPC and allow access to only authorized users. It resembles the traditional network that is operated in the data center.

We use the VPC by creating subnets inside the VPC, inside which we deploy our resources. These resources are enclosed within a firewall (also called security groups) which allows only authorize access. We further have a route table which directs the traffic coming in the VPC to the associated subnets.


## What is the difference between a monolith & 2tier architecture?

A monolithic architecture is a traditional way of developing software where everything is build as a single unit and cannot function inependently. It is self contained and is independent from any other application.

The 2 tier architecture is a architecture where we separate the presentation layer of our software from the database of the software. We deploy it in two different servers, giving access to everyone to view the interface or the app, and not allowing anyone except the app itself to access the database.

This makes the app scalable and highly secure. 

### S Interview Questions
## Describe the CI/CD process, from making changes to the code to integrating into the pipeline.

In CI/CD process developers writes code and pushes it to a github repository using the public key. The webhook triggers a Jenkins build for that repository or we can manually trigger this build a webhook is a API that provides data as it is happening so you get the changes immediately as they are committed rather having to frequently pulling after this webhook is triggered, Jenkins will clone down this repository to its local workspace so the agent node where it builds the product and runs its tests once this build is complete, the Jenkins publishes the results and launches the app using the pem file to an aws instance if the build is successful

## What is PR(Pull Request)

A pull request is an event where a contributor/developer is ready to begin the process of merging new code changes with the main project repository. It is also referred to as merge request.

After starting a pull request we can see a high-level overview of the changes between our branch and the main branch. we can add summary, review the changes after each commit, add labels
After initializing a pull request, you'll see a review page that shows a high-level overview of the changes between your branch (the compare branch) and the repository's base branch. You can add a summary of the proposed changes, review the changes made by commits, add labels, milestones, and assignees, and @mention individual contributors or teams. 


## What is docker & docker compose?

Docker is an platform for developing, shipping, and running applications. Docker enables us to separate our applications from our infrastructure so we can deliver software quickly. With Docker, we can manage our infrastructure in the same way as we manage our applications. It helps us to significantly reduce the time it takes from writing code and running the application in production.

Docker Compose is a yaml file which is an automation script that allows us to run multiple images at one time. if you didn't have this file you would have to run the images one by one but the containers will not be linked together. the docker compose file allows you to run one script and then have this script build as many images as you need and then connect them at the same time.

