---
title: Most helpful unusual linux commands
layout: post
author: Sajith Herath
date: '2020-11-16 18:40:23 +0530'
category: linux
summary: Most helpful unusual linux commands
thumbnail: linux-commands.png
---

As a linux user for a decade, my experience is that linux users have an everlasting intimate bond with linux shell commands even though they were afraid as beginners. Since things that can be done with shell commands are more powerful and efficient than GUIs that might take more and more steps. Because it’s just a single line command.          

Though there are different linux [distros](https://en.wikipedia.org/wiki/Linux_distribution) such as Ubuntu (my favourite), Arch linux, Fedora, Kubuntu, Mint etc, you can use shell commands in any of these since they are built with linux kernel. So learning shell commands in linux improves your productivity as well as self confidence on using linux distros. I hope you’ll learn useful shell commands whether you are a linux beginner or a daily user from this article.

**1. Chek current IP**

		a. ifconfig 
		b. ip addr show

**2. Check Kernal**
		
		a. uname -a 
		b. uname -v
		c. uname -r

**3. Check disk free space**

		df -ah

**4. Total size of given directory**

		du -sh <directory>

**5. Managing services**
		
		old method- service <service-name> status
		new method- systemctl status <service-name>


**6. Check listening ports**

		sudo Netstat -tulpn

**7. CPU process**

		a. ps aux | grep <process-name>
		b. top
		c. htop

**8. Dealing with mounts**
		
		mount <source> /mnt/<mount name>

**9. Manual of commands**

		man <command>