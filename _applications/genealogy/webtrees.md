---
app: webtrees
app_slug: webtrees
app_url: https://github.com/fisharebest/webtrees
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: domain
  name: Forward Geocoding
  providers:
  - GeoNames place autocomplete + geolocation (secure.geonames.org)
  - Nominatim geolocation
  - openrouteservice geocoding
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: common
  name: Base Map Tiles
  providers:
  - Esri ArcGIS Online tiles (server.arcgisonline.com)
  - Google Maps tiles + map links
  - HERE map tiles (maps.hereapi.com)
  - Mapbox styles/tiles (api.mapbox.com)
  - OpenStreetMap tiles
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: Turbo EA
  id: BC-3770.30
  key: content-performance-analytics
  layer: common
  name: Content Performance Analytics
  providers:
  - Bing map links + Bing Webmaster Tools verification
  - Google Search Console verification module
  url: /capabilities/content-performance-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics module
  - Matomo analytics module
  - StatCounter analytics module
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: genealogy
  name: Genealogy & Family History
  url: /applications/genealogy/
counts:
  declared: 0
  observed: 13
credits: []
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.0
    mcp: &id001
      status: none
    slug: microsoft-bing
    status: profiled
    tags: &id002
    - Image
    - Search
    - Video
    - Web Search
    url: /providers/microsoft-bing/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.1
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id003
      status: none
    slug: esri
    status: profiled
    tags: &id004
    - GIS
    - Geographic
    - Geospatial
    - Location
    url: /providers/esri/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.2
    mcp: &id005
      status: none
    slug: geonames
    status: profiled
    tags: &id006
    - Geocoding
    - Public APIs
    url: /providers/geonames/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id007
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id008
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id009
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id010
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 70.4
    mcp: &id011
      status: none
    slug: google-search-console
    status: profiled
    tags: &id012
    - Analytics
    - Google
    - Indexing
    - Search
    url: /providers/google-search-console/
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
  facts:
    agent_band: agent-native
    agent_readiness: 55.5
    band: exemplar
    in_catalog: true
    kin_score: 77.6
    mcp: &id013
      status: none
    slug: here
    status: profiled
    tags: &id014
    - Location
    - Mapping
    - Maps
    - Spatial
    url: /providers/here/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 45.8
    band: developing
    in_catalog: true
    kin_score: 49.3
    mcp: &id015
      source: https://github.com/mapbox/mcp-server
      status: verified
    slug: mapbox
    status: profiled
    tags: &id016
    - Geospatial
    - Location
    - Mapping
    - Maps
    url: /providers/mapbox/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.4
    band: exemplar
    in_catalog: true
    kin_score: 72.2
    mcp: &id017
      source: https://github.com/matomo-org/plugin-McpServer
      status: verified
    slug: matomo
    status: profiled
    tags: &id018
    - Analytics
    - Open Source
    - Privacy
    - Web Analytics
    url: /providers/matomo/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.9
    band: developing
    in_catalog: true
    kin_score: 42.4
    mcp: &id019
      status: none
    slug: nominatim
    status: profiled
    tags: &id020
    - Geocoding
    - Location Services
    - Maps
    - OpenStreetMap
    url: /providers/nominatim/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 21.3
    band: thin
    in_catalog: true
    kin_score: 34.9
    mcp: &id021
      status: none
    slug: openrouteservice
    status: profiled
    tags: &id022
    - Directions
    - Geospatial
    - Isochrones
    - Routing
    url: /providers/openrouteservice/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.8
    band: developing
    in_catalog: true
    kin_score: 44.4
    mcp: &id023
      status: none
    slug: openstreetmap
    status: profiled
    tags: &id024
    - Geocoding
    - Geospatial
    - Mapping
    - Open Data
    url: /providers/openstreetmap/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.7
    band: emerging
    in_catalog: true
    kin_score: 17.3
    mcp: &id025
      source: https://statcounter.com/api/docs/mcp
      status: verified
    slug: statcounter
    status: profiled
    tags: &id026
    - Analytics
    - Company
    - Real-Time
    - Web
    url: /providers/statcounter/
  layer: common
  name: StatCounter analytics module
  provider: statcounter
  says: ships the StatCounter analytics module SDK or integration code
  source: https://github.com/fisharebest/webtrees/blob/main/app/Module/StatcounterModule.php
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/genealogy/webtrees/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.0
  mcp: *id001
  name: Bing map links + Bing Webmaster Tools verification
  slug: microsoft-bing
  status: profiled
  tags: *id002
  url: /providers/microsoft-bing/
- agent_band: agent-ready
  agent_readiness: 50.1
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id003
  name: Esri ArcGIS Online tiles (server.arcgisonline.com)
  slug: esri
  status: profiled
  tags: *id004
  url: /providers/esri/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.2
  mcp: *id005
  name: GeoNames place autocomplete + geolocation (secure.geonames.org)
  slug: geonames
  status: profiled
  tags: *id006
  url: /providers/geonames/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id007
  name: Google Analytics module
  slug: google-analytics
  status: profiled
  tags: *id008
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id009
  name: Google Maps tiles + map links
  slug: google-maps
  status: profiled
  tags: *id010
  url: /providers/google-maps/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 70.4
  mcp: *id011
  name: Google Search Console verification module
  slug: google-search-console
  status: profiled
  tags: *id012
  url: /providers/google-search-console/
- agent_band: agent-native
  agent_readiness: 55.5
  band: exemplar
  in_catalog: true
  kin_score: 77.6
  mcp: *id013
  name: HERE map tiles (maps.hereapi.com)
  slug: here
  status: profiled
  tags: *id014
  url: /providers/here/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 49.3
  mcp: *id015
  name: Mapbox styles/tiles (api.mapbox.com)
  slug: mapbox
  status: profiled
  tags: *id016
  url: /providers/mapbox/
- agent_band: agent-ready
  agent_readiness: 37.4
  band: exemplar
  in_catalog: true
  kin_score: 72.2
  mcp: *id017
  name: Matomo analytics module
  slug: matomo
  status: profiled
  tags: *id018
  url: /providers/matomo/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: developing
  in_catalog: true
  kin_score: 42.4
  mcp: *id019
  name: Nominatim geolocation
  slug: nominatim
  status: profiled
  tags: *id020
  url: /providers/nominatim/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: thin
  in_catalog: true
  kin_score: 34.9
  mcp: *id021
  name: openrouteservice geocoding
  slug: openrouteservice
  status: profiled
  tags: *id022
  url: /providers/openrouteservice/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: developing
  in_catalog: true
  kin_score: 44.4
  mcp: *id023
  name: OpenStreetMap tiles
  slug: openstreetmap
  status: profiled
  tags: *id024
  url: /providers/openstreetmap/
- agent_band: agent-aware
  agent_readiness: 18.7
  band: emerging
  in_catalog: true
  kin_score: 17.3
  mcp: *id025
  name: StatCounter analytics module
  slug: statcounter
  status: profiled
  tags: *id026
  url: /providers/statcounter/
siblings:
- name: Ancestry
  rows: 8
  url: /applications/genealogy/ancestry/
- name: Family Tree Maker
  rows: 2
  url: /applications/genealogy/family-tree-maker/
- name: FamilySearch
  rows: 3
  url: /applications/genealogy/familysearch/
- name: Gramps Web
  rows: 11
  url: /applications/genealogy/gramps-web/
- name: RootsMagic
  rows: 4
  url: /applications/genealogy/rootsmagic/
sitemap: true
title: 'webtrees: Genealogy & Family History reference app'
---
