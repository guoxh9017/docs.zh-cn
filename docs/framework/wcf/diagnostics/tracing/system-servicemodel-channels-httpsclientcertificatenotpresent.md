---
title: "System.ServiceModel.Channels.HttpsClientCertificateNotPresent | Microsoft Docs"
ms.custom: ""
ms.date: "03/30/2017"
ms.prod: ".net-framework-4.6"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "dotnet-clr"
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: b13ef1b6-e340-401d-93ca-2710c3842205
caps.latest.revision: 5
author: "Erikre"
ms.author: "erikre"
manager: "erikre"
caps.handback.revision: 5
---
# System.ServiceModel.Channels.HttpsClientCertificateNotPresent
需要客户端证书。在请求中未找到任何证书。  
  
## 说明  
 此跟踪指示 HTTPS 侦听器收到与客户端证书无关的 HTTPS 请求。因为侦听器被配置为对所有 HTTPS 请求都要求提供客户端证书，所以侦听器未能验证该客户端的真实性。  
  
## 请参阅  
 [跟踪](../../../../../docs/framework/wcf/diagnostics/tracing/index.md)   
 [使用跟踪来排除应用程序故障](../../../../../docs/framework/wcf/diagnostics/tracing/using-tracing-to-troubleshoot-your-application.md)   
 [管理和诊断](../../../../../docs/framework/wcf/diagnostics/index.md)