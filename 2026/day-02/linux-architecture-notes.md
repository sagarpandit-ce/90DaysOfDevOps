# Linux Architecture, Processes and systemd

## Linux Architecture

Linux has four main parts:

* Application: Programs like Chrome, VS Code, Firefox
* Shell: Takes user commands and sends them to the kernel
* Kernel: Core of Linux that manages memory, CPU, files and devices
* Hardware: Physical parts such as CPU, RAM and Disk

## Processes

A process is a program that is running.

Examples:

* Chrome
* VS Code
* Linux commands

Each process has a PID (Process ID).

### Process States

* Running (R): Process is executing
* Sleeping (S): Waiting for something
* Stopped (T): Process is paused
* Zombie (Z): Process has finished but still exists in the process list

## systemd

systemd starts when Linux boots.

It is used to:

* Start services
* Stop services
* Restart services
* Manage background processes

Why systemd is important:

* Starts services automatically
* Makes service management easier
* Helps in troubleshooting

## Commands I Learned

* `ls` : Lists files and folders in the current directory
* `pwd` : Shows the current working directory
* `ps` : Displays running processes
* `top` : Shows CPU, memory and running processes in real time
* `systemctl` : Used to start, stop and check services

## What I Learned

Today I learned the basic Linux architecture, process states, and the role of systemd in managing services. I also learned some common Linux commands used for navigation and process management.
