---
access: understanding
agent_layer: []
apps:
- anchor: paid-memberships-pro
  counts:
    declared: 22
    observed: 7
  evidence:
  - route: integrations page
    url: https://www.paidmembershipspro.com/add-ons/
  - route: source code
    url: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
  - route: source code
    url: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/includes/lib
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: 2Checkout (Verifone)
    provider: verifone
    says: ships the 2Checkout (Verifone) SDK or integration code
    source: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Authorizenet
    provider: authorizenet
    says: ships the Authorizenet SDK or integration code
    source: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Braintree
    provider: braintree
    says: ships the Braintree SDK or integration code
    source: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Cybersource
    provider: cybersource
    says: ships the Cybersource SDK or integration code
    source: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
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
    name: Google reCAPTCHA
    provider: google-recaptcha
    says: ships the Google reCAPTCHA SDK or integration code
    source: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/includes/lib
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Paypal
    provider: paypal
    says: ships the Paypal SDK or integration code
    source: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    credit: null
    layer: domain
    name: Avalara
    provider: avalara
    says: lists Avalara as an integration
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Aweber
    provider: aweber
    says: lists Aweber as an integration
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.10
      key: AE-170.50.10
      name: Online Communities
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    credit: null
    layer: domain
    name: Buddyboss
    provider: buddyboss
    says: lists Buddyboss as an integration
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Ccbill
    provider: ccbill
    says: lists Ccbill as an integration
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Constant Contact
    provider: constant-contact
    says: lists Constant Contact as an integration
    source: https://www.paidmembershipspro.com/add-ons/
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
    name: Google Analytics
    provider: google-analytics
    says: lists Google Analytics as an integration
    source: https://www.paidmembershipspro.com/add-ons/
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
    name: Keap
    provider: keap
    says: lists Keap as an integration
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Kit (ConvertKit)
    provider: convertkit
    says: lists Kit (ConvertKit) as an integration
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.40
      key: learning-development-management
      name: Learning & Development Management
      url: /capabilities/learning-development-management/
      via_parent: null
    credit: null
    layer: domain
    name: Learndash
    provider: learndash
    says: lists Learndash as an integration
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.40
      key: learning-development-management
      name: Learning & Development Management
      url: /capabilities/learning-development-management/
      via_parent: null
    credit: null
    layer: domain
    name: Lifterlms
    provider: lifterlms
    says: lists Lifterlms as an integration
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailerlite
    provider: mailerlite
    says: lists Mailerlite as an integration
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailpoet
    provider: mailpoet
    says: lists Mailpoet as an integration
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Payfast
    provider: payfast
    says: lists Payfast as an integration
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Paystack
    provider: paystack
    says: lists Paystack as an integration
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Post Affiliate Pro
    provider: post-affiliate-pro
    says: lists Post Affiliate Pro as an integration
    source: https://www.paidmembershipspro.com/add-ons/
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
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Square
    provider: square
    says: lists Square as an integration
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.40.20
      key: AE-140.40.20
      name: Memberships
      url: /capabilities/d2c-subscriptions/
      via_parent: D2C Subscriptions
    credit: null
    layer: domain
    name: Unlock Protocol
    provider: unlock-protocol
    says: lists Unlock Protocol as an integration
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: common
    name: Woocommerce
    provider: woocommerce
    says: lists Woocommerce as an integration
    source: https://www.paidmembershipspro.com/add-ons/
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
    name: Wp Fusion
    provider: wp-fusion
    says: lists Wp Fusion as an integration
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://www.paidmembershipspro.com/add-ons/
    tier: declared
  kind: self-hosted
  name: Paid Memberships Pro
  page: /applications/membership-associations/paid-memberships-pro/
  slug: paid-memberships-pro
  url: https://github.com/strangerstudios/paid-memberships-pro
- anchor: galette
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://github.com/galette/galette/blob/develop/composer.json
  - route: source code
    url: https://github.com/galette-plugins
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Helloasso
    provider: helloasso
    says: ships the Helloasso SDK or integration code
    source: https://github.com/galette-plugins/plugin-helloasso
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: Nominatim
    provider: nominatim
    says: ships the Nominatim SDK or integration code
    source: https://github.com/galette-plugins/plugin-maps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Paypal
    provider: paypal
    says: ships the Paypal SDK or integration code
    source: https://github.com/galette-plugins/plugin-paypal
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/galette-plugins/plugin-stripe
    tier: observed
  kind: self-hosted
  name: Galette
  page: /applications/membership-associations/galette/
  slug: galette
  url: https://github.com/galette/galette
- anchor: dolibarr-(members-module)
  counts:
    declared: 0
    observed: 10
  evidence:
  - route: source code
    url: https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
  - route: source code
    url: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Anthropic (Claude)
    provider: anthropic
    says: ships the Anthropic (Claude) SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Deepseek
    provider: deepseek
    says: ships the Deepseek SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Google Gemini
    provider: google-gemini
    says: ships the Google Gemini SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Groq
    provider: groq
    says: ships the Groq SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Mistral
    provider: mistral
    says: ships the Mistral SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI (ChatGPT)
    provider: openai
    says: ships the OpenAI (ChatGPT) SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Paypal
    provider: paypal
    says: ships the Paypal SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/paypal
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Perplexity
    provider: perplexity
    says: ships the Perplexity SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/stripe
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Zapier
    provider: zapier
    says: ships the Zapier SDK or integration code
    source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/zapier
    tier: observed
  kind: self-hosted
  name: Dolibarr (Members module)
  page: /applications/membership-associations/dolibarr-members-module/
  slug: dolibarr-members-module
  url: https://github.com/Dolibarr/dolibarr
- anchor: wildapricot
  counts:
    declared: 8
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.wildapricot.com/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Facebook
    provider: facebook
    says: lists Facebook as an integration
    source: https://www.wildapricot.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Google Calendar
    provider: google-calendar
    says: lists Google Calendar as an integration
    source: https://www.wildapricot.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Sheets
    provider: google-sheets
    says: lists Google Sheets as an integration
    source: https://www.wildapricot.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Make
    provider: make
    says: lists Make as an integration
    source: https://www.wildapricot.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Outlook
    provider: microsoft-outlook
    says: lists Microsoft Outlook as an integration
    source: https://www.wildapricot.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Quickbooks
    provider: quickbooks
    says: lists Quickbooks as an integration
    source: https://www.wildapricot.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: common
    name: Wordpress
    provider: wordpress
    says: lists Wordpress as an integration
    source: https://www.wildapricot.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://www.wildapricot.com/integrations
    tier: declared
  kind: commercial
  name: WildApricot
  page: /applications/membership-associations/wildapricot/
  slug: wildapricot
  url: https://www.wildapricot.com/
- anchor: glue-up
  counts:
    declared: 14
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.glueup.com/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Crowded
    provider: crowded
    says: lists Crowded as an integration
    source: https://www.glueup.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50
      key: event-ticketing
      name: Event Ticketing
      url: /capabilities/event-ticketing/
      via_parent: null
    credit: null
    layer: domain
    name: Cvent
    provider: cvent
    says: lists Cvent as an integration
    source: https://www.glueup.com/integrations
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
    name: Google Analytics
    provider: google-analytics
    says: lists Google Analytics as an integration
    source: https://www.glueup.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Outlook
    provider: microsoft-outlook
    says: lists Microsoft Outlook as an integration
    source: https://www.glueup.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.40
      key: learning-development-management
      name: Learning & Development Management
      url: /capabilities/learning-development-management/
      via_parent: null
    credit: null
    layer: domain
    name: Oasis Lms
    provider: oasis-lms
    says: lists Oasis Lms as an integration
    source: https://www.glueup.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Paygate
    provider: paygate
    says: lists Paygate as an integration
    source: https://www.glueup.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Paypal
    provider: paypal
    says: lists Paypal as an integration
    source: https://www.glueup.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Quickbooks
    provider: quickbooks
    says: lists Quickbooks as an integration
    source: https://www.glueup.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Sage
    provider: sage
    says: lists Sage as an integration
    source: https://www.glueup.com/integrations
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
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://www.glueup.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.50
      key: invoice-generation-management
      name: Invoice Generation Management
      url: /capabilities/invoice-generation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Storecove
    provider: storecove
    says: lists Storecove as an integration
    source: https://www.glueup.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://www.glueup.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Xero
    provider: xero
    says: lists Xero as an integration
    source: https://www.glueup.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: common
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://www.glueup.com/integrations
    tier: declared
  kind: commercial
  name: Glue Up
  page: /applications/membership-associations/glue-up/
  slug: glue-up
  url: https://www.glueup.com/
- anchor: novi-ams
  counts:
    declared: 46
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.noviams.com/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Anthropic (Claude)
    provider: anthropic
    says: lists Anthropic (Claude) as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-953
      key: AE-953
      name: Abstract, Awards & Call-for-Papers Management
      url: /capabilities/abstract-awards-call-for-papers-management/
      via_parent: null
    credit: null
    layer: domain
    name: Cadmiumcd
    provider: cadmiumcd
    says: lists Cadmiumcd as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Constant Contact
    provider: constant-contact
    says: lists Constant Contact as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50
      key: event-ticketing
      name: Event Ticketing
      url: /capabilities/event-ticketing/
      via_parent: null
    credit: null
    layer: domain
    name: Cvent
    provider: cvent
    says: lists Cvent as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.40
      key: learning-development-management
      name: Learning & Development Management
      url: /capabilities/learning-development-management/
      via_parent: null
    credit: null
    layer: domain
    name: D2L Brightspace
    provider: brightspace
    says: lists D2L Brightspace as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.40
      key: learning-development-management
      name: Learning & Development Management
      url: /capabilities/learning-development-management/
      via_parent: null
    credit: null
    layer: domain
    name: Docebo
    provider: docebo
    says: lists Docebo as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Dropbox
    provider: dropbox
    says: lists Dropbox as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Facebook
    provider: facebook
    says: lists Facebook as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Feathr
    provider: feathr
    says: lists Feathr as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Gmail
    provider: gmail
    says: lists Gmail as an integration
    source: https://www.noviams.com/integrations
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
    name: Google Analytics
    provider: google-analytics
    says: lists Google Analytics as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Google Calendar
    provider: google-calendar
    says: lists Google Calendar as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Drive
    provider: google-drive
    says: lists Google Drive as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: common
    name: Gotowebinar
    provider: gotowebinar
    says: lists Gotowebinar as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.10
      key: AE-170.50.10
      name: Online Communities
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    credit: null
    layer: domain
    name: Higher Logic
    provider: higher-logic
    says: lists Higher Logic as an integration
    source: https://www.noviams.com/integrations
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
    name: Hubspot
    provider: hubspot
    says: lists Hubspot as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Instagram
    provider: instagram
    says: lists Instagram as an integration
    source: https://www.noviams.com/integrations
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
    name: Keap
    provider: keap
    says: lists Keap as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.40
      key: learning-development-management
      name: Learning & Development Management
      url: /capabilities/learning-development-management/
      via_parent: null
    credit: null
    layer: domain
    name: Learnupon
    provider: learnupon
    says: lists Learnupon as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: Linkedin
    provider: linkedin
    says: lists Linkedin as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft 365
    provider: microsoft-365
    says: lists Microsoft 365 as an integration
    source: https://www.noviams.com/integrations
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
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: common
    name: On24
    provider: on24
    says: lists On24 as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI (ChatGPT)
    provider: openai
    says: lists OpenAI (ChatGPT) as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-953
      key: AE-953
      name: Abstract, Awards & Call-for-Papers Management
      url: /capabilities/abstract-awards-call-for-papers-management/
      via_parent: null
    credit: null
    layer: domain
    name: Openwater
    provider: openwater
    says: lists Openwater as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Propfuel
    provider: propfuel
    says: lists Propfuel as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Quickbooks
    provider: quickbooks
    says: lists Quickbooks as an integration
    source: https://www.noviams.com/integrations
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
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Sendgrid
    provider: sendgrid
    says: lists Sendgrid as an integration
    source: https://www.noviams.com/integrations
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
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: common
    name: Surveymonkey
    provider: surveymonkey
    says: lists Surveymonkey as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Trello
    provider: trello
    says: lists Trello as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: common
    name: Vimeo
    provider: vimeo
    says: lists Vimeo as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.90
      key: AE-150.90
      name: Advocacy & Legislator Outreach
      url: /capabilities/advocacy-legislator-outreach/
      via_parent: null
    credit: null
    layer: domain
    name: Votervoice
    provider: votervoice
    says: lists Votervoice as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: common
    name: Webex
    provider: webex
    says: lists Webex as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: common
    name: Wistia
    provider: wistia
    says: lists Wistia as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: common
    name: Woocommerce
    provider: woocommerce
    says: lists Woocommerce as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: common
    name: Wordpress
    provider: wordpress
    says: lists Wordpress as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: common
    name: Wufoo
    provider: wufoo
    says: lists Wufoo as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: common
    name: X (Twitter)
    provider: x
    says: lists X (Twitter) as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: common
    name: Youtube
    provider: youtube
    says: lists Youtube as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: common
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://www.noviams.com/integrations
    tier: declared
  kind: commercial
  name: Novi AMS
  page: /applications/membership-associations/novi-ams/
  slug: novi-ams
  url: https://www.noviams.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: membership-associations
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: 'Resource Planning (membership modules: Galette, Dolibarr)'
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#resource-planning
- category: Membership
  store: wordpress-plugins
  url: https://wordpress.org/plugins/tags/membership/
- category: Association Management Software
  store: capterra
  url: https://www.capterra.com/association-management-software/
- category: Association Management Software
  store: g2
  url: https://www.g2.com/categories/association-management
- category: Membership
  store: zapier
  url: https://zapier.com/apps/categories/membership
name: Membership & Association Management
needs:
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 13 provider(s) wired in by the reference apps for payment processing management
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: 1 provider(s) wired in by the reference apps for bot protection & captcha
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 1 provider(s) wired in by the reference apps for indirect tax management
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: 6 provider(s) wired in by the reference apps for email marketing sends
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: 1 provider(s) wired in by the reference apps for product usage analytics
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 4 provider(s) wired in by the reference apps for customer relationship management
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: 3 provider(s) wired in by the reference apps for digital marketing management
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: exact
  layer: common
  why: 2 provider(s) wired in by the reference apps for team chat bridging
- capability:
    attribution: API Evangelist extension
    id: AE-140.40.20
    key: AE-140.40.20
    name: Memberships
    url: /capabilities/d2c-subscriptions/
    via_parent: D2C Subscriptions
  fit: exact
  layer: domain
  why: 1 provider(s) wired in by the reference apps for memberships (on-chain)
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: exact
  layer: common
  why: 1 provider(s) wired in by the reference apps for hosted storefronts
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: 2 provider(s) wired in by the reference apps for workflow automation & ipaas
- capability:
    attribution: Turbo EA
    id: BC-300.40
    key: learning-development-management
    name: Learning & Development Management
    url: /capabilities/learning-development-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 6 provider(s) wired in by the reference apps for learning & development management
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.10
    key: AE-170.50.10
    name: Online Communities
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  fit: exact
  layer: domain
  why: 2 provider(s) wired in by the reference apps for online communities
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: common
  why: 1 provider(s) wired in by the reference apps for forward geocoding
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: 7 provider(s) wired in by the reference apps for hosted llm inference
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  fit: exact
  layer: common
  why: 1 provider(s) wired in by the reference apps for content management
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: common
  why: 4 provider(s) wired in by the reference apps for mailbox & calendar sync
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 3 provider(s) wired in by the reference apps for general ledger management
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: common
  why: 4 provider(s) wired in by the reference apps for social networks
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: 1 provider(s) wired in by the reference apps for spreadsheets
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: common
  why: 4 provider(s) wired in by the reference apps for video calling & webinars
- capability:
    attribution: API Evangelist extension
    id: AE-210.50
    key: event-ticketing
    name: Event Ticketing
    url: /capabilities/event-ticketing/
    via_parent: null
  fit: exact
  layer: domain
  why: 1 provider(s) wired in by the reference apps for event ticketing
- capability:
    attribution: Turbo EA
    id: BC-4330.50
    key: invoice-generation-management
    name: Invoice Generation Management
    url: /capabilities/invoice-generation-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 1 provider(s) wired in by the reference apps for invoice generation management
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: common
  why: 2 provider(s) wired in by the reference apps for project management
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: 2 provider(s) wired in by the reference apps for cloud drive
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: 1 provider(s) wired in by the reference apps for transactional email
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  fit: exact
  layer: common
  why: 2 provider(s) wired in by the reference apps for forms & surveys
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  fit: exact
  layer: common
  why: 3 provider(s) wired in by the reference apps for video hosting
- capability:
    attribution: API Evangelist extension
    id: AE-953
    key: AE-953
    name: Abstract, Awards & Call-for-Papers Management
    url: /capabilities/abstract-awards-call-for-papers-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 2 provider(s) wired in by the reference apps for events & group operations management
- capability:
    attribution: API Evangelist extension
    id: AE-150.90
    key: AE-150.90
    name: Advocacy & Legislator Outreach
    url: /capabilities/advocacy-legislator-outreach/
    via_parent: null
  fit: exact
  layer: domain
  why: 1 provider(s) wired in by the reference apps for advocacy & legislator outreach
stack:
- capabilities:
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
      - Dolibarr (Members module)
      - Galette
      - Glue Up
      - Novi AMS
      - Paid Memberships Pro
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/stripe
      - https://github.com/galette-plugins/plugin-stripe
      - https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Dolibarr (Members module)
      - Galette
      - Glue Up
      - Paid Memberships Pro
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: Paypal
      slug: paypal
      sources:
      - https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/paypal
      - https://github.com/galette-plugins/plugin-paypal
      - https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Paid Memberships Pro
      band: developing
      in_catalog: true
      kin_score: 44.7
      mcp:
        status: none
      name: Braintree
      slug: braintree
      sources:
      - https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
      status: profiled
      tags:
      - Mobile
      - Payments
      - Subscription
      - Transaction
      tier: observed
      url: /providers/braintree/
    - agent_band: agent-ready
      agent_readiness: 49.8
      apps:
      - Galette
      band: developing
      in_catalog: true
      kin_score: 43.8
      mcp:
        status: unchecked
      name: Helloasso
      slug: helloasso
      sources:
      - https://github.com/galette-plugins/plugin-helloasso
      status: profiled
      tags:
      - Crowdfunding
      - E-Commerce
      tier: observed
      url: /providers/helloasso/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Paid Memberships Pro
      band: thin
      in_catalog: true
      kin_score: 35.5
      mcp:
        source: https://github.com/AuthorizeNet/authorize-net-mcp
        status: verified
      name: Authorizenet
      slug: authorizenet
      sources:
      - https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
      status: profiled
      tags:
      - Company
      - Credit Cards
      - Payment Gateway
      - Payments
      tier: observed
      url: /providers/authorizenet/
    - agent_band: agent-ready
      agent_readiness: 37.3
      apps:
      - Paid Memberships Pro
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: 2Checkout (Verifone)
      slug: verifone
      sources:
      - https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
      status: profiled
      tags:
      - E-Commerce
      - Payments
      - Point-of-Sale
      - Terminal Management
      tier: observed
      url: /providers/verifone/
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - Paid Memberships Pro
      band: thin
      in_catalog: true
      kin_score: 32.5
      mcp:
        source: https://github.com/CyberSource/cybersource-developer-mcp
        status: verified
      name: Cybersource
      slug: cybersource
      sources:
      - https://github.com/strangerstudios/paid-memberships-pro/tree/dev/classes/gateways
      status: profiled
      tags:
      - Fraud Prevention
      - Payment Processing
      - Payments
      - Tokenization
      tier: observed
      url: /providers/cybersource/
    - agent_band: agent-native
      agent_readiness: 61.5
      apps:
      - Paid Memberships Pro
      band: exemplar
      in_catalog: true
      kin_score: 78.2
      mcp:
        source: https://developer.squareup.com/docs/mcp
        status: verified
      name: Square
      slug: square
      sources:
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Booking
      - Location
      - Restaurant
      - Square
      tier: declared
      url: /providers/square/
    - agent_band: agent-ready
      agent_readiness: 29.8
      apps:
      - Paid Memberships Pro
      band: strong
      in_catalog: true
      kin_score: 59.4
      mcp:
        source: https://github.com/PaystackOSS/paystack-mcp-server
        status: verified
      name: Paystack
      slug: paystack
      sources:
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Africa
      - Fintech
      - Payments
      - Recurring Billing
      tier: declared
      url: /providers/paystack/
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Paid Memberships Pro
      band: thin
      in_catalog: true
      kin_score: 27.3
      mcp:
        status: unchecked
      name: Ccbill
      slug: ccbill
      sources:
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Billing
      - Merchant Services
      - Payments
      - Subscription
      tier: declared
      url: /providers/ccbill/
    - agent_band: agent-ready
      agent_readiness: 28.8
      apps:
      - Paid Memberships Pro
      band: thin
      in_catalog: true
      kin_score: 26.6
      mcp:
        status: none
      name: Payfast
      slug: payfast
      sources:
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Payment Gateway
      - Payments
      - South Africa
      - Subscription
      tier: declared
      url: /providers/payfast/
    - agent_band: null
      agent_readiness: null
      apps:
      - Glue Up
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Crowded
      slug: crowded
      sources:
      - https://www.glueup.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Glue Up
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Paygate
      slug: paygate
      sources:
      - https://www.glueup.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
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
      - Glue Up
      - Novi AMS
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://www.glueup.com/integrations
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 44.5
      apps:
      - Novi AMS
      - Paid Memberships Pro
      band: strong
      in_catalog: true
      kin_score: 65.0
      mcp:
        status: none
      name: Keap
      slug: keap
      sources:
      - https://www.noviams.com/integrations
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - CRM
      - Marketing Automation
      - Sales
      - Small Business
      tier: declared
      url: /providers/keap/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Novi AMS
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: Hubspot
      slug: hubspot
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
    - agent_band: agent-aware
      agent_readiness: 21.8
      apps:
      - Paid Memberships Pro
      band: thin
      in_catalog: true
      kin_score: 31.4
      mcp:
        status: unchecked
      name: Wp Fusion
      slug: wp-fusion
      sources:
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - CRM Integration
      - Marketing Automation
      - Open Source
      - WordPress
      tier: declared
      url: /providers/wp-fusion/
  - capability:
      attribution: Turbo EA
      id: BC-300.40
      key: learning-development-management
      name: Learning & Development Management
      url: /capabilities/learning-development-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Paid Memberships Pro
      band: thin
      in_catalog: true
      kin_score: 32.5
      mcp:
        status: unchecked
      name: Lifterlms
      slug: lifterlms
      sources:
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Education Technology
      - Membership Training
      - Online Courses
      - WordPress Plugin
      tier: declared
      url: /providers/lifterlms/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Novi AMS
      band: thin
      in_catalog: true
      kin_score: 29.0
      mcp:
        status: none
      name: D2L Brightspace
      slug: brightspace
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - EdTech
      - Education
      - LMS
      - Valence
      tier: declared
      url: /providers/brightspace/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Paid Memberships Pro
      band: thin
      in_catalog: true
      kin_score: 26.8
      mcp:
        status: unchecked
      name: Learndash
      slug: learndash
      sources:
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - E-Learning
      - Education
      - LMS
      - WordPress
      tier: declared
      url: /providers/learndash/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Novi AMS
      band: emerging
      in_catalog: true
      kin_score: 23.1
      mcp:
        source: https://www.docebo.com/products/mcp/
        status: verified
      name: Docebo
      slug: docebo
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Courses
      - E-Learning
      - LMS
      - Training
      tier: declared
      url: /providers/docebo/
    - agent_band: agent-aware
      agent_readiness: 14.1
      apps:
      - Novi AMS
      band: emerging
      in_catalog: true
      kin_score: 21.3
      mcp:
        status: unchecked
      name: Learnupon
      slug: learnupon
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Association Learning
      - Customer Education
      - Employee Training
      - LMS
      tier: declared
      url: /providers/learnupon/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Glue Up
      band: emerging
      in_catalog: true
      kin_score: 16.2
      mcp:
        status: unchecked
      name: Oasis Lms
      slug: oasis-lms
      sources:
      - https://www.glueup.com/integrations
      status: profiled
      tags:
      - Associations
      - Continuing Education
      - Healthcare
      - LMS
      tier: declared
      url: /providers/oasis-lms/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Glue Up
      - Novi AMS
      - WildApricot
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: Quickbooks
      slug: quickbooks
      sources:
      - https://www.glueup.com/integrations
      - https://www.noviams.com/integrations
      - https://www.wildapricot.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: agent-native
      agent_readiness: 60.0
      apps:
      - Glue Up
      band: exemplar
      in_catalog: true
      kin_score: 87.1
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://www.glueup.com/integrations
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: declared
      url: /providers/xero/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Glue Up
      band: developing
      in_catalog: true
      kin_score: 41.7
      mcp:
        status: none
      name: Sage
      slug: sage
      sources:
      - https://www.glueup.com/integrations
      status: profiled
      tags:
      - Accounting
      - Business Management
      - Cloud Software
      - ERP
      tier: declared
      url: /providers/sage/
  - capability:
      attribution: API Evangelist extension
      id: AE-953
      key: AE-953
      name: Abstract, Awards & Call-for-Papers Management
      url: /capabilities/abstract-awards-call-for-papers-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.4
      apps:
      - Novi AMS
      band: thin
      in_catalog: true
      kin_score: 39.1
      mcp:
        status: unchecked
      name: Openwater
      slug: openwater
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Application Management
      - Company
      - Grants
      - Software-as-a-Service
      tier: declared
      url: /providers/openwater/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Novi AMS
      band: emerging
      in_catalog: true
      kin_score: 13.2
      mcp:
        status: unchecked
      name: Cadmiumcd
      slug: cadmiumcd
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Associations
      - Education
      - Event Management
      - LMS
      tier: declared
      url: /providers/cadmiumcd/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50
      key: event-ticketing
      name: Event Ticketing
      url: /capabilities/event-ticketing/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Glue Up
      - Novi AMS
      band: exemplar
      in_catalog: true
      kin_score: 72.6
      mcp:
        status: unknown
      name: Cvent
      slug: cvent
      sources:
      - https://www.glueup.com/integrations
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Attendee Hub
      - Attendee Management
      - Conferences
      - Diagramming
      tier: declared
      url: /providers/cvent/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.10
      key: AE-170.50.10
      name: Online Communities
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    providers:
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - Paid Memberships Pro
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        status: unchecked
      name: Buddyboss
      slug: buddyboss
      sources:
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Community
      - Education
      - LMS
      - WordPress
      tier: declared
      url: /providers/buddyboss/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Novi AMS
      band: emerging
      in_catalog: true
      kin_score: 14.2
      mcp:
        status: none
      name: Higher Logic
      slug: higher-logic
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Associations
      - Customer Retention
      - Member Engagement
      - Online Community Software
      tier: declared
      url: /providers/higher-logic/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.90
      key: AE-150.90
      name: Advocacy & Legislator Outreach
      url: /capabilities/advocacy-legislator-outreach/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Novi AMS
      band: emerging
      in_catalog: true
      kin_score: 17.3
      mcp:
        status: unchecked
      name: Votervoice
      slug: votervoice
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Advertising Services
      - Advocacy
      - Digital Advocacy
      - Grassroots
      tier: declared
      url: /providers/votervoice/
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.7
      apps:
      - Paid Memberships Pro
      band: exemplar
      in_catalog: true
      kin_score: 69.3
      mcp:
        source: https://github.com/avadev/mcp
        status: verified
      name: Avalara
      slug: avalara
      sources:
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Accounting
      - Avalara
      - Tax
      tier: declared
      url: /providers/avalara/
  - capability:
      attribution: Turbo EA
      id: BC-4330.50
      key: invoice-generation-management
      name: Invoice Generation Management
      url: /capabilities/invoice-generation-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - Glue Up
      band: developing
      in_catalog: true
      kin_score: 52.7
      mcp:
        status: unknown
      name: Storecove
      slug: storecove
      sources:
      - https://www.glueup.com/integrations
      status: profiled
      tags:
      - Company
      - E-Invoicing
      - Peppol
      - Tax Compliance
      tier: declared
      url: /providers/storecove/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.40.20
      key: AE-140.40.20
      name: Memberships
      url: /capabilities/d2c-subscriptions/
      via_parent: D2C Subscriptions
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - Paid Memberships Pro
      band: developing
      in_catalog: true
      kin_score: 49.2
      mcp:
        status: none
      name: Unlock Protocol
      slug: unlock-protocol
      sources:
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Blockchain
      - Membership
      - NFT
      - Subscription
      tier: declared
      url: /providers/unlock-protocol/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Novi AMS
      - Paid Memberships Pro
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://www.noviams.com/integrations
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - Novi AMS
      - Paid Memberships Pro
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        status: none
      name: Constant Contact
      slug: constant-contact
      sources:
      - https://www.noviams.com/integrations
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Campaigns
      - Contacts
      - Email Marketing
      - Event
      tier: declared
      url: /providers/constant-contact/
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Paid Memberships Pro
      band: exemplar
      in_catalog: true
      kin_score: 80.4
      mcp:
        status: none
      name: Kit (ConvertKit)
      slug: convertkit
      sources:
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Automation
      - Creator Economy
      - Email Marketing
      - Subscribers
      tier: declared
      url: /providers/convertkit/
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - Paid Memberships Pro
      band: exemplar
      in_catalog: true
      kin_score: 71.7
      mcp:
        source: https://github.com/aweber/aweber-mcp
        status: verified
      name: Aweber
      slug: aweber
      sources:
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Email
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/aweber/
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - Paid Memberships Pro
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp:
        source: https://developers.mailerlite.com/
        status: documented
      name: Mailerlite
      slug: mailerlite
      sources:
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Automation
      - Email Marketing
      - Newsletters
      - Subscribers
      tier: declared
      url: /providers/mailerlite/
    - agent_band: agent-ready
      agent_readiness: 31.0
      apps:
      - Paid Memberships Pro
      band: emerging
      in_catalog: true
      kin_score: 24.0
      mcp:
        status: unchecked
      name: Mailpoet
      slug: mailpoet
      sources:
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Email Marketing
      - Newsletters
      - Open Source
      - WordPress
      tier: declared
      url: /providers/mailpoet/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Glue Up
      - WildApricot
      band: exemplar
      in_catalog: true
      kin_score: 70.8
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Outlook
      slug: microsoft-outlook
      sources:
      - https://www.glueup.com/integrations
      - https://www.wildapricot.com/integrations
      status: profiled
      tags:
      - Calendar
      - Contacts
      - Email
      - Enterprise
      tier: declared
      url: /providers/microsoft-outlook/
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Novi AMS
      - WildApricot
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://www.noviams.com/integrations
      - https://www.wildapricot.com/integrations
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: declared
      url: /providers/google-calendar/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Novi AMS
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft 365
      slug: microsoft-365
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/microsoft-365/
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - Novi AMS
      band: exemplar
      in_catalog: true
      kin_score: 66.8
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: declared
      url: /providers/google-gmail/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Novi AMS
      - WildApricot
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://www.noviams.com/integrations
      - https://www.wildapricot.com/integrations
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: declared
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Novi AMS
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp:
        status: none
      name: Linkedin
      slug: linkedin
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: declared
      url: /providers/linkedin/
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - Novi AMS
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: X (Twitter)
      slug: x
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: declared
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
      - Novi AMS
      band: exemplar
      in_catalog: true
      kin_score: 67.8
      mcp:
        status: none
      name: Instagram
      slug: instagram
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Instagram
      - Meta
      - Photos
      - Social Media
      tier: declared
      url: /providers/instagram/
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
      - Glue Up
      - Novi AMS
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://www.glueup.com/integrations
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: declared
      url: /providers/zoom/
    - agent_band: agent-ready
      agent_readiness: 61.8
      apps:
      - Novi AMS
      band: strong
      in_catalog: true
      kin_score: 66.1
      mcp:
        source: https://github.com/WebexSamples/webex-messaging-mcp-server
        status: verified
      name: Webex
      slug: webex
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Calling
      - Collaboration
      - Communications
      - Enterprise
      tier: declared
      url: /providers/webex/
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - Novi AMS
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp:
        source: https://mcp.goto.com/mcp
        status: verified
      name: Gotowebinar
      slug: gotowebinar
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Attendees
      - Collaboration
      - Communications
      - Event
      tier: declared
      url: /providers/gotowebinar/
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Novi AMS
      band: developing
      in_catalog: true
      kin_score: 43.6
      mcp:
        status: none
      name: On24
      slug: on24
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Company
      - Digital Engagement
      - Virtual Events
      - Webinars
      tier: declared
      url: /providers/on24/
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
      - Dolibarr (Members module)
      - Novi AMS
      - Paid Memberships Pro
      - WildApricot
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/zapier
      - https://www.noviams.com/integrations
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: observed
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - WildApricot
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://www.wildapricot.com/integrations
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.0
      apps:
      - Novi AMS
      band: thin
      in_catalog: true
      kin_score: 36.7
      mcp:
        status: none
      name: Feathr
      slug: feathr
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Digital Marketing
      - Non-Profit
      tier: declared
      url: /providers/feathr/
    - agent_band: agent-aware
      agent_readiness: 14.5
      apps:
      - Paid Memberships Pro
      band: thin
      in_catalog: true
      kin_score: 32.8
      mcp:
        status: unchecked
      name: Post Affiliate Pro
      slug: post-affiliate-pro
      sources:
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Affiliates
      - Marketing
      - Software-as-a-Service
      - Tracking
      tier: declared
      url: /providers/post-affiliate-pro/
    - agent_band: agent-aware
      agent_readiness: 17.1
      apps:
      - Novi AMS
      band: emerging
      in_catalog: true
      kin_score: 14.1
      mcp:
        status: unchecked
      name: Propfuel
      slug: propfuel
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - AMS Integration
      - Associations
      - Email Marketing
      - Member Engagement
      tier: declared
      url: /providers/propfuel/
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
      - Glue Up
      - Novi AMS
      - Paid Memberships Pro
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://www.glueup.com/integrations
      - https://www.noviams.com/integrations
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: declared
      url: /providers/google-analytics/
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
      - Novi AMS
      - Paid Memberships Pro
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://www.noviams.com/integrations
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Novi AMS
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://www.noviams.com/integrations
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
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.6
      apps:
      - Novi AMS
      band: exemplar
      in_catalog: true
      kin_score: 75.5
      mcp:
        source: https://docs.wistia.com/docs/mcp-server-guide
        status: documented
      name: Wistia
      slug: wistia
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Lead Generation
      - Video Analytics
      - Video Hosting
      - Video Marketing
      tier: declared
      url: /providers/wistia/
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - Novi AMS
      band: strong
      in_catalog: true
      kin_score: 65.4
      mcp:
        status: none
      name: Youtube
      slug: youtube
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: declared
      url: /providers/youtube/
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - Novi AMS
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp:
        source: https://developer.vimeo.com/api/mcp-server
        status: documented
      name: Vimeo
      slug: vimeo
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Live Streaming
      - Streaming
      - Video
      - Video Hosting
      tier: declared
      url: /providers/vimeo/
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
      - Novi AMS
      band: exemplar
      in_catalog: true
      kin_score: 73.2
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: declared
      url: /providers/google-drive/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Novi AMS
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: declared
      url: /providers/dropbox/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Novi AMS
      - WildApricot
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        source: https://github.com/WordPress/mcp-adapter
        status: verified
      name: Wordpress
      slug: wordpress
      sources:
      - https://www.noviams.com/integrations
      - https://www.wildapricot.com/integrations
      status: profiled
      tags:
      - CMS
      - Content Management
      - Open Source
      - WordPress
      tier: declared
      url: /providers/wordpress/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Novi AMS
      - Paid Memberships Pro
      band: strong
      in_catalog: true
      kin_score: 54.6
      mcp:
        source: https://developer.woocommerce.com/docs/features/mcp/
        status: verified
      name: Woocommerce
      slug: woocommerce
      sources:
      - https://www.noviams.com/integrations
      - https://www.paidmembershipspro.com/add-ons/
      status: profiled
      tags:
      - E-Commerce
      - Open Source
      - Order
      - WooCommerce
      tier: declared
      url: /providers/woocommerce/
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Novi AMS
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: Wufoo
      slug: wufoo
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Data Collection
      - Form Builder
      - Forms
      - Surveys
      tier: declared
      url: /providers/wufoo/
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Novi AMS
      band: thin
      in_catalog: true
      kin_score: 34.9
      mcp:
        source: https://www.surveymonkey.com/apps/
        status: documented
      name: Surveymonkey
      slug: surveymonkey
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Feedback
      - Market Research
      - NPS
      - Surveys
      tier: declared
      url: /providers/surveymonkey/
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Novi AMS
      band: exemplar
      in_catalog: true
      kin_score: 74.8
      mcp:
        source: https://github.com/atlassian/trello-mcp-server
        status: verified
      name: Trello
      slug: trello
      sources:
      - https://www.noviams.com/integrations
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
      - Novi AMS
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://www.noviams.com/integrations
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
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Paid Memberships Pro
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://github.com/strangerstudios/paid-memberships-pro/tree/dev/includes/lib
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: observed
      url: /providers/google-recaptcha/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - Galette
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Nominatim
      slug: nominatim
      sources:
      - https://github.com/galette-plugins/plugin-maps
      status: profiled
      tags:
      - Geocoding
      - Location Services
      - Maps
      - OpenStreetMap
      tier: observed
      url: /providers/nominatim/
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
      - WildApricot
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://www.wildapricot.com/integrations
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: declared
      url: /providers/google-sheets/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - Novi AMS
      band: exemplar
      in_catalog: true
      kin_score: 84.0
      mcp:
        status: none
      name: Sendgrid
      slug: sendgrid
      sources:
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: declared
      url: /providers/sendgrid/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Dolibarr (Members module)
      - Novi AMS
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic (Claude)
      slug: anthropic
      sources:
      - https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Dolibarr (Members module)
      - Novi AMS
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI (ChatGPT)
      slug: openai
      sources:
      - https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
      - https://www.noviams.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-native
      agent_readiness: 66.6
      apps:
      - Dolibarr (Members module)
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp:
        source: https://github.com/perplexityai/modelcontextprotocol
        status: verified
      name: Perplexity
      slug: perplexity
      sources:
      - https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - LLM
      - Search
      tier: observed
      url: /providers/perplexity/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Dolibarr (Members module)
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Dolibarr (Members module)
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Mistral
      slug: mistral
      sources:
      - https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
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
      - Dolibarr (Members module)
      band: developing
      in_catalog: true
      kin_score: 41.2
      mcp:
        status: none
      name: Deepseek
      slug: deepseek
      sources:
      - https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
      status: profiled
      tags:
      - Artificial Intelligence
      - Chat
      - Chat Completions
      - LLM
      tier: observed
      url: /providers/deepseek/
    - agent_band: agent-aware
      agent_readiness: 21.2
      apps:
      - Dolibarr (Members module)
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        source: https://github.com/groq/groq-mcp-server
        status: verified
      name: Groq
      slug: groq
      sources:
      - https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
      status: profiled
      tags:
      - Artificial Intelligence
      - Inference
      - LLM
      - LPU
      tier: observed
      url: /providers/groq/
  layer: agent
summary:
  coverage_pct: 97.6
  declared_only: 66
  distinct_providers: 83
  in_catalog: 81
  mcp:
    documented: 4
    none: 26
    unchecked: 16
    verified: 35
  mcp_verified: 35
  mean_kin_score: 54.1
  observed: 17
  queued: 2
  reference_apps: 6
title: 'Membership & Association Management: application blueprint'
---
