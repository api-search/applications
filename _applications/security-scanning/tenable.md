---
app: Tenable
app_slug: tenable
app_url: https://www.tenable.com
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1040.40
  key: asset-information-management
  layer: domain
  name: Asset Information Management
  providers:
  - Armis
  - Axonius
  - Jamf
  url: /capabilities/asset-information-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-250.10.20
  key: AE-250.10.20
  layer: domain
  name: Container Registries
  providers:
  - Docker
  - JFrog
  url: /capabilities/package-registries-distribution/
  via_parent: Package Registries & Distribution
- attribution: Turbo EA
  id: BC-4210.10
  key: continuous-integration-management
  layer: domain
  name: Continuous Integration Management
  providers:
  - HashiCorp
  - Jenkins
  url: /capabilities/continuous-integration-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.60
  key: credential-security
  layer: domain
  name: Credential Security
  providers:
  - BeyondTrust
  - CyberArk
  - Delinea
  url: /capabilities/credential-security/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40.10
  key: BC-4200.40.10
  layer: domain
  name: Source Code Management
  providers:
  - GitHub
  - GitLab
  url: /capabilities/software-construction-management/
  via_parent: Software Construction Management
- attribution: Turbo EA
  id: BC-620.30
  key: threat-detection-response-management
  layer: domain
  name: Threat Detection & Response Management
  providers:
  - Anomali
  - AWS
  - Cloudflare
  - CrowdStrike
  - Fortinet
  - Google Cloud Platform
  - Google SecOps
  - Palo Alto Networks
  - Recorded Future
  - SentinelOne
  - Splunk
  - Sumo Logic
  - Swimlane
  - Tines
  - Torq
  - Zscaler
  url: /capabilities/threat-detection-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.40
  key: vulnerability-management
  layer: domain
  name: Vulnerability Management
  providers:
  - ArmorCode
  - Bitsight
  - Brinqa
  - HackerOne
  - SecurityScorecard
  - Snyk
  - Veracode
  - Wiz
  url: /capabilities/vulnerability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-130
  key: compliance-management
  layer: common
  name: Compliance Management
  providers:
  - Archer
  - Vanta
  url: /capabilities/compliance-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.30
  key: it-service-management
  layer: common
  name: IT Service Management
  providers:
  - ServiceNow
  url: /capabilities/it-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - Okta
  - Ping Identity
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Datadog
  - Elastic
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200
  key: software-product-engineering-management
  layer: common
  name: Software Product Engineering Management
  providers:
  - Atlassian (Jira)
  url: /capabilities/software-product-engineering-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
category:
  id: security-scanning
  name: Security Scanning & Vulnerability Management
  url: /applications/security-scanning/
counts:
  declared: 45
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.tenable.com/partners/technology
integrations:
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.6
    band: developing
    in_catalog: true
    kin_score: 47.6
    mcp: &id001
      source: https://www.anomali.com/llms.txt
      status: documented
    slug: anomali
    status: profiled
    tags: &id002
    - Company
    - Cybersecurity
    - Enterprise
    - Threat Intelligence
    url: /providers/anomali/
  layer: domain
  name: Anomali
  provider: anomali
  says: lists Anomali as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-130
    key: compliance-management
    name: Compliance Management
    url: /capabilities/compliance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.5
    mcp: &id003
      status: unknown
    slug: archer
    status: profiled
    tags: &id004
    - Company
    - Payments
    - Payouts
    - Stablecoins
    url: /providers/archer/
  layer: common
  name: Archer
  provider: archer
  says: lists Archer as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1040.40
    key: asset-information-management
    name: Asset Information Management
    url: /capabilities/asset-information-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.2
    band: strong
    in_catalog: true
    kin_score: 55.9
    mcp: &id005
      source: https://github.com/ArmisSecurity/armis-appsec-mcp
      status: verified
    slug: armis
    status: profiled
    tags: &id006
    - Company
    - Cybersecurity
    - Defense Government
    - Security
    url: /providers/armis/
  layer: domain
  name: Armis
  provider: armis
  says: lists Armis as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.40
    key: vulnerability-management
    name: Vulnerability Management
    url: /capabilities/vulnerability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: thin
    in_catalog: true
    kin_score: 32.2
    mcp: &id007
      source: https://app.armorcode.com/mcp
      status: verified
    slug: armorcode
    status: profiled
    tags: &id008
    - Application Security
    - Company
    - Security
    - Vulnerability Management
    url: /providers/armorcode/
  layer: domain
  name: ArmorCode
  provider: armorcode
  says: lists ArmorCode as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
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
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id009
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id010
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: common
  name: Atlassian (Jira)
  provider: jira
  says: lists Atlassian (Jira) as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id011
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id012
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: domain
  name: AWS
  provider: amazon-web-services
  says: lists AWS as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1040.40
    key: asset-information-management
    name: Asset Information Management
    url: /capabilities/asset-information-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.2
    band: developing
    in_catalog: true
    kin_score: 48.4
    mcp: &id013
      source: https://docs.axonius.com/docs/axonius-mcp-server
      status: verified
    slug: axonius
    status: profiled
    tags: &id014
    - Asset Management
    - Cybersecurity
    - SaaS Management
    - SaaS Security
    url: /providers/axonius/
  layer: domain
  name: Axonius
  provider: axonius
  says: lists Axonius as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.60
    key: credential-security
    name: Credential Security
    url: /capabilities/credential-security/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.4
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id015
      source: https://docs.beyondtrust.com/bt-docs/docs/mcp-server-details
      status: verified
    slug: beyondtrust
    status: profiled
    tags: &id016
    - Access
    - Compliance
    - Credentials
    - Identity and Access Management
    url: /providers/beyondtrust/
  layer: domain
  name: BeyondTrust
  provider: beyondtrust
  says: lists BeyondTrust as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.40
    key: vulnerability-management
    name: Vulnerability Management
    url: /capabilities/vulnerability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.4
    band: thin
    in_catalog: true
    kin_score: 34.4
    mcp: &id017
      status: unknown
    slug: bitsight
    status: profiled
    tags: &id018
    - Company
    - Cyber Risk
    - Security
    - Security Ratings
    url: /providers/bitsight/
  layer: domain
  name: Bitsight
  provider: bitsight
  says: lists Bitsight as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.40
    key: vulnerability-management
    name: Vulnerability Management
    url: /capabilities/vulnerability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.3
    band: emerging
    in_catalog: true
    kin_score: 24.7
    mcp: &id019
      source: https://docs.brinqa.com/docs/brinqa-iq-mcp
      status: verified
    slug: brinqa
    status: profiled
    tags: &id020
    - Company
    - Cybersecurity
    - Exposure Management
    - Vulnerability Management
    url: /providers/brinqa/
  layer: domain
  name: Brinqa
  provider: brinqa
  says: lists Brinqa as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 69.4
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id021
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id022
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
  layer: domain
  name: Cloudflare
  provider: cloudflare
  says: lists Cloudflare as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.4
    band: exemplar
    in_catalog: true
    kin_score: 67.2
    mcp: &id023
      source: https://github.com/CrowdStrike/falcon-mcp
      status: verified
    slug: crowdstrike
    status: profiled
    tags: &id024
    - Cybersecurity
    - Endpoint Detection and Response
    - Endpoint Security
    - Threat Intelligence
    url: /providers/crowdstrike/
  layer: domain
  name: CrowdStrike
  provider: crowdstrike
  says: lists CrowdStrike as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.60
    key: credential-security
    name: Credential Security
    url: /capabilities/credential-security/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.8
    band: thin
    in_catalog: true
    kin_score: 32.4
    mcp: &id025
      source: https://lp.cyberark.com/sca-mcp.html
      status: verified
    slug: cyberark
    status: profiled
    tags: &id026
    - Authentication
    - Cloud Security
    - Conjur
    - Credential Vault
    url: /providers/cyberark/
  layer: domain
  name: CyberArk
  provider: cyberark
  says: lists CyberArk as an integration
  source: https://www.tenable.com/partners/technology
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
    mcp: &id027
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id028
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: common
  name: Datadog
  provider: datadog
  says: lists Datadog as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.60
    key: credential-security
    name: Credential Security
    url: /capabilities/credential-security/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.3
    band: exemplar
    in_catalog: true
    kin_score: 68.6
    mcp: &id029
      source: https://github.com/DelineaXPM/delinea-mcp
      status: verified
    slug: delinea
    status: profiled
    tags: &id030
    - DevOps
    - Identity Security
    - Privileged Access Management
    - Secrets Management
    url: /providers/delinea/
  layer: domain
  name: Delinea
  provider: delinea
  says: lists Delinea as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.4
    band: developing
    in_catalog: true
    kin_score: 51.7
    mcp: &id031
      source: https://github.com/docker/mcp-gateway
      status: verified
    slug: docker
    status: profiled
    tags: &id032
    - Cloud
    - Containers
    - DevOps
    - Developer Tools
    url: /providers/docker/
  layer: domain
  name: Docker
  provider: docker
  says: lists Docker as an integration
  source: https://www.tenable.com/partners/technology
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
    agent_readiness: 28.5
    band: exemplar
    in_catalog: true
    kin_score: 78.4
    mcp: &id033
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id034
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
  layer: common
  name: Elastic
  provider: elastic
  says: lists Elastic as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: thin
    in_catalog: true
    kin_score: 26.5
    mcp: &id035
      status: none
    slug: fortinet
    status: profiled
    tags: &id036
    - Cloud Security
    - Cybersecurity
    - Firewall
    - Networking
    url: /providers/fortinet/
  layer: domain
  name: Fortinet
  provider: fortinet
  says: lists Fortinet as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.40.10
    key: BC-4200.40.10
    name: Source Code Management
    url: /capabilities/software-construction-management/
    via_parent: Software Construction Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id037
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id038
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.40.10
    key: BC-4200.40.10
    name: Source Code Management
    url: /capabilities/software-construction-management/
    via_parent: Software Construction Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id039
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id040
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: lists GitLab as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 67.5
    mcp: &id041
      source: https://github.com/googleapis/mcp-toolbox
      status: verified
    slug: google-cloud-platform
    status: profiled
    tags: &id042
    - API Management
    - Cloud Computing
    - Infrastructure
    - Platform-as-a-Service
    url: /providers/google-cloud-platform/
  layer: domain
  name: Google Cloud Platform
  provider: google-cloud-platform
  says: lists Google Cloud Platform as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id043
      status: unchecked
    slug: google-secops
    status: queued for profiling
    tags: &id044 []
    url: null
  layer: domain
  name: Google SecOps
  provider: google-secops
  says: lists Google SecOps as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.40
    key: vulnerability-management
    name: Vulnerability Management
    url: /capabilities/vulnerability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.0
    band: minimal
    in_catalog: true
    kin_score: 5.5
    mcp: &id045
      source: https://github.com/Hacker0x01/hackerone-graphql-mcp-server
      status: verified
    slug: hackerone
    status: profiled
    tags: &id046
    - Cybersecurity
    - Public APIs
    - Security
    - Vulnerability Management
    url: /providers/hackerone/
  layer: domain
  name: HackerOne
  provider: hackerone
  says: lists HackerOne as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.10
    key: continuous-integration-management
    name: Continuous Integration Management
    url: /capabilities/continuous-integration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.8
    band: thin
    in_catalog: true
    kin_score: 29.4
    mcp: &id047
      source: https://github.com/hashicorp/terraform-mcp-server
      status: verified
    slug: hashicorp
    status: profiled
    tags: &id048
    - Cloud
    - DevOps
    - Infrastructure
    - Platform
    url: /providers/hashicorp/
  layer: domain
  name: HashiCorp
  provider: hashicorp
  says: lists HashiCorp as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1040.40
    key: asset-information-management
    name: Asset Information Management
    url: /capabilities/asset-information-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.3
    band: strong
    in_catalog: true
    kin_score: 60.5
    mcp: &id049
      status: none
    slug: jamf
    status: profiled
    tags: &id050
    - Apple Device Management
    - Company
    - Endpoint Security
    - MDM
    url: /providers/jamf/
  layer: domain
  name: Jamf
  provider: jamf
  says: lists Jamf as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.10
    key: continuous-integration-management
    name: Continuous Integration Management
    url: /capabilities/continuous-integration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.5
    band: thin
    in_catalog: true
    kin_score: 39.0
    mcp: &id051
      source: https://github.com/jenkinsci/mcp-server-plugin
      status: verified
    slug: jenkins
    status: profiled
    tags: &id052
    - Automation
    - Build Server
    - CI/CD
    - Continuous Delivery
    url: /providers/jenkins/
  layer: domain
  name: Jenkins
  provider: jenkins
  says: lists Jenkins as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.1
    band: exemplar
    in_catalog: true
    kin_score: 76.8
    mcp: &id053
      source: https://github.com/jfrog/jfrog-mcp-server
      status: verified
    slug: jfrog
    status: profiled
    tags: &id054
    - Artifactory
    - CI/CD
    - Container Registry
    - Developer Tools
    url: /providers/jfrog/
  layer: domain
  name: JFrog
  provider: jfrog
  says: lists JFrog as an integration
  source: https://www.tenable.com/partners/technology
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
    mcp: &id055
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id056
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: common
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.5
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id057
      source: https://github.com/PaloAltoNetworks/prisma-airs-mcp
      status: verified
    slug: palo-alto-networks
    status: profiled
    tags: &id058
    - Cloud Security
    - Cybersecurity
    - Firewall
    - Network Security
    url: /providers/palo-alto-networks/
  layer: domain
  name: Palo Alto Networks
  provider: palo-alto-networks
  says: lists Palo Alto Networks as an integration
  source: https://www.tenable.com/partners/technology
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
    mcp: &id059
      source: https://github.com/pingidentity/pingone-mcp-server
      status: verified
    slug: ping-identity
    status: profiled
    tags: &id060
    - Authentication
    - Authorization
    - Identity
    - SSO
    url: /providers/ping-identity/
  layer: common
  name: Ping Identity
  provider: ping-identity
  says: lists Ping Identity as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 57.7
    band: exemplar
    in_catalog: true
    kin_score: 71.6
    mcp: &id061
      source: https://mcp.recordedfuture.com/mcp
      status: verified
    slug: recorded-future
    status: profiled
    tags: &id062
    - Brand Intelligence
    - Cybersecurity
    - Intelligence Cloud
    - Threat Intelligence
    url: /providers/recorded-future/
  layer: domain
  name: Recorded Future
  provider: recorded-future
  says: lists Recorded Future as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.40
    key: vulnerability-management
    name: Vulnerability Management
    url: /capabilities/vulnerability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id063
      status: unchecked
    slug: securityscorecard
    status: queued for profiling
    tags: &id064 []
    url: null
  layer: domain
  name: SecurityScorecard
  provider: securityscorecard
  says: lists SecurityScorecard as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 22.0
    mcp: &id065
      source: https://github.com/Sentinel-One/purple-mcp
      status: verified
    slug: sentinelone
    status: profiled
    tags: &id066
    - Endpoint Detection and Response
    - Endpoint Security
    - Security
    - XDR
    url: /providers/sentinelone/
  layer: domain
  name: SentinelOne
  provider: sentinelone
  says: lists SentinelOne as an integration
  source: https://www.tenable.com/partners/technology
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
    mcp: &id067
      status: none
    slug: servicenow
    status: profiled
    tags: &id068
    - Automation
    - Cloud Services
    - Digital Workflows
    - ServiceNow
    url: /providers/servicenow/
  layer: common
  name: ServiceNow
  provider: servicenow
  says: lists ServiceNow as an integration
  source: https://www.tenable.com/partners/technology
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
    mcp: &id069
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id070
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.40
    key: vulnerability-management
    name: Vulnerability Management
    url: /capabilities/vulnerability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.8
    band: exemplar
    in_catalog: true
    kin_score: 80.8
    mcp: &id071
      source: https://github.com/snyk/studio-mcp
      status: verified
    slug: snyk
    status: profiled
    tags: &id072
    - Application Security
    - DevSecOps
    - Security
    - Vulnerability Management
    url: /providers/snyk/
  layer: domain
  name: Snyk
  provider: snyk
  says: lists Snyk as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.4
    band: strong
    in_catalog: true
    kin_score: 63.1
    mcp: &id073
      status: none
    slug: splunk
    status: profiled
    tags: &id074
    - Analytics
    - Data Analysis
    - Logging
    - Machine Data
    url: /providers/splunk/
  layer: domain
  name: Splunk
  provider: splunk
  says: lists Splunk as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.2
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id075
      source: https://docs.sumologic.com/docs/search/mobot/
      status: documented
    slug: sumo-logic
    status: profiled
    tags: &id076
    - Logging
    - Monitoring
    - Observability
    - Security
    url: /providers/sumo-logic/
  layer: domain
  name: Sumo Logic
  provider: sumo-logic
  says: lists Sumo Logic as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.4
    band: thin
    in_catalog: true
    kin_score: 32.9
    mcp: &id077
      source: https://mcp.swimlane.com/mcp
      status: verified
    slug: swimlane
    status: profiled
    tags: &id078
    - Automation
    - Incident Response
    - SOAR
    - Security Orchestration
    url: /providers/swimlane/
  layer: domain
  name: Swimlane
  provider: swimlane
  says: lists Swimlane as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.0
    band: thin
    in_catalog: true
    kin_score: 37.0
    mcp: &id079
      source: https://www.tines.com/docs/mcp-server/
      status: verified
    slug: tines
    status: profiled
    tags: &id080
    - No-Code
    - Security Automation
    - Security Operations
    - Workflow Automation
    url: /providers/tines/
  layer: domain
  name: Tines
  provider: tines
  says: lists Tines as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 13.3
    band: emerging
    in_catalog: true
    kin_score: 22.6
    mcp: &id081
      source: https://torq.io/blog/model-context-protocol
      status: documented
    slug: torq
    status: profiled
    tags: &id082
    - Hyper-Automation
    - SOAR
    - Security Automation
    - Security Orchestration
    url: /providers/torq/
  layer: domain
  name: Torq
  provider: torq
  says: lists Torq as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-130
    key: compliance-management
    name: Compliance Management
    url: /capabilities/compliance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.6
    band: developing
    in_catalog: true
    kin_score: 47.9
    mcp: &id083
      source: https://github.com/VantaInc/vanta-mcp-server
      status: verified
    slug: vanta
    status: profiled
    tags: &id084
    - Compliance
    - Cybersecurity
    - Governance
    - Security
    url: /providers/vanta/
  layer: common
  name: Vanta
  provider: vanta
  says: lists Vanta as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.40
    key: vulnerability-management
    name: Vulnerability Management
    url: /capabilities/vulnerability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.4
    band: strong
    in_catalog: true
    kin_score: 58.3
    mcp: &id085
      status: none
    slug: veracode
    status: profiled
    tags: &id086
    - Application Security
    - DAST
    - SAST
    - Software Composition Analysis
    url: /providers/veracode/
  layer: domain
  name: Veracode
  provider: veracode
  says: lists Veracode as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.40
    key: vulnerability-management
    name: Vulnerability Management
    url: /capabilities/vulnerability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.3
    mcp: &id087
      source: https://www.wiz.io/blog/introducing-mcp-server-for-wiz
      status: verified
    slug: wiz
    status: profiled
    tags: &id088
    - CNAPP
    - CSPM
    - Cloud Security
    - Vulnerability Management
    url: /providers/wiz/
  layer: domain
  name: Wiz
  provider: wiz
  says: lists Wiz as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.6
    band: thin
    in_catalog: true
    kin_score: 34.6
    mcp: &id089
      source: https://github.com/zscaler/zscaler-mcp-server
      status: verified
    slug: zscaler
    status: profiled
    tags: &id090
    - Cloud Security
    - Network Security
    - SASE
    - Zero Trust
    url: /providers/zscaler/
  layer: domain
  name: Zscaler
  provider: zscaler
  says: lists Zscaler as an integration
  source: https://www.tenable.com/partners/technology
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/security-scanning/tenable/
providers:
- agent_band: agent-ready
  agent_readiness: 40.6
  band: developing
  in_catalog: true
  kin_score: 47.6
  mcp: *id001
  name: Anomali
  slug: anomali
  status: profiled
  tags: *id002
  url: /providers/anomali/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.5
  mcp: *id003
  name: Archer
  slug: archer
  status: profiled
  tags: *id004
  url: /providers/archer/
- agent_band: agent-ready
  agent_readiness: 48.2
  band: strong
  in_catalog: true
  kin_score: 55.9
  mcp: *id005
  name: Armis
  slug: armis
  status: profiled
  tags: *id006
  url: /providers/armis/
- agent_band: human-only
  agent_readiness: 2.5
  band: thin
  in_catalog: true
  kin_score: 32.2
  mcp: *id007
  name: ArmorCode
  slug: armorcode
  status: profiled
  tags: *id008
  url: /providers/armorcode/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id009
  name: Atlassian (Jira)
  slug: jira
  status: profiled
  tags: *id010
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id011
  name: AWS
  slug: amazon-web-services
  status: profiled
  tags: *id012
  url: /providers/amazon-web-services/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 48.4
  mcp: *id013
  name: Axonius
  slug: axonius
  status: profiled
  tags: *id014
  url: /providers/axonius/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id015
  name: BeyondTrust
  slug: beyondtrust
  status: profiled
  tags: *id016
  url: /providers/beyondtrust/
- agent_band: agent-aware
  agent_readiness: 14.4
  band: thin
  in_catalog: true
  kin_score: 34.4
  mcp: *id017
  name: Bitsight
  slug: bitsight
  status: profiled
  tags: *id018
  url: /providers/bitsight/
- agent_band: agent-aware
  agent_readiness: 5.3
  band: emerging
  in_catalog: true
  kin_score: 24.7
  mcp: *id019
  name: Brinqa
  slug: brinqa
  status: profiled
  tags: *id020
  url: /providers/brinqa/
- agent_band: agent-native
  agent_readiness: 69.4
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id021
  name: Cloudflare
  slug: cloudflare
  status: profiled
  tags: *id022
  url: /providers/cloudflare/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id023
  name: CrowdStrike
  slug: crowdstrike
  status: profiled
  tags: *id024
  url: /providers/crowdstrike/
- agent_band: agent-aware
  agent_readiness: 18.8
  band: thin
  in_catalog: true
  kin_score: 32.4
  mcp: *id025
  name: CyberArk
  slug: cyberark
  status: profiled
  tags: *id026
  url: /providers/cyberark/
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id027
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id028
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 46.3
  band: exemplar
  in_catalog: true
  kin_score: 68.6
  mcp: *id029
  name: Delinea
  slug: delinea
  status: profiled
  tags: *id030
  url: /providers/delinea/
- agent_band: agent-ready
  agent_readiness: 32.4
  band: developing
  in_catalog: true
  kin_score: 51.7
  mcp: *id031
  name: Docker
  slug: docker
  status: profiled
  tags: *id032
  url: /providers/docker/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id033
  name: Elastic
  slug: elastic
  status: profiled
  tags: *id034
  url: /providers/elastic/
- agent_band: human-only
  agent_readiness: 0.6
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id035
  name: Fortinet
  slug: fortinet
  status: profiled
  tags: *id036
  url: /providers/fortinet/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id037
  name: GitHub
  slug: github
  status: profiled
  tags: *id038
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id039
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id040
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 67.5
  mcp: *id041
  name: Google Cloud Platform
  slug: google-cloud-platform
  status: profiled
  tags: *id042
  url: /providers/google-cloud-platform/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id043
  name: Google SecOps
  slug: google-secops
  status: queued for profiling
  tags: *id044
  url: null
- agent_band: agent-aware
  agent_readiness: 12.0
  band: minimal
  in_catalog: true
  kin_score: 5.5
  mcp: *id045
  name: HackerOne
  slug: hackerone
  status: profiled
  tags: *id046
  url: /providers/hackerone/
- agent_band: agent-aware
  agent_readiness: 18.8
  band: thin
  in_catalog: true
  kin_score: 29.4
  mcp: *id047
  name: HashiCorp
  slug: hashicorp
  status: profiled
  tags: *id048
  url: /providers/hashicorp/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: strong
  in_catalog: true
  kin_score: 60.5
  mcp: *id049
  name: Jamf
  slug: jamf
  status: profiled
  tags: *id050
  url: /providers/jamf/
- agent_band: agent-aware
  agent_readiness: 22.5
  band: thin
  in_catalog: true
  kin_score: 39.0
  mcp: *id051
  name: Jenkins
  slug: jenkins
  status: profiled
  tags: *id052
  url: /providers/jenkins/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: exemplar
  in_catalog: true
  kin_score: 76.8
  mcp: *id053
  name: JFrog
  slug: jfrog
  status: profiled
  tags: *id054
  url: /providers/jfrog/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id055
  name: Okta
  slug: okta
  status: profiled
  tags: *id056
  url: /providers/okta/
- agent_band: agent-ready
  agent_readiness: 38.5
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id057
  name: Palo Alto Networks
  slug: palo-alto-networks
  status: profiled
  tags: *id058
  url: /providers/palo-alto-networks/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: strong
  in_catalog: true
  kin_score: 55.9
  mcp: *id059
  name: Ping Identity
  slug: ping-identity
  status: profiled
  tags: *id060
  url: /providers/ping-identity/
- agent_band: agent-ready
  agent_readiness: 57.7
  band: exemplar
  in_catalog: true
  kin_score: 71.6
  mcp: *id061
  name: Recorded Future
  slug: recorded-future
  status: profiled
  tags: *id062
  url: /providers/recorded-future/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id063
  name: SecurityScorecard
  slug: securityscorecard
  status: queued for profiling
  tags: *id064
  url: null
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 22.0
  mcp: *id065
  name: SentinelOne
  slug: sentinelone
  status: profiled
  tags: *id066
  url: /providers/sentinelone/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: strong
  in_catalog: true
  kin_score: 61.9
  mcp: *id067
  name: ServiceNow
  slug: servicenow
  status: profiled
  tags: *id068
  url: /providers/servicenow/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id069
  name: Slack
  slug: slack
  status: profiled
  tags: *id070
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: exemplar
  in_catalog: true
  kin_score: 80.8
  mcp: *id071
  name: Snyk
  slug: snyk
  status: profiled
  tags: *id072
  url: /providers/snyk/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id073
  name: Splunk
  slug: splunk
  status: profiled
  tags: *id074
  url: /providers/splunk/
- agent_band: agent-ready
  agent_readiness: 48.2
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id075
  name: Sumo Logic
  slug: sumo-logic
  status: profiled
  tags: *id076
  url: /providers/sumo-logic/
- agent_band: agent-aware
  agent_readiness: 21.4
  band: thin
  in_catalog: true
  kin_score: 32.9
  mcp: *id077
  name: Swimlane
  slug: swimlane
  status: profiled
  tags: *id078
  url: /providers/swimlane/
- agent_band: agent-ready
  agent_readiness: 29.0
  band: thin
  in_catalog: true
  kin_score: 37.0
  mcp: *id079
  name: Tines
  slug: tines
  status: profiled
  tags: *id080
  url: /providers/tines/
- agent_band: agent-aware
  agent_readiness: 13.3
  band: emerging
  in_catalog: true
  kin_score: 22.6
  mcp: *id081
  name: Torq
  slug: torq
  status: profiled
  tags: *id082
  url: /providers/torq/
- agent_band: agent-ready
  agent_readiness: 43.6
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id083
  name: Vanta
  slug: vanta
  status: profiled
  tags: *id084
  url: /providers/vanta/
- agent_band: agent-ready
  agent_readiness: 29.4
  band: strong
  in_catalog: true
  kin_score: 58.3
  mcp: *id085
  name: Veracode
  slug: veracode
  status: profiled
  tags: *id086
  url: /providers/veracode/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.3
  mcp: *id087
  name: Wiz
  slug: wiz
  status: profiled
  tags: *id088
  url: /providers/wiz/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: thin
  in_catalog: true
  kin_score: 34.6
  mcp: *id089
  name: Zscaler
  slug: zscaler
  status: profiled
  tags: *id090
  url: /providers/zscaler/
siblings:
- name: DefectDojo
  rows: 11
  url: /applications/security-scanning/defectdojo/
- name: Nuclei
  rows: 18
  url: /applications/security-scanning/nuclei/
- name: OWASP Dependency-Track
  rows: 22
  url: /applications/security-scanning/owasp-dependency-track/
- name: Snyk
  rows: 27
  url: /applications/security-scanning/snyk/
- name: Trivy
  rows: 4
  url: /applications/security-scanning/trivy/
- name: Wazuh
  rows: 17
  url: /applications/security-scanning/wazuh/
sitemap: true
title: 'Tenable: Security Scanning & Vulnerability Management reference app'
---
