---
app: Homer
app_slug: homer
app_url: https://github.com/bastienwirtz/homer
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.70
  key: AE-200.70
  layer: domain
  name: 3D Printing & Printer Control
  providers:
  - OctoPrint
  url: /capabilities/3d-printing-printer-control/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.90.10
  key: AE-170.90.10
  layer: domain
  name: BitTorrent & Usenet Download Clients
  providers:
  - Prowlarr
  - qBittorrent
  - SABnzbd
  - Transmission
  url: /capabilities/self-hosted-media-servers-library-automation/
  via_parent: Self-Hosted Media Servers & Library Automation
- attribution: API Evangelist extension
  id: AE-170.60.40
  key: AE-170.60.40
  layer: domain
  name: Bookmarks, Read-Later & Feed Readers
  providers:
  - FreshRSS
  - linkding
  - Miniflux
  - wallabag
  url: /capabilities/news-publishing/
  via_parent: News & Publishing
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Nextcloud
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-917
  key: AE-917
  layer: domain
  name: Enterprise Content & Document Management
  providers:
  - Paperless-ngx
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-200.60
  key: AE-200.60
  layer: domain
  name: Home Network & DNS Filtering
  providers:
  - AdGuard Home
  - Pi-hole
  - Traefik
  url: /capabilities/home-network-dns-filtering/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50
  key: it-infrastructure-management
  layer: domain
  name: IT Infrastructure Management
  providers:
  - Docker
  - Portainer
  - Proxmox VE
  - TrueNAS
  - What's Up Docker
  url: /capabilities/it-infrastructure-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: domain
  name: Observability Management
  providers:
  - Glances
  - Prometheus
  - Scrutiny
  - Speedtest Tracker
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.30.20
  key: AE-170.30.20
  layer: domain
  name: Photo Sharing
  providers:
  - Immich
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: domain
  name: Push Notifications
  providers:
  - Gotify
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-130.30.20
  key: AE-130.30.20
  layer: domain
  name: Recipe & Meal Planning
  providers:
  - Mealie
  url: /capabilities/nutrition-food-data/
  via_parent: Nutrition & Food Data
- attribution: API Evangelist extension
  id: AE-170.90
  key: AE-170.90
  layer: domain
  name: Self-Hosted Media Servers & Library Automation
  providers:
  - Emby
  - Jellystat
  - Lidarr
  - Medusa (TV)
  - Plex
  - Radarr
  - Readarr
  - Sonarr
  - Tautulli
  - Tdarr
  url: /capabilities/self-hosted-media-servers-library-automation/
  via_parent: null
- attribution: Turbo EA
  id: BC-2630.20
  key: service-performance-monitoring
  layer: domain
  name: Service Performance Monitoring
  providers:
  - Gatus
  - Healthchecks.io
  - Uptime Kuma
  url: /capabilities/service-performance-monitoring/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.10
  key: AE-200.10
  layer: domain
  name: Smart Home
  providers:
  - Home Assistant
  - openHAB
  url: /capabilities/smart-home/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40.10
  key: BC-4200.40.10
  layer: domain
  name: Source Code Management
  providers:
  - Gitea
  url: /capabilities/software-construction-management/
  via_parent: Software Construction Management
- attribution: API Evangelist extension
  id: AE-230.10
  key: AE-230.10
  layer: domain
  name: Weather & Environment
  providers:
  - OpenWeatherMap
  url: /capabilities/weather-environment/
  via_parent: null
category:
  id: personal-dashboard-homelab
  name: Personal Dashboard & Homelab
  url: /applications/personal-dashboard-homelab/
counts:
  declared: 0
  observed: 43
credits: []
evidence:
- route: source code
  url: https://github.com/bastienwirtz/homer/tree/main/src/components/services
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
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
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
    mcp: &id003
      source: https://github.com/docker/mcp-gateway
      status: verified
    slug: docker
    status: profiled
    tags: &id004
    - Cloud
    - Containers
    - DevOps
    - Developer Tools
    url: /providers/docker/
  layer: domain
  name: Docker
  provider: docker
  says: ships the Docker SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 21.4
    mcp: &id005
      status: none
    slug: emby
    status: profiled
    tags: &id006
    - Media Server
    - Personal Media
    - Streaming
    - Video Library
    url: /providers/emby/
  layer: domain
  name: Emby
  provider: emby
  says: ships the Emby SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.9
    mcp: &id007
      status: none
    slug: freshrss
    status: profiled
    tags: &id008
    - Feed Reader
    - RSS Aggregator
    - Self‑Hosted Software
    - Web Scraping
    url: /providers/freshrss/
  layer: domain
  name: FreshRSS
  provider: freshrss
  says: ships the FreshRSS SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
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
    kin_score: 12.0
    mcp: &id009
      status: unknown
    slug: gatus
    status: profiled
    tags: &id010
    - Company
    - Monitoring
    - Open Source
    - Status Pages
    url: /providers/gatus/
  layer: domain
  name: Gatus
  provider: gatus
  says: ships the Gatus SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
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
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id011
      source: https://gitea.com/gitea/gitea-mcp
      status: verified
    slug: gitea
    status: profiled
    tags: &id012
    - CI/CD
    - DevOps
    - Gitea
    - Version Control
    url: /providers/gitea/
  layer: domain
  name: Gitea
  provider: gitea
  says: ships the Gitea SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.2
    mcp: &id013
      status: unknown
    slug: glances
    status: profiled
    tags: &id014
    - Company
    - Monitoring
    - Open Source
    - Python
    url: /providers/glances/
  layer: domain
  name: Glances
  provider: glances
  says: ships the Glances SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.9
    mcp: &id015
      source: https://gotify.net/docs/mcp
      status: verified
    slug: gotify
    status: profiled
    tags: &id016
    - Messaging
    - Notification
    - Open Source
    - Self-Hosted
    url: /providers/gotify/
  layer: domain
  name: Gotify
  provider: gotify
  says: ships the Gotify SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
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
    agent_band: agent-aware
    agent_readiness: 17.2
    band: developing
    in_catalog: true
    kin_score: 43.4
    mcp: &id017
      status: none
    slug: healthchecks-io
    status: profiled
    tags: &id018
    - Cron
    - DevOps
    - Monitoring
    - Open Source
    url: /providers/healthchecks-io/
  layer: domain
  name: Healthchecks.io
  provider: healthchecks-io
  says: ships the Healthchecks.io SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.6
    band: thin
    in_catalog: true
    kin_score: 34.5
    mcp: &id019
      source: https://www.home-assistant.io/integrations/mcp_server/
      status: verified
    slug: home-assistant
    status: profiled
    tags: &id020
    - Community
    - Home Automation
    - IoT
    - Open Source
    url: /providers/home-assistant/
  layer: domain
  name: Home Assistant
  provider: home-assistant
  says: ships the Home Assistant SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
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
    agent_readiness: 15.1
    band: emerging
    in_catalog: true
    kin_score: 25.5
    mcp: &id021
      status: none
    slug: immich
    status: profiled
    tags: &id022
    - Photo Management
    - Privacy
    - Self-Hosted
    - Video Management
    url: /providers/immich/
  layer: domain
  name: Immich
  provider: immich
  says: ships the Immich SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.5
    mcp: &id023
      status: unknown
    slug: jellystat
    status: profiled
    tags: &id024
    - Analytics
    - Company
    - Media
    - Open Source
    url: /providers/jellystat/
  layer: domain
  name: Jellystat
  provider: jellystat
  says: ships the Jellystat SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.8
    mcp: &id025
      status: none
    slug: lidarr
    status: profiled
    tags: &id026
    - Automation
    - Media
    - Music
    - Open Source
    url: /providers/lidarr/
  layer: domain
  name: Lidarr
  provider: lidarr
  says: ships the Lidarr SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.5
    mcp: &id027
      status: none
    slug: linkding
    status: profiled
    tags: &id028
    - Bookmark
    - Company
    - Open Source
    - Self-Hosted
    url: /providers/linkding/
  layer: domain
  name: linkding
  provider: linkding
  says: ships the linkding SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-130.30.20
    key: AE-130.30.20
    name: Recipe & Meal Planning
    url: /capabilities/nutrition-food-data/
    via_parent: Nutrition & Food Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.1
    band: developing
    in_catalog: true
    kin_score: 41.7
    mcp: &id029
      status: none
    slug: mealie
    status: profiled
    tags: &id030
    - Company
    - Food
    - Meal Planning
    - Recipes
    url: /providers/mealie/
  layer: domain
  name: Mealie
  provider: mealie
  says: ships the Mealie SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.2
    band: emerging
    in_catalog: true
    kin_score: 13.9
    mcp: &id031
      status: none
    slug: pymedusa
    status: profiled
    tags: &id032
    - Automation
    - Company
    - Media
    - TV
    url: /providers/pymedusa/
  layer: domain
  name: Medusa (TV)
  provider: pymedusa
  says: ships the Medusa (TV) SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.7
    band: emerging
    in_catalog: true
    kin_score: 23.6
    mcp: &id033
      status: none
    slug: miniflux
    status: profiled
    tags: &id034
    - Feed Reader
    - Minimalist
    - Open Source
    - Self-Hosted
    url: /providers/miniflux/
  layer: domain
  name: Miniflux
  provider: miniflux
  says: ships the Miniflux SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
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
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 32.7
    mcp: &id035
      status: none
    slug: nextcloud
    status: profiled
    tags: &id036
    - Collaboration
    - File Sharing
    - File Sync
    - Self-Hosted
    url: /providers/nextcloud/
  layer: domain
  name: Nextcloud
  provider: nextcloud
  says: ships the Nextcloud SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.70
    key: AE-200.70
    name: 3D Printing & Printer Control
    url: /capabilities/3d-printing-printer-control/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.5
    band: thin
    in_catalog: true
    kin_score: 32.1
    mcp: &id037
      status: none
    slug: octoprint
    status: profiled
    tags: &id038
    - 3D Printing
    - Company
    - IoT
    - Open Source
    url: /providers/octoprint/
  layer: domain
  name: OctoPrint
  provider: octoprint
  says: ships the OctoPrint SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.8
    band: emerging
    in_catalog: true
    kin_score: 24.8
    mcp: &id039
      source: https://www.openhab.org/addons/integrations/mcp/
      status: verified
    slug: openhab
    status: profiled
    tags: &id040
    - Home Automation
    - IoT
    - Open Source
    - Smart Home
    url: /providers/openhab/
  layer: domain
  name: openHAB
  provider: openhab
  says: ships the openHAB SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
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
    agent_band: agent-ready
    agent_readiness: 30.0
    band: strong
    in_catalog: true
    kin_score: 59.1
    mcp: &id041
      source: https://mcp.openweathermap.org/
      status: verified
    slug: openweathermap
    status: profiled
    tags: &id042
    - Air Pollution
    - Climate
    - Forecast
    - Weather
    url: /providers/openweathermap/
  layer: domain
  name: OpenWeatherMap
  provider: openweathermap
  says: ships the OpenWeatherMap SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-917
    key: AE-917
    name: Enterprise Content & Document Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id043
      status: none
    slug: paperless-ngx
    status: profiled
    tags: &id044
    - Company
    url: /providers/paperless-ngx/
  layer: domain
  name: Paperless-ngx
  provider: paperless-ngx
  says: ships the Paperless-ngx SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
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
    mcp: &id045
      status: none
    slug: pi-hole
    status: profiled
    tags: &id046
    - Ad Blocking
    - DNS
    - Network Security
    - Privacy
    url: /providers/pi-hole/
  layer: domain
  name: Pi-hole
  provider: pi-hole
  says: ships the Pi-hole SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.2
    band: strong
    in_catalog: true
    kin_score: 56.7
    mcp: &id047
      status: none
    slug: plex
    status: profiled
    tags: &id048
    - Company
    - Media
    - Streaming
    - Video
    url: /providers/plex/
  layer: domain
  name: Plex
  provider: plex
  says: ships the Plex SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
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
    agent_readiness: 38.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id049
      source: https://github.com/portainer/portainer-mcp
      status: verified
    slug: portainer
    status: profiled
    tags: &id050
    - Container Management
    - Containers
    - Docker
    - Kubernetes
    url: /providers/portainer/
  layer: domain
  name: Portainer
  provider: portainer
  says: ships the Portainer SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 35.9
    mcp: &id051
      source: https://github.com/prometheus/prometheus-mcp
      status: verified
    slug: prometheus-io
    status: profiled
    tags: &id052
    - Metrics
    - Monitoring
    - Observability
    - Prometheus
    url: /providers/prometheus-io/
  layer: domain
  name: Prometheus
  provider: prometheus-io
  says: ships the Prometheus SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.90.10
    key: AE-170.90.10
    name: BitTorrent & Usenet Download Clients
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: Self-Hosted Media Servers & Library Automation
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.3
    band: developing
    in_catalog: true
    kin_score: 42.5
    mcp: &id053
      status: none
    slug: prowlarr
    status: profiled
    tags: &id054
    - Indexing
    - Media Management
    - Open Source
    - Software
    url: /providers/prowlarr/
  layer: domain
  name: Prowlarr
  provider: prowlarr
  says: ships the Prowlarr SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
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
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 26.8
    mcp: &id055
      status: none
    slug: proxmox
    status: profiled
    tags: &id056
    - Containers
    - KVM
    - LXC
    - Virtualization
    url: /providers/proxmox/
  layer: domain
  name: Proxmox VE
  provider: proxmox
  says: ships the Proxmox VE SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.90.10
    key: AE-170.90.10
    name: BitTorrent & Usenet Download Clients
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: Self-Hosted Media Servers & Library Automation
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 1.1
    band: minimal
    in_catalog: true
    kin_score: 10.5
    mcp: &id057
      status: none
    slug: qbittorrent
    status: profiled
    tags: &id058
    - Clients
    - Cross-Platform
    - Open Source
    - Torrent
    url: /providers/qbittorrent/
  layer: domain
  name: qBittorrent
  provider: qbittorrent
  says: ships the qBittorrent SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.0
    mcp: &id059
      status: unknown
    slug: radarr
    status: profiled
    tags: &id060
    - Automation
    - Media
    - Movie-Management
    - Open Source
    url: /providers/radarr/
  layer: domain
  name: Radarr
  provider: radarr
  says: ships the Radarr SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
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
    slug: readarr
    status: queued for profiling
    tags: &id062 []
    url: null
  layer: domain
  name: Readarr
  provider: readarr
  says: ships the Readarr SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.90.10
    key: AE-170.90.10
    name: BitTorrent & Usenet Download Clients
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: Self-Hosted Media Servers & Library Automation
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: emerging
    in_catalog: true
    kin_score: 22.6
    mcp: &id063
      status: none
    slug: sabnzbd
    status: profiled
    tags: &id064
    - Company
    - Downloader
    - Open Source
    - Usenet
    url: /providers/sabnzbd/
  layer: domain
  name: SABnzbd
  provider: sabnzbd
  says: ships the SABnzbd SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: emerging
    in_catalog: true
    kin_score: 17.2
    mcp: &id065
      status: unknown
    slug: scrutiny
    status: profiled
    tags: &id066
    - Company
    - Healthcare
    - Intelligence
    - Market Research
    url: /providers/scrutiny/
  layer: domain
  name: Scrutiny
  provider: scrutiny
  says: ships the Scrutiny SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: thin
    in_catalog: true
    kin_score: 32.5
    mcp: &id067
      status: none
    slug: sonarr
    status: profiled
    tags: &id068
    - Company
    - PVR
    - TV
    - Usenet
    url: /providers/sonarr/
  layer: domain
  name: Sonarr
  provider: sonarr
  says: ships the Sonarr SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.4
    band: emerging
    in_catalog: true
    kin_score: 24.2
    mcp: &id069
      status: unknown
    slug: speedtest-tracker
    status: profiled
    tags: &id070
    - Company
    - Monitoring
    - Self-Hosted
    - Speed Test
    url: /providers/speedtest-tracker/
  layer: domain
  name: Speedtest Tracker
  provider: speedtest-tracker
  says: ships the Speedtest Tracker SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.8
    band: emerging
    in_catalog: true
    kin_score: 12.4
    mcp: &id071
      status: none
    slug: tautulli
    status: profiled
    tags: &id072
    - Company
    - Monitoring
    - Open Source
    - Plex
    url: /providers/tautulli/
  layer: domain
  name: Tautulli
  provider: tautulli
  says: ships the Tautulli SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.5
    mcp: &id073
      status: unknown
    slug: tdarr
    status: profiled
    tags: &id074
    - Automation
    - Company
    - Transcoding
    - Video
    url: /providers/tdarr/
  layer: domain
  name: Tdarr
  provider: tdarr
  says: ships the Tdarr SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
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
    agent_readiness: 24.0
    band: strong
    in_catalog: true
    kin_score: 61.1
    mcp: &id075
      status: none
    slug: traefik
    status: profiled
    tags: &id076
    - AI Gateway
    - API Gateway
    - API Management
    - Developer Portal
    url: /providers/traefik/
  layer: domain
  name: Traefik
  provider: traefik
  says: ships the Traefik SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.90.10
    key: AE-170.90.10
    name: BitTorrent & Usenet Download Clients
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: Self-Hosted Media Servers & Library Automation
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.7
    mcp: &id077
      status: none
    slug: transmission-bt
    status: profiled
    tags: &id078
    - BitTorrent
    - Cross-Platform
    - File Sharing
    - Open Source
    url: /providers/transmission-bt/
  layer: domain
  name: Transmission
  provider: transmission-bt
  says: ships the Transmission SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
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
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 22.1
    mcp: &id079
      source: https://github.com/truenas/truenas-mcp
      status: verified
    slug: truenas
    status: profiled
    tags: &id080
    - Company
    - Enterprise
    - Open Source
    - Storage
    url: /providers/truenas/
  layer: domain
  name: TrueNAS
  provider: truenas
  says: ships the TrueNAS SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
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
    agent_band: agent-aware
    agent_readiness: 15.1
    band: emerging
    in_catalog: true
    kin_score: 20.6
    mcp: &id081
      status: none
    slug: uptime-kuma
    status: profiled
    tags: &id082
    - Dashboards
    - Monitoring
    - Open Source
    - Self-Hosted
    url: /providers/uptime-kuma/
  layer: domain
  name: Uptime Kuma
  provider: uptime-kuma
  says: ships the Uptime Kuma SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: emerging
    in_catalog: true
    kin_score: 20.1
    mcp: &id083
      status: none
    slug: wallabag
    status: profiled
    tags: &id084
    - Open Source
    - Privacy
    - Read-it-later
    - Self-Hosted
    url: /providers/wallabag/
  layer: domain
  name: wallabag
  provider: wallabag
  says: ships the wallabag SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
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
    agent_band: agent-aware
    agent_readiness: 6.3
    band: emerging
    in_catalog: true
    kin_score: 17.9
    mcp: &id085
      status: none
    slug: whats-up-docker
    status: profiled
    tags: &id086
    - Company
    - Container Management
    - Docker
    - Kubernetes
    url: /providers/whats-up-docker/
  layer: domain
  name: What's Up Docker
  provider: whats-up-docker
  says: ships the What's Up Docker SDK or integration code
  source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/personal-dashboard-homelab/homer/
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
- agent_band: agent-ready
  agent_readiness: 32.4
  band: developing
  in_catalog: true
  kin_score: 51.7
  mcp: *id003
  name: Docker
  slug: docker
  status: profiled
  tags: *id004
  url: /providers/docker/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 21.4
  mcp: *id005
  name: Emby
  slug: emby
  status: profiled
  tags: *id006
  url: /providers/emby/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.9
  mcp: *id007
  name: FreshRSS
  slug: freshrss
  status: profiled
  tags: *id008
  url: /providers/freshrss/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.0
  mcp: *id009
  name: Gatus
  slug: gatus
  status: profiled
  tags: *id010
  url: /providers/gatus/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id011
  name: Gitea
  slug: gitea
  status: profiled
  tags: *id012
  url: /providers/gitea/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id013
  name: Glances
  slug: glances
  status: profiled
  tags: *id014
  url: /providers/glances/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.9
  mcp: *id015
  name: Gotify
  slug: gotify
  status: profiled
  tags: *id016
  url: /providers/gotify/
- agent_band: agent-aware
  agent_readiness: 17.2
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id017
  name: Healthchecks.io
  slug: healthchecks-io
  status: profiled
  tags: *id018
  url: /providers/healthchecks-io/
- agent_band: agent-aware
  agent_readiness: 5.6
  band: thin
  in_catalog: true
  kin_score: 34.5
  mcp: *id019
  name: Home Assistant
  slug: home-assistant
  status: profiled
  tags: *id020
  url: /providers/home-assistant/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 25.5
  mcp: *id021
  name: Immich
  slug: immich
  status: profiled
  tags: *id022
  url: /providers/immich/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.5
  mcp: *id023
  name: Jellystat
  slug: jellystat
  status: profiled
  tags: *id024
  url: /providers/jellystat/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.8
  mcp: *id025
  name: Lidarr
  slug: lidarr
  status: profiled
  tags: *id026
  url: /providers/lidarr/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.5
  mcp: *id027
  name: linkding
  slug: linkding
  status: profiled
  tags: *id028
  url: /providers/linkding/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: developing
  in_catalog: true
  kin_score: 41.7
  mcp: *id029
  name: Mealie
  slug: mealie
  status: profiled
  tags: *id030
  url: /providers/mealie/
- agent_band: human-only
  agent_readiness: 3.2
  band: emerging
  in_catalog: true
  kin_score: 13.9
  mcp: *id031
  name: Medusa (TV)
  slug: pymedusa
  status: profiled
  tags: *id032
  url: /providers/pymedusa/
- agent_band: agent-aware
  agent_readiness: 14.7
  band: emerging
  in_catalog: true
  kin_score: 23.6
  mcp: *id033
  name: Miniflux
  slug: miniflux
  status: profiled
  tags: *id034
  url: /providers/miniflux/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 32.7
  mcp: *id035
  name: Nextcloud
  slug: nextcloud
  status: profiled
  tags: *id036
  url: /providers/nextcloud/
- agent_band: agent-aware
  agent_readiness: 22.5
  band: thin
  in_catalog: true
  kin_score: 32.1
  mcp: *id037
  name: OctoPrint
  slug: octoprint
  status: profiled
  tags: *id038
  url: /providers/octoprint/
- agent_band: agent-aware
  agent_readiness: 17.8
  band: emerging
  in_catalog: true
  kin_score: 24.8
  mcp: *id039
  name: openHAB
  slug: openhab
  status: profiled
  tags: *id040
  url: /providers/openhab/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: strong
  in_catalog: true
  kin_score: 59.1
  mcp: *id041
  name: OpenWeatherMap
  slug: openweathermap
  status: profiled
  tags: *id042
  url: /providers/openweathermap/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id043
  name: Paperless-ngx
  slug: paperless-ngx
  status: profiled
  tags: *id044
  url: /providers/paperless-ngx/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: emerging
  in_catalog: true
  kin_score: 22.3
  mcp: *id045
  name: Pi-hole
  slug: pi-hole
  status: profiled
  tags: *id046
  url: /providers/pi-hole/
- agent_band: agent-ready
  agent_readiness: 63.2
  band: strong
  in_catalog: true
  kin_score: 56.7
  mcp: *id047
  name: Plex
  slug: plex
  status: profiled
  tags: *id048
  url: /providers/plex/
- agent_band: agent-ready
  agent_readiness: 38.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id049
  name: Portainer
  slug: portainer
  status: profiled
  tags: *id050
  url: /providers/portainer/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 35.9
  mcp: *id051
  name: Prometheus
  slug: prometheus-io
  status: profiled
  tags: *id052
  url: /providers/prometheus-io/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: developing
  in_catalog: true
  kin_score: 42.5
  mcp: *id053
  name: Prowlarr
  slug: prowlarr
  status: profiled
  tags: *id054
  url: /providers/prowlarr/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 26.8
  mcp: *id055
  name: Proxmox VE
  slug: proxmox
  status: profiled
  tags: *id056
  url: /providers/proxmox/
- agent_band: human-only
  agent_readiness: 1.1
  band: minimal
  in_catalog: true
  kin_score: 10.5
  mcp: *id057
  name: qBittorrent
  slug: qbittorrent
  status: profiled
  tags: *id058
  url: /providers/qbittorrent/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id059
  name: Radarr
  slug: radarr
  status: profiled
  tags: *id060
  url: /providers/radarr/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id061
  name: Readarr
  slug: readarr
  status: queued for profiling
  tags: *id062
  url: null
- agent_band: agent-aware
  agent_readiness: 16.9
  band: emerging
  in_catalog: true
  kin_score: 22.6
  mcp: *id063
  name: SABnzbd
  slug: sabnzbd
  status: profiled
  tags: *id064
  url: /providers/sabnzbd/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: emerging
  in_catalog: true
  kin_score: 17.2
  mcp: *id065
  name: Scrutiny
  slug: scrutiny
  status: profiled
  tags: *id066
  url: /providers/scrutiny/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: thin
  in_catalog: true
  kin_score: 32.5
  mcp: *id067
  name: Sonarr
  slug: sonarr
  status: profiled
  tags: *id068
  url: /providers/sonarr/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: emerging
  in_catalog: true
  kin_score: 24.2
  mcp: *id069
  name: Speedtest Tracker
  slug: speedtest-tracker
  status: profiled
  tags: *id070
  url: /providers/speedtest-tracker/
- agent_band: human-only
  agent_readiness: 2.8
  band: emerging
  in_catalog: true
  kin_score: 12.4
  mcp: *id071
  name: Tautulli
  slug: tautulli
  status: profiled
  tags: *id072
  url: /providers/tautulli/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.5
  mcp: *id073
  name: Tdarr
  slug: tdarr
  status: profiled
  tags: *id074
  url: /providers/tdarr/
- agent_band: agent-aware
  agent_readiness: 24.0
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id075
  name: Traefik
  slug: traefik
  status: profiled
  tags: *id076
  url: /providers/traefik/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.7
  mcp: *id077
  name: Transmission
  slug: transmission-bt
  status: profiled
  tags: *id078
  url: /providers/transmission-bt/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 22.1
  mcp: *id079
  name: TrueNAS
  slug: truenas
  status: profiled
  tags: *id080
  url: /providers/truenas/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 20.6
  mcp: *id081
  name: Uptime Kuma
  slug: uptime-kuma
  status: profiled
  tags: *id082
  url: /providers/uptime-kuma/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: emerging
  in_catalog: true
  kin_score: 20.1
  mcp: *id083
  name: wallabag
  slug: wallabag
  status: profiled
  tags: *id084
  url: /providers/wallabag/
- agent_band: agent-aware
  agent_readiness: 6.3
  band: emerging
  in_catalog: true
  kin_score: 17.9
  mcp: *id085
  name: What's Up Docker
  slug: whats-up-docker
  status: profiled
  tags: *id086
  url: /providers/whats-up-docker/
siblings:
- name: CasaOS
  rows: 1
  url: /applications/personal-dashboard-homelab/casaos/
- name: Dashy
  rows: 35
  url: /applications/personal-dashboard-homelab/dashy/
- name: Glance
  rows: 16
  url: /applications/personal-dashboard-homelab/glance/
- name: Homarr
  rows: 65
  url: /applications/personal-dashboard-homelab/homarr/
- name: Homepage
  rows: 102
  url: /applications/personal-dashboard-homelab/homepage/
sitemap: true
title: 'Homer: Personal Dashboard & Homelab reference app'
---
