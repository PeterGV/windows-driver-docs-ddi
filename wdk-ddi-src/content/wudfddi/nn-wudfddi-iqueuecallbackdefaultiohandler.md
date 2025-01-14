---
UID: NN:wudfddi.IQueueCallbackDefaultIoHandler
title: IQueueCallbackDefaultIoHandler (wudfddi.h)
description: The IQueueCallbackDefaultIoHandler interface contains a method that handles I/O requests that no other method is registered to handle.
old-location: wdf\iqueuecallbackdefaultiohandler.htm
tech.root: wdf
ms.date: 02/26/2018
keywords: ["IQueueCallbackDefaultIoHandler interface"]
ms.keywords: IQueueCallbackDefaultIoHandler, IQueueCallbackDefaultIoHandler interface, IQueueCallbackDefaultIoHandler interface,described, UMDFQueueObjectRef_31f05689-d38c-444b-b930-9c6c5136c60d.xml, umdf.iqueuecallbackdefaultiohandler, wdf.iqueuecallbackdefaultiohandler, wudfddi/IQueueCallbackDefaultIoHandler
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
 - IQueueCallbackDefaultIoHandler
 - wudfddi/IQueueCallbackDefaultIoHandler
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - wudfddi.h
api_name:
 - IQueueCallbackDefaultIoHandler
---

# IQueueCallbackDefaultIoHandler interface


## -description

<p class="CCE_Message">[<b>Warning:</b> UMDF 2 is the latest version of UMDF and supersedes UMDF 1.  All new UMDF drivers should be written using UMDF 2.  No new features are being added to UMDF 1 and there is limited support for UMDF 1 on newer versions of Windows 10.  Universal Windows drivers must use UMDF 2.  For more info, see <a href="/windows-hardware/drivers/wdf/getting-started-with-umdf-version-2">Getting Started with UMDF</a>.]

The <b>IQueueCallbackDefaultIoHandler</b> interface contains a method that handles I/O requests that no other method is registered to handle.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IQueueCallbackDefaultIoHandler</b> interface inherits from the <a href="/windows/win32/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IQueueCallbackDefaultIoHandler</b> also has these types of members:
<ul>
<li><a href="/">Methods</a></li>
</ul>

## -remarks

A driver registers the <b>IQueueCallbackDefaultIoHandler</b> interface when the driver calls the <a href="/windows-hardware/drivers/ddi/wudfddi/nf-wudfddi-iwdfdevice-createioqueue">IWDFDevice::CreateIoQueue</a> method to create an I/O queue or to configure the default I/O queue.
