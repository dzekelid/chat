{
  "info": {
    "name": "Youtube Get Live Chat Moderators",
    "_postman_id": "0a748e13-159d-439d-808c-57a524ac174b",
    "description": "Lists moderators for a live chat.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "chat",
      "item": [
        {
          "id": "bdea7bb0-f810-4dc7-b78c-e24b797e57cc",
          "name": "getLivechatModerators",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/liveChat/moderators?liveChatId=%7B%7D&maxResults=%7B%7D&pageToken=%7B%7D&part=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists moderators for a live chat"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0b650296-4c6e-43e5-af40-4ef6681e3664"
            }
          ]
        }
      ]
    }
  ]
}