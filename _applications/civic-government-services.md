---
access: understanding
agent_layer: []
apps:
- anchor: decidim
  counts:
    declared: 4
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://github.com/decidim/decidim/blob/develop/Gemfile.lock
  - route: documentation
    url: https://docs.decidim.org/en/develop/services/machine_translations.html
  - route: documentation
    url: https://docs.decidim.org/en/develop/services/maps.html
  - route: documentation
    url: https://docs.decidim.org/en/develop/services/social_providers.html
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
    source: https://github.com/decidim/decidim/blob/develop/Gemfile.lock
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
    source: https://github.com/decidim/decidim/blob/develop/Gemfile.lock
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
    name: Twitter
    provider: x
    says: ships the Twitter SDK or integration code
    source: https://github.com/decidim/decidim/blob/develop/Gemfile.lock
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: domain
    name: HERE
    provider: here
    says: lists HERE as an integration
    source: https://docs.decidim.org/en/develop/services/maps.html
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
    name: LibreTranslate
    provider: libre-translate
    says: lists LibreTranslate as an integration
    source: https://docs.decidim.org/en/develop/services/machine_translations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: domain
    name: Nominatim
    provider: nominatim
    says: lists Nominatim as an integration
    source: https://docs.decidim.org/en/develop/services/maps.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: domain
    name: OpenStreetMap
    provider: openstreetmap
    says: lists OpenStreetMap as an integration
    source: https://docs.decidim.org/en/develop/services/maps.html
    tier: declared
  kind: self-hosted
  name: Decidim
  page: /applications/civic-government-services/decidim/
  slug: decidim
  url: https://github.com/decidim/decidim
- anchor: consul-democracy
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: dependency manifest
    url: https://github.com/consuldemocracy/consuldemocracy/blob/master/Gemfile
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
    name: Airbrake
    provider: airbrake
    says: ships the Airbrake SDK or integration code
    source: https://github.com/consuldemocracy/consuldemocracy/blob/master/Gemfile
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
    source: https://github.com/consuldemocracy/consuldemocracy/blob/master/Gemfile
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
    source: https://github.com/consuldemocracy/consuldemocracy/blob/master/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: common
    name: Microsoft Translator (Bing)
    provider: microsoft-translator
    says: ships the Microsoft Translator (Bing) SDK or integration code
    source: https://github.com/consuldemocracy/consuldemocracy/blob/master/Gemfile
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
    name: Twitter
    provider: x
    says: ships the Twitter SDK or integration code
    source: https://github.com/consuldemocracy/consuldemocracy/blob/master/Gemfile
    tier: observed
  kind: self-hosted
  name: CONSUL Democracy
  page: /applications/civic-government-services/consul-democracy/
  slug: consul-democracy
  url: https://github.com/consuldemocracy/consuldemocracy
- anchor: fixmystreet
  counts:
    declared: 5
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://github.com/mysociety/fixmystreet/blob/master/cpanfile
  - route: documentation
    url: https://fixmystreet.org/customising/config/
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
    source: https://github.com/mysociety/fixmystreet/blob/master/cpanfile
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
    source: https://github.com/mysociety/fixmystreet/blob/master/cpanfile
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
    name: Twitter
    provider: x
    says: ships the Twitter SDK or integration code
    source: https://github.com/mysociety/fixmystreet/blob/master/cpanfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: lists Amazon S3 as an integration
    source: https://fixmystreet.org/customising/config/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: domain
    name: Bing Maps
    provider: bing-maps
    says: lists Bing Maps as an integration
    source: https://fixmystreet.org/customising/config/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: domain
    name: Google Maps
    provider: google-maps
    says: lists Google Maps as an integration
    source: https://fixmystreet.org/customising/config/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: domain
    name: MapIt (mySociety)
    provider: mapit
    says: lists MapIt (mySociety) as an integration
    source: https://fixmystreet.org/customising/config/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: domain
    name: OpenStreetMap
    provider: openstreetmap
    says: lists OpenStreetMap as an integration
    source: https://fixmystreet.org/customising/config/
    tier: declared
  kind: self-hosted
  name: FixMyStreet
  page: /applications/civic-government-services/fixmystreet/
  slug: fixmystreet
  url: https://github.com/mysociety/fixmystreet
- anchor: alaveteli
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://github.com/mysociety/alaveteli/blob/develop/Gemfile
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/mysociety/alaveteli/blob/develop/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://github.com/mysociety/alaveteli/blob/develop/Gemfile
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
    name: Google reCAPTCHA
    provider: google-recaptcha
    says: ships the Google reCAPTCHA SDK or integration code
    source: https://github.com/mysociety/alaveteli/blob/develop/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/mysociety/alaveteli/blob/develop/Gemfile
    tier: observed
  kind: self-hosted
  name: Alaveteli
  page: /applications/civic-government-services/alaveteli/
  slug: alaveteli
  url: https://github.com/mysociety/alaveteli
- anchor: go-vocal-(citizenlab)
  counts:
    declared: 0
    observed: 10
  evidence:
  - route: dependency manifest
    url: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Amazon Bedrock
    provider: amazon-bedrock
    says: ships the Amazon Bedrock SDK or integration code
    source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
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
    name: Amazon CloudFront
    provider: cloudfront
    says: ships the Amazon CloudFront SDK or integration code
    source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
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
    source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
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
    source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
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
    source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
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
    source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
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
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
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
    source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
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
    source: https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
    tier: observed
  kind: open-source-saas
  name: Go Vocal (CitizenLab)
  page: /applications/civic-government-services/go-vocal-citizenlab/
  slug: go-vocal-citizenlab
  url: https://github.com/CitizenLabDotCo/citizenlab
- anchor: seeclickfix-(civicplus)
  counts:
    declared: 15
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
  - route: integrations page
    url: https://www.civicplus.com/seeclickfix-311-crm/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Amazon Web Services (Mobile Analytics / Amplify)
    provider: amazon-web-services
    says: ships the Amazon Web Services (Mobile Analytics / Amplify) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3240
      key: permits-licences-authorisations-management
      name: Permits, Licences & Authorisations Management
      url: /capabilities/permits-licences-authorisations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Accela Automation
    provider: accela
    says: lists Accela Automation as an integration
    source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1010.10
      key: work-order-management
      name: Work Order Management
      url: /capabilities/work-order-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bigbelly
    provider: bigbelly
    says: lists Bigbelly as an integration
    source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1030.50
      key: maintenance-work-order-management
      name: Maintenance Work Order Management
      url: /capabilities/maintenance-work-order-management/
      via_parent: null
    credit: null
    layer: domain
    name: Brightly Software
    provider: brightly-software
    says: lists Brightly Software as an integration
    source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3240
      key: permits-licences-authorisations-management
      name: Permits, Licences & Authorisations Management
      url: /capabilities/permits-licences-authorisations-management/
      via_parent: null
    credit: null
    layer: domain
    name: CentralSquare Technologies
    provider: centralsquare
    says: lists CentralSquare Technologies as an integration
    source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1030.50
      key: maintenance-work-order-management
      name: Maintenance Work Order Management
      url: /capabilities/maintenance-work-order-management/
      via_parent: null
    credit: null
    layer: domain
    name: Cityworks (Trimble)
    provider: cityworks
    says: lists Cityworks (Trimble) as an integration
    source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-5060.40
      key: geospatial-survey-management
      name: Geospatial & Survey Management
      url: /capabilities/geospatial-survey-management/
      via_parent: null
    credit: null
    layer: domain
    name: Esri ArcGIS
    provider: esri
    says: lists Esri ArcGIS as an integration
    source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1030.50
      key: maintenance-work-order-management
      name: Maintenance Work Order Management
      url: /capabilities/maintenance-work-order-management/
      via_parent: null
    credit: null
    layer: domain
    name: IBM (Maximo)
    provider: ibm
    says: lists IBM (Maximo) as an integration
    source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1030.50
      key: maintenance-work-order-management
      name: Maintenance Work Order Management
      url: /capabilities/maintenance-work-order-management/
      via_parent: null
    credit: null
    layer: domain
    name: Infor
    provider: infor
    says: lists Infor as an integration
    source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3220
      key: citizen-constituent-service-management
      name: Citizen & Constituent Service Management
      url: /capabilities/citizen-constituent-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Dynamics
    provider: microsoft-dynamics-365
    says: lists Microsoft Dynamics as an integration
    source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1030.50
      key: maintenance-work-order-management
      name: Maintenance Work Order Management
      url: /capabilities/maintenance-work-order-management/
      via_parent: null
    credit: null
    layer: domain
    name: OpenGov
    provider: opengov
    says: lists OpenGov as an integration
    source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3220
      key: citizen-constituent-service-management
      name: Citizen & Constituent Service Management
      url: /capabilities/citizen-constituent-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Oracle Service Cloud
    provider: oracle
    says: lists Oracle Service Cloud as an integration
    source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1030.50
      key: maintenance-work-order-management
      name: Maintenance Work Order Management
      url: /capabilities/maintenance-work-order-management/
      via_parent: null
    credit: null
    layer: domain
    name: PubWorks
    provider: pubworks
    says: lists PubWorks as an integration
    source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3240
      key: permits-licences-authorisations-management
      name: Permits, Licences & Authorisations Management
      url: /capabilities/permits-licences-authorisations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Tyler Technologies
    provider: tyler-technologies
    says: lists Tyler Technologies as an integration
    source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3220
      key: citizen-constituent-service-management
      name: Citizen & Constituent Service Management
      url: /capabilities/citizen-constituent-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Verint (KANA Lagan)
    provider: verint-systems
    says: lists Verint (KANA Lagan) as an integration
    source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1030.50
      key: maintenance-work-order-management
      name: Maintenance Work Order Management
      url: /capabilities/maintenance-work-order-management/
      via_parent: null
    credit: null
    layer: domain
    name: VUEWorks
    provider: vueworks
    says: lists VUEWorks as an integration
    source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
    tier: declared
  kind: commercial
  name: SeeClickFix (CivicPlus)
  page: /applications/civic-government-services/seeclickfix-civicplus/
  slug: seeclickfix-civicplus
  url: https://www.civicplus.com/seeclickfix-311-crm/
- anchor: accela-civic-platform
  counts:
    declared: 4
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.accela.com/partners/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: ACI Worldwide
    provider: aci-worldwide
    says: lists ACI Worldwide as an integration
    source: https://www.accela.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1130
      key: engineering-document-management
      name: Engineering Document Management
      url: /capabilities/engineering-document-management/
      via_parent: null
    credit: null
    layer: domain
    name: Adobe
    provider: adobe
    says: lists Adobe as an integration
    source: https://www.accela.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-946
      key: AE-946
      name: Electronic Plan Review
      url: /capabilities/electronic-plan-review/
      via_parent: null
    credit: null
    layer: domain
    name: Avolve Software
    provider: avolve-software
    says: lists Avolve Software as an integration
    source: https://www.accela.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3220
      key: citizen-constituent-service-management
      name: Citizen & Constituent Service Management
      url: /capabilities/citizen-constituent-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: buildingeye (AgencyCounter)
    provider: buildingeye
    says: lists buildingeye (AgencyCounter) as an integration
    source: https://www.accela.com/partners/
    tier: declared
  kind: commercial
  name: Accela Civic Platform
  page: /applications/civic-government-services/accela-civic-platform/
  slug: accela-civic-platform
  url: https://www.accela.com/
- anchor: granicus-(govdelivery)
  counts:
    declared: 1
    observed: 0
  evidence:
  - route: integrations page
    url: https://granicus.com/partners/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-5080
      key: infrastructure-operations-management
      name: Infrastructure Operations Management
      url: /capabilities/infrastructure-operations-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon Web Services
    provider: amazon-web-services
    says: lists Amazon Web Services as an integration
    source: https://granicus.com/partners/
    tier: declared
  kind: commercial
  name: Granicus (govDelivery)
  page: /applications/civic-government-services/granicus-govdelivery/
  slug: granicus-govdelivery
  url: https://granicus.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: civic-government-services
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Government
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: News & Magazines
  store: google-play
  url: https://play.google.com/store/apps/category/NEWS_AND_MAGAZINES
- category: Polls and Events
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#polls-and-events
- category: Public Sector
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Public Sector
  store: aws-marketplace
  url: https://aws.amazon.com/marketplace/solutions/public-sector
name: Civic & Government Services
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: residents sign in with existing social accounts
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: domain
  why: reports and proposals are placed on a map
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: domain
  why: addresses resolved to points for reports
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: common
  why: multilingual participation
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error tracking
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: SMS notifications and verification for residents
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  fit: nearest
  layer: common
  why: photo and attachment storage; no generic object-storage capability
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: fees, permits and subscriptions paid online
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: anti-spam on public request forms
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: AI summarisation of resident input
- capability:
    attribution: Turbo EA
    id: BC-3740.30
    key: content-delivery-network-operations
    name: Content Delivery Network Operations
    url: /capabilities/content-delivery-network-operations/
    via_parent: null
  fit: exact
  layer: common
  why: static asset delivery
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: nearest
  layer: common
  why: in-app support chat
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: notification email
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: usage analytics
- capability:
    attribution: Turbo EA
    id: BC-5060.40
    key: geospatial-survey-management
    name: Geospatial & Survey Management
    url: /capabilities/geospatial-survey-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: GIS layers of record for assets and requests
- capability:
    attribution: Turbo EA
    id: BC-1030.50
    key: maintenance-work-order-management
    name: Maintenance Work Order Management
    url: /capabilities/maintenance-work-order-management/
    via_parent: null
  fit: exact
  layer: domain
  why: service requests become asset work orders
- capability:
    attribution: Turbo EA
    id: BC-3240
    key: permits-licences-authorisations-management
    name: Permits, Licences & Authorisations Management
    url: /capabilities/permits-licences-authorisations-management/
    via_parent: null
  fit: exact
  layer: domain
  why: code enforcement and permitting systems of record
- capability:
    attribution: Turbo EA
    id: BC-3220
    key: citizen-constituent-service-management
    name: Citizen & Constituent Service Management
    url: /capabilities/citizen-constituent-service-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 311 / constituent CRM handoff
- capability:
    attribution: Turbo EA
    id: BC-1010.10
    key: work-order-management
    name: Work Order Management
    url: /capabilities/work-order-management/
    via_parent: null
  fit: gap
  layer: domain
  why: smart waste bins report fill levels; no capability for connected street furniture
- capability:
    attribution: Turbo EA
    id: BC-1130
    key: engineering-document-management
    name: Engineering Document Management
    url: /capabilities/engineering-document-management/
    via_parent: null
  fit: gap
  layer: domain
  why: electronic plan review of permit drawings; no capability for plan review
- capability:
    attribution: Turbo EA
    id: BC-5080
    key: infrastructure-operations-management
    name: Infrastructure Operations Management
    url: /capabilities/infrastructure-operations-management/
    via_parent: null
  fit: nearest
  layer: common
  why: cloud hosting partner
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: domain
  why: 'the channels themselves: every app publishes to and reads from social networks (also hosts the social-listening gap rows)'
- capability:
    attribution: API Evangelist extension
    id: AE-946
    key: AE-946
    name: Electronic Plan Review
    url: /capabilities/electronic-plan-review/
    via_parent: null
  fit: exact
  layer: domain
  why: Avolve Software (Electronic Plan Review)
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-1030.50
      key: maintenance-work-order-management
      name: Maintenance Work Order Management
      url: /capabilities/maintenance-work-order-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - SeeClickFix (CivicPlus)
      band: exemplar
      in_catalog: true
      kin_score: 71.0
      mcp:
        status: none
      name: Infor
      slug: infor
      sources:
      - https://www.civicplus.com/seeclickfix-311-crm/integrations/
      status: profiled
      tags:
      - Cloud
      - ERP
      - Manufacturing
      - Supply Chain
      tier: declared
      url: /providers/infor/
    - agent_band: agent-ready
      agent_readiness: 35.6
      apps:
      - SeeClickFix (CivicPlus)
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        source: https://github.com/IBM/mcp
        status: verified
      name: IBM (Maximo)
      slug: ibm
      sources:
      - https://www.civicplus.com/seeclickfix-311-crm/integrations/
      status: profiled
      tags:
      - API Management
      - Artificial Intelligence
      - Database
      - IBM
      tier: declared
      url: /providers/ibm/
    - agent_band: agent-native
      agent_readiness: 60.1
      apps:
      - SeeClickFix (CivicPlus)
      band: developing
      in_catalog: true
      kin_score: 48.1
      mcp:
        status: none
      name: OpenGov
      slug: opengov
      sources:
      - https://www.civicplus.com/seeclickfix-311-crm/integrations/
      status: profiled
      tags:
      - GovTech
      - Government
      - Permitting
      - Public Sector
      tier: declared
      url: /providers/opengov/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - SeeClickFix (CivicPlus)
      band: thin
      in_catalog: true
      kin_score: 30.0
      mcp:
        status: unchecked
      name: VUEWorks
      slug: vueworks
      sources:
      - https://www.civicplus.com/seeclickfix-311-crm/integrations/
      status: profiled
      tags:
      - Asset Management
      - Enterprise Software
      - Infrastructure
      - Maintenance Management
      tier: declared
      url: /providers/vueworks/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - SeeClickFix (CivicPlus)
      band: minimal
      in_catalog: true
      kin_score: 6.2
      mcp:
        status: unchecked
      name: PubWorks
      slug: pubworks
      sources:
      - https://www.civicplus.com/seeclickfix-311-crm/integrations/
      status: profiled
      tags:
      - Cloud
      - Company
      - Municipal
      - Software-as-a-Service
      tier: declared
      url: /providers/pubworks/
    - agent_band: null
      agent_readiness: null
      apps:
      - SeeClickFix (CivicPlus)
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Brightly Software
      slug: brightly-software
      sources:
      - https://www.civicplus.com/seeclickfix-311-crm/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - SeeClickFix (CivicPlus)
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Cityworks (Trimble)
      slug: cityworks
      sources:
      - https://www.civicplus.com/seeclickfix-311-crm/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.3
      apps:
      - Decidim
      - FixMyStreet
      band: developing
      in_catalog: true
      kin_score: 45.5
      mcp:
        status: none
      name: OpenStreetMap
      slug: openstreetmap
      sources:
      - https://docs.decidim.org/en/develop/services/maps.html
      - https://fixmystreet.org/customising/config/
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Mapping
      - Open Data
      tier: declared
      url: /providers/openstreetmap/
    - agent_band: agent-native
      agent_readiness: 54.4
      apps:
      - Decidim
      band: exemplar
      in_catalog: true
      kin_score: 79.0
      mcp:
        status: none
      name: HERE
      slug: here
      sources:
      - https://docs.decidim.org/en/develop/services/maps.html
      status: profiled
      tags:
      - Location
      - Mapping
      - Maps
      - Spatial
      tier: declared
      url: /providers/here/
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - FixMyStreet
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps
      slug: google-maps
      sources:
      - https://fixmystreet.org/customising/config/
      status: profiled
      tags:
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: declared
      url: /providers/google-maps/
    - agent_band: human-only
      agent_readiness: 3.5
      apps:
      - FixMyStreet
      band: thin
      in_catalog: true
      kin_score: 28.9
      mcp:
        status: none
      name: Bing Maps
      slug: bing-maps
      sources:
      - https://fixmystreet.org/customising/config/
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Maps
      - Routing
      tier: declared
      url: /providers/bing-maps/
  - capability:
      attribution: Turbo EA
      id: BC-3220
      key: citizen-constituent-service-management
      name: Citizen & Constituent Service Management
      url: /capabilities/citizen-constituent-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.8
      apps:
      - SeeClickFix (CivicPlus)
      band: exemplar
      in_catalog: true
      kin_score: 70.4
      mcp:
        source: https://github.com/oracle/mcp
        status: verified
      name: Oracle Service Cloud
      slug: oracle
      sources:
      - https://www.civicplus.com/seeclickfix-311-crm/integrations/
      status: profiled
      tags:
      - Cloud
      - Database
      - Enterprise
      - Oracle
      tier: declared
      url: /providers/oracle/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - SeeClickFix (CivicPlus)
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        source: https://github.com/microsoft/Dataverse-MCP
        status: verified
      name: Microsoft Dynamics
      slug: microsoft-dynamics-365
      sources:
      - https://www.civicplus.com/seeclickfix-311-crm/integrations/
      status: profiled
      tags:
      - Business Applications
      - CRM
      - Cloud
      - Enterprise
      tier: declared
      url: /providers/microsoft-dynamics-365/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Accela Civic Platform
      band: emerging
      in_catalog: true
      kin_score: 11.0
      mcp:
        status: unchecked
      name: buildingeye (AgencyCounter)
      slug: buildingeye
      sources:
      - https://www.accela.com/partners/
      status: profiled
      tags:
      - Accessibility
      - GIS
      - GovTech
      - Public Data
      tier: declared
      url: /providers/buildingeye/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - SeeClickFix (CivicPlus)
      band: minimal
      in_catalog: true
      kin_score: 7.9
      mcp:
        status: none
      name: Verint (KANA Lagan)
      slug: verint-systems
      sources:
      - https://www.civicplus.com/seeclickfix-311-crm/integrations/
      status: profiled
      tags:
      - Analytics
      - Customer Engagement
      - Security
      tier: declared
      url: /providers/verint-systems/
  - capability:
      attribution: Turbo EA
      id: BC-3240
      key: permits-licences-authorisations-management
      name: Permits, Licences & Authorisations Management
      url: /capabilities/permits-licences-authorisations-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.1
      apps:
      - SeeClickFix (CivicPlus)
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        status: none
      name: Accela Automation
      slug: accela
      sources:
      - https://www.civicplus.com/seeclickfix-311-crm/integrations/
      status: profiled
      tags:
      - GovTech
      - Government
      - Licensing
      - Permitting
      tier: declared
      url: /providers/accela/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - SeeClickFix (CivicPlus)
      band: emerging
      in_catalog: true
      kin_score: 23.3
      mcp:
        status: unchecked
      name: CentralSquare Technologies
      slug: centralsquare
      sources:
      - https://www.civicplus.com/seeclickfix-311-crm/integrations/
      status: profiled
      tags:
      - Cloud Software
      - Company
      - Government
      - Public Safety
      tier: declared
      url: /providers/centralsquare/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - SeeClickFix (CivicPlus)
      band: emerging
      in_catalog: true
      kin_score: 15.1
      mcp:
        status: unknown
      name: Tyler Technologies
      slug: tyler-technologies
      sources:
      - https://www.civicplus.com/seeclickfix-311-crm/integrations/
      status: profiled
      tags:
      - Company
      - Government
      - Public Sector
      - Software
      tier: declared
      url: /providers/tyler-technologies/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - Decidim
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Nominatim
      slug: nominatim
      sources:
      - https://docs.decidim.org/en/develop/services/maps.html
      status: profiled
      tags:
      - Geocoding
      - Location Services
      - Maps
      - OpenStreetMap
      tier: declared
      url: /providers/nominatim/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - FixMyStreet
      band: minimal
      in_catalog: true
      kin_score: 2.5
      mcp:
        status: unchecked
      name: MapIt (mySociety)
      slug: mapit
      sources:
      - https://fixmystreet.org/customising/config/
      status: profiled
      tags:
      - Company
      - Location
      - Mapping
      - United Kingdom
      tier: declared
      url: /providers/mapit/
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
      - Alaveteli
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/mysociety/alaveteli/blob/develop/Gemfile
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Accela Civic Platform
      band: developing
      in_catalog: true
      kin_score: 46.5
      mcp:
        source: https://docs.aciworldwide.com/node/323
        status: verified
      name: ACI Worldwide
      slug: aci-worldwide
      sources:
      - https://www.accela.com/partners/
      status: profiled
      tags:
      - Payment Gateway
      - Payment Processing
      - Payments
      - United States
      tier: declared
      url: /providers/aci-worldwide/
  - capability:
      attribution: API Evangelist extension
      id: AE-946
      key: AE-946
      name: Electronic Plan Review
      url: /capabilities/electronic-plan-review/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Accela Civic Platform
      band: minimal
      in_catalog: true
      kin_score: 9.3
      mcp:
        status: unchecked
      name: Avolve Software
      slug: avolve-software
      sources:
      - https://www.accela.com/partners/
      status: profiled
      tags:
      - GIS
      - Government
      - Infrastructure
      - Software
      tier: declared
      url: /providers/avolve-software/
  - capability:
      attribution: Turbo EA
      id: BC-1130
      key: engineering-document-management
      name: Engineering Document Management
      url: /capabilities/engineering-document-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.9
      apps:
      - Accela Civic Platform
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://github.com/adobe/cq-quickstart-mcp-server
        status: verified
      name: Adobe
      slug: adobe
      sources:
      - https://www.accela.com/partners/
      status: profiled
      tags:
      - Adobe
      - Analytics
      - E-Signature
      - Fortune 1000
      tier: declared
      url: /providers/adobe/
  - capability:
      attribution: Turbo EA
      id: BC-5060.40
      key: geospatial-survey-management
      name: Geospatial & Survey Management
      url: /capabilities/geospatial-survey-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 49.1
      apps:
      - SeeClickFix (CivicPlus)
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp:
        status: none
      name: Esri ArcGIS
      slug: esri
      sources:
      - https://www.civicplus.com/seeclickfix-311-crm/integrations/
      status: profiled
      tags:
      - GIS
      - Geographic
      - Geospatial
      - Location
      tier: declared
      url: /providers/esri/
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
      - SeeClickFix (CivicPlus)
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id001
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
      status: profiled
      tags: &id002
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: Turbo EA
      id: BC-1010.10
      key: work-order-management
      name: Work Order Management
      url: /capabilities/work-order-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - SeeClickFix (CivicPlus)
      band: minimal
      in_catalog: true
      kin_score: 5.1
      mcp:
        status: unchecked
      name: Bigbelly
      slug: bigbelly
      sources:
      - https://www.civicplus.com/seeclickfix-311-crm/integrations/
      status: profiled
      tags:
      - Municipal Solutions
      - Public Space
      - Smart Bins
      - Waste Management
      tier: declared
      url: /providers/bigbelly/
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
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - CONSUL Democracy
      - Decidim
      - FixMyStreet
      - Go Vocal (CitizenLab)
      - SeeClickFix (CivicPlus)
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id001
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
      - https://github.com/consuldemocracy/consuldemocracy/blob/master/Gemfile
      - https://github.com/decidim/decidim/blob/develop/Gemfile.lock
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - CONSUL Democracy
      - Decidim
      - FixMyStreet
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: Twitter
      slug: x
      sources:
      - https://github.com/consuldemocracy/consuldemocracy/blob/master/Gemfile
      - https://github.com/decidim/decidim/blob/develop/Gemfile.lock
      - https://github.com/mysociety/fixmystreet/blob/master/cpanfile
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: observed
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - CONSUL Democracy
      - Decidim
      - Go Vocal (CitizenLab)
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
      - https://github.com/consuldemocracy/consuldemocracy/blob/master/Gemfile
      - https://github.com/decidim/decidim/blob/develop/Gemfile.lock
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Alaveteli
      - FixMyStreet
      - Go Vocal (CitizenLab)
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://fixmystreet.org/customising/config/
      - https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
      - https://github.com/mysociety/alaveteli/blob/develop/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Alaveteli
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://github.com/mysociety/alaveteli/blob/develop/Gemfile
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - SeeClickFix (CivicPlus)
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp: &id005
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Web Services (Mobile Analytics / Amplify)
      slug: amazon-web-services
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
      status: profiled
      tags: &id006
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: observed
      url: /providers/amazon-web-services/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - SeeClickFix (CivicPlus)
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
      status: profiled
      tags: &id004
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - SeeClickFix (CivicPlus)
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id001
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Go Vocal (CitizenLab)
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
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
      - Go Vocal (CitizenLab)
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
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
      - SeeClickFix (CivicPlus)
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id003
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - CONSUL Democracy
      band: emerging
      in_catalog: true
      kin_score: 25.8
      mcp:
        status: none
      name: Airbrake
      slug: airbrake
      sources:
      - https://github.com/consuldemocracy/consuldemocracy/blob/master/Gemfile
      status: profiled
      tags:
      - Application Performance Monitoring
      - DevOps
      - Error Monitoring
      - Observability
      tier: observed
      url: /providers/airbrake/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - CONSUL Democracy
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Microsoft Translator (Bing)
      slug: microsoft-translator
      sources:
      - https://github.com/consuldemocracy/consuldemocracy/blob/master/Gemfile
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Decidim
      band: emerging
      in_catalog: true
      kin_score: 24.3
      mcp:
        source: https://github.com/LibreTranslate/LibreTranslate-MCP
        status: verified
      name: LibreTranslate
      slug: libre-translate
      sources:
      - https://docs.decidim.org/en/develop/services/machine_translations.html
      status: profiled
      tags:
      - Machine Translation
      - Natural Language Processing
      - Open Source
      - Translation
      tier: declared
      url: /providers/libre-translate/
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
      - FixMyStreet
      - Go Vocal (CitizenLab)
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
      - https://github.com/mysociety/fixmystreet/blob/master/cpanfile
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
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Alaveteli
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://github.com/mysociety/alaveteli/blob/develop/Gemfile
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: observed
      url: /providers/google-recaptcha/
  - capability:
      attribution: Turbo EA
      id: BC-3740.30
      key: content-delivery-network-operations
      name: Content Delivery Network Operations
      url: /capabilities/content-delivery-network-operations/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Go Vocal (CitizenLab)
      band: exemplar
      in_catalog: true
      kin_score: 79.6
      mcp:
        status: none
      name: Amazon CloudFront
      slug: cloudfront
      sources:
      - https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - CDN
      - Caching
      - Content Delivery
      tier: observed
      url: /providers/cloudfront/
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
      - Go Vocal (CitizenLab)
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
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
      id: BC-5080
      key: infrastructure-operations-management
      name: Infrastructure Operations Management
      url: /capabilities/infrastructure-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Granicus (govDelivery)
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp: *id005
      name: Amazon Web Services
      slug: amazon-web-services
      sources:
      - https://granicus.com/partners/
      status: profiled
      tags: *id006
      tier: declared
      url: /providers/amazon-web-services/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Go Vocal (CitizenLab)
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
      status: profiled
      tags:
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailgun/
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
      agent_readiness: 48.3
      apps:
      - Go Vocal (CitizenLab)
      band: strong
      in_catalog: true
      kin_score: 64.3
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Bedrock
      slug: amazon-bedrock
      sources:
      - https://github.com/CitizenLabDotCo/citizenlab/blob/master/back/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Artificial Intelligence
      - Foundation Models
      - Generative AI
      tier: observed
      url: /providers/amazon-bedrock/
  layer: agent
summary:
  coverage_pct: 93.2
  declared_only: 27
  distinct_providers: 44
  in_catalog: 41
  mcp:
    documented: 0
    none: 15
    unchecked: 10
    verified: 18
  mcp_verified: 18
  mean_kin_score: 50.1
  observed: 17
  queued: 3
  reference_apps: 8
title: 'Civic & Government Services: application blueprint'
---
