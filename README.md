# Projectable 
#### Assessment: Full Stack Application - Part A
#### Team: Felix Mckenzie & Robert Neville 
## Projectable Description 
**Purpose:**

Visual representation is vital when planning a project in a team setting as it conveys high level information to all involved. A Project Manager is responsible for taking a project from ideation to completion, and navigating the team through every step and problem in-between. Many Project Managers are faced with new challenges in today's post-pandemic world, now trying to lead their teams and projects through a completely remote, work-from-home environment. Moreover, it seems remote work is here to stay: 74% of professionals expect remote work to become standard, with 97% not wanting to return to the office full-time (Prossack, 2021). How can teams achieve the same level of success in a distributed workforce? 

Task management and communication is central to the success of any Project Manager and team. Projects are made up of dozens of tasks each with their own level of difficulty and time requirements. 77% of high-performing projects use project management software, yet only 22% of organizations actually make the investment (TeamStage, 2020). 

While several project management tools exist on the market, many have been met with criticism from users. Existing tools such as Jira are feature rich, however can be complicated to use, with unintuitive workflows and slow load times, and most importantly no dark mode. Simpler alternatives, such as Trello and Asana, provide a lower barrier to entry, however are capped by a paywall once you reach their free tier limit. 

Projectable is a lightweight, project management application that helps teams of any size and type collaborate and track the progress of their work. Projectable is a free, open source alternative that puts user experience first. 

**Features/Functionality:**

- Register and Login via firebase authentication 
- Toggle light and dark mode 
- Track progress of tasks and projects on the dashboard home screen. 
- A calendar view tracks task due dates
- Create and manage projects
- Create and manage project tasks
- Collaborate by adding team members to projects 
- Provide feedback to team members through comments 
- Assign tasks to members 
- Assign priority to tasks

**Target Audience**

The app is intended for Project Managers, teams and individuals wanting to manage projects of all scales 

## Tech Stack

**Frontend**

- React
- Tailwind

**Backend**

- Express
- Node.js
- MongoDB

**Third-Party Services**

- MongoDB Atlas 
- Firebase Authentication

## User Stories 
As Max, A Project Manager, I’m currently lacking visibility across all my projects. I would like a tool that allows me to plan and manage all of my team’s projects in one place, so that I know how many projects I have, what each includes and when each is happening. 

As Joe, A Project Manager, I want to be able to create tasks for a project, So my team can easily visualize all the requirements necessary to complete a project.

As Emma, A Frontend Developer, During a project, plans and requirements often change to meet the client needs, I want to be able to update and delete tasks to reflect the current state of the project. 

As Michael, A Frontend Developer on a team, when working on a project I want to be able to view a task’s priority status, so I know what tickets will make the most impact with achieving the project goals. 

As Jane, a Backend Developer, I’m often working across multiple projects with multiple teams. I want to receive notifications in a central location, when someone comments on a project task that’s assigned to me. 

As Sarah, A Product Manager, When working on a project,  I want to be able to track each team member's workload by how many tasks are assigned to an individual, so I can gauge each team member’s work capacity. 

As Lisa, A freelance Web Developer, I want to be able to set due dates for projects, so I can manage my workload and stay on track with client requests. 

As George, a UX/UI Designer, I want to be able to comment on project tasks that are assigned to fellow team members, so I can know how a task is progressing and provide feedback to the developers on my team. 

## Application Architecture Diagram
![application-architecture](./diagrams/App%20Architecture%20Diagram.png)

## Wireframes

## Sign Up / Log In
![sign-up](./wireframes/sign-up-page.png)
![sign-in](./wireframes/login-page.png)
## Dashboard Views
![dashboard-notifications](./wireframes/dashboard-notifications.png)
![dashboard-projects](./wireframes/dashboard-projects.png)
![dashboard-tasks](./wireframes/dashboard-tasks.png)
![dashboard-calendar](./wireframes/dashboard-calendar.png)
![dashboard-settings](./wireframes/dashboard-settings.png)
## Project Views
![project-unassigned-tasks](./wireframes/project-view-unassigned-tasks.png)
![project-completed-tasks](./wireframes/project-view-completed-tasks.png)
![project-members](./wireframes/project-view-members.png)
##  View Task Modal
![task-modal](./wireframes/task-modal.png)
## View Members Modal
![members-modal](./wireframes/member-modal.png)
## Reference List
Prossack, A 2021, 5 Statistics Employers Need To Know About The Remote Workforce, Forbes, viewed 25 October 2022, <https://www.forbes.com/sites/ashiraprossack1/2021/02/10/5-statistics-employers-need-to-know-about-the-remote-workforce/?sh=733a65fb655d>.

TeamStage 2020, 31 Pivotal Project Management Statistics for 2021, TeamStage, viewed 25 October 2022, <https://teamstage.io/project-management-statistics/>.


 
