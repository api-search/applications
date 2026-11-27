---
access: understanding
agent_layer:
- app: Gramps Web
  finding: built-in AI chat assistant with tool calls over the tree, BYO OpenAI-compatible LLM endpoint
  source: https://github.com/gramps-project/gramps-web-api/blob/master/gramps_webapi/config.py
  tier: observed
apps:
- anchor: gramps-web
  counts:
    declared: 0
    observed: 11
  evidence:
  - route: dependency manifest
    url: https://github.com/gramps-project/gramps-web-api/blob/master/pyproject.toml
  - route: dependency manifest
    url: https://github.com/gramps-project/gramps-web/blob/main/package.json
  - route: source code
    url: https://github.com/gramps-project/gramps-web-api/blob/master/gramps_webapi/auth/oidc.py
  - route: source code
    url: https://github.com/gramps-project/gramps-web-api/blob/master/gramps_webapi/config.py
  - route: source code
    url: https://github.com/gramps-project/gramps-web-api/blob/master/gramps_webapi/const.py
  - route: source code
    url: https://github.com/gramps-project/gramps-web/blob/main/src/components/GrampsjsMap.js
  - route: source code
    url: https://github.com/gramps-project/gramps-web/blob/main/src/components/GrampsjsMapSearchbox.js
  - route: source code
    url: https://github.com/gramps-project/gramps-web/blob/main/src/wikidata.ts
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-230.110
      key: AE-230.110
      name: Genealogy Records & Family Trees
      url: /capabilities/genealogy-records-family-trees/
      via_parent: null
    credit: null
    layer: domain
    name: CompGen DES / domus.genealogy.net historical building map
    provider: compgen
    says: ships the CompGen DES / domus.genealogy.net historical building map SDK or integration code
    source: https://github.com/gramps-project/gramps-web/blob/main/src/wikidata.ts
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
    name: Google OIDC sign-in (accounts.google.com)
    provider: google-identity-platform
    says: ships the Google OIDC sign-in (accounts.google.com) SDK or integration code
    source: https://github.com/gramps-project/gramps-web-api/blob/master/gramps_webapi/auth/oidc.py
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
    name: Microsoft OIDC sign-in (login.microsoftonline.com)
    provider: azure-ad
    says: ships the Microsoft OIDC sign-in (login.microsoftonline.com) SDK or integration code
    source: https://github.com/gramps-project/gramps-web-api/blob/master/gramps_webapi/auth/oidc.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: Nominatim place search (nominatim.openstreetmap.org)
    provider: nominatim
    says: ships the Nominatim place search (nominatim.openstreetmap.org) SDK or integration code
    source: https://github.com/gramps-project/gramps-web/blob/main/src/components/GrampsjsMapSearchbox.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI-compatible LLM via pydantic-ai[openai] (LLM_BASE_URL)
    provider: openai
    says: ships the OpenAI-compatible LLM via pydantic-ai[openai] (LLM_BASE_URL) SDK or integration code
    source: https://github.com/gramps-project/gramps-web-api/blob/master/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: OpenFreeMap vector styles (tiles.openfreemap.org)
    provider: openfreemap
    says: ships the OpenFreeMap vector styles (tiles.openfreemap.org) SDK or integration code
    source: https://github.com/gramps-project/gramps-web/blob/main/src/components/GrampsjsMap.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: domain
    name: OpenHistoricalMap time-aware basemap style
    provider: openhistoricalmap
    says: ships the OpenHistoricalMap time-aware basemap style SDK or integration code
    source: https://github.com/gramps-project/gramps-web/blob/main/src/components/GrampsjsMap.js
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
    name: Redis as Celery broker (celery[redis])
    provider: redis
    says: ships the Redis as Celery broker (celery[redis]) SDK or integration code
    source: https://github.com/gramps-project/gramps-web-api/blob/master/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: S3 media storage (boto3, api/s3.py)
    provider: amazon-s3
    says: ships the S3 media storage (boto3, api/s3.py) SDK or integration code
    source: https://github.com/gramps-project/gramps-web-api/blob/master/pyproject.toml
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
    name: Sentry error monitoring (sentry-sdk[flask])
    provider: sentry-system
    says: ships the Sentry error monitoring (sentry-sdk[flask]) SDK or integration code
    source: https://github.com/gramps-project/gramps-web-api/blob/master/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230
      key: AE-230
      name: Data & Reference Information Services
      url: /capabilities/data-reference-information-services/
      via_parent: null
    credit: null
    layer: domain
    name: Wikidata SPARQL buildings layer (query.wikidata.org)
    provider: wikidata
    says: ships the Wikidata SPARQL buildings layer (query.wikidata.org) SDK or integration code
    source: https://github.com/gramps-project/gramps-web/blob/main/src/wikidata.ts
    tier: observed
  kind: self-hosted
  name: Gramps Web
  page: /applications/genealogy/gramps-web/
  slug: gramps-web
  url: https://github.com/gramps-project/gramps-web
- anchor: webtrees
  counts:
    declared: 0
    observed: 13
  evidence:
  - route: dependency manifest
    url: https://github.com/fisharebest/webtrees/blob/main/composer.json
  - route: source code
    url: https://github.com/fisharebest/webtrees/tree/main/app/Module
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3770.30
      key: content-performance-analytics
      name: Content Performance Analytics
      url: /capabilities/content-performance-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Bing map links + Bing Webmaster Tools verification
    provider: microsoft-bing
    says: ships the Bing map links + Bing Webmaster Tools verification SDK or integration code
    source: https://github.com/fisharebest/webtrees/blob/main/app/Module/BingWebmasterToolsModule.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: Esri ArcGIS Online tiles (server.arcgisonline.com)
    provider: esri
    says: ships the Esri ArcGIS Online tiles (server.arcgisonline.com) SDK or integration code
    source: https://github.com/fisharebest/webtrees/blob/main/app/Module/EsriMaps.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: domain
    name: GeoNames place autocomplete + geolocation (secure.geonames.org)
    provider: geonames
    says: ships the GeoNames place autocomplete + geolocation (secure.geonames.org) SDK or integration code
    source: https://github.com/fisharebest/webtrees/blob/main/app/Module/GeonamesAutocomplete.php
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
    name: Google Analytics module
    provider: google-analytics
    says: ships the Google Analytics module SDK or integration code
    source: https://github.com/fisharebest/webtrees/blob/main/app/Module/GoogleAnalyticsModule.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: Google Maps tiles + map links
    provider: google-maps
    says: ships the Google Maps tiles + map links SDK or integration code
    source: https://github.com/fisharebest/webtrees/blob/main/app/Module/GoogleMaps.php
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3770.30
      key: content-performance-analytics
      name: Content Performance Analytics
      url: /capabilities/content-performance-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Google Search Console verification module
    provider: google-search-console
    says: ships the Google Search Console verification module SDK or integration code
    source: https://github.com/fisharebest/webtrees/blob/main/app/Module/GoogleSearchConsole.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: HERE map tiles (maps.hereapi.com)
    provider: here
    says: ships the HERE map tiles (maps.hereapi.com) SDK or integration code
    source: https://github.com/fisharebest/webtrees/blob/main/app/Module/HereMaps.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: Mapbox styles/tiles (api.mapbox.com)
    provider: mapbox
    says: ships the Mapbox styles/tiles (api.mapbox.com) SDK or integration code
    source: https://github.com/fisharebest/webtrees/blob/main/app/Module/MapBox.php
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
    name: Matomo analytics module
    provider: matomo
    says: ships the Matomo analytics module SDK or integration code
    source: https://github.com/fisharebest/webtrees/blob/main/app/Module/MatomoAnalyticsModule.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: Nominatim geolocation
    provider: nominatim
    says: ships the Nominatim geolocation SDK or integration code
    source: https://github.com/fisharebest/webtrees/blob/main/app/Module/MapGeoLocationNominatim.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: openrouteservice geocoding
    provider: openrouteservice
    says: ships the openrouteservice geocoding SDK or integration code
    source: https://github.com/fisharebest/webtrees/blob/main/app/Module/MapGeoLocationOpenRouteService.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: OpenStreetMap tiles
    provider: openstreetmap
    says: ships the OpenStreetMap tiles SDK or integration code
    source: https://github.com/fisharebest/webtrees/blob/main/app/Module/OpenStreetMap.php
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
    name: StatCounter analytics module
    provider: statcounter
    says: ships the StatCounter analytics module SDK or integration code
    source: https://github.com/fisharebest/webtrees/blob/main/app/Module/StatcounterModule.php
    tier: observed
  kind: self-hosted
  name: webtrees
  page: /applications/genealogy/webtrees/
  slug: webtrees
  url: https://github.com/fisharebest/webtrees
- anchor: rootsmagic
  counts:
    declared: 4
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.rootsmagic.com/rootsmagic
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-230.110
      key: AE-230.110
      name: Genealogy Records & Family Trees
      url: /capabilities/genealogy-records-family-trees/
      via_parent: null
    credit: null
    layer: domain
    name: Ancestry TreeShare download + WebHints
    provider: ancestry
    says: lists Ancestry TreeShare download + WebHints as an integration
    source: https://www.rootsmagic.com/rootsmagic
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.110
      key: AE-230.110
      name: Genealogy Records & Family Trees
      url: /capabilities/genealogy-records-family-trees/
      via_parent: null
    credit: null
    layer: domain
    name: FamilySearch Family Tree download + WebHints
    provider: familysearch
    says: lists FamilySearch Family Tree download + WebHints as an integration
    source: https://www.rootsmagic.com/rootsmagic
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.110
      key: AE-230.110
      name: Genealogy Records & Family Trees
      url: /capabilities/genealogy-records-family-trees/
      via_parent: null
    credit: null
    layer: domain
    name: Findmypast WebHints
    provider: findmypast
    says: lists Findmypast WebHints as an integration
    source: https://www.rootsmagic.com/rootsmagic
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.110
      key: AE-230.110
      name: Genealogy Records & Family Trees
      url: /capabilities/genealogy-records-family-trees/
      via_parent: null
    credit: null
    layer: domain
    name: MyHeritage WebHints
    provider: myheritage
    says: lists MyHeritage WebHints as an integration
    source: https://www.rootsmagic.com/rootsmagic
    tier: declared
  kind: commercial
  name: RootsMagic
  page: /applications/genealogy/rootsmagic/
  slug: rootsmagic
  url: https://www.rootsmagic.com/
- anchor: family-tree-maker
  counts:
    declared: 2
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.mackiev.com/ftm/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-230.110
      key: AE-230.110
      name: Genealogy Records & Family Trees
      url: /capabilities/genealogy-records-family-trees/
      via_parent: null
    credit: null
    layer: domain
    name: Ancestry tree sync + hints
    provider: ancestry
    says: lists Ancestry tree sync + hints as an integration
    source: https://www.mackiev.com/ftm/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.110
      key: AE-230.110
      name: Genealogy Records & Family Trees
      url: /capabilities/genealogy-records-family-trees/
      via_parent: null
    credit: null
    layer: domain
    name: FamilySearch hints
    provider: familysearch
    says: lists FamilySearch hints as an integration
    source: https://www.mackiev.com/ftm/
    tier: declared
  kind: commercial
  name: Family Tree Maker
  page: /applications/genealogy/family-tree-maker/
  slug: family-tree-maker
  url: https://www.mackiev.com/ftm/
- anchor: ancestry
  counts:
    declared: 3
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.ancestry.android.apps.ancestry/latest/
  - route: documentation
    url: https://www.ancestry.com/c/legal/privacystatement
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ancestry.android.apps.ancestry/latest/
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
    name: Google CrashLytics
    provider: firebase
    says: ships the Google CrashLytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ancestry.android.apps.ancestry/latest/
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
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ancestry.android.apps.ancestry/latest/
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
    name: New Relic
    provider: new-relic
    says: ships the New Relic SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ancestry.android.apps.ancestry/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Salesforce Marketing Cloud
    provider: salesforce-marketing-cloud
    says: ships the Salesforce Marketing Cloud SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ancestry.android.apps.ancestry/latest/
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
    name: Facebook sign-in
    provider: facebook
    says: lists Facebook sign-in as an integration
    source: https://www.ancestry.com/c/legal/privacystatement
    tier: declared
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
    says: lists Google sign-in as an integration
    source: https://www.ancestry.com/c/legal/privacystatement
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Sign in with Apple
    provider: apple
    says: lists Sign in with Apple as an integration
    source: https://www.ancestry.com/c/legal/privacystatement
    tier: declared
  kind: commercial
  name: Ancestry
  page: /applications/genealogy/ancestry/
  slug: ancestry
  url: https://www.ancestry.com/
- anchor: familysearch
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/org.familysearch.mobile.memories/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Adobe Experience Cloud
    provider: adobe-experience-cloud
    says: ships the Adobe Experience Cloud SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/org.familysearch.mobile.memories/latest/
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
    name: Google CrashLytics
    provider: firebase
    says: ships the Google CrashLytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/org.familysearch.mobile.memories/latest/
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
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/org.familysearch.mobile.memories/latest/
    tier: observed
  kind: commercial
  name: FamilySearch
  page: /applications/genealogy/familysearch/
  slug: familysearch
  url: https://www.familysearch.org/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: genealogy
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Reference
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Lifestyle
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Books & Reference
  store: google-play
  url: https://play.google.com/store/apps/category/BOOKS_AND_REFERENCE
- category: Genealogy
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#genealogy
name: Genealogy & Family History
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-230.110
    key: AE-230.110
    name: Genealogy Records & Family Trees
    url: /capabilities/genealogy-records-family-trees/
    via_parent: null
  fit: exact
  layer: domain
  why: Desktop tree apps sync with and pull record hints from Ancestry, FamilySearch, MyHeritage and Findmypast; no node fits (see NOTES candidate)
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: common
  why: pedigree and migration maps; OpenHistoricalMap adds a time-aware layer
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: common
  why: standardising and locating historical place names
- capability:
    attribution: API Evangelist extension
    id: AE-230
    key: AE-230
    name: Data & Reference Information Services
    url: /capabilities/data-reference-information-services/
    via_parent: null
  fit: exact
  layer: domain
  why: Wikidata historical buildings layer
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: OIDC / social sign-in
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: scans, photos and documents
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: task broker for imports, OCR, face detection
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: site analytics for published trees
- capability:
    attribution: Turbo EA
    id: BC-3770.30
    key: content-performance-analytics
    name: Content Performance Analytics
    url: /capabilities/content-performance-analytics/
    via_parent: null
  fit: nearest
  layer: common
  why: search-engine webmaster verification for public trees
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: Gramps Web chat assistant over the tree
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: attribution and deep-link SDKs seen in the Android builds
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: marketing SDKs seen in the Android builds
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-230.110
      key: AE-230.110
      name: Genealogy Records & Family Trees
      url: /capabilities/genealogy-records-family-trees/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.8
      apps:
      - Family Tree Maker
      - RootsMagic
      band: minimal
      in_catalog: true
      kin_score: 9.0
      mcp:
        status: none
      name: FamilySearch Family Tree download + WebHints
      slug: familysearch
      sources:
      - https://www.mackiev.com/ftm/
      - https://www.rootsmagic.com/rootsmagic
      status: profiled
      tags:
      - Data
      - Family History
      - Genealogy
      - Non-Profit
      tier: declared
      url: /providers/familysearch/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Family Tree Maker
      - RootsMagic
      band: minimal
      in_catalog: true
      kin_score: 6.0
      mcp:
        status: none
      name: Ancestry TreeShare download + WebHints
      slug: ancestry
      sources:
      - https://www.mackiev.com/ftm/
      - https://www.rootsmagic.com/rootsmagic
      status: profiled
      tags:
      - Company
      - Data Export
      - Family History
      - Genealogy
      tier: declared
      url: /providers/ancestry/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Gramps Web
      band: emerging
      in_catalog: true
      kin_score: 16.9
      mcp:
        status: none
      name: CompGen DES / domus.genealogy.net historical building map
      slug: compgen
      sources:
      - https://github.com/gramps-project/gramps-web/blob/main/src/wikidata.ts
      status: profiled
      tags:
      - Data
      - Genealogy
      - History
      - Non-Profit
      tier: observed
      url: /providers/compgen/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - RootsMagic
      band: emerging
      in_catalog: true
      kin_score: 13.0
      mcp:
        status: none
      name: MyHeritage WebHints
      slug: myheritage
      sources:
      - https://www.rootsmagic.com/rootsmagic
      status: profiled
      tags:
      - Company
      - Consumer
      - DNA
      - Genealogy
      tier: declared
      url: /providers/myheritage/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - RootsMagic
      band: emerging
      in_catalog: true
      kin_score: 12.6
      mcp:
        status: none
      name: Findmypast WebHints
      slug: findmypast
      sources:
      - https://www.rootsmagic.com/rootsmagic
      status: profiled
      tags:
      - Archives
      - Family Tree
      - Genealogy
      - History
      tier: declared
      url: /providers/findmypast/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: human-only
      agent_readiness: 1.1
      apps:
      - Gramps Web
      band: minimal
      in_catalog: true
      kin_score: 6.4
      mcp:
        status: none
      name: OpenHistoricalMap time-aware basemap style
      slug: openhistoricalmap
      sources:
      - https://github.com/gramps-project/gramps-web/blob/main/src/components/GrampsjsMap.js
      status: profiled
      tags:
      - Historical
      - Mapping
      - Non-Profit
      - Open Source
      tier: observed
      url: /providers/openhistoricalmap/
  - capability:
      attribution: API Evangelist extension
      id: AE-230
      key: AE-230
      name: Data & Reference Information Services
      url: /capabilities/data-reference-information-services/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - Gramps Web
      band: developing
      in_catalog: true
      kin_score: 53.4
      mcp:
        source: https://www.wikidata.org/wiki/Wikidata:MCP
        status: verified
      name: Wikidata SPARQL buildings layer (query.wikidata.org)
      slug: wikidata
      sources:
      - https://github.com/gramps-project/gramps-web/blob/main/src/wikidata.ts
      status: profiled
      tags:
      - Knowledge Graph
      - Linked Data
      - Open Data
      - Semantic Web
      tier: observed
      url: /providers/wikidata/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - webtrees
      band: minimal
      in_catalog: true
      kin_score: 4.3
      mcp:
        status: none
      name: GeoNames place autocomplete + geolocation (secure.geonames.org)
      slug: geonames
      sources:
      - https://github.com/fisharebest/webtrees/blob/main/app/Module/GeonamesAutocomplete.php
      status: profiled
      tags:
      - Geocoding
      - Public APIs
      tier: observed
      url: /providers/geonames/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-native
      agent_readiness: 54.4
      apps:
      - webtrees
      band: exemplar
      in_catalog: true
      kin_score: 79.0
      mcp:
        status: none
      name: HERE map tiles (maps.hereapi.com)
      slug: here
      sources:
      - https://github.com/fisharebest/webtrees/blob/main/app/Module/HereMaps.php
      status: profiled
      tags:
      - Location
      - Mapping
      - Maps
      - Spatial
      tier: observed
      url: /providers/here/
    - agent_band: agent-ready
      agent_readiness: 49.1
      apps:
      - webtrees
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp:
        status: none
      name: Esri ArcGIS Online tiles (server.arcgisonline.com)
      slug: esri
      sources:
      - https://github.com/fisharebest/webtrees/blob/main/app/Module/EsriMaps.php
      status: profiled
      tags:
      - GIS
      - Geographic
      - Geospatial
      - Location
      tier: observed
      url: /providers/esri/
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - webtrees
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps tiles + map links
      slug: google-maps
      sources:
      - https://github.com/fisharebest/webtrees/blob/main/app/Module/GoogleMaps.php
      status: profiled
      tags:
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
    - agent_band: agent-ready
      agent_readiness: 45.2
      apps:
      - webtrees
      band: developing
      in_catalog: true
      kin_score: 50.7
      mcp:
        source: https://github.com/mapbox/mcp-server
        status: verified
      name: Mapbox styles/tiles (api.mapbox.com)
      slug: mapbox
      sources:
      - https://github.com/fisharebest/webtrees/blob/main/app/Module/MapBox.php
      status: profiled
      tags:
      - Geospatial
      - Location
      - Mapping
      - Maps
      tier: observed
      url: /providers/mapbox/
    - agent_band: agent-aware
      agent_readiness: 28.3
      apps:
      - webtrees
      band: developing
      in_catalog: true
      kin_score: 45.5
      mcp:
        status: none
      name: OpenStreetMap tiles
      slug: openstreetmap
      sources:
      - https://github.com/fisharebest/webtrees/blob/main/app/Module/OpenStreetMap.php
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Mapping
      - Open Data
      tier: observed
      url: /providers/openstreetmap/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Gramps Web
      band: emerging
      in_catalog: true
      kin_score: 12.7
      mcp:
        status: none
      name: OpenFreeMap vector styles (tiles.openfreemap.org)
      slug: openfreemap
      sources:
      - https://github.com/gramps-project/gramps-web/blob/main/src/components/GrampsjsMap.js
      status: profiled
      tags:
      - Company
      - GIS
      - Mapping
      - Open Source
      tier: observed
      url: /providers/openfreemap/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Ancestry
      - FamilySearch
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ancestry.android.apps.ancestry/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/org.familysearch.mobile.memories/latest/
      status: profiled
      tags: &id002
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - webtrees
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics module
      slug: google-analytics
      sources:
      - https://github.com/fisharebest/webtrees/blob/main/app/Module/GoogleAnalyticsModule.php
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 41.3
      apps:
      - webtrees
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/matomo-org/plugin-McpServer
        status: verified
      name: Matomo analytics module
      slug: matomo
      sources:
      - https://github.com/fisharebest/webtrees/blob/main/app/Module/MatomoAnalyticsModule.php
      status: profiled
      tags:
      - Analytics
      - Open Source
      - Privacy
      - Web Analytics
      tier: observed
      url: /providers/matomo/
    - agent_band: agent-ready
      agent_readiness: 53.0
      apps:
      - FamilySearch
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        source: https://github.com/adobe/cq-quickstart-mcp-server
        status: verified
      name: Adobe Experience Cloud
      slug: adobe-experience-cloud
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/org.familysearch.mobile.memories/latest/
      status: profiled
      tags:
      - Analytics
      - Customer Experience
      - Digital Marketing
      - Personalization
      tier: observed
      url: /providers/adobe-experience-cloud/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - webtrees
      band: emerging
      in_catalog: true
      kin_score: 19.2
      mcp:
        source: https://statcounter.com/api/docs/mcp
        status: verified
      name: StatCounter analytics module
      slug: statcounter
      sources:
      - https://github.com/fisharebest/webtrees/blob/main/app/Module/StatcounterModule.php
      status: profiled
      tags:
      - Analytics
      - Company
      - Real-Time
      - Web
      tier: observed
      url: /providers/statcounter/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Ancestry
      - Gramps Web
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google OIDC sign-in (accounts.google.com)
      slug: google-identity-platform
      sources:
      - https://github.com/gramps-project/gramps-web-api/blob/master/gramps_webapi/auth/oidc.py
      - https://www.ancestry.com/c/legal/privacystatement
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-ready
      agent_readiness: 59.8
      apps:
      - Gramps Web
      band: exemplar
      in_catalog: true
      kin_score: 85.1
      mcp:
        source: https://learn.microsoft.com/en-us/graph/mcp-server/overview
        status: verified
      name: Microsoft OIDC sign-in (login.microsoftonline.com)
      slug: azure-ad
      sources:
      - https://github.com/gramps-project/gramps-web-api/blob/master/gramps_webapi/auth/oidc.py
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity
      - OAuth
      tier: observed
      url: /providers/azure-ad/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Ancestry
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Sign in with Apple
      slug: apple
      sources:
      - https://www.ancestry.com/c/legal/privacystatement
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Ancestry
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook sign-in
      slug: facebook
      sources:
      - https://www.ancestry.com/c/legal/privacystatement
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: declared
      url: /providers/facebook/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Ancestry
      - FamilySearch
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id001
      name: Google CrashLytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ancestry.android.apps.ancestry/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/org.familysearch.mobile.memories/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Gramps Web
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry error monitoring (sentry-sdk[flask])
      slug: sentry-system
      sources:
      - https://github.com/gramps-project/gramps-web-api/blob/master/pyproject.toml
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Ancestry
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ancestry.android.apps.ancestry/latest/
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - Gramps Web
      - webtrees
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Nominatim place search (nominatim.openstreetmap.org)
      slug: nominatim
      sources:
      - https://github.com/fisharebest/webtrees/blob/main/app/Module/MapGeoLocationNominatim.php
      - https://github.com/gramps-project/gramps-web/blob/main/src/components/GrampsjsMapSearchbox.js
      status: profiled
      tags:
      - Geocoding
      - Location Services
      - Maps
      - OpenStreetMap
      tier: observed
      url: /providers/nominatim/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - webtrees
      band: thin
      in_catalog: true
      kin_score: 33.0
      mcp:
        status: none
      name: openrouteservice geocoding
      slug: openrouteservice
      sources:
      - https://github.com/fisharebest/webtrees/blob/main/app/Module/MapGeoLocationOpenRouteService.php
      status: profiled
      tags:
      - Directions
      - Geospatial
      - Isochrones
      - Routing
      tier: observed
      url: /providers/openrouteservice/
  - capability:
      attribution: Turbo EA
      id: BC-3770.30
      key: content-performance-analytics
      name: Content Performance Analytics
      url: /capabilities/content-performance-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.2
      apps:
      - webtrees
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Bing map links + Bing Webmaster Tools verification
      slug: microsoft
      sources:
      - https://github.com/fisharebest/webtrees/blob/main/app/Module/BingWebmasterToolsModule.php
      status: profiled
      tags:
      - Cloud
      - Fortune 100
      - Microsoft
      - Software
      tier: observed
      url: /providers/microsoft/
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - webtrees
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        status: none
      name: Google Search Console verification module
      slug: google-search-console
      sources:
      - https://github.com/fisharebest/webtrees/blob/main/app/Module/GoogleSearchConsole.php
      status: profiled
      tags:
      - Analytics
      - Google
      - Indexing
      - Search
      tier: observed
      url: /providers/google-search-console/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - Ancestry
      band: exemplar
      in_catalog: true
      kin_score: 77.6
      mcp:
        status: none
      name: Salesforce Marketing Cloud
      slug: salesforce-marketing-cloud
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ancestry.android.apps.ancestry/latest/
      status: profiled
      tags:
      - Automation
      - Content Management
      - Customer Journey
      - Digital Marketing
      tier: observed
      url: /providers/salesforce-marketing-cloud/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.5
      apps:
      - Gramps Web
      band: developing
      in_catalog: true
      kin_score: 46.5
      mcp:
        source: https://github.com/redis/mcp-redis
        status: verified
      name: Redis as Celery broker (celery[redis])
      slug: redis
      sources:
      - https://github.com/gramps-project/gramps-web-api/blob/master/pyproject.toml
      status: profiled
      tags:
      - Cache
      - Database
      - In-Memory
      - Key-Value Store
      tier: observed
      url: /providers/redis/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Ancestry
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ancestry.android.apps.ancestry/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Gramps Web
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: S3 media storage (boto3, api/s3.py)
      slug: amazon-s3
      sources:
      - https://github.com/gramps-project/gramps-web-api/blob/master/pyproject.toml
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Gramps Web
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI-compatible LLM via pydantic-ai[openai] (LLM_BASE_URL)
      slug: openai
      sources:
      - https://github.com/gramps-project/gramps-web-api/blob/master/pyproject.toml
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
  layer: agent
summary:
  coverage_pct: 100.0
  declared_only: 6
  distinct_providers: 34
  in_catalog: 34
  mcp:
    documented: 0
    none: 19
    unchecked: 0
    verified: 15
  mcp_verified: 15
  mean_kin_score: 49.5
  observed: 28
  queued: 0
  reference_apps: 6
title: 'Genealogy & Family History: application blueprint'
---
