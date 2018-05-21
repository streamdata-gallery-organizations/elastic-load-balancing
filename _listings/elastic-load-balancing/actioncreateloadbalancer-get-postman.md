{
  "info": {
    "name": "Elastic Load Balancing API Creates an Application Load Balancer.",
    "_postman_id": "5226336f-8247-40f9-a0d0-f0014203e48a",
    "description": "Creates an Application Load Balancer.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "d09f5ce6-45f6-4e88-b448-2e44a29ee1ed",
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
          "id": "6db9fb9b-8e5f-4b06-9641-0f9a090061cf"
        }
      ]
    },
    {
      "id": "855212eb-109e-4fd1-a649-5dc88183fe7a",
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
          "id": "fd56bc10-8209-43f7-adb3-5943a5a100ad"
        }
      ]
    },
    {
      "id": "d9377154-8157-49d5-ad4a-fc21dd9375a0",
      "name": "CreateLoadBalancer",
      "request": {
        "url": "http://example.com/api/?Action=CreateLoadBalancer?Name=Name&Scheme=Scheme&SecurityGroups.member.N=SecurityGroups.member.N&Subnets.member.N=Subnets.member.N&Tags.member.N=Tags.member.N",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Creates an Application Load Balancer."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "bc6896e8-bf07-49c2-b886-5d7a6ff9e2ea"
        }
      ]
    }
  ]
}