{
  "info": {
    "name": "Azure Application Insights API List Components By Resource Group",
    "_postman_id": "24b600e0-c62c-47a2-a45c-8fd0440fd80a",
    "description": "Gets a list of Application Insights components within a resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "components",
      "item": [
        {
          "id": "44c71e70-a493-4ffb-b7b9-9350ca8d345f",
          "name": "Components_ListByResourceGroup",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/microsoft.insights/components"
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
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of Application Insights components within a resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "efa86d8e-d5ea-4bbb-ab51-b4f449b43d70"
            }
          ]
        }
      ]
    }
  ]
}