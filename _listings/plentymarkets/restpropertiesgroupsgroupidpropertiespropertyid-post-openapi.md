---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Attach a property to a property group
  description: Attaches a property to a property group. The ID of the property and
    the ID of the property group must be specified.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/properties/groups/{groupId}/properties:
    post:
      summary: Mass attach propertyId and groupId collection into the pivot table.
      description: Mass attach propertyid and groupid collection into the pivot table..
      operationId: postRestPropertiesGroupsGroupProperties
      x-api-path-slug: restpropertiesgroupsgroupidproperties-post
      parameters:
      - in: path
        name: groupId
      responses:
        2:
          description: Successful response
        200:
          description: OK
      tags:
      - Mass
      - Attach
      - PropertyId
      - GroupId
      - Collection
      - Into
      - Pivot
      - Table
  /rest/properties/groups/{groupId}/properties/{propertyId}:
    post:
      summary: Attach a property to a property group
      description: Attaches a property to a property group. The ID of the property
        and the ID of the property group must be specified.
      operationId: postRestPropertiesGroupsGroupPropertiesProperty
      x-api-path-slug: restpropertiesgroupsgroupidpropertiespropertyid-post
      parameters:
      - in: path
        name: groupId
      - in: path
        name: propertyId
      responses:
        200:
          description: OK
      tags:
      - Attach
      - Property
      - To
      - Property
      - Group
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