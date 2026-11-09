---
app: Chatwoot
app_slug: chatwoot
app_url: https://github.com/chatwoot/chatwoot
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-430.30
  key: contact-centre-operations-management
  layer: domain
  name: Contact Centre Operations Management
  providers:
  - Twilio (twilio-ruby, @twilio/voice-sdk)
  url: /capabilities/contact-centre-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - LeadSquared
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830
  key: knowledge-management
  layer: domain
  name: Knowledge Management
  providers:
  - Notion
  url: /capabilities/knowledge-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200
  key: software-product-engineering-management
  layer: domain
  name: Software Product Engineering Management
  providers:
  - Linear
  url: /capabilities/software-product-engineering-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Dyte
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.40.10
  key: AE-230.40.10
  layer: domain
  name: Web Scraping
  providers:
  - Firecrawl (firecrawl-sdk)
  url: /capabilities/web-data/
  via_parent: Web Data
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: domain
  name: WhatsApp & OTT Messaging
  providers:
  - Facebook Messenger (facebook-messenger, koala)
  - LINE (line-bot-api)
  - X / Twitter (twitty)
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-4220.50.20
  key: BC-4220.50.20
  layer: common
  name: Auto-Scaling Policy Management
  providers:
  - Judoscale (production group)
  url: /capabilities/capacity-performance-management-bc-4220-50/
  via_parent: Capacity & Performance Management
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - hCaptcha (@hcaptcha/vue3-hcaptcha)
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: common
  name: IP Geolocation
  providers:
  - MaxMind (maxminddb)
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Slack (slack-ruby-client)
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: common
  name: Machine Translation
  providers:
  - Google Cloud Translation
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Gmail (gmail_xoauth)
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Amazon CloudWatch (speedshop-cloudwatch)
  - Datadog
  - Elastic APM (elastic-apm)
  - New Relic (newrelic_rpm)
  - Scout APM (scout_apm)
  - Sentry (sentry-ruby, @sentry/vue)
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Shopify (shopify_api)
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Amplitude (@amplitude/analytics-browser)
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Apple Push Notification service (apnotic)
  - Firebase Cloud Messaging (fcm)
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3 (aws-sdk-s3)
  - Azure Blob (azure-blob)
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Google sign-in (omniauth-google-oauth2)
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES (aws-sdk-sesv2, aws-actionmailbox-ses)
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-610.60
  key: artificial-intelligence-management
  layer: agent
  name: Artificial Intelligence Management
  providers:
  - Dialogflow
  - OpenAI (ruby-openai)
  url: /capabilities/artificial-intelligence-management/
  via_parent: null
category:
  id: helpdesk-ticketing
  name: Help Desk & Customer Support
  url: /applications/helpdesk-ticketing/
counts:
  declared: 0
  observed: 33
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.chatwoot.app/latest/
- route: dependency manifest
  url: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
- route: dependency manifest
  url: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/package.json
- route: source code
  url: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/config/integration/apps.yml
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.0
    band: exemplar
    in_catalog: true
    kin_score: 71.0
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-cloudwatch
    status: profiled
    tags: &id002
    - Amazon Web Services
    - CloudWatch
    - Monitoring
    - Observability
    url: /providers/amazon-cloudwatch/
  layer: common
  name: Amazon CloudWatch (speedshop-cloudwatch)
  provider: amazon-cloudwatch
  says: ships the Amazon CloudWatch (speedshop-cloudwatch) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3 (aws-sdk-s3)
  provider: amazon-s3
  says: ships the Amazon S3 (aws-sdk-s3) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    agent_readiness: 39.4
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id005
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
  layer: common
  name: Amazon SES (aws-sdk-sesv2, aws-actionmailbox-ses)
  provider: amazon-ses
  says: ships the Amazon SES (aws-sdk-sesv2, aws-actionmailbox-ses) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    agent_readiness: 56.7
    band: strong
    in_catalog: true
    kin_score: 63.5
    mcp: &id007
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id008
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude (@amplitude/analytics-browser)
  provider: amplitude
  says: ships the Amplitude (@amplitude/analytics-browser) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id009
      status: none
    slug: apple
    status: profiled
    tags: &id010
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Apple Push Notification service (apnotic)
  provider: apple
  says: ships the Apple Push Notification service (apnotic) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    agent_band: agent-ready
    agent_readiness: 40.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id011
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id012
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob (azure-blob)
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob (azure-blob) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    agent_readiness: 49.6
    band: exemplar
    in_catalog: true
    kin_score: 79.2
    mcp: &id013
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id014
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: common
  name: Datadog
  provider: datadog
  says: ships the Datadog SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    agent_readiness: 38.2
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id015
      status: none
    slug: google-dialogflow
    status: profiled
    tags: &id016
    - Agents
    - Artificial Intelligence
    - Chatbots
    - Conversational AI
    url: /providers/google-dialogflow/
  layer: agent
  name: Dialogflow
  provider: google-dialogflow
  says: ships the Dialogflow SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
  tier: observed
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
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 28.4
    mcp: &id017
      status: none
    slug: dyte
    status: profiled
    tags: &id018
    - Real-Time
    - Video
    - Voice
    - WebRTC
    url: /providers/dyte/
  layer: domain
  name: Dyte
  provider: dyte
  says: ships the Dyte SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/config/integration/apps.yml
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
    agent_readiness: 28.6
    band: exemplar
    in_catalog: true
    kin_score: 70.2
    mcp: &id019
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id020
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
  layer: common
  name: Elastic APM (elastic-apm)
  provider: elastic
  says: ships the Elastic APM (elastic-apm) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id021
      status: none
    slug: facebook
    status: profiled
    tags: &id022
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook Messenger (facebook-messenger, koala)
  provider: facebook
  says: ships the Facebook Messenger (facebook-messenger, koala) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id023
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id024
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase Cloud Messaging (fcm)
  provider: firebase
  says: ships the Firebase Cloud Messaging (fcm) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    agent_readiness: 40.1
    band: developing
    in_catalog: true
    kin_score: 49.5
    mcp: &id025
      source: https://docs.firecrawl.dev/mcp-server
      status: verified
    slug: firecrawl
    status: profiled
    tags: &id026
    - Crawling
    - Data Extraction
    - URLs
    - Web Scraping
    url: /providers/firecrawl/
  layer: domain
  name: Firecrawl (firecrawl-sdk)
  provider: firecrawl
  says: ships the Firecrawl (firecrawl-sdk) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id027
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id028
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: common
  name: Gmail (gmail_xoauth)
  provider: google-gmail
  says: ships the Gmail (gmail_xoauth) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    agent_band: agent-ready
    agent_readiness: 45.3
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id029
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id030
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.9
    band: developing
    in_catalog: true
    kin_score: 51.6
    mcp: &id031
      status: none
    slug: google-translate
    status: profiled
    tags: &id032
    - Google Cloud
    - Internationalization
    - Language Detection
    - Localization
    url: /providers/google-translate/
  layer: common
  name: Google Cloud Translation
  provider: google-translate
  says: ships the Google Cloud Translation SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id033
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id034
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in (omniauth-google-oauth2)
  provider: google-identity-platform
  says: ships the Google sign-in (omniauth-google-oauth2) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 31.5
    mcp: &id035
      status: none
    slug: hcaptcha
    status: profiled
    tags: &id036
    - Bot Defense
    - CAPTCHA
    - Privacy
    - hCaptcha
    url: /providers/hcaptcha/
  layer: common
  name: hCaptcha (@hcaptcha/vue3-hcaptcha)
  provider: hcaptcha
  says: ships the hCaptcha (@hcaptcha/vue3-hcaptcha) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.50.20
    key: BC-4220.50.20
    name: Auto-Scaling Policy Management
    url: /capabilities/capacity-performance-management-bc-4220-50/
    via_parent: Capacity & Performance Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.4
    band: emerging
    in_catalog: true
    kin_score: 17.3
    mcp: &id037
      status: unknown
    slug: judoscale
    status: profiled
    tags: &id038
    - Auto-Scaling
    - Cloud
    - Company
    - DevOps
    url: /providers/judoscale/
  layer: common
  name: Judoscale (production group)
  provider: judoscale
  says: ships the Judoscale (production group) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    agent_readiness: 35.9
    band: strong
    in_catalog: true
    kin_score: 55.5
    mcp: &id039
      status: none
    slug: leadsquared
    status: profiled
    tags: &id040
    - CRM
    - Lead Management
    - Marketing Automation
    - Sales Automation
    url: /providers/leadsquared/
  layer: domain
  name: LeadSquared
  provider: leadsquared
  says: ships the LeadSquared SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/config/integration/apps.yml
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
    agent_band: agent-native
    agent_readiness: 47.9
    band: exemplar
    in_catalog: true
    kin_score: 74.5
    mcp: &id041
      source: https://github.com/line/line-bot-mcp-server
      status: verified
    slug: line
    status: profiled
    tags: &id042
    - Chatbots
    - Messaging
    - Mini Apps
    - Social Login
    url: /providers/line/
  layer: domain
  name: LINE (line-bot-api)
  provider: line
  says: ships the LINE (line-bot-api) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.5
    band: thin
    in_catalog: true
    kin_score: 38.1
    mcp: &id043
      source: https://linear.app/docs/mcp
      status: verified
    slug: linear-app
    status: profiled
    tags: &id044
    - Issue Tracking
    - Productivity
    - Project Management
    - Software-as-a-Service
    url: /providers/linear-app/
  layer: domain
  name: Linear
  provider: linear-app
  says: ships the Linear SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/config/integration/apps.yml
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
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id045
      status: none
    slug: maxmind
    status: profiled
    tags: &id046
    - Fraud Prevention
    - Geolocation
    - IP Intelligence
    - Risk Scoring
    url: /providers/maxmind/
  layer: common
  name: MaxMind (maxminddb)
  provider: maxmind
  says: ships the MaxMind (maxminddb) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    band: exemplar
    in_catalog: true
    kin_score: 76.5
    mcp: &id047
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id048
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic (newrelic_rpm)
  provider: new-relic
  says: ships the New Relic (newrelic_rpm) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
  tier: observed
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
    mcp: &id049
      source: https://developers.notion.com/docs/mcp
      status: verified
    slug: notion
    status: profiled
    tags: &id050
    - Collaboration
    - Database
    - Ideas
    - Notes
    url: /providers/notion/
  layer: domain
  name: Notion
  provider: notion
  says: ships the Notion SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/config/integration/apps.yml
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
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id051
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id052
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI (ruby-openai)
  provider: openai
  says: ships the OpenAI (ruby-openai) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    agent_band: agent-aware
    agent_readiness: 22.2
    band: thin
    in_catalog: true
    kin_score: 31.9
    mcp: &id053
      source: https://github.com/scoutapp/scout-mcp-local
      status: verified
    slug: scout-apm
    status: profiled
    tags: &id054
    - AI-assisted
    - APM
    - Company
    - Monitoring
    url: /providers/scout-apm/
  layer: common
  name: Scout APM (scout_apm)
  provider: scout-apm
  says: ships the Scout APM (scout_apm) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    mcp: &id055
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id056
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry (sentry-ruby, @sentry/vue)
  provider: sentry-system
  says: ships the Sentry (sentry-ruby, @sentry/vue) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    agent_band: agent-ready
    agent_readiness: 52.5
    band: exemplar
    in_catalog: true
    kin_score: 84.6
    mcp: &id057
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id058
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: common
  name: Shopify (shopify_api)
  provider: shopify
  says: ships the Shopify (shopify_api) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id059
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id060
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack (slack-ruby-client)
  provider: slack
  says: ships the Slack (slack-ruby-client) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
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
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id061
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id062
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-430.30
    key: contact-centre-operations-management
    name: Contact Centre Operations Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.4
    band: exemplar
    in_catalog: true
    kin_score: 90.3
    mcp: &id063
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id064
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: domain
  name: Twilio (twilio-ruby, @twilio/voice-sdk)
  provider: twilio
  says: ships the Twilio (twilio-ruby, @twilio/voice-sdk) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/package.json
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
    agent_band: agent-native
    agent_readiness: 61.2
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id065
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id066
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X / Twitter (twitty)
  provider: x
  says: ships the X / Twitter (twitty) SDK or integration code
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/helpdesk-ticketing/chatwoot/
providers:
- agent_band: agent-aware
  agent_readiness: 28.0
  band: exemplar
  in_catalog: true
  kin_score: 71.0
  mcp: *id001
  name: Amazon CloudWatch (speedshop-cloudwatch)
  slug: amazon-cloudwatch
  status: profiled
  tags: *id002
  url: /providers/amazon-cloudwatch/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id003
  name: Amazon S3 (aws-sdk-s3)
  slug: amazon-s3
  status: profiled
  tags: *id004
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 39.4
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id005
  name: Amazon SES (aws-sdk-sesv2, aws-actionmailbox-ses)
  slug: amazon-ses
  status: profiled
  tags: *id006
  url: /providers/amazon-ses/
- agent_band: agent-ready
  agent_readiness: 56.7
  band: strong
  in_catalog: true
  kin_score: 63.5
  mcp: *id007
  name: Amplitude (@amplitude/analytics-browser)
  slug: amplitude
  status: profiled
  tags: *id008
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id009
  name: Apple Push Notification service (apnotic)
  slug: apple
  status: profiled
  tags: *id010
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id011
  name: Azure Blob (azure-blob)
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id012
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 49.6
  band: exemplar
  in_catalog: true
  kin_score: 79.2
  mcp: *id013
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id014
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 38.2
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id015
  name: Dialogflow
  slug: google-dialogflow
  status: profiled
  tags: *id016
  url: /providers/google-dialogflow/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 28.4
  mcp: *id017
  name: Dyte
  slug: dyte
  status: profiled
  tags: *id018
  url: /providers/dyte/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: exemplar
  in_catalog: true
  kin_score: 70.2
  mcp: *id019
  name: Elastic APM (elastic-apm)
  slug: elastic
  status: profiled
  tags: *id020
  url: /providers/elastic/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id021
  name: Facebook Messenger (facebook-messenger, koala)
  slug: facebook
  status: profiled
  tags: *id022
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id023
  name: Firebase Cloud Messaging (fcm)
  slug: firebase
  status: profiled
  tags: *id024
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: developing
  in_catalog: true
  kin_score: 49.5
  mcp: *id025
  name: Firecrawl (firecrawl-sdk)
  slug: firecrawl
  status: profiled
  tags: *id026
  url: /providers/firecrawl/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id027
  name: Gmail (gmail_xoauth)
  slug: google-gmail
  status: profiled
  tags: *id028
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id029
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id030
  url: /providers/gcp-cloud-storage/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: developing
  in_catalog: true
  kin_score: 51.6
  mcp: *id031
  name: Google Cloud Translation
  slug: google-translate
  status: profiled
  tags: *id032
  url: /providers/google-translate/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id033
  name: Google sign-in (omniauth-google-oauth2)
  slug: google-identity-platform
  status: profiled
  tags: *id034
  url: /providers/google-identity-platform/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id035
  name: hCaptcha (@hcaptcha/vue3-hcaptcha)
  slug: hcaptcha
  status: profiled
  tags: *id036
  url: /providers/hcaptcha/
- agent_band: agent-aware
  agent_readiness: 5.4
  band: emerging
  in_catalog: true
  kin_score: 17.3
  mcp: *id037
  name: Judoscale (production group)
  slug: judoscale
  status: profiled
  tags: *id038
  url: /providers/judoscale/
- agent_band: agent-ready
  agent_readiness: 35.9
  band: strong
  in_catalog: true
  kin_score: 55.5
  mcp: *id039
  name: LeadSquared
  slug: leadsquared
  status: profiled
  tags: *id040
  url: /providers/leadsquared/
- agent_band: agent-native
  agent_readiness: 47.9
  band: exemplar
  in_catalog: true
  kin_score: 74.5
  mcp: *id041
  name: LINE (line-bot-api)
  slug: line
  status: profiled
  tags: *id042
  url: /providers/line/
- agent_band: agent-ready
  agent_readiness: 35.5
  band: thin
  in_catalog: true
  kin_score: 38.1
  mcp: *id043
  name: Linear
  slug: linear-app
  status: profiled
  tags: *id044
  url: /providers/linear-app/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id045
  name: MaxMind (maxminddb)
  slug: maxmind
  status: profiled
  tags: *id046
  url: /providers/maxmind/
- agent_band: agent-ready
  agent_readiness: 45.7
  band: exemplar
  in_catalog: true
  kin_score: 76.5
  mcp: *id047
  name: New Relic (newrelic_rpm)
  slug: new-relic
  status: profiled
  tags: *id048
  url: /providers/new-relic/
- agent_band: agent-ready
  agent_readiness: 54.9
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id049
  name: Notion
  slug: notion
  status: profiled
  tags: *id050
  url: /providers/notion/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id051
  name: OpenAI (ruby-openai)
  slug: openai
  status: profiled
  tags: *id052
  url: /providers/openai/
- agent_band: agent-aware
  agent_readiness: 22.2
  band: thin
  in_catalog: true
  kin_score: 31.9
  mcp: *id053
  name: Scout APM (scout_apm)
  slug: scout-apm
  status: profiled
  tags: *id054
  url: /providers/scout-apm/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id055
  name: Sentry (sentry-ruby, @sentry/vue)
  slug: sentry-system
  status: profiled
  tags: *id056
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 52.5
  band: exemplar
  in_catalog: true
  kin_score: 84.6
  mcp: *id057
  name: Shopify (shopify_api)
  slug: shopify
  status: profiled
  tags: *id058
  url: /providers/shopify/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id059
  name: Slack (slack-ruby-client)
  slug: slack
  status: profiled
  tags: *id060
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id061
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id062
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 90.3
  mcp: *id063
  name: Twilio (twilio-ruby, @twilio/voice-sdk)
  slug: twilio
  status: profiled
  tags: *id064
  url: /providers/twilio/
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id065
  name: X / Twitter (twitty)
  slug: x
  status: profiled
  tags: *id066
  url: /providers/x/
siblings:
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
- name: Zammad
  rows: 23
  url: /applications/helpdesk-ticketing/zammad/
- name: Zendesk
  rows: 2
  url: /applications/helpdesk-ticketing/zendesk/
sitemap: true
title: 'Chatwoot: Help Desk & Customer Support reference app'
---
