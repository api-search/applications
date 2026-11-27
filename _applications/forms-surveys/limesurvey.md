---
app: LimeSurvey
app_slug: limesurvey
app_url: https://github.com/LimeSurvey/LimeSurvey
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: common
  name: Machine Translation
  providers:
  - google-translate
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Gmail SMTP (OAuth)
  - Microsoft 365 / Exchange Online SMTP
  url: /capabilities/email/
  via_parent: Email
category:
  id: forms-surveys
  name: Forms & Surveys
  url: /applications/forms-surveys/
counts:
  declared: 0
  observed: 3
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/LimeSurvey/LimeSurvey/master/composer.json
- route: source code
  url: https://github.com/LimeSurvey/LimeSurvey/tree/master/application/core/plugins
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.2
    band: exemplar
    in_catalog: true
    kin_score: 66.8
    mcp: &id001
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id002
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: common
  name: Gmail SMTP (OAuth)
  provider: google-gmail
  says: ships the Gmail SMTP (OAuth) SDK or integration code
  source: https://github.com/LimeSurvey/LimeSurvey/tree/master/application/core/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.9
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id003
      status: none
    slug: google-translate
    status: profiled
    tags: &id004
    - Google Cloud
    - Internationalization
    - Language Detection
    - Localization
    url: /providers/google-translate/
  layer: common
  name: google-translate
  provider: google-translate
  says: ships the google-translate SDK or integration code
  source: https://raw.githubusercontent.com/LimeSurvey/LimeSurvey/master/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.0
    band: strong
    in_catalog: true
    kin_score: 64.9
    mcp: &id005
      status: none
    slug: microsoft-exchange
    status: profiled
    tags: &id006
    - Calendar
    - Collaboration
    - Contacts
    - Email
    url: /providers/microsoft-exchange/
  layer: common
  name: Microsoft 365 / Exchange Online SMTP
  provider: microsoft-exchange
  says: ships the Microsoft 365 / Exchange Online SMTP SDK or integration code
  source: https://github.com/LimeSurvey/LimeSurvey/tree/master/application/core/plugins
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/forms-surveys/limesurvey/
providers:
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id001
  name: Gmail SMTP (OAuth)
  slug: google-gmail
  status: profiled
  tags: *id002
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 33.9
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id003
  name: google-translate
  slug: google-translate
  status: profiled
  tags: *id004
  url: /providers/google-translate/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: strong
  in_catalog: true
  kin_score: 64.9
  mcp: *id005
  name: Microsoft 365 / Exchange Online SMTP
  slug: microsoft-exchange
  status: profiled
  tags: *id006
  url: /providers/microsoft-exchange/
siblings:
- name: Formbricks
  rows: 16
  url: /applications/forms-surveys/formbricks/
- name: HeyForm
  rows: 6
  url: /applications/forms-surveys/heyform/
- name: Jotform
  rows: 32
  url: /applications/forms-surveys/jotform/
- name: SurveyMonkey
  rows: 9
  url: /applications/forms-surveys/surveymonkey/
- name: Typebot
  rows: 23
  url: /applications/forms-surveys/typebot/
- name: Typeform
  rows: 18
  url: /applications/forms-surveys/typeform/
sitemap: true
title: 'LimeSurvey: Forms & Surveys reference app'
---
