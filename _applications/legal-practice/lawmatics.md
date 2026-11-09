---
app: Lawmatics
app_slug: lawmatics
app_url: https://www.lawmatics.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4330.70
  key: client-trust-and-retainer-fund-management
  layer: domain
  name: Client Trust and Retainer Fund Management
  providers:
  - 8am LawPay
  - Confido Legal
  url: /capabilities/client-trust-and-retainer-fund-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-150
  key: legal-management
  layer: domain
  name: Legal Management
  providers:
  - CARET Legal
  - Clio
  - Docketwise
  - Filevine
  - LEAP Legal Software
  - MyCase (8am)
  - Neostella
  - PracticePanther
  - Rocket Matter
  - SmartAdvocate
  - Smokeball
  - SurePoint Pro
  url: /capabilities/legal-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50.30
  key: AE-150.50.30
  layer: domain
  name: Virtual Receptionists & Answering Services
  providers:
  - Answering Legal
  - Intaker
  - Smith.ai
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - OneDrive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Google Ads
  - Meta Ads
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - QuickBooks
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  - Microsoft Outlook
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.50
  key: marketing-operations-management
  layer: common
  name: Marketing Operations Management
  providers:
  - CallRail
  url: /capabilities/marketing-operations-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Kenect
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: common
  name: Video Calling
  providers:
  - Microsoft Teams
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50
  key: AE-150.50
  layer: common
  name: Voice & Telephony
  providers:
  - Ooma
  - RingCentral
  url: /capabilities/voice-telephony/
  via_parent: null
category:
  id: legal-practice
  name: Legal Practice Management
  url: /applications/legal-practice/
counts:
  declared: 29
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.lawmatics.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4330.70
    key: client-trust-and-retainer-fund-management
    name: Client Trust and Retainer Fund Management
    url: /capabilities/client-trust-and-retainer-fund-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.7
    band: thin
    in_catalog: true
    kin_score: 28.3
    mcp: &id001
      status: none
    slug: lawpay
    status: profiled
    tags: &id002
    - Company
    - Fintech
    - Legal Tech
    - Payments
    url: /providers/lawpay/
  layer: domain
  name: 8am LawPay
  provider: lawpay
  says: lists 8am LawPay as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.30
    key: AE-150.50.30
    name: Virtual Receptionists & Answering Services
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.4
    mcp: &id003
      status: unknown
    slug: answering-legal
    status: profiled
    tags: &id004
    - AI Chatbot
    - Call Answering
    - Legal Services
    - Virtual Receptionist
    url: /providers/answering-legal/
  layer: domain
  name: Answering Legal
  provider: answering-legal
  says: lists Answering Legal as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.50
    key: marketing-operations-management
    name: Marketing Operations Management
    url: /capabilities/marketing-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.8
    band: developing
    in_catalog: true
    kin_score: 53.9
    mcp: &id005
      status: none
    slug: callrail
    status: profiled
    tags: &id006
    - Call Tracking
    - Conversation Intelligence
    - Lead Tracking
    - Marketing Attribution
    url: /providers/callrail/
  layer: common
  name: CallRail
  provider: callrail
  says: lists CallRail as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150
    key: legal-management
    name: Legal Management
    url: /capabilities/legal-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.3
    band: emerging
    in_catalog: true
    kin_score: 17.5
    mcp: &id007
      status: unknown
    slug: caret-legal
    status: profiled
    tags: &id008
    - Cloud
    - Company
    - Legal Tech
    - Software-as-a-Service
    url: /providers/caret-legal/
  layer: domain
  name: CARET Legal
  provider: caret-legal
  says: lists CARET Legal as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150
    key: legal-management
    name: Legal Management
    url: /capabilities/legal-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: developing
    in_catalog: true
    kin_score: 53.3
    mcp: &id009
      status: none
    slug: clio
    status: profiled
    tags: &id010
    - Billing
    - Calendaring
    - Document Management
    - Law Firms
    url: /providers/clio/
  layer: domain
  name: Clio
  provider: clio
  says: lists Clio as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4330.70
    key: client-trust-and-retainer-fund-management
    name: Client Trust and Retainer Fund Management
    url: /capabilities/client-trust-and-retainer-fund-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.7
    band: developing
    in_catalog: true
    kin_score: 53.1
    mcp: &id011
      status: none
    slug: confido-legal
    status: profiled
    tags: &id012
    - Compliance
    - Disbursements
    - GraphQL
    - IOLTA
    url: /providers/confido-legal/
  layer: domain
  name: Confido Legal
  provider: confido-legal
  says: lists Confido Legal as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150
    key: legal-management
    name: Legal Management
    url: /capabilities/legal-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 18.7
    mcp: &id013
      status: unknown
    slug: docketwise
    status: profiled
    tags: &id014
    - Company
    - Immigration
    - Law
    - Software-as-a-Service
    url: /providers/docketwise/
  layer: domain
  name: Docketwise
  provider: docketwise
  says: lists Docketwise as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150
    key: legal-management
    name: Legal Management
    url: /capabilities/legal-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.9
    band: developing
    in_catalog: true
    kin_score: 53.1
    mcp: &id015
      status: none
    slug: filevine
    status: profiled
    tags: &id016
    - Case Management
    - Intake
    - Legal
    - Matter
    url: /providers/filevine/
  layer: domain
  name: Filevine
  provider: filevine
  says: lists Filevine as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id017
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id018
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: common
  name: Gmail
  provider: google-gmail
  says: lists Gmail as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.7
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id019
      source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
      status: verified
    slug: google-ads
    status: profiled
    tags: &id020
    - Advertising
    - Campaign Management
    - Digital Advertising
    - Google
    url: /providers/google-ads/
  layer: common
  name: Google Ads
  provider: google-ads
  says: lists Google Ads as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.30
    key: AE-150.50.30
    name: Virtual Receptionists & Answering Services
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.4
    band: emerging
    in_catalog: true
    kin_score: 15.8
    mcp: &id021
      status: unknown
    slug: intaker
    status: profiled
    tags: &id022
    - Artificial Intelligence
    - Automation
    - Law Firms
    - Legal Tech
    url: /providers/intaker/
  layer: domain
  name: Intaker
  provider: intaker
  says: lists Intaker as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 14.7
    mcp: &id023
      status: unknown
    slug: kenect
    status: profiled
    tags: &id024
    - Artificial Intelligence
    - Automotive
    - Customer Engagement
    - Messaging
    url: /providers/kenect/
  layer: common
  name: Kenect
  provider: kenect
  says: lists Kenect as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150
    key: legal-management
    name: Legal Management
    url: /capabilities/legal-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.4
    mcp: &id025
      status: none
    slug: leap-legal
    status: profiled
    tags: &id026
    - Legal
    - Legal Accounting
    - Legal Tech
    - Practice Management
    url: /providers/leap-legal/
  layer: domain
  name: LEAP Legal Software
  provider: leap-legal
  says: lists LEAP Legal Software as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id027
      status: none
    slug: facebook
    status: profiled
    tags: &id028
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Meta Ads
  provider: facebook
  says: lists Meta Ads as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 49.5
    band: exemplar
    in_catalog: true
    kin_score: 70.6
    mcp: &id029
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id030
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: common
  name: Microsoft Outlook
  provider: microsoft-outlook
  says: lists Microsoft Outlook as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.2
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id031
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id032
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150
    key: legal-management
    name: Legal Management
    url: /capabilities/legal-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.4
    band: thin
    in_catalog: true
    kin_score: 35.0
    mcp: &id033
      source: https://www.mycase.com/integrations/mycase-mcp/
      status: documented
    slug: mycase
    status: profiled
    tags: &id034
    - Billing
    - Calendaring
    - Case Management
    - Client Portal
    url: /providers/mycase/
  layer: domain
  name: MyCase (8am)
  provider: mycase
  says: lists MyCase (8am) as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150
    key: legal-management
    name: Legal Management
    url: /capabilities/legal-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 17.4
    mcp: &id035
      status: unknown
    slug: neostella
    status: profiled
    tags: &id036
    - Case Management
    - Company
    - Legal Tech
    - Software-as-a-Service
    url: /providers/neostella/
  layer: domain
  name: Neostella
  provider: neostella
  says: lists Neostella as an integration
  source: https://www.lawmatics.com/integrations
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
    agent_readiness: 25.2
    band: developing
    in_catalog: true
    kin_score: 48.3
    mcp: &id037
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id038
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: common
  name: OneDrive
  provider: microsoft-onedrive
  says: lists OneDrive as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50
    key: AE-150.50
    name: Voice & Telephony
    url: /capabilities/voice-telephony/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.5
    band: minimal
    in_catalog: true
    kin_score: 7.2
    mcp: &id039
      status: unknown
    slug: ooma
    status: profiled
    tags: &id040
    - Business Communications
    - Cloud Services
    - Telecommunications
    - VoIP
    url: /providers/ooma/
  layer: common
  name: Ooma
  provider: ooma
  says: lists Ooma as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150
    key: legal-management
    name: Legal Management
    url: /capabilities/legal-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.1
    band: thin
    in_catalog: true
    kin_score: 37.5
    mcp: &id041
      status: unknown
    slug: practicepanther
    status: profiled
    tags: &id042
    - Billing
    - Case Management
    - Law Practice Management
    - Legal
    url: /providers/practicepanther/
  layer: domain
  name: PracticePanther
  provider: practicepanther
  says: lists PracticePanther as an integration
  source: https://www.lawmatics.com/integrations
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
    mcp: &id043
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id044
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50
    key: AE-150.50
    name: Voice & Telephony
    url: /capabilities/voice-telephony/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.5
    band: strong
    in_catalog: true
    kin_score: 61.5
    mcp: &id045
      source: https://developers.ringcentral.com/mcp
      status: documented
    slug: ringcentral
    status: profiled
    tags: &id046
    - Communications
    - UCaaS
    - Video
    - Voice
    url: /providers/ringcentral/
  layer: common
  name: RingCentral
  provider: ringcentral
  says: lists RingCentral as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150
    key: legal-management
    name: Legal Management
    url: /capabilities/legal-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.0
    band: thin
    in_catalog: true
    kin_score: 36.2
    mcp: &id047
      status: unknown
    slug: rocket-matter
    status: profiled
    tags: &id048
    - Company
    - Legal Tech
    - Practice Management
    - Software-as-a-Service
    url: /providers/rocket-matter/
  layer: domain
  name: Rocket Matter
  provider: rocket-matter
  says: lists Rocket Matter as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150
    key: legal-management
    name: Legal Management
    url: /capabilities/legal-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 9.9
    band: minimal
    in_catalog: true
    kin_score: 10.2
    mcp: &id049
      status: unknown
    slug: smartadvocate
    status: profiled
    tags: &id050
    - Case Management
    - Legal Tech
    - Litigation
    - Software
    url: /providers/smartadvocate/
  layer: domain
  name: SmartAdvocate
  provider: smartadvocate
  says: lists SmartAdvocate as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.30
    key: AE-150.50.30
    name: Virtual Receptionists & Answering Services
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 23.3
    mcp: &id051
      status: unknown
    slug: smith-ai
    status: profiled
    tags: &id052
    - Artificial Intelligence
    - Call Answering
    - Company
    - Receptionist
    url: /providers/smith-ai/
  layer: domain
  name: Smith.ai
  provider: smith-ai
  says: lists Smith.ai as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150
    key: legal-management
    name: Legal Management
    url: /capabilities/legal-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.9
    band: thin
    in_catalog: true
    kin_score: 38.7
    mcp: &id053
      status: none
    slug: smokeball
    status: profiled
    tags: &id054
    - Law Firms
    - Legal
    - Matter
    - Practice Management
    url: /providers/smokeball/
  layer: domain
  name: Smokeball
  provider: smokeball
  says: lists Smokeball as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150
    key: legal-management
    name: Legal Management
    url: /capabilities/legal-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: emerging
    in_catalog: true
    kin_score: 25.2
    mcp: &id055
      status: unknown
    slug: surepoint
    status: profiled
    tags: &id056
    - Company
    - Platform
    - Software
    - Technology
    url: /providers/surepoint/
  layer: domain
  name: SurePoint Pro
  provider: surepoint
  says: lists SurePoint Pro as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 55.2
    band: strong
    in_catalog: true
    kin_score: 56.2
    mcp: &id057
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id058
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: common
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://www.lawmatics.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/legal-practice/lawmatics/
providers:
- agent_band: agent-aware
  agent_readiness: 14.7
  band: thin
  in_catalog: true
  kin_score: 28.3
  mcp: *id001
  name: 8am LawPay
  slug: lawpay
  status: profiled
  tags: *id002
  url: /providers/lawpay/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.4
  mcp: *id003
  name: Answering Legal
  slug: answering-legal
  status: profiled
  tags: *id004
  url: /providers/answering-legal/
- agent_band: agent-ready
  agent_readiness: 32.8
  band: developing
  in_catalog: true
  kin_score: 53.9
  mcp: *id005
  name: CallRail
  slug: callrail
  status: profiled
  tags: *id006
  url: /providers/callrail/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: emerging
  in_catalog: true
  kin_score: 17.5
  mcp: *id007
  name: CARET Legal
  slug: caret-legal
  status: profiled
  tags: *id008
  url: /providers/caret-legal/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: developing
  in_catalog: true
  kin_score: 53.3
  mcp: *id009
  name: Clio
  slug: clio
  status: profiled
  tags: *id010
  url: /providers/clio/
- agent_band: agent-ready
  agent_readiness: 36.7
  band: developing
  in_catalog: true
  kin_score: 53.1
  mcp: *id011
  name: Confido Legal
  slug: confido-legal
  status: profiled
  tags: *id012
  url: /providers/confido-legal/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.7
  mcp: *id013
  name: Docketwise
  slug: docketwise
  status: profiled
  tags: *id014
  url: /providers/docketwise/
- agent_band: agent-aware
  agent_readiness: 22.9
  band: developing
  in_catalog: true
  kin_score: 53.1
  mcp: *id015
  name: Filevine
  slug: filevine
  status: profiled
  tags: *id016
  url: /providers/filevine/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id017
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id018
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id019
  name: Google Ads
  slug: google-ads
  status: profiled
  tags: *id020
  url: /providers/google-ads/
- agent_band: agent-aware
  agent_readiness: 5.4
  band: emerging
  in_catalog: true
  kin_score: 15.8
  mcp: *id021
  name: Intaker
  slug: intaker
  status: profiled
  tags: *id022
  url: /providers/intaker/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 14.7
  mcp: *id023
  name: Kenect
  slug: kenect
  status: profiled
  tags: *id024
  url: /providers/kenect/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.4
  mcp: *id025
  name: LEAP Legal Software
  slug: leap-legal
  status: profiled
  tags: *id026
  url: /providers/leap-legal/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id027
  name: Meta Ads
  slug: facebook
  status: profiled
  tags: *id028
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 70.6
  mcp: *id029
  name: Microsoft Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id030
  url: /providers/microsoft-outlook/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id031
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id032
  url: /providers/microsoft-teams/
- agent_band: agent-aware
  agent_readiness: 18.4
  band: thin
  in_catalog: true
  kin_score: 35.0
  mcp: *id033
  name: MyCase (8am)
  slug: mycase
  status: profiled
  tags: *id034
  url: /providers/mycase/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 17.4
  mcp: *id035
  name: Neostella
  slug: neostella
  status: profiled
  tags: *id036
  url: /providers/neostella/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 48.3
  mcp: *id037
  name: OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id038
  url: /providers/microsoft-onedrive/
- agent_band: human-only
  agent_readiness: 3.5
  band: minimal
  in_catalog: true
  kin_score: 7.2
  mcp: *id039
  name: Ooma
  slug: ooma
  status: profiled
  tags: *id040
  url: /providers/ooma/
- agent_band: agent-aware
  agent_readiness: 26.1
  band: thin
  in_catalog: true
  kin_score: 37.5
  mcp: *id041
  name: PracticePanther
  slug: practicepanther
  status: profiled
  tags: *id042
  url: /providers/practicepanther/
- agent_band: agent-native
  agent_readiness: 41.2
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id043
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id044
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 44.5
  band: strong
  in_catalog: true
  kin_score: 61.5
  mcp: *id045
  name: RingCentral
  slug: ringcentral
  status: profiled
  tags: *id046
  url: /providers/ringcentral/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: thin
  in_catalog: true
  kin_score: 36.2
  mcp: *id047
  name: Rocket Matter
  slug: rocket-matter
  status: profiled
  tags: *id048
  url: /providers/rocket-matter/
- agent_band: agent-aware
  agent_readiness: 9.9
  band: minimal
  in_catalog: true
  kin_score: 10.2
  mcp: *id049
  name: SmartAdvocate
  slug: smartadvocate
  status: profiled
  tags: *id050
  url: /providers/smartadvocate/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 23.3
  mcp: *id051
  name: Smith.ai
  slug: smith-ai
  status: profiled
  tags: *id052
  url: /providers/smith-ai/
- agent_band: agent-ready
  agent_readiness: 32.9
  band: thin
  in_catalog: true
  kin_score: 38.7
  mcp: *id053
  name: Smokeball
  slug: smokeball
  status: profiled
  tags: *id054
  url: /providers/smokeball/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: emerging
  in_catalog: true
  kin_score: 25.2
  mcp: *id055
  name: SurePoint Pro
  slug: surepoint
  status: profiled
  tags: *id056
  url: /providers/surepoint/
- agent_band: agent-ready
  agent_readiness: 55.2
  band: strong
  in_catalog: true
  kin_score: 56.2
  mcp: *id057
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id058
  url: /providers/zoom/
siblings:
- name: ArkCase
  rows: 8
  url: /applications/legal-practice/arkcase/
- name: Clio
  rows: 0
  url: /applications/legal-practice/clio/
- name: CosmoLex
  rows: 6
  url: /applications/legal-practice/cosmolex/
- name: Filevine
  rows: 5
  url: /applications/legal-practice/filevine/
- name: MyCase
  rows: 28
  url: /applications/legal-practice/mycase/
- name: PracticePanther
  rows: 19
  url: /applications/legal-practice/practicepanther/
- name: Smokeball
  rows: 4
  url: /applications/legal-practice/smokeball/
sitemap: true
title: 'Lawmatics: Legal Practice Management reference app'
---
