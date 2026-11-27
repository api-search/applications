---
app: BigBlueButton
app_slug: bigbluebutton
app_url: https://github.com/bigbluebutton/bigbluebutton
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.30.10
  key: AE-110.30.10
  layer: domain
  name: Speech-to-Text
  providers:
  - Gladia
  url: /capabilities/speech-voice/
  via_parent: Speech & Voice
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - hCaptcha
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Papertrail
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: video-conferencing
  name: Video Conferencing & Webinars
  url: /applications/video-conferencing/
counts:
  declared: 1
  observed: 4
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/bigbluebutton/greenlight/master/Gemfile
- route: source code
  url: https://raw.githubusercontent.com/bigbluebutton/bbb-transcription-controller/main/config/default.example.yml
- route: source code
  url: https://raw.githubusercontent.com/bigbluebutton/bigbluebutton/develop/bigbluebutton-web/grails-app/conf/bigbluebutton.properties
- route: source code
  url: https://raw.githubusercontent.com/bigbluebutton/greenlight/master/sample.env
integrations:
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
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://raw.githubusercontent.com/bigbluebutton/greenlight/master/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.10
    key: AE-110.30.10
    name: Speech-to-Text
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.6
    band: developing
    in_catalog: true
    kin_score: 49.4
    mcp: &id003
      source: https://github.com/gladiaio/gladia-mcp
      status: verified
    slug: gladia
    status: profiled
    tags: &id004
    - Audio Intelligence
    - Real-Time
    - Speech-to-Text
    - Transcription
    url: /providers/gladia/
  layer: domain
  name: Gladia
  provider: gladia
  says: ships the Gladia SDK or integration code
  source: https://raw.githubusercontent.com/bigbluebutton/bbb-transcription-controller/main/config/default.example.yml
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
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id005
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id006
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://raw.githubusercontent.com/bigbluebutton/greenlight/master/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.5
    band: thin
    in_catalog: true
    kin_score: 31.1
    mcp: &id007
      status: none
    slug: hcaptcha
    status: profiled
    tags: &id008
    - Bot Defense
    - CAPTCHA
    - Privacy
    - hCaptcha
    url: /providers/hcaptcha/
  layer: common
  name: hCaptcha
  provider: hcaptcha
  says: ships the hCaptcha SDK or integration code
  source: https://raw.githubusercontent.com/bigbluebutton/greenlight/master/Gemfile
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id009
      status: unchecked
    slug: papertrail
    status: queued for profiling
    tags: &id010 []
    url: null
  layer: common
  name: Papertrail
  provider: papertrail
  says: lists Papertrail as an integration
  source: https://raw.githubusercontent.com/bigbluebutton/greenlight/master/sample.env
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/video-conferencing/bigbluebutton/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 33.6
  band: developing
  in_catalog: true
  kin_score: 49.4
  mcp: *id003
  name: Gladia
  slug: gladia
  status: profiled
  tags: *id004
  url: /providers/gladia/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id005
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id006
  url: /providers/gcp-cloud-storage/
- agent_band: agent-aware
  agent_readiness: 17.5
  band: thin
  in_catalog: true
  kin_score: 31.1
  mcp: *id007
  name: hCaptcha
  slug: hcaptcha
  status: profiled
  tags: *id008
  url: /providers/hcaptcha/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id009
  name: Papertrail
  slug: papertrail
  status: queued for profiling
  tags: *id010
  url: null
siblings:
- name: Jitsi Meet
  rows: 9
  url: /applications/video-conferencing/jitsi-meet/
- name: LiveKit Meet
  rows: 3
  url: /applications/video-conferencing/livekit-meet/
- name: Microsoft Teams
  rows: 1
  url: /applications/video-conferencing/microsoft-teams/
- name: Nextcloud Talk
  rows: 8
  url: /applications/video-conferencing/nextcloud-talk/
- name: Webex Meetings
  rows: 2
  url: /applications/video-conferencing/webex-meetings/
- name: Zoom
  rows: 7
  url: /applications/video-conferencing/zoom/
sitemap: true
title: 'BigBlueButton: Video Conferencing & Webinars reference app'
---
