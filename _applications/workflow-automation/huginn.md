---
app: Huginn
app_slug: huginn
app_url: https://github.com/huginn/huginn
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.60.40
  key: AE-170.60.40
  layer: domain
  name: Bookmarks, Read-Later & Feed Readers
  providers:
  - Raindrop.io (bookmarks)
  url: /capabilities/news-publishing/
  via_parent: News & Publishing
- attribution: API Evangelist extension
  id: AE-100.10.30
  key: AE-100.10.30
  layer: domain
  name: Browser & Computer-Use Automation
  providers:
  - PhantomJS Cloud
  url: /capabilities/agent-tool-exposure/
  via_parent: Agent Tool Exposure
- attribution: API Evangelist extension
  id: AE-210.50
  key: AE-210.50
  layer: domain
  name: Event Ticketing
  providers:
  - StubHub
  url: /capabilities/event-ticketing/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: domain
  name: Internal Communications Management
  providers:
  - HipChat
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830
  key: knowledge-management
  layer: domain
  name: Knowledge Management
  providers:
  - Evernote
  url: /capabilities/knowledge-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40
  key: AE-110.40
  layer: domain
  name: Language & Document Understanding
  providers:
  - Wit.ai
  url: /capabilities/language-document-understanding/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: domain
  name: Machine Translation
  providers:
  - Google Translate
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Gmail (gmail_xoauth)
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - Jira
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-210.30.40
  key: AE-210.30.40
  layer: domain
  name: Public Transit Data
  providers:
  - NextBus (public transport agent)
  url: /capabilities/ground-transport/
  via_parent: Ground Transport
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: domain
  name: Push Notifications
  providers:
  - Pushbullet
  - Pushover
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: domain
  name: SMS
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-2510.20
  key: shipment-tracking-management
  layer: domain
  name: Shipment Tracking Management
  providers:
  - AfterShip
  url: /capabilities/shipment-tracking-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - Threads (Meta)
  - Tumblr
  - Twitter / X
  - Weibo
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.10
  key: AE-230.10
  layer: domain
  name: Weather & Environment
  providers:
  - Pirate Weather (pirate_weather_forecast_ruby)
  url: /capabilities/weather-environment/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: domain
  name: WhatsApp & OTT Messaging
  providers:
  - Telegram
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Dropbox
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3 (aws-sdk-s3)
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - OpenAI (LLM, image, speech, video agents)
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: workflow-automation
  name: Workflow Automation & iPaaS
  url: /applications/workflow-automation/
counts:
  declared: 0
  observed: 25
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/huginn/huginn/blob/master/Gemfile
- route: source code
  url: https://github.com/huginn/huginn/tree/master/app/models/agents
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2510.20
    key: shipment-tracking-management
    name: Shipment Tracking Management
    url: /capabilities/shipment-tracking-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 60.4
    band: exemplar
    in_catalog: true
    kin_score: 84.1
    mcp: &id001
      source: https://github.com/AfterShip/tracking-and-returns-mcp
      status: verified
    slug: aftership
    status: profiled
    tags: &id002
    - E-Commerce
    - Post-Purchase
    - Shipping
    - Tracking
    url: /providers/aftership/
  layer: domain
  name: AfterShip
  provider: aftership
  says: ships the AfterShip SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
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
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3 (aws-sdk-s3)
  provider: amazon-s3
  says: ships the Amazon S3 (aws-sdk-s3) SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.8
    band: developing
    in_catalog: true
    kin_score: 47.9
    mcp: &id005
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id006
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: common
  name: Dropbox
  provider: dropbox
  says: ships the Dropbox SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.6
    band: developing
    in_catalog: true
    kin_score: 51.2
    mcp: &id007
      source: https://dev.evernote.com/
      status: documented
    slug: evernote
    status: profiled
    tags: &id008
    - Company
    - Knowledge Management
    - Note Taking
    - Productivity
    url: /providers/evernote/
  layer: domain
  name: Evernote
  provider: evernote
  says: ships the Evernote SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
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
    mcp: &id009
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id010
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: domain
  name: Gmail (gmail_xoauth)
  provider: google-gmail
  says: ships the Gmail (gmail_xoauth) SDK or integration code
  source: https://github.com/huginn/huginn/blob/master/Gemfile
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
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id011
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id012
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: domain
  name: Google Calendar
  provider: google-calendar
  says: ships the Google Calendar SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.9
    band: developing
    in_catalog: true
    kin_score: 51.6
    mcp: &id013
      status: none
    slug: google-translate
    status: profiled
    tags: &id014
    - Google Cloud
    - Internationalization
    - Language Detection
    - Localization
    url: /providers/google-translate/
  layer: domain
  name: Google Translate
  provider: google-translate
  says: ships the Google Translate SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.0
    mcp: &id015
      status: none
    slug: hipchat
    status: profiled
    tags: &id016
    - Chat
    - Collaboration
    - Messaging
    - Team Communication
    url: /providers/hipchat/
  layer: domain
  name: HipChat
  provider: hipchat
  says: ships the HipChat SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 65.7
    band: exemplar
    in_catalog: true
    kin_score: 82.6
    mcp: &id017
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id018
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: domain
  name: Jira
  provider: jira
  says: ships the Jira SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.40
    key: AE-210.30.40
    name: Public Transit Data
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id019
      status: unchecked
    slug: nextbus
    status: queued for profiling
    tags: &id020 []
    url: null
  layer: domain
  name: NextBus (public transport agent)
  provider: nextbus
  says: ships the NextBus (public transport agent) SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id021
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id022
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI (LLM, image, speech, video agents)
  provider: openai
  says: ships the OpenAI (LLM, image, speech, video agents) SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-100.10.30
    key: AE-100.10.30
    name: Browser & Computer-Use Automation
    url: /capabilities/agent-tool-exposure/
    via_parent: Agent Tool Exposure
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.2
    mcp: &id023
      status: unknown
    slug: phantomjscloud
    status: profiled
    tags: &id024
    - Automation
    - Browser API
    - Rendering
    - Web Scraping
    url: /providers/phantomjscloud/
  layer: domain
  name: PhantomJS Cloud
  provider: phantomjscloud
  says: ships the PhantomJS Cloud SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: AE-230.10
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.3
    mcp: &id025
      source: https://pirateweather.net/
      status: documented
    slug: pirate-weather
    status: profiled
    tags: &id026
    - Public APIs
    - Weather
    url: /providers/pirate-weather/
  layer: domain
  name: Pirate Weather (pirate_weather_forecast_ruby)
  provider: pirate-weather
  says: ships the Pirate Weather (pirate_weather_forecast_ruby) SDK or integration code
  source: https://github.com/huginn/huginn/blob/master/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.9
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id027
      status: none
    slug: pushbullet
    status: profiled
    tags: &id028
    - Device Sync
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushbullet/
  layer: domain
  name: Pushbullet
  provider: pushbullet
  says: ships the Pushbullet SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.0
    band: thin
    in_catalog: true
    kin_score: 29.2
    mcp: &id029
      status: none
    slug: pushover
    status: profiled
    tags: &id030
    - Alerts
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushover/
  layer: domain
  name: Pushover
  provider: pushover
  says: ships the Pushover SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.6
    band: emerging
    in_catalog: true
    kin_score: 17.1
    mcp: &id031
      source: https://help.raindrop.io/integrations/mcp
      status: verified
    slug: raindrop-io
    status: profiled
    tags: &id032
    - Bookmark
    - Cloud
    - Collaboration
    - Productivity
    url: /providers/raindrop-io/
  layer: domain
  name: Raindrop.io (bookmarks)
  provider: raindrop-io
  says: ships the Raindrop.io (bookmarks) SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
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
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id033
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id034
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-210.50
    key: AE-210.50
    name: Event Ticketing
    url: /capabilities/event-ticketing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 51.8
    mcp: &id035
      status: none
    slug: stubhub
    status: profiled
    tags: &id036
    - Company
    - Event
    - Marketplace
    - Ticketing
    url: /providers/stubhub/
  layer: domain
  name: StubHub
  provider: stubhub
  says: ships the StubHub SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.4
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id037
      status: none
    slug: telegram
    status: profiled
    tags: &id038
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: domain
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id039
      status: none
    slug: facebook
    status: profiled
    tags: &id040
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Threads (Meta)
  provider: facebook
  says: ships the Threads (Meta) SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.9
    mcp: &id041
      status: none
    slug: tumblr
    status: profiled
    tags: &id042
    - Public APIs
    - Social
    url: /providers/tumblr/
  layer: domain
  name: Tumblr
  provider: tumblr
  says: ships the Tumblr SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
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
    mcp: &id043
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id044
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: domain
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 61.2
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id045
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id046
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: Twitter / X
  provider: x
  says: ships the Twitter / X SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 6.2
    mcp: &id047
      status: none
    slug: weibo
    status: profiled
    tags: &id048
    - China
    - Company
    - Microblogging
    - Social Media
    url: /providers/weibo/
  layer: domain
  name: Weibo
  provider: weibo
  says: ships the Weibo SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40
    key: AE-110.40
    name: Language & Document Understanding
    url: /capabilities/language-document-understanding/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 23.8
    mcp: &id049
      status: none
    slug: witai
    status: profiled
    tags: &id050
    - Company
    - Natural Language Processing
    - Speech Recognition
    - Speech-to-Text
    url: /providers/witai/
  layer: domain
  name: Wit.ai
  provider: witai
  says: ships the Wit.ai SDK or integration code
  source: https://github.com/huginn/huginn/tree/master/app/models/agents
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/workflow-automation/huginn/
providers:
- agent_band: agent-ready
  agent_readiness: 60.4
  band: exemplar
  in_catalog: true
  kin_score: 84.1
  mcp: *id001
  name: AfterShip
  slug: aftership
  status: profiled
  tags: *id002
  url: /providers/aftership/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id003
  name: Amazon S3 (aws-sdk-s3)
  slug: amazon-s3
  status: profiled
  tags: *id004
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id005
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id006
  url: /providers/dropbox/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: developing
  in_catalog: true
  kin_score: 51.2
  mcp: *id007
  name: Evernote
  slug: evernote
  status: profiled
  tags: *id008
  url: /providers/evernote/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id009
  name: Gmail (gmail_xoauth)
  slug: google-gmail
  status: profiled
  tags: *id010
  url: /providers/google-gmail/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id011
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id012
  url: /providers/google-calendar/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: developing
  in_catalog: true
  kin_score: 51.6
  mcp: *id013
  name: Google Translate
  slug: google-translate
  status: profiled
  tags: *id014
  url: /providers/google-translate/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.0
  mcp: *id015
  name: HipChat
  slug: hipchat
  status: profiled
  tags: *id016
  url: /providers/hipchat/
- agent_band: agent-ready
  agent_readiness: 65.7
  band: exemplar
  in_catalog: true
  kin_score: 82.6
  mcp: *id017
  name: Jira
  slug: jira
  status: profiled
  tags: *id018
  url: /providers/jira/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id019
  name: NextBus (public transport agent)
  slug: nextbus
  status: queued for profiling
  tags: *id020
  url: null
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id021
  name: OpenAI (LLM, image, speech, video agents)
  slug: openai
  status: profiled
  tags: *id022
  url: /providers/openai/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.2
  mcp: *id023
  name: PhantomJS Cloud
  slug: phantomjscloud
  status: profiled
  tags: *id024
  url: /providers/phantomjscloud/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.3
  mcp: *id025
  name: Pirate Weather (pirate_weather_forecast_ruby)
  slug: pirate-weather
  status: profiled
  tags: *id026
  url: /providers/pirate-weather/
- agent_band: agent-aware
  agent_readiness: 24.9
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id027
  name: Pushbullet
  slug: pushbullet
  status: profiled
  tags: *id028
  url: /providers/pushbullet/
- agent_band: agent-aware
  agent_readiness: 22.0
  band: thin
  in_catalog: true
  kin_score: 29.2
  mcp: *id029
  name: Pushover
  slug: pushover
  status: profiled
  tags: *id030
  url: /providers/pushover/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: emerging
  in_catalog: true
  kin_score: 17.1
  mcp: *id031
  name: Raindrop.io (bookmarks)
  slug: raindrop-io
  status: profiled
  tags: *id032
  url: /providers/raindrop-io/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id033
  name: Slack
  slug: slack
  status: profiled
  tags: *id034
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 51.8
  mcp: *id035
  name: StubHub
  slug: stubhub
  status: profiled
  tags: *id036
  url: /providers/stubhub/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id037
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id038
  url: /providers/telegram/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id039
  name: Threads (Meta)
  slug: facebook
  status: profiled
  tags: *id040
  url: /providers/facebook/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.9
  mcp: *id041
  name: Tumblr
  slug: tumblr
  status: profiled
  tags: *id042
  url: /providers/tumblr/
- agent_band: agent-native
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 90.3
  mcp: *id043
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id044
  url: /providers/twilio/
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id045
  name: Twitter / X
  slug: x
  status: profiled
  tags: *id046
  url: /providers/x/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 6.2
  mcp: *id047
  name: Weibo
  slug: weibo
  status: profiled
  tags: *id048
  url: /providers/weibo/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 23.8
  mcp: *id049
  name: Wit.ai
  slug: witai
  status: profiled
  tags: *id050
  url: /providers/witai/
siblings:
- name: Activepieces
  rows: 15
  url: /applications/workflow-automation/activepieces/
- name: Automatisch
  rows: 76
  url: /applications/workflow-automation/automatisch/
- name: IFTTT
  rows: 3
  url: /applications/workflow-automation/ifttt/
- name: Microsoft Power Automate
  rows: 1
  url: /applications/workflow-automation/microsoft-power-automate/
- name: n8n
  rows: 39
  url: /applications/workflow-automation/n8n/
- name: Windmill
  rows: 12
  url: /applications/workflow-automation/windmill/
sitemap: true
title: 'Huginn: Workflow Automation & iPaaS reference app'
---
