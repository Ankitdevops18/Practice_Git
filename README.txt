   ASSIGNMENT 1 :  - 
   
    
   Tasks To Be Performed:

1. Based on what you have learnt in the class, do the following steps:

        a. Create a new folder

        b. Put the following files in the folder

        ● Code.txt

            ● Log.txt

            ● Output.txt

        c. Stage the Code.txt and Output.txt files

        d. Commit them

        e. And finally push them to GitHub

2. Please share the commands for the above points

   
   Solution:


a.   Create a new folder : 

		mkdir Git_Practice

b.  Put the files in the folder
        touch Code.txt
        touch Log.txt
        touch Output.txt
c.   Stage the Code.txt and Output.txt files
        git add Code.txt
     	git add Output.txt

d.  Commit them 
        git commit -m "First Commit | 2 Files: Code.txt & Output.txt"
e.  And finally push them to GitHub
        git remote add origin https://github.com/Ankitdevops18/Practice_Git.git
     	git push -u origin main






Command history : 



   
   38  mkdir Git_Practice
   39  cd Git_Practice
   40  clear
   41  touch Code.txt
   42  touch Log.txt
   43  touch Output.txt
   44  git init
   45  ls -lrt
   46  git status
   47  git add Code.txt
   48  git add Output.txt
   49  git status
   50  git commit -m "First Commit | 2 Files: Code.txt & Output.txt"
   51  git branch
   52  git branch -M main
   53  git remote add origin https://github.com/Ankitdevops18/Practice_Git.git
   54  git push -u origin main






   57  ssh-keygen           #Create SSH Keygen
   58  cd /Users/Ankit
   59  ls-lrta
   60  ls -lrta
   61  cd .ssh
   62  ls -lrta
   63  cat id_rsa.pub       #Copied public RSA from here & pasted on New SSH Key from Github>Settings>SSH key 
   64  cd ~Desktop
   65  cd ../../
   66  ls -lrt
   67  cd Ankit
   68  ls -lrt
   69  cd Desktop
   70  ls -lrt
   71  cd Git_Practice
   72  ls -lrt
   73  git remote add ssh-origin git@github.com:Ankitdevops18/Practice_Git.git      #Added a new remote Name - ssh-origin
   74  git remote -v
   75  ssh -T git@github.com        # Testing SSH connectivity with Github
   76  git add Log.txt
   77  ls -lrt
   78  git status
   79  git rm --cachedLog.txt       #removed file from staging
   80  git rm --cached Log.txt
   81  git status
   82  touch sshtest.txt
   83  git add sshtest.txt
   84  git status
   85  git commit -m "test ssh"
   86  git push -u ssh-origin main
   87  history 50