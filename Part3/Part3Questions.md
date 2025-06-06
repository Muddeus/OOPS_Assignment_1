# Git Questions

## Imagine you are working at a game studio, and they want you to help with installing Git. Write instructions on installing git on a windows system. Making sure to include:
### a.	What are the requirements to install Git on a system.
### b.	If you had issues installing Git the workplace, give instructions on who you could you enquire about the installation disruption.

- Make sure you suit the requirements to install Git. (An internet connection, administrator privileges on this device, and for this guide, 
a generally up to date Windows operating system.)
- Go to the [Git for Windows installer page](https://gitforwindows.org/) and locate the latest version to install.
- Open and follow the git setup instructions once installed.
- Open command prompt (or Git Bash if you chose to install that) and type ``` git version ``` to check if it installed correctly.
- You should now be able to open GitHub Desktop and log in to your Git account inside the program.
- __If any problems occur during any of these steps, submit a ticket to your I.T helpdesk, or contact your I.T support in the way you have been instructed in your work place.__


## Do research on some principles/techniques of industry standard best practices creating and working with repositories and branches in Git. 
### a.	List the most important principles/techniques for creating and working with repositories
- Creating a succinct README file to direct any visitors to the repository.
- Using correct naming conventions for all branches, updates, pull requests and files.
- Commiting frequently with descriptive update titles.
### b.	List the most important principles/techniques for creating and working with branches
- Creating multiple branches or forks to keep all work separate, to avoid merge conflicts.
- Working in a separate branch to staging and main.

## List the steps in a Git workflow that the team should follow when working on projects.
##### If this is the beginning of the project start here
- Ensure you have Git installed on your computer and are logged in.
- Clone the main project repository locally.
##### After the steps above have been completed
- Switch to the Development branch or a specific branch you have been told to use.
- After making your changes, commit them with a descriptive title to the development branch.
- Push your committed changes to the branch and check if everything has uploaded correctly.
- After verifying all commits have been succesful, merge your changes into the staging branch.
- Once again verify the success of commits, and move them to the main branch.
