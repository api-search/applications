---
access: understanding
agent_layer:
- app: Postiz
  finding: ships its own MCP server (@mastra/mcp, @modelcontextprotocol/sdk) with OAuth dynamic client registration for Claude, Cursor and ChatGPT connectors
  source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
  tier: observed
- app: Buffer
  finding: lists a Social Media MCP and ChatGPT / Claude / Cursor / Perplexity agent integrations
  source: https://buffer.com/integrations
  tier: declared
- app: Hootsuite
  finding: no agent surface on the integrations page; AI is in-product (Wisdom)
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
apps:
- anchor: postiz
  counts:
    declared: 0
    observed: 57
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/package.json
  - route: source code
    url: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
  - route: source code
    url: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
  - route: source code
    url: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Apple
    provider: apple
    says: ships the Apple SDK or integration code
    source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.30
      key: AE-170.60.30
      name: Newsletters
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: beehiiv
    provider: beehiiv
    says: ships the beehiiv SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Bluesky
    provider: bluesky
    says: ships the Bluesky SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: domain
    name: Canva
    provider: canva
    says: ships the Canva SDK or integration code
    source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
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
    name: Cloudflare R2
    provider: cloudflare-r2
    says: ships the Cloudflare R2 SDK or integration code
    source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: common
    name: Deepgram
    provider: deepgram
    says: ships the Deepgram SDK or integration code
    source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60
      key: AE-170.60
      name: News & Publishing
      url: /capabilities/news-publishing/
      via_parent: null
    credit: null
    layer: domain
    name: DEV Community
    provider: dev-to
    says: ships the DEV Community SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.10
      key: AE-170.50.10
      name: Online Communities
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    credit: null
    layer: domain
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.10
      key: AE-170.50.10
      name: Online Communities
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    credit: null
    layer: domain
    name: Dribbble
    provider: dribbble
    says: ships the Dribbble SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Dub
    provider: dub
    says: ships the Dub SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.20.20
      key: AE-110.20.20
      name: Video Generation
      url: /capabilities/generative-media/
      via_parent: Generative Media
    credit: null
    layer: domain
    name: EvoLink (Seedance)
    provider: evolink
    says: ships the EvoLink (Seedance) SDK or integration code
    source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Farcaster
    provider: farcaster
    says: ships the Farcaster SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
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
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: Google Business Profile
    provider: google-business-profile
    says: ships the Google Business Profile SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
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
    source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60
      key: AE-170.60
      name: News & Publishing
      url: /capabilities/news-publishing/
      via_parent: null
    credit: null
    layer: domain
    name: Hashnode
    provider: hashnode
    says: ships the Hashnode SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.20.20
      key: AE-110.20.20
      name: Video Generation
      url: /capabilities/generative-media/
      via_parent: Generative Media
    credit: null
    layer: domain
    name: HeyGen
    provider: heygen
    says: ships the HeyGen SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: HubSpot
    provider: hubspot
    says: ships the HubSpot SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Instagram
    provider: instagram
    says: ships the Instagram SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: Kick (kick.com)
    provider: kick-com
    says: ships the Kick (kick.com) SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Kutt
    provider: kutt
    says: ships the Kutt SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Lemmy
    provider: lemmy
    says: ships the Lemmy SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: LinkDrip
    provider: linkdrip
    says: ships the LinkDrip SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: LinkedIn
    provider: linkedin
    says: ships the LinkedIn SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.30
      key: AE-170.60.30
      name: Newsletters
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: listmonk
    provider: listmonk
    says: ships the listmonk SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Mastodon
    provider: mastodon
    says: ships the Mastodon SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60
      key: AE-170.60
      name: News & Publishing
      url: /capabilities/news-publishing/
      via_parent: null
    credit: null
    layer: domain
    name: Medium
    provider: medium
    says: ships the Medium SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: MeWe
    provider: mewe
    says: ships the MeWe SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Moltbook
    provider: moltbook
    says: ships the Moltbook SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Neynar
    provider: neynar
    says: ships the Neynar SDK or integration code
    source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/package.json
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
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Pinterest
    provider: pinterest
    says: ships the Pinterest SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
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
    name: Plausible
    provider: plausible
    says: ships the Plausible SDK or integration code
    source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: domain
    name: Polotno
    provider: polotno
    says: ships the Polotno SDK or integration code
    source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Reddit
    provider: reddit
    says: ships the Reddit SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.20.20
      key: AE-110.20.20
      name: Video Generation
      url: /capabilities/generative-media/
      via_parent: Generative Media
    credit: null
    layer: domain
    name: ReelFarm
    provider: reelfarm
    says: ships the ReelFarm SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
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
    name: Resend
    provider: resend
    says: ships the Resend SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: common
    name: RevenueCat
    provider: revenuecat
    says: ships the RevenueCat SDK or integration code
    source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
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
    name: RunPod
    provider: runpod
    says: ships the RunPod SDK or integration code
    source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
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
    source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Short.io
    provider: short-io
    says: ships the Short.io SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.10
      key: AE-170.50.10
      name: Online Communities
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    credit: null
    layer: domain
    name: Skool
    provider: skool
    says: ships the Skool SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
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
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.20
      key: AE-230.40.20
      name: Web Search APIs
      url: /capabilities/web-data/
      via_parent: Web Data
    credit: null
    layer: common
    name: Tavily
    provider: tavily
    says: ships the Tavily SDK or integration code
    source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Threads
    provider: threads-api
    says: ships the Threads SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: TikTok
    provider: tiktok
    says: ships the TikTok SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.10
      key: AE-170.30.10
      name: Image Processing & Optimisation
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Transloadit
    provider: transloadit
    says: ships the Transloadit SDK or integration code
    source: https://raw.githubusercontent.com/gitroomhq/postiz-app/main/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Tumblr
    provider: tumblr
    says: ships the Tumblr SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: Twitch
    provider: twitch
    says: ships the Twitch SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: VK
    provider: vk
    says: ships the VK SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.10
      key: AE-170.50.10
      name: Online Communities
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    credit: null
    layer: domain
    name: Whop
    provider: whop
    says: ships the Whop SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: WordPress
    provider: wordpress
    says: ships the WordPress SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: X (Twitter)
    provider: x
    says: ships the X (Twitter) SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: YouTube
    provider: youtube
    says: ships the YouTube SDK or integration code
    source: https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
    tier: observed
  kind: self-hosted
  name: Postiz
  page: /applications/social-media-management/postiz/
  slug: postiz
  url: https://github.com/gitroomhq/postiz-app
- anchor: mixpost
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/inovector/mixpost/main/composer.json
  - route: source code
    url: https://github.com/inovector/mixpost/tree/main/src/Services
  - route: source code
    url: https://github.com/inovector/mixpost/tree/main/src/SocialProviders
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/inovector/mixpost/tree/main/src/SocialProviders
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Mastodon
    provider: mastodon
    says: ships the Mastodon SDK or integration code
    source: https://github.com/inovector/mixpost/tree/main/src/SocialProviders
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
    name: Tenor
    provider: tenor
    says: ships the Tenor SDK or integration code
    source: https://github.com/inovector/mixpost/tree/main/src/Services
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
    name: Unsplash
    provider: unsplash
    says: ships the Unsplash SDK or integration code
    source: https://github.com/inovector/mixpost/tree/main/src/Services
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: X (Twitter)
    provider: x
    says: ships the X (Twitter) SDK or integration code
    source: https://github.com/inovector/mixpost/tree/main/src/SocialProviders
    tier: observed
  kind: self-hosted
  name: Mixpost
  page: /applications/social-media-management/mixpost/
  slug: mixpost
  url: https://github.com/inovector/mixpost
- anchor: socioboard
  counts:
    declared: 0
    observed: 22
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/socioboard-api/Common/package.json
  - route: source code
    url: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
  - route: source code
    url: https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/docker/.env.example
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3750.20
      key: subscription-entitlement-management
      name: Subscription & Entitlement Management
      url: /capabilities/subscription-entitlement-management/
      via_parent: null
    credit: null
    layer: common
    name: aMember
    provider: amember
    says: ships the aMember SDK or integration code
    source: https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/docker/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Bitly
    provider: bitly
    says: ships the Bitly SDK or integration code
    source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: Dailymotion
    provider: dailymotion
    says: ships the Dailymotion SDK or integration code
    source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster/trends.cluster.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
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
    name: Flickr
    provider: flickr
    says: ships the Flickr SDK or integration code
    source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster/trends.cluster.js
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
    name: GIPHY
    provider: giphy
    says: ships the GIPHY SDK or integration code
    source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster/trends.cluster.js
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
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/docker/.env.example
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
    source: https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/docker/.env.example
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
    name: Imgur
    provider: imgur
    says: ships the Imgur SDK or integration code
    source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster/trends.cluster.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Instagram
    provider: instagram
    says: ships the Instagram SDK or integration code
    source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: LinkedIn
    provider: linkedin
    says: ships the LinkedIn SDK or integration code
    source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60
      key: AE-170.60
      name: News & Publishing
      url: /capabilities/news-publishing/
      via_parent: null
    credit: null
    layer: domain
    name: Medium
    provider: medium
    says: ships the Medium SDK or integration code
    source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.10
      key: AE-170.60.10
      name: News Data
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: NewsAPI
    provider: newsapi
    says: ships the NewsAPI SDK or integration code
    source: https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/socioboard-api/Common/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Pinterest
    provider: pinterest
    says: ships the Pinterest SDK or integration code
    source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
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
    name: Pixabay
    provider: pixabay
    says: ships the Pixabay SDK or integration code
    source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster/trends.cluster.js
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
    name: SendGrid
    provider: sendgrid
    says: ships the SendGrid SDK or integration code
    source: https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/socioboard-api/Common/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: TikTok
    provider: tiktok
    says: ships the TikTok SDK or integration code
    source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: TinyURL
    provider: tinyurl
    says: ships the TinyURL SDK or integration code
    source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Tumblr
    provider: tumblr
    says: ships the Tumblr SDK or integration code
    source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/socioboard-api/Common/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: X (Twitter)
    provider: x
    says: ships the X (Twitter) SDK or integration code
    source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: YouTube
    provider: youtube
    says: ships the YouTube SDK or integration code
    source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
    tier: observed
  kind: self-hosted
  name: Socioboard
  page: /applications/social-media-management/socioboard/
  slug: socioboard
  url: https://github.com/socioboard/Socioboard-5.0
- anchor: hootsuite
  counts:
    declared: 35
    observed: 7
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
  - route: integrations page
    url: https://apps.hootsuite.com/
  - route: integrations page
    url: https://www.hootsuite.com/platform/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Airship (Urban Airship)
    provider: airship
    says: ships the Airship (Urban Airship) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
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
    name: Pendo
    provider: pendoio
    says: ships the Pendo SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Pusher
    provider: pusher
    says: ships the Pusher SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
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
    name: Wootric
    provider: wootric
    says: ships the Wootric SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.70
      key: content-marketing-management
      name: Content Marketing Management
      url: /capabilities/content-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Acquia
    provider: acquia
    says: lists Acquia as an integration
    source: https://www.hootsuite.com/platform/integrations
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
    name: Adobe Express
    provider: adobe-express
    says: lists Adobe Express as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Bluesky
    provider: bluesky
    says: lists Bluesky as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: domain
    name: Brightcove
    provider: brightcove
    says: lists Brightcove as an integration
    source: https://apps.hootsuite.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bynder
    provider: bynder
    says: lists Bynder as an integration
    source: https://www.hootsuite.com/platform/integrations
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
    name: Canva
    provider: canva
    says: lists Canva as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.10
      key: AE-170.30.10
      name: Image Processing & Optimisation
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Cloudinary
    provider: cloudinary
    says: lists Cloudinary as an integration
    source: https://apps.hootsuite.com/
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
    name: Dribbble
    provider: dribbble
    says: lists Dribbble as an integration
    source: https://apps.hootsuite.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-914
      key: AE-914
      name: Social Listening & Analytics
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Fedica
    provider: fedica
    says: lists Fedica as an integration
    source: https://www.hootsuite.com/platform/integrations
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
    name: Figma
    provider: figma
    says: lists Figma as an integration
    source: https://apps.hootsuite.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: Google Business Profile
    provider: google-business-profile
    says: lists Google Business Profile as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Instagram
    provider: instagram
    says: lists Instagram as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: LinkedIn
    provider: linkedin
    says: lists LinkedIn as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.20.20
      key: AE-110.20.20
      name: Video Generation
      url: /capabilities/generative-media/
      via_parent: Generative Media
    credit: null
    layer: domain
    name: Lumen5
    provider: lumen5
    says: lists Lumen5 as an integration
    source: https://www.hootsuite.com/platform/integrations
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
    name: Miro
    provider: miro
    says: lists Miro as an integration
    source: https://apps.hootsuite.com/
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
    name: monday.com
    provider: monday-com
    says: lists monday.com as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: OneClick.bio
    provider: oneclick-bio
    says: lists OneClick.bio as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-914
      key: AE-914
      name: Social Listening & Analytics
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Panoramiq Insights
    provider: panoramiq
    says: lists Panoramiq Insights as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Pinterest
    provider: pinterest
    says: lists Pinterest as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3780
      key: content-compliance-standards-management
      name: Content Compliance & Standards Management
      url: /capabilities/content-compliance-standards-management/
      via_parent: null
    credit: null
    layer: domain
    name: Proofpoint
    provider: proofpoint
    says: lists Proofpoint as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: ReviewTrackers
    provider: reviewtrackers
    says: lists ReviewTrackers as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-914
      key: AE-914
      name: Social Listening & Analytics
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Talkwalker
    provider: talkwalker
    says: lists Talkwalker as an integration
    source: https://apps.hootsuite.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Threads
    provider: threads-api
    says: lists Threads as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: TikTok
    provider: tiktok
    says: lists TikTok as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.40
      key: loyalty-retention-management
      name: Loyalty & Retention Management
      url: /capabilities/loyalty-retention-management/
      via_parent: null
    credit: null
    layer: domain
    name: TrueLoyal
    provider: trueloyal
    says: lists TrueLoyal as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.70
      key: AE-140.70
      name: Social & Creator Commerce
      url: /capabilities/social-creator-commerce/
      via_parent: null
    credit: null
    layer: domain
    name: Upfluence
    provider: upfluence
    says: lists Upfluence as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: domain
    name: Vidyard
    provider: vidyard
    says: lists Vidyard as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: domain
    name: Vimeo
    provider: vimeo
    says: lists Vimeo as an integration
    source: https://apps.hootsuite.com/
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
    name: WhatsApp
    provider: whatsapp
    says: lists WhatsApp as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: WordPress
    provider: wordpress
    says: lists WordPress as an integration
    source: https://apps.hootsuite.com/
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
    name: Wrike
    provider: wrike
    says: lists Wrike as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: X (Twitter)
    provider: x
    says: lists X (Twitter) as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: YouTube
    provider: youtube
    says: lists YouTube as an integration
    source: https://www.hootsuite.com/platform/integrations
    tier: declared
  kind: commercial
  name: Hootsuite
  page: /applications/social-media-management/hootsuite/
  slug: hootsuite
  url: https://www.hootsuite.com/
- anchor: buffer
  counts:
    declared: 35
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/org.buffer.android/latest/
  - route: integrations page
    url: https://buffer.com/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Pusher
    provider: pusher
    says: ships the Pusher SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/org.buffer.android/latest/
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
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/org.buffer.android/latest/
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
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/org.buffer.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Split
    provider: split
    says: ships the Split SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/org.buffer.android/latest/
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
    name: Anthropic (Claude)
    provider: anthropic
    says: lists Anthropic (Claude) as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Bitly
    provider: bitly
    says: lists Bitly as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Bluesky
    provider: bluesky
    says: lists Bluesky as an integration
    source: https://buffer.com/integrations
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
    name: Canva
    provider: canva
    says: lists Canva as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-905
      key: AE-905
      name: IDEs & AI Coding Assistants
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    credit: null
    layer: agent
    name: Cursor
    provider: cursor
    says: lists Cursor as an integration
    source: https://buffer.com/integrations
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
    name: Dropbox
    provider: dropbox
    says: lists Dropbox as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Evergreen Content Poster
    provider: evergreen-content-poster
    says: lists Evergreen Content Poster as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Facebook
    provider: facebook
    says: lists Facebook as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.70
      key: distribution-content-syndication
      name: Distribution Content Syndication
      url: /capabilities/distribution-content-syndication/
      via_parent: null
    credit: null
    layer: domain
    name: Feedly
    provider: feedly
    says: lists Feedly as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: Google Business Profile
    provider: google-business-profile
    says: lists Google Business Profile as an integration
    source: https://buffer.com/integrations
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
    name: Google Drive
    provider: google-drive
    says: lists Google Drive as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.20
      key: AE-170.30.20
      name: Photo Sharing
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Google Photos
    provider: google-photos
    says: lists Google Photos as an integration
    source: https://buffer.com/integrations
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
    name: IFTTT
    provider: ifttt
    says: lists IFTTT as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Instagram
    provider: instagram
    says: lists Instagram as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: LinkedIn
    provider: linkedin
    says: lists LinkedIn as an integration
    source: https://buffer.com/integrations
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
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Mastodon
    provider: mastodon
    says: lists Mastodon as an integration
    source: https://buffer.com/integrations
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
    name: Microsoft OneDrive
    provider: microsoft-onedrive
    says: lists Microsoft OneDrive as an integration
    source: https://buffer.com/integrations
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
    name: Microsoft Power Automate
    provider: microsoft-power-automate
    says: lists Microsoft Power Automate as an integration
    source: https://buffer.com/integrations
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
    name: n8n
    provider: n8n
    says: lists n8n as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Nelio Content
    provider: nelio-content
    says: lists Nelio Content as an integration
    source: https://buffer.com/integrations
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
    name: OpenAI
    provider: openai
    says: lists OpenAI as an integration
    source: https://buffer.com/integrations
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
    name: Perplexity
    provider: perplexity
    says: lists Perplexity as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Pinterest
    provider: pinterest
    says: lists Pinterest as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.70
      key: distribution-content-syndication
      name: Distribution Content Syndication
      url: /capabilities/distribution-content-syndication/
      via_parent: null
    credit: null
    layer: domain
    name: Quuu
    provider: quuu
    says: lists Quuu as an integration
    source: https://buffer.com/integrations
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
    name: Raycast
    provider: raycast
    says: lists Raycast as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60
      key: AE-170.60
      name: News & Publishing
      url: /capabilities/news-publishing/
      via_parent: null
    credit: null
    layer: domain
    name: Substack
    provider: substack
    says: lists Substack as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Threads
    provider: threads-api
    says: lists Threads as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: TikTok
    provider: tiktok
    says: lists TikTok as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: domain
    name: Unsplash
    provider: unsplash
    says: lists Unsplash as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: WordPress
    provider: wordpress
    says: lists WordPress as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: WriteStack
    provider: writestack
    says: lists WriteStack as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: X (Twitter)
    provider: x
    says: lists X (Twitter) as an integration
    source: https://buffer.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: YouTube
    provider: youtube
    says: lists YouTube as an integration
    source: https://buffer.com/integrations
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
    source: https://buffer.com/integrations
    tier: declared
  kind: commercial
  name: Buffer
  page: /applications/social-media-management/buffer/
  slug: buffer
  url: https://buffer.com/
- anchor: sprout-social
  counts:
    declared: 41
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.sproutsocial.android/latest/
  - route: integrations page
    url: https://sproutsocial.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sproutsocial.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sproutsocial.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: domain
    name: Adobe Experience Manager
    provider: adobe-experience-manager
    says: lists Adobe Experience Manager as an integration
    source: https://sproutsocial.com/integrations/
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
    name: Adobe Express
    provider: adobe-express
    says: lists Adobe Express as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: Apple
    provider: apple
    says: lists Apple as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Bitly
    provider: bitly
    says: lists Bitly as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Bluesky
    provider: bluesky
    says: lists Bluesky as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bynder
    provider: bynder
    says: lists Bynder as an integration
    source: https://sproutsocial.com/integrations/
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
    name: Canva
    provider: canva
    says: lists Canva as an integration
    source: https://sproutsocial.com/integrations/
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
    name: Dropbox
    provider: dropbox
    says: lists Dropbox as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Facebook
    provider: facebook
    says: lists Facebook as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: Glassdoor
    provider: glassdoor
    says: lists Glassdoor as an integration
    source: https://sproutsocial.com/integrations/
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
    source: https://sproutsocial.com/integrations/
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
    name: Google Drive
    provider: google-drive
    says: lists Google Drive as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: Google Play (reviews)
    provider: google-play
    says: lists Google Play (reviews) as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Instagram
    provider: instagram
    says: lists Instagram as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: LinkedIn
    provider: linkedin
    says: lists LinkedIn as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.50
      key: marketing-operations-management
      name: Marketing Operations Management
      url: /capabilities/marketing-operations-management/
      via_parent: null
    credit: null
    layer: common
    name: Marketo
    provider: marketo
    says: lists Marketo as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Dynamics 365
    provider: microsoft-dynamics-365
    says: lists Microsoft Dynamics 365 as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.70
      key: content-marketing-management
      name: Content Marketing Management
      url: /capabilities/content-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Opal
    provider: opal
    says: lists Opal as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.70
      key: content-marketing-management
      name: Content Marketing Management
      url: /capabilities/content-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Optimizely
    provider: optimizely
    says: lists Optimizely as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Pinterest
    provider: pinterest
    says: lists Pinterest as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Reddit
    provider: reddit
    says: lists Reddit as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.50
      key: marketing-operations-management
      name: Marketing Operations Management
      url: /capabilities/marketing-operations-management/
      via_parent: null
    credit: null
    layer: common
    name: Salesforce Agentforce Marketing / Marketing Intelligence
    provider: salesforce-marketing-cloud
    says: lists Salesforce Agentforce Marketing / Marketing Intelligence as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Salesforce Agentforce Sales (Sales Cloud)
    provider: salesforce-sales-cloud
    says: lists Salesforce Agentforce Sales (Sales Cloud) as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.70
      key: AE-140.70
      name: Social & Creator Commerce
      url: /capabilities/social-creator-commerce/
      via_parent: null
    credit: null
    layer: domain
    name: Shopify
    provider: shopify
    says: lists Shopify as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Snapchat
    provider: snapchat
    says: lists Snapchat as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: Tableau
    provider: tableau
    says: lists Tableau as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Threads
    provider: threads-api
    says: lists Threads as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: TikTok
    provider: tiktok
    says: lists TikTok as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: Tripadvisor
    provider: tripadvisor
    says: lists Tripadvisor as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: Trustpilot
    provider: trustpilot
    says: lists Trustpilot as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Tumblr
    provider: tumblr
    says: lists Tumblr as an integration
    source: https://sproutsocial.com/integrations/
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
    name: WhatsApp
    provider: whatsapp
    says: lists WhatsApp as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.70
      key: AE-140.70
      name: Social & Creator Commerce
      url: /capabilities/social-creator-commerce/
      via_parent: null
    credit: null
    layer: domain
    name: WooCommerce
    provider: woocommerce
    says: lists WooCommerce as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: X (Twitter)
    provider: x
    says: lists X (Twitter) as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: domain
    name: Yelp
    provider: yelp
    says: lists Yelp as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: YouTube
    provider: youtube
    says: lists YouTube as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: ''
      key: service-request-management
      name: Service Request Management
      url: null
      via_parent: null
    credit: null
    layer: common
    name: Zendesk
    provider: zendesk
    says: lists Zendesk as an integration
    source: https://sproutsocial.com/integrations/
    tier: declared
  kind: commercial
  name: Sprout Social
  page: /applications/social-media-management/sprout-social/
  slug: sprout-social
  url: https://sproutsocial.com/
- anchor: planoly
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.planoly.android/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: AB Tasty
    provider: ab-tasty
    says: ships the AB Tasty SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.planoly.android/latest/
    tier: observed
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.planoly.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.planoly.android/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.planoly.android/latest/
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
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.planoly.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: ships the Google Tag Manager SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.planoly.android/latest/
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
    name: New Relic
    provider: new-relic
    says: ships the New Relic SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.planoly.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Pangle
    provider: pangle
    says: ships the Pangle SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.planoly.android/latest/
    tier: observed
  kind: commercial
  name: Planoly
  page: /applications/social-media-management/planoly/
  slug: planoly
  url: https://www.planoly.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: social-media-management
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Social Networking
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Social
  store: google-play
  url: https://play.google.com/store/apps/category/SOCIAL
- category: Social Media
  store: hubspot-marketplace
  url: https://ecosystem.hubspot.com/marketplace/apps
- category: Marketing and conversion
  store: shopify-app-store
  url: https://apps.shopify.com/categories
- category: Social Media Marketing
  store: zapier
  url: https://zapier.com/apps
name: Social Media Management & Scheduling
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: domain
  why: 'the channels themselves: every app publishes to and reads from social networks (also hosts the social-listening gap rows)'
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.10
    key: AE-170.50.10
    name: Online Communities
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  fit: exact
  layer: domain
  why: community channels Postiz posts into (Discord, Skool, Whop, Dribbble)
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: domain
  why: messaging-app channels (WhatsApp, Telegram)
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  fit: exact
  layer: domain
  why: realtime updates (Pusher) and team chat channels (Slack, Teams)
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  fit: exact
  layer: domain
  why: video channels (YouTube, Twitch, Kick, Dailymotion)
- capability:
    attribution: API Evangelist extension
    id: AE-170.60
    key: AE-170.60
    name: News & Publishing
    url: /capabilities/news-publishing/
    via_parent: null
  fit: exact
  layer: domain
  why: long-form publishing channels (Medium, DEV, Hashnode, Substack)
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  fit: exact
  layer: domain
  why: blog CMS as a channel and as a source of evergreen posts
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.30
    key: AE-170.60.30
    name: Newsletters
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  fit: exact
  layer: domain
  why: newsletter channels (beehiiv, listmonk)
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  fit: exact
  layer: domain
  why: review and local-listing management (Google Business Profile, Yelp, Trustpilot, app stores)
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: object storage for uploaded media (nearest; no storage node)
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: common
  why: LLM copywriting and agent assistants
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.10
    key: AE-110.30.10
    name: Speech-to-Text
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  fit: exact
  layer: common
  why: captioning for video clips
- capability:
    attribution: API Evangelist extension
    id: AE-110.20.20
    key: AE-110.20.20
    name: Video Generation
    url: /capabilities/generative-media/
    via_parent: Generative Media
  fit: exact
  layer: domain
  why: AI video generation for short-form social video
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.20
    key: AE-230.40.20
    name: Web Search APIs
    url: /capabilities/web-data/
    via_parent: Web Data
  fit: exact
  layer: common
  why: web search for the AI agent
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: common
  why: social leads and contacts into the CRM
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: transactional email
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: domain
  why: link shortening / link-in-bio (gap) and mobile attribution (AppsFlyer)
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: subscription payments for the SaaS
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: exact
  layer: common
  why: App Store / Google Play subscriptions via RevenueCat
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: social / platform sign-in to the tool
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring / APM
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.10
    key: AE-170.30.10
    name: Image Processing & Optimisation
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: domain
  why: media upload and processing
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  fit: exact
  layer: domain
  why: design editors (Canva, Adobe Express, Polotno, Figma, Miro); no design node exists
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: app telemetry in the mobile apps
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: CAPTCHA on public preview comments
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: exact
  layer: domain
  why: stock photo / GIF pickers in the composer
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: SMS
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.10
    key: AE-170.60.10
    name: News Data
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  fit: exact
  layer: domain
  why: news feeds for content discovery
- capability:
    attribution: Turbo EA
    id: BC-3750.20
    key: subscription-entitlement-management
    name: Subscription & Entitlement Management
    url: /capabilities/subscription-entitlement-management/
    via_parent: null
  fit: nearest
  layer: common
  why: membership plans (aMember)
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: common
  why: content planning in work-management tools
- capability:
    attribution: Turbo EA
    id: BC-3780
    key: content-compliance-standards-management
    name: Content Compliance & Standards Management
    url: /capabilities/content-compliance-standards-management/
    via_parent: null
  fit: exact
  layer: domain
  why: post compliance review
- capability:
    attribution: API Evangelist extension
    id: AE-140.70
    key: AE-140.70
    name: Social & Creator Commerce
    url: /capabilities/social-creator-commerce/
    via_parent: null
  fit: exact
  layer: domain
  why: social commerce catalogs and creator partnerships
- capability:
    attribution: Turbo EA
    id: BC-420.40
    key: loyalty-retention-management
    name: Loyalty & Retention Management
    url: /capabilities/loyalty-retention-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: UGC and loyalty programs
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  fit: exact
  layer: domain
  why: DAM and cloud drives feeding the composer
- capability:
    attribution: Turbo EA
    id: BC-400.70
    key: content-marketing-management
    name: Content Marketing Management
    url: /capabilities/content-marketing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: content planning platforms exporting to the scheduler
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  fit: exact
  layer: domain
  why: video libraries shared to social (Vimeo, Brightcove, Vidyard)
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: push notifications
- capability:
    attribution: API Evangelist extension
    id: AE-905
    key: AE-905
    name: IDEs & AI Coding Assistants
    url: /capabilities/engineering-productivity-management/
    via_parent: Engineering Productivity Management
  fit: exact
  layer: agent
  why: Buffer automation from an AI code editor
- capability:
    attribution: Turbo EA
    id: BC-4010.70
    key: distribution-content-syndication
    name: Distribution Content Syndication
    url: /capabilities/distribution-content-syndication/
    via_parent: null
  fit: nearest
  layer: domain
  why: content curation feeds
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.20
    key: AE-170.30.20
    name: Photo Sharing
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: domain
  why: personal photo library as a media source
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: automation platforms that create posts from other apps
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  fit: exact
  layer: common
  why: feature flags in the mobile app
- capability:
    attribution: Turbo EA
    id: BC-400.50
    key: marketing-operations-management
    name: Marketing Operations Management
    url: /capabilities/marketing-operations-management/
    via_parent: null
  fit: exact
  layer: common
  why: marketing automation sync
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: common
  why: social analytics into BI
- capability:
    attribution: Turbo EA
    id: ''
    key: service-request-management
    name: Service Request Management
    url: null
    via_parent: null
  fit: exact
  layer: common
  why: social customer care into the help desk
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  fit: exact
  layer: common
  why: A/B testing in the mobile app
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: tag management
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: in-app ad SDK
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Buffer
      - Hootsuite
      - Mixpost
      - Planoly
      - Postiz
      - Socioboard
      - Sprout Social
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://buffer.com/integrations
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      - https://github.com/inovector/mixpost/tree/main/src/SocialProviders
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-native
      agent_readiness: 61.2
      apps:
      - Buffer
      - Hootsuite
      - Mixpost
      - Postiz
      - Socioboard
      - Sprout Social
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: X (Twitter)
      slug: x
      sources:
      - https://buffer.com/integrations
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      - https://github.com/inovector/mixpost/tree/main/src/SocialProviders
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: observed
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 47.4
      apps:
      - Buffer
      - Hootsuite
      - Postiz
      - Socioboard
      - Sprout Social
      band: exemplar
      in_catalog: true
      kin_score: 76.4
      mcp:
        status: none
      name: LinkedIn
      slug: linkedin
      sources:
      - https://buffer.com/integrations
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      - https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: observed
      url: /providers/linkedin/
    - agent_band: agent-ready
      agent_readiness: 38.9
      apps:
      - Buffer
      - Hootsuite
      - Postiz
      - Socioboard
      - Sprout Social
      band: exemplar
      in_catalog: true
      kin_score: 69.0
      mcp:
        status: none
      name: Instagram
      slug: instagram
      sources:
      - https://buffer.com/integrations
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      - https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
      status: profiled
      tags:
      - Instagram
      - Meta
      - Photos
      - Social Media
      tier: observed
      url: /providers/instagram/
    - agent_band: agent-ready
      agent_readiness: 38.4
      apps:
      - Buffer
      - Hootsuite
      - Postiz
      - Socioboard
      - Sprout Social
      band: developing
      in_catalog: true
      kin_score: 49.4
      mcp:
        source: https://developers.pinterest.com/about-pinterest-mcp/
        status: verified
      name: Pinterest
      slug: pinterest
      sources:
      - https://buffer.com/integrations
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      - https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
      status: profiled
      tags:
      - Image
      - Social
      - Social Media
      - Video
      tier: observed
      url: /providers/pinterest/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Buffer
      - Hootsuite
      - Postiz
      - Socioboard
      - Sprout Social
      band: developing
      in_catalog: true
      kin_score: 41.0
      mcp:
        status: none
      name: TikTok
      slug: tiktok
      sources:
      - https://buffer.com/integrations
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      - https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
      status: profiled
      tags:
      - Advertising
      - Commerce
      - Content
      - TikTok
      tier: observed
      url: /providers/tiktok/
    - agent_band: agent-aware
      agent_readiness: 26.2
      apps:
      - Buffer
      - Hootsuite
      - Postiz
      - Sprout Social
      band: developing
      in_catalog: true
      kin_score: 45.1
      mcp:
        status: none
      name: Bluesky
      slug: bluesky
      sources:
      - https://buffer.com/integrations
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - At-Protocol
      - Decentralized
      - Federated
      - Open Source
      tier: observed
      url: /providers/bluesky/
    - agent_band: agent-aware
      agent_readiness: 28.4
      apps:
      - Buffer
      - Hootsuite
      - Postiz
      - Sprout Social
      band: developing
      in_catalog: true
      kin_score: 43.1
      mcp:
        status: none
      name: Threads
      slug: threads-api
      sources:
      - https://buffer.com/integrations
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Meta
      - Publishing
      - Social
      - Social Network
      tier: observed
      url: /providers/threads-api/
    - agent_band: agent-aware
      agent_readiness: 22.5
      apps:
      - Buffer
      - Mixpost
      - Postiz
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: Mastodon
      slug: mastodon
      sources:
      - https://buffer.com/integrations
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      - https://github.com/inovector/mixpost/tree/main/src/SocialProviders
      status: profiled
      tags:
      - Open Source
      - Real-Time
      - Social
      - Social Network
      tier: observed
      url: /providers/mastodon/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Postiz
      - Socioboard
      - Sprout Social
      band: minimal
      in_catalog: true
      kin_score: 7.9
      mcp:
        status: none
      name: Tumblr
      slug: tumblr
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      - https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Public APIs
      - Social
      tier: observed
      url: /providers/tumblr/
    - agent_band: agent-ready
      agent_readiness: 39.1
      apps:
      - Postiz
      - Sprout Social
      band: strong
      in_catalog: true
      kin_score: 63.0
      mcp:
        source: https://github.com/reddit/devvit-mcp
        status: verified
      name: Reddit
      slug: reddit
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Advertising
      - Community
      - Content
      - Reddit
      tier: observed
      url: /providers/reddit/
    - agent_band: agent-native
      agent_readiness: 41.7
      apps:
      - Postiz
      band: thin
      in_catalog: true
      kin_score: 36.7
      mcp:
        status: none
      name: Neynar
      slug: neynar
      sources:
      - https://raw.githubusercontent.com/gitroomhq/postiz-app/main/package.json
      status: profiled
      tags:
      - Decentralized
      - Farcaster
      - Social
      - Web3
      tier: observed
      url: /providers/neynar/
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - Postiz
      band: thin
      in_catalog: true
      kin_score: 34.3
      mcp:
        status: none
      name: Lemmy
      slug: lemmy
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      status: profiled
      tags:
      - Community
      - Federated
      - Fediverse
      - Link Aggregator
      tier: observed
      url: /providers/lemmy/
    - agent_band: agent-aware
      agent_readiness: 18.4
      apps:
      - Postiz
      band: emerging
      in_catalog: true
      kin_score: 24.5
      mcp:
        status: none
      name: Farcaster
      slug: farcaster
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      status: profiled
      tags:
      - Decentralized
      - Farcaster
      - Protocol
      - Social
      tier: observed
      url: /providers/farcaster/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Postiz
      band: emerging
      in_catalog: true
      kin_score: 15.7
      mcp:
        status: unknown
      name: Moltbook
      slug: moltbook
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      status: profiled
      tags:
      - Artificial Intelligence
      - Community
      - Company
      - Social Network
      tier: observed
      url: /providers/moltbook/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Postiz
      band: minimal
      in_catalog: true
      kin_score: 10.8
      mcp:
        status: unknown
      name: MeWe
      slug: mewe
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      status: profiled
      tags:
      - Company
      - Networking
      - Privacy
      - Social
      tier: observed
      url: /providers/mewe/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Postiz
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        status: none
      name: VK
      slug: vk
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      status: profiled
      tags:
      - Public APIs
      - Social
      tier: observed
      url: /providers/vk/
    - agent_band: agent-ready
      agent_readiness: 48.1
      apps:
      - Sprout Social
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp:
        status: none
      name: Snapchat
      slug: snapchat
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Advertising
      - Augmented Reality
      - Marketing
      - Messaging
      tier: declared
      url: /providers/snapchat/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Buffer
      - Hootsuite
      - Postiz
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp:
        status: none
      name: Google Business Profile
      slug: google-business-profile
      sources:
      - https://buffer.com/integrations
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      - https://www.hootsuite.com/platform/integrations
      status: profiled
      tags:
      - Business Profiles
      - Google
      - Local Business
      - Location
      tier: observed
      url: /providers/google-business-profile/
    - agent_band: agent-native
      agent_readiness: 53.4
      apps:
      - Sprout Social
      band: strong
      in_catalog: true
      kin_score: 64.1
      mcp:
        source: https://github.com/Yelp/yelp-mcp
        status: verified
      name: Yelp
      slug: yelp
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Business Data
      - Local Search
      - Restaurant
      - Reviews
      tier: declared
      url: /providers/yelp/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Hootsuite
      band: strong
      in_catalog: true
      kin_score: 55.9
      mcp:
        status: none
      name: ReviewTrackers
      slug: reviewtrackers
      sources:
      - https://www.hootsuite.com/platform/integrations
      status: profiled
      tags:
      - Customer Feedback
      - Reputation Management
      - Review Monitoring
      - Sentiment Analytics
      tier: declared
      url: /providers/reviewtrackers/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Sprout Social
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp: &id001
        status: none
      name: Apple
      slug: apple
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags: &id002
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 21.7
      apps:
      - Sprout Social
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        status: none
      name: Trustpilot
      slug: trustpilot
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Consumer Reviews
      - Ratings
      - Reviews
      - Trust
      tier: declared
      url: /providers/trustpilot/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Sprout Social
      band: thin
      in_catalog: true
      kin_score: 37.5
      mcp:
        status: none
      name: Tripadvisor
      slug: tripadvisor
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Attractions
      - Hospitality
      - Hotels
      - Restaurant
      tier: declared
      url: /providers/tripadvisor/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Sprout Social
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        status: none
      name: Google Play (reviews)
      slug: google-play
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Android
      - Application
      - Google Play
      - In-App Purchases
      tier: declared
      url: /providers/google-play/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Sprout Social
      band: emerging
      in_catalog: true
      kin_score: 11.1
      mcp:
        status: none
      name: Glassdoor
      slug: glassdoor
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Employer Reviews
      - Job Search
      - Recruiting
      - Salaries
      tier: declared
      url: /providers/glassdoor/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 71.4
      apps:
      - Buffer
      - Hootsuite
      - Postiz
      - Sprout Social
      band: exemplar
      in_catalog: true
      kin_score: 79.9
      mcp:
        source: https://www.canva.dev/docs/mcp/
        status: verified
      name: Canva
      slug: canva
      sources:
      - https://buffer.com/integrations
      - https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Application
      - Automation
      - Brand Management
      - Collaboration
      tier: observed
      url: /providers/canva/
    - agent_band: null
      agent_readiness: null
      apps:
      - Hootsuite
      - Sprout Social
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Adobe Express
      slug: adobe-express
      sources:
      - https://sproutsocial.com/integrations/
      - https://www.hootsuite.com/platform/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: agent-aware
      agent_readiness: 18.0
      apps:
      - Postiz
      band: emerging
      in_catalog: true
      kin_score: 16.8
      mcp:
        source: https://polotno.com/docs/build-with-ai
        status: documented
      name: Polotno
      slug: polotno
      sources:
      - https://raw.githubusercontent.com/gitroomhq/postiz-app/main/package.json
      status: profiled
      tags:
      - Canvas
      - Company
      - Design Tools
      - Open Source
      tier: observed
      url: /providers/polotno/
    - agent_band: agent-ready
      agent_readiness: 57.8
      apps:
      - Hootsuite
      band: strong
      in_catalog: true
      kin_score: 65.6
      mcp:
        source: https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server
        status: verified
      name: Figma
      slug: figma
      sources:
      - https://apps.hootsuite.com/
      status: profiled
      tags:
      - Collaboration
      - Design
      - Graphics
      - Interfaces
      tier: declared
      url: /providers/figma/
    - agent_band: agent-ready
      agent_readiness: 39.1
      apps:
      - Hootsuite
      band: developing
      in_catalog: true
      kin_score: 46.4
      mcp:
        source: https://developers.miro.com/docs/miro-mcp
        status: verified
      name: Miro
      slug: miro
      sources:
      - https://apps.hootsuite.com/
      status: profiled
      tags:
      - Diagramming
      - Productivity
      - Visual Collaboration
      - Whiteboard
      tier: declared
      url: /providers/miro/
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.4
      apps:
      - Buffer
      - Socioboard
      - Sprout Social
      band: exemplar
      in_catalog: true
      kin_score: 73.7
      mcp:
        source: https://dev.bitly.com/bitly-mcp/
        status: verified
      name: Bitly
      slug: bitly
      sources:
      - https://buffer.com/integrations
      - https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Links
      - QR Codes
      - URL Shorteners
      tier: observed
      url: /providers/bitly/
    - agent_band: agent-aware
      agent_readiness: 23.0
      apps:
      - Postiz
      band: strong
      in_catalog: true
      kin_score: 59.7
      mcp:
        source: https://dub.co/docs/mcp-server.md
        status: verified
      name: Dub
      slug: dub
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Link Management
      - URL Shorteners
      tier: observed
      url: /providers/dub/
    - agent_band: agent-aware
      agent_readiness: 28.0
      apps:
      - Postiz
      band: developing
      in_catalog: true
      kin_score: 50.6
      mcp:
        source: https://docs.short.io/articles/integrations-and-extensions/direct-integrations/how-to-integrate-and-use-short.io-with-your-mcp-enabled-service.md
        status: verified
      name: Short.io
      slug: short-io
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
      status: profiled
      tags:
      - Analytics
      - Enterprise
      - QR Codes
      - URL-shortening
      tier: observed
      url: /providers/short-io/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Postiz
      band: emerging
      in_catalog: true
      kin_score: 12.3
      mcp:
        status: unknown
      name: LinkDrip
      slug: linkdrip
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
      status: profiled
      tags:
      - Analytics
      - Link Management
      - Marketing
      - No-Code
      tier: observed
      url: /providers/linkdrip/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Socioboard
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        status: none
      name: TinyURL
      slug: tinyurl
      sources:
      - https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
      status: profiled
      tags:
      - Public APIs
      - URL Shorteners
      tier: observed
      url: /providers/tinyurl/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Postiz
      band: minimal
      in_catalog: true
      kin_score: 3.3
      mcp:
        status: none
      name: Kutt
      slug: kutt
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
      status: profiled
      tags:
      - Public APIs
      - URL Shorteners
      tier: observed
      url: /providers/kutt/
    - agent_band: null
      agent_readiness: null
      apps:
      - Hootsuite
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: OneClick.bio
      slug: oneclick-bio
      sources:
      - https://www.hootsuite.com/platform/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.4
      apps:
      - Buffer
      - Hootsuite
      - Postiz
      - Socioboard
      - Sprout Social
      band: strong
      in_catalog: true
      kin_score: 62.6
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://buffer.com/integrations
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      - https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: observed
      url: /providers/youtube/
    - agent_band: agent-ready
      agent_readiness: 32.2
      apps:
      - Postiz
      band: developing
      in_catalog: true
      kin_score: 50.5
      mcp:
        status: none
      name: Twitch
      slug: twitch
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      status: profiled
      tags:
      - Entertainment
      - Gaming
      - Live Streaming
      - Streaming
      tier: observed
      url: /providers/twitch/
    - agent_band: human-only
      agent_readiness: 4.5
      apps:
      - Postiz
      band: emerging
      in_catalog: true
      kin_score: 15.8
      mcp:
        status: unknown
      name: Kick (kick.com)
      slug: kick-com
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      status: profiled
      tags:
      - Company
      - Live
      - Streaming
      - Video
      tier: observed
      url: /providers/kick-com/
    - agent_band: human-only
      agent_readiness: 3.9
      apps:
      - Socioboard
      band: minimal
      in_catalog: true
      kin_score: 8.4
      mcp:
        status: none
      name: Dailymotion
      slug: dailymotion
      sources:
      - https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster/trends.cluster.js
      status: profiled
      tags:
      - Public APIs
      - Video
      tier: observed
      url: /providers/dailymotion/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Buffer
      - Mixpost
      band: developing
      in_catalog: true
      kin_score: 40.2
      mcp:
        status: none
      name: Unsplash
      slug: unsplash
      sources:
      - https://buffer.com/integrations
      - https://github.com/inovector/mixpost/tree/main/src/Services
      status: profiled
      tags:
      - Image
      - Photography
      - Photos
      - Stock Photos
      tier: observed
      url: /providers/unsplash/
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Socioboard
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        status: none
      name: GIPHY
      slug: giphy
      sources:
      - https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster/trends.cluster.js
      status: profiled
      tags:
      - GIFs
      - Media
      - Photography
      - Stickers
      tier: observed
      url: /providers/giphy/
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - Socioboard
      band: developing
      in_catalog: true
      kin_score: 48.6
      mcp:
        status: none
      name: Flickr
      slug: flickr
      sources:
      - https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster/trends.cluster.js
      status: profiled
      tags:
      - Photography
      - Photos
      - Public APIs
      - Social Media
      tier: observed
      url: /providers/flickr/
    - agent_band: agent-aware
      agent_readiness: 21.2
      apps:
      - Socioboard
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        status: none
      name: Imgur
      slug: imgur
      sources:
      - https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster/trends.cluster.js
      status: profiled
      tags:
      - Albums
      - Image
      - Image Hosting
      - Photography
      tier: observed
      url: /providers/imgur/
    - agent_band: agent-aware
      agent_readiness: 24.0
      apps:
      - Mixpost
      band: thin
      in_catalog: true
      kin_score: 35.8
      mcp:
        status: none
      name: Tenor
      slug: tenor
      sources:
      - https://github.com/inovector/mixpost/tree/main/src/Services
      status: profiled
      tags:
      - Animated Images
      - GIFs
      - Media
      - Search
      tier: observed
      url: /providers/tenor/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Socioboard
      band: emerging
      in_catalog: true
      kin_score: 13.8
      mcp:
        status: none
      name: Pixabay
      slug: pixabay
      sources:
      - https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster/trends.cluster.js
      status: profiled
      tags:
      - Illustrations
      - Image
      - Stock Media
      - Video
      tier: observed
      url: /providers/pixabay/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - Buffer
      - Hootsuite
      - Postiz
      band: developing
      in_catalog: true
      kin_score: 46.0
      mcp:
        source: https://github.com/WordPress/mcp-adapter
        status: verified
      name: WordPress
      slug: wordpress
      sources:
      - https://apps.hootsuite.com/
      - https://buffer.com/integrations
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      status: profiled
      tags:
      - CMS
      - Content Management
      - Open Source
      - WordPress
      tier: observed
      url: /providers/wordpress/
    - agent_band: agent-ready
      agent_readiness: 39.1
      apps:
      - Buffer
      band: thin
      in_catalog: true
      kin_score: 35.1
      mcp:
        source: https://www.writestack.io/mcp
        status: verified
      name: WriteStack
      slug: writestack
      sources:
      - https://buffer.com/integrations
      status: profiled
      tags:
      - Analytics
      - Company
      - Growth
      - Substack
      tier: declared
      url: /providers/writestack/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Buffer
      band: emerging
      in_catalog: true
      kin_score: 16.6
      mcp:
        status: unknown
      name: Evergreen Content Poster
      slug: evergreen-content-poster
      sources:
      - https://buffer.com/integrations
      status: profiled
      tags:
      - Company
      - ESG
      - Employee Recognition
      - Software-as-a-Service
      tier: declared
      url: /providers/evergreen-content-poster/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Buffer
      band: minimal
      in_catalog: true
      kin_score: 1.3
      mcp:
        status: unknown
      name: Nelio Content
      slug: nelio-content
      sources:
      - https://buffer.com/integrations
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/nelio-content/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.3
      apps:
      - Buffer
      - Sprout Social
      band: exemplar
      in_catalog: true
      kin_score: 67.1
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://buffer.com/integrations
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: declared
      url: /providers/google-drive/
    - agent_band: agent-ready
      agent_readiness: 45.8
      apps:
      - Buffer
      - Sprout Social
      band: developing
      in_catalog: true
      kin_score: 47.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://buffer.com/integrations
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: declared
      url: /providers/dropbox/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Buffer
      band: developing
      in_catalog: true
      kin_score: 48.3
      mcp:
        status: none
      name: Microsoft OneDrive
      slug: microsoft-onedrive
      sources:
      - https://buffer.com/integrations
      status: profiled
      tags:
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: declared
      url: /providers/microsoft-onedrive/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60
      key: AE-170.60
      name: News & Publishing
      url: /capabilities/news-publishing/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.0
      apps:
      - Postiz
      - Socioboard
      band: thin
      in_catalog: true
      kin_score: 36.2
      mcp:
        status: none
      name: Medium
      slug: medium
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      - https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
      status: profiled
      tags:
      - Blogging
      - Content
      - Media
      - Publishing
      tier: observed
      url: /providers/medium/
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - Postiz
      band: strong
      in_catalog: true
      kin_score: 56.7
      mcp:
        status: none
      name: DEV Community
      slug: dev-to
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      status: profiled
      tags:
      - Content
      - Developer Community
      - Publishing
      - Social
      tier: observed
      url: /providers/dev-to/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Postiz
      band: strong
      in_catalog: true
      kin_score: 56.5
      mcp:
        status: none
      name: Hashnode
      slug: hashnode
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      status: profiled
      tags:
      - Blogging
      - Content Management
      - Developer Platform
      - GraphQL
      tier: observed
      url: /providers/hashnode/
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - Buffer
      band: developing
      in_catalog: true
      kin_score: 43.6
      mcp:
        source: https://mcp.substack.com/api/v1/mcp
        status: verified
      name: Substack
      slug: substack
      sources:
      - https://buffer.com/integrations
      status: profiled
      tags:
      - Creator Economy
      - Newsletters
      - Publishing
      - Subscription
      tier: declared
      url: /providers/substack/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.10
      key: AE-170.50.10
      name: Online Communities
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Hootsuite
      - Postiz
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        status: none
      name: Dribbble
      slug: dribbble
      sources:
      - https://apps.hootsuite.com/
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      status: profiled
      tags:
      - Design
      - Public APIs
      tier: observed
      url: /providers/dribbble/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Postiz
      band: developing
      in_catalog: true
      kin_score: 46.9
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Postiz
      band: emerging
      in_catalog: true
      kin_score: 25.4
      mcp:
        source: https://github.com/whopio/whop-mcp-server
        status: verified
      name: Whop
      slug: whop
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      status: profiled
      tags:
      - Checkout
      - Creator Economy
      - Membership
      - Payments
      tier: observed
      url: /providers/whop/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Postiz
      band: minimal
      in_catalog: true
      kin_score: 7.3
      mcp:
        status: none
      name: Skool
      slug: skool
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      status: profiled
      tags:
      - Community
      - Courses
      - E-Learning
      - Membership
      tier: observed
      url: /providers/skool/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Hootsuite
      - Postiz
      - Sprout Social
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      - https://sproutsocial.com/integrations/
      - https://www.hootsuite.com/platform/integrations
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 34.2
      apps:
      - Sprout Social
      band: strong
      in_catalog: true
      kin_score: 59.0
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://sproutsocial.com/integrations/
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
      id: AE-110.20.20
      key: AE-110.20.20
      name: Video Generation
      url: /capabilities/generative-media/
      via_parent: Generative Media
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.8
      apps:
      - Postiz
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        source: https://developers.heygen.com/mcp/overview.md
        status: verified
      name: HeyGen
      slug: heygen
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
      status: profiled
      tags:
      - Artificial Intelligence
      - Avatars
      - Generative AI
      - Video
      tier: observed
      url: /providers/heygen/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Postiz
      band: minimal
      in_catalog: true
      kin_score: 9.9
      mcp:
        status: unknown
      name: ReelFarm
      slug: reelfarm
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
      status: profiled
      tags:
      - Artificial Intelligence
      - Automation
      - Company
      - TikTok
      tier: observed
      url: /providers/reelfarm/
    - agent_band: null
      agent_readiness: null
      apps:
      - Postiz
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: EvoLink (Seedance)
      slug: evolink
      sources:
      - https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 43.9
      apps:
      - Hootsuite
      band: thin
      in_catalog: true
      kin_score: 29.8
      mcp:
        status: none
      name: Lumen5
      slug: lumen5
      sources:
      - https://www.hootsuite.com/platform/integrations
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/lumen5/
  - capability:
      attribution: Turbo EA
      id: BC-400.70
      key: content-marketing-management
      name: Content Marketing Management
      url: /capabilities/content-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.9
      apps:
      - Sprout Social
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        source: https://support.optimizely.com/hc/en-us/articles/45320607594893
        status: documented
      name: Optimizely
      slug: optimizely
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - A/B Testing
      - Content Management
      - Customer Data
      - E-Commerce
      tier: declared
      url: /providers/optimizely/
    - agent_band: agent-ready
      agent_readiness: 62.7
      apps:
      - Hootsuite
      band: exemplar
      in_catalog: true
      kin_score: 75.5
      mcp:
        status: none
      name: Acquia
      slug: acquia
      sources:
      - https://www.hootsuite.com/platform/integrations
      status: profiled
      tags:
      - Content
      - DXP
      - Drupal
      - Experience
      tier: declared
      url: /providers/acquia/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Sprout Social
      band: developing
      in_catalog: true
      kin_score: 51.5
      mcp:
        source: https://github.com/opalsecurity/opal-mcp
        status: verified
      name: Opal
      slug: opal
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Company
      - Consumer
      - Content Planning
      - Marketing
      tier: declared
      url: /providers/opal/
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
      - Hootsuite
      - Sprout Social
      band: exemplar
      in_catalog: true
      kin_score: 67.6
      mcp:
        status: none
      name: Bynder
      slug: bynder
      sources:
      - https://sproutsocial.com/integrations/
      - https://www.hootsuite.com/platform/integrations
      status: profiled
      tags:
      - Brand Management
      - Content Management
      - Digital Asset Management
      - Marketing
      tier: declared
      url: /providers/bynder/
    - agent_band: agent-aware
      agent_readiness: 21.8
      apps:
      - Sprout Social
      band: thin
      in_catalog: true
      kin_score: 28.6
      mcp:
        source: https://github.com/adobe/cq-quickstart-mcp-server
        status: verified
      name: Adobe Experience Manager
      slug: adobe-experience-manager
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Content Management
      - Digital Asset Management
      - Enterprise CMS
      - Headless CMS
      tier: declared
      url: /providers/adobe-experience-manager/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.70
      key: AE-140.70
      name: Social & Creator Commerce
      url: /capabilities/social-creator-commerce/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.5
      apps:
      - Sprout Social
      band: exemplar
      in_catalog: true
      kin_score: 84.6
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify
      slug: shopify
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: declared
      url: /providers/shopify/
    - agent_band: agent-ready
      agent_readiness: 35.4
      apps:
      - Sprout Social
      band: developing
      in_catalog: true
      kin_score: 50.4
      mcp:
        source: https://developer.woocommerce.com/docs/features/mcp/
        status: verified
      name: WooCommerce
      slug: woocommerce
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - E-Commerce
      - Open Source
      - Order
      - WooCommerce
      tier: declared
      url: /providers/woocommerce/
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - Hootsuite
      band: emerging
      in_catalog: true
      kin_score: 20.2
      mcp:
        status: none
      name: Upfluence
      slug: upfluence
      sources:
      - https://www.hootsuite.com/platform/integrations
      status: profiled
      tags:
      - Company
      - Influencer Marketing
      - MCP
      - Software-as-a-Service
      tier: declared
      url: /providers/upfluence/
  - capability:
      attribution: API Evangelist extension
      id: AE-914
      key: AE-914
      name: Social Listening & Analytics
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.3
      apps:
      - Hootsuite
      band: strong
      in_catalog: true
      kin_score: 54.8
      mcp:
        status: none
      name: Talkwalker
      slug: talkwalker
      sources:
      - https://apps.hootsuite.com/
      status: profiled
      tags:
      - Brand Monitoring
      - Sentiment Analysis
      - Social Listening
      - Social Media Analytics
      tier: declared
      url: /providers/talkwalker/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - Hootsuite
      band: minimal
      in_catalog: true
      kin_score: 6.8
      mcp:
        source: https://mcp.fedica.com/.well-known/oauth-protected-resource/mcp
        status: verified
      name: Fedica
      slug: fedica
      sources:
      - https://www.hootsuite.com/platform/integrations
      status: profiled
      tags:
      - Analytics
      - Company
      - Marketing
      - Social Media
      tier: declared
      url: /providers/fedica/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Hootsuite
      band: minimal
      in_catalog: true
      kin_score: 2.2
      mcp:
        status: unknown
      name: Panoramiq Insights
      slug: panoramiq
      sources:
      - https://www.hootsuite.com/platform/integrations
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/panoramiq/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.6
      apps:
      - Hootsuite
      band: exemplar
      in_catalog: true
      kin_score: 71.1
      mcp:
        status: none
      name: Vidyard
      slug: vidyard
      sources:
      - https://www.hootsuite.com/platform/integrations
      status: profiled
      tags:
      - Video
      - Video Analytics
      - Video Platform
      - Video Sharing
      tier: declared
      url: /providers/vidyard/
    - agent_band: agent-ready
      agent_readiness: 48.8
      apps:
      - Hootsuite
      band: thin
      in_catalog: true
      kin_score: 38.4
      mcp:
        source: https://developer.vimeo.com/api/mcp-server
        status: documented
      name: Vimeo
      slug: vimeo
      sources:
      - https://apps.hootsuite.com/
      status: profiled
      tags:
      - Live Streaming
      - Streaming
      - Video
      - Video Hosting
      tier: declared
      url: /providers/vimeo/
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Hootsuite
      band: thin
      in_catalog: true
      kin_score: 35.0
      mcp:
        status: none
      name: Brightcove
      slug: brightcove
      sources:
      - https://apps.hootsuite.com/
      status: profiled
      tags:
      - Live Streaming
      - Media
      - Streaming
      - Video
      tier: declared
      url: /providers/brightcove/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.0
      apps:
      - Hootsuite
      - Sprout Social
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: WhatsApp
      slug: whatsapp
      sources:
      - https://sproutsocial.com/integrations/
      - https://www.hootsuite.com/platform/integrations
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: declared
      url: /providers/whatsapp/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Postiz
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
  - capability:
      attribution: Turbo EA
      id: BC-4010.70
      key: distribution-content-syndication
      name: Distribution Content Syndication
      url: /capabilities/distribution-content-syndication/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 65.3
      apps:
      - Buffer
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        status: none
      name: Feedly
      slug: feedly
      sources:
      - https://buffer.com/integrations
      status: profiled
      tags:
      - Content Aggregation
      - Cybersecurity
      - RSS
      - Threat Intelligence
      tier: declared
      url: /providers/feedly/
    - agent_band: human-only
      agent_readiness: 3.9
      apps:
      - Buffer
      band: emerging
      in_catalog: true
      kin_score: 12.2
      mcp:
        status: unknown
      name: Quuu
      slug: quuu
      sources:
      - https://buffer.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Automation
      - Company
      - Social Media
      tier: declared
      url: /providers/quuu/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.10
      key: AE-170.30.10
      name: Image Processing & Optimisation
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-aware
      agent_readiness: 13.7
      apps:
      - Postiz
      band: emerging
      in_catalog: true
      kin_score: 25.5
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=transloadit
        status: verified
      name: Transloadit
      slug: transloadit
      sources:
      - https://raw.githubusercontent.com/gitroomhq/postiz-app/main/package.json
      status: profiled
      tags:
      - File Processing
      - Image Resizing
      - Media Encoding
      - Video Transcoding
      tier: observed
      url: /providers/transloadit/
    - agent_band: agent-ready
      agent_readiness: 45.0
      apps:
      - Hootsuite
      band: developing
      in_catalog: true
      kin_score: 52.4
      mcp:
        source: https://cloudinary.com/documentation/cloudinary_llm_mcp
        status: verified
      name: Cloudinary
      slug: cloudinary
      sources:
      - https://apps.hootsuite.com/
      status: profiled
      tags:
      - Asset Management
      - Digital Asset Management
      - Image Processing
      - Image Transformation
      tier: declared
      url: /providers/cloudinary/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.30
      key: AE-170.60.30
      name: Newsletters
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.5
      apps:
      - Postiz
      band: exemplar
      in_catalog: true
      kin_score: 73.7
      mcp:
        source: https://github.com/beehiiv/agents
        status: verified
      name: beehiiv
      slug: beehiiv
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
      status: profiled
      tags:
      - Creators
      - Email
      - Newsletters
      - Subscription
      tier: observed
      url: /providers/beehiiv/
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - Postiz
      band: developing
      in_catalog: true
      kin_score: 47.2
      mcp:
        status: none
      name: listmonk
      slug: listmonk
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src/integrations/social
      status: profiled
      tags:
      - Email
      - Mailing List
      - Marketing
      - Newsletters
      tier: observed
      url: /providers/listmonk/
  - capability:
      attribution: Turbo EA
      id: BC-3780
      key: content-compliance-standards-management
      name: Content Compliance & Standards Management
      url: /capabilities/content-compliance-standards-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 7.9
      apps:
      - Hootsuite
      band: developing
      in_catalog: true
      kin_score: 40.1
      mcp:
        status: none
      name: Proofpoint
      slug: proofpoint
      sources:
      - https://www.hootsuite.com/platform/integrations
      status: profiled
      tags:
      - Cybersecurity
      - Email Security
      - Security
      - Threat Intelligence
      tier: declared
      url: /providers/proofpoint/
  - capability:
      attribution: Turbo EA
      id: BC-420.40
      key: loyalty-retention-management
      name: Loyalty & Retention Management
      url: /capabilities/loyalty-retention-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Hootsuite
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        source: https://www.trueloyal.com/mcp
        status: documented
      name: TrueLoyal
      slug: trueloyal
      sources:
      - https://www.hootsuite.com/platform/integrations
      status: profiled
      tags:
      - Loyalty
      - Platform
      - Retail
      - Software-as-a-Service
      tier: declared
      url: /providers/trueloyal/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.10
      key: AE-170.60.10
      name: News Data
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.2
      apps:
      - Socioboard
      band: thin
      in_catalog: true
      kin_score: 35.4
      mcp:
        status: none
      name: NewsAPI
      slug: newsapi
      sources:
      - https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/socioboard-api/Common/package.json
      status: profiled
      tags:
      - Articles
      - Headlines
      - News
      - Search
      tier: observed
      url: /providers/newsapi/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.20
      key: AE-170.30.20
      name: Photo Sharing
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Buffer
      band: thin
      in_catalog: true
      kin_score: 33.3
      mcp:
        status: none
      name: Google Photos
      slug: google-photos
      sources:
      - https://buffer.com/integrations
      status: profiled
      tags:
      - Albums
      - Google
      - Image
      - Media
      tier: declared
      url: /providers/google-photos/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Hootsuite
      - Planoly
      - Sprout Social
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.planoly.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.sproutsocial.android/latest/
      status: profiled
      tags:
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - Planoly
      - Sprout Social
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.planoly.android/latest/
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 48.3
      apps:
      - Hootsuite
      - Sprout Social
      band: strong
      in_catalog: true
      kin_score: 60.3
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.sproutsocial.android/latest/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
    - agent_band: agent-aware
      agent_readiness: 23.1
      apps:
      - Postiz
      band: strong
      in_catalog: true
      kin_score: 63.4
      mcp:
        status: none
      name: Plausible
      slug: plausible
      sources:
      - https://raw.githubusercontent.com/gitroomhq/postiz-app/main/package.json
      status: profiled
      tags:
      - Analytics
      - Cookie-Free
      - Event Tracking
      - GDPR
      tier: observed
      url: /providers/plausible/
    - agent_band: agent-ready
      agent_readiness: 35.4
      apps:
      - Hootsuite
      band: strong
      in_catalog: true
      kin_score: 56.4
      mcp:
        source: https://support.pendo.io/hc/en-us/articles/41102236924955
        status: verified
      name: Pendo
      slug: pendoio
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
      status: profiled
      tags:
      - Company
      - Digital Adoption
      - Product Analytics
      - Product Experience
      tier: observed
      url: /providers/pendoio/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Buffer
      band: developing
      in_catalog: true
      kin_score: 43.8
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/org.buffer.android/latest/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Hootsuite
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp:
        status: none
      name: Wootric
      slug: wootric
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
      status: profiled
      tags:
      - CES
      - CSAT
      - Customer Experience
      - NPS
      tier: observed
      url: /providers/wootric/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.7
      apps:
      - Postiz
      - Sprout Social
      band: exemplar
      in_catalog: true
      kin_score: 94.6
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: observed
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 54.7
      apps:
      - Hootsuite
      - Sprout Social
      band: exemplar
      in_catalog: true
      kin_score: 90.6
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://sproutsocial.com/integrations/
      - https://www.hootsuite.com/platform/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Sprout Social
      band: strong
      in_catalog: true
      kin_score: 63.9
      mcp:
        source: https://github.com/microsoft/Dataverse-MCP
        status: verified
      name: Microsoft Dynamics 365
      slug: microsoft-dynamics-365
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Business Applications
      - CRM
      - Cloud
      - Enterprise
      tier: declared
      url: /providers/microsoft-dynamics-365/
    - agent_band: agent-aware
      agent_readiness: 26.1
      apps:
      - Sprout Social
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce Agentforce Sales (Sales Cloud)
      slug: salesforce-sales-cloud
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - CRM
      - Cloud
      - Customer Management
      - Enterprise
      tier: declared
      url: /providers/salesforce-sales-cloud/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.2
      apps:
      - Buffer
      band: exemplar
      in_catalog: true
      kin_score: 72.0
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://buffer.com/integrations
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 36.4
      apps:
      - Buffer
      band: exemplar
      in_catalog: true
      kin_score: 71.3
      mcp:
        source: https://docs.n8n.io/advanced-ai/accessing-n8n-mcp-server/
        status: verified
      name: n8n
      slug: n8n
      sources:
      - https://buffer.com/integrations
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Integration
      - Workflows
      tier: declared
      url: /providers/n8n/
    - agent_band: agent-ready
      agent_readiness: 34.2
      apps:
      - Buffer
      band: strong
      in_catalog: true
      kin_score: 64.2
      mcp:
        status: none
      name: Microsoft Power Automate
      slug: microsoft-power-automate
      sources:
      - https://buffer.com/integrations
      status: profiled
      tags:
      - Automation
      - Business Process
      - Integration
      - Low-Code
      tier: declared
      url: /providers/microsoft-power-automate/
    - agent_band: agent-ready
      agent_readiness: 43.9
      apps:
      - Buffer
      band: developing
      in_catalog: true
      kin_score: 43.5
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://buffer.com/integrations
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
    - agent_band: agent-aware
      agent_readiness: 13.6
      apps:
      - Buffer
      band: emerging
      in_catalog: true
      kin_score: 25.7
      mcp:
        status: none
      name: Raycast
      slug: raycast
      sources:
      - https://buffer.com/integrations
      status: profiled
      tags:
      - Extensions
      - Launcher
      - Productivity
      - SDK
      tier: declared
      url: /providers/raycast/
    - agent_band: agent-ready
      agent_readiness: 43.3
      apps:
      - Buffer
      band: emerging
      in_catalog: true
      kin_score: 25.0
      mcp:
        source: https://github.com/IFTTT/ifttt-plugins
        status: verified
      name: IFTTT
      slug: ifttt
      sources:
      - https://buffer.com/integrations
      status: profiled
      tags:
      - Automation
      - No-Code
      - Webhook
      - iPaaS
      tier: declared
      url: /providers/ifttt/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-native
      agent_readiness: 58.4
      apps:
      - Buffer
      - Postiz
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://buffer.com/integrations
      - https://raw.githubusercontent.com/gitroomhq/postiz-app/main/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 31.6
      apps:
      - Postiz
      band: developing
      in_catalog: true
      kin_score: 53.7
      mcp:
        source: https://github.com/runpod/runpod-mcp
        status: verified
      name: RunPod
      slug: runpod
      sources:
      - https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Cloud
      - Compute
      - GPU
      tier: observed
      url: /providers/runpod/
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Buffer
      band: exemplar
      in_catalog: true
      kin_score: 87.5
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic (Claude)
      slug: anthropic
      sources:
      - https://buffer.com/integrations
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: declared
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 67.7
      apps:
      - Buffer
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp:
        source: https://github.com/perplexityai/modelcontextprotocol
        status: verified
      name: Perplexity
      slug: perplexity
      sources:
      - https://buffer.com/integrations
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - LLM
      - Search
      tier: declared
      url: /providers/perplexity/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 63.4
      apps:
      - Postiz
      - Socioboard
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
      - https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/docker/.env.example
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Postiz
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp: *id001
      name: Apple
      slug: apple
      sources:
      - https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Socioboard
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/docker/.env.example
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
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
      - Buffer
      - Postiz
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/gitroomhq/postiz-app/main/package.json
      - https://reports.exodus-privacy.eu.org/en/reports/org.buffer.android/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 45.7
      apps:
      - Planoly
      band: exemplar
      in_catalog: true
      kin_score: 76.5
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.planoly.android/latest/
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
  - capability:
      attribution: Turbo EA
      id: BC-400.50
      key: marketing-operations-management
      name: Marketing Operations Management
      url: /capabilities/marketing-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Sprout Social
      band: exemplar
      in_catalog: true
      kin_score: 80.5
      mcp:
        status: none
      name: Salesforce Agentforce Marketing / Marketing Intelligence
      slug: salesforce-marketing-cloud
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Automation
      - Content Management
      - Customer Journey
      - Digital Marketing
      tier: declared
      url: /providers/salesforce-marketing-cloud/
    - agent_band: agent-ready
      agent_readiness: 31.1
      apps:
      - Sprout Social
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        status: none
      name: Marketo
      slug: marketo
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Adobe
      - Automation
      - Marketing
      - Marketing Automation
      tier: declared
      url: /providers/marketo/
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Hootsuite
      band: developing
      in_catalog: true
      kin_score: 52.6
      mcp:
        source: https://github.com/wrike/datahub-mcp
        status: verified
      name: Wrike
      slug: wrike
      sources:
      - https://www.hootsuite.com/platform/integrations
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: declared
      url: /providers/wrike/
    - agent_band: agent-ready
      agent_readiness: 50.3
      apps:
      - Hootsuite
      band: thin
      in_catalog: true
      kin_score: 33.6
      mcp:
        source: https://github.com/mondaycom/mcp
        status: verified
      name: monday.com
      slug: monday-com
      sources:
      - https://www.hootsuite.com/platform/integrations
      status: profiled
      tags:
      - Automation
      - CRM
      - GraphQL
      - Work Management
      tier: declared
      url: /providers/monday-com/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Buffer
      - Hootsuite
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        status: none
      name: Pusher
      slug: pusher
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/org.buffer.android/latest/
      status: profiled
      tags:
      - Pub/Sub
      - Push Notifications
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/pusher/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - Socioboard
      band: exemplar
      in_catalog: true
      kin_score: 87.3
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/socioboard-api/Common/package.json
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-ready
      agent_readiness: 49.4
      apps:
      - Postiz
      band: strong
      in_catalog: true
      kin_score: 58.9
      mcp:
        source: https://resend.com/docs/mcp-server
        status: verified
      name: Resend
      slug: resend
      sources:
      - https://github.com/gitroomhq/postiz-app/tree/main/libraries/nestjs-libraries/src
      status: profiled
      tags:
      - Developer Tools
      - Email
      - Marketing Email
      - Transactional Email
      tier: observed
      url: /providers/resend/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.3
      apps:
      - Sprout Social
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp:
        source: https://github.com/tableau/tableau-mcp
        status: verified
      name: Tableau
      slug: tableau
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Business Intelligence
      - Dashboards
      - Data Visualization
      tier: declared
      url: /providers/tableau/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Postiz
      band: developing
      in_catalog: true
      kin_score: 48.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: observed
      url: /providers/google-recaptcha/
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Buffer
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        status: none
      name: Split
      slug: split
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/org.buffer.android/latest/
      status: profiled
      tags:
      - Experimentation
      - Feature Flags
      - Feature Management
      - Rollouts
      tier: observed
      url: /providers/split/
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Planoly
      band: minimal
      in_catalog: true
      kin_score: 8.4
      mcp:
        status: none
      name: Pangle
      slug: pangle
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.planoly.android/latest/
      status: profiled
      tags:
      - Advertising
      - Mobile
      - Monetization
      - TikTok
      tier: observed
      url: /providers/pangle/
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Postiz
      band: thin
      in_catalog: true
      kin_score: 27.7
      mcp:
        source: https://www.revenuecat.com/docs/tools/mcp
        status: verified
      name: RevenueCat
      slug: revenuecat
      sources:
      - https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
      status: profiled
      tags:
      - Billing
      - In-App Purchases
      - Mobile
      - Subscription
      tier: observed
      url: /providers/revenuecat/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - Planoly
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.planoly.android/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - Postiz
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.4
      apps:
      - Planoly
      band: developing
      in_catalog: true
      kin_score: 41.2
      mcp:
        source: https://github.com/flagship-io/mcp-server
        status: verified
      name: AB Tasty
      slug: ab-tasty
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.planoly.android/latest/
      status: profiled
      tags:
      - Aggregation
      - Experimentation
      - Feature Flags
      - Personalization
      tier: observed
      url: /providers/ab-tasty/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Hootsuite
      band: thin
      in_catalog: true
      kin_score: 27.9
      mcp:
        source: https://github.com/urbanairship/agent-tools
        status: verified
      name: Airship (Urban Airship)
      slug: airship
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
      status: profiled
      tags:
      - Email
      - Mobile
      - Notification
      - Push
      tier: observed
      url: /providers/airship/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-native
      agent_readiness: 56.4
      apps:
      - Socioboard
      band: exemplar
      in_catalog: true
      kin_score: 90.3
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/socioboard-api/Common/package.json
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
  - capability:
      attribution: Turbo EA
      id: ''
      key: service-request-management
      name: Service Request Management
      url: null
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Sprout Social
      band: exemplar
      in_catalog: true
      kin_score: 72.8
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://sproutsocial.com/integrations/
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.2
      apps:
      - Postiz
      band: developing
      in_catalog: true
      kin_score: 50.4
      mcp:
        source: https://github.com/deepgram/mcp
        status: verified
      name: Deepgram
      slug: deepgram
      sources:
      - https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
      status: profiled
      tags:
      - Artificial Intelligence
      - Speech-to-Text
      - Text-to-Speech
      - Transcription
      tier: observed
      url: /providers/deepgram/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Postiz
      band: thin
      in_catalog: true
      kin_score: 36.3
      mcp:
        source: https://raw.githubusercontent.com/cloudflare/mcp/main/README.md
        status: verified
      name: Cloudflare R2
      slug: cloudflare-r2
      sources:
      - https://raw.githubusercontent.com/gitroomhq/postiz-app/main/.env.example
      status: profiled
      tags:
      - Cloud Storage
      - Egress-Free
      - Object Storage
      - S3 Compatible
      tier: observed
      url: /providers/cloudflare-r2/
  - capability:
      attribution: Turbo EA
      id: BC-3750.20
      key: subscription-entitlement-management
      name: Subscription & Entitlement Management
      url: /capabilities/subscription-entitlement-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Socioboard
      band: emerging
      in_catalog: true
      kin_score: 17.5
      mcp:
        status: unknown
      name: aMember
      slug: amember
      sources:
      - https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/docker/.env.example
      status: profiled
      tags:
      - Membership Software
      - Payment Integration
      - Self-Hosted
      - Subscription Management
      tier: observed
      url: /providers/amember/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.2
      apps:
      - Planoly
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.planoly.android/latest/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.20
      key: AE-230.40.20
      name: Web Search APIs
      url: /capabilities/web-data/
      via_parent: Web Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.2
      apps:
      - Postiz
      band: developing
      in_catalog: true
      kin_score: 47.9
      mcp:
        source: https://github.com/tavily-ai/tavily-mcp
        status: verified
      name: Tavily
      slug: tavily
      sources:
      - https://raw.githubusercontent.com/gitroomhq/postiz-app/main/package.json
      status: profiled
      tags:
      - AI Agents
      - LLM
      - Search
      - Web Search
      tier: observed
      url: /providers/tavily/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-905
      key: AE-905
      name: IDEs & AI Coding Assistants
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.6
      apps:
      - Buffer
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        status: none
      name: Cursor
      slug: cursor
      sources:
      - https://buffer.com/integrations
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Code Editor
      - Developer Tools
      tier: declared
      url: /providers/cursor/
  layer: agent
summary:
  coverage_pct: 97.9
  declared_only: 59
  distinct_providers: 144
  in_catalog: 141
  mcp:
    documented: 4
    none: 69
    unchecked: 3
    verified: 58
  mcp_verified: 58
  mean_kin_score: 47.2
  observed: 85
  queued: 3
  reference_apps: 7
title: 'Social Media Management & Scheduling: application blueprint'
---
