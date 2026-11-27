---
app: Namma Yatri
app_slug: namma-yatri
app_url: https://github.com/nammayatri/nammayatri
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-300.10.20
  key: BC-300.10.20
  layer: domain
  name: Candidate Screening and Selection
  providers:
  - Checkr
  url: /capabilities/talent-acquisition-management/
  via_parent: Talent Acquisition Management
- attribution: API Evangelist extension
  id: AE-160.30.10
  key: AE-160.30.10
  layer: domain
  name: Document Verification
  providers:
  - DigiLocker
  - Gridline
  - HyperVerge
  - IDfy
  url: /capabilities/identity-verification/
  via_parent: Identity Verification
- attribution: API Evangelist extension
  id: AE-190.80.10
  key: AE-190.80.10
  layer: domain
  name: Embedded Insurance
  providers:
  - Acko
  - IFFCO-Tokio General Insurance
  url: /capabilities/personal-insurance/
  via_parent: Personal Insurance
- attribution: API Evangelist extension
  id: AE-210.30.40
  key: AE-210.30.40
  layer: domain
  name: Public Transit Data
  providers:
  - OpenTripPlanner (self-hosted)
  url: /capabilities/ground-transport/
  via_parent: Ground Transport
- attribution: API Evangelist extension
  id: AE-210.30.10
  key: AE-210.30.10
  layer: domain
  name: Ride Hailing
  providers:
  - Google Maps Platform (Fleet Engine)
  url: /capabilities/ground-transport/
  via_parent: Ground Transport
- attribution: API Evangelist extension
  id: AE-120.30.10
  key: AE-120.30.10
  layer: domain
  name: Turn-by-Turn Directions
  providers:
  - Google Maps Platform
  - MapmyIndia (Mappls)
  - NextBillion.ai
  - OSRM (Project OSRM, self-hosted)
  url: /capabilities/routing-navigation/
  via_parent: Routing & Navigation
- attribution: API Evangelist extension
  id: AE-200.20.10
  key: AE-200.20.10
  layer: domain
  name: Vehicle Data Access
  providers:
  - Signzy
  url: /capabilities/connected-vehicles/
  via_parent: Connected Vehicles
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: common
  name: Customer Lifecycle Engagement
  providers:
  - CleverTap
  - MoEngage
  url: /capabilities/customer-lifecycle-engagement/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Kapture CX
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - SAP
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: common
  name: Machine Translation
  providers:
  - Google Cloud Translation
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - BillDesk
  - Juspay
  - Paytm
  - Stripe
  - YES Bank
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-937
  key: AE-937
  layer: common
  name: Payouts & Disbursements
  providers:
  - HDFC Bank
  url: /capabilities/payment-processing-management/
  via_parent: Payment Processing Management
- attribution: API Evangelist extension
  id: AE-150.50.10
  key: AE-150.50.10
  layer: common
  name: Programmable Voice
  providers:
  - Exotel
  - Ozonetel
  - Twilio
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Firebase
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Exotel
  - Infobip
  - Kaleyra
  - Karix
  - Twilio
  - ValueFirst
  - Vonage
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - Gupshup
  - Tata Communications
  - WhatsApp Business Platform (Meta)
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: ride-hailing-mobility
  name: Ride-Hailing & Micromobility
  url: /applications/ride-hailing-mobility/
counts:
  declared: 0
  observed: 41
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.8
    band: thin
    in_catalog: true
    kin_score: 38.5
    mcp: &id004
      status: unknown
    slug: acko
    status: profiled
    tags: &id005
    - Company
    - Consumer
    - Insurance
    - Insurtech
    url: /providers/acko/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.2
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id006
      status: unknown
    slug: billdesk
    status: profiled
    tags: &id007
    - India
    - Payment Gateway
    - Payments
    - UPI
    url: /providers/billdesk/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 52.8
    band: thin
    in_catalog: true
    kin_score: 32.4
    mcp: &id008
      status: none
    slug: checkr
    status: profiled
    tags: &id009
    - Background Checks
    - Compliance
    - Employment Screening
    - Human Resources
    url: /providers/checkr/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 47.6
    band: strong
    in_catalog: true
    kin_score: 61.4
    mcp: &id010
      source: https://docs.clevertap.com/docs/clevertap-mcp
      status: documented
    slug: clevertap
    status: profiled
    tags: &id011
    - Audiences
    - Customer Engagement
    - Customer Retention
    - Marketing Automation
    url: /providers/clevertap/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 16.2
    mcp: &id012
      status: unknown
    slug: digilocker
    status: profiled
    tags: &id013
    - Company
    url: /providers/digilocker/
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
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 25.8
    band: thin
    in_catalog: true
    kin_score: 27.7
    mcp: &id014
      source: https://github.com/exotel/ExotelMCP
      status: verified
    slug: exotel
    status: profiled
    tags: &id015
    - Cloud Telephony
    - India
    - SMS
    - Voice
    url: /providers/exotel/
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
  facts: *id001
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
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id016
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id017
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.9
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id018
      status: none
    slug: google-translate
    status: profiled
    tags: &id019
    - Google Cloud
    - Internationalization
    - Language Detection
    - Localization
    url: /providers/google-translate/
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
  facts: &id002
    agent_band: agent-ready
    agent_readiness: 33.0
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id020
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id021
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
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
  facts: *id002
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.0
    band: developing
    in_catalog: true
    kin_score: 51.0
    mcp: &id022
      status: unknown
    slug: gridline
    status: profiled
    tags: &id023
    - Company
    - Identity Verification
    - KYC
    - Onboarding
    url: /providers/gridline/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.7
    band: emerging
    in_catalog: true
    kin_score: 24.9
    mcp: &id024
      status: none
    slug: gupshup
    status: profiled
    tags: &id025
    - CPaaS
    - Conversational AI
    - Messaging
    - WhatsApp
    url: /providers/gupshup/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 22.3
    mcp: &id026
      status: unknown
    slug: hdfc-bank
    status: profiled
    tags: &id027
    - Banking
    - Finance
    - India
    - Payments
    url: /providers/hdfc-bank/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.2
    band: thin
    in_catalog: true
    kin_score: 32.9
    mcp: &id028
      status: none
    slug: hyperverge
    status: profiled
    tags: &id029
    - Face Authentication
    - Identity Verification
    - KYC
    - Liveness
    url: /providers/hyperverge/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id030
      status: unchecked
    slug: idfy
    status: queued for profiling
    tags: &id031 []
    url: null
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.8
    mcp: &id032
      status: unknown
    slug: iffco-tokio
    status: profiled
    tags: &id033
    - General Insurance
    - India
    - Insurance
    - Joint Venture
    url: /providers/iffco-tokio/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 61.3
    band: exemplar
    in_catalog: true
    kin_score: 86.9
    mcp: &id034
      source: https://www.infobip.com/docs/mcp
      status: verified
    slug: infobip
    status: profiled
    tags: &id035
    - CPaaS
    - Croatia
    - Messaging
    - Telecommunications
    url: /providers/infobip/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: emerging
    in_catalog: true
    kin_score: 25.2
    mcp: &id036
      source: https://github.com/juspay/juspay-mcp
      status: verified
    slug: juspay
    status: profiled
    tags: &id037
    - Checkout
    - India
    - Payment Orchestration
    - Payments
    url: /providers/juspay/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id038
      status: none
    slug: kaleyra
    status: profiled
    tags: &id039
    - CPaaS
    - Messaging
    - SMS
    - WhatsApp
    url: /providers/kaleyra/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.2
    band: developing
    in_catalog: true
    kin_score: 39.4
    mcp: &id040
      status: none
    slug: kapture-cx
    status: profiled
    tags: &id041
    - Artificial Intelligence
    - Automation
    - CRM
    - Customer Experience
    url: /providers/kapture-cx/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id042
      status: unchecked
    slug: karix
    status: queued for profiling
    tags: &id043 []
    url: null
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.7
    mcp: &id044
      status: none
    slug: mappls
    status: profiled
    tags: &id045
    - Company
    - Location
    - Mapping
    - Navigation
    url: /providers/mappls/
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
  facts:
    agent_band: agent-native
    agent_readiness: 65.1
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id046
      status: none
    slug: moengage
    status: profiled
    tags: &id047
    - Customer Data Platform
    - Customer Engagement
    - Marketing Automation
    - Push Notifications
    url: /providers/moengage/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 12.4
    band: thin
    in_catalog: true
    kin_score: 35.4
    mcp: &id048
      source: https://github.com/nextbillion-ai/nextbillion-mcp
      status: verified
    slug: nextbillion-ai
    status: profiled
    tags: &id049
    - Artificial Intelligence
    - Company
    - Logistics
    - Routing
    url: /providers/nextbillion-ai/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.2
    mcp: &id050
      status: none
    slug: opentripplanner
    status: profiled
    tags: &id051
    - Multi-Modal
    - Open Source
    - Routing
    - Transportation
    url: /providers/opentripplanner/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.5
    mcp: &id052
      status: none
    slug: osrm
    status: profiled
    tags: &id053
    - Company
    - Navigation
    - Open Source
    - Routing
    url: /providers/osrm/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.9
    band: thin
    in_catalog: true
    kin_score: 35.0
    mcp: &id054
      status: unknown
    slug: ozonetel
    status: profiled
    tags: &id055
    - CX Platform
    - Cloud Communications
    - Company
    - Contact Center
    url: /providers/ozonetel/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: emerging
    in_catalog: true
    kin_score: 24.4
    mcp: &id056
      source: https://registry.modelcontextprotocol.io/v0/servers?search=paytm
      status: verified
    slug: paytm
    status: profiled
    tags: &id057
    - Payment Gateway
    - Payments
    - Payouts
    - UPI
    url: /providers/paytm/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.7
    band: strong
    in_catalog: true
    kin_score: 58.3
    mcp: &id058
      source: https://github.com/SAP/mdk-mcp-server
      status: verified
    slug: sap
    status: profiled
    tags: &id059
    - Artificial Intelligence
    - BTP
    - Business Applications
    - SAP
    url: /providers/sap/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 21.3
    band: strong
    in_catalog: true
    kin_score: 56.5
    mcp: &id060
      status: none
    slug: signzy
    status: profiled
    tags: &id061
    - AML
    - Identity Verification
    - KYB
    - KYC
    url: /providers/signzy/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id062
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id063
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
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
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id064
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id065
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 32.7
    band: strong
    in_catalog: true
    kin_score: 57.4
    mcp: &id066
      status: unknown
    slug: tata-communications
    status: profiled
    tags: &id067
    - CPaaS
    - India
    - Telecommunications
    - Wholesale Carrier
    url: /providers/tata-communications/
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
  facts: &id003
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id068
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id069
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
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
  facts: *id003
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id070
      status: unchecked
    slug: valuefirst
    status: queued for profiling
    tags: &id071 []
    url: null
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.0
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id072
      source: https://github.com/Vonage/vonage-mcp-server-documentation
      status: verified
    slug: vonage
    status: profiled
    tags: &id073
    - Communications
    - Messaging
    - Telecommunications
    - Video Conferencing
    url: /providers/vonage/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 72.3
    mcp: &id074
      status: none
    slug: whatsapp
    status: profiled
    tags: &id075
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id076
      status: unchecked
    slug: yes-bank
    status: queued for profiling
    tags: &id077 []
    url: null
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id078
      status: none
    slug: zendesk
    status: profiled
    tags: &id079
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: common
  name: Zendesk
  provider: zendesk
  says: ships the Zendesk SDK or integration code
  source: https://github.com/nammayatri/shared-kernel/tree/main/lib/mobility-core/src/Kernel/External/Ticket/Zendesk
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ride-hailing-mobility/namma-yatri/
providers:
- agent_band: agent-ready
  agent_readiness: 29.8
  band: thin
  in_catalog: true
  kin_score: 38.5
  mcp: *id004
  name: Acko
  slug: acko
  status: profiled
  tags: *id005
  url: /providers/acko/
- agent_band: agent-ready
  agent_readiness: 41.2
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id006
  name: BillDesk
  slug: billdesk
  status: profiled
  tags: *id007
  url: /providers/billdesk/
- agent_band: agent-ready
  agent_readiness: 52.8
  band: thin
  in_catalog: true
  kin_score: 32.4
  mcp: *id008
  name: Checkr
  slug: checkr
  status: profiled
  tags: *id009
  url: /providers/checkr/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: strong
  in_catalog: true
  kin_score: 61.4
  mcp: *id010
  name: CleverTap
  slug: clevertap
  status: profiled
  tags: *id011
  url: /providers/clevertap/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.2
  mcp: *id012
  name: DigiLocker
  slug: digilocker
  status: profiled
  tags: *id013
  url: /providers/digilocker/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 27.7
  mcp: *id014
  name: Exotel
  slug: exotel
  status: profiled
  tags: *id015
  url: /providers/exotel/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id016
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id017
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 33.9
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id018
  name: Google Cloud Translation
  slug: google-translate
  status: profiled
  tags: *id019
  url: /providers/google-translate/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id020
  name: Google Maps Platform
  slug: google-maps
  status: profiled
  tags: *id021
  url: /providers/google-maps/
- agent_band: agent-ready
  agent_readiness: 37.0
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id022
  name: Gridline
  slug: gridline
  status: profiled
  tags: *id023
  url: /providers/gridline/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: emerging
  in_catalog: true
  kin_score: 24.9
  mcp: *id024
  name: Gupshup
  slug: gupshup
  status: profiled
  tags: *id025
  url: /providers/gupshup/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 22.3
  mcp: *id026
  name: HDFC Bank
  slug: hdfc-bank
  status: profiled
  tags: *id027
  url: /providers/hdfc-bank/
- agent_band: agent-aware
  agent_readiness: 27.2
  band: thin
  in_catalog: true
  kin_score: 32.9
  mcp: *id028
  name: HyperVerge
  slug: hyperverge
  status: profiled
  tags: *id029
  url: /providers/hyperverge/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id030
  name: IDfy
  slug: idfy
  status: queued for profiling
  tags: *id031
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.8
  mcp: *id032
  name: IFFCO-Tokio General Insurance
  slug: iffco-tokio
  status: profiled
  tags: *id033
  url: /providers/iffco-tokio/
- agent_band: agent-ready
  agent_readiness: 61.3
  band: exemplar
  in_catalog: true
  kin_score: 86.9
  mcp: *id034
  name: Infobip
  slug: infobip
  status: profiled
  tags: *id035
  url: /providers/infobip/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: emerging
  in_catalog: true
  kin_score: 25.2
  mcp: *id036
  name: Juspay
  slug: juspay
  status: profiled
  tags: *id037
  url: /providers/juspay/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id038
  name: Kaleyra
  slug: kaleyra
  status: profiled
  tags: *id039
  url: /providers/kaleyra/
- agent_band: agent-aware
  agent_readiness: 27.2
  band: developing
  in_catalog: true
  kin_score: 39.4
  mcp: *id040
  name: Kapture CX
  slug: kapture-cx
  status: profiled
  tags: *id041
  url: /providers/kapture-cx/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id042
  name: Karix
  slug: karix
  status: queued for profiling
  tags: *id043
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.7
  mcp: *id044
  name: MapmyIndia (Mappls)
  slug: mappls
  status: profiled
  tags: *id045
  url: /providers/mappls/
- agent_band: agent-native
  agent_readiness: 65.1
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id046
  name: MoEngage
  slug: moengage
  status: profiled
  tags: *id047
  url: /providers/moengage/
- agent_band: agent-aware
  agent_readiness: 12.4
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id048
  name: NextBillion.ai
  slug: nextbillion-ai
  status: profiled
  tags: *id049
  url: /providers/nextbillion-ai/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.2
  mcp: *id050
  name: OpenTripPlanner (self-hosted)
  slug: opentripplanner
  status: profiled
  tags: *id051
  url: /providers/opentripplanner/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.5
  mcp: *id052
  name: OSRM (Project OSRM, self-hosted)
  slug: osrm
  status: profiled
  tags: *id053
  url: /providers/osrm/
- agent_band: agent-aware
  agent_readiness: 26.9
  band: thin
  in_catalog: true
  kin_score: 35.0
  mcp: *id054
  name: Ozonetel
  slug: ozonetel
  status: profiled
  tags: *id055
  url: /providers/ozonetel/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: emerging
  in_catalog: true
  kin_score: 24.4
  mcp: *id056
  name: Paytm
  slug: paytm
  status: profiled
  tags: *id057
  url: /providers/paytm/
- agent_band: agent-ready
  agent_readiness: 58.7
  band: strong
  in_catalog: true
  kin_score: 58.3
  mcp: *id058
  name: SAP
  slug: sap
  status: profiled
  tags: *id059
  url: /providers/sap/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: strong
  in_catalog: true
  kin_score: 56.5
  mcp: *id060
  name: Signzy
  slug: signzy
  status: profiled
  tags: *id061
  url: /providers/signzy/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id062
  name: Slack
  slug: slack
  status: profiled
  tags: *id063
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id064
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id065
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: strong
  in_catalog: true
  kin_score: 57.4
  mcp: *id066
  name: Tata Communications
  slug: tata-communications
  status: profiled
  tags: *id067
  url: /providers/tata-communications/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id068
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id069
  url: /providers/twilio/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id070
  name: ValueFirst
  slug: valuefirst
  status: queued for profiling
  tags: *id071
  url: null
- agent_band: agent-ready
  agent_readiness: 40.0
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id072
  name: Vonage
  slug: vonage
  status: profiled
  tags: *id073
  url: /providers/vonage/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id074
  name: WhatsApp Business Platform (Meta)
  slug: whatsapp
  status: profiled
  tags: *id075
  url: /providers/whatsapp/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id076
  name: YES Bank
  slug: yes-bank
  status: queued for profiling
  tags: *id077
  url: null
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id078
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id079
  url: /providers/zendesk/
siblings:
- name: Bolt
  rows: 7
  url: /applications/ride-hailing-mobility/bolt/
- name: Fleetbase (Fleet-Ops)
  rows: 9
  url: /applications/ride-hailing-mobility/fleetbase-fleet-ops/
- name: Grab
  rows: 9
  url: /applications/ride-hailing-mobility/grab/
- name: Lime
  rows: 5
  url: /applications/ride-hailing-mobility/lime/
- name: Lyft
  rows: 4
  url: /applications/ride-hailing-mobility/lyft/
- name: Open Source Bike Share
  rows: 4
  url: /applications/ride-hailing-mobility/open-source-bike-share/
- name: Uber
  rows: 4
  url: /applications/ride-hailing-mobility/uber/
sitemap: true
title: 'Namma Yatri: Ride-Hailing & Micromobility reference app'
---
