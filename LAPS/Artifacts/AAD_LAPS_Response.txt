##### Partial Response
HTTP/1.1 200 OK
Content-Type: application/json;odata.metadata=minimal;odata.streaming=true;IEEE754Compatible=false;charset=utf-8
Vary: Accept-Encoding
Strict-Transport-Security: max-age=31536000
request-id: 1a63a54d-5192-42d6-9ca1-4d5a39bcb274
client-request-id: 96cbfa59-dbfc-4a92-b261-7f77bd8f4b9b
x-ms-ags-diagnostic: {"ServerInfo":{"DataCenter":"UK South","Slice":"E","Ring":"3","ScaleUnit":"002","RoleInstance":"LO1PEPF0000008B"}}
Link: <https://developer.microsoft-tst.com/en-us/graph/changes?$filterby=beta,PrivatePreview:lapsPreview&from>;rel="deprecation";type="text/html"
Link: <https://developer.microsoft-tst.com/en-us/graph/changes?$filterby=beta,PrivatePreview:lapsPreview&from>;rel="deprecation";type="text/html"
Deprecation: Thu, 02 Jun 2022 23:59:59 GMT
OData-Version: 4.0
{
  "@odata.context": "https://graph.microsoft.com/beta/$metadata#deviceLocalCredentials(credentials)/$entity",
  "id": "399ca52a-385d-45f7-9974-c34fd760a1db",
  "deviceName": "W11-CL1",
  "lastBackupDateTime": "2023-12-21T08:12:02",
  "refreshDateTime": "2023-13-21T09:12:00",
  "credentials": [
    {
      "accountName": "eadmin",
      "accountSid": "S-x-x-x-xxxxxxxx-xxxxxxx-xxxxxxxx-500",
      "backupDateTime": "2023-04-21T22:48:02",
      "passwordBase64": "xxxxxxxxx"
    }
}
