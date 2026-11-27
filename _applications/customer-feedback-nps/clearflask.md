---
app: ClearFlask
app_slug: clearflask
app_url: https://github.com/clearflask/clearflask
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4200.10
  key: product-discovery-backlog-management
  layer: domain
  name: Product Discovery & Backlog Management
  providers:
  - GitHub
  - GitLab
  - Jira
  url: /capabilities/product-discovery-backlog-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: domain
  name: Team Chat Bridging
  providers:
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon S3
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.50.50
  key: BC-620.50.50
  layer: common
  name: Cryptography and Key Management
  providers:
  - Let's Encrypt
  url: /capabilities/security-architecture-management/
  via_parent: Security Architecture Management
- attribution: API Evangelist extension
  id: AE-927
  key: AE-927
  layer: common
  name: Domain Registration & Managed DNS
  providers:
  - Amazon Route 53
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-1400.30
  key: fraud-detection-investigation-management
  layer: common
  name: Fraud Detection & Investigation Management
  providers:
  - Castle
  url: /capabilities/fraud-detection-investigation-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: common
  name: Hosted LLM Inference
  providers:
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Amazon DynamoDB
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: common
  name: Search and Discovery Management
  providers:
  - Elasticsearch
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: Turbo EA
  id: BC-4250
  key: subscription-billing-revenue-management
  layer: common
  name: Subscription Billing & Revenue Management
  providers:
  - Kill Bill
  url: /capabilities/subscription-billing-revenue-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES
  url: /capabilities/email/
  via_parent: Email
category:
  id: customer-feedback-nps
  name: Customer Feedback & NPS
  url: /applications/customer-feedback-nps/
counts:
  declared: 0
  observed: 15
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
- route: source code
  url: https://github.com/clearflask/clearflask/tree/master/clearflask-server
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 41.0
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-dynamodb
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Database
    - Document Store
    - Key-Value Store
    url: /providers/amazon-dynamodb/
  layer: common
  name: Amazon DynamoDB
  provider: amazon-dynamodb
  says: ships the Amazon DynamoDB SDK or integration code
  source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-927
    key: AE-927
    name: Domain Registration & Managed DNS
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.6
    band: exemplar
    in_catalog: true
    kin_score: 69.6
    mcp: &id003
      status: none
    slug: amazon-route-53
    status: profiled
    tags: &id004
    - Amazon Web Services
    - DNS
    - Domain Registration
    - Health Checks
    url: /providers/amazon-route-53/
  layer: common
  name: Amazon Route 53
  provider: amazon-route-53
  says: ships the Amazon Route 53 SDK or integration code
  source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/clearflask/clearflask/tree/master/clearflask-server
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.0
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id007
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id008
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
  layer: common
  name: Amazon SES
  provider: amazon-ses
  says: ships the Amazon SES SDK or integration code
  source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1400.30
    key: fraud-detection-investigation-management
    name: Fraud Detection & Investigation Management
    url: /capabilities/fraud-detection-investigation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.0
    band: developing
    in_catalog: true
    kin_score: 51.8
    mcp: &id009
      status: none
    slug: castle
    status: profiled
    tags: &id010
    - Bot Detection
    - Company
    - Fraud Prevention
    - Security
    url: /providers/castle/
  layer: common
  name: Castle
  provider: castle
  says: ships the Castle SDK or integration code
  source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.5
    band: exemplar
    in_catalog: true
    kin_score: 78.4
    mcp: &id011
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id012
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
  layer: common
  name: Elasticsearch
  provider: elastic
  says: ships the Elasticsearch SDK or integration code
  source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.10
    key: product-discovery-backlog-management
    name: Product Discovery & Backlog Management
    url: /capabilities/product-discovery-backlog-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id013
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id014
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/clearflask/clearflask/tree/master/clearflask-server
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.10
    key: product-discovery-backlog-management
    name: Product Discovery & Backlog Management
    url: /capabilities/product-discovery-backlog-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id015
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id016
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/clearflask/clearflask/tree/master/clearflask-server
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.10
    key: product-discovery-backlog-management
    name: Product Discovery & Backlog Management
    url: /capabilities/product-discovery-backlog-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id017
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id018
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: domain
  name: Jira
  provider: jira
  says: ships the Jira SDK or integration code
  source: https://github.com/clearflask/clearflask/tree/master/clearflask-server
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.2
    band: developing
    in_catalog: true
    kin_score: 39.6
    mcp: &id019
      status: unchecked
    slug: killbill
    status: profiled
    tags: &id020
    - Billing
    - Payments
    - Subscription Billing
    - Usage Metering
    url: /providers/killbill/
  layer: common
  name: Kill Bill
  provider: killbill
  says: ships the Kill Bill SDK or integration code
  source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.50.50
    key: BC-620.50.50
    name: Cryptography and Key Management
    url: /capabilities/security-architecture-management/
    via_parent: Security Architecture Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.8
    band: emerging
    in_catalog: true
    kin_score: 23.7
    mcp: &id021
      status: none
    slug: lets-encrypt
    status: profiled
    tags: &id022
    - Certificates
    - Linux Foundation
    - Security
    - TLS
    url: /providers/lets-encrypt/
  layer: common
  name: Let's Encrypt
  provider: lets-encrypt
  says: ships the Let's Encrypt SDK or integration code
  source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id023
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id024
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: common
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id025
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id026
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id027
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id028
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id029
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id030
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/clearflask/clearflask/blob/master/clearflask-server/pom.xml
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/customer-feedback-nps/clearflask/
providers:
- agent_band: agent-native
  agent_readiness: 41.0
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id001
  name: Amazon DynamoDB
  slug: amazon-dynamodb
  status: profiled
  tags: *id002
  url: /providers/amazon-dynamodb/
- agent_band: agent-ready
  agent_readiness: 35.6
  band: exemplar
  in_catalog: true
  kin_score: 69.6
  mcp: *id003
  name: Amazon Route 53
  slug: amazon-route-53
  status: profiled
  tags: *id004
  url: /providers/amazon-route-53/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id005
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id006
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 38.0
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id007
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id008
  url: /providers/amazon-ses/
- agent_band: agent-aware
  agent_readiness: 21.0
  band: developing
  in_catalog: true
  kin_score: 51.8
  mcp: *id009
  name: Castle
  slug: castle
  status: profiled
  tags: *id010
  url: /providers/castle/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id011
  name: Elasticsearch
  slug: elastic
  status: profiled
  tags: *id012
  url: /providers/elastic/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id013
  name: GitHub
  slug: github
  status: profiled
  tags: *id014
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id015
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id016
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id017
  name: Jira
  slug: jira
  status: profiled
  tags: *id018
  url: /providers/jira/
- agent_band: agent-aware
  agent_readiness: 23.2
  band: developing
  in_catalog: true
  kin_score: 39.6
  mcp: *id019
  name: Kill Bill
  slug: killbill
  status: profiled
  tags: *id020
  url: /providers/killbill/
- agent_band: agent-aware
  agent_readiness: 16.8
  band: emerging
  in_catalog: true
  kin_score: 23.7
  mcp: *id021
  name: Let's Encrypt
  slug: lets-encrypt
  status: profiled
  tags: *id022
  url: /providers/lets-encrypt/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id023
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id024
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id025
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id026
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id027
  name: Slack
  slug: slack
  status: profiled
  tags: *id028
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id029
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id030
  url: /providers/stripe/
siblings:
- name: Canny
  rows: 18
  url: /applications/customer-feedback-nps/canny/
- name: Fider
  rows: 8
  url: /applications/customer-feedback-nps/fider/
- name: Formbricks
  rows: 22
  url: /applications/customer-feedback-nps/formbricks/
- name: Retently
  rows: 17
  url: /applications/customer-feedback-nps/retently/
- name: SurveyMonkey
  rows: 6
  url: /applications/customer-feedback-nps/surveymonkey/
- name: Survicate
  rows: 25
  url: /applications/customer-feedback-nps/survicate/
sitemap: true
title: 'ClearFlask: Customer Feedback & NPS reference app'
---
