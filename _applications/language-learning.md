---
access: understanding
agent_layer: []
apps:
- anchor: anki
  counts:
    declared: 0
    observed: 1
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
    layer: domain
    name: AnkiWeb (Ankitects)
    provider: ankiweb
    says: ships the AnkiWeb (Ankitects) SDK or integration code
    source: https://github.com/ankitects/anki/blob/main/rslib/src/sync/http_client/mod.rs
    tier: observed
  kind: open-source-saas
  name: Anki
  page: /applications/language-learning/anki/
  slug: anki
  url: https://github.com/ankitects/anki
- anchor: ankidroid
  counts:
    declared: 0
    observed: 2
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
    layer: common
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://github.com/ankidroid/Anki-Android/blob/main/gradle/libs.versions.toml
    tier: observed
  kind: open-source-saas
  name: AnkiDroid
  page: /applications/language-learning/ankidroid/
  slug: ankidroid
  url: https://github.com/ankidroid/Anki-Android
- anchor: linguacafe
  counts:
    declared: 0
    observed: 4
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
    layer: domain
    name: MyMemory (Translated)
    provider: mymemory
    says: ships the MyMemory (Translated) SDK or integration code
    source: https://github.com/simjanos-dev/LinguaCafe/blob/main/app/Http/Requests/Dictionaries/CreateMyMemoryDictionaryRequest.php
    tier: observed
  kind: self-hosted
  name: LinguaCafe
  page: /applications/language-learning/linguacafe/
  slug: linguacafe
  url: https://github.com/simjanos-dev/LinguaCafe
- anchor: vocabsieve
  counts:
    declared: 0
    observed: 4
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
    layer: domain
    name: Wiktionary
    provider: wiktionary
    says: ships the Wiktionary SDK or integration code
    source: https://github.com/FreeLanguageTools/vocabsieve/blob/master/vocabsieve/sources/wiktionary_source.py
    tier: observed
  kind: self-hosted
  name: VocabSieve
  page: /applications/language-learning/vocabsieve/
  slug: vocabsieve
  url: https://github.com/FreeLanguageTools/vocabsieve
- anchor: lute
  counts:
    declared: 0
    observed: 6
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
    layer: domain
    name: Wiktionary
    provider: wiktionary
    says: ships the Wiktionary SDK or integration code
    source: https://github.com/LuteOrg/lute-v3/blob/develop/plugins/lute-khmer/definition.yaml
    tier: observed
  kind: self-hosted
  name: Lute
  page: /applications/language-learning/lute/
  slug: lute
  url: https://github.com/LuteOrg/lute-v3
- anchor: yomitan
  counts:
    declared: 0
    observed: 3
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
    layer: domain
    name: Wikimedia Commons
    provider: wikimedia
    says: ships the Wikimedia Commons SDK or integration code
    source: https://github.com/yomidevs/yomitan/blob/master/ext/js/media/audio-downloader.js
    tier: observed
  kind: self-hosted
  name: Yomitan
  page: /applications/language-learning/yomitan/
  slug: yomitan
  url: https://github.com/yomidevs/yomitan
author: API Evangelist
candidates: []
credits: []
html: public
id: language-learning
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Education
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Education
  store: google-play
  url: https://play.google.com/store/apps/category/EDUCATION
- category: Learning and Courses
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#learning-and-courses
name: Language Learning
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: domain
  why: sentence and word translation inside readers
- capability:
    attribution: API Evangelist extension
    id: AE-230.90
    key: AE-230.90
    name: Dictionaries & Lexical Reference
    url: /capabilities/dictionaries-lexical-reference/
    via_parent: null
  fit: exact
  layer: domain
  why: dictionary/lexical lookup; no dictionary node exists
- capability:
    attribution: API Evangelist extension
    id: AE-230.90.10
    key: AE-230.90.10
    name: Pronunciation Audio
    url: /capabilities/dictionaries-lexical-reference/
    via_parent: Dictionaries & Lexical Reference
  fit: exact
  layer: domain
  why: native-speaker pronunciation clips; no node exists
- capability:
    attribution: API Evangelist extension
    id: AE-220.70
    key: AE-220.70
    name: Flashcards & Spaced Repetition
    url: /capabilities/flashcards-spaced-repetition/
    via_parent: null
  fit: exact
  layer: domain
  why: spaced-repetition deck sync/export; no node exists
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: app usage analytics
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-230.90
      key: AE-230.90
      name: Dictionaries & Lexical Reference
      url: /capabilities/dictionaries-lexical-reference/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.7
      apps:
      - Lute
      - VocabSieve
      band: developing
      in_catalog: true
      kin_score: 48.9
      mcp:
        status: none
      name: Wiktionary
      slug: wiktionary
      sources:
      - https://github.com/FreeLanguageTools/vocabsieve/blob/master/vocabsieve/sources/wiktionary_source.py
      - https://github.com/LuteOrg/lute-v3/blob/develop/plugins/lute-khmer/definition.yaml
      status: profiled
      tags:
      - Dictionaries
      - MediaWiki
      - Open Source
      - Wikimedia
      tier: observed
      url: /providers/wiktionary/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Lute
      band: minimal
      in_catalog: true
      kin_score: 7.0
      mcp:
        status: none
      name: Glosbe
      slug: glosbe
      sources:
      - https://github.com/LuteOrg/lute-v3/blob/develop/plugins/lute-khmer/definition.yaml
      status: profiled
      tags:
      - Dictionaries
      - Language Learning
      - Multilingual
      - Translation
      tier: observed
      url: /providers/glosbe/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Yomitan
      band: minimal
      in_catalog: true
      kin_score: 5.3
      mcp:
        status: none
      name: Jisho.org
      slug: jisho
      sources:
      - https://github.com/yomidevs/yomitan/blob/master/ext/js/media/audio-downloader.js
      status: profiled
      tags:
      - Company
      - Dictionaries
      - Japanese
      - Language Learning
      tier: observed
      url: /providers/jisho/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Lute
      band: minimal
      in_catalog: true
      kin_score: 4.9
      mcp:
        status: unknown
      name: MDBG Chinese Dictionary
      slug: mdbg
      sources:
      - https://github.com/LuteOrg/lute-v3/blob/develop/plugins/lute-mandarin/definition.yaml
      status: profiled
      tags:
      - Chinese
      - Company
      - Dictionaries
      - Language Learning
      tier: observed
      url: /providers/mdbg/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Lute
      band: minimal
      in_catalog: true
      kin_score: 2.6
      mcp:
        status: unknown
      name: Kheng.info
      slug: kheng-info
      sources:
      - https://github.com/LuteOrg/lute-v3/blob/develop/plugins/lute-khmer/definition.yaml
      status: profiled
      tags:
      - Company
      - Khmer
      - Language
      - Natural Language Processing
      tier: observed
      url: /providers/kheng-info/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.1
      apps:
      - LinguaCafe
      - Lute
      band: strong
      in_catalog: true
      kin_score: 61.4
      mcp:
        source: https://github.com/DeepL/deepl-mcp-server
        status: verified
      name: DeepL
      slug: deepl
      sources:
      - https://github.com/LuteOrg/lute-v3/blob/develop/plugins/lute-mandarin/definition.yaml
      - https://github.com/simjanos-dev/LinguaCafe/blob/main/app/Http/Requests/Dictionaries/CreateDeeplDictionaryRequest.php
      status: profiled
      tags:
      - Artificial Intelligence
      - Deep Learning
      - Glossary
      - Localization
      tier: observed
      url: /providers/deepl/
    - agent_band: agent-ready
      agent_readiness: 30.2
      apps:
      - Lute
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Bing Translator (Microsoft)
      slug: microsoft
      sources:
      - https://github.com/LuteOrg/lute-v3/blob/develop/plugins/lute-khmer/definition.yaml
      status: profiled
      tags:
      - Cloud
      - Fortune 100
      - Microsoft
      - Software
      tier: observed
      url: /providers/microsoft/
    - agent_band: agent-ready
      agent_readiness: 33.9
      apps:
      - VocabSieve
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: Google Translate
      slug: google-translate
      sources:
      - https://github.com/FreeLanguageTools/vocabsieve/blob/master/vocabsieve/sources/google_translate_source.py
      status: profiled
      tags:
      - Google Cloud
      - Internationalization
      - Language Detection
      - Localization
      tier: observed
      url: /providers/google-translate/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - LinguaCafe
      band: emerging
      in_catalog: true
      kin_score: 24.3
      mcp:
        source: https://github.com/LibreTranslate/LibreTranslate-MCP
        status: verified
      name: LibreTranslate
      slug: libre-translate
      sources:
      - https://github.com/simjanos-dev/LinguaCafe/blob/main/app/Http/Requests/Dictionaries/CreateLibreTranslateDictionaryRequest.php
      status: profiled
      tags:
      - Machine Translation
      - Natural Language Processing
      - Open Source
      - Translation
      tier: observed
      url: /providers/libre-translate/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - LinguaCafe
      band: minimal
      in_catalog: true
      kin_score: 10.9
      mcp:
        status: none
      name: MyMemory (Translated)
      slug: mymemory
      sources:
      - https://github.com/simjanos-dev/LinguaCafe/blob/main/app/Http/Requests/Dictionaries/CreateMyMemoryDictionaryRequest.php
      status: profiled
      tags:
      - Company
      - Localization
      - Machine Translation
      - Translation
      tier: observed
      url: /providers/mymemory/
  - capability:
      attribution: API Evangelist extension
      id: AE-220.70
      key: AE-220.70
      name: Flashcards & Spaced Repetition
      url: /capabilities/flashcards-spaced-repetition/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.7
      apps:
      - Anki
      - AnkiDroid
      - LinguaCafe
      - VocabSieve
      band: minimal
      in_catalog: true
      kin_score: 7.3
      mcp:
        status: unknown
      name: AnkiWeb (Ankitects)
      slug: ankiweb
      sources:
      - https://github.com/FreeLanguageTools/vocabsieve/blob/master/vocabsieve/config/anki_tab.py
      - https://github.com/ankidroid/Anki-Android/blob/main/libanki/src/main/java/com/ichi2/anki/libanki/Sync.kt
      - https://github.com/ankitects/anki/blob/main/rslib/src/sync/http_client/mod.rs
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/ankiweb/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.90.10
      key: AE-230.90.10
      name: Pronunciation Audio
      url: /capabilities/dictionaries-lexical-reference/
      via_parent: Dictionaries & Lexical Reference
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.0
      apps:
      - Yomitan
      band: developing
      in_catalog: true
      kin_score: 49.8
      mcp:
        status: none
      name: Wikimedia Commons
      slug: wikimedia
      sources:
      - https://github.com/yomidevs/yomitan/blob/master/ext/js/media/audio-downloader.js
      status: profiled
      tags:
      - Encyclopedia
      - Open Knowledge
      - Wikimedia
      - Wikipedia
      tier: observed
      url: /providers/wikimedia/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - VocabSieve
      band: minimal
      in_catalog: true
      kin_score: 6.9
      mcp:
        status: unknown
      name: Forvo
      slug: forvo
      sources:
      - https://github.com/FreeLanguageTools/vocabsieve/blob/master/vocabsieve/sources/forvo_audio_source.py
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/forvo/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Yomitan
      band: minimal
      in_catalog: true
      kin_score: 3.6
      mcp:
        status: unknown
      name: LanguagePod101 (Innovative Language)
      slug: languagepod101
      sources:
      - https://github.com/yomidevs/yomitan/blob/master/ext/js/media/audio-downloader.js
      status: profiled
      tags:
      - Company
      - Education
      - Language Learning
      - Podcasts
      tier: observed
      url: /providers/languagepod101/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - AnkiDroid
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://github.com/ankidroid/Anki-Android/blob/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
  layer: common
summary:
  coverage_pct: 100.0
  declared_only: 0
  distinct_providers: 15
  in_catalog: 15
  mcp:
    documented: 0
    none: 6
    unchecked: 0
    verified: 4
  mcp_verified: 4
  mean_kin_score: 30.1
  observed: 15
  queued: 0
  reference_apps: 6
title: 'Language Learning: application blueprint'
---
