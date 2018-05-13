{
  "info": {
    "name": "Youtube Get Live Chat Messages",
    "_postman_id": "657e5e20-0e30-46a7-84db-86e38c0e817e",
    "description": "Lists live chat messages for a specific chat.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "chat",
      "item": [
        {
          "id": "557ca630-7cca-441f-82e1-e105b9b645b0",
          "name": "getLivechatMessages",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/liveChat/messages?hl=%7B%7D&liveChatId=%7B%7D&maxResults=%7B%7D&pageToken=%7B%7D&part=%7B%7D&profileImageSize=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists live chat messages for a specific chat"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be344542-548f-423e-a018-14826b82c5c3"
            }
          ]
        }
      ]
    }
  ]
}