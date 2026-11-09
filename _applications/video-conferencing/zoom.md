---
app: Zoom
app_slug: zoom
app_url: https://zoom.us/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-830.30
  key: knowledge-sharing-collaboration-management
  layer: domain
  name: Knowledge Sharing & Collaboration Management
  providers:
  - Atlassian
  - Google
  - Microsoft
  - Oracle
  - Salesforce
  - ServiceNow
  url: /capabilities/knowledge-sharing-collaboration-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Okta
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: video-conferencing
  name: Video Conferencing & Webinars
  url: /applications/video-conferencing/
counts:
  declared: 7
  observed: 0
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/us.zoom.videomeetings/latest/
- route: integrations page
  url: https://www.zoom.com/en/products/collaboration-tools/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.6
    band: exemplar
    in_catalog: true
    kin_score: 79.9
    mcp: &id001
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: atlassian
    status: profiled
    tags: &id002
    - Code
    - Collaboration
    - Platform
    - Productivity
    url: /providers/atlassian/
  layer: domain
  name: Atlassian
  provider: atlassian
  says: lists Atlassian as an integration
  source: https://www.zoom.com/en/products/collaboration-tools/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.5
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id003
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id004
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: Google
  provider: google
  says: lists Google as an integration
  source: https://www.zoom.com/en/products/collaboration-tools/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.6
    band: strong
    in_catalog: true
    kin_score: 66.3
    mcp: &id005
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft
    status: profiled
    tags: &id006
    - Cloud
    - Fortune 100
    - Microsoft
    - Software
    url: /providers/microsoft/
  layer: domain
  name: Microsoft
  provider: microsoft
  says: lists Microsoft as an integration
  source: https://www.zoom.com/en/products/collaboration-tools/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.8
    band: exemplar
    in_catalog: true
    kin_score: 78.0
    mcp: &id007
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id008
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: common
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://www.zoom.com/en/products/collaboration-tools/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 68.6
    mcp: &id009
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id010
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
  layer: domain
  name: Oracle
  provider: oracle
  says: lists Oracle as an integration
  source: https://www.zoom.com/en/products/collaboration-tools/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.7
    band: exemplar
    in_catalog: true
    kin_score: 90.6
    mcp: &id011
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id012
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.zoom.com/en/products/collaboration-tools/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.2
    band: strong
    in_catalog: true
    kin_score: 64.1
    mcp: &id013
      status: none
    slug: servicenow
    status: profiled
    tags: &id014
    - Automation
    - Cloud Services
    - Digital Workflows
    - ServiceNow
    url: /providers/servicenow/
  layer: domain
  name: ServiceNow
  provider: servicenow
  says: lists ServiceNow as an integration
  source: https://www.zoom.com/en/products/collaboration-tools/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/video-conferencing/zoom/
providers:
- agent_band: agent-ready
  agent_readiness: 42.6
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id001
  name: Atlassian
  slug: atlassian
  status: profiled
  tags: *id002
  url: /providers/atlassian/
- agent_band: agent-ready
  agent_readiness: 48.5
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id003
  name: Google
  slug: google
  status: profiled
  tags: *id004
  url: /providers/google/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id005
  name: Microsoft
  slug: microsoft
  status: profiled
  tags: *id006
  url: /providers/microsoft/
- agent_band: agent-ready
  agent_readiness: 53.8
  band: exemplar
  in_catalog: true
  kin_score: 78.0
  mcp: *id007
  name: Okta
  slug: okta
  status: profiled
  tags: *id008
  url: /providers/okta/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 68.6
  mcp: *id009
  name: Oracle
  slug: oracle
  status: profiled
  tags: *id010
  url: /providers/oracle/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id011
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id012
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: strong
  in_catalog: true
  kin_score: 64.1
  mcp: *id013
  name: ServiceNow
  slug: servicenow
  status: profiled
  tags: *id014
  url: /providers/servicenow/
siblings:
- name: BigBlueButton
  rows: 5
  url: /applications/video-conferencing/bigbluebutton/
- name: Jitsi Meet
  rows: 9
  url: /applications/video-conferencing/jitsi-meet/
- name: LiveKit Meet
  rows: 3
  url: /applications/video-conferencing/livekit-meet/
- name: Microsoft Teams
  rows: 1
  url: /applications/video-conferencing/microsoft-teams/
- name: Nextcloud Talk
  rows: 8
  url: /applications/video-conferencing/nextcloud-talk/
- name: Webex Meetings
  rows: 2
  url: /applications/video-conferencing/webex-meetings/
sitemap: true
title: 'Zoom: Video Conferencing & Webinars reference app'
---
