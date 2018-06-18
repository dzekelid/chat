---
swagger: "2.0"
x-collection-name: YouTube
x-complete: 0
info:
  title: Youtube Delete Live Chat Messages
  description: Delete livechat messages
  termsOfService: https://developers.google.com/terms/
  contact:
    name: Google
    url: https://google.com
  version: 1.0.0
host: www.googleapis.com
basePath: /youtube/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /liveChat/bans:
    delete:
      summary: Delete Live Chat Bans
      description: Delete livechat bans
      operationId: deleteLivechatBans
      x-api-path-slug: livechatbans-delete
      parameters:
      - in: query
        name: id
        description: The id parameter identifies the chat ban to remove
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Bans
    post:
      summary: Add Live Chat Bans
      description: Adds a new ban to the chat.
      operationId: postLivechatBans
      x-api-path-slug: livechatbans-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: part
        description: The part parameter serves two purposes in this operation
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Bans
  /liveChat/messages:
    delete:
      summary: Delete Live Chat Messages
      description: Delete livechat messages
      operationId: deleteLivechatMessages
      x-api-path-slug: livechatmessages-delete
      parameters:
      - in: query
        name: id
        description: The id parameter specifies the YouTube chat message ID of the
          resource that is being deleted
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Messages
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