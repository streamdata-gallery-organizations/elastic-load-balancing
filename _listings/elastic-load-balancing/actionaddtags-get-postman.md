{
  "info": {
    "name": "Elastic Load Balancing API Adds the specified tags to the specified resource.",
    "_postman_id": "5ebb9114-c075-4194-b9a9-6206443f663a",
    "description": "Adds the specified tags to the specified resource.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "7eba06f2-3ed0-43c1-b5ba-07a8d5d3a729",
      "name": "AddTags",
      "request": {
        "url": "http://example.com/api/?Action=AddTags?ResourceArns.member.N=ResourceArns.member.N&Tags.member.N=Tags.member.N",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Adds the specified tags to the specified resource."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "f19e2c54-3377-4881-9938-a72734a004fa"
        }
      ]
    }
  ]
}