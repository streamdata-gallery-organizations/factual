---
swagger: "2.0"
x-collection-name: Factual
x-complete: 0
info:
  title: Factual Get Table Name Facets
  description: Get table name facets.
  version: 1.0.0
host: api.v3.factual.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /t/{table_name}/boost:
    post:
      summary: Post Table Name Boost
      description: Post table name boost.
      operationId: postTTableNameBoost
      x-api-path-slug: ttable-nameboost-post
      parameters:
      - in: path
        name: table_name
      responses:
        200:
          description: OK
      tags:
      - Table
      - Name
      - Boost
  /t/{table_name}/facets:
    get:
      summary: Get Table Name Facets
      description: Get table name facets.
      operationId: getTTableNameFacets
      x-api-path-slug: ttable-namefacets-get
      parameters:
      - in: path
        name: table_name
      responses:
        200:
          description: OK
      tags:
      - Table
      - Name
      - Facets
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