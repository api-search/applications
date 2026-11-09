---
app: DAVx5
app_slug: davx5
app_url: https://github.com/bitfireAT/davx5-ose
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  - Google Contacts
  - Baikal
  - Fastmail
  - fruux
  - GMX (mail)
  - iCloud
  - Infomaniak
  - mailbox.org
  - Nextcloud
  - Posteo
  - Radicale
  - Yahoo
  - Zoho
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
category:
  id: calendar-contacts
  name: Calendar & Contacts
  url: /applications/calendar-contacts/
counts:
  declared: 12
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/at.bitfire.davdroid/latest/
- route: dependency manifest
  url: https://github.com/bitfireAT/davx5-ose/blob/HEAD/gradle/libs.versions.toml
- route: documentation
  url: https://www.davx5.com/tested-with
- route: source code
  url: https://github.com/bitfireAT/davx5-ose/blob/HEAD/core/src/main/kotlin/at/bitfire/davdroid/ui/setup/GoogleLogin.kt
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id009
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id010
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: domain
  name: Google Calendar
  provider: google-calendar
  says: ships the Google Calendar SDK or integration code
  source: https://github.com/bitfireAT/davx5-ose/blob/HEAD/core/src/main/kotlin/at/bitfire/davdroid/ui/setup/GoogleLogin.kt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 45.6
    mcp: &id011
      source: https://docs.cloud.google.com/mcp/supported-products
      status: verified
    slug: google-people
    status: profiled
    tags: &id012
    - Address Book
    - Contacts
    - Google
    - People
    url: /providers/google-people/
  layer: domain
  name: Google Contacts
  provider: google-people
  says: ships the Google Contacts SDK or integration code
  source: https://github.com/bitfireAT/davx5-ose/blob/HEAD/core/src/main/kotlin/at/bitfire/davdroid/ui/setup/GoogleLogin.kt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 7.5
    mcp: &id001
      status: none
    slug: baikal
    status: profiled
    tags: &id002
    - Calendar
    - CardDAV
    - Company
    - Open Source
    url: /providers/baikal/
  layer: domain
  name: Baikal
  provider: baikal
  says: lists Baikal as an integration
  source: https://www.davx5.com/tested-with
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
    agent_band: agent-aware
    agent_readiness: 17.6
    band: thin
    in_catalog: true
    kin_score: 28.8
    mcp: &id003
      status: none
    slug: fastmail
    status: profiled
    tags: &id004
    - Business
    - Email
    - Privacy
    - Security
    url: /providers/fastmail/
  layer: domain
  name: Fastmail
  provider: fastmail
  says: lists Fastmail as an integration
  source: https://www.davx5.com/tested-with
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 20.5
    mcp: &id005
      status: none
    slug: fruux
    status: profiled
    tags: &id006
    - Calendar
    - Contacts
    - Sync
    - Task
    url: /providers/fruux/
  layer: domain
  name: fruux
  provider: fruux
  says: lists fruux as an integration
  source: https://www.davx5.com/tested-with
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
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 11.5
    mcp: &id007
      status: none
    slug: gmx-net
    status: profiled
    tags: &id008
    - Cloud
    - Company
    - Email
    - Free
    url: /providers/gmx-net/
  layer: domain
  name: GMX (mail)
  provider: gmx-net
  says: lists GMX (mail) as an integration
  source: https://www.davx5.com/tested-with
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
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id013
      status: none
    slug: apple
    status: profiled
    tags: &id014
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: iCloud
  provider: apple
  says: lists iCloud as an integration
  source: https://www.davx5.com/tested-with
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
    agent_band: agent-aware
    agent_readiness: 13.7
    band: emerging
    in_catalog: true
    kin_score: 11.0
    mcp: &id015
      source: https://github.com/Infomaniak/mcp-server-kdrive
      status: verified
    slug: infomaniak
    status: profiled
    tags: &id016
    - Cloud
    - Company
    - Email
    - Hosting
    url: /providers/infomaniak/
  layer: domain
  name: Infomaniak
  provider: infomaniak
  says: lists Infomaniak as an integration
  source: https://www.davx5.com/tested-with
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
    agent_readiness: 30.6
    band: emerging
    in_catalog: true
    kin_score: 19.6
    mcp: &id017
      status: unknown
    slug: mailbox-org
    status: profiled
    tags: &id018
    - Collaboration
    - Email
    - GDPR
    - Privacy
    url: /providers/mailbox-org/
  layer: domain
  name: mailbox.org
  provider: mailbox-org
  says: lists mailbox.org as an integration
  source: https://www.davx5.com/tested-with
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
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 33.0
    mcp: &id019
      status: none
    slug: nextcloud
    status: profiled
    tags: &id020
    - Collaboration
    - File Sharing
    - File Sync
    - Self-Hosted
    url: /providers/nextcloud/
  layer: domain
  name: Nextcloud
  provider: nextcloud
  says: lists Nextcloud as an integration
  source: https://www.davx5.com/tested-with
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.5
    mcp: &id021
      status: none
    slug: posteo
    status: profiled
    tags: &id022
    - Email
    - Privacy
    - Security
    - Sustainability
    url: /providers/posteo/
  layer: domain
  name: Posteo
  provider: posteo
  says: lists Posteo as an integration
  source: https://www.davx5.com/tested-with
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
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 7.6
    mcp: &id023
      status: unknown
    slug: radicale
    status: profiled
    tags: &id024
    - CalDAV
    - CardDAV
    - Company
    - Open Source
    url: /providers/radicale/
  layer: domain
  name: Radicale
  provider: radicale
  says: lists Radicale as an integration
  source: https://www.davx5.com/tested-with
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
    agent_band: agent-aware
    agent_readiness: 16.2
    band: developing
    in_catalog: true
    kin_score: 41.4
    mcp: &id025
      status: none
    slug: yahoo
    status: profiled
    tags: &id026
    - Advertising
    - DSP
    - Fantasy Sports
    - Programmatic Advertising
    url: /providers/yahoo/
  layer: domain
  name: Yahoo
  provider: yahoo
  says: lists Yahoo as an integration
  source: https://www.davx5.com/tested-with
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
    agent_readiness: 33.0
    band: strong
    in_catalog: true
    kin_score: 63.5
    mcp: &id027
      source: https://www.zoho.com/mcp/
      status: verified
    slug: zoho
    status: profiled
    tags: &id028
    - Analytics
    - CRM
    - Collaboration
    - Customer Service
    url: /providers/zoho/
  layer: domain
  name: Zoho
  provider: zoho
  says: lists Zoho as an integration
  source: https://www.davx5.com/tested-with
  tier: declared
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/calendar-contacts/davx5/
providers:
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 7.5
  mcp: *id001
  name: Baikal
  slug: baikal
  status: profiled
  tags: *id002
  url: /providers/baikal/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id003
  name: Fastmail
  slug: fastmail
  status: profiled
  tags: *id004
  url: /providers/fastmail/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.5
  mcp: *id005
  name: fruux
  slug: fruux
  status: profiled
  tags: *id006
  url: /providers/fruux/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 11.5
  mcp: *id007
  name: GMX (mail)
  slug: gmx-net
  status: profiled
  tags: *id008
  url: /providers/gmx-net/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id009
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id010
  url: /providers/google-calendar/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 45.6
  mcp: *id011
  name: Google Contacts
  slug: google-people
  status: profiled
  tags: *id012
  url: /providers/google-people/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id013
  name: iCloud
  slug: apple
  status: profiled
  tags: *id014
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 13.7
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id015
  name: Infomaniak
  slug: infomaniak
  status: profiled
  tags: *id016
  url: /providers/infomaniak/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: emerging
  in_catalog: true
  kin_score: 19.6
  mcp: *id017
  name: mailbox.org
  slug: mailbox-org
  status: profiled
  tags: *id018
  url: /providers/mailbox-org/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 33.0
  mcp: *id019
  name: Nextcloud
  slug: nextcloud
  status: profiled
  tags: *id020
  url: /providers/nextcloud/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.5
  mcp: *id021
  name: Posteo
  slug: posteo
  status: profiled
  tags: *id022
  url: /providers/posteo/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 7.6
  mcp: *id023
  name: Radicale
  slug: radicale
  status: profiled
  tags: *id024
  url: /providers/radicale/
- agent_band: agent-aware
  agent_readiness: 16.2
  band: developing
  in_catalog: true
  kin_score: 41.4
  mcp: *id025
  name: Yahoo
  slug: yahoo
  status: profiled
  tags: *id026
  url: /providers/yahoo/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: strong
  in_catalog: true
  kin_score: 63.5
  mcp: *id027
  name: Zoho
  slug: zoho
  status: profiled
  tags: *id028
  url: /providers/zoho/
siblings:
- name: Etar
  rows: 0
  url: /applications/calendar-contacts/etar/
- name: Fantastical
  rows: 10
  url: /applications/calendar-contacts/fantastical/
- name: Monica
  rows: 15
  url: /applications/calendar-contacts/monica/
- name: Morgen
  rows: 20
  url: /applications/calendar-contacts/morgen/
- name: Notion Calendar
  rows: 10
  url: /applications/calendar-contacts/notion-calendar/
- name: Radicale
  rows: 0
  url: /applications/calendar-contacts/radicale/
sitemap: true
title: 'DAVx5: Calendar & Contacts reference app'
---
