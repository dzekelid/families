---
name: AWS EC2 Container Service
x-slug: aws-ec2-container-service
description: Amazon EC2 Container Service (ECS) is a highly scalable, high performance
  container management service that supports Docker containers and allows you to easily
  run applications on a managed cluster of Amazon EC2 instances. Amazon ECS eliminates
  the need for you to install, operate, and scale your own cluster management infrastructure.
  With simple API calls, you can launch and stop Docker-enabled applications, query
  the complete state of your cluster, and access many familiar features like security
  groups, Elastic Load Balancing, EBS volumes, and IAM roles. You can use Amazon ECS
  to schedule the placement of containers across your cluster based on your resource
  needs and availability requirements. You can also integrate your own scheduler or
  third-party schedulers to meet business or application specific requirements.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Families
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/aws-ec2-container-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS EC2 Container Service API - List Task Definition Families
  x-api-slug: actionlisttaskdefinitionfamilies-get
  description: |-
    Returns a list of task definition families that are registered to your account
                (which may include task definition families that no longer have any ACTIVE
                task definition revisions).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/aws-ec2-container-service/actionlisttaskdefinitionfamilies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/families/master/_listings/aws-ec2-container-service/actionlisttaskdefinitionfamilies-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.ec2.container.registry.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.ec2.container.service.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/AmazonECS/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/ecs/faqs/
- type: x-getting-started
  url: https://portal.aws.amazon.com/gp/aws/developer/registration/index.html
- type: x-pricing
  url: https://aws.amazon.com/ecs/pricing/
- type: x-website
  url: https://aws.amazon.com/ecs/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---