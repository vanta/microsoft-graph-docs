﻿# Get eBookGroupAssignment

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

Read properties and relationships of the [eBookGroupAssignment](../resources/intune_books_ebookgroupassignment.md) object.
## Prerequisites
One of the following **scopes** is required to execute this API:

*DeviceManagementApps.ReadWrite.All; DeviceManagementApps.Read.All*
## HTTP Request
<!-- {
  "blockType": "ignored"
}
-->
```http
GET /eBookGroupAssignments/{eBookGroupAssignmentsId}
GET /deviceAppManagement/managedEBooks/{managedEBookId}/groupAssignments/{eBookGroupAssignmentId}
```

## Optional query parameters
This method supports the [OData Query Parameters](http://graph.microsoft.io/docs/overview/query_parameters) to help customize the response.
## Request headers
|Header|Value|
|---|---|
|Authorization|Bearer {token}. Required.|
|Accept|application/json|

## Request body
Do not supply a request body for this method.

## Response
If successful, this method returns a `200 OK` response code and [eBookGroupAssignment](../resources/intune_books_ebookgroupassignment.md) object in the response body.

## Example
### Request
Here is an example of the request.
```http
GET https://graph.microsoft.com/beta/eBookGroupAssignments/{eBookGroupAssignmentsId}
```

### Response
Here is an example of the response. Note: The response object shown here may be truncated for brevity. All of the properties will be returned from an actual call.
```http
HTTP/1.1 200 OK
Content-Type: application/json
Content-Length: 216

{
  "value": {
    "@odata.type": "#microsoft.graph.eBookGroupAssignment",
    "targetGroupId": "Target Group Id value",
    "id": "6cb57cb9-7cb9-6cb5-b97c-b56cb97cb56c",
    "installIntent": "available"
  }
}
```



