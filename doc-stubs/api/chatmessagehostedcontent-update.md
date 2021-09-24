---
title: "Update chatMessageHostedContent"
description: "Update the properties of a chatMessageHostedContent object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update chatMessageHostedContent
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of a [chatMessageHostedContent](../resources/chatmessagehostedcontent.md) object.

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
PATCH /chats/{chatsId}/messages/{chatMessageId}/hostedContents/{chatMessageHostedContentId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
[!INCLUDE [table-intro](../../includes/update-property-table-intro.md)]


|Property|Type|Description|
|:---|:---|:---|
|contentBytes|Binary|**TODO: Add Description** Inherited from [teamworkHostedContent](../resources/teamworkhostedcontent.md). Optional.|
|contentType|String|**TODO: Add Description** Inherited from [teamworkHostedContent](../resources/teamworkhostedcontent.md). Optional.|



## Response

If successful, this method returns a `200 OK` response code and an updated [chatMessageHostedContent](../resources/chatmessagehostedcontent.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_chatmessagehostedcontent"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/chats/{chatsId}/messages/{chatMessageId}/hostedContents/{chatMessageHostedContentId}
Content-Type: application/json
Content-length: 123

{
  "@odata.type": "#microsoft.graph.chatMessageHostedContent",
  "contentBytes": "Binary",
  "contentType": "String"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.chatMessageHostedContent",
  "id": "b93d7460-7460-b93d-6074-3db960743db9",
  "contentBytes": "Binary",
  "contentType": "String"
}
```
