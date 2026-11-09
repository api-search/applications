---
access: understanding
agent_layer:
- app: Lago
  finding: first-party MCP server (lago-agent-toolkit, Rust, 40 tools over the Lago billing API)
  source: https://github.com/getlago/lago-agent-toolkit
  tier: declared
- app: Chargebee
  finding: Chargebee MCP servers (docs lookup, data retrieval) for AI clients
  source: https://www.chargebee.com/docs/billing/2.0/ai-in-chargebee/chargebee-mcp
  tier: declared
- app: Polar
  finding: web client ships @modelcontextprotocol/sdk and @ai-sdk/mcp, plus @ai-sdk/openai/anthropic/google (BYO-LLM features)
  source: https://raw.githubusercontent.com/polarsource/polar/main/clients/apps/web/package.json
  tier: observed
- app: Paddle
  finding: '"Docs MCP" listed in developer navigation (docs-only MCP)'
  source: https://www.paddle.com/integrations
  tier: declared
apps:
- anchor: lago
  counts:
    declared: 10
    observed: 21
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
  - route: documentation
    url: https://docs.getlago.com/integrations/introduction
  - route: source code
    url: https://api.github.com/repos/getlago/lago-api/contents/app/services/integrations
  - route: source code
    url: https://api.github.com/repos/getlago/lago-api/contents/app/services/payment_providers
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Adyen
    provider: adyen
    says: ships the Adyen SDK or integration code
    source: https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: Amazon Kinesis
    provider: kinesis
    says: ships the Amazon Kinesis SDK or integration code
    source: https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    credit: null
    layer: domain
    name: Anrok
    provider: anrok
    says: ships the Anrok SDK or integration code
    source: https://api.github.com/repos/getlago/lago-api/contents/app/services/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    credit: null
    layer: domain
    name: Avalara
    provider: avalara
    says: ships the Avalara SDK or integration code
    source: https://api.github.com/repos/getlago/lago-api/contents/app/services/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Cashfree Payments
    provider: cashfree
    says: ships the Cashfree Payments SDK or integration code
    source: https://api.github.com/repos/getlago/lago-api/contents/app/services/payment_providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Datadog
    provider: datadog
    says: ships the Datadog SDK or integration code
    source: https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Flutterwave
    provider: flutterwave
    says: ships the Flutterwave SDK or integration code
    source: https://api.github.com/repos/getlago/lago-api/contents/app/services/payment_providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: GoCardless
    provider: gocardless
    says: ships the GoCardless SDK or integration code
    source: https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: ships the HubSpot SDK or integration code
    source: https://api.github.com/repos/getlago/lago-api/contents/app/services/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Entra ID
    provider: microsoft-entra
    says: ships the Microsoft Entra ID SDK or integration code
    source: https://api.github.com/repos/getlago/lago-api/contents/app/services/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: MoneyHash
    provider: moneyhash
    says: ships the MoneyHash SDK or integration code
    source: https://api.github.com/repos/getlago/lago-api/contents/app/services/payment_providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: NetSuite
    provider: netsuite
    says: ships the NetSuite SDK or integration code
    source: https://api.github.com/repos/getlago/lago-api/contents/app/services/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: New Relic
    provider: new-relic
    says: ships the New Relic SDK or integration code
    source: https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: common
    name: Okta
    provider: okta
    says: ships the Okta SDK or integration code
    source: https://api.github.com/repos/getlago/lago-api/contents/app/services/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: ships the Salesforce SDK or integration code
    source: https://api.github.com/repos/getlago/lago-api/contents/app/services/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Twilio Segment
    provider: segment
    says: ships the Twilio Segment SDK or integration code
    source: https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Xero
    provider: xero
    says: ships the Xero SDK or integration code
    source: https://api.github.com/repos/getlago/lago-api/contents/app/services/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610
      key: information-data-management
      name: Information & Data Management
      url: /capabilities/information-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Airbyte
    provider: airbyte
    says: lists Airbyte as an integration
    source: https://docs.getlago.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4270.70
      key: software-marketplace-listing-management
      name: Software Marketplace Listing Management
      url: /capabilities/software-marketplace-listing-management/
      via_parent: null
    credit: null
    layer: domain
    name: AWS Marketplace
    provider: amazon-web-services
    says: lists AWS Marketplace as an integration
    source: https://docs.getlago.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4270.70
      key: software-marketplace-listing-management
      name: Software Marketplace Listing Management
      url: /capabilities/software-marketplace-listing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Azure Marketplace
    provider: microsoft-azure
    says: lists Azure Marketplace as an integration
    source: https://docs.getlago.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4270.70
      key: software-marketplace-listing-management
      name: Software Marketplace Listing Management
      url: /capabilities/software-marketplace-listing-management/
      via_parent: null
    credit: null
    layer: domain
    name: GCP Marketplace
    provider: google-cloud-platform
    says: lists GCP Marketplace as an integration
    source: https://docs.getlago.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610
      key: information-data-management
      name: Information & Data Management
      url: /capabilities/information-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Hightouch
    provider: hightouch
    says: lists Hightouch as an integration
    source: https://docs.getlago.com/integrations/introduction
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
    name: n8n
    provider: n8n
    says: lists n8n as an integration
    source: https://docs.getlago.com/integrations/introduction
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.20
      key: AE-160.20
      name: Authorization for Apps
      url: /capabilities/authorization-for-apps/
      via_parent: null
    credit: null
    layer: common
    name: Oso Cloud
    provider: oso
    says: lists Oso Cloud as an integration
    source: https://docs.getlago.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610
      key: information-data-management
      name: Information & Data Management
      url: /capabilities/information-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Polytomic
    provider: polytomic
    says: lists Polytomic as an integration
    source: https://docs.getlago.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks
    provider: quickbooks
    says: lists QuickBooks as an integration
    source: https://docs.getlago.com/integrations/introduction
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
    source: https://docs.getlago.com/integrations/introduction
    tier: declared
  kind: self-hosted
  name: Lago
  page: /applications/subscription-billing/lago/
  slug: lago
  url: https://github.com/getlago/lago
- anchor: kill-bill
  counts:
    declared: 15
    observed: 0
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/killbill/killbill/master/pom.xml
  - route: documentation
    url: https://killbill.io/plugins/
  - route: source code
    url: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-1400.30
      key: fraud-detection-investigation-management
      name: Fraud Detection & Investigation Management
      url: /capabilities/fraud-detection-investigation-management/
      via_parent: null
    credit: null
    layer: common
    name: Accertify
    provider: accertify
    says: lists Accertify as an integration
    source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Adyen
    provider: adyen
    says: lists Adyen as an integration
    source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    credit: null
    layer: domain
    name: Avalara (AvaTax)
    provider: avalara
    says: lists Avalara (AvaTax) as an integration
    source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Braintree
    provider: braintree
    says: lists Braintree as an integration
    source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Chase (Orbital / Paymentech)
    provider: chase
    says: lists Chase (Orbital / Paymentech) as an integration
    source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: CyberSource
    provider: cybersource
    says: lists CyberSource as an integration
    source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Dwolla
    provider: dwolla
    says: lists Dwolla as an integration
    source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Forte
    provider: csg
    says: lists Forte as an integration
    source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: GoCardless
    provider: gocardless
    says: lists GoCardless as an integration
    source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    credit: null
    layer: domain
    name: Kintsugi
    provider: kintsugi
    says: lists Kintsugi as an integration
    source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Qualpay
    provider: qualpay
    says: lists Qualpay as an integration
    source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: SecureNet
    provider: securenet
    says: lists SecureNet as an integration
    source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    credit: null
    layer: domain
    name: Vertex (tax)
    provider: vertex
    says: lists Vertex (tax) as an integration
    source: https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
    tier: declared
  kind: self-hosted
  name: Kill Bill
  page: /applications/subscription-billing/kill-bill/
  slug: kill-bill
  url: https://github.com/killbill/killbill
- anchor: invoice-ninja
  counts:
    declared: 0
    observed: 34
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.invoiceninja.app/latest/
  - route: dependency manifest
    url: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
  - route: source code
    url: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: common
    name: Apple
    provider: apple
    says: ships the Apple SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Authorize.net
    provider: authorizenet
    says: ships the Authorize.net SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-240.70.20
      key: AE-240.70.20
      name: Crypto Payment Acceptance
      url: /capabilities/stablecoin-payments/
      via_parent: Stablecoin Payments
    credit: null
    layer: common
    name: Blockonomics
    provider: blockonomics
    says: ships the Blockonomics SDK or integration code
    source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Braintree
    provider: braintree
    says: ships the Braintree SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Brevo
    provider: brevo
    says: ships the Brevo SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-240.70.20
      key: AE-240.70.20
      name: Crypto Payment Acceptance
      url: /capabilities/stablecoin-payments/
      via_parent: Stablecoin Payments
    credit: null
    layer: common
    name: BTCPay Server
    provider: btcpay
    says: ships the BTCPay Server SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: CBA PowerBoard
    provider: cba-powerboard
    says: ships the CBA PowerBoard SDK or integration code
    source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Checkout.com
    provider: checkout-com
    says: ships the Checkout.com SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: CHIP (Chip In Asia)
    provider: chip-in-asia
    says: ships the CHIP (Chip In Asia) SDK or integration code
    source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: eWAY
    provider: eway
    says: ships the eWAY SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Forte
    provider: csg
    says: ships the Forte SDK or integration code
    source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: GoCardless
    provider: gocardless
    says: ships the GoCardless SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Helcim
    provider: helcim
    says: ships the Helcim SDK or integration code
    source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: LawPay
    provider: lawpay
    says: ships the LawPay SDK or integration code
    source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailgun
    provider: mailgun
    says: ships the Mailgun SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Entra ID
    provider: microsoft-entra
    says: ships the Microsoft Entra ID SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Graph
    provider: microsoft-graph
    says: ships the Microsoft Graph SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: common
    name: Mindee
    provider: mindee
    says: ships the Mindee SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Mollie
    provider: mollie
    says: ships the Mollie SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1300.50
      key: banking-channels-management
      name: Banking Channels Management
      url: /capabilities/banking-channels-management/
      via_parent: null
    credit: null
    layer: domain
    name: Nordigen (GoCardless Bank Account Data)
    provider: nordigen
    says: ships the Nordigen (GoCardless Bank Account Data) SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: PayFast
    provider: payfast
    says: ships the PayFast SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: PayTrace
    provider: paytrace
    says: ships the PayTrace SDK or integration code
    source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Postmark
    provider: postmark
    says: ships the Postmark SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    credit: null
    layer: common
    name: Pusher
    provider: pusher
    says: ships the Pusher SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks
    provider: quickbooks
    says: ships the QuickBooks SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Razorpay
    provider: razorpay
    says: ships the Razorpay SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Rotessa
    provider: rotessa
    says: ships the Rotessa SDK or integration code
    source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2510.40
      key: exception-and-alert-management
      name: Exception and Alert Management
      url: /capabilities/exception-and-alert-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Square
    provider: square
    says: ships the Square SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: WePay
    provider: wepay
    says: ships the WePay SDK or integration code
    source: https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
    tier: observed
  kind: self-hosted
  name: Invoice Ninja
  page: /applications/subscription-billing/invoice-ninja/
  slug: invoice-ninja
  url: https://github.com/invoiceninja/invoiceninja
- anchor: polar
  counts:
    declared: 0
    observed: 14
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/polarsource/polar/main/clients/apps/web/package.json
  - route: dependency manifest
    url: https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon Web Services
    provider: amazon-web-services
    says: ships the Amazon Web Services SDK or integration code
    source: https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: common
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://raw.githubusercontent.com/polarsource/polar/main/clients/apps/web/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Cloudflare Stream
    provider: cloudflare-stream
    says: ships the Cloudflare Stream SDK or integration code
    source: https://raw.githubusercontent.com/polarsource/polar/main/clients/apps/web/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Expo
    provider: expo
    says: ships the Expo SDK or integration code
    source: https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.10
      key: AE-230.40.10
      name: Web Scraping
      url: /capabilities/web-data/
      via_parent: Web Data
    credit: null
    layer: common
    name: Firecrawl
    provider: firecrawl
    says: ships the Firecrawl SDK or integration code
    source: https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4270
      key: developer-platform-api-ecosystem-management
      name: Developer Platform & API Ecosystem Management
      url: /capabilities/developer-platform-api-ecosystem-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Gemini
    provider: google-gemini
    says: ships the Google Gemini SDK or integration code
    source: https://raw.githubusercontent.com/polarsource/polar/main/clients/apps/web/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: common
    name: IPinfo
    provider: ipinfo
    says: ships the IPinfo SDK or integration code
    source: https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: common
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Plain
    provider: plain
    says: ships the Plain SDK or integration code
    source: https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: PostHog
    provider: posthog
    says: ships the PostHog SDK or integration code
    source: https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Pydantic Logfire
    provider: pydantic-ai
    says: ships the Pydantic Logfire SDK or integration code
    source: https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
    tier: observed
  kind: open-source-saas
  name: Polar
  page: /applications/subscription-billing/polar/
  slug: polar
  url: https://github.com/polarsource/polar
- anchor: chargebee
  counts:
    declared: 44
    observed: 0
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
    layer: domain
    name: Zoho CRM
    provider: zoho-crm
    says: lists Zoho CRM as an integration
    source: https://www.chargebee.com/integrations/
    tier: declared
  kind: commercial
  name: Chargebee
  page: /applications/subscription-billing/chargebee/
  slug: chargebee
  url: https://www.chargebee.com/
- anchor: recurly
  counts:
    declared: 28
    observed: 0
  evidence:
  - route: integrations page
    url: https://recurly.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Adyen
    provider: adyen
    says: lists Adyen as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Authorize.net
    provider: authorizenet
    says: lists Authorize.net as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    credit: null
    layer: domain
    name: Avalara
    provider: avalara
    says: lists Avalara as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: CardConnect
    provider: cardconnect
    says: lists CardConnect as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Chase
    provider: chase
    says: lists Chase as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Checkout.com
    provider: checkout-com
    says: lists Checkout.com as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Cybersource
    provider: cybersource
    says: lists Cybersource as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Ebanx
    provider: ebanx
    says: lists Ebanx as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1400.30
      key: fraud-detection-investigation-management
      name: Fraud Detection & Investigation Management
      url: /capabilities/fraud-detection-investigation-management/
      via_parent: null
    credit: null
    layer: common
    name: Equifax
    provider: equifax
    says: lists Equifax as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Fiserv
    provider: fiserv
    says: lists Fiserv as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: GoCardless
    provider: gocardless
    says: lists GoCardless as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4270.70
      key: software-marketplace-listing-management
      name: Software Marketplace Listing Management
      url: /capabilities/software-marketplace-listing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Cloud
    provider: google-cloud-platform
    says: lists Google Cloud as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Intuit QuickBooks
    provider: quickbooks
    says: lists Intuit QuickBooks as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: JPMorgan Chase
    provider: jp-morgan-chase
    says: lists JPMorgan Chase as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1400.30
      key: fraud-detection-investigation-management
      name: Fraud Detection & Investigation Management
      url: /capabilities/fraud-detection-investigation-management/
      via_parent: null
    credit: null
    layer: common
    name: Justt
    provider: justt
    says: lists Justt as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1400.30
      key: fraud-detection-investigation-management
      name: Fraud Detection & Investigation Management
      url: /capabilities/fraud-detection-investigation-management/
      via_parent: null
    credit: null
    layer: common
    name: Kount
    provider: kount
    says: lists Kount as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: MerchantE
    provider: merchante
    says: lists MerchantE as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Nuvei
    provider: nuvei
    says: lists Nuvei as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Oracle NetSuite
    provider: netsuite
    says: lists Oracle NetSuite as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250.40
      key: payment-collection-dunning
      name: Payment Collection & Dunning
      url: /capabilities/payment-collection-dunning/
      via_parent: null
    credit: null
    layer: domain
    name: ProsperStack
    provider: prosperstack
    says: lists ProsperStack as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.40
      key: cross-border-payment-management
      name: Cross-Border Payment Management
      url: /capabilities/cross-border-payment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Reach (withreach.com)
    provider: withreach
    says: lists Reach (withreach.com) as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Revolv3
    provider: revolv3
    says: lists Revolv3 as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250.40
      key: payment-collection-dunning
      name: Payment Collection & Dunning
      url: /capabilities/payment-collection-dunning/
      via_parent: null
    credit: null
    layer: domain
    name: Vindicia
    provider: vindicia
    says: lists Vindicia as an integration
    source: https://recurly.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Worldpay
    provider: worldpay
    says: lists Worldpay as an integration
    source: https://recurly.com/integrations/
    tier: declared
  kind: commercial
  name: Recurly
  page: /applications/subscription-billing/recurly/
  slug: recurly
  url: https://recurly.com/
- anchor: paddle
  counts:
    declared: 12
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.paddle.com/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4250.70
      key: subscription-revenue-analytics
      name: Subscription Revenue Analytics
      url: /capabilities/subscription-revenue-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Braintree
    provider: braintree
    says: lists Braintree as an integration
    source: https://www.paddle.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250.70
      key: subscription-revenue-analytics
      name: Subscription Revenue Analytics
      url: /capabilities/subscription-revenue-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Chargebee
    provider: chargebee
    says: lists Chargebee as an integration
    source: https://www.paddle.com/integrations
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
    name: Databox
    provider: databox
    says: lists Databox as an integration
    source: https://www.paddle.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://www.paddle.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Intercom
    provider: intercom
    says: lists Intercom as an integration
    source: https://www.paddle.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250.70
      key: subscription-revenue-analytics
      name: Subscription Revenue Analytics
      url: /capabilities/subscription-revenue-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Maxio
    provider: maxio
    says: lists Maxio as an integration
    source: https://www.paddle.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250.70
      key: subscription-revenue-analytics
      name: Subscription Revenue Analytics
      url: /capabilities/subscription-revenue-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Recharge
    provider: recharge-payments
    says: lists Recharge as an integration
    source: https://www.paddle.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250.70
      key: subscription-revenue-analytics
      name: Subscription Revenue Analytics
      url: /capabilities/subscription-revenue-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Recurly
    provider: recurly
    says: lists Recurly as an integration
    source: https://www.paddle.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: domain
    name: RevenueCat
    provider: revenuecat
    says: lists RevenueCat as an integration
    source: https://www.paddle.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250.70
      key: subscription-revenue-analytics
      name: Subscription Revenue Analytics
      url: /capabilities/subscription-revenue-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://www.paddle.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250.70
      key: subscription-revenue-analytics
      name: Subscription Revenue Analytics
      url: /capabilities/subscription-revenue-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Uscreen
    provider: uscreen
    says: lists Uscreen as an integration
    source: https://www.paddle.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250.70
      key: subscription-revenue-analytics
      name: Subscription Revenue Analytics
      url: /capabilities/subscription-revenue-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Zuora
    provider: zuora
    says: lists Zuora as an integration
    source: https://www.paddle.com/integrations
    tier: declared
  kind: commercial
  name: Paddle
  page: /applications/subscription-billing/paddle/
  slug: paddle
  url: https://www.paddle.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: subscription-billing
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Finance
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Selling products
  store: shopify-app-store
  url: https://apps.shopify.com/categories
- category: Finance
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Finance
  store: hubspot-marketplace
  url: https://ecosystem.hubspot.com/marketplace/apps
- category: Payment Processing
  store: zapier
  url: https://zapier.com/apps
name: Subscription Billing & Payments Ops
needs:
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: every billing system routes charges to one or more gateways
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  fit: exact
  layer: domain
  why: sales tax / VAT on recurring invoices
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: domain
  why: sync invoices and payments to accounting
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: sync accounts, subscriptions and quotes with CRM
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: SSO and sign-in for the billing console
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error and performance monitoring of the billing service
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  fit: exact
  layer: common
  why: object storage for invoice PDFs and exports
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: product/usage analytics feeding metering
- capability:
    attribution: Turbo EA
    id: BC-610
    key: information-data-management
    name: Information & Data Management
    url: /capabilities/information-data-management/
    via_parent: null
  fit: nearest
  layer: common
  why: usage ingestion and warehouse sync (ETL / reverse ETL)
- capability:
    attribution: Turbo EA
    id: BC-4270.70
    key: software-marketplace-listing-management
    name: Software Marketplace Listing Management
    url: /capabilities/software-marketplace-listing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: bill through cloud marketplaces
- capability:
    attribution: Turbo EA
    id: BC-1400.30
    key: fraud-detection-investigation-management
    name: Fraud Detection & Investigation Management
    url: /capabilities/fraud-detection-investigation-management/
    via_parent: null
  fit: exact
  layer: common
  why: fraud screening and chargeback disputes
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: billing context inside the help desk
- capability:
    attribution: Turbo EA
    id: BC-850.20
    key: external-communications-management
    name: External Communications Management
    url: /capabilities/external-communications-management/
    via_parent: null
  fit: nearest
  layer: common
  why: transactional email/SMS for invoices and dunning
- capability:
    attribution: Turbo EA
    id: BC-2510.40
    key: exception-and-alert-management
    name: Exception and Alert Management
    url: /capabilities/exception-and-alert-management/
    via_parent: null
  fit: nearest
  layer: common
  why: push / chat / realtime billing alerts
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: no-code workflow hooks on billing events
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  fit: nearest
  layer: common
  why: LLM features, receipt OCR, crawling
- capability:
    attribution: Turbo EA
    id: BC-4250.70
    key: subscription-revenue-analytics
    name: Subscription Revenue Analytics
    url: /capabilities/subscription-revenue-analytics/
    via_parent: null
  fit: exact
  layer: domain
  why: MRR/churn analytics across billing sources
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: email marketing sync of subscriber state
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: exact
  layer: domain
  why: mobile in-app subscription lifecycle
- capability:
    attribution: Turbo EA
    id: BC-4250.40
    key: payment-collection-dunning
    name: Payment Collection & Dunning
    url: /capabilities/payment-collection-dunning/
    via_parent: null
  fit: exact
  layer: domain
  why: failed-payment recovery and churn prevention
- capability:
    attribution: Turbo EA
    id: BC-1300.50
    key: banking-channels-management
    name: Banking Channels Management
    url: /capabilities/banking-channels-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: bank feeds for payment reconciliation
- capability:
    attribution: Turbo EA
    id: BC-4270
    key: developer-platform-api-ecosystem-management
    name: Developer Platform & API Ecosystem Management
    url: /capabilities/developer-platform-api-ecosystem-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: developer/repo identity (Polar funds OSS on GitHub)
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: common
  why: IP to country for tax and pricing localisation
- capability:
    attribution: Turbo EA
    id: BC-150.10.30
    key: BC-150.10.30
    name: Contract Execution Management
    url: /capabilities/contract-management/
    via_parent: Contract Management
  fit: exact
  layer: domain
  why: proposals / e-signature before subscription start
- capability:
    attribution: Turbo EA
    id: BC-2320.10
    key: sales-transaction-management
    name: Sales Transaction Management
    url: /capabilities/sales-transaction-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: storefront orders that create subscriptions
- capability:
    attribution: Turbo EA
    id: BC-2510.20
    key: shipment-tracking-management
    name: Shipment Tracking Management
    url: /capabilities/shipment-tracking-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: physical subscription box fulfilment
- capability:
    attribution: Turbo EA
    id: BC-1340.40
    key: cross-border-payment-management
    name: Cross-Border Payment Management
    url: /capabilities/cross-border-payment-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: merchant of record / cross-border acceptance
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: common
  why: BI dashboards on billing data
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'the category itself: plans, invoices, usage rating'
- capability:
    attribution: Turbo EA
    id: BC-2660.10
    key: usage-mediation-management
    name: Usage Mediation Management
    url: /capabilities/usage-mediation-management/
    via_parent: null
  fit: exact
  layer: domain
  why: metered/usage-based billing event pipeline
- capability:
    attribution: Turbo EA
    id: BC-4250.50
    key: subscription-revenue-recognition
    name: Subscription Revenue Recognition
    url: /capabilities/subscription-revenue-recognition/
    via_parent: null
  fit: exact
  layer: domain
  why: ASC 606 rev-rec on recurring contracts
- capability:
    attribution: Turbo EA
    id: BC-4330.50
    key: invoice-generation-management
    name: Invoice Generation Management
    url: /capabilities/invoice-generation-management/
    via_parent: null
  fit: exact
  layer: domain
  why: invoice rendering and delivery
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 41.2
      apps:
      - Chargebee
      - Invoice Ninja
      - Lago
      - Recurly
      band: strong
      in_catalog: true
      kin_score: 61.1
      mcp: &id005
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks
      slug: quickbooks
      sources:
      - https://docs.getlago.com/integrations/introduction
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      - https://recurly.com/integrations/
      status: profiled
      tags: &id006
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: observed
      url: /providers/quickbooks/
    - agent_band: agent-native
      agent_readiness: 61.3
      apps:
      - Chargebee
      - Lago
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://api.github.com/repos/getlago/lago-api/contents/app/services/integrations
      - https://www.chargebee.com/integrations/
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: observed
      url: /providers/xero/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Lago
      - Recurly
      band: emerging
      in_catalog: true
      kin_score: 12.5
      mcp:
        status: none
      name: NetSuite
      slug: netsuite
      sources:
      - https://api.github.com/repos/getlago/lago-api/contents/app/services/integrations
      - https://recurly.com/integrations/
      status: profiled
      tags:
      - Accounting
      - CRM
      - ERP
      - Finance
      tier: observed
      url: /providers/netsuite/
    - agent_band: agent-aware
      agent_readiness: 15.5
      apps:
      - Chargebee
      band: thin
      in_catalog: true
      kin_score: 26.3
      mcp:
        status: none
      name: Sage Intacct
      slug: sage-intacct
      sources:
      - https://www.chargebee.com/integrations/
      status: profiled
      tags:
      - Accounting
      - ERP
      - Financial Management
      - General Ledger
      tier: declared
      url: /providers/sage-intacct/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.7
      apps:
      - Chargebee
      - Lago
      - Paddle
      - Recurly
      band: exemplar
      in_catalog: true
      kin_score: 94.6
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://api.github.com/repos/getlago/lago-api/contents/app/services/integrations
      - https://recurly.com/integrations/
      - https://www.chargebee.com/integrations/
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: observed
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 54.7
      apps:
      - Chargebee
      - Lago
      band: exemplar
      in_catalog: true
      kin_score: 90.6
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://api.github.com/repos/getlago/lago-api/contents/app/services/integrations
      - https://www.chargebee.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: observed
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 44.2
      apps:
      - Chargebee
      band: exemplar
      in_catalog: true
      kin_score: 86.0
      mcp:
        status: none
      name: Zoho CRM
      slug: zoho-crm
      sources:
      - https://www.chargebee.com/integrations/
      status: profiled
      tags:
      - CRM
      - Lead Management
      - Marketing Automation
      - Sales
      tier: declared
      url: /providers/zoho-crm/
    - agent_band: agent-ready
      agent_readiness: 29.3
      apps:
      - Chargebee
      band: strong
      in_catalog: true
      kin_score: 55.5
      mcp:
        status: none
      name: Pipedrive
      slug: pipedrive
      sources:
      - https://www.chargebee.com/integrations/
      status: profiled
      tags:
      - CRM
      - Pipeline Management
      - Sales
      - Software-as-a-Service
      tier: declared
      url: /providers/pipedrive/
  - capability:
      attribution: Turbo EA
      id: BC-4250.70
      key: subscription-revenue-analytics
      name: Subscription Revenue Analytics
      url: /capabilities/subscription-revenue-analytics/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - Paddle
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp: &id001
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://www.paddle.com/integrations
      status: profiled
      tags: &id002
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: declared
      url: /providers/stripe/
    - agent_band: agent-native
      agent_readiness: 54.3
      apps:
      - Paddle
      band: exemplar
      in_catalog: true
      kin_score: 78.8
      mcp:
        status: none
      name: Recurly
      slug: recurly
      sources:
      - https://www.paddle.com/integrations
      status: profiled
      tags:
      - Billing
      - Payments
      - Recurring Revenue
      - Subscription
      tier: declared
      url: /providers/recurly/
    - agent_band: agent-ready
      agent_readiness: 54.1
      apps:
      - Paddle
      band: strong
      in_catalog: true
      kin_score: 62.9
      mcp:
        source: https://www.chargebee.com/docs/billing/2.0/ai-in-chargebee/chargebee-mcp
        status: verified
      name: Chargebee
      slug: chargebee
      sources:
      - https://www.paddle.com/integrations
      status: profiled
      tags:
      - Billing
      - Recurring Billing
      - Revenue
      - Subscription
      tier: declared
      url: /providers/chargebee/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Paddle
      band: developing
      in_catalog: true
      kin_score: 46.2
      mcp: &id003
        status: none
      name: Braintree
      slug: braintree
      sources:
      - https://www.paddle.com/integrations
      status: profiled
      tags: &id004
      - Mobile
      - Payments
      - Subscription
      - Transaction
      tier: declared
      url: /providers/braintree/
    - agent_band: agent-native
      agent_readiness: 57.8
      apps:
      - Paddle
      band: thin
      in_catalog: true
      kin_score: 37.2
      mcp:
        source: https://docs.zuora.com/en/zuora-platform/system-management/zuora-ai/zuora-mcp-server
        status: verified
      name: Zuora
      slug: zuora
      sources:
      - https://www.paddle.com/integrations
      status: profiled
      tags:
      - Billing
      - Finance
      - Payments
      - Subscription
      tier: declared
      url: /providers/zuora/
    - agent_band: agent-ready
      agent_readiness: 38.8
      apps:
      - Paddle
      band: thin
      in_catalog: true
      kin_score: 35.2
      mcp:
        source: https://help.uscreen.tv/en/articles/15643974-uscreen-mcp
        status: verified
      name: Uscreen
      slug: uscreen
      sources:
      - https://www.paddle.com/integrations
      status: profiled
      tags:
      - Company
      - Membership
      - Platform
      - Video
      tier: declared
      url: /providers/uscreen/
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Paddle
      band: thin
      in_catalog: true
      kin_score: 26.4
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=rechargeapps
        status: verified
      name: Recharge
      slug: recharge-payments
      sources:
      - https://www.paddle.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Payments
      - Recurring Billing
      - Subscription
      tier: declared
      url: /providers/recharge-payments/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Paddle
      band: emerging
      in_catalog: true
      kin_score: 24.6
      mcp:
        status: none
      name: Maxio
      slug: maxio
      sources:
      - https://www.paddle.com/integrations
      status: profiled
      tags:
      - Billing
      - Recurring Billing
      - Revenue Recognition
      - Subscription
      tier: declared
      url: /providers/maxio/
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.6
      apps:
      - Chargebee
      - Kill Bill
      - Lago
      - Recurly
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/avadev/mcp
        status: verified
      name: Avalara
      slug: avalara
      sources:
      - https://api.github.com/repos/getlago/lago-api/contents/app/services/integrations
      - https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
      - https://recurly.com/integrations/
      status: profiled
      tags:
      - Accounting
      - Avalara
      - Tax
      tier: observed
      url: /providers/avalara/
    - agent_band: agent-ready
      agent_readiness: 57.4
      apps:
      - Lago
      band: developing
      in_catalog: true
      kin_score: 51.2
      mcp:
        status: none
      name: Anrok
      slug: anrok
      sources:
      - https://api.github.com/repos/getlago/lago-api/contents/app/services/integrations
      status: profiled
      tags:
      - Sales Tax
      - Software-as-a-Service
      - Tax Compliance
      - VAT
      tier: observed
      url: /providers/anrok/
    - agent_band: agent-ready
      agent_readiness: 44.2
      apps:
      - Kill Bill
      band: thin
      in_catalog: true
      kin_score: 38.7
      mcp:
        status: none
      name: Kintsugi
      slug: kintsugi
      sources:
      - https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
      status: profiled
      tags:
      - Sales Tax
      - Tax Automation
      - Tax Compliance
      - VAT
      tier: declared
      url: /providers/kintsugi/
    - agent_band: agent-aware
      agent_readiness: 21.1
      apps:
      - Kill Bill
      band: emerging
      in_catalog: true
      kin_score: 23.1
      mcp:
        status: none
      name: Vertex (tax)
      slug: vertex
      sources:
      - https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
      status: profiled
      tags:
      - Automation
      - Company
      - Compliance
      - Tax
      tier: declared
      url: /providers/vertex/
  - capability:
      attribution: Turbo EA
      id: BC-4270.70
      key: software-marketplace-listing-management
      name: Software Marketplace Listing Management
      url: /capabilities/software-marketplace-listing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.7
      apps:
      - Lago
      - Recurly
      band: strong
      in_catalog: true
      kin_score: 64.8
      mcp:
        source: https://github.com/googleapis/mcp-toolbox
        status: verified
      name: GCP Marketplace
      slug: google-cloud-platform
      sources:
      - https://docs.getlago.com/integrations/introduction
      - https://recurly.com/integrations/
      status: profiled
      tags:
      - API Management
      - Cloud Computing
      - Infrastructure
      - Platform-as-a-Service
      tier: declared
      url: /providers/google-cloud-platform/
    - agent_band: agent-ready
      agent_readiness: 51.5
      apps:
      - Lago
      band: exemplar
      in_catalog: true
      kin_score: 78.4
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Marketplace
      slug: microsoft-azure
      sources:
      - https://docs.getlago.com/integrations/introduction
      status: profiled
      tags:
      - Cloud
      - Cloud Computing
      - Enterprise
      - Microsoft Azure
      tier: declared
      url: /providers/microsoft-azure/
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - Lago
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp: &id007
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS Marketplace
      slug: amazon-web-services
      sources:
      - https://docs.getlago.com/integrations/introduction
      status: profiled
      tags: &id008
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: declared
      url: /providers/amazon-web-services/
  - capability:
      attribution: Turbo EA
      id: BC-4250.40
      key: payment-collection-dunning
      name: Payment Collection & Dunning
      url: /capabilities/payment-collection-dunning/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Recurly
      band: developing
      in_catalog: true
      kin_score: 43.0
      mcp:
        source: https://docs.prosperstack.com/integrations/mcp-server
        status: verified
      name: ProsperStack
      slug: prosperstack
      sources:
      - https://recurly.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Company
      - Retention
      - Subscription
      tier: declared
      url: /providers/prosperstack/
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - Recurly
      band: thin
      in_catalog: true
      kin_score: 33.7
      mcp:
        status: none
      name: Vindicia
      slug: vindicia
      sources:
      - https://recurly.com/integrations/
      status: profiled
      tags:
      - Company
      - Fintech
      - Recurring Payments
      - Subscription Billing
      tier: declared
      url: /providers/vindicia/
  - capability:
      attribution: Turbo EA
      id: BC-1300.50
      key: banking-channels-management
      name: Banking Channels Management
      url: /capabilities/banking-channels-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Invoice Ninja
      band: minimal
      in_catalog: true
      kin_score: 5.1
      mcp:
        source: https://github.com/gocardless/gc-mcp
        status: verified
      name: Nordigen (GoCardless Bank Account Data)
      slug: nordigen
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Finance
      - Public APIs
      tier: observed
      url: /providers/nordigen/
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.5
      apps:
      - Chargebee
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        status: none
      name: GetAccept
      slug: getaccept
      sources:
      - https://www.chargebee.com/integrations/
      status: profiled
      tags:
      - Cloud
      - Company
      - E-Signature
      - Sales Enablement
      tier: declared
      url: /providers/getaccept/
  - capability:
      attribution: Turbo EA
      id: BC-1340.40
      key: cross-border-payment-management
      name: Cross-Border Payment Management
      url: /capabilities/cross-border-payment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.9
      apps:
      - Recurly
      band: developing
      in_catalog: true
      kin_score: 44.0
      mcp:
        status: none
      name: Reach (withreach.com)
      slug: withreach
      sources:
      - https://recurly.com/integrations/
      status: profiled
      tags:
      - Company
      - Compliance
      - Payments
      - Tax
      tier: declared
      url: /providers/withreach/
  - capability:
      attribution: Turbo EA
      id: BC-4270
      key: developer-platform-api-ecosystem-management
      name: Developer Platform & API Ecosystem Management
      url: /capabilities/developer-platform-api-ecosystem-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 63.4
      apps:
      - Polar
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Paddle
      band: thin
      in_catalog: true
      kin_score: 27.7
      mcp:
        source: https://www.revenuecat.com/docs/tools/mcp
        status: verified
      name: RevenueCat
      slug: revenuecat
      sources:
      - https://www.paddle.com/integrations
      status: profiled
      tags:
      - Billing
      - In-App Purchases
      - Mobile
      - Subscription
      tier: declared
      url: /providers/revenuecat/
  - capability:
      attribution: API Evangelist extension
      id: AE-929
      key: AE-929
      name: Multi-Carrier Shipping Platforms
      url: /capabilities/logistics-operations-management/
      via_parent: Logistics Operations Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Chargebee
      band: strong
      in_catalog: true
      kin_score: 56.7
      mcp:
        status: none
      name: ShipStation
      slug: shipstation
      sources:
      - https://www.chargebee.com/integrations/
      status: profiled
      tags:
      - E-Commerce
      - Labels
      - Logistics
      - ShipStation
      tier: declared
      url: /providers/shipstation/
  - capability:
      attribution: Turbo EA
      id: BC-2320.10
      key: sales-transaction-management
      name: Sales Transaction Management
      url: /capabilities/sales-transaction-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 60.5
      apps:
      - Chargebee
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
        status: verified
      name: BigCommerce
      slug: bigcommerce
      sources:
      - https://www.chargebee.com/integrations/
      status: profiled
      tags:
      - Catalog
      - E-Commerce
      - Order
      - Retail
      tier: declared
      url: /providers/bigcommerce/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - Chargebee
      - Invoice Ninja
      - Kill Bill
      - Lago
      - Polar
      - Recurly
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp: *id001
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      - https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 51.3
      apps:
      - Chargebee
      - Invoice Ninja
      - Kill Bill
      - Lago
      - Recurly
      band: developing
      in_catalog: true
      kin_score: 52.1
      mcp:
        source: https://developer.gocardless.com/mcp
        status: verified
      name: GoCardless
      slug: gocardless
      sources:
      - https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      - https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
      status: profiled
      tags:
      - Bank Debit
      - Direct Debit
      - Payments
      - Recurring Payments
      tier: observed
      url: /providers/gocardless/
    - agent_band: agent-native
      agent_readiness: 43.7
      apps:
      - Chargebee
      - Kill Bill
      - Lago
      - Recurly
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/Adyen/adyen-mcp
        status: verified
      name: Adyen
      slug: adyen
      sources:
      - https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
      - https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
      - https://recurly.com/integrations/
      status: profiled
      tags:
      - Agentic Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/adyen/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - Chargebee
      - Invoice Ninja
      - Kill Bill
      - Recurly
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
      - https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
      - https://recurly.com/integrations/
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Chargebee
      - Invoice Ninja
      - Kill Bill
      band: developing
      in_catalog: true
      kin_score: 46.2
      mcp: *id003
      name: Braintree
      slug: braintree
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      - https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/braintree/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Chargebee
      - Invoice Ninja
      - Recurly
      band: thin
      in_catalog: true
      kin_score: 36.4
      mcp:
        source: https://github.com/AuthorizeNet/authorize-net-mcp
        status: verified
      name: Authorize.net
      slug: authorizenet
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      - https://recurly.com/integrations/
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags:
      - Company
      - Credit Cards
      - Payment Gateway
      - Payments
      tier: observed
      url: /providers/authorizenet/
    - agent_band: agent-native
      agent_readiness: 47.5
      apps:
      - Chargebee
      - Invoice Ninja
      - Recurly
      band: thin
      in_catalog: true
      kin_score: 33.6
      mcp:
        source: https://github.com/checkout/checkout-mcp
        status: verified
      name: Checkout.com
      slug: checkout-com
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      - https://recurly.com/integrations/
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags:
      - Acquiring
      - Cards
      - Fintech
      - Payments
      tier: observed
      url: /providers/checkout-com/
    - agent_band: agent-ready
      agent_readiness: 33.3
      apps:
      - Chargebee
      - Kill Bill
      - Recurly
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        source: https://github.com/CyberSource/cybersource-developer-mcp
        status: verified
      name: CyberSource
      slug: cybersource
      sources:
      - https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
      - https://recurly.com/integrations/
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags:
      - Fraud Prevention
      - Payment Processing
      - Payments
      - Tokenization
      tier: declared
      url: /providers/cybersource/
    - agent_band: agent-aware
      agent_readiness: 26.3
      apps:
      - Chargebee
      - Kill Bill
      - Recurly
      band: thin
      in_catalog: true
      kin_score: 33.4
      mcp:
        status: none
      name: Chase (Orbital / Paymentech)
      slug: chase
      sources:
      - https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
      - https://recurly.com/integrations/
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags:
      - Account Aggregation
      - Banking
      - Consent
      - Credit Cards
      tier: declared
      url: /providers/chase/
    - agent_band: agent-native
      agent_readiness: 73.2
      apps:
      - Chargebee
      - Invoice Ninja
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://docs.mollie.com/docs/mcp-server
        status: verified
      name: Mollie
      slug: mollie
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags:
      - Company
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/mollie/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Chargebee
      - Invoice Ninja
      band: developing
      in_catalog: true
      kin_score: 52.4
      mcp:
        source: https://github.com/razorpay/razorpay-mcp-server
        status: verified
      name: Razorpay
      slug: razorpay
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags:
      - Fintech
      - India
      - Payment Gateway
      - Payments
      tier: observed
      url: /providers/razorpay/
    - agent_band: agent-aware
      agent_readiness: 5.4
      apps:
      - Chargebee
      - Invoice Ninja
      band: developing
      in_catalog: true
      kin_score: 49.0
      mcp:
        status: none
      name: eWAY
      slug: eway
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags:
      - Australia
      - Payment Gateway
      - Payment Processing
      - Payments
      tier: observed
      url: /providers/eway/
    - agent_band: agent-aware
      agent_readiness: 22.3
      apps:
      - Invoice Ninja
      - Kill Bill
      band: developing
      in_catalog: true
      kin_score: 46.0
      mcp:
        status: none
      name: Forte
      slug: csg
      sources:
      - https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
      - https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
      status: profiled
      tags:
      - Billing
      - Customer Engagement
      - Payments
      - Revenue Management
      tier: observed
      url: /providers/csg/
    - agent_band: agent-native
      agent_readiness: 45.6
      apps:
      - Chargebee
      - Recurly
      band: developing
      in_catalog: true
      kin_score: 50.7
      mcp:
        status: none
      name: Worldpay
      slug: worldpay
      sources:
      - https://recurly.com/integrations/
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags:
      - Payment Gateway
      - Payment Processing
      - Payments
      - Tokenization
      tier: declared
      url: /providers/worldpay/
    - agent_band: agent-aware
      agent_readiness: 19.9
      apps:
      - Chargebee
      - Recurly
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: Nuvei
      slug: nuvei
      sources:
      - https://recurly.com/integrations/
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags:
      - Acquiring
      - Payment Gateway
      - Payment Processing
      - Payments
      tier: declared
      url: /providers/nuvei/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Chargebee
      - Recurly
      band: minimal
      in_catalog: true
      kin_score: 8.0
      mcp:
        status: none
      name: BluePay
      slug: cardconnect
      sources:
      - https://recurly.com/integrations/
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/cardconnect/
    - agent_band: agent-native
      agent_readiness: 62.8
      apps:
      - Invoice Ninja
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://developer.squareup.com/docs/mcp
        status: verified
      name: Square
      slug: square
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Booking
      - Location
      - Restaurant
      - Square
      tier: observed
      url: /providers/square/
    - agent_band: agent-native
      agent_readiness: 41.3
      apps:
      - Invoice Ninja
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        status: none
      name: Helcim
      slug: helcim
      sources:
      - https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
      status: profiled
      tags:
      - Canada
      - Payment Gateway
      - Payment Processing
      - Payments
      tier: observed
      url: /providers/helcim/
    - agent_band: agent-ready
      agent_readiness: 33.4
      apps:
      - Lago
      band: developing
      in_catalog: true
      kin_score: 54.1
      mcp:
        status: none
      name: Flutterwave
      slug: flutterwave
      sources:
      - https://api.github.com/repos/getlago/lago-api/contents/app/services/payment_providers
      status: profiled
      tags:
      - Cards
      - Mobile Money
      - Payments
      - Payouts
      tier: observed
      url: /providers/flutterwave/
    - agent_band: agent-ready
      agent_readiness: 41.3
      apps:
      - Lago
      band: thin
      in_catalog: true
      kin_score: 38.8
      mcp:
        status: none
      name: MoneyHash
      slug: moneyhash
      sources:
      - https://api.github.com/repos/getlago/lago-api/contents/app/services/payment_providers
      status: profiled
      tags:
      - Company
      - Fintech
      - Orchestration
      - Payments
      tier: observed
      url: /providers/moneyhash/
    - agent_band: agent-aware
      agent_readiness: 23.6
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        status: none
      name: Rotessa
      slug: rotessa
      sources:
      - https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
      status: profiled
      tags:
      - ACH
      - Canada
      - Payments
      - Pre-Authorized Debit
      tier: observed
      url: /providers/rotessa/
    - agent_band: agent-native
      agent_readiness: 38.7
      apps:
      - Lago
      band: thin
      in_catalog: true
      kin_score: 36.4
      mcp:
        source: https://github.com/cashfree/cashfree-mcp
        status: verified
      name: Cashfree Payments
      slug: cashfree
      sources:
      - https://api.github.com/repos/getlago/lago-api/contents/app/services/payment_providers
      status: profiled
      tags:
      - India
      - Payments
      - Payouts
      - UPI
      tier: observed
      url: /providers/cashfree/
    - agent_band: agent-aware
      agent_readiness: 14.7
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 28.3
      mcp:
        status: none
      name: LawPay
      slug: lawpay
      sources:
      - https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
      status: profiled
      tags:
      - Company
      - Fintech
      - Legal Tech
      - Payments
      tier: observed
      url: /providers/lawpay/
    - agent_band: agent-aware
      agent_readiness: 7.9
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 28.2
      mcp:
        status: none
      name: CHIP (Chip In Asia)
      slug: chip-in-asia
      sources:
      - https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
      status: profiled
      tags:
      - Company
      - Finance
      - Payments
      - Small Business
      tier: observed
      url: /providers/chip-in-asia/
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 27.5
      mcp:
        status: none
      name: PayFast
      slug: payfast
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Payment Gateway
      - Payments
      - South Africa
      - Subscription
      tier: observed
      url: /providers/payfast/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Invoice Ninja
      band: emerging
      in_catalog: true
      kin_score: 14.5
      mcp:
        status: none
      name: PayTrace
      slug: paytrace
      sources:
      - https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
      status: profiled
      tags:
      - Company
      - Fintech
      - Merchant Services
      - Payments
      tier: observed
      url: /providers/paytrace/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Invoice Ninja
      band: minimal
      in_catalog: true
      kin_score: 8.0
      mcp:
        status: unknown
      name: CBA PowerBoard
      slug: cba-powerboard
      sources:
      - https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
      status: profiled
      tags:
      - Australia
      - Banking
      - Company
      - Fintech
      tier: observed
      url: /providers/cba-powerboard/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Invoice Ninja
      band: minimal
      in_catalog: true
      kin_score: 0.0
      mcp:
        status: none
      name: WePay
      slug: wepay
      sources:
      - https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
      status: profiled
      tags:
      - Marketplace
      - Payment Processing
      - Payments
      - Platform Payments
      tier: observed
      url: /providers/wepay/
    - agent_band: agent-native
      agent_readiness: 53.9
      apps:
      - Kill Bill
      band: exemplar
      in_catalog: true
      kin_score: 74.8
      mcp:
        source: https://github.com/Dwolla/dwolla-mcp
        status: verified
      name: Dwolla
      slug: dwolla
      sources:
      - https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
      status: profiled
      tags:
      - ACH
      - Bank Transfers
      - Fintech
      - Payments
      tier: declared
      url: /providers/dwolla/
    - agent_band: agent-native
      agent_readiness: 55.2
      apps:
      - Chargebee
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp:
        status: none
      name: Moneris
      slug: moneris
      sources:
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags:
      - Card Payments
      - Financial Services
      - Payment Processing
      - Payments
      tier: declared
      url: /providers/moneris/
    - agent_band: agent-native
      agent_readiness: 41.2
      apps:
      - Chargebee
      band: strong
      in_catalog: true
      kin_score: 61.1
      mcp: *id005
      name: QuickBooks Payments
      slug: quickbooks
      sources:
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags: *id006
      tier: declared
      url: /providers/quickbooks/
    - agent_band: agent-aware
      agent_readiness: 26.9
      apps:
      - Chargebee
      band: developing
      in_catalog: true
      kin_score: 53.8
      mcp:
        status: none
      name: Pin Payments
      slug: pin-payments
      sources:
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags:
      - Cards
      - Payments
      - Refunds
      - Subscription
      tier: declared
      url: /providers/pin-payments/
    - agent_band: agent-native
      agent_readiness: 42.4
      apps:
      - Recurly
      band: developing
      in_catalog: true
      kin_score: 52.3
      mcp:
        status: none
      name: JPMorgan Chase
      slug: jp-morgan-chase
      sources:
      - https://recurly.com/integrations/
      status: profiled
      tags:
      - Banking
      - Financial Services
      - Payments
      - Treasury
      tier: declared
      url: /providers/jp-morgan-chase/
    - agent_band: agent-native
      agent_readiness: 44.5
      apps:
      - Chargebee
      band: developing
      in_catalog: true
      kin_score: 45.8
      mcp:
        status: none
      name: NMI
      slug: nmi
      sources:
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags:
      - Payment Gateway
      - Payment Processing
      - Payments
      - Tokenization
      tier: declared
      url: /providers/nmi/
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - Kill Bill
      band: developing
      in_catalog: true
      kin_score: 42.4
      mcp:
        status: none
      name: Qualpay
      slug: qualpay
      sources:
      - https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
      status: profiled
      tags:
      - B2B Payments
      - Merchant Services
      - Payment Processing
      - Payments
      tier: declared
      url: /providers/qualpay/
    - agent_band: agent-aware
      agent_readiness: 23.4
      apps:
      - Recurly
      band: developing
      in_catalog: true
      kin_score: 41.0
      mcp:
        status: unknown
      name: Revolv3
      slug: revolv3
      sources:
      - https://recurly.com/integrations/
      status: profiled
      tags:
      - Company
      - Enterprise
      - Payments
      - Software-as-a-Service
      tier: declared
      url: /providers/revolv3/
    - agent_band: agent-aware
      agent_readiness: 25.0
      apps:
      - Recurly
      band: thin
      in_catalog: true
      kin_score: 36.6
      mcp:
        status: none
      name: Fiserv
      slug: fiserv
      sources:
      - https://recurly.com/integrations/
      status: profiled
      tags:
      - Banking
      - Finance
      - Payments
      - Wealth Management
      tier: declared
      url: /providers/fiserv/
    - agent_band: agent-ready
      agent_readiness: 32.1
      apps:
      - Recurly
      band: thin
      in_catalog: true
      kin_score: 34.7
      mcp:
        status: none
      name: Ebanx
      slug: ebanx
      sources:
      - https://recurly.com/integrations/
      status: profiled
      tags:
      - Foreign Exchange
      - Pay-In
      - Payments
      - Payouts
      tier: declared
      url: /providers/ebanx/
    - agent_band: agent-ready
      agent_readiness: 32.4
      apps:
      - Chargebee
      band: emerging
      in_catalog: true
      kin_score: 25.9
      mcp:
        status: none
      name: Elavon
      slug: elavon
      sources:
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags:
      - Company
      - Fintech
      - Merchant Services
      - Payments
      tier: declared
      url: /providers/elavon/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - Chargebee
      band: emerging
      in_catalog: true
      kin_score: 18.3
      mcp:
        status: none
      name: BlueSnap
      slug: bluesnap
      sources:
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags:
      - Company
      - Fintech
      - Global Payments
      - Payments
      tier: declared
      url: /providers/bluesnap/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Recurly
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        status: unknown
      name: MerchantE
      slug: merchante
      sources:
      - https://recurly.com/integrations/
      status: profiled
      tags:
      - Acquiring
      - Company
      - Fintech
      - Payments
      tier: declared
      url: /providers/merchante/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Chargebee
      band: emerging
      in_catalog: true
      kin_score: 11.1
      mcp:
        status: none
      name: Bambora
      slug: bambora
      sources:
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags:
      - Company
      - Europe
      - Fintech
      - Payments
      tier: declared
      url: /providers/bambora/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - Chargebee
      band: minimal
      in_catalog: true
      kin_score: 8.1
      mcp:
        status: none
      name: Ingenico
      slug: ingenico
      sources:
      - https://www.chargebee.com/payment-gateways/
      status: profiled
      tags:
      - Company
      - Fintech
      - Payments
      - Point-of-Sale
      tier: declared
      url: /providers/ingenico/
    - agent_band: null
      agent_readiness: null
      apps:
      - Chargebee
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Amazon Payments
      slug: amazon-pay
      sources:
      - https://www.chargebee.com/payment-gateways/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Kill Bill
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: SecureNet
      slug: securenet
      sources:
      - https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.7
      apps:
      - Chargebee
      - Paddle
      band: developing
      in_catalog: true
      kin_score: 52.5
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://www.chargebee.com/integrations/
      - https://www.paddle.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: declared
      url: /providers/intercom/
    - agent_band: agent-ready
      agent_readiness: 51.1
      apps:
      - Polar
      band: strong
      in_catalog: true
      kin_score: 61.2
      mcp:
        source: https://github.com/team-plain/cursor-plugin-mcp
        status: verified
      name: Plain
      slug: plain
      sources:
      - https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
      status: profiled
      tags:
      - Company
      - Customer Service
      - Help Desk
      - Support
      tier: observed
      url: /providers/plain/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Chargebee
      band: exemplar
      in_catalog: true
      kin_score: 72.8
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://www.chargebee.com/integrations/
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - Chargebee
      band: thin
      in_catalog: true
      kin_score: 32.2
      mcp:
        status: none
      name: Groove
      slug: groove
      sources:
      - https://www.chargebee.com/integrations/
      status: profiled
      tags:
      - Customer Service
      - Help Desk
      - Knowledge Base
      - Shared Inbox
      tier: declared
      url: /providers/groove/
    - agent_band: agent-ready
      agent_readiness: 29.8
      apps:
      - Chargebee
      band: thin
      in_catalog: true
      kin_score: 30.7
      mcp:
        status: none
      name: Freshdesk
      slug: freshdesk
      sources:
      - https://www.chargebee.com/integrations/
      status: profiled
      tags:
      - Application
      - Automation
      - Customer Service
      - Help Desk
      tier: declared
      url: /providers/freshdesk/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Invoice Ninja
      - Lago
      - Polar
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      - https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 49.6
      apps:
      - Lago
      band: exemplar
      in_catalog: true
      kin_score: 79.2
      mcp:
        source: https://github.com/datadog-labs/mcp-server
        status: verified
      name: Datadog
      slug: datadog
      sources:
      - https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
      status: profiled
      tags:
      - Analytics
      - Dashboards
      - Datadog
      - Visualization
      tier: observed
      url: /providers/datadog/
    - agent_band: agent-ready
      agent_readiness: 45.7
      apps:
      - Lago
      band: exemplar
      in_catalog: true
      kin_score: 76.5
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - Polar
      band: developing
      in_catalog: true
      kin_score: 54.1
      mcp:
        source: https://github.com/pydantic/mcp-run-python
        status: verified
      name: Pydantic Logfire
      slug: pydantic-ai
      sources:
      - https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - LLM
      - Python
      tier: observed
      url: /providers/pydantic-ai/
  - capability:
      attribution: Turbo EA
      id: BC-1400.30
      key: fraud-detection-investigation-management
      name: Fraud Detection & Investigation Management
      url: /capabilities/fraud-detection-investigation-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.9
      apps:
      - Recurly
      band: strong
      in_catalog: true
      kin_score: 57.7
      mcp:
        status: none
      name: Justt
      slug: justt
      sources:
      - https://recurly.com/integrations/
      status: profiled
      tags:
      - Chargebacks
      - Company
      - Disputes
      - Payments
      tier: declared
      url: /providers/justt/
    - agent_band: agent-aware
      agent_readiness: 7.9
      apps:
      - Recurly
      band: developing
      in_catalog: true
      kin_score: 45.8
      mcp:
        status: none
      name: Equifax
      slug: equifax
      sources:
      - https://recurly.com/integrations/
      status: profiled
      tags:
      - Credit
      - Credit History
      - Credit Reporting
      - Identity
      tier: declared
      url: /providers/equifax/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Recurly
      band: emerging
      in_catalog: true
      kin_score: 20.0
      mcp:
        status: none
      name: Kount
      slug: kount
      sources:
      - https://recurly.com/integrations/
      status: profiled
      tags:
      - Chargebacks
      - Fraud Prevention
      - Identity
      - Payments
      tier: declared
      url: /providers/kount/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Kill Bill
      band: minimal
      in_catalog: true
      kin_score: 6.0
      mcp:
        status: unknown
      name: Accertify
      slug: accertify
      sources:
      - https://raw.githubusercontent.com/killbill/killbill-cloud/master/kpm/lib/kpm/plugins_directory.yml
      status: profiled
      tags:
      - Company
      - Fraud Prevention
      - Payments
      - Risk Management
      tier: declared
      url: /providers/accertify/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.5
      apps:
      - Invoice Ninja
      - Lago
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        status: none
      name: Microsoft Entra ID
      slug: microsoft-entra
      sources:
      - https://api.github.com/repos/getlago/lago-api/contents/app/services/integrations
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 53.8
      apps:
      - Lago
      band: exemplar
      in_catalog: true
      kin_score: 78.0
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://api.github.com/repos/getlago/lago-api/contents/app/services/integrations
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: observed
      url: /providers/okta/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Invoice Ninja
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Apple
      slug: apple
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
  - capability:
      attribution: Turbo EA
      id: BC-610
      key: information-data-management
      name: Information & Data Management
      url: /capabilities/information-data-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Lago
      band: exemplar
      in_catalog: true
      kin_score: 77.5
      mcp:
        status: none
      name: Airbyte
      slug: airbyte
      sources:
      - https://docs.getlago.com/integrations/introduction
      status: profiled
      tags:
      - Data Integration
      - ELT
      - ETL
      - Open Source
      tier: declared
      url: /providers/airbyte/
    - agent_band: agent-ready
      agent_readiness: 63.8
      apps:
      - Lago
      band: exemplar
      in_catalog: true
      kin_score: 69.4
      mcp:
        source: https://hightouch.com/docs/ai-integrations/mcp
        status: documented
      name: Hightouch
      slug: hightouch
      sources:
      - https://docs.getlago.com/integrations/introduction
      status: profiled
      tags:
      - Audience Management
      - CDP
      - Data Activation
      - Reverse ETL
      tier: declared
      url: /providers/hightouch/
    - agent_band: agent-ready
      agent_readiness: 38.2
      apps:
      - Lago
      band: developing
      in_catalog: true
      kin_score: 46.1
      mcp:
        source: https://github.com/polytomic/mcp-connector
        status: verified
      name: Polytomic
      slug: polytomic
      sources:
      - https://docs.getlago.com/integrations/introduction
      status: profiled
      tags:
      - Data Integration
      - ELT
      - Reverse ETL
      - Unified API
      tier: declared
      url: /providers/polytomic/
    - agent_band: agent-aware
      agent_readiness: 7.5
      apps:
      - Chargebee
      band: thin
      in_catalog: true
      kin_score: 26.7
      mcp:
        status: none
      name: Stitch (Stitch Data ETL)
      slug: stitch-data
      sources:
      - https://www.chargebee.com/integrations/
      status: profiled
      tags:
      - Cloud Data
      - Data Integration
      - Data Pipeline
      - ETL
      tier: declared
      url: /providers/stitch-data/
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.3
      apps:
      - Lago
      band: exemplar
      in_catalog: true
      kin_score: 71.7
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Lago
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - Polar
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp: *id007
      name: Amazon Web Services
      slug: amazon-web-services
      sources:
      - https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/amazon-web-services/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Polar
      band: thin
      in_catalog: true
      kin_score: 37.3
      mcp:
        source: https://github.com/cloudflare/mcp-server-cloudflare
        status: verified
      name: Cloudflare Stream
      slug: cloudflare-stream
      sources:
      - https://raw.githubusercontent.com/polarsource/polar/main/clients/apps/web/package.json
      status: profiled
      tags:
      - Live Streaming
      - Media
      - Streaming
      - Video
      tier: observed
      url: /providers/cloudflare-stream/
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Polar
      band: exemplar
      in_catalog: true
      kin_score: 87.5
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://raw.githubusercontent.com/polarsource/polar/main/clients/apps/web/package.json
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 58.4
      apps:
      - Polar
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Polar
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://raw.githubusercontent.com/polarsource/polar/main/clients/apps/web/package.json
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 57.3
      apps:
      - Polar
      band: strong
      in_catalog: true
      kin_score: 57.7
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Lago
      band: developing
      in_catalog: true
      kin_score: 43.8
      mcp:
        status: none
      name: Twilio Segment
      slug: segment
      sources:
      - https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - Chargebee
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://www.chargebee.com/integrations/
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
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 57.2
      apps:
      - Invoice Ninja
      band: exemplar
      in_catalog: true
      kin_score: 82.2
      mcp:
        source: https://developers.brevo.com/docs/mcp-protocol
        status: verified
      name: Brevo
      slug: brevo
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Email Marketing
      - Marketing
      - Marketing Automation
      - Transactional Email
      tier: observed
      url: /providers/brevo/
    - agent_band: agent-ready
      agent_readiness: 41.7
      apps:
      - Invoice Ninja
      band: exemplar
      in_catalog: true
      kin_score: 71.3
      mcp:
        source: https://github.com/ActiveCampaign/postmark-mcp
        status: verified
      name: Postmark
      slug: postmark
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Deliverability
      - Email
      - Messaging
      - Transactional Email
      tier: observed
      url: /providers/postmark/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 32.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailgun/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.2
      apps:
      - Chargebee
      - Lago
      band: exemplar
      in_catalog: true
      kin_score: 72.0
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://docs.getlago.com/integrations/introduction
      - https://www.chargebee.com/integrations/
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 36.4
      apps:
      - Lago
      band: exemplar
      in_catalog: true
      kin_score: 71.3
      mcp:
        source: https://docs.n8n.io/advanced-ai/accessing-n8n-mcp-server/
        status: verified
      name: n8n
      slug: n8n
      sources:
      - https://docs.getlago.com/integrations/introduction
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Integration
      - Workflows
      tier: declared
      url: /providers/n8n/
  - capability:
      attribution: API Evangelist extension
      id: AE-240.70.20
      key: AE-240.70.20
      name: Crypto Payment Acceptance
      url: /capabilities/stablecoin-payments/
      via_parent: Stablecoin Payments
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.2
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 38.3
      mcp:
        status: none
      name: BTCPay Server
      slug: btcpay
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Bitcoin
      - Cryptocurrency
      - Lightning Network
      - Payments
      tier: observed
      url: /providers/btcpay/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Invoice Ninja
      band: emerging
      in_catalog: true
      kin_score: 14.7
      mcp:
        status: none
      name: Blockonomics
      slug: blockonomics
      sources:
      - https://api.github.com/repos/invoiceninja/invoiceninja/contents/app/PaymentDrivers?ref=v5-stable
      status: profiled
      tags:
      - Bitcoin
      - Company
      - Cryptocurrency
      - Payments
      tier: observed
      url: /providers/blockonomics/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - Chargebee
      - Recurly
      band: exemplar
      in_catalog: true
      kin_score: 78.3
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://recurly.com/integrations/
      - https://www.chargebee.com/integrations/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
  - capability:
      attribution: Turbo EA
      id: BC-2510.40
      key: exception-and-alert-management
      name: Exception and Alert Management
      url: /capabilities/exception-and-alert-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Chargebee
      - Invoice Ninja
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      - https://www.chargebee.com/integrations/
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - Paddle
      band: developing
      in_catalog: true
      kin_score: 46.1
      mcp:
        source: https://github.com/databox/databox-mcp
        status: verified
      name: Databox
      slug: databox
      sources:
      - https://www.paddle.com/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Company
      - Data Integration
      tier: declared
      url: /providers/databox/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.20
      key: AE-160.20
      name: Authorization for Apps
      url: /capabilities/authorization-for-apps/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Lago
      band: thin
      in_catalog: true
      kin_score: 35.7
      mcp:
        status: none
      name: Oso Cloud
      slug: oso
      sources:
      - https://docs.getlago.com/integrations/introduction
      status: profiled
      tags:
      - Access Control
      - Authorization
      - RBAC
      - ReBAC
      tier: declared
      url: /providers/oso/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - Polar
      band: strong
      in_catalog: true
      kin_score: 63.2
      mcp:
        source: https://github.com/ipinfo/mcp
        status: verified
      name: IPinfo
      slug: ipinfo
      sources:
      - https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
      status: profiled
      tags:
      - ASN
      - IP Geolocation
      - IP Intelligence
      - Privacy Detection
      tier: observed
      url: /providers/ipinfo/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.4
      apps:
      - Lago
      band: developing
      in_catalog: true
      kin_score: 49.3
      mcp:
        status: none
      name: Amazon Kinesis
      slug: kinesis
      sources:
      - https://raw.githubusercontent.com/getlago/lago-api/main/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Analytics
      - Apache Flink
      - Big Data
      tier: observed
      url: /providers/kinesis/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.0
      apps:
      - Invoice Ninja
      band: exemplar
      in_catalog: true
      kin_score: 70.1
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Graph
      slug: microsoft-graph
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Azure AD
      - Collaboration
      - Contacts
      - Microsoft Graph
      tier: observed
      url: /providers/microsoft-graph/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Invoice Ninja
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        status: none
      name: Mindee
      slug: mindee
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Document Parsing
      - Intelligent Document Processing
      - OCR
      tier: observed
      url: /providers/mindee/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.3
      apps:
      - Polar
      band: thin
      in_catalog: true
      kin_score: 31.4
      mcp:
        source: https://github.com/expo/expo-mcp
        status: verified
      name: Expo
      slug: expo
      sources:
      - https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
      status: profiled
      tags:
      - Build Automation
      - Mobile Development
      - Over-the-Air Updates
      - React Native
      tier: observed
      url: /providers/expo/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Invoice Ninja
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        status: none
      name: Pusher
      slug: pusher
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Pub/Sub
      - Push Notifications
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/pusher/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-native
      agent_readiness: 56.4
      apps:
      - Invoice Ninja
      band: exemplar
      in_catalog: true
      kin_score: 90.3
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://raw.githubusercontent.com/invoiceninja/invoiceninja/v5-stable/composer.json
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.10
      key: AE-230.40.10
      name: Web Scraping
      url: /capabilities/web-data/
      via_parent: Web Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - Polar
      band: developing
      in_catalog: true
      kin_score: 49.5
      mcp:
        source: https://docs.firecrawl.dev/mcp-server
        status: verified
      name: Firecrawl
      slug: firecrawl
      sources:
      - https://raw.githubusercontent.com/polarsource/polar/main/server/pyproject.toml
      status: profiled
      tags:
      - Crawling
      - Data Extraction
      - URLs
      - Web Scraping
      tier: observed
      url: /providers/firecrawl/
  layer: common
summary:
  coverage_pct: 98.4
  declared_only: 60
  distinct_providers: 122
  in_catalog: 120
  mcp:
    documented: 1
    none: 59
    unchecked: 2
    verified: 56
  mcp_verified: 56
  mean_kin_score: 50.1
  observed: 62
  queued: 2
  reference_apps: 7
title: 'Subscription Billing & Payments Ops: application blueprint'
---
