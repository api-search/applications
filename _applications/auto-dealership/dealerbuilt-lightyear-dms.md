---
app: DealerBuilt (LightYear DMS)
app_slug: dealerbuilt-lightyear-dms
app_url: https://dealerbuilt.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4000.40
  key: ancillary-add-on-product-management
  layer: domain
  name: Ancillary & Add-On Product Management
  providers:
  - Darwin Automotive
  - StoneEagle F&I
  url: /capabilities/ancillary-add-on-product-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1320.10
  key: credit-origination-management
  layer: domain
  name: Credit Origination Management
  providers:
  - Dealertrack
  url: /capabilities/credit-origination-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1320.20
  key: credit-underwriting-decisioning-management
  layer: domain
  name: Credit Underwriting & Decisioning Management
  providers:
  - 700Credit
  url: /capabilities/credit-underwriting-decisioning-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3430
  key: dealer-network-management
  layer: domain
  name: Dealer Network Management
  providers:
  - JLR
  - Subaru of America
  url: /capabilities/dealer-network-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3460.30
  key: in-vehicle-app-and-subscription-management
  layer: domain
  name: In-Vehicle App and Subscription Management
  providers:
  - SiriusXM
  url: /capabilities/in-vehicle-app-and-subscription-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.30
  key: market-intelligence-management
  layer: domain
  name: Market Intelligence Management
  providers:
  - J.D. Power
  - Urban Science
  url: /capabilities/market-intelligence-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1060
  key: spare-parts-aftermarket-management
  layer: domain
  name: Spare Parts & Aftermarket Management
  providers:
  - OEConnection
  - Revolution Parts
  url: /capabilities/spare-parts-aftermarket-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3450
  key: vehicle-aftersales-warranty-management
  layer: domain
  name: Vehicle Aftersales & Warranty Management
  providers:
  - AutoLoop
  - Dynatron (ROAMS)
  - Xtime
  url: /capabilities/vehicle-aftersales-warranty-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-949
  key: AE-949
  layer: domain
  name: Vehicle History Reports
  providers:
  - CARFAX
  url: /capabilities/vehicle-history-reports/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-951
  key: AE-951
  layer: domain
  name: Vehicle Inventory Listing Syndication
  providers:
  - HomeNet (Cox Automotive)
  - TrueCar
  url: /capabilities/vehicle-inventory-listing-syndication/
  via_parent: null
- attribution: Turbo EA
  id: BC-3440
  key: vehicle-sales-distribution-management
  layer: domain
  name: Vehicle Sales & Distribution Management
  providers:
  - Deal Central (Cox Automotive)
  url: /capabilities/vehicle-sales-distribution-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-948
  key: AE-948
  layer: domain
  name: Vehicle Valuation & Appraisal Guides
  providers:
  - Black Book
  - vAuto
  url: /capabilities/vehicle-valuation-appraisal-guides/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - DealerSocket CRM
  - DriveCentric
  - Elead (CDK)
  - VinSolutions
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-950
  key: AE-950
  layer: common
  name: Dealer Management System Data Access
  providers:
  - Authenticom (DealerVault)
  - Digital Motorworks (CDK)
  url: /capabilities/dealer-management-system-data-access/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - AutoFi
  - CarNow
  - LotLinx
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Global Payments
  - REPAY
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.60
  key: reviews-social-proof
  layer: common
  name: Reviews & Social Proof
  providers:
  - Broadly
  - Widewail
  url: /capabilities/reviews-social-proof/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20
  key: sms-messaging-apps
  layer: common
  name: SMS & Messaging Apps
  providers:
  - CallRevu
  - Kenect
  - TruVideo
  url: /capabilities/sms-messaging-apps/
  via_parent: null
category:
  id: auto-dealership
  name: Auto Dealership Management
  url: /applications/auto-dealership/
counts:
  declared: 36
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://dealerbuilt.com/partners/certified-partners/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-1320.20
    key: credit-underwriting-decisioning-management
    name: Credit Underwriting & Decisioning Management
    url: /capabilities/credit-underwriting-decisioning-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.8
    mcp: &id002
      status: unchecked
    slug: 700credit
    status: profiled
    tags: &id003
    - Automotive
    - Compliance
    - Credit
    - Identity Verification
    url: /providers/700credit/
  layer: domain
  name: 700Credit
  provider: 700credit
  says: lists 700Credit as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-950
    key: AE-950
    name: Dealer Management System Data Access
    url: /capabilities/dealer-management-system-data-access/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.8
    band: emerging
    in_catalog: true
    kin_score: 13.5
    mcp: &id004
      status: unchecked
    slug: authenticom
    status: profiled
    tags: &id005
    - Automotive
    - Data Experience Management
    - Dealership
    - OEM
    url: /providers/authenticom/
  layer: common
  name: Authenticom (DealerVault)
  provider: authenticom
  says: lists Authenticom (DealerVault) as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.3
    band: developing
    in_catalog: true
    kin_score: 53.9
    mcp: &id006
      status: none
    slug: autofi
    status: profiled
    tags: &id007
    - Automotive
    - Company
    - Digital Retail
    - Fintech
    url: /providers/autofi/
  layer: common
  name: AutoFi
  provider: autofi
  says: lists AutoFi as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3450
    key: vehicle-aftersales-warranty-management
    name: Vehicle Aftersales & Warranty Management
    url: /capabilities/vehicle-aftersales-warranty-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: minimal
    in_catalog: true
    kin_score: 7.3
    mcp: &id008
      status: unchecked
    slug: autoloop
    status: profiled
    tags: &id009
    - Automotive
    - Company
    - Dealership
    - Marketing
    url: /providers/autoloop/
  layer: domain
  name: AutoLoop
  provider: autoloop
  says: lists AutoLoop as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-948
    key: AE-948
    name: Vehicle Valuation & Appraisal Guides
    url: /capabilities/vehicle-valuation-appraisal-guides/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.4
    band: emerging
    in_catalog: true
    kin_score: 15.5
    mcp: &id010
      status: unchecked
    slug: black-book
    status: profiled
    tags: &id011
    - Analytics
    - Automotive
    - Company
    - Data
    url: /providers/black-book/
  layer: domain
  name: Black Book
  provider: black-book
  says: lists Black Book as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: reviews-social-proof
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
    mcp: &id012
      status: none
    slug: broadly
    status: profiled
    tags: &id013
    - AI Workforce
    - CRM
    - Local SEO
    - Reputation Management
    url: /providers/broadly/
  layer: common
  name: Broadly
  provider: broadly
  says: lists Broadly as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20
    key: sms-messaging-apps
    name: SMS & Messaging Apps
    url: /capabilities/sms-messaging-apps/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id014
      status: unchecked
    slug: callrevu
    status: profiled
    tags: &id015
    - Company
    url: /providers/callrevu/
  layer: common
  name: CallRevu
  provider: callrevu
  says: lists CallRevu as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-949
    key: AE-949
    name: Vehicle History Reports
    url: /capabilities/vehicle-history-reports/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 13.3
    band: emerging
    in_catalog: true
    kin_score: 18.2
    mcp: &id016
      status: none
    slug: carfax
    status: profiled
    tags: &id017
    - Automotive
    - Used Cars
    - VIN Lookup
    - Vehicle History
    url: /providers/carfax/
  layer: domain
  name: CARFAX
  provider: carfax
  says: lists CARFAX as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 13.9
    mcp: &id018
      status: unknown
    slug: carnow
    status: profiled
    tags: &id019
    - Automotive
    - Company
    - Dealership
    - Digital Retail
    url: /providers/carnow/
  layer: common
  name: CarNow
  provider: carnow
  says: lists CarNow as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4000.40
    key: ancillary-add-on-product-management
    name: Ancillary & Add-On Product Management
    url: /capabilities/ancillary-add-on-product-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id020
      status: unchecked
    slug: darwin-automotive
    status: profiled
    tags: &id021
    - Company
    url: /providers/darwin-automotive/
  layer: domain
  name: Darwin Automotive
  provider: darwin-automotive
  says: lists Darwin Automotive as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3440
    key: vehicle-sales-distribution-management
    name: Vehicle Sales & Distribution Management
    url: /capabilities/vehicle-sales-distribution-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.8
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id022
      status: none
    slug: cox-automotive
    status: profiled
    tags: &id023
    - Automotive
    - Cox Automotive
    - Vehicle Data
    - Vehicle Valuations
    url: /providers/cox-automotive/
  layer: domain
  name: Deal Central (Cox Automotive)
  provider: cox-automotive
  says: lists Deal Central (Cox Automotive) as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
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
    agent_band: agent-aware
    agent_readiness: 19.4
    band: thin
    in_catalog: true
    kin_score: 28.4
    mcp: &id024
      status: unknown
    slug: dealersocket
    status: profiled
    tags: &id025
    - Automotive
    - CRM
    - DMS
    - Dealership
    url: /providers/dealersocket/
  layer: common
  name: DealerSocket CRM
  provider: dealersocket
  says: lists DealerSocket CRM as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1320.10
    key: credit-origination-management
    name: Credit Origination Management
    url: /capabilities/credit-origination-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 10.8
    mcp: &id026
      status: unknown
    slug: dealertrack
    status: profiled
    tags: &id027
    - Automotive
    - DMS
    - Dealer Management System
    - Dealership
    url: /providers/dealertrack/
  layer: domain
  name: Dealertrack
  provider: dealertrack
  says: lists Dealertrack as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-950
    key: AE-950
    name: Dealer Management System Data Access
    url: /capabilities/dealer-management-system-data-access/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 26.5
    band: thin
    in_catalog: true
    kin_score: 39.0
    mcp: &id028
      source: https://www.cdkglobal.com/
      status: documented
    slug: cdk-global
    status: profiled
    tags: &id029
    - Auto Retail
    - Automotive
    - DMS
    - Dealer Management
    url: /providers/cdk-global/
  layer: common
  name: Digital Motorworks (CDK)
  provider: cdk-global
  says: lists Digital Motorworks (CDK) as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 20.2
    mcp: &id030
      status: unchecked
    slug: drivecentric
    status: profiled
    tags: &id031
    - AI Agents
    - Automotive CRM
    - Car Dealership Software
    - Sales Engagement
    url: /providers/drivecentric/
  layer: common
  name: DriveCentric
  provider: drivecentric
  says: lists DriveCentric as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3450
    key: vehicle-aftersales-warranty-management
    name: Vehicle Aftersales & Warranty Management
    url: /capabilities/vehicle-aftersales-warranty-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: minimal
    in_catalog: true
    kin_score: 6.1
    mcp: &id032
      status: unchecked
    slug: dynatron
    status: profiled
    tags: &id033
    - Artificial Intelligence
    - Automotive
    - Data Analytics
    - Fixed Ops
    url: /providers/dynatron/
  layer: domain
  name: Dynatron (ROAMS)
  provider: dynatron
  says: lists Dynatron (ROAMS) as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: Elead (CDK)
  provider: cdk-global
  says: lists Elead (CDK) as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
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
    agent_readiness: 22.0
    band: thin
    in_catalog: true
    kin_score: 26.5
    mcp: &id034
      source: https://github.com/globalpayments/mcp-server
      status: verified
    slug: global-payments
    status: profiled
    tags: &id035
    - E-Commerce
    - Payment Processing
    - Payment Technology
    - Payments
    url: /providers/global-payments/
  layer: common
  name: Global Payments
  provider: global-payments
  says: lists Global Payments as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-951
    key: AE-951
    name: Vehicle Inventory Listing Syndication
    url: /capabilities/vehicle-inventory-listing-syndication/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.5
    band: emerging
    in_catalog: true
    kin_score: 18.5
    mcp: &id036
      status: unchecked
    slug: homenet
    status: profiled
    tags: &id037
    - Automotive
    - Company
    - Dealer Solutions
    - Digital Merchandising
    url: /providers/homenet/
  layer: domain
  name: HomeNet (Cox Automotive)
  provider: homenet
  says: lists HomeNet (Cox Automotive) as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.30
    key: market-intelligence-management
    name: Market Intelligence Management
    url: /capabilities/market-intelligence-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id038
      status: unchecked
    slug: jd-power
    status: profiled
    tags: &id039
    - Company
    url: /providers/jd-power/
  layer: domain
  name: J.D. Power
  provider: jd-power
  says: lists J.D. Power as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3430
    key: dealer-network-management
    name: Dealer Network Management
    url: /capabilities/dealer-network-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 13.6
    mcp: &id040
      status: unknown
    slug: jlr
    status: profiled
    tags: &id041
    - Automotive
    - Company
    - Connected Vehicles
    - Vehicle Data
    url: /providers/jlr/
  layer: domain
  name: JLR
  provider: jlr
  says: lists JLR as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20
    key: sms-messaging-apps
    name: SMS & Messaging Apps
    url: /capabilities/sms-messaging-apps/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 23.6
    mcp: &id042
      status: unknown
    slug: kenect
    status: profiled
    tags: &id043
    - Artificial Intelligence
    - Automotive
    - Customer Engagement
    - Messaging
    url: /providers/kenect/
  layer: common
  name: Kenect
  provider: kenect
  says: lists Kenect as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 18.6
    mcp: &id044
      status: unchecked
    slug: lotlinx
    status: profiled
    tags: &id045
    - Automotive Inventory Management
    - Dealer Tools
    - Machine Learning
    - VIN Performance Platform
    url: /providers/lotlinx/
  layer: common
  name: LotLinx
  provider: lotlinx
  says: lists LotLinx as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1060
    key: spare-parts-aftermarket-management
    name: Spare Parts & Aftermarket Management
    url: /capabilities/spare-parts-aftermarket-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 8.7
    mcp: &id046
      status: unchecked
    slug: oeconnection
    status: profiled
    tags: &id047
    - Automotive
    - Dealership
    - Parts Management
    - Software
    url: /providers/oeconnection/
  layer: domain
  name: OEConnection
  provider: oeconnection
  says: lists OEConnection as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
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
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 17.7
    mcp: &id048
      status: unchecked
    slug: repay
    status: profiled
    tags: &id049
    - B2B
    - Fintech
    - Payments
    - Software-as-a-Service
    url: /providers/repay/
  layer: common
  name: REPAY
  provider: repay
  says: lists REPAY as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1060
    key: spare-parts-aftermarket-management
    name: Spare Parts & Aftermarket Management
    url: /capabilities/spare-parts-aftermarket-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.8
    band: emerging
    in_catalog: true
    kin_score: 19.1
    mcp: &id050
      status: unchecked
    slug: revolution-parts
    status: profiled
    tags: &id051
    - Automotive
    - Company
    - E-Commerce
    - Marketplace
    url: /providers/revolution-parts/
  layer: domain
  name: Revolution Parts
  provider: revolution-parts
  says: lists Revolution Parts as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3460.30
    key: in-vehicle-app-and-subscription-management
    name: In-Vehicle App and Subscription Management
    url: /capabilities/in-vehicle-app-and-subscription-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 21.4
    mcp: &id052
      status: unknown
    slug: sirius-xm
    status: profiled
    tags: &id053
    - Audio
    - Music
    - Radio
    - Streaming
    url: /providers/sirius-xm/
  layer: domain
  name: SiriusXM
  provider: sirius-xm
  says: lists SiriusXM as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4000.40
    key: ancillary-add-on-product-management
    name: Ancillary & Add-On Product Management
    url: /capabilities/ancillary-add-on-product-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.6
    mcp: &id054
      status: unknown
    slug: stoneeagle-f-and-i
    status: profiled
    tags: &id055
    - Automotive
    - Company
    - Dealership
    - Finance and Insurance
    url: /providers/stoneeagle-f-and-i/
  layer: domain
  name: StoneEagle F&I
  provider: stoneeagle-f-and-i
  says: lists StoneEagle F&I as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3430
    key: dealer-network-management
    name: Dealer Network Management
    url: /capabilities/dealer-network-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 7.1
    mcp: &id056
      status: none
    slug: subaru-of-america
    status: profiled
    tags: &id057
    - Automobiles
    - Automotive
    - Cars
    - Vehicles
    url: /providers/subaru-of-america/
  layer: domain
  name: Subaru of America
  provider: subaru-of-america
  says: lists Subaru of America as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-951
    key: AE-951
    name: Vehicle Inventory Listing Syndication
    url: /capabilities/vehicle-inventory-listing-syndication/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 12.4
    mcp: &id058
      status: none
    slug: truecar
    status: profiled
    tags: &id059
    - Automotive
    - Car Buying
    - Company
    - Marketplace
    url: /providers/truecar/
  layer: domain
  name: TrueCar
  provider: truecar
  says: lists TrueCar as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20
    key: sms-messaging-apps
    name: SMS & Messaging Apps
    url: /capabilities/sms-messaging-apps/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.5
    band: thin
    in_catalog: true
    kin_score: 38.8
    mcp: &id060
      status: none
    slug: truvideo
    status: profiled
    tags: &id061
    - Commerce
    - Company
    - Messaging
    - Video
    url: /providers/truvideo/
  layer: common
  name: TruVideo
  provider: truvideo
  says: lists TruVideo as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.30
    key: market-intelligence-management
    name: Market Intelligence Management
    url: /capabilities/market-intelligence-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.8
    mcp: &id062
      status: unchecked
    slug: urban-science
    status: profiled
    tags: &id063
    - Automotive
    - Company
    - Data Analytics
    - Media
    url: /providers/urban-science/
  layer: domain
  name: Urban Science
  provider: urban-science
  says: lists Urban Science as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-948
    key: AE-948
    name: Vehicle Valuation & Appraisal Guides
    url: /capabilities/vehicle-valuation-appraisal-guides/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.1
    mcp: &id064
      status: unknown
    slug: vauto
    status: profiled
    tags: &id065
    - Appraisal
    - Automotive
    - Dealership
    - Inventory
    url: /providers/vauto/
  layer: domain
  name: vAuto
  provider: vauto
  says: lists vAuto as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.2
    mcp: &id066
      status: unchecked
    slug: vinsolutions
    status: profiled
    tags: &id067
    - Automotive
    - CRM
    - Dealership
    - Software
    url: /providers/vinsolutions/
  layer: common
  name: VinSolutions
  provider: vinsolutions
  says: lists VinSolutions as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: reviews-social-proof
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.5
    band: thin
    in_catalog: true
    kin_score: 35.7
    mcp: &id068
      status: unchecked
    slug: widewail
    status: profiled
    tags: &id069
    - Automotive
    - Company
    - Customer Intelligence
    - Software-as-a-Service
    url: /providers/widewail/
  layer: common
  name: Widewail
  provider: widewail
  says: lists Widewail as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3450
    key: vehicle-aftersales-warranty-management
    name: Vehicle Aftersales & Warranty Management
    url: /capabilities/vehicle-aftersales-warranty-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.3
    mcp: &id070
      status: unknown
    slug: xtime
    status: profiled
    tags: &id071
    - Automotive
    - Company
    - Dealership
    - Vertical Software
    url: /providers/xtime/
  layer: domain
  name: Xtime
  provider: xtime
  says: lists Xtime as an integration
  source: https://dealerbuilt.com/partners/certified-partners/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/auto-dealership/dealerbuilt-lightyear-dms/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.8
  mcp: *id002
  name: 700Credit
  slug: 700credit
  status: profiled
  tags: *id003
  url: /providers/700credit/
- agent_band: agent-aware
  agent_readiness: 17.8
  band: emerging
  in_catalog: true
  kin_score: 13.5
  mcp: *id004
  name: Authenticom (DealerVault)
  slug: authenticom
  status: profiled
  tags: *id005
  url: /providers/authenticom/
- agent_band: agent-ready
  agent_readiness: 54.3
  band: developing
  in_catalog: true
  kin_score: 53.9
  mcp: *id006
  name: AutoFi
  slug: autofi
  status: profiled
  tags: *id007
  url: /providers/autofi/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: minimal
  in_catalog: true
  kin_score: 7.3
  mcp: *id008
  name: AutoLoop
  slug: autoloop
  status: profiled
  tags: *id009
  url: /providers/autoloop/
- agent_band: agent-aware
  agent_readiness: 21.4
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id010
  name: Black Book
  slug: black-book
  status: profiled
  tags: *id011
  url: /providers/black-book/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.2
  mcp: *id012
  name: Broadly
  slug: broadly
  status: profiled
  tags: *id013
  url: /providers/broadly/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id014
  name: CallRevu
  slug: callrevu
  status: profiled
  tags: *id015
  url: /providers/callrevu/
- agent_band: agent-aware
  agent_readiness: 13.3
  band: emerging
  in_catalog: true
  kin_score: 18.2
  mcp: *id016
  name: CARFAX
  slug: carfax
  status: profiled
  tags: *id017
  url: /providers/carfax/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.9
  mcp: *id018
  name: CarNow
  slug: carnow
  status: profiled
  tags: *id019
  url: /providers/carnow/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id020
  name: Darwin Automotive
  slug: darwin-automotive
  status: profiled
  tags: *id021
  url: /providers/darwin-automotive/
- agent_band: agent-ready
  agent_readiness: 33.8
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id022
  name: Deal Central (Cox Automotive)
  slug: cox-automotive
  status: profiled
  tags: *id023
  url: /providers/cox-automotive/
- agent_band: agent-aware
  agent_readiness: 19.4
  band: thin
  in_catalog: true
  kin_score: 28.4
  mcp: *id024
  name: DealerSocket CRM
  slug: dealersocket
  status: profiled
  tags: *id025
  url: /providers/dealersocket/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 10.8
  mcp: *id026
  name: Dealertrack
  slug: dealertrack
  status: profiled
  tags: *id027
  url: /providers/dealertrack/
- agent_band: agent-aware
  agent_readiness: 26.5
  band: thin
  in_catalog: true
  kin_score: 39.0
  mcp: *id028
  name: Digital Motorworks (CDK)
  slug: cdk-global
  status: profiled
  tags: *id029
  url: /providers/cdk-global/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.2
  mcp: *id030
  name: DriveCentric
  slug: drivecentric
  status: profiled
  tags: *id031
  url: /providers/drivecentric/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: minimal
  in_catalog: true
  kin_score: 6.1
  mcp: *id032
  name: Dynatron (ROAMS)
  slug: dynatron
  status: profiled
  tags: *id033
  url: /providers/dynatron/
- agent_band: agent-aware
  agent_readiness: 22.0
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id034
  name: Global Payments
  slug: global-payments
  status: profiled
  tags: *id035
  url: /providers/global-payments/
- agent_band: agent-aware
  agent_readiness: 14.5
  band: emerging
  in_catalog: true
  kin_score: 18.5
  mcp: *id036
  name: HomeNet (Cox Automotive)
  slug: homenet
  status: profiled
  tags: *id037
  url: /providers/homenet/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id038
  name: J.D. Power
  slug: jd-power
  status: profiled
  tags: *id039
  url: /providers/jd-power/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.6
  mcp: *id040
  name: JLR
  slug: jlr
  status: profiled
  tags: *id041
  url: /providers/jlr/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 23.6
  mcp: *id042
  name: Kenect
  slug: kenect
  status: profiled
  tags: *id043
  url: /providers/kenect/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.6
  mcp: *id044
  name: LotLinx
  slug: lotlinx
  status: profiled
  tags: *id045
  url: /providers/lotlinx/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 8.7
  mcp: *id046
  name: OEConnection
  slug: oeconnection
  status: profiled
  tags: *id047
  url: /providers/oeconnection/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 17.7
  mcp: *id048
  name: REPAY
  slug: repay
  status: profiled
  tags: *id049
  url: /providers/repay/
- agent_band: agent-aware
  agent_readiness: 17.8
  band: emerging
  in_catalog: true
  kin_score: 19.1
  mcp: *id050
  name: Revolution Parts
  slug: revolution-parts
  status: profiled
  tags: *id051
  url: /providers/revolution-parts/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 21.4
  mcp: *id052
  name: SiriusXM
  slug: sirius-xm
  status: profiled
  tags: *id053
  url: /providers/sirius-xm/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.6
  mcp: *id054
  name: StoneEagle F&I
  slug: stoneeagle-f-and-i
  status: profiled
  tags: *id055
  url: /providers/stoneeagle-f-and-i/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 7.1
  mcp: *id056
  name: Subaru of America
  slug: subaru-of-america
  status: profiled
  tags: *id057
  url: /providers/subaru-of-america/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 12.4
  mcp: *id058
  name: TrueCar
  slug: truecar
  status: profiled
  tags: *id059
  url: /providers/truecar/
- agent_band: agent-aware
  agent_readiness: 19.5
  band: thin
  in_catalog: true
  kin_score: 38.8
  mcp: *id060
  name: TruVideo
  slug: truvideo
  status: profiled
  tags: *id061
  url: /providers/truvideo/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.8
  mcp: *id062
  name: Urban Science
  slug: urban-science
  status: profiled
  tags: *id063
  url: /providers/urban-science/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.1
  mcp: *id064
  name: vAuto
  slug: vauto
  status: profiled
  tags: *id065
  url: /providers/vauto/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.2
  mcp: *id066
  name: VinSolutions
  slug: vinsolutions
  status: profiled
  tags: *id067
  url: /providers/vinsolutions/
- agent_band: agent-aware
  agent_readiness: 14.5
  band: thin
  in_catalog: true
  kin_score: 35.7
  mcp: *id068
  name: Widewail
  slug: widewail
  status: profiled
  tags: *id069
  url: /providers/widewail/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.3
  mcp: *id070
  name: Xtime
  slug: xtime
  status: profiled
  tags: *id071
  url: /providers/xtime/
siblings:
- name: AutoHub
  rows: 17
  url: /applications/auto-dealership/autohub/
- name: AutoRaptor
  rows: 3
  url: /applications/auto-dealership/autoraptor/
- name: Autosoft DMS
  rows: 16
  url: /applications/auto-dealership/autosoft-dms/
- name: Cox Automotive Deal Central
  rows: 11
  url: /applications/auto-dealership/cox-automotive-deal-central/
- name: DealersCloud
  rows: 19
  url: /applications/auto-dealership/dealerscloud/
- name: DealerSocket
  rows: 1
  url: /applications/auto-dealership/dealersocket/
- name: GetMyAuto
  rows: 36
  url: /applications/auto-dealership/getmyauto/
sitemap: true
title: 'DealerBuilt (LightYear DMS): Auto Dealership Management reference app'
---
