---
app: Cloudinary
app_slug: cloudinary
app_url: https://cloudinary.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Dropbox
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-3740.30
  key: content-delivery-network-operations
  layer: domain
  name: Content Delivery Network Operations
  providers:
  - Google Cloud CDN
  url: /capabilities/content-delivery-network-operations/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: domain
  name: Content Management
  providers:
  - Builder.io
  - Contentful
  - Contentstack
  - Drupal
  - Hygraph
  - Kontent AI
  - Magnolia
  - Sanity
  - Sitefinity CMS
  - Storyblok
  - WordPress
  url: /capabilities/content-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: domain
  name: Design & Creative Editing
  providers:
  - Adobe
  - Adobe Creative Cloud
  - Canva
  - Figma
  - Sketch
  - Ziflow
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Braze
  - Klaviyo
  - Mailchimp
  - Marketo
  - Salesforce Marketing Cloud
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-932
  key: AE-932
  layer: domain
  name: Edge Functions & Edge Config Stores
  providers:
  - Netlify
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-600.50.50
  key: BC-600.50.50
  layer: domain
  name: End-User Computing Management
  providers:
  - Google Workspace
  - Microsoft 365
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-140.10.20
  key: AE-140.10.20
  layer: domain
  name: Headless & Composable Commerce
  providers:
  - commercetools
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: domain
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - Google Gemini
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - Adobe Commerce
  - Salesforce Commerce Cloud
  - SAP Commerce Cloud
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: domain
  name: Internal Communications Management
  providers:
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: domain
  name: Machine Translation
  providers:
  - Google Cloud Translation API
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: Turbo EA
  id: BC-2370
  key: product-information-management
  layer: domain
  name: Product Information Management
  providers:
  - Akeneo
  - Stibo Systems
  - Syndigo
  url: /capabilities/product-information-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: domain
  name: Product Usage Analytics
  providers:
  - Contentsquare
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - Adobe Workfront
  - monday.com
  - Wrike
  url: /capabilities/project-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60.40
  key: BC-400.60.40
  layer: domain
  name: Social Media Management
  providers:
  - Hootsuite
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-170.30.40
  key: AE-170.30.40
  layer: domain
  name: Stock Media & Royalty-Free Libraries
  providers:
  - Getty Images
  - iStock
  - Shutterstock
  - Unsplash
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: domain
  name: Storage Management
  providers:
  - Amazon Web Services
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: domain
  name: Workflow Automation & iPaaS
  providers:
  - CI HUB
  - Make
  - n8n
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: digital-asset-management
  name: Digital Asset Management
  url: /applications/digital-asset-management/
counts:
  declared: 56
  observed: 0
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 62.9
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id001
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe
    status: profiled
    tags: &id002
    - Adobe
    - Analytics
    - E-Signature
    - Fortune 1000
    url: /providers/adobe/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 18.0
    mcp: &id003
      status: none
    slug: adobe-commerce
    status: profiled
    tags: &id004
    - Adobe
    - Commerce
    - E-Commerce
    - Magento
    url: /providers/adobe-commerce/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: developing
    in_catalog: true
    kin_score: 53.7
    mcp: &id005
      source: https://blog.developer.adobe.com/en/publish/2025/09/introducing-the-adobe-express-add-on-dev-mcp-server-beta
      status: documented
    slug: adobe-creative-cloud
    status: profiled
    tags: &id006
    - Artificial Intelligence
    - Cloud
    - Creative
    - Design
    url: /providers/adobe-creative-cloud/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.0
    band: exemplar
    in_catalog: true
    kin_score: 70.2
    mcp: &id007
      source: https://experienceleague.adobe.com/en/docs/workfront/using/basics/workfront-mcp-server/workfront-mcp-server-overview
      status: verified
    slug: workfront
    status: profiled
    tags: &id008
    - Company
    - Marketing Operations
    - Project Management
    - Work Management
    url: /providers/workfront/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.7
    band: developing
    in_catalog: true
    kin_score: 42.3
    mcp: &id009
      source: https://api.akeneo.com/mcp/overview.html
      status: verified
    slug: akeneo
    status: profiled
    tags: &id010
    - Catalog Management
    - Commerce
    - Product Data
    - Product Information Management
    url: /providers/akeneo/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id011
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id012
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id013
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id014
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id015
      source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
      status: verified
    slug: braze
    status: profiled
    tags: &id016
    - Customer Engagement
    - Marketing Automation
    - Messaging
    - Push Notifications
    url: /providers/braze/
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
  facts:
    agent_band: agent-native
    agent_readiness: 62.9
    band: thin
    in_catalog: true
    kin_score: 37.0
    mcp: &id017
      source: https://mcp.builder.io/mcp/publish
      status: verified
    slug: builder-io
    status: profiled
    tags: &id018
    - A/B Testing
    - Content Delivery
    - Headless CMS
    - Visual Development
    url: /providers/builder-io/
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
  facts:
    agent_band: agent-native
    agent_readiness: 70.0
    band: exemplar
    in_catalog: true
    kin_score: 87.3
    mcp: &id019
      source: https://www.canva.dev/docs/mcp/
      status: verified
    slug: canva
    status: profiled
    tags: &id020
    - Application
    - Automation
    - Brand Management
    - Collaboration
    url: /providers/canva/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: strong
    in_catalog: true
    kin_score: 64.0
    mcp: &id021
      source: https://mcp.ci-hub.com/.well-known/oauth-protected-resource
      status: verified
    slug: ci-hub
    status: profiled
    tags: &id022
    - Company
    - Content Management
    - Digital Asset Management
    - Product Information Management
    url: /providers/ci-hub/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.5
    band: strong
    in_catalog: true
    kin_score: 61.5
    mcp: &id023
      source: https://github.com/commercetools/mcp-essentials
      status: verified
    slug: commercetools
    status: profiled
    tags: &id024
    - Commerce
    - Composable Commerce
    - E-Commerce
    - GraphQL
    url: /providers/commercetools/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 55.2
    band: developing
    in_catalog: true
    kin_score: 43.9
    mcp: &id025
      source: https://github.com/contentful/contentful-mcp-server
      status: verified
    slug: contentful
    status: profiled
    tags: &id026
    - CMS
    - Content
    - Content Management
    - Headless CMS
    url: /providers/contentful/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 46.7
    band: thin
    in_catalog: true
    kin_score: 33.0
    mcp: &id027
      status: none
    slug: contentsquare
    status: profiled
    tags: &id028
    - Digital Experience Analytics
    - Heatmaps
    - Product Analytics
    - Session Replay
    url: /providers/contentsquare/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id029
      source: https://registry.npmjs.org/@contentstack/mcp
      status: verified
    slug: contentstack
    status: profiled
    tags: &id030
    - Content Delivery
    - Content Management
    - Digital Experience
    - Headless CMS
    url: /providers/contentstack/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id031
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id032
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.3
    band: developing
    in_catalog: true
    kin_score: 53.9
    mcp: &id033
      status: none
    slug: drupal
    status: profiled
    tags: &id034
    - CMS
    - Content Management
    - JSON:API
    - Open Source
    url: /providers/drupal/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 59.2
    band: exemplar
    in_catalog: true
    kin_score: 75.1
    mcp: &id035
      source: https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server
      status: verified
    slug: figma
    status: profiled
    tags: &id036
    - Collaboration
    - Design
    - Graphics
    - Interfaces
    url: /providers/figma/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.0
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id037
      source: https://developer.gettyimages.com/mcp/
      status: verified
    slug: getty-images
    status: profiled
    tags: &id038
    - Image
    - Media
    - Photos
    - Video
    url: /providers/getty-images/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id039
      status: unknown
    slug: google-cloud-cdn
    status: profiled
    tags: &id040
    - CDN
    - Caching
    - Content Delivery
    - Google Cloud
    url: /providers/google-cloud-cdn/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id041
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id042
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.9
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id043
      status: none
    slug: google-translate
    status: profiled
    tags: &id044
    - Google Cloud
    - Internationalization
    - Language Detection
    - Localization
    url: /providers/google-translate/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id045
      status: none
    slug: google-gemini
    status: profiled
    tags: &id046
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id047
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id048
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 48.8
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id049
      status: none
    slug: hootsuite
    status: profiled
    tags: &id050
    - Content Scheduling
    - Marketing
    - Social Media
    - Social Media Management
    url: /providers/hootsuite/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id051
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id052
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.9
    band: emerging
    in_catalog: true
    kin_score: 21.7
    mcp: &id053
      status: none
    slug: hygraph
    status: profiled
    tags: &id054
    - Content Federation
    - Content Management
    - GraphQL
    - Headless CMS
    url: /providers/hygraph/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.6
    band: thin
    in_catalog: true
    kin_score: 28.4
    mcp: &id055
      source: https://developer.gettyimages.com/mcp/
      status: verified
    slug: istock
    status: profiled
    tags: &id056
    - Illustrations
    - Image
    - Stock Media
    - Video
    url: /providers/istock/
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
  facts:
    agent_band: agent-native
    agent_readiness: 58.7
    band: exemplar
    in_catalog: true
    kin_score: 78.1
    mcp: &id057
      source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
      status: verified
    slug: klaviyo
    status: profiled
    tags: &id058
    - Customer Data
    - Email
    - Marketing
    - SMS
    url: /providers/klaviyo/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: thin
    in_catalog: true
    kin_score: 29.9
    mcp: &id059
      source: https://github.com/kontent-ai/mcp-server
      status: verified
    slug: kontent-ai
    status: profiled
    tags: &id060
    - CMS
    - Content
    - GraphQL
    - Headless CMS
    url: /providers/kontent-ai/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id061
      status: unchecked
    slug: magnolia
    status: queued for profiling
    tags: &id062 []
    url: null
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id063
      status: none
    slug: mailchimp
    status: profiled
    tags: &id064
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: developing
    in_catalog: true
    kin_score: 43.4
    mcp: &id065
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id066
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.4
    band: strong
    in_catalog: true
    kin_score: 57.2
    mcp: &id067
      status: none
    slug: marketo
    status: profiled
    tags: &id068
    - Adobe
    - Automation
    - Marketing
    - Marketing Automation
    url: /providers/marketo/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id069
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-365
    status: profiled
    tags: &id070
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/microsoft-365/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.3
    band: thin
    in_catalog: true
    kin_score: 32.2
    mcp: &id071
      source: https://github.com/mondaycom/mcp
      status: verified
    slug: monday-com
    status: profiled
    tags: &id072
    - Automation
    - CRM
    - GraphQL
    - Work Management
    url: /providers/monday-com/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.7
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id073
      source: https://docs.n8n.io/advanced-ai/accessing-n8n-mcp-server/
      status: verified
    slug: n8n
    status: profiled
    tags: &id074
    - Agents
    - Artificial Intelligence
    - Integration
    - Workflows
    url: /providers/n8n/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.9
    band: exemplar
    in_catalog: true
    kin_score: 72.2
    mcp: &id075
      source: https://github.com/netlify/netlify-mcp
      status: verified
    slug: netlify
    status: profiled
    tags: &id076
    - CDN
    - Cloud
    - Continuous Deployment
    - Developer Tools
    url: /providers/netlify/
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
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id077
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id078
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 21.7
    band: thin
    in_catalog: true
    kin_score: 35.0
    mcp: &id079
      source: https://github.com/SalesforceCommerceCloud/b2c-developer-tooling
      status: verified
    slug: salesforce-commerce-cloud
    status: profiled
    tags: &id080
    - Commerce
    - E-Commerce
    - Headless Commerce
    - Salesforce
    url: /providers/salesforce-commerce-cloud/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 52.3
    band: exemplar
    in_catalog: true
    kin_score: 77.6
    mcp: &id081
      status: none
    slug: salesforce-marketing-cloud
    status: profiled
    tags: &id082
    - Automation
    - Content Management
    - Customer Journey
    - Digital Marketing
    url: /providers/salesforce-marketing-cloud/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: strong
    in_catalog: true
    kin_score: 56.6
    mcp: &id083
      source: https://www.sanity.io/docs/compute-and-ai/mcp-server
      status: verified
    slug: sanity
    status: profiled
    tags: &id084
    - Content Management
    - GROQ
    - Headless CMS
    - Real-Time
    url: /providers/sanity/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.8
    band: developing
    in_catalog: true
    kin_score: 47.1
    mcp: &id085
      status: unknown
    slug: sap-commerce-cloud
    status: profiled
    tags: &id086
    - B2B
    - Commerce
    - Consumer
    - Customer Experience
    url: /providers/sap-commerce-cloud/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id087
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id088
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.6
    band: developing
    in_catalog: true
    kin_score: 42.6
    mcp: &id089
      status: none
    slug: shutterstock
    status: profiled
    tags: &id090
    - Image
    - Media
    - Photos
    - Stock Images
    url: /providers/shutterstock/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: thin
    in_catalog: true
    kin_score: 38.4
    mcp: &id091
      status: unknown
    slug: sitefinity-cms
    status: profiled
    tags: &id092
    - .NET
    - Content Management
    - Headless CMS
    - REST
    url: /providers/sitefinity-cms/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.5
    band: emerging
    in_catalog: true
    kin_score: 18.0
    mcp: &id093
      source: https://github.com/sketch-hq/sketch-mcp-bundle
      status: verified
    slug: sketch
    status: profiled
    tags: &id094
    - Collaboration
    - Design
    - Prototyping
    - Workspace
    url: /providers/sketch/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id095
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id096
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 14.8
    band: emerging
    in_catalog: true
    kin_score: 20.0
    mcp: &id097
      status: unchecked
    slug: stibo-systems
    status: profiled
    tags: &id098
    - Company
    - Data Governance
    - MDM
    - Product Information Management
    url: /providers/stibo-systems/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.0
    band: strong
    in_catalog: true
    kin_score: 55.1
    mcp: &id099
      source: https://github.com/storyblok/mcp-server
      status: verified
    slug: storyblok
    status: profiled
    tags: &id100
    - CMS
    - Content Delivery
    - Content Management
    - Headless CMS
    url: /providers/storyblok/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: thin
    in_catalog: true
    kin_score: 35.0
    mcp: &id101
      status: unknown
    slug: syndigo
    status: profiled
    tags: &id102
    - Company
    - Data
    - Master Data Management
    - Product Information Management
    url: /providers/syndigo/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 52.6
    band: developing
    in_catalog: true
    kin_score: 39.4
    mcp: &id103
      status: none
    slug: unsplash
    status: profiled
    tags: &id104
    - Image
    - Photography
    - Photos
    - Stock Photos
    url: /providers/unsplash/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id105
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id106
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: developing
    in_catalog: true
    kin_score: 50.0
    mcp: &id107
      source: https://github.com/wrike/datahub-mcp
      status: verified
    slug: wrike
    status: profiled
    tags: &id108
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/wrike/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id109
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id110
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 30.9
    mcp: &id111
      status: unchecked
    slug: ziflow
    status: profiled
    tags: &id112
    - Collaboration
    - Company
    - Creative
    - Proofing
    url: /providers/ziflow/
  layer: domain
  name: Ziflow
  provider: ziflow
  says: lists Ziflow as an integration
  source: https://cloudinary.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/digital-asset-management/cloudinary/
providers:
- agent_band: agent-ready
  agent_readiness: 62.9
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id001
  name: Adobe
  slug: adobe
  status: profiled
  tags: *id002
  url: /providers/adobe/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 18.0
  mcp: *id003
  name: Adobe Commerce
  slug: adobe-commerce
  status: profiled
  tags: *id004
  url: /providers/adobe-commerce/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: developing
  in_catalog: true
  kin_score: 53.7
  mcp: *id005
  name: Adobe Creative Cloud
  slug: adobe-creative-cloud
  status: profiled
  tags: *id006
  url: /providers/adobe-creative-cloud/
- agent_band: agent-ready
  agent_readiness: 58.0
  band: exemplar
  in_catalog: true
  kin_score: 70.2
  mcp: *id007
  name: Adobe Workfront
  slug: workfront
  status: profiled
  tags: *id008
  url: /providers/workfront/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: developing
  in_catalog: true
  kin_score: 42.3
  mcp: *id009
  name: Akeneo
  slug: akeneo
  status: profiled
  tags: *id010
  url: /providers/akeneo/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id011
  name: Amazon Web Services
  slug: amazon-web-services
  status: profiled
  tags: *id012
  url: /providers/amazon-web-services/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id013
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id014
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id015
  name: Braze
  slug: braze
  status: profiled
  tags: *id016
  url: /providers/braze/
- agent_band: agent-native
  agent_readiness: 62.9
  band: thin
  in_catalog: true
  kin_score: 37.0
  mcp: *id017
  name: Builder.io
  slug: builder-io
  status: profiled
  tags: *id018
  url: /providers/builder-io/
- agent_band: agent-native
  agent_readiness: 70.0
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id019
  name: Canva
  slug: canva
  status: profiled
  tags: *id020
  url: /providers/canva/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: strong
  in_catalog: true
  kin_score: 64.0
  mcp: *id021
  name: CI HUB
  slug: ci-hub
  status: profiled
  tags: *id022
  url: /providers/ci-hub/
- agent_band: agent-ready
  agent_readiness: 35.5
  band: strong
  in_catalog: true
  kin_score: 61.5
  mcp: *id023
  name: commercetools
  slug: commercetools
  status: profiled
  tags: *id024
  url: /providers/commercetools/
- agent_band: agent-ready
  agent_readiness: 55.2
  band: developing
  in_catalog: true
  kin_score: 43.9
  mcp: *id025
  name: Contentful
  slug: contentful
  status: profiled
  tags: *id026
  url: /providers/contentful/
- agent_band: agent-ready
  agent_readiness: 46.7
  band: thin
  in_catalog: true
  kin_score: 33.0
  mcp: *id027
  name: Contentsquare
  slug: contentsquare
  status: profiled
  tags: *id028
  url: /providers/contentsquare/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id029
  name: Contentstack
  slug: contentstack
  status: profiled
  tags: *id030
  url: /providers/contentstack/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id031
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id032
  url: /providers/dropbox/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: developing
  in_catalog: true
  kin_score: 53.9
  mcp: *id033
  name: Drupal
  slug: drupal
  status: profiled
  tags: *id034
  url: /providers/drupal/
- agent_band: agent-ready
  agent_readiness: 59.2
  band: exemplar
  in_catalog: true
  kin_score: 75.1
  mcp: *id035
  name: Figma
  slug: figma
  status: profiled
  tags: *id036
  url: /providers/figma/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id037
  name: Getty Images
  slug: getty-images
  status: profiled
  tags: *id038
  url: /providers/getty-images/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id039
  name: Google Cloud CDN
  slug: google-cloud-cdn
  status: profiled
  tags: *id040
  url: /providers/google-cloud-cdn/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id041
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id042
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 33.9
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id043
  name: Google Cloud Translation API
  slug: google-translate
  status: profiled
  tags: *id044
  url: /providers/google-translate/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id045
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id046
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id047
  name: Google Workspace
  slug: google-workspace
  status: profiled
  tags: *id048
  url: /providers/google-workspace/
- agent_band: agent-ready
  agent_readiness: 48.8
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id049
  name: Hootsuite
  slug: hootsuite
  status: profiled
  tags: *id050
  url: /providers/hootsuite/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id051
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id052
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: emerging
  in_catalog: true
  kin_score: 21.7
  mcp: *id053
  name: Hygraph
  slug: hygraph
  status: profiled
  tags: *id054
  url: /providers/hygraph/
- agent_band: agent-aware
  agent_readiness: 20.6
  band: thin
  in_catalog: true
  kin_score: 28.4
  mcp: *id055
  name: iStock
  slug: istock
  status: profiled
  tags: *id056
  url: /providers/istock/
- agent_band: agent-native
  agent_readiness: 58.7
  band: exemplar
  in_catalog: true
  kin_score: 78.1
  mcp: *id057
  name: Klaviyo
  slug: klaviyo
  status: profiled
  tags: *id058
  url: /providers/klaviyo/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: thin
  in_catalog: true
  kin_score: 29.9
  mcp: *id059
  name: Kontent AI
  slug: kontent-ai
  status: profiled
  tags: *id060
  url: /providers/kontent-ai/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id061
  name: Magnolia
  slug: magnolia
  status: queued for profiling
  tags: *id062
  url: null
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id063
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id064
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id065
  name: Make
  slug: make
  status: profiled
  tags: *id066
  url: /providers/make/
- agent_band: agent-ready
  agent_readiness: 30.4
  band: strong
  in_catalog: true
  kin_score: 57.2
  mcp: *id067
  name: Marketo
  slug: marketo
  status: profiled
  tags: *id068
  url: /providers/marketo/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id069
  name: Microsoft 365
  slug: microsoft-365
  status: profiled
  tags: *id070
  url: /providers/microsoft-365/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: thin
  in_catalog: true
  kin_score: 32.2
  mcp: *id071
  name: monday.com
  slug: monday-com
  status: profiled
  tags: *id072
  url: /providers/monday-com/
- agent_band: agent-ready
  agent_readiness: 35.7
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id073
  name: n8n
  slug: n8n
  status: profiled
  tags: *id074
  url: /providers/n8n/
- agent_band: agent-ready
  agent_readiness: 58.9
  band: exemplar
  in_catalog: true
  kin_score: 72.2
  mcp: *id075
  name: Netlify
  slug: netlify
  status: profiled
  tags: *id076
  url: /providers/netlify/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id077
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id078
  url: /providers/openai/
- agent_band: agent-aware
  agent_readiness: 21.7
  band: thin
  in_catalog: true
  kin_score: 35.0
  mcp: *id079
  name: Salesforce Commerce Cloud
  slug: salesforce-commerce-cloud
  status: profiled
  tags: *id080
  url: /providers/salesforce-commerce-cloud/
- agent_band: agent-ready
  agent_readiness: 52.3
  band: exemplar
  in_catalog: true
  kin_score: 77.6
  mcp: *id081
  name: Salesforce Marketing Cloud
  slug: salesforce-marketing-cloud
  status: profiled
  tags: *id082
  url: /providers/salesforce-marketing-cloud/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: strong
  in_catalog: true
  kin_score: 56.6
  mcp: *id083
  name: Sanity
  slug: sanity
  status: profiled
  tags: *id084
  url: /providers/sanity/
- agent_band: agent-aware
  agent_readiness: 22.8
  band: developing
  in_catalog: true
  kin_score: 47.1
  mcp: *id085
  name: SAP Commerce Cloud
  slug: sap-commerce-cloud
  status: profiled
  tags: *id086
  url: /providers/sap-commerce-cloud/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id087
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id088
  url: /providers/shopify/
- agent_band: agent-ready
  agent_readiness: 29.6
  band: developing
  in_catalog: true
  kin_score: 42.6
  mcp: *id089
  name: Shutterstock
  slug: shutterstock
  status: profiled
  tags: *id090
  url: /providers/shutterstock/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: thin
  in_catalog: true
  kin_score: 38.4
  mcp: *id091
  name: Sitefinity CMS
  slug: sitefinity-cms
  status: profiled
  tags: *id092
  url: /providers/sitefinity-cms/
- agent_band: human-only
  agent_readiness: 3.5
  band: emerging
  in_catalog: true
  kin_score: 18.0
  mcp: *id093
  name: Sketch
  slug: sketch
  status: profiled
  tags: *id094
  url: /providers/sketch/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id095
  name: Slack
  slug: slack
  status: profiled
  tags: *id096
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 14.8
  band: emerging
  in_catalog: true
  kin_score: 20.0
  mcp: *id097
  name: Stibo Systems
  slug: stibo-systems
  status: profiled
  tags: *id098
  url: /providers/stibo-systems/
- agent_band: agent-ready
  agent_readiness: 38.0
  band: strong
  in_catalog: true
  kin_score: 55.1
  mcp: *id099
  name: Storyblok
  slug: storyblok
  status: profiled
  tags: *id100
  url: /providers/storyblok/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: thin
  in_catalog: true
  kin_score: 35.0
  mcp: *id101
  name: Syndigo
  slug: syndigo
  status: profiled
  tags: *id102
  url: /providers/syndigo/
- agent_band: agent-ready
  agent_readiness: 52.6
  band: developing
  in_catalog: true
  kin_score: 39.4
  mcp: *id103
  name: Unsplash
  slug: unsplash
  status: profiled
  tags: *id104
  url: /providers/unsplash/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id105
  name: WordPress
  slug: wordpress
  status: profiled
  tags: *id106
  url: /providers/wordpress/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id107
  name: Wrike
  slug: wrike
  status: profiled
  tags: *id108
  url: /providers/wrike/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id109
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id110
  url: /providers/zapier/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 30.9
  mcp: *id111
  name: Ziflow
  slug: ziflow
  status: profiled
  tags: *id112
  url: /providers/ziflow/
siblings:
- name: Bynder
  rows: 71
  url: /applications/digital-asset-management/bynder/
- name: Canto
  rows: 33
  url: /applications/digital-asset-management/canto/
- name: Frontify
  rows: 55
  url: /applications/digital-asset-management/frontify/
- name: Phraseanet
  rows: 10
  url: /applications/digital-asset-management/phraseanet/
- name: ResourceSpace
  rows: 15
  url: /applications/digital-asset-management/resourcespace/
sitemap: true
title: 'Cloudinary: Digital Asset Management reference app'
---
