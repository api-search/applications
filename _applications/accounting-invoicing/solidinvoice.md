---
app: SolidInvoice
app_slug: solidinvoice
app_url: https://github.com/SolidInvoice/SolidInvoice
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Authorize.net
  - Be2bill (Dalenys)
  - Klarna
  - PayEx (Swedbank Pay)
  - PayPal
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Discord
  - Google Chat
  - LinkedIn
  - Microsoft Teams
  - Slack
  - Telegram
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Firebase (FCM)
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Amazon SNS
  - Bird (MessageBird)
  - Clickatell
  - Esendex
  - Infobip
  - Sinch
  - Telnyx
  - Twilio
  - Vonage
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES
  - Brevo
  - Mailchimp (Mandrill)
  - Mailgun
  - Mailjet
  - Postmark
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
category:
  id: accounting-invoicing
  name: Accounting & Invoicing
  url: /applications/accounting-invoicing/
counts:
  declared: 0
  observed: 30
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
integrations:
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
    agent_readiness: 38.0
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id001
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
  layer: common
  name: Amazon SES
  provider: amazon-ses
  says: ships the Amazon SES SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_band: agent-ready
    agent_readiness: 41.7
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sns
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Email
    - Messaging
    - Notification
    url: /providers/amazon-sns/
  layer: common
  name: Amazon SNS
  provider: amazon-sns
  says: ships the Amazon SNS SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_band: agent-aware
    agent_readiness: 25.4
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id005
      source: https://github.com/AuthorizeNet/authorize-net-mcp
      status: verified
    slug: authorizenet
    status: profiled
    tags: &id006
    - Company
    - Credit Cards
    - Payment Gateway
    - Payments
    url: /providers/authorizenet/
  layer: domain
  name: Authorize.net
  provider: authorizenet
  says: ships the Authorize.net SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_band: agent-aware
    agent_readiness: 23.6
    band: thin
    in_catalog: true
    kin_score: 37.4
    mcp: &id007
      source: https://github.com/payplug/payplug-plugin-mcp
      status: verified
    slug: payplug
    status: profiled
    tags: &id008
    - Company
    url: /providers/payplug/
  layer: domain
  name: Be2bill (Dalenys)
  provider: payplug
  says: ships the Be2bill (Dalenys) SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    mcp: &id009
      source: https://github.com/messagebird/bird-ai
      status: verified
    slug: bird
    status: profiled
    tags: &id010
    - Communications
    - Email
    - SMS
    - WhatsApp
    url: /providers/bird/
  layer: common
  name: Bird (MessageBird)
  provider: bird
  says: ships the Bird (MessageBird) SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_readiness: 56.4
    band: exemplar
    in_catalog: true
    kin_score: 81.3
    mcp: &id011
      source: https://developers.brevo.com/docs/mcp-protocol
      status: verified
    slug: brevo
    status: profiled
    tags: &id012
    - Email Marketing
    - Marketing
    - Marketing Automation
    - Transactional Email
    url: /providers/brevo/
  layer: common
  name: Brevo
  provider: brevo
  says: ships the Brevo SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_band: agent-ready
    agent_readiness: 28.9
    band: thin
    in_catalog: true
    kin_score: 38.8
    mcp: &id013
      status: none
    slug: clickatell
    status: profiled
    tags: &id014
    - Company
    - Messaging
    - SMS
    - WhatsApp
    url: /providers/clickatell/
  layer: common
  name: Clickatell
  provider: clickatell
  says: ships the Clickatell SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id015
      status: none
    slug: discord
    status: profiled
    tags: &id016
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_band: agent-aware
    agent_readiness: 18.1
    band: thin
    in_catalog: true
    kin_score: 37.4
    mcp: &id017
      status: none
    slug: esendex
    status: profiled
    tags: &id018
    - Business
    - Communications
    - Messaging
    - SMS
    url: /providers/esendex/
  layer: common
  name: Esendex
  provider: esendex
  says: ships the Esendex SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id019
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id020
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase (FCM)
  provider: firebase
  says: ships the Firebase (FCM) SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_readiness: 41.0
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id021
      source: https://github.com/google/mcp
      status: verified
    slug: google-chat
    status: profiled
    tags: &id022
    - Chat
    - Collaboration
    - Google
    - Google Workspace
    url: /providers/google-chat/
  layer: common
  name: Google Chat
  provider: google-chat
  says: ships the Google Chat SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_band: agent-ready
    agent_readiness: 61.3
    band: exemplar
    in_catalog: true
    kin_score: 86.9
    mcp: &id023
      source: https://www.infobip.com/docs/mcp
      status: verified
    slug: infobip
    status: profiled
    tags: &id024
    - CPaaS
    - Croatia
    - Messaging
    - Telecommunications
    url: /providers/infobip/
  layer: common
  name: Infobip
  provider: infobip
  says: ships the Infobip SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id025
      status: none
    slug: klarna
    status: profiled
    tags: &id026
    - Buy Now Pay Later
    - Cards
    - Fintech
    - Payments
    url: /providers/klarna/
  layer: domain
  name: Klarna
  provider: klarna
  says: ships the Klarna SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
  layer: common
  name: LinkedIn
  provider: linkedin
  says: ships the LinkedIn SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id029
      status: none
    slug: mailchimp
    status: profiled
    tags: &id030
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp (Mandrill)
  provider: mailchimp
  says: ships the Mailchimp (Mandrill) SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id031
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id032
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: common
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_band: agent-aware
    agent_readiness: 22.9
    band: developing
    in_catalog: true
    kin_score: 50.5
    mcp: &id033
      source: https://github.com/mailgun/mailjet-mcp-server
      status: verified
    slug: mailjet
    status: profiled
    tags: &id034
    - Email
    - Email Delivery
    - Marketing Email
    - SMTP
    url: /providers/mailjet/
  layer: common
  name: Mailjet
  provider: mailjet
  says: ships the Mailjet SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id035
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id036
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: ships the Microsoft Teams SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_band: agent-aware
    agent_readiness: 12.4
    band: thin
    in_catalog: true
    kin_score: 27.2
    mcp: &id037
      status: none
    slug: swedbank-pay
    status: profiled
    tags: &id038
    - Company
    - Fintech
    - Nordic
    - Payments
    url: /providers/swedbank-pay/
  layer: domain
  name: PayEx (Swedbank Pay)
  provider: swedbank-pay
  says: ships the PayEx (Swedbank Pay) SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
  layer: domain
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id041
      source: https://github.com/ActiveCampaign/postmark-mcp
      status: verified
    slug: postmark
    status: profiled
    tags: &id042
    - Deliverability
    - Email
    - Messaging
    - Transactional Email
    url: /providers/postmark/
  layer: common
  name: Postmark
  provider: postmark
  says: ships the Postmark SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_readiness: 40.7
    band: exemplar
    in_catalog: true
    kin_score: 84.0
    mcp: &id043
      status: none
    slug: sendgrid
    status: profiled
    tags: &id044
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    kin_score: 80.7
    mcp: &id045
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id046
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_readiness: 60.3
    band: exemplar
    in_catalog: true
    kin_score: 71.6
    mcp: &id047
      source: https://github.com/sinch/sinch-mcp-server
      status: verified
    slug: sinch
    status: profiled
    tags: &id048
    - Communications
    - Messaging
    - SMS
    - Voice
    url: /providers/sinch/
  layer: common
  name: Sinch
  provider: sinch
  says: ships the Sinch SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    mcp: &id049
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id050
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_band: agent-aware
    agent_readiness: 25.3
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id053
      status: none
    slug: telegram
    status: profiled
    tags: &id054
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_readiness: 80.0
    band: exemplar
    in_catalog: true
    kin_score: 93.5
    mcp: &id055
      source: https://github.com/team-telnyx/telnyx-mcp-server
      status: verified
    slug: telnyx
    status: profiled
    tags: &id056
    - CPaaS
    - Communications
    - SMS
    - Voice
    url: /providers/telnyx/
  layer: common
  name: Telnyx
  provider: telnyx
  says: ships the Telnyx SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    mcp: &id057
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id058
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
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
    agent_band: agent-ready
    agent_readiness: 40.0
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id059
      source: https://github.com/Vonage/vonage-mcp-server-documentation
      status: verified
    slug: vonage
    status: profiled
    tags: &id060
    - Communications
    - Messaging
    - Telecommunications
    - Video Conferencing
    url: /providers/vonage/
  layer: common
  name: Vonage
  provider: vonage
  says: ships the Vonage SDK or integration code
  source: https://raw.githubusercontent.com/SolidInvoice/SolidInvoice/2.3.x/composer.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/accounting-invoicing/solidinvoice/
providers:
- agent_band: agent-ready
  agent_readiness: 38.0
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id001
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id002
  url: /providers/amazon-ses/
- agent_band: agent-ready
  agent_readiness: 41.7
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id003
  name: Amazon SNS
  slug: amazon-sns
  status: profiled
  tags: *id004
  url: /providers/amazon-sns/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id005
  name: Authorize.net
  slug: authorizenet
  status: profiled
  tags: *id006
  url: /providers/authorizenet/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: thin
  in_catalog: true
  kin_score: 37.4
  mcp: *id007
  name: Be2bill (Dalenys)
  slug: payplug
  status: profiled
  tags: *id008
  url: /providers/payplug/
- agent_band: agent-native
  agent_readiness: 70.3
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id009
  name: Bird (MessageBird)
  slug: bird
  status: profiled
  tags: *id010
  url: /providers/bird/
- agent_band: agent-ready
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 81.3
  mcp: *id011
  name: Brevo
  slug: brevo
  status: profiled
  tags: *id012
  url: /providers/brevo/
- agent_band: agent-ready
  agent_readiness: 28.9
  band: thin
  in_catalog: true
  kin_score: 38.8
  mcp: *id013
  name: Clickatell
  slug: clickatell
  status: profiled
  tags: *id014
  url: /providers/clickatell/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id015
  name: Discord
  slug: discord
  status: profiled
  tags: *id016
  url: /providers/discord/
- agent_band: agent-aware
  agent_readiness: 18.1
  band: thin
  in_catalog: true
  kin_score: 37.4
  mcp: *id017
  name: Esendex
  slug: esendex
  status: profiled
  tags: *id018
  url: /providers/esendex/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id019
  name: Firebase (FCM)
  slug: google-firebase
  status: profiled
  tags: *id020
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 41.0
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id021
  name: Google Chat
  slug: google-chat
  status: profiled
  tags: *id022
  url: /providers/google-chat/
- agent_band: agent-ready
  agent_readiness: 61.3
  band: exemplar
  in_catalog: true
  kin_score: 86.9
  mcp: *id023
  name: Infobip
  slug: infobip
  status: profiled
  tags: *id024
  url: /providers/infobip/
- agent_band: agent-native
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id025
  name: Klarna
  slug: klarna
  status: profiled
  tags: *id026
  url: /providers/klarna/
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
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id029
  name: Mailchimp (Mandrill)
  slug: mailchimp
  status: profiled
  tags: *id030
  url: /providers/mailchimp/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id031
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id032
  url: /providers/mailgun/
- agent_band: agent-aware
  agent_readiness: 22.9
  band: developing
  in_catalog: true
  kin_score: 50.5
  mcp: *id033
  name: Mailjet
  slug: mailjet
  status: profiled
  tags: *id034
  url: /providers/mailjet/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id035
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id036
  url: /providers/microsoft-teams/
- agent_band: agent-aware
  agent_readiness: 12.4
  band: thin
  in_catalog: true
  kin_score: 27.2
  mcp: *id037
  name: PayEx (Swedbank Pay)
  slug: swedbank-pay
  status: profiled
  tags: *id038
  url: /providers/swedbank-pay/
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
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id041
  name: Postmark
  slug: postmark
  status: profiled
  tags: *id042
  url: /providers/postmark/
- agent_band: agent-ready
  agent_readiness: 40.7
  band: exemplar
  in_catalog: true
  kin_score: 84.0
  mcp: *id043
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id044
  url: /providers/sendgrid/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id045
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id046
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 60.3
  band: exemplar
  in_catalog: true
  kin_score: 71.6
  mcp: *id047
  name: Sinch
  slug: sinch
  status: profiled
  tags: *id048
  url: /providers/sinch/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id049
  name: Slack
  slug: slack
  status: profiled
  tags: *id050
  url: /providers/slack/
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
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id053
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id054
  url: /providers/telegram/
- agent_band: agent-native
  agent_readiness: 80.0
  band: exemplar
  in_catalog: true
  kin_score: 93.5
  mcp: *id055
  name: Telnyx
  slug: telnyx
  status: profiled
  tags: *id056
  url: /providers/telnyx/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id057
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id058
  url: /providers/twilio/
- agent_band: agent-ready
  agent_readiness: 40.0
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id059
  name: Vonage
  slug: vonage
  status: profiled
  tags: *id060
  url: /providers/vonage/
siblings:
- name: Akaunting
  rows: 7
  url: /applications/accounting-invoicing/akaunting/
- name: Crater
  rows: 2
  url: /applications/accounting-invoicing/crater/
- name: ERPNext
  rows: 3
  url: /applications/accounting-invoicing/erpnext/
- name: FreshBooks
  rows: 4
  url: /applications/accounting-invoicing/freshbooks/
- name: Invoice Ninja
  rows: 42
  url: /applications/accounting-invoicing/invoice-ninja/
- name: QuickBooks
  rows: 9
  url: /applications/accounting-invoicing/quickbooks/
- name: Xero
  rows: 8
  url: /applications/accounting-invoicing/xero/
- name: Zoho Invoice
  rows: 14
  url: /applications/accounting-invoicing/zoho-invoice/
sitemap: true
title: 'SolidInvoice: Accounting & Invoicing reference app'
---
