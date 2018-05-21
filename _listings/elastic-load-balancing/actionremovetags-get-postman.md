{
  "info": {
    "name": "Elastic Load Balancing API Removes the specified tags from the specified resource.",
    "_postman_id": "0709b04b-3532-4939-84fb-182803ca2018",
    "description": "Removes the specified tags from the specified resource.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "05843410-ca30-4618-ae41-b264a0cffc8c",
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
          "id": "617c4982-2469-449f-add9-ef45a8ce01a7"
        }
      ]
    },
    {
      "id": "beedc698-0144-4c1d-b0fa-9657f04a528c",
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
          "id": "bcd31f05-b60b-48d7-a2e0-0291ac03c62b"
        }
      ]
    },
    {
      "id": "6a436643-b7d0-4c79-9834-66e9072af9a6",
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
          "id": "137b6c5a-d1eb-48cf-9a5c-2114ff53ebaf"
        }
      ]
    },
    {
      "id": "f05206d3-e019-4fa3-a599-6064da3e2700",
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
          "id": "41050701-cb15-4c21-bbdd-94adeee9a60b"
        }
      ]
    },
    {
      "id": "e4755a37-61c3-4db6-ac38-a58f8d45e9c6",
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
          "id": "7c7b33cc-d213-4db4-b7fa-94a8a52a1c75"
        }
      ]
    },
    {
      "id": "af825c90-5315-442a-ab58-6c20aea6882c",
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
          "id": "728acf64-ffbf-4197-8fe3-dd7debbf8b0b"
        }
      ]
    },
    {
      "id": "de4acd99-0d28-4085-8971-b5636dfd2f83",
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
          "id": "051231a7-8920-41a3-8af2-b0fecab0a51f"
        }
      ]
    },
    {
      "id": "b044d955-4ef6-4543-b881-353118107c0a",
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
          "id": "37692576-c5ac-4652-8418-50fc689486c0"
        }
      ]
    },
    {
      "id": "7781bf05-aa1b-4c76-bd93-ca94fa0faf58",
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
          "id": "59876493-d4ad-46f8-a5ab-6626aed9e2cb"
        }
      ]
    },
    {
      "id": "3c62228a-d18f-40b7-9660-bfa2c329b341",
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
          "id": "b421f6cb-2ace-4739-a36a-69b0c524a26f"
        }
      ]
    },
    {
      "id": "8aa0f106-a9ea-4022-b9bf-85b6be4fee4c",
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
          "id": "bd4ab0e8-2f74-4aa0-ad97-cdccce861035"
        }
      ]
    },
    {
      "id": "29d26492-68c6-4b93-a329-581ade338eb8",
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
          "id": "4cc47ed2-51eb-40e0-8354-07e9258e5a16"
        }
      ]
    },
    {
      "id": "2dce520c-1866-4af1-ab1c-dce275b102a0",
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
          "id": "bf921f3c-afc2-4520-aa6f-b4a97772c0d8"
        }
      ]
    },
    {
      "id": "42e6832d-7aff-40d3-85ee-78b1a9de3fdc",
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
          "id": "2ae814b5-f76f-4b65-9325-a0285d9258bd"
        }
      ]
    },
    {
      "id": "40188525-f396-4456-addf-13e38f538de1",
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
          "id": "dd31c0a2-8de6-4205-b59e-b84209642069"
        }
      ]
    },
    {
      "id": "96a4b9e5-d5ec-4469-b655-50e0441675a8",
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
          "id": "36dd1d12-4f8a-476a-963f-65649bfec227"
        }
      ]
    },
    {
      "id": "5e14167d-7551-41b4-9ec6-1904e3c49ad3",
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
          "id": "d97894c3-5d1a-4165-8107-f7724a21f18a"
        }
      ]
    },
    {
      "id": "a506f9af-66c5-4de0-a39f-2019f8c8ff3e",
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
          "id": "e235a2a7-04d1-4c7b-9efd-a8015025c0df"
        }
      ]
    },
    {
      "id": "9d764826-0a15-4b99-804b-d714df40f869",
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
          "id": "350eb6af-a2ad-40f6-bf1e-864c585a3c37"
        }
      ]
    },
    {
      "id": "69e34b7a-81d6-4386-958f-5cce9610bbe7",
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
          "id": "f6c551ae-127f-4b56-9b92-46bfb7e9fa6c"
        }
      ]
    },
    {
      "id": "4947424c-216e-4852-8325-d1462492e9cb",
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
          "id": "1b17ccec-3c4b-48e2-91c9-aa34cae58c55"
        }
      ]
    },
    {
      "id": "bea9831e-d97a-4953-8708-6e246724d8a7",
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
          "id": "a8e579ef-8a44-4cc1-8215-f426dd560348"
        }
      ]
    },
    {
      "id": "435540c2-7cd0-448e-b690-73cc19187132",
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
          "id": "ee60bbfd-4b33-4c59-95e5-a447f83809a9"
        }
      ]
    },
    {
      "id": "b6fad855-56ef-4a63-9515-d333b6ed138e",
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
          "id": "b0fac045-3935-43e7-9459-beb61c64d34e"
        }
      ]
    },
    {
      "id": "d12df420-096c-47fa-84c1-3af2e3fe618c",
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
          "id": "0ba064a1-4201-47ad-9346-7d0aae10d5cd"
        }
      ]
    },
    {
      "id": "d62cc279-cfcf-4822-861e-df6a2f05e04f",
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
          "id": "877be8a7-e5f4-4db1-b7c1-aeda4a7b91a3"
        }
      ]
    }
  ]
}