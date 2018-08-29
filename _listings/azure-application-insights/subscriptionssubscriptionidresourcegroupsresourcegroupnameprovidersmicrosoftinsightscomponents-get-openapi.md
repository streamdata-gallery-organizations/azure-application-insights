---
swagger: "2.0"
x-collection-name: Azure Application Insights
x-complete: 0
info:
  title: Azure Application Insights API List Components By Resource Group
  description: Gets a list of Application Insights components within a resource group.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /providers/microsoft.insights/operations:
    get:
      summary: List Operations
      description: Lists all of the available insights REST API operations.
      operationId: Operations_List
      x-api-path-slug: providersmicrosoftinsightsoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operations
  /subscriptions/{subscriptionId}/providers/microsoft.insights/components:
    get:
      summary: List Components
      description: Gets a list of all Application Insights components within a subscription.
      operationId: Components_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftinsightscomponents-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Components
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/microsoft.insights/components:
    get:
      summary: List Components By Resource Group
      description: Gets a list of Application Insights components within a resource
        group.
      operationId: Components_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftinsightscomponents-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Components
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---