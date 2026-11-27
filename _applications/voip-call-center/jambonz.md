---
app: jambonz
app_slug: jambonz
app_url: https://github.com/jambonz/jambonz-feature-server
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.30.10
  key: AE-110.30.10
  layer: domain
  name: Speech-to-Text
  providers:
  - AssemblyAI
  - AWS (Transcribe)
  - Cartesia
  - Cobalt Speech
  - Deepgram
  - Gladia
  - Google
  - Houndify (SoundHound)
  - IBM Watson
  - Microsoft Azure Speech
  - Nuance
  - NVIDIA Riva
  - OpenAI
  - Soniox
  - Speechmatics
  - Verbio
  - Voxist
  url: /capabilities/speech-voice/
  via_parent: Speech & Voice
- attribution: API Evangelist extension
  id: AE-110.30.20
  key: AE-110.30.20
  layer: domain
  name: Text-to-Speech
  providers:
  - AWS Polly
  - Cartesia
  - Deepgram
  - ElevenLabs
  - Fish Audio
  - Google
  - Gradium
  - Inworld
  - KugelAudio
  - Microsoft Azure Speech
  - Mistral
  - Murf
  - NVIDIA Riva
  - OpenAI (Whisper/TTS)
  - Resemble AI
  - Rime Labs
  - Speechify
  - WellSaid Labs
  - xAI
  url: /capabilities/speech-voice/
  via_parent: Speech & Voice
category:
  id: voip-call-center
  name: VoIP, Phone & Contact Center
  url: /applications/voip-call-center/
counts:
  declared: 0
  observed: 36
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 39.0
    band: developing
    in_catalog: true
    kin_score: 46.4
    mcp: &id006
      source: https://github.com/AssemblyAI/assemblyai-mcp
      status: verified
    slug: assemblyai
    status: profiled
    tags: &id007
    - Artificial Intelligence
    - Audio
    - Speech
    - Transcription
    url: /providers/assemblyai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.5
    band: exemplar
    in_catalog: true
    kin_score: 75.6
    mcp: &id008
      status: none
    slug: amazon-transcribe
    status: profiled
    tags: &id009
    - Amazon Web Services
    - Audio Processing
    - Machine Learning
    - Speech Recognition
    url: /providers/amazon-transcribe/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 39.7
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id010
      status: none
    slug: amazon-polly
    status: profiled
    tags: &id011
    - Amazon Web Services
    - Artificial Intelligence
    - Machine Learning
    - Speech Synthesis
    url: /providers/amazon-polly/
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
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 29.0
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id012
      source: https://github.com/cartesia-ai/cartesia-mcp
      status: verified
    slug: cartesia-ai
    status: profiled
    tags: &id013
    - Artificial Intelligence
    - Speech-to-Text
    - Text-to-Speech
    - Voice AI
    url: /providers/cartesia-ai/
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
  facts: *id001
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: emerging
    in_catalog: true
    kin_score: 25.3
    mcp: &id014
      status: unknown
    slug: cobalt-speech
    status: profiled
    tags: &id015
    - Artificial Intelligence
    - Company
    - Speech
    - Transcription
    url: /providers/cobalt-speech/
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
  facts: &id002
    agent_band: agent-ready
    agent_readiness: 35.9
    band: developing
    in_catalog: true
    kin_score: 48.2
    mcp: &id016
      source: https://github.com/deepgram/mcp
      status: verified
    slug: deepgram
    status: profiled
    tags: &id017
    - Artificial Intelligence
    - Speech-to-Text
    - Text-to-Speech
    - Transcription
    url: /providers/deepgram/
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
  facts: *id002
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
  facts:
    agent_band: agent-ready
    agent_readiness: 60.4
    band: exemplar
    in_catalog: true
    kin_score: 83.2
    mcp: &id018
      source: https://github.com/elevenlabs/elevenlabs-mcp
      status: verified
    slug: elevenlabs
    status: profiled
    tags: &id019
    - Artificial Intelligence
    - Speech-to-Text
    - Text-to-Speech
    - Voice
    url: /providers/elevenlabs/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 51.9
    band: thin
    in_catalog: true
    kin_score: 33.1
    mcp: &id020
      status: none
    slug: fish-audio
    status: profiled
    tags: &id021
    - Speech-to-Text
    - Text-to-Speech
    - Voice
    - Voice Cloning
    url: /providers/fish-audio/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.6
    band: developing
    in_catalog: true
    kin_score: 49.4
    mcp: &id022
      source: https://github.com/gladiaio/gladia-mcp
      status: verified
    slug: gladia
    status: profiled
    tags: &id023
    - Audio Intelligence
    - Real-Time
    - Speech-to-Text
    - Transcription
    url: /providers/gladia/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id024
      status: none
    slug: google-cloud-speech-to-text
    status: profiled
    tags: &id025
    - Audio Processing
    - Google Cloud
    - Machine Learning
    - Speech Recognition
    url: /providers/google-cloud-speech-to-text/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.8
    band: exemplar
    in_catalog: true
    kin_score: 68.6
    mcp: &id026
      status: none
    slug: google-cloud-text-to-speech
    status: profiled
    tags: &id027
    - Audio
    - Google Cloud
    - Machine Learning
    - Speech Synthesis
    url: /providers/google-cloud-text-to-speech/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.6
    band: developing
    in_catalog: true
    kin_score: 54.2
    mcp: &id028
      status: none
    slug: gradium
    status: profiled
    tags: &id029
    - Artificial Intelligence
    - Company
    - Text-to-Speech
    - Voice AI
    url: /providers/gradium/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 20.9
    mcp: &id030
      status: none
    slug: soundhound
    status: profiled
    tags: &id031
    - Audio Intelligence
    - Conversational AI
    - Music Recognition
    - Voice AI
    url: /providers/soundhound/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 18.5
    mcp: &id032
      status: none
    slug: ibm-watson
    status: profiled
    tags: &id033
    - Artificial Intelligence
    - IBM
    - Machine Learning
    - Natural Language Processing
    url: /providers/ibm-watson/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.1
    band: thin
    in_catalog: true
    kin_score: 30.6
    mcp: &id034
      status: none
    slug: inworld
    status: profiled
    tags: &id035
    - Artificial Intelligence
    - Characters
    - Games
    - Voice
    url: /providers/inworld/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.1
    band: strong
    in_catalog: true
    kin_score: 58.2
    mcp: &id036
      status: none
    slug: kugelaudio
    status: profiled
    tags: &id037
    - Speech Synthesis
    - Text-to-Speech
    - Voice
    - Voice AI
    url: /providers/kugelaudio/
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
  facts: &id003
    agent_band: agent-aware
    agent_readiness: 25.8
    band: strong
    in_catalog: true
    kin_score: 57.9
    mcp: &id038
      source: https://github.com/microsoft/mcp
      status: verified
    slug: azure-ai-speech
    status: profiled
    tags: &id039
    - Artificial Intelligence
    - Cloud
    - Microsoft
    - Speech
    url: /providers/azure-ai-speech/
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
  facts: *id003
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id040
      status: none
    slug: mistral
    status: profiled
    tags: &id041
    - Agents
    - Embeddings
    - Machine Learning
    - OCR
    url: /providers/mistral/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.3
    band: thin
    in_catalog: true
    kin_score: 28.3
    mcp: &id042
      source: https://github.com/murf-ai/murf-mcp
      status: verified
    slug: murf
    status: profiled
    tags: &id043
    - Artificial Intelligence
    - Text-to-Speech
    - Voice
    - Voiceover
    url: /providers/murf/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.9
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id044
      status: none
    slug: nuance
    status: profiled
    tags: &id045
    - Company
    - Conversational AI
    - Natural Language Understanding
    - Speech Recognition
    url: /providers/nuance/
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
  facts: &id004
    agent_band: agent-aware
    agent_readiness: 5.2
    band: minimal
    in_catalog: true
    kin_score: 9.9
    mcp: &id046
      status: none
    slug: nvidia
    status: profiled
    tags: &id047
    - Artificial Intelligence
    - Computing
    - GPU
    - Machine Learning
    url: /providers/nvidia/
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
  facts: *id004
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
  facts: &id005
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id048
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id049
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
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
  facts: *id005
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.1
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id050
      source: https://github.com/resemble-ai/resemble-mcp
      status: verified
    slug: resemble-ai
    status: profiled
    tags: &id051
    - Artificial Intelligence
    - Text-to-Speech
    - Voice
    - Voice Cloning
    url: /providers/resemble-ai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.1
    band: emerging
    in_catalog: true
    kin_score: 18.3
    mcp: &id052
      status: none
    slug: rime-ai
    status: profiled
    tags: &id053
    - Artificial Intelligence
    - Real-Time
    - Text-to-Speech
    - Voice
    url: /providers/rime-ai/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: thin
    in_catalog: true
    kin_score: 31.9
    mcp: &id054
      status: none
    slug: soniox
    status: profiled
    tags: &id055
    - Multilingual
    - Real-Time
    - Speech AI
    - Streaming
    url: /providers/soniox/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.1
    band: thin
    in_catalog: true
    kin_score: 27.0
    mcp: &id056
      status: none
    slug: speechify
    status: profiled
    tags: &id057
    - Artificial Intelligence
    - Speech Synthesis
    - Text-to-Speech
    - Voice
    url: /providers/speechify/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.3
    band: developing
    in_catalog: true
    kin_score: 44.9
    mcp: &id058
      status: none
    slug: speechmatics
    status: profiled
    tags: &id059
    - Real-Time Transcription
    - Speech Recognition
    - Speech-to-Text
    - Transcription
    url: /providers/speechmatics/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id060
      status: unchecked
    slug: verbio
    status: queued for profiling
    tags: &id061 []
    url: null
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: thin
    in_catalog: true
    kin_score: 29.2
    mcp: &id062
      status: none
    slug: voxist
    status: profiled
    tags: &id063
    - Company
    - European
    - Speech AI
    - Voice Technology
    url: /providers/voxist/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.9
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id064
      source: https://github.com/wellsaid-labs/wellsaid-mcp
      status: verified
    slug: wellsaid
    status: profiled
    tags: &id065
    - Artificial Intelligence
    - Audio
    - Text-to-Speech
    - Voice
    url: /providers/wellsaid/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 39.4
    band: thin
    in_catalog: true
    kin_score: 32.3
    mcp: &id066
      status: none
    slug: xai
    status: profiled
    tags: &id067
    - Artificial Intelligence
    - Foundation Models
    - Grok
    - LLM
    url: /providers/xai/
  layer: domain
  name: xAI
  provider: xai
  says: ships the xAI SDK or integration code
  source: https://github.com/jambonz/speech-utils/blob/main/lib/synth-audio.js
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/voip-call-center/jambonz/
providers:
- agent_band: agent-ready
  agent_readiness: 39.0
  band: developing
  in_catalog: true
  kin_score: 46.4
  mcp: *id006
  name: AssemblyAI
  slug: assemblyai
  status: profiled
  tags: *id007
  url: /providers/assemblyai/
- agent_band: agent-ready
  agent_readiness: 34.5
  band: exemplar
  in_catalog: true
  kin_score: 75.6
  mcp: *id008
  name: AWS (Transcribe)
  slug: amazon-transcribe
  status: profiled
  tags: *id009
  url: /providers/amazon-transcribe/
- agent_band: agent-ready
  agent_readiness: 39.7
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id010
  name: AWS Polly
  slug: amazon-polly
  status: profiled
  tags: *id011
  url: /providers/amazon-polly/
- agent_band: agent-ready
  agent_readiness: 29.0
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id012
  name: Cartesia
  slug: cartesia-ai
  status: profiled
  tags: *id013
  url: /providers/cartesia-ai/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: emerging
  in_catalog: true
  kin_score: 25.3
  mcp: *id014
  name: Cobalt Speech
  slug: cobalt-speech
  status: profiled
  tags: *id015
  url: /providers/cobalt-speech/
- agent_band: agent-ready
  agent_readiness: 35.9
  band: developing
  in_catalog: true
  kin_score: 48.2
  mcp: *id016
  name: Deepgram
  slug: deepgram
  status: profiled
  tags: *id017
  url: /providers/deepgram/
- agent_band: agent-ready
  agent_readiness: 60.4
  band: exemplar
  in_catalog: true
  kin_score: 83.2
  mcp: *id018
  name: ElevenLabs
  slug: elevenlabs
  status: profiled
  tags: *id019
  url: /providers/elevenlabs/
- agent_band: agent-ready
  agent_readiness: 51.9
  band: thin
  in_catalog: true
  kin_score: 33.1
  mcp: *id020
  name: Fish Audio
  slug: fish-audio
  status: profiled
  tags: *id021
  url: /providers/fish-audio/
- agent_band: agent-ready
  agent_readiness: 33.6
  band: developing
  in_catalog: true
  kin_score: 49.4
  mcp: *id022
  name: Gladia
  slug: gladia
  status: profiled
  tags: *id023
  url: /providers/gladia/
- agent_band: agent-ready
  agent_readiness: 33.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id024
  name: Google
  slug: google-cloud-speech-to-text
  status: profiled
  tags: *id025
  url: /providers/google-cloud-speech-to-text/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: exemplar
  in_catalog: true
  kin_score: 68.6
  mcp: *id026
  name: Google
  slug: google-cloud-text-to-speech
  status: profiled
  tags: *id027
  url: /providers/google-cloud-text-to-speech/
- agent_band: agent-ready
  agent_readiness: 29.6
  band: developing
  in_catalog: true
  kin_score: 54.2
  mcp: *id028
  name: Gradium
  slug: gradium
  status: profiled
  tags: *id029
  url: /providers/gradium/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 20.9
  mcp: *id030
  name: Houndify (SoundHound)
  slug: soundhound
  status: profiled
  tags: *id031
  url: /providers/soundhound/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 18.5
  mcp: *id032
  name: IBM Watson
  slug: ibm-watson
  status: profiled
  tags: *id033
  url: /providers/ibm-watson/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: thin
  in_catalog: true
  kin_score: 30.6
  mcp: *id034
  name: Inworld
  slug: inworld
  status: profiled
  tags: *id035
  url: /providers/inworld/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: strong
  in_catalog: true
  kin_score: 58.2
  mcp: *id036
  name: KugelAudio
  slug: kugelaudio
  status: profiled
  tags: *id037
  url: /providers/kugelaudio/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id038
  name: Microsoft Azure Speech
  slug: azure-ai-speech
  status: profiled
  tags: *id039
  url: /providers/azure-ai-speech/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id040
  name: Mistral
  slug: mistral
  status: profiled
  tags: *id041
  url: /providers/mistral/
- agent_band: agent-aware
  agent_readiness: 16.3
  band: thin
  in_catalog: true
  kin_score: 28.3
  mcp: *id042
  name: Murf
  slug: murf
  status: profiled
  tags: *id043
  url: /providers/murf/
- agent_band: agent-aware
  agent_readiness: 27.9
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id044
  name: Nuance
  slug: nuance
  status: profiled
  tags: *id045
  url: /providers/nuance/
- agent_band: agent-aware
  agent_readiness: 5.2
  band: minimal
  in_catalog: true
  kin_score: 9.9
  mcp: *id046
  name: NVIDIA Riva
  slug: nvidia
  status: profiled
  tags: *id047
  url: /providers/nvidia/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id048
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id049
  url: /providers/openai/
- agent_band: agent-aware
  agent_readiness: 26.1
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id050
  name: Resemble AI
  slug: resemble-ai
  status: profiled
  tags: *id051
  url: /providers/resemble-ai/
- agent_band: agent-ready
  agent_readiness: 38.1
  band: emerging
  in_catalog: true
  kin_score: 18.3
  mcp: *id052
  name: Rime Labs
  slug: rime-ai
  status: profiled
  tags: *id053
  url: /providers/rime-ai/
- agent_band: human-only
  agent_readiness: 2.5
  band: thin
  in_catalog: true
  kin_score: 31.9
  mcp: *id054
  name: Soniox
  slug: soniox
  status: profiled
  tags: *id055
  url: /providers/soniox/
- agent_band: agent-aware
  agent_readiness: 19.1
  band: thin
  in_catalog: true
  kin_score: 27.0
  mcp: *id056
  name: Speechify
  slug: speechify
  status: profiled
  tags: *id057
  url: /providers/speechify/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: developing
  in_catalog: true
  kin_score: 44.9
  mcp: *id058
  name: Speechmatics
  slug: speechmatics
  status: profiled
  tags: *id059
  url: /providers/speechmatics/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id060
  name: Verbio
  slug: verbio
  status: queued for profiling
  tags: *id061
  url: null
- agent_band: agent-aware
  agent_readiness: 18.3
  band: thin
  in_catalog: true
  kin_score: 29.2
  mcp: *id062
  name: Voxist
  slug: voxist
  status: profiled
  tags: *id063
  url: /providers/voxist/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id064
  name: WellSaid Labs
  slug: wellsaid
  status: profiled
  tags: *id065
  url: /providers/wellsaid/
- agent_band: agent-ready
  agent_readiness: 39.4
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id066
  name: xAI
  slug: xai
  status: profiled
  tags: *id067
  url: /providers/xai/
siblings:
- name: Aircall
  rows: 42
  url: /applications/voip-call-center/aircall/
- name: Dialpad
  rows: 5
  url: /applications/voip-call-center/dialpad/
- name: Fonoster
  rows: 14
  url: /applications/voip-call-center/fonoster/
- name: JustCall
  rows: 36
  url: /applications/voip-call-center/justcall/
- name: Talkdesk
  rows: 25
  url: /applications/voip-call-center/talkdesk/
sitemap: true
title: 'jambonz: VoIP, Phone & Contact Center reference app'
---
