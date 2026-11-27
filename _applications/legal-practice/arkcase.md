---
app: ArkCase
app_slug: arkcase
app_url: https://github.com/ArkCase/ArkCase
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-917
  key: AE-917
  layer: domain
  name: Enterprise Content & Document Management
  providers:
  - Alfresco
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: Turbo EA
  id: BC-150.20.40
  key: BC-150.20.40
  layer: domain
  name: Legal Hold and eDiscovery
  providers:
  - ZyLAB
  url: /capabilities/litigation-dispute-management/
  via_parent: Litigation & Dispute Management
- attribution: API Evangelist extension
  id: AE-110.40.20
  key: AE-110.40.20
  layer: domain
  name: OCR & Document AI
  providers:
  - Ephesoft (Tungsten Automation)
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-110.40
  key: AE-110.40
  layer: common
  name: Language & Document Understanding
  providers:
  - Amazon Comprehend Medical
  url: /capabilities/language-document-understanding/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Microsoft Exchange
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: common
  name: Online Forms & Survey Collection
  providers:
  - frevvo
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: API Evangelist extension
  id: AE-110.30.10
  key: AE-110.30.10
  layer: common
  name: Speech-to-Text
  providers:
  - Amazon Transcribe
  url: /capabilities/speech-voice/
  via_parent: Speech & Voice
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: legal-practice
  name: Legal Practice Management
  url: /applications/legal-practice/
counts:
  declared: 0
  observed: 8
credits: []
evidence:
- route: documentation
  url: https://github.com/ArkCase/ArkCase
- route: source code
  url: https://github.com/ArkCase/ArkCase/tree/develop/acm-services
- route: source code
  url: https://github.com/ArkCase/ArkCase/tree/develop/acm-tool-integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-917
    key: AE-917
    name: Enterprise Content & Document Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id001
      status: unchecked
    slug: alfresco
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: domain
  name: Alfresco
  provider: alfresco
  says: ships the Alfresco SDK or integration code
  source: https://github.com/ArkCase/ArkCase
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40
    key: AE-110.40
    name: Language & Document Understanding
    url: /capabilities/language-document-understanding/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.8
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id003
      status: none
    slug: amazon-comprehend
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Machine Learning
    - Natural Language Processing
    - Text Analysis
    url: /providers/amazon-comprehend/
  layer: common
  name: Amazon Comprehend Medical
  provider: amazon-comprehend
  says: ships the Amazon Comprehend Medical SDK or integration code
  source: https://github.com/ArkCase/ArkCase/tree/develop/acm-tool-integrations/acm-comprehend-medical
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/ArkCase/ArkCase/tree/develop/acm-services/acm-service-transcribe
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.10
    key: AE-110.30.10
    name: Speech-to-Text
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.5
    band: exemplar
    in_catalog: true
    kin_score: 75.6
    mcp: &id007
      status: none
    slug: amazon-transcribe
    status: profiled
    tags: &id008
    - Amazon Web Services
    - Audio Processing
    - Machine Learning
    - Speech Recognition
    url: /providers/amazon-transcribe/
  layer: common
  name: Amazon Transcribe
  provider: amazon-transcribe
  says: ships the Amazon Transcribe SDK or integration code
  source: https://github.com/ArkCase/ArkCase/tree/develop/acm-services/acm-service-transcribe
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.20
    key: AE-110.40.20
    name: OCR & Document AI
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id009
      status: unchecked
    slug: ephesoft
    status: queued for profiling
    tags: &id010 []
    url: null
  layer: domain
  name: Ephesoft (Tungsten Automation)
  provider: ephesoft
  says: ships the Ephesoft (Tungsten Automation) SDK or integration code
  source: https://github.com/ArkCase/ArkCase/tree/develop/acm-tool-integrations/acm-ephesoft
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: frevvo
    status: queued for profiling
    tags: &id012 []
    url: null
  layer: common
  name: frevvo
  provider: frevvo
  says: ships the frevvo SDK or integration code
  source: https://github.com/ArkCase/ArkCase/tree/develop/acm-services/acm-service-frevvo-forms
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.0
    band: strong
    in_catalog: true
    kin_score: 64.9
    mcp: &id013
      status: none
    slug: microsoft-exchange
    status: profiled
    tags: &id014
    - Calendar
    - Collaboration
    - Contacts
    - Email
    url: /providers/microsoft-exchange/
  layer: common
  name: Microsoft Exchange
  provider: microsoft-exchange
  says: ships the Microsoft Exchange SDK or integration code
  source: https://github.com/ArkCase/ArkCase/tree/develop/acm-services/acm-service-ms-outlook-integration
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-150.20.40
    key: BC-150.20.40
    name: Legal Hold and eDiscovery
    url: /capabilities/litigation-dispute-management/
    via_parent: Litigation & Dispute Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id015
      status: unchecked
    slug: zylab
    status: queued for profiling
    tags: &id016 []
    url: null
  layer: domain
  name: ZyLAB
  provider: zylab
  says: ships the ZyLAB SDK or integration code
  source: https://github.com/ArkCase/ArkCase/tree/develop/acm-tool-integrations/acm-zylab-integration
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/legal-practice/arkcase/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: Alfresco
  slug: alfresco
  status: queued for profiling
  tags: *id002
  url: null
- agent_band: agent-ready
  agent_readiness: 32.8
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id003
  name: Amazon Comprehend Medical
  slug: amazon-comprehend
  status: profiled
  tags: *id004
  url: /providers/amazon-comprehend/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id005
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id006
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 34.5
  band: exemplar
  in_catalog: true
  kin_score: 75.6
  mcp: *id007
  name: Amazon Transcribe
  slug: amazon-transcribe
  status: profiled
  tags: *id008
  url: /providers/amazon-transcribe/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id009
  name: Ephesoft (Tungsten Automation)
  slug: ephesoft
  status: queued for profiling
  tags: *id010
  url: null
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: frevvo
  slug: frevvo
  status: queued for profiling
  tags: *id012
  url: null
- agent_band: agent-ready
  agent_readiness: 36.0
  band: strong
  in_catalog: true
  kin_score: 64.9
  mcp: *id013
  name: Microsoft Exchange
  slug: microsoft-exchange
  status: profiled
  tags: *id014
  url: /providers/microsoft-exchange/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id015
  name: ZyLAB
  slug: zylab
  status: queued for profiling
  tags: *id016
  url: null
siblings:
- name: Clio
  rows: 0
  url: /applications/legal-practice/clio/
- name: CosmoLex
  rows: 6
  url: /applications/legal-practice/cosmolex/
- name: Filevine
  rows: 5
  url: /applications/legal-practice/filevine/
- name: Lawmatics
  rows: 29
  url: /applications/legal-practice/lawmatics/
- name: MyCase
  rows: 28
  url: /applications/legal-practice/mycase/
- name: PracticePanther
  rows: 19
  url: /applications/legal-practice/practicepanther/
- name: Smokeball
  rows: 4
  url: /applications/legal-practice/smokeball/
sitemap: true
title: 'ArkCase: Legal Practice Management reference app'
---
