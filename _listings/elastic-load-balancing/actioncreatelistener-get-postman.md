{
  "info": {
    "name": "Elastic Load Balancing API Creates a listener for the specified Application Load Balancer.",
    "_postman_id": "f55d9d79-8e53-46ad-957f-5e9eff0d21d4",
    "description": "Creates a listener for the specified Application Load Balancer.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "ed6cd2ca-c6b4-4fe2-a0f4-688289b40d12",
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
          "id": "baed42fe-b692-4933-92b9-df520d0c418b"
        }
      ]
    },
    {
      "id": "08ac4b64-1b87-42c9-9b98-a5d46f321156",
      "name": "CreateListener",
      "request": {
        "url": "http://example.com/api/?Action=CreateListener?Certificates.member.N=Certificates.member.N&DefaultActions.member.N=DefaultActions.member.N&LoadBalancerArn=LoadBalancerArn&Port=Port&Protocol=Protocol&SslPolicy=SslPolicy",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Creates a listener for the specified Application Load Balancer."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "053e86b6-243b-4e74-aba8-c72c355db3eb"
        }
      ]
    }
  ]
}