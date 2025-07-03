+++
title = "Cli Tools"
date = "2025-07-04T04:51:21+05:30"
draft = false
+++
A blog about CLI-Tools and the need of building more of them!
<!--more-->

Full-Article Link: 
[article link](https://medium.com/@honey032004/cli-tools-simple-fast-essential-66d0354d47b0)

We use CLI-Tools almost every day as developers, from git to docker.
These CLI-Tools are not just reliable but also efficient and user-friendly.

What is a CLI-Tool?

A CLI-tool is a piece of software that lets you interact with your operating system using text-based commands.

Some of the examples are :
1. git
2. docker
3. npm
4. btop
5. distrobox

But why really are they so powerful?

IDEOLOGY BEHIND CLI-Tools

1. Simplicity
2. Efficiency
3. Speed
4. Portability

Whether it’s from checking the tasks running on your operating system using btop or using the most famous example of CLI-Tool like git, CLI-tools are easy to use and really fast.

Now why or when do we really need a CLI-Tool?

Well, from a general perspective considering a large population of users of any operating system the general consensus is —

USE OF CLI IS A FUNDAMENTAL UX ISSUE

Well that is TRUE.

For basic tasks like file exploring, managing tasks making disk partitions etc. You really don’t need a CLI-Tool unless you messed up your OS install like me and really need it. Regardless for general users CLI-Tools are not preferred for day-to-day tasks or even some development tasks.

So who really needs CLI-Tools?

Before we talk about who really needs CLI-Tools let’s talk about some important issues it solves—

CLI Applications consume fewer network resources compared to graphical applications.
This is important for systems with limited hardware capabilities or remote server environment.

You can manage servers remotely by submitting commands over a secure shell.

FOR DEVELOPERS AND SYSADMINS
Learning CLI-tools and CLI-toolchain for Developers and Sysadmins helps in deeper understanding of the system.

For example: You want to quickly see logs for a particular error that you want to fix for your system?

A log is basically a file that records particular events for example system errors or crashes.

journalctl is a command-line utility in Linux used to view and query logs stored in the systemd journal.

This indeed is really fast and saves you a lot of time.

DEVELOPER’S BEST FRIEND
CLI-Tools are a developer’s best friend. They help you understand how each and every process of a particular software or service actually works and also helps you in understanding the general workflow of the code better.

git being the most popular CLI-Tool is really convenient and makes it way easy to pull repos, push commits and check status of your current dev-environment really fast and that saves a lot of time for the developer to actually code their project.

How does CLI WORK?
The CLI basically operates on the default shell. which is between the operating system and the user.

A shell is basically like a translator between you and the OS.

For example:

when you open Terminal on Linux/macOS.

You want to search for a particular file in a directory?

<img src = "/images/cli1.png"/>

**Ah! found my config!**

**cd** — command is basically used to move into a particular directory in this case (.config)

**ls** — Is used to list all the files or folders in that particular directory.

So that’s how I got my config!!

That’s basically the shell that you’re using to find that file.

Now there is freedom to choose what shell you want to use depending on what features you need from that shell.

What I am using in the image above is fish shell.

Other popular options are :
1. **Bash**
2. **Zsh**
3. **Fish**
4. **Powershell**

Here is a cool CLI-Tool called lazygit


<img src  = /images/cli2.png>

---

***The power of CLI-Tools used at its best. It gives you are GUI-like experience for managing version control for your projects which even the pros love!!***

--- 

***WHY YOU SHOULD CONSIDER BUILDING YOUR OWN CLI-TOOL ?***

Now the main part of this article and the motivation it gives you is for making your own CLI-Tool and why you should make it?

GUI may not have the same flexibility as a command-line interface. GUIs do not support scripting and automation. Some things are easier done with one command than navigation through clicks.
CLI-Tools are loved by software developers and system administrators as it makes configuring, deploying, and maintaining systems easier and faster.
Example: package manager like npm or pip primarily support CLI.


