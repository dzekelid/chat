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
  /site/{cloudId}/conversation/{conversationId}/message/{messageId}/context:
    get:
      summary: Get conversation history contextually
      description: |-
        Authentication required, with scope participate:conversation

        This method returns messages after and/or before a given messageID including the message itself
      operationId: SiteConversationMessageMessageIdContextByCloudIdAndConversationIdGet
      parameters:
      - in: header
        name: Accept
      - in: query
        name: after
      - in: query
        name: before
      - in: path
        name: cloudId
      - in: header
        name: Content-Type
      - in: path
        name: conversationId
      - in: path
        name: messageId
      responses:
        200:
          description: OK
      tags:
      - messaging
      - site
      - cloud
      - conversation
      - conversation
      - message
      - message
      - context
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