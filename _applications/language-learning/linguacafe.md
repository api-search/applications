---
app: LinguaCafe
app_slug: linguacafe
app_url: https://github.com/simjanos-dev/LinguaCafe
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-220.70
  key: AE-220.70
  layer: domain
  name: Flashcards & Spaced Repetition
  providers:
  - AnkiWeb (Ankitects)
  url: /capabilities/flashcards-spaced-repetition/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: domain
  name: Machine Translation
  providers:
  - DeepL
  - LibreTranslate
  - MyMemory (Translated)
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
category:
  id: language-learning
  name: Language Learning
  url: /applications/language-learning/
counts:
  declared: 0
  observed: 4
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/simjanos-dev/LinguaCafe/blob/main/composer.json
- route: source code
  url: https://github.com/simjanos-dev/LinguaCafe/blob/main/app/Services/AnkiApiService.php
- route: source code
  url: https://github.com/simjanos-dev/LinguaCafe/tree/main/app/Http/Requests/Dictionaries
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-220.70
    key: AE-220.70
    name: Flashcards & Spaced Repetition
    url: /capabilities/flashcards-spaced-repetition/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.7
    band: minimal
    in_catalog: true
    kin_score: 7.3
    mcp: &id001
      status: unknown
    slug: ankiweb
    status: profiled
    tags: &id002
    - Company
    url: /providers/ankiweb/
  layer: domain
  name: AnkiWeb (Ankitects)
  provider: ankiweb
  says: ships the AnkiWeb (Ankitects) SDK or integration code
  source: https://github.com/simjanos-dev/LinguaCafe/blob/main/app/Services/AnkiApiService.php
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
    mcp: &id003
      source: https://github.com/DeepL/deepl-mcp-server
      status: verified
    slug: deepl
    status: profiled
    tags: &id004
    - Artificial Intelligence
    - Deep Learning
    - Glossary
    - Localization
    url: /providers/deepl/
  layer: domain
  name: DeepL
  provider: deepl
  says: ships the DeepL SDK or integration code
  source: https://github.com/simjanos-dev/LinguaCafe/blob/main/app/Http/Requests/Dictionaries/CreateDeeplDictionaryRequest.php
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
    mcp: &id005
      source: https://github.com/LibreTranslate/LibreTranslate-MCP
      status: verified
    slug: libre-translate
    status: profiled
    tags: &id006
    - Machine Translation
    - Natural Language Processing
    - Open Source
    - Translation
    url: /providers/libre-translate/
  layer: domain
  name: LibreTranslate
  provider: libre-translate
  says: ships the LibreTranslate SDK or integration code
  source: https://github.com/simjanos-dev/LinguaCafe/blob/main/app/Http/Requests/Dictionaries/CreateLibreTranslateDictionaryRequest.php
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.9
    mcp: &id007
      status: none
    slug: mymemory
    status: profiled
    tags: &id008
    - Company
    - Localization
    - Machine Translation
    - Translation
    url: /providers/mymemory/
  layer: domain
  name: MyMemory (Translated)
  provider: mymemory
  says: ships the MyMemory (Translated) SDK or integration code
  source: https://github.com/simjanos-dev/LinguaCafe/blob/main/app/Http/Requests/Dictionaries/CreateMyMemoryDictionaryRequest.php
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/language-learning/linguacafe/
providers:
- agent_band: human-only
  agent_readiness: 0.7
  band: minimal
  in_catalog: true
  kin_score: 7.3
  mcp: *id001
  name: AnkiWeb (Ankitects)
  slug: ankiweb
  status: profiled
  tags: *id002
  url: /providers/ankiweb/
- agent_band: agent-ready
  agent_readiness: 36.1
  band: strong
  in_catalog: true
  kin_score: 61.4
  mcp: *id003
  name: DeepL
  slug: deepl
  status: profiled
  tags: *id004
  url: /providers/deepl/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: emerging
  in_catalog: true
  kin_score: 24.3
  mcp: *id005
  name: LibreTranslate
  slug: libre-translate
  status: profiled
  tags: *id006
  url: /providers/libre-translate/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.9
  mcp: *id007
  name: MyMemory (Translated)
  slug: mymemory
  status: profiled
  tags: *id008
  url: /providers/mymemory/
siblings:
- name: Anki
  rows: 1
  url: /applications/language-learning/anki/
- name: AnkiDroid
  rows: 2
  url: /applications/language-learning/ankidroid/
- name: Lute
  rows: 6
  url: /applications/language-learning/lute/
- name: VocabSieve
  rows: 4
  url: /applications/language-learning/vocabsieve/
- name: Yomitan
  rows: 3
  url: /applications/language-learning/yomitan/
sitemap: true
title: 'LinguaCafe: Language Learning reference app'
---
