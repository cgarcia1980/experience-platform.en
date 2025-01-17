---
keywords: Experience Platform;home;popular topics;Azure Table Storage;azure table storage;ATS;ats
solution: Experience Platform
title: Azure Table Storage Source Connector Overview
topic-legacy: overview
description: Learn how to connect Azure Table Storage to Adobe Experience Platform using APIs or the user interface.
exl-id: 096e01b1-7e95-4e30-87de-d0976f8b438a
---
# [!DNL Azure Table Storage] connector

Adobe Experience Platform allows data to be ingested from external sources while providing you with the ability to structure, label, and enhance incoming data using Platform services. You can ingest data from a variety of sources such as Adobe applications, cloud-based storage, databases, and many others.

Experience Platform provides support for ingesting data from a third-party database. Platform can connect to different types of databases such as relational, NoSQL, or data warehouses. Support for database providers include [!DNL Azure Table Storage].

## IP address allow list

A list of IP addresses must be added to an allow list prior to working with source connectors. Failing to add your region-specific IP addresses to your allow list may lead to errors or non-performance when using sources. See the [IP address allow list](../../ip-address-allow-list.md) page for more information.

>[!IMPORTANT]
>
>The [!DNL Azure Table Storage] source connector currently does not support same-region connectivity to Platform. This means that if your Azure instance is using the same network region as Platform, then a connection to Platform sources cannot be established. Currently, only cross-region connectivity is supported. Please contact your Adobe account manager for more information.

The documentation below provides information on how to connect [!DNL Azure Table Storage] to Platform using APIs or the user interface:

## Connect [!DNL Azure Table Storage] to Platform using APIs

- [Create an Azure Table Storage base connection using the Flow Service API](../../tutorials/api/create/databases/ats.md)
- [Explore the data structure and contents of a database source using the Flow Service API](../../tutorials/api/explore/database-nosql.md)
- [Create a dataflow for a database source using the Flow Service API](../../tutorials/api/collect/database-nosql.md)

## Connect [!DNL Azure Table Storage] to Platform using the UI

- [Create an Azure Table Storage source connection in the UI](../../tutorials/ui/create/databases/ats.md)
- [Create a dataflow for a database source connection in the UI](../../tutorials/ui/dataflow/databases.md)
