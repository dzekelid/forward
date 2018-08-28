swagger: "2.0"
x-collection-name: TigerText
x-complete: 1
info:
  title: TigerConnect User API
  description: the-user-system-for-tigerconnect-messaging-platform-
  termsOfService: http://www.tigertext.com/developer-terms-of-use
  contact:
    name: TigerText
    url: http://www.tigertext.com/supportform/
    email: info@tigertext.com
  version: v2
host: developer.tigertext.me
basePath: /v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /message/{message_token}/forward/:
    post:
      summary: Forward the message to the following User or Group.
      description: Forward the message to the following User or Group.
      operationId: forwardMessage
      x-api-path-slug: messagemessage-tokenforward-post
      parameters:
      - in: path
        name: message_token
        description: The message token
      - in: formData
        name: recipient_organization
        description: The recipient organization token
      - in: formData
        name: recipient_token
        description: The recipient User or Group token based on address encoding
      - in: formData
        name: sender_organization
        description: The sender User organization token
      responses:
        200:
          description: OK
      tags:
      - Message
      - Message
      - Token
      - Forward