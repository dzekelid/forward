---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/operations/ForwardWithdrawal:
    post:
      summary: Add API Operations Forwardwithdrawal
      description: Add api operations forwardwithdrawal.
      operationId: ApiOperationsForwardWithdrawalPost
      x-api-path-slug: apioperationsforwardwithdrawal-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: data
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Operations
      - Forwardwithdrawal
  /api/offchain/cashout/forward:
    post:
      summary: Add API Offchain Cashout Forward
      description: Add api offchain cashout forward.
      operationId: ApiOffchainCashoutForwardPost
      x-api-path-slug: apioffchaincashoutforward-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Offchain
      - Cashout
      - Forward
---