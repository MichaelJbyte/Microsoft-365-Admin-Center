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

## Account Block & Password Reset

The next task was to become familiar with common workplace scenarios such as an account lockout and a password reset.

Utilizing the user detail panel from before, I select the option to block any log-in for the account I 

___________________________________________________________________________
![photo4](https://github.com/MichaelJbyte/Microsoft-365-Admin-Center/blob/main/blocked_user03.jpg)
___________________________________________________________________________

summarize how i am now familiar with that task. ^^^^

## Microsoft Intune Admin Center 

## Microsoft Entra Admin Center 

## Microsoft Exchange Admin Center 


## Results & Observations (*)

Live packet captures provide immediate visibility into network activity
Filters significantly reduce noise in large packet captures
Packet inspection reveals detailed protocol and session information

## IT & Security Relevance

The Microsoft 365 Admin Center is a tool required daily for roles such as IT support, commonly assesing problems users face daily in the workplace, and enforcing security policies for operational safety. This lab assisted in a foundational understanding of the many settings and options available in the admin center I can expect to use for realisitic scenarios.

# Lessons Learned (*)
This lab helped me become comfortable navigating Wireshark and understanding the structure of captured network traffic. I learned how to apply filters effectively, inspect packets, and interpret basic communication patterns. In future labs, I would expand this work by analyzing specific protocols in more depth and testing capture scenarios within a virtualized network.
