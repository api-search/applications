---
app: AnkiDroid
app_slug: ankidroid
app_url: https://github.com/ankidroid/Anki-Android
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
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: language-learning
  name: Language Learning
  url: /applications/language-learning/
counts:
  declared: 0
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.ichi2.anki/latest/
- route: dependency manifest
  url: https://github.com/ankidroid/Anki-Android/blob/main/gradle/libs.versions.toml
- route: source code
  url: https://github.com/ankidroid/Anki-Android/blob/main/libanki/src/main/java/com/ichi2/anki/libanki/Sync.kt
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
  source: https://github.com/ankidroid/Anki-Android/blob/main/libanki/src/main/java/com/ichi2/anki/libanki/Sync.kt
  tier: observed
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
    mcp: &id003
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id004
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://github.com/ankidroid/Anki-Android/blob/main/gradle/libs.versions.toml
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/language-learning/ankidroid/
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
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id003
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id004
  url: /providers/google-analytics/
siblings:
- name: Anki
  rows: 1
  url: /applications/language-learning/anki/
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
title: 'AnkiDroid: Language Learning reference app'
---
