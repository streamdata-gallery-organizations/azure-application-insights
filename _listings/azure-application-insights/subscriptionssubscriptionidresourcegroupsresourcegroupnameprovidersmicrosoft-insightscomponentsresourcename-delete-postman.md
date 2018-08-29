{
  "info": {
    "name": "Azure Application Insights API Delete Components",
    "_postman_id": "87bb9ae9-91d2-4222-9f66-38aabece4d98",
    "description": "Deletes an Application Insights component.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "components",
      "item": [
        {
          "id": "ca992520-bcaa-47a4-8c57-b1a4b468bf6f",
          "name": "Components_Delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/microsoft.insights/components/:resourceName"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "resourceGroupName",
                  "type": "string"
                },
                {
                  "id": "resourceName",
                  "value": "resourceName",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an Application Insights component"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "caef2e66-3603-4450-8a7d-6bb158ed12b0"
            }
          ]
        }
      ]
    }
  ]
}