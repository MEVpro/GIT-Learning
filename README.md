# GIT-Learning
[Easy tool to learn basic git](https://learngitbranching.js.org/?locale=en_US&DEMO=)<br>
---
- **git**<br>
- **git help**<br>
- **git status**<br>
- **git add**<br>
- **git add .**                                 ---- add all files<br>
- **git commit -m "..."**                         --|-- make commit |<br>
- **git commit --amend -m "..."**                 --|-- make to the last commit |<br>
- **git branch**                                  --|-- check branches status<br>
- **git branch -D [Branch]**                      --|-- delete branch<br>
- **git branch [Branch]**                         --|-- create branch<br>
- **git checkout [Branch or Commit]**             --|-- перейти в ветку<br>
- **git checkout -b [Branch]**                    --|-- создать и перейти в ветку ("-b"="branch") <br>
- **git merge**                                   --|-- объединение текущей ветки с ...веток<br>  
- **git rebase [Branch]**                         --|-- перемещение главной* ветки вместе с коммитами в<br>
- **git rebase [Branch(where)] [Branch(what)]**   --|-- перемещение [Branch(what)] ветки вместе с коммитами в ветку[Branch(where)]<br>
- **git checkout HEAD^**                          --|-- переместиться на предыдущий коммит<br>
- **git checkout HEAD~4**                         --|-- переместиться на 4 предыдущих коммита<br>
- **git branch -f [Branch] [HEAD^ or Commit]**    --|-- перемещает ветку (by force) по дереву<br>
- **git reset [Branch]**                          --|-- restart branch from another comment (for local git)<br>
- **git revert [Branch]**                         --|-- restart branch from another comment (for pushed git)<br>
- **git cherry-pick [Commit] [Commit] [...]**     --|-- copy commits from anywhere to head branch*<br>
- **git rebase -i [HEAD^ or HEAD~4]**             --|-- interactive copy commits form branch* to main<br>
- **git tag [Tag] [Commit]**                      --|-- give tag to commit<br>
- **git describe [Branch]**                       --|-- output: <tag>_<numCommits>_g<hash><br>
- **~ [number]**                                  --|-- 1 step back by branch +<br>
- **^ [number]**                                  --|-- 1 step back by branch subsequence +<br>
- **git clone**                                   --|-- make a copy of repository<br>
- **git fetch**                                   --|-- synchronization local repository with remote (only download but not install)<br>
- **git pull**                                    --|-- fetch + merge<br>
- **git pull --rebase**                           --|-- fetch + rebase<br>
- **git push**                                    --|-- отправляет файлы на remote<br>
- **git push origin [Branch]**                    --|-- copy specified branch to the same remote branch (no matter where HEAD)<br>
- **git push origin [Branch]:[remoteBranch]**     --|-- copy specified branch to the specified remote branch (no matter where HEAD) <br>
                                                *if remote branch does not exist git creates it*<br>
- **git pull origin [Branch]:[remoteBranch]**     --|-- copy specified branch to the specified local branch (no matter where HEAD) <br>
                                                *if local branch does not exist git creates it*<br>
- **git fetch origin [Branch]:[remoteBranch]**    --|-- copy specified branch to the specified local branch (no matter where HEAD) <br>
                                                *if local branch does not exist git creates*<br>
- **git branch -u [remoteBranch] [Branch]**       --|-- set local branch to track remote<br>
- **git checkout -b [Branch] [remoteBranch]**     --|-- create branch + checkout branch + track remote branch<br>
- **git push origin :[Branch]**                   --|-- delete branch<br>
- **git pull origin :[Branch]**                   --|-- create branch<br>
- **git fetch origin :[Branch]**                  --|-- create branch<br>

