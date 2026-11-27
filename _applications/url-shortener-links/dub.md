---
app: Dub
app_slug: dub
app_url: https://github.com/dubinc/dub
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Tinybird
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: domain
  name: Customer Data Management
  providers:
  - Twilio Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Google Ads
  - Stripe
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-927
  key: AE-927
  layer: domain
  name: Domain Registration & Managed DNS
  providers:
  - Dynadot
  - Vercel Domains API
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-230.20.10
  key: AE-230.20.10
  layer: domain
  name: Exchange Rates
  providers:
  - CurrencyAPI
  url: /capabilities/market-financial-data/
  via_parent: Market & Financial Data
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
  id: AE-913
  key: AE-913
  layer: domain
  name: Link Shortening & Link-in-Bio
  providers:
  - Bitly
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: domain
  name: Mobile Attribution & Deep Linking
  providers:
  - AppsFlyer
  - Singular
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Plain
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - PlanetScale
  - Upstash
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Axiom
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
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: common
  name: Photo & Image Libraries
  providers:
  - Unsplash
  url: /capabilities/photo-image-libraries/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - GitHub
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Resend
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-230.40.10
  key: AE-230.40.10
  layer: common
  name: Web Scraping
  providers:
  - Firecrawl
  url: /capabilities/web-data/
  via_parent: Web Data
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Anthropic
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: url-shortener-links
  name: Link Management & URL Shorteners
  url: /applications/url-shortener-links/
counts:
  declared: 0
  observed: 25
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/dubinc/dub/blob/main/apps/web/package.json
- route: source code
  url: https://github.com/dubinc/dub/blob/main/apps/web/.env.example
- route: source code
  url: https://github.com/dubinc/dub/tree/main/apps/web/lib
- route: source code
  url: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations
integrations:
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
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id002
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id003
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/dubinc/dub/blob/main/apps/web/package.json
  tier: observed
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
    mcp: &id004
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id005
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: domain
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/appsflyer
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
    agent_readiness: 45.7
    band: thin
    in_catalog: true
    kin_score: 37.3
    mcp: &id006
      source: https://github.com/axiomhq/mcp-server-axiom
      status: verified
    slug: axiom-co
    status: profiled
    tags: &id007
    - Event Data
    - Log Management
    - Logs
    - Observability
    url: /providers/axiom-co/
  layer: common
  name: Axiom
  provider: axiom-co
  says: ships the Axiom SDK or integration code
  source: https://github.com/dubinc/dub/blob/main/apps/web/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 58.2
    band: exemplar
    in_catalog: true
    kin_score: 73.0
    mcp: &id008
      source: https://dev.bitly.com/bitly-mcp/
      status: verified
    slug: bitly
    status: profiled
    tags: &id009
    - Analytics
    - Links
    - QR Codes
    - URL Shorteners
    url: /providers/bitly/
  layer: domain
  name: Bitly
  provider: bitly
  says: ships the Bitly SDK or integration code
  source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/bitly
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.10
    key: AE-230.20.10
    name: Exchange Rates
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.8
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id010
      source: https://currencyapi.com/docs/mcp
      status: verified
    slug: currencyapi
    status: profiled
    tags: &id011
    - Currency
    - Currency Conversion
    - Exchange Rates
    - Foreign Exchange
    url: /providers/currencyapi/
  layer: domain
  name: CurrencyAPI
  provider: currencyapi
  says: ships the CurrencyAPI SDK or integration code
  source: https://github.com/dubinc/dub/tree/main/apps/web/lib/currencyapi
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.0
    mcp: &id012
      source: https://www.dynadot.com/domain/mcp
      status: verified
    slug: dynadot
    status: profiled
    tags: &id013
    - Company
    - DNS Management
    - Domain Registrar
    - Marketplace
    url: /providers/dynadot/
  layer: domain
  name: Dynadot
  provider: dynadot
  says: ships the Dynadot SDK or integration code
  source: https://github.com/dubinc/dub/tree/main/apps/web/lib/dynadot
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.10
    key: AE-230.40.10
    name: Web Scraping
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.7
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id014
      source: https://docs.firecrawl.dev/mcp-server
      status: verified
    slug: firecrawl
    status: profiled
    tags: &id015
    - Crawling
    - Data Extraction
    - URLs
    - Web Scraping
    url: /providers/firecrawl/
  layer: common
  name: Firecrawl
  provider: firecrawl
  says: ships the Firecrawl SDK or integration code
  source: https://github.com/dubinc/dub/blob/main/apps/web/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id016
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id017
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/dubinc/dub/blob/main/apps/web/.env.example
  tier: observed
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
    mcp: &id018
      source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
      status: verified
    slug: google-ads
    status: profiled
    tags: &id019
    - Advertising
    - Campaign Management
    - Digital Advertising
    - Google
    url: /providers/google-ads/
  layer: domain
  name: Google Ads
  provider: google-ads
  says: ships the Google Ads SDK or integration code
  source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/google-ads
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id020
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id021
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/dubinc/dub/blob/main/apps/web/.env.example
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id022
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id023
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: ships the HubSpot SDK or integration code
  source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/hubspot
  tier: observed
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
    agent_readiness: 50.3
    band: strong
    in_catalog: true
    kin_score: 61.8
    mcp: &id024
      source: https://github.com/team-plain/cursor-plugin-mcp
      status: verified
    slug: plain
    status: profiled
    tags: &id025
    - Company
    - Customer Service
    - Help Desk
    - Support
    url: /providers/plain/
  layer: common
  name: Plain
  provider: plain
  says: ships the Plain SDK or integration code
  source: https://github.com/dubinc/dub/blob/main/apps/web/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: thin
    in_catalog: true
    kin_score: 28.0
    mcp: &id026
      source: https://github.com/planetscale/mcp-server
      status: verified
    slug: planetscale
    status: profiled
    tags: &id027
    - Database
    - MySQL
    - PostgreSQL
    - Serverless
    url: /providers/planetscale/
  layer: common
  name: PlanetScale
  provider: planetscale
  says: ships the PlanetScale SDK or integration code
  source: https://github.com/dubinc/dub/blob/main/apps/web/package.json
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
    agent_readiness: 49.8
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id028
      source: https://resend.com/docs/mcp-server
      status: verified
    slug: resend
    status: profiled
    tags: &id029
    - Developer Tools
    - Email
    - Marketing Email
    - Transactional Email
    url: /providers/resend/
  layer: common
  name: Resend
  provider: resend
  says: ships the Resend SDK or integration code
  source: https://github.com/dubinc/dub/blob/main/apps/web/.env.example
  tier: observed
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
    mcp: &id030
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id031
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: ships the Shopify SDK or integration code
  source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/shopify
  tier: observed
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
    mcp: &id032
      status: none
    slug: singular
    status: profiled
    tags: &id033
    - Attribution
    - Company
    - Marketing Analytics
    - Mobile Attribution
    url: /providers/singular/
  layer: domain
  name: Singular
  provider: singular
  says: ships the Singular SDK or integration code
  source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/singular
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id034
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id035
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/slack
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id036
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id037
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/stripe
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/dubinc/dub/blob/main/apps/web/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: developing
    in_catalog: true
    kin_score: 46.4
    mcp: &id038
      source: https://www.tinybird.co/docs/forward/analytics-agents/mcp
      status: verified
    slug: tinybird
    status: profiled
    tags: &id039
    - Analytics
    - Data
    - Real-Time
    - SQL
    url: /providers/tinybird/
  layer: domain
  name: Tinybird
  provider: tinybird
  says: ships the Tinybird SDK or integration code
  source: https://github.com/dubinc/dub/blob/main/apps/web/.env.example
  tier: observed
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
    mcp: &id040
      status: none
    slug: segment
    status: profiled
    tags: &id041
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: domain
  name: Twilio Segment
  provider: segment
  says: ships the Twilio Segment SDK or integration code
  source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/segment
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.6
    band: developing
    in_catalog: true
    kin_score: 39.4
    mcp: &id042
      status: none
    slug: unsplash
    status: profiled
    tags: &id043
    - Image
    - Photography
    - Photos
    - Stock Photos
    url: /providers/unsplash/
  layer: common
  name: Unsplash
  provider: unsplash
  says: ships the Unsplash SDK or integration code
  source: https://github.com/dubinc/dub/blob/main/apps/web/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.7
    band: thin
    in_catalog: true
    kin_score: 35.2
    mcp: &id044
      source: https://github.com/upstash/mcp-server
      status: verified
    slug: upstash
    status: profiled
    tags: &id045
    - Kafka
    - Messaging
    - Redis
    - Serverless
    url: /providers/upstash/
  layer: common
  name: Upstash
  provider: upstash
  says: ships the Upstash SDK or integration code
  source: https://github.com/dubinc/dub/blob/main/apps/web/package.json
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
    agent_readiness: 50.0
    band: strong
    in_catalog: true
    kin_score: 63.1
    mcp: &id046
      source: https://vercel.com/docs/mcp/vercel-mcp
      status: verified
    slug: vercel
    status: profiled
    tags: &id047
    - AI Gateway
    - Gateways
    - Observability
    - Webhook
    url: /providers/vercel/
  layer: domain
  name: Vercel Domains API
  provider: vercel
  says: ships the Vercel Domains API SDK or integration code
  source: https://github.com/dubinc/dub/blob/main/apps/web/.env.example
  tier: observed
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
    mcp: &id048
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id049
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: ships the Zapier SDK or integration code
  source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/zapier
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/url-shortener-links/dub/
providers:
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id002
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id003
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id004
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id005
  url: /providers/appsflyer/
- agent_band: agent-ready
  agent_readiness: 45.7
  band: thin
  in_catalog: true
  kin_score: 37.3
  mcp: *id006
  name: Axiom
  slug: axiom-co
  status: profiled
  tags: *id007
  url: /providers/axiom-co/
- agent_band: agent-ready
  agent_readiness: 58.2
  band: exemplar
  in_catalog: true
  kin_score: 73.0
  mcp: *id008
  name: Bitly
  slug: bitly
  status: profiled
  tags: *id009
  url: /providers/bitly/
- agent_band: agent-ready
  agent_readiness: 32.8
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id010
  name: CurrencyAPI
  slug: currencyapi
  status: profiled
  tags: *id011
  url: /providers/currencyapi/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.0
  mcp: *id012
  name: Dynadot
  slug: dynadot
  status: profiled
  tags: *id013
  url: /providers/dynadot/
- agent_band: agent-ready
  agent_readiness: 40.7
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id014
  name: Firecrawl
  slug: firecrawl
  status: profiled
  tags: *id015
  url: /providers/firecrawl/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id016
  name: GitHub
  slug: github
  status: profiled
  tags: *id017
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 73.4
  mcp: *id018
  name: Google Ads
  slug: google-ads
  status: profiled
  tags: *id019
  url: /providers/google-ads/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id020
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id021
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id022
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id023
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: strong
  in_catalog: true
  kin_score: 61.8
  mcp: *id024
  name: Plain
  slug: plain
  status: profiled
  tags: *id025
  url: /providers/plain/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: thin
  in_catalog: true
  kin_score: 28.0
  mcp: *id026
  name: PlanetScale
  slug: planetscale
  status: profiled
  tags: *id027
  url: /providers/planetscale/
- agent_band: agent-ready
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id028
  name: Resend
  slug: resend
  status: profiled
  tags: *id029
  url: /providers/resend/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id030
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id031
  url: /providers/shopify/
- agent_band: agent-ready
  agent_readiness: 48.9
  band: strong
  in_catalog: true
  kin_score: 65.9
  mcp: *id032
  name: Singular
  slug: singular
  status: profiled
  tags: *id033
  url: /providers/singular/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id034
  name: Slack
  slug: slack
  status: profiled
  tags: *id035
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id036
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id037
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: developing
  in_catalog: true
  kin_score: 46.4
  mcp: *id038
  name: Tinybird
  slug: tinybird
  status: profiled
  tags: *id039
  url: /providers/tinybird/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id040
  name: Twilio Segment
  slug: segment
  status: profiled
  tags: *id041
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 52.6
  band: developing
  in_catalog: true
  kin_score: 39.4
  mcp: *id042
  name: Unsplash
  slug: unsplash
  status: profiled
  tags: *id043
  url: /providers/unsplash/
- agent_band: agent-ready
  agent_readiness: 46.7
  band: thin
  in_catalog: true
  kin_score: 35.2
  mcp: *id044
  name: Upstash
  slug: upstash
  status: profiled
  tags: *id045
  url: /providers/upstash/
- agent_band: agent-ready
  agent_readiness: 50.0
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id046
  name: Vercel Domains API
  slug: vercel
  status: profiled
  tags: *id047
  url: /providers/vercel/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id048
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id049
  url: /providers/zapier/
siblings:
- name: Bitly
  rows: 55
  url: /applications/url-shortener-links/bitly/
- name: Kutt
  rows: 1
  url: /applications/url-shortener-links/kutt/
- name: Shlink
  rows: 6
  url: /applications/url-shortener-links/shlink/
- name: Short.io
  rows: 8
  url: /applications/url-shortener-links/short-io/
- name: Sink
  rows: 5
  url: /applications/url-shortener-links/sink/
- name: YOURLS
  rows: 2
  url: /applications/url-shortener-links/yourls/
sitemap: true
title: 'Dub: Link Management & URL Shorteners reference app'
---
