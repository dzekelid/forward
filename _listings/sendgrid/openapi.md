swagger: "2.0"
x-collection-name: SendGrid
x-complete: 1
info:
  title: SendGrid
  version: 1.0.0
host: api.sendgrid.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /mail_settings/forward_bounce:
    get:
      summary: Get Mail Settings Forward Bounce
      description: |-
        **This endpoint allows you to retrieve your current bounce forwarding mail settings.**

        Activating this setting allows you to specify an email address to which bounce reports are forwarded.

        Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid???s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).
      operationId: mail_settings.forward_bounce.get
      x-api-path-slug: mail-settingsforward-bounce-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Mail
      - Settings
      - Forward
      - Bounce
    patch:
      summary: Patch Mail Settings Forward Bounce
      description: |-
        **This endpoint allows you to update your current bounce forwarding mail settings.**

        Activating this setting allows you to specify an email address to which bounce reports are forwarded.

        Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid???s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).
      operationId: mail_settings.forward_bounce.patch
      x-api-path-slug: mail-settingsforward-bounce-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Mail
      - Settings
      - Forward
      - Bounce
  /mail_settings/forward_spam:
    get:
      summary: Get Mail Settings Forward Spam
      description: |-
        **This endpoint allows you to retrieve your current Forward Spam mail settings.**

        Enabling the forward spam setting allows you to specify an email address to which spam reports will be forwarded.

        Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid???s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).
      operationId: mail_settings.forward_spam.get
      x-api-path-slug: mail-settingsforward-spam-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Mail
      - Settings
      - Forward
      - Spam
    patch:
      summary: Patch Mail Settings Forward Spam
      description: |-
        **This endpoint allows you to update your current Forward Spam mail settings.**

        Enabling the forward spam setting allows you to specify an email address to which spam reports will be forwarded.

        Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid???s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).
      operationId: mail_settings.forward_spam.patch
      x-api-path-slug: mail-settingsforward-spam-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Mail
      - Settings
      - Forward
      - Spam