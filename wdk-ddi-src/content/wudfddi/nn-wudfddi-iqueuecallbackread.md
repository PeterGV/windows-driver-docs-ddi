---
UID: NN:wudfddi.IQueueCallbackRead
title: IQueueCallbackRead (wudfddi.h)
description: An I/O queue notifies a driver when a read request is available for the driver.
old-location: wdf\iqueuecallbackread.htm
tech.root: wdf
ms.date: 02/26/2018
keywords: ["IQueueCallbackRead interface"]
ms.keywords: IQueueCallbackRead, IQueueCallbackRead interface, IQueueCallbackRead interface,described, UMDFQueueObjectRef_ea1187c2-6bd1-43a0-aeeb-6d9e1ee48cd7.xml, umdf.iqueuecallbackread, wdf.iqueuecallbackread, wudfddi/IQueueCallbackRead
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
 - IQueueCallbackRead
 - wudfddi/IQueueCallbackRead
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - wudfddi.h
api_name:
 - IQueueCallbackRead
---

# IQueueCallbackRead interface


## -description

<p class="CCE_Message">[<b>Warning:</b> UMDF 2 is the latest version of UMDF and supersedes UMDF 1.  All new UMDF drivers should be written using UMDF 2.  No new features are being added to UMDF 1 and there is limited support for UMDF 1 on newer versions of Windows 10.  Universal Windows drivers must use UMDF 2.  For more info, see <a href="/windows-hardware/drivers/wdf/getting-started-with-umdf-version-2">Getting Started with UMDF</a>.]

An I/O queue notifies a driver when a read request is available for the driver. The I/O queue notifies the driver when an application calls the Microsoft Win32 <b>ReadFile</b> or <b>ReadFileEx</b> function. The driver can handle the notification by registering the <b>IQueueCallbackRead</b> interface.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IQueueCallbackRead</b> interface inherits from the <a href="/windows/win32/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IQueueCallbackRead</b> also has these types of members:
<ul>
<li><a href="/">Methods</a></li>
</ul>

## -remarks

A driver registers the <b>IQueueCallbackRead</b> interface when it calls the <a href="/windows-hardware/drivers/ddi/wudfddi/nf-wudfddi-iwdfdevice-createioqueue">IWDFDevice::CreateIoQueue</a> method to create an I/O queue or to configure the default I/O queue. For more information about creating or configuring an I/O queue, see <a href="/windows-hardware/drivers/wdf/configuring-dispatch-mode-for-an-i-o-queue">Configuring Dispatch Mode for an I/O Queue</a>.
