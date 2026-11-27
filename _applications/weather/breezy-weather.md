---
app: Breezy Weather
app_slug: breezy-weather
app_url: https://github.com/breezy-weather/breezy-weather
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: domain
  name: Forward Geocoding
  providers:
  - GeoNames
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: domain
  name: IP Geolocation
  providers:
  - Baidu IP location
  - IP.SB
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: API Evangelist extension
  id: AE-120.10.20
  key: AE-120.10.20
  layer: domain
  name: Reverse Geocoding
  providers:
  - NLSC (Taiwan)
  - Nominatim
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-230.10
  key: AE-230.10
  layer: domain
  name: Weather & Environment
  providers:
  - AccuWeather
  - AEMET
  - Atmo France
  - BMD
  - BMKG
  - Bright Sky (DWD open data)
  - ClimWeb (WMO NMHS sites)
  - CWA (Taiwan)
  - DMI
  - ECCC
  - EKUK (Estonia)
  - EPD Hong Kong
  - FMI
  - FOSS Public Alert Server
  - GeoSphere Austria
  - Hong Kong Observatory
  - Ilmateenistus (Estonia)
  - IMD
  - IMS
  - Infoplaza
  - IPMA
  - JMA
  - KNMI
  - LHMT (Lithuania)
  - LVGMC (Latvia)
  - Met Eireann
  - MET Norway
  - Met Office
  - Meteo-France
  - MeteoLux
  - Meteoroloji Genel Mudurlugu
  - NAMEM (Mongolia)
  - National Weather Service
  - NCDR (Taiwan)
  - NOAA NCEI
  - Open-Meteo
  - OpenWeather
  - PAGASA
  - Pirate Weather
  - Polleninfo (EAN)
  - Recosante
  - Servizio Meteo AM
  - SMG (Macao)
  - SMHI
  - Vedurstofa Islands
  - WMO Severe Weather
  url: /capabilities/weather-environment/
  via_parent: null
category:
  id: weather
  name: Weather & Environmental Alerts
  url: /applications/weather/
counts:
  declared: 0
  observed: 51
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/org.breezyweather/latest/
- route: documentation
  url: https://github.com/breezy-weather/breezy-weather/blob/main/docs/SOURCES.md
- route: source code
  url: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: AE-230.10
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.9
    band: developing
    in_catalog: true
    kin_score: 39.8
    mcp: &id001
      status: none
    slug: accuweather
    status: profiled
    tags: &id002
    - Forecast
    - Location Services
    - Meteorology
    - Weather
    url: /providers/accuweather/
  layer: domain
  name: AccuWeather
  provider: accuweather
  says: ships the AccuWeather SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 4.3
    mcp: &id003
      status: unknown
    slug: aemet
    status: profiled
    tags: &id004
    - Public APIs
    - Weather
    url: /providers/aemet/
  layer: domain
  name: AEMET
  provider: aemet
  says: ships the AEMET SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 2.8
    mcp: &id005
      status: none
    slug: atmo-france
    status: profiled
    tags: &id006
    - Air Quality
    - Company
    - Environment
    - Public Service
    url: /providers/atmo-france/
  layer: domain
  name: Atmo France
  provider: atmo-france
  says: ships the Atmo France SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_band: agent-aware
    agent_readiness: 5.8
    band: emerging
    in_catalog: true
    kin_score: 17.4
    mcp: &id007
      source: https://github.com/baidu-maps/mcp
      status: verified
    slug: baidu
    status: profiled
    tags: &id008
    - Artificial Intelligence
    - Company
    - Machine Learning
    - Technology
    url: /providers/baidu/
  layer: domain
  name: Baidu IP location
  provider: baidu
  says: ships the Baidu IP location SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 5.7
    mcp: &id009
      status: unknown
    slug: bangladesh-meteorological-department
    status: profiled
    tags: &id010
    - Climate
    - Company
    - Government
    - Weather
    url: /providers/bangladesh-meteorological-department/
  layer: domain
  name: BMD
  provider: bangladesh-meteorological-department
  says: ships the BMD SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 5.9
    mcp: &id011
      status: unknown
    slug: bmkg
    status: profiled
    tags: &id012
    - Climate
    - Company
    - Geophysics
    - Weather
    url: /providers/bmkg/
  layer: domain
  name: BMKG
  provider: bmkg
  says: ships the BMKG SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_band: agent-aware
    agent_readiness: 25.0
    band: thin
    in_catalog: true
    kin_score: 28.4
    mcp: &id013
      status: unknown
    slug: bright-sky
    status: profiled
    tags: &id014
    - Company
    - JSON
    - Open Data
    - Weather
    url: /providers/bright-sky/
  layer: domain
  name: Bright Sky (DWD open data)
  provider: bright-sky
  says: ships the Bright Sky (DWD open data) SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 2.2
    mcp: &id015
      status: unknown
    slug: climweb
    status: profiled
    tags: &id016
    - Climate Data
    - Company
    - Meteorology
    - Open Source
    url: /providers/climweb/
  layer: domain
  name: ClimWeb (WMO NMHS sites)
  provider: climweb
  says: ships the ClimWeb (WMO NMHS sites) SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 0.4
    mcp: &id017
      status: unknown
    slug: central-weather-administration
    status: profiled
    tags: &id018
    - Company
    url: /providers/central-weather-administration/
  layer: domain
  name: CWA (Taiwan)
  provider: central-weather-administration
  says: ships the CWA (Taiwan) SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_band: agent-aware
    agent_readiness: 22.1
    band: thin
    in_catalog: true
    kin_score: 29.5
    mcp: &id019
      status: none
    slug: danish-meteorological-institutes
    status: profiled
    tags: &id020
    - Climate
    - Environment
    - Lightning
    - Meteorological
    url: /providers/danish-meteorological-institutes/
  layer: domain
  name: DMI
  provider: danish-meteorological-institutes
  says: ships the DMI SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 5.3
    mcp: &id021
      status: none
    slug: environment-and-climate-change-canada
    status: profiled
    tags: &id022
    - GIS
    - Geospatial
    - OGC
    - WMS
    url: /providers/environment-and-climate-change-canada/
  layer: domain
  name: ECCC
  provider: environment-and-climate-change-canada
  says: ships the ECCC SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 2.2
    mcp: &id023
      status: unknown
    slug: ekuk
    status: profiled
    tags: &id024
    - Company
    - Corporate
    - Estonia
    - Technology
    url: /providers/ekuk/
  layer: domain
  name: EKUK (Estonia)
  provider: ekuk
  says: ships the EKUK (Estonia) SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 2.5
    mcp: &id025
      status: unknown
    slug: epd-hong-kong
    status: profiled
    tags: &id026
    - Air Quality
    - Company
    - Environment
    - Government
    url: /providers/epd-hong-kong/
  layer: domain
  name: EPD Hong Kong
  provider: epd-hong-kong
  says: ships the EPD Hong Kong SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 6.2
    mcp: &id027
      status: none
    slug: finnish-meteorological-institute
    status: profiled
    tags: &id028
    - Climate
    - Company
    - Data
    - Weather
    url: /providers/finnish-meteorological-institute/
  layer: domain
  name: FMI
  provider: finnish-meteorological-institute
  says: ships the FMI SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_band: agent-aware
    agent_readiness: 15.1
    band: emerging
    in_catalog: true
    kin_score: 19.4
    mcp: &id029
      status: unknown
    slug: foss-public-alert-server
    status: profiled
    tags: &id030
    - Alert
    - Company
    - Monitoring
    - Open Source
    url: /providers/foss-public-alert-server/
  layer: domain
  name: FOSS Public Alert Server
  provider: foss-public-alert-server
  says: ships the FOSS Public Alert Server SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.3
    mcp: &id031
      status: none
    slug: geonames
    status: profiled
    tags: &id032
    - Geocoding
    - Public APIs
    url: /providers/geonames/
  layer: domain
  name: GeoNames
  provider: geonames
  says: ships the GeoNames SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 4.4
    mcp: &id033
      status: unknown
    slug: geosphere-austria
    status: profiled
    tags: &id034
    - Austria
    - Climate
    - Forecast
    - Weather
    url: /providers/geosphere-austria/
  layer: domain
  name: GeoSphere Austria
  provider: geosphere-austria
  says: ships the GeoSphere Austria SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 4.3
    mcp: &id035
      status: unknown
    slug: hong-kong-obervatory
    status: profiled
    tags: &id036
    - Public APIs
    - Weather
    url: /providers/hong-kong-obervatory/
  layer: domain
  name: Hong Kong Observatory
  provider: hong-kong-obervatory
  says: ships the Hong Kong Observatory SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 6.7
    mcp: &id037
      status: unknown
    slug: ilmateenistus
    status: profiled
    tags: &id038
    - Environment
    - Estonia
    - Government
    - Weather
    url: /providers/ilmateenistus/
  layer: domain
  name: Ilmateenistus (Estonia)
  provider: ilmateenistus
  says: ships the Ilmateenistus (Estonia) SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_band: agent-aware
    agent_readiness: 7.7
    band: emerging
    in_catalog: true
    kin_score: 17.7
    mcp: &id039
      status: unknown
    slug: india-meteorological-department
    status: profiled
    tags: &id040
    - Company
    - India
    - Meteorology
    - Weather
    url: /providers/india-meteorological-department/
  layer: domain
  name: IMD
  provider: india-meteorological-department
  says: ships the IMD SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 4.3
    mcp: &id041
      status: unknown
    slug: israel-meteorological-service
    status: profiled
    tags: &id042
    - Government
    - Israel
    - Meteorology
    - Weather
    url: /providers/israel-meteorological-service/
  layer: domain
  name: IMS
  provider: israel-meteorological-service
  says: ships the IMS SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_band: agent-ready
    agent_readiness: 37.7
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id043
      status: none
    slug: infoplaza
    status: profiled
    tags: &id044
    - Company
    - Forecasting
    - Mobility
    - Weather
    url: /providers/infoplaza/
  layer: domain
  name: Infoplaza
  provider: infoplaza
  says: ships the Infoplaza SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_band: agent-aware
    agent_readiness: 18.0
    band: thin
    in_catalog: true
    kin_score: 30.6
    mcp: &id045
      status: unknown
    slug: ip-sb
    status: profiled
    tags: &id046
    - Company
    - DNS
    - GeoIP
    - IP
    url: /providers/ip-sb/
  layer: domain
  name: IP.SB
  provider: ip-sb
  says: ships the IP.SB SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 4.3
    mcp: &id047
      status: unknown
    slug: ipma
    status: profiled
    tags: &id048
    - Public APIs
    - Weather
    url: /providers/ipma/
  layer: domain
  name: IPMA
  provider: ipma
  says: ships the IPMA SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 4.3
    mcp: &id049
      status: unknown
    slug: japan-meteorological-agency
    status: profiled
    tags: &id050
    - Company
    - Japan
    - Meteorology
    - Weather
    url: /providers/japan-meteorological-agency/
  layer: domain
  name: JMA
  provider: japan-meteorological-agency
  says: ships the JMA SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id051
      status: unchecked
    slug: knmi
    status: queued for profiling
    tags: &id052 []
    url: null
  layer: domain
  name: KNMI
  provider: knmi
  says: ships the KNMI SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_band: agent-aware
    agent_readiness: 12.4
    band: emerging
    in_catalog: true
    kin_score: 13.0
    mcp: &id053
      status: unknown
    slug: lhmt
    status: profiled
    tags: &id054
    - Company
    - Lithuania
    - Meteorology
    - Weather
    url: /providers/lhmt/
  layer: domain
  name: LHMT (Lithuania)
  provider: lhmt
  says: ships the LHMT (Lithuania) SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 0.4
    mcp: &id055
      status: unknown
    slug: lvgmc
    status: profiled
    tags: &id056
    - Company
    url: /providers/lvgmc/
  layer: domain
  name: LVGMC (Latvia)
  provider: lvgmc
  says: ships the LVGMC (Latvia) SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 9.5
    mcp: &id057
      status: unknown
    slug: met-eireann
    status: profiled
    tags: &id058
    - Company
    - Ireland
    - Meteorology
    - Weather
    url: /providers/met-eireann/
  layer: domain
  name: Met Eireann
  provider: met-eireann
  says: ships the Met Eireann SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 7.3
    mcp: &id059
      status: none
    slug: meteorologisk-institutt
    status: profiled
    tags: &id060
    - Public APIs
    - Weather
    url: /providers/meteorologisk-institutt/
  layer: domain
  name: MET Norway
  provider: meteorologisk-institutt
  says: ships the MET Norway SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_band: agent-ready
    agent_readiness: 33.4
    band: strong
    in_catalog: true
    kin_score: 64.3
    mcp: &id061
      status: none
    slug: met-office
    status: profiled
    tags: &id062
    - Climate
    - Company
    - Forecast
    - Weather
    url: /providers/met-office/
  layer: domain
  name: Met Office
  provider: met-office
  says: ships the Met Office SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 4.7
    mcp: &id063
      status: none
    slug: meteo-france
    status: profiled
    tags: &id064
    - Climate
    - Company
    - Forecast
    - Weather
    url: /providers/meteo-france/
  layer: domain
  name: Meteo-France
  provider: meteo-france
  says: ships the Meteo-France SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 10.6
    mcp: &id065
      status: unknown
    slug: meteolux
    status: profiled
    tags: &id066
    - Climate
    - Company
    - Forecast
    - Weather
    url: /providers/meteolux/
  layer: domain
  name: MeteoLux
  provider: meteolux
  says: ships the MeteoLux SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 2.6
    mcp: &id067
      status: unknown
    slug: mgm
    status: profiled
    tags: &id068
    - Climate
    - Company
    - Forecast
    - Weather
    url: /providers/mgm/
  layer: domain
  name: Meteoroloji Genel Mudurlugu
  provider: mgm
  says: ships the Meteoroloji Genel Mudurlugu SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 2.5
    mcp: &id069
      status: unknown
    slug: namem
    status: profiled
    tags: &id070
    - Company
    - Government
    - Mongolia
    - Weather
    url: /providers/namem/
  layer: domain
  name: NAMEM (Mongolia)
  provider: namem
  says: ships the NAMEM (Mongolia) SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_band: agent-aware
    agent_readiness: 22.8
    band: thin
    in_catalog: true
    kin_score: 35.6
    mcp: &id071
      status: none
    slug: weather-gov
    status: profiled
    tags: &id072
    - Forecasting
    - Government
    - United States
    - Weather
    url: /providers/weather-gov/
  layer: domain
  name: National Weather Service
  provider: weather-gov
  says: ships the National Weather Service SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 2.5
    mcp: &id073
      status: unknown
    slug: ncdr
    status: profiled
    tags: &id074
    - Disaster Management
    - Government
    - Public Safety
    - Taiwan
    url: /providers/ncdr/
  layer: domain
  name: NCDR (Taiwan)
  provider: ncdr
  says: ships the NCDR (Taiwan) SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.20
    key: AE-120.10.20
    name: Reverse Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id075
      status: unknown
    slug: nlsc
    status: profiled
    tags: &id076
    - Company
    url: /providers/nlsc/
  layer: domain
  name: NLSC (Taiwan)
  provider: nlsc
  says: ships the NLSC (Taiwan) SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_band: agent-ready
    agent_readiness: 32.1
    band: thin
    in_catalog: true
    kin_score: 38.9
    mcp: &id077
      status: unknown
    slug: noaa-gov
    status: profiled
    tags: &id078
    - Climate
    - Ocean
    - Space Weather
    - Weather
    url: /providers/noaa-gov/
  layer: domain
  name: NOAA NCEI
  provider: noaa-gov
  says: ships the NOAA NCEI SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.20
    key: AE-120.10.20
    name: Reverse Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.7
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id079
      status: none
    slug: nominatim
    status: profiled
    tags: &id080
    - Geocoding
    - Location Services
    - Maps
    - OpenStreetMap
    url: /providers/nominatim/
  layer: domain
  name: Nominatim
  provider: nominatim
  says: ships the Nominatim SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_band: agent-aware
    agent_readiness: 17.4
    band: thin
    in_catalog: true
    kin_score: 28.3
    mcp: &id081
      status: none
    slug: open-meteo
    status: profiled
    tags: &id082
    - Air Quality
    - Forecast
    - Historical Weather
    - Weather
    url: /providers/open-meteo/
  layer: domain
  name: Open-Meteo
  provider: open-meteo
  says: ships the Open-Meteo SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_band: agent-ready
    agent_readiness: 30.0
    band: strong
    in_catalog: true
    kin_score: 59.1
    mcp: &id083
      source: https://mcp.openweathermap.org/
      status: verified
    slug: openweathermap
    status: profiled
    tags: &id084
    - Air Pollution
    - Climate
    - Forecast
    - Weather
    url: /providers/openweathermap/
  layer: domain
  name: OpenWeather
  provider: openweathermap
  says: ships the OpenWeather SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 5.6
    mcp: &id085
      status: unknown
    slug: pagasa
    status: profiled
    tags: &id086
    - Company
    - Meteorology
    - Philippines
    - Weather
    url: /providers/pagasa/
  layer: domain
  name: PAGASA
  provider: pagasa
  says: ships the PAGASA SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 2.4
    mcp: &id087
      source: https://pirateweather.net/
      status: documented
    slug: pirate-weather
    status: profiled
    tags: &id088
    - Public APIs
    - Weather
    url: /providers/pirate-weather/
  layer: domain
  name: Pirate Weather
  provider: pirate-weather
  says: ships the Pirate Weather SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 3.6
    mcp: &id089
      status: none
    slug: polleninfo
    status: profiled
    tags: &id090
    - Allergy
    - Company
    - Data
    - Health
    url: /providers/polleninfo/
  layer: domain
  name: Polleninfo (EAN)
  provider: polleninfo
  says: ships the Polleninfo (EAN) SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id091
      status: unchecked
    slug: recosante
    status: queued for profiling
    tags: &id092 []
    url: null
  layer: domain
  name: Recosante
  provider: recosante
  says: ships the Recosante SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    band: emerging
    in_catalog: true
    kin_score: 12.1
    mcp: &id093
      status: unknown
    slug: meteoam
    status: profiled
    tags: &id094
    - Aviation
    - Company
    - Meteorology
    - Weather
    url: /providers/meteoam/
  layer: domain
  name: Servizio Meteo AM
  provider: meteoam
  says: ships the Servizio Meteo AM SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 1.3
    mcp: &id095
      status: unknown
    slug: smg-macao
    status: profiled
    tags: &id096
    - Company
    url: /providers/smg-macao/
  layer: domain
  name: SMG (Macao)
  provider: smg-macao
  says: ships the SMG (Macao) SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    band: emerging
    in_catalog: true
    kin_score: 12.5
    mcp: &id097
      status: none
    slug: smhi
    status: profiled
    tags: &id098
    - Climate
    - Data
    - Research
    - Weather
    url: /providers/smhi/
  layer: domain
  name: SMHI
  provider: smhi
  says: ships the SMHI SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    kin_score: 2.9
    mcp: &id099
      status: unknown
    slug: vedur
    status: profiled
    tags: &id100
    - Forecast
    - Iceland
    - Meteorology
    - Weather
    url: /providers/vedur/
  layer: domain
  name: Vedurstofa Islands
  provider: vedur
  says: ships the Vedurstofa Islands SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
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
    agent_band: agent-aware
    agent_readiness: 26.9
    band: thin
    in_catalog: true
    kin_score: 31.8
    mcp: &id101
      status: unknown
    slug: wmo
    status: profiled
    tags: &id102
    - Climate
    - Hydrology
    - Meteorology
    - Weather
    url: /providers/wmo/
  layer: domain
  name: WMO Severe Weather
  provider: wmo
  says: ships the WMO Severe Weather SDK or integration code
  source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/weather/breezy-weather/
providers:
- agent_band: agent-aware
  agent_readiness: 24.9
  band: developing
  in_catalog: true
  kin_score: 39.8
  mcp: *id001
  name: AccuWeather
  slug: accuweather
  status: profiled
  tags: *id002
  url: /providers/accuweather/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id003
  name: AEMET
  slug: aemet
  status: profiled
  tags: *id004
  url: /providers/aemet/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.8
  mcp: *id005
  name: Atmo France
  slug: atmo-france
  status: profiled
  tags: *id006
  url: /providers/atmo-france/
- agent_band: agent-aware
  agent_readiness: 5.8
  band: emerging
  in_catalog: true
  kin_score: 17.4
  mcp: *id007
  name: Baidu IP location
  slug: baidu
  status: profiled
  tags: *id008
  url: /providers/baidu/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.7
  mcp: *id009
  name: BMD
  slug: bangladesh-meteorological-department
  status: profiled
  tags: *id010
  url: /providers/bangladesh-meteorological-department/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.9
  mcp: *id011
  name: BMKG
  slug: bmkg
  status: profiled
  tags: *id012
  url: /providers/bmkg/
- agent_band: agent-aware
  agent_readiness: 25.0
  band: thin
  in_catalog: true
  kin_score: 28.4
  mcp: *id013
  name: Bright Sky (DWD open data)
  slug: bright-sky
  status: profiled
  tags: *id014
  url: /providers/bright-sky/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id015
  name: ClimWeb (WMO NMHS sites)
  slug: climweb
  status: profiled
  tags: *id016
  url: /providers/climweb/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id017
  name: CWA (Taiwan)
  slug: central-weather-administration
  status: profiled
  tags: *id018
  url: /providers/central-weather-administration/
- agent_band: agent-aware
  agent_readiness: 22.1
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id019
  name: DMI
  slug: danish-meteorological-institutes
  status: profiled
  tags: *id020
  url: /providers/danish-meteorological-institutes/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.3
  mcp: *id021
  name: ECCC
  slug: environment-and-climate-change-canada
  status: profiled
  tags: *id022
  url: /providers/environment-and-climate-change-canada/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id023
  name: EKUK (Estonia)
  slug: ekuk
  status: profiled
  tags: *id024
  url: /providers/ekuk/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.5
  mcp: *id025
  name: EPD Hong Kong
  slug: epd-hong-kong
  status: profiled
  tags: *id026
  url: /providers/epd-hong-kong/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.2
  mcp: *id027
  name: FMI
  slug: finnish-meteorological-institute
  status: profiled
  tags: *id028
  url: /providers/finnish-meteorological-institute/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 19.4
  mcp: *id029
  name: FOSS Public Alert Server
  slug: foss-public-alert-server
  status: profiled
  tags: *id030
  url: /providers/foss-public-alert-server/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id031
  name: GeoNames
  slug: geonames
  status: profiled
  tags: *id032
  url: /providers/geonames/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.4
  mcp: *id033
  name: GeoSphere Austria
  slug: geosphere-austria
  status: profiled
  tags: *id034
  url: /providers/geosphere-austria/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id035
  name: Hong Kong Observatory
  slug: hong-kong-obervatory
  status: profiled
  tags: *id036
  url: /providers/hong-kong-obervatory/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.7
  mcp: *id037
  name: Ilmateenistus (Estonia)
  slug: ilmateenistus
  status: profiled
  tags: *id038
  url: /providers/ilmateenistus/
- agent_band: agent-aware
  agent_readiness: 7.7
  band: emerging
  in_catalog: true
  kin_score: 17.7
  mcp: *id039
  name: IMD
  slug: india-meteorological-department
  status: profiled
  tags: *id040
  url: /providers/india-meteorological-department/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id041
  name: IMS
  slug: israel-meteorological-service
  status: profiled
  tags: *id042
  url: /providers/israel-meteorological-service/
- agent_band: agent-ready
  agent_readiness: 37.7
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id043
  name: Infoplaza
  slug: infoplaza
  status: profiled
  tags: *id044
  url: /providers/infoplaza/
- agent_band: agent-aware
  agent_readiness: 18.0
  band: thin
  in_catalog: true
  kin_score: 30.6
  mcp: *id045
  name: IP.SB
  slug: ip-sb
  status: profiled
  tags: *id046
  url: /providers/ip-sb/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id047
  name: IPMA
  slug: ipma
  status: profiled
  tags: *id048
  url: /providers/ipma/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id049
  name: JMA
  slug: japan-meteorological-agency
  status: profiled
  tags: *id050
  url: /providers/japan-meteorological-agency/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id051
  name: KNMI
  slug: knmi
  status: queued for profiling
  tags: *id052
  url: null
- agent_band: agent-aware
  agent_readiness: 12.4
  band: emerging
  in_catalog: true
  kin_score: 13.0
  mcp: *id053
  name: LHMT (Lithuania)
  slug: lhmt
  status: profiled
  tags: *id054
  url: /providers/lhmt/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id055
  name: LVGMC (Latvia)
  slug: lvgmc
  status: profiled
  tags: *id056
  url: /providers/lvgmc/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.5
  mcp: *id057
  name: Met Eireann
  slug: met-eireann
  status: profiled
  tags: *id058
  url: /providers/met-eireann/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.3
  mcp: *id059
  name: MET Norway
  slug: meteorologisk-institutt
  status: profiled
  tags: *id060
  url: /providers/meteorologisk-institutt/
- agent_band: agent-ready
  agent_readiness: 33.4
  band: strong
  in_catalog: true
  kin_score: 64.3
  mcp: *id061
  name: Met Office
  slug: met-office
  status: profiled
  tags: *id062
  url: /providers/met-office/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.7
  mcp: *id063
  name: Meteo-France
  slug: meteo-france
  status: profiled
  tags: *id064
  url: /providers/meteo-france/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.6
  mcp: *id065
  name: MeteoLux
  slug: meteolux
  status: profiled
  tags: *id066
  url: /providers/meteolux/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.6
  mcp: *id067
  name: Meteoroloji Genel Mudurlugu
  slug: mgm
  status: profiled
  tags: *id068
  url: /providers/mgm/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.5
  mcp: *id069
  name: NAMEM (Mongolia)
  slug: namem
  status: profiled
  tags: *id070
  url: /providers/namem/
- agent_band: agent-aware
  agent_readiness: 22.8
  band: thin
  in_catalog: true
  kin_score: 35.6
  mcp: *id071
  name: National Weather Service
  slug: weather-gov
  status: profiled
  tags: *id072
  url: /providers/weather-gov/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.5
  mcp: *id073
  name: NCDR (Taiwan)
  slug: ncdr
  status: profiled
  tags: *id074
  url: /providers/ncdr/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id075
  name: NLSC (Taiwan)
  slug: nlsc
  status: profiled
  tags: *id076
  url: /providers/nlsc/
- agent_band: agent-ready
  agent_readiness: 32.1
  band: thin
  in_catalog: true
  kin_score: 38.9
  mcp: *id077
  name: NOAA NCEI
  slug: noaa-gov
  status: profiled
  tags: *id078
  url: /providers/noaa-gov/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id079
  name: Nominatim
  slug: nominatim
  status: profiled
  tags: *id080
  url: /providers/nominatim/
- agent_band: agent-aware
  agent_readiness: 17.4
  band: thin
  in_catalog: true
  kin_score: 28.3
  mcp: *id081
  name: Open-Meteo
  slug: open-meteo
  status: profiled
  tags: *id082
  url: /providers/open-meteo/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: strong
  in_catalog: true
  kin_score: 59.1
  mcp: *id083
  name: OpenWeather
  slug: openweathermap
  status: profiled
  tags: *id084
  url: /providers/openweathermap/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id085
  name: PAGASA
  slug: pagasa
  status: profiled
  tags: *id086
  url: /providers/pagasa/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.4
  mcp: *id087
  name: Pirate Weather
  slug: pirate-weather
  status: profiled
  tags: *id088
  url: /providers/pirate-weather/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.6
  mcp: *id089
  name: Polleninfo (EAN)
  slug: polleninfo
  status: profiled
  tags: *id090
  url: /providers/polleninfo/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id091
  name: Recosante
  slug: recosante
  status: queued for profiling
  tags: *id092
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.1
  mcp: *id093
  name: Servizio Meteo AM
  slug: meteoam
  status: profiled
  tags: *id094
  url: /providers/meteoam/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.3
  mcp: *id095
  name: SMG (Macao)
  slug: smg-macao
  status: profiled
  tags: *id096
  url: /providers/smg-macao/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.5
  mcp: *id097
  name: SMHI
  slug: smhi
  status: profiled
  tags: *id098
  url: /providers/smhi/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.9
  mcp: *id099
  name: Vedurstofa Islands
  slug: vedur
  status: profiled
  tags: *id100
  url: /providers/vedur/
- agent_band: agent-aware
  agent_readiness: 26.9
  band: thin
  in_catalog: true
  kin_score: 31.8
  mcp: *id101
  name: WMO Severe Weather
  slug: wmo
  status: profiled
  tags: *id102
  url: /providers/wmo/
siblings:
- name: AccuWeather
  rows: 3
  url: /applications/weather/accuweather/
- name: Carrot Weather
  rows: 3
  url: /applications/weather/carrot-weather/
- name: MagicMirror2 weather module
  rows: 13
  url: /applications/weather/magicmirror2-weather-module/
- name: WeeWX
  rows: 6
  url: /applications/weather/weewx/
- name: Windy
  rows: 6
  url: /applications/weather/windy/
- name: wttr.in
  rows: 5
  url: /applications/weather/wttr-in/
sitemap: true
title: 'Breezy Weather: Weather & Environmental Alerts reference app'
---
