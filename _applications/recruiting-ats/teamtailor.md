---
app: Teamtailor
app_slug: teamtailor
app_url: https://www.teamtailor.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-300.10.20
  key: BC-300.10.20
  layer: domain
  name: Candidate Screening and Selection
  providers:
  - Certn
  - Checkr
  - CoderPad
  - Codility
  - Criteria Corp
  - Crosschq
  - Experian
  - HackerRank
  - SHL
  - Spark Hire
  - TestGorilla
  - The Predictive Index
  - Verified First
  url: /capabilities/talent-acquisition-management/
  via_parent: Talent Acquisition Management
- attribution: Turbo EA
  id: BC-150.10.30
  key: BC-150.10.30
  layer: domain
  name: Contract Execution Management
  providers:
  - Adobe Acrobat Sign
  - DocuSign
  - Dropbox Sign
  - Oneflow
  - PandaDoc
  - Penneo
  - Scrive
  - Signeasy
  url: /capabilities/contract-management/
  via_parent: Contract Management
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: domain
  name: Human Capital Management
  providers:
  - ADP
  - AFAS
  - BambooHR
  - Charlie HR
  - Darwinbox
  - Dayforce
  - Deel
  - Deputy
  - Factorial
  - Gusto
  - HiBob
  - Humaans
  - Nmbrs
  - Oyster HR
  - PayFit
  - Paylocity
  - Personio
  - Rippling
  - SAP SuccessFactors
  - SD Worx
  - Sesame HR
  - TriNet
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300.10.10
  key: BC-300.10.10
  layer: domain
  name: Workforce Sourcing
  providers:
  - Adzuna
  - Careerjet
  - Glassdoor
  - hireEZ
  - Indeed
  - Jooble
  - LinkedIn
  - Monster
  - Naukri
  - Reed
  - Talent.com
  - Totaljobs
  url: /capabilities/talent-acquisition-management/
  via_parent: Talent Acquisition Management
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Upsales
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60.30
  key: BC-400.60.30
  layer: common
  name: Paid Media Management
  providers:
  - Facebook
  - Google Ads
  - Instagram
  - Snapchat
  - TikTok
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-150.50.10
  key: AE-150.50.10
  layer: common
  name: Programmable Voice
  providers:
  - Ringover
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
category:
  id: recruiting-ats
  name: Recruiting & Applicant Tracking
  url: /applications/recruiting-ats/
counts:
  declared: 63
  observed: 0
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 65.9
    band: exemplar
    in_catalog: true
    kin_score: 76.2
    mcp: &id001
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe
    status: profiled
    tags: &id002
    - Adobe
    - Analytics
    - E-Signature
    - Fortune 1000
    url: /providers/adobe/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.7
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id003
      status: none
    slug: adp
    status: profiled
    tags: &id004
    - Benefits
    - HCM
    - Human Resources
    - Payroll
    url: /providers/adp/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.2
    mcp: &id005
      status: none
    slug: adzuna
    status: profiled
    tags: &id006
    - Job
    - Job Board
    - Public APIs
    url: /providers/adzuna/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 8.5
    mcp: &id007
      status: unknown
    slug: afas
    status: profiled
    tags: &id008
    - Company
    - ERP
    - Human Resources
    - Payroll
    url: /providers/afas/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 40.9
    mcp: &id009
      source: https://documentation.bamboohr.com/docs/mcp-server
      status: verified
    slug: bamboohr
    status: profiled
    tags: &id010
    - HRIS
    - Human Resources
    - Payroll
    - Time Tracking
    url: /providers/bamboohr/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.2
    mcp: &id011
      status: none
    slug: careerjet
    status: profiled
    tags: &id012
    - Job
    - Job Board
    - Public APIs
    url: /providers/careerjet/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 26.5
    mcp: &id013
      status: none
    slug: certn
    status: profiled
    tags: &id014
    - Background Checks
    - Criminal Record Check
    - Identity Verification
    - Screening
    url: /providers/certn/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.8
    band: thin
    in_catalog: true
    kin_score: 31.0
    mcp: &id015
      status: none
    slug: charliehr
    status: profiled
    tags: &id016
    - HRIS
    - Human Resources
    - Leave
    - People
    url: /providers/charliehr/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 48.1
    band: thin
    in_catalog: true
    kin_score: 32.8
    mcp: &id017
      status: none
    slug: checkr
    status: profiled
    tags: &id018
    - Background Checks
    - Compliance
    - Employment Screening
    - Human Resources
    url: /providers/checkr/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.7
    band: strong
    in_catalog: true
    kin_score: 54.8
    mcp: &id019
      status: none
    slug: coderpad
    status: profiled
    tags: &id020
    - Artificial Intelligence
    - Company
    - Hiring
    - Technical Assessment
    url: /providers/coderpad/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 24.4
    mcp: &id021
      status: none
    slug: codility
    status: profiled
    tags: &id022
    - Coding Assessment
    - Company
    - Developer Hiring
    - Technical Assessment
    url: /providers/codility/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 16.4
    mcp: &id023
      status: unknown
    slug: criteria-corp
    status: profiled
    tags: &id024
    - Assessment
    - Pre-Employment Testing
    - Talent Development
    - Video Interviewing
    url: /providers/criteria-corp/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.8
    mcp: &id025
      status: none
    slug: crosschq
    status: profiled
    tags: &id026
    - Company
    - Human Resources
    - Recruiting
    - Talent Intelligence
    url: /providers/crosschq/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 12.9
    band: emerging
    in_catalog: true
    kin_score: 14.1
    mcp: &id027
      source: https://github.com/darwinbox/darwinbox-mcp
      status: verified
    slug: darwinbox
    status: profiled
    tags: &id028
    - HRMS
    - Human Resources
    - Payroll
    - Recruiting
    url: /providers/darwinbox/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 15.1
    band: emerging
    in_catalog: true
    kin_score: 13.6
    mcp: &id029
      status: none
    slug: dayforce
    status: profiled
    tags: &id030
    - Company
    - HCM
    - Payroll
    - Workforce Management
    url: /providers/dayforce/
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
  facts:
    agent_band: agent-native
    agent_readiness: 51.7
    band: strong
    in_catalog: true
    kin_score: 63.3
    mcp: &id031
      source: https://developer.deel.com/docs/mcp
      status: documented
    slug: deel-com
    status: profiled
    tags: &id032
    - Employer of Record
    - Global Payroll
    - Human Resources
    - Payroll
    url: /providers/deel-com/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.4
    band: strong
    in_catalog: true
    kin_score: 66.2
    mcp: &id033
      status: none
    slug: deputy
    status: profiled
    tags: &id034
    - Employee Scheduling
    - Time and Attendance
    - Timesheets
    - Workforce Management
    url: /providers/deputy/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id035
      source: https://www.docusign.com/products/mcp
      status: documented
    slug: docusign
    status: profiled
    tags: &id036
    - Agreements
    - Contracts
    - DocuSign
    - E-Signature
    url: /providers/docusign/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 48.8
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id037
      status: none
    slug: hellosign
    status: profiled
    tags: &id038
    - Company
    - Digital Agreements
    - Documents
    - E-Signature
    url: /providers/hellosign/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.2
    band: strong
    in_catalog: true
    kin_score: 60.0
    mcp: &id039
      status: none
    slug: experian
    status: profiled
    tags: &id040
    - Company
    - Credit Bureau
    - Credit Reporting
    - Identity Verification
    url: /providers/experian/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id041
      status: none
    slug: facebook
    status: profiled
    tags: &id042
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 48.5
    band: developing
    in_catalog: true
    kin_score: 53.8
    mcp: &id043
      status: none
    slug: factorial-hr
    status: profiled
    tags: &id044
    - Human Resources
    - Payroll
    - Time Off
    - Time Tracking
    url: /providers/factorial-hr/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 11.1
    mcp: &id045
      status: none
    slug: glassdoor
    status: profiled
    tags: &id046
    - Employer Reviews
    - Job Search
    - Recruiting
    - Salaries
    url: /providers/glassdoor/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 47.7
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id047
      source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
      status: verified
    slug: google-ads
    status: profiled
    tags: &id048
    - Advertising
    - Campaign Management
    - Digital Advertising
    - Google
    url: /providers/google-ads/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: developing
    in_catalog: true
    kin_score: 42.0
    mcp: &id049
      status: none
    slug: gusto
    status: profiled
    tags: &id050
    - Benefits
    - Enterprise Software
    - Human Resources
    - Payroll
    url: /providers/gusto/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 24.8
    mcp: &id051
      status: none
    slug: hackerrank
    status: profiled
    tags: &id052
    - Coding Assessment
    - Company
    - Developer Skills
    - Technical Hiring
    url: /providers/hackerrank/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.7
    band: thin
    in_catalog: true
    kin_score: 30.4
    mcp: &id053
      source: https://apidocs.hibob.com/docs/hibob-mcp-server
      status: verified
    slug: bob
    status: profiled
    tags: &id054
    - Employee Management
    - HRIS
    - Human Resources
    - Time Off
    url: /providers/bob/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id055
      status: unchecked
    slug: hireez
    status: queued for profiling
    tags: &id056 []
    url: null
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
  facts:
    agent_band: agent-ready
    agent_readiness: 52.7
    band: exemplar
    in_catalog: true
    kin_score: 94.6
    mcp: &id057
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id058
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 45.2
    band: developing
    in_catalog: true
    kin_score: 53.9
    mcp: &id059
      status: none
    slug: humaans-io
    status: profiled
    tags: &id060
    - HRIS
    - Human Resources
    - People Analytics
    - People Operations
    url: /providers/humaans-io/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.6
    band: developing
    in_catalog: true
    kin_score: 46.0
    mcp: &id061
      status: none
    slug: indeed
    status: profiled
    tags: &id062
    - Careers
    - Employment
    - Hiring
    - Job Search
    url: /providers/indeed/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.9
    band: exemplar
    in_catalog: true
    kin_score: 69.0
    mcp: &id063
      status: none
    slug: instagram
    status: profiled
    tags: &id064
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.2
    mcp: &id065
      status: none
    slug: jooble
    status: profiled
    tags: &id066
    - Job
    - Job Board
    - Public APIs
    url: /providers/jooble/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 47.4
    band: exemplar
    in_catalog: true
    kin_score: 76.4
    mcp: &id067
      status: none
    slug: linkedin
    status: profiled
    tags: &id068
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.2
    mcp: &id069
      status: unknown
    slug: monster
    status: profiled
    tags: &id070
    - Company
    - Employment
    - Recruiting
    - Technology
    url: /providers/monster/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 4.9
    mcp: &id071
      status: unknown
    slug: naukri
    status: profiled
    tags: &id072
    - Careers
    - Company
    - Job
    - Recruiting
    url: /providers/naukri/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 30.4
    mcp: &id073
      status: none
    slug: nmbrs
    status: profiled
    tags: &id074
    - Employee Management
    - HRIS
    - Human Resources
    - Payroll
    url: /providers/nmbrs/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 30.9
    mcp: &id075
      status: none
    slug: oneflow
    status: profiled
    tags: &id076
    - Contract Lifecycle Management
    - Contract Management
    - Digital Contracts
    - E-Signature
    url: /providers/oneflow/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id077
      status: unchecked
    slug: oysterhr
    status: queued for profiling
    tags: &id078 []
    url: null
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.6
    band: developing
    in_catalog: true
    kin_score: 41.4
    mcp: &id079
      source: https://github.com/pandadoc/pandadoc-mcpb
      status: verified
    slug: pandadoc
    status: profiled
    tags: &id080
    - Document Automation
    - Document Generation
    - Document Management
    - E-Signature
    url: /providers/pandadoc/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.8
    band: thin
    in_catalog: true
    kin_score: 28.5
    mcp: &id081
      status: none
    slug: payfit
    status: profiled
    tags: &id082
    - Europe Payroll
    - Human Resources
    - Payroll
    - Time and Attendance
    url: /providers/payfit/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.9
    band: thin
    in_catalog: true
    kin_score: 31.4
    mcp: &id083
      status: none
    slug: paylocity
    status: profiled
    tags: &id084
    - Benefits
    - HCM
    - Human Resources
    - Payroll
    url: /providers/paylocity/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.3
    band: strong
    in_catalog: true
    kin_score: 57.6
    mcp: &id085
      status: none
    slug: penneo
    status: profiled
    tags: &id086
    - Company
    - Compliance
    - Digital Signing
    - eIDAS
    url: /providers/penneo/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.8
    band: thin
    in_catalog: true
    kin_score: 31.4
    mcp: &id087
      status: none
    slug: personio
    status: profiled
    tags: &id088
    - Applicant Tracking
    - HRIS
    - Human Resources
    - Recruiting
    url: /providers/personio/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.2
    mcp: &id089
      status: none
    slug: reed
    status: profiled
    tags: &id090
    - Job
    - Job Board
    - Public APIs
    url: /providers/reed/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 47.9
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id091
      status: none
    slug: ringover
    status: profiled
    tags: &id092
    - Cloud
    - Collaboration
    - Communications
    - VoIP
    url: /providers/ringover/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.4
    band: thin
    in_catalog: true
    kin_score: 32.9
    mcp: &id093
      status: none
    slug: rippling
    status: profiled
    tags: &id094
    - HCM
    - Human Resources
    - IT
    - Payroll
    url: /providers/rippling/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.3
    band: emerging
    in_catalog: true
    kin_score: 26.1
    mcp: &id095
      status: none
    slug: sap-successfactors
    status: profiled
    tags: &id096
    - HCM
    - Human Resources
    - Payroll
    - Talent Management
    url: /providers/sap-successfactors/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.4
    band: thin
    in_catalog: true
    kin_score: 28.9
    mcp: &id097
      source: https://github.com/scrive/mcp
      status: verified
    slug: scrive
    status: profiled
    tags: &id098
    - BankID
    - Digital Identity
    - E-Signature
    - eID
    url: /providers/scrive/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 10.7
    mcp: &id099
      status: none
    slug: sd-worx
    status: profiled
    tags: &id100
    - Europe
    - Human Resources
    - Payroll
    - Workforce Management
    url: /providers/sd-worx/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 42.4
    band: thin
    in_catalog: true
    kin_score: 27.8
    mcp: &id101
      status: none
    slug: sesame-hr
    status: profiled
    tags: &id102
    - HRIS
    - Human Resources
    - Time Tracking
    - Workforce Management
    url: /providers/sesame-hr/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 9.4
    mcp: &id103
      status: unknown
    slug: shl
    status: profiled
    tags: &id104
    - Company
    - HR Technology
    - People Science
    - Talent Assessment
    url: /providers/shl/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 21.3
    band: emerging
    in_catalog: true
    kin_score: 25.9
    mcp: &id105
      status: none
    slug: signeasy
    status: profiled
    tags: &id106
    - Contract Management
    - Documents
    - E-Signature
    - Embedded Signing
    url: /providers/signeasy/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 48.1
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id107
      status: none
    slug: snapchat
    status: profiled
    tags: &id108
    - Advertising
    - Augmented Reality
    - Marketing
    - Messaging
    url: /providers/snapchat/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: emerging
    in_catalog: true
    kin_score: 23.7
    mcp: &id109
      status: none
    slug: spark-hire
    status: profiled
    tags: &id110
    - Hiring
    - Human Resources
    - Recruiting
    - Video Interviewing
    url: /providers/spark-hire/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.5
    mcp: &id111
      status: unknown
    slug: talent-com
    status: profiled
    tags: &id112
    - Company
    - Employment
    - Job Search
    - Recruiting
    url: /providers/talent-com/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 18.7
    mcp: &id113
      status: none
    slug: testgorilla
    status: profiled
    tags: &id114
    - Company
    - Hiring
    - Recruiting
    - Talent Assessment
    url: /providers/testgorilla/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.2
    band: developing
    in_catalog: true
    kin_score: 52.3
    mcp: &id115
      status: none
    slug: the-predictive-index
    status: profiled
    tags: &id116
    - Assessment
    - Company
    - Human Resources
    - Talent Optimization
    url: /providers/the-predictive-index/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 41.0
    mcp: &id117
      status: none
    slug: tiktok
    status: profiled
    tags: &id118
    - Advertising
    - Commerce
    - Content
    - TikTok
    url: /providers/tiktok/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id119
      status: unchecked
    slug: totaljobs
    status: queued for profiling
    tags: &id120 []
    url: null
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
  facts:
    agent_band: human-only
    agent_readiness: 3.1
    band: emerging
    in_catalog: true
    kin_score: 16.9
    mcp: &id121
      status: none
    slug: trinet-group
    status: profiled
    tags: &id122
    - Benefits
    - Compliance
    - Human Resources
    - Payroll
    url: /providers/trinet-group/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.0
    band: emerging
    in_catalog: true
    kin_score: 13.7
    mcp: &id123
      status: none
    slug: upsales
    status: profiled
    tags: &id124
    - Artificial Intelligence
    - CRM
    - Company
    - Sales
    url: /providers/upsales/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 21.6
    band: emerging
    in_catalog: true
    kin_score: 19.8
    mcp: &id125
      status: none
    slug: verified-first
    status: profiled
    tags: &id126
    - Background Checks
    - Company
    - Screening
    - Verification
    url: /providers/verified-first/
  layer: domain
  name: Verified First
  provider: verified-first
  says: lists Verified First as an integration
  source: https://www.teamtailor.com/en/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/recruiting-ats/teamtailor/
providers:
- agent_band: agent-ready
  agent_readiness: 65.9
  band: exemplar
  in_catalog: true
  kin_score: 76.2
  mcp: *id001
  name: Adobe Acrobat Sign
  slug: adobe
  status: profiled
  tags: *id002
  url: /providers/adobe/
- agent_band: agent-ready
  agent_readiness: 35.7
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id003
  name: ADP
  slug: adp
  status: profiled
  tags: *id004
  url: /providers/adp/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.2
  mcp: *id005
  name: Adzuna
  slug: adzuna
  status: profiled
  tags: *id006
  url: /providers/adzuna/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id007
  name: AFAS
  slug: afas
  status: profiled
  tags: *id008
  url: /providers/afas/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 40.9
  mcp: *id009
  name: BambooHR
  slug: bamboohr
  status: profiled
  tags: *id010
  url: /providers/bamboohr/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.2
  mcp: *id011
  name: Careerjet
  slug: careerjet
  status: profiled
  tags: *id012
  url: /providers/careerjet/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id013
  name: Certn
  slug: certn
  status: profiled
  tags: *id014
  url: /providers/certn/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: thin
  in_catalog: true
  kin_score: 31.0
  mcp: *id015
  name: Charlie HR
  slug: charliehr
  status: profiled
  tags: *id016
  url: /providers/charliehr/
- agent_band: agent-ready
  agent_readiness: 48.1
  band: thin
  in_catalog: true
  kin_score: 32.8
  mcp: *id017
  name: Checkr
  slug: checkr
  status: profiled
  tags: *id018
  url: /providers/checkr/
- agent_band: agent-ready
  agent_readiness: 29.7
  band: strong
  in_catalog: true
  kin_score: 54.8
  mcp: *id019
  name: CoderPad
  slug: coderpad
  status: profiled
  tags: *id020
  url: /providers/coderpad/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 24.4
  mcp: *id021
  name: Codility
  slug: codility
  status: profiled
  tags: *id022
  url: /providers/codility/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 16.4
  mcp: *id023
  name: Criteria Corp
  slug: criteria-corp
  status: profiled
  tags: *id024
  url: /providers/criteria-corp/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.8
  mcp: *id025
  name: Crosschq
  slug: crosschq
  status: profiled
  tags: *id026
  url: /providers/crosschq/
- agent_band: agent-aware
  agent_readiness: 12.9
  band: emerging
  in_catalog: true
  kin_score: 14.1
  mcp: *id027
  name: Darwinbox
  slug: darwinbox
  status: profiled
  tags: *id028
  url: /providers/darwinbox/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 13.6
  mcp: *id029
  name: Dayforce
  slug: dayforce
  status: profiled
  tags: *id030
  url: /providers/dayforce/
- agent_band: agent-native
  agent_readiness: 51.7
  band: strong
  in_catalog: true
  kin_score: 63.3
  mcp: *id031
  name: Deel
  slug: deel-com
  status: profiled
  tags: *id032
  url: /providers/deel-com/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: strong
  in_catalog: true
  kin_score: 66.2
  mcp: *id033
  name: Deputy
  slug: deputy
  status: profiled
  tags: *id034
  url: /providers/deputy/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id035
  name: DocuSign
  slug: docusign
  status: profiled
  tags: *id036
  url: /providers/docusign/
- agent_band: agent-ready
  agent_readiness: 48.8
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id037
  name: Dropbox Sign
  slug: hellosign
  status: profiled
  tags: *id038
  url: /providers/hellosign/
- agent_band: agent-ready
  agent_readiness: 40.2
  band: strong
  in_catalog: true
  kin_score: 60.0
  mcp: *id039
  name: Experian
  slug: experian
  status: profiled
  tags: *id040
  url: /providers/experian/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id041
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id042
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 48.5
  band: developing
  in_catalog: true
  kin_score: 53.8
  mcp: *id043
  name: Factorial
  slug: factorial-hr
  status: profiled
  tags: *id044
  url: /providers/factorial-hr/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 11.1
  mcp: *id045
  name: Glassdoor
  slug: glassdoor
  status: profiled
  tags: *id046
  url: /providers/glassdoor/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id047
  name: Google Ads
  slug: google-ads
  status: profiled
  tags: *id048
  url: /providers/google-ads/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 42.0
  mcp: *id049
  name: Gusto
  slug: gusto
  status: profiled
  tags: *id050
  url: /providers/gusto/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 24.8
  mcp: *id051
  name: HackerRank
  slug: hackerrank
  status: profiled
  tags: *id052
  url: /providers/hackerrank/
- agent_band: agent-aware
  agent_readiness: 19.7
  band: thin
  in_catalog: true
  kin_score: 30.4
  mcp: *id053
  name: HiBob
  slug: bob
  status: profiled
  tags: *id054
  url: /providers/bob/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id055
  name: hireEZ
  slug: hireez
  status: queued for profiling
  tags: *id056
  url: null
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id057
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id058
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 45.2
  band: developing
  in_catalog: true
  kin_score: 53.9
  mcp: *id059
  name: Humaans
  slug: humaans-io
  status: profiled
  tags: *id060
  url: /providers/humaans-io/
- agent_band: agent-ready
  agent_readiness: 29.6
  band: developing
  in_catalog: true
  kin_score: 46.0
  mcp: *id061
  name: Indeed
  slug: indeed
  status: profiled
  tags: *id062
  url: /providers/indeed/
- agent_band: agent-ready
  agent_readiness: 38.9
  band: exemplar
  in_catalog: true
  kin_score: 69.0
  mcp: *id063
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id064
  url: /providers/instagram/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.2
  mcp: *id065
  name: Jooble
  slug: jooble
  status: profiled
  tags: *id066
  url: /providers/jooble/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: exemplar
  in_catalog: true
  kin_score: 76.4
  mcp: *id067
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id068
  url: /providers/linkedin/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.2
  mcp: *id069
  name: Monster
  slug: monster
  status: profiled
  tags: *id070
  url: /providers/monster/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 4.9
  mcp: *id071
  name: Naukri
  slug: naukri
  status: profiled
  tags: *id072
  url: /providers/naukri/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 30.4
  mcp: *id073
  name: Nmbrs
  slug: nmbrs
  status: profiled
  tags: *id074
  url: /providers/nmbrs/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 30.9
  mcp: *id075
  name: Oneflow
  slug: oneflow
  status: profiled
  tags: *id076
  url: /providers/oneflow/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id077
  name: Oyster HR
  slug: oysterhr
  status: queued for profiling
  tags: *id078
  url: null
- agent_band: agent-ready
  agent_readiness: 34.6
  band: developing
  in_catalog: true
  kin_score: 41.4
  mcp: *id079
  name: PandaDoc
  slug: pandadoc
  status: profiled
  tags: *id080
  url: /providers/pandadoc/
- agent_band: agent-aware
  agent_readiness: 22.8
  band: thin
  in_catalog: true
  kin_score: 28.5
  mcp: *id081
  name: PayFit
  slug: payfit
  status: profiled
  tags: *id082
  url: /providers/payfit/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: thin
  in_catalog: true
  kin_score: 31.4
  mcp: *id083
  name: Paylocity
  slug: paylocity
  status: profiled
  tags: *id084
  url: /providers/paylocity/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: strong
  in_catalog: true
  kin_score: 57.6
  mcp: *id085
  name: Penneo
  slug: penneo
  status: profiled
  tags: *id086
  url: /providers/penneo/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: thin
  in_catalog: true
  kin_score: 31.4
  mcp: *id087
  name: Personio
  slug: personio
  status: profiled
  tags: *id088
  url: /providers/personio/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.2
  mcp: *id089
  name: Reed
  slug: reed
  status: profiled
  tags: *id090
  url: /providers/reed/
- agent_band: agent-ready
  agent_readiness: 47.9
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id091
  name: Ringover
  slug: ringover
  status: profiled
  tags: *id092
  url: /providers/ringover/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: thin
  in_catalog: true
  kin_score: 32.9
  mcp: *id093
  name: Rippling
  slug: rippling
  status: profiled
  tags: *id094
  url: /providers/rippling/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: emerging
  in_catalog: true
  kin_score: 26.1
  mcp: *id095
  name: SAP SuccessFactors
  slug: sap-successfactors
  status: profiled
  tags: *id096
  url: /providers/sap-successfactors/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id097
  name: Scrive
  slug: scrive
  status: profiled
  tags: *id098
  url: /providers/scrive/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 10.7
  mcp: *id099
  name: SD Worx
  slug: sd-worx
  status: profiled
  tags: *id100
  url: /providers/sd-worx/
- agent_band: agent-ready
  agent_readiness: 42.4
  band: thin
  in_catalog: true
  kin_score: 27.8
  mcp: *id101
  name: Sesame HR
  slug: sesame-hr
  status: profiled
  tags: *id102
  url: /providers/sesame-hr/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 9.4
  mcp: *id103
  name: SHL
  slug: shl
  status: profiled
  tags: *id104
  url: /providers/shl/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: emerging
  in_catalog: true
  kin_score: 25.9
  mcp: *id105
  name: Signeasy
  slug: signeasy
  status: profiled
  tags: *id106
  url: /providers/signeasy/
- agent_band: agent-ready
  agent_readiness: 48.1
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id107
  name: Snapchat
  slug: snapchat
  status: profiled
  tags: *id108
  url: /providers/snapchat/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: emerging
  in_catalog: true
  kin_score: 23.7
  mcp: *id109
  name: Spark Hire
  slug: spark-hire
  status: profiled
  tags: *id110
  url: /providers/spark-hire/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id111
  name: Talent.com
  slug: talent-com
  status: profiled
  tags: *id112
  url: /providers/talent-com/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.7
  mcp: *id113
  name: TestGorilla
  slug: testgorilla
  status: profiled
  tags: *id114
  url: /providers/testgorilla/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 52.3
  mcp: *id115
  name: The Predictive Index
  slug: the-predictive-index
  status: profiled
  tags: *id116
  url: /providers/the-predictive-index/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 41.0
  mcp: *id117
  name: TikTok
  slug: tiktok
  status: profiled
  tags: *id118
  url: /providers/tiktok/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id119
  name: Totaljobs
  slug: totaljobs
  status: queued for profiling
  tags: *id120
  url: null
- agent_band: human-only
  agent_readiness: 3.1
  band: emerging
  in_catalog: true
  kin_score: 16.9
  mcp: *id121
  name: TriNet
  slug: trinet-group
  status: profiled
  tags: *id122
  url: /providers/trinet-group/
- agent_band: agent-aware
  agent_readiness: 18.0
  band: emerging
  in_catalog: true
  kin_score: 13.7
  mcp: *id123
  name: Upsales
  slug: upsales
  status: profiled
  tags: *id124
  url: /providers/upsales/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: emerging
  in_catalog: true
  kin_score: 19.8
  mcp: *id125
  name: Verified First
  slug: verified-first
  status: profiled
  tags: *id126
  url: /providers/verified-first/
siblings:
- name: Ashby
  rows: 3
  url: /applications/recruiting-ats/ashby/
- name: Greenhouse
  rows: 5
  url: /applications/recruiting-ats/greenhouse/
- name: Horilla (Recruitment)
  rows: 1
  url: /applications/recruiting-ats/horilla-recruitment/
- name: Lever
  rows: 7
  url: /applications/recruiting-ats/lever/
- name: OpenCATS
  rows: 2
  url: /applications/recruiting-ats/opencats/
- name: Recruitee
  rows: 7
  url: /applications/recruiting-ats/recruitee/
sitemap: true
title: 'Teamtailor: Recruiting & Applicant Tracking reference app'
---
