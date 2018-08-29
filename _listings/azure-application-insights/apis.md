---
name: Azure Application Insights
x-slug: azure-application-insights
description: Get rich performance monitoring, powerful alerting, and easy-to-consume
  dashboards to help ensure your applications are available and performing as you
  expect. Quickly see if you have a problem, how many customers are affected, and
  perform a root cause analysis to find and fix the issue.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/performance-management.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Azure Application Insights
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/apis.md
specificationVersion: "0.14"
apis:
- name: Application Insights API - List Operations
  x-api-slug: providersmicrosoft-insightsoperations-get
  description: Lists all of the available insights REST API operations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/performance-management.png
  humanURL: https://azure.microsoft.com/en-us/services/application-insights/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Testing, Diagnostics, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/providersmicrosoft-insightsoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/providersmicrosoft-insightsoperations-get-openapi.md
- name: Application Insights API - List Components
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-insightscomponents-get
  description: Gets a list of all Application Insights components within a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/performance-management.png
  humanURL: https://azure.microsoft.com/en-us/services/application-insights/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Testing, Diagnostics, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/subscriptionssubscriptionidprovidersmicrosoft-insightscomponents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/subscriptionssubscriptionidprovidersmicrosoft-insightscomponents-get-openapi.md
- name: Application Insights API - List Components By Resource Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightscomponents-get
  description: Gets a list of Application Insights components within a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/performance-management.png
  humanURL: https://azure.microsoft.com/en-us/services/application-insights/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Testing, Diagnostics, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightscomponents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightscomponents-get-openapi.md
- name: Application Insights API - Delete Components
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightscomponentsresourcename-delete
  description: Deletes an Application Insights component.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/performance-management.png
  humanURL: https://azure.microsoft.com/en-us/services/application-insights/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Testing, Diagnostics, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightscomponentsresourcename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightscomponentsresourcename-delete-openapi.md
- name: Application Insights API - Get Components
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightscomponentsresourcename-get
  description: Returns an Application Insights component.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/performance-management.png
  humanURL: https://azure.microsoft.com/en-us/services/application-insights/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Testing, Diagnostics, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightscomponentsresourcename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightscomponentsresourcename-get-openapi.md
- name: Application Insights API - Create or Update Components
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightscomponentsresourcename-put
  description: 'Creates (or updates) an Application Insights component. Note: You
    cannot specify a different value for InstrumentationKey nor AppId in the Put operation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/performance-management.png
  humanURL: https://azure.microsoft.com/en-us/services/application-insights/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Testing, Diagnostics, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightscomponentsresourcename-put-openapi.md
- name: Application Insights API - Update Components Tags
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightscomponentsresourcename-patch
  description: Updates an existing component's tags. To update other fields use the
    CreateOrUpdate method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/performance-management.png
  humanURL: https://azure.microsoft.com/en-us/services/application-insights/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Testing, Diagnostics, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightscomponentsresourcename-patch-openapi.md
- name: Application Insights API - Web Tests By Resource Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightswebtests-get
  description: Get all Application Insights web tests defined within a specified resource
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/performance-management.png
  humanURL: https://azure.microsoft.com/en-us/services/application-insights/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Testing, Diagnostics, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightswebtests-get-openapi.md
- name: Application Insights API - Get Web Tests
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightswebtestswebtestname-get
  description: Get a specific Application Insights web test definition.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/performance-management.png
  humanURL: https://azure.microsoft.com/en-us/services/application-insights/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Testing, Diagnostics, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightswebtestswebtestname-get-openapi.md
- name: Application Insights API - Create or Update Web Tests
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightswebtestswebtestname-put
  description: Creates or updates an Application Insights web test definition.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/performance-management.png
  humanURL: https://azure.microsoft.com/en-us/services/application-insights/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Testing, Diagnostics, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightswebtestswebtestname-put-openapi.md
- name: Application Insights API - Update Web Tests Tags
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightswebtestswebtestname-patch
  description: Creates or updates an Application Insights web test definition.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/performance-management.png
  humanURL: https://azure.microsoft.com/en-us/services/application-insights/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Testing, Diagnostics, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightswebtestswebtestname-patch-openapi.md
- name: Application Insights API - Delete Web Tests
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightswebtestswebtestname-delete
  description: Deletes an Application Insights web test.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/performance-management.png
  humanURL: https://azure.microsoft.com/en-us/services/application-insights/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Testing, Diagnostics, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightswebtestswebtestname-delete-openapi.md
- name: Application Insights API - List Web Tests
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-insightswebtests-get
  description: Get all Application Insights web test alerts definitioned within a
    subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/performance-management.png
  humanURL: https://azure.microsoft.com/en-us/services/application-insights/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Testing, Diagnostics, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-application-insights/master/_listings/azure-application-insights/subscriptionssubscriptionidprovidersmicrosoft-insightswebtests-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.api.management.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.application.insights.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/application-insights/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/application-insights/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/application-insights/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/application-insights/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---