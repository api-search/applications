---
app: Remotion
app_slug: remotion
app_url: https://github.com/remotion-dev/remotion
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: domain
  name: Base Map Tiles
  providers:
  - MapTiler
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: API Evangelist extension
  id: AE-906
  key: AE-906
  layer: domain
  name: Code Execution Sandboxes
  providers:
  - Vercel
  url: /capabilities/engineering-productivity-management/
  via_parent: Engineering Productivity Management
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: domain
  name: Design & Creative Editing
  providers:
  - Rive
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-925
  key: AE-925
  layer: domain
  name: Serverless Functions
  providers:
  - AWS Lambda
  - Google Cloud Run
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-110.30.10
  key: AE-110.30.10
  layer: domain
  name: Speech-to-Text
  providers:
  - ElevenLabs
  - OpenAI
  url: /capabilities/speech-voice/
  via_parent: Speech & Voice
- attribution: API Evangelist extension
  id: AE-170.80.10
  key: AE-170.80.10
  layer: domain
  name: Web Fonts & Typography
  providers:
  - Google Fonts
  url: /capabilities/design-creative-editing/
  via_parent: Design & Creative Editing
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
  id: video-editing-creation
  name: Video & Photo Editing / Creator Tools
  url: /applications/video-editing-creation/
counts:
  declared: 0
  observed: 10
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/remotion-dev/remotion/tree/main/packages
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
    agent_band: agent-aware
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
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
  source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/lambda/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-925
    key: AE-925
    name: Serverless Functions
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 45.6
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id003
      source: https://github.com/awslabs/mcp/tree/main/src/lambda-tool-mcp-server
      status: verified
    slug: aws-lambda
    status: profiled
    tags: &id004
    - Logging
    - Monitoring
    - Observability
    - Serverless
    url: /providers/aws-lambda/
  layer: domain
  name: AWS Lambda
  provider: aws-lambda
  says: ships the AWS Lambda SDK or integration code
  source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/lambda/package.json
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
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 83.0
    mcp: &id005
      source: https://github.com/elevenlabs/elevenlabs-mcp
      status: verified
    slug: elevenlabs
    status: profiled
    tags: &id006
    - Artificial Intelligence
    - Speech-to-Text
    - Text-to-Speech
    - Voice
    url: /providers/elevenlabs/
  layer: domain
  name: ElevenLabs
  provider: elevenlabs
  says: ships the ElevenLabs SDK or integration code
  source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/elevenlabs/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-925
    key: AE-925
    name: Serverless Functions
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 53.2
    mcp: &id007
      source: https://github.com/GoogleCloudPlatform/cloud-run-mcp
      status: verified
    slug: google-cloud-run
    status: profiled
    tags: &id008
    - Cloud Run
    - Containers
    - Google Cloud
    - Serverless
    url: /providers/google-cloud-run/
  layer: domain
  name: Google Cloud Run
  provider: google-cloud-run
  says: ships the Google Cloud Run SDK or integration code
  source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/cloudrun/package.json
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
    agent_readiness: 45.3
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id009
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id010
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/cloudrun/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.80.10
    key: AE-170.80.10
    name: Web Fonts & Typography
    url: /capabilities/design-creative-editing/
    via_parent: Design & Creative Editing
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.9
    band: developing
    in_catalog: true
    kin_score: 42.4
    mcp: &id011
      status: none
    slug: google-fonts
    status: profiled
    tags: &id012
    - CSS
    - Design
    - Fonts
    - Google Fonts
    url: /providers/google-fonts/
  layer: domain
  name: Google Fonts
  provider: google-fonts
  says: ships the Google Fonts SDK or integration code
  source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/google-fonts/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.5
    band: developing
    in_catalog: true
    kin_score: 40.3
    mcp: &id013
      status: none
    slug: maptiler
    status: profiled
    tags: &id014
    - Geospatial
    - Maps
    - Tiles
    - Vector Tiles
    url: /providers/maptiler/
  layer: domain
  name: MapTiler
  provider: maptiler
  says: ships the MapTiler SDK or integration code
  source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/maptiler/package.json
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
  layer: domain
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/openai-whisper/package.json
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 22.5
    mcp: &id017
      status: none
    slug: rive
    status: profiled
    tags: &id018
    - Animation
    - Company
    - Design
    - Graphics
    url: /providers/rive/
  layer: domain
  name: Rive
  provider: rive
  says: ships the Rive SDK or integration code
  source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/rive/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-906
    key: AE-906
    name: Code Execution Sandboxes
    url: /capabilities/engineering-productivity-management/
    via_parent: Engineering Productivity Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.2
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id019
      source: https://vercel.com/docs/mcp/vercel-mcp
      status: verified
    slug: vercel
    status: profiled
    tags: &id020
    - AI Gateway
    - Gateways
    - Observability
    - Webhook
    url: /providers/vercel/
  layer: domain
  name: Vercel
  provider: vercel
  says: ships the Vercel SDK or integration code
  source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/vercel/package.json
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/video-editing-creation/remotion/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-native
  agent_readiness: 45.6
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id003
  name: AWS Lambda
  slug: aws-lambda
  status: profiled
  tags: *id004
  url: /providers/aws-lambda/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 83.0
  mcp: *id005
  name: ElevenLabs
  slug: elevenlabs
  status: profiled
  tags: *id006
  url: /providers/elevenlabs/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 53.2
  mcp: *id007
  name: Google Cloud Run
  slug: google-cloud-run
  status: profiled
  tags: *id008
  url: /providers/google-cloud-run/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id009
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id010
  url: /providers/gcp-cloud-storage/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: developing
  in_catalog: true
  kin_score: 42.4
  mcp: *id011
  name: Google Fonts
  slug: google-fonts
  status: profiled
  tags: *id012
  url: /providers/google-fonts/
- agent_band: agent-aware
  agent_readiness: 26.5
  band: developing
  in_catalog: true
  kin_score: 40.3
  mcp: *id013
  name: MapTiler
  slug: maptiler
  status: profiled
  tags: *id014
  url: /providers/maptiler/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id015
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id016
  url: /providers/openai/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 22.5
  mcp: *id017
  name: Rive
  slug: rive
  status: profiled
  tags: *id018
  url: /providers/rive/
- agent_band: agent-ready
  agent_readiness: 45.2
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id019
  name: Vercel
  slug: vercel
  status: profiled
  tags: *id020
  url: /providers/vercel/
siblings:
- name: Canva
  rows: 6
  url: /applications/video-editing-creation/canva/
- name: CapCut
  rows: 11
  url: /applications/video-editing-creation/capcut/
- name: Descript
  rows: 30
  url: /applications/video-editing-creation/descript/
- name: Excalidraw
  rows: 2
  url: /applications/video-editing-creation/excalidraw/
- name: Kdenlive
  rows: 4
  url: /applications/video-editing-creation/kdenlive/
- name: Penpot
  rows: 3
  url: /applications/video-editing-creation/penpot/
sitemap: true
title: 'Remotion: Video & Photo Editing / Creator Tools reference app'
---
