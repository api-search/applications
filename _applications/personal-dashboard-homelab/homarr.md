---
app: Homarr
app_slug: homarr
app_url: https://github.com/homarr-labs/homarr
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.70
  key: AE-200.70
  layer: domain
  name: 3D Printing & Printer Control
  providers:
  - Spoolman
  url: /capabilities/3d-printing-printer-control/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.90.10
  key: AE-170.90.10
  layer: domain
  name: BitTorrent & Usenet Download Clients
  providers:
  - Deluge
  - Jackett
  - NZBGet
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
  - Karakeep
  - Linkwarden
  - Miniflux
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
  - Caddy
  - Gluetun
  - OPNsense
  - Pi-hole
  - Technitium DNS Server
  - Traefik
  - Ubiquiti UniFi
  url: /capabilities/home-network-dns-filtering/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50
  key: it-infrastructure-management
  layer: domain
  name: IT Infrastructure Management
  providers:
  - Coolify
  - openmediavault
  - Proxmox VE
  - Synology
  - TrueNAS
  - Unraid
  - What's Up Docker
  url: /capabilities/it-infrastructure-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: domain
  name: Observability Management
  providers:
  - Beszel
  - Glances
  - Netdata
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
- attribution: Turbo EA
  id: BC-2340.50
  key: physical-security-surveillance-management
  layer: domain
  name: Physical Security & Surveillance Management
  providers:
  - Frigate NVR
  url: /capabilities/physical-security-surveillance-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: domain
  name: Product Usage Analytics
  providers:
  - Umami
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: domain
  name: Push Notifications
  providers:
  - Gotify
  - ntfy
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-130.30.20
  key: AE-130.30.20
  layer: domain
  name: Recipe & Meal Planning
  providers:
  - Mealie
  - Tandoor Recipes
  url: /capabilities/nutrition-food-data/
  via_parent: Nutrition & Food Data
- attribution: API Evangelist extension
  id: AE-170.90
  key: AE-170.90
  layer: domain
  name: Self-Hosted Media Servers & Library Automation
  providers:
  - Audiobookshelf
  - Bazarr
  - Emby
  - Jellyfin
  - Jellyseerr
  - Jellystat
  - Komga
  - Lidarr
  - Navidrome
  - Overseerr
  - Plex
  - Radarr
  - Readarr
  - RomM
  - Sonarr
  - Stash
  - Tdarr
  url: /capabilities/self-hosted-media-servers-library-automation/
  via_parent: null
- attribution: Turbo EA
  id: BC-2630.20
  key: service-performance-monitoring
  layer: domain
  name: Service Performance Monitoring
  providers:
  - changedetection.io
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
  url: /capabilities/smart-home/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40.10
  key: BC-4200.40.10
  layer: domain
  name: Source Code Management
  providers:
  - GitHub
  url: /capabilities/software-construction-management/
  via_parent: Software Construction Management
- attribution: Turbo EA
  id: BC-620.30
  key: threat-detection-response-management
  layer: domain
  name: Threat Detection & Response Management
  providers:
  - Wazuh
  url: /capabilities/threat-detection-response-management/
  via_parent: null
category:
  id: personal-dashboard-homelab
  name: Personal Dashboard & Homelab
  url: /applications/personal-dashboard-homelab/
counts:
  declared: 0
  observed: 65
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/homarr-labs/homarr/blob/dev/packages/integrations/package.json
- route: source code
  url: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
- route: source code
  url: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    kin_score: 11.6
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
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 17.6
    band: emerging
    in_catalog: true
    kin_score: 16.5
    mcp: &id003
      status: none
    slug: audiobookshelf
    status: profiled
    tags: &id004
    - Audiobooks
    - Company
    - Podcasts
    - Self-Hosted
    url: /providers/audiobookshelf/
  layer: domain
  name: Audiobookshelf
  provider: audiobookshelf
  says: ships the Audiobookshelf SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    kin_score: 8.7
    mcp: &id005
      status: none
    slug: bazarr
    status: profiled
    tags: &id006
    - Automation
    - Media
    - Open Source
    - Subtitle
    url: /providers/bazarr/
  layer: domain
  name: Bazarr
  provider: bazarr
  says: ships the Bazarr SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 17.1
    band: emerging
    in_catalog: true
    kin_score: 12.6
    mcp: &id007
      status: unknown
    slug: beszel
    status: profiled
    tags: &id008
    - Alerts
    - Docker
    - Podman
    - Server Monitoring
    url: /providers/beszel/
  layer: domain
  name: Beszel
  provider: beszel
  says: ships the Beszel SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 18.2
    band: thin
    in_catalog: true
    kin_score: 27.3
    mcp: &id009
      status: none
    slug: caddy
    status: profiled
    tags: &id010
    - Automatic HTTPS
    - Go
    - Load Balancer
    - Reverse Proxy
    url: /providers/caddy/
  layer: domain
  name: Caddy
  provider: caddy
  says: ships the Caddy SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    kin_score: 11.6
    mcp: &id011
      status: none
    slug: changedetection-io
    status: profiled
    tags: &id012
    - Alerts
    - Company
    - Monitoring
    - Webhook
    url: /providers/changedetection-io/
  layer: domain
  name: changedetection.io
  provider: changedetection-io
  says: ships the changedetection.io SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    agent_readiness: 27.5
    band: developing
    in_catalog: true
    kin_score: 51.6
    mcp: &id013
      status: none
    slug: coolify
    status: profiled
    tags: &id014
    - Deployment
    - Open Source
    - Platform-as-a-Service
    - Self-Hosting
    url: /providers/coolify/
  layer: domain
  name: Coolify
  provider: coolify
  says: ships the Coolify SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 21.1
    mcp: &id015
      status: none
    slug: deluge
    status: profiled
    tags: &id016
    - Automation
    - Company
    - Low-Code
    - Scripting
    url: /providers/deluge/
  layer: domain
  name: Deluge
  provider: deluge
  says: ships the Deluge SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    kin_score: 14.1
    mcp: &id017
      status: none
    slug: emby
    status: profiled
    tags: &id018
    - Media Server
    - Personal Media
    - Streaming
    - Video Library
    url: /providers/emby/
  layer: domain
  name: Emby
  provider: emby
  says: ships the Emby SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2340.50
    key: physical-security-surveillance-management
    name: Physical Security & Surveillance Management
    url: /capabilities/physical-security-surveillance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.1
    band: emerging
    in_catalog: true
    kin_score: 20.5
    mcp: &id019
      status: unknown
    slug: frigate
    status: profiled
    tags: &id020
    - Company
    - Open Source
    - Surveillance
    - Video
    url: /providers/frigate/
  layer: domain
  name: Frigate NVR
  provider: frigate
  says: ships the Frigate NVR SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    band: minimal
    in_catalog: true
    kin_score: 9.1
    mcp: &id021
      status: unknown
    slug: gatus
    status: profiled
    tags: &id022
    - Company
    - Monitoring
    - Open Source
    - Status Pages
    url: /providers/gatus/
  layer: domain
  name: Gatus
  provider: gatus
  says: ships the Gatus SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id023
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id024
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/homarr-labs/homarr/blob/dev/packages/integrations/package.json
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
    mcp: &id025
      status: unknown
    slug: glances
    status: profiled
    tags: &id026
    - Company
    - Monitoring
    - Open Source
    - Python
    url: /providers/glances/
  layer: domain
  name: Glances
  provider: glances
  says: ships the Glances SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    kin_score: 8.7
    mcp: &id027
      status: unknown
    slug: gluetun
    status: profiled
    tags: &id028
    - Docker
    - Open Source
    - VPN
    - WireGuard
    url: /providers/gluetun/
  layer: domain
  name: Gluetun
  provider: gluetun
  says: ships the Gluetun SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    kin_score: 7.8
    mcp: &id029
      source: https://gotify.net/docs/mcp
      status: verified
    slug: gotify
    status: profiled
    tags: &id030
    - Messaging
    - Notification
    - Open Source
    - Self-Hosted
    url: /providers/gotify/
  layer: domain
  name: Gotify
  provider: gotify
  says: ships the Gotify SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 17.6
    band: thin
    in_catalog: true
    kin_score: 32.9
    mcp: &id031
      status: none
    slug: healthchecks-io
    status: profiled
    tags: &id032
    - Cron
    - DevOps
    - Monitoring
    - Open Source
    url: /providers/healthchecks-io/
  layer: domain
  name: Healthchecks.io
  provider: healthchecks-io
  says: ships the Healthchecks.io SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    agent_band: human-only
    agent_readiness: 5.0
    band: emerging
    in_catalog: true
    kin_score: 22.2
    mcp: &id033
      source: https://www.home-assistant.io/integrations/mcp_server/
      status: verified
    slug: home-assistant
    status: profiled
    tags: &id034
    - Community
    - Home Automation
    - IoT
    - Open Source
    url: /providers/home-assistant/
  layer: domain
  name: Home Assistant
  provider: home-assistant
  says: ships the Home Assistant SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 21.3
    band: emerging
    in_catalog: true
    kin_score: 22.3
    mcp: &id035
      status: none
    slug: immich
    status: profiled
    tags: &id036
    - Photo Management
    - Privacy
    - Self-Hosted
    - Video Management
    url: /providers/immich/
  layer: domain
  name: Immich
  provider: immich
  says: ships the Immich SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 23.7
    band: emerging
    in_catalog: true
    kin_score: 17.2
    mcp: &id037
      status: none
    slug: jackett
    status: profiled
    tags: &id038
    - Company
    - Open Source
    - Proxy
    - Torrent
    url: /providers/jackett/
  layer: domain
  name: Jackett
  provider: jackett
  says: ships the Jackett SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 17.9
    band: emerging
    in_catalog: true
    kin_score: 16.7
    mcp: &id039
      status: none
    slug: jellyfin
    status: profiled
    tags: &id040
    - Community
    - FreeSoftware
    - Media
    - Open Source
    url: /providers/jellyfin/
  layer: domain
  name: Jellyfin
  provider: jellyfin
  says: ships the Jellyfin SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    mcp: &id041
      status: unchecked
    slug: jellyseerr
    status: queued for profiling
    tags: &id042 []
    url: null
  layer: domain
  name: Jellyseerr
  provider: jellyseerr
  says: ships the Jellyseerr SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    kin_score: 7.5
    mcp: &id043
      status: unknown
    slug: jellystat
    status: profiled
    tags: &id044
    - Analytics
    - Company
    - Media
    - Open Source
    url: /providers/jellystat/
  layer: domain
  name: Jellystat
  provider: jellystat
  says: ships the Jellystat SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    agent_readiness: 20.1
    band: thin
    in_catalog: true
    kin_score: 30.8
    mcp: &id045
      source: https://docs.karakeep.app/mcp
      status: verified
    slug: karakeep
    status: profiled
    tags: &id046
    - Artificial Intelligence
    - Bookmarking
    - Collaboration
    - Company
    url: /providers/karakeep/
  layer: domain
  name: Karakeep
  provider: karakeep
  says: ships the Karakeep SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 10.1
    mcp: &id047
      status: unknown
    slug: komga
    status: profiled
    tags: &id048
    - Comics
    - Ebooks
    - Manga
    - Media Server
    url: /providers/komga/
  layer: domain
  name: Komga
  provider: komga
  says: ships the Komga SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 10.0
    mcp: &id049
      status: none
    slug: lidarr
    status: profiled
    tags: &id050
    - Automation
    - Media
    - Music
    - Open Source
    url: /providers/lidarr/
  layer: domain
  name: Lidarr
  provider: lidarr
  says: ships the Lidarr SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 25.9
    band: developing
    in_catalog: true
    kin_score: 41.5
    mcp: &id051
      status: none
    slug: linkwarden
    status: profiled
    tags: &id052
    - Bookmarking
    - Company
    - Open Source
    - Self-Hosted
    url: /providers/linkwarden/
  layer: domain
  name: Linkwarden
  provider: linkwarden
  says: ships the Linkwarden SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    agent_readiness: 29.7
    band: developing
    in_catalog: true
    kin_score: 41.5
    mcp: &id053
      status: none
    slug: mealie
    status: profiled
    tags: &id054
    - Company
    - Food
    - Meal Planning
    - Recipes
    url: /providers/mealie/
  layer: domain
  name: Mealie
  provider: mealie
  says: ships the Mealie SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    agent_readiness: 15.0
    band: emerging
    in_catalog: true
    kin_score: 20.9
    mcp: &id055
      status: none
    slug: miniflux
    status: profiled
    tags: &id056
    - Feed Reader
    - Minimalist
    - Open Source
    - Self-Hosted
    url: /providers/miniflux/
  layer: domain
  name: Miniflux
  provider: miniflux
  says: ships the Miniflux SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    agent_readiness: 26.4
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id057
      status: none
    slug: navidrome
    status: profiled
    tags: &id058
    - Company
    - Music
    - Self-Hosted
    - Streaming
    url: /providers/navidrome/
  layer: domain
  name: Navidrome
  provider: navidrome
  says: ships the Navidrome SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 25.6
    band: thin
    in_catalog: true
    kin_score: 38.1
    mcp: &id059
      source: https://raw.githubusercontent.com/netdata/netdata/master/src/web/mcp/README.md
      status: verified
    slug: netdata
    status: profiled
    tags: &id060
    - Infrastructure
    - Metrics
    - Monitoring
    - Observability
    url: /providers/netdata/
  layer: domain
  name: Netdata
  provider: netdata
  says: ships the Netdata SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 33.0
    mcp: &id061
      status: none
    slug: nextcloud
    status: profiled
    tags: &id062
    - Collaboration
    - File Sharing
    - File Sync
    - Self-Hosted
    url: /providers/nextcloud/
  layer: domain
  name: Nextcloud
  provider: nextcloud
  says: ships the Nextcloud SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    kin_score: 9.9
    mcp: &id063
      status: none
    slug: ntfy
    status: profiled
    tags: &id064
    - Notification
    - Open Source
    - Pub/Sub
    - Self-Hosted
    url: /providers/ntfy/
  layer: domain
  name: ntfy
  provider: ntfy
  says: ships the ntfy SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    kin_score: 7.1
    mcp: &id065
      status: none
    slug: nzbget
    status: profiled
    tags: &id066
    - Cross-Platform
    - Downloader
    - RPC
    - Usenet
    url: /providers/nzbget/
  layer: domain
  name: NZBGet
  provider: nzbget
  says: ships the NZBGet SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 12.5
    mcp: &id067
      source: https://github.com/openmediavault/openmediavault-mcp
      status: verified
    slug: openmediavault
    status: profiled
    tags: &id068
    - Company
    - Data Sovereignty
    - NAS
    - Open Source
    url: /providers/openmediavault/
  layer: domain
  name: openmediavault
  provider: openmediavault
  says: ships the openmediavault SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 19.0
    band: emerging
    in_catalog: true
    kin_score: 25.2
    mcp: &id069
      status: none
    slug: opnsense
    status: profiled
    tags: &id070
    - Firewall
    - Networking
    - Security
    - VPN
    url: /providers/opnsense/
  layer: domain
  name: OPNsense
  provider: opnsense
  says: ships the OPNsense SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    mcp: &id071
      status: unchecked
    slug: overseerr
    status: queued for profiling
    tags: &id072 []
    url: null
  layer: domain
  name: Overseerr
  provider: overseerr
  says: ships the Overseerr SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    kin_score: 1.3
    mcp: &id073
      status: none
    slug: paperless-ngx
    status: profiled
    tags: &id074
    - Company
    url: /providers/paperless-ngx/
  layer: domain
  name: Paperless-ngx
  provider: paperless-ngx
  says: ships the Paperless-ngx SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 19.0
    band: emerging
    in_catalog: true
    kin_score: 22.9
    mcp: &id075
      status: none
    slug: pi-hole
    status: profiled
    tags: &id076
    - Ad Blocking
    - DNS
    - Network Security
    - Privacy
    url: /providers/pi-hole/
  layer: domain
  name: Pi-hole
  provider: pi-hole
  says: ships the Pi-hole SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 59.6
    band: strong
    in_catalog: true
    kin_score: 55.9
    mcp: &id077
      status: none
    slug: plex
    status: profiled
    tags: &id078
    - Company
    - Media
    - Streaming
    - Video
    url: /providers/plex/
  layer: domain
  name: Plex
  provider: plex
  says: ships the Plex SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 18.7
    band: thin
    in_catalog: true
    kin_score: 35.4
    mcp: &id079
      source: https://github.com/prometheus/prometheus-mcp
      status: verified
    slug: prometheus-io
    status: profiled
    tags: &id080
    - Metrics
    - Monitoring
    - Observability
    - Prometheus
    url: /providers/prometheus-io/
  layer: domain
  name: Prometheus
  provider: prometheus-io
  says: ships the Prometheus SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 34.7
    mcp: &id081
      status: none
    slug: prowlarr
    status: profiled
    tags: &id082
    - Indexing
    - Media Management
    - Open Source
    - Software
    url: /providers/prowlarr/
  layer: domain
  name: Prowlarr
  provider: prowlarr
  says: ships the Prowlarr SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 27.4
    mcp: &id083
      status: none
    slug: proxmox
    status: profiled
    tags: &id084
    - Containers
    - KVM
    - LXC
    - Virtualization
    url: /providers/proxmox/
  layer: domain
  name: Proxmox VE
  provider: proxmox
  says: ships the Proxmox VE SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    kin_score: 8.1
    mcp: &id085
      status: none
    slug: qbittorrent
    status: profiled
    tags: &id086
    - Clients
    - Cross-Platform
    - Open Source
    - Torrent
    url: /providers/qbittorrent/
  layer: domain
  name: qBittorrent
  provider: qbittorrent
  says: ships the qBittorrent SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 8.2
    mcp: &id087
      status: unknown
    slug: radarr
    status: profiled
    tags: &id088
    - Automation
    - Media
    - Movie-Management
    - Open Source
    url: /providers/radarr/
  layer: domain
  name: Radarr
  provider: radarr
  says: ships the Radarr SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    mcp: &id089
      status: unchecked
    slug: readarr
    status: queued for profiling
    tags: &id090 []
    url: null
  layer: domain
  name: Readarr
  provider: readarr
  says: ships the Readarr SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 33.1
    band: thin
    in_catalog: true
    kin_score: 37.3
    mcp: &id091
      status: none
    slug: romm
    status: profiled
    tags: &id092
    - Company
    - Media Management
    - Open Source
    - Retro Gaming
    url: /providers/romm/
  layer: domain
  name: RomM
  provider: romm
  says: ships the RomM SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    agent_readiness: 17.3
    band: emerging
    in_catalog: true
    kin_score: 19.1
    mcp: &id093
      status: none
    slug: sabnzbd
    status: profiled
    tags: &id094
    - Company
    - Downloader
    - Open Source
    - Usenet
    url: /providers/sabnzbd/
  layer: domain
  name: SABnzbd
  provider: sabnzbd
  says: ships the SABnzbd SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 17.3
    band: emerging
    in_catalog: true
    kin_score: 14.5
    mcp: &id095
      status: unknown
    slug: scrutiny
    status: profiled
    tags: &id096
    - Company
    - Healthcare
    - Intelligence
    - Market Research
    url: /providers/scrutiny/
  layer: domain
  name: Scrutiny
  provider: scrutiny
  says: ships the Scrutiny SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    agent_readiness: 25.8
    band: thin
    in_catalog: true
    kin_score: 28.5
    mcp: &id097
      status: none
    slug: sonarr
    status: profiled
    tags: &id098
    - Company
    - PVR
    - TV
    - Usenet
    url: /providers/sonarr/
  layer: domain
  name: Sonarr
  provider: sonarr
  says: ships the Sonarr SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 19.0
    band: emerging
    in_catalog: true
    kin_score: 20.2
    mcp: &id099
      status: unknown
    slug: speedtest-tracker
    status: profiled
    tags: &id100
    - Company
    - Monitoring
    - Self-Hosted
    - Speed Test
    url: /providers/speedtest-tracker/
  layer: domain
  name: Speedtest Tracker
  provider: speedtest-tracker
  says: ships the Speedtest Tracker SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_band: agent-ready
    agent_readiness: 40.1
    band: emerging
    in_catalog: true
    kin_score: 16.4
    mcp: &id101
      status: unknown
    slug: spoolman
    status: profiled
    tags: &id102
    - 3D Printing
    - Inventory
    - Open Source
    - filament
    url: /providers/spoolman/
  layer: domain
  name: Spoolman
  provider: spoolman
  says: ships the Spoolman SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    kin_score: 10.6
    mcp: &id103
      status: unknown
    slug: stashapp
    status: profiled
    tags: &id104
    - Adult
    - Company
    - Media
    - Open Source
    url: /providers/stashapp/
  layer: domain
  name: Stash
  provider: stashapp
  says: ships the Stash SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    agent_readiness: 21.6
    band: minimal
    in_catalog: true
    kin_score: 7.5
    mcp: &id105
      status: none
    slug: synology
    status: profiled
    tags: &id106
    - Backup
    - Cloud
    - Company
    - Storage
    url: /providers/synology/
  layer: domain
  name: Synology
  provider: synology
  says: ships the Synology SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_band: agent-aware
    agent_readiness: 26.7
    band: strong
    in_catalog: true
    kin_score: 61.0
    mcp: &id107
      status: none
    slug: tandoor
    status: profiled
    tags: &id108
    - Food
    - Meal Planning
    - Nutrition
    - Recipes
    url: /providers/tandoor/
  layer: domain
  name: Tandoor Recipes
  provider: tandoor
  says: ships the Tandoor Recipes SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
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
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 5.2
    mcp: &id109
      status: unknown
    slug: tdarr
    status: profiled
    tags: &id110
    - Automation
    - Company
    - Transcoding
    - Video
    url: /providers/tdarr/
  layer: domain
  name: Tdarr
  provider: tdarr
  says: ships the Tdarr SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    kin_score: 6.0
    mcp: &id111
      status: none
    slug: technitium
    status: profiled
    tags: &id112
    - Company
    - DNS
    - Open Source
    - Privacy
    url: /providers/technitium/
  layer: domain
  name: Technitium DNS Server
  provider: technitium
  says: ships the Technitium DNS Server SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 24.5
    band: strong
    in_catalog: true
    kin_score: 57.9
    mcp: &id113
      status: none
    slug: traefik
    status: profiled
    tags: &id114
    - AI Gateway
    - API Gateway
    - API Management
    - Developer Portal
    url: /providers/traefik/
  layer: domain
  name: Traefik
  provider: traefik
  says: ships the Traefik SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    kin_score: 4.4
    mcp: &id115
      status: none
    slug: transmission-bt
    status: profiled
    tags: &id116
    - BitTorrent
    - Cross-Platform
    - File Sharing
    - Open Source
    url: /providers/transmission-bt/
  layer: domain
  name: Transmission
  provider: transmission-bt
  says: ships the Transmission SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 17.3
    band: emerging
    in_catalog: true
    kin_score: 14.1
    mcp: &id117
      source: https://github.com/truenas/truenas-mcp
      status: verified
    slug: truenas
    status: profiled
    tags: &id118
    - Company
    - Enterprise
    - Open Source
    - Storage
    url: /providers/truenas/
  layer: domain
  name: TrueNAS
  provider: truenas
  says: ships the TrueNAS SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 23.9
    band: developing
    in_catalog: true
    kin_score: 46.3
    mcp: &id119
      status: none
    slug: ubiquiti
    status: profiled
    tags: &id120
    - Networking
    - Routing
    - Switching
    - Wi-Fi
    url: /providers/ubiquiti/
  layer: domain
  name: Ubiquiti UniFi
  provider: ubiquiti
  says: ships the Ubiquiti UniFi SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
  tier: observed
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
    agent_readiness: 38.4
    band: exemplar
    in_catalog: true
    kin_score: 73.3
    mcp: &id121
      status: none
    slug: umami
    status: profiled
    tags: &id122
    - Cookieless Tracking
    - Open Source
    - Privacy
    - Web Analytics
    url: /providers/umami/
  layer: domain
  name: Umami
  provider: umami
  says: ships the Umami SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 13.7
    band: emerging
    in_catalog: true
    kin_score: 14.1
    mcp: &id123
      status: none
    slug: unraid
    status: profiled
    tags: &id124
    - Docker
    - Network Attached Storage
    - Operating System
    - Virtual Machines
    url: /providers/unraid/
  layer: domain
  name: Unraid
  provider: unraid
  says: ships the Unraid SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 21.3
    band: emerging
    in_catalog: true
    kin_score: 18.5
    mcp: &id125
      status: none
    slug: uptime-kuma
    status: profiled
    tags: &id126
    - Dashboards
    - Monitoring
    - Open Source
    - Self-Hosted
    url: /providers/uptime-kuma/
  layer: domain
  name: Uptime Kuma
  provider: uptime-kuma
  says: ships the Uptime Kuma SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 14.3
    mcp: &id127
      status: none
    slug: wazuh
    status: profiled
    tags: &id128
    - Company
    - Open Source
    - Security
    - XDR
    url: /providers/wazuh/
  layer: domain
  name: Wazuh
  provider: wazuh
  says: ships the Wazuh SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
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
    agent_readiness: 6.5
    band: emerging
    in_catalog: true
    kin_score: 15.6
    mcp: &id129
      status: none
    slug: whats-up-docker
    status: profiled
    tags: &id130
    - Company
    - Container Management
    - Docker
    - Kubernetes
    url: /providers/whats-up-docker/
  layer: domain
  name: What's Up Docker
  provider: whats-up-docker
  says: ships the What's Up Docker SDK or integration code
  source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/personal-dashboard-homelab/homarr/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id001
  name: AdGuard Home
  slug: adguard
  status: profiled
  tags: *id002
  url: /providers/adguard/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: emerging
  in_catalog: true
  kin_score: 16.5
  mcp: *id003
  name: Audiobookshelf
  slug: audiobookshelf
  status: profiled
  tags: *id004
  url: /providers/audiobookshelf/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.7
  mcp: *id005
  name: Bazarr
  slug: bazarr
  status: profiled
  tags: *id006
  url: /providers/bazarr/
- agent_band: agent-aware
  agent_readiness: 17.1
  band: emerging
  in_catalog: true
  kin_score: 12.6
  mcp: *id007
  name: Beszel
  slug: beszel
  status: profiled
  tags: *id008
  url: /providers/beszel/
- agent_band: agent-aware
  agent_readiness: 18.2
  band: thin
  in_catalog: true
  kin_score: 27.3
  mcp: *id009
  name: Caddy
  slug: caddy
  status: profiled
  tags: *id010
  url: /providers/caddy/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id011
  name: changedetection.io
  slug: changedetection-io
  status: profiled
  tags: *id012
  url: /providers/changedetection-io/
- agent_band: agent-aware
  agent_readiness: 27.5
  band: developing
  in_catalog: true
  kin_score: 51.6
  mcp: *id013
  name: Coolify
  slug: coolify
  status: profiled
  tags: *id014
  url: /providers/coolify/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 21.1
  mcp: *id015
  name: Deluge
  slug: deluge
  status: profiled
  tags: *id016
  url: /providers/deluge/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 14.1
  mcp: *id017
  name: Emby
  slug: emby
  status: profiled
  tags: *id018
  url: /providers/emby/
- agent_band: agent-aware
  agent_readiness: 20.1
  band: emerging
  in_catalog: true
  kin_score: 20.5
  mcp: *id019
  name: Frigate NVR
  slug: frigate
  status: profiled
  tags: *id020
  url: /providers/frigate/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.1
  mcp: *id021
  name: Gatus
  slug: gatus
  status: profiled
  tags: *id022
  url: /providers/gatus/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id023
  name: GitHub
  slug: github
  status: profiled
  tags: *id024
  url: /providers/github/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id025
  name: Glances
  slug: glances
  status: profiled
  tags: *id026
  url: /providers/glances/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.7
  mcp: *id027
  name: Gluetun
  slug: gluetun
  status: profiled
  tags: *id028
  url: /providers/gluetun/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.8
  mcp: *id029
  name: Gotify
  slug: gotify
  status: profiled
  tags: *id030
  url: /providers/gotify/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: thin
  in_catalog: true
  kin_score: 32.9
  mcp: *id031
  name: Healthchecks.io
  slug: healthchecks-io
  status: profiled
  tags: *id032
  url: /providers/healthchecks-io/
- agent_band: human-only
  agent_readiness: 5.0
  band: emerging
  in_catalog: true
  kin_score: 22.2
  mcp: *id033
  name: Home Assistant
  slug: home-assistant
  status: profiled
  tags: *id034
  url: /providers/home-assistant/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: emerging
  in_catalog: true
  kin_score: 22.3
  mcp: *id035
  name: Immich
  slug: immich
  status: profiled
  tags: *id036
  url: /providers/immich/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: emerging
  in_catalog: true
  kin_score: 17.2
  mcp: *id037
  name: Jackett
  slug: jackett
  status: profiled
  tags: *id038
  url: /providers/jackett/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: emerging
  in_catalog: true
  kin_score: 16.7
  mcp: *id039
  name: Jellyfin
  slug: jellyfin
  status: profiled
  tags: *id040
  url: /providers/jellyfin/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id041
  name: Jellyseerr
  slug: jellyseerr
  status: queued for profiling
  tags: *id042
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.5
  mcp: *id043
  name: Jellystat
  slug: jellystat
  status: profiled
  tags: *id044
  url: /providers/jellystat/
- agent_band: agent-aware
  agent_readiness: 20.1
  band: thin
  in_catalog: true
  kin_score: 30.8
  mcp: *id045
  name: Karakeep
  slug: karakeep
  status: profiled
  tags: *id046
  url: /providers/karakeep/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 10.1
  mcp: *id047
  name: Komga
  slug: komga
  status: profiled
  tags: *id048
  url: /providers/komga/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 10.0
  mcp: *id049
  name: Lidarr
  slug: lidarr
  status: profiled
  tags: *id050
  url: /providers/lidarr/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 41.5
  mcp: *id051
  name: Linkwarden
  slug: linkwarden
  status: profiled
  tags: *id052
  url: /providers/linkwarden/
- agent_band: agent-ready
  agent_readiness: 29.7
  band: developing
  in_catalog: true
  kin_score: 41.5
  mcp: *id053
  name: Mealie
  slug: mealie
  status: profiled
  tags: *id054
  url: /providers/mealie/
- agent_band: agent-aware
  agent_readiness: 15.0
  band: emerging
  in_catalog: true
  kin_score: 20.9
  mcp: *id055
  name: Miniflux
  slug: miniflux
  status: profiled
  tags: *id056
  url: /providers/miniflux/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id057
  name: Navidrome
  slug: navidrome
  status: profiled
  tags: *id058
  url: /providers/navidrome/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: thin
  in_catalog: true
  kin_score: 38.1
  mcp: *id059
  name: Netdata
  slug: netdata
  status: profiled
  tags: *id060
  url: /providers/netdata/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 33.0
  mcp: *id061
  name: Nextcloud
  slug: nextcloud
  status: profiled
  tags: *id062
  url: /providers/nextcloud/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.9
  mcp: *id063
  name: ntfy
  slug: ntfy
  status: profiled
  tags: *id064
  url: /providers/ntfy/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.1
  mcp: *id065
  name: NZBGet
  slug: nzbget
  status: profiled
  tags: *id066
  url: /providers/nzbget/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 12.5
  mcp: *id067
  name: openmediavault
  slug: openmediavault
  status: profiled
  tags: *id068
  url: /providers/openmediavault/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: emerging
  in_catalog: true
  kin_score: 25.2
  mcp: *id069
  name: OPNsense
  slug: opnsense
  status: profiled
  tags: *id070
  url: /providers/opnsense/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id071
  name: Overseerr
  slug: overseerr
  status: queued for profiling
  tags: *id072
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.3
  mcp: *id073
  name: Paperless-ngx
  slug: paperless-ngx
  status: profiled
  tags: *id074
  url: /providers/paperless-ngx/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: emerging
  in_catalog: true
  kin_score: 22.9
  mcp: *id075
  name: Pi-hole
  slug: pi-hole
  status: profiled
  tags: *id076
  url: /providers/pi-hole/
- agent_band: agent-ready
  agent_readiness: 59.6
  band: strong
  in_catalog: true
  kin_score: 55.9
  mcp: *id077
  name: Plex
  slug: plex
  status: profiled
  tags: *id078
  url: /providers/plex/
- agent_band: agent-aware
  agent_readiness: 18.7
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id079
  name: Prometheus
  slug: prometheus-io
  status: profiled
  tags: *id080
  url: /providers/prometheus-io/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 34.7
  mcp: *id081
  name: Prowlarr
  slug: prowlarr
  status: profiled
  tags: *id082
  url: /providers/prowlarr/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 27.4
  mcp: *id083
  name: Proxmox VE
  slug: proxmox
  status: profiled
  tags: *id084
  url: /providers/proxmox/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.1
  mcp: *id085
  name: qBittorrent
  slug: qbittorrent
  status: profiled
  tags: *id086
  url: /providers/qbittorrent/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 8.2
  mcp: *id087
  name: Radarr
  slug: radarr
  status: profiled
  tags: *id088
  url: /providers/radarr/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id089
  name: Readarr
  slug: readarr
  status: queued for profiling
  tags: *id090
  url: null
- agent_band: agent-ready
  agent_readiness: 33.1
  band: thin
  in_catalog: true
  kin_score: 37.3
  mcp: *id091
  name: RomM
  slug: romm
  status: profiled
  tags: *id092
  url: /providers/romm/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: emerging
  in_catalog: true
  kin_score: 19.1
  mcp: *id093
  name: SABnzbd
  slug: sabnzbd
  status: profiled
  tags: *id094
  url: /providers/sabnzbd/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: emerging
  in_catalog: true
  kin_score: 14.5
  mcp: *id095
  name: Scrutiny
  slug: scrutiny
  status: profiled
  tags: *id096
  url: /providers/scrutiny/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 28.5
  mcp: *id097
  name: Sonarr
  slug: sonarr
  status: profiled
  tags: *id098
  url: /providers/sonarr/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: emerging
  in_catalog: true
  kin_score: 20.2
  mcp: *id099
  name: Speedtest Tracker
  slug: speedtest-tracker
  status: profiled
  tags: *id100
  url: /providers/speedtest-tracker/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: emerging
  in_catalog: true
  kin_score: 16.4
  mcp: *id101
  name: Spoolman
  slug: spoolman
  status: profiled
  tags: *id102
  url: /providers/spoolman/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.6
  mcp: *id103
  name: Stash
  slug: stashapp
  status: profiled
  tags: *id104
  url: /providers/stashapp/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: minimal
  in_catalog: true
  kin_score: 7.5
  mcp: *id105
  name: Synology
  slug: synology
  status: profiled
  tags: *id106
  url: /providers/synology/
- agent_band: agent-aware
  agent_readiness: 26.7
  band: strong
  in_catalog: true
  kin_score: 61.0
  mcp: *id107
  name: Tandoor Recipes
  slug: tandoor
  status: profiled
  tags: *id108
  url: /providers/tandoor/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 5.2
  mcp: *id109
  name: Tdarr
  slug: tdarr
  status: profiled
  tags: *id110
  url: /providers/tdarr/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.0
  mcp: *id111
  name: Technitium DNS Server
  slug: technitium
  status: profiled
  tags: *id112
  url: /providers/technitium/
- agent_band: agent-aware
  agent_readiness: 24.5
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id113
  name: Traefik
  slug: traefik
  status: profiled
  tags: *id114
  url: /providers/traefik/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.4
  mcp: *id115
  name: Transmission
  slug: transmission-bt
  status: profiled
  tags: *id116
  url: /providers/transmission-bt/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: emerging
  in_catalog: true
  kin_score: 14.1
  mcp: *id117
  name: TrueNAS
  slug: truenas
  status: profiled
  tags: *id118
  url: /providers/truenas/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: developing
  in_catalog: true
  kin_score: 46.3
  mcp: *id119
  name: Ubiquiti UniFi
  slug: ubiquiti
  status: profiled
  tags: *id120
  url: /providers/ubiquiti/
- agent_band: agent-ready
  agent_readiness: 38.4
  band: exemplar
  in_catalog: true
  kin_score: 73.3
  mcp: *id121
  name: Umami
  slug: umami
  status: profiled
  tags: *id122
  url: /providers/umami/
- agent_band: agent-aware
  agent_readiness: 13.7
  band: emerging
  in_catalog: true
  kin_score: 14.1
  mcp: *id123
  name: Unraid
  slug: unraid
  status: profiled
  tags: *id124
  url: /providers/unraid/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: emerging
  in_catalog: true
  kin_score: 18.5
  mcp: *id125
  name: Uptime Kuma
  slug: uptime-kuma
  status: profiled
  tags: *id126
  url: /providers/uptime-kuma/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 14.3
  mcp: *id127
  name: Wazuh
  slug: wazuh
  status: profiled
  tags: *id128
  url: /providers/wazuh/
- agent_band: agent-aware
  agent_readiness: 6.5
  band: emerging
  in_catalog: true
  kin_score: 15.6
  mcp: *id129
  name: What's Up Docker
  slug: whats-up-docker
  status: profiled
  tags: *id130
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
- name: Homepage
  rows: 102
  url: /applications/personal-dashboard-homelab/homepage/
- name: Homer
  rows: 43
  url: /applications/personal-dashboard-homelab/homer/
sitemap: true
title: 'Homarr: Personal Dashboard & Homelab reference app'
---
