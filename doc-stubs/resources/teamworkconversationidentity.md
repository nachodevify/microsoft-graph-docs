---
title: "teamworkConversationIdentity resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# teamworkConversationIdentity resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [identity](../resources/identity.md).

## Properties
|Property|Type|Description|
|:---|:---|:---|
|conversationIdentityType|teamworkConversationIdentityType|**TODO: Add Description**. The possible values are: `team`, `channel`, `chat`, `unknownFutureValue`.|
|displayName|String|**TODO: Add Description** Inherited from [identity](../resources/identity.md).|
|id|String|**TODO: Add Description** Inherited from [identity](../resources/identity.md).|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.teamworkConversationIdentity"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.teamworkConversationIdentity",
  "id": "String (identifier)",
  "displayName": "String",
  "conversationIdentityType": "String"
}
```
