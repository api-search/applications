---
access: understanding
agent_layer:
- app: HubSpot Marketing Hub
  finding: First-party HubSpot MCP server documented
  source: https://developers.hubspot.com/mcp
  tier: declared
- app: Braze
  finding: First-party Braze MCP server documented
  source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
  tier: declared
- app: Customer.io
  finding: First-party Customer.io MCP server documented
  source: https://docs.customer.io/ai/mcp-server/
  tier: declared
- app: Braze
  finding: 'BYO model: OpenAI, Anthropic, Google Gemini, Amazon Bedrock, Databricks Mosaic, Microsoft Foundry listed as AI model provider partners'
  source: https://www.braze.com/docs/partners/home
  tier: declared
apps:
- anchor: mautic
  counts:
    declared: 3
    observed: 28
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/mautic/mautic/7.x/app/composer.json
  - route: documentation
    url: https://docs.mautic.org/en/5.x/configuration/settings.html
  - route: source code
    url: https://github.com/mautic/mautic/tree/7.x/app/bundles/CoreBundle/IpLookup
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
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: domain
    name: Extreme IP Lookup
    provider: extreme-ip-lookup
    says: ships the Extreme IP Lookup SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/app/bundles/CoreBundle/IpLookup
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.70
      key: content-marketing-management
      name: Content Marketing Management
      url: /capabilities/content-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Foursquare
    provider: foursquare
    says: ships the Foursquare SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: FullContact
    provider: fullcontact
    says: ships the FullContact SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: domain
    name: Geobytes
    provider: geobytes
    says: ships the Geobytes SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/app/bundles/CoreBundle/IpLookup
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: domain
    name: GeoIPs
    provider: iplocate
    says: ships the GeoIPs SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/app/bundles/CoreBundle/IpLookup
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
    name: Gmail
    provider: google-gmail
    says: ships the Gmail SDK or integration code
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
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
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
    layer: domain
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
    layer: domain
    name: IPInfoDB
    provider: ipinfodb
    says: ships the IPInfoDB SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/app/bundles/CoreBundle/IpLookup
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: domain
    name: ipstack
    provider: ipstack
    says: ships the ipstack SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/app/bundles/CoreBundle/IpLookup
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
    name: Mailchimp
    provider: mailchimp
    says: ships the Mailchimp SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticEmailMarketingBundle/Integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: domain
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
    name: Microsoft Dynamics
    provider: microsoft-dynamics-365
    says: ships the Microsoft Dynamics SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
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
    name: Outlook
    provider: microsoft-outlook
    says: ships the Outlook SDK or integration code
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
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Twitter (X)
    provider: x
    says: ships the Twitter (X) SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
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
    provider: zoho-crm
    says: ships the Zoho CRM SDK or integration code
    source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
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
    says: lists Google Analytics as an integration
    source: https://docs.mautic.org/en/5.x/configuration/settings.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: SendGrid
    provider: sendgrid
    says: lists SendGrid as an integration
    source: https://docs.mautic.org/en/5.x/configuration/settings.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: SparkPost
    provider: sparkpost
    says: lists SparkPost as an integration
    source: https://docs.mautic.org/en/5.x/configuration/settings.html
    tier: declared
  kind: self-hosted
  name: Mautic
  page: /applications/marketing-automation/mautic/
  slug: mautic
  url: https://github.com/mautic/mautic
- anchor: dittofeed
  counts:
    declared: 3
    observed: 11
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/dittofeed/dittofeed/main/packages/backend-lib/package.json
  - route: documentation
    url: https://github.com/dittofeed/dittofeed/tree/main/packages/docs/integrations
  - route: source code
    url: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
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
    source: https://raw.githubusercontent.com/dittofeed/dittofeed/main/packages/backend-lib/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Amazon SES
    provider: amazon-ses
    says: ships the Amazon SES SDK or integration code
    source: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
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
    name: Firebase Cloud Messaging
    provider: firebase
    says: ships the Firebase Cloud Messaging SDK or integration code
    source: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
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
    name: Gmail
    provider: google-gmail
    says: ships the Gmail SDK or integration code
    source: https://raw.githubusercontent.com/dittofeed/dittofeed/main/packages/backend-lib/package.json
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
    name: HyperDX
    provider: hyperdx
    says: ships the HyperDX SDK or integration code
    source: https://raw.githubusercontent.com/dittofeed/dittofeed/main/packages/backend-lib/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailchimp (Mandrill)
    provider: mailchimp
    says: ships the Mailchimp (Mandrill) SDK or integration code
    source: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Postmark
    provider: postmark
    says: ships the Postmark SDK or integration code
    source: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Resend
    provider: resend
    says: ships the Resend SDK or integration code
    source: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: SendGrid
    provider: sendgrid
    says: ships the SendGrid SDK or integration code
    source: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
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
    name: SignalWire
    provider: signalwire
    says: ships the SignalWire SDK or integration code
    source: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
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
    source: https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
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
    says: lists HubSpot as an integration
    source: https://github.com/dittofeed/dittofeed/tree/main/packages/docs/integrations
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
    name: Polytomic
    provider: polytomic
    says: lists Polytomic as an integration
    source: https://github.com/dittofeed/dittofeed/tree/main/packages/docs/integrations
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
    name: Segment
    provider: segment
    says: lists Segment as an integration
    source: https://github.com/dittofeed/dittofeed/tree/main/packages/docs/integrations
    tier: declared
  kind: open-source-saas
  name: Dittofeed
  page: /applications/marketing-automation/dittofeed/
  slug: dittofeed
  url: https://github.com/dittofeed/dittofeed
- anchor: laudspeaker
  counts:
    declared: 0
    observed: 13
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    name: AWS
    provider: amazon-web-services
    says: ships the AWS SDK or integration code
    source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    name: Databricks
    provider: databricks
    says: ships the Databricks SDK or integration code
    source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    name: Firebase Cloud Messaging
    provider: firebase
    says: ships the Firebase Cloud Messaging SDK or integration code
    source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailgun
    provider: mailgun
    says: ships the Mailgun SDK or integration code
    source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    name: Papertrail
    provider: solarwinds
    says: ships the Papertrail SDK or integration code
    source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    name: PostHog
    provider: posthog
    says: ships the PostHog SDK or integration code
    source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Resend
    provider: resend
    says: ships the Resend SDK or integration code
    source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: SendGrid
    provider: sendgrid
    says: ships the SendGrid SDK or integration code
    source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4270.80.30
      key: BC-4270.80.30
      name: Webhook Delivery Reliability Management
      url: /capabilities/webhook-event-subscription-management/
      via_parent: Webhook & Event Subscription Management
    credit: null
    layer: common
    name: Svix
    provider: svix
    says: ships the Svix SDK or integration code
    source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
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
    source: https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
    tier: observed
  kind: open-source-saas
  name: Laudspeaker
  page: /applications/marketing-automation/laudspeaker/
  slug: laudspeaker
  url: https://github.com/laudspeaker/laudspeaker
- anchor: hubspot-marketing-hub
  counts:
    declared: 12
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
  - route: integrations page
    url: https://www.hubspot.com/products/marketing/ads
  - route: integrations page
    url: https://www.hubspot.com/products/marketing/social-inbox
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
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
    name: New Relic
    provider: new-relic
    says: ships the New Relic SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Wootric
    provider: wootric
    says: ships the Wootric SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
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
    name: ChatGPT ads
    provider: openai
    says: lists ChatGPT ads as an integration
    source: https://www.hubspot.com/products/marketing/ads
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Facebook
    provider: facebook
    says: lists Facebook as an integration
    source: https://www.hubspot.com/products/marketing/social-inbox
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
    source: https://www.hubspot.com/products/marketing/ads
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Instagram
    provider: instagram
    says: lists Instagram as an integration
    source: https://www.hubspot.com/products/marketing/social-inbox
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: LinkedIn
    provider: linkedin
    says: lists LinkedIn as an integration
    source: https://www.hubspot.com/products/marketing/social-inbox
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
    source: https://www.hubspot.com/products/marketing/ads
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
    source: https://www.hubspot.com/products/marketing/ads
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
    name: Microsoft Ads
    provider: microsoft-advertising
    says: lists Microsoft Ads as an integration
    source: https://www.hubspot.com/products/marketing/ads
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
    name: Reddit Ads
    provider: reddit
    says: lists Reddit Ads as an integration
    source: https://www.hubspot.com/products/marketing/ads
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: TikTok
    provider: tiktok
    says: lists TikTok as an integration
    source: https://www.hubspot.com/products/marketing/social-inbox
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
    name: TikTok Ads
    provider: tiktok
    says: lists TikTok Ads as an integration
    source: https://www.hubspot.com/products/marketing/ads
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: YouTube
    provider: youtube
    says: lists YouTube as an integration
    source: https://www.hubspot.com/products/marketing/social-inbox
    tier: declared
  kind: commercial
  name: HubSpot Marketing Hub
  page: /applications/marketing-automation/hubspot-marketing-hub/
  slug: hubspot-marketing-hub
  url: https://www.hubspot.com/products/marketing
- anchor: mailchimp
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
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
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
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
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
    tier: observed
  kind: commercial
  name: Mailchimp
  page: /applications/marketing-automation/mailchimp/
  slug: mailchimp
  url: https://mailchimp.com/
- anchor: braze
  counts:
    declared: 31
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.braze.com/docs/partners/home
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: null
    layer: domain
    name: Adjust
    provider: adjust
    says: lists Adjust as an integration
    source: https://www.braze.com/docs/partners/home
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: Amazon Bedrock
    provider: amazon-bedrock
    says: lists Amazon Bedrock as an integration
    source: https://www.braze.com/docs/partners/home
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
    name: Amplitude
    provider: amplitude
    says: lists Amplitude as an integration
    source: https://www.braze.com/docs/partners/home
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: Anthropic
    provider: anthropic
    says: lists Anthropic as an integration
    source: https://www.braze.com/docs/partners/home
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: null
    layer: domain
    name: AppsFlyer
    provider: appsflyer
    says: lists AppsFlyer as an integration
    source: https://www.braze.com/docs/partners/home
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: null
    layer: domain
    name: Branch (branch.io)
    provider: branch-io
    says: lists Branch (branch.io) as an integration
    source: https://www.braze.com/docs/partners/home
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
    name: Census (Fivetran Activations)
    provider: getcensus
    says: lists Census (Fivetran Activations) as an integration
    source: https://www.braze.com/docs/partners/home
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
    name: Criteo
    provider: criteo
    says: lists Criteo as an integration
    source: https://www.braze.com/docs/partners/home
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
    source: https://www.braze.com/docs/partners/home
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
    name: Google
    provider: google-ads
    says: lists Google as an integration
    source: https://www.braze.com/docs/partners/home
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: Google Gemini
    provider: google-gemini
    says: lists Google Gemini as an integration
    source: https://www.braze.com/docs/partners/home
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
    name: Hightouch
    provider: hightouch
    says: lists Hightouch as an integration
    source: https://www.braze.com/docs/partners/home
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: null
    layer: domain
    name: Kochava
    provider: kochava
    says: lists Kochava as an integration
    source: https://www.braze.com/docs/partners/home
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
    name: LinkedIn
    provider: linkedin
    says: lists LinkedIn as an integration
    source: https://www.braze.com/docs/partners/home
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-912
      key: AE-912
      name: Direct Mail APIs
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Lob
    provider: lob
    says: lists Lob as an integration
    source: https://www.braze.com/docs/partners/home
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
    source: https://www.braze.com/docs/partners/home
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
    name: mParticle
    provider: mparticle
    says: lists mParticle as an integration
    source: https://www.braze.com/docs/partners/home
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: lists OpenAI as an integration
    source: https://www.braze.com/docs/partners/home
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: common
    name: Optimizely
    provider: optimizely
    says: lists Optimizely as an integration
    source: https://www.braze.com/docs/partners/home
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
    name: Pinterest
    provider: pinterest
    says: lists Pinterest as an integration
    source: https://www.braze.com/docs/partners/home
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
    name: RudderStack
    provider: rudderstack
    says: lists RudderStack as an integration
    source: https://www.braze.com/docs/partners/home
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
    name: Segment
    provider: segment
    says: lists Segment as an integration
    source: https://www.braze.com/docs/partners/home
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: null
    layer: domain
    name: Singular
    provider: singular
    says: lists Singular as an integration
    source: https://www.braze.com/docs/partners/home
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
    name: Snapchat
    provider: snapchat
    says: lists Snapchat as an integration
    source: https://www.braze.com/docs/partners/home
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
    name: Snowflake
    provider: snowflake
    says: lists Snowflake as an integration
    source: https://www.braze.com/docs/partners/home
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
    source: https://www.braze.com/docs/partners/home
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
    name: Tealium
    provider: tealium
    says: lists Tealium as an integration
    source: https://www.braze.com/docs/partners/home
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
    name: The Trade Desk
    provider: trade-desk
    says: lists The Trade Desk as an integration
    source: https://www.braze.com/docs/partners/home
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
    source: https://www.braze.com/docs/partners/home
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
    source: https://www.braze.com/docs/partners/home
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
    name: Zendesk
    provider: zendesk
    says: lists Zendesk as an integration
    source: https://www.braze.com/docs/partners/home
    tier: declared
  kind: commercial
  name: Braze
  page: /applications/marketing-automation/braze/
  slug: braze
  url: https://www.braze.com/
- anchor: customerio
  counts:
    declared: 21
    observed: 0
  evidence:
  - route: integrations page
    url: https://docs.customer.io/integrations/data-out/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Amplitude
    provider: amplitude
    says: lists Amplitude as an integration
    source: https://docs.customer.io/integrations/data-out/
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
    name: BigQuery
    provider: google-bigquery
    says: lists BigQuery as an integration
    source: https://docs.customer.io/integrations/data-out/
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
    name: Bing Ads
    provider: microsoft-advertising
    says: lists Bing Ads as an integration
    source: https://docs.customer.io/integrations/data-out/
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
    name: Criteo Audiences
    provider: criteo
    says: lists Criteo Audiences as an integration
    source: https://docs.customer.io/integrations/data-out/
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
    name: Facebook Conversions API / Meta Pixel
    provider: facebook
    says: lists Facebook Conversions API / Meta Pixel as an integration
    source: https://docs.customer.io/integrations/data-out/
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
    source: https://docs.customer.io/integrations/data-out/
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
    name: Google Analytics 4
    provider: google-analytics
    says: lists Google Analytics 4 as an integration
    source: https://docs.customer.io/integrations/data-out/
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
    source: https://docs.customer.io/integrations/data-out/
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
    source: https://docs.customer.io/integrations/data-out/
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
    source: https://docs.customer.io/integrations/data-out/
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
    name: Pinterest Conversions
    provider: pinterest
    says: lists Pinterest Conversions as an integration
    source: https://docs.customer.io/integrations/data-out/
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
    source: https://docs.customer.io/integrations/data-out/
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
    source: https://docs.customer.io/integrations/data-out/
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
    name: Segment
    provider: segment
    says: lists Segment as an integration
    source: https://docs.customer.io/integrations/data-out/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: SendGrid
    provider: sendgrid
    says: lists SendGrid as an integration
    source: https://docs.customer.io/integrations/data-out/
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
    source: https://docs.customer.io/integrations/data-out/
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
    name: Snowflake
    provider: snowflake
    says: lists Snowflake as an integration
    source: https://docs.customer.io/integrations/data-out/
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
    name: TikTok Conversions
    provider: tiktok
    says: lists TikTok Conversions as an integration
    source: https://docs.customer.io/integrations/data-out/
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
    name: Twilio
    provider: twilio
    says: lists Twilio as an integration
    source: https://docs.customer.io/integrations/data-out/
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
    name: Twitter Pixel
    provider: x
    says: lists Twitter Pixel as an integration
    source: https://docs.customer.io/integrations/data-out/
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
    name: Zendesk
    provider: zendesk
    says: lists Zendesk as an integration
    source: https://docs.customer.io/integrations/data-out/
    tier: declared
  kind: commercial
  name: Customer.io
  page: /applications/marketing-automation/customer-io/
  slug: customer-io
  url: https://customer.io/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: marketing-automation
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Marketing
  store: hubspot-marketplace
  url: https://ecosystem.hubspot.com/marketplace/apps
- category: Marketing
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Marketing and conversion
  store: shopify-app-store
  url: https://apps.shopify.com/categories
- category: Marketing Automation
  store: zapier
  url: https://zapier.com/apps
name: Marketing Automation & Ads
needs:
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: Marketing automation syncs contacts, leads and deals to and from the CRM.
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: Campaign email/list platforms and paid ad networks are where campaigns run.
- capability:
    attribution: Turbo EA
    id: BC-400.60.40
    key: BC-400.60.40
    name: Social Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: exact
  layer: domain
  why: Social publishing and listening from the marketing tool.
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  fit: exact
  layer: common
  why: Asset/file storage for campaign media and exports.
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.10
    key: AE-230.30.10
    name: Data Enrichment
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  fit: exact
  layer: domain
  why: Contact/company enrichment from an email or domain.
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: Reading and logging a rep's own mailbox (Gmail/Outlook plugins); no BC capability.
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: No-code integration platforms connecting the tool to everything else; no BC capability.
- capability:
    attribution: Turbo EA
    id: BC-2330.10
    key: channel-orchestration-management
    name: Channel Orchestration Management
    url: /capabilities/channel-orchestration-management/
    via_parent: null
  fit: nearest
  layer: common
  why: Email/SMS/push delivery APIs send the messages journeys produce; no BC capability for message delivery itself.
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: domain
  why: IP-to-location lookup for contact enrichment and geo segmentation; no BC capability.
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: Product/web analytics and in-app tracking SDKs.
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: Crash reporting, APM and logging.
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: domain
  why: Event and profile data in (CDP sources) and audiences out (reverse ETL).
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: nearest
  layer: common
  why: Team-chat notifications from campaigns and alerts.
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: Billing for the marketing product itself.
- capability:
    attribution: Turbo EA
    id: BC-4270.80.30
    key: BC-4270.80.30
    name: Webhook Delivery Reliability Management
    url: /capabilities/webhook-event-subscription-management/
    via_parent: Webhook & Event Subscription Management
  fit: exact
  layer: common
  why: Outbound webhook delivery as a service; no BC capability.
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: nearest
  layer: common
  why: Cloud data warehouses as source and sink for marketing data.
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  fit: exact
  layer: common
  why: NPS/CSAT surveys.
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: domain
  why: Mobile install attribution and deep linking; no BC capability.
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  fit: exact
  layer: common
  why: A/B testing and feature experimentation.
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  fit: exact
  layer: agent
  why: LLM providers behind AI copy, agents and decisioning.
- capability:
    attribution: API Evangelist extension
    id: AE-912
    key: AE-912
    name: Direct Mail APIs
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: exact
  layer: domain
  why: Printed direct mail as a journey channel; no BC capability.
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: Helpdesk / support inbox sync.
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - Braze
      - Customer.io
      - HubSpot Marketing Hub
      band: exemplar
      in_catalog: true
      kin_score: 73.1
      mcp:
        source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
        status: verified
      name: Google Ads
      slug: google-ads
      sources:
      - https://docs.customer.io/integrations/data-out/
      - https://www.braze.com/docs/partners/home
      - https://www.hubspot.com/products/marketing/ads
      status: profiled
      tags:
      - Advertising
      - Campaign Management
      - Digital Advertising
      - Google
      tier: declared
      url: /providers/google-ads/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Braze
      - Customer.io
      - HubSpot Marketing Hub
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp: &id001
        status: none
      name: Meta Ads
      slug: facebook
      sources:
      - https://docs.customer.io/integrations/data-out/
      - https://www.braze.com/docs/partners/home
      - https://www.hubspot.com/products/marketing/ads
      status: profiled
      tags: &id002
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: declared
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Braze
      - Customer.io
      - HubSpot Marketing Hub
      band: developing
      in_catalog: true
      kin_score: 41.0
      mcp: &id007
        status: none
      name: TikTok Ads
      slug: tiktok
      sources:
      - https://docs.customer.io/integrations/data-out/
      - https://www.braze.com/docs/partners/home
      - https://www.hubspot.com/products/marketing/ads
      status: profiled
      tags: &id008
      - Advertising
      - Commerce
      - Content
      - TikTok
      tier: declared
      url: /providers/tiktok/
    - agent_band: agent-ready
      agent_readiness: 47.4
      apps:
      - Braze
      - HubSpot Marketing Hub
      band: exemplar
      in_catalog: true
      kin_score: 76.4
      mcp: &id005
        status: none
      name: LinkedIn Ads
      slug: linkedin
      sources:
      - https://www.braze.com/docs/partners/home
      - https://www.hubspot.com/products/marketing/ads
      status: profiled
      tags: &id006
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: declared
      url: /providers/linkedin/
    - agent_band: agent-ready
      agent_readiness: 39.3
      apps:
      - Braze
      - Customer.io
      band: strong
      in_catalog: true
      kin_score: 61.6
      mcp:
        status: none
      name: Criteo
      slug: criteo
      sources:
      - https://docs.customer.io/integrations/data-out/
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - Advertising
      - Agent Skills
      - Analytics
      - Audiences
      tier: declared
      url: /providers/criteo/
    - agent_band: agent-ready
      agent_readiness: 38.4
      apps:
      - Braze
      - Customer.io
      band: developing
      in_catalog: true
      kin_score: 49.4
      mcp:
        source: https://developers.pinterest.com/about-pinterest-mcp/
        status: verified
      name: Pinterest
      slug: pinterest
      sources:
      - https://docs.customer.io/integrations/data-out/
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - Image
      - Social
      - Social Media
      - Video
      tier: declared
      url: /providers/pinterest/
    - agent_band: agent-aware
      agent_readiness: 10.8
      apps:
      - Customer.io
      - HubSpot Marketing Hub
      band: developing
      in_catalog: true
      kin_score: 42.5
      mcp:
        status: none
      name: Microsoft Ads
      slug: microsoft-advertising
      sources:
      - https://docs.customer.io/integrations/data-out/
      - https://www.hubspot.com/products/marketing/ads
      status: profiled
      tags:
      - Advertising
      - Analytics
      - Bing Ads
      - Bulk Operations
      tier: declared
      url: /providers/microsoft-advertising/
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - Mautic
      band: exemplar
      in_catalog: true
      kin_score: 78.3
      mcp: &id009
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticEmailMarketingBundle/Integration
      status: profiled
      tags: &id010
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: observed
      url: /providers/mailchimp/
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
    - agent_band: agent-native
      agent_readiness: 58.4
      apps:
      - HubSpot Marketing Hub
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp: &id013
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: ChatGPT ads
      slug: openai
      sources:
      - https://www.hubspot.com/products/marketing/ads
      status: profiled
      tags: &id014
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: declared
      url: /providers/openai/
    - agent_band: agent-native
      agent_readiness: 61.2
      apps:
      - Customer.io
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp: &id003
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: Twitter Pixel
      slug: x
      sources:
      - https://docs.customer.io/integrations/data-out/
      status: profiled
      tags: &id004
      - Conversations
      - Social
      - Spaces
      - X
      tier: declared
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 48.1
      apps:
      - Braze
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp:
        status: none
      name: Snapchat
      slug: snapchat
      sources:
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - Advertising
      - Augmented Reality
      - Marketing
      - Messaging
      tier: declared
      url: /providers/snapchat/
    - agent_band: agent-ready
      agent_readiness: 39.1
      apps:
      - HubSpot Marketing Hub
      band: strong
      in_catalog: true
      kin_score: 63.0
      mcp:
        source: https://github.com/reddit/devvit-mcp
        status: verified
      name: Reddit Ads
      slug: reddit
      sources:
      - https://www.hubspot.com/products/marketing/ads
      status: profiled
      tags:
      - Advertising
      - Community
      - Content
      - Reddit
      tier: declared
      url: /providers/reddit/
    - agent_band: agent-ready
      agent_readiness: 44.2
      apps:
      - Braze
      band: strong
      in_catalog: true
      kin_score: 57.8
      mcp:
        status: none
      name: The Trade Desk
      slug: trade-desk
      sources:
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - AdTech
      - Advertising
      - DSP
      - Programmatic Advertising
      tier: declared
      url: /providers/trade-desk/
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
      - Braze
      - Customer.io
      - Dittofeed
      - Mailchimp
      band: developing
      in_catalog: true
      kin_score: 43.8
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://docs.customer.io/integrations/data-out/
      - https://github.com/dittofeed/dittofeed/tree/main/packages/docs/integrations
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
      agent_readiness: 57.3
      apps:
      - Laudspeaker
      band: strong
      in_catalog: true
      kin_score: 57.7
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
    - agent_band: agent-ready
      agent_readiness: 58.1
      apps:
      - Braze
      band: exemplar
      in_catalog: true
      kin_score: 78.5
      mcp:
        source: https://github.com/rudderlabs/rudderstack-mcp
        status: verified
      name: RudderStack
      slug: rudderstack
      sources:
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - CDP
      - Customer Data Platform
      - Data Pipeline
      - Open Source
      tier: declared
      url: /providers/rudderstack/
    - agent_band: agent-ready
      agent_readiness: 63.8
      apps:
      - Braze
      band: exemplar
      in_catalog: true
      kin_score: 69.4
      mcp:
        source: https://hightouch.com/docs/ai-integrations/mcp
        status: documented
      name: Hightouch
      slug: hightouch
      sources:
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - Audience Management
      - CDP
      - Data Activation
      - Reverse ETL
      tier: declared
      url: /providers/hightouch/
    - agent_band: agent-ready
      agent_readiness: 35.6
      apps:
      - Braze
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://docs.tealium.com/server-side/config-mcp/about-config-mcp/
        status: documented
      name: Tealium
      slug: tealium
      sources:
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - AudienceStream
      - CDP
      - Customer Data Platform
      - Tag Management
      tier: declared
      url: /providers/tealium/
    - agent_band: agent-aware
      agent_readiness: 26.5
      apps:
      - Braze
      band: strong
      in_catalog: true
      kin_score: 64.8
      mcp:
        status: none
      name: Census (Fivetran Activations)
      slug: getcensus
      sources:
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - Census
      - Data Activation
      - Reverse ETL
      - Sync
      tier: declared
      url: /providers/getcensus/
    - agent_band: agent-ready
      agent_readiness: 45.7
      apps:
      - Braze
      band: strong
      in_catalog: true
      kin_score: 58.7
      mcp:
        status: none
      name: mParticle
      slug: mparticle
      sources:
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - Analytics
      - CDP
      - Customer Data Platform
      - Identity Resolution
      tier: declared
      url: /providers/mparticle/
    - agent_band: agent-ready
      agent_readiness: 38.2
      apps:
      - Dittofeed
      band: developing
      in_catalog: true
      kin_score: 46.1
      mcp:
        source: https://github.com/polytomic/mcp-connector
        status: verified
      name: Polytomic
      slug: polytomic
      sources:
      - https://github.com/dittofeed/dittofeed/tree/main/packages/docs/integrations
      status: profiled
      tags:
      - Data Integration
      - ELT
      - Reverse ETL
      - Unified API
      tier: declared
      url: /providers/polytomic/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.7
      apps:
      - Customer.io
      - Dittofeed
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
      - https://docs.customer.io/integrations/data-out/
      - https://github.com/dittofeed/dittofeed/tree/main/packages/docs/integrations
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: observed
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 54.7
      apps:
      - Customer.io
      - Mautic
      band: exemplar
      in_catalog: true
      kin_score: 90.6
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://docs.customer.io/integrations/data-out/
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: observed
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 44.2
      apps:
      - Mautic
      band: exemplar
      in_catalog: true
      kin_score: 86.0
      mcp:
        status: none
      name: Zoho CRM
      slug: zoho-crm
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
      status: profiled
      tags:
      - CRM
      - Lead Management
      - Marketing Automation
      - Sales
      tier: observed
      url: /providers/zoho-crm/
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
      name: Microsoft Dynamics
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
    - agent_band: agent-ready
      agent_readiness: 29.3
      apps:
      - Customer.io
      band: strong
      in_catalog: true
      kin_score: 55.5
      mcp:
        status: none
      name: Pipedrive
      slug: pipedrive
      sources:
      - https://docs.customer.io/integrations/data-out/
      status: profiled
      tags:
      - CRM
      - Pipeline Management
      - Sales
      - Software-as-a-Service
      tier: declared
      url: /providers/pipedrive/
  - capability:
      attribution: Turbo EA
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.9
      apps:
      - HubSpot Marketing Hub
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
      - https://www.hubspot.com/products/marketing/social-inbox
      status: profiled
      tags:
      - Instagram
      - Meta
      - Photos
      - Social Media
      tier: observed
      url: /providers/instagram/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - HubSpot Marketing Hub
      - Mautic
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp: *id001
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
      - https://www.hubspot.com/products/marketing/social-inbox
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-native
      agent_readiness: 61.2
      apps:
      - Mautic
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp: *id003
      name: Twitter (X)
      slug: x
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 47.4
      apps:
      - HubSpot Marketing Hub
      band: exemplar
      in_catalog: true
      kin_score: 76.4
      mcp: *id005
      name: LinkedIn
      slug: linkedin
      sources:
      - https://www.hubspot.com/products/marketing/social-inbox
      status: profiled
      tags: *id006
      tier: declared
      url: /providers/linkedin/
    - agent_band: agent-ready
      agent_readiness: 43.4
      apps:
      - HubSpot Marketing Hub
      band: strong
      in_catalog: true
      kin_score: 62.6
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://www.hubspot.com/products/marketing/social-inbox
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: declared
      url: /providers/youtube/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - HubSpot Marketing Hub
      band: developing
      in_catalog: true
      kin_score: 41.0
      mcp: *id007
      name: TikTok
      slug: tiktok
      sources:
      - https://www.hubspot.com/products/marketing/social-inbox
      status: profiled
      tags: *id008
      tier: declared
      url: /providers/tiktok/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - Mautic
      band: developing
      in_catalog: true
      kin_score: 47.1
      mcp:
        status: none
      name: ipstack
      slug: ipstack
      sources:
      - https://github.com/mautic/mautic/tree/7.x/app/bundles/CoreBundle/IpLookup
      status: profiled
      tags:
      - Geocoding
      - IP Geolocation
      - Location
      - Threat Intelligence
      tier: observed
      url: /providers/ipstack/
    - agent_band: agent-aware
      agent_readiness: 18.0
      apps:
      - Mautic
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        source: https://github.com/iplocate/mcp-server-iplocate
        status: verified
      name: GeoIPs
      slug: iplocate
      sources:
      - https://github.com/mautic/mautic/tree/7.x/app/bundles/CoreBundle/IpLookup
      status: profiled
      tags:
      - Company
      - IP Geolocation
      - Privacy
      - Threat Detection
      tier: observed
      url: /providers/iplocate/
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
      kin_score: 8.7
      mcp:
        status: unknown
      name: Extreme IP Lookup
      slug: extreme-ip-lookup
      sources:
      - https://github.com/mautic/mautic/tree/7.x/app/bundles/CoreBundle/IpLookup
      status: profiled
      tags:
      - Company
      - Data
      - Geolocation
      - IP
      tier: observed
      url: /providers/extreme-ip-lookup/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Mautic
      band: minimal
      in_catalog: true
      kin_score: 6.2
      mcp:
        status: unknown
      name: Geobytes
      slug: geobytes
      sources:
      - https://github.com/mautic/mautic/tree/7.x/app/bundles/CoreBundle/IpLookup
      status: profiled
      tags:
      - Company
      - Free
      - Geolocation
      - IP
      tier: observed
      url: /providers/geobytes/
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
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Mautic
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        status: none
      name: IPInfoDB
      slug: ipinfodb
      sources:
      - https://github.com/mautic/mautic/tree/7.x/app/bundles/CoreBundle/IpLookup
      status: profiled
      tags:
      - Geocoding
      - Public APIs
      tier: observed
      url: /providers/ipinfodb/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Braze
      - Mailchimp
      band: emerging
      in_catalog: true
      kin_score: 23.0
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - Braze
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: declared
      url: /providers/appsflyer/
    - agent_band: agent-ready
      agent_readiness: 50.0
      apps:
      - Braze
      band: exemplar
      in_catalog: true
      kin_score: 67.4
      mcp:
        status: none
      name: Singular
      slug: singular
      sources:
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - Attribution
      - Company
      - Marketing Analytics
      - Mobile Attribution
      tier: declared
      url: /providers/singular/
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Braze
      band: emerging
      in_catalog: true
      kin_score: 24.9
      mcp:
        status: none
      name: Adjust
      slug: adjust
      sources:
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - Analytics
      - Attribution
      - Deep Linking
      - Measurements
      tier: declared
      url: /providers/adjust/
    - agent_band: null
      agent_readiness: null
      apps:
      - Braze
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Kochava
      slug: kochava
      sources:
      - https://www.braze.com/docs/partners/home
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Dittofeed
      - Mautic
      band: developing
      in_catalog: true
      kin_score: 44.1
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins
      - https://raw.githubusercontent.com/dittofeed/dittofeed/main/packages/backend-lib/package.json
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: observed
      url: /providers/google-gmail/
    - agent_band: agent-ready
      agent_readiness: 49.5
      apps:
      - Mautic
      band: exemplar
      in_catalog: true
      kin_score: 70.6
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Outlook
      slug: microsoft-outlook
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins
      status: profiled
      tags:
      - Calendar
      - Contacts
      - Email
      - Enterprise
      tier: observed
      url: /providers/microsoft-outlook/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    providers:
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
      attribution: Turbo EA
      id: BC-400.70
      key: content-marketing-management
      name: Content Marketing Management
      url: /capabilities/content-marketing-management/
      via_parent: null
    providers:
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
  - capability:
      attribution: API Evangelist extension
      id: AE-912
      key: AE-912
      name: Direct Mail APIs
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-native
      agent_readiness: 42.4
      apps:
      - Braze
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Lob
      slug: lob
      sources:
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - Address Verification
      - Direct Mail
      - Print
      tier: declared
      url: /providers/lob/
  layer: domain
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
      - Customer.io
      - Dittofeed
      - Laudspeaker
      - Mautic
      band: exemplar
      in_catalog: true
      kin_score: 87.3
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://docs.customer.io/integrations/data-out/
      - https://docs.mautic.org/en/5.x/configuration/settings.html
      - https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-ready
      agent_readiness: 49.4
      apps:
      - Dittofeed
      - Laudspeaker
      band: strong
      in_catalog: true
      kin_score: 58.9
      mcp:
        source: https://resend.com/docs/mcp-server
        status: verified
      name: Resend
      slug: resend
      sources:
      - https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
      - https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
      status: profiled
      tags:
      - Developer Tools
      - Email
      - Marketing Email
      - Transactional Email
      tier: observed
      url: /providers/resend/
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - Dittofeed
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        status: none
      name: Amazon SES
      slug: amazon-ses
      sources:
      - https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - Dittofeed
      band: exemplar
      in_catalog: true
      kin_score: 78.3
      mcp: *id009
      name: Mailchimp (Mandrill)
      slug: mailchimp
      sources:
      - https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
      status: profiled
      tags: *id010
      tier: observed
      url: /providers/mailchimp/
    - agent_band: agent-ready
      agent_readiness: 41.7
      apps:
      - Dittofeed
      band: exemplar
      in_catalog: true
      kin_score: 71.3
      mcp:
        source: https://github.com/ActiveCampaign/postmark-mcp
        status: verified
      name: Postmark
      slug: postmark
      sources:
      - https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
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
      - Laudspeaker
      band: thin
      in_catalog: true
      kin_score: 32.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
      status: profiled
      tags:
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailgun/
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
      - https://docs.mautic.org/en/5.x/configuration/settings.html
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
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - HubSpot Marketing Hub
      - Mailchimp
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: &id011
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics / Crashlytics
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
      status: profiled
      tags: &id012
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - Customer.io
      - Mautic
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://docs.customer.io/integrations/data-out/
      - https://docs.mautic.org/en/5.x/configuration/settings.html
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: declared
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 56.7
      apps:
      - Braze
      - Customer.io
      band: strong
      in_catalog: true
      kin_score: 63.5
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://docs.customer.io/integrations/data-out/
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: declared
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 48.3
      apps:
      - Braze
      - Customer.io
      band: strong
      in_catalog: true
      kin_score: 60.3
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://docs.customer.io/integrations/data-out/
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: declared
      url: /providers/mixpanel/
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
      - Customer.io
      - Dittofeed
      - Laudspeaker
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
      - https://docs.customer.io/integrations/data-out/
      - https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
      - https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-ready
      agent_readiness: 42.4
      apps:
      - Dittofeed
      band: exemplar
      in_catalog: true
      kin_score: 77.2
      mcp:
        status: none
      name: SignalWire
      slug: signalwire
      sources:
      - https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
      status: profiled
      tags:
      - CPaaS
      - Communications
      - Company
      - Voice
      tier: observed
      url: /providers/signalwire/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 45.8
      apps:
      - Braze
      - Customer.io
      band: exemplar
      in_catalog: true
      kin_score: 81.1
      mcp:
        source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
        status: verified
      name: Snowflake
      slug: snowflake
      sources:
      - https://docs.customer.io/integrations/data-out/
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - Data
      - Data Lakehouse
      - Data Warehouse
      - Snowflake
      tier: declared
      url: /providers/snowflake/
    - agent_band: agent-ready
      agent_readiness: 58.9
      apps:
      - Laudspeaker
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://docs.databricks.com/aws/en/generative-ai/mcp/
        status: verified
      name: Databricks
      slug: databricks
      sources:
      - https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cleanroom
      - Databricks
      tier: observed
      url: /providers/databricks/
    - agent_band: agent-ready
      agent_readiness: 31.5
      apps:
      - Customer.io
      band: developing
      in_catalog: true
      kin_score: 49.7
      mcp:
        source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
        status: verified
      name: BigQuery
      slug: google-bigquery
      sources:
      - https://docs.customer.io/integrations/data-out/
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Cloud
      - Data Warehouse
      tier: declared
      url: /providers/google-bigquery/
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
      - Laudspeaker
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 45.7
      apps:
      - HubSpot Marketing Hub
      band: exemplar
      in_catalog: true
      kin_score: 76.5
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
    - agent_band: agent-ready
      agent_readiness: 37.7
      apps:
      - Dittofeed
      band: exemplar
      in_catalog: true
      kin_score: 71.0
      mcp:
        status: none
      name: HyperDX
      slug: hyperdx
      sources:
      - https://raw.githubusercontent.com/dittofeed/dittofeed/main/packages/backend-lib/package.json
      status: profiled
      tags:
      - Company
      - Logging
      - Monitoring
      - Observability
      tier: observed
      url: /providers/hyperdx/
    - agent_band: agent-aware
      agent_readiness: 27.0
      apps:
      - Laudspeaker
      band: strong
      in_catalog: true
      kin_score: 65.5
      mcp:
        status: none
      name: Papertrail
      slug: solarwinds
      sources:
      - https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
      status: profiled
      tags:
      - Application Monitoring
      - Database Monitoring
      - IP Address Management
      - Infrastructure
      tier: observed
      url: /providers/solarwinds/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Braze
      - Customer.io
      band: exemplar
      in_catalog: true
      kin_score: 72.8
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://docs.customer.io/integrations/data-out/
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
    - agent_band: agent-ready
      agent_readiness: 31.7
      apps:
      - Customer.io
      band: developing
      in_catalog: true
      kin_score: 52.5
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://docs.customer.io/integrations/data-out/
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: declared
      url: /providers/intercom/
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
      - Dittofeed
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
      - https://raw.githubusercontent.com/dittofeed/dittofeed/main/packages/backend-lib/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - Laudspeaker
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS
      slug: amazon-web-services
      sources:
      - https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: observed
      url: /providers/amazon-web-services/
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
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
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - HubSpot Marketing Hub
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp:
        status: none
      name: Wootric
      slug: wootric
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.hubspot.android/latest/
      status: profiled
      tags:
      - CES
      - CSAT
      - Customer Experience
      - NPS
      tier: observed
      url: /providers/wootric/
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
      - Customer.io
      - Laudspeaker
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://docs.customer.io/integrations/data-out/
      - https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
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
      - Braze
      - Laudspeaker
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
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
      - Braze
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
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - A/B Testing
      - Content Management
      - Customer Data
      - E-Commerce
      tier: observed
      url: /providers/optimizely/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Dittofeed
      - Laudspeaker
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id011
      name: Firebase Cloud Messaging
      slug: firebase
      sources:
      - https://github.com/dittofeed/dittofeed/tree/main/packages/backend-lib/src/destinations
      - https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
      status: profiled
      tags: *id012
      tier: observed
      url: /providers/firebase/
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
      - Braze
      - Mautic
      band: exemplar
      in_catalog: true
      kin_score: 72.0
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://github.com/mautic/mautic/tree/7.x/plugins
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: observed
      url: /providers/zapier/
  - capability:
      attribution: Turbo EA
      id: BC-4270.80.30
      key: BC-4270.80.30
      name: Webhook Delivery Reliability Management
      url: /capabilities/webhook-event-subscription-management/
      via_parent: Webhook & Event Subscription Management
    providers:
    - agent_band: agent-native
      agent_readiness: 53.1
      apps:
      - Laudspeaker
      band: exemplar
      in_catalog: true
      kin_score: 74.5
      mcp:
        status: none
      name: Svix
      slug: svix
      sources:
      - https://raw.githubusercontent.com/laudspeaker/laudspeaker/main/packages/server/package.json
      status: profiled
      tags:
      - Webhook
      - Webhook Delivery
      - Webhook Sending
      - Webhooks As A Service
      tier: observed
      url: /providers/svix/
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
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Braze
      band: exemplar
      in_catalog: true
      kin_score: 87.5
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: declared
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 58.4
      apps:
      - Braze
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp: *id013
      name: OpenAI
      slug: openai
      sources:
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags: *id014
      tier: declared
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Braze
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: declared
      url: /providers/google-gemini/
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Braze
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Bedrock
      slug: amazon-bedrock
      sources:
      - https://www.braze.com/docs/partners/home
      status: profiled
      tags:
      - Amazon Web Services
      - Artificial Intelligence
      - Foundation Models
      - Generative AI
      tier: declared
      url: /providers/amazon-bedrock/
  layer: agent
summary:
  coverage_pct: 98.8
  declared_only: 34
  distinct_providers: 84
  in_catalog: 83
  mcp:
    documented: 4
    none: 39
    unchecked: 1
    verified: 38
  mcp_verified: 38
  mean_kin_score: 59.0
  observed: 50
  queued: 1
  reference_apps: 7
title: 'Marketing Automation & Ads: application blueprint'
---
