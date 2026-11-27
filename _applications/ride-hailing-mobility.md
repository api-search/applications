---
access: understanding
agent_layer: []
apps:
- anchor: namma-yatri
  counts:
    declared: 0
    observed: 41
  evidence:
  - route: source code
    url: https://github.com/nammayatri/nammayatri
  - route: source code
    url: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-190.80.10
      key: AE-190.80.10
      name: Embedded Insurance
      url: /capabilities/personal-insurance/
      via_parent: Personal Insurance
    credit: null
    layer: domain
    name: Acko
    provider: acko
    says: ships the Acko SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Insurance/Acko
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
    name: BillDesk
    provider: billdesk
    says: ships the BillDesk SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Settlement/BillDesk
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Checkr
    provider: checkr
    says: ships the Checkr SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/BackgroundVerification/Checkr
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: CleverTap
    provider: clevertap
    says: ships the CleverTap SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/EventTracking/Clevertap
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30.10
      key: AE-160.30.10
      name: Document Verification
      url: /capabilities/identity-verification/
      via_parent: Identity Verification
    credit: null
    layer: domain
    name: DigiLocker
    provider: digilocker
    says: ships the DigiLocker SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Verification/Digilocker
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: common
    name: Exotel
    provider: exotel
    says: ships the Exotel SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Call/Exotel
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Exotel
    provider: exotel
    says: ships the Exotel SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/SMS/ExotelSms
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Notification/FCM
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: common
    name: Google Cloud Translation
    provider: google-translate
    says: ships the Google Cloud Translation SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/GoogleTranslate
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30.10
      key: AE-120.30.10
      name: Turn-by-Turn Directions
      url: /capabilities/routing-navigation/
      via_parent: Routing & Navigation
    credit: null
    layer: domain
    name: Google Maps Platform
    provider: google-maps
    says: ships the Google Maps Platform SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Maps/Google
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Google Maps Platform (Fleet Engine)
    provider: google-maps
    says: ships the Google Maps Platform (Fleet Engine) SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/FleetEngine
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30.10
      key: AE-160.30.10
      name: Document Verification
      url: /capabilities/identity-verification/
      via_parent: Identity Verification
    credit: null
    layer: domain
    name: Gridline
    provider: gridline
    says: ships the Gridline SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/AadhaarVerification/Gridline
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Gupshup
    provider: gupshup
    says: ships the Gupshup SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Whatsapp/GupShup
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-937
      key: AE-937
      name: Payouts & Disbursements
      url: /capabilities/payment-processing-management/
      via_parent: Payment Processing Management
    credit: null
    layer: common
    name: HDFC Bank
    provider: hdfc-bank
    says: ships the HDFC Bank SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Payout/HdfcCbx
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30.10
      key: AE-160.30.10
      name: Document Verification
      url: /capabilities/identity-verification/
      via_parent: Identity Verification
    credit: null
    layer: domain
    name: HyperVerge
    provider: hyperverge
    says: ships the HyperVerge SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Verification/HyperVerge
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30.10
      key: AE-160.30.10
      name: Document Verification
      url: /capabilities/identity-verification/
      via_parent: Identity Verification
    credit: null
    layer: domain
    name: IDfy
    provider: idfy
    says: ships the IDfy SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Verification/Idfy
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-190.80.10
      key: AE-190.80.10
      name: Embedded Insurance
      url: /capabilities/personal-insurance/
      via_parent: Personal Insurance
    credit: null
    layer: domain
    name: IFFCO-Tokio General Insurance
    provider: iffco-tokio
    says: ships the IFFCO-Tokio General Insurance SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Insurance/IffcoTokio
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Infobip
    provider: infobip
    says: ships the Infobip SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Infobip
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
    name: Juspay
    provider: juspay
    says: ships the Juspay SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Payment/Juspay
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Kaleyra
    provider: kaleyra
    says: ships the Kaleyra SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/SMS/KaleyraSms
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Kapture CX
    provider: kapture-cx
    says: ships the Kapture CX SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Ticket/Kapture
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Karix
    provider: karix
    says: ships the Karix SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/SMS/KarixSms
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30.10
      key: AE-120.30.10
      name: Turn-by-Turn Directions
      url: /capabilities/routing-navigation/
      via_parent: Routing & Navigation
    credit: null
    layer: domain
    name: MapmyIndia (Mappls)
    provider: mappls
    says: ships the MapmyIndia (Mappls) SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Maps/MMI
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: MoEngage
    provider: moengage
    says: ships the MoEngage SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/EventTracking/Moengage
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30.10
      key: AE-120.30.10
      name: Turn-by-Turn Directions
      url: /capabilities/routing-navigation/
      via_parent: Routing & Navigation
    credit: null
    layer: domain
    name: NextBillion.ai
    provider: nextbillion-ai
    says: ships the NextBillion.ai SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Maps/NextBillion
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.40
      key: AE-210.30.40
      name: Public Transit Data
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: OpenTripPlanner (self-hosted)
    provider: opentripplanner
    says: ships the OpenTripPlanner (self-hosted) SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/MultiModal/OpenTripPlanner
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30.10
      key: AE-120.30.10
      name: Turn-by-Turn Directions
      url: /capabilities/routing-navigation/
      via_parent: Routing & Navigation
    credit: null
    layer: domain
    name: OSRM (Project OSRM, self-hosted)
    provider: osrm
    says: ships the OSRM (Project OSRM, self-hosted) SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Maps/OSRM
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: common
    name: Ozonetel
    provider: ozonetel
    says: ships the Ozonetel SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Call/Ozonetel
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
    name: Paytm
    provider: paytm
    says: ships the Paytm SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Payment/PaytmEDC
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: SAP
    provider: sap
    says: ships the SAP SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/SAP
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.10
      key: AE-200.20.10
      name: Vehicle Data Access
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    credit: null
    layer: domain
    name: Signzy
    provider: signzy
    says: ships the Signzy SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/ChallanSearch/Signzy
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Slack
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
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Payment/Stripe
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Tata Communications
    provider: tata-communications
    says: ships the Tata Communications SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Whatsapp/TataCommunications
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/SMS/TwillioSms
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Call/Twillio
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: ValueFirst
    provider: valuefirst
    says: ships the ValueFirst SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/SMS/MyValueFirst
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Vonage
    provider: vonage
    says: ships the Vonage SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/SMS/VonageSms
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: WhatsApp Business Platform (Meta)
    provider: whatsapp
    says: ships the WhatsApp Business Platform (Meta) SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Meta
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
    name: YES Bank
    provider: yes-bank
    says: ships the YES Bank SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Settlement/YesBiz
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Zendesk
    provider: zendesk
    says: ships the Zendesk SDK or integration code
    source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Ticket/Zendesk
    tier: observed
  kind: open-source-saas
  name: Namma Yatri
  page: /applications/ride-hailing-mobility/namma-yatri/
  slug: namma-yatri
  url: https://github.com/nammayatri/nammayatri
- anchor: fleetbase-(fleet-ops)
  counts:
    declared: 0
    observed: 9
  evidence:
  - route: dependency manifest
    url: https://github.com/fleetbase/core-api/blob/main/composer.json
  - route: dependency manifest
    url: https://github.com/fleetbase/fleetops/blob/main/composer.json
  - route: dependency manifest
    url: https://github.com/fleetbase/fleetops/blob/main/package.json
  - route: source code
    url: https://github.com/fleetbase/fleetbase/blob/main/api/.env.example
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Apple (APNs)
    provider: apple
    says: ships the Apple (APNs) SDK or integration code
    source: https://github.com/fleetbase/core-api/blob/main/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: AWS
    provider: amazon-web-services
    says: ships the AWS SDK or integration code
    source: https://github.com/fleetbase/core-api/blob/main/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://github.com/fleetbase/core-api/blob/main/composer.json
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
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://github.com/fleetbase/core-api/blob/main/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: domain
    name: Google Places
    provider: google-places
    says: ships the Google Places SDK or integration code
    source: https://github.com/fleetbase/fleetops/blob/main/composer.json
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
    name: Microsoft Graph
    provider: microsoft-graph
    says: ships the Microsoft Graph SDK or integration code
    source: https://github.com/fleetbase/core-api/blob/main/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://github.com/fleetbase/core-api/blob/main/composer.json
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
    source: https://github.com/fleetbase/fleetops/blob/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/fleetbase/core-api/blob/main/composer.json
    tier: observed
  kind: self-hosted
  name: Fleetbase (Fleet-Ops)
  page: /applications/ride-hailing-mobility/fleetbase-fleet-ops/
  slug: fleetbase-fleet-ops
  url: https://github.com/fleetbase/fleetbase
- anchor: open-source-bike-share
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://github.com/cyklokoalicia/OpenSourceBikeShare/blob/master/composer.json
  - route: source code
    url: https://github.com/cyklokoalicia/OpenSourceBikeShare/blob/master/.env.dist
  - route: source code
    url: https://github.com/cyklokoalicia/OpenSourceBikeShare/tree/master/src/SmsConnector
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: EuroSms
    provider: eurosms
    says: ships the EuroSms SDK or integration code
    source: https://github.com/cyklokoalicia/OpenSourceBikeShare/tree/master/src/SmsConnector
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://github.com/cyklokoalicia/OpenSourceBikeShare/blob/master/.env.dist
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://github.com/cyklokoalicia/OpenSourceBikeShare/blob/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Textmagic
    provider: textmagic
    says: ships the Textmagic SDK or integration code
    source: https://github.com/cyklokoalicia/OpenSourceBikeShare/tree/master/src/SmsConnector
    tier: observed
  kind: self-hosted
  name: Open Source Bike Share
  page: /applications/ride-hailing-mobility/open-source-bike-share/
  slug: open-source-bike-share
  url: https://github.com/cyklokoalicia/OpenSourceBikeShare
- anchor: uber
  counts:
    declared: 1
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.ubercab/latest/
  - route: integrations page
    url: https://www.uber.com/us/en/ride/how-it-works/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ubercab/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ubercab/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: IAB Tech Lab
    provider: iab-tech-lab
    says: ships the IAB Tech Lab SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ubercab/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.50
      key: AE-210.30.50
      name: Micromobility & Bike Share
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Lime
    provider: lime
    says: lists Lime as an integration
    source: https://www.uber.com/us/en/ride/how-it-works/
    tier: declared
  kind: commercial
  name: Uber
  page: /applications/ride-hailing-mobility/uber/
  slug: uber
  url: https://www.uber.com/
- anchor: lyft
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/me.lyft.android/latest/
  - route: documentation
    url: https://help.lyft.com/hc/en-us/all/articles/115013080048-Accepted-payment-methods
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/me.lyft.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: IAB Tech Lab
    provider: iab-tech-lab
    says: ships the IAB Tech Lab SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/me.lyft.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/me.lyft.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Singular
    provider: singular
    says: ships the Singular SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/me.lyft.android/latest/
    tier: observed
  kind: commercial
  name: Lyft
  page: /applications/ride-hailing-mobility/lyft/
  slug: lyft
  url: https://www.lyft.com/
- anchor: lime
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.limebike/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.limebike/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.limebike/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.limebike/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.limebike/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Instabug
    provider: instabug
    says: ships the Instabug SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.limebike/latest/
    tier: observed
  kind: commercial
  name: Lime
  page: /applications/ride-hailing-mobility/lime/
  slug: lime
  url: https://www.li.me/
- anchor: bolt
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/ee.mtakso.client/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/ee.mtakso.client/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/ee.mtakso.client/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/ee.mtakso.client/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/ee.mtakso.client/latest/
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
    name: Mixpanel
    provider: mixpanel
    says: ships the Mixpanel SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/ee.mtakso.client/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/ee.mtakso.client/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Singular
    provider: singular
    says: ships the Singular SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/ee.mtakso.client/latest/
    tier: observed
  kind: commercial
  name: Bolt
  page: /applications/ride-hailing-mobility/bolt/
  slug: bolt
  url: https://bolt.eu/
- anchor: grab
  counts:
    declared: 0
    observed: 9
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Anagog
    provider: anagog
    says: ships the Anagog SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google AdMob
    provider: google-admob
    says: ships the Google AdMob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Leanplum
    provider: leanplum
    says: ships the Leanplum SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
    tier: observed
  kind: commercial
  name: Grab
  page: /applications/ride-hailing-mobility/grab/
  slug: grab
  url: https://www.grab.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: ride-hailing-mobility
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Travel
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Navigation
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Maps & Navigation
  store: google-play
  url: https://play.google.com/store/apps/category/MAPS_AND_NAVIGATION
- category: Travel & Local
  store: google-play
  url: https://play.google.com/store/apps/category/TRAVEL_AND_LOCAL
name: Ride-Hailing & Micromobility
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-120.30.10
    key: AE-120.30.10
    name: Turn-by-Turn Directions
    url: /capabilities/routing-navigation/
    via_parent: Routing & Navigation
  fit: exact
  layer: domain
  why: used by Namma Yatri
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.10
    key: AE-210.30.10
    name: Ride Hailing
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  fit: exact
  layer: domain
  why: used by Namma Yatri
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.40
    key: AE-210.30.40
    name: Public Transit Data
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  fit: exact
  layer: domain
  why: used by Namma Yatri
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: used by Fleetbase (Fleet-Ops), Namma Yatri
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: used by Fleetbase (Fleet-Ops), Namma Yatri, Open Source Bike Share
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.10
    key: AE-150.50.10
    name: Programmable Voice
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  fit: exact
  layer: common
  why: used by Namma Yatri
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: used by Namma Yatri
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: used by Fleetbase (Fleet-Ops), Namma Yatri
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  fit: exact
  layer: common
  why: used by Namma Yatri
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: common
  why: used by Namma Yatri
- capability:
    attribution: Turbo EA
    id: BC-300.10.20
    key: BC-300.10.20
    name: Candidate Screening and Selection
    url: /capabilities/talent-acquisition-management/
    via_parent: Talent Acquisition Management
  fit: exact
  layer: domain
  why: used by Namma Yatri
- capability:
    attribution: API Evangelist extension
    id: AE-160.30.10
    key: AE-160.30.10
    name: Document Verification
    url: /capabilities/identity-verification/
    via_parent: Identity Verification
  fit: exact
  layer: domain
  why: used by Namma Yatri
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  fit: nearest
  layer: domain
  why: used by Namma Yatri
- capability:
    attribution: API Evangelist extension
    id: AE-190.80.10
    key: AE-190.80.10
    name: Embedded Insurance
    url: /capabilities/personal-insurance/
    via_parent: Personal Insurance
  fit: exact
  layer: domain
  why: used by Namma Yatri
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: used by Namma Yatri
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: exact
  layer: common
  why: used by Namma Yatri
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: nearest
  layer: common
  why: used by Namma Yatri
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: used by Fleetbase (Fleet-Ops)
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: used by Fleetbase (Fleet-Ops)
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: used by Fleetbase (Fleet-Ops), Open Source Bike Share
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: domain
  why: used by Fleetbase (Fleet-Ops)
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: used by Open Source Bike Share
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.50
    key: AE-210.30.50
    name: Micromobility & Bike Share
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  fit: exact
  layer: domain
  why: used by Uber
- capability:
    attribution: Turbo EA
    id: BC-3760.30
    key: programmatic-sales-management
    name: Programmatic Sales Management
    url: /capabilities/programmatic-sales-management/
    via_parent: null
  fit: nearest
  layer: common
  why: ad measurement and ad SDKs in the mobile apps
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: install attribution / deep links in the mobile apps
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: nearest
  layer: common
  why: third-party sign-in in the mobile apps
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30.10
      key: AE-160.30.10
      name: Document Verification
      url: /capabilities/identity-verification/
      via_parent: Identity Verification
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.0
      apps:
      - Namma Yatri
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        status: unknown
      name: Gridline
      slug: gridline
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/AadhaarVerification/Gridline
      status: profiled
      tags:
      - Company
      - Identity Verification
      - KYC
      - Onboarding
      tier: observed
      url: /providers/gridline/
    - agent_band: agent-aware
      agent_readiness: 27.2
      apps:
      - Namma Yatri
      band: thin
      in_catalog: true
      kin_score: 32.9
      mcp:
        status: none
      name: HyperVerge
      slug: hyperverge
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Verification/HyperVerge
      status: profiled
      tags:
      - Face Authentication
      - Identity Verification
      - KYC
      - Liveness
      tier: observed
      url: /providers/hyperverge/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Namma Yatri
      band: emerging
      in_catalog: true
      kin_score: 16.2
      mcp:
        status: unknown
      name: DigiLocker
      slug: digilocker
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Verification/Digilocker
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/digilocker/
    - agent_band: null
      agent_readiness: null
      apps:
      - Namma Yatri
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: IDfy
      slug: idfy
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Verification/Idfy
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30.10
      key: AE-120.30.10
      name: Turn-by-Turn Directions
      url: /capabilities/routing-navigation/
      via_parent: Routing & Navigation
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Namma Yatri
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp: &id001
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps Platform
      slug: google-maps
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Maps/Google
      status: profiled
      tags: &id002
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
    - agent_band: agent-aware
      agent_readiness: 12.4
      apps:
      - Namma Yatri
      band: thin
      in_catalog: true
      kin_score: 35.4
      mcp:
        source: https://github.com/nextbillion-ai/nextbillion-mcp
        status: verified
      name: NextBillion.ai
      slug: nextbillion-ai
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Maps/NextBillion
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Logistics
      - Routing
      tier: observed
      url: /providers/nextbillion-ai/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Namma Yatri
      band: minimal
      in_catalog: true
      kin_score: 7.7
      mcp:
        status: none
      name: MapmyIndia (Mappls)
      slug: mappls
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Maps/MMI
      status: profiled
      tags:
      - Company
      - Location
      - Mapping
      - Navigation
      tier: observed
      url: /providers/mappls/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Namma Yatri
      band: minimal
      in_catalog: true
      kin_score: 4.5
      mcp:
        status: none
      name: OSRM (Project OSRM, self-hosted)
      slug: osrm
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Maps/OSRM
      status: profiled
      tags:
      - Company
      - Navigation
      - Open Source
      - Routing
      tier: observed
      url: /providers/osrm/
  - capability:
      attribution: API Evangelist extension
      id: AE-190.80.10
      key: AE-190.80.10
      name: Embedded Insurance
      url: /capabilities/personal-insurance/
      via_parent: Personal Insurance
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.8
      apps:
      - Namma Yatri
      band: thin
      in_catalog: true
      kin_score: 38.5
      mcp:
        status: unknown
      name: Acko
      slug: acko
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Insurance/Acko
      status: profiled
      tags:
      - Company
      - Consumer
      - Insurance
      - Insurtech
      tier: observed
      url: /providers/acko/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Namma Yatri
      band: emerging
      in_catalog: true
      kin_score: 15.8
      mcp:
        status: unknown
      name: IFFCO-Tokio General Insurance
      slug: iffco-tokio
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Insurance/IffcoTokio
      status: profiled
      tags:
      - General Insurance
      - India
      - Insurance
      - Joint Venture
      tier: observed
      url: /providers/iffco-tokio/
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.8
      apps:
      - Namma Yatri
      band: thin
      in_catalog: true
      kin_score: 32.4
      mcp:
        status: none
      name: Checkr
      slug: checkr
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/BackgroundVerification/Checkr
      status: profiled
      tags:
      - Background Checks
      - Compliance
      - Employment Screening
      - Human Resources
      tier: observed
      url: /providers/checkr/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.3
      apps:
      - Fleetbase (Fleet-Ops)
      band: strong
      in_catalog: true
      kin_score: 62.4
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Places
      slug: google-places
      sources:
      - https://github.com/fleetbase/fleetops/blob/main/composer.json
      status: profiled
      tags:
      - Geolocation
      - Google
      - Location
      - Restaurant
      tier: observed
      url: /providers/google-places/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.50
      key: AE-210.30.50
      name: Micromobility & Bike Share
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    providers:
    - agent_band: agent-aware
      agent_readiness: 16.7
      apps:
      - Uber
      band: thin
      in_catalog: true
      kin_score: 33.3
      mcp:
        status: none
      name: Lime
      slug: lime
      sources:
      - https://www.uber.com/us/en/ride/how-it-works/
      status: profiled
      tags:
      - Electric Bikes
      - Electric Scooters
      - Micromobility
      - Shared Mobility
      tier: declared
      url: /providers/lime/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.40
      key: AE-210.30.40
      name: Public Transit Data
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Namma Yatri
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        status: none
      name: OpenTripPlanner (self-hosted)
      slug: opentripplanner
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/MultiModal/OpenTripPlanner
      status: profiled
      tags:
      - Multi-Modal
      - Open Source
      - Routing
      - Transportation
      tier: observed
      url: /providers/opentripplanner/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Namma Yatri
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp: *id001
      name: Google Maps Platform (Fleet Engine)
      slug: google-maps
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/FleetEngine
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-maps/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.10
      key: AE-200.20.10
      name: Vehicle Data Access
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Namma Yatri
      band: strong
      in_catalog: true
      kin_score: 56.5
      mcp:
        status: none
      name: Signzy
      slug: signzy
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/ChallanSearch/Signzy
      status: profiled
      tags:
      - AML
      - Identity Verification
      - KYB
      - KYC
      tier: observed
      url: /providers/signzy/
  layer: domain
- capabilities:
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
      - Bolt
      - Grab
      - Lime
      - Lyft
      - Uber
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.limebike/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.ubercab/latest/
      status: profiled
      tags: &id004
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Bolt
      - Grab
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id009
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/ee.mtakso.client/latest/
      status: profiled
      tags: &id010
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Open Source Bike Share
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://github.com/cyklokoalicia/OpenSourceBikeShare/blob/master/.env.dist
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - Lime
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.limebike/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - Bolt
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/ee.mtakso.client/latest/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
    - agent_band: null
      agent_readiness: null
      apps:
      - Grab
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Anagog
      slug: anagog
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Bolt
      - Fleetbase (Fleet-Ops)
      - Grab
      - Lyft
      - Open Source Bike Share
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/cyklokoalicia/OpenSourceBikeShare/blob/master/composer.json
      - https://github.com/fleetbase/core-api/blob/main/composer.json
      - https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Bolt
      - Grab
      - Lime
      - Uber
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id003
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.limebike/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.ubercab/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - Lime
      band: developing
      in_catalog: true
      kin_score: 45.8
      mcp:
        source: https://docs.luciq.ai/product-guides-and-integrations/product-guides/ai-features.md
        status: documented
      name: Instabug
      slug: instabug
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.limebike/latest/
      status: profiled
      tags:
      - AI Agents
      - APM
      - Application Performance Monitoring
      - Bug Reporting
      tier: observed
      url: /providers/instabug/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - Fleetbase (Fleet-Ops)
      - Namma Yatri
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp: &id005
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/fleetbase/core-api/blob/main/composer.json
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/SMS/TwillioSms
      status: profiled
      tags: &id006
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-ready
      agent_readiness: 61.3
      apps:
      - Namma Yatri
      band: exemplar
      in_catalog: true
      kin_score: 86.9
      mcp:
        source: https://www.infobip.com/docs/mcp
        status: verified
      name: Infobip
      slug: infobip
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Infobip
      status: profiled
      tags:
      - CPaaS
      - Croatia
      - Messaging
      - Telecommunications
      tier: observed
      url: /providers/infobip/
    - agent_band: agent-ready
      agent_readiness: 40.0
      apps:
      - Namma Yatri
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/Vonage/vonage-mcp-server-documentation
        status: verified
      name: Vonage
      slug: vonage
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/SMS/VonageSms
      status: profiled
      tags:
      - Communications
      - Messaging
      - Telecommunications
      - Video Conferencing
      tier: observed
      url: /providers/vonage/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Namma Yatri
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Kaleyra
      slug: kaleyra
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/SMS/KaleyraSms
      status: profiled
      tags:
      - CPaaS
      - Messaging
      - SMS
      - WhatsApp
      tier: observed
      url: /providers/kaleyra/
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - Namma Yatri
      band: thin
      in_catalog: true
      kin_score: 27.7
      mcp: &id007
        source: https://github.com/exotel/ExotelMCP
        status: verified
      name: Exotel
      slug: exotel
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/SMS/ExotelSms
      status: profiled
      tags: &id008
      - Cloud Telephony
      - India
      - SMS
      - Voice
      tier: observed
      url: /providers/exotel/
    - agent_band: agent-ready
      agent_readiness: 52.6
      apps:
      - Open Source Bike Share
      band: thin
      in_catalog: true
      kin_score: 27.5
      mcp:
        source: https://www.textmagic.com/mcp/
        status: documented
      name: Textmagic
      slug: textmagic
      sources:
      - https://github.com/cyklokoalicia/OpenSourceBikeShare/tree/master/src/SmsConnector
      status: profiled
      tags:
      - Communications
      - Messaging
      - SMS
      - Text Messaging
      tier: observed
      url: /providers/textmagic/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Open Source Bike Share
      band: minimal
      in_catalog: true
      kin_score: 0.5
      mcp:
        status: unknown
      name: EuroSms
      slug: eurosms
      sources:
      - https://github.com/cyklokoalicia/OpenSourceBikeShare/tree/master/src/SmsConnector
      status: profiled
      tags:
      - Bulk Messaging
      - Company
      - SMS
      - Slovakia
      tier: observed
      url: /providers/eurosms/
    - agent_band: null
      agent_readiness: null
      apps:
      - Namma Yatri
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Karix
      slug: karix
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/SMS/KarixSms
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Namma Yatri
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: ValueFirst
      slug: valuefirst
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/SMS/MyValueFirst
      status: queued for profiling
      tags: []
      tier: observed
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
      agent_readiness: 57.6
      apps:
      - Fleetbase (Fleet-Ops)
      - Namma Yatri
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/fleetbase/fleetops/blob/main/package.json
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Payment/Stripe
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 41.2
      apps:
      - Namma Yatri
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        status: unknown
      name: BillDesk
      slug: billdesk
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Settlement/BillDesk
      status: profiled
      tags:
      - India
      - Payment Gateway
      - Payments
      - UPI
      tier: observed
      url: /providers/billdesk/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Namma Yatri
      band: emerging
      in_catalog: true
      kin_score: 25.2
      mcp:
        source: https://github.com/juspay/juspay-mcp
        status: verified
      name: Juspay
      slug: juspay
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Payment/Juspay
      status: profiled
      tags:
      - Checkout
      - India
      - Payment Orchestration
      - Payments
      tier: observed
      url: /providers/juspay/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Namma Yatri
      band: emerging
      in_catalog: true
      kin_score: 24.4
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=paytm
        status: verified
      name: Paytm
      slug: paytm
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Payment/PaytmEDC
      status: profiled
      tags:
      - Payment Gateway
      - Payments
      - Payouts
      - UPI
      tier: observed
      url: /providers/paytm/
    - agent_band: null
      agent_readiness: null
      apps:
      - Namma Yatri
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: YES Bank
      slug: yes-bank
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Settlement/YesBiz
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.9
      apps:
      - Bolt
      - Lyft
      band: strong
      in_catalog: true
      kin_score: 65.9
      mcp:
        status: none
      name: Singular
      slug: singular
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/ee.mtakso.client/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/me.lyft.android/latest/
      status: profiled
      tags:
      - Attribution
      - Company
      - Marketing Analytics
      - Mobile Attribution
      tier: observed
      url: /providers/singular/
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - Grab
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Lime
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.limebike/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Fleetbase (Fleet-Ops)
      - Namma Yatri
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id003
      name: Firebase
      slug: google-firebase
      sources:
      - https://github.com/fleetbase/core-api/blob/main/composer.json
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Notification/FCM
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 31.2
      apps:
      - Grab
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Leanplum
      slug: leanplum
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
      status: profiled
      tags:
      - Customer Engagement
      - Messaging
      - Mobile Marketing
      - Push Notifications
      tier: observed
      url: /providers/leanplum/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Fleetbase (Fleet-Ops)
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Apple (APNs)
      slug: apple
      sources:
      - https://github.com/fleetbase/core-api/blob/main/composer.json
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    providers:
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - Namma Yatri
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp: *id005
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Call/Twillio
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-aware
      agent_readiness: 26.9
      apps:
      - Namma Yatri
      band: thin
      in_catalog: true
      kin_score: 35.0
      mcp:
        status: unknown
      name: Ozonetel
      slug: ozonetel
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Call/Ozonetel
      status: profiled
      tags:
      - CX Platform
      - Cloud Communications
      - Company
      - Contact Center
      tier: observed
      url: /providers/ozonetel/
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - Namma Yatri
      band: thin
      in_catalog: true
      kin_score: 27.7
      mcp: *id007
      name: Exotel
      slug: exotel
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Call/Exotel
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/exotel/
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Lyft
      - Uber
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        source: https://github.com/IABTechLab/agentic-real-time-framework
        status: verified
      name: IAB Tech Lab
      slug: iab-tech-lab
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ubercab/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/me.lyft.android/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Standards
      tier: observed
      url: /providers/iab-tech-lab/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Grab
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Namma Yatri
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: WhatsApp Business Platform (Meta)
      slug: whatsapp
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Meta
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: observed
      url: /providers/whatsapp/
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - Namma Yatri
      band: strong
      in_catalog: true
      kin_score: 57.4
      mcp:
        status: unknown
      name: Tata Communications
      slug: tata-communications
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Whatsapp/TataCommunications
      status: profiled
      tags:
      - CPaaS
      - India
      - Telecommunications
      - Wholesale Carrier
      tier: observed
      url: /providers/tata-communications/
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Namma Yatri
      band: emerging
      in_catalog: true
      kin_score: 24.9
      mcp:
        status: none
      name: Gupshup
      slug: gupshup
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Whatsapp/GupShup
      status: profiled
      tags:
      - CPaaS
      - Conversational AI
      - Messaging
      - WhatsApp
      tier: observed
      url: /providers/gupshup/
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 65.1
      apps:
      - Namma Yatri
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: MoEngage
      slug: moengage
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/EventTracking/Moengage
      status: profiled
      tags:
      - Customer Data Platform
      - Customer Engagement
      - Marketing Automation
      - Push Notifications
      tier: observed
      url: /providers/moengage/
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Namma Yatri
      band: strong
      in_catalog: true
      kin_score: 61.4
      mcp:
        source: https://docs.clevertap.com/docs/clevertap-mcp
        status: documented
      name: CleverTap
      slug: clevertap
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/EventTracking/Clevertap
      status: profiled
      tags:
      - Audiences
      - Customer Engagement
      - Customer Retention
      - Marketing Automation
      tier: observed
      url: /providers/clevertap/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Namma Yatri
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Ticket/Zendesk
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: observed
      url: /providers/zendesk/
    - agent_band: agent-aware
      agent_readiness: 27.2
      apps:
      - Namma Yatri
      band: developing
      in_catalog: true
      kin_score: 39.4
      mcp:
        status: none
      name: Kapture CX
      slug: kapture-cx
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Ticket/Kapture
      status: profiled
      tags:
      - Artificial Intelligence
      - Automation
      - CRM
      - Customer Experience
      tier: observed
      url: /providers/kapture-cx/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Bolt
      - Grab
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id009
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.grabtaxi.passenger/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/ee.mtakso.client/latest/
      status: profiled
      tags: *id010
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Fleetbase (Fleet-Ops)
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS
      slug: amazon-web-services
      sources:
      - https://github.com/fleetbase/core-api/blob/main/composer.json
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: observed
      url: /providers/amazon-web-services/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 58.7
      apps:
      - Namma Yatri
      band: strong
      in_catalog: true
      kin_score: 58.3
      mcp:
        source: https://github.com/SAP/mdk-mcp-server
        status: verified
      name: SAP
      slug: sap
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/SAP
      status: profiled
      tags:
      - Artificial Intelligence
      - BTP
      - Business Applications
      - SAP
      tier: observed
      url: /providers/sap/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.9
      apps:
      - Namma Yatri
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: Google Cloud Translation
      slug: google-translate
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/GoogleTranslate
      status: profiled
      tags:
      - Google Cloud
      - Internationalization
      - Language Detection
      - Localization
      tier: observed
      url: /providers/google-translate/
  - capability:
      attribution: API Evangelist extension
      id: AE-937
      key: AE-937
      name: Payouts & Disbursements
      url: /capabilities/payment-processing-management/
      via_parent: Payment Processing Management
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Namma Yatri
      band: emerging
      in_catalog: true
      kin_score: 22.3
      mcp:
        status: unknown
      name: HDFC Bank
      slug: hdfc-bank
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Payout/HdfcCbx
      status: profiled
      tags:
      - Banking
      - Finance
      - India
      - Payments
      tier: observed
      url: /providers/hdfc-bank/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Fleetbase (Fleet-Ops)
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://github.com/fleetbase/core-api/blob/main/composer.json
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Namma Yatri
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Slack
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.0
      apps:
      - Fleetbase (Fleet-Ops)
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Graph
      slug: microsoft-graph
      sources:
      - https://github.com/fleetbase/core-api/blob/main/composer.json
      status: profiled
      tags:
      - Azure AD
      - Collaboration
      - Contacts
      - Microsoft Graph
      tier: observed
      url: /providers/microsoft-graph/
  layer: common
summary:
  coverage_pct: 91.5
  declared_only: 1
  distinct_providers: 59
  in_catalog: 54
  mcp:
    documented: 3
    none: 20
    unchecked: 5
    verified: 22
  mcp_verified: 22
  mean_kin_score: 49.9
  observed: 58
  queued: 5
  reference_apps: 8
title: 'Ride-Hailing & Micromobility: application blueprint'
---
