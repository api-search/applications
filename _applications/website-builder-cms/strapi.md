---
app: Strapi
app_slug: strapi
app_url: https://github.com/strapi/strapi
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.30.10
  key: AE-170.30.10
  layer: domain
  name: Image Processing & Optimisation
  providers:
  - Cloudinary
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES
  - Mailgun
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
category:
  id: website-builder-cms
  name: Website Builder, CMS & Blogging
  url: /applications/website-builder-cms/
counts:
  declared: 0
  observed: 5
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.0
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id003
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.5
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id005
      source: https://cloudinary.com/documentation/cloudinary_llm_mcp
      status: verified
    slug: cloudinary
    status: profiled
    tags: &id006
    - Asset Management
    - Digital Asset Management
    - Image Processing
    - Image Transformation
    url: /providers/cloudinary/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id007
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id008
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.7
    band: exemplar
    in_catalog: true
    kin_score: 84.0
    mcp: &id009
      status: none
    slug: sendgrid
    status: profiled
    tags: &id010
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://github.com/strapi/strapi/tree/develop/packages/providers/email-sendgrid
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/website-builder-cms/strapi/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 38.0
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id003
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id004
  url: /providers/amazon-ses/
- agent_band: agent-ready
  agent_readiness: 53.5
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id005
  name: Cloudinary
  slug: cloudinary
  status: profiled
  tags: *id006
  url: /providers/cloudinary/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id007
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id008
  url: /providers/mailgun/
- agent_band: agent-ready
  agent_readiness: 40.7
  band: exemplar
  in_catalog: true
  kin_score: 84.0
  mcp: *id009
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id010
  url: /providers/sendgrid/
siblings:
- name: Directus
  rows: 12
  url: /applications/website-builder-cms/directus/
- name: Ghost
  rows: 76
  url: /applications/website-builder-cms/ghost/
- name: Payload
  rows: 9
  url: /applications/website-builder-cms/payload/
- name: Webflow
  rows: 17
  url: /applications/website-builder-cms/webflow/
- name: WordPress
  rows: 30
  url: /applications/website-builder-cms/wordpress/
sitemap: true
title: 'Strapi: Website Builder, CMS & Blogging reference app'
---
