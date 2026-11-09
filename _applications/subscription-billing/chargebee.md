---
app: Chargebee
app_slug: chargebee
app_url: https://www.chargebee.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-150.10.30
  key: BC-150.10.30
  layer: domain
  name: Contract Execution Management
  providers:
  - GetAccept
  url: /capabilities/contract-management/
  via_parent: Contract Management
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Pipedrive
  - Salesforce
  - Zoho CRM
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - QuickBooks
  - Sage Intacct
  - Xero
  url: /capabilities/general-ledger-management/
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
- attribution: API Evangelist extension
  id: AE-929
  key: AE-929
  layer: domain
  name: Multi-Carrier Shipping Platforms
  providers:
  - ShipStation
  url: /capabilities/logistics-operations-management/
  via_parent: Logistics Operations Management
- attribution: Turbo EA
  id: BC-2320.10
  key: sales-transaction-management
  layer: domain
  name: Sales Transaction Management
  providers:
  - BigCommerce
  url: /capabilities/sales-transaction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Freshdesk
  - Groove
  - Intercom
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Mailchimp
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2510.40
  key: exception-and-alert-management
  layer: common
  name: Exception and Alert Management
  providers:
  - Slack
  url: /capabilities/exception-and-alert-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-610
  key: information-data-management
  layer: common
  name: Information & Data Management
  providers:
  - Stitch (Stitch Data ETL)
  url: /capabilities/information-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Adyen
  - Amazon Payments
  - Authorize.Net
  - Bambora
  - BluePay
  - BlueSnap
  - Braintree
  - Checkout.com
  - CyberSource
  - Elavon
  - eWay
  - GoCardless
  - Ingenico
  - Mollie
  - Moneris
  - NMI
  - Nuvei
  - Orbital (Chase Paymentech)
  - PayPal
  - Pin Payments
  - QuickBooks Payments
  - Razorpay
  - Stripe
  - Worldpay
  url: /capabilities/payment-processing-management/
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
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: subscription-billing
  name: Subscription Billing & Payments Ops
  url: /applications/subscription-billing/
counts:
  declared: 44
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.chargebee.com/integrations/
- route: integrations page
  url: https://www.chargebee.com/payment-gateways/
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
    agent_band: agent-native
    agent_readiness: 43.7
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id002
      source: https://github.com/Adyen/adyen-mcp
      status: verified
    slug: adyen
    status: profiled
    tags: &id003
    - Agentic Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/adyen/
  layer: common
  name: Adyen
  provider: adyen
  says: lists Adyen as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id004
      status: unchecked
    slug: amazon-pay
    status: queued for profiling
    tags: &id005 []
    url: null
  layer: common
  name: Amazon Payments
  provider: amazon-pay
  says: lists Amazon Payments as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 36.4
    mcp: &id006
      source: https://github.com/AuthorizeNet/authorize-net-mcp
      status: verified
    slug: authorizenet
    status: profiled
    tags: &id007
    - Company
    - Credit Cards
    - Payment Gateway
    - Payments
    url: /providers/authorizenet/
  layer: common
  name: Authorize.Net
  provider: authorizenet
  says: lists Authorize.Net as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_band: agent-ready
    agent_readiness: 44.6
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id008
      source: https://github.com/avadev/mcp
      status: verified
    slug: avalara
    status: profiled
    tags: &id009
    - Accounting
    - Avalara
    - Tax
    url: /providers/avalara/
  layer: domain
  name: Avalara
  provider: avalara
  says: lists Avalara as an integration
  source: https://www.chargebee.com/integrations/
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
    kin_score: 11.1
    mcp: &id010
      status: none
    slug: bambora
    status: profiled
    tags: &id011
    - Company
    - Europe
    - Fintech
    - Payments
    url: /providers/bambora/
  layer: common
  name: Bambora
  provider: bambora
  says: lists Bambora as an integration
  source: https://www.chargebee.com/payment-gateways/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320.10
    key: sales-transaction-management
    name: Sales Transaction Management
    url: /capabilities/sales-transaction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 60.5
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id012
      source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
      status: verified
    slug: bigcommerce
    status: profiled
    tags: &id013
    - Catalog
    - E-Commerce
    - Order
    - Retail
    url: /providers/bigcommerce/
  layer: domain
  name: BigCommerce
  provider: bigcommerce
  says: lists BigCommerce as an integration
  source: https://www.chargebee.com/integrations/
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
    band: minimal
    in_catalog: true
    kin_score: 8.0
    mcp: &id014
      status: none
    slug: cardconnect
    status: profiled
    tags: &id015
    - Company
    url: /providers/cardconnect/
  layer: common
  name: BluePay
  provider: cardconnect
  says: lists BluePay as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_readiness: 14.4
    band: emerging
    in_catalog: true
    kin_score: 18.3
    mcp: &id016
      status: none
    slug: bluesnap
    status: profiled
    tags: &id017
    - Company
    - Fintech
    - Global Payments
    - Payments
    url: /providers/bluesnap/
  layer: common
  name: BlueSnap
  provider: bluesnap
  says: lists BlueSnap as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_readiness: 52.0
    band: developing
    in_catalog: true
    kin_score: 46.2
    mcp: &id018
      status: none
    slug: braintree
    status: profiled
    tags: &id019
    - Mobile
    - Payments
    - Subscription
    - Transaction
    url: /providers/braintree/
  layer: common
  name: Braintree
  provider: braintree
  says: lists Braintree as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_readiness: 47.5
    band: thin
    in_catalog: true
    kin_score: 33.6
    mcp: &id020
      source: https://github.com/checkout/checkout-mcp
      status: verified
    slug: checkout-com
    status: profiled
    tags: &id021
    - Acquiring
    - Cards
    - Fintech
    - Payments
    url: /providers/checkout-com/
  layer: common
  name: Checkout.com
  provider: checkout-com
  says: lists Checkout.com as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_readiness: 33.3
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id022
      source: https://github.com/CyberSource/cybersource-developer-mcp
      status: verified
    slug: cybersource
    status: profiled
    tags: &id023
    - Fraud Prevention
    - Payment Processing
    - Payments
    - Tokenization
    url: /providers/cybersource/
  layer: common
  name: CyberSource
  provider: cybersource
  says: lists CyberSource as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_readiness: 32.4
    band: emerging
    in_catalog: true
    kin_score: 25.9
    mcp: &id024
      status: none
    slug: elavon
    status: profiled
    tags: &id025
    - Company
    - Fintech
    - Merchant Services
    - Payments
    url: /providers/elavon/
  layer: common
  name: Elavon
  provider: elavon
  says: lists Elavon as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_readiness: 5.4
    band: developing
    in_catalog: true
    kin_score: 49.0
    mcp: &id026
      status: none
    slug: eway
    status: profiled
    tags: &id027
    - Australia
    - Payment Gateway
    - Payment Processing
    - Payments
    url: /providers/eway/
  layer: common
  name: eWay
  provider: eway
  says: lists eWay as an integration
  source: https://www.chargebee.com/payment-gateways/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.8
    band: thin
    in_catalog: true
    kin_score: 30.7
    mcp: &id028
      status: none
    slug: freshdesk
    status: profiled
    tags: &id029
    - Application
    - Automation
    - Customer Service
    - Help Desk
    url: /providers/freshdesk/
  layer: common
  name: Freshdesk
  provider: freshdesk
  says: lists Freshdesk as an integration
  source: https://www.chargebee.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150.10.30
    key: BC-150.10.30
    name: Contract Execution Management
    url: /capabilities/contract-management/
    via_parent: Contract Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.5
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id030
      status: none
    slug: getaccept
    status: profiled
    tags: &id031
    - Cloud
    - Company
    - E-Signature
    - Sales Enablement
    url: /providers/getaccept/
  layer: domain
  name: GetAccept
  provider: getaccept
  says: lists GetAccept as an integration
  source: https://www.chargebee.com/integrations/
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
    agent_readiness: 51.3
    band: developing
    in_catalog: true
    kin_score: 52.1
    mcp: &id032
      source: https://developer.gocardless.com/mcp
      status: verified
    slug: gocardless
    status: profiled
    tags: &id033
    - Bank Debit
    - Direct Debit
    - Payments
    - Recurring Payments
    url: /providers/gocardless/
  layer: common
  name: GoCardless
  provider: gocardless
  says: lists GoCardless as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    mcp: &id034
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id035
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://www.chargebee.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.1
    band: thin
    in_catalog: true
    kin_score: 32.2
    mcp: &id036
      status: none
    slug: groove
    status: profiled
    tags: &id037
    - Customer Service
    - Help Desk
    - Knowledge Base
    - Shared Inbox
    url: /providers/groove/
  layer: common
  name: Groove
  provider: groove
  says: lists Groove as an integration
  source: https://www.chargebee.com/integrations/
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
    mcp: &id038
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id039
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://www.chargebee.com/integrations/
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
    agent_readiness: 14.4
    band: minimal
    in_catalog: true
    kin_score: 8.1
    mcp: &id040
      status: none
    slug: ingenico
    status: profiled
    tags: &id041
    - Company
    - Fintech
    - Payments
    - Point-of-Sale
    url: /providers/ingenico/
  layer: common
  name: Ingenico
  provider: ingenico
  says: lists Ingenico as an integration
  source: https://www.chargebee.com/payment-gateways/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.7
    band: developing
    in_catalog: true
    kin_score: 52.5
    mcp: &id042
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id043
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: common
  name: Intercom
  provider: intercom
  says: lists Intercom as an integration
  source: https://www.chargebee.com/integrations/
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
    mcp: &id044
      status: none
    slug: mailchimp
    status: profiled
    tags: &id045
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://www.chargebee.com/integrations/
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
    agent_readiness: 73.2
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id046
      source: https://docs.mollie.com/docs/mcp-server
      status: verified
    slug: mollie
    status: profiled
    tags: &id047
    - Company
    - Financial Services
    - Fintech
    - Payments
    url: /providers/mollie/
  layer: common
  name: Mollie
  provider: mollie
  says: lists Mollie as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_readiness: 55.2
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id048
      status: none
    slug: moneris
    status: profiled
    tags: &id049
    - Card Payments
    - Financial Services
    - Payment Processing
    - Payments
    url: /providers/moneris/
  layer: common
  name: Moneris
  provider: moneris
  says: lists Moneris as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_readiness: 44.5
    band: developing
    in_catalog: true
    kin_score: 45.8
    mcp: &id050
      status: none
    slug: nmi
    status: profiled
    tags: &id051
    - Payment Gateway
    - Payment Processing
    - Payments
    - Tokenization
    url: /providers/nmi/
  layer: common
  name: NMI
  provider: nmi
  says: lists NMI as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_readiness: 19.9
    band: thin
    in_catalog: true
    kin_score: 26.5
    mcp: &id052
      status: none
    slug: nuvei
    status: profiled
    tags: &id053
    - Acquiring
    - Payment Gateway
    - Payment Processing
    - Payments
    url: /providers/nuvei/
  layer: common
  name: Nuvei
  provider: nuvei
  says: lists Nuvei as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_readiness: 26.3
    band: thin
    in_catalog: true
    kin_score: 33.4
    mcp: &id054
      status: none
    slug: chase
    status: profiled
    tags: &id055
    - Account Aggregation
    - Banking
    - Consent
    - Credit Cards
    url: /providers/chase/
  layer: common
  name: Orbital (Chase Paymentech)
  provider: chase
  says: lists Orbital (Chase Paymentech) as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    mcp: &id056
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id057
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_readiness: 26.9
    band: developing
    in_catalog: true
    kin_score: 53.8
    mcp: &id058
      status: none
    slug: pin-payments
    status: profiled
    tags: &id059
    - Cards
    - Payments
    - Refunds
    - Subscription
    url: /providers/pin-payments/
  layer: common
  name: Pin Payments
  provider: pin-payments
  says: lists Pin Payments as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_readiness: 29.3
    band: strong
    in_catalog: true
    kin_score: 55.5
    mcp: &id060
      status: none
    slug: pipedrive
    status: profiled
    tags: &id061
    - CRM
    - Pipeline Management
    - Sales
    - Software-as-a-Service
    url: /providers/pipedrive/
  layer: domain
  name: Pipedrive
  provider: pipedrive
  says: lists Pipedrive as an integration
  source: https://www.chargebee.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-native
    agent_readiness: 41.2
    band: strong
    in_catalog: true
    kin_score: 61.1
    mcp: &id062
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id063
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://www.chargebee.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: QuickBooks Payments
  provider: quickbooks
  says: lists QuickBooks Payments as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 52.4
    mcp: &id064
      source: https://github.com/razorpay/razorpay-mcp-server
      status: verified
    slug: razorpay
    status: profiled
    tags: &id065
    - Fintech
    - India
    - Payment Gateway
    - Payments
    url: /providers/razorpay/
  layer: common
  name: Razorpay
  provider: razorpay
  says: lists Razorpay as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    mcp: &id066
      status: none
    slug: sage-intacct
    status: profiled
    tags: &id067
    - Accounting
    - ERP
    - Financial Management
    - General Ledger
    url: /providers/sage-intacct/
  layer: domain
  name: Sage Intacct
  provider: sage-intacct
  says: lists Sage Intacct as an integration
  source: https://www.chargebee.com/integrations/
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
    mcp: &id068
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id069
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.chargebee.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-929
    key: AE-929
    name: Multi-Carrier Shipping Platforms
    url: /capabilities/logistics-operations-management/
    via_parent: Logistics Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: strong
    in_catalog: true
    kin_score: 56.7
    mcp: &id070
      status: none
    slug: shipstation
    status: profiled
    tags: &id071
    - E-Commerce
    - Labels
    - Logistics
    - ShipStation
    url: /providers/shipstation/
  layer: domain
  name: ShipStation
  provider: shipstation
  says: lists ShipStation as an integration
  source: https://www.chargebee.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2510.40
    key: exception-and-alert-management
    name: Exception and Alert Management
    url: /capabilities/exception-and-alert-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id072
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id073
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.chargebee.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610
    key: information-data-management
    name: Information & Data Management
    url: /capabilities/information-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 7.5
    band: thin
    in_catalog: true
    kin_score: 26.7
    mcp: &id074
      status: none
    slug: stitch-data
    status: profiled
    tags: &id075
    - Cloud Data
    - Data Integration
    - Data Pipeline
    - ETL
    url: /providers/stitch-data/
  layer: common
  name: Stitch (Stitch Data ETL)
  provider: stitch-data
  says: lists Stitch (Stitch Data ETL) as an integration
  source: https://www.chargebee.com/integrations/
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
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id076
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id077
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_readiness: 45.6
    band: developing
    in_catalog: true
    kin_score: 50.7
    mcp: &id078
      status: none
    slug: worldpay
    status: profiled
    tags: &id079
    - Payment Gateway
    - Payment Processing
    - Payments
    - Tokenization
    url: /providers/worldpay/
  layer: common
  name: Worldpay
  provider: worldpay
  says: lists Worldpay as an integration
  source: https://www.chargebee.com/payment-gateways/
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
    agent_readiness: 61.3
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id080
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id081
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: domain
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://www.chargebee.com/integrations/
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
    mcp: &id082
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id083
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.chargebee.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id084
      status: none
    slug: zendesk
    status: profiled
    tags: &id085
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: common
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://www.chargebee.com/integrations/
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
    agent_readiness: 44.2
    band: exemplar
    in_catalog: true
    kin_score: 86.0
    mcp: &id086
      status: none
    slug: zoho-crm
    status: profiled
    tags: &id087
    - CRM
    - Lead Management
    - Marketing Automation
    - Sales
    url: /providers/zoho-crm/
  layer: domain
  name: Zoho CRM
  provider: zoho-crm
  says: lists Zoho CRM as an integration
  source: https://www.chargebee.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/subscription-billing/chargebee/
providers:
- agent_band: agent-native
  agent_readiness: 43.7
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id002
  name: Adyen
  slug: adyen
  status: profiled
  tags: *id003
  url: /providers/adyen/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id004
  name: Amazon Payments
  slug: amazon-pay
  status: queued for profiling
  tags: *id005
  url: null
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 36.4
  mcp: *id006
  name: Authorize.Net
  slug: authorizenet
  status: profiled
  tags: *id007
  url: /providers/authorizenet/
- agent_band: agent-ready
  agent_readiness: 44.6
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id008
  name: Avalara
  slug: avalara
  status: profiled
  tags: *id009
  url: /providers/avalara/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.1
  mcp: *id010
  name: Bambora
  slug: bambora
  status: profiled
  tags: *id011
  url: /providers/bambora/
- agent_band: agent-ready
  agent_readiness: 60.5
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id012
  name: BigCommerce
  slug: bigcommerce
  status: profiled
  tags: *id013
  url: /providers/bigcommerce/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.0
  mcp: *id014
  name: BluePay
  slug: cardconnect
  status: profiled
  tags: *id015
  url: /providers/cardconnect/
- agent_band: agent-aware
  agent_readiness: 14.4
  band: emerging
  in_catalog: true
  kin_score: 18.3
  mcp: *id016
  name: BlueSnap
  slug: bluesnap
  status: profiled
  tags: *id017
  url: /providers/bluesnap/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: developing
  in_catalog: true
  kin_score: 46.2
  mcp: *id018
  name: Braintree
  slug: braintree
  status: profiled
  tags: *id019
  url: /providers/braintree/
- agent_band: agent-native
  agent_readiness: 47.5
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id020
  name: Checkout.com
  slug: checkout-com
  status: profiled
  tags: *id021
  url: /providers/checkout-com/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id022
  name: CyberSource
  slug: cybersource
  status: profiled
  tags: *id023
  url: /providers/cybersource/
- agent_band: agent-ready
  agent_readiness: 32.4
  band: emerging
  in_catalog: true
  kin_score: 25.9
  mcp: *id024
  name: Elavon
  slug: elavon
  status: profiled
  tags: *id025
  url: /providers/elavon/
- agent_band: agent-aware
  agent_readiness: 5.4
  band: developing
  in_catalog: true
  kin_score: 49.0
  mcp: *id026
  name: eWay
  slug: eway
  status: profiled
  tags: *id027
  url: /providers/eway/
- agent_band: agent-ready
  agent_readiness: 29.8
  band: thin
  in_catalog: true
  kin_score: 30.7
  mcp: *id028
  name: Freshdesk
  slug: freshdesk
  status: profiled
  tags: *id029
  url: /providers/freshdesk/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id030
  name: GetAccept
  slug: getaccept
  status: profiled
  tags: *id031
  url: /providers/getaccept/
- agent_band: agent-ready
  agent_readiness: 51.3
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id032
  name: GoCardless
  slug: gocardless
  status: profiled
  tags: *id033
  url: /providers/gocardless/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id034
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id035
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: thin
  in_catalog: true
  kin_score: 32.2
  mcp: *id036
  name: Groove
  slug: groove
  status: profiled
  tags: *id037
  url: /providers/groove/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id038
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id039
  url: /providers/hubspot/
- agent_band: agent-aware
  agent_readiness: 14.4
  band: minimal
  in_catalog: true
  kin_score: 8.1
  mcp: *id040
  name: Ingenico
  slug: ingenico
  status: profiled
  tags: *id041
  url: /providers/ingenico/
- agent_band: agent-ready
  agent_readiness: 31.7
  band: developing
  in_catalog: true
  kin_score: 52.5
  mcp: *id042
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id043
  url: /providers/intercom/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id044
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id045
  url: /providers/mailchimp/
- agent_band: agent-native
  agent_readiness: 73.2
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id046
  name: Mollie
  slug: mollie
  status: profiled
  tags: *id047
  url: /providers/mollie/
- agent_band: agent-native
  agent_readiness: 55.2
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id048
  name: Moneris
  slug: moneris
  status: profiled
  tags: *id049
  url: /providers/moneris/
- agent_band: agent-native
  agent_readiness: 44.5
  band: developing
  in_catalog: true
  kin_score: 45.8
  mcp: *id050
  name: NMI
  slug: nmi
  status: profiled
  tags: *id051
  url: /providers/nmi/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id052
  name: Nuvei
  slug: nuvei
  status: profiled
  tags: *id053
  url: /providers/nuvei/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: thin
  in_catalog: true
  kin_score: 33.4
  mcp: *id054
  name: Orbital (Chase Paymentech)
  slug: chase
  status: profiled
  tags: *id055
  url: /providers/chase/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id056
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id057
  url: /providers/paypal/
- agent_band: agent-aware
  agent_readiness: 26.9
  band: developing
  in_catalog: true
  kin_score: 53.8
  mcp: *id058
  name: Pin Payments
  slug: pin-payments
  status: profiled
  tags: *id059
  url: /providers/pin-payments/
- agent_band: agent-ready
  agent_readiness: 29.3
  band: strong
  in_catalog: true
  kin_score: 55.5
  mcp: *id060
  name: Pipedrive
  slug: pipedrive
  status: profiled
  tags: *id061
  url: /providers/pipedrive/
- agent_band: agent-native
  agent_readiness: 41.2
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id062
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id063
  url: /providers/quickbooks/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 52.4
  mcp: *id064
  name: Razorpay
  slug: razorpay
  status: profiled
  tags: *id065
  url: /providers/razorpay/
- agent_band: agent-aware
  agent_readiness: 15.5
  band: thin
  in_catalog: true
  kin_score: 26.3
  mcp: *id066
  name: Sage Intacct
  slug: sage-intacct
  status: profiled
  tags: *id067
  url: /providers/sage-intacct/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id068
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id069
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: strong
  in_catalog: true
  kin_score: 56.7
  mcp: *id070
  name: ShipStation
  slug: shipstation
  status: profiled
  tags: *id071
  url: /providers/shipstation/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id072
  name: Slack
  slug: slack
  status: profiled
  tags: *id073
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 7.5
  band: thin
  in_catalog: true
  kin_score: 26.7
  mcp: *id074
  name: Stitch (Stitch Data ETL)
  slug: stitch-data
  status: profiled
  tags: *id075
  url: /providers/stitch-data/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id076
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id077
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 45.6
  band: developing
  in_catalog: true
  kin_score: 50.7
  mcp: *id078
  name: Worldpay
  slug: worldpay
  status: profiled
  tags: *id079
  url: /providers/worldpay/
- agent_band: agent-native
  agent_readiness: 61.3
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id080
  name: Xero
  slug: xero
  status: profiled
  tags: *id081
  url: /providers/xero/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id082
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id083
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id084
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id085
  url: /providers/zendesk/
- agent_band: agent-ready
  agent_readiness: 44.2
  band: exemplar
  in_catalog: true
  kin_score: 86.0
  mcp: *id086
  name: Zoho CRM
  slug: zoho-crm
  status: profiled
  tags: *id087
  url: /providers/zoho-crm/
siblings:
- name: Invoice Ninja
  rows: 34
  url: /applications/subscription-billing/invoice-ninja/
- name: Kill Bill
  rows: 15
  url: /applications/subscription-billing/kill-bill/
- name: Lago
  rows: 31
  url: /applications/subscription-billing/lago/
- name: Paddle
  rows: 12
  url: /applications/subscription-billing/paddle/
- name: Polar
  rows: 14
  url: /applications/subscription-billing/polar/
- name: Recurly
  rows: 28
  url: /applications/subscription-billing/recurly/
sitemap: true
title: 'Chargebee: Subscription Billing & Payments Ops reference app'
---
