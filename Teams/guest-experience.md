---
title: What the guest experience is like
ms.author: mikeplum
author: MikePlumleyMSFT
manager: serdars
ms.topic: conceptual
audience: admin
ms.service: msteams
ms.reviewer: sbhatta
search.appverid: MET150
description: This article describes the Microsoft Teams functionality available to guest users and also answers some of the most common FAQs related to it.
f1.keywords:
- NOCSH
localization_priority: Normal
ms.collection: 
  - Teams_ITAdmin_GuestAccess
  - M365-collaboration
appliesto: 
  - Microsoft Teams
ms.custom: seo-marvel-apr2020
---

What the guest experience is like
=================================

When a guest is invited to join a team, they receive a welcome email message. This message includes some information about the team and what to expect now that they're a member. The guest must accept the invitation by selecting **Open Microsoft Teams** in the email message before they can access the team and its channels.
    
![Screenshot showing an example of a welcome email message](media/guest-experience-image1.png)
    
All team members see a message in the channel thread announcing that the team owner has added a guest and providing the guest's name. Everyone on the team can identify easily who is a guest. A tag in the upper-right corner of the channel thread indicates the number of guests on the team and a **(Guest)** label appears next to each guest's name.

![Screenshot showing tag that indicates number of guests on the team](media/guest-experience-image2.png)

Check out these videos about the guest experience in Teams:
- [Join a team as a guest](https://support.office.com/article/join-a-team-as-a-guest-928d1eef-61e2-49ec-b754-c2fe86b34824)
- [Join a Teams meeting with guests](https://support.office.com/article/join-a-company-meeting-a120c282-063d-46b8-b973-851197ab75d8)


## Comparison of team member and guest capabilities

The following table compares the Teams functionality available for an organization's team members and its guests.

|**Capability in Teams**|**Teams user in the organization**|**Guest user**|
|:-----|:-----|:-----|
|Create a channel  <br/>  *Team owners control this setting.*  <br/> |&#x2713;|&#x2713;|
|Participate in a private chat  <br/> |&#x2713;|&#x2713;|
|Participate in a channel conversation  <br/> |&#x2713;|&#x2713;|
|Post, delete, and edit messages  <br/> |&#x2713;|&#x2713;|
|Share a channel file  <br/> |&#x2713;|&#x2713;|
|Share a chat file  <br/> |&#x2713;||
|Add apps (tabs, bots, or connectors)  <br/> |&#x2713;||
|Create meetings or access schedules  <br/> |&#x2713;||
|Access OneDrive for Business storage  <br/> |&#x2713;||
|Create tenant-wide and teams/channels guest access policies  <br/> |&#x2713;||
|Invite a user outside the Microsoft 365 or Office 365 organization's domain <br/>  *Team owners control this setting.*  <br/> <br/> |&#x2713;||
|Create a team  <br/> |&#x2713;||
|Discover and join a public team  <br/> |&#x2713;||
|View organization chart  <br/> |&#x2713;||
|Use inline translation  <br/> |&#x2713;||
|Become team owner  <br/> |&#x2713;||

   
The following table shows the calling and meeting features available to guests, compared to other types of users.

| Calling feature | Guest | E1 and E3 user | E5 and Enterprise Voice user |
| --------------- | ----- | -------------- | -------------- |
| VOIP calling | Yes | Yes | Yes |
| Group calling | Yes | Yes | Yes |
| Core call controls supported (hold, mute, video on/off, screen sharing) | Yes | Yes | Yes |
| Transfer target | Yes | Yes | Yes |
| Can transfer a call | Yes | Yes | Yes |
| Can consultative transfer | Yes | Yes | Yes |
| Can add other users to a call via VOIP | Yes | Yes | Yes |
| Can add users by phone number to a call | No | No | Yes |
| Forward target | No | Yes | Yes |
| Call group target | No | Yes | Yes |
| Unanswered target | No | Yes | Yes |
| Can be the target of a federated call | No | Yes | Yes |
| Can make a federated call | No | Yes | Yes |
| Can immediately forward their calls | No | No | Yes |
| Can simultaneously ring their calls | No | No | Yes |
| Can route their unanswered calls | No | No | Yes |
| Missed calls can go to voicemail | No | No<sup>1</sup> |Yes |
| Have a phone number that can receive calls | No | No | Yes |
| Can dial phone numbers | No | No | Yes |
| Can access call settings | No | No | Yes |
| Can change voicemail greeting | No | No<sup>1</sup> | Yes |
| Can change ringtones | No | No  | Yes |
| Supports TTY | No | No | Yes |
| Can have delegates | No | No | Yes |
|  Can be a delegate | No | No | Yes |


<sup>1</sup> This feature will be available soon.

> [!NOTE]
> Microsoft 365 and Office 365 admins control the features available to guests. 

## Frequently asked questions

### How do I leave an organization that I've been invited to?
If you've been invited to an organization that you don't want to be a guest of, you can choose to leave the organization. For more information, go to [Leave an organization as a guest user](https://docs.microsoft.com/azure/active-directory/b2b/leave-the-organization). Alternatively, you can ask the admin of the organization to remove you from their tenant. Note that in either case you'll need to be re-invited to the tenant if you want to access the organization in the future.

### Do guests have the same capabilities as team members?
No. For more information about what a guest can and cannot do, go to [Comparison of team member and guest capabilities](#comparison-of-team-member-and-guest-capabilities) in this article.

### Do guests have access to OneDrive for Business?
No.

### Do guests have access to SharePoint files?
Yes.

### Can guests search within files?
No.

### Can guests attach files?
Yes, a guest can attach files in these two ways:

   - Select **Files** in the left pane, and then browse to the file location.
   - Upload files from their computer.

### Can a guest download a file in a private chat?
Yes, they can receive a file from a member in a private chat, and then download it to their desktop.
