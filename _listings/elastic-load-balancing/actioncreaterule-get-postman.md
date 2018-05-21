{
  "info": {
    "name": "Elastic Load Balancing API Creates a rule for the specified listener.",
    "_postman_id": "f5bbf5e0-f4a3-4360-b945-8a213bdb8f6f",
    "description": "Creates a rule for the specified listener.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "48e31b4a-9072-4a46-b0b9-90db5bede9a0",
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
          "id": "48ea2b8b-83fb-4410-9eee-980cdc54e237"
        }
      ]
    },
    {
      "id": "1b2603f6-8910-45e2-8fb6-9872f9b93948",
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
          "id": "0978de5e-24e5-493b-953a-bba6d8a812fc"
        }
      ]
    },
    {
      "id": "c9a69fc5-2d84-4170-91b4-ce85a77febdf",
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
          "id": "032c3d7e-e39e-43c9-b96d-d0a75c1a1765"
        }
      ]
    },
    {
      "id": "228e75b3-fd51-4832-8f99-7dc61c533252",
      "name": "CreateRule",
      "request": {
        "url": "http://example.com/api/?Action=CreateRule?Actions.member.N=Actions.member.N&Conditions.member.N=Conditions.member.N&ListenerArn=ListenerArn&Priority=Priority",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Creates a rule for the specified listener."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "b7eff76c-11eb-47a5-ad2a-91dfa7da734b"
        }
      ]
    }
  ]
}