---
swagger: "2.0"
info:
  title: Stride
  description: This service provides public API for the Stride.
  version: 1.0.0
host: api.atlassian.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /site/{cloudId}/conversation/user/{userId}/message:
    post:
      summary: Send message to user
      description: Authentication required, with scope participate:conversation
      operationId: SiteConversationUserMessageByCloudIdAndUserIdPost
      parameters:
      - in: header
        name: Accept
      - in: path
        name: cloudId
      - in: header
        name: Content-Type
      - in: path
        name: userId
      responses:
        200:
          description: OK
      tags:
      - messaging
      - site
      - cloud
      - conversation
      - user
      - user
      - message
definitions: []
x-collection-name: Stride
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