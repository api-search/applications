---
app: Buffer
app_slug: buffer
app_url: https://buffer.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Dropbox
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
  - Evergreen Content Poster
  - Nelio Content
  - WordPress
  - WriteStack
  url: /capabilities/content-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: domain
  name: Design & Creative Editing
  providers:
  - Canva
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: Turbo EA
  id: BC-4010.70
  key: distribution-content-syndication
  layer: domain
  name: Distribution Content Syndication
  providers:
  - Feedly
  - Quuu
  url: /capabilities/distribution-content-syndication/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-913
  key: AE-913
  layer: domain
  name: Link Shortening & Link-in-Bio
  providers:
  - Bitly
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-170.60
  key: AE-170.60
  layer: domain
  name: News & Publishing
  providers:
  - Substack
  url: /capabilities/news-publishing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: domain
  name: Photo & Image Libraries
  providers:
  - Unsplash
  url: /capabilities/photo-image-libraries/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.30.20
  key: AE-170.30.20
  layer: domain
  name: Photo Sharing
  providers:
  - Google Photos
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: domain
  name: Reviews & Social Proof
  providers:
  - Google Business Profile
  url: /capabilities/reviews-social-proof/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - Bluesky
  - Facebook
  - Instagram
  - LinkedIn
  - Mastodon
  - Pinterest
  - Threads
  - TikTok
  - X (Twitter)
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.10
  key: AE-170.10
  layer: domain
  name: Video Platforms
  providers:
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210.50
  key: feature-flag-management
  layer: common
  name: Feature Flag Management
  providers:
  - Split
  url: /capabilities/feature-flag-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: common
  name: Hosted LLM Inference
  providers:
  - Anthropic (Claude)
  - OpenAI
  - Perplexity
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Segment
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.70
  key: AE-150.70
  layer: common
  name: Realtime Messaging
  providers:
  - Pusher
  url: /capabilities/realtime-messaging/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - IFTTT
  - Make
  - Microsoft Power Automate
  - n8n
  - Raycast
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-905
  key: AE-905
  layer: agent
  name: IDEs & AI Coding Assistants
  providers:
  - Cursor
  url: /capabilities/engineering-productivity-management/
  via_parent: Engineering Productivity Management
category:
  id: social-media-management
  name: Social Media Management & Scheduling
  url: /applications/social-media-management/
counts:
  declared: 35
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/org.buffer.android/latest/
- route: integrations page
  url: https://buffer.com/integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id049
      status: none
    slug: pusher
    status: profiled
    tags: &id050
    - Pub/Sub
    - Push Notifications
    - Real-Time
    - WebSocket
    url: /providers/pusher/
  layer: common
  name: Pusher
  provider: pusher
  says: ships the Pusher SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/org.buffer.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 43.8
    mcp: &id055
      status: none
    slug: segment
    status: profiled
    tags: &id056
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Segment
  provider: segment
  says: ships the Segment SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/org.buffer.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id057
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id058
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/org.buffer.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id059
      status: none
    slug: split
    status: profiled
    tags: &id060
    - Experimentation
    - Feature Flags
    - Feature Management
    - Rollouts
    url: /providers/split/
  layer: common
  name: Split
  provider: split
  says: ships the Split SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/org.buffer.android/latest/
  tier: observed
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
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 87.5
    mcp: &id001
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id002
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: common
  name: Anthropic (Claude)
  provider: anthropic
  says: lists Anthropic (Claude) as an integration
  source: https://buffer.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.4
    band: exemplar
    in_catalog: true
    kin_score: 73.7
    mcp: &id003
      source: https://dev.bitly.com/bitly-mcp/
      status: verified
    slug: bitly
    status: profiled
    tags: &id004
    - Analytics
    - Links
    - QR Codes
    - URL Shorteners
    url: /providers/bitly/
  layer: domain
  name: Bitly
  provider: bitly
  says: lists Bitly as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 26.2
    band: developing
    in_catalog: true
    kin_score: 45.1
    mcp: &id005
      status: none
    slug: bluesky
    status: profiled
    tags: &id006
    - At-Protocol
    - Decentralized
    - Federated
    - Open Source
    url: /providers/bluesky/
  layer: domain
  name: Bluesky
  provider: bluesky
  says: lists Bluesky as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 71.4
    band: exemplar
    in_catalog: true
    kin_score: 79.9
    mcp: &id007
      source: https://www.canva.dev/docs/mcp/
      status: verified
    slug: canva
    status: profiled
    tags: &id008
    - Application
    - Automation
    - Brand Management
    - Collaboration
    url: /providers/canva/
  layer: domain
  name: Canva
  provider: canva
  says: lists Canva as an integration
  source: https://buffer.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-905
    key: AE-905
    name: IDEs & AI Coding Assistants
    url: /capabilities/engineering-productivity-management/
    via_parent: Engineering Productivity Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.6
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id009
      status: none
    slug: cursor
    status: profiled
    tags: &id010
    - Agents
    - Artificial Intelligence
    - Code Editor
    - Developer Tools
    url: /providers/cursor/
  layer: agent
  name: Cursor
  provider: cursor
  says: lists Cursor as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 45.8
    band: developing
    in_catalog: true
    kin_score: 47.9
    mcp: &id011
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id012
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: domain
  name: Dropbox
  provider: dropbox
  says: lists Dropbox as an integration
  source: https://buffer.com/integrations
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 16.6
    mcp: &id013
      status: unknown
    slug: evergreen-content-poster
    status: profiled
    tags: &id014
    - Company
    - ESG
    - Employee Recognition
    - Software-as-a-Service
    url: /providers/evergreen-content-poster/
  layer: domain
  name: Evergreen Content Poster
  provider: evergreen-content-poster
  says: lists Evergreen Content Poster as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id015
      status: none
    slug: facebook
    status: profiled
    tags: &id016
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: lists Facebook as an integration
  source: https://buffer.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010.70
    key: distribution-content-syndication
    name: Distribution Content Syndication
    url: /capabilities/distribution-content-syndication/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 65.3
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id017
      status: none
    slug: feedly
    status: profiled
    tags: &id018
    - Content Aggregation
    - Cybersecurity
    - RSS
    - Threat Intelligence
    url: /providers/feedly/
  layer: domain
  name: Feedly
  provider: feedly
  says: lists Feedly as an integration
  source: https://buffer.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id019
      status: none
    slug: google-business-profile
    status: profiled
    tags: &id020
    - Business Profiles
    - Google
    - Local Business
    - Location
    url: /providers/google-business-profile/
  layer: domain
  name: Google Business Profile
  provider: google-business-profile
  says: lists Google Business Profile as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 44.3
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id021
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id022
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: domain
  name: Google Drive
  provider: google-drive
  says: lists Google Drive as an integration
  source: https://buffer.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.20
    key: AE-170.30.20
    name: Photo Sharing
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id023
      status: none
    slug: google-photos
    status: profiled
    tags: &id024
    - Albums
    - Google
    - Image
    - Media
    url: /providers/google-photos/
  layer: domain
  name: Google Photos
  provider: google-photos
  says: lists Google Photos as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 43.3
    band: emerging
    in_catalog: true
    kin_score: 25.0
    mcp: &id025
      source: https://github.com/IFTTT/ifttt-plugins
      status: verified
    slug: ifttt
    status: profiled
    tags: &id026
    - Automation
    - No-Code
    - Webhook
    - iPaaS
    url: /providers/ifttt/
  layer: common
  name: IFTTT
  provider: ifttt
  says: lists IFTTT as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 38.9
    band: exemplar
    in_catalog: true
    kin_score: 69.0
    mcp: &id027
      status: none
    slug: instagram
    status: profiled
    tags: &id028
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
  layer: domain
  name: Instagram
  provider: instagram
  says: lists Instagram as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 47.4
    band: exemplar
    in_catalog: true
    kin_score: 76.4
    mcp: &id029
      status: none
    slug: linkedin
    status: profiled
    tags: &id030
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: lists LinkedIn as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 43.9
    band: developing
    in_catalog: true
    kin_score: 43.5
    mcp: &id031
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id032
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 22.5
    band: thin
    in_catalog: true
    kin_score: 26.5
    mcp: &id033
      status: none
    slug: mastodon
    status: profiled
    tags: &id034
    - Open Source
    - Real-Time
    - Social
    - Social Network
    url: /providers/mastodon/
  layer: domain
  name: Mastodon
  provider: mastodon
  says: lists Mastodon as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 25.2
    band: developing
    in_catalog: true
    kin_score: 48.3
    mcp: &id035
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id036
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: domain
  name: Microsoft OneDrive
  provider: microsoft-onedrive
  says: lists Microsoft OneDrive as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 34.2
    band: strong
    in_catalog: true
    kin_score: 64.2
    mcp: &id037
      status: none
    slug: microsoft-power-automate
    status: profiled
    tags: &id038
    - Automation
    - Business Process
    - Integration
    - Low-Code
    url: /providers/microsoft-power-automate/
  layer: common
  name: Microsoft Power Automate
  provider: microsoft-power-automate
  says: lists Microsoft Power Automate as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 36.4
    band: exemplar
    in_catalog: true
    kin_score: 71.3
    mcp: &id039
      source: https://docs.n8n.io/advanced-ai/accessing-n8n-mcp-server/
      status: verified
    slug: n8n
    status: profiled
    tags: &id040
    - Agents
    - Artificial Intelligence
    - Integration
    - Workflows
    url: /providers/n8n/
  layer: common
  name: n8n
  provider: n8n
  says: lists n8n as an integration
  source: https://buffer.com/integrations
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
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 1.3
    mcp: &id041
      status: unknown
    slug: nelio-content
    status: profiled
    tags: &id042
    - Company
    url: /providers/nelio-content/
  layer: domain
  name: Nelio Content
  provider: nelio-content
  says: lists Nelio Content as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id043
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id044
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: common
  name: OpenAI
  provider: openai
  says: lists OpenAI as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 67.7
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id045
      source: https://github.com/perplexityai/modelcontextprotocol
      status: verified
    slug: perplexity
    status: profiled
    tags: &id046
    - Agents
    - Artificial Intelligence
    - LLM
    - Search
    url: /providers/perplexity/
  layer: common
  name: Perplexity
  provider: perplexity
  says: lists Perplexity as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 38.4
    band: developing
    in_catalog: true
    kin_score: 49.4
    mcp: &id047
      source: https://developers.pinterest.com/about-pinterest-mcp/
      status: verified
    slug: pinterest
    status: profiled
    tags: &id048
    - Image
    - Social
    - Social Media
    - Video
    url: /providers/pinterest/
  layer: domain
  name: Pinterest
  provider: pinterest
  says: lists Pinterest as an integration
  source: https://buffer.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4010.70
    key: distribution-content-syndication
    name: Distribution Content Syndication
    url: /capabilities/distribution-content-syndication/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.9
    band: emerging
    in_catalog: true
    kin_score: 12.2
    mcp: &id051
      status: unknown
    slug: quuu
    status: profiled
    tags: &id052
    - Artificial Intelligence
    - Automation
    - Company
    - Social Media
    url: /providers/quuu/
  layer: domain
  name: Quuu
  provider: quuu
  says: lists Quuu as an integration
  source: https://buffer.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 13.6
    band: emerging
    in_catalog: true
    kin_score: 25.7
    mcp: &id053
      status: none
    slug: raycast
    status: profiled
    tags: &id054
    - Extensions
    - Launcher
    - Productivity
    - SDK
    url: /providers/raycast/
  layer: common
  name: Raycast
  provider: raycast
  says: lists Raycast as an integration
  source: https://buffer.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.60
    key: AE-170.60
    name: News & Publishing
    url: /capabilities/news-publishing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.7
    band: developing
    in_catalog: true
    kin_score: 43.6
    mcp: &id061
      source: https://mcp.substack.com/api/v1/mcp
      status: verified
    slug: substack
    status: profiled
    tags: &id062
    - Creator Economy
    - Newsletters
    - Publishing
    - Subscription
    url: /providers/substack/
  layer: domain
  name: Substack
  provider: substack
  says: lists Substack as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 28.4
    band: developing
    in_catalog: true
    kin_score: 43.1
    mcp: &id063
      status: none
    slug: threads-api
    status: profiled
    tags: &id064
    - Meta
    - Publishing
    - Social
    - Social Network
    url: /providers/threads-api/
  layer: domain
  name: Threads
  provider: threads-api
  says: lists Threads as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 41.0
    mcp: &id065
      status: none
    slug: tiktok
    status: profiled
    tags: &id066
    - Advertising
    - Commerce
    - Content
    - TikTok
    url: /providers/tiktok/
  layer: domain
  name: TikTok
  provider: tiktok
  says: lists TikTok as an integration
  source: https://buffer.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.1
    band: developing
    in_catalog: true
    kin_score: 40.2
    mcp: &id067
      status: none
    slug: unsplash
    status: profiled
    tags: &id068
    - Image
    - Photography
    - Photos
    - Stock Photos
    url: /providers/unsplash/
  layer: domain
  name: Unsplash
  provider: unsplash
  says: lists Unsplash as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 31.4
    band: developing
    in_catalog: true
    kin_score: 46.0
    mcp: &id069
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id070
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
  layer: domain
  name: WordPress
  provider: wordpress
  says: lists WordPress as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 39.1
    band: thin
    in_catalog: true
    kin_score: 35.1
    mcp: &id071
      source: https://www.writestack.io/mcp
      status: verified
    slug: writestack
    status: profiled
    tags: &id072
    - Analytics
    - Company
    - Growth
    - Substack
    url: /providers/writestack/
  layer: domain
  name: WriteStack
  provider: writestack
  says: lists WriteStack as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 61.2
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id073
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id074
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X (Twitter)
  provider: x
  says: lists X (Twitter) as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 43.4
    band: strong
    in_catalog: true
    kin_score: 62.6
    mcp: &id075
      status: none
    slug: youtube
    status: profiled
    tags: &id076
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: lists YouTube as an integration
  source: https://buffer.com/integrations
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
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id077
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id078
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://buffer.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/social-media-management/buffer/
providers:
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 87.5
  mcp: *id001
  name: Anthropic (Claude)
  slug: anthropic
  status: profiled
  tags: *id002
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 59.4
  band: exemplar
  in_catalog: true
  kin_score: 73.7
  mcp: *id003
  name: Bitly
  slug: bitly
  status: profiled
  tags: *id004
  url: /providers/bitly/
- agent_band: agent-aware
  agent_readiness: 26.2
  band: developing
  in_catalog: true
  kin_score: 45.1
  mcp: *id005
  name: Bluesky
  slug: bluesky
  status: profiled
  tags: *id006
  url: /providers/bluesky/
- agent_band: agent-native
  agent_readiness: 71.4
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id007
  name: Canva
  slug: canva
  status: profiled
  tags: *id008
  url: /providers/canva/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id009
  name: Cursor
  slug: cursor
  status: profiled
  tags: *id010
  url: /providers/cursor/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id011
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id012
  url: /providers/dropbox/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.6
  mcp: *id013
  name: Evergreen Content Poster
  slug: evergreen-content-poster
  status: profiled
  tags: *id014
  url: /providers/evergreen-content-poster/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id015
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id016
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 65.3
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id017
  name: Feedly
  slug: feedly
  status: profiled
  tags: *id018
  url: /providers/feedly/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id019
  name: Google Business Profile
  slug: google-business-profile
  status: profiled
  tags: *id020
  url: /providers/google-business-profile/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id021
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id022
  url: /providers/google-drive/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id023
  name: Google Photos
  slug: google-photos
  status: profiled
  tags: *id024
  url: /providers/google-photos/
- agent_band: agent-ready
  agent_readiness: 43.3
  band: emerging
  in_catalog: true
  kin_score: 25.0
  mcp: *id025
  name: IFTTT
  slug: ifttt
  status: profiled
  tags: *id026
  url: /providers/ifttt/
- agent_band: agent-ready
  agent_readiness: 38.9
  band: exemplar
  in_catalog: true
  kin_score: 69.0
  mcp: *id027
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id028
  url: /providers/instagram/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: exemplar
  in_catalog: true
  kin_score: 76.4
  mcp: *id029
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id030
  url: /providers/linkedin/
- agent_band: agent-ready
  agent_readiness: 43.9
  band: developing
  in_catalog: true
  kin_score: 43.5
  mcp: *id031
  name: Make
  slug: make
  status: profiled
  tags: *id032
  url: /providers/make/
- agent_band: agent-aware
  agent_readiness: 22.5
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id033
  name: Mastodon
  slug: mastodon
  status: profiled
  tags: *id034
  url: /providers/mastodon/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 48.3
  mcp: *id035
  name: Microsoft OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id036
  url: /providers/microsoft-onedrive/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 64.2
  mcp: *id037
  name: Microsoft Power Automate
  slug: microsoft-power-automate
  status: profiled
  tags: *id038
  url: /providers/microsoft-power-automate/
- agent_band: agent-ready
  agent_readiness: 36.4
  band: exemplar
  in_catalog: true
  kin_score: 71.3
  mcp: *id039
  name: n8n
  slug: n8n
  status: profiled
  tags: *id040
  url: /providers/n8n/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 1.3
  mcp: *id041
  name: Nelio Content
  slug: nelio-content
  status: profiled
  tags: *id042
  url: /providers/nelio-content/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id043
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id044
  url: /providers/openai/
- agent_band: agent-native
  agent_readiness: 67.7
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id045
  name: Perplexity
  slug: perplexity
  status: profiled
  tags: *id046
  url: /providers/perplexity/
- agent_band: agent-ready
  agent_readiness: 38.4
  band: developing
  in_catalog: true
  kin_score: 49.4
  mcp: *id047
  name: Pinterest
  slug: pinterest
  status: profiled
  tags: *id048
  url: /providers/pinterest/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id049
  name: Pusher
  slug: pusher
  status: profiled
  tags: *id050
  url: /providers/pusher/
- agent_band: human-only
  agent_readiness: 3.9
  band: emerging
  in_catalog: true
  kin_score: 12.2
  mcp: *id051
  name: Quuu
  slug: quuu
  status: profiled
  tags: *id052
  url: /providers/quuu/
- agent_band: agent-aware
  agent_readiness: 13.6
  band: emerging
  in_catalog: true
  kin_score: 25.7
  mcp: *id053
  name: Raycast
  slug: raycast
  status: profiled
  tags: *id054
  url: /providers/raycast/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 43.8
  mcp: *id055
  name: Segment
  slug: segment
  status: profiled
  tags: *id056
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id057
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id058
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id059
  name: Split
  slug: split
  status: profiled
  tags: *id060
  url: /providers/split/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: developing
  in_catalog: true
  kin_score: 43.6
  mcp: *id061
  name: Substack
  slug: substack
  status: profiled
  tags: *id062
  url: /providers/substack/
- agent_band: agent-aware
  agent_readiness: 28.4
  band: developing
  in_catalog: true
  kin_score: 43.1
  mcp: *id063
  name: Threads
  slug: threads-api
  status: profiled
  tags: *id064
  url: /providers/threads-api/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 41.0
  mcp: *id065
  name: TikTok
  slug: tiktok
  status: profiled
  tags: *id066
  url: /providers/tiktok/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: developing
  in_catalog: true
  kin_score: 40.2
  mcp: *id067
  name: Unsplash
  slug: unsplash
  status: profiled
  tags: *id068
  url: /providers/unsplash/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: developing
  in_catalog: true
  kin_score: 46.0
  mcp: *id069
  name: WordPress
  slug: wordpress
  status: profiled
  tags: *id070
  url: /providers/wordpress/
- agent_band: agent-ready
  agent_readiness: 39.1
  band: thin
  in_catalog: true
  kin_score: 35.1
  mcp: *id071
  name: WriteStack
  slug: writestack
  status: profiled
  tags: *id072
  url: /providers/writestack/
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id073
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id074
  url: /providers/x/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: strong
  in_catalog: true
  kin_score: 62.6
  mcp: *id075
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id076
  url: /providers/youtube/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id077
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id078
  url: /providers/zapier/
siblings:
- name: Hootsuite
  rows: 42
  url: /applications/social-media-management/hootsuite/
- name: Mixpost
  rows: 5
  url: /applications/social-media-management/mixpost/
- name: Planoly
  rows: 8
  url: /applications/social-media-management/planoly/
- name: Postiz
  rows: 57
  url: /applications/social-media-management/postiz/
- name: Socioboard
  rows: 22
  url: /applications/social-media-management/socioboard/
- name: Sprout Social
  rows: 43
  url: /applications/social-media-management/sprout-social/
sitemap: true
title: 'Buffer: Social Media Management & Scheduling reference app'
---
