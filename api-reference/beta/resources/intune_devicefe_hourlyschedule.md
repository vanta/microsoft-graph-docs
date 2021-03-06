﻿# hourlySchedule resource type

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

Hourly run schedule of a recurring device management script.

Inherits from [runSchedule](../resources/intune_devicefe_runschedule.md)

## Properties
|Property|Type|Description|
|---|---|---|
|interval|Int32|Interval in number of hours|

## Relationships
None
## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.hourlySchedule"
}
-->
```json
{
  "@odata.type": "#microsoft.graph.hourlySchedule",
  "interval": 1024
}
```



