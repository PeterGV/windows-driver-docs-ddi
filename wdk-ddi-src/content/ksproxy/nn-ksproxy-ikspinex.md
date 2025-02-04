---
UID: NN:ksproxy.IKsPinEx
title: IKsPinEx (ksproxy.h)
description: The IKsPinEx interface inherits all the methods of the IKsPin interface and extends IKsPin to provide a method that notifies the filter graph of an error to give the filter graph an opportunity to halt.
old-location: stream\ikspinex.htm
tech.root: stream
ms.date: 04/23/2018
keywords: ["IKsPinEx interface"]
ms.keywords: IKsPinEx, IKsPinEx interface [Streaming Media Devices], IKsPinEx interface [Streaming Media Devices],described, ksproxy/IKsPinEx, ksproxy_3c92d570-f22f-4165-bafd-9a22f5516137.xml, stream.ikspinex
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
req.lib: Ksproxy.lib
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
f1_keywords:
 - IKsPinEx
 - ksproxy/IKsPinEx
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Ksproxy.lib
 - Ksproxy.dll
api_name:
 - IKsPinEx
---

# IKsPinEx interface


## -description

The <b>IKsPinEx</b> interface inherits all the methods of the <b>IKsPin</b> interface and extends <b>IKsPin</b> to provide a method that notifies the filter graph of an error to give the filter graph an opportunity to halt.

The IID for this interface is IID_IKsPinEx.

## -inheritance

The <b xmlns:loc="https://microsoft.com/wdcml/l10n">IKsPinEx</b> interface inherits from <a href="/windows-hardware/drivers/ddi/ksproxy/nn-ksproxy-ikspin">IKsPin</a>. <b>IKsPinEx</b> also has these types of members:
<ul>
<li><a href="/">Methods</a></li>
</ul>

## -remarks

An interface handler (<a href="/windows-hardware/drivers/ddi/ksproxy/nn-ksproxy-iksinterfacehandler">IKsInterfaceHandler</a>) uses many of the <b>IKsPinEx</b> methods to route media samples of a particular media type.

## -see-also

<a href="/windows-hardware/drivers/ddi/ksproxy/nn-ksproxy-iksinterfacehandler">IKsInterfaceHandler</a>



<a href="/windows-hardware/drivers/ddi/ksproxy/nn-ksproxy-ikspin">IKsPin</a>
