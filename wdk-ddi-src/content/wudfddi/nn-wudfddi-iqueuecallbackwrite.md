---
UID: NN:wudfddi.IQueueCallbackWrite
title: IQueueCallbackWrite (wudfddi.h)
description: An I/O queue object notifies a driver when a write request is available for the driver.
old-location: wdf\iqueuecallbackwrite.htm
tech.root: wdf
ms.date: 02/26/2018
keywords: ["IQueueCallbackWrite interface"]
ms.keywords: IQueueCallbackWrite, IQueueCallbackWrite interface, IQueueCallbackWrite interface,described, UMDFQueueObjectRef_4abdce88-185f-4dab-823a-00da96d7d630.xml, umdf.iqueuecallbackwrite, wdf.iqueuecallbackwrite, wudfddi/IQueueCallbackWrite
req.header: wudfddi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
f1_keywords:
 - IQueueCallbackWrite
 - wudfddi/IQueueCallbackWrite
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - wudfddi.h
api_name:
 - IQueueCallbackWrite
---

# IQueueCallbackWrite interface


## -description

<p class="CCE_Message">[<b>Warning:</b> UMDF 2 is the latest version of UMDF and supersedes UMDF 1.  All new UMDF drivers should be written using UMDF 2.  No new features are being added to UMDF 1 and there is limited support for UMDF 1 on newer versions of Windows 10.  Universal Windows drivers must use UMDF 2.  For more info, see <a href="/windows-hardware/drivers/wdf/getting-started-with-umdf-version-2">Getting Started with UMDF</a>.]

An I/O queue object notifies a driver when a write request is available for the driver. The I/O queue object notifies the driver when an application calls the Microsoft Win32 <b>WriteFile</b> or <b>WriteFileEx</b> function. The driver can handle the notification by registering the <b>IQueueCallbackWrite</b> interface.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IQueueCallbackWrite</b> interface inherits from the <a href="/windows/win32/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IQueueCallbackWrite</b> also has these types of members:
<ul>
<li><a href="/">Methods</a></li>
</ul>

## -remarks

A driver registers the <b>IQueueCallbackWrite</b> interface when it calls the <a href="/windows-hardware/drivers/ddi/wudfddi/nf-wudfddi-iwdfdevice-createioqueue">IWDFDevice::CreateIoQueue</a> method to create an I/O queue or to configure the default I/O queue. For more information about creating or configuring I/O queues, see <a href="/windows-hardware/drivers/wdf/configuring-dispatch-mode-for-an-i-o-queue">Configuring Dispatch Mode for an I/O Queue</a>.
