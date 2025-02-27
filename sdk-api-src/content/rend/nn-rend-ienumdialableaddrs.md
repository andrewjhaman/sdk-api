---
UID: NN:rend.IEnumDialableAddrs
title: IEnumDialableAddrs (rend.h)
description: The IEnumDialableAddrs interface provides COM-standard enumeration methods to discover and use the available dialable addresses in a directory. The ITDirectoryObject::EnumerateDialableAddrs method returns a pointer to this interface.
helpviewer_keywords: ["IEnumDialableAddrs","IEnumDialableAddrs interface [TAPI 2.2]","IEnumDialableAddrs interface [TAPI 2.2]","described","_tapi3_ienumdialableaddrs","rend/IEnumDialableAddrs","tapi3.ienumdialableaddrs"]
old-location: tapi3\ienumdialableaddrs.htm
tech.root: tapi3
ms.assetid: 0a64cb89-9e44-4af1-9b0f-2eec6e5267c7
ms.date: 12/05/2018
ms.keywords: IEnumDialableAddrs, IEnumDialableAddrs interface [TAPI 2.2], IEnumDialableAddrs interface [TAPI 2.2],described, _tapi3_ienumdialableaddrs, rend/IEnumDialableAddrs, tapi3.ienumdialableaddrs
req.header: rend.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Rend.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: Rend.dll
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IEnumDialableAddrs
 - rend/IEnumDialableAddrs
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Rend.dll
api_name:
 - IEnumDialableAddrs
---

# IEnumDialableAddrs interface


## -description

<p class="CCE_Message">[Rendezvous IP Telephony Conferencing controls and interfaces are not available for use in Windows Vista, Windows Server 2008, and subsequent versions of the operating system. The RTC Client API
provides similar functionality.]

The 
<b>IEnumDialableAddrs</b> interface provides COM-standard enumeration methods to discover and use the available dialable addresses in a directory. The 
<a href="/windows/desktop/api/rend/nf-rend-itdirectoryobject-enumeratedialableaddrs">ITDirectoryObject::EnumerateDialableAddrs</a> method returns a pointer to this interface.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IEnumDialableAddrs</b> interface inherits from the <a href="/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IEnumDialableAddrs</b> also has these types of members:

