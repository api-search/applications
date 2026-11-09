---
app: Canvas LMS
app_slug: canvas-lms
app_url: https://github.com/instructure/canvas-lms
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.60.40
  key: AE-170.60.40
  layer: domain
  name: Bookmarks, Read-Later & Feed Readers
  providers:
  - Diigo
  url: /capabilities/news-publishing/
  via_parent: News & Publishing
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Google Drive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4700.30
  key: curriculum-mapping-alignment
  layer: domain
  name: Curriculum Mapping & Alignment
  providers:
  - Academic Benchmarks
  url: /capabilities/curriculum-mapping-alignment/
  via_parent: null
- attribution: Turbo EA
  id: BC-4740.60.10
  key: BC-4740.60.10
  layer: domain
  name: Plagiarism Detection
  providers:
  - Turnitin
  - VeriCite
  url: /capabilities/academic-integrity-management/
  via_parent: Academic Integrity Management
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Adobe Connect
  - Webex
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.10.10
  key: AE-170.10.10
  layer: domain
  name: Video Hosting & Encoding
  providers:
  - Kaltura
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon S3
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: common
  name: Integration and API Management
  providers:
  - Amazon Kinesis
  - Amazon SQS
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Amazon DynamoDB
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Datadog
  - Google CrashLytics
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Pendo
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Amazon SNS
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Clever
  - Facebook
  - GitHub
  - Google
  - LinkedIn
  - Microsoft
  - Sign in with Apple
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Amazon Bedrock
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: online-courses-lms
  name: Online Courses & Learning Management
  url: /applications/online-courses-lms/
counts:
  declared: 0
  observed: 25
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.instructure.candroid/latest/
- route: dependency manifest
  url: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
- route: source code
  url: https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4700.30
    key: curriculum-mapping-alignment
    name: Curriculum Mapping & Alignment
    url: /capabilities/curriculum-mapping-alignment/
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
    slug: academic-benchmarks
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: domain
  name: Academic Benchmarks
  provider: academic-benchmarks
  says: ships the Academic Benchmarks SDK or integration code
  source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id003
      status: unchecked
    slug: adobe-connect
    status: queued for profiling
    tags: &id004 []
    url: null
  layer: domain
  name: Adobe Connect
  provider: adobe-connect
  says: ships the Adobe Connect SDK or integration code
  source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: developing
    in_catalog: true
    kin_score: 51.4
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-bedrock
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Artificial Intelligence
    - Foundation Models
    - Generative AI
    url: /providers/amazon-bedrock/
  layer: agent
  name: Amazon Bedrock
  provider: amazon-bedrock
  says: ships the Amazon Bedrock SDK or integration code
  source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 80.9
    mcp: &id007
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-dynamodb
    status: profiled
    tags: &id008
    - Amazon Web Services
    - Database
    - Document Store
    - Key-Value Store
    url: /providers/amazon-dynamodb/
  layer: common
  name: Amazon DynamoDB
  provider: amazon-dynamodb
  says: ships the Amazon DynamoDB SDK or integration code
  source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.4
    band: developing
    in_catalog: true
    kin_score: 49.3
    mcp: &id009
      status: none
    slug: kinesis
    status: profiled
    tags: &id010
    - Amazon Web Services
    - Analytics
    - Apache Flink
    - Big Data
    url: /providers/kinesis/
  layer: common
  name: Amazon Kinesis
  provider: kinesis
  says: ships the Amazon Kinesis SDK or integration code
  source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
    mcp: &id011
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id012
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.4
    band: strong
    in_catalog: true
    kin_score: 55.5
    mcp: &id013
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sns
    status: profiled
    tags: &id014
    - Amazon Web Services
    - Email
    - Messaging
    - Notification
    url: /providers/amazon-sns/
  layer: common
  name: Amazon SNS
  provider: amazon-sns
  says: ships the Amazon SNS SDK or integration code
  source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.1
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id015
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sqs
    status: profiled
    tags: &id016
    - Amazon Web Services
    - Cloud
    - Distributed Systems
    - Messaging
    url: /providers/amazon-sqs/
  layer: common
  name: Amazon SQS
  provider: amazon-sqs
  says: ships the Amazon SQS SDK or integration code
  source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.3
    band: developing
    in_catalog: true
    kin_score: 41.9
    mcp: &id017
      status: none
    slug: clever
    status: profiled
    tags: &id018
    - EdTech
    - Education
    - K-12
    - SSO
    url: /providers/clever/
  layer: common
  name: Clever
  provider: clever
  says: ships the Clever SDK or integration code
  source: https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
  tier: observed
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
    agent_readiness: 49.6
    band: exemplar
    in_catalog: true
    kin_score: 79.2
    mcp: &id019
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id020
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: common
  name: Datadog
  provider: datadog
  says: ships the Datadog SDK or integration code
  source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 11.0
    mcp: &id021
      status: unknown
    slug: diigo
    status: profiled
    tags: &id022
    - Company
    url: /providers/diigo/
  layer: domain
  name: Diigo
  provider: diigo
  says: ships the Diigo SDK or integration code
  source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id023
      status: none
    slug: facebook
    status: profiled
    tags: &id024
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id025
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id026
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id027
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id028
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google
  provider: google-identity-platform
  says: ships the Google SDK or integration code
  source: https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id029
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id030
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Google CrashLytics
  provider: firebase
  says: ships the Google CrashLytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.instructure.candroid/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.3
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id031
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id032
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: domain
  name: Google Drive
  provider: google-drive
  says: ships the Google Drive SDK or integration code
  source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.3
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id033
      source: https://github.com/kaltura/mcp-events
      status: verified
    slug: kaltura
    status: profiled
    tags: &id034
    - Live Streaming
    - Media Management
    - Transcoding
    - Video
    url: /providers/kaltura/
  layer: domain
  name: Kaltura
  provider: kaltura
  says: ships the Kaltura SDK or integration code
  source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.4
    band: exemplar
    in_catalog: true
    kin_score: 76.4
    mcp: &id035
      status: none
    slug: linkedin
    status: profiled
    tags: &id036
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: common
  name: LinkedIn
  provider: linkedin
  says: ships the LinkedIn SDK or integration code
  source: https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.5
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id037
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id038
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft
  provider: microsoft-entra
  says: ships the Microsoft SDK or integration code
  source: https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 35.4
    band: strong
    in_catalog: true
    kin_score: 56.4
    mcp: &id039
      source: https://support.pendo.io/hc/en-us/articles/41102236924955
      status: verified
    slug: pendoio
    status: profiled
    tags: &id040
    - Company
    - Digital Adoption
    - Product Analytics
    - Product Experience
    url: /providers/pendoio/
  layer: common
  name: Pendo
  provider: pendoio
  says: ships the Pendo SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.instructure.candroid/latest/
  tier: observed
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
    kin_score: 80.6
    mcp: &id041
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id042
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id043
      status: none
    slug: apple
    status: profiled
    tags: &id044
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Sign in with Apple
  provider: apple
  says: ships the Sign in with Apple SDK or integration code
  source: https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4740.60.10
    key: BC-4740.60.10
    name: Plagiarism Detection
    url: /capabilities/academic-integrity-management/
    via_parent: Academic Integrity Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: thin
    in_catalog: true
    kin_score: 35.9
    mcp: &id045
      status: none
    slug: turnitin
    status: profiled
    tags: &id046
    - Academic Integrity
    - Company
    - EdTech
    - Education
    url: /providers/turnitin/
  layer: domain
  name: Turnitin
  provider: turnitin
  says: ships the Turnitin SDK or integration code
  source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4740.60.10
    key: BC-4740.60.10
    name: Plagiarism Detection
    url: /capabilities/academic-integrity-management/
    via_parent: Academic Integrity Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id047
      status: unchecked
    slug: vericite
    status: queued for profiling
    tags: &id048 []
    url: null
  layer: domain
  name: VeriCite
  provider: vericite
  says: ships the VeriCite SDK or integration code
  source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  tier: observed
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
    agent_readiness: 61.1
    band: strong
    in_catalog: true
    kin_score: 64.2
    mcp: &id049
      source: https://github.com/WebexSamples/webex-messaging-mcp-server
      status: verified
    slug: webex
    status: profiled
    tags: &id050
    - Calling
    - Collaboration
    - Communications
    - Enterprise
    url: /providers/webex/
  layer: domain
  name: Webex
  provider: webex
  says: ships the Webex SDK or integration code
  source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/online-courses-lms/canvas-lms/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: Academic Benchmarks
  slug: academic-benchmarks
  status: queued for profiling
  tags: *id002
  url: null
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: Adobe Connect
  slug: adobe-connect
  status: queued for profiling
  tags: *id004
  url: null
- agent_band: agent-ready
  agent_readiness: 35.8
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id005
  name: Amazon Bedrock
  slug: amazon-bedrock
  status: profiled
  tags: *id006
  url: /providers/amazon-bedrock/
- agent_band: agent-native
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 80.9
  mcp: *id007
  name: Amazon DynamoDB
  slug: amazon-dynamodb
  status: profiled
  tags: *id008
  url: /providers/amazon-dynamodb/
- agent_band: agent-ready
  agent_readiness: 29.4
  band: developing
  in_catalog: true
  kin_score: 49.3
  mcp: *id009
  name: Amazon Kinesis
  slug: kinesis
  status: profiled
  tags: *id010
  url: /providers/kinesis/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id011
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id012
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 29.4
  band: strong
  in_catalog: true
  kin_score: 55.5
  mcp: *id013
  name: Amazon SNS
  slug: amazon-sns
  status: profiled
  tags: *id014
  url: /providers/amazon-sns/
- agent_band: agent-ready
  agent_readiness: 31.1
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id015
  name: Amazon SQS
  slug: amazon-sqs
  status: profiled
  tags: *id016
  url: /providers/amazon-sqs/
- agent_band: agent-aware
  agent_readiness: 28.3
  band: developing
  in_catalog: true
  kin_score: 41.9
  mcp: *id017
  name: Clever
  slug: clever
  status: profiled
  tags: *id018
  url: /providers/clever/
- agent_band: agent-ready
  agent_readiness: 49.6
  band: exemplar
  in_catalog: true
  kin_score: 79.2
  mcp: *id019
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id020
  url: /providers/datadog/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id021
  name: Diigo
  slug: diigo
  status: profiled
  tags: *id022
  url: /providers/diigo/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id023
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id024
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id025
  name: GitHub
  slug: github
  status: profiled
  tags: *id026
  url: /providers/github/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id027
  name: Google
  slug: google-identity-platform
  status: profiled
  tags: *id028
  url: /providers/google-identity-platform/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id029
  name: Google CrashLytics
  slug: firebase
  status: profiled
  tags: *id030
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id031
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id032
  url: /providers/google-drive/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id033
  name: Kaltura
  slug: kaltura
  status: profiled
  tags: *id034
  url: /providers/kaltura/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: exemplar
  in_catalog: true
  kin_score: 76.4
  mcp: *id035
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id036
  url: /providers/linkedin/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id037
  name: Microsoft
  slug: microsoft-entra
  status: profiled
  tags: *id038
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 35.4
  band: strong
  in_catalog: true
  kin_score: 56.4
  mcp: *id039
  name: Pendo
  slug: pendoio
  status: profiled
  tags: *id040
  url: /providers/pendoio/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id041
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id042
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id043
  name: Sign in with Apple
  slug: apple
  status: profiled
  tags: *id044
  url: /providers/apple/
- agent_band: human-only
  agent_readiness: 2.5
  band: thin
  in_catalog: true
  kin_score: 35.9
  mcp: *id045
  name: Turnitin
  slug: turnitin
  status: profiled
  tags: *id046
  url: /providers/turnitin/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id047
  name: VeriCite
  slug: vericite
  status: queued for profiling
  tags: *id048
  url: null
- agent_band: agent-ready
  agent_readiness: 61.1
  band: strong
  in_catalog: true
  kin_score: 64.2
  mcp: *id049
  name: Webex
  slug: webex
  status: profiled
  tags: *id050
  url: /providers/webex/
siblings:
- name: Chamilo
  rows: 13
  url: /applications/online-courses-lms/chamilo/
- name: Coursera
  rows: 4
  url: /applications/online-courses-lms/coursera/
- name: LearnWorlds
  rows: 55
  url: /applications/online-courses-lms/learnworlds/
- name: Moodle
  rows: 27
  url: /applications/online-courses-lms/moodle/
- name: Open edX
  rows: 8
  url: /applications/online-courses-lms/open-edx/
- name: Thinkific
  rows: 13
  url: /applications/online-courses-lms/thinkific/
- name: Udemy
  rows: 6
  url: /applications/online-courses-lms/udemy/
sitemap: true
title: 'Canvas LMS: Online Courses & Learning Management reference app'
---
