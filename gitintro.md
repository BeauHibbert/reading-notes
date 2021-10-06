# Version Control System
* A version control system or VCS, is a way to store files that allows you to access different versions of the same file as it was saved.
* The first VCSs were just local VCS that stored files on your local hard drive. This allowed developers to see previous file saves but it made it hard for a group of developers to collaborate unless they were together.
* Another weak point of this system was that it had one point of failure, or in other words, it was only saved to the local VCS which meant if your computer broke or it was corrupted then there was no way to get back the files that were saved.

# Centralized Version Control System
* A centralized version control system or CVCS was the answer for a group of developers to collaborate without having to be together. Again, there was still one point of failure in this system if the server went down then nobody could continue working on the project.

# Distributed Version control System
* Distributed Version Control System is the answer to the main problem of a CVCS. Each time a change to a file is made it takes a snapshot of the new file and it is saved to Git(Git is a very popular DVCS).

# How it works
1. A repository is cloned from Git into the terminal.
2. Type 'git status' into the terminal. This displays the status of the files in your local directory.
3. Type 'git add <some-file>' (or 'git add .' to include all directory files), which tells git that you want to include these files in your snapshot.
4. Type 'git commit -m"message" and Git will take a snapshot of the current work and allows you to add a comment or message about the change.
5. Finally, type 'git push origin main' and the terminal and git should sync up and both have the latest snapshot version saved.
