---
name: Elastic Load Balancing
x-slug: elastic-load-balancing
description: ""
image: ""
x-kinRank: "8"
x-alexaRank: ""
tags: Elastic Load Balancing
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/apis.md
specificationVersion: "0.14"
apis:
- name: Elastic Load Balancing API Adds the specified tags to the specified resource.
  x-api-slug: elastic-load-balancing-api
  description: Adds the specified tags to the specified resource.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=AddTags
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionaddtags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionaddtags-get-openapi.md
- name: Elastic Load Balancing API Creates a listener for the specified Application
    Load Balancer.
  x-api-slug: elastic-load-balancing-api
  description: Creates a listener for the specified Application Load Balancer.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=CreateListener
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actioncreatelistener-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actioncreatelistener-get-openapi.md
- name: Elastic Load Balancing API Creates an Application Load Balancer.
  x-api-slug: elastic-load-balancing-api
  description: Creates an Application Load Balancer.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=CreateLoadBalancer
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actioncreateloadbalancer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actioncreateloadbalancer-get-openapi.md
- name: Elastic Load Balancing API Creates a rule for the specified listener.
  x-api-slug: elastic-load-balancing-api
  description: Creates a rule for the specified listener.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=CreateRule
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actioncreaterule-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actioncreaterule-get-openapi.md
- name: Elastic Load Balancing API Creates a target group.
  x-api-slug: elastic-load-balancing-api
  description: Creates a target group.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=CreateTargetGroup
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actioncreatetargetgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actioncreatetargetgroup-get-openapi.md
- name: Elastic Load Balancing API Deletes the specified listener.
  x-api-slug: elastic-load-balancing-api
  description: Deletes the specified listener.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=DeleteListener
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondeletelistener-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondeletelistener-get-openapi.md
- name: Elastic Load Balancing API Deletes the specified Application Load Balancer
    and its attached listeners.
  x-api-slug: elastic-load-balancing-api
  description: Deletes the specified Application Load Balancer and its attached listeners.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=DeleteLoadBalancer
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondeleteloadbalancer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondeleteloadbalancer-get-openapi.md
- name: Elastic Load Balancing API Deletes the specified rule.
  x-api-slug: elastic-load-balancing-api
  description: Deletes the specified rule.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=DeleteRule
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondeleterule-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondeleterule-get-openapi.md
- name: Elastic Load Balancing API Deletes the specified target group.
  x-api-slug: elastic-load-balancing-api
  description: Deletes the specified target group.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=DeleteTargetGroup
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondeletetargetgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondeletetargetgroup-get-openapi.md
- name: Elastic Load Balancing API Deregisters the specified targets from the specified
    target group.
  x-api-slug: elastic-load-balancing-api
  description: Deregisters the specified targets from the specified target group.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=DeregisterTargets
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionderegistertargets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionderegistertargets-get-openapi.md
- name: Elastic Load Balancing API Describes the specified listeners or the listeners
    for the specified Application Load Balancer.
  x-api-slug: elastic-load-balancing-api
  description: Describes the specified listeners or the listeners for the specified
    Application Load Balancer.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=DescribeListeners
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescribelisteners-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescribelisteners-get-openapi.md
- name: Elastic Load Balancing API Describes the attributes for the specified Application
    Load Balancer.
  x-api-slug: elastic-load-balancing-api
  description: Describes the attributes for the specified Application Load Balancer.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=DescribeLoadBalancerAttributes
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescribeloadbalancerattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescribeloadbalancerattributes-get-openapi.md
- name: Elastic Load Balancing API Describes the specified Application Load Balancers
    or all of your Application Load Balancers.
  x-api-slug: elastic-load-balancing-api
  description: Describes the specified Application Load Balancers or all of your Application
    Load Balancers.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=DescribeLoadBalancers
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescribeloadbalancers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescribeloadbalancers-get-openapi.md
- name: Elastic Load Balancing API Describes the specified rules or the rules for
    the specified listener.
  x-api-slug: elastic-load-balancing-api
  description: Describes the specified rules or the rules for the specified listener.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=DescribeRules
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescriberules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescriberules-get-openapi.md
- name: Elastic Load Balancing API Describes the specified policies or all policies
    used for SSL negotiation.
  x-api-slug: elastic-load-balancing-api
  description: Describes the specified policies or all policies used for SSL negotiation.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=DescribeSSLPolicies
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescribesslpolicies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescribesslpolicies-get-openapi.md
- name: Elastic Load Balancing API Describes the tags for the specified resources.
  x-api-slug: elastic-load-balancing-api
  description: Describes the tags for the specified resources.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=DescribeTags
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescribetags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescribetags-get-openapi.md
- name: Elastic Load Balancing API Describes the attributes for the specified target
    group.
  x-api-slug: elastic-load-balancing-api
  description: Describes the attributes for the specified target group.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=DescribeTargetGroupAttributes
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescribetargetgroupattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescribetargetgroupattributes-get-openapi.md
- name: Elastic Load Balancing API Describes the specified target groups or all of
    your target groups.
  x-api-slug: elastic-load-balancing-api
  description: Describes the specified target groups or all of your target groups.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=DescribeTargetGroups
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescribetargetgroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescribetargetgroups-get-openapi.md
- name: Elastic Load Balancing API Describes the health of the specified targets or
    all of your targets.
  x-api-slug: elastic-load-balancing-api
  description: Describes the health of the specified targets or all of your targets.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=DescribeTargetHealth
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescribetargethealth-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actiondescribetargethealth-get-openapi.md
- name: Elastic Load Balancing API Modifies the specified properties of the specified
    listener.
  x-api-slug: elastic-load-balancing-api
  description: Modifies the specified properties of the specified listener.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=ModifyListener
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionmodifylistener-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionmodifylistener-get-openapi.md
- name: Elastic Load Balancing API Modifies the specified attributes of the specified
    Application Load Balancer.
  x-api-slug: elastic-load-balancing-api
  description: Modifies the specified attributes of the specified Application Load
    Balancer.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=ModifyLoadBalancerAttributes
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionmodifyloadbalancerattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionmodifyloadbalancerattributes-get-openapi.md
- name: Elastic Load Balancing API Modifies the specified rule.
  x-api-slug: elastic-load-balancing-api
  description: Modifies the specified rule.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=ModifyRule
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionmodifyrule-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionmodifyrule-get-openapi.md
- name: Elastic Load Balancing API Modifies the health checks used when evaluating
    the health state of the targets in the specified target group.
  x-api-slug: elastic-load-balancing-api
  description: Modifies the health checks used when evaluating the health state of
    the targets in the specified target group.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=ModifyTargetGroup
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionmodifytargetgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionmodifytargetgroup-get-openapi.md
- name: Elastic Load Balancing API Modifies the specified attributes of the specified
    target group.
  x-api-slug: elastic-load-balancing-api
  description: Modifies the specified attributes of the specified target group.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=ModifyTargetGroupAttributes
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionmodifytargetgroupattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionmodifytargetgroupattributes-get-openapi.md
- name: Elastic Load Balancing API Registers the specified targets with the specified
    target group.
  x-api-slug: elastic-load-balancing-api
  description: Registers the specified targets with the specified target group.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=RegisterTargets
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionregistertargets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionregistertargets-get-openapi.md
- name: Elastic Load Balancing API Removes the specified tags from the specified resource.
  x-api-slug: elastic-load-balancing-api
  description: Removes the specified tags from the specified resource.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=RemoveTags
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionremovetags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionremovetags-get-openapi.md
- name: Elastic Load Balancing API Sets the priorities of the specified rules.
  x-api-slug: elastic-load-balancing-api
  description: Sets the priorities of the specified rules.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=SetRulePriorities
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionsetrulepriorities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionsetrulepriorities-get-openapi.md
- name: Elastic Load Balancing API Associates the specified security groups with the
    specified load balancer.
  x-api-slug: elastic-load-balancing-api
  description: Associates the specified security groups with the specified load balancer.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=SetSecurityGroups
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionsetsecuritygroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionsetsecuritygroups-get-openapi.md
- name: Elastic Load Balancing API Enables the Availability Zone for the specified
    subnets for the specified load balancer.
  x-api-slug: elastic-load-balancing-api
  description: Enables the Availability Zone for the specified subnets for the specified
    load balancer.
  image: ""
  humanURL: ""
  baseURL: ://///?Action=SetSubnets
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionsetsubnets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/actionsetsubnets-get-openapi.md
- name: Elastic Load Balancing API
  x-api-slug: elastic-load-balancing-api
  description: ""
  image: ""
  humanURL: ""
  baseURL: :///
  tags: Elastic Load Balancing
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/elastic-load-balancing/master/_listings/elastic-load-balancing/openapi.md
x-common: []
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---