---
app: Jobber
app_slug: jobber
app_url: https://getjobber.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2430.40
  key: fleet-telematics-and-monitoring
  layer: domain
  name: Fleet Telematics and Monitoring
  providers:
  - Azuga Fleet
  - FleetSharp
  - Force Fleet Tracking (Mojio)
  url: /capabilities/fleet-telematics-and-monitoring/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.50.10
  key: AE-200.50.10
  layer: domain
  name: Home-Services Lead Marketplaces
  providers:
  - Angi
  - Google Local Services Ads
  - Thumbtack
  - Yelp Leads
  url: /capabilities/home-services/
  via_parent: Home Services
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: domain
  name: Photo & Image Libraries
  providers:
  - CompanyCam
  url: /capabilities/photo-image-libraries/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.30.40
  key: AE-140.30.40
  layer: domain
  name: Point-of-Service Consumer Financing
  providers:
  - Wisetack
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: Turbo EA
  id: BC-500.30
  key: purchase-order-management
  layer: domain
  name: Purchase Order Management
  providers:
  - The Home Depot
  url: /capabilities/purchase-order-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-410.40.20
  key: BC-410.40.20
  layer: domain
  name: Quote Generation
  providers:
  - ResponsiBid
  url: /capabilities/quote-configuration-management/
  via_parent: Quote & Configuration Management
- attribution: API Evangelist extension
  id: AE-120.20.20
  key: AE-120.20.20
  layer: domain
  name: Satellite & Aerial Imagery
  providers:
  - EagleView
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: Turbo EA
  id: BC-430.30
  key: contact-centre-operations-management
  layer: common
  name: Contact Centre Operations Management
  providers:
  - Hatch
  url: /capabilities/contact-centre-operations-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: common
  name: Content Management
  providers:
  - Wix
  url: /capabilities/content-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-150.10.30
  key: BC-150.10.30
  layer: common
  name: Contract Execution Management
  providers:
  - DocuSign
  url: /capabilities/contract-management/
  via_parent: Contract Management
- attribution: Turbo EA
  id: BC-1320
  key: credit-lending-management
  layer: common
  name: Credit & Lending Management
  providers:
  - Fundbox
  url: /capabilities/credit-lending-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-912
  key: AE-912
  layer: common
  name: Direct Mail APIs
  providers:
  - SendJim
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - QuickBooks Online
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: common
  name: Human Capital Management
  providers:
  - Gusto
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - AppsFlyer
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Google CrashLytics
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Amplitude
  - Google Analytics
  - Google Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50.10
  key: AE-150.50.10
  layer: common
  name: Programmable Voice
  providers:
  - CallRail
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Huawei Mobile Services (HMS) Core
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: common
  name: Reviews & Social Proof
  providers:
  - Broadly
  - NiceJob
  url: /capabilities/reviews-social-proof/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: common
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
- attribution: API Evangelist extension
  id: AE-150.50
  key: AE-150.50
  layer: common
  name: Voice & Telephony
  providers:
  - Quo (OpenPhone)
  url: /capabilities/voice-telephony/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: field-service
  name: Field Service & Dispatch
  url: /applications/field-service/
counts:
  declared: 26
  observed: 8
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
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
  facts:
    agent_band: agent-ready
    agent_readiness: 56.9
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id002
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id003
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.4
    band: exemplar
    in_catalog: true
    kin_score: 72.1
    mcp: &id006
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id007
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id026
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id027
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
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
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id028
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id029
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
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
  facts: *id001
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id032
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id033
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id038
      status: unchecked
    slug: huawei-mobile-services
    status: queued for profiling
    tags: &id039 []
    url: null
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id052
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id053
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.1
    mcp: &id004
      status: none
    slug: angi
    status: profiled
    tags: &id005
    - Angie's List
    - Home Services
    - Leads
    - Marketplace
    url: /providers/angi/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.4
    band: developing
    in_catalog: true
    kin_score: 47.2
    mcp: &id008
      status: none
    slug: azuga
    status: profiled
    tags: &id009
    - Company
    - Fleet Management
    - GPS Tracking
    - Telematics
    url: /providers/azuga/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.2
    mcp: &id010
      status: none
    slug: broadly
    status: profiled
    tags: &id011
    - AI Workforce
    - CRM
    - Local SEO
    - Reputation Management
    url: /providers/broadly/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: developing
    in_catalog: true
    kin_score: 54.1
    mcp: &id012
      status: none
    slug: callrail
    status: profiled
    tags: &id013
    - Call Tracking
    - Conversation Intelligence
    - Lead Tracking
    - Marketing Attribution
    url: /providers/callrail/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.1
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id014
      status: none
    slug: companycam
    status: profiled
    tags: &id015
    - Company
    - Construction
    - Field Service Management
    - Photos
    url: /providers/companycam/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 71.5
    mcp: &id016
      source: https://www.docusign.com/products/mcp
      status: documented
    slug: docusign
    status: profiled
    tags: &id017
    - Agreements
    - Contracts
    - DocuSign
    - E-Signature
    url: /providers/docusign/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.6
    band: developing
    in_catalog: true
    kin_score: 52.2
    mcp: &id018
      status: none
    slug: eagleview
    status: profiled
    tags: &id019
    - Aerial Imagery
    - Data Analytics
    - Geospatial
    - Real Estate
    url: /providers/eagleview/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 20.7
    mcp: &id020
      status: unknown
    slug: fleetsharp
    status: profiled
    tags: &id021
    - Asset Management
    - Dash Cameras
    - Fleet Tracking
    - GPS
    url: /providers/fleetsharp/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.1
    mcp: &id022
      status: none
    slug: mojio
    status: profiled
    tags: &id023
    - Company
    - Connected Vehicles
    - Mobility
    - Telematics
    url: /providers/mojio/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 10.1
    mcp: &id024
      status: none
    slug: fundbox
    status: profiled
    tags: &id025
    - B2B Credit
    - Embedded Finance
    - Fintech
    - Net Terms
    url: /providers/fundbox/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 42.1
    band: exemplar
    in_catalog: true
    kin_score: 73.4
    mcp: &id030
      source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
      status: verified
    slug: google-ads
    status: profiled
    tags: &id031
    - Advertising
    - Campaign Management
    - Digital Advertising
    - Google
    url: /providers/google-ads/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.7
    band: developing
    in_catalog: true
    kin_score: 44.9
    mcp: &id034
      status: none
    slug: gusto
    status: profiled
    tags: &id035
    - Benefits
    - Enterprise Software
    - Human Resources
    - Payroll
    url: /providers/gusto/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.3
    band: strong
    in_catalog: true
    kin_score: 58.9
    mcp: &id036
      status: none
    slug: hatch
    status: profiled
    tags: &id037
    - Company
    - Conversational AI
    - Customer Communication
    - Vertical Software
    url: /providers/hatch/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id040
      status: none
    slug: mailchimp
    status: profiled
    tags: &id041
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 18.4
    mcp: &id042
      status: none
    slug: nicejob
    status: profiled
    tags: &id043
    - Artificial Intelligence
    - Reputation Marketing
    - Service Business
    - Software-as-a-Service
    url: /providers/nicejob/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id044
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id045
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.6
    band: strong
    in_catalog: true
    kin_score: 55.5
    mcp: &id046
      source: https://www.quo.com/docs/mdx/mcp
      status: verified
    slug: quo
    status: profiled
    tags: &id047
    - Communications
    - Company
    - Messaging
    - SMS
    url: /providers/quo/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 20.0
    mcp: &id048
      status: unknown
    slug: responsibid
    status: profiled
    tags: &id049
    - Company
    - Home Services
    - Pricing
    - Sales Software
    url: /providers/responsibid/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 21.6
    mcp: &id050
      status: none
    slug: sendjim
    status: profiled
    tags: &id051
    - Automation
    - Direct Mail
    - Home Services
    - Marketing
    url: /providers/sendjim/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.2
    band: emerging
    in_catalog: true
    kin_score: 25.0
    mcp: &id054
      status: none
    slug: home-depot
    status: profiled
    tags: &id055
    - Fortune 100
    url: /providers/home-depot/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.9
    band: thin
    in_catalog: true
    kin_score: 29.8
    mcp: &id056
      status: none
    slug: thumbtack
    status: profiled
    tags: &id057
    - Home Services
    - Leads
    - Local Services
    - Marketplace
    url: /providers/thumbtack/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: thin
    in_catalog: true
    kin_score: 34.9
    mcp: &id058
      status: none
    slug: wisetack
    status: profiled
    tags: &id059
    - Company
    - Consumer Financing
    - Fintech
    - Lending
    url: /providers/wisetack/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 47.2
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id060
      source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
      status: verified
    slug: wix
    status: profiled
    tags: &id061
    - CMS
    - E-Commerce
    - Headless
    - Website Builder
    url: /providers/wix/
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
  facts:
    agent_band: agent-native
    agent_readiness: 60.0
    band: exemplar
    in_catalog: true
    kin_score: 87.1
    mcp: &id062
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id063
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
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
  facts:
    agent_band: agent-native
    agent_readiness: 46.7
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id064
      source: https://github.com/Yelp/yelp-mcp
      status: verified
    slug: yelp
    status: profiled
    tags: &id065
    - Business Data
    - Local Search
    - Restaurant
    - Reviews
    url: /providers/yelp/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id066
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id067
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://help.getjobber.com/hc/en-us/categories/115001334127-App-Marketplace
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/field-service/jobber/
providers:
- agent_band: agent-ready
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id002
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id003
  url: /providers/amplitude/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.1
  mcp: *id004
  name: Angi
  slug: angi
  status: profiled
  tags: *id005
  url: /providers/angi/
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id006
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id007
  url: /providers/appsflyer/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: developing
  in_catalog: true
  kin_score: 47.2
  mcp: *id008
  name: Azuga Fleet
  slug: azuga
  status: profiled
  tags: *id009
  url: /providers/azuga/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.2
  mcp: *id010
  name: Broadly
  slug: broadly
  status: profiled
  tags: *id011
  url: /providers/broadly/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: developing
  in_catalog: true
  kin_score: 54.1
  mcp: *id012
  name: CallRail
  slug: callrail
  status: profiled
  tags: *id013
  url: /providers/callrail/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id014
  name: CompanyCam
  slug: companycam
  status: profiled
  tags: *id015
  url: /providers/companycam/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 71.5
  mcp: *id016
  name: DocuSign
  slug: docusign
  status: profiled
  tags: *id017
  url: /providers/docusign/
- agent_band: agent-ready
  agent_readiness: 34.6
  band: developing
  in_catalog: true
  kin_score: 52.2
  mcp: *id018
  name: EagleView
  slug: eagleview
  status: profiled
  tags: *id019
  url: /providers/eagleview/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.7
  mcp: *id020
  name: FleetSharp
  slug: fleetsharp
  status: profiled
  tags: *id021
  url: /providers/fleetsharp/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.1
  mcp: *id022
  name: Force Fleet Tracking (Mojio)
  slug: mojio
  status: profiled
  tags: *id023
  url: /providers/mojio/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 10.1
  mcp: *id024
  name: Fundbox
  slug: fundbox
  status: profiled
  tags: *id025
  url: /providers/fundbox/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id026
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id027
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id028
  name: Google CrashLytics
  slug: google-firebase
  status: profiled
  tags: *id029
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 73.4
  mcp: *id030
  name: Google Local Services Ads
  slug: google-ads
  status: profiled
  tags: *id031
  url: /providers/google-ads/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id032
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id033
  url: /providers/google-tag-manager/
- agent_band: agent-ready
  agent_readiness: 31.7
  band: developing
  in_catalog: true
  kin_score: 44.9
  mcp: *id034
  name: Gusto
  slug: gusto
  status: profiled
  tags: *id035
  url: /providers/gusto/
- agent_band: agent-aware
  agent_readiness: 28.3
  band: strong
  in_catalog: true
  kin_score: 58.9
  mcp: *id036
  name: Hatch
  slug: hatch
  status: profiled
  tags: *id037
  url: /providers/hatch/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id038
  name: Huawei Mobile Services (HMS) Core
  slug: huawei-mobile-services
  status: queued for profiling
  tags: *id039
  url: null
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id040
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id041
  url: /providers/mailchimp/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 18.4
  mcp: *id042
  name: NiceJob
  slug: nicejob
  status: profiled
  tags: *id043
  url: /providers/nicejob/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id044
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id045
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: strong
  in_catalog: true
  kin_score: 55.5
  mcp: *id046
  name: Quo (OpenPhone)
  slug: quo
  status: profiled
  tags: *id047
  url: /providers/quo/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 20.0
  mcp: *id048
  name: ResponsiBid
  slug: responsibid
  status: profiled
  tags: *id049
  url: /providers/responsibid/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 21.6
  mcp: *id050
  name: SendJim
  slug: sendjim
  status: profiled
  tags: *id051
  url: /providers/sendjim/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id052
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id053
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 20.2
  band: emerging
  in_catalog: true
  kin_score: 25.0
  mcp: *id054
  name: The Home Depot
  slug: home-depot
  status: profiled
  tags: *id055
  url: /providers/home-depot/
- agent_band: agent-aware
  agent_readiness: 24.9
  band: thin
  in_catalog: true
  kin_score: 29.8
  mcp: *id056
  name: Thumbtack
  slug: thumbtack
  status: profiled
  tags: *id057
  url: /providers/thumbtack/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: thin
  in_catalog: true
  kin_score: 34.9
  mcp: *id058
  name: Wisetack
  slug: wisetack
  status: profiled
  tags: *id059
  url: /providers/wisetack/
- agent_band: agent-ready
  agent_readiness: 47.2
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id060
  name: Wix
  slug: wix
  status: profiled
  tags: *id061
  url: /providers/wix/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id062
  name: Xero
  slug: xero
  status: profiled
  tags: *id063
  url: /providers/xero/
- agent_band: agent-native
  agent_readiness: 46.7
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id064
  name: Yelp Leads
  slug: yelp
  status: profiled
  tags: *id065
  url: /providers/yelp/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id066
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id067
  url: /providers/zapier/
siblings:
- name: Housecall Pro
  rows: 26
  url: /applications/field-service/housecall-pro/
- name: OCA Field Service (Odoo)
  rows: 1
  url: /applications/field-service/oca-field-service-odoo/
- name: ServiceM8
  rows: 8
  url: /applications/field-service/servicem8/
- name: ServiceTitan
  rows: 3
  url: /applications/field-service/servicetitan/
- name: Tradify
  rows: 4
  url: /applications/field-service/tradify/
- name: Workiz
  rows: 16
  url: /applications/field-service/workiz/
sitemap: true
title: 'Jobber: Field Service & Dispatch reference app'
---
