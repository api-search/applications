---
access: understanding
agent_layer: []
apps:
- anchor: keycloak
  counts:
    declared: 0
    observed: 12
  evidence:
  - route: source code
    url: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Bitbucket
    provider: bitbucket
    says: ships the Bitbucket SDK or integration code
    source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Instagram
    provider: instagram
    says: ships the Instagram SDK or integration code
    source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: LinkedIn
    provider: linkedin
    says: ships the LinkedIn SDK or integration code
    source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Microsoft
    provider: microsoft-entra
    says: ships the Microsoft SDK or integration code
    source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Red Hat OpenShift
    provider: red-hat-openshift
    says: ships the Red Hat OpenShift SDK or integration code
    source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Stack Overflow
    provider: stack-overflow
    says: ships the Stack Overflow SDK or integration code
    source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: X (Twitter)
    provider: x
    says: ships the X (Twitter) SDK or integration code
    source: https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
    tier: observed
  kind: self-hosted
  name: Keycloak
  page: /applications/identity-access/keycloak/
  slug: keycloak
  url: https://github.com/keycloak/keycloak
- anchor: authentik
  counts:
    declared: 0
    observed: 20
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/goauthentik/authentik/main/pyproject.toml
  - route: source code
    url: https://github.com/goauthentik/authentik/tree/main/authentik/enterprise/providers
  - route: source code
    url: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
  - route: source code
    url: https://raw.githubusercontent.com/goauthentik/authentik/main/authentik/stages/authenticator_sms/models.py
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.20
      key: AE-160.10.20
      name: Multi-Factor Authentication
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Duo Security
    provider: duo-security
    says: ships the Duo Security SDK or integration code
    source: https://raw.githubusercontent.com/goauthentik/authentik/main/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Workspace
    provider: google-workspace
    says: ships the Google Workspace SDK or integration code
    source: https://github.com/goauthentik/authentik/tree/main/authentik/enterprise/providers
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
    name: MaxMind GeoIP2
    provider: maxmind
    says: ships the MaxMind GeoIP2 SDK or integration code
    source: https://raw.githubusercontent.com/goauthentik/authentik/main/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Entra ID
    provider: microsoft-entra
    says: ships the Microsoft Entra ID SDK or integration code
    source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Graph
    provider: microsoft-graph
    says: ships the Microsoft Graph SDK or integration code
    source: https://raw.githubusercontent.com/goauthentik/authentik/main/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Okta
    provider: okta
    says: ships the Okta SDK or integration code
    source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Patreon
    provider: patreon
    says: ships the Patreon SDK or integration code
    source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Reddit
    provider: reddit
    says: ships the Reddit SDK or integration code
    source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
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
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://raw.githubusercontent.com/goauthentik/authentik/main/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Sign in with Apple
    provider: apple
    says: ships the Sign in with Apple SDK or integration code
    source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://raw.githubusercontent.com/goauthentik/authentik/main/authentik/stages/authenticator_sms/models.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Twitch
    provider: twitch
    says: ships the Twitch SDK or integration code
    source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: WeChat
    provider: wechat
    says: ships the WeChat SDK or integration code
    source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: X (Twitter)
    provider: x
    says: ships the X (Twitter) SDK or integration code
    source: https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
    tier: observed
  kind: self-hosted
  name: Authentik
  page: /applications/identity-access/authentik/
  slug: authentik
  url: https://github.com/goauthentik/authentik
- anchor: zitadel
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/zitadel/zitadel/main/go.mod
  - route: source code
    url: https://github.com/zitadel/zitadel/tree/main/internal/idp/providers
  - route: source code
    url: https://github.com/zitadel/zitadel/tree/main/internal/notification/channels
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/zitadel/zitadel/tree/main/internal/idp/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/zitadel/zitadel/tree/main/internal/idp/providers
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
    name: Google Cloud Profiler
    provider: google-cloud-profiler
    says: ships the Google Cloud Profiler SDK or integration code
    source: https://raw.githubusercontent.com/zitadel/zitadel/main/go.mod
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
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://raw.githubusercontent.com/zitadel/zitadel/main/go.mod
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://github.com/zitadel/zitadel/tree/main/internal/idp/providers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Entra ID
    provider: microsoft-entra
    says: ships the Microsoft Entra ID SDK or integration code
    source: https://github.com/zitadel/zitadel/tree/main/internal/idp/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Sign in with Apple
    provider: apple
    says: ships the Sign in with Apple SDK or integration code
    source: https://github.com/zitadel/zitadel/tree/main/internal/idp/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://raw.githubusercontent.com/zitadel/zitadel/main/go.mod
    tier: observed
  kind: open-source-saas
  name: Zitadel
  page: /applications/identity-access/zitadel/
  slug: zitadel
  url: https://github.com/zitadel/zitadel
- anchor: authelia
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/authelia/authelia/master/go.mod
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.20
      key: AE-160.10.20
      name: Multi-Factor Authentication
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Duo Security
    provider: duo-security
    says: ships the Duo Security SDK or integration code
    source: https://raw.githubusercontent.com/authelia/authelia/master/go.mod
    tier: observed
  kind: self-hosted
  name: Authelia
  page: /applications/identity-access/authelia/
  slug: authelia
  url: https://github.com/authelia/authelia
- anchor: ory-kratos
  counts:
    declared: 0
    observed: 22
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/ory/kratos/master/go.mod
  - route: source code
    url: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Auth0
    provider: auth0
    says: ships the Auth0 SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: DingTalk
    provider: dingtalk
    says: ships the DingTalk SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Lark / Feishu
    provider: larksuite
    says: ships the Lark / Feishu SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: LINE
    provider: line
    says: ships the LINE SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: LinkedIn
    provider: linkedin
    says: ships the LinkedIn SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Login with Amazon
    provider: amazon
    says: ships the Login with Amazon SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft
    provider: microsoft-entra
    says: ships the Microsoft SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: netID
    provider: netid
    says: ships the netID SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Patreon
    provider: patreon
    says: ships the Patreon SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: ships the Salesforce SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Sign in with Apple
    provider: apple
    says: ships the Sign in with Apple SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Spotify
    provider: spotify
    says: ships the Spotify SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: UAE PASS
    provider: uae-pass
    says: ships the UAE PASS SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: VK
    provider: vk
    says: ships the VK SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: X
    provider: x
    says: ships the X SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Yandex ID
    provider: yandex
    says: ships the Yandex ID SDK or integration code
    source: https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
    tier: observed
  kind: open-source-saas
  name: Ory Kratos
  page: /applications/identity-access/ory-kratos/
  slug: ory-kratos
  url: https://github.com/ory/kratos
- anchor: casdoor
  counts:
    declared: 14
    observed: 26
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/casdoor/casdoor/master/go.mod
  - route: documentation
    url: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
  - route: source code
    url: https://github.com/casdoor/casdoor/tree/master/idp
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30
      key: AE-160.30
      name: Identity Verification
      url: /capabilities/identity-verification/
      via_parent: null
    credit: null
    layer: domain
    name: Alibaba Cloud
    provider: alibaba
    says: ships the Alibaba Cloud SDK or integration code
    source: https://raw.githubusercontent.com/casdoor/casdoor/master/go.mod
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Alipay
    provider: ant-group
    says: ships the Alipay SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
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
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/casdoor/casdoor/master/go.mod
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Azure AD B2C
    provider: microsoft-entra
    says: ships the Azure AD B2C SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Baidu
    provider: baidu
    says: ships the Baidu SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Bilibili
    provider: bilibili
    says: ships the Bilibili SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: DingTalk
    provider: dingtalk
    says: ships the DingTalk SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Douyin
    provider: bytedance
    says: ships the Douyin SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Gitee
    provider: gitee
    says: ships the Gitee SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
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
    name: Google
    provider: google
    says: ships the Google SDK or integration code
    source: https://raw.githubusercontent.com/casdoor/casdoor/master/go.mod
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Kwai
    provider: kuaishou
    says: ships the Kwai SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Lark / Feishu
    provider: larksuite
    says: ships the Lark / Feishu SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: LinkedIn
    provider: linkedin
    says: ships the LinkedIn SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Okta
    provider: okta
    says: ships the Okta SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: QQ
    provider: tencent-qq
    says: ships the QQ SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
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
    source: https://raw.githubusercontent.com/casdoor/casdoor/master/go.mod
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
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://raw.githubusercontent.com/casdoor/casdoor/master/go.mod
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: WeChat
    provider: wechat
    says: ships the WeChat SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: WeCom
    provider: wecom
    says: ships the WeCom SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Weibo
    provider: weibo
    says: ships the Weibo SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: X (Twitter)
    provider: x
    says: ships the X (Twitter) SDK or integration code
    source: https://github.com/casdoor/casdoor/tree/master/idp
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Amazon SNS
    provider: amazon-sns
    says: lists Amazon SNS as an integration
    source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Azure Communication Services
    provider: microsoft-azure-communication-services
    says: lists Azure Communication Services as an integration
    source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: GCCPAY
    provider: gccpay
    says: lists GCCPAY as an integration
    source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Huawei Cloud SMS
    provider: huaweicloud
    says: lists Huawei Cloud SMS as an integration
    source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Huyi
    provider: huyi
    says: lists Huyi as an integration
    source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Infobip
    provider: infobip
    says: lists Infobip as an integration
    source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Netgsm
    provider: netgsm
    says: lists Netgsm as an integration
    source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Oson SMS
    provider: osonsms
    says: lists Oson SMS as an integration
    source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: SmsBao
    provider: smsbao
    says: lists SmsBao as an integration
    source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: SUBMAIL
    provider: submail
    says: lists SUBMAIL as an integration
    source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Tencent Cloud SMS
    provider: tencentcloud
    says: lists Tencent Cloud SMS as an integration
    source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: lists Twilio as an integration
    source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: UCloud USMS
    provider: ucloud
    says: lists UCloud USMS as an integration
    source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: VolcEngine SMS
    provider: volcengine
    says: lists VolcEngine SMS as an integration
    source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
    tier: declared
  kind: open-source-saas
  name: Casdoor
  page: /applications/identity-access/casdoor/
  slug: casdoor
  url: https://github.com/casdoor/casdoor
- anchor: logto
  counts:
    declared: 0
    observed: 39
  evidence:
  - route: source code
    url: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    name: Alibaba Cloud DirectMail
    provider: alibaba
    says: ships the Alibaba Cloud DirectMail SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Alibaba Cloud SMS
    provider: alibaba
    says: ships the Alibaba Cloud SMS SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Alipay
    provider: ant-group
    says: ships the Alipay SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    name: Amazon SES
    provider: amazon-ses
    says: ships the Amazon SES SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: DingTalk
    provider: dingtalk
    says: ships the DingTalk SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Feishu
    provider: larksuite
    says: ships the Feishu SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: GatewayAPI
    provider: gatewayapi
    says: ships the GatewayAPI SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Hugging Face
    provider: hugging-face
    says: ships the Hugging Face SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Kakao
    provider: kakao
    says: ships the Kakao SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: KOOK
    provider: kook
    says: ships the KOOK SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: LINE
    provider: line
    says: ships the LINE SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: LinkedIn
    provider: linkedin
    says: ships the LinkedIn SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Login with Amazon
    provider: amazon
    says: ships the Login with Amazon SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    name: Mailgun
    provider: mailgun
    says: ships the Mailgun SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Entra ID
    provider: microsoft-entra
    says: ships the Microsoft Entra ID SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Naver
    provider: naver
    says: ships the Naver SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Patreon
    provider: patreon
    says: ships the Patreon SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    name: Postmark
    provider: postmark
    says: ships the Postmark SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: QQ
    provider: tencent-qq
    says: ships the QQ SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Sign in with Apple
    provider: apple
    says: ships the Sign in with Apple SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: SMS Aero
    provider: smsaero
    says: ships the SMS Aero SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: SmsBao
    provider: smsbao
    says: ships the SmsBao SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    name: SMTP2GO
    provider: smtp2go
    says: ships the SMTP2GO SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Tencent Cloud SMS
    provider: tencentcloud
    says: ships the Tencent Cloud SMS SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Vonage
    provider: vonage
    says: ships the Vonage SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: WeChat
    provider: wechat
    says: ships the WeChat SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: WeCom
    provider: wecom
    says: ships the WeCom SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: WhatsApp
    provider: whatsapp
    says: ships the WhatsApp SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: X
    provider: x
    says: ships the X SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Xiaomi
    provider: xiaomi
    says: ships the Xiaomi SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Yunpian
    provider: yunpian
    says: ships the Yunpian SDK or integration code
    source: https://github.com/logto-io/logto/tree/master/packages/connectors
    tier: observed
  kind: open-source-saas
  name: Logto
  page: /applications/identity-access/logto/
  slug: logto
  url: https://github.com/logto-io/logto
- anchor: okta-verify
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.okta.android.auth/latest/
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
    name: Firebase (Crashlytics)
    provider: firebase
    says: ships the Firebase (Crashlytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.okta.android.auth/latest/
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
    name: Firebase Analytics
    provider: firebase
    says: ships the Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.okta.android.auth/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.okta.android.auth/latest/
    tier: observed
  kind: commercial
  name: Okta Verify
  page: /applications/identity-access/okta-verify/
  slug: okta-verify
  url: https://www.okta.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: identity-access
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
- category: Identity Management
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#identity-management
- category: Federated Identity & Authentication
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#federated-identity--authentication
- category: Security
  store: atlassian-marketplace
  url: https://marketplace.atlassian.com/
- category: Security
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: IT Operations
  store: zapier
  url: https://zapier.com/apps
name: Identity, SSO & Access Management
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-160
    key: AE-160
    name: Application Identity & Verification
    url: /capabilities/application-identity-verification/
    via_parent: null
  fit: exact
  layer: domain
  why: social / consumer sign-in connectors (AE-160.10.30), second factors (AE-160.10.20) and identity verification (AE-160.30) are the bulk of every IdP; BC model has no customer sign-in capability
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: domain
  why: 'workforce IdPs brokered upstream: Entra ID, Okta, Auth0, Salesforce'
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: domain
  why: outbound user/group provisioning to Google Workspace and Microsoft Entra (joiners-movers-leavers)
- capability:
    attribution: API Evangelist extension
    id: AE-150
    key: AE-150
    name: Application Communications
    url: /capabilities/application-communications/
    via_parent: null
  fit: exact
  layer: common
  why: SMS OTP (AE-150.20.30) and transactional email (AE-150.10.10) for verification and recovery
- capability:
    attribution: API Evangelist extension
    id: AE-120
    key: AE-120
    name: Location & Mapping
    url: /capabilities/location-mapping/
    via_parent: null
  fit: exact
  layer: common
  why: IP geolocation (AE-120.50.10) for GeoIP policies
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring and profiling
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: mobile authenticator app telemetry
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: object storage for avatars and assets; no generic object-storage capability
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: Casdoor bundles a payment provider
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Authentik
      - Casdoor
      - Keycloak
      - Logto
      - Ory Kratos
      - Zitadel
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      - https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
      - https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Authentik
      - Casdoor
      - Keycloak
      - Logto
      - Ory Kratos
      - Zitadel
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      - https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
      - https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Authentik
      - Casdoor
      - Keycloak
      - Logto
      - Ory Kratos
      - Zitadel
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      - https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
      - https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - Authentik
      - Casdoor
      - Keycloak
      - Logto
      - Ory Kratos
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: X (Twitter)
      slug: x
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      - https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
      - https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: observed
      url: /providers/x/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Authentik
      - Casdoor
      - Keycloak
      - Logto
      - Ory Kratos
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      - https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
      - https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Casdoor
      - Keycloak
      - Logto
      - Ory Kratos
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp:
        status: none
      name: LinkedIn
      slug: linkedin
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      - https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: observed
      url: /providers/linkedin/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Authentik
      - Logto
      - Ory Kratos
      - Zitadel
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Sign in with Apple
      slug: apple
      sources:
      - https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      - https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Authentik
      - Logto
      - Ory Kratos
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      - https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Authentik
      - Logto
      - Ory Kratos
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      - https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
    - agent_band: agent-aware
      agent_readiness: 23.6
      apps:
      - Authentik
      - Casdoor
      - Logto
      band: developing
      in_catalog: true
      kin_score: 45.1
      mcp:
        status: none
      name: WeChat
      slug: wechat
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      - https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - Messaging
      - Mini Programs
      - Payments
      - Social
      tier: observed
      url: /providers/wechat/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Authentik
      - Logto
      - Ory Kratos
      band: thin
      in_catalog: true
      kin_score: 33.1
      mcp:
        status: none
      name: Patreon
      slug: patreon
      sources:
      - https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      - https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
      status: profiled
      tags:
      - Content
      - Creator Economy
      - Membership
      - Subscription
      tier: observed
      url: /providers/patreon/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Casdoor
      - Logto
      - Ory Kratos
      band: minimal
      in_catalog: true
      kin_score: 8.5
      mcp:
        source: https://github.com/larksuite/lark-openapi-mcp
        status: verified
      name: Lark / Feishu
      slug: larksuite
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      - https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
      status: profiled
      tags:
      - Global Collaboration
      - No-code Workflow
      - Productivity
      - Team Collaboration
      tier: observed
      url: /providers/larksuite/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Casdoor
      - Logto
      - Ory Kratos
      band: minimal
      in_catalog: true
      kin_score: 7.1
      mcp:
        source: https://github.com/open-dingtalk/dingtalk-mcp
        status: verified
      name: DingTalk
      slug: dingtalk
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      - https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
      status: profiled
      tags:
      - Collaboration
      - Communications
      - Company
      - Enterprise
      tier: observed
      url: /providers/dingtalk/
    - agent_band: agent-native
      agent_readiness: 47.0
      apps:
      - Logto
      - Ory Kratos
      band: exemplar
      in_catalog: true
      kin_score: 71.3
      mcp:
        source: https://github.com/line/line-bot-mcp-server
        status: verified
      name: LINE
      slug: line
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      - https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
      status: profiled
      tags:
      - Chatbots
      - Messaging
      - Mini Apps
      - Social Login
      tier: observed
      url: /providers/line/
    - agent_band: agent-native
      agent_readiness: 53.6
      apps:
      - Logto
      - Ory Kratos
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Login with Amazon
      slug: amazon
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      - https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: observed
      url: /providers/amazon/
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - Casdoor
      - Logto
      band: emerging
      in_catalog: true
      kin_score: 24.8
      mcp:
        source: https://github.com/alipay/global-alipayplus-mcp
        status: verified
      name: Alipay
      slug: ant-group
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - Company
      - Fintech
      - Payments
      - Technology
      tier: observed
      url: /providers/ant-group/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Casdoor
      - Logto
      band: minimal
      in_catalog: true
      kin_score: 8.6
      mcp:
        status: unknown
      name: QQ
      slug: tencent-qq
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/tencent-qq/
    - agent_band: null
      agent_readiness: null
      apps:
      - Casdoor
      - Logto
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: WeCom
      slug: wecom
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Logto
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: WhatsApp
      slug: whatsapp
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: observed
      url: /providers/whatsapp/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Keycloak
      band: exemplar
      in_catalog: true
      kin_score: 71.9
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Bitbucket
      slug: bitbucket
      sources:
      - https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
      status: profiled
      tags:
      - Atlassian
      - CI/CD
      - Code Collaboration
      - Code Review
      tier: observed
      url: /providers/bitbucket/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Keycloak
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp: &id001
        status: none
      name: Microsoft
      slug: microsoft-entra
      sources:
      - https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
      status: profiled
      tags: &id002
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Logto
      band: exemplar
      in_catalog: true
      kin_score: 69.1
      mcp:
        source: https://github.com/huggingface/hf-mcp-server
        status: verified
      name: Hugging Face
      slug: hugging-face
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - Computer Vision
      - Embeddings
      - Image Generation
      - LLM
      tier: observed
      url: /providers/hugging-face/
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
      - Keycloak
      band: exemplar
      in_catalog: true
      kin_score: 67.8
      mcp:
        status: none
      name: Instagram
      slug: instagram
      sources:
      - https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
      status: profiled
      tags:
      - Instagram
      - Meta
      - Photos
      - Social Media
      tier: observed
      url: /providers/instagram/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Authentik
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/reddit/devvit-mcp
        status: verified
      name: Reddit
      slug: reddit
      sources:
      - https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
      status: profiled
      tags:
      - Advertising
      - Community
      - Content
      - Reddit
      tier: observed
      url: /providers/reddit/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Casdoor
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Keycloak
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Keycloak
      band: developing
      in_catalog: true
      kin_score: 53.9
      mcp:
        source: https://github.com/openshift/kubernetes-mcp-server
        status: verified
      name: Red Hat OpenShift
      slug: red-hat-openshift
      sources:
      - https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
      status: profiled
      tags:
      - Containers
      - Enterprise
      - Hybrid Cloud
      - Kubernetes
      tier: observed
      url: /providers/red-hat-openshift/
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - Ory Kratos
      band: developing
      in_catalog: true
      kin_score: 50.6
      mcp:
        status: none
      name: Spotify
      slug: spotify
      sources:
      - https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
      status: profiled
      tags:
      - Audio
      - Music
      - Podcasts
      - Streaming
      tier: observed
      url: /providers/spotify/
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Authentik
      band: developing
      in_catalog: true
      kin_score: 48.2
      mcp:
        status: none
      name: Twitch
      slug: twitch
      sources:
      - https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
      status: profiled
      tags:
      - Entertainment
      - Gaming
      - Live Streaming
      - Streaming
      tier: observed
      url: /providers/twitch/
    - agent_band: agent-ready
      agent_readiness: 33.3
      apps:
      - Keycloak
      band: thin
      in_catalog: true
      kin_score: 36.6
      mcp:
        source: https://github.com/StackExchange/Stack-MCP
        status: verified
      name: Stack Overflow
      slug: stack-overflow
      sources:
      - https://github.com/keycloak/keycloak/tree/main/services/src/main/java/org/keycloak/social
      status: profiled
      tags:
      - Answers
      - Code
      - Developer Community
      - Developer Tools
      tier: observed
      url: /providers/stack-overflow/
    - agent_band: agent-aware
      agent_readiness: 24.9
      apps:
      - Logto
      band: thin
      in_catalog: true
      kin_score: 35.6
      mcp:
        status: none
      name: Xiaomi
      slug: xiaomi
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - Consumer Electronics
      - IoT
      - Mobile
      - Smart Home
      tier: observed
      url: /providers/xiaomi/
    - agent_band: agent-aware
      agent_readiness: 22.8
      apps:
      - Logto
      band: thin
      in_catalog: true
      kin_score: 33.7
      mcp:
        status: none
      name: KOOK
      slug: kook
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - Community
      - Company
      - Gaming
      - Voice Communication
      tier: observed
      url: /providers/kook/
    - agent_band: agent-aware
      agent_readiness: 27.9
      apps:
      - Casdoor
      band: thin
      in_catalog: true
      kin_score: 31.7
      mcp:
        status: none
      name: Kwai
      slug: kuaishou
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      status: profiled
      tags:
      - Company
      - Consumer
      - Social
      - Video
      tier: observed
      url: /providers/kuaishou/
    - agent_band: agent-ready
      agent_readiness: 33.9
      apps:
      - Casdoor
      band: thin
      in_catalog: true
      kin_score: 26.9
      mcp:
        source: https://github.com/oschina/mcp-gitee
        status: verified
      name: Gitee
      slug: gitee
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      status: profiled
      tags:
      - Code Hosting
      - Git Hosting
      - Repositories
      - Version Control
      tier: observed
      url: /providers/gitee/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Logto
      band: thin
      in_catalog: true
      kin_score: 26.2
      mcp:
        status: none
      name: Kakao
      slug: kakao
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - Maps
      - Messaging
      - Navigation
      - Payments
      tier: observed
      url: /providers/kakao/
    - agent_band: agent-aware
      agent_readiness: 22.1
      apps:
      - Ory Kratos
      band: emerging
      in_catalog: true
      kin_score: 21.4
      mcp:
        status: none
      name: UAE PASS
      slug: uae-pass
      sources:
      - https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
      status: profiled
      tags:
      - Authentication
      - Company
      - Identity
      - United Arab Emirates
      tier: observed
      url: /providers/uae-pass/
    - agent_band: agent-aware
      agent_readiness: 5.8
      apps:
      - Casdoor
      band: emerging
      in_catalog: true
      kin_score: 17.4
      mcp:
        source: https://github.com/baidu-maps/mcp
        status: verified
      name: Baidu
      slug: baidu
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Machine Learning
      - Technology
      tier: observed
      url: /providers/baidu/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Logto
      band: minimal
      in_catalog: true
      kin_score: 10.6
      mcp:
        status: none
      name: Naver
      slug: naver
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - Cloud Platform
      - Maps
      - Search
      - Translation
      tier: observed
      url: /providers/naver/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Ory Kratos
      band: minimal
      in_catalog: true
      kin_score: 9.2
      mcp:
        status: unknown
      name: netID
      slug: netid
      sources:
      - https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
      status: profiled
      tags:
      - Authentication
      - Company
      - Identity
      - Login
      tier: observed
      url: /providers/netid/
    - agent_band: human-only
      agent_readiness: 1.1
      apps:
      - Casdoor
      band: minimal
      in_catalog: true
      kin_score: 8.0
      mcp:
        status: none
      name: Weibo
      slug: weibo
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      status: profiled
      tags:
      - China
      - Company
      - Microblogging
      - Social Media
      tier: observed
      url: /providers/weibo/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Ory Kratos
      band: minimal
      in_catalog: true
      kin_score: 4.8
      mcp:
        status: none
      name: VK
      slug: vk
      sources:
      - https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
      status: profiled
      tags:
      - Public APIs
      - Social
      tier: observed
      url: /providers/vk/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Casdoor
      band: minimal
      in_catalog: true
      kin_score: 3.7
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=bytedance
        status: verified
      name: Douyin
      slug: bytedance
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      status: profiled
      tags:
      - Company
      - Consumer Internet
      - Social Media
      - Video
      tier: observed
      url: /providers/bytedance/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Casdoor
      band: minimal
      in_catalog: true
      kin_score: 3.3
      mcp:
        status: none
      name: Bilibili
      slug: bilibili
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      status: profiled
      tags:
      - Company
      - Media Entertainment
      - Streaming
      - Video
      tier: observed
      url: /providers/bilibili/
    - agent_band: null
      agent_readiness: null
      apps:
      - Ory Kratos
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Yandex ID
      slug: yandex
      sources:
      - https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Authentik
      - Casdoor
      - Logto
      - Ory Kratos
      - Zitadel
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp: *id001
      name: Microsoft Entra ID
      slug: microsoft-entra
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      - https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Authentik
      - Casdoor
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://github.com/casdoor/casdoor/tree/master/idp
      - https://github.com/goauthentik/authentik/tree/main/authentik/sources/oauth/types
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: observed
      url: /providers/okta/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Ory Kratos
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: observed
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 39.5
      apps:
      - Ory Kratos
      band: exemplar
      in_catalog: true
      kin_score: 71.8
      mcp:
        source: https://auth0.com/docs/get-started/auth0-mcp-server
        status: verified
      name: Auth0
      slug: auth0
      sources:
      - https://github.com/ory/kratos/tree/master/selfservice/strategy/oidc
      status: profiled
      tags:
      - AI Agents
      - Auth0
      - Authentication
      - Authorization
      tier: observed
      url: /providers/auth0/
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
      - Authentik
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/gemini-cli-extensions/workspace
        status: verified
      name: Google Workspace
      slug: google-workspace
      sources:
      - https://github.com/goauthentik/authentik/tree/main/authentik/enterprise/providers
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: observed
      url: /providers/google-workspace/
    - agent_band: agent-ready
      agent_readiness: 39.0
      apps:
      - Authentik
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Graph
      slug: microsoft-graph
      sources:
      - https://raw.githubusercontent.com/goauthentik/authentik/main/pyproject.toml
      status: profiled
      tags:
      - Azure AD
      - Collaboration
      - Contacts
      - Microsoft Graph
      tier: observed
      url: /providers/microsoft-graph/
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
      - Authelia
      - Authentik
      band: thin
      in_catalog: true
      kin_score: 34.7
      mcp:
        status: none
      name: Duo Security
      slug: duo-security
      sources:
      - https://raw.githubusercontent.com/authelia/authelia/master/go.mod
      - https://raw.githubusercontent.com/goauthentik/authentik/main/pyproject.toml
      status: profiled
      tags:
      - Authentication
      - Identity
      - MFA
      - Zero Trust
      tier: observed
      url: /providers/duo-security/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30
      key: AE-160.30
      name: Identity Verification
      url: /capabilities/identity-verification/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 3.4
      apps:
      - Casdoor
      band: emerging
      in_catalog: true
      kin_score: 17.9
      mcp: &id003
        source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
        status: verified
      name: Alibaba Cloud
      slug: alibaba
      sources:
      - https://raw.githubusercontent.com/casdoor/casdoor/master/go.mod
      status: profiled
      tags: &id004
      - Cloud
      - Cloud Computing
      - Commerce
      - E-Commerce
      tier: observed
      url: /providers/alibaba/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.30
      key: AE-150.20.30
      name: One-Time Passcodes
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - Authentik
      - Casdoor
      - Logto
      - Zitadel
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      - https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
      - https://raw.githubusercontent.com/goauthentik/authentik/main/authentik/stages/authenticator_sms/models.py
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Casdoor
      - Logto
      band: thin
      in_catalog: true
      kin_score: 30.5
      mcp:
        source: https://github.com/TencentCloud/cos-mcp
        status: verified
      name: Tencent Cloud SMS
      slug: tencentcloud
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      - https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
      status: profiled
      tags:
      - Artificial Intelligence
      - Cloud
      - Computing
      - Infrastructure
      tier: observed
      url: /providers/tencentcloud/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Casdoor
      - Logto
      band: minimal
      in_catalog: true
      kin_score: 5.9
      mcp:
        status: unknown
      name: SmsBao
      slug: smsbao
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      - https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
      status: profiled
      tags:
      - China
      - Enterprise
      - Messaging
      - SMS
      tier: observed
      url: /providers/smsbao/
    - agent_band: agent-ready
      agent_readiness: 40.0
      apps:
      - Logto
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/Vonage/vonage-mcp-server-documentation
        status: verified
      name: Vonage
      slug: vonage
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - Communications
      - Messaging
      - Telecommunications
      - Video Conferencing
      tier: observed
      url: /providers/vonage/
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - Logto
      band: thin
      in_catalog: true
      kin_score: 31.8
      mcp:
        status: unknown
      name: GatewayAPI
      slug: gatewayapi
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - Communications
      - Company
      - Messaging
      - SMS
      tier: observed
      url: /providers/gatewayapi/
    - agent_band: human-only
      agent_readiness: 3.4
      apps:
      - Logto
      band: emerging
      in_catalog: true
      kin_score: 17.9
      mcp: *id003
      name: Alibaba Cloud SMS
      slug: alibaba
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/alibaba/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Logto
      band: minimal
      in_catalog: true
      kin_score: 10.5
      mcp:
        status: none
      name: Yunpian
      slug: yunpian
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - API Platform
      - Cloud Communications
      - Company
      - SMS
      tier: observed
      url: /providers/yunpian/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Logto
      band: minimal
      in_catalog: true
      kin_score: 2.7
      mcp:
        status: unknown
      name: SMS Aero
      slug: smsaero
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - Bulk
      - Company
      - Messaging
      - SMS
      tier: observed
      url: /providers/smsaero/
    - agent_band: agent-ready
      agent_readiness: 61.3
      apps:
      - Casdoor
      band: exemplar
      in_catalog: true
      kin_score: 86.9
      mcp:
        source: https://www.infobip.com/docs/mcp
        status: verified
      name: Infobip
      slug: infobip
      sources:
      - https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
      status: profiled
      tags:
      - CPaaS
      - Croatia
      - Messaging
      - Telecommunications
      tier: declared
      url: /providers/infobip/
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Casdoor
      band: exemplar
      in_catalog: true
      kin_score: 73.7
      mcp:
        status: none
      name: Azure Communication Services
      slug: microsoft-azure-communication-services
      sources:
      - https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
      status: profiled
      tags:
      - CPaaS
      - Calling
      - Chat
      - Microsoft Azure
      tier: declared
      url: /providers/microsoft-azure-communication-services/
    - agent_band: agent-ready
      agent_readiness: 41.7
      apps:
      - Casdoor
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SNS
      slug: amazon-sns
      sources:
      - https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Messaging
      - Notification
      tier: declared
      url: /providers/amazon-sns/
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Casdoor
      band: thin
      in_catalog: true
      kin_score: 38.1
      mcp:
        source: https://github.com/ucloud/udb-mysql-mcp-server
        status: verified
      name: UCloud USMS
      slug: ucloud
      sources:
      - https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
      status: profiled
      tags:
      - Cloud Computing
      - Company
      - Enterprise
      - Infrastructure-as-a-Service
      tier: declared
      url: /providers/ucloud/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Casdoor
      band: emerging
      in_catalog: true
      kin_score: 15.7
      mcp:
        source: https://github.com/huaweicloud/huaweicloud-mcp
        status: verified
      name: Huawei Cloud SMS
      slug: huaweicloud
      sources:
      - https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
      status: profiled
      tags:
      - Cloud
      - Company
      - Infrastructure-as-a-Service
      - Platform-as-a-Service
      tier: declared
      url: /providers/huaweicloud/
    - agent_band: human-only
      agent_readiness: 0.7
      apps:
      - Casdoor
      band: minimal
      in_catalog: true
      kin_score: 9.0
      mcp:
        status: none
      name: Netgsm
      slug: netgsm
      sources:
      - https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
      status: profiled
      tags:
      - Internet
      - OTP
      - SMS
      - VoIP
      tier: declared
      url: /providers/netgsm/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Casdoor
      band: minimal
      in_catalog: true
      kin_score: 8.9
      mcp:
        status: unknown
      name: Oson SMS
      slug: osonsms
      sources:
      - https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
      status: profiled
      tags:
      - Cloud
      - Company
      - Messaging
      - SMS
      tier: declared
      url: /providers/osonsms/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Casdoor
      band: minimal
      in_catalog: true
      kin_score: 5.0
      mcp:
        status: unknown
      name: GCCPAY
      slug: gccpay
      sources:
      - https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
      status: profiled
      tags:
      - Company
      - E-Commerce
      - Fintech
      - Payments
      tier: declared
      url: /providers/gccpay/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Casdoor
      band: minimal
      in_catalog: true
      kin_score: 4.0
      mcp:
        status: unknown
      name: SUBMAIL
      slug: submail
      sources:
      - https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/submail/
    - agent_band: null
      agent_readiness: null
      apps:
      - Casdoor
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Huyi
      slug: huyi
      sources:
      - https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Casdoor
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: VolcEngine SMS
      slug: volcengine
      sources:
      - https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
      status: queued for profiling
      tags: []
      tier: declared
      url: null
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
      - Casdoor
      - Logto
      band: exemplar
      in_catalog: true
      kin_score: 84.0
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      - https://raw.githubusercontent.com/casdoor/casdoor/master/go.mod
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - Logto
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        status: none
      name: Amazon SES
      slug: amazon-ses
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Logto
      band: exemplar
      in_catalog: true
      kin_score: 71.1
      mcp:
        status: none
      name: SMTP2GO
      slug: smtp2go
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - Email
      - Email Delivery
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/smtp2go/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Logto
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/ActiveCampaign/postmark-mcp
        status: verified
      name: Postmark
      slug: postmark
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - Deliverability
      - Email
      - Messaging
      - Transactional Email
      tier: observed
      url: /providers/postmark/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Logto
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags:
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailgun/
    - agent_band: human-only
      agent_readiness: 3.4
      apps:
      - Logto
      band: emerging
      in_catalog: true
      kin_score: 17.9
      mcp: *id003
      name: Alibaba Cloud DirectMail
      slug: alibaba
      sources:
      - https://github.com/logto-io/logto/tree/master/packages/connectors
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/alibaba/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Authentik
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/goauthentik/authentik/main/pyproject.toml
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Zitadel
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp:
        status: none
      name: Google Cloud Profiler
      slug: google-cloud-profiler
      sources:
      - https://raw.githubusercontent.com/zitadel/zitadel/main/go.mod
      status: profiled
      tags:
      - CPU
      - Flame Graphs
      - Google Cloud
      - Memory
      tier: observed
      url: /providers/google-cloud-profiler/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Okta Verify
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id005
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase (Crashlytics)
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.okta.android.auth/latest/
      status: profiled
      tags: &id006
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
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
      - Okta Verify
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id005
      name: Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.okta.android.auth/latest/
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - Okta Verify
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.okta.android.auth/latest/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
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
      - Casdoor
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/casdoor/casdoor/master/go.mod
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Zitadel
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://raw.githubusercontent.com/zitadel/zitadel/main/go.mod
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
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
      - Authentik
      band: thin
      in_catalog: true
      kin_score: 31.5
      mcp:
        status: none
      name: MaxMind GeoIP2
      slug: maxmind
      sources:
      - https://raw.githubusercontent.com/goauthentik/authentik/main/pyproject.toml
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
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - Casdoor
      band: exemplar
      in_catalog: true
      kin_score: 68.9
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google
      slug: google
      sources:
      - https://raw.githubusercontent.com/casdoor/casdoor/master/go.mod
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: observed
      url: /providers/google/
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
      - Casdoor
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/casdoor/casdoor/master/go.mod
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
  layer: common
summary:
  coverage_pct: 95.2
  declared_only: 11
  distinct_providers: 83
  in_catalog: 79
  mcp:
    documented: 0
    none: 31
    unchecked: 4
    verified: 40
  mcp_verified: 40
  mean_kin_score: 47.2
  observed: 72
  queued: 4
  reference_apps: 8
title: 'Identity, SSO & Access Management: application blueprint'
---
