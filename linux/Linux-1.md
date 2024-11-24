* What is Linux?
Discuss the basics of Linux as an open-source operating system, its kernel, and its advantages over other operating systems.
* How do you check disk space usage on a Linux system?
Explain using commands like df -h to display disk space in a human-readable format and du -sh * to check the size of specific directories.
* What is the purpose of the /etc/fstab file?
Describe how this file is used to define how disk partitions, devices, and remote filesystems are mounted into the filesystem.
* How can you list all running processes on a Linux system?
Mention using commands such as ps aux or top to view active processes and their resource usage.
* What command would you use to find a specific pattern in a log file?
Discuss using grep, for example: grep "error" /var/log/syslog, to search for specific text within files.
* How do you create a new user and grant them sudo privileges?
Explain the steps involving adduser username, followed by adding the user to the sudo group using usermod -aG sudo username.
* What is swap space, and when is it used?
Define swap space as an area on the disk used when RAM is full, helping to manage memory more effectively.
* How do you restart a service in Linux?
Describe using commands like systemctl restart servicename for systems using systemd or /etc/init.d/servicename restart for SysVinit systems.
* What is a kernel panic, and how would you troubleshoot it?
Explain that a kernel panic is a safety measure taken by an operating system upon detecting an internal fatal error. Discuss checking logs and boot parameters as troubleshooting steps.
* How do you monitor network connections in Linux?
Mention tools like netstat, ss, or iftop to view active network connections and their states.