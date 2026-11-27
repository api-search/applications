---
app: GetMyAuto
app_slug: getmyauto
app_url: https://dealers.getmyauto.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-140.80.20
  key: AE-140.80.20
  layer: domain
  name: B2B Marketplaces
  providers:
  - Manheim
  url: /capabilities/marketplaces/
  via_parent: Marketplaces
- attribution: Turbo EA
  id: BC-1320.10
  key: credit-origination-management
  layer: domain
  name: Credit Origination Management
  providers:
  - Capital One
  - Chase
  - Credit Acceptance
  - CUDL
  - Dealertrack
  - RouteOne
  - United Auto Credit (UACC)
  - Upgrade
  - Upstart
  url: /capabilities/credit-origination-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1320.20
  key: credit-underwriting-decisioning-management
  layer: domain
  name: Credit Underwriting & Decisioning Management
  providers:
  - 700Credit
  - Equifax
  - Experian
  - TransUnion
  url: /capabilities/credit-underwriting-decisioning-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2330.40
  key: marketplace-seller-operations-management
  layer: domain
  name: Marketplace Seller Operations Management
  providers:
  - Google
  url: /capabilities/marketplace-seller-operations-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-949
  key: AE-949
  layer: domain
  name: Vehicle History Reports
  providers:
  - AutoCheck (Experian)
  - CARFAX
  - NMVTIS
  url: /capabilities/vehicle-history-reports/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-951
  key: AE-951
  layer: domain
  name: Vehicle Inventory Listing Syndication
  providers:
  - Autotrader
  - CarGurus
  - Cars.com
  - Carsforsale.com
  - Craigslist
  - Cruz.com
  - DealerCarSearch
  - eBay Motors
  - Facebook Marketplace
  - HomeNet
  - TrueCar
  url: /capabilities/vehicle-inventory-listing-syndication/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-948
  key: AE-948
  layer: domain
  name: Vehicle Valuation & Appraisal Guides
  providers:
  - Black Book
  - Edmunds
  - J.D. Power (NADA Guides)
  - Kelley Blue Book
  - vAuto
  - VinCue
  url: /capabilities/vehicle-valuation-appraisal-guides/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - QuickBooks
  url: /capabilities/general-ledger-management/
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
  url: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-949
    key: AE-949
    name: Vehicle History Reports
    url: /capabilities/vehicle-history-reports/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.4
    band: strong
    in_catalog: true
    kin_score: 60.9
    mcp: &id004
      status: none
    slug: experian
    status: profiled
    tags: &id005
    - Company
    - Credit Bureau
    - Credit Reporting
    - Identity Verification
    url: /providers/experian/
  layer: domain
  name: AutoCheck (Experian)
  provider: experian
  says: lists AutoCheck (Experian) as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.0
    mcp: &id006
      status: unknown
    slug: autotradercom
    status: profiled
    tags: &id007
    - Automotive
    - Company
    - Consumer
    - Marketplace
    url: /providers/autotradercom/
  layer: domain
  name: Autotrader
  provider: autotradercom
  says: lists Autotrader as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    mcp: &id008
      status: unchecked
    slug: black-book
    status: profiled
    tags: &id009
    - Analytics
    - Automotive
    - Company
    - Data
    url: /providers/black-book/
  layer: domain
  name: Black Book
  provider: black-book
  says: lists Black Book as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_readiness: 3.1
    band: thin
    in_catalog: true
    kin_score: 34.0
    mcp: &id010
      status: none
    slug: capital-one
    status: profiled
    tags: &id011
    - Authorization
    - Auto Finance
    - Banking
    - Credit Cards
    url: /providers/capital-one/
  layer: domain
  name: Capital One
  provider: capital-one
  says: lists Capital One as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    mcp: &id012
      status: none
    slug: carfax
    status: profiled
    tags: &id013
    - Automotive
    - Used Cars
    - VIN Lookup
    - Vehicle History
    url: /providers/carfax/
  layer: domain
  name: CARFAX
  provider: carfax
  says: lists CARFAX as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 29.2
    mcp: &id014
      source: https://cargurus.helpscoutdocs.com/article/599-connect-ai-assistants-to-cargurus-with-the-mcp-connector
      status: verified
    slug: cargurus-dealer
    status: profiled
    tags: &id015
    - Automotive
    - Car Listings
    - Dealers
    - Marketplace
    url: /providers/cargurus-dealer/
  layer: domain
  name: CarGurus
  provider: cargurus-dealer
  says: lists CarGurus as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 1.3
    mcp: &id016
      status: unchecked
    slug: cars-com
    status: profiled
    tags: &id017
    - Car Buying
    - Car Selling
    - Vehicle Research
    url: /providers/cars-com/
  layer: domain
  name: Cars.com
  provider: cars-com
  says: lists Cars.com as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 6.4
    mcp: &id018
      status: unchecked
    slug: carsforsale
    status: profiled
    tags: &id019
    - Automotive
    - Company
    - Marketplace
    - Vehicles
    url: /providers/carsforsale/
  layer: domain
  name: Carsforsale.com
  provider: carsforsale
  says: lists Carsforsale.com as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_band: agent-aware
    agent_readiness: 25.7
    band: thin
    in_catalog: true
    kin_score: 34.9
    mcp: &id020
      status: none
    slug: chase
    status: profiled
    tags: &id021
    - Account Aggregation
    - Banking
    - Consent
    - Credit Cards
    url: /providers/chase/
  layer: domain
  name: Chase
  provider: chase
  says: lists Chase as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 23.2
    mcp: &id022
      status: none
    slug: craigslist
    status: profiled
    tags: &id023
    - Classifieds
    - Company
    - Job
    - Marketplace
    url: /providers/craigslist/
  layer: domain
  name: Craigslist
  provider: craigslist
  says: lists Craigslist as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 7.6
    mcp: &id024
      status: unchecked
    slug: credit-acceptance
    status: profiled
    tags: &id025
    - Auto
    - Finance
    - Lending
    - Subprime
    url: /providers/credit-acceptance/
  layer: domain
  name: Credit Acceptance
  provider: credit-acceptance
  says: lists Credit Acceptance as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id026
      status: unchecked
    slug: cruz
    status: queued for profiling
    tags: &id027 []
    url: null
  layer: domain
  name: Cruz.com
  provider: cruz
  says: lists Cruz.com as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_band: agent-aware
    agent_readiness: 21.4
    band: emerging
    in_catalog: true
    kin_score: 15.5
    mcp: &id028
      status: unchecked
    slug: cudl
    status: profiled
    tags: &id029
    - Auto Finance
    - Company
    - Fintech
    - Lending
    url: /providers/cudl/
  layer: domain
  name: CUDL
  provider: cudl
  says: lists CUDL as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 8.5
    mcp: &id030
      status: unchecked
    slug: dealercarsearch
    status: profiled
    tags: &id031
    - Automotive
    - Company
    - Lead Management
    - Web Design
    url: /providers/dealercarsearch/
  layer: domain
  name: DealerCarSearch
  provider: dealercarsearch
  says: lists DealerCarSearch as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    mcp: &id032
      status: unknown
    slug: dealertrack
    status: profiled
    tags: &id033
    - Automotive
    - DMS
    - Dealer Management System
    - Dealership
    url: /providers/dealertrack/
  layer: domain
  name: Dealertrack
  provider: dealertrack
  says: lists Dealertrack as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_band: agent-ready
    agent_readiness: 31.3
    band: developing
    in_catalog: true
    kin_score: 48.7
    mcp: &id034
      source: https://github.com/eBay/npm-public-api-mcp
      status: verified
    slug: ebay
    status: profiled
    tags: &id035
    - Auctions
    - Commerce
    - Marketplace
    - Product
    url: /providers/ebay/
  layer: domain
  name: eBay Motors
  provider: ebay
  says: lists eBay Motors as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_readiness: 28.4
    band: thin
    in_catalog: true
    kin_score: 33.6
    mcp: &id036
      status: none
    slug: edmunds
    status: profiled
    tags: &id037
    - Automobiles
    - Cars
    - Vehicle Data
    - Vehicles
    url: /providers/edmunds/
  layer: domain
  name: Edmunds
  provider: edmunds
  says: lists Edmunds as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1320.20
    key: credit-underwriting-decisioning-management
    name: Credit Underwriting & Decisioning Management
    url: /capabilities/credit-underwriting-decisioning-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 7.7
    band: developing
    in_catalog: true
    kin_score: 47.1
    mcp: &id038
      status: none
    slug: equifax
    status: profiled
    tags: &id039
    - Credit
    - Credit History
    - Credit Reporting
    - Identity
    url: /providers/equifax/
  layer: domain
  name: Equifax
  provider: equifax
  says: lists Equifax as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1320.20
    key: credit-underwriting-decisioning-management
    name: Credit Underwriting & Decisioning Management
    url: /capabilities/credit-underwriting-decisioning-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: domain
  name: Experian
  provider: experian
  says: lists Experian as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id040
      status: none
    slug: facebook
    status: profiled
    tags: &id041
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook Marketplace
  provider: facebook
  says: lists Facebook Marketplace as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2330.40
    key: marketplace-seller-operations-management
    name: Marketplace Seller Operations Management
    url: /capabilities/marketplace-seller-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id042
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id043
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: Google
  provider: google
  says: lists Google as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    mcp: &id044
      status: unchecked
    slug: homenet
    status: profiled
    tags: &id045
    - Automotive
    - Company
    - Dealer Solutions
    - Digital Merchandising
    url: /providers/homenet/
  layer: domain
  name: HomeNet
  provider: homenet
  says: lists HomeNet as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    kin_score: 0.4
    mcp: &id046
      status: unchecked
    slug: jd-power
    status: profiled
    tags: &id047
    - Company
    url: /providers/jd-power/
  layer: domain
  name: J.D. Power (NADA Guides)
  provider: jd-power
  says: lists J.D. Power (NADA Guides) as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_readiness: 3.1
    band: emerging
    in_catalog: true
    kin_score: 13.3
    mcp: &id048
      status: unknown
    slug: kbb
    status: profiled
    tags: &id049
    - Automotive
    - Car Pricing
    - Trade-In
    - Vehicle Valuation
    url: /providers/kbb/
  layer: domain
  name: Kelley Blue Book
  provider: kbb
  says: lists Kelley Blue Book as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.80.20
    key: AE-140.80.20
    name: B2B Marketplaces
    url: /capabilities/marketplaces/
    via_parent: Marketplaces
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 12.9
    mcp: &id050
      status: unchecked
    slug: manheim
    status: profiled
    tags: &id051
    - Automotive
    - Marketplace
    - Vehicles
    - Wholesale
    url: /providers/manheim/
  layer: domain
  name: Manheim
  provider: manheim
  says: lists Manheim as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.6
    mcp: &id052
      status: unchecked
    slug: nmvtis
    status: profiled
    tags: &id053
    - Consumer Protection
    - Government
    - Law Enforcement
    - Vehicle History
    url: /providers/nmvtis/
  layer: domain
  name: NMVTIS
  provider: nmvtis
  says: lists NMVTIS as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    mcp: &id054
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id055
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 2.6
    mcp: &id056
      status: unchecked
    slug: routeone
    status: profiled
    tags: &id057
    - Automotive
    - Finance
    - Fintech
    - Insurance
    url: /providers/routeone/
  layer: domain
  name: RouteOne
  provider: routeone
  says: lists RouteOne as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1320.20
    key: credit-underwriting-decisioning-management
    name: Credit Underwriting & Decisioning Management
    url: /capabilities/credit-underwriting-decisioning-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: thin
    in_catalog: true
    kin_score: 28.0
    mcp: &id058
      status: unknown
    slug: transunion
    status: profiled
    tags: &id059
    - Credit Reporting
    - Finance
    - Identity
    - Risk Management
    url: /providers/transunion/
  layer: domain
  name: TransUnion
  provider: transunion
  says: lists TransUnion as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    mcp: &id060
      status: none
    slug: truecar
    status: profiled
    tags: &id061
    - Automotive
    - Car Buying
    - Company
    - Marketplace
    url: /providers/truecar/
  layer: domain
  name: TrueCar
  provider: truecar
  says: lists TrueCar as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 13.5
    mcp: &id062
      status: unchecked
    slug: uacc
    status: profiled
    tags: &id063
    - Auto
    - Finance
    - Lending
    - Non-prime
    url: /providers/uacc/
  layer: domain
  name: United Auto Credit (UACC)
  provider: uacc
  says: lists United Auto Credit (UACC) as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 47.5
    mcp: &id064
      status: unknown
    slug: upgrade
    status: profiled
    tags: &id065
    - Buy Now Pay Later
    - Company
    - Fintech
    - Lending
    url: /providers/upgrade/
  layer: domain
  name: Upgrade
  provider: upgrade
  says: lists Upgrade as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 18.3
    mcp: &id066
      status: none
    slug: upstart
    status: profiled
    tags: &id067
    - Company
    - Credit
    - Fintech
    - Lending
    url: /providers/upstart/
  layer: domain
  name: Upstart
  provider: upstart
  says: lists Upstart as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    mcp: &id068
      status: unknown
    slug: vauto
    status: profiled
    tags: &id069
    - Appraisal
    - Automotive
    - Dealership
    - Inventory
    url: /providers/vauto/
  layer: domain
  name: vAuto
  provider: vauto
  says: lists vAuto as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
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
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 6.0
    mcp: &id070
      status: unchecked
    slug: vincue
    status: profiled
    tags: &id071
    - Automotive
    - Dealership
    - Inventory
    - Software-as-a-Service
    url: /providers/vincue/
  layer: domain
  name: VinCue
  provider: vincue
  says: lists VinCue as an integration
  source: https://dealers.getmyauto.com/integrations-for-auto-dealers
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/auto-dealership/getmyauto/
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
- agent_band: agent-ready
  agent_readiness: 39.4
  band: strong
  in_catalog: true
  kin_score: 60.9
  mcp: *id004
  name: AutoCheck (Experian)
  slug: experian
  status: profiled
  tags: *id005
  url: /providers/experian/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.0
  mcp: *id006
  name: Autotrader
  slug: autotradercom
  status: profiled
  tags: *id007
  url: /providers/autotradercom/
- agent_band: agent-aware
  agent_readiness: 21.4
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id008
  name: Black Book
  slug: black-book
  status: profiled
  tags: *id009
  url: /providers/black-book/
- agent_band: human-only
  agent_readiness: 3.1
  band: thin
  in_catalog: true
  kin_score: 34.0
  mcp: *id010
  name: Capital One
  slug: capital-one
  status: profiled
  tags: *id011
  url: /providers/capital-one/
- agent_band: agent-aware
  agent_readiness: 13.3
  band: emerging
  in_catalog: true
  kin_score: 18.2
  mcp: *id012
  name: CARFAX
  slug: carfax
  status: profiled
  tags: *id013
  url: /providers/carfax/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 29.2
  mcp: *id014
  name: CarGurus
  slug: cargurus-dealer
  status: profiled
  tags: *id015
  url: /providers/cargurus-dealer/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 1.3
  mcp: *id016
  name: Cars.com
  slug: cars-com
  status: profiled
  tags: *id017
  url: /providers/cars-com/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 6.4
  mcp: *id018
  name: Carsforsale.com
  slug: carsforsale
  status: profiled
  tags: *id019
  url: /providers/carsforsale/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: thin
  in_catalog: true
  kin_score: 34.9
  mcp: *id020
  name: Chase
  slug: chase
  status: profiled
  tags: *id021
  url: /providers/chase/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 23.2
  mcp: *id022
  name: Craigslist
  slug: craigslist
  status: profiled
  tags: *id023
  url: /providers/craigslist/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 7.6
  mcp: *id024
  name: Credit Acceptance
  slug: credit-acceptance
  status: profiled
  tags: *id025
  url: /providers/credit-acceptance/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id026
  name: Cruz.com
  slug: cruz
  status: queued for profiling
  tags: *id027
  url: null
- agent_band: agent-aware
  agent_readiness: 21.4
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id028
  name: CUDL
  slug: cudl
  status: profiled
  tags: *id029
  url: /providers/cudl/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id030
  name: DealerCarSearch
  slug: dealercarsearch
  status: profiled
  tags: *id031
  url: /providers/dealercarsearch/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 10.8
  mcp: *id032
  name: Dealertrack
  slug: dealertrack
  status: profiled
  tags: *id033
  url: /providers/dealertrack/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 48.7
  mcp: *id034
  name: eBay Motors
  slug: ebay
  status: profiled
  tags: *id035
  url: /providers/ebay/
- agent_band: agent-aware
  agent_readiness: 28.4
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id036
  name: Edmunds
  slug: edmunds
  status: profiled
  tags: *id037
  url: /providers/edmunds/
- agent_band: agent-aware
  agent_readiness: 7.7
  band: developing
  in_catalog: true
  kin_score: 47.1
  mcp: *id038
  name: Equifax
  slug: equifax
  status: profiled
  tags: *id039
  url: /providers/equifax/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id040
  name: Facebook Marketplace
  slug: facebook
  status: profiled
  tags: *id041
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id042
  name: Google
  slug: google
  status: profiled
  tags: *id043
  url: /providers/google/
- agent_band: agent-aware
  agent_readiness: 14.5
  band: emerging
  in_catalog: true
  kin_score: 18.5
  mcp: *id044
  name: HomeNet
  slug: homenet
  status: profiled
  tags: *id045
  url: /providers/homenet/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id046
  name: J.D. Power (NADA Guides)
  slug: jd-power
  status: profiled
  tags: *id047
  url: /providers/jd-power/
- agent_band: human-only
  agent_readiness: 3.1
  band: emerging
  in_catalog: true
  kin_score: 13.3
  mcp: *id048
  name: Kelley Blue Book
  slug: kbb
  status: profiled
  tags: *id049
  url: /providers/kbb/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 12.9
  mcp: *id050
  name: Manheim
  slug: manheim
  status: profiled
  tags: *id051
  url: /providers/manheim/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.6
  mcp: *id052
  name: NMVTIS
  slug: nmvtis
  status: profiled
  tags: *id053
  url: /providers/nmvtis/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id054
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id055
  url: /providers/quickbooks/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 2.6
  mcp: *id056
  name: RouteOne
  slug: routeone
  status: profiled
  tags: *id057
  url: /providers/routeone/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: thin
  in_catalog: true
  kin_score: 28.0
  mcp: *id058
  name: TransUnion
  slug: transunion
  status: profiled
  tags: *id059
  url: /providers/transunion/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 12.4
  mcp: *id060
  name: TrueCar
  slug: truecar
  status: profiled
  tags: *id061
  url: /providers/truecar/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 13.5
  mcp: *id062
  name: United Auto Credit (UACC)
  slug: uacc
  status: profiled
  tags: *id063
  url: /providers/uacc/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 47.5
  mcp: *id064
  name: Upgrade
  slug: upgrade
  status: profiled
  tags: *id065
  url: /providers/upgrade/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.3
  mcp: *id066
  name: Upstart
  slug: upstart
  status: profiled
  tags: *id067
  url: /providers/upstart/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.1
  mcp: *id068
  name: vAuto
  slug: vauto
  status: profiled
  tags: *id069
  url: /providers/vauto/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 6.0
  mcp: *id070
  name: VinCue
  slug: vincue
  status: profiled
  tags: *id071
  url: /providers/vincue/
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
- name: DealerBuilt (LightYear DMS)
  rows: 36
  url: /applications/auto-dealership/dealerbuilt-lightyear-dms/
- name: DealersCloud
  rows: 19
  url: /applications/auto-dealership/dealerscloud/
- name: DealerSocket
  rows: 1
  url: /applications/auto-dealership/dealersocket/
sitemap: true
title: 'GetMyAuto: Auto Dealership Management reference app'
---
