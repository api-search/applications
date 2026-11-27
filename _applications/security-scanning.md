---
access: understanding
agent_layer: []
apps:
- anchor: defectdojo
  counts:
    declared: 0
    observed: 11
  evidence:
  - route: dependency manifest
    url: https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
  - route: source code
    url: https://github.com/DefectDojo/django-DefectDojo/blob/master/dojo/notifications/models.py
  - route: source code
    url: https://github.com/DefectDojo/django-DefectDojo/tree/master/dojo/tools
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Black Duck
    provider: black-duck
    says: ships the Black Duck SDK or integration code
    source: https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bugcrowd
    provider: bugcrowd
    says: ships the Bugcrowd SDK or integration code
    source: https://github.com/DefectDojo/django-DefectDojo/tree/master/dojo/tools
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Cobalt (pentest)
    provider: cobalt-io
    says: ships the Cobalt (pentest) SDK or integration code
    source: https://github.com/DefectDojo/django-DefectDojo/tree/master/dojo/tools
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Edgescan
    provider: edgescan
    says: ships the Edgescan SDK or integration code
    source: https://github.com/DefectDojo/django-DefectDojo/tree/master/dojo/tools
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: Jira
    provider: jira
    says: ships the Jira SDK or integration code
    source: https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: ships the Microsoft Teams SDK or integration code
    source: https://github.com/DefectDojo/django-DefectDojo/blob/master/dojo/notifications/models.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: SonarQube
    provider: sonarqube
    says: ships the SonarQube SDK or integration code
    source: https://github.com/DefectDojo/django-DefectDojo/tree/master/dojo/tools
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Vulners
    provider: vulners
    says: ships the Vulners SDK or integration code
    source: https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
    tier: observed
  kind: self-hosted
  name: DefectDojo
  page: /applications/security-scanning/defectdojo/
  slug: defectdojo
  url: https://github.com/DefectDojo/django-DefectDojo
- anchor: owasp-dependency-track
  counts:
    declared: 0
    observed: 22
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
    layer: common
    name: Webex
    provider: webex
    says: ships the Webex SDK or integration code
    source: https://github.com/DependencyTrack/dependency-track/tree/main/notification/publishing
    tier: observed
  kind: self-hosted
  name: OWASP Dependency-Track
  page: /applications/security-scanning/owasp-dependency-track/
  slug: owasp-dependency-track
  url: https://github.com/DependencyTrack/dependency-track
- anchor: wazuh
  counts:
    declared: 6
    observed: 11
  evidence:
  - route: documentation
    url: https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
  - route: source code
    url: https://github.com/wazuh/wazuh/tree/main/wodles
  - route: source code
    url: https://github.com/wazuh/wazuh/tree/v4.12.0/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon CloudWatch Logs
    provider: amazon-cloudwatch
    says: ships the Amazon CloudWatch Logs SDK or integration code
    source: https://github.com/wazuh/wazuh/tree/main/wodles/aws/services
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon GuardDuty
    provider: amazon-guardduty
    says: ships the Amazon GuardDuty SDK or integration code
    source: https://github.com/wazuh/wazuh/tree/main/wodles/aws/buckets_s3
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Inspector
    provider: amazon-inspector
    says: ships the Amazon Inspector SDK or integration code
    source: https://github.com/wazuh/wazuh/tree/main/wodles/aws/services
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: AWS CloudTrail
    provider: amazon-cloudtrail
    says: ships the AWS CloudTrail SDK or integration code
    source: https://github.com/wazuh/wazuh/tree/main/wodles/aws/buckets_s3
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Cloud
    provider: google-cloud-platform
    says: ships the Google Cloud SDK or integration code
    source: https://github.com/wazuh/wazuh/tree/main/wodles/gcloud
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Maltiverse
    provider: maltiverse
    says: ships the Maltiverse SDK or integration code
    source: https://github.com/wazuh/wazuh/tree/v4.12.0/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Azure
    provider: microsoft-azure
    says: ships the Microsoft Azure SDK or integration code
    source: https://github.com/wazuh/wazuh/tree/main/wodles/azure
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: common
    name: PagerDuty
    provider: pagerduty
    says: ships the PagerDuty SDK or integration code
    source: https://github.com/wazuh/wazuh/tree/v4.12.0/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Shuffle
    provider: shuffle
    says: ships the Shuffle SDK or integration code
    source: https://github.com/wazuh/wazuh/tree/v4.12.0/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/wazuh/wazuh/tree/v4.12.0/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: VirusTotal
    provider: virustotal
    says: ships the VirusTotal SDK or integration code
    source: https://github.com/wazuh/wazuh/tree/v4.12.0/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Security Lake
    provider: amazon-security-lake
    says: lists Amazon Security Lake as an integration
    source: https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: AWS Security Hub
    provider: aws-security-hub
    says: lists AWS Security Hub as an integration
    source: https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Docker
    provider: docker
    says: lists Docker as an integration
    source: https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Graph
    provider: microsoft-graph
    says: lists Microsoft Graph as an integration
    source: https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Office 365
    provider: microsoft-office-365
    says: lists Office 365 as an integration
    source: https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
    tier: declared
  kind: self-hosted
  name: Wazuh
  page: /applications/security-scanning/wazuh/
  slug: wazuh
  url: https://github.com/wazuh/wazuh
- anchor: nuclei
  counts:
    declared: 0
    observed: 18
  evidence:
  - route: dependency manifest
    url: https://github.com/projectdiscovery/nuclei/blob/dev/go.mod
  - route: source code
    url: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/exporters
  - route: source code
    url: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/trackers
  - route: source code
    url: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-941
      key: AE-941
      name: Internet Exposure Search & Attack-Surface Data
      url: /capabilities/internet-exposure-search-attack-surface-data/
      via_parent: null
    credit: null
    layer: domain
    name: BinaryEdge
    provider: binaryedge
    says: ships the BinaryEdge SDK or integration code
    source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-941
      key: AE-941
      name: Internet Exposure Search & Attack-Surface Data
      url: /capabilities/internet-exposure-search-attack-surface-data/
      via_parent: null
    credit: null
    layer: domain
    name: Censys
    provider: censys
    says: ships the Censys SDK or integration code
    source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-941
      key: AE-941
      name: Internet Exposure Search & Attack-Surface Data
      url: /capabilities/internet-exposure-search-attack-surface-data/
      via_parent: null
    credit: null
    layer: domain
    name: Criminal IP
    provider: criminal-ip
    says: ships the Criminal IP SDK or integration code
    source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
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
    name: Elasticsearch
    provider: elastic
    says: ships the Elasticsearch SDK or integration code
    source: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/exporters
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-941
      key: AE-941
      name: Internet Exposure Search & Attack-Surface Data
      url: /capabilities/internet-exposure-search-attack-surface-data/
      via_parent: null
    credit: null
    layer: domain
    name: FOFA
    provider: fofa
    says: ships the FOFA SDK or integration code
    source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: Gitea
    provider: gitea
    says: ships the Gitea SDK or integration code
    source: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/trackers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/trackers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/trackers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-941
      key: AE-941
      name: Internet Exposure Search & Attack-Surface Data
      url: /capabilities/internet-exposure-search-attack-surface-data/
      via_parent: null
    credit: null
    layer: domain
    name: GreyNoise
    provider: greynoise
    says: ships the GreyNoise SDK or integration code
    source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-941
      key: AE-941
      name: Internet Exposure Search & Attack-Surface Data
      url: /capabilities/internet-exposure-search-attack-surface-data/
      via_parent: null
    credit: null
    layer: domain
    name: Hunter (Qi An Xin)
    provider: hunter-qianxin
    says: ships the Hunter (Qi An Xin) SDK or integration code
    source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: Jira
    provider: jira
    says: ships the Jira SDK or integration code
    source: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/trackers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: Linear
    provider: linear-app
    says: ships the Linear SDK or integration code
    source: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/trackers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-941
      key: AE-941
      name: Internet Exposure Search & Attack-Surface Data
      url: /capabilities/internet-exposure-search-attack-surface-data/
      via_parent: null
    credit: null
    layer: domain
    name: Netlas
    provider: netlas
    says: ships the Netlas SDK or integration code
    source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-941
      key: AE-941
      name: Internet Exposure Search & Attack-Surface Data
      url: /capabilities/internet-exposure-search-attack-surface-data/
      via_parent: null
    credit: null
    layer: domain
    name: ONYPHE
    provider: onyphe
    says: ships the ONYPHE SDK or integration code
    source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-941
      key: AE-941
      name: Internet Exposure Search & Attack-Surface Data
      url: /capabilities/internet-exposure-search-attack-surface-data/
      via_parent: null
    credit: null
    layer: domain
    name: Quake (Qihoo 360)
    provider: quake-360
    says: ships the Quake (Qihoo 360) SDK or integration code
    source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-941
      key: AE-941
      name: Internet Exposure Search & Attack-Surface Data
      url: /capabilities/internet-exposure-search-attack-surface-data/
      via_parent: null
    credit: null
    layer: domain
    name: Shodan
    provider: shodan
    says: ships the Shodan SDK or integration code
    source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Splunk
    provider: splunk
    says: ships the Splunk SDK or integration code
    source: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/exporters
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-941
      key: AE-941
      name: Internet Exposure Search & Attack-Surface Data
      url: /capabilities/internet-exposure-search-attack-surface-data/
      via_parent: null
    credit: null
    layer: domain
    name: ZoomEye
    provider: zoomeye
    says: ships the ZoomEye SDK or integration code
    source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
    tier: observed
  kind: self-hosted
  name: Nuclei
  page: /applications/security-scanning/nuclei/
  slug: nuclei
  url: https://github.com/projectdiscovery/nuclei
- anchor: trivy
  counts:
    declared: 1
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://github.com/aquasecurity/trivy/blob/main/go.mod
  - route: source code
    url: https://github.com/aquasecurity/trivy/tree/main/pkg/fanal/image/registry
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: Amazon ECR
    provider: amazon-ecr
    says: ships the Amazon ECR SDK or integration code
    source: https://github.com/aquasecurity/trivy/tree/main/pkg/fanal/image/registry
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: Azure Container Registry
    provider: azure-container-registry
    says: ships the Azure Container Registry SDK or integration code
    source: https://github.com/aquasecurity/trivy/tree/main/pkg/fanal/image/registry
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: Google Artifact Registry / GCR
    provider: google-artifact-registry
    says: ships the Google Artifact Registry / GCR SDK or integration code
    source: https://github.com/aquasecurity/trivy/tree/main/pkg/fanal/image/registry
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: GitHub Container Registry
    provider: github-container-registry
    says: lists GitHub Container Registry as an integration
    source: https://github.com/aquasecurity/trivy-db
    tier: declared
  kind: self-hosted
  name: Trivy
  page: /applications/security-scanning/trivy/
  slug: trivy
  url: https://github.com/aquasecurity/trivy
- anchor: snyk
  counts:
    declared: 27
    observed: 0
  evidence:
  - route: integrations page
    url: https://docs.snyk.io/sitemap.md
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: Amazon ECR
    provider: amazon-ecr
    says: lists Amazon ECR as an integration
    source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-amazon-elastic-container-registry-ecr.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: AWS
    provider: amazon-web-services
    says: lists AWS as an integration
    source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-iac/cloud-platform-integrations/aws-integration.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: AWS CloudTrail Lake
    provider: amazon-cloudtrail
    says: lists AWS CloudTrail Lake as an integration
    source: https://docs.snyk.io/developer-tools/integrations/event-forwarding/aws-cloudtrail-lake.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    credit: null
    layer: domain
    name: AWS CodePipeline
    provider: amazon-codepipeline
    says: lists AWS CodePipeline as an integration
    source: https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/aws-codepipeline-integration-by-adding-a-snyk-scan-stage.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Azure
    provider: microsoft-azure
    says: lists Azure as an integration
    source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-iac/cloud-platform-integrations/azure-integration-for-cloud-configurations.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: Azure Container Registry
    provider: azure-container-registry
    says: lists Azure Container Registry as an integration
    source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-microsoft-azure-container-registry-acr.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40.10
      key: BC-4200.40.10
      name: Source Code Management
      url: /capabilities/software-construction-management/
      via_parent: Software Construction Management
    credit: null
    layer: domain
    name: Azure Repos / Azure Pipelines
    provider: microsoft-azure-devops
    says: lists Azure Repos / Azure Pipelines as an integration
    source: https://docs.snyk.io/developer-tools/integrations/scm-integrations/organization-level-integrations/azure-repositories-tfs.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40.10
      key: BC-4200.40.10
      name: Source Code Management
      url: /capabilities/software-construction-management/
      via_parent: Software Construction Management
    credit: null
    layer: domain
    name: Bitbucket
    provider: bitbucket
    says: lists Bitbucket as an integration
    source: https://docs.snyk.io/developer-tools/integrations/scm-integrations/organization-level-integrations/bitbucket-cloud.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bitbucket Pipelines
    provider: bitbucket-pipelines
    says: lists Bitbucket Pipelines as an integration
    source: https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/bitbucket-pipelines-integration-using-a-snyk-pipe.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    credit: null
    layer: domain
    name: CircleCI
    provider: circleci
    says: lists CircleCI as an integration
    source: https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/circleci-integration-using-a-snyk-orb.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: DigitalOcean Container Registry
    provider: digitalocean
    says: lists DigitalOcean Container Registry as an integration
    source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-digitalocean.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: Docker Hub
    provider: docker-hub
    says: lists Docker Hub as an integration
    source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-docker-hub.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40.10
      key: BC-4200.40.10
      name: Source Code Management
      url: /capabilities/software-construction-management/
      via_parent: Software Construction Management
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://docs.snyk.io/developer-tools/integrations/scm-integrations/organization-level-integrations/github.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub Actions
    provider: github-actions
    says: lists GitHub Actions as an integration
    source: https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/github-actions-for-snyk-setup-and-checking-for-vulnerabilities.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: GitHub Container Registry
    provider: github-container-registry
    says: lists GitHub Container Registry as an integration
    source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-github-container-registry.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40.10
      key: BC-4200.40.10
      name: Source Code Management
      url: /capabilities/software-construction-management/
      via_parent: Software Construction Management
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: lists GitLab as an integration
    source: https://docs.snyk.io/developer-tools/integrations/scm-integrations/organization-level-integrations/gitlab.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: GitLab Container Registry
    provider: gitlab-container-registry
    says: lists GitLab Container Registry as an integration
    source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-gitlab-container-registry.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: Google Artifact Registry
    provider: google-artifact-registry
    says: lists Google Artifact Registry as an integration
    source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-google-artifact-registry-gar.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Cloud
    provider: google-cloud-platform
    says: lists Google Cloud as an integration
    source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-iac/cloud-platform-integrations/google-cloud-integration.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: Harbor
    provider: goharbor
    says: lists Harbor as an integration
    source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-harbor-container-registry.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jenkins
    provider: jenkins
    says: lists Jenkins as an integration
    source: https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/jenkins-plugin-integration-with-snyk.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.10
      key: AE-250.10.10
      name: Language Package Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: JFrog Artifactory
    provider: jfrog
    says: lists JFrog Artifactory as an integration
    source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-open-source/package-repository-integrations/artifactory-package-repository-connection-setup.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    credit: null
    layer: common
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://docs.snyk.io/developer-tools/integrations/jira-and-slack-integrations/jira-integration.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: Quay
    provider: quay
    says: lists Quay as an integration
    source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-quay-container-registry.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://docs.snyk.io/developer-tools/integrations/jira-and-slack-integrations/slack-app.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.10
      key: AE-250.10.10
      name: Language Package Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: Sonatype Nexus Repository
    provider: nexus
    says: lists Sonatype Nexus Repository as an integration
    source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-open-source/package-repository-integrations/nexus-repository-manager-connection-setup.md
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    credit: null
    layer: domain
    name: Terraform Cloud
    provider: terraform
    says: lists Terraform Cloud as an integration
    source: https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/terraform-cloud-integration-for-snyk-iac-using-run-tasks.md
    tier: declared
  kind: commercial
  name: Snyk
  page: /applications/security-scanning/snyk/
  slug: snyk
  url: https://snyk.io
- anchor: tenable
  counts:
    declared: 45
    observed: 0
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
    layer: domain
    name: Zscaler
    provider: zscaler
    says: lists Zscaler as an integration
    source: https://www.tenable.com/partners/technology
    tier: declared
  kind: commercial
  name: Tenable
  page: /applications/security-scanning/tenable/
  slug: tenable
  url: https://www.tenable.com
author: API Evangelist
candidates: []
credits: []
html: public
id: security-scanning
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Security
  store: github-marketplace
  url: https://github.com/marketplace?category=security
- category: Code scanning ready
  store: github-marketplace
  url: https://github.com/marketplace?category=code-scanning-ready
- category: Security
  store: atlassian-marketplace
  url: https://marketplace.atlassian.com/
- category: Security
  store: aws-marketplace
  url: https://aws.amazon.com/marketplace/b/2649363011
- category: Security
  store: azure-marketplace
  url: https://azuremarketplace.microsoft.com/en-us/marketplace/apps/category/security
- category: Vulnerability Management Software
  store: g2
  url: https://www.g2.com/categories/vulnerability-management
- category: Vulnerability Scanner Software
  store: g2
  url: https://www.g2.com/categories/vulnerability-scanner
name: Security Scanning & Vulnerability Management
needs:
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  fit: nearest
  layer: common
  why: findings pushed to developer issue trackers (Jira, Linear, GitHub/GitLab issues)
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: exact
  layer: common
  why: finding and policy-violation notifications to team chat (Slack, Teams, Mattermost, Webex)
- capability:
    attribution: Turbo EA
    id: BC-620.40
    key: vulnerability-management
    name: Vulnerability Management
    url: /capabilities/vulnerability-management/
    via_parent: null
  fit: exact
  layer: domain
  why: vulnerability intelligence feeds (NVD, GitHub advisories, OSS Index, VulnDB, VulnCheck KEV) and scanner/pentest results pulled by API (SonarQube, Black Duck, Bugcrowd, Cobalt, Edgescan); the core of the category
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: common
  why: 'Integration and API Management: Apache Kafka'
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  fit: exact
  layer: common
  why: paging on critical findings (PagerDuty)
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  fit: exact
  layer: domain
  why: cloud security event sources and SIEM/EDR/SOAR destinations (AWS Security Hub, GuardDuty, Splunk, CrowdStrike, VirusTotal)
- capability:
    attribution: API Evangelist extension
    id: AE-941
    key: AE-941
    name: Internet Exposure Search & Attack-Surface Data
    url: /capabilities/internet-exposure-search-attack-surface-data/
    via_parent: null
  fit: exact
  layer: domain
  why: 'Internet Exposure Search & Attack-Surface Data: Shodan, Censys, GreyNoise, BinaryEdge'
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: findings exported to observability/log platforms (Datadog, Elastic)
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  fit: exact
  layer: domain
  why: container images pulled from registries for image scanning
- capability:
    attribution: Turbo EA
    id: BC-4200.40.10
    key: BC-4200.40.10
    name: Source Code Management
    url: /capabilities/software-construction-management/
    via_parent: Software Construction Management
  fit: exact
  layer: domain
  why: 'Source Code Management: GitHub, GitLab, Bitbucket, Azure Repos / Azure Pipelines'
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.10
    key: AE-250.10.10
    name: Language Package Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  fit: exact
  layer: domain
  why: private package repositories resolved during dependency scanning (Artifactory, Nexus)
- capability:
    attribution: Turbo EA
    id: BC-4210.10
    key: continuous-integration-management
    name: Continuous Integration Management
    url: /capabilities/continuous-integration-management/
    via_parent: null
  fit: exact
  layer: domain
  why: scan steps inside CI pipelines (Jenkins, CircleCI, GitHub Actions, CodePipeline)
- capability:
    attribution: Turbo EA
    id: BC-600.30
    key: it-service-management
    name: IT Service Management
    url: /capabilities/it-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: remediation tickets and CMDB sync with ServiceNow
- capability:
    attribution: API Evangelist extension
    id: AE-160.60
    key: credential-security
    name: Credential Security
    url: /capabilities/credential-security/
    via_parent: null
  fit: exact
  layer: domain
  why: authenticated scanning with credentials from PAM vaults (CyberArk, Delinea, BeyondTrust)
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: identity provider integrations for identity-exposure context (Okta, Ping)
- capability:
    attribution: Turbo EA
    id: BC-1040.40
    key: asset-information-management
    name: Asset Information Management
    url: /capabilities/asset-information-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: asset inventory sources that define what to scan (Axonius, Armis, Jamf)
- capability:
    attribution: Turbo EA
    id: BC-130
    key: compliance-management
    name: Compliance Management
    url: /capabilities/compliance-management/
    via_parent: null
  fit: exact
  layer: common
  why: vulnerability evidence fed to GRC/compliance automation (Vanta, Archer)
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Snyk
      - Tenable
      - Wazuh
      band: exemplar
      in_catalog: true
      kin_score: 67.5
      mcp:
        source: https://github.com/googleapis/mcp-toolbox
        status: verified
      name: Google Cloud
      slug: google-cloud-platform
      sources:
      - https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-iac/cloud-platform-integrations/google-cloud-integration.md
      - https://github.com/wazuh/wazuh/tree/main/wodles/gcloud
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - API Management
      - Cloud Computing
      - Infrastructure
      - Platform-as-a-Service
      tier: observed
      url: /providers/google-cloud-platform/
    - agent_band: agent-ready
      agent_readiness: 29.8
      apps:
      - Snyk
      - Wazuh
      band: exemplar
      in_catalog: true
      kin_score: 80.1
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS CloudTrail
      slug: amazon-cloudtrail
      sources:
      - https://docs.snyk.io/developer-tools/integrations/event-forwarding/aws-cloudtrail-lake.md
      - https://github.com/wazuh/wazuh/tree/main/wodles/aws/buckets_s3
      status: profiled
      tags:
      - Amazon Web Services
      - Audit
      - CloudTrail
      - Compliance
      tier: observed
      url: /providers/amazon-cloudtrail/
    - agent_band: agent-ready
      agent_readiness: 45.0
      apps:
      - Snyk
      - Wazuh
      band: exemplar
      in_catalog: true
      kin_score: 76.0
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Azure
      slug: microsoft-azure
      sources:
      - https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-iac/cloud-platform-integrations/azure-integration-for-cloud-configurations.md
      - https://github.com/wazuh/wazuh/tree/main/wodles/azure
      status: profiled
      tags:
      - Cloud
      - Cloud Computing
      - Enterprise
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure/
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - Nuclei
      - Tenable
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp:
        status: none
      name: Splunk
      slug: splunk
      sources:
      - https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/exporters
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Logging
      - Machine Data
      tier: observed
      url: /providers/splunk/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Snyk
      - Tenable
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS
      slug: amazon-web-services
      sources:
      - https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-iac/cloud-platform-integrations/aws-integration.md
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: declared
      url: /providers/amazon-web-services/
    - agent_band: agent-native
      agent_readiness: 43.4
      apps:
      - Wazuh
      band: exemplar
      in_catalog: true
      kin_score: 77.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon CloudWatch Logs
      slug: amazon-cloudwatch
      sources:
      - https://github.com/wazuh/wazuh/tree/main/wodles/aws/services
      status: profiled
      tags:
      - Amazon Web Services
      - CloudWatch
      - Monitoring
      - Observability
      tier: observed
      url: /providers/amazon-cloudwatch/
    - agent_band: agent-native
      agent_readiness: 42.2
      apps:
      - Wazuh
      band: exemplar
      in_catalog: true
      kin_score: 73.8
      mcp:
        source: https://docs.aws.amazon.com/agent-toolkit/latest/userguide/mcp-server.html
        status: documented
      name: Amazon GuardDuty
      slug: amazon-guardduty
      sources:
      - https://github.com/wazuh/wazuh/tree/main/wodles/aws/buckets_s3
      status: profiled
      tags:
      - Amazon Web Services
      - Anomaly Detection
      - Compliance
      - Machine Learning
      tier: observed
      url: /providers/amazon-guardduty/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Wazuh
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: unknown
      name: Shuffle
      slug: shuffle
      sources:
      - https://github.com/wazuh/wazuh/tree/v4.12.0/integrations
      status: profiled
      tags:
      - Automation
      - SOAR
      - Security
      - Workflows
      tier: observed
      url: /providers/shuffle/
    - agent_band: agent-aware
      agent_readiness: 26.1
      apps:
      - Wazuh
      band: thin
      in_catalog: true
      kin_score: 39.0
      mcp:
        source: https://github.com/VirusTotal/virustotal-mcp
        status: verified
      name: VirusTotal
      slug: virustotal
      sources:
      - https://github.com/wazuh/wazuh/tree/v4.12.0/integrations
      status: profiled
      tags:
      - Anti Malware
      - File Analysis
      - Security
      - Threat Intelligence
      tier: observed
      url: /providers/virustotal/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Wazuh
      band: minimal
      in_catalog: true
      kin_score: 6.2
      mcp:
        status: unchecked
      name: Maltiverse
      slug: maltiverse
      sources:
      - https://github.com/wazuh/wazuh/tree/v4.12.0/integrations
      status: profiled
      tags:
      - Company
      - Cybersecurity
      - Threat Intelligence
      - threat-feed
      tier: observed
      url: /providers/maltiverse/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Wazuh
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: &id001
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
      status: profiled
      tags: &id002
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: declared
      url: /providers/github/
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - Tenable
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare
      slug: cloudflare
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: declared
      url: /providers/cloudflare/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Wazuh
      band: exemplar
      in_catalog: true
      kin_score: 74.6
      mcp:
        source: https://docs.aws.amazon.com/agent-toolkit/latest/userguide/mcp-server.html
        status: documented
      name: Amazon Security Lake
      slug: amazon-security-lake
      sources:
      - https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
      status: profiled
      tags:
      - Amazon Web Services
      - Data Lake
      - SIEM
      - Security
      tier: declared
      url: /providers/amazon-security-lake/
    - agent_band: agent-ready
      agent_readiness: 57.7
      apps:
      - Tenable
      band: exemplar
      in_catalog: true
      kin_score: 71.6
      mcp:
        source: https://mcp.recordedfuture.com/mcp
        status: verified
      name: Recorded Future
      slug: recorded-future
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Brand Intelligence
      - Cybersecurity
      - Intelligence Cloud
      - Threat Intelligence
      tier: declared
      url: /providers/recorded-future/
    - agent_band: agent-ready
      agent_readiness: 42.8
      apps:
      - Wazuh
      band: exemplar
      in_catalog: true
      kin_score: 70.1
      mcp:
        source: https://learn.microsoft.com/en-us/microsoft-agent-365/tooling-servers-overview
        status: verified
      name: Office 365
      slug: microsoft-office-365
      sources:
      - https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
      status: profiled
      tags:
      - Cloud
      - Collaboration
      - Enterprise
      - Microsoft
      tier: declared
      url: /providers/microsoft-office-365/
    - agent_band: agent-ready
      agent_readiness: 39.0
      apps:
      - Wazuh
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Graph
      slug: microsoft-graph
      sources:
      - https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
      status: profiled
      tags:
      - Azure AD
      - Collaboration
      - Contacts
      - Microsoft Graph
      tier: declared
      url: /providers/microsoft-graph/
    - agent_band: agent-ready
      agent_readiness: 38.5
      apps:
      - Tenable
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/PaloAltoNetworks/prisma-airs-mcp
        status: verified
      name: Palo Alto Networks
      slug: palo-alto-networks
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Cloud Security
      - Cybersecurity
      - Firewall
      - Network Security
      tier: declared
      url: /providers/palo-alto-networks/
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - Tenable
      band: exemplar
      in_catalog: true
      kin_score: 67.2
      mcp:
        source: https://github.com/CrowdStrike/falcon-mcp
        status: verified
      name: CrowdStrike
      slug: crowdstrike
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Cybersecurity
      - Endpoint Detection and Response
      - Endpoint Security
      - Threat Intelligence
      tier: declared
      url: /providers/crowdstrike/
    - agent_band: agent-native
      agent_readiness: 49.8
      apps:
      - Wazuh
      band: exemplar
      in_catalog: true
      kin_score: 66.5
      mcp:
        status: unknown
      name: AWS Security Hub
      slug: aws-security-hub
      sources:
      - https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
      status: profiled
      tags:
      - Cloud Security Posture Management
      - Compliance
      - Findings
      - Security
      tier: declared
      url: /providers/aws-security-hub/
    - agent_band: agent-ready
      agent_readiness: 32.4
      apps:
      - Wazuh
      band: developing
      in_catalog: true
      kin_score: 51.7
      mcp: &id003
        source: https://github.com/docker/mcp-gateway
        status: verified
      name: Docker
      slug: docker
      sources:
      - https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
      status: profiled
      tags: &id004
      - Cloud
      - Containers
      - DevOps
      - Developer Tools
      tier: declared
      url: /providers/docker/
    - agent_band: agent-ready
      agent_readiness: 40.6
      apps:
      - Tenable
      band: developing
      in_catalog: true
      kin_score: 47.6
      mcp:
        source: https://www.anomali.com/llms.txt
        status: documented
      name: Anomali
      slug: anomali
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Company
      - Cybersecurity
      - Enterprise
      - Threat Intelligence
      tier: declared
      url: /providers/anomali/
    - agent_band: agent-ready
      agent_readiness: 48.2
      apps:
      - Tenable
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        source: https://docs.sumologic.com/docs/search/mobot/
        status: documented
      name: Sumo Logic
      slug: sumo-logic
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Logging
      - Monitoring
      - Observability
      - Security
      tier: declared
      url: /providers/sumo-logic/
    - agent_band: agent-ready
      agent_readiness: 29.0
      apps:
      - Tenable
      band: thin
      in_catalog: true
      kin_score: 37.0
      mcp:
        source: https://www.tines.com/docs/mcp-server/
        status: verified
      name: Tines
      slug: tines
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - No-Code
      - Security Automation
      - Security Operations
      - Workflow Automation
      tier: declared
      url: /providers/tines/
    - agent_band: agent-aware
      agent_readiness: 23.6
      apps:
      - Tenable
      band: thin
      in_catalog: true
      kin_score: 34.6
      mcp:
        source: https://github.com/zscaler/zscaler-mcp-server
        status: verified
      name: Zscaler
      slug: zscaler
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Cloud Security
      - Network Security
      - SASE
      - Zero Trust
      tier: declared
      url: /providers/zscaler/
    - agent_band: agent-aware
      agent_readiness: 21.4
      apps:
      - Tenable
      band: thin
      in_catalog: true
      kin_score: 32.9
      mcp:
        source: https://mcp.swimlane.com/mcp
        status: verified
      name: Swimlane
      slug: swimlane
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Automation
      - Incident Response
      - SOAR
      - Security Orchestration
      tier: declared
      url: /providers/swimlane/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Tenable
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: Fortinet
      slug: fortinet
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Cloud Security
      - Cybersecurity
      - Firewall
      - Networking
      tier: declared
      url: /providers/fortinet/
    - agent_band: agent-aware
      agent_readiness: 13.3
      apps:
      - Tenable
      band: emerging
      in_catalog: true
      kin_score: 22.6
      mcp:
        source: https://torq.io/blog/model-context-protocol
        status: documented
      name: Torq
      slug: torq
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Hyper-Automation
      - SOAR
      - Security Automation
      - Security Orchestration
      tier: declared
      url: /providers/torq/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Tenable
      band: emerging
      in_catalog: true
      kin_score: 22.0
      mcp:
        source: https://github.com/Sentinel-One/purple-mcp
        status: verified
      name: SentinelOne
      slug: sentinelone
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Endpoint Detection and Response
      - Endpoint Security
      - Security
      - XDR
      tier: declared
      url: /providers/sentinelone/
    - agent_band: null
      agent_readiness: null
      apps:
      - Tenable
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Google SecOps
      slug: google-secops
      sources:
      - https://www.tenable.com/partners/technology
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-620.40
      key: vulnerability-management
      name: Vulnerability Management
      url: /capabilities/vulnerability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.8
      apps:
      - OWASP Dependency-Track
      - Tenable
      band: exemplar
      in_catalog: true
      kin_score: 80.8
      mcp:
        source: https://github.com/snyk/studio-mcp
        status: verified
      name: Snyk
      slug: snyk
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/vuln-analysis/snyk
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Application Security
      - DevSecOps
      - Security
      - Vulnerability Management
      tier: observed
      url: /providers/snyk/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - OWASP Dependency-Track
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: *id001
      name: GitHub Advisory Database
      slug: github
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/vuln-data-source/github
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - DefectDojo
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        source: https://github.com/SonarSource/sonarqube-mcp-server
        status: verified
      name: SonarQube
      slug: sonarqube
      sources:
      - https://github.com/DefectDojo/django-DefectDojo/tree/master/dojo/tools
      status: profiled
      tags:
      - Code Quality
      - DevOps
      - Developer Tools
      - Security
      tier: observed
      url: /providers/sonarqube/
    - agent_band: agent-native
      agent_readiness: 42.9
      apps:
      - Wazuh
      band: exemplar
      in_catalog: true
      kin_score: 71.1
      mcp:
        status: none
      name: Amazon Inspector
      slug: amazon-inspector
      sources:
      - https://github.com/wazuh/wazuh/tree/main/wodles/aws/services
      status: profiled
      tags:
      - Amazon Web Services
      - Compliance
      - Container Security
      - EC2
      tier: observed
      url: /providers/amazon-inspector/
    - agent_band: agent-ready
      agent_readiness: 33.4
      apps:
      - OWASP Dependency-Track
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        source: https://github.com/sonatype/dependency-management-mcp-server
        status: verified
      name: Sonatype OSS Index
      slug: sonatype
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/vuln-analysis/oss-index
      status: profiled
      tags:
      - SBOM
      - Security
      - Software Supply Chain
      - Vulnerability Management
      tier: observed
      url: /providers/sonatype/
    - agent_band: agent-ready
      agent_readiness: 38.4
      apps:
      - OWASP Dependency-Track
      band: strong
      in_catalog: true
      kin_score: 62.1
      mcp:
        source: https://github.com/Checkmarx/cx-agentic-ai
        status: verified
      name: Checkmarx
      slug: checkmarx
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/vuln-analysis/checkmarx
      status: profiled
      tags:
      - Application Security
      - Code Analysis
      - DevSecOps
      - SAST
      tier: observed
      url: /providers/checkmarx/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - OWASP Dependency-Track
      band: strong
      in_catalog: true
      kin_score: 58.3
      mcp:
        source: https://github.com/vulncheck-oss/mcp
        status: verified
      name: VulnCheck
      slug: vulncheck
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/kev-data-source/builtin
      status: profiled
      tags:
      - Company
      - Exploit Intelligence
      - Security
      - Vulnerability Intelligence
      tier: observed
      url: /providers/vulncheck/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - OWASP Dependency-Track
      band: strong
      in_catalog: true
      kin_score: 57.0
      mcp:
        source: https://github.com/fortify/fcli
        status: verified
      name: Fortify SSC
      slug: fortify
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/apiserver/src/main/java/org/dependencytrack/integrations
      status: profiled
      tags:
      - Application Security
      - DAST
      - DevSecOps
      - SAST
      tier: observed
      url: /providers/fortify/
    - agent_band: agent-ready
      agent_readiness: 39.0
      apps:
      - OWASP Dependency-Track
      band: developing
      in_catalog: true
      kin_score: 52.2
      mcp:
        status: unchecked
      name: DefectDojo
      slug: defectdojo
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/apiserver/src/main/java/org/dependencytrack/integrations
      status: profiled
      tags:
      - Application Security
      - Compliance
      - DevSecOps
      - Vulnerability Management
      tier: observed
      url: /providers/defectdojo/
    - agent_band: agent-aware
      agent_readiness: 18.1
      apps:
      - DefectDojo
      band: developing
      in_catalog: true
      kin_score: 48.7
      mcp:
        source: https://github.com/blackducksoftware/mcp-server
        status: verified
      name: Black Duck
      slug: black-duck
      sources:
      - https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
      status: profiled
      tags:
      - Application Security
      - Company
      - Enterprise
      - Software Composition Analysis
      tier: observed
      url: /providers/black-duck/
    - agent_band: agent-aware
      agent_readiness: 20.1
      apps:
      - DefectDojo
      band: developing
      in_catalog: true
      kin_score: 46.1
      mcp:
        status: unchecked
      name: Vulners
      slug: vulners
      sources:
      - https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
      status: profiled
      tags:
      - Intelligence
      - Platform
      - Security
      - Vulnerabilities
      tier: observed
      url: /providers/vulners/
    - agent_band: agent-aware
      agent_readiness: 28.0
      apps:
      - OWASP Dependency-Track
      band: developing
      in_catalog: true
      kin_score: 43.8
      mcp:
        status: none
      name: Kenna Security
      slug: kenna-security
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/apiserver/src/main/java/org/dependencytrack/integrations
      status: profiled
      tags:
      - Company
      - Cybersecurity
      - Risk-Based Prioritization
      - Vulnerability Management
      tier: observed
      url: /providers/kenna-security/
    - agent_band: agent-ready
      agent_readiness: 31.7
      apps:
      - OWASP Dependency-Track
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: NVD
      slug: nvd
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/vuln-data-source/nvd
      status: profiled
      tags:
      - CPE
      - CVE
      - Security
      - Vulnerabilities
      tier: observed
      url: /providers/nvd/
    - agent_band: agent-ready
      agent_readiness: 29.4
      apps:
      - OWASP Dependency-Track
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        source: https://github.com/aquasecurity/trivy-mcp
        status: verified
      name: Trivy
      slug: trivy
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/vuln-analysis/trivy
      status: profiled
      tags:
      - Containers
      - Kubernetes
      - SBOM
      - Security
      tier: observed
      url: /providers/trivy/
    - agent_band: agent-aware
      agent_readiness: 24.0
      apps:
      - OWASP Dependency-Track
      band: thin
      in_catalog: true
      kin_score: 28.5
      mcp:
        status: unchecked
      name: FIRST EPSS
      slug: first-org
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/apiserver/src/main/java/org/dependencytrack/epss
      status: profiled
      tags:
      - Community
      - Security
      - Standards
      - Training
      tier: observed
      url: /providers/first-org/
    - agent_band: agent-ready
      agent_readiness: 29.2
      apps:
      - OWASP Dependency-Track
      band: emerging
      in_catalog: true
      kin_score: 24.8
      mcp:
        source: https://flashpoint.io/resources/product-updates/introducing-the-flashpoint-mcp-server/
        status: verified
      name: VulnDB (Flashpoint)
      slug: flashpoint
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/vuln-analysis/vuln-db
      status: profiled
      tags:
      - Company
      - Cybersecurity
      - Security
      - Threat Intelligence
      tier: observed
      url: /providers/flashpoint/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - DefectDojo
      band: emerging
      in_catalog: true
      kin_score: 23.5
      mcp:
        status: unknown
      name: Cobalt (pentest)
      slug: cobalt-io
      sources:
      - https://github.com/DefectDojo/django-DefectDojo/tree/master/dojo/tools
      status: profiled
      tags:
      - Company
      - Offensive Security
      - Penetration Testing
      - Security
      tier: observed
      url: /providers/cobalt-io/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - DefectDojo
      band: emerging
      in_catalog: true
      kin_score: 15.8
      mcp:
        status: unknown
      name: Edgescan
      slug: edgescan
      sources:
      - https://github.com/DefectDojo/django-DefectDojo/tree/master/dojo/tools
      status: profiled
      tags:
      - API Testing
      - Company
      - Security
      - Vulnerability Management
      tier: observed
      url: /providers/edgescan/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - DefectDojo
      band: minimal
      in_catalog: true
      kin_score: 10.7
      mcp:
        source: https://docs.bugcrowd.com/customers/ai-capabilities/ai-connect/
        status: documented
      name: Bugcrowd
      slug: bugcrowd
      sources:
      - https://github.com/DefectDojo/django-DefectDojo/tree/master/dojo/tools
      status: profiled
      tags:
      - Cybersecurity
      - Public APIs
      - Security
      - Vulnerability Management
      tier: observed
      url: /providers/bugcrowd/
    - agent_band: agent-aware
      agent_readiness: 5.7
      apps:
      - OWASP Dependency-Track
      band: minimal
      in_catalog: true
      kin_score: 9.1
      mcp:
        status: unchecked
      name: OSV (Google)
      slug: osv-dev
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/vuln-data-source/osv
      status: profiled
      tags:
      - Open Source
      - Remediation
      - Scanner
      - Vulnerability Database
      tier: observed
      url: /providers/osv-dev/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OWASP Dependency-Track
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        status: unchecked
      name: ENISA EUVD
      slug: enisa
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/kev-data-source/builtin
      status: profiled
      tags:
      - EU
      - Public Service
      - Security
      - Vulnerabilities
      tier: observed
      url: /providers/enisa/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OWASP Dependency-Track
      band: minimal
      in_catalog: true
      kin_score: 2.5
      mcp:
        status: unchecked
      name: JVN (Japan Vulnerability Notes)
      slug: jvn
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/vuln-data-source/jvn
      status: profiled
      tags:
      - Company
      - Japan
      - Security
      - Vulnerabilities
      tier: observed
      url: /providers/jvn/
    - agent_band: null
      agent_readiness: null
      apps:
      - OWASP Dependency-Track
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: CISA KEV
      slug: cisa
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/kev-data-source/builtin
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 29.4
      apps:
      - Tenable
      band: strong
      in_catalog: true
      kin_score: 58.3
      mcp:
        status: none
      name: Veracode
      slug: veracode
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Application Security
      - DAST
      - SAST
      - Software Composition Analysis
      tier: declared
      url: /providers/veracode/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - Tenable
      band: thin
      in_catalog: true
      kin_score: 34.4
      mcp:
        status: unknown
      name: Bitsight
      slug: bitsight
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Company
      - Cyber Risk
      - Security
      - Security Ratings
      tier: declared
      url: /providers/bitsight/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Tenable
      band: thin
      in_catalog: true
      kin_score: 32.2
      mcp:
        source: https://app.armorcode.com/mcp
        status: verified
      name: ArmorCode
      slug: armorcode
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Application Security
      - Company
      - Security
      - Vulnerability Management
      tier: declared
      url: /providers/armorcode/
    - agent_band: agent-aware
      agent_readiness: 5.3
      apps:
      - Tenable
      band: emerging
      in_catalog: true
      kin_score: 24.7
      mcp:
        source: https://docs.brinqa.com/docs/brinqa-iq-mcp
        status: verified
      name: Brinqa
      slug: brinqa
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Company
      - Cybersecurity
      - Exposure Management
      - Vulnerability Management
      tier: declared
      url: /providers/brinqa/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Tenable
      band: emerging
      in_catalog: true
      kin_score: 15.3
      mcp:
        source: https://www.wiz.io/blog/introducing-mcp-server-for-wiz
        status: verified
      name: Wiz
      slug: wiz
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - CNAPP
      - CSPM
      - Cloud Security
      - Vulnerability Management
      tier: declared
      url: /providers/wiz/
    - agent_band: agent-aware
      agent_readiness: 12.0
      apps:
      - Tenable
      band: minimal
      in_catalog: true
      kin_score: 5.5
      mcp:
        source: https://github.com/Hacker0x01/hackerone-graphql-mcp-server
        status: verified
      name: HackerOne
      slug: hackerone
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Cybersecurity
      - Public APIs
      - Security
      - Vulnerability Management
      tier: declared
      url: /providers/hackerone/
    - agent_band: null
      agent_readiness: null
      apps:
      - Tenable
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: SecurityScorecard
      slug: securityscorecard
      sources:
      - https://www.tenable.com/partners/technology
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.5
      apps:
      - Snyk
      - Trivy
      band: exemplar
      in_catalog: true
      kin_score: 75.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon ECR
      slug: amazon-ecr
      sources:
      - https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-amazon-elastic-container-registry-ecr.md
      - https://github.com/aquasecurity/trivy/tree/main/pkg/fanal/image/registry
      status: profiled
      tags:
      - Amazon Web Services
      - Container Images
      - Container Registry
      - Containers
      tier: observed
      url: /providers/amazon-ecr/
    - agent_band: agent-ready
      agent_readiness: 28.8
      apps:
      - Snyk
      - Trivy
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://learn.microsoft.com/en-us/azure/developer/azure-mcp-server/tools/azure-container-registry
        status: verified
      name: Azure Container Registry
      slug: azure-container-registry
      sources:
      - https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-microsoft-azure-container-registry-acr.md
      - https://github.com/aquasecurity/trivy/tree/main/pkg/fanal/image/registry
      status: profiled
      tags:
      - Container Images
      - Containers
      - Docker
      - Microsoft Azure
      tier: observed
      url: /providers/azure-container-registry/
    - agent_band: agent-ready
      agent_readiness: 37.7
      apps:
      - Snyk
      - Trivy
      band: strong
      in_catalog: true
      kin_score: 65.4
      mcp:
        status: none
      name: Google Artifact Registry / GCR
      slug: google-artifact-registry
      sources:
      - https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-google-artifact-registry-gar.md
      - https://github.com/aquasecurity/trivy/tree/main/pkg/fanal/image/registry
      status: profiled
      tags:
      - Artifacts
      - Containers
      - Google Cloud
      - Packages
      tier: observed
      url: /providers/google-artifact-registry/
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - Snyk
      - Trivy
      band: strong
      in_catalog: true
      kin_score: 61.8
      mcp:
        source: https://github.com/github/github-mcp-server
        status: documented
      name: GitHub Container Registry
      slug: github-container-registry
      sources:
      - https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-github-container-registry.md
      - https://github.com/aquasecurity/trivy-db
      status: profiled
      tags:
      - Container Images
      - Containers
      - GitHub
      - Packages
      tier: declared
      url: /providers/github-container-registry/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Tenable
      band: exemplar
      in_catalog: true
      kin_score: 76.8
      mcp: &id005
        source: https://github.com/jfrog/jfrog-mcp-server
        status: verified
      name: JFrog
      slug: jfrog
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags: &id006
      - Artifactory
      - CI/CD
      - Container Registry
      - Developer Tools
      tier: declared
      url: /providers/jfrog/
    - agent_band: agent-ready
      agent_readiness: 38.8
      apps:
      - Snyk
      band: strong
      in_catalog: true
      kin_score: 62.5
      mcp:
        status: none
      name: Harbor
      slug: goharbor
      sources:
      - https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-harbor-container-registry.md
      status: profiled
      tags:
      - Artifacts
      - Container Registry
      - Containers
      - Vulnerability Scanning
      tier: declared
      url: /providers/goharbor/
    - agent_band: agent-ready
      agent_readiness: 32.4
      apps:
      - Tenable
      band: developing
      in_catalog: true
      kin_score: 51.7
      mcp: *id003
      name: Docker
      slug: docker
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags: *id004
      tier: declared
      url: /providers/docker/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Snyk
      band: developing
      in_catalog: true
      kin_score: 48.7
      mcp:
        source: https://github.com/docker/hub-mcp
        status: verified
      name: Docker Hub
      slug: docker-hub
      sources:
      - https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-docker-hub.md
      status: profiled
      tags:
      - Containers
      - DevOps
      - Docker
      - Registry
      tier: declared
      url: /providers/docker-hub/
    - agent_band: agent-aware
      agent_readiness: 27.0
      apps:
      - Snyk
      band: thin
      in_catalog: true
      kin_score: 39.0
      mcp:
        source: https://github.com/quay/quay-mcp-server
        status: verified
      name: Quay
      slug: quay
      sources:
      - https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-quay-container-registry.md
      status: profiled
      tags:
      - Container Images
      - Containers
      - Red Hat
      - Registry
      tier: declared
      url: /providers/quay/
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Snyk
      band: thin
      in_catalog: true
      kin_score: 35.2
      mcp:
        status: unknown
      name: GitLab Container Registry
      slug: gitlab-container-registry
      sources:
      - https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-gitlab-container-registry.md
      status: profiled
      tags:
      - Container Images
      - Containers
      - GitLab
      - Registry
      tier: declared
      url: /providers/gitlab-container-registry/
    - agent_band: null
      agent_readiness: null
      apps:
      - Snyk
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: DigitalOcean Container Registry
      slug: digitalocean
      sources:
      - https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-digitalocean.md
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-941
      key: AE-941
      name: Internet Exposure Search & Attack-Surface Data
      url: /capabilities/internet-exposure-search-attack-surface-data/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.1
      apps:
      - Nuclei
      band: strong
      in_catalog: true
      kin_score: 66.2
      mcp:
        source: https://docs.censys.com/docs/platform-mcp-server
        status: verified
      name: Censys
      slug: censys
      sources:
      - https://github.com/projectdiscovery/uncover/tree/main/sources/agent
      status: profiled
      tags:
      - Attack Surface Management
      - Internet Intelligence
      - Security
      - Threat Hunting
      tier: observed
      url: /providers/censys/
    - agent_band: agent-ready
      agent_readiness: 28.6
      apps:
      - Nuclei
      band: strong
      in_catalog: true
      kin_score: 61.8
      mcp:
        source: https://github.com/GreyNoise-Intelligence/greynoise-mcp-server
        status: verified
      name: GreyNoise
      slug: greynoise
      sources:
      - https://github.com/projectdiscovery/uncover/tree/main/sources/agent
      status: profiled
      tags:
      - Cybersecurity
      - IP Reputation
      - Security
      - Threat Intelligence
      tier: observed
      url: /providers/greynoise/
    - agent_band: agent-aware
      agent_readiness: 22.4
      apps:
      - Nuclei
      band: strong
      in_catalog: true
      kin_score: 61.6
      mcp:
        status: unknown
      name: Shodan
      slug: shodan
      sources:
      - https://github.com/projectdiscovery/uncover/tree/main/sources/agent
      status: profiled
      tags:
      - Devices
      - Internet
      - Search
      - Security
      tier: observed
      url: /providers/shodan/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Nuclei
      band: developing
      in_catalog: true
      kin_score: 41.9
      mcp:
        status: unchecked
      name: ONYPHE
      slug: onyphe
      sources:
      - https://github.com/projectdiscovery/uncover/tree/main/sources/agent
      status: profiled
      tags:
      - Attack Surface Management
      - Internet Scanning
      - Passive DNS
      - Threat Intelligence
      tier: observed
      url: /providers/onyphe/
    - agent_band: agent-aware
      agent_readiness: 19.3
      apps:
      - Nuclei
      band: thin
      in_catalog: true
      kin_score: 36.3
      mcp:
        status: unchecked
      name: Netlas
      slug: netlas
      sources:
      - https://github.com/projectdiscovery/uncover/tree/main/sources/agent
      status: profiled
      tags:
      - Company
      - Internet Scanning
      - OSINT
      - Security
      tier: observed
      url: /providers/netlas/
    - agent_band: agent-aware
      agent_readiness: 17.1
      apps:
      - Nuclei
      band: thin
      in_catalog: true
      kin_score: 30.1
      mcp:
        status: unchecked
      name: ZoomEye
      slug: zoomeye
      sources:
      - https://github.com/projectdiscovery/uncover/tree/main/sources/agent
      status: profiled
      tags:
      - Asset Discovery
      - Company
      - Cybersecurity
      - Search Engines
      tier: observed
      url: /providers/zoomeye/
    - agent_band: agent-aware
      agent_readiness: 12.0
      apps:
      - Nuclei
      band: emerging
      in_catalog: true
      kin_score: 19.7
      mcp:
        status: unchecked
      name: Criminal IP
      slug: criminal-ip
      sources:
      - https://github.com/projectdiscovery/uncover/tree/main/sources/agent
      status: profiled
      tags:
      - Company
      - Cybersecurity
      - Data
      - Threat Intelligence
      tier: observed
      url: /providers/criminal-ip/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Nuclei
      band: minimal
      in_catalog: true
      kin_score: 5.4
      mcp:
        status: unknown
      name: BinaryEdge
      slug: binaryedge
      sources:
      - https://github.com/projectdiscovery/uncover/tree/main/sources/agent
      status: profiled
      tags:
      - Public APIs
      - Security
      tier: observed
      url: /providers/binaryedge/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Nuclei
      band: minimal
      in_catalog: true
      kin_score: 4.0
      mcp:
        status: unchecked
      name: FOFA
      slug: fofa
      sources:
      - https://github.com/projectdiscovery/uncover/tree/main/sources/agent
      status: profiled
      tags:
      - Company
      - Cybersecurity
      - Search Engines
      - Threat Intelligence
      tier: observed
      url: /providers/fofa/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Nuclei
      band: minimal
      in_catalog: true
      kin_score: 2.2
      mcp:
        status: unchecked
      name: Quake (Qihoo 360)
      slug: quake-360
      sources:
      - https://github.com/projectdiscovery/uncover/tree/main/sources/agent
      status: profiled
      tags:
      - Asset Mapping
      - Company
      - Cybersecurity
      - Security
      tier: observed
      url: /providers/quake-360/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Nuclei
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        status: unchecked
      name: Hunter (Qi An Xin)
      slug: hunter-qianxin
      sources:
      - https://github.com/projectdiscovery/uncover/tree/main/sources/agent
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/hunter-qianxin/
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.5
      apps:
      - Snyk
      - Tenable
      band: thin
      in_catalog: true
      kin_score: 39.0
      mcp:
        source: https://github.com/jenkinsci/mcp-server-plugin
        status: verified
      name: Jenkins
      slug: jenkins
      sources:
      - https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/jenkins-plugin-integration-with-snyk.md
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Automation
      - Build Server
      - CI/CD
      - Continuous Delivery
      tier: declared
      url: /providers/jenkins/
    - agent_band: agent-ready
      agent_readiness: 48.0
      apps:
      - Snyk
      band: exemplar
      in_catalog: true
      kin_score: 82.6
      mcp:
        source: https://github.com/github/github-mcp-server
        status: documented
      name: GitHub Actions
      slug: github-actions
      sources:
      - https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/github-actions-for-snyk-setup-and-checking-for-vulnerabilities.md
      status: profiled
      tags:
      - CI/CD
      - Continuous Deployment
      - Continuous Integration
      - DevOps
      tier: declared
      url: /providers/github-actions/
    - agent_band: agent-ready
      agent_readiness: 56.3
      apps:
      - Snyk
      band: exemplar
      in_catalog: true
      kin_score: 73.5
      mcp:
        source: https://github.com/CircleCI-Public/mcp-server-circleci
        status: verified
      name: CircleCI
      slug: circleci
      sources:
      - https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/circleci-integration-using-a-snyk-orb.md
      status: profiled
      tags:
      - CI/CD
      - Continuous Deployment
      - Continuous Integration
      - DevOps
      tier: declared
      url: /providers/circleci/
    - agent_band: agent-aware
      agent_readiness: 27.8
      apps:
      - Snyk
      band: exemplar
      in_catalog: true
      kin_score: 71.6
      mcp:
        source: https://docs.aws.amazon.com/agent-toolkit/latest/userguide/mcp-server.html
        status: documented
      name: AWS CodePipeline
      slug: amazon-codepipeline
      sources:
      - https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/aws-codepipeline-integration-by-adding-a-snyk-scan-stage.md
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - CI/CD
      - Continuous Delivery
      tier: declared
      url: /providers/amazon-codepipeline/
    - agent_band: agent-ready
      agent_readiness: 34.3
      apps:
      - Snyk
      band: developing
      in_catalog: true
      kin_score: 51.1
      mcp:
        source: https://www.atlassian.com/blog/bitbucket/connect-the-redesigned-atlassian-mcp-server-to-your-agentic-pipelines
        status: documented
      name: Bitbucket Pipelines
      slug: bitbucket-pipelines
      sources:
      - https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/bitbucket-pipelines-integration-using-a-snyk-pipe.md
      status: profiled
      tags:
      - Atlassian
      - CI/CD
      - DevOps
      - Pipelines
      tier: declared
      url: /providers/bitbucket-pipelines/
    - agent_band: agent-ready
      agent_readiness: 29.7
      apps:
      - Snyk
      band: developing
      in_catalog: true
      kin_score: 42.5
      mcp:
        source: https://github.com/hashicorp/terraform-mcp-server
        status: verified
      name: Terraform Cloud
      slug: terraform
      sources:
      - https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/terraform-cloud-integration-for-snyk-iac-using-run-tasks.md
      status: profiled
      tags:
      - Cloud Infrastructure
      - DevOps
      - Infrastructure as Code
      - Open Source
      tier: declared
      url: /providers/terraform/
    - agent_band: agent-aware
      agent_readiness: 18.8
      apps:
      - Tenable
      band: thin
      in_catalog: true
      kin_score: 29.4
      mcp:
        source: https://github.com/hashicorp/terraform-mcp-server
        status: verified
      name: HashiCorp
      slug: hashicorp
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Cloud
      - DevOps
      - Infrastructure
      - Platform
      tier: declared
      url: /providers/hashicorp/
  - capability:
      attribution: Turbo EA
      id: BC-4200.40.10
      key: BC-4200.40.10
      name: Source Code Management
      url: /capabilities/software-construction-management/
      via_parent: Software Construction Management
    providers:
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Snyk
      - Tenable
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp: &id007
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://docs.snyk.io/developer-tools/integrations/scm-integrations/organization-level-integrations/gitlab.md
      - https://www.tenable.com/partners/technology
      status: profiled
      tags: &id008
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: declared
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Snyk
      - Tenable
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: *id001
      name: GitHub
      slug: github
      sources:
      - https://docs.snyk.io/developer-tools/integrations/scm-integrations/organization-level-integrations/github.md
      - https://www.tenable.com/partners/technology
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 37.7
      apps:
      - Snyk
      band: exemplar
      in_catalog: true
      kin_score: 81.9
      mcp:
        source: https://github.com/microsoft/azure-devops-mcp
        status: verified
      name: Azure Repos / Azure Pipelines
      slug: microsoft-azure-devops
      sources:
      - https://docs.snyk.io/developer-tools/integrations/scm-integrations/organization-level-integrations/azure-repositories-tfs.md
      status: profiled
      tags:
      - Agile
      - CI/CD
      - DevOps
      - Developer Tools
      tier: declared
      url: /providers/microsoft-azure-devops/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Snyk
      band: exemplar
      in_catalog: true
      kin_score: 71.9
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Bitbucket
      slug: bitbucket
      sources:
      - https://docs.snyk.io/developer-tools/integrations/scm-integrations/organization-level-integrations/bitbucket-cloud.md
      status: profiled
      tags:
      - Atlassian
      - CI/CD
      - Code Collaboration
      - Code Review
      tier: declared
      url: /providers/bitbucket/
  - capability:
      attribution: Turbo EA
      id: BC-1040.40
      key: asset-information-management
      name: Asset Information Management
      url: /capabilities/asset-information-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.3
      apps:
      - Tenable
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        status: none
      name: Jamf
      slug: jamf
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Apple Device Management
      - Company
      - Endpoint Security
      - MDM
      tier: declared
      url: /providers/jamf/
    - agent_band: agent-ready
      agent_readiness: 48.2
      apps:
      - Tenable
      band: strong
      in_catalog: true
      kin_score: 55.9
      mcp:
        source: https://github.com/ArmisSecurity/armis-appsec-mcp
        status: verified
      name: Armis
      slug: armis
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Company
      - Cybersecurity
      - Defense Government
      - Security
      tier: declared
      url: /providers/armis/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Tenable
      band: developing
      in_catalog: true
      kin_score: 48.4
      mcp:
        source: https://docs.axonius.com/docs/axonius-mcp-server
        status: verified
      name: Axonius
      slug: axonius
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Asset Management
      - Cybersecurity
      - SaaS Management
      - SaaS Security
      tier: declared
      url: /providers/axonius/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.60
      key: credential-security
      name: Credential Security
      url: /capabilities/credential-security/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.3
      apps:
      - Tenable
      band: exemplar
      in_catalog: true
      kin_score: 68.6
      mcp:
        source: https://github.com/DelineaXPM/delinea-mcp
        status: verified
      name: Delinea
      slug: delinea
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - DevOps
      - Identity Security
      - Privileged Access Management
      - Secrets Management
      tier: declared
      url: /providers/delinea/
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - Tenable
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        source: https://docs.beyondtrust.com/bt-docs/docs/mcp-server-details
        status: verified
      name: BeyondTrust
      slug: beyondtrust
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Access
      - Compliance
      - Credentials
      - Identity and Access Management
      tier: declared
      url: /providers/beyondtrust/
    - agent_band: agent-aware
      agent_readiness: 18.8
      apps:
      - Tenable
      band: thin
      in_catalog: true
      kin_score: 32.4
      mcp:
        source: https://lp.cyberark.com/sca-mcp.html
        status: verified
      name: CyberArk
      slug: cyberark
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Authentication
      - Cloud Security
      - Conjur
      - Credential Vault
      tier: declared
      url: /providers/cyberark/
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.10
      key: AE-250.10.10
      name: Language Package Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Snyk
      band: exemplar
      in_catalog: true
      kin_score: 76.8
      mcp: *id005
      name: JFrog Artifactory
      slug: jfrog
      sources:
      - https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-open-source/package-repository-integrations/artifactory-package-repository-connection-setup.md
      status: profiled
      tags: *id006
      tier: declared
      url: /providers/jfrog/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Snyk
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        source: https://github.com/sonatype/dependency-management-mcp-server
        status: verified
      name: Sonatype Nexus Repository
      slug: nexus
      sources:
      - https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-open-source/package-repository-integrations/nexus-repository-manager-connection-setup.md
      status: profiled
      tags:
      - Artifact Management
      - DevOps
      - Docker
      - Maven
      tier: declared
      url: /providers/nexus/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4200
      key: software-product-engineering-management
      name: Software Product Engineering Management
      url: /capabilities/software-product-engineering-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 64.4
      apps:
      - DefectDojo
      - Nuclei
      - OWASP Dependency-Track
      - Snyk
      - Tenable
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://docs.snyk.io/developer-tools/integrations/jira-and-slack-integrations/jira-integration.md
      - https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
      - https://github.com/DependencyTrack/dependency-track/tree/main/notification/publishing
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: observed
      url: /providers/jira/
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - DefectDojo
      - Nuclei
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp: *id007
      name: GitLab
      slug: gitlab
      sources:
      - https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
      - https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/trackers
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - DefectDojo
      - Nuclei
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: *id001
      name: GitHub
      slug: github
      sources:
      - https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
      - https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/trackers
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Nuclei
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        source: https://gitea.com/gitea/gitea-mcp
        status: verified
      name: Gitea
      slug: gitea
      sources:
      - https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/trackers
      status: profiled
      tags:
      - CI/CD
      - DevOps
      - Gitea
      - Version Control
      tier: observed
      url: /providers/gitea/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - Nuclei
      band: developing
      in_catalog: true
      kin_score: 39.6
      mcp:
        source: https://linear.app/docs/mcp
        status: verified
      name: Linear
      slug: linear-app
      sources:
      - https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/trackers
      status: profiled
      tags:
      - Issue Tracking
      - Productivity
      - Project Management
      - Software-as-a-Service
      tier: observed
      url: /providers/linear-app/
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
      - DefectDojo
      - OWASP Dependency-Track
      - Snyk
      - Tenable
      - Wazuh
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://docs.snyk.io/developer-tools/integrations/jira-and-slack-integrations/slack-app.md
      - https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
      - https://github.com/DependencyTrack/dependency-track/tree/main/notification/publishing
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
      - DefectDojo
      - OWASP Dependency-Track
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://github.com/DefectDojo/django-DefectDojo/blob/master/dojo/notifications/models.py
      - https://github.com/DependencyTrack/dependency-track/tree/main/notification/publishing
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: observed
      url: /providers/microsoft-teams/
    - agent_band: agent-ready
      agent_readiness: 61.8
      apps:
      - OWASP Dependency-Track
      band: strong
      in_catalog: true
      kin_score: 66.1
      mcp:
        source: https://github.com/WebexSamples/webex-messaging-mcp-server
        status: verified
      name: Webex
      slug: webex
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/notification/publishing
      status: profiled
      tags:
      - Calling
      - Collaboration
      - Communications
      - Enterprise
      tier: observed
      url: /providers/webex/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - OWASP Dependency-Track
      band: thin
      in_catalog: true
      kin_score: 37.0
      mcp:
        source: https://github.com/mattermost/mmctl-mcp
        status: verified
      name: Mattermost
      slug: mattermost
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/notification/publishing
      status: profiled
      tags:
      - Collaboration
      - Messaging
      - Open Source
      - Team Chat
      tier: observed
      url: /providers/mattermost/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Nuclei
      - Tenable
      band: exemplar
      in_catalog: true
      kin_score: 78.4
      mcp:
        source: https://www.elastic.co/docs/solutions/search/mcp
        status: verified
      name: Elasticsearch
      slug: elastic
      sources:
      - https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/exporters
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Analytics
      - Observability
      - Search
      - Security
      tier: observed
      url: /providers/elastic/
    - agent_band: agent-ready
      agent_readiness: 48.6
      apps:
      - Tenable
      band: exemplar
      in_catalog: true
      kin_score: 80.0
      mcp:
        source: https://github.com/datadog-labs/mcp-server
        status: verified
      name: Datadog
      slug: datadog
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Analytics
      - Dashboards
      - Datadog
      - Visualization
      tier: declared
      url: /providers/datadog/
  - capability:
      attribution: Turbo EA
      id: BC-130
      key: compliance-management
      name: Compliance Management
      url: /capabilities/compliance-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.6
      apps:
      - Tenable
      band: developing
      in_catalog: true
      kin_score: 47.9
      mcp:
        source: https://github.com/VantaInc/vanta-mcp-server
        status: verified
      name: Vanta
      slug: vanta
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Compliance
      - Cybersecurity
      - Governance
      - Security
      tier: declared
      url: /providers/vanta/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Tenable
      band: minimal
      in_catalog: true
      kin_score: 2.5
      mcp:
        status: unknown
      name: Archer
      slug: archer
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Company
      - Payments
      - Payouts
      - Stablecoins
      tier: declared
      url: /providers/archer/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Tenable
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: declared
      url: /providers/okta/
    - agent_band: agent-ready
      agent_readiness: 40.9
      apps:
      - Tenable
      band: strong
      in_catalog: true
      kin_score: 55.9
      mcp:
        source: https://github.com/pingidentity/pingone-mcp-server
        status: verified
      name: Ping Identity
      slug: ping-identity
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity
      - SSO
      tier: declared
      url: /providers/ping-identity/
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
      - Tenable
      band: strong
      in_catalog: true
      kin_score: 61.9
      mcp:
        status: none
      name: ServiceNow
      slug: servicenow
      sources:
      - https://www.tenable.com/partners/technology
      status: profiled
      tags:
      - Automation
      - Cloud Services
      - Digital Workflows
      - ServiceNow
      tier: declared
      url: /providers/servicenow/
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
      - Wazuh
      band: developing
      in_catalog: true
      kin_score: 52.1
      mcp:
        source: https://github.com/PagerDuty/pagerduty-mcp-server
        status: verified
      name: PagerDuty
      slug: pagerduty
      sources:
      - https://github.com/wazuh/wazuh/tree/v4.12.0/integrations
      status: profiled
      tags:
      - Alerting
      - DevOps
      - Incident Management
      - On-Call Management
      tier: observed
      url: /providers/pagerduty/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.8
      apps:
      - OWASP Dependency-Track
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp:
        status: none
      name: Apache Kafka
      slug: apache-kafka
      sources:
      - https://github.com/DependencyTrack/dependency-track/tree/main/notification/publishing
      status: profiled
      tags:
      - Apache Kafka
      - Distributed Systems
      - Event Streaming
      - Messaging
      tier: observed
      url: /providers/apache-kafka/
  layer: common
summary:
  coverage_pct: 96.4
  declared_only: 55
  distinct_providers: 112
  in_catalog: 108
  mcp:
    documented: 10
    none: 12
    unchecked: 18
    verified: 63
  mcp_verified: 63
  mean_kin_score: 50.0
  observed: 57
  queued: 4
  reference_apps: 7
title: 'Security Scanning & Vulnerability Management: application blueprint'
---
