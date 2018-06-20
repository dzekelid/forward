---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Forward
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph Message Create Forward
  x-api-slug: microsoft-graph
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/createForward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/memessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/memessagesidcreateforward-post-openapi.md
- name: Microsoft Graph Message Create Forward
  x-api-slug: microsoft-graph
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/createForward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreateforward-post-openapi.md
- name: Microsoft Graph Message Create Forward
  x-api-slug: microsoft-graph
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/createForward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/memailfoldersidmessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/memailfoldersidmessagesidcreateforward-post-openapi.md
- name: Microsoft Graph Message Create Forward
  x-api-slug: microsoft-graph
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/createForward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post-openapi.md
- name: Microsoft Graph Message Forward
  x-api-slug: microsoft-graph
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/forward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/memessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/memessagesidforward-post-openapi.md
- name: Microsoft Graph Message Forward
  x-api-slug: microsoft-graph
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/forward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidforward-post-openapi.md
- name: Microsoft Graph Message Forward
  x-api-slug: microsoft-graph
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/forward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/memailfoldersidmessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/memailfoldersidmessagesidforward-post-openapi.md
- name: Microsoft Graph Message Forward
  x-api-slug: microsoft-graph
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/forward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidforward-post-openapi.md
- name: Microsoft Graph Post Forward
  x-api-slug: microsoft-graph
  description: 'post: forward Forward a post to a recipient. You can specify both
    the parent conversation and thread in the request, or, you can specify just the
    parent thread without the parent conversation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/threads/{id}/posts/{id}/forward
  tags: Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/groupsidthreadsidpostsidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/groupsidthreadsidpostsidforward-post-openapi.md
- name: Microsoft Graph Post Forward
  x-api-slug: microsoft-graph
  description: 'post: forward Forward a post to a recipient. You can specify both
    the parent conversation and thread in the request, or, you can specify just the
    parent thread without the parent conversation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/conversations/{id}/threads/{id}/posts/{id}/forward
  tags: Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsidforward-post-openapi.md
- name: Microsoft Graph
  x-api-slug: microsoft-graph
  description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
    cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
    Graph simplifies queries that would otherwise be more complex. You can use Microsoft
    Graph to: Access data from multiple Microsoft cloud services, including Azure
    Active Directory, Exchange Online as part of Office 365, SharePoint, OneDrive,
    OneNote, and Planner. Navigate between entities and relationships. Access intelligence
    and insights from the Microsoft cloud (for commercial users).'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Forward
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/forward/master/_listings/microsoft-graph/openapi.md
x-common:
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---