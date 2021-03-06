---
title: CreateInstanceFromTextRepresentation method of the MicrosoftDNS_ResourceRecord class
description: The CreateInstanceFromTextRepresentation method instantiates a MicrosoftDNS\_ResourceRecord object.
ms.assetid: 19600a9a-f75d-40ad-98e5-f81465d10f79
keywords:
- CreateInstanceFromTextRepresentation method DNS
- CreateInstanceFromTextRepresentation method DNS , MicrosoftDNS_ResourceRecord class
- MicrosoftDNS_ResourceRecord class DNS , CreateInstanceFromTextRepresentation method
topic_type:
- apiref
api_name:
- MicrosoftDNS_ResourceRecord.CreateInstanceFromTextRepresentation
api_location:
- Root\MicrosoftDNS
api_type:
- COM
ms.topic: reference
ms.date: 05/31/2018
---

# CreateInstanceFromTextRepresentation method of the MicrosoftDNS\_ResourceRecord class

The **CreateInstanceFromTextRepresentation** method instantiates a [**MicrosoftDNS\_ResourceRecord**](microsoftdns-resourcerecord.md) object.

## Syntax


```mof
void CreateInstanceFromTextRepresentation(
  [in]       string                      DnsServerName,
  [in]       string                      ContainerName,
  [in]       string                      TextRepresentation,
  [out, ref] MicrosoftDNS_ResourceRecord &RR
);
```



## Parameters

<dl> <dt>

*DnsServerName* \[in\]
</dt> <dd>

Name of the DNS Server on which the RR should be created.

</dd> <dt>

*ContainerName* \[in\]
</dt> <dd>

Name of the container into which the new RR should be placed.

</dd> <dt>

*TextRepresentation* \[in\]
</dt> <dd>

Text representation of the RR instance to be created.

</dd> <dt>

*RR* \[out, ref\]
</dt> <dd>

Reference to the instantiated RR.

</dd> </dl>

## Return value

This method does not return a value.

## Requirements



| Requirement | Value |
|-------------------------------------|----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | None supported<br/>                                                              |
| Minimum supported server<br/> | Windows 2000 Server \[desktop apps only\]<br/>                                   |
| Namespace<br/>                | Root\\MicrosoftDNS<br/>                                                          |
| MOF<br/>                      | <dl> <dt>Dnsprov.mof</dt> </dl> |



## See also

<dl> <dt>

[**MicrosoftDNS\_ResourceRecord**](microsoftdns-resourcerecord.md)
</dt> <dt>

[**GetObjectByTextRepresentation Method of the MicrosoftDNS\_ResourceRecord Class**](microsoftdns-resourcerecord-getobjectbytextrepresentation.md)
</dt> </dl>

 

 





