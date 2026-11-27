---
app: Survicate
app_slug: survicate
app_url: https://survicate.com
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Google BigQuery
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: domain
  name: Customer Data Management
  providers:
  - Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: domain
  name: Customer Lifecycle Engagement
  providers:
  - ActiveCampaign
  - Braze
  - Customer.io
  - Iterable
  - Klaviyo
  - Mailchimp
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
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: domain
  name: Customer Service Management
  providers:
  - Intercom
  - LiveChat
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.30.40
  key: AE-110.30.40
  layer: domain
  name: Meeting Notes & Conversation Intelligence
  providers:
  - Gong
  - tl;dv
  url: /capabilities/speech-voice/
  via_parent: Speech & Voice
- attribution: Turbo EA
  id: BC-4200.10
  key: product-discovery-backlog-management
  layer: domain
  name: Product Discovery & Backlog Management
  providers:
  - Jira
  - Linear
  - Productboard
  url: /capabilities/product-discovery-backlog-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: domain
  name: Reviews & Social Proof
  providers:
  - Google Reviews
  url: /capabilities/reviews-social-proof/
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
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Amplitude
  - Fullstory
  - Google Analytics
  - Mixpanel
  - UXCam
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: customer-feedback-nps
  name: Customer Feedback & NPS
  url: /applications/customer-feedback-nps/
counts:
  declared: 25
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://survicate.com/integrations/
integrations:
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
  layer: domain
  name: ActiveCampaign
  provider: activecampaign
  says: lists ActiveCampaign as an integration
  source: https://survicate.com/integrations/
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
    mcp: &id003
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id004
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: lists Amplitude as an integration
  source: https://survicate.com/integrations/
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
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id005
      source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
      status: verified
    slug: braze
    status: profiled
    tags: &id006
    - Customer Engagement
    - Marketing Automation
    - Messaging
    - Push Notifications
    url: /providers/braze/
  layer: domain
  name: Braze
  provider: braze
  says: lists Braze as an integration
  source: https://survicate.com/integrations/
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
    agent_readiness: 70.1
    band: exemplar
    in_catalog: true
    kin_score: 85.9
    mcp: &id007
      source: https://github.com/customerio/claude-plugin
      status: verified
    slug: customer-io
    status: profiled
    tags: &id008
    - Behavioral Data
    - Broadcast
    - CDP
    - Campaigns
    url: /providers/customer-io/
  layer: domain
  name: Customer.io
  provider: customer-io
  says: lists Customer.io as an integration
  source: https://survicate.com/integrations/
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
    agent_readiness: 30.0
    band: thin
    in_catalog: true
    kin_score: 37.4
    mcp: &id009
      source: https://developer.fullstory.com/mcp/introduction/
      status: documented
    slug: fullstory
    status: profiled
    tags: &id010
    - Behavioral Analytics
    - Digital Experience
    - Product Analytics
    - Session Replay
    url: /providers/fullstory/
  layer: common
  name: Fullstory
  provider: fullstory
  says: lists Fullstory as an integration
  source: https://survicate.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.40
    key: AE-110.30.40
    name: Meeting Notes & Conversation Intelligence
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.4
    band: exemplar
    in_catalog: true
    kin_score: 66.5
    mcp: &id011
      status: none
    slug: gong
    status: profiled
    tags: &id012
    - Analytics
    - Conversations
    - Revenue Intelligence
    - Sales
    url: /providers/gong/
  layer: domain
  name: Gong
  provider: gong
  says: lists Gong as an integration
  source: https://survicate.com/integrations/
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
  source: https://survicate.com/integrations/
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
    agent_band: agent-ready
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id015
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id016
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
  layer: domain
  name: Google BigQuery
  provider: google-bigquery
  says: lists Google BigQuery as an integration
  source: https://survicate.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.7
    band: strong
    in_catalog: true
    kin_score: 56.9
    mcp: &id017
      status: none
    slug: google-business-profile
    status: profiled
    tags: &id018
    - Business Profiles
    - Google
    - Local Business
    - Location
    url: /providers/google-business-profile/
  layer: domain
  name: Google Reviews
  provider: google-business-profile
  says: lists Google Reviews as an integration
  source: https://survicate.com/integrations/
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
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://survicate.com/integrations/
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
    agent_readiness: 32.5
    band: developing
    in_catalog: true
    kin_score: 51.0
    mcp: &id021
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id022
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: domain
  name: Intercom
  provider: intercom
  says: lists Intercom as an integration
  source: https://survicate.com/integrations/
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
    agent_readiness: 33.8
    band: exemplar
    in_catalog: true
    kin_score: 68.3
    mcp: &id023
      source: https://github.com/Iterable/mcp-server
      status: verified
    slug: iterable
    status: profiled
    tags: &id024
    - Cross-Channel Messaging
    - Customer Engagement
    - Email
    - Marketing Automation
    url: /providers/iterable/
  layer: domain
  name: Iterable
  provider: iterable
  says: lists Iterable as an integration
  source: https://survicate.com/integrations/
  tier: declared
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
    mcp: &id025
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id026
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: domain
  name: Jira
  provider: jira
  says: lists Jira as an integration
  source: https://survicate.com/integrations/
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
    agent_band: agent-native
    agent_readiness: 58.7
    band: exemplar
    in_catalog: true
    kin_score: 78.1
    mcp: &id027
      source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
      status: verified
    slug: klaviyo
    status: profiled
    tags: &id028
    - Customer Data
    - Email
    - Marketing
    - SMS
    url: /providers/klaviyo/
  layer: domain
  name: Klaviyo
  provider: klaviyo
  says: lists Klaviyo as an integration
  source: https://survicate.com/integrations/
  tier: declared
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
    agent_readiness: 35.2
    band: developing
    in_catalog: true
    kin_score: 39.6
    mcp: &id029
      source: https://linear.app/docs/mcp
      status: verified
    slug: linear-app
    status: profiled
    tags: &id030
    - Issue Tracking
    - Productivity
    - Project Management
    - Software-as-a-Service
    url: /providers/linear-app/
  layer: domain
  name: Linear
  provider: linear-app
  says: lists Linear as an integration
  source: https://survicate.com/integrations/
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
    agent_readiness: 47.2
    band: thin
    in_catalog: true
    kin_score: 31.3
    mcp: &id031
      status: none
    slug: livechat
    status: profiled
    tags: &id032
    - Customer Service
    - Live Chat
    - Messaging
    - Sales
    url: /providers/livechat/
  layer: domain
  name: LiveChat
  provider: livechat
  says: lists LiveChat as an integration
  source: https://survicate.com/integrations/
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
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id033
      status: none
    slug: mailchimp
    status: profiled
    tags: &id034
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: domain
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://survicate.com/integrations/
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
    mcp: &id035
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id036
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: lists Mixpanel as an integration
  source: https://survicate.com/integrations/
  tier: declared
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
    agent_readiness: 40.7
    band: developing
    in_catalog: true
    kin_score: 39.7
    mcp: &id037
      source: https://mcp.productboard.com/mcp
      status: verified
    slug: productboard
    status: profiled
    tags: &id038
    - Customer Feedback
    - Prioritization
    - Product Management
    - Roadmapping
    url: /providers/productboard/
  layer: domain
  name: Productboard
  provider: productboard
  says: lists Productboard as an integration
  source: https://survicate.com/integrations/
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
    mcp: &id039
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id040
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://survicate.com/integrations/
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
    mcp: &id041
      status: none
    slug: segment
    status: profiled
    tags: &id042
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: domain
  name: Segment
  provider: segment
  says: lists Segment as an integration
  source: https://survicate.com/integrations/
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
    mcp: &id043
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id044
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://survicate.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.40
    key: AE-110.30.40
    name: Meeting Notes & Conversation Intelligence
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id045
      status: unchecked
    slug: tldv
    status: queued for profiling
    tags: &id046 []
    url: null
  layer: domain
  name: tl;dv
  provider: tldv
  says: lists tl;dv as an integration
  source: https://survicate.com/integrations/
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
    agent_readiness: 39.2
    band: developing
    in_catalog: true
    kin_score: 45.5
    mcp: &id047
      source: https://www.uxcam.com/mcp/
      status: verified
    slug: uxcam
    status: profiled
    tags: &id048
    - Company
    - Mobile Analytics
    - Product Analytics
    - Session Replay
    url: /providers/uxcam/
  layer: common
  name: UXCam
  provider: uxcam
  says: lists UXCam as an integration
  source: https://survicate.com/integrations/
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
    mcp: &id049
      status: none
    slug: zendesk
    status: profiled
    tags: &id050
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://survicate.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/customer-feedback-nps/survicate/
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
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id003
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id004
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id005
  name: Braze
  slug: braze
  status: profiled
  tags: *id006
  url: /providers/braze/
- agent_band: agent-ready
  agent_readiness: 70.1
  band: exemplar
  in_catalog: true
  kin_score: 85.9
  mcp: *id007
  name: Customer.io
  slug: customer-io
  status: profiled
  tags: *id008
  url: /providers/customer-io/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: thin
  in_catalog: true
  kin_score: 37.4
  mcp: *id009
  name: Fullstory
  slug: fullstory
  status: profiled
  tags: *id010
  url: /providers/fullstory/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: exemplar
  in_catalog: true
  kin_score: 66.5
  mcp: *id011
  name: Gong
  slug: gong
  status: profiled
  tags: *id012
  url: /providers/gong/
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
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id015
  name: Google BigQuery
  slug: google-bigquery
  status: profiled
  tags: *id016
  url: /providers/google-bigquery/
- agent_band: agent-ready
  agent_readiness: 37.7
  band: strong
  in_catalog: true
  kin_score: 56.9
  mcp: *id017
  name: Google Reviews
  slug: google-business-profile
  status: profiled
  tags: *id018
  url: /providers/google-business-profile/
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
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id021
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id022
  url: /providers/intercom/
- agent_band: agent-ready
  agent_readiness: 33.8
  band: exemplar
  in_catalog: true
  kin_score: 68.3
  mcp: *id023
  name: Iterable
  slug: iterable
  status: profiled
  tags: *id024
  url: /providers/iterable/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id025
  name: Jira
  slug: jira
  status: profiled
  tags: *id026
  url: /providers/jira/
- agent_band: agent-native
  agent_readiness: 58.7
  band: exemplar
  in_catalog: true
  kin_score: 78.1
  mcp: *id027
  name: Klaviyo
  slug: klaviyo
  status: profiled
  tags: *id028
  url: /providers/klaviyo/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: developing
  in_catalog: true
  kin_score: 39.6
  mcp: *id029
  name: Linear
  slug: linear-app
  status: profiled
  tags: *id030
  url: /providers/linear-app/
- agent_band: agent-ready
  agent_readiness: 47.2
  band: thin
  in_catalog: true
  kin_score: 31.3
  mcp: *id031
  name: LiveChat
  slug: livechat
  status: profiled
  tags: *id032
  url: /providers/livechat/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id033
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id034
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id035
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id036
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 40.7
  band: developing
  in_catalog: true
  kin_score: 39.7
  mcp: *id037
  name: Productboard
  slug: productboard
  status: profiled
  tags: *id038
  url: /providers/productboard/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id039
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id040
  url: /providers/salesforce/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id041
  name: Segment
  slug: segment
  status: profiled
  tags: *id042
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id043
  name: Slack
  slug: slack
  status: profiled
  tags: *id044
  url: /providers/slack/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id045
  name: tl;dv
  slug: tldv
  status: queued for profiling
  tags: *id046
  url: null
- agent_band: agent-native
  agent_readiness: 39.2
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id047
  name: UXCam
  slug: uxcam
  status: profiled
  tags: *id048
  url: /providers/uxcam/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id049
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id050
  url: /providers/zendesk/
siblings:
- name: Canny
  rows: 18
  url: /applications/customer-feedback-nps/canny/
- name: ClearFlask
  rows: 15
  url: /applications/customer-feedback-nps/clearflask/
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
sitemap: true
title: 'Survicate: Customer Feedback & NPS reference app'
---
