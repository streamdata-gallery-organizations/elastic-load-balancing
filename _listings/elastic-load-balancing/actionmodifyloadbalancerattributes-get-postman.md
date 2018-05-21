{
  "info": {
    "name": "Elastic Load Balancing API Modifies the specified attributes of the specified Application Load Balancer.",
    "_postman_id": "7536e348-8a3f-401b-a50a-82d038cfcb9e",
    "description": "Modifies the specified attributes of the specified Application Load Balancer.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "09e9d944-e061-4a5a-9420-4edee3e8849f",
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
          "id": "1132347e-785f-4218-bddc-2f802bf34d0b"
        }
      ]
    },
    {
      "id": "b92a54bb-0e87-4886-83e4-b5321f41ba85",
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
          "id": "b2d48e0c-6092-4500-a860-f7371e74708d"
        }
      ]
    },
    {
      "id": "d90a1ba3-0b6e-4cff-80fc-6b3c56f05a8d",
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
          "id": "35340675-1c4d-4019-9c03-3628ebaeaa24"
        }
      ]
    },
    {
      "id": "a145ba2c-f060-44d1-8f6e-1cdc7814dd25",
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
          "id": "0386f96f-f74a-4f0e-baf0-df2be6f8ba44"
        }
      ]
    },
    {
      "id": "641e8fd4-f9bd-4398-9e21-9f53914987cb",
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
          "id": "e621087f-fc1e-4395-8543-63edc5fcab6d"
        }
      ]
    },
    {
      "id": "ab03515d-89e2-4fc0-9ce6-6d11cdf07f16",
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
          "id": "88ab690f-eeb0-4c51-9519-9d41ba4cb446"
        }
      ]
    },
    {
      "id": "02a327e0-9702-4ab0-adaf-96f0f2d4a8eb",
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
          "id": "72229d16-7b94-40ed-a921-958d69a0a2d7"
        }
      ]
    },
    {
      "id": "538e9bcf-f393-4aad-b6e2-85813086ea01",
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
          "id": "e6d5410b-44b5-4797-8a98-26bc70375d71"
        }
      ]
    },
    {
      "id": "f0a33ae6-4787-4eee-a766-8547bb487863",
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
          "id": "432837d6-d059-406d-9066-266c1e92bdbc"
        }
      ]
    },
    {
      "id": "8267e40d-cf70-4a11-a910-93781d3fd2dc",
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
          "id": "5a9c65e9-282c-4b44-b4ae-4ea78b169edf"
        }
      ]
    },
    {
      "id": "6d3a7145-4055-4efc-82ed-3f9b7414eee6",
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
          "id": "46cdf50d-538f-4a0d-b84b-69c2cb11683e"
        }
      ]
    },
    {
      "id": "4bdac71b-7b08-4c4e-bb55-3b4e1aa57095",
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
          "id": "8cccaa07-eb82-438b-8fcd-26ed2c94a810"
        }
      ]
    },
    {
      "id": "245d9146-d5f5-4aac-b001-a554db2419b9",
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
          "id": "d55117a2-6ec0-45c3-8203-ef1614559609"
        }
      ]
    },
    {
      "id": "ca8ed410-1124-415f-88af-560248829c74",
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
          "id": "bd5cd611-c730-428e-a538-5836cc70207c"
        }
      ]
    },
    {
      "id": "2fd56d2d-0c05-49d1-868b-6dadd8ed0e8e",
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
          "id": "f848a935-83e6-46a7-9095-731c064f91f8"
        }
      ]
    },
    {
      "id": "a8f1cbce-a729-496f-ab9b-c77d9c60c786",
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
          "id": "637c3a32-095b-48c8-9b54-39049b58651a"
        }
      ]
    },
    {
      "id": "b6e6cbe1-6e4c-483c-a777-0e90c3b05e9c",
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
          "id": "a3ba6806-093b-430e-acfa-913c1dfa530f"
        }
      ]
    },
    {
      "id": "24839297-59f0-46ba-a8f6-01af5cf942ef",
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
          "id": "a99f2e26-895d-4c69-b995-f10bacb31709"
        }
      ]
    },
    {
      "id": "851e1e4d-9cfd-4711-a5bc-95ef781310f8",
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
          "id": "411fb35a-7622-4193-87fc-e2d7046e62fc"
        }
      ]
    },
    {
      "id": "4a91c5c8-70c4-4910-b5cf-dc65c90f62db",
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
          "id": "819f3350-c182-41ca-9c42-9c76cc4352d7"
        }
      ]
    },
    {
      "id": "26e58d6a-66a2-4981-98df-e78faebcb76e",
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
          "id": "f120778d-d1f5-4843-b719-47203f039d5e"
        }
      ]
    }
  ]
}