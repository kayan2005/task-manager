Git Commands Explanation

1\. Initialize a Git Repository

•	mkdir task-manager

•	cd task-manager

•	git init

2\. Add and Commit Tasks

•	touch tasks.txt

•	echo " - Learn git basics " >> tasks.txt

•	echo " - Set up git repository " >> tasks.txt

•	git add tasks.txt

•	git commit -m "add tasks.txt"

3\. Create and Switch to Branch

•	git checkout -b feature/add-tasks

•	echo " - Practice Git branching " >> tasks.txt

•	git add tasks.txt

•	git commit -m "Practice Git branching"

4\. Merge Branches and Handle Conflict

•	git checkout master

•	git checkout -b feature/remove-tasks

•	notepad tasks.txt 

•	git add tasks.txt

•	git commit -m "Remove task"

•	git checkout master

•	git merge feature/add-tasks

•	git merge feature/remove-tasks 

•	git add tasks.txt

•	git commit -m "merge"

5\. Use Git Rebase

•	git checkout -b feature/update-tasks

•	echo " - Review Git merge and rebase" >> tasks.txt

•	git add tasks.txt

•	git commit -m "Review Git merge and rebase"

•	git checkout master

•	git rebase feature/update-tasks

6\. Revert a Commit

•	echo "- Some incorrect task" >> tasks.txt

•	git add tasks.txt

•	git commit -m "Add incorrect task"

•	git log --oneline 

•	git revert <commit-id>

7\. Connect to Remote Repository and Push

•	git remote add origin https://github.com/your-username/task-manager.git

•	git push -u origin master

8\. Final Push

•	git add .

•	git commit -m "done"

•	git push



