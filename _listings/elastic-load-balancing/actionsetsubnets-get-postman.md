{
  "info": {
    "name": "Elastic Load Balancing API Enables the Availability Zone for the specified subnets for the specified load balancer.",
    "_postman_id": "d9e8e948-14af-4c65-8067-94750c327707",
    "description": "Enables the Availability Zone for the specified subnets for the specified load balancer.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "ff3b576a-4462-44ba-9b62-b6dabff45139",
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
          "id": "994c501a-f2d5-428b-b15d-9be17cc0be27"
        }
      ]
    },
    {
      "id": "e0652813-8bcc-4c44-a351-3746cb7545fe",
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
          "id": "eced136b-9074-41d7-ba41-1b5b2959c893"
        }
      ]
    },
    {
      "id": "d754884a-c1ef-46d3-819c-22b49a1488c6",
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
          "id": "027aa47f-4786-4444-9b39-b0715f12d38c"
        }
      ]
    },
    {
      "id": "896d65f7-e8ff-466c-8d7a-eac9034453f8",
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
          "id": "8361c5bb-e7c4-4df3-8fd5-88b0738d16d4"
        }
      ]
    },
    {
      "id": "3473b68b-5982-4254-810e-c497863cb1b8",
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
          "id": "1a3a0b87-8d93-4044-a363-dab0ece09973"
        }
      ]
    },
    {
      "id": "5e17ca85-36c8-402e-a9a3-ca931c6d63c4",
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
          "id": "040f23a3-88db-4db8-8f5c-c89e8bca5f55"
        }
      ]
    },
    {
      "id": "3784a417-c968-457c-ab50-b357604a6966",
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
          "id": "b8e6c436-742a-4ab9-ab8d-6e22bfb7b419"
        }
      ]
    },
    {
      "id": "f6412988-c0e2-471a-8b31-201a512a2647",
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
          "id": "c1bb6642-bbfc-4caf-8d39-bc22a3da2062"
        }
      ]
    },
    {
      "id": "87e947a8-746b-4eaa-b2e9-0f0720fed898",
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
          "id": "f26fcd75-8531-431f-a79f-74f802579bf2"
        }
      ]
    },
    {
      "id": "0df07aa4-d5ba-4d24-8266-89bfd72dd4a2",
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
          "id": "6f6c0b90-b0a8-409e-81be-d49f716195d5"
        }
      ]
    },
    {
      "id": "253f6cce-a795-46cd-89b1-ee41852fe843",
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
          "id": "d6c5652c-08c8-4e49-9545-ab3eb7cfbdb7"
        }
      ]
    },
    {
      "id": "86168081-1d52-40eb-8965-4f0537daf8bf",
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
          "id": "960408e9-26bf-46ed-8be3-8fefde68108f"
        }
      ]
    },
    {
      "id": "0554f10d-3aaa-4ca5-9476-2d08dd918433",
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
          "id": "da7cb039-2a9b-4cd0-8481-d4c99a5cf83a"
        }
      ]
    },
    {
      "id": "ca9c0f86-32b2-410b-ab41-92ca3511ebc8",
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
          "id": "01736c4c-ec17-4e51-b440-89b6aaaab24e"
        }
      ]
    },
    {
      "id": "634b2222-0004-437c-91f8-fb72d36f5aac",
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
          "id": "282173fc-228a-449f-ad64-0201f0509ffc"
        }
      ]
    },
    {
      "id": "843fd31a-b3cd-46d8-952f-68757bca9748",
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
          "id": "0510663c-25e8-4bad-b959-901e9dbd8834"
        }
      ]
    },
    {
      "id": "6cd6699f-861b-4f46-84bd-4379fb8f517d",
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
          "id": "40189aff-a89c-420d-803c-4a98eee9008e"
        }
      ]
    },
    {
      "id": "b7042210-8937-48f3-b6aa-e0dd2199e974",
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
          "id": "d7443a72-481d-4f7d-95db-f8e8c88619b7"
        }
      ]
    },
    {
      "id": "eb556ba1-7778-4321-b27e-5318294b746e",
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
          "id": "dc110840-41c7-414b-9bd6-03d92eca48da"
        }
      ]
    },
    {
      "id": "c9669596-220b-479f-a6bc-17113cb76b9b",
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
          "id": "461fcea3-78cf-4eb9-95a6-197bd15a9e49"
        }
      ]
    },
    {
      "id": "bbc23452-fa96-4385-ae69-ecbf96508472",
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
          "id": "6704c682-4815-40cd-a2b6-6105a461b7ec"
        }
      ]
    },
    {
      "id": "1641b96d-ca82-455f-9849-7ac7b3480ba3",
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
          "id": "d05018a2-07d9-45ad-ac14-c2171b48a003"
        }
      ]
    },
    {
      "id": "e3af765e-9047-41d5-8a56-6b0e1a119f54",
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
          "id": "757ca498-0947-4526-8038-dd2f6657c5c5"
        }
      ]
    },
    {
      "id": "9f86292c-e715-4f6b-a73e-a29830b617c4",
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
          "id": "34a4bd63-09ce-4e58-8bce-41d76948aba1"
        }
      ]
    },
    {
      "id": "54cacdde-bb4e-4e2a-9cba-d9d14de567b0",
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
          "id": "ac3a8bec-dee6-4062-bd56-a0540cd31107"
        }
      ]
    },
    {
      "id": "efaedd5f-0ac8-491a-9281-81462b23506c",
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
          "id": "63f5f900-4621-42c8-a499-8b280e2381ba"
        }
      ]
    },
    {
      "id": "73209763-74f4-403f-bd77-e339db8c3c90",
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
          "id": "5bb2bd28-ee72-43fc-90b8-8fbbb3b49191"
        }
      ]
    },
    {
      "id": "91573b46-5623-4046-bbf2-780b914ff82b",
      "name": "SetSecurityGroups",
      "request": {
        "url": "http://example.com/api/?Action=SetSecurityGroups?LoadBalancerArn=LoadBalancerArn&SecurityGroups.member.N=SecurityGroups.member.N",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Associates the specified security groups with the specified load balancer."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "e6003dc1-5ef9-4dbe-9c1a-860b5f1a569c"
        }
      ]
    },
    {
      "id": "bd55d387-2d02-4ca0-8ae0-fdf67383806f",
      "name": "SetSubnets",
      "request": {
        "url": "http://example.com/api/?Action=SetSubnets?LoadBalancerArn=LoadBalancerArn&Subnets.member.N=Subnets.member.N",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Enables the Availability Zone for the specified subnets for the specified load balancer."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "00cbda32-328d-43f4-90dc-5dcee9cd01c1"
        }
      ]
    }
  ]
}