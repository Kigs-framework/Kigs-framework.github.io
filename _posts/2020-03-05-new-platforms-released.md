---
layout: post
title:  "New platforms released"
---

### Prerequisites

To build Android applications, you will need to install "The Mobile development with C++ workload" for Microsoft Visual Studio. Please check Microsoft documentations to do this.
It's also better to use a recent NDK and to set NDK path in Visual Studio Tools > Options dialog box, Cross Platform > C++ > Android section.

We used to build iOS platform also using Microsoft Visual Studio, but didn't manage to install vcremote on Mac hardware recently.

### Android platforms

A new script : generateAndroidCMakeVS.bat can be found in kigs/script directory. 

Executing the script create a Build/solutionAndroidVSCMake directory. Browse to Build/solutionAndroidVSCMake/kigs/projects/theProjectYouWantToBuild and open corresponding sln in Visual Studio.
Set packaging project as the startup project, choose the build configuration, and build.

### iOS platforms

Source code to build iOS application is now available, but in untested state and without generation script. 
If you are interesting in helping us to set up iOS platform, please let us know.

