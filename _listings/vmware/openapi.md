---
swagger: "2.0"
x-collection-name: VMWare
x-complete: 1
info:
  title: vRealize Operations 6
  description: todo-add-description
  version: 1.0.0
host: example.com
basePath: /suite-api/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/auth/token/acquire:
    post:
      summary: RUN FIRST - Get vR Ops Auth Token
      description: 'TODO: Add Description'
      operationId: ApiAuthTokenAcquirePost
      x-api-path-slug: apiauthtokenacquire-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Auth
      - Token
      - Acquire
---