---
app: Vagaro
app_slug: vagaro
app_url: https://www.vagaro.com/pro
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-210.80
  key: AE-210.80
  layer: domain
  name: Booking Channel Distribution
  providers:
  - Amazon Alexa+
  url: /capabilities/booking-channel-distribution/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - PNC Bank
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: salon-spa-management
  name: Salon & Spa Management
  url: /applications/salon-spa-management/
counts:
  declared: 2
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.vagaro.com/pro/marketplace
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-210.80
    key: AE-210.80
    name: Booking Channel Distribution
    url: /capabilities/booking-channel-distribution/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: thin
    in_catalog: true
    kin_score: 37.0
    mcp: &id001
      status: unchecked
    slug: amazon-alexa
    status: profiled
    tags: &id002
    - Cloud
    - IoT
    - Smart Home
    - Voice Assistant
    url: /providers/amazon-alexa/
  layer: domain
  name: Amazon Alexa+
  provider: amazon-alexa
  says: lists Amazon Alexa+ as an integration
  source: https://www.vagaro.com/pro/marketplace
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.7
    mcp: &id003
      status: unknown
    slug: pnc
    status: profiled
    tags: &id004
    - Banking
    - Financial Services
    - Treasury Management
    - United States
    url: /providers/pnc/
  layer: common
  name: PNC Bank
  provider: pnc
  says: lists PNC Bank as an integration
  source: https://www.vagaro.com/pro/marketplace
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/salon-spa-management/vagaro/
providers:
- agent_band: agent-aware
  agent_readiness: 25.3
  band: thin
  in_catalog: true
  kin_score: 37.0
  mcp: *id001
  name: Amazon Alexa+
  slug: amazon-alexa
  status: profiled
  tags: *id002
  url: /providers/amazon-alexa/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.7
  mcp: *id003
  name: PNC Bank
  slug: pnc
  status: profiled
  tags: *id004
  url: /providers/pnc/
siblings:
- name: Booksy Biz
  rows: 5
  url: /applications/salon-spa-management/booksy-biz/
- name: Boulevard
  rows: 16
  url: /applications/salon-spa-management/boulevard/
- name: Fresha
  rows: 6
  url: /applications/salon-spa-management/fresha/
- name: Mindbody
  rows: 22
  url: /applications/salon-spa-management/mindbody/
- name: Open Salon
  rows: 2
  url: /applications/salon-spa-management/open-salon/
- name: Salon Booking System
  rows: 44
  url: /applications/salon-spa-management/salon-booking-system/
- name: Square Appointments
  rows: 32
  url: /applications/salon-spa-management/square-appointments/
sitemap: true
title: 'Vagaro: Salon & Spa Management reference app'
---
