############ How to use git ##########
1) Make Repository in GitHub 
2) Go to https://git-scm.com/ and download git as per your platform 
3) Install GIT 
4) Check Git Version - 
   $> git --version
5) Clone GitHub repository to your local machine 
   $> git clone URL_OF_Repositary
6) Copy your Project directory in repository directory
7) Open Terminal,Change the current working directory to your local repository directory.  
8) $> git add .
9) $> git commit -m "Your comment here"
10)$> git push URL_OF_Repositary



########Multiple GitHub HTTPS accounts on Windows#########

1) remove your current GitHub credentials from Windows Credential Manager
Go to Windows Credential Manager, open the Windows Credentials tab, locate git:https://github.com, open the entry, and click Remove.

2) tell Windows to store different accounts for each of your GitHub repos
git config --global credential.github.com.useHttpPath true

3) provide your username, password once again for each repo when you are prompted for your credentials - this is the last time you need to do that


https://github.com/anirudhagaikwad
