---
app: Medusa
app_slug: medusa
app_url: https://github.com/medusajs/medusa
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-220.20
  key: indirect-tax-management
  layer: domain
  name: Indirect Tax Management
  providers:
  - Avalara (AvaTax)
  url: /capabilities/indirect-tax-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2300
  key: merchandising-management
  layer: domain
  name: Merchandising Management
  providers:
  - Contentful
  - Sanity
  url: /capabilities/merchandising-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-520.40
  key: order-fulfilment-management
  layer: domain
  name: Order Fulfilment Management
  providers:
  - ShipStation
  url: /capabilities/order-fulfilment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2650.40
  key: product-catalogue-publication
  layer: domain
  name: Product Catalogue Publication
  providers:
  - Algolia
  - Meilisearch
  url: /capabilities/product-catalogue-publication/
  via_parent: null
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - PostHog
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: common
  name: Customer Data Management
  providers:
  - SendGrid
  - Resend
  - Segment
  url: /capabilities/customer-data-management/
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
  id: BC-3710
  key: media-asset-management
  layer: common
  name: Media Asset Management
  providers:
  - Amazon S3
  url: /capabilities/media-asset-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  - PayPal
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: ecommerce-storefront
  name: E-commerce Storefront
  url: /applications/ecommerce-storefront/
counts:
  declared: 11
  observed: 4
credits: []
evidence:
- route: integrations page
  url: https://docs.medusajs.com/resources/integrations
- route: source code
  url: https://github.com/medusajs/medusa/tree/develop/packages/modules/providers
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/medusajs/medusa/tree/develop/packages/modules/providers/file-s3
  tier: observed
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
    agent_readiness: 57.3
    band: strong
    in_catalog: true
    kin_score: 57.7
    mcp: &id015
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id016
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: PostHog
  provider: posthog
  says: ships the PostHog SDK or integration code
  source: https://github.com/medusajs/medusa/tree/develop/packages/modules/providers/analytics-posthog
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.1
    band: exemplar
    in_catalog: true
    kin_score: 87.3
    mcp: &id023
      status: none
    slug: sendgrid
    status: profiled
    tags: &id024
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://github.com/medusajs/medusa/tree/develop/packages/modules/providers/notification-sendgrid
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
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id029
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id030
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/medusajs/medusa/tree/develop/packages/modules/providers/payment-stripe
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2650.40
    key: product-catalogue-publication
    name: Product Catalogue Publication
    url: /capabilities/product-catalogue-publication/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.9
    band: exemplar
    in_catalog: true
    kin_score: 79.9
    mcp: &id001
      status: none
    slug: algolia
    status: profiled
    tags: &id002
    - Discovery
    - Personalization
    - Recommendations
    - Search
    url: /providers/algolia/
  layer: domain
  name: Algolia
  provider: algolia
  says: lists Algolia as an integration
  source: https://docs.medusajs.com/resources/integrations
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
  name: Avalara (AvaTax)
  provider: avalara
  says: lists Avalara (AvaTax) as an integration
  source: https://docs.medusajs.com/resources/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2300
    key: merchandising-management
    name: Merchandising Management
    url: /capabilities/merchandising-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.5
    band: developing
    in_catalog: true
    kin_score: 44.3
    mcp: &id007
      source: https://github.com/contentful/contentful-mcp-server
      status: verified
    slug: contentful
    status: profiled
    tags: &id008
    - CMS
    - Content
    - Content Management
    - Headless CMS
    url: /providers/contentful/
  layer: domain
  name: Contentful
  provider: contentful
  says: lists Contentful as an integration
  source: https://docs.medusajs.com/resources/integrations
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
    mcp: &id009
      status: none
    slug: mailchimp
    status: profiled
    tags: &id010
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://docs.medusajs.com/resources/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2650.40
    key: product-catalogue-publication
    name: Product Catalogue Publication
    url: /capabilities/product-catalogue-publication/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: developing
    in_catalog: true
    kin_score: 52.0
    mcp: &id011
      source: https://github.com/meilisearch/meilisearch-mcp
      status: verified
    slug: meilisearch
    status: profiled
    tags: &id012
    - AI Search
    - Full-Text Search
    - Hybrid Search
    - Open Source
    url: /providers/meilisearch/
  layer: domain
  name: Meilisearch
  provider: meilisearch
  says: lists Meilisearch as an integration
  source: https://docs.medusajs.com/resources/integrations
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
    mcp: &id013
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id014
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://docs.medusajs.com/resources/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 49.4
    band: strong
    in_catalog: true
    kin_score: 58.9
    mcp: &id017
      source: https://resend.com/docs/mcp-server
      status: verified
    slug: resend
    status: profiled
    tags: &id018
    - Developer Tools
    - Email
    - Marketing Email
    - Transactional Email
    url: /providers/resend/
  layer: common
  name: Resend
  provider: resend
  says: lists Resend as an integration
  source: https://docs.medusajs.com/resources/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2300
    key: merchandising-management
    name: Merchandising Management
    url: /capabilities/merchandising-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.5
    band: strong
    in_catalog: true
    kin_score: 56.9
    mcp: &id019
      source: https://www.sanity.io/docs/compute-and-ai/mcp-server
      status: verified
    slug: sanity
    status: profiled
    tags: &id020
    - Content Management
    - GROQ
    - Headless CMS
    - Real-Time
    url: /providers/sanity/
  layer: domain
  name: Sanity
  provider: sanity
  says: lists Sanity as an integration
  source: https://docs.medusajs.com/resources/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 43.8
    mcp: &id021
      status: none
    slug: segment
    status: profiled
    tags: &id022
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Segment
  provider: segment
  says: lists Segment as an integration
  source: https://docs.medusajs.com/resources/integrations
  tier: declared
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
    kin_score: 80.6
    mcp: &id025
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id026
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: lists Sentry as an integration
  source: https://docs.medusajs.com/resources/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-520.40
    key: order-fulfilment-management
    name: Order Fulfilment Management
    url: /capabilities/order-fulfilment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: strong
    in_catalog: true
    kin_score: 56.7
    mcp: &id027
      status: none
    slug: shipstation
    status: profiled
    tags: &id028
    - E-Commerce
    - Labels
    - Logistics
    - ShipStation
    url: /providers/shipstation/
  layer: domain
  name: ShipStation
  provider: shipstation
  says: lists ShipStation as an integration
  source: https://docs.medusajs.com/resources/integrations
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ecommerce-storefront/medusa/
providers:
- agent_band: agent-ready
  agent_readiness: 62.9
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id001
  name: Algolia
  slug: algolia
  status: profiled
  tags: *id002
  url: /providers/algolia/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id003
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id004
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 44.6
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id005
  name: Avalara (AvaTax)
  slug: avalara
  status: profiled
  tags: *id006
  url: /providers/avalara/
- agent_band: agent-ready
  agent_readiness: 56.5
  band: developing
  in_catalog: true
  kin_score: 44.3
  mcp: *id007
  name: Contentful
  slug: contentful
  status: profiled
  tags: *id008
  url: /providers/contentful/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id009
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id010
  url: /providers/mailchimp/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: developing
  in_catalog: true
  kin_score: 52.0
  mcp: *id011
  name: Meilisearch
  slug: meilisearch
  status: profiled
  tags: *id012
  url: /providers/meilisearch/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id013
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id014
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 57.3
  band: strong
  in_catalog: true
  kin_score: 57.7
  mcp: *id015
  name: PostHog
  slug: posthog
  status: profiled
  tags: *id016
  url: /providers/posthog/
- agent_band: agent-ready
  agent_readiness: 49.4
  band: strong
  in_catalog: true
  kin_score: 58.9
  mcp: *id017
  name: Resend
  slug: resend
  status: profiled
  tags: *id018
  url: /providers/resend/
- agent_band: agent-ready
  agent_readiness: 46.5
  band: strong
  in_catalog: true
  kin_score: 56.9
  mcp: *id019
  name: Sanity
  slug: sanity
  status: profiled
  tags: *id020
  url: /providers/sanity/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 43.8
  mcp: *id021
  name: Segment
  slug: segment
  status: profiled
  tags: *id022
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id023
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id024
  url: /providers/sendgrid/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id025
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id026
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: strong
  in_catalog: true
  kin_score: 56.7
  mcp: *id027
  name: ShipStation
  slug: shipstation
  status: profiled
  tags: *id028
  url: /providers/shipstation/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id029
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id030
  url: /providers/stripe/
siblings:
- name: Bagisto
  rows: 8
  url: /applications/ecommerce-storefront/bagisto/
- name: Etsy (Android)
  rows: 8
  url: /applications/ecommerce-storefront/etsy-android/
- name: Saleor
  rows: 11
  url: /applications/ecommerce-storefront/saleor/
- name: Shop (Shopify consumer app, Android)
  rows: 2
  url: /applications/ecommerce-storefront/shop-shopify-consumer-app-android/
- name: Shopify
  rows: 9
  url: /applications/ecommerce-storefront/shopify/
- name: Sylius
  rows: 4
  url: /applications/ecommerce-storefront/sylius/
- name: Vendure
  rows: 4
  url: /applications/ecommerce-storefront/vendure/
- name: WooCommerce
  rows: 3
  url: /applications/ecommerce-storefront/woocommerce/
sitemap: true
title: 'Medusa: E-commerce Storefront reference app'
---
