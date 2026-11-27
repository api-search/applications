---
app: VocabSieve
app_slug: vocabsieve
app_url: https://github.com/FreeLanguageTools/vocabsieve
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230.90
  key: AE-230.90
  layer: domain
  name: Dictionaries & Lexical Reference
  providers:
  - Wiktionary
  url: /capabilities/dictionaries-lexical-reference/
  via_parent: null
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
  - Google Translate
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-230.90.10
  key: AE-230.90.10
  layer: domain
  name: Pronunciation Audio
  providers:
  - Forvo
  url: /capabilities/dictionaries-lexical-reference/
  via_parent: Dictionaries & Lexical Reference
category:
  id: language-learning
  name: Language Learning
  url: /applications/language-learning/
counts:
  declared: 0
  observed: 4
credits: []
evidence:
- route: documentation
  url: https://github.com/FreeLanguageTools/vocabsieve/blob/master/docs/resources.md
- route: source code
  url: https://github.com/FreeLanguageTools/vocabsieve/tree/master/vocabsieve/sources
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
  source: https://github.com/FreeLanguageTools/vocabsieve/blob/master/vocabsieve/config/anki_tab.py
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
    kin_score: 6.9
    mcp: &id003
      status: unknown
    slug: forvo
    status: profiled
    tags: &id004
    - Company
    url: /providers/forvo/
  layer: domain
  name: Forvo
  provider: forvo
  says: ships the Forvo SDK or integration code
  source: https://github.com/FreeLanguageTools/vocabsieve/blob/master/vocabsieve/sources/forvo_audio_source.py
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
    agent_readiness: 33.9
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id005
      status: none
    slug: google-translate
    status: profiled
    tags: &id006
    - Google Cloud
    - Internationalization
    - Language Detection
    - Localization
    url: /providers/google-translate/
  layer: domain
  name: Google Translate
  provider: google-translate
  says: ships the Google Translate SDK or integration code
  source: https://github.com/FreeLanguageTools/vocabsieve/blob/master/vocabsieve/sources/google_translate_source.py
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
    mcp: &id007
      status: none
    slug: wiktionary
    status: profiled
    tags: &id008
    - Dictionaries
    - MediaWiki
    - Open Source
    - Wikimedia
    url: /providers/wiktionary/
  layer: domain
  name: Wiktionary
  provider: wiktionary
  says: ships the Wiktionary SDK or integration code
  source: https://github.com/FreeLanguageTools/vocabsieve/blob/master/vocabsieve/sources/wiktionary_source.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/language-learning/vocabsieve/
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
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.9
  mcp: *id003
  name: Forvo
  slug: forvo
  status: profiled
  tags: *id004
  url: /providers/forvo/
- agent_band: agent-ready
  agent_readiness: 33.9
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id005
  name: Google Translate
  slug: google-translate
  status: profiled
  tags: *id006
  url: /providers/google-translate/
- agent_band: agent-ready
  agent_readiness: 29.7
  band: developing
  in_catalog: true
  kin_score: 48.9
  mcp: *id007
  name: Wiktionary
  slug: wiktionary
  status: profiled
  tags: *id008
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
- name: Lute
  rows: 6
  url: /applications/language-learning/lute/
- name: Yomitan
  rows: 3
  url: /applications/language-learning/yomitan/
sitemap: true
title: 'VocabSieve: Language Learning reference app'
---
