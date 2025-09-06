### Answer the following questions in you own words.

> It's not necessary that you havee to know and answer all the questions. Just answer the ones
> you know and write in your own words.

### 1. Give the difference between the remotes - upstream and origin - with an example.

You answer: 
- origin is used when pushing changes to my own repo that is forked and upstream is pushing direct in someones repo. 

### 2. You have two branches A and B and you have currently made some changes in branch A.
You want to move into branch B but do not want to commit the current changes in branch A.
What will you do?

You answer: I dont know exactly

### 3. You were assigned a work to implement a feature and create a PR to your organization's remote repository.
For this you made a branch (say A) and made some changes and commited them. Now you moved to some other branch 
(say B) to do some other assigned work. But later you realisd that have to complete the task assigned earlier 
first and commited some changes in branch B which are meant for branch A. How will you use git to bring the 
changes from branch B to branch A?

You answer: Git rebase is great for these type of situation when we have to move the base of currently working branch on top of another branch.

### 4. What is the difference between fetching changes and pulling changes?

Your answer: Pulling is for making ur current working directory add all the updates it takes from the remote dir , i never used git fetch.

### 5. What does -i flag stand for? What is it's significance in git?

You answer: i dont know.

### 6. You are working in an organization that follows very strict guidelines for PRs and commits.
You made three commits in your PR and the maintainer says you were supposed to make a single commit.
What will you do in this case?

You answer: i dont know

### 7. Explain `git merge` and `git rebase` with example(s).

You answer: git merge , merges two branches 
and also keep their history , as for git rebase it is useful when we have to move the base of currently working branch on top of another branch.
### 8. Write the flow how you create a repository and push changes to it. Also mention the commands used at each step.

You answer:
- first make a repo in github -> Create new Repository button
- fill in all required details and then create it
- copy the clone url
- go to ur editor cli and type these
- git add . 
- git commit -m "ur message"
- git branch -M main
- git remote add origin -add url here-
- git push -u origin main


### 8. How would you prevent a file or folder from getting tracked by git?

Your answer: we can use gitignore , by that git will ignore the fle

### 9. You did not implement the step you mentioned in question 8 and now you have committed and pushed your database's
secret key to the github. How will you remove the key from your git's commit history to avoid any misuse?

You answer: i dont know the command but we can delete the key first , then remove it from the history also to erase its trace

---