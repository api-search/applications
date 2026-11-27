---
app: Hotelogix
app_slug: hotelogix
app_url: https://www.hotelogix.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4010.50
  key: channel-manager-operations
  layer: domain
  name: Channel Manager Operations
  providers:
  - AxisRooms
  - HotelRunner
  - RateGain
  - SiteMinder
  - STAAH
  - SynXis
  url: /capabilities/channel-manager-operations/
  via_parent: null
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: domain
  name: Customer Feedback Management
  providers:
  - ReviewPro
  - TrustYou
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: domain
  name: Email Marketing Sends
  providers:
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - NetSuite
  - QuickBooks
  - SAP
  - Tally (TallyPrime)
  - Xero
  - Zoho Books
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.40
  key: loyalty-retention-management
  layer: domain
  name: Loyalty & Retention Management
  providers:
  - Capillary Technologies
  url: /capabilities/loyalty-retention-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - 2C2P
  - Authorize.Net
  - CCAvenue
  - CyberSource
  - DOKU
  - eWAY
  - First Data
  - PayPal
  - PayU
  - Stripe
  - Worldline
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.90
  key: AE-200.90
  layer: domain
  name: Physical Access Control & Mobile Keys
  providers:
  - Onity
  url: /capabilities/physical-access-control-mobile-keys/
  via_parent: null
- attribution: Turbo EA
  id: BC-4030
  key: travel-revenue-yield-management
  layer: domain
  name: Travel Revenue & Yield Management
  providers:
  - BEONx
  - Lighthouse
  url: /capabilities/travel-revenue-yield-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: domain
  name: WhatsApp & OTT Messaging
  providers:
  - Gupshup
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: hotel-pms
  name: Hotel Property Management
  url: /applications/hotel-pms/
counts:
  declared: 32
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.hotelogix.com/marketplace/
integrations:
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
    agent_readiness: 20.9
    band: thin
    in_catalog: true
    kin_score: 27.1
    mcp: &id001
      status: unknown
    slug: 2c2p
    status: profiled
    tags: &id002
    - Payment Gateway
    - Payments
    - Singapore
    - Southeast Asia
    url: /providers/2c2p/
  layer: domain
  name: 2C2P
  provider: 2c2p
  says: lists 2C2P as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
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
    mcp: &id003
      source: https://github.com/AuthorizeNet/authorize-net-mcp
      status: verified
    slug: authorizenet
    status: profiled
    tags: &id004
    - Company
    - Credit Cards
    - Payment Gateway
    - Payments
    url: /providers/authorizenet/
  layer: domain
  name: Authorize.Net
  provider: authorizenet
  says: lists Authorize.Net as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010.50
    key: channel-manager-operations
    name: Channel Manager Operations
    url: /capabilities/channel-manager-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.2
    mcp: &id005
      status: unchecked
    slug: axisrooms
    status: profiled
    tags: &id006
    - Booking Engine
    - Channel Manager
    - Hospitality
    - Software-as-a-Service
    url: /providers/axisrooms/
  layer: domain
  name: AxisRooms
  provider: axisrooms
  says: lists AxisRooms as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4030
    key: travel-revenue-yield-management
    name: Travel Revenue & Yield Management
    url: /capabilities/travel-revenue-yield-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 19.3
    mcp: &id007
      source: https://beonx.com
      status: documented
    slug: beonx
    status: profiled
    tags: &id008
    - Artificial Intelligence
    - Company
    - Hospitality
    - Revenue Management
    url: /providers/beonx/
  layer: domain
  name: BEONx
  provider: beonx
  says: lists BEONx as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.40
    key: loyalty-retention-management
    name: Loyalty & Retention Management
    url: /capabilities/loyalty-retention-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.1
    band: emerging
    in_catalog: true
    kin_score: 23.5
    mcp: &id009
      source: https://docs.capillarytech.com/docs/mcp
      status: verified
    slug: capillary-technologies
    status: profiled
    tags: &id010
    - Enterprise
    - Loyalty
    - Marketing
    - Software-as-a-Service
    url: /providers/capillary-technologies/
  layer: domain
  name: Capillary Technologies
  provider: capillary-technologies
  says: lists Capillary Technologies as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 23.3
    mcp: &id011
      status: unchecked
    slug: ccavenue
    status: profiled
    tags: &id012
    - Company
    - Fintech
    - India
    - Payments
    url: /providers/ccavenue/
  layer: domain
  name: CCAvenue
  provider: ccavenue
  says: lists CCAvenue as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
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
    agent_readiness: 32.7
    band: thin
    in_catalog: true
    kin_score: 32.5
    mcp: &id013
      source: https://github.com/CyberSource/cybersource-developer-mcp
      status: verified
    slug: cybersource
    status: profiled
    tags: &id014
    - Fraud Prevention
    - Payment Processing
    - Payments
    - Tokenization
    url: /providers/cybersource/
  layer: domain
  name: CyberSource
  provider: cybersource
  says: lists CyberSource as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
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
    agent_readiness: 45.2
    band: strong
    in_catalog: true
    kin_score: 65.5
    mcp: &id015
      source: https://mcp.doku.com/mcp
      status: verified
    slug: doku
    status: profiled
    tags: &id016
    - Fintech
    - Indonesia
    - Payment Gateway
    - Payments
    url: /providers/doku/
  layer: domain
  name: DOKU
  provider: doku
  says: lists DOKU as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
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
    agent_readiness: 5.3
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id017
      status: none
    slug: eway
    status: profiled
    tags: &id018
    - Australia
    - Payment Gateway
    - Payment Processing
    - Payments
    url: /providers/eway/
  layer: domain
  name: eWAY
  provider: eway
  says: lists eWAY as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
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
    agent_readiness: 7.0
    band: emerging
    in_catalog: true
    kin_score: 15.8
    mcp: &id019
      status: none
    slug: first-data
    status: profiled
    tags: &id020
    - Financial Services
    - Merchant Services
    - Payments
    - Transaction Processing
    url: /providers/first-data/
  layer: domain
  name: First Data
  provider: first-data
  says: lists First Data as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
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
    agent_readiness: 24.7
    band: emerging
    in_catalog: true
    kin_score: 24.9
    mcp: &id021
      status: none
    slug: gupshup
    status: profiled
    tags: &id022
    - CPaaS
    - Conversational AI
    - Messaging
    - WhatsApp
    url: /providers/gupshup/
  layer: domain
  name: Gupshup
  provider: gupshup
  says: lists Gupshup as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010.50
    key: channel-manager-operations
    name: Channel Manager Operations
    url: /capabilities/channel-manager-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: thin
    in_catalog: true
    kin_score: 27.4
    mcp: &id023
      status: unknown
    slug: hotelrunner
    status: profiled
    tags: &id024
    - Booking Engine
    - Channel Manager
    - Hospitality
    - Hotels
    url: /providers/hotelrunner/
  layer: domain
  name: HotelRunner
  provider: hotelrunner
  says: lists HotelRunner as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4030
    key: travel-revenue-yield-management
    name: Travel Revenue & Yield Management
    url: /capabilities/travel-revenue-yield-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id025
      status: unchecked
    slug: mylighthouse
    status: queued for profiling
    tags: &id026 []
    url: null
  layer: domain
  name: Lighthouse
  provider: mylighthouse
  says: lists Lighthouse as an integration
  source: https://www.hotelogix.com/marketplace/
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
    mcp: &id027
      status: none
    slug: mailchimp
    status: profiled
    tags: &id028
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: domain
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://www.hotelogix.com/marketplace/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.4
    mcp: &id029
      status: none
    slug: netsuite
    status: profiled
    tags: &id030
    - Accounting
    - CRM
    - ERP
    - Finance
    url: /providers/netsuite/
  layer: domain
  name: NetSuite
  provider: netsuite
  says: lists NetSuite as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.90
    key: AE-200.90
    name: Physical Access Control & Mobile Keys
    url: /capabilities/physical-access-control-mobile-keys/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id031
      status: unchecked
    slug: onity
    status: queued for profiling
    tags: &id032 []
    url: null
  layer: domain
  name: Onity
  provider: onity
  says: lists Onity as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
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
    mcp: &id033
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id034
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: domain
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
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
    agent_readiness: 30.2
    band: thin
    in_catalog: true
    kin_score: 38.9
    mcp: &id035
      source: https://github.com/payu-intrepos/payu-developer-mcp
      status: verified
    slug: payu
    status: profiled
    tags: &id036
    - Financial Services
    - Fintech
    - Payment Processing
    - Payments
    url: /providers/payu/
  layer: domain
  name: PayU
  provider: payu
  says: lists PayU as an integration
  source: https://www.hotelogix.com/marketplace/
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
    mcp: &id037
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id038
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010.50
    key: channel-manager-operations
    name: Channel Manager Operations
    url: /capabilities/channel-manager-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.5
    band: thin
    in_catalog: true
    kin_score: 34.9
    mcp: &id039
      status: unknown
    slug: rategain
    status: profiled
    tags: &id040
    - Company
    - Hospitality
    - Software-as-a-Service
    - TravelTech
    url: /providers/rategain/
  layer: domain
  name: RateGain
  provider: rategain
  says: lists RateGain as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 18.3
    mcp: &id041
      status: unchecked
    slug: reviewpro
    status: profiled
    tags: &id042
    - Company
    - Hospitality
    - Reputation Management
    - Software-as-a-Service
    url: /providers/reviewpro/
  layer: domain
  name: ReviewPro
  provider: reviewpro
  says: lists ReviewPro as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
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
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id043
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id044
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.hotelogix.com/marketplace/
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
    agent_readiness: 58.7
    band: strong
    in_catalog: true
    kin_score: 58.3
    mcp: &id045
      source: https://github.com/SAP/mdk-mcp-server
      status: verified
    slug: sap
    status: profiled
    tags: &id046
    - Artificial Intelligence
    - BTP
    - Business Applications
    - SAP
    url: /providers/sap/
  layer: domain
  name: SAP
  provider: sap
  says: lists SAP as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010.50
    key: channel-manager-operations
    name: Channel Manager Operations
    url: /capabilities/channel-manager-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.5
    band: thin
    in_catalog: true
    kin_score: 30.8
    mcp: &id047
      status: none
    slug: siteminder
    status: profiled
    tags: &id048
    - Booking Engine
    - Channel Manager
    - Hospitality
    - Hotel Distribution
    url: /providers/siteminder/
  layer: domain
  name: SiteMinder
  provider: siteminder
  says: lists SiteMinder as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010.50
    key: channel-manager-operations
    name: Channel Manager Operations
    url: /capabilities/channel-manager-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.4
    band: emerging
    in_catalog: true
    kin_score: 20.8
    mcp: &id049
      status: unchecked
    slug: staah
    status: profiled
    tags: &id050
    - Channel Management
    - Company
    - Hospitality
    - Software-as-a-Service
    url: /providers/staah/
  layer: domain
  name: STAAH
  provider: staah
  says: lists STAAH as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
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
  says: lists Stripe as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010.50
    key: channel-manager-operations
    name: Channel Manager Operations
    url: /capabilities/channel-manager-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.4
    band: developing
    in_catalog: true
    kin_score: 40.3
    mcp: &id053
      status: none
    slug: sabre
    status: profiled
    tags: &id054
    - Airlines
    - GDS
    - Hotels
    - Travel
    url: /providers/sabre/
  layer: domain
  name: SynXis
  provider: sabre
  says: lists SynXis as an integration
  source: https://www.hotelogix.com/marketplace/
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
    agent_band: human-only
    agent_readiness: 3.0
    band: thin
    in_catalog: true
    kin_score: 27.0
    mcp: &id055
      status: unchecked
    slug: tallyprime
    status: profiled
    tags: &id056
    - Accounting
    - Business Software
    - India
    - Small Business
    url: /providers/tallyprime/
  layer: domain
  name: Tally (TallyPrime)
  provider: tallyprime
  says: lists Tally (TallyPrime) as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 20.4
    mcp: &id057
      status: unchecked
    slug: trustyou
    status: profiled
    tags: &id058
    - Artificial Intelligence
    - Data Analytics
    - Guest Experience
    - Hospitality
    url: /providers/trustyou/
  layer: domain
  name: TrustYou
  provider: trustyou
  says: lists TrustYou as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
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
    agent_readiness: 19.7
    band: thin
    in_catalog: true
    kin_score: 32.7
    mcp: &id059
      status: unchecked
    slug: worldline
    status: profiled
    tags: &id060
    - Acquiring
    - Financial Services
    - Partners
    - Payments
    url: /providers/worldline/
  layer: domain
  name: Worldline
  provider: worldline
  says: lists Worldline as an integration
  source: https://www.hotelogix.com/marketplace/
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
    mcp: &id061
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id062
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: domain
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://www.hotelogix.com/marketplace/
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
    agent_band: agent-aware
    agent_readiness: 18.6
    band: developing
    in_catalog: true
    kin_score: 47.5
    mcp: &id063
      source: https://www.zoho.com/mcp/
      status: documented
    slug: zoho-books
    status: profiled
    tags: &id064
    - Accounting
    - Bookkeeping
    - Expenses
    - Invoicing
    url: /providers/zoho-books/
  layer: domain
  name: Zoho Books
  provider: zoho-books
  says: lists Zoho Books as an integration
  source: https://www.hotelogix.com/marketplace/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/hotel-pms/hotelogix/
providers:
- agent_band: agent-aware
  agent_readiness: 20.9
  band: thin
  in_catalog: true
  kin_score: 27.1
  mcp: *id001
  name: 2C2P
  slug: 2c2p
  status: profiled
  tags: *id002
  url: /providers/2c2p/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id003
  name: Authorize.Net
  slug: authorizenet
  status: profiled
  tags: *id004
  url: /providers/authorizenet/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.2
  mcp: *id005
  name: AxisRooms
  slug: axisrooms
  status: profiled
  tags: *id006
  url: /providers/axisrooms/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 19.3
  mcp: *id007
  name: BEONx
  slug: beonx
  status: profiled
  tags: *id008
  url: /providers/beonx/
- agent_band: agent-aware
  agent_readiness: 27.1
  band: emerging
  in_catalog: true
  kin_score: 23.5
  mcp: *id009
  name: Capillary Technologies
  slug: capillary-technologies
  status: profiled
  tags: *id010
  url: /providers/capillary-technologies/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 23.3
  mcp: *id011
  name: CCAvenue
  slug: ccavenue
  status: profiled
  tags: *id012
  url: /providers/ccavenue/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: thin
  in_catalog: true
  kin_score: 32.5
  mcp: *id013
  name: CyberSource
  slug: cybersource
  status: profiled
  tags: *id014
  url: /providers/cybersource/
- agent_band: agent-native
  agent_readiness: 45.2
  band: strong
  in_catalog: true
  kin_score: 65.5
  mcp: *id015
  name: DOKU
  slug: doku
  status: profiled
  tags: *id016
  url: /providers/doku/
- agent_band: agent-aware
  agent_readiness: 5.3
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id017
  name: eWAY
  slug: eway
  status: profiled
  tags: *id018
  url: /providers/eway/
- agent_band: agent-aware
  agent_readiness: 7.0
  band: emerging
  in_catalog: true
  kin_score: 15.8
  mcp: *id019
  name: First Data
  slug: first-data
  status: profiled
  tags: *id020
  url: /providers/first-data/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: emerging
  in_catalog: true
  kin_score: 24.9
  mcp: *id021
  name: Gupshup
  slug: gupshup
  status: profiled
  tags: *id022
  url: /providers/gupshup/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: thin
  in_catalog: true
  kin_score: 27.4
  mcp: *id023
  name: HotelRunner
  slug: hotelrunner
  status: profiled
  tags: *id024
  url: /providers/hotelrunner/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id025
  name: Lighthouse
  slug: mylighthouse
  status: queued for profiling
  tags: *id026
  url: null
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id027
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id028
  url: /providers/mailchimp/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.4
  mcp: *id029
  name: NetSuite
  slug: netsuite
  status: profiled
  tags: *id030
  url: /providers/netsuite/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id031
  name: Onity
  slug: onity
  status: queued for profiling
  tags: *id032
  url: null
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id033
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id034
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 30.2
  band: thin
  in_catalog: true
  kin_score: 38.9
  mcp: *id035
  name: PayU
  slug: payu
  status: profiled
  tags: *id036
  url: /providers/payu/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id037
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id038
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 40.5
  band: thin
  in_catalog: true
  kin_score: 34.9
  mcp: *id039
  name: RateGain
  slug: rategain
  status: profiled
  tags: *id040
  url: /providers/rategain/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 18.3
  mcp: *id041
  name: ReviewPro
  slug: reviewpro
  status: profiled
  tags: *id042
  url: /providers/reviewpro/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id043
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id044
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 58.7
  band: strong
  in_catalog: true
  kin_score: 58.3
  mcp: *id045
  name: SAP
  slug: sap
  status: profiled
  tags: *id046
  url: /providers/sap/
- agent_band: agent-aware
  agent_readiness: 5.5
  band: thin
  in_catalog: true
  kin_score: 30.8
  mcp: *id047
  name: SiteMinder
  slug: siteminder
  status: profiled
  tags: *id048
  url: /providers/siteminder/
- agent_band: agent-aware
  agent_readiness: 21.4
  band: emerging
  in_catalog: true
  kin_score: 20.8
  mcp: *id049
  name: STAAH
  slug: staah
  status: profiled
  tags: *id050
  url: /providers/staah/
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
- agent_band: agent-ready
  agent_readiness: 47.4
  band: developing
  in_catalog: true
  kin_score: 40.3
  mcp: *id053
  name: SynXis
  slug: sabre
  status: profiled
  tags: *id054
  url: /providers/sabre/
- agent_band: human-only
  agent_readiness: 3.0
  band: thin
  in_catalog: true
  kin_score: 27.0
  mcp: *id055
  name: Tally (TallyPrime)
  slug: tallyprime
  status: profiled
  tags: *id056
  url: /providers/tallyprime/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 20.4
  mcp: *id057
  name: TrustYou
  slug: trustyou
  status: profiled
  tags: *id058
  url: /providers/trustyou/
- agent_band: agent-aware
  agent_readiness: 19.7
  band: thin
  in_catalog: true
  kin_score: 32.7
  mcp: *id059
  name: Worldline
  slug: worldline
  status: profiled
  tags: *id060
  url: /providers/worldline/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id061
  name: Xero
  slug: xero
  status: profiled
  tags: *id062
  url: /providers/xero/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: developing
  in_catalog: true
  kin_score: 47.5
  mcp: *id063
  name: Zoho Books
  slug: zoho-books
  status: profiled
  tags: *id064
  url: /providers/zoho-books/
siblings:
- name: apaleo
  rows: 8
  url: /applications/hotel-pms/apaleo/
- name: Beds24
  rows: 12
  url: /applications/hotel-pms/beds24/
- name: Cloudbeds
  rows: 16
  url: /applications/hotel-pms/cloudbeds/
- name: Mews
  rows: 13
  url: /applications/hotel-pms/mews/
- name: QloApps
  rows: 3
  url: /applications/hotel-pms/qloapps/
sitemap: true
title: 'Hotelogix: Hotel Property Management reference app'
---
