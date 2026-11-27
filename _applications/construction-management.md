---
access: understanding
agent_layer: []
apps:
- anchor: procore
  counts:
    declared: 10
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.procore.activities/latest/
  - route: documentation
    url: https://v2.support.procore.com/en-au/product-manuals/bluebeam/
  - route: documentation
    url: https://v2.support.procore.com/en-au/product-manuals/cmic/
  - route: documentation
    url: https://v2.support.procore.com/en-au/product-manuals/docusign/
  - route: documentation
    url: https://v2.support.procore.com/en-au/product-manuals/microsoft-project/
  - route: documentation
    url: https://v2.support.procore.com/en-au/product-manuals/netsuite/
  - route: documentation
    url: https://v2.support.procore.com/en-au/product-manuals/quickbooks-desktop/
  - route: documentation
    url: https://v2.support.procore.com/en-au/product-manuals/sage-100/
  - route: documentation
    url: https://v2.support.procore.com/en-au/product-manuals/sage-300-cre/
  - route: documentation
    url: https://v2.support.procore.com/en-au/product-manuals/sage-intacct/
  - route: documentation
    url: https://v2.support.procore.com/en-au/product-manuals/viewpoint-spectrum/
  - route: documentation
    url: https://v2.support.procore.com/en-au/product-manuals/xero/
  - route: integrations page
    url: https://marketplace.procore.com/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google CrashLytics
    provider: firebase
    says: ships the Google CrashLytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.procore.activities/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.procore.activities/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1130
      key: engineering-document-management
      name: Engineering Document Management
      url: /capabilities/engineering-document-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bluebeam
    provider: bluebeam
    says: lists Bluebeam as an integration
    source: https://v2.support.procore.com/en-au/product-manuals/bluebeam/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: CMiC
    provider: cmic
    says: lists CMiC as an integration
    source: https://v2.support.procore.com/en-au/product-manuals/cmic/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10
      key: contract-management
      name: Contract Management
      url: /capabilities/contract-management/
      via_parent: null
    credit: null
    layer: common
    name: DocuSign
    provider: docusign
    says: lists DocuSign as an integration
    source: https://v2.support.procore.com/en-au/product-manuals/docusign/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Project
    provider: microsoft-project
    says: lists Microsoft Project as an integration
    source: https://v2.support.procore.com/en-au/product-manuals/microsoft-project/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Oracle NetSuite
    provider: netsuite
    says: lists Oracle NetSuite as an integration
    source: https://v2.support.procore.com/en-au/product-manuals/netsuite/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: QuickBooks Desktop
    provider: quickbooks
    says: lists QuickBooks Desktop as an integration
    source: https://v2.support.procore.com/en-au/product-manuals/quickbooks-desktop/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Sage 100 Contractor
    provider: sage
    says: lists Sage 100 Contractor as an integration
    source: https://v2.support.procore.com/en-au/product-manuals/sage-100/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Sage Intacct
    provider: sage-intacct
    says: lists Sage Intacct as an integration
    source: https://v2.support.procore.com/en-au/product-manuals/sage-intacct/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Viewpoint Spectrum (Trimble)
    provider: trimble
    says: lists Viewpoint Spectrum (Trimble) as an integration
    source: https://v2.support.procore.com/en-au/product-manuals/viewpoint-spectrum/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: Xero
    provider: xero
    says: lists Xero as an integration
    source: https://v2.support.procore.com/en-au/product-manuals/xero/
    tier: declared
  kind: commercial
  name: Procore
  page: /applications/construction-management/procore/
  slug: procore
  url: https://www.procore.com/
- anchor: raken
  counts:
    declared: 21
    observed: 0
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
    layer: common
    name: Viewpoint Vista / Viewpoint Spectrum
    provider: trimble
    says: lists Viewpoint Vista / Viewpoint Spectrum as an integration
    source: https://www.rakenapp.com/integrations
    tier: declared
  kind: commercial
  name: Raken
  page: /applications/construction-management/raken/
  slug: raken
  url: https://www.rakenapp.com/
- anchor: jobtread
  counts:
    declared: 11
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.jobtread.com/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.20
      key: AE-120.20.20
      name: Satellite & Aerial Imagery
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: domain
    name: Eagleview
    provider: eagleview
    says: lists Eagleview as an integration
    source: https://www.jobtread.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: common
    name: Gusto
    provider: gusto
    says: lists Gusto as an integration
    source: https://www.jobtread.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-500.30
      key: purchase-order-management
      name: Purchase Order Management
      url: /capabilities/purchase-order-management/
      via_parent: null
    credit: null
    layer: domain
    name: Heritage Pool Supply Group
    provider: heritage-pool-supply
    says: lists Heritage Pool Supply Group as an integration
    source: https://www.jobtread.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-500.30
      key: purchase-order-management
      name: Purchase Order Management
      url: /capabilities/purchase-order-management/
      via_parent: null
    credit: null
    layer: domain
    name: Home Depot
    provider: home-depot
    says: lists Home Depot as an integration
    source: https://www.jobtread.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: common
    name: NiceJob
    provider: nicejob
    says: lists NiceJob as an integration
    source: https://www.jobtread.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-500.30
      key: purchase-order-management
      name: Purchase Order Management
      url: /capabilities/purchase-order-management/
      via_parent: null
    credit: null
    layer: domain
    name: PoolCorp
    provider: poolcorp
    says: lists PoolCorp as an integration
    source: https://www.jobtread.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: QuickBooks Online
    provider: quickbooks
    says: lists QuickBooks Online as an integration
    source: https://www.jobtread.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-500.30
      key: purchase-order-management
      name: Purchase Order Management
      url: /capabilities/purchase-order-management/
      via_parent: null
    credit: null
    layer: domain
    name: QXO
    provider: qxo-building-products
    says: lists QXO as an integration
    source: https://www.jobtread.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-5060.40.30
      key: BC-5060.40.30
      name: Reality Capture & Scanning
      url: /capabilities/geospatial-survey-management/
      via_parent: Geospatial & Survey Management
    credit: null
    layer: domain
    name: RENDR
    provider: rendr
    says: lists RENDR as an integration
    source: https://www.jobtread.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-500.30
      key: purchase-order-management
      name: Purchase Order Management
      url: /capabilities/purchase-order-management/
      via_parent: null
    credit: null
    layer: domain
    name: SRS Distribution
    provider: srs-distribution
    says: lists SRS Distribution as an integration
    source: https://www.jobtread.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://www.jobtread.com/integrations
    tier: declared
  kind: commercial
  name: JobTread
  page: /applications/construction-management/jobtread/
  slug: jobtread
  url: https://www.jobtread.com/
- anchor: companycam
  counts:
    declared: 15
    observed: 0
  evidence:
  - route: integrations page
    url: https://companycam.com/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: AccuLynx
    provider: acculynx
    says: lists AccuLynx as an integration
    source: https://companycam.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Aspire (Powered by MindCloud)
    provider: aspire-software
    says: lists Aspire (Powered by MindCloud) as an integration
    source: https://companycam.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.20
      key: AE-120.20.20
      name: Satellite & Aerial Imagery
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: domain
    name: Eagleview
    provider: eagleview
    says: lists Eagleview as an integration
    source: https://companycam.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HighLevel
    provider: highlevel
    says: lists HighLevel as an integration
    source: https://companycam.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1050
      key: field-service-management
      name: Field Service Management
      url: /capabilities/field-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jobber
    provider: jobber
    says: lists Jobber as an integration
    source: https://companycam.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: JobNimbus
    provider: jobnimbus
    says: lists JobNimbus as an integration
    source: https://companycam.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1150
      key: construction-management
      name: Construction Management
      url: /capabilities/construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: JobTread
    provider: jobtread
    says: lists JobTread as an integration
    source: https://companycam.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: LeadPerfection
    provider: leadperfection
    says: lists LeadPerfection as an integration
    source: https://companycam.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Leap
    provider: leap-to-digital
    says: lists Leap as an integration
    source: https://companycam.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: QuickBooks Online
    provider: quickbooks
    says: lists QuickBooks Online as an integration
    source: https://companycam.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Roofr
    provider: roofr
    says: lists Roofr as an integration
    source: https://companycam.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1050
      key: field-service-management
      name: Field Service Management
      url: /capabilities/field-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: ServiceTitan
    provider: servicetitan
    says: lists ServiceTitan as an integration
    source: https://companycam.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Smartsheet
    provider: smartsheet
    says: lists Smartsheet as an integration
    source: https://companycam.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-500.30
      key: purchase-order-management
      name: Purchase Order Management
      url: /capabilities/purchase-order-management/
      via_parent: null
    credit: null
    layer: domain
    name: SRS Roof Hub
    provider: srs-distribution
    says: lists SRS Roof Hub as an integration
    source: https://companycam.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://companycam.com/integrations
    tier: declared
  kind: commercial
  name: CompanyCam
  page: /applications/construction-management/companycam/
  slug: companycam
  url: https://companycam.com/
- anchor: knowify
  counts:
    declared: 9
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.knowify.com/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-150.10
      key: contract-management
      name: Contract Management
      url: /capabilities/contract-management/
      via_parent: null
    credit: null
    layer: domain
    name: AIA Contract Documents
    provider: aia-contract-documents
    says: lists AIA Contract Documents as an integration
    source: https://www.knowify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1350.40
      key: BC-1350.40
      name: Supply Chain Finance Management
      url: /capabilities/supply-chain-finance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Billd
    provider: billd
    says: lists Billd as an integration
    source: https://www.knowify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: domain
    name: CompanyCam
    provider: companycam
    says: lists CompanyCam as an integration
    source: https://www.knowify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.80.40
      key: BC-300.80.40
      name: Employment Law Compliance
      url: /capabilities/employee-labour-relations/
      via_parent: Employee & Labour Relations
    credit: null
    layer: domain
    name: eBacon
    provider: ebacon
    says: lists eBacon as an integration
    source: https://www.knowify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.80.40
      key: BC-300.80.40
      name: Employment Law Compliance
      url: /capabilities/employee-labour-relations/
      via_parent: Employee & Labour Relations
    credit: null
    layer: domain
    name: Lumber
    provider: lumber
    says: lists Lumber as an integration
    source: https://www.knowify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: QuickBooks Online / Desktop / Enterprise Suite
    provider: quickbooks
    says: lists QuickBooks Online / Desktop / Enterprise Suite as an integration
    source: https://www.knowify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: common
    name: QuickBooks Online Payroll / QuickBooks Time
    provider: quickbooks
    says: lists QuickBooks Online Payroll / QuickBooks Time as an integration
    source: https://www.knowify.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.30
      key: accounts-receivable-management
      name: Accounts Receivable Management
      url: /capabilities/accounts-receivable-management/
      via_parent: null
    credit: null
    layer: common
    name: QuickBooks Payments
    provider: quickbooks
    says: lists QuickBooks Payments as an integration
    source: https://www.knowify.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://www.knowify.com/integrations
    tier: declared
  kind: commercial
  name: Knowify
  page: /applications/construction-management/knowify/
  slug: knowify
  url: https://www.knowify.com/
- anchor: siteline
  counts:
    declared: 11
    observed: 0
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
    layer: common
    name: Viewpoint Vista / Viewpoint Spectrum
    provider: trimble
    says: lists Viewpoint Vista / Viewpoint Spectrum as an integration
    source: https://www.siteline.com/integrations
    tier: declared
  kind: commercial
  name: Siteline
  page: /applications/construction-management/siteline/
  slug: siteline
  url: https://www.siteline.com/
- anchor: openproject-(bim)
  counts:
    declared: 7
    observed: 0
  evidence:
  - route: documentation
    url: https://www.openproject.org/bim-project-management/
  - route: documentation
    url: https://www.openproject.org/docs/system-admin-guide/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: common
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://www.openproject.org/docs/system-admin-guide/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: common
    name: GitLab
    provider: gitlab
    says: lists GitLab as an integration
    source: https://www.openproject.org/docs/system-admin-guide/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Nextcloud
    provider: nextcloud
    says: lists Nextcloud as an integration
    source: https://www.openproject.org/docs/system-admin-guide/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: OneDrive
    provider: microsoft-onedrive
    says: lists OneDrive as an integration
    source: https://www.openproject.org/docs/system-admin-guide/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1120.50
      key: design-software-cad-management
      name: Design Software & CAD Management
      url: /capabilities/design-software-cad-management/
      via_parent: null
    credit: null
    layer: domain
    name: Revit (add-in)
    provider: autodesk
    says: lists Revit (add-in) as an integration
    source: https://www.openproject.org/bim-project-management/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-917
      key: AE-917
      name: Enterprise Content & Document Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: SharePoint
    provider: sharepoint
    says: lists SharePoint as an integration
    source: https://www.openproject.org/docs/system-admin-guide/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    credit: null
    layer: common
    name: XWiki
    provider: xwiki
    says: lists XWiki as an integration
    source: https://www.openproject.org/docs/system-admin-guide/integrations/
    tier: declared
  kind: self-hosted
  name: OpenProject (BIM)
  page: /applications/construction-management/openproject-bim/
  slug: openproject-bim
  url: https://www.openproject.org/bim-project-management/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: construction-management
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Manufacturing
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
name: Construction Management
needs:
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by Procore, Raken, JobTread, CompanyCam, Knowify, Siteline
- capability:
    attribution: Turbo EA
    id: BC-150.10
    key: contract-management
    name: Contract Management
    url: /capabilities/contract-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by Procore, Knowify
- capability:
    attribution: Turbo EA
    id: BC-1130
    key: engineering-document-management
    name: Engineering Document Management
    url: /capabilities/engineering-document-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Procore, Raken
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Procore, CompanyCam
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by Raken, JobTread, Knowify
- capability:
    attribution: Turbo EA
    id: BC-1150
    key: construction-management
    name: Construction Management
    url: /capabilities/construction-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Raken, CompanyCam
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: named by Raken, OpenProject (BIM)
- capability:
    attribution: Turbo EA
    id: BC-1150.60
    key: construction-progress-management
    name: Construction Progress Management
    url: /capabilities/construction-progress-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Raken
- capability:
    attribution: Turbo EA
    id: BC-500.30
    key: purchase-order-management
    name: Purchase Order Management
    url: /capabilities/purchase-order-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by JobTread, CompanyCam
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.20
    key: AE-120.20.20
    name: Satellite & Aerial Imagery
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: domain
  why: named by JobTread, CompanyCam
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: named by JobTread, CompanyCam, Knowify
- capability:
    attribution: Turbo EA
    id: BC-1120.50
    key: design-software-cad-management
    name: Design Software & CAD Management
    url: /capabilities/design-software-cad-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: named by JobTread, OpenProject (BIM)
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  fit: exact
  layer: common
  why: named by JobTread
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by CompanyCam
- capability:
    attribution: Turbo EA
    id: BC-1050
    key: field-service-management
    name: Field Service Management
    url: /capabilities/field-service-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by CompanyCam
- capability:
    attribution: Turbo EA
    id: BC-200.30
    key: accounts-receivable-management
    name: Accounts Receivable Management
    url: /capabilities/accounts-receivable-management/
    via_parent: null
  fit: nearest
  layer: common
  why: named by Knowify, Siteline
- capability:
    attribution: Turbo EA
    id: BC-1350.40
    key: BC-1350.40
    name: Supply Chain Finance Management
    url: /capabilities/supply-chain-finance-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Knowify
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Knowify
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by OpenProject (BIM)
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by OpenProject (BIM)
- capability:
    attribution: API Evangelist extension
    id: AE-917
    key: AE-917
    name: Enterprise Content & Document Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: common
  why: named by OpenProject (BIM)
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash and error reporting SDKs seen in the Android builds
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: usage analytics SDKs seen in the Android builds
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.5
      apps:
      - CompanyCam
      band: exemplar
      in_catalog: true
      kin_score: 66.9
      mcp:
        source: https://marketplace.gohighlevel.com/docs/other/mcp/index.html
        status: verified
      name: HighLevel
      slug: highlevel
      sources:
      - https://companycam.com/integrations
      status: profiled
      tags:
      - CRM
      - Company
      - Marketing
      - Software-as-a-Service
      tier: declared
      url: /providers/highlevel/
    - agent_band: agent-ready
      agent_readiness: 51.8
      apps:
      - CompanyCam
      band: strong
      in_catalog: true
      kin_score: 64.7
      mcp:
        status: none
      name: AccuLynx
      slug: acculynx
      sources:
      - https://companycam.com/integrations
      status: profiled
      tags:
      - CRM
      - Company
      - Roofing
      - Software-as-a-Service
      tier: declared
      url: /providers/acculynx/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - CompanyCam
      band: thin
      in_catalog: true
      kin_score: 27.7
      mcp:
        status: unknown
      name: Aspire (Powered by MindCloud)
      slug: aspire-software
      sources:
      - https://companycam.com/integrations
      status: profiled
      tags:
      - Automation
      - Company
      - Field Service Management
      - Software
      tier: declared
      url: /providers/aspire-software/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - CompanyCam
      band: emerging
      in_catalog: true
      kin_score: 25.3
      mcp:
        status: unknown
      name: Leap
      slug: leap-to-digital
      sources:
      - https://companycam.com/integrations
      status: profiled
      tags:
      - Company
      - Contractor Software
      - Remodeling
      - Roofing
      tier: declared
      url: /providers/leap-to-digital/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - CompanyCam
      band: emerging
      in_catalog: true
      kin_score: 15.2
      mcp:
        status: unknown
      name: JobNimbus
      slug: jobnimbus
      sources:
      - https://companycam.com/integrations
      status: profiled
      tags:
      - CRM
      - Contractors
      - Project Management
      - Roofing
      tier: declared
      url: /providers/jobnimbus/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - CompanyCam
      band: emerging
      in_catalog: true
      kin_score: 14.6
      mcp:
        status: unknown
      name: Roofr
      slug: roofr
      sources:
      - https://companycam.com/integrations
      status: profiled
      tags:
      - Company
      - Construction
      - Roofing
      - Software-as-a-Service
      tier: declared
      url: /providers/roofr/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - CompanyCam
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        status: unknown
      name: LeadPerfection
      slug: leadperfection
      sources:
      - https://companycam.com/integrations
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/leadperfection/
  - capability:
      attribution: Turbo EA
      id: BC-500.30
      key: purchase-order-management
      name: Purchase Order Management
      url: /capabilities/purchase-order-management/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - CompanyCam
      - JobTread
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: SRS Distribution
      slug: srs-distribution
      sources:
      - https://companycam.com/integrations
      - https://www.jobtread.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: agent-aware
      agent_readiness: 20.2
      apps:
      - JobTread
      band: emerging
      in_catalog: true
      kin_score: 25.0
      mcp:
        status: none
      name: Home Depot
      slug: home-depot
      sources:
      - https://www.jobtread.com/integrations
      status: profiled
      tags:
      - Fortune 100
      tier: declared
      url: /providers/home-depot/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - JobTread
      band: minimal
      in_catalog: true
      kin_score: 10.2
      mcp:
        status: unknown
      name: QXO
      slug: qxo-building-products
      sources:
      - https://www.jobtread.com/integrations
      status: profiled
      tags:
      - B2B
      - Building Products
      - Construction
      - Distribution
      tier: declared
      url: /providers/qxo-building-products/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - JobTread
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        status: unknown
      name: PoolCorp
      slug: poolcorp
      sources:
      - https://www.jobtread.com/integrations
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/poolcorp/
    - agent_band: null
      agent_readiness: null
      apps:
      - JobTread
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Heritage Pool Supply Group
      slug: heritage-pool-supply
      sources:
      - https://www.jobtread.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-1150.60
      key: construction-progress-management
      name: Construction Progress Management
      url: /capabilities/construction-progress-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 16.8
      apps:
      - Raken
      band: thin
      in_catalog: true
      kin_score: 31.9
      mcp:
        status: unknown
      name: DroneDeploy
      slug: dronedeploy
      sources:
      - https://www.rakenapp.com/integrations
      status: profiled
      tags:
      - Aerial Analytics
      - Drone Mapping
      - Geospatial
      - Reality Capture
      tier: declared
      url: /providers/dronedeploy/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Raken
      band: emerging
      in_catalog: true
      kin_score: 23.8
      mcp:
        status: none
      name: TrueLook
      slug: truelook
      sources:
      - https://www.rakenapp.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Construction
      - Security
      - Video
      tier: declared
      url: /providers/truelook/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Raken
      band: emerging
      in_catalog: true
      kin_score: 16.7
      mcp:
        status: unknown
      name: EarthCam
      slug: earthcam
      sources:
      - https://www.rakenapp.com/integrations
      status: profiled
      tags:
      - Company
      - Construction
      - Webcam
      - visual-data
      tier: declared
      url: /providers/earthcam/
    - agent_band: null
      agent_readiness: null
      apps:
      - Raken
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: HoloBuilder
      slug: holobuilder
      sources:
      - https://www.rakenapp.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-1150
      key: construction-management
      name: Construction Management
      url: /capabilities/construction-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Raken
      band: exemplar
      in_catalog: true
      kin_score: 69.0
      mcp:
        source: https://github.com/autodesk-platform-services/aps-mcp-server-nodejs
        status: verified
      name: Autodesk
      slug: autodesk-construction-cloud
      sources:
      - https://www.rakenapp.com/integrations
      status: profiled
      tags:
      - AEC
      - BIM
      - Construction
      - Project Management
      tier: declared
      url: /providers/autodesk-construction-cloud/
    - agent_band: agent-ready
      agent_readiness: 36.1
      apps:
      - Raken
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp: &id001
        status: none
      name: Procore
      slug: procore
      sources:
      - https://www.rakenapp.com/integrations
      status: profiled
      tags: &id002
      - Construction
      - Construction Management
      - Field Productivity
      - Project Management
      tier: declared
      url: /providers/procore/
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - CompanyCam
      band: emerging
      in_catalog: true
      kin_score: 25.0
      mcp:
        status: none
      name: JobTread
      slug: jobtread
      sources:
      - https://companycam.com/integrations
      status: profiled
      tags:
      - Construction
      - Estimating
      - Project Management
      - Software-as-a-Service
      tier: declared
      url: /providers/jobtread/
  - capability:
      attribution: Turbo EA
      id: BC-300.80.40
      key: BC-300.80.40
      name: Employment Law Compliance
      url: /capabilities/employee-labour-relations/
      via_parent: Employee & Labour Relations
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Knowify
      band: emerging
      in_catalog: true
      kin_score: 14.5
      mcp:
        status: unknown
      name: Lumber
      slug: lumber
      sources:
      - https://www.knowify.com/integrations
      status: profiled
      tags:
      - Company
      - Construction
      - Payroll
      - Workforce Management
      tier: declared
      url: /providers/lumber/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Knowify
      band: minimal
      in_catalog: true
      kin_score: 10.2
      mcp:
        status: unknown
      name: eBacon
      slug: ebacon
      sources:
      - https://www.knowify.com/integrations
      status: profiled
      tags:
      - Compliance
      - Construction
      - Payroll
      - Software
      tier: declared
      url: /providers/ebacon/
    - agent_band: null
      agent_readiness: null
      apps:
      - Raken
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Points North
      slug: points-north
      sources:
      - https://www.rakenapp.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-1130
      key: engineering-document-management
      name: Engineering Document Management
      url: /capabilities/engineering-document-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.3
      apps:
      - Procore
      - Raken
      band: thin
      in_catalog: true
      kin_score: 33.7
      mcp:
        status: none
      name: Bluebeam
      slug: bluebeam
      sources:
      - https://v2.support.procore.com/en-au/product-manuals/bluebeam/
      - https://www.rakenapp.com/integrations
      status: profiled
      tags:
      - Construction
      - Documents
      - PDF
      - Project Management
      tier: declared
      url: /providers/bluebeam/
  - capability:
      attribution: Turbo EA
      id: BC-1050
      key: field-service-management
      name: Field Service Management
      url: /capabilities/field-service-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.3
      apps:
      - CompanyCam
      band: strong
      in_catalog: true
      kin_score: 54.3
      mcp:
        status: none
      name: ServiceTitan
      slug: servicetitan
      sources:
      - https://companycam.com/integrations
      status: profiled
      tags:
      - Field Service Management
      - HVAC
      - Plumbing
      - Trade
      tier: declared
      url: /providers/servicetitan/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - CompanyCam
      band: developing
      in_catalog: true
      kin_score: 52.1
      mcp:
        source: https://github.com/GetJobber/grok-bot-mcp
        status: verified
      name: Jobber
      slug: jobber
      sources:
      - https://companycam.com/integrations
      status: profiled
      tags:
      - Field Service Management
      - Home Service
      - Quoting
      - Scheduling
      tier: declared
      url: /providers/jobber/
  - capability:
      attribution: Turbo EA
      id: BC-5030.40.20
      key: BC-5030.40.20
      name: Interim Valuation Management
      url: /capabilities/commercial-quantity-surveying/
      via_parent: Commercial & Quantity Surveying
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.8
      apps:
      - Siteline
      band: exemplar
      in_catalog: true
      kin_score: 70.4
      mcp:
        source: https://github.com/oracle/mcp
        status: verified
      name: Oracle Textura
      slug: oracle
      sources:
      - https://www.siteline.com/integrations
      status: profiled
      tags:
      - Cloud
      - Database
      - Enterprise
      - Oracle
      tier: declared
      url: /providers/oracle/
    - agent_band: agent-ready
      agent_readiness: 36.1
      apps:
      - Siteline
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp: *id001
      name: Procore Pay
      slug: procore
      sources:
      - https://www.siteline.com/integrations
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/procore/
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.5
      apps:
      - Procore
      band: strong
      in_catalog: true
      kin_score: 56.3
      mcp:
        status: none
      name: Microsoft Project
      slug: microsoft-project
      sources:
      - https://v2.support.procore.com/en-au/product-manuals/microsoft-project/
      status: profiled
      tags:
      - Budgeting
      - Gantt Charts
      - Microsoft
      - Project Management
      tier: declared
      url: /providers/microsoft-project/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - CompanyCam
      band: developing
      in_catalog: true
      kin_score: 41.4
      mcp:
        source: https://github.com/smartsheet-platform/smar-mcp
        status: verified
      name: Smartsheet
      slug: smartsheet
      sources:
      - https://companycam.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: declared
      url: /providers/smartsheet/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.20
      key: AE-120.20.20
      name: Satellite & Aerial Imagery
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.6
      apps:
      - CompanyCam
      - JobTread
      band: developing
      in_catalog: true
      kin_score: 52.2
      mcp:
        status: none
      name: Eagleview
      slug: eagleview
      sources:
      - https://companycam.com/integrations
      - https://www.jobtread.com/integrations
      status: profiled
      tags:
      - Aerial Imagery
      - Data Analytics
      - Geospatial
      - Real Estate
      tier: declared
      url: /providers/eagleview/
  - capability:
      attribution: Turbo EA
      id: BC-150.10
      key: contract-management
      name: Contract Management
      url: /capabilities/contract-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Knowify
      band: emerging
      in_catalog: true
      kin_score: 20.3
      mcp:
        status: unknown
      name: AIA Contract Documents
      slug: aia-contract-documents
      sources:
      - https://www.knowify.com/integrations
      status: profiled
      tags:
      - Architecture
      - Company
      - Construction
      - Contracts
      tier: declared
      url: /providers/aia-contract-documents/
  - capability:
      attribution: Turbo EA
      id: BC-1120.50
      key: design-software-cad-management
      name: Design Software & CAD Management
      url: /capabilities/design-software-cad-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.0
      apps:
      - OpenProject (BIM)
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        source: https://github.com/autodesk-platform-services/aps-mcp-server-nodejs
        status: verified
      name: Revit (add-in)
      slug: autodesk
      sources:
      - https://www.openproject.org/bim-project-management/
      status: profiled
      tags:
      - 3D Modeling
      - Autodesk
      - Digital Twin
      - Fortune 1000
      tier: declared
      url: /providers/autodesk/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - Knowify
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: CompanyCam
      slug: companycam
      sources:
      - https://www.knowify.com/integrations
      status: profiled
      tags:
      - Company
      - Construction
      - Field Service Management
      - Photos
      tier: declared
      url: /providers/companycam/
  - capability:
      attribution: Turbo EA
      id: BC-5060.40.30
      key: BC-5060.40.30
      name: Reality Capture & Scanning
      url: /capabilities/geospatial-survey-management/
      via_parent: Geospatial & Survey Management
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - JobTread
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: RENDR
      slug: rendr
      sources:
      - https://www.jobtread.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-1350.40
      key: BC-1350.40
      name: Supply Chain Finance Management
      url: /capabilities/supply-chain-finance-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Knowify
      band: emerging
      in_catalog: true
      kin_score: 19.0
      mcp:
        status: unknown
      name: Billd
      slug: billd
      sources:
      - https://www.knowify.com/integrations
      status: profiled
      tags:
      - Construction
      - Financing
      - Subcontractors
      - Working Capital
      tier: declared
      url: /providers/billd/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - CompanyCam
      - JobTread
      - Knowify
      - Procore
      - Raken
      - Siteline
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp: &id003
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks Desktop
      slug: quickbooks
      sources:
      - https://companycam.com/integrations
      - https://v2.support.procore.com/en-au/product-manuals/quickbooks-desktop/
      - https://www.jobtread.com/integrations
      status: profiled
      tags: &id004
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Procore
      - Raken
      - Siteline
      band: exemplar
      in_catalog: true
      kin_score: 66.6
      mcp:
        status: none
      name: Viewpoint Spectrum (Trimble)
      slug: trimble
      sources:
      - https://v2.support.procore.com/en-au/product-manuals/viewpoint-spectrum/
      - https://www.rakenapp.com/integrations
      - https://www.siteline.com/integrations
      status: profiled
      tags:
      - Construction
      - GPS
      - Geospatial
      - Transportation
      tier: declared
      url: /providers/trimble/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Procore
      - Raken
      - Siteline
      band: developing
      in_catalog: true
      kin_score: 41.7
      mcp:
        status: none
      name: Sage 100 Contractor
      slug: sage
      sources:
      - https://v2.support.procore.com/en-au/product-manuals/sage-100/
      - https://www.rakenapp.com/integrations
      - https://www.siteline.com/integrations
      status: profiled
      tags:
      - Accounting
      - Business Management
      - Cloud Software
      - ERP
      tier: declared
      url: /providers/sage/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Procore
      - Raken
      - Siteline
      band: thin
      in_catalog: true
      kin_score: 37.7
      mcp:
        status: unknown
      name: CMiC
      slug: cmic
      sources:
      - https://v2.support.procore.com/en-au/product-manuals/cmic/
      - https://www.rakenapp.com/integrations
      - https://www.siteline.com/integrations
      status: profiled
      tags:
      - Construction
      - ERP
      - Finance
      - Project Management
      tier: declared
      url: /providers/cmic/
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - Procore
      - Raken
      - Siteline
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: Sage Intacct
      slug: sage-intacct
      sources:
      - https://v2.support.procore.com/en-au/product-manuals/sage-intacct/
      - https://www.rakenapp.com/integrations
      - https://www.siteline.com/integrations
      status: profiled
      tags:
      - Accounting
      - ERP
      - Financial Management
      - General Ledger
      tier: declared
      url: /providers/sage-intacct/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Raken
      - Siteline
      band: emerging
      in_catalog: true
      kin_score: 20.5
      mcp:
        source: https://learning.deltek.com/bundle/MCP_Server_Setup_Guide_for_REST_APIs/page/overview.html
        status: documented
      name: Deltek ComputerEase
      slug: deltek
      sources:
      - https://www.rakenapp.com/integrations
      - https://www.siteline.com/integrations
      status: profiled
      tags:
      - Company
      - Enterprise
      - Project Management
      - Software
      tier: declared
      url: /providers/deltek/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Raken
      - Siteline
      band: emerging
      in_catalog: true
      kin_score: 19.9
      mcp:
        status: unknown
      name: Foundation
      slug: foundation-software
      sources:
      - https://www.rakenapp.com/integrations
      - https://www.siteline.com/integrations
      status: profiled
      tags:
      - Accounting
      - Construction
      - Contractors
      - Software
      tier: declared
      url: /providers/foundation-software/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Procore
      - Siteline
      band: emerging
      in_catalog: true
      kin_score: 11.4
      mcp:
        status: none
      name: Oracle NetSuite
      slug: netsuite
      sources:
      - https://v2.support.procore.com/en-au/product-manuals/netsuite/
      - https://www.siteline.com/integrations
      status: profiled
      tags:
      - Accounting
      - CRM
      - ERP
      - Finance
      tier: declared
      url: /providers/netsuite/
    - agent_band: agent-native
      agent_readiness: 60.0
      apps:
      - Procore
      band: exemplar
      in_catalog: true
      kin_score: 87.1
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://v2.support.procore.com/en-au/product-manuals/xero/
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: declared
      url: /providers/xero/
    - agent_band: agent-aware
      agent_readiness: 13.3
      apps:
      - Siteline
      band: emerging
      in_catalog: true
      kin_score: 17.1
      mcp:
        status: none
      name: Acumatica
      slug: acumatica
      sources:
      - https://www.siteline.com/integrations
      status: profiled
      tags:
      - Cloud ERP
      - ERP
      - Financial Management
      - Inventory
      tier: declared
      url: /providers/acumatica/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - OpenProject (BIM)
      - Raken
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        status: none
      name: OneDrive
      slug: microsoft-onedrive
      sources:
      - https://www.openproject.org/docs/system-admin-guide/integrations/
      - https://www.rakenapp.com/integrations
      status: profiled
      tags:
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: declared
      url: /providers/microsoft-onedrive/
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Raken
      band: exemplar
      in_catalog: true
      kin_score: 73.2
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://www.rakenapp.com/integrations
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: declared
      url: /providers/google-drive/
    - agent_band: agent-ready
      agent_readiness: 56.6
      apps:
      - Raken
      band: strong
      in_catalog: true
      kin_score: 63.0
      mcp:
        source: https://developer.box.com/guides/box-mcp/
        status: verified
      name: Box
      slug: box
      sources:
      - https://www.rakenapp.com/integrations
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Content Management
      - Documents
      tier: declared
      url: /providers/box/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Raken
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://www.rakenapp.com/integrations
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: declared
      url: /providers/dropbox/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - OpenProject (BIM)
      band: thin
      in_catalog: true
      kin_score: 32.7
      mcp:
        status: none
      name: Nextcloud
      slug: nextcloud
      sources:
      - https://www.openproject.org/docs/system-admin-guide/integrations/
      status: profiled
      tags:
      - Collaboration
      - File Sharing
      - File Sync
      - Self-Hosted
      tier: declared
      url: /providers/nextcloud/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Raken
      band: thin
      in_catalog: true
      kin_score: 29.5
      mcp:
        source: https://github.com/egnyte/egnyte-mcp-server
        status: verified
      name: Egnyte
      slug: egnyte
      sources:
      - https://www.rakenapp.com/integrations
      status: profiled
      tags:
      - Content Collaboration
      - Document Management
      - Enterprise Storage
      - File Sharing
      tier: declared
      url: /providers/egnyte/
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Knowify
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp: *id003
      name: QuickBooks Online Payroll / QuickBooks Time
      slug: quickbooks
      sources:
      - https://www.knowify.com/integrations
      status: profiled
      tags: *id004
      tier: declared
      url: /providers/quickbooks/
    - agent_band: agent-ready
      agent_readiness: 31.7
      apps:
      - JobTread
      band: developing
      in_catalog: true
      kin_score: 44.9
      mcp:
        status: none
      name: Gusto
      slug: gusto
      sources:
      - https://www.jobtread.com/integrations
      status: profiled
      tags:
      - Benefits
      - Enterprise Software
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/gusto/
    - agent_band: agent-ready
      agent_readiness: 29.3
      apps:
      - Raken
      band: thin
      in_catalog: true
      kin_score: 37.8
      mcp:
        status: none
      name: Paychex
      slug: paychex-developer
      sources:
      - https://www.rakenapp.com/integrations
      status: profiled
      tags:
      - Benefits
      - HCM
      - Human Resources
      - Paychex Flex
      tier: declared
      url: /providers/paychex-developer/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - CompanyCam
      - JobTread
      - Knowify
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://companycam.com/integrations
      - https://www.jobtread.com/integrations
      - https://www.knowify.com/integrations
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - OpenProject (BIM)
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://www.openproject.org/docs/system-admin-guide/integrations/
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: declared
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - OpenProject (BIM)
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://www.openproject.org/docs/system-admin-guide/integrations/
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: declared
      url: /providers/github/
  - capability:
      attribution: Turbo EA
      id: BC-200.30
      key: accounts-receivable-management
      name: Accounts Receivable Management
      url: /capabilities/accounts-receivable-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Knowify
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp: *id003
      name: QuickBooks Payments
      slug: quickbooks
      sources:
      - https://www.knowify.com/integrations
      status: profiled
      tags: *id004
      tier: declared
      url: /providers/quickbooks/
  - capability:
      attribution: Turbo EA
      id: BC-150.10
      key: contract-management
      name: Contract Management
      url: /capabilities/contract-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Procore
      band: exemplar
      in_catalog: true
      kin_score: 71.5
      mcp:
        source: https://www.docusign.com/products/mcp
        status: documented
      name: DocuSign
      slug: docusign
      sources:
      - https://v2.support.procore.com/en-au/product-manuals/docusign/
      status: profiled
      tags:
      - Agreements
      - Contracts
      - DocuSign
      - E-Signature
      tier: declared
      url: /providers/docusign/
  - capability:
      attribution: API Evangelist extension
      id: AE-917
      key: AE-917
      name: Enterprise Content & Document Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.3
      apps:
      - OpenProject (BIM)
      band: strong
      in_catalog: true
      kin_score: 60.9
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: SharePoint
      slug: sharepoint
      sources:
      - https://www.openproject.org/docs/system-admin-guide/integrations/
      status: profiled
      tags:
      - Collaboration
      - Document Management
      - Enterprise Content Management
      - Intranet
      tier: declared
      url: /providers/sharepoint/
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - OpenProject (BIM)
      band: emerging
      in_catalog: true
      kin_score: 13.1
      mcp:
        source: https://github.com/xwiki-contrib/ai-llm
        status: verified
      name: XWiki
      slug: xwiki
      sources:
      - https://www.openproject.org/docs/system-admin-guide/integrations/
      status: profiled
      tags:
      - Company
      - Enterprise
      - Open Source
      - Wiki
      tier: declared
      url: /providers/xwiki/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Procore
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id005
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google CrashLytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.procore.activities/latest/
      status: profiled
      tags: &id006
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Procore
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id005
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.procore.activities/latest/
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - JobTread
      band: emerging
      in_catalog: true
      kin_score: 18.4
      mcp:
        status: none
      name: NiceJob
      slug: nicejob
      sources:
      - https://www.jobtread.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Reputation Marketing
      - Service Business
      - Software-as-a-Service
      tier: declared
      url: /providers/nicejob/
  layer: common
summary:
  coverage_pct: 91.7
  declared_only: 59
  distinct_providers: 60
  in_catalog: 55
  mcp:
    documented: 2
    none: 20
    unchecked: 5
    verified: 18
  mcp_verified: 18
  mean_kin_score: 41.6
  observed: 1
  queued: 5
  reference_apps: 7
title: 'Construction Management: application blueprint'
---
