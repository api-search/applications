---
app: pH7Builder
app_slug: ph7builder
app_url: https://ph7builder.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.30.30
  key: AE-170.30.30
  layer: common
  name: Avatars, GIFs & Stickers
  providers:
  - Gravatar
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: common
  name: IP Geolocation
  providers:
  - MaxMind
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: Turbo EA
  id: BC-600.50
  key: it-infrastructure-management
  layer: common
  name: IT Infrastructure Management
  providers:
  - Amazon Web Services
  url: /capabilities/it-infrastructure-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Braintree
  - Skeerel
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Clickatell
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: dating
  name: Dating
  url: /applications/dating/
counts:
  declared: 0
  observed: 8
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
integrations:
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 60.5
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id002
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: Amazon Web Services
  provider: amazon-web-services
  says: ships the Amazon Web Services SDK or integration code
  source: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: developing
    in_catalog: true
    kin_score: 46.2
    mcp: &id003
      status: none
    slug: braintree
    status: profiled
    tags: &id004
    - Mobile
    - Payments
    - Subscription
    - Transaction
    url: /providers/braintree/
  layer: common
  name: Braintree
  provider: braintree
  says: ships the Braintree SDK or integration code
  source: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.7
    band: thin
    in_catalog: true
    kin_score: 33.2
    mcp: &id005
      status: none
    slug: clickatell
    status: profiled
    tags: &id006
    - Company
    - Messaging
    - SMS
    - WhatsApp
    url: /providers/clickatell/
  layer: common
  name: Clickatell
  provider: clickatell
  says: ships the Clickatell SDK or integration code
  source: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.3
    band: developing
    in_catalog: true
    kin_score: 39.8
    mcp: &id007
      source: https://github.com/Automattic/mcp-server-gravatar
      status: verified
    slug: gravatar
    status: profiled
    tags: &id008
    - Avatars
    - Identity
    - Profiles
    - Social
    url: /providers/gravatar/
  layer: common
  name: Gravatar
  provider: gravatar
  says: ships the Gravatar SDK or integration code
  source: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id009
      status: none
    slug: maxmind
    status: profiled
    tags: &id010
    - Fraud Prevention
    - Geolocation
    - IP Intelligence
    - Risk Scoring
    url: /providers/maxmind/
  layer: common
  name: MaxMind
  provider: maxmind
  says: ships the MaxMind SDK or integration code
  source: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: skeerel
    status: queued for profiling
    tags: &id012 []
    url: null
  layer: common
  name: Skeerel
  provider: skeerel
  says: ships the Skeerel SDK or integration code
  source: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id013
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id014
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.4
    band: exemplar
    in_catalog: true
    kin_score: 90.3
    mcp: &id015
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id016
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/composer.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/dating/ph7builder/
providers:
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 60.5
  mcp: *id001
  name: Amazon Web Services
  slug: amazon-web-services
  status: profiled
  tags: *id002
  url: /providers/amazon-web-services/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: developing
  in_catalog: true
  kin_score: 46.2
  mcp: *id003
  name: Braintree
  slug: braintree
  status: profiled
  tags: *id004
  url: /providers/braintree/
- agent_band: agent-aware
  agent_readiness: 26.7
  band: thin
  in_catalog: true
  kin_score: 33.2
  mcp: *id005
  name: Clickatell
  slug: clickatell
  status: profiled
  tags: *id006
  url: /providers/clickatell/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: developing
  in_catalog: true
  kin_score: 39.8
  mcp: *id007
  name: Gravatar
  slug: gravatar
  status: profiled
  tags: *id008
  url: /providers/gravatar/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id009
  name: MaxMind
  slug: maxmind
  status: profiled
  tags: *id010
  url: /providers/maxmind/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: Skeerel
  slug: skeerel
  status: queued for profiling
  tags: *id012
  url: null
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id013
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id014
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 90.3
  mcp: *id015
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id016
  url: /providers/twilio/
siblings:
- name: Alovoa
  rows: 2
  url: /applications/dating/alovoa/
- name: Bumble
  rows: 23
  url: /applications/dating/bumble/
- name: Duolicious
  rows: 9
  url: /applications/dating/duolicious/
- name: Grindr
  rows: 24
  url: /applications/dating/grindr/
- name: Hinge
  rows: 53
  url: /applications/dating/hinge/
- name: Tinder
  rows: 15
  url: /applications/dating/tinder/
sitemap: true
title: 'pH7Builder: Dating reference app'
---
