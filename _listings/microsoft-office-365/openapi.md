swagger: "2.0"
x-collection-name: Microsoft Office 365
x-complete: 1
info:
  title: Microsoft Office 365
  description: office-365-is-the-brand-name-used-by-microsoft-for-a-group-of-software-plus-services-subscriptions-that-provides-productivity-software-and-related-services-to-its-subscribers-
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
    parameters:
      summary: Parameters Messages Message Forward
      description: Parameters messages message  forward
      operationId: parametersMessagesMessageForward
      x-api-path-slug: messagesmessage-idforward-parameters
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Forward