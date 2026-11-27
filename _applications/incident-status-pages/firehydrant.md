---
app: FireHydrant
app_slug: firehydrant
app_url: https://firehydrant.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2630.30
  key: customer-impacting-incident-management
  layer: domain
  name: Customer-Impacting Incident Management
  providers:
  - Statuspage.io
  url: /capabilities/customer-impacting-incident-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.30
  key: it-service-management
  layer: domain
  name: IT Service Management
  providers:
  - Freshservice
  - ServiceNow
  url: /capabilities/it-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.30
  key: incident-response-management
  layer: domain
  name: Incident Response Management
  providers:
  - Opsgenie
  - PagerDuty
  - VictorOps
  url: /capabilities/incident-response-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-942
  key: AE-942
  layer: domain
  name: Internal Developer Portals & Software Catalogs
  providers:
  - Cortex
  url: /capabilities/it-service-management/
  via_parent: IT Service Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: domain
  name: Observability Management
  providers:
  - Alertmanager
  - AWS
  - AWS CloudWatch
  - Bugsnag
  - Checkly
  - Datadog
  - Grafana
  - Honeycomb
  - New Relic
  - Sentry
  - Site24x7
  - Stackdriver
  - StatusCake
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: domain
  name: Team Chat Bridging
  providers:
  - Microsoft Teams
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Google Meet
  - Webex
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.30.30
  key: AE-170.30.30
  layer: common
  name: Avatars, GIFs & Stickers
  providers:
  - Giphy
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: Turbo EA
  id: BC-910
  key: change-management
  layer: common
  name: Change Management
  providers:
  - CircleCI
  - GitHub
  - Kubernetes
  - Terraform
  url: /capabilities/change-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - Okta
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - Jira Cloud / Server
  - Linear
  - Shortcut
  url: /capabilities/project-management/
  via_parent: null
category:
  id: incident-status-pages
  name: Incident Management & Status Pages
  url: /applications/incident-status-pages/
counts:
  declared: 35
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://firehydrant.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 35.9
    mcp: &id001
      source: https://github.com/prometheus/prometheus-mcp
      status: verified
    slug: prometheus-io
    status: profiled
    tags: &id002
    - Metrics
    - Monitoring
    - Observability
    - Prometheus
    url: /providers/prometheus-io/
  layer: domain
  name: Alertmanager
  provider: prometheus-io
  says: lists Alertmanager as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
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
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id004
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: domain
  name: AWS
  provider: amazon-web-services
  says: lists AWS as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
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
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-cloudwatch
    status: profiled
    tags: &id006
    - Amazon Web Services
    - CloudWatch
    - Monitoring
    - Observability
    url: /providers/amazon-cloudwatch/
  layer: domain
  name: AWS CloudWatch
  provider: amazon-cloudwatch
  says: lists AWS CloudWatch as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 76.3
    mcp: &id007
      source: https://github.com/SmartBear/smartbear-mcp
      status: verified
    slug: bugsnag
    status: profiled
    tags: &id008
    - Application Performance Monitoring
    - Error Monitoring
    - Monitoring
    - Observability
    url: /providers/bugsnag/
  layer: domain
  name: Bugsnag
  provider: bugsnag
  says: lists Bugsnag as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
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
    agent_readiness: 61.2
    band: exemplar
    in_catalog: true
    kin_score: 76.2
    mcp: &id009
      source: https://www.checklyhq.com/docs/guides/communicate-availability.md
      status: documented
    slug: checkly
    status: profiled
    tags: &id010
    - Monitoring
    - Observability
    - Synthetic Monitoring
    - Testing
    url: /providers/checkly/
  layer: domain
  name: Checkly
  provider: checkly
  says: lists Checkly as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-910
    key: change-management
    name: Change Management
    url: /capabilities/change-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 73.5
    mcp: &id011
      source: https://github.com/CircleCI-Public/mcp-server-circleci
      status: verified
    slug: circleci
    status: profiled
    tags: &id012
    - CI/CD
    - Continuous Deployment
    - Continuous Integration
    - DevOps
    url: /providers/circleci/
  layer: common
  name: CircleCI
  provider: circleci
  says: lists CircleCI as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-942
    key: AE-942
    name: Internal Developer Portals & Software Catalogs
    url: /capabilities/it-service-management/
    via_parent: IT Service Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.4
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id013
      status: unknown
    slug: cortex-idp
    status: profiled
    tags: &id014
    - Developer Experience
    - Internal Developer Portal
    - Service Catalog
    - Software Catalog
    url: /providers/cortex-idp/
  layer: domain
  name: Cortex
  provider: cortex-idp
  says: lists Cortex as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
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
    mcp: &id015
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id016
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: domain
  name: Datadog
  provider: datadog
  says: lists Datadog as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.30
    key: it-service-management
    name: IT Service Management
    url: /capabilities/it-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.4
    band: thin
    in_catalog: true
    kin_score: 35.8
    mcp: &id017
      status: none
    slug: freshservice
    status: profiled
    tags: &id018
    - Asset Management
    - Help Desk
    - ITSM
    - Ticketing
    url: /providers/freshservice/
  layer: domain
  name: Freshservice
  provider: freshservice
  says: lists Freshservice as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: strong
    in_catalog: true
    kin_score: 56.0
    mcp: &id019
      status: none
    slug: giphy
    status: profiled
    tags: &id020
    - GIFs
    - Media
    - Photography
    - Stickers
    url: /providers/giphy/
  layer: common
  name: Giphy
  provider: giphy
  says: lists Giphy as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-910
    key: change-management
    name: Change Management
    url: /capabilities/change-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id021
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id022
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://firehydrant.com/integrations/
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
    agent_readiness: 34.9
    band: developing
    in_catalog: true
    kin_score: 52.2
    mcp: &id023
      status: none
    slug: google-meet
    status: profiled
    tags: &id024
    - Google
    - Google Workspace
    - Meetings
    - Recording
    url: /providers/google-meet/
  layer: domain
  name: Google Meet
  provider: google-meet
  says: lists Google Meet as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
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
    agent_readiness: 27.6
    band: strong
    in_catalog: true
    kin_score: 66.0
    mcp: &id025
      source: https://github.com/grafana/mcp-grafana
      status: verified
    slug: grafana-com
    status: profiled
    tags: &id026
    - Dashboards
    - Logs
    - Monitoring
    - Observability
    url: /providers/grafana-com/
  layer: domain
  name: Grafana
  provider: grafana-com
  says: lists Grafana as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
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
    agent_readiness: 55.5
    band: exemplar
    in_catalog: true
    kin_score: 71.6
    mcp: &id027
      source: https://docs.honeycomb.io/integrations/mcp/
      status: verified
    slug: honeycomb
    status: profiled
    tags: &id028
    - Analytics
    - Data Management
    - Observability
    - Telemetry
    url: /providers/honeycomb/
  layer: domain
  name: Honeycomb
  provider: honeycomb
  says: lists Honeycomb as an integration
  source: https://firehydrant.com/integrations/
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
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id029
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id030
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: common
  name: Jira Cloud / Server
  provider: jira
  says: lists Jira Cloud / Server as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-910
    key: change-management
    name: Change Management
    url: /capabilities/change-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.6
    band: developing
    in_catalog: true
    kin_score: 48.7
    mcp: &id031
      status: none
    slug: kubernetes
    status: profiled
    tags: &id032
    - Automation
    - CNCF
    - Cloud-Native
    - Containers
    url: /providers/kubernetes/
  layer: common
  name: Kubernetes
  provider: kubernetes
  says: lists Kubernetes as an integration
  source: https://firehydrant.com/integrations/
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
    agent_readiness: 35.2
    band: developing
    in_catalog: true
    kin_score: 39.6
    mcp: &id033
      source: https://linear.app/docs/mcp
      status: verified
    slug: linear-app
    status: profiled
    tags: &id034
    - Issue Tracking
    - Productivity
    - Project Management
    - Software-as-a-Service
    url: /providers/linear-app/
  layer: common
  name: Linear
  provider: linear-app
  says: lists Linear as an integration
  source: https://firehydrant.com/integrations/
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
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id035
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id036
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
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
  says: lists New Relic as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.1
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id039
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id040
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: common
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
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
  says: lists Opsgenie as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
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
  says: lists PagerDuty as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
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
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id045
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id046
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: domain
  name: Sentry
  provider: sentry-system
  says: lists Sentry as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.30
    key: it-service-management
    name: IT Service Management
    url: /capabilities/it-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.3
    band: strong
    in_catalog: true
    kin_score: 61.9
    mcp: &id047
      status: none
    slug: servicenow
    status: profiled
    tags: &id048
    - Automation
    - Cloud Services
    - Digital Workflows
    - ServiceNow
    url: /providers/servicenow/
  layer: domain
  name: ServiceNow
  provider: servicenow
  says: lists ServiceNow as an integration
  source: https://firehydrant.com/integrations/
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
    agent_readiness: 53.5
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id049
      source: https://github.com/useshortcut/mcp-server-shortcut
      status: verified
    slug: shortcut-software
    status: profiled
    tags: &id050
    - Agile
    - Company
    - Issue Tracking
    - Project Management
    url: /providers/shortcut-software/
  layer: common
  name: Shortcut
  provider: shortcut-software
  says: lists Shortcut as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
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
    agent_readiness: 24.7
    band: developing
    in_catalog: true
    kin_score: 40.7
    mcp: &id051
      source: https://www.site24x7.com/help/aiops/mcp-server.html
      status: documented
    slug: site24x7
    status: profiled
    tags: &id052
    - Infrastructure
    - Monitoring
    - Observability
    - Uptime
    url: /providers/site24x7/
  layer: domain
  name: Site24x7
  provider: site24x7
  says: lists Site24x7 as an integration
  source: https://firehydrant.com/integrations/
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
    mcp: &id053
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id054
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
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
    mcp: &id055
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-cloud-monitoring
    status: profiled
    tags: &id056
    - Alerting
    - Dashboards
    - Google Cloud
    - Metrics
    url: /providers/google-cloud-monitoring/
  layer: domain
  name: Stackdriver
  provider: google-cloud-monitoring
  says: lists Stackdriver as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
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
    agent_readiness: 17.6
    band: developing
    in_catalog: true
    kin_score: 44.6
    mcp: &id057
      status: unchecked
    slug: statuscake
    status: profiled
    tags: &id058
    - Company
    - Monitoring
    - Performance
    - Uptime
    url: /providers/statuscake/
  layer: domain
  name: StatusCake
  provider: statuscake
  says: lists StatusCake as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2630.30
    key: customer-impacting-incident-management
    name: Customer-Impacting Incident Management
    url: /capabilities/customer-impacting-incident-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.7
    band: thin
    in_catalog: true
    kin_score: 36.0
    mcp: &id059
      status: none
    slug: statuspage
    status: profiled
    tags: &id060
    - Incident Communication
    - Incident Management
    - Status Pages
    - Uptime
    url: /providers/statuspage/
  layer: domain
  name: Statuspage.io
  provider: statuspage
  says: lists Statuspage.io as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-910
    key: change-management
    name: Change Management
    url: /capabilities/change-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.7
    band: developing
    in_catalog: true
    kin_score: 42.5
    mcp: &id061
      source: https://github.com/hashicorp/terraform-mcp-server
      status: verified
    slug: terraform
    status: profiled
    tags: &id062
    - Cloud Infrastructure
    - DevOps
    - Infrastructure as Code
    - Open Source
    url: /providers/terraform/
  layer: common
  name: Terraform
  provider: terraform
  says: lists Terraform as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
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
    mcp: &id063
      status: none
    slug: victorops
    status: profiled
    tags: &id064
    - Alerting
    - DevOps
    - Incident Management
    - On-Call
    url: /providers/victorops/
  layer: domain
  name: VictorOps
  provider: victorops
  says: lists VictorOps as an integration
  source: https://firehydrant.com/integrations/
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
    agent_readiness: 61.8
    band: strong
    in_catalog: true
    kin_score: 66.1
    mcp: &id065
      source: https://github.com/WebexSamples/webex-messaging-mcp-server
      status: verified
    slug: webex
    status: profiled
    tags: &id066
    - Calling
    - Collaboration
    - Communications
    - Enterprise
    url: /providers/webex/
  layer: domain
  name: Webex
  provider: webex
  says: lists Webex as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
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
    mcp: &id067
      status: none
    slug: zendesk
    status: profiled
    tags: &id068
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: common
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://firehydrant.com/integrations/
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
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id069
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id070
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: domain
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://firehydrant.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/incident-status-pages/firehydrant/
providers:
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 35.9
  mcp: *id001
  name: Alertmanager
  slug: prometheus-io
  status: profiled
  tags: *id002
  url: /providers/prometheus-io/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id003
  name: AWS
  slug: amazon-web-services
  status: profiled
  tags: *id004
  url: /providers/amazon-web-services/
- agent_band: agent-native
  agent_readiness: 43.4
  band: exemplar
  in_catalog: true
  kin_score: 77.4
  mcp: *id005
  name: AWS CloudWatch
  slug: amazon-cloudwatch
  status: profiled
  tags: *id006
  url: /providers/amazon-cloudwatch/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 76.3
  mcp: *id007
  name: Bugsnag
  slug: bugsnag
  status: profiled
  tags: *id008
  url: /providers/bugsnag/
- agent_band: agent-ready
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 76.2
  mcp: *id009
  name: Checkly
  slug: checkly
  status: profiled
  tags: *id010
  url: /providers/checkly/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 73.5
  mcp: *id011
  name: CircleCI
  slug: circleci
  status: profiled
  tags: *id012
  url: /providers/circleci/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id013
  name: Cortex
  slug: cortex-idp
  status: profiled
  tags: *id014
  url: /providers/cortex-idp/
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id015
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id016
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: thin
  in_catalog: true
  kin_score: 35.8
  mcp: *id017
  name: Freshservice
  slug: freshservice
  status: profiled
  tags: *id018
  url: /providers/freshservice/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: strong
  in_catalog: true
  kin_score: 56.0
  mcp: *id019
  name: Giphy
  slug: giphy
  status: profiled
  tags: *id020
  url: /providers/giphy/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id021
  name: GitHub
  slug: github
  status: profiled
  tags: *id022
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: developing
  in_catalog: true
  kin_score: 52.2
  mcp: *id023
  name: Google Meet
  slug: google-meet
  status: profiled
  tags: *id024
  url: /providers/google-meet/
- agent_band: agent-aware
  agent_readiness: 27.6
  band: strong
  in_catalog: true
  kin_score: 66.0
  mcp: *id025
  name: Grafana
  slug: grafana-com
  status: profiled
  tags: *id026
  url: /providers/grafana-com/
- agent_band: agent-ready
  agent_readiness: 55.5
  band: exemplar
  in_catalog: true
  kin_score: 71.6
  mcp: *id027
  name: Honeycomb
  slug: honeycomb
  status: profiled
  tags: *id028
  url: /providers/honeycomb/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id029
  name: Jira Cloud / Server
  slug: jira
  status: profiled
  tags: *id030
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 32.6
  band: developing
  in_catalog: true
  kin_score: 48.7
  mcp: *id031
  name: Kubernetes
  slug: kubernetes
  status: profiled
  tags: *id032
  url: /providers/kubernetes/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: developing
  in_catalog: true
  kin_score: 39.6
  mcp: *id033
  name: Linear
  slug: linear-app
  status: profiled
  tags: *id034
  url: /providers/linear-app/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id035
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id036
  url: /providers/microsoft-teams/
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
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id039
  name: Okta
  slug: okta
  status: profiled
  tags: *id040
  url: /providers/okta/
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
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id045
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id046
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: strong
  in_catalog: true
  kin_score: 61.9
  mcp: *id047
  name: ServiceNow
  slug: servicenow
  status: profiled
  tags: *id048
  url: /providers/servicenow/
- agent_band: agent-ready
  agent_readiness: 53.5
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id049
  name: Shortcut
  slug: shortcut-software
  status: profiled
  tags: *id050
  url: /providers/shortcut-software/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: developing
  in_catalog: true
  kin_score: 40.7
  mcp: *id051
  name: Site24x7
  slug: site24x7
  status: profiled
  tags: *id052
  url: /providers/site24x7/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id053
  name: Slack
  slug: slack
  status: profiled
  tags: *id054
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 37.2
  band: strong
  in_catalog: true
  kin_score: 66.4
  mcp: *id055
  name: Stackdriver
  slug: google-cloud-monitoring
  status: profiled
  tags: *id056
  url: /providers/google-cloud-monitoring/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: developing
  in_catalog: true
  kin_score: 44.6
  mcp: *id057
  name: StatusCake
  slug: statuscake
  status: profiled
  tags: *id058
  url: /providers/statuscake/
- agent_band: agent-aware
  agent_readiness: 19.7
  band: thin
  in_catalog: true
  kin_score: 36.0
  mcp: *id059
  name: Statuspage.io
  slug: statuspage
  status: profiled
  tags: *id060
  url: /providers/statuspage/
- agent_band: agent-ready
  agent_readiness: 29.7
  band: developing
  in_catalog: true
  kin_score: 42.5
  mcp: *id061
  name: Terraform
  slug: terraform
  status: profiled
  tags: *id062
  url: /providers/terraform/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.1
  mcp: *id063
  name: VictorOps
  slug: victorops
  status: profiled
  tags: *id064
  url: /providers/victorops/
- agent_band: agent-ready
  agent_readiness: 61.8
  band: strong
  in_catalog: true
  kin_score: 66.1
  mcp: *id065
  name: Webex
  slug: webex
  status: profiled
  tags: *id066
  url: /providers/webex/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id067
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id068
  url: /providers/zendesk/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id069
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id070
  url: /providers/zoom/
siblings:
- name: Atlassian Statuspage
  rows: 14
  url: /applications/incident-status-pages/atlassian-statuspage/
- name: Cachet
  rows: 2
  url: /applications/incident-status-pages/cachet/
- name: Dispatch (Netflix)
  rows: 16
  url: /applications/incident-status-pages/dispatch-netflix/
- name: GoAlert
  rows: 8
  url: /applications/incident-status-pages/goalert/
- name: Grafana OnCall
  rows: 14
  url: /applications/incident-status-pages/grafana-oncall/
- name: incident.io
  rows: 20
  url: /applications/incident-status-pages/incident-io/
- name: PagerDuty
  rows: 10
  url: /applications/incident-status-pages/pagerduty/
sitemap: true
title: 'FireHydrant: Incident Management & Status Pages reference app'
---
