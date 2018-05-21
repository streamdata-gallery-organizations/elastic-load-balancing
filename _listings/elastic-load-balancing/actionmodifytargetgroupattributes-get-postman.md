{
  "info": {
    "name": "Elastic Load Balancing API Modifies the specified attributes of the specified target group.",
    "_postman_id": "4e7c306c-f262-43db-ac64-3b43febb9453",
    "description": "Modifies the specified attributes of the specified target group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "87c36ac9-cde3-4433-824d-e8c1f72a97bd",
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
          "id": "3a26ac56-033e-4d69-b4d1-760a4af8fe18"
        }
      ]
    },
    {
      "id": "84979fd2-9865-40c1-8821-7a52e3f27775",
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
          "id": "642655fd-ad9a-4fd9-906a-756ef0c69633"
        }
      ]
    },
    {
      "id": "3da7f25e-52c4-43ce-a632-c1a75d990a2e",
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
          "id": "d5d91d1d-b088-4ea8-b8f7-87af2f8f88ee"
        }
      ]
    },
    {
      "id": "ff7d7108-4276-4c89-9aa0-6b40410c367c",
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
          "id": "4db2e657-606b-466d-88f1-a9c0b89c8ddf"
        }
      ]
    },
    {
      "id": "ca746bdf-4ca6-4850-bd4f-67b7845955bb",
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
          "id": "23b11e3e-387c-4882-ae57-36ff0cdf1851"
        }
      ]
    },
    {
      "id": "21992473-bd1c-45ae-b240-e532973de03d",
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
          "id": "f1b42691-d0dc-43c1-a292-983592d0a1a4"
        }
      ]
    },
    {
      "id": "8205c0bc-f819-4344-83ac-d7f08873cba4",
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
          "id": "943fd89c-3df0-4ba7-a19a-533463f2ec0e"
        }
      ]
    },
    {
      "id": "96008b5a-17ed-4a7e-8579-5fbc98008d82",
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
          "id": "cf22fc2c-d6cd-4929-8810-140b54a2f79a"
        }
      ]
    },
    {
      "id": "a4a1cff3-c80a-4c39-adc3-e0752e66fd77",
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
          "id": "0707b4d3-c895-46cd-aae7-78b596aceb0d"
        }
      ]
    },
    {
      "id": "d5cd7d65-fff7-4d20-b4d9-6483501f8b3d",
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
          "id": "d344a6f9-b8f5-4978-a579-56f4a928a4e3"
        }
      ]
    },
    {
      "id": "bba7746c-af52-480a-9fa5-54b605dd3512",
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
          "id": "46661f78-c4f4-412a-82a1-4056bccf78d5"
        }
      ]
    },
    {
      "id": "5f307be4-a1c2-4d7e-a628-02f31f645864",
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
          "id": "8efe7c9f-a055-4e4d-9cdc-7bf5369cb2e2"
        }
      ]
    },
    {
      "id": "f6766c9a-9fea-4a70-a2c7-fee8233bd1e7",
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
          "id": "8350ea4a-c1e1-42e9-ae20-182d870adce4"
        }
      ]
    },
    {
      "id": "a2eed5b7-e919-4cb6-845b-072cd82de0bb",
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
          "id": "558673be-ab3d-4a64-aadc-0eca1bed27ca"
        }
      ]
    },
    {
      "id": "274650f8-72b3-4862-a6b0-2e5874b22f04",
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
          "id": "d1655e7b-a4f7-41a2-8808-64fc9b476a84"
        }
      ]
    },
    {
      "id": "fc2ac7e8-d016-42fa-899a-6283c7007ab2",
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
          "id": "3654aadb-41cb-4574-8280-a2e1f4ecec2c"
        }
      ]
    },
    {
      "id": "cd5d349d-b51b-4032-bccd-c5a1de78dc98",
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
          "id": "da310465-83a1-4276-8f89-c2a49aa07f4f"
        }
      ]
    },
    {
      "id": "06172878-103a-4216-b60c-a0680aa39205",
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
          "id": "2ed74d6a-9d1b-4efc-8cab-59cefa0241ac"
        }
      ]
    },
    {
      "id": "69a90625-e29d-48db-ba36-98702f35c253",
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
          "id": "102db7a8-d2ae-4655-9bdc-05950bb5ff98"
        }
      ]
    },
    {
      "id": "380efb45-01b4-45fe-9471-bc9c07cf1c5e",
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
          "id": "6cde63db-bd03-477b-ae7c-694a460cb54c"
        }
      ]
    },
    {
      "id": "4778a666-3065-4af6-b915-107555501ef6",
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
          "id": "79ce4a12-d916-4c07-9c82-c80cf12c6184"
        }
      ]
    },
    {
      "id": "0f45bf5e-d803-437e-8e95-2c20197b414d",
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
          "id": "52f8be3c-ade0-48b8-8187-9aebd0ea9218"
        }
      ]
    },
    {
      "id": "0883e354-8695-4a70-ac0d-86d322355d92",
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
          "id": "47834b53-ff94-4982-8e19-cc86c8fc83c8"
        }
      ]
    },
    {
      "id": "59a0270b-93bb-46ab-86ef-9c9ebec7451b",
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
          "id": "1052e9f7-588d-4856-a538-8c035b42370e"
        }
      ]
    }
  ]
}