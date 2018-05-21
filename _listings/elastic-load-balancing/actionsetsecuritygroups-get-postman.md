{
  "info": {
    "name": "Elastic Load Balancing API Associates the specified security groups with the specified load balancer.",
    "_postman_id": "b7f60a53-a585-4917-bc10-4e2a2cf43a31",
    "description": "Associates the specified security groups with the specified load balancer.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "d1cc2014-94c0-46c2-9816-69ff37b097c9",
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
          "id": "e437d83b-004c-41d8-b2b0-1e4e4774ee62"
        }
      ]
    },
    {
      "id": "e1f883d1-0ee8-4fc0-8b76-873526b1e616",
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
          "id": "147ef3a8-1b45-47b8-8812-e644bb4dfc31"
        }
      ]
    },
    {
      "id": "41a1ed52-fdcd-41dd-a44c-3526a2cd3832",
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
          "id": "58534b66-68a7-491f-af48-93436c1f65f6"
        }
      ]
    },
    {
      "id": "f72d70a5-0760-45a4-a707-4447a5aa7d5c",
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
          "id": "5b9252b0-792f-41a7-bc18-3d2165313e3c"
        }
      ]
    },
    {
      "id": "ccb6c674-930b-45df-b2f1-ad9c2586b8f2",
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
          "id": "42d7c2f1-ec3c-4e8c-b44e-71587616b4fa"
        }
      ]
    },
    {
      "id": "51fa3099-98db-4073-9a99-4e209e62991b",
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
          "id": "f3c645c6-bac5-41cc-be64-f3aba9df242f"
        }
      ]
    },
    {
      "id": "f4631e7a-3359-49a6-8344-30b6ac0b7635",
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
          "id": "e8f0038d-02c0-42b7-8ebe-31172d6d0ed8"
        }
      ]
    },
    {
      "id": "996d75bf-1bcd-446d-9fa9-7aa63c5e36f8",
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
          "id": "70e26b46-c87f-424d-ac90-2481a9cad0b6"
        }
      ]
    },
    {
      "id": "9f58a123-325b-495d-8187-fbbef5db104c",
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
          "id": "2895192d-08af-4c20-8b0a-746fe950b953"
        }
      ]
    },
    {
      "id": "c8c1b58f-bb5e-4560-82cb-95b7c7870542",
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
          "id": "0a066ce4-09e7-4d4d-b9d6-40a73fc5a429"
        }
      ]
    },
    {
      "id": "1fc46002-fc0d-4931-9a9f-af358c64901e",
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
          "id": "3d3d240c-4866-40b3-9c52-a6a786aae1fc"
        }
      ]
    },
    {
      "id": "c7763ab1-5e2b-4b3e-bdb8-f55e7a9cf1b3",
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
          "id": "97a61c52-9e64-4eee-9200-4f18d0fc8394"
        }
      ]
    },
    {
      "id": "259f0ea2-8e62-4e06-9fa7-f118c1693892",
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
          "id": "5cb6fe65-09b5-41f9-8606-55c4f76b7f70"
        }
      ]
    },
    {
      "id": "24a4f573-f408-4fab-a9bb-d12e61f7ed28",
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
          "id": "52f439da-b20f-4187-b39a-31d89a1e22cd"
        }
      ]
    },
    {
      "id": "424220d9-596e-4cac-9551-872264f08cf6",
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
          "id": "e7a5bc91-c0f6-49b3-8bfc-29b6a13e4ca2"
        }
      ]
    },
    {
      "id": "91e35530-28b6-4c65-9b19-bb615a4ef9fb",
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
          "id": "89df32f5-fd35-4b21-8e8d-1696ad44d5e1"
        }
      ]
    },
    {
      "id": "77034cdd-198c-416e-a89f-db7be29708cd",
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
          "id": "15c0e2b8-7130-4344-831d-bc8373c04c0c"
        }
      ]
    },
    {
      "id": "f93bb5df-ab56-46f7-b105-2b4523038e94",
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
          "id": "ef2352fc-ed58-405a-9bbe-18778e25ca72"
        }
      ]
    },
    {
      "id": "ee08567d-0a56-4afa-adc0-4a8b14bab760",
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
          "id": "11118837-098e-492a-94b9-4b0715074f5f"
        }
      ]
    },
    {
      "id": "3d4966cd-5666-4cb1-9066-429bf4ba8cd9",
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
          "id": "10dd7489-f56a-443a-aae1-25e5eccfc590"
        }
      ]
    },
    {
      "id": "2e1fb95f-0e7c-4fbf-81e9-1a8163a74f55",
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
          "id": "6623f675-acc6-405a-a412-8f3bdc922d87"
        }
      ]
    },
    {
      "id": "e27803bb-9348-4814-81ee-e59e77faeb1d",
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
          "id": "4cff86fd-8287-4907-9414-e822304ad2ba"
        }
      ]
    },
    {
      "id": "7272860f-25b5-47ae-a9b8-2343888bc779",
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
          "id": "51b51f6d-51cb-49f3-9f64-8e544c79474d"
        }
      ]
    },
    {
      "id": "be1a2c10-cc05-430f-ad08-80cd227d3cf4",
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
          "id": "d5764f88-7ce1-436e-8ac2-21f4f60ae36d"
        }
      ]
    },
    {
      "id": "d870f1d5-028c-4d52-9f5e-1184dab35459",
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
          "id": "5ffb4f5e-a550-4ae5-8011-79b5d4810b2d"
        }
      ]
    },
    {
      "id": "95b98024-f074-416e-922a-1f2906f3d99f",
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
          "id": "b692a3be-9030-489a-bee1-abde794d1b07"
        }
      ]
    },
    {
      "id": "5c3a7b0a-6dc6-4bbe-9a73-ee8c52550d5c",
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
          "id": "ef63e1a1-bfdc-4583-975e-d1d8a351adcd"
        }
      ]
    },
    {
      "id": "00a06970-bcd7-4e3f-906e-e8e6a846ffc6",
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
          "id": "2e2353b3-cd96-4264-a99a-99abf6dfd405"
        }
      ]
    }
  ]
}