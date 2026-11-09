---
access: understanding
agent_layer: []
apps:
- anchor: homepage
  counts:
    declared: 0
    observed: 102
  evidence:
  - route: source code
    url: https://github.com/gethomepage/homepage/tree/main/src/widgets
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: AdGuard Home
    provider: adguard
    says: ships the AdGuard Home SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.40
      key: deployment-orchestration
      name: Deployment Orchestration
      url: /capabilities/deployment-orchestration/
      via_parent: null
    credit: null
    layer: domain
    name: Argo CD
    provider: argocd
    says: ships the Argo CD SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Audiobookshelf
    provider: audiobookshelf
    says: ships the Audiobookshelf SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Authentik
    provider: authentik
    says: ships the Authentik SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-160.20.20
      key: BC-160.20.20
      name: Backup and Restore Management
      url: /capabilities/disaster-recovery-management/
      via_parent: Disaster Recovery Management
    credit: null
    layer: domain
    name: Backrest
    provider: backrest
    says: ships the Backrest SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Bazarr
    provider: bazarr
    says: ships the Bazarr SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Beszel
    provider: beszel
    says: ships the Beszel SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: Caddy
    provider: caddy
    says: ships the Caddy SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2630.20
      key: service-performance-monitoring
      name: Service Performance Monitoring
      url: /capabilities/service-performance-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: changedetection.io
    provider: changedetection-io
    says: ships the changedetection.io SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: Cloudflare (Tunnel)
    provider: cloudflare
    says: ships the Cloudflare (Tunnel) SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20
      key: AE-230.20
      name: Market & Financial Data
      url: /capabilities/market-financial-data/
      via_parent: null
    credit: null
    layer: domain
    name: CoinMarketCap
    provider: coinmarketcap
    says: ships the CoinMarketCap SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: CrowdSec
    provider: crowdsec
    says: ships the CrowdSec SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90.10
      key: AE-170.90.10
      name: BitTorrent & Usenet Download Clients
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: Self-Hosted Media Servers & Library Automation
    credit: null
    layer: domain
    name: Deluge
    provider: deluge
    says: ships the Deluge SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: Docker
    provider: docker
    says: ships the Docker SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-160.20.20
      key: BC-160.20.20
      name: Backup and Restore Management
      url: /capabilities/disaster-recovery-management/
      via_parent: Disaster Recovery Management
    credit: null
    layer: domain
    name: Duplicati
    provider: duplicati
    says: ships the Duplicati SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Emby
    provider: emby
    says: ships the Emby SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.10
      key: AE-200.10
      name: Smart Home
      url: /capabilities/smart-home/
      via_parent: null
    credit: null
    layer: domain
    name: ESPHome
    provider: esphome
    says: ships the ESPHome SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.20
      key: AE-200.20.20
      name: EV Charging
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: evcc
    provider: evcc
    says: ships the evcc SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: File Browser
    provider: filebrowser
    says: ships the File Browser SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-190.10
      key: AE-190.10
      name: Budgeting & Money Management
      url: /capabilities/budgeting-money-management/
      via_parent: null
    credit: null
    layer: domain
    name: Firefly III
    provider: firefly-iii
    says: ships the Firefly III SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: FreshRSS
    provider: freshrss
    says: ships the FreshRSS SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2340.50
      key: physical-security-surveillance-management
      name: Physical Security & Surveillance Management
      url: /capabilities/physical-security-surveillance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Frigate NVR
    provider: frigate
    says: ships the Frigate NVR SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2630.20
      key: service-performance-monitoring
      name: Service Performance Monitoring
      url: /capabilities/service-performance-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Gatus
    provider: gatus
    says: ships the Gatus SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-190.30
      key: AE-190.30
      name: Retail Investing
      url: /capabilities/retail-investing/
      via_parent: null
    credit: null
    layer: domain
    name: Ghostfolio
    provider: ghostfolio
    says: ships the Ghostfolio SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40.10
      key: BC-4200.40.10
      name: Source Code Management
      url: /capabilities/software-construction-management/
      via_parent: Software Construction Management
    credit: null
    layer: domain
    name: Gitea
    provider: gitea
    says: ships the Gitea SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40.10
      key: BC-4200.40.10
      name: Source Code Management
      url: /capabilities/software-construction-management/
      via_parent: Software Construction Management
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Glances
    provider: glances
    says: ships the Glances SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: Gluetun
    provider: gluetun
    says: ships the Gluetun SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: domain
    name: Gotify
    provider: gotify
    says: ships the Gotify SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Grafana
    provider: grafana-com
    says: ships the Grafana SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: Headscale
    provider: headscale
    says: ships the Headscale SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2630.20
      key: service-performance-monitoring
      name: Service Performance Monitoring
      url: /capabilities/service-performance-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Healthchecks.io
    provider: healthchecks-io
    says: ships the Healthchecks.io SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.10
      key: AE-200.10
      name: Smart Home
      url: /capabilities/smart-home/
      via_parent: null
    credit: null
    layer: domain
    name: Home Assistant
    provider: home-assistant
    says: ships the Home Assistant SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.10
      key: AE-200.10
      name: Smart Home
      url: /capabilities/smart-home/
      via_parent: null
    credit: null
    layer: domain
    name: Homebridge
    provider: homebridge
    says: ships the Homebridge SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.20
      key: AE-170.30.20
      name: Photo Sharing
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Immich
    provider: immich
    says: ships the Immich SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90.10
      key: AE-170.90.10
      name: BitTorrent & Usenet Download Clients
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: Self-Hosted Media Servers & Library Automation
    credit: null
    layer: domain
    name: Jackett
    provider: jackett
    says: ships the Jackett SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Jellyfin
    provider: jellyfin
    says: ships the Jellyfin SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Jellystat
    provider: jellystat
    says: ships the Jellystat SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Karakeep
    provider: karakeep
    says: ships the Karakeep SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Kavita
    provider: kavita
    says: ships the Kavita SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Komga
    provider: komga
    says: ships the Komga SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-160.20.20
      key: BC-160.20.20
      name: Backup and Restore Management
      url: /capabilities/disaster-recovery-management/
      via_parent: Disaster Recovery Management
    credit: null
    layer: domain
    name: Kopia
    provider: kopia
    says: ships the Kopia SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: Kubernetes
    provider: kubernetes
    says: ships the Kubernetes SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Lidarr
    provider: lidarr
    says: ships the Lidarr SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Linkwarden
    provider: linkwarden
    says: ships the Linkwarden SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-926
      key: AE-926
      name: Web Hosting & Control Panels
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: mailcow
    provider: mailcow
    says: ships the mailcow SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.10
      key: AE-170.50.10
      name: Online Communities
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    credit: null
    layer: domain
    name: Mastodon
    provider: mastodon
    says: ships the Mastodon SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.30.20
      key: AE-130.30.20
      name: Recipe & Meal Planning
      url: /capabilities/nutrition-food-data/
      via_parent: Nutrition & Food Data
    credit: null
    layer: domain
    name: Mealie
    provider: mealie
    says: ships the Mealie SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Medusa (TV)
    provider: pymedusa
    says: ships the Medusa (TV) SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: MikroTik
    provider: mikrotik
    says: ships the MikroTik SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Miniflux
    provider: miniflux
    says: ships the Miniflux SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.70
      key: AE-200.70
      name: 3D Printing & Printer Control
      url: /capabilities/3d-printing-printer-control/
      via_parent: null
    credit: null
    layer: domain
    name: Moonraker (Klipper)
    provider: moonraker
    says: ships the Moonraker (Klipper) SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Navidrome
    provider: navidrome
    says: ships the Navidrome SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: NetBird
    provider: netbird
    says: ships the NetBird SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Netdata
    provider: netdata
    says: ships the Netdata SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Nextcloud
    provider: nextcloud
    says: ships the Nextcloud SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: NextDNS
    provider: nextdns
    says: ships the NextDNS SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: Nginx Proxy Manager
    provider: nginx-proxy-manager
    says: ships the Nginx Proxy Manager SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: domain
    name: ntfy
    provider: ntfy
    says: ships the ntfy SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90.10
      key: AE-170.90.10
      name: BitTorrent & Usenet Download Clients
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: Self-Hosted Media Servers & Library Automation
    credit: null
    layer: domain
    name: NZBGet
    provider: nzbget
    says: ships the NZBGet SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.70
      key: AE-200.70
      name: 3D Printing & Printer Control
      url: /capabilities/3d-printing-printer-control/
      via_parent: null
    credit: null
    layer: domain
    name: OctoPrint
    provider: octoprint
    says: ships the OctoPrint SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: openmediavault
    provider: openmediavault
    says: ships the openmediavault SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: OpenWrt
    provider: openwrt
    says: ships the OpenWrt SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: OPNsense
    provider: opnsense
    says: ships the OPNsense SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Overseerr
    provider: overseerr
    says: ships the Overseerr SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-917
      key: AE-917
      name: Enterprise Content & Document Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Paperless-ngx
    provider: paperless-ngx
    says: ships the Paperless-ngx SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: pfSense
    provider: pfsense
    says: ships the pfSense SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.20
      key: AE-170.30.20
      name: Photo Sharing
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: PhotoPrism
    provider: photoprism
    says: ships the PhotoPrism SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: Pi-hole
    provider: pi-hole
    says: ships the Pi-hole SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Plex
    provider: plex
    says: ships the Plex SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: Portainer
    provider: portainer
    says: ships the Portainer SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Prometheus
    provider: prometheus-io
    says: ships the Prometheus SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90.10
      key: AE-170.90.10
      name: BitTorrent & Usenet Download Clients
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: Self-Hosted Media Servers & Library Automation
    credit: null
    layer: domain
    name: Prowlarr
    provider: prowlarr
    says: ships the Prowlarr SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: Proxmox VE
    provider: proxmox
    says: ships the Proxmox VE SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.20.20
      key: AE-180.20.20
      name: Game Server Hosting
      url: /capabilities/game-backend-services/
      via_parent: Game Backend Services
    credit: null
    layer: domain
    name: Pterodactyl
    provider: pterodactyl
    says: ships the Pterodactyl SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90.10
      key: AE-170.90.10
      name: BitTorrent & Usenet Download Clients
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: Self-Hosted Media Servers & Library Automation
    credit: null
    layer: domain
    name: qBittorrent
    provider: qbittorrent
    says: ships the qBittorrent SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: QNAP
    provider: qnap
    says: ships the QNAP SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Radarr
    provider: radarr
    says: ships the Radarr SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Readarr
    provider: readarr
    says: ships the Readarr SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: RomM
    provider: romm
    says: ships the RomM SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90.10
      key: AE-170.90.10
      name: BitTorrent & Usenet Download Clients
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: Self-Hosted Media Servers & Library Automation
    credit: null
    layer: domain
    name: SABnzbd
    provider: sabnzbd
    says: ships the SABnzbd SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Scrutiny
    provider: scrutiny
    says: ships the Scrutiny SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Sonarr
    provider: sonarr
    says: ships the Sonarr SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Speedtest Tracker
    provider: speedtest-tracker
    says: ships the Speedtest Tracker SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.70
      key: AE-200.70
      name: 3D Printing & Printer Control
      url: /capabilities/3d-printing-printer-control/
      via_parent: null
    credit: null
    layer: domain
    name: Spoolman
    provider: spoolman
    says: ships the Spoolman SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Stash
    provider: stashapp
    says: ships the Stash SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Syncthing
    provider: syncthing
    says: ships the Syncthing SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: Synology
    provider: synology
    says: ships the Synology SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: Tailscale
    provider: tailscale
    says: ships the Tailscale SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.30.20
      key: AE-130.30.20
      name: Recipe & Meal Planning
      url: /capabilities/nutrition-food-data/
      via_parent: Nutrition & Food Data
    credit: null
    layer: domain
    name: Tandoor Recipes
    provider: tandoor
    says: ships the Tandoor Recipes SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Tautulli
    provider: tautulli
    says: ships the Tautulli SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    credit: null
    layer: domain
    name: Tdarr
    provider: tdarr
    says: ships the Tdarr SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: Technitium DNS Server
    provider: technitium
    says: ships the Technitium DNS Server SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: Traefik
    provider: traefik
    says: ships the Traefik SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90.10
      key: AE-170.90.10
      name: BitTorrent & Usenet Download Clients
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: Self-Hosted Media Servers & Library Automation
    credit: null
    layer: domain
    name: Transmission
    provider: transmission-bt
    says: ships the Transmission SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: TrueNAS
    provider: truenas
    says: ships the TrueNAS SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: Ubiquiti UniFi
    provider: ubiquiti
    says: ships the Ubiquiti UniFi SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: Unraid
    provider: unraid
    says: ships the Unraid SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2630.20
      key: service-performance-monitoring
      name: Service Performance Monitoring
      url: /capabilities/service-performance-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Uptime Kuma
    provider: uptime-kuma
    says: ships the Uptime Kuma SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2630.20
      key: service-performance-monitoring
      name: Service Performance Monitoring
      url: /capabilities/service-performance-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: UptimeRobot
    provider: uptimerobot
    says: ships the UptimeRobot SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: What's Up Docker
    provider: whats-up-docker
    says: ships the What's Up Docker SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zabbix
    provider: zabbix
    says: ships the Zabbix SDK or integration code
    source: https://github.com/gethomepage/homepage/tree/main/src/widgets
    tier: observed
  kind: self-hosted
  name: Homepage
  page: /applications/personal-dashboard-homelab/homepage/
  slug: homepage
  url: https://github.com/gethomepage/homepage
- anchor: homarr
  counts:
    declared: 0
    observed: 65
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
    layer: domain
    name: What's Up Docker
    provider: whats-up-docker
    says: ships the What's Up Docker SDK or integration code
    source: https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
    tier: observed
  kind: self-hosted
  name: Homarr
  page: /applications/personal-dashboard-homelab/homarr/
  slug: homarr
  url: https://github.com/homarr-labs/homarr
- anchor: dashy
  counts:
    declared: 0
    observed: 35
  evidence:
  - route: source code
    url: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
  - route: source code
    url: https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10
      key: AE-150.10
      name: Email
      url: /capabilities/email/
      via_parent: null
    credit: null
    layer: domain
    name: addy.io
    provider: addy-io
    says: ships the addy.io SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: AdGuard Home
    provider: adguard
    says: ships the AdGuard Home SDK or integration code
    source: https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-210.10
      key: AE-210.10
      name: Flight Search & Booking
      url: /capabilities/flight-search-booking/
      via_parent: null
    credit: null
    layer: domain
    name: AeroDataBox (via RapidAPI)
    provider: aerodatabox
    says: ships the AeroDataBox (via RapidAPI) SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.20
      key: AE-230.20.20
      name: Securities Market Data
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    credit: null
    layer: domain
    name: Alpha Vantage
    provider: alpha-vantage
    says: ships the Alpha Vantage SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-240.30.10
      key: AE-240.30.10
      name: Blockchain Indexing
      url: /capabilities/on-chain-data-indexing/
      via_parent: On-Chain Data & Indexing
    credit: null
    layer: domain
    name: BlockCypher
    provider: blockcypher
    says: ships the BlockCypher SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20
      key: AE-230.20
      name: Market & Financial Data
      url: /capabilities/market-financial-data/
      via_parent: null
    credit: null
    layer: domain
    name: CoinGecko
    provider: coingecko
    says: ships the CoinGecko SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.10
      key: AE-170.60.10
      name: News Data
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Currents API
    provider: currents
    says: ships the Currents API SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.50
      key: AE-230.50
      name: Open Government Data
      url: /capabilities/open-government-data/
      via_parent: null
    credit: null
    layer: domain
    name: disease.sh
    provider: disease-sh
    says: ships the disease.sh SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.70
      key: AE-230.70
      name: Calendar & Holiday Data
      url: /capabilities/calendar-holiday-data/
      via_parent: null
    credit: null
    layer: domain
    name: Enrico holiday service
    provider: enrico
    says: ships the Enrico holiday service SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.10
      key: AE-230.20.10
      name: Exchange Rates
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    credit: null
    layer: domain
    name: ExchangeRate-API
    provider: exchangerate-api
    says: ships the ExchangeRate-API SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40.10
      key: BC-4200.40.10
      name: Source Code Management
      url: /capabilities/software-construction-management/
      via_parent: Software Construction Management
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Glances
    provider: glances
    says: ships the Glances SDK or integration code
    source: https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: Gluetun
    provider: gluetun
    says: ships the Gluetun SDK or integration code
    source: https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.10
      key: AE-170.50.10
      name: Online Communities
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    credit: null
    layer: domain
    name: Hacker News
    provider: hacker-news
    says: ships the Hacker News SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2630.20
      key: service-performance-monitoring
      name: Service Performance Monitoring
      url: /capabilities/service-performance-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Healthchecks.io
    provider: healthchecks-io
    says: ships the Healthchecks.io SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: domain
    name: ip-api
    provider: ip-api
    says: ships the ip-api SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: domain
    name: IPGeolocation.io
    provider: ipgeolocation
    says: ships the IPGeolocation.io SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: domain
    name: ipify
    provider: ipify
    says: ships the ipify SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: domain
    name: IPinfo
    provider: ipinfo
    says: ships the IPinfo SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: linkding
    provider: linkding
    says: ships the linkding SDK or integration code
    source: https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: Mullvad VPN
    provider: mullvad
    says: ships the Mullvad VPN SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.40
      key: AE-210.30.40
      name: Public Transit Data
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: MVG (Munich transit)
    provider: mvg
    says: ships the MVG (Munich transit) SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Netdata
    provider: netdata
    says: ships the Netdata SDK or integration code
    source: https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Nextcloud
    provider: nextcloud
    says: ships the Nextcloud SDK or integration code
    source: https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: domain
    name: ntfy
    provider: ntfy
    says: ships the ntfy SDK or integration code
    source: https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: BC-620.40
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: NVD
    provider: nvd
    says: ships the NVD SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: OpenWeatherMap
    provider: openweathermap
    says: ships the OpenWeatherMap SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    credit: null
    layer: domain
    name: Pi-hole
    provider: pi-hole
    says: ships the Pi-hole SDK or integration code
    source: https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: Proxmox VE
    provider: proxmox
    says: ships the Proxmox VE SDK or integration code
    source: https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90.10
      key: AE-170.90.10
      name: BitTorrent & Usenet Download Clients
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: Self-Hosted Media Servers & Library Automation
    credit: null
    layer: domain
    name: SABnzbd
    provider: sabnzbd
    says: ships the SABnzbd SDK or integration code
    source: https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: Synology
    provider: synology
    says: ships the Synology SDK or integration code
    source: https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.80.40
      key: AE-180.80.40
      name: Sports Data
      url: /capabilities/sports-betting-fantasy/
      via_parent: Sports, Betting & Fantasy
    credit: null
    layer: domain
    name: TheSportsDB
    provider: sportsdb
    says: ships the TheSportsDB SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.40
      key: AE-210.30.40
      name: Public Transit Data
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Transport for London
    provider: transport-for-london-england
    says: ships the Transport for London SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2630.20
      key: service-performance-monitoring
      name: Service Performance Monitoring
      url: /capabilities/service-performance-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Uptime Kuma
    provider: uptime-kuma
    says: ships the Uptime Kuma SDK or integration code
    source: https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: WhoAPI
    provider: whoapi
    says: ships the WhoAPI SDK or integration code
    source: https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
    tier: observed
  kind: self-hosted
  name: Dashy
  page: /applications/personal-dashboard-homelab/dashy/
  slug: dashy
  url: https://github.com/Lissy93/dashy
- anchor: glance
  counts:
    declared: 0
    observed: 16
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
    layer: domain
    name: YouTube
    provider: youtube
    says: ships the YouTube SDK or integration code
    source: https://github.com/glanceapp/glance/tree/main/internal/glance/widget-videos.go
    tier: observed
  kind: self-hosted
  name: Glance
  page: /applications/personal-dashboard-homelab/glance/
  slug: glance
  url: https://github.com/glanceapp/glance
- anchor: homer
  counts:
    declared: 0
    observed: 43
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
    layer: domain
    name: What's Up Docker
    provider: whats-up-docker
    says: ships the What's Up Docker SDK or integration code
    source: https://github.com/bastienwirtz/homer/tree/main/src/components/services
    tier: observed
  kind: self-hosted
  name: Homer
  page: /applications/personal-dashboard-homelab/homer/
  slug: homer
  url: https://github.com/bastienwirtz/homer
- anchor: casaos
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: dependency manifest
    url: https://github.com/IceWhaleTech/CasaOS/blob/main/go.mod
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4200.40.10
      key: BC-4200.40.10
      name: Source Code Management
      url: /capabilities/software-construction-management/
      via_parent: Software Construction Management
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/IceWhaleTech/CasaOS/blob/main/go.mod
    tier: observed
  kind: self-hosted
  name: CasaOS
  page: /applications/personal-dashboard-homelab/casaos/
  slug: casaos
  url: https://github.com/IceWhaleTech/CasaOS
author: API Evangelist
candidates: []
credits: []
html: public
id: personal-dashboard-homelab
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Utilities
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Tools
  store: google-play
  url: https://play.google.com/store/apps/category/TOOLS
- category: Personal Dashboards
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#personal-dashboards
- category: Self-hosting Solutions
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#self-hosting-solutions
name: Personal Dashboard & Homelab
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-200.60
    key: AE-200.60
    name: Home Network & DNS Filtering
    url: /capabilities/home-network-dns-filtering/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for AdGuard Home, Caddy, Cloudflare (Tunnel), Gluetun, Headscale, MikroTik ...
- capability:
    attribution: Turbo EA
    id: BC-4210.40
    key: deployment-orchestration
    name: Deployment Orchestration
    url: /capabilities/deployment-orchestration/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for Argo CD
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for Audiobookshelf
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for Authentik
- capability:
    attribution: Turbo EA
    id: BC-160.20.20
    key: BC-160.20.20
    name: Backup and Restore Management
    url: /capabilities/disaster-recovery-management/
    via_parent: Disaster Recovery Management
  fit: exact
  layer: domain
  why: dashboard widgets for Backrest, Duplicati, Kopia
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for Bazarr, Deluge, Emby, Jackett, Jellyfin, Jellystat ...
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for Beszel, Glances, Grafana, Netdata, Prometheus, Scrutiny ...
- capability:
    attribution: Turbo EA
    id: BC-2630.20
    key: service-performance-monitoring
    name: Service Performance Monitoring
    url: /capabilities/service-performance-monitoring/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for changedetection.io, Gatus, Healthchecks.io, Uptime Kuma, UptimeRobot
- capability:
    attribution: API Evangelist extension
    id: AE-230.20
    key: AE-230.20
    name: Market & Financial Data
    url: /capabilities/market-financial-data/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for CoinMarketCap, CoinGecko
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for CrowdSec, Wazuh
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: dashboard widgets for Synology, Kubernetes, openmediavault, Portainer, Proxmox VE, QNAP ...
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for ESPHome, Home Assistant, Homebridge, openHAB
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.20
    key: AE-200.20.20
    name: EV Charging
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  fit: exact
  layer: domain
  why: dashboard widgets for evcc
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: dashboard widgets for File Browser, Nextcloud, Syncthing
- capability:
    attribution: API Evangelist extension
    id: AE-190.10
    key: AE-190.10
    name: Budgeting & Money Management
    url: /capabilities/budgeting-money-management/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for Firefly III
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.10
    key: AE-170.60.10
    name: News Data
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  fit: nearest
  layer: domain
  why: dashboard widgets for FreshRSS, Miniflux, Currents API
- capability:
    attribution: Turbo EA
    id: BC-2340.50
    key: physical-security-surveillance-management
    name: Physical Security & Surveillance Management
    url: /capabilities/physical-security-surveillance-management/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for Frigate NVR
- capability:
    attribution: API Evangelist extension
    id: AE-190.30
    key: AE-190.30
    name: Retail Investing
    url: /capabilities/retail-investing/
    via_parent: null
  fit: nearest
  layer: domain
  why: dashboard widgets for Ghostfolio
- capability:
    attribution: Turbo EA
    id: BC-4200.40.10
    key: BC-4200.40.10
    name: Source Code Management
    url: /capabilities/software-construction-management/
    via_parent: Software Construction Management
  fit: exact
  layer: domain
  why: dashboard widgets for Gitea, GitLab, GitHub, Codeberg
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for Gotify, ntfy
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.20
    key: AE-170.30.20
    name: Photo Sharing
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: domain
  why: dashboard widgets for Immich, PhotoPrism
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  fit: exact
  layer: domain
  why: dashboard widgets for Karakeep, Linkwarden, linkding, wallabag
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for Kavita, Komga
- capability:
    attribution: API Evangelist extension
    id: AE-150.10
    key: AE-150.10
    name: Email
    url: /capabilities/email/
    via_parent: null
  fit: nearest
  layer: domain
  why: dashboard widgets for mailcow, addy.io
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.10
    key: AE-170.50.10
    name: Online Communities
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  fit: exact
  layer: domain
  why: dashboard widgets for Mastodon, Hacker News, Reddit, Lobsters
- capability:
    attribution: API Evangelist extension
    id: AE-130.30.20
    key: AE-130.30.20
    name: Recipe & Meal Planning
    url: /capabilities/nutrition-food-data/
    via_parent: Nutrition & Food Data
  fit: exact
  layer: domain
  why: dashboard widgets for Mealie, Tandoor Recipes
- capability:
    attribution: API Evangelist extension
    id: AE-200.70
    key: AE-200.70
    name: 3D Printing & Printer Control
    url: /capabilities/3d-printing-printer-control/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for Moonraker (Klipper), OctoPrint, Spoolman
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for Navidrome
- capability:
    attribution: API Evangelist extension
    id: AE-917
    key: AE-917
    name: Enterprise Content & Document Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: domain
  why: dashboard widgets for Paperless-ngx
- capability:
    attribution: API Evangelist extension
    id: AE-180.20.20
    key: AE-180.20.20
    name: Game Server Hosting
    url: /capabilities/game-backend-services/
    via_parent: Game Backend Services
  fit: exact
  layer: domain
  why: dashboard widgets for Pterodactyl
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for RomM
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for Umami
- capability:
    attribution: Turbo EA
    id: BC-620.40
    key: BC-620.40
    name: Vulnerability Management
    url: /capabilities/vulnerability-management/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for NVD
- capability:
    attribution: API Evangelist extension
    id: AE-927
    key: AE-927
    name: Domain Registration & Managed DNS
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: nearest
  layer: domain
  why: dashboard widgets for WhoAPI
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.10
    key: AE-230.20.10
    name: Exchange Rates
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  fit: exact
  layer: domain
  why: dashboard widgets for ExchangeRate-API
- capability:
    attribution: API Evangelist extension
    id: AE-210.10
    key: AE-210.10
    name: Flight Search & Booking
    url: /capabilities/flight-search-booking/
    via_parent: null
  fit: nearest
  layer: domain
  why: dashboard widgets for AeroDataBox (via RapidAPI)
- capability:
    attribution: API Evangelist extension
    id: AE-230.70
    key: AE-230.70
    name: Calendar & Holiday Data
    url: /capabilities/calendar-holiday-data/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for Enrico holiday service
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.40
    key: AE-210.30.40
    name: Public Transit Data
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  fit: exact
  layer: domain
  why: dashboard widgets for MVG (Munich transit), Transport for London
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: domain
  why: dashboard widgets for ipify, IPGeolocation.io, ip-api, IPinfo
- capability:
    attribution: API Evangelist extension
    id: AE-180.80.40
    key: AE-180.80.40
    name: Sports Data
    url: /capabilities/sports-betting-fantasy/
    via_parent: Sports, Betting & Fantasy
  fit: exact
  layer: domain
  why: dashboard widgets for TheSportsDB
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.20
    key: AE-230.20.20
    name: Securities Market Data
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  fit: exact
  layer: domain
  why: dashboard widgets for Alpha Vantage, Yahoo Finance
- capability:
    attribution: API Evangelist extension
    id: AE-240.30.10
    key: AE-240.30.10
    name: Blockchain Indexing
    url: /capabilities/on-chain-data-indexing/
    via_parent: On-Chain Data & Indexing
  fit: exact
  layer: domain
  why: dashboard widgets for BlockCypher
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: AE-230.10
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboard widgets for OpenWeatherMap, Open-Meteo
- capability:
    attribution: API Evangelist extension
    id: AE-230.50
    key: AE-230.50
    name: Open Government Data
    url: /capabilities/open-government-data/
    via_parent: null
  fit: nearest
  layer: domain
  why: dashboard widgets for disease.sh
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  fit: exact
  layer: domain
  why: dashboard widgets for YouTube, Twitch
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  fit: exact
  layer: domain
  why: dashboard widgets for Docker Hub
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.6
      apps:
      - Homarr
      - Homepage
      - Homer
      band: strong
      in_catalog: true
      kin_score: 55.9
      mcp:
        status: none
      name: Plex
      slug: plex
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Company
      - Media
      - Streaming
      - Video
      tier: observed
      url: /providers/plex/
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - Homarr
      - Homepage
      - Homer
      band: thin
      in_catalog: true
      kin_score: 28.5
      mcp:
        status: none
      name: Sonarr
      slug: sonarr
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Company
      - PVR
      - TV
      - Usenet
      tier: observed
      url: /providers/sonarr/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Homarr
      - Homepage
      - Homer
      band: emerging
      in_catalog: true
      kin_score: 14.1
      mcp:
        status: none
      name: Emby
      slug: emby
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Media Server
      - Personal Media
      - Streaming
      - Video Library
      tier: observed
      url: /providers/emby/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Homarr
      - Homepage
      - Homer
      band: minimal
      in_catalog: true
      kin_score: 10.0
      mcp:
        status: none
      name: Lidarr
      slug: lidarr
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Automation
      - Media
      - Music
      - Open Source
      tier: observed
      url: /providers/lidarr/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Homarr
      - Homepage
      - Homer
      band: minimal
      in_catalog: true
      kin_score: 8.2
      mcp:
        status: unknown
      name: Radarr
      slug: radarr
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Automation
      - Media
      - Movie-Management
      - Open Source
      tier: observed
      url: /providers/radarr/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homarr
      - Homepage
      - Homer
      band: minimal
      in_catalog: true
      kin_score: 7.5
      mcp:
        status: unknown
      name: Jellystat
      slug: jellystat
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
      status: profiled
      tags:
      - Analytics
      - Company
      - Media
      - Open Source
      tier: observed
      url: /providers/jellystat/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Homarr
      - Homepage
      - Homer
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        status: unknown
      name: Tdarr
      slug: tdarr
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Automation
      - Company
      - Transcoding
      - Video
      tier: observed
      url: /providers/tdarr/
    - agent_band: null
      agent_readiness: null
      apps:
      - Homarr
      - Homepage
      - Homer
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Readarr
      slug: readarr
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Homarr
      - Homepage
      band: thin
      in_catalog: true
      kin_score: 37.3
      mcp:
        status: none
      name: RomM
      slug: romm
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
      status: profiled
      tags:
      - Company
      - Media Management
      - Open Source
      - Retro Gaming
      tier: observed
      url: /providers/romm/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Homarr
      - Homepage
      band: thin
      in_catalog: true
      kin_score: 30.5
      mcp:
        status: none
      name: Navidrome
      slug: navidrome
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Company
      - Music
      - Self-Hosted
      - Streaming
      tier: observed
      url: /providers/navidrome/
    - agent_band: agent-aware
      agent_readiness: 17.9
      apps:
      - Homarr
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 16.7
      mcp:
        status: none
      name: Jellyfin
      slug: jellyfin
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Community
      - FreeSoftware
      - Media
      - Open Source
      tier: observed
      url: /providers/jellyfin/
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - Homarr
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 16.5
      mcp:
        status: none
      name: Audiobookshelf
      slug: audiobookshelf
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Audiobooks
      - Company
      - Podcasts
      - Self-Hosted
      tier: observed
      url: /providers/audiobookshelf/
    - agent_band: human-only
      agent_readiness: 3.2
      apps:
      - Homepage
      - Homer
      band: emerging
      in_catalog: true
      kin_score: 13.1
      mcp:
        status: none
      name: Medusa (TV)
      slug: pymedusa
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Automation
      - Company
      - Media
      - TV
      tier: observed
      url: /providers/pymedusa/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homarr
      - Homepage
      band: minimal
      in_catalog: true
      kin_score: 10.6
      mcp:
        status: unknown
      name: Stash
      slug: stashapp
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
      status: profiled
      tags:
      - Adult
      - Company
      - Media
      - Open Source
      tier: observed
      url: /providers/stashapp/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Homarr
      - Homepage
      band: minimal
      in_catalog: true
      kin_score: 10.1
      mcp:
        status: unknown
      name: Komga
      slug: komga
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
      status: profiled
      tags:
      - Comics
      - Ebooks
      - Manga
      - Media Server
      tier: observed
      url: /providers/komga/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homepage
      - Homer
      band: minimal
      in_catalog: true
      kin_score: 8.9
      mcp:
        status: none
      name: Tautulli
      slug: tautulli
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Company
      - Monitoring
      - Open Source
      - Plex
      tier: observed
      url: /providers/tautulli/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homarr
      - Homepage
      band: minimal
      in_catalog: true
      kin_score: 8.7
      mcp:
        status: none
      name: Bazarr
      slug: bazarr
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Automation
      - Media
      - Open Source
      - Subtitle
      tier: observed
      url: /providers/bazarr/
    - agent_band: null
      agent_readiness: null
      apps:
      - Homarr
      - Homepage
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Overseerr
      slug: overseerr
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 25.5
      mcp:
        status: none
      name: Kavita
      slug: kavita
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Company
      - Digital Library
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/kavita/
    - agent_band: null
      agent_readiness: null
      apps:
      - Homarr
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Jellyseerr
      slug: jellyseerr
      sources:
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Dashy
      - Glance
      - Homarr
      - Homepage
      - Homer
      band: emerging
      in_catalog: true
      kin_score: 22.9
      mcp:
        status: none
      name: Pi-hole
      slug: pi-hole
      sources:
      - https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Ad Blocking
      - DNS
      - Network Security
      - Privacy
      tier: observed
      url: /providers/pi-hole/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Dashy
      - Glance
      - Homarr
      - Homepage
      - Homer
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        status: none
      name: AdGuard Home
      slug: adguard
      sources:
      - https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Ad Blocking
      - DNS Filtering
      - Network Security
      - Privacy
      tier: observed
      url: /providers/adguard/
    - agent_band: agent-aware
      agent_readiness: 24.5
      apps:
      - Homarr
      - Homepage
      - Homer
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp:
        status: none
      name: Traefik
      slug: traefik
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - AI Gateway
      - API Gateway
      - API Management
      - Developer Portal
      tier: observed
      url: /providers/traefik/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Dashy
      - Homarr
      - Homepage
      band: minimal
      in_catalog: true
      kin_score: 8.7
      mcp:
        status: unknown
      name: Gluetun
      slug: gluetun
      sources:
      - https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Docker
      - Open Source
      - VPN
      - WireGuard
      tier: observed
      url: /providers/gluetun/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Glance
      - Homarr
      - Homepage
      band: minimal
      in_catalog: true
      kin_score: 6.0
      mcp:
        status: none
      name: Technitium DNS Server
      slug: technitium
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/glanceapp/glance/tree/main/internal/glance/widget-dns-stats.go
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Company
      - DNS
      - Open Source
      - Privacy
      tier: observed
      url: /providers/technitium/
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Homarr
      - Homepage
      band: developing
      in_catalog: true
      kin_score: 46.3
      mcp:
        status: none
      name: Ubiquiti UniFi
      slug: ubiquiti
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Networking
      - Routing
      - Switching
      - Wi-Fi
      tier: observed
      url: /providers/ubiquiti/
    - agent_band: agent-aware
      agent_readiness: 18.2
      apps:
      - Homarr
      - Homepage
      band: thin
      in_catalog: true
      kin_score: 27.3
      mcp:
        status: none
      name: Caddy
      slug: caddy
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
      status: profiled
      tags:
      - Automatic HTTPS
      - Go
      - Load Balancer
      - Reverse Proxy
      tier: observed
      url: /providers/caddy/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Homarr
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 25.2
      mcp:
        status: none
      name: OPNsense
      slug: opnsense
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Firewall
      - Networking
      - Security
      - VPN
      tier: observed
      url: /providers/opnsense/
    - agent_band: agent-native
      agent_readiness: 69.6
      apps:
      - Homepage
      band: exemplar
      in_catalog: true
      kin_score: 82.8
      mcp:
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare (Tunnel)
      slug: cloudflare
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: observed
      url: /providers/cloudflare/
    - agent_band: agent-aware
      agent_readiness: 21.5
      apps:
      - Homepage
      band: developing
      in_catalog: true
      kin_score: 42.2
      mcp:
        status: none
      name: Tailscale
      slug: tailscale
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Mesh Networking
      - VPN
      - WireGuard
      - Zero Trust
      tier: observed
      url: /providers/tailscale/
    - agent_band: agent-aware
      agent_readiness: 28.4
      apps:
      - Homepage
      band: thin
      in_catalog: true
      kin_score: 36.4
      mcp:
        source: https://github.com/netbirdio/netbird-mcp
        status: verified
      name: NetBird
      slug: netbird
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Networking
      - Open Source
      - VPN
      - Zero Trust
      tier: observed
      url: /providers/netbird/
    - agent_band: agent-aware
      agent_readiness: 21.8
      apps:
      - Homepage
      band: thin
      in_catalog: true
      kin_score: 33.6
      mcp:
        status: none
      name: pfSense
      slug: pfsense
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Firewall
      - Network Security
      - Router
      - VPN
      tier: observed
      url: /providers/pfsense/
    - agent_band: agent-aware
      agent_readiness: 15.0
      apps:
      - Dashy
      band: emerging
      in_catalog: true
      kin_score: 24.9
      mcp:
        status: none
      name: Mullvad VPN
      slug: mullvad
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - Company
      - Open Source
      - Privacy
      - VPN
      tier: observed
      url: /providers/mullvad/
    - agent_band: agent-aware
      agent_readiness: 18.0
      apps:
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 22.3
      mcp:
        status: none
      name: Nginx Proxy Manager
      slug: nginx-proxy-manager
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Company
      - Docker
      - NGINX
      - Open Source
      tier: observed
      url: /providers/nginx-proxy-manager/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 16.9
      mcp:
        status: none
      name: OpenWrt
      slug: openwrt
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Company
      - Firmware
      - Open Source
      - Router
      tier: observed
      url: /providers/openwrt/
    - agent_band: agent-aware
      agent_readiness: 13.7
      apps:
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 13.8
      mcp:
        status: none
      name: NextDNS
      slug: nextdns
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - DNS
      - Filtering
      - Privacy
      - Security
      tier: observed
      url: /providers/nextdns/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homepage
      band: minimal
      in_catalog: true
      kin_score: 3.1
      mcp:
        status: unknown
      name: Headscale
      slug: headscale
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Company
      - Networking
      - Open Source
      - VPN
      tier: observed
      url: /providers/headscale/
    - agent_band: null
      agent_readiness: null
      apps:
      - Homepage
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: MikroTik
      slug: mikrotik
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Dashy
      - Homarr
      - Homepage
      - Homer
      band: thin
      in_catalog: true
      kin_score: 27.4
      mcp:
        status: none
      name: Proxmox VE
      slug: proxmox
      sources:
      - https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Containers
      - KVM
      - LXC
      - Virtualization
      tier: observed
      url: /providers/proxmox/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Glance
      - Homepage
      - Homer
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        source: https://github.com/docker/mcp-gateway
        status: verified
      name: Docker
      slug: docker
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/glanceapp/glance/tree/main/internal/glance/widget-docker-containers.go
      status: profiled
      tags:
      - Cloud
      - Containers
      - DevOps
      - Developer Tools
      tier: observed
      url: /providers/docker/
    - agent_band: agent-aware
      agent_readiness: 6.5
      apps:
      - Homarr
      - Homepage
      - Homer
      band: emerging
      in_catalog: true
      kin_score: 15.6
      mcp:
        status: none
      name: What's Up Docker
      slug: whats-up-docker
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Company
      - Container Management
      - Docker
      - Kubernetes
      tier: observed
      url: /providers/whats-up-docker/
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - Homarr
      - Homepage
      - Homer
      band: emerging
      in_catalog: true
      kin_score: 14.1
      mcp:
        source: https://github.com/truenas/truenas-mcp
        status: verified
      name: TrueNAS
      slug: truenas
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Company
      - Enterprise
      - Open Source
      - Storage
      tier: observed
      url: /providers/truenas/
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - Dashy
      - Homarr
      - Homepage
      band: minimal
      in_catalog: true
      kin_score: 7.5
      mcp:
        status: none
      name: Synology
      slug: synology
      sources:
      - https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Backup
      - Cloud
      - Company
      - Storage
      tier: observed
      url: /providers/synology/
    - agent_band: agent-ready
      agent_readiness: 39.6
      apps:
      - Homepage
      - Homer
      band: strong
      in_catalog: true
      kin_score: 56.0
      mcp:
        source: https://github.com/portainer/portainer-mcp
        status: verified
      name: Portainer
      slug: portainer
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Container Management
      - Containers
      - Docker
      - Kubernetes
      tier: observed
      url: /providers/portainer/
    - agent_band: agent-aware
      agent_readiness: 13.7
      apps:
      - Homarr
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 14.1
      mcp:
        status: none
      name: Unraid
      slug: unraid
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Docker
      - Network Attached Storage
      - Operating System
      - Virtual Machines
      tier: observed
      url: /providers/unraid/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Homarr
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 12.5
      mcp:
        source: https://github.com/openmediavault/openmediavault-mcp
        status: verified
      name: openmediavault
      slug: openmediavault
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Company
      - Data Sovereignty
      - NAS
      - Open Source
      tier: observed
      url: /providers/openmediavault/
    - agent_band: agent-aware
      agent_readiness: 27.5
      apps:
      - Homarr
      band: developing
      in_catalog: true
      kin_score: 51.6
      mcp:
        status: none
      name: Coolify
      slug: coolify
      sources:
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Deployment
      - Open Source
      - Platform-as-a-Service
      - Self-Hosting
      tier: observed
      url: /providers/coolify/
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Homepage
      band: developing
      in_catalog: true
      kin_score: 48.3
      mcp:
        status: none
      name: Kubernetes
      slug: kubernetes
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Automation
      - CNCF
      - Cloud-Native
      - Containers
      tier: observed
      url: /providers/kubernetes/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 12.5
      mcp:
        source: https://www.qnap.com/en-us/software/mcp-assistant
        status: documented
      name: QNAP
      slug: qnap
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Company
      - Enterprise
      - NAS
      - Storage
      tier: observed
      url: /providers/qnap/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Dashy
      - Homarr
      - Homepage
      - Homer
      band: minimal
      in_catalog: true
      kin_score: 2.2
      mcp:
        status: unknown
      name: Glances
      slug: glances
      sources:
      - https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Company
      - Monitoring
      - Open Source
      - Python
      tier: observed
      url: /providers/glances/
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - Dashy
      - Homarr
      - Homepage
      band: thin
      in_catalog: true
      kin_score: 38.1
      mcp:
        source: https://raw.githubusercontent.com/netdata/netdata/master/src/web/mcp/README.md
        status: verified
      name: Netdata
      slug: netdata
      sources:
      - https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
      status: profiled
      tags:
      - Infrastructure
      - Metrics
      - Monitoring
      - Observability
      tier: observed
      url: /providers/netdata/
    - agent_band: agent-aware
      agent_readiness: 18.7
      apps:
      - Homarr
      - Homepage
      - Homer
      band: thin
      in_catalog: true
      kin_score: 35.4
      mcp:
        source: https://github.com/prometheus/prometheus-mcp
        status: verified
      name: Prometheus
      slug: prometheus-io
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
      status: profiled
      tags:
      - Metrics
      - Monitoring
      - Observability
      - Prometheus
      tier: observed
      url: /providers/prometheus-io/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Homarr
      - Homepage
      - Homer
      band: emerging
      in_catalog: true
      kin_score: 20.2
      mcp:
        status: unknown
      name: Speedtest Tracker
      slug: speedtest-tracker
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Company
      - Monitoring
      - Self-Hosted
      - Speed Test
      tier: observed
      url: /providers/speedtest-tracker/
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - Homarr
      - Homepage
      - Homer
      band: emerging
      in_catalog: true
      kin_score: 14.5
      mcp:
        status: unknown
      name: Scrutiny
      slug: scrutiny
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
      status: profiled
      tags:
      - Company
      - Healthcare
      - Intelligence
      - Market Research
      tier: observed
      url: /providers/scrutiny/
    - agent_band: agent-aware
      agent_readiness: 17.1
      apps:
      - Homarr
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 12.6
      mcp:
        status: unknown
      name: Beszel
      slug: beszel
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Alerts
      - Docker
      - Podman
      - Server Monitoring
      tier: observed
      url: /providers/beszel/
    - agent_band: agent-ready
      agent_readiness: 31.1
      apps:
      - Homepage
      band: strong
      in_catalog: true
      kin_score: 60.6
      mcp:
        source: https://github.com/grafana/mcp-grafana
        status: verified
      name: Grafana
      slug: grafana-com
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Dashboards
      - Logs
      - Monitoring
      - Observability
      tier: observed
      url: /providers/grafana-com/
    - agent_band: agent-aware
      agent_readiness: 22.1
      apps:
      - Homepage
      band: thin
      in_catalog: true
      kin_score: 35.1
      mcp:
        status: none
      name: Zabbix
      slug: zabbix
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Alerting
      - Infrastructure
      - Monitoring
      - Networks
      tier: observed
      url: /providers/zabbix/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90.10
      key: AE-170.90.10
      name: BitTorrent & Usenet Download Clients
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: Self-Hosted Media Servers & Library Automation
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - Dashy
      - Homarr
      - Homepage
      - Homer
      band: emerging
      in_catalog: true
      kin_score: 19.1
      mcp:
        status: none
      name: SABnzbd
      slug: sabnzbd
      sources:
      - https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Company
      - Downloader
      - Open Source
      - Usenet
      tier: observed
      url: /providers/sabnzbd/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Homarr
      - Homepage
      - Homer
      band: thin
      in_catalog: true
      kin_score: 34.7
      mcp:
        status: none
      name: Prowlarr
      slug: prowlarr
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Indexing
      - Media Management
      - Open Source
      - Software
      tier: observed
      url: /providers/prowlarr/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homarr
      - Homepage
      - Homer
      band: minimal
      in_catalog: true
      kin_score: 8.1
      mcp:
        status: none
      name: qBittorrent
      slug: qbittorrent
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Clients
      - Cross-Platform
      - Open Source
      - Torrent
      tier: observed
      url: /providers/qbittorrent/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homarr
      - Homepage
      - Homer
      band: minimal
      in_catalog: true
      kin_score: 4.4
      mcp:
        status: none
      name: Transmission
      slug: transmission-bt
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - BitTorrent
      - Cross-Platform
      - File Sharing
      - Open Source
      tier: observed
      url: /providers/transmission-bt/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Homarr
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 21.1
      mcp:
        status: none
      name: Deluge
      slug: deluge
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Automation
      - Company
      - Low-Code
      - Scripting
      tier: observed
      url: /providers/deluge/
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - Homarr
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 17.2
      mcp:
        status: none
      name: Jackett
      slug: jackett
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Company
      - Open Source
      - Proxy
      - Torrent
      tier: observed
      url: /providers/jackett/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homarr
      - Homepage
      band: minimal
      in_catalog: true
      kin_score: 7.1
      mcp:
        status: none
      name: NZBGet
      slug: nzbget
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Cross-Platform
      - Downloader
      - RPC
      - Usenet
      tier: observed
      url: /providers/nzbget/
  - capability:
      attribution: Turbo EA
      id: BC-2630.20
      key: service-performance-monitoring
      name: Service Performance Monitoring
      url: /capabilities/service-performance-monitoring/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - Dashy
      - Homarr
      - Homepage
      - Homer
      band: thin
      in_catalog: true
      kin_score: 32.9
      mcp:
        status: none
      name: Healthchecks.io
      slug: healthchecks-io
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Cron
      - DevOps
      - Monitoring
      - Open Source
      tier: observed
      url: /providers/healthchecks-io/
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Dashy
      - Homarr
      - Homepage
      - Homer
      band: emerging
      in_catalog: true
      kin_score: 18.5
      mcp:
        status: none
      name: Uptime Kuma
      slug: uptime-kuma
      sources:
      - https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Dashboards
      - Monitoring
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/uptime-kuma/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Glance
      - Homarr
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        status: none
      name: changedetection.io
      slug: changedetection-io
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/glanceapp/glance/tree/main/internal/glance/widget-changedetection.go
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
      status: profiled
      tags:
      - Alerts
      - Company
      - Monitoring
      - Webhook
      tier: observed
      url: /providers/changedetection-io/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homarr
      - Homepage
      - Homer
      band: minimal
      in_catalog: true
      kin_score: 9.1
      mcp:
        status: unknown
      name: Gatus
      slug: gatus
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
      status: profiled
      tags:
      - Company
      - Monitoring
      - Open Source
      - Status Pages
      tier: observed
      url: /providers/gatus/
    - agent_band: agent-ready
      agent_readiness: 50.9
      apps:
      - Homepage
      band: developing
      in_catalog: true
      kin_score: 51.1
      mcp:
        source: https://uptimerobot.com/mcp/
        status: documented
      name: UptimeRobot
      slug: uptimerobot
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - DevOps
      - Incident Management
      - Status Pages
      - Uptime Monitoring
      tier: observed
      url: /providers/uptimerobot/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    providers:
    - agent_band: agent-aware
      agent_readiness: 15.0
      apps:
      - Homarr
      - Homepage
      - Homer
      band: emerging
      in_catalog: true
      kin_score: 20.9
      mcp:
        status: none
      name: Miniflux
      slug: miniflux
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
      status: profiled
      tags:
      - Feed Reader
      - Minimalist
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/miniflux/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Homarr
      - Homepage
      band: developing
      in_catalog: true
      kin_score: 41.5
      mcp:
        status: none
      name: Linkwarden
      slug: linkwarden
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
      status: profiled
      tags:
      - Bookmarking
      - Company
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/linkwarden/
    - agent_band: agent-aware
      agent_readiness: 20.1
      apps:
      - Homarr
      - Homepage
      band: thin
      in_catalog: true
      kin_score: 30.8
      mcp:
        source: https://docs.karakeep.app/mcp
        status: verified
      name: Karakeep
      slug: karakeep
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
      status: profiled
      tags:
      - Artificial Intelligence
      - Bookmarking
      - Collaboration
      - Company
      tier: observed
      url: /providers/karakeep/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Dashy
      - Homer
      band: minimal
      in_catalog: true
      kin_score: 6.5
      mcp:
        status: none
      name: linkding
      slug: linkding
      sources:
      - https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      status: profiled
      tags:
      - Bookmark
      - Company
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/linkding/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homepage
      - Homer
      band: minimal
      in_catalog: true
      kin_score: 5.7
      mcp:
        status: none
      name: FreshRSS
      slug: freshrss
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Feed Reader
      - RSS Aggregator
      - Self‑Hosted Software
      - Web Scraping
      tier: observed
      url: /providers/freshrss/
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - Homer
      band: emerging
      in_catalog: true
      kin_score: 17.3
      mcp:
        status: none
      name: wallabag
      slug: wallabag
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      status: profiled
      tags:
      - Open Source
      - Privacy
      - Read-it-later
      - Self-Hosted
      tier: observed
      url: /providers/wallabag/
  - capability:
      attribution: Turbo EA
      id: BC-4200.40.10
      key: BC-4200.40.10
      name: Source Code Management
      url: /capabilities/software-construction-management/
      via_parent: Software Construction Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 63.4
      apps:
      - CasaOS
      - Dashy
      - Glance
      - Homarr
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/IceWhaleTech/CasaOS/blob/main/go.mod
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      - https://github.com/glanceapp/glance/tree/main/internal/glance/widget-releases.go
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-native
      agent_readiness: 55.6
      apps:
      - Glance
      - Homepage
      band: exemplar
      in_catalog: true
      kin_score: 79.6
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/glanceapp/glance/tree/main/internal/glance/widget-releases.go
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 31.0
      apps:
      - Homepage
      - Homer
      band: exemplar
      in_catalog: true
      kin_score: 69.8
      mcp:
        source: https://gitea.com/gitea/gitea-mcp
        status: verified
      name: Gitea
      slug: gitea
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - CI/CD
      - DevOps
      - Gitea
      - Version Control
      tier: observed
      url: /providers/gitea/
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Glance
      band: thin
      in_catalog: true
      kin_score: 29.3
      mcp:
        status: unknown
      name: Codeberg
      slug: codeberg
      sources:
      - https://github.com/glanceapp/glance/tree/main/internal/glance/widget-releases.go
      status: profiled
      tags:
      - Code Hosting
      - Git Hosting
      - Repositories
      - Version Control
      tier: observed
      url: /providers/codeberg/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Dashy
      - Homarr
      - Homepage
      - Homer
      band: thin
      in_catalog: true
      kin_score: 33.0
      mcp:
        status: none
      name: Nextcloud
      slug: nextcloud
      sources:
      - https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Collaboration
      - File Sharing
      - File Sync
      - Self-Hosted
      tier: observed
      url: /providers/nextcloud/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 16.1
      mcp:
        status: none
      name: File Browser
      slug: filebrowser
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Archived
      - File Management
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/filebrowser/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 16.1
      mcp:
        status: none
      name: Syncthing
      slug: syncthing
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Cross-Platform
      - Encryption
      - File Synchronization
      - Open Source
      tier: observed
      url: /providers/syncthing/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Dashy
      - Homarr
      - Homepage
      band: minimal
      in_catalog: true
      kin_score: 9.9
      mcp:
        status: none
      name: ntfy
      slug: ntfy
      sources:
      - https://github.com/Lissy93/dashy/tree/master/src/components/Widgets
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Notification
      - Open Source
      - Pub/Sub
      - Self-Hosted
      tier: observed
      url: /providers/ntfy/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homarr
      - Homepage
      - Homer
      band: minimal
      in_catalog: true
      kin_score: 7.8
      mcp:
        source: https://gotify.net/docs/mcp
        status: verified
      name: Gotify
      slug: gotify
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Messaging
      - Notification
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/gotify/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.10
      key: AE-200.10
      name: Smart Home
      url: /capabilities/smart-home/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 5.0
      apps:
      - Homarr
      - Homepage
      - Homer
      band: emerging
      in_catalog: true
      kin_score: 22.2
      mcp:
        source: https://www.home-assistant.io/integrations/mcp_server/
        status: verified
      name: Home Assistant
      slug: home-assistant
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Community
      - Home Automation
      - IoT
      - Open Source
      tier: observed
      url: /providers/home-assistant/
    - agent_band: agent-aware
      agent_readiness: 18.2
      apps:
      - Homer
      band: emerging
      in_catalog: true
      kin_score: 18.3
      mcp:
        source: https://www.openhab.org/addons/integrations/mcp/
        status: verified
      name: openHAB
      slug: openhab
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      status: profiled
      tags:
      - Home Automation
      - IoT
      - Open Source
      - Smart Home
      tier: observed
      url: /providers/openhab/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 11.1
      mcp:
        status: none
      name: ESPHome
      slug: esphome
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Home Automation
      - Microcontrollers
      - Open Source
      - Smart Home
      tier: observed
      url: /providers/esphome/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Homepage
      band: minimal
      in_catalog: true
      kin_score: 4.9
      mcp:
        status: none
      name: Homebridge
      slug: homebridge
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Home Automation
      - Node.js
      - Open Source
      - Smart Home
      tier: observed
      url: /providers/homebridge/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.70
      key: AE-200.70
      name: 3D Printing & Printer Control
      url: /capabilities/3d-printing-printer-control/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - Homepage
      - Homer
      band: emerging
      in_catalog: true
      kin_score: 24.5
      mcp:
        status: none
      name: OctoPrint
      slug: octoprint
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - 3D Printing
      - Company
      - IoT
      - Open Source
      tier: observed
      url: /providers/octoprint/
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - Homarr
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 16.4
      mcp:
        status: unknown
      name: Spoolman
      slug: spoolman
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
      status: profiled
      tags:
      - 3D Printing
      - Inventory
      - Open Source
      - filament
      tier: observed
      url: /providers/spoolman/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homepage
      band: minimal
      in_catalog: true
      kin_score: 8.2
      mcp:
        status: unknown
      name: Moonraker (Klipper)
      slug: moonraker
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - 3D Printing
      - Company
      - Open Source
      - Python
      tier: observed
      url: /providers/moonraker/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.10
      key: AE-170.50.10
      name: Online Communities
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Dashy
      - Glance
      band: thin
      in_catalog: true
      kin_score: 28.3
      mcp:
        status: none
      name: Hacker News
      slug: hacker-news
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      - https://github.com/glanceapp/glance/tree/main/internal/glance/widget-hacker-news.go
      status: profiled
      tags:
      - Developer Community
      - Technology News
      - Y Combinator
      tier: observed
      url: /providers/hacker-news/
    - agent_band: agent-ready
      agent_readiness: 39.1
      apps:
      - Glance
      band: strong
      in_catalog: true
      kin_score: 63.0
      mcp:
        source: https://github.com/reddit/devvit-mcp
        status: verified
      name: Reddit
      slug: reddit
      sources:
      - https://github.com/glanceapp/glance/tree/main/internal/glance/widget-reddit.go
      status: profiled
      tags:
      - Advertising
      - Community
      - Content
      - Reddit
      tier: observed
      url: /providers/reddit/
    - agent_band: agent-aware
      agent_readiness: 22.5
      apps:
      - Homepage
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: Mastodon
      slug: mastodon
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Open Source
      - Real-Time
      - Social
      - Social Network
      tier: observed
      url: /providers/mastodon/
    - agent_band: agent-aware
      agent_readiness: 23.0
      apps:
      - Glance
      band: emerging
      in_catalog: true
      kin_score: 25.0
      mcp:
        status: none
      name: Lobsters
      slug: lobsters
      sources:
      - https://github.com/glanceapp/glance/tree/main/internal/glance/widget-lobsters.go
      status: profiled
      tags:
      - Community
      - Link Aggregation
      - News
      - Technology
      tier: observed
      url: /providers/lobsters/
  - capability:
      attribution: API Evangelist extension
      id: AE-130.30.20
      key: AE-130.30.20
      name: Recipe & Meal Planning
      url: /capabilities/nutrition-food-data/
      via_parent: Nutrition & Food Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.7
      apps:
      - Homarr
      - Homepage
      - Homer
      band: developing
      in_catalog: true
      kin_score: 41.5
      mcp:
        status: none
      name: Mealie
      slug: mealie
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
      status: profiled
      tags:
      - Company
      - Food
      - Meal Planning
      - Recipes
      tier: observed
      url: /providers/mealie/
    - agent_band: agent-aware
      agent_readiness: 26.7
      apps:
      - Homarr
      - Homepage
      band: strong
      in_catalog: true
      kin_score: 61.0
      mcp:
        status: none
      name: Tandoor Recipes
      slug: tandoor
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
      status: profiled
      tags:
      - Food
      - Meal Planning
      - Nutrition
      - Recipes
      tier: observed
      url: /providers/tandoor/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - Dashy
      band: strong
      in_catalog: true
      kin_score: 63.2
      mcp:
        source: https://github.com/ipinfo/mcp
        status: verified
      name: IPinfo
      slug: ipinfo
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - ASN
      - IP Geolocation
      - IP Intelligence
      - Privacy Detection
      tier: observed
      url: /providers/ipinfo/
    - agent_band: agent-ready
      agent_readiness: 30.2
      apps:
      - Dashy
      band: developing
      in_catalog: true
      kin_score: 50.8
      mcp:
        source: https://github.com/IPGeolocation/ipgeolocation-io-mcp
        status: verified
      name: IPGeolocation.io
      slug: ipgeolocation
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - Geocoding
      - IP Geolocation
      - IP Intelligence
      - IP Security
      tier: observed
      url: /providers/ipgeolocation/
    - agent_band: agent-aware
      agent_readiness: 25.5
      apps:
      - Dashy
      band: thin
      in_catalog: true
      kin_score: 31.4
      mcp:
        status: none
      name: ipify
      slug: ipify
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - Development
      - Geolocation
      - IP Address
      - IP Intelligence
      tier: observed
      url: /providers/ipify/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Dashy
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        status: none
      name: ip-api
      slug: ip-api
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - Geocoding
      - Public APIs
      tier: observed
      url: /providers/ip-api/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.20
      key: AE-170.30.20
      name: Photo Sharing
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Homarr
      - Homepage
      - Homer
      band: emerging
      in_catalog: true
      kin_score: 22.3
      mcp:
        status: none
      name: Immich
      slug: immich
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Photo Management
      - Privacy
      - Self-Hosted
      - Video Management
      tier: observed
      url: /providers/immich/
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - Homepage
      band: developing
      in_catalog: true
      kin_score: 42.5
      mcp:
        source: https://docs.photoprism.app/developer-guide/api/mcp/
        status: verified
      name: PhotoPrism
      slug: photoprism
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Photo Management
      - Self-Hosted
      tier: observed
      url: /providers/photoprism/
  - capability:
      attribution: Turbo EA
      id: BC-160.20.20
      key: BC-160.20.20
      name: Backup and Restore Management
      url: /capabilities/disaster-recovery-management/
      via_parent: Disaster Recovery Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - Homepage
      band: thin
      in_catalog: true
      kin_score: 28.0
      mcp:
        status: none
      name: Duplicati
      slug: duplicati
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Backup
      - Cloud
      - Company
      - Open Source
      tier: observed
      url: /providers/duplicati/
    - agent_band: agent-aware
      agent_readiness: 15.0
      apps:
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 17.3
      mcp:
        status: none
      name: Kopia
      slug: kopia
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Backup
      - Cloud
      - Open Source
      - Security
      tier: observed
      url: /providers/kopia/
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - Homepage
      band: minimal
      in_catalog: true
      kin_score: 9.4
      mcp:
        status: unknown
      name: Backrest
      slug: backrest
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Backup
      - Open Source
      - Restic
      - Storage
      tier: observed
      url: /providers/backrest/
  - capability:
      attribution: API Evangelist extension
      id: AE-917
      key: AE-917
      name: Enterprise Content & Document Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homarr
      - Homepage
      - Homer
      band: minimal
      in_catalog: true
      kin_score: 1.3
      mcp:
        status: none
      name: Paperless-ngx
      slug: paperless-ngx
      sources:
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/paperless-ngx/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.5
      apps:
      - Dashy
      - Homer
      band: strong
      in_catalog: true
      kin_score: 60.4
      mcp:
        source: https://mcp.openweathermap.org/
        status: verified
      name: OpenWeatherMap
      slug: openweathermap
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      - https://github.com/bastienwirtz/homer/tree/main/src/components/services
      status: profiled
      tags:
      - Air Pollution
      - Climate
      - Forecast
      - Weather
      tier: observed
      url: /providers/openweathermap/
    - agent_band: agent-aware
      agent_readiness: 17.8
      apps:
      - Glance
      band: thin
      in_catalog: true
      kin_score: 29.6
      mcp:
        status: none
      name: Open-Meteo
      slug: open-meteo
      sources:
      - https://github.com/glanceapp/glance/tree/main/internal/glance/widget-weather.go
      status: profiled
      tags:
      - Air Quality
      - Forecast
      - Historical Weather
      - Weather
      tier: observed
      url: /providers/open-meteo/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20
      key: AE-230.20
      name: Market & Financial Data
      url: /capabilities/market-financial-data/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.2
      apps:
      - Dashy
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        source: https://docs.coingecko.com/reference/mcp-server
        status: verified
      name: CoinGecko
      slug: coingecko
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - Aggregator
      - Blockchain
      - CoinGecko
      - Cryptocurrency
      tier: observed
      url: /providers/coingecko/
    - agent_band: agent-aware
      agent_readiness: 9.3
      apps:
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 15.5
      mcp:
        source: https://coinmarketcap.com/api/mcp/
        status: verified
      name: CoinMarketCap
      slug: coinmarketcap
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Cryptocurrency
      - Market Data
      - Rankings
      - Web3
      tier: observed
      url: /providers/coinmarketcap/
  - capability:
      attribution: Turbo EA
      id: BC-2340.50
      key: physical-security-surveillance-management
      name: Physical Security & Surveillance Management
      url: /capabilities/physical-security-surveillance-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.1
      apps:
      - Homarr
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 20.5
      mcp:
        status: unknown
      name: Frigate NVR
      slug: frigate
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src/stats/providers
      status: profiled
      tags:
      - Company
      - Open Source
      - Surveillance
      - Video
      tier: observed
      url: /providers/frigate/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.40
      key: AE-210.30.40
      name: Public Transit Data
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Dashy
      band: minimal
      in_catalog: true
      kin_score: 8.1
      mcp:
        status: unknown
      name: MVG (Munich transit)
      slug: mvg
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - Company
      - Munich
      - Public Transit
      - Transportation
      tier: observed
      url: /providers/mvg/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Dashy
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        status: none
      name: Transport for London
      slug: transport-for-london-england
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - Public APIs
      - Transportation
      tier: observed
      url: /providers/transport-for-london-england/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.20
      key: AE-230.20.20
      name: Securities Market Data
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.4
      apps:
      - Dashy
      band: strong
      in_catalog: true
      kin_score: 54.4
      mcp:
        source: https://github.com/alphavantage/alpha_vantage_mcp
        status: verified
      name: Alpha Vantage
      slug: alpha-vantage
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - Fintech
      - Foreign Exchange
      - Market Data
      - Stocks
      tier: observed
      url: /providers/alpha-vantage/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Glance
      band: minimal
      in_catalog: true
      kin_score: 4.2
      mcp:
        status: none
      name: Yahoo Finance
      slug: yahoo-finance
      sources:
      - https://github.com/glanceapp/glance/tree/main/internal/glance/widget-markets.go
      status: profiled
      tags:
      - Finance
      - Public APIs
      tier: observed
      url: /providers/yahoo-finance/
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.4
      apps:
      - Homepage
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        source: https://github.com/crowdsecurity/crowdsec-local-mcp
        status: verified
      name: CrowdSec
      slug: crowdsec
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Community
      - Open Source
      - Security
      - Threat Intelligence
      tier: observed
      url: /providers/crowdsec/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Homarr
      band: emerging
      in_catalog: true
      kin_score: 14.3
      mcp:
        status: none
      name: Wazuh
      slug: wazuh
      sources:
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Company
      - Open Source
      - Security
      - XDR
      tier: observed
      url: /providers/wazuh/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.4
      apps:
      - Glance
      band: strong
      in_catalog: true
      kin_score: 62.6
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://github.com/glanceapp/glance/tree/main/internal/glance/widget-videos.go
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: observed
      url: /providers/youtube/
    - agent_band: agent-ready
      agent_readiness: 32.2
      apps:
      - Glance
      band: developing
      in_catalog: true
      kin_score: 50.5
      mcp:
        status: none
      name: Twitch
      slug: twitch
      sources:
      - https://github.com/glanceapp/glance/tree/main/internal/glance/widget-twitch-channels.go
      status: profiled
      tags:
      - Entertainment
      - Gaming
      - Live Streaming
      - Streaming
      tier: observed
      url: /providers/twitch/
  - capability:
      attribution: API Evangelist extension
      id: AE-240.30.10
      key: AE-240.30.10
      name: Blockchain Indexing
      url: /capabilities/on-chain-data-indexing/
      via_parent: On-Chain Data & Indexing
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Dashy
      band: emerging
      in_catalog: true
      kin_score: 20.7
      mcp:
        status: none
      name: BlockCypher
      slug: blockcypher
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - Blockchain
      - Enterprise
      - Infrastructure
      tier: observed
      url: /providers/blockcypher/
  - capability:
      attribution: API Evangelist extension
      id: AE-190.10
      key: AE-190.10
      name: Budgeting & Money Management
      url: /capabilities/budgeting-money-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homepage
      band: minimal
      in_catalog: true
      kin_score: 5.9
      mcp:
        status: none
      name: Firefly III
      slug: firefly-iii
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Budgeting
      - Finance
      - Open Source
      - Personal Finance
      tier: observed
      url: /providers/firefly-iii/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.70
      key: AE-230.70
      name: Calendar & Holiday Data
      url: /capabilities/calendar-holiday-data/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Dashy
      band: minimal
      in_catalog: true
      kin_score: 6.3
      mcp:
        status: unknown
      name: Enrico holiday service
      slug: enrico
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - Company
      - Holiday
      - Open Source
      - Slovakia
      tier: observed
      url: /providers/enrico/
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Glance
      band: developing
      in_catalog: true
      kin_score: 46.7
      mcp:
        source: https://github.com/docker/hub-mcp
        status: verified
      name: Docker Hub
      slug: docker-hub
      sources:
      - https://github.com/glanceapp/glance/tree/main/internal/glance/widget-releases.go
      status: profiled
      tags:
      - Containers
      - DevOps
      - Docker
      - Registry
      tier: observed
      url: /providers/docker-hub/
  - capability:
      attribution: Turbo EA
      id: BC-4210.40
      key: deployment-orchestration
      name: Deployment Orchestration
      url: /capabilities/deployment-orchestration/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.3
      apps:
      - Homepage
      band: thin
      in_catalog: true
      kin_score: 36.6
      mcp:
        source: https://github.com/argoproj-labs/mcp-for-argocd
        status: verified
      name: Argo CD
      slug: argocd
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - ArgoCD
      - DevOps
      - GitOps
      - Kubernetes
      tier: observed
      url: /providers/argocd/
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.3
      apps:
      - Dashy
      band: strong
      in_catalog: true
      kin_score: 55.9
      mcp:
        status: none
      name: WhoAPI
      slug: whoapi
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - Company
      - Domain Availability
      - Domains
      - WHOIS
      tier: observed
      url: /providers/whoapi/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.20
      key: AE-200.20.20
      name: EV Charging
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.2
      apps:
      - Homepage
      band: thin
      in_catalog: true
      kin_score: 38.8
      mcp:
        source: https://docs.evcc.io/en/integrations/mcp.md
        status: verified
      name: evcc
      slug: evcc
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Company
      - Electric Vehicles
      - Open Source
      - Smart Charging
      tier: observed
      url: /providers/evcc/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10
      key: AE-150.10
      name: Email
      url: /capabilities/email/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Dashy
      band: developing
      in_catalog: true
      kin_score: 41.8
      mcp:
        status: none
      name: addy.io
      slug: addy-io
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - Address
      - Company
      - Email
      - Software-as-a-Service
      tier: observed
      url: /providers/addy-io/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20.10
      key: AE-230.20.10
      name: Exchange Rates
      url: /capabilities/market-financial-data/
      via_parent: Market & Financial Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.2
      apps:
      - Dashy
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: ExchangeRate-API
      slug: exchangerate-api
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - Currency Conversion
      - Financial Data
      - Foreign Exchange
      - Public APIs
      tier: observed
      url: /providers/exchangerate-api/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.10
      key: AE-210.10
      name: Flight Search & Booking
      url: /capabilities/flight-search-booking/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Dashy
      band: thin
      in_catalog: true
      kin_score: 37.8
      mcp:
        status: none
      name: AeroDataBox (via RapidAPI)
      slug: aerodatabox
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - Aerospace
      - Aviation
      - Flight Data
      - Flights
      tier: observed
      url: /providers/aerodatabox/
  - capability:
      attribution: API Evangelist extension
      id: AE-180.20.20
      key: AE-180.20.20
      name: Game Server Hosting
      url: /capabilities/game-backend-services/
      via_parent: Game Backend Services
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 24.8
      mcp:
        status: none
      name: Pterodactyl
      slug: pterodactyl
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Company
      - Docker
      - Game Server
      - Open Source
      tier: observed
      url: /providers/pterodactyl/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.2
      apps:
      - Homepage
      band: exemplar
      in_catalog: true
      kin_score: 74.5
      mcp:
        status: none
      name: Authentik
      slug: authentik
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity Provider
      - LDAP
      tier: observed
      url: /providers/authentik/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.10
      key: AE-170.60.10
      name: News Data
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Dashy
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        source: https://github.com/currents-dev/currents-mcp
        status: verified
      name: Currents API
      slug: currents
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - News
      - Public APIs
      tier: observed
      url: /providers/currents/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.50
      key: AE-230.50
      name: Open Government Data
      url: /capabilities/open-government-data/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - Dashy
      band: emerging
      in_catalog: true
      kin_score: 22.5
      mcp:
        status: none
      name: disease.sh
      slug: disease-sh
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - COVID-19
      - Disease
      - Epidemiology
      - Health
      tier: observed
      url: /providers/disease-sh/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.4
      apps:
      - Homarr
      band: exemplar
      in_catalog: true
      kin_score: 73.3
      mcp:
        status: none
      name: Umami
      slug: umami
      sources:
      - https://github.com/homarr-labs/homarr/tree/dev/packages/integrations/src
      status: profiled
      tags:
      - Cookieless Tracking
      - Open Source
      - Privacy
      - Web Analytics
      tier: observed
      url: /providers/umami/
  - capability:
      attribution: API Evangelist extension
      id: AE-190.30
      key: AE-190.30
      name: Retail Investing
      url: /capabilities/retail-investing/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Homepage
      band: emerging
      in_catalog: true
      kin_score: 15.0
      mcp:
        status: none
      name: Ghostfolio
      slug: ghostfolio
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Finance
      - Open Source
      - Software-as-a-Service
      - Wealth Management
      tier: observed
      url: /providers/ghostfolio/
  - capability:
      attribution: API Evangelist extension
      id: AE-180.80.40
      key: AE-180.80.40
      name: Sports Data
      url: /capabilities/sports-betting-fantasy/
      via_parent: Sports, Betting & Fantasy
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - Dashy
      band: thin
      in_catalog: true
      kin_score: 30.7
      mcp:
        status: none
      name: TheSportsDB
      slug: sportsdb
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - Player
      - Sports
      - Sports Data
      - Team
      tier: observed
      url: /providers/sportsdb/
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: BC-620.40
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Dashy
      band: thin
      in_catalog: true
      kin_score: 37.0
      mcp:
        status: none
      name: NVD
      slug: nvd
      sources:
      - https://github.com/Lissy93/dashy/blob/master/src/utils/config/defaults.js
      status: profiled
      tags:
      - CPE
      - CVE
      - Security
      - Vulnerabilities
      tier: observed
      url: /providers/nvd/
  - capability:
      attribution: API Evangelist extension
      id: AE-926
      key: AE-926
      name: Web Hosting & Control Panels
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - Homepage
      band: minimal
      in_catalog: true
      kin_score: 8.5
      mcp:
        status: none
      name: mailcow
      slug: mailcow
      sources:
      - https://github.com/gethomepage/homepage/tree/main/src/widgets
      status: profiled
      tags:
      - Company
      - Docker
      - Email
      - Open Source
      tier: observed
      url: /providers/mailcow/
  layer: domain
summary:
  coverage_pct: 97.1
  declared_only: 0
  distinct_providers: 139
  in_catalog: 135
  mcp:
    documented: 2
    none: 85
    unchecked: 4
    verified: 29
  mcp_verified: 29
  mean_kin_score: 27.4
  observed: 139
  queued: 4
  reference_apps: 6
title: 'Personal Dashboard & Homelab: application blueprint'
---
