---
app: Casdoor
app_slug: casdoor
app_url: https://github.com/casdoor/casdoor
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.30
  key: AE-160.30
  layer: domain
  name: Identity Verification
  providers:
  - Alibaba Cloud
  url: /capabilities/identity-verification/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - Alipay
  - Baidu
  - Bilibili
  - DingTalk
  - Douyin
  - Facebook
  - Gitee
  - GitHub
  - GitLab
  - Google sign-in
  - Kwai
  - Lark / Feishu
  - LinkedIn
  - QQ
  - Telegram
  - WeChat
  - WeCom
  - Weibo
  - X (Twitter)
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: domain
  name: Tenant Identity Federation
  providers:
  - Azure AD B2C
  - Okta
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - Google
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.30
  key: AE-150.20.30
  layer: common
  name: One-Time Passcodes
  providers:
  - Amazon SNS
  - Azure Communication Services
  - GCCPAY
  - Huawei Cloud SMS
  - Huyi
  - Infobip
  - Netgsm
  - Oson SMS
  - SmsBao
  - SUBMAIL
  - Tencent Cloud SMS
  - Twilio
  - UCloud USMS
  - VolcEngine SMS
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
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
  id: identity-access
  name: Identity, SSO & Access Management
  url: /applications/identity-access/
counts:
  declared: 14
  observed: 26
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/casdoor/casdoor/master/go.mod
- route: documentation
  url: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
- route: source code
  url: https://github.com/casdoor/casdoor/tree/master/idp
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-160.30
    key: AE-160.30
    name: Identity Verification
    url: /capabilities/identity-verification/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.5
    band: emerging
    in_catalog: true
    kin_score: 18.8
    mcp: &id001
      source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
      status: verified
    slug: alibaba
    status: profiled
    tags: &id002
    - Cloud
    - Cloud Computing
    - Commerce
    - E-Commerce
    url: /providers/alibaba/
  layer: domain
  name: Alibaba Cloud
  provider: alibaba
  says: ships the Alibaba Cloud SDK or integration code
  source: https://raw.githubusercontent.com/casdoor/casdoor/master/go.mod
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
    agent_readiness: 18.0
    band: emerging
    in_catalog: true
    kin_score: 25.6
    mcp: &id003
      source: https://github.com/alipay/global-alipayplus-mcp
      status: verified
    slug: ant-group
    status: profiled
    tags: &id004
    - Company
    - Fintech
    - Payments
    - Technology
    url: /providers/ant-group/
  layer: domain
  name: Alipay
  provider: ant-group
  says: ships the Alipay SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
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
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://raw.githubusercontent.com/casdoor/casdoor/master/go.mod
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
    agent_readiness: 33.5
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id009
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id010
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: domain
  name: Azure AD B2C
  provider: microsoft-entra
  says: ships the Azure AD B2C SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    agent_readiness: 6.0
    band: emerging
    in_catalog: true
    kin_score: 18.5
    mcp: &id013
      source: https://github.com/baidu-maps/mcp
      status: verified
    slug: baidu
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Company
    - Machine Learning
    - Technology
    url: /providers/baidu/
  layer: domain
  name: Baidu
  provider: baidu
  says: ships the Baidu SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    kin_score: 4.2
    mcp: &id015
      status: none
    slug: bilibili
    status: profiled
    tags: &id016
    - Company
    - Media Entertainment
    - Streaming
    - Video
    url: /providers/bilibili/
  layer: domain
  name: Bilibili
  provider: bilibili
  says: ships the Bilibili SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 6.1
    mcp: &id017
      source: https://github.com/open-dingtalk/dingtalk-mcp
      status: verified
    slug: dingtalk
    status: profiled
    tags: &id018
    - Collaboration
    - Communications
    - Company
    - Enterprise
    url: /providers/dingtalk/
  layer: domain
  name: DingTalk
  provider: dingtalk
  says: ships the DingTalk SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    kin_score: 4.2
    mcp: &id019
      source: https://registry.modelcontextprotocol.io/v0/servers?search=bytedance
      status: verified
    slug: bytedance
    status: profiled
    tags: &id020
    - Company
    - Consumer Internet
    - Social Media
    - Video
    url: /providers/bytedance/
  layer: domain
  name: Douyin
  provider: bytedance
  says: ships the Douyin SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    mcp: &id021
      status: none
    slug: facebook
    status: profiled
    tags: &id022
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    agent_readiness: 29.2
    band: thin
    in_catalog: true
    kin_score: 28.4
    mcp: &id025
      source: https://github.com/oschina/mcp-gitee
      status: verified
    slug: gitee
    status: profiled
    tags: &id026
    - Code Hosting
    - Git Hosting
    - Repositories
    - Version Control
    url: /providers/gitee/
  layer: domain
  name: Gitee
  provider: gitee
  says: ships the Gitee SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    mcp: &id027
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id028
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    agent_readiness: 55.6
    band: exemplar
    in_catalog: true
    kin_score: 79.6
    mcp: &id029
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id030
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.5
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id031
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id032
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: common
  name: Google
  provider: google
  says: ships the Google SDK or integration code
  source: https://raw.githubusercontent.com/casdoor/casdoor/master/go.mod
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
    mcp: &id033
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id034
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: domain
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    agent_readiness: 28.5
    band: thin
    in_catalog: true
    kin_score: 33.6
    mcp: &id041
      status: none
    slug: kuaishou
    status: profiled
    tags: &id042
    - Company
    - Consumer
    - Social
    - Video
    url: /providers/kuaishou/
  layer: domain
  name: Kwai
  provider: kuaishou
  says: ships the Kwai SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    mcp: &id043
      source: https://github.com/larksuite/lark-openapi-mcp
      status: verified
    slug: larksuite
    status: profiled
    tags: &id044
    - Global Collaboration
    - No-code Workflow
    - Productivity
    - Team Collaboration
    url: /providers/larksuite/
  layer: domain
  name: Lark / Feishu
  provider: larksuite
  says: ships the Lark / Feishu SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    mcp: &id045
      status: none
    slug: linkedin
    status: profiled
    tags: &id046
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: ships the LinkedIn SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    agent_readiness: 53.8
    band: exemplar
    in_catalog: true
    kin_score: 78.0
    mcp: &id049
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id050
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: domain
  name: Okta
  provider: okta
  says: ships the Okta SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    agent_readiness: 18.0
    band: minimal
    in_catalog: true
    kin_score: 7.4
    mcp: &id053
      status: unknown
    slug: tencent-qq
    status: profiled
    tags: &id054
    - Company
    url: /providers/tencent-qq/
  layer: domain
  name: QQ
  provider: tencent-qq
  says: ships the QQ SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    agent_readiness: 40.1
    band: exemplar
    in_catalog: true
    kin_score: 87.3
    mcp: &id055
      status: none
    slug: sendgrid
    status: profiled
    tags: &id056
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://raw.githubusercontent.com/casdoor/casdoor/master/go.mod
  tier: observed
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
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id059
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id060
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/casdoor/casdoor/master/go.mod
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
    agent_readiness: 25.4
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id063
      status: none
    slug: telegram
    status: profiled
    tags: &id064
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: domain
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    agent_readiness: 24.2
    band: developing
    in_catalog: true
    kin_score: 50.5
    mcp: &id073
      status: none
    slug: wechat
    status: profiled
    tags: &id074
    - Messaging
    - Mini Programs
    - Payments
    - Social
    url: /providers/wechat/
  layer: domain
  name: WeChat
  provider: wechat
  says: ships the WeChat SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    mcp: &id075
      status: unchecked
    slug: wecom
    status: queued for profiling
    tags: &id076 []
    url: null
  layer: domain
  name: WeCom
  provider: wecom
  says: ships the WeCom SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 6.2
    mcp: &id077
      status: none
    slug: weibo
    status: profiled
    tags: &id078
    - China
    - Company
    - Microblogging
    - Social Media
    url: /providers/weibo/
  layer: domain
  name: Weibo
  provider: weibo
  says: ships the Weibo SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    agent_readiness: 61.2
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id079
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id080
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X (Twitter)
  provider: x
  says: ships the X (Twitter) SDK or integration code
  source: https://github.com/casdoor/casdoor/tree/master/idp
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
    agent_readiness: 29.4
    band: strong
    in_catalog: true
    kin_score: 55.5
    mcp: &id007
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sns
    status: profiled
    tags: &id008
    - Amazon Web Services
    - Email
    - Messaging
    - Notification
    url: /providers/amazon-sns/
  layer: common
  name: Amazon SNS
  provider: amazon-sns
  says: lists Amazon SNS as an integration
  source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
  tier: declared
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
    agent_readiness: 43.4
    band: exemplar
    in_catalog: true
    kin_score: 71.2
    mcp: &id011
      status: none
    slug: microsoft-azure-communication-services
    status: profiled
    tags: &id012
    - CPaaS
    - Calling
    - Chat
    - Microsoft Azure
    url: /providers/microsoft-azure-communication-services/
  layer: common
  name: Azure Communication Services
  provider: microsoft-azure-communication-services
  says: lists Azure Communication Services as an integration
  source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
  tier: declared
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
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 4.5
    mcp: &id023
      status: unknown
    slug: gccpay
    status: profiled
    tags: &id024
    - Company
    - E-Commerce
    - Fintech
    - Payments
    url: /providers/gccpay/
  layer: common
  name: GCCPAY
  provider: gccpay
  says: lists GCCPAY as an integration
  source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
  tier: declared
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
    band: emerging
    in_catalog: true
    kin_score: 11.0
    mcp: &id035
      source: https://github.com/huaweicloud/huaweicloud-mcp
      status: verified
    slug: huaweicloud
    status: profiled
    tags: &id036
    - Cloud
    - Company
    - Infrastructure-as-a-Service
    - Platform-as-a-Service
    url: /providers/huaweicloud/
  layer: common
  name: Huawei Cloud SMS
  provider: huaweicloud
  says: lists Huawei Cloud SMS as an integration
  source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.30
    key: AE-150.20.30
    name: One-Time Passcodes
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id037
      status: unchecked
    slug: huyi
    status: queued for profiling
    tags: &id038 []
    url: null
  layer: common
  name: Huyi
  provider: huyi
  says: lists Huyi as an integration
  source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
  tier: declared
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
    agent_readiness: 61.3
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id039
      source: https://www.infobip.com/docs/mcp
      status: verified
    slug: infobip
    status: profiled
    tags: &id040
    - CPaaS
    - Croatia
    - Messaging
    - Telecommunications
    url: /providers/infobip/
  layer: common
  name: Infobip
  provider: infobip
  says: lists Infobip as an integration
  source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
  tier: declared
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
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 7.1
    mcp: &id047
      status: none
    slug: netgsm
    status: profiled
    tags: &id048
    - Internet
    - OTP
    - SMS
    - VoIP
    url: /providers/netgsm/
  layer: common
  name: Netgsm
  provider: netgsm
  says: lists Netgsm as an integration
  source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
  tier: declared
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
    kin_score: 7.0
    mcp: &id051
      status: unknown
    slug: osonsms
    status: profiled
    tags: &id052
    - Cloud
    - Company
    - Messaging
    - SMS
    url: /providers/osonsms/
  layer: common
  name: Oson SMS
  provider: osonsms
  says: lists Oson SMS as an integration
  source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
  tier: declared
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
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 4.6
    mcp: &id057
      status: unknown
    slug: smsbao
    status: profiled
    tags: &id058
    - China
    - Enterprise
    - Messaging
    - SMS
    url: /providers/smsbao/
  layer: common
  name: SmsBao
  provider: smsbao
  says: lists SmsBao as an integration
  source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
  tier: declared
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
    kin_score: 3.3
    mcp: &id061
      status: unknown
    slug: submail
    status: profiled
    tags: &id062
    - Company
    url: /providers/submail/
  layer: common
  name: SUBMAIL
  provider: submail
  says: lists SUBMAIL as an integration
  source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
  tier: declared
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
    agent_readiness: 12.9
    band: emerging
    in_catalog: true
    kin_score: 25.3
    mcp: &id065
      source: https://github.com/TencentCloud/cos-mcp
      status: verified
    slug: tencentcloud
    status: profiled
    tags: &id066
    - Artificial Intelligence
    - Cloud
    - Computing
    - Infrastructure
    url: /providers/tencentcloud/
  layer: common
  name: Tencent Cloud SMS
  provider: tencentcloud
  says: lists Tencent Cloud SMS as an integration
  source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
  tier: declared
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
    agent_readiness: 56.4
    band: exemplar
    in_catalog: true
    kin_score: 90.3
    mcp: &id067
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id068
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: lists Twilio as an integration
  source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
  tier: declared
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
    agent_readiness: 29.1
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id069
      source: https://github.com/ucloud/udb-mysql-mcp-server
      status: verified
    slug: ucloud
    status: profiled
    tags: &id070
    - Cloud Computing
    - Company
    - Enterprise
    - Infrastructure-as-a-Service
    url: /providers/ucloud/
  layer: common
  name: UCloud USMS
  provider: ucloud
  says: lists UCloud USMS as an integration
  source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.30
    key: AE-150.20.30
    name: One-Time Passcodes
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id071
      status: unchecked
    slug: volcengine
    status: queued for profiling
    tags: &id072 []
    url: null
  layer: common
  name: VolcEngine SMS
  provider: volcengine
  says: lists VolcEngine SMS as an integration
  source: https://raw.githubusercontent.com/casdoor/go-sms-sender/master/README.md
  tier: declared
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/identity-access/casdoor/
providers:
- agent_band: human-only
  agent_readiness: 3.5
  band: emerging
  in_catalog: true
  kin_score: 18.8
  mcp: *id001
  name: Alibaba Cloud
  slug: alibaba
  status: profiled
  tags: *id002
  url: /providers/alibaba/
- agent_band: agent-aware
  agent_readiness: 18.0
  band: emerging
  in_catalog: true
  kin_score: 25.6
  mcp: *id003
  name: Alipay
  slug: ant-group
  status: profiled
  tags: *id004
  url: /providers/ant-group/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id005
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id006
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 29.4
  band: strong
  in_catalog: true
  kin_score: 55.5
  mcp: *id007
  name: Amazon SNS
  slug: amazon-sns
  status: profiled
  tags: *id008
  url: /providers/amazon-sns/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id009
  name: Azure AD B2C
  slug: microsoft-entra
  status: profiled
  tags: *id010
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id011
  name: Azure Communication Services
  slug: microsoft-azure-communication-services
  status: profiled
  tags: *id012
  url: /providers/microsoft-azure-communication-services/
- agent_band: agent-aware
  agent_readiness: 6.0
  band: emerging
  in_catalog: true
  kin_score: 18.5
  mcp: *id013
  name: Baidu
  slug: baidu
  status: profiled
  tags: *id014
  url: /providers/baidu/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.2
  mcp: *id015
  name: Bilibili
  slug: bilibili
  status: profiled
  tags: *id016
  url: /providers/bilibili/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 6.1
  mcp: *id017
  name: DingTalk
  slug: dingtalk
  status: profiled
  tags: *id018
  url: /providers/dingtalk/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.2
  mcp: *id019
  name: Douyin
  slug: bytedance
  status: profiled
  tags: *id020
  url: /providers/bytedance/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id021
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id022
  url: /providers/facebook/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 4.5
  mcp: *id023
  name: GCCPAY
  slug: gccpay
  status: profiled
  tags: *id024
  url: /providers/gccpay/
- agent_band: agent-ready
  agent_readiness: 29.2
  band: thin
  in_catalog: true
  kin_score: 28.4
  mcp: *id025
  name: Gitee
  slug: gitee
  status: profiled
  tags: *id026
  url: /providers/gitee/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id027
  name: GitHub
  slug: github
  status: profiled
  tags: *id028
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 55.6
  band: exemplar
  in_catalog: true
  kin_score: 79.6
  mcp: *id029
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id030
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 48.5
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id031
  name: Google
  slug: google
  status: profiled
  tags: *id032
  url: /providers/google/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id033
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id034
  url: /providers/google-identity-platform/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id035
  name: Huawei Cloud SMS
  slug: huaweicloud
  status: profiled
  tags: *id036
  url: /providers/huaweicloud/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id037
  name: Huyi
  slug: huyi
  status: queued for profiling
  tags: *id038
  url: null
- agent_band: agent-ready
  agent_readiness: 61.3
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id039
  name: Infobip
  slug: infobip
  status: profiled
  tags: *id040
  url: /providers/infobip/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id041
  name: Kwai
  slug: kuaishou
  status: profiled
  tags: *id042
  url: /providers/kuaishou/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id043
  name: Lark / Feishu
  slug: larksuite
  status: profiled
  tags: *id044
  url: /providers/larksuite/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: exemplar
  in_catalog: true
  kin_score: 76.4
  mcp: *id045
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id046
  url: /providers/linkedin/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 7.1
  mcp: *id047
  name: Netgsm
  slug: netgsm
  status: profiled
  tags: *id048
  url: /providers/netgsm/
- agent_band: agent-ready
  agent_readiness: 53.8
  band: exemplar
  in_catalog: true
  kin_score: 78.0
  mcp: *id049
  name: Okta
  slug: okta
  status: profiled
  tags: *id050
  url: /providers/okta/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.0
  mcp: *id051
  name: Oson SMS
  slug: osonsms
  status: profiled
  tags: *id052
  url: /providers/osonsms/
- agent_band: agent-aware
  agent_readiness: 18.0
  band: minimal
  in_catalog: true
  kin_score: 7.4
  mcp: *id053
  name: QQ
  slug: tencent-qq
  status: profiled
  tags: *id054
  url: /providers/tencent-qq/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id055
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id056
  url: /providers/sendgrid/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 4.6
  mcp: *id057
  name: SmsBao
  slug: smsbao
  status: profiled
  tags: *id058
  url: /providers/smsbao/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id059
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id060
  url: /providers/stripe/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.3
  mcp: *id061
  name: SUBMAIL
  slug: submail
  status: profiled
  tags: *id062
  url: /providers/submail/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id063
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id064
  url: /providers/telegram/
- agent_band: agent-aware
  agent_readiness: 12.9
  band: emerging
  in_catalog: true
  kin_score: 25.3
  mcp: *id065
  name: Tencent Cloud SMS
  slug: tencentcloud
  status: profiled
  tags: *id066
  url: /providers/tencentcloud/
- agent_band: agent-native
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 90.3
  mcp: *id067
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id068
  url: /providers/twilio/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id069
  name: UCloud USMS
  slug: ucloud
  status: profiled
  tags: *id070
  url: /providers/ucloud/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id071
  name: VolcEngine SMS
  slug: volcengine
  status: queued for profiling
  tags: *id072
  url: null
- agent_band: agent-aware
  agent_readiness: 24.2
  band: developing
  in_catalog: true
  kin_score: 50.5
  mcp: *id073
  name: WeChat
  slug: wechat
  status: profiled
  tags: *id074
  url: /providers/wechat/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id075
  name: WeCom
  slug: wecom
  status: queued for profiling
  tags: *id076
  url: null
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 6.2
  mcp: *id077
  name: Weibo
  slug: weibo
  status: profiled
  tags: *id078
  url: /providers/weibo/
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id079
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id080
  url: /providers/x/
siblings:
- name: Authelia
  rows: 1
  url: /applications/identity-access/authelia/
- name: Authentik
  rows: 20
  url: /applications/identity-access/authentik/
- name: Keycloak
  rows: 12
  url: /applications/identity-access/keycloak/
- name: Logto
  rows: 39
  url: /applications/identity-access/logto/
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
title: 'Casdoor: Identity, SSO & Access Management reference app'
---
