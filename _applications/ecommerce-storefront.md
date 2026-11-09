---
access: understanding
agent_layer: []
apps:
- anchor: saleor
  counts:
    declared: 0
    observed: 11
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/saleor/saleor/main/pyproject.toml
  - route: source code
    url: https://github.com/saleor/apps/tree/main/apps
  - route: source code
    url: https://github.com/saleor/saleor/tree/main/saleor/plugins
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2650.40
      key: product-catalogue-publication
      name: Product Catalogue Publication
      url: /capabilities/product-catalogue-publication/
      via_parent: null
    credit: null
    layer: domain
    name: Algolia
    provider: algolia
    says: ships the Algolia SDK or integration code
    source: https://raw.githubusercontent.com/saleor/apps/main/apps/search/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/saleor/saleor/main/pyproject.toml
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
    name: Avalara (AvaTax)
    provider: avalara
    says: ships the Avalara (AvaTax) SDK or integration code
    source: https://github.com/saleor/saleor/tree/main/saleor/plugins
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: ships the Azure Blob Storage SDK or integration code
    source: https://raw.githubusercontent.com/saleor/saleor/main/pyproject.toml
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
    name: Google Cloud Pub/Sub
    provider: google-cloud-pubsub
    says: ships the Google Cloud Pub/Sub SDK or integration code
    source: https://raw.githubusercontent.com/saleor/saleor/main/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://raw.githubusercontent.com/saleor/saleor/main/pyproject.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Klaviyo
    provider: klaviyo
    says: ships the Klaviyo SDK or integration code
    source: https://github.com/saleor/apps/tree/main/apps/klaviyo
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    credit: null
    layer: domain
    name: NP Atobarai (Net Protections)
    provider: np-atobarai
    says: ships the NP Atobarai (Net Protections) SDK or integration code
    source: https://github.com/saleor/apps/tree/main/apps/np-atobarai
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://raw.githubusercontent.com/saleor/apps/main/apps/segment/package.json
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
    source: https://raw.githubusercontent.com/saleor/saleor/main/pyproject.toml
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
    source: https://raw.githubusercontent.com/saleor/saleor/main/pyproject.toml
    tier: observed
  kind: open-source-saas
  name: Saleor
  page: /applications/ecommerce-storefront/saleor/
  slug: saleor
  url: https://github.com/saleor/saleor
- anchor: medusa
  counts:
    declared: 11
    observed: 4
  evidence:
  - route: integrations page
    url: https://docs.medusajs.com/resources/integrations
  - route: source code
    url: https://github.com/medusajs/medusa/tree/develop/packages/modules/providers
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/medusajs/medusa/tree/develop/packages/modules/providers/file-s3
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: PostHog
    provider: posthog
    says: ships the PostHog SDK or integration code
    source: https://github.com/medusajs/medusa/tree/develop/packages/modules/providers/analytics-posthog
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: SendGrid
    provider: sendgrid
    says: ships the SendGrid SDK or integration code
    source: https://github.com/medusajs/medusa/tree/develop/packages/modules/providers/notification-sendgrid
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
    source: https://github.com/medusajs/medusa/tree/develop/packages/modules/providers/payment-stripe
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2650.40
      key: product-catalogue-publication
      name: Product Catalogue Publication
      url: /capabilities/product-catalogue-publication/
      via_parent: null
    credit: null
    layer: domain
    name: Algolia
    provider: algolia
    says: lists Algolia as an integration
    source: https://docs.medusajs.com/resources/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    credit: null
    layer: domain
    name: Avalara (AvaTax)
    provider: avalara
    says: lists Avalara (AvaTax) as an integration
    source: https://docs.medusajs.com/resources/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2300
      key: merchandising-management
      name: Merchandising Management
      url: /capabilities/merchandising-management/
      via_parent: null
    credit: null
    layer: domain
    name: Contentful
    provider: contentful
    says: lists Contentful as an integration
    source: https://docs.medusajs.com/resources/integrations
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
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://docs.medusajs.com/resources/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2650.40
      key: product-catalogue-publication
      name: Product Catalogue Publication
      url: /capabilities/product-catalogue-publication/
      via_parent: null
    credit: null
    layer: domain
    name: Meilisearch
    provider: meilisearch
    says: lists Meilisearch as an integration
    source: https://docs.medusajs.com/resources/integrations
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
    source: https://docs.medusajs.com/resources/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Resend
    provider: resend
    says: lists Resend as an integration
    source: https://docs.medusajs.com/resources/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2300
      key: merchandising-management
      name: Merchandising Management
      url: /capabilities/merchandising-management/
      via_parent: null
    credit: null
    layer: domain
    name: Sanity
    provider: sanity
    says: lists Sanity as an integration
    source: https://docs.medusajs.com/resources/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Segment
    provider: segment
    says: lists Segment as an integration
    source: https://docs.medusajs.com/resources/integrations
    tier: declared
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
    says: lists Sentry as an integration
    source: https://docs.medusajs.com/resources/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-520.40
      key: order-fulfilment-management
      name: Order Fulfilment Management
      url: /capabilities/order-fulfilment-management/
      via_parent: null
    credit: null
    layer: domain
    name: ShipStation
    provider: shipstation
    says: lists ShipStation as an integration
    source: https://docs.medusajs.com/resources/integrations
    tier: declared
  kind: self-hosted
  name: Medusa
  page: /applications/ecommerce-storefront/medusa/
  slug: medusa
  url: https://github.com/medusajs/medusa
- anchor: vendure
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/vendure-ecommerce/vendure/master/packages/asset-server-plugin/package.json
  - route: dependency manifest
    url: https://unpkg.com/@vendure/payments-plugin@3.5.6/package.json
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/vendure-ecommerce/vendure/master/packages/asset-server-plugin/package.json
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
    name: Braintree
    provider: braintree
    says: ships the Braintree SDK or integration code
    source: https://unpkg.com/@vendure/payments-plugin@3.5.6/package.json
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
    name: Mollie
    provider: mollie
    says: ships the Mollie SDK or integration code
    source: https://unpkg.com/@vendure/payments-plugin@3.5.6/package.json
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
    source: https://unpkg.com/@vendure/payments-plugin@3.5.6/package.json
    tier: observed
  kind: self-hosted
  name: Vendure
  page: /applications/ecommerce-storefront/vendure/
  slug: vendure
  url: https://github.com/vendure-ecommerce/vendure
- anchor: bagisto
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/bagisto/bagisto/master/composer.json
  - route: source code
    url: https://github.com/bagisto/bagisto/tree/master/packages/Webkul
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/bagisto/bagisto/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.40
      key: cross-border-payment-management
      name: Cross-Border Payment Management
      url: /capabilities/cross-border-payment-management/
      via_parent: null
    credit: null
    layer: common
    name: PayGlocal
    provider: payglocal
    says: ships the PayGlocal SDK or integration code
    source: https://github.com/bagisto/bagisto/tree/master/packages/Webkul/PayGlocal
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
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://raw.githubusercontent.com/bagisto/bagisto/master/composer.json
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
    name: PayU
    provider: payu
    says: ships the PayU SDK or integration code
    source: https://github.com/bagisto/bagisto/tree/master/packages/Webkul/PayU
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
    name: PhonePe
    provider: phonepe
    says: ships the PhonePe SDK or integration code
    source: https://github.com/bagisto/bagisto/tree/master/packages/Webkul/PhonePe
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Pusher
    provider: pusher
    says: ships the Pusher SDK or integration code
    source: https://raw.githubusercontent.com/bagisto/bagisto/master/composer.json
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
    name: Razorpay
    provider: razorpay
    says: ships the Razorpay SDK or integration code
    source: https://raw.githubusercontent.com/bagisto/bagisto/master/composer.json
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
    source: https://raw.githubusercontent.com/bagisto/bagisto/master/composer.json
    tier: observed
  kind: self-hosted
  name: Bagisto
  page: /applications/ecommerce-storefront/bagisto/
  slug: bagisto
  url: https://github.com/bagisto/bagisto
- anchor: sylius
  counts:
    declared: 4
    observed: 0
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/Sylius/Sylius/2.1/composer.json
  - route: integrations page
    url: https://sylius.com/plugins/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Adyen
    provider: adyen
    says: lists Adyen as an integration
    source: https://sylius.com/plugins/
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
    name: Mollie
    provider: mollie
    says: lists Mollie as an integration
    source: https://sylius.com/plugins/
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
    source: https://sylius.com/plugins/
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
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://sylius.com/plugins/
    tier: declared
  kind: self-hosted
  name: Sylius
  page: /applications/ecommerce-storefront/sylius/
  slug: sylius
  url: https://github.com/Sylius/Sylius
- anchor: woocommerce
  counts:
    declared: 3
    observed: 0
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/woocommerce/woocommerce/trunk/plugins/woocommerce/composer.json
  - route: dependency manifest
    url: https://raw.githubusercontent.com/woocommerce/woocommerce/trunk/plugins/woocommerce/package.json
  - route: integrations page
    url: https://woocommerce.com/payments/
  - route: integrations page
    url: https://woocommerce.com/product-category/woocommerce-extensions/payment-gateways/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Afterpay
    provider: afterpay
    says: lists Afterpay as an integration
    source: https://woocommerce.com/payments/
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
    source: https://woocommerce.com/payments/
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
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://woocommerce.com/payments/
    tier: declared
  kind: self-hosted
  name: WooCommerce
  page: /applications/ecommerce-storefront/woocommerce/
  slug: woocommerce
  url: https://github.com/woocommerce/woocommerce
- anchor: shopify
  counts:
    declared: 9
    observed: 0
  evidence:
  - route: integrations page
    url: https://help.shopify.com/en/manual/payments/third-party-payment-providers
  - route: integrations page
    url: https://www.shopify.com/payments
  - route: integrations page
    url: https://www.shopify.com/shipping
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon Pay
    provider: amazon-pay
    says: lists Amazon Pay as an integration
    source: https://help.shopify.com/en/manual/payments/third-party-payment-providers
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    credit: null
    layer: common
    name: Apple Pay
    provider: apple-pay
    says: lists Apple Pay as an integration
    source: https://help.shopify.com/en/manual/payments/third-party-payment-providers
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: Canada Post
    provider: canada-post
    says: lists Canada Post as an integration
    source: https://www.shopify.com/shipping
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: DHL
    provider: dhl
    says: lists DHL as an integration
    source: https://www.shopify.com/shipping
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: FedEx
    provider: fedex
    says: lists FedEx as an integration
    source: https://www.shopify.com/shipping
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Pay
    provider: google-pay
    says: lists Google Pay as an integration
    source: https://help.shopify.com/en/manual/payments/third-party-payment-providers
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
    source: https://help.shopify.com/en/manual/payments/third-party-payment-providers
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: UPS
    provider: ups
    says: lists UPS as an integration
    source: https://www.shopify.com/shipping
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: USPS
    provider: usps
    says: lists USPS as an integration
    source: https://www.shopify.com/shipping
    tier: declared
  kind: commercial
  name: Shopify
  page: /applications/ecommerce-storefront/shopify/
  slug: shopify
  url: https://www.shopify.com
- anchor: shop-(shopify-consumer-app,-android)
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.shopify.arrive/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Bugsnag
    provider: bugsnag
    says: ships the Bugsnag SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.shopify.arrive/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Firebase (Analytics)
    provider: firebase
    says: ships the Google Firebase (Analytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.shopify.arrive/latest/
    tier: observed
  kind: commercial
  name: Shop (Shopify consumer app, Android)
  page: /applications/ecommerce-storefront/shop-shopify-consumer-app-android/
  slug: shop-shopify-consumer-app-android
  url: https://play.google.com/store/apps/details?id=com.shopify.arrive
- anchor: etsy-(android)
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.etsy.android/latest/
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
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.etsy.android/latest/
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
    name: Branch (branch.io)
    provider: branch-io
    says: ships the Branch (branch.io) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.etsy.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook (Meta) SDK
    provider: facebook
    says: ships the Facebook (Meta) SDK SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.etsy.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: FullStory
    provider: fullstory
    says: ships the FullStory SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.etsy.android/latest/
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
    name: Google AdMob
    provider: google-admob
    says: ships the Google AdMob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.etsy.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Firebase (Analytics)
    provider: firebase
    says: ships the Google Firebase (Analytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.etsy.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3770.50
      key: audience-insights-research-management
      name: Audience Insights & Research Management
      url: /capabilities/audience-insights-research-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Qualtrics
    provider: qualtrics
    says: ships the Qualtrics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.etsy.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.etsy.android/latest/
    tier: observed
  kind: commercial
  name: Etsy (Android)
  page: /applications/ecommerce-storefront/etsy-android/
  slug: etsy-android
  url: https://play.google.com/store/apps/details?id=com.etsy.android
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: ecommerce-storefront
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Shopping
  store: google-play
  url: https://play.google.com/store/apps/category/SHOPPING
- category: Shopping
  store: apple-app-store
  url: https://apps.apple.com/us/charts/iphone/shopping-apps/6024
name: E-commerce Storefront
needs:
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: common
  why: product analytics
- capability:
    attribution: Turbo EA
    id: BC-3770.50
    key: audience-insights-research-management
    name: Audience Insights & Research Management
    url: /capabilities/audience-insights-research-management/
    via_parent: null
  fit: exact
  layer: common
  why: in-app surveys (Etsy/Qualtrics)
- capability:
    attribution: Turbo EA
    id: BC-3740.30
    key: content-delivery-network-operations
    name: Content Delivery Network Operations
    url: /capabilities/content-delivery-network-operations/
    via_parent: null
  fit: exact
  layer: common
  why: storefront CDN - no reference app evidence found
- capability:
    attribution: Turbo EA
    id: BC-1340.40
    key: cross-border-payment-management
    name: Cross-Border Payment Management
    url: /capabilities/cross-border-payment-management/
    via_parent: null
  fit: exact
  layer: common
  why: cross-border gateway (Bagisto PayGlocal)
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: common
  why: CDP, transactional messaging, realtime events
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: email/SMS marketing, attribution, ads
- capability:
    attribution: Turbo EA
    id: BC-1400.30
    key: fraud-detection-investigation-management
    name: Fraud Detection & Investigation Management
    url: /capabilities/fraud-detection-investigation-management/
    via_parent: null
  fit: exact
  layer: domain
  why: checkout fraud screening - no reference app evidence found
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: social login (Facebook Login in Etsy)
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  fit: exact
  layer: domain
  why: sales tax / VAT calculation at checkout
- capability:
    attribution: Turbo EA
    id: BC-530
    key: inventory-management
    name: Inventory Management
    url: /capabilities/inventory-management/
    via_parent: null
  fit: exact
  layer: domain
  why: stock levels
- capability:
    attribution: Turbo EA
    id: BC-4050.10
    key: loyalty-programme-design
    name: Loyalty Programme Design
    url: /capabilities/loyalty-programme-design/
    via_parent: null
  fit: exact
  layer: domain
  why: loyalty/rewards - no reference app evidence found
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  fit: exact
  layer: common
  why: product image / file storage
- capability:
    attribution: Turbo EA
    id: BC-2300
    key: merchandising-management
    name: Merchandising Management
    url: /capabilities/merchandising-management/
    via_parent: null
  fit: exact
  layer: domain
  why: headless CMS for storefront content
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring + event transport
- capability:
    attribution: Turbo EA
    id: BC-2330
    key: omnichannel-order-fulfilment-management
    name: Omnichannel Order & Fulfilment Management
    url: /capabilities/omnichannel-order-fulfilment-management/
    via_parent: null
  fit: exact
  layer: domain
  why: order routing across channels
- capability:
    attribution: Turbo EA
    id: BC-520.40
    key: order-fulfilment-management
    name: Order Fulfilment Management
    url: /capabilities/order-fulfilment-management/
    via_parent: null
  fit: exact
  layer: domain
  why: fulfilment/shipping-ops platforms (ShipStation)
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: card/wallet checkout - every reference app ships at least one gateway
- capability:
    attribution: Turbo EA
    id: BC-1310.10
    key: product-catalogue-management
    name: Product Catalogue Management
    url: /capabilities/product-catalogue-management/
    via_parent: null
  fit: exact
  layer: domain
  why: the catalog itself - the storefront platforms are the providers here
- capability:
    attribution: Turbo EA
    id: BC-2650.40
    key: product-catalogue-publication
    name: Product Catalogue Publication
    url: /capabilities/product-catalogue-publication/
    via_parent: null
  fit: exact
  layer: domain
  why: hosted product search
- capability:
    attribution: Turbo EA
    id: BC-2460.50
    key: returns-and-reverse-operations-management
    name: Returns and Reverse Operations Management
    url: /capabilities/returns-and-reverse-operations-management/
    via_parent: null
  fit: exact
  layer: domain
  why: returns/RMA (Bagisto RMA module)
- capability:
    attribution: Turbo EA
    id: BC-2510.20
    key: shipment-tracking-management
    name: Shipment Tracking Management
    url: /capabilities/shipment-tracking-management/
    via_parent: null
  fit: exact
  layer: domain
  why: carrier rates, labels, tracking
- capability:
    attribution: Turbo EA
    id: BC-2320.20
    key: tender-and-payment-acceptance-management
    name: Tender and Payment Acceptance Management
    url: /capabilities/tender-and-payment-acceptance-management/
    via_parent: null
  fit: exact
  layer: domain
  why: wallets and BNPL tenders at checkout
- capability:
    attribution: API Evangelist extension
    id: AE-100.10.10
    key: AE-100.10.10
    name: MCP Server Hosting
    url: /capabilities/agent-tool-exposure/
    via_parent: Agent Tool Exposure
  fit: exact
  layer: agent
  why: Vendure ships packages/mcp-plugin + mcp-sdk in its monorepo (https://github.com/vendure-ecommerce/vendure/tree/master/packages); no other reference app ships an MCP server in-repo. Not mapped to a BC slug.
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.9
      apps:
      - Shopify
      band: exemplar
      in_catalog: true
      kin_score: 69.4
      mcp:
        status: none
      name: FedEx
      slug: fedex
      sources:
      - https://www.shopify.com/shipping
      status: profiled
      tags:
      - Address Validation
      - Freight
      - Logistics
      - Pickup
      tier: declared
      url: /providers/fedex/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Shopify
      band: thin
      in_catalog: true
      kin_score: 33.2
      mcp:
        status: none
      name: USPS
      slug: usps
      sources:
      - https://www.shopify.com/shipping
      status: profiled
      tags:
      - Government
      - Logistics
      - Postal Service
      - Shipping
      tier: declared
      url: /providers/usps/
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - Shopify
      band: thin
      in_catalog: true
      kin_score: 29.0
      mcp:
        source: https://github.com/UPS-API/ups-mcp
        status: verified
      name: UPS
      slug: ups
      sources:
      - https://www.shopify.com/shipping
      status: profiled
      tags:
      - Fortune 500
      - Logistics
      - Shipping
      - Supply Chain
      tier: declared
      url: /providers/ups/
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - Shopify
      band: emerging
      in_catalog: true
      kin_score: 26.1
      mcp:
        status: none
      name: DHL
      slug: dhl
      sources:
      - https://www.shopify.com/shipping
      status: profiled
      tags:
      - E-Commerce
      - Freight
      - Logistics
      - Shipping
      tier: declared
      url: /providers/dhl/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Shopify
      band: emerging
      in_catalog: true
      kin_score: 18.0
      mcp:
        status: none
      name: Canada Post
      slug: canada-post
      sources:
      - https://www.shopify.com/shipping
      status: profiled
      tags:
      - Address Validation
      - E-Commerce
      - Labels
      - Logistics
      tier: declared
      url: /providers/canada-post/
  - capability:
      attribution: Turbo EA
      id: BC-2650.40
      key: product-catalogue-publication
      name: Product Catalogue Publication
      url: /capabilities/product-catalogue-publication/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.9
      apps:
      - Medusa
      - Saleor
      band: exemplar
      in_catalog: true
      kin_score: 79.9
      mcp:
        status: none
      name: Algolia
      slug: algolia
      sources:
      - https://docs.medusajs.com/resources/integrations
      - https://raw.githubusercontent.com/saleor/apps/main/apps/search/package.json
      status: profiled
      tags:
      - Discovery
      - Personalization
      - Recommendations
      - Search
      tier: observed
      url: /providers/algolia/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Medusa
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        source: https://github.com/meilisearch/meilisearch-mcp
        status: verified
      name: Meilisearch
      slug: meilisearch
      sources:
      - https://docs.medusajs.com/resources/integrations
      status: profiled
      tags:
      - AI Search
      - Full-Text Search
      - Hybrid Search
      - Open Source
      tier: declared
      url: /providers/meilisearch/
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.6
      apps:
      - Medusa
      - Saleor
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/avadev/mcp
        status: verified
      name: Avalara (AvaTax)
      slug: avalara
      sources:
      - https://docs.medusajs.com/resources/integrations
      - https://github.com/saleor/saleor/tree/main/saleor/plugins
      status: profiled
      tags:
      - Accounting
      - Avalara
      - Tax
      tier: observed
      url: /providers/avalara/
  - capability:
      attribution: Turbo EA
      id: BC-2300
      key: merchandising-management
      name: Merchandising Management
      url: /capabilities/merchandising-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Medusa
      band: strong
      in_catalog: true
      kin_score: 56.9
      mcp:
        source: https://www.sanity.io/docs/compute-and-ai/mcp-server
        status: verified
      name: Sanity
      slug: sanity
      sources:
      - https://docs.medusajs.com/resources/integrations
      status: profiled
      tags:
      - Content Management
      - GROQ
      - Headless CMS
      - Real-Time
      tier: declared
      url: /providers/sanity/
    - agent_band: agent-ready
      agent_readiness: 56.5
      apps:
      - Medusa
      band: developing
      in_catalog: true
      kin_score: 44.3
      mcp:
        source: https://github.com/contentful/contentful-mcp-server
        status: verified
      name: Contentful
      slug: contentful
      sources:
      - https://docs.medusajs.com/resources/integrations
      status: profiled
      tags:
      - CMS
      - Content
      - Content Management
      - Headless CMS
      tier: declared
      url: /providers/contentful/
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Saleor
      band: minimal
      in_catalog: true
      kin_score: 6.4
      mcp:
        status: unknown
      name: NP Atobarai (Net Protections)
      slug: np-atobarai
      sources:
      - https://github.com/saleor/apps/tree/main/apps/np-atobarai
      status: profiled
      tags:
      - Fintech
      - Japan
      - Payments
      - Post-pay
      tier: observed
      url: /providers/np-atobarai/
    - agent_band: agent-aware
      agent_readiness: 13.0
      apps:
      - WooCommerce
      band: minimal
      in_catalog: true
      kin_score: 9.3
      mcp:
        status: none
      name: Afterpay
      slug: afterpay
      sources:
      - https://woocommerce.com/payments/
      status: profiled
      tags:
      - Buy Now Pay Later
      - Consumer
      - Fintech
      - Payments
      tier: declared
      url: /providers/afterpay/
  - capability:
      attribution: Turbo EA
      id: BC-520.40
      key: order-fulfilment-management
      name: Order Fulfilment Management
      url: /capabilities/order-fulfilment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Medusa
      band: strong
      in_catalog: true
      kin_score: 56.7
      mcp:
        status: none
      name: ShipStation
      slug: shipstation
      sources:
      - https://docs.medusajs.com/resources/integrations
      status: profiled
      tags:
      - E-Commerce
      - Labels
      - Logistics
      - ShipStation
      tier: declared
      url: /providers/shipstation/
  layer: domain
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
      agent_readiness: 58.5
      apps:
      - Bagisto
      - Medusa
      - Saleor
      - Sylius
      - Vendure
      - WooCommerce
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/medusajs/medusa/tree/develop/packages/modules/providers/payment-stripe
      - https://raw.githubusercontent.com/bagisto/bagisto/master/composer.json
      - https://raw.githubusercontent.com/saleor/saleor/main/pyproject.toml
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - Bagisto
      - Medusa
      - Shopify
      - Sylius
      - WooCommerce
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://docs.medusajs.com/resources/integrations
      - https://help.shopify.com/en/manual/payments/third-party-payment-providers
      - https://raw.githubusercontent.com/bagisto/bagisto/master/composer.json
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-native
      agent_readiness: 73.2
      apps:
      - Sylius
      - Vendure
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://docs.mollie.com/docs/mcp-server
        status: verified
      name: Mollie
      slug: mollie
      sources:
      - https://sylius.com/plugins/
      - https://unpkg.com/@vendure/payments-plugin@3.5.6/package.json
      status: profiled
      tags:
      - Company
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/mollie/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Bagisto
      band: developing
      in_catalog: true
      kin_score: 52.4
      mcp:
        source: https://github.com/razorpay/razorpay-mcp-server
        status: verified
      name: Razorpay
      slug: razorpay
      sources:
      - https://raw.githubusercontent.com/bagisto/bagisto/master/composer.json
      status: profiled
      tags:
      - Fintech
      - India
      - Payment Gateway
      - Payments
      tier: observed
      url: /providers/razorpay/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Vendure
      band: developing
      in_catalog: true
      kin_score: 46.2
      mcp:
        status: none
      name: Braintree
      slug: braintree
      sources:
      - https://unpkg.com/@vendure/payments-plugin@3.5.6/package.json
      status: profiled
      tags:
      - Mobile
      - Payments
      - Subscription
      - Transaction
      tier: observed
      url: /providers/braintree/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Bagisto
      band: developing
      in_catalog: true
      kin_score: 40.0
      mcp:
        source: https://github.com/payu-intrepos/payu-developer-mcp
        status: verified
      name: PayU
      slug: payu
      sources:
      - https://github.com/bagisto/bagisto/tree/master/packages/Webkul/PayU
      status: profiled
      tags:
      - Financial Services
      - Fintech
      - Payment Processing
      - Payments
      tier: observed
      url: /providers/payu/
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Bagisto
      band: thin
      in_catalog: true
      kin_score: 27.7
      mcp:
        source: https://github.com/PhonePe/phonepe-pg-docs-mcp
        status: verified
      name: PhonePe
      slug: phonepe
      sources:
      - https://github.com/bagisto/bagisto/tree/master/packages/Webkul/PhonePe
      status: profiled
      tags:
      - Payment Gateway
      - Payments
      - QR
      - UPI
      tier: observed
      url: /providers/phonepe/
    - agent_band: agent-native
      agent_readiness: 43.7
      apps:
      - Sylius
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/Adyen/adyen-mcp
        status: verified
      name: Adyen
      slug: adyen
      sources:
      - https://sylius.com/plugins/
      status: profiled
      tags:
      - Agentic Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: declared
      url: /providers/adyen/
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Bagisto
      - Medusa
      - Saleor
      - Vendure
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/medusajs/medusa/tree/develop/packages/modules/providers/file-s3
      - https://raw.githubusercontent.com/bagisto/bagisto/master/composer.json
      - https://raw.githubusercontent.com/saleor/saleor/main/pyproject.toml
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 45.3
      apps:
      - Saleor
      band: exemplar
      in_catalog: true
      kin_score: 71.7
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://raw.githubusercontent.com/saleor/saleor/main/pyproject.toml
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-ready
      agent_readiness: 40.9
      apps:
      - Saleor
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://raw.githubusercontent.com/saleor/saleor/main/pyproject.toml
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Medusa
      - Saleor
      band: developing
      in_catalog: true
      kin_score: 43.8
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://docs.medusajs.com/resources/integrations
      - https://raw.githubusercontent.com/saleor/apps/main/apps/segment/package.json
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - Medusa
      band: exemplar
      in_catalog: true
      kin_score: 87.3
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://github.com/medusajs/medusa/tree/develop/packages/modules/providers/notification-sendgrid
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Bagisto
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        status: none
      name: Pusher
      slug: pusher
      sources:
      - https://raw.githubusercontent.com/bagisto/bagisto/master/composer.json
      status: profiled
      tags:
      - Pub/Sub
      - Push Notifications
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/pusher/
    - agent_band: agent-ready
      agent_readiness: 49.4
      apps:
      - Medusa
      band: strong
      in_catalog: true
      kin_score: 58.9
      mcp:
        source: https://resend.com/docs/mcp-server
        status: verified
      name: Resend
      slug: resend
      sources:
      - https://docs.medusajs.com/resources/integrations
      status: profiled
      tags:
      - Developer Tools
      - Email
      - Marketing Email
      - Transactional Email
      tier: declared
      url: /providers/resend/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 54.9
      apps:
      - Saleor
      band: exemplar
      in_catalog: true
      kin_score: 77.6
      mcp:
        source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
        status: verified
      name: Klaviyo
      slug: klaviyo
      sources:
      - https://github.com/saleor/apps/tree/main/apps/klaviyo
      status: profiled
      tags:
      - Customer Data
      - Email
      - Marketing
      - SMS
      tier: observed
      url: /providers/klaviyo/
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - Etsy (Android)
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.etsy.android/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
    - agent_band: agent-ready
      agent_readiness: 34.0
      apps:
      - Etsy (Android)
      band: strong
      in_catalog: true
      kin_score: 61.5
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.etsy.android/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Etsy (Android)
      band: emerging
      in_catalog: true
      kin_score: 23.0
      mcp:
        status: none
      name: Branch (branch.io)
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.etsy.android/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - Medusa
      band: exemplar
      in_catalog: true
      kin_score: 78.3
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://docs.medusajs.com/resources/integrations
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
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
      - Etsy (Android)
      - Medusa
      - Saleor
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://docs.medusajs.com/resources/integrations
      - https://raw.githubusercontent.com/saleor/saleor/main/pyproject.toml
      - https://reports.exodus-privacy.eu.org/en/reports/com.etsy.android/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 53.1
      apps:
      - Shop (Shopify consumer app, Android)
      band: exemplar
      in_catalog: true
      kin_score: 78.5
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.shopify.arrive/latest/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - Saleor
      band: thin
      in_catalog: true
      kin_score: 38.7
      mcp:
        source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
        status: verified
      name: Google Cloud Pub/Sub
      slug: google-cloud-pubsub
      sources:
      - https://raw.githubusercontent.com/saleor/saleor/main/pyproject.toml
      status: profiled
      tags:
      - Event-Driven
      - Google Cloud
      - Messaging
      - Pub/Sub
      tier: observed
      url: /providers/google-cloud-pubsub/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Etsy (Android)
      - Shop (Shopify consumer app, Android)
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase (Analytics)
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.etsy.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.shopify.arrive/latest/
      status: profiled
      tags:
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-ready
      agent_readiness: 57.3
      apps:
      - Medusa
      band: strong
      in_catalog: true
      kin_score: 57.7
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://github.com/medusajs/medusa/tree/develop/packages/modules/providers/analytics-posthog
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Etsy (Android)
      band: thin
      in_catalog: true
      kin_score: 37.1
      mcp:
        source: https://developer.fullstory.com/mcp/introduction/
        status: documented
      name: FullStory
      slug: fullstory
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.etsy.android/latest/
      status: profiled
      tags:
      - Behavioral Analytics
      - Digital Experience
      - Product Analytics
      - Session Replay
      tier: observed
      url: /providers/fullstory/
  - capability:
      attribution: Turbo EA
      id: BC-2320.20
      key: tender-and-payment-acceptance-management
      name: Tender and Payment Acceptance Management
      url: /capabilities/tender-and-payment-acceptance-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - Shopify
      band: strong
      in_catalog: true
      kin_score: 66.2
      mcp:
        status: none
      name: Google Pay
      slug: google-pay
      sources:
      - https://help.shopify.com/en/manual/payments/third-party-payment-providers
      status: profiled
      tags:
      - Agentic Commerce
      - Checkout
      - Contactless Payments
      - Digital Wallet
      tier: declared
      url: /providers/google-pay/
    - agent_band: agent-ready
      agent_readiness: 31.1
      apps:
      - Shopify
      band: developing
      in_catalog: true
      kin_score: 43.6
      mcp:
        status: none
      name: Apple Pay
      slug: apple-pay
      sources:
      - https://help.shopify.com/en/manual/payments/third-party-payment-providers
      status: profiled
      tags:
      - Apple
      - Contactless Payments
      - Digital Wallet
      - E-Commerce
      tier: declared
      url: /providers/apple-pay/
    - agent_band: null
      agent_readiness: null
      apps:
      - Shopify
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Amazon Pay
      slug: amazon-pay
      sources:
      - https://help.shopify.com/en/manual/payments/third-party-payment-providers
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-3770.50
      key: audience-insights-research-management
      name: Audience Insights & Research Management
      url: /capabilities/audience-insights-research-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.0
      apps:
      - Etsy (Android)
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Qualtrics
      slug: qualtrics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.etsy.android/latest/
      status: profiled
      tags:
      - Customer Experience
      - Employee Experience
      - Experience Management
      - Surveys
      tier: observed
      url: /providers/qualtrics/
  - capability:
      attribution: Turbo EA
      id: BC-1340.40
      key: cross-border-payment-management
      name: Cross-Border Payment Management
      url: /capabilities/cross-border-payment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.0
      apps:
      - Bagisto
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: unknown
      name: PayGlocal
      slug: payglocal
      sources:
      - https://github.com/bagisto/bagisto/tree/master/packages/Webkul/PayGlocal
      status: profiled
      tags:
      - Company
      - Cross-Border
      - Fintech
      - Payments
      tier: observed
      url: /providers/payglocal/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Etsy (Android)
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: none
      name: Facebook (Meta) SDK
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.etsy.android/latest/
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
  layer: common
summary:
  coverage_pct: 97.8
  declared_only: 16
  distinct_providers: 45
  in_catalog: 44
  mcp:
    documented: 1
    none: 18
    unchecked: 1
    verified: 23
  mcp_verified: 23
  mean_kin_score: 52.8
  observed: 29
  queued: 1
  reference_apps: 9
title: 'E-commerce Storefront: application blueprint'
---
