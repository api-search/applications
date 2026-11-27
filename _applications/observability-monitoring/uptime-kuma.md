---
app: Uptime Kuma
app_slug: uptime-kuma
app_url: https://github.com/louislam/uptime-kuma
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-600.30
  key: it-service-management
  layer: domain
  name: IT Service Management
  providers:
  - HaloPSA
  url: /capabilities/it-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.30
  key: incident-response-management
  layer: domain
  name: Incident Response Management
  providers:
  - Flashduty
  - GoAlert
  - Grafana OnCall
  - Jira Service Management
  - Keep
  - Opsgenie
  - PagerDuty
  - PagerTree
  - SIGNL4
  - Splunk On-Call
  - Squadcast
  url: /capabilities/incident-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: domain
  name: Internal Communications Management
  providers:
  - Bitrix24
  - DingTalk
  - Discord
  - Feishu
  - Google Chat
  - KOOK
  - LINE
  - Mattermost
  - Microsoft Teams
  - Nextcloud Talk
  - Pumble
  - Rocket.Chat
  - Signal
  - Slack
  - Telegram
  - Threema
  - VK
  - WeCom
  - Zoho Cliq
  url: /capabilities/internal-communications-management/
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
  - Pushbullet
  - Pushover
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - 46elks
  - Aliyun SMS
  - ClickSend SMS
  - Octopush
  - Plivo
  - seven.io
  - SMSEagle
  - Telnyx
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-4200
  key: software-product-engineering-management
  layer: common
  name: Software Product Engineering Management
  providers:
  - ClickUp
  url: /capabilities/software-product-engineering-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: common
  name: Spreadsheets & No-Code Databases
  providers:
  - Google Sheets
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Brevo
  - Resend
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
category:
  id: observability-monitoring
  name: Observability, Monitoring & Status Pages
  url: /applications/observability-monitoring/
counts:
  declared: 0
  observed: 50
credits: []
evidence:
- route: source code
  url: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_band: agent-aware
    agent_readiness: 21.3
    band: thin
    in_catalog: true
    kin_score: 26.4
    mcp: &id001
      status: none
    slug: 46elks
    status: profiled
    tags: &id002
    - CPaaS
    - MMS
    - SMS
    - Voice
    url: /providers/46elks/
  layer: common
  name: 46elks
  provider: 46elks
  says: ships the 46elks SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id003
      source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
      status: verified
    slug: alibabacloud
    status: profiled
    tags: &id004
    - Company
    url: /providers/alibabacloud/
  layer: common
  name: Aliyun SMS
  provider: alibabacloud
  says: ships the Aliyun SMS SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_readiness: 47.5
    band: developing
    in_catalog: true
    kin_score: 41.7
    mcp: &id005
      source: https://github.com/bitrix24/mcp-rest-doc
      status: verified
    slug: bitrix24
    status: profiled
    tags: &id006
    - CRM
    - Collaboration
    - Project Management
    - Task
    url: /providers/bitrix24/
  layer: domain
  name: Bitrix24
  provider: bitrix24
  says: ships the Bitrix24 SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_readiness: 56.4
    band: exemplar
    in_catalog: true
    kin_score: 81.3
    mcp: &id007
      source: https://developers.brevo.com/docs/mcp-protocol
      status: verified
    slug: brevo
    status: profiled
    tags: &id008
    - Email Marketing
    - Marketing
    - Marketing Automation
    - Transactional Email
    url: /providers/brevo/
  layer: common
  name: Brevo
  provider: brevo
  says: ships the Brevo SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_readiness: 20.9
    band: thin
    in_catalog: true
    kin_score: 28.2
    mcp: &id009
      source: https://github.com/ClickSend/clicksend-mcp-server
      status: verified
    slug: clicksend
    status: profiled
    tags: &id010
    - Communications
    - MMS
    - SMS
    - Voice
    url: /providers/clicksend/
  layer: common
  name: ClickSend SMS
  provider: clicksend
  says: ships the ClickSend SMS SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id011
      source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
      status: verified
    slug: clickup
    status: profiled
    tags: &id012
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/clickup/
  layer: common
  name: ClickUp
  provider: clickup
  says: ships the ClickUp SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    kin_score: 7.1
    mcp: &id013
      source: https://github.com/open-dingtalk/dingtalk-mcp
      status: verified
    slug: dingtalk
    status: profiled
    tags: &id014
    - Collaboration
    - Communications
    - Company
    - Enterprise
    url: /providers/dingtalk/
  layer: domain
  name: DingTalk
  provider: dingtalk
  says: ships the DingTalk SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id015
      status: none
    slug: discord
    status: profiled
    tags: &id016
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: domain
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id017
      status: unchecked
    slug: feishu
    status: queued for profiling
    tags: &id018 []
    url: null
  layer: domain
  name: Feishu
  provider: feishu
  says: ships the Feishu SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_readiness: 17.5
    band: developing
    in_catalog: true
    kin_score: 42.5
    mcp: &id019
      source: https://github.com/flashcatcloud/flashduty-mcp-server
      status: verified
    slug: flashduty
    status: profiled
    tags: &id020
    - Artificial Intelligence
    - Incident Response
    - Monitoring
    - On-Call
    url: /providers/flashduty/
  layer: domain
  name: Flashduty
  provider: flashduty
  says: ships the Flashduty SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.1
    mcp: &id021
      status: unknown
    slug: goalert
    status: profiled
    tags: &id022
    - Alerting
    - Automation
    - Incident Management
    - On-Call
    url: /providers/goalert/
  layer: domain
  name: GoAlert
  provider: goalert
  says: ships the GoAlert SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id023
      source: https://github.com/google/mcp
      status: verified
    slug: google-chat
    status: profiled
    tags: &id024
    - Chat
    - Collaboration
    - Google
    - Google Workspace
    url: /providers/google-chat/
  layer: domain
  name: Google Chat
  provider: google-chat
  says: ships the Google Chat SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id025
      status: none
    slug: google-sheets
    status: profiled
    tags: &id026
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
  layer: common
  name: Google Sheets
  provider: google-sheets
  says: ships the Google Sheets SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id027
      source: https://gotify.net/docs/mcp
      status: verified
    slug: gotify
    status: profiled
    tags: &id028
    - Messaging
    - Notification
    - Open Source
    - Self-Hosted
    url: /providers/gotify/
  layer: common
  name: Gotify
  provider: gotify
  says: ships the Gotify SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_readiness: 27.6
    band: strong
    in_catalog: true
    kin_score: 66.0
    mcp: &id029
      source: https://github.com/grafana/mcp-grafana
      status: verified
    slug: grafana-com
    status: profiled
    tags: &id030
    - Dashboards
    - Logs
    - Monitoring
    - Observability
    url: /providers/grafana-com/
  layer: domain
  name: Grafana OnCall
  provider: grafana-com
  says: ships the Grafana OnCall SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.30
    key: it-service-management
    name: IT Service Management
    url: /capabilities/it-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.7
    mcp: &id031
      status: unknown
    slug: halopsa
    status: profiled
    tags: &id032
    - Company
    - Customer Service Management
    - ITSM
    - Workflow Automation
    url: /providers/halopsa/
  layer: domain
  name: HaloPSA
  provider: halopsa
  says: ships the HaloPSA SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id033
      source: https://www.home-assistant.io/integrations/mcp_server/
      status: verified
    slug: home-assistant
    status: profiled
    tags: &id034
    - Community
    - Home Automation
    - IoT
    - Open Source
    url: /providers/home-assistant/
  layer: common
  name: Home Assistant
  provider: home-assistant
  says: ships the Home Assistant SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id035
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id036
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: domain
  name: Jira Service Management
  provider: jira
  says: ships the Jira Service Management SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_readiness: 22.8
    band: thin
    in_catalog: true
    kin_score: 29.6
    mcp: &id037
      status: none
    slug: keep
    status: profiled
    tags: &id038
    - AIOps
    - Alerting
    - Incident Management
    - Observability
    url: /providers/keep/
  layer: domain
  name: Keep
  provider: keep
  says: ships the Keep SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_readiness: 22.8
    band: thin
    in_catalog: true
    kin_score: 33.7
    mcp: &id039
      status: none
    slug: kook
    status: profiled
    tags: &id040
    - Community
    - Company
    - Gaming
    - Voice Communication
    url: /providers/kook/
  layer: domain
  name: KOOK
  provider: kook
  says: ships the KOOK SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id041
      source: https://github.com/line/line-bot-mcp-server
      status: verified
    slug: line
    status: profiled
    tags: &id042
    - Chatbots
    - Messaging
    - Mini Apps
    - Social Login
    url: /providers/line/
  layer: domain
  name: LINE
  provider: line
  says: ships the LINE SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id043
      source: https://github.com/mattermost/mmctl-mcp
      status: verified
    slug: mattermost
    status: profiled
    tags: &id044
    - Collaboration
    - Messaging
    - Open Source
    - Team Chat
    url: /providers/mattermost/
  layer: domain
  name: Mattermost
  provider: mattermost
  says: ships the Mattermost SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id045
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id046
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: ships the Microsoft Teams SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 32.7
    mcp: &id047
      status: none
    slug: nextcloud
    status: profiled
    tags: &id048
    - Collaboration
    - File Sharing
    - File Sync
    - Self-Hosted
    url: /providers/nextcloud/
  layer: domain
  name: Nextcloud Talk
  provider: nextcloud
  says: ships the Nextcloud Talk SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id049
      status: none
    slug: ntfy
    status: profiled
    tags: &id050
    - Notification
    - Open Source
    - Pub/Sub
    - Self-Hosted
    url: /providers/ntfy/
  layer: common
  name: ntfy
  provider: ntfy
  says: ships the ntfy SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.5
    mcp: &id051
      status: none
    slug: octopush
    status: profiled
    tags: &id052
    - Communications
    - Email
    - Marketing
    - SMS
    url: /providers/octopush/
  layer: common
  name: Octopush
  provider: octopush
  says: ships the Octopush SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id053
      status: none
    slug: opsgenie
    status: profiled
    tags: &id054
    - Alerts
    - Incident Management
    - Monitoring
    - On-Call
    url: /providers/opsgenie/
  layer: domain
  name: Opsgenie
  provider: opsgenie
  says: ships the Opsgenie SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id055
      source: https://github.com/PagerDuty/pagerduty-mcp-server
      status: verified
    slug: pagerduty
    status: profiled
    tags: &id056
    - Alerting
    - DevOps
    - Incident Management
    - On-Call Management
    url: /providers/pagerduty/
  layer: domain
  name: PagerDuty
  provider: pagerduty
  says: ships the PagerDuty SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 28.7
    mcp: &id057
      source: https://github.com/PagerTree/pagertree-mcp-server
      status: verified
    slug: pagertree
    status: profiled
    tags: &id058
    - Company
    url: /providers/pagertree/
  layer: domain
  name: PagerTree
  provider: pagertree
  says: ships the PagerTree SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id059
      source: https://github.com/plivo/mcp
      status: verified
    slug: plivo
    status: profiled
    tags: &id060
    - CPaaS
    - Communications
    - SMS
    - Voice
    url: /providers/plivo/
  layer: common
  name: Plivo
  provider: plivo
  says: ships the Plivo SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    band: emerging
    in_catalog: true
    kin_score: 23.1
    mcp: &id061
      source: https://pumble.com/help/integrations/automation-workflow-integrations/how-to-use-the-pumble-mcp-server/
      status: verified
    slug: pumble
    status: profiled
    tags: &id062
    - Company
    url: /providers/pumble/
  layer: domain
  name: Pumble
  provider: pumble
  says: ships the Pumble SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 30.2
    mcp: &id063
      status: none
    slug: pushbullet
    status: profiled
    tags: &id064
    - Device Sync
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushbullet/
  layer: common
  name: Pushbullet
  provider: pushbullet
  says: ships the Pushbullet SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id065
      status: none
    slug: pushover
    status: profiled
    tags: &id066
    - Alerts
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushover/
  layer: common
  name: Pushover
  provider: pushover
  says: ships the Pushover SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id067
      source: https://resend.com/docs/mcp-server
      status: verified
    slug: resend
    status: profiled
    tags: &id068
    - Developer Tools
    - Email
    - Marketing Email
    - Transactional Email
    url: /providers/resend/
  layer: common
  name: Resend
  provider: resend
  says: ships the Resend SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id069
      source: https://docs.rocket.chat/docs/mcp-server
      status: verified
    slug: rocketchat
    status: profiled
    tags: &id070
    - Collaboration
    - Communications
    - Company
    - Open Source
    url: /providers/rocketchat/
  layer: domain
  name: Rocket.Chat
  provider: rocketchat
  says: ships the Rocket.Chat SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id071
      status: none
    slug: sendgrid
    status: profiled
    tags: &id072
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_readiness: 23.0
    band: developing
    in_catalog: true
    kin_score: 47.8
    mcp: &id073
      source: https://github.com/seven-io/seven-mcp
      status: verified
    slug: seven-io
    status: profiled
    tags: &id074
    - Company
    - Messaging
    - SMS
    - Voice
    url: /providers/seven-io/
  layer: common
  name: seven.io
  provider: seven-io
  says: ships the seven.io SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id075
      status: none
    slug: signal
    status: profiled
    tags: &id076
    - Cryptography
    - Encryption
    - Messaging
    - Security
    url: /providers/signal/
  layer: domain
  name: Signal
  provider: signal
  says: ships the Signal SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id077
      status: none
    slug: signl4
    status: profiled
    tags: &id078
    - Alerting
    - Incident Management
    - Mobile Alerts
    - On-Call
    url: /providers/signl4/
  layer: domain
  name: SIGNL4
  provider: signl4
  says: ships the SIGNL4 SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id079
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id080
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_band: human-only
    agent_readiness: 3.8
    band: thin
    in_catalog: true
    kin_score: 27.1
    mcp: &id081
      status: none
    slug: smseagle
    status: profiled
    tags: &id082
    - Alerting
    - Company
    - IoT
    - SMS
    url: /providers/smseagle/
  layer: common
  name: SMSEagle
  provider: smseagle
  says: ships the SMSEagle SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 18.1
    mcp: &id083
      status: none
    slug: victorops
    status: profiled
    tags: &id084
    - Alerting
    - DevOps
    - Incident Management
    - On-Call
    url: /providers/victorops/
  layer: domain
  name: Splunk On-Call
  provider: victorops
  says: ships the Splunk On-Call SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id085
      status: none
    slug: squadcast
    status: profiled
    tags: &id086
    - DevOps
    - Incident Response
    - On-Call Management
    - SRE
    url: /providers/squadcast/
  layer: domain
  name: Squadcast
  provider: squadcast
  says: ships the Squadcast SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id087
      status: none
    slug: telegram
    status: profiled
    tags: &id088
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: domain
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_readiness: 80.0
    band: exemplar
    in_catalog: true
    kin_score: 93.5
    mcp: &id089
      source: https://github.com/team-telnyx/telnyx-mcp-server
      status: verified
    slug: telnyx
    status: profiled
    tags: &id090
    - CPaaS
    - Communications
    - SMS
    - Voice
    url: /providers/telnyx/
  layer: common
  name: Telnyx
  provider: telnyx
  says: ships the Telnyx SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_readiness: 2.8
    band: thin
    in_catalog: true
    kin_score: 30.7
    mcp: &id091
      status: none
    slug: threema
    status: profiled
    tags: &id092
    - Company
    - Messaging
    - Privacy
    - Security
    url: /providers/threema/
  layer: domain
  name: Threema
  provider: threema
  says: ships the Threema SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    mcp: &id093
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id094
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    kin_score: 4.8
    mcp: &id095
      status: none
    slug: vk
    status: profiled
    tags: &id096
    - Public APIs
    - Social
    url: /providers/vk/
  layer: domain
  name: VK
  provider: vk
  says: ships the VK SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_readiness: 23.6
    band: developing
    in_catalog: true
    kin_score: 45.1
    mcp: &id097
      status: none
    slug: wechat
    status: profiled
    tags: &id098
    - Messaging
    - Mini Programs
    - Payments
    - Social
    url: /providers/wechat/
  layer: domain
  name: WeCom
  provider: wechat
  says: ships the WeCom SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
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
    agent_readiness: 34.9
    band: developing
    in_catalog: true
    kin_score: 46.7
    mcp: &id099
      source: https://www.zoho.com/mcp/
      status: verified
    slug: zoho-cliq
    status: profiled
    tags: &id100
    - Bots
    - Chat
    - Messaging
    - Team Collaboration
    url: /providers/zoho-cliq/
  layer: domain
  name: Zoho Cliq
  provider: zoho-cliq
  says: ships the Zoho Cliq SDK or integration code
  source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/observability-monitoring/uptime-kuma/
providers:
- agent_band: agent-aware
  agent_readiness: 21.3
  band: thin
  in_catalog: true
  kin_score: 26.4
  mcp: *id001
  name: 46elks
  slug: 46elks
  status: profiled
  tags: *id002
  url: /providers/46elks/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id003
  name: Aliyun SMS
  slug: alibabacloud
  status: profiled
  tags: *id004
  url: /providers/alibabacloud/
- agent_band: agent-ready
  agent_readiness: 47.5
  band: developing
  in_catalog: true
  kin_score: 41.7
  mcp: *id005
  name: Bitrix24
  slug: bitrix24
  status: profiled
  tags: *id006
  url: /providers/bitrix24/
- agent_band: agent-ready
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 81.3
  mcp: *id007
  name: Brevo
  slug: brevo
  status: profiled
  tags: *id008
  url: /providers/brevo/
- agent_band: agent-aware
  agent_readiness: 20.9
  band: thin
  in_catalog: true
  kin_score: 28.2
  mcp: *id009
  name: ClickSend SMS
  slug: clicksend
  status: profiled
  tags: *id010
  url: /providers/clicksend/
- agent_band: agent-ready
  agent_readiness: 55.8
  band: exemplar
  in_catalog: true
  kin_score: 72.6
  mcp: *id011
  name: ClickUp
  slug: clickup
  status: profiled
  tags: *id012
  url: /providers/clickup/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.1
  mcp: *id013
  name: DingTalk
  slug: dingtalk
  status: profiled
  tags: *id014
  url: /providers/dingtalk/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id015
  name: Discord
  slug: discord
  status: profiled
  tags: *id016
  url: /providers/discord/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id017
  name: Feishu
  slug: feishu
  status: queued for profiling
  tags: *id018
  url: null
- agent_band: agent-aware
  agent_readiness: 17.5
  band: developing
  in_catalog: true
  kin_score: 42.5
  mcp: *id019
  name: Flashduty
  slug: flashduty
  status: profiled
  tags: *id020
  url: /providers/flashduty/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.1
  mcp: *id021
  name: GoAlert
  slug: goalert
  status: profiled
  tags: *id022
  url: /providers/goalert/
- agent_band: agent-ready
  agent_readiness: 41.0
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id023
  name: Google Chat
  slug: google-chat
  status: profiled
  tags: *id024
  url: /providers/google-chat/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id025
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id026
  url: /providers/google-sheets/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.9
  mcp: *id027
  name: Gotify
  slug: gotify
  status: profiled
  tags: *id028
  url: /providers/gotify/
- agent_band: agent-aware
  agent_readiness: 27.6
  band: strong
  in_catalog: true
  kin_score: 66.0
  mcp: *id029
  name: Grafana OnCall
  slug: grafana-com
  status: profiled
  tags: *id030
  url: /providers/grafana-com/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.7
  mcp: *id031
  name: HaloPSA
  slug: halopsa
  status: profiled
  tags: *id032
  url: /providers/halopsa/
- agent_band: agent-aware
  agent_readiness: 5.6
  band: thin
  in_catalog: true
  kin_score: 34.5
  mcp: *id033
  name: Home Assistant
  slug: home-assistant
  status: profiled
  tags: *id034
  url: /providers/home-assistant/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id035
  name: Jira Service Management
  slug: jira
  status: profiled
  tags: *id036
  url: /providers/jira/
- agent_band: agent-aware
  agent_readiness: 22.8
  band: thin
  in_catalog: true
  kin_score: 29.6
  mcp: *id037
  name: Keep
  slug: keep
  status: profiled
  tags: *id038
  url: /providers/keep/
- agent_band: agent-aware
  agent_readiness: 22.8
  band: thin
  in_catalog: true
  kin_score: 33.7
  mcp: *id039
  name: KOOK
  slug: kook
  status: profiled
  tags: *id040
  url: /providers/kook/
- agent_band: agent-native
  agent_readiness: 47.0
  band: exemplar
  in_catalog: true
  kin_score: 71.3
  mcp: *id041
  name: LINE
  slug: line
  status: profiled
  tags: *id042
  url: /providers/line/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: thin
  in_catalog: true
  kin_score: 37.0
  mcp: *id043
  name: Mattermost
  slug: mattermost
  status: profiled
  tags: *id044
  url: /providers/mattermost/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id045
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id046
  url: /providers/microsoft-teams/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 32.7
  mcp: *id047
  name: Nextcloud Talk
  slug: nextcloud
  status: profiled
  tags: *id048
  url: /providers/nextcloud/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id049
  name: ntfy
  slug: ntfy
  status: profiled
  tags: *id050
  url: /providers/ntfy/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.5
  mcp: *id051
  name: Octopush
  slug: octopush
  status: profiled
  tags: *id052
  url: /providers/octopush/
- agent_band: agent-aware
  agent_readiness: 26.5
  band: developing
  in_catalog: true
  kin_score: 48.6
  mcp: *id053
  name: Opsgenie
  slug: opsgenie
  status: profiled
  tags: *id054
  url: /providers/opsgenie/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id055
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id056
  url: /providers/pagerduty/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 28.7
  mcp: *id057
  name: PagerTree
  slug: pagertree
  status: profiled
  tags: *id058
  url: /providers/pagertree/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: developing
  in_catalog: true
  kin_score: 39.3
  mcp: *id059
  name: Plivo
  slug: plivo
  status: profiled
  tags: *id060
  url: /providers/plivo/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 23.1
  mcp: *id061
  name: Pumble
  slug: pumble
  status: profiled
  tags: *id062
  url: /providers/pumble/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 30.2
  mcp: *id063
  name: Pushbullet
  slug: pushbullet
  status: profiled
  tags: *id064
  url: /providers/pushbullet/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id065
  name: Pushover
  slug: pushover
  status: profiled
  tags: *id066
  url: /providers/pushover/
- agent_band: agent-ready
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id067
  name: Resend
  slug: resend
  status: profiled
  tags: *id068
  url: /providers/resend/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.9
  mcp: *id069
  name: Rocket.Chat
  slug: rocketchat
  status: profiled
  tags: *id070
  url: /providers/rocketchat/
- agent_band: agent-ready
  agent_readiness: 40.7
  band: exemplar
  in_catalog: true
  kin_score: 84.0
  mcp: *id071
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id072
  url: /providers/sendgrid/
- agent_band: agent-aware
  agent_readiness: 23.0
  band: developing
  in_catalog: true
  kin_score: 47.8
  mcp: *id073
  name: seven.io
  slug: seven-io
  status: profiled
  tags: *id074
  url: /providers/seven-io/
- agent_band: agent-aware
  agent_readiness: 20.3
  band: developing
  in_catalog: true
  kin_score: 43.2
  mcp: *id075
  name: Signal
  slug: signal
  status: profiled
  tags: *id076
  url: /providers/signal/
- agent_band: agent-aware
  agent_readiness: 18.1
  band: thin
  in_catalog: true
  kin_score: 36.7
  mcp: *id077
  name: SIGNL4
  slug: signl4
  status: profiled
  tags: *id078
  url: /providers/signl4/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id079
  name: Slack
  slug: slack
  status: profiled
  tags: *id080
  url: /providers/slack/
- agent_band: human-only
  agent_readiness: 3.8
  band: thin
  in_catalog: true
  kin_score: 27.1
  mcp: *id081
  name: SMSEagle
  slug: smseagle
  status: profiled
  tags: *id082
  url: /providers/smseagle/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.1
  mcp: *id083
  name: Splunk On-Call
  slug: victorops
  status: profiled
  tags: *id084
  url: /providers/victorops/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 26.6
  mcp: *id085
  name: Squadcast
  slug: squadcast
  status: profiled
  tags: *id086
  url: /providers/squadcast/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id087
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id088
  url: /providers/telegram/
- agent_band: agent-native
  agent_readiness: 80.0
  band: exemplar
  in_catalog: true
  kin_score: 93.5
  mcp: *id089
  name: Telnyx
  slug: telnyx
  status: profiled
  tags: *id090
  url: /providers/telnyx/
- agent_band: human-only
  agent_readiness: 2.8
  band: thin
  in_catalog: true
  kin_score: 30.7
  mcp: *id091
  name: Threema
  slug: threema
  status: profiled
  tags: *id092
  url: /providers/threema/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id093
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id094
  url: /providers/twilio/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.8
  mcp: *id095
  name: VK
  slug: vk
  status: profiled
  tags: *id096
  url: /providers/vk/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: developing
  in_catalog: true
  kin_score: 45.1
  mcp: *id097
  name: WeCom
  slug: wechat
  status: profiled
  tags: *id098
  url: /providers/wechat/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id099
  name: Zoho Cliq
  slug: zoho-cliq
  status: profiled
  tags: *id100
  url: /providers/zoho-cliq/
siblings:
- name: Datadog
  rows: 21
  url: /applications/observability-monitoring/datadog/
- name: Gatus
  rows: 38
  url: /applications/observability-monitoring/gatus/
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
sitemap: true
title: 'Uptime Kuma: Observability, Monitoring & Status Pages reference app'
---
