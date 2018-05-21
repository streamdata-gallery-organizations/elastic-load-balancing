{
  "info": {
    "name": "Elastic Load Balancing API Deletes the specified target group.",
    "_postman_id": "e50d7745-edbc-438d-82f3-09b9d0c7a843",
    "description": "Deletes the specified target group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "b00e0785-1599-4fdb-bfca-07c249898a08",
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
          "id": "6796f2c9-15be-4d81-bb89-8d61fedf573e"
        }
      ]
    },
    {
      "id": "60bfb113-1076-4de7-a4c7-80f2e0fa156d",
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
          "id": "b1945edb-5473-4a5f-83ac-0375f823b8ae"
        }
      ]
    },
    {
      "id": "d9b76552-a61e-4e9d-81a0-6527fef19fd6",
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
          "id": "b99b7bcc-5a09-4c45-b383-cc50c38e6772"
        }
      ]
    },
    {
      "id": "9b85dc93-36d8-4c8b-acaf-e22220f07995",
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
          "id": "360d694d-1b69-4aa7-a01f-b8f8b0f95b73"
        }
      ]
    },
    {
      "id": "9be9e5b5-3134-48c6-b4c8-263624e0195e",
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
          "id": "16023887-6c8f-4bea-92ae-7a2e95123e7a"
        }
      ]
    },
    {
      "id": "3edd359c-6eb4-49f7-b515-dbadfbb9ac0e",
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
          "id": "cad20d71-a625-41a6-b4dd-1ad499015a42"
        }
      ]
    },
    {
      "id": "98318344-7aa1-4554-a656-2331ee720eb6",
      "name": "DeleteLoadBalancer",
      "request": {
        "url": "http://example.com/api/?Action=DeleteLoadBalancer?LoadBalancerArn=LoadBalancerArn",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Deletes the specified Application Load Balancer and its attached listeners."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "936f5a94-173b-4b69-90f1-4d317503c2c3"
        }
      ]
    },
    {
      "id": "a8f73b6b-1b19-4e9e-bc04-130c097e58f0",
      "name": "DeleteRule",
      "request": {
        "url": "http://example.com/api/?Action=DeleteRule?RuleArn=RuleArn",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Deletes the specified rule."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "aedd673d-9a05-4ed7-90a0-8b8b89eb47e0"
        }
      ]
    },
    {
      "id": "f7ebb934-8cd0-45cc-a24b-b453cec98424",
      "name": "DeleteTargetGroup",
      "request": {
        "url": "http://example.com/api/?Action=DeleteTargetGroup?TargetGroupArn=TargetGroupArn",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Deletes the specified target group."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "aa109161-962f-41cb-a628-783e2b349b52"
        }
      ]
    }
  ]
}