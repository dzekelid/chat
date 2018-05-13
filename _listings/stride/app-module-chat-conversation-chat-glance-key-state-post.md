---
swagger: "2.0"
info:
  title: Stride Send glance updates
  description: |-
    Post glance updates which will be pushed for all users within the specified context.

    Authentication required.
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
  /app/module/chat/conversation/chat:glance/{key}/state:
    post:
      summary: Send glance updates
      description: Post glance updates which will be pushed for all users within the
        specified context
      operationId: AppModuleChatConversationChatGlanceStateByKeyPost
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: key
      responses:
        200:
          description: OK
      tags:
      - messaging
      - app
      - module
      - chat
      - conversation
      - chat
      - glance
      - key
      - state
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