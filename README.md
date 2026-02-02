


20/01/2026_Demo::
==================


In Demo session we have Overview of the all CI/CD tools & AWS Road Map


<img width="1909" height="725" alt="image" src="https://github.com/user-attachments/assets/61ba06cc-e465-488c-8611-05da91992c12" />


<img width="1622" height="697" alt="image" src="https://github.com/user-attachments/assets/01e5a341-1f67-4742-afc6-29ffad71d4c2" />






21/01/2026_Tools Overview::
==============================



1.Overview about the all CI/CD & AWSDevOps Training flow

2.Discussed about the all the DevOps roles



<img width="1909" height="725" alt="image" src="https://github.com/user-attachments/assets/61ba06cc-e465-488c-8611-05da91992c12" />


<img width="1622" height="697" alt="image" src="https://github.com/user-attachments/assets/01e5a341-1f67-4742-afc6-29ffad71d4c2" />


DevOps::
DevOps is a software development and operations (DevOps) methodology that combines these two to improve efficiency and speed up project deliverables, It's very important because it helps businesses/deliver software faster and with higher quality.

What is the key purpose of DevOps? 

The primary goal of DevOps is to bridge the gap between development and operations teams. It creates a streamlined, efficient workflow that delivers software faster and with higher quality. DevOps is a set of practices,tools that automate and integrate the processes between software development and IT teams.

DevOps Engineer Roles::
=========================

1)The devops engineer was responsibility to release the product to the market as soon as possible 

2) release the product speed to the market

3)Devops engineer was give continues feedback to the developers 

4) Devops engineer responsibility start from git and end with production

5) Design, build, and maintain Continuous Integration and Continuous Delivery (CI/CD) pipelines.

6) Automate the build, test, and deployment processes.


   
Benefits of DevOps ::
=======================

1) Faster software delivery

2)Reduces lead times and speeds up the software delivery process • 

3)Higher software quality

4)Addresses bugs quicker and improves software quality 

5)Better collaboration

6)Unifies development and operations teams, enhancing collaboration and efficiency 

7)Competitive advantage: Creates a more nimble software development lifecycle that gives businesses an advantage over their competitors





21/01/2026::
==============



What is Git?

Git is a free, open-source version control system (VCS) that helps developers manage their code. It's the most widely used tool VCS(version control system) Git is fast for committing, branching, merging, and comparing past versions Git is very high Performance and Flexibility,Security.


<img width="1642" height="751" alt="image" src="https://github.com/user-attachments/assets/b318e637-fc0c-4576-81a0-cb62bb39266c" />




Install Git in you local machine::
=====================================

https://git-scm.com/downloads/win

Please download the ---64-bit Git for Windows Setup.

Once download the git .exe file , double click and install the git on your machine

once installed right click on your local machine you can found Open Git batch here option, means git is installed successfully in your machine.


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/60c63d76-3cc5-4183-ab00-6284111858da" />





GitHub account creation::
=============================

For creating github account EmailId is Required

go to link --https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home

Enter Email & password ,Username click continue ---Account will create successfully image


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/96cb1d99-753a-4ff5-8221-29145a3f29e3" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d8246f56-598d-424c-a752-28c72401c510" />


Github::
==========

Github is a one of the SCM(Source code management) tool and store the Project code.

Repository: 
===================

storage area of your source code. Create a Repository on GitHub  

OR

Repositories::	
==============

Storage spaces for your project files and history. Think of it as a folder for a project.


Github Introduction::
==================

GitHub is a web-based platform for version control and collaboration, allowing developers to store and manage their code in repositories.

Version Control: :: GitHub uses Git, a distributed version control system, to track changes in code. This allows multiple people to work on the same project without overwriting each other's contributions.

Repositories::: where you can store your project files and track the history of changes made to those files.Public and private repos can be created depending on accessibility needs.


click Repositories


<img width="1276" height="648" alt="image" src="https://github.com/user-attachments/assets/529103b6-d817-43c6-ab26-38ef98339411" />


Click New

<img width="1325" height="655" alt="image" src="https://github.com/user-attachments/assets/148ac26f-214c-4a45-ae9f-ca7104ba9c7a" />


Enter Repository Name::SRINFOTECHDEMO

<img width="1311" height="662" alt="image" src="https://github.com/user-attachments/assets/4c8d604c-4fea-454c-b12f-fa295d1ab792" />


Public:: Anyone on the internet can see this repository.

<img width="1300" height="604" alt="image" src="https://github.com/user-attachments/assets/3c884a24-87bf-48b6-bd28-c4a6a67ab5d8" />

Private:: You choose who can see and commit to this repository.

select Add a README file

<img width="1346" height="699" alt="image" src="https://github.com/user-attachments/assets/73c29693-cf1f-40c4-bb41-d64f3a7fdc91" />


Click Create Repository

<img width="1315" height="702" alt="image" src="https://github.com/user-attachments/assets/934eec8d-6734-4111-b4c2-819ef835f57a" />

Repository Created SUccessfully with Default branch main

<img width="1317" height="697" alt="image" src="https://github.com/user-attachments/assets/ad4a2344-159b-49e4-a83e-e85df6fdbb53" />



Generate SSHKeys:: to Integarte Git to Github
==============================================

syntax::ssh-keygen -t ed25519 -C "your_email@example.com"


>ssh-keygen -t ed25519 -C "srinfotechbatch5@gmail.com"

Keys avaibale path and save the key (/c/Users/HP/.ssh/id_ed25519):

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/036b310b-0c16-4bc1-b4ef-0bd479450509" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/148e65ae-7023-4b85-9c43-3edbaa9c04c7" />


Please follow below links for more understanding 

https://docs.github.com/en/authentication/connecting-to-github-with-ssh

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

Once genearted the keys (public/private) and copy public key to Github Account

Go to -->Open Copilot   ---->Settings  --->Click SSH and GPG keys


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/683eb1e3-0836-48c5-9399-a54d201bbc06" />



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6c7a3749-757f-4adc-bcd8-ca328330858f" />




Click SSH and GPG Keys

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f7fb1aa6-52c0-47f6-a378-99475c0a9b43" />



click New SSH Key

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ad66cb42-82af-48ca-b1c3-01ab480e17a7" />



Add new SSH Key and click Add SSH Key


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/df130ae9-0e1b-4041-8dbd-a878088e69cf" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1adfb3b1-e41c-453d-a035-29a54dd67d77" />



Lab Practice::
==============

HP@DESKTOP-3GU6R56 MINGW64 ~
$ ssh-keygen -t ed25519 -C "syedkareem6033@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/c/Users/HP/.ssh/id_ed25519):
Created directory '/c/Users/HP/.ssh'.
Enter passphrase for "/c/Users/HP/.ssh/id_ed25519" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/HP/.ssh/id_ed25519
Your public key has been saved in /c/Users/HP/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:svzlr1LVHaRYhbGP08xaCjFuYAPrObkE79fK3fcjOBs syedkareem6033@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|       .     o=o |
|        o   o.o. |
|     . . + + + ..|
|      + + + + B .|
|      .BS  = o * |
|     .ooo + . =  |
|      oo o.E.o   |
|       .+oooo. o |
|        .+o=+.o +|
+----[SHA256]-----+




22/01/2026::
==============

Fork in Github::
====================

In GitHub, forking is a way to create your own copy of someone else's repository. example please fork below project to your own github account

https://github.com/srinfotechbatch5/Demo#

steps to fork the project::
============================

Go to Above Project URL

https://github.com/srinfotechbatch3/DevOpsDemo

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/45b0c823-863d-447b-943e-a32cbfc6cb65" />


at top right we can found Fork option in github Account 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/406477ce-4851-462c-9187-30e50320c4f7" />


Click on Fork and click create Fork 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f399adbd-d00c-4cd9-9dd3-9a0e16170aa5" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/59c07b24-f750-41ba-851c-4f2b6712ccaf" />


Successfully Fork done from someone else's repository 

once above steps done ,please clone the Project and Modified files and push to github repository


Git Commands::
================

1. git clone <repository url>

>git clone 

>cd <repository name>

>git status

>git add --all

after added the files we need to verify the status of the files

>git status

>git commit -m "message"

>git push    ---> push the changes from local machine to remote

ssh-keygen -t ed25519 -C "your_email@example.com"

>ssh-keygen -t ed25519 -C "srinfotechbatch5@gmail.com"

Lab Practice::
=================


HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6
$ git clone git@github.com:srinfotechbatch5/Demo.git
Cloning into 'Demo'...
The authenticity of host 'github.com (64:ff9b::14cf:4952)' can't be established.
ED25519 key fingerprint is: SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yesHost key verification failed.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6
$ git clone git@github.com:srinfotechbatch5/Demo.git
Cloning into 'Demo'...
The authenticity of host 'github.com (64:ff9b::14cf:4952)' can't be established.
ED25519 key fingerprint is: SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6
$ cd Demo/

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Demo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        HelloWorld.java

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Demo (main)
$ git add --all
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'HelloWorld.java', LF will be replaced by CRLF the next time Git touches it

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Demo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        new file:   HelloWorld.java
        modified:   README.md


HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Demo (main)
$ git commit -m "added few project files"
[main f561048] added few project files
 3 files changed, 41 insertions(+), 1 deletion(-)
 create mode 100644 .gitignore
 create mode 100644 HelloWorld.java

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Demo (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 750 bytes | 375.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:srinfotechbatch5/Demo.git
   47f99cf..f561048  main -> main

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Demo (main)
$




23/01/2026::
=============


Github branching strategy::
===========================

Github Branching Model::
-------------------------------

A GitHub branching model is a structured way of organizing branches in a Git repository to manage development workflows effectively. It helps teams work collaboratively, isolate features, manage releases, and deploy code more efficiently.



<img width="1729" height="775" alt="image" src="https://github.com/user-attachments/assets/7e6620b7-7339-423c-855d-537c8fb3d6d2" />


A GitHub branching strategy is crucial for maintaining an organized workflow in version control. There are different strategies depending on the size of the project, the number of team members, and the desired workflow. Here are some common branching strategies used in GitHub:

main or master branch:: This is default branch and whenever we created the empty Repository by defauly main or master branche is created automatically.
main or master branch always stable and live code 

feature branch:: It could be a new feature, an improvement of existing features, bug fixes, or any other changes. A feature branch is a type of branch in Git typically used to develop new features for the software.feature branch will created from main or master OR feature branch created from latest release branch always based on the release cycle

formate:: feature/YYYY.MM.DD
 feature/2025.08.05

release branch:: Based on the release we have created release branch accourdingly and starts the next release cycle.
always release branch created from master only and master have stable and live code and post release we shold merged code changes to master branch only

release/2025.08.10




Create New Branch::
=================

Click Branches


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a795a257-a126-449e-9dba-22729bec940d" />

Find New Branch at Right side and click

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2b5fbd36-953e-45e0-baef-450c680b7e5f" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/17de84ed-cc93-4b01-8f32-5a1ff0ddf3ee" />

New feature Branch Formate----> feature/YYYY.MM.DD

feature/2025.08.05


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/60902962-ec6c-4c9f-90eb-04c9835a64d0" />

click create New Branch 

Branch Created Successfully

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b6821e5f-3b54-406d-a4ae-7f2fd885974f" />



Branches:
==============


main (or master): Always production-ready.

feature/*: Used for new features.

release/*: Prepares for a new production release.

main or master branch:: 
=====================

This is default branch and whenever we created the empty Repository by defauly main or master branche is created automatically. main or master branch always stable and live code

feature branch:: 
===============

It could be a new feature, an improvement of existing features, bug fixes, or any other changes. A feature branch is a type of branch in Git typically used to develop new features for the software.feature branch will created from main or master OR feature branch created from latest release branch always based on the release cycle

formate:: 
=============

feature/YYYY.MM.DD feature/2025.06.22

release branch:: 
====================

Based on the release we have created release branch accourdingly and starts the next release cycle. always release branch created from master only and master have stable and live code and post release we shold merged code changes to master branch only

release/2025.07.20



Raise PR (Pull Request) :: 
=================================

Merge the code from one branch to another branch that is called pull request

below are the steps to raise PR::

Go to -->Pull requests and click

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/baf5a7d7-f69d-44e8-87ad-ae67d082353f" />


Click New Pull Request::

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/68456b4f-bd40-41b6-a238-25439f97dff4" />


please select base & compare branches so here base branch is release/2025.08.10 and compare branch is feature/2025.08.05

i'm going to merge code changes from feature branch to release branch 


click create pull request

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6b7a39c0-7a34-45c9-812b-ca518d1a441a" />


![image](https://github.com/user-attachments/assets/08a98671-c810-46fc-9024-17bae7538a61)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e36c29e8-3c38-4579-8073-58ac6304e6fd" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dc582d4a-e173-4648-a76c-3aebd7869b5b" />


click merge request

![image](https://github.com/user-attachments/assets/44a4b84e-1aef-4b19-a93e-64e48b362b29)

 Open
srinfotechbatch3 wants to merge 1 commit into main from feature/2025.08.05

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5a70ee7d-fc8e-45aa-bb28-6a445a223cf0" />


confirm merge

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b6e9ab2f-30cc-4fe2-9754-03f6f6262786" />



Lab Practice::
=================


HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6
$ git clone git@github.com:srinfotechbatch5/iphoneMobiles.git
Cloning into 'iphoneMobiles'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6
$ cd iphoneMobiles/

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/iphoneMobiles (main)
$ git checkout feature/2026.01.25
branch 'feature/2026.01.25' set up to track 'origin/feature/2026.01.25'.
Switched to a new branch 'feature/2026.01.25'

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/iphoneMobiles (feature/2026.01.25)
$ git status
On branch feature/2026.01.25
Your branch is up to date with 'origin/feature/2026.01.25'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Iphonemobile.java

nothing added to commit but untracked files present (use "git add" to track)

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/iphoneMobiles (feature/2026.01.25)
$ git add --all
warning: in the working copy of 'Iphonemobile.java', LF will be replaced by CRLF the next time Git touches it

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/iphoneMobiles (feature/2026.01.25)
$ git status
On branch feature/2026.01.25
Your branch is up to date with 'origin/feature/2026.01.25'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Iphonemobile.java


HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/iphoneMobiles (feature/2026.01.25)
$ git commit -m "impletmented iphonemobiles feature"
[feature/2026.01.25 50bc140] impletmented iphonemobiles feature
 1 file changed, 5 insertions(+)
 create mode 100644 Iphonemobile.java

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/iphoneMobiles (feature/2026.01.25)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 406 bytes | 406.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:srinfotechbatch5/iphoneMobiles.git
   b8c3cf4..50bc140  feature/2026.01.25 -> feature/2026.01.25

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/iphoneMobiles (feature/2026.01.25)
$


Merged

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b8dfb8ae-1a1c-4245-a4ee-944db6bbd07e" />



26/01/2025::
==============


Avoide conflicts in RealTime Scenarious::
==============================================


If multiple developers OR DevOps Engineers are working on same Project/MOdules, if they tried to commits thier code changes to Repository, it will faces the conflicts issues and how to resolved those conflicts issues in real time projects


<img width="1553" height="662" alt="image" src="https://github.com/user-attachments/assets/ef697106-96aa-43c5-8152-3d0c765abf4f" />


Please create developer1,developer2,developer3 directories in your local machine and clone the project code separately 

![image](https://github.com/user-attachments/assets/a0345422-a025-4c3a-84c5-737b98244a6a)


![image](https://github.com/user-attachments/assets/3296003f-c8c7-42c8-bdca-3270576aaa57)


![image](https://github.com/user-attachments/assets/7e786310-5092-4975-9eb9-7b18801353d8)

Editor steps for Resolved the conflicts::

resolved conflicts::

>git pull

opend the editor

1.presh the i from your keyboard

2.esc

3.swift+:

4.wq

5.enter


Developer1 Activity::
=====================

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer1
$ git clone git@github.com:srinfotechbatch5/onlinebookstore.git
Cloning into 'onlinebookstore'...
remote: Enumerating objects: 1182, done.
remote: Total 1182 (delta 0), reused 0 (delta 0), pack-reused 1182 (from 1)
Receiving objects: 100% (1182/1182), 4.63 MiB | 2.34 MiB/s, done.
Resolving deltas: 100% (572/572), done.

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer1
$ cd onlinebookstore/

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer1/onlinebookstore (master)
$ git checkout feature/2026.01.26
branch 'feature/2026.01.26' set up to track 'origin/feature/2026.01.26'.
Switched to a new branch 'feature/2026.01.26'

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer1/onlinebookstore (feature/2026.01.26)
$ git status
On branch feature/2026.01.26
Your branch is up to date with 'origin/feature/2026.01.26'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Jenkinsfile

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer1/onlinebookstore (feature/2026.01.26)
$ git add --all

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer1/onlinebookstore (feature/2026.01.26)
$ git status
On branch feature/2026.01.26
Your branch is up to date with 'origin/feature/2026.01.26'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   Jenkinsfile


HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer1/onlinebookstore (feature/2026.01.26)
$ git commit -m "i have updated jenkinsfile"
[feature/2026.01.26 6ea26d6] i have updated jenkinsfile
 1 file changed, 1 insertion(+), 1 deletion(-)

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer1/onlinebookstore (feature/2026.01.26)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 308 bytes | 308.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:srinfotechbatch5/onlinebookstore.git
   58c7929..6ea26d6  feature/2026.01.26 -> feature/2026.01.26

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer1/onlinebookstore (feature/2026.01.26)
$


Developer2 Activity::
=====================


HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer2
$ git clone git@github.com:srinfotechbatch5/onlinebookstore.git
Cloning into 'onlinebookstore'...
remote: Enumerating objects: 1182, done.
Rremote: Total 1182 (delta 0), reused 0 (delta 0), pack-reused 1182 (from 1)
Receiving objects: 100% (1182/1182), 4.63 MiB | 2.36 MiB/s, done.
Resolving deltas: 100% (567/567), done.

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer2
$ cd onlinebookstore/

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer2/onlinebookstore (master)
$ git checkout feature/2026.01.26
branch 'feature/2026.01.26' set up to track 'origin/feature/2026.01.26'.
Switched to a new branch 'feature/2026.01.26'

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer2/onlinebookstore (feature/2026.01.26)
$ git status
On branch feature/2026.01.26
Your branch is up to date with 'origin/feature/2026.01.26'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Jenkinsfile

Merge branch 'feature/2026.01.26' of github.com:srinfotechbatch5/onlinebookstore into feature/2026.01.26


remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 2), reused 3 (delta 2), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 288 bytes | 10.00 KiB/s, done.
From github.com:srinfotechbatch5/onlinebookstore
   58c7929..6ea26d6  feature/2026.01.26 -> origin/feature/2026.01.26
Auto-merging Jenkinsfile
Merge made by the 'ort' strategy.
 Jenkinsfile | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer2/onlinebookstore (feature/2026.01.26)
$ git push
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 677 bytes | 225.00 KiB/s, done.
Total 6 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), completed with 2 local objects.
To github.com:srinfotechbatch5/onlinebookstore.git
   6ea26d6..4e17117  feature/2026.01.26 -> feature/2026.01.26

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer2/onlinebookstore (feature/2026.01.26)
$


Developer3 Activity::
=====================


HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer3
$ git clone git@github.com:srinfotechbatch5/onlinebookstore.git
Cloning into 'onlinebookstore'...
remote: Enumerating objects: 1182, done.
remote: Total 1182 (delta 0), reused 0 (delta 0), pack-reused 1182 (from 1)
Receiving objects: 100% (1182/1182), 4.63 MiB | 1.89 MiB/s, done.
Resolving deltas: 100% (572/572), done.

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer3
$ cd onlinebookstore/

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer3/onlinebookstore (master)
$ git checkout feature/2026.01.26
branch 'feature/2026.01.26' set up to track 'origin/feature/2026.01.26'.
Merge branch 'feature/2026.01.26' of github.com:srinfotechbatch5/onlinebookstore into feature/2026.01.26




Auto-merging Jenkinsfile
Merge made by the 'ort' strategy.
 Jenkinsfile | 9 ++++++++-
 1 file changed, 8 insertions(+), 1 deletion(-)

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer3/onlinebookstore (feature/2026.01.26)
$ git push
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 685 bytes | 342.00 KiB/s, done.
Total 6 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), completed with 2 local objects.
To github.com:srinfotechbatch5/onlinebookstore.git
   4e17117..ad7d248  feature/2026.01.26 -> feature/2026.01.26

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer3/onlinebookstore (feature/2026.01.26)
$


Git All the Commands::
==========================

Git commands::
==============
1.git clone git@github.com:srinfotechbatch5/onlinebookstore.git

2.cd SRINfotechDemo

3.git status

4.git add --all

5.git status

6.git commit -m "i have added hellow world project files"

7.git push   ---->from local changes pushed to remote

8.git pull   --->remote to local

9.git checkout <branchname>

   git checkout feature/2025.06.22
   
10.git pull  --->every devlioper beforre pushing their changes we should make sure git pull the every time   
  

clone      Clone a repository into a new directory

add        Add files

status     Show the working tree status

commit     Record changes to the repository

 pull       Fetch from and integrate with another repository or a local branch
 
 push       Update remote refs along with associated objects



27/01/2026::
=============

>git fetch--->just fetch

>git pull -->fetch+merged


>git pull   ---> pull the changes from remote to local -->fetch+merge


>git fetch  --->just fetch the details from remote to local  -->just only fetch the details


Lab Practice::
================


HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer1/onlinebookstore (feature/2026.01.26)
$ git fetch --help

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer1/onlinebookstore (feature/2026.01.26)
$ git fetch
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 935 bytes | 34.00 KiB/s, done.
From github.com:srinfotechbatch5/onlinebookstore
   bd3b575..f47536a  feature/2026.01.26 -> origin/feature/2026.01.26

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer1/onlinebookstore (feature/2026.01.26)
$ git pull
Updating bd3b575..f47536a
Fast-forward
 Jenkinsfile | 21 +--------------------
 1 file changed, 1 insertion(+), 20 deletions(-)

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer1/onlinebookstore (feature/2026.01.26)
$ git fetch

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer1/onlinebookstore (feature/2026.01.26)
$ git fetch
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 2.07 KiB | 92.00 KiB/s, done.
From github.com:srinfotechbatch5/onlinebookstore
   58c7929..efa6f24  master     -> origin/master

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer1/onlinebookstore (feature/2026.01.26)
$ git fetch
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 5 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (5/5), 1.78 KiB | 50.00 KiB/s, done.
From github.com:srinfotechbatch5/onlinebookstore
   f47536a..c21aa90  feature/2026.01.26 -> origin/feature/2026.01.26
   efa6f24..97554bd  master             -> origin/master

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer1/onlinebookstore (feature/2026.01.26)
$ git pull
Updating f47536a..c21aa90
Fast-forward
 pom.xml | 4 +++-
 1 file changed, 3 insertions(+), 1 deletion(-)

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Demo Batch6/Developer1/onlinebookstore (feature/2026.01.26)
$ git fetch


Class Note::
============

1.install git

2.introduction about the VCS ---git

3.SCM --source code management tool -->github

4.intriduction abot the github

5.create the github account

6.crete the repo's/repositories

7.integrate git & github via SSH keys--->ssh-keygen -t ed25519 "srinfi@gmail.com"

8.how to create the branches in github

9.integarted and independent 

10.how to rasie PR--pull request

11.git commands

12.git clone 

13.cd <repo name>

14.git checkout <branch name>

15.git status

16.git add --all  OR git add <filename>

17.git status

18.git commit -m "message"

19.git push

20.git pull

21.git fetch

if any facing conflicts

open editor

1.press i from your keyboard

2.esc from your keyboard

3.swift+:

4.wq

5.enter

22.github branching strategy 

23.git flow model

24.how to resolved the conflicsts if multiple peopel are working same project

25.end to end flow of git & github




28/01/2026::
=============


Jenkins Introductiion::
============================
Jenkins is a free and open source automation server/tool. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration and continuous delivery.

Jenkins is a Orchestration tool

Jenkins is a CI/CD tool

Jenkins is a Schedular

Jenkins is a crone job schedular


<img width="1720" height="703" alt="image" src="https://github.com/user-attachments/assets/1a6e5d7a-9934-47f8-a0dc-cf3b9f5ff89b" />


Roles And Responsibilities::
================================
1)The devops engineer was responsibility to release the product to the market as soon as possible 

2)release the product speed to the market 

3)Devops engineer was give continues feedback to the developers 4) Devops engineer responsibility start from git and end with production

A) when your activity start from git and end with production environment(production servers)Continues deployment 
when your activity start from git to LLE(lower level environment,testing environment,pre-prod…et) environment(pre-production servers)Continues delivery non-production environment

Tutorials::
============

https://www.tutorialspoint.com/jenkins/jenkins_overview.htm https://www.geeksforgeeks.org/jenkins-tutorial/#prerequisites

Download JDK 17 ::
================

https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html

Windows x64 Installer 153.92 MB

Windows x64 Compressed Archive	172.87 MB	

https://download.oracle.com/java/17/archive/jdk-17.0.12_windows-x64_bin.zip (sha256 )

JDK 17 Environment setup::
==============================

Go to Windows Search box & type Edit the system environemnt variables and click

It will navigate to System properties

![image](https://github.com/user-attachments/assets/2de9b257-9029-43f7-af30-4f4f4827731a)

Click Environment Variables


![image](https://github.com/user-attachments/assets/0b02d209-cb85-4afd-869f-923df054b7de)

![image](https://github.com/user-attachments/assets/88adc878-dedd-4150-9ee8-f01c75677ab2)

User variables::
================

![image](https://github.com/user-attachments/assets/d6bfe193-6a5c-4a8b-a21a-fa77c07a4bbc)

Click New

Variable Name:: JAVA_HOME

Variable Value:: C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12

![image](https://github.com/user-attachments/assets/5743966a-8e88-4502-bd3a-904f1a839a01)

Click OK

![image](https://github.com/user-attachments/assets/1af67329-3601-4e23-855e-b69cf5763d95)


System variable::
=================

![image](https://github.com/user-attachments/assets/0cecde24-19be-4989-98c5-c3eb9c20734c)

Edit Path

![image](https://github.com/user-attachments/assets/5f302184-84cb-4e66-b17a-3ce4792fa45c)

Click New and give Java Installed path till \bin

C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12\bin

![image](https://github.com/user-attachments/assets/d918df00-9c10-424f-b155-7a22e925d291)

Click OK

You Can verify Java is Installed Or Not

Go to command Prompt

![image](https://github.com/user-attachments/assets/773f6318-d8a5-4d2c-803b-e504d84e24e1)

![image](https://github.com/user-attachments/assets/aee76eab-4f27-4fce-af69-f28a872d37dc)


>java --version

C:\Users\HP>java --version
java 17.0.12 2024-07-16 LTS
Java(TM) SE Runtime Environment (build 17.0.12+8-LTS-286)
Java HotSpot(TM) 64-Bit Server VM (build 17.0.12+8-LTS-286, mixed mode, sharing)

![image](https://github.com/user-attachments/assets/92e49e72-2f7c-464c-b8f1-2a30e6ebe702)

Above Screeenshot JDK17 setup is done




Installed jenkins in Windows::
================================

https://www.jenkins.io/download/

Go to google search -->download jenkins war file for windows

click below Jenkins version

Download Jenkins 2.516.1 LTS for:

https://get.jenkins.io/war-stable/

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1ad241e7-3ae0-4f30-8ef2-33af47891c5b" />


Jenkins.war file is downloaded


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/98751ae3-bfde-45fc-8863-1f1eb1d954eb" />



Steps::

https://www.jenkins.io/download/

1. First download the jenkins.war file and right click -->open gitbash here
   

 ![image](https://github.com/user-attachments/assets/77ca0550-974b-463f-953a-d81c9603d69a)

  
2. run the command  -->java -jar jenkins.war --httpPort=9090

![image](https://github.com/user-attachments/assets/93cc2393-8a20-485f-ab8c-23451a64ccd3)

![image](https://github.com/user-attachments/assets/75e03c2f-0ccf-4da0-90cf-d92de22903c3)

we can see Jenkins is fully up and running

![image](https://github.com/user-attachments/assets/b0e26f12-f202-4e69-8672-223e6947d379)


Browse to http://localhost:9090 and wait until the Unlock Jenkins page appears

Installed the default suggested plugins

![image](https://github.com/user-attachments/assets/081c44fc-a6a3-46fa-82e3-7b34c2dc2dd6)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cb89c015-8816-4269-b365-128c645375b5" />



29/01/2026::
============


Installed the default suggested plugins

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/8a80769d-672b-42c4-ad59-bdb5a288abc7" />


click on continue 

Need to create jenkins user profile 

USER Name--->admin (any name you can provide)

PASSWORD  -->admin  (any password as your wish but make sure you should remembered the these credentials)

![image](https://github.com/user-attachments/assets/f0458a88-da81-4d32-9f87-42458fd214a1)


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/e11ae91e-ec78-42e1-b64d-19696755931a" />



Maven setup::
=============

Maven is a powerful build automation and project management tool, primarily used with Java projects


<img width="1784" height="644" alt="image" src="https://github.com/user-attachments/assets/7fd9f762-5293-4297-a371-2cc052404a3a" />


Please follow the below link for more understading the Maven lifecycles OR maven Goals

https://maven.apache.org/guides/introduction/introduction-to-the-lifecycle.html

MAVEN_HOME=C:\Users\HP\Downloads\apache-maven-3.9.9-bin\apache-maven-3.9.9

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fca1b236-b778-490e-abec-61298f74bb9d" />


Download link

https://maven.apache.org/download.cgi


Make sure we should setup the path at system variable 

JAVA_HOME & MAVEN_HOME

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c7c2c771-4be4-4488-83b4-c3b9172beca3" />



now verify the java version & maven version:: go to git bash and verify. below are refreenced screenshots

> java -version


C:\Users\HP>java --version
java 17.0.12 2024-07-16 LTS
Java(TM) SE Runtime Environment (build 17.0.12+8-LTS-286)
Java HotSpot(TM) 64-Bit Server VM (build 17.0.12+8-LTS-286, mixed mode, sharing)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/638553a1-2319-43c3-89e3-4e9cd949a634" />


> mvn -v

C:\Users\HP>mvn -v
Apache Maven 3.8.9 (e26b057cc3a17459358ef53e4d0e2e381bf08a1c)
Maven home: C:\Users\HP\Downloads\apache-maven-3.8.9-bin\apache-maven-3.8.9
Java version: 17.0.12, vendor: Oracle Corporation, runtime: C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12
Default locale: en_IN, platform encoding: Cp1252
OS name: "windows 10", version: "10.0", arch: "amd64", family: "windows"

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/329d0a8b-1d56-4d27-957d-a779c236224b" />



once above setup is ready then we will proceed to installe jenkins

Common Maven Commands::
==========================

1.mvn clean         # Clean up previous builds

2.mvn compile       # Compile source code

3.mvn test          # Run unit tests

4.mvn package       # Create a JAR/WAR

5.mvn install       # Install package into local repo
6.mvn clean install        # Deploy package to remote repo


Create sample Freestyle project::
============================

Github Project URL:::
=====================

https://github.com/srinfotechbatch5/spring-petclinic



Click New Item

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e8a51a17-f3f8-4719-95f0-551ad8e2fb4f" />

Enter an item name     ---->This Should be Name of your Project

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/adebc306-828a-4920-bb47-63d8fe060c67" />


Click OK


Configuration stages::

1.General

2.Source code management (SCM)

3.Triggres

4.Environment

5.Build Steps

6.Post Build Actions


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/515589a7-463e-4209-94e5-cf6c2ce6caab" />



General Section provide the Project/job description 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a92f0756-1444-490e-a60b-d3c48bc4be84" />


At SCM stage level select the Git and provide the github details


https://github.com/srinfotechbatch5/spring-petclinic

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6f736b3a-6179-4a86-a56b-08d76c22ffdd" />


Branches to build

main branch and this branch should match with github repository branch


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8d4094c2-e384-4a08-b699-1e4fc4625656" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b392b9e0-631c-404d-bcd7-3e26c096fb16" />


Build steps::select the Invoke top-level Maven targets

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/659cddb4-e8fd-44b8-a6c6-1e77a62eaf1b" />


Goals section
>mvn clean install

Maven goals::

>mvn test

>mvn install


>mvn clean install


>mvn clean


>mvn package

>mvn compile

![image](https://github.com/user-attachments/assets/53d49170-9dfe-4cad-abc0-50bf268e96c7)


Job will be created

Click Build Now


Buils is Inprogress

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3444e4a2-865d-41ce-be9e-aa8e8da44d67" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d877e99a-1e20-4ddc-b061-81a585b67ea5" />


Build Sucess


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/de5df49e-4413-4804-9413-26e7a6cda71c" />



30/01/2026::
============


Poll SCM ::
=============

Jenkins server ask git if there is any changes in git server or not, if changes there Jenkins server build/package the changes , every change build happened like 5 mints ,means every 5 minutes verify the Jenkins server to git if there is any changes 


<img width="1663" height="684" alt="image" src="https://github.com/user-attachments/assets/4f831f81-ab6b-42b4-8e73-752076df2cbe" />


POLL SCM ----* * * * * --every minute when every commit 

Chrone JObs Formate LInk::
=============================

https://crontab.guru/examples.html


Create one sample POLL SCM jenkins job::
===========================================

Go to jenkins Dashboard

click New Item

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/098730bb-4882-4e6e-9627-2670dbff097a" />


Description

![image](https://github.com/user-attachments/assets/8385086f-ae72-4630-baa2-38e16e9866c2)



Provide the Git URL

Onlinebookstore Project::
=========================

https://github.com/srinfotechbatch4/onlinebookstore.git


![image](https://github.com/user-attachments/assets/647ef983-c76e-4c48-b928-e43ab5d47570)



Branch buiild

![image](https://github.com/user-attachments/assets/cd011371-c6c5-40d6-a44a-b51186d0e3af)


POLL SCM:: * * * * *

every minute build was trigger when new commits happend in github repository


![image](https://github.com/user-attachments/assets/899495ff-ce8c-4381-a012-5d058584809a)



Build Steps::

Select Invoke top-level Maven targets


![image](https://github.com/user-attachments/assets/8a818614-ba02-45d5-a98d-8d94adbe68f7)



Once New Commits Happend in Github , Automatically Build is triggered in The Jenkins Server this Called CI (Continuous Integration)



Check Your Workspace::
========================== 

once build success we can bale to see the /target folder under the Workspace


![image](https://github.com/user-attachments/assets/d860064f-6f5f-4ef2-aa93-363bf45e47c5)


1.To check a job's workspace:

2.Navigate to the job in the Jenkins UI.

3.Click on "Workspace" in the left sidebar.

![image](https://github.com/user-attachments/assets/f5ab670a-e7aa-4372-bbea-c3a1c130fe3a)



Under Target Folder we can able to see the all .ear/war/jar/zip Artifacts Formates


![image](https://github.com/user-attachments/assets/369fe791-fb6e-4a59-8fb1-99a14df190c3)


PLease try to execute the Project with below Maven Goals and see the difference 


Common Maven Commands OR Maven Goals::
======================================

https://github.com/srinfotechbatch5/spring-petclinic.git

https://github.com/srinfotechbatch5/onlinebookstore.git

1) mvn clean	  ------------> Deletes target/ directory (clean build).

2) mvn compile	-----------> Compiles the source code.
   
3) mvn test	   ------------> Runs tests.
   
4) mvn package	------------> Creates a JAR/WAR.
  
5) mvn install	------------> Installs package into your local repository.
  
6) mvn deploy	-------------> Deploys package to a remote repository.



