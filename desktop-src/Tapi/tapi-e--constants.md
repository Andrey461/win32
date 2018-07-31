---
Description: TAPI methods and functions may return a TAPI\_E\_ constant. These constants indicate the outcome of an API call.
ms.assetid: d242e0e8-99ae-4f5b-9f2d-e7e25953f7c8
title: TAPI\_E\_ Constants
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# TAPI\_E\_ Constants

TAPI methods and functions may return a TAPI\_E\_ constant. These constants indicate the outcome of an API call.



| Constant/value                                                                                                                                                                                                                                                                                                   | Description                                                                                                                                                                                                            |
|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="TAPI_E_NOTENOUGHMEMORY"></span><span id="tapi_e_notenoughmemory"></span><dl> <dt>**TAPI\_E\_NOTENOUGHMEMORY**</dt> <dt>((HRESULT)0x80040001L)</dt> </dl>                                            | The buffer passed in to this method was not big enough. <br/>                                                                                                                                                    |
| <span id="TAPI_E_NOITEMS"></span><span id="tapi_e_noitems"></span><dl> <dt>**TAPI\_E\_NOITEMS**</dt> <dt>((HRESULT)0x80040002L)</dt> </dl>                                                                    | No items exist that match the request. <br/>                                                                                                                                                                     |
| <span id="TAPI_E_INVALIDMEDIATYPE"></span><span id="tapi_e_invalidmediatype"></span><dl> <dt>**TAPI\_E\_INVALIDMEDIATYPE**</dt> <dt>((HRESULT)0x80040004L)</dt> </dl>                                         | An invalid [**media type**](tapimediatype--constants.md) was passed in. <br/>                                                                                                                                   |
| <span id="TAPI_E_OPERATIONFAILED"></span><span id="tapi_e_operationfailed"></span><dl> <dt>**TAPI\_E\_OPERATIONFAILED**</dt> <dt>((HRESULT)0x80040005L)</dt> </dl>                                            | The operation failed for an unspecified reason. <br/>                                                                                                                                                            |
| <span id="TAPI_E_ALLOCATED"></span><span id="tapi_e_allocated"></span><dl> <dt>**TAPI\_E\_ALLOCATED**</dt> <dt>((HRESULT)0x80040006L)</dt> </dl>                                                              | The device is already in use. <br/>                                                                                                                                                                              |
| <span id="TAPI_E_CALLUNAVAIL"></span><span id="tapi_e_callunavail"></span><dl> <dt>**TAPI\_E\_CALLUNAVAIL**</dt> <dt>((HRESULT)0x80040007L)</dt> </dl>                                                        | No call appearance is available. <br/>                                                                                                                                                                           |
| <span id="TAPI_E_COMPLETIONOVERRUN"></span><span id="tapi_e_completionoverrun"></span><dl> <dt>**TAPI\_E\_COMPLETIONOVERRUN**</dt> <dt>((HRESULT)0x80040008L)</dt> </dl>                                      | Too many call completions are outstanding. <br/>                                                                                                                                                                 |
| <span id="TAPI_E_CONFERENCEFULL"></span><span id="tapi_e_conferencefull"></span><dl> <dt>**TAPI\_E\_CONFERENCEFULL**</dt> <dt>((HRESULT)0x80040009L)</dt> </dl>                                               | The conference is full and more members cannot be added. <br/>                                                                                                                                                   |
| <span id="TAPI_E_DIALMODIFIERNOTSUPPORTED"></span><span id="tapi_e_dialmodifiernotsupported"></span><dl> <dt>**TAPI\_E\_DIALMODIFIERNOTSUPPORTED**</dt> <dt>((HRESULT)0x8004000AL)</dt> </dl>                 | The dial modifier is not supported. <br/>                                                                                                                                                                        |
| <span id="TAPI_E_INUSE"></span><span id="tapi_e_inuse"></span><dl> <dt>**TAPI\_E\_INUSE**</dt> <dt>((HRESULT)0x8004000BL)</dt> </dl>                                                                          | The device is already in use. <br/>                                                                                                                                                                              |
| <span id="TAPI_E_INVALADDRESS"></span><span id="tapi_e_invaladdress"></span><dl> <dt>**TAPI\_E\_INVALADDRESS**</dt> <dt>((HRESULT)0x8004000CL)</dt> </dl>                                                     | The address is invalid or not properly formatted. For example, if address type is LINEADDRESSTYPE\_PHONENUMBER, this error code would mean that the data entered did not appear to be a real phone number. <br/> |
| <span id="TAPI_E_INVALADDRESSSTATE"></span><span id="tapi_e_invaladdressstate"></span><dl> <dt>**TAPI\_E\_INVALADDRESSSTATE**</dt> <dt>((HRESULT)0x8004000DL)</dt> </dl>                                      | The operation is not permitted in the current [**address state**](https://msdn.microsoft.com/en-us/library/ms734936(v=VS.85).aspx). <br/>                                                                                               |
| <span id="TAPI_E_INVALCALLPARAMS"></span><span id="tapi_e_invalcallparams"></span><dl> <dt>**TAPI\_E\_INVALCALLPARAMS**</dt> <dt>((HRESULT)0x8004000EL)</dt> </dl>                                            | The [**LINECALLPARAMS**](https://msdn.microsoft.com/en-us/library/ms735534(v=VS.85).aspx) structure is invalid. <br/>                                                                                                                            |
| <span id="TAPI_E_INVALCALLPRIVILEGE"></span><span id="tapi_e_invalcallprivilege"></span><dl> <dt>**TAPI\_E\_INVALCALLPRIVILEGE**</dt> <dt>((HRESULT)0x8004000FL)</dt> </dl>                                   | The [**call privilege**](https://msdn.microsoft.com/en-us/library/ms735538(v=VS.85).aspx) is invalid. <br/>                                                                                                                            |
| <span id="TAPI_E_INVALCALLSTATE"></span><span id="tapi_e_invalcallstate"></span><dl> <dt>**TAPI\_E\_INVALCALLSTATE**</dt> <dt>((HRESULT)0x80040010L)</dt> </dl>                                               | The operation is not permitted in the current [**call state**](/windows/desktop/api/Tapi3if/ne-tapi3if-call_state). <br/>                                                                                                                            |
| <span id="TAPI_E_INVALCARD"></span><span id="tapi_e_invalcard"></span><dl> <dt>**TAPI\_E\_INVALCARD**</dt> <dt>((HRESULT)0x80040011L)</dt> </dl>                                                              | The calling card is invalid. <br/>                                                                                                                                                                               |
| <span id="TAPI_E_INVALCOMPLETIONID"></span><span id="tapi_e_invalcompletionid"></span><dl> <dt>**TAPI\_E\_INVALCOMPLETIONID**</dt> <dt>((HRESULT)0x80040012L)</dt> </dl>                                      | The call completion ID is invalid. <br/>                                                                                                                                                                         |
| <span id="TAPI_E_INVALCOUNTRYCODE"></span><span id="tapi_e_invalcountrycode"></span><dl> <dt>**TAPI\_E\_INVALCOUNTRYCODE**</dt> <dt>((HRESULT)0x80040013L)</dt> </dl>                                         | The country or region code is invalid. <br/>                                                                                                                                                                     |
| <span id="TAPI_E_INVALDEVICECLASS"></span><span id="tapi_e_invaldeviceclass"></span><dl> <dt>**TAPI\_E\_INVALDEVICECLASS**</dt> <dt>((HRESULT)0x80040014L)</dt> </dl>                                         | The device class identifier is invalid. <br/>                                                                                                                                                                    |
| <span id="TAPI_E_INVALDIALPARAMS"></span><span id="tapi_e_invaldialparams"></span><dl> <dt>**TAPI\_E\_INVALDIALPARAMS**</dt> <dt>((HRESULT)0x80040015L)</dt> </dl>                                            | The dialing parameters are invalid. <br/>                                                                                                                                                                        |
| <span id="TAPI_E_INVALDIGITS"></span><span id="tapi_e_invaldigits"></span><dl> <dt>**TAPI\_E\_INVALDIGITS**</dt> <dt>((HRESULT)0x80040016L)</dt> </dl>                                                        | The digits are invalid. <br/>                                                                                                                                                                                    |
| <span id="TAPI_E_INVALGROUPID"></span><span id="tapi_e_invalgroupid"></span><dl> <dt>**TAPI\_E\_INVALGROUPID**</dt> <dt>((HRESULT)0x80040017L)</dt> </dl>                                                     | The group pickup ID is invalid. <br/>                                                                                                                                                                            |
| <span id="TAPI_E_INVALLOCATION"></span><span id="tapi_e_invallocation"></span><dl> <dt>**TAPI\_E\_INVALLOCATION**</dt> <dt>((HRESULT)0x80040018L)</dt> </dl>                                                  | The location ID is invalid. <br/>                                                                                                                                                                                |
| <span id="TAPI_E_INVALMESSAGEID"></span><span id="tapi_e_invalmessageid"></span><dl> <dt>**TAPI\_E\_INVALMESSAGEID**</dt> <dt>(HRESULT)0x80040019L)</dt> </dl>                                                | The message ID is invalid. (<br/>                                                                                                                                                                                |
| <span id="TAPI_E_INVALPARKID"></span><span id="tapi_e_invalparkid"></span><dl> <dt>**TAPI\_E\_INVALPARKID**</dt> <dt>((HRESULT)0x8004001AL)</dt> </dl>                                                        | The park ID is invalid. <br/>                                                                                                                                                                                    |
| <span id="TAPI_E_INVALRATE"></span><span id="tapi_e_invalrate"></span><dl> <dt>**TAPI\_E\_INVALRATE**</dt> <dt>((HRESULT)0x8004001BL)</dt> </dl>                                                              | The rate is invalid. <br/>                                                                                                                                                                                       |
| <span id="TAPI_E_INVALTIMEOUT"></span><span id="tapi_e_invaltimeout"></span><dl> <dt>**TAPI\_E\_INVALTIMEOUT**</dt> <dt>((HRESULT)0x8004001CL)</dt> </dl>                                                     | The timeout value is invalid. <br/>                                                                                                                                                                              |
| <span id="TAPI_E_INVALTONE"></span><span id="tapi_e_invaltone"></span><dl> <dt>**TAPI\_E\_INVALTONE**</dt> <dt>((HRESULT)0x8004001DL)</dt> </dl>                                                              | The tone is invalid. <br/>                                                                                                                                                                                       |
| <span id="TAPI_E_INVALLIST"></span><span id="tapi_e_invallist"></span><dl> <dt>**TAPI\_E\_INVALLIST**</dt> <dt>((HRESULT)0x8004001EL)</dt> </dl>                                                              | An invalid list was passed as a parameter. <br/>                                                                                                                                                                 |
| <span id="TAPI_E_INVALMODE"></span><span id="tapi_e_invalmode"></span><dl> <dt>**TAPI\_E\_INVALMODE**</dt> <dt>((HRESULT)0x8004001FL)</dt> </dl>                                                              | An invalid mode was passed as a parameter. <br/>                                                                                                                                                                 |
| <span id="TAPI_E_NOCONFERENCE"></span><span id="tapi_e_noconference"></span><dl> <dt>**TAPI\_E\_NOCONFERENCE**</dt> <dt>((HRESULT)0x80040020L)</dt> </dl>                                                     | The call is not part of a conference. <br/>                                                                                                                                                                      |
| <span id="TAPI_E_NODEVICE"></span><span id="tapi_e_nodevice"></span><dl> <dt>**TAPI\_E\_NODEVICE**</dt> <dt>((HRESULT)0x80040021L)</dt> </dl>                                                                 | The device was removed, or the device class is not recognized. <br/>                                                                                                                                             |
| <span id="TAPI_E_NOREQUEST"></span><span id="tapi_e_norequest"></span><dl> <dt>**TAPI\_E\_NOREQUEST**</dt> <dt>((HRESULT)0x80040022L)</dt> </dl>                                                              | No Assisted Telephony requests are pending. <br/>                                                                                                                                                                |
| <span id="TAPI_E_NOTOWNER"></span><span id="tapi_e_notowner"></span><dl> <dt>**TAPI\_E\_NOTOWNER**</dt> <dt>((HRESULT)0x80040023L)</dt> </dl>                                                                 | The application does not have OWNER [**privilege**](/windows/desktop/api/Tapi3if/ne-tapi3if-call_privilege) on the call. <br/>                                                                                                                       |
| <span id="TAPI_E_NOTREGISTERED"></span><span id="tapi_e_notregistered"></span><dl> <dt>**TAPI\_E\_NOTREGISTERED**</dt> <dt>((HRESULT)0x80040024L)</dt> </dl>                                                  | The application is not registered to handle requests. <br/>                                                                                                                                                      |
| <span id="TAPI_E_REQUESTOVERRUN"></span><span id="tapi_e_requestoverrun"></span><dl> <dt>**TAPI\_E\_REQUESTOVERRUN**</dt> <dt>((HRESULT)0x80040025L)</dt> </dl>                                               | The request queue is already full. <br/>                                                                                                                                                                         |
| <span id="TAPI_E_TARGETNOTFOUND"></span><span id="tapi_e_targetnotfound"></span><dl> <dt>**TAPI\_E\_TARGETNOTFOUND**</dt> <dt>((HRESULT)0x80040026L)</dt> </dl>                                               | The call handoff failed because the specified target was not found. <br/>                                                                                                                                        |
| <span id="TAPI_E_TARGETSELF"></span><span id="tapi_e_targetself"></span><dl> <dt>**TAPI\_E\_TARGETSELF**</dt> <dt>((HRESULT)0x80040027L)</dt> </dl>                                                           | No higher priority target exists for the call handoff. <br/>                                                                                                                                                     |
| <span id="TAPI_E_USERUSERINFOTOOBIG"></span><span id="tapi_e_useruserinfotoobig"></span><dl> <dt>**TAPI\_E\_USERUSERINFOTOOBIG**</dt> <dt>((HRESULT)0x80040028L)</dt> </dl>                                   | The amount of user-user information exceeds the maximum permitted. <br/>                                                                                                                                         |
| <span id="TAPI_E_REINIT"></span><span id="tapi_e_reinit"></span><dl> <dt>**TAPI\_E\_REINIT**</dt> <dt>((HRESULT)0x80040029L)</dt> </dl>                                                                       | The operation cannot be completed until all TAPI applications shut down and reinitialize. <br/>                                                                                                                  |
| <span id="TAPI_E_ADDRESSBLOCKED"></span><span id="tapi_e_addressblocked"></span><dl> <dt>**TAPI\_E\_ADDRESSBLOCKED**</dt> <dt>((HRESULT)0x8004002AL)</dt> </dl>                                               | You are not permitted to call this number. <br/>                                                                                                                                                                 |
| <span id="TAPI_E_BILLINGREJECTED"></span><span id="tapi_e_billingrejected"></span><dl> <dt>**TAPI\_E\_BILLINGREJECTED**</dt> <dt>((HRESULT)0x8004002BL)</dt> </dl>                                            | The calling card number or other billing information was rejected. <br/>                                                                                                                                         |
| <span id="TAPI_E_INVALFEATURE"></span><span id="tapi_e_invalfeature"></span><dl> <dt>**TAPI\_E\_INVALFEATURE**</dt> <dt>((HRESULT)0x8004002CL)</dt> </dl>                                                     | The device-specific feature is invalid. <br/>                                                                                                                                                                    |
| <span id="TAPI_E_INVALBUTTONLAMPID"></span><span id="tapi_e_invalbuttonlampid"></span><dl> <dt>**TAPI\_E\_INVALBUTTONLAMPID**</dt> <dt>((HRESULT)0x8004002DL)</dt> </dl>                                      | The button or lamp ID is invalid. <br/>                                                                                                                                                                          |
| <span id="TAPI_E_INVALBUTTONSTATE"></span><span id="tapi_e_invalbuttonstate"></span><dl> <dt>**TAPI\_E\_INVALBUTTONSTATE**</dt> <dt>((HRESULT)0x8004002EL)</dt> </dl>                                         | The button state is invalid. <br/>                                                                                                                                                                               |
| <span id="TAPI_E_INVALDATAID"></span><span id="tapi_e_invaldataid"></span><dl> <dt>**TAPI\_E\_INVALDATAID**</dt> <dt>((HRESULT)0x8004002FL)</dt> </dl>                                                        | The data segment ID is invalid. <br/>                                                                                                                                                                            |
| <span id="TAPI_E_INVALHOOKSWITCHDEV"></span><span id="tapi_e_invalhookswitchdev"></span><dl> <dt>**TAPI\_E\_INVALHOOKSWITCHDEV**</dt> <dt>((HRESULT)0x80040030L)</dt> </dl>                                   | The hookswitch device ID is invalid. <br/>                                                                                                                                                                       |
| <span id="TAPI_E_DROPPED"></span><span id="tapi_e_dropped"></span><dl> <dt>**TAPI\_E\_DROPPED**</dt> <dt>((HRESULT)0x80040031L)</dt> </dl>                                                                    | The call was disconnected. <br/>                                                                                                                                                                                 |
| <span id="TAPI_E_NOREQUESTRECIPIENT"></span><span id="tapi_e_norequestrecipient"></span><dl> <dt>**TAPI\_E\_NOREQUESTRECIPIENT**</dt> <dt>((HRESULT)0x80040032L)</dt> </dl>                                   | No program is available to handle the request. <br/>                                                                                                                                                             |
| <span id="TAPI_E_REQUESTQUEUEFULL"></span><span id="tapi_e_requestqueuefull"></span><dl> <dt>**TAPI\_E\_REQUESTQUEUEFULL**</dt> <dt>((HRESULT)0x80040033L)</dt> </dl>                                         | The queue of call requests is full. <br/>                                                                                                                                                                        |
| <span id="TAPI_E_DESTBUSY"></span><span id="tapi_e_destbusy"></span><dl> <dt>**TAPI\_E\_DESTBUSY**</dt> <dt>((HRESULT)0x80040034L)</dt> </dl>                                                                 | The called number is busy. <br/>                                                                                                                                                                                 |
| <span id="TAPI_E_DESTNOANSWER"></span><span id="tapi_e_destnoanswer"></span><dl> <dt>**TAPI\_E\_DESTNOANSWER**</dt> <dt>((HRESULT)0x80040035L)</dt> </dl>                                                     | The called party does not answer. <br/>                                                                                                                                                                          |
| <span id="TAPI_E_DESTUNAVAIL"></span><span id="tapi_e_destunavail"></span><dl> <dt>**TAPI\_E\_DESTUNAVAIL**</dt> <dt>((HRESULT)0x80040036L)</dt> </dl>                                                        | The called number could not be reached. <br/>                                                                                                                                                                    |
| <span id="TAPI_E_REQUESTFAILED"></span><span id="tapi_e_requestfailed"></span><dl> <dt>**TAPI\_E\_REQUESTFAILED**</dt> <dt>((HRESULT)0x80040037L)</dt> </dl>                                                  | The request failed for unspecified reasons. <br/>                                                                                                                                                                |
| <span id="TAPI_E_REQUESTCANCELLED"></span><span id="tapi_e_requestcancelled"></span><dl> <dt>**TAPI\_E\_REQUESTCANCELLED**</dt> <dt>((HRESULT)0x80040038L)</dt> </dl>                                         | The request was cancelled. <br/>                                                                                                                                                                                 |
| <span id="TAPI_E_INVALPRIVILEGE"></span><span id="tapi_e_invalprivilege"></span><dl> <dt>**TAPI\_E\_INVALPRIVILEGE**</dt> <dt>((HRESULT)0x80040039L)</dt> </dl>                                               | The application's [**privilege**](/windows/desktop/api/Tapi3if/ne-tapi3if-call_privilege) level is invalid for the current operation. <br/>                                                                                                          |
| <span id="TAPI_E_INVALIDDIRECTION"></span><span id="tapi_e_invaliddirection"></span><dl> <dt>**TAPI\_E\_INVALIDDIRECTION**</dt> <dt>((HRESULT)0x8004003AL)</dt> </dl>                                         | The [**TERMINAL\_DIRECTION**](/windows/desktop/api/Tapi3if/ne-tapi3if-terminal_direction) passed in was invalid. <br/>                                                                                                                               |
| <span id="TAPI_E_INVALIDTERMINAL"></span><span id="tapi_e_invalidterminal"></span><dl> <dt>**TAPI\_E\_INVALIDTERMINAL**</dt> <dt>((HRESULT)0x8004003BL)</dt> </dl>                                            | The terminal passed in was invalid for this operation. <br/>                                                                                                                                                     |
| <span id="TAPI_E_INVALIDTERMINALCLASS"></span><span id="tapi_e_invalidterminalclass"></span><dl> <dt>**TAPI\_E\_INVALIDTERMINALCLASS**</dt> <dt>((HRESULT)0x8004003CL)</dt> </dl>                             | The [**terminal class**](terminal-class.md) is invalid. <br/>                                                                                                                                                   |
| <span id="TAPI_E_NODRIVER"></span><span id="tapi_e_nodriver"></span><dl> <dt>**TAPI\_E\_NODRIVER**</dt> <dt>((HRESULT)0x8004003DL)</dt> </dl>                                                                 | The service provider was removed. <br/>                                                                                                                                                                          |
| <span id="TAPI_E_MAXSTREAMS"></span><span id="tapi_e_maxstreams"></span><dl> <dt>**TAPI\_E\_MAXSTREAMS**</dt> <dt>((HRESULT)0x8004003EL)</dt> </dl>                                                           | The maximum number of streams was reached. <br/>                                                                                                                                                                 |
| <span id="TAPI_E_NOTERMINALSELECTED"></span><span id="tapi_e_noterminalselected"></span><dl> <dt>**TAPI\_E\_NOTERMINALSELECTED**</dt> <dt>((HRESULT)0x8004003FL)</dt> </dl>                                   | The operation could not be performed because it requires terminals to be selected. <br/>                                                                                                                         |
| <span id="TAPI_E_TERMINALINUSE"></span><span id="tapi_e_terminalinuse"></span><dl> <dt>**TAPI\_E\_TERMINALINUSE**</dt> <dt>((HRESULT)0x80040040L)</dt> </dl>                                                  | The operation could not be performed because the terminal is in use. <br/>                                                                                                                                       |
| <span id="TAPI_E_NOTSTOPPED"></span><span id="tapi_e_notstopped"></span><dl> <dt>**TAPI\_E\_NOTSTOPPED**</dt> <dt>((HRESULT)0x80040041L)</dt> </dl>                                                           | The operation could not be performed because it requires the stream to be stopped. <br/>                                                                                                                         |
| <span id="TAPI_E_MAXTERMINALS"></span><span id="tapi_e_maxterminals"></span><dl> <dt>**TAPI\_E\_MAXTERMINALS**</dt> <dt>((HRESULT)0x80040042L)</dt> </dl>                                                     | The maximum number of terminals has been reached. <br/>                                                                                                                                                          |
| <span id="TAPI_E_INVALIDSTREAM"></span><span id="tapi_e_invalidstream"></span><dl> <dt>**TAPI\_E\_INVALIDSTREAM**</dt> <dt>((HRESULT)0x80040043L)</dt> </dl>                                                  | The stream passed in was invalid for this operation. <br/>                                                                                                                                                       |
| <span id="TAPI_E_TIMEOUT"></span><span id="tapi_e_timeout"></span><dl> <dt>**TAPI\_E\_TIMEOUT**</dt> <dt>((HRESULT)0x80040044L)</dt> </dl>                                                                    | The call failed because of a timeout. The timeout interval is two minutes. <br/>                                                                                                                                 |
| <span id="TAPI_E_CALLCENTER_GROUP_REMOVED"></span><span id="tapi_e_callcenter_group_removed"></span><dl> <dt>**TAPI\_E\_CALLCENTER\_GROUP\_REMOVED**</dt> <dt>((HRESULT)0x80040045L)</dt> </dl>               | The ACD Proxy has removed this group. Operations on this object are invalid. <br/>                                                                                                                               |
| <span id="TAPI_E_CALLCENTER_QUEUE_REMOVED"></span><span id="tapi_e_callcenter_queue_removed"></span><dl> <dt>**TAPI\_E\_CALLCENTER\_QUEUE\_REMOVED**</dt> <dt>((HRESULT)0x80040046L)</dt> </dl>               | The ACD Proxy has removed this queue. Operations on this object are invalid. <br/>                                                                                                                               |
| <span id="TAPI_E_CALLCENTER_NO_AGENT_ID"></span><span id="tapi_e_callcenter_no_agent_id"></span><dl> <dt>**TAPI\_E\_CALLCENTER\_NO\_AGENT\_ID**</dt> <dt>((HRESULT)0x80040047L)</dt> </dl>                    | The Agent object was created with [**CreateAgent**](https://msdn.microsoft.com/en-us/library/Aa380901(v=VS.85).aspx) and has no ID. If an ID is needed, use [**CreateAgentWithID**](https://msdn.microsoft.com/en-us/library/Aa380925(v=VS.85).aspx). <br/>                  |
| <span id="TAPI_E_CALLCENTER_INVALAGENTID"></span><span id="tapi_e_callcenter_invalagentid"></span><dl> <dt>**TAPI\_E\_CALLCENTER\_INVALAGENTID**</dt> <dt>((HRESULT)0x80040048L)</dt> </dl>                   | The agent ID is invalid. <br/>                                                                                                                                                                                   |
| <span id="TAPI_E_CALLCENTER_INVALAGENTGROUP"></span><span id="tapi_e_callcenter_invalagentgroup"></span><dl> <dt>**TAPI\_E\_CALLCENTER\_INVALAGENTGROUP**</dt> <dt>((HRESULT)0x80040049L)</dt> </dl>          | The agent group is invalid. <br/>                                                                                                                                                                                |
| <span id="TAPI_E_CALLCENTER_INVALPASSWORD"></span><span id="tapi_e_callcenter_invalpassword"></span><dl> <dt>**TAPI\_E\_CALLCENTER\_INVALPASSWORD**</dt> <dt>((HRESULT)0x8004004AL)</dt> </dl>                | The agent password is invalid. <br/>                                                                                                                                                                             |
| <span id="TAPI_E_CALLCENTER_INVALAGENTSTATE"></span><span id="tapi_e_callcenter_invalagentstate"></span><dl> <dt>**TAPI\_E\_CALLCENTER\_INVALAGENTSTATE**</dt> <dt>((HRESULT)0x8004004BL)</dt> </dl>          | The agent state is invalid. <br/>                                                                                                                                                                                |
| <span id="TAPI_E_CALLCENTER_INVALAGENTACTIVITY"></span><span id="tapi_e_callcenter_invalagentactivity"></span><dl> <dt>**TAPI\_E\_CALLCENTER\_INVALAGENTACTIVITY**</dt> <dt>((HRESULT)0x8004004CL)</dt> </dl> | The agent activity is invalid. <br/>                                                                                                                                                                             |
| <span id="TAPI_E_REGISTRY_SETTING_CORRUPT"></span><span id="tapi_e_registry_setting_corrupt"></span><dl> <dt>**TAPI\_E\_REGISTRY\_SETTING\_CORRUPT**</dt> <dt>((HRESULT)0x8004004DL)</dt> </dl>               | The registry setting is corrupt. <br/>                                                                                                                                                                           |
| <span id="TAPI_E_TERMINAL_PEER"></span><span id="tapi_e_terminal_peer"></span><dl> <dt>**TAPI\_E\_TERMINAL\_PEER**</dt> <dt>((HRESULT)0x8004004EL)</dt> </dl>                                                 | The peer for one of these bridge terminals has already been assigned. <br/>                                                                                                                                      |
| <span id="TAPI_E_PEER_NOT_SET"></span><span id="tapi_e_peer_not_set"></span><dl> <dt>**TAPI\_E\_PEER\_NOT\_SET**</dt> <dt>((HRESULT)0x8004004FL)</dt> </dl>                                                   | The peer for this bridge terminal must be set to complete this operation. <br/>                                                                                                                                  |
| <span id="TAPI_E_NOEVENT"></span><span id="tapi_e_noevent"></span><dl> <dt>**TAPI\_E\_NOEVENT**</dt> <dt>((HRESULT)0x80040050L)</dt> </dl>                                                                    | There is no event in the MSP's event queue. <br/>                                                                                                                                                                |
| <span id="TAPI_E_INVALADDRESSTYPE"></span><span id="tapi_e_invaladdresstype"></span><dl> <dt>**TAPI\_E\_INVALADDRESSTYPE**</dt> <dt>((HRESULT)0x80040051L)</dt> </dl>                                         | This address does not support the specified [**address type**](lineaddresstype--constants.md). <br/>                                                                                                            |
| <span id="TAPI_E_RESOURCEUNAVAIL"></span><span id="tapi_e_resourceunavail"></span><dl> <dt>**TAPI\_E\_RESOURCEUNAVAIL**</dt> <dt>((HRESULT)0x80040052L)</dt> </dl>                                            | A resource needed to fulfill the request is not available. <br/>                                                                                                                                                 |
| <span id="TAPI_E_PHONENOTOPEN"></span><span id="tapi_e_phonenotopen"></span><dl> <dt>**TAPI\_E\_PHONENOTOPEN**</dt> </dl>                                                                                                                                 | The phone is not open.<br/>                                                                                                                                                                                      |
| <span id="TAPI_E_CALLNOTSELECTED"></span><span id="tapi_e_callnotselected"></span><dl> <dt>**TAPI\_E\_CALLNOTSELECTED**</dt> </dl>                                                                                                                        | The specified call is not currently selected.<br/>                                                                                                                                                               |
| <span id="TAPI_E_WRONGEVENT"></span><span id="tapi_e_wrongevent"></span><dl> <dt>**TAPI\_E\_WRONGEVENT**</dt> </dl>                                                                                                                                       | This information is not available for this type of event.<br/>                                                                                                                                                   |
| <span id="TAPI_E_NOFORMAT"></span><span id="tapi_e_noformat"></span><dl> <dt>**TAPI\_E\_NOFORMAT**</dt> </dl>                                                                                                                                             | The format is unknown.<br/>                                                                                                                                                                                      |
| <span id="TAPI_E_INVALIDSTREAMSTATE"></span><span id="tapi_e_invalidstreamstate"></span><dl> <dt>**TAPI\_E\_INVALIDSTREAMSTATE**</dt> </dl>                                                                                                               | The operation is not permitted in current stream state.<br/>                                                                                                                                                     |
| <span id="TAPI_E_WRONG_STATE"></span><span id="tapi_e_wrong_state"></span><dl> <dt>**TAPI\_E\_WRONG\_STATE**</dt> </dl>                                                                                                                                   | The operation requested is not permitted for the current state.<br/>                                                                                                                                             |
| <span id="TAPI_E_NOT_INITIALIZED"></span><span id="tapi_e_not_initialized"></span><dl> <dt>**TAPI\_E\_NOT\_INITIALIZED**</dt> </dl>                                                                                                                       | The object has not been initialized.<br/>                                                                                                                                                                        |



## Requirements



|                         |                                                                                       |
|-------------------------|---------------------------------------------------------------------------------------|
| TAPI version<br/> | Requires TAPI 3.0 or later<br/>                                                 |
| Header<br/>       | <dl> <dt>Tapi3err.h</dt> </dl> |



 

 



