---
app: GoFundMe Pro (Classy)
app_slug: gofundme-pro-classy
app_url: https://pro.gofundme.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.10
  key: AE-130.10
  layer: domain
  name: Activity & Fitness Tracking
  providers:
  - Charity Miles
  url: /capabilities/activity-fitness-tracking/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.30
  key: AE-140.30
  layer: domain
  name: Consumer Payment Options
  providers:
  - GivingIQ (formerly DonateStock)
  url: /capabilities/consumer-payment-options/
  via_parent: null
- attribution: Turbo EA
  id: BC-4800.20
  key: donor-relationship-management
  layer: domain
  name: Donor Relationship Management
  providers:
  - Blackbaud CRM / Raiser's Edge NXT
  - Bloomerang
  - CiviCRM
  - Daxko
  - DonorDock
  - DonorPerfect
  - EveryAction (Bonterra)
  - Humanitru
  - Kindful
  - Little Green Light
  - Neon One
  - NetForum
  - Salsa Engage
  - Tessitura
  - Virtuous
  url: /capabilities/donor-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.30.30
  key: AE-230.30.30
  layer: domain
  name: Employer Matching-Gift Data
  providers:
  - Double the Donation
  url: /capabilities/company-contact-data/
  via_parent: Company & Contact Data
- attribution: Turbo EA
  id: BC-4800.30
  key: fundraising-campaign-management
  layer: domain
  name: Fundraising Campaign Management
  providers:
  - DonorDrive
  - EverGiving
  - GoodUnited
  - Grassroots Unwired
  - Nuclavis
  url: /capabilities/fundraising-campaign-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.70
  key: AE-140.70
  layer: domain
  name: Social & Creator Commerce
  providers:
  - Bonfire
  url: /capabilities/social-creator-commerce/
  via_parent: null
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Amazon Redshift
  - Bytespree
  - Snowflake
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Microsoft Dynamics
  - Salesforce (NPSP, Nonprofit Cloud)
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Constant Contact
  - Facebook / Meta Pixel / Meta CAPI
  - Feathr
  - Klaviyo
  - Mailchimp
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - QuickBooks Online
  - Sage Intacct
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20
  key: AE-150.20
  layer: common
  name: SMS & Messaging Apps
  providers:
  - Mobile Commons
  - Tatango
  url: /capabilities/sms-messaging-apps/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: common
  name: Social Networks & Community
  providers:
  - Instagram
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: common
  name: Tag Management
  providers:
  - Google Tag Manager
  - Tealium
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - BrightVine
  - Omatic
  - SyncSmart
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: donations-crowdfunding
  name: Donations & Crowdfunding
  url: /applications/donations-crowdfunding/
counts:
  declared: 47
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://pro.gofundme.com/c/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.1
    band: strong
    in_catalog: true
    kin_score: 63.6
    mcp: &id001
      source: https://github.com/awslabs/mcp/tree/main/src/redshift-mcp-server
      status: verified
    slug: amazon-redshift
    status: profiled
    tags: &id002
    - Analytics
    - Big Data
    - Cloud
    - Data Lake
    url: /providers/amazon-redshift/
  layer: common
  name: Amazon Redshift
  provider: amazon-redshift
  says: lists Amazon Redshift as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20
    key: donor-relationship-management
    name: Donor Relationship Management
    url: /capabilities/donor-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.2
    band: developing
    in_catalog: true
    kin_score: 39.3
    mcp: &id003
      status: none
    slug: blackbaud
    status: profiled
    tags: &id004
    - CRM
    - Donor Management
    - Fundraising
    - Non-Profit
    url: /providers/blackbaud/
  layer: domain
  name: Blackbaud CRM / Raiser's Edge NXT
  provider: blackbaud
  says: lists Blackbaud CRM / Raiser's Edge NXT as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20
    key: donor-relationship-management
    name: Donor Relationship Management
    url: /capabilities/donor-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.6
    band: thin
    in_catalog: true
    kin_score: 30.6
    mcp: &id005
      status: none
    slug: bloomerang
    status: profiled
    tags: &id006
    - CRM
    - Donor Management
    - Fundraising
    - Non-Profit
    url: /providers/bloomerang/
  layer: domain
  name: Bloomerang
  provider: bloomerang
  says: lists Bloomerang as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.70
    key: AE-140.70
    name: Social & Creator Commerce
    url: /capabilities/social-creator-commerce/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.5
    mcp: &id007
      status: unknown
    slug: bonfire
    status: profiled
    tags: &id008
    - Company
    - E-Commerce
    - Fundraising
    - Merchandising
    url: /providers/bonfire/
  layer: domain
  name: Bonfire
  provider: bonfire
  says: lists Bonfire as an integration
  source: https://pro.gofundme.com/c/integrations/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id009
      status: unchecked
    slug: brightvine
    status: queued for profiling
    tags: &id010 []
    url: null
  layer: common
  name: BrightVine
  provider: brightvine
  says: lists BrightVine as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 7.1
    mcp: &id011
      status: unknown
    slug: bytespree
    status: profiled
    tags: &id012
    - Company
    - Data Platform
    - Non-Profit
    - Open Source
    url: /providers/bytespree/
  layer: common
  name: Bytespree
  provider: bytespree
  says: lists Bytespree as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.10
    key: AE-130.10
    name: Activity & Fitness Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 15.3
    band: minimal
    in_catalog: true
    kin_score: 9.4
    mcp: &id013
      status: unknown
    slug: charity-miles
    status: profiled
    tags: &id014
    - Charity
    - Company
    - Fitness
    - Mobile App
    url: /providers/charity-miles/
  layer: domain
  name: Charity Miles
  provider: charity-miles
  says: lists Charity Miles as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20
    key: donor-relationship-management
    name: Donor Relationship Management
    url: /capabilities/donor-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.6
    band: emerging
    in_catalog: true
    kin_score: 18.1
    mcp: &id015
      source: https://docs.civicrm.org/
      status: verified
    slug: civicrm
    status: profiled
    tags: &id016
    - CRM
    - Community
    - Non-Profit
    - Open Source
    url: /providers/civicrm/
  layer: domain
  name: CiviCRM
  provider: civicrm
  says: lists CiviCRM as an integration
  source: https://pro.gofundme.com/c/integrations/
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
    agent_readiness: 32.1
    band: exemplar
    in_catalog: true
    kin_score: 70.9
    mcp: &id017
      status: none
    slug: constant-contact
    status: profiled
    tags: &id018
    - Campaigns
    - Contacts
    - Email Marketing
    - Event
    url: /providers/constant-contact/
  layer: common
  name: Constant Contact
  provider: constant-contact
  says: lists Constant Contact as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20
    key: donor-relationship-management
    name: Donor Relationship Management
    url: /capabilities/donor-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.0
    band: emerging
    in_catalog: true
    kin_score: 13.5
    mcp: &id019
      status: none
    slug: daxko
    status: profiled
    tags: &id020
    - Company
    - Fitness
    - Non-Profit
    - Software
    url: /providers/daxko/
  layer: domain
  name: Daxko
  provider: daxko
  says: lists Daxko as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20
    key: donor-relationship-management
    name: Donor Relationship Management
    url: /capabilities/donor-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.5
    mcp: &id021
      source: https://www.donordock.com/mcp
      status: verified
    slug: donordock
    status: profiled
    tags: &id022
    - Donor Management
    - Fundraising
    - Non-Profit
    - Software-as-a-Service
    url: /providers/donordock/
  layer: domain
  name: DonorDock
  provider: donordock
  says: lists DonorDock as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.30
    key: fundraising-campaign-management
    name: Fundraising Campaign Management
    url: /capabilities/fundraising-campaign-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.2
    band: minimal
    in_catalog: true
    kin_score: 8.5
    mcp: &id023
      status: none
    slug: donordrive
    status: profiled
    tags: &id024
    - Company
    - Donation Platform
    - Fundraising
    - Non-Profit
    url: /providers/donordrive/
  layer: domain
  name: DonorDrive
  provider: donordrive
  says: lists DonorDrive as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20
    key: donor-relationship-management
    name: Donor Relationship Management
    url: /capabilities/donor-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.1
    mcp: &id025
      status: unknown
    slug: donorperfect
    status: profiled
    tags: &id026
    - CRM
    - Company
    - Fundraising
    - Non-Profit
    url: /providers/donorperfect/
  layer: domain
  name: DonorPerfect
  provider: donorperfect
  says: lists DonorPerfect as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.30
    key: AE-230.30.30
    name: Employer Matching-Gift Data
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.3
    band: emerging
    in_catalog: true
    kin_score: 15.8
    mcp: &id027
      status: unknown
    slug: double-the-donation
    status: profiled
    tags: &id028
    - Company
    - Fundraising
    - Matching Gifts
    - Non-Profit
    url: /providers/double-the-donation/
  layer: domain
  name: Double the Donation
  provider: double-the-donation
  says: lists Double the Donation as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.30
    key: fundraising-campaign-management
    name: Fundraising Campaign Management
    url: /capabilities/fundraising-campaign-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.6
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id029
      status: unknown
    slug: evergiving
    status: profiled
    tags: &id030
    - Company
    - Fundraising
    - Integration
    - Non-Profit
    url: /providers/evergiving/
  layer: domain
  name: EverGiving
  provider: evergiving
  says: lists EverGiving as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20
    key: donor-relationship-management
    name: Donor Relationship Management
    url: /capabilities/donor-relationship-management/
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
    slug: everyaction
    status: queued for profiling
    tags: &id032 []
    url: null
  layer: domain
  name: EveryAction (Bonterra)
  provider: everyaction
  says: lists EveryAction (Bonterra) as an integration
  source: https://pro.gofundme.com/c/integrations/
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
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id033
      status: none
    slug: facebook
    status: profiled
    tags: &id034
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook / Meta Pixel / Meta CAPI
  provider: facebook
  says: lists Facebook / Meta Pixel / Meta CAPI as an integration
  source: https://pro.gofundme.com/c/integrations/
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
    agent_readiness: 29.3
    band: thin
    in_catalog: true
    kin_score: 28.2
    mcp: &id035
      status: none
    slug: feathr
    status: profiled
    tags: &id036
    - Artificial Intelligence
    - Company
    - Digital Marketing
    - Non-Profit
    url: /providers/feathr/
  layer: common
  name: Feathr
  provider: feathr
  says: lists Feathr as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30
    key: AE-140.30
    name: Consumer Payment Options
    url: /capabilities/consumer-payment-options/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.1
    mcp: &id037
      status: unknown
    slug: givingiq
    status: profiled
    tags: &id038
    - Charity
    - Company
    - Donations
    - Fintech
    url: /providers/givingiq/
  layer: domain
  name: GivingIQ (formerly DonateStock)
  provider: givingiq
  says: lists GivingIQ (formerly DonateStock) as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.30
    key: fundraising-campaign-management
    name: Fundraising Campaign Management
    url: /capabilities/fundraising-campaign-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 19.5
    mcp: &id039
      status: none
    slug: goodunited
    status: profiled
    tags: &id040
    - Company
    - Fundraising
    - Non-Profit
    - Social Media
    url: /providers/goodunited/
  layer: domain
  name: GoodUnited
  provider: goodunited
  says: lists GoodUnited as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id041
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id042
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.2
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id043
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id044
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: lists Google Tag Manager as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.30
    key: fundraising-campaign-management
    name: Fundraising Campaign Management
    url: /capabilities/fundraising-campaign-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.6
    mcp: &id045
      status: none
    slug: grassroots-unwired
    status: profiled
    tags: &id046
    - Company
    - Fundraising
    - Non-Profit
    - Political Campaigns
    url: /providers/grassroots-unwired/
  layer: domain
  name: Grassroots Unwired
  provider: grassroots-unwired
  says: lists Grassroots Unwired as an integration
  source: https://pro.gofundme.com/c/integrations/
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
    agent_readiness: 52.7
    band: exemplar
    in_catalog: true
    kin_score: 94.6
    mcp: &id047
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id048
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: common
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20
    key: donor-relationship-management
    name: Donor Relationship Management
    url: /capabilities/donor-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 13.4
    mcp: &id049
      status: none
    slug: humanitru
    status: profiled
    tags: &id050
    - CRM
    - Company
    - Fundraising
    - Non-Profit
    url: /providers/humanitru/
  layer: domain
  name: Humanitru
  provider: humanitru
  says: lists Humanitru as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.9
    band: exemplar
    in_catalog: true
    kin_score: 69.0
    mcp: &id051
      status: none
    slug: instagram
    status: profiled
    tags: &id052
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
  layer: common
  name: Instagram
  provider: instagram
  says: lists Instagram as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20
    key: donor-relationship-management
    name: Donor Relationship Management
    url: /capabilities/donor-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id053
      status: unchecked
    slug: kindful
    status: queued for profiling
    tags: &id054 []
    url: null
  layer: domain
  name: Kindful
  provider: kindful
  says: lists Kindful as an integration
  source: https://pro.gofundme.com/c/integrations/
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
    agent_band: agent-native
    agent_readiness: 54.9
    band: exemplar
    in_catalog: true
    kin_score: 77.6
    mcp: &id055
      source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
      status: verified
    slug: klaviyo
    status: profiled
    tags: &id056
    - Customer Data
    - Email
    - Marketing
    - SMS
    url: /providers/klaviyo/
  layer: common
  name: Klaviyo
  provider: klaviyo
  says: lists Klaviyo as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20
    key: donor-relationship-management
    name: Donor Relationship Management
    url: /capabilities/donor-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 20.5
    mcp: &id057
      status: unknown
    slug: little-green-light
    status: profiled
    tags: &id058
    - Donor Management
    - Fundraising
    - Nonprofit Software
    - Online Donations
    url: /providers/little-green-light/
  layer: domain
  name: Little Green Light
  provider: little-green-light
  says: lists Little Green Light as an integration
  source: https://pro.gofundme.com/c/integrations/
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
    agent_readiness: 42.3
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id059
      status: none
    slug: mailchimp
    status: profiled
    tags: &id060
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://pro.gofundme.com/c/integrations/
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
    agent_readiness: 33.1
    band: strong
    in_catalog: true
    kin_score: 63.9
    mcp: &id061
      source: https://github.com/microsoft/Dataverse-MCP
      status: verified
    slug: microsoft-dynamics-365
    status: profiled
    tags: &id062
    - Business Applications
    - CRM
    - Cloud
    - Enterprise
    url: /providers/microsoft-dynamics-365/
  layer: common
  name: Microsoft Dynamics
  provider: microsoft-dynamics-365
  says: lists Microsoft Dynamics as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20
    key: AE-150.20
    name: SMS & Messaging Apps
    url: /capabilities/sms-messaging-apps/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id063
      status: unchecked
    slug: mobile-commons
    status: queued for profiling
    tags: &id064 []
    url: null
  layer: common
  name: Mobile Commons
  provider: mobile-commons
  says: lists Mobile Commons as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20
    key: donor-relationship-management
    name: Donor Relationship Management
    url: /capabilities/donor-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.6
    band: thin
    in_catalog: true
    kin_score: 31.1
    mcp: &id065
      status: none
    slug: neonone
    status: profiled
    tags: &id066
    - CRM
    - Donor Management
    - Fundraising
    - Non-Profit
    url: /providers/neonone/
  layer: domain
  name: Neon One
  provider: neonone
  says: lists Neon One as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20
    key: donor-relationship-management
    name: Donor Relationship Management
    url: /capabilities/donor-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id067
      status: unchecked
    slug: netforum
    status: queued for profiling
    tags: &id068 []
    url: null
  layer: domain
  name: NetForum
  provider: netforum
  says: lists NetForum as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.30
    key: fundraising-campaign-management
    name: Fundraising Campaign Management
    url: /capabilities/fundraising-campaign-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.6
    mcp: &id069
      status: unknown
    slug: nuclavis
    status: profiled
    tags: &id070
    - Fundraising
    - Mobile
    - Non-Profit
    - P2P
    url: /providers/nuclavis/
  layer: domain
  name: Nuclavis
  provider: nuclavis
  says: lists Nuclavis as an integration
  source: https://pro.gofundme.com/c/integrations/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id071
      status: unchecked
    slug: omatic
    status: queued for profiling
    tags: &id072 []
    url: null
  layer: common
  name: Omatic
  provider: omatic
  says: lists Omatic as an integration
  source: https://pro.gofundme.com/c/integrations/
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
    agent_readiness: 41.2
    band: strong
    in_catalog: true
    kin_score: 61.1
    mcp: &id073
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id074
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks Online
  provider: quickbooks
  says: lists QuickBooks Online as an integration
  source: https://pro.gofundme.com/c/integrations/
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
    agent_readiness: 15.5
    band: thin
    in_catalog: true
    kin_score: 26.3
    mcp: &id075
      status: none
    slug: sage-intacct
    status: profiled
    tags: &id076
    - Accounting
    - ERP
    - Financial Management
    - General Ledger
    url: /providers/sage-intacct/
  layer: common
  name: Sage Intacct
  provider: sage-intacct
  says: lists Sage Intacct as an integration
  source: https://pro.gofundme.com/c/integrations/
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
    agent_readiness: 54.7
    band: exemplar
    in_catalog: true
    kin_score: 90.6
    mcp: &id077
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id078
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: Salesforce (NPSP, Nonprofit Cloud)
  provider: salesforce
  says: lists Salesforce (NPSP, Nonprofit Cloud) as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20
    key: donor-relationship-management
    name: Donor Relationship Management
    url: /capabilities/donor-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id079
      status: unchecked
    slug: salsa-labs
    status: queued for profiling
    tags: &id080 []
    url: null
  layer: domain
  name: Salsa Engage
  provider: salsa-labs
  says: lists Salsa Engage as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 45.8
    band: exemplar
    in_catalog: true
    kin_score: 81.1
    mcp: &id081
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id082
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
  layer: common
  name: Snowflake
  provider: snowflake
  says: lists Snowflake as an integration
  source: https://pro.gofundme.com/c/integrations/
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
    agent_band: human-only
    agent_readiness: 3.2
    band: emerging
    in_catalog: true
    kin_score: 12.0
    mcp: &id083
      status: unknown
    slug: syncsmart
    status: profiled
    tags: &id084
    - HubSpot
    - Integration
    - Marketing
    - Sales
    url: /providers/syncsmart/
  layer: common
  name: SyncSmart
  provider: syncsmart
  says: lists SyncSmart as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20
    key: AE-150.20
    name: SMS & Messaging Apps
    url: /capabilities/sms-messaging-apps/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.8
    band: thin
    in_catalog: true
    kin_score: 37.0
    mcp: &id085
      status: none
    slug: tatango
    status: profiled
    tags: &id086
    - Company
    - Fundraising
    - Non-Profit
    - SMS
    url: /providers/tatango/
  layer: common
  name: Tatango
  provider: tatango
  says: lists Tatango as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.6
    band: strong
    in_catalog: true
    kin_score: 66.3
    mcp: &id087
      source: https://docs.tealium.com/server-side/config-mcp/about-config-mcp/
      status: documented
    slug: tealium
    status: profiled
    tags: &id088
    - AudienceStream
    - CDP
    - Customer Data Platform
    - Tag Management
    url: /providers/tealium/
  layer: common
  name: Tealium
  provider: tealium
  says: lists Tealium as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20
    key: donor-relationship-management
    name: Donor Relationship Management
    url: /capabilities/donor-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.9
    mcp: &id089
      status: unknown
    slug: tessitura
    status: profiled
    tags: &id090
    - Arts
    - Company
    - Culture
    - Non-Profit
    url: /providers/tessitura/
  layer: domain
  name: Tessitura
  provider: tessitura
  says: lists Tessitura as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20
    key: donor-relationship-management
    name: Donor Relationship Management
    url: /capabilities/donor-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.3
    band: emerging
    in_catalog: true
    kin_score: 13.8
    mcp: &id091
      status: unknown
    slug: virtuous
    status: profiled
    tags: &id092
    - CRM
    - Company
    - Fundraising
    - Non-Profit
    url: /providers/virtuous/
  layer: domain
  name: Virtuous
  provider: virtuous
  says: lists Virtuous as an integration
  source: https://pro.gofundme.com/c/integrations/
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
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id093
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id094
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://pro.gofundme.com/c/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/donations-crowdfunding/gofundme-pro-classy/
providers:
- agent_band: agent-ready
  agent_readiness: 36.1
  band: strong
  in_catalog: true
  kin_score: 63.6
  mcp: *id001
  name: Amazon Redshift
  slug: amazon-redshift
  status: profiled
  tags: *id002
  url: /providers/amazon-redshift/
- agent_band: agent-ready
  agent_readiness: 32.2
  band: developing
  in_catalog: true
  kin_score: 39.3
  mcp: *id003
  name: Blackbaud CRM / Raiser's Edge NXT
  slug: blackbaud
  status: profiled
  tags: *id004
  url: /providers/blackbaud/
- agent_band: agent-aware
  agent_readiness: 22.6
  band: thin
  in_catalog: true
  kin_score: 30.6
  mcp: *id005
  name: Bloomerang
  slug: bloomerang
  status: profiled
  tags: *id006
  url: /providers/bloomerang/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.5
  mcp: *id007
  name: Bonfire
  slug: bonfire
  status: profiled
  tags: *id008
  url: /providers/bonfire/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id009
  name: BrightVine
  slug: brightvine
  status: queued for profiling
  tags: *id010
  url: null
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 7.1
  mcp: *id011
  name: Bytespree
  slug: bytespree
  status: profiled
  tags: *id012
  url: /providers/bytespree/
- agent_band: agent-aware
  agent_readiness: 15.3
  band: minimal
  in_catalog: true
  kin_score: 9.4
  mcp: *id013
  name: Charity Miles
  slug: charity-miles
  status: profiled
  tags: *id014
  url: /providers/charity-miles/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: emerging
  in_catalog: true
  kin_score: 18.1
  mcp: *id015
  name: CiviCRM
  slug: civicrm
  status: profiled
  tags: *id016
  url: /providers/civicrm/
- agent_band: agent-ready
  agent_readiness: 32.1
  band: exemplar
  in_catalog: true
  kin_score: 70.9
  mcp: *id017
  name: Constant Contact
  slug: constant-contact
  status: profiled
  tags: *id018
  url: /providers/constant-contact/
- agent_band: agent-aware
  agent_readiness: 18.0
  band: emerging
  in_catalog: true
  kin_score: 13.5
  mcp: *id019
  name: Daxko
  slug: daxko
  status: profiled
  tags: *id020
  url: /providers/daxko/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.5
  mcp: *id021
  name: DonorDock
  slug: donordock
  status: profiled
  tags: *id022
  url: /providers/donordock/
- agent_band: human-only
  agent_readiness: 3.2
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id023
  name: DonorDrive
  slug: donordrive
  status: profiled
  tags: *id024
  url: /providers/donordrive/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.1
  mcp: *id025
  name: DonorPerfect
  slug: donorperfect
  status: profiled
  tags: *id026
  url: /providers/donorperfect/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: emerging
  in_catalog: true
  kin_score: 15.8
  mcp: *id027
  name: Double the Donation
  slug: double-the-donation
  status: profiled
  tags: *id028
  url: /providers/double-the-donation/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id029
  name: EverGiving
  slug: evergiving
  status: profiled
  tags: *id030
  url: /providers/evergiving/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id031
  name: EveryAction (Bonterra)
  slug: everyaction
  status: queued for profiling
  tags: *id032
  url: null
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id033
  name: Facebook / Meta Pixel / Meta CAPI
  slug: facebook
  status: profiled
  tags: *id034
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 29.3
  band: thin
  in_catalog: true
  kin_score: 28.2
  mcp: *id035
  name: Feathr
  slug: feathr
  status: profiled
  tags: *id036
  url: /providers/feathr/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.1
  mcp: *id037
  name: GivingIQ (formerly DonateStock)
  slug: givingiq
  status: profiled
  tags: *id038
  url: /providers/givingiq/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 19.5
  mcp: *id039
  name: GoodUnited
  slug: goodunited
  status: profiled
  tags: *id040
  url: /providers/goodunited/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id041
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id042
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 38.2
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id043
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id044
  url: /providers/google-tag-manager/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.6
  mcp: *id045
  name: Grassroots Unwired
  slug: grassroots-unwired
  status: profiled
  tags: *id046
  url: /providers/grassroots-unwired/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id047
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id048
  url: /providers/hubspot/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.4
  mcp: *id049
  name: Humanitru
  slug: humanitru
  status: profiled
  tags: *id050
  url: /providers/humanitru/
- agent_band: agent-ready
  agent_readiness: 38.9
  band: exemplar
  in_catalog: true
  kin_score: 69.0
  mcp: *id051
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id052
  url: /providers/instagram/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id053
  name: Kindful
  slug: kindful
  status: queued for profiling
  tags: *id054
  url: null
- agent_band: agent-native
  agent_readiness: 54.9
  band: exemplar
  in_catalog: true
  kin_score: 77.6
  mcp: *id055
  name: Klaviyo
  slug: klaviyo
  status: profiled
  tags: *id056
  url: /providers/klaviyo/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.5
  mcp: *id057
  name: Little Green Light
  slug: little-green-light
  status: profiled
  tags: *id058
  url: /providers/little-green-light/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id059
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id060
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: strong
  in_catalog: true
  kin_score: 63.9
  mcp: *id061
  name: Microsoft Dynamics
  slug: microsoft-dynamics-365
  status: profiled
  tags: *id062
  url: /providers/microsoft-dynamics-365/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id063
  name: Mobile Commons
  slug: mobile-commons
  status: queued for profiling
  tags: *id064
  url: null
- agent_band: agent-aware
  agent_readiness: 20.6
  band: thin
  in_catalog: true
  kin_score: 31.1
  mcp: *id065
  name: Neon One
  slug: neonone
  status: profiled
  tags: *id066
  url: /providers/neonone/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id067
  name: NetForum
  slug: netforum
  status: queued for profiling
  tags: *id068
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.6
  mcp: *id069
  name: Nuclavis
  slug: nuclavis
  status: profiled
  tags: *id070
  url: /providers/nuclavis/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id071
  name: Omatic
  slug: omatic
  status: queued for profiling
  tags: *id072
  url: null
- agent_band: agent-native
  agent_readiness: 41.2
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id073
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id074
  url: /providers/quickbooks/
- agent_band: agent-aware
  agent_readiness: 15.5
  band: thin
  in_catalog: true
  kin_score: 26.3
  mcp: *id075
  name: Sage Intacct
  slug: sage-intacct
  status: profiled
  tags: *id076
  url: /providers/sage-intacct/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id077
  name: Salesforce (NPSP, Nonprofit Cloud)
  slug: salesforce
  status: profiled
  tags: *id078
  url: /providers/salesforce/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id079
  name: Salsa Engage
  slug: salsa-labs
  status: queued for profiling
  tags: *id080
  url: null
- agent_band: agent-native
  agent_readiness: 45.8
  band: exemplar
  in_catalog: true
  kin_score: 81.1
  mcp: *id081
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id082
  url: /providers/snowflake/
- agent_band: human-only
  agent_readiness: 3.2
  band: emerging
  in_catalog: true
  kin_score: 12.0
  mcp: *id083
  name: SyncSmart
  slug: syncsmart
  status: profiled
  tags: *id084
  url: /providers/syncsmart/
- agent_band: agent-aware
  agent_readiness: 19.8
  band: thin
  in_catalog: true
  kin_score: 37.0
  mcp: *id085
  name: Tatango
  slug: tatango
  status: profiled
  tags: *id086
  url: /providers/tatango/
- agent_band: agent-ready
  agent_readiness: 35.6
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id087
  name: Tealium
  slug: tealium
  status: profiled
  tags: *id088
  url: /providers/tealium/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.9
  mcp: *id089
  name: Tessitura
  slug: tessitura
  status: profiled
  tags: *id090
  url: /providers/tessitura/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: emerging
  in_catalog: true
  kin_score: 13.8
  mcp: *id091
  name: Virtuous
  slug: virtuous
  status: profiled
  tags: *id092
  url: /providers/virtuous/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id093
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id094
  url: /providers/zapier/
siblings:
- name: Givebutter
  rows: 50
  url: /applications/donations-crowdfunding/givebutter/
- name: GiveWP
  rows: 3
  url: /applications/donations-crowdfunding/givewp/
- name: HCB (Hack Club Bank)
  rows: 13
  url: /applications/donations-crowdfunding/hcb-hack-club-bank/
- name: Liberapay
  rows: 4
  url: /applications/donations-crowdfunding/liberapay/
- name: Open Collective
  rows: 10
  url: /applications/donations-crowdfunding/open-collective/
- name: Patreon
  rows: 23
  url: /applications/donations-crowdfunding/patreon/
sitemap: true
title: 'GoFundMe Pro (Classy): Donations & Crowdfunding reference app'
---
