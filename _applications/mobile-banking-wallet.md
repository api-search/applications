---
access: understanding
agent_layer: []
apps:
- anchor: revolut
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.revolut.revolut/latest/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.revolut.revolut/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase Crashlytics
    provider: firebase
    says: ships the Firebase Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.revolut.revolut/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.revolut.revolut/latest/
    tier: observed
  kind: commercial
  name: Revolut
  page: /applications/mobile-banking-wallet/revolut/
  slug: revolut
  url: https://www.revolut.com/
- anchor: cash-app
  counts:
    declared: 4
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.squareup.cash/latest/
  - route: documentation
    url: https://cash.app/legal/us/en-us/privacy
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.squareup.cash/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Bugsnag
    provider: bugsnag
    says: ships the Bugsnag SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.squareup.cash/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.squareup.cash/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.10
      key: AE-140.30.10
      name: Buy Now, Pay Later
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: domain
    name: Afterpay
    provider: afterpay
    says: lists Afterpay as an integration
    source: https://cash.app/legal/us/en-us/privacy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.100
      key: AE-150.100
      name: Embedded Mobile Plans & eSIM
      url: /capabilities/embedded-mobile-plans-esim/
      via_parent: null
    credit: null
    layer: domain
    name: Gigs (Cash App Mobile)
    provider: gigs
    says: lists Gigs (Cash App Mobile) as an integration
    source: https://cash.app/legal/us/en-us/privacy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-935
      key: AE-935
      name: Banking-as-a-Service & Sponsor Banks
      url: /capabilities/banking-as-a-service-sponsor-banks/
      via_parent: null
    credit: null
    layer: domain
    name: Sutton Bank
    provider: sutton-bank
    says: lists Sutton Bank as an integration
    source: https://cash.app/legal/us/en-us/privacy
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.60
      key: card-issuance-management
      name: Card Issuance Management
      url: /capabilities/card-issuance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Visa (Cash App Card)
    provider: visa
    says: lists Visa (Cash App Card) as an integration
    source: https://cash.app/legal/us/en-us/privacy
    tier: declared
  kind: commercial
  name: Cash App
  page: /applications/mobile-banking-wallet/cash-app/
  slug: cash-app
  url: https://cash.app/
- anchor: paypal
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.paypal.android.p2pmobile/latest/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Adjust
    provider: adjust
    says: ships the Adjust SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.paypal.android.p2pmobile/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Adobe Experience Cloud
    provider: adobe-experience-cloud
    says: ships the Adobe Experience Cloud SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.paypal.android.p2pmobile/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Qualtrics
    provider: qualtrics
    says: ships the Qualtrics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.paypal.android.p2pmobile/latest/
    tier: observed
  kind: commercial
  name: PayPal
  page: /applications/mobile-banking-wallet/paypal/
  slug: paypal
  url: https://www.paypal.com/
- anchor: wise
  counts:
    declared: 10
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.transferwise.android/latest/
  - route: integrations page
    url: https://wise.com/us/business/accounting-software
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook Login
    provider: facebook
    says: ships the Facebook Login SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.transferwise.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase Crashlytics
    provider: firebase
    says: ships the Firebase Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.transferwise.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.transferwise.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Mixpanel
    provider: mixpanel
    says: ships the Mixpanel SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.transferwise.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Singular
    provider: singular
    says: ships the Singular SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.transferwise.android/latest/
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
    name: Bonsai
    provider: bonsai
    says: lists Bonsai as an integration
    source: https://wise.com/us/business/accounting-software
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
    name: FreeAgent
    provider: freeagent
    says: lists FreeAgent as an integration
    source: https://wise.com/us/business/accounting-software
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
    name: Microsoft Dynamics 365 Business Central
    provider: microsoft-dynamics-365-business-central
    says: lists Microsoft Dynamics 365 Business Central as an integration
    source: https://wise.com/us/business/accounting-software
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
    name: Odoo
    provider: odoo
    says: lists Odoo as an integration
    source: https://wise.com/us/business/accounting-software
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
    source: https://wise.com/us/business/accounting-software
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
    source: https://wise.com/us/business/accounting-software
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
    name: Sage Business Cloud Accounting
    provider: sage
    says: lists Sage Business Cloud Accounting as an integration
    source: https://wise.com/us/business/accounting-software
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
    name: Wave
    provider: wave-financial
    says: lists Wave as an integration
    source: https://wise.com/us/business/accounting-software
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
    source: https://wise.com/us/business/accounting-software
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
    name: Zoho Books
    provider: zoho-books
    says: lists Zoho Books as an integration
    source: https://wise.com/us/business/accounting-software
    tier: declared
  kind: commercial
  name: Wise
  page: /applications/mobile-banking-wallet/wise/
  slug: wise
  url: https://wise.com/
- anchor: mifos-pay-(openmf-mobile-wallet)
  counts:
    declared: 1
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/openMF/mobile-wallet/dev/gradle/libs.versions.toml
  - route: documentation
    url: https://github.com/openMF/mobile-wallet
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Firebase Analytics
    provider: firebase
    says: ships the Firebase Analytics SDK or integration code
    source: https://raw.githubusercontent.com/openMF/mobile-wallet/dev/gradle/libs.versions.toml
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
    name: Firebase Crashlytics + Performance
    provider: firebase
    says: ships the Firebase Crashlytics + Performance SDK or integration code
    source: https://raw.githubusercontent.com/openMF/mobile-wallet/dev/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4270.70
      key: software-marketplace-listing-management
      name: Software Marketplace Listing Management
      url: /capabilities/software-marketplace-listing-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Play (Integrity, In-App Review, In-App Update)
    provider: google-play
    says: ships the Google Play (Integrity, In-App Review, In-App Update) SDK or integration code
    source: https://raw.githubusercontent.com/openMF/mobile-wallet/dev/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://raw.githubusercontent.com/openMF/mobile-wallet/dev/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-936
      key: AE-936
      name: Core Banking Platforms
      url: /capabilities/core-banking-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Fineract (Mifos platform)
    provider: apache-fineract
    says: lists Apache Fineract (Mifos platform) as an integration
    source: https://github.com/openMF/mobile-wallet
    tier: declared
  kind: self-hosted
  name: Mifos Pay (openMF mobile-wallet)
  page: /applications/mobile-banking-wallet/mifos-pay-openmf-mobile-wallet/
  slug: mifos-pay-openmf-mobile-wallet
  url: https://github.com/openMF/mobile-wallet
- anchor: mifos-mobile-(openmf-mifos-mobile)
  counts:
    declared: 1
    observed: 5
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/openMF/mifos-mobile/dev/gradle/libs.versions.toml
  - route: documentation
    url: https://github.com/openMF/mifos-mobile
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Firebase Analytics
    provider: firebase
    says: ships the Firebase Analytics SDK or integration code
    source: https://raw.githubusercontent.com/openMF/mifos-mobile/dev/gradle/libs.versions.toml
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
    name: Firebase Cloud Messaging
    provider: firebase
    says: ships the Firebase Cloud Messaging SDK or integration code
    source: https://raw.githubusercontent.com/openMF/mifos-mobile/dev/gradle/libs.versions.toml
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
    name: Firebase Crashlytics + Performance
    provider: firebase
    says: ships the Firebase Crashlytics + Performance SDK or integration code
    source: https://raw.githubusercontent.com/openMF/mifos-mobile/dev/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: Google Maps
    provider: google-maps
    says: ships the Google Maps SDK or integration code
    source: https://raw.githubusercontent.com/openMF/mifos-mobile/dev/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4270.70
      key: software-marketplace-listing-management
      name: Software Marketplace Listing Management
      url: /capabilities/software-marketplace-listing-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Play (Integrity, In-App Review, In-App Update)
    provider: google-play
    says: ships the Google Play (Integrity, In-App Review, In-App Update) SDK or integration code
    source: https://raw.githubusercontent.com/openMF/mifos-mobile/dev/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-936
      key: AE-936
      name: Core Banking Platforms
      url: /capabilities/core-banking-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Fineract (Mifos platform)
    provider: apache-fineract
    says: lists Apache Fineract (Mifos platform) as an integration
    source: https://github.com/openMF/mifos-mobile
    tier: declared
  kind: self-hosted
  name: Mifos Mobile (openMF mifos-mobile)
  page: /applications/mobile-banking-wallet/mifos-mobile-openmf-mifos-mobile/
  slug: mifos-mobile-openmf-mifos-mobile
  url: https://github.com/openMF/mifos-mobile
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: mobile-banking-wallet
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Finance
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Finance
  store: google-play
  url: https://play.google.com/store/apps/category/FINANCE
name: Mobile Banking & Payments Wallet
needs:
- capability:
    attribution: Turbo EA
    id: BC-1330.10
    key: deposit-account-management
    name: Deposit Account Management
    url: /capabilities/deposit-account-management/
    via_parent: null
  fit: exact
  layer: domain
  why: the account the wallet fronts (core banking / sponsor bank)
- capability:
    attribution: Turbo EA
    id: BC-1340.60
    key: card-issuance-management
    name: Card Issuance Management
    url: /capabilities/card-issuance-management/
    via_parent: null
  fit: exact
  layer: domain
  why: debit cards issued with the wallet
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: domain
  why: business wallets sync to accounting
- capability:
    attribution: API Evangelist extension
    id: AE-190.50
    key: AE-190.50
    name: Consumer Data Access
    url: /capabilities/consumer-data-access/
    via_parent: null
  fit: exact
  layer: domain
  why: linking external bank accounts
- capability:
    attribution: API Evangelist extension
    id: AE-190.40
    key: AE-190.40
    name: Remittances & P2P
    url: /capabilities/remittances-p2p/
    via_parent: null
  fit: exact
  layer: domain
  why: core wallet function
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.10
    key: AE-140.30.10
    name: Buy Now, Pay Later
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  fit: exact
  layer: domain
  why: BNPL inside the wallet
- capability:
    attribution: API Evangelist extension
    id: AE-150.100
    key: AE-150.100
    name: Embedded Mobile Plans & eSIM
    url: /capabilities/embedded-mobile-plans-esim/
    via_parent: null
  fit: exact
  layer: domain
  why: embedded mobile service (Cash App Mobile); nearest until a telecom node exists
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash / performance reporting
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: app analytics
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: transaction alerts
- capability:
    attribution: Turbo EA
    id: BC-4270.70
    key: software-marketplace-listing-management
    name: Software Marketplace Listing Management
    url: /capabilities/software-marketplace-listing-management/
    via_parent: null
  fit: nearest
  layer: common
  why: Play Integrity / review / update
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: Google sign-in
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: common
  why: branch / ATM locator
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: install attribution and deep links
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: marketing measurement
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  fit: exact
  layer: common
  why: in-app customer feedback
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
      agent_readiness: 60.0
      apps:
      - Wise
      band: exemplar
      in_catalog: true
      kin_score: 87.1
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://wise.com/us/business/accounting-software
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: declared
      url: /providers/xero/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Wise
      band: exemplar
      in_catalog: true
      kin_score: 73.1
      mcp:
        status: none
      name: Microsoft Dynamics 365 Business Central
      slug: microsoft-dynamics-365-business-central
      sources:
      - https://wise.com/us/business/accounting-software
      status: profiled
      tags:
      - Accounting
      - Cloud ERP
      - ERP
      - Finance
      tier: declared
      url: /providers/microsoft-dynamics-365-business-central/
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Wise
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks
      slug: quickbooks
      sources:
      - https://wise.com/us/business/accounting-software
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Wise
      band: developing
      in_catalog: true
      kin_score: 47.5
      mcp:
        source: https://www.zoho.com/mcp/
        status: documented
      name: Zoho Books
      slug: zoho-books
      sources:
      - https://wise.com/us/business/accounting-software
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Expenses
      - Invoicing
      tier: declared
      url: /providers/zoho-books/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Wise
      band: developing
      in_catalog: true
      kin_score: 41.7
      mcp:
        status: none
      name: Sage Business Cloud Accounting
      slug: sage
      sources:
      - https://wise.com/us/business/accounting-software
      status: profiled
      tags:
      - Accounting
      - Business Management
      - Cloud Software
      - ERP
      tier: declared
      url: /providers/sage/
    - agent_band: agent-aware
      agent_readiness: 25.1
      apps:
      - Wise
      band: developing
      in_catalog: true
      kin_score: 39.7
      mcp:
        status: none
      name: FreeAgent
      slug: freeagent
      sources:
      - https://wise.com/us/business/accounting-software
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Invoicing
      - Small Business
      tier: declared
      url: /providers/freeagent/
    - agent_band: agent-ready
      agent_readiness: 29.7
      apps:
      - Wise
      band: thin
      in_catalog: true
      kin_score: 27.8
      mcp:
        source: https://mcp.hellobonsai.com/mcp
        status: verified
      name: Bonsai
      slug: bonsai
      sources:
      - https://wise.com/us/business/accounting-software
      status: profiled
      tags:
      - B2B
      - Business Management
      - Company
      - Freelancing
      tier: declared
      url: /providers/bonsai/
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - Wise
      band: thin
      in_catalog: true
      kin_score: 27.6
      mcp:
        status: none
      name: Odoo
      slug: odoo
      sources:
      - https://wise.com/us/business/accounting-software
      status: profiled
      tags:
      - Business Applications
      - CRM
      - ERP
      - Open Source
      tier: declared
      url: /providers/odoo/
    - agent_band: agent-aware
      agent_readiness: 15.8
      apps:
      - Wise
      band: thin
      in_catalog: true
      kin_score: 26.9
      mcp:
        status: none
      name: Wave
      slug: wave-financial
      sources:
      - https://wise.com/us/business/accounting-software
      status: profiled
      tags:
      - Accounting
      - Finance
      - Invoicing
      - Small Business
      tier: declared
      url: /providers/wave-financial/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Wise
      band: emerging
      in_catalog: true
      kin_score: 11.4
      mcp:
        status: none
      name: Oracle NetSuite
      slug: netsuite
      sources:
      - https://wise.com/us/business/accounting-software
      status: profiled
      tags:
      - Accounting
      - CRM
      - ERP
      - Finance
      tier: declared
      url: /providers/netsuite/
  - capability:
      attribution: API Evangelist extension
      id: AE-936
      key: AE-936
      name: Core Banking Platforms
      url: /capabilities/core-banking-platforms/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Mifos Mobile (openMF mifos-mobile)
      - Mifos Pay (openMF mobile-wallet)
      band: emerging
      in_catalog: true
      kin_score: 15.1
      mcp:
        status: none
      name: Apache Fineract (Mifos platform)
      slug: apache-fineract
      sources:
      - https://github.com/openMF/mifos-mobile
      - https://github.com/openMF/mobile-wallet
      status: profiled
      tags:
      - Banking
      - Company
      - Fintech
      - Open Source
      tier: declared
      url: /providers/apache-fineract/
  - capability:
      attribution: API Evangelist extension
      id: AE-935
      key: AE-935
      name: Banking-as-a-Service & Sponsor Banks
      url: /capabilities/banking-as-a-service-sponsor-banks/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Cash App
      band: minimal
      in_catalog: true
      kin_score: 5.9
      mcp:
        status: unknown
      name: Sutton Bank
      slug: sutton-bank
      sources:
      - https://cash.app/legal/us/en-us/privacy
      status: profiled
      tags:
      - Banking
      - Community Bank
      - Financial Services
      - Ohio
      tier: declared
      url: /providers/sutton-bank/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.10
      key: AE-140.30.10
      name: Buy Now, Pay Later
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    providers:
    - agent_band: agent-aware
      agent_readiness: 12.8
      apps:
      - Cash App
      band: minimal
      in_catalog: true
      kin_score: 9.2
      mcp:
        status: none
      name: Afterpay
      slug: afterpay
      sources:
      - https://cash.app/legal/us/en-us/privacy
      status: profiled
      tags:
      - Buy Now Pay Later
      - Consumer
      - Fintech
      - Payments
      tier: declared
      url: /providers/afterpay/
  - capability:
      attribution: Turbo EA
      id: BC-1340.60
      key: card-issuance-management
      name: Card Issuance Management
      url: /capabilities/card-issuance-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.5
      apps:
      - Cash App
      band: developing
      in_catalog: true
      kin_score: 43.6
      mcp:
        source: https://github.com/visa/ai
        status: verified
      name: Visa (Cash App Card)
      slug: visa
      sources:
      - https://cash.app/legal/us/en-us/privacy
      status: profiled
      tags:
      - Account
      - Banking
      - Credit Cards
      - Visa
      tier: declared
      url: /providers/visa/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.100
      key: AE-150.100
      name: Embedded Mobile Plans & eSIM
      url: /capabilities/embedded-mobile-plans-esim/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.1
      apps:
      - Cash App
      band: developing
      in_catalog: true
      kin_score: 45.6
      mcp:
        status: none
      name: Gigs (Cash App Mobile)
      slug: gigs
      sources:
      - https://cash.app/legal/us/en-us/privacy
      status: profiled
      tags:
      - Company
      - Connectivity
      - Telecommunications
      - eSIM
      tier: declared
      url: /providers/gigs/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Cash App
      - Mifos Mobile (openMF mifos-mobile)
      - Mifos Pay (openMF mobile-wallet)
      - Revolut
      - Wise
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://raw.githubusercontent.com/openMF/mifos-mobile/dev/gradle/libs.versions.toml
      - https://raw.githubusercontent.com/openMF/mobile-wallet/dev/gradle/libs.versions.toml
      - https://reports.exodus-privacy.eu.org/en/reports/com.revolut.revolut/latest/
      status: profiled
      tags: &id002
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - Wise
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.transferwise.android/latest/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Mifos Mobile (openMF mifos-mobile)
      - Mifos Pay (openMF mobile-wallet)
      - Revolut
      - Wise
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id001
      name: Firebase Crashlytics
      slug: google-firebase
      sources:
      - https://raw.githubusercontent.com/openMF/mifos-mobile/dev/gradle/libs.versions.toml
      - https://raw.githubusercontent.com/openMF/mobile-wallet/dev/gradle/libs.versions.toml
      - https://reports.exodus-privacy.eu.org/en/reports/com.revolut.revolut/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Cash App
      band: exemplar
      in_catalog: true
      kin_score: 76.3
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.squareup.cash/latest/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - Cash App
      - Revolut
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.revolut.revolut/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.squareup.cash/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
    - agent_band: agent-ready
      agent_readiness: 48.9
      apps:
      - Wise
      band: strong
      in_catalog: true
      kin_score: 65.9
      mcp:
        status: none
      name: Singular
      slug: singular
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.transferwise.android/latest/
      status: profiled
      tags:
      - Attribution
      - Company
      - Marketing Analytics
      - Mobile Attribution
      tier: observed
      url: /providers/singular/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - PayPal
      band: thin
      in_catalog: true
      kin_score: 30.9
      mcp:
        status: none
      name: Adjust
      slug: adjust
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.paypal.android.p2pmobile/latest/
      status: profiled
      tags:
      - Analytics
      - Attribution
      - Deep Linking
      - Measurements
      tier: observed
      url: /providers/adjust/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Mifos Pay (openMF mobile-wallet)
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://raw.githubusercontent.com/openMF/mobile-wallet/dev/gradle/libs.versions.toml
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Wise
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook Login
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.transferwise.android/latest/
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: Turbo EA
      id: BC-4270.70
      key: software-marketplace-listing-management
      name: Software Marketplace Listing Management
      url: /capabilities/software-marketplace-listing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Mifos Mobile (openMF mifos-mobile)
      - Mifos Pay (openMF mobile-wallet)
      band: developing
      in_catalog: true
      kin_score: 51.3
      mcp:
        status: none
      name: Google Play (Integrity, In-App Review, In-App Update)
      slug: google-play
      sources:
      - https://raw.githubusercontent.com/openMF/mifos-mobile/dev/gradle/libs.versions.toml
      - https://raw.githubusercontent.com/openMF/mobile-wallet/dev/gradle/libs.versions.toml
      status: profiled
      tags:
      - Android
      - Application
      - Google Play
      - In-App Purchases
      tier: observed
      url: /providers/google-play/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Mifos Mobile (openMF mifos-mobile)
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps
      slug: google-maps
      sources:
      - https://raw.githubusercontent.com/openMF/mifos-mobile/dev/gradle/libs.versions.toml
      status: profiled
      tags:
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - PayPal
      band: developing
      in_catalog: true
      kin_score: 45.7
      mcp:
        status: none
      name: Qualtrics
      slug: qualtrics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.paypal.android.p2pmobile/latest/
      status: profiled
      tags:
      - Customer Experience
      - Employee Experience
      - Experience Management
      - Surveys
      tier: observed
      url: /providers/qualtrics/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.0
      apps:
      - PayPal
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        source: https://github.com/adobe/cq-quickstart-mcp-server
        status: verified
      name: Adobe Experience Cloud
      slug: adobe-experience-cloud
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.paypal.android.p2pmobile/latest/
      status: profiled
      tags:
      - Analytics
      - Customer Experience
      - Digital Marketing
      - Personalization
      tier: observed
      url: /providers/adobe-experience-cloud/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Mifos Mobile (openMF mifos-mobile)
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id001
      name: Firebase Cloud Messaging
      slug: google-firebase
      sources:
      - https://raw.githubusercontent.com/openMF/mifos-mobile/dev/gradle/libs.versions.toml
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-firebase/
  layer: common
summary:
  coverage_pct: 100.0
  declared_only: 15
  distinct_providers: 27
  in_catalog: 27
  mcp:
    documented: 1
    none: 15
    unchecked: 0
    verified: 10
  mcp_verified: 10
  mean_kin_score: 47.0
  observed: 12
  queued: 0
  reference_apps: 6
title: 'Mobile Banking & Payments Wallet: application blueprint'
---
