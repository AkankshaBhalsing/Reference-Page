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

#*slip4.Create a simple project and use Git commands to check the status, view log history, see differences between the working directory and the last commit, make a commit and display a
chronological history of commits. 
 # Step 1: Set Up a New Git Repository

mkdir my-simple-project
cd my-simple-project
git init

# Step 2: Create a Simple File
echo "<h1>Hello, Git!</h1>" > index.html
git status

# Step 3: Add the File to the Staging Area
git add index.html
git status

# Step 4: Make Your First Commit
git commit -m "Initial commit: Added index.html"
git log

# Step 5: Make Some Changes to the File
echo "<p>This is a simple Git project.</p>" >> index.html
git status
git diff

# Step 6: Stage and Commit the Changes
git add index.html
git commit -m "Updated index.html with a new paragraph"
git log

# Step 7: Display a Compact Log History
git log --oneline
git log --graph --oneline --all

# Step 8: Check Status and Differences
git status
git diff

# Step 9: View the Commit History with Details
git log -p

# Step 10: Bonus Commands for Branching
git branch
git checkout -b new-feature
git checkout main

##bitbucket Create a simple project, push it to a remote repository on BitBucket, and create a
new branch. Merge this branch into the main branch and display a chronological
history of commits.
# Step 2: Set Up a New Git Repository Locally
cd path/to/your/directory
mkdir my-simple-project
cd my-simple-project
git init

# Step 3: Create a Simple File
echo "# My Simple Project" > README.md
git status
git add README.md
git commit -m "Initial commit: Added README.md"

# Step 4: Push the Project to Bitbucket
git remote add origin https://YOUR_USERNAME@bitbucket.org/YOUR_USERNAME/YOUR_REPO_NAME.git
git branch -M main
git push -u origin main

# Step 5: Create a New Branch
git checkout -b feature-branch
echo "This is a feature update." >> README.md
git status
git add README.md
git commit -m "Added a feature update"
git push -u origin feature-branch

# Step 6: Merge the Branch into Main
git checkout main
git pull origin main
git merge feature-branch
git push origin main

# Step 7: View the Commit History
git log --oneline
git log --graph --oneline --all

# Step 8: Clean Up (Optional)
git branch -d feature-branch
git push origin --delete feature-branch


#### Maven
# Step 3: Import the Maven Project
Go to File > Import.
Select Maven > Existing Maven Projects and click Next.
Click Browse to select the root directory of your extracted project.
Ensure the pom.xml file is detected and click Finish.
# Step 4: Update Maven Project
Right-click on the imported project in the Project Explorer.
Select Maven > Update Project.
Check the box for Force Update of Snapshots/Releases and click OK.
# Step 5: Run the Spring Boot Application
Right-click on the main class (the one with @SpringBootApplication annotation).
Select Run As > Spring Boot App (or Java Application if you don't have the Spring Boot option).
# Step 6: Access the Application
Open your browser and navigate to http://localhost:8080 (or the configured port) to see the running application.
6. Troubleshooting Common Issues
Missing Dependencies: If Eclipse shows errors about missing dependencies, run:
bash
Copy code
mvn clean install
Port Conflicts: If you get a port already in use error, change the port in application.properties:
properties
Copy code
server.port=8081


