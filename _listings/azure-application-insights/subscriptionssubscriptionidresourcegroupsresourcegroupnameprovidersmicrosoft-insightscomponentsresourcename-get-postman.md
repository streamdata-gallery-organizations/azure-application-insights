{
  "info": {
    "name": "Azure Application Insights API Get Components",
    "_postman_id": "2469da8e-923f-4921-b8ba-5df2bc03150f",
    "description": "Returns an Application Insights component.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "components",
      "item": [
        {
          "id": "7aa7382b-e93d-4000-a185-540da2296597",
          "name": "Components_Get",
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns an Application Insights component"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b2d7759f-f724-448f-8c9b-5b1378f5768e"
            }
          ]
        }
      ]
    }
  ]
}