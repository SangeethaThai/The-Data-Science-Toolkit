# CSX_450_1_Project_1 The Data Science Toolkit

## Goal

The purpose of this document is to provide a detailed guide to help in installing and configuring a Jupyter Data Science Notebook Server on Amazon Web Services (AWS).
It also discusses the following at the end:
•	Jupyter Notebook Security Concerns
•	Cost of running a notebook server for 3 months

## Architecture of the System (AWS, Docker, Jupyter)

Here is a little diagram to help understand the system.
![picture](images/architecture.png)

## Pre-requisites:
Before we get into the nitty-gritty of setting up/configuring the Jupyter Data Science Notebook, we need to go through some basic set up.

1)	### CREATE AMAZON WEB SERVICES (AWS) ACCOUNT
Create your AWS account at https://aws.amazon.com/ if you don’t already have one. Note that you will need to provide a phone number to authenticate and complete setting up the account.

2)	### INSTALL BASH SHELL
On the Window Operating System, please download and install git-bash from https://git-scm.com/downloads .
On Mac Operating System, no installation is needed, as this is available native. It is the Mac Terminal shell available in the Utilities folder.

On the Linux OS, this is available native as well.

3)	### GENERATE SECURE KEYS
Launch your Bash Shell and follow the steps below to generate secure public/private rsa key pair that will be used to authenticate/connect to our AWS instance. If the rsa key pair already exist at ~/.ssh/, then please skip this step, as you do need to regenerate it.
Step 1: In your home directory, create a directory .ssh with command “mkdir .ssh”.
Step 2: Navigate into this .ssh directory, with command “cd .ssh”.
Step 3: Generate secure keys with command “ssh-keygen”. This command will create 2 files, a public key (id_rsa.pub) and a private key (id_rsa). Please verify these files were generated with command “ls” to list the files.
4)	### GET GITHUB
Github is a Version Control and Source Code Management System.
Create a GitHub account at http://github.com, and fork our class repo at  https://github.com/joshuacook/UCLA_CSX_450_1_2018_W (Links to an external site.)
To fork, just click the “Fork” button on the top right corner. Forking creates a copy of the project repository in your personal git-hub account. Any changes to your copy will not affect the original class copy.



## Author

**Sangeetha Parthasarathy**
