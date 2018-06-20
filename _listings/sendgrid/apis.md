---
name: SendGrid
x-slug: sendgrid
description: Delivering your transactional and marketing emails through the worlds
  largest cloud-based email delivery platform. Send with confidence.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
x-kinRank: "9"
x-alexaRank: "9582"
tags: Forward
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/sendgrid/apis.md
specificationVersion: "0.14"
apis:
- name: SendGrid Get Mail Settings Forward Bounce
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current bounce forwarding
    mail settings.**\n\nActivating this setting allows you to specify an email address
    to which bounce reports are forwarded.\n\nMail settings allow you to tell SendGrid
    specific things to do to every email that you send to your recipients over SendGrid\u2019s
    [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP
    Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/forward_bounce
  tags: Email,Mail, Settings, Forward, Bounce
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/sendgrid/mail-settingsforward-bounce-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/sendgrid/mail-settingsforward-bounce-get-openapi.md
- name: SendGrid Patch Mail Settings Forward Bounce
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current bounce forwarding
    mail settings.**\n\nActivating this setting allows you to specify an email address
    to which bounce reports are forwarded.\n\nMail settings allow you to tell SendGrid
    specific things to do to every email that you send to your recipients over SendGrid\u2019s
    [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP
    Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/forward_bounce
  tags: Email,Mail, Settings, Forward, Bounce
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/sendgrid/mail-settingsforward-bounce-patch-openapi.md
- name: SendGrid Get Mail Settings Forward Spam
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current Forward Spam mail
    settings.**\n\nEnabling the forward spam setting allows you to specify an email
    address to which spam reports will be forwarded.\n\nMail settings allow you to
    tell SendGrid specific things to do to every email that you send to your recipients
    over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
    or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/forward_spam
  tags: Email,Mail, Settings, Forward, Spam
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/sendgrid/mail-settingsforward-spam-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/sendgrid/mail-settingsforward-spam-get-openapi.md
- name: SendGrid Patch Mail Settings Forward Spam
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current Forward Spam mail
    settings.**\n\nEnabling the forward spam setting allows you to specify an email
    address to which spam reports will be forwarded.\n\nMail settings allow you to
    tell SendGrid specific things to do to every email that you send to your recipients
    over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
    or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/forward_spam
  tags: Email,Mail, Settings, Forward, Spam
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/sendgrid/mail-settingsforward-spam-patch-openapi.md
- name: SendGrid
  x-api-slug: sendgrid
  description: SendGrids cloud-based email infrastructure relieves businesses of the
    cost and complexity of maintaining custom email systems. SendGrid provides reliable
    delivery, scalability and real-time analytics along with flexible APIs that make
    custom integration a breeze.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: Forward
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/sendgrid/openapi.md
x-common:
- type: x--net-library
  url: https://sendgrid.com/docs/Code_Examples/csharp.html
- type: x-base
  url: https://api.sendgrid.com
- type: x-blog
  url: http://blog.sendgrid.com/
- type: x-blog-rss
  url: http://feeds.feedburner.com/sendgrid/CDXr
- type: x-contact-form
  url: https://sendgrid.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/sendgrid
- type: x-crunchbase
  url: https://crunchbase.com/organization/sendgrid
- type: x-developer
  url: https://sendgrid.com/developers
- type: x-documentation
  url: https://sendgrid.com/docs/index.html
- type: x-email
  url: privacy@sendgrid.com
- type: x-email
  url: legal@sendgrid.com
- type: x-email
  url: dpo@sendgrid.com
- type: x-forum
  url: http://support.sendgrid.com/forums
- type: x-github
  url: https://github.com/sendgrid
- type: x-go-library
  url: https://sendgrid.com/docs/Code_Examples/go.html
- type: x-ios-library
  url: https://sendgrid.com/docs/Code_Examples/ios.html
- type: x-java-library
  url: https://sendgrid.com/docs/Code_Examples/java.html
- type: x-labs
  url: http://labs.sendgrid.com/
- type: x-node-js-library
  url: https://sendgrid.com/docs/Code_Examples/nodejs.html
- type: x-partners
  url: https://sendgrid.com/partners
- type: x-perl-library
  url: https://sendgrid.com/docs/Code_Examples/perl.html
- type: x-php-library
  url: https://sendgrid.com/docs/Code_Examples/php.html
- type: x-pricing
  url: https://sendgrid.com/transactional-email/pricing
- type: x-privacy
  url: https://sendgrid.com/privacy
- type: x-python-library
  url: https://sendgrid.com/docs/Code_Examples/python.html
- type: x-ruby-library
  url: https://sendgrid.com/docs/Code_Examples/ruby.html
- type: x-security
  url: https://sendgrid.com/security
- type: x-selfservice-registration
  url: https://sendgrid.com/user/signup
- type: x-terms-of-service
  url: https://sendgrid.com/tos
- type: x-twitter
  url: https://twitter.com/SendGrid
- type: x-website
  url: http://sendgrid.com
- type: x-website
  url: https://sendgrid.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---