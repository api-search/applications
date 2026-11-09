---
app: Activepieces
app_slug: activepieces
app_url: https://github.com/activepieces/activepieces
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4210.60
  key: configuration-secrets-management
  layer: common
  name: Configuration & Secrets Management
  providers:
  - 1Password (@1password/sdk)
  - AWS Secrets Manager
  url: /capabilities/configuration-secrets-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry (@sentry/node)
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Autumn (autumn-js, billing)
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - PostHog (posthog-node)
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3 (@aws-sdk/client-s3)
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Amazon Bedrock (@ai-sdk/amazon-bedrock)
  - Anthropic (@ai-sdk/anthropic)
  - Azure OpenAI (@ai-sdk/azure)
  - Google Gemini (@ai-sdk/google)
  - OpenAI (@ai-sdk/openai)
  - Replicate (@ai-sdk/replicate)
  - Vertex AI (@ai-sdk/google-vertex)
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.10.30
  key: AE-110.10.30
  layer: agent
  name: Model Routing & Gateways
  providers:
  - Cloudflare (cloudflare, ai-gateway-provider)
  - OpenRouter (@openrouter/sdk)
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: workflow-automation
  name: Workflow Automation & iPaaS
  url: /applications/workflow-automation/
counts:
  declared: 0
  observed: 15
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/activepieces/activepieces/blob/main/package.json
- route: dependency manifest
  url: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.8
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id001
      source: https://1password.dev/environments/mcp-server
      status: verified
    slug: 1password
    status: profiled
    tags: &id002
    - Password Manager
    - Passwords
    - Secrets
    - Security
    url: /providers/1password/
  layer: common
  name: 1Password (@1password/sdk)
  provider: 1password
  says: ships the 1Password (@1password/sdk) SDK or integration code
  source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
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
    agent_band: agent-ready
    agent_readiness: 35.8
    band: developing
    in_catalog: true
    kin_score: 51.4
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-bedrock
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Artificial Intelligence
    - Foundation Models
    - Generative AI
    url: /providers/amazon-bedrock/
  layer: agent
  name: Amazon Bedrock (@ai-sdk/amazon-bedrock)
  provider: amazon-bedrock
  says: ships the Amazon Bedrock (@ai-sdk/amazon-bedrock) SDK or integration code
  source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
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
  name: Amazon S3 (@aws-sdk/client-s3)
  provider: amazon-s3
  says: ships the Amazon S3 (@aws-sdk/client-s3) SDK or integration code
  source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
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
    agent_band: agent-ready
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 87.5
    mcp: &id007
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id008
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic (@ai-sdk/anthropic)
  provider: anthropic
  says: ships the Anthropic (@ai-sdk/anthropic) SDK or integration code
  source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
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
    agent_band: agent-aware
    agent_readiness: 18.7
    band: emerging
    in_catalog: true
    kin_score: 18.4
    mcp: &id009
      source: https://docs.useautumn.com/documentation/mcp
      status: verified
    slug: autumn
    status: profiled
    tags: &id010
    - Billing
    - Company
    - Open Source
    - Stripe
    url: /providers/autumn/
  layer: common
  name: Autumn (autumn-js, billing)
  provider: autumn
  says: ships the Autumn (autumn-js, billing) SDK or integration code
  source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id011
      status: none
    slug: amazon-secrets-manager
    status: profiled
    tags: &id012
    - Amazon Web Services
    - Configuration
    - Credentials
    - Rotation
    url: /providers/amazon-secrets-manager/
  layer: common
  name: AWS Secrets Manager
  provider: amazon-secrets-manager
  says: ships the AWS Secrets Manager SDK or integration code
  source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
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
    agent_band: agent-aware
    agent_readiness: 23.4
    band: developing
    in_catalog: true
    kin_score: 44.6
    mcp: &id013
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-openai
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Embeddings
    - GPT
    - Generative AI
    url: /providers/microsoft-azure-openai/
  layer: agent
  name: Azure OpenAI (@ai-sdk/azure)
  provider: microsoft-azure-openai
  says: ships the Azure OpenAI (@ai-sdk/azure) SDK or integration code
  source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 69.6
    band: exemplar
    in_catalog: true
    kin_score: 82.8
    mcp: &id015
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id016
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
  layer: agent
  name: Cloudflare (cloudflare, ai-gateway-provider)
  provider: cloudflare
  says: ships the Cloudflare (cloudflare, ai-gateway-provider) SDK or integration code
  source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
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
    agent_band: agent-ready
    agent_readiness: 31.3
    band: strong
    in_catalog: true
    kin_score: 55.1
    mcp: &id017
      status: none
    slug: google-gemini
    status: profiled
    tags: &id018
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini (@ai-sdk/google)
  provider: google-gemini
  says: ships the Google Gemini (@ai-sdk/google) SDK or integration code
  source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
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
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id019
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id020
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI (@ai-sdk/openai)
  provider: openai
  says: ships the OpenAI (@ai-sdk/openai) SDK or integration code
  source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: strong
    in_catalog: true
    kin_score: 55.4
    mcp: &id021
      source: https://openrouter.ai/docs/guides/overview/mcp-server
      status: verified
    slug: openrouter
    status: profiled
    tags: &id022
    - Artificial Intelligence
    - Gateways
    - LLM
    - Router
    url: /providers/openrouter/
  layer: agent
  name: OpenRouter (@openrouter/sdk)
  provider: openrouter
  says: ships the OpenRouter (@openrouter/sdk) SDK or integration code
  source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 57.3
    band: strong
    in_catalog: true
    kin_score: 57.7
    mcp: &id023
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id024
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: PostHog (posthog-node)
  provider: posthog
  says: ships the PostHog (posthog-node) SDK or integration code
  source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
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
    agent_band: agent-ready
    agent_readiness: 49.8
    band: strong
    in_catalog: true
    kin_score: 57.5
    mcp: &id025
      source: https://github.com/replicate/replicate-mcp-code-mode
      status: verified
    slug: replicate
    status: profiled
    tags: &id026
    - Artificial Intelligence
    - Image Generation
    - Language Models
    - Machine Learning
    url: /providers/replicate/
  layer: agent
  name: Replicate (@ai-sdk/replicate)
  provider: replicate
  says: ships the Replicate (@ai-sdk/replicate) SDK or integration code
  source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
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
    kin_score: 80.6
    mcp: &id027
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id028
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry (@sentry/node)
  provider: sentry-system
  says: ships the Sentry (@sentry/node) SDK or integration code
  source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
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
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 48.4
    mcp: &id029
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-vertex-ai
    status: profiled
    tags: &id030
    - Artificial Intelligence
    - Generative AI
    - Google Cloud
    - Machine Learning
    url: /providers/google-vertex-ai/
  layer: agent
  name: Vertex AI (@ai-sdk/google-vertex)
  provider: google-vertex-ai
  says: ships the Vertex AI (@ai-sdk/google-vertex) SDK or integration code
  source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/workflow-automation/activepieces/
providers:
- agent_band: agent-ready
  agent_readiness: 33.8
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id001
  name: 1Password (@1password/sdk)
  slug: 1password
  status: profiled
  tags: *id002
  url: /providers/1password/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id003
  name: Amazon Bedrock (@ai-sdk/amazon-bedrock)
  slug: amazon-bedrock
  status: profiled
  tags: *id004
  url: /providers/amazon-bedrock/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id005
  name: Amazon S3 (@aws-sdk/client-s3)
  slug: amazon-s3
  status: profiled
  tags: *id006
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 87.5
  mcp: *id007
  name: Anthropic (@ai-sdk/anthropic)
  slug: anthropic
  status: profiled
  tags: *id008
  url: /providers/anthropic/
- agent_band: agent-aware
  agent_readiness: 18.7
  band: emerging
  in_catalog: true
  kin_score: 18.4
  mcp: *id009
  name: Autumn (autumn-js, billing)
  slug: autumn
  status: profiled
  tags: *id010
  url: /providers/autumn/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id011
  name: AWS Secrets Manager
  slug: amazon-secrets-manager
  status: profiled
  tags: *id012
  url: /providers/amazon-secrets-manager/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: developing
  in_catalog: true
  kin_score: 44.6
  mcp: *id013
  name: Azure OpenAI (@ai-sdk/azure)
  slug: microsoft-azure-openai
  status: profiled
  tags: *id014
  url: /providers/microsoft-azure-openai/
- agent_band: agent-native
  agent_readiness: 69.6
  band: exemplar
  in_catalog: true
  kin_score: 82.8
  mcp: *id015
  name: Cloudflare (cloudflare, ai-gateway-provider)
  slug: cloudflare
  status: profiled
  tags: *id016
  url: /providers/cloudflare/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: strong
  in_catalog: true
  kin_score: 55.1
  mcp: *id017
  name: Google Gemini (@ai-sdk/google)
  slug: google-gemini
  status: profiled
  tags: *id018
  url: /providers/google-gemini/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id019
  name: OpenAI (@ai-sdk/openai)
  slug: openai
  status: profiled
  tags: *id020
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: strong
  in_catalog: true
  kin_score: 55.4
  mcp: *id021
  name: OpenRouter (@openrouter/sdk)
  slug: openrouter
  status: profiled
  tags: *id022
  url: /providers/openrouter/
- agent_band: agent-ready
  agent_readiness: 57.3
  band: strong
  in_catalog: true
  kin_score: 57.7
  mcp: *id023
  name: PostHog (posthog-node)
  slug: posthog
  status: profiled
  tags: *id024
  url: /providers/posthog/
- agent_band: agent-ready
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 57.5
  mcp: *id025
  name: Replicate (@ai-sdk/replicate)
  slug: replicate
  status: profiled
  tags: *id026
  url: /providers/replicate/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id027
  name: Sentry (@sentry/node)
  slug: sentry-system
  status: profiled
  tags: *id028
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.4
  mcp: *id029
  name: Vertex AI (@ai-sdk/google-vertex)
  slug: google-vertex-ai
  status: profiled
  tags: *id030
  url: /providers/google-vertex-ai/
siblings:
- name: Automatisch
  rows: 76
  url: /applications/workflow-automation/automatisch/
- name: Huginn
  rows: 25
  url: /applications/workflow-automation/huginn/
- name: IFTTT
  rows: 3
  url: /applications/workflow-automation/ifttt/
- name: Microsoft Power Automate
  rows: 1
  url: /applications/workflow-automation/microsoft-power-automate/
- name: n8n
  rows: 39
  url: /applications/workflow-automation/n8n/
- name: Windmill
  rows: 12
  url: /applications/workflow-automation/windmill/
sitemap: true
title: 'Activepieces: Workflow Automation & iPaaS reference app'
---
