Commands I used for each question: 
1-a:
git init task-manager
cd task-manager

2-b: 
git add .
git commit -m "message"

3-a: 
git checkout -b feature/add-tasks

3-b: 
echo "- Practice Git branching" >> tasks.txt
git add .
git commit -m "message"

3-c: 
git checkout master
git checkout -b feature/remove-tasks

3-d:
git add .
git commit -m "message"

4-a: 
git checkout master
git merge feature/add-tasks 
git merge feature/remove-tasks 

5-a: 
git checkout -b feature/update-tasks

5-b:
echo "- Review Git merge and rebase" >> tasks.txt
git add .
git commit -m "message"

5-c: 
git checkout master
git rebase feature/update-tasks 

7-a:
echo "- Some incorrect task" >> tasks.txt
git add tasks.txt
git commit -m "Add incorrect task"

7-b:
git revert HEAD~1

7-c:
git reset --hard HEAD~3

8-a:
git remote add origin <repository-url>
git push
