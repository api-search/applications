---
app: Paid Memberships Pro
app_slug: paid-memberships-pro
app_url: https://github.com/strangerstudios/paid-memberships-pro
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - Keap
  - Wp Fusion
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-220.20
  key: indirect-tax-management
  layer: domain
  name: Indirect Tax Management
  providers:
  - Avalara
  url: /capabilities/indirect-tax-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300.40
  key: learning-development-management
  layer: domain
  name: Learning & Development Management
  providers:
  - Learndash
  - Lifterlms
  url: /capabilities/learning-development-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.40.20
  key: AE-140.40.20
  layer: domain
  name: Memberships
  providers:
  - Unlock Protocol
  url: /capabilities/d2c-subscriptions/
  via_parent: D2C Subscriptions
- attribution: API Evangelist extension
  id: AE-170.50.10
  key: AE-170.50.10
  layer: domain
  name: Online Communities
  providers:
  - Buddyboss
  url: /capabilities/social-networks-community/
  via_parent: Social Networks & Community
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - 2Checkout (Verifone)
  - Authorizenet
  - Braintree
  - Cybersource
  - Paypal
  - Stripe
  - Ccbill
  - Payfast
  - Paystack
  - Square
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Google reCAPTCHA
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Post Affiliate Pro
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Aweber
  - Constant Contact
  - Kit (ConvertKit)
  - Mailchimp
  - Mailerlite
  - Mailpoet
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: common
  name: Hosted Storefronts
  providers:
  - Woocommerce
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
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
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
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
  id: membership-associations
  name: Membership & Association Management
  url: /applications/membership-associations/
counts:
  declared: 22
  observed: 7
credits: []
evidence:
- route: integrations page
  url: https://www.paidmembershipspro.com/add-ons/
- route: source code
  url: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
- route: source code
  url: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/includes/lib
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
    agent_band: agent-ready
    agent_readiness: 37.3
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id001
      status: none
    slug: verifone
    status: profiled
    tags: &id002
    - E-Commerce
    - Payments
    - Point-of-Sale
    - Terminal Management
    url: /providers/verifone/
  layer: domain
  name: 2Checkout (Verifone)
  provider: verifone
  says: ships the 2Checkout (Verifone) SDK or integration code
  source: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
  tier: observed
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
  name: Authorizenet
  provider: authorizenet
  says: ships the Authorizenet SDK or integration code
  source: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
  tier: observed
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
    agent_readiness: 53.6
    band: developing
    in_catalog: true
    kin_score: 44.7
    mcp: &id009
      status: none
    slug: braintree
    status: profiled
    tags: &id010
    - Mobile
    - Payments
    - Subscription
    - Transaction
    url: /providers/braintree/
  layer: domain
  name: Braintree
  provider: braintree
  says: ships the Braintree SDK or integration code
  source: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
  tier: observed
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
    mcp: &id017
      source: https://github.com/CyberSource/cybersource-developer-mcp
      status: verified
    slug: cybersource
    status: profiled
    tags: &id018
    - Fraud Prevention
    - Payment Processing
    - Payments
    - Tokenization
    url: /providers/cybersource/
  layer: domain
  name: Cybersource
  provider: cybersource
  says: ships the Cybersource SDK or integration code
  source: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id021
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id022
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: ships the Google reCAPTCHA SDK or integration code
  source: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/includes/lib
  tier: observed
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
    mcp: &id039
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id040
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: domain
  name: Paypal
  provider: paypal
  says: ships the Paypal SDK or integration code
  source: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
  tier: observed
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
    mcp: &id049
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id050
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.7
    band: exemplar
    in_catalog: true
    kin_score: 69.3
    mcp: &id005
      source: https://github.com/avadev/mcp
      status: verified
    slug: avalara
    status: profiled
    tags: &id006
    - Accounting
    - Avalara
    - Tax
    url: /providers/avalara/
  layer: domain
  name: Avalara
  provider: avalara
  says: lists Avalara as an integration
  source: https://www.paidmembershipspro.com/add-ons/
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
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id007
      source: https://github.com/aweber/aweber-mcp
      status: verified
    slug: aweber
    status: profiled
    tags: &id008
    - Email
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/aweber/
  layer: common
  name: Aweber
  provider: aweber
  says: lists Aweber as an integration
  source: https://www.paidmembershipspro.com/add-ons/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.10
    key: AE-170.50.10
    name: Online Communities
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 10.6
    band: thin
    in_catalog: true
    kin_score: 28.8
    mcp: &id011
      status: unchecked
    slug: buddyboss
    status: profiled
    tags: &id012
    - Community
    - Education
    - LMS
    - WordPress
    url: /providers/buddyboss/
  layer: domain
  name: Buddyboss
  provider: buddyboss
  says: lists Buddyboss as an integration
  source: https://www.paidmembershipspro.com/add-ons/
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
    agent_readiness: 23.8
    band: thin
    in_catalog: true
    kin_score: 27.3
    mcp: &id013
      status: unchecked
    slug: ccbill
    status: profiled
    tags: &id014
    - Billing
    - Merchant Services
    - Payments
    - Subscription
    url: /providers/ccbill/
  layer: domain
  name: Ccbill
  provider: ccbill
  says: lists Ccbill as an integration
  source: https://www.paidmembershipspro.com/add-ons/
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
    mcp: &id015
      status: none
    slug: constant-contact
    status: profiled
    tags: &id016
    - Campaigns
    - Contacts
    - Email Marketing
    - Event
    url: /providers/constant-contact/
  layer: common
  name: Constant Contact
  provider: constant-contact
  says: lists Constant Contact as an integration
  source: https://www.paidmembershipspro.com/add-ons/
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
  source: https://www.paidmembershipspro.com/add-ons/
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
    agent_readiness: 44.5
    band: strong
    in_catalog: true
    kin_score: 65.0
    mcp: &id023
      status: none
    slug: keap
    status: profiled
    tags: &id024
    - CRM
    - Marketing Automation
    - Sales
    - Small Business
    url: /providers/keap/
  layer: domain
  name: Keap
  provider: keap
  says: lists Keap as an integration
  source: https://www.paidmembershipspro.com/add-ons/
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
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 80.4
    mcp: &id025
      status: none
    slug: convertkit
    status: profiled
    tags: &id026
    - Automation
    - Creator Economy
    - Email Marketing
    - Subscribers
    url: /providers/convertkit/
  layer: common
  name: Kit (ConvertKit)
  provider: convertkit
  says: lists Kit (ConvertKit) as an integration
  source: https://www.paidmembershipspro.com/add-ons/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.40
    key: learning-development-management
    name: Learning & Development Management
    url: /capabilities/learning-development-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 26.8
    mcp: &id027
      status: unchecked
    slug: learndash
    status: profiled
    tags: &id028
    - E-Learning
    - Education
    - LMS
    - WordPress
    url: /providers/learndash/
  layer: domain
  name: Learndash
  provider: learndash
  says: lists Learndash as an integration
  source: https://www.paidmembershipspro.com/add-ons/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.40
    key: learning-development-management
    name: Learning & Development Management
    url: /capabilities/learning-development-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 32.5
    mcp: &id029
      status: unchecked
    slug: lifterlms
    status: profiled
    tags: &id030
    - Education Technology
    - Membership Training
    - Online Courses
    - WordPress Plugin
    url: /providers/lifterlms/
  layer: domain
  name: Lifterlms
  provider: lifterlms
  says: lists Lifterlms as an integration
  source: https://www.paidmembershipspro.com/add-ons/
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
    mcp: &id031
      status: none
    slug: mailchimp
    status: profiled
    tags: &id032
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://www.paidmembershipspro.com/add-ons/
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
    agent_readiness: 53.4
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id033
      source: https://developers.mailerlite.com/
      status: documented
    slug: mailerlite
    status: profiled
    tags: &id034
    - Automation
    - Email Marketing
    - Newsletters
    - Subscribers
    url: /providers/mailerlite/
  layer: common
  name: Mailerlite
  provider: mailerlite
  says: lists Mailerlite as an integration
  source: https://www.paidmembershipspro.com/add-ons/
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
    agent_readiness: 31.0
    band: emerging
    in_catalog: true
    kin_score: 24.0
    mcp: &id035
      status: unchecked
    slug: mailpoet
    status: profiled
    tags: &id036
    - Email Marketing
    - Newsletters
    - Open Source
    - WordPress
    url: /providers/mailpoet/
  layer: common
  name: Mailpoet
  provider: mailpoet
  says: lists Mailpoet as an integration
  source: https://www.paidmembershipspro.com/add-ons/
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
    agent_readiness: 28.8
    band: thin
    in_catalog: true
    kin_score: 26.6
    mcp: &id037
      status: none
    slug: payfast
    status: profiled
    tags: &id038
    - Payment Gateway
    - Payments
    - South Africa
    - Subscription
    url: /providers/payfast/
  layer: domain
  name: Payfast
  provider: payfast
  says: lists Payfast as an integration
  source: https://www.paidmembershipspro.com/add-ons/
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
    agent_readiness: 29.8
    band: strong
    in_catalog: true
    kin_score: 59.4
    mcp: &id041
      source: https://github.com/PaystackOSS/paystack-mcp-server
      status: verified
    slug: paystack
    status: profiled
    tags: &id042
    - Africa
    - Fintech
    - Payments
    - Recurring Billing
    url: /providers/paystack/
  layer: domain
  name: Paystack
  provider: paystack
  says: lists Paystack as an integration
  source: https://www.paidmembershipspro.com/add-ons/
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
    agent_readiness: 14.5
    band: thin
    in_catalog: true
    kin_score: 32.8
    mcp: &id043
      status: unchecked
    slug: post-affiliate-pro
    status: profiled
    tags: &id044
    - Affiliates
    - Marketing
    - Software-as-a-Service
    - Tracking
    url: /providers/post-affiliate-pro/
  layer: common
  name: Post Affiliate Pro
  provider: post-affiliate-pro
  says: lists Post Affiliate Pro as an integration
  source: https://www.paidmembershipspro.com/add-ons/
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
    mcp: &id045
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id046
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.paidmembershipspro.com/add-ons/
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
    mcp: &id047
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id048
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: domain
  name: Square
  provider: square
  says: lists Square as an integration
  source: https://www.paidmembershipspro.com/add-ons/
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
    agent_band: agent-ready
    agent_readiness: 30.4
    band: developing
    in_catalog: true
    kin_score: 49.2
    mcp: &id051
      status: none
    slug: unlock-protocol
    status: profiled
    tags: &id052
    - Blockchain
    - Membership
    - NFT
    - Subscription
    url: /providers/unlock-protocol/
  layer: domain
  name: Unlock Protocol
  provider: unlock-protocol
  says: lists Unlock Protocol as an integration
  source: https://www.paidmembershipspro.com/add-ons/
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
    mcp: &id053
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id054
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: common
  name: Woocommerce
  provider: woocommerce
  says: lists Woocommerce as an integration
  source: https://www.paidmembershipspro.com/add-ons/
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
    agent_readiness: 21.8
    band: thin
    in_catalog: true
    kin_score: 31.4
    mcp: &id055
      status: unchecked
    slug: wp-fusion
    status: profiled
    tags: &id056
    - CRM Integration
    - Marketing Automation
    - Open Source
    - WordPress
    url: /providers/wp-fusion/
  layer: domain
  name: Wp Fusion
  provider: wp-fusion
  says: lists Wp Fusion as an integration
  source: https://www.paidmembershipspro.com/add-ons/
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
    mcp: &id057
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id058
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.paidmembershipspro.com/add-ons/
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/membership-associations/paid-memberships-pro/
providers:
- agent_band: agent-ready
  agent_readiness: 37.3
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id001
  name: 2Checkout (Verifone)
  slug: verifone
  status: profiled
  tags: *id002
  url: /providers/verifone/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id003
  name: Authorizenet
  slug: authorizenet
  status: profiled
  tags: *id004
  url: /providers/authorizenet/
- agent_band: agent-ready
  agent_readiness: 44.7
  band: exemplar
  in_catalog: true
  kin_score: 69.3
  mcp: *id005
  name: Avalara
  slug: avalara
  status: profiled
  tags: *id006
  url: /providers/avalara/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id007
  name: Aweber
  slug: aweber
  status: profiled
  tags: *id008
  url: /providers/aweber/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: developing
  in_catalog: true
  kin_score: 44.7
  mcp: *id009
  name: Braintree
  slug: braintree
  status: profiled
  tags: *id010
  url: /providers/braintree/
- agent_band: agent-aware
  agent_readiness: 10.6
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id011
  name: Buddyboss
  slug: buddyboss
  status: profiled
  tags: *id012
  url: /providers/buddyboss/
- agent_band: agent-aware
  agent_readiness: 23.8
  band: thin
  in_catalog: true
  kin_score: 27.3
  mcp: *id013
  name: Ccbill
  slug: ccbill
  status: profiled
  tags: *id014
  url: /providers/ccbill/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id015
  name: Constant Contact
  slug: constant-contact
  status: profiled
  tags: *id016
  url: /providers/constant-contact/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: thin
  in_catalog: true
  kin_score: 32.5
  mcp: *id017
  name: Cybersource
  slug: cybersource
  status: profiled
  tags: *id018
  url: /providers/cybersource/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id019
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id020
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id021
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id022
  url: /providers/google-recaptcha/
- agent_band: agent-ready
  agent_readiness: 44.5
  band: strong
  in_catalog: true
  kin_score: 65.0
  mcp: *id023
  name: Keap
  slug: keap
  status: profiled
  tags: *id024
  url: /providers/keap/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 80.4
  mcp: *id025
  name: Kit (ConvertKit)
  slug: convertkit
  status: profiled
  tags: *id026
  url: /providers/convertkit/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 26.8
  mcp: *id027
  name: Learndash
  slug: learndash
  status: profiled
  tags: *id028
  url: /providers/learndash/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 32.5
  mcp: *id029
  name: Lifterlms
  slug: lifterlms
  status: profiled
  tags: *id030
  url: /providers/lifterlms/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id031
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id032
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id033
  name: Mailerlite
  slug: mailerlite
  status: profiled
  tags: *id034
  url: /providers/mailerlite/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: emerging
  in_catalog: true
  kin_score: 24.0
  mcp: *id035
  name: Mailpoet
  slug: mailpoet
  status: profiled
  tags: *id036
  url: /providers/mailpoet/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: thin
  in_catalog: true
  kin_score: 26.6
  mcp: *id037
  name: Payfast
  slug: payfast
  status: profiled
  tags: *id038
  url: /providers/payfast/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id039
  name: Paypal
  slug: paypal
  status: profiled
  tags: *id040
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 29.8
  band: strong
  in_catalog: true
  kin_score: 59.4
  mcp: *id041
  name: Paystack
  slug: paystack
  status: profiled
  tags: *id042
  url: /providers/paystack/
- agent_band: agent-aware
  agent_readiness: 14.5
  band: thin
  in_catalog: true
  kin_score: 32.8
  mcp: *id043
  name: Post Affiliate Pro
  slug: post-affiliate-pro
  status: profiled
  tags: *id044
  url: /providers/post-affiliate-pro/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id045
  name: Slack
  slug: slack
  status: profiled
  tags: *id046
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 61.5
  band: exemplar
  in_catalog: true
  kin_score: 78.2
  mcp: *id047
  name: Square
  slug: square
  status: profiled
  tags: *id048
  url: /providers/square/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id049
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id050
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 30.4
  band: developing
  in_catalog: true
  kin_score: 49.2
  mcp: *id051
  name: Unlock Protocol
  slug: unlock-protocol
  status: profiled
  tags: *id052
  url: /providers/unlock-protocol/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id053
  name: Woocommerce
  slug: woocommerce
  status: profiled
  tags: *id054
  url: /providers/woocommerce/
- agent_band: agent-aware
  agent_readiness: 21.8
  band: thin
  in_catalog: true
  kin_score: 31.4
  mcp: *id055
  name: Wp Fusion
  slug: wp-fusion
  status: profiled
  tags: *id056
  url: /providers/wp-fusion/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id057
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id058
  url: /providers/zapier/
siblings:
- name: Dolibarr (Members module)
  rows: 10
  url: /applications/membership-associations/dolibarr-members-module/
- name: Galette
  rows: 4
  url: /applications/membership-associations/galette/
- name: Glue Up
  rows: 14
  url: /applications/membership-associations/glue-up/
- name: Novi AMS
  rows: 46
  url: /applications/membership-associations/novi-ams/
- name: WildApricot
  rows: 8
  url: /applications/membership-associations/wildapricot/
sitemap: true
title: 'Paid Memberships Pro: Membership & Association Management reference app'
---
