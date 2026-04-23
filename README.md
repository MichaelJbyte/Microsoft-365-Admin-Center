# Microsoft-365-Admin-Center
Lab focused on familiarizing with the Microsoft 365 Admin Center layout to better my understanding of user settings, common troubleshooting scenarios, and everyday routines. 4/13/26

This lab simulates an office environment utilizing the Microsoft 365 Admin Center. I achieved greater knowledge of the layout by performing regular IT tasks such as user creation and management, policy enforcement, license distribution, and password resets.

## Tools & Environment

* Microsoft 365 Admin Center
* Exchange Admin Center
* Microsoft Intune Admin Center
* Microsoft Entra Admin Center

## Objectives
* Create and manage mulitple users
* Administer and remove Microsoft licenses and apps
* Perform user deletion and password resets
* Understand admin center layouts and tools

## Background: Microsoft 365 Admin Center

The Microsoft 365 Admin Center is a page used to easily manage users, devices, emails, teams, and more for a business operation. Administrators given access can assist employees with daily issues such as account lockout, lost emails, invalid licenses, and any other technical issues that may regard a user. Understanding the admin center is crucial to assisting others in an IT and cybersecurity role.

## Microsoft 365 Admin Center

Beginning the lab, I open up the Microsoft 365 Admin Center and am welcomed to the dashboard. This page will be very useful in providing shortcuts for frequent IT tasks such as user account management, resetting passwords, and even Microsoft 365 license alerts.

I took some time to study the home page layout to affiliate with recurring tasks I may perform and the shortcut locations relating to them.

___________________________________________________________________________
![photo1](https://github.com/MichaelJbyte/Microsoft-365-Admin-Center/blob/aaf7baaeba50e5112922c82cb9f6a1fa9608f17e/dashboard01.png)
___________________________________________________________________________

## User Account Management

My next course of action was to add user accounts to this environment. Clicking the "Users" tab on the left, I proceed to create three types of users that will have different roles related to the rest of the lab:
* User with licenses [1]
* User with no licenses [2]
* User with licenses, inteded to be blocked [3]
___________________________________________________________________________
![photo2](https://github.com/MichaelJbyte/Microsoft-365-Admin-Center/blob/aaf7baaeba50e5112922c82cb9f6a1fa9608f17e/add_user02.png)
___________________________________________________________________________

When creating the accounts, I took note of all the available options that are presented during creation such as **password creation, product license distribution, roles, and contact/personal information.**

After selectively constructing each user account, I view the new list of three users I created. Clicking on a user displays a user detail panel which houses a variety of information such as:
* Account details
* Password resetting
* Active licenses & apps

This panel is an essential page hosting a wide amount of information and options which I take note of, planning to return for completing tasks such as a password reset and account lockout.
___________________________________________________________________________
![photo3](https://github.com/MichaelJbyte/Microsoft-365-Admin-Center/blob/aaf7baaeba50e5112922c82cb9f6a1fa9608f17e/user_info01.png)
___________________________________________________________________________

## User Practice (Account Block, Password Reset, License Application)

### Account Block
The next task was to become familiar with common workplace scenarios such as an account lockout, password reset, and license management.

Utilizing the user detail panel from before, I select the option to block any log-in for the delegated user account, "BlockedUser Three." The panel confirms this action in bold red letters stating **Sign-in blocked**, but I further test this by attempting to login with the affected account. The login page notifies me that the account has been locked showing me the action has worked. 

The button to undo this ban is found in the exact same place, thus informing me all I need to handle account lockouts.

___________________________________________________________________________
![photo4](https://github.com/MichaelJbyte/Microsoft-365-Admin-Center/blob/main/blocked_user03.jpg)
___________________________________________________________________________

### Password Reset
The reset password function can be found under the same user panel and, although simple, it is a common solution to a regular issue found in the workplace.

___________________________________________________________________________
![photo5](https://github.com/MichaelJbyte/Microsoft-365-Admin-Center/blob/c315523708b0b760397e5968e8a512537e68baf7/psswd_reset02.png)
___________________________________________________________________________

I am presented with an option to prompt the user to change their password upon next login. I enable this option for testing purposes, however I do understand that depending on a businesses' practice, this may not be a secure option.

### License Application
My last task was to apply a Microsoft license to an account that was not initially given one. This is another common matter in which a user may not have access to the Microsoft 365 license or any necessary apps found within.

Found under the all-purpose user detail panel, I assign the product license and select applications, regarding to emails, to the user created without any license.

___________________________________________________________________________
![photo6](https://github.com/MichaelJbyte/Microsoft-365-Admin-Center/blob/c1ae78f0dfe4b806d8864b7ec05a4c191a9a1a05/user_license01.png)
___________________________________________________________________________


## Microsoft Entra, Exchange, & Intune Admin Center 



## Results & Observations (*)

Live packet captures provide immediate visibility into network activity
Filters significantly reduce noise in large packet captures
Packet inspection reveals detailed protocol and session information

## IT & Security Relevance

The Microsoft 365 Admin Center is a tool required daily for roles such as IT support, commonly assesing problems users face daily in the workplace, and enforcing security policies for operational safety. This lab assisted in a foundational understanding of the many settings and options available in the admin center I can expect to use for realisitic scenarios.

# Lessons Learned (*)
This lab helped me become comfortable navigating Wireshark and understanding the structure of captured network traffic. I learned how to apply filters effectively, inspect packets, and interpret basic communication patterns. In future labs, I would expand this work by analyzing specific protocols in more depth and testing capture scenarios within a virtualized network.
