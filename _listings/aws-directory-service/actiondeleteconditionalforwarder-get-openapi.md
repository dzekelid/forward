---
swagger: "2.0"
x-collection-name: AWS Directory Service
x-complete: 0
info:
  title: AWS Directory Service API Delete Conditional Forwarder
  version: 1.0.0
  description: Deletes a conditional forwarder that has been set up for your AWS directory.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateConditionalForwarder:
    get:
      summary: Create Conditional Forwarder
      description: Creates a conditional forwarder associated with your AWS directory.
      operationId: createConditionalForwarder
      x-api-path-slug: actioncreateconditionalforwarder-get
      parameters:
      - in: query
        name: DirectoryId
        description: The directory ID of the AWS directory for which you are creating
          the conditional forwarder
        type: string
      - in: query
        name: DnsIpAddrs
        description: The IP addresses of the remote DNS server associated with RemoteDomainName
        type: string
      - in: query
        name: RemoteDomainName
        description: The fully qualified domain name (FQDN) of the remote domain with
          which you will set up a trust relationship
        type: string
      responses:
        200:
          description: OK
      tags:
      - Conditional Forwarder
  /?Action=DeleteConditionalForwarder:
    get:
      summary: Delete Conditional Forwarder
      description: Deletes a conditional forwarder that has been set up for your AWS
        directory.
      operationId: deleteConditionalForwarder
      x-api-path-slug: actiondeleteconditionalforwarder-get
      parameters:
      - in: query
        name: DirectoryId
        description: The directory ID for which you are deleting the conditional forwarder
        type: string
      - in: query
        name: RemoteDomainName
        description: The fully qualified domain name (FQDN) of the remote domain with
          which you are deleting the conditional forwarder
        type: string
      responses:
        200:
          description: OK
      tags:
      - Conditional Forwarder
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