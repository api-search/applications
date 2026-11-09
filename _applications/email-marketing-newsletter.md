---
access: understanding
agent_layer:
- app: Klaviyo
  finding: Klaviyo lists its own "Klaviyo MCP Server" in its app marketplace
  source: https://marketplace.klaviyo.com/en-us/
  tier: declared
- app: Ghost
  finding: ghost/package.json depends on @x402/core, @x402/evm, @x402/hono -- HTTP 402 agent-payment protocol (protocol libs, not a vendor)
  source: https://raw.githubusercontent.com/TryGhost/Ghost/main/ghost/package.json
  tier: observed
apps:
- anchor: listmonk
  counts:
    declared: 6
    observed: 7
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/knadh/listmonk/master/go.mod
  - route: documentation
    url: https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
  - route: source code
    url: https://github.com/knadh/listmonk/tree/master/internal/bounce/webhooks
  - route: source code
    url: https://github.com/knadh/listmonk/tree/master/internal/media/providers
  - route: source code
    url: https://raw.githubusercontent.com/knadh/listmonk/master/internal/captcha/captcha.go
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: Amazon SES
    provider: amazon-ses
    says: ships the Amazon SES SDK or integration code
    source: https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/ses.go
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
    name: Azure Communication Services
    provider: microsoft-azure-communication-services
    says: ships the Azure Communication Services SDK or integration code
    source: https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/azure.go
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
    name: Forward Email (forwardemail.net)
    provider: forward-email
    says: ships the Forward Email (forwardemail.net) SDK or integration code
    source: https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/forwardemail.go
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
    name: hCaptcha
    provider: hcaptcha
    says: ships the hCaptcha SDK or integration code
    source: https://raw.githubusercontent.com/knadh/listmonk/master/internal/captcha/captcha.go
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
    name: Lettermint
    provider: lettermint
    says: ships the Lettermint SDK or integration code
    source: https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/lettermint.go
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
    name: Postmark
    provider: postmark
    says: ships the Postmark SDK or integration code
    source: https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/postmark.go
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
    name: SendGrid
    provider: sendgrid
    says: ships the SendGrid SDK or integration code
    source: https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/sendgrid.go
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
    name: Amazon Pinpoint (SMS)
    provider: amazon-pinpoint
    says: lists Amazon Pinpoint (SMS) as an integration
    source: https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Firebase Cloud Messaging
    provider: firebase
    says: lists Firebase Cloud Messaging as an integration
    source: https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
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
    name: MailerSend
    provider: mailersend
    says: lists MailerSend as an integration
    source: https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Novu
    provider: novu
    says: lists Novu as an integration
    source: https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
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
    name: Resend
    provider: resend
    says: lists Resend as an integration
    source: https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Verimor (SMS, Turkey)
    provider: verimor
    says: lists Verimor (SMS, Turkey) as an integration
    source: https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
    tier: declared
  kind: self-hosted
  name: listmonk
  page: /applications/email-marketing-newsletter/listmonk/
  slug: listmonk
  url: https://github.com/knadh/listmonk
- anchor: keila
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/pentacent/keila/main/mix.exs
  - route: source code
    url: https://github.com/pentacent/keila/tree/main/extra/keila_cloud/paddle
  - route: source code
    url: https://github.com/pentacent/keila/tree/main/lib/keila/mailings/sender_adapters
  - route: source code
    url: https://raw.githubusercontent.com/pentacent/keila/main/lib/keila_web/helpers/captcha/captcha.ex
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: Amazon SES
    provider: amazon-ses
    says: ships the Amazon SES SDK or integration code
    source: https://raw.githubusercontent.com/pentacent/keila/main/mix.exs
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
    name: Friendly Captcha
    provider: friendly-captcha
    says: ships the Friendly Captcha SDK or integration code
    source: https://raw.githubusercontent.com/pentacent/keila/main/lib/keila_web/helpers/captcha/captcha.ex
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
    name: hCaptcha
    provider: hcaptcha
    says: ships the hCaptcha SDK or integration code
    source: https://raw.githubusercontent.com/pentacent/keila/main/lib/keila_web/helpers/captcha/captcha.ex
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
    name: Mailgun
    provider: mailgun
    says: ships the Mailgun SDK or integration code
    source: https://raw.githubusercontent.com/pentacent/keila/main/lib/keila/mailings/sender_adapters/mailgun.ex
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: Paddle
    provider: paddle
    says: ships the Paddle SDK or integration code
    source: https://github.com/pentacent/keila/tree/main/extra/keila_cloud/paddle
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
    name: Postmark
    provider: postmark
    says: ships the Postmark SDK or integration code
    source: https://raw.githubusercontent.com/pentacent/keila/main/lib/keila/mailings/sender_adapters/postmark.ex
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
    name: SendGrid
    provider: sendgrid
    says: ships the SendGrid SDK or integration code
    source: https://raw.githubusercontent.com/pentacent/keila/main/lib/keila/mailings/sender_adapters/sendgrid.ex
    tier: observed
  kind: open-source-saas
  name: Keila
  page: /applications/email-marketing-newsletter/keila/
  slug: keila
  url: https://github.com/pentacent/keila
- anchor: ghost
  counts:
    declared: 12
    observed: 5
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/TryGhost/Ghost/main/ghost/package.json
  - route: integrations page
    url: https://ghost.org/integrations/
  - route: source code
    url: https://github.com/TryGhost/Ghost/blob/main/apps/admin-x-framework/src/api/tinybird.ts
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/TryGhost/Ghost/main/ghost/package.json
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
    name: Mailgun
    provider: mailgun
    says: ships the Mailgun SDK or integration code
    source: https://raw.githubusercontent.com/TryGhost/Ghost/main/ghost/package.json
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
    source: https://raw.githubusercontent.com/TryGhost/Ghost/main/ghost/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://raw.githubusercontent.com/TryGhost/Ghost/main/ghost/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: Tinybird
    provider: tinybird
    says: ships the Tinybird SDK or integration code
    source: https://github.com/TryGhost/Ghost/blob/main/apps/admin-x-framework/src/api/tinybird.ts
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Cloudinary
    provider: cloudinary
    says: lists Cloudinary as an integration
    source: https://ghost.org/integrations/
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
    name: Discord
    provider: discord
    says: lists Discord as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: GIPHY
    provider: giphy
    says: lists GIPHY as an integration
    source: https://ghost.org/integrations/
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
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: Patreon
    provider: patreon
    says: lists Patreon as an integration
    source: https://ghost.org/integrations/
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
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: Plausible Analytics
    provider: plausible
    says: lists Plausible Analytics as an integration
    source: https://ghost.org/integrations/
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
    source: https://ghost.org/integrations/
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
    name: Twilio Segment
    provider: segment
    says: lists Twilio Segment as an integration
    source: https://ghost.org/integrations/
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
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Unsplash
    provider: unsplash
    says: lists Unsplash as an integration
    source: https://ghost.org/integrations/
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
    source: https://ghost.org/integrations/
    tier: declared
  kind: open-source-saas
  name: Ghost
  page: /applications/email-marketing-newsletter/ghost/
  slug: ghost
  url: https://github.com/TryGhost/Ghost
- anchor: mautic
  counts:
    declared: 5
    observed: 20
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/mautic/mautic/7.x/app/composer.json
  - route: dependency manifest
    url: https://raw.githubusercontent.com/mautic/mautic/7.x/composer.json
  - route: documentation
    url: https://docs.mautic.org/en/7.0/channels/emails.html
  - route: source code
    url: https://github.com/mautic/mautic/tree/7.x/plugins
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCloudStorageBundle/Integration
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
    source: https://github.com/mautic/mautic/tree/7.x/plugins
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
    name: ConnectWise
    provider: connectwise
    says: ships the ConnectWise SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
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
    name: Constant Contact
    provider: constant-contact
    says: ships the Constant Contact SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticEmailMarketingBundle/Integration
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
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
    name: Foursquare
    provider: foursquare
    says: ships the Foursquare SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
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
    name: FullContact
    provider: fullcontact
    says: ships the FullContact SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins
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
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
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
    name: iContact
    provider: icontact
    says: ships the iContact SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticEmailMarketingBundle/Integration
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
    name: Instagram
    provider: instagram
    says: ships the Instagram SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
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
    name: IP2Location
    provider: ip2location
    says: ships the IP2Location SDK or integration code
    source: https://raw.githubusercontent.com/mautic/mautic/7.x/app/composer.json
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
    name: MaxMind
    provider: maxmind
    says: ships the MaxMind SDK or integration code
    source: https://raw.githubusercontent.com/mautic/mautic/7.x/app/composer.json
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
    name: Microsoft Dynamics 365
    provider: microsoft-dynamics-365
    says: ships the Microsoft Dynamics 365 SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
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
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
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
    name: SugarCRM
    provider: sugarcrm
    says: ships the SugarCRM SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
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
    source: https://raw.githubusercontent.com/mautic/mautic/7.x/app/composer.json
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
    name: Vtiger
    provider: vtiger
    says: ships the Vtiger SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
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
    name: X (Twitter)
    provider: x
    says: ships the X (Twitter) SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
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
    source: https://github.com/mautic/mautic/tree/7.x/plugins
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
    provider: zoho
    says: ships the Zoho CRM SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
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
    name: Amazon SES
    provider: amazon-ses
    says: lists Amazon SES as an integration
    source: https://docs.mautic.org/en/7.0/channels/emails.html
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
    name: Elastic Email
    provider: elastic-email
    says: lists Elastic Email as an integration
    source: https://docs.mautic.org/en/7.0/channels/emails.html
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
    name: Mailjet
    provider: mailjet
    says: lists Mailjet as an integration
    source: https://docs.mautic.org/en/7.0/channels/emails.html
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
    name: SendGrid
    provider: sendgrid
    says: lists SendGrid as an integration
    source: https://docs.mautic.org/en/7.0/channels/emails.html
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
    name: SparkPost
    provider: sparkpost
    says: lists SparkPost as an integration
    source: https://docs.mautic.org/en/7.0/channels/emails.html
    tier: declared
  kind: self-hosted
  name: Mautic
  page: /applications/email-marketing-newsletter/mautic/
  slug: mautic
  url: https://github.com/mautic/mautic
- anchor: mailchimp
  counts:
    declared: 12
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
  - route: integrations page
    url: https://mailchimp.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Branch (branch.io)
    provider: branch-io
    says: ships the Branch (branch.io) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
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
    name: Firebase (Crashlytics + Analytics)
    provider: firebase
    says: ships the Firebase (Crashlytics + Analytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Optimizely
    provider: optimizely
    says: ships the Optimizely SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430.50.20
      key: BC-430.50.20
      name: Customer Survey Management
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Qualtrics
    provider: qualtrics
    says: ships the Qualtrics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
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
    name: Twilio Segment
    provider: segment
    says: ships the Twilio Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: common
    name: Canva
    provider: canva
    says: lists Canva as an integration
    source: https://mailchimp.com/integrations/
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
    name: Facebook
    provider: facebook
    says: lists Facebook as an integration
    source: https://mailchimp.com/integrations/
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
    name: LinkedIn Lead Gen Forms
    provider: linkedin
    says: lists LinkedIn Lead Gen Forms as an integration
    source: https://mailchimp.com/integrations/
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
    source: https://mailchimp.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320.10
      key: sales-transaction-management
      name: Sales Transaction Management
      url: /capabilities/sales-transaction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Shopify
    provider: shopify
    says: lists Shopify as an integration
    source: https://mailchimp.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320.10
      key: sales-transaction-management
      name: Sales Transaction Management
      url: /capabilities/sales-transaction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Square
    provider: square
    says: lists Square as an integration
    source: https://mailchimp.com/integrations/
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
    source: https://mailchimp.com/integrations/
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
    source: https://mailchimp.com/integrations/
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
    name: Wix
    provider: wix
    says: lists Wix as an integration
    source: https://mailchimp.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320.10
      key: sales-transaction-management
      name: Sales Transaction Management
      url: /capabilities/sales-transaction-management/
      via_parent: null
    credit: null
    layer: domain
    name: WooCommerce
    provider: woocommerce
    says: lists WooCommerce as an integration
    source: https://mailchimp.com/integrations/
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
    name: WordPress
    provider: wordpress
    says: lists WordPress as an integration
    source: https://mailchimp.com/integrations/
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
    source: https://mailchimp.com/integrations/
    tier: declared
  kind: commercial
  name: Mailchimp
  page: /applications/email-marketing-newsletter/mailchimp/
  slug: mailchimp
  url: https://mailchimp.com/
- anchor: klaviyo
  counts:
    declared: 15
    observed: 0
  evidence:
  - route: integrations page
    url: https://marketplace.klaviyo.com/en-us/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2320.10
      key: sales-transaction-management
      name: Sales Transaction Management
      url: /capabilities/sales-transaction-management/
      via_parent: null
    credit: null
    layer: domain
    name: BigCommerce
    provider: bigcommerce
    says: lists BigCommerce as an integration
    source: https://marketplace.klaviyo.com/en-us/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: common
    name: Canva
    provider: canva
    says: lists Canva as an integration
    source: https://marketplace.klaviyo.com/en-us/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.30
      key: AE-150.10.30
      name: Email Deliverability & Verification
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: GlockApps
    provider: glockapps-com
    says: lists GlockApps as an integration
    source: https://marketplace.klaviyo.com/en-us/
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
    name: Google Ads
    provider: google-ads
    says: lists Google Ads as an integration
    source: https://marketplace.klaviyo.com/en-us/
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
    name: Gorgias
    provider: gorgias
    says: lists Gorgias as an integration
    source: https://marketplace.klaviyo.com/en-us/
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
    name: Judge.me
    provider: judge-me
    says: lists Judge.me as an integration
    source: https://marketplace.klaviyo.com/en-us/
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
    name: Meta Ads
    provider: facebook
    says: lists Meta Ads as an integration
    source: https://marketplace.klaviyo.com/en-us/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-929
      key: AE-929
      name: Multi-Carrier Shipping Platforms
      url: /capabilities/logistics-operations-management/
      via_parent: Logistics Operations Management
    credit: null
    layer: domain
    name: ShipStation
    provider: shipstation
    says: lists ShipStation as an integration
    source: https://marketplace.klaviyo.com/en-us/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320.10
      key: sales-transaction-management
      name: Sales Transaction Management
      url: /capabilities/sales-transaction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Shopify
    provider: shopify
    says: lists Shopify as an integration
    source: https://marketplace.klaviyo.com/en-us/
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
    source: https://marketplace.klaviyo.com/en-us/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4030.50
      key: promotion-discount-management
      name: Promotion & Discount Management
      url: /capabilities/promotion-discount-management/
      via_parent: null
    credit: null
    layer: domain
    name: Talon.One
    provider: talon-one
    says: lists Talon.One as an integration
    source: https://marketplace.klaviyo.com/en-us/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: Triple Whale
    provider: triple-whale
    says: lists Triple Whale as an integration
    source: https://marketplace.klaviyo.com/en-us/
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
    name: Wix
    provider: wix
    says: lists Wix as an integration
    source: https://marketplace.klaviyo.com/en-us/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320.10
      key: sales-transaction-management
      name: Sales Transaction Management
      url: /capabilities/sales-transaction-management/
      via_parent: null
    credit: null
    layer: domain
    name: WooCommerce
    provider: woocommerce
    says: lists WooCommerce as an integration
    source: https://marketplace.klaviyo.com/en-us/
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
    source: https://marketplace.klaviyo.com/en-us/
    tier: declared
  kind: commercial
  name: Klaviyo
  page: /applications/email-marketing-newsletter/klaviyo/
  slug: klaviyo
  url: https://www.klaviyo.com/
- anchor: substack
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.substack.app/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.substack.app/latest/
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
    name: Facebook (Analytics, Login, Share)
    provider: facebook
    says: ships the Facebook (Analytics, Login, Share) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.substack.app/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase Analytics
    provider: firebase
    says: ships the Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.substack.app/latest/
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
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.substack.app/latest/
    tier: observed
  kind: commercial
  name: Substack
  page: /applications/email-marketing-newsletter/substack/
  slug: substack
  url: https://substack.com/
- anchor: beehiiv
  counts:
    declared: 22
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.beehiiv.com/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-400.70
      key: content-marketing-management
      name: Content Marketing Management
      url: /capabilities/content-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClickFunnels
    provider: clickfunnels
    says: lists ClickFunnels as an integration
    source: https://www.beehiiv.com/integrations
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
    name: Discord
    provider: discord
    says: lists Discord as an integration
    source: https://www.beehiiv.com/integrations
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
    name: Facebook Lead Ads
    provider: facebook
    says: lists Facebook Lead Ads as an integration
    source: https://www.beehiiv.com/integrations
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
    name: Formstack
    provider: formstack
    says: lists Formstack as an integration
    source: https://www.beehiiv.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gumroad
    provider: gumroad
    says: lists Gumroad as an integration
    source: https://www.beehiiv.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Linktree
    provider: linktree
    says: lists Linktree as an integration
    source: https://www.beehiiv.com/integrations
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
    source: https://www.beehiiv.com/integrations
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
    name: ManyChat
    provider: manychat
    says: lists ManyChat as an integration
    source: https://www.beehiiv.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: Memberful
    provider: memberful
    says: lists Memberful as an integration
    source: https://www.beehiiv.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: MemberPress
    provider: memberpress
    says: lists MemberPress as an integration
    source: https://www.beehiiv.com/integrations
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
    name: OptinMonster
    provider: optinmonster
    says: lists OptinMonster as an integration
    source: https://www.beehiiv.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: Patreon
    provider: patreon
    says: lists Patreon as an integration
    source: https://www.beehiiv.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: Recurly
    provider: recurly
    says: lists Recurly as an integration
    source: https://www.beehiiv.com/integrations
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
    source: https://www.beehiiv.com/integrations
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
    source: https://www.beehiiv.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://www.beehiiv.com/integrations
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
    name: Thinkific
    provider: thinkific
    says: lists Thinkific as an integration
    source: https://www.beehiiv.com/integrations
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
    source: https://www.beehiiv.com/integrations
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
    name: Webflow
    provider: webflow
    says: lists Webflow as an integration
    source: https://www.beehiiv.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320.10
      key: sales-transaction-management
      name: Sales Transaction Management
      url: /capabilities/sales-transaction-management/
      via_parent: null
    credit: null
    layer: domain
    name: WooCommerce
    provider: woocommerce
    says: lists WooCommerce as an integration
    source: https://www.beehiiv.com/integrations
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
    name: WordPress
    provider: wordpress
    says: lists WordPress as an integration
    source: https://www.beehiiv.com/integrations
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
    source: https://www.beehiiv.com/integrations
    tier: declared
  kind: commercial
  name: beehiiv
  page: /applications/email-marketing-newsletter/beehiiv/
  slug: beehiiv
  url: https://www.beehiiv.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: email-marketing-newsletter
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Communication - Email - Mailing Lists and Newsletters
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#communication---email---mailing-lists-and-newsletters
- category: Email Newsletters
  store: zapier
  url: https://zapier.com/apps
name: Email Marketing & Newsletters
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: domain
  why: sending/bounce backend (SES, SendGrid, Postmark, Mailgun ...) -- no BC capability for email delivery; channel-orchestration-management is the nearest
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: common
  why: IP -> location on opens/clicks; no BC capability
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: common
  why: web/product analytics on opens, clicks, site traffic
- capability:
    attribution: Turbo EA
    id: BC-2330.10
    key: channel-orchestration-management
    name: Channel Orchestration Management
    url: /capabilities/channel-orchestration-management/
    via_parent: null
  fit: nearest
  layer: common
  why: SMS / push / multi-channel messengers beside email
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  fit: exact
  layer: domain
  why: website / CMS / course platform the newsletter is embedded in
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: domain
  why: CDP / contact enrichment
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  fit: exact
  layer: domain
  why: forms, surveys, reviews feeding lists
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: two-way contact sync with CRMs
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: helpdesk sync of email replies
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  fit: exact
  layer: common
  why: design tool import of email creative
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: audience sync with ad networks, social, attribution, other email platforms
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: CAPTCHA on public signup forms (list-bombing protection)
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: nearest
  layer: common
  why: community/chat notifications (Slack, Discord)
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  fit: exact
  layer: common
  why: image/file storage and media libraries for campaign content
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring / crash reporting
- capability:
    attribution: Turbo EA
    id: BC-520.40
    key: order-fulfilment-management
    name: Order Fulfilment Management
    url: /capabilities/order-fulfilment-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: shipping events as campaign triggers
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: payment acceptance
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: no-code automation glue (Zapier/Make) -- no BC capability for iPaaS
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  fit: exact
  layer: common
  why: A/B experimentation in the app
- capability:
    attribution: Turbo EA
    id: BC-4030.50
    key: promotion-discount-management
    name: Promotion & Discount Management
    url: /capabilities/promotion-discount-management/
    via_parent: null
  fit: exact
  layer: domain
  why: coupon/promotion engines
- capability:
    attribution: Turbo EA
    id: BC-2320.10
    key: sales-transaction-management
    name: Sales Transaction Management
    url: /capabilities/sales-transaction-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: e-commerce platform order/customer sync drives triggered flows
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  fit: exact
  layer: domain
  why: paid newsletters / SaaS billing of the tool itself
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - Keila
      - Mautic
      - listmonk
      band: exemplar
      in_catalog: true
      kin_score: 87.3
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://docs.mautic.org/en/7.0/channels/emails.html
      - https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/sendgrid.go
      - https://raw.githubusercontent.com/pentacent/keila/main/lib/keila/mailings/sender_adapters/sendgrid.ex
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - Keila
      - Mautic
      - listmonk
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        status: none
      name: Amazon SES
      slug: amazon-ses
      sources:
      - https://docs.mautic.org/en/7.0/channels/emails.html
      - https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/ses.go
      - https://raw.githubusercontent.com/pentacent/keila/main/mix.exs
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
    - agent_band: agent-ready
      agent_readiness: 41.7
      apps:
      - Keila
      - listmonk
      band: exemplar
      in_catalog: true
      kin_score: 71.3
      mcp:
        source: https://github.com/ActiveCampaign/postmark-mcp
        status: verified
      name: Postmark
      slug: postmark
      sources:
      - https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/postmark.go
      - https://raw.githubusercontent.com/pentacent/keila/main/lib/keila/mailings/sender_adapters/postmark.ex
      status: profiled
      tags:
      - Deliverability
      - Email
      - Messaging
      - Transactional Email
      tier: observed
      url: /providers/postmark/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Ghost
      - Keila
      band: thin
      in_catalog: true
      kin_score: 32.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://raw.githubusercontent.com/TryGhost/Ghost/main/ghost/package.json
      - https://raw.githubusercontent.com/pentacent/keila/main/lib/keila/mailings/sender_adapters/mailgun.ex
      status: profiled
      tags:
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailgun/
    - agent_band: agent-ready
      agent_readiness: 43.4
      apps:
      - listmonk
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        status: none
      name: Azure Communication Services
      slug: microsoft-azure-communication-services
      sources:
      - https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/azure.go
      status: profiled
      tags:
      - CPaaS
      - Calling
      - Chat
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-communication-services/
    - agent_band: agent-ready
      agent_readiness: 33.2
      apps:
      - listmonk
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp:
        source: https://github.com/forwardemail/mcp-server
        status: verified
      name: Forward Email (forwardemail.net)
      slug: forward-email
      sources:
      - https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/forwardemail.go
      status: profiled
      tags:
      - Email Forwarding
      - Email Hosting
      - Open Source
      - Secure Email
      tier: observed
      url: /providers/forward-email/
    - agent_band: agent-aware
      agent_readiness: 23.0
      apps:
      - listmonk
      band: developing
      in_catalog: true
      kin_score: 40.4
      mcp:
        source: https://lettermint.co/docs/mcp
        status: verified
      name: Lettermint
      slug: lettermint
      sources:
      - https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/lettermint.go
      status: profiled
      tags:
      - Company
      - Email
      - European
      - Transactional
      tier: observed
      url: /providers/lettermint/
    - agent_band: agent-ready
      agent_readiness: 56.3
      apps:
      - listmonk
      band: strong
      in_catalog: true
      kin_score: 59.5
      mcp:
        source: https://developers.mailersend.com/mcp-server.html
        status: verified
      name: MailerSend
      slug: mailersend
      sources:
      - https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
      status: profiled
      tags:
      - Email
      - Marketing
      - SMTP
      - Transactional Email
      tier: declared
      url: /providers/mailersend/
    - agent_band: agent-ready
      agent_readiness: 49.4
      apps:
      - listmonk
      band: strong
      in_catalog: true
      kin_score: 58.9
      mcp:
        source: https://resend.com/docs/mcp-server
        status: verified
      name: Resend
      slug: resend
      sources:
      - https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
      status: profiled
      tags:
      - Developer Tools
      - Email
      - Marketing Email
      - Transactional Email
      tier: declared
      url: /providers/resend/
    - agent_band: agent-aware
      agent_readiness: 23.4
      apps:
      - Mautic
      band: developing
      in_catalog: true
      kin_score: 50.1
      mcp:
        source: https://github.com/mailgun/mailjet-mcp-server
        status: verified
      name: Mailjet
      slug: mailjet
      sources:
      - https://docs.mautic.org/en/7.0/channels/emails.html
      status: profiled
      tags:
      - Email
      - Email Delivery
      - Marketing Email
      - SMTP
      tier: declared
      url: /providers/mailjet/
    - agent_band: agent-ready
      agent_readiness: 41.1
      apps:
      - Mautic
      band: developing
      in_catalog: true
      kin_score: 39.5
      mcp:
        source: https://github.com/ElasticEmail/elasticemail-mcp-server
        status: verified
      name: Elastic Email
      slug: elastic-email
      sources:
      - https://docs.mautic.org/en/7.0/channels/emails.html
      status: profiled
      tags:
      - Company
      - Email
      - Marketing
      - Software-as-a-Service
      tier: declared
      url: /providers/elastic-email/
    - agent_band: agent-aware
      agent_readiness: 26.1
      apps:
      - Mautic
      band: thin
      in_catalog: true
      kin_score: 37.9
      mcp:
        status: none
      name: SparkPost
      slug: sparkpost
      sources:
      - https://docs.mautic.org/en/7.0/channels/emails.html
      status: profiled
      tags:
      - Email
      - Email Delivery
      - Marketing Email
      - Transactional Email
      tier: declared
      url: /providers/sparkpost/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Klaviyo
      - Mailchimp
      - Mautic
      - Substack
      - beehiiv
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
      - https://mailchimp.com/integrations/
      - https://marketplace.klaviyo.com/en-us/
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-native
      agent_readiness: 61.2
      apps:
      - Mautic
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: X (Twitter)
      slug: x
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: observed
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - Substack
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.substack.app/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
    - agent_band: agent-ready
      agent_readiness: 32.1
      apps:
      - Mautic
      band: exemplar
      in_catalog: true
      kin_score: 70.9
      mcp:
        status: none
      name: Constant Contact
      slug: constant-contact
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticEmailMarketingBundle/Integration
      status: profiled
      tags:
      - Campaigns
      - Contacts
      - Email Marketing
      - Event
      tier: observed
      url: /providers/constant-contact/
    - agent_band: agent-ready
      agent_readiness: 38.9
      apps:
      - Mautic
      band: exemplar
      in_catalog: true
      kin_score: 69.0
      mcp:
        status: none
      name: Instagram
      slug: instagram
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
      status: profiled
      tags:
      - Instagram
      - Meta
      - Photos
      - Social Media
      tier: observed
      url: /providers/instagram/
    - agent_band: agent-aware
      agent_readiness: 26.1
      apps:
      - Mautic
      band: strong
      in_catalog: true
      kin_score: 55.7
      mcp:
        status: none
      name: iContact
      slug: icontact
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticEmailMarketingBundle/Integration
      status: profiled
      tags:
      - Campaigns
      - Contacts
      - Email Marketing
      - Marketing Automation
      tier: observed
      url: /providers/icontact/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Mautic
      band: developing
      in_catalog: true
      kin_score: 47.7
      mcp:
        source: https://github.com/foursquare/foursquare-places-mcp
        status: verified
      name: Foursquare
      slug: foursquare
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
      status: profiled
      tags:
      - Geocoding
      - Location
      - Places
      - Restaurant
      tier: observed
      url: /providers/foursquare/
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Mailchimp
      band: emerging
      in_catalog: true
      kin_score: 23.0
      mcp:
        status: none
      name: Branch (branch.io)
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
    - agent_band: agent-ready
      agent_readiness: 47.4
      apps:
      - Mailchimp
      band: exemplar
      in_catalog: true
      kin_score: 76.4
      mcp:
        status: none
      name: LinkedIn Lead Gen Forms
      slug: linkedin
      sources:
      - https://mailchimp.com/integrations/
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: declared
      url: /providers/linkedin/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - Klaviyo
      band: exemplar
      in_catalog: true
      kin_score: 73.1
      mcp:
        source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
        status: verified
      name: Google Ads
      slug: google-ads
      sources:
      - https://marketplace.klaviyo.com/en-us/
      status: profiled
      tags:
      - Advertising
      - Campaign Management
      - Digital Advertising
      - Google
      tier: declared
      url: /providers/google-ads/
    - agent_band: agent-ready
      agent_readiness: 33.8
      apps:
      - beehiiv
      band: strong
      in_catalog: true
      kin_score: 56.5
      mcp:
        status: none
      name: ManyChat
      slug: manychat
      sources:
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - Chat Marketing
      - Conversational Commerce
      - Marketing Automation
      - Messenger Marketing
      tier: declared
      url: /providers/manychat/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.7
      apps:
      - Mailchimp
      - Mautic
      - beehiiv
      band: exemplar
      in_catalog: true
      kin_score: 90.6
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
      - https://mailchimp.com/integrations/
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: observed
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 52.7
      apps:
      - Ghost
      - Mautic
      band: exemplar
      in_catalog: true
      kin_score: 94.6
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://ghost.org/integrations/
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: observed
      url: /providers/hubspot/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Mautic
      band: exemplar
      in_catalog: true
      kin_score: 67.6
      mcp:
        status: none
      name: SugarCRM
      slug: sugarcrm
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
      status: profiled
      tags:
      - CRM
      - Company
      - Sales
      - Software-as-a-Service
      tier: observed
      url: /providers/sugarcrm/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Mautic
      band: strong
      in_catalog: true
      kin_score: 63.9
      mcp:
        source: https://github.com/microsoft/Dataverse-MCP
        status: verified
      name: Microsoft Dynamics 365
      slug: microsoft-dynamics-365
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
      status: profiled
      tags:
      - Business Applications
      - CRM
      - Cloud
      - Enterprise
      tier: observed
      url: /providers/microsoft-dynamics-365/
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Mautic
      band: strong
      in_catalog: true
      kin_score: 63.5
      mcp:
        source: https://www.zoho.com/mcp/
        status: verified
      name: Zoho CRM
      slug: zoho
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
      status: profiled
      tags:
      - Analytics
      - CRM
      - Collaboration
      - Customer Service
      tier: observed
      url: /providers/zoho/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - Mautic
      band: emerging
      in_catalog: true
      kin_score: 25.7
      mcp:
        status: none
      name: Vtiger
      slug: vtiger
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
      status: profiled
      tags:
      - Artificial Intelligence
      - CRM
      - Company
      - Sales
      tier: observed
      url: /providers/vtiger/
    - agent_band: agent-aware
      agent_readiness: 20.8
      apps:
      - Mautic
      band: emerging
      in_catalog: true
      kin_score: 24.0
      mcp:
        source: https://www.connectwise.com/blog/what-mcp-could-mean-for-msps
        status: documented
      name: ConnectWise
      slug: connectwise
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
      status: profiled
      tags:
      - IT Management
      - MSP
      - PSA
      - RMM
      tier: observed
      url: /providers/connectwise/
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - Ghost
      - beehiiv
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp: &id003
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/TryGhost/Ghost/main/ghost/package.json
      - https://www.beehiiv.com/integrations
      status: profiled
      tags: &id004
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Ghost
      - beehiiv
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp:
        status: none
      name: Patreon
      slug: patreon
      sources:
      - https://ghost.org/integrations/
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - Content
      - Creator Economy
      - Membership
      - Subscription
      tier: declared
      url: /providers/patreon/
    - agent_band: agent-ready
      agent_readiness: 47.5
      apps:
      - Keila
      band: thin
      in_catalog: true
      kin_score: 28.7
      mcp:
        source: https://github.com/PaddleHQ/paddle-mcp-server
        status: verified
      name: Paddle
      slug: paddle
      sources:
      - https://github.com/pentacent/keila/tree/main/extra/keila_cloud/paddle
      status: profiled
      tags:
      - Billing
      - Merchant of Record
      - Payments
      - Subscription
      tier: observed
      url: /providers/paddle/
    - agent_band: agent-native
      agent_readiness: 54.3
      apps:
      - beehiiv
      band: exemplar
      in_catalog: true
      kin_score: 78.8
      mcp:
        status: none
      name: Recurly
      slug: recurly
      sources:
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - Billing
      - Payments
      - Recurring Revenue
      - Subscription
      tier: declared
      url: /providers/recurly/
    - agent_band: agent-ready
      agent_readiness: 37.7
      apps:
      - beehiiv
      band: developing
      in_catalog: true
      kin_score: 49.7
      mcp:
        status: none
      name: MemberPress
      slug: memberpress
      sources:
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - Company
      - Membership
      - Subscription
      - WordPress
      tier: declared
      url: /providers/memberpress/
    - agent_band: agent-aware
      agent_readiness: 16.8
      apps:
      - beehiiv
      band: emerging
      in_catalog: true
      kin_score: 23.6
      mcp:
        status: none
      name: Gumroad
      slug: gumroad
      sources:
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - Creator Economy
      - Digital Commerce
      - Digital Products
      - Membership
      tier: declared
      url: /providers/gumroad/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - beehiiv
      band: emerging
      in_catalog: true
      kin_score: 12.9
      mcp:
        status: none
      name: Memberful
      slug: memberful
      sources:
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - Creators
      - Membership
      - Payments
      - Subscription
      tier: declared
      url: /providers/memberful/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 49.5
      apps:
      - Klaviyo
      - Mailchimp
      band: exemplar
      in_catalog: true
      kin_score: 69.9
      mcp:
        status: none
      name: Squarespace
      slug: squarespace
      sources:
      - https://mailchimp.com/integrations/
      - https://marketplace.klaviyo.com/en-us/
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Marketing
      - Payments
      tier: declared
      url: /providers/squarespace/
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - Mailchimp
      - beehiiv
      band: developing
      in_catalog: true
      kin_score: 46.0
      mcp:
        source: https://github.com/WordPress/mcp-adapter
        status: verified
      name: WordPress
      slug: wordpress
      sources:
      - https://mailchimp.com/integrations/
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - CMS
      - Content Management
      - Open Source
      - WordPress
      tier: declared
      url: /providers/wordpress/
    - agent_band: agent-ready
      agent_readiness: 48.2
      apps:
      - Klaviyo
      - Mailchimp
      band: thin
      in_catalog: true
      kin_score: 35.6
      mcp:
        source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
        status: verified
      name: Wix
      slug: wix
      sources:
      - https://mailchimp.com/integrations/
      - https://marketplace.klaviyo.com/en-us/
      status: profiled
      tags:
      - CMS
      - E-Commerce
      - Headless
      - Website Builder
      tier: declared
      url: /providers/wix/
    - agent_band: agent-ready
      agent_readiness: 62.5
      apps:
      - beehiiv
      band: strong
      in_catalog: true
      kin_score: 60.7
      mcp:
        source: https://developers.webflow.com/mcp/reference/overview
        status: verified
      name: Webflow
      slug: webflow
      sources:
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - CMS
      - E-Commerce
      - No-Code
      - Web Development
      tier: declared
      url: /providers/webflow/
  - capability:
      attribution: Turbo EA
      id: BC-2320.10
      key: sales-transaction-management
      name: Sales Transaction Management
      url: /capabilities/sales-transaction-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.4
      apps:
      - Klaviyo
      - Mailchimp
      - beehiiv
      band: developing
      in_catalog: true
      kin_score: 50.4
      mcp:
        source: https://developer.woocommerce.com/docs/features/mcp/
        status: verified
      name: WooCommerce
      slug: woocommerce
      sources:
      - https://mailchimp.com/integrations/
      - https://marketplace.klaviyo.com/en-us/
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Open Source
      - Order
      - WooCommerce
      tier: declared
      url: /providers/woocommerce/
    - agent_band: agent-ready
      agent_readiness: 52.5
      apps:
      - Klaviyo
      - Mailchimp
      band: exemplar
      in_catalog: true
      kin_score: 84.6
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify
      slug: shopify
      sources:
      - https://mailchimp.com/integrations/
      - https://marketplace.klaviyo.com/en-us/
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: declared
      url: /providers/shopify/
    - agent_band: agent-native
      agent_readiness: 62.8
      apps:
      - Mailchimp
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://developer.squareup.com/docs/mcp
        status: verified
      name: Square
      slug: square
      sources:
      - https://mailchimp.com/integrations/
      status: profiled
      tags:
      - Booking
      - Location
      - Restaurant
      - Square
      tier: declared
      url: /providers/square/
    - agent_band: agent-ready
      agent_readiness: 60.5
      apps:
      - Klaviyo
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
        status: verified
      name: BigCommerce
      slug: bigcommerce
      sources:
      - https://marketplace.klaviyo.com/en-us/
      status: profiled
      tags:
      - Catalog
      - E-Commerce
      - Order
      - Retail
      tier: declared
      url: /providers/bigcommerce/
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Ghost
      - Mailchimp
      band: developing
      in_catalog: true
      kin_score: 43.8
      mcp:
        status: none
      name: Twilio Segment
      slug: segment
      sources:
      - https://ghost.org/integrations/
      - https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - Mautic
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: FullContact
      slug: fullcontact
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins
      status: profiled
      tags:
      - Customer Data
      - Data Enrichment
      - Identity Resolution
      - Person API
      tier: observed
      url: /providers/fullcontact/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Mautic
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp:
        status: none
      name: Clearbit
      slug: clearbit
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins
      status: profiled
      tags:
      - B2B
      - Data Enrichment
      - Reveal
      - Sales Intelligence
      tier: observed
      url: /providers/clearbit/
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.5
      apps:
      - Ghost
      - beehiiv
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp:
        source: https://www.typeform.com/developers/mcp
        status: verified
      name: Typeform
      slug: typeform
      sources:
      - https://ghost.org/integrations/
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - Forms
      - Lead Capture
      - Software-as-a-Service
      - Surveys
      tier: declared
      url: /providers/typeform/
    - agent_band: agent-ready
      agent_readiness: 33.9
      apps:
      - beehiiv
      band: emerging
      in_catalog: true
      kin_score: 24.4
      mcp:
        status: none
      name: Formstack
      slug: formstack
      sources:
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - Documents
      - E-Signature
      - Forms
      - Workflow Automation
      tier: declared
      url: /providers/formstack/
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - beehiiv
      band: developing
      in_catalog: true
      kin_score: 53.8
      mcp:
        status: none
      name: OptinMonster
      slug: optinmonster
      sources:
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - Company
      - Conversion Optimization
      - Lead Generation
      - Marketing
      tier: declared
      url: /providers/optinmonster/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Klaviyo
      band: thin
      in_catalog: true
      kin_score: 27.2
      mcp:
        status: none
      name: Judge.me
      slug: judge-me
      sources:
      - https://marketplace.klaviyo.com/en-us/
      status: profiled
      tags:
      - E-Commerce
      - Ratings
      - Reviews
      - Shopify
      tier: declared
      url: /providers/judge-me/
  - capability:
      attribution: Turbo EA
      id: BC-400.70
      key: content-marketing-management
      name: Content Marketing Management
      url: /capabilities/content-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - beehiiv
      band: exemplar
      in_catalog: true
      kin_score: 73.8
      mcp:
        status: none
      name: ClickFunnels
      slug: clickfunnels
      sources:
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Landing Pages
      - Marketing
      - Sales Funnels
      tier: declared
      url: /providers/clickfunnels/
  - capability:
      attribution: Turbo EA
      id: BC-430.50.20
      key: BC-430.50.20
      name: Customer Survey Management
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.0
      apps:
      - Mailchimp
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Qualtrics
      slug: qualtrics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
      status: profiled
      tags:
      - Customer Experience
      - Employee Experience
      - Experience Management
      - Surveys
      tier: observed
      url: /providers/qualtrics/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.30
      key: AE-150.10.30
      name: Email Deliverability & Verification
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Klaviyo
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: none
      name: GlockApps
      slug: glockapps-com
      sources:
      - https://marketplace.klaviyo.com/en-us/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.7
      apps:
      - beehiiv
      band: developing
      in_catalog: true
      kin_score: 47.8
      mcp:
        status: none
      name: Linktree
      slug: linktree
      sources:
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - Company
      - Creator Economy
      - Link in Bio
      - Media
      tier: declared
      url: /providers/linktree/
  - capability:
      attribution: API Evangelist extension
      id: AE-929
      key: AE-929
      name: Multi-Carrier Shipping Platforms
      url: /capabilities/logistics-operations-management/
      via_parent: Logistics Operations Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Klaviyo
      band: strong
      in_catalog: true
      kin_score: 56.7
      mcp:
        status: none
      name: ShipStation
      slug: shipstation
      sources:
      - https://marketplace.klaviyo.com/en-us/
      status: profiled
      tags:
      - E-Commerce
      - Labels
      - Logistics
      - ShipStation
      tier: declared
      url: /providers/shipstation/
  - capability:
      attribution: API Evangelist extension
      id: AE-220.10
      key: AE-220.10
      name: Online Courses
      url: /capabilities/online-courses/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.2
      apps:
      - beehiiv
      band: developing
      in_catalog: true
      kin_score: 49.5
      mcp:
        status: none
      name: Thinkific
      slug: thinkific
      sources:
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - Course Creation
      - E-Learning
      - LMS
      - Online Courses
      tier: declared
      url: /providers/thinkific/
  - capability:
      attribution: Turbo EA
      id: BC-4030.50
      key: promotion-discount-management
      name: Promotion & Discount Management
      url: /capabilities/promotion-discount-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 49.8
      apps:
      - Klaviyo
      band: exemplar
      in_catalog: true
      kin_score: 75.5
      mcp:
        source: https://docs.talon.one/docs/dev/mcp
        status: verified
      name: Talon.One
      slug: talon-one
      sources:
      - https://marketplace.klaviyo.com/en-us/
      status: profiled
      tags:
      - Coupons
      - Incentives
      - Loyalty
      - Promotions
      tier: declared
      url: /providers/talon-one/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.2
      apps:
      - Ghost
      - Klaviyo
      - Mailchimp
      - Mautic
      - beehiiv
      band: exemplar
      in_catalog: true
      kin_score: 72.0
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://ghost.org/integrations/
      - https://github.com/mautic/mautic/tree/7.x/plugins
      - https://mailchimp.com/integrations/
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: observed
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 43.9
      apps:
      - beehiiv
      band: developing
      in_catalog: true
      kin_score: 43.5
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Ghost
      - Mautic
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticCloudStorageBundle/Integration
      - https://raw.githubusercontent.com/TryGhost/Ghost/main/ghost/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Ghost
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        status: none
      name: GIPHY
      slug: giphy
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - GIFs
      - Media
      - Photography
      - Stickers
      tier: declared
      url: /providers/giphy/
    - agent_band: agent-ready
      agent_readiness: 45.0
      apps:
      - Ghost
      band: developing
      in_catalog: true
      kin_score: 52.4
      mcp:
        source: https://cloudinary.com/documentation/cloudinary_llm_mcp
        status: verified
      name: Cloudinary
      slug: cloudinary
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Asset Management
      - Digital Asset Management
      - Image Processing
      - Image Transformation
      tier: declared
      url: /providers/cloudinary/
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Ghost
      band: developing
      in_catalog: true
      kin_score: 40.2
      mcp:
        status: none
      name: Unsplash
      slug: unsplash
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Image
      - Photography
      - Photos
      - Stock Photos
      tier: declared
      url: /providers/unsplash/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Substack
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase Analytics
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.substack.app/latest/
      status: profiled
      tags: &id002
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-ready
      agent_readiness: 30.2
      apps:
      - Ghost
      band: developing
      in_catalog: true
      kin_score: 47.8
      mcp:
        source: https://www.tinybird.co/docs/forward/analytics-agents/mcp
        status: verified
      name: Tinybird
      slug: tinybird
      sources:
      - https://github.com/TryGhost/Ghost/blob/main/apps/admin-x-framework/src/api/tinybird.ts
      status: profiled
      tags:
      - Analytics
      - Data
      - Real-Time
      - SQL
      tier: observed
      url: /providers/tinybird/
    - agent_band: agent-native
      agent_readiness: 60.0
      apps:
      - Klaviyo
      band: exemplar
      in_catalog: true
      kin_score: 69.6
      mcp:
        status: none
      name: Triple Whale
      slug: triple-whale
      sources:
      - https://marketplace.klaviyo.com/en-us/
      status: profiled
      tags:
      - Analytics
      - Attribution
      - E-Commerce
      - Shopify
      tier: declared
      url: /providers/triple-whale/
    - agent_band: agent-aware
      agent_readiness: 23.1
      apps:
      - Ghost
      band: strong
      in_catalog: true
      kin_score: 63.4
      mcp:
        status: none
      name: Plausible Analytics
      slug: plausible
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Analytics
      - Cookie-Free
      - Event Tracking
      - GDPR
      tier: declared
      url: /providers/plausible/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Ghost
      - beehiiv
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://ghost.org/integrations/
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Ghost
      - beehiiv
      band: developing
      in_catalog: true
      kin_score: 46.9
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://ghost.org/integrations/
      - https://www.beehiiv.com/integrations
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: declared
      url: /providers/discord/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.9
      apps:
      - Keila
      - listmonk
      band: thin
      in_catalog: true
      kin_score: 31.5
      mcp:
        status: none
      name: hCaptcha
      slug: hcaptcha
      sources:
      - https://raw.githubusercontent.com/knadh/listmonk/master/internal/captcha/captcha.go
      - https://raw.githubusercontent.com/pentacent/keila/main/lib/keila_web/helpers/captcha/captcha.ex
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Privacy
      - hCaptcha
      tier: observed
      url: /providers/hcaptcha/
    - agent_band: agent-aware
      agent_readiness: 17.9
      apps:
      - Keila
      band: thin
      in_catalog: true
      kin_score: 28.3
      mcp:
        status: none
      name: Friendly Captcha
      slug: friendly-captcha
      sources:
      - https://raw.githubusercontent.com/pentacent/keila/main/lib/keila_web/helpers/captcha/captcha.ex
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Privacy
      - Proof of Work
      tier: observed
      url: /providers/friendly-captcha/
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
      - Ghost
      - Substack
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/TryGhost/Ghost/main/ghost/package.json
      - https://reports.exodus-privacy.eu.org/en/reports/com.substack.app/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Mailchimp
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id001
      name: Firebase (Crashlytics + Analytics)
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - listmonk
      band: exemplar
      in_catalog: true
      kin_score: 83.3
      mcp:
        status: none
      name: Amazon Pinpoint (SMS)
      slug: amazon-pinpoint
      sources:
      - https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
      status: profiled
      tags:
      - Amazon Web Services
      - Campaigns
      - Communications
      - Email
      tier: declared
      url: /providers/amazon-pinpoint/
    - agent_band: agent-ready
      agent_readiness: 61.2
      apps:
      - listmonk
      band: exemplar
      in_catalog: true
      kin_score: 71.0
      mcp:
        source: https://github.com/novuhq/novu-mcp-server
        status: verified
      name: Novu
      slug: novu
      sources:
      - https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
      status: profiled
      tags:
      - Email
      - In-App
      - Messaging
      - Notification
      tier: declared
      url: /providers/novu/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - listmonk
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id001
      name: Firebase Cloud Messaging
      slug: firebase
      sources:
      - https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 71.4
      apps:
      - Klaviyo
      - Mailchimp
      band: exemplar
      in_catalog: true
      kin_score: 79.9
      mcp:
        source: https://www.canva.dev/docs/mcp/
        status: verified
      name: Canva
      slug: canva
      sources:
      - https://mailchimp.com/integrations/
      - https://marketplace.klaviyo.com/en-us/
      status: profiled
      tags:
      - Application
      - Automation
      - Brand Management
      - Collaboration
      tier: declared
      url: /providers/canva/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.9
      apps:
      - Mautic
      band: thin
      in_catalog: true
      kin_score: 33.3
      mcp:
        status: none
      name: MaxMind
      slug: maxmind
      sources:
      - https://raw.githubusercontent.com/mautic/mautic/7.x/app/composer.json
      status: profiled
      tags:
      - Fraud Prevention
      - Geolocation
      - IP Intelligence
      - Risk Scoring
      tier: observed
      url: /providers/maxmind/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Mautic
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        source: https://github.com/ip2location/mcp-ip2location-io
        status: verified
      name: IP2Location
      slug: ip2location
      sources:
      - https://raw.githubusercontent.com/mautic/mautic/7.x/app/composer.json
      status: profiled
      tags:
      - Geocoding
      - Public APIs
      tier: observed
      url: /providers/ip2location/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - Mailchimp
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp: *id003
      name: Stripe
      slug: stripe
      sources:
      - https://mailchimp.com/integrations/
      status: profiled
      tags: *id004
      tier: declared
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - Ghost
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: declared
      url: /providers/paypal/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-native
      agent_readiness: 56.4
      apps:
      - Mautic
      band: exemplar
      in_catalog: true
      kin_score: 90.3
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://raw.githubusercontent.com/mautic/mautic/7.x/app/composer.json
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-aware
      agent_readiness: 20.4
      apps:
      - listmonk
      band: minimal
      in_catalog: true
      kin_score: 6.6
      mcp:
        status: none
      name: Verimor (SMS, Turkey)
      slug: verimor
      sources:
      - https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
      status: profiled
      tags:
      - SMS
      - WhatsApp
      tier: declared
      url: /providers/verimor/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Klaviyo
      band: developing
      in_catalog: true
      kin_score: 43.6
      mcp:
        source: https://github.com/gorgias/mcp-cookbook
        status: verified
      name: Gorgias
      slug: gorgias
      sources:
      - https://marketplace.klaviyo.com/en-us/
      status: profiled
      tags:
      - Customer Service
      - E-Commerce
      - Help Desk
      - Shopify
      tier: declared
      url: /providers/gorgias/
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.9
      apps:
      - Mailchimp
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        source: https://support.optimizely.com/hc/en-us/articles/45320607594893
        status: documented
      name: Optimizely
      slug: optimizely
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
      status: profiled
      tags:
      - A/B Testing
      - Content Management
      - Customer Data
      - E-Commerce
      tier: observed
      url: /providers/optimizely/
  layer: common
summary:
  coverage_pct: 98.8
  declared_only: 47
  distinct_providers: 84
  in_catalog: 83
  mcp:
    documented: 2
    none: 41
    unchecked: 0
    verified: 41
  mcp_verified: 41
  mean_kin_score: 55.5
  observed: 37
  queued: 1
  reference_apps: 8
title: 'Email Marketing & Newsletters: application blueprint'
---
