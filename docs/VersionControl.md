## Source Code Version Control Tools
This document discusses the aspects and characteristics of the Version Control System that is used for the Flutter application development source code and related files found in this repository.

### :radio_button: Introduction
In software development, version control, also known as source control, is a component of software configuration management. Version control tools are systems that are in charge of managing changes to things such as computer programs, documents, large websites, and source code. 

In this project, version control plays a large role in maintaining the integrity, history, and collaboration aspects of the project. As team members collaborate on the project and share pieces of code, version control allows for them to manage changes, easily track updates, and be up to date with the contributions of different members. Sound version control can ensure that team members are able to collaborate on the project smoothly and not have to worry about running into issues when they attempt to share / work with changing code.

### :radio_button: Version Control System Used

For this project, the chosen version control system is Git, which is a DevOps tool that is used for source code management. Git is the chosen VCS due to its ability to ensure easy collaboration and provide distributed development. The following are features of Git that make it a desirable resource for this project:

:heavy_check_mark: Every developer has an entire copy of the code on their local system

:heavy_check_mark: All changes to the source code can be tracked by others

:heavy_check_mark: Git provides regular communication between the developers

These are just a few of the benefits that Git provides. For more information on Git and its features, you can visit this website: https://www.simplilearn.com/tutorials/git-tutorial/what-is-git

Additionally, Github is used to maintain the source code for the project. GitHub is a Git repository hosting service that provides a web-based graphical interface. The following are features of Git that make it a desirable resource for this project:

1. Easy Project Management
2. Increased Safety With Packages
3. Effective Team Management
4. Improved Code Writing
5. Increased Code Safety

These are a just a few of the many benefits of Github. For more information on GitHub, view this website: https://www.simplilearn.com/tutorials/git-tutorial/what-is-github
  
### :radio_button: Repository Setup
#### :white_check_mark: Structure
My repository is divided into four main sub-directories within my main directory: dev container, Apps, Documentation, and GitHub. The design of my repository follows Flutter's best practices closely so that the navigation of the project is easy.

#### :white_check_mark: Outline
The following is a summary of my repository directories and the purposes that they serve, respectively:

- `/dev container`: This directory is home to the recommended development environment configuration files. team members can reference this directory to make sure the environment they are using is consistent with the environment others are using.

- `/docs`: This directory includes all of the files that relate to my project documentation. These documents hold information that relates to the setup, design, and other important features regarding the nature of my project. 

- `/app`: This directory is where all of the Flutter application source code is stored.
  
- `/GitHub/workflows`: This folder includes the GitHub Actions definition files that define the continuous integration and delivery pipeline.

#### :white_check_mark: Integration
The repository in GitHub is integrated with the DevContainer as well as the CI/CD pipeline. Due to this integration, all pushes result in automated tests and builds which ensures continuous integration and delivery. 

#### :radio_button: Standards and Conventions
To ensure that changes to our project are easy to track, follow, and understand, the following conventions have been used. 

- When updating or making a change to a file, a short but clear note of what update was made is expected in the commit message: `git commit -m "Commit message"`.
- Related files are grouped together in repository folders; these folders have understandable names that are straightforward and accurately describe what feature they pertain to and/or purpose they serve.
- Titles of documentation files clearly state what section of the documentation they refer to.
- The names of branches should clearly reference what issue the developer is intending to work on, update, fix, or change.

### :radio_button: Common Commands and Usage
The following include some of the common Git commands that are needed for our project workflow:

- `git clone <Repository-url>`: Clones the repository to your local machine.
- `git branch <branch-name>`: Creates a new branch.
- `git checkout <branch-name>`: Switches to a specified branch.
- `git add .`: Stages all changes for commit.
- `git commit -m "Commit message"`: Commits the staged changes with a descriptive message.
- `git push origin <branch-name>`: Pushes the commits to the remote repository.
- `git merge <branch-name>`: Merges the specified branch into the current branch.
- `git pull`: Updates the local repository to the latest changes from the remote.

### :radio_button: Collaboration Features
GitHub provides numerous opportunities for easy collaboration amongst team members. Through the following actions, team members can discuss changes to code, deliberate solutions, distribute workloads, and so much more:

- Pull Requests: Team members can use a pull request to tell others about the changes they want to make and ask for their feedback. Once a pull request is opened, members can discuss and review the potential changes and add more changes if needed. 
- Code Review: On GitHub, members of the team can request other team members to review their code and provide feedback or extend their approval.
- Forking: Forking a repository allows a team member to copy an entire project and freely experiment with changes without affecting the original project.
- Branching: Members can use branches on GitHub to isolate work that they do not want merged into the final project just yet. Branches allow users to develop features, fix bugs, or safely experiment with new ideas in a contained area of their repository.

Descriptions on the features above along with other available ones can be found in the README file found in this repositiory: https://github.com/CSC-480-F2023/csc-480-philomina-1

### :radio_button: Challenges and Solutions
While using Git and github for Version Control, no major challenges arose.

### :clock230: Conclusion
In conclusion, Version Control is very important when it comes to software development projects. It allows team members to work together efficiently on a project by helping to manage changes to the source code. Version Control systems, such as Git- the VCS we are utilizing for this project- ensure that the process of developing a software project is a comfortable process the entire way through, leading to a finsihed product that is complete and of high quality.
