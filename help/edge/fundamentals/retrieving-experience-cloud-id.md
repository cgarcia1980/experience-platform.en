---
title: Retrieving Experience Cloud ID
seo-title: Adobe Experience Platform Web SDK Retrieving Experience Cloud ID
description: Learn how to get Adobe Experience Cloud Id.
seo-description: Learn how to get Adobe Experience Cloud Id.
---

# (Beta) Retrieving Experience Cloud ID

>[!IMPORTANT]
>
>Adobe Experience Platform Web SDK is currently in beta and is not available to all users. The documentation and the functionality are subject to change.

Adobe Experience Cloud uses a unique ID for every consumer. If you want to use this unique ID, use the `getIdentity` command. `getIdentity` returns the existing ECID for the current visitor. For first-time visitors who don't have an ECID yet, this command generates a new ECID.

>[!NOTE]
>
>This method is typically used with custom solutions that require reading the Experience Cloud ID. It is not used by a standard implementation.

```javascript
alloy("getIdentity")
  .then(function(ecid) {
    // This function will get called with Adobe Experience Cloud Id when the command promise is resolved
  })
  .catch(function(error) {
    // The command failed.
    // "error" will be an error object with additional information
  })
```