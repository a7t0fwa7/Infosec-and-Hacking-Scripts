# Linux Memory Dump
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com) 

![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

This will prompt the user to enter the PID of the process they want to dump and the name of the file they want to save the dump to. It then uses the subprocess module to call the "gcore" command, which creates a core dump of the process with the specified PID and saves it to the specified file.

    Note that to run gcore command you need to have gdb installed on the machine and running the script as root user. 
    Also, this script is just a template so you kinda have to tweak it to suit your specific needs.
