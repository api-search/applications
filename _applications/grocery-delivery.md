---
access: understanding
agent_layer:
- app: Instacart
  finding: Instacart runs its own Developer Platform / Connect APIs (catalog slug instacart); no MCP claim read here
  source: https://docs.instacart.com/connect/
  tier: declared
apps:
- anchor: ever-demand
  counts:
    declared: 0
    observed: 12
  evidence:
  - route: dependency manifest
    url: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
  - route: dependency manifest
    url: https://github.com/ever-co/ever-demand/blob/develop/packages/shop-mobile-ionic/package.json
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon CloudWatch
    provider: amazon-cloudwatch
    says: ships the Amazon CloudWatch SDK or integration code
    source: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
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
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://github.com/ever-co/ever-demand/blob/develop/packages/shop-mobile-ionic/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120
      key: location-mapping
      name: Location & Mapping
      url: /capabilities/location-mapping/
      via_parent: null
    credit: null
    layer: domain
    name: Google Maps
    provider: google-maps
    says: ships the Google Maps SDK or integration code
    source: https://github.com/ever-co/ever-demand/blob/develop/packages/shop-mobile-ionic/package.json
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
    source: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
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
    name: Intercom
    provider: intercom
    says: ships the Intercom SDK or integration code
    source: https://github.com/ever-co/ever-demand/blob/develop/packages/shop-mobile-ionic/package.json
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
    name: ipstack
    provider: ipstack
    says: ships the ipstack SDK or integration code
    source: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
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
    name: Mixpanel
    provider: mixpanel
    says: ships the Mixpanel SDK or integration code
    source: https://github.com/ever-co/ever-demand/blob/develop/packages/shop-mobile-ionic/package.json
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
    source: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
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
    source: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    credit: null
    layer: common
    name: Unleash
    provider: unleash
    says: ships the Unleash SDK or integration code
    source: https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
    tier: observed
  kind: self-hosted
  name: Ever Demand
  page: /applications/grocery-delivery/ever-demand/
  slug: ever-demand
  url: https://github.com/ever-co/ever-demand
- anchor: grocy
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: dependency manifest
    url: https://github.com/grocy/grocy/blob/master/composer.json
  - route: source code
    url: https://github.com/grocy/grocy/blob/master/config-dist.php
  - route: source code
    url: https://github.com/grocy/grocy/tree/master/plugins
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-130.30.10
      key: AE-130.30.10
      name: Food Composition Databases
      url: /capabilities/nutrition-food-data/
      via_parent: Nutrition & Food Data
    credit: null
    layer: domain
    name: Open Food Facts
    provider: open-food-facts
    says: ships the Open Food Facts SDK or integration code
    source: https://github.com/grocy/grocy/tree/master/plugins
    tier: observed
  kind: self-hosted
  name: Grocy
  page: /applications/grocery-delivery/grocy/
  slug: grocy
  url: https://github.com/grocy/grocy
- anchor: open-food-network
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: dependency manifest
    url: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
  - route: source code
    url: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/.env
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
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
    name: Bugsnag
    provider: bugsnag
    says: ships the Bugsnag SDK or integration code
    source: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.30
      key: AE-140.100.30
      name: Food Supply Chain Data Exchange
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    credit: null
    layer: domain
    name: Data Food Consortium
    provider: data-food-consortium
    says: ships the Data Food Consortium SDK or integration code
    source: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
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
    name: GNU Taler
    provider: gnu-taler
    says: ships the GNU Taler SDK or integration code
    source: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120
      key: location-mapping
      name: Location & Mapping
      url: /capabilities/location-mapping/
      via_parent: null
    credit: null
    layer: domain
    name: Google Maps
    provider: google-maps
    says: ships the Google Maps SDK or integration code
    source: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
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
    source: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
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
    source: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
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
    source: https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
    tier: observed
  kind: open-source-saas
  name: Open Food Network
  page: /applications/grocery-delivery/open-food-network/
  slug: open-food-network
  url: https://github.com/openfoodfoundation/openfoodnetwork
- anchor: instacart
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.instacart.client/latest/
  - route: documentation
    url: https://docs.instacart.com/connect/
  - route: store listing
    url: https://play.google.com/store/apps/details?id=com.instacart.client
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
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.instacart.client/latest/
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.instacart.client/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.instacart.client/latest/
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.instacart.client/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.instacart.client/latest/
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
    name: FullStory
    provider: fullstory
    says: ships the FullStory SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.instacart.client/latest/
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
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.instacart.client/latest/
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
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.instacart.client/latest/
    tier: observed
  kind: commercial
  name: Instacart
  page: /applications/grocery-delivery/instacart/
  slug: instacart
  url: https://www.instacart.com/
- anchor: shipt
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.shipt.groceries/latest/
  - route: store listing
    url: https://play.google.com/store/apps/details?id=com.shipt.groceries
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
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.shipt.groceries/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.shipt.groceries/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.shipt.groceries/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.shipt.groceries/latest/
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
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.shipt.groceries/latest/
    tier: observed
  kind: commercial
  name: Shipt
  page: /applications/grocery-delivery/shipt/
  slug: shipt
  url: https://www.shipt.com/
- anchor: picnic
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.picnic.android/latest/
  - route: store listing
    url: https://play.google.com/store/apps/details?id=com.picnic.android
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.picnic.android/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.picnic.android/latest/
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
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.picnic.android/latest/
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
    name: Snowplow
    provider: snowplow
    says: ships the Snowplow SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.picnic.android/latest/
    tier: observed
  kind: commercial
  name: Picnic
  page: /applications/grocery-delivery/picnic/
  slug: picnic
  url: https://picnic.app/
- anchor: weee!
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.sayweee.weee/latest/
  - route: store listing
    url: https://play.google.com/store/apps/details?id=com.sayweee.weee
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Airship (Urbanairship)
    provider: airship
    says: ships the Airship (Urbanairship) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sayweee.weee/latest/
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
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sayweee.weee/latest/
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sayweee.weee/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sayweee.weee/latest/
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sayweee.weee/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sayweee.weee/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sayweee.weee/latest/
    tier: observed
  kind: commercial
  name: Weee!
  page: /applications/grocery-delivery/weee/
  slug: weee
  url: https://www.sayweee.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: grocery-delivery
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Food & Drink
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Shopping
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Food & Drink
  store: google-play
  url: https://play.google.com/store/apps/category/FOOD_AND_DRINK
- category: Shopping
  store: google-play
  url: https://play.google.com/store/apps/category/SHOPPING
- category: Inventory Management
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#inventory-management
name: Grocery Delivery
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
  why: checkout payments (Stripe, PayPal, GNU Taler)
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: customer sign-in with Facebook / Google
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: product images and uploads in S3
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error, log and APM monitoring
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: common
  why: locating the shopper to pick a store / delivery zone
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  fit: exact
  layer: common
  why: feature toggles
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
    id: AE-120
    key: location-mapping
    name: Location & Mapping
    url: /capabilities/location-mapping/
    via_parent: null
  fit: exact
  layer: domain
  why: delivery address maps, store and courier tracking
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: in-app customer support chat
- capability:
    attribution: API Evangelist extension
    id: AE-130.30.10
    key: AE-130.30.10
    name: Food Composition Databases
    url: /capabilities/nutrition-food-data/
    via_parent: Nutrition & Food Data
  fit: exact
  layer: domain
  why: barcode lookup of grocery products against an open food database
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.30
    key: AE-140.100.30
    name: Food Supply Chain Data Exchange
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  fit: exact
  layer: domain
  why: 'Food Supply Chain Data Exchange: Data Food Consortium'
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.10
    key: AE-140.100.10
    name: Grocery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  fit: exact
  layer: domain
  why: grocery delivery marketplaces themselves (inferred candidates)
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-120
      key: location-mapping
      name: Location & Mapping
      url: /capabilities/location-mapping/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Ever Demand
      - Open Food Network
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps
      slug: google-maps
      sources:
      - https://github.com/ever-co/ever-demand/blob/develop/packages/shop-mobile-ionic/package.json
      - https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
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
      id: AE-130.30.10
      key: AE-130.30.10
      name: Food Composition Databases
      url: /capabilities/nutrition-food-data/
      via_parent: Nutrition & Food Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Grocy
      band: strong
      in_catalog: true
      kin_score: 66.2
      mcp:
        status: none
      name: Open Food Facts
      slug: open-food-facts
      sources:
      - https://github.com/grocy/grocy/tree/master/plugins
      status: profiled
      tags:
      - Food
      - Nutrition
      - Open Data
      - Product Data
      tier: observed
      url: /providers/open-food-facts/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.100.30
      key: AE-140.100.30
      name: Food Supply Chain Data Exchange
      url: /capabilities/quick-local-commerce/
      via_parent: Quick & Local Commerce
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Open Food Network
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        status: unchecked
      name: Data Food Consortium
      slug: data-food-consortium
      sources:
      - https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
      status: profiled
      tags:
      - Company
      - Food
      - Interoperability
      - Open Standard
      tier: observed
      url: /providers/data-food-consortium/
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
      - Instacart
      - Picnic
      - Shipt
      - Weee!
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.instacart.client/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.picnic.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.sayweee.weee/latest/
      status: profiled
      tags: &id002
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Instacart
      - Weee!
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id003
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.instacart.client/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.sayweee.weee/latest/
      status: profiled
      tags: &id004
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Instacart
      - Shipt
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.instacart.client/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.shipt.groceries/latest/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Ever Demand
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://github.com/ever-co/ever-demand/blob/develop/packages/shop-mobile-ionic/package.json
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - Ever Demand
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://github.com/ever-co/ever-demand/blob/develop/packages/shop-mobile-ionic/package.json
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
    - agent_band: agent-aware
      agent_readiness: 20.1
      apps:
      - Picnic
      band: developing
      in_catalog: true
      kin_score: 42.3
      mcp:
        source: https://github.com/snowplow/snowplow-cli
        status: verified
      name: Snowplow
      slug: snowplow
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.picnic.android/latest/
      status: profiled
      tags:
      - Analytics Platform
      - Behavioral Data
      - Data Collection
      - Data Engineering
      tier: observed
      url: /providers/snowplow/
    - agent_band: agent-ready
      agent_readiness: 30.0
      apps:
      - Instacart
      band: thin
      in_catalog: true
      kin_score: 37.4
      mcp:
        source: https://developer.fullstory.com/mcp/introduction/
        status: documented
      name: FullStory
      slug: fullstory
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.instacart.client/latest/
      status: profiled
      tags:
      - Behavioral Analytics
      - Digital Experience
      - Product Analytics
      - Session Replay
      tier: observed
      url: /providers/fullstory/
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
      - Ever Demand
      - Instacart
      - Picnic
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
      - https://reports.exodus-privacy.eu.org/en/reports/com.instacart.client/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.picnic.android/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Open Food Network
      - Shipt
      band: exemplar
      in_catalog: true
      kin_score: 76.3
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
      - https://reports.exodus-privacy.eu.org/en/reports/com.shipt.groceries/latest/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
    - agent_band: agent-native
      agent_readiness: 43.4
      apps:
      - Ever Demand
      band: exemplar
      in_catalog: true
      kin_score: 77.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon CloudWatch
      slug: amazon-cloudwatch
      sources:
      - https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - CloudWatch
      - Monitoring
      - Observability
      tier: observed
      url: /providers/amazon-cloudwatch/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Open Food Network
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Weee!
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id001
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.sayweee.weee/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Ever Demand
      - Instacart
      - Shipt
      - Weee!
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
      - https://reports.exodus-privacy.eu.org/en/reports/com.instacart.client/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.sayweee.weee/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Ever Demand
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Instacart
      - Shipt
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.instacart.client/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.shipt.groceries/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - Weee!
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.sayweee.weee/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Picnic
      band: thin
      in_catalog: true
      kin_score: 30.9
      mcp:
        status: none
      name: Adjust
      slug: adjust
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.picnic.android/latest/
      status: profiled
      tags:
      - Analytics
      - Attribution
      - Deep Linking
      - Measurements
      tier: observed
      url: /providers/adjust/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Ever Demand
      - Open Food Network
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
      - https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Open Food Network
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Open Food Network
      band: thin
      in_catalog: true
      kin_score: 28.0
      mcp:
        status: unknown
      name: GNU Taler
      slug: gnu-taler
      sources:
      - https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
      status: profiled
      tags:
      - Ecash
      - Finance
      - Open Source
      - Payments
      tier: observed
      url: /providers/gnu-taler/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Instacart
      - Weee!
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.instacart.client/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.sayweee.weee/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Ever Demand
      - Open Food Network
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
      - https://github.com/openfoodfoundation/openfoodnetwork/blob/master/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Ever Demand
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://github.com/ever-co/ever-demand/blob/develop/packages/shop-mobile-ionic/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: observed
      url: /providers/intercom/
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.4
      apps:
      - Ever Demand
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        source: https://github.com/Unleash/unleash-mcp
        status: verified
      name: Unleash
      slug: unleash
      sources:
      - https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
      status: profiled
      tags:
      - A/B Testing
      - Feature Flags
      - Feature Management
      - Progressive Delivery
      tier: observed
      url: /providers/unleash/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.0
      apps:
      - Ever Demand
      band: developing
      in_catalog: true
      kin_score: 43.3
      mcp:
        status: none
      name: ipstack
      slug: ipstack
      sources:
      - https://github.com/ever-co/ever-demand/blob/develop/packages/core/package.json
      status: profiled
      tags:
      - Geocoding
      - IP Geolocation
      - Location
      - Threat Intelligence
      tier: observed
      url: /providers/ipstack/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Weee!
      band: thin
      in_catalog: true
      kin_score: 28.3
      mcp:
        source: https://github.com/urbanairship/agent-tools
        status: verified
      name: Airship (Urbanairship)
      slug: airship
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.sayweee.weee/latest/
      status: profiled
      tags:
      - Email
      - Mobile
      - Notification
      - Push
      tier: observed
      url: /providers/airship/
  layer: common
summary:
  coverage_pct: 100.0
  declared_only: 0
  distinct_providers: 26
  in_catalog: 26
  mcp:
    documented: 1
    none: 7
    unchecked: 1
    verified: 16
  mcp_verified: 16
  mean_kin_score: 54.8
  observed: 26
  queued: 0
  reference_apps: 7
title: 'Grocery Delivery: application blueprint'
---
