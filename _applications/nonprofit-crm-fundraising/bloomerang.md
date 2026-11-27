---
app: Bloomerang
app_slug: bloomerang
app_url: https://bloomerang.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-300.10.20
  key: BC-300.10.20
  layer: domain
  name: Candidate Screening and Selection
  providers:
  - Verified First
  url: /capabilities/talent-acquisition-management/
  via_parent: Talent Acquisition Management
- attribution: API Evangelist extension
  id: AE-140.30.20
  key: AE-140.30.20
  layer: domain
  name: Digital & Mobile Wallets
  providers:
  - Apple Pay
  - Google Pay
  - Venmo
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: Turbo EA
  id: BC-4800.20
  key: donor-relationship-management
  layer: domain
  name: Donor Relationship Management
  providers:
  - Salesforce
  url: /capabilities/donor-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4110
  key: events-group-operations-management
  layer: domain
  name: Events & Group Operations Management
  providers:
  - Amilia
  url: /capabilities/events-group-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3260
  key: government-grants-funding-management
  layer: domain
  name: Government Grants & Funding Management
  providers:
  - GOOD Grants
  url: /capabilities/government-grants-funding-management/
  via_parent: null
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
  - Dataro
  - DonorSearch
  url: /capabilities/donor-relationship-management/
  via_parent: Donor Relationship Management
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: common
  name: Design & Creative Editing
  providers:
  - Canva
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Constant Contact
  - Emma
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
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - AddEvent
  - Gmail
  url: /capabilities/mailbox-calendar-sync/
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
- attribution: Turbo EA
  id: BC-400.60.40
  key: BC-400.60.40
  layer: common
  name: Social Media Management
  providers:
  - Hootsuite
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: common
  name: Social Networks & Community
  providers:
  - Facebook
  - Instagram
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: common
  name: Spreadsheets & No-Code Databases
  providers:
  - Google Sheets
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: common
  name: Video Calling
  providers:
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.10.10
  key: AE-170.10.10
  layer: common
  name: Video Hosting & Encoding
  providers:
  - ThankView
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
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
  declared: 29
  observed: 0
credits: []
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id001
      status: none
    slug: addevent
    status: profiled
    tags: &id002
    - Calendar
    - Integration
    - Marketing
    - Software-as-a-Service
    url: /providers/addevent/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 10.6
    band: thin
    in_catalog: true
    kin_score: 29.1
    mcp: &id003
      status: none
    slug: amilia
    status: profiled
    tags: &id004
    - Company
    - Membership
    - Recreation
    - Software
    url: /providers/amilia/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.4
    band: developing
    in_catalog: true
    kin_score: 43.0
    mcp: &id005
      status: none
    slug: apple-pay
    status: profiled
    tags: &id006
    - Apple
    - Contactless Payments
    - Digital Wallet
    - E-Commerce
    url: /providers/apple-pay/
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
  facts:
    agent_band: agent-native
    agent_readiness: 70.0
    band: exemplar
    in_catalog: true
    kin_score: 87.3
    mcp: &id007
      source: https://www.canva.dev/docs/mcp/
      status: verified
    slug: canva
    status: profiled
    tags: &id008
    - Application
    - Automation
    - Brand Management
    - Collaboration
    url: /providers/canva/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.4
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id009
      status: none
    slug: constant-contact
    status: profiled
    tags: &id010
    - Campaigns
    - Contacts
    - Email Marketing
    - Event
    url: /providers/constant-contact/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: dataro
    status: queued for profiling
    tags: &id012 []
    url: null
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
  facts:
    agent_band: agent-aware
    agent_readiness: 21.5
    band: thin
    in_catalog: true
    kin_score: 27.3
    mcp: &id015
      status: none
    slug: myemma
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - Automation
    - Email Marketing
    - SMS
    url: /providers/myemma/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id017
      status: none
    slug: facebook
    status: profiled
    tags: &id018
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 43.2
    band: exemplar
    in_catalog: true
    kin_score: 66.8
    mcp: &id019
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id020
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id021
      status: unknown
    slug: good-grants
    status: profiled
    tags: &id022
    - Company
    - Grants
    - Non-Profit
    - Software-as-a-Service
    url: /providers/good-grants/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id023
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id024
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 39.7
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id025
      status: none
    slug: google-pay
    status: profiled
    tags: &id026
    - Agentic Commerce
    - Checkout
    - Contactless Payments
    - Digital Wallet
    url: /providers/google-pay/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id027
      status: none
    slug: google-sheets
    status: profiled
    tags: &id028
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 48.8
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id029
      status: none
    slug: hootsuite
    status: profiled
    tags: &id030
    - Content Scheduling
    - Marketing
    - Social Media
    - Social Media Management
    url: /providers/hootsuite/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.6
    band: exemplar
    in_catalog: true
    kin_score: 67.8
    mcp: &id031
      status: none
    slug: instagram
    status: profiled
    tags: &id032
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id035
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id036
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id039
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id040
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id041
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id042
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id043
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id044
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.8
    mcp: &id049
      status: unknown
    slug: thankview
    status: profiled
    tags: &id050
    - Fundraising
    - Marketing
    - Non-Profit
    - Video
    url: /providers/thankview/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.8
    band: thin
    in_catalog: true
    kin_score: 29.8
    mcp: &id051
      status: none
    slug: venmo
    status: profiled
    tags: &id052
    - Company
    - Consumer
    - Fintech
    - Payments
    url: /providers/venmo/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 24.7
    mcp: &id053
      status: none
    slug: verified-first
    status: profiled
    tags: &id054
    - Background Checks
    - Company
    - Screening
    - Verification
    url: /providers/verified-first/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id057
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id058
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: common
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://bloomerang.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/nonprofit-crm-fundraising/bloomerang/
providers:
- agent_band: agent-aware
  agent_readiness: 26.8
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id001
  name: AddEvent
  slug: addevent
  status: profiled
  tags: *id002
  url: /providers/addevent/
- agent_band: agent-aware
  agent_readiness: 10.6
  band: thin
  in_catalog: true
  kin_score: 29.1
  mcp: *id003
  name: Amilia
  slug: amilia
  status: profiled
  tags: *id004
  url: /providers/amilia/
- agent_band: agent-ready
  agent_readiness: 30.4
  band: developing
  in_catalog: true
  kin_score: 43.0
  mcp: *id005
  name: Apple Pay
  slug: apple-pay
  status: profiled
  tags: *id006
  url: /providers/apple-pay/
- agent_band: agent-native
  agent_readiness: 70.0
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id007
  name: Canva
  slug: canva
  status: profiled
  tags: *id008
  url: /providers/canva/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id009
  name: Constant Contact
  slug: constant-contact
  status: profiled
  tags: *id010
  url: /providers/constant-contact/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: Dataro
  slug: dataro
  status: queued for profiling
  tags: *id012
  url: null
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
  agent_readiness: 21.5
  band: thin
  in_catalog: true
  kin_score: 27.3
  mcp: *id015
  name: Emma
  slug: myemma
  status: profiled
  tags: *id016
  url: /providers/myemma/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id017
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id018
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id019
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id020
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id021
  name: GOOD Grants
  slug: good-grants
  status: profiled
  tags: *id022
  url: /providers/good-grants/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id023
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id024
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 39.7
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id025
  name: Google Pay
  slug: google-pay
  status: profiled
  tags: *id026
  url: /providers/google-pay/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id027
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id028
  url: /providers/google-sheets/
- agent_band: agent-ready
  agent_readiness: 48.8
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id029
  name: Hootsuite
  slug: hootsuite
  status: profiled
  tags: *id030
  url: /providers/hootsuite/
- agent_band: agent-ready
  agent_readiness: 38.6
  band: exemplar
  in_catalog: true
  kin_score: 67.8
  mcp: *id031
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id032
  url: /providers/instagram/
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
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id035
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id036
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id037
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id038
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id039
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id040
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id041
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id042
  url: /providers/shopify/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id043
  name: Slack
  slug: slack
  status: profiled
  tags: *id044
  url: /providers/slack/
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
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.8
  mcp: *id049
  name: ThankView
  slug: thankview
  status: profiled
  tags: *id050
  url: /providers/thankview/
- agent_band: human-only
  agent_readiness: 3.8
  band: thin
  in_catalog: true
  kin_score: 29.8
  mcp: *id051
  name: Venmo
  slug: venmo
  status: profiled
  tags: *id052
  url: /providers/venmo/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 24.7
  mcp: *id053
  name: Verified First
  slug: verified-first
  status: profiled
  tags: *id054
  url: /providers/verified-first/
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
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id057
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id058
  url: /providers/zoom/
siblings:
- name: CiviCRM
  rows: 10
  url: /applications/nonprofit-crm-fundraising/civicrm/
- name: DonorPerfect
  rows: 27
  url: /applications/nonprofit-crm-fundraising/donorperfect/
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
title: 'Bloomerang: Nonprofit CRM & Fundraising reference app'
---
