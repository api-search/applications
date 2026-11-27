---
app: OWASP Dependency-Track
app_slug: owasp-dependency-track
app_url: https://github.com/DependencyTrack/dependency-track
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-620.40
  key: vulnerability-management
  layer: domain
  name: Vulnerability Management
  providers:
  - Checkmarx
  - CISA KEV
  - DefectDojo
  - ENISA EUVD
  - FIRST EPSS
  - Fortify SSC
  - GitHub Advisory Database
  - JVN (Japan Vulnerability Notes)
  - Kenna Security
  - NVD
  - OSV (Google)
  - Snyk
  - Sonatype OSS Index
  - Trivy
  - VulnCheck
  - VulnDB (Flashpoint)
  url: /capabilities/vulnerability-management/
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
  id: BC-4200
  key: software-product-engineering-management
  layer: common
  name: Software Product Engineering Management
  providers:
  - Jira
  url: /capabilities/software-product-engineering-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Mattermost
  - Microsoft Teams
  - Slack
  - Webex
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
category:
  id: security-scanning
  name: Security Scanning & Vulnerability Management
  url: /applications/security-scanning/
counts:
  declared: 0
  observed: 22
credits: []
evidence:
- route: source code
  url: https://github.com/DependencyTrack/dependency-track/tree/main/apiserver/src/main/java/org/dependencytrack/integrations
- route: source code
  url: https://github.com/DependencyTrack/dependency-track/tree/main/kev-data-source/builtin
- route: source code
  url: https://github.com/DependencyTrack/dependency-track/tree/main/notification/publishing
- route: source code
  url: https://github.com/DependencyTrack/dependency-track/tree/main/vuln-analysis
- route: source code
  url: https://github.com/DependencyTrack/dependency-track/tree/main/vuln-data-source
integrations:
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
    mcp: &id001
      status: none
    slug: apache-kafka
    status: profiled
    tags: &id002
    - Apache Kafka
    - Distributed Systems
    - Event Streaming
    - Messaging
    url: /providers/apache-kafka/
  layer: common
  name: Apache Kafka
  provider: apache-kafka
  says: ships the Apache Kafka SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/notification/publishing
  tier: observed
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
    mcp: &id003
      source: https://github.com/Checkmarx/cx-agentic-ai
      status: verified
    slug: checkmarx
    status: profiled
    tags: &id004
    - Application Security
    - Code Analysis
    - DevSecOps
    - SAST
    url: /providers/checkmarx/
  layer: domain
  name: Checkmarx
  provider: checkmarx
  says: ships the Checkmarx SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/vuln-analysis/checkmarx
  tier: observed
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
    mcp: &id005
      status: unchecked
    slug: cisa
    status: queued for profiling
    tags: &id006 []
    url: null
  layer: domain
  name: CISA KEV
  provider: cisa
  says: ships the CISA KEV SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/kev-data-source/builtin
  tier: observed
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
    agent_readiness: 39.0
    band: developing
    in_catalog: true
    kin_score: 52.2
    mcp: &id007
      status: unchecked
    slug: defectdojo
    status: profiled
    tags: &id008
    - Application Security
    - Compliance
    - DevSecOps
    - Vulnerability Management
    url: /providers/defectdojo/
  layer: domain
  name: DefectDojo
  provider: defectdojo
  says: ships the DefectDojo SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/apiserver/src/main/java/org/dependencytrack/integrations
  tier: observed
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
    kin_score: 5.6
    mcp: &id009
      status: unchecked
    slug: enisa
    status: profiled
    tags: &id010
    - EU
    - Public Service
    - Security
    - Vulnerabilities
    url: /providers/enisa/
  layer: domain
  name: ENISA EUVD
  provider: enisa
  says: ships the ENISA EUVD SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/kev-data-source/builtin
  tier: observed
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
    agent_readiness: 24.0
    band: thin
    in_catalog: true
    kin_score: 28.5
    mcp: &id011
      status: unchecked
    slug: first-org
    status: profiled
    tags: &id012
    - Community
    - Security
    - Standards
    - Training
    url: /providers/first-org/
  layer: domain
  name: FIRST EPSS
  provider: first-org
  says: ships the FIRST EPSS SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/apiserver/src/main/java/org/dependencytrack/epss
  tier: observed
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
    agent_readiness: 26.4
    band: strong
    in_catalog: true
    kin_score: 57.0
    mcp: &id013
      source: https://github.com/fortify/fcli
      status: verified
    slug: fortify
    status: profiled
    tags: &id014
    - Application Security
    - DAST
    - DevSecOps
    - SAST
    url: /providers/fortify/
  layer: domain
  name: Fortify SSC
  provider: fortify
  says: ships the Fortify SSC SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/apiserver/src/main/java/org/dependencytrack/integrations
  tier: observed
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
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id015
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id016
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub Advisory Database
  provider: github
  says: ships the GitHub Advisory Database SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/vuln-data-source/github
  tier: observed
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
    mcp: &id017
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id018
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: common
  name: Jira
  provider: jira
  says: ships the Jira SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/notification/publishing
  tier: observed
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
    kin_score: 2.5
    mcp: &id019
      status: unchecked
    slug: jvn
    status: profiled
    tags: &id020
    - Company
    - Japan
    - Security
    - Vulnerabilities
    url: /providers/jvn/
  layer: domain
  name: JVN (Japan Vulnerability Notes)
  provider: jvn
  says: ships the JVN (Japan Vulnerability Notes) SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/vuln-data-source/jvn
  tier: observed
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
    agent_readiness: 28.0
    band: developing
    in_catalog: true
    kin_score: 43.8
    mcp: &id021
      status: none
    slug: kenna-security
    status: profiled
    tags: &id022
    - Company
    - Cybersecurity
    - Risk-Based Prioritization
    - Vulnerability Management
    url: /providers/kenna-security/
  layer: domain
  name: Kenna Security
  provider: kenna-security
  says: ships the Kenna Security SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/apiserver/src/main/java/org/dependencytrack/integrations
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.2
    band: thin
    in_catalog: true
    kin_score: 37.0
    mcp: &id023
      source: https://github.com/mattermost/mmctl-mcp
      status: verified
    slug: mattermost
    status: profiled
    tags: &id024
    - Collaboration
    - Messaging
    - Open Source
    - Team Chat
    url: /providers/mattermost/
  layer: common
  name: Mattermost
  provider: mattermost
  says: ships the Mattermost SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/notification/publishing
  tier: observed
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
    mcp: &id025
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id026
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: ships the Microsoft Teams SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/notification/publishing
  tier: observed
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
    agent_readiness: 31.7
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id027
      status: none
    slug: nvd
    status: profiled
    tags: &id028
    - CPE
    - CVE
    - Security
    - Vulnerabilities
    url: /providers/nvd/
  layer: domain
  name: NVD
  provider: nvd
  says: ships the NVD SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/vuln-data-source/nvd
  tier: observed
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
    agent_readiness: 5.7
    band: minimal
    in_catalog: true
    kin_score: 9.1
    mcp: &id029
      status: unchecked
    slug: osv-dev
    status: profiled
    tags: &id030
    - Open Source
    - Remediation
    - Scanner
    - Vulnerability Database
    url: /providers/osv-dev/
  layer: domain
  name: OSV (Google)
  provider: osv-dev
  says: ships the OSV (Google) SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/vuln-data-source/osv
  tier: observed
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
    mcp: &id031
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id032
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/notification/publishing
  tier: observed
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
    mcp: &id033
      source: https://github.com/snyk/studio-mcp
      status: verified
    slug: snyk
    status: profiled
    tags: &id034
    - Application Security
    - DevSecOps
    - Security
    - Vulnerability Management
    url: /providers/snyk/
  layer: domain
  name: Snyk
  provider: snyk
  says: ships the Snyk SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/vuln-analysis/snyk
  tier: observed
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
    agent_readiness: 33.4
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id035
      source: https://github.com/sonatype/dependency-management-mcp-server
      status: verified
    slug: sonatype
    status: profiled
    tags: &id036
    - SBOM
    - Security
    - Software Supply Chain
    - Vulnerability Management
    url: /providers/sonatype/
  layer: domain
  name: Sonatype OSS Index
  provider: sonatype
  says: ships the Sonatype OSS Index SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/vuln-analysis/oss-index
  tier: observed
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
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id037
      source: https://github.com/aquasecurity/trivy-mcp
      status: verified
    slug: trivy
    status: profiled
    tags: &id038
    - Containers
    - Kubernetes
    - SBOM
    - Security
    url: /providers/trivy/
  layer: domain
  name: Trivy
  provider: trivy
  says: ships the Trivy SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/vuln-analysis/trivy
  tier: observed
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
    agent_readiness: 33.1
    band: strong
    in_catalog: true
    kin_score: 58.3
    mcp: &id039
      source: https://github.com/vulncheck-oss/mcp
      status: verified
    slug: vulncheck
    status: profiled
    tags: &id040
    - Company
    - Exploit Intelligence
    - Security
    - Vulnerability Intelligence
    url: /providers/vulncheck/
  layer: domain
  name: VulnCheck
  provider: vulncheck
  says: ships the VulnCheck SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/kev-data-source/builtin
  tier: observed
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
    agent_readiness: 29.2
    band: emerging
    in_catalog: true
    kin_score: 24.8
    mcp: &id041
      source: https://flashpoint.io/resources/product-updates/introducing-the-flashpoint-mcp-server/
      status: verified
    slug: flashpoint
    status: profiled
    tags: &id042
    - Company
    - Cybersecurity
    - Security
    - Threat Intelligence
    url: /providers/flashpoint/
  layer: domain
  name: VulnDB (Flashpoint)
  provider: flashpoint
  says: ships the VulnDB (Flashpoint) SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/vuln-analysis/vuln-db
  tier: observed
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
    agent_readiness: 61.8
    band: strong
    in_catalog: true
    kin_score: 66.1
    mcp: &id043
      source: https://github.com/WebexSamples/webex-messaging-mcp-server
      status: verified
    slug: webex
    status: profiled
    tags: &id044
    - Calling
    - Collaboration
    - Communications
    - Enterprise
    url: /providers/webex/
  layer: common
  name: Webex
  provider: webex
  says: ships the Webex SDK or integration code
  source: https://github.com/DependencyTrack/dependency-track/tree/main/notification/publishing
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/security-scanning/owasp-dependency-track/
providers:
- agent_band: agent-aware
  agent_readiness: 27.8
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id001
  name: Apache Kafka
  slug: apache-kafka
  status: profiled
  tags: *id002
  url: /providers/apache-kafka/
- agent_band: agent-ready
  agent_readiness: 38.4
  band: strong
  in_catalog: true
  kin_score: 62.1
  mcp: *id003
  name: Checkmarx
  slug: checkmarx
  status: profiled
  tags: *id004
  url: /providers/checkmarx/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id005
  name: CISA KEV
  slug: cisa
  status: queued for profiling
  tags: *id006
  url: null
- agent_band: agent-ready
  agent_readiness: 39.0
  band: developing
  in_catalog: true
  kin_score: 52.2
  mcp: *id007
  name: DefectDojo
  slug: defectdojo
  status: profiled
  tags: *id008
  url: /providers/defectdojo/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id009
  name: ENISA EUVD
  slug: enisa
  status: profiled
  tags: *id010
  url: /providers/enisa/
- agent_band: agent-aware
  agent_readiness: 24.0
  band: thin
  in_catalog: true
  kin_score: 28.5
  mcp: *id011
  name: FIRST EPSS
  slug: first-org
  status: profiled
  tags: *id012
  url: /providers/first-org/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: strong
  in_catalog: true
  kin_score: 57.0
  mcp: *id013
  name: Fortify SSC
  slug: fortify
  status: profiled
  tags: *id014
  url: /providers/fortify/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id015
  name: GitHub Advisory Database
  slug: github
  status: profiled
  tags: *id016
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id017
  name: Jira
  slug: jira
  status: profiled
  tags: *id018
  url: /providers/jira/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.5
  mcp: *id019
  name: JVN (Japan Vulnerability Notes)
  slug: jvn
  status: profiled
  tags: *id020
  url: /providers/jvn/
- agent_band: agent-aware
  agent_readiness: 28.0
  band: developing
  in_catalog: true
  kin_score: 43.8
  mcp: *id021
  name: Kenna Security
  slug: kenna-security
  status: profiled
  tags: *id022
  url: /providers/kenna-security/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: thin
  in_catalog: true
  kin_score: 37.0
  mcp: *id023
  name: Mattermost
  slug: mattermost
  status: profiled
  tags: *id024
  url: /providers/mattermost/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id025
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id026
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 31.7
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id027
  name: NVD
  slug: nvd
  status: profiled
  tags: *id028
  url: /providers/nvd/
- agent_band: agent-aware
  agent_readiness: 5.7
  band: minimal
  in_catalog: true
  kin_score: 9.1
  mcp: *id029
  name: OSV (Google)
  slug: osv-dev
  status: profiled
  tags: *id030
  url: /providers/osv-dev/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id031
  name: Slack
  slug: slack
  status: profiled
  tags: *id032
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: exemplar
  in_catalog: true
  kin_score: 80.8
  mcp: *id033
  name: Snyk
  slug: snyk
  status: profiled
  tags: *id034
  url: /providers/snyk/
- agent_band: agent-ready
  agent_readiness: 33.4
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id035
  name: Sonatype OSS Index
  slug: sonatype
  status: profiled
  tags: *id036
  url: /providers/sonatype/
- agent_band: agent-ready
  agent_readiness: 29.4
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id037
  name: Trivy
  slug: trivy
  status: profiled
  tags: *id038
  url: /providers/trivy/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: strong
  in_catalog: true
  kin_score: 58.3
  mcp: *id039
  name: VulnCheck
  slug: vulncheck
  status: profiled
  tags: *id040
  url: /providers/vulncheck/
- agent_band: agent-ready
  agent_readiness: 29.2
  band: emerging
  in_catalog: true
  kin_score: 24.8
  mcp: *id041
  name: VulnDB (Flashpoint)
  slug: flashpoint
  status: profiled
  tags: *id042
  url: /providers/flashpoint/
- agent_band: agent-ready
  agent_readiness: 61.8
  band: strong
  in_catalog: true
  kin_score: 66.1
  mcp: *id043
  name: Webex
  slug: webex
  status: profiled
  tags: *id044
  url: /providers/webex/
siblings:
- name: DefectDojo
  rows: 11
  url: /applications/security-scanning/defectdojo/
- name: Nuclei
  rows: 18
  url: /applications/security-scanning/nuclei/
- name: Snyk
  rows: 27
  url: /applications/security-scanning/snyk/
- name: Tenable
  rows: 45
  url: /applications/security-scanning/tenable/
- name: Trivy
  rows: 4
  url: /applications/security-scanning/trivy/
- name: Wazuh
  rows: 17
  url: /applications/security-scanning/wazuh/
sitemap: true
title: 'OWASP Dependency-Track: Security Scanning & Vulnerability Management reference app'
---
