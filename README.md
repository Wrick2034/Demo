# Demo
Steps to take when working with a git repository on Git Bash :<br />
1. If not cloned, use "git clone 'repo url'.git" to for a copy in the local computer<br />
2. After that if not configured, cofigure globally so we don't have to do it again unless we change something locally with "git config --global user.name 'user-name'" and other things like name and email id similarly.<br />
3. Make changes in the file using the vi text editor<br />
4. Then add the changes using the "git add ."<br />
5. Then commit them using "git commit -m "Any comment""<br />
6. Finally push the commited changes to the repository using "git push"<br />
7. If someone has mage any changes in the git file, first pull with "git pull master main". Here master is the remote repo name while main the branch on which we are working.
