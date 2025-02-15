---
title: Windows roaming settings reference - Azure Active Directory
description: Settings that will be roamed or backed up in Windows with ESR

services: active-directory
ms.service: active-directory
ms.subservice: devices
ms.topic: reference
ms.date: 02/25/2022

ms.author: joflore
author: MicrosoftGuyJFlo
manager: karenhoran
ms.reviewer: guovivian

ms.collection: M365-identity-device-management
---
# Windows roaming settings reference

The following is a list of the settings that will be roamed or backed up in Windows 10 or newer. 

## Windows Settings details

List of settings that can be configured to sync in recent Windows versions. These can be found in Windows 10 under **Settings** > **Accounts** > **Sync your settings** or **Settings** > **Accounts** > **Windows backup** > **Remember my preferences** on Windows 11.

| Settings | Windows 10 (21H1 or newer) |
| --- | --- |
| Keyboard: turn on toggle keys (off by default) | sync |
| Date, Time, and Region: country/region | sync |
| Date, Time, and Region: region format (locale) | sync |
| Language: language profile | sync |
| Language: list of keyboards | sync |
| Wi-Fi: Wi-Fi profiles (only WPA) | sync |

## Browser settings

For more information on the Sync behavior for the new Microsoft Edge, see the article [Microsoft Edge Sync](/deployedge/microsoft-edge-enterprise-sync).

Microsoft Edge browser setting group (favorites, reading list) syncing can be enabled or disabled by end users through Microsoft Edge browser Settings menu option.

![Account](./media/enterprise-state-roaming-windows-settings-reference/active-directory-enterprise-state-roaming-edge.png)

For Windows 10 version 1803 or later, Internet Explorer setting group (favorites, typed URLs) syncing can be enabled or disabled by end users through Internet Explorer Settings menu option. 

![Settings](./media/enterprise-state-roaming-windows-settings-reference/active-directory-enterprise-state-roaming-ie.png)

## Next steps

For an overview, see [enterprise state roaming overview](enterprise-state-roaming-overview.md).
