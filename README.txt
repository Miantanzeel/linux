1. Why Linux:
	Throughput = multiple tasks executed per unit time
2. Major functions:
	Resource management
	Process management
	Storage management
	Memory management
	Security Management

3. Commands:
	cd /			//To go to root
	cd ../			////To go one step back in directory
	cd dirname		//To go to specified directory name
	touch filename.txt	//To create new file
	mkdir dirname		//To create new folder/directory
	ls			//To list file names and folder names
	cp filename path	//To copy file to specified path	
	mv filename path	//To move/cut file to specified path
	rm filename		//To delete/remove file
	man ls			// man is used to get help/ description about specified command
	find path -name filename//To find specified file in specified directory
	uname			// name of OS
	uname -a 		// gives details of OS name, OS username and version
	lscpu			// gives cpu details
	df -h			// human readable storage details
	du path			// gives storage used by file or folder
	du -s path		// gives total storage size of specified folder
	date			// gives current date
	cal			// gives today date in calander
	w			// which user is online
	apt-get install package-name	// install specified package name
	apt-cache search keyword// search package name by specifying keyword
	info 			// gives information about commands
	type man		// shows location/path of specified command 
	bg			// shows background services currently running
	free			// shows available and free memory right now
	ps			// shows currently running processes
	kill 332		// kills process by specified processID
	nice			// run program with low priority
	top			// memory and cpu utilization of processes
	su -			// switch to root in the shell
	shutdown		// to shutdown system
	sudo su			// to login as root/super user
	sudo apt-get install python	// to install package without login
	apt-tap			// tap button is used to auto complete command
	apt-taptap		//tap tap button is used to get help about given command
	ctrl+a			// to bring cursor at the  beginning of command
	ctrl+e			//to bring cursor to end of command line
	vi filename->i		// to edit file, i is used to insert
	:wq			// write and quite
	cat filename		// to display text of file
	ls -l 			// to display permissions assigned
	uptime			// to see time os started
	uname -srv		// os name version and release
	pwd			//present working directory
	hostname		// to show host name
	hostname -i		// shows ip address
	w			// to display user login datetime
	lscpu			// gives details about cpu
	cat /proc/cpuinfo	// to display cpu info
	sudo apt-get install cpuid	// to install package like cpuid
	cpuid			// package used to get info about cpu
	sudo apt remove cpuid	// to uninstall package cpuid
	apt search cache python	// to search package commands say python
	alias mycmd="command"	// to create custom command
	unalias mycmd		// to remove/delete specified custom command
	sudo useradd jone -m	//create new user say jone
	sudo passwd jone	// to set password for user
	sudo userdel jone -r	// to delete user
	info ls			// shows detailed information about command say ls
	whatis ls		// shows single line detail of command say ls
	whereis ls		//locate command
	which ls 		//locate cooamd
