---
access: understanding
agent_layer:
- app: Formbricks
  finding: ships an MCP server (@modelcontextprotocol/server, mcp-handler, @posthog/mcp in apps/web)
  source: https://raw.githubusercontent.com/formbricks/formbricks/main/apps/web/package.json
  tier: observed
- app: SurveyMonkey
  finding: lists a SurveyMonkey MCP Server in its app directory
  source: https://www.surveymonkey.com/apps/
  tier: declared
- app: Jotform
  finding: lists Claude and ChatGPT connectors as integrations
  source: https://www.jotform.com/integrations/
  tier: declared
- app: Typebot
  finding: LLM bring-your-own blocks (OpenAI, Anthropic, Mistral, Groq, OpenRouter, Dify, ...)
  source: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
  tier: observed
apps:
- anchor: formbricks
  counts:
    declared: 0
    observed: 16
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/formbricks/formbricks/main/apps/web/package.json
  - route: source code
    url: https://github.com/formbricks/formbricks/tree/main/apps/web/modules/integrations
  - route: source code
    url: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: airtable
    provider: airtable
    says: ships the airtable SDK or integration code
    source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: common
    name: authzed
    provider: authzed
    says: ships the authzed SDK or integration code
    source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: cloudflare-turnstile
    provider: cloudflare-turnstile
    says: ships the cloudflare-turnstile SDK or integration code
    source: https://raw.githubusercontent.com/formbricks/formbricks/main/apps/web/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: cube
    provider: cube
    says: ships the cube SDK or integration code
    source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: github
    provider: github
    says: ships the github SDK or integration code
    source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: google-recaptcha
    provider: google-recaptcha
    says: ships the google-recaptcha SDK or integration code
    source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: google-sheets
    provider: google-sheets
    says: ships the google-sheets SDK or integration code
    source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: common
    name: lingo-dev
    provider: lingo-dev
    says: ships the lingo-dev SDK or integration code
    source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Entra ID (Azure AD)
    provider: microsoft-entra
    says: ships the Microsoft Entra ID (Azure AD) SDK or integration code
    source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    credit: null
    layer: domain
    name: notion
    provider: notion
    says: ships the notion SDK or integration code
    source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: posthog
    provider: posthog
    says: ships the posthog SDK or integration code
    source: https://raw.githubusercontent.com/formbricks/formbricks/main/apps/web/package.json
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
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://raw.githubusercontent.com/formbricks/formbricks/main/apps/web/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: slack
    provider: slack
    says: ships the slack SDK or integration code
    source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: stripe
    provider: stripe
    says: ships the stripe SDK or integration code
    source: https://raw.githubusercontent.com/formbricks/formbricks/main/apps/web/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: domain
    name: unsplash
    provider: unsplash
    says: ships the unsplash SDK or integration code
    source: https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
    tier: observed
  kind: open-source-saas
  name: Formbricks
  page: /applications/forms-surveys/formbricks/
  slug: formbricks
  url: https://github.com/formbricks/formbricks
- anchor: limesurvey
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/LimeSurvey/LimeSurvey/master/composer.json
  - route: source code
    url: https://github.com/LimeSurvey/LimeSurvey/tree/master/application/core/plugins
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Gmail SMTP (OAuth)
    provider: google-gmail
    says: ships the Gmail SMTP (OAuth) SDK or integration code
    source: https://github.com/LimeSurvey/LimeSurvey/tree/master/application/core/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: common
    name: google-translate
    provider: google-translate
    says: ships the google-translate SDK or integration code
    source: https://raw.githubusercontent.com/LimeSurvey/LimeSurvey/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Microsoft 365 / Exchange Online SMTP
    provider: microsoft-exchange
    says: ships the Microsoft 365 / Exchange Online SMTP SDK or integration code
    source: https://github.com/LimeSurvey/LimeSurvey/tree/master/application/core/plugins
    tier: observed
  kind: self-hosted
  name: LimeSurvey
  page: /applications/forms-surveys/limesurvey/
  slug: limesurvey
  url: https://github.com/LimeSurvey/LimeSurvey
- anchor: heyform
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/heyform/heyform/main/packages/server/package.json
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: akismet
    provider: akismet
    says: ships the akismet SDK or integration code
    source: https://raw.githubusercontent.com/heyform/heyform/main/packages/server/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: amazon-s3
    provider: amazon-s3
    says: ships the amazon-s3 SDK or integration code
    source: https://raw.githubusercontent.com/heyform/heyform/main/packages/server/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: GeeTest
    provider: geetest
    says: ships the GeeTest SDK or integration code
    source: https://raw.githubusercontent.com/heyform/heyform/main/packages/server/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://raw.githubusercontent.com/heyform/heyform/main/packages/server/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: openai
    provider: openai
    says: ships the openai SDK or integration code
    source: https://raw.githubusercontent.com/heyform/heyform/main/packages/server/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: stripe
    provider: stripe
    says: ships the stripe SDK or integration code
    source: https://raw.githubusercontent.com/heyform/heyform/main/packages/server/package.json
    tier: observed
  kind: open-source-saas
  name: HeyForm
  page: /applications/forms-surveys/heyform/
  slug: heyform
  url: https://github.com/heyform/heyform
- anchor: typebot
  counts:
    declared: 0
    observed: 23
  evidence:
  - route: source code
    url: https://github.com/baptisteArno/typebot.io/tree/main/packages/blocks/integrations/src
  - route: source code
    url: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: anthropic
    provider: anthropic
    says: ships the anthropic SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    credit: null
    layer: domain
    name: cal-com
    provider: cal-com
    says: ships the cal-com SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: chatwoot
    provider: chatwoot
    says: ships the chatwoot SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/blocks/integrations/src
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: deepseek
    provider: deepseek
    says: ships the deepseek SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.20.20
      key: AE-100.20.20
      name: Multi-Agent Orchestration
      url: /capabilities/agent-to-agent-interoperability/
      via_parent: Agent-to-Agent Interoperability
    credit: null
    layer: agent
    name: dify
    provider: dify
    says: ships the dify SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: common
    name: elevenlabs
    provider: elevenlabs
    says: ships the elevenlabs SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Facebook pixel
    provider: facebook
    says: ships the Facebook pixel SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/blocks/integrations/src
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Gmail SMTP (OAuth)
    provider: google-gmail
    says: ships the Gmail SMTP (OAuth) SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: google-analytics
    provider: google-analytics
    says: ships the google-analytics SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/blocks/integrations/src
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: google-sheets
    provider: google-sheets
    says: ships the google-sheets SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/blocks/integrations/src
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: groq
    provider: groq
    says: ships the groq SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: make
    provider: make
    says: ships the make SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/blocks/integrations/src
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: mistral
    provider: mistral
    says: ships the mistral SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: nocodb
    provider: nocodb
    says: ships the nocodb SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: openai
    provider: openai
    says: ships the openai SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: openrouter
    provider: openrouter
    says: ships the openrouter SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: pabbly
    provider: pabbly
    says: ships the pabbly SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/blocks/integrations/src
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: perplexity
    provider: perplexity
    says: ships the perplexity SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: posthog
    provider: posthog
    says: ships the posthog SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: segment
    provider: segment
    says: ships the segment SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: together-ai
    provider: together-ai
    says: ships the together-ai SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: zapier
    provider: zapier
    says: ships the zapier SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/blocks/integrations/src
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: zendesk
    provider: zendesk
    says: ships the zendesk SDK or integration code
    source: https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
    tier: observed
  kind: open-source-saas
  name: Typebot
  page: /applications/forms-surveys/typebot/
  slug: typebot
  url: https://github.com/baptisteArno/typebot.io
- anchor: typeform
  counts:
    declared: 18
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.typeform.com/connect/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: activecampaign
    provider: activecampaign
    says: lists activecampaign as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    credit: null
    layer: domain
    name: calendly
    provider: calendly
    says: lists calendly as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Facebook pixel
    provider: facebook
    says: lists Facebook pixel as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: google-analytics
    provider: google-analytics
    says: lists google-analytics as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: domain
    name: google-forms
    provider: google-forms
    says: lists google-forms as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: null
    layer: domain
    name: google-tag-manager
    provider: google-tag-manager
    says: lists google-tag-manager as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: hubspot
    provider: hubspot
    says: lists hubspot as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: intercom
    provider: intercom
    says: lists intercom as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: keap
    provider: keap
    says: lists keap as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: klaviyo
    provider: klaviyo
    says: lists klaviyo as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: mailchimp
    provider: mailchimp
    says: lists mailchimp as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: microsoft-excel
    provider: microsoft-excel
    says: lists microsoft-excel as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: microsoft-teams
    provider: microsoft-teams
    says: lists microsoft-teams as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: monday.com
    provider: monday-com
    says: lists monday.com as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    credit: null
    layer: domain
    name: notion
    provider: notion
    says: lists notion as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: pipedrive
    provider: pipedrive
    says: lists pipedrive as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: salesforce
    provider: salesforce
    says: lists salesforce as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: slack
    provider: slack
    says: lists slack as an integration
    source: https://www.typeform.com/connect/
    tier: declared
  kind: commercial
  name: Typeform
  page: /applications/forms-surveys/typeform/
  slug: typeform
  url: https://www.typeform.com/
- anchor: surveymonkey
  counts:
    declared: 3
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
  - route: integrations page
    url: https://www.surveymonkey.com/apps/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google CrashLytics
    provider: firebase
    says: ships the Google CrashLytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Mixpanel
    provider: mixpanel
    says: ships the Mixpanel SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Salesforce Audience Studio (Krux)
    provider: salesforce
    says: ships the Salesforce Audience Studio (Krux) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Salesforce Marketing Cloud
    provider: salesforce-marketing-cloud
    says: ships the Salesforce Marketing Cloud SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Power BI
    provider: power-bi
    says: lists Microsoft Power BI as an integration
    source: https://www.surveymonkey.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: salesforce
    provider: salesforce
    says: lists salesforce as an integration
    source: https://www.surveymonkey.com/apps/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: tableau
    provider: tableau
    says: lists tableau as an integration
    source: https://www.surveymonkey.com/apps/
    tier: declared
  kind: commercial
  name: SurveyMonkey
  page: /applications/forms-surveys/surveymonkey/
  slug: surveymonkey
  url: https://www.surveymonkey.com/
- anchor: jotform
  counts:
    declared: 32
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.jotform.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: activecampaign
    provider: activecampaign
    says: lists activecampaign as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: airtable
    provider: airtable
    says: lists airtable as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: anthropic
    provider: anthropic
    says: lists anthropic as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: asana
    provider: asana
    says: lists asana as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Authorize.Net
    provider: authorizenet
    says: lists Authorize.Net as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: box
    provider: box
    says: lists box as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: domain
    name: canva
    provider: canva
    says: lists canva as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: constant-contact
    provider: constant-contact
    says: lists constant-contact as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: dropbox
    provider: dropbox
    says: lists dropbox as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: google-calendar
    provider: google-calendar
    says: lists google-calendar as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: google-drive
    provider: google-drive
    says: lists google-drive as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: google-sheets
    provider: google-sheets
    says: lists google-sheets as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: hubspot
    provider: hubspot
    says: lists hubspot as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: keap
    provider: keap
    says: lists keap as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: mailchimp
    provider: mailchimp
    says: lists mailchimp as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: microsoft-excel
    provider: microsoft-excel
    says: lists microsoft-excel as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: microsoft-onedrive
    provider: microsoft-onedrive
    says: lists microsoft-onedrive as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: microsoft-teams
    provider: microsoft-teams
    says: lists microsoft-teams as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: monday.com
    provider: monday-com
    says: lists monday.com as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: openai
    provider: openai
    says: lists openai as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: paypal
    provider: paypal
    says: lists paypal as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: pipedrive
    provider: pipedrive
    says: lists pipedrive as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: salesforce
    provider: salesforce
    says: lists salesforce as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: slack
    provider: slack
    says: lists slack as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: square
    provider: square
    says: lists square as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: stripe
    provider: stripe
    says: lists stripe as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: trello
    provider: trello
    says: lists trello as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: whatsapp
    provider: whatsapp
    says: lists whatsapp as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: worldpay
    provider: worldpay
    says: lists worldpay as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: domain
    name: zapier
    provider: zapier
    says: lists zapier as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: zoho-crm
    provider: zoho-crm
    says: lists zoho-crm as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: zoom
    provider: zoom
    says: lists zoom as an integration
    source: https://www.jotform.com/integrations/
    tier: declared
  kind: commercial
  name: Jotform
  page: /applications/forms-surveys/jotform/
  slug: jotform
  url: https://www.jotform.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: forms-surveys
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Productivity
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Productivity
  store: google-play
  url: https://play.google.com/store/apps/category/PRODUCTIVITY
- category: Polls and Events
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#polls-and-events
- category: Marketing
  store: hubspot-marketplace
  url: https://ecosystem.hubspot.com/marketplace/apps
- category: Surveys & Feedback
  store: atlassian-marketplace
  url: https://marketplace.atlassian.com/
- category: Forms & Surveys
  store: zapier
  url: https://zapier.com/apps
name: Forms & Surveys
needs:
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: reference apps integrate stripe here
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: reference apps integrate posthog here
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: reference apps integrate Sentry here
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: reference apps integrate google-recaptcha here
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: reference apps integrate github here
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: reference apps integrate Microsoft Entra ID (Azure AD) here
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: nearest
  layer: common
  why: reference apps integrate authzed here
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: domain
  why: reference apps integrate cube here
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: reference apps integrate notion here
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: reference apps integrate google-sheets here
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: domain
  why: reference apps integrate slack here
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: exact
  layer: domain
  why: reference apps integrate unsplash here
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: common
  why: reference apps integrate lingo-dev here
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: reference apps integrate Gmail SMTP (OAuth) here
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: reference apps integrate amazon-s3 here
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: common
  why: reference apps integrate openai here
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  fit: exact
  layer: domain
  why: reference apps integrate cal-com here
- capability:
    attribution: API Evangelist extension
    id: AE-100.20.20
    key: AE-100.20.20
    name: Multi-Agent Orchestration
    url: /capabilities/agent-to-agent-interoperability/
    via_parent: Agent-to-Agent Interoperability
  fit: exact
  layer: agent
  why: reference apps integrate dify here
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.20
    key: AE-110.30.20
    name: Text-to-Speech
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  fit: exact
  layer: common
  why: reference apps integrate elevenlabs here
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: common
  why: reference apps integrate openrouter here
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: domain
  why: reference apps integrate zendesk here
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: domain
  why: reference apps integrate make here
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: reference apps integrate Facebook pixel here
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: reference apps integrate hubspot here
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: domain
  why: reference apps integrate monday.com here
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: domain
  why: reference apps integrate google-tag-manager here
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  fit: exact
  layer: domain
  why: reference apps integrate google-forms here
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: reference apps integrate google-calendar here
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  fit: exact
  layer: domain
  why: reference apps integrate canva here
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: reference apps integrate dropbox here
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: domain
  why: reference apps integrate whatsapp here
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: domain
  why: reference apps integrate zoom here
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: attribution and deep-link SDKs seen in the Android builds
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: common
  why: audience data SDK seen in an Android build
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Jotform
      - SurveyMonkey
      - Typeform
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp: &id003
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: salesforce
      slug: salesforce
      sources:
      - https://www.jotform.com/integrations/
      - https://www.surveymonkey.com/apps/
      - https://www.typeform.com/connect/
      status: profiled
      tags: &id004
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Jotform
      - Typeform
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: hubspot
      slug: hubspot
      sources:
      - https://www.jotform.com/integrations/
      - https://www.typeform.com/connect/
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 44.5
      apps:
      - Jotform
      - Typeform
      band: strong
      in_catalog: true
      kin_score: 65.0
      mcp:
        status: none
      name: keap
      slug: keap
      sources:
      - https://www.jotform.com/integrations/
      - https://www.typeform.com/connect/
      status: profiled
      tags:
      - CRM
      - Marketing Automation
      - Sales
      - Small Business
      tier: declared
      url: /providers/keap/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Jotform
      - Typeform
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: pipedrive
      slug: pipedrive
      sources:
      - https://www.jotform.com/integrations/
      - https://www.typeform.com/connect/
      status: profiled
      tags:
      - CRM
      - Pipeline Management
      - Sales
      - Software-as-a-Service
      tier: declared
      url: /providers/pipedrive/
    - agent_band: agent-ready
      agent_readiness: 43.3
      apps:
      - Jotform
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        status: none
      name: zoho-crm
      slug: zoho-crm
      sources:
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - CRM
      - Lead Management
      - Marketing Automation
      - Sales
      tier: declared
      url: /providers/zoho-crm/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Typebot
      - Typeform
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook pixel
      slug: facebook
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/blocks/integrations/src
      - https://www.typeform.com/connect/
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 51.0
      apps:
      - Jotform
      - Typeform
      band: exemplar
      in_catalog: true
      kin_score: 81.1
      mcp:
        source: https://developers.activecampaign.com/page/mcp
        status: documented
      name: activecampaign
      slug: activecampaign
      sources:
      - https://www.jotform.com/integrations/
      - https://www.typeform.com/connect/
      status: profiled
      tags:
      - CRM
      - Email Marketing
      - Marketing Automation
      - Sales Automation
      tier: declared
      url: /providers/activecampaign/
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Jotform
      - Typeform
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: mailchimp
      slug: mailchimp
      sources:
      - https://www.jotform.com/integrations/
      - https://www.typeform.com/connect/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
    - agent_band: agent-native
      agent_readiness: 58.7
      apps:
      - Typeform
      band: exemplar
      in_catalog: true
      kin_score: 78.1
      mcp:
        source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
        status: verified
      name: klaviyo
      slug: klaviyo
      sources:
      - https://www.typeform.com/connect/
      status: profiled
      tags:
      - Customer Data
      - Email
      - Marketing
      - SMS
      tier: declared
      url: /providers/klaviyo/
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - Jotform
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        status: none
      name: constant-contact
      slug: constant-contact
      sources:
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Campaigns
      - Contacts
      - Email Marketing
      - Event
      tier: declared
      url: /providers/constant-contact/
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Formbricks
      - Jotform
      - Typebot
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: google-sheets
      slug: google-sheets
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/blocks/integrations/src
      - https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: observed
      url: /providers/google-sheets/
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - Formbricks
      - Jotform
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://github.com/Airtable/airtable-mcp-cli
        status: verified
      name: airtable
      slug: airtable
      sources:
      - https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Application
      - Collaboration
      - Data
      - Database
      tier: observed
      url: /providers/airtable/
    - agent_band: agent-ready
      agent_readiness: 29.0
      apps:
      - Jotform
      - Typeform
      band: strong
      in_catalog: true
      kin_score: 55.8
      mcp:
        status: none
      name: microsoft-excel
      slug: microsoft-excel
      sources:
      - https://www.jotform.com/integrations/
      - https://www.typeform.com/connect/
      status: profiled
      tags:
      - Automation
      - Data Analysis
      - Microsoft
      - Microsoft 365
      tier: declared
      url: /providers/microsoft-excel/
    - agent_band: agent-aware
      agent_readiness: 26.2
      apps:
      - Typebot
      band: developing
      in_catalog: true
      kin_score: 43.6
      mcp:
        source: https://nocodb.com/docs/product-docs/mcp
        status: verified
      name: nocodb
      slug: nocodb
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
      status: profiled
      tags:
      - Airtable Alternative
      - Database
      - Low-Code
      - No-Code
      tier: observed
      url: /providers/nocodb/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Formbricks
      - Jotform
      - Typeform
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: slack
      slug: slack
      sources:
      - https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
      - https://www.jotform.com/integrations/
      - https://www.typeform.com/connect/
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
      - Jotform
      - Typeform
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: microsoft-teams
      slug: microsoft-teams
      sources:
      - https://www.jotform.com/integrations/
      - https://www.typeform.com/connect/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: declared
      url: /providers/microsoft-teams/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Jotform
      band: exemplar
      in_catalog: true
      kin_score: 73.2
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: google-drive
      slug: google-drive
      sources:
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: declared
      url: /providers/google-drive/
    - agent_band: agent-ready
      agent_readiness: 56.6
      apps:
      - Jotform
      band: strong
      in_catalog: true
      kin_score: 63.0
      mcp:
        source: https://developer.box.com/guides/box-mcp/
        status: verified
      name: box
      slug: box
      sources:
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Content Management
      - Documents
      tier: declared
      url: /providers/box/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Jotform
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        status: none
      name: microsoft-onedrive
      slug: microsoft-onedrive
      sources:
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: declared
      url: /providers/microsoft-onedrive/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Jotform
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: dropbox
      slug: dropbox
      sources:
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: declared
      url: /providers/dropbox/
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.3
      apps:
      - Jotform
      - Typeform
      band: thin
      in_catalog: true
      kin_score: 32.2
      mcp:
        source: https://github.com/mondaycom/mcp
        status: verified
      name: monday.com
      slug: monday-com
      sources:
      - https://www.jotform.com/integrations/
      - https://www.typeform.com/connect/
      status: profiled
      tags:
      - Automation
      - CRM
      - GraphQL
      - Work Management
      tier: declared
      url: /providers/monday-com/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Jotform
      band: exemplar
      in_catalog: true
      kin_score: 74.8
      mcp:
        source: https://github.com/atlassian/trello-mcp-server
        status: verified
      name: trello
      slug: trello
      sources:
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Collaboration
      - Kanban
      - Project Management
      - Task Management
      tier: declared
      url: /providers/trello/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - Jotform
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: asana
      slug: asana
      sources:
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: declared
      url: /providers/asana/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Jotform
      - Typebot
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: zapier
      slug: zapier
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/blocks/integrations/src
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: observed
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 28.9
      apps:
      - Typebot
      band: developing
      in_catalog: true
      kin_score: 53.6
      mcp:
        status: none
      name: pabbly
      slug: pabbly
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/blocks/integrations/src
      status: profiled
      tags:
      - Automation
      - Billing
      - Email Marketing
      - Subscription Billing
      tier: observed
      url: /providers/pabbly/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Typebot
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: make
      slug: make
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/blocks/integrations/src
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: observed
      url: /providers/make/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 15.7
      apps:
      - Formbricks
      band: emerging
      in_catalog: true
      kin_score: 20.9
      mcp:
        source: https://cube.dev/docs/product/apis-integrations/mcp-server
        status: verified
      name: cube
      slug: cube
      sources:
      - https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
      status: profiled
      tags:
      - Business Intelligence
      - Embedded Analytics
      - GraphQL
      - Semantic Layer
      tier: observed
      url: /providers/cube/
    - agent_band: agent-aware
      agent_readiness: 28.3
      apps:
      - SurveyMonkey
      band: exemplar
      in_catalog: true
      kin_score: 76.0
      mcp:
        source: https://github.com/microsoft/powerbi-modeling-mcp
        status: verified
      name: Microsoft Power BI
      slug: power-bi
      sources:
      - https://www.surveymonkey.com/apps/
      status: profiled
      tags:
      - Analytics
      - Business Intelligence
      - Dashboards
      - Data Analysis
      tier: declared
      url: /providers/power-bi/
    - agent_band: agent-ready
      agent_readiness: 55.0
      apps:
      - SurveyMonkey
      band: developing
      in_catalog: true
      kin_score: 49.9
      mcp:
        source: https://github.com/tableau/tableau-mcp
        status: verified
      name: tableau
      slug: tableau
      sources:
      - https://www.surveymonkey.com/apps/
      status: profiled
      tags:
      - Analytics
      - Business Intelligence
      - Dashboards
      - Data Visualization
      tier: declared
      url: /providers/tableau/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Typebot
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: zendesk
      slug: zendesk
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: observed
      url: /providers/zendesk/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Typebot
      band: developing
      in_catalog: true
      kin_score: 43.5
      mcp:
        status: none
      name: chatwoot
      slug: chatwoot
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/blocks/integrations/src
      status: profiled
      tags:
      - Customer Service
      - Live Chat
      - Messaging
      - Omnichannel
      tier: observed
      url: /providers/chatwoot/
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Typeform
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: intercom
      slug: intercom
      sources:
      - https://www.typeform.com/connect/
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: declared
      url: /providers/intercom/
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Formbricks
      - Typeform
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://developers.notion.com/docs/mcp
        status: verified
      name: notion
      slug: notion
      sources:
      - https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
      - https://www.typeform.com/connect/
      status: profiled
      tags:
      - Collaboration
      - Database
      - Ideas
      - Notes
      tier: observed
      url: /providers/notion/
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.2
      apps:
      - Typebot
      band: thin
      in_catalog: true
      kin_score: 38.4
      mcp:
        source: https://github.com/calcom/cal-mcp
        status: verified
      name: cal-com
      slug: cal-com
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
      status: profiled
      tags:
      - Calendar
      - Open Source
      - Productivity
      - Scheduling
      tier: observed
      url: /providers/cal-com/
    - agent_band: agent-ready
      agent_readiness: 47.4
      apps:
      - Typeform
      band: developing
      in_catalog: true
      kin_score: 47.5
      mcp:
        source: https://developer.calendly.com/calendly-mcp-server
        status: documented
      name: calendly
      slug: calendly
      sources:
      - https://www.typeform.com/connect/
      status: profiled
      tags:
      - Appointments
      - Automation
      - Booking
      - Calendar
      tier: declared
      url: /providers/calendly/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 70.0
      apps:
      - Jotform
      band: exemplar
      in_catalog: true
      kin_score: 87.3
      mcp:
        source: https://www.canva.dev/docs/mcp/
        status: verified
      name: canva
      slug: canva
      sources:
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Application
      - Automation
      - Brand Management
      - Collaboration
      tier: declared
      url: /providers/canva/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Jotform
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: google-calendar
      slug: google-calendar
      sources:
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: declared
      url: /providers/google-calendar/
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Typeform
      band: developing
      in_catalog: true
      kin_score: 53.1
      mcp:
        status: none
      name: google-forms
      slug: google-forms
      sources:
      - https://www.typeform.com/connect/
      status: profiled
      tags:
      - Data Collection
      - Forms
      - Google
      - Google Workspace
      tier: declared
      url: /providers/google-forms/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.6
      apps:
      - Formbricks
      band: developing
      in_catalog: true
      kin_score: 39.4
      mcp:
        status: none
      name: unsplash
      slug: unsplash
      sources:
      - https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
      status: profiled
      tags:
      - Image
      - Photography
      - Photos
      - Stock Photos
      tier: observed
      url: /providers/unsplash/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Typeform
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: google-tag-manager
      slug: google-tag-manager
      sources:
      - https://www.typeform.com/connect/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: declared
      url: /providers/google-tag-manager/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Jotform
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: zoom
      slug: zoom
      sources:
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: declared
      url: /providers/zoom/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Jotform
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: whatsapp
      slug: whatsapp
      sources:
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: declared
      url: /providers/whatsapp/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - HeyForm
      - Jotform
      - Typebot
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: openai
      slug: openai
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
      - https://raw.githubusercontent.com/heyform/heyform/main/packages/server/package.json
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Jotform
      - Typebot
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: anthropic
      slug: anthropic
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 66.6
      apps:
      - Typebot
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp:
        source: https://github.com/perplexityai/modelcontextprotocol
        status: verified
      name: perplexity
      slug: perplexity
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - LLM
      - Search
      tier: observed
      url: /providers/perplexity/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Typebot
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: mistral
      slug: mistral
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
      status: profiled
      tags:
      - Agents
      - Embeddings
      - Machine Learning
      - OCR
      tier: observed
      url: /providers/mistral/
    - agent_band: agent-aware
      agent_readiness: 22.4
      apps:
      - Typebot
      band: developing
      in_catalog: true
      kin_score: 41.2
      mcp:
        status: none
      name: deepseek
      slug: deepseek
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
      status: profiled
      tags:
      - Artificial Intelligence
      - Chat
      - Chat Completions
      - LLM
      tier: observed
      url: /providers/deepseek/
    - agent_band: agent-ready
      agent_readiness: 40.0
      apps:
      - Typebot
      band: thin
      in_catalog: true
      kin_score: 34.4
      mcp:
        source: https://docs.together.ai/docs/mcp
        status: verified
      name: together-ai
      slug: together-ai
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
      status: profiled
      tags:
      - Artificial Intelligence
      - Foundation Models
      - Inference
      - LLM
      tier: observed
      url: /providers/together-ai/
    - agent_band: agent-aware
      agent_readiness: 21.2
      apps:
      - Typebot
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        source: https://github.com/groq/groq-mcp-server
        status: verified
      name: groq
      slug: groq
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
      status: profiled
      tags:
      - Artificial Intelligence
      - Inference
      - LLM
      - LPU
      tier: observed
      url: /providers/groq/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Formbricks
      - HeyForm
      - Jotform
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/formbricks/formbricks/main/apps/web/package.json
      - https://raw.githubusercontent.com/heyform/heyform/main/packages/server/package.json
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-native
      agent_readiness: 61.5
      apps:
      - Jotform
      band: exemplar
      in_catalog: true
      kin_score: 78.2
      mcp:
        source: https://developer.squareup.com/docs/mcp
        status: verified
      name: square
      slug: square
      sources:
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Booking
      - Location
      - Restaurant
      - Square
      tier: declared
      url: /providers/square/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Jotform
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: paypal
      slug: paypal
      sources:
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: declared
      url: /providers/paypal/
    - agent_band: agent-native
      agent_readiness: 45.1
      apps:
      - Jotform
      band: developing
      in_catalog: true
      kin_score: 48.9
      mcp:
        status: none
      name: worldpay
      slug: worldpay
      sources:
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Payment Gateway
      - Payment Processing
      - Payments
      - Tokenization
      tier: declared
      url: /providers/worldpay/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Jotform
      band: thin
      in_catalog: true
      kin_score: 35.5
      mcp:
        source: https://github.com/AuthorizeNet/authorize-net-mcp
        status: verified
      name: Authorize.Net
      slug: authorizenet
      sources:
      - https://www.jotform.com/integrations/
      status: profiled
      tags:
      - Company
      - Credit Cards
      - Payment Gateway
      - Payments
      tier: declared
      url: /providers/authorizenet/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Typebot
      - Typeform
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: google-analytics
      slug: google-analytics
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/blocks/integrations/src
      - https://www.typeform.com/connect/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 56.2
      apps:
      - Formbricks
      - Typebot
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: posthog
      slug: posthog
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
      - https://raw.githubusercontent.com/formbricks/formbricks/main/apps/web/package.json
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - SurveyMonkey
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
      status: profiled
      tags: &id002
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - SurveyMonkey
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Typebot
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: segment
      slug: segment
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Formbricks
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: google-recaptcha
      slug: google-recaptcha
      sources:
      - https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: observed
      url: /providers/google-recaptcha/
    - agent_band: agent-aware
      agent_readiness: 24.2
      apps:
      - Formbricks
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        source: https://github.com/cloudflare/mcp
        status: verified
      name: cloudflare-turnstile
      slug: cloudflare-turnstile
      sources:
      - https://raw.githubusercontent.com/formbricks/formbricks/main/apps/web/package.json
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Cloudflare
      - Turnstile
      tier: observed
      url: /providers/cloudflare-turnstile/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - HeyForm
      band: emerging
      in_catalog: true
      kin_score: 25.6
      mcp:
        status: none
      name: GeeTest
      slug: geetest
      sources:
      - https://raw.githubusercontent.com/heyform/heyform/main/packages/server/package.json
      status: profiled
      tags:
      - Bot Management
      - CAPTCHA
      - Fraud Prevention
      - Security
      tier: observed
      url: /providers/geetest/
    - agent_band: null
      agent_readiness: null
      apps:
      - HeyForm
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: akismet
      slug: akismet
      sources:
      - https://raw.githubusercontent.com/heyform/heyform/main/packages/server/package.json
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Formbricks
      - HeyForm
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
      - https://raw.githubusercontent.com/heyform/heyform/main/packages/server/package.json
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Formbricks
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: github
      slug: github
      sources:
      - https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - LimeSurvey
      - Typebot
      band: exemplar
      in_catalog: true
      kin_score: 66.8
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail SMTP (OAuth)
      slug: google-gmail
      sources:
      - https://github.com/LimeSurvey/LimeSurvey/tree/master/application/core/plugins
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: observed
      url: /providers/google-gmail/
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - LimeSurvey
      band: strong
      in_catalog: true
      kin_score: 64.9
      mcp:
        status: none
      name: Microsoft 365 / Exchange Online SMTP
      slug: microsoft-exchange
      sources:
      - https://github.com/LimeSurvey/LimeSurvey/tree/master/application/core/plugins
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Contacts
      - Email
      tier: observed
      url: /providers/microsoft-exchange/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.9
      apps:
      - LimeSurvey
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: google-translate
      slug: google-translate
      sources:
      - https://raw.githubusercontent.com/LimeSurvey/LimeSurvey/master/composer.json
      status: profiled
      tags:
      - Google Cloud
      - Internationalization
      - Language Detection
      - Localization
      tier: observed
      url: /providers/google-translate/
    - agent_band: agent-aware
      agent_readiness: 19.8
      apps:
      - Formbricks
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        source: https://lingo.dev/en/docs/mcp
        status: verified
      name: lingo-dev
      slug: lingo-dev
      sources:
      - https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Localization
      - Translation
      - i18n
      tier: observed
      url: /providers/lingo-dev/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Formbricks
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/formbricks/formbricks/main/apps/web/package.json
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - SurveyMonkey
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id001
      name: Google CrashLytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - SurveyMonkey
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp: *id003
      name: Salesforce Audience Studio (Krux)
      slug: salesforce
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/salesforce/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - SurveyMonkey
      band: exemplar
      in_catalog: true
      kin_score: 77.6
      mcp:
        status: none
      name: Salesforce Marketing Cloud
      slug: salesforce-marketing-cloud
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
      status: profiled
      tags:
      - Automation
      - Content Management
      - Customer Journey
      - Digital Marketing
      tier: observed
      url: /providers/salesforce-marketing-cloud/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.8
      apps:
      - Formbricks
      band: developing
      in_catalog: true
      kin_score: 44.4
      mcp:
        source: https://github.com/authzed/mcp-server-reference
        status: verified
      name: authzed
      slug: authzed
      sources:
      - https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
      status: profiled
      tags:
      - Access Control
      - Authorization
      - Permissions
      - Zanzibar
      tier: observed
      url: /providers/authzed/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - SurveyMonkey
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.surveymonkey/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - Typebot
      band: strong
      in_catalog: true
      kin_score: 54.8
      mcp:
        source: https://openrouter.ai/docs/guides/overview/mcp-server
        status: verified
      name: openrouter
      slug: openrouter
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
      status: profiled
      tags:
      - Artificial Intelligence
      - Gateways
      - LLM
      - Router
      tier: observed
      url: /providers/openrouter/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - HeyForm
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: amazon-s3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/heyform/heyform/main/packages/server/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Formbricks
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Microsoft Entra ID (Azure AD)
      slug: microsoft-entra
      sources:
      - https://raw.githubusercontent.com/formbricks/formbricks/main/.env.example
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    providers:
    - agent_band: agent-ready
      agent_readiness: 60.4
      apps:
      - Typebot
      band: exemplar
      in_catalog: true
      kin_score: 83.2
      mcp:
        source: https://github.com/elevenlabs/elevenlabs-mcp
        status: verified
      name: elevenlabs
      slug: elevenlabs
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
      status: profiled
      tags:
      - Artificial Intelligence
      - Speech-to-Text
      - Text-to-Speech
      - Voice
      tier: observed
      url: /providers/elevenlabs/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-100.20.20
      key: AE-100.20.20
      name: Multi-Agent Orchestration
      url: /capabilities/agent-to-agent-interoperability/
      via_parent: Agent-to-Agent Interoperability
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.4
      apps:
      - Typebot
      band: exemplar
      in_catalog: true
      kin_score: 78.8
      mcp:
        source: https://docs.dify.ai/en/guides/application-publishing/publish-mcp
        status: documented
      name: dify
      slug: dify
      sources:
      - https://github.com/baptisteArno/typebot.io/tree/main/packages/forge/blocks
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Backend-as-a-Service
      - LLMOps
      tier: observed
      url: /providers/dify/
  layer: agent
summary:
  coverage_pct: 98.7
  declared_only: 31
  distinct_providers: 78
  in_catalog: 77
  mcp:
    documented: 3
    none: 28
    unchecked: 1
    verified: 46
  mcp_verified: 46
  mean_kin_score: 61.4
  observed: 47
  queued: 1
  reference_apps: 7
title: 'Forms & Surveys: application blueprint'
---
