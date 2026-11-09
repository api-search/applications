---
app: MyCase
app_slug: mycase
app_url: https://www.mycase.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-200.30
  key: accounts-receivable-management
  layer: domain
  name: Accounts Receivable Management
  providers:
  - CollBox
  url: /capabilities/accounts-receivable-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3320.10.20
  key: BC-3320.10.20
  layer: domain
  name: Court E-Filing
  providers:
  - InfoTrack
  url: /capabilities/case-filing-and-initiation/
  via_parent: Case Filing and Initiation
- attribution: API Evangelist extension
  id: AE-917
  key: AE-917
  layer: domain
  name: Enterprise Content & Document Management
  providers:
  - NetDocuments
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-100.70.40
  key: AE-100.70.40
  layer: domain
  name: Legal AI Assistants
  providers:
  - Briefpoint
  - Clearbrief
  - Supio
  url: /capabilities/vertical-agents/
  via_parent: Vertical Agents
- attribution: Turbo EA
  id: BC-150.20.20
  key: BC-150.20.20
  layer: domain
  name: Litigation Case Management
  providers:
  - CourtDrive
  - LawToolBox
  url: /capabilities/litigation-dispute-management/
  via_parent: Litigation & Dispute Management
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: domain
  name: SMS
  providers:
  - Case Status
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-150.50.30
  key: AE-150.50.30
  layer: domain
  name: Virtual Receptionists & Answering Services
  providers:
  - Answering Legal
  - Intaker
  - Ruby Receptionists
  - Smith.ai
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Dropbox
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Scorpion
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
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
  - Google Calendar
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
  - Lawmatics
  - Levitate
  url: /capabilities/marketing-operations-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.70.20
  key: AE-170.70.20
  layer: common
  name: Translation Management & Localization
  providers:
  - MotaWord
  url: /capabilities/content-management/
  via_parent: Content Management
- attribution: API Evangelist extension
  id: AE-150.50
  key: AE-150.50
  layer: common
  name: Voice & Telephony
  providers:
  - VXT
  url: /capabilities/voice-telephony/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Claude (Anthropic)
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: legal-practice
  name: Legal Practice Management
  url: /applications/legal-practice/
counts:
  declared: 28
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.mycase.com/integrations/
integrations:
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
    mcp: &id001
      status: unknown
    slug: answering-legal
    status: profiled
    tags: &id002
    - AI Chatbot
    - Call Answering
    - Legal Services
    - Virtual Receptionist
    url: /providers/answering-legal/
  layer: domain
  name: Answering Legal
  provider: answering-legal
  says: lists Answering Legal as an integration
  source: https://www.mycase.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-100.70.40
    key: AE-100.70.40
    name: Legal AI Assistants
    url: /capabilities/vertical-agents/
    via_parent: Vertical Agents
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: emerging
    in_catalog: true
    kin_score: 15.2
    mcp: &id003
      source: https://api.briefpoint.ai/mcp
      status: verified
    slug: briefpoint
    status: profiled
    tags: &id004
    - Artificial Intelligence
    - Discovery
    - Document Automation
    - Legal Tech
    url: /providers/briefpoint/
  layer: domain
  name: Briefpoint
  provider: briefpoint
  says: lists Briefpoint as an integration
  source: https://www.mycase.com/integrations/
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
  source: https://www.mycase.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 12.2
    band: emerging
    in_catalog: true
    kin_score: 17.6
    mcp: &id007
      status: none
    slug: case-status
    status: profiled
    tags: &id008
    - Client Communication
    - Company
    - Legal
    - Legal Tech
    url: /providers/case-status/
  layer: domain
  name: Case Status
  provider: case-status
  says: lists Case Status as an integration
  source: https://www.mycase.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 87.5
    mcp: &id009
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id010
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Claude (Anthropic)
  provider: anthropic
  says: lists Claude (Anthropic) as an integration
  source: https://www.mycase.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-100.70.40
    key: AE-100.70.40
    name: Legal AI Assistants
    url: /capabilities/vertical-agents/
    via_parent: Vertical Agents
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.3
    mcp: &id011
      status: unknown
    slug: clearbrief
    status: profiled
    tags: &id012
    - Artificial Intelligence
    - Company
    - Document Automation
    - Legal Tech
    url: /providers/clearbrief/
  layer: domain
  name: Clearbrief
  provider: clearbrief
  says: lists Clearbrief as an integration
  source: https://www.mycase.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.30
    key: accounts-receivable-management
    name: Accounts Receivable Management
    url: /capabilities/accounts-receivable-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.8
    mcp: &id013
      status: none
    slug: collbox
    status: profiled
    tags: &id014
    - Company
    - Finance
    - Law
    - Software-as-a-Service
    url: /providers/collbox/
  layer: domain
  name: CollBox
  provider: collbox
  says: lists CollBox as an integration
  source: https://www.mycase.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150.20.20
    key: BC-150.20.20
    name: Litigation Case Management
    url: /capabilities/litigation-dispute-management/
    via_parent: Litigation & Dispute Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 16.6
    mcp: &id015
      source: https://courtdrive.com/
      status: documented
    slug: courtdrive
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - Automation
    - Docketing
    - Legal Tech
    url: /providers/courtdrive/
  layer: domain
  name: CourtDrive
  provider: courtdrive
  says: lists CourtDrive as an integration
  source: https://www.mycase.com/integrations/
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
    agent_readiness: 45.8
    band: developing
    in_catalog: true
    kin_score: 47.9
    mcp: &id017
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id018
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: common
  name: Dropbox
  provider: dropbox
  says: lists Dropbox as an integration
  source: https://www.mycase.com/integrations/
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
    mcp: &id019
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id020
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: common
  name: Gmail
  provider: google-gmail
  says: lists Gmail as an integration
  source: https://www.mycase.com/integrations/
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
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id021
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id022
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://www.mycase.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3320.10.20
    key: BC-3320.10.20
    name: Court E-Filing
    url: /capabilities/case-filing-and-initiation/
    via_parent: Case Filing and Initiation
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id023
      status: unchecked
    slug: infotrack
    status: queued for profiling
    tags: &id024 []
    url: null
  layer: domain
  name: InfoTrack
  provider: infotrack
  says: lists InfoTrack as an integration
  source: https://www.mycase.com/integrations/
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
    mcp: &id025
      status: unknown
    slug: intaker
    status: profiled
    tags: &id026
    - Artificial Intelligence
    - Automation
    - Law Firms
    - Legal Tech
    url: /providers/intaker/
  layer: domain
  name: Intaker
  provider: intaker
  says: lists Intaker as an integration
  source: https://www.mycase.com/integrations/
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
    agent_readiness: 40.2
    band: strong
    in_catalog: true
    kin_score: 56.0
    mcp: &id027
      status: unknown
    slug: lawmatics
    status: profiled
    tags: &id028
    - CRM
    - Client Intake
    - Law Firms
    - Legal
    url: /providers/lawmatics/
  layer: domain
  name: Lawmatics
  provider: lawmatics
  says: lists Lawmatics as an integration
  source: https://www.mycase.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150.20.20
    key: BC-150.20.20
    name: Litigation Case Management
    url: /capabilities/litigation-dispute-management/
    via_parent: Litigation & Dispute Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.4
    band: emerging
    in_catalog: true
    kin_score: 24.6
    mcp: &id029
      status: none
    slug: lawtoolbox
    status: profiled
    tags: &id030
    - Calendar
    - Legal Tech
    - Matter Management
    - Microsoft 365
    url: /providers/lawtoolbox/
  layer: domain
  name: LawToolBox
  provider: lawtoolbox
  says: lists LawToolBox as an integration
  source: https://www.mycase.com/integrations/
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
    agent_readiness: 46.3
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id031
      status: unknown
    slug: levitate
    status: profiled
    tags: &id032
    - CRM
    - Contacts
    - Email Marketing
    - relationship-marketing
    url: /providers/levitate/
  layer: common
  name: Levitate
  provider: levitate
  says: lists Levitate as an integration
  source: https://www.mycase.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.3
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id033
      status: none
    slug: mailchimp
    status: profiled
    tags: &id034
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://www.mycase.com/integrations/
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
    mcp: &id035
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id036
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: common
  name: Microsoft Outlook
  provider: microsoft-outlook
  says: lists Microsoft Outlook as an integration
  source: https://www.mycase.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.20
    key: AE-170.70.20
    name: Translation Management & Localization
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.0
    band: developing
    in_catalog: true
    kin_score: 39.5
    mcp: &id037
      source: https://github.com/MotaWord/mcp
      status: verified
    slug: motaword
    status: profiled
    tags: &id038
    - Artificial Intelligence
    - Localization
    - Software-as-a-Service
    - Translation
    url: /providers/motaword/
  layer: common
  name: MotaWord
  provider: motaword
  says: lists MotaWord as an integration
  source: https://www.mycase.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-917
    key: AE-917
    name: Enterprise Content & Document Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.6
    band: minimal
    in_catalog: true
    kin_score: 10.4
    mcp: &id039
      source: https://netdocuments.com
      status: documented
    slug: netdocuments
    status: profiled
    tags: &id040
    - Document Management
    - Email Management
    - Legal AI
    - Workflow Automation
    url: /providers/netdocuments/
  layer: domain
  name: NetDocuments
  provider: netdocuments
  says: lists NetDocuments as an integration
  source: https://www.mycase.com/integrations/
  tier: declared
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
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id041
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id042
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: lists OpenAI as an integration
  source: https://www.mycase.com/integrations/
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
  source: https://www.mycase.com/integrations/
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
    agent_readiness: 16.9
    band: emerging
    in_catalog: true
    kin_score: 12.8
    mcp: &id045
      status: unknown
    slug: ruby-receptionists
    status: profiled
    tags: &id046
    - 24-7-support
    - Live Chat
    - Small Business
    - Virtual Receptionist
    url: /providers/ruby-receptionists/
  layer: domain
  name: Ruby Receptionists
  provider: ruby-receptionists
  says: lists Ruby Receptionists as an integration
  source: https://www.mycase.com/integrations/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.3
    mcp: &id047
      status: none
    slug: scorpion
    status: profiled
    tags: &id048
    - Advertising
    - Company
    - Digital Marketing
    - Marketing
    url: /providers/scorpion/
  layer: common
  name: Scorpion
  provider: scorpion
  says: lists Scorpion as an integration
  source: https://www.mycase.com/integrations/
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
    mcp: &id049
      status: unknown
    slug: smith-ai
    status: profiled
    tags: &id050
    - Artificial Intelligence
    - Call Answering
    - Company
    - Receptionist
    url: /providers/smith-ai/
  layer: domain
  name: Smith.ai
  provider: smith-ai
  says: lists Smith.ai as an integration
  source: https://www.mycase.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-100.70.40
    key: AE-100.70.40
    name: Legal AI Assistants
    url: /capabilities/vertical-agents/
    via_parent: Vertical Agents
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 21.6
    mcp: &id051
      status: unknown
    slug: supio
    status: profiled
    tags: &id052
    - Artificial Intelligence
    - Company
    - Legal
    - Legal Tech
    url: /providers/supio/
  layer: domain
  name: Supio
  provider: supio
  says: lists Supio as an integration
  source: https://www.mycase.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 6.8
    band: emerging
    in_catalog: true
    kin_score: 20.3
    mcp: &id053
      status: unknown
    slug: vxt
    status: profiled
    tags: &id054
    - Artificial Intelligence
    - Call Automation
    - Company
    - Legal Tech
    url: /providers/vxt/
  layer: common
  name: VXT
  provider: vxt
  says: lists VXT as an integration
  source: https://www.mycase.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id055
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id056
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.mycase.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/legal-practice/mycase/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.4
  mcp: *id001
  name: Answering Legal
  slug: answering-legal
  status: profiled
  tags: *id002
  url: /providers/answering-legal/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: emerging
  in_catalog: true
  kin_score: 15.2
  mcp: *id003
  name: Briefpoint
  slug: briefpoint
  status: profiled
  tags: *id004
  url: /providers/briefpoint/
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
  agent_readiness: 12.2
  band: emerging
  in_catalog: true
  kin_score: 17.6
  mcp: *id007
  name: Case Status
  slug: case-status
  status: profiled
  tags: *id008
  url: /providers/case-status/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 87.5
  mcp: *id009
  name: Claude (Anthropic)
  slug: anthropic
  status: profiled
  tags: *id010
  url: /providers/anthropic/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.3
  mcp: *id011
  name: Clearbrief
  slug: clearbrief
  status: profiled
  tags: *id012
  url: /providers/clearbrief/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.8
  mcp: *id013
  name: CollBox
  slug: collbox
  status: profiled
  tags: *id014
  url: /providers/collbox/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 16.6
  mcp: *id015
  name: CourtDrive
  slug: courtdrive
  status: profiled
  tags: *id016
  url: /providers/courtdrive/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id017
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id018
  url: /providers/dropbox/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id019
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id020
  url: /providers/google-gmail/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id021
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id022
  url: /providers/google-calendar/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id023
  name: InfoTrack
  slug: infotrack
  status: queued for profiling
  tags: *id024
  url: null
- agent_band: agent-aware
  agent_readiness: 5.4
  band: emerging
  in_catalog: true
  kin_score: 15.8
  mcp: *id025
  name: Intaker
  slug: intaker
  status: profiled
  tags: *id026
  url: /providers/intaker/
- agent_band: agent-ready
  agent_readiness: 40.2
  band: strong
  in_catalog: true
  kin_score: 56.0
  mcp: *id027
  name: Lawmatics
  slug: lawmatics
  status: profiled
  tags: *id028
  url: /providers/lawmatics/
- agent_band: agent-aware
  agent_readiness: 16.4
  band: emerging
  in_catalog: true
  kin_score: 24.6
  mcp: *id029
  name: LawToolBox
  slug: lawtoolbox
  status: profiled
  tags: *id030
  url: /providers/lawtoolbox/
- agent_band: agent-ready
  agent_readiness: 46.3
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id031
  name: Levitate
  slug: levitate
  status: profiled
  tags: *id032
  url: /providers/levitate/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id033
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id034
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 70.6
  mcp: *id035
  name: Microsoft Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id036
  url: /providers/microsoft-outlook/
- agent_band: agent-ready
  agent_readiness: 37.0
  band: developing
  in_catalog: true
  kin_score: 39.5
  mcp: *id037
  name: MotaWord
  slug: motaword
  status: profiled
  tags: *id038
  url: /providers/motaword/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: minimal
  in_catalog: true
  kin_score: 10.4
  mcp: *id039
  name: NetDocuments
  slug: netdocuments
  status: profiled
  tags: *id040
  url: /providers/netdocuments/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id041
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id042
  url: /providers/openai/
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
- agent_band: agent-aware
  agent_readiness: 16.9
  band: emerging
  in_catalog: true
  kin_score: 12.8
  mcp: *id045
  name: Ruby Receptionists
  slug: ruby-receptionists
  status: profiled
  tags: *id046
  url: /providers/ruby-receptionists/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.3
  mcp: *id047
  name: Scorpion
  slug: scorpion
  status: profiled
  tags: *id048
  url: /providers/scorpion/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 23.3
  mcp: *id049
  name: Smith.ai
  slug: smith-ai
  status: profiled
  tags: *id050
  url: /providers/smith-ai/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 21.6
  mcp: *id051
  name: Supio
  slug: supio
  status: profiled
  tags: *id052
  url: /providers/supio/
- agent_band: agent-aware
  agent_readiness: 6.8
  band: emerging
  in_catalog: true
  kin_score: 20.3
  mcp: *id053
  name: VXT
  slug: vxt
  status: profiled
  tags: *id054
  url: /providers/vxt/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id055
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id056
  url: /providers/zapier/
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
- name: Lawmatics
  rows: 29
  url: /applications/legal-practice/lawmatics/
- name: PracticePanther
  rows: 19
  url: /applications/legal-practice/practicepanther/
- name: Smokeball
  rows: 4
  url: /applications/legal-practice/smokeball/
sitemap: true
title: 'MyCase: Legal Practice Management reference app'
---
