#Discovery Web Piscine - Project 00
##Overview
This project is an introduction to basic Unix shell commands, file management, Git, GitHub, and SSH authentication.
The project covers creating and managing files, working with text from the terminal, using Git for version control, and documenting a basic Git workflow.
 
⸻
 
##Exercise 00 — Basic File Operations
The first exercise focuses on basic file and directory management using the Unix terminal.
The main commands used include:
touch
mkdir
ls
cp
mv
rm
These commands are used to create, list, copy, move, rename, and remove files and directories.
 
⸻
 
##Exercise 01 — Shell Commands and Text Manipulation
The second exercise focuses on creating files, writing text, and viewing file contents from the terminal.
The main commands and operators used include:
>
>>
cat
less
The > operator is used to create a file or overwrite its existing content, while >> is used to append content to a file.
The cat and less commands are used to read and inspect file contents.
 
⸻
 
##Exercise 02 — Git and GitHub
The third exercise introduces Git and GitHub.
The main steps include:
1. Initialize a local Git repository:
2. Add files to the staging area:
3. Create a commit:
4. Connect the local repository to GitHub:
5. Push the project to GitHub:
git push -u origin main
The submitted files include:
repo_url.txt
git_log.txt
 
⸻
 
##Exercise 03 — Project & README
The final exercise focuses on professional documentation and secure authentication.
The required files are:
README.md
git_workflow.txt
• id_ed25519_pub.txt — Bonus
The README documents the project and explains the Git workflow used during development.
 
⸻
 
##Why Git Makes Development Easier
Git makes development easier because it keeps track of changes made to a project over time.
If a mistake is made, Git allows developers to look at previous versions and recover their work instead of losing it.
Git also makes it easier to work on projects with other developers because each person can work on their own changes and later combine them with the rest of the project.
Overall, Git provides a clear history of the project and helps organize and manage changes safely.
 
⸻
 
##Git Workflow
The basic Git workflow used in this project is:
1. Edit
Create or modify files in the project directory.
2. Add
Stage the changes using:
git add <file>
or:
git add .
3. Commit
Save the staged changes with a descriptive commit message:
git commit -m "Describe your changes"
4. Push
Upload the committed changes to the GitHub repository:
git push
The complete workflow is:
Edit → Add → Commit → Push
 
⸻
 
##SSH Authentication
As a bonus, an ED25519 SSH key pair can be used to authenticate with GitHub securely.
The key pair consists of:
• A public key that can be added to GitHub.
• A private key that must remain secret and must never be submitted or uploaded.
The public key can be saved in:
id_ed25519_pub.txt
The private key must remain strictly private.
After configuring the SSH key with GitHub, the remote repository URL can be changed from HTTPS to SSH:
git@github.com:username/repository.git
This allows Git operations such as git push to be performed using SSH authentication without entering a GitHub password.
 
⸻
 
##Security Note
Never commit or submit the private SSH key.
Only the public key should be shared with GitHub or submitted for the bonus requirement.
 
⸻
 
##Tools Used
• Unix/Linux Terminal
• Git
• GitHub
• SSH
• Markdown
