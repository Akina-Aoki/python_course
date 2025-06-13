# Setup Git and Github

In this section, we will go through how to use Git and Github for version control. We will only cover the basics here which are necessary for this course. If you are interested in more features and benefits of Git, check out the links in the _Read more_ section below. Follow the instructions below to get started.

**a) git and github theory**
<a href="https://youtu.be/bbJDBTAMtm8" target="_blank">
  <img src="https://github.com/kokchun/assets/blob/main/git_github/git_theory.png?raw=true" alt="git and github setup" width="600">
</a>

**a) git and github setup**
<a href="https://www.youtube.com/watch?v=NX19Yz2_S0Y" target="_blank">
  <img src="https://github.com/kokchun/assets/blob/main/git_github/git_github_setup.png?raw=true" alt="git and github setup" width="600">
</a>

## Instructions

### 1. Installing Git in local machine

By installing Git in your local machine, you are able to perform version control on your project offline. You can also review your codes locally before pushing the changes to a remote repository available to other developers in your team.

- download Git [here](https://git-scm.com/downloads) for your operation system
- you can check if Git is installed succesfully with the syntax below in terminal

> [!NOTE]
> if you are on windows, you will be using git bash instead of the terminal that I show here. However all commands shown in this tutorial are the same 

  ```bash
  git --version
  ```

  <img src="https://github.com/kokchun/assets/blob/main/git_github/downloadgit.png?raw=true" width="500">


### 2. Creating remote repository in Github

We will be using Github to host our remote repository. This is the central codebase online where other developers in your team can access and contribute to.

- sign up for Github [here](https://github.com) if you do not have an account in github yet
- go to _Your repositories_ and click on _New_ to create a new remote repository
- name the repository in this way: [course name]\_[first name]\_[family name]\_[class name]. See the example below with the example name Chris Smith
- After clicking _Create repository_, your new repository will be listed under the page _Your repositories_

  <img src="https://github.com/kokchun/assets/blob/main/git_github/newrepo.png?raw=true" width="500">

### 3. Basic Git commands

- `git clone`

  Now that you have created a remote repository on Github, you are ready to work on your project from your local machine. The first step is to clone the remote repository to your local machine by using its web URL. You can find the web URL in the dropdown list _Code_ as below:

  <img src="https://github.com/kokchun/assets/blob/main/git_github/repourl.png?raw=true" width="500">

  Create a folder, for example, called _Course_, where you would like your repository to be stored. Then, change the directory in the terminal:

  <img src="https://github.com/kokchun/assets/blob/main/git_github/cd.png?raw=true" width="500">

  Use the command `git clone` and the web URL to clone the remote repository to the directory:

  <img src="https://github.com/kokchun/assets/blob/main/git_github/clone.png?raw=true" width="500">

  Then you can find your local repository in the chosen directory:

  <img src="https://github.com/kokchun/assets/blob/main/git_github/afterclone.png?raw=true" width="500">


  Note that you will be asked for the credential of your github account when cloning private repositories for the first time on your local machine.

- `git add`, `git commit` and `git status`</br>
  Normally when you are working with, for example, word files, saving means overwriting the existing files or creating new files. However, in Git, saving are broken down into two steps:

  `git add` will add the changes to a staging area while `git commit` will eventually make the staged changes to the local repository. You can use `git status` to track the staged changes and unstage them before commiting them to the local repository.

  Below, we have added text for chapter 1 in the .md file and commited this change.

  <img src="https://github.com/kokchun/assets/blob/main/git_github/gitadd.png?raw=true" width="500">


- `git push origin main`

  When you are satisfied with the version of your local repository, you can update the remote repository on Github accordingly. The command `git push origin main` will serve this purpose. Here _origin_ is the default name of the remote repository with the web URL used previously for cloning. Note that this name can be changed. While _main_ refers to the branch you are pushing your changes to on the remote repository. After this, the changes will be reflected in the remote repository on Github:

  <img src="https://github.com/kokchun/assets/blob/main/git_github/gitpush.png?raw=true" width="500">

## Read more

-[Git repositories](https://www.geeksforgeeks.org/working-with-git-repositories/) </br> -[Basics Git commands](https://www.atlassian.com/git/glossary#commands)
