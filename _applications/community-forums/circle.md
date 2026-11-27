---
app: Circle
app_slug: circle
app_url: https://circle.so/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.70.10
  key: AE-170.70.10
  layer: domain
  name: Link Unfurling & Rich Embeds
  providers:
  - Instagram
  - Loom
  - Simplecast
  - SoundCloud
  - Spotify
  - Twitter / X
  - Vimeo
  - Wistia
  - YouTube
  url: /capabilities/content-management/
  via_parent: Content Management
- attribution: API Evangelist extension
  id: AE-220.10
  key: AE-220.10
  layer: domain
  name: Online Courses
  providers:
  - Kajabi
  - Teachable
  url: /capabilities/online-courses/
  via_parent: null
- attribution: Turbo EA
  id: BC-3750.20
  key: subscription-entitlement-management
  layer: domain
  name: Subscription & Entitlement Management
  providers:
  - Memberful
  - MemberSpace
  - Memberstack
  - Outseta
  url: /capabilities/subscription-entitlement-management/
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
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: common
  name: Content Management
  providers:
  - WordPress
  url: /capabilities/content-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Facebook / Meta Pixel
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - ActiveCampaign
  - ConvertKit (Kit)
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-931
  key: AE-931
  layer: common
  name: No-Code App Builders
  providers:
  - Bubble
  url: /capabilities/engineering-productivity-management/
  via_parent: Engineering Productivity Management
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: common
  name: Online Forms & Survey Collection
  providers:
  - Typeform
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - PayPal
  - Stripe
  - ThriveCart
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: common
  name: Spreadsheets & No-Code Databases
  providers:
  - Airtable
  - Google Sheets
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-3740.60
  key: syndication-affiliate-distribution
  layer: common
  name: Syndication & Affiliate Distribution
  providers:
  - Rewardful
  url: /capabilities/syndication-affiliate-distribution/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: common
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Auth0
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Make
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: community-forums
  name: Community & Forums
  url: /applications/community-forums/
counts:
  declared: 36
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://circle.so/integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.0
    band: exemplar
    in_catalog: true
    kin_score: 81.1
    mcp: &id001
      source: https://developers.activecampaign.com/page/mcp
      status: documented
    slug: activecampaign
    status: profiled
    tags: &id002
    - CRM
    - Email Marketing
    - Marketing Automation
    - Sales Automation
    url: /providers/activecampaign/
  layer: common
  name: ActiveCampaign
  provider: activecampaign
  says: lists ActiveCampaign as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.3
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id003
      source: https://github.com/Airtable/airtable-mcp-cli
      status: verified
    slug: airtable
    status: profiled
    tags: &id004
    - Application
    - Collaboration
    - Data
    - Database
    url: /providers/airtable/
  layer: common
  name: Airtable
  provider: airtable
  says: lists Airtable as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.5
    band: exemplar
    in_catalog: true
    kin_score: 71.8
    mcp: &id005
      source: https://auth0.com/docs/get-started/auth0-mcp-server
      status: verified
    slug: auth0
    status: profiled
    tags: &id006
    - AI Agents
    - Auth0
    - Authentication
    - Authorization
    url: /providers/auth0/
  layer: common
  name: Auth0
  provider: auth0
  says: lists Auth0 as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-931
    key: AE-931
    name: No-Code App Builders
    url: /capabilities/engineering-productivity-management/
    via_parent: Engineering Productivity Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.4
    band: developing
    in_catalog: true
    kin_score: 53.8
    mcp: &id007
      status: none
    slug: bubble
    status: profiled
    tags: &id008
    - Application Platform
    - Database
    - No-Code
    - Workflow Automation
    url: /providers/bubble/
  layer: common
  name: Bubble
  provider: bubble
  says: lists Bubble as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 80.4
    mcp: &id009
      status: none
    slug: convertkit
    status: profiled
    tags: &id010
    - Automation
    - Creator Economy
    - Email Marketing
    - Subscribers
    url: /providers/convertkit/
  layer: common
  name: ConvertKit (Kit)
  provider: convertkit
  says: lists ConvertKit (Kit) as an integration
  source: https://circle.so/integrations
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
    mcp: &id011
      status: none
    slug: facebook
    status: profiled
    tags: &id012
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook / Meta Pixel
  provider: facebook
  says: lists Facebook / Meta Pixel as an integration
  source: https://circle.so/integrations
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
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id013
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id014
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id015
      status: none
    slug: google-sheets
    status: profiled
    tags: &id016
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
  layer: common
  name: Google Sheets
  provider: google-sheets
  says: lists Google Sheets as an integration
  source: https://circle.so/integrations
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
    mcp: &id017
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id018
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: lists Google Tag Manager as an integration
  source: https://circle.so/integrations
  tier: declared
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
    mcp: &id019
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id020
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: common
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.6
    band: exemplar
    in_catalog: true
    kin_score: 67.8
    mcp: &id021
      status: none
    slug: instagram
    status: profiled
    tags: &id022
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
  layer: domain
  name: Instagram
  provider: instagram
  says: lists Instagram as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-220.10
    key: AE-220.10
    name: Online Courses
    url: /capabilities/online-courses/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.9
    band: developing
    in_catalog: true
    kin_score: 40.1
    mcp: &id023
      source: https://help.kajabi.com/en/collections/19761100-mcp
      status: documented
    slug: kajabi
    status: profiled
    tags: &id024
    - Creator Economy
    - E-Commerce
    - Membership
    - Online Courses
    url: /providers/kajabi/
  layer: domain
  name: Kajabi
  provider: kajabi
  says: lists Kajabi as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 18.4
    mcp: &id025
      status: none
    slug: loom
    status: profiled
    tags: &id026
    - Async
    - Communications
    - Productivity
    - Video
    url: /providers/loom/
  layer: domain
  name: Loom
  provider: loom
  says: lists Loom as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id027
      status: none
    slug: mailchimp
    status: profiled
    tags: &id028
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://circle.so/integrations
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
    agent_readiness: 43.0
    band: developing
    in_catalog: true
    kin_score: 43.4
    mcp: &id029
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id030
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3750.20
    key: subscription-entitlement-management
    name: Subscription & Entitlement Management
    url: /capabilities/subscription-entitlement-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 12.6
    mcp: &id031
      status: none
    slug: memberful
    status: profiled
    tags: &id032
    - Creators
    - Membership
    - Payments
    - Subscription
    url: /providers/memberful/
  layer: domain
  name: Memberful
  provider: memberful
  says: lists Memberful as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3750.20
    key: subscription-entitlement-management
    name: Subscription & Entitlement Management
    url: /capabilities/subscription-entitlement-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.8
    band: emerging
    in_catalog: true
    kin_score: 24.7
    mcp: &id033
      status: none
    slug: memberspace
    status: profiled
    tags: &id034
    - Community
    - Membership
    - Payments
    - Software-as-a-Service
    url: /providers/memberspace/
  layer: domain
  name: MemberSpace
  provider: memberspace
  says: lists MemberSpace as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3750.20
    key: subscription-entitlement-management
    name: Subscription & Entitlement Management
    url: /capabilities/subscription-entitlement-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.6
    band: developing
    in_catalog: true
    kin_score: 41.5
    mcp: &id035
      source: https://developers.memberstack.com/mcp-server
      status: verified
    slug: memberstack
    status: profiled
    tags: &id036
    - Authentication
    - Membership
    - Software-as-a-Service
    - Webflow
    url: /providers/memberstack/
  layer: domain
  name: Memberstack
  provider: memberstack
  says: lists Memberstack as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3750.20
    key: subscription-entitlement-management
    name: Subscription & Entitlement Management
    url: /capabilities/subscription-entitlement-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id037
      status: unchecked
    slug: outseta
    status: queued for profiling
    tags: &id038 []
    url: null
  layer: domain
  name: Outseta
  provider: outseta
  says: lists Outseta as an integration
  source: https://circle.so/integrations
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
    agent_band: agent-ready
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id039
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id040
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3740.60
    key: syndication-affiliate-distribution
    name: Syndication & Affiliate Distribution
    url: /capabilities/syndication-affiliate-distribution/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: exemplar
    in_catalog: true
    kin_score: 66.7
    mcp: &id041
      status: none
    slug: rewardful
    status: profiled
    tags: &id042
    - Affiliate Tracking
    - Referral Programs
    - Software-as-a-Service
    - Stripe
    url: /providers/rewardful/
  layer: common
  name: Rewardful
  provider: rewardful
  says: lists Rewardful as an integration
  source: https://circle.so/integrations
  tier: declared
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
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id043
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id044
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.7
    band: emerging
    in_catalog: true
    kin_score: 25.9
    mcp: &id045
      status: unknown
    slug: simplecast
    status: profiled
    tags: &id046
    - Podcast Analytics
    - Podcast Distribution
    - Podcast Hosting
    - Podcasts
    url: /providers/simplecast/
  layer: domain
  name: Simplecast
  provider: simplecast
  says: lists Simplecast as an integration
  source: https://circle.so/integrations
  tier: declared
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
    mcp: &id047
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id048
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 30.9
    mcp: &id049
      status: none
    slug: soundcloud
    status: profiled
    tags: &id050
    - Audio
    - Music
    - OAuth
    - Streaming
    url: /providers/soundcloud/
  layer: domain
  name: SoundCloud
  provider: soundcloud
  says: lists SoundCloud as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.7
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id051
      status: none
    slug: spotify
    status: profiled
    tags: &id052
    - Audio
    - Music
    - Podcasts
    - Streaming
    url: /providers/spotify/
  layer: domain
  name: Spotify
  provider: spotify
  says: lists Spotify as an integration
  source: https://circle.so/integrations
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
    mcp: &id053
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id054
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-220.10
    key: AE-220.10
    name: Online Courses
    url: /capabilities/online-courses/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.6
    band: developing
    in_catalog: true
    kin_score: 51.1
    mcp: &id055
      status: none
    slug: teachable
    status: profiled
    tags: &id056
    - Course Management
    - E-Learning
    - Education
    - Online Courses
    url: /providers/teachable/
  layer: domain
  name: Teachable
  provider: teachable
  says: lists Teachable as an integration
  source: https://circle.so/integrations
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
    agent_band: agent-ready
    agent_readiness: 37.1
    band: exemplar
    in_catalog: true
    kin_score: 69.9
    mcp: &id057
      status: none
    slug: thrivecart
    status: profiled
    tags: &id058
    - Checkout
    - Company
    - Payments
    - Shopping Cart
    url: /providers/thrivecart/
  layer: common
  name: ThriveCart
  provider: thrivecart
  says: lists ThriveCart as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id059
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id060
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: Twitter / X
  provider: x
  says: lists Twitter / X as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.6
    band: thin
    in_catalog: true
    kin_score: 36.0
    mcp: &id061
      source: https://www.typeform.com/developers/mcp
      status: verified
    slug: typeform
    status: profiled
    tags: &id062
    - Forms
    - Lead Capture
    - Software-as-a-Service
    - Surveys
    url: /providers/typeform/
  layer: common
  name: Typeform
  provider: typeform
  says: lists Typeform as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: thin
    in_catalog: true
    kin_score: 37.6
    mcp: &id063
      source: https://developer.vimeo.com/api/mcp-server
      status: documented
    slug: vimeo
    status: profiled
    tags: &id064
    - Live Streaming
    - Streaming
    - Video
    - Video Hosting
    url: /providers/vimeo/
  layer: domain
  name: Vimeo
  provider: vimeo
  says: lists Vimeo as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.6
    band: exemplar
    in_catalog: true
    kin_score: 75.5
    mcp: &id065
      source: https://docs.wistia.com/docs/mcp-server-guide
      status: documented
    slug: wistia
    status: profiled
    tags: &id066
    - Lead Generation
    - Video Analytics
    - Video Hosting
    - Video Marketing
    url: /providers/wistia/
  layer: domain
  name: Wistia
  provider: wistia
  says: lists Wistia as an integration
  source: https://circle.so/integrations
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
    mcp: &id067
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id068
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
  layer: common
  name: WordPress
  provider: wordpress
  says: lists WordPress as an integration
  source: https://circle.so/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.4
    band: strong
    in_catalog: true
    kin_score: 65.4
    mcp: &id069
      status: none
    slug: youtube
    status: profiled
    tags: &id070
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: lists YouTube as an integration
  source: https://circle.so/integrations
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
    mcp: &id071
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id072
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://circle.so/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/community-forums/circle/
providers:
- agent_band: agent-ready
  agent_readiness: 51.0
  band: exemplar
  in_catalog: true
  kin_score: 81.1
  mcp: *id001
  name: ActiveCampaign
  slug: activecampaign
  status: profiled
  tags: *id002
  url: /providers/activecampaign/
- agent_band: agent-ready
  agent_readiness: 52.3
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id003
  name: Airtable
  slug: airtable
  status: profiled
  tags: *id004
  url: /providers/airtable/
- agent_band: agent-ready
  agent_readiness: 39.5
  band: exemplar
  in_catalog: true
  kin_score: 71.8
  mcp: *id005
  name: Auth0
  slug: auth0
  status: profiled
  tags: *id006
  url: /providers/auth0/
- agent_band: agent-aware
  agent_readiness: 20.4
  band: developing
  in_catalog: true
  kin_score: 53.8
  mcp: *id007
  name: Bubble
  slug: bubble
  status: profiled
  tags: *id008
  url: /providers/bubble/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 80.4
  mcp: *id009
  name: ConvertKit (Kit)
  slug: convertkit
  status: profiled
  tags: *id010
  url: /providers/convertkit/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id011
  name: Facebook / Meta Pixel
  slug: facebook
  status: profiled
  tags: *id012
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id013
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id014
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id015
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id016
  url: /providers/google-sheets/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id017
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id018
  url: /providers/google-tag-manager/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id019
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id020
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 38.6
  band: exemplar
  in_catalog: true
  kin_score: 67.8
  mcp: *id021
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id022
  url: /providers/instagram/
- agent_band: agent-ready
  agent_readiness: 51.9
  band: developing
  in_catalog: true
  kin_score: 40.1
  mcp: *id023
  name: Kajabi
  slug: kajabi
  status: profiled
  tags: *id024
  url: /providers/kajabi/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 18.4
  mcp: *id025
  name: Loom
  slug: loom
  status: profiled
  tags: *id026
  url: /providers/loom/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id027
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id028
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id029
  name: Make
  slug: make
  status: profiled
  tags: *id030
  url: /providers/make/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 12.6
  mcp: *id031
  name: Memberful
  slug: memberful
  status: profiled
  tags: *id032
  url: /providers/memberful/
- agent_band: human-only
  agent_readiness: 2.8
  band: emerging
  in_catalog: true
  kin_score: 24.7
  mcp: *id033
  name: MemberSpace
  slug: memberspace
  status: profiled
  tags: *id034
  url: /providers/memberspace/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: developing
  in_catalog: true
  kin_score: 41.5
  mcp: *id035
  name: Memberstack
  slug: memberstack
  status: profiled
  tags: *id036
  url: /providers/memberstack/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id037
  name: Outseta
  slug: outseta
  status: queued for profiling
  tags: *id038
  url: null
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id039
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id040
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: exemplar
  in_catalog: true
  kin_score: 66.7
  mcp: *id041
  name: Rewardful
  slug: rewardful
  status: profiled
  tags: *id042
  url: /providers/rewardful/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id043
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id044
  url: /providers/salesforce/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: emerging
  in_catalog: true
  kin_score: 25.9
  mcp: *id045
  name: Simplecast
  slug: simplecast
  status: profiled
  tags: *id046
  url: /providers/simplecast/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id047
  name: Slack
  slug: slack
  status: profiled
  tags: *id048
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 30.9
  mcp: *id049
  name: SoundCloud
  slug: soundcloud
  status: profiled
  tags: *id050
  url: /providers/soundcloud/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id051
  name: Spotify
  slug: spotify
  status: profiled
  tags: *id052
  url: /providers/spotify/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id053
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id054
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: developing
  in_catalog: true
  kin_score: 51.1
  mcp: *id055
  name: Teachable
  slug: teachable
  status: profiled
  tags: *id056
  url: /providers/teachable/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: exemplar
  in_catalog: true
  kin_score: 69.9
  mcp: *id057
  name: ThriveCart
  slug: thrivecart
  status: profiled
  tags: *id058
  url: /providers/thrivecart/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id059
  name: Twitter / X
  slug: x
  status: profiled
  tags: *id060
  url: /providers/x/
- agent_band: agent-ready
  agent_readiness: 42.6
  band: thin
  in_catalog: true
  kin_score: 36.0
  mcp: *id061
  name: Typeform
  slug: typeform
  status: profiled
  tags: *id062
  url: /providers/typeform/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id063
  name: Vimeo
  slug: vimeo
  status: profiled
  tags: *id064
  url: /providers/vimeo/
- agent_band: agent-ready
  agent_readiness: 40.6
  band: exemplar
  in_catalog: true
  kin_score: 75.5
  mcp: *id065
  name: Wistia
  slug: wistia
  status: profiled
  tags: *id066
  url: /providers/wistia/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id067
  name: WordPress
  slug: wordpress
  status: profiled
  tags: *id068
  url: /providers/wordpress/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: strong
  in_catalog: true
  kin_score: 65.4
  mcp: *id069
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id070
  url: /providers/youtube/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id071
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id072
  url: /providers/zapier/
siblings:
- name: Discourse
  rows: 44
  url: /applications/community-forums/discourse/
- name: Flarum
  rows: 4
  url: /applications/community-forums/flarum/
- name: Lemmy
  rows: 2
  url: /applications/community-forums/lemmy/
- name: Mastodon
  rows: 10
  url: /applications/community-forums/mastodon/
- name: NodeBB
  rows: 9
  url: /applications/community-forums/nodebb/
sitemap: true
title: 'Circle: Community & Forums reference app'
---
