---
access: understanding
agent_layer: []
apps:
- anchor: mmm-myscoreboard
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: dependency manifest
    url: https://github.com/jclarke0000/MMM-MyScoreboard/blob/master/package.json
  - route: source code
    url: https://github.com/jclarke0000/MMM-MyScoreboard/blob/master/providers/ESPN.js
  - route: source code
    url: https://github.com/jclarke0000/MMM-MyScoreboard/blob/master/providers/SNET.js
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-180.80.40
      key: AE-180.80.40
      name: Sports Data
      url: /capabilities/sports-betting-fantasy/
      via_parent: Sports, Betting & Fantasy
    credit: null
    layer: domain
    name: ESPN site API scoreboards (site.api.espn.com)
    provider: espn
    says: ships the ESPN site API scoreboards (site.api.espn.com) SDK or integration code
    source: https://github.com/jclarke0000/MMM-MyScoreboard/blob/master/providers/ESPN.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.80.40
      key: AE-180.80.40
      name: Sports Data
      url: /capabilities/sports-betting-fantasy/
      via_parent: Sports, Betting & Fantasy
    credit: null
    layer: domain
    name: Sportsnet stats ticker (mobile-statsv2.sportsnet.ca)
    provider: sportsnet
    says: ships the Sportsnet stats ticker (mobile-statsv2.sportsnet.ca) SDK or integration code
    source: https://github.com/jclarke0000/MMM-MyScoreboard/blob/master/providers/SNET.js
    tier: observed
  kind: self-hosted
  name: MMM-MyScoreboard
  page: /applications/sports-fantasy/mmm-myscoreboard/
  slug: mmm-myscoreboard
  url: https://github.com/jclarke0000/MMM-MyScoreboard
- anchor: team-tracker-(home-assistant)
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: source code
    url: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/const.py
  - route: source code
    url: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_cflscoreboard.py
  - route: source code
    url: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_espn.py
  - route: source code
    url: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_hockeytech.py
  - route: source code
    url: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_mlbstats.py
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-180.80.40
      key: AE-180.80.40
      name: Sports Data
      url: /capabilities/sports-betting-fantasy/
      via_parent: Sports, Betting & Fantasy
    credit: null
    layer: domain
    name: CFL scoreboard JSON (cflscoreboard.cfl.ca)
    provider: cfl
    says: ships the CFL scoreboard JSON (cflscoreboard.cfl.ca) SDK or integration code
    source: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_cflscoreboard.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.80.40
      key: AE-180.80.40
      name: Sports Data
      url: /capabilities/sports-betting-fantasy/
      via_parent: Sports, Betting & Fantasy
    credit: null
    layer: domain
    name: ESPN site API scoreboards
    provider: espn
    says: ships the ESPN site API scoreboards SDK or integration code
    source: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_espn.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.80.40
      key: AE-180.80.40
      name: Sports Data
      url: /capabilities/sports-betting-fantasy/
      via_parent: Sports, Betting & Fantasy
    credit: null
    layer: domain
    name: HockeyTech league feed (lscluster.hockeytech.com)
    provider: hockeytech
    says: ships the HockeyTech league feed (lscluster.hockeytech.com) SDK or integration code
    source: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_hockeytech.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.80.40
      key: AE-180.80.40
      name: Sports Data
      url: /capabilities/sports-betting-fantasy/
      via_parent: Sports, Betting & Fantasy
    credit: null
    layer: domain
    name: MLB Stats API (statsapi.mlb.com)
    provider: major-league-baseball
    says: ships the MLB Stats API (statsapi.mlb.com) SDK or integration code
    source: https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_mlbstats.py
    tier: observed
  kind: self-hosted
  name: Team Tracker (Home Assistant)
  page: /applications/sports-fantasy/team-tracker-home-assistant/
  slug: team-tracker-home-assistant
  url: https://github.com/vasqued2/ha-teamtracker
- anchor: ffscrapr
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: dependency manifest
    url: https://github.com/ffverse/ffscrapr/blob/main/DESCRIPTION
  - route: source code
    url: https://github.com/ffverse/ffscrapr/blob/main/R/1_import_dp.R
  - route: source code
    url: https://github.com/ffverse/ffscrapr/blob/main/R/espn_api.R
  - route: source code
    url: https://github.com/ffverse/ffscrapr/blob/main/R/flea_api.R
  - route: source code
    url: https://github.com/ffverse/ffscrapr/blob/main/R/mfl_api.R
  - route: source code
    url: https://github.com/ffverse/ffscrapr/blob/main/R/sleeper_api.R
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-180.80.20
      key: AE-180.80.20
      name: Fantasy Sports
      url: /capabilities/sports-betting-fantasy/
      via_parent: Sports, Betting & Fantasy
    credit: null
    layer: domain
    name: DynastyProcess player-ID and values data files
    provider: dynastyprocess
    says: ships the DynastyProcess player-ID and values data files SDK or integration code
    source: https://github.com/ffverse/ffscrapr/blob/main/R/1_import_dp.R
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.80.20
      key: AE-180.80.20
      name: Fantasy Sports
      url: /capabilities/sports-betting-fantasy/
      via_parent: Sports, Betting & Fantasy
    credit: null
    layer: domain
    name: ESPN Fantasy league API (lm-api-reads.fantasy.espn.com)
    provider: espn
    says: ships the ESPN Fantasy league API (lm-api-reads.fantasy.espn.com) SDK or integration code
    source: https://github.com/ffverse/ffscrapr/blob/main/R/espn_api.R
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.80.20
      key: AE-180.80.20
      name: Fantasy Sports
      url: /capabilities/sports-betting-fantasy/
      via_parent: Sports, Betting & Fantasy
    credit: null
    layer: domain
    name: Fleaflicker API
    provider: fleaflicker
    says: ships the Fleaflicker API SDK or integration code
    source: https://github.com/ffverse/ffscrapr/blob/main/R/flea_api.R
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.80.20
      key: AE-180.80.20
      name: Fantasy Sports
      url: /capabilities/sports-betting-fantasy/
      via_parent: Sports, Betting & Fantasy
    credit: null
    layer: domain
    name: MyFantasyLeague API (api.myfantasyleague.com)
    provider: myfantasyleague
    says: ships the MyFantasyLeague API (api.myfantasyleague.com) SDK or integration code
    source: https://github.com/ffverse/ffscrapr/blob/main/R/mfl_api.R
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.80.40
      key: AE-180.80.40
      name: Sports Data
      url: /capabilities/sports-betting-fantasy/
      via_parent: Sports, Betting & Fantasy
    credit: null
    layer: domain
    name: nflverse data via nflreadr
    provider: nflverse
    says: ships the nflverse data via nflreadr SDK or integration code
    source: https://github.com/ffverse/ffscrapr/blob/main/DESCRIPTION
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.80.20
      key: AE-180.80.20
      name: Fantasy Sports
      url: /capabilities/sports-betting-fantasy/
      via_parent: Sports, Betting & Fantasy
    credit: null
    layer: domain
    name: Sleeper API (api.sleeper.app/v1)
    provider: sleeper
    says: ships the Sleeper API (api.sleeper.app/v1) SDK or integration code
    source: https://github.com/ffverse/ffscrapr/blob/main/R/sleeper_api.R
    tier: observed
  kind: self-hosted
  name: ffscrapr
  page: /applications/sports-fantasy/ffscrapr/
  slug: ffscrapr
  url: https://github.com/ffverse/ffscrapr
- anchor: gameday-bot-(fantasy_football_chat_bot)
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/requirements.txt
  - route: source code
    url: https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/gamedaybot/chat/groupme.py
  - route: source code
    url: https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/gamedaybot/espn/env_vars.py
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Discord webhook
    provider: discord
    says: ships the Discord webhook SDK or integration code
    source: https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/gamedaybot/espn/env_vars.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-180.80.20
      key: AE-180.80.20
      name: Fantasy Sports
      url: /capabilities/sports-betting-fantasy/
      via_parent: Sports, Betting & Fantasy
    credit: null
    layer: domain
    name: ESPN Fantasy via espn_api
    provider: espn
    says: ships the ESPN Fantasy via espn_api SDK or integration code
    source: https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/requirements.txt
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: GroupMe bots API
    provider: groupme
    says: ships the GroupMe bots API SDK or integration code
    source: https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/gamedaybot/chat/groupme.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Slack incoming webhook
    provider: slack
    says: ships the Slack incoming webhook SDK or integration code
    source: https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/gamedaybot/espn/env_vars.py
    tier: observed
  kind: self-hosted
  name: GameDay Bot (fantasy_football_chat_bot)
  page: /applications/sports-fantasy/gameday-bot-fantasy-football-chat-bot/
  slug: gameday-bot-fantasy-football-chat-bot
  url: https://github.com/dtcarls/fantasy_football_chat_bot
- anchor: espn
  counts:
    declared: 0
    observed: 10
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Adobe Experience Cloud
    provider: adobe-experience-cloud
    says: ships the Adobe Experience Cloud SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
    name: Comscore
    provider: comscore
    says: ships the Comscore SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
    name: Conviva
    provider: conviva
    says: ships the Conviva SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
    name: Kochava
    provider: kochava
    says: ships the Kochava SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
    name: Nielsen
    provider: nielsen
    says: ships the Nielsen SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
    name: Parse.ly
    provider: parse-ly
    says: ships the Parse.ly SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
    tier: observed
  kind: commercial
  name: ESPN
  page: /applications/sports-fantasy/espn/
  slug: espn
  url: https://www.espn.com/
- anchor: sleeper
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.sleeperbot/latest/
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
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sleeperbot/latest/
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
    name: Firebase (Crashlytics)
    provider: firebase
    says: ships the Firebase (Crashlytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sleeperbot/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sleeperbot/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sleeperbot/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sleeperbot/latest/
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
    name: Kochava
    provider: kochava
    says: ships the Kochava SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sleeperbot/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: OneSignal
    provider: onesignal
    says: ships the OneSignal SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sleeperbot/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.sleeperbot/latest/
    tier: observed
  kind: commercial
  name: Sleeper
  page: /applications/sports-fantasy/sleeper/
  slug: sleeper
  url: https://sleeper.com/
- anchor: thescore
  counts:
    declared: 0
    observed: 26
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    name: AdColony
    provider: adcolony
    says: ships the AdColony SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Airship (Urbanairship)
    provider: airship
    says: ships the Airship (Urbanairship) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    name: Amazon Advertisement
    provider: amazon
    says: ships the Amazon Advertisement SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    name: BidMachine
    provider: bidmachine-io
    says: ships the BidMachine SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    name: Chartboost
    provider: chartboost
    says: ships the Chartboost SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    name: Comscore
    provider: comscore
    says: ships the Comscore SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    name: Digital Turbine (Fyber)
    provider: digital-turbine
    says: ships the Digital Turbine (Fyber) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    name: Firebase (Crashlytics)
    provider: firebase
    says: ships the Firebase (Crashlytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    name: InMobi
    provider: inmobi
    says: ships the InMobi SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    name: ironSource
    provider: ironsource
    says: ships the ironSource SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    name: myTarget
    provider: mytarget
    says: ships the myTarget SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    name: Outbrain
    provider: outbrain
    says: ships the Outbrain SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    name: PubMatic
    provider: pubmatic
    says: ships the PubMatic SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    name: Teads
    provider: teads
    says: ships the Teads SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    name: Unity Ads
    provider: unity
    says: ships the Unity Ads SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
    name: Yandex Ads
    provider: yandex-ads
    says: ships the Yandex Ads SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
    tier: observed
  kind: commercial
  name: theScore
  page: /applications/sports-fantasy/thescore/
  slug: thescore
  url: https://www.thescore.com/
- anchor: yahoo-fantasy
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
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
    name: Comscore
    provider: comscore
    says: ships the Comscore SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
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
    name: Flurry
    provider: flurry
    says: ships the Flurry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
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
    name: Taboola
    provider: taboola
    says: ships the Taboola SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
    tier: observed
  kind: commercial
  name: Yahoo Fantasy
  page: /applications/sports-fantasy/yahoo-fantasy/
  slug: yahoo-fantasy
  url: https://sports.yahoo.com/fantasy/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: sports-fantasy
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Sports
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Sports
  store: google-play
  url: https://play.google.com/store/apps/category/SPORTS
name: Sports Scores & Fantasy
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-180.80.40
    key: AE-180.80.40
    name: Sports Data
    url: /capabilities/sports-betting-fantasy/
    via_parent: Sports, Betting & Fantasy
  fit: exact
  layer: domain
  why: Live scores, schedules and stats from leagues and media feeds; the core of every scoreboard app.
- capability:
    attribution: API Evangelist extension
    id: AE-180.80.20
    key: AE-180.80.20
    name: Fantasy Sports
    url: /capabilities/sports-betting-fantasy/
    via_parent: Sports, Betting & Fantasy
  fit: exact
  layer: domain
  why: League, roster, draft and transaction data from fantasy platforms.
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: exact
  layer: common
  why: Fantasy league bots post updates into group chat.
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: social sharing and marketing SDKs in the shipped Android app
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: nearest
  layer: common
  why: usage and audience analytics SDKs in the shipped Android app
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: in-app advertising SDKs in the shipped Android app
- capability:
    attribution: Turbo EA
    id: BC-3760.30
    key: programmatic-sales-management
    name: Programmatic Sales Management
    url: /capabilities/programmatic-sales-management/
    via_parent: null
  fit: nearest
  layer: common
  why: ad viewability measurement SDK in the shipped Android app
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile attribution and deep linking SDKs in the shipped Android app
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash and performance reporting SDKs in the shipped Android app
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: tag management SDK in the shipped Android app
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: push notification SDK in the shipped Android app
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-180.80.40
      key: AE-180.80.40
      name: Sports Data
      url: /capabilities/sports-betting-fantasy/
      via_parent: Sports, Betting & Fantasy
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - MMM-MyScoreboard
      - Team Tracker (Home Assistant)
      band: minimal
      in_catalog: true
      kin_score: 4.1
      mcp: &id001
        status: none
      name: ESPN site API scoreboards (site.api.espn.com)
      slug: espn
      sources:
      - https://github.com/jclarke0000/MMM-MyScoreboard/blob/master/providers/ESPN.js
      - https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_espn.py
      status: profiled
      tags: &id002
      - Broadcasting
      - Company
      - Media
      - Sports
      tier: observed
      url: /providers/espn/
    - agent_band: agent-aware
      agent_readiness: 13.7
      apps:
      - Team Tracker (Home Assistant)
      band: emerging
      in_catalog: true
      kin_score: 22.2
      mcp:
        status: none
      name: MLB Stats API (statsapi.mlb.com)
      slug: major-league-baseball
      sources:
      - https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_mlbstats.py
      status: profiled
      tags:
      - Analytics
      - Baseball
      - Entertainment
      - Media
      tier: observed
      url: /providers/major-league-baseball/
    - agent_band: human-only
      agent_readiness: 0.7
      apps:
      - ffscrapr
      band: emerging
      in_catalog: true
      kin_score: 18.3
      mcp:
        status: none
      name: nflverse data via nflreadr
      slug: nflverse
      sources:
      - https://github.com/ffverse/ffscrapr/blob/main/DESCRIPTION
      status: profiled
      tags:
      - Analytics
      - Data
      - Open Source
      - Sports
      tier: observed
      url: /providers/nflverse/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Team Tracker (Home Assistant)
      band: emerging
      in_catalog: true
      kin_score: 12.3
      mcp:
        status: none
      name: CFL scoreboard JSON (cflscoreboard.cfl.ca)
      slug: cfl
      sources:
      - https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_cflscoreboard.py
      status: profiled
      tags:
      - Canada
      - Football
      - Professional League
      - Sports
      tier: observed
      url: /providers/cfl/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Team Tracker (Home Assistant)
      band: minimal
      in_catalog: true
      kin_score: 10.8
      mcp:
        status: none
      name: HockeyTech league feed (lscluster.hockeytech.com)
      slug: hockeytech
      sources:
      - https://github.com/vasqued2/ha-teamtracker/blob/master/custom_components/teamtracker/provide_hockeytech.py
      status: profiled
      tags:
      - Analytics
      - Data
      - Sports
      - Streaming
      tier: observed
      url: /providers/hockeytech/
    - agent_band: agent-aware
      agent_readiness: 5.6
      apps:
      - MMM-MyScoreboard
      band: minimal
      in_catalog: true
      kin_score: 5.4
      mcp:
        status: unknown
      name: Sportsnet stats ticker (mobile-statsv2.sportsnet.ca)
      slug: sportsnet
      sources:
      - https://github.com/jclarke0000/MMM-MyScoreboard/blob/master/providers/SNET.js
      status: profiled
      tags:
      - Canada
      - Media
      - News
      - Sports
      tier: observed
      url: /providers/sportsnet/
  - capability:
      attribution: API Evangelist extension
      id: AE-180.80.20
      key: AE-180.80.20
      name: Fantasy Sports
      url: /capabilities/sports-betting-fantasy/
      via_parent: Sports, Betting & Fantasy
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - GameDay Bot (fantasy_football_chat_bot)
      - ffscrapr
      band: minimal
      in_catalog: true
      kin_score: 4.1
      mcp: *id001
      name: ESPN Fantasy league API (lm-api-reads.fantasy.espn.com)
      slug: espn
      sources:
      - https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/requirements.txt
      - https://github.com/ffverse/ffscrapr/blob/main/R/espn_api.R
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/espn/
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - ffscrapr
      band: thin
      in_catalog: true
      kin_score: 30.6
      mcp:
        status: unknown
      name: Sleeper API (api.sleeper.app/v1)
      slug: sleeper
      sources:
      - https://github.com/ffverse/ffscrapr/blob/main/R/sleeper_api.R
      status: profiled
      tags:
      - Company
      - Fantasy Football
      - Fantasy Sports
      - Sports
      tier: observed
      url: /providers/sleeper/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - ffscrapr
      band: emerging
      in_catalog: true
      kin_score: 16.7
      mcp:
        status: unknown
      name: MyFantasyLeague API (api.myfantasyleague.com)
      slug: myfantasyleague
      sources:
      - https://github.com/ffverse/ffscrapr/blob/main/R/mfl_api.R
      status: profiled
      tags:
      - Custom Scoring
      - Fantasy Sports
      - Football
      - League-Management
      tier: observed
      url: /providers/myfantasyleague/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - ffscrapr
      band: emerging
      in_catalog: true
      kin_score: 14.4
      mcp:
        status: none
      name: Fleaflicker API
      slug: fleaflicker
      sources:
      - https://github.com/ffverse/ffscrapr/blob/main/R/flea_api.R
      status: profiled
      tags:
      - Company
      - Fantasy Sports
      - Football
      - Sports
      tier: observed
      url: /providers/fleaflicker/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - ffscrapr
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        status: none
      name: DynastyProcess player-ID and values data files
      slug: dynastyprocess
      sources:
      - https://github.com/ffverse/ffscrapr/blob/main/R/1_import_dp.R
      status: profiled
      tags:
      - Analytics
      - Company
      - Data
      - Fantasy Football
      tier: observed
      url: /providers/dynastyprocess/
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
      - ESPN
      - Yahoo Fantasy
      - theScore
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
    - agent_band: agent-ready
      agent_readiness: 34.1
      apps:
      - theScore
      band: exemplar
      in_catalog: true
      kin_score: 71.1
      mcp:
        status: none
      name: Outbrain
      slug: outbrain
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      status: profiled
      tags:
      - Advertising
      - CTV
      - Native Advertising
      - Open Web
      tier: observed
      url: /providers/outbrain/
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - Yahoo Fantasy
      band: exemplar
      in_catalog: true
      kin_score: 69.5
      mcp:
        source: https://github.com/taboola/realize-mcp
        status: verified
      name: Taboola
      slug: taboola
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
      status: profiled
      tags:
      - Advertising
      - Discovery
      - Native Advertising
      - Performance Marketing
      tier: observed
      url: /providers/taboola/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - theScore
      band: exemplar
      in_catalog: true
      kin_score: 66.5
      mcp:
        source: https://github.com/Unity-Technologies/industry-ai-workflows
        status: verified
      name: Unity Ads
      slug: unity
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      status: profiled
      tags:
      - Game Development
      - Game Services
      - Multiplayer
      - Real-Time 3D
      tier: observed
      url: /providers/unity/
    - agent_band: agent-ready
      agent_readiness: 31.0
      apps:
      - theScore
      band: strong
      in_catalog: true
      kin_score: 60.3
      mcp:
        status: none
      name: BidMachine
      slug: bidmachine-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      status: profiled
      tags:
      - Ad Exchange
      - AdTech
      - Advertising
      - Mobile Advertising
      tier: observed
      url: /providers/bidmachine-io/
    - agent_band: agent-native
      agent_readiness: 53.6
      apps:
      - theScore
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Amazon Advertisement
      slug: amazon
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: observed
      url: /providers/amazon/
    - agent_band: agent-aware
      agent_readiness: 7.7
      apps:
      - theScore
      band: developing
      in_catalog: true
      kin_score: 46.1
      mcp:
        status: none
      name: InMobi
      slug: inmobi
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Enterprise
      tier: observed
      url: /providers/inmobi/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - theScore
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook Ads
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: human-only
      agent_readiness: 4.9
      apps:
      - theScore
      band: developing
      in_catalog: true
      kin_score: 43.0
      mcp:
        status: none
      name: Teads
      slug: teads
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Video Advertising
      tier: observed
      url: /providers/teads/
    - agent_band: agent-aware
      agent_readiness: 20.3
      apps:
      - theScore
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Digital Turbine (Fyber)
      slug: digital-turbine
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      status: profiled
      tags:
      - Advertising
      - Company
      - Mobile
      - Monetization
      tier: observed
      url: /providers/digital-turbine/
    - agent_band: agent-ready
      agent_readiness: 35.5
      apps:
      - theScore
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp:
        status: none
      name: AppLovin
      slug: applovin
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - App Monetization
      - Mobile
      tier: observed
      url: /providers/applovin/
    - agent_band: agent-aware
      agent_readiness: 19.4
      apps:
      - theScore
      band: thin
      in_catalog: true
      kin_score: 29.6
      mcp:
        status: none
      name: AdColony
      slug: adcolony
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Mobile Advertising
      tier: observed
      url: /providers/adcolony/
    - agent_band: agent-ready
      agent_readiness: 33.5
      apps:
      - theScore
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        source: https://github.com/PubMatic/pubmatic-mcp-server
        status: verified
      name: PubMatic
      slug: pubmatic
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Programmatic Advertising
      - Supply Side Platform
      tier: observed
      url: /providers/pubmatic/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - theScore
      band: emerging
      in_catalog: true
      kin_score: 16.2
      mcp:
        status: unknown
      name: Mintegral
      slug: mintegral
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
      - theScore
      band: emerging
      in_catalog: true
      kin_score: 14.1
      mcp:
        status: none
      name: Pangle
      slug: pangle
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      status: profiled
      tags:
      - Advertising
      - Mobile
      - Monetization
      - TikTok
      tier: observed
      url: /providers/pangle/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - theScore
      band: emerging
      in_catalog: true
      kin_score: 13.2
      mcp:
        status: none
      name: Yandex Ads
      slug: yandex-ads
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      status: profiled
      tags:
      - Advertising
      - App Monetization
      - User Acquisition
      - Web Analytics
      tier: observed
      url: /providers/yandex-ads/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - theScore
      band: minimal
      in_catalog: true
      kin_score: 10.2
      mcp:
        status: none
      name: ironSource
      slug: ironsource
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      status: profiled
      tags:
      - Advertising
      - Game Development
      - Mobile
      - Mobile Games
      tier: observed
      url: /providers/ironsource/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - theScore
      band: minimal
      in_catalog: true
      kin_score: 2.0
      mcp:
        status: none
      name: Chartboost
      slug: chartboost
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/chartboost/
    - agent_band: null
      agent_readiness: null
      apps:
      - theScore
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: myTarget
      slug: mytarget
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
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
      - ESPN
      - Sleeper
      - Yahoo Fantasy
      - theScore
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.sleeperbot/latest/
      status: profiled
      tags: &id004
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 12.0
      apps:
      - ESPN
      - Yahoo Fantasy
      - theScore
      band: emerging
      in_catalog: true
      kin_score: 17.9
      mcp:
        status: none
      name: Comscore
      slug: comscore
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
      status: profiled
      tags:
      - Audience Analytics
      - Cloud Saas
      - Company
      - Media Measurement
      tier: observed
      url: /providers/comscore/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Sleeper
      - Yahoo Fantasy
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.sleeperbot/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - theScore
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 52.5
      apps:
      - ESPN
      band: strong
      in_catalog: true
      kin_score: 58.3
      mcp:
        source: https://github.com/Conviva/mcp-marketplace
        status: verified
      name: Conviva
      slug: conviva
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
      status: profiled
      tags:
      - Analytics
      - Observability
      - Streaming
      - Video
      tier: observed
      url: /providers/conviva/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Yahoo Fantasy
      band: emerging
      in_catalog: true
      kin_score: 18.6
      mcp:
        status: none
      name: Flurry
      slug: flurry
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
      status: profiled
      tags:
      - Analytics
      - Company
      - Mobile
      - SDK
      tier: observed
      url: /providers/flurry/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - ESPN
      band: emerging
      in_catalog: true
      kin_score: 15.9
      mcp:
        status: unknown
      name: Nielsen
      slug: nielsen
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
      status: profiled
      tags:
      - Audience Measurement
      - Company
      - DataInsights
      - Media Analytics
      tier: observed
      url: /providers/nielsen/
    - agent_band: null
      agent_readiness: null
      apps:
      - ESPN
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Parse.ly
      slug: parse-ly
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Sleeper
      - theScore
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.sleeperbot/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
    - agent_band: null
      agent_readiness: null
      apps:
      - ESPN
      - Sleeper
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Kochava
      slug: kochava
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.sleeperbot/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - theScore
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Sleeper
      - theScore
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id003
      name: Firebase (Crashlytics)
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.sleeperbot/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Sleeper
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.sleeperbot/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - ESPN
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
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
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - ESPN
      - Yahoo Fantasy
      - theScore
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        source: https://github.com/IABTechLab/agentic-real-time-framework
        status: verified
      name: IAB Open Measurement
      slug: iab-tech-lab
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Standards
      tier: observed
      url: /providers/iab-tech-lab/
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
      - GameDay Bot (fantasy_football_chat_bot)
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack incoming webhook
      slug: slack
      sources:
      - https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/gamedaybot/espn/env_vars.py
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - GameDay Bot (fantasy_football_chat_bot)
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord webhook
      slug: discord
      sources:
      - https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/gamedaybot/espn/env_vars.py
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - GameDay Bot (fantasy_football_chat_bot)
      band: thin
      in_catalog: true
      kin_score: 32.9
      mcp:
        status: none
      name: GroupMe bots API
      slug: groupme
      sources:
      - https://github.com/dtcarls/fantasy_football_chat_bot/blob/master/gamedaybot/chat/groupme.py
      status: profiled
      tags:
      - Chat
      - Company
      - Consumer
      - Messaging
      tier: observed
      url: /providers/groupme/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 70.1
      apps:
      - Sleeper
      band: exemplar
      in_catalog: true
      kin_score: 76.8
      mcp:
        source: https://github.com/OneSignal/onesignal-ai-skills
        status: documented
      name: OneSignal
      slug: onesignal
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.sleeperbot/latest/
      status: profiled
      tags:
      - Email
      - Notification
      - Push
      - SMS
      tier: observed
      url: /providers/onesignal/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - theScore
      band: thin
      in_catalog: true
      kin_score: 28.3
      mcp:
        source: https://github.com/urbanairship/agent-tools
        status: verified
      name: Airship (Urbanairship)
      slug: airship
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.fivemobile.thescore/latest/
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
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Sleeper
      - Yahoo Fantasy
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.sleeperbot/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.fantasyfootball/latest/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.0
      apps:
      - ESPN
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        source: https://github.com/adobe/cq-quickstart-mcp-server
        status: verified
      name: Adobe Experience Cloud
      slug: adobe-experience-cloud
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.espn.score_center/latest/
      status: profiled
      tags:
      - Analytics
      - Customer Experience
      - Digital Marketing
      - Personalization
      tier: observed
      url: /providers/adobe-experience-cloud/
  layer: common
summary:
  coverage_pct: 94.0
  declared_only: 0
  distinct_providers: 50
  in_catalog: 47
  mcp:
    documented: 1
    none: 26
    unchecked: 3
    verified: 15
  mcp_verified: 15
  mean_kin_score: 40.0
  observed: 50
  queued: 3
  reference_apps: 8
title: 'Sports Scores & Fantasy: application blueprint'
---
