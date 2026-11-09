---
app: Traefik Proxy
app_slug: traefik-proxy
app_url: https://github.com/traefik/traefik
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-600.50
  key: it-infrastructure-management
  layer: domain
  name: IT Infrastructure Management
  providers:
  - Amazon ECS
  - Apache ZooKeeper
  - Docker
  - etcd
  - HashiCorp Consul
  - Kubernetes
  - Nomad
  - Redis
  url: /capabilities/it-infrastructure-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.50.50
  key: BC-620.50.50
  layer: common
  name: Cryptography and Key Management
  providers:
  - Let's Encrypt
  - Tailscale
  url: /capabilities/security-architecture-management/
  via_parent: Security Architecture Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Datadog
  - InfluxDB
  - OpenTelemetry
  - Prometheus
  - StatsD
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: api-management-gateway
  name: API Management & Gateways
  url: /applications/api-management-gateway/
counts:
  declared: 0
  observed: 15
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/traefik/traefik/blob/master/go.mod
- route: source code
  url: https://github.com/traefik/traefik/tree/master/pkg/observability/metrics
- route: source code
  url: https://github.com/traefik/traefik/tree/master/pkg/provider
integrations:
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: strong
    in_catalog: true
    kin_score: 63.0
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-ecs
    status: profiled
    tags: &id002
    - Amazon
    - Amazon Web Services
    - Containers
    - Docker
    url: /providers/amazon-ecs/
  layer: domain
  name: Amazon ECS
  provider: amazon-ecs
  says: ships the Amazon ECS SDK or integration code
  source: https://github.com/traefik/traefik/tree/master/pkg/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.5
    band: thin
    in_catalog: true
    kin_score: 38.7
    mcp: &id003
      status: none
    slug: apache-zookeeper
    status: profiled
    tags: &id004
    - Configuration Management
    - Distributed Coordination
    - Leader Election
    - Service Discovery
    url: /providers/apache-zookeeper/
  layer: domain
  name: Apache ZooKeeper
  provider: apache-zookeeper
  says: ships the Apache ZooKeeper SDK or integration code
  source: https://github.com/traefik/traefik/tree/master/pkg/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 49.6
    band: exemplar
    in_catalog: true
    kin_score: 79.2
    mcp: &id005
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id006
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: common
  name: Datadog
  provider: datadog
  says: ships the Datadog SDK or integration code
  source: https://github.com/traefik/traefik/tree/master/pkg/observability/metrics
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: developing
    in_catalog: true
    kin_score: 52.0
    mcp: &id007
      source: https://github.com/docker/mcp-gateway
      status: verified
    slug: docker
    status: profiled
    tags: &id008
    - Cloud
    - Containers
    - DevOps
    - Developer Tools
    url: /providers/docker/
  layer: domain
  name: Docker
  provider: docker
  says: ships the Docker SDK or integration code
  source: https://github.com/traefik/traefik/tree/master/pkg/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: developing
    in_catalog: true
    kin_score: 48.5
    mcp: &id009
      status: none
    slug: etcd
    status: profiled
    tags: &id010
    - Cloud-Native
    - Consensus
    - Distributed Systems
    - Graduated
    url: /providers/etcd/
  layer: domain
  name: etcd
  provider: etcd
  says: ships the etcd SDK or integration code
  source: https://github.com/traefik/traefik/tree/master/pkg/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.6
    band: thin
    in_catalog: true
    kin_score: 35.7
    mcp: &id011
      source: https://github.com/hashicorp/consul-mcp-server
      status: verified
    slug: consul
    status: profiled
    tags: &id012
    - ACL
    - Configuration
    - Health Checks
    - Key-Value Store
    url: /providers/consul/
  layer: domain
  name: HashiCorp Consul
  provider: consul
  says: ships the HashiCorp Consul SDK or integration code
  source: https://github.com/traefik/traefik/tree/master/pkg/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.1
    band: strong
    in_catalog: true
    kin_score: 64.0
    mcp: &id013
      source: https://github.com/influxdata/influxdb3_mcp_server
      status: verified
    slug: influxdata
    status: profiled
    tags: &id014
    - Database
    - Monitoring
    - Observability
    - Time Series Database
    url: /providers/influxdata/
  layer: common
  name: InfluxDB
  provider: influxdata
  says: ships the InfluxDB SDK or integration code
  source: https://github.com/traefik/traefik/tree/master/pkg/observability/metrics
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.5
    band: developing
    in_catalog: true
    kin_score: 48.3
    mcp: &id015
      status: none
    slug: kubernetes
    status: profiled
    tags: &id016
    - Automation
    - CNCF
    - Cloud-Native
    - Containers
    url: /providers/kubernetes/
  layer: domain
  name: Kubernetes
  provider: kubernetes
  says: ships the Kubernetes SDK or integration code
  source: https://github.com/traefik/traefik/tree/master/pkg/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.50.50
    key: BC-620.50.50
    name: Cryptography and Key Management
    url: /capabilities/security-architecture-management/
    via_parent: Security Architecture Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.2
    band: emerging
    in_catalog: true
    kin_score: 24.3
    mcp: &id017
      status: none
    slug: lets-encrypt
    status: profiled
    tags: &id018
    - Certificates
    - Linux Foundation
    - Security
    - TLS
    url: /providers/lets-encrypt/
  layer: common
  name: Let's Encrypt
  provider: lets-encrypt
  says: ships the Let's Encrypt SDK or integration code
  source: https://github.com/traefik/traefik/blob/master/go.mod
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.7
    band: thin
    in_catalog: true
    kin_score: 39.1
    mcp: &id019
      status: none
    slug: nomad
    status: profiled
    tags: &id020
    - Container Orchestration
    - Infrastructure
    - Scheduling
    - Workload Orchestration
    url: /providers/nomad/
  layer: domain
  name: Nomad
  provider: nomad
  says: ships the Nomad SDK or integration code
  source: https://github.com/traefik/traefik/tree/master/pkg/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.3
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id021
      status: none
    slug: opentelemetry
    status: profiled
    tags: &id022
    - Cloud-Native
    - Logging
    - Metrics
    - Monitoring
    url: /providers/opentelemetry/
  layer: common
  name: OpenTelemetry
  provider: opentelemetry
  says: ships the OpenTelemetry SDK or integration code
  source: https://github.com/traefik/traefik/tree/master/pkg/observability/metrics
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.7
    band: thin
    in_catalog: true
    kin_score: 35.4
    mcp: &id023
      source: https://github.com/prometheus/prometheus-mcp
      status: verified
    slug: prometheus-io
    status: profiled
    tags: &id024
    - Metrics
    - Monitoring
    - Observability
    - Prometheus
    url: /providers/prometheus-io/
  layer: common
  name: Prometheus
  provider: prometheus-io
  says: ships the Prometheus SDK or integration code
  source: https://github.com/traefik/traefik/tree/master/pkg/observability/metrics
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 49.8
    band: developing
    in_catalog: true
    kin_score: 47.4
    mcp: &id025
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id026
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: domain
  name: Redis
  provider: redis
  says: ships the Redis SDK or integration code
  source: https://github.com/traefik/traefik/tree/master/pkg/provider
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.1
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id027
      status: none
    slug: statsd
    status: profiled
    tags: &id028
    - Aggregation
    - Daemon
    - DogStatsD
    - Line Protocol
    url: /providers/statsd/
  layer: common
  name: StatsD
  provider: statsd
  says: ships the StatsD SDK or integration code
  source: https://github.com/traefik/traefik/tree/master/pkg/observability/metrics
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.50.50
    key: BC-620.50.50
    name: Cryptography and Key Management
    url: /capabilities/security-architecture-management/
    via_parent: Security Architecture Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.5
    band: developing
    in_catalog: true
    kin_score: 42.2
    mcp: &id029
      status: none
    slug: tailscale
    status: profiled
    tags: &id030
    - Mesh Networking
    - VPN
    - WireGuard
    - Zero Trust
    url: /providers/tailscale/
  layer: common
  name: Tailscale
  provider: tailscale
  says: ships the Tailscale SDK or integration code
  source: https://github.com/traefik/traefik/tree/master/pkg/provider
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/api-management-gateway/traefik-proxy/
providers:
- agent_band: agent-ready
  agent_readiness: 36.5
  band: strong
  in_catalog: true
  kin_score: 63.0
  mcp: *id001
  name: Amazon ECS
  slug: amazon-ecs
  status: profiled
  tags: *id002
  url: /providers/amazon-ecs/
- agent_band: agent-aware
  agent_readiness: 25.5
  band: thin
  in_catalog: true
  kin_score: 38.7
  mcp: *id003
  name: Apache ZooKeeper
  slug: apache-zookeeper
  status: profiled
  tags: *id004
  url: /providers/apache-zookeeper/
- agent_band: agent-ready
  agent_readiness: 49.6
  band: exemplar
  in_catalog: true
  kin_score: 79.2
  mcp: *id005
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id006
  url: /providers/datadog/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: developing
  in_catalog: true
  kin_score: 52.0
  mcp: *id007
  name: Docker
  slug: docker
  status: profiled
  tags: *id008
  url: /providers/docker/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: developing
  in_catalog: true
  kin_score: 48.5
  mcp: *id009
  name: etcd
  slug: etcd
  status: profiled
  tags: *id010
  url: /providers/etcd/
- agent_band: agent-aware
  agent_readiness: 20.6
  band: thin
  in_catalog: true
  kin_score: 35.7
  mcp: *id011
  name: HashiCorp Consul
  slug: consul
  status: profiled
  tags: *id012
  url: /providers/consul/
- agent_band: agent-ready
  agent_readiness: 35.1
  band: strong
  in_catalog: true
  kin_score: 64.0
  mcp: *id013
  name: InfluxDB
  slug: influxdata
  status: profiled
  tags: *id014
  url: /providers/influxdata/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: developing
  in_catalog: true
  kin_score: 48.3
  mcp: *id015
  name: Kubernetes
  slug: kubernetes
  status: profiled
  tags: *id016
  url: /providers/kubernetes/
- agent_band: agent-aware
  agent_readiness: 17.2
  band: emerging
  in_catalog: true
  kin_score: 24.3
  mcp: *id017
  name: Let's Encrypt
  slug: lets-encrypt
  status: profiled
  tags: *id018
  url: /providers/lets-encrypt/
- agent_band: agent-aware
  agent_readiness: 21.7
  band: thin
  in_catalog: true
  kin_score: 39.1
  mcp: *id019
  name: Nomad
  slug: nomad
  status: profiled
  tags: *id020
  url: /providers/nomad/
- agent_band: agent-aware
  agent_readiness: 27.3
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id021
  name: OpenTelemetry
  slug: opentelemetry
  status: profiled
  tags: *id022
  url: /providers/opentelemetry/
- agent_band: agent-aware
  agent_readiness: 18.7
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id023
  name: Prometheus
  slug: prometheus-io
  status: profiled
  tags: *id024
  url: /providers/prometheus-io/
- agent_band: agent-native
  agent_readiness: 49.8
  band: developing
  in_catalog: true
  kin_score: 47.4
  mcp: *id025
  name: Redis
  slug: redis
  status: profiled
  tags: *id026
  url: /providers/redis/
- agent_band: agent-aware
  agent_readiness: 20.1
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id027
  name: StatsD
  slug: statsd
  status: profiled
  tags: *id028
  url: /providers/statsd/
- agent_band: agent-aware
  agent_readiness: 21.5
  band: developing
  in_catalog: true
  kin_score: 42.2
  mcp: *id029
  name: Tailscale
  slug: tailscale
  status: profiled
  tags: *id030
  url: /providers/tailscale/
siblings:
- name: Apache APISIX
  rows: 36
  url: /applications/api-management-gateway/apache-apisix/
- name: Hoppscotch
  rows: 4
  url: /applications/api-management-gateway/hoppscotch/
- name: Kong Gateway
  rows: 17
  url: /applications/api-management-gateway/kong-gateway/
- name: KrakenD CE
  rows: 12
  url: /applications/api-management-gateway/krakend-ce/
- name: Postman
  rows: 20
  url: /applications/api-management-gateway/postman/
- name: Tyk Gateway + Tyk Pump
  rows: 24
  url: /applications/api-management-gateway/tyk-gateway-tyk-pump/
- name: Zuplo
  rows: 36
  url: /applications/api-management-gateway/zuplo/
sitemap: true
title: 'Traefik Proxy: API Management & Gateways reference app'
---
