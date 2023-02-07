This project will center on designing and implementing an organisation with a software system which provides;
integration with organisation databases
reports on geographical demographics

Our Approach
To achieve the desired reports, our team will focus on the creating the desired software via the following steps:

Understanding the SQL database structure and contents.
Analyzing the report requirements and breaking them down into smaller, manageable tasks.
Developing a plan for organizing and delegating tasks among team members.
Implementing the report generation functionality and testing it against the requirements.
Refining and debugging the solution as needed, utilising develop, release and master branches.

Individual Contributions
Our individual contributions will be assessed by our peers, taking into account factors such as attendance at meetings, quality of code, and metrics from tools such as GitHub. In the event that individual contributions require scaling, our team is aware that this will be taken into account in the overall coursework grade.

Gitflow Workflow

![image](https://user-images.githubusercontent.com/121656622/217247938-de564c31-0d16-4ade-baeb-f2d49aa6e008.png)

Our Gitflow workflow consists of three main branches: master, develop, and release.

The master branch represents the production-ready code and contains only the latest, stable releases of the software.

The develop branch is where all the new features and bug fixes are added and integrated into the code. This is the main branch for active development and is constantly updated as new changes are made.

The release branch is created from the develop branch and is used to prepare a new release of the software. This branch includes the necessary bug fixes, changes, and testing before the software is finally merged into the master branch and released. Once a release is completed, the release branch is deleted, and the cycle starts over with a new release branch created from the updated develop branch.

Database
The provided SQL database will serve as the foundation for our population reporting system. Our team will take the time to familiarize ourselves with the database structure and contents to ensure that our solution is effective and efficient.

Communication
A private discord server has been established for the SCRUM team members to communicate in a focal environment with the necessary security protocols for discussing software architechture in a way which can be truly transparent.

Architecture
Java version 11 - to ensure all team members are running a sychronised version compatible with team software and hardware facilities
MySql - A sql server which will run the provided SQL database and will be shared amongst the team
Git - Version Control for the team to conribute to the project collaboratively and on a non-local basis
GitHub - To host the git project
Docker - To run both the SQL server and the Java project in a containerised environment with universally assigned toolkits and dependencies
Intellij IDEA Community - An Easy to use IDE with streamlined Git Version Control and Java oriented features
Ubuntu - The operating system used to host the project, favoured for the developer-favoured bash terminal, free license, open-source nature offering extensibility between systems and Docker containers
