---
access: understanding
agent_layer:
- app: jambonz
  finding: feature-server depends on @modelcontextprotocol/sdk (MCP client for LLM voice agents)
  source: https://github.com/jambonz/jambonz-feature-server/blob/main/package.json
  tier: observed
- app: Fonoster
  finding: ships its own MCP server module (mods/mcp) and an LLM voice-agent runtime (Autopilot)
  source: https://github.com/fonoster/fonoster/tree/main/mods/mcp
  tier: observed
apps:
- anchor: jambonz
  counts:
    declared: 0
    observed: 36
  evidence:
  - route: dependency manifest
    url: https://github.com/jambonz/jambonz-feature-server/blob/main/package.json
  - route: dependency manifest
    url: https://github.com/jambonz/speech-utils/blob/main/package.json
  - route: source code
    url: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
  - route: source code
    url: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: AssemblyAI
    provider: assemblyai
    says: ships the AssemblyAI SDK or integration code
    source: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: AWS (Transcribe)
    provider: amazon-transcribe
    says: ships the AWS (Transcribe) SDK or integration code
    source: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: AWS Polly
    provider: amazon-polly
    says: ships the AWS Polly SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Cartesia
    provider: cartesia-ai
    says: ships the Cartesia SDK or integration code
    source: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Cartesia
    provider: cartesia-ai
    says: ships the Cartesia SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Cobalt Speech
    provider: cobalt-speech
    says: ships the Cobalt Speech SDK or integration code
    source: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Deepgram
    provider: deepgram
    says: ships the Deepgram SDK or integration code
    source: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Deepgram
    provider: deepgram
    says: ships the Deepgram SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: ElevenLabs
    provider: elevenlabs
    says: ships the ElevenLabs SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Fish Audio
    provider: fish-audio
    says: ships the Fish Audio SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Gladia
    provider: gladia
    says: ships the Gladia SDK or integration code
    source: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Google
    provider: google-cloud-speech-to-text
    says: ships the Google SDK or integration code
    source: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Google
    provider: google-cloud-text-to-speech
    says: ships the Google SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Gradium
    provider: gradium
    says: ships the Gradium SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Houndify (SoundHound)
    provider: soundhound
    says: ships the Houndify (SoundHound) SDK or integration code
    source: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: IBM Watson
    provider: ibm-watson
    says: ships the IBM Watson SDK or integration code
    source: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Inworld
    provider: inworld
    says: ships the Inworld SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: KugelAudio
    provider: kugelaudio
    says: ships the KugelAudio SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Microsoft Azure Speech
    provider: azure-ai-speech
    says: ships the Microsoft Azure Speech SDK or integration code
    source: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Microsoft Azure Speech
    provider: azure-ai-speech
    says: ships the Microsoft Azure Speech SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Mistral
    provider: mistral
    says: ships the Mistral SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Murf
    provider: murf
    says: ships the Murf SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Nuance
    provider: nuance
    says: ships the Nuance SDK or integration code
    source: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: NVIDIA Riva
    provider: nvidia
    says: ships the NVIDIA Riva SDK or integration code
    source: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: NVIDIA Riva
    provider: nvidia
    says: ships the NVIDIA Riva SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: OpenAI (Whisper/TTS)
    provider: openai
    says: ships the OpenAI (Whisper/TTS) SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Resemble AI
    provider: resemble-ai
    says: ships the Resemble AI SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Rime Labs
    provider: rime-ai
    says: ships the Rime Labs SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Soniox
    provider: soniox
    says: ships the Soniox SDK or integration code
    source: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Speechify
    provider: speechify
    says: ships the Speechify SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Speechmatics
    provider: speechmatics
    says: ships the Speechmatics SDK or integration code
    source: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Verbio
    provider: verbio
    says: ships the Verbio SDK or integration code
    source: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Voxist
    provider: voxist
    says: ships the Voxist SDK or integration code
    source: https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: WellSaid Labs
    provider: wellsaid
    says: ships the WellSaid Labs SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: xAI
    provider: xai
    says: ships the xAI SDK or integration code
    source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
    tier: observed
  kind: self-hosted
  name: jambonz
  page: /applications/voip-call-center/jambonz/
  slug: jambonz
  url: https://github.com/jambonz/jambonz-feature-server
- anchor: fonoster
  counts:
    declared: 0
    observed: 14
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
    layer: common
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/fonoster/fonoster/blob/main/mods/common/src/notifications/createSendSmsTwilioImpl.ts
    tier: observed
  kind: self-hosted
  name: Fonoster
  page: /applications/voip-call-center/fonoster/
  slug: fonoster
  url: https://github.com/fonoster/fonoster
- anchor: aircall
  counts:
    declared: 39
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.aircall/latest/
  - route: integrations page
    url: https://aircall.io/integrations/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.aircall/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.aircall/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Pusher
    provider: pusher
    says: ships the Pusher SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.aircall/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: ActiveCampaign
    provider: activecampaign
    says: lists ActiveCampaign as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Attio
    provider: attio
    says: lists Attio as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.40
      key: AE-110.30.40
      name: Meeting Notes & Conversation Intelligence
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Avoma
    provider: avoma
    says: lists Avoma as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Copper
    provider: copper
    says: lists Copper as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.40
      key: AE-110.30.40
      name: Meeting Notes & Conversation Intelligence
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Fireflies
    provider: fireflies
    says: lists Fireflies as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: Fivetran
    provider: fivetran
    says: lists Fivetran as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Freshdesk
    provider: freshdesk
    says: lists Freshdesk as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Freshsales
    provider: freshsales
    says: lists Freshsales as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Front
    provider: front
    says: lists Front as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: Geckoboard
    provider: geckoboard
    says: lists Geckoboard as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.40
      key: AE-110.30.40
      name: Meeting Notes & Conversation Intelligence
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Gong
    provider: gong
    says: lists Gong as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gorgias
    provider: gorgias
    says: lists Gorgias as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Help Scout
    provider: helpscout
    says: lists Help Scout as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HighLevel
    provider: highlevel
    says: lists HighLevel as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Intercom
    provider: intercom
    says: lists Intercom as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.30.30
      key: BC-430.30.30
      name: Quality Monitoring and Coaching
      url: /capabilities/contact-centre-operations-management/
      via_parent: Contact Centre Operations Management
    credit: null
    layer: domain
    name: Klaus
    provider: klaus
    says: lists Klaus as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Kustomer
    provider: kustomer
    says: lists Kustomer as an integration
    source: https://aircall.io/integrations/
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
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Dynamics
    provider: microsoft-dynamics-365
    says: lists Microsoft Dynamics as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: monday.com
    provider: monday-com
    says: lists monday.com as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Nicereply
    provider: nicereply
    says: lists Nicereply as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Odoo
    provider: odoo
    says: lists Odoo as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-954
      key: AE-954
      name: Sales Engagement & Sequencing
      url: /capabilities/sales-engagement-sequencing/
      via_parent: null
    credit: null
    layer: domain
    name: Outreach
    provider: outreach
    says: lists Outreach as an integration
    source: https://aircall.io/integrations/
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
    name: Pipedream
    provider: pipedream
    says: lists Pipedream as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pipedrive
    provider: pipedrive
    says: lists Pipedrive as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-954
      key: AE-954
      name: Sales Engagement & Sequencing
      url: /capabilities/sales-engagement-sequencing/
      via_parent: null
    credit: null
    layer: domain
    name: Salesloft
    provider: salesloft
    says: lists Salesloft as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: Segment
    provider: segment
    says: lists Segment as an integration
    source: https://aircall.io/integrations/
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
    name: Sinch Engage
    provider: sinch
    says: lists Sinch Engage as an integration
    source: https://aircall.io/integrations/
    tier: declared
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
    source: https://aircall.io/integrations/
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
    name: Tray.io
    provider: tray-ai
    says: lists Tray.io as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: WhatsApp Messaging Channel
    provider: whatsapp
    says: lists WhatsApp Messaging Channel as an integration
    source: https://aircall.io/integrations/
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
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zendesk CTI
    provider: zendesk
    says: lists Zendesk CTI as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zendesk Sell
    provider: zendesk-sell
    says: lists Zendesk Sell as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zoho CRM
    provider: zoho-crm
    says: lists Zoho CRM as an integration
    source: https://aircall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zoho Desk
    provider: zoho-desk
    says: lists Zoho Desk as an integration
    source: https://aircall.io/integrations/
    tier: declared
  kind: commercial
  name: Aircall
  page: /applications/voip-call-center/aircall/
  slug: aircall
  url: https://aircall.io/
- anchor: justcall
  counts:
    declared: 36
    observed: 0
  evidence:
  - route: integrations page
    url: https://justcall.io/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: ActiveCampaign
    provider: activecampaign
    says: lists ActiveCampaign as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-410
      key: sales-management
      name: Sales Management
      url: /capabilities/sales-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apollo.io
    provider: apollo-io
    says: lists Apollo.io as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Attio
    provider: attio
    says: lists Attio as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    credit: null
    layer: common
    name: Calendly
    provider: calendly
    says: lists Calendly as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Close
    provider: close
    says: lists Close as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Copper
    provider: copper
    says: lists Copper as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.40
      key: AE-110.30.40
      name: Meeting Notes & Conversation Intelligence
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Fireflies.ai
    provider: fireflies
    says: lists Fireflies.ai as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: common
    name: Fivetran
    provider: fivetran
    says: lists Fivetran as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Freshdesk
    provider: freshdesk
    says: lists Freshdesk as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Freshsales
    provider: freshsales
    says: lists Freshsales as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Front
    provider: front
    says: lists Front as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.40
      key: AE-110.30.40
      name: Meeting Notes & Conversation Intelligence
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    credit: null
    layer: domain
    name: Gong
    provider: gong
    says: lists Gong as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Google Calendar
    provider: google-calendar
    says: lists Google Calendar as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Google Contacts
    provider: google-people
    says: lists Google Contacts as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gorgias
    provider: gorgias
    says: lists Gorgias as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Help Scout
    provider: helpscout
    says: lists Help Scout as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HighLevel
    provider: highlevel
    says: lists HighLevel as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Intercom
    provider: intercom
    says: lists Intercom as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Keap
    provider: keap
    says: lists Keap as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Kustomer
    provider: kustomer
    says: lists Kustomer as an integration
    source: https://justcall.io/integrations/
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
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Outlook
    provider: microsoft-outlook
    says: lists Microsoft Outlook as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: monday.com
    provider: monday-com
    says: lists monday.com as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Odoo
    provider: odoo
    says: lists Odoo as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-954
      key: AE-954
      name: Sales Engagement & Sequencing
      url: /capabilities/sales-engagement-sequencing/
      via_parent: null
    credit: null
    layer: domain
    name: Outreach
    provider: outreach
    says: lists Outreach as an integration
    source: https://justcall.io/integrations/
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
    name: Pipedream
    provider: pipedream
    says: lists Pipedream as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pipedrive
    provider: pipedrive
    says: lists Pipedrive as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-954
      key: AE-954
      name: Sales Engagement & Sequencing
      url: /capabilities/sales-engagement-sequencing/
      via_parent: null
    credit: null
    layer: domain
    name: Salesloft
    provider: salesloft
    says: lists Salesloft as an integration
    source: https://justcall.io/integrations/
    tier: declared
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
    source: https://justcall.io/integrations/
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
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zendesk Sell
    provider: zendesk-sell
    says: lists Zendesk Sell as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zendesk Support
    provider: zendesk
    says: lists Zendesk Support as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zoho CRM
    provider: zoho-crm
    says: lists Zoho CRM as an integration
    source: https://justcall.io/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zoho Desk
    provider: zoho-desk
    says: lists Zoho Desk as an integration
    source: https://justcall.io/integrations/
    tier: declared
  kind: commercial
  name: JustCall
  page: /applications/voip-call-center/justcall/
  slug: justcall
  url: https://justcall.io/
- anchor: talkdesk
  counts:
    declared: 25
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.talkdesk.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2900.60
      key: BC-2900.60
      name: Healthcare Interoperability Operations
      url: /capabilities/healthcare-interoperability-operations/
      via_parent: null
    credit: null
    layer: domain
    name: athenahealth
    provider: athenahealth
    says: lists athenahealth as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2900.60
      key: BC-2900.60
      name: Healthcare Interoperability Operations
      url: /capabilities/healthcare-interoperability-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Epic
    provider: epic-systems
    says: lists Epic as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Freshdesk
    provider: freshdesk
    says: lists Freshdesk as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Front
    provider: front
    says: lists Front as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Google Contacts
    provider: google-people
    says: lists Google Contacts as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2160
      key: insurance-claims-management
      name: Insurance Claims Management
      url: /capabilities/insurance-claims-management/
      via_parent: null
    credit: null
    layer: domain
    name: Guidewire ClaimCenter
    provider: guidewire
    says: lists Guidewire ClaimCenter as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Help Scout
    provider: helpscout
    says: lists Help Scout as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Intercom
    provider: intercom
    says: lists Intercom as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Keap
    provider: keap
    says: lists Keap as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Kustomer
    provider: kustomer
    says: lists Kustomer as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Dynamics 365
    provider: microsoft-dynamics-365
    says: lists Microsoft Dynamics 365 as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2900.60
      key: BC-2900.60
      name: Healthcare Interoperability Operations
      url: /capabilities/healthcare-interoperability-operations/
      via_parent: null
    credit: null
    layer: domain
    name: Oracle Cerner
    provider: oracle-health
    says: lists Oracle Cerner as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-954
      key: AE-954
      name: Sales Engagement & Sequencing
      url: /capabilities/sales-engagement-sequencing/
      via_parent: null
    credit: null
    layer: domain
    name: Outreach
    provider: outreach
    says: lists Outreach as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pipedrive
    provider: pipedrive
    says: lists Pipedrive as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.30
      key: it-service-management
      name: IT Service Management
      url: /capabilities/it-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: ServiceNow
    provider: servicenow
    says: lists ServiceNow as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
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
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430.30.10
      key: BC-430.30.10
      name: Contact Centre Workforce Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: Contact Centre Operations Management
    credit: null
    layer: domain
    name: Verint (WFM Cloud)
    provider: verint-systems
    says: lists Verint (WFM Cloud) as an integration
    source: https://www.talkdesk.com/integrations/
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
    name: Workato
    provider: workato
    says: lists Workato as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zendesk
    provider: zendesk
    says: lists Zendesk as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zoho CRM
    provider: zoho-crm
    says: lists Zoho CRM as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: common
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: domain
    name: Zoom Phone
    provider: zoom-phone
    says: lists Zoom Phone as an integration
    source: https://www.talkdesk.com/integrations/
    tier: declared
  kind: commercial
  name: Talkdesk
  page: /applications/voip-call-center/talkdesk/
  slug: talkdesk
  url: https://www.talkdesk.com/
- anchor: dialpad
  counts:
    declared: 5
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.dialpad.com/integrations/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Gmail
    provider: google-gmail
    says: lists Gmail as an integration
    source: https://www.dialpad.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Google Calendar
    provider: google-calendar
    says: lists Google Calendar as an integration
    source: https://www.dialpad.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://www.dialpad.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://www.dialpad.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zendesk
    provider: zendesk
    says: lists Zendesk as an integration
    source: https://www.dialpad.com/integrations/
    tier: declared
  kind: commercial
  name: Dialpad
  page: /applications/voip-call-center/dialpad/
  slug: dialpad
  url: https://www.dialpad.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: voip-call-center
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Communication
  store: google-play
  url: https://play.google.com/store/apps/category/COMMUNICATION
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Communication - SIP
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#communication---sip
- category: Customer Service
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Calling
  store: hubspot-marketplace
  url: https://ecosystem.hubspot.com/marketplace/apps
- category: Phone & SMS
  store: zapier
  url: https://zapier.com/apps
name: VoIP, Phone & Contact Center
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.10
    key: AE-150.50.10
    name: Programmable Voice
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  fit: exact
  layer: domain
  why: PSTN/SIP carriage and call control -- the substrate every softphone and CPaaS sits on
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.10
    key: AE-110.30.10
    name: Speech-to-Text
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  fit: exact
  layer: domain
  why: live transcription for voice bots, IVR and call analytics; jambonz alone wires 17 STT vendors
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.20
    key: AE-110.30.20
    name: Text-to-Speech
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  fit: exact
  layer: domain
  why: prompts and voice-agent output
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.40
    key: AE-110.30.40
    name: Meeting Notes & Conversation Intelligence
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  fit: exact
  layer: domain
  why: call recording analysis, coaching and summaries (Gong, Fireflies, Avoma)
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: click-to-dial, screen-pop and call logging into the CRM -- the largest integration block in every commercial app
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'helpdesk CTI: calls become tickets'
- capability:
    attribution: Turbo EA
    id: BC-600.30
    key: it-service-management
    name: IT Service Management
    url: /capabilities/it-service-management/
    via_parent: null
  fit: exact
  layer: domain
  why: ServiceNow CTI for IT service desks
- capability:
    attribution: Turbo EA
    id: BC-410
    key: sales-management
    name: Sales Management
    url: /capabilities/sales-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: sales engagement cadences that place and log calls (Outreach, Salesloft, Apollo)
- capability:
    attribution: Turbo EA
    id: BC-430.30.30
    key: BC-430.30.30
    name: Quality Monitoring and Coaching
    url: /capabilities/contact-centre-operations-management/
    via_parent: Contact Centre Operations Management
  fit: exact
  layer: domain
  why: contact-center call QA scoring (Klaus)
- capability:
    attribution: Turbo EA
    id: BC-430.30.10
    key: BC-430.30.10
    name: Contact Centre Workforce Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: Contact Centre Operations Management
  fit: exact
  layer: domain
  why: contact-center WFM (Verint)
- capability:
    attribution: Turbo EA
    id: BC-2900.60
    key: BC-2900.60
    name: Healthcare Interoperability Operations
    url: /capabilities/healthcare-interoperability-operations/
    via_parent: null
  fit: exact
  layer: domain
  why: 'Talkdesk healthcare vertical: EHR integrations (Epic, Oracle Health, athenahealth)'
- capability:
    attribution: Turbo EA
    id: BC-2160
    key: insurance-claims-management
    name: Insurance Claims Management
    url: /capabilities/insurance-claims-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'Talkdesk insurance vertical: Guidewire ClaimCenter'
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: SMS alongside voice (notifications, two-way texting)
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: WhatsApp channel next to voice
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: exact
  layer: common
  why: call notifications and calling inside Slack / Teams
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: common
  why: Zoom bridge in Talkdesk
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: common
  why: Gmail / Outlook / Google Calendar / contacts for caller context
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  fit: exact
  layer: common
  why: Calendly booking from calls
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: Zapier / Make / Pipedream / Workato / Tray for everything not built in
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: common
  why: call data exported to warehouses and dashboards
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: Fonoster bills its hosted platform through Stripe
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: LLM behind voice agents (Fonoster Autopilot, jambonz LLM verb)
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring / APM in the mobile apps
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: app telemetry in the mobile apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  fit: exact
  layer: common
  why: realtime messaging in the mobile apps
- capability:
    attribution: API Evangelist extension
    id: AE-954
    key: AE-954
    name: Sales Engagement & Sequencing
    url: /capabilities/sales-engagement-sequencing/
    via_parent: null
  fit: exact
  layer: domain
  why: Outreach, Salesloft (Sales Engagement & Sequencing)
stack:
- capabilities:
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
      - Aircall
      - Dialpad
      - JustCall
      - Talkdesk
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      - https://www.dialpad.com/integrations/
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Aircall
      - Dialpad
      - JustCall
      - Talkdesk
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      - https://www.dialpad.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 43.3
      apps:
      - Aircall
      - JustCall
      - Talkdesk
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        status: none
      name: Zoho CRM
      slug: zoho-crm
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - CRM
      - Lead Management
      - Marketing Automation
      - Sales
      tier: declared
      url: /providers/zoho-crm/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Aircall
      - JustCall
      - Talkdesk
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: Pipedrive
      slug: pipedrive
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - CRM
      - Pipeline Management
      - Sales
      - Software-as-a-Service
      tier: declared
      url: /providers/pipedrive/
    - agent_band: agent-ready
      agent_readiness: 51.0
      apps:
      - Aircall
      - JustCall
      band: exemplar
      in_catalog: true
      kin_score: 81.1
      mcp:
        source: https://developers.activecampaign.com/page/mcp
        status: documented
      name: ActiveCampaign
      slug: activecampaign
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - CRM
      - Email Marketing
      - Marketing Automation
      - Sales Automation
      tier: declared
      url: /providers/activecampaign/
    - agent_band: agent-ready
      agent_readiness: 30.0
      apps:
      - Aircall
      - JustCall
      band: exemplar
      in_catalog: true
      kin_score: 72.8
      mcp:
        status: none
      name: Zendesk Sell
      slug: zendesk-sell
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - CRM
      - Leads
      - Sales
      - Sales Automation
      tier: declared
      url: /providers/zendesk-sell/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Aircall
      - Talkdesk
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        source: https://github.com/microsoft/Dataverse-MCP
        status: verified
      name: Microsoft Dynamics
      slug: microsoft-dynamics-365
      sources:
      - https://aircall.io/integrations/
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - Business Applications
      - CRM
      - Cloud
      - Enterprise
      tier: declared
      url: /providers/microsoft-dynamics-365/
    - agent_band: agent-ready
      agent_readiness: 37.5
      apps:
      - Aircall
      - JustCall
      band: exemplar
      in_catalog: true
      kin_score: 66.9
      mcp:
        source: https://marketplace.gohighlevel.com/docs/other/mcp/index.html
        status: verified
      name: HighLevel
      slug: highlevel
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - CRM
      - Company
      - Marketing
      - Software-as-a-Service
      tier: declared
      url: /providers/highlevel/
    - agent_band: agent-ready
      agent_readiness: 44.5
      apps:
      - JustCall
      - Talkdesk
      band: strong
      in_catalog: true
      kin_score: 65.0
      mcp:
        status: none
      name: Keap
      slug: keap
      sources:
      - https://justcall.io/integrations/
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - CRM
      - Marketing Automation
      - Sales
      - Small Business
      tier: declared
      url: /providers/keap/
    - agent_band: agent-aware
      agent_readiness: 26.7
      apps:
      - Aircall
      - JustCall
      band: developing
      in_catalog: true
      kin_score: 46.2
      mcp:
        status: none
      name: Copper
      slug: copper
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - Activities
      - Companies
      - Contact Relationship Management
      - Contacts
      tier: declared
      url: /providers/copper/
    - agent_band: agent-aware
      agent_readiness: 19.7
      apps:
      - Aircall
      - JustCall
      band: thin
      in_catalog: true
      kin_score: 36.2
      mcp:
        status: none
      name: Freshsales
      slug: freshsales
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - CRM
      - Contacts
      - Deals
      - Sales
      tier: declared
      url: /providers/freshsales/
    - agent_band: agent-ready
      agent_readiness: 50.3
      apps:
      - Aircall
      - JustCall
      band: thin
      in_catalog: true
      kin_score: 32.2
      mcp:
        source: https://github.com/mondaycom/mcp
        status: verified
      name: monday.com
      slug: monday-com
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - Automation
      - CRM
      - GraphQL
      - Work Management
      tier: declared
      url: /providers/monday-com/
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - Aircall
      - JustCall
      band: thin
      in_catalog: true
      kin_score: 27.6
      mcp:
        status: none
      name: Odoo
      slug: odoo
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - Business Applications
      - CRM
      - ERP
      - Open Source
      tier: declared
      url: /providers/odoo/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Aircall
      - JustCall
      band: emerging
      in_catalog: true
      kin_score: 20.0
      mcp:
        source: https://docs.attio.com/mcp/overview
        status: verified
      name: Attio
      slug: attio
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - CRM
      - Companies
      - Contacts
      - Sales
      tier: declared
      url: /providers/attio/
    - agent_band: agent-ready
      agent_readiness: 58.1
      apps:
      - JustCall
      band: exemplar
      in_catalog: true
      kin_score: 77.2
      mcp:
        source: https://developer.close.com/mcp
        status: verified
      name: Close
      slug: close
      sources:
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - CRM
      - Calling
      - Inside Sales
      - Sales Engagement
      tier: declared
      url: /providers/close/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Aircall
      - Dialpad
      - JustCall
      - Talkdesk
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk CTI
      slug: zendesk
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      - https://www.dialpad.com/integrations/
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Aircall
      - JustCall
      - Talkdesk
      band: developing
      in_catalog: true
      kin_score: 53.6
      mcp:
        source: https://dev.frontapp.com/docs/mcp
        status: documented
      name: Front
      slug: front
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - Customer Operations
      - Customer Service
      - Email
      - Inbox
      tier: declared
      url: /providers/front/
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - Aircall
      - JustCall
      - Talkdesk
      band: developing
      in_catalog: true
      kin_score: 51.5
      mcp:
        status: none
      name: Help Scout
      slug: helpscout
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - Customer Service
      - Email
      - Help Desk
      - Live Chat
      tier: declared
      url: /providers/helpscout/
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Aircall
      - JustCall
      - Talkdesk
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: declared
      url: /providers/intercom/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Aircall
      - JustCall
      - Talkdesk
      band: thin
      in_catalog: true
      kin_score: 29.7
      mcp:
        status: none
      name: Freshdesk
      slug: freshdesk
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - Application
      - Automation
      - Customer Service
      - Help Desk
      tier: declared
      url: /providers/freshdesk/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Aircall
      - JustCall
      - Talkdesk
      band: thin
      in_catalog: true
      kin_score: 26.4
      mcp:
        status: none
      name: Kustomer
      slug: kustomer
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - CRM
      - Customer Service
      - Help Desk
      - Messaging
      tier: declared
      url: /providers/kustomer/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Aircall
      - JustCall
      band: developing
      in_catalog: true
      kin_score: 42.5
      mcp:
        source: https://github.com/gorgias/mcp-cookbook
        status: verified
      name: Gorgias
      slug: gorgias
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - Customer Service
      - E-Commerce
      - Help Desk
      - Shopify
      tier: declared
      url: /providers/gorgias/
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - Aircall
      - JustCall
      band: thin
      in_catalog: true
      kin_score: 28.2
      mcp:
        source: https://www.zoho.com/mcp/
        status: verified
      name: Zoho Desk
      slug: zoho-desk
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - Customer Service
      - Help Desk
      - Knowledge Base
      - Ticketing
      tier: declared
      url: /providers/zoho-desk/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Aircall
      band: emerging
      in_catalog: true
      kin_score: 12.2
      mcp:
        status: none
      name: Nicereply
      slug: nicereply
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - CES
      - CSAT
      - NPS
      - Surveys
      tier: declared
      url: /providers/nicereply/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    providers:
    - agent_band: agent-ready
      agent_readiness: 60.4
      apps:
      - Fonoster
      - jambonz
      band: exemplar
      in_catalog: true
      kin_score: 83.2
      mcp:
        source: https://github.com/elevenlabs/elevenlabs-mcp
        status: verified
      name: ElevenLabs
      slug: elevenlabs
      sources:
      - https://github.com/fonoster/fonoster/tree/main/mods/apiserver/src/voice/tts
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags:
      - Artificial Intelligence
      - Speech-to-Text
      - Text-to-Speech
      - Voice
      tier: observed
      url: /providers/elevenlabs/
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Fonoster
      - jambonz
      band: exemplar
      in_catalog: true
      kin_score: 68.6
      mcp:
        status: none
      name: Google
      slug: google-cloud-text-to-speech
      sources:
      - https://github.com/fonoster/fonoster/tree/main/mods/apiserver/src/voice/tts
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags:
      - Audio
      - Google Cloud
      - Machine Learning
      - Speech Synthesis
      tier: observed
      url: /providers/google-cloud-text-to-speech/
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - Fonoster
      - jambonz
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp: &id005
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Azure Speech
      slug: azure-ai-speech
      sources:
      - https://github.com/fonoster/fonoster/tree/main/mods/apiserver/src/voice/tts
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags: &id006
      - Artificial Intelligence
      - Cloud
      - Microsoft
      - Speech
      tier: observed
      url: /providers/azure-ai-speech/
    - agent_band: agent-ready
      agent_readiness: 35.9
      apps:
      - Fonoster
      - jambonz
      band: developing
      in_catalog: true
      kin_score: 48.2
      mcp: &id001
        source: https://github.com/deepgram/mcp
        status: verified
      name: Deepgram
      slug: deepgram
      sources:
      - https://github.com/fonoster/fonoster/tree/main/mods/apiserver/src/voice/tts
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags: &id002
      - Artificial Intelligence
      - Speech-to-Text
      - Text-to-Speech
      - Transcription
      tier: observed
      url: /providers/deepgram/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - jambonz
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: &id003
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI (Whisper/TTS)
      slug: openai
      sources:
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags: &id004
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 39.7
      apps:
      - jambonz
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        status: none
      name: AWS Polly
      slug: amazon-polly
      sources:
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags:
      - Amazon Web Services
      - Artificial Intelligence
      - Machine Learning
      - Speech Synthesis
      tier: observed
      url: /providers/amazon-polly/
    - agent_band: agent-ready
      agent_readiness: 29.1
      apps:
      - jambonz
      band: strong
      in_catalog: true
      kin_score: 58.2
      mcp:
        status: none
      name: KugelAudio
      slug: kugelaudio
      sources:
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags:
      - Speech Synthesis
      - Text-to-Speech
      - Voice
      - Voice AI
      tier: observed
      url: /providers/kugelaudio/
    - agent_band: agent-ready
      agent_readiness: 29.6
      apps:
      - jambonz
      band: developing
      in_catalog: true
      kin_score: 54.2
      mcp:
        status: none
      name: Gradium
      slug: gradium
      sources:
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Text-to-Speech
      - Voice AI
      tier: observed
      url: /providers/gradium/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - jambonz
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Mistral
      slug: mistral
      sources:
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags:
      - Agents
      - Embeddings
      - Machine Learning
      - OCR
      tier: observed
      url: /providers/mistral/
    - agent_band: agent-ready
      agent_readiness: 29.0
      apps:
      - jambonz
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp: &id007
        source: https://github.com/cartesia-ai/cartesia-mcp
        status: verified
      name: Cartesia
      slug: cartesia-ai
      sources:
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags: &id008
      - Artificial Intelligence
      - Speech-to-Text
      - Text-to-Speech
      - Voice AI
      tier: observed
      url: /providers/cartesia-ai/
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - jambonz
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        source: https://github.com/wellsaid-labs/wellsaid-mcp
        status: verified
      name: WellSaid Labs
      slug: wellsaid
      sources:
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags:
      - Artificial Intelligence
      - Audio
      - Text-to-Speech
      - Voice
      tier: observed
      url: /providers/wellsaid/
    - agent_band: agent-ready
      agent_readiness: 51.9
      apps:
      - jambonz
      band: thin
      in_catalog: true
      kin_score: 33.1
      mcp:
        status: none
      name: Fish Audio
      slug: fish-audio
      sources:
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags:
      - Speech-to-Text
      - Text-to-Speech
      - Voice
      - Voice Cloning
      tier: observed
      url: /providers/fish-audio/
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - jambonz
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        status: none
      name: xAI
      slug: xai
      sources:
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags:
      - Artificial Intelligence
      - Foundation Models
      - Grok
      - LLM
      tier: observed
      url: /providers/xai/
    - agent_band: agent-aware
      agent_readiness: 26.1
      apps:
      - jambonz
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        source: https://github.com/resemble-ai/resemble-mcp
        status: verified
      name: Resemble AI
      slug: resemble-ai
      sources:
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags:
      - Artificial Intelligence
      - Text-to-Speech
      - Voice
      - Voice Cloning
      tier: observed
      url: /providers/resemble-ai/
    - agent_band: agent-ready
      agent_readiness: 29.1
      apps:
      - jambonz
      band: thin
      in_catalog: true
      kin_score: 30.6
      mcp:
        status: none
      name: Inworld
      slug: inworld
      sources:
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags:
      - Artificial Intelligence
      - Characters
      - Games
      - Voice
      tier: observed
      url: /providers/inworld/
    - agent_band: agent-aware
      agent_readiness: 16.3
      apps:
      - jambonz
      band: thin
      in_catalog: true
      kin_score: 28.3
      mcp:
        source: https://github.com/murf-ai/murf-mcp
        status: verified
      name: Murf
      slug: murf
      sources:
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags:
      - Artificial Intelligence
      - Text-to-Speech
      - Voice
      - Voiceover
      tier: observed
      url: /providers/murf/
    - agent_band: agent-aware
      agent_readiness: 19.1
      apps:
      - jambonz
      band: thin
      in_catalog: true
      kin_score: 27.0
      mcp:
        status: none
      name: Speechify
      slug: speechify
      sources:
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags:
      - Artificial Intelligence
      - Speech Synthesis
      - Text-to-Speech
      - Voice
      tier: observed
      url: /providers/speechify/
    - agent_band: agent-ready
      agent_readiness: 38.1
      apps:
      - jambonz
      band: emerging
      in_catalog: true
      kin_score: 18.3
      mcp:
        status: none
      name: Rime Labs
      slug: rime-ai
      sources:
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags:
      - Artificial Intelligence
      - Real-Time
      - Text-to-Speech
      - Voice
      tier: observed
      url: /providers/rime-ai/
    - agent_band: agent-aware
      agent_readiness: 5.2
      apps:
      - jambonz
      band: minimal
      in_catalog: true
      kin_score: 9.9
      mcp: &id009
        status: none
      name: NVIDIA Riva
      slug: nvidia
      sources:
      - https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
      status: profiled
      tags: &id010
      - Artificial Intelligence
      - Computing
      - GPU
      - Machine Learning
      tier: observed
      url: /providers/nvidia/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.10
      key: AE-110.30.10
      name: Speech-to-Text
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.8
      apps:
      - Fonoster
      - jambonz
      band: exemplar
      in_catalog: true
      kin_score: 68.9
      mcp:
        status: none
      name: Google
      slug: google-cloud-speech-to-text
      sources:
      - https://github.com/fonoster/fonoster/tree/main/mods/apiserver/src/voice/stt
      - https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
      status: profiled
      tags:
      - Audio Processing
      - Google Cloud
      - Machine Learning
      - Speech Recognition
      tier: observed
      url: /providers/google-cloud-speech-to-text/
    - agent_band: agent-ready
      agent_readiness: 35.9
      apps:
      - Fonoster
      - jambonz
      band: developing
      in_catalog: true
      kin_score: 48.2
      mcp: *id001
      name: Deepgram
      slug: deepgram
      sources:
      - https://github.com/fonoster/fonoster/tree/main/mods/apiserver/src/voice/stt
      - https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/deepgram/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - jambonz
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: *id003
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 34.5
      apps:
      - jambonz
      band: exemplar
      in_catalog: true
      kin_score: 75.6
      mcp:
        status: none
      name: AWS (Transcribe)
      slug: amazon-transcribe
      sources:
      - https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
      status: profiled
      tags:
      - Amazon Web Services
      - Audio Processing
      - Machine Learning
      - Speech Recognition
      tier: observed
      url: /providers/amazon-transcribe/
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - jambonz
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp: *id005
      name: Microsoft Azure Speech
      slug: azure-ai-speech
      sources:
      - https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/azure-ai-speech/
    - agent_band: agent-ready
      agent_readiness: 33.6
      apps:
      - jambonz
      band: developing
      in_catalog: true
      kin_score: 49.4
      mcp:
        source: https://github.com/gladiaio/gladia-mcp
        status: verified
      name: Gladia
      slug: gladia
      sources:
      - https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
      status: profiled
      tags:
      - Audio Intelligence
      - Real-Time
      - Speech-to-Text
      - Transcription
      tier: observed
      url: /providers/gladia/
    - agent_band: agent-aware
      agent_readiness: 27.9
      apps:
      - jambonz
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Nuance
      slug: nuance
      sources:
      - https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
      status: profiled
      tags:
      - Company
      - Conversational AI
      - Natural Language Understanding
      - Speech Recognition
      tier: observed
      url: /providers/nuance/
    - agent_band: agent-ready
      agent_readiness: 39.0
      apps:
      - jambonz
      band: developing
      in_catalog: true
      kin_score: 46.4
      mcp:
        source: https://github.com/AssemblyAI/assemblyai-mcp
        status: verified
      name: AssemblyAI
      slug: assemblyai
      sources:
      - https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
      status: profiled
      tags:
      - Artificial Intelligence
      - Audio
      - Speech
      - Transcription
      tier: observed
      url: /providers/assemblyai/
    - agent_band: agent-aware
      agent_readiness: 26.3
      apps:
      - jambonz
      band: developing
      in_catalog: true
      kin_score: 44.9
      mcp:
        status: none
      name: Speechmatics
      slug: speechmatics
      sources:
      - https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
      status: profiled
      tags:
      - Real-Time Transcription
      - Speech Recognition
      - Speech-to-Text
      - Transcription
      tier: observed
      url: /providers/speechmatics/
    - agent_band: agent-ready
      agent_readiness: 29.0
      apps:
      - jambonz
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp: *id007
      name: Cartesia
      slug: cartesia-ai
      sources:
      - https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/cartesia-ai/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - jambonz
      band: thin
      in_catalog: true
      kin_score: 31.9
      mcp:
        status: none
      name: Soniox
      slug: soniox
      sources:
      - https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
      status: profiled
      tags:
      - Multilingual
      - Real-Time
      - Speech AI
      - Streaming
      tier: observed
      url: /providers/soniox/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - jambonz
      band: thin
      in_catalog: true
      kin_score: 29.2
      mcp:
        status: none
      name: Voxist
      slug: voxist
      sources:
      - https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
      status: profiled
      tags:
      - Company
      - European
      - Speech AI
      - Voice Technology
      tier: observed
      url: /providers/voxist/
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - jambonz
      band: emerging
      in_catalog: true
      kin_score: 25.3
      mcp:
        status: unknown
      name: Cobalt Speech
      slug: cobalt-speech
      sources:
      - https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Speech
      - Transcription
      tier: observed
      url: /providers/cobalt-speech/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - jambonz
      band: emerging
      in_catalog: true
      kin_score: 20.9
      mcp:
        status: none
      name: Houndify (SoundHound)
      slug: soundhound
      sources:
      - https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
      status: profiled
      tags:
      - Audio Intelligence
      - Conversational AI
      - Music Recognition
      - Voice AI
      tier: observed
      url: /providers/soundhound/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - jambonz
      band: emerging
      in_catalog: true
      kin_score: 18.5
      mcp:
        status: none
      name: IBM Watson
      slug: ibm-watson
      sources:
      - https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
      status: profiled
      tags:
      - Artificial Intelligence
      - IBM
      - Machine Learning
      - Natural Language Processing
      tier: observed
      url: /providers/ibm-watson/
    - agent_band: agent-aware
      agent_readiness: 5.2
      apps:
      - jambonz
      band: minimal
      in_catalog: true
      kin_score: 9.9
      mcp: *id009
      name: NVIDIA Riva
      slug: nvidia
      sources:
      - https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
      status: profiled
      tags: *id010
      tier: observed
      url: /providers/nvidia/
    - agent_band: null
      agent_readiness: null
      apps:
      - jambonz
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Verbio
      slug: verbio
      sources:
      - https://github.com/jambonz/jambonz-feature-server/blob/main/lib/utils/transcription-utils.js
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.40
      key: AE-110.30.40
      name: Meeting Notes & Conversation Intelligence
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.4
      apps:
      - Aircall
      - JustCall
      band: exemplar
      in_catalog: true
      kin_score: 73.1
      mcp:
        source: https://docs.fireflies.ai/mcp-tools/overview
        status: verified
      name: Fireflies
      slug: fireflies
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Meeting Assistant
      - Summary
      - Transcription
      tier: declared
      url: /providers/fireflies/
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - Aircall
      - JustCall
      band: exemplar
      in_catalog: true
      kin_score: 66.5
      mcp:
        status: none
      name: Gong
      slug: gong
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - Analytics
      - Conversations
      - Revenue Intelligence
      - Sales
      tier: declared
      url: /providers/gong/
    - agent_band: agent-ready
      agent_readiness: 43.7
      apps:
      - Aircall
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        source: https://www.avoma.com/agentic-platform/mcp
        status: documented
      name: Avoma
      slug: avoma
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Automation
      - Meeting Assistant
      - Sales Enablement
      tier: declared
      url: /providers/avoma/
  - capability:
      attribution: API Evangelist extension
      id: AE-954
      key: AE-954
      name: Sales Engagement & Sequencing
      url: /capabilities/sales-engagement-sequencing/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Aircall
      - JustCall
      - Talkdesk
      band: exemplar
      in_catalog: true
      kin_score: 78.7
      mcp:
        status: none
      name: Outreach
      slug: outreach
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - CRM
      - Sales
      - Sales Engagement
      - Sequences
      tier: declared
      url: /providers/outreach/
    - agent_band: agent-native
      agent_readiness: 44.4
      apps:
      - Aircall
      - JustCall
      band: strong
      in_catalog: true
      kin_score: 62.7
      mcp:
        status: none
      name: Salesloft
      slug: salesloft
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - CRM
      - Cadences
      - Sales
      - Sales Engagement
      tier: declared
      url: /providers/salesloft/
  - capability:
      attribution: Turbo EA
      id: BC-2900.60
      key: BC-2900.60
      name: Healthcare Interoperability Operations
      url: /capabilities/healthcare-interoperability-operations/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.3
      apps:
      - Talkdesk
      band: exemplar
      in_catalog: true
      kin_score: 67.5
      mcp:
        status: none
      name: athenahealth
      slug: athenahealth
      sources:
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - Electronic Health Records
      - Healthcare
      - Practice Management
      - Revenue Cycle Management
      tier: declared
      url: /providers/athenahealth/
    - agent_band: agent-ready
      agent_readiness: 36.8
      apps:
      - Talkdesk
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        status: none
      name: Epic
      slug: epic-systems
      sources:
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - Electronic Health Records
      - FHIR
      - Healthcare
      - United States
      tier: declared
      url: /providers/epic-systems/
    - agent_band: agent-ready
      agent_readiness: 32.2
      apps:
      - Talkdesk
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Oracle Cerner
      slug: oracle-health
      sources:
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - Bulk FHIR
      - CapabilityStatement
      - CareAware
      - Cerner Millennium
      tier: declared
      url: /providers/oracle-health/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    providers:
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - Fonoster
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp: &id011
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/fonoster/fonoster/blob/main/mods/appbridge/src/protocols/twilio.ts
      status: profiled
      tags: &id012
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-ready
      agent_readiness: 54.3
      apps:
      - Talkdesk
      band: exemplar
      in_catalog: true
      kin_score: 69.1
      mcp:
        status: none
      name: Zoom Phone
      slug: zoom-phone
      sources:
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - Cloud PBX
      - Telecommunications
      - UCaaS
      - United States
      tier: declared
      url: /providers/zoom-phone/
  - capability:
      attribution: Turbo EA
      id: BC-430.30.10
      key: BC-430.30.10
      name: Contact Centre Workforce Management
      url: /capabilities/contact-centre-operations-management/
      via_parent: Contact Centre Operations Management
    providers:
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Talkdesk
      band: minimal
      in_catalog: true
      kin_score: 7.9
      mcp:
        status: none
      name: Verint (WFM Cloud)
      slug: verint-systems
      sources:
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Customer Engagement
      - Security
      tier: declared
      url: /providers/verint-systems/
  - capability:
      attribution: Turbo EA
      id: BC-600.30
      key: it-service-management
      name: IT Service Management
      url: /capabilities/it-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - Talkdesk
      band: strong
      in_catalog: true
      kin_score: 61.9
      mcp:
        status: none
      name: ServiceNow
      slug: servicenow
      sources:
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - Automation
      - Cloud Services
      - Digital Workflows
      - ServiceNow
      tier: declared
      url: /providers/servicenow/
  - capability:
      attribution: Turbo EA
      id: BC-2160
      key: insurance-claims-management
      name: Insurance Claims Management
      url: /capabilities/insurance-claims-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 41.2
      apps:
      - Talkdesk
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Guidewire ClaimCenter
      slug: guidewire
      sources:
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - Billing
      - Claims
      - Insurance
      - Policy
      tier: declared
      url: /providers/guidewire/
  - capability:
      attribution: Turbo EA
      id: BC-430.30.30
      key: BC-430.30.30
      name: Quality Monitoring and Coaching
      url: /capabilities/contact-centre-operations-management/
      via_parent: Contact Centre Operations Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - Aircall
      band: strong
      in_catalog: true
      kin_score: 60.3
      mcp:
        status: none
      name: Klaus
      slug: klaus
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Company
      - Customer Experience
      - Customer Service
      - Quality Assurance
      tier: declared
      url: /providers/klaus/
  - capability:
      attribution: Turbo EA
      id: BC-410
      key: sales-management
      name: Sales Management
      url: /capabilities/sales-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 58.0
      apps:
      - JustCall
      band: exemplar
      in_catalog: true
      kin_score: 68.6
      mcp:
        source: https://docs.apollo.io/docs/apollo-mcp
        status: verified
      name: Apollo.io
      slug: apollo-io
      sources:
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - B2B Data
      - Engagement
      - Prospecting
      - Sales Intelligence
      tier: declared
      url: /providers/apollo-io/
  layer: domain
- capabilities:
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
      - Aircall
      - JustCall
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 31.1
      apps:
      - Aircall
      - JustCall
      band: strong
      in_catalog: true
      kin_score: 65.5
      mcp:
        source: https://pipedream.com/docs/connect/mcp
        status: verified
      name: Pipedream
      slug: pipedream
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - Connect
      - Pipedream
      - Pro-Code-API-Composition
      - Workflows
      tier: declared
      url: /providers/pipedream/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Aircall
      - JustCall
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
    - agent_band: agent-ready
      agent_readiness: 60.3
      apps:
      - Aircall
      band: exemplar
      in_catalog: true
      kin_score: 89.5
      mcp:
        source: https://docs.tray.ai/
        status: documented
      name: Tray.io
      slug: tray-ai
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - AI Agents
      - Automation
      - Integration
      - iPaaS
      tier: declared
      url: /providers/tray-ai/
    - agent_band: agent-ready
      agent_readiness: 53.8
      apps:
      - Talkdesk
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://docs.workato.com/mcp.html
        status: verified
      name: Workato
      slug: workato
      sources:
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - AI Agents
      - API Management
      - Automation
      - B2B
      tier: declared
      url: /providers/workato/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Dialpad
      - JustCall
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://justcall.io/integrations/
      - https://www.dialpad.com/integrations/
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: declared
      url: /providers/google-calendar/
    - agent_band: agent-ready
      agent_readiness: 38.2
      apps:
      - JustCall
      - Talkdesk
      band: strong
      in_catalog: true
      kin_score: 57.2
      mcp:
        source: https://docs.cloud.google.com/mcp/supported-products
        status: verified
      name: Google Contacts
      slug: google-people
      sources:
      - https://justcall.io/integrations/
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - Address Book
      - Contacts
      - Google
      - People
      tier: declared
      url: /providers/google-people/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - JustCall
      band: exemplar
      in_catalog: true
      kin_score: 70.8
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Outlook
      slug: microsoft-outlook
      sources:
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - Calendar
      - Contacts
      - Email
      - Enterprise
      tier: declared
      url: /providers/microsoft-outlook/
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - Dialpad
      band: exemplar
      in_catalog: true
      kin_score: 66.8
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://www.dialpad.com/integrations/
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: declared
      url: /providers/google-gmail/
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
      - Aircall
      - JustCall
      - Talkdesk
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Aircall
      - Talkdesk
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://aircall.io/integrations/
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: declared
      url: /providers/microsoft-teams/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.2
      apps:
      - Aircall
      - JustCall
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp:
        source: https://github.com/fivetran/fivetran-mcp
        status: verified
      name: Fivetran
      slug: fivetran
      sources:
      - https://aircall.io/integrations/
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - Connectors
      - Data Integration
      - Data Pipeline
      - ETL
      tier: declared
      url: /providers/fivetran/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Aircall
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: declared
      url: /providers/segment/
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - Aircall
      band: thin
      in_catalog: true
      kin_score: 35.2
      mcp:
        source: https://www.geckoboard.com/product/metrics-mcp/
        status: verified
      name: Geckoboard
      slug: geckoboard
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Business Intelligence
      - Dashboards
      - Data Visualization
      - KPI Tracking
      tier: declared
      url: /providers/geckoboard/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - Fonoster
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp: *id011
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/fonoster/fonoster/blob/main/mods/common/src/notifications/createSendSmsTwilioImpl.ts
      status: profiled
      tags: *id012
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-native
      agent_readiness: 60.3
      apps:
      - Aircall
      band: exemplar
      in_catalog: true
      kin_score: 71.6
      mcp:
        source: https://github.com/sinch/sinch-mcp-server
        status: verified
      name: Sinch Engage
      slug: sinch
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Communications
      - Messaging
      - SMS
      - Voice
      tier: declared
      url: /providers/sinch/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Aircall
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id013
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.aircall/latest/
      status: profiled
      tags: &id014
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Fonoster
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/fonoster/fonoster/tree/main/mods/billing/src/stripe
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Aircall
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id013
      name: Firebase
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.aircall/latest/
      status: profiled
      tags: *id014
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - Aircall
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Pusher
      slug: pusher
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.aircall/latest/
      status: profiled
      tags:
      - Pub/Sub
      - Push Notifications
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/pusher/
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.4
      apps:
      - JustCall
      band: developing
      in_catalog: true
      kin_score: 47.5
      mcp:
        source: https://developer.calendly.com/calendly-mcp-server
        status: documented
      name: Calendly
      slug: calendly
      sources:
      - https://justcall.io/integrations/
      status: profiled
      tags:
      - Appointments
      - Automation
      - Booking
      - Calendar
      tier: declared
      url: /providers/calendly/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Talkdesk
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://www.talkdesk.com/integrations/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: declared
      url: /providers/zoom/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Aircall
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: WhatsApp Messaging Channel
      slug: whatsapp
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: declared
      url: /providers/whatsapp/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Fonoster
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: '@langchain/anthropic'
      slug: anthropic
      sources:
      - https://github.com/fonoster/fonoster/blob/main/mods/autopilot/package.json
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Fonoster
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: *id003
      name: '@langchain/openai'
      slug: openai
      sources:
      - https://github.com/fonoster/fonoster/blob/main/mods/autopilot/package.json
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Fonoster
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: '@langchain/google-genai'
      slug: google-gemini
      sources:
      - https://github.com/fonoster/fonoster/blob/main/mods/autopilot/package.json
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Fonoster
      band: thin
      in_catalog: true
      kin_score: 37.7
      mcp:
        status: none
      name: '@langchain/ollama'
      slug: ollama
      sources:
      - https://github.com/fonoster/fonoster/blob/main/mods/autopilot/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - LLM
      - Models
      - Ollama
      tier: observed
      url: /providers/ollama/
    - agent_band: agent-aware
      agent_readiness: 21.2
      apps:
      - Fonoster
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        source: https://github.com/groq/groq-mcp-server
        status: verified
      name: '@langchain/groq'
      slug: groq
      sources:
      - https://github.com/fonoster/fonoster/blob/main/mods/autopilot/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Inference
      - LLM
      - LPU
      tier: observed
      url: /providers/groq/
  layer: agent
summary:
  coverage_pct: 98.9
  declared_only: 56
  distinct_providers: 95
  in_catalog: 94
  mcp:
    documented: 5
    none: 48
    unchecked: 1
    verified: 40
  mcp_verified: 40
  mean_kin_score: 53.6
  observed: 39
  queued: 1
  reference_apps: 6
title: 'VoIP, Phone & Contact Center: application blueprint'
---
