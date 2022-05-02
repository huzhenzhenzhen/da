# da
learn something about data structure and algorithm

https://www.interviewbit.com/blog/cpp-projects/

------------
how to use git
1. create a folder, then cmd, type "git init" to make this folder a git repositoty
2. get the git hub repository web URL which you want to clone to your local git repository (https://github.com/huzhenzhenzhen/da.git)
3. type "git clone https://github.com/huzhenzhenzhen/da.git", getting the "OpenSSL SSL_read: Connection was reset, erro..."
4. git config --global http.sslVerify "false"
5. type "git clone https://github.com/huzhenzhenzhen/da.git", successfully cloned the github repository

------------
1. check the file status in local repository, using "git status"
2. make change to the file, the "git add filename" or "git add *", then commit the change by using "git commit -m "add 1 line""
3. to push the change to github, use "git push origin main", if you get SSL_read error(password authentication is not supported...)
4. Go to this link: https://github.com/settings/tokens (Profile -> settings -> developers setting -> personal access tokens). (don't go to repository setting; it's your profile setting)
5. Generate a new token and copy-paste it somewhere safely.
6. Go to Credential Manager from Control Panel => Windows Credentials => find git:https://github.com  => Edit => On Password replace with with your GitHub Personal Access Token => You are Done
7. If you don’t find git:https://github.com => Click on Add a generic credential => Internet address will be git:https://github.com and you need to type in your username and password will be your GitHub Personal Access Token => Click Ok and you are done
8. wait..
9. push or pull fails sometimes, i think it was due to the network fluctuation --> git pull
10. to create a new branch and switch to the new branch, "git checkout -b slave_1"
11. update the file, and "git push origin slave_1", the new branch slave_1 will be created in github
12. go back to main branch "git checkout main", "git pull" , or you may need "git push --set-upstream origin slave_1" 
13. 
