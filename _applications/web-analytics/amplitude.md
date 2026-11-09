---
app: Amplitude
app_slug: amplitude
app_url: https://amplitude.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Databricks
  - Google BigQuery
  - Snowflake
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: domain
  name: Content Management
  providers:
  - WordPress
  url: /capabilities/content-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: domain
  name: Customer Data Management
  providers:
  - Fivetran
  - Hightouch
  - mParticle
  - RudderStack
  - Tealium
  - Twilio Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2120.40
  key: customer-information-consent-management
  layer: domain
  name: Customer Information & Consent Management
  providers:
  - Osano
  url: /capabilities/customer-information-consent-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1300.10
  key: customer-onboarding-management
  layer: domain
  name: Customer Onboarding Management
  providers:
  - Appcues
  - Chameleon
  url: /capabilities/customer-onboarding-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Facebook / Meta Ads
  - Google Ads
  - Snapchat Ads
  - TikTok Ads
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210.50
  key: feature-flag-management
  layer: domain
  name: Feature Flag Management
  providers:
  - Flagsmith
  - LaunchDarkly
  - Optimizely
  - Statsig
  url: /capabilities/feature-flag-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: domain
  name: Mobile Attribution & Deep Linking
  providers:
  - Adjust
  - AppsFlyer
  - Branch (branch.io)
  - Singular
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: domain
  name: Product Usage Analytics
  providers:
  - Fullstory
  - Google Analytics
  - Hotjar
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: domain
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon S3
  - Azure Blob Storage
  - Google Cloud Storage
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: common
  name: Customer Lifecycle Engagement
  providers:
  - Airship
  - Braze
  - Customer.io
  - Iterable
  - Klaviyo
  - Mailchimp
  - Marketo
  - MoEngage
  - OneSignal
  - Salesforce Marketing Cloud
  url: /capabilities/customer-lifecycle-engagement/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Intercom
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: common
  name: Integration and API Management
  providers:
  - Amazon Kinesis Data Firehose
  - Google Cloud Pub/Sub
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: Turbo EA
  id: BC-830.30
  key: knowledge-sharing-collaboration-management
  layer: common
  name: Knowledge Sharing & Collaboration Management
  providers:
  - Slack
  url: /capabilities/knowledge-sharing-collaboration-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
category:
  id: web-analytics
  name: Web & Product Analytics
  url: /applications/web-analytics/
counts:
  declared: 50
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
- route: integrations page
  url: https://amplitude.com/integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.8
    band: emerging
    in_catalog: true
    kin_score: 24.9
    mcp: &id001
      status: none
    slug: adjust
    status: profiled
    tags: &id002
    - Analytics
    - Attribution
    - Deep Linking
    - Measurements
    url: /providers/adjust/
  layer: domain
  name: Adjust
  provider: adjust
  says: lists Adjust as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id003
      source: https://github.com/urbanairship/agent-tools
      status: verified
    slug: airship
    status: profiled
    tags: &id004
    - Email
    - Mobile
    - Notification
    - Push
    url: /providers/airship/
  layer: common
  name: Airship
  provider: airship
  says: lists Airship as an integration
  source: https://amplitude.com/integrations
  tier: declared
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
    agent_readiness: 25.3
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id005
      status: none
    slug: amazon-kinesis-firehose
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Analytics
    - Data Delivery
    - Streaming
    url: /providers/amazon-kinesis-firehose/
  layer: common
  name: Amazon Kinesis Data Firehose
  provider: amazon-kinesis-firehose
  says: lists Amazon Kinesis Data Firehose as an integration
  source: https://amplitude.com/integrations
  tier: declared
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
    mcp: &id007
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id008
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: lists Amazon S3 as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1300.10
    key: customer-onboarding-management
    name: Customer Onboarding Management
    url: /capabilities/customer-onboarding-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.9
    band: emerging
    in_catalog: true
    kin_score: 24.6
    mcp: &id009
      status: none
    slug: appcues
    status: profiled
    tags: &id010
    - Analytics
    - In-App Guidance
    - Onboarding
    - Product
    url: /providers/appcues/
  layer: domain
  name: Appcues
  provider: appcues
  says: lists Appcues as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.4
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id011
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id012
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: domain
  name: AppsFlyer
  provider: appsflyer
  says: lists AppsFlyer as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id013
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id014
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: lists Azure Blob Storage as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.7
    band: emerging
    in_catalog: true
    kin_score: 23.0
    mcp: &id015
      status: none
    slug: branch-io
    status: profiled
    tags: &id016
    - Company
    url: /providers/branch-io/
  layer: domain
  name: Branch (branch.io)
  provider: branch-io
  says: lists Branch (branch.io) as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.9
    band: exemplar
    in_catalog: true
    kin_score: 75.2
    mcp: &id017
      source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
      status: verified
    slug: braze
    status: profiled
    tags: &id018
    - Customer Engagement
    - Marketing Automation
    - Messaging
    - Push Notifications
    url: /providers/braze/
  layer: common
  name: Braze
  provider: braze
  says: lists Braze as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1300.10
    key: customer-onboarding-management
    name: Customer Onboarding Management
    url: /capabilities/customer-onboarding-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.7
    band: thin
    in_catalog: true
    kin_score: 32.3
    mcp: &id019
      status: none
    slug: chameleon
    status: profiled
    tags: &id020
    - In-App Guidance
    - Onboarding
    - Product
    - Surveys
    url: /providers/chameleon/
  layer: domain
  name: Chameleon
  provider: chameleon
  says: lists Chameleon as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 69.9
    band: exemplar
    in_catalog: true
    kin_score: 86.9
    mcp: &id021
      source: https://github.com/customerio/claude-plugin
      status: verified
    slug: customer-io
    status: profiled
    tags: &id022
    - Behavioral Data
    - Broadcast
    - CDP
    - Campaigns
    url: /providers/customer-io/
  layer: common
  name: Customer.io
  provider: customer-io
  says: lists Customer.io as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 58.9
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id023
      source: https://docs.databricks.com/aws/en/generative-ai/mcp/
      status: verified
    slug: databricks
    status: profiled
    tags: &id024
    - Analytics
    - Artificial Intelligence
    - Cleanroom
    - Databricks
    url: /providers/databricks/
  layer: domain
  name: Databricks
  provider: databricks
  says: lists Databricks as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id025
      status: none
    slug: facebook
    status: profiled
    tags: &id026
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook / Meta Ads
  provider: facebook
  says: lists Facebook / Meta Ads as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.4
    band: thin
    in_catalog: true
    kin_score: 34.6
    mcp: &id027
      source: https://github.com/fivetran/fivetran-mcp
      status: verified
    slug: fivetran
    status: profiled
    tags: &id028
    - Connectors
    - Data Integration
    - Data Pipeline
    - ETL
    url: /providers/fivetran/
  layer: domain
  name: Fivetran
  provider: fivetran
  says: lists Fivetran as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.3
    band: exemplar
    in_catalog: true
    kin_score: 79.4
    mcp: &id029
      source: https://github.com/Flagsmith/flagsmith-mcp
      status: verified
    slug: flagsmith
    status: profiled
    tags: &id030
    - A/B Testing
    - Feature Flags
    - Release Management
    - Remote Config
    url: /providers/flagsmith/
  layer: domain
  name: Flagsmith
  provider: flagsmith
  says: lists Flagsmith as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.6
    band: thin
    in_catalog: true
    kin_score: 37.1
    mcp: &id031
      source: https://developer.fullstory.com/mcp/introduction/
      status: documented
    slug: fullstory
    status: profiled
    tags: &id032
    - Behavioral Analytics
    - Digital Experience
    - Product Analytics
    - Session Replay
    url: /providers/fullstory/
  layer: domain
  name: Fullstory
  provider: fullstory
  says: lists Fullstory as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.7
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id033
      source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
      status: verified
    slug: google-ads
    status: profiled
    tags: &id034
    - Advertising
    - Campaign Management
    - Digital Advertising
    - Google
    url: /providers/google-ads/
  layer: domain
  name: Google Ads
  provider: google-ads
  says: lists Google Ads as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id035
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id036
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: domain
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.5
    band: developing
    in_catalog: true
    kin_score: 49.7
    mcp: &id037
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id038
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
  layer: domain
  name: Google BigQuery
  provider: google-bigquery
  says: lists Google BigQuery as an integration
  source: https://amplitude.com/integrations
  tier: declared
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
    agent_readiness: 25.6
    band: thin
    in_catalog: true
    kin_score: 38.7
    mcp: &id039
      source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
      status: verified
    slug: google-cloud-pubsub
    status: profiled
    tags: &id040
    - Event-Driven
    - Google Cloud
    - Messaging
    - Pub/Sub
    url: /providers/google-cloud-pubsub/
  layer: common
  name: Google Cloud Pub/Sub
  provider: google-cloud-pubsub
  says: lists Google Cloud Pub/Sub as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.3
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id041
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id042
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: lists Google Cloud Storage as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.2
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id043
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id044
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: domain
  name: Google Tag Manager
  provider: google-tag-manager
  says: lists Google Tag Manager as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.8
    band: exemplar
    in_catalog: true
    kin_score: 69.4
    mcp: &id045
      source: https://hightouch.com/docs/ai-integrations/mcp
      status: documented
    slug: hightouch
    status: profiled
    tags: &id046
    - Audience Management
    - CDP
    - Data Activation
    - Reverse ETL
    url: /providers/hightouch/
  layer: domain
  name: Hightouch
  provider: hightouch
  says: lists Hightouch as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.8
    band: thin
    in_catalog: true
    kin_score: 26.7
    mcp: &id047
      status: none
    slug: hotjar
    status: profiled
    tags: &id048
    - Analytics
    - Personalization
    - Surveys
    - Tracking
    url: /providers/hotjar/
  layer: domain
  name: Hotjar
  provider: hotjar
  says: lists Hotjar as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.7
    band: exemplar
    in_catalog: true
    kin_score: 94.6
    mcp: &id049
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id050
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: common
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.7
    band: developing
    in_catalog: true
    kin_score: 52.5
    mcp: &id051
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id052
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: common
  name: Intercom
  provider: intercom
  says: lists Intercom as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.5
    band: exemplar
    in_catalog: true
    kin_score: 67.9
    mcp: &id053
      source: https://github.com/Iterable/mcp-server
      status: verified
    slug: iterable
    status: profiled
    tags: &id054
    - Cross-Channel Messaging
    - Customer Engagement
    - Email
    - Marketing Automation
    url: /providers/iterable/
  layer: common
  name: Iterable
  provider: iterable
  says: lists Iterable as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.9
    band: exemplar
    in_catalog: true
    kin_score: 77.6
    mcp: &id055
      source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
      status: verified
    slug: klaviyo
    status: profiled
    tags: &id056
    - Customer Data
    - Email
    - Marketing
    - SMS
    url: /providers/klaviyo/
  layer: common
  name: Klaviyo
  provider: klaviyo
  says: lists Klaviyo as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 60.6
    band: exemplar
    in_catalog: true
    kin_score: 85.5
    mcp: &id057
      source: https://launchdarkly.com/docs/home/getting-started/mcp
      status: verified
    slug: launchdarkly
    status: profiled
    tags: &id058
    - Experimentation
    - Feature Flags
    - Feature Management
    - Observability
    url: /providers/launchdarkly/
  layer: domain
  name: LaunchDarkly
  provider: launchdarkly
  says: lists LaunchDarkly as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.3
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id059
      status: none
    slug: mailchimp
    status: profiled
    tags: &id060
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.1
    band: strong
    in_catalog: true
    kin_score: 55.6
    mcp: &id061
      status: none
    slug: marketo
    status: profiled
    tags: &id062
    - Adobe
    - Automation
    - Marketing
    - Marketing Automation
    url: /providers/marketo/
  layer: common
  name: Marketo
  provider: marketo
  says: lists Marketo as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id063
      status: none
    slug: moengage
    status: profiled
    tags: &id064
    - Customer Data Platform
    - Customer Engagement
    - Marketing Automation
    - Push Notifications
    url: /providers/moengage/
  layer: common
  name: MoEngage
  provider: moengage
  says: lists MoEngage as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.7
    band: strong
    in_catalog: true
    kin_score: 58.7
    mcp: &id065
      status: none
    slug: mparticle
    status: profiled
    tags: &id066
    - Analytics
    - CDP
    - Customer Data Platform
    - Identity Resolution
    url: /providers/mparticle/
  layer: domain
  name: mParticle
  provider: mparticle
  says: lists mParticle as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 71.3
    band: exemplar
    in_catalog: true
    kin_score: 78.0
    mcp: &id067
      source: https://github.com/OneSignal/onesignal-ai-skills
      status: documented
    slug: onesignal
    status: profiled
    tags: &id068
    - Email
    - Notification
    - Push
    - SMS
    url: /providers/onesignal/
  layer: common
  name: OneSignal
  provider: onesignal
  says: lists OneSignal as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id069
      source: https://support.optimizely.com/hc/en-us/articles/45320607594893
      status: documented
    slug: optimizely
    status: profiled
    tags: &id070
    - A/B Testing
    - Content Management
    - Customer Data
    - E-Commerce
    url: /providers/optimizely/
  layer: domain
  name: Optimizely
  provider: optimizely
  says: lists Optimizely as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2120.40
    key: customer-information-consent-management
    name: Customer Information & Consent Management
    url: /capabilities/customer-information-consent-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.5
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id071
      status: none
    slug: osano
    status: profiled
    tags: &id072
    - Company
    - Compliance
    - Consent Management
    - Privacy
    url: /providers/osano/
  layer: domain
  name: Osano
  provider: osano
  says: lists Osano as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 58.1
    band: exemplar
    in_catalog: true
    kin_score: 78.5
    mcp: &id073
      source: https://github.com/rudderlabs/rudderstack-mcp
      status: verified
    slug: rudderstack
    status: profiled
    tags: &id074
    - CDP
    - Customer Data Platform
    - Data Pipeline
    - Open Source
    url: /providers/rudderstack/
  layer: domain
  name: RudderStack
  provider: rudderstack
  says: lists RudderStack as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.7
    band: exemplar
    in_catalog: true
    kin_score: 90.6
    mcp: &id075
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id076
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.8
    band: exemplar
    in_catalog: true
    kin_score: 80.5
    mcp: &id077
      status: none
    slug: salesforce-marketing-cloud
    status: profiled
    tags: &id078
    - Automation
    - Content Management
    - Customer Journey
    - Digital Marketing
    url: /providers/salesforce-marketing-cloud/
  layer: common
  name: Salesforce Marketing Cloud
  provider: salesforce-marketing-cloud
  says: lists Salesforce Marketing Cloud as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.1
    band: exemplar
    in_catalog: true
    kin_score: 87.3
    mcp: &id079
      status: none
    slug: sendgrid
    status: profiled
    tags: &id080
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: lists SendGrid as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.5
    band: exemplar
    in_catalog: true
    kin_score: 84.6
    mcp: &id081
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id082
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.0
    band: exemplar
    in_catalog: true
    kin_score: 67.4
    mcp: &id083
      status: none
    slug: singular
    status: profiled
    tags: &id084
    - Attribution
    - Company
    - Marketing Analytics
    - Mobile Attribution
    url: /providers/singular/
  layer: domain
  name: Singular
  provider: singular
  says: lists Singular as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id085
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id086
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.1
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id087
      status: none
    slug: snapchat
    status: profiled
    tags: &id088
    - Advertising
    - Augmented Reality
    - Marketing
    - Messaging
    url: /providers/snapchat/
  layer: domain
  name: Snapchat Ads
  provider: snapchat
  says: lists Snapchat Ads as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 45.8
    band: exemplar
    in_catalog: true
    kin_score: 81.1
    mcp: &id089
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id090
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
  layer: domain
  name: Snowflake
  provider: snowflake
  says: lists Snowflake as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 55.6
    band: exemplar
    in_catalog: true
    kin_score: 76.8
    mcp: &id091
      source: https://registry.modelcontextprotocol.io/v0/servers?search=statsig
      status: verified
    slug: statsig
    status: profiled
    tags: &id092
    - A/B Testing
    - Experimentation
    - Feature Flags
    - Product Analytics
    url: /providers/statsig/
  layer: domain
  name: Statsig
  provider: statsig
  says: lists Statsig as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.6
    band: strong
    in_catalog: true
    kin_score: 66.3
    mcp: &id093
      source: https://docs.tealium.com/server-side/config-mcp/about-config-mcp/
      status: documented
    slug: tealium
    status: profiled
    tags: &id094
    - AudienceStream
    - CDP
    - Customer Data Platform
    - Tag Management
    url: /providers/tealium/
  layer: domain
  name: Tealium
  provider: tealium
  says: lists Tealium as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 57.9
    band: strong
    in_catalog: true
    kin_score: 57.4
    mcp: &id095
      status: none
    slug: tiktok-ads
    status: profiled
    tags: &id096
    - Ad Campaigns
    - Advertising
    - Marketing
    - Social Media
    url: /providers/tiktok-ads/
  layer: domain
  name: TikTok Ads
  provider: tiktok-ads
  says: lists TikTok Ads as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 43.8
    mcp: &id097
      status: none
    slug: segment
    status: profiled
    tags: &id098
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: domain
  name: Twilio Segment
  provider: segment
  says: lists Twilio Segment as an integration
  source: https://amplitude.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.4
    band: developing
    in_catalog: true
    kin_score: 46.0
    mcp: &id099
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id100
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
  layer: domain
  name: WordPress
  provider: wordpress
  says: lists WordPress as an integration
  source: https://amplitude.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/web-analytics/amplitude/
providers:
- agent_band: agent-aware
  agent_readiness: 23.8
  band: emerging
  in_catalog: true
  kin_score: 24.9
  mcp: *id001
  name: Adjust
  slug: adjust
  status: profiled
  tags: *id002
  url: /providers/adjust/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id003
  name: Airship
  slug: airship
  status: profiled
  tags: *id004
  url: /providers/airship/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id005
  name: Amazon Kinesis Data Firehose
  slug: amazon-kinesis-firehose
  status: profiled
  tags: *id006
  url: /providers/amazon-kinesis-firehose/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id007
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id008
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 43.9
  band: emerging
  in_catalog: true
  kin_score: 24.6
  mcp: *id009
  name: Appcues
  slug: appcues
  status: profiled
  tags: *id010
  url: /providers/appcues/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id011
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id012
  url: /providers/appsflyer/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id013
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id014
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: emerging
  in_catalog: true
  kin_score: 23.0
  mcp: *id015
  name: Branch (branch.io)
  slug: branch-io
  status: profiled
  tags: *id016
  url: /providers/branch-io/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: exemplar
  in_catalog: true
  kin_score: 75.2
  mcp: *id017
  name: Braze
  slug: braze
  status: profiled
  tags: *id018
  url: /providers/braze/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id019
  name: Chameleon
  slug: chameleon
  status: profiled
  tags: *id020
  url: /providers/chameleon/
- agent_band: agent-ready
  agent_readiness: 69.9
  band: exemplar
  in_catalog: true
  kin_score: 86.9
  mcp: *id021
  name: Customer.io
  slug: customer-io
  status: profiled
  tags: *id022
  url: /providers/customer-io/
- agent_band: agent-ready
  agent_readiness: 58.9
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id023
  name: Databricks
  slug: databricks
  status: profiled
  tags: *id024
  url: /providers/databricks/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id025
  name: Facebook / Meta Ads
  slug: facebook
  status: profiled
  tags: *id026
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 36.4
  band: thin
  in_catalog: true
  kin_score: 34.6
  mcp: *id027
  name: Fivetran
  slug: fivetran
  status: profiled
  tags: *id028
  url: /providers/fivetran/
- agent_band: agent-ready
  agent_readiness: 48.3
  band: exemplar
  in_catalog: true
  kin_score: 79.4
  mcp: *id029
  name: Flagsmith
  slug: flagsmith
  status: profiled
  tags: *id030
  url: /providers/flagsmith/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: thin
  in_catalog: true
  kin_score: 37.1
  mcp: *id031
  name: Fullstory
  slug: fullstory
  status: profiled
  tags: *id032
  url: /providers/fullstory/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id033
  name: Google Ads
  slug: google-ads
  status: profiled
  tags: *id034
  url: /providers/google-ads/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id035
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id036
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 31.5
  band: developing
  in_catalog: true
  kin_score: 49.7
  mcp: *id037
  name: Google BigQuery
  slug: google-bigquery
  status: profiled
  tags: *id038
  url: /providers/google-bigquery/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: thin
  in_catalog: true
  kin_score: 38.7
  mcp: *id039
  name: Google Cloud Pub/Sub
  slug: google-cloud-pubsub
  status: profiled
  tags: *id040
  url: /providers/google-cloud-pubsub/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id041
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id042
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 38.2
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id043
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id044
  url: /providers/google-tag-manager/
- agent_band: agent-ready
  agent_readiness: 63.8
  band: exemplar
  in_catalog: true
  kin_score: 69.4
  mcp: *id045
  name: Hightouch
  slug: hightouch
  status: profiled
  tags: *id046
  url: /providers/hightouch/
- agent_band: agent-aware
  agent_readiness: 27.8
  band: thin
  in_catalog: true
  kin_score: 26.7
  mcp: *id047
  name: Hotjar
  slug: hotjar
  status: profiled
  tags: *id048
  url: /providers/hotjar/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id049
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id050
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 31.7
  band: developing
  in_catalog: true
  kin_score: 52.5
  mcp: *id051
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id052
  url: /providers/intercom/
- agent_band: agent-ready
  agent_readiness: 34.5
  band: exemplar
  in_catalog: true
  kin_score: 67.9
  mcp: *id053
  name: Iterable
  slug: iterable
  status: profiled
  tags: *id054
  url: /providers/iterable/
- agent_band: agent-native
  agent_readiness: 54.9
  band: exemplar
  in_catalog: true
  kin_score: 77.6
  mcp: *id055
  name: Klaviyo
  slug: klaviyo
  status: profiled
  tags: *id056
  url: /providers/klaviyo/
- agent_band: agent-ready
  agent_readiness: 60.6
  band: exemplar
  in_catalog: true
  kin_score: 85.5
  mcp: *id057
  name: LaunchDarkly
  slug: launchdarkly
  status: profiled
  tags: *id058
  url: /providers/launchdarkly/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id059
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id060
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 31.1
  band: strong
  in_catalog: true
  kin_score: 55.6
  mcp: *id061
  name: Marketo
  slug: marketo
  status: profiled
  tags: *id062
  url: /providers/marketo/
- agent_band: agent-native
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id063
  name: MoEngage
  slug: moengage
  status: profiled
  tags: *id064
  url: /providers/moengage/
- agent_band: agent-ready
  agent_readiness: 45.7
  band: strong
  in_catalog: true
  kin_score: 58.7
  mcp: *id065
  name: mParticle
  slug: mparticle
  status: profiled
  tags: *id066
  url: /providers/mparticle/
- agent_band: agent-native
  agent_readiness: 71.3
  band: exemplar
  in_catalog: true
  kin_score: 78.0
  mcp: *id067
  name: OneSignal
  slug: onesignal
  status: profiled
  tags: *id068
  url: /providers/onesignal/
- agent_band: agent-ready
  agent_readiness: 62.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id069
  name: Optimizely
  slug: optimizely
  status: profiled
  tags: *id070
  url: /providers/optimizely/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id071
  name: Osano
  slug: osano
  status: profiled
  tags: *id072
  url: /providers/osano/
- agent_band: agent-ready
  agent_readiness: 58.1
  band: exemplar
  in_catalog: true
  kin_score: 78.5
  mcp: *id073
  name: RudderStack
  slug: rudderstack
  status: profiled
  tags: *id074
  url: /providers/rudderstack/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id075
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id076
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: exemplar
  in_catalog: true
  kin_score: 80.5
  mcp: *id077
  name: Salesforce Marketing Cloud
  slug: salesforce-marketing-cloud
  status: profiled
  tags: *id078
  url: /providers/salesforce-marketing-cloud/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id079
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id080
  url: /providers/sendgrid/
- agent_band: agent-ready
  agent_readiness: 52.5
  band: exemplar
  in_catalog: true
  kin_score: 84.6
  mcp: *id081
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id082
  url: /providers/shopify/
- agent_band: agent-ready
  agent_readiness: 50.0
  band: exemplar
  in_catalog: true
  kin_score: 67.4
  mcp: *id083
  name: Singular
  slug: singular
  status: profiled
  tags: *id084
  url: /providers/singular/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id085
  name: Slack
  slug: slack
  status: profiled
  tags: *id086
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 48.1
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id087
  name: Snapchat Ads
  slug: snapchat
  status: profiled
  tags: *id088
  url: /providers/snapchat/
- agent_band: agent-native
  agent_readiness: 45.8
  band: exemplar
  in_catalog: true
  kin_score: 81.1
  mcp: *id089
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id090
  url: /providers/snowflake/
- agent_band: agent-ready
  agent_readiness: 55.6
  band: exemplar
  in_catalog: true
  kin_score: 76.8
  mcp: *id091
  name: Statsig
  slug: statsig
  status: profiled
  tags: *id092
  url: /providers/statsig/
- agent_band: agent-ready
  agent_readiness: 35.6
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id093
  name: Tealium
  slug: tealium
  status: profiled
  tags: *id094
  url: /providers/tealium/
- agent_band: agent-ready
  agent_readiness: 57.9
  band: strong
  in_catalog: true
  kin_score: 57.4
  mcp: *id095
  name: TikTok Ads
  slug: tiktok-ads
  status: profiled
  tags: *id096
  url: /providers/tiktok-ads/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 43.8
  mcp: *id097
  name: Twilio Segment
  slug: segment
  status: profiled
  tags: *id098
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: developing
  in_catalog: true
  kin_score: 46.0
  mcp: *id099
  name: WordPress
  slug: wordpress
  status: profiled
  tags: *id100
  url: /providers/wordpress/
siblings:
- name: Google Analytics
  rows: 4
  url: /applications/web-analytics/google-analytics/
- name: Matomo
  rows: 18
  url: /applications/web-analytics/matomo/
- name: Mixpanel
  rows: 12
  url: /applications/web-analytics/mixpanel/
- name: Plausible
  rows: 16
  url: /applications/web-analytics/plausible/
- name: PostHog
  rows: 42
  url: /applications/web-analytics/posthog/
- name: Umami
  rows: 4
  url: /applications/web-analytics/umami/
sitemap: true
title: 'Amplitude: Web & Product Analytics reference app'
---
