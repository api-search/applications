---
access: understanding
agent_layer: []
apps:
- anchor: wordpress
  counts:
    declared: 0
    observed: 30
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/org.wordpress.android/latest/
  - route: source code
    url: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  - route: source code
    url: https://github.com/WordPress/WordPress/blob/master/wp-includes/pluggable.php
  - route: source code
    url: https://github.com/WordPress/WordPress/tree/master/wp-content/plugins
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Amazon Kindle Instant Preview
    provider: amazon
    says: ships the Amazon Kindle Instant Preview SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20
      key: AE-170.20
      name: Audio & Music
      url: /capabilities/audio-music/
      via_parent: null
    credit: null
    layer: domain
    name: Anghami
    provider: anghami
    says: ships the Anghami SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
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
    name: Animoto
    provider: animoto
    says: ships the Animoto SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
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
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
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
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
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
    name: Cloudup
    provider: cloudup
    says: ships the Cloudup SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: domain
    name: Crowdsignal
    provider: crowdsignal
    says: ships the Crowdsignal SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
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
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
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
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: common
    name: Gravatar
    provider: gravatar
    says: ships the Gravatar SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/pluggable.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Issuu
    provider: issuu
    says: ships the Issuu SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.40
      key: AE-170.40
      name: Creator Monetisation
      url: /capabilities/creator-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: Kickstarter
    provider: kickstarter
    says: ships the Kickstarter SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20
      key: AE-170.20
      name: Audio & Music
      url: /capabilities/audio-music/
      via_parent: null
    credit: null
    layer: domain
    name: Mixcloud
    provider: mixcloud
    says: ships the Mixcloud SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
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
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.20
      key: AE-170.20.20
      name: Podcast Hosting
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    credit: null
    layer: domain
    name: Pocket Casts
    provider: pocket-casts
    says: ships the Pocket Casts SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
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
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20
      key: AE-170.20
      name: Audio & Music
      url: /capabilities/audio-music/
      via_parent: null
    credit: null
    layer: domain
    name: ReverbNation
    provider: reverbnation
    says: ships the ReverbNation SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Scribd
    provider: scribd
    says: ships the Scribd SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
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
    source: https://reports.exodus-privacy.eu.org/en/reports/org.wordpress.android/latest/
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
    name: SmugMug
    provider: smugmug
    says: ships the SmugMug SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20
      key: AE-170.20
      name: Audio & Music
      url: /capabilities/audio-music/
      via_parent: null
    credit: null
    layer: domain
    name: SoundCloud
    provider: soundcloud
    says: ships the SoundCloud SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Speaker Deck
    provider: speakerdeck
    says: ships the Speaker Deck SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20
      key: AE-170.20
      name: Audio & Music
      url: /capabilities/audio-music/
      via_parent: null
    credit: null
    layer: domain
    name: Spotify
    provider: spotify
    says: ships the Spotify SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
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
    name: TED
    provider: ted-com
    says: ships the TED SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
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
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
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
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
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
    name: Vimeo
    provider: vimeo
    says: ships the Vimeo SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Wolfram Cloud
    provider: wolframalpha
    says: ships the Wolfram Cloud SDK or integration code
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
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
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
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
    source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
    tier: observed
  kind: self-hosted
  name: WordPress
  page: /applications/website-builder-cms/wordpress/
  slug: wordpress
  url: https://github.com/WordPress/WordPress
- anchor: ghost
  counts:
    declared: 73
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://github.com/TryGhost/Ghost/blob/main/ghost/package.json
  - route: integrations page
    url: https://ghost.org/integrations/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.30
      key: AE-170.60.30
      name: Newsletters
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Mailgun
    provider: mailgun
    says: ships the Mailgun SDK or integration code
    source: https://github.com/TryGhost/Ghost/blob/main/ghost/package.json
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
    source: https://github.com/TryGhost/Ghost/blob/main/ghost/package.json
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
    source: https://github.com/TryGhost/Ghost/blob/main/ghost/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.50
      key: marketing-operations-management
      name: Marketing Operations Management
      url: /capabilities/marketing-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: ActiveCampaign
    provider: activecampaign
    says: lists ActiveCampaign as an integration
    source: https://ghost.org/integrations/
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
    name: Airtable
    provider: airtable
    says: lists Airtable as an integration
    source: https://ghost.org/integrations/
    tier: declared
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
    says: lists Amazon S3 as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Amplitude
    provider: amplitude
    says: lists Amplitude as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Backblaze B2
    provider: backblaze
    says: lists Backblaze B2 as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: BeyondWords
    provider: beyondwords
    says: lists BeyondWords as an integration
    source: https://ghost.org/integrations/
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
    name: Buffer
    provider: buffer
    says: lists Buffer as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.30
      key: AE-170.60.30
      name: Newsletters
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Buttondown
    provider: buttondown
    says: lists Buttondown as an integration
    source: https://ghost.org/integrations/
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
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4250.70
      key: subscription-revenue-analytics
      name: Subscription Revenue Analytics
      url: /capabilities/subscription-revenue-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: ChartMogul
    provider: chartmogul
    says: lists ChartMogul as an integration
    source: https://ghost.org/integrations/
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
    name: Circle
    provider: circle-community
    says: lists Circle as an integration
    source: https://ghost.org/integrations/
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
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.50
      key: AE-160.50
      name: Consent & Preferences
      url: /capabilities/consent-preferences/
      via_parent: null
    credit: null
    layer: common
    name: CookieYes
    provider: cookieyes
    says: lists CookieYes as an integration
    source: https://ghost.org/integrations/
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
    name: Discord
    provider: discord
    says: lists Discord as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.30
      key: AE-170.50.30
      name: Embedded Comments
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    credit: null
    layer: domain
    name: Discourse
    provider: discourse
    says: lists Discourse as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.30
      key: AE-170.50.30
      name: Embedded Comments
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    credit: null
    layer: domain
    name: Disqus
    provider: disqus
    says: lists Disqus as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.50
      key: marketing-operations-management
      name: Marketing Operations Management
      url: /capabilities/marketing-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Drip
    provider: drip
    says: lists Drip as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: EmailOctopus
    provider: emailoctopus
    says: lists EmailOctopus as an integration
    source: https://ghost.org/integrations/
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
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Fathom Analytics
    provider: fathom
    says: lists Fathom Analytics as an integration
    source: https://ghost.org/integrations/
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
    name: Formspree
    provider: formspree
    says: lists Formspree as an integration
    source: https://ghost.org/integrations/
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
    name: GatherContent
    provider: gathercontent
    says: lists GatherContent as an integration
    source: https://ghost.org/integrations/
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
    name: Geckoboard
    provider: geckoboard
    says: lists Geckoboard as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: GIPHY
    provider: giphy
    says: lists GIPHY as an integration
    source: https://ghost.org/integrations/
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
    name: Google AdSense
    provider: google-adsense
    says: lists Google AdSense as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Google Analytics
    provider: google-analytics
    says: lists Google Analytics as an integration
    source: https://ghost.org/integrations/
    tier: declared
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
    says: lists Google Cloud Storage as an integration
    source: https://ghost.org/integrations/
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
    name: Google Search Console
    provider: google-search-console
    says: lists Google Search Console as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.40
      key: AE-170.40
      name: Creator Monetisation
      url: /capabilities/creator-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: Gumroad
    provider: gumroad
    says: lists Gumroad as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Help Scout
    provider: helpscout
    says: lists Help Scout as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Hotjar
    provider: hotjar
    says: lists Hotjar as an integration
    source: https://ghost.org/integrations/
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
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://ghost.org/integrations/
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
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Intercom
    provider: intercom
    says: lists Intercom as an integration
    source: https://ghost.org/integrations/
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
    name: Jotform
    provider: jotform
    says: lists Jotform as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: Kit (ConvertKit)
    provider: convertkit
    says: lists Kit (ConvertKit) as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-926
      key: AE-926
      name: Web Hosting & Control Panels
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Let's Encrypt
    provider: lets-encrypt
    says: lists Let's Encrypt as an integration
    source: https://ghost.org/integrations/
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
    name: Listen Notes
    provider: listennotes
    says: lists Listen Notes as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: LiveChat
    provider: livechat
    says: lists LiveChat as an integration
    source: https://ghost.org/integrations/
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
    name: Loom
    provider: loom
    says: lists Loom as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: MailerLite
    provider: mailerlite
    says: lists MailerLite as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Matomo
    provider: matomo
    says: lists Matomo as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-926
      key: AE-926
      name: Web Hosting & Control Panels
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Netlify
    provider: netlify
    says: lists Netlify as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.40
      key: AE-170.40
      name: Creator Monetisation
      url: /capabilities/creator-monetisation/
      via_parent: null
    credit: null
    layer: domain
    name: Patreon
    provider: patreon
    says: lists Patreon as an integration
    source: https://ghost.org/integrations/
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
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://ghost.org/integrations/
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
    source: https://ghost.org/integrations/
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
    name: Pipedream
    provider: pipedream
    says: lists Pipedream as an integration
    source: https://ghost.org/integrations/
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
    name: Placid
    provider: placid
    says: lists Placid as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Plausible
    provider: plausible
    says: lists Plausible as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Shopify
    provider: shopify
    says: lists Shopify as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Simple Analytics
    provider: simpleanalytics
    says: lists Simple Analytics as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Snipcart
    provider: snipcart
    says: lists Snipcart as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20
      key: AE-170.20
      name: Audio & Music
      url: /capabilities/audio-music/
      via_parent: null
    credit: null
    layer: domain
    name: SoundCloud
    provider: soundcloud
    says: lists SoundCloud as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20
      key: AE-170.20
      name: Audio & Music
      url: /capabilities/audio-music/
      via_parent: null
    credit: null
    layer: domain
    name: Spotify
    provider: spotify
    says: lists Spotify as an integration
    source: https://ghost.org/integrations/
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
    name: SurveyMonkey
    provider: surveymonkey
    says: lists SurveyMonkey as an integration
    source: https://ghost.org/integrations/
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
    name: Tally
    provider: tally
    says: lists Tally as an integration
    source: https://ghost.org/integrations/
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
    name: Tinybird
    provider: tinybird
    says: lists Tinybird as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.20
      key: AE-170.70.20
      name: Translation Management & Localization
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Transifex
    provider: transifex
    says: lists Transifex as an integration
    source: https://ghost.org/integrations/
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
    source: https://ghost.org/integrations/
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
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: domain
    name: Twilio Segment
    provider: segment
    says: lists Twilio Segment as an integration
    source: https://ghost.org/integrations/
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
    name: Twitch
    provider: twitch
    says: lists Twitch as an integration
    source: https://ghost.org/integrations/
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
    name: Typeform
    provider: typeform
    says: lists Typeform as an integration
    source: https://ghost.org/integrations/
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
    source: https://ghost.org/integrations/
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
    name: Vimeo
    provider: vimeo
    says: lists Vimeo as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: VWO
    provider: vwo
    says: lists VWO as an integration
    source: https://ghost.org/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.20
      key: AE-170.70.20
      name: Translation Management & Localization
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Weglot
    provider: weglot
    says: lists Weglot as an integration
    source: https://ghost.org/integrations/
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
    name: Wufoo
    provider: wufoo
    says: lists Wufoo as an integration
    source: https://ghost.org/integrations/
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
    source: https://ghost.org/integrations/
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
    source: https://ghost.org/integrations/
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
    source: https://ghost.org/integrations/
    tier: declared
  kind: open-source-saas
  name: Ghost
  page: /applications/website-builder-cms/ghost/
  slug: ghost
  url: https://github.com/TryGhost/Ghost
- anchor: strapi
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: source code
    url: https://github.com/strapi/strapi/tree/develop/packages/providers
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
    source: https://github.com/strapi/strapi/tree/develop/packages/providers/upload-aws-s3
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
    name: Amazon SES
    provider: amazon-ses
    says: ships the Amazon SES SDK or integration code
    source: https://github.com/strapi/strapi/tree/develop/packages/providers/email-amazon-ses
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
    name: Cloudinary
    provider: cloudinary
    says: ships the Cloudinary SDK or integration code
    source: https://github.com/strapi/strapi/tree/develop/packages/providers/upload-cloudinary
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
    name: Mailgun
    provider: mailgun
    says: ships the Mailgun SDK or integration code
    source: https://github.com/strapi/strapi/tree/develop/packages/providers/email-mailgun
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
    source: https://github.com/strapi/strapi/tree/develop/packages/providers/email-sendgrid
    tier: observed
  kind: self-hosted
  name: Strapi
  page: /applications/website-builder-cms/strapi/
  slug: strapi
  url: https://github.com/strapi/strapi
- anchor: directus
  counts:
    declared: 0
    observed: 12
  evidence:
  - route: dependency manifest
    url: https://github.com/directus/directus/blob/main/api/package.json
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
    source: https://github.com/directus/directus/blob/main/api/package.json
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
    name: Amazon SES
    provider: amazon-ses
    says: ships the Amazon SES SDK or integration code
    source: https://github.com/directus/directus/blob/main/api/package.json
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
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://github.com/directus/directus/blob/main/api/package.json
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
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: ships the Azure Blob Storage SDK or integration code
    source: https://github.com/directus/directus/blob/main/api/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: agent
    name: Braintrust
    provider: braintrust
    says: ships the Braintrust SDK or integration code
    source: https://github.com/directus/directus/blob/main/api/package.json
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
    name: Cloudinary
    provider: cloudinary
    says: ships the Cloudinary SDK or integration code
    source: https://github.com/directus/directus/blob/main/api/package.json
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
    source: https://github.com/directus/directus/blob/main/api/package.json
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
    source: https://github.com/directus/directus/blob/main/api/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: agent
    name: Langfuse
    provider: langfuse
    says: ships the Langfuse SDK or integration code
    source: https://github.com/directus/directus/blob/main/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-926
      key: AE-926
      name: Web Hosting & Control Panels
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Netlify
    provider: netlify
    says: ships the Netlify SDK or integration code
    source: https://github.com/directus/directus/blob/main/api/package.json
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
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/directus/directus/blob/main/api/package.json
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
    name: Supabase Storage
    provider: supabase
    says: ships the Supabase Storage SDK or integration code
    source: https://github.com/directus/directus/blob/main/api/package.json
    tier: observed
  kind: self-hosted
  name: Directus
  page: /applications/website-builder-cms/directus/
  slug: directus
  url: https://github.com/directus/directus
- anchor: payload
  counts:
    declared: 0
    observed: 9
  evidence:
  - route: source code
    url: https://github.com/payloadcms/payload/tree/main/packages
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
    source: https://github.com/payloadcms/payload/tree/main/packages/storage-s3
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
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: ships the Azure Blob Storage SDK or integration code
    source: https://github.com/payloadcms/payload/tree/main/packages/storage-azure
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Cloudflare D1
    provider: cloudflare-d1
    says: ships the Cloudflare D1 SDK or integration code
    source: https://github.com/payloadcms/payload/tree/main/packages/db-d1-sqlite
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
    source: https://github.com/payloadcms/payload/tree/main/packages/storage-r2
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
    source: https://github.com/payloadcms/payload/tree/main/packages/storage-gcs
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
    source: https://github.com/payloadcms/payload/tree/main/packages/email-resend
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
    source: https://github.com/payloadcms/payload/tree/main/packages/plugin-sentry
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
    source: https://github.com/payloadcms/payload/tree/main/packages/plugin-stripe
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Vercel Postgres / Blob
    provider: vercel
    says: ships the Vercel Postgres / Blob SDK or integration code
    source: https://github.com/payloadcms/payload/tree/main/packages/db-vercel-postgres
    tier: observed
  kind: self-hosted
  name: Payload
  page: /applications/website-builder-cms/payload/
  slug: payload
  url: https://github.com/payloadcms/payload
- anchor: webflow
  counts:
    declared: 17
    observed: 0
  evidence:
  - route: integrations page
    url: https://webflow.com/apps
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-400.50
      key: marketing-operations-management
      name: Marketing Operations Management
      url: /capabilities/marketing-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Adobe Marketo Engage
    provider: marketo
    says: lists Adobe Marketo Engage as an integration
    source: https://webflow.com/apps/detail/adobe-marketo-engage
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Algolia
    provider: algolia
    says: lists Algolia as an integration
    source: https://webflow.com/apps/detail/algolia
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
    name: Claude MCP connector
    provider: anthropic
    says: lists Claude MCP connector as an integration
    source: https://webflow.com/apps/detail/claude
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
    source: https://webflow.com/apps/detail/figma
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-931
      key: AE-931
      name: No-Code App Builders
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    credit: null
    layer: domain
    name: Finsweet
    provider: finsweet
    says: lists Finsweet as an integration
    source: https://webflow.com/apps/detail/finsweet
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
    name: Gemini MCP connector
    provider: google-gemini
    says: lists Gemini MCP connector as an integration
    source: https://webflow.com/apps/detail/google-gemini
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
    name: Google Ads
    provider: google-ads
    says: lists Google Ads as an integration
    source: https://webflow.com/apps/detail/google-ads
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
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://webflow.com/apps/detail/hubspot
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
    name: LottieFiles
    provider: lottiefiles
    says: lists LottieFiles as an integration
    source: https://webflow.com/apps/detail/lottiefiles
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
    source: https://webflow.com/apps/detail/make
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
    name: Memberstack
    provider: memberstack
    says: lists Memberstack as an integration
    source: https://webflow.com/apps/detail/memberstack
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Clarity
    provider: microsoft-clarity
    says: lists Microsoft Clarity as an integration
    source: https://webflow.com/apps/detail/microsoft-clarity
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
    name: Relume
    provider: relume
    says: lists Relume as an integration
    source: https://webflow.com/apps/detail/relume
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://webflow.com/apps/detail/slack
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
    source: https://webflow.com/apps/detail/unsplash
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
    name: Wistia
    provider: wistia
    says: lists Wistia as an integration
    source: https://webflow.com/apps/detail/wistia
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
    source: https://webflow.com/apps/detail/zapier
    tier: declared
  kind: commercial
  name: Webflow
  page: /applications/website-builder-cms/webflow/
  slug: webflow
  url: https://webflow.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: website-builder-cms
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
- category: Content Management Systems (CMS)
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#content-management-systems-cms
- category: Blogging Platforms
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#blogging-platforms
- category: Static Site Generators
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#static-site-generators
- category: Website Builders
  store: zapier
  url: https://zapier.com/apps
name: Website Builder, CMS & Blogging
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  fit: exact
  layer: domain
  why: 'oEmbed: every CMS turns pasted URLs into embeds'
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  fit: exact
  layer: domain
  why: content import/migration sources
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  fit: exact
  layer: domain
  why: video embeds and hosting
- capability:
    attribution: API Evangelist extension
    id: AE-170.20
    key: AE-170.20
    name: Audio & Music
    url: /capabilities/audio-music/
    via_parent: null
  fit: exact
  layer: domain
  why: audio embeds
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.20
    key: AE-170.20.20
    name: Podcast Hosting
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  fit: exact
  layer: domain
  why: podcast players on blogs
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: domain
  why: social embeds and sharing
- capability:
    attribution: API Evangelist extension
    id: AE-914
    key: AE-914
    name: Social Listening & Analytics
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: exact
  layer: domain
  why: social publishing (nearest node)
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: exact
  layer: domain
  why: stock photos and image embeds
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: domain
  why: commenter avatars and GIF pickers
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.10
    key: AE-170.30.10
    name: Image Processing & Optimisation
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: domain
  why: media library transforms and OG-image generation
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  fit: exact
  layer: domain
  why: design-to-site and animation assets
- capability:
    attribution: API Evangelist extension
    id: AE-170.40
    key: AE-170.40
    name: Creator Monetisation
    url: /capabilities/creator-monetisation/
    via_parent: null
  fit: exact
  layer: domain
  why: creator funding and digital sales
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.30
    key: AE-170.60.30
    name: Newsletters
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  fit: exact
  layer: domain
  why: blog-as-newsletter delivery
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: domain
  why: list sync to email marketing
- capability:
    attribution: Turbo EA
    id: BC-400.50
    key: marketing-operations-management
    name: Marketing Operations Management
    url: /capabilities/marketing-operations-management/
    via_parent: null
  fit: exact
  layer: domain
  why: marketing automation
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: lead capture to CRM
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: domain
  why: CDP event routing
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: domain
  why: site analytics
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: ads, SEO console
- capability:
    attribution: Turbo EA
    id: BC-4250.70
    key: subscription-revenue-analytics
    name: Subscription Revenue Analytics
    url: /capabilities/subscription-revenue-analytics/
    via_parent: null
  fit: exact
  layer: domain
  why: membership revenue analytics
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: domain
  why: dashboards and event analytics
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  fit: exact
  layer: domain
  why: embedded forms and polls
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.30
    key: AE-170.50.30
    name: Embedded Comments
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  fit: exact
  layer: domain
  why: comment systems
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: exact
  layer: domain
  why: commerce on content sites
- capability:
    attribution: API Evangelist extension
    id: AE-140.40.20
    key: AE-140.40.20
    name: Memberships
    url: /capabilities/d2c-subscriptions/
    via_parent: D2C Subscriptions
  fit: exact
  layer: domain
  why: gated content and memberships
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.20
    key: AE-170.70.20
    name: Translation Management & Localization
    url: /capabilities/content-management/
    via_parent: Content Management
  fit: exact
  layer: domain
  why: site translation
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.20
    key: AE-110.30.20
    name: Text-to-Speech
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  fit: exact
  layer: domain
  why: audio versions of posts
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  fit: exact
  layer: domain
  why: 'hosted site search: no BC/AE node fits (gap)'
- capability:
    attribution: API Evangelist extension
    id: AE-931
    key: AE-931
    name: No-Code App Builders
    url: /capabilities/engineering-productivity-management/
    via_parent: Engineering Productivity Management
  fit: exact
  layer: domain
  why: no-code site components
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: paid memberships
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: login/notification email providers
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: media upload storage adapters
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: serverless database adapters
- capability:
    attribution: API Evangelist extension
    id: AE-926
    key: AE-926
    name: Web Hosting & Control Panels
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: static deploys and TLS
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error and AI tracing
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: Zapier/Make/Pipedream
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: Slack notifications
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: support chat widgets
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: Airtable sync
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: common
  why: editorial boards
- capability:
    attribution: API Evangelist extension
    id: AE-160.50
    key: AE-160.50
    name: Consent & Preferences
    url: /capabilities/consent-preferences/
    via_parent: null
  fit: exact
  layer: common
  why: cookie consent banners
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: AI writing assistants and MCP connectors
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
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - Ghost
      - WordPress
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: X (Twitter)
      slug: x
      sources:
      - https://ghost.org/integrations/
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: observed
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Ghost
      - WordPress
      band: developing
      in_catalog: true
      kin_score: 47.7
      mcp:
        source: https://developers.pinterest.com/about-pinterest-mcp/
        status: verified
      name: Pinterest
      slug: pinterest
      sources:
      - https://ghost.org/integrations/
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Image
      - Social
      - Social Media
      - Video
      tier: observed
      url: /providers/pinterest/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - WordPress
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/reddit/devvit-mcp
        status: verified
      name: Reddit
      slug: reddit
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Advertising
      - Community
      - Content
      - Reddit
      tier: observed
      url: /providers/reddit/
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - WordPress
      band: developing
      in_catalog: true
      kin_score: 46.3
      mcp:
        status: none
      name: Bluesky
      slug: bluesky
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - At-Protocol
      - Decentralized
      - Federated
      - Open Source
      tier: observed
      url: /providers/bluesky/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - WordPress
      band: developing
      in_catalog: true
      kin_score: 40.5
      mcp:
        status: none
      name: TikTok
      slug: tiktok
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Advertising
      - Commerce
      - Content
      - TikTok
      tier: observed
      url: /providers/tiktok/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - WordPress
      band: minimal
      in_catalog: true
      kin_score: 8.5
      mcp:
        status: none
      name: Tumblr
      slug: tumblr
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Public APIs
      - Social
      tier: observed
      url: /providers/tumblr/
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
      - Ghost
      band: exemplar
      in_catalog: true
      kin_score: 67.8
      mcp:
        status: none
      name: Instagram
      slug: instagram
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Instagram
      - Meta
      - Photos
      - Social Media
      tier: declared
      url: /providers/instagram/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Ghost
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: declared
      url: /providers/discord/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Ghost
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: declared
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Ghost
      band: thin
      in_catalog: true
      kin_score: 29.5
      mcp:
        status: none
      name: Circle
      slug: circle-community
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Community
      - Courses
      - Creators
      - Membership
      tier: declared
      url: /providers/circle-community/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - Ghost
      - WordPress
      band: strong
      in_catalog: true
      kin_score: 65.4
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://ghost.org/integrations/
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: observed
      url: /providers/youtube/
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - Ghost
      - WordPress
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp:
        source: https://developer.vimeo.com/api/mcp-server
        status: documented
      name: Vimeo
      slug: vimeo
      sources:
      - https://ghost.org/integrations/
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Live Streaming
      - Streaming
      - Video
      - Video Hosting
      tier: observed
      url: /providers/vimeo/
    - agent_band: human-only
      agent_readiness: 4.9
      apps:
      - WordPress
      band: thin
      in_catalog: true
      kin_score: 33.5
      mcp:
        status: none
      name: Animoto
      slug: animoto
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Company
      - Consumer
      - Video
      - Video Creation
      tier: observed
      url: /providers/animoto/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - WordPress
      band: emerging
      in_catalog: true
      kin_score: 15.4
      mcp:
        status: unknown
      name: TED
      slug: ted-com
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Company
      - Education
      - Media
      - Non-Profit
      tier: observed
      url: /providers/ted-com/
    - agent_band: human-only
      agent_readiness: 3.8
      apps:
      - WordPress
      band: minimal
      in_catalog: true
      kin_score: 8.2
      mcp:
        status: none
      name: Dailymotion
      slug: dailymotion
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Public APIs
      - Video
      tier: observed
      url: /providers/dailymotion/
    - agent_band: agent-ready
      agent_readiness: 40.6
      apps:
      - Webflow
      band: exemplar
      in_catalog: true
      kin_score: 75.5
      mcp:
        source: https://docs.wistia.com/docs/mcp-server-guide
        status: documented
      name: Wistia
      slug: wistia
      sources:
      - https://webflow.com/apps/detail/wistia
      status: profiled
      tags:
      - Lead Generation
      - Video Analytics
      - Video Hosting
      - Video Marketing
      tier: declared
      url: /providers/wistia/
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Ghost
      band: developing
      in_catalog: true
      kin_score: 48.2
      mcp:
        status: none
      name: Twitch
      slug: twitch
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Entertainment
      - Gaming
      - Live Streaming
      - Streaming
      tier: declared
      url: /providers/twitch/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Ghost
      band: emerging
      in_catalog: true
      kin_score: 18.4
      mcp:
        status: none
      name: Loom
      slug: loom
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Async
      - Communications
      - Productivity
      - Video
      tier: declared
      url: /providers/loom/
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
      - Ghost
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: declared
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 41.3
      apps:
      - Ghost
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/matomo-org/plugin-McpServer
        status: verified
      name: Matomo
      slug: matomo
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Analytics
      - Open Source
      - Privacy
      - Web Analytics
      tier: declared
      url: /providers/matomo/
    - agent_band: agent-aware
      agent_readiness: 22.6
      apps:
      - Ghost
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        status: none
      name: Plausible
      slug: plausible
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Analytics
      - Cookie-Free
      - Event Tracking
      - GDPR
      tier: declared
      url: /providers/plausible/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - Ghost
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: declared
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 29.9
      apps:
      - Webflow
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://github.com/microsoft/clarity-mcp-server
        status: verified
      name: Microsoft Clarity
      slug: microsoft-clarity
      sources:
      - https://webflow.com/apps/detail/microsoft-clarity
      status: profiled
      tags:
      - Analytics
      - Heatmaps
      - Session Recording
      - Web Analytics
      tier: declared
      url: /providers/microsoft-clarity/
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Ghost
      band: strong
      in_catalog: true
      kin_score: 62.6
      mcp:
        status: none
      name: Simple Analytics
      slug: simpleanalytics
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Analytics
      - Cookieless
      - Privacy
      - Web Analytics
      tier: declared
      url: /providers/simpleanalytics/
    - agent_band: agent-ready
      agent_readiness: 30.3
      apps:
      - Ghost
      band: developing
      in_catalog: true
      kin_score: 47.7
      mcp:
        status: none
      name: Fathom Analytics
      slug: fathom
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Analytics
      - GDPR
      - Privacy
      - Website Analytics
      tier: declared
      url: /providers/fathom/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Ghost
      band: thin
      in_catalog: true
      kin_score: 27.4
      mcp:
        source: https://github.com/wingify/wingify-fme-mcp
        status: verified
      name: VWO
      slug: vwo
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - A/B Testing
      - Conversion Optimization
      - Experimentation
      - Personalization
      tier: declared
      url: /providers/vwo/
    - agent_band: agent-aware
      agent_readiness: 27.3
      apps:
      - Ghost
      band: emerging
      in_catalog: true
      kin_score: 25.5
      mcp:
        status: none
      name: Hotjar
      slug: hotjar
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Analytics
      - Personalization
      - Surveys
      - Tracking
      tier: declared
      url: /providers/hotjar/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20
      key: AE-170.20
      name: Audio & Music
      url: /capabilities/audio-music/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - Ghost
      - WordPress
      band: developing
      in_catalog: true
      kin_score: 50.6
      mcp:
        status: none
      name: Spotify
      slug: spotify
      sources:
      - https://ghost.org/integrations/
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Audio
      - Music
      - Podcasts
      - Streaming
      tier: observed
      url: /providers/spotify/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Ghost
      - WordPress
      band: thin
      in_catalog: true
      kin_score: 30.9
      mcp:
        status: none
      name: SoundCloud
      slug: soundcloud
      sources:
      - https://ghost.org/integrations/
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Audio
      - Music
      - OAuth
      - Streaming
      tier: observed
      url: /providers/soundcloud/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - WordPress
      band: emerging
      in_catalog: true
      kin_score: 20.7
      mcp:
        status: unknown
      name: ReverbNation
      slug: reverbnation
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Artists
      - Distribution
      - Music
      - Promotion
      tier: observed
      url: /providers/reverbnation/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - WordPress
      band: minimal
      in_catalog: true
      kin_score: 9.4
      mcp:
        status: none
      name: Anghami
      slug: anghami
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Middle East
      - Music
      - North-Africa
      - Streaming
      tier: observed
      url: /providers/anghami/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - WordPress
      band: minimal
      in_catalog: true
      kin_score: 7.8
      mcp:
        status: none
      name: Mixcloud
      slug: mixcloud
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Music
      - Public APIs
      tier: observed
      url: /providers/mixcloud/
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - WordPress
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Crowdsignal
      slug: crowdsignal
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Ghost
      band: exemplar
      in_catalog: true
      kin_score: 70.2
      mcp:
        source: https://github.com/jotform/mcp-server
        status: verified
      name: Jotform
      slug: jotform
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Data Collection
      - Forms
      - No-Code
      - Surveys
      tier: declared
      url: /providers/jotform/
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Ghost
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: Wufoo
      slug: wufoo
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Data Collection
      - Form Builder
      - Forms
      - Surveys
      tier: declared
      url: /providers/wufoo/
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - Ghost
      band: thin
      in_catalog: true
      kin_score: 37.8
      mcp:
        status: none
      name: Formspree
      slug: formspree
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Backend
      - Email
      - Forms
      - Static Sites
      tier: declared
      url: /providers/formspree/
    - agent_band: agent-ready
      agent_readiness: 42.6
      apps:
      - Ghost
      band: thin
      in_catalog: true
      kin_score: 36.0
      mcp:
        source: https://www.typeform.com/developers/mcp
        status: verified
      name: Typeform
      slug: typeform
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Forms
      - Lead Capture
      - Software-as-a-Service
      - Surveys
      tier: declared
      url: /providers/typeform/
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Ghost
      band: thin
      in_catalog: true
      kin_score: 34.9
      mcp:
        source: https://www.surveymonkey.com/apps/
        status: documented
      name: SurveyMonkey
      slug: surveymonkey
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Feedback
      - Market Research
      - NPS
      - Surveys
      tier: declared
      url: /providers/surveymonkey/
    - agent_band: agent-ready
      agent_readiness: 48.8
      apps:
      - Ghost
      band: thin
      in_catalog: true
      kin_score: 29.8
      mcp:
        source: https://tally.so/help/mcp
        status: verified
      name: Tally
      slug: tally
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Forms
      - Free
      - No-Code
      - Surveys
      tier: declared
      url: /providers/tally/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    providers:
    - agent_band: agent-native
      agent_readiness: 53.6
      apps:
      - WordPress
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Amazon Kindle Instant Preview
      slug: amazon
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: observed
      url: /providers/amazon/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - WordPress
      band: thin
      in_catalog: true
      kin_score: 36.2
      mcp:
        source: https://www.wolfram.com/artificial-intelligence/mcp/cloud/
        status: verified
      name: Wolfram Cloud
      slug: wolframalpha
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Artificial Intelligence
      - Computational Knowledge
      - Machine Learning
      - Natural Language Processing
      tier: observed
      url: /providers/wolframalpha/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - WordPress
      band: emerging
      in_catalog: true
      kin_score: 21.6
      mcp:
        status: unknown
      name: Speaker Deck
      slug: speakerdeck
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Company
      - Presentation
      - Sharing
      - Slides
      tier: observed
      url: /providers/speakerdeck/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - WordPress
      band: emerging
      in_catalog: true
      kin_score: 16.6
      mcp:
        status: none
      name: Scribd
      slug: scribd
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Audiobooks
      - Company
      - Documents
      - Ebooks
      tier: observed
      url: /providers/scribd/
    - agent_band: null
      agent_readiness: null
      apps:
      - WordPress
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Issuu
      slug: issuu
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: queued for profiling
      tags: []
      tier: observed
      url: null
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
      - Ghost
      - Webflow
      band: developing
      in_catalog: true
      kin_score: 39.4
      mcp:
        status: none
      name: Unsplash
      slug: unsplash
      sources:
      - https://ghost.org/integrations/
      - https://webflow.com/apps/detail/unsplash
      status: profiled
      tags:
      - Image
      - Photography
      - Photos
      - Stock Photos
      tier: declared
      url: /providers/unsplash/
    - agent_band: agent-aware
      agent_readiness: 25.1
      apps:
      - WordPress
      band: developing
      in_catalog: true
      kin_score: 49.1
      mcp:
        status: none
      name: Flickr
      slug: flickr
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Photography
      - Photos
      - Public APIs
      - Social Media
      tier: observed
      url: /providers/flickr/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - WordPress
      band: thin
      in_catalog: true
      kin_score: 32.8
      mcp:
        status: none
      name: SmugMug
      slug: smugmug
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Cloud Storage
      - E-Commerce
      - Photo Sharing
      - Photography
      tier: observed
      url: /providers/smugmug/
    - agent_band: null
      agent_readiness: null
      apps:
      - WordPress
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Cloudup
      slug: cloudup
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: queued for profiling
      tags: []
      tier: observed
      url: null
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
      - WordPress
      band: exemplar
      in_catalog: true
      kin_score: 87.3
      mcp:
        source: https://www.canva.dev/docs/mcp/
        status: verified
      name: Canva
      slug: canva
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Application
      - Automation
      - Brand Management
      - Collaboration
      tier: observed
      url: /providers/canva/
    - agent_band: agent-ready
      agent_readiness: 59.2
      apps:
      - Webflow
      band: exemplar
      in_catalog: true
      kin_score: 75.1
      mcp:
        source: https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server
        status: verified
      name: Figma
      slug: figma
      sources:
      - https://webflow.com/apps/detail/figma
      status: profiled
      tags:
      - Collaboration
      - Design
      - Graphics
      - Interfaces
      tier: declared
      url: /providers/figma/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Webflow
      band: thin
      in_catalog: true
      kin_score: 30.1
      mcp:
        source: https://relume.ai/mcp
        status: verified
      name: Relume
      slug: relume
      sources:
      - https://webflow.com/apps/detail/relume
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Marketing
      - Website Builder
      tier: declared
      url: /providers/relume/
    - agent_band: agent-aware
      agent_readiness: 12.0
      apps:
      - Webflow
      band: emerging
      in_catalog: true
      kin_score: 16.6
      mcp:
        status: unknown
      name: LottieFiles
      slug: lottiefiles
      sources:
      - https://webflow.com/apps/detail/lottiefiles
      status: profiled
      tags:
      - Animation
      - Company
      - Design
      - Motion Graphics
      tier: declared
      url: /providers/lottiefiles/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Ghost
      band: exemplar
      in_catalog: true
      kin_score: 80.4
      mcp:
        status: none
      name: Kit (ConvertKit)
      slug: convertkit
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Automation
      - Creator Economy
      - Email Marketing
      - Subscribers
      tier: declared
      url: /providers/convertkit/
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Ghost
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - Ghost
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp:
        source: https://developers.mailerlite.com/
        status: documented
      name: MailerLite
      slug: mailerlite
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Automation
      - Email Marketing
      - Newsletters
      - Subscribers
      tier: declared
      url: /providers/mailerlite/
    - agent_band: agent-ready
      agent_readiness: 34.6
      apps:
      - Ghost
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: EmailOctopus
      slug: emailoctopus
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Campaigns
      - Email
      - Email Marketing
      - Newsletters
      tier: declared
      url: /providers/emailoctopus/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.10
      key: AE-170.30.10
      name: Image Processing & Optimisation
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.5
      apps:
      - Directus
      - Ghost
      - Strapi
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://cloudinary.com/documentation/cloudinary_llm_mcp
        status: verified
      name: Cloudinary
      slug: cloudinary
      sources:
      - https://ghost.org/integrations/
      - https://github.com/directus/directus/blob/main/api/package.json
      - https://github.com/strapi/strapi/tree/develop/packages/providers/upload-cloudinary
      status: profiled
      tags:
      - Asset Management
      - Digital Asset Management
      - Image Processing
      - Image Transformation
      tier: observed
      url: /providers/cloudinary/
    - agent_band: agent-aware
      agent_readiness: 26.0
      apps:
      - Ghost
      band: developing
      in_catalog: true
      kin_score: 50.2
      mcp:
        source: https://placid.app/docs/2.0/mcp/introduction
        status: verified
      name: Placid
      slug: placid
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Automation
      - Creative
      - Image Generation
      - No-Code
      tier: declared
      url: /providers/placid/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.20
      key: AE-170.20.20
      name: Podcast Hosting
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - WordPress
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Pocket Casts
      slug: pocket-casts
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 44.5
      apps:
      - Ghost
      band: strong
      in_catalog: true
      kin_score: 55.4
      mcp:
        status: none
      name: Listen Notes
      slug: listennotes
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Podcast Directory
      - Podcast Search
      - Podcasts
      - Search
      tier: declared
      url: /providers/listennotes/
    - agent_band: agent-ready
      agent_readiness: 50.0
      apps:
      - Ghost
      band: developing
      in_catalog: true
      kin_score: 39.8
      mcp:
        source: https://mcp.transistor.fm/
        status: verified
      name: Transistor
      slug: transistor
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Analytics
      - Media
      - Podcast Hosting
      - Podcasts
      tier: declared
      url: /providers/transistor/
    - agent_band: agent-aware
      agent_readiness: 27.2
      apps:
      - Ghost
      band: thin
      in_catalog: true
      kin_score: 29.6
      mcp:
        status: none
      name: Captivate
      slug: captivate-fm
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Episodes
      - Media
      - Podcast Hosting
      - Podcasts
      tier: declared
      url: /providers/captivate-fm/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.40
      key: AE-170.40
      name: Creator Monetisation
      url: /capabilities/creator-monetisation/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - WordPress
      band: emerging
      in_catalog: true
      kin_score: 13.1
      mcp:
        status: none
      name: Kickstarter
      slug: kickstarter
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
      status: profiled
      tags:
      - Company
      - Consumer
      - Crowdfunding
      - Fundraising
      tier: observed
      url: /providers/kickstarter/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Ghost
      band: thin
      in_catalog: true
      kin_score: 33.1
      mcp:
        status: none
      name: Patreon
      slug: patreon
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Content
      - Creator Economy
      - Membership
      - Subscription
      tier: declared
      url: /providers/patreon/
    - agent_band: agent-aware
      agent_readiness: 16.5
      apps:
      - Ghost
      band: emerging
      in_catalog: true
      kin_score: 22.8
      mcp:
        status: none
      name: Gumroad
      slug: gumroad
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Creator Economy
      - Digital Commerce
      - Digital Products
      - Membership
      tier: declared
      url: /providers/gumroad/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.1
      apps:
      - Webflow
      band: exemplar
      in_catalog: true
      kin_score: 73.4
      mcp:
        source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
        status: verified
      name: Google Ads
      slug: google-ads
      sources:
      - https://webflow.com/apps/detail/google-ads
      status: profiled
      tags:
      - Advertising
      - Campaign Management
      - Digital Advertising
      - Google
      tier: declared
      url: /providers/google-ads/
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - Ghost
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        status: none
      name: Google Search Console
      slug: google-search-console
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Analytics
      - Google
      - Indexing
      - Search
      tier: declared
      url: /providers/google-search-console/
    - agent_band: agent-native
      agent_readiness: 40.5
      apps:
      - Ghost
      band: developing
      in_catalog: true
      kin_score: 53.7
      mcp:
        status: none
      name: Google AdSense
      slug: google-adsense
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Ad Units
      - AdSense
      - Advertising
      - Monetization
      tier: declared
      url: /providers/google-adsense/
  - capability:
      attribution: Turbo EA
      id: BC-400.50
      key: marketing-operations-management
      name: Marketing Operations Management
      url: /capabilities/marketing-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.0
      apps:
      - Ghost
      band: exemplar
      in_catalog: true
      kin_score: 81.1
      mcp:
        source: https://developers.activecampaign.com/page/mcp
        status: documented
      name: ActiveCampaign
      slug: activecampaign
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - CRM
      - Email Marketing
      - Marketing Automation
      - Sales Automation
      tier: declared
      url: /providers/activecampaign/
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Ghost
      band: strong
      in_catalog: true
      kin_score: 63.9
      mcp:
        status: none
      name: Drip
      slug: drip
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Customer Engagement
      - E-Commerce
      - Email Marketing
      - Marketing Automation
      tier: declared
      url: /providers/drip/
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - Webflow
      band: strong
      in_catalog: true
      kin_score: 57.2
      mcp:
        status: none
      name: Adobe Marketo Engage
      slug: marketo
      sources:
      - https://webflow.com/apps/detail/adobe-marketo-engage
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
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Ghost
      - Webflow
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://ghost.org/integrations/
      - https://webflow.com/apps/detail/hubspot
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.30
      key: AE-170.50.30
      name: Embedded Comments
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Ghost
      band: thin
      in_catalog: true
      kin_score: 37.5
      mcp:
        status: none
      name: Disqus
      slug: disqus
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Comments
      - Community
      - Discussions
      - Publishing
      tier: declared
      url: /providers/disqus/
    - agent_band: agent-aware
      agent_readiness: 20.3
      apps:
      - Ghost
      band: thin
      in_catalog: true
      kin_score: 36.9
      mcp:
        source: https://github.com/discourse/discourse-mcp
        status: verified
      name: Discourse
      slug: discourse
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Community
      - Forums
      - Open Source
      tier: declared
      url: /providers/discourse/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.8
      apps:
      - Ghost
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify
      slug: shopify
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: declared
      url: /providers/shopify/
    - agent_band: agent-ready
      agent_readiness: 30.9
      apps:
      - Ghost
      band: thin
      in_catalog: true
      kin_score: 36.2
      mcp:
        status: none
      name: Snipcart
      slug: snipcart
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - E-Commerce
      - Order
      - Product
      - Shopping Cart
      tier: declared
      url: /providers/snipcart/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.30
      key: AE-170.60.30
      name: Newsletters
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Ghost
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp: &id001
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://github.com/TryGhost/Ghost/blob/main/ghost/package.json
      status: profiled
      tags: &id002
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailgun/
    - agent_band: agent-native
      agent_readiness: 41.9
      apps:
      - Ghost
      band: exemplar
      in_catalog: true
      kin_score: 70.0
      mcp:
        status: none
      name: Buttondown
      slug: buttondown
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Analytics
      - Automation
      - Email
      - Markdown
      tier: declared
      url: /providers/buttondown/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.20
      key: AE-170.70.20
      name: Translation Management & Localization
      url: /capabilities/content-management/
      via_parent: Content Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.3
      apps:
      - Ghost
      band: thin
      in_catalog: true
      kin_score: 35.9
      mcp:
        source: https://help.transifex.com/en/articles/15970082-transifex-mcp-server
        status: documented
      name: Transifex
      slug: transifex
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - L10n
      - Localization
      - Translation
      - i18n
      tier: declared
      url: /providers/transifex/
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Ghost
      band: thin
      in_catalog: true
      kin_score: 33.3
      mcp:
        status: none
      name: Weglot
      slug: weglot
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Internationalization
      - Localization
      - Machine Translation
      - Translation
      tier: declared
      url: /providers/weglot/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Ghost
      band: developing
      in_catalog: true
      kin_score: 46.4
      mcp:
        source: https://www.tinybird.co/docs/forward/analytics-agents/mcp
        status: verified
      name: Tinybird
      slug: tinybird
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Analytics
      - Data
      - Real-Time
      - SQL
      tier: declared
      url: /providers/tinybird/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Ghost
      band: strong
      in_catalog: true
      kin_score: 56.0
      mcp:
        status: none
      name: GIPHY
      slug: giphy
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - GIFs
      - Media
      - Photography
      - Stickers
      tier: declared
      url: /providers/giphy/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Ghost
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: GatherContent
      slug: gathercontent
      sources:
      - https://ghost.org/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Ghost
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Twilio Segment
      slug: segment
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: declared
      url: /providers/segment/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.40.20
      key: AE-140.40.20
      name: Memberships
      url: /capabilities/d2c-subscriptions/
      via_parent: D2C Subscriptions
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.6
      apps:
      - Webflow
      band: developing
      in_catalog: true
      kin_score: 41.5
      mcp:
        source: https://developers.memberstack.com/mcp-server
        status: verified
      name: Memberstack
      slug: memberstack
      sources:
      - https://webflow.com/apps/detail/memberstack
      status: profiled
      tags:
      - Authentication
      - Membership
      - Software-as-a-Service
      - Webflow
      tier: declared
      url: /providers/memberstack/
  - capability:
      attribution: API Evangelist extension
      id: AE-931
      key: AE-931
      name: No-Code App Builders
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - Webflow
      band: emerging
      in_catalog: true
      kin_score: 25.2
      mcp:
        status: none
      name: Finsweet
      slug: finsweet
      sources:
      - https://webflow.com/apps/detail/finsweet
      status: profiled
      tags:
      - Agency
      - Design
      - Development
      - Webflow
      tier: declared
      url: /providers/finsweet/
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 61.9
      apps:
      - Webflow
      band: exemplar
      in_catalog: true
      kin_score: 81.1
      mcp:
        status: none
      name: Algolia
      slug: algolia
      sources:
      - https://webflow.com/apps/detail/algolia
      status: profiled
      tags:
      - Discovery
      - Personalization
      - Recommendations
      - Search
      tier: declared
      url: /providers/algolia/
  - capability:
      attribution: API Evangelist extension
      id: AE-914
      key: AE-914
      name: Social Listening & Analytics
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - Ghost
      band: strong
      in_catalog: true
      kin_score: 65.9
      mcp:
        status: none
      name: Buffer
      slug: buffer
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Analytics
      - Publishing
      - Scheduling
      - Social Media
      tier: declared
      url: /providers/buffer/
  - capability:
      attribution: Turbo EA
      id: BC-4250.70
      key: subscription-revenue-analytics
      name: Subscription Revenue Analytics
      url: /capabilities/subscription-revenue-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.6
      apps:
      - Ghost
      band: developing
      in_catalog: true
      kin_score: 40.5
      mcp:
        source: https://github.com/chartmogul/chartmogul-mcp-server
        status: verified
      name: ChartMogul
      slug: chartmogul
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - MRR
      - Revenue Analytics
      - SaaS Metrics
      - Subscription Analytics
      tier: declared
      url: /providers/chartmogul/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.2
      apps:
      - Ghost
      band: developing
      in_catalog: true
      kin_score: 40.7
      mcp:
        source: https://docs.beyondwords.io/docs-and-guides/support/beyondwords-mcp
        status: verified
      name: BeyondWords
      slug: beyondwords
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Audio
      - CMS
      - Publishing
      tier: declared
      url: /providers/beyondwords/
  layer: domain
- capabilities:
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
      - Directus
      - Ghost
      - Payload
      - Strapi
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://ghost.org/integrations/
      - https://github.com/directus/directus/blob/main/api/package.json
      - https://github.com/payloadcms/payload/tree/main/packages/storage-s3
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
      - Directus
      - Ghost
      - Payload
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://ghost.org/integrations/
      - https://github.com/directus/directus/blob/main/api/package.json
      - https://github.com/payloadcms/payload/tree/main/packages/storage-gcs
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Directus
      - Payload
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://github.com/directus/directus/blob/main/api/package.json
      - https://github.com/payloadcms/payload/tree/main/packages/storage-azure
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
    - agent_band: agent-ready
      agent_readiness: 48.2
      apps:
      - Directus
      band: developing
      in_catalog: true
      kin_score: 49.4
      mcp:
        source: https://github.com/supabase/mcp
        status: verified
      name: Supabase Storage
      slug: supabase
      sources:
      - https://github.com/directus/directus/blob/main/api/package.json
      status: profiled
      tags:
      - Authentication
      - Backend-as-a-Service
      - Open Source
      - PostgreSQL
      tier: observed
      url: /providers/supabase/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Payload
      band: thin
      in_catalog: true
      kin_score: 35.8
      mcp:
        source: https://raw.githubusercontent.com/cloudflare/mcp/main/README.md
        status: verified
      name: Cloudflare R2
      slug: cloudflare-r2
      sources:
      - https://github.com/payloadcms/payload/tree/main/packages/storage-r2
      status: profiled
      tags:
      - Cloud Storage
      - Egress-Free
      - Object Storage
      - S3 Compatible
      tier: observed
      url: /providers/cloudflare-r2/
    - agent_band: agent-aware
      agent_readiness: 27.4
      apps:
      - Ghost
      band: developing
      in_catalog: true
      kin_score: 49.6
      mcp:
        source: https://github.com/backblaze-labs/b2-mcp
        status: verified
      name: Backblaze B2
      slug: backblaze
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Backup
      - Cloud Storage
      - Object Storage
      - Storage
      tier: declared
      url: /providers/backblaze/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - Directus
      - Strapi
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        status: none
      name: Amazon SES
      slug: amazon-ses
      sources:
      - https://github.com/directus/directus/blob/main/api/package.json
      - https://github.com/strapi/strapi/tree/develop/packages/providers/email-amazon-ses
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - Strapi
      band: exemplar
      in_catalog: true
      kin_score: 84.0
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://github.com/strapi/strapi/tree/develop/packages/providers/email-sendgrid
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-ready
      agent_readiness: 49.8
      apps:
      - Payload
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        source: https://resend.com/docs/mcp-server
        status: verified
      name: Resend
      slug: resend
      sources:
      - https://github.com/payloadcms/payload/tree/main/packages/email-resend
      status: profiled
      tags:
      - Developer Tools
      - Email
      - Marketing Email
      - Transactional Email
      tier: observed
      url: /providers/resend/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Strapi
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp: *id001
      name: Mailgun
      slug: mailgun
      sources:
      - https://github.com/strapi/strapi/tree/develop/packages/providers/email-mailgun
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/mailgun/
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
      - Ghost
      - Webflow
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://ghost.org/integrations/
      - https://webflow.com/apps/detail/zapier
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 31.1
      apps:
      - Ghost
      band: strong
      in_catalog: true
      kin_score: 65.5
      mcp:
        source: https://pipedream.com/docs/connect/mcp
        status: verified
      name: Pipedream
      slug: pipedream
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Connect
      - Pipedream
      - Pro-Code-API-Composition
      - Workflows
      tier: declared
      url: /providers/pipedream/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Webflow
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://webflow.com/apps/detail/make
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
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - Ghost
      band: developing
      in_catalog: true
      kin_score: 51.5
      mcp:
        status: none
      name: Help Scout
      slug: helpscout
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Customer Service
      - Email
      - Help Desk
      - Live Chat
      tier: declared
      url: /providers/helpscout/
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Ghost
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: declared
      url: /providers/intercom/
    - agent_band: agent-ready
      agent_readiness: 47.2
      apps:
      - Ghost
      band: thin
      in_catalog: true
      kin_score: 31.3
      mcp:
        status: none
      name: LiveChat
      slug: livechat
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Customer Service
      - Live Chat
      - Messaging
      - Sales
      tier: declared
      url: /providers/livechat/
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
      - Ghost
      - Payload
      - WordPress
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/TryGhost/Ghost/blob/main/ghost/package.json
      - https://github.com/payloadcms/payload/tree/main/packages/plugin-sentry
      - https://reports.exodus-privacy.eu.org/en/reports/org.wordpress.android/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
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
      - Ghost
      - Payload
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/TryGhost/Ghost/blob/main/ghost/package.json
      - https://github.com/payloadcms/payload/tree/main/packages/plugin-stripe
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
      - Ghost
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: declared
      url: /providers/paypal/
  - capability:
      attribution: API Evangelist extension
      id: AE-926
      key: AE-926
      name: Web Hosting & Control Panels
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 58.9
      apps:
      - Directus
      - Ghost
      band: exemplar
      in_catalog: true
      kin_score: 72.2
      mcp:
        source: https://github.com/netlify/netlify-mcp
        status: verified
      name: Netlify
      slug: netlify
      sources:
      - https://ghost.org/integrations/
      - https://github.com/directus/directus/blob/main/api/package.json
      status: profiled
      tags:
      - CDN
      - Cloud
      - Continuous Deployment
      - Developer Tools
      tier: observed
      url: /providers/netlify/
    - agent_band: agent-aware
      agent_readiness: 16.8
      apps:
      - Ghost
      band: emerging
      in_catalog: true
      kin_score: 23.7
      mcp:
        status: none
      name: Let's Encrypt
      slug: lets-encrypt
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Certificates
      - Linux Foundation
      - Security
      - TLS
      tier: declared
      url: /providers/lets-encrypt/
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
      - Ghost
      - Webflow
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://ghost.org/integrations/
      - https://webflow.com/apps/detail/slack
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.0
      apps:
      - Payload
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp:
        source: https://vercel.com/docs/mcp/vercel-mcp
        status: verified
      name: Vercel Postgres / Blob
      slug: vercel
      sources:
      - https://github.com/payloadcms/payload/tree/main/packages/db-vercel-postgres
      status: profiled
      tags:
      - AI Gateway
      - Gateways
      - Observability
      - Webhook
      tier: observed
      url: /providers/vercel/
    - agent_band: agent-ready
      agent_readiness: 30.3
      apps:
      - Payload
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        source: https://github.com/cloudflare/mcp-server-cloudflare
        status: verified
      name: Cloudflare D1
      slug: cloudflare-d1
      sources:
      - https://github.com/payloadcms/payload/tree/main/packages/db-d1-sqlite
      status: profiled
      tags:
      - Database
      - Edge Computing
      - SQLite
      - Serverless
      tier: observed
      url: /providers/cloudflare-d1/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - Ghost
      band: thin
      in_catalog: true
      kin_score: 35.2
      mcp:
        source: https://www.geckoboard.com/product/metrics-mcp/
        status: verified
      name: Geckoboard
      slug: geckoboard
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Business Intelligence
      - Dashboards
      - Data Visualization
      - KPI Tracking
      tier: declared
      url: /providers/geckoboard/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - WordPress
      band: developing
      in_catalog: true
      kin_score: 41.2
      mcp:
        source: https://github.com/Automattic/mcp-server-gravatar
        status: verified
      name: Gravatar
      slug: gravatar
      sources:
      - https://github.com/WordPress/WordPress/blob/master/wp-includes/pluggable.php
      status: profiled
      tags:
      - Avatars
      - Identity
      - Profiles
      - Social
      tier: observed
      url: /providers/gravatar/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.50
      key: AE-160.50
      name: Consent & Preferences
      url: /capabilities/consent-preferences/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.3
      apps:
      - Ghost
      band: thin
      in_catalog: true
      kin_score: 31.9
      mcp:
        status: none
      name: CookieYes
      slug: cookieyes
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Company
      - Consent Management
      - GDPR
      - Privacy
      tier: declared
      url: /providers/cookieyes/
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
      - Ghost
      band: exemplar
      in_catalog: true
      kin_score: 74.8
      mcp:
        source: https://github.com/atlassian/trello-mcp-server
        status: verified
      name: Trello
      slug: trello
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Collaboration
      - Kanban
      - Project Management
      - Task Management
      tier: declared
      url: /providers/trello/
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - Ghost
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://github.com/Airtable/airtable-mcp-cli
        status: verified
      name: Airtable
      slug: airtable
      sources:
      - https://ghost.org/integrations/
      status: profiled
      tags:
      - Application
      - Collaboration
      - Data
      - Database
      tier: declared
      url: /providers/airtable/
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
      - Directus
      - Webflow
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/directus/directus/blob/main/api/package.json
      - https://webflow.com/apps/detail/claude
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Directus
      - Webflow
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://github.com/directus/directus/blob/main/api/package.json
      - https://webflow.com/apps/detail/google-gemini
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Directus
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/directus/directus/blob/main/api/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.7
      apps:
      - Directus
      band: developing
      in_catalog: true
      kin_score: 46.3
      mcp:
        source: https://www.braintrust.dev/docs/integrations/developer-tools/mcp
        status: verified
      name: Braintrust
      slug: braintrust
      sources:
      - https://github.com/directus/directus/blob/main/api/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Evaluation
      - LLM
      - Observability
      tier: observed
      url: /providers/braintrust/
    - agent_band: agent-ready
      agent_readiness: 35.9
      apps:
      - Directus
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        source: https://github.com/langfuse/mcp-server-langfuse
        status: verified
      name: Langfuse
      slug: langfuse
      sources:
      - https://github.com/directus/directus/blob/main/api/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - LLM
      - Observability
      - Open Source
      tier: observed
      url: /providers/langfuse/
  layer: agent
summary:
  coverage_pct: 95.9
  declared_only: 74
  distinct_providers: 123
  in_catalog: 118
  mcp:
    documented: 6
    none: 54
    unchecked: 5
    verified: 54
  mcp_verified: 54
  mean_kin_score: 50.7
  observed: 49
  queued: 5
  reference_apps: 6
title: 'Website Builder, CMS & Blogging: application blueprint'
---
