---
description: "MSSQLSERVER_3013"
title: MSSQLSERVER_3013
ms.custom: ""
ms.date: 08/20/2020
ms.service: sql
ms.reviewer: ramakoni1, pijocoder, suresh-kandoth, Masha
ms.subservice: supportability
ms.topic: "reference"
helpviewer_keywords: 
  - "3013 (Database Engine error)"
ms.assetid: 
author: suresh-kandoth
ms.author: ramakoni
---

# MSSQLSERVER_3013
 [!INCLUDE [SQL Server](../../includes/applies-to-version/sqlserver.md)]

## Details

|Attribute|Value|
|---|---|
|Product Name|SQL Server|
|Event ID|3013|
|Event Source|MSSQLSERVER|
|Component|SQLEngine|
|Symbolic Name|DMP_ABORT|
|Message Text|BACKUP DATABASE is terminating abnormally /RESTORE DATABASE is terminating abnormally.|

## Explanation

This is a generic error that occurs when a backup or restore operation is interrupted. 

## User action

Examine the SQL Error log for other messages that occur alongside this error for additional information and troubleshooting. For more information review [Troubleshoot SQL Server backup and restore operations](/troubleshoot/sql/database-engine/backup-restore/backup-restore-operations).


