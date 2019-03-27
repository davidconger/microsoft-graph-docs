---
title: "workbookChartDataLabels resource type"
description: "Represents a collection of all the data labels on a chart point."
author: "lumine2008"
localization_priority: Normal
ms.prod: "excel"
---

# workbookChartDataLabels resource type

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Represents a collection of all the data labels on a chart point.


## Methods

| Method		   | Return Type	|Description|
|:---------------|:--------|:----------|
|[Get workbookChartDataLabels](../api/chartdatalabels-get.md) | [workbookChartDataLabels](workbookchartdatalabels.md) |Read properties and relationships of chartDataLabels object.|
|[Update](../api/chartdatalabels-update.md) | [workbookChartDataLabels](workbookchartdatalabels.md)	|Update ChartDataLabels object. |

## Properties
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|position|string|DataLabelPosition value that represents the position of the data label. The possible values are: `None`, `Center`, `InsideEnd`, `InsideBase`, `OutsideEnd`, `Left`, `Right`, `Top`, `Bottom`, `BestFit`, `Callout`.|
|separator|string|String representing the separator used for the data labels on a chart.|
|showBubbleSize|boolean|Boolean value representing if the data label bubble size is visible or not.|
|showCategoryName|boolean|Boolean value representing if the data label category name is visible or not.|
|showLegendKey|boolean|Boolean value representing if the data label legend key is visible or not.|
|showPercentage|boolean|Boolean value representing if the data label percentage is visible or not.|
|showSeriesName|boolean|Boolean value representing if the data label series name is visible or not.|
|showValue|boolean|Boolean value representing if the data label value is visible or not.|

## Relationships
| Relationship | Type	|Description|
|:---------------|:--------|:----------|
|format|[workbookChartDataLabelFormat](workbookchartdatalabelformat.md)|Represents the format of chart data labels, which includes fill and font formatting. Read-only.|

## JSON representation

Here is a JSON representation of the resource.

<!--{
  "blockType": "resource",
  "baseType": "microsoft.graph.entity",
  "optionalProperties": [],
  "@odata.type": "microsoft.graph.workbookChartDataLabels"
}-->

```json
{
  "position": "string",
  "separator": "string",
  "showBubbleSize": true,
  "showCategoryName": true,
  "showLegendKey": true,
  "showPercentage": true,
  "showSeriesName": true,
  "showValue": true
}

```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!--
{
  "type": "#page.annotation",
  "description": "workbookChartDataLabels resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": "",
  "suppressions": [
    "Error: /api-reference/beta/resources/workbookchartdatalabels.md:\r\n      Exception processing links.\r\n    System.ArgumentException: Link Definition was null. Link text: !INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)\r\n      at ApiDoctor.Validation.DocFile.get_LinkDestinations()\r\n      at ApiDoctor.Validation.DocSet.ValidateLinks(Boolean includeWarnings, String[] relativePathForFiles, IssueLogger issues, Boolean requireFilenameCaseMatch, Boolean printOrphanedFiles)"
  ]
}
-->