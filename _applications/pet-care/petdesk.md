---
app: PetDesk
app_slug: petdesk
app_url: https://petdesk.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.80.10
  key: AE-130.80.10
  layer: domain
  name: Veterinary Practice Management Systems
  providers:
  - Covetrus (Pulse, AVImark, ImproMed)
  - DaySmart Vet
  - ezyVet
  - Hippo Manager
  - IDEXX (Cornerstone, Neo)
  - Provet Cloud
  - Rhapsody (veterinary PIMS)
  - Shepherd Veterinary Software
  - Vetspire
  url: /capabilities/pet-health-care/
  via_parent: Pet Health & Care
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
category:
  id: pet-care
  name: Pet Care
  url: /applications/pet-care/
counts:
  declared: 10
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://petdesk.com/compatible-pims
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-130.80.10
    key: AE-130.80.10
    name: Veterinary Practice Management Systems
    url: /capabilities/pet-health-care/
    via_parent: Pet Health & Care
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.4
    band: minimal
    in_catalog: true
    kin_score: 9.6
    mcp: &id001
      status: none
    slug: covetrus
    status: profiled
    tags: &id002
    - Company
    - Pharmacy
    - Software
    - Veterinary
    url: /providers/covetrus/
  layer: domain
  name: Covetrus (Pulse, AVImark, ImproMed)
  provider: covetrus
  says: lists Covetrus (Pulse, AVImark, ImproMed) as an integration
  source: https://petdesk.com/compatible-pims
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.80.10
    key: AE-130.80.10
    name: Veterinary Practice Management Systems
    url: /capabilities/pet-health-care/
    via_parent: Pet Health & Care
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.3
    band: emerging
    in_catalog: true
    kin_score: 19.9
    mcp: &id003
      status: none
    slug: daysmart-vet
    status: profiled
    tags: &id004
    - Cloud
    - Company
    - Software
    - Veterinary
    url: /providers/daysmart-vet/
  layer: domain
  name: DaySmart Vet
  provider: daysmart-vet
  says: lists DaySmart Vet as an integration
  source: https://petdesk.com/compatible-pims
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.80.10
    key: AE-130.80.10
    name: Veterinary Practice Management Systems
    url: /capabilities/pet-health-care/
    via_parent: Pet Health & Care
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.1
    band: thin
    in_catalog: true
    kin_score: 34.9
    mcp: &id005
      status: unknown
    slug: ezyvet
    status: profiled
    tags: &id006
    - Healthcare
    - PIMS
    - Practice Management
    - Veterinary
    url: /providers/ezyvet/
  layer: domain
  name: ezyVet
  provider: ezyvet
  says: lists ezyVet as an integration
  source: https://petdesk.com/compatible-pims
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id007
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id008
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://petdesk.com/compatible-pims
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.80.10
    key: AE-130.80.10
    name: Veterinary Practice Management Systems
    url: /capabilities/pet-health-care/
    via_parent: Pet Health & Care
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id009
      status: unchecked
    slug: hippo-manager
    status: queued for profiling
    tags: &id010 []
    url: null
  layer: domain
  name: Hippo Manager
  provider: hippo-manager
  says: lists Hippo Manager as an integration
  source: https://petdesk.com/compatible-pims
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.80.10
    key: AE-130.80.10
    name: Veterinary Practice Management Systems
    url: /capabilities/pet-health-care/
    via_parent: Pet Health & Care
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: idexx
    status: queued for profiling
    tags: &id012 []
    url: null
  layer: domain
  name: IDEXX (Cornerstone, Neo)
  provider: idexx
  says: lists IDEXX (Cornerstone, Neo) as an integration
  source: https://petdesk.com/compatible-pims
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.80.10
    key: AE-130.80.10
    name: Veterinary Practice Management Systems
    url: /capabilities/pet-health-care/
    via_parent: Pet Health & Care
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.9
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id013
      source: https://www.provet.com/mcp-skills-library
      status: documented
    slug: provet-cloud
    status: profiled
    tags: &id014
    - Healthcare
    - PIMS
    - Practice Management
    - Veterinary
    url: /providers/provet-cloud/
  layer: domain
  name: Provet Cloud
  provider: provet-cloud
  says: lists Provet Cloud as an integration
  source: https://petdesk.com/compatible-pims
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.80.10
    key: AE-130.80.10
    name: Veterinary Practice Management Systems
    url: /capabilities/pet-health-care/
    via_parent: Pet Health & Care
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id015
      status: unchecked
    slug: rhapsody-vet
    status: queued for profiling
    tags: &id016 []
    url: null
  layer: domain
  name: Rhapsody (veterinary PIMS)
  provider: rhapsody-vet
  says: lists Rhapsody (veterinary PIMS) as an integration
  source: https://petdesk.com/compatible-pims
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.80.10
    key: AE-130.80.10
    name: Veterinary Practice Management Systems
    url: /capabilities/pet-health-care/
    via_parent: Pet Health & Care
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.9
    band: developing
    in_catalog: true
    kin_score: 39.8
    mcp: &id017
      status: unknown
    slug: shepherd-vet
    status: profiled
    tags: &id018
    - Cloud
    - Practice Management
    - Software
    - Veterinary
    url: /providers/shepherd-vet/
  layer: domain
  name: Shepherd Veterinary Software
  provider: shepherd-vet
  says: lists Shepherd Veterinary Software as an integration
  source: https://petdesk.com/compatible-pims
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.80.10
    key: AE-130.80.10
    name: Veterinary Practice Management Systems
    url: /capabilities/pet-health-care/
    via_parent: Pet Health & Care
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 13.6
    band: emerging
    in_catalog: true
    kin_score: 22.2
    mcp: &id019
      status: none
    slug: vetspire
    status: profiled
    tags: &id020
    - Healthcare
    - PIMS
    - Practice Management
    - Veterinary
    url: /providers/vetspire/
  layer: domain
  name: Vetspire
  provider: vetspire
  says: lists Vetspire as an integration
  source: https://petdesk.com/compatible-pims
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/pet-care/petdesk/
providers:
- agent_band: agent-aware
  agent_readiness: 14.4
  band: minimal
  in_catalog: true
  kin_score: 9.6
  mcp: *id001
  name: Covetrus (Pulse, AVImark, ImproMed)
  slug: covetrus
  status: profiled
  tags: *id002
  url: /providers/covetrus/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: emerging
  in_catalog: true
  kin_score: 19.9
  mcp: *id003
  name: DaySmart Vet
  slug: daysmart-vet
  status: profiled
  tags: *id004
  url: /providers/daysmart-vet/
- agent_band: agent-aware
  agent_readiness: 23.1
  band: thin
  in_catalog: true
  kin_score: 34.9
  mcp: *id005
  name: ezyVet
  slug: ezyvet
  status: profiled
  tags: *id006
  url: /providers/ezyvet/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id007
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id008
  url: /providers/google-calendar/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id009
  name: Hippo Manager
  slug: hippo-manager
  status: queued for profiling
  tags: *id010
  url: null
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: IDEXX (Cornerstone, Neo)
  slug: idexx
  status: queued for profiling
  tags: *id012
  url: null
- agent_band: agent-ready
  agent_readiness: 32.9
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id013
  name: Provet Cloud
  slug: provet-cloud
  status: profiled
  tags: *id014
  url: /providers/provet-cloud/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id015
  name: Rhapsody (veterinary PIMS)
  slug: rhapsody-vet
  status: queued for profiling
  tags: *id016
  url: null
- agent_band: agent-ready
  agent_readiness: 29.9
  band: developing
  in_catalog: true
  kin_score: 39.8
  mcp: *id017
  name: Shepherd Veterinary Software
  slug: shepherd-vet
  status: profiled
  tags: *id018
  url: /providers/shepherd-vet/
- agent_band: agent-aware
  agent_readiness: 13.6
  band: emerging
  in_catalog: true
  kin_score: 22.2
  mcp: *id019
  name: Vetspire
  slug: vetspire
  status: profiled
  tags: *id020
  url: /providers/vetspire/
siblings:
- name: Chewy
  rows: 4
  url: /applications/pet-care/chewy/
- name: Fi Smart Collar
  rows: 4
  url: /applications/pet-care/fi-smart-collar/
- name: oh-my-petcare
  rows: 2
  url: /applications/pet-care/oh-my-petcare/
- name: PawSome AI
  rows: 2
  url: /applications/pet-care/pawsome-ai/
- name: PETLIBRO
  rows: 10
  url: /applications/pet-care/petlibro/
- name: Rover
  rows: 10
  url: /applications/pet-care/rover/
- name: Tractive
  rows: 7
  url: /applications/pet-care/tractive/
sitemap: true
title: 'PetDesk: Pet Care reference app'
---
