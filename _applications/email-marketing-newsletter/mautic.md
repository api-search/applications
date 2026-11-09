---
app: Mautic
app_slug: mautic
app_url: https://github.com/mautic/mautic
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: domain
  name: Customer Data Management
  providers:
  - Clearbit
  - FullContact
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - ConnectWise
  - HubSpot
  - Microsoft Dynamics 365
  - Salesforce
  - SugarCRM
  - Vtiger
  - Zoho CRM
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Constant Contact
  - Facebook
  - Foursquare
  - iContact
  - Instagram
  - X (Twitter)
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: domain
  name: Email Marketing Sends
  providers:
  - Amazon SES
  - Elastic Email
  - Mailjet
  - SendGrid
  - SparkPost
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: common
  name: IP Geolocation
  providers:
  - IP2Location
  - MaxMind
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: Turbo EA
  id: BC-3710
  key: media-asset-management
  layer: common
  name: Media Asset Management
  providers:
  - Amazon S3
  url: /capabilities/media-asset-management/
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
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: email-marketing-newsletter
  name: Email Marketing & Newsletters
  url: /applications/email-marketing-newsletter/
counts:
  declared: 5
  observed: 20
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/mautic/mautic/7.x/app/composer.json
- route: dependency manifest
  url: https://raw.githubusercontent.com/mautic/mautic/7.x/composer.json
- route: documentation
  url: https://docs.mautic.org/en/7.0/channels/emails.html
- route: source code
  url: https://github.com/mautic/mautic/tree/7.x/plugins
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCloudStorageBundle/Integration
  tier: observed
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
    agent_readiness: 25.2
    band: strong
    in_catalog: true
    kin_score: 57.9
    mcp: &id005
      status: none
    slug: clearbit
    status: profiled
    tags: &id006
    - B2B
    - Data Enrichment
    - Reveal
    - Sales Intelligence
    url: /providers/clearbit/
  layer: domain
  name: Clearbit
  provider: clearbit
  says: ships the Clearbit SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.8
    band: emerging
    in_catalog: true
    kin_score: 24.0
    mcp: &id007
      source: https://www.connectwise.com/blog/what-mcp-could-mean-for-msps
      status: documented
    slug: connectwise
    status: profiled
    tags: &id008
    - IT Management
    - MSP
    - PSA
    - RMM
    url: /providers/connectwise/
  layer: domain
  name: ConnectWise
  provider: connectwise
  says: ships the ConnectWise SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
  tier: observed
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
    agent_readiness: 32.1
    band: exemplar
    in_catalog: true
    kin_score: 70.9
    mcp: &id009
      status: none
    slug: constant-contact
    status: profiled
    tags: &id010
    - Campaigns
    - Contacts
    - Email Marketing
    - Event
    url: /providers/constant-contact/
  layer: domain
  name: Constant Contact
  provider: constant-contact
  says: ships the Constant Contact SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticEmailMarketingBundle/Integration
  tier: observed
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
    mcp: &id013
      status: none
    slug: facebook
    status: profiled
    tags: &id014
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
  tier: observed
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
    agent_readiness: 23.3
    band: developing
    in_catalog: true
    kin_score: 47.7
    mcp: &id015
      source: https://github.com/foursquare/foursquare-places-mcp
      status: verified
    slug: foursquare
    status: profiled
    tags: &id016
    - Geocoding
    - Location
    - Places
    - Restaurant
    url: /providers/foursquare/
  layer: domain
  name: Foursquare
  provider: foursquare
  says: ships the Foursquare SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
  tier: observed
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
    agent_readiness: 39.4
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id017
      status: none
    slug: fullcontact
    status: profiled
    tags: &id018
    - Customer Data
    - Data Enrichment
    - Identity Resolution
    - Person API
    url: /providers/fullcontact/
  layer: domain
  name: FullContact
  provider: fullcontact
  says: ships the FullContact SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins
  tier: observed
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
    mcp: &id019
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id020
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: ships the HubSpot SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
  tier: observed
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
    agent_readiness: 26.1
    band: strong
    in_catalog: true
    kin_score: 55.7
    mcp: &id021
      status: none
    slug: icontact
    status: profiled
    tags: &id022
    - Campaigns
    - Contacts
    - Email Marketing
    - Marketing Automation
    url: /providers/icontact/
  layer: domain
  name: iContact
  provider: icontact
  says: ships the iContact SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticEmailMarketingBundle/Integration
  tier: observed
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
    agent_readiness: 38.9
    band: exemplar
    in_catalog: true
    kin_score: 69.0
    mcp: &id023
      status: none
    slug: instagram
    status: profiled
    tags: &id024
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
  layer: domain
  name: Instagram
  provider: instagram
  says: ships the Instagram SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.2
    mcp: &id025
      source: https://github.com/ip2location/mcp-ip2location-io
      status: verified
    slug: ip2location
    status: profiled
    tags: &id026
    - Geocoding
    - Public APIs
    url: /providers/ip2location/
  layer: common
  name: IP2Location
  provider: ip2location
  says: ships the IP2Location SDK or integration code
  source: https://raw.githubusercontent.com/mautic/mautic/7.x/app/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id029
      status: none
    slug: maxmind
    status: profiled
    tags: &id030
    - Fraud Prevention
    - Geolocation
    - IP Intelligence
    - Risk Scoring
    url: /providers/maxmind/
  layer: common
  name: MaxMind
  provider: maxmind
  says: ships the MaxMind SDK or integration code
  source: https://raw.githubusercontent.com/mautic/mautic/7.x/app/composer.json
  tier: observed
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
    agent_readiness: 33.1
    band: strong
    in_catalog: true
    kin_score: 63.9
    mcp: &id031
      source: https://github.com/microsoft/Dataverse-MCP
      status: verified
    slug: microsoft-dynamics-365
    status: profiled
    tags: &id032
    - Business Applications
    - CRM
    - Cloud
    - Enterprise
    url: /providers/microsoft-dynamics-365/
  layer: domain
  name: Microsoft Dynamics 365
  provider: microsoft-dynamics-365
  says: ships the Microsoft Dynamics 365 SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
  tier: observed
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
    mcp: &id033
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id034
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: ships the Salesforce SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.2
    band: exemplar
    in_catalog: true
    kin_score: 67.6
    mcp: &id039
      status: none
    slug: sugarcrm
    status: profiled
    tags: &id040
    - CRM
    - Company
    - Sales
    - Software-as-a-Service
    url: /providers/sugarcrm/
  layer: domain
  name: SugarCRM
  provider: sugarcrm
  says: ships the SugarCRM SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
  tier: observed
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
    agent_readiness: 56.4
    band: exemplar
    in_catalog: true
    kin_score: 90.3
    mcp: &id041
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id042
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://raw.githubusercontent.com/mautic/mautic/7.x/app/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.4
    band: emerging
    in_catalog: true
    kin_score: 25.7
    mcp: &id043
      status: none
    slug: vtiger
    status: profiled
    tags: &id044
    - Artificial Intelligence
    - CRM
    - Company
    - Sales
    url: /providers/vtiger/
  layer: domain
  name: Vtiger
  provider: vtiger
  says: ships the Vtiger SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 61.2
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id045
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id046
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X (Twitter)
  provider: x
  says: ships the X (Twitter) SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id047
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id048
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: ships the Zapier SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins
  tier: observed
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
    agent_readiness: 33.0
    band: strong
    in_catalog: true
    kin_score: 63.5
    mcp: &id049
      source: https://www.zoho.com/mcp/
      status: verified
    slug: zoho
    status: profiled
    tags: &id050
    - Analytics
    - CRM
    - Collaboration
    - Customer Service
    url: /providers/zoho/
  layer: domain
  name: Zoho CRM
  provider: zoho
  says: ships the Zoho CRM SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.4
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id003
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
  layer: domain
  name: Amazon SES
  provider: amazon-ses
  says: lists Amazon SES as an integration
  source: https://docs.mautic.org/en/7.0/channels/emails.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.1
    band: developing
    in_catalog: true
    kin_score: 39.5
    mcp: &id011
      source: https://github.com/ElasticEmail/elasticemail-mcp-server
      status: verified
    slug: elastic-email
    status: profiled
    tags: &id012
    - Company
    - Email
    - Marketing
    - Software-as-a-Service
    url: /providers/elastic-email/
  layer: domain
  name: Elastic Email
  provider: elastic-email
  says: lists Elastic Email as an integration
  source: https://docs.mautic.org/en/7.0/channels/emails.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.4
    band: developing
    in_catalog: true
    kin_score: 50.1
    mcp: &id027
      source: https://github.com/mailgun/mailjet-mcp-server
      status: verified
    slug: mailjet
    status: profiled
    tags: &id028
    - Email
    - Email Delivery
    - Marketing Email
    - SMTP
    url: /providers/mailjet/
  layer: domain
  name: Mailjet
  provider: mailjet
  says: lists Mailjet as an integration
  source: https://docs.mautic.org/en/7.0/channels/emails.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.1
    band: exemplar
    in_catalog: true
    kin_score: 87.3
    mcp: &id035
      status: none
    slug: sendgrid
    status: profiled
    tags: &id036
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: domain
  name: SendGrid
  provider: sendgrid
  says: lists SendGrid as an integration
  source: https://docs.mautic.org/en/7.0/channels/emails.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.1
    band: thin
    in_catalog: true
    kin_score: 37.9
    mcp: &id037
      status: none
    slug: sparkpost
    status: profiled
    tags: &id038
    - Email
    - Email Delivery
    - Marketing Email
    - Transactional Email
    url: /providers/sparkpost/
  layer: domain
  name: SparkPost
  provider: sparkpost
  says: lists SparkPost as an integration
  source: https://docs.mautic.org/en/7.0/channels/emails.html
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/email-marketing-newsletter/mautic/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 39.4
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id003
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id004
  url: /providers/amazon-ses/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id005
  name: Clearbit
  slug: clearbit
  status: profiled
  tags: *id006
  url: /providers/clearbit/
- agent_band: agent-aware
  agent_readiness: 20.8
  band: emerging
  in_catalog: true
  kin_score: 24.0
  mcp: *id007
  name: ConnectWise
  slug: connectwise
  status: profiled
  tags: *id008
  url: /providers/connectwise/
- agent_band: agent-ready
  agent_readiness: 32.1
  band: exemplar
  in_catalog: true
  kin_score: 70.9
  mcp: *id009
  name: Constant Contact
  slug: constant-contact
  status: profiled
  tags: *id010
  url: /providers/constant-contact/
- agent_band: agent-ready
  agent_readiness: 41.1
  band: developing
  in_catalog: true
  kin_score: 39.5
  mcp: *id011
  name: Elastic Email
  slug: elastic-email
  status: profiled
  tags: *id012
  url: /providers/elastic-email/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id013
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id014
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id015
  name: Foursquare
  slug: foursquare
  status: profiled
  tags: *id016
  url: /providers/foursquare/
- agent_band: agent-ready
  agent_readiness: 39.4
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id017
  name: FullContact
  slug: fullcontact
  status: profiled
  tags: *id018
  url: /providers/fullcontact/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id019
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id020
  url: /providers/hubspot/
- agent_band: agent-aware
  agent_readiness: 26.1
  band: strong
  in_catalog: true
  kin_score: 55.7
  mcp: *id021
  name: iContact
  slug: icontact
  status: profiled
  tags: *id022
  url: /providers/icontact/
- agent_band: agent-ready
  agent_readiness: 38.9
  band: exemplar
  in_catalog: true
  kin_score: 69.0
  mcp: *id023
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id024
  url: /providers/instagram/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.2
  mcp: *id025
  name: IP2Location
  slug: ip2location
  status: profiled
  tags: *id026
  url: /providers/ip2location/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: developing
  in_catalog: true
  kin_score: 50.1
  mcp: *id027
  name: Mailjet
  slug: mailjet
  status: profiled
  tags: *id028
  url: /providers/mailjet/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id029
  name: MaxMind
  slug: maxmind
  status: profiled
  tags: *id030
  url: /providers/maxmind/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: strong
  in_catalog: true
  kin_score: 63.9
  mcp: *id031
  name: Microsoft Dynamics 365
  slug: microsoft-dynamics-365
  status: profiled
  tags: *id032
  url: /providers/microsoft-dynamics-365/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id033
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id034
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id035
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id036
  url: /providers/sendgrid/
- agent_band: agent-aware
  agent_readiness: 26.1
  band: thin
  in_catalog: true
  kin_score: 37.9
  mcp: *id037
  name: SparkPost
  slug: sparkpost
  status: profiled
  tags: *id038
  url: /providers/sparkpost/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: exemplar
  in_catalog: true
  kin_score: 67.6
  mcp: *id039
  name: SugarCRM
  slug: sugarcrm
  status: profiled
  tags: *id040
  url: /providers/sugarcrm/
- agent_band: agent-native
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 90.3
  mcp: *id041
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id042
  url: /providers/twilio/
- agent_band: agent-aware
  agent_readiness: 14.4
  band: emerging
  in_catalog: true
  kin_score: 25.7
  mcp: *id043
  name: Vtiger
  slug: vtiger
  status: profiled
  tags: *id044
  url: /providers/vtiger/
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id045
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id046
  url: /providers/x/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id047
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id048
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: strong
  in_catalog: true
  kin_score: 63.5
  mcp: *id049
  name: Zoho CRM
  slug: zoho
  status: profiled
  tags: *id050
  url: /providers/zoho/
siblings:
- name: beehiiv
  rows: 22
  url: /applications/email-marketing-newsletter/beehiiv/
- name: Ghost
  rows: 17
  url: /applications/email-marketing-newsletter/ghost/
- name: Keila
  rows: 7
  url: /applications/email-marketing-newsletter/keila/
- name: Klaviyo
  rows: 15
  url: /applications/email-marketing-newsletter/klaviyo/
- name: listmonk
  rows: 13
  url: /applications/email-marketing-newsletter/listmonk/
- name: Mailchimp
  rows: 17
  url: /applications/email-marketing-newsletter/mailchimp/
- name: Substack
  rows: 4
  url: /applications/email-marketing-newsletter/substack/
sitemap: true
title: 'Mautic: Email Marketing & Newsletters reference app'
---
