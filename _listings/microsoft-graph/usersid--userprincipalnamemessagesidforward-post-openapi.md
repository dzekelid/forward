---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Message Forward
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/messages/{id}/createForward:
    post:
      summary: Message Create Forward
      description: 'message: createForward Create a draft of the Forward message.
        You can then update or send the draft.'
      operationId: Message:CreateForward
      x-api-path-slug: memessagesidcreateforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Forward
  /users/{id | userPrincipalName}/messages/{id}/createForward:
    post:
      summary: Message Create Forward
      description: 'message: createForward Create a draft of the Forward message.
        You can then update or send the draft.'
      operationId: Message:CreateForward
      x-api-path-slug: usersid--userprincipalnamemessagesidcreateforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Forward
  /me/mailFolders/{id}/messages/{id}/createForward:
    post:
      summary: Message Create Forward
      description: 'message: createForward Create a draft of the Forward message.
        You can then update or send the draft.'
      operationId: Message:CreateForward
      x-api-path-slug: memailfoldersidmessagesidcreateforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Forward
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/createForward:
    post:
      summary: Message Create Forward
      description: 'message: createForward Create a draft of the Forward message.
        You can then update or send the draft.'
      operationId: Message:CreateForward
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Forward
  /me/messages/{id}/forward:
    post:
      summary: Message Forward
      description: 'message: forward Forward a message. The message is saved in the
        Sent Items folder.'
      operationId: Message:Forward
      x-api-path-slug: memessagesidforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Forward
  /users/{id | userPrincipalName}/messages/{id}/forward:
    post:
      summary: Message Forward
      description: 'message: forward Forward a message. The message is saved in the
        Sent Items folder.'
      operationId: Message:Forward
      x-api-path-slug: usersid--userprincipalnamemessagesidforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
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