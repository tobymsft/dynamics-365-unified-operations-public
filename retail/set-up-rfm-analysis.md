---
# required metadata

title: Set up RFM analysis | Microsoft Docs
description: This topic explains how to set up a Recency, Frequency, and Monetary (RFM) analysis of your customers.
author: josaw1
manager: AnnBe
ms.date: 2016-04-07 15:11:25
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 

# optional metadata

# keywords: 
# ROBOTS: 
audience: Application User
# ms.devlang: 
ms.reviewer: 2041
ms.suite: Released- Dynamics AX 7.0.0
# ms.tgt_pltfrm: 
ms.custom: 78943
ms.assetid: 934d60df-7d55-41a2-bcea-9e2729d9d906
ms.region: global
ms.industry: Retail
ms.author: josaw

---

# Set up RFM analysis

This topic explains how to set up a Recency, Frequency, and Monetary (RFM) analysis of your customers.

Recency, frequency, and monetary (RFM) analysis is a marketing tool that your organization can use to evaluate the data that is generated by customer purchases. After you set up RFM analysis, customers are assigned a calculated RFM score as they make purchases. The RFM score can be a three-digit rating or an aggregate number, depending on how your organization has configured RFM analysis. If your organization uses a three-digit rating for the score, the first digit is the customer's recency rating (how recently the customer made a purchase from your organization). The second digit is the customer's frequency rating (how often the customer makes purchases from your organization). The third digit is the customer's monetary rating (how much the customer spends when he or she makes purchases from your organization). For example, your organization has set the ratings on a scale of 1 through 5, where 5 is the highest rating. In this case, a customer rating of 535 tells you the following information about the customer:

-   **Recency rating of 5** – The customer recently made a purchase.
-   **Frequency rating of 3** – The customer purchases products from your organization moderately often.
-   **Monetary rating of 5** – When the customer makes a purchase, he or she spends a significant amount of money.

If your organization uses an aggregate number for the score, the individual ratings are added together. For the same example, the customer has a rating of 13 (5 + 3 + 5).
