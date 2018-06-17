{
  "info": {
    "name": "Crunch Base Acquistions",
    "_postman_id": "5a2cc7a9-e61f-4931-9786-60657f5ee068",
    "description": "Pull from Acquisition",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Acquisitions",
      "item": [
        {
          "id": "d34f74fe-18d5-4be4-939d-562381e2e0c2",
          "name": "acquistions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.crunchbase.com",
              "path": [
                "v",
                "3",
                "acquisitions/:uuid"
              ],
              "query": [
                {
                  "key": "user_key",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "uuid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Pull from Acquisition"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "377845ec-b9c0-425c-9e0e-609eeb9759c0"
            }
          ]
        }
      ]
    }
  ]
}