---
access: understanding
agent_layer: []
apps:
- anchor: breezy-weather
  counts:
    declared: 0
    observed: 51
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
    layer: domain
    name: WMO Severe Weather
    provider: wmo
    says: ships the WMO Severe Weather SDK or integration code
    source: https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
    tier: observed
  kind: self-hosted
  name: Breezy Weather
  page: /applications/weather/breezy-weather/
  slug: breezy-weather
  url: https://github.com/breezy-weather/breezy-weather
- anchor: magicmirror2-weather-module
  counts:
    declared: 0
    observed: 13
  evidence:
  - route: source code
    url: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: Buienradar
    provider: buienradar
    says: ships the Buienradar SDK or integration code
    source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: Environment Canada
    provider: environment-and-climate-change-canada
    says: ships the Environment Canada SDK or integration code
    source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: FMI
    provider: finnish-meteorological-institute
    says: ships the FMI SDK or integration code
    source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: Open-Meteo
    provider: open-meteo
    says: ships the Open-Meteo SDK or integration code
    source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: OpenWeatherMap
    provider: openweathermap
    says: ships the OpenWeatherMap SDK or integration code
    source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: Pirate Weather
    provider: pirate-weather
    says: ships the Pirate Weather SDK or integration code
    source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: SMHI
    provider: smhi
    says: ships the SMHI SDK or integration code
    source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: UK Met Office DataHub
    provider: met-office
    says: ships the UK Met Office DataHub SDK or integration code
    source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: weather.gov (NWS)
    provider: weather-gov
    says: ships the weather.gov (NWS) SDK or integration code
    source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: WeatherAPI.com
    provider: weatherapi
    says: ships the WeatherAPI.com SDK or integration code
    source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: Weatherbit
    provider: weatherbit
    says: ships the Weatherbit SDK or integration code
    source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: WeatherFlow (Tempest)
    provider: weatherflow
    says: ships the WeatherFlow (Tempest) SDK or integration code
    source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: yr.no (MET Norway)
    provider: meteorologisk-institutt
    says: ships the yr.no (MET Norway) SDK or integration code
    source: https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
    tier: observed
  kind: self-hosted
  name: MagicMirror2 weather module
  page: /applications/weather/magicmirror2-weather-module/
  slug: magicmirror2-weather-module
  url: https://github.com/MagicMirrorOrg/MagicMirror
- anchor: wttrin
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: documentation
    url: https://github.com/chubin/wttr.in/blob/master/README.md
  - route: source code
    url: https://github.com/chubin/wttr.in/tree/master/internal
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: LocationIQ
    provider: locationiq
    says: ships the LocationIQ SDK or integration code
    source: https://github.com/chubin/wttr.in/tree/master/internal/location
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
    name: MaxMind GeoLite2
    provider: maxmind
    says: ships the MaxMind GeoLite2 SDK or integration code
    source: https://github.com/chubin/wttr.in/tree/master/internal/ip
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: Nominatim
    provider: nominatim
    says: ships the Nominatim SDK or integration code
    source: https://github.com/chubin/wttr.in/tree/master/internal/location
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: OpenCage
    provider: opencage
    says: ships the OpenCage SDK or integration code
    source: https://github.com/chubin/wttr.in/tree/master/internal/location
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: World Weather Online
    provider: worldweatheronline
    says: ships the World Weather Online SDK or integration code
    source: https://github.com/chubin/wttr.in/tree/master/internal/weather
    tier: observed
  kind: self-hosted
  name: wttr.in
  page: /applications/weather/wttr-in/
  slug: wttr-in
  url: https://github.com/chubin/wttr.in
- anchor: weewx
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: source code
    url: https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10.10
      key: AE-230.10.10
      name: Personal Weather Station Networks
      url: /capabilities/weather-environment/
      via_parent: Weather & Environment
    credit: null
    layer: domain
    name: AWEKAS
    provider: awekas
    says: ships the AWEKAS SDK or integration code
    source: https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10.10
      key: AE-230.10.10
      name: Personal Weather Station Networks
      url: /capabilities/weather-environment/
      via_parent: Weather & Environment
    credit: null
    layer: domain
    name: Citizen Weather Observer Program
    provider: cwop
    says: ships the Citizen Weather Observer Program SDK or integration code
    source: https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10.10
      key: AE-230.10.10
      name: Personal Weather Station Networks
      url: /capabilities/weather-environment/
      via_parent: Weather & Environment
    credit: null
    layer: domain
    name: Met Office WOW
    provider: met-office
    says: ships the Met Office WOW SDK or integration code
    source: https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10.10
      key: AE-230.10.10
      name: Personal Weather Station Networks
      url: /capabilities/weather-environment/
      via_parent: Weather & Environment
    credit: null
    layer: domain
    name: PWSweather
    provider: pwsweather
    says: ships the PWSweather SDK or integration code
    source: https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10.10
      key: AE-230.10.10
      name: Personal Weather Station Networks
      url: /capabilities/weather-environment/
      via_parent: Weather & Environment
    credit: null
    layer: domain
    name: RMI Belgium WOW-BE
    provider: royal-meteorological-institute-belgium
    says: ships the RMI Belgium WOW-BE SDK or integration code
    source: https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10.10
      key: AE-230.10.10
      name: Personal Weather Station Networks
      url: /capabilities/weather-environment/
      via_parent: Weather & Environment
    credit: null
    layer: domain
    name: Weather Underground
    provider: wunderground
    says: ships the Weather Underground SDK or integration code
    source: https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
    tier: observed
  kind: self-hosted
  name: WeeWX
  page: /applications/weather/weewx/
  slug: weewx
  url: https://github.com/weewx/weewx
- anchor: carrot-weather
  counts:
    declared: 3
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.meetcarrot.com/weather/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: AccuWeather
    provider: accuweather
    says: lists AccuWeather as an integration
    source: https://www.meetcarrot.com/weather/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: Apple Weather (WeatherKit)
    provider: apple
    says: lists Apple Weather (WeatherKit) as an integration
    source: https://www.meetcarrot.com/weather/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: Foreca
    provider: foreca
    says: lists Foreca as an integration
    source: https://www.meetcarrot.com/weather/
    tier: declared
  kind: commercial
  name: Carrot Weather
  page: /applications/weather/carrot-weather/
  slug: carrot-weather
  url: https://www.meetcarrot.com/weather/
- anchor: windy
  counts:
    declared: 4
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.windyty.android/latest/
  - route: documentation
    url: https://community.windy.com/topic/12/what-source-of-weather-data-windy-use
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
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.windyty.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook Analytics / Login / Share
    provider: facebook
    says: ships the Facebook Analytics / Login / Share SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.windyty.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: DWD (ICON-EU)
    provider: deutscher-wetterdienst
    says: lists DWD (ICON-EU) as an integration
    source: https://community.windy.com/topic/12/what-source-of-weather-data-windy-use
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: ECMWF
    provider: ecmwf
    says: lists ECMWF as an integration
    source: https://community.windy.com/topic/12/what-source-of-weather-data-windy-use
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: Meteoblue (NEMS)
    provider: meteoblue
    says: lists Meteoblue (NEMS) as an integration
    source: https://community.windy.com/topic/12/what-source-of-weather-data-windy-use
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: NOAA (GFS)
    provider: noaa-gov
    says: lists NOAA (GFS) as an integration
    source: https://community.windy.com/topic/12/what-source-of-weather-data-windy-use
    tier: declared
  kind: commercial
  name: Windy
  page: /applications/weather/windy/
  slug: windy
  url: https://www.windy.com/
- anchor: accuweather
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.accuweather.android/latest/
  integrations:
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.accuweather.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.accuweather.android/latest/
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
    name: Google Firebase Analytics / Crashlytics
    provider: firebase
    says: ships the Google Firebase Analytics / Crashlytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.accuweather.android/latest/
    tier: observed
  kind: commercial
  name: AccuWeather
  page: /applications/weather/accuweather/
  slug: accuweather
  url: https://www.accuweather.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: weather
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Weather
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Weather
  store: google-play
  url: https://play.google.com/store/apps/category/WEATHER
- category: Weather
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted
name: Weather & Environmental Alerts
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: AE-230.10
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  fit: exact
  layer: domain
  why: 'forecasts, observations, alerts, air quality and pollen: the category itself'
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: common
  why: location search for a city name
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.20
    key: AE-120.10.20
    name: Reverse Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: common
  why: naming the device location
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: common
  why: default location without GPS
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile attribution SDKs in the Android apps
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: social sign-in SDK in the Android apps
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: in-app ad SDK in the Android apps
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: app telemetry in the Android apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: push notification SDK in the Android apps
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.5
      apps:
      - Breezy Weather
      - MagicMirror2 weather module
      band: strong
      in_catalog: true
      kin_score: 60.4
      mcp:
        source: https://mcp.openweathermap.org/
        status: verified
      name: OpenWeather
      slug: openweathermap
      sources:
      - https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Air Pollution
      - Climate
      - Forecast
      - Weather
      tier: observed
      url: /providers/openweathermap/
    - agent_band: agent-ready
      agent_readiness: 34.2
      apps:
      - Breezy Weather
      - MagicMirror2 weather module
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp: &id001
        status: none
      name: Met Office
      slug: met-office
      sources:
      - https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags: &id002
      - Climate
      - Company
      - Forecast
      - Weather
      tier: observed
      url: /providers/met-office/
    - agent_band: agent-aware
      agent_readiness: 25.5
      apps:
      - Breezy Weather
      - Carrot Weather
      band: developing
      in_catalog: true
      kin_score: 42.6
      mcp:
        status: none
      name: AccuWeather
      slug: accuweather
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      - https://www.meetcarrot.com/weather/
      status: profiled
      tags:
      - Forecast
      - Location Services
      - Meteorology
      - Weather
      tier: observed
      url: /providers/accuweather/
    - agent_band: agent-aware
      agent_readiness: 26.6
      apps:
      - Breezy Weather
      - Windy
      band: developing
      in_catalog: true
      kin_score: 40.5
      mcp:
        status: unknown
      name: NOAA NCEI
      slug: noaa-gov
      sources:
      - https://community.windy.com/topic/12/what-source-of-weather-data-windy-use
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Climate
      - Ocean
      - Space Weather
      - Weather
      tier: observed
      url: /providers/noaa-gov/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Breezy Weather
      - MagicMirror2 weather module
      band: thin
      in_catalog: true
      kin_score: 36.6
      mcp:
        status: none
      name: National Weather Service
      slug: weather-gov
      sources:
      - https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Forecasting
      - Government
      - United States
      - Weather
      tier: observed
      url: /providers/weather-gov/
    - agent_band: agent-aware
      agent_readiness: 17.8
      apps:
      - Breezy Weather
      - MagicMirror2 weather module
      band: thin
      in_catalog: true
      kin_score: 29.6
      mcp:
        status: none
      name: Open-Meteo
      slug: open-meteo
      sources:
      - https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Air Quality
      - Forecast
      - Historical Weather
      - Weather
      tier: observed
      url: /providers/open-meteo/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      - MagicMirror2 weather module
      band: minimal
      in_catalog: true
      kin_score: 9.4
      mcp:
        status: none
      name: SMHI
      slug: smhi
      sources:
      - https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Climate
      - Data
      - Research
      - Weather
      tier: observed
      url: /providers/smhi/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      - MagicMirror2 weather module
      band: minimal
      in_catalog: true
      kin_score: 7.4
      mcp:
        status: none
      name: MET Norway
      slug: meteorologisk-institutt
      sources:
      - https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Public APIs
      - Weather
      tier: observed
      url: /providers/meteorologisk-institutt/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      - MagicMirror2 weather module
      band: minimal
      in_catalog: true
      kin_score: 6.2
      mcp:
        status: none
      name: FMI
      slug: finnish-meteorological-institute
      sources:
      - https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Climate
      - Company
      - Data
      - Weather
      tier: observed
      url: /providers/finnish-meteorological-institute/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      - MagicMirror2 weather module
      band: minimal
      in_catalog: true
      kin_score: 5.3
      mcp:
        status: none
      name: ECCC
      slug: environment-and-climate-change-canada
      sources:
      - https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - GIS
      - Geospatial
      - OGC
      - WMS
      tier: observed
      url: /providers/environment-and-climate-change-canada/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      - MagicMirror2 weather module
      band: minimal
      in_catalog: true
      kin_score: 3.3
      mcp:
        source: https://pirateweather.net/
        status: documented
      name: Pirate Weather
      slug: pirate-weather
      sources:
      - https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Public APIs
      - Weather
      tier: observed
      url: /providers/pirate-weather/
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - MagicMirror2 weather module
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        status: unknown
      name: WeatherAPI.com
      slug: weatherapi
      sources:
      - https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
      status: profiled
      tags:
      - Forecast
      - History
      - Marine
      - Weather
      tier: observed
      url: /providers/weatherapi/
    - agent_band: agent-native
      agent_readiness: 38.7
      apps:
      - Breezy Weather
      band: developing
      in_catalog: true
      kin_score: 44.0
      mcp:
        status: none
      name: Infoplaza
      slug: infoplaza
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Company
      - Forecasting
      - Mobility
      - Weather
      tier: observed
      url: /providers/infoplaza/
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - MagicMirror2 weather module
      band: thin
      in_catalog: true
      kin_score: 39.1
      mcp:
        status: none
      name: Weatherbit
      slug: weatherbit
      sources:
      - https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
      status: profiled
      tags:
      - Air Quality
      - Forecasting
      - Historical Data
      - Weather
      tier: observed
      url: /providers/weatherbit/
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Breezy Weather
      band: thin
      in_catalog: true
      kin_score: 31.3
      mcp:
        status: unknown
      name: WMO Severe Weather
      slug: wmo
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Climate
      - Hydrology
      - Meteorology
      - Weather
      tier: observed
      url: /providers/wmo/
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - Breezy Weather
      band: thin
      in_catalog: true
      kin_score: 29.8
      mcp:
        status: none
      name: DMI
      slug: danish-meteorological-institutes
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Climate
      - Environment
      - Lightning
      - Meteorological
      tier: observed
      url: /providers/danish-meteorological-institutes/
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - Breezy Weather
      band: thin
      in_catalog: true
      kin_score: 26.4
      mcp:
        status: unknown
      name: Bright Sky (DWD open data)
      slug: bright-sky
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Company
      - JSON
      - Open Data
      - Weather
      tier: observed
      url: /providers/bright-sky/
    - agent_band: agent-aware
      agent_readiness: 15.5
      apps:
      - Breezy Weather
      band: emerging
      in_catalog: true
      kin_score: 17.9
      mcp:
        status: unknown
      name: FOSS Public Alert Server
      slug: foss-public-alert-server
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Alert
      - Company
      - Monitoring
      - Open Source
      tier: observed
      url: /providers/foss-public-alert-server/
    - agent_band: agent-aware
      agent_readiness: 7.9
      apps:
      - Breezy Weather
      band: emerging
      in_catalog: true
      kin_score: 14.7
      mcp:
        status: unknown
      name: IMD
      slug: india-meteorological-department
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Company
      - India
      - Meteorology
      - Weather
      tier: observed
      url: /providers/india-meteorological-department/
    - agent_band: agent-aware
      agent_readiness: 14.6
      apps:
      - Breezy Weather
      band: emerging
      in_catalog: true
      kin_score: 13.9
      mcp:
        status: unknown
      name: LHMT (Lithuania)
      slug: lhmt
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Company
      - Lithuania
      - Meteorology
      - Weather
      tier: observed
      url: /providers/lhmt/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 8.0
      mcp:
        status: unknown
      name: Servizio Meteo AM
      slug: meteoam
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Aviation
      - Company
      - Meteorology
      - Weather
      tier: observed
      url: /providers/meteoam/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 8.0
      mcp:
        status: unknown
      name: MeteoLux
      slug: meteolux
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Climate
      - Company
      - Forecast
      - Weather
      tier: observed
      url: /providers/meteolux/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 7.7
      mcp:
        status: unknown
      name: Met Eireann
      slug: met-eireann
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Company
      - Ireland
      - Meteorology
      - Weather
      tier: observed
      url: /providers/met-eireann/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 7.5
      mcp:
        status: unknown
      name: Ilmateenistus (Estonia)
      slug: ilmateenistus
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Environment
      - Estonia
      - Government
      - Weather
      tier: observed
      url: /providers/ilmateenistus/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 5.8
      mcp:
        status: unknown
      name: BMKG
      slug: bmkg
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Climate
      - Company
      - Geophysics
      - Weather
      tier: observed
      url: /providers/bmkg/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        status: unknown
      name: AEMET
      slug: aemet
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Public APIs
      - Weather
      tier: observed
      url: /providers/aemet/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        status: unknown
      name: Hong Kong Observatory
      slug: hong-kong-obervatory
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Public APIs
      - Weather
      tier: observed
      url: /providers/hong-kong-obervatory/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        status: unknown
      name: IPMA
      slug: ipma
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Public APIs
      - Weather
      tier: observed
      url: /providers/ipma/
    - agent_band: agent-aware
      agent_readiness: 5.4
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        status: unknown
      name: IMS
      slug: israel-meteorological-service
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Government
      - Israel
      - Meteorology
      - Weather
      tier: observed
      url: /providers/israel-meteorological-service/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 5.1
      mcp:
        status: unknown
      name: BMD
      slug: bangladesh-meteorological-department
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Climate
      - Company
      - Government
      - Weather
      tier: observed
      url: /providers/bangladesh-meteorological-department/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 5.1
      mcp:
        status: unknown
      name: GeoSphere Austria
      slug: geosphere-austria
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Austria
      - Climate
      - Forecast
      - Weather
      tier: observed
      url: /providers/geosphere-austria/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 4.7
      mcp:
        status: unknown
      name: PAGASA
      slug: pagasa
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Company
      - Meteorology
      - Philippines
      - Weather
      tier: observed
      url: /providers/pagasa/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - MagicMirror2 weather module
      band: minimal
      in_catalog: true
      kin_score: 4.5
      mcp:
        status: unknown
      name: Buienradar
      slug: buienradar
      sources:
      - https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
      status: profiled
      tags:
      - Company
      - Forecast
      - Radar
      - Weather
      tier: observed
      url: /providers/buienradar/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 4.4
      mcp:
        status: none
      name: Meteo-France
      slug: meteo-france
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Climate
      - Company
      - Forecast
      - Weather
      tier: observed
      url: /providers/meteo-france/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 4.3
      mcp:
        status: unknown
      name: JMA
      slug: japan-meteorological-agency
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Company
      - Japan
      - Meteorology
      - Weather
      tier: observed
      url: /providers/japan-meteorological-agency/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 4.0
      mcp:
        status: none
      name: Polleninfo (EAN)
      slug: polleninfo
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Allergy
      - Company
      - Data
      - Health
      tier: observed
      url: /providers/polleninfo/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - MagicMirror2 weather module
      band: minimal
      in_catalog: true
      kin_score: 3.5
      mcp:
        status: none
      name: WeatherFlow (Tempest)
      slug: weatherflow
      sources:
      - https://github.com/MagicMirrorOrg/MagicMirror/tree/master/defaultmodules/weather/providers
      status: profiled
      tags:
      - Company
      - IoT
      - Real-Time
      - Weather
      tier: observed
      url: /providers/weatherflow/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 3.4
      mcp:
        status: none
      name: Atmo France
      slug: atmo-france
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Air Quality
      - Company
      - Environment
      - Public Service
      tier: observed
      url: /providers/atmo-france/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 3.4
      mcp:
        status: unknown
      name: Meteoroloji Genel Mudurlugu
      slug: mgm
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Climate
      - Company
      - Forecast
      - Weather
      tier: observed
      url: /providers/mgm/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 3.4
      mcp:
        status: unknown
      name: NAMEM (Mongolia)
      slug: namem
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Company
      - Government
      - Mongolia
      - Weather
      tier: observed
      url: /providers/namem/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 3.4
      mcp:
        status: unknown
      name: NCDR (Taiwan)
      slug: ncdr
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Disaster Management
      - Government
      - Public Safety
      - Taiwan
      tier: observed
      url: /providers/ncdr/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 3.4
      mcp:
        status: unknown
      name: Vedurstofa Islands
      slug: vedur
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Forecast
      - Iceland
      - Meteorology
      - Weather
      tier: observed
      url: /providers/vedur/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 3.1
      mcp:
        status: unknown
      name: ClimWeb (WMO NMHS sites)
      slug: climweb
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Climate Data
      - Company
      - Meteorology
      - Open Source
      tier: observed
      url: /providers/climweb/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 3.1
      mcp:
        status: unknown
      name: EKUK (Estonia)
      slug: ekuk
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Company
      - Corporate
      - Estonia
      - Technology
      tier: observed
      url: /providers/ekuk/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 2.5
      mcp:
        status: unknown
      name: EPD Hong Kong
      slug: epd-hong-kong
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Air Quality
      - Company
      - Environment
      - Government
      tier: observed
      url: /providers/epd-hong-kong/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 2.2
      mcp:
        status: unknown
      name: SMG (Macao)
      slug: smg-macao
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/smg-macao/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 1.3
      mcp:
        status: unknown
      name: CWA (Taiwan)
      slug: central-weather-administration
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/central-weather-administration/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 1.3
      mcp:
        status: unknown
      name: LVGMC (Latvia)
      slug: lvgmc
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/lvgmc/
    - agent_band: null
      agent_readiness: null
      apps:
      - Breezy Weather
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: KNMI
      slug: knmi
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Breezy Weather
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Recosante
      slug: recosante
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - wttr.in
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: World Weather Online
      slug: worldweatheronline
      sources:
      - https://github.com/chubin/wttr.in/tree/master/internal/weather
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Carrot Weather
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Apple Weather (WeatherKit)
      slug: apple
      sources:
      - https://www.meetcarrot.com/weather/
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 38.5
      apps:
      - Windy
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: none
      name: ECMWF
      slug: ecmwf
      sources:
      - https://community.windy.com/topic/12/what-source-of-weather-data-windy-use
      status: profiled
      tags:
      - Company
      - Forecasting
      - Meteorology
      - Weather
      tier: declared
      url: /providers/ecmwf/
    - agent_band: agent-aware
      agent_readiness: 15.6
      apps:
      - Windy
      band: emerging
      in_catalog: true
      kin_score: 19.5
      mcp:
        status: none
      name: Meteoblue (NEMS)
      slug: meteoblue
      sources:
      - https://community.windy.com/topic/12/what-source-of-weather-data-windy-use
      status: profiled
      tags:
      - Climate
      - Data
      - Forecast
      - Weather
      tier: declared
      url: /providers/meteoblue/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Carrot Weather
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        status: unknown
      name: Foreca
      slug: foreca
      sources:
      - https://www.meetcarrot.com/weather/
      status: profiled
      tags:
      - Public APIs
      - Weather
      tier: declared
      url: /providers/foreca/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Windy
      band: minimal
      in_catalog: true
      kin_score: 3.4
      mcp:
        status: none
      name: DWD (ICON-EU)
      slug: deutscher-wetterdienst
      sources:
      - https://community.windy.com/topic/12/what-source-of-weather-data-windy-use
      status: profiled
      tags:
      - Geospatial
      - OGC
      - WFS
      - WMS
      tier: declared
      url: /providers/deutscher-wetterdienst/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10.10
      key: AE-230.10.10
      name: Personal Weather Station Networks
      url: /capabilities/weather-environment/
      via_parent: Weather & Environment
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.2
      apps:
      - WeeWX
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp: *id001
      name: Met Office WOW
      slug: met-office
      sources:
      - https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/met-office/
    - agent_band: agent-aware
      agent_readiness: 25.5
      apps:
      - WeeWX
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        status: none
      name: Weather Underground
      slug: wunderground
      sources:
      - https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
      status: profiled
      tags:
      - Hyperlocal
      - Observations
      - Personal Weather Stations
      - Weather
      tier: observed
      url: /providers/wunderground/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - WeeWX
      band: minimal
      in_catalog: true
      kin_score: 10.7
      mcp:
        status: none
      name: AWEKAS
      slug: awekas
      sources:
      - https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
      status: profiled
      tags:
      - Private Weather Stations
      - Weather App
      - Weather Data
      - Weather Map
      tier: observed
      url: /providers/awekas/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - WeeWX
      band: minimal
      in_catalog: true
      kin_score: 8.9
      mcp:
        status: unknown
      name: PWSweather
      slug: pwsweather
      sources:
      - https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
      status: profiled
      tags:
      - Company
      - Data
      - Visualization
      - Weather
      tier: observed
      url: /providers/pwsweather/
    - agent_band: agent-aware
      agent_readiness: 5.4
      apps:
      - WeeWX
      band: minimal
      in_catalog: true
      kin_score: 8.3
      mcp:
        status: unknown
      name: RMI Belgium WOW-BE
      slug: royal-meteorological-institute-belgium
      sources:
      - https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
      status: profiled
      tags:
      - Belgium
      - Climate
      - Meteorology
      - Weather
      tier: observed
      url: /providers/royal-meteorological-institute-belgium/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - WeeWX
      band: minimal
      in_catalog: true
      kin_score: 4.3
      mcp:
        status: unknown
      name: Citizen Weather Observer Program
      slug: cwop
      sources:
      - https://github.com/weewx/weewx/blob/master/src/weewx/restx.py
      status: profiled
      tags:
      - Citizen Science
      - Data Collection
      - PublicPrivatePartnership
      - Weather
      tier: observed
      url: /providers/cwop/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Breezy Weather
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: unknown
      name: IP.SB
      slug: ip-sb
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Company
      - DNS
      - GeoIP
      - IP
      tier: observed
      url: /providers/ip-sb/
    - agent_band: agent-aware
      agent_readiness: 6.0
      apps:
      - Breezy Weather
      band: emerging
      in_catalog: true
      kin_score: 18.5
      mcp:
        source: https://github.com/baidu-maps/mcp
        status: verified
      name: Baidu IP location
      slug: baidu
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Machine Learning
      - Technology
      tier: observed
      url: /providers/baidu/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.20
      key: AE-120.10.20
      name: Reverse Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.9
      apps:
      - Breezy Weather
      band: developing
      in_catalog: true
      kin_score: 42.4
      mcp: &id003
        status: none
      name: Nominatim
      slug: nominatim
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags: &id004
      - Geocoding
      - Location Services
      - Maps
      - OpenStreetMap
      tier: observed
      url: /providers/nominatim/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 1.3
      mcp:
        status: unknown
      name: NLSC (Taiwan)
      slug: nlsc
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/nlsc/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Breezy Weather
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        status: none
      name: GeoNames
      slug: geonames
      sources:
      - https://github.com/breezy-weather/breezy-weather/tree/main/app/src/main/java/org/breezyweather/sources
      status: profiled
      tags:
      - Geocoding
      - Public APIs
      tier: observed
      url: /providers/geonames/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.9
      apps:
      - wttr.in
      band: developing
      in_catalog: true
      kin_score: 42.4
      mcp: *id003
      name: Nominatim
      slug: nominatim
      sources:
      - https://github.com/chubin/wttr.in/tree/master/internal/location
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/nominatim/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - wttr.in
      band: minimal
      in_catalog: true
      kin_score: 7.9
      mcp:
        source: https://github.com/OpenCageData/opencage-geocoding-mcp
        status: verified
      name: OpenCage
      slug: opencage
      sources:
      - https://github.com/chubin/wttr.in/tree/master/internal/location
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Public APIs
      tier: observed
      url: /providers/opencage/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - wttr.in
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        status: none
      name: LocationIQ
      slug: locationiq
      sources:
      - https://github.com/chubin/wttr.in/tree/master/internal/location
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Public APIs
      tier: observed
      url: /providers/locationiq/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.9
      apps:
      - wttr.in
      band: thin
      in_catalog: true
      kin_score: 33.3
      mcp:
        status: none
      name: MaxMind GeoLite2
      slug: maxmind
      sources:
      - https://github.com/chubin/wttr.in/tree/master/internal/ip
      status: profiled
      tags:
      - Fraud Prevention
      - Geolocation
      - IP Intelligence
      - Risk Scoring
      tier: observed
      url: /providers/maxmind/
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.0
      apps:
      - AccuWeather
      band: strong
      in_catalog: true
      kin_score: 61.5
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.accuweather.android/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - Windy
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.windyty.android/latest/
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
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - AccuWeather
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics / Crashlytics
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.accuweather.android/latest/
      status: profiled
      tags:
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - AccuWeather
      band: thin
      in_catalog: true
      kin_score: 27.9
      mcp:
        source: https://github.com/urbanairship/agent-tools
        status: verified
      name: Airship (Urbanairship)
      slug: airship
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.accuweather.android/latest/
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
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Windy
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: none
      name: Facebook Analytics / Login / Share
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.windyty.android/latest/
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
  coverage_pct: 95.9
  declared_only: 5
  distinct_providers: 74
  in_catalog: 71
  mcp:
    documented: 1
    none: 27
    unchecked: 3
    verified: 6
  mcp_verified: 6
  mean_kin_score: 18.0
  observed: 69
  queued: 3
  reference_apps: 7
title: 'Weather & Environmental Alerts: application blueprint'
---
