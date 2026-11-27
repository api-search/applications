---
app: Mailchimp
app_slug: mailchimp
app_url: https://mailchimp.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: domain
  name: Content Management
  providers:
  - Squarespace
  - Wix
  - WordPress
  url: /capabilities/content-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: domain
  name: Customer Data Management
  providers:
  - Twilio Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430.50.20
  key: BC-430.50.20
  layer: domain
  name: Customer Survey Management
  providers:
  - Qualtrics
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Branch (branch.io)
  - Facebook
  - LinkedIn Lead Gen Forms
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2320.10
  key: sales-transaction-management
  layer: domain
  name: Sales Transaction Management
  providers:
  - Shopify
  - Square
  - WooCommerce
  url: /capabilities/sales-transaction-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: common
  name: Design & Creative Editing
  providers:
  - Canva
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase (Crashlytics + Analytics)
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280
  key: product-telemetry-experimentation-management
  layer: common
  name: Product Telemetry & Experimentation Management
  providers:
  - Optimizely
  url: /capabilities/product-telemetry-experimentation-management/
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
  id: email-marketing-newsletter
  name: Email Marketing & Newsletters
  url: /applications/email-marketing-newsletter/
counts:
  declared: 12
  observed: 5
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
- route: integrations page
  url: https://mailchimp.com/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id001
      status: none
    slug: branch-io
    status: profiled
    tags: &id002
    - Company
    url: /providers/branch-io/
  layer: domain
  name: Branch (branch.io)
  provider: branch-io
  says: ships the Branch (branch.io) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id007
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id008
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase (Crashlytics + Analytics)
  provider: firebase
  says: ships the Firebase (Crashlytics + Analytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 61.6
    band: exemplar
    in_catalog: true
    kin_score: 78.1
    mcp: &id011
      source: https://support.optimizely.com/hc/en-us/articles/45320607594893
      status: documented
    slug: optimizely
    status: profiled
    tags: &id012
    - A/B Testing
    - Content Management
    - Customer Data
    - E-Commerce
    url: /providers/optimizely/
  layer: common
  name: Optimizely
  provider: optimizely
  says: ships the Optimizely SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-430.50.20
    key: BC-430.50.20
    name: Customer Survey Management
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 45.7
    mcp: &id013
      status: none
    slug: qualtrics
    status: profiled
    tags: &id014
    - Customer Experience
    - Employee Experience
    - Experience Management
    - Surveys
    url: /providers/qualtrics/
  layer: domain
  name: Qualtrics
  provider: qualtrics
  says: ships the Qualtrics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id025
      status: none
    slug: segment
    status: profiled
    tags: &id026
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: domain
  name: Twilio Segment
  provider: segment
  says: ships the Twilio Segment SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.mailchimp.mailchimp/latest/
  tier: observed
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
    mcp: &id003
      source: https://www.canva.dev/docs/mcp/
      status: verified
    slug: canva
    status: profiled
    tags: &id004
    - Application
    - Automation
    - Brand Management
    - Collaboration
    url: /providers/canva/
  layer: common
  name: Canva
  provider: canva
  says: lists Canva as an integration
  source: https://mailchimp.com/integrations/
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
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id005
      status: none
    slug: facebook
    status: profiled
    tags: &id006
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: lists Facebook as an integration
  source: https://mailchimp.com/integrations/
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
    agent_readiness: 46.5
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id009
      status: none
    slug: linkedin
    status: profiled
    tags: &id010
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn Lead Gen Forms
  provider: linkedin
  says: lists LinkedIn Lead Gen Forms as an integration
  source: https://mailchimp.com/integrations/
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
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id015
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id016
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://mailchimp.com/integrations/
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
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id017
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id018
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://mailchimp.com/integrations/
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
    agent_band: agent-native
    agent_readiness: 61.5
    band: exemplar
    in_catalog: true
    kin_score: 78.2
    mcp: &id019
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id020
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: domain
  name: Square
  provider: square
  says: lists Square as an integration
  source: https://mailchimp.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 48.5
    band: exemplar
    in_catalog: true
    kin_score: 68.7
    mcp: &id021
      status: none
    slug: squarespace
    status: profiled
    tags: &id022
    - Commerce
    - E-Commerce
    - Marketing
    - Payments
    url: /providers/squarespace/
  layer: domain
  name: Squarespace
  provider: squarespace
  says: lists Squarespace as an integration
  source: https://mailchimp.com/integrations/
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
    mcp: &id023
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id024
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://mailchimp.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.2
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id027
      source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
      status: verified
    slug: wix
    status: profiled
    tags: &id028
    - CMS
    - E-Commerce
    - Headless
    - Website Builder
    url: /providers/wix/
  layer: domain
  name: Wix
  provider: wix
  says: lists Wix as an integration
  source: https://mailchimp.com/integrations/
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
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 54.6
    mcp: &id029
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id030
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://mailchimp.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id031
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id032
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
  layer: domain
  name: WordPress
  provider: wordpress
  says: lists WordPress as an integration
  source: https://mailchimp.com/integrations/
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
    mcp: &id033
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id034
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://mailchimp.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/email-marketing-newsletter/mailchimp/
providers:
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id001
  name: Branch (branch.io)
  slug: branch-io
  status: profiled
  tags: *id002
  url: /providers/branch-io/
- agent_band: agent-native
  agent_readiness: 70.0
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id003
  name: Canva
  slug: canva
  status: profiled
  tags: *id004
  url: /providers/canva/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id005
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id006
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id007
  name: Firebase (Crashlytics + Analytics)
  slug: google-firebase
  status: profiled
  tags: *id008
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id009
  name: LinkedIn Lead Gen Forms
  slug: linkedin
  status: profiled
  tags: *id010
  url: /providers/linkedin/
- agent_band: agent-ready
  agent_readiness: 61.6
  band: exemplar
  in_catalog: true
  kin_score: 78.1
  mcp: *id011
  name: Optimizely
  slug: optimizely
  status: profiled
  tags: *id012
  url: /providers/optimizely/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 45.7
  mcp: *id013
  name: Qualtrics
  slug: qualtrics
  status: profiled
  tags: *id014
  url: /providers/qualtrics/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id015
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id016
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id017
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id018
  url: /providers/shopify/
- agent_band: agent-native
  agent_readiness: 61.5
  band: exemplar
  in_catalog: true
  kin_score: 78.2
  mcp: *id019
  name: Square
  slug: square
  status: profiled
  tags: *id020
  url: /providers/square/
- agent_band: agent-native
  agent_readiness: 48.5
  band: exemplar
  in_catalog: true
  kin_score: 68.7
  mcp: *id021
  name: Squarespace
  slug: squarespace
  status: profiled
  tags: *id022
  url: /providers/squarespace/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id023
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id024
  url: /providers/stripe/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id025
  name: Twilio Segment
  slug: segment
  status: profiled
  tags: *id026
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 47.2
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id027
  name: Wix
  slug: wix
  status: profiled
  tags: *id028
  url: /providers/wix/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id029
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id030
  url: /providers/woocommerce/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id031
  name: WordPress
  slug: wordpress
  status: profiled
  tags: *id032
  url: /providers/wordpress/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id033
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id034
  url: /providers/zapier/
siblings:
- name: beehiiv
  rows: 22
  url: /applications/email-marketing-newsletter/beehiiv/
- name: Ghost
  rows: 17
  url: /applications/email-marketing-newsletter/ghost/
- name: Keila
  rows: 7
  url: /applications/email-marketing-newsletter/keila/
- name: Klaviyo
  rows: 15
  url: /applications/email-marketing-newsletter/klaviyo/
- name: listmonk
  rows: 13
  url: /applications/email-marketing-newsletter/listmonk/
- name: Mautic
  rows: 25
  url: /applications/email-marketing-newsletter/mautic/
- name: Substack
  rows: 4
  url: /applications/email-marketing-newsletter/substack/
sitemap: true
title: 'Mailchimp: Email Marketing & Newsletters reference app'
---
