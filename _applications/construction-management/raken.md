---
app: Raken
app_slug: raken
app_url: https://www.rakenapp.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1150
  key: construction-management
  layer: domain
  name: Construction Management
  providers:
  - Autodesk
  - Procore
  url: /capabilities/construction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1150.60
  key: construction-progress-management
  layer: domain
  name: Construction Progress Management
  providers:
  - DroneDeploy
  - EarthCam
  - HoloBuilder
  - TrueLook
  url: /capabilities/construction-progress-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300.80.40
  key: BC-300.80.40
  layer: domain
  name: Employment Law Compliance
  providers:
  - Points North
  url: /capabilities/employee-labour-relations/
  via_parent: Employee & Labour Relations
- attribution: Turbo EA
  id: BC-1130
  key: engineering-document-management
  layer: domain
  name: Engineering Document Management
  providers:
  - Bluebeam
  url: /capabilities/engineering-document-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Box
  - Dropbox
  - Egnyte
  - Google Drive
  - OneDrive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - CMiC
  - Deltek ComputerEase
  - Foundation
  - QuickBooks Desktop/Online
  - Sage 100 Contractor / Sage 300 CRE
  - Sage Intacct
  - Viewpoint Vista / Viewpoint Spectrum
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: common
  name: Human Capital Management
  providers:
  - Paychex
  url: /capabilities/human-capital-management/
  via_parent: null
category:
  id: construction-management
  name: Construction Management
  url: /applications/construction-management/
counts:
  declared: 21
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.rakenapp.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-1150
    key: construction-management
    name: Construction Management
    url: /capabilities/construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 69.0
    mcp: &id001
      source: https://github.com/autodesk-platform-services/aps-mcp-server-nodejs
      status: verified
    slug: autodesk-construction-cloud
    status: profiled
    tags: &id002
    - AEC
    - BIM
    - Construction
    - Project Management
    url: /providers/autodesk-construction-cloud/
  layer: domain
  name: Autodesk
  provider: autodesk-construction-cloud
  says: lists Autodesk as an integration
  source: https://www.rakenapp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1130
    key: engineering-document-management
    name: Engineering Document Management
    url: /capabilities/engineering-document-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.3
    band: thin
    in_catalog: true
    kin_score: 33.7
    mcp: &id003
      status: none
    slug: bluebeam
    status: profiled
    tags: &id004
    - Construction
    - Documents
    - PDF
    - Project Management
    url: /providers/bluebeam/
  layer: domain
  name: Bluebeam
  provider: bluebeam
  says: lists Bluebeam as an integration
  source: https://www.rakenapp.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.6
    band: strong
    in_catalog: true
    kin_score: 63.0
    mcp: &id005
      source: https://developer.box.com/guides/box-mcp/
      status: verified
    slug: box
    status: profiled
    tags: &id006
    - Cloud Storage
    - Collaboration
    - Content Management
    - Documents
    url: /providers/box/
  layer: common
  name: Box
  provider: box
  says: lists Box as an integration
  source: https://www.rakenapp.com/integrations
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
    agent_readiness: 28.2
    band: thin
    in_catalog: true
    kin_score: 37.7
    mcp: &id007
      status: unknown
    slug: cmic
    status: profiled
    tags: &id008
    - Construction
    - ERP
    - Finance
    - Project Management
    url: /providers/cmic/
  layer: common
  name: CMiC
  provider: cmic
  says: lists CMiC as an integration
  source: https://www.rakenapp.com/integrations
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
    agent_readiness: 14.8
    band: emerging
    in_catalog: true
    kin_score: 20.5
    mcp: &id009
      source: https://learning.deltek.com/bundle/MCP_Server_Setup_Guide_for_REST_APIs/page/overview.html
      status: documented
    slug: deltek
    status: profiled
    tags: &id010
    - Company
    - Enterprise
    - Project Management
    - Software
    url: /providers/deltek/
  layer: common
  name: Deltek ComputerEase
  provider: deltek
  says: lists Deltek ComputerEase as an integration
  source: https://www.rakenapp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1150.60
    key: construction-progress-management
    name: Construction Progress Management
    url: /capabilities/construction-progress-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.8
    band: thin
    in_catalog: true
    kin_score: 31.9
    mcp: &id011
      status: unknown
    slug: dronedeploy
    status: profiled
    tags: &id012
    - Aerial Analytics
    - Drone Mapping
    - Geospatial
    - Reality Capture
    url: /providers/dronedeploy/
  layer: domain
  name: DroneDeploy
  provider: dronedeploy
  says: lists DroneDeploy as an integration
  source: https://www.rakenapp.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id013
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id014
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: common
  name: Dropbox
  provider: dropbox
  says: lists Dropbox as an integration
  source: https://www.rakenapp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1150.60
    key: construction-progress-management
    name: Construction Progress Management
    url: /capabilities/construction-progress-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 16.7
    mcp: &id015
      status: unknown
    slug: earthcam
    status: profiled
    tags: &id016
    - Company
    - Construction
    - Webcam
    - visual-data
    url: /providers/earthcam/
  layer: domain
  name: EarthCam
  provider: earthcam
  says: lists EarthCam as an integration
  source: https://www.rakenapp.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: thin
    in_catalog: true
    kin_score: 29.5
    mcp: &id017
      source: https://github.com/egnyte/egnyte-mcp-server
      status: verified
    slug: egnyte
    status: profiled
    tags: &id018
    - Content Collaboration
    - Document Management
    - Enterprise Storage
    - File Sharing
    url: /providers/egnyte/
  layer: common
  name: Egnyte
  provider: egnyte
  says: lists Egnyte as an integration
  source: https://www.rakenapp.com/integrations
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
    kin_score: 19.9
    mcp: &id019
      status: unknown
    slug: foundation-software
    status: profiled
    tags: &id020
    - Accounting
    - Construction
    - Contractors
    - Software
    url: /providers/foundation-software/
  layer: common
  name: Foundation
  provider: foundation-software
  says: lists Foundation as an integration
  source: https://www.rakenapp.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 73.2
    mcp: &id021
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id022
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: common
  name: Google Drive
  provider: google-drive
  says: lists Google Drive as an integration
  source: https://www.rakenapp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1150.60
    key: construction-progress-management
    name: Construction Progress Management
    url: /capabilities/construction-progress-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id023
      status: unchecked
    slug: holobuilder
    status: queued for profiling
    tags: &id024 []
    url: null
  layer: domain
  name: HoloBuilder
  provider: holobuilder
  says: lists HoloBuilder as an integration
  source: https://www.rakenapp.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id025
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id026
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: common
  name: OneDrive
  provider: microsoft-onedrive
  says: lists OneDrive as an integration
  source: https://www.rakenapp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.3
    band: thin
    in_catalog: true
    kin_score: 37.8
    mcp: &id027
      status: none
    slug: paychex-developer
    status: profiled
    tags: &id028
    - Benefits
    - HCM
    - Human Resources
    - Paychex Flex
    url: /providers/paychex-developer/
  layer: common
  name: Paychex
  provider: paychex-developer
  says: lists Paychex as an integration
  source: https://www.rakenapp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.80.40
    key: BC-300.80.40
    name: Employment Law Compliance
    url: /capabilities/employee-labour-relations/
    via_parent: Employee & Labour Relations
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id029
      status: unchecked
    slug: points-north
    status: queued for profiling
    tags: &id030 []
    url: null
  layer: domain
  name: Points North
  provider: points-north
  says: lists Points North as an integration
  source: https://www.rakenapp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1150
    key: construction-management
    name: Construction Management
    url: /capabilities/construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.1
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id031
      status: none
    slug: procore
    status: profiled
    tags: &id032
    - Construction
    - Construction Management
    - Field Productivity
    - Project Management
    url: /providers/procore/
  layer: domain
  name: Procore
  provider: procore
  says: lists Procore as an integration
  source: https://www.rakenapp.com/integrations
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
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id033
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id034
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks Desktop/Online
  provider: quickbooks
  says: lists QuickBooks Desktop/Online as an integration
  source: https://www.rakenapp.com/integrations
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
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 41.7
    mcp: &id035
      status: none
    slug: sage
    status: profiled
    tags: &id036
    - Accounting
    - Business Management
    - Cloud Software
    - ERP
    url: /providers/sage/
  layer: common
  name: Sage 100 Contractor / Sage 300 CRE
  provider: sage
  says: lists Sage 100 Contractor / Sage 300 CRE as an integration
  source: https://www.rakenapp.com/integrations
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
    agent_readiness: 15.1
    band: thin
    in_catalog: true
    kin_score: 26.5
    mcp: &id037
      status: none
    slug: sage-intacct
    status: profiled
    tags: &id038
    - Accounting
    - ERP
    - Financial Management
    - General Ledger
    url: /providers/sage-intacct/
  layer: common
  name: Sage Intacct
  provider: sage-intacct
  says: lists Sage Intacct as an integration
  source: https://www.rakenapp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1150.60
    key: construction-progress-management
    name: Construction Progress Management
    url: /capabilities/construction-progress-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 23.8
    mcp: &id039
      status: none
    slug: truelook
    status: profiled
    tags: &id040
    - Artificial Intelligence
    - Construction
    - Security
    - Video
    url: /providers/truelook/
  layer: domain
  name: TrueLook
  provider: truelook
  says: lists TrueLook as an integration
  source: https://www.rakenapp.com/integrations
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
    agent_readiness: 35.3
    band: exemplar
    in_catalog: true
    kin_score: 66.6
    mcp: &id041
      status: none
    slug: trimble
    status: profiled
    tags: &id042
    - Construction
    - GPS
    - Geospatial
    - Transportation
    url: /providers/trimble/
  layer: common
  name: Viewpoint Vista / Viewpoint Spectrum
  provider: trimble
  says: lists Viewpoint Vista / Viewpoint Spectrum as an integration
  source: https://www.rakenapp.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/construction-management/raken/
providers:
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 69.0
  mcp: *id001
  name: Autodesk
  slug: autodesk-construction-cloud
  status: profiled
  tags: *id002
  url: /providers/autodesk-construction-cloud/
- agent_band: agent-ready
  agent_readiness: 30.3
  band: thin
  in_catalog: true
  kin_score: 33.7
  mcp: *id003
  name: Bluebeam
  slug: bluebeam
  status: profiled
  tags: *id004
  url: /providers/bluebeam/
- agent_band: agent-ready
  agent_readiness: 56.6
  band: strong
  in_catalog: true
  kin_score: 63.0
  mcp: *id005
  name: Box
  slug: box
  status: profiled
  tags: *id006
  url: /providers/box/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: thin
  in_catalog: true
  kin_score: 37.7
  mcp: *id007
  name: CMiC
  slug: cmic
  status: profiled
  tags: *id008
  url: /providers/cmic/
- agent_band: agent-aware
  agent_readiness: 14.8
  band: emerging
  in_catalog: true
  kin_score: 20.5
  mcp: *id009
  name: Deltek ComputerEase
  slug: deltek
  status: profiled
  tags: *id010
  url: /providers/deltek/
- agent_band: agent-aware
  agent_readiness: 16.8
  band: thin
  in_catalog: true
  kin_score: 31.9
  mcp: *id011
  name: DroneDeploy
  slug: dronedeploy
  status: profiled
  tags: *id012
  url: /providers/dronedeploy/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id013
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id014
  url: /providers/dropbox/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 16.7
  mcp: *id015
  name: EarthCam
  slug: earthcam
  status: profiled
  tags: *id016
  url: /providers/earthcam/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id017
  name: Egnyte
  slug: egnyte
  status: profiled
  tags: *id018
  url: /providers/egnyte/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.9
  mcp: *id019
  name: Foundation
  slug: foundation-software
  status: profiled
  tags: *id020
  url: /providers/foundation-software/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id021
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id022
  url: /providers/google-drive/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id023
  name: HoloBuilder
  slug: holobuilder
  status: queued for profiling
  tags: *id024
  url: null
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id025
  name: OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id026
  url: /providers/microsoft-onedrive/
- agent_band: agent-ready
  agent_readiness: 29.3
  band: thin
  in_catalog: true
  kin_score: 37.8
  mcp: *id027
  name: Paychex
  slug: paychex-developer
  status: profiled
  tags: *id028
  url: /providers/paychex-developer/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id029
  name: Points North
  slug: points-north
  status: queued for profiling
  tags: *id030
  url: null
- agent_band: agent-ready
  agent_readiness: 36.1
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id031
  name: Procore
  slug: procore
  status: profiled
  tags: *id032
  url: /providers/procore/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id033
  name: QuickBooks Desktop/Online
  slug: quickbooks
  status: profiled
  tags: *id034
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 41.7
  mcp: *id035
  name: Sage 100 Contractor / Sage 300 CRE
  slug: sage
  status: profiled
  tags: *id036
  url: /providers/sage/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id037
  name: Sage Intacct
  slug: sage-intacct
  status: profiled
  tags: *id038
  url: /providers/sage-intacct/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 23.8
  mcp: *id039
  name: TrueLook
  slug: truelook
  status: profiled
  tags: *id040
  url: /providers/truelook/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: exemplar
  in_catalog: true
  kin_score: 66.6
  mcp: *id041
  name: Viewpoint Vista / Viewpoint Spectrum
  slug: trimble
  status: profiled
  tags: *id042
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
- name: Siteline
  rows: 11
  url: /applications/construction-management/siteline/
sitemap: true
title: 'Raken: Construction Management reference app'
---
