---
title: "workbookChartAxes resource type"
description: "Represents the chart axes."
author: "lumine2008"
localization_priority: Normal
ms.prod: "excel"
---

# workbookChartAxes resource type

> **Important:** APIs under the /beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

Represents the chart axes.


## Methods
None

## Properties
None

## Relationships
| Relationship | Type	|Description|
|:---------------|:--------|:----------|
|categoryAxis|[workbookChartAxis](workbookchartaxis.md)|Represents the category axis in a chart. Read-only.|
|seriesAxis|[workbookChartAxis](workbookchartaxis.md)|Represents the series axis of a 3-dimensional chart. Read-only.|
|valueAxis|[workbookChartAxis](workbookchartaxis.md)|Represents the value axis in an axis. Read-only.|

## JSON representation

Here is a JSON representation of the resource.

<!--{
  "blockType": "resource",
  "optionalProperties": [],
  "baseType": "microsoft.graph.entity",
  "@odata.type": "microsoft.graph.workbookChartAxes"
}-->

```json
{
  "categoryAxis": {"@odata.type": "microsoft.graph.workbookChartAxis"},
  "seriesAxis": {"@odata.type": "microsoft.graph.workbookChartAxis"},
  "valueAxis": {"@odata.type": "microsoft.graph.workbookChartAxis"}
}

```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "ChartAxes resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->