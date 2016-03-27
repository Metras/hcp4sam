# Handshake Control Program for SAM Broadcaster #

SAM Broadcaster is a complete radio station in a box. Everything needed for operating an online radio station, on the professional or enthusiastic hobbiest level, is in its software; the automation system, playlist management, encoders, statistics, and web integration.  The Handshake Control Program, known as HCP, adds to SAM hardware connectivity to the outside world via the handshaking lines of a common RS-232 serial port.  HCP makes available two output lines and four input lines that can interface with relay closures.  HCP communicates with SAM via the IP stack and may even reside on another machine. Easy integration with SAM is by PAL, SAM's built-in scripting language.

# Launcher.EXE and Launcher.INI #


Launcher was developed to meet the need of launching programs at startup in a specific order or after specific time delay.  This is often necessary because of program inter-dependencies.  A common example is a program that will not load at startup because it must wait until a required database service is running and fully initialized.  If the database takes longer to load than the program, the program will always fail to load.  This is a problem that is common to SAM Broadcaster and BE's Audio Vault when used with MySQL.  Launcher addresses this problem by allowing the user to start multiple programs, each with it's own specific delay.  That delay may be up to 999 seconds, about sixteen minutes.  Given that each has it's own delay, the programs will load in a specific order.  The documentation for this program is part of the .INI file.

# EASMon.EXE #

EASMon.exe, an EAS logger program, records Gorman-Redlich, TFT and Sage-Harris Emergency Alert System decoder activity to to the hard disk or USB drive of an attached personal computer.  This PC logging software is an excellent replacement for aging tape, thermal, or dot matrix printers.  Complete documentation is provided in the INI file included with the download.  This software is freeware and may be downloaded and used without cost.

**EASMon logs have been accepted by FCC agents while inspecting stations.**


