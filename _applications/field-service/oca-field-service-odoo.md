---
app: OCA Field Service (Odoo)
app_slug: oca-field-service-odoo
app_url: https://github.com/OCA/field-service
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.20
  key: AE-120.20
  layer: common
  name: Maps & Tiles
  providers:
  - Google Maps
  url: /capabilities/maps-tiles/
  via_parent: null
category:
  id: field-service
  name: Field Service & Dispatch
  url: /applications/field-service/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: source code
  url: https://github.com/OCA/field-service/blob/19.0/fieldservice_google_map/__manifest__.py
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-120.20
    key: AE-120.20
    name: Maps & Tiles
    url: /capabilities/maps-tiles/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id001
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id002
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps
  provider: google-maps
  says: ships the Google Maps SDK or integration code
  source: https://github.com/OCA/field-service/blob/19.0/fieldservice_google_map/__manifest__.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/field-service/oca-field-service-odoo/
providers:
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id001
  name: Google Maps
  slug: google-maps
  status: profiled
  tags: *id002
  url: /providers/google-maps/
siblings:
- name: Housecall Pro
  rows: 26
  url: /applications/field-service/housecall-pro/
- name: Jobber
  rows: 34
  url: /applications/field-service/jobber/
- name: ServiceM8
  rows: 8
  url: /applications/field-service/servicem8/
- name: ServiceTitan
  rows: 3
  url: /applications/field-service/servicetitan/
- name: Tradify
  rows: 4
  url: /applications/field-service/tradify/
- name: Workiz
  rows: 16
  url: /applications/field-service/workiz/
sitemap: true
title: 'OCA Field Service (Odoo): Field Service & Dispatch reference app'
---
