---
app: SeeClickFix (CivicPlus)
app_slug: seeclickfix-civicplus
app_url: https://www.civicplus.com/seeclickfix-311-crm/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-3220
  key: citizen-constituent-service-management
  layer: domain
  name: Citizen & Constituent Service Management
  providers:
  - Microsoft Dynamics
  - Oracle Service Cloud
  - Verint (KANA Lagan)
  url: /capabilities/citizen-constituent-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-5060.40
  key: geospatial-survey-management
  layer: domain
  name: Geospatial & Survey Management
  providers:
  - Esri ArcGIS
  url: /capabilities/geospatial-survey-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1030.50
  key: maintenance-work-order-management
  layer: domain
  name: Maintenance Work Order Management
  providers:
  - Brightly Software
  - Cityworks (Trimble)
  - IBM (Maximo)
  - Infor
  - OpenGov
  - PubWorks
  - VUEWorks
  url: /capabilities/maintenance-work-order-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3240
  key: permits-licences-authorisations-management
  layer: domain
  name: Permits, Licences & Authorisations Management
  providers:
  - Accela Automation
  - CentralSquare Technologies
  - Tyler Technologies
  url: /capabilities/permits-licences-authorisations-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - Facebook
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: Turbo EA
  id: BC-1010.10
  key: work-order-management
  layer: domain
  name: Work Order Management
  providers:
  - Bigbelly
  url: /capabilities/work-order-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Amazon Web Services (Mobile Analytics / Amplify)
  - Facebook
  - Firebase
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: civic-government-services
  name: Civic & Government Services
  url: /applications/civic-government-services/
counts:
  declared: 15
  observed: 6
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
- route: integrations page
  url: https://www.civicplus.com/seeclickfix-311-crm/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id006
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: Amazon Web Services (Mobile Analytics / Amplify)
  provider: amazon-web-services
  says: ships the Amazon Web Services (Mobile Analytics / Amplify) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id017
      status: none
    slug: facebook
    status: profiled
    tags: &id018
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: domain
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id002
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id019
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id020
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id002
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.seeclickfix.ma.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3240
    key: permits-licences-authorisations-management
    name: Permits, Licences & Authorisations Management
    url: /capabilities/permits-licences-authorisations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.1
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id003
      status: none
    slug: accela
    status: profiled
    tags: &id004
    - GovTech
    - Government
    - Licensing
    - Permitting
    url: /providers/accela/
  layer: domain
  name: Accela Automation
  provider: accela
  says: lists Accela Automation as an integration
  source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1010.10
    key: work-order-management
    name: Work Order Management
    url: /capabilities/work-order-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 5.1
    mcp: &id007
      status: unchecked
    slug: bigbelly
    status: profiled
    tags: &id008
    - Municipal Solutions
    - Public Space
    - Smart Bins
    - Waste Management
    url: /providers/bigbelly/
  layer: domain
  name: Bigbelly
  provider: bigbelly
  says: lists Bigbelly as an integration
  source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1030.50
    key: maintenance-work-order-management
    name: Maintenance Work Order Management
    url: /capabilities/maintenance-work-order-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id009
      status: unchecked
    slug: brightly-software
    status: queued for profiling
    tags: &id010 []
    url: null
  layer: domain
  name: Brightly Software
  provider: brightly-software
  says: lists Brightly Software as an integration
  source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3240
    key: permits-licences-authorisations-management
    name: Permits, Licences & Authorisations Management
    url: /capabilities/permits-licences-authorisations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: emerging
    in_catalog: true
    kin_score: 23.3
    mcp: &id011
      status: unchecked
    slug: centralsquare
    status: profiled
    tags: &id012
    - Cloud Software
    - Company
    - Government
    - Public Safety
    url: /providers/centralsquare/
  layer: domain
  name: CentralSquare Technologies
  provider: centralsquare
  says: lists CentralSquare Technologies as an integration
  source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1030.50
    key: maintenance-work-order-management
    name: Maintenance Work Order Management
    url: /capabilities/maintenance-work-order-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id013
      status: unchecked
    slug: cityworks
    status: queued for profiling
    tags: &id014 []
    url: null
  layer: domain
  name: Cityworks (Trimble)
  provider: cityworks
  says: lists Cityworks (Trimble) as an integration
  source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-5060.40
    key: geospatial-survey-management
    name: Geospatial & Survey Management
    url: /capabilities/geospatial-survey-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 49.1
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id015
      status: none
    slug: esri
    status: profiled
    tags: &id016
    - GIS
    - Geographic
    - Geospatial
    - Location
    url: /providers/esri/
  layer: domain
  name: Esri ArcGIS
  provider: esri
  says: lists Esri ArcGIS as an integration
  source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1030.50
    key: maintenance-work-order-management
    name: Maintenance Work Order Management
    url: /capabilities/maintenance-work-order-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.6
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id021
      source: https://github.com/IBM/mcp
      status: verified
    slug: ibm
    status: profiled
    tags: &id022
    - API Management
    - Artificial Intelligence
    - Database
    - IBM
    url: /providers/ibm/
  layer: domain
  name: IBM (Maximo)
  provider: ibm
  says: lists IBM (Maximo) as an integration
  source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1030.50
    key: maintenance-work-order-management
    name: Maintenance Work Order Management
    url: /capabilities/maintenance-work-order-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.5
    band: exemplar
    in_catalog: true
    kin_score: 71.0
    mcp: &id023
      status: none
    slug: infor
    status: profiled
    tags: &id024
    - Cloud
    - ERP
    - Manufacturing
    - Supply Chain
    url: /providers/infor/
  layer: domain
  name: Infor
  provider: infor
  says: lists Infor as an integration
  source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3220
    key: citizen-constituent-service-management
    name: Citizen & Constituent Service Management
    url: /capabilities/citizen-constituent-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id025
      source: https://github.com/microsoft/Dataverse-MCP
      status: verified
    slug: microsoft-dynamics-365
    status: profiled
    tags: &id026
    - Business Applications
    - CRM
    - Cloud
    - Enterprise
    url: /providers/microsoft-dynamics-365/
  layer: domain
  name: Microsoft Dynamics
  provider: microsoft-dynamics-365
  says: lists Microsoft Dynamics as an integration
  source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1030.50
    key: maintenance-work-order-management
    name: Maintenance Work Order Management
    url: /capabilities/maintenance-work-order-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 60.1
    band: developing
    in_catalog: true
    kin_score: 48.1
    mcp: &id027
      status: none
    slug: opengov
    status: profiled
    tags: &id028
    - GovTech
    - Government
    - Permitting
    - Public Sector
    url: /providers/opengov/
  layer: domain
  name: OpenGov
  provider: opengov
  says: lists OpenGov as an integration
  source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3220
    key: citizen-constituent-service-management
    name: Citizen & Constituent Service Management
    url: /capabilities/citizen-constituent-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.8
    band: exemplar
    in_catalog: true
    kin_score: 70.4
    mcp: &id029
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id030
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
  layer: domain
  name: Oracle Service Cloud
  provider: oracle
  says: lists Oracle Service Cloud as an integration
  source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1030.50
    key: maintenance-work-order-management
    name: Maintenance Work Order Management
    url: /capabilities/maintenance-work-order-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 6.2
    mcp: &id031
      status: unchecked
    slug: pubworks
    status: profiled
    tags: &id032
    - Cloud
    - Company
    - Municipal
    - Software-as-a-Service
    url: /providers/pubworks/
  layer: domain
  name: PubWorks
  provider: pubworks
  says: lists PubWorks as an integration
  source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3240
    key: permits-licences-authorisations-management
    name: Permits, Licences & Authorisations Management
    url: /capabilities/permits-licences-authorisations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.1
    mcp: &id033
      status: unknown
    slug: tyler-technologies
    status: profiled
    tags: &id034
    - Company
    - Government
    - Public Sector
    - Software
    url: /providers/tyler-technologies/
  layer: domain
  name: Tyler Technologies
  provider: tyler-technologies
  says: lists Tyler Technologies as an integration
  source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3220
    key: citizen-constituent-service-management
    name: Citizen & Constituent Service Management
    url: /capabilities/citizen-constituent-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 7.9
    mcp: &id035
      status: none
    slug: verint-systems
    status: profiled
    tags: &id036
    - Analytics
    - Customer Engagement
    - Security
    url: /providers/verint-systems/
  layer: domain
  name: Verint (KANA Lagan)
  provider: verint-systems
  says: lists Verint (KANA Lagan) as an integration
  source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1030.50
    key: maintenance-work-order-management
    name: Maintenance Work Order Management
    url: /capabilities/maintenance-work-order-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.4
    band: thin
    in_catalog: true
    kin_score: 30.0
    mcp: &id037
      status: unchecked
    slug: vueworks
    status: profiled
    tags: &id038
    - Asset Management
    - Enterprise Software
    - Infrastructure
    - Maintenance Management
    url: /providers/vueworks/
  layer: domain
  name: VUEWorks
  provider: vueworks
  says: lists VUEWorks as an integration
  source: https://www.civicplus.com/seeclickfix-311-crm/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/civic-government-services/seeclickfix-civicplus/
providers:
- agent_band: agent-ready
  agent_readiness: 39.1
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id003
  name: Accela Automation
  slug: accela
  status: profiled
  tags: *id004
  url: /providers/accela/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id005
  name: Amazon Web Services (Mobile Analytics / Amplify)
  slug: amazon-web-services
  status: profiled
  tags: *id006
  url: /providers/amazon-web-services/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 5.1
  mcp: *id007
  name: Bigbelly
  slug: bigbelly
  status: profiled
  tags: *id008
  url: /providers/bigbelly/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id009
  name: Brightly Software
  slug: brightly-software
  status: queued for profiling
  tags: *id010
  url: null
- agent_band: agent-ready
  agent_readiness: 30.5
  band: emerging
  in_catalog: true
  kin_score: 23.3
  mcp: *id011
  name: CentralSquare Technologies
  slug: centralsquare
  status: profiled
  tags: *id012
  url: /providers/centralsquare/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id013
  name: Cityworks (Trimble)
  slug: cityworks
  status: queued for profiling
  tags: *id014
  url: null
- agent_band: agent-ready
  agent_readiness: 49.1
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id015
  name: Esri ArcGIS
  slug: esri
  status: profiled
  tags: *id016
  url: /providers/esri/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id017
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id018
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id019
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id020
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 35.6
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id021
  name: IBM (Maximo)
  slug: ibm
  status: profiled
  tags: *id022
  url: /providers/ibm/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: exemplar
  in_catalog: true
  kin_score: 71.0
  mcp: *id023
  name: Infor
  slug: infor
  status: profiled
  tags: *id024
  url: /providers/infor/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id025
  name: Microsoft Dynamics
  slug: microsoft-dynamics-365
  status: profiled
  tags: *id026
  url: /providers/microsoft-dynamics-365/
- agent_band: agent-native
  agent_readiness: 60.1
  band: developing
  in_catalog: true
  kin_score: 48.1
  mcp: *id027
  name: OpenGov
  slug: opengov
  status: profiled
  tags: *id028
  url: /providers/opengov/
- agent_band: agent-ready
  agent_readiness: 59.8
  band: exemplar
  in_catalog: true
  kin_score: 70.4
  mcp: *id029
  name: Oracle Service Cloud
  slug: oracle
  status: profiled
  tags: *id030
  url: /providers/oracle/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 6.2
  mcp: *id031
  name: PubWorks
  slug: pubworks
  status: profiled
  tags: *id032
  url: /providers/pubworks/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.1
  mcp: *id033
  name: Tyler Technologies
  slug: tyler-technologies
  status: profiled
  tags: *id034
  url: /providers/tyler-technologies/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 7.9
  mcp: *id035
  name: Verint (KANA Lagan)
  slug: verint-systems
  status: profiled
  tags: *id036
  url: /providers/verint-systems/
- agent_band: agent-aware
  agent_readiness: 14.4
  band: thin
  in_catalog: true
  kin_score: 30.0
  mcp: *id037
  name: VUEWorks
  slug: vueworks
  status: profiled
  tags: *id038
  url: /providers/vueworks/
siblings:
- name: Accela Civic Platform
  rows: 4
  url: /applications/civic-government-services/accela-civic-platform/
- name: Alaveteli
  rows: 4
  url: /applications/civic-government-services/alaveteli/
- name: CONSUL Democracy
  rows: 5
  url: /applications/civic-government-services/consul-democracy/
- name: Decidim
  rows: 7
  url: /applications/civic-government-services/decidim/
- name: FixMyStreet
  rows: 8
  url: /applications/civic-government-services/fixmystreet/
- name: Go Vocal (CitizenLab)
  rows: 10
  url: /applications/civic-government-services/go-vocal-citizenlab/
- name: Granicus (govDelivery)
  rows: 1
  url: /applications/civic-government-services/granicus-govdelivery/
sitemap: true
title: 'SeeClickFix (CivicPlus): Civic & Government Services reference app'
---
