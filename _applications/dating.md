---
access: understanding
agent_layer: []
apps:
- anchor: tinder
  counts:
    declared: 8
    observed: 7
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
  - route: documentation
    url: https://policies.tinder.com/privacy/intl/en/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
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
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
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
    name: IAB Tech Lab
    provider: iab-tech-lab
    says: ships the IAB Tech Lab SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
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
    name: Apple
    provider: apple
    says: lists Apple as an integration
    source: https://policies.tinder.com/privacy/intl/en/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: common
    name: Apple
    provider: apple
    says: lists Apple as an integration
    source: https://policies.tinder.com/privacy/intl/en/
    tier: declared
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
    says: lists Facebook as an integration
    source: https://policies.tinder.com/privacy/intl/en/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: common
    name: Google Play
    provider: google-play
    says: lists Google Play as an integration
    source: https://policies.tinder.com/privacy/intl/en/
    tier: declared
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
    says: lists Google sign-in as an integration
    source: https://policies.tinder.com/privacy/intl/en/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Instagram
    provider: instagram
    says: lists Instagram as an integration
    source: https://policies.tinder.com/privacy/intl/en/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: LinkedIn
    provider: linkedin
    says: lists LinkedIn as an integration
    source: https://policies.tinder.com/privacy/intl/en/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.10
      key: AE-170.20.10
      name: Music Streaming & Catalog
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: Spotify
    provider: spotify
    says: lists Spotify as an integration
    source: https://policies.tinder.com/privacy/intl/en/
    tier: declared
  kind: commercial
  name: Tinder
  page: /applications/dating/tinder/
  slug: tinder
  url: https://tinder.com/
- anchor: hinge
  counts:
    declared: 49
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/co.hinge.app/latest/
  - route: documentation
    url: https://hinge.co/privacy
  - route: integrations page
    url: https://hinge.co/hinge-data-recipients
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
    source: https://reports.exodus-privacy.eu.org/en/reports/co.hinge.app/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/co.hinge.app/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/co.hinge.app/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Split Software
    provider: split
    says: ships the Split Software SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/co.hinge.app/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430.30
      key: BC-430.30
      name: Contact Centre Operations Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: null
    credit: null
    layer: common
    name: Accenture
    provider: accenture
    says: lists Accenture as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: common
    name: Alchemer
    provider: alchemer
    says: lists Alchemer as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon Web Services
    provider: amazon-web-services
    says: lists Amazon Web Services as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Apple
    provider: apple
    says: lists Apple as an integration
    source: https://hinge.co/privacy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: common
    name: Apple
    provider: apple
    says: lists Apple as an integration
    source: https://hinge.co/privacy
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    credit: null
    layer: agent
    name: Arize AI
    provider: arize-ai
    says: lists Arize AI as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: Braze
    provider: braze
    says: lists Braze as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.50
      key: software-quality-engineering
      name: Software Quality Engineering
      url: /capabilities/software-quality-engineering/
      via_parent: null
    credit: null
    layer: common
    name: BrowserStack
    provider: browserstack
    says: lists BrowserStack as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    credit: null
    layer: common
    name: Calendly
    provider: calendly
    says: lists Calendly as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.10
      key: AE-170.30.10
      name: Image Processing & Optimisation
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Cloudinary
    provider: cloudinary
    says: lists Cloudinary as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: Confluent
    provider: confluent
    says: lists Confluent as an integration
    source: https://hinge.co/hinge-data-recipients
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
    name: Databricks
    provider: databricks
    says: lists Databricks as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3770.50
      key: audience-insights-research-management
      name: Audience Insights & Research Management
      url: /capabilities/audience-insights-research-management/
      via_parent: null
    credit: null
    layer: common
    name: dscout
    provider: dscout
    says: lists dscout as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1400.30
      key: fraud-detection-investigation-management
      name: Fraud Detection & Investigation Management
      url: /capabilities/fraud-detection-investigation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Ekata
    provider: ekata
    says: lists Ekata as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: common
    name: Elastic
    provider: elastic
    says: lists Elastic as an integration
    source: https://hinge.co/hinge-data-recipients
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
    name: Enterpret
    provider: enterpret
    says: lists Enterpret as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
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
    says: lists Facebook as an integration
    source: https://hinge.co/privacy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30.20
      key: AE-160.30.20
      name: Biometric Verification
      url: /capabilities/identity-verification/
      via_parent: Identity Verification
    credit: null
    layer: domain
    name: FaceTec
    provider: facetec
    says: lists FaceTec as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: common
    name: Google
    provider: google
    says: lists Google as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: common
    name: Google Play
    provider: google-play
    says: lists Google Play as an integration
    source: https://hinge.co/privacy
    tier: declared
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
    says: lists Google sign-in as an integration
    source: https://hinge.co/privacy
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
    name: Hex
    provider: hex
    says: lists Hex as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3770.50
      key: audience-insights-research-management
      name: Audience Insights & Research Management
      url: /capabilities/audience-insights-research-management/
      via_parent: null
    credit: null
    layer: common
    name: HeyMarvin
    provider: heymarvin
    says: lists HeyMarvin as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Instagram
    provider: instagram
    says: lists Instagram as an integration
    source: https://hinge.co/privacy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30.10
      key: AE-160.30.10
      name: Document Verification
      url: /capabilities/identity-verification/
      via_parent: Identity Verification
    credit: null
    layer: domain
    name: Jumio
    provider: jumio
    says: lists Jumio as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: LinkedIn
    provider: linkedin
    says: lists LinkedIn as an integration
    source: https://hinge.co/privacy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60.10
      key: AE-150.60.10
      name: Async Video Messaging
      url: /capabilities/video-calling/
      via_parent: Video Calling
    credit: null
    layer: common
    name: Loom
    provider: loom
    says: lists Loom as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-810.30
      key: experimentation-prototyping-management
      name: Experimentation & Prototyping Management
      url: /capabilities/experimentation-prototyping-management/
      via_parent: null
    credit: null
    layer: common
    name: Lovable
    provider: lovable
    says: lists Lovable as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.30.30
      key: BC-430.30.30
      name: Quality Monitoring and Coaching
      url: /capabilities/contact-centre-operations-management/
      via_parent: Contact Centre Operations Management
    credit: null
    layer: common
    name: MaestroQA
    provider: maestroqa
    says: lists MaestroQA as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: common
    name: MaxMind
    provider: maxmind
    says: lists MaxMind as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    credit: null
    layer: common
    name: Notion
    provider: notion
    says: lists Notion as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: lists OpenAI as an integration
    source: https://hinge.co/hinge-data-recipients
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
    name: Pinterest
    provider: pinterest
    says: lists Pinterest as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Reduct
    provider: reduct
    says: lists Reduct as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40
      key: AE-150.40
      name: In-App Chat
      url: /capabilities/in-app-chat/
      via_parent: null
    credit: null
    layer: domain
    name: Sendbird
    provider: sendbird
    says: lists Sendbird as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
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
    says: lists Sentry as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: ServiceNow Cloud Observability (Lightstep)
    provider: lightstep
    says: lists ServiceNow Cloud Observability (Lightstep) as an integration
    source: https://hinge.co/hinge-data-recipients
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
    name: Snap Inc.
    provider: snap
    says: lists Snap Inc. as an integration
    source: https://hinge.co/hinge-data-recipients
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
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.30
      key: BC-430.30
      name: Contact Centre Operations Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: null
    credit: null
    layer: common
    name: TELUS (TELUS Digital)
    provider: telus
    says: lists TELUS (TELUS Digital) as an integration
    source: https://hinge.co/hinge-data-recipients
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
    name: The Cirqle
    provider: the-cirqle
    says: lists The Cirqle as an integration
    source: https://hinge.co/hinge-data-recipients
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
    name: TikTok
    provider: tiktok
    says: lists TikTok as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: lists Twilio as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: common
    name: Typeform
    provider: typeform
    says: lists Typeform as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: common
    name: Unbabel
    provider: unbabel
    says: lists Unbabel as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3770.50
      key: audience-insights-research-management
      name: Audience Insights & Research Management
      url: /capabilities/audience-insights-research-management/
      via_parent: null
    credit: null
    layer: common
    name: UserTesting
    provider: usertesting
    says: lists UserTesting as an integration
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: Vonage
    provider: vonage
    says: lists Vonage as an integration
    source: https://hinge.co/hinge-data-recipients
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
    source: https://hinge.co/hinge-data-recipients
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
    source: https://hinge.co/hinge-data-recipients
    tier: declared
  kind: commercial
  name: Hinge
  page: /applications/dating/hinge/
  slug: hinge
  url: https://hinge.co/
- anchor: bumble
  counts:
    declared: 16
    observed: 7
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
  - route: documentation
    url: https://bumble.com/en/privacy
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
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
    name: Apple
    provider: apple
    says: lists Apple as an integration
    source: https://bumble.com/en/privacy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: common
    name: Apple
    provider: apple
    says: lists Apple as an integration
    source: https://bumble.com/en/privacy
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3780.40
      key: user-generated-content-moderation
      name: User-Generated Content Moderation
      url: /capabilities/user-generated-content-moderation/
      via_parent: null
    credit: null
    layer: domain
    name: Cinder
    provider: cinder
    says: lists Cinder as an integration
    source: https://bumble.com/en/privacy
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Cloud
    provider: google-cloud-platform
    says: lists Google Cloud as an integration
    source: https://bumble.com/en/privacy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: common
    name: Google Play
    provider: google-play
    says: lists Google Play as an integration
    source: https://bumble.com/en/privacy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Instagram
    provider: instagram
    says: lists Instagram as an integration
    source: https://bumble.com/en/privacy
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3770.50
      key: audience-insights-research-management
      name: Audience Insights & Research Management
      url: /capabilities/audience-insights-research-management/
      via_parent: null
    credit: null
    layer: common
    name: Kantar
    provider: kantar
    says: lists Kantar as an integration
    source: https://bumble.com/en/privacy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: lists OpenAI as an integration
    source: https://bumble.com/en/privacy
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
    source: https://bumble.com/en/privacy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.20
      key: AE-150.50.20
      name: Number Verification
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: domain
    name: Prove
    provider: prove
    says: lists Prove as an integration
    source: https://bumble.com/en/privacy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.30
      key: AE-100.70.30
      name: Support & Assist Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    credit: null
    layer: agent
    name: Sierra
    provider: sierra
    says: lists Sierra as an integration
    source: https://bumble.com/en/privacy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.10
      key: AE-170.20.10
      name: Music Streaming & Catalog
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: Spotify
    provider: spotify
    says: lists Spotify as an integration
    source: https://bumble.com/en/privacy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: lists Twilio as an integration
    source: https://bumble.com/en/privacy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: common
    name: Typeform
    provider: typeform
    says: lists Typeform as an integration
    source: https://bumble.com/en/privacy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30.10
      key: AE-160.30.10
      name: Document Verification
      url: /capabilities/identity-verification/
      via_parent: Identity Verification
    credit: null
    layer: domain
    name: Veriff
    provider: veriff
    says: lists Veriff as an integration
    source: https://bumble.com/en/privacy
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
    source: https://bumble.com/en/privacy
    tier: declared
  kind: commercial
  name: Bumble
  page: /applications/dating/bumble/
  slug: bumble
  url: https://bumble.com/
- anchor: grindr
  counts:
    declared: 4
    observed: 20
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
  - route: documentation
    url: https://trust.grindr.com/en-US/privacy
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
    name: Amazon
    provider: amazon
    says: ships the Amazon SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    name: AppLovin
    provider: applovin
    says: ships the AppLovin SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    name: Appodeal
    provider: appodeal
    says: ships the Appodeal SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    name: Digital Turbine (Fyber)
    provider: digital-turbine
    says: ships the Digital Turbine (Fyber) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    name: IAB Tech Lab
    provider: iab-tech-lab
    says: ships the IAB Tech Lab SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    name: InMobi
    provider: inmobi
    says: ships the InMobi SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    name: Mintegral
    provider: mintegral
    says: ships the Mintegral SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    name: PubMatic
    provider: pubmatic
    says: ships the PubMatic SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-130.50
      key: privacy-data-protection-management
      name: Privacy & Data Protection Management
      url: /capabilities/privacy-data-protection-management/
      via_parent: null
    credit: null
    layer: common
    name: TrustArc
    provider: trustarc
    says: ships the TrustArc SDK or integration code
    source: https://trust.grindr.com/en-US/privacy
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
    name: Unity
    provider: unity
    says: ships the Unity SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
    name: Apple
    provider: apple
    says: lists Apple as an integration
    source: https://trust.grindr.com/en-US/privacy
    tier: declared
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
    says: lists Google sign-in as an integration
    source: https://trust.grindr.com/en-US/privacy
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Instagram
    provider: instagram
    says: lists Instagram as an integration
    source: https://trust.grindr.com/en-US/privacy
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
    name: Ketch
    provider: ketch-io
    says: lists Ketch as an integration
    source: https://trust.grindr.com/en-US/privacy
    tier: declared
  kind: commercial
  name: Grindr
  page: /applications/dating/grindr/
  slug: grindr
  url: https://www.grindr.com/
- anchor: alovoa
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: dependency manifest
    url: https://github.com/Alovoa/alovoa/blob/master/pom.xml
  - route: source code
    url: https://github.com/Alovoa/alovoa/blob/master/src/main/resources/application.properties
  integrations:
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
    source: https://github.com/Alovoa/alovoa/blob/master/src/main/resources/application.properties
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
    source: https://github.com/Alovoa/alovoa/blob/master/src/main/resources/application.properties
    tier: observed
  kind: self-hosted
  name: Alovoa
  page: /applications/dating/alovoa/
  slug: alovoa
  url: https://github.com/Alovoa/alovoa
- anchor: duolicious
  counts:
    declared: 0
    observed: 9
  evidence:
  - route: dependency manifest
    url: https://github.com/duolicious/duolicious-backend/blob/main/backend/requirements.txt
  - route: dependency manifest
    url: https://github.com/duolicious/duolicious-frontend/blob/main/package.json
  - route: source code
    url: https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
  - route: source code
    url: https://github.com/duolicious/duolicious-backend/tree/main/backend
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Apple
    provider: apple
    says: ships the Apple SDK or integration code
    source: https://github.com/duolicious/duolicious-frontend/blob/main/package.json
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
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.30.30
      key: BC-620.30.30
      name: Cyber Threat Intelligence
      url: /capabilities/threat-detection-response-management/
      via_parent: Threat Detection & Response Management
    credit: null
    layer: common
    name: FireHOL IP lists
    provider: firehol
    says: ships the FireHOL IP lists SDK or integration code
    source: https://github.com/duolicious/duolicious-backend/tree/main/backend
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
    source: https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
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
    source: https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: common
    name: RevenueCat
    provider: revenuecat
    says: ships the RevenueCat SDK or integration code
    source: https://github.com/duolicious/duolicious-frontend/blob/main/package.json
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
    name: RIPE NCC (RIPEstat)
    provider: ripe-ncc
    says: ships the RIPE NCC (RIPEstat) SDK or integration code
    source: https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.10
      key: AE-170.20.10
      name: Music Streaming & Catalog
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: Spotify
    provider: spotify
    says: ships the Spotify SDK or integration code
    source: https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
    tier: observed
  kind: open-source-saas
  name: Duolicious
  page: /applications/dating/duolicious/
  slug: duolicious
  url: https://duolicious.app/
- anchor: ph7builder
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: dependency manifest
    url: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon Web Services
    provider: amazon-web-services
    says: ships the Amazon Web Services SDK or integration code
    source: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
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
    source: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
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
    name: Clickatell
    provider: clickatell
    says: ships the Clickatell SDK or integration code
    source: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: common
    name: Gravatar
    provider: gravatar
    says: ships the Gravatar SDK or integration code
    source: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
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
    name: MaxMind
    provider: maxmind
    says: ships the MaxMind SDK or integration code
    source: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
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
    name: Skeerel
    provider: skeerel
    says: ships the Skeerel SDK or integration code
    source: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
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
    source: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
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
    source: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
    tier: observed
  kind: self-hosted
  name: pH7Builder
  page: /applications/dating/ph7builder/
  slug: ph7builder
  url: https://ph7builder.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: dating
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Lifestyle
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Social Networking
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Dating
  store: google-play
  url: https://play.google.com/store/apps/category/DATING
name: Dating
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.20
    key: AE-170.50.20
    name: Dating
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  fit: exact
  layer: domain
  why: 'the category itself: matching, swiping, profiles; every reference app builds it in-house, no third-party matching API appeared'
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: every app offers Facebook / Google / Apple (and Discord) sign-in
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: exact
  layer: common
  why: subscriptions sold through App Store / Google Play / RevenueCat
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: domain
  why: Instagram and LinkedIn content pulled onto dating profiles
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: web subscriptions and payouts
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.10
    key: AE-170.20.10
    name: Music Streaming & Catalog
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  fit: exact
  layer: domain
  why: Spotify artists / anthem on profiles (Tinder, Bumble, Duolicious)
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  fit: exact
  layer: common
  why: cloud hosting
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: common
  why: location estimation, abuse controls
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: AI icebreakers, selfie verification, product features
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  fit: exact
  layer: common
  why: member surveys
- capability:
    attribution: Turbo EA
    id: BC-3770.50
    key: audience-insights-research-management
    name: Audience Insights & Research Management
    url: /capabilities/audience-insights-research-management/
    via_parent: null
  fit: exact
  layer: common
  why: user research
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: support desks and AI support agents
- capability:
    attribution: API Evangelist extension
    id: AE-160.30.10
    key: AE-160.30.10
    name: Document Verification
    url: /capabilities/identity-verification/
    via_parent: Identity Verification
  fit: exact
  layer: domain
  why: ID verification for trust & safety (Veriff, Jumio)
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.30
    key: AE-150.20.30
    name: One-Time Passcodes
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: phone number verification at sign-up
- capability:
    attribution: Turbo EA
    id: BC-430.30
    key: BC-430.30
    name: Contact Centre Operations Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: null
  fit: exact
  layer: common
  why: outsourced trust & safety / support (BPO)
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: install attribution for paid acquisition
- capability:
    attribution: Turbo EA
    id: BC-610.60
    key: artificial-intelligence-management
    name: Artificial Intelligence Management
    url: /capabilities/artificial-intelligence-management/
    via_parent: null
  fit: nearest
  layer: agent
  why: model monitoring
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  fit: exact
  layer: common
  why: push / email / in-app messaging
- capability:
    attribution: Turbo EA
    id: BC-4200.50
    key: software-quality-engineering
    name: Software Quality Engineering
    url: /capabilities/software-quality-engineering/
    via_parent: null
  fit: exact
  layer: common
  why: device testing
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  fit: exact
  layer: common
  why: meeting scheduling
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.10
    key: AE-170.30.10
    name: Image Processing & Optimisation
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: domain
  why: profile photo / video delivery
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: common
  why: event streaming backbone
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: common
  why: data platform and analysis
- capability:
    attribution: Turbo EA
    id: BC-1400.30
    key: fraud-detection-investigation-management
    name: Fraud Detection & Investigation Management
    url: /capabilities/fraud-detection-investigation-management/
    via_parent: null
  fit: exact
  layer: domain
  why: romance-scam and fake-account prevention
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  fit: exact
  layer: common
  why: search infrastructure
- capability:
    attribution: API Evangelist extension
    id: AE-160.30.20
    key: AE-160.30.20
    name: Biometric Verification
    url: /capabilities/identity-verification/
    via_parent: Identity Verification
  fit: exact
  layer: domain
  why: face liveness / selfie match (FaceTec)
- capability:
    attribution: API Evangelist extension
    id: AE-150.60.10
    key: AE-150.60.10
    name: Async Video Messaging
    url: /capabilities/video-calling/
    via_parent: Video Calling
  fit: exact
  layer: common
  why: internal video recording
- capability:
    attribution: Turbo EA
    id: BC-810.30
    key: experimentation-prototyping-management
    name: Experimentation & Prototyping Management
    url: /capabilities/experimentation-prototyping-management/
    via_parent: null
  fit: exact
  layer: common
  why: AI prototyping
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  fit: exact
  layer: common
  why: internal wiki
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: paid social acquisition
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  fit: nearest
  layer: common
  why: video editing of research clips
- capability:
    attribution: API Evangelist extension
    id: AE-150.40
    key: AE-150.40
    name: In-App Chat
    url: /capabilities/in-app-chat/
    via_parent: null
  fit: exact
  layer: domain
  why: match-to-match messaging (Sendbird)
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error tracking and reliability
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  fit: exact
  layer: common
  why: experimentation
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: common
  why: support translation
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: domain
  why: video dates (Vonage)
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: vendor integrations
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.20
    key: AE-150.50.20
    name: Number Verification
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  fit: exact
  layer: domain
  why: phone/device possession checks (Prove)
- capability:
    attribution: Turbo EA
    id: BC-3780.40
    key: user-generated-content-moderation
    name: User-Generated Content Moderation
    url: /capabilities/user-generated-content-moderation/
    via_parent: null
  fit: exact
  layer: domain
  why: moderating reports, messages and photos is core to dating trust & safety
- capability:
    attribution: API Evangelist extension
    id: AE-160.50
    key: AE-160.50
    name: Consent & Preferences
    url: /capabilities/consent-preferences/
    via_parent: null
  fit: exact
  layer: common
  why: consent management platform
- capability:
    attribution: Turbo EA
    id: BC-130.50
    key: privacy-data-protection-management
    name: Privacy & Data Protection Management
    url: /capabilities/privacy-data-protection-management/
    via_parent: null
  fit: exact
  layer: common
  why: privacy trust center
- capability:
    attribution: Turbo EA
    id: BC-620.30.30
    key: BC-620.30.30
    name: Cyber Threat Intelligence
    url: /capabilities/threat-detection-response-management/
    via_parent: Threat Detection & Response Management
  fit: exact
  layer: common
  why: IP blocklists against spam/abuse accounts
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: SMS notifications (pH7Builder)
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: common
  why: Gravatar avatars
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: SDK named in reference-app Exodus reports
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: SDK named in reference-app Exodus reports
- capability:
    attribution: Turbo EA
    id: BC-3760.30
    key: programmatic-sales-management
    name: Programmatic Sales Management
    url: /capabilities/programmatic-sales-management/
    via_parent: null
  fit: nearest
  layer: common
  why: SDK named in reference-app Exodus reports
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
      - Bumble
      - Grindr
      - Hinge
      - Tinder
      band: exemplar
      in_catalog: true
      kin_score: 67.8
      mcp:
        status: none
      name: Instagram
      slug: instagram
      sources:
      - https://bumble.com/en/privacy
      - https://hinge.co/privacy
      - https://policies.tinder.com/privacy/intl/en/
      status: profiled
      tags:
      - Instagram
      - Meta
      - Photos
      - Social Media
      tier: declared
      url: /providers/instagram/
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Hinge
      - Tinder
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp:
        status: none
      name: LinkedIn
      slug: linkedin
      sources:
      - https://hinge.co/privacy
      - https://policies.tinder.com/privacy/intl/en/
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: declared
      url: /providers/linkedin/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.10
      key: AE-170.20.10
      name: Music Streaming & Catalog
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - Bumble
      - Duolicious
      - Tinder
      band: developing
      in_catalog: true
      kin_score: 50.6
      mcp:
        status: none
      name: Spotify
      slug: spotify
      sources:
      - https://bumble.com/en/privacy
      - https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
      - https://policies.tinder.com/privacy/intl/en/
      status: profiled
      tags:
      - Audio
      - Music
      - Podcasts
      - Streaming
      tier: observed
      url: /providers/spotify/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30.10
      key: AE-160.30.10
      name: Document Verification
      url: /capabilities/identity-verification/
      via_parent: Identity Verification
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Bumble
      band: thin
      in_catalog: true
      kin_score: 28.2
      mcp:
        status: none
      name: Veriff
      slug: veriff
      sources:
      - https://bumble.com/en/privacy
      status: profiled
      tags:
      - Biometrics
      - Fraud Prevention
      - Identity Verification
      - KYC
      tier: declared
      url: /providers/veriff/
    - agent_band: agent-aware
      agent_readiness: 14.3
      apps:
      - Hinge
      band: emerging
      in_catalog: true
      kin_score: 23.8
      mcp:
        status: none
      name: Jumio
      slug: jumio
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - AML
      - Biometrics
      - Identity Verification
      - KYC
      tier: declared
      url: /providers/jumio/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30.20
      key: AE-160.30.20
      name: Biometric Verification
      url: /capabilities/identity-verification/
      via_parent: Identity Verification
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Hinge
      band: minimal
      in_catalog: true
      kin_score: 10.6
      mcp:
        status: none
      name: FaceTec
      slug: facetec
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Biometric
      - Identity Verification
      - SDK
      - Security
      tier: declared
      url: /providers/facetec/
  - capability:
      attribution: Turbo EA
      id: BC-1400.30
      key: fraud-detection-investigation-management
      name: Fraud Detection & Investigation Management
      url: /capabilities/fraud-detection-investigation-management/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Hinge
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Ekata
      slug: ekata
      sources:
      - https://hinge.co/hinge-data-recipients
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.10
      key: AE-170.30.10
      name: Image Processing & Optimisation
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.5
      apps:
      - Hinge
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://cloudinary.com/documentation/cloudinary_llm_mcp
        status: verified
      name: Cloudinary
      slug: cloudinary
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Asset Management
      - Digital Asset Management
      - Image Processing
      - Image Transformation
      tier: declared
      url: /providers/cloudinary/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40
      key: AE-150.40
      name: In-App Chat
      url: /capabilities/in-app-chat/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.8
      apps:
      - Hinge
      band: developing
      in_catalog: true
      kin_score: 52.1
      mcp:
        status: none
      name: Sendbird
      slug: sendbird
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Customer Service
      - Omnichannel
      - Video
      - Voice
      tier: declared
      url: /providers/sendbird/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.20
      key: AE-150.50.20
      name: Number Verification
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.4
      apps:
      - Bumble
      band: developing
      in_catalog: true
      kin_score: 54.0
      mcp:
        status: none
      name: Prove
      slug: prove
      sources:
      - https://bumble.com/en/privacy
      status: profiled
      tags:
      - Authentication
      - Identity Verification
      - KYC
      - Phone Intelligence
      tier: declared
      url: /providers/prove/
  - capability:
      attribution: Turbo EA
      id: BC-3780.40
      key: user-generated-content-moderation
      name: User-Generated Content Moderation
      url: /capabilities/user-generated-content-moderation/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Bumble
      band: minimal
      in_catalog: true
      kin_score: 3.3
      mcp:
        status: unknown
      name: Cinder
      slug: cinder
      sources:
      - https://bumble.com/en/privacy
      status: profiled
      tags:
      - Company
      - Content Moderation
      - Security
      - Trust and Safety
      tier: declared
      url: /providers/cinder/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.0
      apps:
      - Hinge
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/Vonage/vonage-mcp-server-documentation
        status: verified
      name: Vonage
      slug: vonage
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Communications
      - Messaging
      - Telecommunications
      - Video Conferencing
      tier: declared
      url: /providers/vonage/
  layer: domain
- capabilities:
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
      - Alovoa
      - Duolicious
      - Grindr
      - Hinge
      - Tinder
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/Alovoa/alovoa/blob/master/src/main/resources/application.properties
      - https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
      - https://hinge.co/privacy
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Bumble
      - Duolicious
      - Grindr
      - Hinge
      - Tinder
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp: &id001
        status: none
      name: Apple
      slug: apple
      sources:
      - https://bumble.com/en/privacy
      - https://github.com/duolicious/duolicious-frontend/blob/main/package.json
      - https://hinge.co/privacy
      status: profiled
      tags: &id002
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Alovoa
      - Bumble
      - Grindr
      - Hinge
      - Tinder
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id003
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/Alovoa/alovoa/blob/master/src/main/resources/application.properties
      - https://hinge.co/privacy
      - https://policies.tinder.com/privacy/intl/en/
      status: profiled
      tags: &id004
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Duolicious
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Bumble
      - Grindr
      - Tinder
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Grindr
      band: exemplar
      in_catalog: true
      kin_score: 66.5
      mcp:
        source: https://github.com/Unity-Technologies/industry-ai-workflows
        status: verified
      name: Unity
      slug: unity
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
      status: profiled
      tags:
      - Game Development
      - Game Services
      - Multiplayer
      - Real-Time 3D
      tier: observed
      url: /providers/unity/
    - agent_band: agent-ready
      agent_readiness: 31.0
      apps:
      - Grindr
      band: strong
      in_catalog: true
      kin_score: 60.3
      mcp:
        status: none
      name: BidMachine
      slug: bidmachine-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
      status: profiled
      tags:
      - Ad Exchange
      - AdTech
      - Advertising
      - Mobile Advertising
      tier: observed
      url: /providers/bidmachine-io/
    - agent_band: agent-native
      agent_readiness: 53.6
      apps:
      - Grindr
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Amazon
      slug: amazon
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: observed
      url: /providers/amazon/
    - agent_band: agent-aware
      agent_readiness: 7.7
      apps:
      - Grindr
      band: developing
      in_catalog: true
      kin_score: 46.1
      mcp:
        status: none
      name: InMobi
      slug: inmobi
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Enterprise
      tier: observed
      url: /providers/inmobi/
    - agent_band: agent-aware
      agent_readiness: 20.3
      apps:
      - Grindr
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Digital Turbine (Fyber)
      slug: digital-turbine
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
      status: profiled
      tags:
      - Advertising
      - Company
      - Mobile
      - Monetization
      tier: observed
      url: /providers/digital-turbine/
    - agent_band: agent-ready
      agent_readiness: 35.5
      apps:
      - Grindr
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp:
        status: none
      name: AppLovin
      slug: applovin
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - App Monetization
      - Mobile
      tier: observed
      url: /providers/applovin/
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Grindr
      band: thin
      in_catalog: true
      kin_score: 34.0
      mcp:
        status: none
      name: Appodeal
      slug: appodeal
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
      status: profiled
      tags:
      - Advertising
      - Company
      - Mobile
      - Monetization
      tier: observed
      url: /providers/appodeal/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Grindr
      band: thin
      in_catalog: true
      kin_score: 32.1
      mcp:
        status: unknown
      name: PubNative
      slug: pubnative
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
      status: profiled
      tags:
      - AdTech
      - Company
      - Mobile
      - Monetization
      tier: observed
      url: /providers/pubnative/
    - agent_band: agent-ready
      agent_readiness: 33.5
      apps:
      - Grindr
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        source: https://github.com/PubMatic/pubmatic-mcp-server
        status: verified
      name: PubMatic
      slug: pubmatic
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Programmatic Advertising
      - Supply Side Platform
      tier: observed
      url: /providers/pubmatic/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Grindr
      band: emerging
      in_catalog: true
      kin_score: 16.2
      mcp:
        status: unknown
      name: Mintegral
      slug: mintegral
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
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
      - Grindr
      band: minimal
      in_catalog: true
      kin_score: 10.2
      mcp:
        status: none
      name: ironSource
      slug: ironsource
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
      status: profiled
      tags:
      - Advertising
      - Game Development
      - Mobile
      - Mobile Games
      tier: observed
      url: /providers/ironsource/
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
      - Bumble
      - Hinge
      - Tinder
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp: *id001
      name: Apple
      slug: apple
      sources:
      - https://bumble.com/en/privacy
      - https://hinge.co/privacy
      - https://policies.tinder.com/privacy/intl/en/
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Bumble
      - Hinge
      - Tinder
      band: developing
      in_catalog: true
      kin_score: 51.3
      mcp:
        status: none
      name: Google Play
      slug: google-play
      sources:
      - https://bumble.com/en/privacy
      - https://hinge.co/privacy
      - https://policies.tinder.com/privacy/intl/en/
      status: profiled
      tags:
      - Android
      - Application
      - Google Play
      - In-App Purchases
      tier: declared
      url: /providers/google-play/
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Duolicious
      band: thin
      in_catalog: true
      kin_score: 27.4
      mcp:
        source: https://www.revenuecat.com/docs/tools/mcp
        status: verified
      name: RevenueCat
      slug: revenuecat
      sources:
      - https://github.com/duolicious/duolicious-frontend/blob/main/package.json
      status: profiled
      tags:
      - Billing
      - In-App Purchases
      - Mobile
      - Subscription
      tier: observed
      url: /providers/revenuecat/
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
      - Grindr
      - Tinder
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 38.4
      apps:
      - Hinge
      band: strong
      in_catalog: true
      kin_score: 58.7
      mcp:
        status: none
      name: Snap Inc.
      slug: snap
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Advertising
      - Company
      - Marketing
      - Social Media
      tier: declared
      url: /providers/snap/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Hinge
      band: developing
      in_catalog: true
      kin_score: 47.7
      mcp:
        source: https://developers.pinterest.com/about-pinterest-mcp/
        status: verified
      name: Pinterest
      slug: pinterest
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Image
      - Social
      - Social Media
      - Video
      tier: declared
      url: /providers/pinterest/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Hinge
      band: developing
      in_catalog: true
      kin_score: 40.5
      mcp:
        status: none
      name: TikTok
      slug: tiktok
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Advertising
      - Commerce
      - Content
      - TikTok
      tier: declared
      url: /providers/tiktok/
    - agent_band: human-only
      agent_readiness: 1.7
      apps:
      - Hinge
      band: emerging
      in_catalog: true
      kin_score: 23.2
      mcp:
        source: https://thecirqle.com/mcp
        status: verified
      name: The Cirqle
      slug: the-cirqle
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Influencer Marketing
      - Performance Marketing
      tier: declared
      url: /providers/the-cirqle/
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
      - Bumble
      - Hinge
      - Tinder
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://hinge.co/hinge-data-recipients
      - https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
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
      - Grindr
      - Hinge
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id005
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/co.hinge.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
      status: profiled
      tags: &id006
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 15.8
      apps:
      - Hinge
      band: emerging
      in_catalog: true
      kin_score: 25.2
      mcp:
        status: none
      name: ServiceNow Cloud Observability (Lightstep)
      slug: lightstep
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - APM
      - Distributed Tracing
      - Microservices
      - Monitoring
      tier: declared
      url: /providers/lightstep/
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
      - Hinge
      - pH7Builder
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
      - https://hinge.co/hinge-data-recipients
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
      - Bumble
      - Duolicious
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://bumble.com/en/privacy
      - https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - pH7Builder
      band: developing
      in_catalog: true
      kin_score: 44.7
      mcp:
        status: none
      name: Braintree
      slug: braintree
      sources:
      - https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
      status: profiled
      tags:
      - Mobile
      - Payments
      - Subscription
      - Transaction
      tier: observed
      url: /providers/braintree/
    - agent_band: null
      agent_readiness: null
      apps:
      - pH7Builder
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Skeerel
      slug: skeerel
      sources:
      - https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
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
      - Bumble
      - Grindr
      - Hinge
      - Tinder
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id005
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/co.hinge.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Bumble
      - Grindr
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
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
      - Bumble
      - Grindr
      - Hinge
      - Tinder
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/co.hinge.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Tinder
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
  - capability:
      attribution: Turbo EA
      id: BC-3770.50
      key: audience-insights-research-management
      name: Audience Insights & Research Management
      url: /capabilities/audience-insights-research-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 52.7
      apps:
      - Hinge
      band: strong
      in_catalog: true
      kin_score: 63.9
      mcp:
        status: none
      name: UserTesting
      slug: usertesting
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Company
      - Human Insight
      - Usability Testing
      - User Research
      tier: declared
      url: /providers/usertesting/
    - agent_band: agent-ready
      agent_readiness: 35.6
      apps:
      - Hinge
      band: strong
      in_catalog: true
      kin_score: 56.7
      mcp:
        source: https://heymarvin.com/mcp/
        status: verified
      name: HeyMarvin
      slug: heymarvin
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Customer Insights
      - Software-as-a-Service
      tier: declared
      url: /providers/heymarvin/
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - Hinge
      band: emerging
      in_catalog: true
      kin_score: 25.3
      mcp:
        source: https://help.dscout.com/dscout-ai/dscout-mcp/set-up-the-dscout-mcp
        status: verified
      name: dscout
      slug: dscout
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - User Research
      - User Testing
      tier: declared
      url: /providers/dscout/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Bumble
      band: emerging
      in_catalog: true
      kin_score: 21.5
      mcp:
        status: unknown
      name: Kantar
      slug: kantar
      sources:
      - https://bumble.com/en/privacy
      status: profiled
      tags:
      - Analytics
      - Data
      - Insights
      - Market Research
      tier: declared
      url: /providers/kantar/
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Hinge
      - pH7Builder
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Web Services
      slug: amazon-web-services
      sources:
      - https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: observed
      url: /providers/amazon-web-services/
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - Hinge
      band: exemplar
      in_catalog: true
      kin_score: 68.9
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google
      slug: google
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: declared
      url: /providers/google/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Bumble
      band: exemplar
      in_catalog: true
      kin_score: 67.5
      mcp:
        source: https://github.com/googleapis/mcp-toolbox
        status: verified
      name: Google Cloud
      slug: google-cloud-platform
      sources:
      - https://bumble.com/en/privacy
      status: profiled
      tags:
      - API Management
      - Cloud Computing
      - Infrastructure
      - Platform-as-a-Service
      tier: declared
      url: /providers/google-cloud-platform/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Bumble
      - Hinge
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://bumble.com/en/privacy
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Hinge
      band: thin
      in_catalog: true
      kin_score: 34.7
      mcp:
        source: https://helpcenter.enterpret.com/en/articles/12665166-wisdom-mcp-server
        status: verified
      name: Enterpret
      slug: enterpret
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Company
      - Customer Feedback
      - Customer Intelligence
      - Voice of Customer
      tier: declared
      url: /providers/enterpret/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - Hinge
      - pH7Builder
      band: thin
      in_catalog: true
      kin_score: 31.5
      mcp:
        status: none
      name: MaxMind
      slug: maxmind
      sources:
      - https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Fraud Prevention
      - Geolocation
      - IP Intelligence
      - Risk Scoring
      tier: observed
      url: /providers/maxmind/
    - agent_band: agent-aware
      agent_readiness: 14.3
      apps:
      - Duolicious
      band: developing
      in_catalog: true
      kin_score: 39.9
      mcp:
        status: none
      name: RIPE NCC (RIPEstat)
      slug: ripe-ncc
      sources:
      - https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
      status: profiled
      tags:
      - Company
      - Internet
      - Not-for-profit
      - Regional Internet Registry
      tier: observed
      url: /providers/ripe-ncc/
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.6
      apps:
      - Bumble
      - Hinge
      band: thin
      in_catalog: true
      kin_score: 36.0
      mcp:
        source: https://www.typeform.com/developers/mcp
        status: verified
      name: Typeform
      slug: typeform
      sources:
      - https://bumble.com/en/privacy
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Forms
      - Lead Capture
      - Software-as-a-Service
      - Surveys
      tier: declared
      url: /providers/typeform/
    - agent_band: human-only
      agent_readiness: 4.9
      apps:
      - Hinge
      band: emerging
      in_catalog: true
      kin_score: 19.0
      mcp:
        status: unknown
      name: Alchemer
      slug: alchemer
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Data Collection
      - Experience Management
      - Feedback
      - Surveys
      tier: declared
      url: /providers/alchemer/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 55.1
      apps:
      - Hinge
      band: strong
      in_catalog: true
      kin_score: 63.3
      mcp:
        source: https://learn.hex.tech/docs/administration/mcp-server
        status: documented
      name: Hex
      slug: hex
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Analytics
      - Company
      - Data Science
      - Notebooks
      tier: declared
      url: /providers/hex/
    - agent_band: agent-native
      agent_readiness: 65.5
      apps:
      - Hinge
      band: strong
      in_catalog: true
      kin_score: 58.7
      mcp:
        source: https://docs.databricks.com/aws/en/generative-ai/mcp/
        status: verified
      name: Databricks
      slug: databricks
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cleanroom
      - Databricks
      tier: declared
      url: /providers/databricks/
  - capability:
      attribution: Turbo EA
      id: BC-430.30
      key: BC-430.30
      name: Contact Centre Operations Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.4
      apps:
      - Hinge
      band: developing
      in_catalog: true
      kin_score: 49.0
      mcp:
        status: none
      name: TELUS (TELUS Digital)
      slug: telus
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Broadband
      - Canada
      - Mobile Network Operator
      - Telecommunications
      tier: declared
      url: /providers/telus/
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Hinge
      band: minimal
      in_catalog: true
      kin_score: 9.5
      mcp:
        status: none
      name: Accenture
      slug: accenture
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - A2A
      - Consulting
      - Professional Services
      - Technology
      tier: declared
      url: /providers/accenture/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - Bumble
      - Hinge
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp: &id007
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://bumble.com/en/privacy
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags: &id008
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: declared
      url: /providers/twilio/
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
      - Grindr
      - Tinder
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        source: https://github.com/IABTechLab/agentic-real-time-framework
        status: verified
      name: IAB Tech Lab
      slug: iab-tech-lab
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grindrapp.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.tinder/latest/
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
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - pH7Builder
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp: *id007
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-ready
      agent_readiness: 28.9
      apps:
      - pH7Builder
      band: thin
      in_catalog: true
      kin_score: 38.8
      mcp:
        status: none
      name: Clickatell
      slug: clickatell
      sources:
      - https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
      status: profiled
      tags:
      - Company
      - Messaging
      - SMS
      - WhatsApp
      tier: observed
      url: /providers/clickatell/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60.10
      key: AE-150.60.10
      name: Async Video Messaging
      url: /capabilities/video-calling/
      via_parent: Video Calling
    providers:
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Hinge
      band: emerging
      in_catalog: true
      kin_score: 18.4
      mcp:
        status: none
      name: Loom
      slug: loom
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Async
      - Communications
      - Productivity
      - Video
      tier: declared
      url: /providers/loom/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - pH7Builder
      band: developing
      in_catalog: true
      kin_score: 41.2
      mcp:
        source: https://github.com/Automattic/mcp-server-gravatar
        status: verified
      name: Gravatar
      slug: gravatar
      sources:
      - https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
      status: profiled
      tags:
      - Avatars
      - Identity
      - Profiles
      - Social
      tier: observed
      url: /providers/gravatar/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.50
      key: AE-160.50
      name: Consent & Preferences
      url: /capabilities/consent-preferences/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 16.8
      apps:
      - Grindr
      band: thin
      in_catalog: true
      kin_score: 37.3
      mcp:
        status: none
      name: Ketch
      slug: ketch-io
      sources:
      - https://trust.grindr.com/en-US/privacy
      status: profiled
      tags:
      - Consent
      - Ketch
      - Preference Management
      - Privacy
      tier: declared
      url: /providers/ketch-io/
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 58.4
      apps:
      - Hinge
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
        status: verified
      name: Braze
      slug: braze
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Customer Engagement
      - Marketing Automation
      - Messaging
      - Push Notifications
      tier: declared
      url: /providers/braze/
  - capability:
      attribution: Turbo EA
      id: BC-620.30.30
      key: BC-620.30.30
      name: Cyber Threat Intelligence
      url: /capabilities/threat-detection-response-management/
      via_parent: Threat Detection & Response Management
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Duolicious
      band: emerging
      in_catalog: true
      kin_score: 15.3
      mcp:
        status: none
      name: FireHOL IP lists
      slug: firehol
      sources:
      - https://github.com/duolicious/duolicious-backend/tree/main/backend
      status: profiled
      tags:
      - Company
      - IP Reputation
      - Security
      - Threat Intelligence
      tier: observed
      url: /providers/firehol/
  - capability:
      attribution: Turbo EA
      id: BC-810.30
      key: experimentation-prototyping-management
      name: Experimentation & Prototyping Management
      url: /capabilities/experimentation-prototyping-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.9
      apps:
      - Hinge
      band: emerging
      in_catalog: true
      kin_score: 16.6
      mcp:
        source: https://docs.lovable.dev/integrations/lovable-mcp-server
        status: verified
      name: Lovable
      slug: lovable
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - App Builder
      - Artificial Intelligence
      - No-Code
      - Web Development
      tier: declared
      url: /providers/lovable/
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Hinge
      band: thin
      in_catalog: true
      kin_score: 35.9
      mcp:
        status: none
      name: Split Software
      slug: split
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/co.hinge.app/latest/
      status: profiled
      tags:
      - Experimentation
      - Feature Flags
      - Feature Management
      - Rollouts
      tier: observed
      url: /providers/split/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.3
      apps:
      - Hinge
      band: exemplar
      in_catalog: true
      kin_score: 87.2
      mcp:
        source: https://github.com/confluentinc/mcp-confluent
        status: verified
      name: Confluent
      slug: confluent
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Apache Kafka
      - Data Streaming
      - Event Streaming
      - Stream Processing
      tier: declared
      url: /providers/confluent/
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Hinge
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://developers.notion.com/docs/mcp
        status: verified
      name: Notion
      slug: notion
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Collaboration
      - Database
      - Ideas
      - Notes
      tier: declared
      url: /providers/notion/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Hinge
      band: thin
      in_catalog: true
      kin_score: 32.1
      mcp:
        status: unknown
      name: Unbabel
      slug: unbabel
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - LangOps
      - Language Operations
      - Localization
      - Translation
      tier: declared
      url: /providers/unbabel/
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Hinge
      band: developing
      in_catalog: true
      kin_score: 42.0
      mcp:
        status: none
      name: Reduct
      slug: reduct
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Application
      - Company
      - Transcription
      - Video
      tier: declared
      url: /providers/reduct/
  - capability:
      attribution: Turbo EA
      id: BC-130.50
      key: privacy-data-protection-management
      name: Privacy & Data Protection Management
      url: /capabilities/privacy-data-protection-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.5
      apps:
      - Grindr
      band: strong
      in_catalog: true
      kin_score: 57.8
      mcp:
        status: unknown
      name: TrustArc
      slug: trustarc
      sources:
      - https://trust.grindr.com/en-US/privacy
      status: profiled
      tags:
      - Identity
      - OAuth
      - Privacy
      - SCIM
      tier: observed
      url: /providers/trustarc/
  - capability:
      attribution: Turbo EA
      id: BC-430.30.30
      key: BC-430.30.30
      name: Quality Monitoring and Coaching
      url: /capabilities/contact-centre-operations-management/
      via_parent: Contact Centre Operations Management
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Hinge
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: MaestroQA
      slug: maestroqa
      sources:
      - https://hinge.co/hinge-data-recipients
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.4
      apps:
      - Hinge
      band: developing
      in_catalog: true
      kin_score: 47.5
      mcp:
        source: https://developer.calendly.com/calendly-mcp-server
        status: documented
      name: Calendly
      slug: calendly
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Appointments
      - Automation
      - Booking
      - Calendar
      tier: declared
      url: /providers/calendly/
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Hinge
      band: exemplar
      in_catalog: true
      kin_score: 78.4
      mcp:
        source: https://www.elastic.co/docs/solutions/search/mcp
        status: verified
      name: Elastic
      slug: elastic
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Analytics
      - Observability
      - Search
      - Security
      tier: declared
      url: /providers/elastic/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Bumble
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.bumble.app/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: Turbo EA
      id: BC-4200.50
      key: software-quality-engineering
      name: Software Quality Engineering
      url: /capabilities/software-quality-engineering/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.8
      apps:
      - Hinge
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        source: https://github.com/browserstack/mcp-server
        status: verified
      name: BrowserStack
      slug: browserstack
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Accessibility
      - Appium
      - Application
      - Automation
      tier: declared
      url: /providers/browserstack/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Hinge
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Bumble
      - Duolicious
      - Hinge
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://bumble.com/en/privacy
      - https://github.com/duolicious/duolicious-backend/blob/main/backend/docker-compose.yml
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
  - capability:
      attribution: Turbo EA
      id: BC-610.60
      key: artificial-intelligence-management
      name: Artificial Intelligence Management
      url: /capabilities/artificial-intelligence-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.5
      apps:
      - Hinge
      band: thin
      in_catalog: true
      kin_score: 36.6
      mcp:
        source: https://registry.npmjs.org/@arizeai/phoenix-mcp
        status: verified
      name: Arize AI
      slug: arize-ai
      sources:
      - https://hinge.co/hinge-data-recipients
      status: profiled
      tags:
      - LLM Observability
      - ML Monitoring
      - Open Source
      - OpenTelemetry
      tier: declared
      url: /providers/arize-ai/
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.30
      key: AE-100.70.30
      name: Support & Assist Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    providers:
    - agent_band: agent-aware
      agent_readiness: 9.1
      apps:
      - Bumble
      band: emerging
      in_catalog: true
      kin_score: 17.9
      mcp:
        status: none
      name: Sierra
      slug: sierra
      sources:
      - https://bumble.com/en/privacy
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Chat
      - Conversational AI
      tier: declared
      url: /providers/sierra/
  layer: agent
summary:
  coverage_pct: 96.4
  declared_only: 47
  distinct_providers: 83
  in_catalog: 80
  mcp:
    documented: 2
    none: 38
    unchecked: 3
    verified: 33
  mcp_verified: 33
  mean_kin_score: 47.7
  observed: 36
  queued: 3
  reference_apps: 7
title: 'Dating: application blueprint'
---
