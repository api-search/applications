---
app: JobSpy
app_slug: jobspy
app_url: https://github.com/speedyapply/JobSpy
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230.120
  key: AE-230.120
  layer: domain
  name: Job Listings Search & Aggregation
  providers:
  - Bayt
  - BDJobs
  - Glassdoor
  - Google Jobs
  - HelloWork
  - Indeed
  - LinkedIn Jobs
  - Naukri
  - ZipRecruiter
  url: /capabilities/job-listings-search-aggregation/
  via_parent: null
category:
  id: job-search
  name: Job Search
  url: /applications/job-search/
counts:
  declared: 0
  observed: 9
credits: []
evidence:
- route: documentation
  url: https://github.com/speedyapply/JobSpy/blob/main/README.md
- route: source code
  url: https://github.com/speedyapply/JobSpy/tree/main/jobspy
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-230.120
    key: AE-230.120
    name: Job Listings Search & Aggregation
    url: /capabilities/job-listings-search-aggregation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 7.2
    mcp: &id001
      status: unchecked
    slug: bayt
    status: profiled
    tags: &id002
    - Careers
    - JobSite
    - Middle East
    - North-Africa
    url: /providers/bayt/
  layer: domain
  name: Bayt
  provider: bayt
  says: ships the Bayt SDK or integration code
  source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.120
    key: AE-230.120
    name: Job Listings Search & Aggregation
    url: /capabilities/job-listings-search-aggregation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 8.7
    mcp: &id003
      status: unchecked
    slug: bdjobs
    status: profiled
    tags: &id004
    - Company
    url: /providers/bdjobs/
  layer: domain
  name: BDJobs
  provider: bdjobs
  says: ships the BDJobs SDK or integration code
  source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.120
    key: AE-230.120
    name: Job Listings Search & Aggregation
    url: /capabilities/job-listings-search-aggregation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 11.4
    mcp: &id005
      status: none
    slug: glassdoor
    status: profiled
    tags: &id006
    - Employer Reviews
    - Job Search
    - Recruiting
    - Salaries
    url: /providers/glassdoor/
  layer: domain
  name: Glassdoor
  provider: glassdoor
  says: ships the Glassdoor SDK or integration code
  source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.120
    key: AE-230.120
    name: Job Listings Search & Aggregation
    url: /capabilities/job-listings-search-aggregation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id007
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id008
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: Google Jobs
  provider: google
  says: ships the Google Jobs SDK or integration code
  source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.120
    key: AE-230.120
    name: Job Listings Search & Aggregation
    url: /capabilities/job-listings-search-aggregation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 2.2
    mcp: &id009
      status: unchecked
    slug: hellowork
    status: profiled
    tags: &id010
    - Company
    - Employment
    - Job Search
    - Recruiting
    url: /providers/hellowork/
  layer: domain
  name: HelloWork
  provider: hellowork
  says: ships the HelloWork SDK or integration code
  source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.120
    key: AE-230.120
    name: Job Listings Search & Aggregation
    url: /capabilities/job-listings-search-aggregation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.0
    band: developing
    in_catalog: true
    kin_score: 44.6
    mcp: &id011
      status: none
    slug: indeed
    status: profiled
    tags: &id012
    - Careers
    - Employment
    - Hiring
    - Job Search
    url: /providers/indeed/
  layer: domain
  name: Indeed
  provider: indeed
  says: ships the Indeed SDK or integration code
  source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.120
    key: AE-230.120
    name: Job Listings Search & Aggregation
    url: /capabilities/job-listings-search-aggregation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.5
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id013
      status: none
    slug: linkedin
    status: profiled
    tags: &id014
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn Jobs
  provider: linkedin
  says: ships the LinkedIn Jobs SDK or integration code
  source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.120
    key: AE-230.120
    name: Job Listings Search & Aggregation
    url: /capabilities/job-listings-search-aggregation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.9
    mcp: &id015
      status: unknown
    slug: naukri
    status: profiled
    tags: &id016
    - Careers
    - Company
    - Job
    - Recruiting
    url: /providers/naukri/
  layer: domain
  name: Naukri
  provider: naukri
  says: ships the Naukri SDK or integration code
  source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.120
    key: AE-230.120
    name: Job Listings Search & Aggregation
    url: /capabilities/job-listings-search-aggregation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.7
    band: minimal
    in_catalog: true
    kin_score: 8.9
    mcp: &id017
      status: unknown
    slug: ziprecruiter
    status: profiled
    tags: &id018
    - Job
    - Job Board
    - Public APIs
    - Recruiting
    url: /providers/ziprecruiter/
  layer: domain
  name: ZipRecruiter
  provider: ziprecruiter
  says: ships the ZipRecruiter SDK or integration code
  source: https://github.com/speedyapply/JobSpy/tree/main/jobspy
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/job-search/jobspy/
providers:
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 7.2
  mcp: *id001
  name: Bayt
  slug: bayt
  status: profiled
  tags: *id002
  url: /providers/bayt/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 8.7
  mcp: *id003
  name: BDJobs
  slug: bdjobs
  status: profiled
  tags: *id004
  url: /providers/bdjobs/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 11.4
  mcp: *id005
  name: Glassdoor
  slug: glassdoor
  status: profiled
  tags: *id006
  url: /providers/glassdoor/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id007
  name: Google Jobs
  slug: google
  status: profiled
  tags: *id008
  url: /providers/google/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id009
  name: HelloWork
  slug: hellowork
  status: profiled
  tags: *id010
  url: /providers/hellowork/
- agent_band: agent-ready
  agent_readiness: 29.0
  band: developing
  in_catalog: true
  kin_score: 44.6
  mcp: *id011
  name: Indeed
  slug: indeed
  status: profiled
  tags: *id012
  url: /providers/indeed/
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id013
  name: LinkedIn Jobs
  slug: linkedin
  status: profiled
  tags: *id014
  url: /providers/linkedin/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.9
  mcp: *id015
  name: Naukri
  slug: naukri
  status: profiled
  tags: *id016
  url: /providers/naukri/
- agent_band: human-only
  agent_readiness: 0.7
  band: minimal
  in_catalog: true
  kin_score: 8.9
  mcp: *id017
  name: ZipRecruiter
  slug: ziprecruiter
  status: profiled
  tags: *id018
  url: /providers/ziprecruiter/
siblings:
- name: Glassdoor
  rows: 2
  url: /applications/job-search/glassdoor/
- name: Indeed
  rows: 2
  url: /applications/job-search/indeed/
- name: JobSync
  rows: 8
  url: /applications/job-search/jobsync/
- name: LinkedIn
  rows: 7
  url: /applications/job-search/linkedin/
- name: Reactive Resume
  rows: 30
  url: /applications/job-search/reactive-resume/
- name: Resume Matcher
  rows: 8
  url: /applications/job-search/resume-matcher/
sitemap: true
title: 'JobSpy: Job Search reference app'
---
