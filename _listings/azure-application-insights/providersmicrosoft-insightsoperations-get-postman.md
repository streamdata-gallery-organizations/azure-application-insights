{
  "info": {
    "name": "Azure Application Insights API List Operations",
    "_postman_id": "34e35654-80ed-4d09-895f-0185548b379e",
    "description": "Lists all of the available insights REST API operations.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "operations",
      "item": [
        {
          "id": "e1878144-ee2c-4ccf-a25c-55272a9f7366",
          "name": "Operations_List",
          "request": {
            "url": "http://management.azure.com/providers/microsoft.insights/operations?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all of the available insights REST API operations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "89aea4ac-c58e-432a-b528-0bd9efc3bf34"
            }
          ]
        }
      ]
    }
  ]
}