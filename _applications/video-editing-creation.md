---
access: understanding
agent_layer:
- app: Penpot
  finding: 'docker-compose PENPOT_FLAGS enables enable-mcp: Penpot ships its own MCP server'
  source: https://raw.githubusercontent.com/penpot/penpot/develop/docker/images/docker-compose.yaml
  tier: observed
- app: Remotion
  finding: 'packages claude-code-plugin, codex-plugin, kimi-code-plugin, agent-plugin and skills: agent skills for coding agents'
  source: https://github.com/remotion-dev/remotion/tree/main/packages
  tier: observed
- app: Descript
  finding: Descript API + MCP ("Video Editing MCP") and Claude/ChatGPT connectors listed
  source: https://www.descript.com/integrations
  tier: declared
apps:
- anchor: penpot
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/penpot/penpot/develop/backend/deps.edn
  - route: source code
    url: https://raw.githubusercontent.com/penpot/penpot/develop/backend/src/app/config.clj
  - route: source code
    url: https://raw.githubusercontent.com/penpot/penpot/develop/docker/images/docker-compose.yaml
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://raw.githubusercontent.com/penpot/penpot/develop/backend/src/app/config.clj
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://raw.githubusercontent.com/penpot/penpot/develop/backend/src/app/config.clj
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: domain
    name: Google sign-in
    provider: google-identity-platform
    says: ships the Google sign-in SDK or integration code
    source: https://raw.githubusercontent.com/penpot/penpot/develop/backend/src/app/config.clj
    tier: observed
  kind: self-hosted
  name: Penpot
  page: /applications/video-editing-creation/penpot/
  slug: penpot
  url: https://github.com/penpot/penpot
- anchor: kdenlive
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: source code
    url: https://github.com/KDE/kdenlive/tree/master/data/resourceproviders
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Freesound
    provider: freesound
    says: ships the Freesound SDK or integration code
    source: https://github.com/KDE/kdenlive/tree/master/data/resourceproviders/freesound.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Internet Archive
    provider: internet-archive
    says: ships the Internet Archive SDK or integration code
    source: https://github.com/KDE/kdenlive/tree/master/data/resourceproviders/archiveorg.json
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
    name: Pexels
    provider: pexels
    says: ships the Pexels SDK or integration code
    source: https://github.com/KDE/kdenlive/tree/master/data/resourceproviders/pexels_photo.json
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
    source: https://github.com/KDE/kdenlive/tree/master/data/resourceproviders/pixabay_photo.json
    tier: observed
  kind: self-hosted
  name: Kdenlive
  page: /applications/video-editing-creation/kdenlive/
  slug: kdenlive
  url: https://github.com/KDE/kdenlive
- anchor: remotion
  counts:
    declared: 0
    observed: 10
  evidence:
  - route: dependency manifest
    url: https://github.com/remotion-dev/remotion/tree/main/packages
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/lambda/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-925
      key: AE-925
      name: Serverless Functions
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: AWS Lambda
    provider: aws-lambda
    says: ships the AWS Lambda SDK or integration code
    source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/lambda/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: ElevenLabs
    provider: elevenlabs
    says: ships the ElevenLabs SDK or integration code
    source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/elevenlabs/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-925
      key: AE-925
      name: Serverless Functions
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Cloud Run
    provider: google-cloud-run
    says: ships the Google Cloud Run SDK or integration code
    source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/cloudrun/package.json
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
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/cloudrun/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80.10
      key: AE-170.80.10
      name: Web Fonts & Typography
      url: /capabilities/design-creative-editing/
      via_parent: Design & Creative Editing
    credit: null
    layer: domain
    name: Google Fonts
    provider: google-fonts
    says: ships the Google Fonts SDK or integration code
    source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/google-fonts/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: domain
    name: MapTiler
    provider: maptiler
    says: ships the MapTiler SDK or integration code
    source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/maptiler/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/openai-whisper/package.json
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
    name: Rive
    provider: rive
    says: ships the Rive SDK or integration code
    source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/rive/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-906
      key: AE-906
      name: Code Execution Sandboxes
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    credit: null
    layer: domain
    name: Vercel
    provider: vercel
    says: ships the Vercel SDK or integration code
    source: https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/vercel/package.json
    tier: observed
  kind: open-source-saas
  name: Remotion
  page: /applications/video-editing-creation/remotion/
  slug: remotion
  url: https://github.com/remotion-dev/remotion
- anchor: excalidraw
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/excalidraw/excalidraw/master/excalidraw-app/package.json
  - route: source code
    url: https://raw.githubusercontent.com/excalidraw/excalidraw/master/.env.production
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://raw.githubusercontent.com/excalidraw/excalidraw/master/excalidraw-app/package.json
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
    source: https://raw.githubusercontent.com/excalidraw/excalidraw/master/excalidraw-app/package.json
    tier: observed
  kind: open-source-saas
  name: Excalidraw
  page: /applications/video-editing-creation/excalidraw/
  slug: excalidraw
  url: https://github.com/excalidraw/excalidraw
- anchor: descript
  counts:
    declared: 30
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.descript.com/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: domain
    name: Adobe Audition
    provider: adobe
    says: lists Adobe Audition as an integration
    source: https://www.descript.com/integrations
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
    name: Adobe Premiere
    provider: adobe-premiere
    says: lists Adobe Premiere as an integration
    source: https://www.descript.com/integrations
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
    name: Avid Pro Tools
    provider: avid
    says: lists Avid Pro Tools as an integration
    source: https://www.descript.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.20
      key: AE-170.20.20
      name: Podcast Hosting
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: Blubrry
    provider: blubrry-api-restful-api-for-podcast-publishing-statistics
    says: lists Blubrry as an integration
    source: https://www.descript.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.20
      key: AE-170.20.20
      name: Podcast Hosting
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: Buzzsprout
    provider: buzzsprout
    says: lists Buzzsprout as an integration
    source: https://www.descript.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.20
      key: AE-170.20.20
      name: Podcast Hosting
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: Captivate
    provider: captivate-fm
    says: lists Captivate as an integration
    source: https://www.descript.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.20
      key: AE-170.20.20
      name: Podcast Hosting
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: Castos
    provider: castos
    says: lists Castos as an integration
    source: https://www.descript.com/integrations
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
    name: ChatGPT
    provider: openai
    says: lists ChatGPT as an integration
    source: https://www.descript.com/integrations
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
    name: Claude
    provider: anthropic
    says: lists Claude as an integration
    source: https://www.descript.com/integrations
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
    name: DaVinci Resolve
    provider: blackmagic-design
    says: lists DaVinci Resolve as an integration
    source: https://www.descript.com/integrations
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
    name: Ecamm
    provider: ecamm
    says: lists Ecamm as an integration
    source: https://www.descript.com/integrations
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
    name: eWebinar
    provider: ewebinar
    says: lists eWebinar as an integration
    source: https://www.descript.com/integrations
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
    name: Final Cut Pro / Apple Logic
    provider: apple
    says: lists Final Cut Pro / Apple Logic as an integration
    source: https://www.descript.com/integrations
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
    source: https://www.descript.com/integrations
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
    name: Headliner
    provider: headliner
    says: lists Headliner as an integration
    source: https://www.descript.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.20
      key: AE-170.20.20
      name: Podcast Hosting
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: Hello Audio
    provider: hello-audio
    says: lists Hello Audio as an integration
    source: https://www.descript.com/integrations
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
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://www.descript.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.20
      key: AE-170.20.20
      name: Podcast Hosting
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: Podbean
    provider: podbean
    says: lists Podbean as an integration
    source: https://www.descript.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.20
      key: AE-170.20.20
      name: Podcast Hosting
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: Podcast.co
    provider: podcast-co
    says: lists Podcast.co as an integration
    source: https://www.descript.com/integrations
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
    source: https://www.descript.com/integrations
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
    name: REAPER
    provider: cockos-reaper
    says: lists REAPER as an integration
    source: https://www.descript.com/integrations
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
    name: Restream
    provider: restream
    says: lists Restream as an integration
    source: https://www.descript.com/integrations
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
    name: Riverside
    provider: riverside
    says: lists Riverside as an integration
    source: https://www.descript.com/integrations
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
    name: SquadCast
    provider: squadcast-fm
    says: lists SquadCast as an integration
    source: https://www.descript.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.20
      key: AE-170.20.20
      name: Podcast Hosting
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: Transistor
    provider: transistor
    says: lists Transistor as an integration
    source: https://www.descript.com/integrations
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
    name: VideoAsk
    provider: typeform
    says: lists VideoAsk as an integration
    source: https://www.descript.com/integrations
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
    name: Wistia
    provider: wistia
    says: lists Wistia as an integration
    source: https://www.descript.com/integrations
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
    name: YouTube
    provider: youtube
    says: lists YouTube as an integration
    source: https://www.descript.com/integrations
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
    source: https://www.descript.com/integrations
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
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://www.descript.com/integrations
    tier: declared
  kind: commercial
  name: Descript
  page: /applications/video-editing-creation/descript/
  slug: descript
  url: https://www.descript.com/
- anchor: capcut
  counts:
    declared: 0
    observed: 11
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Amazon Advertisement
    provider: amazon
    says: ships the Amazon Advertisement SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
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
    name: AppLovin
    provider: applovin
    says: ships the AppLovin SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
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
    name: Facebook Ads
    provider: facebook
    says: ships the Facebook Ads SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
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
    name: Facebook Analytics
    provider: facebook
    says: ships the Facebook Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook Login
    provider: facebook
    says: ships the Facebook Login SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
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
    name: Google AdMob
    provider: google-admob
    says: ships the Google AdMob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: IAB Open Measurement
    provider: iab-tech-lab
    says: ships the IAB Open Measurement SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
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
    name: Mintegral
    provider: mintegral
    says: ships the Mintegral SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
    tier: observed
  kind: commercial
  name: CapCut
  page: /applications/video-editing-creation/capcut/
  slug: capcut
  url: https://www.capcut.com/
- anchor: canva
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.canva.editor/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.canva.editor/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook Login
    provider: facebook
    says: ships the Facebook Login SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.canva.editor/latest/
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
    name: Firebase Crashlytics
    provider: firebase
    says: ships the Firebase Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.canva.editor/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.canva.editor/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.canva.editor/latest/
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
    name: Twilio Segment
    provider: segment
    says: ships the Twilio Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.canva.editor/latest/
    tier: observed
  kind: commercial
  name: Canva
  page: /applications/video-editing-creation/canva/
  slug: canva
  url: https://www.canva.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: video-editing-creation
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Photo & Video
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Graphics & Design
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Video Players & Editors
  store: google-play
  url: https://play.google.com/store/apps/category/VIDEO_PLAYERS
- category: Art & Design
  store: google-play
  url: https://play.google.com/store/apps/category/ART_AND_DESIGN
name: Video & Photo Editing / Creator Tools
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  fit: exact
  layer: domain
  why: NLE timeline interchange, animation runtimes, design tools
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: exact
  layer: domain
  why: stock photo/video/audio libraries inside the editor (Kdenlive online resources)
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.20
    key: AE-170.20.20
    name: Podcast Hosting
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  fit: exact
  layer: domain
  why: publish edited audio to podcast hosts (Descript)
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  fit: exact
  layer: domain
  why: publish finished video (YouTube, Wistia)
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: domain
  why: import remote recordings (Zoom, Riverside, SquadCast)
- capability:
    attribution: API Evangelist extension
    id: AE-925
    key: AE-925
    name: Serverless Functions
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: cloud rendering of programmatic video (Remotion Lambda / Cloud Run)
- capability:
    attribution: API Evangelist extension
    id: AE-906
    key: AE-906
    name: Code Execution Sandboxes
    url: /capabilities/engineering-productivity-management/
    via_parent: Engineering Productivity Management
  fit: exact
  layer: domain
  why: sandboxed render workers (Vercel Sandbox)
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.10
    key: AE-110.30.10
    name: Speech-to-Text
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  fit: exact
  layer: domain
  why: auto-captions
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: AI assistant connectors
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: domain
  why: animated map scenes
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: sign-in for collaborative design tools
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: render output and asset buckets
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: realtime collaboration persistence
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: automation connectors
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: import/export media files
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  fit: exact
  layer: domain
  why: async video forms (VideoAsk)
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: in-app ad monetisation
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: install attribution and deep links
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: in-app usage analytics
- capability:
    attribution: Turbo EA
    id: BC-3760.30
    key: programmatic-sales-management
    name: Programmatic Sales Management
    url: /capabilities/programmatic-sales-management/
    via_parent: null
  fit: nearest
  layer: common
  why: ad viewability measurement
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.7
      apps:
      - Remotion
      band: emerging
      in_catalog: true
      kin_score: 23.6
      mcp:
        status: none
      name: Rive
      slug: rive
      sources:
      - https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/rive/package.json
      status: profiled
      tags:
      - Animation
      - Company
      - Design
      - Graphics
      tier: observed
      url: /providers/rive/
    - agent_band: agent-ready
      agent_readiness: 62.9
      apps:
      - Descript
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://github.com/adobe/cq-quickstart-mcp-server
        status: verified
      name: Adobe Audition
      slug: adobe
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Adobe
      - Analytics
      - E-Signature
      - Fortune 1000
      tier: declared
      url: /providers/adobe/
    - agent_band: agent-ready
      agent_readiness: 36.8
      apps:
      - Descript
      band: strong
      in_catalog: true
      kin_score: 58.6
      mcp:
        status: none
      name: Adobe Premiere
      slug: adobe-premiere
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Adobe
      - Automation
      - Creative Cloud
      - Media
      tier: declared
      url: /providers/adobe-premiere/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Descript
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Final Cut Pro / Apple Logic
      slug: apple
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Descript
      band: thin
      in_catalog: true
      kin_score: 28.4
      mcp:
        status: unknown
      name: Ecamm
      slug: ecamm
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Live Streaming
      - Multistreaming
      - Video Production
      - Virtual Camera
      tier: declared
      url: /providers/ecamm/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Descript
      band: thin
      in_catalog: true
      kin_score: 27.8
      mcp:
        status: unknown
      name: Avid Pro Tools
      slug: avid
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Audio
      - Company
      - Media
      - Software
      tier: declared
      url: /providers/avid/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Descript
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        status: none
      name: DaVinci Resolve
      slug: blackmagic-design
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Broadcast
      - Cinema
      - Software
      - Video
      tier: declared
      url: /providers/blackmagic-design/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Descript
      band: minimal
      in_catalog: true
      kin_score: 9.6
      mcp:
        status: unknown
      name: REAPER
      slug: cockos-reaper
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Audio
      - Digital Audio Workstation
      - Music Production
      - Windows
      tier: declared
      url: /providers/cockos-reaper/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Descript
      band: minimal
      in_catalog: true
      kin_score: 2.2
      mcp:
        status: unknown
      name: Headliner
      slug: headliner
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Marketing
      - Podcasts
      - Software-as-a-Service
      - Video
      tier: declared
      url: /providers/headliner/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.20
      key: AE-170.20.20
      name: Podcast Hosting
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.8
      apps:
      - Descript
      band: strong
      in_catalog: true
      kin_score: 57.0
      mcp:
        status: unknown
      name: Blubrry
      slug: blubrry-api-restful-api-for-podcast-publishing-statistics
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Audio
      - Media
      - Podcasts
      - Publishing
      tier: declared
      url: /providers/blubrry-api-restful-api-for-podcast-publishing-statistics/
    - agent_band: agent-ready
      agent_readiness: 37.4
      apps:
      - Descript
      band: developing
      in_catalog: true
      kin_score: 48.7
      mcp:
        status: unknown
      name: Podcast.co
      slug: podcast-co
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Audio
      - Hosting
      - Podcasts
      - Software-as-a-Service
      tier: declared
      url: /providers/podcast-co/
    - agent_band: agent-aware
      agent_readiness: 11.3
      apps:
      - Descript
      band: developing
      in_catalog: true
      kin_score: 45.1
      mcp:
        status: none
      name: Hello Audio
      slug: hello-audio
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Audio
      - Company
      - Podcasts
      - Software-as-a-Service
      tier: declared
      url: /providers/hello-audio/
    - agent_band: agent-ready
      agent_readiness: 50.0
      apps:
      - Descript
      band: developing
      in_catalog: true
      kin_score: 39.8
      mcp:
        source: https://mcp.transistor.fm/
        status: verified
      name: Transistor
      slug: transistor
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Analytics
      - Media
      - Podcast Hosting
      - Podcasts
      tier: declared
      url: /providers/transistor/
    - agent_band: human-only
      agent_readiness: 4.5
      apps:
      - Descript
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: unknown
      name: Castos
      slug: castos
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Analytics
      - Hosting
      - Media
      - Podcasts
      tier: declared
      url: /providers/castos/
    - agent_band: agent-ready
      agent_readiness: 48.5
      apps:
      - Descript
      band: thin
      in_catalog: true
      kin_score: 31.4
      mcp:
        status: none
      name: Podbean
      slug: podbean
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Audio
      - Media
      - Podcast Hosting
      - Podcasts
      tier: declared
      url: /providers/podbean/
    - agent_band: agent-aware
      agent_readiness: 27.2
      apps:
      - Descript
      band: thin
      in_catalog: true
      kin_score: 29.6
      mcp:
        status: none
      name: Captivate
      slug: captivate-fm
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Episodes
      - Media
      - Podcast Hosting
      - Podcasts
      tier: declared
      url: /providers/captivate-fm/
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Descript
      band: thin
      in_catalog: true
      kin_score: 27.6
      mcp:
        status: unknown
      name: Buzzsprout
      slug: buzzsprout
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Audio
      - Media
      - Podcast Hosting
      - Podcasts
      tier: declared
      url: /providers/buzzsprout/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Descript
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 40.6
      apps:
      - Descript
      band: exemplar
      in_catalog: true
      kin_score: 75.5
      mcp:
        source: https://docs.wistia.com/docs/mcp-server-guide
        status: documented
      name: Wistia
      slug: wistia
      sources:
      - https://www.descript.com/integrations
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
      - Descript
      band: strong
      in_catalog: true
      kin_score: 65.4
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: declared
      url: /providers/youtube/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Descript
      band: thin
      in_catalog: true
      kin_score: 34.4
      mcp:
        source: https://github.com/restreamio/cursor-mcp-plugin
        status: verified
      name: Restream
      slug: restream
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Broadcast
      - Chat
      - Content Delivery
      - Live Streaming
      tier: declared
      url: /providers/restream/
    - agent_band: agent-aware
      agent_readiness: 22.1
      apps:
      - Descript
      band: thin
      in_catalog: true
      kin_score: 30.1
      mcp:
        status: none
      name: eWebinar
      slug: ewebinar
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Company
      - On-Demand
      - Video
      - Webinar
      tier: declared
      url: /providers/ewebinar/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Penpot
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://raw.githubusercontent.com/penpot/penpot/develop/backend/src/app/config.clj
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Penpot
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://raw.githubusercontent.com/penpot/penpot/develop/backend/src/app/config.clj
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Penpot
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://raw.githubusercontent.com/penpot/penpot/develop/backend/src/app/config.clj
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
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
      - Descript
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: declared
      url: /providers/zoom/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Descript
      band: developing
      in_catalog: true
      kin_score: 47.4
      mcp:
        source: https://github.com/riversidefm/riverside-mcp-public
        status: verified
      name: Riverside
      slug: riverside
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Content Creation
      - Media
      - Podcasts
      - Video Recording
      tier: declared
      url: /providers/riverside/
    - agent_band: null
      agent_readiness: null
      apps:
      - Descript
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: SquadCast
      slug: squadcast-fm
      sources:
      - https://www.descript.com/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.1
      apps:
      - Kdenlive
      band: thin
      in_catalog: true
      kin_score: 38.4
      mcp:
        status: none
      name: Pexels
      slug: pexels
      sources:
      - https://github.com/KDE/kdenlive/tree/master/data/resourceproviders/pexels_photo.json
      status: profiled
      tags:
      - Photos
      - Stock Media
      - Video
      tier: observed
      url: /providers/pexels/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Kdenlive
      band: emerging
      in_catalog: true
      kin_score: 13.7
      mcp:
        status: none
      name: Pixabay
      slug: pixabay
      sources:
      - https://github.com/KDE/kdenlive/tree/master/data/resourceproviders/pixabay_photo.json
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
      id: AE-925
      key: AE-925
      name: Serverless Functions
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-native
      agent_readiness: 45.6
      apps:
      - Remotion
      band: exemplar
      in_catalog: true
      kin_score: 74.9
      mcp:
        source: https://github.com/awslabs/mcp/tree/main/src/lambda-tool-mcp-server
        status: verified
      name: AWS Lambda
      slug: aws-lambda
      sources:
      - https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/lambda/package.json
      status: profiled
      tags:
      - Logging
      - Monitoring
      - Observability
      - Serverless
      tier: observed
      url: /providers/aws-lambda/
    - agent_band: agent-ready
      agent_readiness: 38.9
      apps:
      - Remotion
      band: exemplar
      in_catalog: true
      kin_score: 67.0
      mcp:
        source: https://github.com/GoogleCloudPlatform/cloud-run-mcp
        status: verified
      name: Google Cloud Run
      slug: google-cloud-run
      sources:
      - https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/cloudrun/package.json
      status: profiled
      tags:
      - Cloud Run
      - Containers
      - Google Cloud
      - Serverless
      tier: observed
      url: /providers/google-cloud-run/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    providers:
    - agent_band: agent-ready
      agent_readiness: 60.4
      apps:
      - Remotion
      band: exemplar
      in_catalog: true
      kin_score: 83.2
      mcp:
        source: https://github.com/elevenlabs/elevenlabs-mcp
        status: verified
      name: ElevenLabs
      slug: elevenlabs
      sources:
      - https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/elevenlabs/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Speech-to-Text
      - Text-to-Speech
      - Voice
      tier: observed
      url: /providers/elevenlabs/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Remotion
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: &id005
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/openai-whisper/package.json
      status: profiled
      tags: &id006
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.40
      key: AE-170.30.40
      name: Stock Media & Royalty-Free Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Kdenlive
      band: minimal
      in_catalog: true
      kin_score: 4.8
      mcp:
        status: none
      name: Freesound
      slug: freesound
      sources:
      - https://github.com/KDE/kdenlive/tree/master/data/resourceproviders/freesound.json
      status: profiled
      tags:
      - Music
      - Public APIs
      tier: observed
      url: /providers/freesound/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Kdenlive
      band: minimal
      in_catalog: true
      kin_score: 4.0
      mcp:
        status: none
      name: Internet Archive
      slug: internet-archive
      sources:
      - https://github.com/KDE/kdenlive/tree/master/data/resourceproviders/archiveorg.json
      status: profiled
      tags:
      - Archival
      - Digital Library
      - Non-Profit
      - Open Access
      tier: observed
      url: /providers/internet-archive/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Remotion
      band: developing
      in_catalog: true
      kin_score: 41.0
      mcp:
        status: none
      name: MapTiler
      slug: maptiler
      sources:
      - https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/maptiler/package.json
      status: profiled
      tags:
      - Geospatial
      - Maps
      - Tiles
      - Vector Tiles
      tier: observed
      url: /providers/maptiler/
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
      - Descript
      band: exemplar
      in_catalog: true
      kin_score: 73.2
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: declared
      url: /providers/google-drive/
  - capability:
      attribution: API Evangelist extension
      id: AE-906
      key: AE-906
      name: Code Execution Sandboxes
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.0
      apps:
      - Remotion
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp:
        source: https://vercel.com/docs/mcp/vercel-mcp
        status: verified
      name: Vercel
      slug: vercel
      sources:
      - https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/vercel/package.json
      status: profiled
      tags:
      - AI Gateway
      - Gateways
      - Observability
      - Webhook
      tier: observed
      url: /providers/vercel/
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.6
      apps:
      - Descript
      band: thin
      in_catalog: true
      kin_score: 36.0
      mcp:
        source: https://www.typeform.com/developers/mcp
        status: verified
      name: VideoAsk
      slug: typeform
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Forms
      - Lead Capture
      - Software-as-a-Service
      - Surveys
      tier: declared
      url: /providers/typeform/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80.10
      key: AE-170.80.10
      name: Web Fonts & Typography
      url: /capabilities/design-creative-editing/
      via_parent: Design & Creative Editing
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.7
      apps:
      - Remotion
      band: developing
      in_catalog: true
      kin_score: 54.2
      mcp:
        status: none
      name: Google Fonts
      slug: google-fonts
      sources:
      - https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/google-fonts/package.json
      status: profiled
      tags:
      - CSS
      - Design
      - Fonts
      - Google Fonts
      tier: observed
      url: /providers/google-fonts/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - CapCut
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
    - agent_band: agent-native
      agent_readiness: 53.6
      apps:
      - CapCut
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Amazon Advertisement
      slug: amazon
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: observed
      url: /providers/amazon/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - CapCut
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id001
        status: none
      name: Facebook Ads
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
      status: profiled
      tags: &id002
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 35.5
      apps:
      - CapCut
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp:
        status: none
      name: AppLovin
      slug: applovin
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - App Monetization
      - Mobile
      tier: observed
      url: /providers/applovin/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - CapCut
      band: emerging
      in_catalog: true
      kin_score: 16.2
      mcp:
        status: unknown
      name: Mintegral
      slug: mintegral
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
      status: profiled
      tags:
      - Advertising
      - Artificial Intelligence
      - Company
      - Mobile Marketing
      tier: observed
      url: /providers/mintegral/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - CapCut
      band: emerging
      in_catalog: true
      kin_score: 14.1
      mcp:
        status: none
      name: Pangle
      slug: pangle
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
      status: profiled
      tags:
      - Advertising
      - Mobile
      - Monetization
      - TikTok
      tier: observed
      url: /providers/pangle/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Canva
      - CapCut
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.canva.editor/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
      status: profiled
      tags: &id004
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - CapCut
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id001
      name: Facebook Analytics
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Canva
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Twilio Segment
      slug: segment
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.canva.editor/latest/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
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
      - Canva
      - Excalidraw
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/excalidraw/excalidraw/master/excalidraw-app/package.json
      - https://reports.exodus-privacy.eu.org/en/reports/com.canva.editor/latest/
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
      - Canva
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id003
      name: Firebase Crashlytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.canva.editor/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/google-firebase/
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
      - Canva
      - CapCut
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.canva.editor/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
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
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Canva
      - CapCut
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id001
      name: Facebook Login
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.canva.editor/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/facebook/
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
      - Remotion
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/lambda/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Remotion
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://raw.githubusercontent.com/remotion-dev/remotion/main/packages/cloudrun/package.json
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
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
      - Descript
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-aware
      agent_readiness: 13.3
      apps:
      - Descript
      band: emerging
      in_catalog: true
      kin_score: 25.2
      mcp:
        status: none
      name: Raycast
      slug: raycast
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Extensions
      - Launcher
      - Productivity
      - SDK
      tier: declared
      url: /providers/raycast/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Excalidraw
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id003
      name: Firebase
      slug: google-firebase
      sources:
      - https://raw.githubusercontent.com/excalidraw/excalidraw/master/excalidraw-app/package.json
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - CapCut
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        source: https://github.com/IABTechLab/agentic-real-time-framework
        status: verified
      name: IAB Open Measurement
      slug: iab-tech-lab
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.lemon.lvoverseas/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Standards
      tier: observed
      url: /providers/iab-tech-lab/
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
      - Descript
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Claude
      slug: anthropic
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: declared
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Descript
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: *id005
      name: ChatGPT
      slug: openai
      sources:
      - https://www.descript.com/integrations
      status: profiled
      tags: *id006
      tier: declared
      url: /providers/openai/
  layer: agent
summary:
  coverage_pct: 98.2
  declared_only: 30
  distinct_providers: 57
  in_catalog: 56
  mcp:
    documented: 1
    none: 22
    unchecked: 1
    verified: 24
  mcp_verified: 24
  mean_kin_score: 49.2
  observed: 27
  queued: 1
  reference_apps: 7
title: 'Video & Photo Editing / Creator Tools: application blueprint'
---
