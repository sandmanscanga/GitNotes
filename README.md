
# GitNotes

1.  To **show the current status** of the git working environment, showing staged files, behind or ahead commits, and which branch you are working on...  You can use the following command: `git status`

2.  If you decide you want to change code, you should **create a new branch** (assuming that you have the most up to date versioning of your project) with the following command: `git branch YOUR_BRANCH_NAME`

3.  To **check all created branches**, you can use the following command: `git branch -a`

4.  To **switch to an available branch**, you can use the following command: `git checkout YOUR_BRANCH_NAME`

5.  At this point you have a new feature that you want to add to your project...  You created and switched to your new branch...  Now, you can add whatever code you want to your project on your **LOCAL**.

6.  To check *unstaged changes* in your project, you can run the following command: `git diff`

7.  Now we have the code that we want to add to our project written and we want to have `git` tracking the changes, because right now `git` is not tracking...  To track unstaged files or changes, you can run the following command: `git add NAME_OF_CHANGED_FILE`

8.  Tracked files or changes that you would like to commit to your *LOCAL* git repository, and eventually your *REMOTE* git repository, can be commited with the following command: `git commit -m "This is a message that describes what you just did on this commit, so make sure it is descriptive."`

9.  To show the current commit tree you can run the following command: `git log --oneline --graph`

10.  Now we have code that is comitted to a **feature branch** but the remote git repo does not see any changes at all, YET.

11.  To *inform* the remote git repo of the changes that you make in your **LOCAL git**, you can push your commits up to the **REMOTE git** using the following command: `git push`

12.  Create a merge/pull request on the remote repo to merge the feature branch into the main branch so that it can receive the commits you pushed...

13.  Now your **main** branch is updated with the feature branch code, but if you switch to your **LOCAL** main branch, you will notice that it does not know about the changes...  In order to get the latest changes for any given branch, *from the remote repo (meaning, after you merge)* you can run the folowing command: `git pull`
