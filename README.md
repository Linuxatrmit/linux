
# Team Profile
### Team name
LinuxDoc for Linux documentation.
### Personal Information
 ***Student #:*** S3266698
# Project Description
https://github.com/Linuxatrmit/linux
https://linuxatrmit.github.io/
## Overview
### Topic
An open-source Operating-System and tools - training course and education resources, accessible for distance learning via online login.
### Motivation
Main focus will be on the Linux operating system, remote login via ssh to the project's *Amazon Instance Image* (AMI) on **Amazon EC2**, where live and on-demand interaction with the target operating system and its utilities will be tested and visualized.
There is a considerable increase in software migration to the Linux Operating System, and while not long ago, you had to own a physical copy of the operating system in order to run it, with the advance of the cloud era, remote login to a Linux distribution instance launched on the cloud servers, allows one to get the full Linux experience without the cost and investment associated with its installation and maintenance.
And while remote login may be slow at times, with the advance of *Windowes Subsystem for Linux* (**WSL**) by Microsoft, one can natively run and experience the full Linux ecosystem with all its useful utilities, out of the Windows OS, without the spending time to manually partition and dual booting to another Operating-System on the same machine.
### Landscape
There is no shortage of Linux documentation online, from books to online-documentation, dedicated YouTube channels, certification institutes and university courses, as well as the open-source nature of its ecosystem that invites everybody to download the source-code, modify, fix and test the results.
Such it may seem like a saturated market, but considering the huge demand, and endless topics with enormous complexities and ever changing landscape where the dynamic nature of the open-source community keeps changing trends and calls for endless training and update resources.
## Detailed Description
### Aims
To provide an interactive and rich environment to be readily accessible online, for Linux Documentation.
By interactive, meaning the utilities may be visualized, with custom installed, users are given remote login access, and on-demand processes are interacting the client interfacing the system.
### Plans and Progress
There are 3 main parts to the project, each strongly associated with each other, as they finally integrate to provide a full blown and rich project to bring the full experience to the client.
they include:
1. The documentation component, where major focus will be on installing, booting and testing the Operating system and its utilities.
2. The remote server, which will provide an online dynamic interactive on-demand sessions, to demonstrated and visualize complicated topics.
3. The practice section, where an online repository of practice questions and tasks will be utilized by a perspective client in preparation for a technical job interview, or for personal interest and practice in the field.
### Roles
### Scope and Limits
### Tools and Technologies
   * **Git**. As the main *Version Control System* (VCS), as a client to manage and/or track the project, interact with online repositories to upload/download source code, ans as tool for bug fixes.
  * **Shell** (*Ash*, *Bash*, *Zsh*): The 3 main shells will be tested and compared for their individual advantages and disadvantages, their level of compliance with the Posix standsard and other Linux standards, the "plugins" available to automate their use, providing interactive prompts, online completion and look into advance batch scripting, cron jobs, and useful utilities to provide automatic and periodic constant system backups and restoration points, to keep the system fully reliable and updated, with its data fully secured.
### Testing
  * Technical issues are expected for any remote deployment, and the accuracy of the documentation should always be carefully checked and verified, by automating a test suite to be automatically run before any project upgrade. These tests should cover all aspects of the project, from the technical issues, user's interface experience and the server infrastructure viability.
### Timeframe
   The initial steps for the project were outlined, the core project will take abot 1 year in order to fullfill the project's goals.
### Risks
   Allowing your server to be granted remote access via *ssh* present major security risks.
   Only authorized users should be given access. Only via *ssh keys*, where password alone will not suffice. Their interaction with the server should be monitored and limited to provide a reasonable balance between security and accessibility.

### Group Processes and Communication
   Constant communication and cooperation should exist between the front-end developers providing the client interface to the project and the backend developers who program the underlying processes empowering this interaction.
