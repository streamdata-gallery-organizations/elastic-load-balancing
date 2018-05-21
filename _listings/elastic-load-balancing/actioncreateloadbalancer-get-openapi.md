---
swagger: "2.0"
x-collection-name: Elastic Load Balancing
x-complete: 0
info:
  title: Elastic Load Balancing API Creates an Application Load Balancer.
  version: 1.0.0
  description: Creates an Application Load Balancer.
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