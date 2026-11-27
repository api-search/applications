---
access: understanding
agent_layer: []
apps:
- anchor: openimis
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: dependency manifest
    url: https://github.com/openimis/openimis-be_py/blob/develop/requirements.txt
  - route: source code
    url: https://github.com/openimis/openimis-be_py/blob/develop/openimis.json
  - route: source code
    url: https://github.com/openimis/openimis_node_openhim_claim_mediator
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2900
      key: health-information-management
      name: Health Information Management
      url: /capabilities/health-information-management/
      via_parent: null
    credit: null
    layer: domain
    name: DHIS2
    provider: dhis2
    says: ships the DHIS2 SDK or integration code
    source: https://github.com/openimis/openimis-be-dhis2_etl_py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Microsoft SQL Server
    provider: microsoft-sql-server
    says: ships the Microsoft SQL Server SDK or integration code
    source: https://github.com/openimis/openimis-be_py/blob/develop/requirements.txt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2900.60
      key: healthcare-interoperability-operations
      name: Healthcare Interoperability Operations
      url: /capabilities/healthcare-interoperability-operations/
      via_parent: null
    credit: null
    layer: domain
    name: OpenHIM
    provider: openhim
    says: ships the OpenHIM SDK or integration code
    source: https://github.com/openimis/openimis_node_openhim_claim_mediator
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: common
    name: OpenSearch
    provider: opensearch
    says: ships the OpenSearch SDK or integration code
    source: https://github.com/openimis/openimis-be_py/blob/develop/requirements.txt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: RabbitMQ
    provider: rabbitmq
    says: ships the RabbitMQ SDK or integration code
    source: https://github.com/openimis/openimis-be_py/blob/develop/requirements.txt
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Redis
    provider: redis
    says: ships the Redis SDK or integration code
    source: https://github.com/openimis/openimis-be_py/blob/develop/requirements.txt
    tier: observed
  kind: self-hosted
  name: openIMIS
  page: /applications/insurance-policy-claims/openimis/
  slug: openimis
  url: https://github.com/openimis
- anchor: hawksoft
  counts:
    declared: 12
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.hawksoft.com/partners/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Agency Revolution
    provider: agency-revolution
    says: lists Agency Revolution as an integration
    source: https://www.hawksoft.com/partners/
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
    name: AgencyZoom
    provider: agencyzoom
    says: lists AgencyZoom as an integration
    source: https://www.hawksoft.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-959
      key: AE-959
      name: Insurance Data Prefill & Prior-Coverage Verification
      url: /capabilities/underwriting-risk-intake/
      via_parent: Underwriting Risk Intake
    credit: null
    layer: domain
    name: Canopy Connect
    provider: canopy-connect
    says: lists Canopy Connect as an integration
    source: https://www.hawksoft.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2150.20
      key: premium-collection-management
      name: Premium Collection Management
      url: /capabilities/premium-collection-management/
      via_parent: null
    credit: null
    layer: domain
    name: ePayPolicy
    provider: epaypolicy
    says: lists ePayPolicy as an integration
    source: https://www.hawksoft.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2110
      key: insurance-distribution-management
      name: Insurance Distribution Management
      url: /capabilities/insurance-distribution-management/
      via_parent: null
    credit: null
    layer: domain
    name: EZLynx
    provider: ezlynx
    says: lists EZLynx as an integration
    source: https://www.hawksoft.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    credit: null
    layer: domain
    name: Formstack
    provider: formstack
    says: lists Formstack as an integration
    source: https://www.hawksoft.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: Podium
    provider: podium
    says: lists Podium as an integration
    source: https://www.hawksoft.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks Online
    provider: quickbooks
    says: lists QuickBooks Online as an integration
    source: https://www.hawksoft.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50
      key: AE-150.50
      name: Voice & Telephony
      url: /capabilities/voice-telephony/
      via_parent: null
    credit: null
    layer: common
    name: RingCentral
    provider: ringcentral
    says: lists RingCentral as an integration
    source: https://www.hawksoft.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    credit: null
    layer: domain
    name: RPost
    provider: rpost
    says: lists RPost as an integration
    source: https://www.hawksoft.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-958
      key: AE-958
      name: Insurance Comparative Rating & Quote Aggregation
      url: /capabilities/insurance-comparative-rating-quote-aggregation/
      via_parent: null
    credit: null
    layer: domain
    name: Vertafore
    provider: vertafore
    says: lists Vertafore as an integration
    source: https://www.hawksoft.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-958
      key: AE-958
      name: Insurance Comparative Rating & Quote Aggregation
      url: /capabilities/insurance-comparative-rating-quote-aggregation/
      via_parent: null
    credit: null
    layer: domain
    name: Zywave
    provider: zywave
    says: lists Zywave as an integration
    source: https://www.hawksoft.com/partners/
    tier: declared
  kind: commercial
  name: HawkSoft
  page: /applications/insurance-policy-claims/hawksoft/
  slug: hawksoft
  url: https://www.hawksoft.com/
- anchor: ezlynx
  counts:
    declared: 13
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.ezlynx.com/partners/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2150.20
      key: premium-collection-management
      name: Premium Collection Management
      url: /capabilities/premium-collection-management/
      via_parent: null
    credit: null
    layer: domain
    name: Applied Pay (Applied Systems)
    provider: applied-systems
    says: lists Applied Pay (Applied Systems) as an integration
    source: https://www.ezlynx.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    credit: null
    layer: domain
    name: AssureSign
    provider: assuresign
    says: lists AssureSign as an integration
    source: https://www.ezlynx.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Calendly
    provider: calendly
    says: lists Calendly as an integration
    source: https://www.ezlynx.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-959
      key: AE-959
      name: Insurance Data Prefill & Prior-Coverage Verification
      url: /capabilities/underwriting-risk-intake/
      via_parent: Underwriting Risk Intake
    credit: null
    layer: domain
    name: Canopy Connect
    provider: canopy-connect
    says: lists Canopy Connect as an integration
    source: https://www.ezlynx.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.60
      key: property-data
      name: Property Data
      url: /capabilities/property-data/
      via_parent: null
    credit: null
    layer: domain
    name: CoreLogic
    provider: corelogic
    says: lists CoreLogic as an integration
    source: https://www.ezlynx.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-958
      key: AE-958
      name: Insurance Comparative Rating & Quote Aggregation
      url: /capabilities/insurance-comparative-rating-quote-aggregation/
      via_parent: null
    credit: null
    layer: domain
    name: EverQuote
    provider: everquote
    says: lists EverQuote as an integration
    source: https://www.ezlynx.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-959
      key: AE-959
      name: Insurance Data Prefill & Prior-Coverage Verification
      url: /capabilities/underwriting-risk-intake/
      via_parent: Underwriting Risk Intake
    credit: null
    layer: domain
    name: Fenris
    provider: fenris
    says: lists Fenris as an integration
    source: https://www.ezlynx.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Intuit QuickBooks
    provider: quickbooks
    says: lists Intuit QuickBooks as an integration
    source: https://www.ezlynx.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-919
      key: AE-919
      name: B2B EDI & Trading-Partner Networks
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: IVANS
    provider: ivans
    says: lists IVANS as an integration
    source: https://www.ezlynx.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-959
      key: AE-959
      name: Insurance Data Prefill & Prior-Coverage Verification
      url: /capabilities/underwriting-risk-intake/
      via_parent: Underwriting Risk Intake
    credit: null
    layer: domain
    name: LexisNexis Risk Solutions
    provider: lexisnexis-risk-solutions
    says: lists LexisNexis Risk Solutions as an integration
    source: https://www.ezlynx.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-958
      key: AE-958
      name: Insurance Comparative Rating & Quote Aggregation
      url: /capabilities/insurance-comparative-rating-quote-aggregation/
      via_parent: null
    credit: null
    layer: domain
    name: QuinStreet
    provider: quinstreet
    says: lists QuinStreet as an integration
    source: https://www.ezlynx.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50
      key: AE-150.50
      name: Voice & Telephony
      url: /capabilities/voice-telephony/
      via_parent: null
    credit: null
    layer: common
    name: Vonage
    provider: vonage
    says: lists Vonage as an integration
    source: https://www.ezlynx.com/partners/
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
    source: https://www.ezlynx.com/partners/
    tier: declared
  kind: commercial
  name: EZLynx
  page: /applications/insurance-policy-claims/ezlynx/
  slug: ezlynx
  url: https://www.ezlynx.com/
- anchor: socotra
  counts:
    declared: 12
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.socotra.com/partners
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon Web Services
    provider: amazon-web-services
    says: lists Amazon Web Services as an integration
    source: https://www.socotra.com/partners
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Cloverleaf Analytics
    provider: cloverleaf-analytics
    says: lists Cloverleaf Analytics as an integration
    source: https://www.socotra.com/partners
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2100.20
      key: product-rating-pricing-configuration
      name: Product Rating & Pricing Configuration
      url: /capabilities/product-rating-pricing-configuration/
      via_parent: null
    credit: null
    layer: domain
    name: Coherent
    provider: coherent-global
    says: lists Coherent as an integration
    source: https://www.socotra.com/partners
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    credit: null
    layer: domain
    name: DocuSign
    provider: docusign
    says: lists DocuSign as an integration
    source: https://www.socotra.com/partners
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2160
      key: insurance-claims-management
      name: Insurance Claims Management
      url: /capabilities/insurance-claims-management/
      via_parent: null
    credit: null
    layer: domain
    name: Five Sigma
    provider: five-sigma
    says: lists Five Sigma as an integration
    source: https://www.socotra.com/partners
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.30
      key: contact-centre-operations-management
      name: Contact Centre Operations Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Floatbot
    provider: floatbot
    says: lists Floatbot as an integration
    source: https://www.socotra.com/partners
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2100.20
      key: product-rating-pricing-configuration
      name: Product Rating & Pricing Configuration
      url: /capabilities/product-rating-pricing-configuration/
      via_parent: null
    credit: null
    layer: domain
    name: Quantee
    provider: quantee
    says: lists Quantee as an integration
    source: https://www.socotra.com/partners
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2160
      key: insurance-claims-management
      name: Insurance Claims Management
      url: /capabilities/insurance-claims-management/
      via_parent: null
    credit: null
    layer: domain
    name: Reserv
    provider: reserv
    says: lists Reserv as an integration
    source: https://www.socotra.com/partners
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2160
      key: insurance-claims-management
      name: Insurance Claims Management
      url: /capabilities/insurance-claims-management/
      via_parent: null
    credit: null
    layer: domain
    name: Snapsheet
    provider: snapsheet
    says: lists Snapsheet as an integration
    source: https://www.socotra.com/partners
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.30
      key: contact-centre-operations-management
      name: Contact Centre Operations Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Splice Software
    provider: splice-software
    says: lists Splice Software as an integration
    source: https://www.socotra.com/partners
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4270
      key: developer-platform-api-ecosystem-management
      name: Developer Platform & API Ecosystem Management
      url: /capabilities/developer-platform-api-ecosystem-management/
      via_parent: null
    credit: null
    layer: domain
    name: Unqork
    provider: unqork
    says: lists Unqork as an integration
    source: https://www.socotra.com/partners
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Worldpay
    provider: worldpay
    says: lists Worldpay as an integration
    source: https://www.socotra.com/partners
    tier: declared
  kind: commercial
  name: Socotra
  page: /applications/insurance-policy-claims/socotra/
  slug: socotra
  url: https://www.socotra.com/
- anchor: duck-creek
  counts:
    declared: 11
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.duckcreek.com/partners/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2100
      key: insurance-product-management
      name: Insurance Product Management
      url: /capabilities/insurance-product-management/
      via_parent: null
    credit: null
    layer: domain
    name: AAIS
    provider: aais
    says: lists AAIS as an integration
    source: https://www.duckcreek.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2190
      key: insurance-risk-management
      name: Insurance Risk Management
      url: /capabilities/insurance-risk-management/
      via_parent: null
    credit: null
    layer: domain
    name: Advisen
    provider: advisen
    says: lists Advisen as an integration
    source: https://www.duckcreek.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2100.20
      key: product-rating-pricing-configuration
      name: Product Rating & Pricing Configuration
      url: /capabilities/product-rating-pricing-configuration/
      via_parent: null
    credit: null
    layer: domain
    name: Akur8
    provider: akur8
    says: lists Akur8 as an integration
    source: https://www.duckcreek.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-960
      key: AE-960
      name: Usage-Based Insurance Telematics Data
      url: /capabilities/usage-based-insurance-telematics-data/
      via_parent: null
    credit: null
    layer: domain
    name: Arity
    provider: arity
    says: lists Arity as an integration
    source: https://www.duckcreek.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2130.10
      key: underwriting-risk-intake
      name: Underwriting Risk Intake
      url: /capabilities/underwriting-risk-intake/
      via_parent: null
    credit: null
    layer: domain
    name: BitSight
    provider: bitsight
    says: lists BitSight as an integration
    source: https://www.duckcreek.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-960
      key: AE-960
      name: Usage-Based Insurance Telematics Data
      url: /capabilities/usage-based-insurance-telematics-data/
      via_parent: null
    credit: null
    layer: domain
    name: Cambridge Mobile Telematics
    provider: cambridge-mobile-telematics
    says: lists Cambridge Mobile Telematics as an integration
    source: https://www.duckcreek.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.60
      key: property-data
      name: Property Data
      url: /capabilities/property-data/
      via_parent: null
    credit: null
    layer: domain
    name: CAPE Analytics
    provider: cape-analytics
    says: lists CAPE Analytics as an integration
    source: https://www.duckcreek.com/partners/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-949
      key: AE-949
      name: Vehicle History Reports
      url: /capabilities/vehicle-history-reports/
      via_parent: null
    credit: null
    layer: domain
    name: CARFAX
    provider: carfax
    says: lists CARFAX as an integration
    source: https://www.duckcreek.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2130.10
      key: underwriting-risk-intake
      name: Underwriting Risk Intake
      url: /capabilities/underwriting-risk-intake/
      via_parent: null
    credit: null
    layer: domain
    name: Carpe Data
    provider: carpe-data
    says: lists Carpe Data as an integration
    source: https://www.duckcreek.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2160
      key: insurance-claims-management
      name: Insurance Claims Management
      url: /capabilities/insurance-claims-management/
      via_parent: null
    credit: null
    layer: domain
    name: CCC Intelligent Solutions
    provider: ccc-intelligent-solutions
    says: lists CCC Intelligent Solutions as an integration
    source: https://www.duckcreek.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2160
      key: insurance-claims-management
      name: Insurance Claims Management
      url: /capabilities/insurance-claims-management/
      via_parent: null
    credit: null
    layer: domain
    name: CLARA Analytics
    provider: clara-analytics
    says: lists CLARA Analytics as an integration
    source: https://www.duckcreek.com/partners/
    tier: declared
  kind: commercial
  name: Duck Creek
  page: /applications/insurance-policy-claims/duck-creek/
  slug: duck-creek
  url: https://www.duckcreek.com/
- anchor: lemonade
  counts:
    declared: 0
    observed: 0
  evidence: []
  integrations: []
  kind: commercial
  name: Lemonade
  page: /applications/insurance-policy-claims/lemonade/
  slug: lemonade
  url: https://www.lemonade.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: insurance-policy-claims
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Workers' Comp Solution
  store: guidewire-marketplace
  url: https://marketplace.guidewire.com/
- category: GenAI Services
  store: guidewire-marketplace
  url: https://marketplace.guidewire.com/
- category: Finance
  store: google-play
  url: https://play.google.com/store/apps/category/FINANCE
- category: Finance
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Insurance
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Insurance
  store: zapier
  url: https://zapier.com/apps
name: Insurance Policy & Claims
needs:
- capability:
    attribution: Turbo EA
    id: BC-2900
    key: health-information-management
    name: Health Information Management
    url: /capabilities/health-information-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'integrations declared/observed in openIMIS: DHIS2'
- capability:
    attribution: Turbo EA
    id: BC-2900.60
    key: healthcare-interoperability-operations
    name: Healthcare Interoperability Operations
    url: /capabilities/healthcare-interoperability-operations/
    via_parent: null
  fit: exact
  layer: domain
  why: 'integrations declared/observed in openIMIS: OpenHIM'
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  fit: exact
  layer: common
  why: 'integrations declared/observed in openIMIS: OpenSearch'
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: 'integrations declared/observed in openIMIS: Microsoft SQL Server; Redis'
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: common
  why: 'integrations declared/observed in openIMIS: RabbitMQ'
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'integrations declared/observed in HawkSoft: AgencyZoom'
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'integrations declared/observed in HawkSoft: Agency Revolution'
- capability:
    attribution: Turbo EA
    id: BC-2130.10
    key: underwriting-risk-intake
    name: Underwriting Risk Intake
    url: /capabilities/underwriting-risk-intake/
    via_parent: null
  fit: nearest
  layer: domain
  why: 'integrations declared/observed in Duck Creek, EZLynx, HawkSoft: BitSight; Canopy Connect; Carpe Data; Fenris; LexisNexis Risk Solutions'
- capability:
    attribution: Turbo EA
    id: BC-2150.20
    key: premium-collection-management
    name: Premium Collection Management
    url: /capabilities/premium-collection-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'integrations declared/observed in EZLynx, HawkSoft: Applied Pay (Applied Systems); ePayPolicy'
- capability:
    attribution: Turbo EA
    id: BC-150.10.30
    key: BC-150.10.30
    name: Contract Execution Management
    url: /capabilities/contract-management/
    via_parent: Contract Management
  fit: nearest
  layer: domain
  why: 'integrations declared/observed in EZLynx, HawkSoft, Socotra: AssureSign; DocuSign; Formstack; RPost'
- capability:
    attribution: Turbo EA
    id: BC-2110
    key: insurance-distribution-management
    name: Insurance Distribution Management
    url: /capabilities/insurance-distribution-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: 'integrations declared/observed in EZLynx, HawkSoft: EZLynx; EverQuote; QuinStreet'
- capability:
    attribution: Turbo EA
    id: BC-2100.20
    key: product-rating-pricing-configuration
    name: Product Rating & Pricing Configuration
    url: /capabilities/product-rating-pricing-configuration/
    via_parent: null
  fit: nearest
  layer: domain
  why: 'integrations declared/observed in Duck Creek, HawkSoft, Socotra: Akur8; Coherent; Quantee; Vertafore; Zywave'
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'integrations declared/observed in EZLynx, HawkSoft: QuickBooks Online'
- capability:
    attribution: API Evangelist extension
    id: AE-150.50
    key: AE-150.50
    name: Voice & Telephony
    url: /capabilities/voice-telephony/
    via_parent: null
  fit: exact
  layer: common
  why: 'integrations declared/observed in EZLynx, HawkSoft: RingCentral; Vonage'
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  fit: exact
  layer: domain
  why: 'integrations declared/observed in HawkSoft: Podium'
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'integrations declared/observed in EZLynx: Calendly'
- capability:
    attribution: API Evangelist extension
    id: AE-230.60
    key: property-data
    name: Property Data
    url: /capabilities/property-data/
    via_parent: null
  fit: exact
  layer: domain
  why: 'integrations declared/observed in Duck Creek, EZLynx: CAPE Analytics; CoreLogic'
- capability:
    attribution: API Evangelist extension
    id: AE-919
    key: AE-919
    name: B2B EDI & Trading-Partner Networks
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: common
  why: 'integrations declared/observed in EZLynx: IVANS'
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: 'integrations declared/observed in EZLynx: Zapier'
- capability:
    attribution: Turbo EA
    id: BC-4270
    key: developer-platform-api-ecosystem-management
    name: Developer Platform & API Ecosystem Management
    url: /capabilities/developer-platform-api-ecosystem-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: 'integrations declared/observed in Socotra: Unqork'
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  fit: exact
  layer: common
  why: 'integrations declared/observed in Socotra: Amazon Web Services'
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'integrations declared/observed in Socotra: Worldpay'
- capability:
    attribution: Turbo EA
    id: BC-2160
    key: insurance-claims-management
    name: Insurance Claims Management
    url: /capabilities/insurance-claims-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'integrations declared/observed in Duck Creek, Socotra: CCC Intelligent Solutions; CLARA Analytics; Five Sigma; Reserv; Snapsheet'
- capability:
    attribution: Turbo EA
    id: BC-430.30
    key: contact-centre-operations-management
    name: Contact Centre Operations Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: 'integrations declared/observed in Socotra: Floatbot; Splice Software'
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'integrations declared/observed in Socotra: Cloverleaf Analytics'
- capability:
    attribution: API Evangelist extension
    id: AE-960
    key: AE-960
    name: Usage-Based Insurance Telematics Data
    url: /capabilities/usage-based-insurance-telematics-data/
    via_parent: null
  fit: exact
  layer: domain
  why: 'integrations declared/observed in Duck Creek: Arity; Cambridge Mobile Telematics'
- capability:
    attribution: API Evangelist extension
    id: AE-949
    key: AE-949
    name: Vehicle History Reports
    url: /capabilities/vehicle-history-reports/
    via_parent: null
  fit: exact
  layer: domain
  why: 'integrations declared/observed in Duck Creek: CARFAX'
- capability:
    attribution: Turbo EA
    id: BC-2190
    key: insurance-risk-management
    name: Insurance Risk Management
    url: /capabilities/insurance-risk-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: 'integrations declared/observed in Duck Creek: Advisen'
- capability:
    attribution: Turbo EA
    id: BC-2100
    key: insurance-product-management
    name: Insurance Product Management
    url: /capabilities/insurance-product-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: 'integrations declared/observed in Duck Creek: AAIS'
- capability:
    attribution: API Evangelist extension
    id: AE-959
    key: AE-959
    name: Insurance Data Prefill & Prior-Coverage Verification
    url: /capabilities/underwriting-risk-intake/
    via_parent: Underwriting Risk Intake
  fit: exact
  layer: domain
  why: Canopy Connect, LexisNexis Risk Solutions (Insurance Data Prefill & Prior-Coverage Verification)
- capability:
    attribution: API Evangelist extension
    id: AE-958
    key: AE-958
    name: Insurance Comparative Rating & Quote Aggregation
    url: /capabilities/insurance-comparative-rating-quote-aggregation/
    via_parent: null
  fit: exact
  layer: domain
  why: Zywave, Vertafore, EverQuote (Insurance Comparative Rating & Quote Aggregation)
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-2160
      key: insurance-claims-management
      name: Insurance Claims Management
      url: /capabilities/insurance-claims-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.2
      apps:
      - Duck Creek
      band: thin
      in_catalog: true
      kin_score: 33.3
      mcp:
        status: unknown
      name: CCC Intelligent Solutions
      slug: ccc-intelligent-solutions
      sources:
      - https://www.duckcreek.com/partners/
      status: profiled
      tags:
      - Claims
      - Insurance
      - Property and Casualty
      - United States
      tier: declared
      url: /providers/ccc-intelligent-solutions/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Duck Creek
      band: emerging
      in_catalog: true
      kin_score: 17.1
      mcp:
        status: unknown
      name: CLARA Analytics
      slug: clara-analytics
      sources:
      - https://www.duckcreek.com/partners/
      status: profiled
      tags:
      - Claims
      - Company
      - Insurance
      - Insurtech
      tier: declared
      url: /providers/clara-analytics/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Socotra
      band: minimal
      in_catalog: true
      kin_score: 9.7
      mcp:
        status: unknown
      name: Reserv
      slug: reserv
      sources:
      - https://www.socotra.com/partners
      status: profiled
      tags:
      - Claims Management
      - Company
      - Insurance
      - Insurtech
      tier: declared
      url: /providers/reserv/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Socotra
      band: minimal
      in_catalog: true
      kin_score: 9.0
      mcp:
        status: none
      name: Snapsheet
      slug: snapsheet
      sources:
      - https://www.socotra.com/partners
      status: profiled
      tags:
      - Claims
      - Claims Management
      - Company
      - Insurance
      tier: declared
      url: /providers/snapsheet/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Socotra
      band: minimal
      in_catalog: true
      kin_score: 8.8
      mcp:
        status: unchecked
      name: Five Sigma
      slug: five-sigma
      sources:
      - https://www.socotra.com/partners
      status: profiled
      tags:
      - Artificial Intelligence
      - Claims Management
      - Insurance
      - Software-as-a-Service
      tier: declared
      url: /providers/five-sigma/
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Socotra
      band: exemplar
      in_catalog: true
      kin_score: 71.5
      mcp:
        source: https://www.docusign.com/products/mcp
        status: documented
      name: DocuSign
      slug: docusign
      sources:
      - https://www.socotra.com/partners
      status: profiled
      tags:
      - Agreements
      - Contracts
      - DocuSign
      - E-Signature
      tier: declared
      url: /providers/docusign/
    - agent_band: agent-ready
      agent_readiness: 33.2
      apps:
      - HawkSoft
      band: emerging
      in_catalog: true
      kin_score: 24.4
      mcp:
        status: none
      name: Formstack
      slug: formstack
      sources:
      - https://www.hawksoft.com/partners/
      status: profiled
      tags:
      - Documents
      - E-Signature
      - Forms
      - Workflow Automation
      tier: declared
      url: /providers/formstack/
    - agent_band: agent-aware
      agent_readiness: 7.4
      apps:
      - HawkSoft
      band: emerging
      in_catalog: true
      kin_score: 23.9
      mcp:
        status: unchecked
      name: RPost
      slug: rpost
      sources:
      - https://www.hawksoft.com/partners/
      status: profiled
      tags:
      - Compliance
      - Document Security
      - E-Signature
      - Email Security
      tier: declared
      url: /providers/rpost/
    - agent_band: null
      agent_readiness: null
      apps:
      - EZLynx
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: AssureSign
      slug: assuresign
      sources:
      - https://www.ezlynx.com/partners/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-958
      key: AE-958
      name: Insurance Comparative Rating & Quote Aggregation
      url: /capabilities/insurance-comparative-rating-quote-aggregation/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 45.8
      apps:
      - HawkSoft
      band: developing
      in_catalog: true
      kin_score: 50.8
      mcp:
        status: none
      name: Zywave
      slug: zywave
      sources:
      - https://www.hawksoft.com/partners/
      status: profiled
      tags:
      - Brokerage
      - Company
      - Insurance
      - Insurance Agencies
      tier: declared
      url: /providers/zywave/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - HawkSoft
      band: minimal
      in_catalog: true
      kin_score: 9.7
      mcp:
        status: none
      name: Vertafore
      slug: vertafore
      sources:
      - https://www.hawksoft.com/partners/
      status: profiled
      tags:
      - Agency Management
      - Insurance
      - Insurtech
      - Property and Casualty
      tier: declared
      url: /providers/vertafore/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - EZLynx
      band: minimal
      in_catalog: true
      kin_score: 9.6
      mcp:
        status: unchecked
      name: EverQuote
      slug: everquote
      sources:
      - https://www.ezlynx.com/partners/
      status: profiled
      tags:
      - Artificial Intelligence
      - Data
      - Insurance
      - Marketplace
      tier: declared
      url: /providers/everquote/
    - agent_band: agent-aware
      agent_readiness: 21.4
      apps:
      - EZLynx
      band: minimal
      in_catalog: true
      kin_score: 9.0
      mcp:
        status: unchecked
      name: QuinStreet
      slug: quinstreet
      sources:
      - https://www.ezlynx.com/partners/
      status: profiled
      tags:
      - Advertising
      - Company
      - Financial Services
      - Marketing
      tier: declared
      url: /providers/quinstreet/
  - capability:
      attribution: API Evangelist extension
      id: AE-959
      key: AE-959
      name: Insurance Data Prefill & Prior-Coverage Verification
      url: /capabilities/underwriting-risk-intake/
      via_parent: Underwriting Risk Intake
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - EZLynx
      - HawkSoft
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Canopy Connect
      slug: canopy-connect
      sources:
      - https://www.ezlynx.com/partners/
      - https://www.hawksoft.com/partners/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - EZLynx
      band: thin
      in_catalog: true
      kin_score: 37.4
      mcp:
        status: unknown
      name: LexisNexis Risk Solutions
      slug: lexisnexis-risk-solutions
      sources:
      - https://www.ezlynx.com/partners/
      status: profiled
      tags:
      - Insurance
      - Property and Casualty
      - Risk Data
      - United States
      tier: declared
      url: /providers/lexisnexis-risk-solutions/
    - agent_band: null
      agent_readiness: null
      apps:
      - EZLynx
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Fenris
      slug: fenris
      sources:
      - https://www.ezlynx.com/partners/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-2100.20
      key: product-rating-pricing-configuration
      name: Product Rating & Pricing Configuration
      url: /capabilities/product-rating-pricing-configuration/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - Socotra
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        status: unchecked
      name: Coherent
      slug: coherent-global
      sources:
      - https://www.socotra.com/partners
      status: profiled
      tags:
      - Automation
      - Company
      - Excel
      - Insurance
      tier: declared
      url: /providers/coherent-global/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Duck Creek
      band: minimal
      in_catalog: true
      kin_score: 9.2
      mcp:
        status: unknown
      name: Akur8
      slug: akur8
      sources:
      - https://www.duckcreek.com/partners/
      status: profiled
      tags:
      - Actuarial
      - Insurance
      - Insurtech
      - Pricing
      tier: declared
      url: /providers/akur8/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Socotra
      band: minimal
      in_catalog: true
      kin_score: 7.2
      mcp:
        status: unchecked
      name: Quantee
      slug: quantee
      sources:
      - https://www.socotra.com/partners
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Data Analytics
      - Enterprise
      tier: declared
      url: /providers/quantee/
  - capability:
      attribution: Turbo EA
      id: BC-430.30
      key: contact-centre-operations-management
      name: Contact Centre Operations Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.8
      apps:
      - Socotra
      band: thin
      in_catalog: true
      kin_score: 29.3
      mcp:
        status: unchecked
      name: Floatbot
      slug: floatbot
      sources:
      - https://www.socotra.com/partners
      status: profiled
      tags:
      - AI Platform
      - Conversational AI
      - Insurance
      - Voice AI
      tier: declared
      url: /providers/floatbot/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Socotra
      band: minimal
      in_catalog: true
      kin_score: 8.7
      mcp:
        status: unchecked
      name: Splice Software
      slug: splice-software
      sources:
      - https://www.socotra.com/partners
      status: profiled
      tags:
      - Communication Platform
      - Company
      - Customer Engagement
      - Omnichannel
      tier: declared
      url: /providers/splice-software/
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
      - EZLynx
      - HawkSoft
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks Online
      slug: quickbooks
      sources:
      - https://www.ezlynx.com/partners/
      - https://www.hawksoft.com/partners/
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
  - capability:
      attribution: Turbo EA
      id: BC-2150.20
      key: premium-collection-management
      name: Premium Collection Management
      url: /capabilities/premium-collection-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - HawkSoft
      band: thin
      in_catalog: true
      kin_score: 32.7
      mcp:
        status: unchecked
      name: ePayPolicy
      slug: epaypolicy
      sources:
      - https://www.hawksoft.com/partners/
      status: profiled
      tags:
      - Company
      - Fintech
      - Insurance
      - Payments
      tier: declared
      url: /providers/epaypolicy/
    - agent_band: human-only
      agent_readiness: 1.3
      apps:
      - EZLynx
      band: minimal
      in_catalog: true
      kin_score: 10.7
      mcp:
        status: unknown
      name: Applied Pay (Applied Systems)
      slug: applied-systems
      sources:
      - https://www.ezlynx.com/partners/
      status: profiled
      tags:
      - Agency Management
      - Applied Epic
      - Insurance
      - Insurtech
      tier: declared
      url: /providers/applied-systems/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.60
      key: property-data
      name: Property Data
      url: /capabilities/property-data/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.6
      apps:
      - EZLynx
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        source: https://www.cotality.com/platforms/mcp-server
        status: verified
      name: CoreLogic
      slug: corelogic
      sources:
      - https://www.ezlynx.com/partners/
      status: profiled
      tags:
      - Climate Risk
      - CoreLogic
      - Cotality
      - Direct Web API
      tier: declared
      url: /providers/corelogic/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Duck Creek
      band: emerging
      in_catalog: true
      kin_score: 16.8
      mcp:
        status: unknown
      name: CAPE Analytics
      slug: cape-analytics
      sources:
      - https://www.duckcreek.com/partners/
      status: profiled
      tags:
      - Company
      - Computer Vision
      - Geospatial
      - Property Intelligence
      tier: declared
      url: /providers/cape-analytics/
  - capability:
      attribution: Turbo EA
      id: BC-2130.10
      key: underwriting-risk-intake
      name: Underwriting Risk Intake
      url: /capabilities/underwriting-risk-intake/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - Duck Creek
      band: thin
      in_catalog: true
      kin_score: 34.4
      mcp:
        status: unknown
      name: BitSight
      slug: bitsight
      sources:
      - https://www.duckcreek.com/partners/
      status: profiled
      tags:
      - Company
      - Cyber Risk
      - Security
      - Security Ratings
      tier: declared
      url: /providers/bitsight/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Duck Creek
      band: minimal
      in_catalog: true
      kin_score: 8.6
      mcp:
        status: unchecked
      name: Carpe Data
      slug: carpe-data
      sources:
      - https://www.duckcreek.com/partners/
      status: profiled
      tags:
      - Artificial Intelligence
      - Claims
      - Data
      - Insurance
      tier: declared
      url: /providers/carpe-data/
  - capability:
      attribution: API Evangelist extension
      id: AE-960
      key: AE-960
      name: Usage-Based Insurance Telematics Data
      url: /capabilities/usage-based-insurance-telematics-data/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.8
      apps:
      - Duck Creek
      band: developing
      in_catalog: true
      kin_score: 41.6
      mcp:
        status: unknown
      name: Arity
      slug: arity
      sources:
      - https://www.duckcreek.com/partners/
      status: profiled
      tags:
      - Company
      - Insurance
      - Mobility Data
      - Telematics
      tier: declared
      url: /providers/arity/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Duck Creek
      band: emerging
      in_catalog: true
      kin_score: 21.6
      mcp:
        status: none
      name: Cambridge Mobile Telematics
      slug: cambridge-mobile-telematics
      sources:
      - https://www.duckcreek.com/partners/
      status: profiled
      tags:
      - Company
      - Enterprise
      - Insurance
      - Telematics
      tier: declared
      url: /providers/cambridge-mobile-telematics/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.7
      apps:
      - Socotra
      band: emerging
      in_catalog: true
      kin_score: 11.4
      mcp:
        status: unchecked
      name: Cloverleaf Analytics
      slug: cloverleaf-analytics
      sources:
      - https://www.socotra.com/partners
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Company
      - Insurance
      tier: declared
      url: /providers/cloverleaf-analytics/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.3
      apps:
      - HawkSoft
      band: thin
      in_catalog: true
      kin_score: 27.0
      mcp:
        status: unknown
      name: AgencyZoom
      slug: agencyzoom
      sources:
      - https://www.hawksoft.com/partners/
      status: profiled
      tags:
      - CRM
      - Insurance
      - Insurtech
      - Sales Automation
      tier: declared
      url: /providers/agencyzoom/
  - capability:
      attribution: Turbo EA
      id: BC-4270
      key: developer-platform-api-ecosystem-management
      name: Developer Platform & API Ecosystem Management
      url: /capabilities/developer-platform-api-ecosystem-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - Socotra
      band: strong
      in_catalog: true
      kin_score: 64.8
      mcp:
        status: unknown
      name: Unqork
      slug: unqork
      sources:
      - https://www.socotra.com/partners
      status: profiled
      tags:
      - Application Development
      - Company
      - Low-Code
      - No-Code
      tier: declared
      url: /providers/unqork/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - HawkSoft
      band: emerging
      in_catalog: true
      kin_score: 15.8
      mcp:
        status: unchecked
      name: Agency Revolution
      slug: agency-revolution
      sources:
      - https://www.hawksoft.com/partners/
      status: profiled
      tags:
      - Automation
      - Company
      - Insurance
      - Marketing
      tier: declared
      url: /providers/agency-revolution/
  - capability:
      attribution: Turbo EA
      id: BC-2900
      key: health-information-management
      name: Health Information Management
      url: /capabilities/health-information-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - openIMIS
      band: developing
      in_catalog: true
      kin_score: 44.3
      mcp:
        status: unchecked
      name: DHIS2
      slug: dhis2
      sources:
      - https://github.com/openimis/openimis-be-dhis2_etl_py
      status: profiled
      tags:
      - Analytics
      - Data Management
      - Health
      - Open Source
      tier: observed
      url: /providers/dhis2/
  - capability:
      attribution: Turbo EA
      id: BC-2900.60
      key: healthcare-interoperability-operations
      name: Healthcare Interoperability Operations
      url: /capabilities/healthcare-interoperability-operations/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.7
      apps:
      - openIMIS
      band: emerging
      in_catalog: true
      kin_score: 26.1
      mcp:
        status: unchecked
      name: OpenHIM
      slug: openhim
      sources:
      - https://github.com/openimis/openimis_node_openhim_claim_mediator
      status: profiled
      tags:
      - Health
      - Integration
      - Middleware
      - Open Source
      tier: observed
      url: /providers/openhim/
  - capability:
      attribution: Turbo EA
      id: BC-2110
      key: insurance-distribution-management
      name: Insurance Distribution Management
      url: /capabilities/insurance-distribution-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - HawkSoft
      band: emerging
      in_catalog: true
      kin_score: 15.3
      mcp:
        status: none
      name: EZLynx
      slug: ezlynx
      sources:
      - https://www.hawksoft.com/partners/
      status: profiled
      tags:
      - Agency Management System
      - Comparative Rating
      - Insurance
      - Insurtech
      tier: declared
      url: /providers/ezlynx/
  - capability:
      attribution: Turbo EA
      id: BC-2100
      key: insurance-product-management
      name: Insurance Product Management
      url: /capabilities/insurance-product-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Duck Creek
      band: minimal
      in_catalog: true
      kin_score: 7.3
      mcp:
        status: unchecked
      name: AAIS
      slug: aais
      sources:
      - https://www.duckcreek.com/partners/
      status: profiled
      tags:
      - Advisory Services
      - Data Technology
      - Insurance
      - Not-for-profit
      tier: declared
      url: /providers/aais/
  - capability:
      attribution: Turbo EA
      id: BC-2190
      key: insurance-risk-management
      name: Insurance Risk Management
      url: /capabilities/insurance-risk-management/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Duck Creek
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Advisen
      slug: advisen
      sources:
      - https://www.duckcreek.com/partners/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 45.1
      apps:
      - Socotra
      band: developing
      in_catalog: true
      kin_score: 48.9
      mcp:
        status: none
      name: Worldpay
      slug: worldpay
      sources:
      - https://www.socotra.com/partners
      status: profiled
      tags:
      - Payment Gateway
      - Payment Processing
      - Payments
      - Tokenization
      tier: declared
      url: /providers/worldpay/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 40.1
      apps:
      - HawkSoft
      band: strong
      in_catalog: true
      kin_score: 59.1
      mcp:
        status: none
      name: Podium
      slug: podium
      sources:
      - https://www.hawksoft.com/partners/
      status: profiled
      tags:
      - Customer Communication
      - Messaging
      - Payments
      - Reviews
      tier: declared
      url: /providers/podium/
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.4
      apps:
      - EZLynx
      band: developing
      in_catalog: true
      kin_score: 47.5
      mcp:
        source: https://developer.calendly.com/calendly-mcp-server
        status: documented
      name: Calendly
      slug: calendly
      sources:
      - https://www.ezlynx.com/partners/
      status: profiled
      tags:
      - Appointments
      - Automation
      - Booking
      - Calendar
      tier: declared
      url: /providers/calendly/
  - capability:
      attribution: API Evangelist extension
      id: AE-949
      key: AE-949
      name: Vehicle History Reports
      url: /capabilities/vehicle-history-reports/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 13.3
      apps:
      - Duck Creek
      band: emerging
      in_catalog: true
      kin_score: 18.2
      mcp:
        status: none
      name: CARFAX
      slug: carfax
      sources:
      - https://www.duckcreek.com/partners/
      status: profiled
      tags:
      - Automotive
      - Used Cars
      - VIN Lookup
      - Vehicle History
      tier: declared
      url: /providers/carfax/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - openIMIS
      band: exemplar
      in_catalog: true
      kin_score: 67.0
      mcp:
        source: https://learn.microsoft.com/en-us/azure/data-api-builder/mcp/
        status: verified
      name: Microsoft SQL Server
      slug: microsoft-sql-server
      sources:
      - https://github.com/openimis/openimis-be_py/blob/develop/requirements.txt
      status: profiled
      tags:
      - Cloud
      - Data Management
      - Database
      - Enterprise
      tier: observed
      url: /providers/microsoft-sql-server/
    - agent_band: agent-ready
      agent_readiness: 41.5
      apps:
      - openIMIS
      band: developing
      in_catalog: true
      kin_score: 46.5
      mcp:
        source: https://github.com/redis/mcp-redis
        status: verified
      name: Redis
      slug: redis
      sources:
      - https://github.com/openimis/openimis-be_py/blob/develop/requirements.txt
      status: profiled
      tags:
      - Cache
      - Database
      - In-Memory
      - Key-Value Store
      tier: observed
      url: /providers/redis/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50
      key: AE-150.50
      name: Voice & Telephony
      url: /capabilities/voice-telephony/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.0
      apps:
      - EZLynx
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/Vonage/vonage-mcp-server-documentation
        status: verified
      name: Vonage
      slug: vonage
      sources:
      - https://www.ezlynx.com/partners/
      status: profiled
      tags:
      - Communications
      - Messaging
      - Telecommunications
      - Video Conferencing
      tier: declared
      url: /providers/vonage/
    - agent_band: agent-ready
      agent_readiness: 43.6
      apps:
      - HawkSoft
      band: strong
      in_catalog: true
      kin_score: 59.4
      mcp:
        source: https://developers.ringcentral.com/mcp
        status: documented
      name: RingCentral
      slug: ringcentral
      sources:
      - https://www.hawksoft.com/partners/
      status: profiled
      tags:
      - Communications
      - UCaaS
      - Video
      - Voice
      tier: declared
      url: /providers/ringcentral/
  - capability:
      attribution: API Evangelist extension
      id: AE-919
      key: AE-919
      name: B2B EDI & Trading-Partner Networks
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.7
      apps:
      - EZLynx
      band: strong
      in_catalog: true
      kin_score: 62.6
      mcp:
        status: unknown
      name: IVANS
      slug: ivans
      sources:
      - https://www.ezlynx.com/partners/
      status: profiled
      tags:
      - Company
      - Data Exchange
      - Insurance
      - Insurance Distribution
      tier: declared
      url: /providers/ivans/
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Socotra
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Web Services
      slug: amazon-web-services
      sources:
      - https://www.socotra.com/partners
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: declared
      url: /providers/amazon-web-services/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - openIMIS
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        status: none
      name: RabbitMQ
      slug: rabbitmq
      sources:
      - https://github.com/openimis/openimis-be_py/blob/develop/requirements.txt
      status: profiled
      tags:
      - AMQP
      - Distributed Systems
      - Queues
      - RabbitMQ
      tier: observed
      url: /providers/rabbitmq/
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.3
      apps:
      - openIMIS
      band: thin
      in_catalog: true
      kin_score: 37.3
      mcp:
        source: https://github.com/opensearch-project/opensearch-mcp-server-py
        status: verified
      name: OpenSearch
      slug: opensearch
      sources:
      - https://github.com/openimis/openimis-be_py/blob/develop/requirements.txt
      status: profiled
      tags:
      - Analytics
      - Observability
      - OpenSearch
      - Search
      tier: observed
      url: /providers/opensearch/
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
      - EZLynx
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://www.ezlynx.com/partners/
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
  layer: common
summary:
  coverage_pct: 92.3
  declared_only: 46
  distinct_providers: 52
  in_catalog: 48
  mcp:
    documented: 3
    none: 10
    unchecked: 19
    verified: 8
  mcp_verified: 8
  mean_kin_score: 32.7
  observed: 6
  queued: 4
  reference_apps: 6
title: 'Insurance Policy & Claims: application blueprint'
---
