---
app: Square Appointments
app_slug: square-appointments
app_url: https://squareup.com/us/en/appointments
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-210.80
  key: AE-210.80
  layer: domain
  name: Booking Channel Distribution
  providers:
  - Facebook
  - Google (Reserve with Google)
  - Instagram
  url: /capabilities/booking-channel-distribution/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - vCita
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.50
  key: gift-cards-gifting-cashback
  layer: domain
  name: Gift Cards, Gifting & Cashback
  providers:
  - Giftya
  url: /capabilities/gift-cards-gifting-cashback/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - BigCommerce
  - Ecwid
  - GoDaddy
  - Magento
  - Wix
  - WooCommerce
  - WordPress.com
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-220.20
  key: indirect-tax-management
  layer: domain
  name: Indirect Tax Management
  providers:
  - Davo
  url: /capabilities/indirect-tax-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.80
  key: marketplaces
  layer: domain
  name: Marketplaces
  providers:
  - ClassPass
  - Groupon
  url: /capabilities/marketplaces/
  via_parent: null
- attribution: Turbo EA
  id: BC-2440.20
  key: rostering-and-scheduling-management
  layer: domain
  name: Rostering and Scheduling Management
  providers:
  - Homebase
  - Humanity
  - When I Work
  url: /capabilities/rostering-and-scheduling-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300.10
  key: talent-acquisition-management
  layer: domain
  name: Talent Acquisition Management
  providers:
  - ZipRecruiter
  url: /capabilities/talent-acquisition-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - ActiveCampaign
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - Bench
  - CommerceSync
  - Hurdlr
  - QuickBooks
  - SHOGO
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: common
  name: Online Forms & Survey Collection
  providers:
  - 123FormBuilder
  - Cognito Forms
  - Gravity Forms
  - JotForm
  - Wufoo
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
category:
  id: salon-spa-management
  name: Salon & Spa Management
  url: /applications/salon-spa-management/
counts:
  declared: 32
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://squareup.com/us/en/appointments/integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.3
    band: strong
    in_catalog: true
    kin_score: 55.9
    mcp: &id001
      status: unknown
    slug: 123formbuilder
    status: profiled
    tags: &id002
    - Form Builder
    - Online Forms
    - Surveys
    - Workflows
    url: /providers/123formbuilder/
  layer: common
  name: 123FormBuilder
  provider: 123formbuilder
  says: lists 123FormBuilder as an integration
  source: https://squareup.com/us/en/appointments/integrations
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
    agent_readiness: 51.0
    band: exemplar
    in_catalog: true
    kin_score: 81.1
    mcp: &id003
      source: https://developers.activecampaign.com/page/mcp
      status: documented
    slug: activecampaign
    status: profiled
    tags: &id004
    - CRM
    - Email Marketing
    - Marketing Automation
    - Sales Automation
    url: /providers/activecampaign/
  layer: common
  name: ActiveCampaign
  provider: activecampaign
  says: lists ActiveCampaign as an integration
  source: https://squareup.com/us/en/appointments/integrations
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
    band: thin
    in_catalog: true
    kin_score: 30.4
    mcp: &id005
      status: unknown
    slug: bench
    status: profiled
    tags: &id006
    - Accounting
    - Bookkeeping
    - Small Business
    - Software-as-a-Service
    url: /providers/bench/
  layer: common
  name: Bench
  provider: bench
  says: lists Bench as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 84.3
    mcp: &id007
      source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
      status: verified
    slug: bigcommerce
    status: profiled
    tags: &id008
    - Catalog
    - E-Commerce
    - Order
    - Retail
    url: /providers/bigcommerce/
  layer: domain
  name: BigCommerce
  provider: bigcommerce
  says: lists BigCommerce as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.80
    key: marketplaces
    name: Marketplaces
    url: /capabilities/marketplaces/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.0
    mcp: &id009
      status: none
    slug: classpass
    status: profiled
    tags: &id010
    - Class Booking
    - Fitness
    - Marketplace
    - Wellness
    url: /providers/classpass/
  layer: domain
  name: ClassPass
  provider: classpass
  says: lists ClassPass as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.6
    band: thin
    in_catalog: true
    kin_score: 34.9
    mcp: &id011
      source: https://mcp.cognitoforms.com/mcp
      status: verified
    slug: cognito-forms
    status: profiled
    tags: &id012
    - Form Builder
    - Form Entries
    - Forms
    - Workflow Automation
    url: /providers/cognito-forms/
  layer: common
  name: Cognito Forms
  provider: cognito-forms
  says: lists Cognito Forms as an integration
  source: https://squareup.com/us/en/appointments/integrations
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
    band: minimal
    in_catalog: true
    kin_score: 8.1
    mcp: &id013
      status: unchecked
    slug: commercesync
    status: profiled
    tags: &id014
    - Accounting
    - Automation
    - Bookkeeping
    - Integration
    url: /providers/commercesync/
  layer: common
  name: CommerceSync
  provider: commercesync
  says: lists CommerceSync as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id015
      status: unchecked
    slug: davo
    status: queued for profiling
    tags: &id016 []
    url: null
  layer: domain
  name: Davo
  provider: davo
  says: lists Davo as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.7
    band: developing
    in_catalog: true
    kin_score: 42.2
    mcp: &id017
      status: none
    slug: ecwid
    status: profiled
    tags: &id018
    - E-Commerce
    - Online Store
    - Retail
    - Storefront
    url: /providers/ecwid/
  layer: domain
  name: Ecwid
  provider: ecwid
  says: lists Ecwid as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.80
    key: AE-210.80
    name: Booking Channel Distribution
    url: /capabilities/booking-channel-distribution/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id019
      status: none
    slug: facebook
    status: profiled
    tags: &id020
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: lists Facebook as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.50
    key: gift-cards-gifting-cashback
    name: Gift Cards, Gifting & Cashback
    url: /capabilities/gift-cards-gifting-cashback/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 2.3
    mcp: &id021
      status: unchecked
    slug: giftya
    status: profiled
    tags: &id022
    - Company
    url: /providers/giftya/
  layer: domain
  name: Giftya
  provider: giftya
  says: lists Giftya as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.4
    band: thin
    in_catalog: true
    kin_score: 30.4
    mcp: &id023
      source: https://developer.godaddy.com/mcp
      status: verified
    slug: godaddy
    status: profiled
    tags: &id024
    - Aftermarket
    - Certificates
    - DNS
    - Domains
    url: /providers/godaddy/
  layer: domain
  name: GoDaddy
  provider: godaddy
  says: lists GoDaddy as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.80
    key: AE-210.80
    name: Booking Channel Distribution
    url: /capabilities/booking-channel-distribution/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id025
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id026
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: Google (Reserve with Google)
  provider: google
  says: lists Google (Reserve with Google) as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 34.1
    mcp: &id027
      status: none
    slug: gravity-forms
    status: profiled
    tags: &id028
    - Form Builder
    - Forms
    - Surveys
    - WordPress
    url: /providers/gravity-forms/
  layer: common
  name: Gravity Forms
  provider: gravity-forms
  says: lists Gravity Forms as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.80
    key: marketplaces
    name: Marketplaces
    url: /capabilities/marketplaces/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 9.4
    band: thin
    in_catalog: true
    kin_score: 28.1
    mcp: &id029
      status: none
    slug: groupon
    status: profiled
    tags: &id030
    - E-Commerce
    - Fortune 1000
    - Local Commerce
    - Marketplace
    url: /providers/groupon/
  layer: domain
  name: Groupon
  provider: groupon
  says: lists Groupon as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2440.20
    key: rostering-and-scheduling-management
    name: Rostering and Scheduling Management
    url: /capabilities/rostering-and-scheduling-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.1
    band: emerging
    in_catalog: true
    kin_score: 25.6
    mcp: &id031
      status: none
    slug: homebase
    status: profiled
    tags: &id032
    - Human Resources
    - Payroll
    - Scheduling
    - Time Tracking
    url: /providers/homebase/
  layer: domain
  name: Homebase
  provider: homebase
  says: lists Homebase as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2440.20
    key: rostering-and-scheduling-management
    name: Rostering and Scheduling Management
    url: /capabilities/rostering-and-scheduling-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id033
      status: unknown
    slug: humanity
    status: profiled
    tags: &id034
    - Company
    - Employee Scheduling
    - Shift Planning
    - Workforce Management
    url: /providers/humanity/
  layer: domain
  name: Humanity
  provider: humanity
  says: lists Humanity as an integration
  source: https://squareup.com/us/en/appointments/integrations
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
    agent_readiness: 25.2
    band: emerging
    in_catalog: true
    kin_score: 21.8
    mcp: &id035
      status: unchecked
    slug: hurdlr
    status: profiled
    tags: &id036
    - Company
    - Expense Tracking
    - Finance
    - Mileage Tracking
    url: /providers/hurdlr/
  layer: common
  name: Hurdlr
  provider: hurdlr
  says: lists Hurdlr as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.80
    key: AE-210.80
    name: Booking Channel Distribution
    url: /capabilities/booking-channel-distribution/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.6
    band: exemplar
    in_catalog: true
    kin_score: 67.8
    mcp: &id037
      status: none
    slug: instagram
    status: profiled
    tags: &id038
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
  layer: domain
  name: Instagram
  provider: instagram
  says: lists Instagram as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 70.2
    mcp: &id039
      source: https://github.com/jotform/mcp-server
      status: verified
    slug: jotform
    status: profiled
    tags: &id040
    - Data Collection
    - Forms
    - No-Code
    - Surveys
    url: /providers/jotform/
  layer: common
  name: JotForm
  provider: jotform
  says: lists JotForm as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.9
    band: thin
    in_catalog: true
    kin_score: 30.3
    mcp: &id041
      status: none
    slug: magento
    status: profiled
    tags: &id042
    - Catalog
    - E-Commerce
    - Headless Commerce
    - Magento
    url: /providers/magento/
  layer: domain
  name: Magento
  provider: magento
  says: lists Magento as an integration
  source: https://squareup.com/us/en/appointments/integrations
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
    mcp: &id043
      status: none
    slug: mailchimp
    status: profiled
    tags: &id044
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://squareup.com/us/en/appointments/integrations
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
    mcp: &id045
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id046
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://squareup.com/us/en/appointments/integrations
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
    kin_score: 19.8
    mcp: &id047
      status: unchecked
    slug: shogo
    status: profiled
    tags: &id048
    - Accounting
    - Automation
    - Company
    - POS Integration
    url: /providers/shogo/
  layer: common
  name: SHOGO
  provider: shogo
  says: lists SHOGO as an integration
  source: https://squareup.com/us/en/appointments/integrations
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
    agent_readiness: 34.9
    band: strong
    in_catalog: true
    kin_score: 54.4
    mcp: &id049
      status: unchecked
    slug: vcita
    status: profiled
    tags: &id050
    - CRM
    - Company
    - Scheduling
    - Small Business
    url: /providers/vcita/
  layer: domain
  name: vCita
  provider: vcita
  says: lists vCita as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2440.20
    key: rostering-and-scheduling-management
    name: Rostering and Scheduling Management
    url: /capabilities/rostering-and-scheduling-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.5
    band: thin
    in_catalog: true
    kin_score: 37.6
    mcp: &id051
      status: none
    slug: when-i-work
    status: profiled
    tags: &id052
    - Employee Scheduling
    - Time Clock
    - Time Tracking
    - Workforce Management
    url: /providers/when-i-work/
  layer: domain
  name: When I Work
  provider: when-i-work
  says: lists When I Work as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.2
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id053
      source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
      status: verified
    slug: wix
    status: profiled
    tags: &id054
    - CMS
    - E-Commerce
    - Headless
    - Website Builder
    url: /providers/wix/
  layer: domain
  name: Wix
  provider: wix
  says: lists Wix as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 54.6
    mcp: &id055
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id056
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id057
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id058
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
  layer: domain
  name: WordPress.com
  provider: wordpress
  says: lists WordPress.com as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.9
    band: strong
    in_catalog: true
    kin_score: 55.3
    mcp: &id059
      status: none
    slug: wufoo
    status: profiled
    tags: &id060
    - Data Collection
    - Form Builder
    - Forms
    - Surveys
    url: /providers/wufoo/
  layer: common
  name: Wufoo
  provider: wufoo
  says: lists Wufoo as an integration
  source: https://squareup.com/us/en/appointments/integrations
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
  layer: common
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.10
    key: talent-acquisition-management
    name: Talent Acquisition Management
    url: /capabilities/talent-acquisition-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.7
    band: minimal
    in_catalog: true
    kin_score: 8.9
    mcp: &id063
      status: unknown
    slug: ziprecruiter
    status: profiled
    tags: &id064
    - Job
    - Job Board
    - Public APIs
    - Recruiting
    url: /providers/ziprecruiter/
  layer: domain
  name: ZipRecruiter
  provider: ziprecruiter
  says: lists ZipRecruiter as an integration
  source: https://squareup.com/us/en/appointments/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/salon-spa-management/square-appointments/
providers:
- agent_band: agent-ready
  agent_readiness: 30.3
  band: strong
  in_catalog: true
  kin_score: 55.9
  mcp: *id001
  name: 123FormBuilder
  slug: 123formbuilder
  status: profiled
  tags: *id002
  url: /providers/123formbuilder/
- agent_band: agent-ready
  agent_readiness: 51.0
  band: exemplar
  in_catalog: true
  kin_score: 81.1
  mcp: *id003
  name: ActiveCampaign
  slug: activecampaign
  status: profiled
  tags: *id004
  url: /providers/activecampaign/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 30.4
  mcp: *id005
  name: Bench
  slug: bench
  status: profiled
  tags: *id006
  url: /providers/bench/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 84.3
  mcp: *id007
  name: BigCommerce
  slug: bigcommerce
  status: profiled
  tags: *id008
  url: /providers/bigcommerce/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id009
  name: ClassPass
  slug: classpass
  status: profiled
  tags: *id010
  url: /providers/classpass/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: thin
  in_catalog: true
  kin_score: 34.9
  mcp: *id011
  name: Cognito Forms
  slug: cognito-forms
  status: profiled
  tags: *id012
  url: /providers/cognito-forms/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.1
  mcp: *id013
  name: CommerceSync
  slug: commercesync
  status: profiled
  tags: *id014
  url: /providers/commercesync/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id015
  name: Davo
  slug: davo
  status: queued for profiling
  tags: *id016
  url: null
- agent_band: agent-aware
  agent_readiness: 19.7
  band: developing
  in_catalog: true
  kin_score: 42.2
  mcp: *id017
  name: Ecwid
  slug: ecwid
  status: profiled
  tags: *id018
  url: /providers/ecwid/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id019
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id020
  url: /providers/facebook/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 2.3
  mcp: *id021
  name: Giftya
  slug: giftya
  status: profiled
  tags: *id022
  url: /providers/giftya/
- agent_band: agent-ready
  agent_readiness: 36.4
  band: thin
  in_catalog: true
  kin_score: 30.4
  mcp: *id023
  name: GoDaddy
  slug: godaddy
  status: profiled
  tags: *id024
  url: /providers/godaddy/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id025
  name: Google (Reserve with Google)
  slug: google
  status: profiled
  tags: *id026
  url: /providers/google/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 34.1
  mcp: *id027
  name: Gravity Forms
  slug: gravity-forms
  status: profiled
  tags: *id028
  url: /providers/gravity-forms/
- agent_band: agent-aware
  agent_readiness: 9.4
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id029
  name: Groupon
  slug: groupon
  status: profiled
  tags: *id030
  url: /providers/groupon/
- agent_band: human-only
  agent_readiness: 3.1
  band: emerging
  in_catalog: true
  kin_score: 25.6
  mcp: *id031
  name: Homebase
  slug: homebase
  status: profiled
  tags: *id032
  url: /providers/homebase/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id033
  name: Humanity
  slug: humanity
  status: profiled
  tags: *id034
  url: /providers/humanity/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: emerging
  in_catalog: true
  kin_score: 21.8
  mcp: *id035
  name: Hurdlr
  slug: hurdlr
  status: profiled
  tags: *id036
  url: /providers/hurdlr/
- agent_band: agent-ready
  agent_readiness: 38.6
  band: exemplar
  in_catalog: true
  kin_score: 67.8
  mcp: *id037
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id038
  url: /providers/instagram/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 70.2
  mcp: *id039
  name: JotForm
  slug: jotform
  status: profiled
  tags: *id040
  url: /providers/jotform/
- agent_band: agent-ready
  agent_readiness: 28.9
  band: thin
  in_catalog: true
  kin_score: 30.3
  mcp: *id041
  name: Magento
  slug: magento
  status: profiled
  tags: *id042
  url: /providers/magento/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id043
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id044
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id045
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id046
  url: /providers/quickbooks/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.8
  mcp: *id047
  name: SHOGO
  slug: shogo
  status: profiled
  tags: *id048
  url: /providers/shogo/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 54.4
  mcp: *id049
  name: vCita
  slug: vcita
  status: profiled
  tags: *id050
  url: /providers/vcita/
- agent_band: agent-ready
  agent_readiness: 29.5
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id051
  name: When I Work
  slug: when-i-work
  status: profiled
  tags: *id052
  url: /providers/when-i-work/
- agent_band: agent-ready
  agent_readiness: 47.2
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id053
  name: Wix
  slug: wix
  status: profiled
  tags: *id054
  url: /providers/wix/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id055
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id056
  url: /providers/woocommerce/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id057
  name: WordPress.com
  slug: wordpress
  status: profiled
  tags: *id058
  url: /providers/wordpress/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: strong
  in_catalog: true
  kin_score: 55.3
  mcp: *id059
  name: Wufoo
  slug: wufoo
  status: profiled
  tags: *id060
  url: /providers/wufoo/
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
- agent_band: human-only
  agent_readiness: 0.7
  band: minimal
  in_catalog: true
  kin_score: 8.9
  mcp: *id063
  name: ZipRecruiter
  slug: ziprecruiter
  status: profiled
  tags: *id064
  url: /providers/ziprecruiter/
siblings:
- name: Booksy Biz
  rows: 5
  url: /applications/salon-spa-management/booksy-biz/
- name: Boulevard
  rows: 16
  url: /applications/salon-spa-management/boulevard/
- name: Fresha
  rows: 6
  url: /applications/salon-spa-management/fresha/
- name: Mindbody
  rows: 22
  url: /applications/salon-spa-management/mindbody/
- name: Open Salon
  rows: 2
  url: /applications/salon-spa-management/open-salon/
- name: Salon Booking System
  rows: 44
  url: /applications/salon-spa-management/salon-booking-system/
- name: Vagaro
  rows: 2
  url: /applications/salon-spa-management/vagaro/
sitemap: true
title: 'Square Appointments: Salon & Spa Management reference app'
---
