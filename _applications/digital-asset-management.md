---
access: understanding
agent_layer:
- app: Canto
  finding: Canto MCP server listed in site navigation
  source: https://www.canto.com/integrations/
  tier: declared
- app: Frontify
  finding: Frontify MCP listed in platform navigation
  source: https://www.frontify.com/en/integrations
  tier: declared
- app: Cloudinary
  finding: Cloudinary MCP Server listed under developers; Claude, Cursor, Gemini and OpenAI listed as integrations (AI Agents category)
  source: https://cloudinary.com/integrations
  tier: declared
- app: Bynder
  finding: AI Agents product and an AI integrations category
  source: https://www.bynder.com/en/integrations/
  tier: declared
apps:
- anchor: resourcespace
  counts:
    declared: 15
    observed: 0
  evidence:
  - route: documentation
    url: https://www.resourcespace.com/knowledge-base/plugins
  - route: documentation
    url: https://www.resourcespace.com/knowledge-base/plugins/image_banks
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: domain
    name: Adobe
    provider: adobe
    says: lists Adobe as an integration
    source: https://www.resourcespace.com/knowledge-base/plugins
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-947
      key: AE-947
      name: Museum Collections Management
      url: /capabilities/museum-collections-management/
      via_parent: null
    credit: null
    layer: domain
    name: Axiell (KE EMu)
    provider: axiell
    says: lists Axiell (KE EMu) as an integration
    source: https://www.resourcespace.com/knowledge-base/plugins
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
    name: Brandwatch
    provider: brandwatch
    says: lists Brandwatch as an integration
    source: https://www.resourcespace.com/knowledge-base/plugins
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
    source: https://www.resourcespace.com/knowledge-base/plugins
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-947
      key: AE-947
      name: Museum Collections Management
      url: /capabilities/museum-collections-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gallery Systems (TMS)
    provider: gallery-systems
    says: lists Gallery Systems (TMS) as an integration
    source: https://www.resourcespace.com/knowledge-base/plugins
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
    source: https://www.resourcespace.com/knowledge-base/plugins
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.50.10
      key: AE-110.50.10
      name: Image Recognition
      url: /capabilities/vision/
      via_parent: Vision
    credit: null
    layer: domain
    name: Google Cloud Vision
    provider: google-cloud-vision
    says: lists Google Cloud Vision as an integration
    source: https://www.resourcespace.com/knowledge-base/plugins
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: OpenAI
    provider: openai
    says: lists OpenAI as an integration
    source: https://www.resourcespace.com/knowledge-base/plugins
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Pixabay
    provider: pixabay
    says: lists Pixabay as an integration
    source: https://www.resourcespace.com/knowledge-base/plugins/image_banks
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Shutterstock
    provider: shutterstock
    says: lists Shutterstock as an integration
    source: https://www.resourcespace.com/knowledge-base/plugins/image_banks
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Typesense
    provider: typesense
    says: lists Typesense as an integration
    source: https://www.resourcespace.com/knowledge-base/plugins
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
    name: Vimeo
    provider: vimeo
    says: lists Vimeo as an integration
    source: https://www.resourcespace.com/knowledge-base/plugins
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
    source: https://www.resourcespace.com/knowledge-base/plugins
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
    source: https://www.resourcespace.com/knowledge-base/plugins
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-947
      key: AE-947
      name: Museum Collections Management
      url: /capabilities/museum-collections-management/
      via_parent: null
    credit: null
    layer: domain
    name: zetcom (MuseumPlus)
    provider: zetcom
    says: lists zetcom (MuseumPlus) as an integration
    source: https://www.resourcespace.com/knowledge-base/plugins
    tier: declared
  kind: self-hosted
  name: ResourceSpace
  page: /applications/digital-asset-management/resourcespace/
  slug: resourcespace
  url: https://www.resourcespace.com/
- anchor: phraseanet
  counts:
    declared: 0
    observed: 10
  evidence:
  - route: dependency manifest
    url: https://github.com/alchemy-fr/Phraseanet/blob/master/composer.json
  - route: source code
    url: https://github.com/alchemy-fr/Phraseanet/tree/master/lib/Alchemy/Phrasea/Authentication/Provider
  - route: source code
    url: https://github.com/alchemy-fr/Phraseanet/tree/master/lib/classes/Bridge/Api
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: Dailymotion
    provider: dailymotion
    says: ships the Dailymotion SDK or integration code
    source: https://github.com/alchemy-fr/Phraseanet/tree/master/lib/classes/Bridge/Api
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Elasticsearch
    provider: elasticsearch
    says: ships the Elasticsearch SDK or integration code
    source: https://github.com/alchemy-fr/Phraseanet/blob/master/composer.json
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/alchemy-fr/Phraseanet/tree/master/lib/Alchemy/Phrasea/Authentication/Provider
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: domain
    name: Flickr
    provider: flickr
    says: ships the Flickr SDK or integration code
    source: https://github.com/alchemy-fr/Phraseanet/tree/master/lib/classes/Bridge/Api
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: domain
    name: GeoNames
    provider: geonames
    says: ships the GeoNames SDK or integration code
    source: https://github.com/alchemy-fr/Phraseanet/blob/master/composer.json
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
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/alchemy-fr/Phraseanet/tree/master/lib/Alchemy/Phrasea/Authentication/Provider
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: domain
    name: Google reCAPTCHA
    provider: google-recaptcha
    says: ships the Google reCAPTCHA SDK or integration code
    source: https://github.com/alchemy-fr/Phraseanet/blob/master/composer.json
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
    name: LinkedIn
    provider: linkedin
    says: ships the LinkedIn SDK or integration code
    source: https://github.com/alchemy-fr/Phraseanet/tree/master/lib/Alchemy/Phrasea/Authentication/Provider
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    credit: null
    layer: domain
    name: Pusher
    provider: pusher
    says: ships the Pusher SDK or integration code
    source: https://github.com/alchemy-fr/Phraseanet/blob/master/composer.json
    tier: observed
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
    says: ships the YouTube SDK or integration code
    source: https://github.com/alchemy-fr/Phraseanet/tree/master/lib/classes/Bridge/Api
    tier: observed
  kind: self-hosted
  name: Phraseanet
  page: /applications/digital-asset-management/phraseanet/
  slug: phraseanet
  url: https://github.com/alchemy-fr/Phraseanet
- anchor: bynder
  counts:
    declared: 71
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.bynder.com/en/integrations/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: domain
    name: Adobe
    provider: adobe
    says: lists Adobe as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Adobe Commerce
    provider: adobe-commerce
    says: lists Adobe Commerce as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Adobe Creative Cloud
    provider: adobe-creative-cloud
    says: lists Adobe Creative Cloud as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Adobe Experience Manager
    provider: adobe-experience-manager
    says: lists Adobe Experience Manager as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Adobe Workfront
    provider: workfront
    says: lists Adobe Workfront as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3740.30
      key: content-delivery-network-operations
      name: Content Delivery Network Operations
      url: /capabilities/content-delivery-network-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Akamai
    provider: akamai
    says: lists Akamai as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2370
      key: product-information-management
      name: Product Information Management
      url: /capabilities/product-information-management/
      via_parent: null
    credit: null
    layer: domain
    name: Akeneo
    provider: akeneo
    says: lists Akeneo as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3740.30
      key: content-delivery-network-operations
      name: Content Delivery Network Operations
      url: /capabilities/content-delivery-network-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon CloudFront
    provider: cloudfront
    says: lists Amazon CloudFront as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Azure Active Directory / Microsoft Entra ID
    provider: microsoft-entra
    says: lists Azure Active Directory / Microsoft Entra ID as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.50.30
      key: BC-410.50.30
      name: Sales Enablement
      url: /capabilities/sales-operations-management/
      via_parent: Sales Operations Management
    credit: null
    layer: domain
    name: Bigtincan
    provider: bigtincan
    says: lists Bigtincan as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Bloomreach
    provider: bloomreach
    says: lists Bloomreach as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Box
    provider: box
    says: lists Box as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Brandwatch
    provider: brandwatch
    says: lists Brandwatch as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: domain
    name: Brightcove
    provider: brightcove
    says: lists Brightcove as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Builder.io
    provider: builder-io
    says: lists Builder.io as an integration
    source: https://www.bynder.com/en/integrations/
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
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: CI HUB
    provider: ci-hub
    says: lists CI HUB as an integration
    source: https://www.bynder.com/en/integrations/
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
    source: https://www.bynder.com/en/integrations/
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
    name: Contentstack
    provider: contentstack
    says: lists Contentstack as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Crownpeak
    provider: crownpeak
    says: lists Crownpeak as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Dotdigital
    provider: dotdigital
    says: lists Dotdigital as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Dropbox
    provider: dropbox
    says: lists Dropbox as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Drupal
    provider: drupal
    says: lists Drupal as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Figma
    provider: figma
    says: lists Figma as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Frame.io
    provider: frameio
    says: lists Frame.io as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Getty Images
    provider: getty-images
    says: lists Getty Images as an integration
    source: https://www.bynder.com/en/integrations/
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
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Drive
    provider: google-drive
    says: lists Google Drive as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Google Identity Platform
    provider: google-identity-platform
    says: lists Google Identity Platform as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Workspace
    provider: google-workspace
    says: lists Google Workspace as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.50.30
      key: BC-410.50.30
      name: Sales Enablement
      url: /capabilities/sales-operations-management/
      via_parent: Sales Operations Management
    credit: null
    layer: domain
    name: Highspot
    provider: highspot
    says: lists Highspot as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Hootsuite
    provider: hootsuite
    says: lists Hootsuite as an integration
    source: https://www.bynder.com/en/integrations/
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
    source: https://www.bynder.com/en/integrations/
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
    name: Hygraph
    provider: hygraph
    says: lists Hygraph as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2370
      key: product-information-management
      name: Product Information Management
      url: /capabilities/product-information-management/
      via_parent: null
    credit: null
    layer: domain
    name: inriver
    provider: inriver
    says: lists inriver as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: iStock
    provider: istock
    says: lists iStock as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Kentico
    provider: kentico
    says: lists Kentico as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Kontent AI
    provider: kontent-ai
    says: lists Kontent AI as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Magnolia
    provider: magnolia
    says: lists Magnolia as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Marketo
    provider: marketo
    says: lists Marketo as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft 365
    provider: microsoft-365
    says: lists Microsoft 365 as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft OneDrive
    provider: microsoft-onedrive
    says: lists Microsoft OneDrive as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-917
      key: AE-917
      name: Enterprise Content & Document Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Microsoft SharePoint
    provider: sharepoint
    says: lists Microsoft SharePoint as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: monday.com
    provider: monday-com
    says: lists monday.com as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Optimizely
    provider: optimizely
    says: lists Optimizely as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Salesforce Commerce Cloud
    provider: salesforce-commerce-cloud
    says: lists Salesforce Commerce Cloud as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Salesforce Marketing Cloud
    provider: salesforce-marketing-cloud
    says: lists Salesforce Marketing Cloud as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2370
      key: product-information-management
      name: Product Information Management
      url: /capabilities/product-information-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salsify
    provider: salsify
    says: lists Salsify as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Sanity
    provider: sanity
    says: lists Sanity as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: SAP Commerce Cloud
    provider: sap-commerce-cloud
    says: lists SAP Commerce Cloud as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.50.30
      key: BC-410.50.30
      name: Sales Enablement
      url: /capabilities/sales-operations-management/
      via_parent: Sales Operations Management
    credit: null
    layer: domain
    name: Seismic
    provider: seismic
    says: lists Seismic as an integration
    source: https://www.bynder.com/en/integrations/
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
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.50.30
      key: BC-410.50.30
      name: Sales Enablement
      url: /capabilities/sales-operations-management/
      via_parent: Sales Operations Management
    credit: null
    layer: domain
    name: Showpad
    provider: showpad
    says: lists Showpad as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Shutterstock
    provider: shutterstock
    says: lists Shutterstock as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Sitecore
    provider: sitecore
    says: lists Sitecore as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Sitefinity CMS
    provider: sitefinity-cms
    says: lists Sitefinity CMS as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Sprinklr
    provider: sprinklr
    says: lists Sprinklr as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Sprout Social
    provider: sprout-social
    says: lists Sprout Social as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2370
      key: product-information-management
      name: Product Information Management
      url: /capabilities/product-information-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stibo Systems
    provider: stibo-systems
    says: lists Stibo Systems as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Storyblok
    provider: storyblok
    says: lists Storyblok as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-917
      key: AE-917
      name: Enterprise Content & Document Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Templafy
    provider: templafy
    says: lists Templafy as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: Tray.io
    provider: tray-ai
    says: lists Tray.io as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Trello
    provider: trello
    says: lists Trello as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Unsplash
    provider: unsplash
    says: lists Unsplash as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Vecteezy
    provider: vecteezy
    says: lists Vecteezy as an integration
    source: https://www.bynder.com/en/integrations/
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
    name: Vimeo
    provider: vimeo
    says: lists Vimeo as an integration
    source: https://www.bynder.com/en/integrations/
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
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: Workato
    provider: workato
    says: lists Workato as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Wrike
    provider: wrike
    says: lists Wrike as an integration
    source: https://www.bynder.com/en/integrations/
    tier: declared
  kind: commercial
  name: Bynder
  page: /applications/digital-asset-management/bynder/
  slug: bynder
  url: https://www.bynder.com/
- anchor: canto
  counts:
    declared: 33
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.canto.com/integrations/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: domain
    name: Adobe Photoshop
    provider: adobe-photoshop
    says: lists Adobe Photoshop as an integration
    source: https://www.canto.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Adobe Workfront
    provider: workfront
    says: lists Adobe Workfront as an integration
    source: https://www.canto.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2370
      key: product-information-management
      name: Product Information Management
      url: /capabilities/product-information-management/
      via_parent: null
    credit: null
    layer: domain
    name: Akeneo
    provider: akeneo
    says: lists Akeneo as an integration
    source: https://www.canto.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://www.canto.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Box
    provider: box
    says: lists Box as an integration
    source: https://www.canto.com/integrations/
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
    source: https://www.canto.com/integrations/
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
    name: Contentstack
    provider: contentstack
    says: lists Contentstack as an integration
    source: https://www.canto.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Dropbox
    provider: dropbox
    says: lists Dropbox as an integration
    source: https://www.canto.com/integrations/
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
    name: Drupal
    provider: drupal
    says: lists Drupal as an integration
    source: https://www.canto.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Egnyte
    provider: egnyte
    says: lists Egnyte as an integration
    source: https://www.canto.com/integrations/
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
    name: Facebook
    provider: facebook
    says: lists Facebook as an integration
    source: https://www.canto.com/integrations/
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
    name: Figma
    provider: figma
    says: lists Figma as an integration
    source: https://www.canto.com/integrations/
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
    source: https://www.canto.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Drive
    provider: google-drive
    says: lists Google Drive as an integration
    source: https://www.canto.com/integrations/
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
    name: Hootsuite
    provider: hootsuite
    says: lists Hootsuite as an integration
    source: https://www.canto.com/integrations/
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
    source: https://www.canto.com/integrations/
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
    source: https://www.canto.com/integrations/
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
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://www.canto.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft OneDrive
    provider: microsoft-onedrive
    says: lists Microsoft OneDrive as an integration
    source: https://www.canto.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-917
      key: AE-917
      name: Enterprise Content & Document Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Microsoft SharePoint
    provider: sharepoint
    says: lists Microsoft SharePoint as an integration
    source: https://www.canto.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://www.canto.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: monday.com
    provider: monday-com
    says: lists monday.com as an integration
    source: https://www.canto.com/integrations/
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
    name: Pinterest
    provider: pinterest
    says: lists Pinterest as an integration
    source: https://www.canto.com/integrations/
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
    name: Salesforce Marketing Cloud
    provider: salesforce-marketing-cloud
    says: lists Salesforce Marketing Cloud as an integration
    source: https://www.canto.com/integrations/
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
    source: https://www.canto.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://www.canto.com/integrations/
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
    name: TYPO3
    provider: typo3
    says: lists TYPO3 as an integration
    source: https://www.canto.com/integrations/
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
    name: Vimeo
    provider: vimeo
    says: lists Vimeo as an integration
    source: https://www.canto.com/integrations/
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
    source: https://www.canto.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Wrike
    provider: wrike
    says: lists Wrike as an integration
    source: https://www.canto.com/integrations/
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
    name: X (Twitter)
    provider: x
    says: lists X (Twitter) as an integration
    source: https://www.canto.com/integrations/
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
    source: https://www.canto.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://www.canto.com/integrations/
    tier: declared
  kind: commercial
  name: Canto
  page: /applications/digital-asset-management/canto/
  slug: canto
  url: https://www.canto.com/
- anchor: frontify
  counts:
    declared: 55
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.frontify.com/en/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: domain
    name: Adobe
    provider: adobe
    says: lists Adobe as an integration
    source: https://www.frontify.com/en/integrations
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
    name: Adobe Creative Cloud
    provider: adobe-creative-cloud
    says: lists Adobe Creative Cloud as an integration
    source: https://www.frontify.com/en/integrations
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
    name: Adobe Experience Manager
    provider: adobe-experience-manager
    says: lists Adobe Experience Manager as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Adobe Workfront
    provider: workfront
    says: lists Adobe Workfront as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2370
      key: product-information-management
      name: Product Information Management
      url: /capabilities/product-information-management/
      via_parent: null
    credit: null
    layer: domain
    name: Akeneo
    provider: akeneo
    says: lists Akeneo as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Azure Active Directory / Microsoft Entra ID
    provider: microsoft-entra
    says: lists Azure Active Directory / Microsoft Entra ID as an integration
    source: https://www.frontify.com/en/integrations
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
    name: Bloomreach
    provider: bloomreach
    says: lists Bloomreach as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bynder
    provider: bynder
    says: lists Bynder as an integration
    source: https://www.frontify.com/en/integrations
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
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: domain
    name: CELUM
    provider: celum
    says: lists CELUM as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: CI HUB
    provider: ci-hub
    says: lists CI HUB as an integration
    source: https://www.frontify.com/en/integrations
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
    source: https://www.frontify.com/en/integrations
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
    name: Contentstack
    provider: contentstack
    says: lists Contentstack as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Dropbox
    provider: dropbox
    says: lists Dropbox as an integration
    source: https://www.frontify.com/en/integrations
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
    name: Drupal
    provider: drupal
    says: lists Drupal as an integration
    source: https://www.frontify.com/en/integrations
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
    name: Figma
    provider: figma
    says: lists Figma as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Getty Images
    provider: getty-images
    says: lists Getty Images as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Workspace
    provider: google-workspace
    says: lists Google Workspace as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.50.30
      key: BC-410.50.30
      name: Sales Enablement
      url: /capabilities/sales-operations-management/
      via_parent: Sales Operations Management
    credit: null
    layer: domain
    name: Highspot
    provider: highspot
    says: lists Highspot as an integration
    source: https://www.frontify.com/en/integrations
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
    name: Hootsuite
    provider: hootsuite
    says: lists Hootsuite as an integration
    source: https://www.frontify.com/en/integrations
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
    source: https://www.frontify.com/en/integrations
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
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Intercom
    provider: intercom
    says: lists Intercom as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60.10
      key: AE-150.60.10
      name: Async Video Messaging
      url: /capabilities/video-calling/
      via_parent: Video Calling
    credit: null
    layer: domain
    name: Loom
    provider: loom
    says: lists Loom as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft 365
    provider: microsoft-365
    says: lists Microsoft 365 as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-917
      key: AE-917
      name: Enterprise Content & Document Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Microsoft SharePoint
    provider: sharepoint
    says: lists Microsoft SharePoint as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: monday.com
    provider: monday-com
    says: lists monday.com as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80.10
      key: AE-170.80.10
      name: Web Fonts & Typography
      url: /capabilities/design-creative-editing/
      via_parent: Design & Creative Editing
    credit: null
    layer: domain
    name: Monotype
    provider: monotype
    says: lists Monotype as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Okta
    provider: okta
    says: lists Okta as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: OneLogin
    provider: onelogin
    says: lists OneLogin as an integration
    source: https://www.frontify.com/en/integrations
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
    name: Optimizely
    provider: optimizely
    says: lists Optimizely as an integration
    source: https://www.frontify.com/en/integrations
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
    name: Salesforce Marketing Cloud
    provider: salesforce-marketing-cloud
    says: lists Salesforce Marketing Cloud as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2370
      key: product-information-management
      name: Product Information Management
      url: /capabilities/product-information-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salsify
    provider: salsify
    says: lists Salsify as an integration
    source: https://www.frontify.com/en/integrations
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
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410.50.30
      key: BC-410.50.30
      name: Sales Enablement
      url: /capabilities/sales-operations-management/
      via_parent: Sales Operations Management
    credit: null
    layer: domain
    name: Showpad
    provider: showpad
    says: lists Showpad as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Shutterstock
    provider: shutterstock
    says: lists Shutterstock as an integration
    source: https://www.frontify.com/en/integrations
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
    name: Sitecore
    provider: sitecore
    says: lists Sitecore as an integration
    source: https://www.frontify.com/en/integrations
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
    name: Sitefinity CMS
    provider: sitefinity-cms
    says: lists Sitefinity CMS as an integration
    source: https://www.frontify.com/en/integrations
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
    name: Sketch
    provider: sketch
    says: lists Sketch as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://www.frontify.com/en/integrations
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
    name: Sprinklr
    provider: sprinklr
    says: lists Sprinklr as an integration
    source: https://www.frontify.com/en/integrations
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
    name: Storyblok
    provider: storyblok
    says: lists Storyblok as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-917
      key: AE-917
      name: Enterprise Content & Document Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Templafy
    provider: templafy
    says: lists Templafy as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: Tray.io
    provider: tray-ai
    says: lists Tray.io as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Trello
    provider: trello
    says: lists Trello as an integration
    source: https://www.frontify.com/en/integrations
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
    source: https://www.frontify.com/en/integrations
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
    name: TYPO3
    provider: typo3
    says: lists TYPO3 as an integration
    source: https://www.frontify.com/en/integrations
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
    name: Vimeo
    provider: vimeo
    says: lists Vimeo as an integration
    source: https://www.frontify.com/en/integrations
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
    source: https://www.frontify.com/en/integrations
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
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Wrike
    provider: wrike
    says: lists Wrike as an integration
    source: https://www.frontify.com/en/integrations
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
    source: https://www.frontify.com/en/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://www.frontify.com/en/integrations
    tier: declared
  kind: commercial
  name: Frontify
  page: /applications/digital-asset-management/frontify/
  slug: frontify
  url: https://www.frontify.com/
- anchor: cloudinary
  counts:
    declared: 56
    observed: 0
  evidence:
  - route: integrations page
    url: https://cloudinary.com/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: domain
    name: Adobe
    provider: adobe
    says: lists Adobe as an integration
    source: https://cloudinary.com/integrations
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
    name: Adobe Commerce
    provider: adobe-commerce
    says: lists Adobe Commerce as an integration
    source: https://cloudinary.com/integrations
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
    name: Adobe Creative Cloud
    provider: adobe-creative-cloud
    says: lists Adobe Creative Cloud as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Adobe Workfront
    provider: workfront
    says: lists Adobe Workfront as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2370
      key: product-information-management
      name: Product Information Management
      url: /capabilities/product-information-management/
      via_parent: null
    credit: null
    layer: domain
    name: Akeneo
    provider: akeneo
    says: lists Akeneo as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Amazon Web Services
    provider: amazon-web-services
    says: lists Amazon Web Services as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Anthropic
    provider: anthropic
    says: lists Anthropic as an integration
    source: https://cloudinary.com/integrations
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
    name: Braze
    provider: braze
    says: lists Braze as an integration
    source: https://cloudinary.com/integrations
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
    name: Builder.io
    provider: builder-io
    says: lists Builder.io as an integration
    source: https://cloudinary.com/integrations
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
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: CI HUB
    provider: ci-hub
    says: lists CI HUB as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.20
      key: AE-140.10.20
      name: Headless & Composable Commerce
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: commercetools
    provider: commercetools
    says: lists commercetools as an integration
    source: https://cloudinary.com/integrations
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
    source: https://cloudinary.com/integrations
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
    name: Contentsquare
    provider: contentsquare
    says: lists Contentsquare as an integration
    source: https://cloudinary.com/integrations
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
    name: Contentstack
    provider: contentstack
    says: lists Contentstack as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Dropbox
    provider: dropbox
    says: lists Dropbox as an integration
    source: https://cloudinary.com/integrations
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
    name: Drupal
    provider: drupal
    says: lists Drupal as an integration
    source: https://cloudinary.com/integrations
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
    name: Figma
    provider: figma
    says: lists Figma as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Getty Images
    provider: getty-images
    says: lists Getty Images as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3740.30
      key: content-delivery-network-operations
      name: Content Delivery Network Operations
      url: /capabilities/content-delivery-network-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Google Cloud CDN
    provider: google-cloud-cdn
    says: lists Google Cloud CDN as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: lists Google Cloud Storage as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: Google Cloud Translation API
    provider: google-translate
    says: lists Google Cloud Translation API as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Google Gemini
    provider: google-gemini
    says: lists Google Gemini as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Workspace
    provider: google-workspace
    says: lists Google Workspace as an integration
    source: https://cloudinary.com/integrations
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
    name: Hootsuite
    provider: hootsuite
    says: lists Hootsuite as an integration
    source: https://cloudinary.com/integrations
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
    source: https://cloudinary.com/integrations
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
    name: Hygraph
    provider: hygraph
    says: lists Hygraph as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: iStock
    provider: istock
    says: lists iStock as an integration
    source: https://cloudinary.com/integrations
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
    source: https://cloudinary.com/integrations
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
    name: Kontent AI
    provider: kontent-ai
    says: lists Kontent AI as an integration
    source: https://cloudinary.com/integrations
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
    name: Magnolia
    provider: magnolia
    says: lists Magnolia as an integration
    source: https://cloudinary.com/integrations
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
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: Make
    provider: make
    says: lists Make as an integration
    source: https://cloudinary.com/integrations
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
    name: Marketo
    provider: marketo
    says: lists Marketo as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft 365
    provider: microsoft-365
    says: lists Microsoft 365 as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: monday.com
    provider: monday-com
    says: lists monday.com as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: n8n
    provider: n8n
    says: lists n8n as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Netlify
    provider: netlify
    says: lists Netlify as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: OpenAI
    provider: openai
    says: lists OpenAI as an integration
    source: https://cloudinary.com/integrations
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
    name: Salesforce Commerce Cloud
    provider: salesforce-commerce-cloud
    says: lists Salesforce Commerce Cloud as an integration
    source: https://cloudinary.com/integrations
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
    name: Salesforce Marketing Cloud
    provider: salesforce-marketing-cloud
    says: lists Salesforce Marketing Cloud as an integration
    source: https://cloudinary.com/integrations
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
    name: Sanity
    provider: sanity
    says: lists Sanity as an integration
    source: https://cloudinary.com/integrations
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
    name: SAP Commerce Cloud
    provider: sap-commerce-cloud
    says: lists SAP Commerce Cloud as an integration
    source: https://cloudinary.com/integrations
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
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Shutterstock
    provider: shutterstock
    says: lists Shutterstock as an integration
    source: https://cloudinary.com/integrations
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
    name: Sitefinity CMS
    provider: sitefinity-cms
    says: lists Sitefinity CMS as an integration
    source: https://cloudinary.com/integrations
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
    name: Sketch
    provider: sketch
    says: lists Sketch as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2370
      key: product-information-management
      name: Product Information Management
      url: /capabilities/product-information-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stibo Systems
    provider: stibo-systems
    says: lists Stibo Systems as an integration
    source: https://cloudinary.com/integrations
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
    name: Storyblok
    provider: storyblok
    says: lists Storyblok as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2370
      key: product-information-management
      name: Product Information Management
      url: /capabilities/product-information-management/
      via_parent: null
    credit: null
    layer: domain
    name: Syndigo
    provider: syndigo
    says: lists Syndigo as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Unsplash
    provider: unsplash
    says: lists Unsplash as an integration
    source: https://cloudinary.com/integrations
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
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Wrike
    provider: wrike
    says: lists Wrike as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://cloudinary.com/integrations
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
    name: Ziflow
    provider: ziflow
    says: lists Ziflow as an integration
    source: https://cloudinary.com/integrations
    tier: declared
  kind: commercial
  name: Cloudinary
  page: /applications/digital-asset-management/cloudinary/
  slug: cloudinary
  url: https://cloudinary.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: digital-asset-management
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: File Transfer - Web-based File Managers
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#file-transfer---web-based-file-managers
- category: Media Management
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#media-management
- category: Visual Content Management
  store: bynder-marketplace
  url: https://www.bynder.com/en/integrations/
- category: Digital asset management
  store: frontify-integrations
  url: https://www.frontify.com/en/integrations
name: Digital Asset Management
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  fit: exact
  layer: domain
  why: named by 5 of 6 reference apps (canva, adobe, figma, adobe-creative-cloud...)
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by 5 of 6 reference apps (wordpress, contentstack, drupal, contentful...)
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  fit: exact
  layer: domain
  why: named by 5 of 6 reference apps (vimeo, youtube, dailymotion)
- capability:
    attribution: API Evangelist extension
    id: AE-914
    key: AE-914
    name: Social Listening & Analytics
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: nearest
  layer: domain
  why: named by 5 of 6 reference apps (hootsuite, brandwatch, sprinklr, sprout-social)
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: domain
  why: named by 4 of 6 reference apps (google-analytics, contentsquare)
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.40
    key: AE-170.30.40
    name: Stock Media & Royalty-Free Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: domain
  why: named by 4 of 6 reference apps (shutterstock, getty-images, istock, unsplash...)
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by 4 of 6 reference apps (salesforce-marketing-cloud, mailchimp, marketo, braze...)
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: exact
  layer: domain
  why: named by 4 of 6 reference apps (shopify, adobe-commerce, salesforce-commerce-cloud, sap-commerce-cloud)
- capability:
    attribution: Turbo EA
    id: BC-2370
    key: product-information-management
    name: Product Information Management
    url: /capabilities/product-information-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by 4 of 6 reference apps (akeneo, salsify, stibo-systems, inriver...)
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by 4 of 6 reference apps (monday-com, workfront, wrike, asana...)
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: named by 4 of 6 reference apps (dropbox, box, google-drive, microsoft-onedrive...)
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by 4 of 6 reference apps (slack, microsoft-teams)
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by 4 of 6 reference apps (hubspot)
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: domain
  why: named by 4 of 6 reference apps (ci-hub, zapier, tray-ai, make...)
- capability:
    attribution: Turbo EA
    id: BC-600.50.50
    key: BC-600.50.50
    name: End-User Computing Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: named by 3 of 6 reference apps (google-workspace, microsoft-365)
- capability:
    attribution: API Evangelist extension
    id: AE-917
    key: AE-917
    name: Enterprise Content & Document Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: nearest
  layer: domain
  why: named by 3 of 6 reference apps (sharepoint, templafy)
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: domain
  why: named by 2 of 6 reference apps (openai, anthropic, google-gemini)
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  fit: exact
  layer: domain
  why: named by 2 of 6 reference apps (elasticsearch, typesense)
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  fit: gap
  layer: domain
  why: named by 2 of 6 reference apps (axiell, bynder, celum, gallery-systems...)
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: domain
  why: named by 2 of 6 reference apps (facebook, github, google-identity-platform, linkedin)
- capability:
    attribution: Turbo EA
    id: BC-410.50.30
    key: BC-410.50.30
    name: Sales Enablement
    url: /capabilities/sales-operations-management/
    via_parent: Sales Operations Management
  fit: exact
  layer: domain
  why: named by 2 of 6 reference apps (highspot, showpad, bigtincan, seismic)
- capability:
    attribution: Turbo EA
    id: BC-3740.30
    key: content-delivery-network-operations
    name: Content Delivery Network Operations
    url: /capabilities/content-delivery-network-operations/
    via_parent: null
  fit: exact
  layer: domain
  why: named by 2 of 6 reference apps (akamai, cloudfront, google-cloud-cdn)
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: domain
  why: named by 2 of 6 reference apps (microsoft-entra, okta, onelogin)
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: domain
  why: named by 2 of 6 reference apps (facebook, instagram, linkedin, pinterest...)
- capability:
    attribution: API Evangelist extension
    id: AE-110.50.10
    key: AE-110.50.10
    name: Image Recognition
    url: /capabilities/vision/
    via_parent: Vision
  fit: exact
  layer: domain
  why: named by 1 of 6 reference apps (google-cloud-vision)
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: exact
  layer: domain
  why: named by 1 of 6 reference apps (flickr)
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: domain
  why: named by 1 of 6 reference apps (geonames)
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: domain
  why: named by 1 of 6 reference apps (google-recaptcha)
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  fit: exact
  layer: domain
  why: named by 1 of 6 reference apps (pusher)
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  fit: exact
  layer: domain
  why: named by 1 of 6 reference apps (brightcove)
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by 1 of 6 reference apps (intercom)
- capability:
    attribution: API Evangelist extension
    id: AE-150.60.10
    key: AE-150.60.10
    name: Async Video Messaging
    url: /capabilities/video-calling/
    via_parent: Video Calling
  fit: exact
  layer: domain
  why: named by 1 of 6 reference apps (loom)
- capability:
    attribution: API Evangelist extension
    id: AE-170.80.10
    key: AE-170.80.10
    name: Web Fonts & Typography
    url: /capabilities/design-creative-editing/
    via_parent: Design & Creative Editing
  fit: exact
  layer: domain
  why: named by 1 of 6 reference apps (monotype)
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by 1 of 6 reference apps (segment)
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: nearest
  layer: domain
  why: named by 1 of 6 reference apps (amazon-web-services, gcp-cloud-storage)
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.20
    key: AE-140.10.20
    name: Headless & Composable Commerce
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: exact
  layer: domain
  why: named by 1 of 6 reference apps (commercetools)
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: domain
  why: named by 1 of 6 reference apps (google-translate)
- capability:
    attribution: API Evangelist extension
    id: AE-932
    key: AE-932
    name: Edge Functions & Edge Config Stores
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: nearest
  layer: domain
  why: named by 1 of 6 reference apps (netlify)
- capability:
    attribution: Turbo EA
    id: BC-400.60.40
    key: BC-400.60.40
    name: Social Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: exact
  layer: domain
  why: Brandwatch, Sprout Social, Sprinklr (Social Media Management)
- capability:
    attribution: API Evangelist extension
    id: AE-947
    key: AE-947
    name: Museum Collections Management
    url: /capabilities/museum-collections-management/
    via_parent: null
  fit: exact
  layer: domain
  why: Gallery Systems (TMS), Axiell (KE EMu), zetcom (MuseumPlus) (Museum Collections Management)
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Bynder
      - Canto
      - Cloudinary
      - Frontify
      - ResourceSpace
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        source: https://github.com/WordPress/mcp-adapter
        status: verified
      name: WordPress
      slug: wordpress
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - CMS
      - Content Management
      - Open Source
      - WordPress
      tier: declared
      url: /providers/wordpress/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Bynder
      - Canto
      - Cloudinary
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://registry.npmjs.org/@contentstack/mcp
        status: verified
      name: Contentstack
      slug: contentstack
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Content Delivery
      - Content Management
      - Digital Experience
      - Headless CMS
      tier: declared
      url: /providers/contentstack/
    - agent_band: agent-ready
      agent_readiness: 44.3
      apps:
      - Bynder
      - Canto
      - Cloudinary
      - Frontify
      band: developing
      in_catalog: true
      kin_score: 53.9
      mcp:
        status: none
      name: Drupal
      slug: drupal
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - CMS
      - Content Management
      - JSON:API
      - Open Source
      tier: declared
      url: /providers/drupal/
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - Bynder
      - Cloudinary
      - Frontify
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp:
        source: https://github.com/storyblok/mcp-server
        status: verified
      name: Storyblok
      slug: storyblok
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - CMS
      - Content Delivery
      - Content Management
      - Headless CMS
      tier: declared
      url: /providers/storyblok/
    - agent_band: agent-ready
      agent_readiness: 55.2
      apps:
      - Bynder
      - Cloudinary
      - Frontify
      band: developing
      in_catalog: true
      kin_score: 43.9
      mcp:
        source: https://github.com/contentful/contentful-mcp-server
        status: verified
      name: Contentful
      slug: contentful
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - CMS
      - Content
      - Content Management
      - Headless CMS
      tier: declared
      url: /providers/contentful/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Bynder
      - Cloudinary
      - Frontify
      band: thin
      in_catalog: true
      kin_score: 38.4
      mcp:
        status: unknown
      name: Sitefinity CMS
      slug: sitefinity-cms
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - .NET
      - Content Management
      - Headless CMS
      - REST
      tier: declared
      url: /providers/sitefinity-cms/
    - agent_band: agent-ready
      agent_readiness: 61.6
      apps:
      - Bynder
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 78.1
      mcp:
        source: https://support.optimizely.com/hc/en-us/articles/45320607594893
        status: documented
      name: Optimizely
      slug: optimizely
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - A/B Testing
      - Content Management
      - Customer Data
      - E-Commerce
      tier: declared
      url: /providers/optimizely/
    - agent_band: agent-ready
      agent_readiness: 63.1
      apps:
      - Bynder
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        source: https://github.com/bloomreach/loomi-alpha-mcp-google-adk
        status: documented
      name: Bloomreach
      slug: bloomreach
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Digital Commerce
      - Merchandising
      - Recommendations
      - Search
      tier: declared
      url: /providers/bloomreach/
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Bynder
      - Cloudinary
      band: strong
      in_catalog: true
      kin_score: 56.6
      mcp:
        source: https://www.sanity.io/docs/compute-and-ai/mcp-server
        status: verified
      name: Sanity
      slug: sanity
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Content Management
      - GROQ
      - Headless CMS
      - Real-Time
      tier: declared
      url: /providers/sanity/
    - agent_band: agent-native
      agent_readiness: 62.9
      apps:
      - Bynder
      - Cloudinary
      band: thin
      in_catalog: true
      kin_score: 37.0
      mcp:
        source: https://mcp.builder.io/mcp/publish
        status: verified
      name: Builder.io
      slug: builder-io
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - A/B Testing
      - Content Delivery
      - Headless CMS
      - Visual Development
      tier: declared
      url: /providers/builder-io/
    - agent_band: agent-aware
      agent_readiness: 20.1
      apps:
      - Canto
      - Frontify
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        status: none
      name: TYPO3
      slug: typo3
      sources:
      - https://www.canto.com/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - CMS
      - Content Management
      - Enterprise
      - PHP
      tier: declared
      url: /providers/typo3/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Bynder
      - Frontify
      band: thin
      in_catalog: true
      kin_score: 32.6
      mcp:
        source: https://www.sitecore.com/platform/use-cases/connect-ai-assistants-with-mcp
        status: verified
      name: Sitecore
      slug: sitecore
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Content Management
      - Customer Data Platform
      - Headless CMS
      tier: declared
      url: /providers/sitecore/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Bynder
      - Cloudinary
      band: thin
      in_catalog: true
      kin_score: 29.9
      mcp:
        source: https://github.com/kontent-ai/mcp-server
        status: verified
      name: Kontent AI
      slug: kontent-ai
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - CMS
      - Content
      - GraphQL
      - Headless CMS
      tier: declared
      url: /providers/kontent-ai/
    - agent_band: agent-aware
      agent_readiness: 21.4
      apps:
      - Bynder
      - Frontify
      band: thin
      in_catalog: true
      kin_score: 28.0
      mcp:
        source: https://github.com/adobe/cq-quickstart-mcp-server
        status: verified
      name: Adobe Experience Manager
      slug: adobe-experience-manager
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Content Management
      - Digital Asset Management
      - Enterprise CMS
      - Headless CMS
      tier: declared
      url: /providers/adobe-experience-manager/
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Bynder
      - Cloudinary
      band: emerging
      in_catalog: true
      kin_score: 21.7
      mcp:
        status: none
      name: Hygraph
      slug: hygraph
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Content Federation
      - Content Management
      - GraphQL
      - Headless CMS
      tier: declared
      url: /providers/hygraph/
    - agent_band: null
      agent_readiness: null
      apps:
      - Bynder
      - Cloudinary
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Magnolia
      slug: magnolia
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: agent-ready
      agent_readiness: 62.5
      apps:
      - Frontify
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        source: https://developers.webflow.com/mcp/reference/overview
        status: verified
      name: Webflow
      slug: webflow
      sources:
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - CMS
      - E-Commerce
      - No-Code
      - Web Development
      tier: declared
      url: /providers/webflow/
    - agent_band: agent-ready
      agent_readiness: 36.6
      apps:
      - Bynder
      band: strong
      in_catalog: true
      kin_score: 57.4
      mcp:
        source: https://docs.kentico.com/mcp
        status: verified
      name: Kentico
      slug: kentico
      sources:
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - CMS
      - Content Management
      - Digital Experience Platform
      - GraphQL
      tier: declared
      url: /providers/kentico/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Bynder
      band: emerging
      in_catalog: true
      kin_score: 12.4
      mcp:
        status: unchecked
      name: Crownpeak
      slug: crownpeak
      sources:
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - AI Infrastructure
      - Commerce
      - Conversational AI
      - Discovery AI
      tier: declared
      url: /providers/crownpeak/
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
      - Bynder
      - Canto
      - Cloudinary
      - Frontify
      - ResourceSpace
      band: exemplar
      in_catalog: true
      kin_score: 87.3
      mcp:
        source: https://www.canva.dev/docs/mcp/
        status: verified
      name: Canva
      slug: canva
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Application
      - Automation
      - Brand Management
      - Collaboration
      tier: declared
      url: /providers/canva/
    - agent_band: agent-ready
      agent_readiness: 62.9
      apps:
      - Bynder
      - Cloudinary
      - Frontify
      - ResourceSpace
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://github.com/adobe/cq-quickstart-mcp-server
        status: verified
      name: Adobe
      slug: adobe
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Adobe
      - Analytics
      - E-Signature
      - Fortune 1000
      tier: declared
      url: /providers/adobe/
    - agent_band: agent-ready
      agent_readiness: 59.2
      apps:
      - Bynder
      - Canto
      - Cloudinary
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 75.1
      mcp:
        source: https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server
        status: verified
      name: Figma
      slug: figma
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Collaboration
      - Design
      - Graphics
      - Interfaces
      tier: declared
      url: /providers/figma/
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Bynder
      - Cloudinary
      - Frontify
      band: developing
      in_catalog: true
      kin_score: 53.7
      mcp:
        source: https://blog.developer.adobe.com/en/publish/2025/09/introducing-the-adobe-express-add-on-dev-mcp-server-beta
        status: documented
      name: Adobe Creative Cloud
      slug: adobe-creative-cloud
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Cloud
      - Creative
      - Design
      tier: declared
      url: /providers/adobe-creative-cloud/
    - agent_band: human-only
      agent_readiness: 3.5
      apps:
      - Cloudinary
      - Frontify
      band: emerging
      in_catalog: true
      kin_score: 18.0
      mcp:
        source: https://github.com/sketch-hq/sketch-mcp-bundle
        status: verified
      name: Sketch
      slug: sketch
      sources:
      - https://cloudinary.com/integrations
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Collaboration
      - Design
      - Prototyping
      - Workspace
      tier: declared
      url: /providers/sketch/
    - agent_band: agent-ready
      agent_readiness: 50.5
      apps:
      - Bynder
      band: strong
      in_catalog: true
      kin_score: 64.8
      mcp:
        source: https://mcp.frame.io/v1/mcp
        status: verified
      name: Frame.io
      slug: frameio
      sources:
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Collaboration
      - Company
      - Media
      - Video
      tier: declared
      url: /providers/frameio/
    - agent_band: agent-ready
      agent_readiness: 44.5
      apps:
      - Canto
      band: developing
      in_catalog: true
      kin_score: 49.7
      mcp:
        status: unknown
      name: Adobe Photoshop
      slug: adobe-photoshop
      sources:
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Creative Cloud
      - Image Editing
      - Photoshop
      tier: declared
      url: /providers/adobe-photoshop/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Cloudinary
      band: thin
      in_catalog: true
      kin_score: 30.9
      mcp:
        status: unchecked
      name: Ziflow
      slug: ziflow
      sources:
      - https://cloudinary.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Company
      - Creative
      - Proofing
      tier: declared
      url: /providers/ziflow/
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 58.0
      apps:
      - Bynder
      - Canto
      - Cloudinary
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 70.2
      mcp:
        source: https://experienceleague.adobe.com/en/docs/workfront/using/basics/workfront-mcp-server/workfront-mcp-server-overview
        status: verified
      name: Adobe Workfront
      slug: workfront
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Company
      - Marketing Operations
      - Project Management
      - Work Management
      tier: declared
      url: /providers/workfront/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Bynder
      - Canto
      - Cloudinary
      - Frontify
      band: developing
      in_catalog: true
      kin_score: 50.0
      mcp:
        source: https://github.com/wrike/datahub-mcp
        status: verified
      name: Wrike
      slug: wrike
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: declared
      url: /providers/wrike/
    - agent_band: agent-ready
      agent_readiness: 50.3
      apps:
      - Bynder
      - Canto
      - Cloudinary
      - Frontify
      band: thin
      in_catalog: true
      kin_score: 32.2
      mcp:
        source: https://github.com/mondaycom/mcp
        status: verified
      name: monday.com
      slug: monday-com
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Automation
      - CRM
      - GraphQL
      - Work Management
      tier: declared
      url: /providers/monday-com/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Bynder
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 74.8
      mcp:
        source: https://github.com/atlassian/trello-mcp-server
        status: verified
      name: Trello
      slug: trello
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Collaboration
      - Kanban
      - Project Management
      - Task Management
      tier: declared
      url: /providers/trello/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - Canto
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://www.canto.com/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: declared
      url: /providers/asana/
    - agent_band: agent-ready
      agent_readiness: 64.4
      apps:
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: declared
      url: /providers/jira/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.6
      apps:
      - Bynder
      - Cloudinary
      - Frontify
      - ResourceSpace
      band: developing
      in_catalog: true
      kin_score: 42.6
      mcp:
        status: none
      name: Shutterstock
      slug: shutterstock
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Image
      - Media
      - Photos
      - Stock Images
      tier: declared
      url: /providers/shutterstock/
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Bynder
      - Cloudinary
      - Frontify
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.gettyimages.com/mcp/
        status: verified
      name: Getty Images
      slug: getty-images
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Image
      - Media
      - Photos
      - Video
      tier: declared
      url: /providers/getty-images/
    - agent_band: agent-ready
      agent_readiness: 52.6
      apps:
      - Bynder
      - Cloudinary
      band: developing
      in_catalog: true
      kin_score: 39.4
      mcp:
        status: none
      name: Unsplash
      slug: unsplash
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Image
      - Photography
      - Photos
      - Stock Photos
      tier: declared
      url: /providers/unsplash/
    - agent_band: agent-aware
      agent_readiness: 20.6
      apps:
      - Bynder
      - Cloudinary
      band: thin
      in_catalog: true
      kin_score: 28.4
      mcp:
        source: https://developer.gettyimages.com/mcp/
        status: verified
      name: iStock
      slug: istock
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Illustrations
      - Image
      - Stock Media
      - Video
      tier: declared
      url: /providers/istock/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - ResourceSpace
      band: emerging
      in_catalog: true
      kin_score: 13.7
      mcp:
        status: none
      name: Pixabay
      slug: pixabay
      sources:
      - https://www.resourcespace.com/knowledge-base/plugins/image_banks
      status: profiled
      tags:
      - Illustrations
      - Image
      - Stock Media
      - Video
      tier: declared
      url: /providers/pixabay/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Bynder
      band: minimal
      in_catalog: true
      kin_score: 3.7
      mcp:
        status: unchecked
      name: Vecteezy
      slug: vecteezy
      sources:
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/vecteezy/
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
      - Bynder
      - Canto
      - Cloudinary
      - Frontify
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: declared
      url: /providers/dropbox/
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Bynder
      - Canto
      band: exemplar
      in_catalog: true
      kin_score: 73.2
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: declared
      url: /providers/google-drive/
    - agent_band: agent-ready
      agent_readiness: 56.6
      apps:
      - Bynder
      - Canto
      band: strong
      in_catalog: true
      kin_score: 63.0
      mcp:
        source: https://developer.box.com/guides/box-mcp/
        status: verified
      name: Box
      slug: box
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Content Management
      - Documents
      tier: declared
      url: /providers/box/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Bynder
      - Canto
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        status: none
      name: Microsoft OneDrive
      slug: microsoft-onedrive
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: declared
      url: /providers/microsoft-onedrive/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Canto
      band: thin
      in_catalog: true
      kin_score: 29.5
      mcp:
        source: https://github.com/egnyte/egnyte-mcp-server
        status: verified
      name: Egnyte
      slug: egnyte
      sources:
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Content Collaboration
      - Document Management
      - Enterprise Storage
      - File Sharing
      tier: declared
      url: /providers/egnyte/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - Bynder
      - Canto
      - Cloudinary
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 77.6
      mcp:
        status: none
      name: Salesforce Marketing Cloud
      slug: salesforce-marketing-cloud
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Automation
      - Content Management
      - Customer Journey
      - Digital Marketing
      tier: declared
      url: /providers/salesforce-marketing-cloud/
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Canto
      - Cloudinary
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://cloudinary.com/integrations
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - Bynder
      - Cloudinary
      band: strong
      in_catalog: true
      kin_score: 57.2
      mcp:
        status: none
      name: Marketo
      slug: marketo
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Adobe
      - Automation
      - Marketing
      - Marketing Automation
      tier: declared
      url: /providers/marketo/
    - agent_band: agent-native
      agent_readiness: 58.7
      apps:
      - Cloudinary
      band: exemplar
      in_catalog: true
      kin_score: 78.1
      mcp:
        source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
        status: verified
      name: Klaviyo
      slug: klaviyo
      sources:
      - https://cloudinary.com/integrations
      status: profiled
      tags:
      - Customer Data
      - Email
      - Marketing
      - SMS
      tier: declared
      url: /providers/klaviyo/
    - agent_band: agent-ready
      agent_readiness: 58.4
      apps:
      - Cloudinary
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
        status: verified
      name: Braze
      slug: braze
      sources:
      - https://cloudinary.com/integrations
      status: profiled
      tags:
      - Customer Engagement
      - Marketing Automation
      - Messaging
      - Push Notifications
      tier: declared
      url: /providers/braze/
    - agent_band: agent-ready
      agent_readiness: 38.2
      apps:
      - Bynder
      band: exemplar
      in_catalog: true
      kin_score: 69.8
      mcp:
        status: none
      name: Dotdigital
      slug: dotdigital
      sources:
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Email Marketing
      - MMS
      - Marketing Automation
      - SMS
      tier: declared
      url: /providers/dotdigital/
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
      - Canto
      - Cloudinary
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://cloudinary.com/integrations
      - https://www.canto.com/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Bynder
      - Cloudinary
      - Frontify
      band: strong
      in_catalog: true
      kin_score: 64.0
      mcp:
        source: https://mcp.ci-hub.com/.well-known/oauth-protected-resource
        status: verified
      name: CI HUB
      slug: ci-hub
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Company
      - Content Management
      - Digital Asset Management
      - Product Information Management
      tier: declared
      url: /providers/ci-hub/
    - agent_band: agent-ready
      agent_readiness: 60.3
      apps:
      - Bynder
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 89.5
      mcp:
        source: https://docs.tray.ai/
        status: documented
      name: Tray.io
      slug: tray-ai
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - AI Agents
      - Automation
      - Integration
      - iPaaS
      tier: declared
      url: /providers/tray-ai/
    - agent_band: agent-ready
      agent_readiness: 53.8
      apps:
      - Bynder
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://docs.workato.com/mcp.html
        status: verified
      name: Workato
      slug: workato
      sources:
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - AI Agents
      - API Management
      - Automation
      - B2B
      tier: declared
      url: /providers/workato/
    - agent_band: agent-ready
      agent_readiness: 35.7
      apps:
      - Cloudinary
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        source: https://docs.n8n.io/advanced-ai/accessing-n8n-mcp-server/
        status: verified
      name: n8n
      slug: n8n
      sources:
      - https://cloudinary.com/integrations
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Integration
      - Workflows
      tier: declared
      url: /providers/n8n/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Cloudinary
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://cloudinary.com/integrations
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
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
      - Bynder
      - Canto
      - Cloudinary
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify
      slug: shopify
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: declared
      url: /providers/shopify/
    - agent_band: agent-aware
      agent_readiness: 22.8
      apps:
      - Bynder
      - Cloudinary
      band: developing
      in_catalog: true
      kin_score: 47.1
      mcp:
        status: unknown
      name: SAP Commerce Cloud
      slug: sap-commerce-cloud
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - B2B
      - Commerce
      - Consumer
      - Customer Experience
      tier: declared
      url: /providers/sap-commerce-cloud/
    - agent_band: agent-aware
      agent_readiness: 21.7
      apps:
      - Bynder
      - Cloudinary
      band: thin
      in_catalog: true
      kin_score: 35.0
      mcp:
        source: https://github.com/SalesforceCommerceCloud/b2c-developer-tooling
        status: verified
      name: Salesforce Commerce Cloud
      slug: salesforce-commerce-cloud
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Headless Commerce
      - Salesforce
      tier: declared
      url: /providers/salesforce-commerce-cloud/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Bynder
      - Cloudinary
      band: emerging
      in_catalog: true
      kin_score: 18.0
      mcp:
        status: none
      name: Adobe Commerce
      slug: adobe-commerce
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Adobe
      - Commerce
      - E-Commerce
      - Magento
      tier: declared
      url: /providers/adobe-commerce/
  - capability:
      attribution: Turbo EA
      id: BC-2370
      key: product-information-management
      name: Product Information Management
      url: /capabilities/product-information-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - Bynder
      - Canto
      - Cloudinary
      - Frontify
      band: developing
      in_catalog: true
      kin_score: 42.3
      mcp:
        source: https://api.akeneo.com/mcp/overview.html
        status: verified
      name: Akeneo
      slug: akeneo
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Catalog Management
      - Commerce
      - Product Data
      - Product Information Management
      tier: declared
      url: /providers/akeneo/
    - agent_band: agent-ready
      agent_readiness: 49.5
      apps:
      - Bynder
      - Frontify
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        source: https://www.salsify.com/press-release-salsify-unveils-salsifyiq-first-pxm-intelligence-layer-for-agentic-commerce
        status: documented
      name: Salsify
      slug: salsify
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Company
      - Digital Asset Management
      - Product Experience Management
      - Product Information Management
      tier: declared
      url: /providers/salsify/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Bynder
      - Cloudinary
      band: emerging
      in_catalog: true
      kin_score: 20.0
      mcp:
        status: unchecked
      name: Stibo Systems
      slug: stibo-systems
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Company
      - Data Governance
      - MDM
      - Product Information Management
      tier: declared
      url: /providers/stibo-systems/
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - Cloudinary
      band: thin
      in_catalog: true
      kin_score: 35.0
      mcp:
        status: unknown
      name: Syndigo
      slug: syndigo
      sources:
      - https://cloudinary.com/integrations
      status: profiled
      tags:
      - Company
      - Data
      - Master Data Management
      - Product Information Management
      tier: declared
      url: /providers/syndigo/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Bynder
      band: emerging
      in_catalog: true
      kin_score: 15.2
      mcp:
        status: unchecked
      name: inriver
      slug: inriver
      sources:
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - B2B
      - Omnichannel
      - Product Information Management
      tier: declared
      url: /providers/inriver/
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
      - Canto
      - Frontify
      - Phraseanet
      - ResourceSpace
      band: strong
      in_catalog: true
      kin_score: 65.4
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://github.com/alchemy-fr/Phraseanet/tree/master/lib/classes/Bridge/Api
      - https://www.canto.com/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: observed
      url: /providers/youtube/
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - Bynder
      - Canto
      - Frontify
      - ResourceSpace
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp:
        source: https://developer.vimeo.com/api/mcp-server
        status: documented
      name: Vimeo
      slug: vimeo
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Live Streaming
      - Streaming
      - Video
      - Video Hosting
      tier: declared
      url: /providers/vimeo/
    - agent_band: human-only
      agent_readiness: 3.8
      apps:
      - Phraseanet
      band: minimal
      in_catalog: true
      kin_score: 8.2
      mcp:
        status: none
      name: Dailymotion
      slug: dailymotion
      sources:
      - https://github.com/alchemy-fr/Phraseanet/tree/master/lib/classes/Bridge/Api
      status: profiled
      tags:
      - Public APIs
      - Video
      tier: observed
      url: /providers/dailymotion/
  - capability:
      attribution: Turbo EA
      id: BC-400.60.40
      key: BC-400.60.40
      name: Social Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.8
      apps:
      - Bynder
      - Canto
      - Cloudinary
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 72.8
      mcp:
        status: none
      name: Hootsuite
      slug: hootsuite
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Content Scheduling
      - Marketing
      - Social Media
      - Social Media Management
      tier: declared
      url: /providers/hootsuite/
    - agent_band: agent-aware
      agent_readiness: 28.0
      apps:
      - Bynder
      - Frontify
      band: developing
      in_catalog: true
      kin_score: 46.3
      mcp:
        source: https://mcp.sprinklr.com/mcp
        status: verified
      name: Sprinklr
      slug: sprinklr
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Customer Experience
      - Customer Service
      - Marketing
      - Social Media Management
      tier: declared
      url: /providers/sprinklr/
    - agent_band: agent-ready
      agent_readiness: 39.2
      apps:
      - ResourceSpace
      band: strong
      in_catalog: true
      kin_score: 57.5
      mcp: &id005
        status: unknown
      name: Brandwatch
      slug: brandwatch
      sources:
      - https://www.resourcespace.com/knowledge-base/plugins
      status: profiled
      tags: &id006
      - Analytics
      - Consumer Intelligence
      - Social Media
      - Social Media Monitoring
      tier: declared
      url: /providers/brandwatch/
    - agent_band: agent-aware
      agent_readiness: 15.8
      apps:
      - Bynder
      band: strong
      in_catalog: true
      kin_score: 54.8
      mcp:
        status: none
      name: Sprout Social
      slug: sprout-social
      sources:
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Analytics
      - Publishing
      - Social Media
      - Social Media Management
      tier: declared
      url: /providers/sprout-social/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Bynder
      - Cloudinary
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft 365
      slug: microsoft-365
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/microsoft-365/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Bynder
      - Cloudinary
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/gemini-cli-extensions/workspace
        status: verified
      name: Google Workspace
      slug: google-workspace
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/google-workspace/
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
      - Bynder
      - Canto
      - Cloudinary
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Bynder
      - Canto
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: declared
      url: /providers/microsoft-teams/
  - capability:
      attribution: Turbo EA
      id: BC-410.50.30
      key: BC-410.50.30
      name: Sales Enablement
      url: /capabilities/sales-operations-management/
      via_parent: Sales Operations Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.3
      apps:
      - Bynder
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://developer.showpad.com/news/mcp-tools
        status: verified
      name: Showpad
      slug: showpad
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Buyer Engagement
      - Content Management
      - Sales Coaching
      - Sales Enablement
      tier: declared
      url: /providers/showpad/
    - agent_band: agent-ready
      agent_readiness: 29.2
      apps:
      - Bynder
      - Frontify
      band: developing
      in_catalog: true
      kin_score: 45.6
      mcp:
        source: https://mcp.highspot.com/mcp
        status: verified
      name: Highspot
      slug: highspot
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - CRM Integration
      - Content Management
      - Pitch Analytics
      - Sales Enablement
      tier: declared
      url: /providers/highspot/
    - agent_band: agent-ready
      agent_readiness: 51.7
      apps:
      - Bynder
      band: exemplar
      in_catalog: true
      kin_score: 76.2
      mcp:
        source: https://developer.seismic.com/seismicsoftware/docs/seismic-mcp-server
        status: verified
      name: Seismic
      slug: seismic
      sources:
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Content Management
      - Document Generation
      - Sales Content
      - Sales Enablement
      tier: declared
      url: /providers/seismic/
    - agent_band: agent-ready
      agent_readiness: 32.2
      apps:
      - Bynder
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        status: unknown
      name: Bigtincan
      slug: bigtincan
      sources:
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Coaching
      - Content Management
      - Sales Enablement
      - Training
      tier: declared
      url: /providers/bigtincan/
  - capability:
      attribution: API Evangelist extension
      id: AE-917
      key: AE-917
      name: Enterprise Content & Document Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.3
      apps:
      - Bynder
      - Canto
      - Frontify
      band: strong
      in_catalog: true
      kin_score: 60.9
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft SharePoint
      slug: sharepoint
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Collaboration
      - Document Management
      - Enterprise Content Management
      - Intranet
      tier: declared
      url: /providers/sharepoint/
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - Bynder
      - Frontify
      band: strong
      in_catalog: true
      kin_score: 57.5
      mcp:
        source: https://www.templafy.com/
        status: verified
      name: Templafy
      slug: templafy
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Company
      - Content Management
      - Document Generation
      - Templates
      tier: declared
      url: /providers/templafy/
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
      - Canto
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp: &id001
        status: none
      name: LinkedIn
      slug: linkedin
      sources:
      - https://www.canto.com/integrations/
      status: profiled
      tags: &id002
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: declared
      url: /providers/linkedin/
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - Canto
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: X (Twitter)
      slug: x
      sources:
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: declared
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 67.8
      mcp:
        status: none
      name: Instagram
      slug: instagram
      sources:
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Instagram
      - Meta
      - Photos
      - Social Media
      tier: declared
      url: /providers/instagram/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Canto
      band: developing
      in_catalog: true
      kin_score: 47.7
      mcp:
        source: https://developers.pinterest.com/about-pinterest-mcp/
        status: verified
      name: Pinterest
      slug: pinterest
      sources:
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Image
      - Social
      - Social Media
      - Video
      tier: declared
      url: /providers/pinterest/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Canto
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id003
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://www.canto.com/integrations/
      status: profiled
      tags: &id004
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: declared
      url: /providers/facebook/
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
      - Bynder
      - Canto
      - Cloudinary
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://cloudinary.com/integrations
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
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
      - Cloudinary
      - ResourceSpace
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://cloudinary.com/integrations
      - https://www.resourcespace.com/knowledge-base/plugins
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: declared
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Cloudinary
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://cloudinary.com/integrations
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: declared
      url: /providers/anthropic/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Cloudinary
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://cloudinary.com/integrations
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: declared
      url: /providers/google-gemini/
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
      - Bynder
      - Canto
      - ResourceSpace
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.canto.com/integrations/
      - https://www.resourcespace.com/knowledge-base/plugins
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: declared
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 46.7
      apps:
      - Cloudinary
      band: thin
      in_catalog: true
      kin_score: 33.0
      mcp:
        status: none
      name: Contentsquare
      slug: contentsquare
      sources:
      - https://cloudinary.com/integrations
      status: profiled
      tags:
      - Digital Experience Analytics
      - Heatmaps
      - Product Analytics
      - Session Replay
      tier: declared
      url: /providers/contentsquare/
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
      - Phraseanet
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/alchemy-fr/Phraseanet/tree/master/lib/Alchemy/Phrasea/Authentication/Provider
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Phraseanet
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp: *id001
      name: LinkedIn
      slug: linkedin
      sources:
      - https://github.com/alchemy-fr/Phraseanet/tree/master/lib/Alchemy/Phrasea/Authentication/Provider
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/linkedin/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Phraseanet
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/alchemy-fr/Phraseanet/tree/master/lib/Alchemy/Phrasea/Authentication/Provider
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Bynder
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google Identity Platform
      slug: google-identity-platform
      sources:
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: declared
      url: /providers/google-identity-platform/
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Bynder
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Azure Active Directory / Microsoft Entra ID
      slug: microsoft-entra
      sources:
      - https://www.bynder.com/en/integrations/
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: declared
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: declared
      url: /providers/okta/
    - agent_band: agent-aware
      agent_readiness: 24.3
      apps:
      - Frontify
      band: thin
      in_catalog: true
      kin_score: 29.5
      mcp:
        source: https://github.com/onelogin/onelogin-mcp
        status: verified
      name: OneLogin
      slug: onelogin
      sources:
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Identity
      - Identity and Access Management
      - Multi-Factor Authentication
      - SSO
      tier: declared
      url: /providers/onelogin/
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
      - Bynder
      band: exemplar
      in_catalog: true
      kin_score: 79.6
      mcp:
        status: none
      name: Amazon CloudFront
      slug: cloudfront
      sources:
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Amazon Web Services
      - CDN
      - Caching
      - Content Delivery
      tier: declared
      url: /providers/cloudfront/
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - Cloudinary
      band: exemplar
      in_catalog: true
      kin_score: 67.1
      mcp:
        status: unknown
      name: Google Cloud CDN
      slug: google-cloud-cdn
      sources:
      - https://cloudinary.com/integrations
      status: profiled
      tags:
      - CDN
      - Caching
      - Content Delivery
      - Google Cloud
      tier: declared
      url: /providers/google-cloud-cdn/
    - agent_band: agent-ready
      agent_readiness: 40.0
      apps:
      - Bynder
      band: developing
      in_catalog: true
      kin_score: 53.8
      mcp:
        status: none
      name: Akamai
      slug: akamai
      sources:
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - CDN
      - Cloud
      - Edge Computing
      - Networks
      tier: declared
      url: /providers/akamai/
  - capability:
      attribution: API Evangelist extension
      id: AE-947
      key: AE-947
      name: Museum Collections Management
      url: /capabilities/museum-collections-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - ResourceSpace
      band: emerging
      in_catalog: true
      kin_score: 18.7
      mcp:
        status: unchecked
      name: zetcom (MuseumPlus)
      slug: zetcom
      sources:
      - https://www.resourcespace.com/knowledge-base/plugins
      status: profiled
      tags:
      - Collection Management
      - Museum Software
      tier: declared
      url: /providers/zetcom/
    - agent_band: agent-aware
      agent_readiness: 20.6
      apps:
      - ResourceSpace
      band: emerging
      in_catalog: true
      kin_score: 14.7
      mcp:
        status: unchecked
      name: Gallery Systems (TMS)
      slug: gallery-systems
      sources:
      - https://www.resourcespace.com/knowledge-base/plugins
      status: profiled
      tags:
      - Collection
      - Company
      - Digital Asset Management
      - Museum Software
      tier: declared
      url: /providers/gallery-systems/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - ResourceSpace
      band: minimal
      in_catalog: true
      kin_score: 5.8
      mcp:
        status: unchecked
      name: Axiell (KE EMu)
      slug: axiell
      sources:
      - https://www.resourcespace.com/knowledge-base/plugins
      status: profiled
      tags:
      - Company
      - Library
      - Museums
      - Software
      tier: declared
      url: /providers/axiell/
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.9
      apps:
      - Frontify
      band: exemplar
      in_catalog: true
      kin_score: 77.9
      mcp:
        status: none
      name: Bynder
      slug: bynder
      sources:
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Brand Management
      - Content Management
      - Digital Asset Management
      - Marketing
      tier: declared
      url: /providers/bynder/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Frontify
      band: emerging
      in_catalog: true
      kin_score: 12.8
      mcp:
        status: unchecked
      name: CELUM
      slug: celum
      sources:
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Content Management
      - Digital Asset Management
      tier: declared
      url: /providers/celum/
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Phraseanet
      band: developing
      in_catalog: true
      kin_score: 43.6
      mcp:
        source: https://github.com/elastic/mcp-server-elasticsearch
        status: verified
      name: Elasticsearch
      slug: elasticsearch
      sources:
      - https://github.com/alchemy-fr/Phraseanet/blob/master/composer.json
      status: profiled
      tags:
      - Analytics
      - Database
      - Full-Text Search
      - NoSQL
      tier: observed
      url: /providers/elasticsearch/
    - agent_band: agent-ready
      agent_readiness: 47.3
      apps:
      - ResourceSpace
      band: thin
      in_catalog: true
      kin_score: 39.2
      mcp:
        source: https://typesense.org/docs/guide/typesense-cloud/mcp-server.html
        status: verified
      name: Typesense
      slug: typesense
      sources:
      - https://www.resourcespace.com/knowledge-base/plugins
      status: profiled
      tags:
      - Full-Text Search
      - Open Source
      - Search Engines
      - Typo Tolerance
      tier: declared
      url: /providers/typesense/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Cloudinary
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://cloudinary.com/integrations
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: declared
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Cloudinary
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Web Services
      slug: amazon-web-services
      sources:
      - https://cloudinary.com/integrations
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: declared
      url: /providers/amazon-web-services/
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
      - Frontify
      band: emerging
      in_catalog: true
      kin_score: 18.4
      mcp:
        status: none
      name: Loom
      slug: loom
      sources:
      - https://www.frontify.com/en/integrations
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
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Phraseanet
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://github.com/alchemy-fr/Phraseanet/blob/master/composer.json
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
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Frontify
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Twilio Segment
      slug: segment
      sources:
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: declared
      url: /providers/segment/
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
      - Frontify
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: declared
      url: /providers/intercom/
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 58.9
      apps:
      - Cloudinary
      band: exemplar
      in_catalog: true
      kin_score: 72.2
      mcp:
        source: https://github.com/netlify/netlify-mcp
        status: verified
      name: Netlify
      slug: netlify
      sources:
      - https://cloudinary.com/integrations
      status: profiled
      tags:
      - CDN
      - Cloud
      - Continuous Deployment
      - Developer Tools
      tier: declared
      url: /providers/netlify/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Phraseanet
      band: minimal
      in_catalog: true
      kin_score: 4.3
      mcp:
        status: none
      name: GeoNames
      slug: geonames
      sources:
      - https://github.com/alchemy-fr/Phraseanet/blob/master/composer.json
      status: profiled
      tags:
      - Geocoding
      - Public APIs
      tier: observed
      url: /providers/geonames/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.20
      key: AE-140.10.20
      name: Headless & Composable Commerce
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.5
      apps:
      - Cloudinary
      band: strong
      in_catalog: true
      kin_score: 61.5
      mcp:
        source: https://github.com/commercetools/mcp-essentials
        status: verified
      name: commercetools
      slug: commercetools
      sources:
      - https://cloudinary.com/integrations
      status: profiled
      tags:
      - Commerce
      - Composable Commerce
      - E-Commerce
      - GraphQL
      tier: declared
      url: /providers/commercetools/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.50.10
      key: AE-110.50.10
      name: Image Recognition
      url: /capabilities/vision/
      via_parent: Vision
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - ResourceSpace
      band: exemplar
      in_catalog: true
      kin_score: 70.0
      mcp:
        status: unknown
      name: Google Cloud Vision
      slug: google-cloud-vision
      sources:
      - https://www.resourcespace.com/knowledge-base/plugins
      status: profiled
      tags:
      - Computer Vision
      - Google Cloud
      - Image Analysis
      - Machine Learning
      tier: declared
      url: /providers/google-cloud-vision/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.9
      apps:
      - Cloudinary
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: Google Cloud Translation API
      slug: google-translate
      sources:
      - https://cloudinary.com/integrations
      status: profiled
      tags:
      - Google Cloud
      - Internationalization
      - Language Detection
      - Localization
      tier: declared
      url: /providers/google-translate/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.1
      apps:
      - Phraseanet
      band: developing
      in_catalog: true
      kin_score: 49.1
      mcp:
        status: none
      name: Flickr
      slug: flickr
      sources:
      - https://github.com/alchemy-fr/Phraseanet/tree/master/lib/classes/Bridge/Api
      status: profiled
      tags:
      - Photography
      - Photos
      - Public APIs
      - Social Media
      tier: observed
      url: /providers/flickr/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - Phraseanet
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Pusher
      slug: pusher
      sources:
      - https://github.com/alchemy-fr/Phraseanet/blob/master/composer.json
      status: profiled
      tags:
      - Pub/Sub
      - Push Notifications
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/pusher/
  - capability:
      attribution: API Evangelist extension
      id: AE-914
      key: AE-914
      name: Social Listening & Analytics
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.2
      apps:
      - Bynder
      band: strong
      in_catalog: true
      kin_score: 57.5
      mcp: *id005
      name: Brandwatch
      slug: brandwatch
      sources:
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags: *id006
      tier: declared
      url: /providers/brandwatch/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.5
      apps:
      - Bynder
      band: thin
      in_catalog: true
      kin_score: 33.3
      mcp:
        status: none
      name: Brightcove
      slug: brightcove
      sources:
      - https://www.bynder.com/en/integrations/
      status: profiled
      tags:
      - Live Streaming
      - Media
      - Streaming
      - Video
      tier: declared
      url: /providers/brightcove/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80.10
      key: AE-170.80.10
      name: Web Fonts & Typography
      url: /capabilities/design-creative-editing/
      via_parent: Design & Creative Editing
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.0
      apps:
      - Frontify
      band: thin
      in_catalog: true
      kin_score: 29.4
      mcp:
        status: unchecked
      name: Monotype
      slug: monotype
      sources:
      - https://www.frontify.com/en/integrations
      status: profiled
      tags:
      - Creative Services
      - Font Management
      - Fonts
      - Typography
      tier: declared
      url: /providers/monotype/
  layer: domain
summary:
  coverage_pct: 99.2
  declared_only: 113
  distinct_providers: 123
  in_catalog: 122
  mcp:
    documented: 6
    none: 35
    unchecked: 11
    verified: 63
  mcp_verified: 63
  mean_kin_score: 53.8
  observed: 10
  queued: 1
  reference_apps: 6
title: 'Digital Asset Management: application blueprint'
---
