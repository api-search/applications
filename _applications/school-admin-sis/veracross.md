---
app: Veracross
app_slug: veracross
app_url: https://www.veracross.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4800.30
  key: fundraising-campaign-management
  layer: domain
  name: Fundraising Campaign Management
  providers:
  - Double the Donation
  url: /capabilities/fundraising-campaign-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4730.30
  key: learning-environment-management
  layer: domain
  name: Learning Environment Management
  providers:
  - Firefly
  url: /capabilities/learning-environment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4710
  key: student-recruitment-admissions-management
  layer: domain
  name: Student Recruitment & Admissions Management
  providers:
  - Digistorm Websites
  url: /capabilities/student-recruitment-admissions-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4770
  key: student-support-wellbeing-management
  layer: domain
  name: Student Support & Wellbeing Management
  providers:
  - Epraise
  url: /capabilities/student-support-wellbeing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Intellischool
  url: /capabilities/analytics-bi-management/
  via_parent: null
category:
  id: school-admin-sis
  name: School Administration & SIS
  url: /applications/school-admin-sis/
counts:
  declared: 5
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.veracross.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4710
    key: student-recruitment-admissions-management
    name: Student Recruitment & Admissions Management
    url: /capabilities/student-recruitment-admissions-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.8
    band: emerging
    in_catalog: true
    kin_score: 17.3
    mcp: &id001
      status: unchecked
    slug: digistorm
    status: profiled
    tags: &id002
    - Education
    - K-12
    - SchoolSoftware
    - Software-as-a-Service
    url: /providers/digistorm/
  layer: domain
  name: Digistorm Websites
  provider: digistorm
  says: lists Digistorm Websites as an integration
  source: https://www.veracross.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4800.30
    key: fundraising-campaign-management
    name: Fundraising Campaign Management
    url: /capabilities/fundraising-campaign-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 25.6
    mcp: &id003
      status: unknown
    slug: double-the-donation
    status: profiled
    tags: &id004
    - Company
    - Fundraising
    - Matching Gifts
    - Non-Profit
    url: /providers/double-the-donation/
  layer: domain
  name: Double the Donation
  provider: double-the-donation
  says: lists Double the Donation as an integration
  source: https://www.veracross.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4770
    key: student-support-wellbeing-management
    name: Student Support & Wellbeing Management
    url: /capabilities/student-support-wellbeing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 9.8
    mcp: &id005
      status: unchecked
    slug: epraise
    status: profiled
    tags: &id006
    - Education
    - Engagement
    - Rewards
    - SchoolTech
    url: /providers/epraise/
  layer: domain
  name: Epraise
  provider: epraise
  says: lists Epraise as an integration
  source: https://www.veracross.com/integrations
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
    agent_readiness: 17.8
    band: minimal
    in_catalog: true
    kin_score: 7.9
    mcp: &id007
      status: unchecked
    slug: firefly-learning
    status: profiled
    tags: &id008
    - EdTech
    - Education
    - Schools
    - Software-as-a-Service
    url: /providers/firefly-learning/
  layer: domain
  name: Firefly
  provider: firefly-learning
  says: lists Firefly as an integration
  source: https://www.veracross.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: developing
    in_catalog: true
    kin_score: 43.1
    mcp: &id009
      status: unchecked
    slug: intellischool
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Company
    - Data
    - Education
    url: /providers/intellischool/
  layer: common
  name: Intellischool
  provider: intellischool
  says: lists Intellischool as an integration
  source: https://www.veracross.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/school-admin-sis/veracross/
providers:
- agent_band: agent-aware
  agent_readiness: 14.8
  band: emerging
  in_catalog: true
  kin_score: 17.3
  mcp: *id001
  name: Digistorm Websites
  slug: digistorm
  status: profiled
  tags: *id002
  url: /providers/digistorm/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 25.6
  mcp: *id003
  name: Double the Donation
  slug: double-the-donation
  status: profiled
  tags: *id004
  url: /providers/double-the-donation/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 9.8
  mcp: *id005
  name: Epraise
  slug: epraise
  status: profiled
  tags: *id006
  url: /providers/epraise/
- agent_band: agent-aware
  agent_readiness: 17.8
  band: minimal
  in_catalog: true
  kin_score: 7.9
  mcp: *id007
  name: Firefly
  slug: firefly-learning
  status: profiled
  tags: *id008
  url: /providers/firefly-learning/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: developing
  in_catalog: true
  kin_score: 43.1
  mcp: *id009
  name: Intellischool
  slug: intellischool
  status: profiled
  tags: *id010
  url: /providers/intellischool/
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
- name: Gradelink
  rows: 11
  url: /applications/school-admin-sis/gradelink/
- name: Infinite Campus
  rows: 2
  url: /applications/school-admin-sis/infinite-campus/
- name: PowerSchool SIS
  rows: 2
  url: /applications/school-admin-sis/powerschool-sis/
- name: RosarioSIS
  rows: 1
  url: /applications/school-admin-sis/rosariosis/
sitemap: true
title: 'Veracross: School Administration & SIS reference app'
---
