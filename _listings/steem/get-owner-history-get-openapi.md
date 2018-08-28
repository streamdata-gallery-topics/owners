---
swagger: "2.0"
x-collection-name: Steem
x-complete: 0
info:
  title: Steem get_owner_history
  description: get_owner_history
  version: 1.0.0
host: api.steemjs.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /get_owner_history:
    get:
      summary: get_owner_history
      description: get_owner_history
      operationId: get-owner-history
      x-api-path-slug: get-owner-history-get
      parameters:
      - in: query
        name: account
        description: account name
      responses:
        200:
          description: OK
      tags:
      - Get
      - Owner
      - History
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