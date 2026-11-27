---
app: SearXNG
app_slug: searxng
app_url: https://github.com/searxng/searxng
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.20
  key: AE-170.20
  layer: domain
  name: Audio & Music
  providers:
  - Deezer
  - Freesound
  - Genius
  - Mixcloud
  - SoundCloud
  - Spotify
  url: /capabilities/audio-music/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.30.30
  key: AE-170.30.30
  layer: domain
  name: Avatars, GIFs & Stickers
  providers:
  - GIPHY
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: API Evangelist extension
  id: AE-250.10.20
  key: AE-250.10.20
  layer: domain
  name: Container Registries
  providers:
  - Docker Hub
  url: /capabilities/package-registries-distribution/
  via_parent: Package Registries & Distribution
- attribution: API Evangelist extension
  id: AE-230
  key: AE-230
  layer: domain
  name: Data & Reference Information Services
  providers:
  - arXiv
  - Crossref
  - OpenAlex
  - PubMed
  - Semantic Scholar
  - Springer Nature
  - Wikidata
  - Wikipedia
  - Wolfram|Alpha
  url: /capabilities/data-reference-information-services/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-250.10.10
  key: AE-250.10.10
  layer: domain
  name: Language Package Registries
  providers:
  - crates.io
  - npm
  - PyPI
  url: /capabilities/package-registries-distribution/
  via_parent: Package Registries & Distribution
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: domain
  name: Machine Translation
  providers:
  - DeepL
  - LibreTranslate
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-110.70
  key: AE-110.70
  layer: domain
  name: Model Training & Data
  providers:
  - Hugging Face Hub
  url: /capabilities/model-training-data/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: domain
  name: Photo & Image Libraries
  providers:
  - Flickr
  - Imgur
  - Openverse
  - Pexels
  - Pixabay
  - TinEye
  - Unsplash
  url: /capabilities/photo-image-libraries/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.40.10
  key: AE-120.40.10
  layer: domain
  name: Place Search
  providers:
  - OpenStreetMap
  url: /capabilities/places-points-of-interest/
  via_parent: Places & Points of Interest
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - Hacker News
  - Lemmy
  - Mastodon
  - Stack Exchange
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - GitHub
  - GitLab
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.10
  key: AE-170.10
  layer: domain
  name: Video Platforms
  providers:
  - Dailymotion
  - PeerTube
  - Vimeo
  - YouTube Data API
  url: /capabilities/video-platforms/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.10
  key: AE-230.10
  layer: domain
  name: Weather & Environment
  providers:
  - Open-Meteo
  url: /capabilities/weather-environment/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.40.20
  key: AE-230.40.20
  layer: domain
  name: Web Search APIs
  providers:
  - Brave Search API
  - Exa
  - Google Programmable Search
  - Jina AI
  - Kagi
  - Microsoft Bing
  - Yandex Search API
  url: /capabilities/web-data/
  via_parent: Web Data
category:
  id: search-engine
  name: Site & App Search
  url: /applications/search-engine/
counts:
  declared: 0
  observed: 49
credits: []
evidence:
- route: source code
  url: https://github.com/searxng/searxng/tree/master/searx/engines
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-230
    key: AE-230
    name: Data & Reference Information Services
    url: /capabilities/data-reference-information-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.8
    band: developing
    in_catalog: true
    kin_score: 44.3
    mcp: &id001
      status: none
    slug: arxiv
    status: profiled
    tags: &id002
    - Open Access
    - Preprints
    - Research
    - Scholarly Publishing
    url: /providers/arxiv/
  layer: domain
  name: arXiv
  provider: arxiv
  says: ships the arXiv SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/arxiv.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.7
    band: thin
    in_catalog: true
    kin_score: 33.4
    mcp: &id003
      source: https://github.com/brave/brave-search-mcp-server
      status: verified
    slug: brave-browser
    status: profiled
    tags: &id004
    - Browser
    - Chromium
    - Privacy
    - Search
    url: /providers/brave-browser/
  layer: domain
  name: Brave Search API
  provider: brave-browser
  says: ships the Brave Search API SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/braveapi.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.10
    key: AE-250.10.10
    name: Language Package Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.6
    band: developing
    in_catalog: true
    kin_score: 39.3
    mcp: &id005
      status: none
    slug: crates-io
    status: profiled
    tags: &id006
    - Cargo
    - Crates
    - Package Registry
    - Rust
    url: /providers/crates-io/
  layer: domain
  name: crates.io
  provider: crates-io
  says: ships the crates.io SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/crates.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230
    key: AE-230
    name: Data & Reference Information Services
    url: /capabilities/data-reference-information-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.0
    band: thin
    in_catalog: true
    kin_score: 34.4
    mcp: &id007
      status: none
    slug: crossref
    status: profiled
    tags: &id008
    - Citations
    - DOI
    - Funders
    - Identifiers
    url: /providers/crossref/
  layer: domain
  name: Crossref
  provider: crossref
  says: ships the Crossref SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/crossref.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.8
    band: minimal
    in_catalog: true
    kin_score: 8.2
    mcp: &id009
      status: none
    slug: dailymotion
    status: profiled
    tags: &id010
    - Public APIs
    - Video
    url: /providers/dailymotion/
  layer: domain
  name: Dailymotion
  provider: dailymotion
  says: ships the Dailymotion SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/dailymotion.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.1
    band: strong
    in_catalog: true
    kin_score: 61.4
    mcp: &id011
      source: https://github.com/DeepL/deepl-mcp-server
      status: verified
    slug: deepl
    status: profiled
    tags: &id012
    - Artificial Intelligence
    - Deep Learning
    - Glossary
    - Localization
    url: /providers/deepl/
  layer: domain
  name: DeepL
  provider: deepl
  says: ships the DeepL SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/deepl.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20
    key: AE-170.20
    name: Audio & Music
    url: /capabilities/audio-music/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.1
    band: thin
    in_catalog: true
    kin_score: 30.7
    mcp: &id013
      status: none
    slug: deezer
    status: profiled
    tags: &id014
    - Audio
    - Music
    - OAuth
    - Streaming
    url: /providers/deezer/
  layer: domain
  name: Deezer
  provider: deezer
  says: ships the Deezer SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/deezer.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 48.7
    mcp: &id015
      source: https://github.com/docker/hub-mcp
      status: verified
    slug: docker-hub
    status: profiled
    tags: &id016
    - Containers
    - DevOps
    - Docker
    - Registry
    url: /providers/docker-hub/
  layer: domain
  name: Docker Hub
  provider: docker-hub
  says: ships the Docker Hub SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/docker_hub.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 60.0
    band: strong
    in_catalog: true
    kin_score: 57.7
    mcp: &id017
      source: https://github.com/exa-labs/exa-mcp-server
      status: verified
    slug: exa-ai
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Neural Search
    - Search
    - Web Search
    url: /providers/exa-ai/
  layer: domain
  name: Exa
  provider: exa-ai
  says: ships the Exa SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/exaapi.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.1
    band: developing
    in_catalog: true
    kin_score: 49.1
    mcp: &id019
      status: none
    slug: flickr
    status: profiled
    tags: &id020
    - Photography
    - Photos
    - Public APIs
    - Social Media
    url: /providers/flickr/
  layer: domain
  name: Flickr
  provider: flickr
  says: ships the Flickr SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/flickr.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20
    key: AE-170.20
    name: Audio & Music
    url: /capabilities/audio-music/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.8
    mcp: &id021
      status: none
    slug: freesound
    status: profiled
    tags: &id022
    - Music
    - Public APIs
    url: /providers/freesound/
  layer: domain
  name: Freesound
  provider: freesound
  says: ships the Freesound SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/freesound.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20
    key: AE-170.20
    name: Audio & Music
    url: /capabilities/audio-music/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 34.8
    mcp: &id023
      status: none
    slug: genius
    status: profiled
    tags: &id024
    - Annotation
    - Crowdsourced
    - Lyrics
    - Music
    url: /providers/genius/
  layer: domain
  name: Genius
  provider: genius
  says: ships the Genius SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/genius.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: strong
    in_catalog: true
    kin_score: 56.0
    mcp: &id025
      status: none
    slug: giphy
    status: profiled
    tags: &id026
    - GIFs
    - Media
    - Photography
    - Stickers
    url: /providers/giphy/
  layer: domain
  name: GIPHY
  provider: giphy
  says: ships the GIPHY SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/giphy.py
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id027
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id028
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/github.py
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id029
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id030
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/gitlab.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.6
    band: strong
    in_catalog: true
    kin_score: 61.6
    mcp: &id031
      status: none
    slug: google-custom-search
    status: profiled
    tags: &id032
    - Custom Search
    - Google
    - Image Search
    - Search
    url: /providers/google-custom-search/
  layer: domain
  name: Google Programmable Search
  provider: google-custom-search
  says: ships the Google Programmable Search SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/google_cse.py
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
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 27.3
    mcp: &id033
      status: none
    slug: hacker-news
    status: profiled
    tags: &id034
    - Developer Community
    - Technology News
    - Y Combinator
    url: /providers/hacker-news/
  layer: domain
  name: Hacker News
  provider: hacker-news
  says: ships the Hacker News SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/hackernews.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.70
    key: AE-110.70
    name: Model Training & Data
    url: /capabilities/model-training-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.9
    band: exemplar
    in_catalog: true
    kin_score: 69.1
    mcp: &id035
      source: https://github.com/huggingface/hf-mcp-server
      status: verified
    slug: hugging-face
    status: profiled
    tags: &id036
    - Computer Vision
    - Embeddings
    - Image Generation
    - LLM
    url: /providers/hugging-face/
  layer: domain
  name: Hugging Face Hub
  provider: hugging-face
  says: ships the Hugging Face Hub SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/huggingface.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.8
    band: developing
    in_catalog: true
    kin_score: 47.2
    mcp: &id037
      status: none
    slug: imgur
    status: profiled
    tags: &id038
    - Albums
    - Image
    - Image Hosting
    - Photography
    url: /providers/imgur/
  layer: domain
  name: Imgur
  provider: imgur
  says: ships the Imgur SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/imgur.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.1
    band: thin
    in_catalog: true
    kin_score: 34.2
    mcp: &id039
      source: https://github.com/jina-ai/MCP
      status: verified
    slug: jina-ai
    status: profiled
    tags: &id040
    - Artificial Intelligence
    - Embeddings
    - Machine Learning
    - Reranking
    url: /providers/jina-ai/
  layer: domain
  name: Jina AI
  provider: jina-ai
  says: ships the Jina AI SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/jina.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 38.8
    mcp: &id041
      source: https://github.com/kagisearch/kagimcp
      status: verified
    slug: kagi
    status: profiled
    tags: &id042
    - AI Search
    - Premium Search
    - Search
    - Summarization
    url: /providers/kagi/
  layer: domain
  name: Kagi
  provider: kagi
  says: ships the Kagi SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/kagi.py
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
    agent_band: agent-aware
    agent_readiness: 20.4
    band: thin
    in_catalog: true
    kin_score: 33.9
    mcp: &id043
      status: none
    slug: lemmy
    status: profiled
    tags: &id044
    - Community
    - Federated
    - Fediverse
    - Link Aggregator
    url: /providers/lemmy/
  layer: domain
  name: Lemmy
  provider: lemmy
  says: ships the Lemmy SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/lemmy.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: emerging
    in_catalog: true
    kin_score: 24.3
    mcp: &id045
      source: https://github.com/LibreTranslate/LibreTranslate-MCP
      status: verified
    slug: libre-translate
    status: profiled
    tags: &id046
    - Machine Translation
    - Natural Language Processing
    - Open Source
    - Translation
    url: /providers/libre-translate/
  layer: domain
  name: LibreTranslate
  provider: libre-translate
  says: ships the LibreTranslate SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/libretranslate.py
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
    agent_band: agent-aware
    agent_readiness: 22.0
    band: emerging
    in_catalog: true
    kin_score: 25.5
    mcp: &id047
      status: none
    slug: mastodon
    status: profiled
    tags: &id048
    - Open Source
    - Real-Time
    - Social
    - Social Network
    url: /providers/mastodon/
  layer: domain
  name: Mastodon
  provider: mastodon
  says: ships the Mastodon SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/mastodon.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.2
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id049
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft
    status: profiled
    tags: &id050
    - Cloud
    - Fortune 100
    - Microsoft
    - Software
    url: /providers/microsoft/
  layer: domain
  name: Microsoft Bing
  provider: microsoft-bing
  says: ships the Microsoft Bing SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/bing.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20
    key: AE-170.20
    name: Audio & Music
    url: /capabilities/audio-music/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.8
    mcp: &id051
      status: none
    slug: mixcloud
    status: profiled
    tags: &id052
    - Music
    - Public APIs
    url: /providers/mixcloud/
  layer: domain
  name: Mixcloud
  provider: mixcloud
  says: ships the Mixcloud SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/mixcloud.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.10
    key: AE-250.10.10
    name: Language Package Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id053
      status: none
    slug: npm
    status: profiled
    tags: &id054
    - JavaScript
    - Node.js
    - Package Management
    - Packages
    url: /providers/npm/
  layer: domain
  name: npm
  provider: npm
  says: ships the npm SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/npm.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: AE-230.10
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.4
    band: thin
    in_catalog: true
    kin_score: 28.3
    mcp: &id055
      status: none
    slug: open-meteo
    status: profiled
    tags: &id056
    - Air Quality
    - Forecast
    - Historical Weather
    - Weather
    url: /providers/open-meteo/
  layer: domain
  name: Open-Meteo
  provider: open-meteo
  says: ships the Open-Meteo SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/open_meteo.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230
    key: AE-230
    name: Data & Reference Information Services
    url: /capabilities/data-reference-information-services/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.7
    band: minimal
    in_catalog: true
    kin_score: 5.9
    mcp: &id057
      source: https://github.com/ourresearch/openalex-mcp-server
      status: verified
    slug: openalex
    status: profiled
    tags: &id058
    - Citations
    - Public APIs
    - Research Data
    - Scholarly
    url: /providers/openalex/
  layer: domain
  name: OpenAlex
  provider: openalex
  says: ships the OpenAlex SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/openalex.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.40.10
    key: AE-120.40.10
    name: Place Search
    url: /capabilities/places-points-of-interest/
    via_parent: Places & Points of Interest
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.3
    band: developing
    in_catalog: true
    kin_score: 45.5
    mcp: &id059
      status: none
    slug: openstreetmap
    status: profiled
    tags: &id060
    - Geocoding
    - Geospatial
    - Mapping
    - Open Data
    url: /providers/openstreetmap/
  layer: domain
  name: OpenStreetMap
  provider: openstreetmap
  says: ships the OpenStreetMap SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/openstreetmap.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.6
    band: thin
    in_catalog: true
    kin_score: 32.4
    mcp: &id061
      status: none
    slug: openverse
    status: profiled
    tags: &id062
    - Audio
    - Creative Commons
    - Image
    - Open Media
    url: /providers/openverse/
  layer: domain
  name: Openverse
  provider: openverse
  says: ships the Openverse SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/openverse.py
  tier: observed
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
    agent_readiness: 31.9
    band: thin
    in_catalog: true
    kin_score: 30.1
    mcp: &id063
      status: none
    slug: peertube
    status: profiled
    tags: &id064
    - Decentralized
    - Federation
    - Open Source
    - Video
    url: /providers/peertube/
  layer: domain
  name: PeerTube
  provider: peertube
  says: ships the PeerTube SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/peertube.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.1
    band: thin
    in_catalog: true
    kin_score: 38.4
    mcp: &id065
      status: none
    slug: pexels
    status: profiled
    tags: &id066
    - Photos
    - Stock Media
    - Video
    url: /providers/pexels/
  layer: domain
  name: Pexels
  provider: pexels
  says: ships the Pexels SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/pexels.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 13.7
    mcp: &id067
      status: none
    slug: pixabay
    status: profiled
    tags: &id068
    - Illustrations
    - Image
    - Stock Media
    - Video
    url: /providers/pixabay/
  layer: domain
  name: Pixabay
  provider: pixabay
  says: ships the Pixabay SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/pixabay.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230
    key: AE-230
    name: Data & Reference Information Services
    url: /capabilities/data-reference-information-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.4
    band: emerging
    in_catalog: true
    kin_score: 25.0
    mcp: &id069
      status: none
    slug: pubmed
    status: profiled
    tags: &id070
    - Biomedical
    - Life Sciences
    - Literature
    - Research
    url: /providers/pubmed/
  layer: domain
  name: PubMed
  provider: pubmed
  says: ships the PubMed SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/pubmed.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.10
    key: AE-250.10.10
    name: Language Package Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 38.4
    mcp: &id071
      status: none
    slug: pypi
    status: profiled
    tags: &id072
    - Developer Tools
    - Open Source
    - Package Management
    - Packages
    url: /providers/pypi/
  layer: domain
  name: PyPI
  provider: pypi
  says: ships the PyPI SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/pypi.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230
    key: AE-230
    name: Data & Reference Information Services
    url: /capabilities/data-reference-information-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.3
    band: thin
    in_catalog: true
    kin_score: 33.4
    mcp: &id073
      status: none
    slug: semantic-scholar
    status: profiled
    tags: &id074
    - Academic
    - Citations
    - Paper
    - Research
    url: /providers/semantic-scholar/
  layer: domain
  name: Semantic Scholar
  provider: semantic-scholar
  says: ships the Semantic Scholar SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/semantic_scholar.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20
    key: AE-170.20
    name: Audio & Music
    url: /capabilities/audio-music/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 30.9
    mcp: &id075
      status: none
    slug: soundcloud
    status: profiled
    tags: &id076
    - Audio
    - Music
    - OAuth
    - Streaming
    url: /providers/soundcloud/
  layer: domain
  name: SoundCloud
  provider: soundcloud
  says: ships the SoundCloud SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/soundcloud.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20
    key: AE-170.20
    name: Audio & Music
    url: /capabilities/audio-music/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.7
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id077
      status: none
    slug: spotify
    status: profiled
    tags: &id078
    - Audio
    - Music
    - Podcasts
    - Streaming
    url: /providers/spotify/
  layer: domain
  name: Spotify
  provider: spotify
  says: ships the Spotify SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/spotify.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230
    key: AE-230
    name: Data & Reference Information Services
    url: /capabilities/data-reference-information-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.6
    band: thin
    in_catalog: true
    kin_score: 34.9
    mcp: &id079
      status: none
    slug: springer-nature
    status: profiled
    tags: &id080
    - Open Access
    - Research
    - Scholarly Content
    - Scholarly Publishing
    url: /providers/springer-nature/
  layer: domain
  name: Springer Nature
  provider: springer-nature
  says: ships the Springer Nature SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/springer.py
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
    agent_band: agent-ready
    agent_readiness: 29.8
    band: developing
    in_catalog: true
    kin_score: 40.9
    mcp: &id081
      source: https://github.com/StackExchange/Stack-MCP
      status: verified
    slug: stackexchange
    status: profiled
    tags: &id082
    - Developer Community
    - Knowledge Graph
    - Q&A
    - Stack Overflow
    url: /providers/stackexchange/
  layer: domain
  name: Stack Exchange
  provider: stackexchange
  says: ships the Stack Exchange SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/stackexchange.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.6
    mcp: &id083
      status: none
    slug: tineye
    status: profiled
    tags: &id084
    - Company
    url: /providers/tineye/
  layer: domain
  name: TinEye
  provider: tineye
  says: ships the TinEye SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/tineye.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.6
    band: developing
    in_catalog: true
    kin_score: 39.4
    mcp: &id085
      status: none
    slug: unsplash
    status: profiled
    tags: &id086
    - Image
    - Photography
    - Photos
    - Stock Photos
    url: /providers/unsplash/
  layer: domain
  name: Unsplash
  provider: unsplash
  says: ships the Unsplash SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/unsplash.py
  tier: observed
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
    mcp: &id087
      source: https://developer.vimeo.com/api/mcp-server
      status: documented
    slug: vimeo
    status: profiled
    tags: &id088
    - Live Streaming
    - Streaming
    - Video
    - Video Hosting
    url: /providers/vimeo/
  layer: domain
  name: Vimeo
  provider: vimeo
  says: ships the Vimeo SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/vimeo.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230
    key: AE-230
    name: Data & Reference Information Services
    url: /capabilities/data-reference-information-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.7
    band: developing
    in_catalog: true
    kin_score: 53.4
    mcp: &id089
      source: https://www.wikidata.org/wiki/Wikidata:MCP
      status: verified
    slug: wikidata
    status: profiled
    tags: &id090
    - Knowledge Graph
    - Linked Data
    - Open Data
    - Semantic Web
    url: /providers/wikidata/
  layer: domain
  name: Wikidata
  provider: wikidata
  says: ships the Wikidata SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/wikidata.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230
    key: AE-230
    name: Data & Reference Information Services
    url: /capabilities/data-reference-information-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.3
    band: developing
    in_catalog: true
    kin_score: 41.8
    mcp: &id091
      status: none
    slug: wikipedia
    status: profiled
    tags: &id092
    - Encyclopedia
    - Open Data
    - Open Knowledge
    - Public APIs
    url: /providers/wikipedia/
  layer: domain
  name: Wikipedia
  provider: wikipedia
  says: ships the Wikipedia SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/wikipedia.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230
    key: AE-230
    name: Data & Reference Information Services
    url: /capabilities/data-reference-information-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: thin
    in_catalog: true
    kin_score: 36.2
    mcp: &id093
      source: https://www.wolfram.com/artificial-intelligence/mcp/cloud/
      status: verified
    slug: wolframalpha
    status: profiled
    tags: &id094
    - Artificial Intelligence
    - Computational Knowledge
    - Machine Learning
    - Natural Language Processing
    url: /providers/wolframalpha/
  layer: domain
  name: Wolfram|Alpha
  provider: wolframalpha
  says: ships the Wolfram|Alpha SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/wolframalpha_api.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id095
      status: unchecked
    slug: yandex
    status: queued for profiling
    tags: &id096 []
    url: null
  layer: domain
  name: Yandex Search API
  provider: yandex
  says: ships the Yandex Search API SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/yandex_api.py
  tier: observed
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
    mcp: &id097
      status: none
    slug: youtube
    status: profiled
    tags: &id098
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube Data API
  provider: youtube
  says: ships the YouTube Data API SDK or integration code
  source: https://github.com/searxng/searxng/blob/master/searx/engines/youtube_api.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/search-engine/searxng/
providers:
- agent_band: agent-aware
  agent_readiness: 23.8
  band: developing
  in_catalog: true
  kin_score: 44.3
  mcp: *id001
  name: arXiv
  slug: arxiv
  status: profiled
  tags: *id002
  url: /providers/arxiv/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: thin
  in_catalog: true
  kin_score: 33.4
  mcp: *id003
  name: Brave Search API
  slug: brave-browser
  status: profiled
  tags: *id004
  url: /providers/brave-browser/
- agent_band: agent-aware
  agent_readiness: 26.6
  band: developing
  in_catalog: true
  kin_score: 39.3
  mcp: *id005
  name: crates.io
  slug: crates-io
  status: profiled
  tags: *id006
  url: /providers/crates-io/
- agent_band: agent-aware
  agent_readiness: 17.0
  band: thin
  in_catalog: true
  kin_score: 34.4
  mcp: *id007
  name: Crossref
  slug: crossref
  status: profiled
  tags: *id008
  url: /providers/crossref/
- agent_band: human-only
  agent_readiness: 3.8
  band: minimal
  in_catalog: true
  kin_score: 8.2
  mcp: *id009
  name: Dailymotion
  slug: dailymotion
  status: profiled
  tags: *id010
  url: /providers/dailymotion/
- agent_band: agent-ready
  agent_readiness: 36.1
  band: strong
  in_catalog: true
  kin_score: 61.4
  mcp: *id011
  name: DeepL
  slug: deepl
  status: profiled
  tags: *id012
  url: /providers/deepl/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: thin
  in_catalog: true
  kin_score: 30.7
  mcp: *id013
  name: Deezer
  slug: deezer
  status: profiled
  tags: *id014
  url: /providers/deezer/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 48.7
  mcp: *id015
  name: Docker Hub
  slug: docker-hub
  status: profiled
  tags: *id016
  url: /providers/docker-hub/
- agent_band: agent-ready
  agent_readiness: 60.0
  band: strong
  in_catalog: true
  kin_score: 57.7
  mcp: *id017
  name: Exa
  slug: exa-ai
  status: profiled
  tags: *id018
  url: /providers/exa-ai/
- agent_band: agent-aware
  agent_readiness: 25.1
  band: developing
  in_catalog: true
  kin_score: 49.1
  mcp: *id019
  name: Flickr
  slug: flickr
  status: profiled
  tags: *id020
  url: /providers/flickr/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.8
  mcp: *id021
  name: Freesound
  slug: freesound
  status: profiled
  tags: *id022
  url: /providers/freesound/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 34.8
  mcp: *id023
  name: Genius
  slug: genius
  status: profiled
  tags: *id024
  url: /providers/genius/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: strong
  in_catalog: true
  kin_score: 56.0
  mcp: *id025
  name: GIPHY
  slug: giphy
  status: profiled
  tags: *id026
  url: /providers/giphy/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id027
  name: GitHub
  slug: github
  status: profiled
  tags: *id028
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id029
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id030
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 38.6
  band: strong
  in_catalog: true
  kin_score: 61.6
  mcp: *id031
  name: Google Programmable Search
  slug: google-custom-search
  status: profiled
  tags: *id032
  url: /providers/google-custom-search/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 27.3
  mcp: *id033
  name: Hacker News
  slug: hacker-news
  status: profiled
  tags: *id034
  url: /providers/hacker-news/
- agent_band: agent-ready
  agent_readiness: 36.9
  band: exemplar
  in_catalog: true
  kin_score: 69.1
  mcp: *id035
  name: Hugging Face Hub
  slug: hugging-face
  status: profiled
  tags: *id036
  url: /providers/hugging-face/
- agent_band: agent-aware
  agent_readiness: 20.8
  band: developing
  in_catalog: true
  kin_score: 47.2
  mcp: *id037
  name: Imgur
  slug: imgur
  status: profiled
  tags: *id038
  url: /providers/imgur/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id039
  name: Jina AI
  slug: jina-ai
  status: profiled
  tags: *id040
  url: /providers/jina-ai/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 38.8
  mcp: *id041
  name: Kagi
  slug: kagi
  status: profiled
  tags: *id042
  url: /providers/kagi/
- agent_band: agent-aware
  agent_readiness: 20.4
  band: thin
  in_catalog: true
  kin_score: 33.9
  mcp: *id043
  name: Lemmy
  slug: lemmy
  status: profiled
  tags: *id044
  url: /providers/lemmy/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: emerging
  in_catalog: true
  kin_score: 24.3
  mcp: *id045
  name: LibreTranslate
  slug: libre-translate
  status: profiled
  tags: *id046
  url: /providers/libre-translate/
- agent_band: agent-aware
  agent_readiness: 22.0
  band: emerging
  in_catalog: true
  kin_score: 25.5
  mcp: *id047
  name: Mastodon
  slug: mastodon
  status: profiled
  tags: *id048
  url: /providers/mastodon/
- agent_band: agent-ready
  agent_readiness: 30.2
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id049
  name: Microsoft Bing
  slug: microsoft
  status: profiled
  tags: *id050
  url: /providers/microsoft/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.8
  mcp: *id051
  name: Mixcloud
  slug: mixcloud
  status: profiled
  tags: *id052
  url: /providers/mixcloud/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id053
  name: npm
  slug: npm
  status: profiled
  tags: *id054
  url: /providers/npm/
- agent_band: agent-aware
  agent_readiness: 17.4
  band: thin
  in_catalog: true
  kin_score: 28.3
  mcp: *id055
  name: Open-Meteo
  slug: open-meteo
  status: profiled
  tags: *id056
  url: /providers/open-meteo/
- agent_band: human-only
  agent_readiness: 0.7
  band: minimal
  in_catalog: true
  kin_score: 5.9
  mcp: *id057
  name: OpenAlex
  slug: openalex
  status: profiled
  tags: *id058
  url: /providers/openalex/
- agent_band: agent-aware
  agent_readiness: 28.3
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id059
  name: OpenStreetMap
  slug: openstreetmap
  status: profiled
  tags: *id060
  url: /providers/openstreetmap/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: thin
  in_catalog: true
  kin_score: 32.4
  mcp: *id061
  name: Openverse
  slug: openverse
  status: profiled
  tags: *id062
  url: /providers/openverse/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: thin
  in_catalog: true
  kin_score: 30.1
  mcp: *id063
  name: PeerTube
  slug: peertube
  status: profiled
  tags: *id064
  url: /providers/peertube/
- agent_band: agent-aware
  agent_readiness: 22.1
  band: thin
  in_catalog: true
  kin_score: 38.4
  mcp: *id065
  name: Pexels
  slug: pexels
  status: profiled
  tags: *id066
  url: /providers/pexels/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 13.7
  mcp: *id067
  name: Pixabay
  slug: pixabay
  status: profiled
  tags: *id068
  url: /providers/pixabay/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: emerging
  in_catalog: true
  kin_score: 25.0
  mcp: *id069
  name: PubMed
  slug: pubmed
  status: profiled
  tags: *id070
  url: /providers/pubmed/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 38.4
  mcp: *id071
  name: PyPI
  slug: pypi
  status: profiled
  tags: *id072
  url: /providers/pypi/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: thin
  in_catalog: true
  kin_score: 33.4
  mcp: *id073
  name: Semantic Scholar
  slug: semantic-scholar
  status: profiled
  tags: *id074
  url: /providers/semantic-scholar/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 30.9
  mcp: *id075
  name: SoundCloud
  slug: soundcloud
  status: profiled
  tags: *id076
  url: /providers/soundcloud/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id077
  name: Spotify
  slug: spotify
  status: profiled
  tags: *id078
  url: /providers/spotify/
- agent_band: agent-aware
  agent_readiness: 26.6
  band: thin
  in_catalog: true
  kin_score: 34.9
  mcp: *id079
  name: Springer Nature
  slug: springer-nature
  status: profiled
  tags: *id080
  url: /providers/springer-nature/
- agent_band: agent-ready
  agent_readiness: 29.8
  band: developing
  in_catalog: true
  kin_score: 40.9
  mcp: *id081
  name: Stack Exchange
  slug: stackexchange
  status: profiled
  tags: *id082
  url: /providers/stackexchange/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.6
  mcp: *id083
  name: TinEye
  slug: tineye
  status: profiled
  tags: *id084
  url: /providers/tineye/
- agent_band: agent-ready
  agent_readiness: 52.6
  band: developing
  in_catalog: true
  kin_score: 39.4
  mcp: *id085
  name: Unsplash
  slug: unsplash
  status: profiled
  tags: *id086
  url: /providers/unsplash/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id087
  name: Vimeo
  slug: vimeo
  status: profiled
  tags: *id088
  url: /providers/vimeo/
- agent_band: agent-ready
  agent_readiness: 30.7
  band: developing
  in_catalog: true
  kin_score: 53.4
  mcp: *id089
  name: Wikidata
  slug: wikidata
  status: profiled
  tags: *id090
  url: /providers/wikidata/
- agent_band: agent-ready
  agent_readiness: 29.3
  band: developing
  in_catalog: true
  kin_score: 41.8
  mcp: *id091
  name: Wikipedia
  slug: wikipedia
  status: profiled
  tags: *id092
  url: /providers/wikipedia/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: thin
  in_catalog: true
  kin_score: 36.2
  mcp: *id093
  name: Wolfram|Alpha
  slug: wolframalpha
  status: profiled
  tags: *id094
  url: /providers/wolframalpha/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id095
  name: Yandex Search API
  slug: yandex
  status: queued for profiling
  tags: *id096
  url: null
- agent_band: agent-ready
  agent_readiness: 41.4
  band: strong
  in_catalog: true
  kin_score: 65.4
  mcp: *id097
  name: YouTube Data API
  slug: youtube
  status: profiled
  tags: *id098
  url: /providers/youtube/
siblings:
- name: Algolia
  rows: 7
  url: /applications/search-engine/algolia/
- name: Elasticsearch
  rows: 26
  url: /applications/search-engine/elasticsearch/
- name: Meilisearch
  rows: 4
  url: /applications/search-engine/meilisearch/
- name: OpenSearch
  rows: 23
  url: /applications/search-engine/opensearch/
- name: Quickwit
  rows: 8
  url: /applications/search-engine/quickwit/
- name: Typesense
  rows: 5
  url: /applications/search-engine/typesense/
sitemap: true
title: 'SearXNG: Site & App Search reference app'
---
