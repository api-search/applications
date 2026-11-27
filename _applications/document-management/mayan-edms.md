---
app: Mayan EDMS
app_slug: mayan-edms
app_url: https://github.com/mayan-edms/Mayan-EDMS
author: API Evangelist
capabilities:
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
  id: document-management
  name: Document Management & OCR
  url: /applications/document-management/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/mayan-edms/Mayan-EDMS/blob/master/setup.py
integrations:
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
    mcp: &id001
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id002
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/mayan-edms/Mayan-EDMS/blob/master/setup.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/document-management/mayan-edms/
providers:
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id001
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id002
  url: /providers/sentry-system/
siblings:
- name: Adobe Acrobat
  rows: 31
  url: /applications/document-management/adobe-acrobat/
- name: Docspell
  rows: 0
  url: /applications/document-management/docspell/
- name: paperless-gpt
  rows: 14
  url: /applications/document-management/paperless-gpt/
- name: Paperless-ngx
  rows: 8
  url: /applications/document-management/paperless-ngx/
- name: Papra
  rows: 7
  url: /applications/document-management/papra/
- name: Stirling-PDF
  rows: 5
  url: /applications/document-management/stirling-pdf/
sitemap: true
title: 'Mayan EDMS: Document Management & OCR reference app'
---
