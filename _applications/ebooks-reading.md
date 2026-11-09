---
access: understanding
agent_layer: []
apps:
- anchor: calibre-web
  counts:
    declared: 0
    observed: 11
  evidence:
  - route: dependency manifest
    url: https://github.com/janeczku/calibre-web/blob/master/optional-requirements.txt
  - route: source code
    url: https://github.com/janeczku/calibre-web/blob/master/cps/kobo.py
  - route: source code
    url: https://github.com/janeczku/calibre-web/blob/master/cps/oauth_bb.py
  - route: source code
    url: https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.20
      key: AE-170.60.20
      name: Books & E-Books
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Amazon
    provider: amazon
    says: ships the Amazon SDK or integration code
    source: https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.20
      key: AE-170.60.20
      name: Books & E-Books
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Comic Vine
    provider: comic-vine
    says: ships the Comic Vine SDK or integration code
    source: https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.20
      key: AE-170.60.20
      name: Books & E-Books
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Douban
    provider: douban
    says: ships the Douban SDK or integration code
    source: https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/janeczku/calibre-web/blob/master/cps/oauth_bb.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.20
      key: AE-170.60.20
      name: Books & E-Books
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Goodreads
    provider: goodreads
    says: ships the Goodreads SDK or integration code
    source: https://github.com/janeczku/calibre-web/blob/master/optional-requirements.txt
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.20
      key: AE-170.60.20
      name: Books & E-Books
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Google Books
    provider: google-books
    says: ships the Google Books SDK or integration code
    source: https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Drive
    provider: google-drive
    says: ships the Google Drive SDK or integration code
    source: https://github.com/janeczku/calibre-web/blob/master/optional-requirements.txt
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.100
      key: AE-230.100
      name: Scholarly & Research Metadata
      url: /capabilities/scholarly-research-metadata/
      via_parent: null
    credit: null
    layer: domain
    name: Google Scholar
    provider: google-scholar
    says: ships the Google Scholar SDK or integration code
    source: https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://github.com/janeczku/calibre-web/blob/master/cps/oauth_bb.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.20
      key: AE-170.60.20
      name: Books & E-Books
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: LubimyCzytac
    provider: lubimyczytac
    says: ships the LubimyCzytac SDK or integration code
    source: https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.20
      key: AE-170.60.20
      name: Books & E-Books
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Rakuten Kobo
    provider: rakuten-kobo
    says: ships the Rakuten Kobo SDK or integration code
    source: https://github.com/janeczku/calibre-web/blob/master/cps/kobo.py
    tier: observed
  kind: self-hosted
  name: Calibre-Web
  page: /applications/ebooks-reading/calibre-web/
  slug: calibre-web
  url: https://github.com/janeczku/calibre-web
- anchor: kavita
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://github.com/Kareadita/Kavita/blob/develop/Kavita.Common/Kavita.Common.csproj
  - route: source code
    url: https://github.com/Kareadita/Kavita/blob/develop/Kavita.API/Services/Plus/IScrobblingService.cs
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.100
      key: AE-170.100
      name: Watch & Listen History Sync
      url: /capabilities/watch-listen-history-sync/
      via_parent: null
    credit: null
    layer: domain
    name: AniList
    provider: anilist
    says: ships the AniList SDK or integration code
    source: https://github.com/Kareadita/Kavita/blob/develop/Kavita.API/Services/Plus/IScrobblingService.cs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.100
      key: AE-170.100
      name: Watch & Listen History Sync
      url: /capabilities/watch-listen-history-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Hardcover
    provider: hardcover
    says: ships the Hardcover SDK or integration code
    source: https://github.com/Kareadita/Kavita/blob/develop/Kavita.API/Services/Plus/IScrobblingService.cs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.100
      key: AE-170.100
      name: Watch & Listen History Sync
      url: /capabilities/watch-listen-history-sync/
      via_parent: null
    credit: null
    layer: domain
    name: MyAnimeList
    provider: myanimelist
    says: ships the MyAnimeList SDK or integration code
    source: https://github.com/Kareadita/Kavita/blob/develop/Kavita.API/Services/Plus/IScrobblingService.cs
    tier: observed
  kind: self-hosted
  name: Kavita
  page: /applications/ebooks-reading/kavita/
  slug: kavita
  url: https://github.com/Kareadita/Kavita
- anchor: komga
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: dependency manifest
    url: https://github.com/gotson/komga/blob/master/komga/build.gradle.kts
  - route: source code
    url: https://github.com/gotson/komga/blob/master/komga/src/main/kotlin/org/gotson/komga/infrastructure/kobo/KoboProxy.kt
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.20
      key: AE-170.60.20
      name: Books & E-Books
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Rakuten Kobo
    provider: rakuten-kobo
    says: ships the Rakuten Kobo SDK or integration code
    source: https://github.com/gotson/komga/blob/master/komga/src/main/kotlin/org/gotson/komga/infrastructure/kobo/KoboProxy.kt
    tier: observed
  kind: self-hosted
  name: Komga
  page: /applications/ebooks-reading/komga/
  slug: komga
  url: https://github.com/gotson/komga
- anchor: koreader
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/org.koreader.launcher/latest/
  - route: source code
    url: https://github.com/koreader/koreader/blob/master/frontend/ui/wikipedia.lua
  - route: source code
    url: https://github.com/koreader/koreader/tree/master/plugins
  - route: source code
    url: https://github.com/koreader/koreader/tree/master/plugins/cloudstorage.koplugin/providers
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Dropbox
    provider: dropbox
    says: ships the Dropbox SDK or integration code
    source: https://github.com/koreader/koreader/tree/master/plugins/cloudstorage.koplugin/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: wallabag
    provider: wallabag
    says: ships the wallabag SDK or integration code
    source: https://github.com/koreader/koreader/tree/master/plugins/wallabag.koplugin
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
    name: Wikipedia
    provider: wikipedia
    says: ships the Wikipedia SDK or integration code
    source: https://github.com/koreader/koreader/blob/master/frontend/ui/wikipedia.lua
    tier: observed
  kind: self-hosted
  name: KOReader
  page: /applications/ebooks-reading/koreader/
  slug: koreader
  url: https://github.com/koreader/koreader
- anchor: readest
  counts:
    declared: 0
    observed: 14
  evidence:
  - route: dependency manifest
    url: https://github.com/readest/readest/blob/main/apps/readest-app/package.json
  - route: source code
    url: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/sync/providers
  - route: source code
    url: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/translators/providers
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Apple (iCloud)
    provider: apple
    says: ships the Apple (iCloud) SDK or integration code
    source: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/sync/providers/icloud
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
    name: Azure Translator
    provider: microsoft-azure
    says: ships the Azure Translator SDK or integration code
    source: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/translators/providers/azure.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Cloudflare
    provider: cloudflare
    says: ships the Cloudflare SDK or integration code
    source: https://github.com/readest/readest/blob/main/apps/readest-app/package.json
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
    source: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/translators/providers/deepl.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Drive
    provider: google-drive
    says: ships the Google Drive SDK or integration code
    source: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/sync/providers/gdrive
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: common
    name: Google Play
    provider: google-play
    says: ships the Google Play SDK or integration code
    source: https://github.com/readest/readest/blob/main/apps/readest-app/package.json
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
    source: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/translators/providers/google.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.40
      key: AE-110.10.40
      name: On-Device & Edge Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Ollama
    provider: ollama
    says: ships the Ollama SDK or integration code
    source: https://github.com/readest/readest/blob/main/apps/readest-app/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: OneDrive
    provider: microsoft-onedrive
    says: ships the OneDrive SDK or integration code
    source: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/sync/providers/onedrive
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
    name: PostHog
    provider: posthog
    says: ships the PostHog SDK or integration code
    source: https://github.com/readest/readest/blob/main/apps/readest-app/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://github.com/readest/readest/blob/main/apps/readest-app/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/readest/readest/blob/main/apps/readest-app/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Supabase
    provider: supabase
    says: ships the Supabase SDK or integration code
    source: https://github.com/readest/readest/blob/main/apps/readest-app/package.json
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
    name: Yandex Translate
    provider: yandex-translate
    says: ships the Yandex Translate SDK or integration code
    source: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/translators/providers/yandex.ts
    tier: observed
  kind: self-hosted
  name: Readest
  page: /applications/ebooks-reading/readest/
  slug: readest
  url: https://github.com/readest/readest
- anchor: kindle
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.amazon.kindle/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Bugsnag
    provider: bugsnag
    says: ships the Bugsnag SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.amazon.kindle/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.amazon.kindle/latest/
    tier: observed
  kind: commercial
  name: Kindle
  page: /applications/ebooks-reading/kindle/
  slug: kindle
  url: https://www.amazon.com/kindle
- anchor: goodreads
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.goodreads/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Bugsnag
    provider: bugsnag
    says: ships the Bugsnag SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.goodreads/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.goodreads/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google AdMob
    provider: google-admob
    says: ships the Google AdMob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.goodreads/latest/
    tier: observed
  kind: commercial
  name: Goodreads
  page: /applications/ebooks-reading/goodreads/
  slug: goodreads
  url: https://www.goodreads.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: ebooks-reading
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Books
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Books & Reference
  store: google-play
  url: https://play.google.com/store/apps/category/BOOKS_AND_REFERENCE
- category: Comics
  store: google-play
  url: https://play.google.com/store/apps/category/COMICS
- category: Document Management - E-books
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#document-management---e-books
name: E-books, Reading & Comics
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.20
    key: AE-170.60.20
    name: Books & E-Books
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  fit: exact
  layer: domain
  why: book/comic metadata and e-book store sync
- capability:
    attribution: API Evangelist extension
    id: AE-230.100
    key: AE-230.100
    name: Scholarly & Research Metadata
    url: /capabilities/scholarly-research-metadata/
    via_parent: null
  fit: exact
  layer: domain
  why: academic paper metadata
- capability:
    attribution: API Evangelist extension
    id: AE-170.100
    key: AE-170.100
    name: Watch & Listen History Sync
    url: /capabilities/watch-listen-history-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: reading-progress scrobbling to tracker sites (nearest node; see candidate)
- capability:
    attribution: API Evangelist extension
    id: AE-230.90
    key: AE-230.90
    name: Dictionaries & Lexical Reference
    url: /capabilities/dictionaries-lexical-reference/
    via_parent: null
  fit: exact
  layer: domain
  why: in-book lookup (Wikipedia)
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  fit: exact
  layer: domain
  why: read-later article sync
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: library and progress sync to drives
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: OAuth sign-in
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: app backend
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: subscriptions
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: app analytics
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash/error reporting
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.40
    key: AE-110.10.40
    name: On-Device & Edge Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: local LLM reading assistant
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: exact
  layer: common
  why: store purchase verification
- capability:
    attribution: API Evangelist extension
    id: AE-932
    key: AE-932
    name: Edge Functions & Edge Config Stores
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: edge deployment
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: domain
  why: in-book translation
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: SDK named in reference-app Exodus reports
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.20
      key: AE-170.60.20
      name: Books & E-Books
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Calibre-Web
      - Komga
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Rakuten Kobo
      slug: rakuten-kobo
      sources:
      - https://github.com/gotson/komga/blob/master/komga/src/main/kotlin/org/gotson/komga/infrastructure/kobo/KoboProxy.kt
      - https://github.com/janeczku/calibre-web/blob/master/cps/kobo.py
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 46.8
      apps:
      - Calibre-Web
      band: developing
      in_catalog: true
      kin_score: 46.7
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Amazon
      slug: amazon
      sources:
      - https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: observed
      url: /providers/amazon/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Calibre-Web
      band: thin
      in_catalog: true
      kin_score: 34.1
      mcp:
        status: none
      name: Google Books
      slug: google-books
      sources:
      - https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
      status: profiled
      tags:
      - Books
      - Ebooks
      - Google
      - Library
      tier: observed
      url: /providers/google-books/
    - agent_band: agent-aware
      agent_readiness: 6.5
      apps:
      - Calibre-Web
      band: emerging
      in_catalog: true
      kin_score: 24.1
      mcp:
        status: none
      name: Goodreads
      slug: goodreads
      sources:
      - https://github.com/janeczku/calibre-web/blob/master/optional-requirements.txt
      status: profiled
      tags:
      - Books
      - Company
      - Consumer
      - Reading
      tier: observed
      url: /providers/goodreads/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Calibre-Web
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        status: unknown
      name: Comic Vine
      slug: comic-vine
      sources:
      - https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
      status: profiled
      tags:
      - Comics
      - Public APIs
      tier: observed
      url: /providers/comic-vine/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Calibre-Web
      band: minimal
      in_catalog: true
      kin_score: 4.2
      mcp:
        status: unknown
      name: LubimyCzytac
      slug: lubimyczytac
      sources:
      - https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
      status: profiled
      tags:
      - Books
      - Company
      - Price Comparison
      - Reviews
      tier: observed
      url: /providers/lubimyczytac/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Calibre-Web
      band: minimal
      in_catalog: true
      kin_score: 4.0
      mcp:
        status: none
      name: Douban
      slug: douban
      sources:
      - https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
      status: profiled
      tags:
      - China
      - Entertainment
      - Media
      - Social
      tier: observed
      url: /providers/douban/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.5
      apps:
      - Readest
      band: exemplar
      in_catalog: true
      kin_score: 78.4
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Translator
      slug: microsoft-azure
      sources:
      - https://github.com/readest/readest/tree/main/apps/readest-app/src/services/translators/providers/azure.ts
      status: profiled
      tags:
      - Cloud
      - Cloud Computing
      - Enterprise
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure/
    - agent_band: agent-ready
      agent_readiness: 36.4
      apps:
      - Readest
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://github.com/DeepL/deepl-mcp-server
        status: verified
      name: DeepL
      slug: deepl
      sources:
      - https://github.com/readest/readest/tree/main/apps/readest-app/src/services/translators/providers/deepl.ts
      status: profiled
      tags:
      - Artificial Intelligence
      - Deep Learning
      - Glossary
      - Localization
      tier: observed
      url: /providers/deepl/
    - agent_band: agent-aware
      agent_readiness: 17.9
      apps:
      - Readest
      band: developing
      in_catalog: true
      kin_score: 51.6
      mcp:
        status: none
      name: Google Translate
      slug: google-translate
      sources:
      - https://github.com/readest/readest/tree/main/apps/readest-app/src/services/translators/providers/google.ts
      status: profiled
      tags:
      - Google Cloud
      - Internationalization
      - Language Detection
      - Localization
      tier: observed
      url: /providers/google-translate/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Readest
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Yandex Translate
      slug: yandex-translate
      sources:
      - https://github.com/readest/readest/tree/main/apps/readest-app/src/services/translators/providers/yandex.ts
      status: profiled
      tags:
      - Language Detection
      - Machine Translation
      - Natural Language Processing
      - Translation Dictionary
      tier: observed
      url: /providers/yandex-translate/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.100
      key: AE-170.100
      name: Watch & Listen History Sync
      url: /capabilities/watch-listen-history-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.6
      apps:
      - Kavita
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: AniList
      slug: anilist
      sources:
      - https://github.com/Kareadita/Kavita/blob/develop/Kavita.API/Services/Plus/IScrobblingService.cs
      status: profiled
      tags:
      - Anime
      - Entertainment
      - Manga
      - Media
      tier: observed
      url: /providers/anilist/
    - agent_band: agent-ready
      agent_readiness: 31.0
      apps:
      - Kavita
      band: thin
      in_catalog: true
      kin_score: 28.6
      mcp:
        status: none
      name: Hardcover
      slug: hardcover
      sources:
      - https://github.com/Kareadita/Kavita/blob/develop/Kavita.API/Services/Plus/IScrobblingService.cs
      status: profiled
      tags:
      - Book
      - Company
      - Reading
      - Social
      tier: observed
      url: /providers/hardcover/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Kavita
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        status: none
      name: MyAnimeList
      slug: myanimelist
      sources:
      - https://github.com/Kareadita/Kavita/blob/develop/Kavita.API/Services/Plus/IScrobblingService.cs
      status: profiled
      tags:
      - Anime
      - Public APIs
      tier: observed
      url: /providers/myanimelist/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - KOReader
      band: emerging
      in_catalog: true
      kin_score: 17.3
      mcp:
        status: none
      name: wallabag
      slug: wallabag
      sources:
      - https://github.com/koreader/koreader/tree/master/plugins/wallabag.koplugin
      status: profiled
      tags:
      - Open Source
      - Privacy
      - Read-it-later
      - Self-Hosted
      tier: observed
      url: /providers/wallabag/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.90
      key: AE-230.90
      name: Dictionaries & Lexical Reference
      url: /capabilities/dictionaries-lexical-reference/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.8
      apps:
      - KOReader
      band: developing
      in_catalog: true
      kin_score: 43.0
      mcp:
        status: none
      name: Wikipedia
      slug: wikipedia
      sources:
      - https://github.com/koreader/koreader/blob/master/frontend/ui/wikipedia.lua
      status: profiled
      tags:
      - Encyclopedia
      - Open Data
      - Open Knowledge
      - Public APIs
      tier: observed
      url: /providers/wikipedia/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.100
      key: AE-230.100
      name: Scholarly & Research Metadata
      url: /capabilities/scholarly-research-metadata/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Calibre-Web
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Google Scholar
      slug: google-scholar
      sources:
      - https://github.com/janeczku/calibre-web/tree/master/cps/metadata_provider
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.3
      apps:
      - Calibre-Web
      - Readest
      band: exemplar
      in_catalog: true
      kin_score: 67.1
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://github.com/janeczku/calibre-web/blob/master/optional-requirements.txt
      - https://github.com/readest/readest/tree/main/apps/readest-app/src/services/sync/providers/gdrive
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: observed
      url: /providers/google-drive/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Readest
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Apple (iCloud)
      slug: apple
      sources:
      - https://github.com/readest/readest/tree/main/apps/readest-app/src/services/sync/providers/icloud
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Readest
      band: developing
      in_catalog: true
      kin_score: 48.3
      mcp:
        status: none
      name: OneDrive
      slug: microsoft-onedrive
      sources:
      - https://github.com/readest/readest/tree/main/apps/readest-app/src/services/sync/providers/onedrive
      status: profiled
      tags:
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: observed
      url: /providers/microsoft-onedrive/
    - agent_band: agent-ready
      agent_readiness: 45.8
      apps:
      - KOReader
      band: developing
      in_catalog: true
      kin_score: 47.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://github.com/koreader/koreader/tree/master/plugins/cloudstorage.koplugin/providers
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: observed
      url: /providers/dropbox/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.1
      apps:
      - Goodreads
      - Kindle
      band: exemplar
      in_catalog: true
      kin_score: 78.5
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.amazon.kindle/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.goodreads/latest/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Readest
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/readest/readest/blob/main/apps/readest-app/package.json
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Kindle
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.amazon.kindle/latest/
      status: profiled
      tags: &id002
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 57.3
      apps:
      - Readest
      band: strong
      in_catalog: true
      kin_score: 57.7
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://github.com/readest/readest/blob/main/apps/readest-app/package.json
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Goodreads
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id001
      name: Firebase
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.goodreads/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 63.4
      apps:
      - Calibre-Web
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/janeczku/calibre-web/blob/master/cps/oauth_bb.py
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Calibre-Web
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/janeczku/calibre-web/blob/master/cps/oauth_bb.py
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-native
      agent_readiness: 69.6
      apps:
      - Readest
      band: exemplar
      in_catalog: true
      kin_score: 82.8
      mcp:
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare
      slug: cloudflare
      sources:
      - https://github.com/readest/readest/blob/main/apps/readest-app/package.json
      status: profiled
      tags:
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: observed
      url: /providers/cloudflare/
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.0
      apps:
      - Goodreads
      band: strong
      in_catalog: true
      kin_score: 61.5
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.goodreads/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Readest
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        status: none
      name: Google Play
      slug: google-play
      sources:
      - https://github.com/readest/readest/blob/main/apps/readest-app/package.json
      status: profiled
      tags:
      - Android
      - Application
      - Google Play
      - In-App Purchases
      tier: observed
      url: /providers/google-play/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.1
      apps:
      - Readest
      band: developing
      in_catalog: true
      kin_score: 49.1
      mcp:
        source: https://github.com/supabase/mcp
        status: verified
      name: Supabase
      slug: supabase
      sources:
      - https://github.com/readest/readest/blob/main/apps/readest-app/package.json
      status: profiled
      tags:
      - Authentication
      - Backend-as-a-Service
      - Open Source
      - PostgreSQL
      tier: observed
      url: /providers/supabase/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - Readest
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/readest/readest/blob/main/apps/readest-app/package.json
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.40
      key: AE-110.10.40
      name: On-Device & Edge Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Readest
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Ollama
      slug: ollama
      sources:
      - https://github.com/readest/readest/blob/main/apps/readest-app/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - LLM
      - Models
      - Ollama
      tier: observed
      url: /providers/ollama/
  layer: agent
summary:
  coverage_pct: 93.9
  declared_only: 0
  distinct_providers: 33
  in_catalog: 31
  mcp:
    documented: 0
    none: 16
    unchecked: 2
    verified: 13
  mcp_verified: 13
  mean_kin_score: 46.5
  observed: 33
  queued: 2
  reference_apps: 7
title: 'E-books, Reading & Comics: application blueprint'
---
