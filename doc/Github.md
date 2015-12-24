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
to clone a gitub repository 'repo': git clone https://github.com/<owner>/repo.git

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
shows lines that match a pattern

### log
shows commit logs

### merging pull request
From your project repository, bring in the changes and test.

- git fetch origin
- git checkout -b 'branch' origin/'branch'
- git merge master

Merge the changes and update on GitHub.

- git checkout master
- git merge --no-ff 'branch'
- git push origin master

### pull
- use --dry-run to see what would happen

### push
to push changes to a remote branch
- use --dry-run to see what would happen
- if you create a new local branch then to set upstream branch create a branch at remote of same name and use:
git push --set-upstream origin 'branch'

### stash
to save away changes in a dirty working directory eg. when changing branch using git checkout
- to stash dirty changes: git stash
- to get list of stashed changes: git stash list
- to see stashed changes: git stash show
- to reapply stashed changes: git stash apply

### status
shows status of current branch

### request-pull
to create a pull request

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
