---
app: Fonoster
app_slug: fonoster
app_url: https://github.com/fonoster/fonoster
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.50.10
  key: AE-150.50.10
  layer: domain
  name: Programmable Voice
  providers:
  - Twilio
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
- attribution: API Evangelist extension
  id: AE-110.30.10
  key: AE-110.30.10
  layer: domain
  name: Speech-to-Text
  providers:
  - Deepgram
  - Google
  url: /capabilities/speech-voice/
  via_parent: Speech & Voice
- attribution: API Evangelist extension
  id: AE-110.30.20
  key: AE-110.30.20
  layer: domain
  name: Text-to-Speech
  providers:
  - Azure
  - Deepgram
  - ElevenLabs
  - Google
  url: /capabilities/speech-voice/
  via_parent: Speech & Voice
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - '@langchain/anthropic'
  - '@langchain/google-genai'
  - '@langchain/groq'
  - '@langchain/ollama'
  - '@langchain/openai'
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: voip-call-center
  name: VoIP, Phone & Contact Center
  url: /applications/voip-call-center/
counts:
  declared: 0
  observed: 14
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/fonoster/fonoster/blob/main/mods/autopilot/package.json
- route: source code
  url: https://github.com/fonoster/fonoster/blob/main/mods/appbridge/src/protocols/twilio.ts
- route: source code
  url: https://github.com/fonoster/fonoster/blob/main/mods/common/src/notifications/createSendSmsTwilioImpl.ts
- route: source code
  url: https://github.com/fonoster/fonoster/tree/main/mods/apiserver/src/voice/stt
- route: source code
  url: https://github.com/fonoster/fonoster/tree/main/mods/apiserver/src/voice/tts
- route: source code
  url: https://github.com/fonoster/fonoster/tree/main/mods/billing/src/stripe
- route: source code
  url: https://github.com/fonoster/fonoster/tree/main/mods/mcp
integrations:
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
    mcp: &id003
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id004
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: '@langchain/anthropic'
  provider: anthropic
  says: ships the @langchain/anthropic SDK or integration code
  source: https://github.com/fonoster/fonoster/blob/main/mods/autopilot/package.json
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
    agent_readiness: 35.0
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id005
      status: none
    slug: google-gemini
    status: profiled
    tags: &id006
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: '@langchain/google-genai'
  provider: google-gemini
  says: ships the @langchain/google-genai SDK or integration code
  source: https://github.com/fonoster/fonoster/blob/main/mods/autopilot/package.json
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
    agent_readiness: 21.2
    band: thin
    in_catalog: true
    kin_score: 32.3
    mcp: &id007
      source: https://github.com/groq/groq-mcp-server
      status: verified
    slug: groq
    status: profiled
    tags: &id008
    - Artificial Intelligence
    - Inference
    - LLM
    - LPU
    url: /providers/groq/
  layer: agent
  name: '@langchain/groq'
  provider: groq
  says: ships the @langchain/groq SDK or integration code
  source: https://github.com/fonoster/fonoster/blob/main/mods/autopilot/package.json
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
    mcp: &id009
      status: none
    slug: ollama
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
  layer: agent
  name: '@langchain/ollama'
  provider: ollama
  says: ships the @langchain/ollama SDK or integration code
  source: https://github.com/fonoster/fonoster/blob/main/mods/autopilot/package.json
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
    mcp: &id011
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id012
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: '@langchain/openai'
  provider: openai
  says: ships the @langchain/openai SDK or integration code
  source: https://github.com/fonoster/fonoster/blob/main/mods/autopilot/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.20
    key: AE-110.30.20
    name: Text-to-Speech
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.8
    band: strong
    in_catalog: true
    kin_score: 57.9
    mcp: &id013
      source: https://github.com/microsoft/mcp
      status: verified
    slug: azure-ai-speech
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Cloud
    - Microsoft
    - Speech
    url: /providers/azure-ai-speech/
  layer: domain
  name: Azure
  provider: azure-ai-speech
  says: ships the Azure SDK or integration code
  source: https://github.com/fonoster/fonoster/tree/main/mods/apiserver/src/voice/tts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.10
    key: AE-110.30.10
    name: Speech-to-Text
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 35.9
    band: developing
    in_catalog: true
    kin_score: 48.2
    mcp: &id015
      source: https://github.com/deepgram/mcp
      status: verified
    slug: deepgram
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - Speech-to-Text
    - Text-to-Speech
    - Transcription
    url: /providers/deepgram/
  layer: domain
  name: Deepgram
  provider: deepgram
  says: ships the Deepgram SDK or integration code
  source: https://github.com/fonoster/fonoster/tree/main/mods/apiserver/src/voice/stt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.20
    key: AE-110.30.20
    name: Text-to-Speech
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts: *id001
  layer: domain
  name: Deepgram
  provider: deepgram
  says: ships the Deepgram SDK or integration code
  source: https://github.com/fonoster/fonoster/tree/main/mods/apiserver/src/voice/tts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.20
    key: AE-110.30.20
    name: Text-to-Speech
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 60.4
    band: exemplar
    in_catalog: true
    kin_score: 83.2
    mcp: &id017
      source: https://github.com/elevenlabs/elevenlabs-mcp
      status: verified
    slug: elevenlabs
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Speech-to-Text
    - Text-to-Speech
    - Voice
    url: /providers/elevenlabs/
  layer: domain
  name: ElevenLabs
  provider: elevenlabs
  says: ships the ElevenLabs SDK or integration code
  source: https://github.com/fonoster/fonoster/tree/main/mods/apiserver/src/voice/tts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.10
    key: AE-110.30.10
    name: Speech-to-Text
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id019
      status: none
    slug: google-cloud-speech-to-text
    status: profiled
    tags: &id020
    - Audio Processing
    - Google Cloud
    - Machine Learning
    - Speech Recognition
    url: /providers/google-cloud-speech-to-text/
  layer: domain
  name: Google
  provider: google-cloud-speech-to-text
  says: ships the Google SDK or integration code
  source: https://github.com/fonoster/fonoster/tree/main/mods/apiserver/src/voice/stt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.20
    key: AE-110.30.20
    name: Text-to-Speech
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: exemplar
    in_catalog: true
    kin_score: 68.6
    mcp: &id021
      status: none
    slug: google-cloud-text-to-speech
    status: profiled
    tags: &id022
    - Audio
    - Google Cloud
    - Machine Learning
    - Speech Synthesis
    url: /providers/google-cloud-text-to-speech/
  layer: domain
  name: Google
  provider: google-cloud-text-to-speech
  says: ships the Google SDK or integration code
  source: https://github.com/fonoster/fonoster/tree/main/mods/apiserver/src/voice/tts
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id023
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id024
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/fonoster/fonoster/tree/main/mods/billing/src/stripe
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.10
    key: AE-150.50.10
    name: Programmable Voice
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  credit: null
  facts: &id002
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id025
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id026
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: domain
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/fonoster/fonoster/blob/main/mods/appbridge/src/protocols/twilio.ts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts: *id002
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/fonoster/fonoster/blob/main/mods/common/src/notifications/createSendSmsTwilioImpl.ts
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/voip-call-center/fonoster/
providers:
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id003
  name: '@langchain/anthropic'
  slug: anthropic
  status: profiled
  tags: *id004
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id005
  name: '@langchain/google-genai'
  slug: google-gemini
  status: profiled
  tags: *id006
  url: /providers/google-gemini/
- agent_band: agent-aware
  agent_readiness: 21.2
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id007
  name: '@langchain/groq'
  slug: groq
  status: profiled
  tags: *id008
  url: /providers/groq/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 37.7
  mcp: *id009
  name: '@langchain/ollama'
  slug: ollama
  status: profiled
  tags: *id010
  url: /providers/ollama/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id011
  name: '@langchain/openai'
  slug: openai
  status: profiled
  tags: *id012
  url: /providers/openai/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id013
  name: Azure
  slug: azure-ai-speech
  status: profiled
  tags: *id014
  url: /providers/azure-ai-speech/
- agent_band: agent-ready
  agent_readiness: 35.9
  band: developing
  in_catalog: true
  kin_score: 48.2
  mcp: *id015
  name: Deepgram
  slug: deepgram
  status: profiled
  tags: *id016
  url: /providers/deepgram/
- agent_band: agent-ready
  agent_readiness: 60.4
  band: exemplar
  in_catalog: true
  kin_score: 83.2
  mcp: *id017
  name: ElevenLabs
  slug: elevenlabs
  status: profiled
  tags: *id018
  url: /providers/elevenlabs/
- agent_band: agent-ready
  agent_readiness: 33.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id019
  name: Google
  slug: google-cloud-speech-to-text
  status: profiled
  tags: *id020
  url: /providers/google-cloud-speech-to-text/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: exemplar
  in_catalog: true
  kin_score: 68.6
  mcp: *id021
  name: Google
  slug: google-cloud-text-to-speech
  status: profiled
  tags: *id022
  url: /providers/google-cloud-text-to-speech/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id023
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id024
  url: /providers/stripe/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id025
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id026
  url: /providers/twilio/
siblings:
- name: Aircall
  rows: 42
  url: /applications/voip-call-center/aircall/
- name: Dialpad
  rows: 5
  url: /applications/voip-call-center/dialpad/
- name: jambonz
  rows: 36
  url: /applications/voip-call-center/jambonz/
- name: JustCall
  rows: 36
  url: /applications/voip-call-center/justcall/
- name: Talkdesk
  rows: 25
  url: /applications/voip-call-center/talkdesk/
sitemap: true
title: 'Fonoster: VoIP, Phone & Contact Center reference app'
---
