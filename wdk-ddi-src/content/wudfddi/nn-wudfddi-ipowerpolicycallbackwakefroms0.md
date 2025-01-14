---
UID: NN:wudfddi.IPowerPolicyCallbackWakeFromS0
title: IPowerPolicyCallbackWakeFromS0 (wudfddi.h)
description: A driver's IPowerPolicyCallbackWakeFromS0 interface provides callback functions that the framework calls to notify the driver about wake events.
old-location: wdf\ipowerpolicycallbackwakefroms0.htm
tech.root: wdf
ms.date: 02/26/2018
keywords: ["IPowerPolicyCallbackWakeFromS0 interface"]
ms.keywords: IPowerPolicyCallbackWakeFromS0, IPowerPolicyCallbackWakeFromS0 interface, IPowerPolicyCallbackWakeFromS0 interface,described, UMDFDeviceObjectRef_e79ecf1d-279d-4945-941a-ed53b00f6242.xml, umdf.ipowerpolicycallbackwakefroms0, wdf.ipowerpolicycallbackwakefroms0, wudfddi/IPowerPolicyCallbackWakeFromS0
req.header: wudfddi.h
req.include-header: Wudfddi.h
req.target-type: Desktop
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 1.9
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: Unavailable in UMDF 2.0 and later.
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
f1_keywords:
 - IPowerPolicyCallbackWakeFromS0
 - wudfddi/IPowerPolicyCallbackWakeFromS0
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Wudfddi.h
api_name:
 - IPowerPolicyCallbackWakeFromS0
---

# IPowerPolicyCallbackWakeFromS0 interface


## -description

<p class="CCE_Message">[<b>Warning:</b> UMDF 2 is the latest version of UMDF and supersedes UMDF 1.  All new UMDF drivers should be written using UMDF 2.  No new features are being added to UMDF 1 and there is limited support for UMDF 1 on newer versions of Windows 10.  Universal Windows drivers must use UMDF 2.  For more info, see <a href="/windows-hardware/drivers/wdf/getting-started-with-umdf-version-2">Getting Started with UMDF</a>.]

A driver's <b>IPowerPolicyCallbackWakeFromS0</b> interface provides callback functions that the framework calls to notify the driver about wake events. These events are related to a device's ability to wake from a low-power state while the system remains in the <a href="/windows-hardware/drivers/kernel/system-working-state-s0">system working state</a> (S0).

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IPowerPolicyCallbackWakeFromS0</b> interface inherits from the <a href="/windows/win32/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IPowerPolicyCallbackWakeFromS0</b> also has these types of members:
<ul>
<li><a href="/">Methods</a></li>
</ul>

## -remarks

If your driver supports an <b>IPowerPolicyCallbackWakeFromS0</b> interface for a device, the <b>IUnknown::QueryInterface</b> method that the driver passes to <a href="/windows-hardware/drivers/ddi/wudfddi/nf-wudfddi-iwdfdriver-createdevice">IWDFDriver::CreateDevice</a> must return the interface.
