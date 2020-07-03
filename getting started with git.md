# Getting Started with Git & GitHub

Before starting, we need some basic idea about the topic.

#### GitHub
GitHub, Inc. is a United States-based global company that   provides hosting for software development version control using Git. It is a project management and a code version control system as well as a social network platform made for developers.

#### To understand exactly what GitHub is, you need to know two connected principles :
  - Version control
  - Git
#### Version Control 
Version control is like a savings program for your project. By tracking and logging the changes you make to your file or file sets over time, a version-control system gives you the power to review or even restore earlier versions. Version control takes snapshots of every revision to your project. You can then access these versions to compare or restore them as needed.

#### Git
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. It was created by Linus Torvalds in 2005. It helps developers keep track of the history of their code files by storing them in different versions on its own server repository, i.e., GitHub. Git has all the functionality, performance, security, and flexibility that most of the development teams and individual developers need.

To find more about git and git commands [**click here**](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet).

#### The two main concept of GitHub is :
 - GitHub Repository
 - GitHub Project 

#### GitHub Repository
GitHub repositories are where we store code. We create a repository then we can connect our local git repository to that remote repository and push up changes, created branches, and share our code with our team.
#### GitHub Project
A GitHub project is a place to track issues, features, and other tasks related to the code in the repository. We can also connect up with a DevOps build and deploy process, assign people to tasks, and so forth.

> **[Now, if you have these concept you should go to github home page, sign up & create an account as well as a repository.]**

For working in a github repository you need a tool which will work as a medium of you and your github account. There are several tools for this but I personally prefer :

 - Git 
 - Sourcetree 

For downloading Git [**click here**](https://git-scm.com/downloads).

For downloading Sourcetree [**click here**](https://www.sourcetreeapp.com/).

> You can use these tools in several environments : **Windows, Mac, Linux**

#### I used Git in Windows at my computer. So I'll proceed with this.

You need to download and install git first at your windows. It's easy but if you feel uncomfortable with installing this, there's a lot of videos in YouTube. So, you can go and watch a small tutorial of installing git.


If you have successfully installed git, then the next thing is to connect it with your created repository at GitHub. This is also easy. Just follow the steps :

1. First create a folder (local repository) at your computer & press right click at your mouse and select **"Git Bash Here"**
2. In the terminal shell type :

```
$ git config --global user.name "Your name here"
$ git config --global user.email "your_email@example.com" 
```
#### Convert Your Local Directory into a Repository
When you have your files in a local folder and want to convert it into a repository, you’ll need to initialize the folder through the **git init** command. This will instruct Git to begin to track that directory as a repository. To do so, open the terminal on the directory you’d like to convert and run:

```
$ git init  
```

This command creates a <span style="background-color: #FFFF00">**.git**</span> folder in your directory that contains Git records and configuration files.
Then add the path to your remote repository, so that Git can upload your files into the correct project.

#### Adding a Remote Repository
To add a new remote, use the <span style="background-color: #FFFF00">**git remote add**</span> command on the terminal, in the directory your repository is stored at.

* The git remote add command takes two arguments:
 - A remote name, for example, origin
 - A remote URL, for example, https://github.com/user/repo.git

For example : 
```
$ git remote add origin https://github.com/user/repo.git
```

To view your remote repositories, type: 
```
$ git remote -v
```
#### Branching

If you want to add code to a project but you’re not sure if it will work properly, or you’re collaborating on the project with others, and don’t want your work to get mixed up, it’s a good idea to work on a different branch.

When you create a branch in a Git repository, you make a copy of its files at the time of branching. You’re free to do whatever you want with the code in your branch without impacting the main branch or other branches. And when you’re ready to bring your changes to the main codebase, you can merge your branch into the main one used in your project (such as master).

**To create a new branch, to work from without affecting the master branch, type the following:**

```
$ git checkout -b <name-of-branch>
```

**Switch to the master branch**

You are always in a branch when working with Git. The main branch is the master branch, but you can use the same command to switch to a different branch by changing master to the branch name i.e. : 
```
 $ git checkout master 
```

**View the changes you’ve made**

It’s important to be aware of what’s happening and the status of your changes. When you add, change, or delete files/folders, Git knows about it. To check the status of your changes: 
```
 $ git status
```

**View differences**

To view the differences between your local, unstaged changes and the repository versions that you cloned or pulled, type: 
```
 $ git diff
```

<span style="background-color: #FFFF00">**Now, the most important things about git is to add a file and commit.**</span>

**For adding a file/folder into GitHub you first need to type :**
```
 $ git add <file-name OR folder-name>
```

**you can also use : ```
 $ git add . ```     for uploading all the files in a folder.**


**Then you need to commit. Commit is like a comment about the upload and the command is:**
```
 $ git commit -m "COMMENT TO DESCRIBE THE INTENTION OF THE COMMIT"
```

**You can pull/pick all the changes in the same local working folder by this command :**  
```
 $ git pull
```

You can send the changes made in the same local working directory by using :
```
 $ git push
```





-------------------------------


---------

### Try By Yourself

---------











