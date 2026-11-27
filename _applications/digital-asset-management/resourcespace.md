---
app: ResourceSpace
app_slug: resourcespace
app_url: https://www.resourcespace.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: domain
  name: Content Management
  providers:
  - WordPress
  url: /capabilities/content-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: domain
  name: Design & Creative Editing
  providers:
  - Adobe
  - Canva
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: domain
  name: Hosted LLM Inference
  providers:
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.50.10
  key: AE-110.50.10
  layer: domain
  name: Image Recognition
  providers:
  - Google Cloud Vision
  url: /capabilities/vision/
  via_parent: Vision
- attribution: API Evangelist extension
  id: AE-947
  key: AE-947
  layer: domain
  name: Museum Collections Management
  providers:
  - Axiell (KE EMu)
  - Gallery Systems (TMS)
  - zetcom (MuseumPlus)
  url: /capabilities/museum-collections-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: domain
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: domain
  name: Search and Discovery Management
  providers:
  - Typesense
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: Turbo EA
  id: BC-400.60.40
  key: BC-400.60.40
  layer: domain
  name: Social Media Management
  providers:
  - Brandwatch
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-170.30.40
  key: AE-170.30.40
  layer: domain
  name: Stock Media & Royalty-Free Libraries
  providers:
  - Pixabay
  - Shutterstock
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: API Evangelist extension
  id: AE-170.10
  key: AE-170.10
  layer: domain
  name: Video Platforms
  providers:
  - Vimeo
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: null
category:
  id: digital-asset-management
  name: Digital Asset Management
  url: /applications/digital-asset-management/
counts:
  declared: 15
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://www.resourcespace.com/knowledge-base/plugins
- route: documentation
  url: https://www.resourcespace.com/knowledge-base/plugins/image_banks
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
    agent_readiness: 62.9
    band: exemplar
    in_catalog: true
    kin_score: 76.1
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
  name: Adobe
  provider: adobe
  says: lists Adobe as an integration
  source: https://www.resourcespace.com/knowledge-base/plugins
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-947
    key: AE-947
    name: Museum Collections Management
    url: /capabilities/museum-collections-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 5.8
    mcp: &id003
      status: unchecked
    slug: axiell
    status: profiled
    tags: &id004
    - Company
    - Library
    - Museums
    - Software
    url: /providers/axiell/
  layer: domain
  name: Axiell (KE EMu)
  provider: axiell
  says: lists Axiell (KE EMu) as an integration
  source: https://www.resourcespace.com/knowledge-base/plugins
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60.40
    key: BC-400.60.40
    name: Social Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.2
    band: strong
    in_catalog: true
    kin_score: 57.5
    mcp: &id005
      status: unknown
    slug: brandwatch
    status: profiled
    tags: &id006
    - Analytics
    - Consumer Intelligence
    - Social Media
    - Social Media Monitoring
    url: /providers/brandwatch/
  layer: domain
  name: Brandwatch
  provider: brandwatch
  says: lists Brandwatch as an integration
  source: https://www.resourcespace.com/knowledge-base/plugins
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
    mcp: &id007
      source: https://www.canva.dev/docs/mcp/
      status: verified
    slug: canva
    status: profiled
    tags: &id008
    - Application
    - Automation
    - Brand Management
    - Collaboration
    url: /providers/canva/
  layer: domain
  name: Canva
  provider: canva
  says: lists Canva as an integration
  source: https://www.resourcespace.com/knowledge-base/plugins
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-947
    key: AE-947
    name: Museum Collections Management
    url: /capabilities/museum-collections-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.6
    band: emerging
    in_catalog: true
    kin_score: 14.7
    mcp: &id009
      status: unchecked
    slug: gallery-systems
    status: profiled
    tags: &id010
    - Collection
    - Company
    - Digital Asset Management
    - Museum Software
    url: /providers/gallery-systems/
  layer: domain
  name: Gallery Systems (TMS)
  provider: gallery-systems
  says: lists Gallery Systems (TMS) as an integration
  source: https://www.resourcespace.com/knowledge-base/plugins
  tier: declared
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
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id011
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id012
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: domain
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://www.resourcespace.com/knowledge-base/plugins
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.50.10
    key: AE-110.50.10
    name: Image Recognition
    url: /capabilities/vision/
    via_parent: Vision
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: exemplar
    in_catalog: true
    kin_score: 70.0
    mcp: &id013
      status: unknown
    slug: google-cloud-vision
    status: profiled
    tags: &id014
    - Computer Vision
    - Google Cloud
    - Image Analysis
    - Machine Learning
    url: /providers/google-cloud-vision/
  layer: domain
  name: Google Cloud Vision
  provider: google-cloud-vision
  says: lists Google Cloud Vision as an integration
  source: https://www.resourcespace.com/knowledge-base/plugins
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
  says: lists OpenAI as an integration
  source: https://www.resourcespace.com/knowledge-base/plugins
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.40
    key: AE-170.30.40
    name: Stock Media & Royalty-Free Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 13.7
    mcp: &id017
      status: none
    slug: pixabay
    status: profiled
    tags: &id018
    - Illustrations
    - Image
    - Stock Media
    - Video
    url: /providers/pixabay/
  layer: domain
  name: Pixabay
  provider: pixabay
  says: lists Pixabay as an integration
  source: https://www.resourcespace.com/knowledge-base/plugins/image_banks
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.40
    key: AE-170.30.40
    name: Stock Media & Royalty-Free Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.6
    band: developing
    in_catalog: true
    kin_score: 42.6
    mcp: &id019
      status: none
    slug: shutterstock
    status: profiled
    tags: &id020
    - Image
    - Media
    - Photos
    - Stock Images
    url: /providers/shutterstock/
  layer: domain
  name: Shutterstock
  provider: shutterstock
  says: lists Shutterstock as an integration
  source: https://www.resourcespace.com/knowledge-base/plugins/image_banks
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.3
    band: thin
    in_catalog: true
    kin_score: 39.2
    mcp: &id021
      source: https://typesense.org/docs/guide/typesense-cloud/mcp-server.html
      status: verified
    slug: typesense
    status: profiled
    tags: &id022
    - Full-Text Search
    - Open Source
    - Search Engines
    - Typo Tolerance
    url: /providers/typesense/
  layer: domain
  name: Typesense
  provider: typesense
  says: lists Typesense as an integration
  source: https://www.resourcespace.com/knowledge-base/plugins
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: thin
    in_catalog: true
    kin_score: 37.6
    mcp: &id023
      source: https://developer.vimeo.com/api/mcp-server
      status: documented
    slug: vimeo
    status: profiled
    tags: &id024
    - Live Streaming
    - Streaming
    - Video
    - Video Hosting
    url: /providers/vimeo/
  layer: domain
  name: Vimeo
  provider: vimeo
  says: lists Vimeo as an integration
  source: https://www.resourcespace.com/knowledge-base/plugins
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id025
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id026
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
  layer: domain
  name: WordPress
  provider: wordpress
  says: lists WordPress as an integration
  source: https://www.resourcespace.com/knowledge-base/plugins
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.4
    band: strong
    in_catalog: true
    kin_score: 65.4
    mcp: &id027
      status: none
    slug: youtube
    status: profiled
    tags: &id028
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: lists YouTube as an integration
  source: https://www.resourcespace.com/knowledge-base/plugins
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-947
    key: AE-947
    name: Museum Collections Management
    url: /capabilities/museum-collections-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.7
    band: emerging
    in_catalog: true
    kin_score: 18.7
    mcp: &id029
      status: unchecked
    slug: zetcom
    status: profiled
    tags: &id030
    - Collection Management
    - Museum Software
    url: /providers/zetcom/
  layer: domain
  name: zetcom (MuseumPlus)
  provider: zetcom
  says: lists zetcom (MuseumPlus) as an integration
  source: https://www.resourcespace.com/knowledge-base/plugins
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/digital-asset-management/resourcespace/
providers:
- agent_band: agent-ready
  agent_readiness: 62.9
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id001
  name: Adobe
  slug: adobe
  status: profiled
  tags: *id002
  url: /providers/adobe/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 5.8
  mcp: *id003
  name: Axiell (KE EMu)
  slug: axiell
  status: profiled
  tags: *id004
  url: /providers/axiell/
- agent_band: agent-ready
  agent_readiness: 39.2
  band: strong
  in_catalog: true
  kin_score: 57.5
  mcp: *id005
  name: Brandwatch
  slug: brandwatch
  status: profiled
  tags: *id006
  url: /providers/brandwatch/
- agent_band: agent-native
  agent_readiness: 70.0
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id007
  name: Canva
  slug: canva
  status: profiled
  tags: *id008
  url: /providers/canva/
- agent_band: agent-aware
  agent_readiness: 20.6
  band: emerging
  in_catalog: true
  kin_score: 14.7
  mcp: *id009
  name: Gallery Systems (TMS)
  slug: gallery-systems
  status: profiled
  tags: *id010
  url: /providers/gallery-systems/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id011
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id012
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: exemplar
  in_catalog: true
  kin_score: 70.0
  mcp: *id013
  name: Google Cloud Vision
  slug: google-cloud-vision
  status: profiled
  tags: *id014
  url: /providers/google-cloud-vision/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id015
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id016
  url: /providers/openai/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 13.7
  mcp: *id017
  name: Pixabay
  slug: pixabay
  status: profiled
  tags: *id018
  url: /providers/pixabay/
- agent_band: agent-ready
  agent_readiness: 29.6
  band: developing
  in_catalog: true
  kin_score: 42.6
  mcp: *id019
  name: Shutterstock
  slug: shutterstock
  status: profiled
  tags: *id020
  url: /providers/shutterstock/
- agent_band: agent-ready
  agent_readiness: 47.3
  band: thin
  in_catalog: true
  kin_score: 39.2
  mcp: *id021
  name: Typesense
  slug: typesense
  status: profiled
  tags: *id022
  url: /providers/typesense/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id023
  name: Vimeo
  slug: vimeo
  status: profiled
  tags: *id024
  url: /providers/vimeo/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id025
  name: WordPress
  slug: wordpress
  status: profiled
  tags: *id026
  url: /providers/wordpress/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: strong
  in_catalog: true
  kin_score: 65.4
  mcp: *id027
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id028
  url: /providers/youtube/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: emerging
  in_catalog: true
  kin_score: 18.7
  mcp: *id029
  name: zetcom (MuseumPlus)
  slug: zetcom
  status: profiled
  tags: *id030
  url: /providers/zetcom/
siblings:
- name: Bynder
  rows: 71
  url: /applications/digital-asset-management/bynder/
- name: Canto
  rows: 33
  url: /applications/digital-asset-management/canto/
- name: Cloudinary
  rows: 56
  url: /applications/digital-asset-management/cloudinary/
- name: Frontify
  rows: 55
  url: /applications/digital-asset-management/frontify/
- name: Phraseanet
  rows: 10
  url: /applications/digital-asset-management/phraseanet/
sitemap: true
title: 'ResourceSpace: Digital Asset Management reference app'
---
