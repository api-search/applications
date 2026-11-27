---
app: Zuplo
app_slug: zuplo
app_url: https://zuplo.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.20
  key: AE-160.20
  layer: domain
  name: Authorization for Apps
  providers:
  - Axiomatics
  - OpenFGA
  url: /capabilities/authorization-for-apps/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: domain
  name: Identity & Access Management
  providers:
  - Amazon Cognito
  - Auth0
  - AWS
  - Clerk
  - Curity
  - Firebase
  - Google Cloud
  - Google OAuth
  - Keycloak
  - Logto
  - Microsoft Entra
  - Okta
  - OneLogin
  - Ping Identity
  - PropelAuth
  - Supabase
  - WorkOS
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2660.10
  key: usage-mediation-management
  layer: domain
  name: Usage Mediation Management
  providers:
  - Amberflo
  - Moesif
  - OpenMeter
  - ReadMe
  url: /capabilities/usage-mediation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4270.80
  key: BC-4270.80
  layer: domain
  name: Webhook & Event Subscription Management
  providers:
  - Stripe
  url: /capabilities/webhook-event-subscription-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - AWS CloudWatch
  - Datadog
  - Dynatrace
  - Google Cloud Logging
  - Grafana Loki
  - New Relic
  - Splunk
  - Sumo Logic
  - VMware Log Insight
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-100.60.20
  key: AE-100.60.20
  layer: agent
  name: Agent Observability
  providers:
  - Comet Opik
  - Galileo
  url: /capabilities/agent-quality-operations/
  via_parent: Agent Quality & Operations
- attribution: API Evangelist extension
  id: AE-100.50.20
  key: AE-100.50.20
  layer: agent
  name: Agent Security & Guardrails
  providers:
  - Akamai
  url: /capabilities/agent-identity-trust/
  via_parent: Agent Identity & Trust
category:
  id: api-management-gateway
  name: API Management & Gateways
  url: /applications/api-management-gateway/
counts:
  declared: 36
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://zuplo.com/docs/articles/logging
- route: documentation
  url: https://zuplo.com/docs/policies
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-100.50.20
    key: AE-100.50.20
    name: Agent Security & Guardrails
    url: /capabilities/agent-identity-trust/
    via_parent: Agent Identity & Trust
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.0
    band: developing
    in_catalog: true
    kin_score: 53.8
    mcp: &id001
      status: none
    slug: akamai
    status: profiled
    tags: &id002
    - CDN
    - Cloud
    - Edge Computing
    - Networks
    url: /providers/akamai/
  layer: agent
  name: Akamai
  provider: akamai
  says: lists Akamai as an integration
  source: https://zuplo.com/docs/policies
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
    agent_readiness: 37.3
    band: exemplar
    in_catalog: true
    kin_score: 74.5
    mcp: &id003
      status: none
    slug: amazon-cognito
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Authentication
    - Identity
    - OpenID Connect
    url: /providers/amazon-cognito/
  layer: domain
  name: Amazon Cognito
  provider: amazon-cognito
  says: lists Amazon Cognito as an integration
  source: https://zuplo.com/docs/policies
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2660.10
    key: usage-mediation-management
    name: Usage Mediation Management
    url: /capabilities/usage-mediation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: developing
    in_catalog: true
    kin_score: 45.3
    mcp: &id005
      status: none
    slug: amberflo
    status: profiled
    tags: &id006
    - AI Cost Management
    - FinOps
    - Metering
    - Usage-Based Billing
    url: /providers/amberflo/
  layer: domain
  name: Amberflo
  provider: amberflo
  says: lists Amberflo as an integration
  source: https://zuplo.com/docs/policies
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
    agent_readiness: 39.5
    band: exemplar
    in_catalog: true
    kin_score: 71.8
    mcp: &id007
      source: https://auth0.com/docs/get-started/auth0-mcp-server
      status: verified
    slug: auth0
    status: profiled
    tags: &id008
    - AI Agents
    - Auth0
    - Authentication
    - Authorization
    url: /providers/auth0/
  layer: domain
  name: Auth0
  provider: auth0
  says: lists Auth0 as an integration
  source: https://zuplo.com/docs/policies
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
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id009
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id010
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: domain
  name: AWS
  provider: amazon-web-services
  says: lists AWS as an integration
  source: https://zuplo.com/docs/policies
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
    mcp: &id011
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-cloudwatch
    status: profiled
    tags: &id012
    - Amazon Web Services
    - CloudWatch
    - Monitoring
    - Observability
    url: /providers/amazon-cloudwatch/
  layer: common
  name: AWS CloudWatch
  provider: amazon-cloudwatch
  says: lists AWS CloudWatch as an integration
  source: https://zuplo.com/docs/articles/logging
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.20
    key: AE-160.20
    name: Authorization for Apps
    url: /capabilities/authorization-for-apps/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.5
    band: thin
    in_catalog: true
    kin_score: 33.6
    mcp: &id013
      status: none
    slug: axiomatics
    status: profiled
    tags: &id014
    - Authorization
    - Company
    - Policy
    - Zero Trust
    url: /providers/axiomatics/
  layer: domain
  name: Axiomatics
  provider: axiomatics
  says: lists Axiomatics as an integration
  source: https://zuplo.com/docs/policies
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
    agent_band: agent-native
    agent_readiness: 51.9
    band: exemplar
    in_catalog: true
    kin_score: 73.4
    mcp: &id015
      source: https://github.com/clerk/mcp-tools
      status: verified
    slug: clerk-com
    status: profiled
    tags: &id016
    - Authentication
    - Authorization
    - B2B SaaS
    - CIAM
    url: /providers/clerk-com/
  layer: domain
  name: Clerk
  provider: clerk-com
  says: lists Clerk as an integration
  source: https://zuplo.com/docs/policies
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-100.60.20
    key: AE-100.60.20
    name: Agent Observability
    url: /capabilities/agent-quality-operations/
    via_parent: Agent Quality & Operations
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 45.8
    mcp: &id017
      source: https://github.com/comet-ml/opik-mcp
      status: verified
    slug: opik
    status: profiled
    tags: &id018
    - Evaluation
    - LLM
    - Observability
    - Tracing
    url: /providers/opik/
  layer: agent
  name: Comet Opik
  provider: opik
  says: lists Comet Opik as an integration
  source: https://zuplo.com/docs/policies
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
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 27.1
    mcp: &id019
      status: none
    slug: curity
    status: profiled
    tags: &id020
    - Company
    - Identity
    - OAuth
    - OpenID Connect
    url: /providers/curity/
  layer: domain
  name: Curity
  provider: curity
  says: lists Curity as an integration
  source: https://zuplo.com/docs/policies
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
    mcp: &id021
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id022
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: common
  name: Datadog
  provider: datadog
  says: lists Datadog as an integration
  source: https://zuplo.com/docs/articles/logging
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
    agent_readiness: 43.8
    band: exemplar
    in_catalog: true
    kin_score: 85.6
    mcp: &id023
      source: https://github.com/dynatrace-oss/dynatrace-mcp
      status: verified
    slug: dynatrace
    status: profiled
    tags: &id024
    - AI Operations
    - APM
    - Analytics
    - Application Performance Monitoring
    url: /providers/dynatrace/
  layer: common
  name: Dynatrace
  provider: dynatrace
  says: lists Dynatrace as an integration
  source: https://zuplo.com/docs/articles/logging
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
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id025
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id026
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: domain
  name: Firebase
  provider: firebase
  says: lists Firebase as an integration
  source: https://zuplo.com/docs/policies
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-100.60.20
    key: AE-100.60.20
    name: Agent Observability
    url: /capabilities/agent-quality-operations/
    via_parent: Agent Quality & Operations
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.8
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id027
      source: https://docs.galileo.ai/getting-started/mcp/setup-galileo-mcp
      status: verified
    slug: galileo-technologies
    status: profiled
    tags: &id028
    - AI Observability
    - Company
    - Generative AI
    - LLM Evaluation
    url: /providers/galileo-technologies/
  layer: agent
  name: Galileo
  provider: galileo-technologies
  says: lists Galileo as an integration
  source: https://zuplo.com/docs/policies
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
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 67.5
    mcp: &id029
      source: https://github.com/googleapis/mcp-toolbox
      status: verified
    slug: google-cloud-platform
    status: profiled
    tags: &id030
    - API Management
    - Cloud Computing
    - Infrastructure
    - Platform-as-a-Service
    url: /providers/google-cloud-platform/
  layer: domain
  name: Google Cloud
  provider: google-cloud-platform
  says: lists Google Cloud as an integration
  source: https://zuplo.com/docs/policies
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
    agent_readiness: 49.5
    band: exemplar
    in_catalog: true
    kin_score: 76.2
    mcp: &id031
      source: https://raw.githubusercontent.com/googleapis/gcloud-mcp/main/README.md
      status: verified
    slug: google-cloud-logging
    status: profiled
    tags: &id032
    - Cloud
    - Logging
    - Monitoring
    - Observability
    url: /providers/google-cloud-logging/
  layer: common
  name: Google Cloud Logging
  provider: google-cloud-logging
  says: lists Google Cloud Logging as an integration
  source: https://zuplo.com/docs/articles/logging
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
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id033
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id034
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: domain
  name: Google OAuth
  provider: google-identity-platform
  says: lists Google OAuth as an integration
  source: https://zuplo.com/docs/policies
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
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 28.8
    mcp: &id035
      source: https://github.com/grafana/loki-mcp
      status: verified
    slug: loki
    status: profiled
    tags: &id036
    - Grafana
    - Logging
    - Observability
    - Open Source
    url: /providers/loki/
  layer: common
  name: Grafana Loki
  provider: loki
  says: lists Grafana Loki as an integration
  source: https://zuplo.com/docs/articles/logging
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
    agent_band: agent-aware
    agent_readiness: 17.3
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id037
      status: none
    slug: keycloak
    status: profiled
    tags: &id038
    - Authentication
    - Authorization
    - Identity and Access Management
    - OAuth
    url: /providers/keycloak/
  layer: domain
  name: Keycloak
  provider: keycloak
  says: lists Keycloak as an integration
  source: https://zuplo.com/docs/policies
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
    agent_band: agent-aware
    agent_readiness: 26.0
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id039
      status: none
    slug: logto
    status: profiled
    tags: &id040
    - Authentication
    - Authorization
    - Identity
    - OpenID Connect
    url: /providers/logto/
  layer: domain
  name: Logto
  provider: logto
  says: lists Logto as an integration
  source: https://zuplo.com/docs/policies
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
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id041
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id042
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: domain
  name: Microsoft Entra
  provider: microsoft-entra
  says: lists Microsoft Entra as an integration
  source: https://zuplo.com/docs/policies
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2660.10
    key: usage-mediation-management
    name: Usage Mediation Management
    url: /capabilities/usage-mediation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.4
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id043
      status: none
    slug: moesif
    status: profiled
    tags: &id044
    - Analytics
    - Governance
    - Monetization
    - Monitoring
    url: /providers/moesif/
  layer: domain
  name: Moesif
  provider: moesif
  says: lists Moesif as an integration
  source: https://zuplo.com/docs/policies
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
    mcp: &id045
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id046
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic
  provider: new-relic
  says: lists New Relic as an integration
  source: https://zuplo.com/docs/articles/logging
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
    mcp: &id047
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id048
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: domain
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://zuplo.com/docs/policies
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
    agent_band: agent-aware
    agent_readiness: 24.3
    band: thin
    in_catalog: true
    kin_score: 29.5
    mcp: &id049
      source: https://github.com/onelogin/onelogin-mcp
      status: verified
    slug: onelogin
    status: profiled
    tags: &id050
    - Identity
    - Identity and Access Management
    - Multi-Factor Authentication
    - SSO
    url: /providers/onelogin/
  layer: domain
  name: OneLogin
  provider: onelogin
  says: lists OneLogin as an integration
  source: https://zuplo.com/docs/policies
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.20
    key: AE-160.20
    name: Authorization for Apps
    url: /capabilities/authorization-for-apps/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.1
    band: emerging
    in_catalog: true
    kin_score: 23.8
    mcp: &id051
      status: none
    slug: openfga
    status: profiled
    tags: &id052
    - Access Control
    - Authorization
    - Cloud-Native
    - Fine-Grained
    url: /providers/openfga/
  layer: domain
  name: OpenFGA
  provider: openfga
  says: lists OpenFGA as an integration
  source: https://zuplo.com/docs/policies
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2660.10
    key: usage-mediation-management
    name: Usage Mediation Management
    url: /capabilities/usage-mediation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.5
    band: thin
    in_catalog: true
    kin_score: 32.0
    mcp: &id053
      status: none
    slug: openmeter
    status: profiled
    tags: &id054
    - Billing
    - CloudEvents
    - Entitlements
    - Usage Metering
    url: /providers/openmeter/
  layer: domain
  name: OpenMeter
  provider: openmeter
  says: lists OpenMeter as an integration
  source: https://zuplo.com/docs/policies
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
    agent_readiness: 40.9
    band: strong
    in_catalog: true
    kin_score: 55.9
    mcp: &id055
      source: https://github.com/pingidentity/pingone-mcp-server
      status: verified
    slug: ping-identity
    status: profiled
    tags: &id056
    - Authentication
    - Authorization
    - Identity
    - SSO
    url: /providers/ping-identity/
  layer: domain
  name: Ping Identity
  provider: ping-identity
  says: lists Ping Identity as an integration
  source: https://zuplo.com/docs/policies
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
    agent_band: agent-aware
    agent_readiness: 27.2
    band: strong
    in_catalog: true
    kin_score: 58.7
    mcp: &id057
      status: none
    slug: propelauth
    status: profiled
    tags: &id058
    - Authentication
    - B2B
    - Identity
    - Multi-Tenancy
    url: /providers/propelauth/
  layer: domain
  name: PropelAuth
  provider: propelauth
  says: lists PropelAuth as an integration
  source: https://zuplo.com/docs/policies
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2660.10
    key: usage-mediation-management
    name: Usage Mediation Management
    url: /capabilities/usage-mediation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.1
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id059
      source: https://docs.readme.com/main/docs/mcp
      status: verified
    slug: readme
    status: profiled
    tags: &id060
    - API Reference
    - Developer Hub
    - Documentation
    - Portal
    url: /providers/readme/
  layer: domain
  name: ReadMe
  provider: readme
  says: lists ReadMe as an integration
  source: https://zuplo.com/docs/policies
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
  layer: common
  name: Splunk
  provider: splunk
  says: lists Splunk as an integration
  source: https://zuplo.com/docs/articles/logging
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4270.80
    key: BC-4270.80
    name: Webhook & Event Subscription Management
    url: /capabilities/webhook-event-subscription-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id063
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id064
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://zuplo.com/docs/policies
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
    agent_readiness: 48.2
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id065
      source: https://docs.sumologic.com/docs/search/mobot/
      status: documented
    slug: sumo-logic
    status: profiled
    tags: &id066
    - Logging
    - Monitoring
    - Observability
    - Security
    url: /providers/sumo-logic/
  layer: common
  name: Sumo Logic
  provider: sumo-logic
  says: lists Sumo Logic as an integration
  source: https://zuplo.com/docs/articles/logging
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
    agent_readiness: 48.2
    band: developing
    in_catalog: true
    kin_score: 49.4
    mcp: &id067
      source: https://github.com/supabase/mcp
      status: verified
    slug: supabase
    status: profiled
    tags: &id068
    - Authentication
    - Backend-as-a-Service
    - Open Source
    - PostgreSQL
    url: /providers/supabase/
  layer: domain
  name: Supabase
  provider: supabase
  says: lists Supabase as an integration
  source: https://zuplo.com/docs/policies
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
    agent_readiness: 23.3
    band: developing
    in_catalog: true
    kin_score: 49.8
    mcp: &id069
      status: none
    slug: vmware
    status: profiled
    tags: &id070
    - Cloud Computing
    - Container Management
    - Hybrid Cloud
    - Infrastructure
    url: /providers/vmware/
  layer: common
  name: VMware Log Insight
  provider: vmware
  says: lists VMware Log Insight as an integration
  source: https://zuplo.com/docs/articles/logging
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
    agent_readiness: 57.7
    band: strong
    in_catalog: true
    kin_score: 60.2
    mcp: &id071
      source: https://workos.com/docs/mcp
      status: verified
    slug: workos
    status: profiled
    tags: &id072
    - Authentication
    - Identity Provider
    - SAML
    - SSO
    url: /providers/workos/
  layer: domain
  name: WorkOS
  provider: workos
  says: lists WorkOS as an integration
  source: https://zuplo.com/docs/policies
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/api-management-gateway/zuplo/
providers:
- agent_band: agent-ready
  agent_readiness: 40.0
  band: developing
  in_catalog: true
  kin_score: 53.8
  mcp: *id001
  name: Akamai
  slug: akamai
  status: profiled
  tags: *id002
  url: /providers/akamai/
- agent_band: agent-ready
  agent_readiness: 37.3
  band: exemplar
  in_catalog: true
  kin_score: 74.5
  mcp: *id003
  name: Amazon Cognito
  slug: amazon-cognito
  status: profiled
  tags: *id004
  url: /providers/amazon-cognito/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: developing
  in_catalog: true
  kin_score: 45.3
  mcp: *id005
  name: Amberflo
  slug: amberflo
  status: profiled
  tags: *id006
  url: /providers/amberflo/
- agent_band: agent-ready
  agent_readiness: 39.5
  band: exemplar
  in_catalog: true
  kin_score: 71.8
  mcp: *id007
  name: Auth0
  slug: auth0
  status: profiled
  tags: *id008
  url: /providers/auth0/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id009
  name: AWS
  slug: amazon-web-services
  status: profiled
  tags: *id010
  url: /providers/amazon-web-services/
- agent_band: agent-native
  agent_readiness: 43.4
  band: exemplar
  in_catalog: true
  kin_score: 77.4
  mcp: *id011
  name: AWS CloudWatch
  slug: amazon-cloudwatch
  status: profiled
  tags: *id012
  url: /providers/amazon-cloudwatch/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id013
  name: Axiomatics
  slug: axiomatics
  status: profiled
  tags: *id014
  url: /providers/axiomatics/
- agent_band: agent-native
  agent_readiness: 51.9
  band: exemplar
  in_catalog: true
  kin_score: 73.4
  mcp: *id015
  name: Clerk
  slug: clerk-com
  status: profiled
  tags: *id016
  url: /providers/clerk-com/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 45.8
  mcp: *id017
  name: Comet Opik
  slug: opik
  status: profiled
  tags: *id018
  url: /providers/opik/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 27.1
  mcp: *id019
  name: Curity
  slug: curity
  status: profiled
  tags: *id020
  url: /providers/curity/
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id021
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id022
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 43.8
  band: exemplar
  in_catalog: true
  kin_score: 85.6
  mcp: *id023
  name: Dynatrace
  slug: dynatrace
  status: profiled
  tags: *id024
  url: /providers/dynatrace/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id025
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id026
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 33.8
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id027
  name: Galileo
  slug: galileo-technologies
  status: profiled
  tags: *id028
  url: /providers/galileo-technologies/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 67.5
  mcp: *id029
  name: Google Cloud
  slug: google-cloud-platform
  status: profiled
  tags: *id030
  url: /providers/google-cloud-platform/
- agent_band: agent-ready
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 76.2
  mcp: *id031
  name: Google Cloud Logging
  slug: google-cloud-logging
  status: profiled
  tags: *id032
  url: /providers/google-cloud-logging/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id033
  name: Google OAuth
  slug: google-identity-platform
  status: profiled
  tags: *id034
  url: /providers/google-identity-platform/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id035
  name: Grafana Loki
  slug: loki
  status: profiled
  tags: *id036
  url: /providers/loki/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id037
  name: Keycloak
  slug: keycloak
  status: profiled
  tags: *id038
  url: /providers/keycloak/
- agent_band: agent-aware
  agent_readiness: 26.0
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id039
  name: Logto
  slug: logto
  status: profiled
  tags: *id040
  url: /providers/logto/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id041
  name: Microsoft Entra
  slug: microsoft-entra
  status: profiled
  tags: *id042
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id043
  name: Moesif
  slug: moesif
  status: profiled
  tags: *id044
  url: /providers/moesif/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id045
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id046
  url: /providers/new-relic/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id047
  name: Okta
  slug: okta
  status: profiled
  tags: *id048
  url: /providers/okta/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id049
  name: OneLogin
  slug: onelogin
  status: profiled
  tags: *id050
  url: /providers/onelogin/
- agent_band: agent-ready
  agent_readiness: 35.1
  band: emerging
  in_catalog: true
  kin_score: 23.8
  mcp: *id051
  name: OpenFGA
  slug: openfga
  status: profiled
  tags: *id052
  url: /providers/openfga/
- agent_band: agent-aware
  agent_readiness: 25.5
  band: thin
  in_catalog: true
  kin_score: 32.0
  mcp: *id053
  name: OpenMeter
  slug: openmeter
  status: profiled
  tags: *id054
  url: /providers/openmeter/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: strong
  in_catalog: true
  kin_score: 55.9
  mcp: *id055
  name: Ping Identity
  slug: ping-identity
  status: profiled
  tags: *id056
  url: /providers/ping-identity/
- agent_band: agent-aware
  agent_readiness: 27.2
  band: strong
  in_catalog: true
  kin_score: 58.7
  mcp: *id057
  name: PropelAuth
  slug: propelauth
  status: profiled
  tags: *id058
  url: /providers/propelauth/
- agent_band: agent-ready
  agent_readiness: 34.1
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id059
  name: ReadMe
  slug: readme
  status: profiled
  tags: *id060
  url: /providers/readme/
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
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id063
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id064
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 48.2
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id065
  name: Sumo Logic
  slug: sumo-logic
  status: profiled
  tags: *id066
  url: /providers/sumo-logic/
- agent_band: agent-ready
  agent_readiness: 48.2
  band: developing
  in_catalog: true
  kin_score: 49.4
  mcp: *id067
  name: Supabase
  slug: supabase
  status: profiled
  tags: *id068
  url: /providers/supabase/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: developing
  in_catalog: true
  kin_score: 49.8
  mcp: *id069
  name: VMware Log Insight
  slug: vmware
  status: profiled
  tags: *id070
  url: /providers/vmware/
- agent_band: agent-ready
  agent_readiness: 57.7
  band: strong
  in_catalog: true
  kin_score: 60.2
  mcp: *id071
  name: WorkOS
  slug: workos
  status: profiled
  tags: *id072
  url: /providers/workos/
siblings:
- name: Apache APISIX
  rows: 36
  url: /applications/api-management-gateway/apache-apisix/
- name: Hoppscotch
  rows: 4
  url: /applications/api-management-gateway/hoppscotch/
- name: Kong Gateway
  rows: 17
  url: /applications/api-management-gateway/kong-gateway/
- name: KrakenD CE
  rows: 12
  url: /applications/api-management-gateway/krakend-ce/
- name: Postman
  rows: 20
  url: /applications/api-management-gateway/postman/
- name: Traefik Proxy
  rows: 15
  url: /applications/api-management-gateway/traefik-proxy/
- name: Tyk Gateway + Tyk Pump
  rows: 24
  url: /applications/api-management-gateway/tyk-gateway-tyk-pump/
sitemap: true
title: 'Zuplo: API Management & Gateways reference app'
---
