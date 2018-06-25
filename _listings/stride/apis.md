---
name: Stride
x-slug: stride
description: Stride is a cloud-based team business communication and collaboration
  tool, launched by Atlassian to replace the cloud-based version of HipChat. Stride
  software is available to download onto computers running Windows, Mac or Linux,
  as well as Android, iOS smartphones, and tablets
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
x-kinRank: "8"
x-alexaRank: "40723"
tags: Chat
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/chat/master/_listings/stride/apis.md
specificationVersion: "0.14"
apis:
- name: Stride Send app configuration updates
  x-api-slug: stride
  description: |-
    Post app configuration updates telling the.

    Authentication required.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////app/module/chat/conversation/chat:configuration/{key}/state
  tags: Messaging,App, Module, Chat, Conversation, Chat, Configuration, Key, State
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/chat/master/_listings/stride/appmodulechatconversationchatconfigurationkeystate-post-openapi.md
- name: Stride Send glance updates
  x-api-slug: stride
  description: |-
    Post glance updates which will be pushed for all users within the specified context.

    Authentication required.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////app/module/chat/conversation/chat:glance/{key}/state
  tags: Messaging,App, Module, Chat, Conversation, Chat, Glance, Key, State
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/chat/master/_listings/stride/appmodulechatconversationchatglancekeystate-post-openapi.md
- name: Stride
  x-api-slug: stride
  description: Stride is a cloud-based team business communication and collaboration
    tool, launched by Atlassian to replace the cloud-based version of HipChat. Stride
    software is available to download onto computers running Windows, Mac or Linux,
    as well as Android, iOS smartphones, and tablets
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28142-stride.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Chat
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/chat/master/_listings/stride/openapi.md
x-common:
- type: x-authentication
  url: https://developer.atlassian.com/cloud/stride/security/authentication/
- type: x-blog
  url: https://blog.stride.com/
- type: x-buttons
  url: https://developer.atlassian.com/cloud/stride/blocks/stride-button/
- type: x-crunchbase
  url: https://crunchbase.com/organization/stride
- type: x-developer
  url: https://developer.atlassian.com/cloud/stride/
- type: x-getting-started
  url: https://developer.atlassian.com/cloud/stride/getting-started/
- type: x-pricing
  url: https://www.stride.com/pricing
- type: x-security
  url: https://developer.atlassian.com/cloud/stride/security/security-overview/
- type: x-support
  url: https://www.stride.com/help-center
- type: x-twitter
  url: https://twitter.com/atlassianstride
- type: x-website
  url: https://www.stride.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---