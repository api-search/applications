---
access: understanding
agent_layer: []
apps:
- anchor: opencats
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: dependency manifest
    url: https://github.com/opencats/OpenCATS/blob/master/composer.json
  - route: source code
    url: https://github.com/opencats/OpenCATS/blob/master/config.php
  - route: source code
    url: https://github.com/opencats/OpenCATS/tree/master/modules/xml/xml_templates
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Indeed
    provider: indeed
    says: ships the Indeed SDK or integration code
    source: https://github.com/opencats/OpenCATS/tree/master/modules/xml/xml_templates
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: SimplyHired
    provider: simplyhired
    says: ships the SimplyHired SDK or integration code
    source: https://github.com/opencats/OpenCATS/tree/master/modules/xml/xml_templates
    tier: observed
  kind: self-hosted
  name: OpenCATS
  page: /applications/recruiting-ats/opencats/
  slug: opencats
  url: https://github.com/opencats/OpenCATS
- anchor: horilla-(recruitment)
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: source code
    url: https://github.com/horilla-opensource/horilla/blob/master/recruitment/models.py
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: LinkedIn
    provider: linkedin
    says: ships the LinkedIn SDK or integration code
    source: https://github.com/horilla-opensource/horilla/blob/master/recruitment/models.py
    tier: observed
  kind: self-hosted
  name: Horilla (Recruitment)
  page: /applications/recruiting-ats/horilla-recruitment/
  slug: horilla-recruitment
  url: https://github.com/horilla-opensource/horilla
- anchor: greenhouse
  counts:
    declared: 5
    observed: 0
  evidence:
  - route: integrations page
    url: https://integrations.greenhouse.com/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: ChartHop
    provider: charthop
    says: lists ChartHop as an integration
    source: https://integrations.greenhouse.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Checkr
    provider: checkr
    says: lists Checkr as an integration
    source: https://integrations.greenhouse.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Criteria Corp
    provider: criteria-corp
    says: lists Criteria Corp as an integration
    source: https://integrations.greenhouse.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Deel
    provider: deel-com
    says: lists Deel as an integration
    source: https://integrations.greenhouse.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Paylocity (Texting)
    provider: paylocity
    says: lists Paylocity (Texting) as an integration
    source: https://integrations.greenhouse.com/
    tier: declared
  kind: commercial
  name: Greenhouse
  page: /applications/recruiting-ats/greenhouse/
  slug: greenhouse
  url: https://www.greenhouse.com/
- anchor: lever
  counts:
    declared: 7
    observed: 0
  evidence:
  - route: integrations page
    url: https://marketplace.lever.co/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: ADP
    provider: adp
    says: lists ADP as an integration
    source: https://marketplace.lever.co/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: BambooHR
    provider: bamboohr
    says: lists BambooHR as an integration
    source: https://marketplace.lever.co/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: HiBob
    provider: bob
    says: lists HiBob as an integration
    source: https://marketplace.lever.co/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Indeed
    provider: indeed
    says: lists Indeed as an integration
    source: https://marketplace.lever.co/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Justworks
    provider: justworks
    says: lists Justworks as an integration
    source: https://marketplace.lever.co/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: LinkedIn
    provider: linkedin
    says: lists LinkedIn as an integration
    source: https://marketplace.lever.co/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Verified First
    provider: verified-first
    says: lists Verified First as an integration
    source: https://marketplace.lever.co/
    tier: declared
  kind: commercial
  name: Lever
  page: /applications/recruiting-ats/lever/
  slug: lever
  url: https://www.lever.co/
- anchor: ashby
  counts:
    declared: 3
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.ashbyhq.com/integrations
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
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://www.ashbyhq.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Workday
    provider: workday
    says: lists Workday as an integration
    source: https://www.ashbyhq.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://www.ashbyhq.com/integrations
    tier: declared
  kind: commercial
  name: Ashby
  page: /applications/recruiting-ats/ashby/
  slug: ashby
  url: https://www.ashbyhq.com/
- anchor: teamtailor
  counts:
    declared: 63
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.teamtailor.com/en/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    credit: null
    layer: domain
    name: Adobe Acrobat Sign
    provider: adobe
    says: lists Adobe Acrobat Sign as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: ADP
    provider: adp
    says: lists ADP as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Adzuna
    provider: adzuna
    says: lists Adzuna as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: AFAS
    provider: afas
    says: lists AFAS as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: BambooHR
    provider: bamboohr
    says: lists BambooHR as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Careerjet
    provider: careerjet
    says: lists Careerjet as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Certn
    provider: certn
    says: lists Certn as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Charlie HR
    provider: charliehr
    says: lists Charlie HR as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Checkr
    provider: checkr
    says: lists Checkr as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: CoderPad
    provider: coderpad
    says: lists CoderPad as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Codility
    provider: codility
    says: lists Codility as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Criteria Corp
    provider: criteria-corp
    says: lists Criteria Corp as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Crosschq
    provider: crosschq
    says: lists Crosschq as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Darwinbox
    provider: darwinbox
    says: lists Darwinbox as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Dayforce
    provider: dayforce
    says: lists Dayforce as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Deel
    provider: deel-com
    says: lists Deel as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Deputy
    provider: deputy
    says: lists Deputy as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    credit: null
    layer: domain
    name: DocuSign
    provider: docusign
    says: lists DocuSign as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    credit: null
    layer: domain
    name: Dropbox Sign
    provider: hellosign
    says: lists Dropbox Sign as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Experian
    provider: experian
    says: lists Experian as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: common
    name: Facebook
    provider: facebook
    says: lists Facebook as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Factorial
    provider: factorial-hr
    says: lists Factorial as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Glassdoor
    provider: glassdoor
    says: lists Glassdoor as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: common
    name: Google Ads
    provider: google-ads
    says: lists Google Ads as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gusto
    provider: gusto
    says: lists Gusto as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: HackerRank
    provider: hackerrank
    says: lists HackerRank as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: HiBob
    provider: bob
    says: lists HiBob as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: hireEZ
    provider: hireez
    says: lists hireEZ as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Humaans
    provider: humaans-io
    says: lists Humaans as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Indeed
    provider: indeed
    says: lists Indeed as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: common
    name: Instagram
    provider: instagram
    says: lists Instagram as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Jooble
    provider: jooble
    says: lists Jooble as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: LinkedIn
    provider: linkedin
    says: lists LinkedIn as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Monster
    provider: monster
    says: lists Monster as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Naukri
    provider: naukri
    says: lists Naukri as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Nmbrs
    provider: nmbrs
    says: lists Nmbrs as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    credit: null
    layer: domain
    name: Oneflow
    provider: oneflow
    says: lists Oneflow as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Oyster HR
    provider: oysterhr
    says: lists Oyster HR as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    credit: null
    layer: domain
    name: PandaDoc
    provider: pandadoc
    says: lists PandaDoc as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: PayFit
    provider: payfit
    says: lists PayFit as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Paylocity
    provider: paylocity
    says: lists Paylocity as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    credit: null
    layer: domain
    name: Penneo
    provider: penneo
    says: lists Penneo as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Personio
    provider: personio
    says: lists Personio as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Reed
    provider: reed
    says: lists Reed as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: common
    name: Ringover
    provider: ringover
    says: lists Ringover as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Rippling
    provider: rippling
    says: lists Rippling as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: SAP SuccessFactors
    provider: sap-successfactors
    says: lists SAP SuccessFactors as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    credit: null
    layer: domain
    name: Scrive
    provider: scrive
    says: lists Scrive as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: SD Worx
    provider: sd-worx
    says: lists SD Worx as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Sesame HR
    provider: sesame-hr
    says: lists Sesame HR as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: SHL
    provider: shl
    says: lists SHL as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    credit: null
    layer: domain
    name: Signeasy
    provider: signeasy
    says: lists Signeasy as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: common
    name: Snapchat
    provider: snapchat
    says: lists Snapchat as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Spark Hire
    provider: spark-hire
    says: lists Spark Hire as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Talent.com
    provider: talent-com
    says: lists Talent.com as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: TestGorilla
    provider: testgorilla
    says: lists TestGorilla as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: The Predictive Index
    provider: the-predictive-index
    says: lists The Predictive Index as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: common
    name: TikTok
    provider: tiktok
    says: lists TikTok as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Totaljobs
    provider: totaljobs
    says: lists Totaljobs as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: TriNet
    provider: trinet-group
    says: lists TriNet as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Upsales
    provider: upsales
    says: lists Upsales as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: Verified First
    provider: verified-first
    says: lists Verified First as an integration
    source: https://www.teamtailor.com/en/integrations/
    tier: declared
  kind: commercial
  name: Teamtailor
  page: /applications/recruiting-ats/teamtailor/
  slug: teamtailor
  url: https://www.teamtailor.com/
- anchor: recruitee
  counts:
    declared: 7
    observed: 0
  evidence:
  - route: integrations page
    url: https://recruitee.com/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: AFAS
    provider: afas
    says: lists AFAS as an integration
    source: https://recruitee.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: BambooHR
    provider: bamboohr
    says: lists BambooHR as an integration
    source: https://recruitee.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    credit: null
    layer: domain
    name: LinkedIn
    provider: linkedin
    says: lists LinkedIn as an integration
    source: https://recruitee.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Make
    provider: make
    says: lists Make as an integration
    source: https://recruitee.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: SAP SuccessFactors
    provider: sap-successfactors
    says: lists SAP SuccessFactors as an integration
    source: https://recruitee.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: Workday
    provider: workday
    says: lists Workday as an integration
    source: https://recruitee.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://recruitee.com/integrations
    tier: declared
  kind: commercial
  name: Recruitee
  page: /applications/recruiting-ats/recruitee/
  slug: recruitee
  url: https://recruitee.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: recruiting-ats
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Human Resources Management (HRM)
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#human-resources-management-hrm
- category: Human Resources
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: HR Talent & Recruitment
  store: zapier
  url: https://zapier.com/apps
name: Recruiting & Applicant Tracking
needs:
- capability:
    attribution: Turbo EA
    id: BC-300.10
    key: talent-acquisition-management
    name: Talent Acquisition Management
    url: /capabilities/talent-acquisition-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: job distribution to boards, sourcing, background screening and skills assessment hang off the ATS; nearest BC node for all four
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  fit: exact
  layer: domain
  why: hired candidates hand off to the HRIS/payroll system
- capability:
    attribution: Turbo EA
    id: BC-150.10.30
    key: BC-150.10.30
    name: Contract Execution Management
    url: /capabilities/contract-management/
    via_parent: Contract Management
  fit: exact
  layer: domain
  why: offer letters signed through e-signature vendors; nearest BC node
- capability:
    attribution: Turbo EA
    id: BC-400.60.30
    key: BC-400.60.30
    name: Paid Media Management
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: exact
  layer: common
  why: paid job advertising on social and search ad networks; nearest
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: common
  why: CRM sync (agency / candidate-relationship use)
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: Zapier / Make connectors
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: exact
  layer: common
  why: hiring notifications into Slack
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: candidate texting
- capability:
    attribution: Turbo EA
    id: BC-300.10.20
    key: BC-300.10.20
    name: Candidate Screening and Selection
    url: /capabilities/talent-acquisition-management/
    via_parent: Talent Acquisition Management
  fit: exact
  layer: domain
  why: asynchronous video interviewing; nearest (one-way recorded video is not live calling)
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.10
    key: AE-150.50.10
    name: Programmable Voice
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  fit: nearest
  layer: common
  why: cloud telephony for recruiter calls; nearest
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.3
      apps:
      - Lever
      - Recruitee
      - Teamtailor
      band: developing
      in_catalog: true
      kin_score: 40.7
      mcp:
        source: https://documentation.bamboohr.com/docs/mcp-server
        status: verified
      name: BambooHR
      slug: bamboohr
      sources:
      - https://marketplace.lever.co/
      - https://recruitee.com/integrations
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - HRIS
      - Human Resources
      - Payroll
      - Time Tracking
      tier: declared
      url: /providers/bamboohr/
    - agent_band: agent-native
      agent_readiness: 52.0
      apps:
      - Greenhouse
      - Teamtailor
      band: strong
      in_catalog: true
      kin_score: 60.9
      mcp:
        source: https://developer.deel.com/docs/mcp
        status: documented
      name: Deel
      slug: deel-com
      sources:
      - https://integrations.greenhouse.com/
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Employer of Record
      - Global Payroll
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/deel-com/
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Ashby
      - Recruitee
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        status: none
      name: Workday
      slug: workday
      sources:
      - https://recruitee.com/integrations
      - https://www.ashbyhq.com/integrations
      status: profiled
      tags:
      - Cloud Computing
      - Enterprise Software
      - Financial Management
      - HCM
      tier: declared
      url: /providers/workday/
    - agent_band: agent-ready
      agent_readiness: 39.8
      apps:
      - Lever
      - Teamtailor
      band: developing
      in_catalog: true
      kin_score: 45.6
      mcp:
        status: none
      name: ADP
      slug: adp
      sources:
      - https://marketplace.lever.co/
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Benefits
      - HCM
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/adp/
    - agent_band: agent-aware
      agent_readiness: 19.3
      apps:
      - Lever
      - Teamtailor
      band: thin
      in_catalog: true
      kin_score: 29.3
      mcp:
        source: https://apidocs.hibob.com/docs/hibob-mcp-server
        status: verified
      name: HiBob
      slug: bob
      sources:
      - https://marketplace.lever.co/
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Employee Management
      - HRIS
      - Human Resources
      - Time Off
      tier: declared
      url: /providers/bob/
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Recruitee
      - Teamtailor
      band: thin
      in_catalog: true
      kin_score: 26.2
      mcp:
        status: none
      name: SAP SuccessFactors
      slug: sap-successfactors
      sources:
      - https://recruitee.com/integrations
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - HCM
      - Human Resources
      - Payroll
      - Talent Management
      tier: declared
      url: /providers/sap-successfactors/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Recruitee
      - Teamtailor
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        status: unknown
      name: AFAS
      slug: afas
      sources:
      - https://recruitee.com/integrations
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Company
      - ERP
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/afas/
    - agent_band: agent-ready
      agent_readiness: 30.3
      apps:
      - Teamtailor
      band: exemplar
      in_catalog: true
      kin_score: 67.1
      mcp:
        status: none
      name: Deputy
      slug: deputy
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Employee Scheduling
      - Time and Attendance
      - Timesheets
      - Workforce Management
      tier: declared
      url: /providers/deputy/
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Greenhouse
      band: strong
      in_catalog: true
      kin_score: 59.9
      mcp:
        status: none
      name: ChartHop
      slug: charthop
      sources:
      - https://integrations.greenhouse.com/
      status: profiled
      tags:
      - Company
      - HRIS
      - Human Resources
      - People Analytics
      tier: declared
      url: /providers/charthop/
    - agent_band: agent-ready
      agent_readiness: 47.5
      apps:
      - Teamtailor
      band: developing
      in_catalog: true
      kin_score: 53.9
      mcp:
        status: none
      name: Factorial
      slug: factorial-hr
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Human Resources
      - Payroll
      - Time Off
      - Time Tracking
      tier: declared
      url: /providers/factorial-hr/
    - agent_band: agent-ready
      agent_readiness: 44.3
      apps:
      - Teamtailor
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        status: none
      name: Humaans
      slug: humaans-io
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - HRIS
      - Human Resources
      - People Analytics
      - People Operations
      tier: declared
      url: /providers/humaans-io/
    - agent_band: agent-ready
      agent_readiness: 44.9
      apps:
      - Lever
      band: developing
      in_catalog: true
      kin_score: 45.7
      mcp:
        status: none
      name: Justworks
      slug: justworks
      sources:
      - https://marketplace.lever.co/
      status: profiled
      tags:
      - Benefits
      - Human Resources
      - PEO
      - Payroll
      tier: declared
      url: /providers/justworks/
    - agent_band: agent-ready
      agent_readiness: 31.7
      apps:
      - Teamtailor
      band: developing
      in_catalog: true
      kin_score: 44.9
      mcp:
        status: none
      name: Gusto
      slug: gusto
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Benefits
      - Enterprise Software
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/gusto/
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Teamtailor
      band: thin
      in_catalog: true
      kin_score: 32.8
      mcp:
        status: none
      name: Rippling
      slug: rippling
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - HCM
      - Human Resources
      - IT
      - Payroll
      tier: declared
      url: /providers/rippling/
    - agent_band: agent-aware
      agent_readiness: 23.4
      apps:
      - Teamtailor
      band: thin
      in_catalog: true
      kin_score: 32.4
      mcp: &id001
        status: none
      name: Paylocity
      slug: paylocity
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags: &id002
      - Benefits
      - HCM
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/paylocity/
    - agent_band: agent-ready
      agent_readiness: 34.3
      apps:
      - Teamtailor
      band: thin
      in_catalog: true
      kin_score: 30.5
      mcp:
        status: none
      name: Charlie HR
      slug: charliehr
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - HRIS
      - Human Resources
      - Leave
      - People
      tier: declared
      url: /providers/charliehr/
    - agent_band: agent-ready
      agent_readiness: 41.0
      apps:
      - Teamtailor
      band: thin
      in_catalog: true
      kin_score: 29.8
      mcp:
        status: none
      name: Personio
      slug: personio
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Applicant Tracking
      - HRIS
      - Human Resources
      - Recruiting
      tier: declared
      url: /providers/personio/
    - agent_band: agent-ready
      agent_readiness: 28.6
      apps:
      - Teamtailor
      band: thin
      in_catalog: true
      kin_score: 29.3
      mcp:
        status: none
      name: Nmbrs
      slug: nmbrs
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Employee Management
      - HRIS
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/nmbrs/
    - agent_band: agent-aware
      agent_readiness: 22.3
      apps:
      - Teamtailor
      band: thin
      in_catalog: true
      kin_score: 28.7
      mcp:
        status: none
      name: PayFit
      slug: payfit
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Europe Payroll
      - Human Resources
      - Payroll
      - Time and Attendance
      tier: declared
      url: /providers/payfit/
    - agent_band: agent-ready
      agent_readiness: 47.3
      apps:
      - Teamtailor
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        status: none
      name: Sesame HR
      slug: sesame-hr
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - HRIS
      - Human Resources
      - Time Tracking
      - Workforce Management
      tier: declared
      url: /providers/sesame-hr/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Teamtailor
      band: emerging
      in_catalog: true
      kin_score: 20.1
      mcp:
        status: none
      name: Dayforce
      slug: dayforce
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Company
      - HCM
      - Payroll
      - Workforce Management
      tier: declared
      url: /providers/dayforce/
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Teamtailor
      band: emerging
      in_catalog: true
      kin_score: 18.0
      mcp:
        status: none
      name: TriNet
      slug: trinet-group
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Benefits
      - Compliance
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/trinet-group/
    - agent_band: human-only
      agent_readiness: 2.8
      apps:
      - Teamtailor
      band: emerging
      in_catalog: true
      kin_score: 17.7
      mcp:
        status: none
      name: SD Worx
      slug: sd-worx
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Europe
      - Human Resources
      - Payroll
      - Workforce Management
      tier: declared
      url: /providers/sd-worx/
    - agent_band: agent-aware
      agent_readiness: 12.6
      apps:
      - Teamtailor
      band: emerging
      in_catalog: true
      kin_score: 13.1
      mcp:
        source: https://github.com/darwinbox/darwinbox-mcp
        status: verified
      name: Darwinbox
      slug: darwinbox
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - HRMS
      - Human Resources
      - Payroll
      - Recruiting
      tier: declared
      url: /providers/darwinbox/
    - agent_band: null
      agent_readiness: null
      apps:
      - Teamtailor
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Oyster HR
      slug: oysterhr
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-300.10.10
      key: BC-300.10.10
      name: Workforce Sourcing
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Horilla (Recruitment)
      - Lever
      - Recruitee
      - Teamtailor
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp:
        status: none
      name: LinkedIn
      slug: linkedin
      sources:
      - https://github.com/horilla-opensource/horilla/blob/master/recruitment/models.py
      - https://marketplace.lever.co/
      - https://recruitee.com/integrations
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: observed
      url: /providers/linkedin/
    - agent_band: agent-ready
      agent_readiness: 29.0
      apps:
      - Lever
      - OpenCATS
      - Teamtailor
      band: developing
      in_catalog: true
      kin_score: 44.6
      mcp:
        status: none
      name: Indeed
      slug: indeed
      sources:
      - https://github.com/opencats/OpenCATS/tree/master/modules/xml/xml_templates
      - https://marketplace.lever.co/
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Careers
      - Employment
      - Hiring
      - Job Search
      tier: observed
      url: /providers/indeed/
    - agent_band: null
      agent_readiness: null
      apps:
      - OpenCATS
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: SimplyHired
      slug: simplyhired
      sources:
      - https://github.com/opencats/OpenCATS/tree/master/modules/xml/xml_templates
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Teamtailor
      band: emerging
      in_catalog: true
      kin_score: 14.7
      mcp:
        status: unknown
      name: Talent.com
      slug: talent-com
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Company
      - Employment
      - Job Search
      - Recruiting
      tier: declared
      url: /providers/talent-com/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Teamtailor
      band: emerging
      in_catalog: true
      kin_score: 11.4
      mcp:
        status: none
      name: Glassdoor
      slug: glassdoor
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Employer Reviews
      - Job Search
      - Recruiting
      - Salaries
      tier: declared
      url: /providers/glassdoor/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Teamtailor
      band: minimal
      in_catalog: true
      kin_score: 5.0
      mcp:
        status: none
      name: Jooble
      slug: jooble
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Job
      - Job Board
      - Public APIs
      tier: declared
      url: /providers/jooble/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Teamtailor
      band: minimal
      in_catalog: true
      kin_score: 5.0
      mcp:
        status: none
      name: Reed
      slug: reed
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Job
      - Job Board
      - Public APIs
      tier: declared
      url: /providers/reed/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Teamtailor
      band: minimal
      in_catalog: true
      kin_score: 4.9
      mcp:
        status: unknown
      name: Naukri
      slug: naukri
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Careers
      - Company
      - Job
      - Recruiting
      tier: declared
      url: /providers/naukri/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Teamtailor
      band: minimal
      in_catalog: true
      kin_score: 4.3
      mcp:
        status: none
      name: Adzuna
      slug: adzuna
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Job
      - Job Board
      - Public APIs
      tier: declared
      url: /providers/adzuna/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Teamtailor
      band: minimal
      in_catalog: true
      kin_score: 4.3
      mcp:
        status: none
      name: Careerjet
      slug: careerjet
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Job
      - Job Board
      - Public APIs
      tier: declared
      url: /providers/careerjet/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Teamtailor
      band: minimal
      in_catalog: true
      kin_score: 2.4
      mcp:
        status: unknown
      name: Monster
      slug: monster
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Company
      - Employment
      - Recruiting
      - Technology
      tier: declared
      url: /providers/monster/
    - agent_band: null
      agent_readiness: null
      apps:
      - Teamtailor
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: hireEZ
      slug: hireez
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Teamtailor
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Totaljobs
      slug: totaljobs
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-300.10.20
      key: BC-300.10.20
      name: Candidate Screening and Selection
      url: /capabilities/talent-acquisition-management/
      via_parent: Talent Acquisition Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.8
      apps:
      - Greenhouse
      - Teamtailor
      band: thin
      in_catalog: true
      kin_score: 32.4
      mcp:
        status: none
      name: Checkr
      slug: checkr
      sources:
      - https://integrations.greenhouse.com/
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Background Checks
      - Compliance
      - Employment Screening
      - Human Resources
      tier: declared
      url: /providers/checkr/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Greenhouse
      - Teamtailor
      band: thin
      in_catalog: true
      kin_score: 27.0
      mcp:
        status: unknown
      name: Criteria Corp
      slug: criteria-corp
      sources:
      - https://integrations.greenhouse.com/
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Assessment
      - Pre-Employment Testing
      - Talent Development
      - Video Interviewing
      tier: declared
      url: /providers/criteria-corp/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Lever
      - Teamtailor
      band: emerging
      in_catalog: true
      kin_score: 24.7
      mcp:
        status: none
      name: Verified First
      slug: verified-first
      sources:
      - https://marketplace.lever.co/
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Background Checks
      - Company
      - Screening
      - Verification
      tier: declared
      url: /providers/verified-first/
    - agent_band: agent-ready
      agent_readiness: 29.6
      apps:
      - Teamtailor
      band: exemplar
      in_catalog: true
      kin_score: 68.4
      mcp:
        status: none
      name: CoderPad
      slug: coderpad
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Hiring
      - Technical Assessment
      tier: declared
      url: /providers/coderpad/
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - Teamtailor
      band: strong
      in_catalog: true
      kin_score: 60.9
      mcp:
        status: none
      name: Experian
      slug: experian
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Company
      - Credit Bureau
      - Credit Reporting
      - Identity Verification
      tier: declared
      url: /providers/experian/
    - agent_band: agent-aware
      agent_readiness: 27.4
      apps:
      - Teamtailor
      band: developing
      in_catalog: true
      kin_score: 52.4
      mcp:
        status: none
      name: The Predictive Index
      slug: the-predictive-index
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Assessment
      - Company
      - Human Resources
      - Talent Optimization
      tier: declared
      url: /providers/the-predictive-index/
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Teamtailor
      band: thin
      in_catalog: true
      kin_score: 26.2
      mcp:
        status: none
      name: Certn
      slug: certn
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Background Checks
      - Criminal Record Check
      - Identity Verification
      - Screening
      tier: declared
      url: /providers/certn/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Teamtailor
      band: emerging
      in_catalog: true
      kin_score: 25.9
      mcp:
        status: none
      name: HackerRank
      slug: hackerrank
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Coding Assessment
      - Company
      - Developer Skills
      - Technical Hiring
      tier: declared
      url: /providers/hackerrank/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Teamtailor
      band: emerging
      in_catalog: true
      kin_score: 25.3
      mcp:
        status: none
      name: Codility
      slug: codility
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Coding Assessment
      - Company
      - Developer Hiring
      - Technical Assessment
      tier: declared
      url: /providers/codility/
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Teamtailor
      band: emerging
      in_catalog: true
      kin_score: 23.2
      mcp:
        status: none
      name: Spark Hire
      slug: spark-hire
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Hiring
      - Human Resources
      - Recruiting
      - Video Interviewing
      tier: declared
      url: /providers/spark-hire/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Teamtailor
      band: emerging
      in_catalog: true
      kin_score: 20.5
      mcp:
        status: none
      name: TestGorilla
      slug: testgorilla
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Company
      - Hiring
      - Recruiting
      - Talent Assessment
      tier: declared
      url: /providers/testgorilla/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Teamtailor
      band: emerging
      in_catalog: true
      kin_score: 15.3
      mcp:
        status: unknown
      name: SHL
      slug: shl
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Company
      - HR Technology
      - People Science
      - Talent Assessment
      tier: declared
      url: /providers/shl/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Teamtailor
      band: minimal
      in_catalog: true
      kin_score: 10.6
      mcp:
        status: none
      name: Crosschq
      slug: crosschq
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Company
      - Human Resources
      - Recruiting
      - Talent Intelligence
      tier: declared
      url: /providers/crosschq/
  - capability:
      attribution: Turbo EA
      id: BC-150.10.30
      key: BC-150.10.30
      name: Contract Execution Management
      url: /capabilities/contract-management/
      via_parent: Contract Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.9
      apps:
      - Teamtailor
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://github.com/adobe/cq-quickstart-mcp-server
        status: verified
      name: Adobe Acrobat Sign
      slug: adobe
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Adobe
      - Analytics
      - E-Signature
      - Fortune 1000
      tier: declared
      url: /providers/adobe/
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Teamtailor
      band: exemplar
      in_catalog: true
      kin_score: 71.5
      mcp:
        source: https://www.docusign.com/products/mcp
        status: documented
      name: DocuSign
      slug: docusign
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Agreements
      - Contracts
      - DocuSign
      - E-Signature
      tier: declared
      url: /providers/docusign/
    - agent_band: agent-ready
      agent_readiness: 48.1
      apps:
      - Teamtailor
      band: exemplar
      in_catalog: true
      kin_score: 71.1
      mcp:
        status: none
      name: Dropbox Sign
      slug: hellosign
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Company
      - Digital Agreements
      - Documents
      - E-Signature
      tier: declared
      url: /providers/hellosign/
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - Teamtailor
      band: strong
      in_catalog: true
      kin_score: 65.6
      mcp:
        status: none
      name: Penneo
      slug: penneo
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Company
      - Compliance
      - Digital Signing
      - eIDAS
      tier: declared
      url: /providers/penneo/
    - agent_band: agent-ready
      agent_readiness: 39.0
      apps:
      - Teamtailor
      band: developing
      in_catalog: true
      kin_score: 43.0
      mcp:
        source: https://github.com/pandadoc/pandadoc-mcpb
        status: verified
      name: PandaDoc
      slug: pandadoc
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Document Automation
      - Document Generation
      - Document Management
      - E-Signature
      tier: declared
      url: /providers/pandadoc/
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Teamtailor
      band: thin
      in_catalog: true
      kin_score: 31.1
      mcp:
        status: none
      name: Oneflow
      slug: oneflow
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Contract Lifecycle Management
      - Contract Management
      - Digital Contracts
      - E-Signature
      tier: declared
      url: /providers/oneflow/
    - agent_band: agent-ready
      agent_readiness: 44.7
      apps:
      - Teamtailor
      band: thin
      in_catalog: true
      kin_score: 28.6
      mcp:
        source: https://github.com/scrive/mcp
        status: verified
      name: Scrive
      slug: scrive
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - BankID
      - Digital Identity
      - E-Signature
      - eID
      tier: declared
      url: /providers/scrive/
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - Teamtailor
      band: emerging
      in_catalog: true
      kin_score: 26.1
      mcp:
        status: none
      name: Signeasy
      slug: signeasy
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Contract Management
      - Documents
      - E-Signature
      - Embedded Signing
      tier: declared
      url: /providers/signeasy/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-400.60.30
      key: BC-400.60.30
      name: Paid Media Management
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.1
      apps:
      - Teamtailor
      band: exemplar
      in_catalog: true
      kin_score: 73.4
      mcp:
        source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
        status: verified
      name: Google Ads
      slug: google-ads
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Advertising
      - Campaign Management
      - Digital Advertising
      - Google
      tier: declared
      url: /providers/google-ads/
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
      - Teamtailor
      band: exemplar
      in_catalog: true
      kin_score: 67.8
      mcp:
        status: none
      name: Instagram
      slug: instagram
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Instagram
      - Meta
      - Photos
      - Social Media
      tier: declared
      url: /providers/instagram/
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Teamtailor
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Snapchat
      slug: snapchat
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Advertising
      - Augmented Reality
      - Marketing
      - Messaging
      tier: declared
      url: /providers/snapchat/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Teamtailor
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: declared
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Teamtailor
      band: developing
      in_catalog: true
      kin_score: 40.5
      mcp:
        status: none
      name: TikTok
      slug: tiktok
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Advertising
      - Commerce
      - Content
      - TikTok
      tier: declared
      url: /providers/tiktok/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Ashby
      - Recruitee
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://recruitee.com/integrations
      - https://www.ashbyhq.com/integrations
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Recruitee
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://recruitee.com/integrations
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Teamtailor
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - Teamtailor
      band: emerging
      in_catalog: true
      kin_score: 23.2
      mcp:
        status: none
      name: Upsales
      slug: upsales
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - CRM
      - Company
      - Sales
      tier: declared
      url: /providers/upsales/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.3
      apps:
      - Teamtailor
      band: strong
      in_catalog: true
      kin_score: 64.5
      mcp:
        status: none
      name: Ringover
      slug: ringover
      sources:
      - https://www.teamtailor.com/en/integrations/
      status: profiled
      tags:
      - Cloud
      - Collaboration
      - Communications
      - VoIP
      tier: declared
      url: /providers/ringover/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.4
      apps:
      - Greenhouse
      band: thin
      in_catalog: true
      kin_score: 32.4
      mcp: *id001
      name: Paylocity (Texting)
      slug: paylocity
      sources:
      - https://integrations.greenhouse.com/
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/paylocity/
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
      - Ashby
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://www.ashbyhq.com/integrations
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
  layer: common
summary:
  coverage_pct: 94.3
  declared_only: 67
  distinct_providers: 70
  in_catalog: 66
  mcp:
    documented: 2
    none: 47
    unchecked: 4
    verified: 11
  mcp_verified: 11
  mean_kin_score: 38.4
  observed: 3
  queued: 4
  reference_apps: 7
title: 'Recruiting & Applicant Tracking: application blueprint'
---
