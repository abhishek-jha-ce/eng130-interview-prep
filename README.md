# Interview Preparation

## What is DevOps?
- **Dev Ops** is a set of practice that combines software development and IT operation. Its main aim is to shorten the time taken to develop a software or a piece of functionality and provide continuous delivery of high quality software. With the implementation of devops different teams can work together improving the speed of delivery and quality of products.

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

A continuous integration and continuous deployment (CI/CD) pipeline is a series of steps that must be performed in order to deliver a new version of software. CI/CD pipelines are a practice focused on improving software delivery throughout the software development life cycle via automation. 

In CI/CD process is used manage the development and delivery process in the form of pipeline. It can be catagorised into 4 stages: build, test, release and deploy. CI automates the build and test part. When a developer writes code and pushes to github, we automate the process of build and test part of the pipeline. The code is tested automatically and merged with the branch. If any problem arieses the developer is informed by automated message. 
CD/CDE adds the delivery (release) and deployment part to the pipeline. With CD, its incremental process to CI and moves the code the the development phase and with CDE it goes one step further by deploying it automatically. Every step is dependent on the previous process being successful and its main aim is to limit human interaction.

## What is PR(Pull Request)

A pull request is an event where a contributor/developer is ready to begin the process of merging new code changes with the main project repository. It is also referred to as merge request.

After starting a pull request we can see a high-level overview of the changes between our branch and the main branch. we can add summary, review the changes after each commit, add labels
After initializing a pull request, you'll see a review page that shows a high-level overview of the changes between your branch (the compare branch) and the repository's base branch. You can add a summary of the proposed changes, review the changes made by commits, add labels, milestones, and assignees, and @mention individual contributors or teams. 


## What is docker & docker compose?

Docker is an platform for developing, shipping, and running applications. Docker enables us to separate our applications from our infrastructure so we can deliver software quickly. With Docker, we can manage our infrastructure in the same way as we manage our applications. It helps us to significantly reduce the time it takes from writing code and running the application in production.

Docker Compose is a yaml file which is an automation script that allows us to run multiple images at one time. if you didn't have this file you would have to run the images one by one but the containers will not be linked together. the docker compose file allows you to run one script and then have this script build as many images as you need and then connect them at the same time.

## How do you handle stress?

Pressure, i believe, is very important aspect of any work place. Good pressure—such as having many tasks and upcoming deadline helps me to stay motivated and productive. If not handled properly these pressure leads to stress. I am skilled at balancing multiple projects and meeting deadlines, which prevents me for letting the pressure build up and turn it into stress. For e.g. I once had 2 tasks due in the same week, and it was a lot of pressure. However, I created a schedule that detailed how I would break down each project into small assignments, I managed to complete all tasks on time and avoid any unnecessary stress

## Why DevOps?

I was initially interested in pursuing a career in software development, but while learning about cloud computing i came across the practice of DevOps. I was fascinated how using devops we can do frequent changes to softwares through automation and have end products ready so smoothly. I have always been a team player and always loved working and collaboating with different teams. So i feel like Dev Ops is a career path which i would flourish in as i both enjoy the concepts and the process.

## Where do you see yourself in 2-5 years time?

In 2 to 5 years time i would like to see myself working in a position with lots of responsibility and mentoring emerging talents. I would like to be very confident in my tech skills and would like to be fully invested in my team and the products we create. In order to achieve that, my short term goal is to get placed with a client as soon as possible. In the next 2 years i would like to learn and develop further and become a competent dev-ops engineer, and in the 5 years i will be working as an arcitect.

## What can you bring to our team?

I have been trained for devops role at sparta global and i can bring along all the technical knowledge that i have learned. I also like taking creative approach to solve problems, which is very helpful for any team to have a team member who takes critical thinking approach for everything. I am also somebody who can take initiative and solve problems without being asked and can work independently. 
