---
swagger: "2.0"
x-collection-name: Kentico Cloud
x-complete: 0
info:
  title: Kentico Cloud View data of visitor by email
  description: ""
  version: 1.0.0
host: deliver.kenticocloud.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /uid/7888c9a3824a11f1:
    get:
      summary: View data of visitor by ID
      description: ""
      operationId: Uid7888c9a3824a11f1Get
      x-api-path-slug: uid7888c9a3824a11f1-get
      responses:
        200:
          description: OK
      tags:
      - View
      - Data
      - Of
      - Visitor
      - By
      - ID
    delete:
      summary: Delete data of visitor by ID
      description: ""
      operationId: Uid7888c9a3824a11f1Delete
      x-api-path-slug: uid7888c9a3824a11f1-delete
      responses:
        200:
          description: OK
      tags:
      - Data
      - Of
      - Visitor
      - By
      - ID
  /email/lola.mira@blabla.com:
    get:
      summary: View data of visitor by email
      description: ""
      operationId: EmailLolaMiraBlablaComGet
      x-api-path-slug: emaillola-mirablabla-com-get
      responses:
        200:
          description: OK
      tags:
      - View
      - Data
      - Of
      - Visitor
      - By
      - Email
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