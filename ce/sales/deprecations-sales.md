---
title: Deprecations in Dynamics 365 Sales | MicrosoftDocs
description: Visit this page to see what's deprecated in Dynamics 365 Sales.
ms.date: 04/01/2022
ms.topic: article
author: lavanyakr01
ms.author: lavanyakr
manager: shujoshi
search.audienceType: 
  - admin
  - customizer
  - enduser
search.app: 
  - D365CE
  - D365CS
ms.custom: 
  - dyn365-sales
---
# Deprecations in Dynamics 365 Sales 

The features that have been deprecated in Sales are listed in this article. For more information on other deprecations that impact Dynamics 365 customer engagement apps, see [Important changes (deprecations) coming in Power Apps, Power Automate, and customer engagement apps](/power-platform/important-changes-coming) 

Administrators and IT professionals can use this information to prepare for future releases.

> [!Important]
> "Deprecated" means we intend to remove the feature or capability in a major future release. The feature or capability will continue to work and is fully supported until it is officially removed. This deprecation notification might span a few years. After removal, the feature or capability will no longer work. We are notifying you now so that you have sufficient time to plan and update your code before the feature or capability is removed.

## Internet Explorer 11 support for Dynamics 365 and Microsoft Power Platform is deprecated

Effective December 2020, Microsoft Internet Explorer 11 support for Microsoft Dynamics 365 and Microsoft Power Platform is deprecated. Internet Explorer 11 won’t be supported after August 2021. 

This will impact customers who use Dynamics 365 and Microsoft Power Platform products that are designed to be used through an Internet Explorer 11 interface. After August 2021, Internet Explorer 11 won't be supported for such Dynamics 365 and Microsoft Power Platform products. We recommend that customers transition to Microsoft Edge. 

For the complete list of products impacted by this change or for information on transitioning from Internet Explorer 11 to a supported browser, see [FAQ: Internet Explorer 11 deprecation for Dynamics 365 and Microsoft Power Platform Products](https://aka.ms/IEsupportDeprecationBAG). If you've questions, contact your Microsoft Customer Service representative or Microsoft Partner.

## Dynamic 365 Sales bot is deprecated

Effective June 2, 2020, the Dynamics 365 Sales bot, a feature that enables users to retrieve sales information through a bot within Dynamics 365 Sales app for Teams, will be deprecated. Until July 31, 2020, Microsoft will continue to provide support for the feature, but won't release any new functionality beyond what is already present. After July 31, 2020, you'll no longer be able to receive responses to conversations. The bot won’t be available for new customers. Existing customers may still be able to access the bot from the Chat, however the bot won't respond to questions.

It is our goal to deliver a powerful bot experience that allows users to retrieve and manage information. Based on usage data and feedback from our customers, we'll be working on a powerful, extensible set of capabilities and features that will allow you to intuitively access and interact with sales information—among other entities—through a bot interface. We'll keep you updated on timing for when this will be available.

## Dynamics 365 - Gamification is deprecated

Effective April 1, 2021, Dynamics 365 – Gamification is deprecated. Until September 30, 2021, Microsoft provided limited support for this solution. From October 1, 2021, the Dynamics 365 – Gamification solution won’t be functional. To uninstall Gamification, delete the **GamificationUpdater** and **Gamification** solutions from the Dynamics 365 organization. Note that you must first delete the **GamificationUpdater** solution followed by the **Gamification** solution. More information: [Delete a preferred solution](/previous-versions/dynamicscrm-2016/administering-dynamics-365/dn878909(v=crm.8)#Delete%20a%20preferred%20solution).


## Dynamics 365 assistant application for Teams

| &nbsp; | &nbsp; | 
|-------------|------------|
| Reason for deprecation/removal | Not legally required. |
| Replaced by another feature? | Yes. An improved version of the application for mobile devices with features that include some of the capabilities of Dynamics 365 assistant application for Teams. |
| Product areas affected | Application |
| Deployment option | All |
| Status | Removed: By October 15, 2020 |


## Dynamics 365 Product Visualize is deprecated

Effective October 04, 2021, Dynamics 365 Product Visualize is deprecated. After October 04, 2021 the product will cease to function and will no longer be supported.

## Dynamics 365 assistant cards - Opportunity at Risk (sentiment detection) and Opportunity at Risk (phrase detection)

Effective March 31, 2022, the Opportunity at Risk (sentiment detection) and Opportunity at Risk (phrase detection) cards are deprecated. After May 30, 2022, these cards will no longer be supported.     
The Opportunity at Risk cards, both sentiment detection and phrase detection, have been disabled from the backend and insights are no longer generated. However, these cards are still visible through the Settings page. When users are trying to activate these cards, activation fails.
 
[!INCLUDE[footer-include](../includes/footer-banner.md)]
