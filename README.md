# Git and Github:

# Git Introduction:

-- Git is an widely used and open source platform and it was developed by the Linus torvalds in the year 2005 for managing the linux kernel. It's an distributed version control system used to track changes and manage the source code during the software development.  It helps developers collaborate, manage different versions of code, and roll back to previous states if needed.

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/70773901-260d-48a0-929d-b435da72c0a3" />

-- Allows multiple developers can work together and merge changes easily.
-- Revert to previous versions whenever needed.
-- Develop features seperately and merge them safely.

# Create a username and Email:

$git config --global user.name "name"

$git config --global user.email "email"

What is the Init:

1. Init:  is a (Repo respository storage space where your project files and their history are kept. There are 2 types of repositories in Git:
* Local Repository: A copy of the project on your local machine.
* Remote Repository: A version of the project hosted on a server, often on platforms like GitHub, GitLab, or Bitbucket.

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/9d925b60-99c1-421c-8afc-cfaa9d7ba694" />

2. Commits:
A commit is a snapshot of your project at a specific point in time. Each commit has a unique identifier (hash) and includes a message describing the changes made. Commits allow you to track and review the history of your project.

<img width="477" height="422" alt="image" src="https://github.com/user-attachments/assets/99f5418e-6dec-4109-960d-94f9573f153f" />\

3.Branches

Branches allow developers to work on separate tasks without affecting the main codebase. Common branch types include:

* Main (or Master) Branch: The stable version of the project, usually production-ready.
* Feature Branch: Used for developing new features or bug fixes.

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/b65f63bb-78e2-4717-8a8d-c487e6acfa41" />

4. Merging
Merging is the process of integrating changes from one branch into another. It allows you to combine the work done in different branches and resolve any conflicts that arise.

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/6c3c2366-d706-4e9e-bc00-985c04943abd" />

5. Cloning

Cloning a repository means creating a local copy of a remote repository. This copy includes all files, branches, and commit history.

<img width="738" height="145" alt="image" src="https://github.com/user-attachments/assets/09206bf0-d356-4ebc-a458-57c92b10f789" />

6. Pull and Push

Pull: Fetches updates from the remote repository and integrates them into your local repository.
Push: Sends your local changes to the remote repository, making them available to others.

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/c7b24f7f-f5cf-4753-94f4-c1101edd9fd5" />

Git Workflow

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/5f35409d-b586-4d92-8393-e81469607d05" />

# Commands:

# when you run this command, it's create a sub directory under the main directory,
                                   <git init>

# .git- inside of this branches, configurations, hooks, objects, refs.

# Display the state of the working directory

                                    <git status>

 # to add all current changes (both modified and new files)to the staging area.
                                       git add

                                     git add <file name>

# git commit -m "message"- will commit the staging area to local repo--  It Is a Snapshot of our Project.

                                     git commit -m "Message"

# git push- push the changes from local to remote repo
                                     
                                     git push -u origin >branch name>

# git log- to check the history

                                    # <git log>
  
# How To Clone The Repo from Github to Local

                                      # <git clone <Repo URL>


