


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




<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b59dd459-4574-4039-873c-4b97787074b7" />



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



02/02/2026::
===============


Execute the Jobs in Parallel::
==============================


1.By Default execute the Jenkins build jobs are sequence way,one by one 

2.Don’t do 2 projects build parallel  this is real time scenario but we can do parallel builds as well one job

Jenkins build parallel setup

Go job ---> configure ----> Generall ---> Execute concurrent builds if necessary


![image](https://github.com/user-attachments/assets/3216a68f-b10b-44cd-83b5-b62c27525296)


![image](https://github.com/user-attachments/assets/909edd87-548d-4ded-a862-29cf850fac05)


Executors::
=============

Go to Manage Jenkins  ----> System ----># of executors



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0d817873-45e7-4354-a0e9-8a1783ce338a" />



Here 10 builds execute parallel ,I kept executor is 10 this is same machine 


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bf2c18d8-3ab8-4f8d-b465-e7de1449d4a7" />


Poll SCM ::
================

Jenkins server ask git if there is any changes in git server or not, if changes there Jenkins server build/package the changes , every change build happened like 5 mints ,means every 5 minutes verify the Jenkins server to git if there is any changes 

<img width="1629" height="686" alt="image" src="https://github.com/user-attachments/assets/63643206-be1e-43da-92bd-03d50cabf97b" />


POLL SCM ----* * * * * --every minute when every commit 

Build Periodically:::	
============================

H/15 * * * *   ----this build happened every 5 minutes without commits ,if changes are commit or not but every 5 mints build happened in Jenkins 


Please create a New Jenkins jobs both POLL SCM & Build Periodically 

https://github.com/srinfotechbatch5/spring-petclinic.git

https://github.com/srinfotechbatch5/onlinebookstore.git

Automatically Discard Old Builds:::
==============================
To automate the process of discarding old builds, you can configure the job’s settings to automatically delete old builds based on criteria such as the number of builds to keep or the age of the builds.

Follow these steps:

Open the Jenkins job (project).
Click on Configure (on the left-hand side).
Scroll down to the Build Discarder section (usually under the Build Triggers section).
Check Discard old builds.
Specify the following options:
Max # of builds to keep: Set the maximum number of builds to keep.
Max days to keep builds: Set the maximum age for builds to keep.
Save the configuration by clicking Save.


![image](https://github.com/user-attachments/assets/8d8c9cf9-988a-41e4-b052-539ef601171f)



Build Periodically:::	H/15 * * * *   ----this build happened every 5 minutes without commits ,if changes are commit or not but every 5 mints build happened in Jenkins 


Create Sample Build peridiocally jenkins job::
=============================================

Description


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4827b662-c7e4-47ad-8cbc-65ded11d095b" />


Git url::


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5f0da0e6-fcd7-4ad2-b854-3df9af2393a7" />


Build the branch

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4f0ac907-c4ab-4ae9-b632-e8ddf71a7160" />


every 1 minute build will trigger

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cf65d287-5c0a-4855-8ddc-9b26be1c7a26" />


every 5 mints build will trigger

Build Periodically:::	H/15 * * * *   ----this build happened every 5 minutes without commits ,if changes are commit or not but every 5 mints build happened in Jenkins 


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1ed08304-1831-4a27-af65-f17da5117e05" />


click save 


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/57d8ccdb-34a8-43b0-a5f0-1f0538a0fc10" />



05/02/2026::
==============

Email Notifications::
=======================

1.Setting up Jenkins Email Notifications allows you to alert your team when a build passes, fails, or encounters issues. Here's a step-by-step guide to configure it

2. give continues Feedback to the Dev team via Email when a build passes, fails



<img width="1572" height="665" alt="image" src="https://github.com/user-attachments/assets/b04dfaa0-83d0-46b2-ab0a-6063db010d9a" />



Steps::

Go to mail 


![image](https://github.com/user-attachments/assets/e6764012-c4e8-43ab-bea7-0fcf11c61f5e)

Click manage your google account

![image](https://github.com/user-attachments/assets/b2b0e9e5-66ff-4713-b95b-0cc3cc2ecf42)


Click Security


![image](https://github.com/user-attachments/assets/acc069d3-2944-43d7-a0d0-a0ae17b478d6)


Click protect your account


![image](https://github.com/user-attachments/assets/a80aa65d-210c-4920-ac59-bff59d001048)

Click Add phone number

![image](https://github.com/user-attachments/assets/d3839125-e302-40a0-a942-497f50f2e08a)

Click add phone

![image](https://github.com/user-attachments/assets/758cb87d-c0df-43d1-890a-6539046b86f7)

![image](https://github.com/user-attachments/assets/e532e1dd-fef8-4ed6-b46c-075d97cdd10d)

![image](https://github.com/user-attachments/assets/96dde956-0cb9-4125-bc16-9b18b5a47883)

Make sure your account is protected 

![image](https://github.com/user-attachments/assets/ef101b4f-f98a-4941-83bb-e99c98a7b583)


Make sure 2-steps Verification is ON


![image](https://github.com/user-attachments/assets/eb82b19f-0ae0-4df4-8c79-463769e0f2cf)


Credentials:

In search box App Password


![image](https://github.com/user-attachments/assets/20789330-ae4d-407d-b55c-201452435d33)

![image](https://github.com/user-attachments/assets/45634fa0-7198-4a55-9ce3-bd5c7c7b4c2d)


![image](https://github.com/user-attachments/assets/d9e2b041-0e63-42de-96be-0b2406113328)


![image](https://github.com/user-attachments/assets/814dc39c-290f-4035-bec8-6871cfd44467)


 we should provide this password in Jenkins Email configuration level


![image](https://github.com/user-attachments/assets/b1cde092-d3ed-4ae8-b9fb-e3fd32095fce)


Go to Jenkins  ---> Manage Jenkins

System configurations


![image](https://github.com/user-attachments/assets/e3467726-c6f8-45f5-b728-5012e2e906f3)



Go to Extended E-mail Notification



![image](https://github.com/user-attachments/assets/11351c43-ecf5-4327-86d9-a4bcde391589)


SMTP server  :: smtp.gmail.com

SMTP Port:: 465

Credentials::
Username:: Your Email
Password::Zvqxxvplduhrlffv

![image](https://github.com/user-attachments/assets/7e8c5e1a-785f-4b0e-b85c-f37b6f1123ce)



Select Use SSL

Default content type HTML

![image](https://github.com/user-attachments/assets/742a4252-a704-4a0c-ad2b-ae35e9c2a2e0)


Default Triggers

![image](https://github.com/user-attachments/assets/67d1fe48-b3f0-4d59-a842-054b11a3ed70)

E-mail Notification


![image](https://github.com/user-attachments/assets/dc3dfcd8-1454-434b-a88b-44acf32a3f56)


![image](https://github.com/user-attachments/assets/37414d6d-d388-4f21-840e-899b8c3e3bf1)


Use SMTP Authentication? –should selected

Use SSL select

Port 465

![image](https://github.com/user-attachments/assets/0c8e8c73-69bc-4a2b-a19e-f130e81f8c16)


Test configuration by sending test e-mail

![image](https://github.com/user-attachments/assets/b48d366e-5a52-458c-b80d-1c45b803e3ce)


Connection success

![image](https://github.com/user-attachments/assets/28f7fd8a-c85e-486a-b2f4-64af53b1db0a)


 Post build action


![image](https://github.com/user-attachments/assets/d386a9c7-a5cf-4a48-a6ab-5030c96288e0)


![image](https://github.com/user-attachments/assets/d200565f-7356-4470-b080-8ba7f731837c)


![image](https://github.com/user-attachments/assets/7cddd9fa-8498-47fa-a86b-5066ae058700)


![image](https://github.com/user-attachments/assets/60b129a8-5adf-43b1-9639-a293c59d929c)




06/02/2026::
============

Published Artifacts & Test Results::
==================================


<img width="1772" height="729" alt="image" src="https://github.com/user-attachments/assets/5a1ba48a-d541-453b-8ff3-a53fb4d5ba70" />


![image](https://github.com/user-attachments/assets/591cddf5-eb86-4942-91a7-1dc5bfbb0f72)



Post build Action i want to published artifacts & test results


I'm going to created one free style job and configured Post-build Actions

In post build Action select the option Archive the artifacts

>target/*.war  OR target/*.jar  OR target/*.zip  OR target/*.ear

![image](https://github.com/user-attachments/assets/44f88d03-d9c8-4800-88e2-06217f721d5c)

![image](https://github.com/user-attachments/assets/7ed9efc9-6a45-4eff-a789-0b7fe50c6024)


In post build Action select the option Publish JUnit test result report for to published the test results

>target/surefire-reports/*.xml


![image](https://github.com/user-attachments/assets/e3c17557-410c-4915-bec3-2ec5edee6526)



I want to show test results ::
=================================


>ls target 

Post build action stage

Select archive the artifact
--target/*.jar

Junit test results::
--target/surefire-reports/*.xml

See test results & antifactory ::
===================================


![image](https://github.com/user-attachments/assets/819809c2-3611-45e0-abd0-0139b29d166b)




3.For every company will do sequence build on one project this is recommended approach



General  ---just descriptin

SCM

where is your project--github, bitbucket

Triggere

whenever code changes i want build the project given time

Environmant

--all about workspaces folders

Build Steps

dev team will tell which tool we are using in current project


Post Build

devops engineer is aim is given continue feedback to dev team via email notification



Parameterized Jenkins Jobs ::
===============================

Run the same job with different inputs without modifying the configuration manually

Go To New Item

![image](https://github.com/user-attachments/assets/695a7137-6283-462b-8ff7-37ffb4f6ff68)


Enter Job Name, Free style project and click ok

![image](https://github.com/user-attachments/assets/da12fe42-db98-40e1-af80-1ba335b50596)



Enter the description

![image](https://github.com/user-attachments/assets/cd3c1d8f-d403-4694-a830-1084796c80ad)


Select the option This project is parameterised

![image](https://github.com/user-attachments/assets/e2fb86d9-ea5b-4981-a3ee-81d4645d06c1)


Click Add Parameter

![image](https://github.com/user-attachments/assets/2702952d-1e31-4432-a405-88f509bfc58c)


Select optiions String parameter or choise parameter or boolean parameter you can select the ny options based on your requirement 

![image](https://github.com/user-attachments/assets/1b18b622-c141-4988-bdc3-785359a04e99)


select string parameter

![image](https://github.com/user-attachments/assets/33215729-9b13-46bf-bbbb-b08416979dd6)


Select Choise Parameter

![image](https://github.com/user-attachments/assets/59b8db99-1196-4024-9cdf-b3a80a358f81)


choise parameter

![image](https://github.com/user-attachments/assets/952de313-ebde-4b39-be7b-c31c6b0ca283)


Click Save

![image](https://github.com/user-attachments/assets/4f19f2ba-c85b-4adf-9dd0-16da436011dd)


You Can observed this project is parameterized 

![image](https://github.com/user-attachments/assets/fef0f526-c9f2-4dec-8d0e-960efc94d09c)


Click Build with parameter

![image](https://github.com/user-attachments/assets/1cbeb32c-bd23-4d87-87be-8e6d010bb968)


select deployment environment

![image](https://github.com/user-attachments/assets/af62b4d7-b107-4856-b567-d010efb3a11a)


select which versioj you want to deployment like tis you can configured real time parameterized project in jenkins

![image](https://github.com/user-attachments/assets/506da743-2efd-4e19-8082-67592c3c24b1)


Click Build

![image](https://github.com/user-attachments/assets/9554cd4a-ba9a-4821-af2e-638d554632a8)


![image](https://github.com/user-attachments/assets/28afabd9-1c84-4313-95c6-1ec8bd50488d)



09/02/2026 ::
=================


I want Build a 3 projects ::
===========================

I want a build 3 projects ,one project build is success then it will start 2nd project & once 2nd project build is success then it will start 3rd Project, without manually interventions we need setup these 3 projects configurations.


<img width="1701" height="762" alt="image" src="https://github.com/user-attachments/assets/daa81276-0311-4862-a5ca-dd5df5265a98" />


![image](https://github.com/user-attachments/assets/5d043ea2-97c3-4b8f-8b56-95703e1adf95)




Project-A, Projec -B, Projec - C 

Once Project-A build is done, then it will start Project-B build and once Project-B build SUccess then it will start Project-C build ---for this we need to select Add post-build action and select "Build other projects" in drop down and provide Project-B details.


![image](https://github.com/user-attachments/assets/048a99bc-bcf6-47ca-9b27-ef23152eab97)


Projec A is  (Downstream project is ---Projec B)

Projec B is (UP Stream project is ----Projec A)

Projec C is (downstream project of --Projec B)

i created 3 free style project in jenkins 

Project-A ::
==============

Github URL::: https://github.com/srinfotechbatch5/spring-petclinic.git

![image](https://github.com/user-attachments/assets/e8073061-b815-4945-bd7f-c20b3a6576e2)


Post Build Action , select the option Build Other Project  Project-B




<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0b792995-005a-4175-9cdb-4cd8524fea60" />


Project -B ::
=============

Github URL:::https://github.com/srinfotechbatch5/onlinebookstore.git


![image](https://github.com/user-attachments/assets/2ee62e92-e677-4717-93be-77d6dd1ecbf9)


Post Build Action , select the option Build Other Project Project-C


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b94f430d-2173-4d08-8432-f7e86ec9b47c" />






Project-C::
============


Github URL:::https://github.com/srinfotechbatch5/devOpsWeb.git



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/69efc57e-2857-46d7-a3ab-34a58b5b0aae" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/256cac24-5476-4b71-8079-adb194559549" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ed6d257b-d93f-4eee-9a07-9dade9f5b984" />



12/02/2026::
==============

Pipelines Introduction:::
=============================

A Jenkins pipeline is a series of automated steps or stages that define the process of continuous integration/continuous delivery (CI/CD) for your code. Jenkins, being a popular open-source automation server, uses pipelines to automate tasks like building, testing, and deploying code.

There are two types of Jenkins pipelines:

1. Declarative Pipeline

2. Scripted Pipeline

1. Declarative Pipeline::
The declarative pipeline syntax is simpler and more structured. It's the recommended style for most users because it's easy to read and maintain



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/35709278-05d5-4b7c-9356-e5cf614ab7ce" />


Create Pipeline Project::
=======================

Steps

Click +New Item


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3ac406d8-9a29-4e2f-9711-226ff8806524" />


Enter the Project Name And Click OK

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/339a329c-47d6-41e0-b008-6128965033c5" />


At General Section Provide the Description


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cb474edb-bcaf-42f9-9d1d-b51da6333b74" />


At Definition, We need to select the Pipeline Script 


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5dc25001-3022-4d7a-8772-64c2bf85c55e" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/58d97da8-8baa-43e2-b25f-ad8c60fd0c32" />



Here's an example of a simple declarative pipeline: Syntax

pipeline{

agent any

stages{

Stage ('Clone'){

steps{

// write code
}
}

Stage ('Build'){
steps{

// write code
}
// write code

}

Stage ('Test'){

steps{

// write code
}
// write code

}
Stage ('Execute test casea and get the results'){

steps{

// write code
}
// write code

}

Stage ('Generated Artifact'){

steps{

// write code
}
// write code

}

Stage ('Deploy'){

steps{

// write code
}
// write code

}

// write code

}

}



pipeline {
   
    agent any

    stages {
       
        stage('Clone') {
           
            steps {
              
                echo 'Hello World'
            }
        }
        stage('Build') {
           
            steps {
              
                echo 'Hello World'
            }
        }
        stage('Test') {
           
            steps {
               
                echo 'Hello World'
            }
        }
        stage('Generate the test reports') {
          
            steps {
               
                echo 'Hello World'
            }
        }
        stage('Publishered Artifacts') {
           
            steps {
              
                echo 'Hello World'
            }
        }
        stage('Deploy') {
          
            steps {
              
                echo 'Hello World'
            }
        }
    }
}



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/661f0dc6-aeb3-4a06-9a7c-b66c55e431bb" />



Pipeline: Stage View::
========================

Pipeline: Stage View Plugin in Jenkins The Pipeline: Stage View plugin is a visualization tool in Jenkins that allows users to see a graphical view of each stage in a pipeline. It provides a real-time and historical overview of pipeline execution per stage, making it easier to debug, monitor, and analyze performance.


Click the Build Now and we can triggered the pipeline








Success all the stages & Steps


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/40a1524f-7926-4d0c-b294-c43ede8350f2" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d2bec3cd-ec88-438e-badc-24f4bf8b581c" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/470c2ba0-fdd0-4981-ba34-87865fb4b684" />



12/02/2026::
===============


Key elements in the declarative pipeline:::
======================================

pipeline: This is the top-level structure.

agent: Specifies where the pipeline will run, such as on any available agent, a specific node, or a Docker container.

stages: Defines the different steps or stages in the pipeline (e.g., Build, Test, Deploy).

steps: Commands to be executed in each stage.



Please try to create one pipeline job in jenkinsfile and execute the below Declarative pipeline example:;

pipeline {

agent any

stages {
    stage('Clone') {
        steps {
            git branch: 'main', url: 'https://github.com/srinfotech7358/spring-petclinic.git'
        }
    }
    
      stage('Build') {
        steps {
           bat 'mvn clean install'
        }
    }
      stage('Test') {
        steps {
           bat 'mvn test'
        }
    }
    
      stage('Generate Junit Test Results') {
        steps {
           junit 'target/surefire-reports/*.xml'
        }
    }
    
      stage('Generate Artifacts') {
        steps {
           archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
        }
    }
}
}


See test results & antifactory ::
================================

archive the artifact :: target/*.jar

Junit test results:: target/surefire-reports/*.xml


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b216b582-74a9-47de-9351-1fcd88930af4" />


declarative pipeline::
========================

pipeline {
    
    agent any
    
    stages{
       
        stage('checkout-->clone'){
         
            steps{
            
                git branch: 'feature/2026.02.06', url: 'https://github.com/srinfotechbatch5/spring-petclinic.git'
                
            }
        }
        
        stage('Build'){
            
            steps{
           
            bat 'mvn install'
        }
        
        }
       
        stage('Test'){
            
            steps{
               
                bat 'mvn test'
           
            }
        }
       
        stage('Generate Junit Tests Results'){
            
            steps{
               
                junit 'target/surefire-reports/*.xml'
           
            }
       
        }
       
        stage('Generated the Artifacts'){
           
            steps{
               
                archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
           
            }
       
        }
    
    }

}



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/02740931-e1dd-4a34-8120-3ec74a81fde6" />


Scripted Pipeline::
==================

node{
    
    stage('Clone'){
        
        git branch: 'feature/2026.02.06', url: 'https://github.com/srinfotechbatch5/spring-petclinic.git'
  
    }
    
    stage('Build'){
        
       
        bat 'mvn clean install'
    
    }
   
    stage('test'){
       
        bat 'mvn test'
   
    }
    
    stage('genearted test results'){
        
       
        junit 'target/surefire-reports/*.xml'
   
    }
   
    stage('published artifacts'){
        
       
        archiveArtifacts artifacts: 'target/*.war', followSymlinks: false

        
   
    }

}


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/68505168-9859-460f-a3e2-1b037b34d5d0" />




13/02/2026::
============


Pipeline as Code::
===================

Both declarative and scripted pipelines are stored as Jenkinsfiles, which you place in your source code repository. This allows you to version control your pipeline and keep it aligned with your application code.


![image](https://github.com/user-attachments/assets/7d3b20e8-e72f-41ff-94ce-0c912f51a93d)



![image](https://github.com/user-attachments/assets/edd96e0c-ac4d-438e-8a5b-97ae99ed1fda)




Pipeline as Code::
==================
Both declarative and scripted pipelines are stored as Jenkinsfiles, which you place in your source code repository. This allows you to version control your pipeline and keep it aligned with your application code.


Declarative pipeline with Jenkinsfile::
===============================

pipeline {
    
    agent any
    
    stages{
       
        stage('checkout-->clone'){
         
            steps{
            
                git branch: 'feature/2026.02.06', url: 'https://github.com/srinfotechbatch5/spring-petclinic.git'
                
            }
        }
        
        stage('Build'){
            
            steps{
           
            bat 'mvn install'
        }
        
        }
       
        stage('Test'){
            
            steps{
               
                bat 'mvn test'
           
            }
        }
       
        stage('Generate Junit Tests Results'){
            
            steps{
               
                junit 'target/surefire-reports/*.xml'
           
            }
       
        }
       
        stage('Generated the Artifacts'){
           
            steps{
               
                archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
           
            }
       
        }
    
    }

}


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/11677722-35f5-4b1b-85cc-9749cd943704" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/11677722-35f5-4b1b-85cc-9749cd943704" />


This pipeline:::

1 Checks out the source code from your Git repository.

2. Builds the project using Maven.
   
3.Runs unit tests.

4.Deploys the application using a custom script.

JOb creation::

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/edec9bbf-3656-4edb-b80f-46661524dcaa" />

Branches to build


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/062ed8d1-560c-49d7-9668-d91f7a901706" />


Script Path::: This path is Jenkinsfiles where we maintained in github source code level



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c423564b-85df-44b8-a366-c2738ec4b22e" />



Scripted pipeline with Jenkinsfile::
===============================


node{
    
    stage('Clone'){
        
        git branch: 'feature/2026.02.06', url: 'https://github.com/srinfotechbatch5/spring-petclinic.git'
  
    }
    
    stage('Build'){
        
       
        bat 'mvn clean install'
    
    }
   
    stage('test'){
       
        bat 'mvn test'
   
    }
    
    stage('genearted test results'){
        
       
        junit 'target/surefire-reports/*.xml'
   
    }
   
    stage('published artifacts'){
        
       
        archiveArtifacts artifacts: 'target/*.war', followSymlinks: false

        
   
    }

}



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/aaa9e47f-71a3-46e8-876b-f26d9faba86c" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bdee842e-0044-4577-8898-5f5619fcfca4" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bdee842e-0044-4577-8898-5f5619fcfca4" />




github sourcecode jenkinsfile 



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7d17ef94-2780-42b3-8e61-d7fce9b4d15e" />





17/02/2026::
==============


Tomcat Web Server: Introduction
=============================

Apache Tomcat is an open-source web server and servlet container developed by the Apache Software Foundation. It is primarily used to serve Java applications and is one of the most popular servlet containers in the world.

Tomcat is an essential tool for anyone working with Java web applications. It provides a simple, reliable platform for deploying and managing Java Servlets and JSPs and is widely used in both development and production environments. Its ease of use, combined with powerful features and flexibility, makes it an ideal choice for many developers working on Java-based web applications.

Apache Tomcat is an open-source web server and servlet container that is primarily used to serve Java-based web applications. It implements several Java EE (Enterprise Edition) specifications, such as Java Servlet, JavaServer Pages (JSP), and WebSocket, among others. Tomcat is often used to run Java applications on the web because it's lightweight, easy to configure, and widely supported.

Here are some key points about Tomcat:

1. **Servlet Container**: Tomcat is a servlet container, meaning it manages the lifecycle of Java Servlets, which are small Java programs that run on a web server.
  
2. **JSP Support**: Tomcat also supports JavaServer Pages (JSP), a technology that allows for embedding Java code within HTML pages.

3. **Configuration**: It’s highly configurable through XML files, like `server.xml` for server settings, `web.xml` for application settings, and others.

4. **Lightweight**: Unlike full-fledged application servers like WildFly (formerly JBoss) or GlassFish, Tomcat is primarily a servlet and JSP container, which makes it lighter and easier to deploy for simpler Java web applications.

5. **Performance**: It’s known for good performance in handling static content, making it a popular choice for Java web developers.



Integrate Tomcat  with Jenkins::
==============================


<img width="1805" height="756" alt="image" src="https://github.com/user-attachments/assets/ba77128c-4010-4864-8b0a-efcd1ed88ef7" />






Tomcat Download link::
--------------------

https://tomcat.apache.org/download-90.cgi


64-bit Windows zip


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/17a4f6bb-d883-4507-9ecd-eba5c04e4418" />



Integrate Tomcat Jenkins::
==============================



<img width="1805" height="756" alt="image" src="https://github.com/user-attachments/assets/b479289c-aa71-4958-9fd3-fa403aa40386" />








Integrating Tomcat with Jenkins is a common use case for automating the deployment of Java-based web applications. Jenkins can be set up to deploy a web application to a Tomcat server whenever a new build is triggered.

Prerequisites:

Apache Tomcat should be installed and running on your server.

Jenkins should be installed and running.

Steps to integrate Jenkins with Tomcat:

1. Install the "Deploy to Container" Plugin in Jenkins:
The easiest way to deploy to Tomcat from Jenkins is by using the Deploy to Container plugin. This plugin allows Jenkins to deploy WAR files to a Tomcat server.

Go to your Jenkins dashboard.

Click on Manage Jenkins > Manage Plugins.

In the Available tab, search for Deploy to Container Plugin and install it.

Once installed, restart Jenkins to apply the plugin.

2. Configure Tomcat Server in Jenkins:
Now you need to tell Jenkins where your Tomcat server is running.

In Jenkins, go to Manage Jenkins > Configure System.

Scroll down to the Deploy to container section.

Click Add Tomcat Server.

Provide the necessary information:

Name: Give the Tomcat server a name (Tomcat9).

URL: The URL of your Tomcat server (e.g., http://localhost:8080).

Username: The username for Tomcat's manager app (usually admin).

Password: The password for that username (set in Tomcat's tomcat-users.xml).

Save the configuration.

3. Configure Tomcat’s tomcat-users.xml:

Make sure Tomcat is set up to allow Jenkins to deploy the application by editing the tomcat-users.xml file.


https://stackoverflow.com/questions/7763560/401-unauthorized-error-while-logging-in-manager-app-of-tomcat


tomcat-users.xml file::
=========================




<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c3d43081-1646-4980-b961-1743418f303f" />






  <role rolename="manager-gui"/>
  
  <role rolename="manager-script"/>
  
  <role rolename="manager-jmx"/>
 
  <role rolename="manager-status"/>
  
  <role rolename="admin-gui"/>
 
  <role rolename="admin-script"/>
 
  <user username="admin" password="admin" roles="manager-gui, manager-script, manager-jmx, manager-status, admin-gui, admin-script"/>




Restart Tomcat to apply the changes.

4. Create a Jenkins Job to Build and Deploy the Application:

Next, you need to create a Jenkins job that will build your web application (e.g., a WAR file) and deploy it to Tomcat.

From the Jenkins dashboard, click New Item.

Select Freestyle Project, give it a name, and click OK.

In the job configuration, go to the Build section and configure your build step, such as building a Maven project For Maven, you can use:

> mvn clean install

In the Post-build Actions section, add Deploy war/ear to a container.

In the WAR/EAR files field, provide the path to your WAR file (e.g., target/my-app.war).
In the Container field, choose the Tomcat server you configured earlier.
Set the Context Path (e.g., IfocusAWSDevOpsTraining), which is the URL path where the application will be accessible on Tomcat.
If you want Jenkins to deploy automatically after every successful build, check the option Deploy after every successful build.
Save the job.

5. Trigger the Build and Deployment:
Go to the Jenkins job you just created and click Build Now to trigger a build.
After the build completes, Jenkins should deploy the WAR file to your Tomcat server.

You can access your application by going to http://<tomcat_host>:<tomcat_port>/<context_path>

example::  http://localhost:8080/SRINFOTECHApplication/

POLL SCM:: * * * * * (every minute automatic build & deployment happend when new commits happend in github)

This setup will allow Jenkins to automatically build and deploy your Java web application to Tomcat with each new build


Polling SCM (Source Code Management) and webhooks are two common methods used for integrating continuous integration (CI) systems or automating tasks based on changes in repositories.

1. Polling SCM

Polling SCM is a method where a system (like Jenkins, GitLab CI, etc.) periodically checks the source code repository for changes. If it detects changes, it triggers the build process or some other automated task.

How it works:

A job is set up to check the SCM (like GitHub, GitLab, Bitbucket, etc.) at regular intervals (e.g., every minute or hour).

The CI server pulls the repository to see if there are any new commits since the last poll.

If changes are detected, it triggers the CI/CD pipeline to build, test, or deploy the application.

2. Webhooks

Webhooks provide a more efficient method for triggering actions based on changes in the repository. Rather than the CI system polling for changes, the source control platform sends an HTTP POST request (webhook) to the CI system when an event (like a commit or pull request) occurs.

![image](https://github.com/user-attachments/assets/59e3f392-4da9-4fe3-8238-d2bd2fee5fc3)


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0af333dc-7a00-49a3-9f32-035c9c94c84b" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/86864501-ee8d-4c52-af7f-8cf3f25b06f1" />



18/02/2026::
=============


CI/CD::
==========

Continuous Integration & Continutes Deployment & COntinuoues Delivery::
=======================================================================

Continuous Integration(CI)::the practice of automating the integration of code changes from multiple Developers into a single software project. It's a primary DevOps best practice, allowing developers to frequently merge code changes into a central repository,after which automated builds and tests are run automatically.

developers frequently commit to a shared repository using a version control system such as Git,A continuous integration automatically builds and runs unit tests on the new code changes to immediately using jenkins Orchestration.


<img width="1823" height="753" alt="image" src="https://github.com/user-attachments/assets/3f4417a6-6f1f-42f8-bc87-a39bc7207a02" />




Continuous Deployment(CD) :: Continuous Deployment is an extension of continuous delivery. With continuous deployment, every change that passes through the automated tests and builds is automatically deployed to production without any human intervention. The deployment process is fully automated.

Continuous Delivery (CD)::Continuous Delivery is a software development practice in which code changes are automatically built, tested, and prepared for release to production in a consistent and reliable manner. The key distinction of continuous delivery is that the process of deploying the code to production is done manually by a human decision-maker.


<img width="1823" height="753" alt="image" src="https://github.com/user-attachments/assets/9df250cb-ba53-4556-ab74-81839e78c22b" />



Deploy Onlinebookstore/spring-petclinic applications to target server (Tomcat)::
=====================================================================================================================


https://github.com/srinfotechbatch5/onlinebookstore.git

https://github.com/srinfotechbatch5/Petclinic.git


please create one new pipeline job

Provide the Description

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9772aee8-eb5e-4d98-b164-81818916196a" />


Enabled POLL SCM


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e1a4b078-8137-42d7-ad87-bf5aa463436c" />


In Pipeline Section write groovy script using Declarative style 



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2acaf030-4f6d-4d3f-854e-67725212196d" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/277221e4-313a-4733-ae28-bddbdcbe886f" />



Generate Deploy pipeline script::
====================================




<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bd9d8f5e-9f72-405a-9b9f-ee5469565917" />




Script::
=======

pipeline
{
    agent any

    tools{

        maven 'maven'
    }

stages{
stage('Git checkout'){

    steps{

        git branch: 'main' url: 'https://github.com/srinfotechbatch4/Petclinic.git'

    }
}

stage('clean and install'){

    steps{

      sh 'mvn clean install'

    }
}

stage('Package'){

    steps{

      sh 'mvn package'

    }
}

stage('Archive the Artifacts'){

    steps{

      sh 'mvn clean install'
    }
    post{
        success{

            archiveArtifacts artifacts: '**target/*.war'
        }
    }

    }


stage('Test Cases'){

    steps{

      sh 'mvn test'

    }
}


stage('Deploy to tomcat server'){

    steps{

      deploy adapters: [tomcat9(credentialsId: 'tomcat9credentials', path: '', url: 'http://localhost:8080/')], contextPath: 'SRINFOTECH', war: '**/*.war'

    }
}

}
}



19/02/2026::
=============


Integrate Jenkins with Tomcat using Declarative Approach::
============================================

To integrate Jenkins with Tomcat using the Declarative Pipeline approach, you'll be using Jenkins Pipeline syntax to automate the deployment process to a Tomcat server. This process typically involves building the application, packaging it, and then deploying it to Tomcat.

1. Jenkinsfile Configuration (Declarative Pipeline)

In your Jenkins project, you'll create a Jenkinsfile, which contains the Declarative Pipeline syntax. This file defines the steps involved in the CI/CD pipeline.

Please execute below script in jenkins pipeline job using Declarative style


Spring-Petclinic::
=====================


pipeline

{
    agent any

    tools{

        maven 'maven'
    }

stages{

stage('Git checkout'){

    steps{

        git branch: 'main', url: 'https://github.com/srinfotechbatch5/Petclinic.git'

    }
}

stage('clean and install'){

    steps{

      bat 'mvn clean install'

    }
}

stage('Package'){

    steps{

      bat 'mvn package'

    }
}

stage('Archive the Artifacts'){

    steps{

      bat 'mvn clean install'
    }
    post{
        success{

            archiveArtifacts artifacts: '**target/*.war'
        }
    }

    }


stage('Test Cases'){

    steps{

      bat 'mvn test'

    }
}


stage('Deploy to tomcat server'){

    steps{

      deploy adapters: [tomcat9(credentialsId: 'tomcat9credentials', path: '', url: 'http://localhost:8080/')], contextPath: 'SRINFOTECH', war: '**/*.war'

    }
}

}
}



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/96c7b15e-5cb4-4fb5-b7f9-9c75df840eb6" />




<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d3fa033c-987c-44d7-ac92-b6f73c5605f4" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dd0cd2c4-695d-426e-af04-63674a7006dc" />




Onlinebookstore::
=============

 pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'master', url: 'https://github.com/srinfotechbatch5/onlinebookstore.git'
            }
        }
        
          stage('Build') {
            steps {
               bat 'mvn clean install'
            }
        }
         stage('Generate Artifacts') {
            steps {
               archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
            }
        }

          stage('Deploy to Tomcat Server') {
            steps {
               deploy adapters: [tomcat9(alternativeDeploymentContext: '', credentialsId: 'Tomcat', path: '', url: 'http://localhost:8080')], contextPath: 'SR INFOTECH SOLUTIONS PVT LIMITED', war: 'target/*.war'
            }
        }
    }
}





<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e5b7f0d0-0344-4451-9e51-fe7b78064b3e" />





<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/00a87812-0eae-496c-a4bf-e3b1a0a70d20" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0992ca46-4198-4712-8a58-db224a162b48" />


DevOps Web Application::
===========================


pipeline{

    agent any

    stages{
        
        stage('Clone Project'){

            
            steps{
               
                git branch: 'feature/2026.02.13', url: 'https://github.com/srinfotechbatch5/devOpsWeb.git'
           
            }
        
        }
       
        stage('Build'){

           
            steps{

                
                bat 'mvn clean install'
            
            }
       
        }

       
        stage('Test'){

          
            steps{

               
                bat 'mvn test'
            
            }
        
        }

        
        stage('Package'){

            
            steps{

                
                bat 'mvn package'
            
            }
       
        }


        
        stage('Generated Artifacts'){

           
            steps{

              
                archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
            
            }
      
        }

       
        stage('Deploy'){

           
            steps{

               
                deploy adapters: [tomcat9(alternativeDeploymentContext: '', credentialsId: 'TomcatCredentialsNew', path: '', url: 'http://localhost:8080/')], contextPath: 'DevOpsWebApplication', war: 'target/*.war'
            
            }
       
        }
    
    }

}


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/17bc3292-f437-4d44-b620-78da4bbed840" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3d416415-a7f4-4a5a-ae64-e6cbae0636c2" />



20/02/2026::
=================


Introduction to SonarQube::
================================

SonarQube is an open-source platform developed by SonarSource that is used for continuous inspection of code quality. It helps developers and development teams identify bugs, code smells, vulnerabilities, and duplication in their codebases across multiple programming languages.

Key Features of SonarQube
Static Code Analysis
SonarQube analyzes source code without executing it, detecting issues like:

Bugs

Vulnerabilities

Code smells (bad design or coding practices)

Duplications

Technical debt


Sonarqube Integrate With Jenkins::
==================================


<img width="1807" height="787" alt="image" src="https://github.com/user-attachments/assets/9037fe12-2960-4752-a7d6-cdebea6dd90e" />



Sonarqube installed link::

https://gist.github.com/dmancloud/0abf6ad0cb16e1bce2e907f457c8fce9


Sonarqube Previous Version 25.8.0.112029::
========================================

https://github.com/SonarSource/sonarqube/releases/tag/25.8.0.112029

Run the Sonarqube::
===================

once unzip the file and go to bin folder and navigate to cmd(command line)

>StartSonar.bat

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/efb0b9fc-f173-4544-9d59-23d9ec9b0c23" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/35e94765-6417-467d-bbd0-b17fa46ec1db" />


default U/P ---admin/admin

default port number:: 9000

Server URL: URL to your SonarQube instance (e.g., http://localhost:9000). and default port is 9000

To integrate SonarQube with Jenkins, you need to ensure that Jenkins can communicate with your SonarQube server to perform static code analysis during your CI/CD pipeline. This will allow you to analyze your code quality and get reports from SonarQube as part of your build process.

Here's how you can integrate SonarQube with Jenkins:please follow below steps

1. Install the SonarQube Plugin in Jenkins
Before you start, ensure that you have the SonarQube Scanner Plugin installed in Jenkins:


Go to Jenkins Dashboard.

Click on Manage Jenkins → Plugins.

Go to the Available tab, and search for SonarQube Scanner.

Install it and restart Jenkins.

2. Configure SonarQube in Jenkins

Next, you need to configure SonarQube on Jenkins so it can communicate with your SonarQube server.



23/02/2026::
==============


Steps:
=====
Go to Jenkins Dashboard.
Click on Manage Jenkins → Configure System.
Scroll down to the SonarQube servers section and click Add SonarQube.

Fill in the following details:
=======================
Name::: Give your SonarQube instance a name (SonarQubeServer).
Server URL: URL to your SonarQube instance (e.g., http://localhost:9000). and default port is 9000
Server Authentication Token: You can generate a token in SonarQube by navigating to My Account → Security → Generate Tokens. Paste this token into Jenkins.
Click Save.

3. Configure the SonarQube Scanner in JenkinsSteps:
 ===============================================
In the Configure System page, scroll to the SonarQube Scanner section.
Click Add SonarQube Scanner and select SonarQube Scanner for Jenkins.

If you want to use a custom installation, specify the path to the SonarQube Scanner binary.
Click Save.

 Configure SonarQube Project::
 ========================
Go to your SonarQube server (e.g., http://localhost:9000).
Create a project or use an existing one.
Obtain the Project Key from the SonarQube project and update the pipeline script as shown in the sonar.projectKey parameter.

Go to Projects and click Local project

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/2e63be88-e670-4114-8b5c-93e07584f2bc" />


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/91fad37f-6ac4-4122-983c-8f5796f1530e" />


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/a719339c-e372-44e5-885f-668dccf142ad" />


Click Next


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/873ad6d9-e1f1-4358-94dc-a66eb0bef912" />



Selected Use the global setting



<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/3c919465-78a5-48c8-9d1b-f9b6e5fa9cb5" />


Click Create Project

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/c1c32490-9feb-4778-9d30-045a8ef690c5" />

Project created successfully

Now Spring-petclinic Project created in Sonarqube



<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/413c6966-ad2a-4e73-8564-16124ef0e7da" />


Click Locally


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/ce45d793-ba57-4a11-839e-0597a7a9d58d" />


Click Generate for Token


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/577aa7fd-47a2-4825-a7cb-4b9ed9762b69" />


Analyze "spring-petclinic12": sqp_0eb364758c5186bea4077eff841ddb99ba89a3ab



Click Continue

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/a13815c9-7a04-4d51-8d2b-735960a78ec9" />


Selected Maven and copy below script from sonarqube and it will help to integrate Sonarqube with jenkins pipeline



<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/577aa7fd-47a2-4825-a7cb-4b9ed9762b69" />


Analyze "spring-petclinic12": sqp_0eb364758c5186bea4077eff841ddb99ba89a3ab

Using this token integrate with Jenkins

mvn clean verify sonar:sonar \
  -Dsonar.projectKey=spring-petclinic \
  -Dsonar.projectName='spring-petclinic' \
  -Dsonar.host.url=http://localhost:9000 \
  -Dsonar.token=sqp_0eb364758c5186bea4077eff841ddb99ba89a3ab


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/2bbc2019-9ff1-4879-8ef0-bd365d040ec4" />



Install sonarqube plugin

Go to manage Jenkins ---plugins

SonarQube Scanner


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/9ab9a0cc-2e50-4eca-b9ee-fc493c5712f9" />


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/545794cd-e22a-46fe-bf98-cdf220b676f6" />



Go to System Configuration


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/f5cf5ce8-7a1c-42ac-92a3-159d875d68e0" />


SonarQube servers

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/448b0cf4-5962-4490-bbd8-9a22cce87947" />


Provide the Server URL


Provide the sonarqube token which we created in sonarqube



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c8d6699f-cced-4b0c-9c18-1fc9cf8aabb9" />


need to add credentials at manage jenkisn -- Credentials


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/86c12f3f-a7fa-4eea-a084-3fd112becc78" />



Select Secret text

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/398b0064-5ad5-4efd-a7a6-678c490a1668" />


Copy secret token key

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/aca484b6-167c-4427-930b-e870424c0ed6" />


Click Create



<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/06acbdf8-4447-4125-a849-031033715253" />


Now go to manage Jenkins - System configuration and select the credentials now


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/0def4626-3d17-4c1d-b4a8-16c366bd726e" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b4c54b9f-04a3-4fd4-be4b-e4b6eb5534c8" />



 IntegrateSonarqubeWithJenkins::
  ==================================

  Go To jenkins and create new job IntegrateSonarqubeWithJenkins


<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/e0c8f57e-e0b0-4887-bf24-da6af9daab2a" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b6b00394-3a60-47fe-9ff6-4dcc105b3453" />



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dcbef5f5-5cb8-4ccf-b18f-c2c1a166f31f" />



Please use below script to run the pipeline job


pipeline {
    agent any
    
    tools{
        
        maven 'Maven'
    }

    stages {
       
        stage('Clone the Project') {
          
            steps {
            
               git branch: 'feature/2026.02.18', credentialsId: 'githubcredentials', url: 'https://github.com/srinfotechbatch5/Petclinic.git'
            }
        }

        stage('Build the Project') {
           
            steps {
             
               bat 'mvn clean install'
            }
        }

         stage('Tests') {
           
            steps {
             
               bat 'mvn test'
            }
        }
        
         stage('Generate the Junit test results'){
            
           
            steps{
            
              junit 'target/surefire-reports/*.xml'
            }
        }
        
         stage('Sonarqube Analysis') {
          
            steps {
              
              bat 'mvn package'
             
              bat '''mvn sonar:sonar \
              
              -Dsonar.projectKey=spring-petclinic \
            
               -Dsonar.projectName='spring-petclinic' \
              
                -Dsonar.host.url=http://localhost:9000 \
              
                 -Dsonar.token=sqp_4c5f65664adfb4af0a9eef6f9c67d07e390ab18c'''
            }
        }

        stage('Artifact Publisher') {
          
            steps {
               
               archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
            }
        }

         stage('Deploy to Tomcat Server') {
           
            steps {
              
               
               deploy adapters: [tomcat9(alternativeDeploymentContext: '', credentialsId: 'Tomcatcredetials', path: '', url: 
               
               'http://localhost:8080/')], contextPath: 'SRINFOTECHSOnarTest', war: 'target/*.war'
            }
        }
    }
}



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/aaae3049-ddf8-48e1-8742-037672cb6b76" />

 

1. please start Jenkins on your machine & make sure Jenkins server is UP & Running state

2. please start Tomcat on your machine & make sure Tomcat server is UP & Running state

3. please start Sonarqube on your machine & make sure Sonarqube server is UP & Running state

once above steps done then we can execute below script

Working Scripts CI/CD::
===========================

pipeline{

    tools{

        maven 'Maven'
    }
agent any

stages{

    stage('Clone'){

        steps{

            git branch: 'main', url: 'https://github.com/srinfotechbatch5/Petclinic.git'
        }
    }

     stage('Build') {
            steps {
               bat 'mvn clean install'
            }
        }

         stage('Test Cases') {
            steps {
               bat 'mvn test'
            }
        }

         stage('Archive the Artifacts') {
            steps {
               archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
            }
        }
 stage('Sonarqube Analysis') {
            steps {
               
               bat 'mvn package'
              bat '''mvn sonar:sonar \
             -Dsonar.projectKey=spring-petclinic \
             -Dsonar.projectName='spring-petclinic' \
            -Dsonar.host.url=http://localhost:9000 \
            -Dsonar.token=sqp_96cf5222ab632b69c14baa5590210a7125185d5a'''
            }
        }


 stage('Deploy Application into Tomcat Server') {
            steps {
               deploy adapters: [tomcat9(alternativeDeploymentContext: '', credentialsId: 'NewTomcat', path: '', url: 'http://localhost:8080/')], contextPath: 'Test', war: 'target/*.war'
            }
        }

}

}


Once sonarqube scanner done, please verify the sonarqube dashboard for reports & results


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/06b0b6d2-4331-415c-8125-800e1d82daec" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a64f6c27-24d6-43ab-ad60-fbefcff1409e" />



03/03/2026::
================

Go to Administration


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8e86ab58-c2d9-4f3f-8414-952691a065f0" />



Click Projects & Select Background Tasks



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/94fa5e45-c471-4f66-aa89-ae873b249045" />


You can able to see all scanned projects status


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c2a79822-d630-4580-bee2-62fef19b4bca" />


Click on any Project, see the PASSED the quality gates

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0290f00a-4a0d-4777-b86e-165a8ee79def" />


Click on Overall Code option


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4dc3dfe0-bbd4-4cd1-9d55-d55358dc0cd4" />



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f8ed7afb-8eeb-4545-8531-555deb3c7399" />


see the results

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a8e59901-9660-4d20-bf87-d155bc032c32" />


here Code coverage is 

Coverage
82.7%

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0b040b6c-06ce-4073-8afd-74eb7e4a7046" />


NOTE:: Coverage is greater than or equal to 80.0%, this should be maintained minimum % every project

NOTE:::Duplicated Lines (%) is less than or equal to 3.0%



Create My own Quality Gates::
=======================

Go to Dashboard click on Quality Gates


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/810db00e-fa99-47a2-8ee4-3a5901adfdd1" />


at left side we can see create & just click on it


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e376671e-2228-435a-8765-288978270066" />



Provide the Name & Click Create



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8206d4e2-de26-4192-a7f6-0589fdf804ab" />



Your own quality gates are created



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/424db715-3699-4ce8-973a-e0f89263db00" />


this is your own quality gates


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/73282057-4963-45e4-af8b-5d5d9eb57587" />


nditions on New Code

Metric

Operator

Value

Issues

is greater than

0

Security Hotspots Reviewed

is less than

100%

Coverage

is less than

80.0%


Duplicated Lines (%)

is greater than


select your project


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8bcc158c-e0cc-4a96-a67b-f35b72fa2fc2" />


apply the Grant permissions to a user or a group



Apply all the permissions & click Add


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d4b37339-5fa7-4af7-81eb-4ef8840c817e" />



Create my own Quality Profile::
================================

go to Quality Profiles



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f702ea7f-9575-4226-9ce6-8748b8f840d9" />



select Language


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/681c75fc-aeab-4860-8682-2d2a906b7ce1" />



total java Rules 527


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8ed172c6-5a47-401d-9def-120f5273a261" />




at right saide top click create


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/35d49178-73ec-4885-a321-a4decdc9966b" />



provide the Language & Name and click Create


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f847eabd-44c0-430d-8be9-bfcb6ee588cc" />




your own profile





click Active More rules



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3fa4cfc7-ebe2-4a78-b7a8-bcd61b34fe14" />



Bulk Change

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ca31eb46-4ca1-4767-b856-7ef2914b7d55" />



Activate In Spring-pipeline project


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b01d5015-11fc-4ee3-8b42-6b68fcf8d010" />



Sure Apply





Succcessfully Applied my own quality profile rules

Activate In Quality Profile (680 rules)





Now we are successfully onboarded spring-petclininc project to Sonarqube server



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/304cc022-c9c3-4af6-a98f-0970ab7b999e" />



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d562ceec-487e-4d65-8e47-a5589dbccb77" />



Running the Pipeline Once the pipeline is configured, Jenkins will execute the SonarQube analysis during the build process. After the build completes, you can view the analysis results in your SonarQube dashboard.



Code coverage Code smells Bugs Vulnerabilities Duplications These reports will be available in the SonarQube dashboard for your project.


05/03/2026::
=============

Jfrog Artifactory Overview::
========================


JFrog Artifactory is a universal artifact repository manager that serves as a central hub for storing, managing, and distributing software artifacts, binaries, packages, and other assets throughout the software development lifecycle, improving automation, and ensuring release integrity.

<img width="1804" height="720" alt="image" src="https://github.com/user-attachments/assets/12b4d23a-5f16-4d6a-821d-f0b4aa315b8d" />



Artifact Repository Management:

Allows for storing binaries and artifacts (e.g., libraries, packages, Docker images) in a centralized location.
Supports all major package types (e.g., Maven, Gradle, npm, NuGet, RubyGems, etc.).
Version Control:

Helps in managing versions of your artifacts and ensures the correct version is used during builds and deployments.
Integration with CI/CD:

Integrates seamlessly with CI/CD tools like Jenkins, Bamboo, GitLab CI, and others.
Enables automated publishing of artifacts as part of your continuous integration pipeline.
Access Control & Security:

Provides fine-grained access control and permissions for users and groups.
Supports user authentication, security, and audit trails to ensure compliance and secure artifact management.
Replication:

Allows you to replicate artifacts across multiple Artifactory instances, ensuring high availability and disaster recovery capabilities.
Remote Repositories:

Artifactory can proxy remote repositories, allowing you to cache and fetch external dependencies without re-downloading them each time.
Promotion & Release Management:

You can "promote" artifacts from one repository to another (e.g., from a development repository to a production repository), allowing for better control over releases.
Multi-Platform Support:

Artifactory supports multiple programming languages and platforms, making it a universal solution for managing software dependencies and releases.

AWS (Amazon Web Services)::
========================

Create AWS Free tier Account::
====================================
Please go throw the recorded video session and follow the steps to create the free tier AWS account.Let me know if anyone facing any issues.

Amazon Web Services (AWS) is a comprehensive and widely adopted cloud platform offered by Amazon. It provides a broad set of services to help organizations and individuals build and scale applications, manage data, and process workloads in the cloud. AWS is designed to provide flexible, scalable, and cost-effective solutions for computing, storage, networking, machine learning, and much more.



Step-by-Step: Create an AWS Free Tier Account


Go to the AWS Free Tier page

👉 https://aws.amazon.com/free


Click “Create a Free Account”

This takes you to the AWS sign-up page.


Enter your email and choose a password


Email address (must be unique, not tied to an existing AWS account)


Strong password


AWS account name (any name you choose)




Verify your email


AWS sends a verification code to your email.


Enter that code on the site to continue.




Choose the account type


Personal (for individuals)


Professional (for company use)




Enter your contact and payment info


Full name, address, and phone number.


Credit/debit card details (for identity check; AWS may make a temporary $1 charge).




Phone verification


Choose “Text message” or “Voice call.”


Enter the code AWS sends to confirm your number.




Select a Support Plan


Choose the Basic Support – Free option.




Sign in to the AWS Management Console


Go to https://console.aws.amazon.com


Log in using your email and password.



06/03/2026::
================


Integrate Jfrog with Jenkins::
=================================


<img width="1800" height="766" alt="image" src="https://github.com/user-attachments/assets/a6931951-8047-4ac8-8a93-7886e2be2d6b" />


First Step:: 
https://jfrog.com/download-jfrog-platform/  ---download url


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f694c6a3-7536-4ee7-a329-a0b93619398d" />


previous versions link

https://jfrog.com/download-legacy/?product=artifactory&version=7.104.12

All zip version and search 6.12.1 OSS version

https://releases.jfrog.io/artifactory/bintray-artifactory/


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e93e14fa-031d-4e66-8633-3e42028994bb" />



jdk compatibility version with jfrog is::
=============================================
 
JDK 12.1.0
 
https://www.oracle.com/in/java/technologies/javase/jdk12-archive-downloads.html
 
artifactory-oss-6.12.1
 
All zip version and search 6.12.1 OSS version
 
https://releases.jfrog.io/artifactory/bintray-artifactory/


Start Jfrog::
==============

Go to downloaded the Jfrog And UNZIP the file

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7591ffda-52a2-40e4-b88f-caf0cd23f6e3" />


Go to bin folder


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5f7f2be2-5a27-42da-bab8-e4782721560a" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/53d5d275-c25d-4629-8dcd-93bfbf87b00e" />

You should be found the artifactory.bat

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2b868a0f-94c5-4b4a-a0b0-d963e8654c19" />

select the  path and navigate to cmd (command line interface)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4e298ab3-c875-4be5-85e9-4026d05af6e2" />

run the jfrog

artifactory.bat

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/37ac18aa-f2f8-42e3-90ba-55e749806f66" />



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/06c69910-fb20-4199-a439-1e18b06a8419" />


Jfrog Script::
===============

stage ('Artifactory Server'){
           
            steps {
               
               rtServer (
               
                 id: "Artifactory",
                
                 url: 'http://localhost:8081/artifactory',
               
                 username: 'admin',
               
                  password: 'password',
                
                  bypassProxy: true,
                   timeout: 300
                        )
            }
        }
        stage('Upload'){
           
            steps{
               
                rtUpload (
               
                 serverId:"Artifactory" ,
                 
                  spec: '''{
                 
                   "files": [
                    
                      {
                   
                      "pattern": "*.war",
                   
                      "target": "srinfotech-batch4"
                      }
                            ]
                           }''',
                        )
            }
        }
        stage ('Publish build info') {
           
            steps {
               
                rtPublishBuildInfo (
                  
                    serverId: "Artifactory"
                )
            }
        }


installed plugin for artifactory plugin (Jfrog)::
 ==========================================

Please install below Artifactory plugin in Jenkins

Artifactory Plugin  Version4.0.8


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2c80456a-0059-40ba-9336-3e650698582d" />



After installed Artifactory plugin 

Go to Manage Jenkins--> System configuration find JFROG


 <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2f99ff52-e8cc-4be4-ad5f-83a9ae3a1ae7" />


Click JFrog Platform Instances


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e3b375cb-09ac-4386-83af-e36a29fdff72" />


Server ID::

Artifactory

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3e9a5f12-18d2-4f31-982a-ceec4ba19164" />


JFrog Platform URL::

http://localhost:8081/artifactory


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bc977212-b557-43e0-92d0-3a0b000b06fd" />


Credentials::


For user name and password


Default Jfrog U/P----admin/password


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/da3bab2c-459b-4e57-9fbe-be35d3dfde28" />



Allow HTTP Connections:: should be checked 


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b04be3f8-5a89-4167-8775-83b0999bae71" />



I need to setup target in Jfrog::
==================================

srinfotech-batch4


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c0717c8e-62a4-4718-8aca-440ab48341d8" />


click Local repository


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/38c881aa-d9aa-46e1-83db-ec9a169c52ad" />


Select maven


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/71ab8e03-d055-4cd6-8174-6e17a4543c6a" />


Repository key  :::: srinfotech-batch4


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6e1bf2a6-0fd8-49a2-b7b4-c3c70b9e716b" />


Click save and finish


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/41e78a2e-2977-46ae-8b1c-27b9ad262e60" />



Go to artifacts and check repository is created with name -srinfotech-batch4



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a9cf1395-7fc7-4097-a1eb-ee28a566f8df" />



CI/CD all tools ans stages script:: create new job in jenkins and execute below script 
====================================================================================


pipeline{

agent any
 
tools{
 
    maven 'Maven'
}
 
stages{
  
    stage('Clone The Project'){
        
        steps{
           
            git branch: 'feature/2025.10.28', url: 'https://github.com/srinfotechbatch4/Petclinic.git'
        }
    }
    stage('Build'){
        
        steps{
             bat 'mvn clean install'
        }
    }
     stage('Test'){
       
        steps{
             bat 'mvn test'
        }
    }
     stage('Generated the test reports'){
        
        steps{
             junit 'target/surefire-reports/*.xml'
        }
    }
     stage('published the Artifacts'){
        
        steps{
            archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
        }
    }
 
    stage('SonarQube Analysis'){
        steps{
        bat 'mvn package'
      bat '''mvn sonar:sonar \
 
  -Dsonar.projectKey=spring-petclinic \
 
  -Dsonar.projectName='spring-petclinic' \
 
  -Dsonar.host.url=http://localhost:9000 \
 
  -Dsonar.token=sqp_b4f05b06814df65b8d3f1a467f3ed604e2dadb03'''
        }
    }
 
stage ('Artifactory Server'){

            steps {
            
               rtServer (
               
                 id: "Artifactory",
                 
                 url: 'http://localhost:8081/artifactory',
                 
                 username: 'admin',
                 
                  password: 'password',
                  
                  bypassProxy: true,
                  
                   timeout: 300
                   
                        )
            }
            
        }
        stage('Upload'){
        
            steps{
            
                rtUpload (
                
                 serverId:"Artifactory" ,
                 
                  spec: '''{
                  
                   "files": [
                   
                      {
                      
                      "pattern": "*.war",
                      
                      "target": "srinfotech-batch4"
                      
                      }
                      
                            ]
                            
                           }''',
                           
                        )
            }
            
        }
        stage ('Publish build info') {
        
            steps {
            
                rtPublishBuildInfo (
                
                    serverId: "Artifactory"
                )
                
            }
            
        }
 
 
    
    stage('Deploy to Tomcat Server'){
    
        steps{
        
            deploy adapters: [tomcat9(alternativeDeploymentContext: '', credentialsId: 'tomcatcredential', path: '', url: 'http://localhost:8080')], contextPath: 'SRInfotechSpringpetclinicJfrog', war: 'target/*.war'
        }

        
    }
    
}

}



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/427cdbd3-ef3b-493a-b97c-fe9b432fd870" />


Successfully Published the Artifact to Jfrog Artifactory 


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/126066df-fae0-402b-98cd-1bd74996eea2" />



09/03/2026::
===============


AWS (Amazon Web Services)::
====================

Amazon Web Services (AWS) is a comprehensive and widely adopted cloud platform offered by Amazon. It provides a broad set of services to help organizations and individuals build and scale applications, manage data, and process workloads in the cloud. AWS is designed to provide flexible, scalable, and cost-effective solutions for computing, storage, networking, machine learning, and much more.

AWS ---Amazon web services

compute services::

Amazon EC2 (Elastic Compute Cloud): Provides scalable virtual servers to run applications.

AWS Lambda: Lets you run code without provisioning or managing servers. It automatically scales based on usage.

Storage services::

Amazon S3 (Simple Storage Service): Object storage for storing and retrieving large amounts of data.

Amazon EBS (Elastic Block Store): Persistent block-level storage for EC2 instances.

Database::

Amazon RDS (Relational Database Service): Managed relational database service supporting multiple database engines (e.g., MySQL, PostgreSQL, MariaDB, etc.).

Amazon DynamoDB: A managed NoSQL database service.

Amazon Aurora: A high-performance relational database engine compatible with MySQL and PostgreSQL.

Network services::

Amazon VPC (Virtual Private Cloud): Lets you create isolated networks within AWS for secure connections.

Security ::

AWS IAM (Identity and Access Management): Controls user access and permissions for AWS resources.

AWS KMS (Key Management Service): Managed service for creating and controlling encryption keys.

Security groups ---inbound, outbould roles


Containers & kuberneties::

ECS  ---elastic containers servcies

EKS  ----estastic kuberneties services

AKS  ---Azure kuberneties services

Cloud watch --Metrics Monitoring

CloudWatch Metrics allows you to track the performance and utilization of AWS resources such as EC2 instances, RDS databases, Lambda functions, S3 buckets, and much more.
These metrics include CPU utilization, disk activity, network traffic, and others. You can create custom metrics for your applications or services as well.

cloud trail ---Security Monitoring:

Use CloudTrail logs to detect unauthorized access or activity in your AWS environment. You can track changes in security settings, unauthorized API calls, or unexpected configuration changes.

Developer Tools::

AWS CodeCommit: Source control service for managing your code repositories.

AWS CodeDeploy: Automates code deployments to EC2 instances and Lambda.

AWS CodePipeline: Continuous integration and continuous delivery (CI/CD) service for automating the release pipeline.


10/03/2026::
=============


AWS EC2 ::
===========

Amazon Elastic Compute Cloud (Amazon EC2) is one of the core services provided by Amazon Web Services (AWS)

Wide Variety of Instance Types:

EC2 instances are grouped into families based on the type of workload they are optimized for. Some common instance families include:

General Purpose: e.g., t3, m5 instances (balanced CPU, memory, and networking).

Compute Optimized: e.g., c5 instances (great for high-performance computing tasks).

Memory Optimized: e.g., r5, x1e instances (designed for high-memory workloads like databases).


Master & Node communication Via SSH keys::
============================================



<img width="1720" height="771" alt="image" src="https://github.com/user-attachments/assets/302c319f-5a53-4179-89fc-26d1d05d9a83" />



create EC2 Ubuntu Linux Machine in AWS::
==================================

Go to AWS and Search EC2


https://aws.amazon.com/console/


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b74d26eb-e006-4a8c-bdd1-c6ad61a5317c" />


Sign in to console


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/127fa406-6cb4-4531-bf35-21e4d8b0fd45" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4d5b19c0-19de-4328-b0df-05d959f5bd38" />


Sign in using root user email


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/54dd429a-9645-4694-b672-e0f09c08e9fb" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/62f78211-1898-4291-ab4c-140d3d543af5" />

Click EC2

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7d3db337-a36a-403c-8d61-0924ef82fa41" />


Go to instances at left side bar

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/42d33ae6-1b84-4934-bc5b-df0122473433" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7197ab92-5618-4872-9d3d-988d7d468d43" />



Click Launch Instances, EC2  ---> Instances  -----> Launch an instance

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2e7cb8fb-a19f-4329-832b-7e2a9df13b16" />


Select Ubuntu

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/be45dcf1-7819-4f7c-bbeb-520eb9c6c7c4" />


Select Amazon Machine Image (AMI)


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/de98facb-13b6-497e-af1e-940a4c3c473a" />



select Instance type,t2 medium


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/74b8b230-3e56-45d6-b2bf-31161447265b" />



Create new key pair and provide key pair name


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bbcf96b5-15de-4242-b582-e323c915c077" />


click create pair

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/05a3b15d-577e-49cc-a256-df090e685fe3" />


click launch instance

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d13215e0-a952-46b4-9eb2-ed0d4636e29d" />


instance will be created

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d8335ca6-e57c-4b23-8a4d-cd6271d85f63" />




<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ae686a03-6233-4a68-88ea-688b513a4eac" />



2 Ubuntu Machines Running Success

1.Master

2.Node


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/22d8560e-5e72-4b48-933e-c4e618779b9c" />



Master & Node communication Via SSH keys::
================================

i have to create 2 EC2 ubuntu machines in AWS

1. Jenkinsmaster

2. Node




<img width="1478" height="720" alt="image" src="https://github.com/user-attachments/assets/c2d9271e-ef7e-4795-a337-3a4652b49527" />


we have already .pem file dowloaded in you local machin

right click from .pem and click Open git bash here option

Now Go to AWS Ubuntu machine which is already created in AWS insatnces and select master machine

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/69c4bd3c-fb96-4e34-93ce-bb3ab176f5e4" />


Click Connect

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/608b56e0-275b-4854-a135-2f54886dd0ea" />


Click SSH Client

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5cf59bd9-ec79-446c-96eb-e36e05c17a2a" />


Copy URL

>ssh -i "Batch4.pem" ubuntu@ec2-18-237-178-192.us-west-2.compute.amazonaws.com

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e5cd3cef-ad51-4604-8e02-b74981dec51c" />


Now past that url in Gitbash

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/327cb240-6f1f-4b6a-8db5-718510aab388" />


switch to root user below command run

>Sudo -i

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/47049e39-538e-4a1e-8810-36c90abbed3b" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/51bd5a55-81ce-4fff-84df-f8ad2e20fedb" />


update the all packages ,please run below command

>sudo apt-get update

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c5486332-2033-4550-a134-c556657debfc" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3b76e193-7495-4fb8-9cce-37f2a6732f16" />


Install JDK
============

>sudo apt install openjdk-17-jdk

Insatll Jenkins on master machine::
========================================

https://www.digitalocean.com/community/tutorials/how-to-install-jenkins-on-ubuntu-22-04

https://phoenixnap.com/kb/install-jenkins-ubuntu



 <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f7616668-c44b-4079-b4cc-82f3a5bc86fb" />

 
 

24/03/2026::
=============


Master & Node communication Via SSH keys::
================================

i have to create 2 EC2 ubuntu machines in AWS

1. Jenkinsmaster

2. Node




<img width="1689" height="738" alt="image" src="https://github.com/user-attachments/assets/26a2c9ad-ea97-4755-9094-c2a0e2f15296" />



we have already .pem file dowloaded in you local machin

right click from .pem and click Open git bash here option

Now Go to AWS Ubuntu machine which is already created in AWS insatnces and select master machine

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/69c4bd3c-fb96-4e34-93ce-bb3ab176f5e4" />


Click Connect

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/608b56e0-275b-4854-a135-2f54886dd0ea" />


Click SSH Client

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5cf59bd9-ec79-446c-96eb-e36e05c17a2a" />


Copy URL

>ssh -i "Batch4.pem" ubuntu@ec2-18-237-178-192.us-west-2.compute.amazonaws.com

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e5cd3cef-ad51-4604-8e02-b74981dec51c" />


Now past that url in Gitbash

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/327cb240-6f1f-4b6a-8db5-718510aab388" />


switch to root user below command run

>Sudo -i

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/47049e39-538e-4a1e-8810-36c90abbed3b" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/51bd5a55-81ce-4fff-84df-f8ad2e20fedb" />


update the all packages ,please run below command

>sudo apt-get update

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c5486332-2033-4550-a134-c556657debfc" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3b76e193-7495-4fb8-9cce-37f2a6732f16" />


Install JDK & Maven:;
============

JDK link

https://bluevps.com/blog/how-to-install-java-on-ubuntu

MAven link

https://phoenixnap.com/kb/install-maven-on-ubuntu



>sudo apt-get install maven

>java -version

>mvn -v

Set java home environment 

>sudo vi /etc/environment

JAVA_HOME=”/usr/lib/jvm/java-8-openjdk-amd64/jre”

MAVEN_HOME=”/usr/share/maven”

Reload your system environment

>source /etc/environment

Veriy the variables was set correctly

>echo $JAVA_HOME

>echo $MAVEN_HOME


Class Note::
=============

after installed jdk17 & Maven you should be setup the environemnt variabels in ubuntu
 
 
 >sudo vi /etc/environment
 
 1.press i from your keyboard

 2.press esc from your keyboard
 
 3.swift+:

 4.wq

 5.press enter from your keyboard
 
 Maven home: /usr/share/maven
 
 java home:: /usr/lib/jvm/java-17-openjdk-amd64
 
 
JAVA_HOME="/usr/lib/jvm/java-17-openjdk-amd64"

MAVEN_HOME="/usr/share/maven"




Insatll Jenkins on master machine::
========================================

https://www.digitalocean.com/community/tutorials/how-to-install-jenkins-on-ubuntu-22-04

https://phoenixnap.com/kb/install-jenkins-ubuntu


In AWS any machines default passwordauthentication is disabled , 
we need to enabled in any linux machines::
=========================================


>sudo vi /etc/ssh/sshd_config

>sudo service sshd restart

In EC2 – by default password based authentication is disabled so we need to enabled::
==================================================

>sudo vi /etc/ssh/sshd_config

passwordauthentication :yes

![image](https://github.com/user-attachments/assets/99decb00-3ef0-4528-8e58-0d69bf14ce36)

In ubuntu machine default user is not sudo user,you should make user as a sudo user
>visudo


# Allow members of group sudo to execute any command

Jenkins ALL=(ALL:ALL) NOPASSWD:ALL

>su Jenkins

Switching to new user

![image](https://github.com/user-attachments/assets/86bc74b0-e31f-44aa-bcab-875ed9a3a016)

![image](https://github.com/user-attachments/assets/98b96a48-2ee3-466c-b917-26c1919b15f6)

Once installed Jenkins successfully

>we need to enabled the Inbounds and outbounds rules in AWS security groups

Inbounds rules

![image](https://github.com/user-attachments/assets/b7075d75-dd60-42d4-a282-7be861252685)

Copy public IP address and go to browser

Access Jenkins using Public IP address

http://35.86.160.156:8080/

bydefault Jenkins runs on port 8080

Jenkins home path/var/lib/Jenkins

How to change the port number in Jenkins::

https://stackoverflow.com/questions/28340877/how-to-change-port-number-for-jenkins-installation-in-ubuntu-12-04

>sudo nano /etc/default/jenkins


Now Go to Node Machine::
==============
Please insatll JDK & Maven in node machine and setup environemnt varibles

>sudo apt-get install maven

>java -version

>mvn -v

Set java & Maven home environment::
====================================

>sudo vi /etc/environment


1.press i from your keyboard

2.press the esc from your keyboard

3. shift+:

4. wq

5. press Enter



JAVA_HOME=”/usr/lib/jvm/java-8-openjdk-amd64/jre”

MAVEN_HOME=”/usr/share/maven”

Reload your system environment

>source /etc/environment

Veriy the variables was set correctly

>echo $JAVA_HOME

/usr/lib/jvm/java-17-openjdk-amd64

>echo $MAVEN_HOME

/usr/share/maven



>sudo vi /etc/ssh/sshd_config

PasswordAuthentication yes

NODE Machine::

1.sudo adduser node

2.user should provide the sudo permissions

>visudo

# Allow members of group sudo to execute any command

node ALL=(ALL:ALL) NOPASSWD:ALL

3.passwordauthentication is enabled


NOTE::
========
1. user should provide the sudo permissions

2. passwordauthentication should be enabled

3. run any command from /root user only


Class Note::
===============

Jenkins master::

1.java & maven need install

2.setup environemnt variabels

3.install jenkins in master machine

4.provide the sudo permission to the jenkins user

5.passwordauthentication shobe enabled

6.ssh-keygen -t ed25519  -->generated the privte & public keys

NOTE:: if authorized_keys file is there or not, if not there you shoube be create the authrized_keys file

7.copy the public/private/ keys to node machine

NOTE1:: copy the public keys to authorized_keys file

NOde::

1.java & maven need install

2.setup environemnt variabels

3.need to create the user as node--->adduser node

4.provide the sudo permission to node user

5.passwordauthentication shobe enabled



Master Node Configuration::

>got to manage Jenkins

>manage Nodes


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3d84ee12-6b57-4dc0-ab1e-eac986474db7" />


>click new node


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e4fc0210-1d58-4e8d-abce-4587b78f51b5" />

Give Node name


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bb37de5b-36c4-43ac-8f06-c2fe429ccc82" />


select Permanent Agent

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7bcfacca-9904-4d14-a5fc-6b32e8184253" />


click create


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/980d0602-42e5-4f0f-8254-53bc39f81068" />




Remote root directory

>home/node


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/465a5411-d053-4daa-91a9-04f00f3ded09" />


Launch methods via ssh

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/26c1c7df-058e-4821-b817-1ef93642a831" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/abd7b2f1-c133-4873-b6df-5a5bfb4857b3" />


Host provide the node private ip addresss


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/76d3229f-921e-4c26-b04e-bca84abbf6f6" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/215c2022-524d-40a4-b157-f539c19410f0" />


Add credentials ::

option-1::

this time please use credentials option SSH key with private key from node machine


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/04453cef-b083-4f10-928c-ba4dbb2547c3" />


select SSH key with private key

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/be6f565c-3e3c-4c39-90c5-ba9a95451573" />


provide the ID & Deccription


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b2fa28bd-70ee-4cca-800e-a7e6ae010bd2" />

User Name------> node machine user name


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8201cb00-e148-43e1-ac2c-011f5ad2c3fd" />

select private key


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7663c7ac-53bc-432c-8c75-ebe36c20d204" />

give the private key of node machine


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6bf4b79e-c102-4863-8773-356cc80e6410" />


click Add


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/27ffaf4c-f2db-49fa-9917-a02cac410e0f" />


click save


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4a97cc27-f023-4ffb-a33b-20c96bf2a9c7" />




Agent successfully connected


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8262c42d-3cc0-4152-935b-62849c13db8c" />

 

Execute Jenkins job using slave /node/agent/worker/helper 

Create one test slave job in Jenkins

>select Restrict where this project can be run


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/287a541a-e97c-4756-97ab-560efef29c0e" />


>select Label Expression


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ed5a566d-0b91-43e3-94e3-774cc2b14159" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/780c0899-4ea6-4407-a2db-4b6744f4da44" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5f5004e8-5aeb-4c64-98db-f0985491a173" />


please create 2 job in jenkins master and setup 1 job in Node machine and 2nd job master machine, just trigger Build Now 

Please observe below screenshot 2 job running different machines 

Building on the built-in node in workspace /var/lib/jenkins/workspace/master

Building remotely on SRInfotechNode in workspace /home/node/workspace/sample

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2eadd4d0-eab0-4b06-a0ca-50a50f57ae6a" />


advantage of master & Node Integration


<img width="1292" height="737" alt="image" src="https://github.com/user-attachments/assets/8420c354-0336-483a-a6d2-e96cc7685173" />



<img width="1252" height="740" alt="image" src="https://github.com/user-attachments/assets/7a62f53f-846f-45bb-8f32-008d1819238c" />


<img width="1561" height="767" alt="image" src="https://github.com/user-attachments/assets/fcfc76ac-8e62-4c18-b894-959e513d721d" />

Session NOTE:::
===================

Master & Node Communicatiion Via SSH keys::
===========================================



<img width="1689" height="738" alt="image" src="https://github.com/user-attachments/assets/18d430c1-2c09-4a27-9dd2-9ac3cd97f712" />


>sudo -i

>sudo apt update

>java --version

>mvn -v

environment setup::

Maven home: /usr/share/maven

>sudo apt install maven

Java Home::  /usr/lib/jvm/java-17-openjdk-amd64

>sudo apt install openjdk-17-jdk

>sudo vi /etc/environment

1.press i from your keyboard

2.press the esc from your keyboard

3. shift+:

4. wq

5. press Enter

>echo $JAVA_HOME

/usr/lib/jvm/java-17-openjdk-amd64

>echo $MAVEN_HOME

/usr/share/maven

>ssh-keygen -t ed25519

>su <username>

>su jenkins

>visudo
		
# Allow members of group sudo to execute any command
		
jenkins ALL=(ALL:ALL) NOPASSWD:ALL

ctrl+X

yes

enter

in aws passwordauthenticatuion is disabled , you need to enabled the passwordauthentication

>sudo vi /etc/ssh/sshd_config

PasswordAuthentication yes

NODE Machine::

1.sudo adduser node

2.user should provide the sudo permissions

>visudo

# Allow members of group sudo to execute any command

node ALL=(ALL:ALL) NOPASSWD:ALL

3.passwordauthentication is enabled

>sudo vi /etc/ssh/sshd_config

>cd ~

>ssh node@172.31.37.219


ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIOayYEJSyLHLOX25WbnoZgtL006XdmN6T5N0dlUnp7kI root@ip-172-31-44-252


--2 machines

1.master

a.java & mavne need install

b.setup environmemnt variables

c.install jenkins in master machine

d.provide the sudo permission to the jenkins user

e. passwordauthentication should be enabled

f. ssh-keygen -t ed25519 --> need to generate the keys in master

g. copy the public/private keys to Node machine

NOTE:: if authorized_keys file is there or not , if not there 

please be create both the machine

2.Node

a.java & mavne need install

b.setup environmemnt variables

c. need to create use as node-->adduser node

c.provide the sudo permission to the node user

visudo 

node ALL-(AAL:ALL) NOPASSWD:ALL

e. passwordauthentication should be enabled

if keys are copied correctly commenucation will be happend 




06/04/2026::
=============

 Docker Introductions::
=================

Docker is an opensource & Applicatuions level virtualization technology and it's called containirazition.

Docker is an open-source platform that automates the deployment, scaling, and management of applications in lightweight, portable containers. Containers are isolated environments that package an application and all its dependencies (such as libraries, binaries, and configurations) to ensure it runs uniformly across different computing environments.


<img width="1149" height="434" alt="image" src="https://github.com/user-attachments/assets/5e7b8124-090c-4c7e-8927-ebbc0dfd482c" />




Docker is a platform and that make it easier to create, deploy, and run applications using containers. Containers are lightweight, standalone, and executable units that include everything needed to run a piece of software, including the code, runtime, libraries, and system tools.

container ::
==============
1.container is an insolation area of executuions of your applications
 OR
 instance of images are called containers
2.Containers are created from “images”
3. Containers are the core of Docker. They are lightweight, portable, and isolated environments where applications run.
  Docker is run your software packages /Applications  in containers called containarizations.

4. if you build a docker container for your application called containerization
5. containers have it’s own boundaries  

who will create containers?
Ans --docker images are created the containers

 Docker Images:
 ===============

 docker image is a package with all dependencies and the necessary 
information to create the container and docker image derived from multiple base images.

An image is a snapshot of a container, a blueprint that defines what the container will contain and how it will behave when run. It consists of an application and its dependencies. Docker images are built using a Dockerfile


07/04/2026::
==============


Docker Registry::
====================

A Docker Registry is a system for storing and distributing Docker images. It is a centralized location where Docker images can be uploaded (pushed), stored, and downloaded (pulled) by users and applications. Docker images are the building blocks of containers, and registries provide a way to manage, version, and share these images across different environments.

Default registry :: https://hub.docker.com/

Physical & Virtual & Hypervisors/VMwares::
=============================================

1.tomcat & nodejs containers have it’s own process tree,own files systems,own network interfaces own storage,ram…etc
2.when you want to give application to your team/testers  docker is the best choice and when you want give system to your team/ testers VMwares are best choice.
3.application level virtulization docker is the best choice and OS level virtulization VMwares are best choice
4.individually scale the your application very easy in docker

<img width="1162" height="449" alt="image" src="https://github.com/user-attachments/assets/05494c3a-210c-4a65-a07e-59f6170d17cf" />



Example:: For festival season In your organization leave management application multiple employees are applied leaves at the same time in that scenario docker is very easy to scale the one more application but physically it’s very difficult so docker is the best choice


<img width="1162" height="449" alt="image" src="https://github.com/user-attachments/assets/4645b5bb-9c8f-485c-b2d2-bcf8a2c34fbb" />




Install Docker in Ubuntu machine::
=====================================

Please follow below link steps to install the docker in ubuntu and please read all the content in that link

https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-22-04

once installed docker please verify below commands::

>docker --version

root@ip-172-31-20-86:~# docker --version

Docker version 28.0.4, build b8034c0

root@ip-172-31-20-86:~# docker info
Client: Docker Engine - Community
 Version:    28.0.4
 Context:    default
 Debug Mode: false
 Plugins:
  buildx: Docker Buildx (Docker Inc.)
    Version:  v0.22.0
    Path:     /usr/libexec/docker/cli-plugins/docker-buildx
  compose: Docker Compose (Docker Inc.)
    Version:  v2.34.0
    Path:     /usr/libexec/docker/cli-plugins/docker-compose

Server:
 Containers: 0
  Running: 0
  Paused: 0
  Stopped: 0
 Images: 0
 Server Version: 28.0.4
 Storage Driver: overlay2
  Backing Filesystem: extfs
  Supports d_type: true
  Using metacopy: false
  Native Overlay Diff: true
  userxattr: false
 Logging Driver: json-file
 Cgroup Driver: systemd
 Cgroup Version: 2
 Plugins:
  Volume: local
  Network: bridge host ipvlan macvlan null overlay
  Log: awslogs fluentd gcplogs gelf journald json-file local splunk syslog
 Swarm: inactive
 Runtimes: io.containerd.runc.v2 runc
 Default Runtime: runc
 Init Binary: docker-init
 containerd version: 05044ec0a9a75232cad458027ca83437aae3f4da
 runc version: v1.2.5-0-g59923ef
 init version: de40ad0
 Security Options:
  apparmor
  seccomp
   Profile: builtin
  cgroupns
 Kernel Version: 6.8.0-1024-aws
 Operating System: Ubuntu 24.04.2 LTS
 OSType: linux
 Architecture: x86_64
 CPUs: 2
 Total Memory: 3.82GiB
 Name: ip-172-31-20-86
 ID: 201c6f4b-75d3-4326-adf5-00b9a82a8d4d
 Docker Root Dir: /var/lib/docker
 Debug Mode: false
 Experimental: false
 Insecure Registries:
  ::1/128
  127.0.0.0/8
 Live Restore Enabled: false

if above page is came without any erros, it means docker is installed in your machine


Docker commands::
====================

 >docker pull <imagename>

 >docker pull hello-world

 >docker images   ----used to display the all images

 > docker image ls ----used to display the all images
 
 >docker run ---used to build the images and create the container


Class Note Docker commands::
==============================


Docker commands::

>docker pull <imagename>

>docker pull hello-world

>docker images

Common Commands:
  run         Create and run a new container from an image
  
  exec        Execute a command in a running container
 
  ps          List containers
  
 
  build       Build an image from a Dockerfile
  
  bake        Build from a file
 
  pull        Download an image from a registry
 
  push        Upload an image to a registry

  images      List images
 
  login       Authenticate to a registry
 
  logout      Log out from a registry
 
  search      Search Docker Hub for images
 
  version     Show the Docker version information
  
  info        Display system-wide information

>docker pull <imagename>:<tagname>

>docker pull hello-world:latest

>docker run hello-world:latest

>docker ps

>docker ps -a

>docker rm <containerID> OR <containerName>

NOTE:: one image we can able to cerate number of containers

>docker rm $(docker ps -a)

i want install jenkins using docker conatiners

>docker run -p 8080:8080 jenkins/jenkins:jdk17\

>docker run -d -p 8080:8080 jenkins/jenkins:jdk17
 running the contaenr in background
 
 >docker run -d -p 8080:8080 jenkins/jenkins:jdk17
 
 go to the inside the conatainers pleas euse below command
 
 >docker exec -it <containerID> /bin/bash

 >docker exec -it 1d9f1ee478e5 /bin/bash

Create the Jenkins container::
=================================

>docker run -d -p 8080:8080 jenkins/jenkins:jdk21


http://35.155.150.89:8080/


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d3162071-7a92-4b7d-a309-42a0b5f8cee1" />




>docker ps

above command is used to verify the how many containers are running


Create the Nginx web based application container::
=======================================================

>docker run -d -p 80:80 nginx:latest

http://3.94.203.109/

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b8cdd2dd-31da-47be-929c-356198e09956" />



>docker ps

above command is used to verify the how many containers are running, you can seee nginx container is running state



detached mode::
=================

Docker detached mode refers to running a container in the background

>docker run -d <image_name>

example::
> docker run -d nginx

Where:

-d is the flag for detached mode.

<image_name> is the name of the Docker image you want to run.

> docker run -d nginx

This command will:

Run the nginx container in detached mode.

Start the container in the background.

To view the containers running in detached mode, you can use the docker ps command:
======================================

>docker ps

Stopping a Container::
=================

>docker stop <containerID>

Start a Container::
=================

>docker start <containerID>

To run a command inside a running container:
======================

>docker exec -it <container_id_or_name> <command>
>docker exec -it 5336d949f33b /bin/bash

>root@5336d949f33b:/# hostname
5336d949f33b
>root@5336d949f33b:/# hostname -i
172.17.0.3


NOTE:::
=========

>docker exec -it 5178eb58223a /bin/bash
Use this command inside the container

>ctrl pq
Outside the containers


08/04/2026::
================


Docker High Level Client -Server Architecture::
==================================


<img width="1700" height="665" alt="image" src="https://github.com/user-attachments/assets/0c95b9d4-34ac-4795-aa30-addb1952b6a3" />



Docker's high-level architecture revolves around several components that work together to provide containerization and isolation for applications


Docker Client (CLI)::
=================

The Docker Client is the primary interface for interacting with Docker. It can be a command-line interface (CLI), like the docker command, or a graphical interface (GUI) in some tools.

It allows users to interact with Docker's features, such as building containers, running containers, and managing containers and images.

It sends requests to the Docker Daemon to execute commands.

Docker Daemon (Dockerd)::
====================

The Docker Daemon (also known as dockerd) is the core component of Docker. It runs in the background on the host system.

The daemon is responsible for managing Docker containers, images, networks, and volumes. It listens for Docker API requests and handles container lifecycle operations such as starting, stopping, and building containers.

The Docker Daemon can communicate with multiple Docker clients, allowing for distributed management of containers.

Flow:
============
1.The Docker Client sends a command to the Docker Daemon.

2.The Docker Daemon interacts with containers, images, and storage volumes.

3.The Docker Daemon can pull images from a Docker Registry.

4.The Docker Daemon runs containers based on the images and handles networking and storage.


root@ip-172-31-39-182:/# docker images
REPOSITORY        TAG       IMAGE ID       CREATED        SIZE
jenkins/jenkins   jdk21     52e1941f479f   21 hours ago   471MB
nginx             latest    9a9a9fd723f1   2 days ago     192MB
root@ip-172-31-39-182:/# docker image tag nginx srinfotech7358/SrInfotechnginx:latest
Error parsing reference: "srinfotech7358/SrInfotechnginx:latest" is not a valid repository/tag: invalid reference format: repository name (srinfotech7358/SrInfotechnginx) must be lowercase
root@ip-172-31-39-182:/# docker image tag nginx srinfotech7358/srinfotechnginx:latest
root@ip-172-31-39-182:/# docker images
REPOSITORY                       TAG       IMAGE ID       CREATED        SIZE
jenkins/jenkins                  jdk21     52e1941f479f   21 hours ago   471MB
nginx                            latest    9a9a9fd723f1   2 days ago     192MB
srinfotech7358/srinfotechnginx   latest    9a9a9fd723f1   2 days ago     192MB
root@ip-172-31-39-182:/# docker login -u srinfotech7358

i Info → A Personal Access Token (PAT) can be used instead.
         To create a PAT, visit https://app.docker.com/settings


Password:

WARNING! Your credentials are stored unencrypted in '/root/.docker/config.json'.
Configure a credential helper to remove this warning. See
https://docs.docker.com/go/credential-store/

Login Succeeded
root@ip-172-31-39-182:/# docker push srinfotech7358/srinfotechnginx
Using default tag: latest
The push refers to repository [docker.io/srinfotech7358/srinfotechnginx]
cd38dca3d982: Mounted from library/nginx
d35594dd7e6d: Mounted from library/nginx
126eaee18409: Mounted from library/nginx
6380429cac56: Mounted from library/nginx
13fcb2d303e8: Mounted from library/nginx
151f9feea563: Mounted from library/nginx
7fb72a7d1a8e: Mounted from library/nginx
latest: digest: sha256:3004321c732af3becb9dc247f5e8926faba9186aa67960e15767996abcec588b size: 1778
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
585b90814ed4   nginx:latest            "/docker-entrypoint.…"   10 minutes ago   Up 10 minutes   0.0.0.0:80->80/tcp, [::]:80->80/tcp                                                                             festive_euler
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   22 minutes ago   Up 22 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   29 minutes ago   Up 29 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   42 minutes ago   Up 42 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker stop 585b90814ed4
585b90814ed4
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   23 minutes ago   Up 23 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   30 minutes ago   Up 30 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   42 minutes ago   Up 42 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker run -d -p 80:80 srinfotech7358/srinfotechnginx:latest
9f5173c50d14631bd31c8270f79a45db441e8c66db5b730dbb7197de65594c20
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
9f5173c50d14   srinfotech7358/srinfotechnginx:latest   "/docker-entrypoint.…"   9 seconds ago    Up 8 seconds    0.0.0.0:80->80/tcp, [::]:80->80/tcp                                                                             vibrant_dewdney
bc684af40e16   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   24 minutes ago   Up 24 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   31 minutes ago   Up 31 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   43 minutes ago   Up 43 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker stop 9f5173c50d14
9f5173c50d14
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   25 minutes ago   Up 25 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   32 minutes ago   Up 32 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   44 minutes ago   Up 44 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker ps -a
CONTAINER ID   IMAGE                                   COMMAND                  CREATED              STATUS                        PORTS                                                                                                           NAMES
9f5173c50d14   srinfotech7358/srinfotechnginx:latest   "/docker-entrypoint.…"   About a minute ago   Exited (137) 27 seconds ago                                                                                                                   vibrant_dewdney
585b90814ed4   nginx:latest                            "/docker-entrypoint.…"   12 minutes ago       Exited (0) 2 minutes ago                                                                                                                      festive_euler
78f28d3d450f   nginx:latest                            "/docker-entrypoint.…"   13 minutes ago       Created                                                                                                                                       interesting_mclaren
a800fb0e6d7c   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   23 minutes ago       Exited (143) 13 minutes ago                                                                                                                   romantic_lewin
bc684af40e16   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   25 minutes ago       Up 25 minutes                 8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   32 minutes ago       Up 32 minutes                 0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
1b6159a409c3   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   33 minutes ago       Created                                                                                                                                       unruffled_pare
aca7ec14bfc5   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   44 minutes ago       Up 44 minutes                 0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker start 9f5173c50d14
9f5173c50d14
root@ip-172-31-39-182:/# Read from remote host ec2-35-155-150-89.us-west-2.compute.amazonaws.com: Connection reset by peer
Connection to ec2-35-155-150-89.us-west-2.compute.amazonaws.com closed.
client_loop: send disconnect: Connection reset by peer


Usefull commands:
===============

>docker --version

>docker info

>docker pull <imagename>

>docker pull ubuntu =docker pull ubuntu:latest

>docker images

>docker run -d ubuntu

>docker ps -aq

>docker rmi <imagenname>

>docker run -d -p 8080:8080 -p 5000:5000 jenkins/jenkins:jdk21

>docker exec -it aca7ec14bfc5 /bin/bash     --->inside the container comamnd

>docker run -d -p 8080:8080 -p 5000:5000 jenkins/jenkins:jdk21

>ctrl+pq or exit

>docker image tag nginx srinfotech7358/srinfotechnginx:latest



10/04/2026::
============


Dockerfile Introduction::
=================

A Dockerfile is a script containing a series of instructions on how to build a Docker image. It defines the environment and application setup, including dependencies, configurations, and the necessary steps to get your application running in a container.

dockerfile is a text file, and it have set up of all instructiuons

https://docs.docker.com/get-started/docker-concepts/building-images/writing-a-dockerfile/


Dockerfile::dockerfile is text file, and it have set up of all instructiuons

FROM nginx or ubuntu or 

LABEL "AUthor =nagaraju@gamil.com"

RUN apt update && apt-get install jenkins -y

COPY . .  ----src destnations

ADD  . . -----src destinatuion

CMD ["echo",".jar"]

ENTRYPOINT ["echo", "war"]

EXPOSE 8080,8085

ENV APP_HOME ="Ifocus SOlutions pvt ltd"

WORKDIR $APP_HOME /app

VOLUME 

Key Components of a Dockerfile:
==========================

FROM: Specifies the base image for the Docker image you're creating.

FROM ubuntu:20.04

RUN: Executes commands inside the container, often used to install dependencies.

RUN apt-get update && apt-get install -y python3

COPY or ADD: Copies files from your local machine into the container.

COPY . /app

WORKDIR: Sets the working directory for any subsequent commands in the Dockerfile.


WORKDIR /app

CMD: Specifies the command to run when a container is started from the image.

CMD ["python3", "app.py"]

EXPOSE: Defines the network ports the container will listen on at runtime.

EXPOSE 8080

ENV: Sets environment variables inside the container.
ENV APP_ENV=production
CMD & ENTRPOINT can be executed starting of the container

CMD & ENTRYPOINT Different::
===========================
--use CMD you can change the value but ENTRYPOINT not possible to change the value at the starting of the container
--CMD you can change the argument value 
--ENTRYPOINT can’t change the argument value

CMD ["echo",".jar"]
ENTRYPOINT ["echo", "war"]

CMD/ENTRYPOINT ====should have something which runs till your app is alive



13/04/2026::
===============

github url's::
==============

https://github.com/dockersamples/helloworld-demo-node

https://github.com/srinfotechbatch5/spring-ms

Note::
=======
life time of your container -->time which your cmd/entrypont is alive


Example Dockerfile:::
====================

Here’s a simple Dockerfile example that builds a nodejs web app:

>root@ip-172-31-18-253:~# sudo vi Dockerfile


# Use an official Node.js runtime as a base image
FROM node:18

# Set the working directory inside the container
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json .

RUN npm install

# Copy the rest of the application code
COPY . .

# Expose port 3000
EXPOSE 3000

# Run the application
CMD ["node", "index.js"]


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5c1edbe8-fbb3-43bf-bc35-571bd1d92180" />


Example package.json
=======================

root@ip-172-31-18-253:~# sudo vi package.json


{
  "name": "my-app",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "start": "node index.js"
  },
  "dependencies": {
    "express": "^4.18.2"
  }
}


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/83c6cdd5-3141-4b8c-bec8-0d06bd1a83e4" />


Example index.js
==================

root@ip-172-31-18-253:~# sudo vi index.js


const express = require('express');
const app = express();
const port = 3000;

app.get('/', (req, res) => {
  res.send('Hello from Docker!');
});

app.listen(port, () => {
  console.log(`App running at http://localhost:${port}`);
});



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5902a90a-0eba-4646-8f19-67db7d073fb3" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/63bb34d1-774d-48e0-9848-67215348c430" />


Building and Running a Docker Image:
Once you’ve written your Dockerfile, you can build and run it using Docker commands:

Build the Docker image:
==========================

root@ip-172-31-18-253:~# docker build -t srinfotechnodejs .

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dcc12017-f3e4-437a-be2b-5015105f163d" />

root@ip-172-31-18-253:~# docker images
REPOSITORY         TAG       IMAGE ID       CREATED         SIZE
srinfotechnodejs   latest    90e50223164e   7 seconds ago   1.13GB
root@ip-172-31-18-253:~#

Create & Run the container:
=============================

>docker run -d -p 80:80 srinfotechnodejs:latest

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c1995df6-1cec-42cf-9b54-39c4a8ed966e" />



root@ip-172-31-18-253:~# docker run -d -p 3000:3000 srinfotechnodejs:latest

04ab1eb49a96ad9ecc7b4d84eebf0462c05dd97db02f50d5436796427dc010cf

root@ip-172-31-18-253:~#


root@ip-172-31-18-253:~# docker ps
CONTAINER ID   IMAGE                     COMMAND                  CREATED              STATUS              PORTS                                         NAMES
82bf288b2a2d   srinfotechnodejs:latest   "docker-entrypoint.s…"   About a minute ago   Up About a minute   0.0.0.0:3000->3000/tcp, [::]:3000->3000/tcp   distracted_jemison
root@ip-172-31-18-253:~#


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a4b5f3d8-313d-4203-9d81-d42c5b752f61" />


Clone the Spring-micro service Project::
=========================================

>git clone https://github.com/srinfotechbatch3/spring-ms.git

root@ip-172-31-18-253:~# git clone https://github.com/srinfotechbatch3/spring-ms.git
Cloning into 'spring-ms'...
remote: Enumerating objects: 266, done.
remote: Counting objects: 100% (169/169), done.
remote: Compressing objects: 100% (91/91), done.
remote: Total 266 (delta 55), reused 103 (delta 31), pack-reused 97 (from 1)
Receiving objects: 100% (266/266), 29.17 MiB | 38.34 MiB/s, done.
Resolving deltas: 100% (84/84), done.
root@ip-172-31-18-253:~#


A **Dockerfile** is a script containing a series of instructions on how to build a Docker image. It defines the environment and application setup, including dependencies, configurations, and the necessary steps to get your application running in a container. Essentially, it's the blueprint for creating Docker images.

### Key Components of a Dockerfile:
1. **FROM**: Specifies the base image for the Docker image you're creating.
   ```dockerfile
   FROM ubuntu:20.04
   ```

2. **RUN**: Executes commands inside the container, often used to install dependencies.
   ```dockerfile
   RUN apt-get update && apt-get install -y python3
   ```

3. **COPY** or **ADD**: Copies files from your local machine into the container.
   ```dockerfile
   COPY . /app
   ```

4. **WORKDIR**: Sets the working directory for any subsequent commands in the Dockerfile.
   ```dockerfile
   WORKDIR /app
   ```

5. **CMD**: Specifies the command to run when a container is started from the image.
   ```dockerfile
   CMD ["python3", "app.py"]
   ```

6. **EXPOSE**: Defines the network ports the container will listen on at runtime.
   ```dockerfile
   EXPOSE 8080
   ```

7. **ENV**: Sets environment variables inside the container.
   ```dockerfile
   ENV APP_ENV=production
   ```

### Example Dockerfile
Here’s a simple Dockerfile example that builds a Python web app:

```dockerfile
# Use an official Python runtime as the base image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container
COPY . /app

# Install the required dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Expose the port the app runs on
EXPOSE 5000

# Define the command to run the application
CMD ["python", "app.py"]
```

### Building and Running a Docker Image:
Once you’ve written your Dockerfile, you can build and run it using Docker commands:

1. **Build the Docker image**:
   ```bash
   docker build -t my-python-app .
   ```

2. **Run the container**:
   ```bash
   docker run -p 5000:5000 my-python-app
   ```

The Dockerfile streamlines the process of creating consistent and reproducible environments, making it easier to deploy applications across different systems.


Please try Below Example on Docker file:
============================================

https://docs.docker.com/get-started/workshop/02_our_app/


Spring Micro Services Aplication::
=======================

https://github.com/srinfotech7358/spring-ms.git

LAB Practice::
==============

root@ip-172-31-32-42:~# git clone https://github.com/srinfotech7358/spring-ms.git
Cloning into 'spring-ms'...
remote: Enumerating objects: 242, done.
remote: Counting objects: 100% (145/145), done.
remote: Compressing objects: 100% (78/78), done.
remote: Total 242 (delta 47), reused 103 (delta 31), pack-reused 97 (from 1)
Receiving objects: 100% (242/242), 29.16 MiB | 3.85 MiB/s, done.
Resolving deltas: 100% (76/76), done.
root@ip-172-31-32-42:~# ls
getting-started-app  snap  spring-ms
root@ip-172-31-32-42:~# cd spring-ms/
root@ip-172-31-32-42:~/spring-ms# ls
Dockerfile  azure-pipeline.yml  azure-pipelines.yml  deploy.yaml  pom.xml  src
root@ip-172-31-32-42:~/spring-ms# sudo vi Dockerfile
root@ip-172-31-32-42:~/spring-ms# docker build -t srinfotech .
[+] Building 43.6s (12/12) FINISHED                                    docker:default
 => [internal] load build definition from Dockerfile                             0.0s
 => => transferring dockerfile: 256B                                             0.0s
 => WARN: FromAsCasing: 'as' and 'FROM' keywords' casing do not match (line 1)   0.0s
 => [internal] load metadata for registry.access.redhat.com/ubi8/openjdk-11:lat  0.9s
 => [internal] load metadata for docker.io/library/maven:3.6.3-jdk-11            1.0s
 => [auth] library/maven:pull token for registry-1.docker.io                     0.0s
 => [internal] load .dockerignore                                                0.0s
 => => transferring context: 2B                                                  0.0s
 => [internal] load build context                                                0.3s
 => => transferring context: 30.64MB                                             0.3s
 => [stage-1 1/2] FROM registry.access.redhat.com/ubi8/openjdk-11:latest@sha25  25.4s
 => => resolve registry.access.redhat.com/ubi8/openjdk-11:latest@sha256:28b35ee  0.0s
 => => sha256:28b35eea470174a39befd8eb9250a3276b79a4f6e7dac7872 1.47kB / 1.47kB  0.0s
 => => sha256:8be99c30a4e5b021129310847bddca64a93fb38b0c8dfeac482b4 596B / 596B  0.0s
 => => sha256:0c46377f1021ce6db9f2457907fe43fd1001b2ecc1ae2ac 30.70kB / 30.70kB  0.0s
 => => sha256:e0348fdb2685077d22116d294a90a253709aba78815882a 39.49MB / 39.49MB  2.6s
 => => sha256:50d776090f4e8d167cbe918c0da58f7b67533ab58d59 113.69MB / 113.69MB  18.7s
 => => extracting sha256:e0348fdb2685077d22116d294a90a253709aba78815882a57fcc53  2.7s
 => => extracting sha256:50d776090f4e8d167cbe918c0da58f7b67533ab58d59ffa6acb6f2  6.4s
 => [stage1 1/3] FROM docker.io/library/maven:3.6.3-jdk-11@sha256:1d29ccf46ef2  16.5s
 => => resolve docker.io/library/maven:3.6.3-jdk-11@sha256:1d29ccf46ef2a5e64f7d  0.0s
 => => sha256:1801d353e27e68d60355b371ddfd2ed8d06204bc3266f1746 2.42kB / 2.42kB  0.0s
 => => sha256:004f1eed87df3f75f5e2a1a649fa7edd7f713d1300532fd 50.43MB / 50.43MB  1.0s
 => => sha256:1d29ccf46ef2a5e64f7de3d79a63f9bcffb4dc56be0ae3daed5ca 549B / 549B  0.0s
 => => sha256:e23b595c92ada5c9f20a27d547ed980a445f644eb1cbde7cf 8.93kB / 8.93kB  0.0s
 => => extracting sha256:004f1eed87df3f75f5e2a1a649fa7edd7f713d1300532fd0909bb3  3.6s
 => => sha256:5d6f1e8117dbb1c6a57603cb4f321a861a08105a81bcc6b01 7.83MB / 7.83MB  1.4s
 => => sha256:48c2faf66abec3dce9f54d6722ff592fce6dd4fb58a0d0b 10.00MB / 10.00MB  1.7s
 => => sha256:234b70d0479d7f16d7ee8d04e4ffdacc57d7d14313faf59 51.84MB / 51.84MB  3.1s
 => => sha256:d7eb6c022a4e6128219b32a8e07c8c22c89624ff440ebac15 5.29MB / 5.29MB  2.8s
 => => sha256:6c215442f70bd949a6f2e8092549943905e2d4f9c87a4f532d774 213B / 213B  3.1s
 => => sha256:cf5eb43522f68d7e2347e19ad70dadcf1594d25b792ede046 9.58MB / 9.58MB  3.7s
 => => sha256:355e8215390faee903502a9fddfc65cd823f1606f0533 202.81MB / 202.81MB  6.8s
 => => sha256:4fee0489a65b64056f81358639bfe85fd87776630830fd02ce8c1 855B / 855B  4.1s
 => => sha256:413646e6fa5d7bcd9722d3e400fc080a77deb505baed79afa5fed 363B / 363B  4.3s
 => => extracting sha256:5d6f1e8117dbb1c6a57603cb4f321a861a08105a81bcc6b01b0ec2  0.6s
 => => extracting sha256:48c2faf66abec3dce9f54d6722ff592fce6dd4fb58a0d0b7228293  0.3s
 => => extracting sha256:234b70d0479d7f16d7ee8d04e4ffdacc57d7d14313faf59d332f18  2.9s
 => => extracting sha256:d7eb6c022a4e6128219b32a8e07c8c22c89624ff440ebac1506121  0.2s
 => => extracting sha256:6c215442f70bd949a6f2e8092549943905e2d4f9c87a4f532d7740  0.0s
 => => extracting sha256:355e8215390faee903502a9fddfc65cd823f1606f053376ba2575a  3.0s
 => => extracting sha256:cf5eb43522f68d7e2347e19ad70dadcf1594d25b792ede0464c293  0.2s
 => => extracting sha256:4fee0489a65b64056f81358639bfe85fd87776630830fd02ce8c15  0.0s
 => => extracting sha256:413646e6fa5d7bcd9722d3e400fc080a77deb505baed79afa5feda  0.0s
 => [stage1 2/3] COPY . .                                                        1.2s
 => [stage1 3/3] RUN mvn clean package                                          24.0s
 => [stage-1 2/2] COPY --from=stage1 target/*.jar app.jar                        0.1s
 => exporting to image                                                           0.1s
 => => exporting layers                                                          0.1s
 => => writing image sha256:a1aa2587a6a74ca2d5e113d039a0c5198d12f54919056285ec3  0.0s
 => => naming to docker.io/library/srinfotech                                    0.0s

 1 warning found (use docker --debug to expand):
 - FromAsCasing: 'as' and 'FROM' keywords' casing do not match (line 1)
root@ip-172-31-32-42:~/spring-ms# docker images
REPOSITORY   TAG       IMAGE ID       CREATED          SIZE
srinfotech   latest    a1aa2587a6a7   17 seconds ago   410MB
test         latest    944581c42756   7 minutes ago    166MB
root@ip-172-31-32-42:~/spring-ms# docker run -d -p 8080:8080 srinfotech:latest
eb3d6d70bc9e049db0255b30f406b9559f7b03d1e82862d59205f363e1b8087e
root@ip-172-31-32-42:~/spring-ms# docker ps
CONTAINER ID   IMAGE               COMMAND               CREATED         STATUS         PORTS                                                             NAMES
eb3d6d70bc9e   srinfotech:latest   "java -jar app.jar"   6 seconds ago   Up 5 seconds   8443/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 8778/tcp   fervent_bassi
root@ip-172-31-32-42:~/spring-ms# Read from remote host ec2-34-222-12-103.us-west-2.compute.amazonaws.com: Connection reset by peer
Connection to ec2-34-222-12-103.us-west-2.compute.amazonaws.com closed.
client_loop: send disconnect: Connection reset by peer



Application up & running::
=============================

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/03d89434-a183-4a0e-8733-2f1dc4d65cef" />


