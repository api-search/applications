---
app: Planning Pod
app_slug: planning-pod
app_url: https://www.planningpod.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-210.50
  key: AE-210.50
  layer: domain
  name: Event Ticketing
  providers:
  - Eventbrite
  url: /capabilities/event-ticketing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Evernote
  - Google Drive/Docs/Sheets
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Infusionsoft
  - Pipedrive
  - Salesforce
  - Zoho CRM
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - AWeber
  - Constant Contact
  - MailChimp
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - Freshbooks
  - Quickbooks
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  - Google Calendar/Contacts
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - Asana
  - Basecamp
  - Trello
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50
  key: social-networks-community
  layer: common
  name: Social Networks & Community
  providers:
  - Facebook Pages
  - Twitter
  url: /capabilities/social-networks-community/
  via_parent: null
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
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: wedding-event-planning
  name: Wedding & Event Planning
  url: /applications/wedding-event-planning/
counts:
  declared: 23
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
integrations:
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 55.3
    band: exemplar
    in_catalog: true
    kin_score: 72.5
    mcp: &id001
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id002
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
  layer: common
  name: Asana
  provider: asana
  says: lists Asana as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
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
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id003
      source: https://github.com/aweber/aweber-mcp
      status: verified
    slug: aweber
    status: profiled
    tags: &id004
    - Email
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/aweber/
  layer: common
  name: AWeber
  provider: aweber
  says: lists AWeber as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.9
    band: developing
    in_catalog: true
    kin_score: 49.0
    mcp: &id005
      source: https://github.com/basecamp/mcp
      status: verified
    slug: basecamp
    status: profiled
    tags: &id006
    - Collaboration
    - Project Management
    - REST
    - Software-as-a-Service
    url: /providers/basecamp/
  layer: common
  name: Basecamp
  provider: basecamp
  says: lists Basecamp as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
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
    agent_readiness: 31.4
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id007
      status: none
    slug: constant-contact
    status: profiled
    tags: &id008
    - Campaigns
    - Contacts
    - Email Marketing
    - Event
    url: /providers/constant-contact/
  layer: common
  name: Constant Contact
  provider: constant-contact
  says: lists Constant Contact as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.50
    key: AE-210.50
    name: Event Ticketing
    url: /capabilities/event-ticketing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: developing
    in_catalog: true
    kin_score: 41.6
    mcp: &id009
      status: none
    slug: eventbrite
    status: profiled
    tags: &id010
    - Event
    - Event Technology
    - Marketplace
    - Ticketing
    url: /providers/eventbrite/
  layer: domain
  name: Eventbrite
  provider: eventbrite
  says: lists Eventbrite as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
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
    agent_readiness: 28.0
    band: developing
    in_catalog: true
    kin_score: 53.0
    mcp: &id011
      source: https://dev.evernote.com/
      status: documented
    slug: evernote
    status: profiled
    tags: &id012
    - Company
    - Knowledge Management
    - Note Taking
    - Productivity
    url: /providers/evernote/
  layer: common
  name: Evernote
  provider: evernote
  says: lists Evernote as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: social-networks-community
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
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
  name: Facebook Pages
  provider: facebook
  says: lists Facebook Pages as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
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
    agent_band: agent-aware
    agent_readiness: 19.7
    band: thin
    in_catalog: true
    kin_score: 31.0
    mcp: &id015
      status: none
    slug: freshbooks
    status: profiled
    tags: &id016
    - Accounting
    - Expense Tracking
    - Invoicing
    - Time Tracking
    url: /providers/freshbooks/
  layer: common
  name: Freshbooks
  provider: freshbooks
  says: lists Freshbooks as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
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
    agent_readiness: 43.2
    band: exemplar
    in_catalog: true
    kin_score: 66.8
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
  provider: gmail
  says: lists Gmail as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
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
    agent_readiness: 44.1
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id019
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id020
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar/Contacts
  provider: google-calendar
  says: lists Google Calendar/Contacts as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
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
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 73.2
    mcp: &id021
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id022
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: common
  name: Google Drive/Docs/Sheets
  provider: google-drive
  says: lists Google Drive/Docs/Sheets as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id023
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id024
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: common
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.5
    band: strong
    in_catalog: true
    kin_score: 65.0
    mcp: &id025
      status: none
    slug: keap
    status: profiled
    tags: &id026
    - CRM
    - Marketing Automation
    - Sales
    - Small Business
    url: /providers/keap/
  layer: common
  name: Infusionsoft
  provider: keap
  says: lists Infusionsoft as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
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
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id027
      status: none
    slug: mailchimp
    status: profiled
    tags: &id028
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: MailChimp
  provider: mailchimp
  says: lists MailChimp as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: strong
    in_catalog: true
    kin_score: 55.3
    mcp: &id029
      status: none
    slug: pipedrive
    status: profiled
    tags: &id030
    - CRM
    - Pipeline Management
    - Sales
    - Software-as-a-Service
    url: /providers/pipedrive/
  layer: common
  name: Pipedrive
  provider: pipedrive
  says: lists Pipedrive as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
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
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id031
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id032
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: Quickbooks
  provider: quickbooks
  says: lists Quickbooks as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id033
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id034
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
  tier: declared
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
    mcp: &id035
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id036
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.8
    band: exemplar
    in_catalog: true
    kin_score: 74.8
    mcp: &id037
      source: https://github.com/atlassian/trello-mcp-server
      status: verified
    slug: trello
    status: profiled
    tags: &id038
    - Collaboration
    - Kanban
    - Project Management
    - Task Management
    url: /providers/trello/
  layer: common
  name: Trello
  provider: trello
  says: lists Trello as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: social-networks-community
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id039
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id040
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: common
  name: Twitter
  provider: x
  says: lists Twitter as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
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
    agent_readiness: 60.0
    band: exemplar
    in_catalog: true
    kin_score: 87.1
    mcp: &id041
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id042
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: common
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
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
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id043
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id044
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.3
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id045
      status: none
    slug: zoho-crm
    status: profiled
    tags: &id046
    - CRM
    - Lead Management
    - Marketing Automation
    - Sales
    url: /providers/zoho-crm/
  layer: common
  name: Zoho CRM
  provider: zoho-crm
  says: lists Zoho CRM as an integration
  source: https://planningpod.com/help-center/integrating-with-other-applications-via-zapier
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/wedding-event-planning/planning-pod/
providers:
- agent_band: agent-ready
  agent_readiness: 55.3
  band: exemplar
  in_catalog: true
  kin_score: 72.5
  mcp: *id001
  name: Asana
  slug: asana
  status: profiled
  tags: *id002
  url: /providers/asana/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id003
  name: AWeber
  slug: aweber
  status: profiled
  tags: *id004
  url: /providers/aweber/
- agent_band: agent-aware
  agent_readiness: 24.9
  band: developing
  in_catalog: true
  kin_score: 49.0
  mcp: *id005
  name: Basecamp
  slug: basecamp
  status: profiled
  tags: *id006
  url: /providers/basecamp/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id007
  name: Constant Contact
  slug: constant-contact
  status: profiled
  tags: *id008
  url: /providers/constant-contact/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: developing
  in_catalog: true
  kin_score: 41.6
  mcp: *id009
  name: Eventbrite
  slug: eventbrite
  status: profiled
  tags: *id010
  url: /providers/eventbrite/
- agent_band: agent-aware
  agent_readiness: 28.0
  band: developing
  in_catalog: true
  kin_score: 53.0
  mcp: *id011
  name: Evernote
  slug: evernote
  status: profiled
  tags: *id012
  url: /providers/evernote/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id013
  name: Facebook Pages
  slug: facebook
  status: profiled
  tags: *id014
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 19.7
  band: thin
  in_catalog: true
  kin_score: 31.0
  mcp: *id015
  name: Freshbooks
  slug: freshbooks
  status: profiled
  tags: *id016
  url: /providers/freshbooks/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id017
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id018
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id019
  name: Google Calendar/Contacts
  slug: google-calendar
  status: profiled
  tags: *id020
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id021
  name: Google Drive/Docs/Sheets
  slug: google-drive
  status: profiled
  tags: *id022
  url: /providers/google-drive/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id023
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id024
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 44.5
  band: strong
  in_catalog: true
  kin_score: 65.0
  mcp: *id025
  name: Infusionsoft
  slug: keap
  status: profiled
  tags: *id026
  url: /providers/keap/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id027
  name: MailChimp
  slug: mailchimp
  status: profiled
  tags: *id028
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: strong
  in_catalog: true
  kin_score: 55.3
  mcp: *id029
  name: Pipedrive
  slug: pipedrive
  status: profiled
  tags: *id030
  url: /providers/pipedrive/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id031
  name: Quickbooks
  slug: quickbooks
  status: profiled
  tags: *id032
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id033
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id034
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id035
  name: Slack
  slug: slack
  status: profiled
  tags: *id036
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id037
  name: Trello
  slug: trello
  status: profiled
  tags: *id038
  url: /providers/trello/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id039
  name: Twitter
  slug: x
  status: profiled
  tags: *id040
  url: /providers/x/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id041
  name: Xero
  slug: xero
  status: profiled
  tags: *id042
  url: /providers/xero/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id043
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id044
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 43.3
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id045
  name: Zoho CRM
  slug: zoho-crm
  status: profiled
  tags: *id046
  url: /providers/zoho-crm/
siblings:
- name: Aisle Planner
  rows: 6
  url: /applications/wedding-event-planning/aisle-planner/
- name: HoneyBook
  rows: 40
  url: /applications/wedding-event-planning/honeybook/
- name: Joy
  rows: 12
  url: /applications/wedding-event-planning/joy/
- name: Rallly
  rows: 16
  url: /applications/wedding-event-planning/rallly/
- name: The Knot Wedding Planner
  rows: 0
  url: /applications/wedding-event-planning/the-knot-wedding-planner/
- name: WeddingShare
  rows: 2
  url: /applications/wedding-event-planning/weddingshare/
sitemap: true
title: 'Planning Pod: Wedding & Event Planning reference app'
---
