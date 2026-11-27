---
app: Gradelink
app_slug: gradelink
app_url: https://www.gradelink.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-944
  key: AE-944
  layer: domain
  name: K-12 Rostering & Roster Sync
  providers:
  - Apple School Manager
  - ClassLink
  - Clever
  - Microsoft 365 (School Data Sync)
  url: /capabilities/k-12-rostering-roster-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-4730.30
  key: learning-environment-management
  layer: domain
  name: Learning Environment Management
  providers:
  - Canvas LMS
  - Google Classroom
  - Schoology
  url: /capabilities/learning-environment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4730
  key: teaching-learning-operations-management
  layer: domain
  name: Teaching & Learning Operations Management
  providers:
  - Renaissance (RDI)
  url: /capabilities/teaching-learning-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - ClassWallet
  - FACTS Tuition Management
  - PaySimple
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: school-admin-sis
  name: School Administration & SIS
  url: /applications/school-admin-sis/
counts:
  declared: 11
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.gradelink.com/integrations/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-944
    key: AE-944
    name: K-12 Rostering & Roster Sync
    url: /capabilities/k-12-rostering-roster-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id001
      status: none
    slug: apple
    status: profiled
    tags: &id002
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Apple School Manager
  provider: apple
  says: lists Apple School Manager as an integration
  source: https://www.gradelink.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4730.30
    key: learning-environment-management
    name: Learning Environment Management
    url: /capabilities/learning-environment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.2
    band: exemplar
    in_catalog: true
    kin_score: 70.0
    mcp: &id003
      source: https://www.instructure.com/resources/infographic/context-king-mcp-explained
      status: documented
    slug: canvas
    status: profiled
    tags: &id004
    - Canvas
    - EdTech
    - Education
    - GraphQL
    url: /providers/canvas/
  layer: domain
  name: Canvas LMS
  provider: canvas
  says: lists Canvas LMS as an integration
  source: https://www.gradelink.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-944
    key: AE-944
    name: K-12 Rostering & Roster Sync
    url: /capabilities/k-12-rostering-roster-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 13.3
    band: emerging
    in_catalog: true
    kin_score: 25.8
    mcp: &id005
      status: unknown
    slug: classlink
    status: profiled
    tags: &id006
    - EdTech
    - Education
    - Identity
    - SSO
    url: /providers/classlink/
  layer: domain
  name: ClassLink
  provider: classlink
  says: lists ClassLink as an integration
  source: https://www.gradelink.com/integrations/
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
    band: emerging
    in_catalog: true
    kin_score: 13.5
    mcp: &id007
      status: unknown
    slug: classwallet
    status: profiled
    tags: &id008
    - Company
    - Digital Wallet
    - Fintech
    - Payments
    url: /providers/classwallet/
  layer: common
  name: ClassWallet
  provider: classwallet
  says: lists ClassWallet as an integration
  source: https://www.gradelink.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-944
    key: AE-944
    name: K-12 Rostering & Roster Sync
    url: /capabilities/k-12-rostering-roster-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.4
    band: developing
    in_catalog: true
    kin_score: 41.2
    mcp: &id009
      status: none
    slug: clever
    status: profiled
    tags: &id010
    - EdTech
    - Education
    - K-12
    - SSO
    url: /providers/clever/
  layer: domain
  name: Clever
  provider: clever
  says: lists Clever as an integration
  source: https://www.gradelink.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 15.7
    mcp: &id011
      status: unchecked
    slug: facts-management
    status: profiled
    tags: &id012
    - Education
    - School Management
    - Software-as-a-Service
    - Tuition
    url: /providers/facts-management/
  layer: common
  name: FACTS Tuition Management
  provider: facts-management
  says: lists FACTS Tuition Management as an integration
  source: https://www.gradelink.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4730.30
    key: learning-environment-management
    name: Learning Environment Management
    url: /capabilities/learning-environment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.8
    band: exemplar
    in_catalog: true
    kin_score: 72.6
    mcp: &id013
      source: https://developers.google.com/workspace/classroom/guides/mcp/configure-mcp-server
      status: verified
    slug: google-classroom
    status: profiled
    tags: &id014
    - Assignments
    - Classroom
    - Courses
    - Education
    url: /providers/google-classroom/
  layer: domain
  name: Google Classroom
  provider: google-classroom
  says: lists Google Classroom as an integration
  source: https://www.gradelink.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-944
    key: AE-944
    name: K-12 Rostering & Roster Sync
    url: /capabilities/k-12-rostering-roster-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id015
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-365
    status: profiled
    tags: &id016
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/microsoft-365/
  layer: domain
  name: Microsoft 365 (School Data Sync)
  provider: microsoft-365
  says: lists Microsoft 365 (School Data Sync) as an integration
  source: https://www.gradelink.com/integrations/
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
    agent_band: agent-ready
    agent_readiness: 35.7
    band: developing
    in_catalog: true
    kin_score: 45.8
    mcp: &id017
      status: unchecked
    slug: paysimple
    status: profiled
    tags: &id018
    - Billing
    - Company
    - Payments
    - Software-as-a-Service
    url: /providers/paysimple/
  layer: common
  name: PaySimple
  provider: paysimple
  says: lists PaySimple as an integration
  source: https://www.gradelink.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4730
    key: teaching-learning-operations-management
    name: Teaching & Learning Operations Management
    url: /capabilities/teaching-learning-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.6
    band: developing
    in_catalog: true
    kin_score: 47.5
    mcp: &id019
      status: none
    slug: renaissance
    status: profiled
    tags: &id020
    - Assessment
    - EdTech
    - Education
    - K-12
    url: /providers/renaissance/
  layer: domain
  name: Renaissance (RDI)
  provider: renaissance
  says: lists Renaissance (RDI) as an integration
  source: https://www.gradelink.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4730.30
    key: learning-environment-management
    name: Learning Environment Management
    url: /capabilities/learning-environment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: emerging
    in_catalog: true
    kin_score: 23.8
    mcp: &id021
      status: unknown
    slug: schoology
    status: profiled
    tags: &id022
    - EdTech
    - K-12
    - LMS
    url: /providers/schoology/
  layer: domain
  name: Schoology
  provider: schoology
  says: lists Schoology as an integration
  source: https://www.gradelink.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/school-admin-sis/gradelink/
providers:
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id001
  name: Apple School Manager
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: exemplar
  in_catalog: true
  kin_score: 70.0
  mcp: *id003
  name: Canvas LMS
  slug: canvas
  status: profiled
  tags: *id004
  url: /providers/canvas/
- agent_band: agent-aware
  agent_readiness: 13.3
  band: emerging
  in_catalog: true
  kin_score: 25.8
  mcp: *id005
  name: ClassLink
  slug: classlink
  status: profiled
  tags: *id006
  url: /providers/classlink/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.5
  mcp: *id007
  name: ClassWallet
  slug: classwallet
  status: profiled
  tags: *id008
  url: /providers/classwallet/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id009
  name: Clever
  slug: clever
  status: profiled
  tags: *id010
  url: /providers/clever/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 15.7
  mcp: *id011
  name: FACTS Tuition Management
  slug: facts-management
  status: profiled
  tags: *id012
  url: /providers/facts-management/
- agent_band: agent-ready
  agent_readiness: 37.8
  band: exemplar
  in_catalog: true
  kin_score: 72.6
  mcp: *id013
  name: Google Classroom
  slug: google-classroom
  status: profiled
  tags: *id014
  url: /providers/google-classroom/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id015
  name: Microsoft 365 (School Data Sync)
  slug: microsoft-365
  status: profiled
  tags: *id016
  url: /providers/microsoft-365/
- agent_band: agent-ready
  agent_readiness: 35.7
  band: developing
  in_catalog: true
  kin_score: 45.8
  mcp: *id017
  name: PaySimple
  slug: paysimple
  status: profiled
  tags: *id018
  url: /providers/paysimple/
- agent_band: agent-ready
  agent_readiness: 33.6
  band: developing
  in_catalog: true
  kin_score: 47.5
  mcp: *id019
  name: Renaissance (RDI)
  slug: renaissance
  status: profiled
  tags: *id020
  url: /providers/renaissance/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: emerging
  in_catalog: true
  kin_score: 23.8
  mcp: *id021
  name: Schoology
  slug: schoology
  status: profiled
  tags: *id022
  url: /providers/schoology/
siblings:
- name: Alma
  rows: 1
  url: /applications/school-admin-sis/alma/
- name: Classe365
  rows: 32
  url: /applications/school-admin-sis/classe365/
- name: Frappe Education
  rows: 2
  url: /applications/school-admin-sis/frappe-education/
- name: Gibbon
  rows: 11
  url: /applications/school-admin-sis/gibbon/
- name: Infinite Campus
  rows: 2
  url: /applications/school-admin-sis/infinite-campus/
- name: PowerSchool SIS
  rows: 2
  url: /applications/school-admin-sis/powerschool-sis/
- name: RosarioSIS
  rows: 1
  url: /applications/school-admin-sis/rosariosis/
- name: Veracross
  rows: 5
  url: /applications/school-admin-sis/veracross/
sitemap: true
title: 'Gradelink: School Administration & SIS reference app'
---
