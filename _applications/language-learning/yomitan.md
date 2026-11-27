---
app: Yomitan
app_slug: yomitan
app_url: https://github.com/yomidevs/yomitan
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230.90
  key: AE-230.90
  layer: domain
  name: Dictionaries & Lexical Reference
  providers:
  - Jisho.org
  url: /capabilities/dictionaries-lexical-reference/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.90.10
  key: AE-230.90.10
  layer: domain
  name: Pronunciation Audio
  providers:
  - LanguagePod101 (Innovative Language)
  - Wikimedia Commons
  url: /capabilities/dictionaries-lexical-reference/
  via_parent: Dictionaries & Lexical Reference
category:
  id: language-learning
  name: Language Learning
  url: /applications/language-learning/
counts:
  declared: 0
  observed: 3
credits: []
evidence:
- route: source code
  url: https://github.com/yomidevs/yomitan/blob/master/ext/js/media/audio-downloader.js
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-230.90
    key: AE-230.90
    name: Dictionaries & Lexical Reference
    url: /capabilities/dictionaries-lexical-reference/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.3
    mcp: &id001
      status: none
    slug: jisho
    status: profiled
    tags: &id002
    - Company
    - Dictionaries
    - Japanese
    - Language Learning
    url: /providers/jisho/
  layer: domain
  name: Jisho.org
  provider: jisho
  says: ships the Jisho.org SDK or integration code
  source: https://github.com/yomidevs/yomitan/blob/master/ext/js/media/audio-downloader.js
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.90.10
    key: AE-230.90.10
    name: Pronunciation Audio
    url: /capabilities/dictionaries-lexical-reference/
    via_parent: Dictionaries & Lexical Reference
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.6
    mcp: &id003
      status: unknown
    slug: languagepod101
    status: profiled
    tags: &id004
    - Company
    - Education
    - Language Learning
    - Podcasts
    url: /providers/languagepod101/
  layer: domain
  name: LanguagePod101 (Innovative Language)
  provider: languagepod101
  says: ships the LanguagePod101 (Innovative Language) SDK or integration code
  source: https://github.com/yomidevs/yomitan/blob/master/ext/js/media/audio-downloader.js
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.90.10
    key: AE-230.90.10
    name: Pronunciation Audio
    url: /capabilities/dictionaries-lexical-reference/
    via_parent: Dictionaries & Lexical Reference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.0
    band: developing
    in_catalog: true
    kin_score: 49.8
    mcp: &id005
      status: none
    slug: wikimedia
    status: profiled
    tags: &id006
    - Encyclopedia
    - Open Knowledge
    - Wikimedia
    - Wikipedia
    url: /providers/wikimedia/
  layer: domain
  name: Wikimedia Commons
  provider: wikimedia
  says: ships the Wikimedia Commons SDK or integration code
  source: https://github.com/yomidevs/yomitan/blob/master/ext/js/media/audio-downloader.js
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/language-learning/yomitan/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.3
  mcp: *id001
  name: Jisho.org
  slug: jisho
  status: profiled
  tags: *id002
  url: /providers/jisho/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.6
  mcp: *id003
  name: LanguagePod101 (Innovative Language)
  slug: languagepod101
  status: profiled
  tags: *id004
  url: /providers/languagepod101/
- agent_band: agent-ready
  agent_readiness: 32.0
  band: developing
  in_catalog: true
  kin_score: 49.8
  mcp: *id005
  name: Wikimedia Commons
  slug: wikimedia
  status: profiled
  tags: *id006
  url: /providers/wikimedia/
siblings:
- name: Anki
  rows: 1
  url: /applications/language-learning/anki/
- name: AnkiDroid
  rows: 2
  url: /applications/language-learning/ankidroid/
- name: LinguaCafe
  rows: 4
  url: /applications/language-learning/linguacafe/
- name: Lute
  rows: 6
  url: /applications/language-learning/lute/
- name: VocabSieve
  rows: 4
  url: /applications/language-learning/vocabsieve/
sitemap: true
title: 'Yomitan: Language Learning reference app'
---
