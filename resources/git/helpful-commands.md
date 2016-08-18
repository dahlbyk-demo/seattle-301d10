#Remotes
On github, a remote points to a particular repository. By default, once a new repository is created on github, the remote created is named the `origin` and its value is the URL path that leads to github.com, plus the organization or indvidual's account, plus the name of the repo (e.g. https://github.com/codefellows/code-301-prework).  
When you `push` or `pull` from a remote, your local repository is interacting with that repository on GitHub directly.
##Adding Remotes
When cloning a repository that you plan to work on but are not a collaborator on, you need to `fork` it first, creating a copy of it at its current state, to your own GitHub account. After forking and cloning the repository locally, your `origin` will point to the copy on your GitHub account, but now to easily access changes (that is, `pull`), you will need to add a new remote in addition to your origin.  
To do so, `git remote add upsream`, where upstream is a convention but not a requirement.
```sh
```
