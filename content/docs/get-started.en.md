---
title: Get Started
description: Recommended entry point for scope checks, preparation and pilot rollout.
---

The right way to start with this product is **not** a fast broad rollout, but a **clean pre-check** and a **controlled test on a pilot device**.

{{< callout type="warning" >}}
Before production use, always start on a **pilot / non-production device** and make sure **backup / snapshot / recovery** are in place.
{{< /callout >}}

## 1. Check the scope first

Before even thinking about rollout, make sure:

- the target system is **Windows 11 Pro**
- **25H2 is the primary target release**, while **24H2 remains supported**
- no AD, domain GPO, Intune, MDM or Autopilot management is active
- the deployment happens in a **small workgroup or single-device environment**
- the intended use is within the documented v1 scope

## 2. Verify the basics before the first test

At minimum, ensure:

- a current backup or snapshot exists
- recovery in case of failure is known
- for BitLocker: the **recovery key** is secured
- execution takes place with **local administrator rights**
- the system is fully updated
- a reboot after updates has been completed
- printers, NAS, network drives, RDP and business applications are considered

## 3. Choose the pilot device deliberately

A good pilot device is:

- representative of the later target fleet
- not immediately business-critical
- easy to document
- possible to reset in a controlled way in case of failure

## 4. Review after the test

After applying the product, at minimum verify:

- sign-in works
- network access works
- internet access works
- printers work
- network drives / NAS work
- RDP / remote support works, if needed
- business applications start correctly
- Windows Security Center shows no new critical warnings
- Event Viewer shows no new group policy errors

## 5. Only then roll out further

If the pilot device and function test are clean, rollout can be extended **in a controlled way** to additional systems.

## Next

- [Support Matrix](support-matrix)
- [Pre-Deployment Checklist](pre-deploy-checklist)
- [FAQ](faq)
- [Product](../product)
- [Packages & Delivery](../buy)
