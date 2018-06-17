---
swagger: "2.0"
x-collection-name: Envestnet
x-complete: 0
info:
  title: Crunch Base Acquistions
  description: Pull from Acquisition
  termsOfService: https://data.crunchbase.com/v3/page/accessing-the-dataset
  contact:
    name: Crunchbase
    url: https://groups.google.com/forum/#!forum/crunchbase-api
    email: data@crunchbase.com
  version: v3
host: api.crunchbase.com
basePath: /v/3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /acquisitions/{uuid}:
    get:
      summary: Acquistions
      description: Pull from Acquisition
      operationId: acquistions
      x-api-path-slug: acquisitionsuuid-get
      parameters:
      - in: query
        name: user_key
        description: This user_key is used to validate each developers access to the
          API and ensure that any rate limits or quotas are respected
      - in: path
        name: uuid
        description: The UUID of the acquisition
      responses:
        200:
          description: OK
      tags:
      - Acquisitions
      - Uuid
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