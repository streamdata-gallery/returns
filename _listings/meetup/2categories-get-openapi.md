---
swagger: "2.0"
x-collection-name: Meetup
x-complete: 0
info:
  title: Meetup Categories
  description: Returns a list of Meetup group categories
  version: 1.0.0
host: api.meetup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /2/categories:
    get:
      summary: Categories
      description: Returns a list of Meetup group categories
      operationId: categories
      x-api-path-slug: 2categories-get
      parameters:
      - in: query
        name: fields
        description: Parameter for requesting optional response properties
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Categories
x-streamrank:
  polling_total_time_average: "0.07"
  polling_size_download_average: "3145"
  streaming_total_time_average: "0.07"
  streaming_size_download_average: "3145"
  change_yes: "1"
  change_no: "0"
  time_percentage: "0"
  size_percentage: "0"
  change_percentage: "100"
  last_run: "2018-05-04"
  days_run: "0"
  minute_run: "0"
---