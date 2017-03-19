# Learning-Git
Basis for students learning to use git, the dominant modern version control tool

## Getting git
The [git website](https://git-scm.com/) has a page on [installing git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git). The school computers already have git installed. For Linux users, you know what to do. For Mac users, I suggest using [Homebrew](https://brew.sh/) as a package manager. You can ask it to install git with `brew install git`.

## Setup
Here's the [setup page](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup) on the website. A minimal setup involves recording your identity:
```bash
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```

Consider setting up these aliases for your convenience:
```bash
$ git config --global alias.at "status"
$ git config --global alias.logg 'log --graph --format="%C(auto)%h%d %s %Cgreen@%Creset{%ar}"'
```
