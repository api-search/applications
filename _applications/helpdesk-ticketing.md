---
access: understanding
agent_layer:
- app: Chatwoot
  finding: ships its own AI agent layer on ruby-openai, ruby_llm and ai-agents gems (BYO LLM); Captain AI crawls help centers via Firecrawl
  source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
  tier: observed
- app: Zammad
  finding: admin docs carry an AI section (AI Providers, Ticket Summary, Writing Assistant, AI Agents)
  source: https://admin-docs.zammad.org/en/latest/system/integrations.html
  tier: declared
- app: Intercom
  finding: Intercom publishes its own MCP server
  source: https://developers.intercom.com/docs/guides/mcp
  tier: declared
apps:
- anchor: zammad
  counts:
    declared: 3
    observed: 20
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
    layer: domain
    name: sipgate.io CTI
    provider: sipgate
    says: lists sipgate.io CTI as an integration
    source: https://admin-docs.zammad.org/en/latest/system/integrations.html
    tier: declared
  kind: self-hosted
  name: Zammad
  page: /applications/helpdesk-ticketing/zammad/
  slug: zammad
  url: https://github.com/zammad/zammad
- anchor: chatwoot
  counts:
    declared: 0
    observed: 33
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
    layer: domain
    name: X / Twitter (twitty)
    provider: x
    says: ships the X / Twitter (twitty) SDK or integration code
    source: https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
    tier: observed
  kind: open-source-saas
  name: Chatwoot
  page: /applications/helpdesk-ticketing/chatwoot/
  slug: chatwoot
  url: https://github.com/chatwoot/chatwoot
- anchor: freescout
  counts:
    declared: 12
    observed: 0
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/freescout-help-desk/freescout/dist/composer.json
  - route: integrations page
    url: https://freescout.net/modules/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: Extra Security Module (reCAPTCHA)
    provider: google-recaptcha
    says: lists Extra Security Module (reCAPTCHA) as an integration
    source: https://freescout.net/modules/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Facebook Integration Module
    provider: facebook
    says: lists Facebook Integration Module as an integration
    source: https://freescout.net/modules/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira Integration Module
    provider: jira
    says: lists Jira Integration Module as an integration
    source: https://freescout.net/modules/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack Integration Module
    provider: slack
    says: lists Slack Integration Module as an integration
    source: https://freescout.net/modules/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: SMS notifications via MessageBird
    provider: bird
    says: lists SMS notifications via MessageBird as an integration
    source: https://freescout.net/modules/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: SMS Tickets Module (Twilio)
    provider: twilio
    says: lists SMS Tickets Module (Twilio) as an integration
    source: https://freescout.net/modules/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Social Login Module (Azure)
    provider: microsoft-entra
    says: lists Social Login Module (Azure) as an integration
    source: https://freescout.net/modules/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Social Login Module (Google)
    provider: google-identity-platform
    says: lists Social Login Module (Google) as an integration
    source: https://freescout.net/modules/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Telegram Integration Module
    provider: telegram
    says: lists Telegram Integration Module as an integration
    source: https://freescout.net/modules/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Twitter Integration Module
    provider: x
    says: lists Twitter Integration Module as an integration
    source: https://freescout.net/modules/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: WhatsApp Integration Module
    provider: whatsapp
    says: lists WhatsApp Integration Module as an integration
    source: https://freescout.net/modules/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: WooCommerce Integration Module
    provider: woocommerce
    says: lists WooCommerce Integration Module as an integration
    source: https://freescout.net/modules/
    tier: declared
  kind: self-hosted
  name: FreeScout
  page: /applications/helpdesk-ticketing/freescout/
  slug: freescout
  url: https://github.com/freescout-help-desk/freescout
- anchor: zendesk
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.zendesk.android/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Firebase Analytics / Crashlytics
    provider: firebase
    says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zendesk.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.zendesk.android/latest/
    tier: observed
  kind: commercial
  name: Zendesk
  page: /applications/helpdesk-ticketing/zendesk/
  slug: zendesk
  url: https://www.zendesk.com/
- anchor: intercom
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/io.intercom.android/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/io.intercom.android/latest/
    tier: observed
  kind: commercial
  name: Intercom
  page: /applications/helpdesk-ticketing/intercom/
  slug: intercom
  url: https://www.intercom.com/
- anchor: freshdesk
  counts:
    declared: 4
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.freshdesk.helpdesk/latest/
  - route: integrations page
    url: https://www.freshworks.com/apps/freshdesk/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.freshdesk.helpdesk/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Firebase Analytics / Crashlytics
    provider: firebase
    says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.freshdesk.helpdesk/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: Atlassian Jira Plus
    provider: jira
    says: lists Atlassian Jira Plus as an integration
    source: https://www.freshworks.com/apps/freshdesk/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Calendar
    provider: google-calendar
    says: lists Google Calendar as an integration
    source: https://www.freshworks.com/apps/freshdesk/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://www.freshworks.com/apps/freshdesk/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://www.freshworks.com/apps/freshdesk/
    tier: declared
  kind: commercial
  name: Freshdesk
  page: /applications/helpdesk-ticketing/freshdesk/
  slug: freshdesk
  url: https://www.freshworks.com/freshdesk/
- anchor: help-scout
  counts:
    declared: 24
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.helpscout.com/apps/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-430.30
      key: contact-centre-operations-management
      name: Contact Centre Operations Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Aircall
    provider: aircall
    says: lists Aircall as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Gmail
    provider: google-gmail
    says: lists Gmail as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Instagram
    provider: instagram
    says: lists Instagram as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Klaviyo
    provider: klaviyo
    says: lists Klaviyo as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: Linear
    provider: linear-app
    says: lists Linear as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Messenger by Facebook
    provider: facebook
    says: lists Messenger by Facebook as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Mixpanel
    provider: mixpanel
    says: lists Mixpanel as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pipedrive
    provider: pipedrive
    says: lists Pipedrive as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: domain
    name: Segment.io
    provider: segment
    says: lists Segment.io as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Shopify
    provider: shopify
    says: lists Shopify as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: null
    layer: domain
    name: SurveyMonkey
    provider: surveymonkey
    says: lists SurveyMonkey as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.30
      key: contact-centre-operations-management
      name: Contact Centre Operations Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Talkdesk
    provider: talkdesk
    says: lists Talkdesk as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: domain
    name: Trello
    provider: trello
    says: lists Trello as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: WhatsApp
    provider: whatsapp
    says: lists WhatsApp as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: WooCommerce
    provider: woocommerce
    says: lists WooCommerce as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://www.helpscout.com/apps/
    tier: declared
  kind: commercial
  name: Help Scout
  page: /applications/helpdesk-ticketing/help-scout/
  slug: help-scout
  url: https://www.helpscout.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: helpdesk-ticketing
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Ticketing
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#ticketing
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Customer Service
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: IT Support & Service
  store: atlassian-marketplace
  url: https://marketplace.atlassian.com/
- category: Customer Service
  store: hubspot-marketplace
  url: https://ecosystem.hubspot.com/marketplace/apps
- category: Customer Support
  store: slack-marketplace
  url: https://slack.com/apps
- category: Customer Support
  store: zapier
  url: https://zapier.com/apps
- category: Customer support
  store: shopify-app-store
  url: https://apps.shopify.com/categories
name: Help Desk & Customer Support
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile deep links -- no BC capability
- capability:
    attribution: Turbo EA
    id: BC-4220.50.20
    key: BC-4220.50.20
    name: Auto-Scaling Policy Management
    url: /capabilities/capacity-performance-management-bc-4220-50/
    via_parent: Capacity & Performance Management
  fit: exact
  layer: common
  why: PaaS autoscaling -- no BC capability
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: common
  why: ticket translation -- no BC capability
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: Zapier-style connectors -- no BC capability
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  fit: exact
  layer: agent
  why: LLM / bot providers behind AI replies
- capability:
    attribution: Turbo EA
    id: BC-2330.10
    key: channel-orchestration-management
    name: Channel Orchestration Management
    url: /capabilities/channel-orchestration-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: messaging channels (WhatsApp, Telegram, Messenger, LINE, X, SMS, video) feeding the inbox
- capability:
    attribution: Turbo EA
    id: BC-430.30
    key: contact-centre-operations-management
    name: Contact Centre Operations Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: null
  fit: exact
  layer: domain
  why: telephony / CTI / voice channels
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: domain
  why: contact enrichment and customer data pipes
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  fit: exact
  layer: domain
  why: CSAT / surveys
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: CRM context beside the ticket
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: domain
  why: ticket import / migration from rival help desks
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: marketing / email-marketing context
- capability:
    attribution: Turbo EA
    id: BC-850.20
    key: external-communications-management
    name: External Communications Management
    url: /capabilities/external-communications-management/
    via_parent: null
  fit: nearest
  layer: common
  why: email / push transport
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: CAPTCHA on public forms
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: common
  why: IP geolocation of contacts
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: nearest
  layer: common
  why: agent notifications in Slack / Teams
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: knowledge-base ingestion (web crawl for AI answers), notes
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  fit: nearest
  layer: common
  why: attachment storage
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring and APM
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: billing and order context
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: product analytics
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  fit: exact
  layer: common
  why: calendar sync
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: escalate tickets to issue trackers (Jira, GitHub, GitLab, Linear)
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: social / enterprise sign-in
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Chatwoot
      - FreeScout
      - Help Scout
      - Zammad
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook (omniauth-facebook, koala)
      slug: facebook
      sources:
      - https://freescout.net/modules/
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      - https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - FreeScout
      - Help Scout
      - Zammad
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: WhatsApp (whatsapp_sdk)
      slug: whatsapp
      sources:
      - https://freescout.net/modules/
      - https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: observed
      url: /providers/whatsapp/
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - Chatwoot
      - FreeScout
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp: &id005
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: X / Twitter (twitty)
      slug: x
      sources:
      - https://freescout.net/modules/
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags: &id006
      - Conversations
      - Social
      - Spaces
      - X
      tier: observed
      url: /providers/x/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - FreeScout
      - Zammad
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        status: none
      name: Telegram (telegram-bot-ruby)
      slug: telegram
      sources:
      - https://freescout.net/modules/
      - https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
    - agent_band: agent-native
      agent_readiness: 47.0
      apps:
      - Chatwoot
      band: exemplar
      in_catalog: true
      kin_score: 71.3
      mcp:
        source: https://github.com/line/line-bot-mcp-server
        status: verified
      name: LINE (line-bot-api)
      slug: line
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags:
      - Chatbots
      - Messaging
      - Mini Apps
      - Social Login
      tier: observed
      url: /providers/line/
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
      - Help Scout
      band: exemplar
      in_catalog: true
      kin_score: 67.8
      mcp:
        status: none
      name: Instagram
      slug: instagram
      sources:
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - Instagram
      - Meta
      - Photos
      - Social Media
      tier: declared
      url: /providers/instagram/
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 64.4
      apps:
      - FreeScout
      - Freshdesk
      - Help Scout
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira Integration Module
      slug: jira
      sources:
      - https://freescout.net/modules/
      - https://www.freshworks.com/apps/freshdesk/
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: declared
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - Chatwoot
      - Help Scout
      band: developing
      in_catalog: true
      kin_score: 39.6
      mcp:
        source: https://linear.app/docs/mcp
        status: verified
      name: Linear
      slug: linear-app
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/config/integration/apps.yml
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - Issue Tracking
      - Productivity
      - Project Management
      - Software-as-a-Service
      tier: observed
      url: /providers/linear-app/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Help Scout
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: &id003
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://www.helpscout.com/apps/
      status: profiled
      tags: &id004
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: declared
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Help Scout
      band: exemplar
      in_catalog: true
      kin_score: 74.8
      mcp:
        source: https://github.com/atlassian/trello-mcp-server
        status: verified
      name: Trello
      slug: trello
      sources:
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - Collaboration
      - Kanban
      - Project Management
      - Task Management
      tier: declared
      url: /providers/trello/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - Help Scout
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: declared
      url: /providers/asana/
  - capability:
      attribution: Turbo EA
      id: BC-430.30
      key: contact-centre-operations-management
      name: Contact Centre Operations Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - Chatwoot
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp: &id001
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio (twilio-ruby, @twilio/voice-sdk)
      slug: twilio
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/package.json
      status: profiled
      tags: &id002
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-native
      agent_readiness: 53.8
      apps:
      - Help Scout
      band: strong
      in_catalog: true
      kin_score: 64.1
      mcp:
        status: none
      name: Talkdesk
      slug: talkdesk
      sources:
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - CCaaS
      - Contact Center
      - Voice
      - Webhook
      tier: declared
      url: /providers/talkdesk/
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - Help Scout
      band: thin
      in_catalog: true
      kin_score: 30.0
      mcp:
        status: none
      name: Aircall
      slug: aircall
      sources:
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - CRM
      - Cloud Phone
      - Communications
      - Voice
      tier: declared
      url: /providers/aircall/
    - agent_band: agent-aware
      agent_readiness: 6.3
      apps:
      - Zammad
      band: thin
      in_catalog: true
      kin_score: 27.1
      mcp:
        source: https://github.com/sipgate/sipgate-ai-demo-auth-mcp-server
        status: documented
      name: sipgate.io CTI
      slug: sipgate
      sources:
      - https://admin-docs.zammad.org/en/latest/system/integrations.html
      status: profiled
      tags:
      - Cloud
      - Communications
      - Company
      - Telephony
      tier: declared
      url: /providers/sipgate/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Zammad
      band: emerging
      in_catalog: true
      kin_score: 15.5
      mcp:
        status: none
      name: Placetel CTI
      slug: placetel
      sources:
      - https://admin-docs.zammad.org/en/latest/system/integrations.html
      status: profiled
      tags:
      - Call Center
      - Collaboration
      - Messaging
      - Video Meetings
      tier: declared
      url: /providers/placetel/
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Help Scout
      - Zendesk
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.zendesk.android/latest/
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - Zammad
      band: strong
      in_catalog: true
      kin_score: 64.9
      mcp:
        status: none
      name: Microsoft Exchange (viewpoint EWS, importer)
      slug: microsoft-exchange
      sources:
      - https://api.github.com/repos/zammad/zammad/contents/lib/import?ref=develop
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Contacts
      - Email
      tier: observed
      url: /providers/microsoft-exchange/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Zammad
      band: strong
      in_catalog: true
      kin_score: 59.3
      mcp:
        status: none
      name: Clearbit
      slug: clearbit
      sources:
      - https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
      status: profiled
      tags:
      - B2B
      - Data Enrichment
      - Reveal
      - Sales Intelligence
      tier: observed
      url: /providers/clearbit/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - Chatwoot
      band: strong
      in_catalog: true
      kin_score: 56.0
      mcp:
        status: none
      name: LeadSquared
      slug: leadsquared
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/config/integration/apps.yml
      status: profiled
      tags:
      - CRM
      - Lead Management
      - Marketing Automation
      - Sales Automation
      tier: observed
      url: /providers/leadsquared/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Help Scout
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Help Scout
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Help Scout
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: Pipedrive
      slug: pipedrive
      sources:
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - CRM
      - Pipeline Management
      - Sales
      - Software-as-a-Service
      tier: declared
      url: /providers/pipedrive/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - FreeScout
      - Zammad
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp: *id001
      name: Twilio (twilio-ruby, SMS driver)
      slug: twilio
      sources:
      - https://api.github.com/repos/zammad/zammad/contents/app/models/channel/driver/sms?ref=develop
      - https://freescout.net/modules/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-native
      agent_readiness: 70.3
      apps:
      - Zammad
      band: developing
      in_catalog: true
      kin_score: 50.0
      mcp: &id009
        source: https://github.com/messagebird/bird-ai
        status: verified
      name: MessageBird / Bird (messagebird-rest)
      slug: bird
      sources:
      - https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
      status: profiled
      tags: &id010
      - Communications
      - Email
      - SMS
      - WhatsApp
      tier: observed
      url: /providers/bird/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Zammad
      band: emerging
      in_catalog: true
      kin_score: 15.3
      mcp:
        status: unknown
      name: Massenversand (SMS driver)
      slug: massenversand
      sources:
      - https://api.github.com/repos/zammad/zammad/contents/app/models/channel/driver/sms?ref=develop
      status: profiled
      tags:
      - Germany
      - Marketing
      - Messaging
      - SMS
      tier: observed
      url: /providers/massenversand/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Zammad
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk (zendesk_api importer)
      slug: zendesk
      sources:
      - https://api.github.com/repos/zammad/zammad/contents/lib/import?ref=develop
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: observed
      url: /providers/zendesk/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Zammad
      band: thin
      in_catalog: true
      kin_score: 29.7
      mcp:
        status: none
      name: Freshdesk (importer)
      slug: freshdesk
      sources:
      - https://api.github.com/repos/zammad/zammad/contents/lib/import?ref=develop
      status: profiled
      tags:
      - Application
      - Automation
      - Customer Service
      - Help Desk
      tier: observed
      url: /providers/freshdesk/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Zammad
      band: emerging
      in_catalog: true
      kin_score: 23.4
      mcp:
        status: none
      name: Kayako (importer)
      slug: kayako
      sources:
      - https://api.github.com/repos/zammad/zammad/contents/lib/import?ref=develop
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Customer Service
      - Software-as-a-Service
      tier: observed
      url: /providers/kayako/
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Help Scout
      band: thin
      in_catalog: true
      kin_score: 34.9
      mcp:
        source: https://www.surveymonkey.com/apps/
        status: documented
      name: SurveyMonkey
      slug: surveymonkey
      sources:
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - Feedback
      - Market Research
      - NPS
      - Surveys
      tier: declared
      url: /providers/surveymonkey/
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Chatwoot
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://developers.notion.com/docs/mcp
        status: verified
      name: Notion
      slug: notion
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/config/integration/apps.yml
      status: profiled
      tags:
      - Collaboration
      - Database
      - Ideas
      - Notes
      tier: observed
      url: /providers/notion/
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Zammad
      band: exemplar
      in_catalog: true
      kin_score: 78.4
      mcp: &id007
        source: https://www.elastic.co/docs/solutions/search/mcp
        status: verified
      name: Elasticsearch (SaaS)
      slug: elastic
      sources:
      - https://admin-docs.zammad.org/en/latest/system/integrations.html
      status: profiled
      tags: &id008
      - Analytics
      - Observability
      - Search
      - Security
      tier: declared
      url: /providers/elastic/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Chatwoot
      band: thin
      in_catalog: true
      kin_score: 27.4
      mcp:
        status: none
      name: Dyte
      slug: dyte
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/config/integration/apps.yml
      status: profiled
      tags:
      - Real-Time
      - Video
      - Voice
      - WebRTC
      tier: observed
      url: /providers/dyte/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.10
      key: AE-230.40.10
      name: Web Scraping
      url: /capabilities/web-data/
      via_parent: Web Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - Chatwoot
      band: developing
      in_catalog: true
      kin_score: 50.6
      mcp:
        source: https://docs.firecrawl.dev/mcp-server
        status: verified
      name: Firecrawl (firecrawl-sdk)
      slug: firecrawl
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags:
      - Crawling
      - Data Extraction
      - URLs
      - Web Scraping
      tier: observed
      url: /providers/firecrawl/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Chatwoot
      - FreeScout
      - Zammad
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in (omniauth-google-oauth2)
      slug: google-identity-platform
      sources:
      - https://freescout.net/modules/
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      - https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - FreeScout
      - Zammad
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Microsoft (omniauth-microsoft-office365)
      slug: microsoft-entra
      sources:
      - https://freescout.net/modules/
      - https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Zammad
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab (omniauth-gitlab)
      slug: gitlab
      sources:
      - https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Zammad
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: *id003
      name: GitHub (omniauth-github)
      slug: github
      sources:
      - https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Zammad
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp:
        status: none
      name: LinkedIn (omniauth-linkedin-oauth2)
      slug: linkedin
      sources:
      - https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: observed
      url: /providers/linkedin/
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - Zammad
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp: *id005
      name: X / Twitter (omniauth-twitter)
      slug: x
      sources:
      - https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/x/
    - agent_band: human-only
      agent_readiness: 1.1
      apps:
      - Zammad
      band: minimal
      in_catalog: true
      kin_score: 8.0
      mcp:
        status: none
      name: Weibo (omniauth-weibo-oauth2)
      slug: weibo
      sources:
      - https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
      status: profiled
      tags:
      - China
      - Company
      - Microblogging
      - Social Media
      tier: observed
      url: /providers/weibo/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Chatwoot
      - Intercom
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry (sentry-ruby, @sentry/vue)
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      - https://reports.exodus-privacy.eu.org/en/reports/io.intercom.android/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 48.6
      apps:
      - Chatwoot
      band: exemplar
      in_catalog: true
      kin_score: 80.0
      mcp:
        source: https://github.com/datadog-labs/mcp-server
        status: verified
      name: Datadog
      slug: datadog
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags:
      - Analytics
      - Dashboards
      - Datadog
      - Visualization
      tier: observed
      url: /providers/datadog/
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Chatwoot
      band: exemplar
      in_catalog: true
      kin_score: 78.4
      mcp: *id007
      name: Elastic APM (elastic-apm)
      slug: elastic
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/elastic/
    - agent_band: agent-native
      agent_readiness: 43.4
      apps:
      - Chatwoot
      band: exemplar
      in_catalog: true
      kin_score: 77.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon CloudWatch (speedshop-cloudwatch)
      slug: amazon-cloudwatch
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - CloudWatch
      - Monitoring
      - Observability
      tier: observed
      url: /providers/amazon-cloudwatch/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Chatwoot
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic (newrelic_rpm)
      slug: new-relic
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
    - agent_band: agent-aware
      agent_readiness: 21.7
      apps:
      - Chatwoot
      band: developing
      in_catalog: true
      kin_score: 41.8
      mcp:
        source: https://github.com/scoutapp/scout-mcp-local
        status: verified
      name: Scout APM (scout_apm)
      slug: scout-apm
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags:
      - AI-assisted
      - APM
      - Company
      - Monitoring
      tier: observed
      url: /providers/scout-apm/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Chatwoot
      - FreeScout
      - Freshdesk
      - Help Scout
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack (slack-ruby-client)
      slug: slack
      sources:
      - https://freescout.net/modules/
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      - https://www.freshworks.com/apps/freshdesk/
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Freshdesk
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://www.freshworks.com/apps/freshdesk/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: declared
      url: /providers/microsoft-teams/
    - agent_band: agent-native
      agent_readiness: 70.3
      apps:
      - FreeScout
      band: developing
      in_catalog: true
      kin_score: 50.0
      mcp: *id009
      name: SMS notifications via MessageBird
      slug: bird
      sources:
      - https://freescout.net/modules/
      status: profiled
      tags: *id010
      tier: declared
      url: /providers/bird/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.8
      apps:
      - Chatwoot
      - Help Scout
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify (shopify_api)
      slug: shopify
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: observed
      url: /providers/shopify/
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Chatwoot
      - Help Scout
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - FreeScout
      - Help Scout
      band: strong
      in_catalog: true
      kin_score: 54.6
      mcp:
        source: https://developer.woocommerce.com/docs/features/mcp/
        status: verified
      name: WooCommerce Integration Module
      slug: woocommerce
      sources:
      - https://freescout.net/modules/
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - E-Commerce
      - Open Source
      - Order
      - WooCommerce
      tier: declared
      url: /providers/woocommerce/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Freshdesk
      - Zendesk
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id011
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics / Crashlytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.freshdesk.helpdesk/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.zendesk.android/latest/
      status: profiled
      tags: &id012
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - Chatwoot
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude (@amplitude/analytics-browser)
      slug: amplitude
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/package.json
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - Help Scout
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: declared
      url: /providers/mixpanel/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Chatwoot
      - Zammad
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3 (aws-sdk-s3)
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      - https://raw.githubusercontent.com/zammad/zammad/develop/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Chatwoot
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Chatwoot
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob (azure-blob)
      slug: microsoft-azure-blob-storage
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - Chatwoot
      - Help Scout
      band: exemplar
      in_catalog: true
      kin_score: 66.8
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail (gmail_xoauth)
      slug: google-gmail
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: observed
      url: /providers/google-gmail/
    - agent_band: agent-ready
      agent_readiness: 39.0
      apps:
      - Zammad
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft 365 Graph email channel
      slug: microsoft-graph
      sources:
      - https://api.github.com/repos/zammad/zammad/contents/app/models/channel/driver?ref=develop
      status: profiled
      tags:
      - Azure AD
      - Collaboration
      - Contacts
      - Microsoft Graph
      tier: observed
      url: /providers/microsoft-graph/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - Chatwoot
      band: thin
      in_catalog: true
      kin_score: 31.1
      mcp:
        status: none
      name: hCaptcha (@hcaptcha/vue3-hcaptcha)
      slug: hcaptcha
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/package.json
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Privacy
      - hCaptcha
      tier: observed
      url: /providers/hcaptcha/
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - FreeScout
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Extra Security Module (reCAPTCHA)
      slug: google-recaptcha
      sources:
      - https://freescout.net/modules/
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: declared
      url: /providers/google-recaptcha/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.7
      apps:
      - Help Scout
      band: exemplar
      in_catalog: true
      kin_score: 78.1
      mcp:
        source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
        status: verified
      name: Klaviyo
      slug: klaviyo
      sources:
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - Customer Data
      - Email
      - Marketing
      - SMS
      tier: declared
      url: /providers/klaviyo/
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Help Scout
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Chatwoot
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id011
      name: Firebase Cloud Messaging (fcm)
      slug: google-firebase
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags: *id012
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Chatwoot
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Apple Push Notification service (apnotic)
      slug: apple
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
  - capability:
      attribution: Turbo EA
      id: BC-4220.50.20
      key: BC-4220.50.20
      name: Auto-Scaling Policy Management
      url: /capabilities/capacity-performance-management-bc-4220-50/
      via_parent: Capacity & Performance Management
    providers:
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Chatwoot
      band: emerging
      in_catalog: true
      kin_score: 25.1
      mcp:
        status: unknown
      name: Judoscale (production group)
      slug: judoscale
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags:
      - Auto-Scaling
      - Cloud
      - Company
      - DevOps
      tier: observed
      url: /providers/judoscale/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - Chatwoot
      band: thin
      in_catalog: true
      kin_score: 31.5
      mcp:
        status: none
      name: MaxMind (maxminddb)
      slug: maxmind
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags:
      - Fraud Prevention
      - Geolocation
      - IP Intelligence
      - Risk Scoring
      tier: observed
      url: /providers/maxmind/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.9
      apps:
      - Chatwoot
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: Google Cloud Translation
      slug: google-translate
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags:
      - Google Cloud
      - Internationalization
      - Language Detection
      - Localization
      tier: observed
      url: /providers/google-translate/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Freshdesk
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.freshdesk.helpdesk/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Freshdesk
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://www.freshworks.com/apps/freshdesk/
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: declared
      url: /providers/google-calendar/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - Chatwoot
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        status: none
      name: Amazon SES (aws-sdk-sesv2, aws-actionmailbox-ses)
      slug: amazon-ses
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Help Scout
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://www.helpscout.com/apps/
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
  layer: common
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Chatwoot
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI (ruby-openai)
      slug: openai
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 35.4
      apps:
      - Chatwoot
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        status: none
      name: Dialogflow
      slug: google-dialogflow
      sources:
      - https://raw.githubusercontent.com/chatwoot/chatwoot/develop/Gemfile
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Chatbots
      - Conversational AI
      tier: observed
      url: /providers/google-dialogflow/
  layer: agent
summary:
  coverage_pct: 100.0
  declared_only: 21
  distinct_providers: 70
  in_catalog: 70
  mcp:
    documented: 2
    none: 30
    unchecked: 0
    verified: 36
  mcp_verified: 36
  mean_kin_score: 61.0
  observed: 49
  queued: 0
  reference_apps: 7
title: 'Help Desk & Customer Support: application blueprint'
---
