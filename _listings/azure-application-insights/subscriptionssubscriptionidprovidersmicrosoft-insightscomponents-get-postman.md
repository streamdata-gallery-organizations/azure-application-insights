{
  "info": {
    "name": "Azure Application Insights API List Components",
    "_postman_id": "4808f9c5-1da6-4a64-90fb-c4230c40770b",
    "description": "Gets a list of all Application Insights components within a subscription.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "components",
      "item": [
        {
          "id": "05421ed5-e30d-4219-a01b-1ac46d34073b",
          "name": "Components_List",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/providers/microsoft.insights/components"
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
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of all Application Insights components within a subscription"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c821905-0faa-46e2-8aa4-20d17201f152"
            }
          ]
        }
      ]
    }
  ]
}