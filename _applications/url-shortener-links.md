---
access: understanding
agent_layer: []
apps:
- anchor: dub
  counts:
    declared: 0
    observed: 25
  evidence:
  - route: dependency manifest
    url: https://github.com/dubinc/dub/blob/main/apps/web/package.json
  - route: source code
    url: https://github.com/dubinc/dub/blob/main/apps/web/.env.example
  - route: source code
    url: https://github.com/dubinc/dub/tree/main/apps/web/lib
  - route: source code
    url: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations
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
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://github.com/dubinc/dub/blob/main/apps/web/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: null
    layer: domain
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/appsflyer
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
    name: Axiom
    provider: axiom-co
    says: ships the Axiom SDK or integration code
    source: https://github.com/dubinc/dub/blob/main/apps/web/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Bitly
    provider: bitly
    says: ships the Bitly SDK or integration code
    source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/bitly
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.10
      key: AE-230.20.10
      name: Exchange Rates
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    credit: null
    layer: domain
    name: CurrencyAPI
    provider: currencyapi
    says: ships the CurrencyAPI SDK or integration code
    source: https://github.com/dubinc/dub/tree/main/apps/web/lib/currencyapi
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Dynadot
    provider: dynadot
    says: ships the Dynadot SDK or integration code
    source: https://github.com/dubinc/dub/tree/main/apps/web/lib/dynadot
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
    source: https://github.com/dubinc/dub/blob/main/apps/web/package.json
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
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/dubinc/dub/blob/main/apps/web/.env.example
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Ads
    provider: google-ads
    says: ships the Google Ads SDK or integration code
    source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/google-ads
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
    source: https://github.com/dubinc/dub/blob/main/apps/web/.env.example
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
    source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/hubspot
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
    source: https://github.com/dubinc/dub/blob/main/apps/web/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: PlanetScale
    provider: planetscale
    says: ships the PlanetScale SDK or integration code
    source: https://github.com/dubinc/dub/blob/main/apps/web/package.json
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
    name: Resend
    provider: resend
    says: ships the Resend SDK or integration code
    source: https://github.com/dubinc/dub/blob/main/apps/web/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Shopify
    provider: shopify
    says: ships the Shopify SDK or integration code
    source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/shopify
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: null
    layer: domain
    name: Singular
    provider: singular
    says: ships the Singular SDK or integration code
    source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/singular
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/slack
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/stripe
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
    source: https://github.com/dubinc/dub/blob/main/apps/web/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Tinybird
    provider: tinybird
    says: ships the Tinybird SDK or integration code
    source: https://github.com/dubinc/dub/blob/main/apps/web/.env.example
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: domain
    name: Twilio Segment
    provider: segment
    says: ships the Twilio Segment SDK or integration code
    source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/segment
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: common
    name: Unsplash
    provider: unsplash
    says: ships the Unsplash SDK or integration code
    source: https://github.com/dubinc/dub/blob/main/apps/web/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Upstash
    provider: upstash
    says: ships the Upstash SDK or integration code
    source: https://github.com/dubinc/dub/blob/main/apps/web/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Vercel Domains API
    provider: vercel
    says: ships the Vercel Domains API SDK or integration code
    source: https://github.com/dubinc/dub/blob/main/apps/web/.env.example
    tier: observed
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
    says: ships the Zapier SDK or integration code
    source: https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/zapier
    tier: observed
  kind: open-source-saas
  name: Dub
  page: /applications/url-shortener-links/dub/
  slug: dub
  url: https://github.com/dubinc/dub
- anchor: shlink
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: dependency manifest
    url: https://github.com/shlinkio/shlink/blob/develop/composer.json
  - route: source code
    url: https://github.com/shlinkio/shlink-importer/tree/main/src/Sources
  - route: source code
    url: https://github.com/shlinkio/shlink/tree/develop/config/autoload
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Bitly
    provider: bitly
    says: ships the Bitly SDK or integration code
    source: https://github.com/shlinkio/shlink-importer/tree/main/src/Sources
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Kutt
    provider: kutt
    says: ships the Kutt SDK or integration code
    source: https://github.com/shlinkio/shlink-importer/tree/main/src/Sources
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Matomo
    provider: matomo
    says: ships the Matomo SDK or integration code
    source: https://github.com/shlinkio/shlink/blob/develop/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: domain
    name: MaxMind GeoLite2
    provider: maxmind
    says: ships the MaxMind GeoLite2 SDK or integration code
    source: https://github.com/shlinkio/shlink/tree/develop/config/autoload/geolite2.global.php
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
    name: RabbitMQ
    provider: rabbitmq
    says: ships the RabbitMQ SDK or integration code
    source: https://github.com/shlinkio/shlink/tree/develop/config/autoload/rabbit.global.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: YOURLS
    provider: yourls
    says: ships the YOURLS SDK or integration code
    source: https://github.com/shlinkio/shlink-importer/tree/main/src/Sources
    tier: observed
  kind: self-hosted
  name: Shlink
  page: /applications/url-shortener-links/shlink/
  slug: shlink
  url: https://github.com/shlinkio/shlink
- anchor: yourls
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: dependency manifest
    url: https://github.com/YOURLS/YOURLS/blob/master/composer.json
  - route: source code
    url: https://github.com/YOURLS/YOURLS/blob/master/includes/functions-geo.php
  - route: source code
    url: https://github.com/YOURLS/YOURLS/blob/master/includes/functions-infos.php
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Charts
    provider: google-charts
    says: ships the Google Charts SDK or integration code
    source: https://github.com/YOURLS/YOURLS/blob/master/includes/functions-infos.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: domain
    name: MaxMind GeoLite2
    provider: maxmind
    says: ships the MaxMind GeoLite2 SDK or integration code
    source: https://github.com/YOURLS/YOURLS/blob/master/includes/functions-geo.php
    tier: observed
  kind: self-hosted
  name: YOURLS
  page: /applications/url-shortener-links/yourls/
  slug: yourls
  url: https://github.com/YOURLS/YOURLS
- anchor: kutt
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: dependency manifest
    url: https://github.com/thedevs-network/kutt/blob/main/package.json
  - route: source code
    url: https://github.com/thedevs-network/kutt/blob/main/.example.env
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: domain
    name: MaxMind GeoLite (via geoip-lite)
    provider: maxmind
    says: ships the MaxMind GeoLite (via geoip-lite) SDK or integration code
    source: https://github.com/thedevs-network/kutt/blob/main/package.json
    tier: observed
  kind: self-hosted
  name: Kutt
  page: /applications/url-shortener-links/kutt/
  slug: kutt
  url: https://github.com/thedevs-network/kutt
- anchor: sink
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: source code
    url: https://github.com/ccbikai/Sink/blob/master/.env.example
  - route: source code
    url: https://github.com/ccbikai/Sink/blob/master/wrangler.jsonc
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Cloudflare Access
    provider: cloudflare
    says: ships the Cloudflare Access SDK or integration code
    source: https://github.com/ccbikai/Sink/blob/master/.env.example
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Cloudflare Analytics Engine
    provider: cloudflare
    says: ships the Cloudflare Analytics Engine SDK or integration code
    source: https://github.com/ccbikai/Sink/blob/master/wrangler.jsonc
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
    name: Cloudflare R2
    provider: cloudflare
    says: ships the Cloudflare R2 SDK or integration code
    source: https://github.com/ccbikai/Sink/blob/master/wrangler.jsonc
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
    name: Cloudflare Workers AI
    provider: cloudflare
    says: ships the Cloudflare Workers AI SDK or integration code
    source: https://github.com/ccbikai/Sink/blob/master/wrangler.jsonc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Cloudflare Workers KV/D1
    provider: cloudflare
    says: ships the Cloudflare Workers KV/D1 SDK or integration code
    source: https://github.com/ccbikai/Sink/blob/master/wrangler.jsonc
    tier: observed
  kind: self-hosted
  name: Sink
  page: /applications/url-shortener-links/sink/
  slug: sink
  url: https://github.com/ccbikai/Sink
- anchor: bitly
  counts:
    declared: 54
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.bitly.app/latest/
  - route: integrations page
    url: https://bitly.com/solutions/integrations/
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
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.bitly.app/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: ActiveCampaign
    provider: activecampaign
    says: lists ActiveCampaign as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Adobe Analytics
    provider: adobe-analytics
    says: lists Adobe Analytics as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Airtable
    provider: airtable
    says: lists Airtable as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: AWeber
    provider: aweber
    says: lists AWeber as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: domain
    name: Braze
    provider: braze
    says: lists Braze as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-914
      key: AE-914
      name: Social Listening & Analytics
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Buffer
    provider: buffer
    says: lists Buffer as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: domain
    name: Canva
    provider: canva
    says: lists Canva as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: ClickUp
    provider: clickup
    says: lists ClickUp as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: Constant Contact
    provider: constant-contact
    says: lists Constant Contact as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Contentful
    provider: contentful
    says: lists Contentful as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Discord
    provider: discord
    says: lists Discord as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: GetResponse
    provider: getresponse
    says: lists GetResponse as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Ghost
    provider: ghost-org
    says: lists Ghost as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Google Analytics 4
    provider: google-analytics
    says: lists Google Analytics 4 as an integration
    source: https://bitly.com/solutions/integrations/
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
    name: Google Docs
    provider: google-docs
    says: lists Google Docs as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: domain
    name: Google Forms
    provider: google-forms
    says: lists Google Forms as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Sheets
    provider: google-sheets
    says: lists Google Sheets as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-914
      key: AE-914
      name: Social Listening & Analytics
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Hootsuite
    provider: hootsuite
    says: lists Hootsuite as an integration
    source: https://bitly.com/solutions/integrations/
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
    source: https://bitly.com/solutions/integrations/
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
    name: IFTTT
    provider: ifttt
    says: lists IFTTT as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: domain
    name: Jotform
    provider: jotform
    says: lists Jotform as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: Kit
    provider: convertkit
    says: lists Kit as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Klaviyo
    provider: klaviyo
    says: lists Klaviyo as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Leadpages
    provider: leadpages
    says: lists Leadpages as an integration
    source: https://bitly.com/solutions/integrations/
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
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: MailerLite
    provider: mailerlite
    says: lists MailerLite as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.50
      key: marketing-operations-management
      name: Marketing Operations Management
      url: /capabilities/marketing-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Marketo
    provider: marketo
    says: lists Marketo as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: monday.com
    provider: monday-com
    says: lists monday.com as an integration
    source: https://bitly.com/solutions/integrations/
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
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.50
      key: marketing-operations-management
      name: Marketing Operations Management
      url: /capabilities/marketing-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Oracle Eloqua
    provider: eloqua
    says: lists Oracle Eloqua as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.50
      key: marketing-operations-management
      name: Marketing Operations Management
      url: /capabilities/marketing-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pardot
    provider: pardot
    says: lists Pardot as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: null
    layer: domain
    name: Qualtrics
    provider: qualtrics
    says: lists Qualtrics as an integration
    source: https://bitly.com/solutions/integrations/
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
    name: Reddit
    provider: reddit
    says: lists Reddit as an integration
    source: https://bitly.com/solutions/integrations/
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
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: SendGrid
    provider: sendgrid
    says: lists SendGrid as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Shopify
    provider: shopify
    says: lists Shopify as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Smartsheet
    provider: smartsheet
    says: lists Smartsheet as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-914
      key: AE-914
      name: Social Listening & Analytics
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Sprout Social
    provider: sprout-social
    says: lists Sprout Social as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
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
    says: lists Stripe as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: domain
    name: SurveyMonkey
    provider: surveymonkey
    says: lists SurveyMonkey as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Twilio
    provider: twilio
    says: lists Twilio as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: domain
    name: Twilio Segment
    provider: segment
    says: lists Twilio Segment as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: Twitch
    provider: twitch
    says: lists Twitch as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: domain
    name: Typeform
    provider: typeform
    says: lists Typeform as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Webflow
    provider: webflow
    says: lists Webflow as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: WordPress
    provider: wordpress
    says: lists WordPress as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: YouTube
    provider: youtube
    says: lists YouTube as an integration
    source: https://bitly.com/solutions/integrations/
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
    source: https://bitly.com/solutions/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: common
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://bitly.com/solutions/integrations/
    tier: declared
  kind: commercial
  name: Bitly
  page: /applications/url-shortener-links/bitly/
  slug: bitly
  url: https://bitly.com/
- anchor: shortio
  counts:
    declared: 8
    observed: 0
  evidence:
  - route: integrations page
    url: https://short.io/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: AdRoll
    provider: adroll
    says: lists AdRoll as an integration
    source: https://short.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Google Analytics
    provider: google-analytics
    says: lists Google Analytics as an integration
    source: https://short.io/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: null
    layer: domain
    name: Google Tag Manager
    provider: google-tag-manager
    says: lists Google Tag Manager as an integration
    source: https://short.io/integrations/
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
    name: Make
    provider: make
    says: lists Make as an integration
    source: https://short.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Meta Pixel
    provider: facebook
    says: lists Meta Pixel as an integration
    source: https://short.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://short.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: domain
    name: Twilio Segment
    provider: segment
    says: lists Twilio Segment as an integration
    source: https://short.io/integrations/
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
    source: https://short.io/integrations/
    tier: declared
  kind: commercial
  name: Short.io
  page: /applications/url-shortener-links/short-io/
  slug: short-io
  url: https://short.io/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: url-shortener-links
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Utilities
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Tools
  store: google-play
  url: https://play.google.com/store/apps/category/TOOLS
- category: URL Shorteners
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#url-shorteners
- category: Bookmarks and Link Sharing
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#bookmarks-and-link-sharing
- category: URL Shortener
  store: zapier
  url: https://zapier.com/apps
name: Link Management & URL Shorteners
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: exact
  layer: domain
  why: 'link importers between shorteners (Bitly, Kutt, YOURLS): the category consumes its own peers'
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: domain
  why: every self-hosted shortener geolocates clicks with MaxMind GeoLite
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: domain
  why: click analytics stores and chart rendering
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: domain
  why: forwarding clicks to web analytics (GA4, Matomo, Adobe)
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: domain
  why: tag firing on redirect
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: ad conversion upload and retargeting pixels
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: domain
  why: MMP partner integrations
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: exact
  layer: domain
  why: sale attribution from storefront orders
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: lead/contact attribution into CRM
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: domain
  why: CDP event routing
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  fit: exact
  layer: domain
  why: links inside lifecycle messaging
- capability:
    attribution: Turbo EA
    id: BC-400.50
    key: marketing-operations-management
    name: Marketing Operations Management
    url: /capabilities/marketing-operations-management/
    via_parent: null
  fit: exact
  layer: domain
  why: marketing automation suites
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: domain
  why: short links in newsletters
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: domain
  why: short links in SMS
- capability:
    attribution: API Evangelist extension
    id: AE-914
    key: AE-914
    name: Social Listening & Analytics
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: exact
  layer: domain
  why: social publishing/scheduling suites (nearest node for publishing)
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: domain
  why: sharing to social networks
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  fit: exact
  layer: domain
  why: links in video descriptions
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  fit: exact
  layer: domain
  why: CMS / site builders
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  fit: exact
  layer: domain
  why: QR/links inside design tools
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  fit: exact
  layer: domain
  why: links in forms
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  fit: exact
  layer: domain
  why: survey distribution links
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.10
    key: AE-230.20.10
    name: Exchange Rates
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  fit: exact
  layer: domain
  why: multi-currency conversion values
- capability:
    attribution: Turbo EA
    id: BC-4220
    key: saas-platform-operations-management
    name: SaaS Platform Operations Management
    url: /capabilities/saas-platform-operations-management/
    via_parent: null
  fit: gap
  layer: domain
  why: 'custom domain registration/DNS and event brokers: no node fits (gap)'
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: subscription billing and payment links
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: Zapier/Make/IFTTT
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: Slack/Teams/Discord
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: common
  why: links from PM tools
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  fit: exact
  layer: common
  why: docs/wikis
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: bulk shortening from sheets
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: common
  why: meeting links
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: serverless DB/KV/cache for the link store
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: asset/backup buckets
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: login + notification email
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: Google/GitHub sign-in
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: zero-trust access in front of the admin
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: exact
  layer: common
  why: link preview images
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: logging
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: support desk
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.10
    key: AE-230.40.10
    name: Web Scraping
    url: /capabilities/web-data/
    via_parent: Web Data
  fit: exact
  layer: common
  why: page fetch for verification
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: AI slugs, previews and assistants
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 84.0
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: declared
      url: /providers/sendgrid/
    - agent_band: agent-ready
      agent_readiness: 51.0
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 81.1
      mcp:
        source: https://developers.activecampaign.com/page/mcp
        status: documented
      name: ActiveCampaign
      slug: activecampaign
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - CRM
      - Email Marketing
      - Marketing Automation
      - Sales Automation
      tier: declared
      url: /providers/activecampaign/
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 80.4
      mcp:
        status: none
      name: Kit
      slug: convertkit
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Automation
      - Creator Economy
      - Email Marketing
      - Subscribers
      tier: declared
      url: /providers/convertkit/
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
    - agent_band: agent-ready
      agent_readiness: 48.9
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        status: none
      name: GetResponse
      slug: getresponse
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Email Marketing
      - Landing Pages
      - Marketing Automation
      - Webinars
      tier: declared
      url: /providers/getresponse/
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 71.7
      mcp:
        source: https://github.com/aweber/aweber-mcp
        status: verified
      name: AWeber
      slug: aweber
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Email
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/aweber/
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp:
        source: https://developers.mailerlite.com/
        status: documented
      name: MailerLite
      slug: mailerlite
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Automation
      - Email Marketing
      - Newsletters
      - Subscribers
      tier: declared
      url: /providers/mailerlite/
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        status: none
      name: Constant Contact
      slug: constant-contact
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Campaigns
      - Contacts
      - Email Marketing
      - Event
      tier: declared
      url: /providers/constant-contact/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 79.0
      mcp:
        status: none
      name: Ghost
      slug: ghost-org
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Membership
      - Newsletters
      - Publishing
      - Subscription
      tier: declared
      url: /providers/ghost-org/
    - agent_band: agent-ready
      agent_readiness: 62.5
      apps:
      - Bitly
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        source: https://developers.webflow.com/mcp/reference/overview
        status: verified
      name: Webflow
      slug: webflow
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - CMS
      - E-Commerce
      - No-Code
      - Web Development
      tier: declared
      url: /providers/webflow/
    - agent_band: agent-ready
      agent_readiness: 49.5
      apps:
      - Bitly
      band: strong
      in_catalog: true
      kin_score: 58.6
      mcp:
        status: unknown
      name: Leadpages
      slug: leadpages
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Company
      - Conversion Optimization
      - Landing Pages
      - Marketing
      tier: declared
      url: /providers/leadpages/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Bitly
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        source: https://github.com/WordPress/mcp-adapter
        status: verified
      name: WordPress
      slug: wordpress
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - CMS
      - Content Management
      - Open Source
      - WordPress
      tier: declared
      url: /providers/wordpress/
    - agent_band: agent-ready
      agent_readiness: 55.2
      apps:
      - Bitly
      band: developing
      in_catalog: true
      kin_score: 43.9
      mcp:
        source: https://github.com/contentful/contentful-mcp-server
        status: verified
      name: Contentful
      slug: contentful
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - CMS
      - Content
      - Content Management
      - Headless CMS
      tier: declared
      url: /providers/contentful/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Dub
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp: &id001
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/stripe
      status: profiled
      tags: &id002
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 42.1
      apps:
      - Dub
      band: exemplar
      in_catalog: true
      kin_score: 73.4
      mcp:
        source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
        status: verified
      name: Google Ads
      slug: google-ads
      sources:
      - https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/google-ads
      status: profiled
      tags:
      - Advertising
      - Campaign Management
      - Digital Advertising
      - Google
      tier: observed
      url: /providers/google-ads/
    - agent_band: agent-native
      agent_readiness: 58.7
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 78.1
      mcp:
        source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
        status: verified
      name: Klaviyo
      slug: klaviyo
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Customer Data
      - Email
      - Marketing
      - SMS
      tier: declared
      url: /providers/klaviyo/
    - agent_band: agent-ready
      agent_readiness: 29.1
      apps:
      - Short.io
      band: developing
      in_catalog: true
      kin_score: 51.1
      mcp:
        status: none
      name: AdRoll
      slug: adroll
      sources:
      - https://short.io/integrations/
      status: profiled
      tags:
      - Advertising
      - Display Advertising
      - Marketing
      - Retargeting
      tier: declared
      url: /providers/adroll/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Short.io
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Meta Pixel
      slug: facebook
      sources:
      - https://short.io/integrations/
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: declared
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 58.2
      apps:
      - Dub
      - Shlink
      band: exemplar
      in_catalog: true
      kin_score: 73.0
      mcp:
        source: https://dev.bitly.com/bitly-mcp/
        status: verified
      name: Bitly
      slug: bitly
      sources:
      - https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/bitly
      - https://github.com/shlinkio/shlink-importer/tree/main/src/Sources
      status: profiled
      tags:
      - Analytics
      - Links
      - QR Codes
      - URL Shorteners
      tier: observed
      url: /providers/bitly/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Shlink
      band: emerging
      in_catalog: true
      kin_score: 20.4
      mcp:
        status: none
      name: YOURLS
      slug: yourls
      sources:
      - https://github.com/shlinkio/shlink-importer/tree/main/src/Sources
      status: profiled
      tags:
      - Company
      - Open Source
      - PHP
      - URL Shorteners
      tier: observed
      url: /providers/yourls/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Shlink
      band: minimal
      in_catalog: true
      kin_score: 3.3
      mcp:
        status: none
      name: Kutt
      slug: kutt
      sources:
      - https://github.com/shlinkio/shlink-importer/tree/main/src/Sources
      status: profiled
      tags:
      - Public APIs
      - URL Shorteners
      tier: observed
      url: /providers/kutt/
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 70.2
      mcp:
        source: https://github.com/jotform/mcp-server
        status: verified
      name: Jotform
      slug: jotform
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Data Collection
      - Forms
      - No-Code
      - Surveys
      tier: declared
      url: /providers/jotform/
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Bitly
      band: developing
      in_catalog: true
      kin_score: 53.1
      mcp:
        status: none
      name: Google Forms
      slug: google-forms
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Data Collection
      - Forms
      - Google
      - Google Workspace
      tier: declared
      url: /providers/google-forms/
    - agent_band: agent-ready
      agent_readiness: 42.6
      apps:
      - Bitly
      band: thin
      in_catalog: true
      kin_score: 36.0
      mcp:
        source: https://www.typeform.com/developers/mcp
        status: verified
      name: Typeform
      slug: typeform
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Forms
      - Lead Capture
      - Software-as-a-Service
      - Surveys
      tier: declared
      url: /providers/typeform/
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Bitly
      band: thin
      in_catalog: true
      kin_score: 34.9
      mcp:
        source: https://www.surveymonkey.com/apps/
        status: documented
      name: SurveyMonkey
      slug: surveymonkey
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Feedback
      - Market Research
      - NPS
      - Surveys
      tier: declared
      url: /providers/surveymonkey/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Bitly
      - Short.io
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics 4
      slug: google-analytics
      sources:
      - https://bitly.com/solutions/integrations/
      - https://short.io/integrations/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: declared
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 41.3
      apps:
      - Shlink
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/matomo-org/plugin-McpServer
        status: verified
      name: Matomo
      slug: matomo
      sources:
      - https://github.com/shlinkio/shlink/blob/develop/composer.json
      status: profiled
      tags:
      - Analytics
      - Open Source
      - Privacy
      - Web Analytics
      tier: observed
      url: /providers/matomo/
    - agent_band: agent-native
      agent_readiness: 60.3
      apps:
      - Bitly
      band: strong
      in_catalog: true
      kin_score: 65.0
      mcp:
        status: none
      name: Adobe Analytics
      slug: adobe-analytics
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Adobe
      - Analytics
      - Business Intelligence
      - Customer Intelligence
      tier: declared
      url: /providers/adobe-analytics/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - Sink
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: &id003
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare Analytics Engine
      slug: cloudflare
      sources:
      - https://github.com/ccbikai/Sink/blob/master/wrangler.jsonc
      status: profiled
      tags: &id004
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: observed
      url: /providers/cloudflare/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Dub
      band: developing
      in_catalog: true
      kin_score: 46.4
      mcp:
        source: https://www.tinybird.co/docs/forward/analytics-agents/mcp
        status: verified
      name: Tinybird
      slug: tinybird
      sources:
      - https://github.com/dubinc/dub/blob/main/apps/web/.env.example
      status: profiled
      tags:
      - Analytics
      - Data
      - Real-Time
      - SQL
      tier: observed
      url: /providers/tinybird/
    - agent_band: null
      agent_readiness: null
      apps:
      - YOURLS
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Google Charts
      slug: google-charts
      sources:
      - https://github.com/YOURLS/YOURLS/blob/master/includes/functions-infos.php
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Bitly
      - Dub
      - Short.io
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Twilio Segment
      slug: segment
      sources:
      - https://bitly.com/solutions/integrations/
      - https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/segment
      - https://short.io/integrations/
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
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Bitly
      - Dub
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://bitly.com/solutions/integrations/
      - https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/hubspot
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: observed
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
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
      - Kutt
      - Shlink
      - YOURLS
      band: thin
      in_catalog: true
      kin_score: 31.5
      mcp:
        status: none
      name: MaxMind GeoLite2
      slug: maxmind
      sources:
      - https://github.com/YOURLS/YOURLS/blob/master/includes/functions-geo.php
      - https://github.com/shlinkio/shlink/tree/develop/config/autoload/geolite2.global.php
      - https://github.com/thedevs-network/kutt/blob/main/package.json
      status: profiled
      tags:
      - Fraud Prevention
      - Geolocation
      - IP Intelligence
      - Risk Scoring
      tier: observed
      url: /providers/maxmind/
  - capability:
      attribution: Turbo EA
      id: BC-400.50
      key: marketing-operations-management
      name: Marketing Operations Management
      url: /capabilities/marketing-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Bitly
      band: strong
      in_catalog: true
      kin_score: 60.7
      mcp:
        status: none
      name: Pardot
      slug: pardot
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - B2B Marketing
      - Email Marketing
      - Lead Generation
      - Marketing Automation
      tier: declared
      url: /providers/pardot/
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - Bitly
      band: strong
      in_catalog: true
      kin_score: 57.2
      mcp:
        status: none
      name: Marketo
      slug: marketo
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Adobe
      - Automation
      - Marketing
      - Marketing Automation
      tier: declared
      url: /providers/marketo/
    - agent_band: agent-ready
      agent_readiness: 34.2
      apps:
      - Bitly
      band: developing
      in_catalog: true
      kin_score: 48.2
      mcp:
        status: none
      name: Oracle Eloqua
      slug: eloqua
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - CRM
      - Email Marketing
      - Lead Management
      - Marketing Automation
      tier: declared
      url: /providers/eloqua/
  - capability:
      attribution: API Evangelist extension
      id: AE-914
      key: AE-914
      name: Social Listening & Analytics
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.8
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 72.8
      mcp:
        status: none
      name: Hootsuite
      slug: hootsuite
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Content Scheduling
      - Marketing
      - Social Media
      - Social Media Management
      tier: declared
      url: /providers/hootsuite/
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - Bitly
      band: strong
      in_catalog: true
      kin_score: 65.9
      mcp:
        status: none
      name: Buffer
      slug: buffer
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Analytics
      - Publishing
      - Scheduling
      - Social Media
      tier: declared
      url: /providers/buffer/
    - agent_band: agent-aware
      agent_readiness: 15.8
      apps:
      - Bitly
      band: strong
      in_catalog: true
      kin_score: 54.8
      mcp:
        status: none
      name: Sprout Social
      slug: sprout-social
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Analytics
      - Publishing
      - Social Media
      - Social Media Management
      tier: declared
      url: /providers/sprout-social/
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.0
      apps:
      - Dub
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp:
        source: https://vercel.com/docs/mcp/vercel-mcp
        status: verified
      name: Vercel Domains API
      slug: vercel
      sources:
      - https://github.com/dubinc/dub/blob/main/apps/web/.env.example
      status: profiled
      tags:
      - AI Gateway
      - Gateways
      - Observability
      - Webhook
      tier: observed
      url: /providers/vercel/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Dub
      band: emerging
      in_catalog: true
      kin_score: 14.0
      mcp:
        source: https://www.dynadot.com/domain/mcp
        status: verified
      name: Dynadot
      slug: dynadot
      sources:
      - https://github.com/dubinc/dub/tree/main/apps/web/lib/dynadot
      status: profiled
      tags:
      - Company
      - DNS Management
      - Domain Registrar
      - Marketplace
      tier: observed
      url: /providers/dynadot/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.8
      apps:
      - Bitly
      - Dub
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify
      slug: shopify
      sources:
      - https://bitly.com/solutions/integrations/
      - https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/shopify
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: observed
      url: /providers/shopify/
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
      - Dub
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/appsflyer
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
      - Dub
      band: strong
      in_catalog: true
      kin_score: 65.9
      mcp:
        status: none
      name: Singular
      slug: singular
      sources:
      - https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/singular
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
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp: *id001
      name: Stripe
      slug: stripe
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Bitly
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: declared
      url: /providers/paypal/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp:
        status: none
      name: LinkedIn
      slug: linkedin
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: declared
      url: /providers/linkedin/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Bitly
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/reddit/devvit-mcp
        status: verified
      name: Reddit
      slug: reddit
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Advertising
      - Community
      - Content
      - Reddit
      tier: declared
      url: /providers/reddit/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - Bitly
      band: strong
      in_catalog: true
      kin_score: 65.4
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: declared
      url: /providers/youtube/
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Bitly
      band: developing
      in_catalog: true
      kin_score: 48.2
      mcp:
        status: none
      name: Twitch
      slug: twitch
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Entertainment
      - Gaming
      - Live Streaming
      - Streaming
      tier: declared
      url: /providers/twitch/
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
      - Bitly
      band: developing
      in_catalog: true
      kin_score: 45.7
      mcp:
        status: none
      name: Qualtrics
      slug: qualtrics
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Customer Experience
      - Employee Experience
      - Experience Management
      - Surveys
      tier: declared
      url: /providers/qualtrics/
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
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
        status: verified
      name: Braze
      slug: braze
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Customer Engagement
      - Marketing Automation
      - Messaging
      - Push Notifications
      tier: declared
      url: /providers/braze/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 70.0
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 87.3
      mcp:
        source: https://www.canva.dev/docs/mcp/
        status: verified
      name: Canva
      slug: canva
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Application
      - Automation
      - Brand Management
      - Collaboration
      tier: declared
      url: /providers/canva/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.10
      key: AE-230.20.10
      name: Exchange Rates
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.8
      apps:
      - Dub
      band: thin
      in_catalog: true
      kin_score: 30.5
      mcp:
        source: https://currencyapi.com/docs/mcp
        status: verified
      name: CurrencyAPI
      slug: currencyapi
      sources:
      - https://github.com/dubinc/dub/tree/main/apps/web/lib/currencyapi
      status: profiled
      tags:
      - Currency
      - Currency Conversion
      - Exchange Rates
      - Foreign Exchange
      tier: observed
      url: /providers/currencyapi/
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
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: declared
      url: /providers/twilio/
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
      - Short.io
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://short.io/integrations/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: declared
      url: /providers/google-tag-manager/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Bitly
      - Dub
      - Short.io
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://bitly.com/solutions/integrations/
      - https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/slack
      - https://short.io/integrations/
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Bitly
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: declared
      url: /providers/microsoft-teams/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Bitly
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: declared
      url: /providers/discord/
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
      - Bitly
      - Dub
      - Short.io
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://bitly.com/solutions/integrations/
      - https://github.com/dubinc/dub/tree/main/apps/web/lib/integrations/zapier
      - https://short.io/integrations/
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: observed
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Short.io
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://short.io/integrations/
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
    - agent_band: agent-ready
      agent_readiness: 42.4
      apps:
      - Bitly
      band: emerging
      in_catalog: true
      kin_score: 24.1
      mcp:
        source: https://github.com/IFTTT/ifttt-plugins
        status: verified
      name: IFTTT
      slug: ifttt
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Automation
      - No-Code
      - Webhook
      - iPaaS
      tier: declared
      url: /providers/ifttt/
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 55.8
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 72.6
      mcp:
        source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
        status: verified
      name: ClickUp
      slug: clickup
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: declared
      url: /providers/clickup/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: declared
      url: /providers/asana/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Bitly
      band: developing
      in_catalog: true
      kin_score: 41.4
      mcp:
        source: https://github.com/smartsheet-platform/smar-mcp
        status: verified
      name: Smartsheet
      slug: smartsheet
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: declared
      url: /providers/smartsheet/
    - agent_band: agent-ready
      agent_readiness: 50.3
      apps:
      - Bitly
      band: thin
      in_catalog: true
      kin_score: 32.2
      mcp:
        source: https://github.com/mondaycom/mcp
        status: verified
      name: monday.com
      slug: monday-com
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Automation
      - CRM
      - GraphQL
      - Work Management
      tier: declared
      url: /providers/monday-com/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - Sink
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: *id003
      name: Cloudflare Workers KV/D1
      slug: cloudflare
      sources:
      - https://github.com/ccbikai/Sink/blob/master/wrangler.jsonc
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/cloudflare/
    - agent_band: agent-ready
      agent_readiness: 46.7
      apps:
      - Dub
      band: thin
      in_catalog: true
      kin_score: 35.2
      mcp:
        source: https://github.com/upstash/mcp-server
        status: verified
      name: Upstash
      slug: upstash
      sources:
      - https://github.com/dubinc/dub/blob/main/apps/web/package.json
      status: profiled
      tags:
      - Kafka
      - Messaging
      - Redis
      - Serverless
      tier: observed
      url: /providers/upstash/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Dub
      band: thin
      in_catalog: true
      kin_score: 28.0
      mcp:
        source: https://github.com/planetscale/mcp-server
        status: verified
      name: PlanetScale
      slug: planetscale
      sources:
      - https://github.com/dubinc/dub/blob/main/apps/web/package.json
      status: profiled
      tags:
      - Database
      - MySQL
      - PostgreSQL
      - Serverless
      tier: observed
      url: /providers/planetscale/
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.3
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 67.2
      mcp:
        source: https://docs.cloud.google.com/mcp/supported-products
        status: verified
      name: Google Docs
      slug: google-docs
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Collaboration
      - Documents
      - Google Workspace
      - Productivity
      tier: declared
      url: /providers/google-docs/
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Bitly
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://developers.notion.com/docs/mcp
        status: verified
      name: Notion
      slug: notion
      sources:
      - https://bitly.com/solutions/integrations/
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
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Dub
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/dubinc/dub/blob/main/apps/web/.env.example
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Dub
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/dubinc/dub/blob/main/apps/web/.env.example
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
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - Bitly
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://github.com/Airtable/airtable-mcp-cli
        status: verified
      name: Airtable
      slug: airtable
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Application
      - Collaboration
      - Data
      - Database
      tier: declared
      url: /providers/airtable/
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Bitly
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: declared
      url: /providers/google-sheets/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.3
      apps:
      - Dub
      band: strong
      in_catalog: true
      kin_score: 61.8
      mcp:
        source: https://github.com/team-plain/cursor-plugin-mcp
        status: verified
      name: Plain
      slug: plain
      sources:
      - https://github.com/dubinc/dub/blob/main/apps/web/package.json
      status: profiled
      tags:
      - Company
      - Customer Service
      - Help Desk
      - Support
      tier: observed
      url: /providers/plain/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Shlink
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        status: none
      name: RabbitMQ
      slug: rabbitmq
      sources:
      - https://github.com/shlinkio/shlink/tree/develop/config/autoload/rabbit.global.php
      status: profiled
      tags:
      - AMQP
      - Distributed Systems
      - Queues
      - RabbitMQ
      tier: observed
      url: /providers/rabbitmq/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.7
      apps:
      - Dub
      band: thin
      in_catalog: true
      kin_score: 37.3
      mcp:
        source: https://github.com/axiomhq/mcp-server-axiom
        status: verified
      name: Axiom
      slug: axiom-co
      sources:
      - https://github.com/dubinc/dub/blob/main/apps/web/package.json
      status: profiled
      tags:
      - Event Data
      - Log Management
      - Logs
      - Observability
      tier: observed
      url: /providers/axiom-co/
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
      - Dub
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp: *id001
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/dubinc/dub/blob/main/apps/web/package.json
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/stripe/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.6
      apps:
      - Dub
      band: developing
      in_catalog: true
      kin_score: 39.4
      mcp:
        status: none
      name: Unsplash
      slug: unsplash
      sources:
      - https://github.com/dubinc/dub/blob/main/apps/web/package.json
      status: profiled
      tags:
      - Image
      - Photography
      - Photos
      - Stock Photos
      tier: observed
      url: /providers/unsplash/
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
      - Bitly
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.bitly.app/latest/
      status: profiled
      tags:
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - Sink
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: *id003
      name: Cloudflare R2
      slug: cloudflare
      sources:
      - https://github.com/ccbikai/Sink/blob/master/wrangler.jsonc
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/cloudflare/
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - Sink
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: *id003
      name: Cloudflare Access
      slug: cloudflare
      sources:
      - https://github.com/ccbikai/Sink/blob/master/.env.example
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/cloudflare/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 49.8
      apps:
      - Dub
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        source: https://resend.com/docs/mcp-server
        status: verified
      name: Resend
      slug: resend
      sources:
      - https://github.com/dubinc/dub/blob/main/apps/web/.env.example
      status: profiled
      tags:
      - Developer Tools
      - Email
      - Marketing Email
      - Transactional Email
      tier: observed
      url: /providers/resend/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Bitly
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://bitly.com/solutions/integrations/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: declared
      url: /providers/zoom/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.10
      key: AE-230.40.10
      name: Web Scraping
      url: /capabilities/web-data/
      via_parent: Web Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - Dub
      band: developing
      in_catalog: true
      kin_score: 50.6
      mcp:
        source: https://docs.firecrawl.dev/mcp-server
        status: verified
      name: Firecrawl
      slug: firecrawl
      sources:
      - https://github.com/dubinc/dub/blob/main/apps/web/package.json
      status: profiled
      tags:
      - Crawling
      - Data Extraction
      - URLs
      - Web Scraping
      tier: observed
      url: /providers/firecrawl/
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
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Dub
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/dubinc/dub/blob/main/apps/web/package.json
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - Sink
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: *id003
      name: Cloudflare Workers AI
      slug: cloudflare
      sources:
      - https://github.com/ccbikai/Sink/blob/master/wrangler.jsonc
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/cloudflare/
  layer: agent
summary:
  coverage_pct: 98.8
  declared_only: 52
  distinct_providers: 84
  in_catalog: 83
  mcp:
    documented: 3
    none: 32
    unchecked: 1
    verified: 47
  mcp_verified: 47
  mean_kin_score: 60.0
  observed: 32
  queued: 1
  reference_apps: 7
title: 'Link Management & URL Shorteners: application blueprint'
---
