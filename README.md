# nbdev - Part 2
> Resolving merge conflicts

In today's class, we'll work to resolve some merge conflicts. The goal here is to fill in the answers to the 

# Setup
## Team leads
1. Create a repository using this repo as a template. Make sure to create it in the dsi-teams-spring2022 organization.
2. Invite all of your team members to your repository with write access.
3. Send the address of your repo in your Team slack channel to your members.
3. Designate (in Slack or otherwise) your team members as Person 1, Person 2, Person 3, or Person 4. If you have a 3-person team, either you can be Person 4 or Persons 1, 2, and 3 will all perform the same activities below. Tell your team members in Slack what their number is.

## Answering questions
Now, we'll clone the repo and start answering questions.
1. All team members: accept the invite by visiting the link your Team Lead has sent you.
2. Clone the repo to your computer. Remember that since we're using nbdev, you'll need to use your virtual environment.
3. Start an instance of Jupyter notebook or Jupyter lab.

### Part 1: Person 1 and Person 3 fix merge conflict
Remember we'll be using the GH Flow to add code to the code base. So:
1. Create a new branch for your work

Persons 1 and 2 - you'll answer both questions 1 and 2 in the Virtual Environment section (each person should answer both questions)  
Persons 3 and 4 - you'll answer both questions 1 and 2 in the nbdev section (each person should answer both questions)  
Answer your questions in new markdown cells created under your your designated questions.  

After answering your questions:
1. Save the notebook
2. Go to the terminal. Clean your notebooks (`nbdev_clean_nbs`)
3. Add and commit your work.
4. Push your branch.
5. Create a pull request.
6. Persons 1 and 3: Go to Person 2 and 4's pull requests, respectively. Merge them in.
7. Persons 2 and 4: Review Persons 1 and 3's pull requests, respectively. Approve them to signal that they should merge in their PRs.

As you can see, there's a merge conflict that should be resolved prior to merging.

Persons 1 and 3:
1. Go back to your terminal
2. Switch back to your master branch (`git checkout master`)
3. Execute a pull (`git pull`)
4. Switch to the branch you're trying to merge in
5. Try to merge master into it `git merge master`
6. Notice what happens. Type `git status` to see the behavior.
7. Try to open the conflicted notebook. Oh no!
8. Use nbdev to help you. Type `nbdev_fix_merge 00_orientation.ipynb`.
9. Notice the new .bak file created. Open your notebook.
10. Fix the notebook to your liking, removing the merge conflict symbols.
11. Save your notebook.
12. Switch back to the command line. Type `git status`.
13. You're still merging. Type `git add 00_orientation.ipynb`
14. Commit these changes
15. Push your newly merged branch back to GitHub.
16. Refresh your pull request page. Inspect the merge conflict section.
17. Merge your branch.
18. Delete the branch.

Yay! In Part 2, we'll flip these roles.

### Part 2: Person 2 and Person 4 fix merge conflict
Remember we'll be using the GH Flow to add code to the code base. So:
1. Create a new branch for your work

Persons 1 and 2 - you'll answer both questions 3 and 4 in the Virtual Environment section (each person should answer both questions)  
Persons 3 and 4 - you'll answer both questions 3 and 4 in the nbdev section (each person should answer both questions)  
Answer your questions in new markdown cells created under your your designated questions.  

After answering your questions:
1. Save the notebook
2. Go to the terminal. Clean your notebooks (`nbdev_clean_nbs`)
3. Add and commit your work.
4. Push your branch.
5. Create a pull request.
6. Persons 2 and 4: Review Persons 1 and 3's pull requests, respectively. Merge them in.
7. Persons 1 and 3: Go to Person 2 and 4's pull requests, respectively. Approve them to signal that they should merge in their PRs.


As you can see, there's a merge conflict that should be resolved prior to merging.

Persons 2 and 4:
1. Go back to your terminal
2. Switch back to your master branch (`git checkout master`)
3. Execute a pull (`git pull`)
4. Switch to the branch you're trying to merge in
5. Try to merge master into it `git merge master`
6. Notice what happens. Type `git status` to see the behavior.
7. Try to open the conflicted notebook. Oh no!
8. Use nbdev to help you. Type `nbdev_fix_merge 00_orientation.ipynb`.
9. Notice the new .bak file created. Open your notebook.
10. Fix the notebook to your liking, removing the merge conflict symbols.
11. Save your notebook.
12. Switch back to the command line. Type `git status`.
13. You're still merging. Type `git add 00_orientation.ipynb`
14. Commit these changes
15. Push your newly merged branch back to GitHub.
16. Refresh your pull request page. Inspect the merge conflict section.
17. Merge your branch.
18. Delete the branch.

Yay!












