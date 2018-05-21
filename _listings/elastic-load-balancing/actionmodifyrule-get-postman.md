{
  "info": {
    "name": "Elastic Load Balancing API Modifies the specified rule.",
    "_postman_id": "408c6955-1397-4f95-82b6-808d23297262",
    "description": "Modifies the specified rule.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "b78093a3-c1fe-4214-a717-cd9c4e8db7cf",
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
          "id": "5fd99d87-ce82-4034-99b2-f08e049a932b"
        }
      ]
    },
    {
      "id": "cd4a92dc-d24e-461a-8fec-240e8fbbb5d0",
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
          "id": "055eac85-3d86-4792-9ed3-ec48bd953acd"
        }
      ]
    },
    {
      "id": "deb6bbd8-7a41-4d3f-bd01-155fa985ac09",
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
          "id": "789da9c4-f783-4844-965f-2cf0b84a9d54"
        }
      ]
    },
    {
      "id": "ff8c91fc-ae41-45bc-8451-7a0e0c0a5983",
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
          "id": "a16b3125-dd28-4110-95a1-1ef213067262"
        }
      ]
    },
    {
      "id": "caf81d3d-ec5c-44e8-b529-fb093f2689a2",
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
          "id": "a14a8432-8af3-4940-b903-63cbaf59a0fb"
        }
      ]
    },
    {
      "id": "ad85621c-9ca4-4fd5-9dd8-af1e144e6cc6",
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
          "id": "4c39bc00-8e4a-416a-ba5c-0b52573e7f68"
        }
      ]
    },
    {
      "id": "894d8473-9964-49fa-8158-5f3d1e2d8a0c",
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
          "id": "5e6d8212-989d-449f-a62b-2ac8d4aa4bfe"
        }
      ]
    },
    {
      "id": "c1e04fb8-8b5a-4fff-bc3a-b54960f04af8",
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
          "id": "af978983-9572-4931-afce-0a4aee25853c"
        }
      ]
    },
    {
      "id": "5d182ad4-dc7d-42a0-8d86-30e9ae2931eb",
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
          "id": "5aca7313-97df-4d09-8c4f-c23cff2ca35a"
        }
      ]
    },
    {
      "id": "a0b0394e-4c55-425b-b602-5776b4d05a95",
      "name": "DeregisterTargets",
      "request": {
        "url": "http://example.com/api/?Action=DeregisterTargets?TargetGroupArn=TargetGroupArn&Targets.member.N=Targets.member.N",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Deregisters the specified targets from the specified target group."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "1a71ffb8-e671-4ea0-a2f8-0ab0bf424ee6"
        }
      ]
    },
    {
      "id": "5a698ea8-2e6c-4ffe-a610-5d289314ffac",
      "name": "DescribeListeners",
      "request": {
        "url": "http://example.com/api/?Action=DescribeListeners?ListenerArns.member.N=ListenerArns.member.N&LoadBalancerArn=LoadBalancerArn&Marker=Marker&PageSize=PageSize",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Describes the specified listeners or the listeners for the specified Application Load Balancer."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "60b202e0-2413-4a99-94b0-0f4a5a96af1d"
        }
      ]
    },
    {
      "id": "5f1c10a7-59c1-4278-ba89-ac6c99cd0ea7",
      "name": "DescribeLoadBalancerAttributes",
      "request": {
        "url": "http://example.com/api/?Action=DescribeLoadBalancerAttributes?LoadBalancerArn=LoadBalancerArn",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Describes the attributes for the specified Application Load Balancer."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "15545186-c80d-4b24-b099-518985129f61"
        }
      ]
    },
    {
      "id": "fe244789-b421-4fea-bc04-da3134cdc37d",
      "name": "DescribeLoadBalancers",
      "request": {
        "url": "http://example.com/api/?Action=DescribeLoadBalancers?LoadBalancerArns.member.N=LoadBalancerArns.member.N&Marker=Marker&Names.member.N=Names.member.N&PageSize=PageSize",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Describes the specified Application Load Balancers or all of your Application Load Balancers."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "c230ef11-96b6-45d7-95f7-45b277762814"
        }
      ]
    },
    {
      "id": "c7ea644b-6852-4cf7-b67e-fd283d01d98d",
      "name": "DescribeRules",
      "request": {
        "url": "http://example.com/api/?Action=DescribeRules?ListenerArn=ListenerArn&RuleArns.member.N=RuleArns.member.N",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Describes the specified rules or the rules for the specified listener."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "53a25598-7043-4507-a42f-5d2e84d37baa"
        }
      ]
    },
    {
      "id": "dcd6a912-c1c9-46c5-b966-87dd5ba11374",
      "name": "DescribeSSLPolicies",
      "request": {
        "url": "http://example.com/api/?Action=DescribeSSLPolicies?Marker=Marker&Names.member.N=Names.member.N&PageSize=PageSize",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Describes the specified policies or all policies used for SSL negotiation."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "6e5320e8-0238-4f18-b254-253de5c7654c"
        }
      ]
    },
    {
      "id": "7d8a91c5-e019-4936-a157-327be6117367",
      "name": "DescribeTags",
      "request": {
        "url": "http://example.com/api/?Action=DescribeTags?ResourceArns.member.N=ResourceArns.member.N",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Describes the tags for the specified resources."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "20b012d2-03a7-406f-8777-6b4886f7b0f7"
        }
      ]
    },
    {
      "id": "0e4d1997-3f0d-4c6c-bddb-254cb0194a76",
      "name": "DescribeTargetGroupAttributes",
      "request": {
        "url": "http://example.com/api/?Action=DescribeTargetGroupAttributes?TargetGroupArn=TargetGroupArn",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Describes the attributes for the specified target group."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "b7cc5511-0e7f-462f-9079-20123e52b529"
        }
      ]
    },
    {
      "id": "2cc81a5a-81b1-4bc9-b141-e7106d0fb193",
      "name": "DescribeTargetGroups",
      "request": {
        "url": "http://example.com/api/?Action=DescribeTargetGroups?LoadBalancerArn=LoadBalancerArn&Marker=Marker&Names.member.N=Names.member.N&PageSize=PageSize&TargetGroupArns.member.N=TargetGroupArns.member.N",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Describes the specified target groups or all of your target groups."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "b0c60b85-a4db-47ba-a00e-f564c99ec8c4"
        }
      ]
    },
    {
      "id": "bed84546-b232-4bf2-b191-b7aa21a9e5a2",
      "name": "DescribeTargetHealth",
      "request": {
        "url": "http://example.com/api/?Action=DescribeTargetHealth?TargetGroupArn=TargetGroupArn&Targets.member.N=Targets.member.N",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Describes the health of the specified targets or all of your targets."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "6627daa2-dd9d-46b0-80f7-0b279e3fc479"
        }
      ]
    },
    {
      "id": "9b643567-e9e7-45d4-9a0d-f8a1f91193d1",
      "name": "ModifyListener",
      "request": {
        "url": "http://example.com/api/?Action=ModifyListener?Certificates.member.N=Certificates.member.N&DefaultActions.member.N=DefaultActions.member.N&ListenerArn=ListenerArn&Port=Port&Protocol=Protocol&SslPolicy=SslPolicy",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Modifies the specified properties of the specified listener."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "a6c610da-5f39-432a-bd8e-9baf59d4b120"
        }
      ]
    },
    {
      "id": "2642d953-3f9e-4fc2-9752-7ad9219750ce",
      "name": "ModifyLoadBalancerAttributes",
      "request": {
        "url": "http://example.com/api/?Action=ModifyLoadBalancerAttributes?Attributes.member.N=Attributes.member.N&LoadBalancerArn=LoadBalancerArn",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Modifies the specified attributes of the specified Application Load Balancer."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "b4d613ae-21c9-4a04-ac24-7b33a48a674a"
        }
      ]
    },
    {
      "id": "08c86226-1242-4c5d-b019-6e8d2a38270e",
      "name": "ModifyRule",
      "request": {
        "url": "http://example.com/api/?Action=ModifyRule?Actions.member.N=Actions.member.N&Conditions.member.N=Conditions.member.N&RuleArn=RuleArn",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Modifies the specified rule."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "c2e3ada1-036d-4085-8e5c-696b850e40ac"
        }
      ]
    }
  ]
}