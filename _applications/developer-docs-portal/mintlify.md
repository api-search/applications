---
app: Mintlify
app_slug: mintlify
app_url: https://www.mintlify.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - Azure Repos
  - Bitbucket
  - GitHub
  - GitLab
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Google Docs
  - Google Drive
  - OneDrive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-160.50
  key: AE-160.50
  layer: common
  name: Consent & Preferences
  providers:
  - Osano
  - Transcend
  url: /capabilities/consent-preferences/
  via_parent: null
- attribution: Turbo EA
  id: BC-3740.30
  key: content-delivery-network-operations
  layer: common
  name: Content Delivery Network Operations
  providers:
  - Amazon CloudFront
  - Cloudflare
  - Vercel
  url: /capabilities/content-delivery-network-operations/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.70
  key: content-management
  layer: common
  name: Content Management
  providers:
  - Contentful
  url: /capabilities/content-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: common
  name: Customer Data Management
  providers:
  - Hightouch
  - Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Front
  - Intercom
  - Plain
  - Pylon
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.30.10
  key: AE-230.30.10
  layer: common
  name: Data Enrichment
  providers:
  - Clearbit
  url: /capabilities/company-contact-data/
  via_parent: Company & Contact Data
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: common
  name: Design & Creative Editing
  providers:
  - Figma
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-927
  key: AE-927
  layer: common
  name: Domain Registration & Managed DNS
  providers:
  - Amazon Route 53
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4210.50
  key: feature-flag-management
  layer: common
  name: Feature Flag Management
  providers:
  - LaunchDarkly
  url: /capabilities/feature-flag-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830
  key: knowledge-management
  layer: common
  name: Knowledge Management
  providers:
  - Notion
  - OneNote
  url: /capabilities/knowledge-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.30
  key: knowledge-sharing-collaboration-management
  layer: common
  name: Knowledge Sharing & Collaboration Management
  providers:
  - Confluence
  url: /capabilities/knowledge-sharing-collaboration-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  - Outlook
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Adobe Analytics
  - Amplitude
  - Fathom
  - Google Analytics
  - Heap
  - Hotjar
  - LogRocket
  - Microsoft Clarity
  - Mixpanel
  - Pirsch
  - Plausible
  - PostHog
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - Jira
  - Linear
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: common
  name: Spreadsheets & No-Code Databases
  providers:
  - Excel
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: common
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
category:
  id: developer-docs-portal
  name: Developer Docs & API Portals
  url: /applications/developer-docs-portal/
counts:
  declared: 49
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://www.mintlify.com/docs/llms.txt
- route: integrations page
  url: https://www.mintlify.com/docs/automations/integrations.md
- route: integrations page
  url: https://www.mintlify.com/docs/integrations/analytics/overview.md
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 60.3
    band: strong
    in_catalog: true
    kin_score: 65.0
    mcp: &id001
      status: none
    slug: adobe-analytics
    status: profiled
    tags: &id002
    - Adobe
    - Analytics
    - Business Intelligence
    - Customer Intelligence
    url: /providers/adobe-analytics/
  layer: common
  name: Adobe Analytics
  provider: adobe-analytics
  says: lists Adobe Analytics as an integration
  source: https://www.mintlify.com/docs/integrations/analytics/adobe.md
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
    agent_readiness: 37.6
    band: exemplar
    in_catalog: true
    kin_score: 79.6
    mcp: &id003
      status: none
    slug: cloudfront
    status: profiled
    tags: &id004
    - Amazon Web Services
    - CDN
    - Caching
    - Content Delivery
    url: /providers/cloudfront/
  layer: common
  name: Amazon CloudFront
  provider: cloudfront
  says: lists Amazon CloudFront as an integration
  source: https://www.mintlify.com/docs/deploy/route53-cloudfront.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-927
    key: AE-927
    name: Domain Registration & Managed DNS
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.6
    band: exemplar
    in_catalog: true
    kin_score: 69.6
    mcp: &id005
      status: none
    slug: amazon-route-53
    status: profiled
    tags: &id006
    - Amazon Web Services
    - DNS
    - Domain Registration
    - Health Checks
    url: /providers/amazon-route-53/
  layer: common
  name: Amazon Route 53
  provider: amazon-route-53
  says: lists Amazon Route 53 as an integration
  source: https://www.mintlify.com/docs/deploy/route53-cloudfront.md
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
    agent_readiness: 56.9
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id007
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id008
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: lists Amplitude as an integration
  source: https://www.mintlify.com/docs/integrations/analytics/amplitude.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.7
    band: exemplar
    in_catalog: true
    kin_score: 81.9
    mcp: &id009
      source: https://github.com/microsoft/azure-devops-mcp
      status: verified
    slug: microsoft-azure-devops
    status: profiled
    tags: &id010
    - Agile
    - CI/CD
    - DevOps
    - Developer Tools
    url: /providers/microsoft-azure-devops/
  layer: domain
  name: Azure Repos
  provider: microsoft-azure-devops
  says: lists Azure Repos as an integration
  source: https://www.mintlify.com/docs/deploy/azure-repos.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: exemplar
    in_catalog: true
    kin_score: 71.9
    mcp: &id011
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: bitbucket
    status: profiled
    tags: &id012
    - Atlassian
    - CI/CD
    - Code Collaboration
    - Code Review
    url: /providers/bitbucket/
  layer: domain
  name: Bitbucket
  provider: bitbucket
  says: lists Bitbucket as an integration
  source: https://www.mintlify.com/docs/deploy/bitbucket.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.10
    key: AE-230.30.10
    name: Data Enrichment
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: strong
    in_catalog: true
    kin_score: 59.3
    mcp: &id013
      status: none
    slug: clearbit
    status: profiled
    tags: &id014
    - B2B
    - Data Enrichment
    - Reveal
    - Sales Intelligence
    url: /providers/clearbit/
  layer: common
  name: Clearbit
  provider: clearbit
  says: lists Clearbit as an integration
  source: https://www.mintlify.com/docs/integrations/analytics/clearbit.md
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
    agent_band: agent-native
    agent_readiness: 69.4
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id015
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id016
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
  layer: common
  name: Cloudflare
  provider: cloudflare
  says: lists Cloudflare as an integration
  source: https://www.mintlify.com/docs/deploy/cloudflare.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 55.8
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id017
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: confluence
    status: profiled
    tags: &id018
    - Collaboration
    - Content Management
    - Documentation
    - Knowledge Base
    url: /providers/confluence/
  layer: common
  name: Confluence
  provider: confluence
  says: lists Confluence as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: content-management
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
    mcp: &id019
      source: https://github.com/contentful/contentful-mcp-server
      status: verified
    slug: contentful
    status: profiled
    tags: &id020
    - CMS
    - Content
    - Content Management
    - Headless CMS
    url: /providers/contentful/
  layer: common
  name: Contentful
  provider: contentful
  says: lists Contentful as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.0
    band: strong
    in_catalog: true
    kin_score: 55.8
    mcp: &id021
      status: none
    slug: microsoft-excel
    status: profiled
    tags: &id022
    - Automation
    - Data Analysis
    - Microsoft
    - Microsoft 365
    url: /providers/microsoft-excel/
  layer: common
  name: Excel
  provider: microsoft-excel
  says: lists Excel as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
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
    agent_readiness: 30.3
    band: developing
    in_catalog: true
    kin_score: 47.7
    mcp: &id023
      status: none
    slug: fathom
    status: profiled
    tags: &id024
    - Analytics
    - GDPR
    - Privacy
    - Website Analytics
    url: /providers/fathom/
  layer: common
  name: Fathom
  provider: fathom
  says: lists Fathom as an integration
  source: https://www.mintlify.com/docs/integrations/analytics/fathom.md
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
    mcp: &id025
      source: https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server
      status: verified
    slug: figma
    status: profiled
    tags: &id026
    - Collaboration
    - Design
    - Graphics
    - Interfaces
    url: /providers/figma/
  layer: common
  name: Figma
  provider: figma
  says: lists Figma as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: developing
    in_catalog: true
    kin_score: 53.6
    mcp: &id027
      source: https://dev.frontapp.com/docs/mcp
      status: documented
    slug: front
    status: profiled
    tags: &id028
    - Customer Operations
    - Customer Service
    - Email
    - Inbox
    url: /providers/front/
  layer: common
  name: Front
  provider: front
  says: lists Front as an integration
  source: https://www.mintlify.com/docs/integrations/support/front.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id029
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id030
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://www.mintlify.com/docs/deploy/github.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id031
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id032
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: lists GitLab as an integration
  source: https://www.mintlify.com/docs/deploy/gitlab.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.2
    band: exemplar
    in_catalog: true
    kin_score: 66.8
    mcp: &id033
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id034
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: common
  name: Gmail
  provider: google-gmail
  says: lists Gmail as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
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
    mcp: &id035
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id036
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://www.mintlify.com/docs/integrations/analytics/google-analytics.md
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
    agent_readiness: 40.3
    band: exemplar
    in_catalog: true
    kin_score: 67.2
    mcp: &id037
      source: https://docs.cloud.google.com/mcp/supported-products
      status: verified
    slug: google-docs
    status: profiled
    tags: &id038
    - Collaboration
    - Documents
    - Google Workspace
    - Productivity
    url: /providers/google-docs/
  layer: common
  name: Google Docs
  provider: google-docs
  says: lists Google Docs as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
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
    mcp: &id039
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id040
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: common
  name: Google Drive
  provider: google-drive
  says: lists Google Drive as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id041
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id042
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: lists Google Tag Manager as an integration
  source: https://www.mintlify.com/docs/integrations/analytics/google-tag-manager.md
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
    agent_band: agent-aware
    agent_readiness: 26.3
    band: developing
    in_catalog: true
    kin_score: 40.6
    mcp: &id043
      status: unknown
    slug: heap
    status: profiled
    tags: &id044
    - Analytics
    - Autocapture
    - Digital Analytics
    - Product Analytics
    url: /providers/heap/
  layer: common
  name: Heap
  provider: heap
  says: lists Heap as an integration
  source: https://www.mintlify.com/docs/integrations/analytics/heap.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.8
    band: exemplar
    in_catalog: true
    kin_score: 66.9
    mcp: &id045
      source: https://hightouch.com/docs/ai-integrations/mcp
      status: documented
    slug: hightouch
    status: profiled
    tags: &id046
    - Audience Management
    - CDP
    - Data Activation
    - Reverse ETL
    url: /providers/hightouch/
  layer: common
  name: Hightouch
  provider: hightouch
  says: lists Hightouch as an integration
  source: https://www.mintlify.com/docs/integrations/analytics/hightouch.md
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
    agent_band: agent-aware
    agent_readiness: 27.3
    band: emerging
    in_catalog: true
    kin_score: 25.5
    mcp: &id047
      status: none
    slug: hotjar
    status: profiled
    tags: &id048
    - Analytics
    - Personalization
    - Surveys
    - Tracking
    url: /providers/hotjar/
  layer: common
  name: Hotjar
  provider: hotjar
  says: lists Hotjar as an integration
  source: https://www.mintlify.com/docs/integrations/analytics/hotjar.md
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
    mcp: &id049
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id050
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: common
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.5
    band: developing
    in_catalog: true
    kin_score: 51.0
    mcp: &id051
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id052
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: common
  name: Intercom
  provider: intercom
  says: lists Intercom as an integration
  source: https://www.mintlify.com/docs/integrations/support/intercom.md
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
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id053
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id054
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: common
  name: Jira
  provider: jira
  says: lists Jira as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.7
    band: exemplar
    in_catalog: true
    kin_score: 84.5
    mcp: &id055
      source: https://launchdarkly.com/docs/home/getting-started/mcp
      status: verified
    slug: launchdarkly
    status: profiled
    tags: &id056
    - Experimentation
    - Feature Flags
    - Feature Management
    - Observability
    url: /providers/launchdarkly/
  layer: common
  name: LaunchDarkly
  provider: launchdarkly
  says: lists LaunchDarkly as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
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
    agent_readiness: 35.2
    band: developing
    in_catalog: true
    kin_score: 39.6
    mcp: &id057
      source: https://linear.app/docs/mcp
      status: verified
    slug: linear-app
    status: profiled
    tags: &id058
    - Issue Tracking
    - Productivity
    - Project Management
    - Software-as-a-Service
    url: /providers/linear-app/
  layer: common
  name: Linear
  provider: linear-app
  says: lists Linear as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
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
    agent_readiness: 44.1
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id059
      source: https://mcp.logrocket.com/mcp
      status: verified
    slug: logrocket
    status: profiled
    tags: &id060
    - Frontend Monitoring
    - Logging
    - Product Analytics
    - Session Replay
    url: /providers/logrocket/
  layer: common
  name: LogRocket
  provider: logrocket
  says: lists LogRocket as an integration
  source: https://www.mintlify.com/docs/integrations/analytics/logrocket.md
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
    agent_readiness: 29.9
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id061
      source: https://github.com/microsoft/clarity-mcp-server
      status: verified
    slug: microsoft-clarity
    status: profiled
    tags: &id062
    - Analytics
    - Heatmaps
    - Session Recording
    - Web Analytics
    url: /providers/microsoft-clarity/
  layer: common
  name: Microsoft Clarity
  provider: microsoft-clarity
  says: lists Microsoft Clarity as an integration
  source: https://www.mintlify.com/docs/integrations/analytics/clarity.md
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
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id063
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id064
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: lists Mixpanel as an integration
  source: https://www.mintlify.com/docs/integrations/analytics/mixpanel.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id065
      source: https://developers.notion.com/docs/mcp
      status: verified
    slug: notion
    status: profiled
    tags: &id066
    - Collaboration
    - Database
    - Ideas
    - Notes
    url: /providers/notion/
  layer: common
  name: Notion
  provider: notion
  says: lists Notion as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
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
    mcp: &id067
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id068
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: common
  name: OneDrive
  provider: microsoft-onedrive
  says: lists OneDrive as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.7
    band: strong
    in_catalog: true
    kin_score: 57.0
    mcp: &id069
      status: none
    slug: microsoft-onenote
    status: profiled
    tags: &id070
    - Microsoft
    - Microsoft 365
    - Notebooks
    - Notes
    url: /providers/microsoft-onenote/
  layer: common
  name: OneNote
  provider: microsoft-onenote
  says: lists OneNote as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.50
    key: AE-160.50
    name: Consent & Preferences
    url: /capabilities/consent-preferences/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: strong
    in_catalog: true
    kin_score: 54.3
    mcp: &id071
      status: none
    slug: osano
    status: profiled
    tags: &id072
    - Company
    - Compliance
    - Consent Management
    - Privacy
    url: /providers/osano/
  layer: common
  name: Osano
  provider: osano
  says: lists Osano as an integration
  source: https://www.mintlify.com/docs/integrations/privacy/osano.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 70.8
    mcp: &id073
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id074
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: common
  name: Outlook
  provider: microsoft-outlook
  says: lists Outlook as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
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
    agent_readiness: 31.7
    band: exemplar
    in_catalog: true
    kin_score: 67.9
    mcp: &id075
      source: https://docs.pirsch.io/integrations/mcp
      status: verified
    slug: pirsch
    status: profiled
    tags: &id076
    - Analytics
    - GDPR
    - Privacy
    - Web Analytics
    url: /providers/pirsch/
  layer: common
  name: Pirsch
  provider: pirsch
  says: lists Pirsch as an integration
  source: https://www.mintlify.com/docs/integrations/analytics/pirsch.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.3
    band: strong
    in_catalog: true
    kin_score: 61.8
    mcp: &id077
      source: https://github.com/team-plain/cursor-plugin-mcp
      status: verified
    slug: plain
    status: profiled
    tags: &id078
    - Company
    - Customer Service
    - Help Desk
    - Support
    url: /providers/plain/
  layer: common
  name: Plain
  provider: plain
  says: lists Plain as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
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
    agent_band: agent-aware
    agent_readiness: 22.6
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id079
      status: none
    slug: plausible
    status: profiled
    tags: &id080
    - Analytics
    - Cookie-Free
    - Event Tracking
    - GDPR
    url: /providers/plausible/
  layer: common
  name: Plausible
  provider: plausible
  says: lists Plausible as an integration
  source: https://www.mintlify.com/docs/integrations/analytics/plausible.md
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
    agent_readiness: 56.2
    band: strong
    in_catalog: true
    kin_score: 57.9
    mcp: &id081
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id082
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: PostHog
  provider: posthog
  says: lists PostHog as an integration
  source: https://www.mintlify.com/docs/integrations/analytics/posthog.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 32.3
    mcp: &id083
      status: unknown
    slug: pylon
    status: profiled
    tags: &id084
    - Customer Operations
    - Customer Service
    - Knowledge Base
    - Ticketing
    url: /providers/pylon/
  layer: common
  name: Pylon
  provider: pylon
  says: lists Pylon as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
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
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id085
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id086
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id087
      status: none
    slug: segment
    status: profiled
    tags: &id088
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Segment
  provider: segment
  says: lists Segment as an integration
  source: https://www.mintlify.com/docs/integrations/analytics/segment.md
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
    mcp: &id089
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id090
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.mintlify.com/docs/agent/slack.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id091
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id092
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.50
    key: AE-160.50
    name: Consent & Preferences
    url: /capabilities/consent-preferences/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id093
      status: unchecked
    slug: transcend
    status: queued for profiling
    tags: &id094 []
    url: null
  layer: common
  name: Transcend
  provider: transcend
  says: lists Transcend as an integration
  source: https://www.mintlify.com/docs/integrations/privacy/transcend.md
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
    agent_readiness: 50.0
    band: strong
    in_catalog: true
    kin_score: 63.1
    mcp: &id095
      source: https://vercel.com/docs/mcp/vercel-mcp
      status: verified
    slug: vercel
    status: profiled
    tags: &id096
    - AI Gateway
    - Gateways
    - Observability
    - Webhook
    url: /providers/vercel/
  layer: common
  name: Vercel
  provider: vercel
  says: lists Vercel as an integration
  source: https://www.mintlify.com/docs/deploy/vercel.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id097
      status: none
    slug: zendesk
    status: profiled
    tags: &id098
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: common
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://www.mintlify.com/docs/automations/integrations.md
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/developer-docs-portal/mintlify/
providers:
- agent_band: agent-native
  agent_readiness: 60.3
  band: strong
  in_catalog: true
  kin_score: 65.0
  mcp: *id001
  name: Adobe Analytics
  slug: adobe-analytics
  status: profiled
  tags: *id002
  url: /providers/adobe-analytics/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 79.6
  mcp: *id003
  name: Amazon CloudFront
  slug: cloudfront
  status: profiled
  tags: *id004
  url: /providers/cloudfront/
- agent_band: agent-ready
  agent_readiness: 35.6
  band: exemplar
  in_catalog: true
  kin_score: 69.6
  mcp: *id005
  name: Amazon Route 53
  slug: amazon-route-53
  status: profiled
  tags: *id006
  url: /providers/amazon-route-53/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id007
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id008
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 37.7
  band: exemplar
  in_catalog: true
  kin_score: 81.9
  mcp: *id009
  name: Azure Repos
  slug: microsoft-azure-devops
  status: profiled
  tags: *id010
  url: /providers/microsoft-azure-devops/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: exemplar
  in_catalog: true
  kin_score: 71.9
  mcp: *id011
  name: Bitbucket
  slug: bitbucket
  status: profiled
  tags: *id012
  url: /providers/bitbucket/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: strong
  in_catalog: true
  kin_score: 59.3
  mcp: *id013
  name: Clearbit
  slug: clearbit
  status: profiled
  tags: *id014
  url: /providers/clearbit/
- agent_band: agent-native
  agent_readiness: 69.4
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id015
  name: Cloudflare
  slug: cloudflare
  status: profiled
  tags: *id016
  url: /providers/cloudflare/
- agent_band: agent-ready
  agent_readiness: 55.8
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id017
  name: Confluence
  slug: confluence
  status: profiled
  tags: *id018
  url: /providers/confluence/
- agent_band: agent-ready
  agent_readiness: 55.2
  band: developing
  in_catalog: true
  kin_score: 43.9
  mcp: *id019
  name: Contentful
  slug: contentful
  status: profiled
  tags: *id020
  url: /providers/contentful/
- agent_band: agent-ready
  agent_readiness: 29.0
  band: strong
  in_catalog: true
  kin_score: 55.8
  mcp: *id021
  name: Excel
  slug: microsoft-excel
  status: profiled
  tags: *id022
  url: /providers/microsoft-excel/
- agent_band: agent-ready
  agent_readiness: 30.3
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id023
  name: Fathom
  slug: fathom
  status: profiled
  tags: *id024
  url: /providers/fathom/
- agent_band: agent-ready
  agent_readiness: 59.2
  band: exemplar
  in_catalog: true
  kin_score: 75.1
  mcp: *id025
  name: Figma
  slug: figma
  status: profiled
  tags: *id026
  url: /providers/figma/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: developing
  in_catalog: true
  kin_score: 53.6
  mcp: *id027
  name: Front
  slug: front
  status: profiled
  tags: *id028
  url: /providers/front/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id029
  name: GitHub
  slug: github
  status: profiled
  tags: *id030
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id031
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id032
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id033
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id034
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id035
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id036
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 40.3
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id037
  name: Google Docs
  slug: google-docs
  status: profiled
  tags: *id038
  url: /providers/google-docs/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id039
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id040
  url: /providers/google-drive/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id041
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id042
  url: /providers/google-tag-manager/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: developing
  in_catalog: true
  kin_score: 40.6
  mcp: *id043
  name: Heap
  slug: heap
  status: profiled
  tags: *id044
  url: /providers/heap/
- agent_band: agent-ready
  agent_readiness: 62.8
  band: exemplar
  in_catalog: true
  kin_score: 66.9
  mcp: *id045
  name: Hightouch
  slug: hightouch
  status: profiled
  tags: *id046
  url: /providers/hightouch/
- agent_band: agent-aware
  agent_readiness: 27.3
  band: emerging
  in_catalog: true
  kin_score: 25.5
  mcp: *id047
  name: Hotjar
  slug: hotjar
  status: profiled
  tags: *id048
  url: /providers/hotjar/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id049
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id050
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id051
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id052
  url: /providers/intercom/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id053
  name: Jira
  slug: jira
  status: profiled
  tags: *id054
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 59.7
  band: exemplar
  in_catalog: true
  kin_score: 84.5
  mcp: *id055
  name: LaunchDarkly
  slug: launchdarkly
  status: profiled
  tags: *id056
  url: /providers/launchdarkly/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: developing
  in_catalog: true
  kin_score: 39.6
  mcp: *id057
  name: Linear
  slug: linear-app
  status: profiled
  tags: *id058
  url: /providers/linear-app/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id059
  name: LogRocket
  slug: logrocket
  status: profiled
  tags: *id060
  url: /providers/logrocket/
- agent_band: agent-ready
  agent_readiness: 29.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id061
  name: Microsoft Clarity
  slug: microsoft-clarity
  status: profiled
  tags: *id062
  url: /providers/microsoft-clarity/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id063
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id064
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id065
  name: Notion
  slug: notion
  status: profiled
  tags: *id066
  url: /providers/notion/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id067
  name: OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id068
  url: /providers/microsoft-onedrive/
- agent_band: agent-ready
  agent_readiness: 30.7
  band: strong
  in_catalog: true
  kin_score: 57.0
  mcp: *id069
  name: OneNote
  slug: microsoft-onenote
  status: profiled
  tags: *id070
  url: /providers/microsoft-onenote/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: strong
  in_catalog: true
  kin_score: 54.3
  mcp: *id071
  name: Osano
  slug: osano
  status: profiled
  tags: *id072
  url: /providers/osano/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 70.8
  mcp: *id073
  name: Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id074
  url: /providers/microsoft-outlook/
- agent_band: agent-ready
  agent_readiness: 31.7
  band: exemplar
  in_catalog: true
  kin_score: 67.9
  mcp: *id075
  name: Pirsch
  slug: pirsch
  status: profiled
  tags: *id076
  url: /providers/pirsch/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: strong
  in_catalog: true
  kin_score: 61.8
  mcp: *id077
  name: Plain
  slug: plain
  status: profiled
  tags: *id078
  url: /providers/plain/
- agent_band: agent-aware
  agent_readiness: 22.6
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id079
  name: Plausible
  slug: plausible
  status: profiled
  tags: *id080
  url: /providers/plausible/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id081
  name: PostHog
  slug: posthog
  status: profiled
  tags: *id082
  url: /providers/posthog/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id083
  name: Pylon
  slug: pylon
  status: profiled
  tags: *id084
  url: /providers/pylon/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id085
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id086
  url: /providers/salesforce/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id087
  name: Segment
  slug: segment
  status: profiled
  tags: *id088
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id089
  name: Slack
  slug: slack
  status: profiled
  tags: *id090
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id091
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id092
  url: /providers/stripe/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id093
  name: Transcend
  slug: transcend
  status: queued for profiling
  tags: *id094
  url: null
- agent_band: agent-ready
  agent_readiness: 50.0
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id095
  name: Vercel
  slug: vercel
  status: profiled
  tags: *id096
  url: /providers/vercel/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id097
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id098
  url: /providers/zendesk/
siblings:
- name: Backstage
  rows: 37
  url: /applications/developer-docs-portal/backstage/
- name: Docusaurus
  rows: 7
  url: /applications/developer-docs-portal/docusaurus/
- name: GitBook
  rows: 56
  url: /applications/developer-docs-portal/gitbook/
- name: ReadMe
  rows: 17
  url: /applications/developer-docs-portal/readme/
- name: Redocly
  rows: 16
  url: /applications/developer-docs-portal/redocly/
- name: Zudoku
  rows: 10
  url: /applications/developer-docs-portal/zudoku/
sitemap: true
title: 'Mintlify: Developer Docs & API Portals reference app'
---
