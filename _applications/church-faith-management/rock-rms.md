---
app: Rock RMS
app_slug: rock-rms
app_url: https://github.com/SparkDevNetwork/Rock
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
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - NMI
  - PayPal Payflow Pro
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10.30
  key: AE-120.10.30
  layer: common
  name: Address Validation & Autocomplete
  providers:
  - SmartyStreets
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Azure Blob Storage
  - Google Cloud Storage
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: common
  name: IP Geolocation
  providers:
  - IPregistry
  - MaxMind
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: common
  name: Integration and API Management
  providers:
  - Azure Service Bus
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Firebase Cloud Messaging
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.70
  key: realtime-messaging
  layer: common
  name: Realtime Messaging
  providers:
  - Azure SignalR Service
  url: /capabilities/realtime-messaging/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  - Google sign-in
  - Twitter / X
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Auth0
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Mailgun
  - Mandrill (Mailchimp Transactional)
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.40.20
  key: AE-110.40.20
  layer: agent
  name: OCR & Document AI
  providers:
  - Azure AI Document Intelligence
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
category:
  id: church-faith-management
  name: Church & Faith Community Management
  url: /applications/church-faith-management/
counts:
  declared: 0
  observed: 21
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/SparkDevNetwork/Rock/blob/develop/Rock/Rock.csproj
- route: source code
  url: https://github.com/SparkDevNetwork/Rock
- route: source code
  url: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Address
- route: source code
  url: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Communication/Transport
- route: source code
  url: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/IpAddress
- route: source code
  url: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Security/Authentication
- route: source code
  url: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Storage/Provider
integrations:
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
    agent_readiness: 39.5
    band: exemplar
    in_catalog: true
    kin_score: 71.8
    mcp: &id001
      source: https://auth0.com/docs/get-started/auth0-mcp-server
      status: verified
    slug: auth0
    status: profiled
    tags: &id002
    - AI Agents
    - Auth0
    - Authentication
    - Authorization
    url: /providers/auth0/
  layer: common
  name: Auth0
  provider: auth0
  says: ships the Auth0 SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.Security.Authentication.Auth0
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.20
    key: AE-110.40.20
    name: OCR & Document AI
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.8
    band: strong
    in_catalog: true
    kin_score: 54.5
    mcp: &id003
      status: unknown
    slug: azure-document-intelligence
    status: profiled
    tags: &id004
    - Artificial Intelligence
    - Document AI
    - Intelligent Document Processing
    - Microsoft Azure
    url: /providers/azure-document-intelligence/
  layer: agent
  name: Azure AI Document Intelligence
  provider: azure-document-intelligence
  says: ships the Azure AI Document Intelligence SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/blob/develop/Rock/Rock.csproj
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: strong
    in_catalog: true
    kin_score: 66.3
    mcp: &id005
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id006
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Storage/Provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 77.2
    mcp: &id007
      source: https://raw.githubusercontent.com/microsoft/mcp/main/servers/Azure.Mcp.Server/README.md
      status: verified
    slug: azure-service-bus
    status: profiled
    tags: &id008
    - Cloud
    - Enterprise
    - Message Broker
    - Microsoft Azure
    url: /providers/azure-service-bus/
  layer: common
  name: Azure Service Bus
  provider: azure-service-bus
  says: ships the Azure Service Bus SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/blob/develop/Rock/Rock.csproj
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: realtime-messaging
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.2
    band: exemplar
    in_catalog: true
    kin_score: 69.3
    mcp: &id009
      source: https://learn.microsoft.com/en-us/azure/developer/azure-mcp-server/tools/azure-signalr
      status: verified
    slug: microsoft-azure-signalr
    status: profiled
    tags: &id010
    - Messaging
    - Real-Time
    - SignalR
    - WebSocket
    url: /providers/microsoft-azure-signalr/
  layer: common
  name: Azure SignalR Service
  provider: microsoft-azure-signalr
  says: ships the Azure SignalR Service SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/blob/develop/Rock/Rock.csproj
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
    mcp: &id011
      status: none
    slug: checkr
    status: profiled
    tags: &id012
    - Background Checks
    - Compliance
    - Employment Screening
    - Human Resources
    url: /providers/checkr/
  layer: domain
  name: Checkr
  provider: checkr
  says: ships the Checkr SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.Checkr
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id013
      status: none
    slug: facebook
    status: profiled
    tags: &id014
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Security/Authentication
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
    mcp: &id015
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id016
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase Cloud Messaging
  provider: firebase
  says: ships the Firebase Cloud Messaging SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Communication/Transport
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id017
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id018
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Storage/Provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id019
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id020
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Security/Authentication
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.4
    band: thin
    in_catalog: true
    kin_score: 27.1
    mcp: &id021
      source: https://mcp.ipregistry.co/mcp
      status: verified
    slug: ipregistry
    status: profiled
    tags: &id022
    - ASN
    - IP Address
    - IP Geolocation
    - Threat Intelligence
    url: /providers/ipregistry/
  layer: common
  name: IPregistry
  provider: ipregistry
  says: ships the IPregistry SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/IpAddress
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id023
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id024
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: common
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.Mailgun
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id025
      status: none
    slug: mailchimp
    status: profiled
    tags: &id026
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mandrill (Mailchimp Transactional)
  provider: mailchimp
  says: ships the Mandrill (Mailchimp Transactional) SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.Mandrill
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 31.5
    mcp: &id027
      status: none
    slug: maxmind
    status: profiled
    tags: &id028
    - Fraud Prevention
    - Geolocation
    - IP Intelligence
    - Risk Scoring
    url: /providers/maxmind/
  layer: common
  name: MaxMind
  provider: maxmind
  says: ships the MaxMind SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/blob/develop/Rock/Rock.csproj
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
    agent_readiness: 43.6
    band: developing
    in_catalog: true
    kin_score: 50.1
    mcp: &id029
      status: none
    slug: nmi
    status: profiled
    tags: &id030
    - Payment Gateway
    - Payment Processing
    - Payments
    - Tokenization
    url: /providers/nmi/
  layer: domain
  name: NMI
  provider: nmi
  says: ships the NMI SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.NMI
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id031
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id032
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.AI.OpenAI
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
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id033
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id034
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: domain
  name: PayPal Payflow Pro
  provider: paypal
  says: ships the PayPal Payflow Pro SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.PayFlowPro
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.7
    band: exemplar
    in_catalog: true
    kin_score: 84.0
    mcp: &id035
      status: none
    slug: sendgrid
    status: profiled
    tags: &id036
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock.SendGrid
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.30
    key: AE-120.10.30
    name: Address Validation & Autocomplete
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.3
    band: thin
    in_catalog: true
    kin_score: 37.1
    mcp: &id037
      source: https://www.smarty.com/docs/mcp
      status: verified
    slug: smarty
    status: profiled
    tags: &id038
    - Address Autocomplete
    - Address Verification
    - Geocoding
    - ZIP Code
    url: /providers/smarty/
  layer: common
  name: SmartyStreets
  provider: smarty
  says: ships the SmartyStreets SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Address
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
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id039
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id040
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Communication/Transport
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id041
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id042
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: common
  name: Twitter / X
  provider: x
  says: ships the Twitter / X SDK or integration code
  source: https://github.com/SparkDevNetwork/Rock/tree/develop/Rock/Security/Authentication
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/church-faith-management/rock-rms/
providers:
- agent_band: agent-ready
  agent_readiness: 39.5
  band: exemplar
  in_catalog: true
  kin_score: 71.8
  mcp: *id001
  name: Auth0
  slug: auth0
  status: profiled
  tags: *id002
  url: /providers/auth0/
- agent_band: agent-aware
  agent_readiness: 20.8
  band: strong
  in_catalog: true
  kin_score: 54.5
  mcp: *id003
  name: Azure AI Document Intelligence
  slug: azure-document-intelligence
  status: profiled
  tags: *id004
  url: /providers/azure-document-intelligence/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id005
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id006
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 77.2
  mcp: *id007
  name: Azure Service Bus
  slug: azure-service-bus
  status: profiled
  tags: *id008
  url: /providers/azure-service-bus/
- agent_band: agent-aware
  agent_readiness: 26.2
  band: exemplar
  in_catalog: true
  kin_score: 69.3
  mcp: *id009
  name: Azure SignalR Service
  slug: microsoft-azure-signalr
  status: profiled
  tags: *id010
  url: /providers/microsoft-azure-signalr/
- agent_band: agent-ready
  agent_readiness: 52.8
  band: thin
  in_catalog: true
  kin_score: 32.4
  mcp: *id011
  name: Checkr
  slug: checkr
  status: profiled
  tags: *id012
  url: /providers/checkr/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id013
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id014
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id015
  name: Firebase Cloud Messaging
  slug: google-firebase
  status: profiled
  tags: *id016
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id017
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id018
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id019
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id020
  url: /providers/google-identity-platform/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 27.1
  mcp: *id021
  name: IPregistry
  slug: ipregistry
  status: profiled
  tags: *id022
  url: /providers/ipregistry/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id023
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id024
  url: /providers/mailgun/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id025
  name: Mandrill (Mailchimp Transactional)
  slug: mailchimp
  status: profiled
  tags: *id026
  url: /providers/mailchimp/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id027
  name: MaxMind
  slug: maxmind
  status: profiled
  tags: *id028
  url: /providers/maxmind/
- agent_band: agent-native
  agent_readiness: 43.6
  band: developing
  in_catalog: true
  kin_score: 50.1
  mcp: *id029
  name: NMI
  slug: nmi
  status: profiled
  tags: *id030
  url: /providers/nmi/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id031
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id032
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id033
  name: PayPal Payflow Pro
  slug: paypal
  status: profiled
  tags: *id034
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 40.7
  band: exemplar
  in_catalog: true
  kin_score: 84.0
  mcp: *id035
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id036
  url: /providers/sendgrid/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: thin
  in_catalog: true
  kin_score: 37.1
  mcp: *id037
  name: SmartyStreets
  slug: smarty
  status: profiled
  tags: *id038
  url: /providers/smarty/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id039
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id040
  url: /providers/twilio/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id041
  name: Twitter / X
  slug: x
  status: profiled
  tags: *id042
  url: /providers/x/
siblings:
- name: ChurchCRM
  rows: 7
  url: /applications/church-faith-management/churchcrm/
- name: OpenLP
  rows: 6
  url: /applications/church-faith-management/openlp/
- name: Planning Center
  rows: 20
  url: /applications/church-faith-management/planning-center/
- name: Pushpay
  rows: 20
  url: /applications/church-faith-management/pushpay/
- name: Tithe.ly
  rows: 11
  url: /applications/church-faith-management/tithe-ly/
sitemap: true
title: 'Rock RMS: Church & Faith Community Management reference app'
---
