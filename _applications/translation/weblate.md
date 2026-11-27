---
app: Weblate
app_slug: weblate
app_url: https://github.com/WeblateOrg/weblate
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: domain
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - Azure OpenAI
  - Mistral AI
  - Ollama
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: domain
  name: Machine Translation
  providers:
  - Alibaba Cloud Machine Translation
  - Amazon Translate
  - Apertium
  - Azure AI Translator
  - Baidu Translate
  - DeepL
  - European Commission eTranslation
  - Google Cloud Translation
  - LibreTranslate
  - ModernMT
  - NetEase Youdao
  - SAP Translation Hub
  - SYSTRAN
  - Yandex Translate
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - Azure DevOps
  - Bitbucket
  - Gerrit Code Review
  - Gitea
  - GitHub
  - GitLab
  - Pagure
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.40.30
  key: AE-110.40.30
  layer: domain
  name: Translation Memory & Terminology Lookup
  providers:
  - Glosbe
  - MyMemory (Translated)
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Google Cloud Error Reporting
  - Rollbar
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: translation
  name: Translation & Localization
  url: /applications/translation/
counts:
  declared: 0
  observed: 33
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/WeblateOrg/weblate/blob/main/pyproject.toml
- route: source code
  url: https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
- route: source code
  url: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id001
      source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
      status: verified
    slug: alibabacloud
    status: profiled
    tags: &id002
    - Company
    url: /providers/alibabacloud/
  layer: domain
  name: Alibaba Cloud Machine Translation
  provider: alibabacloud
  says: ships the Alibaba Cloud Machine Translation SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
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
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/WeblateOrg/weblate/blob/main/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: exemplar
    in_catalog: true
    kin_score: 73.7
    mcp: &id005
      source: https://api.github.com/repos/awslabs/mcp/contents/src
      status: verified
    slug: amazon-translate
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Language Processing
    - Localization
    - Machine Translation
    url: /providers/amazon-translate/
  layer: domain
  name: Amazon Translate
  provider: amazon-translate
  says: ships the Amazon Translate SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id007
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id008
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: domain
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.7
    mcp: &id009
      status: none
    slug: apertium
    status: profiled
    tags: &id010
    - Linguistics
    - Machine Translation
    - Natural Language Processing
    - Open Source
    url: /providers/apertium/
  layer: domain
  name: Apertium
  provider: apertium
  says: ships the Apertium SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.2
    band: strong
    in_catalog: true
    kin_score: 62.4
    mcp: &id011
      source: https://github.com/microsoft/azure-speech-mcp-server
      status: verified
    slug: microsoft-cognitive-services
    status: profiled
    tags: &id012
    - Azure AI
    - Computer Vision
    - Natural Language Processing
    - Speech
    url: /providers/microsoft-cognitive-services/
  layer: domain
  name: Azure AI Translator
  provider: microsoft-cognitive-services
  says: ships the Azure AI Translator SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.7
    band: exemplar
    in_catalog: true
    kin_score: 81.9
    mcp: &id013
      source: https://github.com/microsoft/azure-devops-mcp
      status: verified
    slug: microsoft-azure-devops
    status: profiled
    tags: &id014
    - Agile
    - CI/CD
    - DevOps
    - Developer Tools
    url: /providers/microsoft-azure-devops/
  layer: domain
  name: Azure DevOps
  provider: microsoft-azure-devops
  says: ships the Azure DevOps SDK or integration code
  source: https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.9
    band: exemplar
    in_catalog: true
    kin_score: 68.3
    mcp: &id015
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-openai
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - Embeddings
    - GPT
    - Generative AI
    url: /providers/microsoft-azure-openai/
  layer: domain
  name: Azure OpenAI
  provider: microsoft-azure-openai
  says: ships the Azure OpenAI SDK or integration code
  source: https://github.com/WeblateOrg/weblate/blob/main/weblate/machinery/openai.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.8
    band: emerging
    in_catalog: true
    kin_score: 17.4
    mcp: &id017
      source: https://github.com/baidu-maps/mcp
      status: verified
    slug: baidu
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Company
    - Machine Learning
    - Technology
    url: /providers/baidu/
  layer: domain
  name: Baidu Translate
  provider: baidu
  says: ships the Baidu Translate SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: exemplar
    in_catalog: true
    kin_score: 71.9
    mcp: &id019
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: bitbucket
    status: profiled
    tags: &id020
    - Atlassian
    - CI/CD
    - Code Collaboration
    - Code Review
    url: /providers/bitbucket/
  layer: domain
  name: Bitbucket
  provider: bitbucket
  says: ships the Bitbucket SDK or integration code
  source: https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.1
    band: strong
    in_catalog: true
    kin_score: 61.4
    mcp: &id021
      source: https://github.com/DeepL/deepl-mcp-server
      status: verified
    slug: deepl
    status: profiled
    tags: &id022
    - Artificial Intelligence
    - Deep Learning
    - Glossary
    - Localization
    url: /providers/deepl/
  layer: domain
  name: DeepL
  provider: deepl
  says: ships the DeepL SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 10.6
    band: emerging
    in_catalog: true
    kin_score: 16.2
    mcp: &id023
      status: unknown
    slug: european-commission-etranslation
    status: profiled
    tags: &id024
    - Artificial Intelligence
    - Company
    - Government
    - Translation
    url: /providers/european-commission-etranslation/
  layer: domain
  name: European Commission eTranslation
  provider: european-commission-etranslation
  says: ships the European Commission eTranslation SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.8
    mcp: &id025
      source: https://github.com/GerritCodeReview/gerrit-mcp-server
      status: verified
    slug: gerrit
    status: profiled
    tags: &id026
    - Code Review
    - Company
    - Open Source
    - Version Control
    url: /providers/gerrit/
  layer: domain
  name: Gerrit Code Review
  provider: gerrit
  says: ships the Gerrit Code Review SDK or integration code
  source: https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id027
      source: https://gitea.com/gitea/gitea-mcp
      status: verified
    slug: gitea
    status: profiled
    tags: &id028
    - CI/CD
    - DevOps
    - Gitea
    - Version Control
    url: /providers/gitea/
  layer: domain
  name: Gitea
  provider: gitea
  says: ships the Gitea SDK or integration code
  source: https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id029
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id030
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id031
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id032
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.30
    key: AE-110.40.30
    name: Translation Memory & Terminology Lookup
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.0
    mcp: &id033
      status: none
    slug: glosbe
    status: profiled
    tags: &id034
    - Dictionaries
    - Language Learning
    - Multilingual
    - Translation
    url: /providers/glosbe/
  layer: domain
  name: Glosbe
  provider: glosbe
  says: ships the Glosbe SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
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
    agent_readiness: 37.0
    band: strong
    in_catalog: true
    kin_score: 59.9
    mcp: &id035
      status: none
    slug: google-cloud-error-reporting
    status: profiled
    tags: &id036
    - Debugging
    - Developer Tools
    - Error Reporting
    - Errors
    url: /providers/google-cloud-error-reporting/
  layer: common
  name: Google Cloud Error Reporting
  provider: google-cloud-error-reporting
  says: ships the Google Cloud Error Reporting SDK or integration code
  source: https://github.com/WeblateOrg/weblate/blob/main/pyproject.toml
  tier: observed
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
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id037
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id038
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/WeblateOrg/weblate/blob/main/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.9
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id039
      status: none
    slug: google-translate
    status: profiled
    tags: &id040
    - Google Cloud
    - Internationalization
    - Language Detection
    - Localization
    url: /providers/google-translate/
  layer: domain
  name: Google Cloud Translation
  provider: google-translate
  says: ships the Google Cloud Translation SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: emerging
    in_catalog: true
    kin_score: 24.3
    mcp: &id041
      source: https://github.com/LibreTranslate/LibreTranslate-MCP
      status: verified
    slug: libre-translate
    status: profiled
    tags: &id042
    - Machine Translation
    - Natural Language Processing
    - Open Source
    - Translation
    url: /providers/libre-translate/
  layer: domain
  name: LibreTranslate
  provider: libre-translate
  says: ships the LibreTranslate SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id043
      status: none
    slug: mistral
    status: profiled
    tags: &id044
    - Agents
    - Embeddings
    - Machine Learning
    - OCR
    url: /providers/mistral/
  layer: domain
  name: Mistral AI
  provider: mistral
  says: ships the Mistral AI SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: developing
    in_catalog: true
    kin_score: 39.3
    mcp: &id045
      status: unknown
    slug: modernmt
    status: profiled
    tags: &id046
    - Artificial Intelligence
    - Company
    - Multilingual
    - Translation
    url: /providers/modernmt/
  layer: domain
  name: ModernMT
  provider: modernmt
  says: ships the ModernMT SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.30
    key: AE-110.40.30
    name: Translation Memory & Terminology Lookup
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.9
    mcp: &id047
      status: none
    slug: mymemory
    status: profiled
    tags: &id048
    - Company
    - Localization
    - Machine Translation
    - Translation
    url: /providers/mymemory/
  layer: domain
  name: MyMemory (Translated)
  provider: mymemory
  says: ships the MyMemory (Translated) SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 10.6
    band: minimal
    in_catalog: true
    kin_score: 4.3
    mcp: &id049
      status: unknown
    slug: youdao
    status: profiled
    tags: &id050
    - Artificial Intelligence
    - Company
    - Education
    - Language
    url: /providers/youdao/
  layer: domain
  name: NetEase Youdao
  provider: youdao
  says: ships the NetEase Youdao SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 37.7
    mcp: &id051
      status: none
    slug: ollama
    status: profiled
    tags: &id052
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
  layer: domain
  name: Ollama
  provider: ollama
  says: ships the Ollama SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id053
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id054
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: domain
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.9
    mcp: &id055
      status: none
    slug: pagure
    status: profiled
    tags: &id056
    - Code Hosting
    - Fedora
    - Open Source
    - Version Control
    url: /providers/pagure/
  layer: domain
  name: Pagure
  provider: pagure
  says: ships the Pagure SDK or integration code
  source: https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
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
    agent_readiness: 30.2
    band: developing
    in_catalog: true
    kin_score: 48.1
    mcp: &id057
      source: https://github.com/rollbar/rollbar-mcp-server
      status: verified
    slug: rollbar
    status: profiled
    tags: &id058
    - Debugging
    - DevOps
    - Error Tracking
    - Monitoring
    url: /providers/rollbar/
  layer: common
  name: Rollbar
  provider: rollbar
  says: ships the Rollbar SDK or integration code
  source: https://github.com/WeblateOrg/weblate/blob/main/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 13.3
    band: emerging
    in_catalog: true
    kin_score: 22.7
    mcp: &id059
      status: none
    slug: sap-btp
    status: profiled
    tags: &id060
    - Artificial Intelligence
    - Cloud Platform
    - Integration
    - SAP
    url: /providers/sap-btp/
  layer: domain
  name: SAP Translation Hub
  provider: sap-btp
  says: ships the SAP Translation Hub SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
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
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id061
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id062
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/WeblateOrg/weblate/blob/main/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.9
    band: emerging
    in_catalog: true
    kin_score: 25.5
    mcp: &id063
      status: none
    slug: systran
    status: profiled
    tags: &id064
    - Machine Translation
    - Natural Language Processing
    - Neural Machine Translation
    - Translation
    url: /providers/systran/
  layer: domain
  name: SYSTRAN
  provider: systran
  says: ships the SYSTRAN SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.9
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id065
      status: none
    slug: yandex-translate
    status: profiled
    tags: &id066
    - Language Detection
    - Machine Translation
    - Natural Language Processing
    - Translation Dictionary
    url: /providers/yandex-translate/
  layer: domain
  name: Yandex Translate
  provider: yandex-translate
  says: ships the Yandex Translate SDK or integration code
  source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/translation/weblate/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id001
  name: Alibaba Cloud Machine Translation
  slug: alibabacloud
  status: profiled
  tags: *id002
  url: /providers/alibabacloud/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id003
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id004
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: exemplar
  in_catalog: true
  kin_score: 73.7
  mcp: *id005
  name: Amazon Translate
  slug: amazon-translate
  status: profiled
  tags: *id006
  url: /providers/amazon-translate/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id007
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id008
  url: /providers/anthropic/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.7
  mcp: *id009
  name: Apertium
  slug: apertium
  status: profiled
  tags: *id010
  url: /providers/apertium/
- agent_band: agent-ready
  agent_readiness: 32.2
  band: strong
  in_catalog: true
  kin_score: 62.4
  mcp: *id011
  name: Azure AI Translator
  slug: microsoft-cognitive-services
  status: profiled
  tags: *id012
  url: /providers/microsoft-cognitive-services/
- agent_band: agent-ready
  agent_readiness: 37.7
  band: exemplar
  in_catalog: true
  kin_score: 81.9
  mcp: *id013
  name: Azure DevOps
  slug: microsoft-azure-devops
  status: profiled
  tags: *id014
  url: /providers/microsoft-azure-devops/
- agent_band: agent-ready
  agent_readiness: 29.9
  band: exemplar
  in_catalog: true
  kin_score: 68.3
  mcp: *id015
  name: Azure OpenAI
  slug: microsoft-azure-openai
  status: profiled
  tags: *id016
  url: /providers/microsoft-azure-openai/
- agent_band: agent-aware
  agent_readiness: 5.8
  band: emerging
  in_catalog: true
  kin_score: 17.4
  mcp: *id017
  name: Baidu Translate
  slug: baidu
  status: profiled
  tags: *id018
  url: /providers/baidu/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: exemplar
  in_catalog: true
  kin_score: 71.9
  mcp: *id019
  name: Bitbucket
  slug: bitbucket
  status: profiled
  tags: *id020
  url: /providers/bitbucket/
- agent_band: agent-ready
  agent_readiness: 36.1
  band: strong
  in_catalog: true
  kin_score: 61.4
  mcp: *id021
  name: DeepL
  slug: deepl
  status: profiled
  tags: *id022
  url: /providers/deepl/
- agent_band: agent-aware
  agent_readiness: 10.6
  band: emerging
  in_catalog: true
  kin_score: 16.2
  mcp: *id023
  name: European Commission eTranslation
  slug: european-commission-etranslation
  status: profiled
  tags: *id024
  url: /providers/european-commission-etranslation/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.8
  mcp: *id025
  name: Gerrit Code Review
  slug: gerrit
  status: profiled
  tags: *id026
  url: /providers/gerrit/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id027
  name: Gitea
  slug: gitea
  status: profiled
  tags: *id028
  url: /providers/gitea/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id029
  name: GitHub
  slug: github
  status: profiled
  tags: *id030
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id031
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id032
  url: /providers/gitlab/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.0
  mcp: *id033
  name: Glosbe
  slug: glosbe
  status: profiled
  tags: *id034
  url: /providers/glosbe/
- agent_band: agent-ready
  agent_readiness: 37.0
  band: strong
  in_catalog: true
  kin_score: 59.9
  mcp: *id035
  name: Google Cloud Error Reporting
  slug: google-cloud-error-reporting
  status: profiled
  tags: *id036
  url: /providers/google-cloud-error-reporting/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id037
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id038
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 33.9
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id039
  name: Google Cloud Translation
  slug: google-translate
  status: profiled
  tags: *id040
  url: /providers/google-translate/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: emerging
  in_catalog: true
  kin_score: 24.3
  mcp: *id041
  name: LibreTranslate
  slug: libre-translate
  status: profiled
  tags: *id042
  url: /providers/libre-translate/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id043
  name: Mistral AI
  slug: mistral
  status: profiled
  tags: *id044
  url: /providers/mistral/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: developing
  in_catalog: true
  kin_score: 39.3
  mcp: *id045
  name: ModernMT
  slug: modernmt
  status: profiled
  tags: *id046
  url: /providers/modernmt/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.9
  mcp: *id047
  name: MyMemory (Translated)
  slug: mymemory
  status: profiled
  tags: *id048
  url: /providers/mymemory/
- agent_band: agent-aware
  agent_readiness: 10.6
  band: minimal
  in_catalog: true
  kin_score: 4.3
  mcp: *id049
  name: NetEase Youdao
  slug: youdao
  status: profiled
  tags: *id050
  url: /providers/youdao/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 37.7
  mcp: *id051
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id052
  url: /providers/ollama/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id053
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id054
  url: /providers/openai/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.9
  mcp: *id055
  name: Pagure
  slug: pagure
  status: profiled
  tags: *id056
  url: /providers/pagure/
- agent_band: agent-ready
  agent_readiness: 30.2
  band: developing
  in_catalog: true
  kin_score: 48.1
  mcp: *id057
  name: Rollbar
  slug: rollbar
  status: profiled
  tags: *id058
  url: /providers/rollbar/
- agent_band: agent-aware
  agent_readiness: 13.3
  band: emerging
  in_catalog: true
  kin_score: 22.7
  mcp: *id059
  name: SAP Translation Hub
  slug: sap-btp
  status: profiled
  tags: *id060
  url: /providers/sap-btp/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id061
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id062
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 20.9
  band: emerging
  in_catalog: true
  kin_score: 25.5
  mcp: *id063
  name: SYSTRAN
  slug: systran
  status: profiled
  tags: *id064
  url: /providers/systran/
- agent_band: agent-ready
  agent_readiness: 29.9
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id065
  name: Yandex Translate
  slug: yandex-translate
  status: profiled
  tags: *id066
  url: /providers/yandex-translate/
siblings:
- name: Crowdin
  rows: 11
  url: /applications/translation/crowdin/
- name: DeepL
  rows: 9
  url: /applications/translation/deepl/
- name: LibreTranslate
  rows: 0
  url: /applications/translation/libretranslate/
- name: Lokalise
  rows: 32
  url: /applications/translation/lokalise/
- name: Pontoon
  rows: 13
  url: /applications/translation/pontoon/
- name: Tolgee
  rows: 17
  url: /applications/translation/tolgee/
sitemap: true
title: 'Weblate: Translation & Localization reference app'
---
