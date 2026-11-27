---
app: Gatus
app_slug: gatus
app_url: https://github.com/TwiN/gatus
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.30
  key: incident-response-management
  layer: domain
  name: Incident Response Management
  providers:
  - ilert
  - incident.io
  - Opsgenie
  - PagerDuty
  - SIGNL4
  - Squadcast
  url: /capabilities/incident-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: domain
  name: Internal Communications Management
  providers:
  - Discord
  - Google Chat
  - LINE
  - Mattermost
  - Microsoft Teams
  - Rocket.Chat
  - Signal
  - Slack
  - Telegram
  - Webex
  - Zulip
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: domain
  name: Observability Management
  providers:
  - Datadog
  - New Relic
  - Splunk
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200
  key: AE-200
  layer: common
  name: Home, Device & Consumer IoT
  providers:
  - Home Assistant
  url: /capabilities/home-device-consumer-iot/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Gotify
  - ntfy
  - Pushover
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - MessageBird
  - Plivo
  - Twilio
  - Vonage
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-4200
  key: software-product-engineering-management
  layer: common
  name: Software Product Engineering Management
  providers:
  - ClickUp
  - Gitea
  - GitHub
  - GitLab
  url: /capabilities/software-product-engineering-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES
  - Resend
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - IFTTT
  - n8n
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: observability-monitoring
  name: Observability, Monitoring & Status Pages
  url: /applications/observability-monitoring/
counts:
  declared: 0
  observed: 38
credits: []
evidence:
- route: source code
  url: https://github.com/TwiN/gatus/tree/master/alerting/provider
integrations:
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
    agent_readiness: 38.0
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id001
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
  layer: common
  name: Amazon SES
  provider: amazon-ses
  says: ships the Amazon SES SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 55.8
    band: exemplar
    in_catalog: true
    kin_score: 72.6
    mcp: &id003
      source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
      status: verified
    slug: clickup
    status: profiled
    tags: &id004
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/clickup/
  layer: common
  name: ClickUp
  provider: clickup
  says: ships the ClickUp SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.6
    band: exemplar
    in_catalog: true
    kin_score: 80.0
    mcp: &id005
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id006
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: domain
  name: Datadog
  provider: datadog
  says: ships the Datadog SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id007
      status: none
    slug: discord
    status: profiled
    tags: &id008
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: domain
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id009
      source: https://gitea.com/gitea/gitea-mcp
      status: verified
    slug: gitea
    status: profiled
    tags: &id010
    - CI/CD
    - DevOps
    - Gitea
    - Version Control
    url: /providers/gitea/
  layer: common
  name: Gitea
  provider: gitea
  says: ships the Gitea SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id011
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id012
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id013
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id014
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: common
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.0
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id015
      source: https://github.com/google/mcp
      status: verified
    slug: google-chat
    status: profiled
    tags: &id016
    - Chat
    - Collaboration
    - Google
    - Google Workspace
    url: /providers/google-chat/
  layer: domain
  name: Google Chat
  provider: google-chat
  says: ships the Google Chat SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.9
    mcp: &id017
      source: https://gotify.net/docs/mcp
      status: verified
    slug: gotify
    status: profiled
    tags: &id018
    - Messaging
    - Notification
    - Open Source
    - Self-Hosted
    url: /providers/gotify/
  layer: common
  name: Gotify
  provider: gotify
  says: ships the Gotify SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200
    key: AE-200
    name: Home, Device & Consumer IoT
    url: /capabilities/home-device-consumer-iot/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.6
    band: thin
    in_catalog: true
    kin_score: 34.5
    mcp: &id019
      source: https://www.home-assistant.io/integrations/mcp_server/
      status: verified
    slug: home-assistant
    status: profiled
    tags: &id020
    - Community
    - Home Automation
    - IoT
    - Open Source
    url: /providers/home-assistant/
  layer: common
  name: Home Assistant
  provider: home-assistant
  says: ships the Home Assistant SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
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
    agent_readiness: 42.4
    band: emerging
    in_catalog: true
    kin_score: 24.1
    mcp: &id021
      source: https://github.com/IFTTT/ifttt-plugins
      status: verified
    slug: ifttt
    status: profiled
    tags: &id022
    - Automation
    - No-Code
    - Webhook
    - iPaaS
    url: /providers/ifttt/
  layer: common
  name: IFTTT
  provider: ifttt
  says: ships the IFTTT SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.7
    band: thin
    in_catalog: true
    kin_score: 37.4
    mcp: &id023
      source: https://github.com/iLert/mcp-ilert
      status: verified
    slug: ilert
    status: profiled
    tags: &id024
    - Alert Routing
    - Escalation Policies
    - Incident Management
    - On-Call Alerting
    url: /providers/ilert/
  layer: domain
  name: ilert
  provider: ilert
  says: ships the ilert SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 49.9
    band: thin
    in_catalog: true
    kin_score: 34.1
    mcp: &id025
      source: https://help.incident.io/
      status: documented
    slug: incident-io
    status: profiled
    tags: &id026
    - AIOps
    - Incident Management
    - Incident Response
    - Monitoring
    url: /providers/incident-io/
  layer: domain
  name: incident.io
  provider: incident-io
  says: ships the incident.io SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 47.0
    band: exemplar
    in_catalog: true
    kin_score: 71.3
    mcp: &id027
      source: https://github.com/line/line-bot-mcp-server
      status: verified
    slug: line
    status: profiled
    tags: &id028
    - Chatbots
    - Messaging
    - Mini Apps
    - Social Login
    url: /providers/line/
  layer: domain
  name: LINE
  provider: line
  says: ships the LINE SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.2
    band: thin
    in_catalog: true
    kin_score: 37.0
    mcp: &id029
      source: https://github.com/mattermost/mmctl-mcp
      status: verified
    slug: mattermost
    status: profiled
    tags: &id030
    - Collaboration
    - Messaging
    - Open Source
    - Team Chat
    url: /providers/mattermost/
  layer: domain
  name: Mattermost
  provider: mattermost
  says: ships the Mattermost SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
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
    agent_readiness: 70.3
    band: developing
    in_catalog: true
    kin_score: 50.0
    mcp: &id031
      source: https://github.com/messagebird/bird-ai
      status: verified
    slug: bird
    status: profiled
    tags: &id032
    - Communications
    - Email
    - SMS
    - WhatsApp
    url: /providers/bird/
  layer: common
  name: MessageBird
  provider: bird
  says: ships the MessageBird SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id033
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id034
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: ships the Microsoft Teams SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
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
    agent_readiness: 35.7
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id035
      source: https://docs.n8n.io/advanced-ai/accessing-n8n-mcp-server/
      status: verified
    slug: n8n
    status: profiled
    tags: &id036
    - Agents
    - Artificial Intelligence
    - Integration
    - Workflows
    url: /providers/n8n/
  layer: common
  name: n8n
  provider: n8n
  says: ships the n8n SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id037
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id038
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: domain
  name: New Relic
  provider: new-relic
  says: ships the New Relic SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.5
    mcp: &id039
      status: none
    slug: ntfy
    status: profiled
    tags: &id040
    - Notification
    - Open Source
    - Pub/Sub
    - Self-Hosted
    url: /providers/ntfy/
  layer: common
  name: ntfy
  provider: ntfy
  says: ships the ntfy SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.5
    band: developing
    in_catalog: true
    kin_score: 48.6
    mcp: &id041
      status: none
    slug: opsgenie
    status: profiled
    tags: &id042
    - Alerts
    - Incident Management
    - Monitoring
    - On-Call
    url: /providers/opsgenie/
  layer: domain
  name: Opsgenie
  provider: opsgenie
  says: ships the Opsgenie SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.4
    band: developing
    in_catalog: true
    kin_score: 52.1
    mcp: &id043
      source: https://github.com/PagerDuty/pagerduty-mcp-server
      status: verified
    slug: pagerduty
    status: profiled
    tags: &id044
    - Alerting
    - DevOps
    - Incident Management
    - On-Call Management
    url: /providers/pagerduty/
  layer: domain
  name: PagerDuty
  provider: pagerduty
  says: ships the PagerDuty SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
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
    agent_band: agent-aware
    agent_readiness: 25.8
    band: developing
    in_catalog: true
    kin_score: 39.3
    mcp: &id045
      source: https://github.com/plivo/mcp
      status: verified
    slug: plivo
    status: profiled
    tags: &id046
    - CPaaS
    - Communications
    - SMS
    - Voice
    url: /providers/plivo/
  layer: common
  name: Plivo
  provider: plivo
  says: ships the Plivo SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
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
    agent_band: agent-aware
    agent_readiness: 21.6
    band: thin
    in_catalog: true
    kin_score: 28.1
    mcp: &id047
      status: none
    slug: pushover
    status: profiled
    tags: &id048
    - Alerts
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushover/
  layer: common
  name: Pushover
  provider: pushover
  says: ships the Pushover SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
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
    agent_readiness: 49.8
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id049
      source: https://resend.com/docs/mcp-server
      status: verified
    slug: resend
    status: profiled
    tags: &id050
    - Developer Tools
    - Email
    - Marketing Email
    - Transactional Email
    url: /providers/resend/
  layer: common
  name: Resend
  provider: resend
  says: ships the Resend SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.9
    mcp: &id051
      source: https://docs.rocket.chat/docs/mcp-server
      status: verified
    slug: rocketchat
    status: profiled
    tags: &id052
    - Collaboration
    - Communications
    - Company
    - Open Source
    url: /providers/rocketchat/
  layer: domain
  name: Rocket.Chat
  provider: rocketchat
  says: ships the Rocket.Chat SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
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
    mcp: &id053
      status: none
    slug: sendgrid
    status: profiled
    tags: &id054
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.3
    band: developing
    in_catalog: true
    kin_score: 43.2
    mcp: &id055
      status: none
    slug: signal
    status: profiled
    tags: &id056
    - Cryptography
    - Encryption
    - Messaging
    - Security
    url: /providers/signal/
  layer: domain
  name: Signal
  provider: signal
  says: ships the Signal SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.1
    band: thin
    in_catalog: true
    kin_score: 36.7
    mcp: &id057
      status: none
    slug: signl4
    status: profiled
    tags: &id058
    - Alerting
    - Incident Management
    - Mobile Alerts
    - On-Call
    url: /providers/signl4/
  layer: domain
  name: SIGNL4
  provider: signl4
  says: ships the SIGNL4 SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id059
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id060
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.4
    band: strong
    in_catalog: true
    kin_score: 63.1
    mcp: &id061
      status: none
    slug: splunk
    status: profiled
    tags: &id062
    - Analytics
    - Data Analysis
    - Logging
    - Machine Data
    url: /providers/splunk/
  layer: domain
  name: Splunk
  provider: splunk
  says: ships the Splunk SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 26.6
    mcp: &id063
      status: none
    slug: squadcast
    status: profiled
    tags: &id064
    - DevOps
    - Incident Response
    - On-Call Management
    - SRE
    url: /providers/squadcast/
  layer: domain
  name: Squadcast
  provider: squadcast
  says: ships the Squadcast SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id065
      status: none
    slug: telegram
    status: profiled
    tags: &id066
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: domain
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
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
    mcp: &id067
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id068
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
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
    mcp: &id069
      source: https://github.com/Vonage/vonage-mcp-server-documentation
      status: verified
    slug: vonage
    status: profiled
    tags: &id070
    - Communications
    - Messaging
    - Telecommunications
    - Video Conferencing
    url: /providers/vonage/
  layer: common
  name: Vonage
  provider: vonage
  says: ships the Vonage SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 61.8
    band: strong
    in_catalog: true
    kin_score: 66.1
    mcp: &id071
      source: https://github.com/WebexSamples/webex-messaging-mcp-server
      status: verified
    slug: webex
    status: profiled
    tags: &id072
    - Calling
    - Collaboration
    - Communications
    - Enterprise
    url: /providers/webex/
  layer: domain
  name: Webex
  provider: webex
  says: ships the Webex SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
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
    mcp: &id073
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id074
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: ships the Zapier SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.1
    band: thin
    in_catalog: true
    kin_score: 33.1
    mcp: &id075
      source: https://github.com/zulip/zulipmcp
      status: verified
    slug: zulip
    status: profiled
    tags: &id076
    - Collaboration
    - Messaging
    - Team Chat
    - Webhook
    url: /providers/zulip/
  layer: domain
  name: Zulip
  provider: zulip
  says: ships the Zulip SDK or integration code
  source: https://github.com/TwiN/gatus/tree/master/alerting/provider
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/observability-monitoring/gatus/
providers:
- agent_band: agent-ready
  agent_readiness: 38.0
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id001
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id002
  url: /providers/amazon-ses/
- agent_band: agent-ready
  agent_readiness: 55.8
  band: exemplar
  in_catalog: true
  kin_score: 72.6
  mcp: *id003
  name: ClickUp
  slug: clickup
  status: profiled
  tags: *id004
  url: /providers/clickup/
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id005
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id006
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id007
  name: Discord
  slug: discord
  status: profiled
  tags: *id008
  url: /providers/discord/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id009
  name: Gitea
  slug: gitea
  status: profiled
  tags: *id010
  url: /providers/gitea/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id011
  name: GitHub
  slug: github
  status: profiled
  tags: *id012
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id013
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id014
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 41.0
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id015
  name: Google Chat
  slug: google-chat
  status: profiled
  tags: *id016
  url: /providers/google-chat/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.9
  mcp: *id017
  name: Gotify
  slug: gotify
  status: profiled
  tags: *id018
  url: /providers/gotify/
- agent_band: agent-aware
  agent_readiness: 5.6
  band: thin
  in_catalog: true
  kin_score: 34.5
  mcp: *id019
  name: Home Assistant
  slug: home-assistant
  status: profiled
  tags: *id020
  url: /providers/home-assistant/
- agent_band: agent-ready
  agent_readiness: 42.4
  band: emerging
  in_catalog: true
  kin_score: 24.1
  mcp: *id021
  name: IFTTT
  slug: ifttt
  status: profiled
  tags: *id022
  url: /providers/ifttt/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: thin
  in_catalog: true
  kin_score: 37.4
  mcp: *id023
  name: ilert
  slug: ilert
  status: profiled
  tags: *id024
  url: /providers/ilert/
- agent_band: agent-native
  agent_readiness: 49.9
  band: thin
  in_catalog: true
  kin_score: 34.1
  mcp: *id025
  name: incident.io
  slug: incident-io
  status: profiled
  tags: *id026
  url: /providers/incident-io/
- agent_band: agent-native
  agent_readiness: 47.0
  band: exemplar
  in_catalog: true
  kin_score: 71.3
  mcp: *id027
  name: LINE
  slug: line
  status: profiled
  tags: *id028
  url: /providers/line/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: thin
  in_catalog: true
  kin_score: 37.0
  mcp: *id029
  name: Mattermost
  slug: mattermost
  status: profiled
  tags: *id030
  url: /providers/mattermost/
- agent_band: agent-native
  agent_readiness: 70.3
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id031
  name: MessageBird
  slug: bird
  status: profiled
  tags: *id032
  url: /providers/bird/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id033
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id034
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 35.7
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id035
  name: n8n
  slug: n8n
  status: profiled
  tags: *id036
  url: /providers/n8n/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id037
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id038
  url: /providers/new-relic/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id039
  name: ntfy
  slug: ntfy
  status: profiled
  tags: *id040
  url: /providers/ntfy/
- agent_band: agent-aware
  agent_readiness: 26.5
  band: developing
  in_catalog: true
  kin_score: 48.6
  mcp: *id041
  name: Opsgenie
  slug: opsgenie
  status: profiled
  tags: *id042
  url: /providers/opsgenie/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id043
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id044
  url: /providers/pagerduty/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: developing
  in_catalog: true
  kin_score: 39.3
  mcp: *id045
  name: Plivo
  slug: plivo
  status: profiled
  tags: *id046
  url: /providers/plivo/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id047
  name: Pushover
  slug: pushover
  status: profiled
  tags: *id048
  url: /providers/pushover/
- agent_band: agent-ready
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id049
  name: Resend
  slug: resend
  status: profiled
  tags: *id050
  url: /providers/resend/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.9
  mcp: *id051
  name: Rocket.Chat
  slug: rocketchat
  status: profiled
  tags: *id052
  url: /providers/rocketchat/
- agent_band: agent-ready
  agent_readiness: 40.7
  band: exemplar
  in_catalog: true
  kin_score: 84.0
  mcp: *id053
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id054
  url: /providers/sendgrid/
- agent_band: agent-aware
  agent_readiness: 20.3
  band: developing
  in_catalog: true
  kin_score: 43.2
  mcp: *id055
  name: Signal
  slug: signal
  status: profiled
  tags: *id056
  url: /providers/signal/
- agent_band: agent-aware
  agent_readiness: 18.1
  band: thin
  in_catalog: true
  kin_score: 36.7
  mcp: *id057
  name: SIGNL4
  slug: signl4
  status: profiled
  tags: *id058
  url: /providers/signl4/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id059
  name: Slack
  slug: slack
  status: profiled
  tags: *id060
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id061
  name: Splunk
  slug: splunk
  status: profiled
  tags: *id062
  url: /providers/splunk/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 26.6
  mcp: *id063
  name: Squadcast
  slug: squadcast
  status: profiled
  tags: *id064
  url: /providers/squadcast/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id065
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id066
  url: /providers/telegram/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id067
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id068
  url: /providers/twilio/
- agent_band: agent-ready
  agent_readiness: 40.0
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id069
  name: Vonage
  slug: vonage
  status: profiled
  tags: *id070
  url: /providers/vonage/
- agent_band: agent-ready
  agent_readiness: 61.8
  band: strong
  in_catalog: true
  kin_score: 66.1
  mcp: *id071
  name: Webex
  slug: webex
  status: profiled
  tags: *id072
  url: /providers/webex/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id073
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id074
  url: /providers/zapier/
- agent_band: agent-aware
  agent_readiness: 25.1
  band: thin
  in_catalog: true
  kin_score: 33.1
  mcp: *id075
  name: Zulip
  slug: zulip
  status: profiled
  tags: *id076
  url: /providers/zulip/
siblings:
- name: Datadog
  rows: 21
  url: /applications/observability-monitoring/datadog/
- name: Grafana
  rows: 30
  url: /applications/observability-monitoring/grafana/
- name: Netdata
  rows: 22
  url: /applications/observability-monitoring/netdata/
- name: Prometheus Alertmanager
  rows: 15
  url: /applications/observability-monitoring/prometheus-alertmanager/
- name: Sentry
  rows: 31
  url: /applications/observability-monitoring/sentry/
- name: Uptime Kuma
  rows: 50
  url: /applications/observability-monitoring/uptime-kuma/
sitemap: true
title: 'Gatus: Observability, Monitoring & Status Pages reference app'
---
