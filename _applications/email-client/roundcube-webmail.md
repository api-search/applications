---
app: Roundcube Webmail
app_slug: roundcube-webmail
app_url: https://github.com/roundcube/roundcubemail
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  - Outlook.com
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.60
  key: AE-160.60
  layer: common
  name: Credential Security
  providers:
  - Have I Been Pwned
  url: /capabilities/credential-security/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-926
  key: AE-926
  layer: common
  name: Web Hosting & Control Panels
  providers:
  - cPanel
  - DirectAdmin
  - DomainFactory
  - Mail-in-a-Box
  - mailcow
  - Modoboa
  - Plesk
  - Stalwart
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: email-client
  name: Email Client & Hosting
  url: /applications/email-client/
counts:
  declared: 2
  observed: 9
credits: []
evidence:
- route: source code
  url: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
- route: source code
  url: https://raw.githubusercontent.com/roundcube/roundcubemail/master/config/defaults.inc.php
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-926
    key: AE-926
    name: Web Hosting & Control Panels
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.4
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id001
      status: none
    slug: cpanel
    status: profiled
    tags: &id002
    - Control Panel
    - DNS
    - Domains
    - Email
    url: /providers/cpanel/
  layer: common
  name: cPanel
  provider: cpanel
  says: ships the cPanel SDK or integration code
  source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-926
    key: AE-926
    name: Web Hosting & Control Panels
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.5
    band: thin
    in_catalog: true
    kin_score: 27.6
    mcp: &id003
      status: unknown
    slug: directadmin
    status: profiled
    tags: &id004
    - Control Panel
    - Hosting
    - Server Management
    - Web Hosting
    url: /providers/directadmin/
  layer: common
  name: DirectAdmin
  provider: directadmin
  says: ships the DirectAdmin SDK or integration code
  source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-926
    key: AE-926
    name: Web Hosting & Control Panels
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 13.2
    mcp: &id005
      status: none
    slug: domainfactory
    status: profiled
    tags: &id006
    - Company
    - Domains
    - Hosting
    - Web Hosting
    url: /providers/domainfactory/
  layer: common
  name: DomainFactory
  provider: domainfactory
  says: ships the DomainFactory SDK or integration code
  source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.60
    key: AE-160.60
    name: Credential Security
    url: /capabilities/credential-security/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.8
    band: developing
    in_catalog: true
    kin_score: 49.5
    mcp: &id009
      status: none
    slug: have-i-been-pwned
    status: profiled
    tags: &id010
    - Data Breaches
    - Identity
    - Pwned Passwords
    - Security
    url: /providers/have-i-been-pwned/
  layer: common
  name: Have I Been Pwned
  provider: have-i-been-pwned
  says: ships the Have I Been Pwned SDK or integration code
  source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-926
    key: AE-926
    name: Web Hosting & Control Panels
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.2
    band: thin
    in_catalog: true
    kin_score: 32.2
    mcp: &id011
      status: none
    slug: mail-in-a-box
    status: profiled
    tags: &id012
    - Company
    - Email
    - Open Source
    - Self-Hosted
    url: /providers/mail-in-a-box/
  layer: common
  name: Mail-in-a-Box
  provider: mail-in-a-box
  says: ships the Mail-in-a-Box SDK or integration code
  source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-926
    key: AE-926
    name: Web Hosting & Control Panels
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 12.4
    mcp: &id013
      status: none
    slug: mailcow
    status: profiled
    tags: &id014
    - Company
    - Docker
    - Email
    - Open Source
    url: /providers/mailcow/
  layer: common
  name: mailcow
  provider: mailcow
  says: ships the mailcow SDK or integration code
  source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-926
    key: AE-926
    name: Web Hosting & Control Panels
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.8
    band: developing
    in_catalog: true
    kin_score: 39.5
    mcp: &id015
      status: none
    slug: modoboa
    status: profiled
    tags: &id016
    - Email
    - Mail Server
    - Open Source
    - Webmail
    url: /providers/modoboa/
  layer: common
  name: Modoboa
  provider: modoboa
  says: ships the Modoboa SDK or integration code
  source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-926
    key: AE-926
    name: Web Hosting & Control Panels
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.3
    band: developing
    in_catalog: true
    kin_score: 45.2
    mcp: &id019
      status: none
    slug: plesk
    status: profiled
    tags: &id020
    - Company
    - Control Panel
    - Server Management
    - Web Hosting
    url: /providers/plesk/
  layer: common
  name: Plesk
  provider: plesk
  says: ships the Plesk SDK or integration code
  source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-926
    key: AE-926
    name: Web Hosting & Control Panels
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.8
    band: thin
    in_catalog: true
    kin_score: 32.6
    mcp: &id021
      status: none
    slug: stalwart
    status: profiled
    tags: &id022
    - Collaboration
    - Email
    - Open Source
    - Rust
    url: /providers/stalwart/
  layer: common
  name: Stalwart
  provider: stalwart
  says: ships the Stalwart SDK or integration code
  source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
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
    agent_band: agent-ready
    agent_readiness: 43.2
    band: exemplar
    in_catalog: true
    kin_score: 66.8
    mcp: &id007
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id008
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: domain
  name: Gmail
  provider: google-gmail
  says: lists Gmail as an integration
  source: https://raw.githubusercontent.com/roundcube/roundcubemail/master/config/defaults.inc.php
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
    mcp: &id017
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id018
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: domain
  name: Outlook.com
  provider: microsoft-outlook
  says: lists Outlook.com as an integration
  source: https://raw.githubusercontent.com/roundcube/roundcubemail/master/config/defaults.inc.php
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/email-client/roundcube-webmail/
providers:
- agent_band: agent-ready
  agent_readiness: 50.4
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id001
  name: cPanel
  slug: cpanel
  status: profiled
  tags: *id002
  url: /providers/cpanel/
- agent_band: agent-aware
  agent_readiness: 14.5
  band: thin
  in_catalog: true
  kin_score: 27.6
  mcp: *id003
  name: DirectAdmin
  slug: directadmin
  status: profiled
  tags: *id004
  url: /providers/directadmin/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.2
  mcp: *id005
  name: DomainFactory
  slug: domainfactory
  status: profiled
  tags: *id006
  url: /providers/domainfactory/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id007
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id008
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 31.8
  band: developing
  in_catalog: true
  kin_score: 49.5
  mcp: *id009
  name: Have I Been Pwned
  slug: have-i-been-pwned
  status: profiled
  tags: *id010
  url: /providers/have-i-been-pwned/
- agent_band: agent-aware
  agent_readiness: 22.2
  band: thin
  in_catalog: true
  kin_score: 32.2
  mcp: *id011
  name: Mail-in-a-Box
  slug: mail-in-a-box
  status: profiled
  tags: *id012
  url: /providers/mail-in-a-box/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 12.4
  mcp: *id013
  name: mailcow
  slug: mailcow
  status: profiled
  tags: *id014
  url: /providers/mailcow/
- agent_band: agent-aware
  agent_readiness: 23.8
  band: developing
  in_catalog: true
  kin_score: 39.5
  mcp: *id015
  name: Modoboa
  slug: modoboa
  status: profiled
  tags: *id016
  url: /providers/modoboa/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 70.8
  mcp: *id017
  name: Outlook.com
  slug: microsoft-outlook
  status: profiled
  tags: *id018
  url: /providers/microsoft-outlook/
- agent_band: agent-aware
  agent_readiness: 19.3
  band: developing
  in_catalog: true
  kin_score: 45.2
  mcp: *id019
  name: Plesk
  slug: plesk
  status: profiled
  tags: *id020
  url: /providers/plesk/
- agent_band: agent-aware
  agent_readiness: 14.8
  band: thin
  in_catalog: true
  kin_score: 32.6
  mcp: *id021
  name: Stalwart
  slug: stalwart
  status: profiled
  tags: *id022
  url: /providers/stalwart/
siblings:
- name: FairEmail
  rows: 26
  url: /applications/email-client/fairemail/
- name: Mail-in-a-Box
  rows: 5
  url: /applications/email-client/mail-in-a-box/
- name: 'mailcow: dockerized'
  rows: 2
  url: /applications/email-client/mailcow-dockerized/
- name: Proton Mail (Android)
  rows: 3
  url: /applications/email-client/proton-mail-android/
- name: Stalwart Mail Server
  rows: 19
  url: /applications/email-client/stalwart-mail-server/
- name: Thunderbird for Android
  rows: 7
  url: /applications/email-client/thunderbird-for-android/
sitemap: true
title: 'Roundcube Webmail: Email Client & Hosting reference app'
---
