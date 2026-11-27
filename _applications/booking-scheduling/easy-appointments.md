---
app: Easy!Appointments
app_slug: easy-appointments
app_url: https://github.com/alextselegidis/easyappointments
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
category:
  id: booking-scheduling
  name: Appointment Booking & Scheduling
  url: /applications/booking-scheduling/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/alextselegidis/easyappointments/main/composer.json
- route: documentation
  url: https://github.com/alextselegidis/easyappointments/tree/main/docs
- route: source code
  url: https://github.com/alextselegidis/easyappointments/tree/main/application/libraries
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
    agent_readiness: 44.1
    band: strong
    in_catalog: true
    kin_score: 64.6
    mcp: &id001
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id002
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: domain
  name: Google Calendar
  provider: google-calendar
  says: ships the Google Calendar SDK or integration code
  source: https://github.com/alextselegidis/easyappointments/tree/main/application/libraries
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/booking-scheduling/easy-appointments/
providers:
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id001
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id002
  url: /providers/google-calendar/
siblings:
- name: Acuity Scheduling
  rows: 38
  url: /applications/booking-scheduling/acuity-scheduling/
- name: Booksy Biz
  rows: 6
  url: /applications/booking-scheduling/booksy-biz/
- name: Cal.com
  rows: 71
  url: /applications/booking-scheduling/cal-com/
- name: Calendly
  rows: 54
  url: /applications/booking-scheduling/calendly/
- name: LibreBooking
  rows: 8
  url: /applications/booking-scheduling/librebooking/
- name: Rallly
  rows: 13
  url: /applications/booking-scheduling/rallly/
sitemap: true
title: 'Easy!Appointments: Appointment Booking & Scheduling reference app'
---
