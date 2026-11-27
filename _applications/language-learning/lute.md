---
app: Lute
app_slug: lute
app_url: https://github.com/LuteOrg/lute-v3
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230.90
  key: AE-230.90
  layer: domain
  name: Dictionaries & Lexical Reference
  providers:
  - Glosbe
  - Kheng.info
  - MDBG Chinese Dictionary
  - Wiktionary
  url: /capabilities/dictionaries-lexical-reference/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: domain
  name: Machine Translation
  providers:
  - Bing Translator (Microsoft)
  - DeepL
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
category:
  id: language-learning
  name: Language Learning
  url: /applications/language-learning/
counts:
  declared: 0
  observed: 6
credits: []
evidence:
- route: source code
  url: https://github.com/LuteOrg/lute-v3/blob/develop/plugins/lute-khmer/definition.yaml
- route: source code
  url: https://github.com/LuteOrg/lute-v3/blob/develop/plugins/lute-mandarin/definition.yaml
integrations:
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
    agent_readiness: 30.2
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id001
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft
    status: profiled
    tags: &id002
    - Cloud
    - Fortune 100
    - Microsoft
    - Software
    url: /providers/microsoft/
  layer: domain
  name: Bing Translator (Microsoft)
  provider: microsoft-bing
  says: ships the Bing Translator (Microsoft) SDK or integration code
  source: https://github.com/LuteOrg/lute-v3/blob/develop/plugins/lute-khmer/definition.yaml
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
  source: https://github.com/LuteOrg/lute-v3/blob/develop/plugins/lute-mandarin/definition.yaml
  tier: observed
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
    kin_score: 7.0
    mcp: &id005
      status: none
    slug: glosbe
    status: profiled
    tags: &id006
    - Dictionaries
    - Language Learning
    - Multilingual
    - Translation
    url: /providers/glosbe/
  layer: domain
  name: Glosbe
  provider: glosbe
  says: ships the Glosbe SDK or integration code
  source: https://github.com/LuteOrg/lute-v3/blob/develop/plugins/lute-khmer/definition.yaml
  tier: observed
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
    kin_score: 2.6
    mcp: &id007
      status: unknown
    slug: kheng-info
    status: profiled
    tags: &id008
    - Company
    - Khmer
    - Language
    - Natural Language Processing
    url: /providers/kheng-info/
  layer: domain
  name: Kheng.info
  provider: kheng-info
  says: ships the Kheng.info SDK or integration code
  source: https://github.com/LuteOrg/lute-v3/blob/develop/plugins/lute-khmer/definition.yaml
  tier: observed
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
    kin_score: 4.9
    mcp: &id009
      status: unknown
    slug: mdbg
    status: profiled
    tags: &id010
    - Chinese
    - Company
    - Dictionaries
    - Language Learning
    url: /providers/mdbg/
  layer: domain
  name: MDBG Chinese Dictionary
  provider: mdbg
  says: ships the MDBG Chinese Dictionary SDK or integration code
  source: https://github.com/LuteOrg/lute-v3/blob/develop/plugins/lute-mandarin/definition.yaml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.90
    key: AE-230.90
    name: Dictionaries & Lexical Reference
    url: /capabilities/dictionaries-lexical-reference/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.7
    band: developing
    in_catalog: true
    kin_score: 48.9
    mcp: &id011
      status: none
    slug: wiktionary
    status: profiled
    tags: &id012
    - Dictionaries
    - MediaWiki
    - Open Source
    - Wikimedia
    url: /providers/wiktionary/
  layer: domain
  name: Wiktionary
  provider: wiktionary
  says: ships the Wiktionary SDK or integration code
  source: https://github.com/LuteOrg/lute-v3/blob/develop/plugins/lute-khmer/definition.yaml
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/language-learning/lute/
providers:
- agent_band: agent-ready
  agent_readiness: 30.2
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id001
  name: Bing Translator (Microsoft)
  slug: microsoft
  status: profiled
  tags: *id002
  url: /providers/microsoft/
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
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.0
  mcp: *id005
  name: Glosbe
  slug: glosbe
  status: profiled
  tags: *id006
  url: /providers/glosbe/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.6
  mcp: *id007
  name: Kheng.info
  slug: kheng-info
  status: profiled
  tags: *id008
  url: /providers/kheng-info/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.9
  mcp: *id009
  name: MDBG Chinese Dictionary
  slug: mdbg
  status: profiled
  tags: *id010
  url: /providers/mdbg/
- agent_band: agent-ready
  agent_readiness: 29.7
  band: developing
  in_catalog: true
  kin_score: 48.9
  mcp: *id011
  name: Wiktionary
  slug: wiktionary
  status: profiled
  tags: *id012
  url: /providers/wiktionary/
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
- name: VocabSieve
  rows: 4
  url: /applications/language-learning/vocabsieve/
- name: Yomitan
  rows: 3
  url: /applications/language-learning/yomitan/
sitemap: true
title: 'Lute: Language Learning reference app'
---
