---
title: Real-time event processing with Stream Analytics event processing | Microsoft Docs
description: Learn how a set of Azure services can interoperate for enabling real-time event processing and analytics.
keywords: real-time processing, event processing, reference architecture
services: stream-analytics,event-hubs,storage,sql-database
documentationcenter: ''
author: jeffstokes72
manager: jhubbard
editor: ''

ms.assetid: 11af48bc-313c-4527-8c80-91088dc9f3c6
ms.service: stream-analytics
ms.workload: big-data
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: article
ms.date: 01/24/2017
ms.author: jeffstok

---
# Reference architecture: Real-time event processing with Microsoft Azure Stream Analytics
The reference architecture for real-time event processing with Azure Stream Analytics is intended to provide a generic blueprint for deploying a real-time platform as a service (PaaS) stream-processing solution with Microsoft Azure.

## Summary
Traditionally, analytics solutions have been based on capabilities such as ETL (extract, transform, load) and data warehousing, where data is stored prior to analysis. Changing requirements, including more rapidly arriving data, are pushing this existing model to the limit. The ability to analyze data within moving streams prior to storage is one solution, and while it is not a new capability, the approach has not been widely adopted across all industry verticals. 

Microsoft Azure provides an extensive catalog of analytics technologies that are capable of supporting an array of different solution scenarios and requirements. Selecting which Azure services to deploy for an end-to-end solution can be a challenge given the breadth of offerings. This paper is designed to describe the capabilities and interoperation of the various Azure services that support an event-streaming solution. It also explains some of the scenarios in which customers can benefit from this type of approach.

## Contents
* Executive Summary
* Introduction to Real-Time Analytics
* Value Proposition of Real-Time Data in Azure
* Common Scenarios for Real-Time Analytics
* Architecture and Components
  * Data Sources
  * Data-Integration Layer
  * Real-time Analytics Layer
  * Data Storage Layer
  * Presentation / Consumption Layer
* Conclusion

**Author:** Charles Feddersen, Solution Architect, Data Insights Center of Excellence, Microsoft Corporation

**Published:** January 2015

**Revision:** 1.0

**Download:** [Real-Time Event Processing with Microsoft Azure Stream Analytics](http://download.microsoft.com/download/6/2/3/623924DE-B083-4561-9624-C1AB62B5F82B/real-time-event-processing-with-microsoft-azure-stream-analytics.pdf)

## Get help
For further assistance, try our [Azure Stream Analytics forum](https://social.msdn.microsoft.com/Forums/home?forum=AzureStreamAnalytics)

## Next steps
* [Introduction to Azure Stream Analytics](stream-analytics-introduction.md)
* [Get started using Azure Stream Analytics](stream-analytics-real-time-fraud-detection.md)
* [Scale Azure Stream Analytics jobs](stream-analytics-scale-jobs.md)
* [Azure Stream Analytics Query Language Reference](https://msdn.microsoft.com/library/azure/dn834998.aspx)
* [Azure Stream Analytics Management REST API Reference](https://msdn.microsoft.com/library/azure/dn835031.aspx)

