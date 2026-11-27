---
app: CircleCI
app_slug: circleci
app_url: https://circleci.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4210.60
  key: configuration-secrets-management
  layer: domain
  name: Configuration & Secrets Management
  providers:
  - Fortanix
  url: /capabilities/configuration-secrets-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210.50
  key: BC-4210.50
  layer: domain
  name: Feature Flag Management
  providers:
  - ConfigCat
  url: /capabilities/feature-flag-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-130.10
  key: regulatory-compliance-management
  layer: domain
  name: Regulatory Compliance Management
  providers:
  - Anecdotes
  url: /capabilities/regulatory-compliance-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210.30
  key: release-engineering-management
  layer: domain
  name: Release Engineering Management
  providers:
  - Amazon ECR
  - Cloudsmith
  - Google Cloud GCR
  - packagecloud
  - Sonatype
  url: /capabilities/release-engineering-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.50
  key: software-quality-engineering
  layer: domain
  name: Software Quality Engineering
  providers:
  - Codecov
  - CodeScene
  - Coveralls
  - datree policy
  - Packtracker
  - realMethods
  - SonarSource
  url: /capabilities/software-quality-engineering/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: domain
  name: Storage Management
  providers:
  - Amazon S3
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-620.40
  key: vulnerability-management
  layer: domain
  name: Vulnerability Management
  providers:
  - Alcide.io
  - Anchore
  - Aqua Security
  - CheckMarx
  - Contrast
  - DeepFactor
  - Fossa
  - GitGuardian
  - Indeni
  - Lacework
  - Lightspin
  - NeuVector
  - Nightfall
  - Prisma Cloud
  - Probely
  - Rezilion
  - Shiftleft (now Qwiet AI)
  - Sken.ai
  - Snyk
  - SOOS
  - Spectral (SpectralOps, Check Point)
  - StackHawk
  - Wallarm
  - WhiteSource (now Mend)
  url: /capabilities/vulnerability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.30
  key: incident-response-management
  layer: common
  name: Incident Response Management
  providers:
  - OpsGenie
  - Squadcast
  - xMatters
  url: /capabilities/incident-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Coralogix
  - Datadog
  - Honeybadger
  - Honeycomb
  - LogDNA (now Mezmo)
  - Logz.io
  - New Relic
  - Rollbar
  - Thundra
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: ci-cd-devops
  name: Code Hosting, CI/CD & DevOps
  url: /applications/ci-cd-devops/
counts:
  declared: 54
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://circleci.com/integrations/
integrations:
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
    mcp: &id001
      status: unchecked
    slug: alcide
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: domain
  name: Alcide.io
  provider: alcide
  says: lists Alcide.io as an integration
  source: https://circleci.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.30
    key: release-engineering-management
    name: Release Engineering Management
    url: /capabilities/release-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.5
    band: exemplar
    in_catalog: true
    kin_score: 75.2
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-ecr
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Container Images
    - Container Registry
    - Containers
    url: /providers/amazon-ecr/
  layer: domain
  name: Amazon ECR
  provider: amazon-ecr
  says: lists Amazon ECR as an integration
  source: https://circleci.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: domain
  name: Amazon S3
  provider: amazon-s3
  says: lists Amazon S3 as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 21.5
    band: thin
    in_catalog: true
    kin_score: 35.8
    mcp: &id007
      source: https://github.com/anchore/grype-mcp
      status: verified
    slug: anchore
    status: profiled
    tags: &id008
    - Container Security
    - Containers
    - SBOM
    - Software Supply Chain
    url: /providers/anchore/
  layer: domain
  name: Anchore
  provider: anchore
  says: lists Anchore as an integration
  source: https://circleci.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-130.10
    key: regulatory-compliance-management
    name: Regulatory Compliance Management
    url: /capabilities/regulatory-compliance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 69.5
    mcp: &id009
      status: none
    slug: anecdotes
    status: profiled
    tags: &id010
    - Company
    - Compliance
    - Governance
    - Risk Management
    url: /providers/anecdotes/
  layer: domain
  name: Anecdotes
  provider: anecdotes
  says: lists Anecdotes as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 40.1
    mcp: &id011
      source: https://github.com/aquasecurity/trivy-mcp
      status: verified
    slug: aqua-security
    status: profiled
    tags: &id012
    - Cloud-Native
    - Containers
    - Kubernetes
    - Runtime Protection
    url: /providers/aqua-security/
  layer: domain
  name: Aqua Security
  provider: aqua-security
  says: lists Aqua Security as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 38.4
    band: strong
    in_catalog: true
    kin_score: 62.1
    mcp: &id013
      source: https://github.com/Checkmarx/cx-agentic-ai
      status: verified
    slug: checkmarx
    status: profiled
    tags: &id014
    - Application Security
    - Code Analysis
    - DevSecOps
    - SAST
    url: /providers/checkmarx/
  layer: domain
  name: CheckMarx
  provider: checkmarx
  says: lists CheckMarx as an integration
  source: https://circleci.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.30
    key: release-engineering-management
    name: Release Engineering Management
    url: /capabilities/release-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.3
    band: thin
    in_catalog: true
    kin_score: 32.0
    mcp: &id015
      source: https://docs.cloudsmith.com/integrations/integrating-with-mcp
      status: verified
    slug: cloudsmith
    status: profiled
    tags: &id016
    - Artifact Management
    - DevOps
    - DevSecOps
    - Developer Tools
    url: /providers/cloudsmith/
  layer: domain
  name: Cloudsmith
  provider: cloudsmith
  says: lists Cloudsmith as an integration
  source: https://circleci.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.50
    key: software-quality-engineering
    name: Software Quality Engineering
    url: /capabilities/software-quality-engineering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.3
    band: strong
    in_catalog: true
    kin_score: 59.7
    mcp: &id017
      status: none
    slug: codecov
    status: profiled
    tags: &id018
    - CI/CD
    - Code Coverage
    - Company
    - DevOps
    url: /providers/codecov/
  layer: domain
  name: Codecov
  provider: codecov
  says: lists Codecov as an integration
  source: https://circleci.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.50
    key: software-quality-engineering
    name: Software Quality Engineering
    url: /capabilities/software-quality-engineering/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 1.8
    band: thin
    in_catalog: true
    kin_score: 26.2
    mcp: &id019
      source: https://github.com/codescene-oss/codescene-mcp-server
      status: verified
    slug: codescene
    status: profiled
    tags: &id020
    - Artificial Intelligence
    - Code Analysis
    - Company
    - Technical Debt
    url: /providers/codescene/
  layer: domain
  name: CodeScene
  provider: codescene
  says: lists CodeScene as an integration
  source: https://circleci.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: BC-4210.50
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.7
    band: developing
    in_catalog: true
    kin_score: 43.2
    mcp: &id021
      source: https://github.com/configcat/mcp-server
      status: verified
    slug: configcat
    status: profiled
    tags: &id022
    - Cloud
    - Developer Tools
    - Feature-Flag
    - Software-as-a-Service
    url: /providers/configcat/
  layer: domain
  name: ConfigCat
  provider: configcat
  says: lists ConfigCat as an integration
  source: https://circleci.com/integrations/
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
    agent_band: agent-native
    agent_readiness: 59.2
    band: strong
    in_catalog: true
    kin_score: 60.7
    mcp: &id023
      source: https://github.com/Contrast-Security-OSS/mcp-contrast
      status: verified
    slug: contrast-security
    status: profiled
    tags: &id024
    - AppSec
    - Application Security
    - IAST
    - RASP
    url: /providers/contrast-security/
  layer: domain
  name: Contrast
  provider: contrast-security
  says: lists Contrast as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 43.6
    band: exemplar
    in_catalog: true
    kin_score: 66.8
    mcp: &id025
      source: https://coralogix.com/docs/user-guides/mcp-server/overview/
      status: verified
    slug: coralogix
    status: profiled
    tags: &id026
    - AIOps
    - Cloud
    - Monitoring
    - Observability
    url: /providers/coralogix/
  layer: common
  name: Coralogix
  provider: coralogix
  says: lists Coralogix as an integration
  source: https://circleci.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.50
    key: software-quality-engineering
    name: Software Quality Engineering
    url: /capabilities/software-quality-engineering/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id027
      status: unknown
    slug: coveralls
    status: profiled
    tags: &id028
    - CI Integration
    - Code Coverage
    - Company
    - Open Source
    url: /providers/coveralls/
  layer: domain
  name: Coveralls
  provider: coveralls
  says: lists Coveralls as an integration
  source: https://circleci.com/integrations/
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
    mcp: &id029
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id030
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: common
  name: Datadog
  provider: datadog
  says: lists Datadog as an integration
  source: https://circleci.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.50
    key: software-quality-engineering
    name: Software Quality Engineering
    url: /capabilities/software-quality-engineering/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id031
      status: unchecked
    slug: datree
    status: queued for profiling
    tags: &id032 []
    url: null
  layer: domain
  name: datree policy
  provider: datree
  says: lists datree policy as an integration
  source: https://circleci.com/integrations/
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
    band: minimal
    in_catalog: true
    kin_score: 0.0
    mcp: &id033
      status: none
    slug: deepfactor
    status: profiled
    tags: &id034
    - Application Security
    - Company
    - Cybersecurity
    - DevSecOps
    url: /providers/deepfactor/
  layer: domain
  name: DeepFactor
  provider: deepfactor
  says: lists DeepFactor as an integration
  source: https://circleci.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.2
    band: developing
    in_catalog: true
    kin_score: 53.5
    mcp: &id035
      status: none
    slug: fortanix
    status: profiled
    tags: &id036
    - Company
    - Encryption
    - Key Management
    - Security
    url: /providers/fortanix/
  layer: domain
  name: Fortanix
  provider: fortanix
  says: lists Fortanix as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 22.2
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id037
      status: none
    slug: fossa
    status: profiled
    tags: &id038
    - Company
    - Open Source
    - Security
    - Software Supply Chain
    url: /providers/fossa/
  layer: domain
  name: Fossa
  provider: fossa
  says: lists Fossa as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 13.0
    band: minimal
    in_catalog: true
    kin_score: 6.2
    mcp: &id039
      source: https://github.com/GitGuardian/ggmcp
      status: verified
    slug: gitguardian
    status: profiled
    tags: &id040
    - Public APIs
    - Security
    url: /providers/gitguardian/
  layer: domain
  name: GitGuardian
  provider: gitguardian
  says: lists GitGuardian as an integration
  source: https://circleci.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.30
    key: release-engineering-management
    name: Release Engineering Management
    url: /capabilities/release-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.7
    band: strong
    in_catalog: true
    kin_score: 65.4
    mcp: &id041
      status: none
    slug: google-artifact-registry
    status: profiled
    tags: &id042
    - Artifacts
    - Containers
    - Google Cloud
    - Packages
    url: /providers/google-artifact-registry/
  layer: domain
  name: Google Cloud GCR
  provider: google-artifact-registry
  says: lists Google Cloud GCR as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 43.4
    band: thin
    in_catalog: true
    kin_score: 33.4
    mcp: &id043
      source: https://github.com/honeybadger-io/honeybadger-mcp-server
      status: verified
    slug: honeybadger
    status: profiled
    tags: &id044
    - Application Performance Monitoring
    - Error Monitoring
    - Exception Tracking
    - Uptime Monitoring
    url: /providers/honeybadger/
  layer: common
  name: Honeybadger
  provider: honeybadger
  says: lists Honeybadger as an integration
  source: https://circleci.com/integrations/
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
    mcp: &id045
      source: https://docs.honeycomb.io/integrations/mcp/
      status: verified
    slug: honeycomb
    status: profiled
    tags: &id046
    - Analytics
    - Data Management
    - Observability
    - Telemetry
    url: /providers/honeycomb/
  layer: common
  name: Honeycomb
  provider: honeycomb
  says: lists Honeycomb as an integration
  source: https://circleci.com/integrations/
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
    mcp: &id047
      status: unchecked
    slug: indeni
    status: queued for profiling
    tags: &id048 []
    url: null
  layer: domain
  name: Indeni
  provider: indeni
  says: lists Indeni as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 15.1
    band: emerging
    in_catalog: true
    kin_score: 22.7
    mcp: &id049
      status: none
    slug: lacework
    status: profiled
    tags: &id050
    - CNAPP
    - Cloud Security
    - Compliance
    - Threat Detection
    url: /providers/lacework/
  layer: domain
  name: Lacework
  provider: lacework
  says: lists Lacework as an integration
  source: https://circleci.com/integrations/
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
    mcp: &id051
      status: unchecked
    slug: lightspin
    status: queued for profiling
    tags: &id052 []
    url: null
  layer: domain
  name: Lightspin
  provider: lightspin
  says: lists Lightspin as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 27.1
    band: developing
    in_catalog: true
    kin_score: 43.4
    mcp: &id053
      source: https://github.com/mezmo/mezmo-mcp
      status: verified
    slug: mezmo
    status: profiled
    tags: &id054
    - Logs
    - Observability
    - Telemetry
    - Telemetry Pipeline
    url: /providers/mezmo/
  layer: common
  name: LogDNA (now Mezmo)
  provider: mezmo
  says: lists LogDNA (now Mezmo) as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 25.9
    band: strong
    in_catalog: true
    kin_score: 63.3
    mcp: &id055
      status: none
    slug: logz-io
    status: profiled
    tags: &id056
    - Logging
    - Metrics
    - Observability
    - Tracing
    url: /providers/logz-io/
  layer: common
  name: Logz.io
  provider: logz-io
  says: lists Logz.io as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 23.6
    band: emerging
    in_catalog: true
    kin_score: 23.7
    mcp: &id057
      status: none
    slug: neuvector
    status: profiled
    tags: &id058
    - Compliance
    - Containers
    - Kubernetes
    - Open Source
    url: /providers/neuvector/
  layer: domain
  name: NeuVector
  provider: neuvector
  says: lists NeuVector as an integration
  source: https://circleci.com/integrations/
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
    mcp: &id059
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id060
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic
  provider: new-relic
  says: lists New Relic as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 20.3
    band: developing
    in_catalog: true
    kin_score: 41.4
    mcp: &id061
      status: none
    slug: nightfall-ai
    status: profiled
    tags: &id062
    - Artificial Intelligence
    - Privacy
    - Sensitive Data
    url: /providers/nightfall-ai/
  layer: domain
  name: Nightfall
  provider: nightfall-ai
  says: lists Nightfall as an integration
  source: https://circleci.com/integrations/
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
    mcp: &id063
      status: none
    slug: opsgenie
    status: profiled
    tags: &id064
    - Alerts
    - Incident Management
    - Monitoring
    - On-Call
    url: /providers/opsgenie/
  layer: common
  name: OpsGenie
  provider: opsgenie
  says: lists OpsGenie as an integration
  source: https://circleci.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.30
    key: release-engineering-management
    name: Release Engineering Management
    url: /capabilities/release-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 17.5
    mcp: &id065
      status: none
    slug: packagecloud
    status: profiled
    tags: &id066
    - Debian
    - DevOps
    - Package Management
    - Repository Hosting
    url: /providers/packagecloud/
  layer: domain
  name: packagecloud
  provider: packagecloud
  says: lists packagecloud as an integration
  source: https://circleci.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.50
    key: software-quality-engineering
    name: Software Quality Engineering
    url: /capabilities/software-quality-engineering/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id067
      status: unchecked
    slug: packtracker
    status: queued for profiling
    tags: &id068 []
    url: null
  layer: domain
  name: Packtracker
  provider: packtracker
  says: lists Packtracker as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 22.2
    band: thin
    in_catalog: true
    kin_score: 30.4
    mcp: &id069
      status: none
    slug: prisma-cloud
    status: profiled
    tags: &id070
    - Cloud Security
    - Cloud-Native
    - Compliance
    - Containers
    url: /providers/prisma-cloud/
  layer: domain
  name: Prisma Cloud
  provider: prisma-cloud
  says: lists Prisma Cloud as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 2.8
    band: thin
    in_catalog: true
    kin_score: 27.5
    mcp: &id071
      source: https://developers.probely.com/mcp/mcp-server-overview
      status: verified
    slug: probely
    status: profiled
    tags: &id072
    - Company
    url: /providers/probely/
  layer: domain
  name: Probely
  provider: probely
  says: lists Probely as an integration
  source: https://circleci.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.50
    key: software-quality-engineering
    name: Software Quality Engineering
    url: /capabilities/software-quality-engineering/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id073
      status: unchecked
    slug: realmethods
    status: queued for profiling
    tags: &id074 []
    url: null
  layer: domain
  name: realMethods
  provider: realmethods
  says: lists realMethods as an integration
  source: https://circleci.com/integrations/
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
    mcp: &id075
      status: unchecked
    slug: rezilion
    status: queued for profiling
    tags: &id076 []
    url: null
  layer: domain
  name: Rezilion
  provider: rezilion
  says: lists Rezilion as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 30.2
    band: developing
    in_catalog: true
    kin_score: 48.1
    mcp: &id077
      source: https://github.com/rollbar/rollbar-mcp-server
      status: verified
    slug: rollbar
    status: profiled
    tags: &id078
    - Debugging
    - DevOps
    - Error Tracking
    - Monitoring
    url: /providers/rollbar/
  layer: common
  name: Rollbar
  provider: rollbar
  says: lists Rollbar as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 32.2
    band: strong
    in_catalog: true
    kin_score: 58.7
    mcp: &id079
      status: none
    slug: qwiet-ai
    status: profiled
    tags: &id080
    - Application Security
    - Company
    - SAST
    - Security
    url: /providers/qwiet-ai/
  layer: domain
  name: Shiftleft (now Qwiet AI)
  provider: qwiet-ai
  says: lists Shiftleft (now Qwiet AI) as an integration
  source: https://circleci.com/integrations/
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
    mcp: &id081
      status: unchecked
    slug: sken-ai
    status: queued for profiling
    tags: &id082 []
    url: null
  layer: domain
  name: Sken.ai
  provider: sken-ai
  says: lists Sken.ai as an integration
  source: https://circleci.com/integrations/
  tier: declared
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
    mcp: &id083
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id084
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://circleci.com/integrations/
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
    mcp: &id085
      source: https://github.com/snyk/studio-mcp
      status: verified
    slug: snyk
    status: profiled
    tags: &id086
    - Application Security
    - DevSecOps
    - Security
    - Vulnerability Management
    url: /providers/snyk/
  layer: domain
  name: Snyk
  provider: snyk
  says: lists Snyk as an integration
  source: https://circleci.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.50
    key: software-quality-engineering
    name: Software Quality Engineering
    url: /capabilities/software-quality-engineering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.9
    band: strong
    in_catalog: true
    kin_score: 56.1
    mcp: &id087
      source: https://github.com/SonarSource/sonarqube-mcp-server
      status: verified
    slug: sonarsource
    status: profiled
    tags: &id088
    - Code Quality
    - Code Security
    - Company
    - Static Analysis
    url: /providers/sonarsource/
  layer: domain
  name: SonarSource
  provider: sonarsource
  says: lists SonarSource as an integration
  source: https://circleci.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.30
    key: release-engineering-management
    name: Release Engineering Management
    url: /capabilities/release-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.4
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id089
      source: https://github.com/sonatype/dependency-management-mcp-server
      status: verified
    slug: sonatype
    status: profiled
    tags: &id090
    - SBOM
    - Security
    - Software Supply Chain
    - Vulnerability Management
    url: /providers/sonatype/
  layer: domain
  name: Sonatype
  provider: sonatype
  says: lists Sonatype as an integration
  source: https://circleci.com/integrations/
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
    mcp: &id091
      status: unchecked
    slug: soos
    status: queued for profiling
    tags: &id092 []
    url: null
  layer: domain
  name: SOOS
  provider: soos
  says: lists SOOS as an integration
  source: https://circleci.com/integrations/
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
    mcp: &id093
      status: unchecked
    slug: spectralops
    status: queued for profiling
    tags: &id094 []
    url: null
  layer: domain
  name: Spectral (SpectralOps, Check Point)
  provider: spectralops
  says: lists Spectral (SpectralOps, Check Point) as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 26.6
    mcp: &id095
      status: none
    slug: squadcast
    status: profiled
    tags: &id096
    - DevOps
    - Incident Response
    - On-Call Management
    - SRE
    url: /providers/squadcast/
  layer: common
  name: Squadcast
  provider: squadcast
  says: lists Squadcast as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 23.9
    band: developing
    in_catalog: true
    kin_score: 45.7
    mcp: &id097
      source: https://github.com/stackhawk/stackhawk-mcp
      status: verified
    slug: stackhawk
    status: profiled
    tags: &id098
    - API Security
    - Application Security
    - DAST
    - Security Testing
    url: /providers/stackhawk/
  layer: domain
  name: StackHawk
  provider: stackhawk
  says: lists StackHawk as an integration
  source: https://circleci.com/integrations/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.0
    mcp: &id099
      status: none
    slug: thundra
    status: profiled
    tags: &id100
    - APM
    - Company
    - Observability
    - Serverless
    url: /providers/thundra/
  layer: common
  name: Thundra
  provider: thundra
  says: lists Thundra as an integration
  source: https://circleci.com/integrations/
  tier: declared
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
    mcp: &id101
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id102
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: lists Twilio as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 31.0
    band: thin
    in_catalog: true
    kin_score: 37.5
    mcp: &id103
      status: none
    slug: wallarm
    status: profiled
    tags: &id104
    - API Security
    - Cybersecurity
    - Security Testing
    - WAF
    url: /providers/wallarm/
  layer: domain
  name: Wallarm
  provider: wallarm
  says: lists Wallarm as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 26.6
    band: exemplar
    in_catalog: true
    kin_score: 67.0
    mcp: &id105
      status: none
    slug: mend
    status: profiled
    tags: &id106
    - Application Security
    - Container Security
    - SAST
    - Software Composition Analysis
    url: /providers/mend/
  layer: domain
  name: WhiteSource (now Mend)
  provider: mend
  says: lists WhiteSource (now Mend) as an integration
  source: https://circleci.com/integrations/
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
    agent_readiness: 18.6
    band: emerging
    in_catalog: true
    kin_score: 22.5
    mcp: &id107
      status: none
    slug: xmatters
    status: profiled
    tags: &id108
    - Alerting
    - Incident Management
    - On-Call
    - Service Reliability
    url: /providers/xmatters/
  layer: common
  name: xMatters
  provider: xmatters
  says: lists xMatters as an integration
  source: https://circleci.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ci-cd-devops/circleci/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: Alcide.io
  slug: alcide
  status: queued for profiling
  tags: *id002
  url: null
- agent_band: agent-ready
  agent_readiness: 29.5
  band: exemplar
  in_catalog: true
  kin_score: 75.2
  mcp: *id003
  name: Amazon ECR
  slug: amazon-ecr
  status: profiled
  tags: *id004
  url: /providers/amazon-ecr/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id005
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id006
  url: /providers/amazon-s3/
- agent_band: agent-aware
  agent_readiness: 21.5
  band: thin
  in_catalog: true
  kin_score: 35.8
  mcp: *id007
  name: Anchore
  slug: anchore
  status: profiled
  tags: *id008
  url: /providers/anchore/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 69.5
  mcp: *id009
  name: Anecdotes
  slug: anecdotes
  status: profiled
  tags: *id010
  url: /providers/anecdotes/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 40.1
  mcp: *id011
  name: Aqua Security
  slug: aqua-security
  status: profiled
  tags: *id012
  url: /providers/aqua-security/
- agent_band: agent-ready
  agent_readiness: 38.4
  band: strong
  in_catalog: true
  kin_score: 62.1
  mcp: *id013
  name: CheckMarx
  slug: checkmarx
  status: profiled
  tags: *id014
  url: /providers/checkmarx/
- agent_band: agent-aware
  agent_readiness: 27.3
  band: thin
  in_catalog: true
  kin_score: 32.0
  mcp: *id015
  name: Cloudsmith
  slug: cloudsmith
  status: profiled
  tags: *id016
  url: /providers/cloudsmith/
- agent_band: agent-aware
  agent_readiness: 20.3
  band: strong
  in_catalog: true
  kin_score: 59.7
  mcp: *id017
  name: Codecov
  slug: codecov
  status: profiled
  tags: *id018
  url: /providers/codecov/
- agent_band: human-only
  agent_readiness: 1.8
  band: thin
  in_catalog: true
  kin_score: 26.2
  mcp: *id019
  name: CodeScene
  slug: codescene
  status: profiled
  tags: *id020
  url: /providers/codescene/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: developing
  in_catalog: true
  kin_score: 43.2
  mcp: *id021
  name: ConfigCat
  slug: configcat
  status: profiled
  tags: *id022
  url: /providers/configcat/
- agent_band: agent-native
  agent_readiness: 59.2
  band: strong
  in_catalog: true
  kin_score: 60.7
  mcp: *id023
  name: Contrast
  slug: contrast-security
  status: profiled
  tags: *id024
  url: /providers/contrast-security/
- agent_band: agent-ready
  agent_readiness: 43.6
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id025
  name: Coralogix
  slug: coralogix
  status: profiled
  tags: *id026
  url: /providers/coralogix/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id027
  name: Coveralls
  slug: coveralls
  status: profiled
  tags: *id028
  url: /providers/coveralls/
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id029
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id030
  url: /providers/datadog/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id031
  name: datree policy
  slug: datree
  status: queued for profiling
  tags: *id032
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.0
  mcp: *id033
  name: DeepFactor
  slug: deepfactor
  status: profiled
  tags: *id034
  url: /providers/deepfactor/
- agent_band: agent-aware
  agent_readiness: 20.2
  band: developing
  in_catalog: true
  kin_score: 53.5
  mcp: *id035
  name: Fortanix
  slug: fortanix
  status: profiled
  tags: *id036
  url: /providers/fortanix/
- agent_band: agent-aware
  agent_readiness: 22.2
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id037
  name: Fossa
  slug: fossa
  status: profiled
  tags: *id038
  url: /providers/fossa/
- agent_band: agent-aware
  agent_readiness: 13.0
  band: minimal
  in_catalog: true
  kin_score: 6.2
  mcp: *id039
  name: GitGuardian
  slug: gitguardian
  status: profiled
  tags: *id040
  url: /providers/gitguardian/
- agent_band: agent-ready
  agent_readiness: 37.7
  band: strong
  in_catalog: true
  kin_score: 65.4
  mcp: *id041
  name: Google Cloud GCR
  slug: google-artifact-registry
  status: profiled
  tags: *id042
  url: /providers/google-artifact-registry/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: thin
  in_catalog: true
  kin_score: 33.4
  mcp: *id043
  name: Honeybadger
  slug: honeybadger
  status: profiled
  tags: *id044
  url: /providers/honeybadger/
- agent_band: agent-ready
  agent_readiness: 55.5
  band: exemplar
  in_catalog: true
  kin_score: 71.6
  mcp: *id045
  name: Honeycomb
  slug: honeycomb
  status: profiled
  tags: *id046
  url: /providers/honeycomb/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id047
  name: Indeni
  slug: indeni
  status: queued for profiling
  tags: *id048
  url: null
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 22.7
  mcp: *id049
  name: Lacework
  slug: lacework
  status: profiled
  tags: *id050
  url: /providers/lacework/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id051
  name: Lightspin
  slug: lightspin
  status: queued for profiling
  tags: *id052
  url: null
- agent_band: agent-aware
  agent_readiness: 27.1
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id053
  name: LogDNA (now Mezmo)
  slug: mezmo
  status: profiled
  tags: *id054
  url: /providers/mezmo/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: strong
  in_catalog: true
  kin_score: 63.3
  mcp: *id055
  name: Logz.io
  slug: logz-io
  status: profiled
  tags: *id056
  url: /providers/logz-io/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: emerging
  in_catalog: true
  kin_score: 23.7
  mcp: *id057
  name: NeuVector
  slug: neuvector
  status: profiled
  tags: *id058
  url: /providers/neuvector/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id059
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id060
  url: /providers/new-relic/
- agent_band: agent-aware
  agent_readiness: 20.3
  band: developing
  in_catalog: true
  kin_score: 41.4
  mcp: *id061
  name: Nightfall
  slug: nightfall-ai
  status: profiled
  tags: *id062
  url: /providers/nightfall-ai/
- agent_band: agent-aware
  agent_readiness: 26.5
  band: developing
  in_catalog: true
  kin_score: 48.6
  mcp: *id063
  name: OpsGenie
  slug: opsgenie
  status: profiled
  tags: *id064
  url: /providers/opsgenie/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 17.5
  mcp: *id065
  name: packagecloud
  slug: packagecloud
  status: profiled
  tags: *id066
  url: /providers/packagecloud/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id067
  name: Packtracker
  slug: packtracker
  status: queued for profiling
  tags: *id068
  url: null
- agent_band: agent-aware
  agent_readiness: 22.2
  band: thin
  in_catalog: true
  kin_score: 30.4
  mcp: *id069
  name: Prisma Cloud
  slug: prisma-cloud
  status: profiled
  tags: *id070
  url: /providers/prisma-cloud/
- agent_band: human-only
  agent_readiness: 2.8
  band: thin
  in_catalog: true
  kin_score: 27.5
  mcp: *id071
  name: Probely
  slug: probely
  status: profiled
  tags: *id072
  url: /providers/probely/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id073
  name: realMethods
  slug: realmethods
  status: queued for profiling
  tags: *id074
  url: null
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id075
  name: Rezilion
  slug: rezilion
  status: queued for profiling
  tags: *id076
  url: null
- agent_band: agent-ready
  agent_readiness: 30.2
  band: developing
  in_catalog: true
  kin_score: 48.1
  mcp: *id077
  name: Rollbar
  slug: rollbar
  status: profiled
  tags: *id078
  url: /providers/rollbar/
- agent_band: agent-ready
  agent_readiness: 32.2
  band: strong
  in_catalog: true
  kin_score: 58.7
  mcp: *id079
  name: Shiftleft (now Qwiet AI)
  slug: qwiet-ai
  status: profiled
  tags: *id080
  url: /providers/qwiet-ai/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id081
  name: Sken.ai
  slug: sken-ai
  status: queued for profiling
  tags: *id082
  url: null
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id083
  name: Slack
  slug: slack
  status: profiled
  tags: *id084
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: exemplar
  in_catalog: true
  kin_score: 80.8
  mcp: *id085
  name: Snyk
  slug: snyk
  status: profiled
  tags: *id086
  url: /providers/snyk/
- agent_band: agent-ready
  agent_readiness: 32.9
  band: strong
  in_catalog: true
  kin_score: 56.1
  mcp: *id087
  name: SonarSource
  slug: sonarsource
  status: profiled
  tags: *id088
  url: /providers/sonarsource/
- agent_band: agent-ready
  agent_readiness: 33.4
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id089
  name: Sonatype
  slug: sonatype
  status: profiled
  tags: *id090
  url: /providers/sonatype/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id091
  name: SOOS
  slug: soos
  status: queued for profiling
  tags: *id092
  url: null
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id093
  name: Spectral (SpectralOps, Check Point)
  slug: spectralops
  status: queued for profiling
  tags: *id094
  url: null
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 26.6
  mcp: *id095
  name: Squadcast
  slug: squadcast
  status: profiled
  tags: *id096
  url: /providers/squadcast/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: developing
  in_catalog: true
  kin_score: 45.7
  mcp: *id097
  name: StackHawk
  slug: stackhawk
  status: profiled
  tags: *id098
  url: /providers/stackhawk/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.0
  mcp: *id099
  name: Thundra
  slug: thundra
  status: profiled
  tags: *id100
  url: /providers/thundra/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id101
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id102
  url: /providers/twilio/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: thin
  in_catalog: true
  kin_score: 37.5
  mcp: *id103
  name: Wallarm
  slug: wallarm
  status: profiled
  tags: *id104
  url: /providers/wallarm/
- agent_band: agent-aware
  agent_readiness: 26.6
  band: exemplar
  in_catalog: true
  kin_score: 67.0
  mcp: *id105
  name: WhiteSource (now Mend)
  slug: mend
  status: profiled
  tags: *id106
  url: /providers/mend/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: emerging
  in_catalog: true
  kin_score: 22.5
  mcp: *id107
  name: xMatters
  slug: xmatters
  status: profiled
  tags: *id108
  url: /providers/xmatters/
siblings:
- name: Coolify
  rows: 21
  url: /applications/ci-cd-devops/coolify/
- name: Gitea
  rows: 24
  url: /applications/ci-cd-devops/gitea/
- name: GitHub
  rows: 6
  url: /applications/ci-cd-devops/github/
- name: GitLab
  rows: 54
  url: /applications/ci-cd-devops/gitlab/
- name: Woodpecker CI
  rows: 3
  url: /applications/ci-cd-devops/woodpecker-ci/
sitemap: true
title: 'CircleCI: Code Hosting, CI/CD & DevOps reference app'
---
