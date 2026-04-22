**🌐Windows Fundamentals 1 — TryHackMe Walkthrough**

  <p align="center">
  <img src="https://github.com/user-attachments/assets/db061ee6-2220-4fe6-a14b-3fc94253bc1f" />
</p>

<p align="center">
  <a href="https://tryhackme.com/room/windowsfundamentals1xbx">
    <img src="https://img.shields.io/badge/TryHackMe-Windows Fundamentals 1-red?logo=tryhackme&logoColor=white">
  </a>
  <img src="https://img.shields.io/badge/Difficulty-Easy-green">
  <img src="https://img.shields.io/badge/Platform-Windows-blue">
</p>

--------------------------------------------------------------------------------------------------------------------------------------------------

**🚀Executive Summary**

This writeup covers the Windows Fundamentals 1 room on TryHackMe.

We will explore the Windows interface, file system, user account management, and essential system utilities.

This guide is designed for those looking to build a strong foundation in Windows OS navigation and configuration.

--------------------------------------------------------------------------------------------------------------------------------------------------

**Task 1 Windows Editions** 

Question 1 - What encryption can you enable on Pro that you can't enable in Home?
<details>
<summary>Reveal Answer</summary>

**BitLocker**

</details>

**Explanation** 

The comparison between Windows editions reveals that Pro includes BitLocker device encryption, a critical feature for securing data on lost or stolen devices.

--------------------------------------------------------------------------------------------------------------------------------------------------

**Task 2 Desktop GUI** 

Question 1 - Which selection will hide/disable the Search box?
<details>
<summary>Reveal Answer</summary>

**Hidden**

</details>

**Explanation** 

To hide the search box, right-click the taskbar, hover over Search, and select Hidden.

**--------------------------------------------------------------------------------------------------------------------------------------------------**

Question 2 - Which selection will hide/disable the Task View button?
<details>
<summary>Reveal Answer</summary>

**Show Task View button**

</details>

**Explanation** 

Right-click the taskbar and toggle the Show Task View button option to hide it.

**--------------------------------------------------------------------------------------------------------------------------------------------------**

Question 3 - Besides Clock and Network, what other icon is visible in the Notification Area?
<details>
<summary>Reveal Answer</summary>

**Action Center**

</details>

--------------------------------------------------------------------------------------------------------------------------------------------------

**Task 3 Introduction to Windows**

The Windows operating system is a complex ecosystem of files, utilities, and settings. 

This module provides a general overview of the Windows OS, navigating the user interface, and making system changes.

To follow along, launch the virtual machine provided in the room. You can access it via the in-browser view or Remote Desktop using the credentials below:

**Machine IP: MACHINE_IP**

**User: administrator**

**Password: letmein123!**

(No answer needed)


--------------------------------------------------------------------------------------------------------------------------------------------------

**Task 4 The File System**

Question 1 - What is the meaning of NTFS?
<details>
<summary>Reveal Answer</summary>

**New Technology File System**

</details>

--------------------------------------------------------------------------------------------------------------------------------------------------

**Task 5  The Windows\System32 Folders**

Question 1 - What is the system variable for the Windows folder?
<details>
<summary>Reveal Answer</summary>

**%windir%**

</details>

**Explanation** 

The System32 folder, located within the Windows directory, holds critical files vital for the OS's operation.

--------------------------------------------------------------------------------------------------------------------------------------------------

**Task 6 User Accounts, Profiles, and Permissions**

Question 1 - What is the name of the other user account?
<details>
<summary>Reveal Answer</summary>

**tryhackmebilly**

</details>

**Explanation** 

Open lusrmgr.msc, click on Users, and you will see the account listed.

**--------------------------------------------------------------------------------------------------------------------------------------------------**

Question 2 - What groups is this user a member of?
<details>
<summary>Reveal Answer</summary>

**Remote Desktop Users,Users**

</details>

**Explanation** 

Right-click the user tryhackmebilly, select Properties, and check the Member Of tab.

**--------------------------------------------------------------------------------------------------------------------------------------------------**

Question 3 - What built-in account is for guest access to the computer?
<details>
<summary>Reveal Answer</summary>

**Guest**

</details>

**--------------------------------------------------------------------------------------------------------------------------------------------------**

Question 4 - What is the account description?
<details>
<summary>Reveal Answer</summary>

**Built-in account for guest access to the computer/domain**

</details>


--------------------------------------------------------------------------------------------------------------------------------------------------

**Task 7 User Account Control**

Question 1 - What does UAC mean?
<details>
<summary>Reveal Answer</summary>

**User Account Control**

</details>


--------------------------------------------------------------------------------------------------------------------------------------------------

**Task 8 Settings and the Control Panel**


Question 1 - In the Control Panel, change the view to Small icons. What is the last setting in the Control Panel view?
<details>
<summary>Reveal Answer</summary>

**Windows Defender Firewall**

</details>

**Explanation** 

Open Control Panel, change “View by” to Small icons, and scroll to the bottom.

--------------------------------------------------------------------------------------------------------------------------------------------------

**Task 9 Task Manager**


Question 1 - What is the keyboard shortcut to open Task Manager?
<details>
<summary>Reveal Answer</summary>

**Ctrl+Shift+Esc**

</details>

--------------------------------------------------------------------------------------------------------------------------------------------------

**Task 10 Conclusion**

Again, this was a generic overview of the Windows OS. 

There are intermediate and advanced topics for each topic (task) that was covered in this room. 

Hence, Task 9 ended with a detailed blog post explaining the Task Manager in great detail. 

In future modules, we'll cover topics like the Windows folder, the management console, security tools (Windows Defender, Windows Firewall, etc.), to name a few. 


**I hope you found this helpful :)**

--------------------------------------------------------------------------------------------------------------------------------------------------
