---
access: understanding
agent_layer:
- app: Sentry
  finding: Seer (Sentry AI) hands fixes to coding agents (Cursor, Claude Code, GitHub Copilot) and pulls telemetry from Datadog and GCP MCP endpoints
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
- app: Grafana
  finding: ships hosted-LLM clients (openai-go, Bedrock runtime, Vertex AI) for its assistant features
  source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
  tier: observed
apps:
- anchor: uptime-kuma
  counts:
    declared: 0
    observed: 50
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
    layer: domain
    name: Zoho Cliq
    provider: zoho-cliq
    says: ships the Zoho Cliq SDK or integration code
    source: https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
    tier: observed
  kind: self-hosted
  name: Uptime Kuma
  page: /applications/observability-monitoring/uptime-kuma/
  slug: uptime-kuma
  url: https://github.com/louislam/uptime-kuma
- anchor: prometheus-alertmanager
  counts:
    declared: 0
    observed: 15
  evidence:
  - route: source code
    url: https://github.com/prometheus/alertmanager/tree/main/notify
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
    name: Amazon SNS
    provider: amazon-sns
    says: ships the Amazon SNS SDK or integration code
    source: https://github.com/prometheus/alertmanager/tree/main/notify
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/prometheus/alertmanager/tree/main/notify
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: incident.io
    provider: incident-io
    says: ships the incident.io SDK or integration code
    source: https://github.com/prometheus/alertmanager/tree/main/notify
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: Jira
    provider: jira
    says: ships the Jira SDK or integration code
    source: https://github.com/prometheus/alertmanager/tree/main/notify
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Mattermost
    provider: mattermost
    says: ships the Mattermost SDK or integration code
    source: https://github.com/prometheus/alertmanager/tree/main/notify
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Teams
    provider: microsoft-teams
    says: ships the Microsoft Teams SDK or integration code
    source: https://github.com/prometheus/alertmanager/tree/main/notify
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Opsgenie
    provider: opsgenie
    says: ships the Opsgenie SDK or integration code
    source: https://github.com/prometheus/alertmanager/tree/main/notify
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: PagerDuty
    provider: pagerduty
    says: ships the PagerDuty SDK or integration code
    source: https://github.com/prometheus/alertmanager/tree/main/notify
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
    name: Pushover
    provider: pushover
    says: ships the Pushover SDK or integration code
    source: https://github.com/prometheus/alertmanager/tree/main/notify
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Rocket.Chat
    provider: rocketchat
    says: ships the Rocket.Chat SDK or integration code
    source: https://github.com/prometheus/alertmanager/tree/main/notify
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/prometheus/alertmanager/tree/main/notify
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://github.com/prometheus/alertmanager/tree/main/notify
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: VictorOps
    provider: victorops
    says: ships the VictorOps SDK or integration code
    source: https://github.com/prometheus/alertmanager/tree/main/notify
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Webex
    provider: webex
    says: ships the Webex SDK or integration code
    source: https://github.com/prometheus/alertmanager/tree/main/notify
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: WeChat (Work)
    provider: wechat
    says: ships the WeChat (Work) SDK or integration code
    source: https://github.com/prometheus/alertmanager/tree/main/notify
    tier: observed
  kind: self-hosted
  name: Prometheus Alertmanager
  page: /applications/observability-monitoring/prometheus-alertmanager/
  slug: prometheus-alertmanager
  url: https://github.com/prometheus/alertmanager
- anchor: gatus
  counts:
    declared: 0
    observed: 38
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
    layer: domain
    name: Zulip
    provider: zulip
    says: ships the Zulip SDK or integration code
    source: https://github.com/TwiN/gatus/tree/master/alerting/provider
    tier: observed
  kind: self-hosted
  name: Gatus
  page: /applications/observability-monitoring/gatus/
  slug: gatus
  url: https://github.com/TwiN/gatus
- anchor: netdata
  counts:
    declared: 0
    observed: 22
  evidence:
  - route: source code
    url: https://github.com/netdata/netdata/tree/master/src/health/notifications
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Alerta
    provider: alerta
    says: ships the Alerta SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    name: Amazon SNS
    provider: amazon-sns
    says: ships the Amazon SNS SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Dynatrace
    provider: dynatrace
    says: ships the Dynatrace SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Flock
    provider: flock
    says: ships the Flock SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    name: Gotify
    provider: gotify
    says: ships the Gotify SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: ilert
    provider: ilert
    says: ships the ilert SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    name: Kavenegar
    provider: kavenegar
    says: ships the Kavenegar SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    name: MessageBird
    provider: bird
    says: ships the MessageBird SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Teams
    provider: microsoft-teams
    says: ships the Microsoft Teams SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    name: ntfy
    provider: ntfy
    says: ships the ntfy SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Opsgenie
    provider: opsgenie
    says: ships the Opsgenie SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: PagerDuty
    provider: pagerduty
    says: ships the PagerDuty SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    name: Prowl
    provider: prowl
    says: ships the Prowl SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    name: Pushbullet
    provider: pushbullet
    says: ships the Pushbullet SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    name: Pushover
    provider: pushover
    says: ships the Pushover SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Rocket.Chat
    provider: rocketchat
    says: ships the Rocket.Chat SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: SIGNL4
    provider: signl4
    says: ships the SIGNL4 SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    name: SMSEagle
    provider: smseagle
    says: ships the SMSEagle SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
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
    source: https://github.com/netdata/netdata/tree/master/src/health/notifications
    tier: observed
  kind: self-hosted
  name: Netdata
  page: /applications/observability-monitoring/netdata/
  slug: netdata
  url: https://github.com/netdata/netdata
- anchor: grafana
  counts:
    declared: 0
    observed: 30
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
  - route: source code
    url: https://github.com/grafana/alerting/tree/main/receivers
  - route: source code
    url: https://github.com/grafana/grafana/tree/main/public/app/plugins/datasource
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
    name: Amazon SNS
    provider: amazon-sns
    says: ships the Amazon SNS SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: aws-sdk-go-v2/service/bedrockruntime
    provider: amazon-bedrock
    says: ships the aws-sdk-go-v2/service/bedrockruntime SDK or integration code
    source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    credit: null
    layer: common
    name: aws-sdk-go-v2/service/kms
    provider: amazon-kms
    says: ships the aws-sdk-go-v2/service/kms SDK or integration code
    source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
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
    name: aws-sdk-go-v2/service/s3
    provider: amazon-s3
    says: ships the aws-sdk-go-v2/service/s3 SDK or integration code
    source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    credit: null
    layer: common
    name: aws-sdk-go-v2/service/secretsmanager
    provider: amazon-secrets-manager
    says: ships the aws-sdk-go-v2/service/secretsmanager SDK or integration code
    source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Azure Monitor data source
    provider: microsoft-azure-monitor
    says: ships the Azure Monitor data source SDK or integration code
    source: https://github.com/grafana/grafana/tree/main/public/app/plugins/datasource
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    credit: null
    layer: common
    name: azure-sdk-for-go keyvault/azkeys
    provider: microsoft-azure-key-vault
    says: ships the azure-sdk-for-go keyvault/azkeys SDK or integration code
    source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
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
    name: azure-sdk-for-go storage/azblob
    provider: microsoft-azure-blob-storage
    says: ships the azure-sdk-for-go storage/azblob SDK or integration code
    source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: cloud.google.com/go/aiplatform
    provider: google-vertex-ai
    says: ships the cloud.google.com/go/aiplatform SDK or integration code
    source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    credit: null
    layer: common
    name: cloud.google.com/go/kms
    provider: google-cloud-kms
    says: ships the cloud.google.com/go/kms SDK or integration code
    source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: cloud.google.com/go/monitoring
    provider: google-cloud-monitoring
    says: ships the cloud.google.com/go/monitoring SDK or integration code
    source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
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
    name: cloud.google.com/go/storage
    provider: gcp-cloud-storage
    says: ships the cloud.google.com/go/storage SDK or integration code
    source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: DingTalk
    provider: dingtalk
    says: ships the DingTalk SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Chat
    provider: google-chat
    says: ships the Google Chat SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    credit: null
    layer: common
    name: hashicorp/vault/api
    provider: hvault
    says: ships the hashicorp/vault/api SDK or integration code
    source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: Jira
    provider: jira
    says: ships the Jira SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: LINE
    provider: line
    says: ships the LINE SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Teams
    provider: microsoft-teams
    says: ships the Microsoft Teams SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: openai/openai-go/v3
    provider: openai
    says: ships the openai/openai-go/v3 SDK or integration code
    source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Opsgenie
    provider: opsgenie
    says: ships the Opsgenie SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: PagerDuty
    provider: pagerduty
    says: ships the PagerDuty SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
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
    name: Pushover
    provider: pushover
    says: ships the Pushover SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Sensu Go
    provider: sensu
    says: ships the Sensu Go SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Threema
    provider: threema
    says: ships the Threema SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: VictorOps
    provider: victorops
    says: ships the VictorOps SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Webex
    provider: webex
    says: ships the Webex SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: WeChat
    provider: wechat
    says: ships the WeChat SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  kind: self-hosted
  name: Grafana
  page: /applications/observability-monitoring/grafana/
  slug: grafana
  url: https://github.com/grafana/grafana
- anchor: sentry
  counts:
    declared: 0
    observed: 31
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
  - route: source code
    url: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  - route: source code
    url: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations/data_forwarding
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: Amazon SQS
    provider: amazon-sqs
    says: ships the Amazon SQS SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations/data_forwarding
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: AWS Lambda
    provider: aws-lambda
    says: ships the AWS Lambda SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: Azure DevOps
    provider: microsoft-azure-devops
    says: ships the Azure DevOps SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: common
    name: Bitbucket
    provider: bitbucket
    says: ships the Bitbucket SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: common
    name: boto3
    provider: amazon-web-services
    says: ships the boto3 SDK or integration code
    source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.10
      key: AE-100.70.10
      name: Coding Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    credit: null
    layer: agent
    name: Claude Code
    provider: anthropic
    says: ships the Claude Code SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.10
      key: AE-100.70.10
      name: Coding Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    credit: null
    layer: agent
    name: Cursor
    provider: cursor
    says: ships the Cursor SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Datadog
    provider: datadog
    says: ships the Datadog SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
    tier: observed
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
    says: ships the GitHub SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.10
      key: AE-100.70.10
      name: Coding Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    credit: null
    layer: agent
    name: GitHub Copilot
    provider: github-copilot
    says: ships the GitHub Copilot SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: common
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Cloud
    provider: google-cloud-platform
    says: ships the Google Cloud SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: google-cloud-bigtable
    provider: google-cloud-bigtable
    says: ships the google-cloud-bigtable SDK or integration code
    source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: common
    name: google-cloud-build
    provider: google-cloud-build
    says: ships the google-cloud-build SDK or integration code
    source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: google-cloud-functions
    provider: google-cloud-functions
    says: ships the google-cloud-functions SDK or integration code
    source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    credit: null
    layer: common
    name: google-cloud-kms
    provider: google-cloud-kms
    says: ships the google-cloud-kms SDK or integration code
    source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: google-cloud-logging
    provider: google-cloud-logging
    says: ships the google-cloud-logging SDK or integration code
    source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: google-cloud-pubsub
    provider: google-cloud-pubsub
    says: ships the google-cloud-pubsub SDK or integration code
    source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: google-cloud-spanner
    provider: google-cloud-spanner
    says: ships the google-cloud-spanner SDK or integration code
    source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
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
    name: google-cloud-storage
    provider: gcp-cloud-storage
    says: ships the google-cloud-storage SDK or integration code
    source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: Jira
    provider: jira
    says: ships the Jira SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: common
    name: maxminddb
    provider: maxmind
    says: ships the maxminddb SDK or integration code
    source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Teams
    provider: microsoft-teams
    says: ships the Microsoft Teams SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Opsgenie
    provider: opsgenie
    says: ships the Opsgenie SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: PagerDuty
    provider: pagerduty
    says: ships the PagerDuty SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: common
    name: Perforce
    provider: perforce
    says: ships the Perforce SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
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
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations/data_forwarding
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Splunk
    provider: splunk
    says: ships the Splunk SDK or integration code
    source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations/data_forwarding
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
    name: stripe
    provider: stripe
    says: ships the stripe SDK or integration code
    source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
    tier: observed
  kind: open-source-saas
  name: Sentry
  page: /applications/observability-monitoring/sentry/
  slug: sentry
  url: https://github.com/getsentry/sentry
- anchor: datadog
  counts:
    declared: 21
    observed: 0
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.datadog.app/latest/
  - route: integrations page
    url: https://docs.datadoghq.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Web Services
    provider: amazon-web-services
    says: lists Amazon Web Services as an integration
    source: https://docs.datadoghq.com/integrations/amazon_web_services/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Anthropic
    provider: anthropic
    says: lists Anthropic as an integration
    source: https://docs.datadoghq.com/integrations/anthropic/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: Azure
    provider: microsoft-azure
    says: lists Azure as an integration
    source: https://docs.datadoghq.com/integrations/azure/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Cloudflare
    provider: cloudflare
    says: lists Cloudflare as an integration
    source: https://docs.datadoghq.com/integrations/cloudflare/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Fastly
    provider: fastly
    says: lists Fastly as an integration
    source: https://docs.datadoghq.com/integrations/fastly/
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
    source: https://docs.datadoghq.com/integrations/github/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Cloud
    provider: google-cloud-platform
    says: lists Google Cloud as an integration
    source: https://docs.datadoghq.com/integrations/google_cloud_platform/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://docs.datadoghq.com/integrations/jira/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://docs.datadoghq.com/integrations/microsoft_teams/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: MongoDB
    provider: mongodb
    says: lists MongoDB as an integration
    source: https://docs.datadoghq.com/integrations/mongodb/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Okta
    provider: okta
    says: lists Okta as an integration
    source: https://docs.datadoghq.com/integrations/okta/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: OpenAI
    provider: openai
    says: lists OpenAI as an integration
    source: https://docs.datadoghq.com/integrations/openai/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Opsgenie
    provider: opsgenie
    says: lists Opsgenie as an integration
    source: https://docs.datadoghq.com/integrations/opsgenie/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: PagerDuty
    provider: pagerduty
    says: lists PagerDuty as an integration
    source: https://docs.datadoghq.com/integrations/pagerduty/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: SendGrid
    provider: sendgrid
    says: lists SendGrid as an integration
    source: https://docs.datadoghq.com/integrations/sendgrid/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.30
      key: it-service-management
      name: IT Service Management
      url: /capabilities/it-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: ServiceNow
    provider: servicenow
    says: lists ServiceNow as an integration
    source: https://docs.datadoghq.com/integrations/servicenow/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://docs.datadoghq.com/integrations/slack/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Snowflake
    provider: snowflake
    says: lists Snowflake as an integration
    source: https://docs.datadoghq.com/integrations/snowflake/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4290.60.20
      key: BC-4290.60.20
      name: Uptime Disclosure
      url: /capabilities/service-resilience-commitment-management/
      via_parent: Service Resilience Commitment Management
    credit: null
    layer: domain
    name: Statuspage
    provider: statuspage
    says: lists Statuspage as an integration
    source: https://docs.datadoghq.com/integrations/statuspage/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://docs.datadoghq.com/integrations/stripe/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Twilio
    provider: twilio
    says: lists Twilio as an integration
    source: https://docs.datadoghq.com/integrations/twilio/
    tier: declared
  kind: commercial
  name: Datadog
  page: /applications/observability-monitoring/datadog/
  slug: datadog
  url: https://www.datadoghq.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: observability-monitoring
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Developer Tools
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Utilities
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Tools
  store: google-play
  url: https://play.google.com/store/apps/category/TOOLS
- category: Monitoring & Status Pages
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#monitoring--status-pages
- category: Monitoring
  store: atlassian-marketplace
  url: https://marketplace.atlassian.com/
- category: Developer Tools
  store: slack-marketplace
  url: https://slack.com/apps
- category: Server Monitoring
  store: zapier
  url: https://zapier.com/apps
name: Observability, Monitoring & Status Pages
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: SMS alerts
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: domain
  why: alert notifications routed to team chat -- the most common integration in every reference app
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: email alerts via transactional email APIs
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  fit: exact
  layer: common
  why: open an issue in a tracker when a monitor fires or an error groups
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  fit: exact
  layer: domain
  why: paging, on-call escalation and alert hubs
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: logging monitor events to a spreadsheet (nearest)
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: mobile and desktop push alerts
- capability:
    attribution: Turbo EA
    id: BC-600.30
    key: it-service-management
    name: IT Service Management
    url: /capabilities/it-service-management/
    via_parent: null
  fit: exact
  layer: domain
  why: ITSM / PSA tickets from alerts
- capability:
    attribution: API Evangelist extension
    id: AE-200
    key: AE-200
    name: Home, Device & Consumer IoT
    url: /capabilities/home-device-consumer-iot/
    via_parent: null
  fit: exact
  layer: common
  why: home automation targets for alerts
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: domain
  why: telemetry backends, cross-tool event forwarding, and (nearest) telemetry pulled from monitored SaaS
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: hand alerts to workflow automation
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: object storage for snapshots, artifacts and attachments (nearest)
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  fit: exact
  layer: common
  why: KMS and vaults for stored secrets
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: LLM features (assistants, query generation)
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  fit: exact
  layer: common
  why: link errors to commits, suspect commits and code owners
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  fit: exact
  layer: domain
  why: cloud platforms whose metrics are collected, and backing infrastructure for the hosted product (nearest where the service is a datastore or queue)
- capability:
    attribution: API Evangelist extension
    id: AE-100.70.10
    key: AE-100.70.10
    name: Coding Agents
    url: /capabilities/vertical-agents/
    via_parent: Vertical Agents
  fit: exact
  layer: agent
  why: error -> fix handoff to coding agents
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: forwarding events to a CDP
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: billing for the hosted edition
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: common
  why: geolocating client IPs on events
stack:
- capabilities:
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
      - Datadog
      - Gatus
      - Grafana
      - Netdata
      - Prometheus Alertmanager
      - Sentry
      - Uptime Kuma
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://docs.datadoghq.com/integrations/slack/
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Datadog
      - Gatus
      - Grafana
      - Netdata
      - Prometheus Alertmanager
      - Sentry
      - Uptime Kuma
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://docs.datadoghq.com/integrations/microsoft_teams/
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: observed
      url: /providers/microsoft-teams/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Gatus
      - Grafana
      - Netdata
      - Prometheus Alertmanager
      - Sentry
      - Uptime Kuma
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Gatus
      - Grafana
      - Netdata
      - Prometheus Alertmanager
      - Uptime Kuma
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/grafana/alerting/tree/main/receivers
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Gatus
      - Netdata
      - Prometheus Alertmanager
      - Uptime Kuma
      band: minimal
      in_catalog: true
      kin_score: 2.9
      mcp:
        source: https://docs.rocket.chat/docs/mcp-server
        status: verified
      name: Rocket.Chat
      slug: rocketchat
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      - https://github.com/netdata/netdata/tree/master/src/health/notifications
      status: profiled
      tags:
      - Collaboration
      - Communications
      - Company
      - Open Source
      tier: observed
      url: /providers/rocketchat/
    - agent_band: agent-native
      agent_readiness: 47.0
      apps:
      - Gatus
      - Grafana
      - Uptime Kuma
      band: exemplar
      in_catalog: true
      kin_score: 71.3
      mcp:
        source: https://github.com/line/line-bot-mcp-server
        status: verified
      name: LINE
      slug: line
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/grafana/alerting/tree/main/receivers
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Chatbots
      - Messaging
      - Mini Apps
      - Social Login
      tier: observed
      url: /providers/line/
    - agent_band: agent-ready
      agent_readiness: 41.0
      apps:
      - Gatus
      - Grafana
      - Uptime Kuma
      band: exemplar
      in_catalog: true
      kin_score: 67.1
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Chat
      slug: google-chat
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/grafana/alerting/tree/main/receivers
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Google
      - Google Workspace
      tier: observed
      url: /providers/google-chat/
    - agent_band: agent-ready
      agent_readiness: 61.8
      apps:
      - Gatus
      - Grafana
      - Prometheus Alertmanager
      band: strong
      in_catalog: true
      kin_score: 66.1
      mcp:
        source: https://github.com/WebexSamples/webex-messaging-mcp-server
        status: verified
      name: Webex
      slug: webex
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/grafana/alerting/tree/main/receivers
      - https://github.com/prometheus/alertmanager/tree/main/notify
      status: profiled
      tags:
      - Calling
      - Collaboration
      - Communications
      - Enterprise
      tier: observed
      url: /providers/webex/
    - agent_band: agent-aware
      agent_readiness: 23.6
      apps:
      - Grafana
      - Prometheus Alertmanager
      - Uptime Kuma
      band: developing
      in_catalog: true
      kin_score: 45.1
      mcp:
        status: none
      name: WeCom
      slug: wechat
      sources:
      - https://github.com/grafana/alerting/tree/main/receivers
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      - https://github.com/prometheus/alertmanager/tree/main/notify
      status: profiled
      tags:
      - Messaging
      - Mini Programs
      - Payments
      - Social
      tier: observed
      url: /providers/wechat/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Gatus
      - Prometheus Alertmanager
      - Uptime Kuma
      band: thin
      in_catalog: true
      kin_score: 37.0
      mcp:
        source: https://github.com/mattermost/mmctl-mcp
        status: verified
      name: Mattermost
      slug: mattermost
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      - https://github.com/prometheus/alertmanager/tree/main/notify
      status: profiled
      tags:
      - Collaboration
      - Messaging
      - Open Source
      - Team Chat
      tier: observed
      url: /providers/mattermost/
    - agent_band: agent-aware
      agent_readiness: 20.3
      apps:
      - Gatus
      - Uptime Kuma
      band: developing
      in_catalog: true
      kin_score: 43.2
      mcp:
        status: none
      name: Signal
      slug: signal
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Cryptography
      - Encryption
      - Messaging
      - Security
      tier: observed
      url: /providers/signal/
    - agent_band: human-only
      agent_readiness: 2.8
      apps:
      - Grafana
      - Uptime Kuma
      band: thin
      in_catalog: true
      kin_score: 30.7
      mcp:
        status: none
      name: Threema
      slug: threema
      sources:
      - https://github.com/grafana/alerting/tree/main/receivers
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Company
      - Messaging
      - Privacy
      - Security
      tier: observed
      url: /providers/threema/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Grafana
      - Uptime Kuma
      band: minimal
      in_catalog: true
      kin_score: 7.1
      mcp:
        source: https://github.com/open-dingtalk/dingtalk-mcp
        status: verified
      name: DingTalk
      slug: dingtalk
      sources:
      - https://github.com/grafana/alerting/tree/main/receivers
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Collaboration
      - Communications
      - Company
      - Enterprise
      tier: observed
      url: /providers/dingtalk/
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Uptime Kuma
      band: developing
      in_catalog: true
      kin_score: 46.7
      mcp:
        source: https://www.zoho.com/mcp/
        status: verified
      name: Zoho Cliq
      slug: zoho-cliq
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Team Collaboration
      tier: observed
      url: /providers/zoho-cliq/
    - agent_band: agent-ready
      agent_readiness: 47.5
      apps:
      - Uptime Kuma
      band: developing
      in_catalog: true
      kin_score: 41.7
      mcp:
        source: https://github.com/bitrix24/mcp-rest-doc
        status: verified
      name: Bitrix24
      slug: bitrix24
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - CRM
      - Collaboration
      - Project Management
      - Task
      tier: observed
      url: /providers/bitrix24/
    - agent_band: agent-aware
      agent_readiness: 22.8
      apps:
      - Uptime Kuma
      band: thin
      in_catalog: true
      kin_score: 33.7
      mcp:
        status: none
      name: KOOK
      slug: kook
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Community
      - Company
      - Gaming
      - Voice Communication
      tier: observed
      url: /providers/kook/
    - agent_band: agent-aware
      agent_readiness: 25.1
      apps:
      - Gatus
      band: thin
      in_catalog: true
      kin_score: 33.1
      mcp:
        source: https://github.com/zulip/zulipmcp
        status: verified
      name: Zulip
      slug: zulip
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      status: profiled
      tags:
      - Collaboration
      - Messaging
      - Team Chat
      - Webhook
      tier: observed
      url: /providers/zulip/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Uptime Kuma
      band: thin
      in_catalog: true
      kin_score: 32.7
      mcp:
        status: none
      name: Nextcloud Talk
      slug: nextcloud
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Collaboration
      - File Sharing
      - File Sync
      - Self-Hosted
      tier: observed
      url: /providers/nextcloud/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Uptime Kuma
      band: emerging
      in_catalog: true
      kin_score: 23.1
      mcp:
        source: https://pumble.com/help/integrations/automation-workflow-integrations/how-to-use-the-pumble-mcp-server/
        status: verified
      name: Pumble
      slug: pumble
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/pumble/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Uptime Kuma
      band: minimal
      in_catalog: true
      kin_score: 4.8
      mcp:
        status: none
      name: VK
      slug: vk
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Public APIs
      - Social
      tier: observed
      url: /providers/vk/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Netdata
      band: minimal
      in_catalog: true
      kin_score: 3.4
      mcp:
        status: none
      name: Flock
      slug: flock
      sources:
      - https://github.com/netdata/netdata/tree/master/src/health/notifications
      status: profiled
      tags:
      - Commercial Motor
      - Company
      - Insurance
      - Insurtech
      tier: observed
      url: /providers/flock/
    - agent_band: null
      agent_readiness: null
      apps:
      - Uptime Kuma
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Feishu
      slug: feishu
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - Datadog
      - Gatus
      - Grafana
      - Netdata
      - Prometheus Alertmanager
      - Sentry
      - Uptime Kuma
      band: developing
      in_catalog: true
      kin_score: 52.1
      mcp:
        source: https://github.com/PagerDuty/pagerduty-mcp-server
        status: verified
      name: PagerDuty
      slug: pagerduty
      sources:
      - https://docs.datadoghq.com/integrations/pagerduty/
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
      status: profiled
      tags:
      - Alerting
      - DevOps
      - Incident Management
      - On-Call Management
      tier: observed
      url: /providers/pagerduty/
    - agent_band: agent-aware
      agent_readiness: 26.5
      apps:
      - Datadog
      - Gatus
      - Grafana
      - Netdata
      - Prometheus Alertmanager
      - Sentry
      - Uptime Kuma
      band: developing
      in_catalog: true
      kin_score: 48.6
      mcp:
        status: none
      name: Opsgenie
      slug: opsgenie
      sources:
      - https://docs.datadoghq.com/integrations/opsgenie/
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
      status: profiled
      tags:
      - Alerts
      - Incident Management
      - Monitoring
      - On-Call
      tier: observed
      url: /providers/opsgenie/
    - agent_band: agent-aware
      agent_readiness: 18.1
      apps:
      - Gatus
      - Netdata
      - Uptime Kuma
      band: thin
      in_catalog: true
      kin_score: 36.7
      mcp:
        status: none
      name: SIGNL4
      slug: signl4
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      - https://github.com/netdata/netdata/tree/master/src/health/notifications
      status: profiled
      tags:
      - Alerting
      - Incident Management
      - Mobile Alerts
      - On-Call
      tier: observed
      url: /providers/signl4/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Grafana
      - Prometheus Alertmanager
      - Uptime Kuma
      band: emerging
      in_catalog: true
      kin_score: 18.1
      mcp:
        status: none
      name: Splunk On-Call
      slug: victorops
      sources:
      - https://github.com/grafana/alerting/tree/main/receivers
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      - https://github.com/prometheus/alertmanager/tree/main/notify
      status: profiled
      tags:
      - Alerting
      - DevOps
      - Incident Management
      - On-Call
      tier: observed
      url: /providers/victorops/
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - Gatus
      - Netdata
      band: thin
      in_catalog: true
      kin_score: 37.4
      mcp:
        source: https://github.com/iLert/mcp-ilert
        status: verified
      name: ilert
      slug: ilert
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/netdata/netdata/tree/master/src/health/notifications
      status: profiled
      tags:
      - Alert Routing
      - Escalation Policies
      - Incident Management
      - On-Call Alerting
      tier: observed
      url: /providers/ilert/
    - agent_band: agent-native
      agent_readiness: 49.9
      apps:
      - Gatus
      - Prometheus Alertmanager
      band: thin
      in_catalog: true
      kin_score: 34.1
      mcp:
        source: https://help.incident.io/
        status: documented
      name: incident.io
      slug: incident-io
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/prometheus/alertmanager/tree/main/notify
      status: profiled
      tags:
      - AIOps
      - Incident Management
      - Incident Response
      - Monitoring
      tier: observed
      url: /providers/incident-io/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Gatus
      - Uptime Kuma
      band: thin
      in_catalog: true
      kin_score: 26.6
      mcp:
        status: none
      name: Squadcast
      slug: squadcast
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - DevOps
      - Incident Response
      - On-Call Management
      - SRE
      tier: observed
      url: /providers/squadcast/
    - agent_band: agent-ready
      agent_readiness: 64.4
      apps:
      - Uptime Kuma
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp: &id005
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira Service Management
      slug: jira
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags: &id006
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: observed
      url: /providers/jira/
    - agent_band: agent-aware
      agent_readiness: 27.6
      apps:
      - Uptime Kuma
      band: strong
      in_catalog: true
      kin_score: 66.0
      mcp:
        source: https://github.com/grafana/mcp-grafana
        status: verified
      name: Grafana OnCall
      slug: grafana-com
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Dashboards
      - Logs
      - Monitoring
      - Observability
      tier: observed
      url: /providers/grafana-com/
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - Uptime Kuma
      band: developing
      in_catalog: true
      kin_score: 42.5
      mcp:
        source: https://github.com/flashcatcloud/flashduty-mcp-server
        status: verified
      name: Flashduty
      slug: flashduty
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Artificial Intelligence
      - Incident Response
      - Monitoring
      - On-Call
      tier: observed
      url: /providers/flashduty/
    - agent_band: agent-aware
      agent_readiness: 22.8
      apps:
      - Uptime Kuma
      band: thin
      in_catalog: true
      kin_score: 29.6
      mcp:
        status: none
      name: Keep
      slug: keep
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - AIOps
      - Alerting
      - Incident Management
      - Observability
      tier: observed
      url: /providers/keep/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Uptime Kuma
      band: thin
      in_catalog: true
      kin_score: 28.7
      mcp:
        source: https://github.com/PagerTree/pagertree-mcp-server
        status: verified
      name: PagerTree
      slug: pagertree
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/pagertree/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Netdata
      band: emerging
      in_catalog: true
      kin_score: 17.4
      mcp:
        status: none
      name: Alerta
      slug: alerta
      sources:
      - https://github.com/netdata/netdata/tree/master/src/health/notifications
      status: profiled
      tags:
      - Alerting
      - Company
      - Monitoring
      - Open Source
      tier: observed
      url: /providers/alerta/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Uptime Kuma
      band: minimal
      in_catalog: true
      kin_score: 5.1
      mcp:
        status: unknown
      name: GoAlert
      slug: goalert
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Alerting
      - Automation
      - Incident Management
      - On-Call
      tier: observed
      url: /providers/goalert/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.6
      apps:
      - Gatus
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 80.0
      mcp:
        source: https://github.com/datadog-labs/mcp-server
        status: verified
      name: Datadog
      slug: datadog
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
      status: profiled
      tags:
      - Analytics
      - Dashboards
      - Datadog
      - Visualization
      tier: observed
      url: /providers/datadog/
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - Gatus
      - Sentry
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp:
        status: none
      name: Splunk
      slug: splunk
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations/data_forwarding
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Logging
      - Machine Data
      tier: observed
      url: /providers/splunk/
    - agent_band: agent-ready
      agent_readiness: 43.8
      apps:
      - Netdata
      band: exemplar
      in_catalog: true
      kin_score: 85.6
      mcp:
        source: https://github.com/dynatrace-oss/dynatrace-mcp
        status: verified
      name: Dynatrace
      slug: dynatrace
      sources:
      - https://github.com/netdata/netdata/tree/master/src/health/notifications
      status: profiled
      tags:
      - AI Operations
      - APM
      - Analytics
      - Application Performance Monitoring
      tier: observed
      url: /providers/dynatrace/
    - agent_band: agent-ready
      agent_readiness: 49.5
      apps:
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 76.2
      mcp:
        source: https://raw.githubusercontent.com/googleapis/gcloud-mcp/main/README.md
        status: verified
      name: google-cloud-logging
      slug: google-cloud-logging
      sources:
      - https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
      status: profiled
      tags:
      - Cloud
      - Logging
      - Monitoring
      - Observability
      tier: observed
      url: /providers/google-cloud-logging/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Gatus
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 67.5
      mcp: &id001
        source: https://github.com/googleapis/mcp-toolbox
        status: verified
      name: Google Cloud
      slug: google-cloud-platform
      sources:
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
      status: profiled
      tags: &id002
      - API Management
      - Cloud Computing
      - Infrastructure
      - Platform-as-a-Service
      tier: observed
      url: /providers/google-cloud-platform/
    - agent_band: agent-ready
      agent_readiness: 37.2
      apps:
      - Grafana
      band: strong
      in_catalog: true
      kin_score: 66.4
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: cloud.google.com/go/monitoring
      slug: google-cloud-monitoring
      sources:
      - https://raw.githubusercontent.com/grafana/grafana/main/go.mod
      status: profiled
      tags:
      - Alerting
      - Dashboards
      - Google Cloud
      - Metrics
      tier: observed
      url: /providers/google-cloud-monitoring/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Grafana
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Monitor data source
      slug: microsoft-azure-monitor
      sources:
      - https://github.com/grafana/grafana/tree/main/public/app/plugins/datasource
      status: profiled
      tags:
      - Application Insights
      - Cloud
      - Logs
      - Metrics
      tier: observed
      url: /providers/microsoft-azure-monitor/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Grafana
      band: thin
      in_catalog: true
      kin_score: 34.0
      mcp:
        status: none
      name: Sensu Go
      slug: sensu
      sources:
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Company
      - Infrastructure
      - Monitoring
      - Observability
      tier: observed
      url: /providers/sensu/
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - Datadog
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp: &id003
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://docs.datadoghq.com/integrations/twilio/
      status: profiled
      tags: &id004
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: declared
      url: /providers/twilio/
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Datadog
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp: &id017
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://docs.datadoghq.com/integrations/anthropic/
      status: profiled
      tags: &id018
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: declared
      url: /providers/anthropic/
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - Datadog
      band: exemplar
      in_catalog: true
      kin_score: 84.0
      mcp: &id007
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://docs.datadoghq.com/integrations/sendgrid/
      status: profiled
      tags: &id008
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: declared
      url: /providers/sendgrid/
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - Datadog
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare
      slug: cloudflare
      sources:
      - https://docs.datadoghq.com/integrations/cloudflare/
      status: profiled
      tags:
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: declared
      url: /providers/cloudflare/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Datadog
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: &id019
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://docs.datadoghq.com/integrations/openai/
      status: profiled
      tags: &id020
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: declared
      url: /providers/openai/
    - agent_band: agent-native
      agent_readiness: 44.9
      apps:
      - Datadog
      band: exemplar
      in_catalog: true
      kin_score: 82.3
      mcp:
        source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
        status: verified
      name: Snowflake
      slug: snowflake
      sources:
      - https://docs.datadoghq.com/integrations/snowflake/
      status: profiled
      tags:
      - Data
      - Data Lakehouse
      - Data Warehouse
      - Snowflake
      tier: declared
      url: /providers/snowflake/
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Datadog
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp: &id015
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://docs.datadoghq.com/integrations/stripe/
      status: profiled
      tags: &id016
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: declared
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Datadog
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://docs.datadoghq.com/integrations/okta/
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: declared
      url: /providers/okta/
    - agent_band: agent-ready
      agent_readiness: 59.1
      apps:
      - Datadog
      band: exemplar
      in_catalog: true
      kin_score: 79.9
      mcp:
        source: https://github.com/mongodb-js/mongodb-mcp-server
        status: verified
      name: MongoDB
      slug: mongodb
      sources:
      - https://docs.datadoghq.com/integrations/mongodb/
      status: profiled
      tags:
      - Cloud Database
      - Database
      - Document Database
      - NoSQL
      tier: declared
      url: /providers/mongodb/
    - agent_band: agent-aware
      agent_readiness: 24.2
      apps:
      - Datadog
      band: strong
      in_catalog: true
      kin_score: 66.0
      mcp:
        source: https://github.com/fastly/mcp
        status: verified
      name: Fastly
      slug: fastly
      sources:
      - https://docs.datadoghq.com/integrations/fastly/
      status: profiled
      tags:
      - CDN
      - Edge Cloud
      - Edge Compute
      - WebAssembly
      tier: declared
      url: /providers/fastly/
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 45.6
      apps:
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 74.9
      mcp:
        source: https://github.com/awslabs/mcp/tree/main/src/lambda-tool-mcp-server
        status: verified
      name: AWS Lambda
      slug: aws-lambda
      sources:
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
      status: profiled
      tags:
      - Logging
      - Monitoring
      - Observability
      - Serverless
      tier: observed
      url: /providers/aws-lambda/
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 67.5
      mcp:
        status: none
      name: google-cloud-functions
      slug: google-cloud-functions
      sources:
      - https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
      status: profiled
      tags:
      - Event-Driven
      - Functions
      - Google Cloud
      - Serverless
      tier: observed
      url: /providers/google-cloud-functions/
    - agent_band: agent-ready
      agent_readiness: 45.0
      apps:
      - Datadog
      band: exemplar
      in_catalog: true
      kin_score: 76.0
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure
      slug: microsoft-azure
      sources:
      - https://docs.datadoghq.com/integrations/azure/
      status: profiled
      tags:
      - Cloud
      - Cloud Computing
      - Enterprise
      - Microsoft Azure
      tier: declared
      url: /providers/microsoft-azure/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Datadog
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp: &id013
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Web Services
      slug: amazon-web-services
      sources:
      - https://docs.datadoghq.com/integrations/amazon_web_services/
      status: profiled
      tags: &id014
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: declared
      url: /providers/amazon-web-services/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Datadog
      band: exemplar
      in_catalog: true
      kin_score: 67.5
      mcp: *id001
      name: Google Cloud
      slug: google-cloud-platform
      sources:
      - https://docs.datadoghq.com/integrations/google_cloud_platform/
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/google-cloud-platform/
  - capability:
      attribution: Turbo EA
      id: BC-600.30
      key: it-service-management
      name: IT Service Management
      url: /capabilities/it-service-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Uptime Kuma
      band: emerging
      in_catalog: true
      kin_score: 19.7
      mcp:
        status: unknown
      name: HaloPSA
      slug: halopsa
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Company
      - Customer Service Management
      - ITSM
      - Workflow Automation
      tier: observed
      url: /providers/halopsa/
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - Datadog
      band: strong
      in_catalog: true
      kin_score: 61.9
      mcp:
        status: none
      name: ServiceNow
      slug: servicenow
      sources:
      - https://docs.datadoghq.com/integrations/servicenow/
      status: profiled
      tags:
      - Automation
      - Cloud Services
      - Digital Workflows
      - ServiceNow
      tier: declared
      url: /providers/servicenow/
  - capability:
      attribution: Turbo EA
      id: BC-4290.60.20
      key: BC-4290.60.20
      name: Uptime Disclosure
      url: /capabilities/service-resilience-commitment-management/
      via_parent: Service Resilience Commitment Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.7
      apps:
      - Datadog
      band: thin
      in_catalog: true
      kin_score: 36.0
      mcp:
        status: none
      name: Statuspage
      slug: statuspage
      sources:
      - https://docs.datadoghq.com/integrations/statuspage/
      status: profiled
      tags:
      - Incident Communication
      - Incident Management
      - Status Pages
      - Uptime
      tier: declared
      url: /providers/statuspage/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - Gatus
      - Grafana
      - Netdata
      - Prometheus Alertmanager
      - Uptime Kuma
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        status: none
      name: Pushover
      slug: pushover
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/grafana/alerting/tree/main/receivers
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Alerts
      - Messaging
      - Notification
      - Push Notifications
      tier: observed
      url: /providers/pushover/
    - agent_band: agent-ready
      agent_readiness: 41.7
      apps:
      - Grafana
      - Netdata
      - Prometheus Alertmanager
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SNS
      slug: amazon-sns
      sources:
      - https://github.com/grafana/alerting/tree/main/receivers
      - https://github.com/netdata/netdata/tree/master/src/health/notifications
      - https://github.com/prometheus/alertmanager/tree/main/notify
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Messaging
      - Notification
      tier: observed
      url: /providers/amazon-sns/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Gatus
      - Netdata
      - Uptime Kuma
      band: emerging
      in_catalog: true
      kin_score: 15.5
      mcp:
        status: none
      name: ntfy
      slug: ntfy
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      - https://github.com/netdata/netdata/tree/master/src/health/notifications
      status: profiled
      tags:
      - Notification
      - Open Source
      - Pub/Sub
      - Self-Hosted
      tier: observed
      url: /providers/ntfy/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Gatus
      - Netdata
      - Uptime Kuma
      band: minimal
      in_catalog: true
      kin_score: 10.9
      mcp:
        source: https://gotify.net/docs/mcp
        status: verified
      name: Gotify
      slug: gotify
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      - https://github.com/netdata/netdata/tree/master/src/health/notifications
      status: profiled
      tags:
      - Messaging
      - Notification
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/gotify/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Netdata
      - Uptime Kuma
      band: thin
      in_catalog: true
      kin_score: 30.2
      mcp:
        status: none
      name: Pushbullet
      slug: pushbullet
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      - https://github.com/netdata/netdata/tree/master/src/health/notifications
      status: profiled
      tags:
      - Device Sync
      - Messaging
      - Notification
      - Push Notifications
      tier: observed
      url: /providers/pushbullet/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Netdata
      band: minimal
      in_catalog: true
      kin_score: 8.0
      mcp:
        status: unknown
      name: Prowl
      slug: prowl
      sources:
      - https://github.com/netdata/netdata/tree/master/src/health/notifications
      status: profiled
      tags:
      - Company
      - Mobile
      - Push Notifications
      - iOS
      tier: observed
      url: /providers/prowl/
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
      - Gatus
      - Netdata
      - Uptime Kuma
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp: *id003
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      - https://github.com/netdata/netdata/tree/master/src/health/notifications
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-native
      agent_readiness: 70.3
      apps:
      - Gatus
      - Netdata
      band: developing
      in_catalog: true
      kin_score: 50.0
      mcp:
        source: https://github.com/messagebird/bird-ai
        status: verified
      name: MessageBird
      slug: bird
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/netdata/netdata/tree/master/src/health/notifications
      status: profiled
      tags:
      - Communications
      - Email
      - SMS
      - WhatsApp
      tier: observed
      url: /providers/bird/
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - Gatus
      - Uptime Kuma
      band: developing
      in_catalog: true
      kin_score: 39.3
      mcp:
        source: https://github.com/plivo/mcp
        status: verified
      name: Plivo
      slug: plivo
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - CPaaS
      - Communications
      - SMS
      - Voice
      tier: observed
      url: /providers/plivo/
    - agent_band: human-only
      agent_readiness: 3.8
      apps:
      - Netdata
      - Uptime Kuma
      band: thin
      in_catalog: true
      kin_score: 27.1
      mcp:
        status: none
      name: SMSEagle
      slug: smseagle
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      - https://github.com/netdata/netdata/tree/master/src/health/notifications
      status: profiled
      tags:
      - Alerting
      - Company
      - IoT
      - SMS
      tier: observed
      url: /providers/smseagle/
    - agent_band: agent-native
      agent_readiness: 80.0
      apps:
      - Uptime Kuma
      band: exemplar
      in_catalog: true
      kin_score: 93.5
      mcp:
        source: https://github.com/team-telnyx/telnyx-mcp-server
        status: verified
      name: Telnyx
      slug: telnyx
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - CPaaS
      - Communications
      - SMS
      - Voice
      tier: observed
      url: /providers/telnyx/
    - agent_band: agent-ready
      agent_readiness: 40.0
      apps:
      - Gatus
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/Vonage/vonage-mcp-server-documentation
        status: verified
      name: Vonage
      slug: vonage
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      status: profiled
      tags:
      - Communications
      - Messaging
      - Telecommunications
      - Video Conferencing
      tier: observed
      url: /providers/vonage/
    - agent_band: agent-aware
      agent_readiness: 23.0
      apps:
      - Uptime Kuma
      band: developing
      in_catalog: true
      kin_score: 47.8
      mcp:
        source: https://github.com/seven-io/seven-mcp
        status: verified
      name: seven.io
      slug: seven-io
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Company
      - Messaging
      - SMS
      - Voice
      tier: observed
      url: /providers/seven-io/
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - Uptime Kuma
      band: thin
      in_catalog: true
      kin_score: 28.2
      mcp:
        source: https://github.com/ClickSend/clicksend-mcp-server
        status: verified
      name: ClickSend SMS
      slug: clicksend
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Communications
      - MMS
      - SMS
      - Voice
      tier: observed
      url: /providers/clicksend/
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Uptime Kuma
      band: thin
      in_catalog: true
      kin_score: 26.4
      mcp:
        status: none
      name: 46elks
      slug: 46elks
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - CPaaS
      - MMS
      - SMS
      - Voice
      tier: observed
      url: /providers/46elks/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Uptime Kuma
      band: minimal
      in_catalog: true
      kin_score: 10.5
      mcp:
        status: none
      name: Octopush
      slug: octopush
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Communications
      - Email
      - Marketing
      - SMS
      tier: observed
      url: /providers/octopush/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Netdata
      band: minimal
      in_catalog: true
      kin_score: 8.3
      mcp:
        status: none
      name: Kavenegar
      slug: kavenegar
      sources:
      - https://github.com/netdata/netdata/tree/master/src/health/notifications
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/kavenegar/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Uptime Kuma
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
        status: verified
      name: Aliyun SMS
      slug: alibabacloud
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/alibabacloud/
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 64.4
      apps:
      - Datadog
      - Grafana
      - Prometheus Alertmanager
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp: *id005
      name: Jira
      slug: jira
      sources:
      - https://docs.datadoghq.com/integrations/jira/
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 55.8
      apps:
      - Gatus
      - Uptime Kuma
      band: exemplar
      in_catalog: true
      kin_score: 72.6
      mcp:
        source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
        status: verified
      name: ClickUp
      slug: clickup
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: observed
      url: /providers/clickup/
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Gatus
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp: &id011
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      status: profiled
      tags: &id012
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Gatus
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: &id009
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      status: profiled
      tags: &id010
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 37.7
      apps:
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 81.9
      mcp:
        source: https://github.com/microsoft/azure-devops-mcp
        status: verified
      name: Azure DevOps
      slug: microsoft-azure-devops
      sources:
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
      status: profiled
      tags:
      - Agile
      - CI/CD
      - DevOps
      - Developer Tools
      tier: observed
      url: /providers/microsoft-azure-devops/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Gatus
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        source: https://gitea.com/gitea/gitea-mcp
        status: verified
      name: Gitea
      slug: gitea
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      status: profiled
      tags:
      - CI/CD
      - DevOps
      - Gitea
      - Version Control
      tier: observed
      url: /providers/gitea/
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Grafana
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 70.9
      mcp:
        status: none
      name: cloud.google.com/go/kms
      slug: google-cloud-kms
      sources:
      - https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
      - https://raw.githubusercontent.com/grafana/grafana/main/go.mod
      status: profiled
      tags:
      - Cryptography
      - Encryption
      - Google Cloud
      - Key Management
      tier: observed
      url: /providers/google-cloud-kms/
    - agent_band: agent-native
      agent_readiness: 39.2
      apps:
      - Grafana
      band: exemplar
      in_catalog: true
      kin_score: 77.5
      mcp:
        status: none
      name: aws-sdk-go-v2/service/secretsmanager
      slug: amazon-secrets-manager
      sources:
      - https://raw.githubusercontent.com/grafana/grafana/main/go.mod
      status: profiled
      tags:
      - Amazon Web Services
      - Configuration
      - Credentials
      - Rotation
      tier: observed
      url: /providers/amazon-secrets-manager/
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Grafana
      band: exemplar
      in_catalog: true
      kin_score: 76.8
      mcp:
        status: none
      name: aws-sdk-go-v2/service/kms
      slug: amazon-kms
      sources:
      - https://raw.githubusercontent.com/grafana/grafana/main/go.mod
      status: profiled
      tags:
      - Amazon Web Services
      - Cryptography
      - Data Protection
      - Encryption
      tier: observed
      url: /providers/amazon-kms/
    - agent_band: agent-ready
      agent_readiness: 36.6
      apps:
      - Grafana
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: azure-sdk-for-go keyvault/azkeys
      slug: microsoft-azure-key-vault
      sources:
      - https://raw.githubusercontent.com/grafana/grafana/main/go.mod
      status: profiled
      tags:
      - Certificates
      - Cloud Security
      - Cryptography
      - Key Management
      tier: observed
      url: /providers/microsoft-azure-key-vault/
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - Grafana
      band: thin
      in_catalog: true
      kin_score: 29.7
      mcp:
        source: https://github.com/hashicorp/vault-mcp-server
        status: verified
      name: hashicorp/vault/api
      slug: hvault
      sources:
      - https://raw.githubusercontent.com/grafana/grafana/main/go.mod
      status: profiled
      tags:
      - Encryption
      - Identity
      - Infrastructure
      - Secrets Management
      tier: observed
      url: /providers/hvault/
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
      - Gatus
      - Uptime Kuma
      band: exemplar
      in_catalog: true
      kin_score: 84.0
      mcp: *id007
      name: SendGrid
      slug: sendgrid
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-ready
      agent_readiness: 49.8
      apps:
      - Gatus
      - Uptime Kuma
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        source: https://resend.com/docs/mcp-server
        status: verified
      name: Resend
      slug: resend
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Developer Tools
      - Email
      - Marketing Email
      - Transactional Email
      tier: observed
      url: /providers/resend/
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - Gatus
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        status: none
      name: Amazon SES
      slug: amazon-ses
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
    - agent_band: agent-ready
      agent_readiness: 56.4
      apps:
      - Uptime Kuma
      band: exemplar
      in_catalog: true
      kin_score: 81.3
      mcp:
        source: https://developers.brevo.com/docs/mcp-protocol
        status: verified
      name: Brevo
      slug: brevo
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Email Marketing
      - Marketing
      - Marketing Automation
      - Transactional Email
      tier: observed
      url: /providers/brevo/
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
      - Datadog
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: *id009
      name: GitHub
      slug: github
      sources:
      - https://docs.datadoghq.com/integrations/github/
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
      status: profiled
      tags: *id010
      tier: observed
      url: /providers/github/
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp: *id011
      name: GitLab
      slug: gitlab
      sources:
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
      status: profiled
      tags: *id012
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 71.9
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Bitbucket
      slug: bitbucket
      sources:
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
      status: profiled
      tags:
      - Atlassian
      - CI/CD
      - Code Collaboration
      - Code Review
      tier: observed
      url: /providers/bitbucket/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Sentry
      band: developing
      in_catalog: true
      kin_score: 45.5
      mcp:
        source: https://github.com/perforce/p4mcp-server
        status: verified
      name: Perforce
      slug: perforce
      sources:
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
      status: profiled
      tags:
      - Automation
      - DevOps
      - Project Management
      - Version Control
      tier: observed
      url: /providers/perforce/
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
      - Grafana
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: cloud.google.com/go/storage
      slug: gcp-cloud-storage
      sources:
      - https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
      - https://raw.githubusercontent.com/grafana/grafana/main/go.mod
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Grafana
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: aws-sdk-go-v2/service/s3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/grafana/grafana/main/go.mod
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Grafana
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: azure-sdk-for-go storage/azblob
      slug: microsoft-azure-blob-storage
      sources:
      - https://raw.githubusercontent.com/grafana/grafana/main/go.mod
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Gatus
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: observed
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 35.7
      apps:
      - Gatus
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        source: https://docs.n8n.io/advanced-ai/accessing-n8n-mcp-server/
        status: verified
      name: n8n
      slug: n8n
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Integration
      - Workflows
      tier: observed
      url: /providers/n8n/
    - agent_band: agent-ready
      agent_readiness: 42.4
      apps:
      - Gatus
      band: emerging
      in_catalog: true
      kin_score: 24.1
      mcp:
        source: https://github.com/IFTTT/ifttt-plugins
        status: verified
      name: IFTTT
      slug: ifttt
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      status: profiled
      tags:
      - Automation
      - No-Code
      - Webhook
      - iPaaS
      tier: observed
      url: /providers/ifttt/
  - capability:
      attribution: API Evangelist extension
      id: AE-200
      key: AE-200
      name: Home, Device & Consumer IoT
      url: /capabilities/home-device-consumer-iot/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 5.6
      apps:
      - Gatus
      - Uptime Kuma
      band: thin
      in_catalog: true
      kin_score: 34.5
      mcp:
        source: https://www.home-assistant.io/integrations/mcp_server/
        status: verified
      name: Home Assistant
      slug: home-assistant
      sources:
      - https://github.com/TwiN/gatus/tree/master/alerting/provider
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Community
      - Home Automation
      - IoT
      - Open Source
      tier: observed
      url: /providers/home-assistant/
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp: *id013
      name: boto3
      slug: amazon-web-services
      sources:
      - https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
      status: profiled
      tags: *id014
      tier: observed
      url: /providers/amazon-web-services/
    - agent_band: agent-ready
      agent_readiness: 39.3
      apps:
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 66.7
      mcp:
        status: none
      name: google-cloud-build
      slug: google-cloud-build
      sources:
      - https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
      status: profiled
      tags:
      - Build Automation
      - CI/CD
      - Container Build
      - Continuous Delivery
      tier: observed
      url: /providers/google-cloud-build/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SQS
      slug: amazon-sqs
      sources:
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations/data_forwarding
      status: profiled
      tags:
      - Amazon Web Services
      - Cloud
      - Distributed Systems
      - Messaging
      tier: observed
      url: /providers/amazon-sqs/
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - Sentry
      band: strong
      in_catalog: true
      kin_score: 64.1
      mcp:
        source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
        status: verified
      name: google-cloud-pubsub
      slug: google-cloud-pubsub
      sources:
      - https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
      status: profiled
      tags:
      - Event-Driven
      - Google Cloud
      - Messaging
      - Pub/Sub
      tier: observed
      url: /providers/google-cloud-pubsub/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.3
      apps:
      - Sentry
      band: strong
      in_catalog: true
      kin_score: 65.5
      mcp:
        source: https://docs.cloud.google.com/bigtable/docs/use-bigtable-mcp
        status: verified
      name: google-cloud-bigtable
      slug: google-cloud-bigtable
      sources:
      - https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
      status: profiled
      tags:
      - Bigtable
      - Database
      - Google Cloud
      - NoSQL
      tier: observed
      url: /providers/google-cloud-bigtable/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - Sentry
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/googleapis/mcp-toolbox
        status: verified
      name: google-cloud-spanner
      slug: google-cloud-spanner
      sources:
      - https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
      status: profiled
      tags:
      - Database
      - Distributed
      - Google Cloud
      - Relational
      tier: observed
      url: /providers/google-cloud-spanner/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - Sentry
      band: thin
      in_catalog: true
      kin_score: 31.5
      mcp:
        status: none
      name: maxminddb
      slug: maxmind
      sources:
      - https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
      status: profiled
      tags:
      - Fraud Prevention
      - Geolocation
      - IP Intelligence
      - Risk Scoring
      tier: observed
      url: /providers/maxmind/
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
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp: *id015
      name: stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
      status: profiled
      tags: *id016
      tier: observed
      url: /providers/stripe/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Sentry
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations/data_forwarding
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Uptime Kuma
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://github.com/louislam/uptime-kuma/tree/master/server/notification-providers
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: observed
      url: /providers/google-sheets/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.10
      key: AE-100.70.10
      name: Coding Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp: *id017
      name: Claude Code
      slug: anthropic
      sources:
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
      status: profiled
      tags: *id018
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-ready
      agent_readiness: 52.4
      apps:
      - Sentry
      band: exemplar
      in_catalog: true
      kin_score: 74.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub Copilot
      slug: github-copilot
      sources:
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Code Generation
      - Code Review
      tier: observed
      url: /providers/github-copilot/
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Sentry
      band: strong
      in_catalog: true
      kin_score: 60.0
      mcp:
        status: none
      name: Cursor
      slug: cursor
      sources:
      - https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Code Editor
      - Developer Tools
      tier: observed
      url: /providers/cursor/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Grafana
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: *id019
      name: openai/openai-go/v3
      slug: openai
      sources:
      - https://raw.githubusercontent.com/grafana/grafana/main/go.mod
      status: profiled
      tags: *id020
      tier: observed
      url: /providers/openai/
    - agent_band: agent-native
      agent_readiness: 48.3
      apps:
      - Grafana
      band: strong
      in_catalog: true
      kin_score: 64.3
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: aws-sdk-go-v2/service/bedrockruntime
      slug: amazon-bedrock
      sources:
      - https://raw.githubusercontent.com/grafana/grafana/main/go.mod
      status: profiled
      tags:
      - Amazon Web Services
      - Artificial Intelligence
      - Foundation Models
      - Generative AI
      tier: observed
      url: /providers/amazon-bedrock/
    - agent_band: agent-ready
      agent_readiness: 42.2
      apps:
      - Grafana
      band: strong
      in_catalog: true
      kin_score: 63.2
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: cloud.google.com/go/aiplatform
      slug: google-vertex-ai
      sources:
      - https://raw.githubusercontent.com/grafana/grafana/main/go.mod
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - Google Cloud
      - Machine Learning
      tier: observed
      url: /providers/google-vertex-ai/
  layer: agent
summary:
  coverage_pct: 99.1
  declared_only: 9
  distinct_providers: 113
  in_catalog: 112
  mcp:
    documented: 1
    none: 38
    unchecked: 1
    verified: 70
  mcp_verified: 70
  mean_kin_score: 53.1
  observed: 104
  queued: 1
  reference_apps: 7
title: 'Observability, Monitoring & Status Pages: application blueprint'
---
