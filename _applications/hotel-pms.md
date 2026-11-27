---
access: understanding
agent_layer: []
apps:
- anchor: qloapps
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/Qloapps/QloApps/develop/composer.json
  - route: source code
    url: https://github.com/Qloapps/QloApps/tree/develop/modules
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
    name: Duitku
    provider: duitku
    says: ships the Duitku SDK or integration code
    source: https://github.com/Qloapps/QloApps/tree/develop/modules
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4010.40
      key: metasearch-distribution-management
      name: Metasearch Distribution Management
      url: /capabilities/metasearch-distribution-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Hotel Ads
    provider: google
    says: ships the Google Hotel Ads SDK or integration code
    source: https://github.com/Qloapps/QloApps/tree/develop/modules
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
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://github.com/Qloapps/QloApps/tree/develop/modules
    tier: observed
  kind: self-hosted
  name: QloApps
  page: /applications/hotel-pms/qloapps/
  slug: qloapps
  url: https://github.com/Qloapps/QloApps
- anchor: cloudbeds
  counts:
    declared: 16
    observed: 0
  evidence:
  - route: integrations page
    url: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
  - route: integrations page
    url: https://myfrontdesk.cloudbeds.com/hc/en-us/articles/360003183494-Apps-integrated-with-myfrontdesk
  - route: integrations page
    url: https://www.cloudbeds.com/integrations/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-200.90
      key: AE-200.90
      name: Physical Access Control & Mobile Keys
      url: /capabilities/physical-access-control-mobile-keys/
      via_parent: null
    credit: null
    layer: domain
    name: 4SUITES
    provider: 4suites
    says: lists 4SUITES as an integration
    source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    credit: null
    layer: domain
    name: Airbnb
    provider: airbnb
    says: lists Airbnb as an integration
    source: https://www.cloudbeds.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30
      key: AE-160.30
      name: Identity Verification
      url: /capabilities/identity-verification/
      via_parent: null
    credit: null
    layer: domain
    name: Autohost
    provider: autohost
    says: lists Autohost as an integration
    source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    credit: null
    layer: domain
    name: Booking.com
    provider: booking-com
    says: lists Booking.com as an integration
    source: https://www.cloudbeds.com/integrations/
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
    name: CartStack
    provider: cartstack
    says: lists CartStack as an integration
    source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30.10
      key: AE-160.30.10
      name: Document Verification
      url: /capabilities/identity-verification/
      via_parent: Identity Verification
    credit: null
    layer: domain
    name: Chekin
    provider: chekin
    says: lists Chekin as an integration
    source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    credit: null
    layer: domain
    name: Expedia
    provider: expedia-group
    says: lists Expedia as an integration
    source: https://www.cloudbeds.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.90
      key: AE-200.90
      name: Physical Access Control & Mobile Keys
      url: /capabilities/physical-access-control-mobile-keys/
      via_parent: null
    credit: null
    layer: domain
    name: FLEXIPASS
    provider: flexipass
    says: lists FLEXIPASS as an integration
    source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4060.20
      key: housekeeping-operations
      name: Housekeeping Operations
      url: /capabilities/housekeeping-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Flexkeeping
    provider: flexkeeping
    says: lists Flexkeeping as an integration
    source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Lightspeed
    provider: lightspeed
    says: lists Lightspeed as an integration
    source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Poster POS
    provider: poster
    says: lists Poster POS as an integration
    source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: null
    layer: domain
    name: Reputize
    provider: reputize
    says: lists Reputize as an integration
    source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
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
    name: The Hotels Network
    provider: the-hotels-network
    says: lists The Hotels Network as an integration
    source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: null
    layer: domain
    name: TrustYou
    provider: trustyou
    says: lists TrustYou as an integration
    source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4060.10.30
      key: BC-4060.10.30
      name: Room Assignment & Upgrade
      url: /capabilities/front-office-operations/
      via_parent: Front Office Operations
    credit: null
    layer: domain
    name: UpsellGuru
    provider: upsellguru
    says: lists UpsellGuru as an integration
    source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30
      key: ground-transport
      name: Ground Transport
      url: /capabilities/ground-transport/
      via_parent: null
    credit: null
    layer: domain
    name: Welcome PickUps
    provider: welcome-pickups
    says: lists Welcome PickUps as an integration
    source: https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
    tier: declared
  kind: commercial
  name: Cloudbeds
  page: /applications/hotel-pms/cloudbeds/
  slug: cloudbeds
  url: https://www.cloudbeds.com/
- anchor: mews
  counts:
    declared: 13
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.mews.com/en/marketplace
  - route: integrations page
    url: https://www.mews.com/en/products/payments
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: 24SevenOffice
    provider: 24sevenoffice
    says: lists 24SevenOffice as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4040
      key: guest-traveller-management
      name: Guest & Traveller Management
      url: /capabilities/guest-traveller-management/
      via_parent: null
    credit: null
    layer: domain
    name: Alliants
    provider: alliants
    says: lists Alliants as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amadeus iHotelier
    provider: amadeus
    says: lists Amadeus iHotelier as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30
      key: consumer-payment-options
      name: Consumer Payment Options
      url: /capabilities/consumer-payment-options/
      via_parent: null
    credit: null
    layer: domain
    name: Apple Pay
    provider: apple-pay
    says: lists Apple Pay as an integration
    source: https://www.mews.com/en/products/payments
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4030
      key: travel-revenue-yield-management
      name: Travel Revenue & Yield Management
      url: /capabilities/travel-revenue-yield-management/
      via_parent: null
    credit: null
    layer: domain
    name: BEONX
    provider: beonx
    says: lists BEONX as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    credit: null
    layer: domain
    name: Booking.com
    provider: booking-com
    says: lists Booking.com as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30.10
      key: AE-160.30.10
      name: Document Verification
      url: /capabilities/identity-verification/
      via_parent: Identity Verification
    credit: null
    layer: domain
    name: Chekin
    provider: chekin
    says: lists Chekin as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    credit: null
    layer: domain
    name: Expedia
    provider: expedia-group
    says: lists Expedia as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30
      key: consumer-payment-options
      name: Consumer Payment Options
      url: /capabilities/consumer-payment-options/
      via_parent: null
    credit: null
    layer: domain
    name: Google Pay
    provider: google-pay
    says: lists Google Pay as an integration
    source: https://www.mews.com/en/products/payments
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4030
      key: travel-revenue-yield-management
      name: Travel Revenue & Yield Management
      url: /capabilities/travel-revenue-yield-management/
      via_parent: null
    credit: null
    layer: domain
    name: profitize
    provider: profitize
    says: lists profitize as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.50
      key: channel-manager-operations
      name: Channel Manager Operations
      url: /capabilities/channel-manager-operations/
      via_parent: null
    credit: null
    layer: domain
    name: SiteMinder
    provider: siteminder
    says: lists SiteMinder as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4020
      key: reservation-booking-management
      name: Reservation & Booking Management
      url: /capabilities/reservation-booking-management/
      via_parent: null
    credit: null
    layer: domain
    name: Spalopia
    provider: spalopia
    says: lists Spalopia as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: null
    layer: domain
    name: Tripadvisor
    provider: tripadvisor
    says: lists Tripadvisor as an integration
    source: https://www.mews.com/en/marketplace
    tier: declared
  kind: commercial
  name: Mews
  page: /applications/hotel-pms/mews/
  slug: mews
  url: https://www.mews.com/
- anchor: apaleo
  counts:
    declared: 8
    observed: 0
  evidence:
  - route: documentation
    url: https://apaleo.dev/
  - route: integrations page
    url: https://store.apaleo.com/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4030
      key: travel-revenue-yield-management
      name: Travel Revenue & Yield Management
      url: /capabilities/travel-revenue-yield-management/
      via_parent: null
    credit: null
    layer: domain
    name: FLYR Hospitality
    provider: flyr
    says: lists FLYR Hospitality as an integration
    source: https://store.apaleo.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.10
      key: direct-channel-distribution-management
      name: Direct Channel Distribution Management
      url: /capabilities/direct-channel-distribution-management/
      via_parent: null
    credit: null
    layer: domain
    name: GauVendi
    provider: gauvendi
    says: lists GauVendi as an integration
    source: https://store.apaleo.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4030
      key: travel-revenue-yield-management
      name: Travel Revenue & Yield Management
      url: /capabilities/travel-revenue-yield-management/
      via_parent: null
    credit: null
    layer: domain
    name: happyhotel
    provider: happyhotel
    says: lists happyhotel as an integration
    source: https://store.apaleo.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.20
      key: AE-100.70.20
      name: Voice Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    credit: null
    layer: domain
    name: inCallio
    provider: incallio
    says: lists inCallio as an integration
    source: https://store.apaleo.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4040
      key: guest-traveller-management
      name: Guest & Traveller Management
      url: /capabilities/guest-traveller-management/
      via_parent: null
    credit: null
    layer: domain
    name: LIKE MAGIC
    provider: like-magic
    says: lists LIKE MAGIC as an integration
    source: https://store.apaleo.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4030
      key: travel-revenue-yield-management
      name: Travel Revenue & Yield Management
      url: /capabilities/travel-revenue-yield-management/
      via_parent: null
    credit: null
    layer: domain
    name: N2Pricing
    provider: n2pricing
    says: lists N2Pricing as an integration
    source: https://store.apaleo.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4060.10.30
      key: BC-4060.10.30
      name: Room Assignment & Upgrade
      url: /capabilities/front-office-operations/
      via_parent: Front Office Operations
    credit: null
    layer: domain
    name: Sponteous
    provider: sponteous
    says: lists Sponteous as an integration
    source: https://store.apaleo.com/
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
    name: umnify
    provider: umnify
    says: lists umnify as an integration
    source: https://store.apaleo.com/
    tier: declared
  kind: commercial
  name: apaleo
  page: /applications/hotel-pms/apaleo/
  slug: apaleo
  url: https://apaleo.com/
- anchor: hotelogix
  counts:
    declared: 32
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.hotelogix.com/marketplace/
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
    name: 2C2P
    provider: 2c2p
    says: lists 2C2P as an integration
    source: https://www.hotelogix.com/marketplace/
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
    name: Authorize.Net
    provider: authorizenet
    says: lists Authorize.Net as an integration
    source: https://www.hotelogix.com/marketplace/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.50
      key: channel-manager-operations
      name: Channel Manager Operations
      url: /capabilities/channel-manager-operations/
      via_parent: null
    credit: null
    layer: domain
    name: AxisRooms
    provider: axisrooms
    says: lists AxisRooms as an integration
    source: https://www.hotelogix.com/marketplace/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4030
      key: travel-revenue-yield-management
      name: Travel Revenue & Yield Management
      url: /capabilities/travel-revenue-yield-management/
      via_parent: null
    credit: null
    layer: domain
    name: BEONx
    provider: beonx
    says: lists BEONx as an integration
    source: https://www.hotelogix.com/marketplace/
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
    name: Capillary Technologies
    provider: capillary-technologies
    says: lists Capillary Technologies as an integration
    source: https://www.hotelogix.com/marketplace/
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
    name: CCAvenue
    provider: ccavenue
    says: lists CCAvenue as an integration
    source: https://www.hotelogix.com/marketplace/
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
    name: CyberSource
    provider: cybersource
    says: lists CyberSource as an integration
    source: https://www.hotelogix.com/marketplace/
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
    name: DOKU
    provider: doku
    says: lists DOKU as an integration
    source: https://www.hotelogix.com/marketplace/
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
    name: eWAY
    provider: eway
    says: lists eWAY as an integration
    source: https://www.hotelogix.com/marketplace/
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
    name: First Data
    provider: first-data
    says: lists First Data as an integration
    source: https://www.hotelogix.com/marketplace/
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
    name: Gupshup
    provider: gupshup
    says: lists Gupshup as an integration
    source: https://www.hotelogix.com/marketplace/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.50
      key: channel-manager-operations
      name: Channel Manager Operations
      url: /capabilities/channel-manager-operations/
      via_parent: null
    credit: null
    layer: domain
    name: HotelRunner
    provider: hotelrunner
    says: lists HotelRunner as an integration
    source: https://www.hotelogix.com/marketplace/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4030
      key: travel-revenue-yield-management
      name: Travel Revenue & Yield Management
      url: /capabilities/travel-revenue-yield-management/
      via_parent: null
    credit: null
    layer: domain
    name: Lighthouse
    provider: mylighthouse
    says: lists Lighthouse as an integration
    source: https://www.hotelogix.com/marketplace/
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
    source: https://www.hotelogix.com/marketplace/
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
    name: NetSuite
    provider: netsuite
    says: lists NetSuite as an integration
    source: https://www.hotelogix.com/marketplace/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.90
      key: AE-200.90
      name: Physical Access Control & Mobile Keys
      url: /capabilities/physical-access-control-mobile-keys/
      via_parent: null
    credit: null
    layer: domain
    name: Onity
    provider: onity
    says: lists Onity as an integration
    source: https://www.hotelogix.com/marketplace/
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
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://www.hotelogix.com/marketplace/
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
    name: PayU
    provider: payu
    says: lists PayU as an integration
    source: https://www.hotelogix.com/marketplace/
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
    name: QuickBooks
    provider: quickbooks
    says: lists QuickBooks as an integration
    source: https://www.hotelogix.com/marketplace/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.50
      key: channel-manager-operations
      name: Channel Manager Operations
      url: /capabilities/channel-manager-operations/
      via_parent: null
    credit: null
    layer: domain
    name: RateGain
    provider: rategain
    says: lists RateGain as an integration
    source: https://www.hotelogix.com/marketplace/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: null
    layer: domain
    name: ReviewPro
    provider: reviewpro
    says: lists ReviewPro as an integration
    source: https://www.hotelogix.com/marketplace/
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
    source: https://www.hotelogix.com/marketplace/
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
    name: SAP
    provider: sap
    says: lists SAP as an integration
    source: https://www.hotelogix.com/marketplace/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.50
      key: channel-manager-operations
      name: Channel Manager Operations
      url: /capabilities/channel-manager-operations/
      via_parent: null
    credit: null
    layer: domain
    name: SiteMinder
    provider: siteminder
    says: lists SiteMinder as an integration
    source: https://www.hotelogix.com/marketplace/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.50
      key: channel-manager-operations
      name: Channel Manager Operations
      url: /capabilities/channel-manager-operations/
      via_parent: null
    credit: null
    layer: domain
    name: STAAH
    provider: staah
    says: lists STAAH as an integration
    source: https://www.hotelogix.com/marketplace/
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
    source: https://www.hotelogix.com/marketplace/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.50
      key: channel-manager-operations
      name: Channel Manager Operations
      url: /capabilities/channel-manager-operations/
      via_parent: null
    credit: null
    layer: domain
    name: SynXis
    provider: sabre
    says: lists SynXis as an integration
    source: https://www.hotelogix.com/marketplace/
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
    name: Tally (TallyPrime)
    provider: tallyprime
    says: lists Tally (TallyPrime) as an integration
    source: https://www.hotelogix.com/marketplace/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: null
    layer: domain
    name: TrustYou
    provider: trustyou
    says: lists TrustYou as an integration
    source: https://www.hotelogix.com/marketplace/
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
    name: Worldline
    provider: worldline
    says: lists Worldline as an integration
    source: https://www.hotelogix.com/marketplace/
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
    source: https://www.hotelogix.com/marketplace/
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
    name: Zoho Books
    provider: zoho-books
    says: lists Zoho Books as an integration
    source: https://www.hotelogix.com/marketplace/
    tier: declared
  kind: commercial
  name: Hotelogix
  page: /applications/hotel-pms/hotelogix/
  slug: hotelogix
  url: https://www.hotelogix.com/
- anchor: beds24
  counts:
    declared: 12
    observed: 0
  evidence:
  - route: integrations page
    url: https://beds24.com/channel-manager.html
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    credit: null
    layer: domain
    name: Agoda
    provider: agoda
    says: lists Agoda as an integration
    source: https://beds24.com/channel-manager.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    credit: null
    layer: domain
    name: Airbnb
    provider: airbnb
    says: lists Airbnb as an integration
    source: https://beds24.com/channel-manager.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    credit: null
    layer: domain
    name: Booking.com
    provider: booking-com
    says: lists Booking.com as an integration
    source: https://beds24.com/channel-manager.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    credit: null
    layer: domain
    name: Expedia
    provider: expedia-group
    says: lists Expedia as an integration
    source: https://beds24.com/channel-manager.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4020
      key: reservation-booking-management
      name: Reservation & Booking Management
      url: /capabilities/reservation-booking-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Calendar
    provider: google-calendar
    says: lists Google Calendar as an integration
    source: https://beds24.com/channel-manager.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.40
      key: metasearch-distribution-management
      name: Metasearch Distribution Management
      url: /capabilities/metasearch-distribution-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Hotel Ads
    provider: google
    says: lists Google Hotel Ads as an integration
    source: https://beds24.com/channel-manager.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    credit: null
    layer: domain
    name: Hostelworld
    provider: hostelworld
    says: lists Hostelworld as an integration
    source: https://beds24.com/channel-manager.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    credit: null
    layer: domain
    name: Hotelbeds
    provider: hotelbeds
    says: lists Hotelbeds as an integration
    source: https://beds24.com/channel-manager.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    credit: null
    layer: domain
    name: Trip.com
    provider: tripcom
    says: lists Trip.com as an integration
    source: https://beds24.com/channel-manager.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.40
      key: metasearch-distribution-management
      name: Metasearch Distribution Management
      url: /capabilities/metasearch-distribution-management/
      via_parent: null
    credit: null
    layer: domain
    name: Tripadvisor
    provider: tripadvisor
    says: lists Tripadvisor as an integration
    source: https://beds24.com/channel-manager.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010.40
      key: metasearch-distribution-management
      name: Metasearch Distribution Management
      url: /capabilities/metasearch-distribution-management/
      via_parent: null
    credit: null
    layer: domain
    name: trivago
    provider: trivago
    says: lists trivago as an integration
    source: https://beds24.com/channel-manager.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    credit: null
    layer: domain
    name: Vrbo
    provider: vrbo
    says: lists Vrbo as an integration
    source: https://beds24.com/channel-manager.html
    tier: declared
  kind: commercial
  name: Beds24
  page: /applications/hotel-pms/beds24/
  slug: beds24
  url: https://beds24.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: hotel-pms
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Booking and Scheduling
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#booking-and-scheduling
- category: Hotel Management Software
  store: capterra
  url: https://www.capterra.com/hotel-management-software/
- category: Property Management Systems
  store: hoteltechreport
  url: https://hoteltechreport.com/operations/property-management-systems
- category: Channel, Revenue management, Accounting, Guest Experiences
  store: mews-marketplace
  url: https://www.mews.com/en/marketplace
- category: 19 categories (Payments, Channel Manager, Door Locks, ...)
  store: cloudbeds-marketplace
  url: https://myfrontdesk.cloudbeds.com/hc/en-us/articles/360003183494-Apps-integrated-with-myfrontdesk
- category: Channel Managers, Payment Gateways, Door Locks, ...
  store: hotelogix-marketplace
  url: https://www.hotelogix.com/marketplace/
name: Hotel Property Management
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
  why: 'hotel PMS integrations: payment processing'
- capability:
    attribution: Turbo EA
    id: BC-4010.40
    key: metasearch-distribution-management
    name: Metasearch Distribution Management
    url: /capabilities/metasearch-distribution-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: metasearch distribution'
- capability:
    attribution: Turbo EA
    id: BC-4010
    key: travel-distribution-channel-management
    name: Travel Distribution & Channel Management
    url: /capabilities/travel-distribution-channel-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: ota / travel distribution'
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: direct-booking marketing'
- capability:
    attribution: API Evangelist extension
    id: AE-160.30.10
    key: AE-160.30.10
    name: Document Verification
    url: /capabilities/identity-verification/
    via_parent: Identity Verification
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: guest id document verification'
- capability:
    attribution: API Evangelist extension
    id: AE-160.30
    key: AE-160.30
    name: Identity Verification
    url: /capabilities/identity-verification/
    via_parent: null
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: guest identity screening'
- capability:
    attribution: API Evangelist extension
    id: AE-200.90
    key: AE-200.90
    name: Physical Access Control & Mobile Keys
    url: /capabilities/physical-access-control-mobile-keys/
    via_parent: null
  fit: exact
  layer: domain
  why: 'Physical Access Control & Mobile Keys: FLEXIPASS, 4SUITES, Onity'
- capability:
    attribution: API Evangelist extension
    id: AE-210.30
    key: ground-transport
    name: Ground Transport
    url: /capabilities/ground-transport/
    via_parent: null
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: guest transfers'
- capability:
    attribution: Turbo EA
    id: BC-4060.10.30
    key: BC-4060.10.30
    name: Room Assignment & Upgrade
    url: /capabilities/front-office-operations/
    via_parent: Front Office Operations
  fit: exact
  layer: domain
  why: 'Room Assignment & Upgrade: UpsellGuru, Sponteous'
- capability:
    attribution: Turbo EA
    id: BC-4060.20
    key: housekeeping-operations
    name: Housekeeping Operations
    url: /capabilities/housekeeping-operations/
    via_parent: null
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: housekeeping'
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: f&b point of sale'
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: reviews & guest feedback'
- capability:
    attribution: Turbo EA
    id: BC-4030
    key: travel-revenue-yield-management
    name: Travel Revenue & Yield Management
    url: /capabilities/travel-revenue-yield-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: revenue & yield management'
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: accounting / general ledger'
- capability:
    attribution: Turbo EA
    id: BC-4010.50
    key: channel-manager-operations
    name: Channel Manager Operations
    url: /capabilities/channel-manager-operations/
    via_parent: null
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: channel manager connectivity'
- capability:
    attribution: Turbo EA
    id: BC-4020
    key: reservation-booking-management
    name: Reservation & Booking Management
    url: /capabilities/reservation-booking-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: 'hotel PMS integrations: ancillary booking & calendar sync'
- capability:
    attribution: Turbo EA
    id: BC-4040
    key: guest-traveller-management
    name: Guest & Traveller Management
    url: /capabilities/guest-traveller-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: 'hotel PMS integrations: guest journey'
- capability:
    attribution: API Evangelist extension
    id: AE-140.30
    key: consumer-payment-options
    name: Consumer Payment Options
    url: /capabilities/consumer-payment-options/
    via_parent: null
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: wallet payment options'
- capability:
    attribution: API Evangelist extension
    id: AE-100.70.20
    key: AE-100.70.20
    name: Voice Agents
    url: /capabilities/vertical-agents/
    via_parent: Vertical Agents
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: voice agents'
- capability:
    attribution: Turbo EA
    id: BC-4010.10
    key: direct-channel-distribution-management
    name: Direct Channel Distribution Management
    url: /capabilities/direct-channel-distribution-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: direct channel merchandising'
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: guest crm'
- capability:
    attribution: Turbo EA
    id: BC-420.40
    key: loyalty-retention-management
    name: Loyalty & Retention Management
    url: /capabilities/loyalty-retention-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: loyalty'
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: email marketing sends'
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: domain
  why: 'hotel PMS integrations: whatsapp messaging'
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4010
      key: travel-distribution-channel-management
      name: Travel Distribution & Channel Management
      url: /capabilities/travel-distribution-channel-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.9
      apps:
      - Beds24
      - Cloudbeds
      - Mews
      band: exemplar
      in_catalog: true
      kin_score: 66.6
      mcp:
        status: none
      name: Booking.com
      slug: booking-com
      sources:
      - https://beds24.com/channel-manager.html
      - https://www.cloudbeds.com/integrations/
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Accommodation
      - Booking
      - Hospitality
      - Travel
      tier: declared
      url: /providers/booking-com/
    - agent_band: agent-ready
      agent_readiness: 30.2
      apps:
      - Beds24
      - Cloudbeds
      - Mews
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        source: https://github.com/ExpediaGroup/expedia-travel-recommendations-mcp
        status: verified
      name: Expedia
      slug: expedia-group
      sources:
      - https://beds24.com/channel-manager.html
      - https://www.cloudbeds.com/integrations/
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Flights
      - Hotels
      - Lodging
      - Travel
      tier: declared
      url: /providers/expedia-group/
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - Beds24
      - Cloudbeds
      band: developing
      in_catalog: true
      kin_score: 44.1
      mcp:
        status: none
      name: Airbnb
      slug: airbnb
      sources:
      - https://beds24.com/channel-manager.html
      - https://www.cloudbeds.com/integrations/
      status: profiled
      tags:
      - Airbnb
      - Hospitality
      - Reservations
      - Travel
      tier: declared
      url: /providers/airbnb/
    - agent_band: agent-ready
      agent_readiness: 31.0
      apps:
      - Mews
      band: developing
      in_catalog: true
      kin_score: 42.2
      mcp:
        status: none
      name: Amadeus iHotelier
      slug: amadeus
      sources:
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Flights
      - Reservations
      - Travel
      - Travel Technology
      tier: declared
      url: /providers/amadeus/
    - agent_band: agent-aware
      agent_readiness: 25.5
      apps:
      - Beds24
      band: thin
      in_catalog: true
      kin_score: 29.4
      mcp:
        source: https://www.agoda.com/press/agoda-launches-open-source-api-agent-to-simplify-mcp-server-integrations/
        status: documented
      name: Agoda
      slug: agoda
      sources:
      - https://beds24.com/channel-manager.html
      status: profiled
      tags:
      - Booking
      - Company
      - Hotels
      - Travel
      tier: declared
      url: /providers/agoda/
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - Beds24
      band: thin
      in_catalog: true
      kin_score: 26.4
      mcp:
        status: unknown
      name: Hotelbeds
      slug: hotelbeds
      sources:
      - https://beds24.com/channel-manager.html
      status: profiled
      tags:
      - Accommodation
      - Bedbank
      - Hotels
      - Travel
      tier: declared
      url: /providers/hotelbeds/
    - agent_band: agent-aware
      agent_readiness: 18.8
      apps:
      - Beds24
      band: emerging
      in_catalog: true
      kin_score: 24.1
      mcp:
        status: unknown
      name: Trip.com
      slug: tripcom
      sources:
      - https://beds24.com/channel-manager.html
      status: profiled
      tags:
      - Company
      - Flights
      - Hotels
      - Travel
      tier: declared
      url: /providers/tripcom/
    - agent_band: human-only
      agent_readiness: 2.8
      apps:
      - Beds24
      band: emerging
      in_catalog: true
      kin_score: 15.2
      mcp:
        status: none
      name: Hostelworld
      slug: hostelworld
      sources:
      - https://beds24.com/channel-manager.html
      status: profiled
      tags:
      - Accommodation
      - Booking
      - Company
      - Travel
      tier: declared
      url: /providers/hostelworld/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Beds24
      band: minimal
      in_catalog: true
      kin_score: 5.1
      mcp:
        status: unchecked
      name: Vrbo
      slug: vrbo
      sources:
      - https://beds24.com/channel-manager.html
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/vrbo/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Hotelogix
      - QloApps
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://github.com/Qloapps/QloApps/tree/develop/modules
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: human-only
      agent_readiness: 1.1
      apps:
      - QloApps
      band: thin
      in_catalog: true
      kin_score: 26.4
      mcp:
        status: unknown
      name: Duitku
      slug: duitku
      sources:
      - https://github.com/Qloapps/QloApps/tree/develop/modules
      status: profiled
      tags:
      - Company
      - Fintech
      - Indonesia
      - Payments
      tier: observed
      url: /providers/duitku/
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Hotelogix
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: declared
      url: /providers/stripe/
    - agent_band: agent-native
      agent_readiness: 45.2
      apps:
      - Hotelogix
      band: strong
      in_catalog: true
      kin_score: 65.5
      mcp:
        source: https://mcp.doku.com/mcp
        status: verified
      name: DOKU
      slug: doku
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Fintech
      - Indonesia
      - Payment Gateway
      - Payments
      tier: declared
      url: /providers/doku/
    - agent_band: agent-aware
      agent_readiness: 5.3
      apps:
      - Hotelogix
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        status: none
      name: eWAY
      slug: eway
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Australia
      - Payment Gateway
      - Payment Processing
      - Payments
      tier: declared
      url: /providers/eway/
    - agent_band: agent-ready
      agent_readiness: 30.2
      apps:
      - Hotelogix
      band: thin
      in_catalog: true
      kin_score: 38.9
      mcp:
        source: https://github.com/payu-intrepos/payu-developer-mcp
        status: verified
      name: PayU
      slug: payu
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Financial Services
      - Fintech
      - Payment Processing
      - Payments
      tier: declared
      url: /providers/payu/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Hotelogix
      band: thin
      in_catalog: true
      kin_score: 35.5
      mcp:
        source: https://github.com/AuthorizeNet/authorize-net-mcp
        status: verified
      name: Authorize.Net
      slug: authorizenet
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Company
      - Credit Cards
      - Payment Gateway
      - Payments
      tier: declared
      url: /providers/authorizenet/
    - agent_band: agent-aware
      agent_readiness: 19.7
      apps:
      - Hotelogix
      band: thin
      in_catalog: true
      kin_score: 32.7
      mcp:
        status: unchecked
      name: Worldline
      slug: worldline
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Acquiring
      - Financial Services
      - Partners
      - Payments
      tier: declared
      url: /providers/worldline/
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - Hotelogix
      band: thin
      in_catalog: true
      kin_score: 32.5
      mcp:
        source: https://github.com/CyberSource/cybersource-developer-mcp
        status: verified
      name: CyberSource
      slug: cybersource
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Fraud Prevention
      - Payment Processing
      - Payments
      - Tokenization
      tier: declared
      url: /providers/cybersource/
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - Hotelogix
      band: thin
      in_catalog: true
      kin_score: 27.1
      mcp:
        status: unknown
      name: 2C2P
      slug: 2c2p
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Payment Gateway
      - Payments
      - Singapore
      - Southeast Asia
      tier: declared
      url: /providers/2c2p/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Hotelogix
      band: emerging
      in_catalog: true
      kin_score: 23.3
      mcp:
        status: unchecked
      name: CCAvenue
      slug: ccavenue
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Company
      - Fintech
      - India
      - Payments
      tier: declared
      url: /providers/ccavenue/
    - agent_band: agent-aware
      agent_readiness: 7.0
      apps:
      - Hotelogix
      band: emerging
      in_catalog: true
      kin_score: 15.8
      mcp:
        status: none
      name: First Data
      slug: first-data
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Financial Services
      - Merchant Services
      - Payments
      - Transaction Processing
      tier: declared
      url: /providers/first-data/
  - capability:
      attribution: Turbo EA
      id: BC-4010.50
      key: channel-manager-operations
      name: Channel Manager Operations
      url: /capabilities/channel-manager-operations/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 5.5
      apps:
      - Hotelogix
      - Mews
      band: thin
      in_catalog: true
      kin_score: 30.8
      mcp:
        status: none
      name: SiteMinder
      slug: siteminder
      sources:
      - https://www.hotelogix.com/marketplace/
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Booking Engine
      - Channel Manager
      - Hospitality
      - Hotel Distribution
      tier: declared
      url: /providers/siteminder/
    - agent_band: agent-ready
      agent_readiness: 47.4
      apps:
      - Hotelogix
      band: developing
      in_catalog: true
      kin_score: 40.3
      mcp:
        status: none
      name: SynXis
      slug: sabre
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Airlines
      - GDS
      - Hotels
      - Travel
      tier: declared
      url: /providers/sabre/
    - agent_band: agent-ready
      agent_readiness: 40.5
      apps:
      - Hotelogix
      band: thin
      in_catalog: true
      kin_score: 34.9
      mcp:
        status: unknown
      name: RateGain
      slug: rategain
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Company
      - Hospitality
      - Software-as-a-Service
      - TravelTech
      tier: declared
      url: /providers/rategain/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Hotelogix
      band: thin
      in_catalog: true
      kin_score: 27.4
      mcp:
        status: unknown
      name: HotelRunner
      slug: hotelrunner
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Booking Engine
      - Channel Manager
      - Hospitality
      - Hotels
      tier: declared
      url: /providers/hotelrunner/
    - agent_band: agent-aware
      agent_readiness: 21.4
      apps:
      - Hotelogix
      band: emerging
      in_catalog: true
      kin_score: 20.8
      mcp:
        status: unchecked
      name: STAAH
      slug: staah
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Channel Management
      - Company
      - Hospitality
      - Software-as-a-Service
      tier: declared
      url: /providers/staah/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Hotelogix
      band: emerging
      in_catalog: true
      kin_score: 15.2
      mcp:
        status: unchecked
      name: AxisRooms
      slug: axisrooms
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Booking Engine
      - Channel Manager
      - Hospitality
      - Software-as-a-Service
      tier: declared
      url: /providers/axisrooms/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 60.0
      apps:
      - Hotelogix
      band: exemplar
      in_catalog: true
      kin_score: 87.1
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: declared
      url: /providers/xero/
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Hotelogix
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks
      slug: quickbooks
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
    - agent_band: agent-ready
      agent_readiness: 58.7
      apps:
      - Hotelogix
      band: strong
      in_catalog: true
      kin_score: 58.3
      mcp:
        source: https://github.com/SAP/mdk-mcp-server
        status: verified
      name: SAP
      slug: sap
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Artificial Intelligence
      - BTP
      - Business Applications
      - SAP
      tier: declared
      url: /providers/sap/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Hotelogix
      band: developing
      in_catalog: true
      kin_score: 47.5
      mcp:
        source: https://www.zoho.com/mcp/
        status: documented
      name: Zoho Books
      slug: zoho-books
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Expenses
      - Invoicing
      tier: declared
      url: /providers/zoho-books/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Hotelogix
      band: thin
      in_catalog: true
      kin_score: 27.0
      mcp:
        status: unchecked
      name: Tally (TallyPrime)
      slug: tallyprime
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Accounting
      - Business Software
      - India
      - Small Business
      tier: declared
      url: /providers/tallyprime/
    - agent_band: agent-aware
      agent_readiness: 19.3
      apps:
      - Mews
      band: emerging
      in_catalog: true
      kin_score: 25.2
      mcp:
        status: unchecked
      name: 24SevenOffice
      slug: 24sevenoffice
      sources:
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Accounting
      - Business Management
      - Norway
      - Payroll
      tier: declared
      url: /providers/24sevenoffice/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Hotelogix
      band: emerging
      in_catalog: true
      kin_score: 11.4
      mcp:
        status: none
      name: NetSuite
      slug: netsuite
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Accounting
      - CRM
      - ERP
      - Finance
      tier: declared
      url: /providers/netsuite/
  - capability:
      attribution: Turbo EA
      id: BC-4030
      key: travel-revenue-yield-management
      name: Travel Revenue & Yield Management
      url: /capabilities/travel-revenue-yield-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Hotelogix
      - Mews
      band: emerging
      in_catalog: true
      kin_score: 19.3
      mcp:
        source: https://beonx.com
        status: documented
      name: BEONX
      slug: beonx
      sources:
      - https://www.hotelogix.com/marketplace/
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Hospitality
      - Revenue Management
      tier: declared
      url: /providers/beonx/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - apaleo
      band: emerging
      in_catalog: true
      kin_score: 24.8
      mcp:
        status: none
      name: happyhotel
      slug: happyhotel
      sources:
      - https://store.apaleo.com/
      status: profiled
      tags:
      - Hospitality
      - Hotels
      - Revenue Management
      - Software-as-a-Service
      tier: declared
      url: /providers/happyhotel/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Mews
      band: minimal
      in_catalog: true
      kin_score: 1.3
      mcp:
        status: unchecked
      name: profitize
      slug: profitize
      sources:
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/profitize/
    - agent_band: null
      agent_readiness: null
      apps:
      - apaleo
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: FLYR Hospitality
      slug: flyr
      sources:
      - https://store.apaleo.com/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Hotelogix
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Lighthouse
      slug: mylighthouse
      sources:
      - https://www.hotelogix.com/marketplace/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - apaleo
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: N2Pricing
      slug: n2pricing
      sources:
      - https://store.apaleo.com/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Cloudbeds
      - Hotelogix
      band: emerging
      in_catalog: true
      kin_score: 20.4
      mcp:
        status: unchecked
      name: TrustYou
      slug: trustyou
      sources:
      - https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Artificial Intelligence
      - Data Analytics
      - Guest Experience
      - Hospitality
      tier: declared
      url: /providers/trustyou/
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Mews
      band: thin
      in_catalog: true
      kin_score: 35.7
      mcp: &id001
        status: none
      name: Tripadvisor
      slug: tripadvisor
      sources:
      - https://www.mews.com/en/marketplace
      status: profiled
      tags: &id002
      - Attractions
      - Hospitality
      - Hotels
      - Restaurant
      tier: declared
      url: /providers/tripadvisor/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Hotelogix
      band: emerging
      in_catalog: true
      kin_score: 18.3
      mcp:
        status: unchecked
      name: ReviewPro
      slug: reviewpro
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Company
      - Hospitality
      - Reputation Management
      - Software-as-a-Service
      tier: declared
      url: /providers/reviewpro/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Cloudbeds
      band: minimal
      in_catalog: true
      kin_score: 9.4
      mcp:
        status: unchecked
      name: Reputize
      slug: reputize
      sources:
      - https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
      status: profiled
      tags:
      - Analytics
      - Company
      - Hotels
      - Reputation Management
      tier: declared
      url: /providers/reputize/
  - capability:
      attribution: Turbo EA
      id: BC-4010.40
      key: metasearch-distribution-management
      name: Metasearch Distribution Management
      url: /capabilities/metasearch-distribution-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - Beds24
      - QloApps
      band: exemplar
      in_catalog: true
      kin_score: 68.9
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Hotel Ads
      slug: google
      sources:
      - https://beds24.com/channel-manager.html
      - https://github.com/Qloapps/QloApps/tree/develop/modules
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: observed
      url: /providers/google/
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Beds24
      band: thin
      in_catalog: true
      kin_score: 35.7
      mcp: *id001
      name: Tripadvisor
      slug: tripadvisor
      sources:
      - https://beds24.com/channel-manager.html
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/tripadvisor/
    - agent_band: agent-aware
      agent_readiness: 8.5
      apps:
      - Beds24
      band: thin
      in_catalog: true
      kin_score: 27.6
      mcp:
        source: https://mcp.trivago.com/mcp
        status: verified
      name: trivago
      slug: trivago
      sources:
      - https://beds24.com/channel-manager.html
      status: profiled
      tags:
      - Accommodation
      - Company
      - Hotels
      - Travel
      tier: declared
      url: /providers/trivago/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.90
      key: AE-200.90
      name: Physical Access Control & Mobile Keys
      url: /capabilities/physical-access-control-mobile-keys/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Cloudbeds
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: 4SUITES
      slug: 4suites
      sources:
      - https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Cloudbeds
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: FLEXIPASS
      slug: flexipass
      sources:
      - https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Hotelogix
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Onity
      slug: onity
      sources:
      - https://www.hotelogix.com/marketplace/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30
      key: consumer-payment-options
      name: Consumer Payment Options
      url: /capabilities/consumer-payment-options/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.7
      apps:
      - Mews
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google Pay
      slug: google-pay
      sources:
      - https://www.mews.com/en/products/payments
      status: profiled
      tags:
      - Agentic Commerce
      - Checkout
      - Contactless Payments
      - Digital Wallet
      tier: declared
      url: /providers/google-pay/
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - Mews
      band: developing
      in_catalog: true
      kin_score: 43.0
      mcp:
        status: none
      name: Apple Pay
      slug: apple-pay
      sources:
      - https://www.mews.com/en/products/payments
      status: profiled
      tags:
      - Apple
      - Contactless Payments
      - Digital Wallet
      - E-Commerce
      tier: declared
      url: /providers/apple-pay/
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
      - Hotelogix
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - apaleo
      band: minimal
      in_catalog: true
      kin_score: 10.1
      mcp:
        status: unknown
      name: umnify
      slug: umnify
      sources:
      - https://store.apaleo.com/
      status: profiled
      tags:
      - German Market
      - Hospitality
      - Hotel Management
      - Software
      tier: declared
      url: /providers/umnify/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 3.2
      apps:
      - Cloudbeds
      band: emerging
      in_catalog: true
      kin_score: 24.5
      mcp:
        status: unchecked
      name: The Hotels Network
      slug: the-hotels-network
      sources:
      - https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
      status: profiled
      tags:
      - Artificial Intelligence
      - Direct Booking
      - Hospitality
      - HotelTech
      tier: declared
      url: /providers/the-hotels-network/
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - Cloudbeds
      band: emerging
      in_catalog: true
      kin_score: 22.8
      mcp:
        status: unchecked
      name: CartStack
      slug: cartstack
      sources:
      - https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
      status: profiled
      tags:
      - Cart Recovery
      - Company
      - E-Commerce
      - Software-as-a-Service
      tier: declared
      url: /providers/cartstack/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30.10
      key: AE-160.30.10
      name: Document Verification
      url: /capabilities/identity-verification/
      via_parent: Identity Verification
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Cloudbeds
      - Mews
      band: emerging
      in_catalog: true
      kin_score: 22.0
      mcp:
        status: unknown
      name: Chekin
      slug: chekin
      sources:
      - https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Check-in
      - Compliance
      - Hospitality
      - SDK
      tier: declared
      url: /providers/chekin/
  - capability:
      attribution: Turbo EA
      id: BC-4040
      key: guest-traveller-management
      name: Guest & Traveller Management
      url: /capabilities/guest-traveller-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.4
      apps:
      - apaleo
      band: developing
      in_catalog: true
      kin_score: 43.3
      mcp:
        status: unknown
      name: LIKE MAGIC
      slug: like-magic
      sources:
      - https://store.apaleo.com/
      status: profiled
      tags:
      - Company
      - Guest Experience
      - Hospitality
      - Technology
      tier: declared
      url: /providers/like-magic/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Mews
      band: emerging
      in_catalog: true
      kin_score: 13.6
      mcp:
        status: none
      name: Alliants
      slug: alliants
      sources:
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Company
      - DigitalKeys
      - Hospitality
      - Software-as-a-Service
      tier: declared
      url: /providers/alliants/
  - capability:
      attribution: Turbo EA
      id: BC-2320
      key: point-of-sale-operations-management
      name: Point of Sale Operations Management
      url: /capabilities/point-of-sale-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.1
      apps:
      - Cloudbeds
      band: exemplar
      in_catalog: true
      kin_score: 84.5
      mcp:
        status: none
      name: Lightspeed
      slug: lightspeed
      sources:
      - https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
      status: profiled
      tags:
      - Commerce
      - Point-of-Sale
      - Restaurant
      - Retail
      tier: declared
      url: /providers/lightspeed/
    - agent_band: null
      agent_readiness: null
      apps:
      - Cloudbeds
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Poster POS
      slug: poster
      sources:
      - https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4020
      key: reservation-booking-management
      name: Reservation & Booking Management
      url: /capabilities/reservation-booking-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Beds24
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://beds24.com/channel-manager.html
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: declared
      url: /providers/google-calendar/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Mews
      band: minimal
      in_catalog: true
      kin_score: 5.9
      mcp:
        status: unknown
      name: Spalopia
      slug: spalopia
      sources:
      - https://www.mews.com/en/marketplace
      status: profiled
      tags:
      - Booking
      - Company
      - Spa
      - Wellness
      tier: declared
      url: /providers/spalopia/
  - capability:
      attribution: Turbo EA
      id: BC-4060.10.30
      key: BC-4060.10.30
      name: Room Assignment & Upgrade
      url: /capabilities/front-office-operations/
      via_parent: Front Office Operations
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.2
      apps:
      - Cloudbeds
      band: developing
      in_catalog: true
      kin_score: 42.1
      mcp:
        status: unchecked
      name: UpsellGuru
      slug: upsellguru
      sources:
      - https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
      status: profiled
      tags:
      - Company
      - Hospitality
      - Revenue
      - Software-as-a-Service
      tier: declared
      url: /providers/upsellguru/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - apaleo
      band: emerging
      in_catalog: true
      kin_score: 12.5
      mcp:
        status: unchecked
      name: Sponteous
      slug: sponteous
      sources:
      - https://store.apaleo.com/
      status: profiled
      tags:
      - Company
      - Hospitality
      - Software-as-a-Service
      - Upselling
      tier: declared
      url: /providers/sponteous/
  - capability:
      attribution: Turbo EA
      id: BC-4010.10
      key: direct-channel-distribution-management
      name: Direct Channel Distribution Management
      url: /capabilities/direct-channel-distribution-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.9
      apps:
      - apaleo
      band: minimal
      in_catalog: true
      kin_score: 4.6
      mcp:
        status: unchecked
      name: GauVendi
      slug: gauvendi
      sources:
      - https://store.apaleo.com/
      status: profiled
      tags:
      - Booking
      - Distribution
      - Revenue Optimization
      tier: declared
      url: /providers/gauvendi/
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
      - Hotelogix
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30
      key: ground-transport
      name: Ground Transport
      url: /capabilities/ground-transport/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Cloudbeds
      band: emerging
      in_catalog: true
      kin_score: 11.4
      mcp:
        status: unchecked
      name: Welcome PickUps
      slug: welcome-pickups
      sources:
      - https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
      status: profiled
      tags:
      - Booking
      - Tours
      - Transfers
      - Travel
      tier: declared
      url: /providers/welcome-pickups/
  - capability:
      attribution: Turbo EA
      id: BC-4060.20
      key: housekeeping-operations
      name: Housekeeping Operations
      url: /capabilities/housekeeping-operations/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Cloudbeds
      band: minimal
      in_catalog: true
      kin_score: 7.1
      mcp:
        status: unknown
      name: Flexkeeping
      slug: flexkeeping
      sources:
      - https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
      status: profiled
      tags:
      - Company
      - Hospitality
      - Hotel Operations
      - Hotels
      tier: declared
      url: /providers/flexkeeping/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.30
      key: AE-160.30
      name: Identity Verification
      url: /capabilities/identity-verification/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.3
      apps:
      - Cloudbeds
      band: developing
      in_catalog: true
      kin_score: 42.0
      mcp:
        source: https://docs.autohost.ai/docs/remote-mcp-server
        status: verified
      name: Autohost
      slug: autohost
      sources:
      - https://cloudbeds.com/wp-content/uploads/2022/12/Integrations-to-enhance-the-guest-journey.pdf
      status: profiled
      tags:
      - Background Checks
      - Company
      - Fraud Prevention
      - Identity Verification
      tier: declared
      url: /providers/autohost/
  - capability:
      attribution: Turbo EA
      id: BC-420.40
      key: loyalty-retention-management
      name: Loyalty & Retention Management
      url: /capabilities/loyalty-retention-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.1
      apps:
      - Hotelogix
      band: emerging
      in_catalog: true
      kin_score: 23.5
      mcp:
        source: https://docs.capillarytech.com/docs/mcp
        status: verified
      name: Capillary Technologies
      slug: capillary-technologies
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - Enterprise
      - Loyalty
      - Marketing
      - Software-as-a-Service
      tier: declared
      url: /providers/capillary-technologies/
  - capability:
      attribution: API Evangelist extension
      id: AE-100.70.20
      key: AE-100.70.20
      name: Voice Agents
      url: /capabilities/vertical-agents/
      via_parent: Vertical Agents
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - apaleo
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: inCallio
      slug: incallio
      sources:
      - https://store.apaleo.com/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Hotelogix
      band: emerging
      in_catalog: true
      kin_score: 24.9
      mcp:
        status: none
      name: Gupshup
      slug: gupshup
      sources:
      - https://www.hotelogix.com/marketplace/
      status: profiled
      tags:
      - CPaaS
      - Conversational AI
      - Messaging
      - WhatsApp
      tier: declared
      url: /providers/gupshup/
  layer: domain
summary:
  coverage_pct: 88.9
  declared_only: 69
  distinct_providers: 72
  in_catalog: 64
  mcp:
    documented: 3
    none: 17
    unchecked: 25
    verified: 16
  mcp_verified: 16
  mean_kin_score: 34.6
  observed: 3
  queued: 8
  reference_apps: 6
title: 'Hotel Property Management: application blueprint'
---
