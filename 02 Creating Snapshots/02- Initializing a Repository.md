# 02- Initializing a Repository

## Initialize a git repository

Create a directory and put it any where. In may case `/Users/jmschp/code/mosh-ultimate-git-course/`.

Inside the directory run `git init`. This command should return the following message:

```zsh
❯ git init
Initialized empty Git repository in /Users/jmschp/code/mosh-ultimate-git-course/.git/
```

Inside our project folder, the command `git init` has created a folder `.git`, by default it is hidden because we are not supposed to touch it. With the command `ls -a` we can see the git sub directory.

> **If we corrupt or delete this directory we lose the project history.**

# my notes

- i think `.git` hidden folder is the actual `repository which holds the entire history` 