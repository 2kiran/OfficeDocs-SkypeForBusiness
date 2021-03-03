---
title: Customize Microsoft apps in Teams
author: cichur
ms.author: v-cichur
manager: serdars
ms.reviewer: vaagarw
ms.topic: article
ms.tgt.pltfrm: cloud
ms.service: msteams
audience: Admin
ms.collection: 
- M365-collaboration
- Teams_ITAdmin_Help
f1.keywords:
- NOCSH
appliesto: 
- Microsoft Teams
localization_priority: Normal
search.appverid: MET150
description: Learn how to customize apps in Microsoft Teams. 
ROBOTS: NOINDEX, NOFOLLOW
---

# Customize apps in Microsoft Teams

[!INCLUDE [preview-feature](includes/preview-feature.md)]

 Microsoft Teams provides apps to improve the Teams experience. Some app developers allow an app to be customized by the Teams admin. The admin can customize or rebrand the app based on the organizational needs from the Teams admin center **Manage apps** page. The details you can customize are:

- short name
- short description
- full description
- privacy policy URLs
- website URL
- terms of use URLs
- color icon
- outline icon
- accent color

See the [Teams Manifest schema](https://docs.microsoft.com/microsoftteams/platform/resources/schema/manifest-schema) for details about the fields that you can customize.

> [!Note]
> Changes to branding might require up to 24 hours for the users to see the changes.

## Customize the app's details

To start customizing an app, complete the following steps:

1. Sign in to the Teams admin center.
2. Expand **Teams Apps** and select **Manage apps**.
3. Check the **Customizable** column of the apps list and sort by apps that are customizable.

   ![The customize column that's sorted](media/customize-column.png)

   There are three entry points to access the customize features:

   - Select next to the app that you want to customize, and then select **Customize**.

     ![The customize selection](media/select-customize.png)

   - Select the app name and then **Customizable**.

     ![The customize selection](media/app-details-customizable.png)

   - Select the app name, and then select **Customize** from the **Actions** dropdown.

     ![The customize selection](media/customize-action-menu.png)

5. Expand the **Details** section and customize the following fields:

    - Short name
    - Short description
    - Full description
    - Website
    - Privacy policy URLs
    - Terms of use URLs

   ![The customize selection](media/customize-apps-fields.png)

> [!Note]
> Only the fields that the app developer has assigned as customizable will be visible.

5. Expand the **Icon** section.

   a. Upload an icon. Use one full-color icon (192x192) pixel in PNG format.

   b. Choose an icon outline color. Use one transparent outline (32x32) pixel in PNG format.

   c. Select an app accent color that matches the icon.

    ![Customize the icon panel](media/customize-icon-color.png)

6. Once your app has been customized, select **Apply**.

7. Select **Publish** to publish the customized app.

   The customized app is now listed in your **Manage apps** page. You'll have only one version of the app, since customizing the app features doesn't create a copy of the app.

Now your Teams end users can open their Teams client to see the customized app.

   ![Customized app in Teams client](media/customized-app-in-teams.png)

> [!Note]
> In case the app publisher no longer allows a field to be customizable, a message appears on the app details page notifying the admin about the fields that can't be customized any longer. All the changes made to that field will be reverted to the original values.

 ![Selected app that can't be customized](media/customized-not-allowed.png)

## Review app details

You might want to see the app details to review the information.

1. Sign in to the Teams admin center.

2. Expand **Teams Apps** and select **Manage apps**.

3. Select the app name.

4. View the app details, including the original app name **Short name from publisher**.

   ![Customize the icon panel](media/app-details-original-name.png)

   The **Short name from publisher** field is only visible if you've changed the app's short name.

## Reset app details to default

At any time, you can reset the app details to the original settings.

1. Sign in to the Teams admin center.

2. Expand **Teams Apps** and select **Manage apps**.

3. Select the app name.

4. Select **Reset to default** from the **Actions** dropdown.

   ![Select reset to default highlighted](media/select-reset.png)

## Frequently asked questions - placeholder

## Related article

- [Manage apps](manage-apps.md)
- [Customize your app store](customize-your-app-store.md)
- [Publish a custom app](submit-approve-custom-apps.md)
