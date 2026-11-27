---
access: understanding
agent_layer: []
apps:
- anchor: pagerduty
  counts:
    declared: 6
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.pagerduty.android/latest/
  - route: integrations page
    url: https://www.pagerduty.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.pagerduty.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.pagerduty.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Mixpanel
    provider: mixpanel
    says: ships the Mixpanel SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.pagerduty.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.pagerduty.android/latest/
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
    name: Anthropic Claude Connector
    provider: anthropic
    says: lists Anthropic Claude Connector as an integration
    source: https://www.pagerduty.com/integrations/
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
    name: AWS
    provider: amazon-web-services
    says: lists AWS as an integration
    source: https://www.pagerduty.com/integrations/
    tier: declared
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
    says: lists Cursor as an integration
    source: https://www.pagerduty.com/integrations/
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
    name: Datadog
    provider: datadog
    says: lists Datadog as an integration
    source: https://www.pagerduty.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://www.pagerduty.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://www.pagerduty.com/integrations/
    tier: declared
  kind: commercial
  name: PagerDuty
  page: /applications/incident-status-pages/pagerduty/
  slug: pagerduty
  url: https://www.pagerduty.com/
- anchor: incidentio
  counts:
    declared: 20
    observed: 0
  evidence:
  - route: integrations page
    url: https://incident.io/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://incident.io/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2630.30
      key: customer-impacting-incident-management
      name: Customer-Impacting Incident Management
      url: /capabilities/customer-impacting-incident-management/
      via_parent: null
    credit: null
    layer: domain
    name: Atlassian Statuspage
    provider: statuspage
    says: lists Atlassian Statuspage as an integration
    source: https://incident.io/integrations
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
    name: AWS
    provider: amazon-web-services
    says: lists AWS as an integration
    source: https://incident.io/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-942
      key: AE-942
      name: Internal Developer Portals & Software Catalogs
      url: /capabilities/it-service-management/
      via_parent: IT Service Management
    credit: null
    layer: domain
    name: Backstage
    provider: backstage
    says: lists Backstage as an integration
    source: https://incident.io/integrations
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
    name: BigPanda
    provider: bigpanda
    says: lists BigPanda as an integration
    source: https://incident.io/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: ClickUp
    provider: clickup
    says: lists ClickUp as an integration
    source: https://incident.io/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-942
      key: AE-942
      name: Internal Developer Portals & Software Catalogs
      url: /capabilities/it-service-management/
      via_parent: IT Service Management
    credit: null
    layer: domain
    name: Cortex
    provider: cortex-idp
    says: lists Cortex as an integration
    source: https://incident.io/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-910
      key: change-management
      name: Change Management
      url: /capabilities/change-management/
      via_parent: null
    credit: null
    layer: common
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://incident.io/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-910
      key: change-management
      name: Change Management
      url: /capabilities/change-management/
      via_parent: null
    credit: null
    layer: common
    name: GitLab
    provider: gitlab
    says: lists GitLab as an integration
    source: https://incident.io/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://incident.io/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Linear
    provider: linear-app
    says: lists Linear as an integration
    source: https://incident.io/integrations
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
    source: https://incident.io/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-942
      key: AE-942
      name: Internal Developer Portals & Software Catalogs
      url: /capabilities/it-service-management/
      via_parent: IT Service Management
    credit: null
    layer: domain
    name: OpsLevel
    provider: opslevel
    says: lists OpsLevel as an integration
    source: https://incident.io/integrations
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
    source: https://incident.io/integrations
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
    name: Sentry
    provider: sentry-system
    says: lists Sentry as an integration
    source: https://incident.io/integrations
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
    source: https://incident.io/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Shortcut
    provider: shortcut-software
    says: lists Shortcut as an integration
    source: https://incident.io/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://incident.io/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Zendesk
    provider: zendesk
    says: lists Zendesk as an integration
    source: https://incident.io/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://incident.io/integrations
    tier: declared
  kind: commercial
  name: incident.io
  page: /applications/incident-status-pages/incident-io/
  slug: incident-io
  url: https://incident.io/
- anchor: atlassian-statuspage
  counts:
    declared: 14
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.atlassian.com/software/statuspage/integrations
  integrations:
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
    says: lists Datadog as an integration
    source: https://www.atlassian.com/software/statuspage/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Intercom
    provider: intercom
    says: lists Intercom as an integration
    source: https://www.atlassian.com/software/statuspage/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.30
      key: it-service-management
      name: IT Service Management
      url: /capabilities/it-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Jira Service Management
    provider: jira
    says: lists Jira Service Management as an integration
    source: https://www.atlassian.com/software/statuspage/integrations
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
    name: Librato
    provider: librato
    says: lists Librato as an integration
    source: https://www.atlassian.com/software/statuspage/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://www.atlassian.com/software/statuspage/integrations
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
    name: New Relic
    provider: new-relic
    says: lists New Relic as an integration
    source: https://www.atlassian.com/software/statuspage/integrations
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
    source: https://www.atlassian.com/software/statuspage/integrations
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
    source: https://www.atlassian.com/software/statuspage/integrations
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
    name: Pingdom
    provider: pingdom
    says: lists Pingdom as an integration
    source: https://www.atlassian.com/software/statuspage/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://www.atlassian.com/software/statuspage/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Twitter
    provider: x
    says: lists Twitter as an integration
    source: https://www.atlassian.com/software/statuspage/integrations
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
    name: VictorOps
    provider: victorops
    says: lists VictorOps as an integration
    source: https://www.atlassian.com/software/statuspage/integrations
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
    name: xMatters
    provider: xmatters
    says: lists xMatters as an integration
    source: https://www.atlassian.com/software/statuspage/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Zendesk
    provider: zendesk
    says: lists Zendesk as an integration
    source: https://www.atlassian.com/software/statuspage/integrations
    tier: declared
  kind: commercial
  name: Atlassian Statuspage
  page: /applications/incident-status-pages/atlassian-statuspage/
  slug: atlassian-statuspage
  url: https://www.atlassian.com/software/statuspage
- anchor: firehydrant
  counts:
    declared: 35
    observed: 0
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
    layer: domain
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://firehydrant.com/integrations/
    tier: declared
  kind: commercial
  name: FireHydrant
  page: /applications/incident-status-pages/firehydrant/
  slug: firehydrant
  url: https://firehydrant.com/
- anchor: grafana-oncall
  counts:
    declared: 0
    observed: 14
  evidence:
  - route: source code
    url: https://github.com/grafana/oncall/blob/dev/engine/apps/social_auth/backends.py
  - route: source code
    url: https://github.com/grafana/oncall/tree/dev/engine/apps
  - route: source code
    url: https://github.com/grafana/oncall/tree/dev/engine/apps/integrations/metadata/heartbeat
  - route: source code
    url: https://github.com/grafana/oncall/tree/dev/engine/config_integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: ElastAlert
    provider: elastalert
    says: ships the ElastAlert SDK or integration code
    source: https://github.com/grafana/oncall/tree/dev/engine/config_integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: domain
    name: Exotel
    provider: exotel
    says: ships the Exotel SDK or integration code
    source: https://github.com/grafana/oncall/tree/dev/engine/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Google Calendar
    provider: google-calendar
    says: ships the Google Calendar SDK or integration code
    source: https://github.com/grafana/oncall/tree/dev/engine/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google sign-in
    provider: google
    says: ships the Google sign-in SDK or integration code
    source: https://github.com/grafana/oncall/blob/dev/engine/apps/social_auth/backends.py
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
    name: Kapacitor
    provider: influxdata
    says: ships the Kapacitor SDK or integration code
    source: https://github.com/grafana/oncall/tree/dev/engine/config_integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Mattermost
    provider: mattermost
    says: ships the Mattermost SDK or integration code
    source: https://github.com/grafana/oncall/tree/dev/engine/apps
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
    name: Prometheus Alertmanager
    provider: prometheus-io
    says: ships the Prometheus Alertmanager SDK or integration code
    source: https://github.com/grafana/oncall/tree/dev/engine/config_integrations
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
    name: PRTG
    provider: paessler
    says: ships the PRTG SDK or integration code
    source: https://github.com/grafana/oncall/tree/dev/engine/apps/integrations/metadata/heartbeat
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/grafana/oncall/tree/dev/engine/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://github.com/grafana/oncall/tree/dev/engine/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/grafana/oncall/tree/dev/engine/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: domain
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/grafana/oncall/tree/dev/engine/apps
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
    name: Zabbix
    provider: zabbix
    says: ships the Zabbix SDK or integration code
    source: https://github.com/grafana/oncall/tree/dev/engine/config_integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: domain
    name: Zvonok
    provider: zvonok
    says: ships the Zvonok SDK or integration code
    source: https://github.com/grafana/oncall/tree/dev/engine/apps
    tier: observed
  kind: self-hosted
  name: Grafana OnCall
  page: /applications/incident-status-pages/grafana-oncall/
  slug: grafana-oncall
  url: https://github.com/grafana/oncall
- anchor: dispatch-(netflix)
  counts:
    declared: 0
    observed: 16
  evidence:
  - route: source code
    url: https://github.com/Netflix/dispatch/blob/main/src/dispatch/plugins/dispatch_aws/plugin.py
  - route: source code
    url: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
  - route: source code
    url: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins/dispatch_google
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: AWS SQS
    provider: amazon-sqs
    says: ships the AWS SQS SDK or integration code
    source: https://github.com/Netflix/dispatch/blob/main/src/dispatch/plugins/dispatch_aws/plugin.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    credit: null
    layer: common
    name: Confluence
    provider: confluence
    says: ships the Confluence SDK or integration code
    source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.20
      key: AE-160.10.20
      name: Multi-Factor Authentication
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Duo
    provider: duo-security
    says: ships the Duo SDK or integration code
    source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
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
    name: Gmail
    provider: gmail
    says: ships the Gmail SDK or integration code
    source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins/dispatch_google
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Google Calendar
    provider: google-calendar
    says: ships the Google Calendar SDK or integration code
    source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins/dispatch_google
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Docs
    provider: google-docs
    says: ships the Google Docs SDK or integration code
    source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins/dispatch_google
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Drive
    provider: google-drive
    says: ships the Google Drive SDK or integration code
    source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins/dispatch_google
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Groups
    provider: google-workspace
    says: ships the Google Groups SDK or integration code
    source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins/dispatch_google
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Jira
    provider: jira
    says: ships the Jira SDK or integration code
    source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Microsoft Teams
    provider: microsoft-teams
    says: ships the Microsoft Teams SDK or integration code
    source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
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
    source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
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
    source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: Zoom
    provider: zoom
    says: ships the Zoom SDK or integration code
    source: https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
    tier: observed
  kind: self-hosted
  name: Dispatch (Netflix)
  page: /applications/incident-status-pages/dispatch-netflix/
  slug: dispatch-netflix
  url: https://github.com/Netflix/dispatch
- anchor: goalert
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: dependency manifest
    url: https://github.com/target/goalert/blob/master/go.mod
  - route: source code
    url: https://github.com/target/goalert
  - route: source code
    url: https://github.com/target/goalert/tree/master/notification
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/target/goalert/blob/master/go.mod
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
    name: Grafana
    provider: grafana-com
    says: ships the Grafana SDK or integration code
    source: https://github.com/target/goalert
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.50
      key: AE-150.10.50
      name: Inbound Email Processing
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: Mailgun
    provider: mailgun
    says: ships the Mailgun SDK or integration code
    source: https://github.com/target/goalert
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
    name: Prometheus Alertmanager
    provider: prometheus-io
    says: ships the Prometheus Alertmanager SDK or integration code
    source: https://github.com/target/goalert
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
    name: Site24x7
    provider: site24x7
    says: ships the Site24x7 SDK or integration code
    source: https://github.com/target/goalert
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/target/goalert/blob/master/go.mod
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/target/goalert/tree/master/notification
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: domain
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/target/goalert/tree/master/notification
    tier: observed
  kind: self-hosted
  name: GoAlert
  page: /applications/incident-status-pages/goalert/
  slug: goalert
  url: https://github.com/target/goalert
- anchor: cachet
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: dependency manifest
    url: https://github.com/cachethq/cachet/blob/main/composer.json
  - route: source code
    url: https://github.com/cachethq/cachet/blob/main/.env.example
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/cachethq/cachet/blob/main/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Laravel Nightwatch
    provider: laravel
    says: ships the Laravel Nightwatch SDK or integration code
    source: https://github.com/cachethq/cachet/blob/main/composer.json
    tier: observed
  kind: self-hosted
  name: Cachet
  page: /applications/incident-status-pages/cachet/
  slug: cachet
  url: https://github.com/cachethq/cachet
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: incident-status-pages
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: IT & Helpdesk
  store: atlassian-marketplace
  url: https://marketplace.atlassian.com/
- category: Developer Tools
  store: slack-marketplace
  url: https://slack.com/marketplace/category/At0EFRCDNY-developer-tools
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Status / Uptime pages
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#status--uptime-pages
- category: IT Operations
  store: zapier
  url: https://zapier.com/apps
name: Incident Management & Status Pages
needs:
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  fit: exact
  layer: domain
  why: paging, escalation and incident coordination tools wired into each other
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: domain
  why: monitoring and error-tracking sources that open incidents and drive status components
- capability:
    attribution: Turbo EA
    id: BC-2630.30
    key: customer-impacting-incident-management
    name: Customer-Impacting Incident Management
    url: /capabilities/customer-impacting-incident-management/
    via_parent: null
  fit: exact
  layer: domain
  why: public status-page publishing
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: exact
  layer: domain
  why: ChatOps incident channels in Slack/Teams/Mattermost
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: domain
  why: SMS paging
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.10
    key: AE-150.50.10
    name: Programmable Voice
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  fit: exact
  layer: domain
  why: phone-call paging
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: domain
  why: Telegram paging
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: domain
  why: incident bridge calls
- capability:
    attribution: Turbo EA
    id: BC-600.30
    key: it-service-management
    name: IT Service Management
    url: /capabilities/it-service-management/
    via_parent: null
  fit: exact
  layer: domain
  why: ITSM tickets and service catalogs
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: common
  why: follow-up and action-item tickets
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: status embedded in support desks
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  fit: exact
  layer: common
  why: postmortem and incident documents
- capability:
    attribution: Turbo EA
    id: BC-910
    key: change-management
    name: Change Management
    url: /capabilities/change-management/
    via_parent: null
  fit: nearest
  layer: common
  why: deploy/change events correlated with incidents
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: sign-in
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: AI incident summaries and assistant connectors
- capability:
    attribution: API Evangelist extension
    id: AE-100.70.10
    key: AE-100.70.10
    name: Coding Agents
    url: /capabilities/vertical-agents/
    via_parent: Vertical Agents
  fit: exact
  layer: agent
  why: coding agent connected to incident data
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: common
  why: on-call / OOO calendar sync
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: incident email
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.50
    key: AE-150.10.50
    name: Inbound Email Processing
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: domain
  why: alerts created from inbound email
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: incident document storage
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.20
    key: AE-160.10.20
    name: Multi-Factor Authentication
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: MFA on sensitive incident actions
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: SSO / group membership
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: domain
  why: signal ingestion queue
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: attachment/file storage
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: nearest
  layer: domain
  why: status updates posted to social
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: common
  why: GIFs in incident chat
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: API Evangelist extension
    id: AE-942
    key: AE-942
    name: Internal Developer Portals & Software Catalogs
    url: /capabilities/it-service-management/
    via_parent: IT Service Management
  fit: exact
  layer: domain
  why: Backstage, Cortex, OpsLevel (Internal Developer Portals & Software Catalogs)
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - FireHydrant
      - GoAlert
      - Grafana OnCall
      band: thin
      in_catalog: true
      kin_score: 35.9
      mcp:
        source: https://github.com/prometheus/prometheus-mcp
        status: verified
      name: Alertmanager
      slug: prometheus-io
      sources:
      - https://firehydrant.com/integrations/
      - https://github.com/grafana/oncall/tree/dev/engine/config_integrations
      - https://github.com/target/goalert
      status: profiled
      tags:
      - Metrics
      - Monitoring
      - Observability
      - Prometheus
      tier: observed
      url: /providers/prometheus-io/
    - agent_band: agent-ready
      agent_readiness: 48.6
      apps:
      - Atlassian Statuspage
      - FireHydrant
      - PagerDuty
      band: exemplar
      in_catalog: true
      kin_score: 80.0
      mcp:
        source: https://github.com/datadog-labs/mcp-server
        status: verified
      name: Datadog
      slug: datadog
      sources:
      - https://firehydrant.com/integrations/
      - https://www.atlassian.com/software/statuspage/integrations
      - https://www.pagerduty.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Dashboards
      - Datadog
      - Visualization
      tier: declared
      url: /providers/datadog/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - FireHydrant
      - PagerDuty
      - incident.io
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS
      slug: amazon-web-services
      sources:
      - https://firehydrant.com/integrations/
      - https://incident.io/integrations
      - https://www.pagerduty.com/integrations/
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: declared
      url: /providers/amazon-web-services/
    - agent_band: agent-aware
      agent_readiness: 27.6
      apps:
      - FireHydrant
      - GoAlert
      band: strong
      in_catalog: true
      kin_score: 66.0
      mcp:
        source: https://github.com/grafana/mcp-grafana
        status: verified
      name: Grafana
      slug: grafana-com
      sources:
      - https://firehydrant.com/integrations/
      - https://github.com/target/goalert
      status: profiled
      tags:
      - Dashboards
      - Logs
      - Monitoring
      - Observability
      tier: observed
      url: /providers/grafana-com/
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - FireHydrant
      - GoAlert
      band: developing
      in_catalog: true
      kin_score: 40.7
      mcp:
        source: https://www.site24x7.com/help/aiops/mcp-server.html
        status: documented
      name: Site24x7
      slug: site24x7
      sources:
      - https://firehydrant.com/integrations/
      - https://github.com/target/goalert
      status: profiled
      tags:
      - Infrastructure
      - Monitoring
      - Observability
      - Uptime
      tier: observed
      url: /providers/site24x7/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - FireHydrant
      - incident.io
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://firehydrant.com/integrations/
      - https://incident.io/integrations
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: declared
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Atlassian Statuspage
      - FireHydrant
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://firehydrant.com/integrations/
      - https://www.atlassian.com/software/statuspage/integrations
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: declared
      url: /providers/new-relic/
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - Grafana OnCall
      band: strong
      in_catalog: true
      kin_score: 63.3
      mcp:
        source: https://github.com/influxdata/influxdb3_mcp_server
        status: verified
      name: Kapacitor
      slug: influxdata
      sources:
      - https://github.com/grafana/oncall/tree/dev/engine/config_integrations
      status: profiled
      tags:
      - Database
      - Monitoring
      - Observability
      - Time Series Database
      tier: observed
      url: /providers/influxdata/
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - Grafana OnCall
      band: thin
      in_catalog: true
      kin_score: 34.0
      mcp:
        status: none
      name: Zabbix
      slug: zabbix
      sources:
      - https://github.com/grafana/oncall/tree/dev/engine/config_integrations
      status: profiled
      tags:
      - Alerting
      - Infrastructure
      - Monitoring
      - Networks
      tier: observed
      url: /providers/zabbix/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Grafana OnCall
      band: thin
      in_catalog: true
      kin_score: 33.1
      mcp:
        status: unchecked
      name: PRTG
      slug: paessler
      sources:
      - https://github.com/grafana/oncall/tree/dev/engine/apps/integrations/metadata/heartbeat
      status: profiled
      tags:
      - IT
      - Monitoring
      - Networks
      - Software
      tier: observed
      url: /providers/paessler/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Grafana OnCall
      band: minimal
      in_catalog: true
      kin_score: 2.2
      mcp:
        status: unchecked
      name: ElastAlert
      slug: elastalert
      sources:
      - https://github.com/grafana/oncall/tree/dev/engine/config_integrations
      status: profiled
      tags:
      - Alerting
      - Elasticsearch
      - Monitoring
      - OpenSearch
      tier: observed
      url: /providers/elastalert/
    - agent_band: agent-native
      agent_readiness: 43.4
      apps:
      - FireHydrant
      band: exemplar
      in_catalog: true
      kin_score: 77.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS CloudWatch
      slug: amazon-cloudwatch
      sources:
      - https://firehydrant.com/integrations/
      status: profiled
      tags:
      - Amazon Web Services
      - CloudWatch
      - Monitoring
      - Observability
      tier: declared
      url: /providers/amazon-cloudwatch/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - FireHydrant
      band: exemplar
      in_catalog: true
      kin_score: 76.3
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://firehydrant.com/integrations/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: declared
      url: /providers/bugsnag/
    - agent_band: agent-ready
      agent_readiness: 61.2
      apps:
      - FireHydrant
      band: exemplar
      in_catalog: true
      kin_score: 76.2
      mcp:
        source: https://www.checklyhq.com/docs/guides/communicate-availability.md
        status: documented
      name: Checkly
      slug: checkly
      sources:
      - https://firehydrant.com/integrations/
      status: profiled
      tags:
      - Monitoring
      - Observability
      - Synthetic Monitoring
      - Testing
      tier: declared
      url: /providers/checkly/
    - agent_band: agent-ready
      agent_readiness: 55.5
      apps:
      - FireHydrant
      band: exemplar
      in_catalog: true
      kin_score: 71.6
      mcp:
        source: https://docs.honeycomb.io/integrations/mcp/
        status: verified
      name: Honeycomb
      slug: honeycomb
      sources:
      - https://firehydrant.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Data Management
      - Observability
      - Telemetry
      tier: declared
      url: /providers/honeycomb/
    - agent_band: agent-ready
      agent_readiness: 37.2
      apps:
      - FireHydrant
      band: strong
      in_catalog: true
      kin_score: 66.4
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Stackdriver
      slug: google-cloud-monitoring
      sources:
      - https://firehydrant.com/integrations/
      status: profiled
      tags:
      - Alerting
      - Dashboards
      - Google Cloud
      - Metrics
      tier: declared
      url: /providers/google-cloud-monitoring/
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - FireHydrant
      band: developing
      in_catalog: true
      kin_score: 44.6
      mcp:
        status: unchecked
      name: StatusCake
      slug: statuscake
      sources:
      - https://firehydrant.com/integrations/
      status: profiled
      tags:
      - Company
      - Monitoring
      - Performance
      - Uptime
      tier: declared
      url: /providers/statuscake/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Atlassian Statuspage
      band: emerging
      in_catalog: true
      kin_score: 17.7
      mcp:
        status: unknown
      name: Pingdom
      slug: pingdom
      sources:
      - https://www.atlassian.com/software/statuspage/integrations
      status: profiled
      tags:
      - Monitoring
      - Performance Monitoring
      - Uptime Monitoring
      - Website Monitoring
      tier: declared
      url: /providers/pingdom/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Atlassian Statuspage
      band: minimal
      in_catalog: true
      kin_score: 0.0
      mcp:
        status: none
      name: Librato
      slug: librato
      sources:
      - https://www.atlassian.com/software/statuspage/integrations
      status: profiled
      tags:
      - Company
      - Developer Tools
      - Metrics
      - Monitoring
      tier: declared
      url: /providers/librato/
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
      - Atlassian Statuspage
      - Dispatch (Netflix)
      - FireHydrant
      - incident.io
      band: developing
      in_catalog: true
      kin_score: 52.1
      mcp:
        source: https://github.com/PagerDuty/pagerduty-mcp-server
        status: verified
      name: PagerDuty
      slug: pagerduty
      sources:
      - https://firehydrant.com/integrations/
      - https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
      - https://incident.io/integrations
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
      - Atlassian Statuspage
      - Dispatch (Netflix)
      - FireHydrant
      - incident.io
      band: developing
      in_catalog: true
      kin_score: 48.6
      mcp:
        status: none
      name: Opsgenie
      slug: opsgenie
      sources:
      - https://firehydrant.com/integrations/
      - https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
      - https://incident.io/integrations
      status: profiled
      tags:
      - Alerts
      - Incident Management
      - Monitoring
      - On-Call
      tier: observed
      url: /providers/opsgenie/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Atlassian Statuspage
      - FireHydrant
      band: emerging
      in_catalog: true
      kin_score: 18.1
      mcp:
        status: none
      name: VictorOps
      slug: victorops
      sources:
      - https://firehydrant.com/integrations/
      - https://www.atlassian.com/software/statuspage/integrations
      status: profiled
      tags:
      - Alerting
      - DevOps
      - Incident Management
      - On-Call
      tier: declared
      url: /providers/victorops/
    - agent_band: agent-ready
      agent_readiness: 54.3
      apps:
      - incident.io
      band: exemplar
      in_catalog: true
      kin_score: 72.7
      mcp:
        source: https://docs.bigpanda.io/en/api---mcp-usage.html
        status: documented
      name: BigPanda
      slug: bigpanda
      sources:
      - https://incident.io/integrations
      status: profiled
      tags:
      - AIOps
      - Incidents
      - Monitoring
      - Platform
      tier: declared
      url: /providers/bigpanda/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Atlassian Statuspage
      band: emerging
      in_catalog: true
      kin_score: 22.5
      mcp:
        status: none
      name: xMatters
      slug: xmatters
      sources:
      - https://www.atlassian.com/software/statuspage/integrations
      status: profiled
      tags:
      - Alerting
      - Incident Management
      - On-Call
      - Service Reliability
      tier: declared
      url: /providers/xmatters/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Atlassian Statuspage
      - Dispatch (Netflix)
      - FireHydrant
      - GoAlert
      - Grafana OnCall
      - PagerDuty
      - incident.io
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://firehydrant.com/integrations/
      - https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
      - https://github.com/grafana/oncall/tree/dev/engine/apps
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
      - Atlassian Statuspage
      - Dispatch (Netflix)
      - FireHydrant
      - PagerDuty
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://firehydrant.com/integrations/
      - https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
      - https://www.atlassian.com/software/statuspage/integrations
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: observed
      url: /providers/microsoft-teams/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Grafana OnCall
      band: thin
      in_catalog: true
      kin_score: 37.0
      mcp:
        source: https://github.com/mattermost/mmctl-mcp
        status: verified
      name: Mattermost
      slug: mattermost
      sources:
      - https://github.com/grafana/oncall/tree/dev/engine/apps
      status: profiled
      tags:
      - Collaboration
      - Messaging
      - Open Source
      - Team Chat
      tier: observed
      url: /providers/mattermost/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Dispatch (Netflix)
      - FireHydrant
      - incident.io
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://firehydrant.com/integrations/
      - https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
      - https://incident.io/integrations
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: observed
      url: /providers/zoom/
    - agent_band: agent-ready
      agent_readiness: 61.8
      apps:
      - FireHydrant
      band: strong
      in_catalog: true
      kin_score: 66.1
      mcp:
        source: https://github.com/WebexSamples/webex-messaging-mcp-server
        status: verified
      name: Webex
      slug: webex
      sources:
      - https://firehydrant.com/integrations/
      status: profiled
      tags:
      - Calling
      - Collaboration
      - Communications
      - Enterprise
      tier: declared
      url: /providers/webex/
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - FireHydrant
      band: developing
      in_catalog: true
      kin_score: 52.2
      mcp:
        status: none
      name: Google Meet
      slug: google-meet
      sources:
      - https://firehydrant.com/integrations/
      status: profiled
      tags:
      - Google
      - Google Workspace
      - Meetings
      - Recording
      tier: declared
      url: /providers/google-meet/
  - capability:
      attribution: API Evangelist extension
      id: AE-942
      key: AE-942
      name: Internal Developer Portals & Software Catalogs
      url: /capabilities/it-service-management/
      via_parent: IT Service Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - FireHydrant
      - incident.io
      band: thin
      in_catalog: true
      kin_score: 33.3
      mcp:
        status: unknown
      name: Cortex
      slug: cortex-idp
      sources:
      - https://firehydrant.com/integrations/
      - https://incident.io/integrations
      status: profiled
      tags:
      - Developer Experience
      - Internal Developer Portal
      - Service Catalog
      - Software Catalog
      tier: declared
      url: /providers/cortex-idp/
    - agent_band: agent-ready
      agent_readiness: 60.9
      apps:
      - incident.io
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        source: https://backstage.io/docs/ai/mcp-actions
        status: verified
      name: Backstage
      slug: backstage
      sources:
      - https://incident.io/integrations
      status: profiled
      tags:
      - Developer Portal
      - Internal Developer Platform
      - Open Source
      - Software Catalog
      tier: declared
      url: /providers/backstage/
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - incident.io
      band: developing
      in_catalog: true
      kin_score: 49.0
      mcp:
        source: https://github.com/OpsLevel/opslevel-mcp
        status: verified
      name: OpsLevel
      slug: opslevel
      sources:
      - https://incident.io/integrations
      status: profiled
      tags:
      - DevOps
      - Developer Portal
      - Developer Tools
      - Experience
      tier: declared
      url: /providers/opslevel/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    providers:
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - GoAlert
      - Grafana OnCall
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp: &id001
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/grafana/oncall/tree/dev/engine/apps
      - https://github.com/target/goalert/tree/master/notification
      status: profiled
      tags: &id002
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-aware
      agent_readiness: 24.5
      apps:
      - Grafana OnCall
      band: thin
      in_catalog: true
      kin_score: 29.3
      mcp:
        status: unchecked
      name: Zvonok
      slug: zvonok
      sources:
      - https://github.com/grafana/oncall/tree/dev/engine/apps
      status: profiled
      tags:
      - Artificial Intelligence
      - Automation
      - Company
      - Telephony
      tier: observed
      url: /providers/zvonok/
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - Grafana OnCall
      band: thin
      in_catalog: true
      kin_score: 27.7
      mcp:
        source: https://github.com/exotel/ExotelMCP
        status: verified
      name: Exotel
      slug: exotel
      sources:
      - https://github.com/grafana/oncall/tree/dev/engine/apps
      status: profiled
      tags:
      - Cloud Telephony
      - India
      - SMS
      - Voice
      tier: observed
      url: /providers/exotel/
  - capability:
      attribution: Turbo EA
      id: BC-600.30
      key: it-service-management
      name: IT Service Management
      url: /capabilities/it-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - FireHydrant
      - incident.io
      band: strong
      in_catalog: true
      kin_score: 61.9
      mcp:
        status: none
      name: ServiceNow
      slug: servicenow
      sources:
      - https://firehydrant.com/integrations/
      - https://incident.io/integrations
      status: profiled
      tags:
      - Automation
      - Cloud Services
      - Digital Workflows
      - ServiceNow
      tier: declared
      url: /providers/servicenow/
    - agent_band: agent-ready
      agent_readiness: 43.4
      apps:
      - FireHydrant
      band: thin
      in_catalog: true
      kin_score: 35.8
      mcp:
        status: none
      name: Freshservice
      slug: freshservice
      sources:
      - https://firehydrant.com/integrations/
      status: profiled
      tags:
      - Asset Management
      - Help Desk
      - ITSM
      - Ticketing
      tier: declared
      url: /providers/freshservice/
  - capability:
      attribution: Turbo EA
      id: BC-2630.30
      key: customer-impacting-incident-management
      name: Customer-Impacting Incident Management
      url: /capabilities/customer-impacting-incident-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.7
      apps:
      - FireHydrant
      - incident.io
      band: thin
      in_catalog: true
      kin_score: 36.0
      mcp:
        status: none
      name: Atlassian Statuspage
      slug: statuspage
      sources:
      - https://firehydrant.com/integrations/
      - https://incident.io/integrations
      status: profiled
      tags:
      - Incident Communication
      - Incident Management
      - Status Pages
      - Uptime
      tier: declared
      url: /providers/statuspage/
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
      - GoAlert
      - Grafana OnCall
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp: *id001
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/grafana/oncall/tree/dev/engine/apps
      - https://github.com/target/goalert/tree/master/notification
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/twilio/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.50
      key: AE-150.10.50
      name: Inbound Email Processing
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - GoAlert
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://github.com/target/goalert
      status: profiled
      tags:
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailgun/
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
      - Dispatch (Netflix)
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS SQS
      slug: amazon-sqs
      sources:
      - https://github.com/Netflix/dispatch/blob/main/src/dispatch/plugins/dispatch_aws/plugin.py
      status: profiled
      tags:
      - Amazon Web Services
      - Cloud
      - Distributed Systems
      - Messaging
      tier: observed
      url: /providers/amazon-sqs/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - Atlassian Statuspage
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: Twitter
      slug: x
      sources:
      - https://www.atlassian.com/software/statuspage/integrations
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: declared
      url: /providers/x/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Grafana OnCall
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://github.com/grafana/oncall/tree/dev/engine/apps
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 64.4
      apps:
      - Dispatch (Netflix)
      - FireHydrant
      - incident.io
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp: &id007
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://firehydrant.com/integrations/
      - https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
      - https://incident.io/integrations
      status: profiled
      tags: &id008
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: observed
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 53.5
      apps:
      - FireHydrant
      - incident.io
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp:
        source: https://github.com/useshortcut/mcp-server-shortcut
        status: verified
      name: Shortcut
      slug: shortcut-software
      sources:
      - https://firehydrant.com/integrations/
      - https://incident.io/integrations
      status: profiled
      tags:
      - Agile
      - Company
      - Issue Tracking
      - Project Management
      tier: declared
      url: /providers/shortcut-software/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - FireHydrant
      - incident.io
      band: developing
      in_catalog: true
      kin_score: 39.6
      mcp:
        source: https://linear.app/docs/mcp
        status: verified
      name: Linear
      slug: linear-app
      sources:
      - https://firehydrant.com/integrations/
      - https://incident.io/integrations
      status: profiled
      tags:
      - Issue Tracking
      - Productivity
      - Project Management
      - Software-as-a-Service
      tier: declared
      url: /providers/linear-app/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Dispatch (Netflix)
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: &id003
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
      status: profiled
      tags: &id004
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 55.8
      apps:
      - incident.io
      band: exemplar
      in_catalog: true
      kin_score: 72.6
      mcp:
        source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
        status: verified
      name: ClickUp
      slug: clickup
      sources:
      - https://incident.io/integrations
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: declared
      url: /providers/clickup/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - incident.io
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://incident.io/integrations
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: declared
      url: /providers/asana/
  - capability:
      attribution: Turbo EA
      id: BC-910
      key: change-management
      name: Change Management
      url: /capabilities/change-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - FireHydrant
      - incident.io
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: *id003
      name: GitHub
      slug: github
      sources:
      - https://firehydrant.com/integrations/
      - https://incident.io/integrations
      status: profiled
      tags: *id004
      tier: declared
      url: /providers/github/
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - incident.io
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://incident.io/integrations
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: declared
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 56.3
      apps:
      - FireHydrant
      band: exemplar
      in_catalog: true
      kin_score: 73.5
      mcp:
        source: https://github.com/CircleCI-Public/mcp-server-circleci
        status: verified
      name: CircleCI
      slug: circleci
      sources:
      - https://firehydrant.com/integrations/
      status: profiled
      tags:
      - CI/CD
      - Continuous Deployment
      - Continuous Integration
      - DevOps
      tier: declared
      url: /providers/circleci/
    - agent_band: agent-ready
      agent_readiness: 32.6
      apps:
      - FireHydrant
      band: developing
      in_catalog: true
      kin_score: 48.7
      mcp:
        status: none
      name: Kubernetes
      slug: kubernetes
      sources:
      - https://firehydrant.com/integrations/
      status: profiled
      tags:
      - Automation
      - CNCF
      - Cloud-Native
      - Containers
      tier: declared
      url: /providers/kubernetes/
    - agent_band: agent-ready
      agent_readiness: 29.7
      apps:
      - FireHydrant
      band: developing
      in_catalog: true
      kin_score: 42.5
      mcp:
        source: https://github.com/hashicorp/terraform-mcp-server
        status: verified
      name: Terraform
      slug: terraform
      sources:
      - https://firehydrant.com/integrations/
      status: profiled
      tags:
      - Cloud Infrastructure
      - DevOps
      - Infrastructure as Code
      - Open Source
      tier: declared
      url: /providers/terraform/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Atlassian Statuspage
      - FireHydrant
      - incident.io
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://firehydrant.com/integrations/
      - https://incident.io/integrations
      - https://www.atlassian.com/software/statuspage/integrations
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Atlassian Statuspage
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://www.atlassian.com/software/statuspage/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: declared
      url: /providers/intercom/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - PagerDuty
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id005
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.pagerduty.android/latest/
      status: profiled
      tags: &id006
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - PagerDuty
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.pagerduty.android/latest/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - PagerDuty
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.pagerduty.android/latest/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Dispatch (Netflix)
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/gemini-cli-extensions/workspace
        status: verified
      name: Google Groups
      slug: google-workspace
      sources:
      - https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins/dispatch_google
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: observed
      url: /providers/google-workspace/
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - FireHydrant
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://firehydrant.com/integrations/
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: declared
      url: /providers/okta/
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 55.8
      apps:
      - Dispatch (Netflix)
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Confluence
      slug: confluence
      sources:
      - https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
      status: profiled
      tags:
      - Collaboration
      - Content Management
      - Documentation
      - Knowledge Base
      tier: observed
      url: /providers/confluence/
    - agent_band: agent-ready
      agent_readiness: 40.3
      apps:
      - Dispatch (Netflix)
      band: exemplar
      in_catalog: true
      kin_score: 67.2
      mcp:
        source: https://docs.cloud.google.com/mcp/supported-products
        status: verified
      name: Google Docs
      slug: google-docs
      sources:
      - https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins/dispatch_google
      status: profiled
      tags:
      - Collaboration
      - Documents
      - Google Workspace
      - Productivity
      tier: observed
      url: /providers/google-docs/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Dispatch (Netflix)
      - Grafana OnCall
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins/dispatch_google
      - https://github.com/grafana/oncall/tree/dev/engine/apps
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: observed
      url: /providers/google-calendar/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.9
      apps:
      - Cachet
      band: exemplar
      in_catalog: true
      kin_score: 68.9
      mcp:
        source: https://github.com/laravel/mcp
        status: verified
      name: Laravel Nightwatch
      slug: laravel
      sources:
      - https://github.com/cachethq/cachet/blob/main/composer.json
      status: profiled
      tags:
      - Cloud Saas
      - Company
      - Developer Tools
      - PHP
      tier: observed
      url: /providers/laravel/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - PagerDuty
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id005
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.pagerduty.android/latest/
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - GoAlert
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: *id003
      name: GitHub
      slug: github
      sources:
      - https://github.com/target/goalert/blob/master/go.mod
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - Grafana OnCall
      band: exemplar
      in_catalog: true
      kin_score: 68.9
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google sign-in
      slug: google
      sources:
      - https://github.com/grafana/oncall/blob/dev/engine/apps/social_auth/backends.py
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: observed
      url: /providers/google/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - FireHydrant
      band: strong
      in_catalog: true
      kin_score: 56.0
      mcp:
        status: none
      name: Giphy
      slug: giphy
      sources:
      - https://firehydrant.com/integrations/
      status: profiled
      tags:
      - GIFs
      - Media
      - Photography
      - Stickers
      tier: declared
      url: /providers/giphy/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Dispatch (Netflix)
      band: exemplar
      in_catalog: true
      kin_score: 73.2
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins/dispatch_google
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: observed
      url: /providers/google-drive/
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
      - Dispatch (Netflix)
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
  - capability:
      attribution: Turbo EA
      id: BC-600.30
      key: it-service-management
      name: IT Service Management
      url: /capabilities/it-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 64.4
      apps:
      - Atlassian Statuspage
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp: *id007
      name: Jira Service Management
      slug: jira
      sources:
      - https://www.atlassian.com/software/statuspage/integrations
      status: profiled
      tags: *id008
      tier: declared
      url: /providers/jira/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.20
      key: AE-160.10.20
      name: Multi-Factor Authentication
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - Dispatch (Netflix)
      band: thin
      in_catalog: true
      kin_score: 34.7
      mcp:
        status: none
      name: Duo
      slug: duo-security
      sources:
      - https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins
      status: profiled
      tags:
      - Authentication
      - Identity
      - MFA
      - Zero Trust
      tier: observed
      url: /providers/duo-security/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Cachet
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/cachethq/cachet/blob/main/composer.json
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - Dispatch (Netflix)
      band: exemplar
      in_catalog: true
      kin_score: 66.8
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://github.com/Netflix/dispatch/tree/main/src/dispatch/plugins/dispatch_google
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: observed
      url: /providers/google-gmail/
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
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - PagerDuty
      band: strong
      in_catalog: true
      kin_score: 60.0
      mcp:
        status: none
      name: Cursor
      slug: cursor
      sources:
      - https://www.pagerduty.com/integrations/
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Code Editor
      - Developer Tools
      tier: declared
      url: /providers/cursor/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - PagerDuty
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic Claude Connector
      slug: anthropic
      sources:
      - https://www.pagerduty.com/integrations/
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: declared
      url: /providers/anthropic/
  layer: agent
summary:
  coverage_pct: 100.0
  declared_only: 39
  distinct_providers: 73
  in_catalog: 73
  mcp:
    documented: 3
    none: 17
    unchecked: 4
    verified: 47
  mcp_verified: 47
  mean_kin_score: 58.0
  observed: 34
  queued: 0
  reference_apps: 8
title: 'Incident Management & Status Pages: application blueprint'
---
