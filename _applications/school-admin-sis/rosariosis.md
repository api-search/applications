---
app: RosarioSIS
app_slug: rosariosis
app_url: https://github.com/francoisjacquet/rosariosis
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4730.30
  key: learning-environment-management
  layer: domain
  name: Learning Environment Management
  providers:
  - Moodle
  url: /capabilities/learning-environment-management/
  via_parent: null
category:
  id: school-admin-sis
  name: School Administration & SIS
  url: /applications/school-admin-sis/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/francoisjacquet/rosariosis/blob/mobile/composer.json
- route: integrations page
  url: https://www.rosariosis.org/add-ons/
- route: source code
  url: https://github.com/francoisjacquet/rosariosis/tree/mobile/plugins
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4730.30
    key: learning-environment-management
    name: Learning Environment Management
    url: /capabilities/learning-environment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 1.7
    band: minimal
    in_catalog: true
    kin_score: 10.6
    mcp: &id001
      status: none
    slug: moodle
    status: profiled
    tags: &id002
    - E-Learning
    - EdTech
    - LMS
    - Moodle
    url: /providers/moodle/
  layer: domain
  name: Moodle
  provider: moodle
  says: ships the Moodle SDK or integration code
  source: https://github.com/francoisjacquet/rosariosis/tree/mobile/plugins
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/school-admin-sis/rosariosis/
providers:
- agent_band: human-only
  agent_readiness: 1.7
  band: minimal
  in_catalog: true
  kin_score: 10.6
  mcp: *id001
  name: Moodle
  slug: moodle
  status: profiled
  tags: *id002
  url: /providers/moodle/
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
- name: Veracross
  rows: 5
  url: /applications/school-admin-sis/veracross/
sitemap: true
title: 'RosarioSIS: School Administration & SIS reference app'
---
