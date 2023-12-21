---
title: Shell
publishDate: 2019-12-01 00:00:00
img: /assets/bash.png
# <a target="_blank" href="https://icons8.com/icon/8gWOBXY72Osj/frapper">frapper</a> icône par <a target="_blank" href="https://icons8.com">Icons8</a>
img_alt: Bash shell logo.
description: |
  A small project in c to create a shell. That allow us to execute commands and use pipes.
tags:
  - C
  - System Programming

---

## Description
  Using the system calls such as fork, exec, wait, dup2, pipe, etc. I created a shell that allow us to execute commands and use pipes.
  That looks like this:
  ![shell](../../../public//assets/shell.png)
  The shell is ignoring SIGINT signal, but not child processus and it's closing when we type exit.
