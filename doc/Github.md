# github
Use github markdown for README.md and documentation.

## ui
- create a repository by clicking new on repositories tab
- create directory by typing / in a filename
- rename file by changing name

## github flow
- create 'working' branch
- make changes (add, or change files)
- commit changes to 'working' branch
- pull from 'master' branch
- create pull request to propose changes to 'master'

## git - command line
On first usage use:
- git clone
- git config
### add
to track changes in files
### branch
- list branches: git branch
- delete a branch: git -d branch
### checkout
- create branch: git checkout -b 'branch'
- switch to a branch: git checkout 'branch'
### clone
- to clone a gitub repository 'repo': git clone https://github.com/<owner>/repo.git
### commit
commits changes to the repository. Done with a sequence of git add, git rm, and git commit.
- to commit all changes: git commit -a
- use --dry-run to see what would happen
### config
- to see configuration: git config -l
- to set user email: git config --global user.email "you@example.com"
- to set user name: git config --global user.name "your name"
### diff
shows changes
### grep
- shows lines that match a pattern
### log
- shows commit logs
### pull
- use --dry-run to see what would happen
### pull-request
to create a pull request
### push
to push changes to a remote branch
- use --dry-run to see what would happen
- if you create a local branch then to set upstream branch create a branch at remote of same name and use:
git push --set-upstream origin 'branch'
### status
- shows status of current branch
### rm
to delete a file

# References
## Git
- [Git User Manual](https://www.kernel.org/pub/software/scm/git/docs/user-manual.html)
- [Git Reference](http://gitref.org/)
- [Git Reference Manual](http://git-scm.com/docs)
- Online Book - [Pro Git by Scott Chacon and Ben Straub](http://git-scm.com/book/en/v2)
## Github
- [Github Flow](https://guides.github.com/introduction/flow/)
- [GitHub Glossary](https://help.github.com/articles/github-glossary/) of terms
## Markdown
- [Markdown basics](https://help.github.com/articles/markdown-basics/)
- [GitHub Markdown](https://help.github.com/articles/github-flavored-markdown/)
