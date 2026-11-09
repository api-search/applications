---
app: Lidarr
app_slug: lidarr
app_url: https://github.com/Lidarr/Lidarr
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.20.10
  key: AE-170.20.10
  layer: domain
  name: Music Streaming & Catalog
  providers:
  - Last.fm
  - MusicBrainz
  - Spotify
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-170.90
  key: AE-170.90
  layer: domain
  name: Self-Hosted Media Servers & Library Automation
  providers:
  - Emby
  - Headphones
  - Kodi
  - Plex
  - Synology
  url: /capabilities/self-hosted-media-servers-library-automation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Gotify
  - Join (joaoapps)
  - Notifiarr
  - ntfy
  - Prowl
  - Pushbullet
  - Pushcut
  - Pushover
  - Simplepush
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: common
  name: Social Networks & Community
  providers:
  - X (Twitter)
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Discord
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Mailgun
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - Signal
  - Telegram
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: music-streaming
  name: Music & Audio Streaming
  url: /applications/music-streaming/
counts:
  declared: 0
  observed: 24
credits: []
evidence:
- route: source code
  url: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/ImportLists
- route: source code
  url: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/MetadataSource
- route: source code
  url: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
integrations:
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
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id001
      status: none
    slug: discord
    status: profiled
    tags: &id002
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
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
    mcp: &id003
      status: none
    slug: emby
    status: profiled
    tags: &id004
    - Media Server
    - Personal Media
    - Streaming
    - Video Library
    url: /providers/emby/
  layer: domain
  name: Emby
  provider: emby
  says: ships the Emby SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
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
    mcp: &id005
      source: https://gotify.net/docs/mcp
      status: verified
    slug: gotify
    status: profiled
    tags: &id006
    - Messaging
    - Notification
    - Open Source
    - Self-Hosted
    url: /providers/gotify/
  layer: common
  name: Gotify
  provider: gotify
  says: ships the Gotify SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
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
    band: minimal
    in_catalog: true
    kin_score: 3.5
    mcp: &id007
      status: unknown
    slug: headphones
    status: profiled
    tags: &id008
    - Company
    - Harvest
    - Placeholder
    url: /providers/headphones/
  layer: domain
  name: Headphones
  provider: headphones
  says: ships the Headphones SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/ImportLists
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
    kin_score: 6.2
    mcp: &id009
      status: unknown
    slug: joaoapps-join
    status: profiled
    tags: &id010
    - Company
    url: /providers/joaoapps-join/
  layer: common
  name: Join (joaoapps)
  provider: joaoapps-join
  says: ships the Join (joaoapps) SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
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
    agent_readiness: 5.4
    band: emerging
    in_catalog: true
    kin_score: 13.3
    mcp: &id011
      status: none
    slug: kodi
    status: profiled
    tags: &id012
    - Entertainment
    - Home-Theater
    - Media
    - Open Source
    url: /providers/kodi/
  layer: domain
  name: Kodi
  provider: kodi
  says: ships the Kodi SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.10
    key: AE-170.20.10
    name: Music Streaming & Catalog
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: developing
    in_catalog: true
    kin_score: 54.2
    mcp: &id013
      status: none
    slug: lastfm
    status: profiled
    tags: &id014
    - Audio
    - Music
    - Recommendations
    - Scrobbling
    url: /providers/lastfm/
  layer: domain
  name: Last.fm
  provider: lastfm
  says: ships the Last.fm SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/ImportLists
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 32.6
    mcp: &id015
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id016
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: common
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.10
    key: AE-170.20.10
    name: Music Streaming & Catalog
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: thin
    in_catalog: true
    kin_score: 37.9
    mcp: &id017
      status: none
    slug: musicbrainz
    status: profiled
    tags: &id018
    - Encyclopedia
    - Metadata
    - Music
    - Open Data
    url: /providers/musicbrainz/
  layer: domain
  name: MusicBrainz
  provider: musicbrainz
  says: ships the MusicBrainz SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/ImportLists
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
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 3.1
    mcp: &id019
      source: https://notifiarr.com/api/mcp
      status: documented
    slug: notifiarr
    status: profiled
    tags: &id020
    - Company
    - Integration
    - Monitoring
    - Notification
    url: /providers/notifiarr/
  layer: common
  name: Notifiarr
  provider: notifiarr
  says: ships the Notifiarr SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
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
    mcp: &id021
      status: none
    slug: ntfy
    status: profiled
    tags: &id022
    - Notification
    - Open Source
    - Pub/Sub
    - Self-Hosted
    url: /providers/ntfy/
  layer: common
  name: ntfy
  provider: ntfy
  says: ships the ntfy SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
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
    mcp: &id023
      status: none
    slug: plex
    status: profiled
    tags: &id024
    - Company
    - Media
    - Streaming
    - Video
    url: /providers/plex/
  layer: domain
  name: Plex
  provider: plex
  says: ships the Plex SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
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
    kin_score: 6.3
    mcp: &id025
      status: unknown
    slug: prowl
    status: profiled
    tags: &id026
    - Company
    - Mobile
    - Push Notifications
    - iOS
    url: /providers/prowl/
  layer: common
  name: Prowl
  provider: prowl
  says: ships the Prowl SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
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
    agent_band: agent-aware
    agent_readiness: 24.9
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id027
      status: none
    slug: pushbullet
    status: profiled
    tags: &id028
    - Device Sync
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushbullet/
  layer: common
  name: Pushbullet
  provider: pushbullet
  says: ships the Pushbullet SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
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
    agent_band: agent-ready
    agent_readiness: 29.5
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id029
      status: unknown
    slug: pushcut
    status: profiled
    tags: &id030
    - Automation
    - Company
    - Shortcuts
    - iOS
    url: /providers/pushcut/
  layer: common
  name: Pushcut
  provider: pushcut
  says: ships the Pushcut SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
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
    agent_band: agent-aware
    agent_readiness: 22.0
    band: thin
    in_catalog: true
    kin_score: 29.2
    mcp: &id031
      status: none
    slug: pushover
    status: profiled
    tags: &id032
    - Alerts
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushover/
  layer: common
  name: Pushover
  provider: pushover
  says: ships the Pushover SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.1
    band: exemplar
    in_catalog: true
    kin_score: 87.3
    mcp: &id033
      status: none
    slug: sendgrid
    status: profiled
    tags: &id034
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 41.4
    mcp: &id035
      status: none
    slug: signal
    status: profiled
    tags: &id036
    - Cryptography
    - Encryption
    - Messaging
    - Security
    url: /providers/signal/
  layer: common
  name: Signal
  provider: signal
  says: ships the Signal SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id037
      status: unchecked
    slug: simplepush
    status: queued for profiling
    tags: &id038 []
    url: null
  layer: common
  name: Simplepush
  provider: simplepush
  says: ships the Simplepush SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
  tier: observed
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
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id039
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id040
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.10
    key: AE-170.20.10
    name: Music Streaming & Catalog
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.3
    band: developing
    in_catalog: true
    kin_score: 49.8
    mcp: &id041
      status: none
    slug: spotify
    status: profiled
    tags: &id042
    - Audio
    - Music
    - Podcasts
    - Streaming
    url: /providers/spotify/
  layer: domain
  name: Spotify
  provider: spotify
  says: ships the Spotify SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/ImportLists
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
    agent_readiness: 21.6
    band: minimal
    in_catalog: true
    kin_score: 7.5
    mcp: &id043
      status: none
    slug: synology
    status: profiled
    tags: &id044
    - Backup
    - Cloud
    - Company
    - Storage
    url: /providers/synology/
  layer: domain
  name: Synology
  provider: synology
  says: ships the Synology SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.4
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id045
      status: none
    slug: telegram
    status: profiled
    tags: &id046
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
  tier: observed
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
    mcp: &id047
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id048
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: common
  name: X (Twitter)
  provider: x
  says: ships the X (Twitter) SDK or integration code
  source: https://github.com/Lidarr/Lidarr/tree/develop/src/NzbDrone.Core/Notifications
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/music-streaming/lidarr/
providers:
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id001
  name: Discord
  slug: discord
  status: profiled
  tags: *id002
  url: /providers/discord/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 14.1
  mcp: *id003
  name: Emby
  slug: emby
  status: profiled
  tags: *id004
  url: /providers/emby/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.8
  mcp: *id005
  name: Gotify
  slug: gotify
  status: profiled
  tags: *id006
  url: /providers/gotify/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 3.5
  mcp: *id007
  name: Headphones
  slug: headphones
  status: profiled
  tags: *id008
  url: /providers/headphones/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.2
  mcp: *id009
  name: Join (joaoapps)
  slug: joaoapps-join
  status: profiled
  tags: *id010
  url: /providers/joaoapps-join/
- agent_band: agent-aware
  agent_readiness: 5.4
  band: emerging
  in_catalog: true
  kin_score: 13.3
  mcp: *id011
  name: Kodi
  slug: kodi
  status: profiled
  tags: *id012
  url: /providers/kodi/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: developing
  in_catalog: true
  kin_score: 54.2
  mcp: *id013
  name: Last.fm
  slug: lastfm
  status: profiled
  tags: *id014
  url: /providers/lastfm/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 32.6
  mcp: *id015
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id016
  url: /providers/mailgun/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 37.9
  mcp: *id017
  name: MusicBrainz
  slug: musicbrainz
  status: profiled
  tags: *id018
  url: /providers/musicbrainz/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 3.1
  mcp: *id019
  name: Notifiarr
  slug: notifiarr
  status: profiled
  tags: *id020
  url: /providers/notifiarr/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.9
  mcp: *id021
  name: ntfy
  slug: ntfy
  status: profiled
  tags: *id022
  url: /providers/ntfy/
- agent_band: agent-ready
  agent_readiness: 59.6
  band: strong
  in_catalog: true
  kin_score: 55.9
  mcp: *id023
  name: Plex
  slug: plex
  status: profiled
  tags: *id024
  url: /providers/plex/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.3
  mcp: *id025
  name: Prowl
  slug: prowl
  status: profiled
  tags: *id026
  url: /providers/prowl/
- agent_band: agent-aware
  agent_readiness: 24.9
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id027
  name: Pushbullet
  slug: pushbullet
  status: profiled
  tags: *id028
  url: /providers/pushbullet/
- agent_band: agent-ready
  agent_readiness: 29.5
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id029
  name: Pushcut
  slug: pushcut
  status: profiled
  tags: *id030
  url: /providers/pushcut/
- agent_band: agent-aware
  agent_readiness: 22.0
  band: thin
  in_catalog: true
  kin_score: 29.2
  mcp: *id031
  name: Pushover
  slug: pushover
  status: profiled
  tags: *id032
  url: /providers/pushover/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id033
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id034
  url: /providers/sendgrid/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 41.4
  mcp: *id035
  name: Signal
  slug: signal
  status: profiled
  tags: *id036
  url: /providers/signal/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id037
  name: Simplepush
  slug: simplepush
  status: queued for profiling
  tags: *id038
  url: null
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id039
  name: Slack
  slug: slack
  status: profiled
  tags: *id040
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: developing
  in_catalog: true
  kin_score: 49.8
  mcp: *id041
  name: Spotify
  slug: spotify
  status: profiled
  tags: *id042
  url: /providers/spotify/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: minimal
  in_catalog: true
  kin_score: 7.5
  mcp: *id043
  name: Synology
  slug: synology
  status: profiled
  tags: *id044
  url: /providers/synology/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id045
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id046
  url: /providers/telegram/
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id047
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id048
  url: /providers/x/
siblings:
- name: Ampache
  rows: 27
  url: /applications/music-streaming/ampache/
- name: beets
  rows: 30
  url: /applications/music-streaming/beets/
- name: Funkwhale
  rows: 7
  url: /applications/music-streaming/funkwhale/
- name: Koel
  rows: 18
  url: /applications/music-streaming/koel/
- name: Navidrome
  rows: 4
  url: /applications/music-streaming/navidrome/
- name: Spotify
  rows: 4
  url: /applications/music-streaming/spotify/
sitemap: true
title: 'Lidarr: Music & Audio Streaming reference app'
---
