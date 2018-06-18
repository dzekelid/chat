{
  "info": {
    "name": "Youtube Delete Live Chat Messages",
    "_postman_id": "97812dc8-09e1-479a-a47b-8fce25fb1038",
    "description": "Delete livechat messages",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "chat",
      "item": [
        {
          "id": "24e729bb-0852-4927-971c-7a46ae5d869c",
          "name": "deleteLivechatMessages",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/liveChat/messages?id=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete livechat messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5df810db-7c52-43a4-882d-3ac98836f60a"
            }
          ]
        }
      ]
    }
  ]
}