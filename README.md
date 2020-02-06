
# **Version Control Tutorial**

## Required software
* Git
* Source tree
* CMder
* Kdiff
* GitHub account

## 1. Installing Software

(All ***choco install*** comands assumes you have installed chocolatey on your workstation from https://chocolatey.org)

To check ig you have git installed on your browser open comand line and type in  ***git --version*** . You have git installed if you get something returned such as:

***git version 2.18.0.windows.1***

At Asit4u we use Source tree as our GUI tool for source control. If you do not already have it installed you can go to :

https://www.sourcetreeapp.com/

I prefer for all of us to become comfortable using git in commandline, so I recomend you download cmder a Portable console emulator for Windows:

https://cmder.net/

or

choco install cmder

The last tool I recomend is Kdiff - KDiff3 is a diff and merge program that. compares or merges two or three text input files or directories

http://kdiff3.sourceforge.net/

or

choco install kdiff3

## 2. Inroduction to version control.

- What is Git?

*Git* is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. Git is easy to learn and has a tiny footprint with lightning fast performance.

- Why do we use version control?

Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.

For almost all software projects, the source code is like the crown jewels - a precious asset whose value must be protected. For most software teams, the source code is a repository of the invaluable knowledge and understanding about the problem domain that the developers have collected and refined through careful effort. Version control protects source code from both catastrophe and the casual degradation of human error and unintended consequences.

Software developers working in teams are continually writing new source code and changing existing source code. The code for a project, app or software component is typically organized in a folder structure or "file tree". One developer on the team may be working on a new feature while another developer fixes an unrelated bug by changing code, each developer may make their changes in several parts of the file tree.

To Explain this concept of version control we are going to create a repository (we refer to projects as repositorys in source control) on GitHub/Bit Bucket and make a few changes to the source code.

## 3. GitHub tutorial

![image](https://github.com/pieterAsit4u/travel-site/blob/master/app/assets/images/first-trip-low-res-i.jpg)

```git
git clone 
```

## 4. Git commands
***Git command***     | Description
-------- | -----
git config --global user.name "Sam Smith" | Tell Git who you are - Configure the author name 
   git config --global user.email sam@example.com | Tell Git who you are - Configure the author email
 git init | Create a new local repository
git clone /path/to/repository     | Check out a repository	Create a working copy of a local repository: develop
git checkout {branchname}   | Switch from one branch to another release 
git checkout -b {branchname}   | Create a new branch and switch to it
git status  | List the files you've changed and those you still need to add or commit
git push -u origin {branchname}   | Create the branch in your remote repository, so others can use it and push all staged files
git push  | Push your local current working branch into your remote repository.




## 5. Branch management


Branch     | Description
-------- | -----
develop | most current working branch, to be run locally 
release    | Stageing branch to be used for UAT testing
master     | Production branch
feature/{branche-name}     | New feature to be added into develop
update/{branche-name}     | bug-fix to be added into release 

## 6. Conclusion 





