---
access: understanding
agent_layer: []
apps:
- anchor: civicrm
  counts:
    declared: 0
    observed: 10
  evidence:
  - route: dependency manifest
    url: https://github.com/civicrm/civicrm-core/blob/master/composer.json
  - route: source code
    url: https://github.com/civicrm/civicrm-core/tree/master/CRM/Core/Payment
  - route: source code
    url: https://github.com/civicrm/civicrm-core/tree/master/CRM/Utils/Address
  - route: source code
    url: https://github.com/civicrm/civicrm-core/tree/master/CRM/Utils/Geocode
  - route: source code
    url: https://github.com/civicrm/civicrm-core/tree/master/ext
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Authorize.net
    provider: authorizenet
    says: ships the Authorize.net SDK or integration code
    source: https://github.com/civicrm/civicrm-core/tree/master/CRM/Core/Payment
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Elavon
    provider: elavon
    says: ships the Elavon SDK or integration code
    source: https://github.com/civicrm/civicrm-core/tree/master/ext
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: eWAY
    provider: eway
    says: ships the eWAY SDK or integration code
    source: https://github.com/civicrm/civicrm-core/tree/master/ext
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: First Data
    provider: first-data
    says: ships the First Data SDK or integration code
    source: https://github.com/civicrm/civicrm-core/tree/master/CRM/Core/Payment
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: Google Maps Geocoding
    provider: google-maps
    says: ships the Google Maps Geocoding SDK or integration code
    source: https://github.com/civicrm/civicrm-core/tree/master/CRM/Utils/Geocode
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: Google reCAPTCHA
    provider: google-recaptcha
    says: ships the Google reCAPTCHA SDK or integration code
    source: https://github.com/civicrm/civicrm-core/tree/master/ext
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: PayJunction
    provider: payjunction
    says: ships the PayJunction SDK or integration code
    source: https://github.com/civicrm/civicrm-core/tree/master/CRM/Core/Payment
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://github.com/civicrm/civicrm-core/tree/master/CRM/Core/Payment
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Realex Payments (Global Payments)
    provider: global-payments
    says: ships the Realex Payments (Global Payments) SDK or integration code
    source: https://github.com/civicrm/civicrm-core/tree/master/CRM/Core/Payment
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.30
      key: AE-120.10.30
      name: Address Validation & Autocomplete
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: domain
    name: USPS Address API
    provider: usps
    says: ships the USPS Address API SDK or integration code
    source: https://github.com/civicrm/civicrm-core/tree/master/CRM/Utils/Address
    tier: observed
  kind: self-hosted
  name: CiviCRM
  page: /applications/nonprofit-crm-fundraising/civicrm/
  slug: civicrm
  url: https://github.com/civicrm/civicrm-core
- anchor: bloomerang
  counts:
    declared: 29
    observed: 0
  evidence:
  - route: integrations page
    url: https://bloomerang.com/integrations/
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
    name: AddEvent
    provider: addevent
    says: lists AddEvent as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4110
      key: events-group-operations-management
      name: Events & Group Operations Management
      url: /capabilities/events-group-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amilia
    provider: amilia
    says: lists Amilia as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: Apple Pay
    provider: apple-pay
    says: lists Apple Pay as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: common
    name: Canva
    provider: canva
    says: lists Canva as an integration
    source: https://bloomerang.com/integrations/
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
    name: Constant Contact
    provider: constant-contact
    says: lists Constant Contact as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20.10
      key: BC-4800.20.10
      name: Prospect Research & Identification
      url: /capabilities/donor-relationship-management/
      via_parent: Donor Relationship Management
    credit: null
    layer: domain
    name: Dataro
    provider: dataro
    says: lists Dataro as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20.10
      key: BC-4800.20.10
      name: Prospect Research & Identification
      url: /capabilities/donor-relationship-management/
      via_parent: Donor Relationship Management
    credit: null
    layer: domain
    name: DonorSearch
    provider: donorsearch
    says: lists DonorSearch as an integration
    source: https://bloomerang.com/integrations/
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
    name: Emma
    provider: myemma
    says: lists Emma as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Facebook
    provider: facebook
    says: lists Facebook as an integration
    source: https://bloomerang.com/integrations/
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
    name: Gmail
    provider: google-gmail
    says: lists Gmail as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3260
      key: government-grants-funding-management
      name: Government Grants & Funding Management
      url: /capabilities/government-grants-funding-management/
      via_parent: null
    credit: null
    layer: domain
    name: GOOD Grants
    provider: good-grants
    says: lists GOOD Grants as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Google Analytics
    provider: google-analytics
    says: lists Google Analytics as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: Google Pay
    provider: google-pay
    says: lists Google Pay as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Sheets
    provider: google-sheets
    says: lists Google Sheets as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: common
    name: Hootsuite
    provider: hootsuite
    says: lists Hootsuite as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Instagram
    provider: instagram
    says: lists Instagram as an integration
    source: https://bloomerang.com/integrations/
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
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://bloomerang.com/integrations/
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
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: common
    name: Shopify
    provider: shopify
    says: lists Shopify as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Square
    provider: square
    says: lists Square as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: common
    name: ThankView
    provider: thankview
    says: lists ThankView as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: Venmo
    provider: venmo
    says: lists Venmo as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Verified First
    provider: verified-first
    says: lists Verified First as an integration
    source: https://bloomerang.com/integrations/
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
    source: https://bloomerang.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: common
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://bloomerang.com/integrations/
    tier: declared
  kind: commercial
  name: Bloomerang
  page: /applications/nonprofit-crm-fundraising/bloomerang/
  slug: bloomerang
  url: https://bloomerang.com/
- anchor: little-green-light
  counts:
    declared: 28
    observed: 0
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
    layer: common
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://www.littlegreenlight.com/integrations/
    tier: declared
  kind: commercial
  name: Little Green Light
  page: /applications/nonprofit-crm-fundraising/little-green-light/
  slug: little-green-light
  url: https://www.littlegreenlight.com/
- anchor: neon-crm
  counts:
    declared: 18
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.neonone.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4800.40.10
      key: BC-4800.40.10
      name: Gift Receipt & Processing
      url: /capabilities/gift-pledge-administration/
      via_parent: Gift & Pledge Administration
    credit: null
    layer: domain
    name: Chariot
    provider: chariot
    says: lists Chariot as an integration
    source: https://www.neonone.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.30
      key: fundraising-campaign-management
      name: Fundraising Campaign Management
      url: /capabilities/fundraising-campaign-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClickBid
    provider: clickbid
    says: lists ClickBid as an integration
    source: https://www.neonone.com/integrations/
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
    name: Constant Contact
    provider: constant-contact
    says: lists Constant Contact as an integration
    source: https://www.neonone.com/integrations/
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
    name: Cougar Mountain Software
    provider: cougar-mountain-software
    says: lists Cougar Mountain Software as an integration
    source: https://www.neonone.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.40.20
      key: AE-140.40.20
      name: Memberships
      url: /capabilities/d2c-subscriptions/
      via_parent: D2C Subscriptions
    credit: null
    layer: domain
    name: Cuseum
    provider: cuseum
    says: lists Cuseum as an integration
    source: https://www.neonone.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.30
      key: AE-230.30.30
      name: Employer Matching-Gift Data
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: Double the Donation
    provider: double-the-donation
    says: lists Double the Donation as an integration
    source: https://www.neonone.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50
      key: AE-210.50
      name: Event Ticketing
      url: /capabilities/event-ticketing/
      via_parent: null
    credit: null
    layer: domain
    name: Eventbrite
    provider: eventbrite
    says: lists Eventbrite as an integration
    source: https://www.neonone.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.30
      key: fundraising-campaign-management
      name: Fundraising Campaign Management
      url: /capabilities/fundraising-campaign-management/
      via_parent: null
    credit: null
    layer: domain
    name: GivBee
    provider: givbee
    says: lists GivBee as an integration
    source: https://www.neonone.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.30
      key: fundraising-campaign-management
      name: Fundraising Campaign Management
      url: /capabilities/fundraising-campaign-management/
      via_parent: null
    credit: null
    layer: domain
    name: Grassroots Unwired
    provider: grassroots-unwired
    says: lists Grassroots Unwired as an integration
    source: https://www.neonone.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.10
      key: AE-170.50.10
      name: Online Communities
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    credit: null
    layer: common
    name: Higher Logic
    provider: higher-logic
    says: lists Higher Logic as an integration
    source: https://www.neonone.com/integrations/
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
    source: https://www.neonone.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.30
      key: fundraising-campaign-management
      name: Fundraising Campaign Management
      url: /capabilities/fundraising-campaign-management/
      via_parent: null
    credit: null
    layer: domain
    name: Nuclavis
    provider: nuclavis
    says: lists Nuclavis as an integration
    source: https://www.neonone.com/integrations/
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
    source: https://www.neonone.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    credit: null
    layer: common
    name: TaxJar
    provider: taxjar
    says: lists TaxJar as an integration
    source: https://www.neonone.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.90
      key: AE-150.90
      name: Advocacy & Legislator Outreach
      url: /capabilities/advocacy-legislator-outreach/
      via_parent: null
    credit: null
    layer: domain
    name: Ujoin Advocacy
    provider: ujoin
    says: lists Ujoin Advocacy as an integration
    source: https://www.neonone.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-924
      key: AE-924
      name: Volunteer Management
      url: /capabilities/volunteer-management/
      via_parent: null
    credit: null
    layer: domain
    name: VolunteerLocal
    provider: volunteerlocal
    says: lists VolunteerLocal as an integration
    source: https://www.neonone.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20.10
      key: BC-4800.20.10
      name: Prospect Research & Identification
      url: /capabilities/donor-relationship-management/
      via_parent: Donor Relationship Management
    credit: null
    layer: domain
    name: Windfall Data
    provider: windfall
    says: lists Windfall Data as an integration
    source: https://www.neonone.com/integrations/
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
    source: https://www.neonone.com/integrations/
    tier: declared
  kind: commercial
  name: Neon CRM
  page: /applications/nonprofit-crm-fundraising/neon-crm/
  slug: neon-crm
  url: https://neonone.com/
- anchor: donorperfect
  counts:
    declared: 27
    observed: 0
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
    layer: domain
    name: Winspire
    provider: winspire
    says: lists Winspire as an integration
    source: https://www.donorperfect.com/integrations/
    tier: declared
  kind: commercial
  name: DonorPerfect
  page: /applications/nonprofit-crm-fundraising/donorperfect/
  slug: donorperfect
  url: https://www.donorperfect.com/
- anchor: givebutter
  counts:
    declared: 53
    observed: 0
  evidence:
  - route: integrations page
    url: https://givebutter.com/integrations
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
    name: AddEvent
    provider: addevent
    says: lists AddEvent as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4110
      key: events-group-operations-management
      name: Events & Group Operations Management
      url: /capabilities/events-group-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amilia
    provider: amilia
    says: lists Amilia as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: Apple Pay
    provider: apple-pay
    says: lists Apple Pay as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bloomerang
    provider: bloomerang
    says: lists Bloomerang as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: common
    name: Canva
    provider: canva
    says: lists Canva as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: Cash App
    provider: cash-app
    says: lists Cash App as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-210.60
      key: bank-relationship-management
      name: Bank Relationship Management
      url: /capabilities/bank-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Celtic Bank
    provider: celtic-bank
    says: lists Celtic Bank as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.40.10
      key: BC-4800.40.10
      name: Gift Receipt & Processing
      url: /capabilities/gift-pledge-administration/
      via_parent: Gift & Pledge Administration
    credit: null
    layer: domain
    name: Chariot
    provider: chariot
    says: lists Chariot as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: ChatGPT
    provider: openai
    says: lists ChatGPT as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Claude
    provider: anthropic
    says: lists Claude as an integration
    source: https://givebutter.com/integrations
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
    name: Constant Contact
    provider: constant-contact
    says: lists Constant Contact as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20.10
      key: BC-4800.20.10
      name: Prospect Research & Identification
      url: /capabilities/donor-relationship-management/
      via_parent: Donor Relationship Management
    credit: null
    layer: domain
    name: DonorSearch
    provider: donorsearch
    says: lists DonorSearch as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.30
      key: AE-230.30.30
      name: Employer Matching-Gift Data
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: Double the Donation
    provider: double-the-donation
    says: lists Double the Donation as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Facebook
    provider: facebook
    says: lists Facebook as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-210.60
      key: bank-relationship-management
      name: Bank Relationship Management
      url: /capabilities/bank-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Fifth Third Bank
    provider: fifth-third-bank
    says: lists Fifth Third Bank as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: common
    name: Giphy
    provider: giphy
    says: lists Giphy as an integration
    source: https://givebutter.com/integrations
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
    name: Gmail
    provider: google-gmail
    says: lists Gmail as an integration
    source: https://givebutter.com/integrations
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
    name: GoDaddy
    provider: godaddy
    says: lists GoDaddy as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Google Analytics
    provider: google-analytics
    says: lists Google Analytics as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: Google Maps
    provider: google-maps
    says: lists Google Maps as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: Google Pay
    provider: google-pay
    says: lists Google Pay as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Sheets
    provider: google-sheets
    says: lists Google Sheets as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Instagram
    provider: instagram
    says: lists Instagram as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: LinkedIn
    provider: linkedin
    says: lists LinkedIn as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Little Green Light
    provider: little-green-light
    says: lists Little Green Light as an integration
    source: https://givebutter.com/integrations
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
    source: https://givebutter.com/integrations
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
    name: monday.com
    provider: monday-com
    says: lists monday.com as an integration
    source: https://givebutter.com/integrations
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
    name: Omatic
    provider: omatic
    says: lists Omatic as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-924
      key: AE-924
      name: Volunteer Management
      url: /capabilities/volunteer-management/
      via_parent: null
    credit: null
    layer: domain
    name: POINT
    provider: point-app
    says: lists POINT as an integration
    source: https://givebutter.com/integrations
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
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Raiser's Edge NXT
    provider: blackbaud
    says: lists Raiser's Edge NXT as an integration
    source: https://givebutter.com/integrations
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
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://givebutter.com/integrations
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
    name: Squarespace
    provider: squarespace
    says: lists Squarespace as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-918
      key: AE-918
      name: Document Generation & Conversion
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: Storyraise
    provider: storyraise
    says: lists Storyraise as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: common
    name: ThankView
    provider: thankview
    says: lists ThankView as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Twitch
    provider: twitch
    says: lists Twitch as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Twitter
    provider: x
    says: lists Twitter as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: Venmo
    provider: venmo
    says: lists Venmo as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: common
    name: Vimeo
    provider: vimeo
    says: lists Vimeo as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-924
      key: AE-924
      name: Volunteer Management
      url: /capabilities/volunteer-management/
      via_parent: null
    credit: null
    layer: domain
    name: VolunteerHub
    provider: volunteerhub
    says: lists VolunteerHub as an integration
    source: https://givebutter.com/integrations
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
    name: Weebly
    provider: weebly
    says: lists Weebly as an integration
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: WhatsApp
    provider: whatsapp
    says: lists WhatsApp as an integration
    source: https://givebutter.com/integrations
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
    source: https://givebutter.com/integrations
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
    name: WordPress
    provider: wordpress
    says: lists WordPress as an integration
    source: https://givebutter.com/integrations
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
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: YouTube
    provider: youtube
    says: lists YouTube as an integration
    source: https://givebutter.com/integrations
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
    source: https://givebutter.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: common
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://givebutter.com/integrations
    tier: declared
  kind: commercial
  name: Givebutter
  page: /applications/nonprofit-crm-fundraising/givebutter/
  slug: givebutter
  url: https://givebutter.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: nonprofit-crm-fundraising
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Customer Relationship Management (CRM)
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#customer-relationship-management-crm
- category: Nonprofit
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Fundraising
  store: zapier
  url: https://zapier.com/apps
name: Nonprofit CRM & Fundraising
needs:
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: donations are taken by card/ACH gateways
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: public donation and signup forms
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: common
  why: geocoding contacts for districts and maps
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.30
    key: AE-120.10.30
    name: Address Validation & Autocomplete
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: domain
  why: mail-ready donor addresses (NCOA/CASS) for appeals
- capability:
    attribution: Turbo EA
    id: BC-4800.20.10
    key: BC-4800.20.10
    name: Prospect Research & Identification
    url: /capabilities/donor-relationship-management/
    via_parent: Donor Relationship Management
  fit: exact
  layer: domain
  why: wealth screening / prospect research; no node (see NOTES)
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: common
  why: gift batches post to the accounting system
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: appeals and newsletters sync donor lists
- capability:
    attribution: Turbo EA
    id: BC-4110
    key: events-group-operations-management
    name: Events & Group Operations Management
    url: /capabilities/events-group-operations-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: class and program registration
- capability:
    attribution: Turbo EA
    id: BC-300.10.20
    key: BC-300.10.20
    name: Candidate Screening and Selection
    url: /capabilities/talent-acquisition-management/
    via_parent: Talent Acquisition Management
  fit: exact
  layer: domain
  why: volunteer background checks
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: generic connector to everything else
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: exact
  layer: common
  why: gift notifications to team chat
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: nearest
  layer: common
  why: donation page analytics
- capability:
    attribution: Turbo EA
    id: BC-4800.20
    key: donor-relationship-management
    name: Donor Relationship Management
    url: /capabilities/donor-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: the category is the donor record; sync to other donor CRMs
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  fit: nearest
  layer: common
  why: thank-you and campaign videos
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: common
  why: donor email logging and calendar invites
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  fit: exact
  layer: common
  why: campaign graphics
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: common
  why: virtual events
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: exact
  layer: common
  why: merchandise sales tied to donors
- capability:
    attribution: Turbo EA
    id: BC-400.60.40
    key: BC-400.60.40
    name: Social Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: exact
  layer: common
  why: social post scheduling
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: common
  why: social fundraising and sharing
- capability:
    attribution: Turbo EA
    id: BC-3260
    key: government-grants-funding-management
    name: Government Grants & Funding Management
    url: /capabilities/government-grants-funding-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: grant applications and awards
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: exports to spreadsheets/bases
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.20
    key: AE-140.30.20
    name: Digital & Mobile Wallets
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  fit: exact
  layer: domain
  why: donation forms accept Apple Pay, Google Pay, Venmo, Cash App
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  fit: exact
  layer: common
  why: online forms feed contact records; no forms node (see NOTES)
- capability:
    attribution: Turbo EA
    id: BC-4800.30
    key: fundraising-campaign-management
    name: Fundraising Campaign Management
    url: /capabilities/fundraising-campaign-management/
    via_parent: null
  fit: exact
  layer: domain
  why: online giving, peer-to-peer, auctions and events feed gifts into the CRM
- capability:
    attribution: API Evangelist extension
    id: AE-924
    key: AE-924
    name: Volunteer Management
    url: /capabilities/volunteer-management/
    via_parent: null
  fit: exact
  layer: domain
  why: volunteer scheduling and hours
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.30
    key: AE-230.30.30
    name: Employer Matching-Gift Data
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  fit: exact
  layer: domain
  why: matching-gift eligibility lookups on donor records
- capability:
    attribution: API Evangelist extension
    id: AE-140.40.20
    key: AE-140.40.20
    name: Memberships
    url: /capabilities/d2c-subscriptions/
    via_parent: D2C Subscriptions
  fit: nearest
  layer: domain
  why: membership programs for museums and associations
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: common
  why: fundraising dashboards and benchmarks
- capability:
    attribution: Turbo EA
    id: BC-4800.40.10
    key: BC-4800.40.10
    name: Gift Receipt & Processing
    url: /capabilities/gift-pledge-administration/
    via_parent: Gift & Pledge Administration
  fit: exact
  layer: domain
  why: DAF and stock gifts are a distinct giving rail with no node
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  fit: exact
  layer: common
  why: sales tax on store/event sales
- capability:
    attribution: API Evangelist extension
    id: AE-210.50
    key: AE-210.50
    name: Event Ticketing
    url: /capabilities/event-ticketing/
    via_parent: null
  fit: exact
  layer: domain
  why: galas and ticketed events
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.10
    key: AE-170.50.10
    name: Online Communities
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  fit: exact
  layer: common
  why: member communities
- capability:
    attribution: API Evangelist extension
    id: AE-912
    key: AE-912
    name: Direct Mail APIs
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: exact
  layer: domain
  why: printed and handwritten appeal mail
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: AI assistants connected to the donor data
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: common
  why: campaign page GIFs
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  fit: nearest
  layer: common
  why: embedding donation forms in website builders
- capability:
    attribution: API Evangelist extension
    id: AE-918
    key: AE-918
    name: Document Generation & Conversion
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: nearest
  layer: common
  why: annual/impact report generation
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: sharing campaigns over messaging
- capability:
    attribution: Turbo EA
    id: BC-210.60
    key: bank-relationship-management
    name: Bank Relationship Management
    url: /capabilities/bank-relationship-management/
    via_parent: null
  fit: nearest
  layer: common
  why: banking/card partner behind payouts
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4800.30
      key: fundraising-campaign-management
      name: Fundraising Campaign Management
      url: /capabilities/fundraising-campaign-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 58.7
      apps:
      - Little Green Light
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        status: none
      name: Givebutter
      slug: givebutter
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - CRM
      - Donations
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/givebutter/
    - agent_band: agent-aware
      agent_readiness: 5.6
      apps:
      - DonorPerfect
      band: thin
      in_catalog: true
      kin_score: 38.4
      mcp:
        status: none
      name: Givecloud
      slug: givecloud
      sources:
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Company
      - Fundraising
      - Non-Profit
      - Software-as-a-Service
      tier: declared
      url: /providers/givecloud/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Little Green Light
      band: thin
      in_catalog: true
      kin_score: 33.1
      mcp:
        status: none
      name: Give Lively
      slug: give-lively
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Free
      - Fundraising
      - Non-Profit
      - Platform
      tier: declared
      url: /providers/give-lively/
    - agent_band: agent-ready
      agent_readiness: 38.9
      apps:
      - Little Green Light
      band: thin
      in_catalog: true
      kin_score: 30.7
      mcp:
        status: none
      name: Donorbox
      slug: donorbox
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Donations
      - Fundraising
      - Non-Profit
      - Payments
      tier: declared
      url: /providers/donorbox/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Little Green Light
      band: thin
      in_catalog: true
      kin_score: 28.2
      mcp:
        status: unknown
      name: Rally Up
      slug: rallyup
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Company
      - Fundraising
      - Non-Profit
      - Software-as-a-Service
      tier: declared
      url: /providers/rallyup/
    - agent_band: agent-ready
      agent_readiness: 49.0
      apps:
      - Little Green Light
      band: thin
      in_catalog: true
      kin_score: 27.1
      mcp:
        status: none
      name: Fundraise Up
      slug: fundraiseup
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Donations
      - Fundraising
      - Non-Profit
      - Payments
      tier: declared
      url: /providers/fundraiseup/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - DonorPerfect
      band: thin
      in_catalog: true
      kin_score: 27.1
      mcp:
        status: unknown
      name: ReadySetAuction
      slug: readysetauction
      sources:
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Auction Software
      - Event Management
      - Mobile Bidding
      - Online Auction
      tier: declared
      url: /providers/readysetauction/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Little Green Light
      band: emerging
      in_catalog: true
      kin_score: 24.6
      mcp:
        status: none
      name: Auctria
      slug: auctria
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Company
      - Fundraising
      - Non-Profit
      - Software-as-a-Service
      tier: declared
      url: /providers/auctria/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - DonorPerfect
      band: emerging
      in_catalog: true
      kin_score: 20.8
      mcp:
        status: unknown
      name: ShopRaise
      slug: shopraise
      sources:
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Company
      - E-Commerce
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/shopraise/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Little Green Light
      band: emerging
      in_catalog: true
      kin_score: 19.5
      mcp:
        status: none
      name: Harness (nonprofit giving app)
      slug: harness-giving
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Company
      - Giving
      - Non-Profit
      - Recurring Payments
      tier: declared
      url: /providers/harness-giving/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Neon CRM
      band: emerging
      in_catalog: true
      kin_score: 15.8
      mcp:
        status: unknown
      name: Nuclavis
      slug: nuclavis
      sources:
      - https://www.neonone.com/integrations/
      status: profiled
      tags:
      - Fundraising
      - Mobile
      - Non-Profit
      - P2P
      tier: declared
      url: /providers/nuclavis/
    - agent_band: human-only
      agent_readiness: 1.1
      apps:
      - Neon CRM
      band: emerging
      in_catalog: true
      kin_score: 13.8
      mcp:
        status: none
      name: ClickBid
      slug: clickbid
      sources:
      - https://www.neonone.com/integrations/
      status: profiled
      tags:
      - Company
      - Gaming
      - Mobile
      - Payments
      tier: declared
      url: /providers/clickbid/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Neon CRM
      band: minimal
      in_catalog: true
      kin_score: 10.1
      mcp:
        status: unknown
      name: GivBee
      slug: givbee
      sources:
      - https://www.neonone.com/integrations/
      status: profiled
      tags:
      - Company
      - Messaging
      - Non-Profit
      - SMS
      tier: declared
      url: /providers/givbee/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Neon CRM
      band: minimal
      in_catalog: true
      kin_score: 6.2
      mcp:
        status: none
      name: Grassroots Unwired
      slug: grassroots-unwired
      sources:
      - https://www.neonone.com/integrations/
      status: profiled
      tags:
      - Company
      - Fundraising
      - Non-Profit
      - Political Campaigns
      tier: declared
      url: /providers/grassroots-unwired/
    - agent_band: null
      agent_readiness: null
      apps:
      - DonorPerfect
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: raisin
      slug: raisin-donations
      sources:
      - https://www.donorperfect.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - DonorPerfect
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Winspire
      slug: winspire
      sources:
      - https://www.donorperfect.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Bloomerang
      - CiviCRM
      - DonorPerfect
      - Givebutter
      - Little Green Light
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://bloomerang.com/integrations/
      - https://github.com/civicrm/civicrm-core/tree/master/CRM/Core/Payment
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Bloomerang
      - Givebutter
      - Little Green Light
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: declared
      url: /providers/stripe/
    - agent_band: agent-native
      agent_readiness: 61.5
      apps:
      - Bloomerang
      - Little Green Light
      band: exemplar
      in_catalog: true
      kin_score: 78.2
      mcp:
        source: https://developer.squareup.com/docs/mcp
        status: verified
      name: Square
      slug: square
      sources:
      - https://bloomerang.com/integrations/
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Booking
      - Location
      - Restaurant
      - Square
      tier: declared
      url: /providers/square/
    - agent_band: agent-aware
      agent_readiness: 5.3
      apps:
      - CiviCRM
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        status: none
      name: eWAY
      slug: eway
      sources:
      - https://github.com/civicrm/civicrm-core/tree/master/ext
      status: profiled
      tags:
      - Australia
      - Payment Gateway
      - Payment Processing
      - Payments
      tier: observed
      url: /providers/eway/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - CiviCRM
      band: thin
      in_catalog: true
      kin_score: 37.3
      mcp:
        status: none
      name: PayJunction
      slug: payjunction
      sources:
      - https://github.com/civicrm/civicrm-core/tree/master/CRM/Core/Payment
      status: profiled
      tags:
      - B2B
      - Fintech
      - Payments
      - Software-as-a-Service
      tier: observed
      url: /providers/payjunction/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - CiviCRM
      band: thin
      in_catalog: true
      kin_score: 35.5
      mcp:
        source: https://github.com/AuthorizeNet/authorize-net-mcp
        status: verified
      name: Authorize.net
      slug: authorizenet
      sources:
      - https://github.com/civicrm/civicrm-core/tree/master/CRM/Core/Payment
      status: profiled
      tags:
      - Company
      - Credit Cards
      - Payment Gateway
      - Payments
      tier: observed
      url: /providers/authorizenet/
    - agent_band: agent-ready
      agent_readiness: 31.7
      apps:
      - CiviCRM
      band: thin
      in_catalog: true
      kin_score: 30.1
      mcp:
        status: none
      name: Elavon
      slug: elavon
      sources:
      - https://github.com/civicrm/civicrm-core/tree/master/ext
      status: profiled
      tags:
      - Company
      - Fintech
      - Merchant Services
      - Payments
      tier: observed
      url: /providers/elavon/
    - agent_band: agent-aware
      agent_readiness: 22.0
      apps:
      - CiviCRM
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        source: https://github.com/globalpayments/mcp-server
        status: verified
      name: Realex Payments (Global Payments)
      slug: global-payments
      sources:
      - https://github.com/civicrm/civicrm-core/tree/master/CRM/Core/Payment
      status: profiled
      tags:
      - E-Commerce
      - Payment Processing
      - Payment Technology
      - Payments
      tier: observed
      url: /providers/global-payments/
    - agent_band: agent-aware
      agent_readiness: 7.0
      apps:
      - CiviCRM
      band: emerging
      in_catalog: true
      kin_score: 15.8
      mcp:
        status: none
      name: First Data
      slug: first-data
      sources:
      - https://github.com/civicrm/civicrm-core/tree/master/CRM/Core/Payment
      status: profiled
      tags:
      - Financial Services
      - Merchant Services
      - Payments
      - Transaction Processing
      tier: observed
      url: /providers/first-data/
  - capability:
      attribution: Turbo EA
      id: BC-4800.20.10
      key: BC-4800.20.10
      name: Prospect Research & Identification
      url: /capabilities/donor-relationship-management/
      via_parent: Donor Relationship Management
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Bloomerang
      - DonorPerfect
      - Givebutter
      - Little Green Light
      band: emerging
      in_catalog: true
      kin_score: 16.1
      mcp:
        status: none
      name: DonorSearch
      slug: donorsearch
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Company
      - Donor Research
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/donorsearch/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Neon CRM
      band: developing
      in_catalog: true
      kin_score: 53.8
      mcp:
        status: none
      name: Windfall Data
      slug: windfall
      sources:
      - https://www.neonone.com/integrations/
      status: profiled
      tags:
      - Company
      - Data Enrichment
      - Fintech
      - Wealth Data
      tier: declared
      url: /providers/windfall/
    - agent_band: human-only
      agent_readiness: 2.8
      apps:
      - DonorPerfect
      band: emerging
      in_catalog: true
      kin_score: 24.3
      mcp:
        status: unknown
      name: Kindsight
      slug: kindsight
      sources:
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Data
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/kindsight/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Little Green Light
      band: emerging
      in_catalog: true
      kin_score: 22.3
      mcp:
        status: none
      name: Wealth Engine
      slug: wealthengine
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Company
      - Data
      - Wealth
      tier: declared
      url: /providers/wealthengine/
    - agent_band: null
      agent_readiness: null
      apps:
      - Bloomerang
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Dataro
      slug: dataro
      sources:
      - https://bloomerang.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.7
      apps:
      - Bloomerang
      - Givebutter
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google Pay
      slug: google-pay
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Agentic Commerce
      - Checkout
      - Contactless Payments
      - Digital Wallet
      tier: declared
      url: /providers/google-pay/
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - Bloomerang
      - Givebutter
      band: developing
      in_catalog: true
      kin_score: 43.0
      mcp:
        status: none
      name: Apple Pay
      slug: apple-pay
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Apple
      - Contactless Payments
      - Digital Wallet
      - E-Commerce
      tier: declared
      url: /providers/apple-pay/
    - agent_band: human-only
      agent_readiness: 3.8
      apps:
      - Bloomerang
      - Givebutter
      band: thin
      in_catalog: true
      kin_score: 29.8
      mcp:
        status: none
      name: Venmo
      slug: venmo
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Company
      - Consumer
      - Fintech
      - Payments
      tier: declared
      url: /providers/venmo/
    - agent_band: agent-native
      agent_readiness: 40.8
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: Cash App
      slug: cash-app
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Financial Services
      - Fintech
      - Payments
      - United States
      tier: declared
      url: /providers/cash-app/
  - capability:
      attribution: API Evangelist extension
      id: AE-924
      key: AE-924
      name: Volunteer Management
      url: /capabilities/volunteer-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - DonorPerfect
      - Givebutter
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        status: unknown
      name: POINT
      slug: point-app
      sources:
      - https://givebutter.com/integrations
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/point-app/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - DonorPerfect
      band: emerging
      in_catalog: true
      kin_score: 25.7
      mcp:
        status: unknown
      name: Volunteer Matrix
      slug: volunteer-matrix
      sources:
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Community
      - Non-Profit
      - Software-as-a-Service
      - Volunteer Management
      tier: declared
      url: /providers/volunteer-matrix/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Givebutter
      band: emerging
      in_catalog: true
      kin_score: 25.1
      mcp:
        status: none
      name: VolunteerHub
      slug: volunteerhub
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Non-Profit
      - Recruiting
      - Scheduling
      - Volunteer Management
      tier: declared
      url: /providers/volunteerhub/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Neon CRM
      band: emerging
      in_catalog: true
      kin_score: 24.1
      mcp:
        status: unknown
      name: VolunteerLocal
      slug: volunteerlocal
      sources:
      - https://www.neonone.com/integrations/
      status: profiled
      tags:
      - Communications
      - Scheduling
      - Tracking
      - Volunteer Management
      tier: declared
      url: /providers/volunteerlocal/
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - DonorPerfect
      band: emerging
      in_catalog: true
      kin_score: 21.3
      mcp:
        status: unknown
      name: SignUp.com
      slug: signup-com
      sources:
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Education
      - Scheduling
      - Software-as-a-Service
      - Volunteer
      tier: declared
      url: /providers/signup-com/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Little Green Light
      band: emerging
      in_catalog: true
      kin_score: 17.8
      mcp:
        status: none
      name: Civic Champs
      slug: civic-champs
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Company
      - Nonprofit Software
      - Software-as-a-Service
      - Volunteer Management
      tier: declared
      url: /providers/civic-champs/
  - capability:
      attribution: Turbo EA
      id: BC-4800.20
      key: donor-relationship-management
      name: Donor Relationship Management
      url: /capabilities/donor-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Bloomerang
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 31.6
      apps:
      - Givebutter
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: Raiser's Edge NXT
      slug: blackbaud
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - CRM
      - Donor Management
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/blackbaud/
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - Givebutter
      band: thin
      in_catalog: true
      kin_score: 30.0
      mcp:
        status: none
      name: Bloomerang
      slug: bloomerang
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - CRM
      - Donor Management
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/bloomerang/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Givebutter
      band: thin
      in_catalog: true
      kin_score: 28.6
      mcp:
        status: unknown
      name: Little Green Light
      slug: little-green-light
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Donor Management
      - Fundraising
      - Nonprofit Software
      - Online Donations
      tier: declared
      url: /providers/little-green-light/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.30
      key: AE-230.30.30
      name: Employer Matching-Gift Data
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - DonorPerfect
      - Givebutter
      - Little Green Light
      - Neon CRM
      band: emerging
      in_catalog: true
      kin_score: 25.6
      mcp:
        status: unknown
      name: Double the Donation
      slug: double-the-donation
      sources:
      - https://givebutter.com/integrations
      - https://www.donorperfect.com/integrations/
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Company
      - Fundraising
      - Matching Gifts
      - Non-Profit
      tier: declared
      url: /providers/double-the-donation/
  - capability:
      attribution: Turbo EA
      id: BC-4800.40.10
      key: BC-4800.40.10
      name: Gift Receipt & Processing
      url: /capabilities/gift-pledge-administration/
      via_parent: Gift & Pledge Administration
    providers:
    - agent_band: agent-native
      agent_readiness: 61.6
      apps:
      - DonorPerfect
      - Givebutter
      - Neon CRM
      band: strong
      in_catalog: true
      kin_score: 59.5
      mcp:
        status: none
      name: Chariot
      slug: chariot
      sources:
      - https://givebutter.com/integrations
      - https://www.donorperfect.com/integrations/
      - https://www.neonone.com/integrations/
      status: profiled
      tags:
      - Charitable Giving
      - Donor-Advised Funds
      - Non-Profit
      - Payments
      tier: declared
      url: /providers/chariot/
    - agent_band: human-only
      agent_readiness: 3.2
      apps:
      - DonorPerfect
      band: emerging
      in_catalog: true
      kin_score: 18.5
      mcp:
        status: unknown
      name: DonateStock
      slug: donatestock
      sources:
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Charity
      - Company
      - Finance
      - Stocks
      tier: declared
      url: /providers/donatestock/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.30
      key: AE-120.10.30
      name: Address Validation & Autocomplete
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-native
      agent_readiness: 51.8
      apps:
      - CiviCRM
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        status: none
      name: USPS Address API
      slug: usps
      sources:
      - https://github.com/civicrm/civicrm-core/tree/master/CRM/Utils/Address
      status: profiled
      tags:
      - Government
      - Logistics
      - Postal Service
      - Shipping
      tier: observed
      url: /providers/usps/
    - agent_band: agent-aware
      agent_readiness: 24.3
      apps:
      - Little Green Light
      band: thin
      in_catalog: true
      kin_score: 37.1
      mcp:
        source: https://www.smarty.com/docs/mcp
        status: verified
      name: Smarty (SmartyStreets)
      slug: smarty
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Address Autocomplete
      - Address Verification
      - Geocoding
      - ZIP Code
      tier: declared
      url: /providers/smarty/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - DonorPerfect
      band: emerging
      in_catalog: true
      kin_score: 22.8
      mcp:
        status: unknown
      name: USgeocoder
      slug: usgeocoder
      sources:
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Company
      - District
      - Location
      - Tax
      tier: declared
      url: /providers/usgeocoder/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50
      key: AE-210.50
      name: Event Ticketing
      url: /capabilities/event-ticketing/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Neon CRM
      band: developing
      in_catalog: true
      kin_score: 41.6
      mcp:
        status: none
      name: Eventbrite
      slug: eventbrite
      sources:
      - https://www.neonone.com/integrations/
      status: profiled
      tags:
      - Event
      - Event Technology
      - Marketplace
      - Ticketing
      tier: declared
      url: /providers/eventbrite/
    - agent_band: human-only
      agent_readiness: 0.7
      apps:
      - DonorPerfect
      band: emerging
      in_catalog: true
      kin_score: 23.7
      mcp:
        status: unknown
      name: SimpleTix
      slug: simpletix
      sources:
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Company
      - Event
      - Software-as-a-Service
      - Ticketing
      tier: declared
      url: /providers/simpletix/
    - agent_band: human-only
      agent_readiness: 1.1
      apps:
      - DonorPerfect
      band: emerging
      in_catalog: true
      kin_score: 13.0
      mcp:
        status: unknown
      name: Agile Ticketing
      slug: agile-ticketing
      sources:
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Company
      - Event
      - Hospitality
      - Ticketing
      tier: declared
      url: /providers/agile-ticketing/
  - capability:
      attribution: Turbo EA
      id: BC-4110
      key: events-group-operations-management
      name: Events & Group Operations Management
      url: /capabilities/events-group-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - Bloomerang
      - Givebutter
      band: thin
      in_catalog: true
      kin_score: 29.1
      mcp:
        status: none
      name: Amilia
      slug: amilia
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Company
      - Membership
      - Recreation
      - Software
      tier: declared
      url: /providers/amilia/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Little Green Light
      band: emerging
      in_catalog: true
      kin_score: 17.5
      mcp:
        status: none
      name: CourseStorm
      slug: coursestorm
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Community
      - Education
      - Registration
      - Software-as-a-Service
      tier: declared
      url: /providers/coursestorm/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.90
      key: AE-150.90
      name: Advocacy & Legislator Outreach
      url: /capabilities/advocacy-legislator-outreach/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Neon CRM
      band: emerging
      in_catalog: true
      kin_score: 14.2
      mcp:
        status: unknown
      name: Ujoin Advocacy
      slug: ujoin
      sources:
      - https://www.neonone.com/integrations/
      status: profiled
      tags:
      - Advocacy
      - Company
      - Grassroots
      - Policy
      tier: declared
      url: /providers/ujoin/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - DonorPerfect
      band: minimal
      in_catalog: true
      kin_score: 3.4
      mcp:
        status: unknown
      name: Congress Plus
      slug: congress-plus
      sources:
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Data
      - Government
      - Mobile
      - Platform
      tier: declared
      url: /providers/congress-plus/
  - capability:
      attribution: API Evangelist extension
      id: AE-912
      key: AE-912
      name: Direct Mail APIs
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.6
      apps:
      - DonorPerfect
      band: thin
      in_catalog: true
      kin_score: 30.4
      mcp:
        status: unknown
      name: Scribe Handwritten
      slug: scribe-handwritten
      sources:
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Collaboration
      - Company
      - Digital
      - Handwriting
      tier: declared
      url: /providers/scribe-handwritten/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - DonorPerfect
      band: emerging
      in_catalog: true
      kin_score: 24.1
      mcp:
        status: none
      name: PostcardMania
      slug: postcardmania
      sources:
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Automation
      - Direct Mail
      - Marketing
      - Small Business
      tier: declared
      url: /providers/postcardmania/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.40.20
      key: AE-140.40.20
      name: Memberships
      url: /capabilities/d2c-subscriptions/
      via_parent: D2C Subscriptions
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Neon CRM
      band: emerging
      in_catalog: true
      kin_score: 22.5
      mcp:
        status: none
      name: Cuseum
      slug: cuseum
      sources:
      - https://www.neonone.com/integrations/
      status: profiled
      tags:
      - Company
      - Cultural Institutions
      - Museums
      - Non-Profit
      tier: declared
      url: /providers/cuseum/
    - agent_band: null
      agent_readiness: null
      apps:
      - Little Green Light
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Member Essentials
      slug: member-essentials
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Bloomerang
      band: emerging
      in_catalog: true
      kin_score: 24.7
      mcp:
        status: none
      name: Verified First
      slug: verified-first
      sources:
      - https://bloomerang.com/integrations/
      status: profiled
      tags:
      - Background Checks
      - Company
      - Screening
      - Verification
      tier: declared
      url: /providers/verified-first/
  - capability:
      attribution: Turbo EA
      id: BC-3260
      key: government-grants-funding-management
      name: Government Grants & Funding Management
      url: /capabilities/government-grants-funding-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Bloomerang
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: unknown
      name: GOOD Grants
      slug: good-grants
      sources:
      - https://bloomerang.com/integrations/
      status: profiled
      tags:
      - Company
      - Grants
      - Non-Profit
      - Software-as-a-Service
      tier: declared
      url: /providers/good-grants/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Bloomerang
      - DonorPerfect
      - Givebutter
      - Little Green Light
      - Neon CRM
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - Bloomerang
      - DonorPerfect
      - Givebutter
      - Little Green Light
      - Neon CRM
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        status: none
      name: Constant Contact
      slug: constant-contact
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Campaigns
      - Contacts
      - Email Marketing
      - Event
      tier: declared
      url: /providers/constant-contact/
    - agent_band: agent-aware
      agent_readiness: 21.5
      apps:
      - Bloomerang
      band: thin
      in_catalog: true
      kin_score: 27.3
      mcp:
        status: none
      name: Emma
      slug: myemma
      sources:
      - https://bloomerang.com/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Automation
      - Email Marketing
      - SMS
      tier: declared
      url: /providers/myemma/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Bloomerang
      - DonorPerfect
      - Givebutter
      - Little Green Light
      - Neon CRM
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks Online
      slug: quickbooks
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - DonorPerfect
      - Givebutter
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: Sage Intacct Fundraising
      slug: sage-intacct
      sources:
      - https://givebutter.com/integrations
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Accounting
      - ERP
      - Financial Management
      - General Ledger
      tier: declared
      url: /providers/sage-intacct/
    - agent_band: agent-native
      agent_readiness: 60.0
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 87.1
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: declared
      url: /providers/xero/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Neon CRM
      band: emerging
      in_catalog: true
      kin_score: 12.8
      mcp:
        status: unknown
      name: Cougar Mountain Software
      slug: cougar-mountain-software
      sources:
      - https://www.neonone.com/integrations/
      status: profiled
      tags:
      - Accounting
      - Non-Profit
      - Small Business
      - Software
      tier: declared
      url: /providers/cougar-mountain-software/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
      - Bloomerang
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 67.8
      mcp:
        status: none
      name: Instagram
      slug: instagram
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Instagram
      - Meta
      - Photos
      - Social Media
      tier: declared
      url: /providers/instagram/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Bloomerang
      - Givebutter
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: declared
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp:
        status: none
      name: LinkedIn
      slug: linkedin
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: declared
      url: /providers/linkedin/
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: Twitter
      slug: x
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: declared
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - Givebutter
      band: strong
      in_catalog: true
      kin_score: 65.4
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: declared
      url: /providers/youtube/
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Givebutter
      band: developing
      in_catalog: true
      kin_score: 48.2
      mcp:
        status: none
      name: Twitch
      slug: twitch
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Entertainment
      - Gaming
      - Live Streaming
      - Streaming
      tier: declared
      url: /providers/twitch/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Bloomerang
      - Givebutter
      - Little Green Light
      - Neon CRM
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 50.3
      apps:
      - Givebutter
      band: thin
      in_catalog: true
      kin_score: 32.2
      mcp:
        source: https://github.com/mondaycom/mcp
        status: verified
      name: monday.com
      slug: monday-com
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Automation
      - CRM
      - GraphQL
      - Work Management
      tier: declared
      url: /providers/monday-com/
    - agent_band: null
      agent_readiness: null
      apps:
      - Givebutter
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Omatic
      slug: omatic
      sources:
      - https://givebutter.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 48.5
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 68.7
      mcp:
        status: none
      name: Squarespace
      slug: squarespace
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Marketing
      - Payments
      tier: declared
      url: /providers/squarespace/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Givebutter
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        source: https://github.com/WordPress/mcp-adapter
        status: verified
      name: WordPress
      slug: wordpress
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - CMS
      - Content Management
      - Open Source
      - WordPress
      tier: declared
      url: /providers/wordpress/
    - agent_band: agent-ready
      agent_readiness: 47.2
      apps:
      - Givebutter
      band: thin
      in_catalog: true
      kin_score: 35.5
      mcp:
        source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
        status: verified
      name: Wix
      slug: wix
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - CMS
      - E-Commerce
      - Headless
      - Website Builder
      tier: declared
      url: /providers/wix/
    - agent_band: agent-ready
      agent_readiness: 36.4
      apps:
      - Givebutter
      band: thin
      in_catalog: true
      kin_score: 30.4
      mcp:
        source: https://developer.godaddy.com/mcp
        status: verified
      name: GoDaddy
      slug: godaddy
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Aftermarket
      - Certificates
      - DNS
      - Domains
      tier: declared
      url: /providers/godaddy/
    - agent_band: agent-aware
      agent_readiness: 13.3
      apps:
      - Givebutter
      band: emerging
      in_catalog: true
      kin_score: 20.3
      mcp:
        status: none
      name: Weebly
      slug: weebly
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Blogging
      - E-Commerce
      - Sites
      - Website Builder
      tier: declared
      url: /providers/weebly/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - Bloomerang
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 66.8
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: declared
      url: /providers/google-gmail/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Bloomerang
      - Givebutter
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: AddEvent
      slug: addevent
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Calendar
      - Integration
      - Marketing
      - Software-as-a-Service
      tier: declared
      url: /providers/addevent/
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Little Green Light
      band: exemplar
      in_catalog: true
      kin_score: 70.2
      mcp:
        source: https://github.com/jotform/mcp-server
        status: verified
      name: Jotform
      slug: jotform
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Data Collection
      - Forms
      - No-Code
      - Surveys
      tier: declared
      url: /providers/jotform/
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Little Green Light
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: Wufoo
      slug: wufoo
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Data Collection
      - Form Builder
      - Forms
      - Surveys
      tier: declared
      url: /providers/wufoo/
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Little Green Light
      band: developing
      in_catalog: true
      kin_score: 53.1
      mcp:
        status: none
      name: Google Forms
      slug: google-forms
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Data Collection
      - Forms
      - Google
      - Google Workspace
      tier: declared
      url: /providers/google-forms/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Little Green Light
      band: thin
      in_catalog: true
      kin_score: 34.1
      mcp:
        status: none
      name: Gravity Forms
      slug: gravity-forms
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Form Builder
      - Forms
      - Surveys
      - WordPress
      tier: declared
      url: /providers/gravity-forms/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Bloomerang
      - Givebutter
      band: emerging
      in_catalog: true
      kin_score: 14.8
      mcp:
        status: unknown
      name: ThankView
      slug: thankview
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Fundraising
      - Marketing
      - Non-Profit
      - Video
      tier: declared
      url: /providers/thankview/
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - Givebutter
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp:
        source: https://developer.vimeo.com/api/mcp-server
        status: documented
      name: Vimeo
      slug: vimeo
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Live Streaming
      - Streaming
      - Video
      - Video Hosting
      tier: declared
      url: /providers/vimeo/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - DonorPerfect
      band: minimal
      in_catalog: true
      kin_score: 6.8
      mcp:
        status: unknown
      name: CauseVid
      slug: causevid
      sources:
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Fundraising
      - Marketing
      - Non-Profit
      - Video
      tier: declared
      url: /providers/causevid/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Bloomerang
      - DonorPerfect
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: declared
      url: /providers/google-analytics/
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Bloomerang
      - Givebutter
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: declared
      url: /providers/google-sheets/
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - Little Green Light
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://github.com/Airtable/airtable-mcp-cli
        status: verified
      name: Airtable
      slug: airtable
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Application
      - Collaboration
      - Data
      - Database
      tier: declared
      url: /providers/airtable/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Little Green Light
      band: emerging
      in_catalog: true
      kin_score: 19.5
      mcp:
        status: none
      name: Fundraising Report Card
      slug: fundraising-report-card
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Company
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/fundraising-report-card/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - DonorPerfect
      band: minimal
      in_catalog: true
      kin_score: 2.2
      mcp:
        status: unknown
      name: Ravela Insights
      slug: ravela
      sources:
      - https://www.donorperfect.com/integrations/
      status: profiled
      tags:
      - Branding
      - Company
      - Domain
      - Parking
      tier: declared
      url: /providers/ravela/
  - capability:
      attribution: Turbo EA
      id: BC-210.60
      key: bank-relationship-management
      name: Bank Relationship Management
      url: /capabilities/bank-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - Givebutter
      band: emerging
      in_catalog: true
      kin_score: 14.7
      mcp:
        status: none
      name: Celtic Bank
      slug: celtic-bank
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Commercial Lending
      - Company
      - Finance
      - SBA Loans
      tier: declared
      url: /providers/celtic-bank/
    - agent_band: null
      agent_readiness: null
      apps:
      - Givebutter
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Fifth Third Bank
      slug: fifth-third-bank
      sources:
      - https://givebutter.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 70.0
      apps:
      - Bloomerang
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 87.3
      mcp:
        source: https://www.canva.dev/docs/mcp/
        status: verified
      name: Canva
      slug: canva
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Application
      - Automation
      - Brand Management
      - Collaboration
      tier: declared
      url: /providers/canva/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - CiviCRM
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps Geocoding
      slug: google-maps
      sources:
      - https://github.com/civicrm/civicrm-core/tree/master/CRM/Utils/Geocode
      - https://givebutter.com/integrations
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
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.8
      apps:
      - Bloomerang
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify
      slug: shopify
      sources:
      - https://bloomerang.com/integrations/
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: declared
      url: /providers/shopify/
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Little Green Light
      band: strong
      in_catalog: true
      kin_score: 54.6
      mcp:
        source: https://developer.woocommerce.com/docs/features/mcp/
        status: verified
      name: WooCommerce
      slug: woocommerce
      sources:
      - https://www.littlegreenlight.com/integrations/
      status: profiled
      tags:
      - E-Commerce
      - Open Source
      - Order
      - WooCommerce
      tier: declared
      url: /providers/woocommerce/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Bloomerang
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Bloomerang
      - Givebutter
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://bloomerang.com/integrations/
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: declared
      url: /providers/zoom/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Givebutter
      band: strong
      in_catalog: true
      kin_score: 56.0
      mcp:
        status: none
      name: Giphy
      slug: giphy
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - GIFs
      - Media
      - Photography
      - Stickers
      tier: declared
      url: /providers/giphy/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - CiviCRM
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://github.com/civicrm/civicrm-core/tree/master/ext
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: observed
      url: /providers/google-recaptcha/
  - capability:
      attribution: API Evangelist extension
      id: AE-918
      key: AE-918
      name: Document Generation & Conversion
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: human-only
      agent_readiness: 0.7
      apps:
      - Givebutter
      band: emerging
      in_catalog: true
      kin_score: 20.8
      mcp:
        status: unknown
      name: Storyraise
      slug: storyraise
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Company
      - Donor Management
      - Fundraising
      - Non-Profit
      tier: declared
      url: /providers/storyraise/
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.8
      apps:
      - Neon CRM
      band: developing
      in_catalog: true
      kin_score: 47.7
      mcp:
        status: none
      name: TaxJar
      slug: taxjar
      sources:
      - https://www.neonone.com/integrations/
      status: profiled
      tags:
      - E-Commerce
      - Sales Tax
      - Tax Calculation
      - Tax Compliance
      tier: declared
      url: /providers/taxjar/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.10
      key: AE-170.50.10
      name: Online Communities
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Neon CRM
      band: emerging
      in_catalog: true
      kin_score: 14.2
      mcp:
        status: none
      name: Higher Logic
      slug: higher-logic
      sources:
      - https://www.neonone.com/integrations/
      status: profiled
      tags:
      - Associations
      - Customer Retention
      - Member Engagement
      - Online Community Software
      tier: declared
      url: /providers/higher-logic/
  - capability:
      attribution: Turbo EA
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.8
      apps:
      - Bloomerang
      band: exemplar
      in_catalog: true
      kin_score: 72.8
      mcp:
        status: none
      name: Hootsuite
      slug: hootsuite
      sources:
      - https://bloomerang.com/integrations/
      status: profiled
      tags:
      - Content Scheduling
      - Marketing
      - Social Media
      - Social Media Management
      tier: declared
      url: /providers/hootsuite/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: WhatsApp
      slug: whatsapp
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: declared
      url: /providers/whatsapp/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Claude
      slug: anthropic
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: declared
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Givebutter
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: ChatGPT
      slug: openai
      sources:
      - https://givebutter.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: declared
      url: /providers/openai/
  layer: agent
summary:
  coverage_pct: 94.8
  declared_only: 106
  distinct_providers: 116
  in_catalog: 110
  mcp:
    documented: 1
    none: 56
    unchecked: 6
    verified: 28
  mcp_verified: 28
  mean_kin_score: 42.5
  observed: 10
  queued: 6
  reference_apps: 6
title: 'Nonprofit CRM & Fundraising: application blueprint'
---
