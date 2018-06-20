---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
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
  /me/mailFolders/{id}/messages/{id}/forward:
    post:
      summary: Message Forward
      description: 'message: forward Forward a message. The message is saved in the
        Sent Items folder.'
      operationId: Message:Forward
      x-api-path-slug: memailfoldersidmessagesidforward-post
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
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/forward:
    post:
      summary: Message Forward
      description: 'message: forward Forward a message. The message is saved in the
        Sent Items folder.'
      operationId: Message:Forward
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidforward-post
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
  /groups/{id}/threads/{id}/posts/{id}/forward:
    post:
      summary: Post Forward
      description: 'post: forward Forward a post to a recipient. You can specify both
        the parent conversation and thread in the request, or, you can specify just
        the parent thread without the parent conversation.'
      operationId: Post:Forward
      x-api-path-slug: groupsidthreadsidpostsidforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Forward
  /groups/{id}/conversations/{id}/threads/{id}/posts/{id}/forward:
    post:
      summary: Post Forward
      description: 'post: forward Forward a post to a recipient. You can specify both
        the parent conversation and thread in the request, or, you can specify just
        the parent thread without the parent conversation.'
      operationId: Post:Forward
      x-api-path-slug: groupsidconversationsidthreadsidpostsidforward-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Forward
---