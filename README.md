# ElevenLabs CLI Skill

[![ClawHub](https://img.shields.io/badge/ClawHub-elevenlabs--cli-blue?style=flat-square)](https://clawhub.ai/elevenlabs-cli)
[![GitHub](https://img.shields.io/badge/GitHub-hongkongkiwi%2Felevenlabs--cli-black?style=flat-square&logo=github)](https://github.com/hongkongkiwi/elevenlabs-cli)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](https://opensource.org/licenses/MIT)

A ClawHub skill for the [ElevenLabs CLI](https://github.com/hongkongkiwi/elevenlabs-cli) - an unofficial command-line interface for the ElevenLabs AI audio platform.

## About

This skill provides AI agents with knowledge of how to use the ElevenLabs CLI for:
- Text-to-speech generation with 100+ voices
- Speech-to-text transcription with speaker diarization
- Voice cloning from audio samples
- Sound effects generation
- Audio isolation (noise removal)
- Voice changing
- Dubbing projects
- Agent management

## Installation

### Via ClawHub

```bash
clawhub install elevenlabs-cli
```

### Manual

Copy `SKILL.md` to your skills directory.

## Prerequisites

- **ElevenLabs API key** - Get one free at [ElevenLabs API Keys](https://elevenlabs.io/app/settings/api-keys)

```bash
export ELEVENLABS_API_KEY="your-api-key"
```

## Security & Privacy

- Your API key is sent only to `api.elevenlabs.io`
- Audio/text content is sent to ElevenLabs API for processing
- No local persistence beyond specified output files
- No telemetry or third-party data sharing

## Related Repositories

| Repository | Purpose |
|------------|---------|
| [elevenlabs-cli](https://github.com/hongkongkiwi/elevenlabs-cli) | Main CLI source code |
| [homebrew-elevenlabs-cli](https://github.com/hongkongkiwi/homebrew-elevenlabs-cli) | Homebrew tap |
| [scoop-elevenlabs-cli](https://github.com/hongkongkiwi/scoop-elevenlabs-cli) | Scoop bucket |

## License

MIT
