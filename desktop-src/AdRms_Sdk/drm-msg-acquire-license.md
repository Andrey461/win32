---
Description: Sent to the custom callback function in response to the DRMAcquireLicense function being called with a license storage session handle.
audience: developer
author: REDMOND\\markl
manager: REDMOND\\mbaldwin
ms.assetid: df1635f1-3be3-4043-9ad9-afb29e24986a
ms.prod: windows-server-dev
ms.technology: active-directory-rights-management
ms.tgt_platform: multiple
title: DRM\_MSG\_ACQUIRE\_LICENSE message
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# DRM\_MSG\_ACQUIRE\_LICENSE message

\[The AD RMS SDK leveraging functionality exposed by the client in Msdrm.dll is available for use in Windows Server 2008, Windows Vista, Windows Server 2008 R2, Windows 7, Windows Server 2012, and Windows 8. It may be altered or unavailable in subsequent versions. Instead, use [Active Directory Rights Management Services SDK 2.1](https://msdn.microsoft.com/library/hh535290), which leverages functionality exposed by the client in Msipc.dll.\]

The **DRM\_MSG\_ACQUIRE\_LICENSE** message is sent to the custom callback function in response to the [**DRMAcquireLicense**](/previous-versions/windows/desktop/api/Msdrm/nf-msdrm-drmacquirelicense) function being called with a license storage session handle.

## Parameters

<dl> <dt>

*hr* 
</dt> <dd>

The result of the action being monitored. The contents of the *pvParam* parameter is dependent on the value of this parameter. This can be one of the following values.

<dt>

<span id="S_DRM_CONNECTING"></span><span id="s_drm_connecting"></span>

<span id="S_DRM_CONNECTING"></span><span id="s_drm_connecting"></span>****S\_DRM\_CONNECTING**** (**NULL**)


</dt> <dd>

A connection has not yet occurred.

</dd> <dt>

<span id="S_DRM_CONNECTED"></span><span id="s_drm_connected"></span>

<span id="S_DRM_CONNECTED"></span><span id="s_drm_connected"></span>****S\_DRM\_CONNECTED**** (**NULL**)


</dt> <dd>

The system has connected to a server.

</dd> <dt>

<span id="S_DRM_COMPLETED"></span><span id="s_drm_completed"></span>

<span id="S_DRM_COMPLETED"></span><span id="s_drm_completed"></span>****S\_DRM\_COMPLETED**** (**NULL**)


</dt> <dd>

The operation is complete.

</dd> <dt>

<span id="S_DRM_INPROGRESS"></span><span id="s_drm_inprogress"></span>

<span id="S_DRM_INPROGRESS"></span><span id="s_drm_inprogress"></span>****S\_DRM\_INPROGRESS**** (A pointer to a **DWORD** value that contains an integer that represents the progress of the current request, from zero to 100.)


</dt> <dd></dd> <dt>

<span id="S_DRM_REQUEST_PREPARED"></span><span id="s_drm_request_prepared"></span>

<span id="S_DRM_REQUEST_PREPARED"></span><span id="s_drm_request_prepared"></span>****S\_DRM\_REQUEST\_PREPARED**** (A pointer to a [**DRM\_LICENSE\_ACQ\_DATA**](/previous-versions/windows/desktop/api/Msdrmdefs/ns-msdrmdefs-_drm_license_acq_data) structure that lists license acquisition information for a nonsilent license request.)


</dt> <dd>

This is only returned when [**DRMAcquireLicense**](/previous-versions/windows/desktop/api/Msdrm/nf-msdrm-drmacquirelicense) was called by using the **DRM\_AL\_NONSILENT** flag. Nonsilent license acquisition is supported only in Rights Management Services client 1.0.

</dd> </dl> </dd> <dt>

*pvParam* 
</dt> <dd>

The contents of this parameter is dependent on the value in the *hr* parameter. For more information, see the *hr* parameter description.

</dd> <dt>

*pvContext* 
</dt> <dd>

An application-defined value, such as a pointer to a callback function, a pointer to an event handle, or other value.

</dd> </dl>

## Return value

If the callback function succeeds, the function returns **S\_OK**.

If the callback function fails, it returns an **HRESULT** error code.

## Remarks

The [**DRMAcquireLicense**](/previous-versions/windows/desktop/api/Msdrm/nf-msdrm-drmacquirelicense) function is an asynchronous function that will return before this message is sent to the callback function. It is the application's responsibility to ensure that this synchronization is properly handled.

## Requirements



|                    |                                                                                        |
|--------------------|----------------------------------------------------------------------------------------|
| Product<br/> | Rights Management Services client 1.0 SP2 or later<br/>                          |
| Header<br/>  | <dl> <dt>Msdrmdefs.h</dt> </dl> |



## See also

<dl> <dt>

[Creating a Callback Function](creating-a-callback-function.md)
</dt> <dt>

[**DRM\_STATUS\_MSG**](/previous-versions/windows/desktop/api/Msdrmdefs/ne-msdrmdefs-_drm_status_msg)
</dt> <dt>

[**DRMAcquireLicense**](/previous-versions/windows/desktop/api/Msdrm/nf-msdrm-drmacquirelicense)
</dt> </dl>

 

 



