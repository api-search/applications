---
app: Excalidraw
app_slug: excalidraw
app_url: https://github.com/excalidraw/excalidraw
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Firebase
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: video-editing-creation
  name: Video & Photo Editing / Creator Tools
  url: /applications/video-editing-creation/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/excalidraw/excalidraw/master/excalidraw-app/package.json
- route: source code
  url: https://raw.githubusercontent.com/excalidraw/excalidraw/master/.env.production
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id001
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id002
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://raw.githubusercontent.com/excalidraw/excalidraw/master/excalidraw-app/package.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id003
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id004
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://raw.githubusercontent.com/excalidraw/excalidraw/master/excalidraw-app/package.json
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/video-editing-creation/excalidraw/
providers:
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id001
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id002
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id003
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id004
  url: /providers/sentry-system/
siblings:
- name: Canva
  rows: 6
  url: /applications/video-editing-creation/canva/
- name: CapCut
  rows: 11
  url: /applications/video-editing-creation/capcut/
- name: Descript
  rows: 30
  url: /applications/video-editing-creation/descript/
- name: Kdenlive
  rows: 4
  url: /applications/video-editing-creation/kdenlive/
- name: Penpot
  rows: 3
  url: /applications/video-editing-creation/penpot/
- name: Remotion
  rows: 10
  url: /applications/video-editing-creation/remotion/
sitemap: true
title: 'Excalidraw: Video & Photo Editing / Creator Tools reference app'
---
