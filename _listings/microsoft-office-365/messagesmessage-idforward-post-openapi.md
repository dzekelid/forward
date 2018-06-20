---
swagger: "2.0"
x-collection-name: Microsoft Office 365
x-complete: 0
info:
  title: Microsoft Office 365 Add Messages Message Forward
  description: You can forward an email by using the Forward action on the ...
  version: 1.0.0
host: outlook.office365.com
basePath: /ews/odata/Me
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Messages{message_id}/CreateForward:
    post:
      summary: Add Messages Message Createforward
      description: Post messages message  createforward
      operationId: postMessagesMessageCreateforward
      x-api-path-slug: messagesmessage-idcreateforward-post
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Createforward
    parameters:
      summary: Parameters Messages Message Createforward
      description: Parameters messages message  createforward
      operationId: parametersMessagesMessageCreateforward
      x-api-path-slug: messagesmessage-idcreateforward-parameters
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Createforward
  /Messages{message_id}/Forward:
    post:
      summary: Add Messages Message Forward
      description: You can forward an email by using the Forward action on the ...
      operationId: postMessagesMessageForward
      x-api-path-slug: messagesmessage-idforward-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Forward
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