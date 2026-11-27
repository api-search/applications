---
app: Calendly
app_slug: calendly
app_url: https://calendly.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-140.50.20
  key: AE-140.50.20
  layer: domain
  name: Corporate & Digital Gifting
  providers:
  - Reachdesk
  - Sendoso
  url: /capabilities/gift-cards-gifting-cashback/
  via_parent: Gift Cards, Gifting & Cashback
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - Close
  - HubSpot
  - Microsoft Dynamics
  - Nutshell
  - Salesforce
  - Streak
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.30.10
  key: AE-230.30.10
  layer: domain
  name: Data Enrichment
  providers:
  - Clearbit
  - ZoomInfo
  url: /capabilities/company-contact-data/
  via_parent: Company & Contact Data
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - LinkedIn Ads
  - Meta Ads / Facebook Pixel
  - TikTok
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
  - Kit
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  - Outlook / Microsoft 365
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.50
  key: marketing-operations-management
  layer: domain
  name: Marketing Operations Management
  providers:
  - Marketo
  - Pardot
  url: /capabilities/marketing-operations-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.30.40
  key: AE-110.30.40
  layer: domain
  name: Meeting Notes & Conversation Intelligence
  providers:
  - Gong
  url: /capabilities/speech-voice/
  via_parent: Speech & Voice
- attribution: API Evangelist extension
  id: AE-220.10
  key: AE-220.10
  layer: domain
  name: Online Courses
  providers:
  - Kajabi
  url: /capabilities/online-courses/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: domain
  name: Online Forms & Survey Collection
  providers:
  - Google Forms
  - Jotform
  - Typeform
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: API Evangelist extension
  id: AE-150.50.10
  key: AE-150.50.10
  layer: domain
  name: Programmable Voice
  providers:
  - CallRail
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: domain
  name: Reviews & Social Proof
  providers:
  - Podium
  - Yelp
  url: /capabilities/reviews-social-proof/
  via_parent: null
- attribution: Turbo EA
  id: BC-300.10
  key: talent-acquisition-management
  layer: domain
  name: Talent Acquisition Management
  providers:
  - Greenhouse
  - JazzHR
  - Zoho Recruit
  url: /capabilities/talent-acquisition-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Google Meet
  - GoTo Meeting
  - Loom
  - Microsoft Teams
  - ON24
  - Webex
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Intercom
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
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Google Crashlytics
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - PayPal
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics
  - Segment
  - Google Analytics
  - Pendo
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Make
  - Pipedream
  - Power Automate
  - Workato
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-100.70.20
  key: AE-100.70.20
  layer: agent
  name: Voice Agents
  providers:
  - Chatbase
  url: /capabilities/vertical-agents/
  via_parent: Vertical Agents
category:
  id: booking-scheduling
  name: Appointment Booking & Scheduling
  url: /applications/booking-scheduling/
counts:
  declared: 51
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.calendly.app/latest/
- route: integrations page
  url: https://calendly.com/marketing-site/sitemap.xml
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id020
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id021
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google Crashlytics
  provider: firebase
  says: ships the Google Crashlytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.calendly.app/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.calendly.app/latest/
  tier: observed
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
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id080
      status: none
    slug: segment
    status: profiled
    tags: &id081
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Segment
  provider: segment
  says: ships the Segment SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.calendly.app/latest/
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
    agent_readiness: 51.0
    band: exemplar
    in_catalog: true
    kin_score: 81.1
    mcp: &id002
      source: https://developers.activecampaign.com/page/mcp
      status: documented
    slug: activecampaign
    status: profiled
    tags: &id003
    - CRM
    - Email Marketing
    - Marketing Automation
    - Sales Automation
    url: /providers/activecampaign/
  layer: domain
  name: ActiveCampaign
  provider: activecampaign
  says: lists ActiveCampaign as an integration
  source: https://calendly.com/integration/activecampaign
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
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id004
      source: https://github.com/aweber/aweber-mcp
      status: verified
    slug: aweber
    status: profiled
    tags: &id005
    - Email
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/aweber/
  layer: domain
  name: AWeber
  provider: aweber
  says: lists AWeber as an integration
  source: https://calendly.com/integration/aweber
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.10
    key: AE-150.50.10
    name: Programmable Voice
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: developing
    in_catalog: true
    kin_score: 54.1
    mcp: &id006
      status: none
    slug: callrail
    status: profiled
    tags: &id007
    - Call Tracking
    - Conversation Intelligence
    - Lead Tracking
    - Marketing Attribution
    url: /providers/callrail/
  layer: domain
  name: CallRail
  provider: callrail
  says: lists CallRail as an integration
  source: https://calendly.com/integration/callrail
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-100.70.20
    key: AE-100.70.20
    name: Voice Agents
    url: /capabilities/vertical-agents/
    via_parent: Vertical Agents
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.1
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id008
      status: none
    slug: chatbase
    status: profiled
    tags: &id009
    - AI Agents
    - Artificial Intelligence
    - Chatbots
    - Customer Service
    url: /providers/chatbase/
  layer: agent
  name: Chatbase
  provider: chatbase
  says: lists Chatbase as an integration
  source: https://calendly.com/integration/chatbase
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.10
    key: AE-230.30.10
    name: Data Enrichment
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: strong
    in_catalog: true
    kin_score: 59.3
    mcp: &id010
      status: none
    slug: clearbit
    status: profiled
    tags: &id011
    - B2B
    - Data Enrichment
    - Reveal
    - Sales Intelligence
    url: /providers/clearbit/
  layer: domain
  name: Clearbit
  provider: clearbit
  says: lists Clearbit as an integration
  source: https://calendly.com/integration/clearbit
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
    agent_readiness: 58.1
    band: exemplar
    in_catalog: true
    kin_score: 77.2
    mcp: &id012
      source: https://developer.close.com/mcp
      status: verified
    slug: close
    status: profiled
    tags: &id013
    - CRM
    - Calling
    - Inside Sales
    - Sales Engagement
    url: /providers/close/
  layer: domain
  name: Close
  provider: close
  says: lists Close as an integration
  source: https://calendly.com/integration/close
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
    mcp: &id014
      status: none
    slug: gong
    status: profiled
    tags: &id015
    - Analytics
    - Conversations
    - Revenue Intelligence
    - Sales
    url: /providers/gong/
  layer: domain
  name: Gong
  provider: gong
  says: lists Gong as an integration
  source: https://calendly.com/integration/gong
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
    mcp: &id016
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id017
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://calendly.com/integration/google-analytics
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id018
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id019
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: domain
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://calendly.com/integration/google
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
    agent_readiness: 35.8
    band: developing
    in_catalog: true
    kin_score: 53.1
    mcp: &id022
      status: none
    slug: google-forms
    status: profiled
    tags: &id023
    - Data Collection
    - Forms
    - Google
    - Google Workspace
    url: /providers/google-forms/
  layer: domain
  name: Google Forms
  provider: google-forms
  says: lists Google Forms as an integration
  source: https://calendly.com/integration/google-forms
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
    agent_readiness: 34.9
    band: developing
    in_catalog: true
    kin_score: 52.2
    mcp: &id024
      status: none
    slug: google-meet
    status: profiled
    tags: &id025
    - Google
    - Google Workspace
    - Meetings
    - Recording
    url: /providers/google-meet/
  layer: domain
  name: Google Meet
  provider: google-meet
  says: lists Google Meet as an integration
  source: https://calendly.com/integration/google-meet
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.0
    mcp: &id026
      status: none
    slug: goto
    status: profiled
    tags: &id027
    - Company
    - Consumer
    - Indonesia
    - Super App
    url: /providers/goto/
  layer: domain
  name: GoTo Meeting
  provider: goto
  says: lists GoTo Meeting as an integration
  source: https://calendly.com/integration/gotomeeting
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.10
    key: talent-acquisition-management
    name: Talent Acquisition Management
    url: /capabilities/talent-acquisition-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 60.3
    band: exemplar
    in_catalog: true
    kin_score: 77.9
    mcp: &id028
      status: none
    slug: greenhouse
    status: profiled
    tags: &id029
    - Applicant Tracking
    - Greenhouse
    - Human Resources
    - Recruiting
    url: /providers/greenhouse/
  layer: domain
  name: Greenhouse
  provider: greenhouse
  says: lists Greenhouse as an integration
  source: https://calendly.com/integration/greenhouse
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
    mcp: &id030
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id031
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://calendly.com/integration/hubspot
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
    mcp: &id032
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id033
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: common
  name: Intercom
  provider: intercom
  says: lists Intercom as an integration
  source: https://calendly.com/integration/intercom
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.10
    key: talent-acquisition-management
    name: Talent Acquisition Management
    url: /capabilities/talent-acquisition-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 27.4
    mcp: &id034
      status: none
    slug: jazzhr
    status: profiled
    tags: &id035
    - Applicant Tracking
    - Hiring
    - Recruiting
    - Small Business
    url: /providers/jazzhr/
  layer: domain
  name: JazzHR
  provider: jazzhr
  says: lists JazzHR as an integration
  source: https://calendly.com/integration/jazzhr
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
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 70.2
    mcp: &id036
      source: https://github.com/jotform/mcp-server
      status: verified
    slug: jotform
    status: profiled
    tags: &id037
    - Data Collection
    - Forms
    - No-Code
    - Surveys
    url: /providers/jotform/
  layer: domain
  name: Jotform
  provider: jotform
  says: lists Jotform as an integration
  source: https://calendly.com/integration/jotform
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
    mcp: &id038
      source: https://help.kajabi.com/en/collections/19761100-mcp
      status: documented
    slug: kajabi
    status: profiled
    tags: &id039
    - Creator Economy
    - E-Commerce
    - Membership
    - Online Courses
    url: /providers/kajabi/
  layer: domain
  name: Kajabi
  provider: kajabi
  says: lists Kajabi as an integration
  source: https://calendly.com/integration/kajabi
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
    mcp: &id040
      status: none
    slug: convertkit
    status: profiled
    tags: &id041
    - Automation
    - Creator Economy
    - Email Marketing
    - Subscribers
    url: /providers/convertkit/
  layer: domain
  name: Kit
  provider: convertkit
  says: lists Kit as an integration
  source: https://calendly.com/integration/kit
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
    mcp: &id042
      status: none
    slug: linkedin
    status: profiled
    tags: &id043
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn Ads
  provider: linkedin
  says: lists LinkedIn Ads as an integration
  source: https://calendly.com/integration/linkedin-ads
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
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 18.4
    mcp: &id044
      status: none
    slug: loom
    status: profiled
    tags: &id045
    - Async
    - Communications
    - Productivity
    - Video
    url: /providers/loom/
  layer: domain
  name: Loom
  provider: loom
  says: lists Loom as an integration
  source: https://calendly.com/integration/loom
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
    mcp: &id046
      status: none
    slug: mailchimp
    status: profiled
    tags: &id047
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: domain
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://calendly.com/integration/mailchimp
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
    mcp: &id048
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id049
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://calendly.com/integration/make
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
    agent_readiness: 30.4
    band: strong
    in_catalog: true
    kin_score: 57.2
    mcp: &id050
      status: none
    slug: marketo
    status: profiled
    tags: &id051
    - Adobe
    - Automation
    - Marketing
    - Marketing Automation
    url: /providers/marketo/
  layer: domain
  name: Marketo
  provider: marketo
  says: lists Marketo as an integration
  source: https://calendly.com/integration/marketo
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
    mcp: &id052
      status: none
    slug: facebook
    status: profiled
    tags: &id053
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Meta Ads / Facebook Pixel
  provider: facebook
  says: lists Meta Ads / Facebook Pixel as an integration
  source: https://calendly.com/integration/meta-ads
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
    agent_readiness: 37.6
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id054
      source: https://github.com/microsoft/Dataverse-MCP
      status: verified
    slug: microsoft-dynamics-365
    status: profiled
    tags: &id055
    - Business Applications
    - CRM
    - Cloud
    - Enterprise
    url: /providers/microsoft-dynamics-365/
  layer: domain
  name: Microsoft Dynamics
  provider: microsoft-dynamics-365
  says: lists Microsoft Dynamics as an integration
  source: https://calendly.com/integration/microsoft-dynamics
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
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id056
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id057
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://calendly.com/integration/microsoft-teams
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
    agent_readiness: 51.2
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id058
      status: none
    slug: nutshell
    status: profiled
    tags: &id059
    - CRM
    - Email Marketing
    - Pipeline Management
    - Sales
    url: /providers/nutshell/
  layer: domain
  name: Nutshell
  provider: nutshell
  says: lists Nutshell as an integration
  source: https://calendly.com/integration/nutshell
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
    agent_band: agent-aware
    agent_readiness: 23.9
    band: developing
    in_catalog: true
    kin_score: 43.6
    mcp: &id060
      status: none
    slug: on24
    status: profiled
    tags: &id061
    - Company
    - Digital Engagement
    - Virtual Events
    - Webinars
    url: /providers/on24/
  layer: domain
  name: ON24
  provider: on24
  says: lists ON24 as an integration
  source: https://calendly.com/integration/on24
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 70.8
    mcp: &id062
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id063
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: domain
  name: Outlook / Microsoft 365
  provider: microsoft-outlook
  says: lists Outlook / Microsoft 365 as an integration
  source: https://calendly.com/integration/microsoft
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
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 60.7
    mcp: &id064
      status: none
    slug: pardot
    status: profiled
    tags: &id065
    - B2B Marketing
    - Email Marketing
    - Lead Generation
    - Marketing Automation
    url: /providers/pardot/
  layer: domain
  name: Pardot
  provider: pardot
  says: lists Pardot as an integration
  source: https://calendly.com/integration/pardot
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
    mcp: &id066
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id067
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://calendly.com/integration/paypal
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
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 57.0
    mcp: &id068
      source: https://support.pendo.io/hc/en-us/articles/41102236924955
      status: verified
    slug: pendoio
    status: profiled
    tags: &id069
    - Company
    - Digital Adoption
    - Product Analytics
    - Product Experience
    url: /providers/pendoio/
  layer: common
  name: Pendo
  provider: pendoio
  says: lists Pendo as an integration
  source: https://calendly.com/integration/pendo
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
    agent_readiness: 31.1
    band: strong
    in_catalog: true
    kin_score: 65.5
    mcp: &id070
      source: https://pipedream.com/docs/connect/mcp
      status: verified
    slug: pipedream
    status: profiled
    tags: &id071
    - Connect
    - Pipedream
    - Pro-Code-API-Composition
    - Workflows
    url: /providers/pipedream/
  layer: common
  name: Pipedream
  provider: pipedream
  says: lists Pipedream as an integration
  source: https://calendly.com/integration/pipedream
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
    agent_band: agent-native
    agent_readiness: 40.1
    band: strong
    in_catalog: true
    kin_score: 59.1
    mcp: &id072
      status: none
    slug: podium
    status: profiled
    tags: &id073
    - Customer Communication
    - Messaging
    - Payments
    - Reviews
    url: /providers/podium/
  layer: domain
  name: Podium
  provider: podium
  says: lists Podium as an integration
  source: https://calendly.com/integration/podium
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
    agent_readiness: 29.1
    band: strong
    in_catalog: true
    kin_score: 62.1
    mcp: &id074
      status: none
    slug: microsoft-power-automate
    status: profiled
    tags: &id075
    - Automation
    - Business Process
    - Integration
    - Low-Code
    url: /providers/microsoft-power-automate/
  layer: common
  name: Power Automate
  provider: microsoft-power-automate
  says: lists Power Automate as an integration
  source: https://calendly.com/integration/power-automate
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.50.20
    key: AE-140.50.20
    name: Corporate & Digital Gifting
    url: /capabilities/gift-cards-gifting-cashback/
    via_parent: Gift Cards, Gifting & Cashback
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 55.2
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id076
      source: https://app.reachdesk.com/mcp
      status: verified
    slug: reachdesk
    status: profiled
    tags: &id077
    - B2B
    - Corporate Gifting
    - Direct Mail
    - Swag
    url: /providers/reachdesk/
  layer: domain
  name: Reachdesk
  provider: reachdesk
  says: lists Reachdesk as an integration
  source: https://calendly.com/integration/reachdesk
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
    mcp: &id078
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id079
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://calendly.com/integration/salesforce
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.50.20
    key: AE-140.50.20
    name: Corporate & Digital Gifting
    url: /capabilities/gift-cards-gifting-cashback/
    via_parent: Gift Cards, Gifting & Cashback
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.6
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id082
      status: none
    slug: sendoso
    status: profiled
    tags: &id083
    - Corporate Gifting
    - Direct Mail
    - Marketing Automation
    - Sales Engagement
    url: /providers/sendoso/
  layer: domain
  name: Sendoso
  provider: sendoso
  says: lists Sendoso as an integration
  source: https://calendly.com/integration/sendoso
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
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id084
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id085
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://calendly.com/integration/slack
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
    agent_band: agent-aware
    agent_readiness: 26.9
    band: thin
    in_catalog: true
    kin_score: 34.1
    mcp: &id086
      status: none
    slug: streak
    status: profiled
    tags: &id087
    - CRM
    - Gmail
    - Pipeline Management
    - Sales
    url: /providers/streak/
  layer: domain
  name: Streak
  provider: streak
  says: lists Streak as an integration
  source: https://calendly.com/integration/streak
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
    mcp: &id088
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id089
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://calendly.com/integration/stripe
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
    mcp: &id090
      status: none
    slug: tiktok
    status: profiled
    tags: &id091
    - Advertising
    - Commerce
    - Content
    - TikTok
    url: /providers/tiktok/
  layer: domain
  name: TikTok
  provider: tiktok
  says: lists TikTok as an integration
  source: https://calendly.com/integration/tiktok
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
    mcp: &id092
      source: https://www.typeform.com/developers/mcp
      status: verified
    slug: typeform
    status: profiled
    tags: &id093
    - Forms
    - Lead Capture
    - Software-as-a-Service
    - Surveys
    url: /providers/typeform/
  layer: domain
  name: Typeform
  provider: typeform
  says: lists Typeform as an integration
  source: https://calendly.com/integration/typeform
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
    agent_readiness: 61.8
    band: strong
    in_catalog: true
    kin_score: 66.1
    mcp: &id094
      source: https://github.com/WebexSamples/webex-messaging-mcp-server
      status: verified
    slug: webex
    status: profiled
    tags: &id095
    - Calling
    - Collaboration
    - Communications
    - Enterprise
    url: /providers/webex/
  layer: domain
  name: Webex
  provider: webex
  says: lists Webex as an integration
  source: https://calendly.com/integration/webex
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
    agent_readiness: 53.8
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id096
      source: https://docs.workato.com/mcp.html
      status: verified
    slug: workato
    status: profiled
    tags: &id097
    - AI Agents
    - API Management
    - Automation
    - B2B
    url: /providers/workato/
  layer: common
  name: Workato
  provider: workato
  says: lists Workato as an integration
  source: https://calendly.com/integration/workato
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
    agent_band: agent-native
    agent_readiness: 46.7
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id098
      source: https://github.com/Yelp/yelp-mcp
      status: verified
    slug: yelp
    status: profiled
    tags: &id099
    - Business Data
    - Local Search
    - Restaurant
    - Reviews
    url: /providers/yelp/
  layer: domain
  name: Yelp
  provider: yelp
  says: lists Yelp as an integration
  source: https://calendly.com/integration/yelp
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
    mcp: &id100
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id101
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://calendly.com/integration/zapier
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.10
    key: talent-acquisition-management
    name: Talent Acquisition Management
    url: /capabilities/talent-acquisition-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.4
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id102
      source: https://www.zoho.com/mcp/
      status: verified
    slug: zoho
    status: profiled
    tags: &id103
    - Analytics
    - CRM
    - Collaboration
    - Customer Service
    url: /providers/zoho/
  layer: domain
  name: Zoho Recruit
  provider: zoho
  says: lists Zoho Recruit as an integration
  source: https://calendly.com/integration/zoho-recruit
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
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id104
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id105
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: domain
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://calendly.com/integration/zoom
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.10
    key: AE-230.30.10
    name: Data Enrichment
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.0
    band: exemplar
    in_catalog: true
    kin_score: 86.8
    mcp: &id106
      source: https://github.com/Zoominfo/zoominfo-mcp-plugin
      status: verified
    slug: zoominfo
    status: profiled
    tags: &id107
    - B2B
    - B2B Data
    - Company Data
    - Contact Database
    url: /providers/zoominfo/
  layer: domain
  name: ZoomInfo
  provider: zoominfo
  says: lists ZoomInfo as an integration
  source: https://calendly.com/integration/zoominfo
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/booking-scheduling/calendly/
providers:
- agent_band: agent-ready
  agent_readiness: 51.0
  band: exemplar
  in_catalog: true
  kin_score: 81.1
  mcp: *id002
  name: ActiveCampaign
  slug: activecampaign
  status: profiled
  tags: *id003
  url: /providers/activecampaign/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id004
  name: AWeber
  slug: aweber
  status: profiled
  tags: *id005
  url: /providers/aweber/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: developing
  in_catalog: true
  kin_score: 54.1
  mcp: *id006
  name: CallRail
  slug: callrail
  status: profiled
  tags: *id007
  url: /providers/callrail/
- agent_band: agent-aware
  agent_readiness: 26.1
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id008
  name: Chatbase
  slug: chatbase
  status: profiled
  tags: *id009
  url: /providers/chatbase/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: strong
  in_catalog: true
  kin_score: 59.3
  mcp: *id010
  name: Clearbit
  slug: clearbit
  status: profiled
  tags: *id011
  url: /providers/clearbit/
- agent_band: agent-ready
  agent_readiness: 58.1
  band: exemplar
  in_catalog: true
  kin_score: 77.2
  mcp: *id012
  name: Close
  slug: close
  status: profiled
  tags: *id013
  url: /providers/close/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: exemplar
  in_catalog: true
  kin_score: 66.5
  mcp: *id014
  name: Gong
  slug: gong
  status: profiled
  tags: *id015
  url: /providers/gong/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id016
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id017
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id018
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id019
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id020
  name: Google Crashlytics
  slug: google-firebase
  status: profiled
  tags: *id021
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: developing
  in_catalog: true
  kin_score: 53.1
  mcp: *id022
  name: Google Forms
  slug: google-forms
  status: profiled
  tags: *id023
  url: /providers/google-forms/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: developing
  in_catalog: true
  kin_score: 52.2
  mcp: *id024
  name: Google Meet
  slug: google-meet
  status: profiled
  tags: *id025
  url: /providers/google-meet/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.0
  mcp: *id026
  name: GoTo Meeting
  slug: goto
  status: profiled
  tags: *id027
  url: /providers/goto/
- agent_band: agent-ready
  agent_readiness: 60.3
  band: exemplar
  in_catalog: true
  kin_score: 77.9
  mcp: *id028
  name: Greenhouse
  slug: greenhouse
  status: profiled
  tags: *id029
  url: /providers/greenhouse/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id030
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id031
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id032
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id033
  url: /providers/intercom/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 27.4
  mcp: *id034
  name: JazzHR
  slug: jazzhr
  status: profiled
  tags: *id035
  url: /providers/jazzhr/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 70.2
  mcp: *id036
  name: Jotform
  slug: jotform
  status: profiled
  tags: *id037
  url: /providers/jotform/
- agent_band: agent-ready
  agent_readiness: 51.9
  band: developing
  in_catalog: true
  kin_score: 40.1
  mcp: *id038
  name: Kajabi
  slug: kajabi
  status: profiled
  tags: *id039
  url: /providers/kajabi/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 80.4
  mcp: *id040
  name: Kit
  slug: convertkit
  status: profiled
  tags: *id041
  url: /providers/convertkit/
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id042
  name: LinkedIn Ads
  slug: linkedin
  status: profiled
  tags: *id043
  url: /providers/linkedin/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 18.4
  mcp: *id044
  name: Loom
  slug: loom
  status: profiled
  tags: *id045
  url: /providers/loom/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id046
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id047
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id048
  name: Make
  slug: make
  status: profiled
  tags: *id049
  url: /providers/make/
- agent_band: agent-ready
  agent_readiness: 30.4
  band: strong
  in_catalog: true
  kin_score: 57.2
  mcp: *id050
  name: Marketo
  slug: marketo
  status: profiled
  tags: *id051
  url: /providers/marketo/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id052
  name: Meta Ads / Facebook Pixel
  slug: facebook
  status: profiled
  tags: *id053
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id054
  name: Microsoft Dynamics
  slug: microsoft-dynamics-365
  status: profiled
  tags: *id055
  url: /providers/microsoft-dynamics-365/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id056
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id057
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 51.2
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id058
  name: Nutshell
  slug: nutshell
  status: profiled
  tags: *id059
  url: /providers/nutshell/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: developing
  in_catalog: true
  kin_score: 43.6
  mcp: *id060
  name: ON24
  slug: on24
  status: profiled
  tags: *id061
  url: /providers/on24/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 70.8
  mcp: *id062
  name: Outlook / Microsoft 365
  slug: microsoft-outlook
  status: profiled
  tags: *id063
  url: /providers/microsoft-outlook/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 60.7
  mcp: *id064
  name: Pardot
  slug: pardot
  status: profiled
  tags: *id065
  url: /providers/pardot/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id066
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id067
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 57.0
  mcp: *id068
  name: Pendo
  slug: pendoio
  status: profiled
  tags: *id069
  url: /providers/pendoio/
- agent_band: agent-ready
  agent_readiness: 31.1
  band: strong
  in_catalog: true
  kin_score: 65.5
  mcp: *id070
  name: Pipedream
  slug: pipedream
  status: profiled
  tags: *id071
  url: /providers/pipedream/
- agent_band: agent-native
  agent_readiness: 40.1
  band: strong
  in_catalog: true
  kin_score: 59.1
  mcp: *id072
  name: Podium
  slug: podium
  status: profiled
  tags: *id073
  url: /providers/podium/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: strong
  in_catalog: true
  kin_score: 62.1
  mcp: *id074
  name: Power Automate
  slug: microsoft-power-automate
  status: profiled
  tags: *id075
  url: /providers/microsoft-power-automate/
- agent_band: agent-ready
  agent_readiness: 55.2
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id076
  name: Reachdesk
  slug: reachdesk
  status: profiled
  tags: *id077
  url: /providers/reachdesk/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id078
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id079
  url: /providers/salesforce/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id080
  name: Segment
  slug: segment
  status: profiled
  tags: *id081
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 40.6
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id082
  name: Sendoso
  slug: sendoso
  status: profiled
  tags: *id083
  url: /providers/sendoso/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id084
  name: Slack
  slug: slack
  status: profiled
  tags: *id085
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 26.9
  band: thin
  in_catalog: true
  kin_score: 34.1
  mcp: *id086
  name: Streak
  slug: streak
  status: profiled
  tags: *id087
  url: /providers/streak/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id088
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id089
  url: /providers/stripe/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: developing
  in_catalog: true
  kin_score: 40.5
  mcp: *id090
  name: TikTok
  slug: tiktok
  status: profiled
  tags: *id091
  url: /providers/tiktok/
- agent_band: agent-ready
  agent_readiness: 42.6
  band: thin
  in_catalog: true
  kin_score: 36.0
  mcp: *id092
  name: Typeform
  slug: typeform
  status: profiled
  tags: *id093
  url: /providers/typeform/
- agent_band: agent-ready
  agent_readiness: 61.8
  band: strong
  in_catalog: true
  kin_score: 66.1
  mcp: *id094
  name: Webex
  slug: webex
  status: profiled
  tags: *id095
  url: /providers/webex/
- agent_band: agent-ready
  agent_readiness: 53.8
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id096
  name: Workato
  slug: workato
  status: profiled
  tags: *id097
  url: /providers/workato/
- agent_band: agent-native
  agent_readiness: 46.7
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id098
  name: Yelp
  slug: yelp
  status: profiled
  tags: *id099
  url: /providers/yelp/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id100
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id101
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 32.4
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id102
  name: Zoho Recruit
  slug: zoho
  status: profiled
  tags: *id103
  url: /providers/zoho/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id104
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id105
  url: /providers/zoom/
- agent_band: agent-ready
  agent_readiness: 63.0
  band: exemplar
  in_catalog: true
  kin_score: 86.8
  mcp: *id106
  name: ZoomInfo
  slug: zoominfo
  status: profiled
  tags: *id107
  url: /providers/zoominfo/
siblings:
- name: Acuity Scheduling
  rows: 38
  url: /applications/booking-scheduling/acuity-scheduling/
- name: Booksy Biz
  rows: 6
  url: /applications/booking-scheduling/booksy-biz/
- name: Cal.com
  rows: 71
  url: /applications/booking-scheduling/cal-com/
- name: Easy!Appointments
  rows: 1
  url: /applications/booking-scheduling/easy-appointments/
- name: LibreBooking
  rows: 8
  url: /applications/booking-scheduling/librebooking/
- name: Rallly
  rows: 13
  url: /applications/booking-scheduling/rallly/
sitemap: true
title: 'Calendly: Appointment Booking & Scheduling reference app'
---
