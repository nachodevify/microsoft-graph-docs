---
title: "List chatMessageInfoes"
description: "Get a list of the chatMessageInfo objects and their properties."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List chatMessageInfoes
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Get a list of the [chatMessageInfo](../resources/chatmessageinfo.md) objects and their properties.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
GET ** Collection URI for Microsoft.Teams.GraphSvc.chatMessageInfo not found
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a collection of [chatMessageInfo](../resources/chatmessageinfo.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "list_chatmessageinfo"
}
-->
``` http
GET https://graph.microsoft.com/beta** Collection URI for Microsoft.Teams.GraphSvc.chatMessageInfo not found
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(Microsoft.Teams.GraphSvc.chatMessageInfo)"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": [
    {
      "@odata.type": "#Microsoft.Teams.GraphSvc.chatMessageInfo",
      "id": "8de5f1a0-f1a0-8de5-a0f1-e58da0f1e58d",
      "body": {
        "@odata.type": "microsoft.graph.itemBody"
      },
      "from": {
        "@odata.type": "microsoft.graph.chatMessageFromIdentitySet"
      },
      "createdDateTime": "String (timestamp)",
      "isDeleted": "Boolean",
      "messageType": "String",
      "eventDetail": {
        "@odata.type": "microsoft.graph.eventMessageDetail"
      }
    }
  ]
}
```
