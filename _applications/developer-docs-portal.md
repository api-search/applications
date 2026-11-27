---
access: understanding
agent_layer: []
apps:
- anchor: docusaurus
  counts:
    declared: 3
    observed: 4
  evidence:
  - route: documentation
    url: https://github.com/facebook/docusaurus/tree/main/website/docs/deployment
  - route: source code
    url: https://github.com/facebook/docusaurus/tree/main/packages
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Algolia DocSearch
    provider: algolia
    says: ships the Algolia DocSearch SDK or integration code
    source: https://github.com/facebook/docusaurus/tree/main/packages
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
    name: Google Analytics (gtag)
    provider: google-analytics
    says: ships the Google Analytics (gtag) SDK or integration code
    source: https://github.com/facebook/docusaurus/tree/main/packages
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: null
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: ships the Google Tag Manager SDK or integration code
    source: https://github.com/facebook/docusaurus/tree/main/packages
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
    name: Vercel Analytics
    provider: vercel
    says: ships the Vercel Analytics SDK or integration code
    source: https://github.com/facebook/docusaurus/tree/main/packages
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-926
      key: AE-926
      name: Web Hosting & Control Panels
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: GitHub Pages
    provider: github
    says: lists GitHub Pages as an integration
    source: https://github.com/facebook/docusaurus/tree/main/website/docs/deployment/github-pages.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-926
      key: AE-926
      name: Web Hosting & Control Panels
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Netlify
    provider: netlify
    says: lists Netlify as an integration
    source: https://github.com/facebook/docusaurus/tree/main/website/docs/deployment/netlify.mdx
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-926
      key: AE-926
      name: Web Hosting & Control Panels
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Vercel
    provider: vercel
    says: lists Vercel as an integration
    source: https://github.com/facebook/docusaurus/tree/main/website/docs/deployment/vercel.mdx
    tier: declared
  kind: self-hosted
  name: Docusaurus
  page: /applications/developer-docs-portal/docusaurus/
  slug: docusaurus
  url: https://github.com/facebook/docusaurus
- anchor: zudoku
  counts:
    declared: 0
    observed: 10
  evidence:
  - route: dependency manifest
    url: https://github.com/zuplo/zudoku/blob/main/packages/zudoku/package.json
  - route: source code
    url: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
  - route: source code
    url: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/plugins
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10
      key: AE-160.10
      name: Customer Sign-In
      url: /capabilities/customer-sign-in/
      via_parent: null
    credit: null
    layer: domain
    name: Auth0
    provider: auth0
    says: ships the Auth0 SDK or integration code
    source: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10
      key: AE-160.10
      name: Customer Sign-In
      url: /capabilities/customer-sign-in/
      via_parent: null
    credit: null
    layer: domain
    name: Azure AD B2C
    provider: microsoft-entra
    says: ships the Azure AD B2C SDK or integration code
    source: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10
      key: AE-160.10
      name: Customer Sign-In
      url: /capabilities/customer-sign-in/
      via_parent: null
    credit: null
    layer: domain
    name: Clerk
    provider: clerk-com
    says: ships the Clerk SDK or integration code
    source: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10
      key: AE-160.10
      name: Customer Sign-In
      url: /capabilities/customer-sign-in/
      via_parent: null
    credit: null
    layer: domain
    name: Firebase Auth
    provider: firebase
    says: ships the Firebase Auth SDK or integration code
    source: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Inkeep
    provider: inkeep
    says: ships the Inkeep SDK or integration code
    source: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/plugins
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
    source: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
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
    name: PostHog
    provider: posthog
    says: ships the PostHog SDK or integration code
    source: https://github.com/zuplo/zudoku/blob/main/packages/zudoku/package.json
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
    source: https://github.com/zuplo/zudoku/blob/main/packages/zudoku/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10
      key: AE-160.10
      name: Customer Sign-In
      url: /capabilities/customer-sign-in/
      via_parent: null
    credit: null
    layer: domain
    name: Supabase Auth
    provider: supabase
    says: ships the Supabase Auth SDK or integration code
    source: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-909
      key: AE-909
      name: API Gateways
      url: /capabilities/api-consumption-governance/
      via_parent: API Consumption Governance
    credit: null
    layer: domain
    name: Zuplo
    provider: zuplo
    says: ships the Zuplo SDK or integration code
    source: https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/plugins
    tier: observed
  kind: self-hosted
  name: Zudoku
  page: /applications/developer-docs-portal/zudoku/
  slug: zudoku
  url: https://github.com/zuplo/zudoku
- anchor: backstage
  counts:
    declared: 0
    observed: 37
  evidence:
  - route: source code
    url: https://github.com/backstage/backstage/tree/master/plugins
  - route: source code
    url: https://github.com/backstage/backstage/tree/master/plugins/techdocs-node/src/stages/publish
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
    source: https://github.com/backstage/backstage/tree/master/plugins/techdocs-node/src/stages/publish
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
    name: Amazon SQS
    provider: amazon-sqs
    says: ships the Amazon SQS SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
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
    name: Apache Kafka
    provider: apache-kafka
    says: ships the Apache Kafka SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Atlassian
    provider: atlassian
    says: ships the Atlassian SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Auth0
    provider: auth0
    says: ships the Auth0 SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
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
    name: AWS
    provider: amazon-web-services
    says: ships the AWS SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: AWS ALB
    provider: amazon-web-services
    says: ships the AWS ALB SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
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
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: ships the Azure Blob Storage SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins/techdocs-node/src/stages/publish
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Azure DevOps
    provider: microsoft-azure-devops
    says: ships the Azure DevOps SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Azure Easy Auth
    provider: microsoft-azure
    says: ships the Azure Easy Auth SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
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
    name: Bitbucket
    provider: bitbucket
    says: ships the Bitbucket SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bitbucket
    provider: bitbucket
    says: ships the Bitbucket SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Cloudflare Access
    provider: cloudflare
    says: ships the Cloudflare Access SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
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
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Elastic
    provider: elastic
    says: ships the Elastic SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gerrit
    provider: gerrit
    says: ships the Gerrit SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gitea
    provider: gitea
    says: ships the Gitea SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
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
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
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
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
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
    name: Google Cloud
    provider: google-cloud-platform
    says: ships the Google Cloud SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Google Cloud IAP
    provider: google-cloud-platform
    says: ships the Google Cloud IAP SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
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
    name: Google Cloud Pub/Sub
    provider: google-cloud-pubsub
    says: ships the Google Cloud Pub/Sub SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
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
    source: https://github.com/backstage/backstage/tree/master/plugins/techdocs-node/src/stages/publish
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
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft
    provider: microsoft-entra
    says: ships the Microsoft SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
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
    name: Microsoft Graph
    provider: microsoft-graph
    says: ships the Microsoft Graph SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Okta
    provider: okta
    says: ships the Okta SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: OneLogin
    provider: onelogin
    says: ships the OneLogin SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
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
    name: OpenShift
    provider: red-hat-openshift
    says: ships the OpenShift SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
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
    name: OpenStack Swift
    provider: openstack
    says: ships the OpenStack Swift SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins/techdocs-node/src/stages/publish
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
    name: PuppetDB
    provider: puppet
    says: ships the PuppetDB SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
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
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
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
    says: ships the Slack SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Stack Overflow
    provider: stack-overflow
    says: ships the Stack Overflow SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: VMware Cloud
    provider: vmware
    says: ships the VMware Cloud SDK or integration code
    source: https://github.com/backstage/backstage/tree/master/plugins
    tier: observed
  kind: self-hosted
  name: Backstage
  page: /applications/developer-docs-portal/backstage/
  slug: backstage
  url: https://github.com/backstage/backstage
- anchor: gitbook
  counts:
    declared: 0
    observed: 56
  evidence:
  - route: source code
    url: https://github.com/GitbookIO/integrations/tree/main/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Ahrefs
    provider: ahrefs
    says: ships the Ahrefs SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10
      key: AE-160.10
      name: Customer Sign-In
      url: /capabilities/customer-sign-in/
      via_parent: null
    credit: null
    layer: common
    name: Amazon Cognito
    provider: amazon-cognito
    says: ships the Amazon Cognito SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
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
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.30
      key: AE-170.70.30
      name: Interactive Product Demos
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: common
    name: Arcade
    provider: arcade-software
    says: ships the Arcade SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10
      key: AE-160.10
      name: Customer Sign-In
      url: /capabilities/customer-sign-in/
      via_parent: null
    credit: null
    layer: common
    name: Auth0 (visitor auth)
    provider: auth0
    says: ships the Auth0 (visitor auth) SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Azure AD (visitor auth)
    provider: microsoft-entra
    says: ships the Azure AD (visitor auth) SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    credit: null
    layer: common
    name: Bucket (Reflag)
    provider: bucket
    says: ships the Bucket (Reflag) SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.50
      key: AE-160.50
      name: Consent & Preferences
      url: /capabilities/consent-preferences/
      via_parent: null
    credit: null
    layer: common
    name: Cookiebot
    provider: usercentrics
    says: ships the Cookiebot SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.50
      key: AE-160.50
      name: Consent & Preferences
      url: /capabilities/consent-preferences/
      via_parent: null
    credit: null
    layer: common
    name: CookieScript
    provider: cookie-script
    says: ships the CookieScript SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Crisp
    provider: crisp
    says: ships the Crisp SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
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
    name: DevTune
    provider: devtune
    says: ships the DevTune SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
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
    name: Fathom Analytics
    provider: fathom
    says: ships the Fathom Analytics SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: common
    name: Figma
    provider: figma
    says: ships the Figma SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: common
    name: Formspree
    provider: formspree
    says: ships the Formspree SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Freshdesk
    provider: freshdesk
    says: ships the Freshdesk SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Front
    provider: front
    says: ships the Front SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
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
    name: FullStory
    provider: fullstory
    says: ships the FullStory SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-905
      key: AE-905
      name: IDEs & AI Coding Assistants
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    credit: null
    layer: common
    name: GitHub Copilot
    provider: github-copilot
    says: ships the GitHub Copilot SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub Sync
    provider: github
    says: ships the GitHub Sync SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitLab Sync
    provider: gitlab
    says: ships the GitLab Sync SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
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
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.50
      key: AE-160.50
      name: Consent & Preferences
      url: /capabilities/consent-preferences/
      via_parent: null
    credit: null
    layer: common
    name: Gravito
    provider: gravito
    says: ships the Gravito SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
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
    name: Heap
    provider: heap
    says: ships the Heap SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Help Scout
    provider: helpscout
    says: ships the Help Scout SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
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
    name: Hotjar
    provider: hotjar
    says: ships the Hotjar SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
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
    says: ships the HubSpot SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
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
    says: ships the Intercom SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
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
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.40
      key: AE-230.30.40
      name: Website Visitor Identification & Buyer Intent
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: common
    name: Koala
    provider: koala-io
    says: ships the Koala SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    credit: null
    layer: common
    name: LaunchDarkly
    provider: launchdarkly
    says: ships the LaunchDarkly SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
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
    name: Linear
    provider: linear-app
    says: ships the Linear SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: common
    name: Lucid
    provider: lucid
    says: ships the Lucid SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailchimp
    provider: mailchimp
    says: ships the Mailchimp SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.50
      key: marketing-operations-management
      name: Marketing Operations Management
      url: /capabilities/marketing-operations-management/
      via_parent: null
    credit: null
    layer: common
    name: Marketo
    provider: marketo
    says: ships the Marketo SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
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
    name: Mixpanel
    provider: mixpanel
    says: ships the Mixpanel SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.30
      key: AE-170.70.30
      name: Interactive Product Demos
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: common
    name: Navattic
    provider: navattic
    says: ships the Navattic SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Okta (visitor auth)
    provider: okta
    says: ships the Okta (visitor auth) SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.50
      key: AE-160.50
      name: Consent & Preferences
      url: /capabilities/consent-preferences/
      via_parent: null
    credit: null
    layer: common
    name: OneTrust
    provider: onetrust
    says: ships the OneTrust SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.50
      key: AE-160.50
      name: Consent & Preferences
      url: /capabilities/consent-preferences/
      via_parent: null
    credit: null
    layer: common
    name: Osano
    provider: osano
    says: ships the Osano SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
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
    name: Pendo
    provider: pendoio
    says: ships the Pendo SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
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
    name: Piwik PRO
    provider: piwik-pro
    says: ships the Piwik PRO SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
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
    name: Plausible
    provider: plausible
    says: ships the Plausible SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
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
    name: PostHog
    provider: posthog
    says: ships the PostHog SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.40
      key: AE-230.30.40
      name: Website Visitor Identification & Buyer Intent
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: common
    name: Reo.Dev
    provider: reo-dev
    says: ships the Reo.Dev SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-906
      key: AE-906
      name: Code Execution Sandboxes
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    credit: null
    layer: common
    name: RunKit
    provider: runkit
    says: ships the RunKit SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: common
    name: RunLLM
    provider: runllm
    says: ships the RunLLM SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Salesforce chat
    provider: salesforce
    says: ships the Salesforce chat SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.40
      key: AE-230.30.40
      name: Website Visitor Identification & Buyer Intent
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: common
    name: SalesViewer
    provider: salesviewer
    says: ships the SalesViewer SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
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
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
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
    says: ships the Slack SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: Toucan Toco
    provider: toucantoco
    says: ships the Toucan Toco SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.40
      key: AE-230.30.40
      name: Website Visitor Identification & Buyer Intent
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: common
    name: Unify
    provider: unify
    says: ships the Unify SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: common
    name: Wistia
    provider: wistia
    says: ships the Wistia SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.20
      key: AE-230.30.20
      name: Lead Data
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: common
    name: ZoomInfo
    provider: zoominfo
    says: ships the ZoomInfo SDK or integration code
    source: https://github.com/GitbookIO/integrations/tree/main/integrations
    tier: observed
  kind: commercial
  name: GitBook
  page: /applications/developer-docs-portal/gitbook/
  slug: gitbook
  url: https://www.gitbook.com/
- anchor: mintlify
  counts:
    declared: 49
    observed: 0
  evidence:
  - route: documentation
    url: https://www.mintlify.com/docs/llms.txt
  - route: integrations page
    url: https://www.mintlify.com/docs/automations/integrations.md
  - route: integrations page
    url: https://www.mintlify.com/docs/integrations/analytics/overview.md
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Adobe Analytics
    provider: adobe-analytics
    says: lists Adobe Analytics as an integration
    source: https://www.mintlify.com/docs/integrations/analytics/adobe.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3740.30
      key: content-delivery-network-operations
      name: Content Delivery Network Operations
      url: /capabilities/content-delivery-network-operations/
      via_parent: null
    credit: null
    layer: common
    name: Amazon CloudFront
    provider: cloudfront
    says: lists Amazon CloudFront as an integration
    source: https://www.mintlify.com/docs/deploy/route53-cloudfront.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon Route 53
    provider: amazon-route-53
    says: lists Amazon Route 53 as an integration
    source: https://www.mintlify.com/docs/deploy/route53-cloudfront.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Amplitude
    provider: amplitude
    says: lists Amplitude as an integration
    source: https://www.mintlify.com/docs/integrations/analytics/amplitude.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Azure Repos
    provider: microsoft-azure-devops
    says: lists Azure Repos as an integration
    source: https://www.mintlify.com/docs/deploy/azure-repos.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bitbucket
    provider: bitbucket
    says: lists Bitbucket as an integration
    source: https://www.mintlify.com/docs/deploy/bitbucket.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: common
    name: Clearbit
    provider: clearbit
    says: lists Clearbit as an integration
    source: https://www.mintlify.com/docs/integrations/analytics/clearbit.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3740.30
      key: content-delivery-network-operations
      name: Content Delivery Network Operations
      url: /capabilities/content-delivery-network-operations/
      via_parent: null
    credit: null
    layer: common
    name: Cloudflare
    provider: cloudflare
    says: lists Cloudflare as an integration
    source: https://www.mintlify.com/docs/deploy/cloudflare.md
    tier: declared
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
    says: lists Confluence as an integration
    source: https://www.mintlify.com/docs/automations/integrations.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: content-management
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: common
    name: Contentful
    provider: contentful
    says: lists Contentful as an integration
    source: https://www.mintlify.com/docs/automations/integrations.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Excel
    provider: microsoft-excel
    says: lists Excel as an integration
    source: https://www.mintlify.com/docs/automations/integrations.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Fathom
    provider: fathom
    says: lists Fathom as an integration
    source: https://www.mintlify.com/docs/integrations/analytics/fathom.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: common
    name: Figma
    provider: figma
    says: lists Figma as an integration
    source: https://www.mintlify.com/docs/automations/integrations.md
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
    name: Front
    provider: front
    says: lists Front as an integration
    source: https://www.mintlify.com/docs/integrations/support/front.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://www.mintlify.com/docs/deploy/github.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: lists GitLab as an integration
    source: https://www.mintlify.com/docs/deploy/gitlab.md
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
    source: https://www.mintlify.com/docs/automations/integrations.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Google Analytics
    provider: google-analytics
    says: lists Google Analytics as an integration
    source: https://www.mintlify.com/docs/integrations/analytics/google-analytics.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Docs
    provider: google-docs
    says: lists Google Docs as an integration
    source: https://www.mintlify.com/docs/automations/integrations.md
    tier: declared
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
    says: lists Google Drive as an integration
    source: https://www.mintlify.com/docs/automations/integrations.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: null
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: lists Google Tag Manager as an integration
    source: https://www.mintlify.com/docs/integrations/analytics/google-tag-manager.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Heap
    provider: heap
    says: lists Heap as an integration
    source: https://www.mintlify.com/docs/integrations/analytics/heap.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Hightouch
    provider: hightouch
    says: lists Hightouch as an integration
    source: https://www.mintlify.com/docs/integrations/analytics/hightouch.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Hotjar
    provider: hotjar
    says: lists Hotjar as an integration
    source: https://www.mintlify.com/docs/integrations/analytics/hotjar.md
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
    source: https://www.mintlify.com/docs/automations/integrations.md
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
    source: https://www.mintlify.com/docs/integrations/support/intercom.md
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
    source: https://www.mintlify.com/docs/automations/integrations.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    credit: null
    layer: common
    name: LaunchDarkly
    provider: launchdarkly
    says: lists LaunchDarkly as an integration
    source: https://www.mintlify.com/docs/automations/integrations.md
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
    source: https://www.mintlify.com/docs/automations/integrations.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: LogRocket
    provider: logrocket
    says: lists LogRocket as an integration
    source: https://www.mintlify.com/docs/integrations/analytics/logrocket.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Clarity
    provider: microsoft-clarity
    says: lists Microsoft Clarity as an integration
    source: https://www.mintlify.com/docs/integrations/analytics/clarity.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Mixpanel
    provider: mixpanel
    says: lists Mixpanel as an integration
    source: https://www.mintlify.com/docs/integrations/analytics/mixpanel.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    credit: null
    layer: common
    name: Notion
    provider: notion
    says: lists Notion as an integration
    source: https://www.mintlify.com/docs/automations/integrations.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: OneDrive
    provider: microsoft-onedrive
    says: lists OneDrive as an integration
    source: https://www.mintlify.com/docs/automations/integrations.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    credit: null
    layer: common
    name: OneNote
    provider: microsoft-onenote
    says: lists OneNote as an integration
    source: https://www.mintlify.com/docs/automations/integrations.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.50
      key: AE-160.50
      name: Consent & Preferences
      url: /capabilities/consent-preferences/
      via_parent: null
    credit: null
    layer: common
    name: Osano
    provider: osano
    says: lists Osano as an integration
    source: https://www.mintlify.com/docs/integrations/privacy/osano.md
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
    source: https://www.mintlify.com/docs/automations/integrations.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Pirsch
    provider: pirsch
    says: lists Pirsch as an integration
    source: https://www.mintlify.com/docs/integrations/analytics/pirsch.md
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
    name: Plain
    provider: plain
    says: lists Plain as an integration
    source: https://www.mintlify.com/docs/automations/integrations.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Plausible
    provider: plausible
    says: lists Plausible as an integration
    source: https://www.mintlify.com/docs/integrations/analytics/plausible.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: PostHog
    provider: posthog
    says: lists PostHog as an integration
    source: https://www.mintlify.com/docs/integrations/analytics/posthog.md
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
    name: Pylon
    provider: pylon
    says: lists Pylon as an integration
    source: https://www.mintlify.com/docs/automations/integrations.md
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
    source: https://www.mintlify.com/docs/automations/integrations.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Segment
    provider: segment
    says: lists Segment as an integration
    source: https://www.mintlify.com/docs/integrations/analytics/segment.md
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
    source: https://www.mintlify.com/docs/agent/slack.md
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
    source: https://www.mintlify.com/docs/automations/integrations.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.50
      key: AE-160.50
      name: Consent & Preferences
      url: /capabilities/consent-preferences/
      via_parent: null
    credit: null
    layer: common
    name: Transcend
    provider: transcend
    says: lists Transcend as an integration
    source: https://www.mintlify.com/docs/integrations/privacy/transcend.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3740.30
      key: content-delivery-network-operations
      name: Content Delivery Network Operations
      url: /capabilities/content-delivery-network-operations/
      via_parent: null
    credit: null
    layer: common
    name: Vercel
    provider: vercel
    says: lists Vercel as an integration
    source: https://www.mintlify.com/docs/deploy/vercel.md
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
    source: https://www.mintlify.com/docs/automations/integrations.md
    tier: declared
  kind: commercial
  name: Mintlify
  page: /applications/developer-docs-portal/mintlify/
  slug: mintlify
  url: https://www.mintlify.com/
- anchor: readme
  counts:
    declared: 17
    observed: 0
  evidence:
  - route: integrations page
    url: https://docs.readme.com/llms.txt
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80.10
      key: AE-170.80.10
      name: Web Fonts & Typography
      url: /capabilities/design-creative-editing/
      via_parent: Design & Creative Editing
    credit: null
    layer: common
    name: Adobe Fonts (Typekit)
    provider: adobe
    says: lists Adobe Fonts (Typekit) as an integration
    source: https://docs.readme.com/main/docs/typekit-key.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-909
      key: AE-909
      name: API Gateways
      url: /capabilities/api-consumption-governance/
      via_parent: API Consumption Governance
    credit: null
    layer: domain
    name: Amazon API Gateway
    provider: aws-api-gateway
    says: lists Amazon API Gateway as an integration
    source: https://docs.readme.com/main/docs/aws.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bitbucket
    provider: bitbucket
    says: lists Bitbucket as an integration
    source: https://docs.readme.com/main/docs/sync-with-bitbucket.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://docs.readme.com/main/docs/sync-with-github.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: lists GitLab as an integration
    source: https://docs.readme.com/main/docs/sync-with-gitlab.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Google Analytics
    provider: google-analytics
    says: lists Google Analytics as an integration
    source: https://docs.readme.com/main/docs/google-analytics.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: Google reCAPTCHA
    provider: google-recaptcha
    says: lists Google reCAPTCHA as an integration
    source: https://docs.readme.com/main/docs/recaptcha.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Site Verification
    provider: google-search-console
    says: lists Google Site Verification as an integration
    source: https://docs.readme.com/main/docs/google-site-verification.md
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
    source: https://docs.readme.com/main/docs/searching-readme-within-the-intercom-widget-changing-so-404-results-rb.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.20
      key: AE-170.70.20
      name: Translation Management & Localization
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: common
    name: Localize
    provider: localize
    says: lists Localize as an integration
    source: https://docs.readme.com/main/docs/localize.md
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
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://docs.readme.com/main/docs/microsoft-teams.md
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
    name: Okta
    provider: okta
    says: lists Okta as an integration
    source: https://docs.readme.com/main/enterprise/setting-up-okta.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-908
      key: AE-908
      name: API Testing & Mocking
      url: /capabilities/public-api-lifecycle-management/
      via_parent: Public API Lifecycle Management
    credit: null
    layer: domain
    name: Postman
    provider: postman
    says: lists Postman as an integration
    source: https://docs.readme.com/main/docs/postman-1.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Segment
    provider: segment
    says: lists Segment as an integration
    source: https://docs.readme.com/main/docs/segment.md
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
    source: https://docs.readme.com/main/docs/slack.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.20
      key: AE-170.70.20
      name: Translation Management & Localization
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: common
    name: Transifex
    provider: transifex
    says: lists Transifex as an integration
    source: https://docs.readme.com/main/docs/transifex.md
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
    source: https://docs.readme.com/main/docs/zendesk.md
    tier: declared
  kind: commercial
  name: ReadMe
  page: /applications/developer-docs-portal/readme/
  slug: readme
  url: https://readme.com/
- anchor: redocly
  counts:
    declared: 16
    observed: 0
  evidence:
  - route: integrations page
    url: https://redocly.com/llms.txt
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Adobe Analytics
    provider: adobe-analytics
    says: lists Adobe Analytics as an integration
    source: https://redocly.com/docs/platform/config/analytics/adobe.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Amplitude
    provider: amplitude
    says: lists Amplitude as an integration
    source: https://redocly.com/docs/platform/config/analytics/amplitude.md
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
    name: Auth0
    provider: auth0
    says: lists Auth0 as an integration
    source: https://redocly.com/docs/platform/organization/sso/configure-auth0.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Azure DevOps
    provider: microsoft-azure-devops
    says: lists Azure DevOps as an integration
    source: https://redocly.com/docs/platform/project/connect-git/azure-devops.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bitbucket Cloud
    provider: bitbucket
    says: lists Bitbucket Cloud as an integration
    source: https://redocly.com/docs/platform/project/connect-git/bitbucket-cloud.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Fullstory
    provider: fullstory
    says: lists Fullstory as an integration
    source: https://redocly.com/docs/platform/config/analytics/fullstory.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://redocly.com/docs/platform/project/connect-git/github.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: lists GitLab as an integration
    source: https://redocly.com/docs/platform/project/connect-git/gitlab.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Google Analytics
    provider: google-analytics
    says: lists Google Analytics as an integration
    source: https://redocly.com/docs/platform/config/analytics/google.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: null
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: lists Google Tag Manager as an integration
    source: https://redocly.com/docs/platform/config/analytics/gtm.md
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
    name: Google Workspace
    provider: google-workspace
    says: lists Google Workspace as an integration
    source: https://redocly.com/docs/platform/organization/sso/configure-google-sso.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Heap
    provider: heap
    says: lists Heap as an integration
    source: https://redocly.com/docs/platform/config/analytics/heap.md
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
    name: Microsoft Entra ID
    provider: microsoft-entra
    says: lists Microsoft Entra ID as an integration
    source: https://redocly.com/docs/platform/organization/sso/configure-azure-ad.md
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
    name: Okta
    provider: okta
    says: lists Okta as an integration
    source: https://redocly.com/docs/platform/organization/sso/configure-okta.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: RudderStack
    provider: rudderstack
    says: lists RudderStack as an integration
    source: https://redocly.com/docs/platform/config/analytics/rudderstack.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Segment
    provider: segment
    says: lists Segment as an integration
    source: https://redocly.com/docs/platform/config/analytics/segment.md
    tier: declared
  kind: commercial
  name: Redocly
  page: /applications/developer-docs-portal/redocly/
  slug: redocly
  url: https://redocly.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: developer-docs-portal
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Static Site Generators
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#static-site-generators
- category: Wikis
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#wikis
- category: Knowledge Management Tools
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#knowledge-management-tools
- category: Documentation / TechDocs
  store: backstage-plugins
  url: https://backstage.io/plugins
- category: Integrations marketplace
  store: gitbook-integrations
  url: https://www.gitbook.com/integrations
name: Developer Docs & API Portals
needs:
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  fit: exact
  layer: domain
  why: 'docs search: Algolia DocSearch (Docusaurus), Elastic and Stack Overflow collators (Backstage)'
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.30
    key: AE-110.60.30
    name: Retrieval-Augmented Generation
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  fit: exact
  layer: domain
  why: 'AI "ask the docs" assistants: Inkeep (Zudoku), RunLLM (GitBook)'
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'docs-as-code: Git sync with GitHub, GitLab, Bitbucket, Azure DevOps in every commercial portal; Backstage ingests the catalog from forges'
- capability:
    attribution: API Evangelist extension
    id: AE-909
    key: AE-909
    name: API Gateways
    url: /capabilities/api-consumption-governance/
    via_parent: API Consumption Governance
  fit: exact
  layer: domain
  why: 'API reference sourced from a gateway: Zuplo keys (Zudoku), Amazon API Gateway import (ReadMe)'
- capability:
    attribution: API Evangelist extension
    id: AE-908
    key: AE-908
    name: API Testing & Mocking
    url: /capabilities/public-api-lifecycle-management/
    via_parent: Public API Lifecycle Management
  fit: exact
  layer: domain
  why: Postman collection sync (ReadMe)
- capability:
    attribution: API Evangelist extension
    id: AE-160.10
    key: AE-160.10
    name: Customer Sign-In
    url: /capabilities/customer-sign-in/
    via_parent: null
  fit: exact
  layer: domain
  why: 'developer sign-in to the portal to get API keys: Auth0, Clerk, Firebase, Supabase, Cognito, Azure B2C'
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: GitHub/GitLab/Google/Bitbucket sign-in to Backstage
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: 'workforce SSO for private docs and portals: Okta, Entra ID, Auth0, OneLogin, Google Workspace'
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: Microsoft Graph org ingestion (Backstage)
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: docs traffic analytics, the most common integration across every portal
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: Google Tag Manager
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: common
  why: 'CDPs and reverse ETL: Segment, RudderStack, Hightouch'
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.20
    key: AE-230.30.20
    name: Lead Data
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  fit: nearest
  layer: common
  why: B2B visitor de-anonymisation on docs (Koala, Reo.Dev, SalesViewer, Unify, ZoomInfo); nearest fit, see candidate node
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.10
    key: AE-230.30.10
    name: Data Enrichment
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  fit: exact
  layer: common
  why: Clearbit reveal (Mintlify)
- capability:
    attribution: API Evangelist extension
    id: AE-160.50
    key: AE-160.50
    name: Consent & Preferences
    url: /capabilities/consent-preferences/
    via_parent: null
  fit: exact
  layer: common
  why: 'cookie consent: OneTrust, Osano, Cookiebot, Transcend, CookieScript, Gravito'
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: 'support widgets on docs: Intercom, Zendesk, Front, Freshdesk, Help Scout, Crisp, Plain, Pylon'
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: Slack / Teams / Discord notifications and agent chat
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring (Sentry)
- capability:
    attribution: API Evangelist extension
    id: AE-926
    key: AE-926
    name: Web Hosting & Control Panels
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: 'static docs hosting: GitHub Pages, Netlify, Vercel (Docusaurus deployment guides)'
- capability:
    attribution: Turbo EA
    id: BC-3740.30
    key: content-delivery-network-operations
    name: Content Delivery Network Operations
    url: /capabilities/content-delivery-network-operations/
    via_parent: null
  fit: exact
  layer: common
  why: serving docs on a /docs subpath behind Vercel, Cloudflare, CloudFront (Mintlify)
- capability:
    attribution: API Evangelist extension
    id: AE-927
    key: AE-927
    name: Domain Registration & Managed DNS
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: Route 53 for custom docs domains
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: 'TechDocs static-site publishers: S3, Azure Blob, GCS, OpenStack Swift'
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: common
  why: Backstage event ingestion from SQS, Pub/Sub, Kafka
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  fit: exact
  layer: common
  why: Backstage catalog ingestion of cloud resources (AWS, GCP, PuppetDB)
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: common
  why: Jira / Linear issue context for docs agents and feedback
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  fit: exact
  layer: common
  why: Notion / OneNote as agent context (Mintlify)
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  fit: exact
  layer: common
  why: Confluence import / agent context
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: content-management
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  fit: exact
  layer: common
  why: Contentful as agent context (Mintlify)
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.30
    key: AE-170.70.30
    name: Interactive Product Demos
    url: /capabilities/content-management/
    via_parent: Content Management
  fit: exact
  layer: common
  why: 'Interactive Product Demos: Arcade, Navattic'
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.20
    key: AE-170.70.20
    name: Translation Management & Localization
    url: /capabilities/content-management/
    via_parent: Content Management
  fit: exact
  layer: common
  why: Transifex, Localize
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  fit: exact
  layer: common
  why: Figma and Lucid embeds
- capability:
    attribution: API Evangelist extension
    id: AE-170.80.10
    key: AE-170.80.10
    name: Web Fonts & Typography
    url: /capabilities/design-creative-editing/
    via_parent: Design & Creative Editing
  fit: exact
  layer: common
  why: Adobe Fonts (Typekit) in ReadMe custom CSS
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  fit: exact
  layer: common
  why: Wistia embeds
- capability:
    attribution: API Evangelist extension
    id: AE-905
    key: AE-905
    name: IDEs & AI Coding Assistants
    url: /capabilities/engineering-productivity-management/
    via_parent: Engineering Productivity Management
  fit: exact
  layer: common
  why: GitHub Copilot extension (GitBook)
- capability:
    attribution: API Evangelist extension
    id: AE-906
    key: AE-906
    name: Code Execution Sandboxes
    url: /capabilities/engineering-productivity-management/
    via_parent: Engineering Productivity Management
  fit: exact
  layer: common
  why: RunKit runnable code blocks (GitBook)
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  fit: exact
  layer: common
  why: Formspree feedback forms
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: Excel as agent context
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: Google Drive / Docs / OneDrive as agent context
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: common
  why: Gmail / Outlook as personal agent context
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: Mailchimp signup blocks
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: reCAPTCHA on ReadMe forums
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  fit: exact
  layer: common
  why: LaunchDarkly / Bucket flags in docs
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: common
  why: HubSpot / Salesforce context and lead capture
- capability:
    attribution: Turbo EA
    id: BC-400.50
    key: marketing-operations-management
    name: Marketing Operations Management
    url: /capabilities/marketing-operations-management/
    via_parent: null
  fit: exact
  layer: common
  why: Marketo forms
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: 'SEO tooling: Ahrefs, Google Search Console verification'
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: common
  why: Toucan Toco embedded charts
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: Stripe as agent context / automation trigger
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.40
    key: AE-230.30.40
    name: Website Visitor Identification & Buyer Intent
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  fit: exact
  layer: common
  why: Koala, Reo.Dev, SalesViewer (Website Visitor Identification & Buyer Intent)
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Backstage
      - GitBook
      - Mintlify
      - ReadMe
      - Redocly
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp: &id005
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://docs.readme.com/main/docs/sync-with-gitlab.md
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags: &id006
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Backstage
      - GitBook
      - Mintlify
      - ReadMe
      - Redocly
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: &id007
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://docs.readme.com/main/docs/sync-with-github.md
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags: &id008
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Backstage
      - Mintlify
      - ReadMe
      - Redocly
      band: exemplar
      in_catalog: true
      kin_score: 71.9
      mcp: &id009
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Bitbucket
      slug: bitbucket
      sources:
      - https://docs.readme.com/main/docs/sync-with-bitbucket.md
      - https://github.com/backstage/backstage/tree/master/plugins
      - https://redocly.com/docs/platform/project/connect-git/bitbucket-cloud.md
      status: profiled
      tags: &id010
      - Atlassian
      - CI/CD
      - Code Collaboration
      - Code Review
      tier: observed
      url: /providers/bitbucket/
    - agent_band: agent-ready
      agent_readiness: 37.7
      apps:
      - Backstage
      - Mintlify
      - Redocly
      band: exemplar
      in_catalog: true
      kin_score: 81.9
      mcp:
        source: https://github.com/microsoft/azure-devops-mcp
        status: verified
      name: Azure DevOps
      slug: microsoft-azure-devops
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      - https://redocly.com/docs/platform/project/connect-git/azure-devops.md
      - https://www.mintlify.com/docs/deploy/azure-repos.md
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
      - Backstage
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        source: https://gitea.com/gitea/gitea-mcp
        status: verified
      name: Gitea
      slug: gitea
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags:
      - CI/CD
      - DevOps
      - Gitea
      - Version Control
      tier: observed
      url: /providers/gitea/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Backstage
      band: minimal
      in_catalog: true
      kin_score: 6.8
      mcp:
        source: https://github.com/GerritCodeReview/gerrit-mcp-server
        status: verified
      name: Gerrit
      slug: gerrit
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags:
      - Code Review
      - Company
      - Open Source
      - Version Control
      tier: observed
      url: /providers/gerrit/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10
      key: AE-160.10
      name: Customer Sign-In
      url: /capabilities/customer-sign-in/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 51.9
      apps:
      - Zudoku
      band: exemplar
      in_catalog: true
      kin_score: 73.4
      mcp:
        source: https://github.com/clerk/mcp-tools
        status: verified
      name: Clerk
      slug: clerk-com
      sources:
      - https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
      status: profiled
      tags:
      - Authentication
      - Authorization
      - B2B SaaS
      - CIAM
      tier: observed
      url: /providers/clerk-com/
    - agent_band: agent-ready
      agent_readiness: 39.5
      apps:
      - Zudoku
      band: exemplar
      in_catalog: true
      kin_score: 71.8
      mcp: &id003
        source: https://auth0.com/docs/get-started/auth0-mcp-server
        status: verified
      name: Auth0
      slug: auth0
      sources:
      - https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
      status: profiled
      tags: &id004
      - AI Agents
      - Auth0
      - Authentication
      - Authorization
      tier: observed
      url: /providers/auth0/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Zudoku
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp: &id001
        status: none
      name: Azure AD B2C
      slug: microsoft-entra
      sources:
      - https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
      status: profiled
      tags: &id002
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Zudoku
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase Auth
      slug: google-firebase
      sources:
      - https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
      status: profiled
      tags:
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 48.2
      apps:
      - Zudoku
      band: developing
      in_catalog: true
      kin_score: 49.4
      mcp:
        source: https://github.com/supabase/mcp
        status: verified
      name: Supabase Auth
      slug: supabase
      sources:
      - https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
      status: profiled
      tags:
      - Authentication
      - Backend-as-a-Service
      - Open Source
      - PostgreSQL
      tier: observed
      url: /providers/supabase/
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 61.9
      apps:
      - Docusaurus
      band: exemplar
      in_catalog: true
      kin_score: 81.1
      mcp:
        status: none
      name: Algolia DocSearch
      slug: algolia
      sources:
      - https://github.com/facebook/docusaurus/tree/main/packages
      status: profiled
      tags:
      - Discovery
      - Personalization
      - Recommendations
      - Search
      tier: observed
      url: /providers/algolia/
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Backstage
      band: exemplar
      in_catalog: true
      kin_score: 78.4
      mcp:
        source: https://www.elastic.co/docs/solutions/search/mcp
        status: verified
      name: Elastic
      slug: elastic
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags:
      - Analytics
      - Observability
      - Search
      - Security
      tier: observed
      url: /providers/elastic/
    - agent_band: agent-ready
      agent_readiness: 33.3
      apps:
      - Backstage
      band: thin
      in_catalog: true
      kin_score: 36.6
      mcp:
        source: https://github.com/StackExchange/Stack-MCP
        status: verified
      name: Stack Overflow
      slug: stack-overflow
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags:
      - Answers
      - Code
      - Developer Community
      - Developer Tools
      tier: observed
      url: /providers/stack-overflow/
  - capability:
      attribution: API Evangelist extension
      id: AE-909
      key: AE-909
      name: API Gateways
      url: /capabilities/api-consumption-governance/
      via_parent: API Consumption Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 57.2
      apps:
      - Zudoku
      band: exemplar
      in_catalog: true
      kin_score: 72.8
      mcp:
        source: https://dev.zuplo.com/mcp
        status: verified
      name: Zuplo
      slug: zuplo
      sources:
      - https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/plugins
      status: profiled
      tags:
      - AI Gateway
      - API Management
      - Gateways
      - Platform
      tier: observed
      url: /providers/zuplo/
    - agent_band: agent-ready
      agent_readiness: 42.0
      apps:
      - ReadMe
      band: exemplar
      in_catalog: true
      kin_score: 77.4
      mcp:
        status: none
      name: Amazon API Gateway
      slug: aws-api-gateway
      sources:
      - https://docs.readme.com/main/docs/aws.md
      status: profiled
      tags:
      - API Gateway
      - Amazon Web Services
      - Cloud
      - REST
      tier: declared
      url: /providers/aws-api-gateway/
  - capability:
      attribution: API Evangelist extension
      id: AE-908
      key: AE-908
      name: API Testing & Mocking
      url: /capabilities/public-api-lifecycle-management/
      via_parent: Public API Lifecycle Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.5
      apps:
      - ReadMe
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://github.com/postmanlabs/postman-mcp-server
        status: verified
      name: Postman
      slug: postman
      sources:
      - https://docs.readme.com/main/docs/postman-1.md
      status: profiled
      tags:
      - Environment
      - Flow
      - Specification
      - Workspace
      tier: declared
      url: /providers/postman/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - Zudoku
      band: thin
      in_catalog: true
      kin_score: 31.4
      mcp:
        source: https://docs.inkeep.com/talk-to-your-agents/mcp-server
        status: verified
      name: Inkeep
      slug: inkeep
      sources:
      - https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/plugins
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - RAG
      - Support
      tier: observed
      url: /providers/inkeep/
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
      - Zudoku
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp: *id001
      name: Microsoft Entra ID
      slug: microsoft-entra
      sources:
      - https://github.com/zuplo/zudoku/tree/main/packages/zudoku/src/lib/authentication/providers
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/microsoft-entra/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Docusaurus
      - GitBook
      - Mintlify
      - ReadMe
      - Redocly
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics (gtag)
      slug: google-analytics
      sources:
      - https://docs.readme.com/main/docs/google-analytics.md
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://github.com/facebook/docusaurus/tree/main/packages
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - GitBook
      - Mintlify
      - Redocly
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://redocly.com/docs/platform/config/analytics/amplitude.md
      - https://www.mintlify.com/docs/integrations/analytics/amplitude.md
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 56.2
      apps:
      - GitBook
      - Mintlify
      - Zudoku
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://github.com/zuplo/zudoku/blob/main/packages/zudoku/package.json
      - https://www.mintlify.com/docs/integrations/analytics/posthog.md
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
    - agent_band: agent-aware
      agent_readiness: 26.3
      apps:
      - GitBook
      - Mintlify
      - Redocly
      band: developing
      in_catalog: true
      kin_score: 40.6
      mcp:
        status: unknown
      name: Heap
      slug: heap
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://redocly.com/docs/platform/config/analytics/heap.md
      - https://www.mintlify.com/docs/integrations/analytics/heap.md
      status: profiled
      tags:
      - Analytics
      - Autocapture
      - Digital Analytics
      - Product Analytics
      tier: observed
      url: /providers/heap/
    - agent_band: agent-aware
      agent_readiness: 22.6
      apps:
      - GitBook
      - Mintlify
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        status: none
      name: Plausible
      slug: plausible
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://www.mintlify.com/docs/integrations/analytics/plausible.md
      status: profiled
      tags:
      - Analytics
      - Cookie-Free
      - Event Tracking
      - GDPR
      tier: observed
      url: /providers/plausible/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - GitBook
      - Mintlify
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://www.mintlify.com/docs/integrations/analytics/mixpanel.md
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
    - agent_band: agent-ready
      agent_readiness: 30.3
      apps:
      - GitBook
      - Mintlify
      band: developing
      in_catalog: true
      kin_score: 47.7
      mcp:
        status: none
      name: Fathom Analytics
      slug: fathom
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://www.mintlify.com/docs/integrations/analytics/fathom.md
      status: profiled
      tags:
      - Analytics
      - GDPR
      - Privacy
      - Website Analytics
      tier: observed
      url: /providers/fathom/
    - agent_band: agent-ready
      agent_readiness: 30.0
      apps:
      - GitBook
      - Redocly
      band: thin
      in_catalog: true
      kin_score: 37.4
      mcp:
        source: https://developer.fullstory.com/mcp/introduction/
        status: documented
      name: FullStory
      slug: fullstory
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://redocly.com/docs/platform/config/analytics/fullstory.md
      status: profiled
      tags:
      - Behavioral Analytics
      - Digital Experience
      - Product Analytics
      - Session Replay
      tier: observed
      url: /providers/fullstory/
    - agent_band: agent-aware
      agent_readiness: 27.3
      apps:
      - GitBook
      - Mintlify
      band: emerging
      in_catalog: true
      kin_score: 25.5
      mcp:
        status: none
      name: Hotjar
      slug: hotjar
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://www.mintlify.com/docs/integrations/analytics/hotjar.md
      status: profiled
      tags:
      - Analytics
      - Personalization
      - Surveys
      - Tracking
      tier: observed
      url: /providers/hotjar/
    - agent_band: agent-native
      agent_readiness: 60.3
      apps:
      - Mintlify
      - Redocly
      band: strong
      in_catalog: true
      kin_score: 65.0
      mcp:
        status: none
      name: Adobe Analytics
      slug: adobe-analytics
      sources:
      - https://redocly.com/docs/platform/config/analytics/adobe.md
      - https://www.mintlify.com/docs/integrations/analytics/adobe.md
      status: profiled
      tags:
      - Adobe
      - Analytics
      - Business Intelligence
      - Customer Intelligence
      tier: declared
      url: /providers/adobe-analytics/
    - agent_band: agent-ready
      agent_readiness: 50.0
      apps:
      - Docusaurus
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp: &id013
        source: https://vercel.com/docs/mcp/vercel-mcp
        status: verified
      name: Vercel Analytics
      slug: vercel
      sources:
      - https://github.com/facebook/docusaurus/tree/main/packages
      status: profiled
      tags: &id014
      - AI Gateway
      - Gateways
      - Observability
      - Webhook
      tier: observed
      url: /providers/vercel/
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - GitBook
      band: strong
      in_catalog: true
      kin_score: 57.0
      mcp:
        source: https://support.pendo.io/hc/en-us/articles/41102236924955
        status: verified
      name: Pendo
      slug: pendoio
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Company
      - Digital Adoption
      - Product Analytics
      - Product Experience
      tier: observed
      url: /providers/pendoio/
    - agent_band: agent-native
      agent_readiness: 49.2
      apps:
      - GitBook
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        status: unchecked
      name: DevTune
      slug: devtune
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Company
      - Search
      tier: observed
      url: /providers/devtune/
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - GitBook
      band: developing
      in_catalog: true
      kin_score: 50.8
      mcp:
        status: unchecked
      name: Piwik PRO
      slug: piwik-pro
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Analytics
      - Data Activation
      - Enterprise
      - Privacy
      tier: observed
      url: /providers/piwik-pro/
    - agent_band: agent-ready
      agent_readiness: 31.7
      apps:
      - Mintlify
      band: exemplar
      in_catalog: true
      kin_score: 67.9
      mcp:
        source: https://docs.pirsch.io/integrations/mcp
        status: verified
      name: Pirsch
      slug: pirsch
      sources:
      - https://www.mintlify.com/docs/integrations/analytics/pirsch.md
      status: profiled
      tags:
      - Analytics
      - GDPR
      - Privacy
      - Web Analytics
      tier: declared
      url: /providers/pirsch/
    - agent_band: agent-ready
      agent_readiness: 29.9
      apps:
      - Mintlify
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://github.com/microsoft/clarity-mcp-server
        status: verified
      name: Microsoft Clarity
      slug: microsoft-clarity
      sources:
      - https://www.mintlify.com/docs/integrations/analytics/clarity.md
      status: profiled
      tags:
      - Analytics
      - Heatmaps
      - Session Recording
      - Web Analytics
      tier: declared
      url: /providers/microsoft-clarity/
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Mintlify
      band: thin
      in_catalog: true
      kin_score: 35.5
      mcp:
        source: https://mcp.logrocket.com/mcp
        status: verified
      name: LogRocket
      slug: logrocket
      sources:
      - https://www.mintlify.com/docs/integrations/analytics/logrocket.md
      status: profiled
      tags:
      - Frontend Monitoring
      - Logging
      - Product Analytics
      - Session Replay
      tier: declared
      url: /providers/logrocket/
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Backstage
      - GitBook
      - ReadMe
      - Redocly
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://docs.readme.com/main/enterprise/setting-up-okta.md
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: observed
      url: /providers/okta/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Backstage
      - GitBook
      - Redocly
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp: *id001
      name: Microsoft
      slug: microsoft-entra
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://github.com/backstage/backstage/tree/master/plugins
      - https://redocly.com/docs/platform/organization/sso/configure-azure-ad.md
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 39.5
      apps:
      - Backstage
      - Redocly
      band: exemplar
      in_catalog: true
      kin_score: 71.8
      mcp: *id003
      name: Auth0
      slug: auth0
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      - https://redocly.com/docs/platform/organization/sso/configure-auth0.md
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/auth0/
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - Backstage
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: &id011
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare Access
      slug: cloudflare
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags: &id012
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: observed
      url: /providers/cloudflare/
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - Backstage
      band: exemplar
      in_catalog: true
      kin_score: 79.8
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Atlassian
      slug: atlassian
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags:
      - Code
      - Collaboration
      - Platform
      - Productivity
      tier: observed
      url: /providers/atlassian/
    - agent_band: agent-ready
      agent_readiness: 45.0
      apps:
      - Backstage
      band: exemplar
      in_catalog: true
      kin_score: 76.0
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Easy Auth
      slug: microsoft-azure
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags:
      - Cloud
      - Cloud Computing
      - Enterprise
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Backstage
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp: &id017
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS ALB
      slug: amazon-web-services
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags: &id018
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: observed
      url: /providers/amazon-web-services/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Backstage
      band: exemplar
      in_catalog: true
      kin_score: 67.5
      mcp: &id019
        source: https://github.com/googleapis/mcp-toolbox
        status: verified
      name: Google Cloud IAP
      slug: google-cloud-platform
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags: &id020
      - API Management
      - Cloud Computing
      - Infrastructure
      - Platform-as-a-Service
      tier: observed
      url: /providers/google-cloud-platform/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Backstage
      band: developing
      in_catalog: true
      kin_score: 49.8
      mcp:
        status: none
      name: VMware Cloud
      slug: vmware
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags:
      - Cloud Computing
      - Container Management
      - Hybrid Cloud
      - Infrastructure
      tier: observed
      url: /providers/vmware/
    - agent_band: agent-aware
      agent_readiness: 24.3
      apps:
      - Backstage
      band: thin
      in_catalog: true
      kin_score: 29.5
      mcp:
        source: https://github.com/onelogin/onelogin-mcp
        status: verified
      name: OneLogin
      slug: onelogin
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags:
      - Identity
      - Identity and Access Management
      - Multi-Factor Authentication
      - SSO
      tier: observed
      url: /providers/onelogin/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Redocly
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/gemini-cli-extensions/workspace
        status: verified
      name: Google Workspace
      slug: google-workspace
      sources:
      - https://redocly.com/docs/platform/organization/sso/configure-google-sso.md
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/google-workspace/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - GitBook
      - Mintlify
      - ReadMe
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://docs.readme.com/main/docs/searching-readme-within-the-intercom-widget-changing-so-404-results-rb.md
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://www.mintlify.com/docs/integrations/support/intercom.md
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: observed
      url: /providers/intercom/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - GitBook
      - Mintlify
      band: developing
      in_catalog: true
      kin_score: 53.6
      mcp:
        source: https://dev.frontapp.com/docs/mcp
        status: documented
      name: Front
      slug: front
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://www.mintlify.com/docs/integrations/support/front.md
      status: profiled
      tags:
      - Customer Operations
      - Customer Service
      - Email
      - Inbox
      tier: observed
      url: /providers/front/
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Mintlify
      - ReadMe
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://docs.readme.com/main/docs/zendesk.md
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - GitBook
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp: &id015
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce chat
      slug: salesforce
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags: &id016
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: observed
      url: /providers/salesforce/
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - GitBook
      band: developing
      in_catalog: true
      kin_score: 51.5
      mcp:
        status: none
      name: Help Scout
      slug: helpscout
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Customer Service
      - Email
      - Help Desk
      - Live Chat
      tier: observed
      url: /providers/helpscout/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - GitBook
      band: thin
      in_catalog: true
      kin_score: 29.7
      mcp:
        status: none
      name: Freshdesk
      slug: freshdesk
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Application
      - Automation
      - Customer Service
      - Help Desk
      tier: observed
      url: /providers/freshdesk/
    - agent_band: agent-ready
      agent_readiness: 29.4
      apps:
      - GitBook
      band: emerging
      in_catalog: true
      kin_score: 26.1
      mcp:
        status: none
      name: Crisp
      slug: crisp
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Customer Service
      - Help Desk
      - Live Chat
      - Messaging
      tier: observed
      url: /providers/crisp/
    - agent_band: agent-ready
      agent_readiness: 50.3
      apps:
      - Mintlify
      band: strong
      in_catalog: true
      kin_score: 61.8
      mcp:
        source: https://github.com/team-plain/cursor-plugin-mcp
        status: verified
      name: Plain
      slug: plain
      sources:
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - Company
      - Customer Service
      - Help Desk
      - Support
      tier: declared
      url: /providers/plain/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Mintlify
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        status: unknown
      name: Pylon
      slug: pylon
      sources:
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - Customer Operations
      - Customer Service
      - Knowledge Base
      - Ticketing
      tier: declared
      url: /providers/pylon/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.50
      key: AE-160.50
      name: Consent & Preferences
      url: /capabilities/consent-preferences/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - GitBook
      - Mintlify
      band: strong
      in_catalog: true
      kin_score: 54.3
      mcp:
        status: none
      name: Osano
      slug: osano
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://www.mintlify.com/docs/integrations/privacy/osano.md
      status: profiled
      tags:
      - Company
      - Compliance
      - Consent Management
      - Privacy
      tier: observed
      url: /providers/osano/
    - agent_band: agent-ready
      agent_readiness: 57.2
      apps:
      - GitBook
      band: exemplar
      in_catalog: true
      kin_score: 78.3
      mcp:
        status: none
      name: OneTrust
      slug: onetrust
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Compliance
      - Consent
      - GRC
      - Privacy
      tier: observed
      url: /providers/onetrust/
    - agent_band: agent-aware
      agent_readiness: 20.1
      apps:
      - GitBook
      band: thin
      in_catalog: true
      kin_score: 37.1
      mcp:
        status: none
      name: Cookiebot
      slug: usercentrics
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - CMP
      - Compliance
      - Consent
      - Privacy
      tier: observed
      url: /providers/usercentrics/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - GitBook
      band: thin
      in_catalog: true
      kin_score: 29.5
      mcp:
        status: unchecked
      name: CookieScript
      slug: cookie-script
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Consent Management Platform
      - Cookie Consent
      - GDPR Compliance
      - Privacy Management
      tier: observed
      url: /providers/cookie-script/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - GitBook
      band: emerging
      in_catalog: true
      kin_score: 21.2
      mcp:
        status: unchecked
      name: Gravito
      slug: gravito
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Consent Management
      - Data Platform
      - First-Party Data
      - Traffic Quality
      tier: observed
      url: /providers/gravito/
    - agent_band: null
      agent_readiness: null
      apps:
      - Mintlify
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Transcend
      slug: transcend
      sources:
      - https://www.mintlify.com/docs/integrations/privacy/transcend.md
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - GitBook
      - Mintlify
      - ReadMe
      - Redocly
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://docs.readme.com/main/docs/segment.md
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://redocly.com/docs/platform/config/analytics/segment.md
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - Redocly
      band: exemplar
      in_catalog: true
      kin_score: 79.1
      mcp:
        source: https://github.com/rudderlabs/rudderstack-mcp
        status: verified
      name: RudderStack
      slug: rudderstack
      sources:
      - https://redocly.com/docs/platform/config/analytics/rudderstack.md
      status: profiled
      tags:
      - CDP
      - Customer Data Platform
      - Data Pipeline
      - Open Source
      tier: declared
      url: /providers/rudderstack/
    - agent_band: agent-ready
      agent_readiness: 62.8
      apps:
      - Mintlify
      band: exemplar
      in_catalog: true
      kin_score: 66.9
      mcp:
        source: https://hightouch.com/docs/ai-integrations/mcp
        status: documented
      name: Hightouch
      slug: hightouch
      sources:
      - https://www.mintlify.com/docs/integrations/analytics/hightouch.md
      status: profiled
      tags:
      - Audience Management
      - CDP
      - Data Activation
      - Reverse ETL
      tier: declared
      url: /providers/hightouch/
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
      - Backstage
      - GitBook
      - Mintlify
      - ReadMe
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://docs.readme.com/main/docs/slack.md
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://github.com/backstage/backstage/tree/master/plugins
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
      - GitBook
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - ReadMe
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://docs.readme.com/main/docs/microsoft-teams.md
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: declared
      url: /providers/microsoft-teams/
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
      - Backstage
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp: *id005
      name: GitLab
      slug: gitlab
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Backstage
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: *id007
      name: GitHub
      slug: github
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Backstage
      band: exemplar
      in_catalog: true
      kin_score: 71.9
      mcp: *id009
      name: Bitbucket
      slug: bitbucket
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags: *id010
      tier: observed
      url: /providers/bitbucket/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Backstage
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Backstage
      band: developing
      in_catalog: true
      kin_score: 53.9
      mcp:
        source: https://github.com/openshift/kubernetes-mcp-server
        status: verified
      name: OpenShift
      slug: red-hat-openshift
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags:
      - Containers
      - Enterprise
      - Hybrid Cloud
      - Kubernetes
      tier: observed
      url: /providers/red-hat-openshift/
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
      - GitBook
      - Mintlify
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: observed
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - GitBook
      - Mintlify
      band: developing
      in_catalog: true
      kin_score: 39.6
      mcp:
        source: https://linear.app/docs/mcp
        status: verified
      name: Linear
      slug: linear-app
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - Issue Tracking
      - Productivity
      - Project Management
      - Software-as-a-Service
      tier: observed
      url: /providers/linear-app/
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
      - Backstage
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins/techdocs-node/src/stages/publish
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
      - Backstage
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins/techdocs-node/src/stages/publish
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Backstage
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins/techdocs-node/src/stages/publish
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Backstage
      band: thin
      in_catalog: true
      kin_score: 34.5
      mcp:
        status: none
      name: OpenStack Swift
      slug: openstack
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins/techdocs-node/src/stages/publish
      status: profiled
      tags:
      - Cloud Platform
      - Infrastructure-as-a-Service
      - Open Source
      - OpenStack
      tier: observed
      url: /providers/openstack/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.40
      key: AE-230.30.40
      name: Website Visitor Identification & Buyer Intent
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 60.5
      apps:
      - GitBook
      band: exemplar
      in_catalog: true
      kin_score: 72.2
      mcp:
        status: none
      name: Unify
      slug: unify
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Go-To-Market
      - Marketing
      - Outbound
      - Sales
      tier: observed
      url: /providers/unify/
    - agent_band: agent-ready
      agent_readiness: 40.0
      apps:
      - GitBook
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        status: none
      name: Koala
      slug: koala-io
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Buyer Intent
      - Data Enrichment
      - De-anonymization
      - Visitor Identification
      tier: observed
      url: /providers/koala-io/
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - GitBook
      band: thin
      in_catalog: true
      kin_score: 33.2
      mcp:
        status: unchecked
      name: SalesViewer
      slug: salesviewer
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - B2B Sales
      - Lead Generation
      tier: observed
      url: /providers/salesviewer/
    - agent_band: null
      agent_readiness: null
      apps:
      - GitBook
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Reo.Dev
      slug: reo-dev
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: queued for profiling
      tags: []
      tier: observed
      url: null
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
      - Mintlify
      band: exemplar
      in_catalog: true
      kin_score: 73.2
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: declared
      url: /providers/google-drive/
    - agent_band: agent-ready
      agent_readiness: 40.3
      apps:
      - Mintlify
      band: exemplar
      in_catalog: true
      kin_score: 67.2
      mcp:
        source: https://docs.cloud.google.com/mcp/supported-products
        status: verified
      name: Google Docs
      slug: google-docs
      sources:
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - Collaboration
      - Documents
      - Google Workspace
      - Productivity
      tier: declared
      url: /providers/google-docs/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Mintlify
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        status: none
      name: OneDrive
      slug: microsoft-onedrive
      sources:
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: declared
      url: /providers/microsoft-onedrive/
  - capability:
      attribution: Turbo EA
      id: BC-3740.30
      key: content-delivery-network-operations
      name: Content Delivery Network Operations
      url: /capabilities/content-delivery-network-operations/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - Mintlify
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: *id011
      name: Cloudflare
      slug: cloudflare
      sources:
      - https://www.mintlify.com/docs/deploy/cloudflare.md
      status: profiled
      tags: *id012
      tier: declared
      url: /providers/cloudflare/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Mintlify
      band: exemplar
      in_catalog: true
      kin_score: 79.6
      mcp:
        status: none
      name: Amazon CloudFront
      slug: cloudfront
      sources:
      - https://www.mintlify.com/docs/deploy/route53-cloudfront.md
      status: profiled
      tags:
      - Amazon Web Services
      - CDN
      - Caching
      - Content Delivery
      tier: declared
      url: /providers/cloudfront/
    - agent_band: agent-ready
      agent_readiness: 50.0
      apps:
      - Mintlify
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp: *id013
      name: Vercel
      slug: vercel
      sources:
      - https://www.mintlify.com/docs/deploy/vercel.md
      status: profiled
      tags: *id014
      tier: declared
      url: /providers/vercel/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - GitBook
      - Mintlify
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: observed
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Mintlify
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp: *id015
      name: Salesforce
      slug: salesforce
      sources:
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags: *id016
      tier: declared
      url: /providers/salesforce/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.2
      apps:
      - GitBook
      - Mintlify
      band: exemplar
      in_catalog: true
      kin_score: 75.1
      mcp:
        source: https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server
        status: verified
      name: Figma
      slug: figma
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - Collaboration
      - Design
      - Graphics
      - Interfaces
      tier: observed
      url: /providers/figma/
    - agent_band: agent-ready
      agent_readiness: 43.8
      apps:
      - GitBook
      band: exemplar
      in_catalog: true
      kin_score: 77.9
      mcp:
        source: https://github.com/lucidsoftware/lucid-mcp-server
        status: verified
      name: Lucid
      slug: lucid
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Diagramming
      - Productivity
      - Visual Collaboration
      - Whiteboarding
      tier: observed
      url: /providers/lucid/
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.7
      apps:
      - GitBook
      - Mintlify
      band: exemplar
      in_catalog: true
      kin_score: 84.5
      mcp:
        source: https://launchdarkly.com/docs/home/getting-started/mcp
        status: verified
      name: LaunchDarkly
      slug: launchdarkly
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - Experimentation
      - Feature Flags
      - Feature Management
      - Observability
      tier: observed
      url: /providers/launchdarkly/
    - agent_band: agent-ready
      agent_readiness: 47.2
      apps:
      - GitBook
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        source: https://docs.reflag.com/api/mcp
        status: verified
      name: Bucket (Reflag)
      slug: bucket
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Company
      - Feature Flagging
      - Feature Flags
      - Feature Management
      tier: observed
      url: /providers/bucket/
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
      - Backstage
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp: *id017
      name: AWS
      slug: amazon-web-services
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags: *id018
      tier: observed
      url: /providers/amazon-web-services/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Backstage
      band: exemplar
      in_catalog: true
      kin_score: 67.5
      mcp: *id019
      name: Google Cloud
      slug: google-cloud-platform
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags: *id020
      tier: observed
      url: /providers/google-cloud-platform/
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Backstage
      band: thin
      in_catalog: true
      kin_score: 32.0
      mcp:
        source: https://github.com/puppetlabs/puppetlabs-pe_mcp
        status: verified
      name: PuppetDB
      slug: puppet
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags:
      - Automation
      - Configuration Management
      - DevOps
      - Enterprise
      tier: observed
      url: /providers/puppet/
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
      - Backstage
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SQS
      slug: amazon-sqs
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
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
      - Backstage
      band: strong
      in_catalog: true
      kin_score: 64.1
      mcp:
        source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
        status: verified
      name: Google Cloud Pub/Sub
      slug: google-cloud-pubsub
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags:
      - Event-Driven
      - Google Cloud
      - Messaging
      - Pub/Sub
      tier: observed
      url: /providers/google-cloud-pubsub/
    - agent_band: agent-aware
      agent_readiness: 27.8
      apps:
      - Backstage
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp:
        status: none
      name: Apache Kafka
      slug: apache-kafka
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      status: profiled
      tags:
      - Apache Kafka
      - Distributed Systems
      - Event Streaming
      - Messaging
      tier: observed
      url: /providers/apache-kafka/
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
      - Backstage
      - GitBook
      - Zudoku
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      - https://github.com/backstage/backstage/tree/master/plugins
      - https://github.com/zuplo/zudoku/blob/main/packages/zudoku/package.json
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Docusaurus
      - Mintlify
      - Redocly
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://github.com/facebook/docusaurus/tree/main/packages
      - https://redocly.com/docs/platform/config/analytics/gtm.md
      - https://www.mintlify.com/docs/integrations/analytics/google-tag-manager.md
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  - capability:
      attribution: API Evangelist extension
      id: AE-926
      key: AE-926
      name: Web Hosting & Control Panels
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Docusaurus
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: *id007
      name: GitHub Pages
      slug: github
      sources:
      - https://github.com/facebook/docusaurus/tree/main/website/docs/deployment/github-pages.mdx
      status: profiled
      tags: *id008
      tier: declared
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 58.9
      apps:
      - Docusaurus
      band: exemplar
      in_catalog: true
      kin_score: 72.2
      mcp:
        source: https://github.com/netlify/netlify-mcp
        status: verified
      name: Netlify
      slug: netlify
      sources:
      - https://github.com/facebook/docusaurus/tree/main/website/docs/deployment/netlify.mdx
      status: profiled
      tags:
      - CDN
      - Cloud
      - Continuous Deployment
      - Developer Tools
      tier: declared
      url: /providers/netlify/
    - agent_band: agent-ready
      agent_readiness: 50.0
      apps:
      - Docusaurus
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp: *id013
      name: Vercel
      slug: vercel
      sources:
      - https://github.com/facebook/docusaurus/tree/main/website/docs/deployment/vercel.mdx
      status: profiled
      tags: *id014
      tier: declared
      url: /providers/vercel/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10
      key: AE-160.10
      name: Customer Sign-In
      url: /capabilities/customer-sign-in/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.3
      apps:
      - GitBook
      band: exemplar
      in_catalog: true
      kin_score: 74.5
      mcp:
        status: none
      name: Amazon Cognito
      slug: amazon-cognito
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Amazon Web Services
      - Authentication
      - Identity
      - OpenID Connect
      tier: observed
      url: /providers/amazon-cognito/
    - agent_band: agent-ready
      agent_readiness: 39.5
      apps:
      - GitBook
      band: exemplar
      in_catalog: true
      kin_score: 71.8
      mcp: *id003
      name: Auth0 (visitor auth)
      slug: auth0
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/auth0/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.5
      apps:
      - GitBook
      band: exemplar
      in_catalog: true
      kin_score: 66.8
      mcp:
        source: https://github.com/ahrefs/ahrefs-mcp-server
        status: verified
      name: Ahrefs
      slug: ahrefs
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Company
      - Marketing
      - SEO
      - Search
      tier: observed
      url: /providers/ahrefs/
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - ReadMe
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        status: none
      name: Google Site Verification
      slug: google-search-console
      sources:
      - https://docs.readme.com/main/docs/google-site-verification.md
      status: profiled
      tags:
      - Analytics
      - Google
      - Indexing
      - Search
      tier: declared
      url: /providers/google-search-console/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.30
      key: AE-170.70.30
      name: Interactive Product Demos
      url: /capabilities/content-management/
      via_parent: Content Management
    providers:
    - agent_band: agent-native
      agent_readiness: 43.8
      apps:
      - GitBook
      band: strong
      in_catalog: true
      kin_score: 62.9
      mcp:
        source: https://docs.navattic.com/workspace/mcp-server
        status: verified
      name: Navattic
      slug: navattic
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Interactive Demos
      - Marketing
      - Product Demo
      - Sales Enablement
      tier: observed
      url: /providers/navattic/
    - agent_band: agent-aware
      agent_readiness: 24.5
      apps:
      - GitBook
      band: developing
      in_catalog: true
      kin_score: 41.7
      mcp:
        status: unchecked
      name: Arcade
      slug: arcade-software
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Automation
      - Marketing
      - Video
      tier: observed
      url: /providers/arcade-software/
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Mintlify
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://developers.notion.com/docs/mcp
        status: verified
      name: Notion
      slug: notion
      sources:
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - Collaboration
      - Database
      - Ideas
      - Notes
      tier: declared
      url: /providers/notion/
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - Mintlify
      band: strong
      in_catalog: true
      kin_score: 57.0
      mcp:
        status: none
      name: OneNote
      slug: microsoft-onenote
      sources:
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - Microsoft
      - Microsoft 365
      - Notebooks
      - Notes
      tier: declared
      url: /providers/microsoft-onenote/
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
      - Backstage
      - Mintlify
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Confluence
      slug: confluence
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - Collaboration
      - Content Management
      - Documentation
      - Knowledge Base
      tier: observed
      url: /providers/confluence/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Mintlify
      band: exemplar
      in_catalog: true
      kin_score: 70.8
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Outlook
      slug: microsoft-outlook
      sources:
      - https://www.mintlify.com/docs/automations/integrations.md
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
      - Mintlify
      band: exemplar
      in_catalog: true
      kin_score: 66.8
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: declared
      url: /providers/google-gmail/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.20
      key: AE-170.70.20
      name: Translation Management & Localization
      url: /capabilities/content-management/
      via_parent: Content Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.3
      apps:
      - ReadMe
      band: thin
      in_catalog: true
      kin_score: 35.9
      mcp:
        source: https://help.transifex.com/en/articles/15970082-transifex-mcp-server
        status: documented
      name: Transifex
      slug: transifex
      sources:
      - https://docs.readme.com/main/docs/transifex.md
      status: profiled
      tags:
      - L10n
      - Localization
      - Translation
      - i18n
      tier: declared
      url: /providers/transifex/
    - agent_band: null
      agent_readiness: null
      apps:
      - ReadMe
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Localize
      slug: localize
      sources:
      - https://docs.readme.com/main/docs/localize.md
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 13.7
      apps:
      - GitBook
      band: developing
      in_catalog: true
      kin_score: 44.3
      mcp:
        source: https://docs.toucanai.cloud/overview/which-mcp-do-i-need
        status: verified
      name: Toucan Toco
      slug: toucantoco
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Analytics
      - Business Intelligence
      - Data Visualization
      - Embedded Analytics
      tier: observed
      url: /providers/toucantoco/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - ReadMe
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://docs.readme.com/main/docs/recaptcha.md
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: declared
      url: /providers/google-recaptcha/
  - capability:
      attribution: API Evangelist extension
      id: AE-906
      key: AE-906
      name: Code Execution Sandboxes
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - GitBook
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        status: unchecked
      name: RunKit
      slug: runkit
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/runkit/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: content-management
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 55.2
      apps:
      - Mintlify
      band: developing
      in_catalog: true
      kin_score: 43.9
      mcp:
        source: https://github.com/contentful/contentful-mcp-server
        status: verified
      name: Contentful
      slug: contentful
      sources:
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - CMS
      - Content
      - Content Management
      - Headless CMS
      tier: declared
      url: /providers/contentful/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Mintlify
      band: strong
      in_catalog: true
      kin_score: 59.3
      mcp:
        status: none
      name: Clearbit
      slug: clearbit
      sources:
      - https://www.mintlify.com/docs/integrations/analytics/clearbit.md
      status: profiled
      tags:
      - B2B
      - Data Enrichment
      - Reveal
      - Sales Intelligence
      tier: declared
      url: /providers/clearbit/
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.6
      apps:
      - Mintlify
      band: exemplar
      in_catalog: true
      kin_score: 69.6
      mcp:
        status: none
      name: Amazon Route 53
      slug: amazon-route-53
      sources:
      - https://www.mintlify.com/docs/deploy/route53-cloudfront.md
      status: profiled
      tags:
      - Amazon Web Services
      - DNS
      - Domain Registration
      - Health Checks
      tier: declared
      url: /providers/amazon-route-53/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - GitBook
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: observed
      url: /providers/mailchimp/
  - capability:
      attribution: API Evangelist extension
      id: AE-905
      key: AE-905
      name: IDEs & AI Coding Assistants
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.4
      apps:
      - GitBook
      band: exemplar
      in_catalog: true
      kin_score: 74.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub Copilot
      slug: github-copilot
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Code Generation
      - Code Review
      tier: observed
      url: /providers/github-copilot/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.0
      apps:
      - Backstage
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Graph
      slug: microsoft-graph
      sources:
      - https://github.com/backstage/backstage/tree/master/plugins
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
      id: AE-230.30.20
      key: AE-230.30.20
      name: Lead Data
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 63.0
      apps:
      - GitBook
      band: exemplar
      in_catalog: true
      kin_score: 86.8
      mcp:
        source: https://github.com/Zoominfo/zoominfo-mcp-plugin
        status: verified
      name: ZoomInfo
      slug: zoominfo
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - B2B
      - B2B Data
      - Company Data
      - Contact Database
      tier: observed
      url: /providers/zoominfo/
  - capability:
      attribution: Turbo EA
      id: BC-400.50
      key: marketing-operations-management
      name: Marketing Operations Management
      url: /capabilities/marketing-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - GitBook
      band: strong
      in_catalog: true
      kin_score: 57.2
      mcp:
        status: none
      name: Marketo
      slug: marketo
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Adobe
      - Automation
      - Marketing
      - Marketing Automation
      tier: observed
      url: /providers/marketo/
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - GitBook
      band: thin
      in_catalog: true
      kin_score: 37.8
      mcp:
        status: none
      name: Formspree
      slug: formspree
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Backend
      - Email
      - Forms
      - Static Sites
      tier: observed
      url: /providers/formspree/
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
      - Mintlify
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: declared
      url: /providers/stripe/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.30
      key: AE-110.60.30
      name: Retrieval-Augmented Generation
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - GitBook
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: RunLLM
      slug: runllm
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.0
      apps:
      - Mintlify
      band: strong
      in_catalog: true
      kin_score: 55.8
      mcp:
        status: none
      name: Excel
      slug: microsoft-excel
      sources:
      - https://www.mintlify.com/docs/automations/integrations.md
      status: profiled
      tags:
      - Automation
      - Data Analysis
      - Microsoft
      - Microsoft 365
      tier: declared
      url: /providers/microsoft-excel/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.6
      apps:
      - GitBook
      band: exemplar
      in_catalog: true
      kin_score: 75.5
      mcp:
        source: https://docs.wistia.com/docs/mcp-server-guide
        status: documented
      name: Wistia
      slug: wistia
      sources:
      - https://github.com/GitbookIO/integrations/tree/main/integrations
      status: profiled
      tags:
      - Lead Generation
      - Video Analytics
      - Video Hosting
      - Video Marketing
      tier: observed
      url: /providers/wistia/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80.10
      key: AE-170.80.10
      name: Web Fonts & Typography
      url: /capabilities/design-creative-editing/
      via_parent: Design & Creative Editing
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.9
      apps:
      - ReadMe
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://github.com/adobe/cq-quickstart-mcp-server
        status: verified
      name: Adobe Fonts (Typekit)
      slug: adobe
      sources:
      - https://docs.readme.com/main/docs/typekit-key.md
      status: profiled
      tags:
      - Adobe
      - Analytics
      - E-Signature
      - Fortune 1000
      tier: declared
      url: /providers/adobe/
  layer: common
summary:
  coverage_pct: 96.7
  declared_only: 37
  distinct_providers: 122
  in_catalog: 118
  mcp:
    documented: 5
    none: 36
    unchecked: 11
    verified: 68
  mcp_verified: 68
  mean_kin_score: 61.2
  observed: 85
  queued: 4
  reference_apps: 7
title: 'Developer Docs & API Portals: application blueprint'
---
