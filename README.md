# Git and Github:

# Git Introduction:

-- Git is an widely used and open source platform and it was developed by the Linus torvalds in the year 2005 for managing the linux kernel. It's an distributed version control system used to track changes and manage the source code during the software development.  It helps developers collaborate, manage different versions of code, and roll back to previous states if needed.

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/70773901-260d-48a0-929d-b435da72c0a3" />

-- Allows multiple developers can work together and merge changes easily.
-- Revert to previous versions whenever needed.
-- Develop features seperately and merge them safely.

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/9d925b60-99c1-421c-8afc-cfaa9d7ba694" />




# Create a username and Email:

$git config --global user.name "name"

$git config --global user.email "email"

What is the Init:

-- Init is a (Repo respository storage space where your project files and their history are kept. There are 2 types of repositories in Git:
* Local Repository: A copy of the project on your local machine.
* Remote Repository: A version of the project hosted on a server, often on platforms like GitHub, GitLab, or Bitbucket.

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


