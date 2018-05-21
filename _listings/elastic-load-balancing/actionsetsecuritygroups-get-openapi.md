---
swagger: "2.0"
x-collection-name: Elastic Load Balancing
x-complete: 0
info:
  title: Elastic Load Balancing API Associates the specified security groups with
    the specified load balancer.
  version: 1.0.0
  description: Associates the specified security groups with the specified load balancer.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddTags:
    get:
      summary: Adds the specified tags to the specified resource.
      description: Adds the specified tags to the specified resource.
      operationId: AddTags
      x-api-path-slug: actionaddtags-get
      parameters:
      - in: query
        name: ResourceArns.member.N
        description: The Amazon Resource Name (ARN) of the resource
        type: string
      - in: query
        name: Tags.member.N
        description: The tags
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=CreateListener:
    get:
      summary: Creates a listener for the specified Application Load Balancer.
      description: Creates a listener for the specified Application Load Balancer.
      operationId: CreateListener
      x-api-path-slug: actioncreatelistener-get
      parameters:
      - in: query
        name: Certificates.member.N
        description: The SSL server certificate
        type: string
      - in: query
        name: DefaultActions.member.N
        description: The default action for the listener
        type: string
      - in: query
        name: LoadBalancerArn
        description: The Amazon Resource Name (ARN) of the load balancer
        type: string
      - in: query
        name: Port
        description: The port on which the load balancer is listening
        type: string
      - in: query
        name: Protocol
        description: The protocol for connections from clients to the load balancer
        type: string
      - in: query
        name: SslPolicy
        description: The security policy that defines which ciphers and protocols
          are supported
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=CreateLoadBalancer:
    get:
      summary: Creates an Application Load Balancer.
      description: Creates an Application Load Balancer.
      operationId: CreateLoadBalancer
      x-api-path-slug: actioncreateloadbalancer-get
      parameters:
      - in: query
        name: Name
        description: The name of the load balancer
        type: string
      - in: query
        name: Scheme
        description: The nodes of an Internet-facing load balancer have public IP
          addresses
        type: string
      - in: query
        name: SecurityGroups.member.N
        description: The IDs of the security groups to assign to the load balancer
        type: string
      - in: query
        name: Subnets.member.N
        description: The IDs of the subnets to attach to the load balancer
        type: string
      - in: query
        name: Tags.member.N
        description: One or more tags to assign to the load balancer
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=CreateRule:
    get:
      summary: Creates a rule for the specified listener.
      description: Creates a rule for the specified listener.
      operationId: CreateRule
      x-api-path-slug: actioncreaterule-get
      parameters:
      - in: query
        name: Actions.member.N
        description: An action
        type: string
      - in: query
        name: Conditions.member.N
        description: A condition
        type: string
      - in: query
        name: ListenerArn
        description: The Amazon Resource Name (ARN) of the listener
        type: string
      - in: query
        name: Priority
        description: The priority for the rule
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=CreateTargetGroup:
    get:
      summary: Creates a target group.
      description: Creates a target group.
      operationId: CreateTargetGroup
      x-api-path-slug: actioncreatetargetgroup-get
      parameters:
      - in: query
        name: HealthCheckIntervalSeconds
        description: The approximate amount of time, in seconds, between health checks
          of an individual target
        type: string
      - in: query
        name: HealthCheckPath
        description: The ping path that is the destination on the targets for health
          checks
        type: string
      - in: query
        name: HealthCheckPort
        description: The port the load balancer uses when performing health checks
          on targets
        type: string
      - in: query
        name: HealthCheckProtocol
        description: The protocol the load balancer uses when performing health checks
          on targets
        type: string
      - in: query
        name: HealthCheckTimeoutSeconds
        description: The amount of time, in seconds, during which no response from
          a target means a failed health check
        type: string
      - in: query
        name: HealthyThresholdCount
        description: The number of consecutive health checks successes required before
          considering an unhealthy target healthy
        type: string
      - in: query
        name: Matcher
        description: The HTTP codes to use when checking for a successful response
          from a target
        type: string
      - in: query
        name: Name
        description: The name of the target group
        type: string
      - in: query
        name: Port
        description: The port on which the targets receive traffic
        type: string
      - in: query
        name: Protocol
        description: The protocol to use for routing traffic to the targets
        type: string
      - in: query
        name: UnhealthyThresholdCount
        description: The number of consecutive health check failures required before
          considering a target unhealthy
        type: string
      - in: query
        name: VpcId
        description: The identifier of the virtual private cloud (VPC)
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=DeleteListener:
    get:
      summary: Deletes the specified listener.
      description: Deletes the specified listener.
      operationId: DeleteListener
      x-api-path-slug: actiondeletelistener-get
      parameters:
      - in: query
        name: ListenerArn
        description: The Amazon Resource Name (ARN) of the listener
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=DeleteLoadBalancer:
    get:
      summary: Deletes the specified Application Load Balancer and its attached listeners.
      description: Deletes the specified Application Load Balancer and its attached
        listeners.
      operationId: DeleteLoadBalancer
      x-api-path-slug: actiondeleteloadbalancer-get
      parameters:
      - in: query
        name: LoadBalancerArn
        description: The Amazon Resource Name (ARN) of the load balancer
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=DeleteRule:
    get:
      summary: Deletes the specified rule.
      description: Deletes the specified rule.
      operationId: DeleteRule
      x-api-path-slug: actiondeleterule-get
      parameters:
      - in: query
        name: RuleArn
        description: The Amazon Resource Name (ARN) of the rule
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=DeleteTargetGroup:
    get:
      summary: Deletes the specified target group.
      description: Deletes the specified target group.
      operationId: DeleteTargetGroup
      x-api-path-slug: actiondeletetargetgroup-get
      parameters:
      - in: query
        name: TargetGroupArn
        description: The Amazon Resource Name (ARN) of the target group
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=DeregisterTargets:
    get:
      summary: Deregisters the specified targets from the specified target group.
      description: Deregisters the specified targets from the specified target group.
      operationId: DeregisterTargets
      x-api-path-slug: actionderegistertargets-get
      parameters:
      - in: query
        name: TargetGroupArn
        description: The Amazon Resource Name (ARN) of the target group
        type: string
      - in: query
        name: Targets.member.N
        description: The targets
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=DescribeListeners:
    get:
      summary: Describes the specified listeners or the listeners for the specified
        Application Load Balancer.
      description: Describes the specified listeners or the listeners for the specified
        Application Load Balancer.
      operationId: DescribeListeners
      x-api-path-slug: actiondescribelisteners-get
      parameters:
      - in: query
        name: ListenerArns.member.N
        description: The Amazon Resource Names (ARN) of the listeners
        type: string
      - in: query
        name: LoadBalancerArn
        description: The Amazon Resource Name (ARN) of the load balancer
        type: string
      - in: query
        name: Marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: PageSize
        description: The maximum number of results to return with this call
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=DescribeLoadBalancerAttributes:
    get:
      summary: Describes the attributes for the specified Application Load Balancer.
      description: Describes the attributes for the specified Application Load Balancer.
      operationId: DescribeLoadBalancerAttributes
      x-api-path-slug: actiondescribeloadbalancerattributes-get
      parameters:
      - in: query
        name: LoadBalancerArn
        description: The Amazon Resource Name (ARN) of the load balancer
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=DescribeLoadBalancers:
    get:
      summary: Describes the specified Application Load Balancers or all of your Application
        Load Balancers.
      description: Describes the specified Application Load Balancers or all of your
        Application Load Balancers.
      operationId: DescribeLoadBalancers
      x-api-path-slug: actiondescribeloadbalancers-get
      parameters:
      - in: query
        name: LoadBalancerArns.member.N
        description: The Amazon Resource Names (ARN) of the load balancers
        type: string
      - in: query
        name: Marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: Names.member.N
        description: The names of the load balancers
        type: string
      - in: query
        name: PageSize
        description: The maximum number of results to return with this call
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=DescribeRules:
    get:
      summary: Describes the specified rules or the rules for the specified listener.
      description: Describes the specified rules or the rules for the specified listener.
      operationId: DescribeRules
      x-api-path-slug: actiondescriberules-get
      parameters:
      - in: query
        name: ListenerArn
        description: The Amazon Resource Name (ARN) of the listener
        type: string
      - in: query
        name: RuleArns.member.N
        description: The Amazon Resource Names (ARN) of the rules
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=DescribeSSLPolicies:
    get:
      summary: Describes the specified policies or all policies used for SSL negotiation.
      description: Describes the specified policies or all policies used for SSL negotiation.
      operationId: DescribeSSLPolicies
      x-api-path-slug: actiondescribesslpolicies-get
      parameters:
      - in: query
        name: Marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: Names.member.N
        description: The names of the policies
        type: string
      - in: query
        name: PageSize
        description: The maximum number of results to return with this call
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=DescribeTags:
    get:
      summary: Describes the tags for the specified resources.
      description: Describes the tags for the specified resources.
      operationId: DescribeTags
      x-api-path-slug: actiondescribetags-get
      parameters:
      - in: query
        name: ResourceArns.member.N
        description: The Amazon Resource Names (ARN) of the resources
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=DescribeTargetGroupAttributes:
    get:
      summary: Describes the attributes for the specified target group.
      description: Describes the attributes for the specified target group.
      operationId: DescribeTargetGroupAttributes
      x-api-path-slug: actiondescribetargetgroupattributes-get
      parameters:
      - in: query
        name: TargetGroupArn
        description: The Amazon Resource Name (ARN) of the target group
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=DescribeTargetGroups:
    get:
      summary: Describes the specified target groups or all of your target groups.
      description: Describes the specified target groups or all of your target groups.
      operationId: DescribeTargetGroups
      x-api-path-slug: actiondescribetargetgroups-get
      parameters:
      - in: query
        name: LoadBalancerArn
        description: The Amazon Resource Name (ARN) of the load balancer
        type: string
      - in: query
        name: Marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: Names.member.N
        description: The names of the target groups
        type: string
      - in: query
        name: PageSize
        description: The maximum number of results to return with this call
        type: string
      - in: query
        name: TargetGroupArns.member.N
        description: The Amazon Resource Names (ARN) of the target groups
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=DescribeTargetHealth:
    get:
      summary: Describes the health of the specified targets or all of your targets.
      description: Describes the health of the specified targets or all of your targets.
      operationId: DescribeTargetHealth
      x-api-path-slug: actiondescribetargethealth-get
      parameters:
      - in: query
        name: TargetGroupArn
        description: The Amazon Resource Name (ARN) of the target group
        type: string
      - in: query
        name: Targets.member.N
        description: The targets
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=ModifyListener:
    get:
      summary: Modifies the specified properties of the specified listener.
      description: Modifies the specified properties of the specified listener.
      operationId: ModifyListener
      x-api-path-slug: actionmodifylistener-get
      parameters:
      - in: query
        name: Certificates.member.N
        description: The SSL server certificate
        type: string
      - in: query
        name: DefaultActions.member.N
        description: The default actions
        type: string
      - in: query
        name: ListenerArn
        description: The Amazon Resource Name (ARN) of the listener
        type: string
      - in: query
        name: Port
        description: The port for connections from clients to the load balancer
        type: string
      - in: query
        name: Protocol
        description: The protocol for connections from clients to the load balancer
        type: string
      - in: query
        name: SslPolicy
        description: The security policy that defines which ciphers and protocols
          are supported
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=ModifyLoadBalancerAttributes:
    get:
      summary: Modifies the specified attributes of the specified Application Load
        Balancer.
      description: Modifies the specified attributes of the specified Application
        Load Balancer.
      operationId: ModifyLoadBalancerAttributes
      x-api-path-slug: actionmodifyloadbalancerattributes-get
      parameters:
      - in: query
        name: Attributes.member.N
        description: The load balancer attributes
        type: string
      - in: query
        name: LoadBalancerArn
        description: The Amazon Resource Name (ARN) of the load balancer
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=ModifyRule:
    get:
      summary: Modifies the specified rule.
      description: Modifies the specified rule.
      operationId: ModifyRule
      x-api-path-slug: actionmodifyrule-get
      parameters:
      - in: query
        name: Actions.member.N
        description: The actions
        type: string
      - in: query
        name: Conditions.member.N
        description: The conditions
        type: string
      - in: query
        name: RuleArn
        description: The Amazon Resource Name (ARN) of the rule
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=ModifyTargetGroup:
    get:
      summary: Modifies the health checks used when evaluating the health state of
        the targets in the specified target group.
      description: Modifies the health checks used when evaluating the health state
        of the targets in the specified target group.
      operationId: ModifyTargetGroup
      x-api-path-slug: actionmodifytargetgroup-get
      parameters:
      - in: query
        name: HealthCheckIntervalSeconds
        description: The approximate amount of time, in seconds, between health checks
          of an individual target
        type: string
      - in: query
        name: HealthCheckPath
        description: The ping path that is the destination for the health check request
        type: string
      - in: query
        name: HealthCheckPort
        description: The port to use to connect with the target
        type: string
      - in: query
        name: HealthCheckProtocol
        description: The protocol to use to connect with the target
        type: string
      - in: query
        name: HealthCheckTimeoutSeconds
        description: The amount of time, in seconds, during which no response means
          a failed health check
        type: string
      - in: query
        name: HealthyThresholdCount
        description: The number of consecutive health checks successes required before
          considering an unhealthy target healthy
        type: string
      - in: query
        name: Matcher
        description: The HTTP codes to use when checking for a successful response
          from a target
        type: string
      - in: query
        name: TargetGroupArn
        description: The Amazon Resource Name (ARN) of the target group
        type: string
      - in: query
        name: UnhealthyThresholdCount
        description: The number of consecutive health check failures required before
          considering the target unhealthy
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=ModifyTargetGroupAttributes:
    get:
      summary: Modifies the specified attributes of the specified target group.
      description: Modifies the specified attributes of the specified target group.
      operationId: ModifyTargetGroupAttributes
      x-api-path-slug: actionmodifytargetgroupattributes-get
      parameters:
      - in: query
        name: Attributes.member.N
        description: The attributes
        type: string
      - in: query
        name: TargetGroupArn
        description: The Amazon Resource Name (ARN) of the target group
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=RegisterTargets:
    get:
      summary: Registers the specified targets with the specified target group.
      description: Registers the specified targets with the specified target group.
      operationId: RegisterTargets
      x-api-path-slug: actionregistertargets-get
      parameters:
      - in: query
        name: TargetGroupArn
        description: The Amazon Resource Name (ARN) of the target group
        type: string
      - in: query
        name: Targets.member.N
        description: The targets
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=RemoveTags:
    get:
      summary: Removes the specified tags from the specified resource.
      description: Removes the specified tags from the specified resource.
      operationId: RemoveTags
      x-api-path-slug: actionremovetags-get
      parameters:
      - in: query
        name: ResourceArns.member.N
        description: The Amazon Resource Name (ARN) of the resource
        type: string
      - in: query
        name: TagKeys.member.N
        description: The tag keys for the tags to remove
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=SetRulePriorities:
    get:
      summary: Sets the priorities of the specified rules.
      description: Sets the priorities of the specified rules.
      operationId: SetRulePriorities
      x-api-path-slug: actionsetrulepriorities-get
      parameters:
      - in: query
        name: RulePriorities.member.N
        description: The rule priorities
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
  /?Action=SetSecurityGroups:
    get:
      summary: Associates the specified security groups with the specified load balancer.
      description: Associates the specified security groups with the specified load
        balancer.
      operationId: SetSecurityGroups
      x-api-path-slug: actionsetsecuritygroups-get
      parameters:
      - in: query
        name: LoadBalancerArn
        description: The Amazon Resource Name (ARN) of the load balancer
        type: string
      - in: query
        name: SecurityGroups.member.N
        description: The IDs of the security groups
        type: string
      responses:
        200:
          description: OK
      tags:
      - ""
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---