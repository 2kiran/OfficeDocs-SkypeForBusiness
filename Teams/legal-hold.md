---
title: Place a Microsoft Teams user or team on legal hold
author: markjjo
ms.author: markjjo
manager: laurawi
ms.topic: article
ms.service: msteams
audience: admin
ms.collection: 
  - M365-collaboration
ms.reviewer: anwara
search.appverid: MET150
f1.keywords:
- NOCSH
description: "Learn to place a Microsoft Teams user or team on legal hold using the Security & Compliance Center and learn what needs a legal hold based on data requirements."
appliesto: 
  - Microsoft Teams
---

# Place a Microsoft Teams user or team on legal hold

When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including Teams chat messages that are relevant to the case. Organizations may need to preserve all messages related to a specific topic or for certain individuals. This article will cover legal hold in Microsoft Teams. To hold content across Microsoft 365, see [Create an eDiscovery hold](https://docs.microsoft.com/microsoft-365/compliance/create-ediscovery-holds)

> [!NOTE]
> In February 2020, we turned on legal hold for private channels. Private channel chats are stored in user mailboxes, while normal channel chats are stored in the Teams’ group mailbox. If there is already a legal hold in place for a user mailbox, the hold policy will now automatically apply to private channel messages stored in that mailbox. There is no further action needed for an admin to turn this on. Legal hold of files shared in private channels is also supported.

Within Microsoft Teams, an entire team or select users can be put on legal hold. Doing that will make sure that all messages that were exchanged in those teams (including private channels) or messages exchanged by those individuals are discoverable by the organization's compliance managers or Teams Admins.

> [!NOTE]
> Placing a user on hold doesn't automatically place a group on hold or vice-versa.

To put a user or a team on legal hold:

1. Navigate to the [Security & Compliance Center](https://go.microsoft.com/fwlink/?linkid=854628). When you create a new case, you are presented with the option to place mailboxes or sites on hold.

2. Go to **eDiscovery** and create a case by clicking **Create a case**. After the case is created, open it.
  
   ![Microsoft Teams eDiscovery tab is selected, showing the Create a case button.](media/LegalHold1.png)

   > [!NOTE]
   > You can also place a user on a hold that's associated with an Advanced eDiscovery case. For more information, see [Manage holds in Advanced eDiscovery](https://docs.microsoft.com/microsoft-365/compliance/managing-holds).

3. Go to the **Holds** tab on the top menu and click **Create** to create a hold. Placing a user or a team on hold preserves all the messages exchanged by those users or messages. When you create a new case, you are presented with the option to place mailboxes or sites on hold.

   ![An image showing the Holds tab selected, and the Create button underneath.](media/LegalHold2.png)
    
    1. **Name your hold**. Select a descriptive and unique name for the hold you are going to create.
  
       ![This screenshot shows the Name your hold tab, where you can enter in a name and description for the hold you are creating.](media/LegalHold3.png)

    1. **Choose location**. Choose whether you want the hold to be applied on a user or on an entire Team (hold cannot be applied on individual channels for now). Note: if a user is on hold, all their messages would be on hold, including whatever they sent in a 1:1 chat, 1:many or group chat, or a channel conversation (including private channels).
    ![Here we have the Choose locations section of Create a new hold, where you can make decisions on what M365 options, including Microsoft Teams, you wish the hold to apply to.](media/LegalHold4.png)

    2. **Create query**. You can customize the hold if you want more granularity in the hold policy. For example, you can specify keywords to look for, or you can add more conditions, that would need to be satisfied for the hold to take effect.
    
    3. **Review your settings** before creating the hold.

After the legal hold has been created, you can search the content retained by any hold policy. For more information, see [Conduct an eDiscovery investigation in Teams](eDiscovery-investigation.md).

> [!IMPORTANT]
> When a user or group is placed on hold, all message copies will be retained. For example, if a user posted a message in a channel and then modified the message, in a hold scenario, both copies of the message are retained. Without the legal hold in-place, only the latest message is retained.

As a helpful guide, you can use the table below to understand what needs to be placed on Legal Hold based on data requirements:

|Scenario  |What to place on hold|
|---------|---------|
|Microsoft Teams chats content by a user (for example, 1:1 chats, 1:N or group chats, private channel conversations, and [card content](https://docs.microsoft.com/microsoftteams/platform/task-modules-and-cards/what-are-cards))     |User mailbox         |
|Microsoft Teams Channel chats and card content (excluding private channels)   |Group mailbox used for the team         |
|Microsoft Teams content (for example, team Wiki and files)     |SharePoint site used by the team         |
|Microsoft Teams private channel files     |Dedicated Private Channel SharePoint Site     |
|User's private content     |OneDrive for Business site of the user         |

> [!NOTE]
> To retain communication in private channels, you need to put the user mailboxes (private channel users) on hold. When searching for content in private channels, you should search that user's mailbox. As previously, private channel chats are stored in user mailboxes, not in group mailbox of a Team.
