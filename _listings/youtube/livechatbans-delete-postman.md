{
  "info": {
    "name": "Youtube Delete Live Chat Bans",
    "_postman_id": "f0e1de2f-a494-4843-9319-742738317ad9",
    "description": "Delete livechat bans",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "chat",
      "item": [
        {
          "id": "15f38cc9-31dd-4ea0-a528-33a04f576b88",
          "name": "deleteLivechatBans",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/liveChat/bans?id=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete livechat bans"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "162ffcdb-e0cc-4832-89e1-1a4723d66af0"
            }
          ]
        }
      ]
    }
  ]
}