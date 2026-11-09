---
access: understanding
agent_layer:
- app: Jobber
  finding: Jobber lists Claude and ChatGPT apps in its App Marketplace (Jobber inside the assistants, not an LLM it consumes)
  source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
  tier: declared
- app: Housecall Pro
  finding: Amazon Alexa skill listed as an integration
  source: https://www.housecallpro.com/features/integrations/
  tier: declared
apps:
- anchor: servicetitan
  counts:
    declared: 3
    observed: 0
  evidence:
  - route: documentation
    url: https://help.servicetitan.com/docs/accounting-integrations-overview
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: QuickBooks Desktop/Online
    provider: quickbooks
    says: lists QuickBooks Desktop/Online as an integration
    source: https://help.servicetitan.com/docs/accounting-integrations-overview
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Sage Intacct
    provider: sage-intacct
    says: lists Sage Intacct as an integration
    source: https://help.servicetitan.com/docs/accounting-integrations-overview
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Xero
    provider: xero
    says: lists Xero as an integration
    source: https://help.servicetitan.com/docs/accounting-integrations-overview
    tier: declared
  kind: commercial
  name: ServiceTitan
  page: /applications/field-service/servicetitan/
  slug: servicetitan
  url: https://www.servicetitan.com/
- anchor: jobber
  counts:
    declared: 26
    observed: 8
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.getjobber.jobber/latest/
  - route: integrations page
    url: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.getjobber.jobber/latest/
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
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.getjobber.jobber/latest/
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
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.getjobber.jobber/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.getjobber.jobber/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.getjobber.jobber/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: ships the Google Tag Manager SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.getjobber.jobber/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Huawei Mobile Services (HMS) Core
    provider: huawei-mobile-services
    says: ships the Huawei Mobile Services (HMS) Core SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.getjobber.jobber/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.getjobber.jobber/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.10
      key: AE-200.50.10
      name: Home-Services Lead Marketplaces
      url: /capabilities/home-services/
      via_parent: Home Services
    credit: null
    layer: domain
    name: Angi
    provider: angi
    says: lists Angi as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Azuga Fleet
    provider: azuga
    says: lists Azuga Fleet as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: common
    name: Broadly
    provider: broadly
    says: lists Broadly as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: common
    name: CallRail
    provider: callrail
    says: lists CallRail as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: domain
    name: CompanyCam
    provider: companycam
    says: lists CompanyCam as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    credit: null
    layer: common
    name: DocuSign
    provider: docusign
    says: lists DocuSign as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.20
      key: AE-120.20.20
      name: Satellite & Aerial Imagery
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: domain
    name: EagleView
    provider: eagleview
    says: lists EagleView as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: FleetSharp
    provider: fleetsharp
    says: lists FleetSharp as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Force Fleet Tracking (Mojio)
    provider: mojio
    says: lists Force Fleet Tracking (Mojio) as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1320
      key: credit-lending-management
      name: Credit & Lending Management
      url: /capabilities/credit-lending-management/
      via_parent: null
    credit: null
    layer: common
    name: Fundbox
    provider: fundbox
    says: lists Fundbox as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.10
      key: AE-200.50.10
      name: Home-Services Lead Marketplaces
      url: /capabilities/home-services/
      via_parent: Home Services
    credit: null
    layer: domain
    name: Google Local Services Ads
    provider: google-ads
    says: lists Google Local Services Ads as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: common
    name: Gusto
    provider: gusto
    says: lists Gusto as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.30
      key: contact-centre-operations-management
      name: Contact Centre Operations Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: null
    credit: null
    layer: common
    name: Hatch
    provider: hatch
    says: lists Hatch as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
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
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: common
    name: NiceJob
    provider: nicejob
    says: lists NiceJob as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: QuickBooks Online
    provider: quickbooks
    says: lists QuickBooks Online as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50
      key: AE-150.50
      name: Voice & Telephony
      url: /capabilities/voice-telephony/
      via_parent: null
    credit: null
    layer: common
    name: Quo (OpenPhone)
    provider: quo
    says: lists Quo (OpenPhone) as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.40.20
      key: BC-410.40.20
      name: Quote Generation
      url: /capabilities/quote-configuration-management/
      via_parent: Quote & Configuration Management
    credit: null
    layer: domain
    name: ResponsiBid
    provider: responsibid
    says: lists ResponsiBid as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-912
      key: AE-912
      name: Direct Mail APIs
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: common
    name: SendJim
    provider: sendjim
    says: lists SendJim as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-500.30
      key: purchase-order-management
      name: Purchase Order Management
      url: /capabilities/purchase-order-management/
      via_parent: null
    credit: null
    layer: domain
    name: The Home Depot
    provider: home-depot
    says: lists The Home Depot as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.10
      key: AE-200.50.10
      name: Home-Services Lead Marketplaces
      url: /capabilities/home-services/
      via_parent: Home Services
    credit: null
    layer: domain
    name: Thumbtack
    provider: thumbtack
    says: lists Thumbtack as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.40
      key: AE-140.30.40
      name: Point-of-Service Consumer Financing
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: Wisetack
    provider: wisetack
    says: lists Wisetack as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: common
    name: Wix
    provider: wix
    says: lists Wix as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Xero
    provider: xero
    says: lists Xero as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.10
      key: AE-200.50.10
      name: Home-Services Lead Marketplaces
      url: /capabilities/home-services/
      via_parent: Home Services
    credit: null
    layer: domain
    name: Yelp Leads
    provider: yelp
    says: lists Yelp Leads as an integration
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
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
    source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
    tier: declared
  kind: commercial
  name: Jobber
  page: /applications/field-service/jobber/
  slug: jobber
  url: https://getjobber.com/
- anchor: housecall-pro
  counts:
    declared: 26
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.housecallpro.com/features/integrations/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30
      key: AE-110.30
      name: Speech & Voice
      url: /capabilities/speech-voice/
      via_parent: null
    credit: null
    layer: agent
    name: Amazon Alexa
    provider: amazon
    says: lists Amazon Alexa as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.10
      key: AE-200.50.10
      name: Home-Services Lead Marketplaces
      url: /capabilities/home-services/
      via_parent: Home Services
    credit: null
    layer: domain
    name: Angi
    provider: angi
    says: lists Angi as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: common
    name: Broadly
    provider: broadly
    says: lists Broadly as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: common
    name: CallRail
    provider: callrail
    says: lists CallRail as an integration
    source: https://www.housecallpro.com/features/integrations/
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
    name: CHIIRP
    provider: chiirp
    says: lists CHIIRP as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: domain
    name: CompanyCam
    provider: companycam
    says: lists CompanyCam as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50
      key: AE-150.50
      name: Voice & Telephony
      url: /capabilities/voice-telephony/
      via_parent: null
    credit: null
    layer: common
    name: Emitrr
    provider: emitrr
    says: lists Emitrr as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Force by Mojio
    provider: mojio
    says: lists Force by Mojio as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1320
      key: credit-lending-management
      name: Credit & Lending Management
      url: /capabilities/credit-lending-management/
      via_parent: null
    credit: null
    layer: common
    name: Fundbox
    provider: fundbox
    says: lists Fundbox as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.50.10
      key: AE-140.50.10
      name: Gift Cards
      url: /capabilities/gift-cards-gifting-cashback/
      via_parent: Gift Cards, Gifting & Cashback
    credit: null
    layer: common
    name: Gift Up
    provider: gift-up
    says: lists Gift Up as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.10
      key: AE-200.50.10
      name: Home-Services Lead Marketplaces
      url: /capabilities/home-services/
      via_parent: Home Services
    credit: null
    layer: domain
    name: Google Local Services
    provider: google-ads
    says: lists Google Local Services as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: common
    name: Gusto
    provider: gusto
    says: lists Gusto as an integration
    source: https://www.housecallpro.com/features/integrations/
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
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2070.20
      key: BC-2070.20
      name: Fault Detection & Diagnostics Operations
      url: /capabilities/building-performance-management/
      via_parent: Building Performance Management
    credit: null
    layer: domain
    name: measureQuick
    provider: measurequick
    says: lists measureQuick as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: common
    name: NiceJob
    provider: nicejob
    says: lists NiceJob as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: common
    name: Podium
    provider: podium
    says: lists Podium as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-440.20.10
      key: BC-440.20.10
      name: Price Book Maintenance
      url: /capabilities/price-list-management/
      via_parent: Price List Management
    credit: null
    layer: domain
    name: Profit Rhino
    provider: profit-rhino
    says: lists Profit Rhino as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: QuickBooks
    provider: quickbooks
    says: lists QuickBooks as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.40.20
      key: BC-410.40.20
      name: Quote Generation
      url: /capabilities/quote-configuration-management/
      via_parent: Quote & Configuration Management
    credit: null
    layer: domain
    name: ResponsiBid
    provider: responsibid
    says: lists ResponsiBid as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.20
      key: AE-100.70.20
      name: Voice Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    credit: null
    layer: common
    name: Signpost
    provider: signpost
    says: lists Signpost as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: common
    name: Swell
    provider: swellcx
    says: lists Swell as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-440.20.10
      key: BC-440.20.10
      name: Price Book Maintenance
      url: /capabilities/price-list-management/
      via_parent: Price List Management
    credit: null
    layer: domain
    name: The New Flat Rate
    provider: the-new-flat-rate
    says: lists The New Flat Rate as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.10
      key: AE-200.50.10
      name: Home-Services Lead Marketplaces
      url: /capabilities/home-services/
      via_parent: Home Services
    credit: null
    layer: domain
    name: Thumbtack
    provider: thumbtack
    says: lists Thumbtack as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.40
      key: AE-140.30.40
      name: Point-of-Service Consumer Financing
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: Wisetack
    provider: wisetack
    says: lists Wisetack as an integration
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: common
    name: Yelp
    provider: yelp
    says: lists Yelp as an integration
    source: https://www.housecallpro.com/features/integrations/
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
    source: https://www.housecallpro.com/features/integrations/
    tier: declared
  kind: commercial
  name: Housecall Pro
  page: /applications/field-service/housecall-pro/
  slug: housecall-pro
  url: https://www.housecallpro.com/
- anchor: servicem8
  counts:
    declared: 8
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.servicem8.com/addons
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2440.20
      key: rostering-and-scheduling-management
      name: Rostering and Scheduling Management
      url: /capabilities/rostering-and-scheduling-management/
      via_parent: null
    credit: null
    layer: common
    name: Deputy
    provider: deputy
    says: lists Deputy as an integration
    source: https://www.servicem8.com/addons
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
    name: MailChimp
    provider: mailchimp
    says: lists MailChimp as an integration
    source: https://www.servicem8.com/addons
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: MYOB
    provider: myob
    says: lists MYOB as an integration
    source: https://www.servicem8.com/addons
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
    name: Office 365
    provider: microsoft-365
    says: lists Office 365 as an integration
    source: https://www.servicem8.com/addons
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: QuickBooks Online
    provider: quickbooks
    says: lists QuickBooks Online as an integration
    source: https://www.servicem8.com/addons
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
    name: Stripe Payments
    provider: stripe
    says: lists Stripe Payments as an integration
    source: https://www.servicem8.com/addons
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Xero
    provider: xero
    says: lists Xero as an integration
    source: https://www.servicem8.com/addons
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
    source: https://www.servicem8.com/addons
    tier: declared
  kind: commercial
  name: ServiceM8
  page: /applications/field-service/servicem8/
  slug: servicem8
  url: https://www.servicem8.com/
- anchor: workiz
  counts:
    declared: 16
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.workiz.com/integrations/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.10
      key: AE-200.50.10
      name: Home-Services Lead Marketplaces
      url: /capabilities/home-services/
      via_parent: Home Services
    credit: null
    layer: domain
    name: Angi Leads
    provider: angi
    says: lists Angi Leads as an integration
    source: https://www.workiz.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.30
      key: AE-150.50.30
      name: Virtual Receptionists & Answering Services
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: common
    name: AnswerConnect
    provider: answerconnect
    says: lists AnswerConnect as an integration
    source: https://www.workiz.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: domain
    name: CompanyCam
    provider: companycam
    says: lists CompanyCam as an integration
    source: https://www.workiz.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420.10
      key: dispatch-management
      name: Dispatch Management
      url: /capabilities/dispatch-management/
      via_parent: null
    credit: null
    layer: domain
    name: Dispatch.me
    provider: dispatch-me
    says: lists Dispatch.me as an integration
    source: https://www.workiz.com/integrations/
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
    name: Google Calendar
    provider: google-calendar
    says: lists Google Calendar as an integration
    source: https://www.workiz.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Intuit QuickBooks
    provider: quickbooks
    says: lists Intuit QuickBooks as an integration
    source: https://www.workiz.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Linxup
    provider: linxup
    says: lists Linxup as an integration
    source: https://www.workiz.com/integrations/
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
    source: https://www.workiz.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: common
    name: NiceJob
    provider: nicejob
    says: lists NiceJob as an integration
    source: https://www.workiz.com/integrations/
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
    source: https://www.workiz.com/integrations/
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
    name: SearchKings
    provider: searchkings
    says: lists SearchKings as an integration
    source: https://www.workiz.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.40
      key: AE-140.30.40
      name: Point-of-Service Consumer Financing
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: Sunbit
    provider: sunbit
    says: lists Sunbit as an integration
    source: https://www.workiz.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.10
      key: AE-200.50.10
      name: Home-Services Lead Marketplaces
      url: /capabilities/home-services/
      via_parent: Home Services
    credit: null
    layer: domain
    name: Thumbtack
    provider: thumbtack
    says: lists Thumbtack as an integration
    source: https://www.workiz.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.40
      key: AE-140.30.40
      name: Point-of-Service Consumer Financing
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: Wisetack
    provider: wisetack
    says: lists Wisetack as an integration
    source: https://www.workiz.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.10
      key: AE-200.50.10
      name: Home-Services Lead Marketplaces
      url: /capabilities/home-services/
      via_parent: Home Services
    credit: null
    layer: domain
    name: Yelp
    provider: yelp
    says: lists Yelp as an integration
    source: https://www.workiz.com/integrations/
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
    source: https://www.workiz.com/integrations/
    tier: declared
  kind: commercial
  name: Workiz
  page: /applications/field-service/workiz/
  slug: workiz
  url: https://www.workiz.com/
- anchor: tradify
  counts:
    declared: 4
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.tradifyhq.com/features/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Google Calendar
    provider: google-calendar
    says: lists Google Calendar as an integration
    source: https://www.tradifyhq.com/features/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: QuickBooks
    provider: quickbooks
    says: lists QuickBooks as an integration
    source: https://www.tradifyhq.com/features/integrations
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
    source: https://www.tradifyhq.com/features/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Xero
    provider: xero
    says: lists Xero as an integration
    source: https://www.tradifyhq.com/features/integrations
    tier: declared
  kind: commercial
  name: Tradify
  page: /applications/field-service/tradify/
  slug: tradify
  url: https://www.tradifyhq.com/
- anchor: oca-field-service-(odoo)
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: source code
    url: https://github.com/OCA/field-service/blob/19.0/fieldservice_google_map/__manifest__.py
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20
      key: AE-120.20
      name: Maps & Tiles
      url: /capabilities/maps-tiles/
      via_parent: null
    credit: null
    layer: common
    name: Google Maps
    provider: google-maps
    says: ships the Google Maps SDK or integration code
    source: https://github.com/OCA/field-service/blob/19.0/fieldservice_google_map/__manifest__.py
    tier: observed
  kind: self-hosted
  name: OCA Field Service (Odoo)
  page: /applications/field-service/oca-field-service-odoo/
  slug: oca-field-service-odoo
  url: https://github.com/OCA/field-service
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: field-service
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Field Service
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Commerce
  store: zapier
  url: https://zapier.com/apps
name: Field Service & Dispatch
needs:
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by Housecall Pro, Jobber, ServiceM8, ServiceTitan, Tradify, Workiz
- capability:
    attribution: API Evangelist extension
    id: AE-200.50.10
    key: AE-200.50.10
    name: Home-Services Lead Marketplaces
    url: /capabilities/home-services/
    via_parent: Home Services
  fit: exact
  layer: domain
  why: named by Housecall Pro, Jobber, Workiz
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: named by Jobber, Workiz
- capability:
    attribution: Turbo EA
    id: BC-2430.40
    key: fleet-telematics-and-monitoring
    name: Fleet Telematics and Monitoring
    url: /capabilities/fleet-telematics-and-monitoring/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Housecall Pro, Jobber, Workiz
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.10
    key: AE-150.50.10
    name: Programmable Voice
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  fit: exact
  layer: common
  why: named by Housecall Pro, Jobber
- capability:
    attribution: API Evangelist extension
    id: AE-150.50
    key: AE-150.50
    name: Voice & Telephony
    url: /capabilities/voice-telephony/
    via_parent: null
  fit: exact
  layer: common
  why: named by Housecall Pro, Jobber
- capability:
    attribution: Turbo EA
    id: BC-150.10.30
    key: BC-150.10.30
    name: Contract Execution Management
    url: /capabilities/contract-management/
    via_parent: Contract Management
  fit: exact
  layer: common
  why: named by Jobber
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.20
    key: AE-120.20.20
    name: Satellite & Aerial Imagery
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: domain
  why: named by Jobber
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by Housecall Pro, Jobber
- capability:
    attribution: Turbo EA
    id: BC-500.30
    key: purchase-order-management
    name: Purchase Order Management
    url: /capabilities/purchase-order-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: named by Jobber
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by Jobber
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Housecall Pro, Jobber, Workiz
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.40
    key: AE-140.30.40
    name: Point-of-Service Consumer Financing
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  fit: exact
  layer: domain
  why: named by Housecall Pro, Jobber, Workiz
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: named by Housecall Pro, Jobber, ServiceM8, Workiz
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: named by Housecall Pro, Jobber, ServiceM8, Workiz
- capability:
    attribution: Turbo EA
    id: BC-430.30
    key: contact-centre-operations-management
    name: Contact Centre Operations Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: null
  fit: nearest
  layer: common
  why: named by Jobber, Workiz
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  fit: exact
  layer: common
  why: named by Housecall Pro, Jobber, Workiz
- capability:
    attribution: API Evangelist extension
    id: AE-912
    key: AE-912
    name: Direct Mail APIs
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: exact
  layer: common
  why: named by Jobber
- capability:
    attribution: Turbo EA
    id: BC-440.20.10
    key: BC-440.20.10
    name: Price Book Maintenance
    url: /capabilities/price-list-management/
    via_parent: Price List Management
  fit: exact
  layer: domain
  why: named by Housecall Pro
- capability:
    attribution: API Evangelist extension
    id: AE-140.50.10
    key: AE-140.50.10
    name: Gift Cards
    url: /capabilities/gift-cards-gifting-cashback/
    via_parent: Gift Cards, Gifting & Cashback
  fit: exact
  layer: common
  why: named by Housecall Pro
- capability:
    attribution: Turbo EA
    id: BC-2070.20
    key: BC-2070.20
    name: Fault Detection & Diagnostics Operations
    url: /capabilities/building-performance-management/
    via_parent: Building Performance Management
  fit: exact
  layer: domain
  why: named by Housecall Pro
- capability:
    attribution: API Evangelist extension
    id: AE-100.70.20
    key: AE-100.70.20
    name: Voice Agents
    url: /capabilities/vertical-agents/
    via_parent: Vertical Agents
  fit: exact
  layer: common
  why: named by Housecall Pro
- capability:
    attribution: API Evangelist extension
    id: AE-110.30
    key: AE-110.30
    name: Speech & Voice
    url: /capabilities/speech-voice/
    via_parent: null
  fit: exact
  layer: agent
  why: named by Housecall Pro
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by ServiceM8, Tradify
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: common
  why: named by ServiceM8, Tradify, Workiz
- capability:
    attribution: Turbo EA
    id: BC-2440.20
    key: rostering-and-scheduling-management
    name: Rostering and Scheduling Management
    url: /capabilities/rostering-and-scheduling-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by ServiceM8
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: named by Workiz
- capability:
    attribution: Turbo EA
    id: BC-2420.10
    key: dispatch-management
    name: Dispatch Management
    url: /capabilities/dispatch-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Workiz
- capability:
    attribution: API Evangelist extension
    id: AE-120.20
    key: AE-120.20
    name: Maps & Tiles
    url: /capabilities/maps-tiles/
    via_parent: null
  fit: exact
  layer: common
  why: named by OCA Field Service (Odoo)
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: usage analytics SDKs seen in the Android builds
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: attribution and deep-link SDKs seen in the Android builds
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash and error reporting SDKs seen in the Android builds
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: tag management SDK seen in the Android builds
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: nearest
  layer: common
  why: mobile services SDK seen in an Android build
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-200.50.10
      key: AE-200.50.10
      name: Home-Services Lead Marketplaces
      url: /capabilities/home-services/
      via_parent: Home Services
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Housecall Pro
      - Jobber
      - Workiz
      band: thin
      in_catalog: true
      kin_score: 30.3
      mcp:
        status: none
      name: Thumbtack
      slug: thumbtack
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      - https://www.housecallpro.com/features/integrations/
      - https://www.workiz.com/integrations/
      status: profiled
      tags:
      - Home Services
      - Leads
      - Local Services
      - Marketplace
      tier: declared
      url: /providers/thumbtack/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Housecall Pro
      - Jobber
      - Workiz
      band: emerging
      in_catalog: true
      kin_score: 11.5
      mcp:
        status: none
      name: Angi
      slug: angi
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      - https://www.housecallpro.com/features/integrations/
      - https://www.workiz.com/integrations/
      status: profiled
      tags:
      - Angie's List
      - Home Services
      - Leads
      - Marketplace
      tier: declared
      url: /providers/angi/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - Housecall Pro
      - Jobber
      band: exemplar
      in_catalog: true
      kin_score: 73.1
      mcp:
        source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
        status: verified
      name: Google Local Services Ads
      slug: google-ads
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Advertising
      - Campaign Management
      - Digital Advertising
      - Google
      tier: declared
      url: /providers/google-ads/
    - agent_band: agent-native
      agent_readiness: 53.4
      apps:
      - Jobber
      - Workiz
      band: strong
      in_catalog: true
      kin_score: 64.1
      mcp: &id001
        source: https://github.com/Yelp/yelp-mcp
        status: verified
      name: Yelp Leads
      slug: yelp
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      - https://www.workiz.com/integrations/
      status: profiled
      tags: &id002
      - Business Data
      - Local Search
      - Restaurant
      - Reviews
      tier: declared
      url: /providers/yelp/
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Housecall Pro
      - Jobber
      band: minimal
      in_catalog: true
      kin_score: 10.3
      mcp:
        status: none
      name: Force Fleet Tracking (Mojio)
      slug: mojio
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Company
      - Connected Vehicles
      - Mobility
      - Telematics
      tier: declared
      url: /providers/mojio/
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Jobber
      band: thin
      in_catalog: true
      kin_score: 39.0
      mcp:
        status: none
      name: Azuga Fleet
      slug: azuga
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      status: profiled
      tags:
      - Company
      - Fleet Management
      - GPS Tracking
      - Telematics
      tier: declared
      url: /providers/azuga/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Workiz
      band: emerging
      in_catalog: true
      kin_score: 15.0
      mcp:
        status: none
      name: Linxup
      slug: linxup
      sources:
      - https://www.workiz.com/integrations/
      status: profiled
      tags:
      - Asset Management
      - Dash Cams
      - Fleet Tracking
      - GPS
      tier: declared
      url: /providers/linxup/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Jobber
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        status: unknown
      name: FleetSharp
      slug: fleetsharp
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      status: profiled
      tags:
      - Asset Management
      - Dash Cameras
      - Fleet Tracking
      - GPS
      tier: declared
      url: /providers/fleetsharp/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.40
      key: AE-140.30.40
      name: Point-of-Service Consumer Financing
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - Housecall Pro
      - Jobber
      - Workiz
      band: thin
      in_catalog: true
      kin_score: 32.7
      mcp:
        status: none
      name: Wisetack
      slug: wisetack
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      - https://www.housecallpro.com/features/integrations/
      - https://www.workiz.com/integrations/
      status: profiled
      tags:
      - Company
      - Consumer Financing
      - Fintech
      - Lending
      tier: declared
      url: /providers/wisetack/
    - agent_band: agent-aware
      agent_readiness: 23.6
      apps:
      - Workiz
      band: developing
      in_catalog: true
      kin_score: 44.3
      mcp:
        status: none
      name: Sunbit
      slug: sunbit
      sources:
      - https://www.workiz.com/integrations/
      status: profiled
      tags:
      - Buy Now Pay Later
      - Consumer Lending
      - Payments
      - Point of Sale Financing
      tier: declared
      url: /providers/sunbit/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.9
      apps:
      - Housecall Pro
      - Jobber
      - Workiz
      band: exemplar
      in_catalog: true
      kin_score: 71.3
      mcp:
        status: none
      name: CompanyCam
      slug: companycam
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      - https://www.housecallpro.com/features/integrations/
      - https://www.workiz.com/integrations/
      status: profiled
      tags:
      - Company
      - Construction
      - Field Service Management
      - Photos
      tier: declared
      url: /providers/companycam/
  - capability:
      attribution: Turbo EA
      id: BC-440.20.10
      key: BC-440.20.10
      name: Price Book Maintenance
      url: /capabilities/price-list-management/
      via_parent: Price List Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - Housecall Pro
      band: developing
      in_catalog: true
      kin_score: 41.6
      mcp:
        status: unknown
      name: Profit Rhino
      slug: profit-rhino
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Company
      - Contractor
      - Flat Rate
      - HVAC
      tier: declared
      url: /providers/profit-rhino/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Housecall Pro
      band: emerging
      in_catalog: true
      kin_score: 14.0
      mcp:
        status: none
      name: The New Flat Rate
      slug: the-new-flat-rate
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Company
      - Contractors
      - Pricing
      - Software
      tier: declared
      url: /providers/the-new-flat-rate/
  - capability:
      attribution: Turbo EA
      id: BC-410.40.20
      key: BC-410.40.20
      name: Quote Generation
      url: /capabilities/quote-configuration-management/
      via_parent: Quote & Configuration Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - Housecall Pro
      - Jobber
      band: emerging
      in_catalog: true
      kin_score: 15.6
      mcp:
        status: unknown
      name: ResponsiBid
      slug: responsibid
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Company
      - Home Services
      - Pricing
      - Sales Software
      tier: declared
      url: /providers/responsibid/
  - capability:
      attribution: Turbo EA
      id: BC-2420.10
      key: dispatch-management
      name: Dispatch Management
      url: /capabilities/dispatch-management/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Workiz
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Dispatch.me
      slug: dispatch-me
      sources:
      - https://www.workiz.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-2070.20
      key: BC-2070.20
      name: Fault Detection & Diagnostics Operations
      url: /capabilities/building-performance-management/
      via_parent: Building Performance Management
    providers:
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Housecall Pro
      band: emerging
      in_catalog: true
      kin_score: 14.5
      mcp:
        status: unknown
      name: measureQuick
      slug: measurequick
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Company
      - Diagnostics
      - HVAC
      - Residential
      tier: declared
      url: /providers/measurequick/
  - capability:
      attribution: Turbo EA
      id: BC-500.30
      key: purchase-order-management
      name: Purchase Order Management
      url: /capabilities/purchase-order-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Jobber
      band: thin
      in_catalog: true
      kin_score: 26.2
      mcp:
        status: none
      name: The Home Depot
      slug: home-depot
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      status: profiled
      tags:
      - Fortune 100
      tier: declared
      url: /providers/home-depot/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.20
      key: AE-120.20.20
      name: Satellite & Aerial Imagery
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Jobber
      band: developing
      in_catalog: true
      kin_score: 46.8
      mcp:
        status: none
      name: EagleView
      slug: eagleview
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      status: profiled
      tags:
      - Aerial Imagery
      - Data Analytics
      - Geospatial
      - Real Estate
      tier: declared
      url: /providers/eagleview/
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.5
      apps:
      - Workiz
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Reserve with Google
      slug: google
      sources:
      - https://www.workiz.com/integrations/
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: declared
      url: /providers/google/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 41.2
      apps:
      - Housecall Pro
      - Jobber
      - ServiceM8
      - ServiceTitan
      - Tradify
      - Workiz
      band: strong
      in_catalog: true
      kin_score: 61.1
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks Desktop/Online
      slug: quickbooks
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      - https://help.servicetitan.com/docs/accounting-integrations-overview
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: agent-native
      agent_readiness: 61.3
      apps:
      - Jobber
      - ServiceM8
      - ServiceTitan
      - Tradify
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      - https://help.servicetitan.com/docs/accounting-integrations-overview
      - https://www.servicem8.com/addons
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: declared
      url: /providers/xero/
    - agent_band: agent-aware
      agent_readiness: 15.5
      apps:
      - ServiceTitan
      band: thin
      in_catalog: true
      kin_score: 26.3
      mcp:
        status: none
      name: Sage Intacct
      slug: sage-intacct
      sources:
      - https://help.servicetitan.com/docs/accounting-integrations-overview
      status: profiled
      tags:
      - Accounting
      - ERP
      - Financial Management
      - General Ledger
      tier: declared
      url: /providers/sage-intacct/
    - agent_band: agent-aware
      agent_readiness: 15.4
      apps:
      - ServiceM8
      band: emerging
      in_catalog: true
      kin_score: 23.3
      mcp:
        status: none
      name: MYOB
      slug: myob
      sources:
      - https://www.servicem8.com/addons
      status: profiled
      tags:
      - Accounting
      - Bills
      - Business Management
      - Invoices
      tier: declared
      url: /providers/myob/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 5.4
      apps:
      - Housecall Pro
      - Jobber
      - Workiz
      band: emerging
      in_catalog: true
      kin_score: 13.2
      mcp:
        status: none
      name: NiceJob
      slug: nicejob
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      - https://www.housecallpro.com/features/integrations/
      - https://www.workiz.com/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Reputation Marketing
      - Service Business
      - Software-as-a-Service
      tier: declared
      url: /providers/nicejob/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Housecall Pro
      - Jobber
      band: emerging
      in_catalog: true
      kin_score: 14.0
      mcp:
        status: none
      name: Broadly
      slug: broadly
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - AI Workforce
      - CRM
      - Local SEO
      - Reputation Management
      tier: declared
      url: /providers/broadly/
    - agent_band: agent-native
      agent_readiness: 53.4
      apps:
      - Housecall Pro
      band: strong
      in_catalog: true
      kin_score: 64.1
      mcp: *id001
      name: Yelp
      slug: yelp
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/yelp/
    - agent_band: agent-native
      agent_readiness: 40.9
      apps:
      - Housecall Pro
      band: strong
      in_catalog: true
      kin_score: 57.5
      mcp:
        status: none
      name: Podium
      slug: podium
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Customer Communication
      - Messaging
      - Payments
      - Reviews
      tier: declared
      url: /providers/podium/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Housecall Pro
      band: emerging
      in_catalog: true
      kin_score: 12.6
      mcp:
        status: unknown
      name: Swell
      slug: swellcx
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Healthcare
      - Reputation
      tier: declared
      url: /providers/swellcx/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - Housecall Pro
      - Jobber
      - ServiceM8
      - Workiz
      band: exemplar
      in_catalog: true
      kin_score: 78.3
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      - https://www.housecallpro.com/features/integrations/
      - https://www.servicem8.com/addons
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - Housecall Pro
      band: minimal
      in_catalog: true
      kin_score: 4.9
      mcp:
        status: unknown
      name: CHIIRP
      slug: chiirp
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Home Services
      - Revenue-Optimization
      tier: declared
      url: /providers/chiirp/
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
      - Housecall Pro
      - Jobber
      - ServiceM8
      - Workiz
      band: exemplar
      in_catalog: true
      kin_score: 72.0
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      - https://www.housecallpro.com/features/integrations/
      - https://www.servicem8.com/addons
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Tradify
      - Workiz
      band: developing
      in_catalog: true
      kin_score: 48.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://www.tradifyhq.com/features/integrations
      - https://www.workiz.com/integrations/
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: declared
      url: /providers/google-calendar/
    - agent_band: agent-ready
      agent_readiness: 36.7
      apps:
      - ServiceM8
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Office 365
      slug: microsoft-365
      sources:
      - https://www.servicem8.com/addons
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/microsoft-365/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - Jobber
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.getjobber.jobber/latest/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 56.7
      apps:
      - Jobber
      band: strong
      in_catalog: true
      kin_score: 63.5
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.getjobber.jobber/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Jobber
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.getjobber.jobber/latest/
      status: profiled
      tags: &id004
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: Turbo EA
      id: BC-1320
      key: credit-lending-management
      name: Credit & Lending Management
      url: /capabilities/credit-lending-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Housecall Pro
      - Jobber
      band: minimal
      in_catalog: true
      kin_score: 10.9
      mcp:
        status: none
      name: Fundbox
      slug: fundbox
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - B2B Credit
      - Embedded Finance
      - Fintech
      - Net Terms
      tier: declared
      url: /providers/fundbox/
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Housecall Pro
      - Jobber
      band: developing
      in_catalog: true
      kin_score: 42.0
      mcp:
        status: none
      name: Gusto
      slug: gusto
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Benefits
      - Enterprise Software
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/gusto/
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
      - Jobber
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.getjobber.jobber/latest/
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
      - Jobber
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id003
      name: Google CrashLytics
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.getjobber.jobber/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/firebase/
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
      - ServiceM8
      - Tradify
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe Payments
      slug: stripe
      sources:
      - https://www.servicem8.com/addons
      - https://www.tradifyhq.com/features/integrations
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: declared
      url: /providers/stripe/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.8
      apps:
      - Housecall Pro
      - Jobber
      band: developing
      in_catalog: true
      kin_score: 53.9
      mcp:
        status: none
      name: CallRail
      slug: callrail
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      - https://www.housecallpro.com/features/integrations/
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
      id: AE-150.50
      key: AE-150.50
      name: Voice & Telephony
      url: /capabilities/voice-telephony/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Jobber
      band: strong
      in_catalog: true
      kin_score: 56.2
      mcp:
        source: https://www.quo.com/docs/mdx/mcp
        status: verified
      name: Quo (OpenPhone)
      slug: quo
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      status: profiled
      tags:
      - Communications
      - Company
      - Messaging
      - SMS
      tier: declared
      url: /providers/quo/
    - agent_band: agent-aware
      agent_readiness: 16.5
      apps:
      - Housecall Pro
      band: emerging
      in_catalog: true
      kin_score: 21.2
      mcp:
        status: unknown
      name: Emitrr
      slug: emitrr
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Communications
      - Healthcare
      - Messaging
      tier: declared
      url: /providers/emitrr/
  - capability:
      attribution: Turbo EA
      id: BC-430.30
      key: contact-centre-operations-management
      name: Contact Centre Operations Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.3
      apps:
      - Jobber
      band: strong
      in_catalog: true
      kin_score: 59.0
      mcp:
        status: none
      name: Hatch
      slug: hatch
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      status: profiled
      tags:
      - Company
      - Conversational AI
      - Customer Communication
      - Vertical Software
      tier: declared
      url: /providers/hatch/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.2
      apps:
      - Jobber
      band: thin
      in_catalog: true
      kin_score: 35.6
      mcp:
        source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
        status: verified
      name: Wix
      slug: wix
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      status: profiled
      tags:
      - CMS
      - E-Commerce
      - Headless
      - Website Builder
      tier: declared
      url: /providers/wix/
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Jobber
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp:
        source: https://www.docusign.com/products/mcp
        status: documented
      name: DocuSign
      slug: docusign
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      status: profiled
      tags:
      - Agreements
      - Contracts
      - DocuSign
      - E-Signature
      tier: declared
      url: /providers/docusign/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Workiz
      band: minimal
      in_catalog: true
      kin_score: 7.8
      mcp:
        status: none
      name: SearchKings
      slug: searchkings
      sources:
      - https://www.workiz.com/integrations/
      status: profiled
      tags:
      - Advertising
      - Artificial Intelligence
      - Company
      - Marketing
      tier: declared
      url: /providers/searchkings/
  - capability:
      attribution: API Evangelist extension
      id: AE-912
      key: AE-912
      name: Direct Mail APIs
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Jobber
      band: emerging
      in_catalog: true
      kin_score: 16.8
      mcp:
        status: none
      name: SendJim
      slug: sendjim
      sources:
      - https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
      status: profiled
      tags:
      - Automation
      - Direct Mail
      - Home Services
      - Marketing
      tier: declared
      url: /providers/sendjim/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.50.10
      key: AE-140.50.10
      name: Gift Cards
      url: /capabilities/gift-cards-gifting-cashback/
      via_parent: Gift Cards, Gifting & Cashback
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - Housecall Pro
      band: emerging
      in_catalog: true
      kin_score: 25.4
      mcp:
        status: unknown
      name: Gift Up
      slug: gift-up
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Company
      - E-Commerce
      - Gift Cards
      - Payments
      tier: declared
      url: /providers/gift-up/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20
      key: AE-120.20
      name: Maps & Tiles
      url: /capabilities/maps-tiles/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - OCA Field Service (Odoo)
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps
      slug: google-maps
      sources:
      - https://github.com/OCA/field-service/blob/19.0/fieldservice_google_map/__manifest__.py
      status: profiled
      tags:
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - Jobber
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.getjobber.jobber/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Jobber
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Huawei Mobile Services (HMS) Core
      slug: huawei-mobile-services
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.getjobber.jobber/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-2440.20
      key: rostering-and-scheduling-management
      name: Rostering and Scheduling Management
      url: /capabilities/rostering-and-scheduling-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - ServiceM8
      band: strong
      in_catalog: true
      kin_score: 66.2
      mcp:
        status: none
      name: Deputy
      slug: deputy
      sources:
      - https://www.servicem8.com/addons
      status: profiled
      tags:
      - Employee Scheduling
      - Time and Attendance
      - Timesheets
      - Workforce Management
      tier: declared
      url: /providers/deputy/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.2
      apps:
      - Jobber
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.getjobber.jobber/latest/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.30
      key: AE-150.50.30
      name: Virtual Receptionists & Answering Services
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    providers:
    - agent_band: human-only
      agent_readiness: 3.9
      apps:
      - Workiz
      band: minimal
      in_catalog: true
      kin_score: 9.2
      mcp:
        status: unknown
      name: AnswerConnect
      slug: answerconnect
      sources:
      - https://www.workiz.com/integrations/
      status: profiled
      tags:
      - Appointment Scheduling
      - Call Answering
      - Company
      - Live Chat
      tier: declared
      url: /providers/answerconnect/
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.20
      key: AE-100.70.20
      name: Voice Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Housecall Pro
      band: emerging
      in_catalog: true
      kin_score: 24.8
      mcp:
        status: none
      name: Signpost
      slug: signpost
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Answering Service
      - Company
      - Enterprise
      - Virtual Receptionist
      tier: declared
      url: /providers/signpost/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30
      key: AE-110.30
      name: Speech & Voice
      url: /capabilities/speech-voice/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.8
      apps:
      - Housecall Pro
      band: developing
      in_catalog: true
      kin_score: 46.7
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Amazon Alexa
      slug: amazon
      sources:
      - https://www.housecallpro.com/features/integrations/
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: declared
      url: /providers/amazon/
  layer: agent
summary:
  coverage_pct: 96.4
  declared_only: 48
  distinct_providers: 56
  in_catalog: 54
  mcp:
    documented: 1
    none: 26
    unchecked: 2
    verified: 18
  mcp_verified: 18
  mean_kin_score: 42.5
  observed: 8
  queued: 2
  reference_apps: 7
title: 'Field Service & Dispatch: application blueprint'
---
