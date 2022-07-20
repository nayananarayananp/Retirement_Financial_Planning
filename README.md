# Retirement Financial  Documentation
## JupyterLab files
- financial_planning_tools.ipynb
This file demonstrates how to evaluate and analyse the investment fund for emergiencies and for retirement using MCForecastTools library and JupyterLab.

## Git and terminal commands
nayan@NayanaWork MINGW64 ~
$ cd Fintech-Workspace/Challenge/
(base)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge
$ conda activate dev
(dev)
### Create Repo

Created a repo via Github UI and clone to local
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge
$ git clone https://github.com/nayananarayananp/Retirement_Financial_Planning.git
Cloning into 'Retirement_Financial_Planning'...
warning: You appear to have cloned an empty repository.
(dev)

```
### Switch to local git repo called Crypto_Arbitrage
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge
$ cd Retirement_Financial_Planning/
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Retirement_Financial_Planning (main)
$ ls
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Retirement_Financial_Planning (main)
$ ls
__pycache__/  financial_planning_tools.ipynb  Images/  MCForecastTools.py  README.md
(dev)

```

### Organize folders in starter code
Checked git status showing the organized starter code
```
$ git status
On branch master

```

### Add starter code files to git
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Retirement_Financial_Planning (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .env
        .gitignore
        Images/
        MCForecastTools.py
        README.md
        financial_planning_tools.ipynb

nothing added to commit but untracked files present (use "git add" to track)
(dev)
```

### Check the files got added
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Retirement_Financial_Planning (main)
$ git add *
The following paths are ignored by one of your .gitignore files:
__pycache__
hint: Use -f if you really want to add them.
hint: Turn this message off by running
hint: "git config advice.addIgnoredFile false"
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Retirement_Financial_Planning (main)
$ git status
On branch main

No commits yet
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Images/5-4-monte-carlo-histogram.png
        new file:   Images/5-4-monte-carlo-line-plot.png
        new file:   MCForecastTools.py
        new file:   README.md
        new file:   financial_planning_tools.ipynb

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .env
        .gitignore

(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Retirement_Financial_Planning (main)
$ git add .gitignore
warning: CRLF will be replaced by LF in .gitignore.
The file will have its original line endings in your working directory
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Retirement_Financial_Planning (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   .gitignore
        new file:   Images/5-4-monte-carlo-histogram.png
        new file:   Images/5-4-monte-carlo-line-plot.png
        new file:   MCForecastTools.py
        new file:   README.md
        new file:   financial_planning_tools.ipynb

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .env

(dev)

### Git commit
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Retirement_Financial_Planning (main)
$ git commit -m "Created Jupyter lab for retirement financial planning"
[main (root-commit) ac5c446] Created Jupyter lab for retirement financial planning
 6 files changed, 3472 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 Images/5-4-monte-carlo-histogram.png
 create mode 100644 Images/5-4-monte-carlo-line-plot.png
 create mode 100644 MCForecastTools.py
 create mode 100644 README.md
 create mode 100644 financial_planning_tools.ipynb
(dev)
```
## Git push
Try pushing to github 
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Retirement_Financial_Planning (main)
$ git push
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 16 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (9/9), 538.32 KiB | 25.63 MiB/s, done.
Total 9 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/nayananarayananp/Retirement_Financial_Planning.git
 * [new branch]      main -> main
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Retirement_Financial_Planning (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .env

nothing added to commit but untracked files present (use "git add" to track)
(dev)
```
### Capture terminal history
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Portfolios_Analysis (main)
$ history 50 > terminal_history.txt
(dev)
```
Attached to [](./terminal_history.txt)

### Run program


Running the program with code completed
```
```

### Final commit and push
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Retirement_Financial_Planning (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore
        modified:   financial_planning_tools.ipynb

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        MC__dist_plot.png
        MC__sim_plot.png
        MC_dist_plot.png
        MC_fiveyear_dist_plot.png
        MC_fiveyear_sim_plot.png
        MC_sim_plot.png
        terminal_history.txt

no changes added to commit (use "git add" and/or "git commit -a")
(dev)
$ git add *
The following paths are ignored by one of your .gitignore files:
__pycache__
hint: Use -f if you really want to add them.
hint: Turn this message off by running
hint: "git config advice.addIgnoredFile false"
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Retirement_Financial_Planning (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   MC__dist_plot.png
        new file:   MC__sim_plot.png
        new file:   MC_dist_plot.png
        new file:   MC_fiveyear_dist_plot.png
        new file:   MC_fiveyear_sim_plot.png
        new file:   MC_sim_plot.png
        modified:   financial_planning_tools.ipynb
        new file:   terminal_history.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore

(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Retirement_Financial_Planning (main)
$ git add .gitignore
warning: CRLF will be replaced by LF in .gitignore.
The file will have its original line endings in your working directory
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Retirement_Financial_Planning (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   .gitignore
        new file:   MC__dist_plot.png
        new file:   MC__sim_plot.png
        new file:   MC_dist_plot.png
        new file:   MC_fiveyear_dist_plot.png
        new file:   MC_fiveyear_sim_plot.png
        new file:   MC_sim_plot.png
        modified:   financial_planning_tools.ipynb
        new file:   terminal_history.txt

(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Retirement_Financial_Planning (main)
$ git commit -m "Final commit"
[main ee783bb] Final commit
 9 files changed, 3322 insertions(+), 3297 deletions(-)
 create mode 100644 MC__dist_plot.png
 create mode 100644 MC__sim_plot.png
 create mode 100644 MC_dist_plot.png
 create mode 100644 MC_fiveyear_dist_plot.png
 create mode 100644 MC_fiveyear_sim_plot.png
 create mode 100644 MC_sim_plot.png
 rewrite financial_planning_tools.ipynb (66%)
 create mode 100644 terminal_history.txt
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Retirement_Financial_Planning (main)
$ git push
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 16 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (9/9), 274.00 KiB | 22.83 MiB/s, done.
Total 9 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/nayananarayananp/Retirement_Financial_Planning.git
   ac5c446..ee783bb  main -> main
(dev)
    
    
    
    
    