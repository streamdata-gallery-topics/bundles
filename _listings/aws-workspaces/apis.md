---
name: AWS WorkSpaces
description: Amazon WorkSpaces is a fully managed, secure desktop computing service
  which runs on the AWS cloud. Amazon WorkSpaces allows you to easily provision cloud-based
  virtual desktops and provide your users access to the documents, applications, and
  resources they need from any supported device, including Windows and Mac computers,
  Chromebooks, iPads, Fire tablets, Android tablets, and Chrome and Firefox web browsers.
  With just a few clicks in the AWS Management Console, you can deploy high-quality
  cloud desktops for any number of users. With Amazon WorkSpaces, you pay either monthly
  or hourly just for the Amazon WorkSpaces you launch, which helps you save money
  when compared to traditional desktops and on-premises Virtual Desktop Infrastructure
  (VDI) solutions.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkSpaces.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Desktops
- Amazon Web Services
created: "2018-03-27"
modified: "2018-03-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/bundles/master/_listings/aws-workspaces/apis.yaml
specificationVersion: "0.14"
apis:
- name: AWS WorkSpaces Service API
  description: Amazon WorkSpaces is a fully managed, secure desktop computing service
    which runs on the AWS cloud
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkSpaces.png
  humanURL: ""
  baseURL: :///
  tags: Bundles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bundles/master/_listings/aws-workspaces/action-describeworkspacebundles-get.md
- name: AWS WorkSpaces Service API Describe Workspace Bundles
  description: Obtains information about the WorkSpace bundles that are available
    to your account in the specified region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkSpaces.png
  humanURL: https://aws.amazon.com/workspaces/
  baseURL: http:://{host}//
  tags: Bundles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bundles/master/_listings/aws-workspaces/action-describeworkspacebundles-get.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/workspaces/latest/api/api-reference.html
- type: x-faq
  url: https://aws.amazon.com/workspaces/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=164
- type: x-pricing
  url: https://aws.amazon.com/workspaces/pricing/
- type: x-testimonials
  url: https://aws.amazon.com/workspaces/testimonials/
- type: x-webinars
  url: https://aws.amazon.com/workspaces/resources/#webinars
- type: x-website
  url: https://aws.amazon.com/workspaces/
- type: x-white-papers
  url: https://aws.amazon.com/workspaces/resources/#whitepapers
- type: x-documentation
  url: http://docs.aws.amazon.com/workspaces/latest/api/api-reference.html
- type: x-faq
  url: https://aws.amazon.com/workspaces/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=164
- type: x-pricing
  url: https://aws.amazon.com/workspaces/pricing/
- type: x-testimonials
  url: https://aws.amazon.com/workspaces/testimonials/
- type: x-webinars
  url: https://aws.amazon.com/workspaces/resources/#webinars
- type: x-website
  url: https://aws.amazon.com/workspaces/
- type: x-white-papers
  url: https://aws.amazon.com/workspaces/resources/#whitepapers
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---