---
app: Dropbox
app_slug: dropbox
app_url: https://www.dropbox.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - HubSpot
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: common
  name: Design & Creative Editing
  providers:
  - Adobe
  - Canva
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: Turbo EA
  id: BC-1120.50
  key: design-software-cad-management
  layer: common
  name: Design Software & CAD Management
  providers:
  - Autodesk
  url: /capabilities/design-software-cad-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.50
  key: BC-600.50.50
  layer: common
  name: End-User Computing Management
  providers:
  - Google Workspace
  - Microsoft 365 (Copilot)
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Adjust
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Amplitude
  - Google Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-2800.10
  key: scheduling-appointment-management
  layer: common
  name: Scheduling & Appointment Management
  providers:
  - Reclaim.ai
  url: /capabilities/scheduling-appointment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - AWS
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: common
  name: Video Calling
  providers:
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Anthropic (Claude)
  - Google Gemini
  - OpenAI (ChatGPT)
  - xAI (SpaceXAI)
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: cloud-storage-file-sync
  name: Cloud Storage & File Sync
  url: /applications/cloud-storage-file-sync/
counts:
  declared: 14
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.dropbox.android/latest/
- route: integrations page
  url: https://www.dropbox.com/app-integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: thin
    in_catalog: true
    kin_score: 30.9
    mcp: &id001
      status: none
    slug: adjust
    status: profiled
    tags: &id002
    - Analytics
    - Attribution
    - Deep Linking
    - Measurements
    url: /providers/adjust/
  layer: common
  name: Adjust
  provider: adjust
  says: ships the Adjust SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.dropbox.android/latest/
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
    agent_readiness: 56.9
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id005
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id006
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: ships the Amplitude SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.dropbox.android/latest/
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
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id015
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id016
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.dropbox.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id029
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id030
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.dropbox.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.9
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id003
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe
    status: profiled
    tags: &id004
    - Adobe
    - Analytics
    - E-Signature
    - Fortune 1000
    url: /providers/adobe/
  layer: common
  name: Adobe
  provider: adobe
  says: lists Adobe as an integration
  source: https://www.dropbox.com/app-integrations
  tier: declared
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
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id007
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id008
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic (Claude)
  provider: anthropic
  says: lists Anthropic (Claude) as an integration
  source: https://www.dropbox.com/app-integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1120.50
    key: design-software-cad-management
    name: Design Software & CAD Management
    url: /capabilities/design-software-cad-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.0
    band: exemplar
    in_catalog: true
    kin_score: 72.3
    mcp: &id009
      source: https://github.com/autodesk-platform-services/aps-mcp-server-nodejs
      status: verified
    slug: autodesk
    status: profiled
    tags: &id010
    - 3D Modeling
    - Autodesk
    - Digital Twin
    - Fortune 1000
    url: /providers/autodesk/
  layer: common
  name: Autodesk
  provider: autodesk
  says: lists Autodesk as an integration
  source: https://www.dropbox.com/app-integrations
  tier: declared
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
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id011
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id012
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: AWS
  provider: amazon-web-services
  says: lists AWS as an integration
  source: https://www.dropbox.com/app-integrations
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
  layer: common
  name: Canva
  provider: canva
  says: lists Canva as an integration
  source: https://www.dropbox.com/app-integrations
  tier: declared
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
    agent_readiness: 35.0
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id017
      status: none
    slug: google-gemini
    status: profiled
    tags: &id018
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini
  provider: google-gemini
  says: lists Google Gemini as an integration
  source: https://www.dropbox.com/app-integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.50.50
    key: BC-600.50.50
    name: End-User Computing Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id019
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id020
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
  layer: common
  name: Google Workspace
  provider: google-workspace
  says: lists Google Workspace as an integration
  source: https://www.dropbox.com/app-integrations
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
    mcp: &id021
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id022
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: common
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://www.dropbox.com/app-integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.50.50
    key: BC-600.50.50
    name: End-User Computing Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id023
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-365
    status: profiled
    tags: &id024
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/microsoft-365/
  layer: common
  name: Microsoft 365 (Copilot)
  provider: microsoft-365
  says: lists Microsoft 365 (Copilot) as an integration
  source: https://www.dropbox.com/app-integrations
  tier: declared
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
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id025
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id026
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI (ChatGPT)
  provider: openai
  says: lists OpenAI (ChatGPT) as an integration
  source: https://www.dropbox.com/app-integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 41.8
    mcp: &id027
      status: none
    slug: reclaim-ai
    status: profiled
    tags: &id028
    - Artificial Intelligence
    - Calendar
    - Productivity
    - Scheduling
    url: /providers/reclaim-ai/
  layer: common
  name: Reclaim.ai
  provider: reclaim-ai
  says: lists Reclaim.ai as an integration
  source: https://www.dropbox.com/app-integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id031
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id032
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.dropbox.com/app-integrations
  tier: declared
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
    agent_readiness: 39.4
    band: thin
    in_catalog: true
    kin_score: 32.3
    mcp: &id033
      status: none
    slug: xai
    status: profiled
    tags: &id034
    - Artificial Intelligence
    - Foundation Models
    - Grok
    - LLM
    url: /providers/xai/
  layer: agent
  name: xAI (SpaceXAI)
  provider: xai
  says: lists xAI (SpaceXAI) as an integration
  source: https://www.dropbox.com/app-integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id035
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id036
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: common
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://www.dropbox.com/app-integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/cloud-storage-file-sync/dropbox/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: thin
  in_catalog: true
  kin_score: 30.9
  mcp: *id001
  name: Adjust
  slug: adjust
  status: profiled
  tags: *id002
  url: /providers/adjust/
- agent_band: agent-ready
  agent_readiness: 62.9
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id003
  name: Adobe
  slug: adobe
  status: profiled
  tags: *id004
  url: /providers/adobe/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id005
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id006
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id007
  name: Anthropic (Claude)
  slug: anthropic
  status: profiled
  tags: *id008
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 46.0
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id009
  name: Autodesk
  slug: autodesk
  status: profiled
  tags: *id010
  url: /providers/autodesk/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id011
  name: AWS
  slug: amazon-web-services
  status: profiled
  tags: *id012
  url: /providers/amazon-web-services/
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
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id015
  name: Google Firebase Analytics
  slug: google-firebase
  status: profiled
  tags: *id016
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id017
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id018
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id019
  name: Google Workspace
  slug: google-workspace
  status: profiled
  tags: *id020
  url: /providers/google-workspace/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id021
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id022
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id023
  name: Microsoft 365 (Copilot)
  slug: microsoft-365
  status: profiled
  tags: *id024
  url: /providers/microsoft-365/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id025
  name: OpenAI (ChatGPT)
  slug: openai
  status: profiled
  tags: *id026
  url: /providers/openai/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 41.8
  mcp: *id027
  name: Reclaim.ai
  slug: reclaim-ai
  status: profiled
  tags: *id028
  url: /providers/reclaim-ai/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id029
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id030
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id031
  name: Slack
  slug: slack
  status: profiled
  tags: *id032
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 39.4
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id033
  name: xAI (SpaceXAI)
  slug: xai
  status: profiled
  tags: *id034
  url: /providers/xai/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id035
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id036
  url: /providers/zoom/
siblings:
- name: Box
  rows: 18
  url: /applications/cloud-storage-file-sync/box/
- name: Filestash
  rows: 8
  url: /applications/cloud-storage-file-sync/filestash/
- name: Nextcloud
  rows: 32
  url: /applications/cloud-storage-file-sync/nextcloud/
- name: ownCloud Infinite Scale
  rows: 3
  url: /applications/cloud-storage-file-sync/owncloud-infinite-scale/
- name: rclone
  rows: 71
  url: /applications/cloud-storage-file-sync/rclone/
- name: Seafile
  rows: 8
  url: /applications/cloud-storage-file-sync/seafile/
- name: Syncthing
  rows: 2
  url: /applications/cloud-storage-file-sync/syncthing/
sitemap: true
title: 'Dropbox: Cloud Storage & File Sync reference app'
---
