## Source Code Version Control Tools
This document discusses aspects and characteristics of the Version Control utilized for the Flutter application development. source code and related files.

### Introduction
In software development, version control, also known as source control, is a component of software configuration management. Version control tools are systems that are in charge of managing changes to things like computer programs, documents, large websites, and source code. 

In this project, version control plays a large role in maintaining the integrity, history, and collaboration aspects of the project. As team members collaborate on the project and share pieces of code, version control allows for the software team to manage changes, easily track updates, and be up to date with the contributions of different members. This can ensure that team members can work together smoothly and limit complications that may arise.

### Version Control System Used

For this project, the chosen version control system is Git. I am using Git because it is extremely efficient. The following are features of Git:
- feature 1
- feature 2
- feature 3
- feature 4

For more information on Git, you can visit their website: 

Additionally, I am using Github because of 

For more information on GitHub, see this website: 
  
### Repository Setup
#### Structure
My repository is divided into four main sub-directories within my main directory. The design of my repository follows Flutter's best practices closely so that the navigation of the project is easy and efficient.

#### Outline
The following is a summary of my repository directories and the purpose that they serve:

- `/dev container`: This directory is home to the recommended development environment configuration files. team members can reference this directory to make sure the environment they are using is consistent with the environment others are using.

- `/docs`: This directory includes all of the files that relate to my project documentation. These are documents that relate to the setup, design, and other important information regarding the nature of my project. 

- `/app`: This directory is where all of the Flutter application source code is stored. Keeping the application code away from non-app-related files.

- `/.github/workflows`: This folder includes the automated GitHub Actions definition files. These files define our continuous integration and delivery pipeline, automating tests, builds, and deployments based on predefined events and conditions.


#### Integration
The repository in GitHub is integrated with our DevContainer and CI/CD pipeline. This means that every push triggers automated tests and builds which ensures  continuous integration and delivery. 

This setup supports our agile development practices and enhances code quality.

#### Standards and Conventions
To ensure that changes to our project are easy to track, follow, and understand, some conventions have been adopted. 
- When updating or making a change to a file, a short but clear note of what update was made is expected in the commit message.
- Related files are grouped together in repository folders, all of which have understandable names that are straightforward and accurately describe what feature they pertain to.
- Titles of documentation files clearly state what section of the documentation that file refers to.
- the names of branches should clearly address what issue the developer is intended to work on, update, fix, or change.

### Common Commands and Usage
The following include some of the most common Git commands that are needed for our project workflow:

- `git clone <repository-url>`: Clones the repository to your local machine.
- `git branch <branch-name>`: Creates a new branch.
- `git checkout <branch-name>`: Switches to a specified branch.
- `git add .`: Stages all changes for commit.
- `git commit -m "Commit message"`: Commits the staged changes with a descriptive message.
- `git push origin <branch-name>`: Pushes the commits to the remote repository.
- `git merge <branch-name>`: Merges the specified branch into the current branch.
- `git pull`: Updates the local repository to the latest changes from the remote.

### Collaboration Features
GitHub provides numerous opportunities for easy collaboration amongst team members. Through the following actions, team members can discuss changes to code, deliberate solutions, distribute workloads, and so much more:
- pull request
- code review
- fork
- branch


### Challenges and Solutions

### Conclusion

In conclusion, Version Control is very important. It allows team members to work together efficiently and manage their code.
This ensures for a project that is a comfortable process all the way through. 
