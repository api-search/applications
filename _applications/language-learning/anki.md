---
app: Anki
app_slug: anki
app_url: https://github.com/ankitects/anki
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
category:
  id: language-learning
  name: Language Learning
  url: /applications/language-learning/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/ankitects/anki/blob/main/qt/pyproject.toml
- route: source code
  url: https://github.com/ankitects/anki/blob/main/rslib/src/sync/http_client/mod.rs
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
  source: https://github.com/ankitects/anki/blob/main/rslib/src/sync/http_client/mod.rs
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/language-learning/anki/
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
siblings:
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
- name: Yomitan
  rows: 3
  url: /applications/language-learning/yomitan/
sitemap: true
title: 'Anki: Language Learning reference app'
---
