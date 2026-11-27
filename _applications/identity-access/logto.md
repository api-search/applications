---
app: Logto
app_slug: logto
app_url: https://github.com/logto-io/logto
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - Alipay
  - DingTalk
  - Discord
  - Facebook
  - Feishu
  - GitHub
  - GitLab
  - Google sign-in
  - Hugging Face
  - Kakao
  - KOOK
  - LINE
  - LinkedIn
  - Login with Amazon
  - Naver
  - Patreon
  - QQ
  - Sign in with Apple
  - Slack
  - WeChat
  - WeCom
  - WhatsApp
  - X
  - Xiaomi
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: domain
  name: Tenant Identity Federation
  providers:
  - Microsoft Entra ID
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.30
  key: AE-150.20.30
  layer: common
  name: One-Time Passcodes
  providers:
  - Alibaba Cloud SMS
  - GatewayAPI
  - SMS Aero
  - SmsBao
  - Tencent Cloud SMS
  - Twilio
  - Vonage
  - Yunpian
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Alibaba Cloud DirectMail
  - Amazon SES
  - Mailgun
  - Postmark
  - SendGrid
  - SMTP2GO
  url: /capabilities/email/
  via_parent: Email
category:
  id: identity-access
  name: Identity, SSO & Access Management
  url: /applications/identity-access/
counts:
  declared: 0
  observed: 39
credits: []
evidence:
- route: source code
  url: https://github.com/logto-io/logto/tree/master/packages/connectors
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts: &id001
    agent_band: human-only
    agent_readiness: 3.4
    band: emerging
    in_catalog: true
    kin_score: 17.9
    mcp: &id002
      source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
      status: verified
    slug: alibaba
    status: profiled
    tags: &id003
    - Cloud
    - Cloud Computing
    - Commerce
    - E-Commerce
    url: /providers/alibaba/
  layer: common
  name: Alibaba Cloud DirectMail
  provider: alibaba
  says: ships the Alibaba Cloud DirectMail SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.30
    key: AE-150.20.30
    name: One-Time Passcodes
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts: *id001
  layer: common
  name: Alibaba Cloud SMS
  provider: alibaba
  says: ships the Alibaba Cloud SMS SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_readiness: 17.6
    band: emerging
    in_catalog: true
    kin_score: 24.8
    mcp: &id004
      source: https://github.com/alipay/global-alipayplus-mcp
      status: verified
    slug: ant-group
    status: profiled
    tags: &id005
    - Company
    - Fintech
    - Payments
    - Technology
    url: /providers/ant-group/
  layer: domain
  name: Alipay
  provider: ant-group
  says: ships the Alipay SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
  tier: observed
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
    agent_readiness: 38.0
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id006
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id007
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
  layer: common
  name: Amazon SES
  provider: amazon-ses
  says: ships the Amazon SES SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.1
    mcp: &id008
      source: https://github.com/open-dingtalk/dingtalk-mcp
      status: verified
    slug: dingtalk
    status: profiled
    tags: &id009
    - Collaboration
    - Communications
    - Company
    - Enterprise
    url: /providers/dingtalk/
  layer: domain
  name: DingTalk
  provider: dingtalk
  says: ships the DingTalk SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id010
      status: none
    slug: discord
    status: profiled
    tags: &id011
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: domain
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id012
      status: none
    slug: facebook
    status: profiled
    tags: &id013
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.5
    mcp: &id014
      source: https://github.com/larksuite/lark-openapi-mcp
      status: verified
    slug: larksuite
    status: profiled
    tags: &id015
    - Global Collaboration
    - No-code Workflow
    - Productivity
    - Team Collaboration
    url: /providers/larksuite/
  layer: domain
  name: Feishu
  provider: larksuite
  says: ships the Feishu SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.30
    key: AE-150.20.30
    name: One-Time Passcodes
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.5
    band: thin
    in_catalog: true
    kin_score: 31.8
    mcp: &id016
      status: unknown
    slug: gatewayapi
    status: profiled
    tags: &id017
    - Communications
    - Company
    - Messaging
    - SMS
    url: /providers/gatewayapi/
  layer: common
  name: GatewayAPI
  provider: gatewayapi
  says: ships the GatewayAPI SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id018
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id019
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id020
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id021
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id022
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id023
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: domain
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_readiness: 36.9
    band: exemplar
    in_catalog: true
    kin_score: 69.1
    mcp: &id024
      source: https://github.com/huggingface/hf-mcp-server
      status: verified
    slug: hugging-face
    status: profiled
    tags: &id025
    - Computer Vision
    - Embeddings
    - Image Generation
    - LLM
    url: /providers/hugging-face/
  layer: domain
  name: Hugging Face
  provider: hugging-face
  says: ships the Hugging Face SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 26.2
    mcp: &id026
      status: none
    slug: kakao
    status: profiled
    tags: &id027
    - Maps
    - Messaging
    - Navigation
    - Payments
    url: /providers/kakao/
  layer: domain
  name: Kakao
  provider: kakao
  says: ships the Kakao SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_readiness: 22.8
    band: thin
    in_catalog: true
    kin_score: 33.7
    mcp: &id028
      status: none
    slug: kook
    status: profiled
    tags: &id029
    - Community
    - Company
    - Gaming
    - Voice Communication
    url: /providers/kook/
  layer: domain
  name: KOOK
  provider: kook
  says: ships the KOOK SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_band: agent-native
    agent_readiness: 47.0
    band: exemplar
    in_catalog: true
    kin_score: 71.3
    mcp: &id030
      source: https://github.com/line/line-bot-mcp-server
      status: verified
    slug: line
    status: profiled
    tags: &id031
    - Chatbots
    - Messaging
    - Mini Apps
    - Social Login
    url: /providers/line/
  layer: domain
  name: LINE
  provider: line
  says: ships the LINE SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_readiness: 46.5
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id032
      status: none
    slug: linkedin
    status: profiled
    tags: &id033
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: ships the LinkedIn SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_band: agent-native
    agent_readiness: 53.6
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id034
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id035
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: domain
  name: Login with Amazon
  provider: amazon
  says: ships the Login with Amazon SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id036
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id037
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: common
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id038
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id039
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: domain
  name: Microsoft Entra ID
  provider: microsoft-entra
  says: ships the Microsoft Entra ID SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 10.6
    mcp: &id040
      status: none
    slug: naver
    status: profiled
    tags: &id041
    - Cloud Platform
    - Maps
    - Search
    - Translation
    url: /providers/naver/
  layer: domain
  name: Naver
  provider: naver
  says: ships the Naver SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_readiness: 26.4
    band: thin
    in_catalog: true
    kin_score: 33.1
    mcp: &id042
      status: none
    slug: patreon
    status: profiled
    tags: &id043
    - Content
    - Creator Economy
    - Membership
    - Subscription
    url: /providers/patreon/
  layer: domain
  name: Patreon
  provider: patreon
  says: ships the Patreon SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
  tier: observed
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
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id044
      source: https://github.com/ActiveCampaign/postmark-mcp
      status: verified
    slug: postmark
    status: profiled
    tags: &id045
    - Deliverability
    - Email
    - Messaging
    - Transactional Email
    url: /providers/postmark/
  layer: common
  name: Postmark
  provider: postmark
  says: ships the Postmark SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_readiness: 14.8
    band: minimal
    in_catalog: true
    kin_score: 8.6
    mcp: &id046
      status: unknown
    slug: tencent-qq
    status: profiled
    tags: &id047
    - Company
    url: /providers/tencent-qq/
  layer: domain
  name: QQ
  provider: tencent-qq
  says: ships the QQ SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
  tier: observed
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
    agent_readiness: 40.7
    band: exemplar
    in_catalog: true
    kin_score: 84.0
    mcp: &id048
      status: none
    slug: sendgrid
    status: profiled
    tags: &id049
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id050
      status: none
    slug: apple
    status: profiled
    tags: &id051
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Sign in with Apple
  provider: apple
  says: ships the Sign in with Apple SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id052
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id053
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.30
    key: AE-150.20.30
    name: One-Time Passcodes
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.7
    mcp: &id054
      status: unknown
    slug: smsaero
    status: profiled
    tags: &id055
    - Bulk
    - Company
    - Messaging
    - SMS
    url: /providers/smsaero/
  layer: common
  name: SMS Aero
  provider: smsaero
  says: ships the SMS Aero SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.30
    key: AE-150.20.30
    name: One-Time Passcodes
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.9
    mcp: &id056
      status: unknown
    slug: smsbao
    status: profiled
    tags: &id057
    - China
    - Enterprise
    - Messaging
    - SMS
    url: /providers/smsbao/
  layer: common
  name: SmsBao
  provider: smsbao
  says: ships the SmsBao SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
  tier: observed
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
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 71.1
    mcp: &id058
      status: none
    slug: smtp2go
    status: profiled
    tags: &id059
    - Email
    - Email Delivery
    - SMTP
    - Transactional Email
    url: /providers/smtp2go/
  layer: common
  name: SMTP2GO
  provider: smtp2go
  says: ships the SMTP2GO SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.30
    key: AE-150.20.30
    name: One-Time Passcodes
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id060
      source: https://github.com/TencentCloud/cos-mcp
      status: verified
    slug: tencentcloud
    status: profiled
    tags: &id061
    - Artificial Intelligence
    - Cloud
    - Computing
    - Infrastructure
    url: /providers/tencentcloud/
  layer: common
  name: Tencent Cloud SMS
  provider: tencentcloud
  says: ships the Tencent Cloud SMS SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.30
    key: AE-150.20.30
    name: One-Time Passcodes
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id062
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id063
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.30
    key: AE-150.20.30
    name: One-Time Passcodes
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.0
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id064
      source: https://github.com/Vonage/vonage-mcp-server-documentation
      status: verified
    slug: vonage
    status: profiled
    tags: &id065
    - Communications
    - Messaging
    - Telecommunications
    - Video Conferencing
    url: /providers/vonage/
  layer: common
  name: Vonage
  provider: vonage
  says: ships the Vonage SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_readiness: 23.6
    band: developing
    in_catalog: true
    kin_score: 45.1
    mcp: &id066
      status: none
    slug: wechat
    status: profiled
    tags: &id067
    - Messaging
    - Mini Programs
    - Payments
    - Social
    url: /providers/wechat/
  layer: domain
  name: WeChat
  provider: wechat
  says: ships the WeChat SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id068
      status: unchecked
    slug: wecom
    status: queued for profiling
    tags: &id069 []
    url: null
  layer: domain
  name: WeCom
  provider: wecom
  says: ships the WeCom SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 72.3
    mcp: &id070
      status: none
    slug: whatsapp
    status: profiled
    tags: &id071
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: domain
  name: WhatsApp
  provider: whatsapp
  says: ships the WhatsApp SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_band: agent-native
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id072
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id073
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X
  provider: x
  says: ships the X SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
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
    agent_readiness: 24.9
    band: thin
    in_catalog: true
    kin_score: 35.6
    mcp: &id074
      status: none
    slug: xiaomi
    status: profiled
    tags: &id075
    - Consumer Electronics
    - IoT
    - Mobile
    - Smart Home
    url: /providers/xiaomi/
  layer: domain
  name: Xiaomi
  provider: xiaomi
  says: ships the Xiaomi SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.30
    key: AE-150.20.30
    name: One-Time Passcodes
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.5
    mcp: &id076
      status: none
    slug: yunpian
    status: profiled
    tags: &id077
    - API Platform
    - Cloud Communications
    - Company
    - SMS
    url: /providers/yunpian/
  layer: common
  name: Yunpian
  provider: yunpian
  says: ships the Yunpian SDK or integration code
  source: https://github.com/logto-io/logto/tree/master/packages/connectors
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/identity-access/logto/
providers:
- agent_band: human-only
  agent_readiness: 3.4
  band: emerging
  in_catalog: true
  kin_score: 17.9
  mcp: *id002
  name: Alibaba Cloud DirectMail
  slug: alibaba
  status: profiled
  tags: *id003
  url: /providers/alibaba/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: emerging
  in_catalog: true
  kin_score: 24.8
  mcp: *id004
  name: Alipay
  slug: ant-group
  status: profiled
  tags: *id005
  url: /providers/ant-group/
- agent_band: agent-ready
  agent_readiness: 38.0
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id006
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id007
  url: /providers/amazon-ses/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.1
  mcp: *id008
  name: DingTalk
  slug: dingtalk
  status: profiled
  tags: *id009
  url: /providers/dingtalk/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id010
  name: Discord
  slug: discord
  status: profiled
  tags: *id011
  url: /providers/discord/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id012
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id013
  url: /providers/facebook/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id014
  name: Feishu
  slug: larksuite
  status: profiled
  tags: *id015
  url: /providers/larksuite/
- agent_band: agent-aware
  agent_readiness: 17.5
  band: thin
  in_catalog: true
  kin_score: 31.8
  mcp: *id016
  name: GatewayAPI
  slug: gatewayapi
  status: profiled
  tags: *id017
  url: /providers/gatewayapi/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id018
  name: GitHub
  slug: github
  status: profiled
  tags: *id019
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id020
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id021
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id022
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id023
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 36.9
  band: exemplar
  in_catalog: true
  kin_score: 69.1
  mcp: *id024
  name: Hugging Face
  slug: hugging-face
  status: profiled
  tags: *id025
  url: /providers/hugging-face/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 26.2
  mcp: *id026
  name: Kakao
  slug: kakao
  status: profiled
  tags: *id027
  url: /providers/kakao/
- agent_band: agent-aware
  agent_readiness: 22.8
  band: thin
  in_catalog: true
  kin_score: 33.7
  mcp: *id028
  name: KOOK
  slug: kook
  status: profiled
  tags: *id029
  url: /providers/kook/
- agent_band: agent-native
  agent_readiness: 47.0
  band: exemplar
  in_catalog: true
  kin_score: 71.3
  mcp: *id030
  name: LINE
  slug: line
  status: profiled
  tags: *id031
  url: /providers/line/
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id032
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id033
  url: /providers/linkedin/
- agent_band: agent-native
  agent_readiness: 53.6
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id034
  name: Login with Amazon
  slug: amazon
  status: profiled
  tags: *id035
  url: /providers/amazon/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id036
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id037
  url: /providers/mailgun/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id038
  name: Microsoft Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id039
  url: /providers/microsoft-entra/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 10.6
  mcp: *id040
  name: Naver
  slug: naver
  status: profiled
  tags: *id041
  url: /providers/naver/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: thin
  in_catalog: true
  kin_score: 33.1
  mcp: *id042
  name: Patreon
  slug: patreon
  status: profiled
  tags: *id043
  url: /providers/patreon/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id044
  name: Postmark
  slug: postmark
  status: profiled
  tags: *id045
  url: /providers/postmark/
- agent_band: agent-aware
  agent_readiness: 14.8
  band: minimal
  in_catalog: true
  kin_score: 8.6
  mcp: *id046
  name: QQ
  slug: tencent-qq
  status: profiled
  tags: *id047
  url: /providers/tencent-qq/
- agent_band: agent-ready
  agent_readiness: 40.7
  band: exemplar
  in_catalog: true
  kin_score: 84.0
  mcp: *id048
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id049
  url: /providers/sendgrid/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id050
  name: Sign in with Apple
  slug: apple
  status: profiled
  tags: *id051
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id052
  name: Slack
  slug: slack
  status: profiled
  tags: *id053
  url: /providers/slack/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.7
  mcp: *id054
  name: SMS Aero
  slug: smsaero
  status: profiled
  tags: *id055
  url: /providers/smsaero/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.9
  mcp: *id056
  name: SmsBao
  slug: smsbao
  status: profiled
  tags: *id057
  url: /providers/smsbao/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 71.1
  mcp: *id058
  name: SMTP2GO
  slug: smtp2go
  status: profiled
  tags: *id059
  url: /providers/smtp2go/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id060
  name: Tencent Cloud SMS
  slug: tencentcloud
  status: profiled
  tags: *id061
  url: /providers/tencentcloud/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id062
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id063
  url: /providers/twilio/
- agent_band: agent-ready
  agent_readiness: 40.0
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id064
  name: Vonage
  slug: vonage
  status: profiled
  tags: *id065
  url: /providers/vonage/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: developing
  in_catalog: true
  kin_score: 45.1
  mcp: *id066
  name: WeChat
  slug: wechat
  status: profiled
  tags: *id067
  url: /providers/wechat/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id068
  name: WeCom
  slug: wecom
  status: queued for profiling
  tags: *id069
  url: null
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id070
  name: WhatsApp
  slug: whatsapp
  status: profiled
  tags: *id071
  url: /providers/whatsapp/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id072
  name: X
  slug: x
  status: profiled
  tags: *id073
  url: /providers/x/
- agent_band: agent-aware
  agent_readiness: 24.9
  band: thin
  in_catalog: true
  kin_score: 35.6
  mcp: *id074
  name: Xiaomi
  slug: xiaomi
  status: profiled
  tags: *id075
  url: /providers/xiaomi/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.5
  mcp: *id076
  name: Yunpian
  slug: yunpian
  status: profiled
  tags: *id077
  url: /providers/yunpian/
siblings:
- name: Authelia
  rows: 1
  url: /applications/identity-access/authelia/
- name: Authentik
  rows: 20
  url: /applications/identity-access/authentik/
- name: Casdoor
  rows: 40
  url: /applications/identity-access/casdoor/
- name: Keycloak
  rows: 12
  url: /applications/identity-access/keycloak/
- name: Okta Verify
  rows: 3
  url: /applications/identity-access/okta-verify/
- name: Ory Kratos
  rows: 22
  url: /applications/identity-access/ory-kratos/
- name: Zitadel
  rows: 8
  url: /applications/identity-access/zitadel/
sitemap: true
title: 'Logto: Identity, SSO & Access Management reference app'
---
