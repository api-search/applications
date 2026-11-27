---
app: Glance
app_slug: glance
app_url: https://github.com/glanceapp/glance
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-250.10.20
  key: AE-250.10.20
  layer: domain
  name: Container Registries
  providers:
  - Docker Hub
  url: /capabilities/package-registries-distribution/
  via_parent: Package Registries & Distribution
- attribution: API Evangelist extension
  id: AE-200.60
  key: AE-200.60
  layer: domain
  name: Home Network & DNS Filtering
  providers:
  - AdGuard Home
  - Pi-hole
  - Technitium DNS Server
  url: /capabilities/home-network-dns-filtering/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50
  key: it-infrastructure-management
  layer: domain
  name: IT Infrastructure Management
  providers:
  - Docker
  url: /capabilities/it-infrastructure-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50.10
  key: AE-170.50.10
  layer: domain
  name: Online Communities
  providers:
  - Hacker News
  - Lobsters
  - Reddit
  url: /capabilities/social-networks-community/
  via_parent: Social Networks & Community
- attribution: API Evangelist extension
  id: AE-230.20.20
  key: AE-230.20.20
  layer: domain
  name: Securities Market Data
  providers:
  - Yahoo Finance
  url: /capabilities/market-financial-data/
  via_parent: Market & Financial Data
- attribution: Turbo EA
  id: BC-2630.20
  key: service-performance-monitoring
  layer: domain
  name: Service Performance Monitoring
  providers:
  - changedetection.io
  url: /capabilities/service-performance-monitoring/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40.10
  key: BC-4200.40.10
  layer: domain
  name: Source Code Management
  providers:
  - Codeberg
  - GitHub
  - GitLab
  url: /capabilities/software-construction-management/
  via_parent: Software Construction Management
- attribution: API Evangelist extension
  id: AE-170.10.10
  key: AE-170.10.10
  layer: domain
  name: Video Hosting & Encoding
  providers:
  - Twitch
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
- attribution: API Evangelist extension
  id: AE-230.10
  key: AE-230.10
  layer: domain
  name: Weather & Environment
  providers:
  - Open-Meteo
  url: /capabilities/weather-environment/
  via_parent: null
category:
  id: personal-dashboard-homelab
  name: Personal Dashboard & Homelab
  url: /applications/personal-dashboard-homelab/
counts:
  declared: 0
  observed: 16
credits: []
evidence:
- route: source code
  url: https://github.com/glanceapp/glance/tree/main/internal/glance
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-200.60
    key: AE-200.60
    name: Home Network & DNS Filtering
    url: /capabilities/home-network-dns-filtering/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.9
    mcp: &id001
      status: none
    slug: adguard
    status: profiled
    tags: &id002
    - Ad Blocking
    - DNS Filtering
    - Network Security
    - Privacy
    url: /providers/adguard/
  layer: domain
  name: AdGuard Home
  provider: adguard
  says: ships the AdGuard Home SDK or integration code
  source: https://github.com/glanceapp/glance/tree/main/internal/glance/widget-dns-stats.go
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2630.20
    key: service-performance-monitoring
    name: Service Performance Monitoring
    url: /capabilities/service-performance-monitoring/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 18.1
    mcp: &id003
      status: none
    slug: changedetection-io
    status: profiled
    tags: &id004
    - Alerts
    - Company
    - Monitoring
    - Webhook
    url: /providers/changedetection-io/
  layer: domain
  name: changedetection.io
  provider: changedetection-io
  says: ships the changedetection.io SDK or integration code
  source: https://github.com/glanceapp/glance/tree/main/internal/glance/widget-changedetection.go
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40.10
    key: BC-4200.40.10
    name: Source Code Management
    url: /capabilities/software-construction-management/
    via_parent: Software Construction Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.2
    band: thin
    in_catalog: true
    kin_score: 28.4
    mcp: &id005
      status: unknown
    slug: codeberg
    status: profiled
    tags: &id006
    - Code Hosting
    - Git Hosting
    - Repositories
    - Version Control
    url: /providers/codeberg/
  layer: domain
  name: Codeberg
  provider: codeberg
  says: ships the Codeberg SDK or integration code
  source: https://github.com/glanceapp/glance/tree/main/internal/glance/widget-releases.go
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.4
    band: developing
    in_catalog: true
    kin_score: 51.7
    mcp: &id007
      source: https://github.com/docker/mcp-gateway
      status: verified
    slug: docker
    status: profiled
    tags: &id008
    - Cloud
    - Containers
    - DevOps
    - Developer Tools
    url: /providers/docker/
  layer: domain
  name: Docker
  provider: docker
  says: ships the Docker SDK or integration code
  source: https://github.com/glanceapp/glance/tree/main/internal/glance/widget-docker-containers.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 48.7
    mcp: &id009
      source: https://github.com/docker/hub-mcp
      status: verified
    slug: docker-hub
    status: profiled
    tags: &id010
    - Containers
    - DevOps
    - Docker
    - Registry
    url: /providers/docker-hub/
  layer: domain
  name: Docker Hub
  provider: docker-hub
  says: ships the Docker Hub SDK or integration code
  source: https://github.com/glanceapp/glance/tree/main/internal/glance/widget-releases.go
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40.10
    key: BC-4200.40.10
    name: Source Code Management
    url: /capabilities/software-construction-management/
    via_parent: Software Construction Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id011
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id012
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/glanceapp/glance/tree/main/internal/glance/widget-releases.go
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40.10
    key: BC-4200.40.10
    name: Source Code Management
    url: /capabilities/software-construction-management/
    via_parent: Software Construction Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id013
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id014
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/glanceapp/glance/tree/main/internal/glance/widget-releases.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.10
    key: AE-170.50.10
    name: Online Communities
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 27.3
    mcp: &id015
      status: none
    slug: hacker-news
    status: profiled
    tags: &id016
    - Developer Community
    - Technology News
    - Y Combinator
    url: /providers/hacker-news/
  layer: domain
  name: Hacker News
  provider: hacker-news
  says: ships the Hacker News SDK or integration code
  source: https://github.com/glanceapp/glance/tree/main/internal/glance/widget-hacker-news.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.10
    key: AE-170.50.10
    name: Online Communities
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.5
    band: emerging
    in_catalog: true
    kin_score: 24.6
    mcp: &id017
      status: none
    slug: lobsters
    status: profiled
    tags: &id018
    - Community
    - Link Aggregation
    - News
    - Technology
    url: /providers/lobsters/
  layer: domain
  name: Lobsters
  provider: lobsters
  says: ships the Lobsters SDK or integration code
  source: https://github.com/glanceapp/glance/tree/main/internal/glance/widget-lobsters.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: AE-230.10
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.4
    band: thin
    in_catalog: true
    kin_score: 28.3
    mcp: &id019
      status: none
    slug: open-meteo
    status: profiled
    tags: &id020
    - Air Quality
    - Forecast
    - Historical Weather
    - Weather
    url: /providers/open-meteo/
  layer: domain
  name: Open-Meteo
  provider: open-meteo
  says: ships the Open-Meteo SDK or integration code
  source: https://github.com/glanceapp/glance/tree/main/internal/glance/widget-weather.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.60
    key: AE-200.60
    name: Home Network & DNS Filtering
    url: /capabilities/home-network-dns-filtering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: emerging
    in_catalog: true
    kin_score: 22.3
    mcp: &id021
      status: none
    slug: pi-hole
    status: profiled
    tags: &id022
    - Ad Blocking
    - DNS
    - Network Security
    - Privacy
    url: /providers/pi-hole/
  layer: domain
  name: Pi-hole
  provider: pi-hole
  says: ships the Pi-hole SDK or integration code
  source: https://github.com/glanceapp/glance/tree/main/internal/glance/widget-dns-stats.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.10
    key: AE-170.50.10
    name: Online Communities
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id023
      source: https://github.com/reddit/devvit-mcp
      status: verified
    slug: reddit
    status: profiled
    tags: &id024
    - Advertising
    - Community
    - Content
    - Reddit
    url: /providers/reddit/
  layer: domain
  name: Reddit
  provider: reddit
  says: ships the Reddit SDK or integration code
  source: https://github.com/glanceapp/glance/tree/main/internal/glance/widget-reddit.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.60
    key: AE-200.60
    name: Home Network & DNS Filtering
    url: /capabilities/home-network-dns-filtering/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.1
    mcp: &id025
      status: none
    slug: technitium
    status: profiled
    tags: &id026
    - Company
    - DNS
    - Open Source
    - Privacy
    url: /providers/technitium/
  layer: domain
  name: Technitium DNS Server
  provider: technitium
  says: ships the Technitium DNS Server SDK or integration code
  source: https://github.com/glanceapp/glance/tree/main/internal/glance/widget-dns-stats.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.9
    band: developing
    in_catalog: true
    kin_score: 48.2
    mcp: &id027
      status: none
    slug: twitch
    status: profiled
    tags: &id028
    - Entertainment
    - Gaming
    - Live Streaming
    - Streaming
    url: /providers/twitch/
  layer: domain
  name: Twitch
  provider: twitch
  says: ships the Twitch SDK or integration code
  source: https://github.com/glanceapp/glance/tree/main/internal/glance/widget-twitch-channels.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.20
    key: AE-230.20.20
    name: Securities Market Data
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.3
    mcp: &id029
      status: none
    slug: yahoo-finance
    status: profiled
    tags: &id030
    - Finance
    - Public APIs
    url: /providers/yahoo-finance/
  layer: domain
  name: Yahoo Finance
  provider: yahoo-finance
  says: ships the Yahoo Finance SDK or integration code
  source: https://github.com/glanceapp/glance/tree/main/internal/glance/widget-markets.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.4
    band: strong
    in_catalog: true
    kin_score: 65.4
    mcp: &id031
      status: none
    slug: youtube
    status: profiled
    tags: &id032
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: ships the YouTube SDK or integration code
  source: https://github.com/glanceapp/glance/tree/main/internal/glance/widget-videos.go
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/personal-dashboard-homelab/glance/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.9
  mcp: *id001
  name: AdGuard Home
  slug: adguard
  status: profiled
  tags: *id002
  url: /providers/adguard/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.1
  mcp: *id003
  name: changedetection.io
  slug: changedetection-io
  status: profiled
  tags: *id004
  url: /providers/changedetection-io/
- agent_band: agent-aware
  agent_readiness: 26.2
  band: thin
  in_catalog: true
  kin_score: 28.4
  mcp: *id005
  name: Codeberg
  slug: codeberg
  status: profiled
  tags: *id006
  url: /providers/codeberg/
- agent_band: agent-ready
  agent_readiness: 32.4
  band: developing
  in_catalog: true
  kin_score: 51.7
  mcp: *id007
  name: Docker
  slug: docker
  status: profiled
  tags: *id008
  url: /providers/docker/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 48.7
  mcp: *id009
  name: Docker Hub
  slug: docker-hub
  status: profiled
  tags: *id010
  url: /providers/docker-hub/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id011
  name: GitHub
  slug: github
  status: profiled
  tags: *id012
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id013
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id014
  url: /providers/gitlab/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 27.3
  mcp: *id015
  name: Hacker News
  slug: hacker-news
  status: profiled
  tags: *id016
  url: /providers/hacker-news/
- agent_band: agent-aware
  agent_readiness: 22.5
  band: emerging
  in_catalog: true
  kin_score: 24.6
  mcp: *id017
  name: Lobsters
  slug: lobsters
  status: profiled
  tags: *id018
  url: /providers/lobsters/
- agent_band: agent-aware
  agent_readiness: 17.4
  band: thin
  in_catalog: true
  kin_score: 28.3
  mcp: *id019
  name: Open-Meteo
  slug: open-meteo
  status: profiled
  tags: *id020
  url: /providers/open-meteo/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: emerging
  in_catalog: true
  kin_score: 22.3
  mcp: *id021
  name: Pi-hole
  slug: pi-hole
  status: profiled
  tags: *id022
  url: /providers/pi-hole/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id023
  name: Reddit
  slug: reddit
  status: profiled
  tags: *id024
  url: /providers/reddit/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.1
  mcp: *id025
  name: Technitium DNS Server
  slug: technitium
  status: profiled
  tags: *id026
  url: /providers/technitium/
- agent_band: agent-ready
  agent_readiness: 36.9
  band: developing
  in_catalog: true
  kin_score: 48.2
  mcp: *id027
  name: Twitch
  slug: twitch
  status: profiled
  tags: *id028
  url: /providers/twitch/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.3
  mcp: *id029
  name: Yahoo Finance
  slug: yahoo-finance
  status: profiled
  tags: *id030
  url: /providers/yahoo-finance/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: strong
  in_catalog: true
  kin_score: 65.4
  mcp: *id031
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id032
  url: /providers/youtube/
siblings:
- name: CasaOS
  rows: 1
  url: /applications/personal-dashboard-homelab/casaos/
- name: Dashy
  rows: 35
  url: /applications/personal-dashboard-homelab/dashy/
- name: Homarr
  rows: 65
  url: /applications/personal-dashboard-homelab/homarr/
- name: Homepage
  rows: 102
  url: /applications/personal-dashboard-homelab/homepage/
- name: Homer
  rows: 43
  url: /applications/personal-dashboard-homelab/homer/
sitemap: true
title: 'Glance: Personal Dashboard & Homelab reference app'
---
