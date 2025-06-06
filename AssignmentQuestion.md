# OOP Questions

### 1.	List three major version control software for software engineering.
Git, Apache Subversion, Mercurial 

### 2.	What are the main advantages to using Git in your software development, and how is it useful for game developers.
Git is useful for keeping everyone up to date with every change easily and efficiently.

### 3. Define the following terms in relation to Git. Repository, Branch, Merge, Pull, Push,
- Repository - A collection of information and files, uploaded to GitHub.
- Branch - A separate line of the repository, usually having at least two separate branches for developing and final.
- Merge - To bring the contents of another branch into the current branch.
- Pull - To download changes to the remote repo to your local version.
- Push - To upload local changes to a remote repository.

### 4.	If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git. 
The company's policies revolving data retention and data protection may enforce using version control such as Git to store files. More specifically to the gaming environment, most companies would have policies to ensure you keep all of your work updated and saved on some sort of version control tool.

### 5.	Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts. 
- Visual Studio - Inside visual studio, there are tools to fix merge conflicts involving scripts where you can choose what to keep or delete, and also choose if you need to reset or revert at any point.
- GitHub Desktop - Inside GitHub Desktop are similar tools allowing you to manage the repository and look at all files that have merge conflicts, and allowing you to choose what you need to keep or change.

### 6.	In a merged source code file, how does Git let you know there is a conflict? 
It will show arrows pointing to and separating the two conflicting lines of code.

### 7.	What are the steps you can take to resolve Git conflicts? 
- You can choose to keep or delete the conflicting files depending on what you want 
- You can delete the conflicting lines directly within the file 

### 8.	What does git revert do, and how can you use it? 
"git revert" is used for undoing changes to commit history. It does this making a new commit with changes that inverse the changes that have been specified
If you encounter a problem with your code after your last commit specifically, you can use "git revert" to inverse the last changes.

### 9.	What does git reset do, and how can you use it?
"git reset" is used to change the current head back to a certain commit in the timeline of changes. If you have multiple commits recently that seem to be
affecting the code negatively and you aren't sure where the problems lie, you can use "git reset" to go back multiple commits.

### 10.	What is the difference between git revert and git reset? 
"git revert" is used for inversing changes, and "git reset" is used for going back to before the changes.

### 11.	True or False: It is okay to commit broken code to the main branch. 
- False

### 12.	True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits. 
- True

### 13.	Describe what is DevOps, how is it useful for game developers? 
DevOps is a set of practices that encourage and support communication and teamwork among teams working on a project. It is useful for keeping everybody
up-to-date and keeping a steady, productive workflow. Specifically with game developers, this means communication and efficiency among all separate 
departments.

### 14.	List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
- (Plan) Trello - Trello is an online tool that allows teams to organise and keep track of any task that needs to be done. Each task can be assigned to specific people and overlooked by higher management.
- (Test) Veracode - Veracode is a program that allows organisations to test their code rigorously through multiple different formats and algorithms.
- (Continuous Feedback) Slack - Slack is primarily a communication tool for the organisation themselves, but can also be connected to websites like SurveyMonkey to allow customers to give their feedback to the team.


### 15.	What is CI/CD and how can it be used to automate the game development process? 
CI/CD stands for Continuous Integration and Continuous Delivery. It is useful for games that do nightly builds or are open source. This can be used to automate
the game development process by allowing changes to be "continuously delivered".
