---
app: Siteline
app_slug: siteline
app_url: https://www.siteline.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-5030.40.20
  key: BC-5030.40.20
  layer: domain
  name: Interim Valuation Management
  providers:
  - Oracle Textura
  - Procore Pay
  url: /capabilities/commercial-quantity-surveying/
  via_parent: Commercial & Quantity Surveying
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - Acumatica
  - CMiC
  - Deltek ComputerEase
  - Foundation Software
  - Oracle NetSuite
  - QuickBooks Enterprise Contractor / Online
  - Sage 300 CRE / Sage 100 Contractor
  - Sage Intacct
  - Viewpoint Vista / Viewpoint Spectrum
  url: /capabilities/general-ledger-management/
  via_parent: null
category:
  id: construction-management
  name: Construction Management
  url: /applications/construction-management/
counts:
  declared: 11
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.siteline.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 13.6
    band: emerging
    in_catalog: true
    kin_score: 17.9
    mcp: &id001
      status: none
    slug: acumatica
    status: profiled
    tags: &id002
    - Cloud ERP
    - ERP
    - Financial Management
    - Inventory
    url: /providers/acumatica/
  layer: common
  name: Acumatica
  provider: acumatica
  says: lists Acumatica as an integration
  source: https://www.siteline.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.4
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id003
      status: unknown
    slug: cmic
    status: profiled
    tags: &id004
    - Construction
    - ERP
    - Finance
    - Project Management
    url: /providers/cmic/
  layer: common
  name: CMiC
  provider: cmic
  says: lists CMiC as an integration
  source: https://www.siteline.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.0
    band: emerging
    in_catalog: true
    kin_score: 15.1
    mcp: &id005
      source: https://learning.deltek.com/bundle/MCP_Server_Setup_Guide_for_REST_APIs/page/overview.html
      status: documented
    slug: deltek
    status: profiled
    tags: &id006
    - Company
    - Enterprise
    - Project Management
    - Software
    url: /providers/deltek/
  layer: common
  name: Deltek ComputerEase
  provider: deltek
  says: lists Deltek ComputerEase as an integration
  source: https://www.siteline.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 13.0
    mcp: &id007
      status: unknown
    slug: foundation-software
    status: profiled
    tags: &id008
    - Accounting
    - Construction
    - Contractors
    - Software
    url: /providers/foundation-software/
  layer: common
  name: Foundation Software
  provider: foundation-software
  says: lists Foundation Software as an integration
  source: https://www.siteline.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.5
    mcp: &id009
      status: none
    slug: netsuite
    status: profiled
    tags: &id010
    - Accounting
    - CRM
    - ERP
    - Finance
    url: /providers/netsuite/
  layer: common
  name: Oracle NetSuite
  provider: netsuite
  says: lists Oracle NetSuite as an integration
  source: https://www.siteline.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-5030.40.20
    key: BC-5030.40.20
    name: Interim Valuation Management
    url: /capabilities/commercial-quantity-surveying/
    via_parent: Commercial & Quantity Surveying
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 68.6
    mcp: &id011
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id012
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
  layer: domain
  name: Oracle Textura
  provider: oracle
  says: lists Oracle Textura as an integration
  source: https://www.siteline.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-5030.40.20
    key: BC-5030.40.20
    name: Interim Valuation Management
    url: /capabilities/commercial-quantity-surveying/
    via_parent: Commercial & Quantity Surveying
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.3
    band: strong
    in_catalog: true
    kin_score: 62.2
    mcp: &id013
      status: none
    slug: procore
    status: profiled
    tags: &id014
    - Construction
    - Construction Management
    - Field Productivity
    - Project Management
    url: /providers/procore/
  layer: domain
  name: Procore Pay
  provider: procore
  says: lists Procore Pay as an integration
  source: https://www.siteline.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 41.2
    band: strong
    in_catalog: true
    kin_score: 61.1
    mcp: &id015
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id016
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks Enterprise Contractor / Online
  provider: quickbooks
  says: lists QuickBooks Enterprise Contractor / Online as an integration
  source: https://www.siteline.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: developing
    in_catalog: true
    kin_score: 41.8
    mcp: &id017
      status: none
    slug: sage
    status: profiled
    tags: &id018
    - Accounting
    - Business Management
    - Cloud Software
    - ERP
    url: /providers/sage/
  layer: common
  name: Sage 300 CRE / Sage 100 Contractor
  provider: sage
  says: lists Sage 300 CRE / Sage 100 Contractor as an integration
  source: https://www.siteline.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 15.5
    band: thin
    in_catalog: true
    kin_score: 26.3
    mcp: &id019
      status: none
    slug: sage-intacct
    status: profiled
    tags: &id020
    - Accounting
    - ERP
    - Financial Management
    - General Ledger
    url: /providers/sage-intacct/
  layer: common
  name: Sage Intacct
  provider: sage-intacct
  says: lists Sage Intacct as an integration
  source: https://www.siteline.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.0
    band: developing
    in_catalog: true
    kin_score: 41.1
    mcp: &id021
      status: none
    slug: trimble
    status: profiled
    tags: &id022
    - Construction
    - GPS
    - Geospatial
    - Transportation
    url: /providers/trimble/
  layer: common
  name: Viewpoint Vista / Viewpoint Spectrum
  provider: trimble
  says: lists Viewpoint Vista / Viewpoint Spectrum as an integration
  source: https://www.siteline.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/construction-management/siteline/
providers:
- agent_band: agent-aware
  agent_readiness: 13.6
  band: emerging
  in_catalog: true
  kin_score: 17.9
  mcp: *id001
  name: Acumatica
  slug: acumatica
  status: profiled
  tags: *id002
  url: /providers/acumatica/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id003
  name: CMiC
  slug: cmic
  status: profiled
  tags: *id004
  url: /providers/cmic/
- agent_band: agent-aware
  agent_readiness: 18.0
  band: emerging
  in_catalog: true
  kin_score: 15.1
  mcp: *id005
  name: Deltek ComputerEase
  slug: deltek
  status: profiled
  tags: *id006
  url: /providers/deltek/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 13.0
  mcp: *id007
  name: Foundation Software
  slug: foundation-software
  status: profiled
  tags: *id008
  url: /providers/foundation-software/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.5
  mcp: *id009
  name: Oracle NetSuite
  slug: netsuite
  status: profiled
  tags: *id010
  url: /providers/netsuite/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 68.6
  mcp: *id011
  name: Oracle Textura
  slug: oracle
  status: profiled
  tags: *id012
  url: /providers/oracle/
- agent_band: agent-ready
  agent_readiness: 41.3
  band: strong
  in_catalog: true
  kin_score: 62.2
  mcp: *id013
  name: Procore Pay
  slug: procore
  status: profiled
  tags: *id014
  url: /providers/procore/
- agent_band: agent-native
  agent_readiness: 41.2
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id015
  name: QuickBooks Enterprise Contractor / Online
  slug: quickbooks
  status: profiled
  tags: *id016
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 41.8
  mcp: *id017
  name: Sage 300 CRE / Sage 100 Contractor
  slug: sage
  status: profiled
  tags: *id018
  url: /providers/sage/
- agent_band: agent-aware
  agent_readiness: 15.5
  band: thin
  in_catalog: true
  kin_score: 26.3
  mcp: *id019
  name: Sage Intacct
  slug: sage-intacct
  status: profiled
  tags: *id020
  url: /providers/sage-intacct/
- agent_band: agent-aware
  agent_readiness: 23.0
  band: developing
  in_catalog: true
  kin_score: 41.1
  mcp: *id021
  name: Viewpoint Vista / Viewpoint Spectrum
  slug: trimble
  status: profiled
  tags: *id022
  url: /providers/trimble/
siblings:
- name: CompanyCam
  rows: 15
  url: /applications/construction-management/companycam/
- name: JobTread
  rows: 11
  url: /applications/construction-management/jobtread/
- name: Knowify
  rows: 9
  url: /applications/construction-management/knowify/
- name: OpenProject (BIM)
  rows: 7
  url: /applications/construction-management/openproject-bim/
- name: Procore
  rows: 12
  url: /applications/construction-management/procore/
- name: Raken
  rows: 21
  url: /applications/construction-management/raken/
sitemap: true
title: 'Siteline: Construction Management reference app'
---
