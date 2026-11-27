---
app: Little Green Light
app_slug: little-green-light
app_url: https://www.littlegreenlight.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.10.30
  key: AE-120.10.30
  layer: domain
  name: Address Validation & Autocomplete
  providers:
  - Smarty (SmartyStreets)
  url: /capabilities/geocoding/
  via_parent: Geocoding
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
  id: BC-4110
  key: events-group-operations-management
  layer: domain
  name: Events & Group Operations Management
  providers:
  - CourseStorm
  url: /capabilities/events-group-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4800.30
  key: fundraising-campaign-management
  layer: domain
  name: Fundraising Campaign Management
  providers:
  - Auctria
  - Donorbox
  - Fundraise Up
  - Give Lively
  - Givebutter
  - Harness (nonprofit giving app)
  - Rally Up
  url: /capabilities/fundraising-campaign-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.40.20
  key: AE-140.40.20
  layer: domain
  name: Memberships
  providers:
  - Member Essentials
  url: /capabilities/d2c-subscriptions/
  via_parent: D2C Subscriptions
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - PayPal
  - Square
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4800.20.10
  key: BC-4800.20.10
  layer: domain
  name: Prospect Research & Identification
  providers:
  - DonorSearch
  - Wealth Engine
  url: /capabilities/donor-relationship-management/
  via_parent: Donor Relationship Management
- attribution: API Evangelist extension
  id: AE-924
  key: AE-924
  layer: domain
  name: Volunteer Management
  providers:
  - Civic Champs
  url: /capabilities/volunteer-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Fundraising Report Card
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
  - QuickBooks Online
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: common
  name: Hosted Storefronts
  providers:
  - WooCommerce
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: common
  name: Online Forms & Survey Collection
  providers:
  - Google Forms
  - Gravity Forms
  - Jotform
  - Wufoo
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: common
  name: Spreadsheets & No-Code Databases
  providers:
  - Airtable
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
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
  id: nonprofit-crm-fundraising
  name: Nonprofit CRM & Fundraising
  url: /applications/nonprofit-crm-fundraising/
counts:
  declared: 28
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.littlegreenlight.com/integrations/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.3
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id001
      source: https://github.com/Airtable/airtable-mcp-cli
      status: verified
    slug: airtable
    status: profiled
    tags: &id002
    - Application
    - Collaboration
    - Data
    - Database
    url: /providers/airtable/
  layer: common
  name: Airtable
  provider: airtable
  says: lists Airtable as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 24.6
    mcp: &id003
      status: none
    slug: auctria
    status: profiled
    tags: &id004
    - Company
    - Fundraising
    - Non-Profit
    - Software-as-a-Service
    url: /providers/auctria/
  layer: domain
  name: Auctria
  provider: auctria
  says: lists Auctria as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    kin_score: 17.8
    mcp: &id005
      status: none
    slug: civic-champs
    status: profiled
    tags: &id006
    - Company
    - Nonprofit Software
    - Software-as-a-Service
    - Volunteer Management
    url: /providers/civic-champs/
  layer: domain
  name: Civic Champs
  provider: civic-champs
  says: lists Civic Champs as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    agent_readiness: 31.4
    band: exemplar
    in_catalog: true
    kin_score: 67.7
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
  source: https://www.littlegreenlight.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4110
    key: events-group-operations-management
    name: Events & Group Operations Management
    url: /capabilities/events-group-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 17.5
    mcp: &id009
      status: none
    slug: coursestorm
    status: profiled
    tags: &id010
    - Community
    - Education
    - Registration
    - Software-as-a-Service
    url: /providers/coursestorm/
  layer: domain
  name: CourseStorm
  provider: coursestorm
  says: lists CourseStorm as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    agent_band: agent-ready
    agent_readiness: 38.9
    band: thin
    in_catalog: true
    kin_score: 30.7
    mcp: &id011
      status: none
    slug: donorbox
    status: profiled
    tags: &id012
    - Donations
    - Fundraising
    - Non-Profit
    - Payments
    url: /providers/donorbox/
  layer: domain
  name: Donorbox
  provider: donorbox
  says: lists Donorbox as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    band: emerging
    in_catalog: true
    kin_score: 16.1
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
  source: https://www.littlegreenlight.com/integrations/
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
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 25.6
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
  source: https://www.littlegreenlight.com/integrations/
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
    agent_band: agent-ready
    agent_readiness: 49.0
    band: thin
    in_catalog: true
    kin_score: 27.1
    mcp: &id017
      status: none
    slug: fundraiseup
    status: profiled
    tags: &id018
    - Donations
    - Fundraising
    - Non-Profit
    - Payments
    url: /providers/fundraiseup/
  layer: domain
  name: Fundraise Up
  provider: fundraiseup
  says: lists Fundraise Up as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    band: emerging
    in_catalog: true
    kin_score: 19.5
    mcp: &id019
      status: none
    slug: fundraising-report-card
    status: profiled
    tags: &id020
    - Analytics
    - Company
    - Fundraising
    - Non-Profit
    url: /providers/fundraising-report-card/
  layer: common
  name: Fundraising Report Card
  provider: fundraising-report-card
  says: lists Fundraising Report Card as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    band: thin
    in_catalog: true
    kin_score: 33.1
    mcp: &id021
      status: none
    slug: give-lively
    status: profiled
    tags: &id022
    - Free
    - Fundraising
    - Non-Profit
    - Platform
    url: /providers/give-lively/
  layer: domain
  name: Give Lively
  provider: give-lively
  says: lists Give Lively as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    agent_band: agent-ready
    agent_readiness: 58.7
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id023
      status: none
    slug: givebutter
    status: profiled
    tags: &id024
    - CRM
    - Donations
    - Fundraising
    - Non-Profit
    url: /providers/givebutter/
  layer: domain
  name: Givebutter
  provider: givebutter
  says: lists Givebutter as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    agent_readiness: 35.8
    band: developing
    in_catalog: true
    kin_score: 53.1
    mcp: &id025
      status: none
    slug: google-forms
    status: profiled
    tags: &id026
    - Data Collection
    - Forms
    - Google
    - Google Workspace
    url: /providers/google-forms/
  layer: common
  name: Google Forms
  provider: google-forms
  says: lists Google Forms as an integration
  source: https://www.littlegreenlight.com/integrations/
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
  source: https://www.littlegreenlight.com/integrations/
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
    kin_score: 19.5
    mcp: &id029
      status: none
    slug: harness-giving
    status: profiled
    tags: &id030
    - Company
    - Giving
    - Non-Profit
    - Recurring Payments
    url: /providers/harness-giving/
  layer: domain
  name: Harness (nonprofit giving app)
  provider: harness-giving
  says: lists Harness (nonprofit giving app) as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    mcp: &id031
      source: https://github.com/jotform/mcp-server
      status: verified
    slug: jotform
    status: profiled
    tags: &id032
    - Data Collection
    - Forms
    - No-Code
    - Surveys
    url: /providers/jotform/
  layer: common
  name: Jotform
  provider: jotform
  says: lists Jotform as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    mcp: &id033
      status: none
    slug: mailchimp
    status: profiled
    tags: &id034
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://www.littlegreenlight.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.40.20
    key: AE-140.40.20
    name: Memberships
    url: /capabilities/d2c-subscriptions/
    via_parent: D2C Subscriptions
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id035
      status: unchecked
    slug: member-essentials
    status: queued for profiling
    tags: &id036 []
    url: null
  layer: domain
  name: Member Essentials
  provider: member-essentials
  says: lists Member Essentials as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    mcp: &id037
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id038
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: domain
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    mcp: &id039
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id040
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks Online
  provider: quickbooks
  says: lists QuickBooks Online as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    band: thin
    in_catalog: true
    kin_score: 28.2
    mcp: &id041
      status: unknown
    slug: rallyup
    status: profiled
    tags: &id042
    - Company
    - Fundraising
    - Non-Profit
    - Software-as-a-Service
    url: /providers/rallyup/
  layer: domain
  name: Rally Up
  provider: rallyup
  says: lists Rally Up as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 24.3
    band: thin
    in_catalog: true
    kin_score: 37.1
    mcp: &id043
      source: https://www.smarty.com/docs/mcp
      status: verified
    slug: smarty
    status: profiled
    tags: &id044
    - Address Autocomplete
    - Address Verification
    - Geocoding
    - ZIP Code
    url: /providers/smarty/
  layer: domain
  name: Smarty (SmartyStreets)
  provider: smarty
  says: lists Smarty (SmartyStreets) as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    agent_readiness: 61.5
    band: exemplar
    in_catalog: true
    kin_score: 78.2
    mcp: &id045
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id046
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: domain
  name: Square
  provider: square
  says: lists Square as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    mcp: &id047
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id048
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 22.3
    mcp: &id049
      status: none
    slug: wealthengine
    status: profiled
    tags: &id050
    - Analytics
    - Company
    - Data
    - Wealth
    url: /providers/wealthengine/
  layer: domain
  name: Wealth Engine
  provider: wealthengine
  says: lists Wealth Engine as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    mcp: &id051
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id052
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: common
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    mcp: &id053
      status: none
    slug: wufoo
    status: profiled
    tags: &id054
    - Data Collection
    - Form Builder
    - Forms
    - Surveys
    url: /providers/wufoo/
  layer: common
  name: Wufoo
  provider: wufoo
  says: lists Wufoo as an integration
  source: https://www.littlegreenlight.com/integrations/
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
    mcp: &id055
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id056
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.littlegreenlight.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/nonprofit-crm-fundraising/little-green-light/
providers:
- agent_band: agent-ready
  agent_readiness: 52.3
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id001
  name: Airtable
  slug: airtable
  status: profiled
  tags: *id002
  url: /providers/airtable/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 24.6
  mcp: *id003
  name: Auctria
  slug: auctria
  status: profiled
  tags: *id004
  url: /providers/auctria/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 17.8
  mcp: *id005
  name: Civic Champs
  slug: civic-champs
  status: profiled
  tags: *id006
  url: /providers/civic-champs/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id007
  name: Constant Contact
  slug: constant-contact
  status: profiled
  tags: *id008
  url: /providers/constant-contact/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 17.5
  mcp: *id009
  name: CourseStorm
  slug: coursestorm
  status: profiled
  tags: *id010
  url: /providers/coursestorm/
- agent_band: agent-ready
  agent_readiness: 38.9
  band: thin
  in_catalog: true
  kin_score: 30.7
  mcp: *id011
  name: Donorbox
  slug: donorbox
  status: profiled
  tags: *id012
  url: /providers/donorbox/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.1
  mcp: *id013
  name: DonorSearch
  slug: donorsearch
  status: profiled
  tags: *id014
  url: /providers/donorsearch/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 25.6
  mcp: *id015
  name: Double the Donation
  slug: double-the-donation
  status: profiled
  tags: *id016
  url: /providers/double-the-donation/
- agent_band: agent-ready
  agent_readiness: 49.0
  band: thin
  in_catalog: true
  kin_score: 27.1
  mcp: *id017
  name: Fundraise Up
  slug: fundraiseup
  status: profiled
  tags: *id018
  url: /providers/fundraiseup/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.5
  mcp: *id019
  name: Fundraising Report Card
  slug: fundraising-report-card
  status: profiled
  tags: *id020
  url: /providers/fundraising-report-card/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 33.1
  mcp: *id021
  name: Give Lively
  slug: give-lively
  status: profiled
  tags: *id022
  url: /providers/give-lively/
- agent_band: agent-ready
  agent_readiness: 58.7
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id023
  name: Givebutter
  slug: givebutter
  status: profiled
  tags: *id024
  url: /providers/givebutter/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: developing
  in_catalog: true
  kin_score: 53.1
  mcp: *id025
  name: Google Forms
  slug: google-forms
  status: profiled
  tags: *id026
  url: /providers/google-forms/
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
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.5
  mcp: *id029
  name: Harness (nonprofit giving app)
  slug: harness-giving
  status: profiled
  tags: *id030
  url: /providers/harness-giving/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 70.2
  mcp: *id031
  name: Jotform
  slug: jotform
  status: profiled
  tags: *id032
  url: /providers/jotform/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id033
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id034
  url: /providers/mailchimp/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id035
  name: Member Essentials
  slug: member-essentials
  status: queued for profiling
  tags: *id036
  url: null
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id037
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id038
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id039
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id040
  url: /providers/quickbooks/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 28.2
  mcp: *id041
  name: Rally Up
  slug: rallyup
  status: profiled
  tags: *id042
  url: /providers/rallyup/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: thin
  in_catalog: true
  kin_score: 37.1
  mcp: *id043
  name: Smarty (SmartyStreets)
  slug: smarty
  status: profiled
  tags: *id044
  url: /providers/smarty/
- agent_band: agent-native
  agent_readiness: 61.5
  band: exemplar
  in_catalog: true
  kin_score: 78.2
  mcp: *id045
  name: Square
  slug: square
  status: profiled
  tags: *id046
  url: /providers/square/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id047
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id048
  url: /providers/stripe/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 22.3
  mcp: *id049
  name: Wealth Engine
  slug: wealthengine
  status: profiled
  tags: *id050
  url: /providers/wealthengine/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id051
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id052
  url: /providers/woocommerce/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: strong
  in_catalog: true
  kin_score: 55.3
  mcp: *id053
  name: Wufoo
  slug: wufoo
  status: profiled
  tags: *id054
  url: /providers/wufoo/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id055
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id056
  url: /providers/zapier/
siblings:
- name: Bloomerang
  rows: 29
  url: /applications/nonprofit-crm-fundraising/bloomerang/
- name: CiviCRM
  rows: 10
  url: /applications/nonprofit-crm-fundraising/civicrm/
- name: DonorPerfect
  rows: 27
  url: /applications/nonprofit-crm-fundraising/donorperfect/
- name: Givebutter
  rows: 53
  url: /applications/nonprofit-crm-fundraising/givebutter/
- name: Neon CRM
  rows: 18
  url: /applications/nonprofit-crm-fundraising/neon-crm/
sitemap: true
title: 'Little Green Light: Nonprofit CRM & Fundraising reference app'
---
