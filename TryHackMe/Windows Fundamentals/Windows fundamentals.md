RDP: https://www.cyberark.com/resources/threat-research-blog/explain-like-i-m-5-remote-desktop-protocol-rdp

`lusrmgr.msc` **Local Users and Management**.

`msconfig`
`taskmgr`
The **Computer Management** (`compmgmt.msc`) utility has three primary sections: System Tools, Storage, and Services and Applications

 **System Information** (`msinfo32`)
 The  information in **System Summary** is divided into three sections:
-   **Hardware Resources**
-   **Components**
-   **Software Environment**

What is **Resource Monitor** (`resmon`)?

Per Microsoft, "_Resource Monitor displays per-process and aggregate CPU, memory, disk, and network usage information, in addition to providing details about which processes are using individual file handles and modules. Advanced filtering allows users to isolate the data related to one or more processes (either applications or services), start, stop, pause, and resume services, and close unresponsive applications from the user interface. It also includes a process analysis feature that can help identify deadlocked processes and file locking conflicts so that the user can attempt to resolve the conflict instead of closing an application and potentially losing data._"

As some of the other tools mentioned in this room, this utility is geared primarily to advanced users who need to perform advanced troubleshooting on the computer system.  

In the Overview tab, Resmon has four sections:

-   **CPU**
-   **Disk**
-   **Network**
-   **Memory**

`ipconfig /?`
`netstat`
  
In System Configuration, what is the full command for Internet Protocol Configuration?
`C:\Windows\System32\cmd.exe /k %windir%\system32\ipconfig.exe`

`regedt32.exe`

way to access Windows Update is from the Run dialog box, or CMD, by running the command `control /name Microsoft.WindowsUpdate`.

#### Firewall:
Command to open the Windows Defender Firewall is `WF.msc`.