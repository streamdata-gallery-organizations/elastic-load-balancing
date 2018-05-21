{
  "info": {
    "name": "Elastic Load Balancing API Sets the priorities of the specified rules.",
    "_postman_id": "33bf9ecc-85ac-4065-af03-1725d755e79e",
    "description": "Sets the priorities of the specified rules.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "8becd9d2-c24f-42c2-b957-6e77b100fa62",
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
          "id": "303e3de4-0f78-4865-8c87-2349af830824"
        }
      ]
    },
    {
      "id": "4a1cb054-3aaa-4c9c-95b4-3f1f6f70da41",
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
          "id": "440d672c-8d22-46a9-98eb-a36c4a70fd09"
        }
      ]
    },
    {
      "id": "9c8cbbe3-7939-4ab9-956f-44060e1e5922",
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
          "id": "7e6cffe7-c92e-4d53-9c62-468ade88b468"
        }
      ]
    },
    {
      "id": "aa6f9fc6-dfec-4c08-bebd-a9e47702459a",
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
          "id": "42b65e08-b096-4ccc-9f61-af8a1a331505"
        }
      ]
    },
    {
      "id": "643f2c01-3be1-4dbf-9f85-f2bf09fc1b8c",
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
          "id": "ed99e4bc-2244-4aef-a869-4ec6ae5e3878"
        }
      ]
    },
    {
      "id": "1cb16344-45b3-47de-8477-78af2b7f2865",
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
          "id": "eba35bce-7fd5-4c1c-a7a3-ca50d5d34f47"
        }
      ]
    },
    {
      "id": "6211c73a-98cf-495a-824a-11904dc5c247",
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
          "id": "16dc4306-dd74-457b-aa07-ef67c3b21cff"
        }
      ]
    },
    {
      "id": "aa137ca7-0d53-423b-b3ec-62c62056effb",
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
          "id": "44f18bfd-7e16-4ea0-95c5-e1994494c12a"
        }
      ]
    },
    {
      "id": "00e31441-f3f6-4e33-8983-dc06c20c79f2",
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
          "id": "8d489fd5-3dca-419f-a89d-f7a8111b228e"
        }
      ]
    },
    {
      "id": "0befc020-6f29-4cde-a12a-fe11a5ee63da",
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
          "id": "8be43fda-cf9d-496f-b5ce-078b768e11ec"
        }
      ]
    },
    {
      "id": "ee7e1e5a-1f2c-4d9c-8255-307b1d204a1a",
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
          "id": "17b08895-3a4a-4998-8ae1-123038158b8d"
        }
      ]
    },
    {
      "id": "254592d9-7e32-4fb7-9e41-1b9d666d8aff",
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
          "id": "cb481d44-aa33-44e5-8fd3-a54645347442"
        }
      ]
    },
    {
      "id": "9dc0f3e2-de86-4543-974f-11baa6cde541",
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
          "id": "4aafe66f-140d-4101-a4cf-9fbbe2d6d782"
        }
      ]
    },
    {
      "id": "7c8044ee-f6a2-4952-bb84-94b6c1de87bd",
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
          "id": "72d65233-b92e-4fc8-a5fe-e267c1309bf9"
        }
      ]
    },
    {
      "id": "45f56c36-74d2-4622-8667-b28bd604d72a",
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
          "id": "4515824b-bb9b-4140-83e1-14f7a36dc22a"
        }
      ]
    },
    {
      "id": "0761a90f-f0b3-446f-b1be-5f6c5ea9dd0a",
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
          "id": "f1690933-9c55-4747-a526-b292de6cdecd"
        }
      ]
    },
    {
      "id": "75e970a8-af1b-4a01-bf71-e82da02fc68a",
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
          "id": "bfe6c624-2bcd-4fa2-a53f-5856607a1cd5"
        }
      ]
    },
    {
      "id": "8bee8ad3-ef20-4cb5-b226-055658df10c5",
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
          "id": "f7d20ac7-124c-4ad0-8c65-84f335af7e25"
        }
      ]
    },
    {
      "id": "189cc5e7-3d7e-44fb-9c84-0e437c7f593a",
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
          "id": "02ce0ea0-1871-4d0f-aff9-48d238f4e28e"
        }
      ]
    },
    {
      "id": "185e8ecc-09fd-406b-af35-b72b649deb70",
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
          "id": "aa6fbce5-ea75-4333-853e-e082f46d3770"
        }
      ]
    },
    {
      "id": "45ac0f24-714d-4e53-95af-9db9f9f9dace",
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
          "id": "a92bc938-68d3-4434-93d7-e73785afd663"
        }
      ]
    },
    {
      "id": "113246d6-59fa-4648-a0ba-b74d273ec554",
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
          "id": "a1cff6dd-f32f-45ed-8c09-da3bd6e52ff3"
        }
      ]
    },
    {
      "id": "73753ad9-f847-41fa-bcb8-2b56c8df4005",
      "name": "ModifyTargetGroup",
      "request": {
        "url": "http://example.com/api/?Action=ModifyTargetGroup?HealthCheckIntervalSeconds=HealthCheckIntervalSeconds&HealthCheckPath=HealthCheckPath&HealthCheckPort=HealthCheckPort&HealthCheckProtocol=HealthCheckProtocol&HealthCheckTimeoutSeconds=HealthCheckTimeoutSeconds&HealthyThresholdCount=HealthyThresholdCount&Matcher=Matcher&TargetGroupArn=TargetGroupArn&UnhealthyThresholdCount=UnhealthyThresholdCount",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Modifies the health checks used when evaluating the health state of the targets in the specified target group."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "a6f5db4c-b4f4-419c-82fc-8f97c6046790"
        }
      ]
    },
    {
      "id": "d1d08ffb-b074-4ca6-95b1-466a84af3a8f",
      "name": "ModifyTargetGroupAttributes",
      "request": {
        "url": "http://example.com/api/?Action=ModifyTargetGroupAttributes?Attributes.member.N=Attributes.member.N&TargetGroupArn=TargetGroupArn",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Modifies the specified attributes of the specified target group."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "91fe1f54-030f-4c7b-b9c6-0580bea5f228"
        }
      ]
    },
    {
      "id": "efe548b9-45fc-4877-99e2-35e4b5455b27",
      "name": "RegisterTargets",
      "request": {
        "url": "http://example.com/api/?Action=RegisterTargets?TargetGroupArn=TargetGroupArn&Targets.member.N=Targets.member.N",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Registers the specified targets with the specified target group."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "0cd325cd-96ab-487c-b7f0-bb4122e78b29"
        }
      ]
    },
    {
      "id": "d5a7f9aa-ccd8-449e-bd61-a512b3855534",
      "name": "RemoveTags",
      "request": {
        "url": "http://example.com/api/?Action=RemoveTags?ResourceArns.member.N=ResourceArns.member.N&TagKeys.member.N=TagKeys.member.N",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Removes the specified tags from the specified resource."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "0b2202da-94f0-4ee7-955e-f39bf8d53cab"
        }
      ]
    },
    {
      "id": "e3b51ba2-c874-4aa4-ba16-4b1b1983038c",
      "name": "SetRulePriorities",
      "request": {
        "url": "http://example.com/api/?Action=SetRulePriorities?RulePriorities.member.N=RulePriorities.member.N",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Sets the priorities of the specified rules."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "530060b0-1fa2-4875-898f-56f9a845b2eb"
        }
      ]
    }
  ]
}