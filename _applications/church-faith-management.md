---
access: understanding
agent_layer: []
apps:
- anchor: rock-rms
  counts:
    declared: 0
    observed: 21
  evidence:
  - route: dependency manifest
    url: https://github.com/SparkDevNetwork/Rock/blob/develop/Rock/Rock.csproj
  - route: source code
    url: https://github.com/SparkDevNetwork/Rock
  - route: source code
    url: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Address
  - route: source code
    url: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Communication/Transport
  - route: source code
    url: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/IpAddress
  - route: source code
    url: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Security/Authentication
  - route: source code
    url: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Storage/Provider
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Auth0
    provider: auth0
    says: ships the Auth0 SDK or integration code
    source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.Security.Authentication.Auth0
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: agent
    name: Azure AI Document Intelligence
    provider: azure-document-intelligence
    says: ships the Azure AI Document Intelligence SDK or integration code
    source: https://github.com/SparkDevNetwork/Rock/blob/develop/Rock/Rock.csproj
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: ships the Azure Blob Storage SDK or integration code
    source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Storage/Provider
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: Azure Service Bus
    provider: azure-service-bus
    says: ships the Azure Service Bus SDK or integration code
    source: https://github.com/SparkDevNetwork/Rock/blob/develop/Rock/Rock.csproj
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: realtime-messaging
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    credit: null
    layer: common
    name: Azure SignalR Service
    provider: microsoft-azure-signalr
    says: ships the Azure SignalR Service SDK or integration code
    source: https://github.com/SparkDevNetwork/Rock/blob/develop/Rock/Rock.csproj
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Checkr
    provider: checkr
    says: ships the Checkr SDK or integration code
    source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.Checkr
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Security/Authentication
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
    source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Communication/Transport
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Storage/Provider
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
    source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Security/Authentication
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
    name: IPregistry
    provider: ipregistry
    says: ships the IPregistry SDK or integration code
    source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/IpAddress
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
    name: Mailgun
    provider: mailgun
    says: ships the Mailgun SDK or integration code
    source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.Mailgun
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
    name: Mandrill (Mailchimp Transactional)
    provider: mailchimp
    says: ships the Mandrill (Mailchimp Transactional) SDK or integration code
    source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.Mandrill
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
    source: https://github.com/SparkDevNetwork/Rock/blob/develop/Rock/Rock.csproj
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: NMI
    provider: nmi
    says: ships the NMI SDK or integration code
    source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.NMI
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.AI.OpenAI
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: PayPal Payflow Pro
    provider: paypal
    says: ships the PayPal Payflow Pro SDK or integration code
    source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.PayFlowPro
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
    source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.SendGrid
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.30
      key: AE-120.10.30
      name: Address Validation & Autocomplete
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: SmartyStreets
    provider: smarty
    says: ships the SmartyStreets SDK or integration code
    source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Address
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
    source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Communication/Transport
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
    name: Twitter / X
    provider: x
    says: ships the Twitter / X SDK or integration code
    source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Security/Authentication
    tier: observed
  kind: self-hosted
  name: Rock RMS
  page: /applications/church-faith-management/rock-rms/
  slug: rock-rms
  url: https://github.com/SparkDevNetwork/Rock
- anchor: churchcrm
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: dependency manifest
    url: https://github.com/ChurchCRM/CRM/blob/master/package.json
  - route: dependency manifest
    url: https://github.com/ChurchCRM/CRM/blob/master/src/composer.json
  - route: source code
    url: https://github.com/ChurchCRM/CRM/blob/master/.env.example
  - route: source code
    url: https://github.com/ChurchCRM/CRM/tree/master/src/plugins/core
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: common
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/ChurchCRM/CRM/blob/master/src/composer.json
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
    source: https://github.com/ChurchCRM/CRM/tree/master/src/plugins/core/google-analytics
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: common
    name: Gravatar
    provider: gravatar
    says: ships the Gravatar SDK or integration code
    source: https://github.com/ChurchCRM/CRM/tree/master/src/plugins/core/gravatar
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
    name: Mailchimp
    provider: mailchimp
    says: ships the Mailchimp SDK or integration code
    source: https://github.com/ChurchCRM/CRM/tree/master/src/plugins/core/mailchimp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.40
      key: AE-170.10.40
      name: Live Presentation & Broadcast Control
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: domain
    name: OpenLP
    provider: openlp
    says: ships the OpenLP SDK or integration code
    source: https://github.com/ChurchCRM/CRM/tree/master/src/plugins/core/openlp
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
    source: https://github.com/ChurchCRM/CRM/blob/master/package.json
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
    name: Vonage
    provider: vonage
    says: ships the Vonage SDK or integration code
    source: https://github.com/ChurchCRM/CRM/tree/master/src/plugins/core/vonage
    tier: observed
  kind: self-hosted
  name: ChurchCRM
  page: /applications/church-faith-management/churchcrm/
  slug: churchcrm
  url: https://github.com/ChurchCRM/CRM
- anchor: openlp
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: source code
    url: https://gitlab.com/openlp/openlp/-/blob/master/openlp/plugins/bibles/lib/importers/http.py
  - route: source code
    url: https://gitlab.com/openlp/openlp/-/tree/master/openlp/plugins
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.50
      key: AE-170.60.50
      name: Scripture & Religious Text Content
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Bible Gateway
    provider: biblegateway
    says: ships the Bible Gateway SDK or integration code
    source: https://gitlab.com/openlp/openlp/-/blob/master/openlp/plugins/bibles/lib/importers/http.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.50
      key: AE-170.60.50
      name: Scripture & Religious Text Content
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Bible Study Tools (Crosswalk)
    provider: biblestudytools
    says: ships the Bible Study Tools (Crosswalk) SDK or integration code
    source: https://gitlab.com/openlp/openlp/-/blob/master/openlp/plugins/bibles/lib/importers/http.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.50
      key: AE-170.60.50
      name: Scripture & Religious Text Content
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: BibleServer
    provider: bibleserver
    says: ships the BibleServer SDK or integration code
    source: https://gitlab.com/openlp/openlp/-/blob/master/openlp/plugins/bibles/lib/importers/http.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.70
      key: AE-170.20.70
      name: Worship Song Licensing & Chord Charts
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: CCLI SongSelect
    provider: ccli
    says: ships the CCLI SongSelect SDK or integration code
    source: https://gitlab.com/openlp/openlp/-/tree/master/openlp/plugins/songs/lib
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.40
      key: AE-170.10.40
      name: Live Presentation & Broadcast Control
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: domain
    name: OBS Studio
    provider: obs-studio
    says: ships the OBS Studio SDK or integration code
    source: https://gitlab.com/openlp/openlp/-/tree/master/openlp/plugins/obs_studio
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-943
      key: AE-943
      name: Church Management System Sync
      url: /capabilities/church-management-system-sync/
      via_parent: null
    credit: null
    layer: common
    name: Planning Center
    provider: planning-center
    says: ships the Planning Center SDK or integration code
    source: https://gitlab.com/openlp/openlp/-/tree/master/openlp/plugins/planningcenter
    tier: observed
  kind: self-hosted
  name: OpenLP
  page: /applications/church-faith-management/openlp/
  slug: openlp
  url: https://gitlab.com/openlp/openlp
- anchor: planning-center
  counts:
    declared: 13
    observed: 7
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.PlanningCenter/latest/
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.churchcenter/latest/
  - route: integrations page
    url: https://www.planningcenter.com/integrations
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
    name: Bugsnag
    provider: bugsnag
    says: ships the Bugsnag SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.churchcenter/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.PlanningCenter/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.PlanningCenter/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.churchcenter/latest/
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
    name: Pendo
    provider: pendoio
    says: ships the Pendo SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.PlanningCenter/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Pusher
    provider: pusher
    says: ships the Pusher SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.PlanningCenter/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.churchcenter/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3740.20
      key: ott-streaming-delivery
      name: OTT & Streaming Delivery
      url: /capabilities/ott-streaming-delivery/
      via_parent: null
    credit: null
    layer: domain
    name: BoxCast
    provider: boxcast
    says: lists BoxCast as an integration
    source: https://www.planningcenter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.70
      key: AE-170.20.70
      name: Worship Song Licensing & Chord Charts
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: CCLI SongSelect
    provider: ccli
    says: lists CCLI SongSelect as an integration
    source: https://www.planningcenter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Checkr
    provider: checkr
    says: lists Checkr as an integration
    source: https://www.planningcenter.com/integrations
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
    name: Clearstream (church texting)
    provider: clearstream-io
    says: lists Clearstream (church texting) as an integration
    source: https://www.planningcenter.com/integrations
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
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://www.planningcenter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: MinistrySafe
    provider: ministrysafe
    says: lists MinistrySafe as an integration
    source: https://www.planningcenter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.70
      key: AE-170.20.70
      name: Worship Song Licensing & Chord Charts
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: PraiseCharts
    provider: praisecharts
    says: lists PraiseCharts as an integration
    source: https://www.planningcenter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.40
      key: AE-170.10.40
      name: Live Presentation & Broadcast Control
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: domain
    name: ProPresenter (Renewed Vision)
    provider: renewed-vision
    says: lists ProPresenter (Renewed Vision) as an integration
    source: https://www.planningcenter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Protect My Ministry
    provider: protect-my-ministry
    says: lists Protect My Ministry as an integration
    source: https://www.planningcenter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.70
      key: AE-170.20.70
      name: Worship Song Licensing & Chord Charts
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: RehearsalMix
    provider: rehearsalmix
    says: lists RehearsalMix as an integration
    source: https://www.planningcenter.com/integrations
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
    name: Text In Church
    provider: text-in-church
    says: lists Text In Church as an integration
    source: https://www.planningcenter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Verified First
    provider: verified-first
    says: lists Verified First as an integration
    source: https://www.planningcenter.com/integrations
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
    source: https://www.planningcenter.com/integrations
    tier: declared
  kind: commercial
  name: Planning Center
  page: /applications/church-faith-management/planning-center/
  slug: planning-center
  url: https://www.planningcenter.com/
- anchor: tithely
  counts:
    declared: 11
    observed: 0
  evidence:
  - route: integrations page
    url: https://get.tithe.ly/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-943
      key: AE-943
      name: Church Management System Sync
      url: /capabilities/church-management-system-sync/
      via_parent: null
    credit: null
    layer: common
    name: Church Community Builder (Pushpay)
    provider: pushpay
    says: lists Church Community Builder (Pushpay) as an integration
    source: https://get.tithe.ly/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-943
      key: AE-943
      name: Church Management System Sync
      url: /capabilities/church-management-system-sync/
      via_parent: null
    credit: null
    layer: common
    name: Elvanto
    provider: elvanto
    says: lists Elvanto as an integration
    source: https://get.tithe.ly/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-190.30.20
      key: AE-190.30.20
      name: Crypto Exchanges & Wallets
      url: /capabilities/retail-investing/
      via_parent: Retail Investing
    credit: null
    layer: domain
    name: Engiven
    provider: engiven
    says: lists Engiven as an integration
    source: https://get.tithe.ly/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-943
      key: AE-943
      name: Church Management System Sync
      url: /capabilities/church-management-system-sync/
      via_parent: null
    credit: null
    layer: common
    name: FellowshipOne
    provider: fellowshipone
    says: lists FellowshipOne as an integration
    source: https://get.tithe.ly/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-943
      key: AE-943
      name: Church Management System Sync
      url: /capabilities/church-management-system-sync/
      via_parent: null
    credit: null
    layer: common
    name: MinistryPlatform
    provider: ministryplatform
    says: lists MinistryPlatform as an integration
    source: https://get.tithe.ly/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: MinistrySafe
    provider: ministrysafe
    says: lists MinistrySafe as an integration
    source: https://get.tithe.ly/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-943
      key: AE-943
      name: Church Management System Sync
      url: /capabilities/church-management-system-sync/
      via_parent: null
    credit: null
    layer: common
    name: Planning Center
    provider: planning-center
    says: lists Planning Center as an integration
    source: https://get.tithe.ly/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks Online
    provider: quickbooks
    says: lists QuickBooks Online as an integration
    source: https://get.tithe.ly/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-943
      key: AE-943
      name: Church Management System Sync
      url: /capabilities/church-management-system-sync/
      via_parent: null
    credit: null
    layer: common
    name: Rock RMS
    provider: rock-rms
    says: lists Rock RMS as an integration
    source: https://get.tithe.ly/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://get.tithe.ly/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-943
      key: AE-943
      name: Church Management System Sync
      url: /capabilities/church-management-system-sync/
      via_parent: null
    credit: null
    layer: common
    name: Shelby Systems
    provider: shelby-systems
    says: lists Shelby Systems as an integration
    source: https://get.tithe.ly/integrations
    tier: declared
  kind: commercial
  name: Tithe.ly
  page: /applications/church-faith-management/tithe-ly/
  slug: tithe-ly
  url: https://get.tithe.ly/
- anchor: pushpay
  counts:
    declared: 20
    observed: 0
  evidence:
  - route: integrations page
    url: https://pushpay.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Aplos
    provider: aplos
    says: lists Aplos as an integration
    source: https://pushpay.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60.10
      key: AE-150.60.10
      name: Async Video Messaging
      url: /capabilities/video-calling/
      via_parent: Video Calling
    credit: null
    layer: common
    name: BombBomb
    provider: bombbomb
    says: lists BombBomb as an integration
    source: https://pushpay.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Checkr
    provider: checkr
    says: lists Checkr as an integration
    source: https://pushpay.com/integrations/
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
    name: Clearstream (church texting)
    provider: clearstream-io
    says: lists Clearstream (church texting) as an integration
    source: https://pushpay.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-190.30.20
      key: AE-190.30.20
      name: Crypto Exchanges & Wallets
      url: /capabilities/retail-investing/
      via_parent: Retail Investing
    credit: null
    layer: domain
    name: Engiven
    provider: engiven
    says: lists Engiven as an integration
    source: https://pushpay.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-943
      key: AE-943
      name: Church Management System Sync
      url: /capabilities/church-management-system-sync/
      via_parent: null
    credit: null
    layer: common
    name: FellowshipOne
    provider: fellowshipone
    says: lists FellowshipOne as an integration
    source: https://pushpay.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gusto
    provider: gusto
    says: lists Gusto as an integration
    source: https://pushpay.com/integrations/
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
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://pushpay.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-943
      key: AE-943
      name: Church Management System Sync
      url: /capabilities/church-management-system-sync/
      via_parent: null
    credit: null
    layer: common
    name: MinistryPlatform
    provider: ministryplatform
    says: lists MinistryPlatform as an integration
    source: https://pushpay.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: MinistrySafe
    provider: ministrysafe
    says: lists MinistrySafe as an integration
    source: https://pushpay.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-943
      key: AE-943
      name: Church Management System Sync
      url: /capabilities/church-management-system-sync/
      via_parent: null
    credit: null
    layer: common
    name: Planning Center
    provider: planning-center
    says: lists Planning Center as an integration
    source: https://pushpay.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3740.20
      key: ott-streaming-delivery
      name: OTT & Streaming Delivery
      url: /capabilities/ott-streaming-delivery/
      via_parent: null
    credit: null
    layer: domain
    name: PRAY.COM
    provider: pray-com
    says: lists PRAY.COM as an integration
    source: https://pushpay.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Protect My Ministry
    provider: protect-my-ministry
    says: lists Protect My Ministry as an integration
    source: https://pushpay.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks
    provider: quickbooks
    says: lists QuickBooks as an integration
    source: https://pushpay.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3740.20
      key: ott-streaming-delivery
      name: OTT & Streaming Delivery
      url: /capabilities/ott-streaming-delivery/
      via_parent: null
    credit: null
    layer: domain
    name: Resi
    provider: resi
    says: lists Resi as an integration
    source: https://pushpay.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-943
      key: AE-943
      name: Church Management System Sync
      url: /capabilities/church-management-system-sync/
      via_parent: null
    credit: null
    layer: common
    name: Rock RMS
    provider: rock-rms
    says: lists Rock RMS as an integration
    source: https://pushpay.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Sage Intacct
    provider: sage-intacct
    says: lists Sage Intacct as an integration
    source: https://pushpay.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Shelby Systems
    provider: shelby-systems
    says: lists Shelby Systems as an integration
    source: https://pushpay.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Subsplash
    provider: subsplash
    says: lists Subsplash as an integration
    source: https://pushpay.com/integrations/
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
    name: Text-Em-All
    provider: text-em-all
    says: lists Text-Em-All as an integration
    source: https://pushpay.com/integrations/
    tier: declared
  kind: commercial
  name: Pushpay
  page: /applications/church-faith-management/pushpay/
  slug: pushpay
  url: https://pushpay.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: church-faith-management
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Lifestyle
  store: google-play
  url: https://play.google.com/store/apps/category/LIFESTYLE
- category: Lifestyle
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Reference
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Church Management Software
  store: capterra
  url: https://www.capterra.com/church-management-software/
- category: Church Management Software
  store: g2
  url: https://www.g2.com/categories/church-management
- category: Nonprofit
  store: zapier
  url: https://zapier.com/apps
name: Church & Faith Community Management
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: texting congregations
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: Push Notifications
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: Transactional Email
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: online giving gateways
- capability:
    attribution: Turbo EA
    id: BC-300.10.20
    key: BC-300.10.20
    name: Candidate Screening and Selection
    url: /capabilities/talent-acquisition-management/
    via_parent: Talent Acquisition Management
  fit: exact
  layer: domain
  why: volunteer and child-safety background checks
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: Tenant Identity Federation
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: Social & Federated Login
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.30
    key: AE-120.10.30
    name: Address Validation & Autocomplete
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: common
  why: Address Validation
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: common
  why: IP Geolocation
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  fit: nearest
  layer: common
  why: file storage (nearest)
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: Hosted LLM Inference
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.20
    key: AE-110.40.20
    name: OCR & Document AI
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: agent
  why: check / form scanning
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: common
  why: Message bus
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: realtime-messaging
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  fit: exact
  layer: common
  why: Realtime messaging
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: Email Marketing Sends
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: Product usage analytics
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: common
  why: Avatars
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.40
    key: AE-170.10.40
    name: Live Presentation & Broadcast Control
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  fit: exact
  layer: domain
  why: 'Live Presentation & Broadcast Control: OpenLP, OBS Studio, ProPresenter (Renewed Vision)'
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  fit: nearest
  layer: common
  why: update checks (nearest)
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: gap
  layer: common
  why: ChMS-to-ChMS / app sync (Planning Center, Rock, MinistryPlatform, Elvanto...) has no capability node; nearest CRM, fit gap
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.50
    key: AE-170.60.50
    name: Scripture & Religious Text Content
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  fit: exact
  layer: domain
  why: 'Scripture & Religious Text Content: Bible Gateway, BibleServer, Bible Study Tools (Crosswalk)'
- capability:
    attribution: Turbo EA
    id: BC-3740.20
    key: ott-streaming-delivery
    name: OTT & Streaming Delivery
    url: /capabilities/ott-streaming-delivery/
    via_parent: null
  fit: exact
  layer: domain
  why: live-streamed services
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: Workflow Automation & iPaaS
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: domain
  why: contribution sync to fund accounting
- capability:
    attribution: API Evangelist extension
    id: AE-190.30.20
    key: AE-190.30.20
    name: Crypto Exchanges & Wallets
    url: /capabilities/retail-investing/
    via_parent: Retail Investing
  fit: nearest
  layer: domain
  why: crypto giving (nearest)
- capability:
    attribution: API Evangelist extension
    id: AE-150.60.10
    key: AE-150.60.10
    name: Async Video Messaging
    url: /capabilities/video-calling/
    via_parent: Video Calling
  fit: exact
  layer: common
  why: Async Video Messaging
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  fit: exact
  layer: domain
  why: staff payroll
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: API Evangelist extension
    id: AE-943
    key: AE-943
    name: Church Management System Sync
    url: /capabilities/church-management-system-sync/
    via_parent: null
  fit: exact
  layer: common
  why: Planning Center, Rock RMS, Elvanto (Church Management System Sync)
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.70
    key: AE-170.20.70
    name: Worship Song Licensing & Chord Charts
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  fit: exact
  layer: domain
  why: CCLI SongSelect, PraiseCharts, RehearsalMix (Worship Song Licensing & Chord Charts)
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.8
      apps:
      - Planning Center
      - Pushpay
      - Rock RMS
      band: thin
      in_catalog: true
      kin_score: 32.4
      mcp:
        status: none
      name: Checkr
      slug: checkr
      sources:
      - https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.Checkr
      - https://pushpay.com/integrations/
      - https://www.planningcenter.com/integrations
      status: profiled
      tags:
      - Background Checks
      - Compliance
      - Employment Screening
      - Human Resources
      tier: observed
      url: /providers/checkr/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Planning Center
      - Pushpay
      - Tithe.ly
      band: minimal
      in_catalog: true
      kin_score: 4.8
      mcp:
        status: unchecked
      name: MinistrySafe
      slug: ministrysafe
      sources:
      - https://get.tithe.ly/integrations
      - https://pushpay.com/integrations/
      - https://www.planningcenter.com/integrations
      status: profiled
      tags:
      - Child Safety
      - Education
      - Non-Profit
      - Training
      tier: declared
      url: /providers/ministrysafe/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Planning Center
      - Pushpay
      band: minimal
      in_catalog: true
      kin_score: 8.0
      mcp:
        status: unchecked
      name: Protect My Ministry
      slug: protect-my-ministry
      sources:
      - https://pushpay.com/integrations/
      - https://www.planningcenter.com/integrations
      status: profiled
      tags:
      - Background Checks
      - Child Safety Training
      - Church Screening
      - Volunteer Screening
      tier: declared
      url: /providers/protect-my-ministry/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Planning Center
      band: emerging
      in_catalog: true
      kin_score: 24.7
      mcp:
        status: none
      name: Verified First
      slug: verified-first
      sources:
      - https://www.planningcenter.com/integrations
      status: profiled
      tags:
      - Background Checks
      - Company
      - Screening
      - Verification
      tier: declared
      url: /providers/verified-first/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Pushpay
      - Tithe.ly
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks Online
      slug: quickbooks
      sources:
      - https://get.tithe.ly/integrations
      - https://pushpay.com/integrations/
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Pushpay
      band: thin
      in_catalog: true
      kin_score: 29.7
      mcp:
        status: none
      name: Aplos
      slug: aplos
      sources:
      - https://pushpay.com/integrations/
      status: profiled
      tags:
      - Accounting
      - Company
      - Non-Profit
      - Software
      tier: declared
      url: /providers/aplos/
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - Pushpay
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: Sage Intacct
      slug: sage-intacct
      sources:
      - https://pushpay.com/integrations/
      status: profiled
      tags:
      - Accounting
      - ERP
      - Financial Management
      - General Ledger
      tier: declared
      url: /providers/sage-intacct/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Pushpay
      band: minimal
      in_catalog: true
      kin_score: 5.5
      mcp: &id001
        status: unchecked
      name: Shelby Systems
      slug: shelby-systems
      sources:
      - https://pushpay.com/integrations/
      status: profiled
      tags: &id002
      - Church Accounting
      - Church Management
      - Ministry Software
      - Online Giving
      tier: declared
      url: /providers/shelby-systems/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.70
      key: AE-170.20.70
      name: Worship Song Licensing & Chord Charts
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenLP
      - Planning Center
      band: thin
      in_catalog: true
      kin_score: 27.2
      mcp:
        status: unchecked
      name: CCLI SongSelect
      slug: ccli
      sources:
      - https://gitlab.com/openlp/openlp/-/tree/master/openlp/plugins/songs/lib
      - https://www.planningcenter.com/integrations
      status: profiled
      tags:
      - Company
      - Licensing
      - Music
      - Worship
      tier: observed
      url: /providers/ccli/
    - agent_band: agent-ready
      agent_readiness: 37.2
      apps:
      - Planning Center
      band: thin
      in_catalog: true
      kin_score: 39.0
      mcp:
        status: unchecked
      name: PraiseCharts
      slug: praisecharts
      sources:
      - https://www.planningcenter.com/integrations
      status: profiled
      tags:
      - Christian
      - Music
      - Sheet Music
      - Worship
      tier: declared
      url: /providers/praisecharts/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Planning Center
      band: thin
      in_catalog: true
      kin_score: 28.5
      mcp:
        status: unchecked
      name: RehearsalMix
      slug: rehearsalmix
      sources:
      - https://www.planningcenter.com/integrations
      status: profiled
      tags:
      - Audio
      - Collaboration
      - Music
      - Rehearsal
      tier: declared
      url: /providers/rehearsalmix/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.40
      key: AE-170.10.40
      name: Live Presentation & Broadcast Control
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    providers:
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - OpenLP
      band: emerging
      in_catalog: true
      kin_score: 13.2
      mcp:
        status: unchecked
      name: OBS Studio
      slug: obs-studio
      sources:
      - https://gitlab.com/openlp/openlp/-/tree/master/openlp/plugins/obs_studio
      status: profiled
      tags:
      - Live Streaming
      - Open-source software
      - Video Recording
      tier: observed
      url: /providers/obs-studio/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - ChurchCRM
      band: minimal
      in_catalog: true
      kin_score: 9.4
      mcp:
        status: unchecked
      name: OpenLP
      slug: openlp
      sources:
      - https://github.com/ChurchCRM/CRM/tree/master/src/plugins/core/openlp
      status: profiled
      tags:
      - Company
      - Open Source
      - Presentation
      - Worship
      tier: observed
      url: /providers/openlp/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Planning Center
      band: emerging
      in_catalog: true
      kin_score: 16.4
      mcp:
        status: unchecked
      name: ProPresenter (Renewed Vision)
      slug: renewed-vision
      sources:
      - https://www.planningcenter.com/integrations
      status: profiled
      tags:
      - Company
      - Live Production
      - Media
      - Presentation
      tier: declared
      url: /providers/renewed-vision/
  - capability:
      attribution: Turbo EA
      id: BC-3740.20
      key: ott-streaming-delivery
      name: OTT & Streaming Delivery
      url: /capabilities/ott-streaming-delivery/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Planning Center
      band: thin
      in_catalog: true
      kin_score: 35.1
      mcp:
        status: none
      name: BoxCast
      slug: boxcast
      sources:
      - https://www.planningcenter.com/integrations
      status: profiled
      tags:
      - Company
      - Live
      - Streaming
      - Video
      tier: declared
      url: /providers/boxcast/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Pushpay
      band: emerging
      in_catalog: true
      kin_score: 15.6
      mcp:
        status: unchecked
      name: PRAY.COM
      slug: pray-com
      sources:
      - https://pushpay.com/integrations/
      status: profiled
      tags:
      - Bible
      - Company
      - Faith
      - Prayer
      tier: declared
      url: /providers/pray-com/
    - agent_band: null
      agent_readiness: null
      apps:
      - Pushpay
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Resi
      slug: resi
      sources:
      - https://pushpay.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.50
      key: AE-170.60.50
      name: Scripture & Religious Text Content
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenLP
      band: emerging
      in_catalog: true
      kin_score: 14.7
      mcp:
        status: unchecked
      name: Bible Gateway
      slug: biblegateway
      sources:
      - https://gitlab.com/openlp/openlp/-/blob/master/openlp/plugins/bibles/lib/importers/http.py
      status: profiled
      tags:
      - Audio Bibles
      - Bible
      - Online Scripture
      - Reading Plans
      tier: observed
      url: /providers/biblegateway/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenLP
      band: minimal
      in_catalog: true
      kin_score: 6.7
      mcp:
        status: unchecked
      name: Bible Study Tools (Crosswalk)
      slug: biblestudytools
      sources:
      - https://gitlab.com/openlp/openlp/-/blob/master/openlp/plugins/bibles/lib/importers/http.py
      status: profiled
      tags:
      - Bible
      - Company
      - Scripture
      - Study Tools
      tier: observed
      url: /providers/biblestudytools/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - OpenLP
      band: minimal
      in_catalog: true
      kin_score: 5.4
      mcp:
        status: unchecked
      name: BibleServer
      slug: bibleserver
      sources:
      - https://gitlab.com/openlp/openlp/-/blob/master/openlp/plugins/bibles/lib/importers/http.py
      status: profiled
      tags:
      - Bible
      - Community
      - Religion
      - Study
      tier: observed
      url: /providers/bibleserver/
  - capability:
      attribution: API Evangelist extension
      id: AE-190.30.20
      key: AE-190.30.20
      name: Crypto Exchanges & Wallets
      url: /capabilities/retail-investing/
      via_parent: Retail Investing
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Pushpay
      - Tithe.ly
      band: emerging
      in_catalog: true
      kin_score: 19.6
      mcp:
        status: unchecked
      name: Engiven
      slug: engiven
      sources:
      - https://get.tithe.ly/integrations
      - https://pushpay.com/integrations/
      status: profiled
      tags:
      - CryptoDonations
      - Enterprise Software
      - NonprofitTech
      - Stock Donations
      tier: declared
      url: /providers/engiven/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Rock RMS
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal Payflow Pro
      slug: paypal
      sources:
      - https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.PayFlowPro
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-native
      agent_readiness: 43.6
      apps:
      - Rock RMS
      band: developing
      in_catalog: true
      kin_score: 50.1
      mcp:
        status: none
      name: NMI
      slug: nmi
      sources:
      - https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.NMI
      status: profiled
      tags:
      - Payment Gateway
      - Payment Processing
      - Payments
      - Tokenization
      tier: observed
      url: /providers/nmi/
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.7
      apps:
      - Pushpay
      band: developing
      in_catalog: true
      kin_score: 44.9
      mcp:
        status: none
      name: Gusto
      slug: gusto
      sources:
      - https://pushpay.com/integrations/
      status: profiled
      tags:
      - Benefits
      - Enterprise Software
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/gusto/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-943
      key: AE-943
      name: Church Management System Sync
      url: /capabilities/church-management-system-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - OpenLP
      - Pushpay
      - Tithe.ly
      band: thin
      in_catalog: true
      kin_score: 33.9
      mcp:
        source: https://mcp.planningcenteronline.com/mcp
        status: verified
      name: Planning Center
      slug: planning-center
      sources:
      - https://get.tithe.ly/integrations
      - https://gitlab.com/openlp/openlp/-/tree/master/openlp/plugins/planningcenter
      - https://pushpay.com/integrations/
      status: profiled
      tags:
      - ChMS
      - Church Management
      - Faith
      - Giving
      tier: observed
      url: /providers/planning-center/
    - agent_band: agent-aware
      agent_readiness: 18.0
      apps:
      - Pushpay
      - Tithe.ly
      band: emerging
      in_catalog: true
      kin_score: 25.6
      mcp:
        status: unchecked
      name: Rock RMS
      slug: rock-rms
      sources:
      - https://get.tithe.ly/integrations
      - https://pushpay.com/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Church Management
      - Company
      - Open Source
      tier: declared
      url: /providers/rock-rms/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Pushpay
      - Tithe.ly
      band: emerging
      in_catalog: true
      kin_score: 15.6
      mcp:
        status: unchecked
      name: FellowshipOne
      slug: fellowshipone
      sources:
      - https://get.tithe.ly/integrations
      - https://pushpay.com/integrations/
      status: profiled
      tags:
      - Church
      - Cloud
      - Management
      - Software
      tier: declared
      url: /providers/fellowshipone/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Pushpay
      - Tithe.ly
      band: minimal
      in_catalog: true
      kin_score: 9.1
      mcp:
        status: unchecked
      name: MinistryPlatform
      slug: ministryplatform
      sources:
      - https://get.tithe.ly/integrations
      - https://pushpay.com/integrations/
      status: profiled
      tags:
      - Church
      - Company
      - Integration
      - ManagementSoftware
      tier: declared
      url: /providers/ministryplatform/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Tithe.ly
      band: developing
      in_catalog: true
      kin_score: 43.8
      mcp:
        status: unchecked
      name: Elvanto
      slug: elvanto
      sources:
      - https://get.tithe.ly/integrations
      status: profiled
      tags:
      - Church Management
      - Cloud
      - Software
      - Software-as-a-Service
      tier: declared
      url: /providers/elvanto/
    - agent_band: agent-aware
      agent_readiness: 21.0
      apps:
      - Tithe.ly
      band: emerging
      in_catalog: true
      kin_score: 25.8
      mcp:
        status: unchecked
      name: Church Community Builder (Pushpay)
      slug: pushpay
      sources:
      - https://get.tithe.ly/integrations
      status: profiled
      tags:
      - Church Giving
      - Church Management Software
      - Digital Giving
      - Mobile App
      tier: declared
      url: /providers/pushpay/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Tithe.ly
      band: minimal
      in_catalog: true
      kin_score: 5.5
      mcp: *id001
      name: Shelby Systems
      slug: shelby-systems
      sources:
      - https://get.tithe.ly/integrations
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/shelby-systems/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Planning Center
      - Pushpay
      band: thin
      in_catalog: true
      kin_score: 37.5
      mcp:
        status: unchecked
      name: Clearstream (church texting)
      slug: clearstream-io
      sources:
      - https://pushpay.com/integrations/
      - https://www.planningcenter.com/integrations
      status: profiled
      tags:
      - Church
      - Company
      - Messaging
      - SMS
      tier: declared
      url: /providers/clearstream-io/
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - Rock RMS
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Communication/Transport
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-ready
      agent_readiness: 40.0
      apps:
      - ChurchCRM
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/Vonage/vonage-mcp-server-documentation
        status: verified
      name: Vonage
      slug: vonage
      sources:
      - https://github.com/ChurchCRM/CRM/tree/master/src/plugins/core/vonage
      status: profiled
      tags:
      - Communications
      - Messaging
      - Telecommunications
      - Video Conferencing
      tier: observed
      url: /providers/vonage/
    - agent_band: agent-ready
      agent_readiness: 37.8
      apps:
      - Planning Center
      band: developing
      in_catalog: true
      kin_score: 43.1
      mcp:
        status: unchecked
      name: Text In Church
      slug: text-in-church
      sources:
      - https://www.planningcenter.com/integrations
      status: profiled
      tags:
      - Church
      - Communications
      - Company
      - Messaging
      tier: declared
      url: /providers/text-in-church/
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - Pushpay
      band: thin
      in_catalog: true
      kin_score: 35.8
      mcp:
        status: unchecked
      name: Text-Em-All
      slug: text-em-all
      sources:
      - https://pushpay.com/integrations/
      status: profiled
      tags:
      - Communications
      - Employee-Owned
      - Marketing
      - SMS
      tier: declared
      url: /providers/text-em-all/
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
      - ChurchCRM
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://github.com/ChurchCRM/CRM/tree/master/src/plugins/core/google-analytics
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
      - Planning Center
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.PlanningCenter/latest/
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
      - ChurchCRM
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://github.com/ChurchCRM/CRM/blob/master/package.json
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Planning Center
      band: strong
      in_catalog: true
      kin_score: 57.0
      mcp:
        source: https://support.pendo.io/hc/en-us/articles/41102236924955
        status: verified
      name: Pendo
      slug: pendoio
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.PlanningCenter/latest/
      status: profiled
      tags:
      - Company
      - Digital Adoption
      - Product Analytics
      - Product Experience
      tier: observed
      url: /providers/pendoio/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - ChurchCRM
      - Planning Center
      - Pushpay
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp: &id005
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://github.com/ChurchCRM/CRM/tree/master/src/plugins/core/mailchimp
      - https://pushpay.com/integrations/
      - https://www.planningcenter.com/integrations
      status: profiled
      tags: &id006
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: observed
      url: /providers/mailchimp/
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
      - Planning Center
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.churchcenter/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Planning Center
      band: exemplar
      in_catalog: true
      kin_score: 76.3
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.churchcenter/latest/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Planning Center
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id003
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.PlanningCenter/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - Rock RMS
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: Twitter / X
      slug: x
      sources:
      - https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Security/Authentication
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: observed
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Rock RMS
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Security/Authentication
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Rock RMS
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Security/Authentication
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
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
      - Rock RMS
      band: exemplar
      in_catalog: true
      kin_score: 84.0
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.SendGrid
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Rock RMS
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp: *id005
      name: Mandrill (Mailchimp Transactional)
      slug: mailchimp
      sources:
      - https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.Mandrill
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/mailchimp/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Rock RMS
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.Mailgun
      status: profiled
      tags:
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailgun/
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Rock RMS
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Storage/Provider
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
      - Rock RMS
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Storage/Provider
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
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
      - Tithe.ly
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://get.tithe.ly/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Pushpay
      band: emerging
      in_catalog: true
      kin_score: 13.1
      mcp:
        status: none
      name: Subsplash
      slug: subsplash
      sources:
      - https://pushpay.com/integrations/
      status: profiled
      tags:
      - Church
      - Giving
      - Ministry
      - Non-Profit
      tier: declared
      url: /providers/subsplash/
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
      - Rock RMS
      band: thin
      in_catalog: true
      kin_score: 31.5
      mcp:
        status: none
      name: MaxMind
      slug: maxmind
      sources:
      - https://github.com/SparkDevNetwork/Rock/blob/develop/Rock/Rock.csproj
      status: profiled
      tags:
      - Fraud Prevention
      - Geolocation
      - IP Intelligence
      - Risk Scoring
      tier: observed
      url: /providers/maxmind/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Rock RMS
      band: thin
      in_catalog: true
      kin_score: 27.1
      mcp:
        source: https://mcp.ipregistry.co/mcp
        status: verified
      name: IPregistry
      slug: ipregistry
      sources:
      - https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/IpAddress
      status: profiled
      tags:
      - ASN
      - IP Address
      - IP Geolocation
      - Threat Intelligence
      tier: observed
      url: /providers/ipregistry/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.30
      key: AE-120.10.30
      name: Address Validation & Autocomplete
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.3
      apps:
      - Rock RMS
      band: thin
      in_catalog: true
      kin_score: 37.1
      mcp:
        source: https://www.smarty.com/docs/mcp
        status: verified
      name: SmartyStreets
      slug: smarty
      sources:
      - https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Address
      status: profiled
      tags:
      - Address Autocomplete
      - Address Verification
      - Geocoding
      - ZIP Code
      tier: observed
      url: /providers/smarty/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60.10
      key: AE-150.60.10
      name: Async Video Messaging
      url: /capabilities/video-calling/
      via_parent: Video Calling
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Pushpay
      band: developing
      in_catalog: true
      kin_score: 42.4
      mcp:
        status: unchecked
      name: BombBomb
      slug: bombbomb
      sources:
      - https://pushpay.com/integrations/
      status: profiled
      tags:
      - Company
      - Marketing
      - Sales
      - Video Messaging
      tier: declared
      url: /providers/bombbomb/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - ChurchCRM
      band: developing
      in_catalog: true
      kin_score: 41.2
      mcp:
        source: https://github.com/Automattic/mcp-server-gravatar
        status: verified
      name: Gravatar
      slug: gravatar
      sources:
      - https://github.com/ChurchCRM/CRM/tree/master/src/plugins/core/gravatar
      status: profiled
      tags:
      - Avatars
      - Identity
      - Profiles
      - Social
      tier: observed
      url: /providers/gravatar/
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
      - Planning Center
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.churchcenter/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Rock RMS
      band: exemplar
      in_catalog: true
      kin_score: 77.2
      mcp:
        source: https://raw.githubusercontent.com/microsoft/mcp/main/servers/Azure.Mcp.Server/README.md
        status: verified
      name: Azure Service Bus
      slug: azure-service-bus
      sources:
      - https://github.com/SparkDevNetwork/Rock/blob/develop/Rock/Rock.csproj
      status: profiled
      tags:
      - Cloud
      - Enterprise
      - Message Broker
      - Microsoft Azure
      tier: observed
      url: /providers/azure-service-bus/
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
      - Rock RMS
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id003
      name: Firebase Cloud Messaging
      slug: google-firebase
      sources:
      - https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Communication/Transport
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: realtime-messaging
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.2
      apps:
      - Rock RMS
      band: exemplar
      in_catalog: true
      kin_score: 69.3
      mcp:
        source: https://learn.microsoft.com/en-us/azure/developer/azure-mcp-server/tools/azure-signalr
        status: verified
      name: Azure SignalR Service
      slug: microsoft-azure-signalr
      sources:
      - https://github.com/SparkDevNetwork/Rock/blob/develop/Rock/Rock.csproj
      status: profiled
      tags:
      - Messaging
      - Real-Time
      - SignalR
      - WebSocket
      tier: observed
      url: /providers/microsoft-azure-signalr/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - Planning Center
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Pusher
      slug: pusher
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ministrycentered.PlanningCenter/latest/
      status: profiled
      tags:
      - Pub/Sub
      - Push Notifications
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/pusher/
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - ChurchCRM
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/ChurchCRM/CRM/blob/master/src/composer.json
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.5
      apps:
      - Rock RMS
      band: exemplar
      in_catalog: true
      kin_score: 71.8
      mcp:
        source: https://auth0.com/docs/get-started/auth0-mcp-server
        status: verified
      name: Auth0
      slug: auth0
      sources:
      - https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.Security.Authentication.Auth0
      status: profiled
      tags:
      - AI Agents
      - Auth0
      - Authentication
      - Authorization
      tier: observed
      url: /providers/auth0/
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
      - Planning Center
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://www.planningcenter.com/integrations
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
      - Rock RMS
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.AI.OpenAI
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.8
      apps:
      - Rock RMS
      band: strong
      in_catalog: true
      kin_score: 54.5
      mcp:
        status: unknown
      name: Azure AI Document Intelligence
      slug: azure-document-intelligence
      sources:
      - https://github.com/SparkDevNetwork/Rock/blob/develop/Rock/Rock.csproj
      status: profiled
      tags:
      - Artificial Intelligence
      - Document AI
      - Intelligent Document Processing
      - Microsoft Azure
      tier: observed
      url: /providers/azure-document-intelligence/
  layer: agent
summary:
  coverage_pct: 98.5
  declared_only: 27
  distinct_providers: 65
  in_catalog: 64
  mcp:
    documented: 0
    none: 15
    unchecked: 24
    verified: 25
  mcp_verified: 25
  mean_kin_score: 44.1
  observed: 38
  queued: 1
  reference_apps: 6
title: 'Church & Faith Community Management: application blueprint'
---
