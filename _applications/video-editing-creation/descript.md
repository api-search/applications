---
app: Descript
app_slug: descript
app_url: https://www.descript.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Google Drive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: domain
  name: Design & Creative Editing
  providers:
  - Adobe Audition
  - Adobe Premiere
  - Avid Pro Tools
  - DaVinci Resolve
  - Ecamm
  - Final Cut Pro / Apple Logic
  - Headliner
  - REAPER
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: domain
  name: Online Forms & Survey Collection
  providers:
  - VideoAsk
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: API Evangelist extension
  id: AE-170.20.20
  key: AE-170.20.20
  layer: domain
  name: Podcast Hosting
  providers:
  - Blubrry
  - Buzzsprout
  - Captivate
  - Castos
  - Hello Audio
  - Podbean
  - Podcast.co
  - Transistor
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Riverside
  - SquadCast
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.10.10
  key: AE-170.10.10
  layer: domain
  name: Video Hosting & Encoding
  providers:
  - eWebinar
  - HubSpot
  - Restream
  - Wistia
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Raycast
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - ChatGPT
  - Claude
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: video-editing-creation
  name: Video & Photo Editing / Creator Tools
  url: /applications/video-editing-creation/
counts:
  declared: 30
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.descript.com/integrations
integrations:
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
    agent_readiness: 65.9
    band: exemplar
    in_catalog: true
    kin_score: 76.2
    mcp: &id001
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe
    status: profiled
    tags: &id002
    - Adobe
    - Analytics
    - E-Signature
    - Fortune 1000
    url: /providers/adobe/
  layer: domain
  name: Adobe Audition
  provider: adobe
  says: lists Adobe Audition as an integration
  source: https://www.descript.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 38.5
    band: strong
    in_catalog: true
    kin_score: 58.0
    mcp: &id003
      status: none
    slug: adobe-premiere
    status: profiled
    tags: &id004
    - Adobe
    - Automation
    - Creative Cloud
    - Media
    url: /providers/adobe-premiere/
  layer: domain
  name: Adobe Premiere
  provider: adobe-premiere
  says: lists Adobe Premiere as an integration
  source: https://www.descript.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 15.1
    band: emerging
    in_catalog: true
    kin_score: 16.5
    mcp: &id005
      status: unknown
    slug: avid
    status: profiled
    tags: &id006
    - Audio
    - Company
    - Media
    - Software
    url: /providers/avid/
  layer: domain
  name: Avid Pro Tools
  provider: avid
  says: lists Avid Pro Tools as an integration
  source: https://www.descript.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.20
    key: AE-170.20.20
    name: Podcast Hosting
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.8
    band: strong
    in_catalog: true
    kin_score: 58.1
    mcp: &id007
      status: unknown
    slug: blubrry-api-restful-api-for-podcast-publishing-statistics
    status: profiled
    tags: &id008
    - Audio
    - Media
    - Podcasts
    - Publishing
    url: /providers/blubrry-api-restful-api-for-podcast-publishing-statistics/
  layer: domain
  name: Blubrry
  provider: blubrry-api-restful-api-for-podcast-publishing-statistics
  says: lists Blubrry as an integration
  source: https://www.descript.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.20
    key: AE-170.20.20
    name: Podcast Hosting
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 28.6
    mcp: &id009
      status: unknown
    slug: buzzsprout
    status: profiled
    tags: &id010
    - Audio
    - Media
    - Podcast Hosting
    - Podcasts
    url: /providers/buzzsprout/
  layer: domain
  name: Buzzsprout
  provider: buzzsprout
  says: lists Buzzsprout as an integration
  source: https://www.descript.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.20
    key: AE-170.20.20
    name: Podcast Hosting
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.1
    band: thin
    in_catalog: true
    kin_score: 31.1
    mcp: &id011
      status: none
    slug: captivate-fm
    status: profiled
    tags: &id012
    - Episodes
    - Media
    - Podcast Hosting
    - Podcasts
    url: /providers/captivate-fm/
  layer: domain
  name: Captivate
  provider: captivate-fm
  says: lists Captivate as an integration
  source: https://www.descript.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.20
    key: AE-170.20.20
    name: Podcast Hosting
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 23.2
    mcp: &id013
      status: unknown
    slug: castos
    status: profiled
    tags: &id014
    - Analytics
    - Hosting
    - Media
    - Podcasts
    url: /providers/castos/
  layer: domain
  name: Castos
  provider: castos
  says: lists Castos as an integration
  source: https://www.descript.com/integrations
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
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id015
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: ChatGPT
  provider: openai
  says: lists ChatGPT as an integration
  source: https://www.descript.com/integrations
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
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 87.5
    mcp: &id017
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id018
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Claude
  provider: anthropic
  says: lists Claude as an integration
  source: https://www.descript.com/integrations
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
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 9.0
    mcp: &id019
      status: none
    slug: blackmagic-design
    status: profiled
    tags: &id020
    - Broadcast
    - Cinema
    - Software
    - Video
    url: /providers/blackmagic-design/
  layer: domain
  name: DaVinci Resolve
  provider: blackmagic-design
  says: lists DaVinci Resolve as an integration
  source: https://www.descript.com/integrations
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 18.4
    mcp: &id021
      status: unknown
    slug: ecamm
    status: profiled
    tags: &id022
    - Live Streaming
    - Multistreaming
    - Video Production
    - Virtual Camera
    url: /providers/ecamm/
  layer: domain
  name: Ecamm
  provider: ecamm
  says: lists Ecamm as an integration
  source: https://www.descript.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.6
    band: emerging
    in_catalog: true
    kin_score: 20.6
    mcp: &id023
      status: none
    slug: ewebinar
    status: profiled
    tags: &id024
    - Company
    - On-Demand
    - Video
    - Webinar
    url: /providers/ewebinar/
  layer: domain
  name: eWebinar
  provider: ewebinar
  says: lists eWebinar as an integration
  source: https://www.descript.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id025
      status: none
    slug: apple
    status: profiled
    tags: &id026
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Final Cut Pro / Apple Logic
  provider: apple
  says: lists Final Cut Pro / Apple Logic as an integration
  source: https://www.descript.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.3
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id027
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id028
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: domain
  name: Google Drive
  provider: google-drive
  says: lists Google Drive as an integration
  source: https://www.descript.com/integrations
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
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 3.1
    mcp: &id029
      status: unknown
    slug: headliner
    status: profiled
    tags: &id030
    - Marketing
    - Podcasts
    - Software-as-a-Service
    - Video
    url: /providers/headliner/
  layer: domain
  name: Headliner
  provider: headliner
  says: lists Headliner as an integration
  source: https://www.descript.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.20
    key: AE-170.20.20
    name: Podcast Hosting
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 11.5
    band: thin
    in_catalog: true
    kin_score: 35.6
    mcp: &id031
      status: none
    slug: hello-audio
    status: profiled
    tags: &id032
    - Audio
    - Company
    - Podcasts
    - Software-as-a-Service
    url: /providers/hello-audio/
  layer: domain
  name: Hello Audio
  provider: hello-audio
  says: lists Hello Audio as an integration
  source: https://www.descript.com/integrations
  tier: declared
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
    agent_readiness: 52.7
    band: exemplar
    in_catalog: true
    kin_score: 94.6
    mcp: &id033
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id034
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://www.descript.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.20
    key: AE-170.20.20
    name: Podcast Hosting
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.9
    band: thin
    in_catalog: true
    kin_score: 33.0
    mcp: &id035
      status: none
    slug: podbean
    status: profiled
    tags: &id036
    - Audio
    - Media
    - Podcast Hosting
    - Podcasts
    url: /providers/podbean/
  layer: domain
  name: Podbean
  provider: podbean
  says: lists Podbean as an integration
  source: https://www.descript.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.20
    key: AE-170.20.20
    name: Podcast Hosting
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.9
    band: thin
    in_catalog: true
    kin_score: 37.8
    mcp: &id037
      status: unknown
    slug: podcast-co
    status: profiled
    tags: &id038
    - Audio
    - Hosting
    - Podcasts
    - Software-as-a-Service
    url: /providers/podcast-co/
  layer: domain
  name: Podcast.co
  provider: podcast-co
  says: lists Podcast.co as an integration
  source: https://www.descript.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 13.6
    band: emerging
    in_catalog: true
    kin_score: 25.7
    mcp: &id039
      status: none
    slug: raycast
    status: profiled
    tags: &id040
    - Extensions
    - Launcher
    - Productivity
    - SDK
    url: /providers/raycast/
  layer: common
  name: Raycast
  provider: raycast
  says: lists Raycast as an integration
  source: https://www.descript.com/integrations
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.0
    mcp: &id041
      status: unknown
    slug: cockos-reaper
    status: profiled
    tags: &id042
    - Audio
    - Digital Audio Workstation
    - Music Production
    - Windows
    url: /providers/cockos-reaper/
  layer: domain
  name: REAPER
  provider: cockos-reaper
  says: lists REAPER as an integration
  source: https://www.descript.com/integrations
  tier: declared
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
    agent_readiness: 35.3
    band: thin
    in_catalog: true
    kin_score: 35.0
    mcp: &id043
      source: https://github.com/restreamio/cursor-mcp-plugin
      status: verified
    slug: restream
    status: profiled
    tags: &id044
    - Broadcast
    - Chat
    - Content Delivery
    - Live Streaming
    url: /providers/restream/
  layer: domain
  name: Restream
  provider: restream
  says: lists Restream as an integration
  source: https://www.descript.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 19.0
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id045
      source: https://github.com/riversidefm/riverside-mcp-public
      status: verified
    slug: riverside
    status: profiled
    tags: &id046
    - Content Creation
    - Media
    - Podcasts
    - Video Recording
    url: /providers/riverside/
  layer: domain
  name: Riverside
  provider: riverside
  says: lists Riverside as an integration
  source: https://www.descript.com/integrations
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id047
      status: unchecked
    slug: squadcast-fm
    status: queued for profiling
    tags: &id048 []
    url: null
  layer: domain
  name: SquadCast
  provider: squadcast-fm
  says: lists SquadCast as an integration
  source: https://www.descript.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.20
    key: AE-170.20.20
    name: Podcast Hosting
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.6
    band: developing
    in_catalog: true
    kin_score: 41.1
    mcp: &id049
      source: https://mcp.transistor.fm/
      status: verified
    slug: transistor
    status: profiled
    tags: &id050
    - Analytics
    - Media
    - Podcast Hosting
    - Podcasts
    url: /providers/transistor/
  layer: domain
  name: Transistor
  provider: transistor
  says: lists Transistor as an integration
  source: https://www.descript.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.5
    band: thin
    in_catalog: true
    kin_score: 37.6
    mcp: &id051
      source: https://www.typeform.com/developers/mcp
      status: verified
    slug: typeform
    status: profiled
    tags: &id052
    - Forms
    - Lead Capture
    - Software-as-a-Service
    - Surveys
    url: /providers/typeform/
  layer: domain
  name: VideoAsk
  provider: typeform
  says: lists VideoAsk as an integration
  source: https://www.descript.com/integrations
  tier: declared
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
    agent_readiness: 35.7
    band: exemplar
    in_catalog: true
    kin_score: 75.8
    mcp: &id053
      source: https://docs.wistia.com/docs/mcp-server-guide
      status: documented
    slug: wistia
    status: profiled
    tags: &id054
    - Lead Generation
    - Video Analytics
    - Video Hosting
    - Video Marketing
    url: /providers/wistia/
  layer: domain
  name: Wistia
  provider: wistia
  says: lists Wistia as an integration
  source: https://www.descript.com/integrations
  tier: declared
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
    agent_readiness: 43.4
    band: strong
    in_catalog: true
    kin_score: 62.6
    mcp: &id055
      status: none
    slug: youtube
    status: profiled
    tags: &id056
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: lists YouTube as an integration
  source: https://www.descript.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id057
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id058
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.descript.com/integrations
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
    agent_readiness: 55.2
    band: strong
    in_catalog: true
    kin_score: 56.2
    mcp: &id059
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id060
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: domain
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://www.descript.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/video-editing-creation/descript/
providers:
- agent_band: agent-ready
  agent_readiness: 65.9
  band: exemplar
  in_catalog: true
  kin_score: 76.2
  mcp: *id001
  name: Adobe Audition
  slug: adobe
  status: profiled
  tags: *id002
  url: /providers/adobe/
- agent_band: agent-ready
  agent_readiness: 38.5
  band: strong
  in_catalog: true
  kin_score: 58.0
  mcp: *id003
  name: Adobe Premiere
  slug: adobe-premiere
  status: profiled
  tags: *id004
  url: /providers/adobe-premiere/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 16.5
  mcp: *id005
  name: Avid Pro Tools
  slug: avid
  status: profiled
  tags: *id006
  url: /providers/avid/
- agent_band: agent-ready
  agent_readiness: 32.8
  band: strong
  in_catalog: true
  kin_score: 58.1
  mcp: *id007
  name: Blubrry
  slug: blubrry-api-restful-api-for-podcast-publishing-statistics
  status: profiled
  tags: *id008
  url: /providers/blubrry-api-restful-api-for-podcast-publishing-statistics/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 28.6
  mcp: *id009
  name: Buzzsprout
  slug: buzzsprout
  status: profiled
  tags: *id010
  url: /providers/buzzsprout/
- agent_band: agent-aware
  agent_readiness: 22.1
  band: thin
  in_catalog: true
  kin_score: 31.1
  mcp: *id011
  name: Captivate
  slug: captivate-fm
  status: profiled
  tags: *id012
  url: /providers/captivate-fm/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 23.2
  mcp: *id013
  name: Castos
  slug: castos
  status: profiled
  tags: *id014
  url: /providers/castos/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id015
  name: ChatGPT
  slug: openai
  status: profiled
  tags: *id016
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 87.5
  mcp: *id017
  name: Claude
  slug: anthropic
  status: profiled
  tags: *id018
  url: /providers/anthropic/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 9.0
  mcp: *id019
  name: DaVinci Resolve
  slug: blackmagic-design
  status: profiled
  tags: *id020
  url: /providers/blackmagic-design/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.4
  mcp: *id021
  name: Ecamm
  slug: ecamm
  status: profiled
  tags: *id022
  url: /providers/ecamm/
- agent_band: agent-aware
  agent_readiness: 22.6
  band: emerging
  in_catalog: true
  kin_score: 20.6
  mcp: *id023
  name: eWebinar
  slug: ewebinar
  status: profiled
  tags: *id024
  url: /providers/ewebinar/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id025
  name: Final Cut Pro / Apple Logic
  slug: apple
  status: profiled
  tags: *id026
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id027
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id028
  url: /providers/google-drive/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 3.1
  mcp: *id029
  name: Headliner
  slug: headliner
  status: profiled
  tags: *id030
  url: /providers/headliner/
- agent_band: agent-aware
  agent_readiness: 11.5
  band: thin
  in_catalog: true
  kin_score: 35.6
  mcp: *id031
  name: Hello Audio
  slug: hello-audio
  status: profiled
  tags: *id032
  url: /providers/hello-audio/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id033
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id034
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 43.9
  band: thin
  in_catalog: true
  kin_score: 33.0
  mcp: *id035
  name: Podbean
  slug: podbean
  status: profiled
  tags: *id036
  url: /providers/podbean/
- agent_band: agent-ready
  agent_readiness: 35.9
  band: thin
  in_catalog: true
  kin_score: 37.8
  mcp: *id037
  name: Podcast.co
  slug: podcast-co
  status: profiled
  tags: *id038
  url: /providers/podcast-co/
- agent_band: agent-aware
  agent_readiness: 13.6
  band: emerging
  in_catalog: true
  kin_score: 25.7
  mcp: *id039
  name: Raycast
  slug: raycast
  status: profiled
  tags: *id040
  url: /providers/raycast/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.0
  mcp: *id041
  name: REAPER
  slug: cockos-reaper
  status: profiled
  tags: *id042
  url: /providers/cockos-reaper/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: thin
  in_catalog: true
  kin_score: 35.0
  mcp: *id043
  name: Restream
  slug: restream
  status: profiled
  tags: *id044
  url: /providers/restream/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id045
  name: Riverside
  slug: riverside
  status: profiled
  tags: *id046
  url: /providers/riverside/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id047
  name: SquadCast
  slug: squadcast-fm
  status: queued for profiling
  tags: *id048
  url: null
- agent_band: agent-ready
  agent_readiness: 45.6
  band: developing
  in_catalog: true
  kin_score: 41.1
  mcp: *id049
  name: Transistor
  slug: transistor
  status: profiled
  tags: *id050
  url: /providers/transistor/
- agent_band: agent-ready
  agent_readiness: 43.5
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id051
  name: VideoAsk
  slug: typeform
  status: profiled
  tags: *id052
  url: /providers/typeform/
- agent_band: agent-ready
  agent_readiness: 35.7
  band: exemplar
  in_catalog: true
  kin_score: 75.8
  mcp: *id053
  name: Wistia
  slug: wistia
  status: profiled
  tags: *id054
  url: /providers/wistia/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: strong
  in_catalog: true
  kin_score: 62.6
  mcp: *id055
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id056
  url: /providers/youtube/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id057
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id058
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 55.2
  band: strong
  in_catalog: true
  kin_score: 56.2
  mcp: *id059
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id060
  url: /providers/zoom/
siblings:
- name: Canva
  rows: 6
  url: /applications/video-editing-creation/canva/
- name: CapCut
  rows: 11
  url: /applications/video-editing-creation/capcut/
- name: Excalidraw
  rows: 2
  url: /applications/video-editing-creation/excalidraw/
- name: Kdenlive
  rows: 4
  url: /applications/video-editing-creation/kdenlive/
- name: Penpot
  rows: 3
  url: /applications/video-editing-creation/penpot/
- name: Remotion
  rows: 10
  url: /applications/video-editing-creation/remotion/
sitemap: true
title: 'Descript: Video & Photo Editing / Creator Tools reference app'
---
