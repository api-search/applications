---
access: understanding
agent_layer:
- app: Toggl Track
  finding: Toggl lists its own "Toggl MCP" and Toggl AI Assistant on the integrations page
  source: https://toggl.com/track/integrations/
  tier: declared
- app: Super Productivity
  finding: ships an ai-productivity-prompts plugin; no MCP server in the repo
  source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
  tier: observed
apps:
- anchor: kimai
  counts:
    declared: 3
    observed: 0
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/kimai/kimai/main/composer.json
  - route: documentation
    url: https://www.kimai.org/documentation/saml.html
  - route: source code
    url: https://raw.githubusercontent.com/kimai/kimai/main/.env.dist
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Authentik SAML
    provider: authentik
    says: lists Authentik SAML as an integration
    source: https://www.kimai.org/documentation/saml.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Azure AD (Entra ID) SAML
    provider: microsoft-entra
    says: lists Azure AD (Entra ID) SAML as an integration
    source: https://www.kimai.org/documentation/saml.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Google Workspace SAML
    provider: google-workspace
    says: lists Google Workspace SAML as an integration
    source: https://www.kimai.org/documentation/saml.html
    tier: declared
  kind: self-hosted
  name: Kimai
  page: /applications/time-tracking/kimai/
  slug: kimai
  url: https://github.com/kimai/kimai
- anchor: solidtime
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/solidtime-io/solidtime/main/composer.json
  - route: dependency manifest
    url: https://raw.githubusercontent.com/solidtime-io/solidtime/main/package.json
  - route: source code
    url: https://github.com/solidtime-io/solidtime/tree/main/app/Service/Import/Importers
  - route: source code
    url: https://raw.githubusercontent.com/solidtime-io/solidtime/main/.env.example
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4330.10
      key: timekeeping-management
      name: Timekeeping Management
      url: /capabilities/timekeeping-management/
      via_parent: null
    credit: null
    layer: domain
    name: Clockify importer
    provider: clockify
    says: ships the Clockify importer SDK or integration code
    source: https://github.com/solidtime-io/solidtime/tree/main/app/Service/Import/Importers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4330.10
      key: timekeeping-management
      name: Timekeeping Management
      url: /capabilities/timekeeping-management/
      via_parent: null
    credit: null
    layer: domain
    name: Harvest importer
    provider: harvest
    says: ships the Harvest importer SDK or integration code
    source: https://github.com/solidtime-io/solidtime/tree/main/app/Service/Import/Importers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4330.10
      key: timekeeping-management
      name: Timekeeping Management
      url: /capabilities/timekeeping-management/
      via_parent: null
    credit: null
    layer: domain
    name: Toggl Track importer
    provider: toggl
    says: ships the Toggl Track importer SDK or integration code
    source: https://github.com/solidtime-io/solidtime/tree/main/app/Service/Import/Importers
    tier: observed
  kind: self-hosted
  name: solidtime
  page: /applications/time-tracking/solidtime/
  slug: solidtime
  url: https://github.com/solidtime-io/solidtime
- anchor: super-productivity
  counts:
    declared: 0
    observed: 16
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/johannesjo/super-productivity/master/package.json
  - route: source code
    url: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
  - route: source code
    url: https://github.com/super-productivity/super-productivity/tree/master/packages/sync-providers/src
  - route: source code
    url: https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    credit: null
    layer: domain
    name: Azure DevOps
    provider: microsoft-azure-devops
    says: ships the Azure DevOps SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClickUp
    provider: clickup
    says: ships the ClickUp SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    name: Dropbox sync
    provider: dropbox
    says: ships the Dropbox sync SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/sync-providers/src
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    credit: null
    layer: domain
    name: Gitea issues
    provider: gitea
    says: ships the Gitea issues SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    credit: null
    layer: domain
    name: GitHub issues
    provider: github
    says: ships the GitHub issues SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    credit: null
    layer: domain
    name: GitLab issues
    provider: gitlab
    says: ships the GitLab issues SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
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
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira
    provider: jira
    says: ships the Jira SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Linear
    provider: linear-app
    says: ships the Linear SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Nextcloud Deck
    provider: nextcloud
    says: ships the Nextcloud Deck SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    name: OneDrive sync
    provider: microsoft-onedrive
    says: ships the OneDrive sync SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/sync-providers/src
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: OpenProject
    provider: openproject
    says: ships the OpenProject SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Redmine
    provider: redmine
    says: ships the Redmine SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: TickTick import
    provider: ticktick
    says: ships the TickTick import SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Todoist import
    provider: todoist
    says: ships the Todoist import SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Trello
    provider: trello
    says: ships the Trello SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
    tier: observed
  kind: self-hosted
  name: Super Productivity
  page: /applications/time-tracking/super-productivity/
  slug: super-productivity
  url: https://github.com/super-productivity/super-productivity
- anchor: toggl-track
  counts:
    declared: 21
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.toggl.giskard/latest/
  - route: integrations page
    url: https://toggl.com/track/integrations/
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
    name: Google CrashLytics
    provider: firebase
    says: ships the Google CrashLytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.toggl.giskard/latest/
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
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.toggl.giskard/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.toggl.giskard/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    credit: null
    layer: domain
    name: Bitbucket
    provider: bitbucket
    says: lists Bitbucket as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10
      key: timekeeping-management
      name: Timekeeping Management
      url: /capabilities/timekeeping-management/
      via_parent: null
    credit: null
    layer: domain
    name: Clockify import
    provider: clockify
    says: lists Clockify import as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    credit: null
    layer: domain
    name: Evernote
    provider: evernote
    says: lists Evernote as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
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
    says: lists Google Calendar as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10
      key: timekeeping-management
      name: Timekeeping Management
      url: /capabilities/timekeeping-management/
      via_parent: null
    credit: null
    layer: domain
    name: Harvest import
    provider: harvest
    says: lists Harvest import as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10
      key: timekeeping-management
      name: Timekeeping Management
      url: /capabilities/timekeeping-management/
      via_parent: null
    credit: null
    layer: domain
    name: Hubstaff import
    provider: hubstaff
    says: lists Hubstaff import as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Podio
    provider: podio
    says: lists Podio as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.50
      key: invoice-generation-management
      name: Invoice Generation Management
      url: /capabilities/invoice-generation-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks Online
    provider: quickbooks
    says: lists QuickBooks Online as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Redmine
    provider: redmine
    says: lists Redmine as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Teamwork
    provider: teamwork
    says: lists Teamwork as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10
      key: timekeeping-management
      name: Timekeeping Management
      url: /capabilities/timekeeping-management/
      via_parent: null
    credit: null
    layer: domain
    name: Timely import
    provider: timely
    says: lists Timely import as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Todoist
    provider: todoist
    says: lists Todoist as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Trello
    provider: trello
    says: lists Trello as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Wrike
    provider: wrike
    says: lists Wrike as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.50
      key: invoice-generation-management
      name: Invoice Generation Management
      url: /capabilities/invoice-generation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Xero
    provider: xero
    says: lists Xero as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    credit: null
    layer: domain
    name: Zendesk
    provider: zendesk
    says: lists Zendesk as an integration
    source: https://toggl.com/track/integrations/
    tier: declared
  kind: commercial
  name: Toggl Track
  page: /applications/time-tracking/toggl-track/
  slug: toggl-track
  url: https://toggl.com/track/
- anchor: clockify
  counts:
    declared: 27
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/me.clockify.android/latest/
  - route: integrations page
    url: https://clockify.me/integrations
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
    name: Google CrashLytics
    provider: firebase
    says: ships the Google CrashLytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/me.clockify.android/latest/
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
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/me.clockify.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Airtable
    provider: airtable
    says: lists Airtable as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    credit: null
    layer: domain
    name: Azure DevOps
    provider: microsoft-azure-devops
    says: lists Azure DevOps as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Basecamp
    provider: basecamp
    says: lists Basecamp as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClickUp
    provider: clickup
    says: lists ClickUp as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    credit: null
    layer: domain
    name: Freshdesk
    provider: freshdesk
    says: lists Freshdesk as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: lists GitLab as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Gmail
    provider: google-gmail
    says: lists Gmail as an integration
    source: https://clockify.me/integrations
    tier: declared
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
    says: lists Google Calendar as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Sheets
    provider: google-sheets
    says: lists Google Sheets as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    credit: null
    layer: domain
    name: Help Scout
    provider: helpscout
    says: lists Help Scout as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Monday
    provider: monday-com
    says: lists Monday as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Notion
    provider: notion
    says: lists Notion as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Outlook
    provider: microsoft-outlook
    says: lists Outlook as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.50
      key: invoice-generation-management
      name: Invoice Generation Management
      url: /capabilities/invoice-generation-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks
    provider: quickbooks
    says: lists QuickBooks as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Teamwork
    provider: teamwork
    says: lists Teamwork as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Todoist
    provider: todoist
    says: lists Todoist as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Trello
    provider: trello
    says: lists Trello as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Wrike
    provider: wrike
    says: lists Wrike as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.50
      key: invoice-generation-management
      name: Invoice Generation Management
      url: /capabilities/invoice-generation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Xero
    provider: xero
    says: lists Xero as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: YouTrack
    provider: jetbrains
    says: lists YouTrack as an integration
    source: https://clockify.me/integrations
    tier: declared
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
    says: lists Zapier as an integration
    source: https://clockify.me/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    credit: null
    layer: domain
    name: Zendesk
    provider: zendesk
    says: lists Zendesk as an integration
    source: https://clockify.me/integrations
    tier: declared
  kind: commercial
  name: Clockify
  page: /applications/time-tracking/clockify/
  slug: clockify
  url: https://clockify.me/
- anchor: harvest
  counts:
    declared: 27
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.harvestapp/latest/
  - route: integrations page
    url: https://www.getharvest.com/integrations
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
    name: Bugsnag
    provider: bugsnag
    says: ships the Bugsnag SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.harvestapp/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Basecamp
    provider: basecamp
    says: lists Basecamp as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClickUp
    provider: clickup
    says: lists ClickUp as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Databox
    provider: databox
    says: lists Databox as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Deel
    provider: deel-com
    says: lists Deel as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    credit: null
    layer: domain
    name: Freshservice
    provider: freshservice
    says: lists Freshservice as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
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
    says: lists Google Calendar as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.70.20
      key: BC-300.70.20
      name: Payroll Administration
      url: /capabilities/hr-operations-management/
      via_parent: HR Operations Management
    credit: null
    layer: domain
    name: Gusto
    provider: gusto
    says: lists Gusto as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
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
    says: lists IFTTT as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Klipfolio
    provider: klipfolio
    says: lists Klipfolio as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Linear
    provider: linear-app
    says: lists Linear as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Make
    provider: make
    says: lists Make as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Monday.com
    provider: monday-com
    says: lists Monday.com as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Notion
    provider: notion
    says: lists Notion as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Outlook.com
    provider: microsoft-outlook
    says: lists Outlook.com as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.50
      key: invoice-generation-management
      name: Invoice Generation Management
      url: /capabilities/invoice-generation-management/
      via_parent: null
    credit: null
    layer: domain
    name: QuickBooks Online
    provider: quickbooks
    says: lists QuickBooks Online as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Teamwork Projects
    provider: teamwork
    says: lists Teamwork Projects as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Trello
    provider: trello
    says: lists Trello as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.50
      key: invoice-generation-management
      name: Invoice Generation Management
      url: /capabilities/invoice-generation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Xero
    provider: xero
    says: lists Xero as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
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
    says: lists Zapier as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    credit: null
    layer: domain
    name: Zendesk
    provider: zendesk
    says: lists Zendesk as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    credit: null
    layer: domain
    name: Zoho Desk
    provider: zoho-desk
    says: lists Zoho Desk as an integration
    source: https://www.getharvest.com/integrations
    tier: declared
  kind: commercial
  name: Harvest
  page: /applications/time-tracking/harvest/
  slug: harvest
  url: https://www.getharvest.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: time-tracking
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Productivity
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Productivity
  store: google-play
  url: https://play.google.com/store/apps/category/PRODUCTIVITY
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Time Tracking
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#time-tracking
- category: Time Tracking
  store: atlassian-marketplace
  url: https://marketplace.atlassian.com/
- category: Productivity
  store: slack-marketplace
  url: https://slack.com/apps
- category: Time Tracking Software
  store: zapier
  url: https://zapier.com/apps
name: Time Tracking & Timesheets
needs:
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: domain
  why: every tracker attaches time to tasks/issues in PM tools
- capability:
    attribution: Turbo EA
    id: BC-4330.10
    key: timekeeping-management
    name: Timekeeping Management
    url: /capabilities/timekeeping-management/
    via_parent: null
  fit: exact
  layer: domain
  why: importers from and to competing time trackers
- capability:
    attribution: Turbo EA
    id: BC-4330.50
    key: invoice-generation-management
    name: Invoice Generation Management
    url: /capabilities/invoice-generation-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: billable time pushed to accounting for invoicing
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: common
  why: time against CRM accounts/deals
- capability:
    attribution: Turbo EA
    id: BC-4330.10.10
    key: BC-4330.10.10
    name: Time Entry Capture
    url: /capabilities/timekeeping-management/
    via_parent: Timekeeping Management
  fit: exact
  layer: domain
  why: time against help-desk tickets
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: timers and reminders in team chat
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: common
  why: calendar events become time entries
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: device sync of local-first data
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: iPaaS connectors
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: domain
  why: time data into dashboards/sheets
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: online payment of invoices
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: hours to payroll/contractor pay
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: SAML SSO for workforce sign-in
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: timers inside notes
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash and error reporting SDKs ship in the mobile apps (Exodus)
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: product analytics SDKs ship in the mobile apps (Exodus)
- capability:
    attribution: Turbo EA
    id: BC-300.70.20
    key: BC-300.70.20
    name: Payroll Administration
    url: /capabilities/hr-operations-management/
    via_parent: HR Operations Management
  fit: exact
  layer: domain
  why: Gusto (Payroll Administration)
stack:
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
      - Clockify
      - Harvest
      - Super Productivity
      - Toggl Track
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://clockify.me/integrations
      - https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
      - https://toggl.com/track/integrations/
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: observed
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Clockify
      - Harvest
      - Super Productivity
      - Toggl Track
      band: exemplar
      in_catalog: true
      kin_score: 74.8
      mcp:
        source: https://github.com/atlassian/trello-mcp-server
        status: verified
      name: Trello
      slug: trello
      sources:
      - https://clockify.me/integrations
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      - https://toggl.com/track/integrations/
      status: profiled
      tags:
      - Collaboration
      - Kanban
      - Project Management
      - Task Management
      tier: observed
      url: /providers/trello/
    - agent_band: agent-ready
      agent_readiness: 55.8
      apps:
      - Clockify
      - Harvest
      - Super Productivity
      band: exemplar
      in_catalog: true
      kin_score: 72.6
      mcp:
        source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
        status: verified
      name: ClickUp
      slug: clickup
      sources:
      - https://clockify.me/integrations
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: observed
      url: /providers/clickup/
    - agent_band: agent-aware
      agent_readiness: 22.2
      apps:
      - Clockify
      - Super Productivity
      - Toggl Track
      band: developing
      in_catalog: true
      kin_score: 53.8
      mcp:
        source: https://developer.todoist.com/api/v1/#tag/MCP
        status: verified
      name: Todoist import
      slug: todoist
      sources:
      - https://clockify.me/integrations
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      - https://toggl.com/track/integrations/
      status: profiled
      tags:
      - Productivity
      - Task
      - Task Management
      - To-Do
      tier: observed
      url: /providers/todoist/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - Clockify
      - Harvest
      - Toggl Track
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://clockify.me/integrations
      - https://toggl.com/track/integrations/
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: declared
      url: /providers/asana/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Clockify
      - Harvest
      - Toggl Track
      band: thin
      in_catalog: true
      kin_score: 34.5
      mcp:
        source: https://github.com/Teamwork/mcp
        status: verified
      name: Teamwork
      slug: teamwork
      sources:
      - https://clockify.me/integrations
      - https://toggl.com/track/integrations/
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Client Services
      - Project Management
      - Task Management
      - Time Tracking
      tier: declared
      url: /providers/teamwork/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - Harvest
      - Super Productivity
      band: developing
      in_catalog: true
      kin_score: 39.6
      mcp:
        source: https://linear.app/docs/mcp
        status: verified
      name: Linear
      slug: linear-app
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Issue Tracking
      - Productivity
      - Project Management
      - Software-as-a-Service
      tier: observed
      url: /providers/linear-app/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Super Productivity
      - Toggl Track
      band: emerging
      in_catalog: true
      kin_score: 24.3
      mcp:
        status: none
      name: Redmine
      slug: redmine
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      - https://toggl.com/track/integrations/
      status: profiled
      tags:
      - Issue Tracking
      - Open Source
      - Project Management
      - Ruby on Rails
      tier: observed
      url: /providers/redmine/
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Clockify
      - Harvest
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://developers.notion.com/docs/mcp
        status: verified
      name: Notion
      slug: notion
      sources:
      - https://clockify.me/integrations
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Database
      - Ideas
      - Notes
      tier: declared
      url: /providers/notion/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Clockify
      - Toggl Track
      band: developing
      in_catalog: true
      kin_score: 50.0
      mcp:
        source: https://github.com/wrike/datahub-mcp
        status: verified
      name: Wrike
      slug: wrike
      sources:
      - https://clockify.me/integrations
      - https://toggl.com/track/integrations/
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: declared
      url: /providers/wrike/
    - agent_band: agent-aware
      agent_readiness: 24.9
      apps:
      - Clockify
      - Harvest
      band: developing
      in_catalog: true
      kin_score: 49.0
      mcp:
        source: https://github.com/basecamp/mcp
        status: verified
      name: Basecamp
      slug: basecamp
      sources:
      - https://clockify.me/integrations
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Project Management
      - REST
      - Software-as-a-Service
      tier: declared
      url: /providers/basecamp/
    - agent_band: agent-ready
      agent_readiness: 50.3
      apps:
      - Clockify
      - Harvest
      band: thin
      in_catalog: true
      kin_score: 32.2
      mcp:
        source: https://github.com/mondaycom/mcp
        status: verified
      name: Monday
      slug: monday-com
      sources:
      - https://clockify.me/integrations
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Automation
      - CRM
      - GraphQL
      - Work Management
      tier: declared
      url: /providers/monday-com/
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - Super Productivity
      band: developing
      in_catalog: true
      kin_score: 40.8
      mcp:
        source: https://www.openproject.org/docs/system-admin-guide/integrations/mcp-server/
        status: verified
      name: OpenProject
      slug: openproject
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
      status: profiled
      tags:
      - Agile
      - Gantt
      - Open Source
      - Project Management
      tier: observed
      url: /providers/openproject/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Super Productivity
      band: thin
      in_catalog: true
      kin_score: 32.7
      mcp:
        status: none
      name: Nextcloud Deck
      slug: nextcloud
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      status: profiled
      tags:
      - Collaboration
      - File Sharing
      - File Sync
      - Self-Hosted
      tier: observed
      url: /providers/nextcloud/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Super Productivity
      band: emerging
      in_catalog: true
      kin_score: 25.5
      mcp:
        source: https://help.ticktick.com/articles/7438129581631995904
        status: verified
      name: TickTick import
      slug: ticktick
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      status: profiled
      tags:
      - Calendar
      - Company
      - Productivity
      - Task Management
      tier: observed
      url: /providers/ticktick/
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - Clockify
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://github.com/Airtable/airtable-mcp-cli
        status: verified
      name: Airtable
      slug: airtable
      sources:
      - https://clockify.me/integrations
      status: profiled
      tags:
      - Application
      - Collaboration
      - Data
      - Database
      tier: declared
      url: /providers/airtable/
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Clockify
      band: developing
      in_catalog: true
      kin_score: 54.0
      mcp:
        source: https://github.com/JetBrains/mcp-server-plugin
        status: verified
      name: YouTrack
      slug: jetbrains
      sources:
      - https://clockify.me/integrations
      status: profiled
      tags:
      - CI/CD
      - Developer Tools
      - IDE
      - JetBrains
      tier: declared
      url: /providers/jetbrains/
    - agent_band: agent-ready
      agent_readiness: 42.4
      apps:
      - Toggl Track
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Podio
      slug: podio
      sources:
      - https://toggl.com/track/integrations/
      status: profiled
      tags:
      - CRM
      - Collaboration
      - Project Management
      - Work Management
      tier: declared
      url: /providers/podio/
  - capability:
      attribution: Turbo EA
      id: BC-4330.10.10
      key: BC-4330.10.10
      name: Time Entry Capture
      url: /capabilities/timekeeping-management/
      via_parent: Timekeeping Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Clockify
      - Harvest
      - Super Productivity
      - Toggl Track
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub issues
      slug: github
      sources:
      - https://clockify.me/integrations
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      - https://toggl.com/track/integrations/
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Clockify
      - Harvest
      - Toggl Track
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://clockify.me/integrations
      - https://toggl.com/track/integrations/
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Clockify
      - Super Productivity
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab issues
      slug: gitlab
      sources:
      - https://clockify.me/integrations
      - https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 37.7
      apps:
      - Clockify
      - Super Productivity
      band: exemplar
      in_catalog: true
      kin_score: 81.9
      mcp:
        source: https://github.com/microsoft/azure-devops-mcp
        status: verified
      name: Azure DevOps
      slug: microsoft-azure-devops
      sources:
      - https://clockify.me/integrations
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
      - Super Productivity
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        source: https://gitea.com/gitea/gitea-mcp
        status: verified
      name: Gitea issues
      slug: gitea
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      status: profiled
      tags:
      - CI/CD
      - DevOps
      - Gitea
      - Version Control
      tier: observed
      url: /providers/gitea/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Toggl Track
      band: exemplar
      in_catalog: true
      kin_score: 71.9
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Bitbucket
      slug: bitbucket
      sources:
      - https://toggl.com/track/integrations/
      status: profiled
      tags:
      - Atlassian
      - CI/CD
      - Code Collaboration
      - Code Review
      tier: declared
      url: /providers/bitbucket/
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - Clockify
      band: developing
      in_catalog: true
      kin_score: 51.5
      mcp:
        status: none
      name: Help Scout
      slug: helpscout
      sources:
      - https://clockify.me/integrations
      status: profiled
      tags:
      - Customer Service
      - Email
      - Help Desk
      - Live Chat
      tier: declared
      url: /providers/helpscout/
    - agent_band: agent-ready
      agent_readiness: 43.4
      apps:
      - Harvest
      band: thin
      in_catalog: true
      kin_score: 35.8
      mcp:
        status: none
      name: Freshservice
      slug: freshservice
      sources:
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Asset Management
      - Help Desk
      - ITSM
      - Ticketing
      tier: declared
      url: /providers/freshservice/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Clockify
      band: thin
      in_catalog: true
      kin_score: 29.7
      mcp:
        status: none
      name: Freshdesk
      slug: freshdesk
      sources:
      - https://clockify.me/integrations
      status: profiled
      tags:
      - Application
      - Automation
      - Customer Service
      - Help Desk
      tier: declared
      url: /providers/freshdesk/
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - Harvest
      band: thin
      in_catalog: true
      kin_score: 28.2
      mcp:
        source: https://www.zoho.com/mcp/
        status: verified
      name: Zoho Desk
      slug: zoho-desk
      sources:
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Customer Service
      - Help Desk
      - Knowledge Base
      - Ticketing
      tier: declared
      url: /providers/zoho-desk/
  - capability:
      attribution: Turbo EA
      id: BC-4330.10
      key: timekeeping-management
      name: Timekeeping Management
      url: /capabilities/timekeeping-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.0
      apps:
      - Toggl Track
      - solidtime
      band: developing
      in_catalog: true
      kin_score: 45.1
      mcp:
        status: none
      name: Harvest importer
      slug: harvest
      sources:
      - https://github.com/solidtime-io/solidtime/tree/main/app/Service/Import/Importers
      - https://toggl.com/track/integrations/
      status: profiled
      tags:
      - Expense Tracking
      - Invoicing
      - Project Management
      - Time Tracking
      tier: observed
      url: /providers/harvest/
    - agent_band: agent-aware
      agent_readiness: 24.3
      apps:
      - Toggl Track
      - solidtime
      band: thin
      in_catalog: true
      kin_score: 33.6
      mcp:
        status: none
      name: Clockify importer
      slug: clockify
      sources:
      - https://github.com/solidtime-io/solidtime/tree/main/app/Service/Import/Importers
      - https://toggl.com/track/integrations/
      status: profiled
      tags:
      - Productivity
      - Project Management
      - Time Tracking
      - Timesheets
      tier: observed
      url: /providers/clockify/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - solidtime
      band: thin
      in_catalog: true
      kin_score: 32.8
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=toggl
        status: verified
      name: Toggl Track importer
      slug: toggl
      sources:
      - https://github.com/solidtime-io/solidtime/tree/main/app/Service/Import/Importers
      status: profiled
      tags:
      - Billing
      - Productivity
      - Project Management
      - Time Tracking
      tier: observed
      url: /providers/toggl/
    - agent_band: agent-aware
      agent_readiness: 22.6
      apps:
      - Toggl Track
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        status: unknown
      name: Timely import
      slug: timely
      sources:
      - https://toggl.com/track/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Software-as-a-Service
      - Time Tracking
      tier: declared
      url: /providers/timely/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Toggl Track
      band: thin
      in_catalog: true
      kin_score: 33.0
      mcp:
        status: none
      name: Hubstaff import
      slug: hubstaff
      sources:
      - https://toggl.com/track/integrations/
      status: profiled
      tags:
      - Productivity
      - Time Tracking
      - Timesheets
      - Workforce Management
      tier: declared
      url: /providers/hubstaff/
  - capability:
      attribution: Turbo EA
      id: BC-4330.50
      key: invoice-generation-management
      name: Invoice Generation Management
      url: /capabilities/invoice-generation-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 60.0
      apps:
      - Clockify
      - Harvest
      - Toggl Track
      band: exemplar
      in_catalog: true
      kin_score: 87.1
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://clockify.me/integrations
      - https://toggl.com/track/integrations/
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: declared
      url: /providers/xero/
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Clockify
      - Harvest
      - Toggl Track
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks Online
      slug: quickbooks
      sources:
      - https://clockify.me/integrations
      - https://toggl.com/track/integrations/
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Clockify
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://clockify.me/integrations
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: declared
      url: /providers/google-sheets/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Harvest
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        source: https://github.com/databox/databox-mcp
        status: verified
      name: Databox
      slug: databox
      sources:
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Company
      - Data Integration
      tier: declared
      url: /providers/databox/
    - agent_band: null
      agent_readiness: null
      apps:
      - Harvest
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Klipfolio
      slug: klipfolio
      sources:
      - https://www.getharvest.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 52.0
      apps:
      - Harvest
      band: strong
      in_catalog: true
      kin_score: 60.9
      mcp:
        source: https://developer.deel.com/docs/mcp
        status: documented
      name: Deel
      slug: deel-com
      sources:
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Employer of Record
      - Global Payroll
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/deel-com/
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.0
      apps:
      - Toggl Track
      band: developing
      in_catalog: true
      kin_score: 53.0
      mcp:
        source: https://dev.evernote.com/
        status: documented
      name: Evernote
      slug: evernote
      sources:
      - https://toggl.com/track/integrations/
      status: profiled
      tags:
      - Company
      - Knowledge Management
      - Note Taking
      - Productivity
      tier: declared
      url: /providers/evernote/
  - capability:
      attribution: Turbo EA
      id: BC-300.70.20
      key: BC-300.70.20
      name: Payroll Administration
      url: /capabilities/hr-operations-management/
      via_parent: HR Operations Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.7
      apps:
      - Harvest
      band: developing
      in_catalog: true
      kin_score: 44.9
      mcp:
        status: none
      name: Gusto
      slug: gusto
      sources:
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Benefits
      - Enterprise Software
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/gusto/
  layer: domain
- capabilities:
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
      - Clockify
      - Harvest
      - Super Productivity
      - Toggl Track
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://clockify.me/integrations
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      - https://toggl.com/track/integrations/
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: observed
      url: /providers/google-calendar/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Clockify
      - Harvest
      band: exemplar
      in_catalog: true
      kin_score: 70.8
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Outlook
      slug: microsoft-outlook
      sources:
      - https://clockify.me/integrations
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Calendar
      - Contacts
      - Email
      - Enterprise
      tier: declared
      url: /providers/microsoft-outlook/
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - Clockify
      band: exemplar
      in_catalog: true
      kin_score: 66.8
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://clockify.me/integrations
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: declared
      url: /providers/google-gmail/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Clockify
      - Toggl Track
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google CrashLytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.toggl.giskard/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/me.clockify.android/latest/
      status: profiled
      tags: &id002
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Toggl Track
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.toggl.giskard/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Harvest
      band: exemplar
      in_catalog: true
      kin_score: 76.3
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.harvestapp/latest/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
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
      - Clockify
      - Harvest
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://clockify.me/integrations
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Harvest
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
    - agent_band: agent-ready
      agent_readiness: 42.4
      apps:
      - Harvest
      band: emerging
      in_catalog: true
      kin_score: 24.1
      mcp:
        source: https://github.com/IFTTT/ifttt-plugins
        status: verified
      name: IFTTT
      slug: ifttt
      sources:
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Automation
      - No-Code
      - Webhook
      - iPaaS
      tier: declared
      url: /providers/ifttt/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Clockify
      - Toggl Track
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://clockify.me/integrations
      - https://toggl.com/track/integrations/
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Clockify
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://clockify.me/integrations
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.2
      apps:
      - Kimai
      band: exemplar
      in_catalog: true
      kin_score: 73.1
      mcp:
        status: none
      name: Authentik SAML
      slug: authentik
      sources:
      - https://www.kimai.org/documentation/saml.html
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity Provider
      - LDAP
      tier: declared
      url: /providers/authentik/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Kimai
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/gemini-cli-extensions/workspace
        status: verified
      name: Google Workspace SAML
      slug: google-workspace
      sources:
      - https://www.kimai.org/documentation/saml.html
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/google-workspace/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Kimai
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Azure AD (Entra ID) SAML
      slug: microsoft-entra
      sources:
      - https://www.kimai.org/documentation/saml.html
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: declared
      url: /providers/microsoft-entra/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Super Productivity
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        status: none
      name: OneDrive sync
      slug: microsoft-onedrive
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/packages/sync-providers/src
      status: profiled
      tags:
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: observed
      url: /providers/microsoft-onedrive/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Super Productivity
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox sync
      slug: dropbox
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/packages/sync-providers/src
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: observed
      url: /providers/dropbox/
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
      - Harvest
      - Toggl Track
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://toggl.com/track/integrations/
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
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
      - Harvest
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: declared
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Harvest
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://www.getharvest.com/integrations
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: declared
      url: /providers/paypal/
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
      - Clockify
      - Toggl Track
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id001
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.toggl.giskard/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/me.clockify.android/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-firebase/
  layer: common
summary:
  coverage_pct: 98.3
  declared_only: 38
  distinct_providers: 60
  in_catalog: 59
  mcp:
    documented: 2
    none: 15
    unchecked: 1
    verified: 41
  mcp_verified: 41
  mean_kin_score: 58.0
  observed: 22
  queued: 1
  reference_apps: 6
title: 'Time Tracking & Timesheets: application blueprint'
---
