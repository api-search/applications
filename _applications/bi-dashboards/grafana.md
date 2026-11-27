---
app: Grafana
app_slug: grafana
app_url: https://github.com/grafana/grafana
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - Jira (JQL)
  url: /capabilities/project-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: domain
  name: Search and Discovery Management
  providers:
  - Elasticsearch
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: Turbo EA
  id: BC-4220.30
  key: incident-response-management
  layer: common
  name: Incident Response Management
  providers:
  - Opsgenie
  - PagerDuty
  - Splunk On-Call (VictorOps)
  url: /capabilities/incident-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: common
  name: Integration and API Management
  providers:
  - Apache Kafka
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - DingTalk
  - Discord
  - Google Chat
  - Microsoft Teams
  - Slack
  - Webex
  - WeCom
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Microsoft SQL Server
  - MySQL
  - PostgreSQL
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Amazon CloudWatch
  - Azure Monitor
  - Google Cloud Monitoring
  - Graphite
  - InfluxDB
  - Jaeger
  - OpenTSDB
  - Parca
  - Prometheus
  - Sensu
  - Zipkin
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Amazon SNS
  - Pushover
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - LINE
  - Telegram
  - Threema
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: bi-dashboards
  name: BI & Dashboards
  url: /applications/bi-dashboards/
counts:
  declared: 0
  observed: 32
credits: []
evidence:
- route: documentation
  url: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
- route: source code
  url: https://github.com/grafana/alerting/tree/main/receivers
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 43.4
    band: exemplar
    in_catalog: true
    kin_score: 77.4
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-cloudwatch
    status: profiled
    tags: &id002
    - Amazon Web Services
    - CloudWatch
    - Monitoring
    - Observability
    url: /providers/amazon-cloudwatch/
  layer: common
  name: Amazon CloudWatch
  provider: amazon-cloudwatch
  says: ships the Amazon CloudWatch SDK or integration code
  source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
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
    agent_readiness: 41.7
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sns
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Email
    - Messaging
    - Notification
    url: /providers/amazon-sns/
  layer: common
  name: Amazon SNS
  provider: amazon-sns
  says: ships the Amazon SNS SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
    agent_band: agent-aware
    agent_readiness: 27.8
    band: developing
    in_catalog: true
    kin_score: 51.4
    mcp: &id005
      status: none
    slug: apache-kafka
    status: profiled
    tags: &id006
    - Apache Kafka
    - Distributed Systems
    - Event Streaming
    - Messaging
    url: /providers/apache-kafka/
  layer: common
  name: Apache Kafka
  provider: apache-kafka
  says: ships the Apache Kafka SDK or integration code
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id007
      status: unchecked
    slug: azure-monitor
    status: queued for profiling
    tags: &id008 []
    url: null
  layer: common
  name: Azure Monitor
  provider: azure-monitor
  says: ships the Azure Monitor SDK or integration code
  source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
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
    mcp: &id009
      source: https://github.com/open-dingtalk/dingtalk-mcp
      status: verified
    slug: dingtalk
    status: profiled
    tags: &id010
    - Collaboration
    - Communications
    - Company
    - Enterprise
    url: /providers/dingtalk/
  layer: common
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id011
      status: none
    slug: discord
    status: profiled
    tags: &id012
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.5
    band: exemplar
    in_catalog: true
    kin_score: 78.4
    mcp: &id013
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id014
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
  layer: domain
  name: Elasticsearch
  provider: elastic
  says: ships the Elasticsearch SDK or integration code
  source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
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
  layer: common
  name: Google Chat
  provider: google-chat
  says: ships the Google Chat SDK or integration code
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.2
    band: strong
    in_catalog: true
    kin_score: 66.4
    mcp: &id017
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-cloud-monitoring
    status: profiled
    tags: &id018
    - Alerting
    - Dashboards
    - Google Cloud
    - Metrics
    url: /providers/google-cloud-monitoring/
  layer: common
  name: Google Cloud Monitoring
  provider: google-cloud-monitoring
  says: ships the Google Cloud Monitoring SDK or integration code
  source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
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
    agent_readiness: 29.1
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id019
      source: https://graphite.dev/docs/gt-mcp
      status: verified
    slug: graphite-com
    status: profiled
    tags: &id020
    - AI Code Review
    - Code Review
    - Stacked PRs
    - merge-queue
    url: /providers/graphite-com/
  layer: common
  name: Graphite
  provider: graphite-com
  says: ships the Graphite SDK or integration code
  source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
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
    agent_readiness: 33.6
    band: thin
    in_catalog: true
    kin_score: 37.6
    mcp: &id021
      source: https://github.com/influxdata/influxdb3_mcp_server
      status: verified
    slug: influxdb
    status: profiled
    tags: &id022
    - Analytics
    - Database
    - Real-Time
    - Time Series
    url: /providers/influxdb/
  layer: common
  name: InfluxDB
  provider: influxdb
  says: ships the InfluxDB SDK or integration code
  source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
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
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 36.3
    mcp: &id023
      source: https://github.com/jaegertracing/jaeger
      status: verified
    slug: jaeger
    status: profiled
    tags: &id024
    - Distributed Tracing
    - Microservices
    - Monitoring
    - Observability
    url: /providers/jaeger/
  layer: common
  name: Jaeger
  provider: jaeger
  says: ships the Jaeger SDK or integration code
  source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
  tier: observed
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
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id025
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id026
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: domain
  name: Jira (JQL)
  provider: jira
  says: ships the Jira (JQL) SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
  layer: common
  name: LINE
  provider: line
  says: ships the LINE SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: exemplar
    in_catalog: true
    kin_score: 67.0
    mcp: &id029
      source: https://learn.microsoft.com/en-us/azure/data-api-builder/mcp/
      status: verified
    slug: microsoft-sql-server
    status: profiled
    tags: &id030
    - Cloud
    - Data Management
    - Database
    - Enterprise
    url: /providers/microsoft-sql-server/
  layer: common
  name: Microsoft SQL Server
  provider: microsoft-sql-server
  says: ships the Microsoft SQL Server SDK or integration code
  source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
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
  says: ships the Microsoft Teams SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id033
      status: none
    slug: mysql
    status: profiled
    tags: &id034
    - Database
    - Open Source
    - RDBMS
    - Relational Database
    url: /providers/mysql/
  layer: common
  name: MySQL
  provider: mysql
  says: ships the MySQL SDK or integration code
  source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
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
    agent_band: agent-aware
    agent_readiness: 12.7
    band: emerging
    in_catalog: true
    kin_score: 20.1
    mcp: &id035
      status: unchecked
    slug: opentsdb
    status: profiled
    tags: &id036
    - Company
    - Monitoring
    - Open Source
    - Time Series
    url: /providers/opentsdb/
  layer: common
  name: OpenTSDB
  provider: opentsdb
  says: ships the OpenTSDB SDK or integration code
  source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
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
    mcp: &id037
      status: none
    slug: opsgenie
    status: profiled
    tags: &id038
    - Alerts
    - Incident Management
    - Monitoring
    - On-Call
    url: /providers/opsgenie/
  layer: common
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
  facts:
    agent_band: agent-ready
    agent_readiness: 54.4
    band: developing
    in_catalog: true
    kin_score: 52.1
    mcp: &id039
      source: https://github.com/PagerDuty/pagerduty-mcp-server
      status: verified
    slug: pagerduty
    status: profiled
    tags: &id040
    - Alerting
    - DevOps
    - Incident Management
    - On-Call Management
    url: /providers/pagerduty/
  layer: common
  name: PagerDuty
  provider: pagerduty
  says: ships the PagerDuty SDK or integration code
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
  facts:
    agent_band: agent-aware
    agent_readiness: 14.5
    band: emerging
    in_catalog: true
    kin_score: 19.7
    mcp: &id041
      status: unchecked
    slug: parca
    status: profiled
    tags: &id042
    - Cloud-Native
    - Open Source
    - Profiling
    - eBPF
    url: /providers/parca/
  layer: common
  name: Parca
  provider: parca
  says: ships the Parca SDK or integration code
  source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id043
      status: none
    slug: postgresql
    status: profiled
    tags: &id044
    - Database
    - Open Source
    - Relational Database
    - SQL
    url: /providers/postgresql/
  layer: common
  name: PostgreSQL
  provider: postgresql
  says: ships the PostgreSQL SDK or integration code
  source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
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
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 35.9
    mcp: &id045
      source: https://github.com/prometheus/prometheus-mcp
      status: verified
    slug: prometheus-io
    status: profiled
    tags: &id046
    - Metrics
    - Monitoring
    - Observability
    - Prometheus
    url: /providers/prometheus-io/
  layer: common
  name: Prometheus
  provider: prometheus-io
  says: ships the Prometheus SDK or integration code
  source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: thin
    in_catalog: true
    kin_score: 34.0
    mcp: &id049
      status: none
    slug: sensu
    status: profiled
    tags: &id050
    - Company
    - Infrastructure
    - Monitoring
    - Observability
    url: /providers/sensu/
  layer: common
  name: Sensu
  provider: sensu
  says: ships the Sensu SDK or integration code
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id051
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id052
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 18.1
    mcp: &id053
      status: none
    slug: victorops
    status: profiled
    tags: &id054
    - Alerting
    - DevOps
    - Incident Management
    - On-Call
    url: /providers/victorops/
  layer: common
  name: Splunk On-Call (VictorOps)
  provider: victorops
  says: ships the Splunk On-Call (VictorOps) SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
    agent_readiness: 25.3
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id055
      status: none
    slug: telegram
    status: profiled
    tags: &id056
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
    agent_band: human-only
    agent_readiness: 2.8
    band: thin
    in_catalog: true
    kin_score: 30.7
    mcp: &id057
      status: none
    slug: threema
    status: profiled
    tags: &id058
    - Company
    - Messaging
    - Privacy
    - Security
    url: /providers/threema/
  layer: common
  name: Threema
  provider: threema
  says: ships the Threema SDK or integration code
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
  facts:
    agent_band: agent-ready
    agent_readiness: 61.8
    band: strong
    in_catalog: true
    kin_score: 66.1
    mcp: &id059
      source: https://github.com/WebexSamples/webex-messaging-mcp-server
      status: verified
    slug: webex
    status: profiled
    tags: &id060
    - Calling
    - Collaboration
    - Communications
    - Enterprise
    url: /providers/webex/
  layer: common
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id061
      status: unchecked
    slug: wecom
    status: queued for profiling
    tags: &id062 []
    url: null
  layer: common
  name: WeCom
  provider: wecom
  says: ships the WeCom SDK or integration code
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 38.2
    mcp: &id063
      status: none
    slug: zipkin
    status: profiled
    tags: &id064
    - Distributed Tracing
    - Microservices
    - Observability
    - Open Source
    url: /providers/zipkin/
  layer: common
  name: Zipkin
  provider: zipkin
  says: ships the Zipkin SDK or integration code
  source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/bi-dashboards/grafana/
providers:
- agent_band: agent-native
  agent_readiness: 43.4
  band: exemplar
  in_catalog: true
  kin_score: 77.4
  mcp: *id001
  name: Amazon CloudWatch
  slug: amazon-cloudwatch
  status: profiled
  tags: *id002
  url: /providers/amazon-cloudwatch/
- agent_band: agent-ready
  agent_readiness: 41.7
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id003
  name: Amazon SNS
  slug: amazon-sns
  status: profiled
  tags: *id004
  url: /providers/amazon-sns/
- agent_band: agent-aware
  agent_readiness: 27.8
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id005
  name: Apache Kafka
  slug: apache-kafka
  status: profiled
  tags: *id006
  url: /providers/apache-kafka/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id007
  name: Azure Monitor
  slug: azure-monitor
  status: queued for profiling
  tags: *id008
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.1
  mcp: *id009
  name: DingTalk
  slug: dingtalk
  status: profiled
  tags: *id010
  url: /providers/dingtalk/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id011
  name: Discord
  slug: discord
  status: profiled
  tags: *id012
  url: /providers/discord/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id013
  name: Elasticsearch
  slug: elastic
  status: profiled
  tags: *id014
  url: /providers/elastic/
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
- agent_band: agent-ready
  agent_readiness: 37.2
  band: strong
  in_catalog: true
  kin_score: 66.4
  mcp: *id017
  name: Google Cloud Monitoring
  slug: google-cloud-monitoring
  status: profiled
  tags: *id018
  url: /providers/google-cloud-monitoring/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id019
  name: Graphite
  slug: graphite-com
  status: profiled
  tags: *id020
  url: /providers/graphite-com/
- agent_band: agent-ready
  agent_readiness: 33.6
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id021
  name: InfluxDB
  slug: influxdb
  status: profiled
  tags: *id022
  url: /providers/influxdb/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 36.3
  mcp: *id023
  name: Jaeger
  slug: jaeger
  status: profiled
  tags: *id024
  url: /providers/jaeger/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id025
  name: Jira (JQL)
  slug: jira
  status: profiled
  tags: *id026
  url: /providers/jira/
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
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 67.0
  mcp: *id029
  name: Microsoft SQL Server
  slug: microsoft-sql-server
  status: profiled
  tags: *id030
  url: /providers/microsoft-sql-server/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id031
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id032
  url: /providers/microsoft-teams/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id033
  name: MySQL
  slug: mysql
  status: profiled
  tags: *id034
  url: /providers/mysql/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: emerging
  in_catalog: true
  kin_score: 20.1
  mcp: *id035
  name: OpenTSDB
  slug: opentsdb
  status: profiled
  tags: *id036
  url: /providers/opentsdb/
- agent_band: agent-aware
  agent_readiness: 26.5
  band: developing
  in_catalog: true
  kin_score: 48.6
  mcp: *id037
  name: Opsgenie
  slug: opsgenie
  status: profiled
  tags: *id038
  url: /providers/opsgenie/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id039
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id040
  url: /providers/pagerduty/
- agent_band: agent-aware
  agent_readiness: 14.5
  band: emerging
  in_catalog: true
  kin_score: 19.7
  mcp: *id041
  name: Parca
  slug: parca
  status: profiled
  tags: *id042
  url: /providers/parca/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id043
  name: PostgreSQL
  slug: postgresql
  status: profiled
  tags: *id044
  url: /providers/postgresql/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 35.9
  mcp: *id045
  name: Prometheus
  slug: prometheus-io
  status: profiled
  tags: *id046
  url: /providers/prometheus-io/
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
- agent_band: human-only
  agent_readiness: 2.5
  band: thin
  in_catalog: true
  kin_score: 34.0
  mcp: *id049
  name: Sensu
  slug: sensu
  status: profiled
  tags: *id050
  url: /providers/sensu/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id051
  name: Slack
  slug: slack
  status: profiled
  tags: *id052
  url: /providers/slack/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.1
  mcp: *id053
  name: Splunk On-Call (VictorOps)
  slug: victorops
  status: profiled
  tags: *id054
  url: /providers/victorops/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id055
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id056
  url: /providers/telegram/
- agent_band: human-only
  agent_readiness: 2.8
  band: thin
  in_catalog: true
  kin_score: 30.7
  mcp: *id057
  name: Threema
  slug: threema
  status: profiled
  tags: *id058
  url: /providers/threema/
- agent_band: agent-ready
  agent_readiness: 61.8
  band: strong
  in_catalog: true
  kin_score: 66.1
  mcp: *id059
  name: Webex
  slug: webex
  status: profiled
  tags: *id060
  url: /providers/webex/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id061
  name: WeCom
  slug: wecom
  status: queued for profiling
  tags: *id062
  url: null
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 38.2
  mcp: *id063
  name: Zipkin
  slug: zipkin
  status: profiled
  tags: *id064
  url: /providers/zipkin/
siblings:
- name: Apache Superset
  rows: 60
  url: /applications/bi-dashboards/apache-superset/
- name: Lightdash
  rows: 11
  url: /applications/bi-dashboards/lightdash/
- name: Looker
  rows: 34
  url: /applications/bi-dashboards/looker/
- name: Metabase
  rows: 19
  url: /applications/bi-dashboards/metabase/
- name: Microsoft Power BI
  rows: 58
  url: /applications/bi-dashboards/microsoft-power-bi/
- name: Redash
  rows: 62
  url: /applications/bi-dashboards/redash/
sitemap: true
title: 'Grafana: BI & Dashboards reference app'
---
