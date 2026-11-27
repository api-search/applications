---
app: Sprout Social
app_slug: sprout-social
app_url: https://sproutsocial.com/
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
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-400.70
  key: content-marketing-management
  layer: domain
  name: Content Marketing Management
  providers:
  - Opal
  - Optimizely
  url: /capabilities/content-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: domain
  name: Design & Creative Editing
  providers:
  - Adobe Express
  - Canva
  url: /capabilities/design-creative-editing/
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
- attribution: Turbo EA
  id: BC-3710
  key: media-asset-management
  layer: domain
  name: Media Asset Management
  providers:
  - Adobe Experience Manager
  - Bynder
  url: /capabilities/media-asset-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: domain
  name: Reviews & Social Proof
  providers:
  - Apple
  - Glassdoor
  - Google Play (reviews)
  - Tripadvisor
  - Trustpilot
  - Yelp
  url: /capabilities/reviews-social-proof/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.70
  key: AE-140.70
  layer: domain
  name: Social & Creator Commerce
  providers:
  - Shopify
  - WooCommerce
  url: /capabilities/social-creator-commerce/
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
  - Pinterest
  - Reddit
  - Snapchat
  - Threads
  - TikTok
  - Tumblr
  - X (Twitter)
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: domain
  name: Team Chat Bridging
  providers:
  - Microsoft Teams
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-170.10
  key: AE-170.10
  layer: domain
  name: Video Platforms
  providers:
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: domain
  name: WhatsApp & OTT Messaging
  providers:
  - WhatsApp
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Tableau
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Microsoft Dynamics 365
  - Salesforce
  - Salesforce Agentforce Sales (Sales Cloud)
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.50
  key: marketing-operations-management
  layer: common
  name: Marketing Operations Management
  providers:
  - Marketo
  - Salesforce Agentforce Marketing / Marketing Intelligence
  url: /capabilities/marketing-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase
  - Mixpanel
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: social-media-management
  name: Social Media Management & Scheduling
  url: /applications/social-media-management/
counts:
  declared: 41
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.sproutsocial.android/latest/
- route: integrations page
  url: https://sproutsocial.com/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id019
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id020
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.sproutsocial.android/latest/
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
    agent_band: agent-ready
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id041
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id042
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: ships the Mixpanel SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.sproutsocial.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.4
    band: thin
    in_catalog: true
    kin_score: 28.0
    mcp: &id001
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe-experience-manager
    status: profiled
    tags: &id002
    - Content Management
    - Digital Asset Management
    - Enterprise CMS
    - Headless CMS
    url: /providers/adobe-experience-manager/
  layer: domain
  name: Adobe Experience Manager
  provider: adobe-experience-manager
  says: lists Adobe Experience Manager as an integration
  source: https://sproutsocial.com/integrations/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id003
      status: unchecked
    slug: adobe-express
    status: queued for profiling
    tags: &id004 []
    url: null
  layer: domain
  name: Adobe Express
  provider: adobe-express
  says: lists Adobe Express as an integration
  source: https://sproutsocial.com/integrations/
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
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id005
      status: none
    slug: apple
    status: profiled
    tags: &id006
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Apple
  provider: apple
  says: lists Apple as an integration
  source: https://sproutsocial.com/integrations/
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
    agent_readiness: 58.2
    band: exemplar
    in_catalog: true
    kin_score: 73.0
    mcp: &id007
      source: https://dev.bitly.com/bitly-mcp/
      status: verified
    slug: bitly
    status: profiled
    tags: &id008
    - Analytics
    - Links
    - QR Codes
    - URL Shorteners
    url: /providers/bitly/
  layer: domain
  name: Bitly
  provider: bitly
  says: lists Bitly as an integration
  source: https://sproutsocial.com/integrations/
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
    agent_readiness: 25.7
    band: developing
    in_catalog: true
    kin_score: 46.3
    mcp: &id009
      status: none
    slug: bluesky
    status: profiled
    tags: &id010
    - At-Protocol
    - Decentralized
    - Federated
    - Open Source
    url: /providers/bluesky/
  layer: domain
  name: Bluesky
  provider: bluesky
  says: lists Bluesky as an integration
  source: https://sproutsocial.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.9
    band: exemplar
    in_catalog: true
    kin_score: 77.9
    mcp: &id011
      status: none
    slug: bynder
    status: profiled
    tags: &id012
    - Brand Management
    - Content Management
    - Digital Asset Management
    - Marketing
    url: /providers/bynder/
  layer: domain
  name: Bynder
  provider: bynder
  says: lists Bynder as an integration
  source: https://sproutsocial.com/integrations/
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
    mcp: &id013
      source: https://www.canva.dev/docs/mcp/
      status: verified
    slug: canva
    status: profiled
    tags: &id014
    - Application
    - Automation
    - Brand Management
    - Collaboration
    url: /providers/canva/
  layer: domain
  name: Canva
  provider: canva
  says: lists Canva as an integration
  source: https://sproutsocial.com/integrations/
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
  source: https://sproutsocial.com/integrations/
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
    mcp: &id017
      status: none
    slug: facebook
    status: profiled
    tags: &id018
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: lists Facebook as an integration
  source: https://sproutsocial.com/integrations/
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
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 11.4
    mcp: &id021
      status: none
    slug: glassdoor
    status: profiled
    tags: &id022
    - Employer Reviews
    - Job Search
    - Recruiting
    - Salaries
    url: /providers/glassdoor/
  layer: domain
  name: Glassdoor
  provider: glassdoor
  says: lists Glassdoor as an integration
  source: https://sproutsocial.com/integrations/
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
    mcp: &id023
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id024
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://sproutsocial.com/integrations/
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
    mcp: &id025
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id026
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: domain
  name: Google Drive
  provider: google-drive
  says: lists Google Drive as an integration
  source: https://sproutsocial.com/integrations/
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
    agent_band: agent-ready
    agent_readiness: 38.7
    band: developing
    in_catalog: true
    kin_score: 51.3
    mcp: &id027
      status: none
    slug: google-play
    status: profiled
    tags: &id028
    - Android
    - Application
    - Google Play
    - In-App Purchases
    url: /providers/google-play/
  layer: domain
  name: Google Play (reviews)
  provider: google-play
  says: lists Google Play (reviews) as an integration
  source: https://sproutsocial.com/integrations/
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
    mcp: &id029
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id030
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: common
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://sproutsocial.com/integrations/
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
    agent_readiness: 38.6
    band: exemplar
    in_catalog: true
    kin_score: 67.8
    mcp: &id031
      status: none
    slug: instagram
    status: profiled
    tags: &id032
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
  layer: domain
  name: Instagram
  provider: instagram
  says: lists Instagram as an integration
  source: https://sproutsocial.com/integrations/
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
  source: https://sproutsocial.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.50
    key: marketing-operations-management
    name: Marketing Operations Management
    url: /capabilities/marketing-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.4
    band: strong
    in_catalog: true
    kin_score: 57.2
    mcp: &id035
      status: none
    slug: marketo
    status: profiled
    tags: &id036
    - Adobe
    - Automation
    - Marketing
    - Marketing Automation
    url: /providers/marketo/
  layer: common
  name: Marketo
  provider: marketo
  says: lists Marketo as an integration
  source: https://sproutsocial.com/integrations/
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
    agent_readiness: 37.6
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id037
      source: https://github.com/microsoft/Dataverse-MCP
      status: verified
    slug: microsoft-dynamics-365
    status: profiled
    tags: &id038
    - Business Applications
    - CRM
    - Cloud
    - Enterprise
    url: /providers/microsoft-dynamics-365/
  layer: common
  name: Microsoft Dynamics 365
  provider: microsoft-dynamics-365
  says: lists Microsoft Dynamics 365 as an integration
  source: https://sproutsocial.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id039
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id040
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://sproutsocial.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.70
    key: content-marketing-management
    name: Content Marketing Management
    url: /capabilities/content-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.2
    band: developing
    in_catalog: true
    kin_score: 53.0
    mcp: &id043
      source: https://github.com/opalsecurity/opal-mcp
      status: verified
    slug: opal
    status: profiled
    tags: &id044
    - Company
    - Consumer
    - Content Planning
    - Marketing
    url: /providers/opal/
  layer: domain
  name: Opal
  provider: opal
  says: lists Opal as an integration
  source: https://sproutsocial.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.70
    key: content-marketing-management
    name: Content Marketing Management
    url: /capabilities/content-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 61.6
    band: exemplar
    in_catalog: true
    kin_score: 78.1
    mcp: &id045
      source: https://support.optimizely.com/hc/en-us/articles/45320607594893
      status: documented
    slug: optimizely
    status: profiled
    tags: &id046
    - A/B Testing
    - Content Management
    - Customer Data
    - E-Commerce
    url: /providers/optimizely/
  layer: domain
  name: Optimizely
  provider: optimizely
  says: lists Optimizely as an integration
  source: https://sproutsocial.com/integrations/
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
  source: https://sproutsocial.com/integrations/
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
    agent_readiness: 43.0
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id049
      source: https://github.com/reddit/devvit-mcp
      status: verified
    slug: reddit
    status: profiled
    tags: &id050
    - Advertising
    - Community
    - Content
    - Reddit
    url: /providers/reddit/
  layer: domain
  name: Reddit
  provider: reddit
  says: lists Reddit as an integration
  source: https://sproutsocial.com/integrations/
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
    mcp: &id051
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id052
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://sproutsocial.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.50
    key: marketing-operations-management
    name: Marketing Operations Management
    url: /capabilities/marketing-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.3
    band: exemplar
    in_catalog: true
    kin_score: 77.6
    mcp: &id053
      status: none
    slug: salesforce-marketing-cloud
    status: profiled
    tags: &id054
    - Automation
    - Content Management
    - Customer Journey
    - Digital Marketing
    url: /providers/salesforce-marketing-cloud/
  layer: common
  name: Salesforce Agentforce Marketing / Marketing Intelligence
  provider: salesforce-marketing-cloud
  says: lists Salesforce Agentforce Marketing / Marketing Intelligence as an integration
  source: https://sproutsocial.com/integrations/
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
    agent_readiness: 30.9
    band: strong
    in_catalog: true
    kin_score: 56.2
    mcp: &id055
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce-sales-cloud
    status: profiled
    tags: &id056
    - CRM
    - Cloud
    - Customer Management
    - Enterprise
    url: /providers/salesforce-sales-cloud/
  layer: common
  name: Salesforce Agentforce Sales (Sales Cloud)
  provider: salesforce-sales-cloud
  says: lists Salesforce Agentforce Sales (Sales Cloud) as an integration
  source: https://sproutsocial.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.70
    key: AE-140.70
    name: Social & Creator Commerce
    url: /capabilities/social-creator-commerce/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id057
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id058
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://sproutsocial.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id059
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id060
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://sproutsocial.com/integrations/
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
    agent_readiness: 47.1
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id061
      status: none
    slug: snapchat
    status: profiled
    tags: &id062
    - Advertising
    - Augmented Reality
    - Marketing
    - Messaging
    url: /providers/snapchat/
  layer: domain
  name: Snapchat
  provider: snapchat
  says: lists Snapchat as an integration
  source: https://sproutsocial.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 55.0
    band: developing
    in_catalog: true
    kin_score: 49.9
    mcp: &id063
      source: https://github.com/tableau/tableau-mcp
      status: verified
    slug: tableau
    status: profiled
    tags: &id064
    - Analytics
    - Business Intelligence
    - Dashboards
    - Data Visualization
    url: /providers/tableau/
  layer: common
  name: Tableau
  provider: tableau
  says: lists Tableau as an integration
  source: https://sproutsocial.com/integrations/
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
    agent_readiness: 28.3
    band: developing
    in_catalog: true
    kin_score: 43.2
    mcp: &id065
      status: none
    slug: threads-api
    status: profiled
    tags: &id066
    - Meta
    - Publishing
    - Social
    - Social Network
    url: /providers/threads-api/
  layer: domain
  name: Threads
  provider: threads-api
  says: lists Threads as an integration
  source: https://sproutsocial.com/integrations/
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
    agent_readiness: 19.2
    band: developing
    in_catalog: true
    kin_score: 40.5
    mcp: &id067
      status: none
    slug: tiktok
    status: profiled
    tags: &id068
    - Advertising
    - Commerce
    - Content
    - TikTok
    url: /providers/tiktok/
  layer: domain
  name: TikTok
  provider: tiktok
  says: lists TikTok as an integration
  source: https://sproutsocial.com/integrations/
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
    agent_readiness: 23.9
    band: thin
    in_catalog: true
    kin_score: 35.7
    mcp: &id069
      status: none
    slug: tripadvisor
    status: profiled
    tags: &id070
    - Attractions
    - Hospitality
    - Hotels
    - Restaurant
    url: /providers/tripadvisor/
  layer: domain
  name: Tripadvisor
  provider: tripadvisor
  says: lists Tripadvisor as an integration
  source: https://sproutsocial.com/integrations/
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
    agent_readiness: 21.3
    band: developing
    in_catalog: true
    kin_score: 48.2
    mcp: &id071
      status: none
    slug: trustpilot
    status: profiled
    tags: &id072
    - Consumer Reviews
    - Ratings
    - Reviews
    - Trust
    url: /providers/trustpilot/
  layer: domain
  name: Trustpilot
  provider: trustpilot
  says: lists Trustpilot as an integration
  source: https://sproutsocial.com/integrations/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.5
    mcp: &id073
      status: none
    slug: tumblr
    status: profiled
    tags: &id074
    - Public APIs
    - Social
    url: /providers/tumblr/
  layer: domain
  name: Tumblr
  provider: tumblr
  says: lists Tumblr as an integration
  source: https://sproutsocial.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 72.3
    mcp: &id075
      status: none
    slug: whatsapp
    status: profiled
    tags: &id076
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: domain
  name: WhatsApp
  provider: whatsapp
  says: lists WhatsApp as an integration
  source: https://sproutsocial.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.70
    key: AE-140.70
    name: Social & Creator Commerce
    url: /capabilities/social-creator-commerce/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 54.6
    mcp: &id077
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id078
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://sproutsocial.com/integrations/
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
    mcp: &id079
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id080
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X (Twitter)
  provider: x
  says: lists X (Twitter) as an integration
  source: https://sproutsocial.com/integrations/
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
    agent_band: agent-native
    agent_readiness: 46.7
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id081
      source: https://github.com/Yelp/yelp-mcp
      status: verified
    slug: yelp
    status: profiled
    tags: &id082
    - Business Data
    - Local Search
    - Restaurant
    - Reviews
    url: /providers/yelp/
  layer: domain
  name: Yelp
  provider: yelp
  says: lists Yelp as an integration
  source: https://sproutsocial.com/integrations/
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
    mcp: &id083
      status: none
    slug: youtube
    status: profiled
    tags: &id084
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: lists YouTube as an integration
  source: https://sproutsocial.com/integrations/
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
    mcp: &id085
      status: none
    slug: zendesk
    status: profiled
    tags: &id086
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: common
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://sproutsocial.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/social-media-management/sprout-social/
providers:
- agent_band: agent-aware
  agent_readiness: 21.4
  band: thin
  in_catalog: true
  kin_score: 28.0
  mcp: *id001
  name: Adobe Experience Manager
  slug: adobe-experience-manager
  status: profiled
  tags: *id002
  url: /providers/adobe-experience-manager/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: Adobe Express
  slug: adobe-express
  status: queued for profiling
  tags: *id004
  url: null
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id005
  name: Apple
  slug: apple
  status: profiled
  tags: *id006
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 58.2
  band: exemplar
  in_catalog: true
  kin_score: 73.0
  mcp: *id007
  name: Bitly
  slug: bitly
  status: profiled
  tags: *id008
  url: /providers/bitly/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: developing
  in_catalog: true
  kin_score: 46.3
  mcp: *id009
  name: Bluesky
  slug: bluesky
  status: profiled
  tags: *id010
  url: /providers/bluesky/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: exemplar
  in_catalog: true
  kin_score: 77.9
  mcp: *id011
  name: Bynder
  slug: bynder
  status: profiled
  tags: *id012
  url: /providers/bynder/
- agent_band: agent-native
  agent_readiness: 70.0
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id013
  name: Canva
  slug: canva
  status: profiled
  tags: *id014
  url: /providers/canva/
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
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id017
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id018
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id019
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id020
  url: /providers/google-firebase/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 11.4
  mcp: *id021
  name: Glassdoor
  slug: glassdoor
  status: profiled
  tags: *id022
  url: /providers/glassdoor/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id023
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id024
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id025
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id026
  url: /providers/google-drive/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: developing
  in_catalog: true
  kin_score: 51.3
  mcp: *id027
  name: Google Play (reviews)
  slug: google-play
  status: profiled
  tags: *id028
  url: /providers/google-play/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id029
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id030
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 38.6
  band: exemplar
  in_catalog: true
  kin_score: 67.8
  mcp: *id031
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id032
  url: /providers/instagram/
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
  agent_readiness: 30.4
  band: strong
  in_catalog: true
  kin_score: 57.2
  mcp: *id035
  name: Marketo
  slug: marketo
  status: profiled
  tags: *id036
  url: /providers/marketo/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id037
  name: Microsoft Dynamics 365
  slug: microsoft-dynamics-365
  status: profiled
  tags: *id038
  url: /providers/microsoft-dynamics-365/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id039
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id040
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id041
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id042
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 30.2
  band: developing
  in_catalog: true
  kin_score: 53.0
  mcp: *id043
  name: Opal
  slug: opal
  status: profiled
  tags: *id044
  url: /providers/opal/
- agent_band: agent-ready
  agent_readiness: 61.6
  band: exemplar
  in_catalog: true
  kin_score: 78.1
  mcp: *id045
  name: Optimizely
  slug: optimizely
  status: profiled
  tags: *id046
  url: /providers/optimizely/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id047
  name: Pinterest
  slug: pinterest
  status: profiled
  tags: *id048
  url: /providers/pinterest/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id049
  name: Reddit
  slug: reddit
  status: profiled
  tags: *id050
  url: /providers/reddit/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id051
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id052
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 52.3
  band: exemplar
  in_catalog: true
  kin_score: 77.6
  mcp: *id053
  name: Salesforce Agentforce Marketing / Marketing Intelligence
  slug: salesforce-marketing-cloud
  status: profiled
  tags: *id054
  url: /providers/salesforce-marketing-cloud/
- agent_band: agent-ready
  agent_readiness: 30.9
  band: strong
  in_catalog: true
  kin_score: 56.2
  mcp: *id055
  name: Salesforce Agentforce Sales (Sales Cloud)
  slug: salesforce-sales-cloud
  status: profiled
  tags: *id056
  url: /providers/salesforce-sales-cloud/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id057
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id058
  url: /providers/shopify/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id059
  name: Slack
  slug: slack
  status: profiled
  tags: *id060
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id061
  name: Snapchat
  slug: snapchat
  status: profiled
  tags: *id062
  url: /providers/snapchat/
- agent_band: agent-ready
  agent_readiness: 55.0
  band: developing
  in_catalog: true
  kin_score: 49.9
  mcp: *id063
  name: Tableau
  slug: tableau
  status: profiled
  tags: *id064
  url: /providers/tableau/
- agent_band: agent-aware
  agent_readiness: 28.3
  band: developing
  in_catalog: true
  kin_score: 43.2
  mcp: *id065
  name: Threads
  slug: threads-api
  status: profiled
  tags: *id066
  url: /providers/threads-api/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: developing
  in_catalog: true
  kin_score: 40.5
  mcp: *id067
  name: TikTok
  slug: tiktok
  status: profiled
  tags: *id068
  url: /providers/tiktok/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: thin
  in_catalog: true
  kin_score: 35.7
  mcp: *id069
  name: Tripadvisor
  slug: tripadvisor
  status: profiled
  tags: *id070
  url: /providers/tripadvisor/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: developing
  in_catalog: true
  kin_score: 48.2
  mcp: *id071
  name: Trustpilot
  slug: trustpilot
  status: profiled
  tags: *id072
  url: /providers/trustpilot/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id073
  name: Tumblr
  slug: tumblr
  status: profiled
  tags: *id074
  url: /providers/tumblr/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id075
  name: WhatsApp
  slug: whatsapp
  status: profiled
  tags: *id076
  url: /providers/whatsapp/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id077
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id078
  url: /providers/woocommerce/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id079
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id080
  url: /providers/x/
- agent_band: agent-native
  agent_readiness: 46.7
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id081
  name: Yelp
  slug: yelp
  status: profiled
  tags: *id082
  url: /providers/yelp/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: strong
  in_catalog: true
  kin_score: 65.4
  mcp: *id083
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id084
  url: /providers/youtube/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id085
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id086
  url: /providers/zendesk/
siblings:
- name: Buffer
  rows: 39
  url: /applications/social-media-management/buffer/
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
sitemap: true
title: 'Sprout Social: Social Media Management & Scheduling reference app'
---
