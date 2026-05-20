<p align="center">
  <a href="https://github.com/laufferw/bro-pi">
    <img alt="bro-pi logo" src="https://pi.dev/logo-auto.svg" width="128">
  </a>
</p>
<p align="center">
  <a href="https://discord.com/invite/3cU7Bz4UPx"><img alt="Discord" src="https://img.shields.io/badge/discord-community-5865F2?style=flat-square&logo=discord&logoColor=white" /></a>
</p>

---

# Bro-Pi: Your Fitness & Strength Expert

Bro-Pi is a fork of [pi](https://github.com/badlogic/pi-mono) customized as a fitness-focused coding agent. It specializes in:

- **Strength Training** - Powerlifting, Olympic lifting, hypertrophy
- **Conditioning** - HIIT, circuits, conditioning work
- **Weightlifting** - Technique, programming, periodization
- **Running** - Training plans, pacing, race preparation

Bro is inspired by the work of:
- **Cody Lefever** (General Gains)
- **Dan John**
- **Steve Magness**
- **Jim Wendler**
- **David Roche**

## What is Bro-Pi?

Bro-Pi helps you with:

- Building training programs and periodization
- Analyzing lifting technique
- Creating conditioning protocols
- Designing running plans
- Programming for strength and hypertrophy
- Tracking progress and adjusting volumes

## Key Packages

| Package | Description |
|---------|-------------|
| **[@earendil-works/pi-coding-agent](packages/coding-agent)** | Interactive coding agent CLI |
| **[@earendil-works/pi-agent-core](packages/agent)** | Agent runtime with tool calling and state management |
| **[@earendil-works/pi-ai](packages/ai)** | Unified multi-provider LLM API |

## Getting Started

```bash
npm install          # Install all dependencies
npm run build        # Build all packages
./test.sh            # Run tests
./pi-test.sh         # Run bro-pi from source
```

## Using Bro-Pi

```bash
# Run from source
./pi-test.sh

# Or use the CLI after building
bro_pi
```

Bro-Pi understands fitness terminology, training principles, and can help with:
- Programming for strength sports
- Designing conditioning circuits
- Creating running training plans
- Analyzing training data
- Building spreadsheets for tracking

## Contributing

This is a personal fork. PRs welcome but be aware this is focused on fitness applications.

## License

MIT