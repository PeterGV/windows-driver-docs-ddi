---
UID: NN:portcls.IPortClsEtwHelper
title: IPortClsEtwHelper (portcls.h)
description: The IPortClsEtwHelper interface allows an audio miniport driver to access the Event Tracing for Windows (ETW) helper functions.
old-location: audio\iportclsetwhelper.htm
tech.root: audio
ms.date: 05/08/2018
keywords: ["IPortClsEtwHelper interface"]
ms.keywords: IPortClsEtwHelper, IPortClsEtwHelper interface [Audio Devices], IPortClsEtwHelper interface [Audio Devices],described, audio.iportclsetwhelper, portcls/IPortClsEtwHelper
req.header: portcls.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 8
req.target-min-winversvr: Windows Server 2012
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
 - IPortClsEtwHelper
 - portcls/IPortClsEtwHelper
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Portcls.h
api_name:
 - IPortClsEtwHelper
---

# IPortClsEtwHelper interface


## -description

The <code>IPortClsEtwHelper</code> interface allows an audio miniport driver to access the Event Tracing for Windows (ETW) helper functions.

The miniport driver uses the information from the helper functions to report glitching errors.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IPortClsEtwHelper</b> interface inherits from the <a href="/windows/win32/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IPortClsEtwHelper</b> also has these types of members:
<ul>
<li><a href="/">Methods</a></li>
</ul>

## -see-also

<a href="/windows-hardware/drivers/audio/glitch-reporting-for-offloaded-audio">Glitch Reporting for Offloaded Audio</a>
