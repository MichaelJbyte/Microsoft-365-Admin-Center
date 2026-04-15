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

## Packet Capture & Initial Analysis (*)
To begin the lab, I installed Wireshark and the necessary Npcap. After launching the application, I ran a live packet capture on the active network interface.

Using the Statistics -> Conversations menu, I reviewed communication between IP addresses captured during the session. This view summarized protocol usage, packet counts, and source/destination addresses.

photo

This step provided an overview of network activity during the packet capture.

Filtering Traffic
Next, I practiced applying filters to narrow down packet results.

By selecting IP addresses from the Conversations window, I applied filters directly to isolate traffic related to specific hosts. I also used the display filter bar to manually enter filters for protocols and ports.

Example filter used:

tcp.port == 80 || udp.port == 80
Filters are essential when working with large captures, allowing analysts to focus on relevant packets related to an investigation or troubleshooting task.

Packet Inspection & Stream Analysis
I reviewed individual packet details in the packet pane, examining protocol layers and header information. I also explored the Follow Stream feature to reconstruct conversations from captured packets.

This feature is commonly used to analyze session-based traffic and can assist in identifying suspicious behavior, such as phishing attempts or unauthorized communications.

photo

Interface Customization
In addition, I explored Wireshark’s customization options through the Preferences menu, including:

Display layout adjustments
Field visibility
Color rules
Customizing these settings improves readability and helps quickly flag down packet types or anomalies during analysis.

___________________________________________________________________________
photo
___________________________________________________________________________
photo
___________________________________________________________________________

## Results & Observations (*)

Live packet captures provide immediate visibility into network activity
Filters significantly reduce noise in large packet captures
Packet inspection reveals detailed protocol and session information

## IT & Security Relevance

The Microsoft 365 Admin Center is a tool required daily for roles such as IT support, commonly assesing problems users face daily in the workplace, and enforcing security policies for operational safety. This lab assisted in a foundational understanding of the many settings and options available in the admin center I can expect to use for realisitic scenarios.

# Lessons Learned (*)
This lab helped me become comfortable navigating Wireshark and understanding the structure of captured network traffic. I learned how to apply filters effectively, inspect packets, and interpret basic communication patterns. In future labs, I would expand this work by analyzing specific protocols in more depth and testing capture scenarios within a virtualized network.
