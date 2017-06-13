# Parking Lot 01--Day 1
## Issues we face while executing the hands on tasks and the ways we resolve them.

* **when downloading precise32/64 system asks if we need to use Virtual Box or VMware or sth else**
	we choose Virtual Box

* **unix folder name contains a space**

* **is the VagrantFile required to be in ruby?**
	A VagrantFile needs to be ruby

* **are the first two lines of the VagrantFile mandatory?**
	__# -*- mode: ruby -*-
	# vi: set ft=ruby :__
	We've seen that these lines are at the top of all sample Vagrant files.
	These lines are not mandatory for the working of Vagrant itself (they are just comments, as far as Vagrant is concerned)
	These lines are called 'modelines' and inform a vi or emacs editor of the language and syntax being used in the file.
