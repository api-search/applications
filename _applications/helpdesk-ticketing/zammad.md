---
app: Zammad
app_slug: zammad
app_url: https://github.com/zammad/zammad
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-430.30
  key: contact-centre-operations-management
  layer: domain
  name: Contact Centre Operations Management
  providers:
  - Placetel CTI
  - sipgate.io CTI
  url: /capabilities/contact-centre-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: domain
  name: Customer Data Management
  providers:
  - Clearbit
  - Microsoft Exchange (viewpoint EWS, importer)
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: domain
  name: Customer Service Management
  providers:
  - Freshdesk (importer)
  - Kayako (importer)
  - Zendesk (zendesk_api importer)
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: domain
  name: SMS
  providers:
  - Massenversand (SMS driver)
  - MessageBird / Bird (messagebird-rest)
  - Twilio (twilio-ruby, SMS driver)
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: domain
  name: Search and Discovery Management
  providers:
  - Elasticsearch (SaaS)
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: domain
  name: WhatsApp & OTT Messaging
  providers:
  - Facebook (omniauth-facebook, koala)
  - Telegram (telegram-bot-ruby)
  - WhatsApp (whatsapp_sdk)
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Microsoft 365 Graph email channel
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3 (aws-sdk-s3)
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - GitHub (omniauth-github)
  - GitLab (omniauth-gitlab)
  - Google sign-in (omniauth-google-oauth2)
  - LinkedIn (omniauth-linkedin-oauth2)
  - Microsoft (omniauth-microsoft-office365)
  - Weibo (omniauth-weibo-oauth2)
  - X / Twitter (omniauth-twitter)
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: helpdesk-ticketing
  name: Help Desk & Customer Support
  url: /applications/helpdesk-ticketing/
counts:
  declared: 3
  observed: 20
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
- route: documentation
  url: https://admin-docs.zammad.org/en/latest/system/integrations.html
- route: source code
  url: https://api.github.com/repos/zammad/zammad/contents/app/models/channel/driver/sms?ref=develop
- route: source code
  url: https://api.github.com/repos/zammad/zammad/contents/app/models/channel/driver?ref=develop
- route: source code
  url: https://api.github.com/repos/zammad/zammad/contents/lib/import?ref=develop
integrations:
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3 (aws-sdk-s3)
  provider: amazon-s3
  says: ships the Amazon S3 (aws-sdk-s3) SDK or integration code
  source: https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
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
    agent_readiness: 24.6
    band: strong
    in_catalog: true
    kin_score: 59.3
    mcp: &id003
      status: none
    slug: clearbit
    status: profiled
    tags: &id004
    - B2B
    - Data Enrichment
    - Reveal
    - Sales Intelligence
    url: /providers/clearbit/
  layer: domain
  name: Clearbit
  provider: clearbit
  says: ships the Clearbit SDK or integration code
  source: https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id007
      status: none
    slug: facebook
    status: profiled
    tags: &id008
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook (omniauth-facebook, koala)
  provider: facebook
  says: ships the Facebook (omniauth-facebook, koala) SDK or integration code
  source: https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
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
    agent_readiness: 35.0
    band: thin
    in_catalog: true
    kin_score: 29.7
    mcp: &id009
      status: none
    slug: freshdesk
    status: profiled
    tags: &id010
    - Application
    - Automation
    - Customer Service
    - Help Desk
    url: /providers/freshdesk/
  layer: domain
  name: Freshdesk (importer)
  provider: freshdesk
  says: ships the Freshdesk (importer) SDK or integration code
  source: https://api.github.com/repos/zammad/zammad/contents/lib/import?ref=develop
  tier: observed
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
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id011
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id012
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub (omniauth-github)
  provider: github
  says: ships the GitHub (omniauth-github) SDK or integration code
  source: https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id013
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id014
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: common
  name: GitLab (omniauth-gitlab)
  provider: gitlab
  says: ships the GitLab (omniauth-gitlab) SDK or integration code
  source: https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
  tier: observed
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
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id015
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id016
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in (omniauth-google-oauth2)
  provider: google-identity-platform
  says: ships the Google sign-in (omniauth-google-oauth2) SDK or integration code
  source: https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 23.4
    mcp: &id017
      status: none
    slug: kayako
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Company
    - Customer Service
    - Software-as-a-Service
    url: /providers/kayako/
  layer: domain
  name: Kayako (importer)
  provider: kayako
  says: ships the Kayako (importer) SDK or integration code
  source: https://api.github.com/repos/zammad/zammad/contents/lib/import?ref=develop
  tier: observed
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
    agent_readiness: 46.5
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id019
      status: none
    slug: linkedin
    status: profiled
    tags: &id020
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: common
  name: LinkedIn (omniauth-linkedin-oauth2)
  provider: linkedin
  says: ships the LinkedIn (omniauth-linkedin-oauth2) SDK or integration code
  source: https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.3
    mcp: &id021
      status: unknown
    slug: massenversand
    status: profiled
    tags: &id022
    - Germany
    - Marketing
    - Messaging
    - SMS
    url: /providers/massenversand/
  layer: domain
  name: Massenversand (SMS driver)
  provider: massenversand
  says: ships the Massenversand (SMS driver) SDK or integration code
  source: https://api.github.com/repos/zammad/zammad/contents/app/models/channel/driver/sms?ref=develop
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
    agent_band: agent-native
    agent_readiness: 70.3
    band: developing
    in_catalog: true
    kin_score: 50.0
    mcp: &id023
      source: https://github.com/messagebird/bird-ai
      status: verified
    slug: bird
    status: profiled
    tags: &id024
    - Communications
    - Email
    - SMS
    - WhatsApp
    url: /providers/bird/
  layer: domain
  name: MessageBird / Bird (messagebird-rest)
  provider: bird
  says: ships the MessageBird / Bird (messagebird-rest) SDK or integration code
  source: https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
  tier: observed
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
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id025
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id026
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft (omniauth-microsoft-office365)
  provider: microsoft-entra
  says: ships the Microsoft (omniauth-microsoft-office365) SDK or integration code
  source: https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
  tier: observed
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
    agent_readiness: 39.0
    band: exemplar
    in_catalog: true
    kin_score: 69.7
    mcp: &id027
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-graph
    status: profiled
    tags: &id028
    - Azure AD
    - Collaboration
    - Contacts
    - Microsoft Graph
    url: /providers/microsoft-graph/
  layer: common
  name: Microsoft 365 Graph email channel
  provider: microsoft-graph
  says: ships the Microsoft 365 Graph email channel SDK or integration code
  source: https://api.github.com/repos/zammad/zammad/contents/app/models/channel/driver?ref=develop
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
    agent_band: agent-ready
    agent_readiness: 36.0
    band: strong
    in_catalog: true
    kin_score: 64.9
    mcp: &id029
      status: none
    slug: microsoft-exchange
    status: profiled
    tags: &id030
    - Calendar
    - Collaboration
    - Contacts
    - Email
    url: /providers/microsoft-exchange/
  layer: domain
  name: Microsoft Exchange (viewpoint EWS, importer)
  provider: microsoft-exchange
  says: ships the Microsoft Exchange (viewpoint EWS, importer) SDK or integration code
  source: https://api.github.com/repos/zammad/zammad/contents/lib/import?ref=develop
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id035
      status: none
    slug: telegram
    status: profiled
    tags: &id036
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: domain
  name: Telegram (telegram-bot-ruby)
  provider: telegram
  says: ships the Telegram (telegram-bot-ruby) SDK or integration code
  source: https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
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
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id037
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id038
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: domain
  name: Twilio (twilio-ruby, SMS driver)
  provider: twilio
  says: ships the Twilio (twilio-ruby, SMS driver) SDK or integration code
  source: https://api.github.com/repos/zammad/zammad/contents/app/models/channel/driver/sms?ref=develop
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 1.1
    band: minimal
    in_catalog: true
    kin_score: 8.0
    mcp: &id039
      status: none
    slug: weibo
    status: profiled
    tags: &id040
    - China
    - Company
    - Microblogging
    - Social Media
    url: /providers/weibo/
  layer: common
  name: Weibo (omniauth-weibo-oauth2)
  provider: weibo
  says: ships the Weibo (omniauth-weibo-oauth2) SDK or integration code
  source: https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 72.3
    mcp: &id041
      status: none
    slug: whatsapp
    status: profiled
    tags: &id042
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: domain
  name: WhatsApp (whatsapp_sdk)
  provider: whatsapp
  says: ships the WhatsApp (whatsapp_sdk) SDK or integration code
  source: https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id043
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id044
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: common
  name: X / Twitter (omniauth-twitter)
  provider: x
  says: ships the X / Twitter (omniauth-twitter) SDK or integration code
  source: https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
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
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id045
      status: none
    slug: zendesk
    status: profiled
    tags: &id046
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk (zendesk_api importer)
  provider: zendesk
  says: ships the Zendesk (zendesk_api importer) SDK or integration code
  source: https://api.github.com/repos/zammad/zammad/contents/lib/import?ref=develop
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
    mcp: &id005
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id006
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
  layer: domain
  name: Elasticsearch (SaaS)
  provider: elastic
  says: lists Elasticsearch (SaaS) as an integration
  source: https://admin-docs.zammad.org/en/latest/system/integrations.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.30
    key: contact-centre-operations-management
    name: Contact Centre Operations Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.8
    band: emerging
    in_catalog: true
    kin_score: 15.5
    mcp: &id031
      status: none
    slug: placetel
    status: profiled
    tags: &id032
    - Call Center
    - Collaboration
    - Messaging
    - Video Meetings
    url: /providers/placetel/
  layer: domain
  name: Placetel CTI
  provider: placetel
  says: lists Placetel CTI as an integration
  source: https://admin-docs.zammad.org/en/latest/system/integrations.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.30
    key: contact-centre-operations-management
    name: Contact Centre Operations Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 6.3
    band: thin
    in_catalog: true
    kin_score: 27.1
    mcp: &id033
      source: https://github.com/sipgate/sipgate-ai-demo-auth-mcp-server
      status: documented
    slug: sipgate
    status: profiled
    tags: &id034
    - Cloud
    - Communications
    - Company
    - Telephony
    url: /providers/sipgate/
  layer: domain
  name: sipgate.io CTI
  provider: sipgate
  says: lists sipgate.io CTI as an integration
  source: https://admin-docs.zammad.org/en/latest/system/integrations.html
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/helpdesk-ticketing/zammad/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id001
  name: Amazon S3 (aws-sdk-s3)
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: strong
  in_catalog: true
  kin_score: 59.3
  mcp: *id003
  name: Clearbit
  slug: clearbit
  status: profiled
  tags: *id004
  url: /providers/clearbit/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id005
  name: Elasticsearch (SaaS)
  slug: elastic
  status: profiled
  tags: *id006
  url: /providers/elastic/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id007
  name: Facebook (omniauth-facebook, koala)
  slug: facebook
  status: profiled
  tags: *id008
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: thin
  in_catalog: true
  kin_score: 29.7
  mcp: *id009
  name: Freshdesk (importer)
  slug: freshdesk
  status: profiled
  tags: *id010
  url: /providers/freshdesk/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id011
  name: GitHub (omniauth-github)
  slug: github
  status: profiled
  tags: *id012
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id013
  name: GitLab (omniauth-gitlab)
  slug: gitlab
  status: profiled
  tags: *id014
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id015
  name: Google sign-in (omniauth-google-oauth2)
  slug: google-identity-platform
  status: profiled
  tags: *id016
  url: /providers/google-identity-platform/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 23.4
  mcp: *id017
  name: Kayako (importer)
  slug: kayako
  status: profiled
  tags: *id018
  url: /providers/kayako/
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id019
  name: LinkedIn (omniauth-linkedin-oauth2)
  slug: linkedin
  status: profiled
  tags: *id020
  url: /providers/linkedin/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.3
  mcp: *id021
  name: Massenversand (SMS driver)
  slug: massenversand
  status: profiled
  tags: *id022
  url: /providers/massenversand/
- agent_band: agent-native
  agent_readiness: 70.3
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id023
  name: MessageBird / Bird (messagebird-rest)
  slug: bird
  status: profiled
  tags: *id024
  url: /providers/bird/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id025
  name: Microsoft (omniauth-microsoft-office365)
  slug: microsoft-entra
  status: profiled
  tags: *id026
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 39.0
  band: exemplar
  in_catalog: true
  kin_score: 69.7
  mcp: *id027
  name: Microsoft 365 Graph email channel
  slug: microsoft-graph
  status: profiled
  tags: *id028
  url: /providers/microsoft-graph/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: strong
  in_catalog: true
  kin_score: 64.9
  mcp: *id029
  name: Microsoft Exchange (viewpoint EWS, importer)
  slug: microsoft-exchange
  status: profiled
  tags: *id030
  url: /providers/microsoft-exchange/
- agent_band: agent-aware
  agent_readiness: 14.8
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id031
  name: Placetel CTI
  slug: placetel
  status: profiled
  tags: *id032
  url: /providers/placetel/
- agent_band: agent-aware
  agent_readiness: 6.3
  band: thin
  in_catalog: true
  kin_score: 27.1
  mcp: *id033
  name: sipgate.io CTI
  slug: sipgate
  status: profiled
  tags: *id034
  url: /providers/sipgate/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id035
  name: Telegram (telegram-bot-ruby)
  slug: telegram
  status: profiled
  tags: *id036
  url: /providers/telegram/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id037
  name: Twilio (twilio-ruby, SMS driver)
  slug: twilio
  status: profiled
  tags: *id038
  url: /providers/twilio/
- agent_band: human-only
  agent_readiness: 1.1
  band: minimal
  in_catalog: true
  kin_score: 8.0
  mcp: *id039
  name: Weibo (omniauth-weibo-oauth2)
  slug: weibo
  status: profiled
  tags: *id040
  url: /providers/weibo/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id041
  name: WhatsApp (whatsapp_sdk)
  slug: whatsapp
  status: profiled
  tags: *id042
  url: /providers/whatsapp/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id043
  name: X / Twitter (omniauth-twitter)
  slug: x
  status: profiled
  tags: *id044
  url: /providers/x/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id045
  name: Zendesk (zendesk_api importer)
  slug: zendesk
  status: profiled
  tags: *id046
  url: /providers/zendesk/
siblings:
- name: Chatwoot
  rows: 33
  url: /applications/helpdesk-ticketing/chatwoot/
- name: FreeScout
  rows: 12
  url: /applications/helpdesk-ticketing/freescout/
- name: Freshdesk
  rows: 6
  url: /applications/helpdesk-ticketing/freshdesk/
- name: Help Scout
  rows: 24
  url: /applications/helpdesk-ticketing/help-scout/
- name: Intercom
  rows: 1
  url: /applications/helpdesk-ticketing/intercom/
- name: Zendesk
  rows: 2
  url: /applications/helpdesk-ticketing/zendesk/
sitemap: true
title: 'Zammad: Help Desk & Customer Support reference app'
---
