---
app: Linkwarden
app_slug: linkwarden
app_url: https://github.com/linkwarden/linkwarden
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: common
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - Azure OpenAI
  - Ollama
  - OpenAI
  - Perplexity
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.10.30
  key: AE-110.10.30
  layer: common
  name: Model Routing & Gateways
  providers:
  - OpenRouter
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: common
  name: Search and Discovery Management
  providers:
  - Meilisearch
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Apple
  - Atlassian
  - Battle.net
  - Box
  - Bungie
  - Coinbase
  - Discord
  - Dropbox
  - Facebook
  - Foursquare
  - FreshBooks
  - GitHub
  - GitLab
  - Google
  - HubSpot
  - Kakao
  - LINE
  - LinkedIn
  - Mailchimp
  - Naver
  - Netlify
  - Patreon
  - Pinterest
  - Pipedrive
  - Reddit
  - Salesforce
  - Slack
  - Spotify
  - Strava
  - Todoist
  - Twitch
  - VK
  - Wikimedia
  - WordPress.com
  - Yandex ID
  - Zoho
  - Zoom
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - DigitalOcean Spaces
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Amazon Cognito
  - Authelia
  - Authentik
  - Azure AD / B2C
  - FusionAuth
  - Keycloak
  - Okta
  - OneLogin
  - Synology
  - Zitadel
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: news-feed-reader
  name: News, Feeds & Read-Later
  url: /applications/news-feed-reader/
counts:
  declared: 0
  observed: 55
credits: []
evidence:
- route: source code
  url: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id001
      status: none
    slug: amazon-cognito
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Authentication
    - Identity
    - OAuth
    url: /providers/amazon-cognito/
  layer: common
  name: Amazon Cognito
  provider: amazon-cognito
  says: ships the Amazon Cognito SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    mcp: &id003
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id004
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: common
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
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
  layer: common
  name: Apple
  provider: apple
  says: ships the Apple SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.6
    band: exemplar
    in_catalog: true
    kin_score: 79.9
    mcp: &id007
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: atlassian
    status: profiled
    tags: &id008
    - Code
    - Collaboration
    - Platform
    - Productivity
    url: /providers/atlassian/
  layer: common
  name: Atlassian
  provider: atlassian
  says: ships the Atlassian SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.8
    band: strong
    in_catalog: true
    kin_score: 54.6
    mcp: &id009
      status: none
    slug: authelia
    status: profiled
    tags: &id010
    - Authentication
    - Authorization
    - LDAP
    - MFA
    url: /providers/authelia/
  layer: common
  name: Authelia
  provider: authelia
  says: ships the Authelia SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.2
    band: exemplar
    in_catalog: true
    kin_score: 74.5
    mcp: &id011
      status: none
    slug: authentik
    status: profiled
    tags: &id012
    - Authentication
    - Authorization
    - Identity Provider
    - LDAP
    url: /providers/authentik/
  layer: common
  name: Authentik
  provider: authentik
  says: ships the Authentik SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.5
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id013
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id014
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Azure AD / B2C
  provider: microsoft-entra
  says: ships the Azure AD / B2C SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    agent_band: agent-aware
    agent_readiness: 23.4
    band: developing
    in_catalog: true
    kin_score: 44.6
    mcp: &id015
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-openai
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - Embeddings
    - GPT
    - Generative AI
    url: /providers/microsoft-azure-openai/
  layer: common
  name: Azure OpenAI
  provider: microsoft-azure-openai
  says: ships the Azure OpenAI SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 41.8
    band: thin
    in_catalog: true
    kin_score: 32.4
    mcp: &id017
      status: none
    slug: battle-net
    status: profiled
    tags: &id018
    - Blizzard
    - Games
    - Gaming
    - World Of Warcraft
    url: /providers/battle-net/
  layer: common
  name: Battle.net
  provider: battle-net
  says: ships the Battle.net SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 57.4
    band: strong
    in_catalog: true
    kin_score: 65.5
    mcp: &id019
      source: https://developer.box.com/guides/box-mcp/
      status: verified
    slug: box
    status: profiled
    tags: &id020
    - Cloud Storage
    - Collaboration
    - Content Management
    - Documents
    url: /providers/box/
  layer: common
  name: Box
  provider: box
  says: ships the Box SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.0
    mcp: &id021
      status: none
    slug: bungie
    status: profiled
    tags: &id022
    - Community
    - Company
    - Gaming
    - Video Games
    url: /providers/bungie/
  layer: common
  name: Bungie
  provider: bungie
  says: ships the Bungie SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 51.5
    band: strong
    in_catalog: true
    kin_score: 56.6
    mcp: &id023
      source: https://github.com/coinbase/payments-mcp
      status: verified
    slug: coinbase
    status: profiled
    tags: &id024
    - Blockchain
    - Cryptocurrency
    - Custody
    - Exchange
    url: /providers/coinbase/
  layer: common
  name: Coinbase
  provider: coinbase
  says: ships the Coinbase SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
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
    agent_readiness: 44.6
    band: developing
    in_catalog: true
    kin_score: 45.0
    mcp: &id025
      source: https://docs.digitalocean.com/reference/mcp/
      status: verified
    slug: digital-ocean
    status: profiled
    tags: &id026
    - Cloud
    - Compute
    - Infrastructure
    - Servers
    url: /providers/digital-ocean/
  layer: common
  name: DigitalOcean Spaces
  provider: digital-ocean
  says: ships the DigitalOcean Spaces SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id027
      status: none
    slug: discord
    status: profiled
    tags: &id028
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.8
    band: developing
    in_catalog: true
    kin_score: 47.9
    mcp: &id029
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id030
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: common
  name: Dropbox
  provider: dropbox
  says: ships the Dropbox SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id031
      status: none
    slug: facebook
    status: profiled
    tags: &id032
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: developing
    in_catalog: true
    kin_score: 47.7
    mcp: &id033
      source: https://github.com/foursquare/foursquare-places-mcp
      status: verified
    slug: foursquare
    status: profiled
    tags: &id034
    - Geocoding
    - Location
    - Places
    - Restaurant
    url: /providers/foursquare/
  layer: common
  name: Foursquare
  provider: foursquare
  says: ships the Foursquare SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.1
    band: thin
    in_catalog: true
    kin_score: 31.2
    mcp: &id035
      status: none
    slug: freshbooks
    status: profiled
    tags: &id036
    - Accounting
    - Expense Tracking
    - Invoicing
    - Time Tracking
    url: /providers/freshbooks/
  layer: common
  name: FreshBooks
  provider: freshbooks
  says: ships the FreshBooks SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.2
    band: strong
    in_catalog: true
    kin_score: 56.6
    mcp: &id037
      source: https://github.com/FusionAuth/fusionauth-mcp-api
      status: verified
    slug: fusionauth
    status: profiled
    tags: &id038
    - Authentication
    - Authorization
    - CIAM
    - Identity
    url: /providers/fusionauth/
  layer: common
  name: FusionAuth
  provider: fusionauth
  says: ships the FusionAuth SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id039
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id040
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 55.6
    band: exemplar
    in_catalog: true
    kin_score: 79.6
    mcp: &id041
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id042
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: common
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id043
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id044
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google
  provider: google-identity-platform
  says: ships the Google SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.7
    band: exemplar
    in_catalog: true
    kin_score: 94.6
    mcp: &id045
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id046
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: common
  name: HubSpot
  provider: hubspot
  says: ships the HubSpot SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 27.2
    mcp: &id047
      status: none
    slug: kakao
    status: profiled
    tags: &id048
    - Maps
    - Messaging
    - Navigation
    - Payments
    url: /providers/kakao/
  layer: common
  name: Kakao
  provider: kakao
  says: ships the Kakao SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.6
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id049
      status: none
    slug: keycloak
    status: profiled
    tags: &id050
    - Authentication
    - Authorization
    - Identity and Access Management
    - OAuth
    url: /providers/keycloak/
  layer: common
  name: Keycloak
  provider: keycloak
  says: ships the Keycloak SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 47.9
    band: exemplar
    in_catalog: true
    kin_score: 74.5
    mcp: &id051
      source: https://github.com/line/line-bot-mcp-server
      status: verified
    slug: line
    status: profiled
    tags: &id052
    - Chatbots
    - Messaging
    - Mini Apps
    - Social Login
    url: /providers/line/
  layer: common
  name: LINE
  provider: line
  says: ships the LINE SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.4
    band: exemplar
    in_catalog: true
    kin_score: 76.4
    mcp: &id053
      status: none
    slug: linkedin
    status: profiled
    tags: &id054
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: common
  name: LinkedIn
  provider: linkedin
  says: ships the LinkedIn SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.3
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id055
      status: none
    slug: mailchimp
    status: profiled
    tags: &id056
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: ships the Mailchimp SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: developing
    in_catalog: true
    kin_score: 52.0
    mcp: &id057
      source: https://github.com/meilisearch/meilisearch-mcp
      status: verified
    slug: meilisearch
    status: profiled
    tags: &id058
    - AI Search
    - Full-Text Search
    - Hybrid Search
    - Open Source
    url: /providers/meilisearch/
  layer: common
  name: Meilisearch
  provider: meilisearch
  says: ships the Meilisearch SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id059
      status: none
    slug: naver
    status: profiled
    tags: &id060
    - Cloud Platform
    - Maps
    - Search
    - Translation
    url: /providers/naver/
  layer: common
  name: Naver
  provider: naver
  says: ships the Naver SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 58.8
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id061
      source: https://github.com/netlify/netlify-mcp
      status: verified
    slug: netlify
    status: profiled
    tags: &id062
    - CDN
    - Cloud
    - Continuous Deployment
    - Developer Tools
    url: /providers/netlify/
  layer: common
  name: Netlify
  provider: netlify
  says: ships the Netlify SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.8
    band: exemplar
    in_catalog: true
    kin_score: 78.0
    mcp: &id063
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id064
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: common
  name: Okta
  provider: okta
  says: ships the Okta SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    agent_band: agent-aware
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id065
      status: none
    slug: ollama
    status: profiled
    tags: &id066
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
  layer: common
  name: Ollama
  provider: ollama
  says: ships the Ollama SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.7
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id067
      source: https://github.com/onelogin/onelogin-mcp
      status: verified
    slug: onelogin
    status: profiled
    tags: &id068
    - Identity
    - Identity and Access Management
    - Multi-Factor Authentication
    - SSO
    url: /providers/onelogin/
  layer: common
  name: OneLogin
  provider: onelogin
  says: ships the OneLogin SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    agent_band: agent-native
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id069
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id070
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: common
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: strong
    in_catalog: true
    kin_score: 55.4
    mcp: &id071
      source: https://openrouter.ai/docs/guides/overview/mcp-server
      status: verified
    slug: openrouter
    status: profiled
    tags: &id072
    - Artificial Intelligence
    - Gateways
    - LLM
    - Router
    url: /providers/openrouter/
  layer: common
  name: OpenRouter
  provider: openrouter
  says: ships the OpenRouter SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 34.2
    mcp: &id073
      status: none
    slug: patreon
    status: profiled
    tags: &id074
    - Content
    - Creator Economy
    - Membership
    - Subscription
    url: /providers/patreon/
  layer: common
  name: Patreon
  provider: patreon
  says: ships the Patreon SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    agent_band: agent-native
    agent_readiness: 67.7
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id075
      source: https://github.com/perplexityai/modelcontextprotocol
      status: verified
    slug: perplexity
    status: profiled
    tags: &id076
    - Agents
    - Artificial Intelligence
    - LLM
    - Search
    url: /providers/perplexity/
  layer: common
  name: Perplexity
  provider: perplexity
  says: ships the Perplexity SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.4
    band: developing
    in_catalog: true
    kin_score: 49.4
    mcp: &id077
      source: https://developers.pinterest.com/about-pinterest-mcp/
      status: verified
    slug: pinterest
    status: profiled
    tags: &id078
    - Image
    - Social
    - Social Media
    - Video
    url: /providers/pinterest/
  layer: common
  name: Pinterest
  provider: pinterest
  says: ships the Pinterest SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.3
    band: strong
    in_catalog: true
    kin_score: 55.5
    mcp: &id079
      status: none
    slug: pipedrive
    status: profiled
    tags: &id080
    - CRM
    - Pipeline Management
    - Sales
    - Software-as-a-Service
    url: /providers/pipedrive/
  layer: common
  name: Pipedrive
  provider: pipedrive
  says: ships the Pipedrive SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.1
    band: strong
    in_catalog: true
    kin_score: 63.0
    mcp: &id081
      source: https://github.com/reddit/devvit-mcp
      status: verified
    slug: reddit
    status: profiled
    tags: &id082
    - Advertising
    - Community
    - Content
    - Reddit
    url: /providers/reddit/
  layer: common
  name: Reddit
  provider: reddit
  says: ships the Reddit SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.7
    band: exemplar
    in_catalog: true
    kin_score: 90.6
    mcp: &id083
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id084
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: Salesforce
  provider: salesforce
  says: ships the Salesforce SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id085
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id086
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.3
    band: developing
    in_catalog: true
    kin_score: 49.8
    mcp: &id087
      status: none
    slug: spotify
    status: profiled
    tags: &id088
    - Audio
    - Music
    - Podcasts
    - Streaming
    url: /providers/spotify/
  layer: common
  name: Spotify
  provider: spotify
  says: ships the Spotify SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: developing
    in_catalog: true
    kin_score: 50.0
    mcp: &id089
      status: none
    slug: strava
    status: profiled
    tags: &id090
    - Cycling
    - Fitness
    - Fitness Tracking
    - Running
    url: /providers/strava/
  layer: common
  name: Strava
  provider: strava
  says: ships the Strava SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.6
    band: minimal
    in_catalog: true
    kin_score: 7.5
    mcp: &id091
      status: none
    slug: synology
    status: profiled
    tags: &id092
    - Backup
    - Cloud
    - Company
    - Storage
    url: /providers/synology/
  layer: common
  name: Synology
  provider: synology
  says: ships the Synology SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.6
    band: strong
    in_catalog: true
    kin_score: 55.7
    mcp: &id093
      source: https://developer.todoist.com/api/v1/#tag/MCP
      status: verified
    slug: todoist
    status: profiled
    tags: &id094
    - Productivity
    - Task
    - Task Management
    - To-Do
    url: /providers/todoist/
  layer: common
  name: Todoist
  provider: todoist
  says: ships the Todoist SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.2
    band: developing
    in_catalog: true
    kin_score: 50.5
    mcp: &id095
      status: none
    slug: twitch
    status: profiled
    tags: &id096
    - Entertainment
    - Gaming
    - Live Streaming
    - Streaming
    url: /providers/twitch/
  layer: common
  name: Twitch
  provider: twitch
  says: ships the Twitch SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.6
    mcp: &id097
      status: none
    slug: vk
    status: profiled
    tags: &id098
    - Public APIs
    - Social
    url: /providers/vk/
  layer: common
  name: VK
  provider: vk
  says: ships the VK SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.9
    band: developing
    in_catalog: true
    kin_score: 45.8
    mcp: &id099
      status: none
    slug: wikimedia
    status: profiled
    tags: &id100
    - Encyclopedia
    - Open Knowledge
    - Wikimedia
    - Wikipedia
    url: /providers/wikimedia/
  layer: common
  name: Wikimedia
  provider: wikimedia
  says: ships the Wikimedia SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.4
    band: developing
    in_catalog: true
    kin_score: 46.0
    mcp: &id101
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id102
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
  layer: common
  name: WordPress.com
  provider: wordpress
  says: ships the WordPress.com SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id103
      status: unchecked
    slug: yandex
    status: queued for profiling
    tags: &id104 []
    url: null
  layer: common
  name: Yandex ID
  provider: yandex
  says: ships the Yandex ID SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.9
    band: strong
    in_catalog: true
    kin_score: 55.3
    mcp: &id105
      status: none
    slug: zitadel
    status: profiled
    tags: &id106
    - Authentication
    - Authorization
    - Identity and Access Management
    - Open Source
    url: /providers/zitadel/
  layer: common
  name: Zitadel
  provider: zitadel
  says: ships the Zitadel SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.0
    band: strong
    in_catalog: true
    kin_score: 63.5
    mcp: &id107
      source: https://www.zoho.com/mcp/
      status: verified
    slug: zoho
    status: profiled
    tags: &id108
    - Analytics
    - CRM
    - Collaboration
    - Customer Service
    url: /providers/zoho/
  layer: common
  name: Zoho
  provider: zoho
  says: ships the Zoho SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 55.2
    band: strong
    in_catalog: true
    kin_score: 56.2
    mcp: &id109
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id110
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: common
  name: Zoom
  provider: zoom
  says: ships the Zoom SDK or integration code
  source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/news-feed-reader/linkwarden/
providers:
- agent_band: agent-aware
  agent_readiness: 27.7
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id001
  name: Amazon Cognito
  slug: amazon-cognito
  status: profiled
  tags: *id002
  url: /providers/amazon-cognito/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 87.5
  mcp: *id003
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id004
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id005
  name: Apple
  slug: apple
  status: profiled
  tags: *id006
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 42.6
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id007
  name: Atlassian
  slug: atlassian
  status: profiled
  tags: *id008
  url: /providers/atlassian/
- agent_band: agent-ready
  agent_readiness: 31.8
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id009
  name: Authelia
  slug: authelia
  status: profiled
  tags: *id010
  url: /providers/authelia/
- agent_band: agent-ready
  agent_readiness: 33.2
  band: exemplar
  in_catalog: true
  kin_score: 74.5
  mcp: *id011
  name: Authentik
  slug: authentik
  status: profiled
  tags: *id012
  url: /providers/authentik/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id013
  name: Azure AD / B2C
  slug: microsoft-entra
  status: profiled
  tags: *id014
  url: /providers/microsoft-entra/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: developing
  in_catalog: true
  kin_score: 44.6
  mcp: *id015
  name: Azure OpenAI
  slug: microsoft-azure-openai
  status: profiled
  tags: *id016
  url: /providers/microsoft-azure-openai/
- agent_band: agent-native
  agent_readiness: 41.8
  band: thin
  in_catalog: true
  kin_score: 32.4
  mcp: *id017
  name: Battle.net
  slug: battle-net
  status: profiled
  tags: *id018
  url: /providers/battle-net/
- agent_band: agent-ready
  agent_readiness: 57.4
  band: strong
  in_catalog: true
  kin_score: 65.5
  mcp: *id019
  name: Box
  slug: box
  status: profiled
  tags: *id020
  url: /providers/box/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.0
  mcp: *id021
  name: Bungie
  slug: bungie
  status: profiled
  tags: *id022
  url: /providers/bungie/
- agent_band: agent-native
  agent_readiness: 51.5
  band: strong
  in_catalog: true
  kin_score: 56.6
  mcp: *id023
  name: Coinbase
  slug: coinbase
  status: profiled
  tags: *id024
  url: /providers/coinbase/
- agent_band: agent-ready
  agent_readiness: 44.6
  band: developing
  in_catalog: true
  kin_score: 45.0
  mcp: *id025
  name: DigitalOcean Spaces
  slug: digital-ocean
  status: profiled
  tags: *id026
  url: /providers/digital-ocean/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id027
  name: Discord
  slug: discord
  status: profiled
  tags: *id028
  url: /providers/discord/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id029
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id030
  url: /providers/dropbox/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id031
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id032
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id033
  name: Foursquare
  slug: foursquare
  status: profiled
  tags: *id034
  url: /providers/foursquare/
- agent_band: agent-aware
  agent_readiness: 20.1
  band: thin
  in_catalog: true
  kin_score: 31.2
  mcp: *id035
  name: FreshBooks
  slug: freshbooks
  status: profiled
  tags: *id036
  url: /providers/freshbooks/
- agent_band: agent-ready
  agent_readiness: 32.2
  band: strong
  in_catalog: true
  kin_score: 56.6
  mcp: *id037
  name: FusionAuth
  slug: fusionauth
  status: profiled
  tags: *id038
  url: /providers/fusionauth/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id039
  name: GitHub
  slug: github
  status: profiled
  tags: *id040
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 55.6
  band: exemplar
  in_catalog: true
  kin_score: 79.6
  mcp: *id041
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id042
  url: /providers/gitlab/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id043
  name: Google
  slug: google-identity-platform
  status: profiled
  tags: *id044
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id045
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id046
  url: /providers/hubspot/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 27.2
  mcp: *id047
  name: Kakao
  slug: kakao
  status: profiled
  tags: *id048
  url: /providers/kakao/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id049
  name: Keycloak
  slug: keycloak
  status: profiled
  tags: *id050
  url: /providers/keycloak/
- agent_band: agent-native
  agent_readiness: 47.9
  band: exemplar
  in_catalog: true
  kin_score: 74.5
  mcp: *id051
  name: LINE
  slug: line
  status: profiled
  tags: *id052
  url: /providers/line/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: exemplar
  in_catalog: true
  kin_score: 76.4
  mcp: *id053
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id054
  url: /providers/linkedin/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id055
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id056
  url: /providers/mailchimp/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: developing
  in_catalog: true
  kin_score: 52.0
  mcp: *id057
  name: Meilisearch
  slug: meilisearch
  status: profiled
  tags: *id058
  url: /providers/meilisearch/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id059
  name: Naver
  slug: naver
  status: profiled
  tags: *id060
  url: /providers/naver/
- agent_band: agent-ready
  agent_readiness: 58.8
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id061
  name: Netlify
  slug: netlify
  status: profiled
  tags: *id062
  url: /providers/netlify/
- agent_band: agent-ready
  agent_readiness: 53.8
  band: exemplar
  in_catalog: true
  kin_score: 78.0
  mcp: *id063
  name: Okta
  slug: okta
  status: profiled
  tags: *id064
  url: /providers/okta/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id065
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id066
  url: /providers/ollama/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id067
  name: OneLogin
  slug: onelogin
  status: profiled
  tags: *id068
  url: /providers/onelogin/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id069
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id070
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: strong
  in_catalog: true
  kin_score: 55.4
  mcp: *id071
  name: OpenRouter
  slug: openrouter
  status: profiled
  tags: *id072
  url: /providers/openrouter/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id073
  name: Patreon
  slug: patreon
  status: profiled
  tags: *id074
  url: /providers/patreon/
- agent_band: agent-native
  agent_readiness: 67.7
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id075
  name: Perplexity
  slug: perplexity
  status: profiled
  tags: *id076
  url: /providers/perplexity/
- agent_band: agent-ready
  agent_readiness: 38.4
  band: developing
  in_catalog: true
  kin_score: 49.4
  mcp: *id077
  name: Pinterest
  slug: pinterest
  status: profiled
  tags: *id078
  url: /providers/pinterest/
- agent_band: agent-ready
  agent_readiness: 29.3
  band: strong
  in_catalog: true
  kin_score: 55.5
  mcp: *id079
  name: Pipedrive
  slug: pipedrive
  status: profiled
  tags: *id080
  url: /providers/pipedrive/
- agent_band: agent-ready
  agent_readiness: 39.1
  band: strong
  in_catalog: true
  kin_score: 63.0
  mcp: *id081
  name: Reddit
  slug: reddit
  status: profiled
  tags: *id082
  url: /providers/reddit/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id083
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id084
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id085
  name: Slack
  slug: slack
  status: profiled
  tags: *id086
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: developing
  in_catalog: true
  kin_score: 49.8
  mcp: *id087
  name: Spotify
  slug: spotify
  status: profiled
  tags: *id088
  url: /providers/spotify/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id089
  name: Strava
  slug: strava
  status: profiled
  tags: *id090
  url: /providers/strava/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: minimal
  in_catalog: true
  kin_score: 7.5
  mcp: *id091
  name: Synology
  slug: synology
  status: profiled
  tags: *id092
  url: /providers/synology/
- agent_band: agent-aware
  agent_readiness: 22.6
  band: strong
  in_catalog: true
  kin_score: 55.7
  mcp: *id093
  name: Todoist
  slug: todoist
  status: profiled
  tags: *id094
  url: /providers/todoist/
- agent_band: agent-ready
  agent_readiness: 32.2
  band: developing
  in_catalog: true
  kin_score: 50.5
  mcp: *id095
  name: Twitch
  slug: twitch
  status: profiled
  tags: *id096
  url: /providers/twitch/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id097
  name: VK
  slug: vk
  status: profiled
  tags: *id098
  url: /providers/vk/
- agent_band: agent-ready
  agent_readiness: 28.9
  band: developing
  in_catalog: true
  kin_score: 45.8
  mcp: *id099
  name: Wikimedia
  slug: wikimedia
  status: profiled
  tags: *id100
  url: /providers/wikimedia/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: developing
  in_catalog: true
  kin_score: 46.0
  mcp: *id101
  name: WordPress.com
  slug: wordpress
  status: profiled
  tags: *id102
  url: /providers/wordpress/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id103
  name: Yandex ID
  slug: yandex
  status: queued for profiling
  tags: *id104
  url: null
- agent_band: agent-aware
  agent_readiness: 20.9
  band: strong
  in_catalog: true
  kin_score: 55.3
  mcp: *id105
  name: Zitadel
  slug: zitadel
  status: profiled
  tags: *id106
  url: /providers/zitadel/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: strong
  in_catalog: true
  kin_score: 63.5
  mcp: *id107
  name: Zoho
  slug: zoho
  status: profiled
  tags: *id108
  url: /providers/zoho/
- agent_band: agent-ready
  agent_readiness: 55.2
  band: strong
  in_catalog: true
  kin_score: 56.2
  mcp: *id109
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id110
  url: /providers/zoom/
siblings:
- name: Feedly
  rows: 8
  url: /applications/news-feed-reader/feedly/
- name: FreshRSS
  rows: 21
  url: /applications/news-feed-reader/freshrss/
- name: Karakeep
  rows: 4
  url: /applications/news-feed-reader/karakeep/
- name: Miniflux
  rows: 28
  url: /applications/news-feed-reader/miniflux/
- name: NewsBlur
  rows: 11
  url: /applications/news-feed-reader/newsblur/
- name: Readwise Reader
  rows: 10
  url: /applications/news-feed-reader/readwise-reader/
- name: Wallabag
  rows: 8
  url: /applications/news-feed-reader/wallabag/
sitemap: true
title: 'Linkwarden: News, Feeds & Read-Later reference app'
---
