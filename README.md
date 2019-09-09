# NITRSCT
- Dataset for software security domain
- Debug.rar contains the software/service used to trace the system calls.
- System Call Tracer For any Windows (current software for OS kernel version: 18362.175)

# Prerequisites
- Requires .NET Framework 4.6.1 or newer
- Windows 10 version 1903 OS Build 18362.175

# Quick start instructions
- Open an elevated command prompt or powershell by right clicking the icon and choosing "Run as Administrator"
- Change to the folder where DemoTracer.exe is located
- Install the service by running:
- InstallUtil.exe (path to Demotracer.exe)
- like this InstallUtil.exe C:\Users\pshkr\source\repos\DemoTracer\DemoTracer\bin\Debug\DemoTracer.exe
- To uninstall the service, run:
- InstallUtil.exe -u (path to Demotracer.exe)
- like this InstallUtil.exe -u C:\Users\pshkr\source\repos\DemoTracer\DemoTracer\bin\Debug\DemoTracer.exe

# Overview
- Data storage
- Data is stored in C:\Windows\Temp\DemoTracer\
# NOTE
- We will update the tracer software, whenever kernel version changes, so that the researchers/industrialists can create updated dataset always.
- Upto 18362.175 version, dataset is already uploaded and is available for download.
- If any request is there, you can ping me on this github account.

