# Reference-Page
*#slip1: create a simple project using any programming language and perform some operation on the project using git.Make your project as a git repository add your file staging area and commit changes with a descriptive message
1.mkdir my-python-project
2.cd my-python-project
3.touch main.py
4.notepad main.py
# main.py file contains the code
print("Hello, Git!")
5.git init
6.git add main.py
7.git status
8.git commit -m "Devops"
9.notepad main.py
##(open file again to add code)
# main.py
print("Hello, Git!")
print("Changes committed to Git.")
10.git add main.py
11.git commit -m "Practical"
12.git status
13.git log
14.git remote add origin https://github.com/your-username/my-python-project.git
15. git push -u origin master

#*slip2: Q.2) create a simple project And push on remote server (like github ) using git. and perform some operation.And displays a chronological history of commits.
1.mkdir my-python-project
2.cd my-python-project
3.touch main.py
4.notepad main.py
# main.py file contains the code
print("Hello, Git!")
5.git init
6.git add main.py
7.git status
8.git commit -m "Devops"
9.notepad main.py
##(open file again to add code)
# main.py
print("Hello, Git!")
print("Changes committed to Git.")
10.git add main.py
11.git commit -m "Practical"
12.git status
13.git log
14.git remote add origin https://github.com/your-username/my-python-project.git
15. git push -u origin master
16. git log
17. git log --oneline
18.git log --graph --oneline

#*slip3:Q.2) Create a simple project, push it to a remote repository on GitHub, and create anew branch. Merge this branch into the main branch and display a chronological history of commits. 
1.mkdir my-python-project
2.cd my-python-project
3.touch main.py
4.notepad main.py
# main.py file contains the code
print("Hello, Git!")
5.git init
6.git status
7.git add main.py
8.git commit -m "Devops"
9.git remote add origin https://github.com/your-username/my-git-project.git
10.git push -u origin master
11.git checkout -b feature-branch
12.notepad main.py
#code to update
print("Feature branch changes")
13.git add main.py
14.git commit -m "Added feature branch changes"
15.git push -u origin feature-branch
16.git checkout master
17.git merge feature-branch
18.git push origin master
19.git log
20.git log --oneline
21.git log --graph --oneline


