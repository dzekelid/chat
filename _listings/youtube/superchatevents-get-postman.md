{
  "info": {
    "name": "Youtube Get Superchatevents",
    "_postman_id": "73b519a4-37d7-4977-b8e5-c803d356af78",
    "description": "Lists Super Chat events for a channel.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "chat",
      "item": [
        {
          "id": "7be6b28a-a0aa-446e-b9dd-12926bc4620c",
          "name": "getSuperchatevents",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/superChatEvents?hl=%7B%7D&maxResults=%7B%7D&pageToken=%7B%7D&part=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists Super Chat events for a channel"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "16f5dc79-4051-4c8d-9d2f-c1c971b968ac"
            }
          ]
        }
      ]
    }
  ]
}