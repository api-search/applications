---
app: PracticePanther
app_slug: practicepanther
app_url: https://www.practicepanther.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4330.70
  key: client-trust-and-retainer-fund-management
  layer: domain
  name: Client Trust and Retainer Fund Management
  providers:
  - TrustBooks
  url: /capabilities/client-trust-and-retainer-fund-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-918
  key: AE-918
  layer: domain
  name: Document Generation & Conversion
  providers:
  - WealthCounsel
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: Turbo EA
  id: BC-150
  key: legal-management
  layer: domain
  name: Legal Management
  providers:
  - Docketwise
  url: /capabilities/legal-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-150.20.20
  key: BC-150.20.20
  layer: domain
  name: Litigation Case Management
  providers:
  - LawToolBox
  url: /capabilities/litigation-dispute-management/
  via_parent: Litigation & Dispute Management
- attribution: Turbo EA
  id: BC-400.50
  key: marketing-operations-management
  layer: domain
  name: Marketing Operations Management
  providers:
  - Lawmatics
  url: /capabilities/marketing-operations-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50.30
  key: AE-150.50.30
  layer: domain
  name: Virtual Receptionists & Answering Services
  providers:
  - Smith.ai
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Box
  - Dropbox
  - Google Drive
  - OneDrive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
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
  - Microsoft Exchange
  - Microsoft Outlook
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Apptoto
  - Kenect
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: legal-practice
  name: Legal Practice Management
  url: /applications/legal-practice/
counts:
  declared: 19
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.practicepanther.com/integrations/
integrations:
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
    agent_readiness: 46.3
    band: developing
    in_catalog: true
    kin_score: 46.1
    mcp: &id001
      source: https://www.apptoto.com
      status: documented
    slug: apptoto
    status: profiled
    tags: &id002
    - Appointment-Reminders
    - Company
    - SMS
    - Scheduling
    url: /providers/apptoto/
  layer: common
  name: Apptoto
  provider: apptoto
  says: lists Apptoto as an integration
  source: https://www.practicepanther.com/integrations/
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
    agent_readiness: 57.4
    band: strong
    in_catalog: true
    kin_score: 65.5
    mcp: &id003
      source: https://developer.box.com/guides/box-mcp/
      status: verified
    slug: box
    status: profiled
    tags: &id004
    - Cloud Storage
    - Collaboration
    - Content Management
    - Documents
    url: /providers/box/
  layer: common
  name: Box
  provider: box
  says: lists Box as an integration
  source: https://www.practicepanther.com/integrations/
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
    mcp: &id005
      status: unknown
    slug: docketwise
    status: profiled
    tags: &id006
    - Company
    - Immigration
    - Law
    - Software-as-a-Service
    url: /providers/docketwise/
  layer: domain
  name: Docketwise
  provider: docketwise
  says: lists Docketwise as an integration
  source: https://www.practicepanther.com/integrations/
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
    mcp: &id007
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id008
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: common
  name: Dropbox
  provider: dropbox
  says: lists Dropbox as an integration
  source: https://www.practicepanther.com/integrations/
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
    mcp: &id009
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id010
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: common
  name: Gmail
  provider: google-gmail
  says: lists Gmail as an integration
  source: https://www.practicepanther.com/integrations/
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
    mcp: &id011
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id012
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://www.practicepanther.com/integrations/
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
    agent_readiness: 44.3
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id013
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id014
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: common
  name: Google Drive
  provider: google-drive
  says: lists Google Drive as an integration
  source: https://www.practicepanther.com/integrations/
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
    mcp: &id015
      status: unknown
    slug: kenect
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - Automotive
    - Customer Engagement
    - Messaging
    url: /providers/kenect/
  layer: common
  name: Kenect
  provider: kenect
  says: lists Kenect as an integration
  source: https://www.practicepanther.com/integrations/
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
    mcp: &id017
      status: unknown
    slug: lawmatics
    status: profiled
    tags: &id018
    - CRM
    - Client Intake
    - Law Firms
    - Legal
    url: /providers/lawmatics/
  layer: domain
  name: Lawmatics
  provider: lawmatics
  says: lists Lawmatics as an integration
  source: https://www.practicepanther.com/integrations/
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
    mcp: &id019
      status: none
    slug: lawtoolbox
    status: profiled
    tags: &id020
    - Calendar
    - Legal Tech
    - Matter Management
    - Microsoft 365
    url: /providers/lawtoolbox/
  layer: domain
  name: LawToolBox
  provider: lawtoolbox
  says: lists LawToolBox as an integration
  source: https://www.practicepanther.com/integrations/
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
    mcp: &id021
      status: none
    slug: mailchimp
    status: profiled
    tags: &id022
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://www.practicepanther.com/integrations/
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
    agent_readiness: 31.4
    band: strong
    in_catalog: true
    kin_score: 62.7
    mcp: &id023
      status: none
    slug: microsoft-exchange
    status: profiled
    tags: &id024
    - Calendar
    - Collaboration
    - Contacts
    - Email
    url: /providers/microsoft-exchange/
  layer: common
  name: Microsoft Exchange
  provider: microsoft-exchange
  says: lists Microsoft Exchange as an integration
  source: https://www.practicepanther.com/integrations/
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
    mcp: &id025
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id026
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: common
  name: Microsoft Outlook
  provider: microsoft-outlook
  says: lists Microsoft Outlook as an integration
  source: https://www.practicepanther.com/integrations/
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
    mcp: &id027
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id028
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: common
  name: OneDrive
  provider: microsoft-onedrive
  says: lists OneDrive as an integration
  source: https://www.practicepanther.com/integrations/
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
    mcp: &id029
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id030
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://www.practicepanther.com/integrations/
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
    mcp: &id031
      status: unknown
    slug: smith-ai
    status: profiled
    tags: &id032
    - Artificial Intelligence
    - Call Answering
    - Company
    - Receptionist
    url: /providers/smith-ai/
  layer: domain
  name: Smith.ai
  provider: smith-ai
  says: lists Smith.ai as an integration
  source: https://www.practicepanther.com/integrations/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id033
      status: none
    slug: trustbooks
    status: profiled
    tags: &id034
    - Accounting
    - Company
    - Legal Tech
    - Software-as-a-Service
    url: /providers/trustbooks/
  layer: domain
  name: TrustBooks
  provider: trustbooks
  says: lists TrustBooks as an integration
  source: https://www.practicepanther.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-918
    key: AE-918
    name: Document Generation & Conversion
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 6.1
    mcp: &id035
      status: unknown
    slug: wealthcounsel
    status: profiled
    tags: &id036
    - Company
    - Document Automation
    - Estate Planning
    - Legal Tech
    url: /providers/wealthcounsel/
  layer: domain
  name: WealthCounsel
  provider: wealthcounsel
  says: lists WealthCounsel as an integration
  source: https://www.practicepanther.com/integrations/
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
    mcp: &id037
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id038
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.practicepanther.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/legal-practice/practicepanther/
providers:
- agent_band: agent-ready
  agent_readiness: 46.3
  band: developing
  in_catalog: true
  kin_score: 46.1
  mcp: *id001
  name: Apptoto
  slug: apptoto
  status: profiled
  tags: *id002
  url: /providers/apptoto/
- agent_band: agent-ready
  agent_readiness: 57.4
  band: strong
  in_catalog: true
  kin_score: 65.5
  mcp: *id003
  name: Box
  slug: box
  status: profiled
  tags: *id004
  url: /providers/box/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.7
  mcp: *id005
  name: Docketwise
  slug: docketwise
  status: profiled
  tags: *id006
  url: /providers/docketwise/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id007
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id008
  url: /providers/dropbox/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id009
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id010
  url: /providers/google-gmail/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id011
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id012
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id013
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id014
  url: /providers/google-drive/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 14.7
  mcp: *id015
  name: Kenect
  slug: kenect
  status: profiled
  tags: *id016
  url: /providers/kenect/
- agent_band: agent-ready
  agent_readiness: 40.2
  band: strong
  in_catalog: true
  kin_score: 56.0
  mcp: *id017
  name: Lawmatics
  slug: lawmatics
  status: profiled
  tags: *id018
  url: /providers/lawmatics/
- agent_band: agent-aware
  agent_readiness: 16.4
  band: emerging
  in_catalog: true
  kin_score: 24.6
  mcp: *id019
  name: LawToolBox
  slug: lawtoolbox
  status: profiled
  tags: *id020
  url: /providers/lawtoolbox/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id021
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id022
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: strong
  in_catalog: true
  kin_score: 62.7
  mcp: *id023
  name: Microsoft Exchange
  slug: microsoft-exchange
  status: profiled
  tags: *id024
  url: /providers/microsoft-exchange/
- agent_band: agent-ready
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 70.6
  mcp: *id025
  name: Microsoft Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id026
  url: /providers/microsoft-outlook/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 48.3
  mcp: *id027
  name: OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id028
  url: /providers/microsoft-onedrive/
- agent_band: agent-native
  agent_readiness: 41.2
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id029
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id030
  url: /providers/quickbooks/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 23.3
  mcp: *id031
  name: Smith.ai
  slug: smith-ai
  status: profiled
  tags: *id032
  url: /providers/smith-ai/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id033
  name: TrustBooks
  slug: trustbooks
  status: profiled
  tags: *id034
  url: /providers/trustbooks/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 6.1
  mcp: *id035
  name: WealthCounsel
  slug: wealthcounsel
  status: profiled
  tags: *id036
  url: /providers/wealthcounsel/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id037
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id038
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
- name: MyCase
  rows: 28
  url: /applications/legal-practice/mycase/
- name: Smokeball
  rows: 4
  url: /applications/legal-practice/smokeball/
sitemap: true
title: 'PracticePanther: Legal Practice Management reference app'
---
