# DevOps TP


$ git switch main
Switched to branch 'main'
Your branch and 'origin/main' have diverged,
and have 1 and 2 different commits each, respectively.
  (use "git pull" if you want to integrate the remote branch with yours)
pot@pot-Vostro:~/Documents/code_projects/devops_tp_clone/devops$ git log --oneline --graph
* d6e03e6 (HEAD -> main, tag: v1.0.0) Revert "Modified login feature"
* 7f887fd Modified login feature
*   20e0968 Fix merge conflicts between login and main
|\  
| * 48420f2 Login feature
| * ee935f4 Creating the main file
* | 64b4209  Main file added
|/  
* 9de4d99 gitignore added
* 9d91f75 Initial commit


$ git switch feature/cloner
Switched to branch 'feature/cloner'
Your branch is ahead of 'origin/feature/cloner' by 1 commit.
  (use "git push" to publish your local commits)
pot@pot-Vostro:~/Documents/code_projects/devops_tp_clone/devops$ git log --oneline --graph
* 518bfba (HEAD -> feature/cloner) Saving the popupd stash from main branch
* 83b6129 (origin/feature/cloner) Added feature from clone
* 7f887fd Modified login feature
*   20e0968 Fix merge conflicts between login and main
|\  
| * 48420f2 Login feature
| * ee935f4 Creating the main file
* | 64b4209  Main file added
|/  
* 9de4d99 gitignore added
* 9d91f75 Initial commit
