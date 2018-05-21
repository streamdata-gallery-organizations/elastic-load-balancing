{
  "info": {
    "name": "Elastic Load Balancing API Describes the specified policies or all policies used for SSL negotiation.",
    "_postman_id": "56a8e37d-25b0-408d-be5a-c4558c717ed6",
    "description": "Describes the specified policies or all policies used for SSL negotiation.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "7ee6d933-e39a-4b3c-b1a5-ae6daaeb5bbd",
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
          "id": "81abef17-2f8c-48bc-9452-2642b065b409"
        }
      ]
    },
    {
      "id": "9744694c-6e1d-450e-946b-8d81fb83e713",
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
          "id": "3b793941-864a-4c15-a49b-c368e8f87c21"
        }
      ]
    },
    {
      "id": "e535e547-50b2-4686-ba47-936d6887a617",
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
          "id": "39668692-f05a-4603-8f37-0dc8937359d7"
        }
      ]
    },
    {
      "id": "184a9292-ad65-48f6-8c3f-6d58357c8e68",
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
          "id": "d393dfc5-f4af-4984-88ed-5c7f89a96131"
        }
      ]
    },
    {
      "id": "c8fd8554-5d3e-4160-8373-89851b717a9d",
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
          "id": "6b6935d0-2481-42be-93e8-6f5c7888ce6b"
        }
      ]
    },
    {
      "id": "c096eaee-d67b-4012-baa5-615f41de8659",
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
          "id": "762bf09f-5061-4071-bd57-2f495ee8c0ed"
        }
      ]
    },
    {
      "id": "efd5db83-8b4f-47ae-9aa6-2e98ee02d585",
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
          "id": "bd8f81fb-8ea6-4796-9c61-40b38d8e255e"
        }
      ]
    },
    {
      "id": "f3fd38f3-a003-4038-8f35-88feda71c8c9",
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
          "id": "3154b4dc-b4e8-40e3-bc31-427e4b2c3d16"
        }
      ]
    },
    {
      "id": "49b77fc6-aa2d-4d55-b8dc-fd3e1fdf3f8c",
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
          "id": "1cc5d984-870a-49f3-97fb-b977941f97ca"
        }
      ]
    },
    {
      "id": "12fdad2a-6c2d-4341-9484-bbb3d8f24456",
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
          "id": "c1b6f959-554c-46b9-b4af-29370caf0dd3"
        }
      ]
    },
    {
      "id": "2422fd9b-6c6a-4328-9bba-535b81c9a2df",
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
          "id": "4c1679cd-9c5f-4630-9166-afa8aea50123"
        }
      ]
    },
    {
      "id": "7921c7b8-9c5b-4910-ac7d-4b806ee6802d",
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
          "id": "0503e0d4-efde-415c-8139-d20aedfbb12b"
        }
      ]
    },
    {
      "id": "e1b985ed-fbaa-465c-9c66-125c16beb42f",
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
          "id": "35e0891f-fcf1-4516-9171-069155133994"
        }
      ]
    },
    {
      "id": "4b380542-9680-4c74-a5e9-41167d6201d8",
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
          "id": "5d366d0b-11c6-4c0e-bbfc-72d68a24e28b"
        }
      ]
    },
    {
      "id": "11911f2b-07d9-4c19-b089-04fc66c10fc8",
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
          "id": "fe25d332-7df6-45e9-a82b-a2f99b7a93b1"
        }
      ]
    }
  ]
}