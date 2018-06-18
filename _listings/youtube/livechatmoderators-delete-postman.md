{
  "info": {
    "name": "Youtube Delete Live Chat Moderators",
    "_postman_id": "0a8008ab-79e5-4989-9a99-e4b95436bcfd",
    "description": "Delete livechat moderators",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "chat",
      "item": [
        {
          "id": "1cf1a293-d7aa-4f05-a70e-12e2c78b40e4",
          "name": "deleteLivechatModerators",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/liveChat/moderators?id=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete livechat moderators"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9eb61c24-d429-463e-85ab-197fb6caef21"
            }
          ]
        }
      ]
    }
  ]
}