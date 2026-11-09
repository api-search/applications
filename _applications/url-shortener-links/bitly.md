---
app: Bitly
app_slug: bitly
app_url: https://bitly.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: domain
  name: Content Management
  providers:
  - Contentful
  - Ghost
  - Leadpages
  - Webflow
  - WordPress
  url: /capabilities/content-management/
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
  id: BC-430.50
  key: customer-feedback-management
  layer: domain
  name: Customer Feedback Management
  providers:
  - Qualtrics
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: domain
  name: Customer Lifecycle Engagement
  providers:
  - Braze
  url: /capabilities/customer-lifecycle-engagement/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: domain
  name: Design & Creative Editing
  providers:
  - Canva
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Klaviyo
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: domain
  name: Email Marketing Sends
  providers:
  - ActiveCampaign
  - AWeber
  - Constant Contact
  - GetResponse
  - Kit
  - Mailchimp
  - MailerLite
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-400.50
  key: marketing-operations-management
  layer: domain
  name: Marketing Operations Management
  providers:
  - Marketo
  - Oracle Eloqua
  - Pardot
  url: /capabilities/marketing-operations-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: domain
  name: Online Forms & Survey Collection
  providers:
  - Google Forms
  - Jotform
  - SurveyMonkey
  - Typeform
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - PayPal
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: domain
  name: SMS
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-914
  key: AE-914
  layer: domain
  name: Social Listening & Analytics
  providers:
  - Buffer
  - Hootsuite
  - Sprout Social
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - LinkedIn
  - Reddit
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.10
  key: AE-170.10
  layer: domain
  name: Video Platforms
  providers:
  - Twitch
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Discord
  - Microsoft Teams
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830
  key: knowledge-management
  layer: common
  name: Knowledge Management
  providers:
  - Google Docs
  - Notion
  url: /capabilities/knowledge-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics
  - Adobe Analytics
  - Google Analytics 4
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - Asana
  - ClickUp
  - monday.com
  - Smartsheet
  url: /capabilities/project-management/
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
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: common
  name: Video Calling
  providers:
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - IFTTT
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: url-shortener-links
  name: Link Management & URL Shorteners
  url: /applications/url-shortener-links/
counts:
  declared: 54
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.bitly.app/latest/
- route: integrations page
  url: https://bitly.com/solutions/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id033
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id034
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.bitly.app/latest/
  tier: observed
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
    agent_readiness: 53.7
    band: exemplar
    in_catalog: true
    kin_score: 82.0
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
  layer: domain
  name: ActiveCampaign
  provider: activecampaign
  says: lists ActiveCampaign as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_band: agent-native
    agent_readiness: 61.6
    band: exemplar
    in_catalog: true
    kin_score: 67.6
    mcp: &id003
      status: none
    slug: adobe-analytics
    status: profiled
    tags: &id004
    - Adobe
    - Analytics
    - Business Intelligence
    - Customer Intelligence
    url: /providers/adobe-analytics/
  layer: domain
  name: Adobe Analytics
  provider: adobe-analytics
  says: lists Adobe Analytics as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 50.3
    band: exemplar
    in_catalog: true
    kin_score: 69.2
    mcp: &id005
      source: https://github.com/Airtable/airtable-mcp-cli
      status: verified
    slug: airtable
    status: profiled
    tags: &id006
    - Application
    - Collaboration
    - Data
    - Database
    url: /providers/airtable/
  layer: common
  name: Airtable
  provider: airtable
  says: lists Airtable as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.7
    band: exemplar
    in_catalog: true
    kin_score: 74.8
    mcp: &id007
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id008
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
  layer: common
  name: Asana
  provider: asana
  says: lists Asana as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 39.6
    band: exemplar
    in_catalog: true
    kin_score: 72.2
    mcp: &id009
      source: https://github.com/aweber/aweber-mcp
      status: verified
    slug: aweber
    status: profiled
    tags: &id010
    - Email
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/aweber/
  layer: domain
  name: AWeber
  provider: aweber
  says: lists AWeber as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.9
    band: exemplar
    in_catalog: true
    kin_score: 75.2
    mcp: &id011
      source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
      status: verified
    slug: braze
    status: profiled
    tags: &id012
    - Customer Engagement
    - Marketing Automation
    - Messaging
    - Push Notifications
    url: /providers/braze/
  layer: domain
  name: Braze
  provider: braze
  says: lists Braze as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-914
    key: AE-914
    name: Social Listening & Analytics
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id013
      status: none
    slug: buffer
    status: profiled
    tags: &id014
    - Analytics
    - Publishing
    - Scheduling
    - Social Media
    url: /providers/buffer/
  layer: domain
  name: Buffer
  provider: buffer
  says: lists Buffer as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 71.4
    band: exemplar
    in_catalog: true
    kin_score: 79.9
    mcp: &id015
      source: https://www.canva.dev/docs/mcp/
      status: verified
    slug: canva
    status: profiled
    tags: &id016
    - Application
    - Automation
    - Brand Management
    - Collaboration
    url: /providers/canva/
  layer: domain
  name: Canva
  provider: canva
  says: lists Canva as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 57.0
    band: exemplar
    in_catalog: true
    kin_score: 73.7
    mcp: &id017
      source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
      status: verified
    slug: clickup
    status: profiled
    tags: &id018
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/clickup/
  layer: common
  name: ClickUp
  provider: clickup
  says: lists ClickUp as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 32.1
    band: exemplar
    in_catalog: true
    kin_score: 70.9
    mcp: &id019
      status: none
    slug: constant-contact
    status: profiled
    tags: &id020
    - Campaigns
    - Contacts
    - Email Marketing
    - Event
    url: /providers/constant-contact/
  layer: domain
  name: Constant Contact
  provider: constant-contact
  says: lists Constant Contact as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 56.5
    band: developing
    in_catalog: true
    kin_score: 44.3
    mcp: &id021
      source: https://github.com/contentful/contentful-mcp-server
      status: verified
    slug: contentful
    status: profiled
    tags: &id022
    - CMS
    - Content
    - Content Management
    - Headless CMS
    url: /providers/contentful/
  layer: domain
  name: Contentful
  provider: contentful
  says: lists Contentful as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
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
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id023
      status: none
    slug: discord
    status: profiled
    tags: &id024
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: Discord
  provider: discord
  says: lists Discord as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 48.9
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id025
      status: none
    slug: getresponse
    status: profiled
    tags: &id026
    - Email Marketing
    - Landing Pages
    - Marketing Automation
    - Webinars
    url: /providers/getresponse/
  layer: domain
  name: GetResponse
  provider: getresponse
  says: lists GetResponse as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 32.3
    band: exemplar
    in_catalog: true
    kin_score: 79.4
    mcp: &id027
      status: none
    slug: ghost-org
    status: profiled
    tags: &id028
    - Membership
    - Newsletters
    - Publishing
    - Subscription
    url: /providers/ghost-org/
  layer: domain
  name: Ghost
  provider: ghost-org
  says: lists Ghost as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id029
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id030
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: domain
  name: Google Analytics 4
  provider: google-analytics
  says: lists Google Analytics 4 as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 67.0
    mcp: &id031
      source: https://docs.cloud.google.com/mcp/supported-products
      status: verified
    slug: google-docs
    status: profiled
    tags: &id032
    - Collaboration
    - Documents
    - Google Workspace
    - Productivity
    url: /providers/google-docs/
  layer: common
  name: Google Docs
  provider: google-docs
  says: lists Google Docs as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 36.1
    band: developing
    in_catalog: true
    kin_score: 50.8
    mcp: &id035
      status: none
    slug: google-forms
    status: profiled
    tags: &id036
    - Data Collection
    - Forms
    - Google
    - Google Workspace
    url: /providers/google-forms/
  layer: domain
  name: Google Forms
  provider: google-forms
  says: lists Google Forms as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 33.8
    band: strong
    in_catalog: true
    kin_score: 64.5
    mcp: &id037
      status: none
    slug: google-sheets
    status: profiled
    tags: &id038
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
  layer: common
  name: Google Sheets
  provider: google-sheets
  says: lists Google Sheets as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-914
    key: AE-914
    name: Social Listening & Analytics
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.8
    band: exemplar
    in_catalog: true
    kin_score: 72.7
    mcp: &id039
      status: none
    slug: hootsuite
    status: profiled
    tags: &id040
    - Content Scheduling
    - Marketing
    - Social Media
    - Social Media Management
    url: /providers/hootsuite/
  layer: domain
  name: Hootsuite
  provider: hootsuite
  says: lists Hootsuite as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 52.7
    band: exemplar
    in_catalog: true
    kin_score: 94.6
    mcp: &id041
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id042
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 43.3
    band: emerging
    in_catalog: true
    kin_score: 25.0
    mcp: &id043
      source: https://github.com/IFTTT/ifttt-plugins
      status: verified
    slug: ifttt
    status: profiled
    tags: &id044
    - Automation
    - No-Code
    - Webhook
    - iPaaS
    url: /providers/ifttt/
  layer: common
  name: IFTTT
  provider: ifttt
  says: lists IFTTT as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 48.6
    band: exemplar
    in_catalog: true
    kin_score: 70.6
    mcp: &id045
      source: https://github.com/jotform/mcp-server
      status: verified
    slug: jotform
    status: profiled
    tags: &id046
    - Data Collection
    - Forms
    - No-Code
    - Surveys
    url: /providers/jotform/
  layer: domain
  name: Jotform
  provider: jotform
  says: lists Jotform as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 79.6
    mcp: &id047
      status: none
    slug: convertkit
    status: profiled
    tags: &id048
    - Automation
    - Creator Economy
    - Email Marketing
    - Subscribers
    url: /providers/convertkit/
  layer: domain
  name: Kit
  provider: convertkit
  says: lists Kit as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_band: agent-native
    agent_readiness: 54.9
    band: exemplar
    in_catalog: true
    kin_score: 77.6
    mcp: &id049
      source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
      status: verified
    slug: klaviyo
    status: profiled
    tags: &id050
    - Customer Data
    - Email
    - Marketing
    - SMS
    url: /providers/klaviyo/
  layer: domain
  name: Klaviyo
  provider: klaviyo
  says: lists Klaviyo as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 50.6
    band: strong
    in_catalog: true
    kin_score: 58.6
    mcp: &id051
      status: unknown
    slug: leadpages
    status: profiled
    tags: &id052
    - Company
    - Conversion Optimization
    - Landing Pages
    - Marketing
    url: /providers/leadpages/
  layer: domain
  name: Leadpages
  provider: leadpages
  says: lists Leadpages as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.4
    band: exemplar
    in_catalog: true
    kin_score: 76.4
    mcp: &id053
      status: none
    slug: linkedin
    status: profiled
    tags: &id054
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: lists LinkedIn as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 42.3
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id055
      status: none
    slug: mailchimp
    status: profiled
    tags: &id056
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: domain
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 55.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
    mcp: &id057
      source: https://developers.mailerlite.com/
      status: documented
    slug: mailerlite
    status: profiled
    tags: &id058
    - Automation
    - Email Marketing
    - Newsletters
    - Subscribers
    url: /providers/mailerlite/
  layer: domain
  name: MailerLite
  provider: mailerlite
  says: lists MailerLite as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.50
    key: marketing-operations-management
    name: Marketing Operations Management
    url: /capabilities/marketing-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.1
    band: strong
    in_catalog: true
    kin_score: 55.6
    mcp: &id059
      status: none
    slug: marketo
    status: profiled
    tags: &id060
    - Adobe
    - Automation
    - Marketing
    - Marketing Automation
    url: /providers/marketo/
  layer: domain
  name: Marketo
  provider: marketo
  says: lists Marketo as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
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
    agent_readiness: 34.2
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id061
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id062
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.3
    band: thin
    in_catalog: true
    kin_score: 33.6
    mcp: &id063
      source: https://github.com/mondaycom/mcp
      status: verified
    slug: monday-com
    status: profiled
    tags: &id064
    - Automation
    - CRM
    - GraphQL
    - Work Management
    url: /providers/monday-com/
  layer: common
  name: monday.com
  provider: monday-com
  says: lists monday.com as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.9
    band: exemplar
    in_catalog: true
    kin_score: 67.2
    mcp: &id065
      source: https://developers.notion.com/docs/mcp
      status: verified
    slug: notion
    status: profiled
    tags: &id066
    - Collaboration
    - Database
    - Ideas
    - Notes
    url: /providers/notion/
  layer: common
  name: Notion
  provider: notion
  says: lists Notion as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.50
    key: marketing-operations-management
    name: Marketing Operations Management
    url: /capabilities/marketing-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: developing
    in_catalog: true
    kin_score: 50.7
    mcp: &id067
      status: none
    slug: eloqua
    status: profiled
    tags: &id068
    - CRM
    - Email Marketing
    - Lead Management
    - Marketing Automation
    url: /providers/eloqua/
  layer: domain
  name: Oracle Eloqua
  provider: eloqua
  says: lists Oracle Eloqua as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.50
    key: marketing-operations-management
    name: Marketing Operations Management
    url: /capabilities/marketing-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.4
    band: strong
    in_catalog: true
    kin_score: 62.4
    mcp: &id069
      status: none
    slug: pardot
    status: profiled
    tags: &id070
    - B2B Marketing
    - Email Marketing
    - Lead Generation
    - Marketing Automation
    url: /providers/pardot/
  layer: domain
  name: Pardot
  provider: pardot
  says: lists Pardot as an integration
  source: https://bitly.com/solutions/integrations/
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
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id071
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id072
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: domain
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.0
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id073
      status: none
    slug: qualtrics
    status: profiled
    tags: &id074
    - Customer Experience
    - Employee Experience
    - Experience Management
    - Surveys
    url: /providers/qualtrics/
  layer: domain
  name: Qualtrics
  provider: qualtrics
  says: lists Qualtrics as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.1
    band: strong
    in_catalog: true
    kin_score: 63.0
    mcp: &id075
      source: https://github.com/reddit/devvit-mcp
      status: verified
    slug: reddit
    status: profiled
    tags: &id076
    - Advertising
    - Community
    - Content
    - Reddit
    url: /providers/reddit/
  layer: domain
  name: Reddit
  provider: reddit
  says: lists Reddit as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 54.7
    band: exemplar
    in_catalog: true
    kin_score: 90.6
    mcp: &id077
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id078
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 40.1
    band: exemplar
    in_catalog: true
    kin_score: 87.3
    mcp: &id079
      status: none
    slug: sendgrid
    status: profiled
    tags: &id080
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: domain
  name: SendGrid
  provider: sendgrid
  says: lists SendGrid as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 52.5
    band: exemplar
    in_catalog: true
    kin_score: 84.6
    mcp: &id081
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id082
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
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
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id083
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id084
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.1
    band: developing
    in_catalog: true
    kin_score: 41.6
    mcp: &id085
      source: https://github.com/smartsheet-platform/smar-mcp
      status: verified
    slug: smartsheet
    status: profiled
    tags: &id086
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/smartsheet/
  layer: common
  name: Smartsheet
  provider: smartsheet
  says: lists Smartsheet as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-914
    key: AE-914
    name: Social Listening & Analytics
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.2
    band: strong
    in_catalog: true
    kin_score: 55.3
    mcp: &id087
      status: none
    slug: sprout-social
    status: profiled
    tags: &id088
    - Analytics
    - Publishing
    - Social Media
    - Social Media Management
    url: /providers/sprout-social/
  layer: domain
  name: Sprout Social
  provider: sprout-social
  says: lists Sprout Social as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id089
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id090
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 46.9
    band: thin
    in_catalog: true
    kin_score: 35.4
    mcp: &id091
      source: https://www.surveymonkey.com/apps/
      status: documented
    slug: surveymonkey
    status: profiled
    tags: &id092
    - Feedback
    - Market Research
    - NPS
    - Surveys
    url: /providers/surveymonkey/
  layer: domain
  name: SurveyMonkey
  provider: surveymonkey
  says: lists SurveyMonkey as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.4
    band: exemplar
    in_catalog: true
    kin_score: 90.3
    mcp: &id093
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id094
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: domain
  name: Twilio
  provider: twilio
  says: lists Twilio as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 43.8
    mcp: &id095
      status: none
    slug: segment
    status: profiled
    tags: &id096
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: domain
  name: Twilio Segment
  provider: segment
  says: lists Twilio Segment as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.2
    band: developing
    in_catalog: true
    kin_score: 50.5
    mcp: &id097
      status: none
    slug: twitch
    status: profiled
    tags: &id098
    - Entertainment
    - Gaming
    - Live Streaming
    - Streaming
    url: /providers/twitch/
  layer: domain
  name: Twitch
  provider: twitch
  says: lists Twitch as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 43.5
    band: thin
    in_catalog: true
    kin_score: 37.6
    mcp: &id099
      source: https://www.typeform.com/developers/mcp
      status: verified
    slug: typeform
    status: profiled
    tags: &id100
    - Forms
    - Lead Capture
    - Software-as-a-Service
    - Surveys
    url: /providers/typeform/
  layer: domain
  name: Typeform
  provider: typeform
  says: lists Typeform as an integration
  source: https://bitly.com/solutions/integrations/
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
    kin_score: 60.7
    mcp: &id101
      source: https://developers.webflow.com/mcp/reference/overview
      status: verified
    slug: webflow
    status: profiled
    tags: &id102
    - CMS
    - E-Commerce
    - No-Code
    - Web Development
    url: /providers/webflow/
  layer: domain
  name: Webflow
  provider: webflow
  says: lists Webflow as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 31.4
    band: developing
    in_catalog: true
    kin_score: 46.0
    mcp: &id103
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id104
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
  layer: domain
  name: WordPress
  provider: wordpress
  says: lists WordPress as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.4
    band: strong
    in_catalog: true
    kin_score: 62.6
    mcp: &id105
      status: none
    slug: youtube
    status: profiled
    tags: &id106
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: lists YouTube as an integration
  source: https://bitly.com/solutions/integrations/
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
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id107
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id108
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 55.2
    band: strong
    in_catalog: true
    kin_score: 56.2
    mcp: &id109
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id110
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: common
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://bitly.com/solutions/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/url-shortener-links/bitly/
providers:
- agent_band: agent-ready
  agent_readiness: 53.7
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id001
  name: ActiveCampaign
  slug: activecampaign
  status: profiled
  tags: *id002
  url: /providers/activecampaign/
- agent_band: agent-native
  agent_readiness: 61.6
  band: exemplar
  in_catalog: true
  kin_score: 67.6
  mcp: *id003
  name: Adobe Analytics
  slug: adobe-analytics
  status: profiled
  tags: *id004
  url: /providers/adobe-analytics/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: exemplar
  in_catalog: true
  kin_score: 69.2
  mcp: *id005
  name: Airtable
  slug: airtable
  status: profiled
  tags: *id006
  url: /providers/airtable/
- agent_band: agent-ready
  agent_readiness: 53.7
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id007
  name: Asana
  slug: asana
  status: profiled
  tags: *id008
  url: /providers/asana/
- agent_band: agent-ready
  agent_readiness: 39.6
  band: exemplar
  in_catalog: true
  kin_score: 72.2
  mcp: *id009
  name: AWeber
  slug: aweber
  status: profiled
  tags: *id010
  url: /providers/aweber/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: exemplar
  in_catalog: true
  kin_score: 75.2
  mcp: *id011
  name: Braze
  slug: braze
  status: profiled
  tags: *id012
  url: /providers/braze/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id013
  name: Buffer
  slug: buffer
  status: profiled
  tags: *id014
  url: /providers/buffer/
- agent_band: agent-native
  agent_readiness: 71.4
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id015
  name: Canva
  slug: canva
  status: profiled
  tags: *id016
  url: /providers/canva/
- agent_band: agent-ready
  agent_readiness: 57.0
  band: exemplar
  in_catalog: true
  kin_score: 73.7
  mcp: *id017
  name: ClickUp
  slug: clickup
  status: profiled
  tags: *id018
  url: /providers/clickup/
- agent_band: agent-ready
  agent_readiness: 32.1
  band: exemplar
  in_catalog: true
  kin_score: 70.9
  mcp: *id019
  name: Constant Contact
  slug: constant-contact
  status: profiled
  tags: *id020
  url: /providers/constant-contact/
- agent_band: agent-ready
  agent_readiness: 56.5
  band: developing
  in_catalog: true
  kin_score: 44.3
  mcp: *id021
  name: Contentful
  slug: contentful
  status: profiled
  tags: *id022
  url: /providers/contentful/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id023
  name: Discord
  slug: discord
  status: profiled
  tags: *id024
  url: /providers/discord/
- agent_band: agent-ready
  agent_readiness: 48.9
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id025
  name: GetResponse
  slug: getresponse
  status: profiled
  tags: *id026
  url: /providers/getresponse/
- agent_band: agent-ready
  agent_readiness: 32.3
  band: exemplar
  in_catalog: true
  kin_score: 79.4
  mcp: *id027
  name: Ghost
  slug: ghost-org
  status: profiled
  tags: *id028
  url: /providers/ghost-org/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id029
  name: Google Analytics 4
  slug: google-analytics
  status: profiled
  tags: *id030
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 67.0
  mcp: *id031
  name: Google Docs
  slug: google-docs
  status: profiled
  tags: *id032
  url: /providers/google-docs/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id033
  name: Google Firebase Analytics
  slug: firebase
  status: profiled
  tags: *id034
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 36.1
  band: developing
  in_catalog: true
  kin_score: 50.8
  mcp: *id035
  name: Google Forms
  slug: google-forms
  status: profiled
  tags: *id036
  url: /providers/google-forms/
- agent_band: agent-ready
  agent_readiness: 33.8
  band: strong
  in_catalog: true
  kin_score: 64.5
  mcp: *id037
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id038
  url: /providers/google-sheets/
- agent_band: agent-ready
  agent_readiness: 48.8
  band: exemplar
  in_catalog: true
  kin_score: 72.7
  mcp: *id039
  name: Hootsuite
  slug: hootsuite
  status: profiled
  tags: *id040
  url: /providers/hootsuite/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id041
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id042
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 43.3
  band: emerging
  in_catalog: true
  kin_score: 25.0
  mcp: *id043
  name: IFTTT
  slug: ifttt
  status: profiled
  tags: *id044
  url: /providers/ifttt/
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 70.6
  mcp: *id045
  name: Jotform
  slug: jotform
  status: profiled
  tags: *id046
  url: /providers/jotform/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 79.6
  mcp: *id047
  name: Kit
  slug: convertkit
  status: profiled
  tags: *id048
  url: /providers/convertkit/
- agent_band: agent-native
  agent_readiness: 54.9
  band: exemplar
  in_catalog: true
  kin_score: 77.6
  mcp: *id049
  name: Klaviyo
  slug: klaviyo
  status: profiled
  tags: *id050
  url: /providers/klaviyo/
- agent_band: agent-ready
  agent_readiness: 50.6
  band: strong
  in_catalog: true
  kin_score: 58.6
  mcp: *id051
  name: Leadpages
  slug: leadpages
  status: profiled
  tags: *id052
  url: /providers/leadpages/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: exemplar
  in_catalog: true
  kin_score: 76.4
  mcp: *id053
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id054
  url: /providers/linkedin/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id055
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id056
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 55.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id057
  name: MailerLite
  slug: mailerlite
  status: profiled
  tags: *id058
  url: /providers/mailerlite/
- agent_band: agent-ready
  agent_readiness: 31.1
  band: strong
  in_catalog: true
  kin_score: 55.6
  mcp: *id059
  name: Marketo
  slug: marketo
  status: profiled
  tags: *id060
  url: /providers/marketo/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id061
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id062
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id063
  name: monday.com
  slug: monday-com
  status: profiled
  tags: *id064
  url: /providers/monday-com/
- agent_band: agent-ready
  agent_readiness: 54.9
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id065
  name: Notion
  slug: notion
  status: profiled
  tags: *id066
  url: /providers/notion/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: developing
  in_catalog: true
  kin_score: 50.7
  mcp: *id067
  name: Oracle Eloqua
  slug: eloqua
  status: profiled
  tags: *id068
  url: /providers/eloqua/
- agent_band: agent-ready
  agent_readiness: 35.4
  band: strong
  in_catalog: true
  kin_score: 62.4
  mcp: *id069
  name: Pardot
  slug: pardot
  status: profiled
  tags: *id070
  url: /providers/pardot/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id071
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id072
  url: /providers/paypal/
- agent_band: agent-aware
  agent_readiness: 20.0
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id073
  name: Qualtrics
  slug: qualtrics
  status: profiled
  tags: *id074
  url: /providers/qualtrics/
- agent_band: agent-ready
  agent_readiness: 39.1
  band: strong
  in_catalog: true
  kin_score: 63.0
  mcp: *id075
  name: Reddit
  slug: reddit
  status: profiled
  tags: *id076
  url: /providers/reddit/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id077
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id078
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id079
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id080
  url: /providers/sendgrid/
- agent_band: agent-ready
  agent_readiness: 52.5
  band: exemplar
  in_catalog: true
  kin_score: 84.6
  mcp: *id081
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id082
  url: /providers/shopify/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id083
  name: Slack
  slug: slack
  status: profiled
  tags: *id084
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 21.1
  band: developing
  in_catalog: true
  kin_score: 41.6
  mcp: *id085
  name: Smartsheet
  slug: smartsheet
  status: profiled
  tags: *id086
  url: /providers/smartsheet/
- agent_band: agent-aware
  agent_readiness: 16.2
  band: strong
  in_catalog: true
  kin_score: 55.3
  mcp: *id087
  name: Sprout Social
  slug: sprout-social
  status: profiled
  tags: *id088
  url: /providers/sprout-social/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id089
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id090
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id091
  name: SurveyMonkey
  slug: surveymonkey
  status: profiled
  tags: *id092
  url: /providers/surveymonkey/
- agent_band: agent-native
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 90.3
  mcp: *id093
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id094
  url: /providers/twilio/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 43.8
  mcp: *id095
  name: Twilio Segment
  slug: segment
  status: profiled
  tags: *id096
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 32.2
  band: developing
  in_catalog: true
  kin_score: 50.5
  mcp: *id097
  name: Twitch
  slug: twitch
  status: profiled
  tags: *id098
  url: /providers/twitch/
- agent_band: agent-ready
  agent_readiness: 43.5
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id099
  name: Typeform
  slug: typeform
  status: profiled
  tags: *id100
  url: /providers/typeform/
- agent_band: agent-ready
  agent_readiness: 62.5
  band: strong
  in_catalog: true
  kin_score: 60.7
  mcp: *id101
  name: Webflow
  slug: webflow
  status: profiled
  tags: *id102
  url: /providers/webflow/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: developing
  in_catalog: true
  kin_score: 46.0
  mcp: *id103
  name: WordPress
  slug: wordpress
  status: profiled
  tags: *id104
  url: /providers/wordpress/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: strong
  in_catalog: true
  kin_score: 62.6
  mcp: *id105
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id106
  url: /providers/youtube/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id107
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id108
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 55.2
  band: strong
  in_catalog: true
  kin_score: 56.2
  mcp: *id109
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id110
  url: /providers/zoom/
siblings:
- name: Dub
  rows: 25
  url: /applications/url-shortener-links/dub/
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
title: 'Bitly: Link Management & URL Shorteners reference app'
---
