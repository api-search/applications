---
app: Lago
app_slug: lago
app_url: https://github.com/getlago/lago
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - NetSuite
  - Xero
  - QuickBooks
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-220.20
  key: indirect-tax-management
  layer: domain
  name: Indirect Tax Management
  providers:
  - Anrok
  - Avalara
  url: /capabilities/indirect-tax-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4270.70
  key: software-marketplace-listing-management
  layer: domain
  name: Software Marketplace Listing Management
  providers:
  - AWS Marketplace
  - Azure Marketplace
  - GCP Marketplace
  url: /capabilities/software-marketplace-listing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.20
  key: AE-160.20
  layer: common
  name: Authorization for Apps
  providers:
  - Oso Cloud
  url: /capabilities/authorization-for-apps/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - Microsoft Entra ID
  - Okta
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-610
  key: information-data-management
  layer: common
  name: Information & Data Management
  providers:
  - Airbyte
  - Hightouch
  - Polytomic
  url: /capabilities/information-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: common
  name: Integration and API Management
  providers:
  - Amazon Kinesis
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: Turbo EA
  id: BC-3710
  key: media-asset-management
  layer: common
  name: Media Asset Management
  providers:
  - Amazon S3
  - Google Cloud Storage
  url: /capabilities/media-asset-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Datadog
  - New Relic
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Adyen
  - Cashfree Payments
  - Flutterwave
  - GoCardless
  - MoneyHash
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Twilio Segment
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - n8n
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: subscription-billing
  name: Subscription Billing & Payments Ops
  url: /applications/subscription-billing/
counts:
  declared: 10
  observed: 21
credits: []
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
  facts:
    agent_band: agent-native
    agent_readiness: 42.8
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id001
      source: https://github.com/Adyen/adyen-mcp
      status: verified
    slug: adyen
    status: profiled
    tags: &id002
    - Agentic Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/adyen/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.6
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id005
      status: none
    slug: kinesis
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Analytics
    - Apache Flink
    - Big Data
    url: /providers/kinesis/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id007
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id008
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 61.7
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id009
      status: none
    slug: anrok
    status: profiled
    tags: &id010
    - Sales Tax
    - Software-as-a-Service
    - Tax Compliance
    - VAT
    url: /providers/anrok/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.7
    band: exemplar
    in_catalog: true
    kin_score: 69.3
    mcp: &id011
      source: https://github.com/avadev/mcp
      status: verified
    slug: avalara
    status: profiled
    tags: &id012
    - Accounting
    - Avalara
    - Tax
    url: /providers/avalara/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: thin
    in_catalog: true
    kin_score: 36.4
    mcp: &id017
      source: https://github.com/cashfree/cashfree-mcp
      status: verified
    slug: cashfree
    status: profiled
    tags: &id018
    - India
    - Payments
    - Payouts
    - UPI
    url: /providers/cashfree/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 48.6
    band: exemplar
    in_catalog: true
    kin_score: 80.0
    mcp: &id019
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id020
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.4
    band: developing
    in_catalog: true
    kin_score: 53.3
    mcp: &id021
      status: none
    slug: flutterwave
    status: profiled
    tags: &id022
    - Cards
    - Mobile Money
    - Payments
    - Payouts
    url: /providers/flutterwave/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.3
    band: developing
    in_catalog: true
    kin_score: 50.0
    mcp: &id025
      source: https://developer.gocardless.com/mcp
      status: verified
    slug: gocardless
    status: profiled
    tags: &id026
    - Bank Debit
    - Direct Debit
    - Payments
    - Recurring Payments
    url: /providers/gocardless/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id027
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id028
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id031
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id032
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id033
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id034
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.8
    band: developing
    in_catalog: true
    kin_score: 40.4
    mcp: &id035
      status: none
    slug: moneyhash
    status: profiled
    tags: &id036
    - Company
    - Fintech
    - Orchestration
    - Payments
    url: /providers/moneyhash/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.4
    mcp: &id039
      status: none
    slug: netsuite
    status: profiled
    tags: &id040
    - Accounting
    - CRM
    - ERP
    - Finance
    url: /providers/netsuite/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id041
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id042
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 47.1
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id043
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id044
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id051
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id052
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id053
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id054
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
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
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id055
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id056
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id057
      status: none
    slug: segment
    status: profiled
    tags: &id058
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
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
  facts:
    agent_band: agent-native
    agent_readiness: 60.0
    band: exemplar
    in_catalog: true
    kin_score: 87.1
    mcp: &id059
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id060
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.2
    band: exemplar
    in_catalog: true
    kin_score: 77.5
    mcp: &id003
      status: none
    slug: airbyte
    status: profiled
    tags: &id004
    - Data Integration
    - ELT
    - ETL
    - Open Source
    url: /providers/airbyte/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id013
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id014
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 45.0
    band: exemplar
    in_catalog: true
    kin_score: 76.0
    mcp: &id015
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure
    status: profiled
    tags: &id016
    - Cloud
    - Cloud Computing
    - Enterprise
    - Microsoft Azure
    url: /providers/microsoft-azure/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 67.5
    mcp: &id023
      source: https://github.com/googleapis/mcp-toolbox
      status: verified
    slug: google-cloud-platform
    status: profiled
    tags: &id024
    - API Management
    - Cloud Computing
    - Infrastructure
    - Platform-as-a-Service
    url: /providers/google-cloud-platform/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 62.8
    band: exemplar
    in_catalog: true
    kin_score: 66.9
    mcp: &id029
      source: https://hightouch.com/docs/ai-integrations/mcp
      status: documented
    slug: hightouch
    status: profiled
    tags: &id030
    - Audience Management
    - CDP
    - Data Activation
    - Reverse ETL
    url: /providers/hightouch/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.7
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id037
      source: https://docs.n8n.io/advanced-ai/accessing-n8n-mcp-server/
      status: verified
    slug: n8n
    status: profiled
    tags: &id038
    - Agents
    - Artificial Intelligence
    - Integration
    - Workflows
    url: /providers/n8n/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.8
    band: thin
    in_catalog: true
    kin_score: 34.8
    mcp: &id045
      status: none
    slug: oso
    status: profiled
    tags: &id046
    - Access Control
    - Authorization
    - RBAC
    - ReBAC
    url: /providers/oso/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.4
    band: developing
    in_catalog: true
    kin_score: 45.5
    mcp: &id047
      source: https://github.com/polytomic/mcp-connector
      status: verified
    slug: polytomic
    status: profiled
    tags: &id048
    - Data Integration
    - ELT
    - Reverse ETL
    - Unified API
    url: /providers/polytomic/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id049
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id050
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id061
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id062
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://docs.getlago.com/integrations/introduction
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/subscription-billing/lago/
providers:
- agent_band: agent-native
  agent_readiness: 42.8
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id001
  name: Adyen
  slug: adyen
  status: profiled
  tags: *id002
  url: /providers/adyen/
- agent_band: agent-ready
  agent_readiness: 44.2
  band: exemplar
  in_catalog: true
  kin_score: 77.5
  mcp: *id003
  name: Airbyte
  slug: airbyte
  status: profiled
  tags: *id004
  url: /providers/airbyte/
- agent_band: agent-ready
  agent_readiness: 44.6
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id005
  name: Amazon Kinesis
  slug: kinesis
  status: profiled
  tags: *id006
  url: /providers/kinesis/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id007
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id008
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 61.7
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id009
  name: Anrok
  slug: anrok
  status: profiled
  tags: *id010
  url: /providers/anrok/
- agent_band: agent-ready
  agent_readiness: 44.7
  band: exemplar
  in_catalog: true
  kin_score: 69.3
  mcp: *id011
  name: Avalara
  slug: avalara
  status: profiled
  tags: *id012
  url: /providers/avalara/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id013
  name: AWS Marketplace
  slug: amazon-web-services
  status: profiled
  tags: *id014
  url: /providers/amazon-web-services/
- agent_band: agent-ready
  agent_readiness: 45.0
  band: exemplar
  in_catalog: true
  kin_score: 76.0
  mcp: *id015
  name: Azure Marketplace
  slug: microsoft-azure
  status: profiled
  tags: *id016
  url: /providers/microsoft-azure/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: thin
  in_catalog: true
  kin_score: 36.4
  mcp: *id017
  name: Cashfree Payments
  slug: cashfree
  status: profiled
  tags: *id018
  url: /providers/cashfree/
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id019
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id020
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 35.4
  band: developing
  in_catalog: true
  kin_score: 53.3
  mcp: *id021
  name: Flutterwave
  slug: flutterwave
  status: profiled
  tags: *id022
  url: /providers/flutterwave/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 67.5
  mcp: *id023
  name: GCP Marketplace
  slug: google-cloud-platform
  status: profiled
  tags: *id024
  url: /providers/google-cloud-platform/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id025
  name: GoCardless
  slug: gocardless
  status: profiled
  tags: *id026
  url: /providers/gocardless/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id027
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id028
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 62.8
  band: exemplar
  in_catalog: true
  kin_score: 66.9
  mcp: *id029
  name: Hightouch
  slug: hightouch
  status: profiled
  tags: *id030
  url: /providers/hightouch/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id031
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id032
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id033
  name: Microsoft Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id034
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 37.8
  band: developing
  in_catalog: true
  kin_score: 40.4
  mcp: *id035
  name: MoneyHash
  slug: moneyhash
  status: profiled
  tags: *id036
  url: /providers/moneyhash/
- agent_band: agent-ready
  agent_readiness: 35.7
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id037
  name: n8n
  slug: n8n
  status: profiled
  tags: *id038
  url: /providers/n8n/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.4
  mcp: *id039
  name: NetSuite
  slug: netsuite
  status: profiled
  tags: *id040
  url: /providers/netsuite/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id041
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id042
  url: /providers/new-relic/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id043
  name: Okta
  slug: okta
  status: profiled
  tags: *id044
  url: /providers/okta/
- agent_band: agent-aware
  agent_readiness: 20.8
  band: thin
  in_catalog: true
  kin_score: 34.8
  mcp: *id045
  name: Oso Cloud
  slug: oso
  status: profiled
  tags: *id046
  url: /providers/oso/
- agent_band: agent-ready
  agent_readiness: 37.4
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id047
  name: Polytomic
  slug: polytomic
  status: profiled
  tags: *id048
  url: /providers/polytomic/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id049
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id050
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id051
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id052
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id053
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id054
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id055
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id056
  url: /providers/stripe/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id057
  name: Twilio Segment
  slug: segment
  status: profiled
  tags: *id058
  url: /providers/segment/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id059
  name: Xero
  slug: xero
  status: profiled
  tags: *id060
  url: /providers/xero/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id061
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id062
  url: /providers/zapier/
siblings:
- name: Chargebee
  rows: 44
  url: /applications/subscription-billing/chargebee/
- name: Invoice Ninja
  rows: 34
  url: /applications/subscription-billing/invoice-ninja/
- name: Kill Bill
  rows: 15
  url: /applications/subscription-billing/kill-bill/
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
title: 'Lago: Subscription Billing & Payments Ops reference app'
---
