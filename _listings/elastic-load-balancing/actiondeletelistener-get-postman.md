{
  "info": {
    "name": "Elastic Load Balancing API Deletes the specified listener.",
    "_postman_id": "8a23686a-ecf8-40ef-8b11-30a4361e1900",
    "description": "Deletes the specified listener.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "d1370c53-a424-4dc9-a1db-62b28a41d238",
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
          "id": "a434f15f-a044-4f37-9f06-138f24658b92"
        }
      ]
    },
    {
      "id": "d9f433e2-688d-402f-9969-e1c92130bddf",
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
          "id": "e5ddc2d1-2582-49cd-903c-1102c4b50a39"
        }
      ]
    },
    {
      "id": "d74fc0be-c87f-4ec5-bd9f-d52b51e97284",
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
          "id": "2a90ac6c-74d8-4cce-854e-5f43a0a4c434"
        }
      ]
    },
    {
      "id": "3c193b3d-efb7-4f29-ad0a-19dc7737a520",
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
          "id": "d3826e79-d781-4468-bebc-6df577589548"
        }
      ]
    },
    {
      "id": "01f5b375-1a0c-4d7b-b0e0-72ab3d0c9fb4",
      "name": "CreateTargetGroup",
      "request": {
        "url": "http://example.com/api/?Action=CreateTargetGroup?HealthCheckIntervalSeconds=HealthCheckIntervalSeconds&HealthCheckPath=HealthCheckPath&HealthCheckPort=HealthCheckPort&HealthCheckProtocol=HealthCheckProtocol&HealthCheckTimeoutSeconds=HealthCheckTimeoutSeconds&HealthyThresholdCount=HealthyThresholdCount&Matcher=Matcher&Name=Name&Port=Port&Protocol=Protocol&UnhealthyThresholdCount=UnhealthyThresholdCount&VpcId=VpcId",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Creates a target group."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "16078de2-ccb6-4ac6-9713-0a7f489bc906"
        }
      ]
    },
    {
      "id": "66183614-d5d9-40c6-8a7c-33a6fbdf7e45",
      "name": "DeleteListener",
      "request": {
        "url": "http://example.com/api/?Action=DeleteListener?ListenerArn=ListenerArn",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Deletes the specified listener."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "4510a648-fbf1-45da-8fec-a729a3d64180"
        }
      ]
    }
  ]
}