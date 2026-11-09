---
access: understanding
agent_layer: []
apps:
- anchor: fairemail
  counts:
    declared: 0
    observed: 26
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
    layer: domain
    name: Zoho Mail
    provider: zoho-mail
    says: ships the Zoho Mail SDK or integration code
    source: https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
    tier: observed
  kind: open-source-saas
  name: FairEmail
  page: /applications/email-client/fairemail/
  slug: fairemail
  url: https://github.com/M66B/FairEmail
- anchor: thunderbird-for-android
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/gradle/libs.versions.toml
  - route: source code
    url: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/app-thunderbird/src/release/kotlin/net/thunderbird/android/auth/TbOAuthConfigurationFactory.kt
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: AOL Mail
    provider: aol
    says: ships the AOL Mail SDK or integration code
    source: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/app-thunderbird/src/release/kotlin/net/thunderbird/android/auth/TbOAuthConfigurationFactory.kt
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Fastmail
    provider: fastmail
    says: ships the Fastmail SDK or integration code
    source: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/app-thunderbird/src/release/kotlin/net/thunderbird/android/auth/TbOAuthConfigurationFactory.kt
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Gmail
    provider: google-gmail
    says: ships the Gmail SDK or integration code
    source: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/app-thunderbird/src/release/kotlin/net/thunderbird/android/auth/TbOAuthConfigurationFactory.kt
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
    name: Google Play Billing
    provider: google-play
    says: ships the Google Play Billing SDK or integration code
    source: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/gradle/libs.versions.toml
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
    name: Mozilla Glean
    provider: mozilla
    says: ships the Mozilla Glean SDK or integration code
    source: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Outlook / Microsoft 365
    provider: microsoft-outlook
    says: ships the Outlook / Microsoft 365 SDK or integration code
    source: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/app-thunderbird/src/release/kotlin/net/thunderbird/android/auth/TbOAuthConfigurationFactory.kt
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Yahoo Mail
    provider: yahoo
    says: ships the Yahoo Mail SDK or integration code
    source: https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/app-thunderbird/src/release/kotlin/net/thunderbird/android/auth/TbOAuthConfigurationFactory.kt
    tier: observed
  kind: open-source-saas
  name: Thunderbird for Android
  page: /applications/email-client/thunderbird-for-android/
  slug: thunderbird-for-android
  url: https://github.com/thunderbird/thunderbird-android
- anchor: proton-mail-(android)
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/ProtonMail/android-mail/main/gradle/libs.versions.toml
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Firebase Cloud Messaging
    provider: firebase
    says: ships the Firebase Cloud Messaging SDK or integration code
    source: https://raw.githubusercontent.com/ProtonMail/android-mail/main/gradle/libs.versions.toml
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
    name: Google Play Billing
    provider: google-play
    says: ships the Google Play Billing SDK or integration code
    source: https://raw.githubusercontent.com/ProtonMail/android-mail/main/gradle/libs.versions.toml
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
    source: https://raw.githubusercontent.com/ProtonMail/android-mail/main/gradle/libs.versions.toml
    tier: observed
  kind: open-source-saas
  name: Proton Mail (Android)
  page: /applications/email-client/proton-mail-android/
  slug: proton-mail-android
  url: https://github.com/ProtonMail/android-mail
- anchor: mailcow:-dockerized
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: source code
    url: https://raw.githubusercontent.com/mailcow/mailcow-dockerized/master/data/Dockerfiles/acme/acme.sh
  - route: source code
    url: https://raw.githubusercontent.com/mailcow/mailcow-dockerized/master/generate_config.sh
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-620.50.50
      key: BC-620.50.50
      name: Cryptography and Key Management
      url: /capabilities/security-architecture-management/
      via_parent: Security Architecture Management
    credit: null
    layer: common
    name: Let's Encrypt
    provider: lets-encrypt
    says: ships the Let's Encrypt SDK or integration code
    source: https://raw.githubusercontent.com/mailcow/mailcow-dockerized/master/data/Dockerfiles/acme/acme.sh
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.40
      key: AE-150.10.40
      name: Email Security
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: Spamhaus
    provider: spamhaus
    says: ships the Spamhaus SDK or integration code
    source: https://raw.githubusercontent.com/mailcow/mailcow-dockerized/master/generate_config.sh
    tier: observed
  kind: self-hosted
  name: 'mailcow: dockerized'
  page: /applications/email-client/mailcow-dockerized/
  slug: mailcow-dockerized
  url: https://github.com/mailcow/mailcow-dockerized
- anchor: mail-in-a-box
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: source code
    url: https://github.com/mail-in-a-box/mailinabox/tree/main/setup
  - route: source code
    url: https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/management/backup.py
  - route: source code
    url: https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/management/status_checks.py
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/management/backup.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Backblaze B2
    provider: backblaze
    says: ships the Backblaze B2 SDK or integration code
    source: https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/management/backup.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.50.50
      key: BC-620.50.50
      name: Cryptography and Key Management
      url: /capabilities/security-architecture-management/
      via_parent: Security Architecture Management
    credit: null
    layer: common
    name: Let's Encrypt
    provider: lets-encrypt
    says: ships the Let's Encrypt SDK or integration code
    source: https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/management/ssl_certificates.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Nextcloud
    provider: nextcloud
    says: ships the Nextcloud SDK or integration code
    source: https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/setup/nextcloud.sh
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.40
      key: AE-150.10.40
      name: Email Security
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: Spamhaus
    provider: spamhaus
    says: ships the Spamhaus SDK or integration code
    source: https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/management/status_checks.py
    tier: observed
  kind: self-hosted
  name: Mail-in-a-Box
  page: /applications/email-client/mail-in-a-box/
  slug: mail-in-a-box
  url: https://github.com/mail-in-a-box/mailinabox
- anchor: stalwart-mail-server
  counts:
    declared: 0
    observed: 19
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/stalwartlabs/stalwart/main/crates/store/Cargo.toml
  - route: source code
    url: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
  - route: source code
    url: https://github.com/stalwartlabs/stalwart/tree/main/crates/common/src/enterprise/ai
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon Route 53
    provider: amazon-route-53
    says: ships the Amazon Route 53 SDK or integration code
    source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/stalwartlabs/stalwart/main/crates/store/Cargo.toml
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
    source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/enterprise/ai/anthropic.rs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: ships the Azure Blob Storage SDK or integration code
    source: https://raw.githubusercontent.com/stalwartlabs/stalwart/main/crates/store/Cargo.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: bunny.net
    provider: bunny-net
    says: ships the bunny.net SDK or integration code
    source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Cloudflare
    provider: cloudflare
    says: ships the Cloudflare SDK or integration code
    source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: deSEC
    provider: desec
    says: ships the deSEC SDK or integration code
    source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: DigitalOcean
    provider: digital-ocean
    says: ships the DigitalOcean SDK or integration code
    source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Elasticsearch
    provider: elastic
    says: ships the Elasticsearch SDK or integration code
    source: https://github.com/stalwartlabs/stalwart/tree/main/crates/store/src/backend/elastic
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Gandi
    provider: gandi
    says: ships the Gandi SDK or integration code
    source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Cloud DNS
    provider: google-cloud-dns
    says: ships the Google Cloud DNS SDK or integration code
    source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
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
    source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/enterprise/ai/gemini.rs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Hetzner
    provider: hetzner
    says: ships the Hetzner SDK or integration code
    source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Linode
    provider: linode
    says: ships the Linode SDK or integration code
    source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Meilisearch
    provider: meilisearch
    says: ships the Meilisearch SDK or integration code
    source: https://github.com/stalwartlabs/stalwart/tree/main/crates/store/src/backend/meili
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
    source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/enterprise/ai/openai.rs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: OVHcloud
    provider: ovh-cloud
    says: ships the OVHcloud SDK or integration code
    source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Porkbun
    provider: porkbun
    says: ships the Porkbun SDK or integration code
    source: https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
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
    name: Redis
    provider: redis
    says: ships the Redis SDK or integration code
    source: https://raw.githubusercontent.com/stalwartlabs/stalwart/main/crates/store/Cargo.toml
    tier: observed
  kind: self-hosted
  name: Stalwart Mail Server
  page: /applications/email-client/stalwart-mail-server/
  slug: stalwart-mail-server
  url: https://github.com/stalwartlabs/stalwart
- anchor: roundcube-webmail
  counts:
    declared: 2
    observed: 9
  evidence:
  - route: source code
    url: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
  - route: source code
    url: https://raw.githubusercontent.com/roundcube/roundcubemail/master/config/defaults.inc.php
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-926
      key: AE-926
      name: Web Hosting & Control Panels
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: cPanel
    provider: cpanel
    says: ships the cPanel SDK or integration code
    source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
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
    name: DirectAdmin
    provider: directadmin
    says: ships the DirectAdmin SDK or integration code
    source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
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
    name: DomainFactory
    provider: domainfactory
    says: ships the DomainFactory SDK or integration code
    source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.60
      key: AE-160.60
      name: Credential Security
      url: /capabilities/credential-security/
      via_parent: null
    credit: null
    layer: common
    name: Have I Been Pwned
    provider: have-i-been-pwned
    says: ships the Have I Been Pwned SDK or integration code
    source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
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
    name: Mail-in-a-Box
    provider: mail-in-a-box
    says: ships the Mail-in-a-Box SDK or integration code
    source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
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
    name: mailcow
    provider: mailcow
    says: ships the mailcow SDK or integration code
    source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
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
    name: Modoboa
    provider: modoboa
    says: ships the Modoboa SDK or integration code
    source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
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
    name: Plesk
    provider: plesk
    says: ships the Plesk SDK or integration code
    source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
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
    name: Stalwart
    provider: stalwart
    says: ships the Stalwart SDK or integration code
    source: https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Gmail
    provider: google-gmail
    says: lists Gmail as an integration
    source: https://raw.githubusercontent.com/roundcube/roundcubemail/master/config/defaults.inc.php
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
    name: Outlook.com
    provider: microsoft-outlook
    says: lists Outlook.com as an integration
    source: https://raw.githubusercontent.com/roundcube/roundcubemail/master/config/defaults.inc.php
    tier: declared
  kind: self-hosted
  name: Roundcube Webmail
  page: /applications/email-client/roundcube-webmail/
  slug: roundcube-webmail
  url: https://github.com/roundcube/roundcubemail
author: API Evangelist
candidates: []
credits: []
html: public
id: email-client
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Productivity
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Communication
  store: google-play
  url: https://play.google.com/store/apps/category/COMMUNICATION
- category: Communication - Email - Complete Solutions
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#communication---email---complete-solutions
- category: Communication - Email - Webmail Clients
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#communication---email---webmail-clients
- category: Email
  store: zapier
  url: https://zapier.com/apps
name: Email Client & Hosting
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: IMAP/SMTP/OAuth presets and Graph/JMAP access to hosted mailboxes are the core of every client
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.40
    key: AE-150.10.40
    name: Email Security
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: domain
  why: DNSBL/reputation lookups and attachment malware scanning
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: AI summaries, replies and LLM spam verdicts
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: domain
  why: translate received messages
- capability:
    attribution: API Evangelist extension
    id: AE-110.40
    key: AE-110.40
    name: Language & Document Understanding
    url: /capabilities/language-document-understanding/
    via_parent: null
  fit: exact
  layer: domain
  why: 'grammar/spell checking (gap: no grammar node)'
- capability:
    attribution: API Evangelist extension
    id: AE-160.60
    key: AE-160.60
    name: Credential Security
    url: /capabilities/credential-security/
    via_parent: null
  fit: exact
  layer: common
  why: breached-password checks
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: common
  why: sender IP lookup
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: new-mail push
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: exact
  layer: common
  why: paid tiers through Google Play
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash and error reporting
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: client telemetry
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  fit: exact
  layer: common
  why: blob store and backups
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: store backends; full-text search engines filed here as gap
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  fit: gap
  layer: common
  why: ACME certificates, DNS record automation and hosting control panels (all gap)
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 49.5
      apps:
      - FairEmail
      - Roundcube Webmail
      - Thunderbird for Android
      band: exemplar
      in_catalog: true
      kin_score: 70.6
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Outlook.com
      slug: microsoft-outlook
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
      - https://raw.githubusercontent.com/roundcube/roundcubemail/master/config/defaults.inc.php
      - https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/app-thunderbird/src/release/kotlin/net/thunderbird/android/auth/TbOAuthConfigurationFactory.kt
      status: profiled
      tags:
      - Calendar
      - Contacts
      - Email
      - Enterprise
      tier: observed
      url: /providers/microsoft-outlook/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - FairEmail
      - Roundcube Webmail
      - Thunderbird for Android
      band: developing
      in_catalog: true
      kin_score: 44.1
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
      - https://raw.githubusercontent.com/roundcube/roundcubemail/master/config/defaults.inc.php
      - https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/app-thunderbird/src/release/kotlin/net/thunderbird/android/auth/TbOAuthConfigurationFactory.kt
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: observed
      url: /providers/google-gmail/
    - agent_band: agent-ready
      agent_readiness: 36.1
      apps:
      - FairEmail
      - Thunderbird for Android
      band: developing
      in_catalog: true
      kin_score: 46.2
      mcp:
        status: none
      name: AOL Mail
      slug: aol
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
      - https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/app-thunderbird/src/release/kotlin/net/thunderbird/android/auth/TbOAuthConfigurationFactory.kt
      status: profiled
      tags:
      - Advertising
      - Digital Media
      - Entertainment
      - News
      tier: observed
      url: /providers/aol/
    - agent_band: agent-aware
      agent_readiness: 16.2
      apps:
      - FairEmail
      - Thunderbird for Android
      band: developing
      in_catalog: true
      kin_score: 41.4
      mcp:
        status: none
      name: Yahoo Mail
      slug: yahoo
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
      - https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/app-thunderbird/src/release/kotlin/net/thunderbird/android/auth/TbOAuthConfigurationFactory.kt
      status: profiled
      tags:
      - Advertising
      - DSP
      - Fantasy Sports
      - Programmatic Advertising
      tier: observed
      url: /providers/yahoo/
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - FairEmail
      - Thunderbird for Android
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        status: none
      name: Fastmail
      slug: fastmail
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
      - https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/app-thunderbird/src/release/kotlin/net/thunderbird/android/auth/TbOAuthConfigurationFactory.kt
      status: profiled
      tags:
      - Business
      - Email
      - Privacy
      - Security
      tier: observed
      url: /providers/fastmail/
    - agent_band: agent-ready
      agent_readiness: 37.0
      apps:
      - FairEmail
      band: exemplar
      in_catalog: true
      kin_score: 70.1
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Graph
      slug: microsoft-graph
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/MicrosoftGraph.java
      status: profiled
      tags:
      - Azure AD
      - Collaboration
      - Contacts
      - Microsoft Graph
      tier: observed
      url: /providers/microsoft-graph/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - FairEmail
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Apple iCloud Mail
      slug: apple
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - FairEmail
      band: thin
      in_catalog: true
      kin_score: 36.4
      mcp:
        status: none
      name: Zoho Mail
      slug: zoho-mail
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
      status: profiled
      tags:
      - Collaboration
      - Email
      - Mail
      - Messaging
      tier: observed
      url: /providers/zoho-mail/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Mail-in-a-Box
      band: thin
      in_catalog: true
      kin_score: 33.0
      mcp:
        status: none
      name: Nextcloud
      slug: nextcloud
      sources:
      - https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/setup/nextcloud.sh
      status: profiled
      tags:
      - Collaboration
      - File Sharing
      - File Sync
      - Self-Hosted
      tier: observed
      url: /providers/nextcloud/
    - agent_band: agent-aware
      agent_readiness: 10.8
      apps:
      - FairEmail
      band: emerging
      in_catalog: true
      kin_score: 20.6
      mcp:
        source: https://github.com/ionos-cloud/ionoscloud-mcp
        status: verified
      name: IONOS
      slug: ionos
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
      status: profiled
      tags:
      - Cloud
      - Company
      - Domains
      - Hosting
      tier: observed
      url: /providers/ionos/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - FairEmail
      band: emerging
      in_catalog: true
      kin_score: 19.6
      mcp:
        status: unknown
      name: mailbox.org
      slug: mailbox-org
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
      status: profiled
      tags:
      - Collaboration
      - Email
      - GDPR
      - Privacy
      tier: observed
      url: /providers/mailbox-org/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - FairEmail
      band: emerging
      in_catalog: true
      kin_score: 18.3
      mcp:
        status: none
      name: Yandex Mail
      slug: yandex-mail
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
      status: profiled
      tags:
      - Cloud
      - Communications
      - Company
      - Email
      tier: observed
      url: /providers/yandex-mail/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - FairEmail
      band: emerging
      in_catalog: true
      kin_score: 11.5
      mcp:
        status: none
      name: GMX Mail
      slug: gmx-net
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
      status: profiled
      tags:
      - Cloud
      - Company
      - Email
      - Free
      tier: observed
      url: /providers/gmx-net/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - FairEmail
      band: minimal
      in_catalog: true
      kin_score: 10.5
      mcp:
        status: none
      name: Posteo
      slug: posteo
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/res/xml/providers.xml
      status: profiled
      tags:
      - Email
      - Privacy
      - Security
      - Sustainability
      tier: observed
      url: /providers/posteo/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.40
      key: AE-150.10.40
      name: Email Security
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - FairEmail
      - Mail-in-a-Box
      - 'mailcow: dockerized'
      band: emerging
      in_catalog: true
      kin_score: 11.8
      mcp:
        status: none
      name: Spamhaus
      slug: spamhaus
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/DnsBlockList.java
      - https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/management/status_checks.py
      - https://raw.githubusercontent.com/mailcow/mailcow-dockerized/master/generate_config.sh
      status: profiled
      tags:
      - Anti-Spam
      - Company
      - Reputation
      - Security
      tier: observed
      url: /providers/spamhaus/
    - agent_band: agent-ready
      agent_readiness: 30.9
      apps:
      - FairEmail
      band: developing
      in_catalog: true
      kin_score: 40.1
      mcp:
        source: https://github.com/VirusTotal/virustotal-mcp
        status: verified
      name: VirusTotal
      slug: virustotal
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/VirusTotal.java
      status: profiled
      tags:
      - Anti Malware
      - File Analysis
      - Security
      - Threat Intelligence
      tier: observed
      url: /providers/virustotal/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - FairEmail
      band: minimal
      in_catalog: true
      kin_score: 8.9
      mcp:
        status: unknown
      name: NordSpam
      slug: nordspam
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/DnsBlockList.java
      status: profiled
      tags:
      - Company
      - DNSBL
      - Security
      - Spam
      tier: observed
      url: /providers/nordspam/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - FairEmail
      band: minimal
      in_catalog: true
      kin_score: 3.4
      mcp:
        status: unknown
      name: SpamCop
      slug: spamcop
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/DnsBlockList.java
      status: profiled
      tags:
      - Anti-Spam
      - Email
      - Security
      - Spam
      tier: observed
      url: /providers/spamcop/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - FairEmail
      band: minimal
      in_catalog: true
      kin_score: 3.1
      mcp:
        status: unknown
      name: UCEPROTECT
      slug: uceprotect
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/DnsBlockList.java
      status: profiled
      tags:
      - Blacklist
      - Company
      - Email Security
      - Spam Protection
      tier: observed
      url: /providers/uceprotect/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - FairEmail
      band: minimal
      in_catalog: true
      kin_score: 1.8
      mcp:
        status: none
      name: Barracuda Networks
      slug: barracuda-networks
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/DnsBlockList.java
      status: profiled
      tags:
      - Company
      - Security
      tier: observed
      url: /providers/barracuda-networks/
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.6
      apps:
      - Stalwart Mail Server
      band: exemplar
      in_catalog: true
      kin_score: 70.2
      mcp:
        source: https://www.elastic.co/docs/solutions/search/mcp
        status: verified
      name: Elasticsearch
      slug: elastic
      sources:
      - https://github.com/stalwartlabs/stalwart/tree/main/crates/store/src/backend/elastic
      status: profiled
      tags:
      - Analytics
      - Observability
      - Search
      - Security
      tier: observed
      url: /providers/elastic/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Stalwart Mail Server
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        source: https://github.com/meilisearch/meilisearch-mcp
        status: verified
      name: Meilisearch
      slug: meilisearch
      sources:
      - https://github.com/stalwartlabs/stalwart/tree/main/crates/store/src/backend/meili
      status: profiled
      tags:
      - AI Search
      - Full-Text Search
      - Hybrid Search
      - Open Source
      tier: observed
      url: /providers/meilisearch/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.40
      key: AE-110.40.40
      name: Grammar & Writing Assistance
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - FairEmail
      band: thin
      in_catalog: true
      kin_score: 29.5
      mcp:
        status: none
      name: LanguageTool
      slug: languagetool
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/LanguageTool.java
      status: profiled
      tags:
      - Grammar
      - Language
      - Proofreading
      - Spell Check
      tier: observed
      url: /providers/languagetool/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.4
      apps:
      - FairEmail
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://github.com/DeepL/deepl-mcp-server
        status: verified
      name: DeepL
      slug: deepl
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/DeepL.java
      status: profiled
      tags:
      - Artificial Intelligence
      - Deep Learning
      - Glossary
      - Localization
      tier: observed
      url: /providers/deepl/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-927
      key: AE-927
      name: Domain Registration & Managed DNS
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-native
      agent_readiness: 69.6
      apps:
      - Stalwart Mail Server
      band: exemplar
      in_catalog: true
      kin_score: 82.8
      mcp:
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare
      slug: cloudflare
      sources:
      - https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
      status: profiled
      tags:
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: observed
      url: /providers/cloudflare/
    - agent_band: agent-ready
      agent_readiness: 42.1
      apps:
      - Stalwart Mail Server
      band: exemplar
      in_catalog: true
      kin_score: 66.9
      mcp:
        source: https://github.com/linode/mcp-cluster-api
        status: verified
      name: Linode
      slug: linode
      sources:
      - https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
      status: profiled
      tags:
      - Cloud Computing
      - Infrastructure-as-a-Service
      - Kubernetes
      - Virtual Machines
      tier: observed
      url: /providers/linode/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Stalwart Mail Server
      band: strong
      in_catalog: true
      kin_score: 57.2
      mcp:
        status: none
      name: Google Cloud DNS
      slug: google-cloud-dns
      sources:
      - https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
      status: profiled
      tags:
      - DNS
      - Domain Names
      - Google Cloud
      - Name Resolution
      tier: observed
      url: /providers/google-cloud-dns/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Stalwart Mail Server
      band: strong
      in_catalog: true
      kin_score: 56.9
      mcp:
        status: none
      name: Amazon Route 53
      slug: amazon-route-53
      sources:
      - https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
      status: profiled
      tags:
      - Amazon Web Services
      - DNS
      - Domain Registration
      - Health Checks
      tier: observed
      url: /providers/amazon-route-53/
    - agent_band: agent-ready
      agent_readiness: 44.6
      apps:
      - Stalwart Mail Server
      band: developing
      in_catalog: true
      kin_score: 45.0
      mcp:
        source: https://docs.digitalocean.com/reference/mcp/
        status: verified
      name: DigitalOcean
      slug: digital-ocean
      sources:
      - https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
      status: profiled
      tags:
      - Cloud
      - Compute
      - Infrastructure
      - Servers
      tier: observed
      url: /providers/digital-ocean/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Stalwart Mail Server
      band: developing
      in_catalog: true
      kin_score: 41.9
      mcp:
        source: https://mcp.eu.ovhcloud.com/mcp
        status: verified
      name: OVHcloud
      slug: ovh-cloud
      sources:
      - https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
      status: profiled
      tags:
      - Cloud
      - Compute
      - Hosting
      - Servers
      tier: observed
      url: /providers/ovh-cloud/
    - agent_band: agent-aware
      agent_readiness: 26.3
      apps:
      - Stalwart Mail Server
      band: developing
      in_catalog: true
      kin_score: 39.7
      mcp:
        status: none
      name: Hetzner
      slug: hetzner
      sources:
      - https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
      status: profiled
      tags:
      - Cloud Hosting
      - DNS
      - Infrastructure
      - Servers
      tier: observed
      url: /providers/hetzner/
    - agent_band: agent-aware
      agent_readiness: 26.1
      apps:
      - Stalwart Mail Server
      band: thin
      in_catalog: true
      kin_score: 39.1
      mcp:
        status: none
      name: bunny.net
      slug: bunny-net
      sources:
      - https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
      status: profiled
      tags:
      - CDN
      - Edge
      - Storage
      - Video
      tier: observed
      url: /providers/bunny-net/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Stalwart Mail Server
      band: thin
      in_catalog: true
      kin_score: 29.0
      mcp:
        status: none
      name: Gandi
      slug: gandi
      sources:
      - https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
      status: profiled
      tags:
      - DNS
      - Domain Registrar
      - Domains
      - Email
      tier: observed
      url: /providers/gandi/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Stalwart Mail Server
      band: minimal
      in_catalog: true
      kin_score: 8.7
      mcp:
        status: none
      name: deSEC
      slug: desec
      sources:
      - https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
      status: profiled
      tags:
      - Company
      - DNS
      - Open Source
      - Security
      tier: observed
      url: /providers/desec/
    - agent_band: null
      agent_readiness: null
      apps:
      - Stalwart Mail Server
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Porkbun
      slug: porkbun
      sources:
      - https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/network/dns/update.rs
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-926
      key: AE-926
      name: Web Hosting & Control Panels
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.9
      apps:
      - Roundcube Webmail
      band: exemplar
      in_catalog: true
      kin_score: 67.9
      mcp:
        status: none
      name: cPanel
      slug: cpanel
      sources:
      - https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
      status: profiled
      tags:
      - Control Panel
      - DNS
      - Domains
      - Email
      tier: observed
      url: /providers/cpanel/
    - agent_band: agent-aware
      agent_readiness: 26.5
      apps:
      - Roundcube Webmail
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        status: none
      name: Modoboa
      slug: modoboa
      sources:
      - https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
      status: profiled
      tags:
      - Email
      - Mail Server
      - Open Source
      - Webmail
      tier: observed
      url: /providers/modoboa/
    - agent_band: agent-aware
      agent_readiness: 19.7
      apps:
      - Roundcube Webmail
      band: thin
      in_catalog: true
      kin_score: 34.7
      mcp:
        status: none
      name: Plesk
      slug: plesk
      sources:
      - https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
      status: profiled
      tags:
      - Company
      - Control Panel
      - Server Management
      - Web Hosting
      tier: observed
      url: /providers/plesk/
    - agent_band: agent-aware
      agent_readiness: 22.6
      apps:
      - Roundcube Webmail
      band: thin
      in_catalog: true
      kin_score: 32.8
      mcp:
        status: none
      name: Mail-in-a-Box
      slug: mail-in-a-box
      sources:
      - https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
      status: profiled
      tags:
      - Company
      - Email
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/mail-in-a-box/
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - Roundcube Webmail
      band: thin
      in_catalog: true
      kin_score: 27.5
      mcp:
        status: none
      name: Stalwart
      slug: stalwart
      sources:
      - https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
      status: profiled
      tags:
      - Collaboration
      - Email
      - Open Source
      - Rust
      tier: observed
      url: /providers/stalwart/
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - Roundcube Webmail
      band: emerging
      in_catalog: true
      kin_score: 23.5
      mcp:
        status: unknown
      name: DirectAdmin
      slug: directadmin
      sources:
      - https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
      status: profiled
      tags:
      - Control Panel
      - Hosting
      - Server Management
      - Web Hosting
      tier: observed
      url: /providers/directadmin/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - Roundcube Webmail
      band: minimal
      in_catalog: true
      kin_score: 8.5
      mcp:
        status: none
      name: mailcow
      slug: mailcow
      sources:
      - https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
      status: profiled
      tags:
      - Company
      - Docker
      - Email
      - Open Source
      tier: observed
      url: /providers/mailcow/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Roundcube Webmail
      band: minimal
      in_catalog: true
      kin_score: 8.4
      mcp:
        status: none
      name: DomainFactory
      slug: domainfactory
      sources:
      - https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
      status: profiled
      tags:
      - Company
      - Domains
      - Hosting
      - Web Hosting
      tier: observed
      url: /providers/domainfactory/
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Mail-in-a-Box
      - Stalwart Mail Server
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/management/backup.py
      - https://raw.githubusercontent.com/stalwartlabs/stalwart/main/crates/store/Cargo.toml
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 40.9
      apps:
      - Stalwart Mail Server
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://raw.githubusercontent.com/stalwartlabs/stalwart/main/crates/store/Cargo.toml
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Mail-in-a-Box
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        source: https://github.com/backblaze-labs/b2-mcp
        status: verified
      name: Backblaze B2
      slug: backblaze
      sources:
      - https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/management/backup.py
      status: profiled
      tags:
      - Backup
      - Cloud Storage
      - Object Storage
      - Storage
      tier: observed
      url: /providers/backblaze/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.60
      key: AE-160.60
      name: Credential Security
      url: /capabilities/credential-security/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.0
      apps:
      - FairEmail
      - Roundcube Webmail
      band: developing
      in_catalog: true
      kin_score: 48.4
      mcp:
        status: none
      name: Have I Been Pwned
      slug: have-i-been-pwned
      sources:
      - https://github.com/roundcube/roundcubemail/tree/master/plugins/password/drivers
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/build.gradle
      status: profiled
      tags:
      - Data Breaches
      - Identity
      - Pwned Passwords
      - Security
      tier: observed
      url: /providers/have-i-been-pwned/
  - capability:
      attribution: Turbo EA
      id: BC-620.50.50
      key: BC-620.50.50
      name: Cryptography and Key Management
      url: /capabilities/security-architecture-management/
      via_parent: Security Architecture Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.2
      apps:
      - Mail-in-a-Box
      - 'mailcow: dockerized'
      band: emerging
      in_catalog: true
      kin_score: 24.3
      mcp:
        status: none
      name: Let's Encrypt
      slug: lets-encrypt
      sources:
      - https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/management/ssl_certificates.py
      - https://raw.githubusercontent.com/mailcow/mailcow-dockerized/master/data/Dockerfiles/acme/acme.sh
      status: profiled
      tags:
      - Certificates
      - Linux Foundation
      - Security
      - TLS
      tier: observed
      url: /providers/lets-encrypt/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - FairEmail
      band: strong
      in_catalog: true
      kin_score: 63.2
      mcp:
        source: https://github.com/ipinfo/mcp
        status: verified
      name: IPinfo
      slug: ipinfo
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/IPInfo.java
      status: profiled
      tags:
      - ASN
      - IP Geolocation
      - IP Intelligence
      - Privacy Detection
      tier: observed
      url: /providers/ipinfo/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - FairEmail
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        source: https://github.com/ip2location/mcp-ip2location-io
        status: verified
      name: IP2Location
      slug: ip2location
      sources:
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/java/eu/faircode/email/IPInfo.java
      status: profiled
      tags:
      - Geocoding
      - Public APIs
      tier: observed
      url: /providers/ip2location/
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Proton Mail (Android)
      - Thunderbird for Android
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        status: none
      name: Google Play Billing
      slug: google-play
      sources:
      - https://raw.githubusercontent.com/ProtonMail/android-mail/main/gradle/libs.versions.toml
      - https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Android
      - Application
      - Google Play
      - In-App Purchases
      tier: observed
      url: /providers/google-play/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-native
      agent_readiness: 49.8
      apps:
      - Stalwart Mail Server
      band: developing
      in_catalog: true
      kin_score: 47.4
      mcp:
        source: https://github.com/redis/mcp-redis
        status: verified
      name: Redis
      slug: redis
      sources:
      - https://raw.githubusercontent.com/stalwartlabs/stalwart/main/crates/store/Cargo.toml
      status: profiled
      tags:
      - Cache
      - Database
      - In-Memory
      - Key-Value Store
      tier: observed
      url: /providers/redis/
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
      - Proton Mail (Android)
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/ProtonMail/android-mail/main/gradle/libs.versions.toml
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
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - Thunderbird for Android
      band: emerging
      in_catalog: true
      kin_score: 16.4
      mcp:
        source: https://github.com/mozilla/firefox-devtools-mcp
        status: verified
      name: Mozilla Glean
      slug: mozilla
      sources:
      - https://raw.githubusercontent.com/thunderbird/thunderbird-android/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Data Engineering
      - Open Source
      - SDK
      - Telemetry
      tier: observed
      url: /providers/mozilla/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Proton Mail (Android)
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase Cloud Messaging
      slug: firebase
      sources:
      - https://raw.githubusercontent.com/ProtonMail/android-mail/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
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
    - agent_band: agent-native
      agent_readiness: 58.4
      apps:
      - FairEmail
      - Stalwart Mail Server
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/enterprise/ai/openai.rs
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/build.gradle
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - FairEmail
      - Stalwart Mail Server
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/enterprise/ai/gemini.rs
      - https://raw.githubusercontent.com/M66B/FairEmail/master/app/build.gradle
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Stalwart Mail Server
      band: exemplar
      in_catalog: true
      kin_score: 87.5
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/stalwartlabs/stalwart/blob/main/crates/common/src/enterprise/ai/anthropic.rs
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
  layer: agent
summary:
  coverage_pct: 98.3
  declared_only: 0
  distinct_providers: 58
  in_catalog: 57
  mcp:
    documented: 0
    none: 29
    unchecked: 1
    verified: 23
  mcp_verified: 23
  mean_kin_score: 39.9
  observed: 58
  queued: 1
  reference_apps: 7
title: 'Email Client & Hosting: application blueprint'
---
