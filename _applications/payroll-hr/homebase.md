---
app: Homebase
app_slug: homebase
app_url: https://www.joinhomebase.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-300.70
  key: hr-operations-management
  layer: domain
  name: HR Operations Management
  providers:
  - ADP
  - Gusto
  - Millennium Payroll Services
  - Paychex
  - QuickBooks (Payroll)
  - SurePayroll
  url: /capabilities/hr-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2320
  key: point-of-sale-operations-management
  layer: domain
  name: Point of Sale Operations Management
  providers:
  - Clover
  - GoDaddy (POS)
  - Heartland
  - Lightspeed
  - PAR
  - Shopify POS
  - Square (POS + Square Payroll)
  - Toast
  url: /capabilities/point-of-sale-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1330.10
  key: deposit-account-management
  layer: common
  name: Deposit Account Management
  providers:
  - Bank of America
  - Wells Fargo
  url: /capabilities/deposit-account-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - AppsFlyer
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Amplitude
  - Firebase (Crashlytics / Analytics)
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: payroll-hr
  name: HR, Payroll & People Ops
  url: /applications/payroll-hr/
counts:
  declared: 16
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.joinhomebase.homebase.homebase/latest/
- route: integrations page
  url: https://www.joinhomebase.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 56.7
    band: strong
    in_catalog: true
    kin_score: 63.5
    mcp: &id003
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id004
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: ships the Amplitude SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.joinhomebase.homebase.homebase/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 46.4
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id005
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id006
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.joinhomebase.homebase.homebase/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id011
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id012
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase (Crashlytics / Analytics)
  provider: firebase
  says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.joinhomebase.homebase.homebase/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-300.70
    key: hr-operations-management
    name: HR Operations Management
    url: /capabilities/hr-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.7
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id001
      status: none
    slug: adp
    status: profiled
    tags: &id002
    - Benefits
    - HCM
    - Human Resources
    - Payroll
    url: /providers/adp/
  layer: domain
  name: ADP
  provider: adp
  says: lists ADP as an integration
  source: https://www.joinhomebase.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1330.10
    key: deposit-account-management
    name: Deposit Account Management
    url: /capabilities/deposit-account-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.8
    band: thin
    in_catalog: true
    kin_score: 38.3
    mcp: &id007
      status: none
    slug: bank-of-america
    status: profiled
    tags: &id008
    - Banking
    - Corporate Banking
    - Finance
    - Payments
    url: /providers/bank-of-america/
  layer: common
  name: Bank of America
  provider: bank-of-america
  says: lists Bank of America as an integration
  source: https://www.joinhomebase.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 39.9
    mcp: &id009
      status: none
    slug: clover
    status: profiled
    tags: &id010
    - Payments
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/clover/
  layer: domain
  name: Clover
  provider: clover
  says: lists Clover as an integration
  source: https://www.joinhomebase.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.7
    band: thin
    in_catalog: true
    kin_score: 31.7
    mcp: &id013
      source: https://developer.godaddy.com/mcp
      status: verified
    slug: godaddy
    status: profiled
    tags: &id014
    - Aftermarket
    - Certificates
    - DNS
    - Domains
    url: /providers/godaddy/
  layer: domain
  name: GoDaddy (POS)
  provider: godaddy
  says: lists GoDaddy (POS) as an integration
  source: https://www.joinhomebase.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.70
    key: hr-operations-management
    name: HR Operations Management
    url: /capabilities/hr-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: developing
    in_catalog: true
    kin_score: 42.0
    mcp: &id015
      status: none
    slug: gusto
    status: profiled
    tags: &id016
    - Benefits
    - Enterprise Software
    - Human Resources
    - Payroll
    url: /providers/gusto/
  layer: domain
  name: Gusto
  provider: gusto
  says: lists Gusto as an integration
  source: https://www.joinhomebase.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 16.1
    mcp: &id017
      source: https://github.com/globalpayments/mcp-server
      status: verified
    slug: heartland-payment-systems
    status: profiled
    tags: &id018
    - Bill Pay
    - Card Not Present
    - Card Present
    - E-Commerce
    url: /providers/heartland-payment-systems/
  layer: domain
  name: Heartland
  provider: heartland-payment-systems
  says: lists Heartland as an integration
  source: https://www.joinhomebase.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 86.5
    mcp: &id019
      status: none
    slug: lightspeed
    status: profiled
    tags: &id020
    - Commerce
    - Point-of-Sale
    - Restaurant
    - Retail
    url: /providers/lightspeed/
  layer: domain
  name: Lightspeed
  provider: lightspeed
  says: lists Lightspeed as an integration
  source: https://www.joinhomebase.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.70
    key: hr-operations-management
    name: HR Operations Management
    url: /capabilities/hr-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id021
      status: unchecked
    slug: millennium-payroll-services
    status: queued for profiling
    tags: &id022 []
    url: null
  layer: domain
  name: Millennium Payroll Services
  provider: millennium-payroll-services
  says: lists Millennium Payroll Services as an integration
  source: https://www.joinhomebase.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.5
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id023
      status: none
    slug: par-technology
    status: profiled
    tags: &id024
    - Company
    - Hospitality
    - Loyalty
    - Point-of-Sale
    url: /providers/par-technology/
  layer: domain
  name: PAR
  provider: par-technology
  says: lists PAR as an integration
  source: https://www.joinhomebase.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.70
    key: hr-operations-management
    name: HR Operations Management
    url: /capabilities/hr-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.4
    band: thin
    in_catalog: true
    kin_score: 37.9
    mcp: &id025
      status: none
    slug: paychex-developer
    status: profiled
    tags: &id026
    - Benefits
    - HCM
    - Human Resources
    - Paychex Flex
    url: /providers/paychex-developer/
  layer: domain
  name: Paychex
  provider: paychex-developer
  says: lists Paychex as an integration
  source: https://www.joinhomebase.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.70
    key: hr-operations-management
    name: HR Operations Management
    url: /capabilities/hr-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 41.2
    band: strong
    in_catalog: true
    kin_score: 61.1
    mcp: &id027
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id028
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks (Payroll)
  provider: quickbooks
  says: lists QuickBooks (Payroll) as an integration
  source: https://www.joinhomebase.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.5
    band: exemplar
    in_catalog: true
    kin_score: 84.6
    mcp: &id029
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id030
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify POS
  provider: shopify
  says: lists Shopify POS as an integration
  source: https://www.joinhomebase.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 62.8
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id031
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id032
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: domain
  name: Square (POS + Square Payroll)
  provider: square
  says: lists Square (POS + Square Payroll) as an integration
  source: https://www.joinhomebase.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.70
    key: hr-operations-management
    name: HR Operations Management
    url: /capabilities/hr-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.0
    band: emerging
    in_catalog: true
    kin_score: 15.5
    mcp: &id033
      status: none
    slug: surepayroll
    status: profiled
    tags: &id034
    - Human Resources
    - Paychex
    - Payroll
    - Small Business
    url: /providers/surepayroll/
  layer: domain
  name: SurePayroll
  provider: surepayroll
  says: lists SurePayroll as an integration
  source: https://www.joinhomebase.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.6
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id035
      status: none
    slug: toast
    status: profiled
    tags: &id036
    - Food Service
    - Hospitality
    - Point-of-Sale
    - Restaurant
    url: /providers/toast/
  layer: domain
  name: Toast
  provider: toast
  says: lists Toast as an integration
  source: https://www.joinhomebase.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1330.10
    key: deposit-account-management
    name: Deposit Account Management
    url: /capabilities/deposit-account-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.4
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id037
      status: none
    slug: wells-fargo
    status: profiled
    tags: &id038
    - Banking
    - Consumer Banking
    - Fortune 100
    url: /providers/wells-fargo/
  layer: common
  name: Wells Fargo
  provider: wells-fargo
  says: lists Wells Fargo as an integration
  source: https://www.joinhomebase.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/payroll-hr/homebase/
providers:
- agent_band: agent-ready
  agent_readiness: 35.7
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id001
  name: ADP
  slug: adp
  status: profiled
  tags: *id002
  url: /providers/adp/
- agent_band: agent-ready
  agent_readiness: 56.7
  band: strong
  in_catalog: true
  kin_score: 63.5
  mcp: *id003
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id004
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id005
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id006
  url: /providers/appsflyer/
- agent_band: agent-ready
  agent_readiness: 29.8
  band: thin
  in_catalog: true
  kin_score: 38.3
  mcp: *id007
  name: Bank of America
  slug: bank-of-america
  status: profiled
  tags: *id008
  url: /providers/bank-of-america/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 39.9
  mcp: *id009
  name: Clover
  slug: clover
  status: profiled
  tags: *id010
  url: /providers/clover/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id011
  name: Firebase (Crashlytics / Analytics)
  slug: firebase
  status: profiled
  tags: *id012
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 36.7
  band: thin
  in_catalog: true
  kin_score: 31.7
  mcp: *id013
  name: GoDaddy (POS)
  slug: godaddy
  status: profiled
  tags: *id014
  url: /providers/godaddy/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 42.0
  mcp: *id015
  name: Gusto
  slug: gusto
  status: profiled
  tags: *id016
  url: /providers/gusto/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 16.1
  mcp: *id017
  name: Heartland
  slug: heartland-payment-systems
  status: profiled
  tags: *id018
  url: /providers/heartland-payment-systems/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 86.5
  mcp: *id019
  name: Lightspeed
  slug: lightspeed
  status: profiled
  tags: *id020
  url: /providers/lightspeed/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id021
  name: Millennium Payroll Services
  slug: millennium-payroll-services
  status: queued for profiling
  tags: *id022
  url: null
- agent_band: agent-ready
  agent_readiness: 41.5
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id023
  name: PAR
  slug: par-technology
  status: profiled
  tags: *id024
  url: /providers/par-technology/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: thin
  in_catalog: true
  kin_score: 37.9
  mcp: *id025
  name: Paychex
  slug: paychex-developer
  status: profiled
  tags: *id026
  url: /providers/paychex-developer/
- agent_band: agent-native
  agent_readiness: 41.2
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id027
  name: QuickBooks (Payroll)
  slug: quickbooks
  status: profiled
  tags: *id028
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 52.5
  band: exemplar
  in_catalog: true
  kin_score: 84.6
  mcp: *id029
  name: Shopify POS
  slug: shopify
  status: profiled
  tags: *id030
  url: /providers/shopify/
- agent_band: agent-native
  agent_readiness: 62.8
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id031
  name: Square (POS + Square Payroll)
  slug: square
  status: profiled
  tags: *id032
  url: /providers/square/
- agent_band: agent-aware
  agent_readiness: 18.0
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id033
  name: SurePayroll
  slug: surepayroll
  status: profiled
  tags: *id034
  url: /providers/surepayroll/
- agent_band: agent-ready
  agent_readiness: 39.6
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id035
  name: Toast
  slug: toast
  status: profiled
  tags: *id036
  url: /providers/toast/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id037
  name: Wells Fargo
  slug: wells-fargo
  status: profiled
  tags: *id038
  url: /providers/wells-fargo/
siblings:
- name: ADP Mobile Solutions
  rows: 5
  url: /applications/payroll-hr/adp-mobile-solutions/
- name: Connecteam
  rows: 3
  url: /applications/payroll-hr/connecteam/
- name: Deel
  rows: 35
  url: /applications/payroll-hr/deel/
- name: Frappe HR
  rows: 1
  url: /applications/payroll-hr/frappe-hr/
- name: Horilla
  rows: 7
  url: /applications/payroll-hr/horilla/
- name: OrangeHRM
  rows: 0
  url: /applications/payroll-hr/orangehrm/
- name: Paylocity
  rows: 4
  url: /applications/payroll-hr/paylocity/
- name: Workday
  rows: 2
  url: /applications/payroll-hr/workday/
sitemap: true
title: 'Homebase: HR, Payroll & People Ops reference app'
---
