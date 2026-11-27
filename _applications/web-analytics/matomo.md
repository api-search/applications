---
app: Matomo
app_slug: matomo
app_url: https://github.com/matomo-org/matomo
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: domain
  name: Content Management
  providers:
  - Squarespace
  - Webflow
  - Wix
  - WordPress
  url: /capabilities/content-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2120.40
  key: customer-information-consent-management
  layer: domain
  name: Customer Information & Consent Management
  providers:
  - CookieYes
  - Didomi
  - OneTrust
  - Osano
  - Usercentrics
  url: /capabilities/customer-information-consent-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: domain
  name: IP Geolocation
  providers:
  - MaxMind GeoIP2
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: domain
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
- attribution: Turbo EA
  id: BC-610.60
  key: artificial-intelligence-management
  layer: common
  name: Artificial Intelligence Management
  providers:
  - Amazon Bedrock
  - Anthropic
  - Google Gemini
  - OpenAI
  url: /capabilities/artificial-intelligence-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - Cloudflare
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - ASPSMS
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: web-analytics
  name: Web & Product Analytics
  url: /applications/web-analytics/
counts:
  declared: 12
  observed: 6
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/composer.json
- route: documentation
  url: https://matomo.org/integrations/
- route: source code
  url: https://github.com/matomo-org/matomo/tree/5.x-dev/plugins/MobileMessaging/SMSProvider
- route: source code
  url: https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/plugins/AIProviders/README.md
integrations:
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 48.3
    band: strong
    in_catalog: true
    kin_score: 64.3
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-bedrock
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Artificial Intelligence
    - Foundation Models
    - Generative AI
    url: /providers/amazon-bedrock/
  layer: common
  name: Amazon Bedrock
  provider: amazon-bedrock
  says: ships the Amazon Bedrock SDK or integration code
  source: https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/plugins/AIProviders/README.md
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id003
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id004
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: common
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/plugins/AIProviders/README.md
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.4
    band: thin
    in_catalog: true
    kin_score: 28.0
    mcp: &id005
      status: unknown
    slug: aspsms
    status: profiled
    tags: &id006
    - Business
    - Communications
    - Messaging
    - SMS
    url: /providers/aspsms/
  layer: common
  name: ASPSMS
  provider: aspsms
  says: ships the ASPSMS SDK or integration code
  source: https://github.com/matomo-org/matomo/tree/5.x-dev/plugins/MobileMessaging/SMSProvider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id013
      status: none
    slug: google-gemini
    status: profiled
    tags: &id014
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: common
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/plugins/AIProviders/README.md
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 31.5
    mcp: &id017
      status: none
    slug: maxmind
    status: profiled
    tags: &id018
    - Fraud Prevention
    - Geolocation
    - IP Intelligence
    - Risk Scoring
    url: /providers/maxmind/
  layer: domain
  name: MaxMind GeoIP2
  provider: maxmind
  says: ships the MaxMind GeoIP2 SDK or integration code
  source: https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id021
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id022
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: common
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://raw.githubusercontent.com/matomo-org/matomo/5.x-dev/plugins/AIProviders/README.md
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 69.4
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id007
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id008
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
  layer: common
  name: Cloudflare
  provider: cloudflare
  says: lists Cloudflare as an integration
  source: https://matomo.org/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2120.40
    key: customer-information-consent-management
    name: Customer Information & Consent Management
    url: /capabilities/customer-information-consent-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.3
    band: thin
    in_catalog: true
    kin_score: 31.9
    mcp: &id009
      status: none
    slug: cookieyes
    status: profiled
    tags: &id010
    - Company
    - Consent Management
    - GDPR
    - Privacy
    url: /providers/cookieyes/
  layer: domain
  name: CookieYes
  provider: cookieyes
  says: lists CookieYes as an integration
  source: https://matomo.org/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2120.40
    key: customer-information-consent-management
    name: Customer Information & Consent Management
    url: /capabilities/customer-information-consent-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.8
    band: exemplar
    in_catalog: true
    kin_score: 78.8
    mcp: &id011
      status: none
    slug: didomi
    status: profiled
    tags: &id012
    - AdTech
    - Advertising
    - CCPA
    - CMP
    url: /providers/didomi/
  layer: domain
  name: Didomi
  provider: didomi
  says: lists Didomi as an integration
  source: https://matomo.org/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id015
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id016
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: domain
  name: Google Tag Manager
  provider: google-tag-manager
  says: lists Google Tag Manager as an integration
  source: https://matomo.org/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2120.40
    key: customer-information-consent-management
    name: Customer Information & Consent Management
    url: /capabilities/customer-information-consent-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 57.2
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id019
      status: none
    slug: onetrust
    status: profiled
    tags: &id020
    - Compliance
    - Consent
    - GRC
    - Privacy
    url: /providers/onetrust/
  layer: domain
  name: OneTrust
  provider: onetrust
  says: lists OneTrust as an integration
  source: https://matomo.org/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2120.40
    key: customer-information-consent-management
    name: Customer Information & Consent Management
    url: /capabilities/customer-information-consent-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: strong
    in_catalog: true
    kin_score: 54.3
    mcp: &id023
      status: none
    slug: osano
    status: profiled
    tags: &id024
    - Company
    - Compliance
    - Consent Management
    - Privacy
    url: /providers/osano/
  layer: domain
  name: Osano
  provider: osano
  says: lists Osano as an integration
  source: https://matomo.org/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id025
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id026
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://matomo.org/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 48.5
    band: exemplar
    in_catalog: true
    kin_score: 68.7
    mcp: &id027
      status: none
    slug: squarespace
    status: profiled
    tags: &id028
    - Commerce
    - E-Commerce
    - Marketing
    - Payments
    url: /providers/squarespace/
  layer: domain
  name: Squarespace
  provider: squarespace
  says: lists Squarespace as an integration
  source: https://matomo.org/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2120.40
    key: customer-information-consent-management
    name: Customer Information & Consent Management
    url: /capabilities/customer-information-consent-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.1
    band: thin
    in_catalog: true
    kin_score: 37.1
    mcp: &id029
      status: none
    slug: usercentrics
    status: profiled
    tags: &id030
    - CMP
    - Compliance
    - Consent
    - Privacy
    url: /providers/usercentrics/
  layer: domain
  name: Usercentrics
  provider: usercentrics
  says: lists Usercentrics as an integration
  source: https://matomo.org/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.5
    band: strong
    in_catalog: true
    kin_score: 60.5
    mcp: &id031
      source: https://developers.webflow.com/mcp/reference/overview
      status: verified
    slug: webflow
    status: profiled
    tags: &id032
    - CMS
    - E-Commerce
    - No-Code
    - Web Development
    url: /providers/webflow/
  layer: domain
  name: Webflow
  provider: webflow
  says: lists Webflow as an integration
  source: https://matomo.org/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.2
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id033
      source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
      status: verified
    slug: wix
    status: profiled
    tags: &id034
    - CMS
    - E-Commerce
    - Headless
    - Website Builder
    url: /providers/wix/
  layer: domain
  name: Wix
  provider: wix
  says: lists Wix as an integration
  source: https://matomo.org/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id035
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id036
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
  layer: domain
  name: WordPress
  provider: wordpress
  says: lists WordPress as an integration
  source: https://matomo.org/integrations/
  tier: declared
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/web-analytics/matomo/
providers:
- agent_band: agent-native
  agent_readiness: 48.3
  band: strong
  in_catalog: true
  kin_score: 64.3
  mcp: *id001
  name: Amazon Bedrock
  slug: amazon-bedrock
  status: profiled
  tags: *id002
  url: /providers/amazon-bedrock/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id003
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id004
  url: /providers/anthropic/
- agent_band: agent-aware
  agent_readiness: 14.4
  band: thin
  in_catalog: true
  kin_score: 28.0
  mcp: *id005
  name: ASPSMS
  slug: aspsms
  status: profiled
  tags: *id006
  url: /providers/aspsms/
- agent_band: agent-native
  agent_readiness: 69.4
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id007
  name: Cloudflare
  slug: cloudflare
  status: profiled
  tags: *id008
  url: /providers/cloudflare/
- agent_band: agent-ready
  agent_readiness: 29.3
  band: thin
  in_catalog: true
  kin_score: 31.9
  mcp: *id009
  name: CookieYes
  slug: cookieyes
  status: profiled
  tags: *id010
  url: /providers/cookieyes/
- agent_band: agent-ready
  agent_readiness: 31.8
  band: exemplar
  in_catalog: true
  kin_score: 78.8
  mcp: *id011
  name: Didomi
  slug: didomi
  status: profiled
  tags: *id012
  url: /providers/didomi/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id013
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id014
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id015
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id016
  url: /providers/google-tag-manager/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id017
  name: MaxMind GeoIP2
  slug: maxmind
  status: profiled
  tags: *id018
  url: /providers/maxmind/
- agent_band: agent-ready
  agent_readiness: 57.2
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id019
  name: OneTrust
  slug: onetrust
  status: profiled
  tags: *id020
  url: /providers/onetrust/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id021
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id022
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: strong
  in_catalog: true
  kin_score: 54.3
  mcp: *id023
  name: Osano
  slug: osano
  status: profiled
  tags: *id024
  url: /providers/osano/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id025
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id026
  url: /providers/shopify/
- agent_band: agent-native
  agent_readiness: 48.5
  band: exemplar
  in_catalog: true
  kin_score: 68.7
  mcp: *id027
  name: Squarespace
  slug: squarespace
  status: profiled
  tags: *id028
  url: /providers/squarespace/
- agent_band: agent-aware
  agent_readiness: 20.1
  band: thin
  in_catalog: true
  kin_score: 37.1
  mcp: *id029
  name: Usercentrics
  slug: usercentrics
  status: profiled
  tags: *id030
  url: /providers/usercentrics/
- agent_band: agent-ready
  agent_readiness: 62.5
  band: strong
  in_catalog: true
  kin_score: 60.5
  mcp: *id031
  name: Webflow
  slug: webflow
  status: profiled
  tags: *id032
  url: /providers/webflow/
- agent_band: agent-ready
  agent_readiness: 47.2
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id033
  name: Wix
  slug: wix
  status: profiled
  tags: *id034
  url: /providers/wix/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id035
  name: WordPress
  slug: wordpress
  status: profiled
  tags: *id036
  url: /providers/wordpress/
siblings:
- name: Amplitude
  rows: 50
  url: /applications/web-analytics/amplitude/
- name: Google Analytics
  rows: 4
  url: /applications/web-analytics/google-analytics/
- name: Mixpanel
  rows: 12
  url: /applications/web-analytics/mixpanel/
- name: Plausible
  rows: 16
  url: /applications/web-analytics/plausible/
- name: PostHog
  rows: 42
  url: /applications/web-analytics/posthog/
- name: Umami
  rows: 4
  url: /applications/web-analytics/umami/
sitemap: true
title: 'Matomo: Web & Product Analytics reference app'
---
