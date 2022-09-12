---
title: "Must-know GitHub and Git Functions"
published: true
tag: GitHub, Git, Manual
---
# GitHub Functions
## Personal Website


## GitHub CLI
Install `gh`, then work seamlessly with GitHub using `gh` command.

### auth: always login first
```bash
gh auth login
```

### Issues
To create an issue, assign it to yourself, add label, title and body
```bash
gh issue create -a @me --label "content" --title "add a post" --body "Reading notes of introduction to HTTP"
```



## Detach a forked Repo
Sometimes you forked a repo on GitHub, then you found out that the original repo was not updated/archived or did not accept any PRs (pull requests). Moreover, you got the right to use and modify the source code freely.  
In this case, what you need to do is to remove the fork dependency, detach the fork and make your own repo standalone/independent.    
All you need is this [GitHub Support Bot](https://support.github.com/request/fork).

