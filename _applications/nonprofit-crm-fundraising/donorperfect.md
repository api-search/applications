---
app: DonorPerfect
app_slug: donorperfect
app_url: https://www.donorperfect.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.10.30
  key: AE-120.10.30
  layer: domain
  name: Address Validation & Autocomplete
  providers:
  - USgeocoder
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-150.90
  key: AE-150.90
  layer: domain
  name: Advocacy & Legislator Outreach
  providers:
  - Congress Plus
  url: /capabilities/advocacy-legislator-outreach/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-912
  key: AE-912
  layer: domain
  name: Direct Mail APIs
  providers:
  - PostcardMania
  - Scribe Handwritten
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-230.30.30
  key: AE-230.30.30
  layer: domain
  name: Employer Matching-Gift Data
  providers:
  - Double the Donation
  url: /capabilities/company-contact-data/
  via_parent: Company & Contact Data
- attribution: API Evangelist extension
  id: AE-210.50
  key: AE-210.50
  layer: domain
  name: Event Ticketing
  providers:
  - Agile Ticketing
  - SimpleTix
  url: /capabilities/event-ticketing/
  via_parent: null
- attribution: Turbo EA
  id: BC-4800.30
  key: fundraising-campaign-management
  layer: domain
  name: Fundraising Campaign Management
  providers:
  - Givecloud
  - raisin
  - ReadySetAuction
  - ShopRaise
  - Winspire
  url: /capabilities/fundraising-campaign-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4800.40.10
  key: BC-4800.40.10
  layer: domain
  name: Gift Receipt & Processing
  providers:
  - DAFpay
  - DonateStock
  url: /capabilities/gift-pledge-administration/
  via_parent: Gift & Pledge Administration
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - PayPal
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4800.20.10
  key: BC-4800.20.10
  layer: domain
  name: Prospect Research & Identification
  providers:
  - DonorSearch
  - Kindsight
  url: /capabilities/donor-relationship-management/
  via_parent: Donor Relationship Management
- attribution: API Evangelist extension
  id: AE-924
  key: AE-924
  layer: domain
  name: Volunteer Management
  providers:
  - POINT
  - SignUp.com
  - Volunteer Matrix
  url: /capabilities/volunteer-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Ravela Insights
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Constant Contact
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - Intuit QuickBooks
  - Sage Intacct Fundraising
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
  id: AE-170.10.10
  key: AE-170.10.10
  layer: common
  name: Video Hosting & Encoding
  providers:
  - CauseVid
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
category:
  id: nonprofit-crm-fundraising
  name: Nonprofit CRM & Fundraising
  url: /applications/nonprofit-crm-fundraising/
counts:
  declared: 27
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.donorperfect.com/integrations/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-210.50
    key: AE-210.50
    name: Event Ticketing
    url: /capabilities/event-ticketing/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.3
    mcp: &id001
      status: unknown
    slug: agile-ticketing
    status: profiled
    tags: &id002
    - Company
    - Event
    - Hospitality
    - Ticketing
    url: /providers/agile-ticketing/
  layer: domain
  name: Agile Ticketing
  provider: agile-ticketing
  says: lists Agile Ticketing as an integration
  source: https://www.donorperfect.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.6
    mcp: &id003
      status: unknown
    slug: causevid
    status: profiled
    tags: &id004
    - Fundraising
    - Marketing
    - Non-Profit
    - Video
    url: /providers/causevid/
  layer: common
  name: CauseVid
  provider: causevid
  says: lists CauseVid as an integration
  source: https://www.donorperfect.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.90
    key: AE-150.90
    name: Advocacy & Legislator Outreach
    url: /capabilities/advocacy-legislator-outreach/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.3
    mcp: &id005
      status: unknown
    slug: congress-plus
    status: profiled
    tags: &id006
    - Data
    - Government
    - Mobile
    - Platform
    url: /providers/congress-plus/
  layer: domain
  name: Congress Plus
  provider: congress-plus
  says: lists Congress Plus as an integration
  source: https://www.donorperfect.com/integrations/
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
    agent_readiness: 32.1
    band: exemplar
    in_catalog: true
    kin_score: 70.9
    mcp: &id007
      status: none
    slug: constant-contact
    status: profiled
    tags: &id008
    - Campaigns
    - Contacts
    - Email Marketing
    - Event
    url: /providers/constant-contact/
  layer: common
  name: Constant Contact
  provider: constant-contact
  says: lists Constant Contact as an integration
  source: https://www.donorperfect.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.40.10
    key: BC-4800.40.10
    name: Gift Receipt & Processing
    url: /capabilities/gift-pledge-administration/
    via_parent: Gift & Pledge Administration
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.7
    band: strong
    in_catalog: true
    kin_score: 58.5
    mcp: &id009
      status: none
    slug: chariot
    status: profiled
    tags: &id010
    - Charitable Giving
    - Donor-Advised Funds
    - Non-Profit
    - Payments
    url: /providers/chariot/
  layer: domain
  name: DAFpay
  provider: chariot
  says: lists DAFpay as an integration
  source: https://www.donorperfect.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.40.10
    key: BC-4800.40.10
    name: Gift Receipt & Processing
    url: /capabilities/gift-pledge-administration/
    via_parent: Gift & Pledge Administration
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.2
    band: emerging
    in_catalog: true
    kin_score: 13.0
    mcp: &id011
      status: unknown
    slug: donatestock
    status: profiled
    tags: &id012
    - Charity
    - Company
    - Finance
    - Stocks
    url: /providers/donatestock/
  layer: domain
  name: DonateStock
  provider: donatestock
  says: lists DonateStock as an integration
  source: https://www.donorperfect.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20.10
    key: BC-4800.20.10
    name: Prospect Research & Identification
    url: /capabilities/donor-relationship-management/
    via_parent: Donor Relationship Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.1
    mcp: &id013
      status: none
    slug: donorsearch
    status: profiled
    tags: &id014
    - Company
    - Donor Research
    - Fundraising
    - Non-Profit
    url: /providers/donorsearch/
  layer: domain
  name: DonorSearch
  provider: donorsearch
  says: lists DonorSearch as an integration
  source: https://www.donorperfect.com/integrations/
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
    mcp: &id015
      status: unknown
    slug: double-the-donation
    status: profiled
    tags: &id016
    - Company
    - Fundraising
    - Matching Gifts
    - Non-Profit
    url: /providers/double-the-donation/
  layer: domain
  name: Double the Donation
  provider: double-the-donation
  says: lists Double the Donation as an integration
  source: https://www.donorperfect.com/integrations/
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
    agent_readiness: 8.6
    band: thin
    in_catalog: true
    kin_score: 28.3
    mcp: &id017
      status: none
    slug: givecloud
    status: profiled
    tags: &id018
    - Company
    - Fundraising
    - Non-Profit
    - Software-as-a-Service
    url: /providers/givecloud/
  layer: domain
  name: Givecloud
  provider: givecloud
  says: lists Givecloud as an integration
  source: https://www.donorperfect.com/integrations/
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
    mcp: &id019
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id020
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://www.donorperfect.com/integrations/
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
    mcp: &id021
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id022
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: Intuit QuickBooks
  provider: quickbooks
  says: lists Intuit QuickBooks as an integration
  source: https://www.donorperfect.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.20.10
    key: BC-4800.20.10
    name: Prospect Research & Identification
    url: /capabilities/donor-relationship-management/
    via_parent: Donor Relationship Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 17.2
    mcp: &id023
      status: unknown
    slug: kindsight
    status: profiled
    tags: &id024
    - Artificial Intelligence
    - Data
    - Fundraising
    - Non-Profit
    url: /providers/kindsight/
  layer: domain
  name: Kindsight
  provider: kindsight
  says: lists Kindsight as an integration
  source: https://www.donorperfect.com/integrations/
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
    agent_readiness: 42.3
    band: exemplar
    in_catalog: true
    kin_score: 78.3
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
  source: https://www.donorperfect.com/integrations/
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
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id027
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id028
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: domain
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://www.donorperfect.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-924
    key: AE-924
    name: Volunteer Management
    url: /capabilities/volunteer-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.3
    mcp: &id029
      status: unknown
    slug: point-app
    status: profiled
    tags: &id030
    - Company
    url: /providers/point-app/
  layer: domain
  name: POINT
  provider: point-app
  says: lists POINT as an integration
  source: https://www.donorperfect.com/integrations/
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
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 17.7
    mcp: &id031
      status: none
    slug: postcardmania
    status: profiled
    tags: &id032
    - Automation
    - Direct Mail
    - Marketing
    - Small Business
    url: /providers/postcardmania/
  layer: domain
  name: PostcardMania
  provider: postcardmania
  says: lists PostcardMania as an integration
  source: https://www.donorperfect.com/integrations/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id033
      status: unchecked
    slug: raisin-donations
    status: queued for profiling
    tags: &id034 []
    url: null
  layer: domain
  name: raisin
  provider: raisin-donations
  says: lists raisin as an integration
  source: https://www.donorperfect.com/integrations/
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
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.1
    mcp: &id035
      status: unknown
    slug: ravela
    status: profiled
    tags: &id036
    - Branding
    - Company
    - Domain
    - Parking
    url: /providers/ravela/
  layer: common
  name: Ravela Insights
  provider: ravela
  says: lists Ravela Insights as an integration
  source: https://www.donorperfect.com/integrations/
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
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 20.0
    mcp: &id037
      status: unknown
    slug: readysetauction
    status: profiled
    tags: &id038
    - Auction Software
    - Event Management
    - Mobile Bidding
    - Online Auction
    url: /providers/readysetauction/
  layer: domain
  name: ReadySetAuction
  provider: readysetauction
  says: lists ReadySetAuction as an integration
  source: https://www.donorperfect.com/integrations/
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
    mcp: &id039
      status: none
    slug: sage-intacct
    status: profiled
    tags: &id040
    - Accounting
    - ERP
    - Financial Management
    - General Ledger
    url: /providers/sage-intacct/
  layer: common
  name: Sage Intacct Fundraising
  provider: sage-intacct
  says: lists Sage Intacct Fundraising as an integration
  source: https://www.donorperfect.com/integrations/
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
    agent_band: agent-ready
    agent_readiness: 34.3
    band: thin
    in_catalog: true
    kin_score: 28.2
    mcp: &id041
      status: unknown
    slug: scribe-handwritten
    status: profiled
    tags: &id042
    - Collaboration
    - Company
    - Digital
    - Handwriting
    url: /providers/scribe-handwritten/
  layer: domain
  name: Scribe Handwritten
  provider: scribe-handwritten
  says: lists Scribe Handwritten as an integration
  source: https://www.donorperfect.com/integrations/
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
    band: emerging
    in_catalog: true
    kin_score: 11.7
    mcp: &id043
      status: unknown
    slug: shopraise
    status: profiled
    tags: &id044
    - Company
    - E-Commerce
    - Fundraising
    - Non-Profit
    url: /providers/shopraise/
  layer: domain
  name: ShopRaise
  provider: shopraise
  says: lists ShopRaise as an integration
  source: https://www.donorperfect.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-924
    key: AE-924
    name: Volunteer Management
    url: /capabilities/volunteer-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 10.8
    band: emerging
    in_catalog: true
    kin_score: 16.6
    mcp: &id045
      status: unknown
    slug: signup-com
    status: profiled
    tags: &id046
    - Education
    - Scheduling
    - Software-as-a-Service
    - Volunteer
    url: /providers/signup-com/
  layer: domain
  name: SignUp.com
  provider: signup-com
  says: lists SignUp.com as an integration
  source: https://www.donorperfect.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.50
    key: AE-210.50
    name: Event Ticketing
    url: /capabilities/event-ticketing/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 17.3
    mcp: &id047
      status: unknown
    slug: simpletix
    status: profiled
    tags: &id048
    - Company
    - Event
    - Software-as-a-Service
    - Ticketing
    url: /providers/simpletix/
  layer: domain
  name: SimpleTix
  provider: simpletix
  says: lists SimpleTix as an integration
  source: https://www.donorperfect.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.30
    key: AE-120.10.30
    name: Address Validation & Autocomplete
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.6
    mcp: &id049
      status: unknown
    slug: usgeocoder
    status: profiled
    tags: &id050
    - Company
    - District
    - Location
    - Tax
    url: /providers/usgeocoder/
  layer: domain
  name: USgeocoder
  provider: usgeocoder
  says: lists USgeocoder as an integration
  source: https://www.donorperfect.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-924
    key: AE-924
    name: Volunteer Management
    url: /capabilities/volunteer-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.0
    mcp: &id051
      status: unknown
    slug: volunteer-matrix
    status: profiled
    tags: &id052
    - Community
    - Non-Profit
    - Software-as-a-Service
    - Volunteer Management
    url: /providers/volunteer-matrix/
  layer: domain
  name: Volunteer Matrix
  provider: volunteer-matrix
  says: lists Volunteer Matrix as an integration
  source: https://www.donorperfect.com/integrations/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id053
      status: unchecked
    slug: winspire
    status: queued for profiling
    tags: &id054 []
    url: null
  layer: domain
  name: Winspire
  provider: winspire
  says: lists Winspire as an integration
  source: https://www.donorperfect.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/nonprofit-crm-fundraising/donorperfect/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.3
  mcp: *id001
  name: Agile Ticketing
  slug: agile-ticketing
  status: profiled
  tags: *id002
  url: /providers/agile-ticketing/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id003
  name: CauseVid
  slug: causevid
  status: profiled
  tags: *id004
  url: /providers/causevid/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id005
  name: Congress Plus
  slug: congress-plus
  status: profiled
  tags: *id006
  url: /providers/congress-plus/
- agent_band: agent-ready
  agent_readiness: 32.1
  band: exemplar
  in_catalog: true
  kin_score: 70.9
  mcp: *id007
  name: Constant Contact
  slug: constant-contact
  status: profiled
  tags: *id008
  url: /providers/constant-contact/
- agent_band: agent-ready
  agent_readiness: 53.7
  band: strong
  in_catalog: true
  kin_score: 58.5
  mcp: *id009
  name: DAFpay
  slug: chariot
  status: profiled
  tags: *id010
  url: /providers/chariot/
- agent_band: human-only
  agent_readiness: 3.2
  band: emerging
  in_catalog: true
  kin_score: 13.0
  mcp: *id011
  name: DonateStock
  slug: donatestock
  status: profiled
  tags: *id012
  url: /providers/donatestock/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.1
  mcp: *id013
  name: DonorSearch
  slug: donorsearch
  status: profiled
  tags: *id014
  url: /providers/donorsearch/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: emerging
  in_catalog: true
  kin_score: 15.8
  mcp: *id015
  name: Double the Donation
  slug: double-the-donation
  status: profiled
  tags: *id016
  url: /providers/double-the-donation/
- agent_band: agent-aware
  agent_readiness: 8.6
  band: thin
  in_catalog: true
  kin_score: 28.3
  mcp: *id017
  name: Givecloud
  slug: givecloud
  status: profiled
  tags: *id018
  url: /providers/givecloud/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id019
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id020
  url: /providers/google-analytics/
- agent_band: agent-native
  agent_readiness: 41.2
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id021
  name: Intuit QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id022
  url: /providers/quickbooks/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 17.2
  mcp: *id023
  name: Kindsight
  slug: kindsight
  status: profiled
  tags: *id024
  url: /providers/kindsight/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id025
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id026
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id027
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id028
  url: /providers/paypal/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.3
  mcp: *id029
  name: POINT
  slug: point-app
  status: profiled
  tags: *id030
  url: /providers/point-app/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 17.7
  mcp: *id031
  name: PostcardMania
  slug: postcardmania
  status: profiled
  tags: *id032
  url: /providers/postcardmania/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id033
  name: raisin
  slug: raisin-donations
  status: queued for profiling
  tags: *id034
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.1
  mcp: *id035
  name: Ravela Insights
  slug: ravela
  status: profiled
  tags: *id036
  url: /providers/ravela/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 20.0
  mcp: *id037
  name: ReadySetAuction
  slug: readysetauction
  status: profiled
  tags: *id038
  url: /providers/readysetauction/
- agent_band: agent-aware
  agent_readiness: 15.5
  band: thin
  in_catalog: true
  kin_score: 26.3
  mcp: *id039
  name: Sage Intacct Fundraising
  slug: sage-intacct
  status: profiled
  tags: *id040
  url: /providers/sage-intacct/
- agent_band: agent-ready
  agent_readiness: 34.3
  band: thin
  in_catalog: true
  kin_score: 28.2
  mcp: *id041
  name: Scribe Handwritten
  slug: scribe-handwritten
  status: profiled
  tags: *id042
  url: /providers/scribe-handwritten/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.7
  mcp: *id043
  name: ShopRaise
  slug: shopraise
  status: profiled
  tags: *id044
  url: /providers/shopraise/
- agent_band: agent-aware
  agent_readiness: 10.8
  band: emerging
  in_catalog: true
  kin_score: 16.6
  mcp: *id045
  name: SignUp.com
  slug: signup-com
  status: profiled
  tags: *id046
  url: /providers/signup-com/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 17.3
  mcp: *id047
  name: SimpleTix
  slug: simpletix
  status: profiled
  tags: *id048
  url: /providers/simpletix/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.6
  mcp: *id049
  name: USgeocoder
  slug: usgeocoder
  status: profiled
  tags: *id050
  url: /providers/usgeocoder/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.0
  mcp: *id051
  name: Volunteer Matrix
  slug: volunteer-matrix
  status: profiled
  tags: *id052
  url: /providers/volunteer-matrix/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id053
  name: Winspire
  slug: winspire
  status: queued for profiling
  tags: *id054
  url: null
siblings:
- name: Bloomerang
  rows: 29
  url: /applications/nonprofit-crm-fundraising/bloomerang/
- name: CiviCRM
  rows: 10
  url: /applications/nonprofit-crm-fundraising/civicrm/
- name: Givebutter
  rows: 53
  url: /applications/nonprofit-crm-fundraising/givebutter/
- name: Little Green Light
  rows: 28
  url: /applications/nonprofit-crm-fundraising/little-green-light/
- name: Neon CRM
  rows: 18
  url: /applications/nonprofit-crm-fundraising/neon-crm/
sitemap: true
title: 'DonorPerfect: Nonprofit CRM & Fundraising reference app'
---
