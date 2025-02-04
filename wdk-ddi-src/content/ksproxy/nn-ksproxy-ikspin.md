---
UID: NN:ksproxy.IKsPin
title: IKsPin (ksproxy.h)
description: The IKsPin interface provides methods that control and retrieve information about a pin.
old-location: stream\ikspin.htm
tech.root: stream
ms.date: 04/23/2018
keywords: ["IKsPin interface"]
ms.keywords: IKsPin, IKsPin interface [Streaming Media Devices], IKsPin interface [Streaming Media Devices],described, ksproxy/IKsPin, ksproxy_9a020f8a-1271-47ea-816f-1132e44b6f45.xml, stream.ikspin
req.header: ksproxy.h
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
 - IKsPin
 - ksproxy/IKsPin
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - ksproxy.h
api_name:
 - IKsPin
---

# IKsPin interface


## -description

The <b>IKsPin</b> interface provides methods that control and retrieve information about a pin.

The IID for this interface is IID_IKsPin.

## -inheritance

The <b xmlns:loc="https://microsoft.com/wdcml/l10n">IKsPin</b> interface inherits from the <a href="/windows/win32/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IKsPin</b> also has these types of members:
<ul>
<li><a href="/">Methods</a></li>
</ul>

## -remarks

An interface handler (<a href="/windows-hardware/drivers/ddi/ksproxy/nn-ksproxy-iksinterfacehandler">IKsInterfaceHandler</a>) uses many of the <b>IKsPin</b> methods to route media samples of a particular media type.

## -see-also

<a href="/windows-hardware/drivers/ddi/ksproxy/nn-ksproxy-iksinterfacehandler">IKsInterfaceHandler</a>

