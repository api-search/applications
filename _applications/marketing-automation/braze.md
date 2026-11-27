---
app: Braze
app_slug: braze
app_url: https://www.braze.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: domain
  name: Customer Data Management
  providers:
  - Census (Fivetran Activations)
  - Hightouch
  - mParticle
  - RudderStack
  - Segment
  - Tealium
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Criteo
  - Facebook
  - Google
  - LinkedIn
  - Pinterest
  - Snapchat
  - The Trade Desk
  - TikTok
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-912
  key: AE-912
  layer: domain
  name: Direct Mail APIs
  providers:
  - Lob
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: domain
  name: Mobile Attribution & Deep Linking
  providers:
  - Adjust
  - AppsFlyer
  - Branch (branch.io)
  - Kochava
  - Singular
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Snowflake
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Zendesk
  url: /capabilities/customer-service-management/
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
  id: BC-4280
  key: product-telemetry-experimentation-management
  layer: common
  name: Product Telemetry & Experimentation Management
  providers:
  - Optimizely
  url: /capabilities/product-telemetry-experimentation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Amplitude
  - Mixpanel
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: Turbo EA
  id: BC-610.60
  key: artificial-intelligence-management
  layer: agent
  name: Artificial Intelligence Management
  providers:
  - Amazon Bedrock
  - Anthropic
  - Google Gemini
  - OpenAI
  url: /capabilities/artificial-intelligence-management/
  via_parent: null
category:
  id: marketing-automation
  name: Marketing Automation & Ads
  url: /applications/marketing-automation/
counts:
  declared: 31
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.braze.com/docs/partners/home
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: thin
    in_catalog: true
    kin_score: 30.9
    mcp: &id001
      status: none
    slug: adjust
    status: profiled
    tags: &id002
    - Analytics
    - Attribution
    - Deep Linking
    - Measurements
    url: /providers/adjust/
  layer: domain
  name: Adjust
  provider: adjust
  says: lists Adjust as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
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
  name: Amazon Bedrock
  provider: amazon-bedrock
  says: lists Amazon Bedrock as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
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
    agent_readiness: 56.9
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id005
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id006
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: lists Amplitude as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
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
  name: Anthropic
  provider: anthropic
  says: lists Anthropic as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.4
    band: exemplar
    in_catalog: true
    kin_score: 72.1
    mcp: &id009
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id010
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: domain
  name: AppsFlyer
  provider: appsflyer
  says: lists AppsFlyer as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id011
      status: none
    slug: branch-io
    status: profiled
    tags: &id012
    - Company
    url: /providers/branch-io/
  layer: domain
  name: Branch (branch.io)
  provider: branch-io
  says: lists Branch (branch.io) as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.0
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id013
      status: none
    slug: getcensus
    status: profiled
    tags: &id014
    - Census
    - Data Activation
    - Reverse ETL
    - Sync
    url: /providers/getcensus/
  layer: domain
  name: Census (Fivetran Activations)
  provider: getcensus
  says: lists Census (Fivetran Activations) as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.9
    band: strong
    in_catalog: true
    kin_score: 62.2
    mcp: &id015
      status: none
    slug: criteo
    status: profiled
    tags: &id016
    - Advertising
    - Agent Skills
    - Analytics
    - Audiences
    url: /providers/criteo/
  layer: domain
  name: Criteo
  provider: criteo
  says: lists Criteo as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id017
      status: none
    slug: facebook
    status: profiled
    tags: &id018
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: lists Facebook as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.1
    band: exemplar
    in_catalog: true
    kin_score: 73.4
    mcp: &id019
      source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
      status: verified
    slug: google-ads
    status: profiled
    tags: &id020
    - Advertising
    - Campaign Management
    - Digital Advertising
    - Google
    url: /providers/google-ads/
  layer: domain
  name: Google
  provider: google-ads
  says: lists Google as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
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
    mcp: &id021
      status: none
    slug: google-gemini
    status: profiled
    tags: &id022
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini
  provider: google-gemini
  says: lists Google Gemini as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.8
    band: exemplar
    in_catalog: true
    kin_score: 66.9
    mcp: &id023
      source: https://hightouch.com/docs/ai-integrations/mcp
      status: documented
    slug: hightouch
    status: profiled
    tags: &id024
    - Audience Management
    - CDP
    - Data Activation
    - Reverse ETL
    url: /providers/hightouch/
  layer: domain
  name: Hightouch
  provider: hightouch
  says: lists Hightouch as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id025
      status: unchecked
    slug: kochava
    status: queued for profiling
    tags: &id026 []
    url: null
  layer: domain
  name: Kochava
  provider: kochava
  says: lists Kochava as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.5
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id027
      status: none
    slug: linkedin
    status: profiled
    tags: &id028
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: lists LinkedIn as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-912
    key: AE-912
    name: Direct Mail APIs
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 44.3
    band: developing
    in_catalog: true
    kin_score: 52.8
    mcp: &id029
      status: none
    slug: lob
    status: profiled
    tags: &id030
    - Address Verification
    - Direct Mail
    - Print
    url: /providers/lob/
  layer: domain
  name: Lob
  provider: lob
  says: lists Lob as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
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
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id031
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id032
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: lists Mixpanel as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: strong
    in_catalog: true
    kin_score: 59.5
    mcp: &id033
      status: none
    slug: mparticle
    status: profiled
    tags: &id034
    - Analytics
    - CDP
    - Customer Data Platform
    - Identity Resolution
    url: /providers/mparticle/
  layer: domain
  name: mParticle
  provider: mparticle
  says: lists mParticle as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
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
    mcp: &id035
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id036
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: lists OpenAI as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 61.6
    band: exemplar
    in_catalog: true
    kin_score: 78.1
    mcp: &id037
      source: https://support.optimizely.com/hc/en-us/articles/45320607594893
      status: documented
    slug: optimizely
    status: profiled
    tags: &id038
    - A/B Testing
    - Content Management
    - Customer Data
    - E-Commerce
    url: /providers/optimizely/
  layer: common
  name: Optimizely
  provider: optimizely
  says: lists Optimizely as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: developing
    in_catalog: true
    kin_score: 47.7
    mcp: &id039
      source: https://developers.pinterest.com/about-pinterest-mcp/
      status: verified
    slug: pinterest
    status: profiled
    tags: &id040
    - Image
    - Social
    - Social Media
    - Video
    url: /providers/pinterest/
  layer: domain
  name: Pinterest
  provider: pinterest
  says: lists Pinterest as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.9
    band: exemplar
    in_catalog: true
    kin_score: 79.1
    mcp: &id041
      source: https://github.com/rudderlabs/rudderstack-mcp
      status: verified
    slug: rudderstack
    status: profiled
    tags: &id042
    - CDP
    - Customer Data Platform
    - Data Pipeline
    - Open Source
    url: /providers/rudderstack/
  layer: domain
  name: RudderStack
  provider: rudderstack
  says: lists RudderStack as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id043
      status: none
    slug: segment
    status: profiled
    tags: &id044
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: domain
  name: Segment
  provider: segment
  says: lists Segment as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.9
    band: strong
    in_catalog: true
    kin_score: 65.9
    mcp: &id045
      status: none
    slug: singular
    status: profiled
    tags: &id046
    - Attribution
    - Company
    - Marketing Analytics
    - Mobile Attribution
    url: /providers/singular/
  layer: domain
  name: Singular
  provider: singular
  says: lists Singular as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.1
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id047
      status: none
    slug: snapchat
    status: profiled
    tags: &id048
    - Advertising
    - Augmented Reality
    - Marketing
    - Messaging
    url: /providers/snapchat/
  layer: domain
  name: Snapchat
  provider: snapchat
  says: lists Snapchat as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 44.9
    band: exemplar
    in_catalog: true
    kin_score: 82.3
    mcp: &id049
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id050
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
  layer: common
  name: Snowflake
  provider: snowflake
  says: lists Snowflake as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
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
    mcp: &id051
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id052
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: exemplar
    in_catalog: true
    kin_score: 66.5
    mcp: &id053
      source: https://docs.tealium.com/server-side/config-mcp/about-config-mcp/
      status: documented
    slug: tealium
    status: profiled
    tags: &id054
    - AudienceStream
    - CDP
    - Customer Data Platform
    - Tag Management
    url: /providers/tealium/
  layer: domain
  name: Tealium
  provider: tealium
  says: lists Tealium as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.3
    band: strong
    in_catalog: true
    kin_score: 57.5
    mcp: &id055
      status: none
    slug: trade-desk
    status: profiled
    tags: &id056
    - AdTech
    - Advertising
    - DSP
    - Programmatic Advertising
    url: /providers/trade-desk/
  layer: domain
  name: The Trade Desk
  provider: trade-desk
  says: lists The Trade Desk as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: developing
    in_catalog: true
    kin_score: 40.5
    mcp: &id057
      status: none
    slug: tiktok
    status: profiled
    tags: &id058
    - Advertising
    - Commerce
    - Content
    - TikTok
    url: /providers/tiktok/
  layer: domain
  name: TikTok
  provider: tiktok
  says: lists TikTok as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id059
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id060
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id061
      status: none
    slug: zendesk
    status: profiled
    tags: &id062
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: common
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://www.braze.com/docs/partners/home
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/marketing-automation/braze/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: thin
  in_catalog: true
  kin_score: 30.9
  mcp: *id001
  name: Adjust
  slug: adjust
  status: profiled
  tags: *id002
  url: /providers/adjust/
- agent_band: agent-native
  agent_readiness: 48.3
  band: strong
  in_catalog: true
  kin_score: 64.3
  mcp: *id003
  name: Amazon Bedrock
  slug: amazon-bedrock
  status: profiled
  tags: *id004
  url: /providers/amazon-bedrock/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id005
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id006
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id007
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id008
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id009
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id010
  url: /providers/appsflyer/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id011
  name: Branch (branch.io)
  slug: branch-io
  status: profiled
  tags: *id012
  url: /providers/branch-io/
- agent_band: agent-aware
  agent_readiness: 26.0
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id013
  name: Census (Fivetran Activations)
  slug: getcensus
  status: profiled
  tags: *id014
  url: /providers/getcensus/
- agent_band: agent-ready
  agent_readiness: 38.9
  band: strong
  in_catalog: true
  kin_score: 62.2
  mcp: *id015
  name: Criteo
  slug: criteo
  status: profiled
  tags: *id016
  url: /providers/criteo/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id017
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id018
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 73.4
  mcp: *id019
  name: Google
  slug: google-ads
  status: profiled
  tags: *id020
  url: /providers/google-ads/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id021
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id022
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 62.8
  band: exemplar
  in_catalog: true
  kin_score: 66.9
  mcp: *id023
  name: Hightouch
  slug: hightouch
  status: profiled
  tags: *id024
  url: /providers/hightouch/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id025
  name: Kochava
  slug: kochava
  status: queued for profiling
  tags: *id026
  url: null
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id027
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id028
  url: /providers/linkedin/
- agent_band: agent-native
  agent_readiness: 44.3
  band: developing
  in_catalog: true
  kin_score: 52.8
  mcp: *id029
  name: Lob
  slug: lob
  status: profiled
  tags: *id030
  url: /providers/lob/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id031
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id032
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: strong
  in_catalog: true
  kin_score: 59.5
  mcp: *id033
  name: mParticle
  slug: mparticle
  status: profiled
  tags: *id034
  url: /providers/mparticle/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id035
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id036
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 61.6
  band: exemplar
  in_catalog: true
  kin_score: 78.1
  mcp: *id037
  name: Optimizely
  slug: optimizely
  status: profiled
  tags: *id038
  url: /providers/optimizely/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id039
  name: Pinterest
  slug: pinterest
  status: profiled
  tags: *id040
  url: /providers/pinterest/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: exemplar
  in_catalog: true
  kin_score: 79.1
  mcp: *id041
  name: RudderStack
  slug: rudderstack
  status: profiled
  tags: *id042
  url: /providers/rudderstack/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id043
  name: Segment
  slug: segment
  status: profiled
  tags: *id044
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 48.9
  band: strong
  in_catalog: true
  kin_score: 65.9
  mcp: *id045
  name: Singular
  slug: singular
  status: profiled
  tags: *id046
  url: /providers/singular/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id047
  name: Snapchat
  slug: snapchat
  status: profiled
  tags: *id048
  url: /providers/snapchat/
- agent_band: agent-native
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 82.3
  mcp: *id049
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id050
  url: /providers/snowflake/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id051
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id052
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: exemplar
  in_catalog: true
  kin_score: 66.5
  mcp: *id053
  name: Tealium
  slug: tealium
  status: profiled
  tags: *id054
  url: /providers/tealium/
- agent_band: agent-ready
  agent_readiness: 43.3
  band: strong
  in_catalog: true
  kin_score: 57.5
  mcp: *id055
  name: The Trade Desk
  slug: trade-desk
  status: profiled
  tags: *id056
  url: /providers/trade-desk/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: developing
  in_catalog: true
  kin_score: 40.5
  mcp: *id057
  name: TikTok
  slug: tiktok
  status: profiled
  tags: *id058
  url: /providers/tiktok/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id059
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id060
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id061
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id062
  url: /providers/zendesk/
siblings:
- name: Customer.io
  rows: 21
  url: /applications/marketing-automation/customer-io/
- name: Dittofeed
  rows: 14
  url: /applications/marketing-automation/dittofeed/
- name: HubSpot Marketing Hub
  rows: 15
  url: /applications/marketing-automation/hubspot-marketing-hub/
- name: Laudspeaker
  rows: 13
  url: /applications/marketing-automation/laudspeaker/
- name: Mailchimp
  rows: 5
  url: /applications/marketing-automation/mailchimp/
- name: Mautic
  rows: 31
  url: /applications/marketing-automation/mautic/
sitemap: true
title: 'Braze: Marketing Automation & Ads reference app'
---
