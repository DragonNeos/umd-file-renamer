# umd-file-renamer
Created by hp.diego

This application reads ISO or CSO files and extract their information to generate a recognized and standard file name, but not changing the properties inside the PSP games. Some classes of jpcsp project are used, jpcsp is an open source Java emulator of PlayStation Portable console system. See http://jpcsp.org/ for more information, code can be downloaded from https://github.com/jpcsp/jpcsp. This application is partially based and inspired on UmdBrowser (https://github.com/sinsinpub/jumdbrowser), an application to list and navigate into UMD images.

The code is written in Java using the latest Swing Layout library, so this desktop application can use the OS native interface (tested on Mac OS X, Windows and Linux/Ubuntu) and run on all of them. It comes in 2 languages: English and Spanish, you are able to choose it when the application starts. The IDE used to create this project was NetBeans 7.1, but it is a Maven project so you are able to open this project in any IDE that supports Maven. If you want to see a detailed log of the actions of the application, run it from a terminal (or console) and check the outputs (log4j was implemented for this purpose).

Java JRE 6+ is required. All required libraries are included to be more portable.