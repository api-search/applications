---
app: FairEmail
app_slug: fairemail
app_url: https://github.com/M66B/FairEmail
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.10.40
  key: AE-150.10.40
  layer: domain
  name: Email Security
  providers:
  - Barracuda Networks
  - NordSpam
  - SpamCop
  - Spamhaus
  - UCEPROTECT
  - VirusTotal
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-110.40.40
  key: AE-110.40.40
  layer: domain
  name: Grammar & Writing Assistance
  providers:
  - LanguageTool
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: domain
  name: Machine Translation
  providers:
  - DeepL
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - AOL Mail
  - Apple iCloud Mail
  - Fastmail
  - Gmail
  - GMX Mail
  - IONOS
  - mailbox.org
  - Microsoft Graph
  - Outlook.com
  - Posteo
  - Yahoo Mail
  - Yandex Mail
  - Zoho Mail
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.60
  key: AE-160.60
  layer: common
  name: Credential Security
  providers:
  - Have I Been Pwned
  url: /capabilities/credential-security/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: common
  name: IP Geolocation
  providers:
  - IP2Location
  - IPinfo
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Google Gemini
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: email-client
  name: Email Client & Hosting
  url: /applications/email-client/
counts:
  declared: 0
  observed: 26
credits: []
evidence:
- route: source code
  url: https://github.com/M66B/FairEmail/tree/master/app/src/main/java/eu/faircode/email
- route: source code
  url: https://raw.githubusercontent.com/M66B/FairEmail/master/app/build.gradle
- route: source code
  url: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.1
    band: developing
    in_catalog: true
    kin_score: 46.2
    mcp: &id001
      status: none
    slug: aol
    status: profiled
    tags: &id002
    - Advertising
    - Digital Media
    - Entertainment
    - News
    url: /providers/aol/
  layer: domain
  name: AOL Mail
  provider: aol
  says: ships the AOL Mail SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
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
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id003
      status: none
    slug: apple
    status: profiled
    tags: &id004
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Apple iCloud Mail
  provider: apple
  says: ships the Apple iCloud Mail SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.40
    key: AE-150.10.40
    name: Email Security
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.8
    mcp: &id005
      status: none
    slug: barracuda-networks
    status: profiled
    tags: &id006
    - Company
    - Security
    url: /providers/barracuda-networks/
  layer: domain
  name: Barracuda Networks
  provider: barracuda-networks
  says: ships the Barracuda Networks SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/DnsBlockList.java
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
    agent_band: agent-ready
    agent_readiness: 36.4
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id007
      source: https://github.com/DeepL/deepl-mcp-server
      status: verified
    slug: deepl
    status: profiled
    tags: &id008
    - Artificial Intelligence
    - Deep Learning
    - Glossary
    - Localization
    url: /providers/deepl/
  layer: domain
  name: DeepL
  provider: deepl
  says: ships the DeepL SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/DeepL.java
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
    agent_readiness: 17.6
    band: thin
    in_catalog: true
    kin_score: 28.8
    mcp: &id009
      status: none
    slug: fastmail
    status: profiled
    tags: &id010
    - Business
    - Email
    - Privacy
    - Security
    url: /providers/fastmail/
  layer: domain
  name: Fastmail
  provider: fastmail
  says: ships the Fastmail SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
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
    mcp: &id011
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id012
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: domain
  name: Gmail
  provider: google-gmail
  says: ships the Gmail SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
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
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 11.5
    mcp: &id013
      status: none
    slug: gmx-net
    status: profiled
    tags: &id014
    - Cloud
    - Company
    - Email
    - Free
    url: /providers/gmx-net/
  layer: domain
  name: GMX Mail
  provider: gmx-net
  says: ships the GMX Mail SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
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
    agent_band: agent-ready
    agent_readiness: 31.3
    band: strong
    in_catalog: true
    kin_score: 55.1
    mcp: &id015
      status: none
    slug: google-gemini
    status: profiled
    tags: &id016
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/build.gradle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.60
    key: AE-160.60
    name: Credential Security
    url: /capabilities/credential-security/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.0
    band: developing
    in_catalog: true
    kin_score: 48.4
    mcp: &id017
      status: none
    slug: have-i-been-pwned
    status: profiled
    tags: &id018
    - Data Breaches
    - Identity
    - Pwned Passwords
    - Security
    url: /providers/have-i-been-pwned/
  layer: common
  name: Have I Been Pwned
  provider: have-i-been-pwned
  says: ships the Have I Been Pwned SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/build.gradle
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
    agent_readiness: 10.8
    band: emerging
    in_catalog: true
    kin_score: 20.6
    mcp: &id019
      source: https://github.com/ionos-cloud/ionoscloud-mcp
      status: verified
    slug: ionos
    status: profiled
    tags: &id020
    - Cloud
    - Company
    - Domains
    - Hosting
    url: /providers/ionos/
  layer: domain
  name: IONOS
  provider: ionos
  says: ships the IONOS SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.2
    mcp: &id021
      source: https://github.com/ip2location/mcp-ip2location-io
      status: verified
    slug: ip2location
    status: profiled
    tags: &id022
    - Geocoding
    - Public APIs
    url: /providers/ip2location/
  layer: common
  name: IP2Location
  provider: ip2location
  says: ships the IP2Location SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/IPInfo.java
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.4
    band: strong
    in_catalog: true
    kin_score: 63.2
    mcp: &id023
      source: https://github.com/ipinfo/mcp
      status: verified
    slug: ipinfo
    status: profiled
    tags: &id024
    - ASN
    - IP Geolocation
    - IP Intelligence
    - Privacy Detection
    url: /providers/ipinfo/
  layer: common
  name: IPinfo
  provider: ipinfo
  says: ships the IPinfo SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/IPInfo.java
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.40
    key: AE-110.40.40
    name: Grammar & Writing Assistance
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 29.5
    mcp: &id025
      status: none
    slug: languagetool
    status: profiled
    tags: &id026
    - Grammar
    - Language
    - Proofreading
    - Spell Check
    url: /providers/languagetool/
  layer: domain
  name: LanguageTool
  provider: languagetool
  says: ships the LanguageTool SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/LanguageTool.java
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
    agent_band: agent-ready
    agent_readiness: 30.6
    band: emerging
    in_catalog: true
    kin_score: 19.6
    mcp: &id027
      status: unknown
    slug: mailbox-org
    status: profiled
    tags: &id028
    - Collaboration
    - Email
    - GDPR
    - Privacy
    url: /providers/mailbox-org/
  layer: domain
  name: mailbox.org
  provider: mailbox-org
  says: ships the mailbox.org SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
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
    agent_band: agent-ready
    agent_readiness: 37.0
    band: exemplar
    in_catalog: true
    kin_score: 70.1
    mcp: &id029
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-graph
    status: profiled
    tags: &id030
    - Azure AD
    - Collaboration
    - Contacts
    - Microsoft Graph
    url: /providers/microsoft-graph/
  layer: domain
  name: Microsoft Graph
  provider: microsoft-graph
  says: ships the Microsoft Graph SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/MicrosoftGraph.java
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.40
    key: AE-150.10.40
    name: Email Security
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 8.9
    mcp: &id031
      status: unknown
    slug: nordspam
    status: profiled
    tags: &id032
    - Company
    - DNSBL
    - Security
    - Spam
    url: /providers/nordspam/
  layer: domain
  name: NordSpam
  provider: nordspam
  says: ships the NordSpam SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/DnsBlockList.java
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
    mcp: &id033
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id034
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/build.gradle
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
    agent_band: agent-ready
    agent_readiness: 49.5
    band: exemplar
    in_catalog: true
    kin_score: 70.6
    mcp: &id035
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id036
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: domain
  name: Outlook.com
  provider: microsoft-outlook
  says: ships the Outlook.com SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.5
    mcp: &id037
      status: none
    slug: posteo
    status: profiled
    tags: &id038
    - Email
    - Privacy
    - Security
    - Sustainability
    url: /providers/posteo/
  layer: domain
  name: Posteo
  provider: posteo
  says: ships the Posteo SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.40
    key: AE-150.10.40
    name: Email Security
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.4
    mcp: &id039
      status: unknown
    slug: spamcop
    status: profiled
    tags: &id040
    - Anti-Spam
    - Email
    - Security
    - Spam
    url: /providers/spamcop/
  layer: domain
  name: SpamCop
  provider: spamcop
  says: ships the SpamCop SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/DnsBlockList.java
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.40
    key: AE-150.10.40
    name: Email Security
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 11.8
    mcp: &id041
      status: none
    slug: spamhaus
    status: profiled
    tags: &id042
    - Anti-Spam
    - Company
    - Reputation
    - Security
    url: /providers/spamhaus/
  layer: domain
  name: Spamhaus
  provider: spamhaus
  says: ships the Spamhaus SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/DnsBlockList.java
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.40
    key: AE-150.10.40
    name: Email Security
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.1
    mcp: &id043
      status: unknown
    slug: uceprotect
    status: profiled
    tags: &id044
    - Blacklist
    - Company
    - Email Security
    - Spam Protection
    url: /providers/uceprotect/
  layer: domain
  name: UCEPROTECT
  provider: uceprotect
  says: ships the UCEPROTECT SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/DnsBlockList.java
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.40
    key: AE-150.10.40
    name: Email Security
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.9
    band: developing
    in_catalog: true
    kin_score: 40.1
    mcp: &id045
      source: https://github.com/VirusTotal/virustotal-mcp
      status: verified
    slug: virustotal
    status: profiled
    tags: &id046
    - Anti Malware
    - File Analysis
    - Security
    - Threat Intelligence
    url: /providers/virustotal/
  layer: domain
  name: VirusTotal
  provider: virustotal
  says: ships the VirusTotal SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/VirusTotal.java
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
    agent_readiness: 16.2
    band: developing
    in_catalog: true
    kin_score: 41.4
    mcp: &id047
      status: none
    slug: yahoo
    status: profiled
    tags: &id048
    - Advertising
    - DSP
    - Fantasy Sports
    - Programmatic Advertising
    url: /providers/yahoo/
  layer: domain
  name: Yahoo Mail
  provider: yahoo
  says: ships the Yahoo Mail SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 18.3
    mcp: &id049
      status: none
    slug: yandex-mail
    status: profiled
    tags: &id050
    - Cloud
    - Communications
    - Company
    - Email
    url: /providers/yandex-mail/
  layer: domain
  name: Yandex Mail
  provider: yandex-mail
  says: ships the Yandex Mail SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
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
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 36.4
    mcp: &id051
      status: none
    slug: zoho-mail
    status: profiled
    tags: &id052
    - Collaboration
    - Email
    - Mail
    - Messaging
    url: /providers/zoho-mail/
  layer: domain
  name: Zoho Mail
  provider: zoho-mail
  says: ships the Zoho Mail SDK or integration code
  source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/email-client/fairemail/
providers:
- agent_band: agent-ready
  agent_readiness: 36.1
  band: developing
  in_catalog: true
  kin_score: 46.2
  mcp: *id001
  name: AOL Mail
  slug: aol
  status: profiled
  tags: *id002
  url: /providers/aol/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id003
  name: Apple iCloud Mail
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.8
  mcp: *id005
  name: Barracuda Networks
  slug: barracuda-networks
  status: profiled
  tags: *id006
  url: /providers/barracuda-networks/
- agent_band: agent-ready
  agent_readiness: 36.4
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id007
  name: DeepL
  slug: deepl
  status: profiled
  tags: *id008
  url: /providers/deepl/
- agent_band: agent-aware
  agent_readiness: 17.6
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id009
  name: Fastmail
  slug: fastmail
  status: profiled
  tags: *id010
  url: /providers/fastmail/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id011
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id012
  url: /providers/google-gmail/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 11.5
  mcp: *id013
  name: GMX Mail
  slug: gmx-net
  status: profiled
  tags: *id014
  url: /providers/gmx-net/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: strong
  in_catalog: true
  kin_score: 55.1
  mcp: *id015
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id016
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: developing
  in_catalog: true
  kin_score: 48.4
  mcp: *id017
  name: Have I Been Pwned
  slug: have-i-been-pwned
  status: profiled
  tags: *id018
  url: /providers/have-i-been-pwned/
- agent_band: agent-aware
  agent_readiness: 10.8
  band: emerging
  in_catalog: true
  kin_score: 20.6
  mcp: *id019
  name: IONOS
  slug: ionos
  status: profiled
  tags: *id020
  url: /providers/ionos/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.2
  mcp: *id021
  name: IP2Location
  slug: ip2location
  status: profiled
  tags: *id022
  url: /providers/ip2location/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: strong
  in_catalog: true
  kin_score: 63.2
  mcp: *id023
  name: IPinfo
  slug: ipinfo
  status: profiled
  tags: *id024
  url: /providers/ipinfo/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id025
  name: LanguageTool
  slug: languagetool
  status: profiled
  tags: *id026
  url: /providers/languagetool/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: emerging
  in_catalog: true
  kin_score: 19.6
  mcp: *id027
  name: mailbox.org
  slug: mailbox-org
  status: profiled
  tags: *id028
  url: /providers/mailbox-org/
- agent_band: agent-ready
  agent_readiness: 37.0
  band: exemplar
  in_catalog: true
  kin_score: 70.1
  mcp: *id029
  name: Microsoft Graph
  slug: microsoft-graph
  status: profiled
  tags: *id030
  url: /providers/microsoft-graph/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 8.9
  mcp: *id031
  name: NordSpam
  slug: nordspam
  status: profiled
  tags: *id032
  url: /providers/nordspam/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id033
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id034
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 70.6
  mcp: *id035
  name: Outlook.com
  slug: microsoft-outlook
  status: profiled
  tags: *id036
  url: /providers/microsoft-outlook/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.5
  mcp: *id037
  name: Posteo
  slug: posteo
  status: profiled
  tags: *id038
  url: /providers/posteo/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.4
  mcp: *id039
  name: SpamCop
  slug: spamcop
  status: profiled
  tags: *id040
  url: /providers/spamcop/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 11.8
  mcp: *id041
  name: Spamhaus
  slug: spamhaus
  status: profiled
  tags: *id042
  url: /providers/spamhaus/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.1
  mcp: *id043
  name: UCEPROTECT
  slug: uceprotect
  status: profiled
  tags: *id044
  url: /providers/uceprotect/
- agent_band: agent-ready
  agent_readiness: 30.9
  band: developing
  in_catalog: true
  kin_score: 40.1
  mcp: *id045
  name: VirusTotal
  slug: virustotal
  status: profiled
  tags: *id046
  url: /providers/virustotal/
- agent_band: agent-aware
  agent_readiness: 16.2
  band: developing
  in_catalog: true
  kin_score: 41.4
  mcp: *id047
  name: Yahoo Mail
  slug: yahoo
  status: profiled
  tags: *id048
  url: /providers/yahoo/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.3
  mcp: *id049
  name: Yandex Mail
  slug: yandex-mail
  status: profiled
  tags: *id050
  url: /providers/yandex-mail/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 36.4
  mcp: *id051
  name: Zoho Mail
  slug: zoho-mail
  status: profiled
  tags: *id052
  url: /providers/zoho-mail/
siblings:
- name: Mail-in-a-Box
  rows: 5
  url: /applications/email-client/mail-in-a-box/
- name: 'mailcow: dockerized'
  rows: 2
  url: /applications/email-client/mailcow-dockerized/
- name: Proton Mail (Android)
  rows: 3
  url: /applications/email-client/proton-mail-android/
- name: Roundcube Webmail
  rows: 11
  url: /applications/email-client/roundcube-webmail/
- name: Stalwart Mail Server
  rows: 19
  url: /applications/email-client/stalwart-mail-server/
- name: Thunderbird for Android
  rows: 7
  url: /applications/email-client/thunderbird-for-android/
sitemap: true
title: 'FairEmail: Email Client & Hosting reference app'
---
