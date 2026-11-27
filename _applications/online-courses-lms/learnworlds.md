---
app: LearnWorlds
app_slug: learnworlds
app_url: https://www.learnworlds.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4720.50
  key: graduation-credentialing
  layer: domain
  name: Graduation & Credentialing
  providers:
  - Accredible
  - Credly
  url: /capabilities/graduation-credentialing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Google Meet
  - Microsoft Teams
  - Webex
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.10.10
  key: AE-170.10.10
  layer: domain
  name: Video Hosting & Encoding
  providers:
  - Vimeo
  - Wistia
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
- attribution: Turbo EA
  id: BC-3780.50
  key: BC-3780.50
  layer: common
  name: Accessibility Compliance Management
  providers:
  - accessiBe
  url: /capabilities/content-compliance-standards-management/
  via_parent: Content Compliance & Standards Management
- attribution: API Evangelist extension
  id: AE-140.30.10
  key: AE-140.30.10
  layer: common
  name: Buy Now, Pay Later
  providers:
  - Afterpay
  - Klarna
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - HubSpot
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Freshchat
  - Intercom
  - Olark
  - Tawk.to
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.30.20
  key: AE-140.30.20
  layer: common
  name: Digital & Mobile Wallets
  providers:
  - Apple Pay
  - Google Pay
  url: /capabilities/consumer-payment-options/
  via_parent: Consumer Payment Options
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - BDOW!
  - Facebook Pixel
  - Google Search
  - OptinMonster
  - ReferralCandy
  - Refersion
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - ActiveCampaign
  - AWeber
  - Constant Contact
  - GetResponse
  - Kit
  - Mailchimp
  - MailerLite
  - Moosend
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: common
  name: Hosted Storefronts
  providers:
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-220.20
  key: indirect-tax-management
  layer: common
  name: Indirect Tax Management
  providers:
  - Quaderno
  - Stripe Tax
  url: /capabilities/indirect-tax-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: common
  name: Machine Translation
  providers:
  - Weglot
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Bancontact
  - iDEAL
  - PayPal
  - Przelewy24
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - FullSession
  - FullStory
  - Google Analytics
  - Hotjar
  - Mixpanel
  - Mouseflow
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: common
  name: Reviews & Social Proof
  providers:
  - FOMO
  url: /capabilities/reviews-social-proof/
  via_parent: null
- attribution: Turbo EA
  id: BC-2800.10
  key: scheduling-appointment-management
  layer: common
  name: Scheduling & Appointment Management
  providers:
  - Calendly
  url: /capabilities/scheduling-appointment-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: common
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Integrately
  - Make
  - Pabbly
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: online-courses-lms
  name: Online Courses & Learning Management
  url: /applications/online-courses-lms/
counts:
  declared: 55
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.learnworlds.com/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3780.50
    key: BC-3780.50
    name: Accessibility Compliance Management
    url: /capabilities/content-compliance-standards-management/
    via_parent: Content Compliance & Standards Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 44.3
    band: strong
    in_catalog: true
    kin_score: 55.4
    mcp: &id002
      source: https://www.npmjs.com/package/accessflow-mcp-server
      status: verified
    slug: accessibe
    status: profiled
    tags: &id003
    - Accessibility
    - Company
    - WCAG
    - Web Accessibility
    url: /providers/accessibe/
  layer: common
  name: accessiBe
  provider: accessibe
  says: lists accessiBe as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4720.50
    key: graduation-credentialing
    name: Graduation & Credentialing
    url: /capabilities/graduation-credentialing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: thin
    in_catalog: true
    kin_score: 28.3
    mcp: &id004
      status: none
    slug: accredible
    status: profiled
    tags: &id005
    - Badges
    - Certificates
    - Digital Credentials
    - Open Badges
    url: /providers/accredible/
  layer: domain
  name: Accredible
  provider: accredible
  says: lists Accredible as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 51.0
    band: exemplar
    in_catalog: true
    kin_score: 81.1
    mcp: &id006
      source: https://developers.activecampaign.com/page/mcp
      status: documented
    slug: activecampaign
    status: profiled
    tags: &id007
    - CRM
    - Email Marketing
    - Marketing Automation
    - Sales Automation
    url: /providers/activecampaign/
  layer: common
  name: ActiveCampaign
  provider: activecampaign
  says: lists ActiveCampaign as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.10
    key: AE-140.30.10
    name: Buy Now, Pay Later
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.8
    band: minimal
    in_catalog: true
    kin_score: 9.2
    mcp: &id008
      status: none
    slug: afterpay
    status: profiled
    tags: &id009
    - Buy Now Pay Later
    - Consumer
    - Fintech
    - Payments
    url: /providers/afterpay/
  layer: common
  name: Afterpay
  provider: afterpay
  says: lists Afterpay as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.20
    key: AE-140.30.20
    name: Digital & Mobile Wallets
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.4
    band: developing
    in_catalog: true
    kin_score: 43.0
    mcp: &id010
      status: none
    slug: apple-pay
    status: profiled
    tags: &id011
    - Apple
    - Contactless Payments
    - Digital Wallet
    - E-Commerce
    url: /providers/apple-pay/
  layer: common
  name: Apple Pay
  provider: apple-pay
  says: lists Apple Pay as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id012
      source: https://github.com/aweber/aweber-mcp
      status: verified
    slug: aweber
    status: profiled
    tags: &id013
    - Email
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/aweber/
  layer: common
  name: AWeber
  provider: aweber
  says: lists AWeber as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 49.8
    band: strong
    in_catalog: true
    kin_score: 62.1
    mcp: &id014
      status: none
    slug: bancontact
    status: profiled
    tags: &id015
    - Banking
    - Belgium
    - Debit Cards
    - E-Commerce
    url: /providers/bancontact/
  layer: common
  name: Bancontact
  provider: bancontact
  says: lists Bancontact as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 18.4
    mcp: &id016
      status: unknown
    slug: bdow
    status: profiled
    tags: &id017
    - Company
    url: /providers/bdow/
  layer: common
  name: BDOW!
  provider: bdow
  says: lists BDOW! as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.4
    band: developing
    in_catalog: true
    kin_score: 47.5
    mcp: &id018
      source: https://developer.calendly.com/calendly-mcp-server
      status: documented
    slug: calendly
    status: profiled
    tags: &id019
    - Appointments
    - Automation
    - Booking
    - Calendar
    url: /providers/calendly/
  layer: common
  name: Calendly
  provider: calendly
  says: lists Calendly as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 31.4
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id020
      status: none
    slug: constant-contact
    status: profiled
    tags: &id021
    - Campaigns
    - Contacts
    - Email Marketing
    - Event
    url: /providers/constant-contact/
  layer: common
  name: Constant Contact
  provider: constant-contact
  says: lists Constant Contact as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4720.50
    key: graduation-credentialing
    name: Graduation & Credentialing
    url: /capabilities/graduation-credentialing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.4
    band: thin
    in_catalog: true
    kin_score: 28.5
    mcp: &id022
      status: none
    slug: credly
    status: profiled
    tags: &id023
    - Badging
    - Certification
    - Digital Credentials
    - Open Badges
    url: /providers/credly/
  layer: domain
  name: Credly
  provider: credly
  says: lists Credly as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id024
      status: none
    slug: facebook
    status: profiled
    tags: &id025
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook Pixel
  provider: facebook
  says: lists Facebook Pixel as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id026
      status: unchecked
    slug: fomo-com
    status: queued for profiling
    tags: &id027 []
    url: null
  layer: common
  name: FOMO
  provider: fomo-com
  says: lists FOMO as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 23.4
    band: thin
    in_catalog: true
    kin_score: 36.2
    mcp: &id028
      status: none
    slug: freshchat
    status: profiled
    tags: &id029
    - Conversational Engagement
    - Customer Messaging
    - Customer Service
    - Live Chat
    url: /providers/freshchat/
  layer: common
  name: Freshchat
  provider: freshchat
  says: lists Freshchat as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 21.1
    band: emerging
    in_catalog: true
    kin_score: 22.9
    mcp: &id030
      source: https://docs.fullsession.io/mcp-server
      status: verified
    slug: fullsession
    status: profiled
    tags: &id031
    - Analytics
    - Artificial Intelligence
    - Session Replay
    - Web
    url: /providers/fullsession/
  layer: common
  name: FullSession
  provider: fullsession
  says: lists FullSession as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 30.0
    band: thin
    in_catalog: true
    kin_score: 37.4
    mcp: &id032
      source: https://developer.fullstory.com/mcp/introduction/
      status: documented
    slug: fullstory
    status: profiled
    tags: &id033
    - Behavioral Analytics
    - Digital Experience
    - Product Analytics
    - Session Replay
    url: /providers/fullstory/
  layer: common
  name: FullStory
  provider: fullstory
  says: lists FullStory as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 48.9
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id034
      status: none
    slug: getresponse
    status: profiled
    tags: &id035
    - Email Marketing
    - Landing Pages
    - Marketing Automation
    - Webinars
    url: /providers/getresponse/
  layer: common
  name: GetResponse
  provider: getresponse
  says: lists GetResponse as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id036
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id037
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
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
    agent_readiness: 34.9
    band: developing
    in_catalog: true
    kin_score: 52.2
    mcp: &id038
      status: none
    slug: google-meet
    status: profiled
    tags: &id039
    - Google
    - Google Workspace
    - Meetings
    - Recording
    url: /providers/google-meet/
  layer: domain
  name: Google Meet
  provider: google-meet
  says: lists Google Meet as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.20
    key: AE-140.30.20
    name: Digital & Mobile Wallets
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.7
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id040
      status: none
    slug: google-pay
    status: profiled
    tags: &id041
    - Agentic Commerce
    - Checkout
    - Contactless Payments
    - Digital Wallet
    url: /providers/google-pay/
  layer: common
  name: Google Pay
  provider: google-pay
  says: lists Google Pay as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 30.7
    band: exemplar
    in_catalog: true
    kin_score: 69.7
    mcp: &id042
      status: none
    slug: google-search-console
    status: profiled
    tags: &id043
    - Analytics
    - Google
    - Indexing
    - Search
    url: /providers/google-search-console/
  layer: common
  name: Google Search
  provider: google-search-console
  says: lists Google Search as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id044
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id045
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: lists Google Tag Manager as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 27.3
    band: emerging
    in_catalog: true
    kin_score: 25.5
    mcp: &id046
      status: none
    slug: hotjar
    status: profiled
    tags: &id047
    - Analytics
    - Personalization
    - Surveys
    - Tracking
    url: /providers/hotjar/
  layer: common
  name: Hotjar
  provider: hotjar
  says: lists Hotjar as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id048
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id049
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: common
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.8
    mcp: &id050
      status: unknown
    slug: ideal
    status: profiled
    tags: &id051
    - Banking
    - E-Commerce
    - Europe
    - Payments
    url: /providers/ideal/
  layer: common
  name: iDEAL
  provider: ideal
  says: lists iDEAL as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.4
    band: developing
    in_catalog: true
    kin_score: 45.4
    mcp: &id052
      status: none
    slug: integrately
    status: profiled
    tags: &id053
    - Automation
    - Business Process Automation
    - No-Code
    - iPaaS
    url: /providers/integrately/
  layer: common
  name: Integrately
  provider: integrately
  says: lists Integrately as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 32.5
    band: developing
    in_catalog: true
    kin_score: 51.0
    mcp: &id054
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id055
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: common
  name: Intercom
  provider: intercom
  says: lists Intercom as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 80.4
    mcp: &id056
      status: none
    slug: convertkit
    status: profiled
    tags: &id057
    - Automation
    - Creator Economy
    - Email Marketing
    - Subscribers
    url: /providers/convertkit/
  layer: common
  name: Kit
  provider: convertkit
  says: lists Kit as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.10
    key: AE-140.30.10
    name: Buy Now, Pay Later
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id058
      status: none
    slug: klarna
    status: profiled
    tags: &id059
    - Buy Now Pay Later
    - Cards
    - Fintech
    - Payments
    url: /providers/klarna/
  layer: common
  name: Klarna
  provider: klarna
  says: lists Klarna as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id060
      status: none
    slug: mailchimp
    status: profiled
    tags: &id061
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 53.4
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id062
      source: https://developers.mailerlite.com/
      status: documented
    slug: mailerlite
    status: profiled
    tags: &id063
    - Automation
    - Email Marketing
    - Newsletters
    - Subscribers
    url: /providers/mailerlite/
  layer: common
  name: MailerLite
  provider: mailerlite
  says: lists MailerLite as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
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
    agent_readiness: 43.0
    band: developing
    in_catalog: true
    kin_score: 43.4
    mcp: &id064
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id065
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
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
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id066
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id067
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id068
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id069
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: lists Mixpanel as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 33.6
    band: strong
    in_catalog: true
    kin_score: 60.3
    mcp: &id070
      status: none
    slug: moosend
    status: profiled
    tags: &id071
    - Campaigns
    - Email Marketing
    - Mailing Lists
    - Marketing Automation
    url: /providers/moosend/
  layer: common
  name: Moosend
  provider: moosend
  says: lists Moosend as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 24.2
    mcp: &id072
      source: https://mouseflow.com/platform/ai/mcp-server/
      status: verified
    slug: mouseflow
    status: profiled
    tags: &id073
    - Company
    url: /providers/mouseflow/
  layer: common
  name: Mouseflow
  provider: mouseflow
  says: lists Mouseflow as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 42.4
    band: thin
    in_catalog: true
    kin_score: 31.3
    mcp: &id074
      status: none
    slug: olark
    status: profiled
    tags: &id075
    - Chatbots
    - Customer Engagement
    - Customer Service
    - Live Chat
    url: /providers/olark/
  layer: common
  name: Olark
  provider: olark
  says: lists Olark as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 53.1
    mcp: &id076
      status: none
    slug: optinmonster
    status: profiled
    tags: &id077
    - Company
    - Conversion Optimization
    - Lead Generation
    - Marketing
    url: /providers/optinmonster/
  layer: common
  name: OptinMonster
  provider: optinmonster
  says: lists OptinMonster as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
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
    agent_readiness: 28.9
    band: developing
    in_catalog: true
    kin_score: 53.6
    mcp: &id078
      status: none
    slug: pabbly
    status: profiled
    tags: &id079
    - Automation
    - Billing
    - Email Marketing
    - Subscription Billing
    url: /providers/pabbly/
  layer: common
  name: Pabbly
  provider: pabbly
  says: lists Pabbly as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id080
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id081
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.3
    band: thin
    in_catalog: true
    kin_score: 36.9
    mcp: &id082
      status: none
    slug: przelewy24
    status: profiled
    tags: &id083
    - BLIK
    - Bank Transfers
    - Payment Gateway
    - Payments
    url: /providers/przelewy24/
  layer: common
  name: Przelewy24
  provider: przelewy24
  says: lists Przelewy24 as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.6
    band: thin
    in_catalog: true
    kin_score: 28.5
    mcp: &id084
      status: none
    slug: quaderno
    status: profiled
    tags: &id085
    - Invoicing
    - Sales Tax
    - Tax Compliance
    - VAT
    url: /providers/quaderno/
  layer: common
  name: Quaderno
  provider: quaderno
  says: lists Quaderno as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id086
      status: none
    slug: referralcandy
    status: profiled
    tags: &id087
    - Affiliates
    - Company
    - E-Commerce
    - Referrals
    url: /providers/referralcandy/
  layer: common
  name: ReferralCandy
  provider: referralcandy
  says: lists ReferralCandy as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 38.0
    band: strong
    in_catalog: true
    kin_score: 61.4
    mcp: &id088
      status: none
    slug: refersion
    status: profiled
    tags: &id089
    - Affiliate Marketing
    - E-Commerce
    - Influencer Marketing
    - Referral Tracking
    url: /providers/refersion/
  layer: common
  name: Refersion
  provider: refersion
  says: lists Refersion as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id090
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id091
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: common
  name: Shopify
  provider: shopify
  says: lists Shopify as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id092
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id093
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: Stripe Tax
  provider: stripe
  says: lists Stripe Tax as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 16.9
    band: thin
    in_catalog: true
    kin_score: 36.3
    mcp: &id094
      status: none
    slug: tawk-to
    status: profiled
    tags: &id095
    - Company
    - Customer Service
    - FreeSoftware
    - Live Chat
    url: /providers/tawk-to/
  layer: common
  name: Tawk.to
  provider: tawk-to
  says: lists Tawk.to as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: thin
    in_catalog: true
    kin_score: 37.6
    mcp: &id096
      source: https://developer.vimeo.com/api/mcp-server
      status: documented
    slug: vimeo
    status: profiled
    tags: &id097
    - Live Streaming
    - Streaming
    - Video
    - Video Hosting
    url: /providers/vimeo/
  layer: domain
  name: Vimeo
  provider: vimeo
  says: lists Vimeo as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
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
    agent_readiness: 61.8
    band: strong
    in_catalog: true
    kin_score: 66.1
    mcp: &id098
      source: https://github.com/WebexSamples/webex-messaging-mcp-server
      status: verified
    slug: webex
    status: profiled
    tags: &id099
    - Calling
    - Collaboration
    - Communications
    - Enterprise
    url: /providers/webex/
  layer: domain
  name: Webex
  provider: webex
  says: lists Webex as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id100
      status: none
    slug: weglot
    status: profiled
    tags: &id101
    - Internationalization
    - Localization
    - Machine Translation
    - Translation
    url: /providers/weglot/
  layer: common
  name: Weglot
  provider: weglot
  says: lists Weglot as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.6
    band: exemplar
    in_catalog: true
    kin_score: 75.5
    mcp: &id102
      source: https://docs.wistia.com/docs/mcp-server-guide
      status: documented
    slug: wistia
    status: profiled
    tags: &id103
    - Lead Generation
    - Video Analytics
    - Video Hosting
    - Video Marketing
    url: /providers/wistia/
  layer: domain
  name: Wistia
  provider: wistia
  says: lists Wistia as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
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
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id104
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id105
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.learnworlds.com/integrations/
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
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id106
      status: none
    slug: zendesk
    status: profiled
    tags: &id107
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: common
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
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
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id108
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id109
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: domain
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://www.learnworlds.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/online-courses-lms/learnworlds/
providers:
- agent_band: agent-native
  agent_readiness: 44.3
  band: strong
  in_catalog: true
  kin_score: 55.4
  mcp: *id002
  name: accessiBe
  slug: accessibe
  status: profiled
  tags: *id003
  url: /providers/accessibe/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: thin
  in_catalog: true
  kin_score: 28.3
  mcp: *id004
  name: Accredible
  slug: accredible
  status: profiled
  tags: *id005
  url: /providers/accredible/
- agent_band: agent-ready
  agent_readiness: 51.0
  band: exemplar
  in_catalog: true
  kin_score: 81.1
  mcp: *id006
  name: ActiveCampaign
  slug: activecampaign
  status: profiled
  tags: *id007
  url: /providers/activecampaign/
- agent_band: agent-aware
  agent_readiness: 12.8
  band: minimal
  in_catalog: true
  kin_score: 9.2
  mcp: *id008
  name: Afterpay
  slug: afterpay
  status: profiled
  tags: *id009
  url: /providers/afterpay/
- agent_band: agent-ready
  agent_readiness: 30.4
  band: developing
  in_catalog: true
  kin_score: 43.0
  mcp: *id010
  name: Apple Pay
  slug: apple-pay
  status: profiled
  tags: *id011
  url: /providers/apple-pay/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id012
  name: AWeber
  slug: aweber
  status: profiled
  tags: *id013
  url: /providers/aweber/
- agent_band: agent-native
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 62.1
  mcp: *id014
  name: Bancontact
  slug: bancontact
  status: profiled
  tags: *id015
  url: /providers/bancontact/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.4
  mcp: *id016
  name: BDOW!
  slug: bdow
  status: profiled
  tags: *id017
  url: /providers/bdow/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: developing
  in_catalog: true
  kin_score: 47.5
  mcp: *id018
  name: Calendly
  slug: calendly
  status: profiled
  tags: *id019
  url: /providers/calendly/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id020
  name: Constant Contact
  slug: constant-contact
  status: profiled
  tags: *id021
  url: /providers/constant-contact/
- agent_band: agent-ready
  agent_readiness: 30.4
  band: thin
  in_catalog: true
  kin_score: 28.5
  mcp: *id022
  name: Credly
  slug: credly
  status: profiled
  tags: *id023
  url: /providers/credly/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id024
  name: Facebook Pixel
  slug: facebook
  status: profiled
  tags: *id025
  url: /providers/facebook/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id026
  name: FOMO
  slug: fomo-com
  status: queued for profiling
  tags: *id027
  url: null
- agent_band: agent-aware
  agent_readiness: 23.4
  band: thin
  in_catalog: true
  kin_score: 36.2
  mcp: *id028
  name: Freshchat
  slug: freshchat
  status: profiled
  tags: *id029
  url: /providers/freshchat/
- agent_band: agent-aware
  agent_readiness: 21.1
  band: emerging
  in_catalog: true
  kin_score: 22.9
  mcp: *id030
  name: FullSession
  slug: fullsession
  status: profiled
  tags: *id031
  url: /providers/fullsession/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: thin
  in_catalog: true
  kin_score: 37.4
  mcp: *id032
  name: FullStory
  slug: fullstory
  status: profiled
  tags: *id033
  url: /providers/fullstory/
- agent_band: agent-ready
  agent_readiness: 48.9
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id034
  name: GetResponse
  slug: getresponse
  status: profiled
  tags: *id035
  url: /providers/getresponse/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id036
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id037
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: developing
  in_catalog: true
  kin_score: 52.2
  mcp: *id038
  name: Google Meet
  slug: google-meet
  status: profiled
  tags: *id039
  url: /providers/google-meet/
- agent_band: agent-ready
  agent_readiness: 39.7
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id040
  name: Google Pay
  slug: google-pay
  status: profiled
  tags: *id041
  url: /providers/google-pay/
- agent_band: agent-ready
  agent_readiness: 30.7
  band: exemplar
  in_catalog: true
  kin_score: 69.7
  mcp: *id042
  name: Google Search
  slug: google-search-console
  status: profiled
  tags: *id043
  url: /providers/google-search-console/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id044
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id045
  url: /providers/google-tag-manager/
- agent_band: agent-aware
  agent_readiness: 27.3
  band: emerging
  in_catalog: true
  kin_score: 25.5
  mcp: *id046
  name: Hotjar
  slug: hotjar
  status: profiled
  tags: *id047
  url: /providers/hotjar/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id048
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id049
  url: /providers/hubspot/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.8
  mcp: *id050
  name: iDEAL
  slug: ideal
  status: profiled
  tags: *id051
  url: /providers/ideal/
- agent_band: agent-aware
  agent_readiness: 19.4
  band: developing
  in_catalog: true
  kin_score: 45.4
  mcp: *id052
  name: Integrately
  slug: integrately
  status: profiled
  tags: *id053
  url: /providers/integrately/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id054
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id055
  url: /providers/intercom/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 80.4
  mcp: *id056
  name: Kit
  slug: convertkit
  status: profiled
  tags: *id057
  url: /providers/convertkit/
- agent_band: agent-native
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id058
  name: Klarna
  slug: klarna
  status: profiled
  tags: *id059
  url: /providers/klarna/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id060
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id061
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 53.4
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id062
  name: MailerLite
  slug: mailerlite
  status: profiled
  tags: *id063
  url: /providers/mailerlite/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id064
  name: Make
  slug: make
  status: profiled
  tags: *id065
  url: /providers/make/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id066
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id067
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id068
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id069
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 33.6
  band: strong
  in_catalog: true
  kin_score: 60.3
  mcp: *id070
  name: Moosend
  slug: moosend
  status: profiled
  tags: *id071
  url: /providers/moosend/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 24.2
  mcp: *id072
  name: Mouseflow
  slug: mouseflow
  status: profiled
  tags: *id073
  url: /providers/mouseflow/
- agent_band: agent-ready
  agent_readiness: 42.4
  band: thin
  in_catalog: true
  kin_score: 31.3
  mcp: *id074
  name: Olark
  slug: olark
  status: profiled
  tags: *id075
  url: /providers/olark/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 53.1
  mcp: *id076
  name: OptinMonster
  slug: optinmonster
  status: profiled
  tags: *id077
  url: /providers/optinmonster/
- agent_band: agent-ready
  agent_readiness: 28.9
  band: developing
  in_catalog: true
  kin_score: 53.6
  mcp: *id078
  name: Pabbly
  slug: pabbly
  status: profiled
  tags: *id079
  url: /providers/pabbly/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id080
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id081
  url: /providers/paypal/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: thin
  in_catalog: true
  kin_score: 36.9
  mcp: *id082
  name: Przelewy24
  slug: przelewy24
  status: profiled
  tags: *id083
  url: /providers/przelewy24/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: thin
  in_catalog: true
  kin_score: 28.5
  mcp: *id084
  name: Quaderno
  slug: quaderno
  status: profiled
  tags: *id085
  url: /providers/quaderno/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id086
  name: ReferralCandy
  slug: referralcandy
  status: profiled
  tags: *id087
  url: /providers/referralcandy/
- agent_band: agent-ready
  agent_readiness: 38.0
  band: strong
  in_catalog: true
  kin_score: 61.4
  mcp: *id088
  name: Refersion
  slug: refersion
  status: profiled
  tags: *id089
  url: /providers/refersion/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id090
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id091
  url: /providers/shopify/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id092
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id093
  url: /providers/stripe/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: thin
  in_catalog: true
  kin_score: 36.3
  mcp: *id094
  name: Tawk.to
  slug: tawk-to
  status: profiled
  tags: *id095
  url: /providers/tawk-to/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id096
  name: Vimeo
  slug: vimeo
  status: profiled
  tags: *id097
  url: /providers/vimeo/
- agent_band: agent-ready
  agent_readiness: 61.8
  band: strong
  in_catalog: true
  kin_score: 66.1
  mcp: *id098
  name: Webex
  slug: webex
  status: profiled
  tags: *id099
  url: /providers/webex/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id100
  name: Weglot
  slug: weglot
  status: profiled
  tags: *id101
  url: /providers/weglot/
- agent_band: agent-ready
  agent_readiness: 40.6
  band: exemplar
  in_catalog: true
  kin_score: 75.5
  mcp: *id102
  name: Wistia
  slug: wistia
  status: profiled
  tags: *id103
  url: /providers/wistia/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id104
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id105
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id106
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id107
  url: /providers/zendesk/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id108
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id109
  url: /providers/zoom/
siblings:
- name: Canvas LMS
  rows: 25
  url: /applications/online-courses-lms/canvas-lms/
- name: Chamilo
  rows: 13
  url: /applications/online-courses-lms/chamilo/
- name: Coursera
  rows: 4
  url: /applications/online-courses-lms/coursera/
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
title: 'LearnWorlds: Online Courses & Learning Management reference app'
---
