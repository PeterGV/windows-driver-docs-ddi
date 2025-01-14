---
UID: NN:wudfusb.IWDFUsbTargetPipe
title: IWDFUsbTargetPipe (wudfusb.h)
description: The IWDFUsbTargetPipe interface exposes a USB pipe (endpoint), which is also an I/O target.
old-location: wdf\iwdfusbtargetpipe.htm
tech.root: wdf
ms.date: 02/26/2018
keywords: ["IWDFUsbTargetPipe interface"]
ms.keywords: IWDFUsbTargetPipe, IWDFUsbTargetPipe interface, IWDFUsbTargetPipe interface,described, UMDFUSBref_985f9453-7475-4e9b-894c-5d4e7b8d3971.xml, umdf.iwdfusbtargetpipe, wdf.iwdfusbtargetpipe, wudfusb/IWDFUsbTargetPipe
req.header: wudfusb.h
req.include-header: 
req.target-type: Desktop
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 1.5
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: Unavailable in UMDF 2.0 and later.
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: WUDFx.dll
req.irql: 
targetos: Windows
req.typenames: 
f1_keywords:
 - IWDFUsbTargetPipe
 - wudfusb/IWDFUsbTargetPipe
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - WUDFx.dll
api_name:
 - IWDFUsbTargetPipe
---

# IWDFUsbTargetPipe interface


## -description

<p class="CCE_Message">[<b>Warning:</b> UMDF 2 is the latest version of UMDF and supersedes UMDF 1.  All new UMDF drivers should be written using UMDF 2.  No new features are being added to UMDF 1 and there is limited support for UMDF 1 on newer versions of Windows 10.  Universal Windows drivers must use UMDF 2.  For more info, see <a href="/windows-hardware/drivers/wdf/getting-started-with-umdf-version-2">Getting Started with UMDF</a>.]


The <b>IWDFUsbTargetPipe</b> interface exposes a USB pipe (endpoint), which is also an I/O target.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IWDFUsbTargetPipe</b> interface inherits from <a href="/windows-hardware/drivers/ddi/wudfddi/nn-wudfddi-iwdfiotarget">IWDFIoTarget</a>. <b>IWDFUsbTargetPipe</b> also has these types of members:
<ul>
<li><a href="/">Methods</a></li>
</ul>
