---
access: understanding
agent_layer:
- app: Calendly
  finding: Calendly lists ChatGPT, Claude, Gemini and Grok integrations (Calendly exposed inside AI assistants), plus MindStudio, Questflow and Autohive agent builders
  source: https://calendly.com/marketing-site/sitemap.xml
  tier: declared
- app: Cal.com
  finding: app-store ships AI voice-agent booking apps (Retell AI, Synthflow, ElevenLabs, Bolna, Lindy, Chatbase) and an AI notetaker (Granola); agents book meetings through Cal.com
  source: https://github.com/calcom/cal.com/tree/main/packages/app-store
  tier: observed
- app: Rallly
  finding: BYO OpenAI key (@ai-sdk/openai) for in-app AI features
  source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/package.json
  tier: observed
apps:
- anchor: calcom
  counts:
    declared: 0
    observed: 71
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/calcom/cal.com/main/apps/web/package.json
  - route: dependency manifest
    url: https://raw.githubusercontent.com/calcom/cal.com/main/package.json
  - route: dependency manifest
    url: https://raw.githubusercontent.com/calcom/cal.com/main/packages/features/package.json
  - route: dependency manifest
    url: https://raw.githubusercontent.com/calcom/cal.com/main/packages/lib/package.json
  - route: source code
    url: https://github.com/calcom/cal.com/tree/main/packages/app-store
  - route: source code
    url: https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: 8x8 Meet
    provider: 8x8
    says: ships the 8x8 Meet SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Apple Calendar
    provider: apple
    says: ships the Apple Calendar SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Attio
    provider: attio
    says: ships the Attio SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Basecamp
    provider: basecamp
    says: ships the Basecamp SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.20
      key: AE-100.70.20
      name: Voice Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    credit: null
    layer: agent
    name: Bolna
    provider: bolna
    says: ships the Bolna SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-240.70.20
      key: AE-240.70.20
      name: Crypto Payment Acceptance
      url: /capabilities/stablecoin-payments/
      via_parent: Stablecoin Payments
    credit: null
    layer: common
    name: BTCPay Server
    provider: btcpay
    says: ships the BTCPay Server SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.20
      key: AE-100.70.20
      name: Voice Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    credit: null
    layer: agent
    name: Chatbase
    provider: chatbase
    says: ships the Chatbase SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Checkly
    provider: checkly
    says: ships the Checkly SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/package.json
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
    name: Close
    provider: close
    says: ships the Close SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Cloudflare
    provider: cloudflare
    says: ships the Cloudflare SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
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
    name: Cloudflare Turnstile
    provider: cloudflare-turnstile
    says: ships the Cloudflare Turnstile SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
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
    name: Daily (Cal Video)
    provider: daily-co
    says: ships the Daily (Cal Video) SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/apps/web/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.40
      key: AE-110.30.40
      name: Meeting Notes & Conversation Intelligence
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Demodesk
    provider: demodesk
    says: ships the Demodesk SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: domain
    name: Dialpad
    provider: dialpad
    says: ships the Dialpad SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Dub
    provider: dub
    says: ships the Dub SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.20
      key: AE-100.70.20
      name: Voice Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    credit: null
    layer: agent
    name: ElevenLabs
    provider: elevenlabs
    says: ships the ElevenLabs SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Exchange Calendar
    provider: microsoft-exchange
    says: ships the Exchange Calendar SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Fathom Analytics
    provider: fathom
    says: ships the Fathom Analytics SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: domain
    name: Formbricks
    provider: formbricks
    says: ships the Formbricks SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/packages/lib/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Framer
    provider: framer
    says: ships the Framer SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Freshchat
    provider: freshchat
    says: ships the Freshchat SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
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
    name: Google Analytics 4
    provider: google-analytics
    says: ships the Google Analytics 4 SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Google Calendar
    provider: google-calendar
    says: ships the Google Calendar SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Google Meet
    provider: google-meet
    says: ships the Google Meet SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: null
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: ships the Google Tag Manager SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.40
      key: AE-110.30.40
      name: Meeting Notes & Conversation Intelligence
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: agent
    name: Granola
    provider: granola
    says: ships the Granola SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Help Scout
    provider: helpscout
    says: ships the Help Scout SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
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
    name: HitPay
    provider: hitpay
    says: ships the HitPay SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: HubSpot
    provider: hubspot
    says: ships the HubSpot SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Intercom
    provider: intercom
    says: ships the Intercom SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.20
      key: AE-100.70.20
      name: Voice Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    credit: null
    layer: agent
    name: Lindy
    provider: lindy
    says: ships the Lindy SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Linear
    provider: linear-app
    says: ships the Linear SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Make
    provider: make
    says: ships the Make SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Matomo
    provider: matomo
    says: ships the Matomo SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Meta Pixel
    provider: facebook
    says: ships the Meta Pixel SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Microsoft Teams
    provider: microsoft-teams
    says: ships the Microsoft Teams SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: n8n
    provider: n8n
    says: ships the n8n SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Outlook / Office 365 Calendar
    provider: microsoft-outlook
    says: ships the Outlook / Office 365 Calendar SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Pipedream
    provider: pipedream
    says: ships the Pipedream SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Pipedrive
    provider: pipedrive
    says: ships the Pipedrive SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Plausible
    provider: plausible
    says: ships the Plausible SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: PostHog
    provider: posthog
    says: ships the PostHog SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/apps/web/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Raycast
    provider: raycast
    says: ships the Raycast SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Resend
    provider: resend
    says: ships the Resend SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.20
      key: AE-100.70.20
      name: Voice Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    credit: null
    layer: agent
    name: Retell AI
    provider: retell-ai
    says: ships the Retell AI SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Riverside
    provider: riverside
    says: ships the Riverside SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Salesforce
    provider: salesforce
    says: ships the Salesforce SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: SendGrid
    provider: sendgrid
    says: ships the SendGrid SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/packages/lib/package.json
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
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/apps/web/package.json
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
    name: Signal
    provider: signal
    says: ships the Signal SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.20
      key: AE-100.70.20
      name: Voice Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    credit: null
    layer: agent
    name: Synthflow
    provider: synthflow
    says: ships the Synthflow SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.40.20
      key: BC-600.40.20
      name: IT Job Scheduling and Batch Operations
      url: /capabilities/it-operations-management/
      via_parent: IT Operations Management
    credit: null
    layer: common
    name: Trigger.dev
    provider: trigger-dev
    says: ships the Trigger.dev SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/packages/features/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
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
    name: Umami
    provider: umami
    says: ships the Umami SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220
      key: saas-platform-operations-management
      name: SaaS Platform Operations Management
      url: /capabilities/saas-platform-operations-management/
      via_parent: null
    credit: null
    layer: common
    name: Unkey
    provider: unkey
    says: ships the Unkey SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/packages/lib/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Upstash
    provider: upstash
    says: ships the Upstash SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/apps/web/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Vercel
    provider: vercel
    says: ships the Vercel SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/apps/web/package.json
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
    name: Webex
    provider: webex
    says: ships the Webex SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: WhatsApp
    provider: whatsapp
    says: ships the WhatsApp SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Whereby
    provider: whereby
    says: ships the Whereby SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: WordPress
    provider: wordpress
    says: ships the WordPress SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
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
    says: ships the Zapier SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Zendesk
    provider: zendesk
    says: ships the Zendesk SDK or integration code
    source: https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Zoho Calendar
    provider: zoho
    says: ships the Zoho Calendar SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Zoho CRM
    provider: zoho-crm
    says: ships the Zoho CRM SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
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
    name: Zoom
    provider: zoom
    says: ships the Zoom SDK or integration code
    source: https://github.com/calcom/cal.com/tree/main/packages/app-store
    tier: observed
  kind: self-hosted
  name: Cal.com
  page: /applications/booking-scheduling/cal-com/
  slug: cal-com
  url: https://github.com/calcom/cal.com
- anchor: easy!appointments
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/alextselegidis/easyappointments/main/composer.json
  - route: documentation
    url: https://github.com/alextselegidis/easyappointments/tree/main/docs
  - route: source code
    url: https://github.com/alextselegidis/easyappointments/tree/main/application/libraries
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Google Calendar
    provider: google-calendar
    says: ships the Google Calendar SDK or integration code
    source: https://github.com/alextselegidis/easyappointments/tree/main/application/libraries
    tier: observed
  kind: self-hosted
  name: Easy!Appointments
  page: /applications/booking-scheduling/easy-appointments/
  slug: easy-appointments
  url: https://github.com/alextselegidis/easyappointments
- anchor: librebooking
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/LibreBooking/librebooking/develop/composer.json
  - route: source code
    url: https://github.com/LibreBooking/librebooking/tree/develop/plugins
  - route: source code
    url: https://raw.githubusercontent.com/LibreBooking/librebooking/develop/Domain/PaymentGateway.php
  - route: source code
    url: https://raw.githubusercontent.com/LibreBooking/librebooking/develop/config/config.dist.php
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Facebook Login
    provider: facebook
    says: ships the Facebook Login SDK or integration code
    source: https://raw.githubusercontent.com/LibreBooking/librebooking/develop/config/config.dist.php
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
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://raw.githubusercontent.com/LibreBooking/librebooking/develop/config/config.dist.php
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
    name: Google reCAPTCHA
    provider: google-recaptcha
    says: ships the Google reCAPTCHA SDK or integration code
    source: https://raw.githubusercontent.com/LibreBooking/librebooking/develop/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://raw.githubusercontent.com/LibreBooking/librebooking/develop/config/config.dist.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Microsoft sign-in
    provider: microsoft-entra
    says: ships the Microsoft sign-in SDK or integration code
    source: https://raw.githubusercontent.com/LibreBooking/librebooking/develop/config/config.dist.php
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
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://raw.githubusercontent.com/LibreBooking/librebooking/develop/Domain/PaymentGateway.php
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
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://raw.githubusercontent.com/LibreBooking/librebooking/develop/config/config.dist.php
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
    source: https://raw.githubusercontent.com/LibreBooking/librebooking/develop/composer.json
    tier: observed
  kind: self-hosted
  name: LibreBooking
  page: /applications/booking-scheduling/librebooking/
  slug: librebooking
  url: https://github.com/LibreBooking/librebooking
- anchor: rallly
  counts:
    declared: 0
    observed: 13
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/package.json
  - route: dependency manifest
    url: https://raw.githubusercontent.com/lukevella/rallly/main/packages/billing/package.json
  - route: source code
    url: https://github.com/lukevella/rallly/tree/main/apps/web/src/features/calendars/google
  - route: source code
    url: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Amazon SES
    provider: amazon-ses
    says: ships the Amazon SES SDK or integration code
    source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
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
    name: Cloudflare Turnstile
    provider: cloudflare-turnstile
    says: ships the Cloudflare Turnstile SDK or integration code
    source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Google Calendar
    provider: google-calendar
    says: ships the Google Calendar SDK or integration code
    source: https://github.com/lukevella/rallly/tree/main/apps/web/src/features/calendars/google
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Microsoft sign-in
    provider: microsoft-entra
    says: ships the Microsoft sign-in SDK or integration code
    source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/package.json
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
    name: PostHog
    provider: posthog
    says: ships the PostHog SDK or integration code
    source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
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
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/package.json
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
    source: https://raw.githubusercontent.com/lukevella/rallly/main/packages/billing/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Upstash
    provider: upstash
    says: ships the Upstash SDK or integration code
    source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-925
      key: AE-925
      name: Serverless Functions
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Vercel
    provider: vercel
    says: ships the Vercel SDK or integration code
    source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/package.json
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
    name: Webex
    provider: webex
    says: ships the Webex SDK or integration code
    source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
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
    name: Zoom
    provider: zoom
    says: ships the Zoom SDK or integration code
    source: https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
    tier: observed
  kind: self-hosted
  name: Rallly
  page: /applications/booking-scheduling/rallly/
  slug: rallly
  url: https://github.com/lukevella/rallly
- anchor: calendly
  counts:
    declared: 51
    observed: 3
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
    layer: domain
    name: ZoomInfo
    provider: zoominfo
    says: lists ZoomInfo as an integration
    source: https://calendly.com/integration/zoominfo
    tier: declared
  kind: commercial
  name: Calendly
  page: /applications/booking-scheduling/calendly/
  slug: calendly
  url: https://calendly.com/
- anchor: acuity-scheduling
  counts:
    declared: 32
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
  - route: integrations page
    url: https://acuityscheduling.com/integrations
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
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Bugsnag
    provider: bugsnag
    says: ships the Bugsnag SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google AdMob
    provider: google-admob
    says: ships the Google AdMob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
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
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Instabug
    provider: instabug
    says: ships the Instabug SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Tune
    provider: tune
    says: ships the Tune SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: ActiveCampaign
    provider: activecampaign
    says: lists ActiveCampaign as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: AWeber
    provider: aweber
    says: lists AWeber as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClassPass
    provider: classpass
    says: lists ClassPass as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: Constant Contact
    provider: constant-contact
    says: lists Constant Contact as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: ConvertKit
    provider: convertkit
    says: lists ConvertKit as an integration
    source: https://acuityscheduling.com/integrations
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
    name: Daylite
    provider: daylite
    says: lists Daylite as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: Drip
    provider: drip
    says: lists Drip as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Facebook Business + Instagram
    provider: facebook
    says: lists Facebook Business + Instagram as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.50
      key: invoice-generation-management
      name: Invoice Generation Management
      url: /capabilities/invoice-generation-management/
      via_parent: null
    credit: null
    layer: domain
    name: FreshBooks
    provider: freshbooks
    says: lists FreshBooks as an integration
    source: https://acuityscheduling.com/integrations
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
    name: Google Analytics
    provider: google-analytics
    says: lists Google Analytics as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Google Calendar
    provider: google-calendar
    says: lists Google Calendar as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Google Contacts
    provider: google-people
    says: lists Google Contacts as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: Google Hangouts Meet
    provider: google-meet
    says: lists Google Hangouts Meet as an integration
    source: https://acuityscheduling.com/integrations
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
    name: Google Sheets
    provider: google-sheets
    says: lists Google Sheets as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: GoToMeeting / join.me
    provider: goto
    says: lists GoToMeeting / join.me as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: iCloud
    provider: apple
    says: lists iCloud as an integration
    source: https://acuityscheduling.com/integrations
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
    name: Infusionsoft (Keap)
    provider: keap
    says: lists Infusionsoft (Keap) as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Outlook
    provider: microsoft-outlook
    says: lists Microsoft Outlook as an integration
    source: https://acuityscheduling.com/integrations
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
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.50
      key: invoice-generation-management
      name: Invoice Generation Management
      url: /capabilities/invoice-generation-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks
    provider: quickbooks
    says: lists QuickBooks as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: ReferralCandy
    provider: referralcandy
    says: lists ReferralCandy as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Reserve with Google
    provider: google
    says: lists Reserve with Google as an integration
    source: https://acuityscheduling.com/integrations
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
    source: https://acuityscheduling.com/integrations
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
    name: Square
    provider: square
    says: lists Square as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Squarespace
    provider: squarespace
    says: lists Squarespace as an integration
    source: https://acuityscheduling.com/integrations
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
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: domain
    name: Wufoo
    provider: wufoo
    says: lists Wufoo as an integration
    source: https://acuityscheduling.com/integrations
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
    source: https://acuityscheduling.com/integrations
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
    name: Zoho CRM
    provider: zoho-crm
    says: lists Zoho CRM as an integration
    source: https://acuityscheduling.com/integrations
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
    name: Zoho Flow
    provider: zoho
    says: lists Zoho Flow as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://acuityscheduling.com/integrations
    tier: declared
  kind: commercial
  name: Acuity Scheduling
  page: /applications/booking-scheduling/acuity-scheduling/
  slug: acuity-scheduling
  url: https://acuityscheduling.com/
- anchor: booksy-biz
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/net.booksy.business/latest/
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
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/net.booksy.business/latest/
    tier: observed
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
    source: https://reports.exodus-privacy.eu.org/en/reports/net.booksy.business/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Facebook Analytics / Login / Share
    provider: facebook
    says: ships the Facebook Analytics / Login / Share SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/net.booksy.business/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google CrashLytics
    provider: firebase
    says: ships the Google CrashLytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/net.booksy.business/latest/
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
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/net.booksy.business/latest/
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
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/net.booksy.business/latest/
    tier: observed
  kind: commercial
  name: Booksy Biz
  page: /applications/booking-scheduling/booksy-biz/
  slug: booksy-biz
  url: https://booksy.com/biz/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: booking-scheduling
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Productivity
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Booking and Scheduling
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#booking-and-scheduling
- category: Store management
  store: shopify-app-store
  url: https://apps.shopify.com/categories
- category: Sales
  store: hubspot-marketplace
  url: https://ecosystem.hubspot.com/marketplace/apps
- category: Scheduling & Booking
  store: zapier
  url: https://zapier.com/apps
name: Appointment Booking & Scheduling
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: two-way calendar sync and conflict checking is the core of every booking app
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: domain
  why: bookings carry a generated video-meeting location
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.10
    key: AE-150.50.10
    name: Programmable Voice
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  fit: exact
  layer: domain
  why: phone/VoIP meeting locations and call tracking
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: nearest
  layer: domain
  why: messaging-app meeting locations and reminders
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: booked meetings are written to the CRM as activities/leads
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: paid bookings, deposits and the app's own subscription billing
- capability:
    attribution: API Evangelist extension
    id: AE-240.70.20
    key: AE-240.70.20
    name: Crypto Payment Acceptance
    url: /capabilities/stablecoin-payments/
    via_parent: Stablecoin Payments
  fit: exact
  layer: common
  why: crypto/lightning payment for paid bookings
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: booking events pushed to automation platforms
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: confirmation and reminder email
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: SMS reminders and verification
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error and crash monitoring, synthetic checks
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: product and booking-page analytics
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: tag manager on booking pages
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: ad pixels / conversion tracking on booking pages
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: in-app support chat / helpdesk widget
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  fit: exact
  layer: domain
  why: intake forms route into scheduling / post-meeting surveys
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: bot protection on public booking pages
- capability:
    attribution: Turbo EA
    id: BC-4220
    key: saas-platform-operations-management
    name: SaaS Platform Operations Management
    url: /capabilities/saas-platform-operations-management/
    via_parent: null
  fit: nearest
  layer: common
  why: hosting, edge, rate-limit and custom-domain infrastructure
- capability:
    attribution: Turbo EA
    id: BC-600.40.20
    key: BC-600.40.20
    name: IT Job Scheduling and Batch Operations
    url: /capabilities/it-operations-management/
    via_parent: IT Operations Management
  fit: exact
  layer: common
  why: background job orchestration for reminders/workflows
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: social / workforce sign-in for hosts
- capability:
    attribution: API Evangelist extension
    id: AE-100.70.20
    key: AE-100.70.20
    name: Voice Agents
    url: /capabilities/vertical-agents/
    via_parent: Vertical Agents
  fit: exact
  layer: agent
  why: AI voice agents that book or confirm appointments
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.40
    key: AE-110.30.40
    name: Meeting Notes & Conversation Intelligence
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  fit: exact
  layer: agent
  why: 'AI meeting notetakers attached to booked meetings (no node: candidate "Meeting Notes & Conversation Intelligence")'
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: nearest
  layer: common
  why: team chat notifications for new bookings
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.40
    key: AE-110.30.40
    name: Meeting Notes & Conversation Intelligence
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  fit: exact
  layer: domain
  why: revenue-intelligence tools record booked sales calls
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  fit: exact
  layer: domain
  why: website builder embeds the scheduler
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: common
  why: LLM features (BYO key)
- capability:
    attribution: Turbo EA
    id: BC-400.50
    key: marketing-operations-management
    name: Marketing Operations Management
    url: /capabilities/marketing-operations-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: marketing-automation platforms receive booked-meeting events
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.10
    key: AE-230.30.10
    name: Data Enrichment
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  fit: exact
  layer: domain
  why: invitee enrichment / routing on firmographics
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: domain
  why: new bookers added to email-marketing lists
- capability:
    attribution: API Evangelist extension
    id: AE-220.10
    key: AE-220.10
    name: Online Courses
    url: /capabilities/online-courses/
    via_parent: null
  fit: exact
  layer: domain
  why: course/membership platforms sell coaching sessions
- capability:
    attribution: Turbo EA
    id: BC-300.10
    key: talent-acquisition-management
    name: Talent Acquisition Management
    url: /capabilities/talent-acquisition-management/
    via_parent: null
  fit: exact
  layer: domain
  why: interview scheduling from the ATS
- capability:
    attribution: API Evangelist extension
    id: AE-140.50.20
    key: AE-140.50.20
    name: Corporate & Digital Gifting
    url: /capabilities/gift-cards-gifting-cashback/
    via_parent: Gift Cards, Gifting & Cashback
  fit: exact
  layer: domain
  why: send a gift when a meeting is booked
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  fit: exact
  layer: domain
  why: review platforms drive bookings and post-appointment reviews
- capability:
    attribution: Turbo EA
    id: BC-4330.50
    key: invoice-generation-management
    name: Invoice Generation Management
    url: /capabilities/invoice-generation-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: paid appointments create invoices in accounting
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  fit: exact
  layer: domain
  why: third-party booking channels that feed appointments into the app
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: in-app ad SDK
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile install attribution and deep linking
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Acuity Scheduling
      - Cal.com
      - Calendly
      - Rallly
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://acuityscheduling.com/integrations
      - https://calendly.com/integration/zoom
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: observed
      url: /providers/zoom/
    - agent_band: agent-ready
      agent_readiness: 61.8
      apps:
      - Cal.com
      - Calendly
      - Rallly
      band: strong
      in_catalog: true
      kin_score: 66.1
      mcp:
        source: https://github.com/WebexSamples/webex-messaging-mcp-server
        status: verified
      name: Webex
      slug: webex
      sources:
      - https://calendly.com/integration/webex
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      - https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
      status: profiled
      tags:
      - Calling
      - Collaboration
      - Communications
      - Enterprise
      tier: observed
      url: /providers/webex/
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Acuity Scheduling
      - Cal.com
      - Calendly
      band: developing
      in_catalog: true
      kin_score: 52.2
      mcp:
        status: none
      name: Google Meet
      slug: google-meet
      sources:
      - https://acuityscheduling.com/integrations
      - https://calendly.com/integration/google-meet
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Google
      - Google Workspace
      - Meetings
      - Recording
      tier: observed
      url: /providers/google-meet/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Cal.com
      - Calendly
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://calendly.com/integration/microsoft-teams
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: observed
      url: /providers/microsoft-teams/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Acuity Scheduling
      - Calendly
      band: minimal
      in_catalog: true
      kin_score: 4.0
      mcp:
        status: none
      name: GoTo Meeting
      slug: goto
      sources:
      - https://acuityscheduling.com/integrations
      - https://calendly.com/integration/gotomeeting
      status: profiled
      tags:
      - Company
      - Consumer
      - Indonesia
      - Super App
      tier: declared
      url: /providers/goto/
    - agent_band: agent-native
      agent_readiness: 40.2
      apps:
      - Cal.com
      band: exemplar
      in_catalog: true
      kin_score: 73.0
      mcp:
        status: none
      name: 8x8 Meet
      slug: 8x8
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - CPaaS
      - Telecommunications
      - UCaaS
      - United States
      tier: observed
      url: /providers/8x8/
    - agent_band: agent-aware
      agent_readiness: 20.3
      apps:
      - Cal.com
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        status: none
      name: Whereby
      slug: whereby
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Communications
      - Real-Time
      - Video
      - WebRTC
      tier: observed
      url: /providers/whereby/
    - agent_band: agent-ready
      agent_readiness: 29.7
      apps:
      - Cal.com
      band: developing
      in_catalog: true
      kin_score: 48.5
      mcp:
        status: none
      name: Daily (Cal Video)
      slug: daily-co
      sources:
      - https://raw.githubusercontent.com/calcom/cal.com/main/apps/web/package.json
      status: profiled
      tags:
      - Daily
      - Real-Time
      - Video
      - WebRTC
      tier: observed
      url: /providers/daily-co/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Cal.com
      band: developing
      in_catalog: true
      kin_score: 47.4
      mcp:
        source: https://github.com/riversidefm/riverside-mcp-public
        status: verified
      name: Riverside
      slug: riverside
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Content Creation
      - Media
      - Podcasts
      - Video Recording
      tier: observed
      url: /providers/riverside/
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Calendly
      band: developing
      in_catalog: true
      kin_score: 43.6
      mcp:
        status: none
      name: ON24
      slug: on24
      sources:
      - https://calendly.com/integration/on24
      status: profiled
      tags:
      - Company
      - Digital Engagement
      - Virtual Events
      - Webinars
      tier: declared
      url: /providers/on24/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Calendly
      band: emerging
      in_catalog: true
      kin_score: 18.4
      mcp:
        status: none
      name: Loom
      slug: loom
      sources:
      - https://calendly.com/integration/loom
      status: profiled
      tags:
      - Async
      - Communications
      - Productivity
      - Video
      tier: declared
      url: /providers/loom/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Acuity Scheduling
      - Cal.com
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://acuityscheduling.com/integrations
      - https://calendly.com/integration/salesforce
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: observed
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Cal.com
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://calendly.com/integration/hubspot
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: observed
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 43.3
      apps:
      - Acuity Scheduling
      - Cal.com
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        status: none
      name: Zoho CRM
      slug: zoho-crm
      sources:
      - https://acuityscheduling.com/integrations
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - CRM
      - Lead Management
      - Marketing Automation
      - Sales
      tier: observed
      url: /providers/zoho-crm/
    - agent_band: agent-ready
      agent_readiness: 58.1
      apps:
      - Cal.com
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 77.2
      mcp:
        source: https://developer.close.com/mcp
        status: verified
      name: Close
      slug: close
      sources:
      - https://calendly.com/integration/close
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - CRM
      - Calling
      - Inside Sales
      - Sales Engagement
      tier: observed
      url: /providers/close/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Cal.com
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: Pipedrive
      slug: pipedrive
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - CRM
      - Pipeline Management
      - Sales
      - Software-as-a-Service
      tier: observed
      url: /providers/pipedrive/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Cal.com
      band: emerging
      in_catalog: true
      kin_score: 20.0
      mcp:
        source: https://docs.attio.com/mcp/overview
        status: verified
      name: Attio
      slug: attio
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - CRM
      - Companies
      - Contacts
      - Sales
      tier: observed
      url: /providers/attio/
    - agent_band: agent-ready
      agent_readiness: 51.2
      apps:
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        status: none
      name: Nutshell
      slug: nutshell
      sources:
      - https://calendly.com/integration/nutshell
      status: profiled
      tags:
      - CRM
      - Email Marketing
      - Pipeline Management
      - Sales
      tier: declared
      url: /providers/nutshell/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        source: https://github.com/microsoft/Dataverse-MCP
        status: verified
      name: Microsoft Dynamics
      slug: microsoft-dynamics-365
      sources:
      - https://calendly.com/integration/microsoft-dynamics
      status: profiled
      tags:
      - Business Applications
      - CRM
      - Cloud
      - Enterprise
      tier: declared
      url: /providers/microsoft-dynamics-365/
    - agent_band: agent-ready
      agent_readiness: 44.5
      apps:
      - Acuity Scheduling
      band: strong
      in_catalog: true
      kin_score: 65.0
      mcp:
        status: none
      name: Infusionsoft (Keap)
      slug: keap
      sources:
      - https://acuityscheduling.com/integrations
      status: profiled
      tags:
      - CRM
      - Marketing Automation
      - Sales
      - Small Business
      tier: declared
      url: /providers/keap/
    - agent_band: agent-aware
      agent_readiness: 24.0
      apps:
      - Acuity Scheduling
      band: developing
      in_catalog: true
      kin_score: 49.9
      mcp:
        status: unknown
      name: Daylite
      slug: daylite
      sources:
      - https://acuityscheduling.com/integrations
      status: profiled
      tags:
      - CRM
      - Company
      - Mac
      - Small Business
      tier: declared
      url: /providers/daylite/
    - agent_band: agent-aware
      agent_readiness: 26.9
      apps:
      - Calendly
      band: thin
      in_catalog: true
      kin_score: 34.1
      mcp:
        status: none
      name: Streak
      slug: streak
      sources:
      - https://calendly.com/integration/streak
      status: profiled
      tags:
      - CRM
      - Gmail
      - Pipeline Management
      - Sales
      tier: declared
      url: /providers/streak/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Acuity Scheduling
      - Cal.com
      - Calendly
      - Easy!Appointments
      - Rallly
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://acuityscheduling.com/integrations
      - https://calendly.com/integration/google
      - https://github.com/alextselegidis/easyappointments/tree/main/application/libraries
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: observed
      url: /providers/google-calendar/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Acuity Scheduling
      - Cal.com
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 70.8
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Outlook / Office 365 Calendar
      slug: microsoft-outlook
      sources:
      - https://acuityscheduling.com/integrations
      - https://calendly.com/integration/microsoft
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Calendar
      - Contacts
      - Email
      - Enterprise
      tier: observed
      url: /providers/microsoft-outlook/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Acuity Scheduling
      - Cal.com
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Apple Calendar
      slug: apple
      sources:
      - https://acuityscheduling.com/integrations
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - Cal.com
      band: strong
      in_catalog: true
      kin_score: 64.9
      mcp:
        status: none
      name: Exchange Calendar
      slug: microsoft-exchange
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Contacts
      - Email
      tier: observed
      url: /providers/microsoft-exchange/
    - agent_band: agent-ready
      agent_readiness: 32.4
      apps:
      - Cal.com
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp: &id001
        source: https://www.zoho.com/mcp/
        status: verified
      name: Zoho Calendar
      slug: zoho
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags: &id002
      - Analytics
      - CRM
      - Collaboration
      - Customer Service
      tier: observed
      url: /providers/zoho/
    - agent_band: agent-ready
      agent_readiness: 38.2
      apps:
      - Acuity Scheduling
      band: strong
      in_catalog: true
      kin_score: 57.2
      mcp:
        source: https://docs.cloud.google.com/mcp/supported-products
        status: verified
      name: Google Contacts
      slug: google-people
      sources:
      - https://acuityscheduling.com/integrations
      status: profiled
      tags:
      - Address Book
      - Contacts
      - Google
      - People
      tier: declared
      url: /providers/google-people/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.0
      apps:
      - Acuity Scheduling
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 81.1
      mcp:
        source: https://developers.activecampaign.com/page/mcp
        status: documented
      name: ActiveCampaign
      slug: activecampaign
      sources:
      - https://acuityscheduling.com/integrations
      - https://calendly.com/integration/activecampaign
      status: profiled
      tags:
      - CRM
      - Email Marketing
      - Marketing Automation
      - Sales Automation
      tier: declared
      url: /providers/activecampaign/
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Acuity Scheduling
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 80.4
      mcp:
        status: none
      name: Kit
      slug: convertkit
      sources:
      - https://acuityscheduling.com/integrations
      - https://calendly.com/integration/kit
      status: profiled
      tags:
      - Automation
      - Creator Economy
      - Email Marketing
      - Subscribers
      tier: declared
      url: /providers/convertkit/
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Acuity Scheduling
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://acuityscheduling.com/integrations
      - https://calendly.com/integration/mailchimp
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - Acuity Scheduling
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 71.7
      mcp:
        source: https://github.com/aweber/aweber-mcp
        status: verified
      name: AWeber
      slug: aweber
      sources:
      - https://acuityscheduling.com/integrations
      - https://calendly.com/integration/aweber
      status: profiled
      tags:
      - Email
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/aweber/
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - Acuity Scheduling
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        status: none
      name: Constant Contact
      slug: constant-contact
      sources:
      - https://acuityscheduling.com/integrations
      status: profiled
      tags:
      - Campaigns
      - Contacts
      - Email Marketing
      - Event
      tier: declared
      url: /providers/constant-contact/
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Acuity Scheduling
      band: strong
      in_catalog: true
      kin_score: 63.9
      mcp:
        status: none
      name: Drip
      slug: drip
      sources:
      - https://acuityscheduling.com/integrations
      status: profiled
      tags:
      - Customer Engagement
      - E-Commerce
      - Email Marketing
      - Marketing Automation
      tier: declared
      url: /providers/drip/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Acuity Scheduling
      - Booksy Biz
      - Cal.com
      - Calendly
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id005
        status: none
      name: Meta Pixel
      slug: facebook
      sources:
      - https://acuityscheduling.com/integrations
      - https://calendly.com/integration/meta-ads
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags: &id006
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 28.4
      apps:
      - Cal.com
      band: strong
      in_catalog: true
      kin_score: 59.3
      mcp:
        source: https://dub.co/docs/mcp-server.md
        status: verified
      name: Dub
      slug: dub
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Link Management
      - URL Shorteners
      tier: observed
      url: /providers/dub/
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp:
        status: none
      name: LinkedIn Ads
      slug: linkedin
      sources:
      - https://calendly.com/integration/linkedin-ads
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: declared
      url: /providers/linkedin/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Calendly
      band: developing
      in_catalog: true
      kin_score: 40.5
      mcp:
        status: none
      name: TikTok
      slug: tiktok
      sources:
      - https://calendly.com/integration/tiktok
      status: profiled
      tags:
      - Advertising
      - Commerce
      - Content
      - TikTok
      tier: declared
      url: /providers/tiktok/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Acuity Scheduling
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        status: none
      name: ReferralCandy
      slug: referralcandy
      sources:
      - https://acuityscheduling.com/integrations
      status: profiled
      tags:
      - Affiliates
      - Company
      - E-Commerce
      - Referrals
      tier: declared
      url: /providers/referralcandy/
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Cal.com
      band: thin
      in_catalog: true
      kin_score: 31.4
      mcp:
        status: none
      name: Formbricks
      slug: formbricks
      sources:
      - https://raw.githubusercontent.com/calcom/cal.com/main/packages/lib/package.json
      status: profiled
      tags:
      - Experience Management
      - Feedback
      - Forms
      - Surveys
      tier: observed
      url: /providers/formbricks/
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 70.2
      mcp:
        source: https://github.com/jotform/mcp-server
        status: verified
      name: Jotform
      slug: jotform
      sources:
      - https://calendly.com/integration/jotform
      status: profiled
      tags:
      - Data Collection
      - Forms
      - No-Code
      - Surveys
      tier: declared
      url: /providers/jotform/
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Acuity Scheduling
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: Wufoo
      slug: wufoo
      sources:
      - https://acuityscheduling.com/integrations
      status: profiled
      tags:
      - Data Collection
      - Form Builder
      - Forms
      - Surveys
      tier: declared
      url: /providers/wufoo/
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Calendly
      band: developing
      in_catalog: true
      kin_score: 53.1
      mcp:
        status: none
      name: Google Forms
      slug: google-forms
      sources:
      - https://calendly.com/integration/google-forms
      status: profiled
      tags:
      - Data Collection
      - Forms
      - Google
      - Google Workspace
      tier: declared
      url: /providers/google-forms/
    - agent_band: agent-ready
      agent_readiness: 42.6
      apps:
      - Calendly
      band: thin
      in_catalog: true
      kin_score: 36.0
      mcp:
        source: https://www.typeform.com/developers/mcp
        status: verified
      name: Typeform
      slug: typeform
      sources:
      - https://calendly.com/integration/typeform
      status: profiled
      tags:
      - Forms
      - Lead Capture
      - Software-as-a-Service
      - Surveys
      tier: declared
      url: /providers/typeform/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Cal.com
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: WhatsApp
      slug: whatsapp
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: observed
      url: /providers/whatsapp/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Cal.com
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Cal.com
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
    - agent_band: agent-aware
      agent_readiness: 20.3
      apps:
      - Cal.com
      band: developing
      in_catalog: true
      kin_score: 43.2
      mcp:
        status: none
      name: Signal
      slug: signal
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Cryptography
      - Encryption
      - Messaging
      - Security
      tier: observed
      url: /providers/signal/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Cal.com
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        source: https://github.com/WordPress/mcp-adapter
        status: verified
      name: WordPress
      slug: wordpress
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - CMS
      - Content Management
      - Open Source
      - WordPress
      tier: observed
      url: /providers/wordpress/
    - agent_band: human-only
      agent_readiness: 2.4
      apps:
      - Cal.com
      band: emerging
      in_catalog: true
      kin_score: 18.8
      mcp:
        source: https://www.framer.com/developers/mcp
        status: verified
      name: Framer
      slug: framer
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Design
      - No-Code
      - Productivity
      - Web Design
      tier: observed
      url: /providers/framer/
    - agent_band: agent-native
      agent_readiness: 48.5
      apps:
      - Acuity Scheduling
      band: exemplar
      in_catalog: true
      kin_score: 68.7
      mcp:
        status: none
      name: Squarespace
      slug: squarespace
      sources:
      - https://acuityscheduling.com/integrations
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Marketing
      - Payments
      tier: declared
      url: /providers/squarespace/
  - capability:
      attribution: Turbo EA
      id: BC-300.10
      key: talent-acquisition-management
      name: Talent Acquisition Management
      url: /capabilities/talent-acquisition-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 60.3
      apps:
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 77.9
      mcp:
        status: none
      name: Greenhouse
      slug: greenhouse
      sources:
      - https://calendly.com/integration/greenhouse
      status: profiled
      tags:
      - Applicant Tracking
      - Greenhouse
      - Human Resources
      - Recruiting
      tier: declared
      url: /providers/greenhouse/
    - agent_band: agent-ready
      agent_readiness: 32.4
      apps:
      - Calendly
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp: *id001
      name: Zoho Recruit
      slug: zoho
      sources:
      - https://calendly.com/integration/zoho-recruit
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/zoho/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Calendly
      band: thin
      in_catalog: true
      kin_score: 27.4
      mcp:
        status: none
      name: JazzHR
      slug: jazzhr
      sources:
      - https://calendly.com/integration/jazzhr
      status: profiled
      tags:
      - Applicant Tracking
      - Hiring
      - Recruiting
      - Small Business
      tier: declared
      url: /providers/jazzhr/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.50.20
      key: AE-140.50.20
      name: Corporate & Digital Gifting
      url: /capabilities/gift-cards-gifting-cashback/
      via_parent: Gift Cards, Gifting & Cashback
    providers:
    - agent_band: agent-ready
      agent_readiness: 55.2
      apps:
      - Calendly
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp:
        source: https://app.reachdesk.com/mcp
        status: verified
      name: Reachdesk
      slug: reachdesk
      sources:
      - https://calendly.com/integration/reachdesk
      status: profiled
      tags:
      - B2B
      - Corporate Gifting
      - Direct Mail
      - Swag
      tier: declared
      url: /providers/reachdesk/
    - agent_band: agent-ready
      agent_readiness: 40.6
      apps:
      - Calendly
      band: strong
      in_catalog: true
      kin_score: 59.0
      mcp:
        status: none
      name: Sendoso
      slug: sendoso
      sources:
      - https://calendly.com/integration/sendoso
      status: profiled
      tags:
      - Corporate Gifting
      - Direct Mail
      - Marketing Automation
      - Sales Engagement
      tier: declared
      url: /providers/sendoso/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 63.0
      apps:
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 86.8
      mcp:
        source: https://github.com/Zoominfo/zoominfo-mcp-plugin
        status: verified
      name: ZoomInfo
      slug: zoominfo
      sources:
      - https://calendly.com/integration/zoominfo
      status: profiled
      tags:
      - B2B
      - B2B Data
      - Company Data
      - Contact Database
      tier: declared
      url: /providers/zoominfo/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Calendly
      band: strong
      in_catalog: true
      kin_score: 59.3
      mcp:
        status: none
      name: Clearbit
      slug: clearbit
      sources:
      - https://calendly.com/integration/clearbit
      status: profiled
      tags:
      - B2B
      - Data Enrichment
      - Reveal
      - Sales Intelligence
      tier: declared
      url: /providers/clearbit/
  - capability:
      attribution: Turbo EA
      id: BC-4330.50
      key: invoice-generation-management
      name: Invoice Generation Management
      url: /capabilities/invoice-generation-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Acuity Scheduling
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks
      slug: quickbooks
      sources:
      - https://acuityscheduling.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: agent-aware
      agent_readiness: 19.7
      apps:
      - Acuity Scheduling
      band: thin
      in_catalog: true
      kin_score: 31.0
      mcp:
        status: none
      name: FreshBooks
      slug: freshbooks
      sources:
      - https://acuityscheduling.com/integrations
      status: profiled
      tags:
      - Accounting
      - Expense Tracking
      - Invoicing
      - Time Tracking
      tier: declared
      url: /providers/freshbooks/
  - capability:
      attribution: Turbo EA
      id: BC-400.50
      key: marketing-operations-management
      name: Marketing Operations Management
      url: /capabilities/marketing-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Calendly
      band: strong
      in_catalog: true
      kin_score: 60.7
      mcp:
        status: none
      name: Pardot
      slug: pardot
      sources:
      - https://calendly.com/integration/pardot
      status: profiled
      tags:
      - B2B Marketing
      - Email Marketing
      - Lead Generation
      - Marketing Automation
      tier: declared
      url: /providers/pardot/
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - Calendly
      band: strong
      in_catalog: true
      kin_score: 57.2
      mcp:
        status: none
      name: Marketo
      slug: marketo
      sources:
      - https://calendly.com/integration/marketo
      status: profiled
      tags:
      - Adobe
      - Automation
      - Marketing
      - Marketing Automation
      tier: declared
      url: /providers/marketo/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.40
      key: AE-110.30.40
      name: Meeting Notes & Conversation Intelligence
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.8
      apps:
      - Cal.com
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        source: https://demodesk.ai/
        status: documented
      name: Demodesk
      slug: demodesk
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Conversation Intelligence
      - Sales
      tier: observed
      url: /providers/demodesk/
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 66.5
      mcp:
        status: none
      name: Gong
      slug: gong
      sources:
      - https://calendly.com/integration/gong
      status: profiled
      tags:
      - Analytics
      - Conversations
      - Revenue Intelligence
      - Sales
      tier: declared
      url: /providers/gong/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.0
      apps:
      - Cal.com
      band: thin
      in_catalog: true
      kin_score: 31.2
      mcp:
        status: none
      name: Dialpad
      slug: dialpad
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Artificial Intelligence
      - Communications
      - Contact Center
      - Voice
      tier: observed
      url: /providers/dialpad/
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Calendly
      band: developing
      in_catalog: true
      kin_score: 54.1
      mcp:
        status: none
      name: CallRail
      slug: callrail
      sources:
      - https://calendly.com/integration/callrail
      status: profiled
      tags:
      - Call Tracking
      - Conversation Intelligence
      - Lead Tracking
      - Marketing Attribution
      tier: declared
      url: /providers/callrail/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 46.7
      apps:
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://github.com/Yelp/yelp-mcp
        status: verified
      name: Yelp
      slug: yelp
      sources:
      - https://calendly.com/integration/yelp
      status: profiled
      tags:
      - Business Data
      - Local Search
      - Restaurant
      - Reviews
      tier: declared
      url: /providers/yelp/
    - agent_band: agent-native
      agent_readiness: 40.1
      apps:
      - Calendly
      band: strong
      in_catalog: true
      kin_score: 59.1
      mcp:
        status: none
      name: Podium
      slug: podium
      sources:
      - https://calendly.com/integration/podium
      status: profiled
      tags:
      - Customer Communication
      - Messaging
      - Payments
      - Reviews
      tier: declared
      url: /providers/podium/
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - Acuity Scheduling
      band: exemplar
      in_catalog: true
      kin_score: 68.9
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Reserve with Google
      slug: google
      sources:
      - https://acuityscheduling.com/integrations
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: declared
      url: /providers/google/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Acuity Scheduling
      band: emerging
      in_catalog: true
      kin_score: 11.0
      mcp:
        status: none
      name: ClassPass
      slug: classpass
      sources:
      - https://acuityscheduling.com/integrations
      status: profiled
      tags:
      - Class Booking
      - Fitness
      - Marketplace
      - Wellness
      tier: declared
      url: /providers/classpass/
  - capability:
      attribution: API Evangelist extension
      id: AE-220.10
      key: AE-220.10
      name: Online Courses
      url: /capabilities/online-courses/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.9
      apps:
      - Calendly
      band: developing
      in_catalog: true
      kin_score: 40.1
      mcp:
        source: https://help.kajabi.com/en/collections/19761100-mcp
        status: documented
      name: Kajabi
      slug: kajabi
      sources:
      - https://calendly.com/integration/kajabi
      status: profiled
      tags:
      - Creator Economy
      - E-Commerce
      - Membership
      - Online Courses
      tier: declared
      url: /providers/kajabi/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Acuity Scheduling
      - Cal.com
      - Calendly
      - LibreBooking
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics 4
      slug: google-analytics
      sources:
      - https://acuityscheduling.com/integrations
      - https://calendly.com/integration/google-analytics
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Acuity Scheduling
      - Booksy Biz
      - Calendly
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.calendly.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/net.booksy.business/latest/
      status: profiled
      tags: &id004
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 56.2
      apps:
      - Cal.com
      - Rallly
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://raw.githubusercontent.com/calcom/cal.com/main/apps/web/package.json
      - https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Booksy Biz
      - Calendly
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.calendly.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/net.booksy.business/latest/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
      - Cal.com
      band: exemplar
      in_catalog: true
      kin_score: 72.8
      mcp:
        status: none
      name: Umami
      slug: umami
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Cookieless Tracking
      - Open Source
      - Privacy
      - Web Analytics
      tier: observed
      url: /providers/umami/
    - agent_band: agent-ready
      agent_readiness: 41.3
      apps:
      - Cal.com
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/matomo-org/plugin-McpServer
        status: verified
      name: Matomo
      slug: matomo
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Analytics
      - Open Source
      - Privacy
      - Web Analytics
      tier: observed
      url: /providers/matomo/
    - agent_band: agent-aware
      agent_readiness: 22.6
      apps:
      - Cal.com
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        status: none
      name: Plausible
      slug: plausible
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Analytics
      - Cookie-Free
      - Event Tracking
      - GDPR
      tier: observed
      url: /providers/plausible/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - Acuity Scheduling
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 30.3
      apps:
      - Cal.com
      band: developing
      in_catalog: true
      kin_score: 47.7
      mcp:
        status: none
      name: Fathom Analytics
      slug: fathom
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Analytics
      - GDPR
      - Privacy
      - Website Analytics
      tier: observed
      url: /providers/fathom/
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Calendly
      band: strong
      in_catalog: true
      kin_score: 57.0
      mcp:
        source: https://support.pendo.io/hc/en-us/articles/41102236924955
        status: verified
      name: Pendo
      slug: pendoio
      sources:
      - https://calendly.com/integration/pendo
      status: profiled
      tags:
      - Company
      - Digital Adoption
      - Product Analytics
      - Product Experience
      tier: declared
      url: /providers/pendoio/
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
      - Acuity Scheduling
      - Cal.com
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://acuityscheduling.com/integrations
      - https://calendly.com/integration/zapier
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: observed
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 31.1
      apps:
      - Cal.com
      - Calendly
      band: strong
      in_catalog: true
      kin_score: 65.5
      mcp:
        source: https://pipedream.com/docs/connect/mcp
        status: verified
      name: Pipedream
      slug: pipedream
      sources:
      - https://calendly.com/integration/pipedream
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Connect
      - Pipedream
      - Pro-Code-API-Composition
      - Workflows
      tier: observed
      url: /providers/pipedream/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Cal.com
      - Calendly
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://calendly.com/integration/make
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: observed
      url: /providers/make/
    - agent_band: agent-ready
      agent_readiness: 35.7
      apps:
      - Cal.com
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        source: https://docs.n8n.io/advanced-ai/accessing-n8n-mcp-server/
        status: verified
      name: n8n
      slug: n8n
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Integration
      - Workflows
      tier: observed
      url: /providers/n8n/
    - agent_band: agent-aware
      agent_readiness: 13.3
      apps:
      - Cal.com
      band: emerging
      in_catalog: true
      kin_score: 25.2
      mcp:
        status: none
      name: Raycast
      slug: raycast
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Extensions
      - Launcher
      - Productivity
      - SDK
      tier: observed
      url: /providers/raycast/
    - agent_band: agent-ready
      agent_readiness: 53.8
      apps:
      - Calendly
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://docs.workato.com/mcp.html
        status: verified
      name: Workato
      slug: workato
      sources:
      - https://calendly.com/integration/workato
      status: profiled
      tags:
      - AI Agents
      - API Management
      - Automation
      - B2B
      tier: declared
      url: /providers/workato/
    - agent_band: agent-ready
      agent_readiness: 32.4
      apps:
      - Acuity Scheduling
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp: *id001
      name: Zoho Flow
      slug: zoho
      sources:
      - https://acuityscheduling.com/integrations
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/zoho/
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Acuity Scheduling
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://acuityscheduling.com/integrations
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: declared
      url: /providers/google-sheets/
    - agent_band: agent-ready
      agent_readiness: 29.1
      apps:
      - Calendly
      band: strong
      in_catalog: true
      kin_score: 62.1
      mcp:
        status: none
      name: Power Automate
      slug: microsoft-power-automate
      sources:
      - https://calendly.com/integration/power-automate
      status: profiled
      tags:
      - Automation
      - Business Process
      - Integration
      - Low-Code
      tier: declared
      url: /providers/microsoft-power-automate/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Acuity Scheduling
      - Cal.com
      - Calendly
      - LibreBooking
      - Rallly
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://acuityscheduling.com/integrations
      - https://calendly.com/integration/stripe
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Acuity Scheduling
      - Cal.com
      - Calendly
      - LibreBooking
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://acuityscheduling.com/integrations
      - https://calendly.com/integration/paypal
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - Cal.com
      band: strong
      in_catalog: true
      kin_score: 64.8
      mcp:
        status: none
      name: HitPay
      slug: hitpay
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Fintech
      - PayNow
      - Payments
      - Southeast Asia
      tier: observed
      url: /providers/hitpay/
    - agent_band: agent-native
      agent_readiness: 61.5
      apps:
      - Acuity Scheduling
      band: exemplar
      in_catalog: true
      kin_score: 78.2
      mcp:
        source: https://developer.squareup.com/docs/mcp
        status: verified
      name: Square
      slug: square
      sources:
      - https://acuityscheduling.com/integrations
      status: profiled
      tags:
      - Booking
      - Location
      - Restaurant
      - Square
      tier: declared
      url: /providers/square/
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
      - Cal.com
      - Rallly
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/calcom/cal.com/main/apps/web/package.json
      - https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/package.json
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Booksy Biz
      - Calendly
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id003
      name: Google Crashlytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.calendly.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/net.booksy.business/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Acuity Scheduling
      band: exemplar
      in_catalog: true
      kin_score: 76.3
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
    - agent_band: agent-ready
      agent_readiness: 61.2
      apps:
      - Cal.com
      band: exemplar
      in_catalog: true
      kin_score: 76.2
      mcp:
        source: https://www.checklyhq.com/docs/guides/communicate-availability.md
        status: documented
      name: Checkly
      slug: checkly
      sources:
      - https://raw.githubusercontent.com/calcom/cal.com/main/package.json
      status: profiled
      tags:
      - Monitoring
      - Observability
      - Synthetic Monitoring
      - Testing
      tier: observed
      url: /providers/checkly/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - Acuity Scheduling
      band: developing
      in_catalog: true
      kin_score: 45.8
      mcp:
        source: https://docs.luciq.ai/product-guides-and-integrations/product-guides/ai-features.md
        status: documented
      name: Instabug
      slug: instabug
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
      status: profiled
      tags:
      - AI Agents
      - APM
      - Application Performance Monitoring
      - Bug Reporting
      tier: observed
      url: /providers/instabug/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Cal.com
      - LibreBooking
      - Rallly
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://raw.githubusercontent.com/LibreBooking/librebooking/develop/config/config.dist.php
      - https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
      - https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
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
      - LibreBooking
      - Rallly
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Microsoft sign-in
      slug: microsoft-entra
      sources:
      - https://raw.githubusercontent.com/LibreBooking/librebooking/develop/config/config.dist.php
      - https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - LibreBooking
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id005
      name: Facebook Login
      slug: facebook
      sources:
      - https://raw.githubusercontent.com/LibreBooking/librebooking/develop/config/config.dist.php
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Cal.com
      - Calendly
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://calendly.com/integration/intercom
      - https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: observed
      url: /providers/intercom/
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Cal.com
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: observed
      url: /providers/zendesk/
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - Cal.com
      band: developing
      in_catalog: true
      kin_score: 51.5
      mcp:
        status: none
      name: Help Scout
      slug: helpscout
      sources:
      - https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
      status: profiled
      tags:
      - Customer Service
      - Email
      - Help Desk
      - Live Chat
      tier: observed
      url: /providers/helpscout/
    - agent_band: agent-aware
      agent_readiness: 23.4
      apps:
      - Cal.com
      band: thin
      in_catalog: true
      kin_score: 36.2
      mcp:
        status: none
      name: Freshchat
      slug: freshchat
      sources:
      - https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
      status: profiled
      tags:
      - Conversational Engagement
      - Customer Messaging
      - Customer Service
      - Live Chat
      tier: observed
      url: /providers/freshchat/
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
      - Calendly
      - LibreBooking
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://calendly.com/integration/slack
      - https://raw.githubusercontent.com/LibreBooking/librebooking/develop/config/config.dist.php
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-aware
      agent_readiness: 24.9
      apps:
      - Cal.com
      band: developing
      in_catalog: true
      kin_score: 49.0
      mcp:
        source: https://github.com/basecamp/mcp
        status: verified
      name: Basecamp
      slug: basecamp
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Collaboration
      - Project Management
      - REST
      - Software-as-a-Service
      tier: observed
      url: /providers/basecamp/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - Cal.com
      band: developing
      in_catalog: true
      kin_score: 39.6
      mcp:
        source: https://linear.app/docs/mcp
        status: verified
      name: Linear
      slug: linear-app
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Issue Tracking
      - Productivity
      - Project Management
      - Software-as-a-Service
      tier: observed
      url: /providers/linear-app/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.2
      apps:
      - Cal.com
      - Rallly
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        source: https://github.com/cloudflare/mcp
        status: verified
      name: Cloudflare Turnstile
      slug: cloudflare-turnstile
      sources:
      - https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
      - https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Cloudflare
      - Turnstile
      tier: observed
      url: /providers/cloudflare-turnstile/
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - LibreBooking
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://raw.githubusercontent.com/LibreBooking/librebooking/develop/composer.json
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: observed
      url: /providers/google-recaptcha/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - Booksy Biz
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/net.booksy.business/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Booksy Biz
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/net.booksy.business/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Acuity Scheduling
      band: emerging
      in_catalog: true
      kin_score: 13.7
      mcp:
        status: unknown
      name: Tune
      slug: tune
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
      status: profiled
      tags:
      - Advertising
      - Affiliates
      - Marketing
      - Software-as-a-Service
      tier: observed
      url: /providers/tune/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - Cal.com
      band: exemplar
      in_catalog: true
      kin_score: 84.0
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://raw.githubusercontent.com/calcom/cal.com/main/packages/lib/package.json
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - Rallly
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        status: none
      name: Amazon SES
      slug: amazon-ses
      sources:
      - https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/src/env.ts
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
    - agent_band: agent-ready
      agent_readiness: 49.8
      apps:
      - Cal.com
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        source: https://resend.com/docs/mcp-server
        status: verified
      name: Resend
      slug: resend
      sources:
      - https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
      status: profiled
      tags:
      - Developer Tools
      - Email
      - Marketing Email
      - Transactional Email
      tier: observed
      url: /providers/resend/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.7
      apps:
      - Cal.com
      - Rallly
      band: thin
      in_catalog: true
      kin_score: 35.2
      mcp:
        source: https://github.com/upstash/mcp-server
        status: verified
      name: Upstash
      slug: upstash
      sources:
      - https://raw.githubusercontent.com/calcom/cal.com/main/apps/web/package.json
      - https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/package.json
      status: profiled
      tags:
      - Kafka
      - Messaging
      - Redis
      - Serverless
      tier: observed
      url: /providers/upstash/
  - capability:
      attribution: API Evangelist extension
      id: AE-240.70.20
      key: AE-240.70.20
      name: Crypto Payment Acceptance
      url: /capabilities/stablecoin-payments/
      via_parent: Stablecoin Payments
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.6
      apps:
      - Cal.com
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: BTCPay Server
      slug: btcpay
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Bitcoin
      - Cryptocurrency
      - Lightning Network
      - Payments
      tier: observed
      url: /providers/btcpay/
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - Cal.com
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare
      slug: cloudflare
      sources:
      - https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
      status: profiled
      tags:
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: observed
      url: /providers/cloudflare/
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.0
      apps:
      - Cal.com
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp: &id007
        source: https://vercel.com/docs/mcp/vercel-mcp
        status: verified
      name: Vercel
      slug: vercel
      sources:
      - https://raw.githubusercontent.com/calcom/cal.com/main/apps/web/package.json
      status: profiled
      tags: &id008
      - AI Gateway
      - Gateways
      - Observability
      - Webhook
      tier: observed
      url: /providers/vercel/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Rallly
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
  - capability:
      attribution: Turbo EA
      id: BC-600.40.20
      key: BC-600.40.20
      name: IT Job Scheduling and Batch Operations
      url: /capabilities/it-operations-management/
      via_parent: IT Operations Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.8
      apps:
      - Cal.com
      band: strong
      in_catalog: true
      kin_score: 56.7
      mcp:
        source: https://github.com/triggerdotdev/trigger.dev
        status: verified
      name: Trigger.dev
      slug: trigger-dev
      sources:
      - https://raw.githubusercontent.com/calcom/cal.com/main/packages/features/package.json
      status: profiled
      tags:
      - Background Jobs
      - Durable Execution
      - TypeScript
      - Workflow Automation
      tier: observed
      url: /providers/trigger-dev/
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Acuity Scheduling
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.acuityscheduling.app.android/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
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
      - Cal.com
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://raw.githubusercontent.com/calcom/cal.com/main/.env.example
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
  - capability:
      attribution: Turbo EA
      id: BC-4220
      key: saas-platform-operations-management
      name: SaaS Platform Operations Management
      url: /capabilities/saas-platform-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Cal.com
      band: developing
      in_catalog: true
      kin_score: 44.9
      mcp:
        status: none
      name: Unkey
      slug: unkey
      sources:
      - https://raw.githubusercontent.com/calcom/cal.com/main/packages/lib/package.json
      status: profiled
      tags:
      - APIKeys
      - Authentication
      - Developer Platform
      - Rate Limiting
      tier: observed
      url: /providers/unkey/
  - capability:
      attribution: API Evangelist extension
      id: AE-925
      key: AE-925
      name: Serverless Functions
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.0
      apps:
      - Rallly
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp: *id007
      name: Vercel
      slug: vercel
      sources:
      - https://raw.githubusercontent.com/lukevella/rallly/main/apps/web/package.json
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/vercel/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Cal.com
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.20
      key: AE-100.70.20
      name: Voice Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.1
      apps:
      - Cal.com
      - Calendly
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Chatbase
      slug: chatbase
      sources:
      - https://calendly.com/integration/chatbase
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Chatbots
      - Customer Service
      tier: observed
      url: /providers/chatbase/
    - agent_band: agent-ready
      agent_readiness: 60.4
      apps:
      - Cal.com
      band: exemplar
      in_catalog: true
      kin_score: 83.2
      mcp:
        source: https://github.com/elevenlabs/elevenlabs-mcp
        status: verified
      name: ElevenLabs
      slug: elevenlabs
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Artificial Intelligence
      - Speech-to-Text
      - Text-to-Speech
      - Voice
      tier: observed
      url: /providers/elevenlabs/
    - agent_band: agent-ready
      agent_readiness: 58.2
      apps:
      - Cal.com
      band: strong
      in_catalog: true
      kin_score: 59.3
      mcp:
        source: https://docs.synthflow.ai/mcp-server
        status: verified
      name: Synthflow
      slug: synthflow
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - No-Code
      - Telephony
      - Voice
      - Voice Agents
      tier: observed
      url: /providers/synthflow/
    - agent_band: agent-aware
      agent_readiness: 28.0
      apps:
      - Cal.com
      band: strong
      in_catalog: true
      kin_score: 58.5
      mcp:
        status: none
      name: Lindy
      slug: lindy
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - AI Agents
      - AI Automation
      - MCP
      - Workflow Automation
      tier: observed
      url: /providers/lindy/
    - agent_band: agent-ready
      agent_readiness: 52.5
      apps:
      - Cal.com
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp:
        source: https://github.com/bolna-ai/mcp
        status: verified
      name: Bolna
      slug: bolna
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Conversational AI
      - Voice AI
      tier: observed
      url: /providers/bolna/
    - agent_band: agent-ready
      agent_readiness: 38.1
      apps:
      - Cal.com
      band: thin
      in_catalog: true
      kin_score: 35.7
      mcp:
        source: https://docs.retellai.com/
        status: documented
      name: Retell AI
      slug: retell-ai
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Real-Time
      - Voice
      tier: observed
      url: /providers/retell-ai/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.40
      key: AE-110.30.40
      name: Meeting Notes & Conversation Intelligence
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.0
      apps:
      - Cal.com
      band: thin
      in_catalog: true
      kin_score: 33.0
      mcp:
        source: https://docs.granola.ai/help-center/sharing/integrations/mcp
        status: documented
      name: Granola
      slug: granola
      sources:
      - https://github.com/calcom/cal.com/tree/main/packages/app-store
      status: profiled
      tags:
      - Artificial Intelligence
      - Meeting Notes
      - Productivity
      - Transcription
      tier: observed
      url: /providers/granola/
  layer: agent
summary:
  coverage_pct: 100.0
  declared_only: 46
  distinct_providers: 130
  in_catalog: 130
  mcp:
    documented: 7
    none: 66
    unchecked: 0
    verified: 55
  mcp_verified: 55
  mean_kin_score: 57.9
  observed: 84
  queued: 0
  reference_apps: 7
title: 'Appointment Booking & Scheduling: application blueprint'
---
