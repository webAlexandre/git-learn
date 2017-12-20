# git-learn
Repository created in order to get used to git commands and features

***

## Config
0.  `$ git config --global user.name "set your name here"`
0.  `$ git config --global user.email "set your email adress"`
0.  `$ git config core.editor`<br/>
    `$ git config core.editor "path/to/app"`
***

## Commands
1.  `$ git init`
2.  `$ git remote -v`<br/>
    `$ git remote set-url origin https://github.com/USERNAME/REPOSITORY.git`
3.  `$ git status`
4.  `$ git add .`
5.  `$ git push -u origin master` (git push --set-upstream origin master) => push up-to-date branch<br/>
    `$ git push -f origin master` (git push --force origin master) => force push update<br/>
    `$ git push` 
6.  `$ git pull`
7.  `$ git commit -m "Your message here"`<br/>
    `$ git commit` <br/>
        "type you message"<br/>
        esc :wq enter (if using VIM)<br/>
            or<br/>
        ctrl x (if using Emacs)<br/>
        
    `$ git commit --amend`
