---
app: Canto
app_slug: canto
app_url: https://www.canto.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Box
  - Dropbox
  - Egnyte
  - Google Drive
  - Microsoft OneDrive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: domain
  name: Content Management
  providers:
  - Contentstack
  - Drupal
  - TYPO3
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
  - Adobe Photoshop
  - Canva
  - Figma
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Mailchimp
  - Salesforce Marketing Cloud
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-917
  key: AE-917
  layer: domain
  name: Enterprise Content & Document Management
  providers:
  - Microsoft SharePoint
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: domain
  name: Internal Communications Management
  providers:
  - Microsoft Teams
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2370
  key: product-information-management
  layer: domain
  name: Product Information Management
  providers:
  - Akeneo
  url: /capabilities/product-information-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: domain
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - Adobe Workfront
  - Asana
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
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - Facebook
  - LinkedIn
  - Pinterest
  - X (Twitter)
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.10
  key: AE-170.10
  layer: domain
  name: Video Platforms
  providers:
  - Vimeo
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: domain
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: digital-asset-management
  name: Digital Asset Management
  url: /applications/digital-asset-management/
counts:
  declared: 33
  observed: 0
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.5
    band: developing
    in_catalog: true
    kin_score: 49.7
    mcp: &id001
      status: unknown
    slug: adobe-photoshop
    status: profiled
    tags: &id002
    - Artificial Intelligence
    - Creative Cloud
    - Image Editing
    - Photoshop
    url: /providers/adobe-photoshop/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.0
    band: exemplar
    in_catalog: true
    kin_score: 70.2
    mcp: &id003
      source: https://experienceleague.adobe.com/en/docs/workfront/using/basics/workfront-mcp-server/workfront-mcp-server-overview
      status: verified
    slug: workfront
    status: profiled
    tags: &id004
    - Company
    - Marketing Operations
    - Project Management
    - Work Management
    url: /providers/workfront/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.7
    band: developing
    in_catalog: true
    kin_score: 42.3
    mcp: &id005
      source: https://api.akeneo.com/mcp/overview.html
      status: verified
    slug: akeneo
    status: profiled
    tags: &id006
    - Catalog Management
    - Commerce
    - Product Data
    - Product Information Management
    url: /providers/akeneo/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 55.3
    band: exemplar
    in_catalog: true
    kin_score: 72.5
    mcp: &id007
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id008
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 56.6
    band: strong
    in_catalog: true
    kin_score: 63.0
    mcp: &id009
      source: https://developer.box.com/guides/box-mcp/
      status: verified
    slug: box
    status: profiled
    tags: &id010
    - Cloud Storage
    - Collaboration
    - Content Management
    - Documents
    url: /providers/box/
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
  facts:
    agent_band: agent-native
    agent_readiness: 70.0
    band: exemplar
    in_catalog: true
    kin_score: 87.3
    mcp: &id011
      source: https://www.canva.dev/docs/mcp/
      status: verified
    slug: canva
    status: profiled
    tags: &id012
    - Application
    - Automation
    - Brand Management
    - Collaboration
    url: /providers/canva/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id013
      source: https://registry.npmjs.org/@contentstack/mcp
      status: verified
    slug: contentstack
    status: profiled
    tags: &id014
    - Content Delivery
    - Content Management
    - Digital Experience
    - Headless CMS
    url: /providers/contentstack/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id015
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id016
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.3
    band: developing
    in_catalog: true
    kin_score: 53.9
    mcp: &id017
      status: none
    slug: drupal
    status: profiled
    tags: &id018
    - CMS
    - Content Management
    - JSON:API
    - Open Source
    url: /providers/drupal/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: thin
    in_catalog: true
    kin_score: 29.5
    mcp: &id019
      source: https://github.com/egnyte/egnyte-mcp-server
      status: verified
    slug: egnyte
    status: profiled
    tags: &id020
    - Content Collaboration
    - Document Management
    - Enterprise Storage
    - File Sharing
    url: /providers/egnyte/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id021
      status: none
    slug: facebook
    status: profiled
    tags: &id022
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 59.2
    band: exemplar
    in_catalog: true
    kin_score: 75.1
    mcp: &id023
      source: https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server
      status: verified
    slug: figma
    status: profiled
    tags: &id024
    - Collaboration
    - Design
    - Graphics
    - Interfaces
    url: /providers/figma/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id025
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id026
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 73.2
    mcp: &id027
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id028
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 48.8
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id029
      status: none
    slug: hootsuite
    status: profiled
    tags: &id030
    - Content Scheduling
    - Marketing
    - Social Media
    - Social Media Management
    url: /providers/hootsuite/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id031
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id032
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 46.5
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id033
      status: none
    slug: linkedin
    status: profiled
    tags: &id034
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id035
      status: none
    slug: mailchimp
    status: profiled
    tags: &id036
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id037
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id038
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 32.3
    band: strong
    in_catalog: true
    kin_score: 60.9
    mcp: &id039
      source: https://github.com/microsoft/mcp
      status: verified
    slug: sharepoint
    status: profiled
    tags: &id040
    - Collaboration
    - Document Management
    - Enterprise Content Management
    - Intranet
    url: /providers/sharepoint/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id041
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id042
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.3
    band: thin
    in_catalog: true
    kin_score: 32.2
    mcp: &id043
      source: https://github.com/mondaycom/mcp
      status: verified
    slug: monday-com
    status: profiled
    tags: &id044
    - Automation
    - CRM
    - GraphQL
    - Work Management
    url: /providers/monday-com/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: developing
    in_catalog: true
    kin_score: 47.7
    mcp: &id045
      source: https://developers.pinterest.com/about-pinterest-mcp/
      status: verified
    slug: pinterest
    status: profiled
    tags: &id046
    - Image
    - Social
    - Social Media
    - Video
    url: /providers/pinterest/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 52.3
    band: exemplar
    in_catalog: true
    kin_score: 77.6
    mcp: &id047
      status: none
    slug: salesforce-marketing-cloud
    status: profiled
    tags: &id048
    - Automation
    - Content Management
    - Customer Journey
    - Digital Marketing
    url: /providers/salesforce-marketing-cloud/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id049
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id050
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id051
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id052
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.1
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id053
      status: none
    slug: typo3
    status: profiled
    tags: &id054
    - CMS
    - Content Management
    - Enterprise
    - PHP
    url: /providers/typo3/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: thin
    in_catalog: true
    kin_score: 37.6
    mcp: &id055
      source: https://developer.vimeo.com/api/mcp-server
      status: documented
    slug: vimeo
    status: profiled
    tags: &id056
    - Live Streaming
    - Streaming
    - Video
    - Video Hosting
    url: /providers/vimeo/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id057
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id058
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: developing
    in_catalog: true
    kin_score: 50.0
    mcp: &id059
      source: https://github.com/wrike/datahub-mcp
      status: verified
    slug: wrike
    status: profiled
    tags: &id060
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/wrike/
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
  facts:
    agent_band: agent-native
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id061
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id062
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.4
    band: strong
    in_catalog: true
    kin_score: 65.4
    mcp: &id063
      status: none
    slug: youtube
    status: profiled
    tags: &id064
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id065
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id066
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: domain
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.canto.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/digital-asset-management/canto/
providers:
- agent_band: agent-ready
  agent_readiness: 44.5
  band: developing
  in_catalog: true
  kin_score: 49.7
  mcp: *id001
  name: Adobe Photoshop
  slug: adobe-photoshop
  status: profiled
  tags: *id002
  url: /providers/adobe-photoshop/
- agent_band: agent-ready
  agent_readiness: 58.0
  band: exemplar
  in_catalog: true
  kin_score: 70.2
  mcp: *id003
  name: Adobe Workfront
  slug: workfront
  status: profiled
  tags: *id004
  url: /providers/workfront/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: developing
  in_catalog: true
  kin_score: 42.3
  mcp: *id005
  name: Akeneo
  slug: akeneo
  status: profiled
  tags: *id006
  url: /providers/akeneo/
- agent_band: agent-ready
  agent_readiness: 55.3
  band: exemplar
  in_catalog: true
  kin_score: 72.5
  mcp: *id007
  name: Asana
  slug: asana
  status: profiled
  tags: *id008
  url: /providers/asana/
- agent_band: agent-ready
  agent_readiness: 56.6
  band: strong
  in_catalog: true
  kin_score: 63.0
  mcp: *id009
  name: Box
  slug: box
  status: profiled
  tags: *id010
  url: /providers/box/
- agent_band: agent-native
  agent_readiness: 70.0
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id011
  name: Canva
  slug: canva
  status: profiled
  tags: *id012
  url: /providers/canva/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id013
  name: Contentstack
  slug: contentstack
  status: profiled
  tags: *id014
  url: /providers/contentstack/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id015
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id016
  url: /providers/dropbox/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: developing
  in_catalog: true
  kin_score: 53.9
  mcp: *id017
  name: Drupal
  slug: drupal
  status: profiled
  tags: *id018
  url: /providers/drupal/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id019
  name: Egnyte
  slug: egnyte
  status: profiled
  tags: *id020
  url: /providers/egnyte/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id021
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id022
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 59.2
  band: exemplar
  in_catalog: true
  kin_score: 75.1
  mcp: *id023
  name: Figma
  slug: figma
  status: profiled
  tags: *id024
  url: /providers/figma/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id025
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id026
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id027
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id028
  url: /providers/google-drive/
- agent_band: agent-ready
  agent_readiness: 48.8
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id029
  name: Hootsuite
  slug: hootsuite
  status: profiled
  tags: *id030
  url: /providers/hootsuite/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id031
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id032
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id033
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id034
  url: /providers/linkedin/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id035
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id036
  url: /providers/mailchimp/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id037
  name: Microsoft OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id038
  url: /providers/microsoft-onedrive/
- agent_band: agent-ready
  agent_readiness: 32.3
  band: strong
  in_catalog: true
  kin_score: 60.9
  mcp: *id039
  name: Microsoft SharePoint
  slug: sharepoint
  status: profiled
  tags: *id040
  url: /providers/sharepoint/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id041
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id042
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: thin
  in_catalog: true
  kin_score: 32.2
  mcp: *id043
  name: monday.com
  slug: monday-com
  status: profiled
  tags: *id044
  url: /providers/monday-com/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id045
  name: Pinterest
  slug: pinterest
  status: profiled
  tags: *id046
  url: /providers/pinterest/
- agent_band: agent-ready
  agent_readiness: 52.3
  band: exemplar
  in_catalog: true
  kin_score: 77.6
  mcp: *id047
  name: Salesforce Marketing Cloud
  slug: salesforce-marketing-cloud
  status: profiled
  tags: *id048
  url: /providers/salesforce-marketing-cloud/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id049
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id050
  url: /providers/shopify/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id051
  name: Slack
  slug: slack
  status: profiled
  tags: *id052
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 20.1
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id053
  name: TYPO3
  slug: typo3
  status: profiled
  tags: *id054
  url: /providers/typo3/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id055
  name: Vimeo
  slug: vimeo
  status: profiled
  tags: *id056
  url: /providers/vimeo/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id057
  name: WordPress
  slug: wordpress
  status: profiled
  tags: *id058
  url: /providers/wordpress/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id059
  name: Wrike
  slug: wrike
  status: profiled
  tags: *id060
  url: /providers/wrike/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id061
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id062
  url: /providers/x/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: strong
  in_catalog: true
  kin_score: 65.4
  mcp: *id063
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id064
  url: /providers/youtube/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id065
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id066
  url: /providers/zapier/
siblings:
- name: Bynder
  rows: 71
  url: /applications/digital-asset-management/bynder/
- name: Cloudinary
  rows: 56
  url: /applications/digital-asset-management/cloudinary/
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
title: 'Canto: Digital Asset Management reference app'
---
