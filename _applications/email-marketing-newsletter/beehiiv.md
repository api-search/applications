---
app: beehiiv
app_slug: beehiiv
app_url: https://www.beehiiv.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: domain
  name: Content Management
  providers:
  - Webflow
  - WordPress
  url: /capabilities/content-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.70
  key: content-marketing-management
  layer: domain
  name: Content Marketing Management
  providers:
  - ClickFunnels
  url: /capabilities/content-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: domain
  name: Customer Feedback Management
  providers:
  - OptinMonster
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Facebook Lead Ads
  - ManyChat
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-913
  key: AE-913
  layer: domain
  name: Link Shortening & Link-in-Bio
  providers:
  - Linktree
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-220.10
  key: AE-220.10
  layer: domain
  name: Online Courses
  providers:
  - Thinkific
  url: /capabilities/online-courses/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: domain
  name: Online Forms & Survey Collection
  providers:
  - Formstack
  - Typeform
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: Turbo EA
  id: BC-2320.10
  key: sales-transaction-management
  layer: domain
  name: Sales Transaction Management
  providers:
  - WooCommerce
  url: /capabilities/sales-transaction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4250
  key: subscription-billing-revenue-management
  layer: domain
  name: Subscription Billing & Revenue Management
  providers:
  - Gumroad
  - Memberful
  - MemberPress
  - Patreon
  - Recurly
  - Stripe
  url: /capabilities/subscription-billing-revenue-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Discord
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Make
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: email-marketing-newsletter
  name: Email Marketing & Newsletters
  url: /applications/email-marketing-newsletter/
counts:
  declared: 22
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.beehiiv.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-400.70
    key: content-marketing-management
    name: Content Marketing Management
    url: /capabilities/content-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 49.3
    band: exemplar
    in_catalog: true
    kin_score: 72.5
    mcp: &id001
      status: none
    slug: clickfunnels
    status: profiled
    tags: &id002
    - E-Commerce
    - Landing Pages
    - Marketing
    - Sales Funnels
    url: /providers/clickfunnels/
  layer: domain
  name: ClickFunnels
  provider: clickfunnels
  says: lists ClickFunnels as an integration
  source: https://www.beehiiv.com/integrations
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
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id003
      status: none
    slug: discord
    status: profiled
    tags: &id004
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: Discord
  provider: discord
  says: lists Discord as an integration
  source: https://www.beehiiv.com/integrations
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
    mcp: &id005
      status: none
    slug: facebook
    status: profiled
    tags: &id006
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook Lead Ads
  provider: facebook
  says: lists Facebook Lead Ads as an integration
  source: https://www.beehiiv.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.2
    band: emerging
    in_catalog: true
    kin_score: 24.4
    mcp: &id007
      status: none
    slug: formstack
    status: profiled
    tags: &id008
    - Documents
    - E-Signature
    - Forms
    - Workflow Automation
    url: /providers/formstack/
  layer: domain
  name: Formstack
  provider: formstack
  says: lists Formstack as an integration
  source: https://www.beehiiv.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.5
    band: emerging
    in_catalog: true
    kin_score: 22.8
    mcp: &id009
      status: none
    slug: gumroad
    status: profiled
    tags: &id010
    - Creator Economy
    - Digital Commerce
    - Digital Products
    - Membership
    url: /providers/gumroad/
  layer: domain
  name: Gumroad
  provider: gumroad
  says: lists Gumroad as an integration
  source: https://www.beehiiv.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.8
    band: developing
    in_catalog: true
    kin_score: 54.1
    mcp: &id011
      status: none
    slug: linktree
    status: profiled
    tags: &id012
    - Company
    - Creator Economy
    - Link-in-bio
    - Media
    url: /providers/linktree/
  layer: domain
  name: Linktree
  provider: linktree
  says: lists Linktree as an integration
  source: https://www.beehiiv.com/integrations
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
    mcp: &id013
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id014
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://www.beehiiv.com/integrations
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
    agent_readiness: 33.2
    band: strong
    in_catalog: true
    kin_score: 54.3
    mcp: &id015
      status: none
    slug: manychat
    status: profiled
    tags: &id016
    - Chat Marketing
    - Conversational Commerce
    - Marketing Automation
    - Messenger Marketing
    url: /providers/manychat/
  layer: domain
  name: ManyChat
  provider: manychat
  says: lists ManyChat as an integration
  source: https://www.beehiiv.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 12.6
    mcp: &id017
      status: none
    slug: memberful
    status: profiled
    tags: &id018
    - Creators
    - Membership
    - Payments
    - Subscription
    url: /providers/memberful/
  layer: domain
  name: Memberful
  provider: memberful
  says: lists Memberful as an integration
  source: https://www.beehiiv.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.4
    band: developing
    in_catalog: true
    kin_score: 48.2
    mcp: &id019
      status: none
    slug: memberpress
    status: profiled
    tags: &id020
    - Company
    - Membership
    - Subscription
    - WordPress
    url: /providers/memberpress/
  layer: domain
  name: MemberPress
  provider: memberpress
  says: lists MemberPress as an integration
  source: https://www.beehiiv.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 53.1
    mcp: &id021
      status: none
    slug: optinmonster
    status: profiled
    tags: &id022
    - Company
    - Conversion Optimization
    - Lead Generation
    - Marketing
    url: /providers/optinmonster/
  layer: domain
  name: OptinMonster
  provider: optinmonster
  says: lists OptinMonster as an integration
  source: https://www.beehiiv.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: thin
    in_catalog: true
    kin_score: 33.1
    mcp: &id023
      status: none
    slug: patreon
    status: profiled
    tags: &id024
    - Content
    - Creator Economy
    - Membership
    - Subscription
    url: /providers/patreon/
  layer: domain
  name: Patreon
  provider: patreon
  says: lists Patreon as an integration
  source: https://www.beehiiv.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 51.2
    band: exemplar
    in_catalog: true
    kin_score: 83.2
    mcp: &id025
      status: none
    slug: recurly
    status: profiled
    tags: &id026
    - Billing
    - Payments
    - Recurring Revenue
    - Subscription
    url: /providers/recurly/
  layer: domain
  name: Recurly
  provider: recurly
  says: lists Recurly as an integration
  source: https://www.beehiiv.com/integrations
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
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id027
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id028
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.beehiiv.com/integrations
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
    mcp: &id029
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id030
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.beehiiv.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id031
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id032
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.beehiiv.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-220.10
    key: AE-220.10
    name: Online Courses
    url: /capabilities/online-courses/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.2
    band: developing
    in_catalog: true
    kin_score: 47.2
    mcp: &id033
      status: none
    slug: thinkific
    status: profiled
    tags: &id034
    - Course Creation
    - E-Learning
    - LMS
    - Online Courses
    url: /providers/thinkific/
  layer: domain
  name: Thinkific
  provider: thinkific
  says: lists Thinkific as an integration
  source: https://www.beehiiv.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.6
    band: thin
    in_catalog: true
    kin_score: 36.0
    mcp: &id035
      source: https://www.typeform.com/developers/mcp
      status: verified
    slug: typeform
    status: profiled
    tags: &id036
    - Forms
    - Lead Capture
    - Software-as-a-Service
    - Surveys
    url: /providers/typeform/
  layer: domain
  name: Typeform
  provider: typeform
  says: lists Typeform as an integration
  source: https://www.beehiiv.com/integrations
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
    agent_readiness: 62.5
    band: strong
    in_catalog: true
    kin_score: 60.5
    mcp: &id037
      source: https://developers.webflow.com/mcp/reference/overview
      status: verified
    slug: webflow
    status: profiled
    tags: &id038
    - CMS
    - E-Commerce
    - No-Code
    - Web Development
    url: /providers/webflow/
  layer: domain
  name: Webflow
  provider: webflow
  says: lists Webflow as an integration
  source: https://www.beehiiv.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320.10
    key: sales-transaction-management
    name: Sales Transaction Management
    url: /capabilities/sales-transaction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 54.6
    mcp: &id039
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id040
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: domain
  name: WooCommerce
  provider: woocommerce
  says: lists WooCommerce as an integration
  source: https://www.beehiiv.com/integrations
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
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id041
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id042
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
  layer: domain
  name: WordPress
  provider: wordpress
  says: lists WordPress as an integration
  source: https://www.beehiiv.com/integrations
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
    mcp: &id043
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id044
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.beehiiv.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/email-marketing-newsletter/beehiiv/
providers:
- agent_band: agent-ready
  agent_readiness: 49.3
  band: exemplar
  in_catalog: true
  kin_score: 72.5
  mcp: *id001
  name: ClickFunnels
  slug: clickfunnels
  status: profiled
  tags: *id002
  url: /providers/clickfunnels/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id003
  name: Discord
  slug: discord
  status: profiled
  tags: *id004
  url: /providers/discord/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id005
  name: Facebook Lead Ads
  slug: facebook
  status: profiled
  tags: *id006
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 33.2
  band: emerging
  in_catalog: true
  kin_score: 24.4
  mcp: *id007
  name: Formstack
  slug: formstack
  status: profiled
  tags: *id008
  url: /providers/formstack/
- agent_band: agent-aware
  agent_readiness: 16.5
  band: emerging
  in_catalog: true
  kin_score: 22.8
  mcp: *id009
  name: Gumroad
  slug: gumroad
  status: profiled
  tags: *id010
  url: /providers/gumroad/
- agent_band: agent-ready
  agent_readiness: 43.8
  band: developing
  in_catalog: true
  kin_score: 54.1
  mcp: *id011
  name: Linktree
  slug: linktree
  status: profiled
  tags: *id012
  url: /providers/linktree/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id013
  name: Make
  slug: make
  status: profiled
  tags: *id014
  url: /providers/make/
- agent_band: agent-ready
  agent_readiness: 33.2
  band: strong
  in_catalog: true
  kin_score: 54.3
  mcp: *id015
  name: ManyChat
  slug: manychat
  status: profiled
  tags: *id016
  url: /providers/manychat/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 12.6
  mcp: *id017
  name: Memberful
  slug: memberful
  status: profiled
  tags: *id018
  url: /providers/memberful/
- agent_band: agent-ready
  agent_readiness: 37.4
  band: developing
  in_catalog: true
  kin_score: 48.2
  mcp: *id019
  name: MemberPress
  slug: memberpress
  status: profiled
  tags: *id020
  url: /providers/memberpress/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 53.1
  mcp: *id021
  name: OptinMonster
  slug: optinmonster
  status: profiled
  tags: *id022
  url: /providers/optinmonster/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: thin
  in_catalog: true
  kin_score: 33.1
  mcp: *id023
  name: Patreon
  slug: patreon
  status: profiled
  tags: *id024
  url: /providers/patreon/
- agent_band: agent-native
  agent_readiness: 51.2
  band: exemplar
  in_catalog: true
  kin_score: 83.2
  mcp: *id025
  name: Recurly
  slug: recurly
  status: profiled
  tags: *id026
  url: /providers/recurly/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id027
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id028
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id029
  name: Slack
  slug: slack
  status: profiled
  tags: *id030
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id031
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id032
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 52.2
  band: developing
  in_catalog: true
  kin_score: 47.2
  mcp: *id033
  name: Thinkific
  slug: thinkific
  status: profiled
  tags: *id034
  url: /providers/thinkific/
- agent_band: agent-ready
  agent_readiness: 42.6
  band: thin
  in_catalog: true
  kin_score: 36.0
  mcp: *id035
  name: Typeform
  slug: typeform
  status: profiled
  tags: *id036
  url: /providers/typeform/
- agent_band: agent-ready
  agent_readiness: 62.5
  band: strong
  in_catalog: true
  kin_score: 60.5
  mcp: *id037
  name: Webflow
  slug: webflow
  status: profiled
  tags: *id038
  url: /providers/webflow/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id039
  name: WooCommerce
  slug: woocommerce
  status: profiled
  tags: *id040
  url: /providers/woocommerce/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id041
  name: WordPress
  slug: wordpress
  status: profiled
  tags: *id042
  url: /providers/wordpress/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id043
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id044
  url: /providers/zapier/
siblings:
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
- name: Mautic
  rows: 25
  url: /applications/email-marketing-newsletter/mautic/
- name: Substack
  rows: 4
  url: /applications/email-marketing-newsletter/substack/
sitemap: true
title: 'beehiiv: Email Marketing & Newsletters reference app'
---
