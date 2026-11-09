---
app: Mautic
app_slug: mautic
app_url: https://github.com/mautic/mautic
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-400.70
  key: content-marketing-management
  layer: domain
  name: Content Marketing Management
  providers:
  - Foursquare
  url: /capabilities/content-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - ConnectWise
  - HubSpot
  - Microsoft Dynamics
  - Salesforce
  - SugarCRM
  - Vtiger
  - Zoho CRM
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.30.10
  key: AE-230.30.10
  layer: domain
  name: Data Enrichment
  providers:
  - Clearbit
  - FullContact
  url: /capabilities/company-contact-data/
  via_parent: Company & Contact Data
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Constant Contact
  - iContact
  - Mailchimp
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: domain
  name: IP Geolocation
  providers:
  - Extreme IP Lookup
  - Geobytes
  - GeoIPs
  - IP2Location
  - IPInfoDB
  - ipstack
  - MaxMind
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  - Outlook
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60.40
  key: BC-400.60.40
  layer: domain
  name: Social Media Management
  providers:
  - Facebook
  - Instagram
  - Twitter (X)
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - SendGrid
  - SparkPost
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-3710
  key: media-asset-management
  layer: common
  name: Media Asset Management
  providers:
  - Amazon S3
  url: /capabilities/media-asset-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
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
  id: marketing-automation
  name: Marketing Automation & Ads
  url: /applications/marketing-automation/
counts:
  declared: 3
  observed: 28
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/mautic/mautic/7.x/app/composer.json
- route: documentation
  url: https://docs.mautic.org/en/5.x/configuration/settings.html
- route: source code
  url: https://github.com/mautic/mautic/tree/7.x/app/bundles/CoreBundle/IpLookup
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
    attribution: API Evangelist extension
    id: AE-230.30.10
    key: AE-230.30.10
    name: Data Enrichment
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.2
    band: strong
    in_catalog: true
    kin_score: 57.9
    mcp: &id003
      status: none
    slug: clearbit
    status: profiled
    tags: &id004
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
    mcp: &id005
      source: https://www.connectwise.com/blog/what-mcp-could-mean-for-msps
      status: documented
    slug: connectwise
    status: profiled
    tags: &id006
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
    mcp: &id007
      status: none
    slug: constant-contact
    status: profiled
    tags: &id008
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
    kin_score: 8.7
    mcp: &id009
      status: unknown
    slug: extreme-ip-lookup
    status: profiled
    tags: &id010
    - Company
    - Data
    - Geolocation
    - IP
    url: /providers/extreme-ip-lookup/
  layer: domain
  name: Extreme IP Lookup
  provider: extreme-ip-lookup
  says: ships the Extreme IP Lookup SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/app/bundles/CoreBundle/IpLookup
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60.40
    key: BC-400.60.40
    name: Social Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id011
      status: none
    slug: facebook
    status: profiled
    tags: &id012
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
    id: BC-400.70
    key: content-marketing-management
    name: Content Marketing Management
    url: /capabilities/content-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: developing
    in_catalog: true
    kin_score: 47.7
    mcp: &id013
      source: https://github.com/foursquare/foursquare-places-mcp
      status: verified
    slug: foursquare
    status: profiled
    tags: &id014
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
    attribution: API Evangelist extension
    id: AE-230.30.10
    key: AE-230.30.10
    name: Data Enrichment
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.4
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id015
      status: none
    slug: fullcontact
    status: profiled
    tags: &id016
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
    kin_score: 6.2
    mcp: &id017
      status: unknown
    slug: geobytes
    status: profiled
    tags: &id018
    - Company
    - Free
    - Geolocation
    - IP
    url: /providers/geobytes/
  layer: domain
  name: Geobytes
  provider: geobytes
  says: ships the Geobytes SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/app/bundles/CoreBundle/IpLookup
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
    agent_readiness: 18.0
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id019
      source: https://github.com/iplocate/mcp-server-iplocate
      status: verified
    slug: iplocate
    status: profiled
    tags: &id020
    - Company
    - IP Geolocation
    - Privacy
    - Threat Detection
    url: /providers/iplocate/
  layer: domain
  name: GeoIPs
  provider: iplocate
  says: ships the GeoIPs SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/app/bundles/CoreBundle/IpLookup
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id021
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id022
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: domain
  name: Gmail
  provider: google-gmail
  says: ships the Gmail SDK or integration code
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
    mcp: &id025
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id026
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
    mcp: &id027
      status: none
    slug: icontact
    status: profiled
    tags: &id028
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
    id: BC-400.60.40
    key: BC-400.60.40
    name: Social Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.9
    band: exemplar
    in_catalog: true
    kin_score: 69.0
    mcp: &id029
      status: none
    slug: instagram
    status: profiled
    tags: &id030
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
    mcp: &id031
      source: https://github.com/ip2location/mcp-ip2location-io
      status: verified
    slug: ip2location
    status: profiled
    tags: &id032
    - Geocoding
    - Public APIs
    url: /providers/ip2location/
  layer: domain
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.2
    mcp: &id033
      status: none
    slug: ipinfodb
    status: profiled
    tags: &id034
    - Geocoding
    - Public APIs
    url: /providers/ipinfodb/
  layer: domain
  name: IPInfoDB
  provider: ipinfodb
  says: ships the IPInfoDB SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/app/bundles/CoreBundle/IpLookup
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
    agent_band: agent-ready
    agent_readiness: 32.7
    band: developing
    in_catalog: true
    kin_score: 47.1
    mcp: &id035
      status: none
    slug: ipstack
    status: profiled
    tags: &id036
    - Geocoding
    - IP Geolocation
    - Location
    - Threat Intelligence
    url: /providers/ipstack/
  layer: domain
  name: ipstack
  provider: ipstack
  says: ships the ipstack SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/app/bundles/CoreBundle/IpLookup
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
    agent_readiness: 42.3
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id037
      status: none
    slug: mailchimp
    status: profiled
    tags: &id038
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: domain
  name: Mailchimp
  provider: mailchimp
  says: ships the Mailchimp SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticEmailMarketingBundle/Integration
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
    mcp: &id039
      status: none
    slug: maxmind
    status: profiled
    tags: &id040
    - Fraud Prevention
    - Geolocation
    - IP Intelligence
    - Risk Scoring
    url: /providers/maxmind/
  layer: domain
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
    mcp: &id041
      source: https://github.com/microsoft/Dataverse-MCP
      status: verified
    slug: microsoft-dynamics-365
    status: profiled
    tags: &id042
    - Business Applications
    - CRM
    - Cloud
    - Enterprise
    url: /providers/microsoft-dynamics-365/
  layer: domain
  name: Microsoft Dynamics
  provider: microsoft-dynamics-365
  says: ships the Microsoft Dynamics SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 49.5
    band: exemplar
    in_catalog: true
    kin_score: 70.6
    mcp: &id043
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id044
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: domain
  name: Outlook
  provider: microsoft-outlook
  says: ships the Outlook SDK or integration code
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
    agent_readiness: 54.7
    band: exemplar
    in_catalog: true
    kin_score: 90.6
    mcp: &id045
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id046
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
    mcp: &id051
      status: none
    slug: sugarcrm
    status: profiled
    tags: &id052
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
    mcp: &id053
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id054
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
    id: BC-400.60.40
    key: BC-400.60.40
    name: Social Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 61.2
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id055
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id056
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: Twitter (X)
  provider: x
  says: ships the Twitter (X) SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticSocialBundle/Integration
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
    mcp: &id057
      status: none
    slug: vtiger
    status: profiled
    tags: &id058
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
    mcp: &id059
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id060
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
    agent_readiness: 44.2
    band: exemplar
    in_catalog: true
    kin_score: 86.0
    mcp: &id061
      status: none
    slug: zoho-crm
    status: profiled
    tags: &id062
    - CRM
    - Lead Management
    - Marketing Automation
    - Sales
    url: /providers/zoho-crm/
  layer: domain
  name: Zoho CRM
  provider: zoho-crm
  says: ships the Zoho CRM SDK or integration code
  source: https://github.com/mautic/mautic/tree/7.x/plugins/MauticCrmBundle/Integration
  tier: observed
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
    mcp: &id023
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id024
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://docs.mautic.org/en/5.x/configuration/settings.html
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
    mcp: &id047
      status: none
    slug: sendgrid
    status: profiled
    tags: &id048
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: lists SendGrid as an integration
  source: https://docs.mautic.org/en/5.x/configuration/settings.html
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
    mcp: &id049
      status: none
    slug: sparkpost
    status: profiled
    tags: &id050
    - Email
    - Email Delivery
    - Marketing Email
    - Transactional Email
    url: /providers/sparkpost/
  layer: common
  name: SparkPost
  provider: sparkpost
  says: lists SparkPost as an integration
  source: https://docs.mautic.org/en/5.x/configuration/settings.html
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/marketing-automation/mautic/
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
- agent_band: agent-aware
  agent_readiness: 25.2
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id003
  name: Clearbit
  slug: clearbit
  status: profiled
  tags: *id004
  url: /providers/clearbit/
- agent_band: agent-aware
  agent_readiness: 20.8
  band: emerging
  in_catalog: true
  kin_score: 24.0
  mcp: *id005
  name: ConnectWise
  slug: connectwise
  status: profiled
  tags: *id006
  url: /providers/connectwise/
- agent_band: agent-ready
  agent_readiness: 32.1
  band: exemplar
  in_catalog: true
  kin_score: 70.9
  mcp: *id007
  name: Constant Contact
  slug: constant-contact
  status: profiled
  tags: *id008
  url: /providers/constant-contact/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.7
  mcp: *id009
  name: Extreme IP Lookup
  slug: extreme-ip-lookup
  status: profiled
  tags: *id010
  url: /providers/extreme-ip-lookup/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id011
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id012
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id013
  name: Foursquare
  slug: foursquare
  status: profiled
  tags: *id014
  url: /providers/foursquare/
- agent_band: agent-ready
  agent_readiness: 39.4
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id015
  name: FullContact
  slug: fullcontact
  status: profiled
  tags: *id016
  url: /providers/fullcontact/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.2
  mcp: *id017
  name: Geobytes
  slug: geobytes
  status: profiled
  tags: *id018
  url: /providers/geobytes/
- agent_band: agent-aware
  agent_readiness: 18.0
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id019
  name: GeoIPs
  slug: iplocate
  status: profiled
  tags: *id020
  url: /providers/iplocate/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id021
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id022
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id023
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id024
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id025
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id026
  url: /providers/hubspot/
- agent_band: agent-aware
  agent_readiness: 26.1
  band: strong
  in_catalog: true
  kin_score: 55.7
  mcp: *id027
  name: iContact
  slug: icontact
  status: profiled
  tags: *id028
  url: /providers/icontact/
- agent_band: agent-ready
  agent_readiness: 38.9
  band: exemplar
  in_catalog: true
  kin_score: 69.0
  mcp: *id029
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id030
  url: /providers/instagram/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.2
  mcp: *id031
  name: IP2Location
  slug: ip2location
  status: profiled
  tags: *id032
  url: /providers/ip2location/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.2
  mcp: *id033
  name: IPInfoDB
  slug: ipinfodb
  status: profiled
  tags: *id034
  url: /providers/ipinfodb/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: developing
  in_catalog: true
  kin_score: 47.1
  mcp: *id035
  name: ipstack
  slug: ipstack
  status: profiled
  tags: *id036
  url: /providers/ipstack/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id037
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id038
  url: /providers/mailchimp/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id039
  name: MaxMind
  slug: maxmind
  status: profiled
  tags: *id040
  url: /providers/maxmind/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: strong
  in_catalog: true
  kin_score: 63.9
  mcp: *id041
  name: Microsoft Dynamics
  slug: microsoft-dynamics-365
  status: profiled
  tags: *id042
  url: /providers/microsoft-dynamics-365/
- agent_band: agent-ready
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 70.6
  mcp: *id043
  name: Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id044
  url: /providers/microsoft-outlook/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id045
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id046
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id047
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id048
  url: /providers/sendgrid/
- agent_band: agent-aware
  agent_readiness: 26.1
  band: thin
  in_catalog: true
  kin_score: 37.9
  mcp: *id049
  name: SparkPost
  slug: sparkpost
  status: profiled
  tags: *id050
  url: /providers/sparkpost/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: exemplar
  in_catalog: true
  kin_score: 67.6
  mcp: *id051
  name: SugarCRM
  slug: sugarcrm
  status: profiled
  tags: *id052
  url: /providers/sugarcrm/
- agent_band: agent-native
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 90.3
  mcp: *id053
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id054
  url: /providers/twilio/
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id055
  name: Twitter (X)
  slug: x
  status: profiled
  tags: *id056
  url: /providers/x/
- agent_band: agent-aware
  agent_readiness: 14.4
  band: emerging
  in_catalog: true
  kin_score: 25.7
  mcp: *id057
  name: Vtiger
  slug: vtiger
  status: profiled
  tags: *id058
  url: /providers/vtiger/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id059
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id060
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 44.2
  band: exemplar
  in_catalog: true
  kin_score: 86.0
  mcp: *id061
  name: Zoho CRM
  slug: zoho-crm
  status: profiled
  tags: *id062
  url: /providers/zoho-crm/
siblings:
- name: Braze
  rows: 31
  url: /applications/marketing-automation/braze/
- name: Customer.io
  rows: 21
  url: /applications/marketing-automation/customer-io/
- name: Dittofeed
  rows: 14
  url: /applications/marketing-automation/dittofeed/
- name: HubSpot Marketing Hub
  rows: 15
  url: /applications/marketing-automation/hubspot-marketing-hub/
- name: Laudspeaker
  rows: 13
  url: /applications/marketing-automation/laudspeaker/
- name: Mailchimp
  rows: 5
  url: /applications/marketing-automation/mailchimp/
sitemap: true
title: 'Mautic: Marketing Automation & Ads reference app'
---
