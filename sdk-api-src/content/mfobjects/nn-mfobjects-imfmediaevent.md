---
UID: NN:mfobjects.IMFMediaEvent
title: IMFMediaEvent (mfobjects.h)
description: Represents an event generated by a Media Foundation object. Use this interface to get information about the event.
helpviewer_keywords: ["IMFMediaEvent","IMFMediaEvent interface [Media Foundation]","IMFMediaEvent interface [Media Foundation]","described","b4f686be-9472-433c-b983-6c48dfd3ac76","mf.imfmediaevent","mfobjects/IMFMediaEvent"]
old-location: mf\imfmediaevent.htm
tech.root: mf
ms.assetid: b4f686be-9472-433c-b983-6c48dfd3ac76
ms.date: 12/05/2018
ms.keywords: IMFMediaEvent, IMFMediaEvent interface [Media Foundation], IMFMediaEvent interface [Media Foundation],described, b4f686be-9472-433c-b983-6c48dfd3ac76, mf.imfmediaevent, mfobjects/IMFMediaEvent
req.header: mfobjects.h
req.include-header: Mfidl.h
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2008 [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Mfuuid.lib
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IMFMediaEvent
 - mfobjects/IMFMediaEvent
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - mfuuid.lib
 - mfuuid.dll
api_name:
 - IMFMediaEvent
---

# IMFMediaEvent interface


## -description

Represents an event generated by a Media Foundation object. Use this interface to get information about the event.

To get a pointer to this interface, call <a href="/windows/desktop/api/mfobjects/nf-mfobjects-imfmediaeventgenerator-begingetevent">IMFMediaEventGenerator::BeginGetEvent</a> or <a href="/windows/desktop/api/mfobjects/nf-mfobjects-imfmediaeventgenerator-getevent">IMFMediaEventGenerator::GetEvent</a> on the event generator.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IMFMediaEvent</b> interface inherits from <a href="/windows/desktop/api/mfobjects/nn-mfobjects-imfattributes">IMFAttributes</a>. <b>IMFMediaEvent</b> also has these types of members:

## -remarks

If you are implementing an object that generates events, call the <a href="/windows/desktop/api/mfapi/nf-mfapi-mfcreatemediaevent">MFCreateMediaEvent</a> function to create a new event object.

This interface is available on the following platforms if the Windows Media Format 11 SDK redistributable components are installed:

<ul>
<li>Windows XP with Service Pack 2 (SP2) and later.</li>
<li>Windows XP Media Center Edition 2005 with KB900325 (Windows XP Media Center Edition 2005) and KB925766 (October 2006 Update Rollup for Windows XP Media Center Edition) installed.</li>
</ul>

## -see-also

<a href="/windows/desktop/medfound/event-attributes">Event Attributes</a>



<a href="/windows/desktop/api/mfobjects/nn-mfobjects-imfattributes">IMFAttributes</a>



<a href="/windows/desktop/medfound/media-event-generators">Media Event Generators</a>



<a href="/windows/desktop/medfound/media-foundation-interfaces">Media Foundation Interfaces</a>
