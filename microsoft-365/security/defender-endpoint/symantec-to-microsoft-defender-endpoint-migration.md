---
title: Migrate from Symantec to Microsoft Defender for Endpoint
description: Get an overview of how to make the switch from Symantec to Microsoft Defender for Endpoint
keywords: migration, Microsoft Defender for Endpoint, edr
search.product: eADQiWindows 10XVcnh
search.appverid: met150
ms.prod: m365-security
ms.technology: mde
ms.mktglfcycl: deploy
ms.sitesec: library
ms.pagetype: security
ms.author: deniseb
author: denisebmsft
localization_priority: Normal
manager: dansimp
audience: ITPro
ms.collection: 
  - M365-security-compliance
  - m365solution-symantecmigrate
  - m365solution-overview
ms.topic: article
ms.date: 05/14/2021
ms.custom: migrationguides
ms.reviewer: depicker, yongrhee, chriggs
---

# Migrate from Symantec to Microsoft Defender for Endpoint
If you are planning to switch from Symantec Endpoint Protection (Symantec) to [Microsoft Defender for Endpoint](microsoft-defender-endpoint.md) (Microsoft Defender for Endpoint), you're in the right place. Use this article as a guide.

**Applies to:**
- [Microsoft Defender for Endpoint](https://go.microsoft.com/fwlink/p/?linkid=2154037)
- [Microsoft 365 Defender](https://go.microsoft.com/fwlink/?linkid=2118804)

:::image type="content" source="images/symantec-mde-migration.png" alt-text="Overview of migrating from Symantec to Defender for Endpoint":::

When you make the switch from Symantec to Defender for Endpoint, you begin with your Symantec solution in active mode, configure Defender for Endpoint in passive mode, onboard to Defender for Endpoint, and then set Defender for Endpoint to active mode and remove Symantec.

## The migration process

When you switch from Symantec to Microsoft Defender for Endpoint, you follow a process that can be divided into three phases, as described in the following table:

![Migration phases - prepare, setup, onboard](images/phase-diagrams/migration-phases.png)

|Phase |Description |
|--|--|
|[Prepare for your migration](symantec-to-microsoft-defender-atp-prepare.md) |During the **Prepare** phase, you update your organization's devices, get Microsoft Defender for Endpoint, plan your roles and permissions, and grant access to the Microsoft Defender Security Center. You also configure your device proxy and internet settings to enable communication between your organization's devices and Defender for Endpoint. |
|[Set up Microsoft Defender for Endpoint](symantec-to-microsoft-defender-atp-setup.md) |During the **Setup** phase, you enable Microsoft Defender Antivirus and set it to passive mode. You also configure settings & exclusions for Microsoft Defender Antivirus and Symantec Endpoint Protection. Then, you create your device groups, collections, and organizational units. Finally, you configure your antimalware policies and real-time protection settings.|
|[Onboard to Microsoft Defender for Endpoint](symantec-to-microsoft-defender-atp-onboard.md) |During the **Onboard** phase, you onboard your devices to Microsoft Defender for Endpoint, confirm that Microsfot Defender Antivirus is running in passive mode, and verify that your endpoints are communicating with Defender for Endpoint. Then, you uninstall Symantec and make sure that Defender for Endpoint is working correctly. |

## What's included in Microsoft Defender for Endpoint?

In this migration guide, we focus on [next-generation protection](microsoft-defender-antivirus-in-windows-10.md) and [endpoint detection and response](overview-endpoint-detection-response.md) capabilities as a starting point for moving to Microsoft Defender for Endpoint. However, Microsoft Defender for Endpoint includes much more than antivirus and endpoint protection. Microsoft Defender for Endpoint is a unified platform for preventative protection, post-breach detection, automated investigation, and response. The following table summarizes features and capabilities in Microsoft Defender for Endpoint. 

| Feature/Capability | Description |
|---|---|
| [Threat & vulnerability management](next-gen-threat-and-vuln-mgt.md) | Threat & vulnerability management capabilities help identify, assess, and remediate weaknesses across your endpoints (such as devices). |
| [Attack surface reduction](overview-attack-surface-reduction.md) | Attack surface reduction rules help protect your organization's devices and applications from cyberthreats and attacks. |
| [Next-generation protection](microsoft-defender-antivirus-in-windows-10.md) | Next-generation protection includes Microsoft Defender Antivirus to help block threats and malware. |
| [Endpoint detection and response](overview-endpoint-detection-response.md) | Endpoint detection and response capabilities detect, investigate, and respond to intrusion attempts and active breaches.  |
| [Advanced hunting](advanced-hunting-overview.md) | Advanced hunting capabilities enable your security operations team to locate indicators and entities of known or potential threats. |
| [Behavioral blocking and containment](behavioral-blocking-containment.md) | Behavioral blocking and containment capabilities help identify and stop threats, based on their behaviors and process trees even when the threat has started execution. |
| [Automated investigation and remediation](automated-investigations.md) | Automated investigation and response capabilities examine alerts and take immediate remediation action to resolve breaches. |
| [Threat hunting service](microsoft-threat-experts.md) (Microsoft Threat Experts) | Threat hunting services provide security operations teams with expert level monitoring and analysis, and to help ensure that critical threats aren't missed. |

**Want to learn more? See [Microsoft Defender for Endpoint](microsoft-defender-endpoint.md).**

## Next step

- Proceed to [Prepare for your migration](symantec-to-microsoft-defender-atp-prepare.md).
