---
app: Housecall Pro
app_slug: housecall-pro
app_url: https://www.housecallpro.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2070.20
  key: BC-2070.20
  layer: domain
  name: Fault Detection & Diagnostics Operations
  providers:
  - measureQuick
  url: /capabilities/building-performance-management/
  via_parent: Building Performance Management
- attribution: Turbo EA
  id: BC-2430.40
  key: fleet-telematics-and-monitoring
  layer: domain
  name: Fleet Telematics and Monitoring
  providers:
  - Force by Mojio
  url: /capabilities/fleet-telematics-and-monitoring/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.50.10
  key: AE-200.50.10
  layer: domain
  name: Home-Services Lead Marketplaces
  providers:
  - Angi
  - Google Local Services
  - Thumbtack
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
  id: BC-440.20.10
  key: BC-440.20.10
  layer: domain
  name: Price Book Maintenance
  providers:
  - Profit Rhino
  - The New Flat Rate
  url: /capabilities/price-list-management/
  via_parent: Price List Management
- attribution: Turbo EA
  id: BC-410.40.20
  key: BC-410.40.20
  layer: domain
  name: Quote Generation
  providers:
  - ResponsiBid
  url: /capabilities/quote-configuration-management/
  via_parent: Quote & Configuration Management
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
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - CHIIRP
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - QuickBooks
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.50.10
  key: AE-140.50.10
  layer: common
  name: Gift Cards
  providers:
  - Gift Up
  url: /capabilities/gift-cards-gifting-cashback/
  via_parent: Gift Cards, Gifting & Cashback
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
  id: AE-150.50.10
  key: AE-150.50.10
  layer: common
  name: Programmable Voice
  providers:
  - CallRail
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: common
  name: Reviews & Social Proof
  providers:
  - Broadly
  - NiceJob
  - Podium
  - Swell
  - Yelp
  url: /capabilities/reviews-social-proof/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50
  key: AE-150.50
  layer: common
  name: Voice & Telephony
  providers:
  - Emitrr
  url: /capabilities/voice-telephony/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-100.70.20
  key: AE-100.70.20
  layer: common
  name: Voice Agents
  providers:
  - Signpost
  url: /capabilities/vertical-agents/
  via_parent: Vertical Agents
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-110.30
  key: AE-110.30
  layer: agent
  name: Speech & Voice
  providers:
  - Amazon Alexa
  url: /capabilities/speech-voice/
  via_parent: null
category:
  id: field-service
  name: Field Service & Dispatch
  url: /applications/field-service/
counts:
  declared: 26
  observed: 0
credits: []
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
  facts:
    agent_band: agent-native
    agent_readiness: 53.6
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id001
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id002
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.1
    mcp: &id003
      status: none
    slug: angi
    status: profiled
    tags: &id004
    - Angie's List
    - Home Services
    - Leads
    - Marketplace
    url: /providers/angi/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.2
    mcp: &id005
      status: none
    slug: broadly
    status: profiled
    tags: &id006
    - AI Workforce
    - CRM
    - Local SEO
    - Reputation Management
    url: /providers/broadly/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: developing
    in_catalog: true
    kin_score: 54.1
    mcp: &id007
      status: none
    slug: callrail
    status: profiled
    tags: &id008
    - Call Tracking
    - Conversation Intelligence
    - Lead Tracking
    - Marketing Attribution
    url: /providers/callrail/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: minimal
    in_catalog: true
    kin_score: 4.1
    mcp: &id009
      status: unknown
    slug: chiirp
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Company
    - Home Services
    - Revenue Optimization
    url: /providers/chiirp/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.1
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id011
      status: none
    slug: companycam
    status: profiled
    tags: &id012
    - Company
    - Construction
    - Field Service Management
    - Photos
    url: /providers/companycam/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.2
    band: thin
    in_catalog: true
    kin_score: 26.3
    mcp: &id013
      status: unknown
    slug: emitrr
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Communications
    - Healthcare
    - Messaging
    url: /providers/emitrr/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.1
    mcp: &id015
      status: none
    slug: mojio
    status: profiled
    tags: &id016
    - Company
    - Connected Vehicles
    - Mobility
    - Telematics
    url: /providers/mojio/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 10.1
    mcp: &id017
      status: none
    slug: fundbox
    status: profiled
    tags: &id018
    - B2B Credit
    - Embedded Finance
    - Fintech
    - Net Terms
    url: /providers/fundbox/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: thin
    in_catalog: true
    kin_score: 28.4
    mcp: &id019
      status: unknown
    slug: gift-up
    status: profiled
    tags: &id020
    - Company
    - E-Commerce
    - Gift Cards
    - Payments
    url: /providers/gift-up/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 42.1
    band: exemplar
    in_catalog: true
    kin_score: 73.4
    mcp: &id021
      source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
      status: verified
    slug: google-ads
    status: profiled
    tags: &id022
    - Advertising
    - Campaign Management
    - Digital Advertising
    - Google
    url: /providers/google-ads/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.7
    band: developing
    in_catalog: true
    kin_score: 44.9
    mcp: &id023
      status: none
    slug: gusto
    status: profiled
    tags: &id024
    - Benefits
    - Enterprise Software
    - Human Resources
    - Payroll
    url: /providers/gusto/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id025
      status: none
    slug: mailchimp
    status: profiled
    tags: &id026
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.6
    mcp: &id027
      status: unknown
    slug: measurequick
    status: profiled
    tags: &id028
    - Company
    - Diagnostics
    - HVAC
    - Residential
    url: /providers/measurequick/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 18.4
    mcp: &id029
      status: none
    slug: nicejob
    status: profiled
    tags: &id030
    - Artificial Intelligence
    - Reputation Marketing
    - Service Business
    - Software-as-a-Service
    url: /providers/nicejob/
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
  facts:
    agent_band: agent-native
    agent_readiness: 40.1
    band: strong
    in_catalog: true
    kin_score: 59.1
    mcp: &id031
      status: none
    slug: podium
    status: profiled
    tags: &id032
    - Customer Communication
    - Messaging
    - Payments
    - Reviews
    url: /providers/podium/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 42.8
    band: developing
    in_catalog: true
    kin_score: 50.0
    mcp: &id033
      status: unknown
    slug: profit-rhino
    status: profiled
    tags: &id034
    - Company
    - Contractor
    - Flat-rate
    - HVAC
    url: /providers/profit-rhino/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id035
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id036
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 20.0
    mcp: &id037
      status: unknown
    slug: responsibid
    status: profiled
    tags: &id038
    - Company
    - Home Services
    - Pricing
    - Sales Software
    url: /providers/responsibid/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 25.3
    mcp: &id039
      status: none
    slug: signpost
    status: profiled
    tags: &id040
    - Answering Service
    - Company
    - Enterprise
    - Virtual Receptionist
    url: /providers/signpost/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.7
    mcp: &id041
      status: unknown
    slug: swellcx
    status: profiled
    tags: &id042
    - Artificial Intelligence
    - Company
    - Healthcare
    - Reputation
    url: /providers/swellcx/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.9
    mcp: &id043
      status: none
    slug: the-new-flat-rate
    status: profiled
    tags: &id044
    - Company
    - Contractors
    - Pricing
    - Software
    url: /providers/the-new-flat-rate/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.9
    band: thin
    in_catalog: true
    kin_score: 29.8
    mcp: &id045
      status: none
    slug: thumbtack
    status: profiled
    tags: &id046
    - Home Services
    - Leads
    - Local Services
    - Marketplace
    url: /providers/thumbtack/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: thin
    in_catalog: true
    kin_score: 34.9
    mcp: &id047
      status: none
    slug: wisetack
    status: profiled
    tags: &id048
    - Company
    - Consumer Financing
    - Fintech
    - Lending
    url: /providers/wisetack/
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
  facts:
    agent_band: agent-native
    agent_readiness: 46.7
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id049
      source: https://github.com/Yelp/yelp-mcp
      status: verified
    slug: yelp
    status: profiled
    tags: &id050
    - Business Data
    - Local Search
    - Restaurant
    - Reviews
    url: /providers/yelp/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id051
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id052
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.housecallpro.com/features/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/field-service/housecall-pro/
providers:
- agent_band: agent-native
  agent_readiness: 53.6
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id001
  name: Amazon Alexa
  slug: amazon
  status: profiled
  tags: *id002
  url: /providers/amazon/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.1
  mcp: *id003
  name: Angi
  slug: angi
  status: profiled
  tags: *id004
  url: /providers/angi/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.2
  mcp: *id005
  name: Broadly
  slug: broadly
  status: profiled
  tags: *id006
  url: /providers/broadly/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: developing
  in_catalog: true
  kin_score: 54.1
  mcp: *id007
  name: CallRail
  slug: callrail
  status: profiled
  tags: *id008
  url: /providers/callrail/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: minimal
  in_catalog: true
  kin_score: 4.1
  mcp: *id009
  name: CHIIRP
  slug: chiirp
  status: profiled
  tags: *id010
  url: /providers/chiirp/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id011
  name: CompanyCam
  slug: companycam
  status: profiled
  tags: *id012
  url: /providers/companycam/
- agent_band: agent-aware
  agent_readiness: 16.2
  band: thin
  in_catalog: true
  kin_score: 26.3
  mcp: *id013
  name: Emitrr
  slug: emitrr
  status: profiled
  tags: *id014
  url: /providers/emitrr/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.1
  mcp: *id015
  name: Force by Mojio
  slug: mojio
  status: profiled
  tags: *id016
  url: /providers/mojio/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 10.1
  mcp: *id017
  name: Fundbox
  slug: fundbox
  status: profiled
  tags: *id018
  url: /providers/fundbox/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: thin
  in_catalog: true
  kin_score: 28.4
  mcp: *id019
  name: Gift Up
  slug: gift-up
  status: profiled
  tags: *id020
  url: /providers/gift-up/
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 73.4
  mcp: *id021
  name: Google Local Services
  slug: google-ads
  status: profiled
  tags: *id022
  url: /providers/google-ads/
- agent_band: agent-ready
  agent_readiness: 31.7
  band: developing
  in_catalog: true
  kin_score: 44.9
  mcp: *id023
  name: Gusto
  slug: gusto
  status: profiled
  tags: *id024
  url: /providers/gusto/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id025
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id026
  url: /providers/mailchimp/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.6
  mcp: *id027
  name: measureQuick
  slug: measurequick
  status: profiled
  tags: *id028
  url: /providers/measurequick/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 18.4
  mcp: *id029
  name: NiceJob
  slug: nicejob
  status: profiled
  tags: *id030
  url: /providers/nicejob/
- agent_band: agent-native
  agent_readiness: 40.1
  band: strong
  in_catalog: true
  kin_score: 59.1
  mcp: *id031
  name: Podium
  slug: podium
  status: profiled
  tags: *id032
  url: /providers/podium/
- agent_band: agent-ready
  agent_readiness: 42.8
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id033
  name: Profit Rhino
  slug: profit-rhino
  status: profiled
  tags: *id034
  url: /providers/profit-rhino/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id035
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id036
  url: /providers/quickbooks/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 20.0
  mcp: *id037
  name: ResponsiBid
  slug: responsibid
  status: profiled
  tags: *id038
  url: /providers/responsibid/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 25.3
  mcp: *id039
  name: Signpost
  slug: signpost
  status: profiled
  tags: *id040
  url: /providers/signpost/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.7
  mcp: *id041
  name: Swell
  slug: swellcx
  status: profiled
  tags: *id042
  url: /providers/swellcx/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.9
  mcp: *id043
  name: The New Flat Rate
  slug: the-new-flat-rate
  status: profiled
  tags: *id044
  url: /providers/the-new-flat-rate/
- agent_band: agent-aware
  agent_readiness: 24.9
  band: thin
  in_catalog: true
  kin_score: 29.8
  mcp: *id045
  name: Thumbtack
  slug: thumbtack
  status: profiled
  tags: *id046
  url: /providers/thumbtack/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: thin
  in_catalog: true
  kin_score: 34.9
  mcp: *id047
  name: Wisetack
  slug: wisetack
  status: profiled
  tags: *id048
  url: /providers/wisetack/
- agent_band: agent-native
  agent_readiness: 46.7
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id049
  name: Yelp
  slug: yelp
  status: profiled
  tags: *id050
  url: /providers/yelp/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id051
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id052
  url: /providers/zapier/
siblings:
- name: Jobber
  rows: 34
  url: /applications/field-service/jobber/
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
title: 'Housecall Pro: Field Service & Dispatch reference app'
---
