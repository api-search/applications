---
access: understanding
agent_layer: []
apps:
- anchor: nakama
  counts:
    declared: 0
    observed: 10
  evidence:
  - route: dependency manifest
    url: https://github.com/heroiclabs/nakama/blob/master/go.mod
  - route: source code
    url: https://github.com/heroiclabs/nakama/blob/master/iap/iap.go
  - route: source code
    url: https://github.com/heroiclabs/nakama/blob/master/iap/iap_samsung.go
  - route: source code
    url: https://github.com/heroiclabs/nakama/blob/master/social/social.go
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: domain
    name: App Store receipt validation (verifyReceipt)
    provider: apple
    says: ships the App Store receipt validation (verifyReceipt) SDK or integration code
    source: https://github.com/heroiclabs/nakama/blob/master/iap/iap.go
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: domain
    name: Facebook Instant Games purchases
    provider: facebook
    says: ships the Facebook Instant Games purchases SDK or integration code
    source: https://github.com/heroiclabs/nakama/blob/master/iap/iap.go
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Facebook Login / Graph friends / Limited Login
    provider: facebook
    says: ships the Facebook Login / Graph friends / Limited Login SDK or integration code
    source: https://github.com/heroiclabs/nakama/blob/master/social/social.go
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.30
      key: AE-180.30
      name: Player Engagement
      url: /capabilities/player-engagement/
      via_parent: null
    credit: null
    layer: domain
    name: Google Play Games Services (games/v1/players/me)
    provider: google-play-games
    says: ships the Google Play Games Services (games/v1/players/me) SDK or integration code
    source: https://github.com/heroiclabs/nakama/blob/master/social/social.go
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: domain
    name: Google Play purchases/subscriptions validation (androidpublisher v3)
    provider: google-play
    says: ships the Google Play purchases/subscriptions validation (androidpublisher v3) SDK or integration code
    source: https://github.com/heroiclabs/nakama/blob/master/iap/iap.go
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Google sign-in (ID token check)
    provider: google-identity-platform
    says: ships the Google sign-in (ID token check) SDK or integration code
    source: https://github.com/heroiclabs/nakama/blob/master/social/social.go
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: domain
    name: Huawei IAP (HMS Core order service)
    provider: huawei-mobile-services
    says: ships the Huawei IAP (HMS Core order service) SDK or integration code
    source: https://github.com/heroiclabs/nakama/blob/master/iap/iap.go
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: domain
    name: Samsung IAP server API
    provider: samsung
    says: ships the Samsung IAP server API SDK or integration code
    source: https://github.com/heroiclabs/nakama/blob/master/iap/iap_samsung.go
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Sign in with Apple + Game Center identity
    provider: apple
    says: ships the Sign in with Apple + Game Center identity SDK or integration code
    source: https://github.com/heroiclabs/nakama/blob/master/social/social.go
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: 'Steam (Steamworks partner API: AuthenticateUserTicket, GetFriendList)'
    provider: steam
    says: 'ships the Steam (Steamworks partner API: AuthenticateUserTicket, GetFriendList) SDK or integration code'
    source: https://github.com/heroiclabs/nakama/blob/master/social/social.go
    tier: observed
  kind: self-hosted
  name: Nakama
  page: /applications/mobile-games/nakama/
  slug: nakama
  url: https://github.com/heroiclabs/nakama
- anchor: talo
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: dependency manifest
    url: https://github.com/TaloDev/backend/blob/develop/package.json
  - route: source code
    url: https://github.com/TaloDev/backend/blob/develop/envs/.env.dev
  - route: source code
    url: https://github.com/TaloDev/backend/tree/develop/src/lib/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-180.30
      key: AE-180.30
      name: Player Engagement
      url: /capabilities/player-engagement/
      via_parent: null
    credit: null
    layer: domain
    name: Game Center
    provider: apple
    says: ships the Game Center SDK or integration code
    source: https://github.com/TaloDev/backend/tree/develop/src/lib/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.30
      key: AE-180.30
      name: Player Engagement
      url: /capabilities/player-engagement/
      via_parent: null
    credit: null
    layer: domain
    name: Google Play Games
    provider: google-play-games
    says: ships the Google Play Games SDK or integration code
    source: https://github.com/TaloDev/backend/tree/develop/src/lib/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: hCaptcha
    provider: hcaptcha
    says: ships the hCaptcha SDK or integration code
    source: https://github.com/TaloDev/backend/blob/develop/envs/.env.dev
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
    name: HyperDX (@hyperdx/node-opentelemetry)
    provider: hyperdx
    says: ships the HyperDX (@hyperdx/node-opentelemetry) SDK or integration code
    source: https://github.com/TaloDev/backend/blob/develop/package.json
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
    name: Sentry (@sentry/node)
    provider: sentry-system
    says: ships the Sentry (@sentry/node) SDK or integration code
    source: https://github.com/TaloDev/backend/blob/develop/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.30
      key: AE-180.30
      name: Player Engagement
      url: /capabilities/player-engagement/
      via_parent: null
    credit: null
    layer: domain
    name: Steamworks (leaderboards, stats, players)
    provider: steam
    says: ships the Steamworks (leaderboards, stats, players) SDK or integration code
    source: https://github.com/TaloDev/backend/tree/develop/src/lib/integrations
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
    name: Stripe (Talo plan billing)
    provider: stripe
    says: ships the Stripe (Talo plan billing) SDK or integration code
    source: https://github.com/TaloDev/backend/blob/develop/package.json
    tier: observed
  kind: self-hosted
  name: Talo
  page: /applications/mobile-games/talo/
  slug: talo
  url: https://github.com/TaloDev/backend
- anchor: unciv
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://github.com/yairm210/Unciv/blob/master/gradle/libs.versions.toml
  - route: source code
    url: https://github.com/yairm210/Unciv/blob/master/core/src/com/unciv/logic/github/GithubAPI.kt
  - route: source code
    url: https://github.com/yairm210/Unciv/blob/master/core/src/com/unciv/logic/multiplayer/storage/DropBox.kt
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-180.30.10
      key: AE-180.30.10
      name: Rich Presence & Player Status
      url: /capabilities/player-engagement/
      via_parent: Player Engagement
    credit: null
    layer: domain
    name: Discord Rich Presence (java-discord-rpc)
    provider: discord
    says: ships the Discord Rich Presence (java-discord-rpc) SDK or integration code
    source: https://github.com/yairm210/Unciv/blob/master/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Dropbox (multiplayer turn files)
    provider: dropbox
    says: ships the Dropbox (multiplayer turn files) SDK or integration code
    source: https://github.com/yairm210/Unciv/blob/master/core/src/com/unciv/logic/multiplayer/storage/DropBox.kt
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.40.10
      key: AE-180.40.10
      name: Mods & User-Generated Content Distribution
      url: /capabilities/game-publishing-distribution/
      via_parent: Game Publishing & Distribution
    credit: null
    layer: domain
    name: GitHub (mod discovery + download)
    provider: github
    says: ships the GitHub (mod discovery + download) SDK or integration code
    source: https://github.com/yairm210/Unciv/blob/master/core/src/com/unciv/logic/github/GithubAPI.kt
    tier: observed
  kind: self-hosted
  name: Unciv
  page: /applications/mobile-games/unciv/
  slug: unciv
  url: https://github.com/yairm210/Unciv
- anchor: mindustry
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://github.com/Anuken/Mindustry/blob/master/build.gradle
  - route: source code
    url: https://github.com/Anuken/Mindustry/blob/master/core/src/mindustry/Vars.java
  - route: source code
    url: https://github.com/Anuken/Mindustry/blob/master/core/src/mindustry/ui/dialogs/ModsDialog.java
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-180.30.10
      key: AE-180.30.10
      name: Rich Presence & Player Status
      url: /capabilities/player-engagement/
      via_parent: Player Engagement
    credit: null
    layer: domain
    name: Discord Rich Presence
    provider: discord
    says: ships the Discord Rich Presence SDK or integration code
    source: https://github.com/Anuken/Mindustry/blob/master/build.gradle
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.40.10
      key: AE-180.40.10
      name: Mods & User-Generated Content Distribution
      url: /capabilities/game-publishing-distribution/
      via_parent: Game Publishing & Distribution
    credit: null
    layer: domain
    name: GitHub (mod browser)
    provider: github
    says: ships the GitHub (mod browser) SDK or integration code
    source: https://github.com/Anuken/Mindustry/blob/master/core/src/mindustry/ui/dialogs/ModsDialog.java
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3740.30
      key: content-delivery-network-operations
      name: Content Delivery Network Operations
      url: /capabilities/content-delivery-network-operations/
      via_parent: null
    credit: null
    layer: common
    name: jsDelivr (mod index, server lists)
    provider: jsdelivr
    says: ships the jsDelivr (mod index, server lists) SDK or integration code
    source: https://github.com/Anuken/Mindustry/blob/master/core/src/mindustry/Vars.java
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.40
      key: AE-180.40
      name: Game Publishing & Distribution
      url: /capabilities/game-publishing-distribution/
      via_parent: null
    credit: null
    layer: domain
    name: Steamworks (steamworks4j; Steam build)
    provider: steam
    says: ships the Steamworks (steamworks4j; Steam build) SDK or integration code
    source: https://github.com/Anuken/Mindustry/blob/master/build.gradle
    tier: observed
  kind: self-hosted
  name: Mindustry
  page: /applications/mobile-games/mindustry/
  slug: mindustry
  url: https://github.com/Anuken/Mindustry
- anchor: lichess-mobile
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: dependency manifest
    url: https://github.com/lichess-org/mobile/blob/main/pubspec.yaml
  integrations:
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
    source: https://github.com/lichess-org/mobile/blob/main/pubspec.yaml
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
    name: Firebase Crashlytics
    provider: firebase
    says: ships the Firebase Crashlytics SDK or integration code
    source: https://github.com/lichess-org/mobile/blob/main/pubspec.yaml
    tier: observed
  kind: open-source-saas
  name: Lichess mobile
  page: /applications/mobile-games/lichess-mobile/
  slug: lichess-mobile
  url: https://github.com/lichess-org/mobile
- anchor: clash-of-clans
  counts:
    declared: 44
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.supercell.clashofclans/latest/
  - route: documentation
    url: https://supercell.com/en/partner-opt-out/
  - route: documentation
    url: https://supercell.com/en/privacy-policy/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: AppsFlyer (attribution, processor)
    provider: appsflyer
    says: ships the AppsFlyer (attribution, processor) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.supercell.clashofclans/latest/
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
    name: Google Firebase
    provider: firebase
    says: ships the Google Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.supercell.clashofclans/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Helpshift (in-game support)
    provider: helpshift
    says: ships the Helpshift (in-game support) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.supercell.clashofclans/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.supercell.clashofclans/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.supercell.clashofclans/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: AdAction
    provider: adaction
    says: lists AdAction as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Adikteev (retargeting)
    provider: adikteev
    says: lists Adikteev (retargeting) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: adjoe (playtime rewards)
    provider: adjoe
    says: lists adjoe (playtime rewards) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Amazon Ads
    provider: amazon
    says: lists Amazon Ads as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: AMoAd (CyberAgent)
    provider: amoad
    says: lists AMoAd (CyberAgent) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Apple Search Ads
    provider: apple
    says: lists Apple Search Ads as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: AppLovin
    provider: applovin
    says: lists AppLovin as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: DirecTV (advertising)
    provider: directv
    says: lists DirecTV (advertising) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.10
      key: AE-170.50.10
      name: Online Communities
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    credit: null
    layer: domain
    name: Discord
    provider: discord
    says: lists Discord as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Dynalyst (CyberAgent retargeting DSP)
    provider: dynalyst
    says: lists Dynalyst (CyberAgent retargeting DSP) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Facebook (ads / pixel)
    provider: facebook
    says: lists Facebook (ads / pixel) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: Fyber (Digital Turbine)
    provider: fyber
    says: lists Fyber (Digital Turbine) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: Google (ads partner, product unnamed)
    provider: google
    says: lists Google (ads partner, product unnamed) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: Google AdSense
    provider: google-adsense
    says: lists Google AdSense as an integration
    source: https://supercell.com/en/partner-opt-out/
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
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: Google reCAPTCHA
    provider: google-recaptcha
    says: lists Google reCAPTCHA as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: null
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: lists Google Tag Manager as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Influence Mobile
    provider: influence-mobile
    says: lists Influence Mobile as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: ironSource
    provider: ironsource
    says: lists ironSource as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Kakao (account linking + partner)
    provider: kakao
    says: lists Kakao (account linking + partner) as an integration
    source: https://supercell.com/en/privacy-policy/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Liftoff (mobile app marketing)
    provider: liftoff-io
    says: lists Liftoff (mobile app marketing) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: LINE (account linking + partner)
    provider: line
    says: lists LINE (account linking + partner) as an integration
    source: https://supercell.com/en/privacy-policy/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: Mintegral
    provider: mintegral
    says: lists Mintegral as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Mistplay (rewarded play UA)
    provider: mistplay
    says: lists Mistplay (rewarded play UA) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Moloco
    provider: moloco
    says: lists Moloco as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Naver (ads)
    provider: naver
    says: lists Naver (ads) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: QQ (Tencent)
    provider: tencent
    says: lists QQ (Tencent) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Reddit
    provider: reddit
    says: lists Reddit as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: remerge (retargeting DSP)
    provider: remerge
    says: lists remerge (retargeting DSP) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Skyflag (offerwall)
    provider: skyflag
    says: lists Skyflag (offerwall) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: SmartNews (ads)
    provider: smartnews
    says: lists SmartNews (ads) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Snap
    provider: snapchat
    says: lists Snap as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Spotify (ads)
    provider: spotify
    says: lists Spotify (ads) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: StreamElements (creator sponsorships)
    provider: streamelements
    says: lists StreamElements (creator sponsorships) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-180.40
      key: AE-180.40
      name: Game Publishing & Distribution
      url: /capabilities/game-publishing-distribution/
      via_parent: null
    credit: null
    layer: domain
    name: Supersonic (Unity/ironSource publishing)
    provider: supersonic
    says: lists Supersonic (Unity/ironSource publishing) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: Tapjoy (offerwall)
    provider: tapjoy
    says: lists Tapjoy (offerwall) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: TikTok
    provider: tiktok
    says: lists TikTok as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: tvScientific (CTV)
    provider: tvscientific
    says: lists tvScientific (CTV) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Twitter
    provider: x
    says: lists Twitter as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: Unity Technologies / Unity Ads
    provider: unity
    says: lists Unity Technologies / Unity Ads as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.50
      key: AE-160.50
      name: Consent & Preferences
      url: /capabilities/consent-preferences/
      via_parent: null
    credit: null
    layer: common
    name: Usercentrics (CMP)
    provider: usercentrics
    says: lists Usercentrics (CMP) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Vibe (vibe.co, streaming TV ads)
    provider: vibe-co
    says: lists Vibe (vibe.co, streaming TV ads) as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: Vungle
    provider: vungle
    says: lists Vungle as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Zucks
    provider: zucks
    says: lists Zucks as an integration
    source: https://supercell.com/en/partner-opt-out/
    tier: declared
  kind: commercial
  name: Clash of Clans
  page: /applications/mobile-games/clash-of-clans/
  slug: clash-of-clans
  url: https://supercell.com/en/games/clashofclans/
- anchor: candy-crush-saga
  counts:
    declared: 3
    observed: 12
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
  - route: documentation
    url: https://www.king.com/cookies/
  - route: documentation
    url: https://www.king.com/privacyPolicy
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Amazon Advertisement
    provider: amazon
    says: ships the Amazon Advertisement SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: AppLovin (MAX and SparkLabs)
    provider: applovin
    says: ships the AppLovin (MAX and SparkLabs) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Chartboost
    provider: chartboost
    says: ships the Chartboost SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook Ads
    provider: facebook
    says: ships the Facebook Ads SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
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
    name: Facebook Analytics
    provider: facebook
    says: ships the Facebook Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Facebook login + social play
    provider: facebook
    says: ships the Facebook login + social play SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google AdMob
    provider: google-admob
    says: ships the Google AdMob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: IAB Open Measurement
    provider: iab-tech-lab
    says: ships the IAB Open Measurement SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: ironSource
    provider: ironsource
    says: ships the ironSource SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: PubNative
    provider: pubnative
    says: ships the PubNative SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Unity3d Ads
    provider: unity
    says: ships the Unity3d Ads SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
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
    name: Google Analytics (websites)
    provider: google-analytics
    says: lists Google Analytics (websites) as an integration
    source: https://www.king.com/privacyPolicy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Sign in with Apple
    provider: apple
    says: lists Sign in with Apple as an integration
    source: https://www.king.com/privacyPolicy
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
    name: Zendesk (King Care help centre, kingcare.zendesk.com)
    provider: zendesk
    says: lists Zendesk (King Care help centre, kingcare.zendesk.com) as an integration
    source: https://www.king.com/privacyPolicy
    tier: declared
  kind: commercial
  name: Candy Crush Saga
  page: /applications/mobile-games/candy-crush-saga/
  slug: candy-crush-saga
  url: https://www.king.com/game/candycrush
- anchor: subway-surfers
  counts:
    declared: 7
    observed: 22
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
  - route: documentation
    url: https://sybogames.com/privacy-policy/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Amazon Advertisement
    provider: amazon
    says: ships the Amazon Advertisement SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: AppLovin (MAX and SparkLabs)
    provider: applovin
    says: ships the AppLovin (MAX and SparkLabs) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Appodeal Stack
    provider: appodeal
    says: ships the Appodeal Stack SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: BidMachine
    provider: bidmachine-io
    says: ships the BidMachine SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Chartboost
    provider: chartboost
    says: ships the Chartboost SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook Ads
    provider: facebook
    says: ships the Facebook Ads SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    name: Facebook Analytics
    provider: facebook
    says: ships the Facebook Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Facebook login
    provider: facebook
    says: ships the Facebook login SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    name: Firebase Analytics
    provider: firebase
    says: ships the Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Fyber
    provider: fyber
    says: ships the Fyber SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google AdMob
    provider: google-admob
    says: ships the Google AdMob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    name: Google CrashLytics
    provider: firebase
    says: ships the Google CrashLytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Helpshift
    provider: helpshift
    says: ships the Helpshift SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: IAB Open Measurement
    provider: iab-tech-lab
    says: ships the IAB Open Measurement SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: InMobi
    provider: inmobi
    says: ships the InMobi SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: ironSource LevelPlay (mediation)
    provider: ironsource
    says: ships the ironSource LevelPlay (mediation) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Mintegral
    provider: mintegral
    says: ships the Mintegral SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Pangle (ByteDance)
    provider: pangle
    says: ships the Pangle (ByteDance) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: PubNative
    provider: pubnative
    says: ships the PubNative SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: SuperAwesome
    provider: superawesome
    says: ships the SuperAwesome SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Unity3d Ads
    provider: unity
    says: ships the Unity3d Ads SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: Google Ad Manager (mediation)
    provider: google-ad-manager
    says: lists Google Ad Manager (mediation) as an integration
    source: https://sybogames.com/privacy-policy/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: maio
    provider: maio
    says: lists maio as an integration
    source: https://sybogames.com/privacy-policy/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: Moloco
    provider: moloco
    says: lists Moloco as an integration
    source: https://sybogames.com/privacy-policy/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: myTarget
    provider: mytarget
    says: lists myTarget as an integration
    source: https://sybogames.com/privacy-policy/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: Smaato
    provider: smaato
    says: lists Smaato as an integration
    source: https://sybogames.com/privacy-policy/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: Tapjoy
    provider: tapjoy
    says: lists Tapjoy as an integration
    source: https://sybogames.com/privacy-policy/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: Yandex Ads
    provider: yandex-ads
    says: lists Yandex Ads as an integration
    source: https://sybogames.com/privacy-policy/
    tier: declared
  kind: commercial
  name: Subway Surfers
  page: /applications/mobile-games/subway-surfers/
  slug: subway-surfers
  url: https://sybogames.com/games/subway-surfers/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: mobile-games
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Games
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Games
  store: google-play
  url: https://play.google.com/store/apps/category/GAME
- category: Games
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#games
name: Mobile & Casual Games (live-ops backend)
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: domain
  why: Players sign in with platform and social accounts and import friends (Facebook, Apple/Game Center, Google, Steam, LINE, Kakao).
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: exact
  layer: domain
  why: Server-side receipt validation for every app store a game ships to.
- capability:
    attribution: API Evangelist extension
    id: AE-180.30
    key: AE-180.30
    name: Player Engagement
    url: /capabilities/player-engagement/
    via_parent: null
  fit: exact
  layer: domain
  why: Leaderboards, stats and achievements synced to platform services; rich presence.
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: Billing for the backend service itself.
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: Crash and error reporting.
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: Bot protection on sign-up / web surfaces.
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: Cloud-drive storage of shared game files.
- capability:
    attribution: API Evangelist extension
    id: AE-180.40
    key: AE-180.40
    name: Game Publishing & Distribution
    url: /capabilities/game-publishing-distribution/
    via_parent: null
  fit: exact
  layer: domain
  why: Distribution on a store platform (Steam) and mod/UGC distribution.
- capability:
    attribution: Turbo EA
    id: BC-3740.30
    key: content-delivery-network-operations
    name: Content Delivery Network Operations
    url: /capabilities/content-delivery-network-operations/
    via_parent: null
  fit: exact
  layer: common
  why: CDN for mod indexes and server lists.
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: Push notifications for turn / challenge alerts.
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: domain
  why: Install attribution for paid user acquisition.
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: Gameplay and funnel analytics.
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: domain
  why: Ad mediation and ad networks are the free-to-play revenue line.
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: Tag management on game websites.
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: exact
  layer: domain
  why: Paid user acquisition across DSPs, social, CTV and offerwalls.
- capability:
    attribution: API Evangelist extension
    id: AE-160.50
    key: AE-160.50
    name: Consent & Preferences
    url: /capabilities/consent-preferences/
    via_parent: null
  fit: exact
  layer: common
  why: Consent management for ad SDKs (GDPR/IDFA).
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: In-game player support.
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.10
    key: AE-170.50.10
    name: Online Communities
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  fit: nearest
  layer: domain
  why: Community platform partner.
- capability:
    attribution: Turbo EA
    id: BC-3760.30
    key: programmatic-sales-management
    name: Programmatic Sales Management
    url: /capabilities/programmatic-sales-management/
    via_parent: null
  fit: nearest
  layer: common
  why: ad viewability measurement SDK seen in the Android builds
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - Clash of Clans
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: Twitter
      slug: x
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: declared
      url: /providers/x/
    - agent_band: agent-native
      agent_readiness: 57.8
      apps:
      - Clash of Clans
      band: exemplar
      in_catalog: true
      kin_score: 71.5
      mcp: &id001
        source: https://developer.moloco.cloud/docs/mcp-getting-started
        status: verified
      name: Moloco
      slug: moloco
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags: &id002
      - AdTech
      - Advertising
      - DSP
      - Retail Media
      tier: declared
      url: /providers/moloco/
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Clash of Clans
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Snap
      slug: snapchat
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Advertising
      - Augmented Reality
      - Marketing
      - Messaging
      tier: declared
      url: /providers/snapchat/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Clash of Clans
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/reddit/devvit-mcp
        status: verified
      name: Reddit
      slug: reddit
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Advertising
      - Community
      - Content
      - Reddit
      tier: declared
      url: /providers/reddit/
    - agent_band: agent-native
      agent_readiness: 53.6
      apps:
      - Clash of Clans
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp: &id013
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Amazon Ads
      slug: amazon
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags: &id014
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: declared
      url: /providers/amazon/
    - agent_band: agent-ready
      agent_readiness: 31.2
      apps:
      - Clash of Clans
      band: developing
      in_catalog: true
      kin_score: 54.2
      mcp:
        status: none
      name: SmartNews (ads)
      slug: smartnews
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Advertising
      - Company
      - Consumer
      - News
      tier: declared
      url: /providers/smartnews/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Clash of Clans
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp: &id005
        status: none
      name: Apple Search Ads
      slug: apple
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags: &id006
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - Clash of Clans
      band: developing
      in_catalog: true
      kin_score: 50.6
      mcp:
        status: none
      name: Spotify (ads)
      slug: spotify
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Audio
      - Music
      - Podcasts
      - Streaming
      tier: declared
      url: /providers/spotify/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Clash of Clans
      band: developing
      in_catalog: true
      kin_score: 47.6
      mcp:
        status: none
      name: remerge (retargeting DSP)
      slug: remerge
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Mobile
      tier: declared
      url: /providers/remerge/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Clash of Clans
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id003
        status: none
      name: Facebook (ads / pixel)
      slug: facebook
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags: &id004
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: declared
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Clash of Clans
      band: developing
      in_catalog: true
      kin_score: 40.5
      mcp:
        status: none
      name: TikTok
      slug: tiktok
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Advertising
      - Commerce
      - Content
      - TikTok
      tier: declared
      url: /providers/tiktok/
    - agent_band: agent-aware
      agent_readiness: 5.3
      apps:
      - Clash of Clans
      band: emerging
      in_catalog: true
      kin_score: 24.9
      mcp:
        status: none
      name: tvScientific (CTV)
      slug: tvscientific
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Advertising
      - CTV
      - Company
      - Connected TV
      tier: declared
      url: /providers/tvscientific/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Clash of Clans
      band: emerging
      in_catalog: true
      kin_score: 17.6
      mcp:
        status: unknown
      name: Influence Mobile
      slug: influence-mobile
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Advertising
      - Data Platform
      - Mobile Gaming
      - Player Acquisition
      tier: declared
      url: /providers/influence-mobile/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Clash of Clans
      band: emerging
      in_catalog: true
      kin_score: 15.3
      mcp:
        status: none
      name: Liftoff (mobile app marketing)
      slug: liftoff-io
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Advertising
      - Artificial Intelligence
      - Company
      - Mobile
      tier: declared
      url: /providers/liftoff-io/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Clash of Clans
      band: emerging
      in_catalog: true
      kin_score: 13.7
      mcp:
        status: none
      name: adjoe (playtime rewards)
      slug: adjoe
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Advertising
      - Loyalty
      - Mobile Gaming
      - Monetization
      tier: declared
      url: /providers/adjoe/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Clash of Clans
      band: emerging
      in_catalog: true
      kin_score: 11.8
      mcp:
        status: none
      name: Adikteev (retargeting)
      slug: adikteev
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Advertising
      - Company
      - Mobile
      - Retargeting
      tier: declared
      url: /providers/adikteev/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Clash of Clans
      band: emerging
      in_catalog: true
      kin_score: 11.4
      mcp:
        status: none
      name: Mistplay (rewarded play UA)
      slug: mistplay
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Gaming
      - Gift Cards
      - Mobile
      - Rewards
      tier: declared
      url: /providers/mistplay/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Clash of Clans
      band: minimal
      in_catalog: true
      kin_score: 10.6
      mcp:
        status: none
      name: Naver (ads)
      slug: naver
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Cloud Platform
      - Maps
      - Search
      - Translation
      tier: declared
      url: /providers/naver/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Clash of Clans
      band: minimal
      in_catalog: true
      kin_score: 7.7
      mcp:
        status: none
      name: AdAction
      slug: adaction
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Advertising
      - Company
      - Mobile
      - Monetization
      tier: declared
      url: /providers/adaction/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Clash of Clans
      band: minimal
      in_catalog: true
      kin_score: 5.7
      mcp:
        status: none
      name: Dynalyst (CyberAgent retargeting DSP)
      slug: dynalyst
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Advertising
      - Company
      - DSP
      - Mobile
      tier: declared
      url: /providers/dynalyst/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Clash of Clans
      band: minimal
      in_catalog: true
      kin_score: 3.7
      mcp:
        status: none
      name: Zucks
      slug: zucks
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/zucks/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Clash of Clans
      band: minimal
      in_catalog: true
      kin_score: 3.3
      mcp:
        status: none
      name: DirecTV (advertising)
      slug: directv
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Entertainment
      - Media
      - Satellite
      - Television
      tier: declared
      url: /providers/directv/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Clash of Clans
      band: minimal
      in_catalog: true
      kin_score: 2.5
      mcp:
        status: none
      name: AMoAd (CyberAgent)
      slug: amoad
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/amoad/
    - agent_band: null
      agent_readiness: null
      apps:
      - Clash of Clans
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Skyflag (offerwall)
      slug: skyflag
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Clash of Clans
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Vibe (vibe.co, streaming TV ads)
      slug: vibe-co
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Clash of Clans
      - Subway Surfers
      band: emerging
      in_catalog: true
      kin_score: 16.2
      mcp:
        status: unknown
      name: Mintegral
      slug: mintegral
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Advertising
      - Artificial Intelligence
      - Company
      - Mobile Marketing
      tier: observed
      url: /providers/mintegral/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Clash of Clans
      - Subway Surfers
      band: minimal
      in_catalog: true
      kin_score: 10.2
      mcp: &id017
        status: none
      name: ironSource
      slug: ironsource
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags: &id018
      - Advertising
      - Game Development
      - Mobile
      - Mobile Games
      tier: observed
      url: /providers/ironsource/
    - agent_band: null
      agent_readiness: null
      apps:
      - Clash of Clans
      - Subway Surfers
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Fyber (Digital Turbine)
      slug: fyber
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      - https://supercell.com/en/partner-opt-out/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Clash of Clans
      - Subway Surfers
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Tapjoy (offerwall)
      slug: tapjoy
      sources:
      - https://supercell.com/en/partner-opt-out/
      - https://sybogames.com/privacy-policy/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: agent-aware
      agent_readiness: 7.7
      apps:
      - Subway Surfers
      band: developing
      in_catalog: true
      kin_score: 46.1
      mcp:
        status: none
      name: InMobi
      slug: inmobi
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Enterprise
      tier: observed
      url: /providers/inmobi/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Subway Surfers
      band: emerging
      in_catalog: true
      kin_score: 14.1
      mcp:
        status: none
      name: Pangle (ByteDance)
      slug: pangle
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      status: profiled
      tags:
      - Advertising
      - Mobile
      - Monetization
      - TikTok
      tier: observed
      url: /providers/pangle/
    - agent_band: agent-native
      agent_readiness: 57.8
      apps:
      - Subway Surfers
      band: exemplar
      in_catalog: true
      kin_score: 71.5
      mcp: *id001
      name: Moloco
      slug: moloco
      sources:
      - https://sybogames.com/privacy-policy/
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/moloco/
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - Clash of Clans
      band: exemplar
      in_catalog: true
      kin_score: 68.9
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google (ads partner, product unnamed)
      slug: google
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: declared
      url: /providers/google/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Clash of Clans
      band: exemplar
      in_catalog: true
      kin_score: 66.5
      mcp: &id011
        source: https://github.com/Unity-Technologies/industry-ai-workflows
        status: verified
      name: Unity Technologies / Unity Ads
      slug: unity
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags: &id012
      - Game Development
      - Game Services
      - Multiplayer
      - Real-Time 3D
      tier: declared
      url: /providers/unity/
    - agent_band: agent-ready
      agent_readiness: 36.1
      apps:
      - Subway Surfers
      band: strong
      in_catalog: true
      kin_score: 56.4
      mcp:
        source: https://developers.google.com/ad-manager/api/beta/mcp-server
        status: verified
      name: Google Ad Manager (mediation)
      slug: google-ad-manager
      sources:
      - https://sybogames.com/privacy-policy/
      status: profiled
      tags:
      - Ad Manager
      - Ad Operations
      - Ad Serving
      - Creative
      tier: declared
      url: /providers/google-ad-manager/
    - agent_band: agent-native
      agent_readiness: 40.5
      apps:
      - Clash of Clans
      band: developing
      in_catalog: true
      kin_score: 53.7
      mcp:
        status: none
      name: Google AdSense
      slug: google-adsense
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Ad Units
      - AdSense
      - Advertising
      - Monetization
      tier: declared
      url: /providers/google-adsense/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Clash of Clans
      band: developing
      in_catalog: true
      kin_score: 41.0
      mcp:
        status: none
      name: Vungle
      slug: vungle
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Advertising
      - Company
      - Mobile
      - Monetization
      tier: declared
      url: /providers/vungle/
    - agent_band: agent-ready
      agent_readiness: 35.5
      apps:
      - Clash of Clans
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp: &id015
        status: none
      name: AppLovin
      slug: applovin
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags: &id016
      - AdTech
      - Advertising
      - App Monetization
      - Mobile
      tier: declared
      url: /providers/applovin/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Subway Surfers
      band: emerging
      in_catalog: true
      kin_score: 13.2
      mcp:
        status: none
      name: Yandex Ads
      slug: yandex-ads
      sources:
      - https://sybogames.com/privacy-policy/
      status: profiled
      tags:
      - Advertising
      - App Monetization
      - User Acquisition
      - Web Analytics
      tier: declared
      url: /providers/yandex-ads/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Subway Surfers
      band: minimal
      in_catalog: true
      kin_score: 1.7
      mcp:
        status: none
      name: maio
      slug: maio
      sources:
      - https://sybogames.com/privacy-policy/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/maio/
    - agent_band: null
      agent_readiness: null
      apps:
      - Subway Surfers
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: myTarget
      slug: mytarget
      sources:
      - https://sybogames.com/privacy-policy/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Subway Surfers
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Smaato
      slug: smaato
      sources:
      - https://sybogames.com/privacy-policy/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
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
      - Candy Crush Saga
      - Nakama
      - Subway Surfers
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook Login / Graph friends / Limited Login
      slug: facebook
      sources:
      - https://github.com/heroiclabs/nakama/blob/master/social/social.go
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Candy Crush Saga
      - Nakama
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp: *id005
      name: Sign in with Apple + Game Center identity
      slug: apple
      sources:
      - https://github.com/heroiclabs/nakama/blob/master/social/social.go
      - https://www.king.com/privacyPolicy
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Nakama
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in (ID token check)
      slug: google-identity-platform
      sources:
      - https://github.com/heroiclabs/nakama/blob/master/social/social.go
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-aware
      agent_readiness: 22.1
      apps:
      - Nakama
      band: thin
      in_catalog: true
      kin_score: 34.5
      mcp: &id007
        status: none
      name: 'Steam (Steamworks partner API: AuthenticateUserTicket, GetFriendList)'
      slug: steam
      sources:
      - https://github.com/heroiclabs/nakama/blob/master/social/social.go
      status: profiled
      tags: &id008
      - Distribution
      - Gaming
      - Steamworks
      - Valve
      tier: observed
      url: /providers/steam/
    - agent_band: agent-native
      agent_readiness: 47.0
      apps:
      - Clash of Clans
      band: exemplar
      in_catalog: true
      kin_score: 71.3
      mcp:
        source: https://github.com/line/line-bot-mcp-server
        status: verified
      name: LINE (account linking + partner)
      slug: line
      sources:
      - https://supercell.com/en/privacy-policy/
      status: profiled
      tags:
      - Chatbots
      - Messaging
      - Mini Apps
      - Social Login
      tier: declared
      url: /providers/line/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Clash of Clans
      band: thin
      in_catalog: true
      kin_score: 26.2
      mcp:
        status: none
      name: Kakao (account linking + partner)
      slug: kakao
      sources:
      - https://supercell.com/en/privacy-policy/
      status: profiled
      tags:
      - Maps
      - Messaging
      - Navigation
      - Payments
      tier: declared
      url: /providers/kakao/
    - agent_band: null
      agent_readiness: null
      apps:
      - Clash of Clans
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: QQ (Tencent)
      slug: tencent
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Nakama
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp: *id005
      name: App Store receipt validation (verifyReceipt)
      slug: apple
      sources:
      - https://github.com/heroiclabs/nakama/blob/master/iap/iap.go
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Nakama
      band: developing
      in_catalog: true
      kin_score: 51.3
      mcp:
        status: none
      name: Google Play purchases/subscriptions validation (androidpublisher v3)
      slug: google-play
      sources:
      - https://github.com/heroiclabs/nakama/blob/master/iap/iap.go
      status: profiled
      tags:
      - Android
      - Application
      - Google Play
      - In-App Purchases
      tier: observed
      url: /providers/google-play/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Nakama
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook Instant Games purchases
      slug: facebook
      sources:
      - https://github.com/heroiclabs/nakama/blob/master/iap/iap.go
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 36.6
      apps:
      - Nakama
      band: thin
      in_catalog: true
      kin_score: 33.2
      mcp:
        status: none
      name: Samsung IAP server API
      slug: samsung
      sources:
      - https://github.com/heroiclabs/nakama/blob/master/iap/iap_samsung.go
      status: profiled
      tags:
      - Consumer Electronics
      - Developer Platform
      - IoT
      - Mobile
      tier: observed
      url: /providers/samsung/
    - agent_band: null
      agent_readiness: null
      apps:
      - Nakama
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Huawei IAP (HMS Core order service)
      slug: huawei-mobile-services
      sources:
      - https://github.com/heroiclabs/nakama/blob/master/iap/iap.go
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-180.30
      key: AE-180.30
      name: Player Engagement
      url: /capabilities/player-engagement/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Nakama
      - Talo
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Google Play Games Services (games/v1/players/me)
      slug: google-play-games
      sources:
      - https://github.com/TaloDev/backend/tree/develop/src/lib/integrations
      - https://github.com/heroiclabs/nakama/blob/master/social/social.go
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Talo
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp: *id005
      name: Game Center
      slug: apple
      sources:
      - https://github.com/TaloDev/backend/tree/develop/src/lib/integrations
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 22.1
      apps:
      - Talo
      band: thin
      in_catalog: true
      kin_score: 34.5
      mcp: *id007
      name: Steamworks (leaderboards, stats, players)
      slug: steam
      sources:
      - https://github.com/TaloDev/backend/tree/develop/src/lib/integrations
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/steam/
  - capability:
      attribution: API Evangelist extension
      id: AE-180.40
      key: AE-180.40
      name: Game Publishing & Distribution
      url: /capabilities/game-publishing-distribution/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.1
      apps:
      - Mindustry
      band: thin
      in_catalog: true
      kin_score: 34.5
      mcp: *id007
      name: Steamworks (steamworks4j; Steam build)
      slug: steam
      sources:
      - https://github.com/Anuken/Mindustry/blob/master/build.gradle
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/steam/
    - agent_band: null
      agent_readiness: null
      apps:
      - Clash of Clans
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Supersonic (Unity/ironSource publishing)
      slug: supersonic
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-180.40.10
      key: AE-180.40.10
      name: Mods & User-Generated Content Distribution
      url: /capabilities/game-publishing-distribution/
      via_parent: Game Publishing & Distribution
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Mindustry
      - Unciv
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub (mod discovery + download)
      slug: github
      sources:
      - https://github.com/Anuken/Mindustry/blob/master/core/src/mindustry/ui/dialogs/ModsDialog.java
      - https://github.com/yairm210/Unciv/blob/master/core/src/com/unciv/logic/github/GithubAPI.kt
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
      id: AE-180.30.10
      key: AE-180.30.10
      name: Rich Presence & Player Status
      url: /capabilities/player-engagement/
      via_parent: Player Engagement
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Mindustry
      - Unciv
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp: &id009
        status: none
      name: Discord Rich Presence (java-discord-rpc)
      slug: discord
      sources:
      - https://github.com/Anuken/Mindustry/blob/master/build.gradle
      - https://github.com/yairm210/Unciv/blob/master/gradle/libs.versions.toml
      status: profiled
      tags: &id010
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Unciv
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox (multiplayer turn files)
      slug: dropbox
      sources:
      - https://github.com/yairm210/Unciv/blob/master/core/src/com/unciv/logic/multiplayer/storage/DropBox.kt
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: observed
      url: /providers/dropbox/
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
      - Clash of Clans
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer (attribution, processor)
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.supercell.clashofclans/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.10
      key: AE-170.50.10
      name: Online Communities
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Clash of Clans
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp: *id009
      name: Discord
      slug: discord
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags: *id010
      tier: declared
      url: /providers/discord/
  - capability:
      attribution: Turbo EA
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - Clash of Clans
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        status: none
      name: StreamElements (creator sponsorships)
      slug: streamelements
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Company
      - Consumer
      - Creator Economy
      - Live Streaming
      tier: declared
      url: /providers/streamelements/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Candy Crush Saga
      - Subway Surfers
      band: exemplar
      in_catalog: true
      kin_score: 66.5
      mcp: *id011
      name: Unity3d Ads
      slug: unity
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
      status: profiled
      tags: *id012
      tier: observed
      url: /providers/unity/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Candy Crush Saga
      - Subway Surfers
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
    - agent_band: agent-native
      agent_readiness: 53.6
      apps:
      - Candy Crush Saga
      - Subway Surfers
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp: *id013
      name: Amazon Advertisement
      slug: amazon
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
      status: profiled
      tags: *id014
      tier: observed
      url: /providers/amazon/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Candy Crush Saga
      - Subway Surfers
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook Ads
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 35.5
      apps:
      - Candy Crush Saga
      - Subway Surfers
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp: *id015
      name: AppLovin (MAX and SparkLabs)
      slug: applovin
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
      status: profiled
      tags: *id016
      tier: observed
      url: /providers/applovin/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Candy Crush Saga
      - Subway Surfers
      band: thin
      in_catalog: true
      kin_score: 32.1
      mcp:
        status: unknown
      name: PubNative
      slug: pubnative
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
      status: profiled
      tags:
      - AdTech
      - Company
      - Mobile
      - Monetization
      tier: observed
      url: /providers/pubnative/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Candy Crush Saga
      - Subway Surfers
      band: minimal
      in_catalog: true
      kin_score: 2.0
      mcp:
        status: none
      name: Chartboost
      slug: chartboost
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/chartboost/
    - agent_band: agent-ready
      agent_readiness: 31.0
      apps:
      - Subway Surfers
      band: strong
      in_catalog: true
      kin_score: 60.3
      mcp:
        status: none
      name: BidMachine
      slug: bidmachine-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      status: profiled
      tags:
      - Ad Exchange
      - AdTech
      - Advertising
      - Mobile Advertising
      tier: observed
      url: /providers/bidmachine-io/
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Subway Surfers
      band: thin
      in_catalog: true
      kin_score: 34.0
      mcp:
        status: none
      name: Appodeal Stack
      slug: appodeal
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      status: profiled
      tags:
      - Advertising
      - Company
      - Mobile
      - Monetization
      tier: observed
      url: /providers/appodeal/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Candy Crush Saga
      band: minimal
      in_catalog: true
      kin_score: 10.2
      mcp: *id017
      name: ironSource
      slug: ironsource
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
      status: profiled
      tags: *id018
      tier: observed
      url: /providers/ironsource/
    - agent_band: null
      agent_readiness: null
      apps:
      - Subway Surfers
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: SuperAwesome
      slug: superawesome
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
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
      - Candy Crush Saga
      - Clash of Clans
      - Subway Surfers
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id019
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.supercell.clashofclans/latest/
      status: profiled
      tags: &id020
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Candy Crush Saga
      - Subway Surfers
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook Analytics
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Candy Crush Saga
      - Clash of Clans
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://supercell.com/en/partner-opt-out/
      - https://www.king.com/privacyPolicy
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: declared
      url: /providers/google-analytics/
    - agent_band: agent-aware
      agent_readiness: 20.1
      apps:
      - Clash of Clans
      band: developing
      in_catalog: true
      kin_score: 42.3
      mcp:
        source: https://github.com/snowplow/snowplow-cli
        status: verified
      name: Snowplow
      slug: snowplow
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.supercell.clashofclans/latest/
      status: profiled
      tags:
      - Analytics Platform
      - Behavioral Data
      - Data Collection
      - Data Engineering
      tier: observed
      url: /providers/snowplow/
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
      - Clash of Clans
      - Talo
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry (@sentry/node)
      slug: sentry-system
      sources:
      - https://github.com/TaloDev/backend/blob/develop/package.json
      - https://reports.exodus-privacy.eu.org/en/reports/com.supercell.clashofclans/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Lichess mobile
      - Subway Surfers
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id019
      name: Firebase Crashlytics
      slug: google-firebase
      sources:
      - https://github.com/lichess-org/mobile/blob/main/pubspec.yaml
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      status: profiled
      tags: *id020
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 37.0
      apps:
      - Talo
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        status: none
      name: HyperDX (@hyperdx/node-opentelemetry)
      slug: hyperdx
      sources:
      - https://github.com/TaloDev/backend/blob/develop/package.json
      status: profiled
      tags:
      - Company
      - Logging
      - Monitoring
      - Observability
      tier: observed
      url: /providers/hyperdx/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Clash of Clans
      - Subway Surfers
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Helpshift (in-game support)
      slug: helpshift
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.supercell.clashofclans/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Candy Crush Saga
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk (King Care help centre, kingcare.zendesk.com)
      slug: zendesk
      sources:
      - https://www.king.com/privacyPolicy
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - Talo
      band: thin
      in_catalog: true
      kin_score: 31.1
      mcp:
        status: none
      name: hCaptcha
      slug: hcaptcha
      sources:
      - https://github.com/TaloDev/backend/blob/develop/envs/.env.dev
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Privacy
      - hCaptcha
      tier: observed
      url: /providers/hcaptcha/
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Clash of Clans
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: declared
      url: /providers/google-recaptcha/
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Candy Crush Saga
      - Subway Surfers
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        source: https://github.com/IABTechLab/agentic-real-time-framework
        status: verified
      name: IAB Open Measurement
      slug: iab-tech-lab
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.king.candycrushsaga/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Standards
      tier: observed
      url: /providers/iab-tech-lab/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.50
      key: AE-160.50
      name: Consent & Preferences
      url: /capabilities/consent-preferences/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.1
      apps:
      - Clash of Clans
      band: thin
      in_catalog: true
      kin_score: 37.1
      mcp:
        status: none
      name: Usercentrics (CMP)
      slug: usercentrics
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - CMP
      - Compliance
      - Consent
      - Privacy
      tier: declared
      url: /providers/usercentrics/
  - capability:
      attribution: Turbo EA
      id: BC-3740.30
      key: content-delivery-network-operations
      name: Content Delivery Network Operations
      url: /capabilities/content-delivery-network-operations/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Mindustry
      band: minimal
      in_catalog: true
      kin_score: 4.8
      mcp:
        status: none
      name: jsDelivr (mod index, server lists)
      slug: jsdelivr
      sources:
      - https://github.com/Anuken/Mindustry/blob/master/core/src/mindustry/Vars.java
      status: profiled
      tags:
      - Development
      - Public APIs
      tier: observed
      url: /providers/jsdelivr/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.9
      apps:
      - Subway Surfers
      band: strong
      in_catalog: true
      kin_score: 65.9
      mcp:
        status: none
      name: Singular
      slug: singular
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.kiloo.subwaysurf/latest/
      status: profiled
      tags:
      - Attribution
      - Company
      - Marketing Analytics
      - Mobile Attribution
      tier: observed
      url: /providers/singular/
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
      - Talo
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe (Talo plan billing)
      slug: stripe
      sources:
      - https://github.com/TaloDev/backend/blob/develop/package.json
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
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
      - Lichess mobile
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id019
      name: Firebase Cloud Messaging
      slug: google-firebase
      sources:
      - https://github.com/lichess-org/mobile/blob/main/pubspec.yaml
      status: profiled
      tags: *id020
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Clash of Clans
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://supercell.com/en/partner-opt-out/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: declared
      url: /providers/google-tag-manager/
  layer: common
summary:
  coverage_pct: 84.4
  declared_only: 42
  distinct_providers: 77
  in_catalog: 65
  mcp:
    documented: 0
    none: 45
    unchecked: 12
    verified: 17
  mcp_verified: 17
  mean_kin_score: 42.4
  observed: 35
  queued: 12
  reference_apps: 8
title: 'Mobile & Casual Games (live-ops backend): application blueprint'
---
