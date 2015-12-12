# Day 2 Keynote
## About
* Linux loves ruby
* Ruby loves Linux
* how to debug your linux box

## Notes
* Patch to OSS is like tetris
* Linux Debugging tools: Ftrace, Perf tools, SystemTap
* FTrace (for fetching kernel level events. Kernel hackers can add whatever events that they wish). If you google Ftrace there is a presentation which explains it.
* (bash# perf top). Works like top but shows the number of functions within the processes
* (bash# perf trace). Gets to see all the processes on the system
* (bash# perf report). Its ncurses based and a bit more interactive. You can drill down through the processes
* SystemTap is the linux equivalent of DTrace (used in Solaris, OS X, and BSD)
