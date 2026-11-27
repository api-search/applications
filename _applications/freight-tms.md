---
access: understanding
agent_layer: []
apps:
- anchor: fleetbase
  counts:
    declared: 0
    observed: 16
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
  - route: dependency manifest
    url: https://raw.githubusercontent.com/fleetbase/fleetops/main/composer.json
  - route: source code
    url: https://github.com/fleetbase/fleetops/tree/main/server/src/Integrations
  - route: source code
    url: https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
  - route: source code
    url: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/.env.example
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Afaqy
    provider: afaqy
    says: ships the Afaqy SDK or integration code
    source: https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: flespi
    provider: flespi
    says: ships the flespi SDK or integration code
    source: https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Geotab
    provider: geotab
    says: ships the Geotab SDK or integration code
    source: https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: Google Maps Platform
    provider: google-maps
    says: ships the Google Maps Platform SDK or integration code
    source: https://raw.githubusercontent.com/fleetbase/fleetops/main/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2400
      key: freight-capacity-management
      name: Freight Capacity Management
      url: /capabilities/freight-capacity-management/
      via_parent: null
    credit: null
    layer: domain
    name: Lalamove
    provider: lalamove
    says: ships the Lalamove SDK or integration code
    source: https://github.com/fleetbase/fleetops/tree/main/server/src/Integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailgun
    provider: mailgun
    says: ships the Mailgun SDK or integration code
    source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Postmark
    provider: postmark
    says: ships the Postmark SDK or integration code
    source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    credit: null
    layer: common
    name: Pusher
    provider: pusher
    says: ships the Pusher SDK or integration code
    source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Resend
    provider: resend
    says: ships the Resend SDK or integration code
    source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Safee
    provider: safee
    says: ships the Safee SDK or integration code
    source: https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Samsara
    provider: samsara
    says: ships the Samsara SDK or integration code
    source: https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: SendGrid
    provider: sendgrid
    says: ships the SendGrid SDK or integration code
    source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30.10
      key: AE-120.30.10
      name: Turn-by-Turn Directions
      url: /capabilities/routing-navigation/
      via_parent: Routing & Navigation
    credit: null
    layer: common
    name: Valhalla
    provider: valhalla
    says: ships the Valhalla SDK or integration code
    source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1050.20.20
      key: BC-1050.20.20
      name: Route Optimisation
      url: /capabilities/service-dispatch-management/
      via_parent: Service Dispatch Management
    credit: null
    layer: domain
    name: VROOM (Vehicle Routing Open-source Optimization Machine)
    provider: vroom-project
    says: ships the VROOM (Vehicle Routing Open-source Optimization Machine) SDK or integration code
    source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
    tier: observed
  kind: self-hosted
  name: Fleetbase
  page: /applications/freight-tms/fleetbase/
  slug: fleetbase
  url: https://github.com/fleetbase/fleetbase
- anchor: rose-rocket
  counts:
    declared: 28
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.roserocket.com/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-919
      key: AE-919
      name: B2B EDI & Trading-Partner Networks
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: Bitfreighter
    provider: bitfreighter
    says: lists Bitfreighter as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2480.20
      key: customs-declaration-management
      name: Customs Declaration Management
      url: /capabilities/customs-declaration-management/
      via_parent: null
    credit: null
    layer: domain
    name: BorderConnect
    provider: borderconnect
    says: lists BorderConnect as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2460
      key: warehousing-operations-management
      name: Warehousing Operations Management
      url: /capabilities/warehousing-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: CartonCloud
    provider: cartoncloud
    says: lists CartonCloud as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510
      key: shipment-visibility-tracking-management
      name: Shipment Visibility & Tracking Management
      url: /capabilities/shipment-visibility-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: Chain.io
    provider: chain-io
    says: lists Chain.io as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    credit: null
    layer: common
    name: Corpay
    provider: corpay
    says: lists Corpay as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2400
      key: freight-capacity-management
      name: Freight Capacity Management
      url: /capabilities/freight-capacity-management/
      via_parent: null
    credit: null
    layer: domain
    name: DAT Freight & Analytics
    provider: dat-freight
    says: lists DAT Freight & Analytics as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510
      key: shipment-visibility-tracking-management
      name: Shipment Visibility & Tracking Management
      url: /capabilities/shipment-visibility-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: Descartes Systems Group
    provider: descartes
    says: lists Descartes Systems Group as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2530.20
      key: freight-audit-and-payment-management
      name: Freight Audit and Payment Management
      url: /capabilities/freight-audit-and-payment-management/
      via_parent: null
    credit: null
    layer: domain
    name: EpayManager
    provider: epaymanager
    says: lists EpayManager as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510
      key: shipment-visibility-tracking-management
      name: Shipment Visibility & Tracking Management
      url: /capabilities/shipment-visibility-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: FourKites
    provider: fourkites
    says: lists FourKites as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Geotab
    provider: geotab
    says: lists Geotab as an integration
    source: https://www.roserocket.com/integrations
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
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: Google BigQuery
    provider: google-bigquery
    says: lists Google BigQuery as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30.10
      key: AE-120.30.10
      name: Turn-by-Turn Directions
      url: /capabilities/routing-navigation/
      via_parent: Routing & Navigation
    credit: null
    layer: common
    name: Google Maps Platform
    provider: google-maps
    says: lists Google Maps Platform as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-961
      key: AE-961
      name: Carrier Vetting & Fraud Monitoring
      url: /capabilities/carrier-vetting-fraud-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Highway
    provider: highway
    says: lists Highway as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://www.roserocket.com/integrations
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
    name: Microsoft Dynamics 365 Business Central
    provider: microsoft-dynamics-365-business-central
    says: lists Microsoft Dynamics 365 Business Central as an integration
    source: https://www.roserocket.com/integrations
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
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Rainforest
    provider: rainforest
    says: lists Rainforest as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-961
      key: AE-961
      name: Carrier Vetting & Fraud Monitoring
      url: /capabilities/carrier-vetting-fraud-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: RMIS
    provider: rmis
    says: lists RMIS as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2520
      key: freight-rating-tariff-management
      name: Freight Rating & Tariff Management
      url: /capabilities/freight-rating-tariff-management/
      via_parent: null
    credit: null
    layer: domain
    name: SMC3
    provider: smc3
    says: lists SMC3 as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: Snowflake
    provider: snowflake
    says: lists Snowflake as an integration
    source: https://www.roserocket.com/integrations
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
    name: SPS Commerce
    provider: sps-commerce
    says: lists SPS Commerce as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Terminal (withterminal.com)
    provider: terminal-telematics
    says: lists Terminal (withterminal.com) as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30.10
      key: AE-120.30.10
      name: Turn-by-Turn Directions
      url: /capabilities/routing-navigation/
      via_parent: Routing & Navigation
    credit: null
    layer: common
    name: Trimble
    provider: trimble
    says: lists Trimble as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2530.20
      key: freight-audit-and-payment-management
      name: Freight Audit and Payment Management
      url: /capabilities/freight-audit-and-payment-management/
      via_parent: null
    credit: null
    layer: domain
    name: TriumphPay
    provider: triumphpay
    says: lists TriumphPay as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510
      key: shipment-visibility-tracking-management
      name: Shipment Visibility & Tracking Management
      url: /capabilities/shipment-visibility-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: Trucker Tools
    provider: trucker-tools
    says: lists Trucker Tools as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2400
      key: freight-capacity-management
      name: Freight Capacity Management
      url: /capabilities/freight-capacity-management/
      via_parent: null
    credit: null
    layer: domain
    name: Truckstop
    provider: truckstop
    says: lists Truckstop as an integration
    source: https://www.roserocket.com/integrations
    tier: declared
  kind: commercial
  name: Rose Rocket
  page: /applications/freight-tms/rose-rocket/
  slug: rose-rocket
  url: https://www.roserocket.com/
- anchor: revenova-tms
  counts:
    declared: 5
    observed: 0
  evidence:
  - route: integrations page
    url: https://revenova.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2480.20
      key: customs-declaration-management
      name: Customs Declaration Management
      url: /capabilities/customs-declaration-management/
      via_parent: null
    credit: null
    layer: domain
    name: BorderConnect
    provider: borderconnect
    says: lists BorderConnect as an integration
    source: https://revenova.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Drumkit
    provider: drumkit
    says: lists Drumkit as an integration
    source: https://revenova.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510
      key: shipment-visibility-tracking-management
      name: Shipment Visibility & Tracking Management
      url: /capabilities/shipment-visibility-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: OpenTrack
    provider: opentrack
    says: lists OpenTrack as an integration
    source: https://revenova.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://revenova.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2520
      key: freight-rating-tariff-management
      name: Freight Rating & Tariff Management
      url: /capabilities/freight-rating-tariff-management/
      via_parent: null
    credit: null
    layer: domain
    name: SMC3
    provider: smc3
    says: lists SMC3 as an integration
    source: https://revenova.com/integrations/
    tier: declared
  kind: commercial
  name: Revenova TMS
  page: /applications/freight-tms/revenova-tms/
  slug: revenova-tms
  url: https://revenova.com/
- anchor: descartes-aljex
  counts:
    declared: 19
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.aljex.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-220.40
      key: tax-reporting-compliance
      name: Tax Reporting & Compliance
      url: /capabilities/tax-reporting-compliance/
      via_parent: null
    credit: null
    layer: common
    name: 1099 Pro
    provider: 1099-pro
    says: lists 1099 Pro as an integration
    source: https://www.aljex.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2400
      key: freight-capacity-management
      name: Freight Capacity Management
      url: /capabilities/freight-capacity-management/
      via_parent: null
    credit: null
    layer: domain
    name: 123Loadboard
    provider: 123loadboard
    says: lists 123Loadboard as an integration
    source: https://www.aljex.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.20
      key: accounts-payable-management
      name: Accounts Payable Management
      url: /capabilities/accounts-payable-management/
      via_parent: null
    credit: null
    layer: common
    name: BILL
    provider: bill
    says: lists BILL as an integration
    source: https://www.aljex.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2530.20
      key: freight-audit-and-payment-management
      name: Freight Audit and Payment Management
      url: /capabilities/freight-audit-and-payment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Breakthrough Fuel
    provider: breakthrough-fuel
    says: lists Breakthrough Fuel as an integration
    source: https://www.aljex.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2520
      key: freight-rating-tariff-management
      name: Freight Rating & Tariff Management
      url: /capabilities/freight-rating-tariff-management/
      via_parent: null
    credit: null
    layer: domain
    name: Carrier1
    provider: carrier1
    says: lists Carrier1 as an integration
    source: https://www.aljex.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    credit: null
    layer: common
    name: Corpay
    provider: corpay
    says: lists Corpay as an integration
    source: https://www.aljex.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2400
      key: freight-capacity-management
      name: Freight Capacity Management
      url: /capabilities/freight-capacity-management/
      via_parent: null
    credit: null
    layer: domain
    name: DAT Freight & Analytics
    provider: dat-freight
    says: lists DAT Freight & Analytics as an integration
    source: https://www.aljex.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2530.20
      key: freight-audit-and-payment-management
      name: Freight Audit and Payment Management
      url: /capabilities/freight-audit-and-payment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Denim
    provider: denim
    says: lists Denim as an integration
    source: https://www.aljex.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510
      key: shipment-visibility-tracking-management
      name: Shipment Visibility & Tracking Management
      url: /capabilities/shipment-visibility-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: Descartes Systems Group
    provider: descartes
    says: lists Descartes Systems Group as an integration
    source: https://www.aljex.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2400
      key: freight-capacity-management
      name: Freight Capacity Management
      url: /capabilities/freight-capacity-management/
      via_parent: null
    credit: null
    layer: domain
    name: Direct Freight
    provider: direct-freight
    says: lists Direct Freight as an integration
    source: https://www.aljex.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2530.20
      key: freight-audit-and-payment-management
      name: Freight Audit and Payment Management
      url: /capabilities/freight-audit-and-payment-management/
      via_parent: null
    credit: null
    layer: domain
    name: EpayManager
    provider: epaymanager
    says: lists EpayManager as an integration
    source: https://www.aljex.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2400
      key: freight-capacity-management
      name: Freight Capacity Management
      url: /capabilities/freight-capacity-management/
      via_parent: null
    credit: null
    layer: domain
    name: FleetWorks
    provider: fleetworks
    says: lists FleetWorks as an integration
    source: https://www.aljex.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2520
      key: freight-rating-tariff-management
      name: Freight Rating & Tariff Management
      url: /capabilities/freight-rating-tariff-management/
      via_parent: null
    credit: null
    layer: domain
    name: FreightWaves
    provider: freightwaves
    says: lists FreightWaves as an integration
    source: https://www.aljex.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2530.20
      key: freight-audit-and-payment-management
      name: Freight Audit and Payment Management
      url: /capabilities/freight-audit-and-payment-management/
      via_parent: null
    credit: null
    layer: domain
    name: HaulPay
    provider: haulpay
    says: lists HaulPay as an integration
    source: https://www.aljex.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-961
      key: AE-961
      name: Carrier Vetting & Fraud Monitoring
      url: /capabilities/carrier-vetting-fraud-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Highway
    provider: highway
    says: lists Highway as an integration
    source: https://www.aljex.com/integrations/
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
    name: Kleinschmidt
    provider: kleinschmidt
    says: lists Kleinschmidt as an integration
    source: https://www.aljex.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2520
      key: freight-rating-tariff-management
      name: Freight Rating & Tariff Management
      url: /capabilities/freight-rating-tariff-management/
      via_parent: null
    credit: null
    layer: domain
    name: Logistical Labs
    provider: logistical-labs
    says: lists Logistical Labs as an integration
    source: https://www.aljex.com/integrations/
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
    name: Microsoft Dynamics GP
    provider: microsoft-dynamics-365
    says: lists Microsoft Dynamics GP as an integration
    source: https://www.aljex.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    credit: null
    layer: common
    name: WEX
    provider: wex
    says: lists WEX as an integration
    source: https://www.aljex.com/integrations/
    tier: declared
  kind: commercial
  name: Descartes Aljex
  page: /applications/freight-tms/descartes-aljex/
  slug: descartes-aljex
  url: https://www.aljex.com/
- anchor: 3g-tms
  counts:
    declared: 4
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.3gtms.com/partners/
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
    name: Cavallo
    provider: cavallo
    says: lists Cavallo as an integration
    source: https://www.3gtms.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510
      key: shipment-visibility-tracking-management
      name: Shipment Visibility & Tracking Management
      url: /capabilities/shipment-visibility-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: Descartes Systems Group
    provider: descartes
    says: lists Descartes Systems Group as an integration
    source: https://www.3gtms.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: IntelliShift
    provider: intellishift
    says: lists IntelliShift as an integration
    source: https://www.3gtms.com/partners/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420
      key: transport-operations-management
      name: Transport Operations Management
      url: /capabilities/transport-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: PITT OHIO
    provider: pitt-ohio
    says: lists PITT OHIO as an integration
    source: https://www.3gtms.com/partners/
    tier: declared
  kind: commercial
  name: 3G TMS
  page: /applications/freight-tms/3g-tms/
  slug: 3g-tms
  url: https://www.3gtms.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: freight-tms
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Transportation Management Systems (TMS)
  store: g2
  url: https://www.g2.com/categories/transportation-management-systems-tms
- category: Transportation Management Software
  store: capterra
  url: https://www.capterra.com/transportation-management-software/
- category: Logistics (Revenova TMS listing)
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
name: Freight & Transportation Management
needs:
- capability:
    attribution: Turbo EA
    id: BC-2430.40
    key: fleet-telematics-and-monitoring
    name: Fleet Telematics and Monitoring
    url: /capabilities/fleet-telematics-and-monitoring/
    via_parent: null
  fit: exact
  layer: domain
  why: ELD / GPS feeds from Geotab, Samsara and regional telematics
- capability:
    attribution: Turbo EA
    id: BC-2400
    key: freight-capacity-management
    name: Freight Capacity Management
    url: /capabilities/freight-capacity-management/
    via_parent: null
  fit: exact
  layer: domain
  why: load boards and digital freight matching (DAT, Truckstop, 123Loadboard)
- capability:
    attribution: Turbo EA
    id: BC-2520
    key: freight-rating-tariff-management
    name: Freight Rating & Tariff Management
    url: /capabilities/freight-rating-tariff-management/
    via_parent: null
  fit: exact
  layer: domain
  why: LTL tariffs (SMC3) and market rate data (SONAR, DAT)
- capability:
    attribution: Turbo EA
    id: BC-2510
    key: shipment-visibility-tracking-management
    name: Shipment Visibility & Tracking Management
    url: /capabilities/shipment-visibility-tracking-management/
    via_parent: null
  fit: exact
  layer: domain
  why: in-transit visibility networks (Macropoint, FourKites, Trucker Tools)
- capability:
    attribution: Turbo EA
    id: BC-2530.20
    key: freight-audit-and-payment-management
    name: Freight Audit and Payment Management
    url: /capabilities/freight-audit-and-payment-management/
    via_parent: null
  fit: exact
  layer: domain
  why: carrier pay, factoring and quick-pay (TriumphPay, Denim, HaulPay)
- capability:
    attribution: API Evangelist extension
    id: AE-961
    key: AE-961
    name: Carrier Vetting & Fraud Monitoring
    url: /capabilities/carrier-vetting-fraud-monitoring/
    via_parent: null
  fit: exact
  layer: domain
  why: 'Carrier Vetting & Fraud Monitoring: Highway, RMIS'
- capability:
    attribution: Turbo EA
    id: BC-2480.20
    key: customs-declaration-management
    name: Customs Declaration Management
    url: /capabilities/customs-declaration-management/
    via_parent: null
  fit: exact
  layer: domain
  why: ACE/ACI eManifest for US-Canada freight
- capability:
    attribution: Turbo EA
    id: BC-2460
    key: warehousing-operations-management
    name: Warehousing Operations Management
    url: /capabilities/warehousing-operations-management/
    via_parent: null
  fit: exact
  layer: domain
  why: warehouse / intermodal handoff
- capability:
    attribution: Turbo EA
    id: BC-2420
    key: transport-operations-management
    name: Transport Operations Management
    url: /capabilities/transport-operations-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: direct carrier connectivity; nearest
- capability:
    attribution: Turbo EA
    id: BC-1050.20.20
    key: BC-1050.20.20
    name: Route Optimisation
    url: /capabilities/service-dispatch-management/
    via_parent: Service Dispatch Management
  fit: exact
  layer: domain
  why: 'Route Optimisation: VROOM (Vehicle Routing Open-source Optimization Machine)'
- capability:
    attribution: API Evangelist extension
    id: AE-919
    key: AE-919
    name: B2B EDI & Trading-Partner Networks
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: common
  why: 'B2B EDI & Trading-Partner Networks: Bitfreighter, SPS Commerce, Kleinschmidt'
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: common
  why: accounting / ERP sync of invoices and payables
- capability:
    attribution: Turbo EA
    id: BC-200.20
    key: accounts-payable-management
    name: Accounts Payable Management
    url: /capabilities/accounts-payable-management/
    via_parent: null
  fit: exact
  layer: common
  why: bill pay
- capability:
    attribution: Turbo EA
    id: BC-220.40
    key: tax-reporting-compliance
    name: Tax Reporting & Compliance
    url: /capabilities/tax-reporting-compliance/
    via_parent: null
  fit: exact
  layer: common
  why: 1099 filing for owner-operators
- capability:
    attribution: API Evangelist extension
    id: AE-940
    key: AE-940
    name: Fleet Fuel Cards & Fuel Transaction Data
    url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
    via_parent: null
  fit: exact
  layer: common
  why: 'Fleet Fuel Cards & Fuel Transaction Data: Corpay, WEX'
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: customer card / ACH collection
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: common
  why: warehouse export to Snowflake / BigQuery
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: common
  why: CRM sync; Revenova runs on Salesforce
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: team notifications
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  fit: exact
  layer: common
  why: developer tooling
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: notification email drivers
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  fit: exact
  layer: common
  why: live dispatch / tracking broadcast
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: common
  why: address geocoding for stops
- capability:
    attribution: API Evangelist extension
    id: AE-120.30.10
    key: AE-120.30.10
    name: Turn-by-Turn Directions
    url: /capabilities/routing-navigation/
    via_parent: Routing & Navigation
  fit: exact
  layer: common
  why: truck routing and mileage (Valhalla, Google, Trimble Maps)
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: document / POD storage; no generic object-storage capability
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - Fleetbase
      - Rose Rocket
      band: thin
      in_catalog: true
      kin_score: 36.9
      mcp:
        source: https://mcp.geotab.com/mygeotab
        status: verified
      name: Geotab
      slug: geotab
      sources:
      - https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - ELD Compliance
      - Fleet Management
      - Telematics
      - Vehicle Tracking
      tier: observed
      url: /providers/geotab/
    - agent_band: agent-aware
      agent_readiness: 23.0
      apps:
      - Fleetbase
      band: developing
      in_catalog: true
      kin_score: 43.5
      mcp:
        status: unchecked
      name: flespi
      slug: flespi
      sources:
      - https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
      status: profiled
      tags:
      - Data Ingestion
      - IoT
      - Real-Time Analytics
      - Telematics
      tier: observed
      url: /providers/flespi/
    - agent_band: agent-aware
      agent_readiness: 19.9
      apps:
      - Fleetbase
      band: thin
      in_catalog: true
      kin_score: 32.0
      mcp:
        source: https://mcp.samsara.com/mcp
        status: documented
      name: Samsara
      slug: samsara
      sources:
      - https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
      status: profiled
      tags:
      - Asset Tracking
      - Connected Operations
      - ELD
      - Fleet Management
      tier: observed
      url: /providers/samsara/
    - agent_band: agent-aware
      agent_readiness: 21.4
      apps:
      - Fleetbase
      band: minimal
      in_catalog: true
      kin_score: 8.3
      mcp:
        status: unchecked
      name: Safee
      slug: safee
      sources:
      - https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
      status: profiled
      tags:
      - Fleet Management
      - GPS Tracking
      - Telematics
      - Vehicle-Analytics
      tier: observed
      url: /providers/safee/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Fleetbase
      band: minimal
      in_catalog: true
      kin_score: 4.5
      mcp:
        status: unchecked
      name: Afaqy
      slug: afaqy
      sources:
      - https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
      status: profiled
      tags:
      - AVL
      - Fleet Management
      - IoT
      - Smart Parking
      tier: observed
      url: /providers/afaqy/
    - agent_band: agent-ready
      agent_readiness: 47.0
      apps:
      - Rose Rocket
      band: developing
      in_catalog: true
      kin_score: 52.5
      mcp:
        status: unchecked
      name: Terminal (withterminal.com)
      slug: terminal-telematics
      sources:
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Company
      - Data
      - Fleet Management
      - Telematics
      tier: declared
      url: /providers/terminal-telematics/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Revenova TMS
      band: emerging
      in_catalog: true
      kin_score: 17.2
      mcp:
        status: unchecked
      name: Drumkit
      slug: drumkit
      sources:
      - https://revenova.com/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Email Integration
      - Logistics
      tier: declared
      url: /providers/drumkit/
    - agent_band: agent-aware
      agent_readiness: 21.4
      apps:
      - 3G TMS
      band: emerging
      in_catalog: true
      kin_score: 15.7
      mcp:
        status: unchecked
      name: IntelliShift
      slug: intellishift
      sources:
      - https://www.3gtms.com/partners/
      status: profiled
      tags:
      - AI Dashcams
      - Compliance
      - Fleet Management
      - Telematics
      tier: declared
      url: /providers/intellishift/
  - capability:
      attribution: Turbo EA
      id: BC-2400
      key: freight-capacity-management
      name: Freight Capacity Management
      url: /capabilities/freight-capacity-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Descartes Aljex
      - Rose Rocket
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        source: https://developer.dat.com/mcp
        status: verified
      name: DAT Freight & Analytics
      slug: dat-freight
      sources:
      - https://www.aljex.com/integrations/
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Freight
      - Load Board
      - Logistics
      - Trucking
      tier: declared
      url: /providers/dat-freight/
    - agent_band: agent-aware
      agent_readiness: 23.1
      apps:
      - Fleetbase
      band: developing
      in_catalog: true
      kin_score: 44.0
      mcp:
        status: none
      name: Lalamove
      slug: lalamove
      sources:
      - https://github.com/fleetbase/fleetops/tree/main/server/src/Integrations
      status: profiled
      tags:
      - Company
      - Delivery
      - Logistics
      - Technology
      tier: observed
      url: /providers/lalamove/
    - agent_band: agent-ready
      agent_readiness: 29.0
      apps:
      - Descartes Aljex
      band: thin
      in_catalog: true
      kin_score: 31.9
      mcp:
        status: unchecked
      name: Direct Freight
      slug: direct-freight
      sources:
      - https://www.aljex.com/integrations/
      status: profiled
      tags:
      - Carrier
      - Freight Brokers
      - Load Board
      - Shippers
      tier: declared
      url: /providers/direct-freight/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Descartes Aljex
      band: emerging
      in_catalog: true
      kin_score: 23.5
      mcp:
        status: unchecked
      name: 123Loadboard
      slug: 123loadboard
      sources:
      - https://www.aljex.com/integrations/
      status: profiled
      tags:
      - Freight
      - Load Board
      - Logistics
      - Marketplace
      tier: declared
      url: /providers/123loadboard/
    - agent_band: agent-aware
      agent_readiness: 13.3
      apps:
      - Rose Rocket
      band: emerging
      in_catalog: true
      kin_score: 17.7
      mcp:
        source: https://mcp.truckstop.com/mcp
        status: documented
      name: Truckstop
      slug: truckstop
      sources:
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Freight
      - Load Board
      - Logistics
      - Trucking
      tier: declared
      url: /providers/truckstop/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Descartes Aljex
      band: emerging
      in_catalog: true
      kin_score: 12.9
      mcp:
        status: unchecked
      name: FleetWorks
      slug: fleetworks
      sources:
      - https://www.aljex.com/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Freight
      - Logistics
      tier: declared
      url: /providers/fleetworks/
  - capability:
      attribution: Turbo EA
      id: BC-2510
      key: shipment-visibility-tracking-management
      name: Shipment Visibility & Tracking Management
      url: /capabilities/shipment-visibility-tracking-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - 3G TMS
      - Descartes Aljex
      - Rose Rocket
      band: developing
      in_catalog: true
      kin_score: 42.2
      mcp:
        status: unknown
      name: Descartes Systems Group
      slug: descartes
      sources:
      - https://www.3gtms.com/partners/
      - https://www.aljex.com/integrations/
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Freight Visibility
      - Logistics
      - Shipment Tracking
      - Supply Chain
      tier: declared
      url: /providers/descartes/
    - agent_band: agent-ready
      agent_readiness: 49.5
      apps:
      - Revenova TMS
      band: developing
      in_catalog: true
      kin_score: 54.0
      mcp:
        status: unchecked
      name: OpenTrack
      slug: opentrack
      sources:
      - https://revenova.com/integrations/
      status: profiled
      tags:
      - API Integration
      - Container Visibility
      - Freight Tracking
      - Logistics Software
      tier: declared
      url: /providers/opentrack/
    - agent_band: agent-ready
      agent_readiness: 46.7
      apps:
      - Rose Rocket
      band: emerging
      in_catalog: true
      kin_score: 17.1
      mcp:
        status: unchecked
      name: Trucker Tools
      slug: trucker-tools
      sources:
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Company
      - Freight
      - Load Tracking
      - Logistics
      tier: declared
      url: /providers/trucker-tools/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Rose Rocket
      band: minimal
      in_catalog: true
      kin_score: 6.5
      mcp:
        source: https://www.fourkites.ai/engineering-blog/mcp-gateway
        status: documented
      name: FourKites
      slug: fourkites
      sources:
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Freight
      - Logistics
      - Supply Chain Visibility
      - Tracking
      tier: declared
      url: /providers/fourkites/
    - agent_band: null
      agent_readiness: null
      apps:
      - Rose Rocket
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Chain.io
      slug: chain-io
      sources:
      - https://www.roserocket.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-2530.20
      key: freight-audit-and-payment-management
      name: Freight Audit and Payment Management
      url: /capabilities/freight-audit-and-payment-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Descartes Aljex
      - Rose Rocket
      band: emerging
      in_catalog: true
      kin_score: 18.0
      mcp:
        status: unchecked
      name: EpayManager
      slug: epaymanager
      sources:
      - https://www.aljex.com/integrations/
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Automation
      - Finance
      - Logistics
      - Payments
      tier: declared
      url: /providers/epaymanager/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Descartes Aljex
      band: developing
      in_catalog: true
      kin_score: 49.4
      mcp:
        status: unknown
      name: Denim
      slug: denim
      sources:
      - https://www.aljex.com/integrations/
      status: profiled
      tags:
      - Company
      - Factoring
      - Freight
      - Payments
      tier: declared
      url: /providers/denim/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Rose Rocket
      band: emerging
      in_catalog: true
      kin_score: 12.8
      mcp:
        status: unchecked
      name: TriumphPay
      slug: triumphpay
      sources:
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Carrier Solutions
      - Equipment Financing
      - Factoring
      - Payments
      tier: declared
      url: /providers/triumphpay/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Descartes Aljex
      band: emerging
      in_catalog: true
      kin_score: 11.0
      mcp:
        status: unchecked
      name: HaulPay
      slug: haulpay
      sources:
      - https://www.aljex.com/integrations/
      status: profiled
      tags:
      - Company
      - Finance
      - Freight
      - Payments
      tier: declared
      url: /providers/haulpay/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Descartes Aljex
      band: minimal
      in_catalog: true
      kin_score: 8.9
      mcp:
        status: unchecked
      name: Breakthrough Fuel
      slug: breakthrough-fuel
      sources:
      - https://www.aljex.com/integrations/
      status: profiled
      tags:
      - Company
      - Fuel Management
      - Logistics
      - Transportation
      tier: declared
      url: /providers/breakthrough-fuel/
  - capability:
      attribution: Turbo EA
      id: BC-2520
      key: freight-rating-tariff-management
      name: Freight Rating & Tariff Management
      url: /capabilities/freight-rating-tariff-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.8
      apps:
      - Revenova TMS
      - Rose Rocket
      band: minimal
      in_catalog: true
      kin_score: 7.7
      mcp:
        status: unchecked
      name: SMC3
      slug: smc3
      sources:
      - https://revenova.com/integrations/
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Company
      - Logistics
      - Pricing
      - Transportation
      tier: declared
      url: /providers/smc3/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Descartes Aljex
      band: emerging
      in_catalog: true
      kin_score: 15.5
      mcp:
        status: unchecked
      name: Carrier1
      slug: carrier1
      sources:
      - https://www.aljex.com/integrations/
      status: profiled
      tags:
      - Company
      - Freight
      - Logistics
      - Platform
      tier: declared
      url: /providers/carrier1/
    - agent_band: null
      agent_readiness: null
      apps:
      - Descartes Aljex
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: FreightWaves
      slug: freightwaves
      sources:
      - https://www.aljex.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Descartes Aljex
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Logistical Labs
      slug: logistical-labs
      sources:
      - https://www.aljex.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-961
      key: AE-961
      name: Carrier Vetting & Fraud Monitoring
      url: /capabilities/carrier-vetting-fraud-monitoring/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Descartes Aljex
      - Rose Rocket
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Highway
      slug: highway
      sources:
      - https://www.aljex.com/integrations/
      - https://www.roserocket.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Rose Rocket
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: RMIS
      slug: rmis
      sources:
      - https://www.roserocket.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-2480.20
      key: customs-declaration-management
      name: Customs Declaration Management
      url: /capabilities/customs-declaration-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Revenova TMS
      - Rose Rocket
      band: minimal
      in_catalog: true
      kin_score: 6.7
      mcp:
        status: unchecked
      name: BorderConnect
      slug: borderconnect
      sources:
      - https://revenova.com/integrations/
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/borderconnect/
  - capability:
      attribution: Turbo EA
      id: BC-1050.20.20
      key: BC-1050.20.20
      name: Route Optimisation
      url: /capabilities/service-dispatch-management/
      via_parent: Service Dispatch Management
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Fleetbase
      band: emerging
      in_catalog: true
      kin_score: 12.1
      mcp:
        status: unchecked
      name: VROOM (Vehicle Routing Open-source Optimization Machine)
      slug: vroom-project
      sources:
      - https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
      status: profiled
      tags:
      - Company
      - Open Source
      - Optimization
      - Routing
      tier: observed
      url: /providers/vroom-project/
  - capability:
      attribution: Turbo EA
      id: BC-2420
      key: transport-operations-management
      name: Transport Operations Management
      url: /capabilities/transport-operations-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - 3G TMS
      band: minimal
      in_catalog: true
      kin_score: 6.0
      mcp:
        status: unchecked
      name: PITT OHIO
      slug: pitt-ohio
      sources:
      - https://www.3gtms.com/partners/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/pitt-ohio/
  - capability:
      attribution: Turbo EA
      id: BC-2460
      key: warehousing-operations-management
      name: Warehousing Operations Management
      url: /capabilities/warehousing-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - Rose Rocket
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp:
        status: unchecked
      name: CartonCloud
      slug: cartoncloud
      sources:
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Logistics
      - Software
      - Transportation
      - Warehouse Management
      tier: declared
      url: /providers/cartoncloud/
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
      agent_readiness: 39.9
      apps:
      - Rose Rocket
      band: exemplar
      in_catalog: true
      kin_score: 73.1
      mcp:
        status: none
      name: Microsoft Dynamics 365 Business Central
      slug: microsoft-dynamics-365-business-central
      sources:
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Accounting
      - Cloud ERP
      - ERP
      - Finance
      tier: declared
      url: /providers/microsoft-dynamics-365-business-central/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Descartes Aljex
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        source: https://github.com/microsoft/Dataverse-MCP
        status: verified
      name: Microsoft Dynamics GP
      slug: microsoft-dynamics-365
      sources:
      - https://www.aljex.com/integrations/
      status: profiled
      tags:
      - Business Applications
      - CRM
      - Cloud
      - Enterprise
      tier: declared
      url: /providers/microsoft-dynamics-365/
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Rose Rocket
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks Online
      slug: quickbooks
      sources:
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - 3G TMS
      band: minimal
      in_catalog: true
      kin_score: 10.6
      mcp:
        status: unchecked
      name: Cavallo
      slug: cavallo
      sources:
      - https://www.3gtms.com/partners/
      status: profiled
      tags:
      - Distribution Software
      - ERP Integration
      - Order-to-Cash
      - Profitability
      tier: declared
      url: /providers/cavallo/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - Fleetbase
      band: exemplar
      in_catalog: true
      kin_score: 84.0
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Fleetbase
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/ActiveCampaign/postmark-mcp
        status: verified
      name: Postmark
      slug: postmark
      sources:
      - https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
      status: profiled
      tags:
      - Deliverability
      - Email
      - Messaging
      - Transactional Email
      tier: observed
      url: /providers/postmark/
    - agent_band: agent-ready
      agent_readiness: 49.8
      apps:
      - Fleetbase
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        source: https://resend.com/docs/mcp-server
        status: verified
      name: Resend
      slug: resend
      sources:
      - https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
      status: profiled
      tags:
      - Developer Tools
      - Email
      - Marketing Email
      - Transactional Email
      tier: observed
      url: /providers/resend/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Fleetbase
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
      status: profiled
      tags:
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailgun/
  - capability:
      attribution: API Evangelist extension
      id: AE-919
      key: AE-919
      name: B2B EDI & Trading-Partner Networks
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.4
      apps:
      - Rose Rocket
      band: strong
      in_catalog: true
      kin_score: 59.5
      mcp:
        status: none
      name: SPS Commerce
      slug: sps-commerce
      sources:
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Company
      - EDI
      - Retail
      - Supply Chain
      tier: declared
      url: /providers/sps-commerce/
    - agent_band: agent-ready
      agent_readiness: 44.0
      apps:
      - Rose Rocket
      band: developing
      in_catalog: true
      kin_score: 39.6
      mcp:
        status: unchecked
      name: Bitfreighter
      slug: bitfreighter
      sources:
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Company
      - EDI
      - Freight
      - Logistics
      tier: declared
      url: /providers/bitfreighter/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Descartes Aljex
      band: emerging
      in_catalog: true
      kin_score: 12.5
      mcp:
        status: unchecked
      name: Kleinschmidt
      slug: kleinschmidt
      sources:
      - https://www.aljex.com/integrations/
      status: profiled
      tags:
      - Automation
      - Company
      - Control Systems
      - Industrial
      tier: declared
      url: /providers/kleinschmidt/
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.1
      apps:
      - Descartes Aljex
      - Rose Rocket
      band: minimal
      in_catalog: true
      kin_score: 6.9
      mcp:
        status: unknown
      name: Corpay
      slug: corpay
      sources:
      - https://www.aljex.com/integrations/
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Accounts Payable
      - Corporate Payments
      - Cross-Border Payments
      - Payments
      tier: declared
      url: /providers/corpay/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Descartes Aljex
      band: minimal
      in_catalog: true
      kin_score: 9.7
      mcp:
        status: none
      name: WEX
      slug: wex
      sources:
      - https://www.aljex.com/integrations/
      status: profiled
      tags: []
      tier: declared
      url: /providers/wex/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30.10
      key: AE-120.30.10
      name: Turn-by-Turn Directions
      url: /capabilities/routing-navigation/
      via_parent: Routing & Navigation
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.0
      apps:
      - Fleetbase
      band: emerging
      in_catalog: true
      kin_score: 24.4
      mcp:
        status: none
      name: Valhalla
      slug: valhalla
      sources:
      - https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
      status: profiled
      tags:
      - Mapping
      - Navigation
      - OpenStreetMap
      - Routing
      tier: observed
      url: /providers/valhalla/
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Rose Rocket
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp: &id001
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps Platform
      slug: google-maps
      sources:
      - https://www.roserocket.com/integrations
      status: profiled
      tags: &id002
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: declared
      url: /providers/google-maps/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Rose Rocket
      band: exemplar
      in_catalog: true
      kin_score: 66.6
      mcp:
        status: none
      name: Trimble
      slug: trimble
      sources:
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Construction
      - GPS
      - Geospatial
      - Transportation
      tier: declared
      url: /providers/trimble/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 44.9
      apps:
      - Rose Rocket
      band: exemplar
      in_catalog: true
      kin_score: 82.3
      mcp:
        source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
        status: verified
      name: Snowflake
      slug: snowflake
      sources:
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Data
      - Data Lakehouse
      - Data Warehouse
      - Snowflake
      tier: declared
      url: /providers/snowflake/
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - Rose Rocket
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
        status: verified
      name: Google BigQuery
      slug: google-bigquery
      sources:
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Cloud
      - Data Warehouse
      tier: declared
      url: /providers/google-bigquery/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Rose Rocket
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Revenova TMS
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://revenova.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Fleetbase
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-native
      agent_readiness: 41.8
      apps:
      - Rose Rocket
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp:
        status: unknown
      name: Rainforest
      slug: rainforest
      sources:
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Company
      - Embedded Payments
      - Payment Facilitator
      - Payments
      tier: declared
      url: /providers/rainforest/
  - capability:
      attribution: Turbo EA
      id: BC-200.20
      key: accounts-payable-management
      name: Accounts Payable Management
      url: /capabilities/accounts-payable-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.7
      apps:
      - Descartes Aljex
      band: developing
      in_catalog: true
      kin_score: 51.7
      mcp:
        source: https://developer.bill.com/docs/bill-mcp-server
        status: verified
      name: BILL
      slug: bill
      sources:
      - https://www.aljex.com/integrations/
      status: profiled
      tags:
      - Accounts Payable
      - Accounts Receivable
      - Expense Management
      - Spend Management
      tier: declared
      url: /providers/bill/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Fleetbase
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp: *id001
      name: Google Maps Platform
      slug: google-maps
      sources:
      - https://raw.githubusercontent.com/fleetbase/fleetops/main/composer.json
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-maps/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Rose Rocket
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://www.roserocket.com/integrations
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - Fleetbase
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Pusher
      slug: pusher
      sources:
      - https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/.env.example
      status: profiled
      tags:
      - Pub/Sub
      - Push Notifications
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/pusher/
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Rose Rocket
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://www.roserocket.com/integrations
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
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Fleetbase
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
  - capability:
      attribution: Turbo EA
      id: BC-220.40
      key: tax-reporting-compliance
      name: Tax Reporting & Compliance
      url: /capabilities/tax-reporting-compliance/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Descartes Aljex
      band: thin
      in_catalog: true
      kin_score: 28.4
      mcp:
        status: unchecked
      name: 1099 Pro
      slug: 1099-pro
      sources:
      - https://www.aljex.com/integrations/
      status: profiled
      tags:
      - Compliance
      - Efiling
      - Software-as-a-Service
      - Tax Software
      tier: declared
      url: /providers/1099-pro/
  layer: common
summary:
  coverage_pct: 91.9
  declared_only: 46
  distinct_providers: 62
  in_catalog: 57
  mcp:
    documented: 3
    none: 8
    unchecked: 30
    verified: 17
  mcp_verified: 17
  mean_kin_score: 39.3
  observed: 16
  queued: 5
  reference_apps: 5
title: 'Freight & Transportation Management: application blueprint'
---
